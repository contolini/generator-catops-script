# CatOps Hubot Script Generator [![Build Status][travis-image]][travis-url] [![NPM version][npm-image]][npm-url]

:cat: A Yeoman generator for creating Hubot scripts with brain storage, environment variables and robust mocha tests.

## Installation

First, install [Yeoman](http://yeoman.io) and generator-catops-script using [npm](https://www.npmjs.com/) (we assume you have pre-installed [node.js](https://nodejs.org/)).

```bash
npm install -g yo generator-catops-script
```

Then generate your new Hubot script:

```bash
mkdir hubot-awesome-script
cd hubot-awesome-script
yo catops-script
```

Run your script's tests with: `npm test`
Watch for file changes and run tests automatically with: `npm run watch`

## Contributing

Please read our general [contributing guidelines](CONTRIBUTING.md).

## Open source licensing info

1. [TERMS](TERMS.md)
2. [LICENSE](LICENSE)
3. [CFPB Source Code Policy](https://github.com/cfpb/source-code-policy/)

[npm-image]: https://img.shields.io/npm/v/generator-catops-script.svg?maxAge=2592000&style=flat-square
[npm-url]: https://www.npmjs.com/package/generator-catops-script
[travis-image]: https://img.shields.io/travis/catops/generator-catops-script.svg?maxAge=2592000&style=flat-square
[travis-url]: https://travis-ci.org/catops/generator-catops-script
