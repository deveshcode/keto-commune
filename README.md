<p align="center">
  <img src="https://assets.gqindia.com/photos/601aabe83135acf98278fa9d/3:2/w_1620,h_1080,c_limit/KETO.jpg" alt="Logo"/>
</p>

This is a sample application for building a clone of [Reddit](https://www.reddit.com/). [Link to detailed article about how this was developed](https://www.sitepoint.com/reddit-clone-react-firebase/).

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Overview](#overview)
- [Article](#article)
- [Requirements](#requirements)
- [Installation](#installation)
  - [1. **Clone the application**](#1-clone-the-application)
  - [2. **Install necessary dependencies for the application**](#2-install-necessary-dependencies-for-the-application)
  - [3. **Create a .env file and copy the contents from .env.example**](#3-create-a-env-file-and-copy-the-contents-from-envexample)
  - [4. **Start the application**](#4-start-the-application)
- [Deployment](#deployment)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Overview

This application is built using the following technologies:

1. [Chakra UI](https://chakra-ui.com/)
2. [Emotion](https://emotion.sh/)
3. [Create React App](https://create-react-app.dev/)
4. [Firebase](https://firebase.google.com/)

## Article

[Link to detailed article about how this was developed](https://www.sitepoint.com/reddit-clone-react-firebase/).

## Requirements

1. [Node.js](https://nodejs.org/)
2. [npm](https://www.npmjs.com/)

## Installation

### 1. **Clone the application**

```sh
git clone https://github.com/ghoshnirmalya/reddit-clone
```

### 2. **Install necessary dependencies for the application**

```sh
yarn install
```

### 3. **Create a .env file and copy the contents from .env.example**

### 4. **Start the application**

From the frontend directory, we can run the following command to start our Next.js frontend application:

```sh
yarn start
```

The above command will start the frontend application on [http://localhost:3000/](http://localhost:3000).

## Deployment

Click on the button below to deploy the frontend application on Vercel. You'll need to [sign up for a free Vercel account](https://vercel.com/signup/).

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/import/git?s=https%3A%2F%2Fgithub.com%2Fghoshnirmalya%2Fnextjs-hasura-boilerplate%2Ftree%2Fmaster%2Ffrontend&env=REACT_APP_FIREBASE_API_KEY,REACT_APP_FIREBASE_AUTH_DOMAIN,REACT_APP_FIREBASE_PROJECT_ID,REACT_APP_FIREBASE_STORAGE_BUCKET,REACT_APP_FIREBASE_MESSAGING_SENDER_IDREACT_APP_FIREBASE_APP_ID,REACT_APP_FIREBASE_MEASUREMENT_ID&project-name=reddit-clone&repo-name=reddit-clone)
