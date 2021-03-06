# EPFL Arrival

A Vue.js project for EPFL's newcomers.

This project serves two aims:
  1. Provide a user friendly website for newcomers to easily find services and resources they might need;
  2. Act as a discovery tools for EPFL employees.

For now, the site is available online on https://ponsfrilus.github.io/EPFLArrival/.

## How to add new tiles
You may want to have a look to the [CONTRIBUTING](https://github.com/ponsfrilus/EPFLArrival/blob/master/CONTRIBUTING.md) guide.

:bulb: **Heads up:** In order to serve your local copy of `tiles.json` you will have to use `npm run local`, while `npm run dev` will serve remote JSON data from [github](https://github.com/ponsfrilus/EPFLArrival/blob/master/data/tiles.json).

### The smart way
It should be pretty straight-forward if you are familiar with github:
  1. [Fork](https://github.com/ponsfrilus/EPFLArrival/fork) the repository,
  1. Edit the [./data/tiles.json](https://github.com/ponsfrilus/EPFLArrival/blob/master/data/tiles.json) file,
  1. Run `npm install`, `npm run local` & `npm run test` to install and check everythings,
  1. Create a [Pull Request](https://help.github.com/articles/about-pull-requests/).

### The new way
Leave me a message on [Telegram](https://telegram.org/) → [@ponsfrilus](https://t.me/ponsfrilus).

### The old way
You can send me a mail once you have tried rly rly hard the others ways.

## Developers

### Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# serve (with local tiles.json) with hot reload at localhost:8080
npm run local

# build for production with minification
npm run build

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
