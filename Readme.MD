# Google-Task-clone

This repository contains the application source code for the project google-task-clone.

## Code style

[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://github.com/feross/standard)

## Tools used along this project

- [React Native](https://reactnative.dev/) as principal mobile framework.
- [@react-navigation](https://reactnavigation.org/) as the navigation in react
  native
- [ES6](http://es6-features.org) as the main language.
- [Async](https://github.com/caolan/async) as async utilities for node and the
  browser
- [Jest](https://jestjs.io/) as a testing framework.
- [@testing-library/react-native](https://testing-library.com/docs/react-native-testing-library/intro/)
  as TDD assertion library.
- [ESLint](http://eslint.org) as JavaScript linter.
- [eslint-config-airbnb](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb)
  as plugin for helping to follow the code style guide
- [Husky](https://github.com/typicode/husky) as git hook to check linter and
  test before commit.

## Screenshots

Include logo/demo screenshot etc.

## Tech used

### Built with

- [React Native](https://reactnative.dev/)
- [React Navigation](https://reactnavigation.org/)
- [Async Storage](https://react-native-async-storage.github.io/async-storage/docs/install/);
- [Formik]();
- [Yup]();

## Requirements

`Node version 15+`
`React Native Cli version 65+`
`gem install cocoapods -v 1.10.1`

## Installation

### Setup vars for environment

**_copy .env.example file with the vars gave by the dev team_**

0. `cp .env.example .env`

1. Cloned off the staging branch.

   ```bash
   gh repo clone repo
   git checkout staging
   ```

2. Install dependencies.

   ```bash
   npm install
   ```

3. iOS dependencies

   ```bash
    cd ios && pod install
   ```

4. iOS dependencies

   ```bash
    cd ios && pod install
   ```

5. Create the keystore.properties file, and ask for the content of this file

```bash
printf 'keyAlias=%s\nkeyPassword=%s\nstoreFile=%s\nstorePassword=%s' $keyAlias $keyPassword $storeFile $storePassword > ./android/keystore.properties
```

6. Ask for the release.keystore

### Running the Application in development

To run the app during development. you will follow the process listed below

- start metro packager run the command below to start the packager in a separate
  terminal console

this must be done in the root directory

```bash
npm start --reset-cache
```

```sh
npm run ios
```

**_create a .netrc file in your home ~ directory and add this the keys in it_**

3.2. Android Studio configuration

3.2.1. Open android studio and install the following dependencies

Android 10 (Q)

Android SDK Platform 29.0.2

Intel x86 Atom_64 System Image or Google APIs Intel x86 Atom System Image

© [tdammy](https://tdammy.com.ng/)
