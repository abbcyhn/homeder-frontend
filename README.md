# Homeder Frontend

## Frontend Development

### Install Node

Install one of [actively supported versions for Angular 17](https://angular.io/guide/versions) using [NVM](https://github.com/coreybutler/nvm-windows#readme) (recommended) or [official web site](https://nodejs.org/).

### Install Angular CLI

You should not install Angular CLI by yourself, appropriate version (17) will be installed on first `npm run start` call.

Avoid using `ng` directly, use `npm run ng` instead, to make sure you are using the proper Angular CLI version.

### Install dependecies

```sh
npm install
```

### Run application

```sh
npm run start
```

## Frontend Development Guideline

Run following commands before each commit/PR:

```sh
npm run lint
```

```sh
npm run prettier
```
