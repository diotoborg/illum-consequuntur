# @diotoborg/illum-consequuntur <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Give a regex, get a robust predicate function that tests it against a string. This will work even if `RegExp.prototype` is altered later.

## Getting started

```sh
npm install --save @diotoborg/illum-consequuntur
```

## Usage/Examples

```js
var regexTester = require('@diotoborg/illum-consequuntur');
var assert = require('assert');

var tester = regexTester('a');
assert.ok(tester('a'));
assert.notOk(tester('b'));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@diotoborg/illum-consequuntur
[npm-version-svg]: https://versionbadg.es/ljharb/@diotoborg/illum-consequuntur.svg
[deps-svg]: https://david-dm.org/ljharb/@diotoborg/illum-consequuntur.svg
[deps-url]: https://david-dm.org/ljharb/@diotoborg/illum-consequuntur
[dev-deps-svg]: https://david-dm.org/ljharb/@diotoborg/illum-consequuntur/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@diotoborg/illum-consequuntur#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@diotoborg/illum-consequuntur.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@diotoborg/illum-consequuntur.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@diotoborg/illum-consequuntur.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@diotoborg/illum-consequuntur
[codecov-image]: https://codecov.io/gh/ljharb/@diotoborg/illum-consequuntur/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@diotoborg/illum-consequuntur/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@diotoborg/illum-consequuntur
[actions-url]: https://github.com/diotoborg/illum-consequuntur/actions
