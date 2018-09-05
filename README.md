# nuxt-firebase-pwa

[Nuxt.js](https://nuxtjs.org) * [Firebase](https://firebase.google.com) = SPA * SSR * PWA * Serverless


## 👻Description

Run the Nuxt.js application on Firebase.

### Features

* SPA (Single Page Application)
* SSR (Sever Side Rendering)
* PWA (Progressive Web Apps)
* Serverless (Cloud Functions for Firebase + Firebase Hosting)

### Libraries

* [Node.js](https://github.com/nodejs/node) v8.11.1
* [Nuxt.js](https://github.com/nuxt/nuxt.js) v1.x


## 👶Start

### Install dependencies

``` bash
$ npm install # Or yarn install
$ cd /path/to/nuxt-firebase-pwa/src && npm install
$ cd /path/to/nuxt-firebase-pwa/functions && npm install
```

### Launch development server

```bash
$ cd /path/to/nuxt-firebase-pwa/src
$ npm run dev
```

Open [http://localhost:3000]()


## 🚀Build and Deploy to Firebase

### Build

Build Nuxt.js app.

```bash
$ cd /path/to/nuxt-firebase-pwa/src
$ npm run build
```

Copy assets and static files.

```bash
$ cd /path/to/nuxt-firebase-pwa
$ npm run setup
```

### Firebase Project Setup

Create a Firebase Project using the [Firebase Console](https://console.firebase.google.com/).

Install Firebase CLI.

```bash
$ npm install -g firebase-tools
$ exec $SHELL -l
```

Login to Firebase.

```bash
$ firebase login
```

Edit `.firebaserc`

```json
{
  "projects": {
    "default": "<your-firebase-project-id>"
  }
}
```

### Emulate Firebase on local

```bash
$ npm run serve
```

Open [http://localhost:5000]()

### Deploy🎉

```bash
$ npm run deploy
```

Let's enjoy!!!
