# Nuxt 3 - Firebase - Pinia Minimal Starter Template

This is an example starter project, using Nuxt 3 (composition API) with Firebase and Pinia to auth users in client-side. \
The goal is to make it easy to generate an application that has basic Firebase authentication setup.

Look at below documentations to learn more: \
Nuxt 3: https://nuxt.com/docs/getting-started/introduction \
Firebase Authentication on Web: https://firebase.google.com/docs/auth/web/start

## Firebase setup

You need to create [Firebase](https://firebase.google.com/docs/auth/web/start) account and setup SDK. 

You need to create .env file with this content from Firebase project:

```bash
cp .env.example .env
```

Set environment variable:

```bash
NUXT_PUBLIC_API_KEY=""
```


## Setup

Make sure to install the dependencies:

```bash
# npm
npm install
```

## Development Server

Start the development server on `http://localhost:3000`

```bash
# npm
npm run dev
```

## Production

Build the application for production:

```bash
# npm
npm run build
```

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.
