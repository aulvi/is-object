# is-object <sup>[![Version Badge][12]][npm-url]</sup>

[![build status][travis-svg]][travis-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][13]][npm-url]

[![browser support][testling-png]][testling-url]

Checks whether a value is an object

Because `typeof null` is a troll.

## Example

```js
var isObject = require('is-object');
var assert = require('assert');

assert.equal(isObject(null), false);
assert.equal(isObject({}), true);
```

## Installation

`npm install is-object`

## Contributors

 - [Raynos][7]
 - [Jordan Harband][8]

## MIT Licensed

  [travis-svg]: https://secure.travis-ci.org/ljharb/is-object.svg
  [travis-url]: http://travis-ci.org/ljharb/is-object
  [deps-svg]: http://david-dm.org/ljharb/is-object/status.svg
  [deps-url]: http://david-dm.org/ljharb/is-object
  [testling-png]: http://ci.testling.com/ljharb/is-object.png
  [testling-url]: http://ci.testling.com/ljharb/is-object
  [7]: https://github.com/Raynos
  [8]: https://github.com/ljharb
  [dev-deps-svg]: https://david-dm.org/ljharb/is-object/dev-status.svg
  [dev-deps-url]: https://david-dm.org/ljharb/is-object#info=devDependencies
  [npm-url]: https://npmjs.org/package/is-object
  [12]: http://vb.teelaun.ch/ljharb/is-object.svg
  [13]: https://nodei.co/npm/is-object.png?downloads=true&stars=true
[license-image]: http://img.shields.io/npm/l/is-object.svg
[license-url]: LICENSE
[downloads-image]: http://img.shields.io/npm/dm/is-object.svg
[downloads-url]: http://npm-stat.com/charts.html?package=is-object

