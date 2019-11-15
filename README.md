
# Vue (Nuxt.js) + Vuetify UI + Firebase Demo

> This is an example of using Nuxt.js with Vuetify and Firebase tools and hosting
> The app is simply search for IMDB movie details using https://www.omdbapi.com API

## Live Demo
[https://nuxt-vuetify-dc3f4.firebaseapp.com](https://nuxt-vuetify-dc3f4.firebaseapp.com)

## Development and Build Setup

``` bash

# install dependencies

$ yarn install

# serve with hot reload at localhost:3000

$ yarn dev

# build for production and launch server

$ yarn build

$ yarn start

# generate static project

$ yarn generate

```
For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org) , [Vuetify](https://vuetifyjs.com/) and [Firebase](https://firebase.google.com/)

## Deploy to Firebase

 1. SignUp at [Firebase console](https://console.firebase.google.com/) if you haven't yet
 2. Create a new project
 3. In your root application folder run `yarn generate` - this will generate the static SPA app in `/dist` folder for the deployment
 4. `npm install -g firebase-tools`
 5. `firebase login`  - this command will open a browser window asking you to choose your Google account, and accept all the required permissions
 6. `firebase init` - this way you will setup your project for the Firebase deployment. When you are asked for `Public directory` you should enter the the build bundle folder (`dist` in our case). Eventually, it would create `firebase.json` and `.firebaserc` in your root folder
 7. `firebase deploy` - your app will be deployed in couple seconds and the app url will be provided