# generator-typescript-service [![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Dependency Status][daviddm-image]][daviddm-url]
scaffolds a new TypeScript NodeJs service
mostly for internal use at my company but feel free to use it as well ;)

## Installation

First, install [Yeoman](http://yeoman.io) and generator-typescript-service using [npm](https://www.npmjs.com/) (we assume you have pre-installed [node.js](https://nodejs.org/)).

```bash
npm install -g yo
npm install -g generator-typescript-service
```

Then generate your new project:

```bash
yo typescript-service
```

And up you go!

```
yarn build && yarn start
```

## Environment Variables

  * APPINSIGHTS_KEY: your appinsights key so we can setup basic logging for you
  * PORT: the server will listen to port 8000 by default, you can override this with any non reserved (<1024) port here

## Getting To Know Yeoman

 * Yeoman has a heart of gold.
 * Yeoman is a person with feelings and opinions, but is very easy to work with.
 * Yeoman can be too opinionated at times but is easily convinced not to be.
 * Feel free to [learn more about Yeoman](http://yeoman.io/).

## License

 © [Thomas Klaner](https://github.com/kl4n4)


[npm-image]: https://badge.fury.io/js/generator-typescript-service.svg
[npm-url]: https://npmjs.org/package/generator-typescript-service
[travis-image]: https://travis-ci.org/IWAtech/generator-typescript-service.svg?branch=master
[travis-url]: https://travis-ci.org/IWAtech/generator-typescript-service
[daviddm-image]: https://david-dm.org/IWAtech/generator-typescript-service.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/IWAtech/generator-typescript-service
