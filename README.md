# @dramaorg/aperiam-nostrum-iste <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple cache for a few of the JS Error constructors.

## Example

```js
const assert = require('assert');

const Base = require('@dramaorg/aperiam-nostrum-iste');
const Eval = require('@dramaorg/aperiam-nostrum-iste/eval');
const Range = require('@dramaorg/aperiam-nostrum-iste/range');
const Ref = require('@dramaorg/aperiam-nostrum-iste/ref');
const Syntax = require('@dramaorg/aperiam-nostrum-iste/syntax');
const Type = require('@dramaorg/aperiam-nostrum-iste/type');
const URI = require('@dramaorg/aperiam-nostrum-iste/uri');

assert.equal(Base, Error);
assert.equal(Eval, EvalError);
assert.equal(Range, RangeError);
assert.equal(Ref, ReferenceError);
assert.equal(Syntax, SyntaxError);
assert.equal(Type, TypeError);
assert.equal(URI, URIError);
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

## Security

Please email [@ljharb](https://github.com/ljharb) or see https://tidelift.com/security if you have a potential security vulnerability to report.

[package-url]: https://npmjs.org/package/@dramaorg/aperiam-nostrum-iste
[npm-version-svg]: https://versionbadg.es/ljharb/@dramaorg/aperiam-nostrum-iste.svg
[deps-svg]: https://david-dm.org/ljharb/@dramaorg/aperiam-nostrum-iste.svg
[deps-url]: https://david-dm.org/ljharb/@dramaorg/aperiam-nostrum-iste
[dev-deps-svg]: https://david-dm.org/ljharb/@dramaorg/aperiam-nostrum-iste/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@dramaorg/aperiam-nostrum-iste#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@dramaorg/aperiam-nostrum-iste.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@dramaorg/aperiam-nostrum-iste.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@dramaorg/aperiam-nostrum-iste.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@dramaorg/aperiam-nostrum-iste
[codecov-image]: https://codecov.io/gh/ljharb/@dramaorg/aperiam-nostrum-iste/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@dramaorg/aperiam-nostrum-iste/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@dramaorg/aperiam-nostrum-iste
[actions-url]: https://github.com/dramaorg/aperiam-nostrum-iste/actions
