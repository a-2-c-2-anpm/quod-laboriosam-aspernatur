# @a-2-c-2-anpm/quod-laboriosam-aspernatur <sup>[![Version Badge][2]][1]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][5]][6]
[![dev dependency status][7]][8]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][11]][1]

Determine if the JS environment has Symbol support. Supports spec, or shams.

## Example

```js
var hasSymbols = require('@a-2-c-2-anpm/quod-laboriosam-aspernatur');

hasSymbols() === true; // if the environment has native Symbol support. Not polyfillable, not forgeable.

var hasSymbolsKinda = require('@a-2-c-2-anpm/quod-laboriosam-aspernatur/shams');
hasSymbolsKinda() === true; // if the environment has a Symbol sham that mostly follows the spec.
```

## Supported Symbol shams
 - get-own-property-symbols [npm](https://www.npmjs.com/package/get-own-property-symbols) | [github](https://github.com/WebReflection/get-own-property-symbols)
 - core-js [npm](https://www.npmjs.com/package/core-js) | [github](https://github.com/zloirock/core-js)

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[1]: https://npmjs.org/package/@a-2-c-2-anpm/quod-laboriosam-aspernatur
[2]: https://versionbadg.es/inspect-js/@a-2-c-2-anpm/quod-laboriosam-aspernatur.svg
[5]: https://david-dm.org/inspect-js/@a-2-c-2-anpm/quod-laboriosam-aspernatur.svg
[6]: https://david-dm.org/inspect-js/@a-2-c-2-anpm/quod-laboriosam-aspernatur
[7]: https://david-dm.org/inspect-js/@a-2-c-2-anpm/quod-laboriosam-aspernatur/dev-status.svg
[8]: https://david-dm.org/inspect-js/@a-2-c-2-anpm/quod-laboriosam-aspernatur#info=devDependencies
[11]: https://nodei.co/npm/@a-2-c-2-anpm/quod-laboriosam-aspernatur.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@a-2-c-2-anpm/quod-laboriosam-aspernatur.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@a-2-c-2-anpm/quod-laboriosam-aspernatur.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@a-2-c-2-anpm/quod-laboriosam-aspernatur
[codecov-image]: https://codecov.io/gh/inspect-js/@a-2-c-2-anpm/quod-laboriosam-aspernatur/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@a-2-c-2-anpm/quod-laboriosam-aspernatur/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@a-2-c-2-anpm/quod-laboriosam-aspernatur
[actions-url]: https://github.com/a-2-c-2-anpm/quod-laboriosam-aspernatur/actions
