Max Int32
===
[![NPM version][npm-image]][npm-url] [![Build Status][build-image]][build-url] [![Coverage Status][coverage-image]][coverage-url] [![Dependencies][dependencies-image]][dependencies-url]

> Maximum [signed 32-bit integer][max-int32].


## Installation

``` bash
$ npm install const-max-int32
```


## Usage

``` javascript
var MAX_INT32 = require( 'const-max-int32' );
```

#### MAX_INT32

Maximum signed 32-bit integer.

``` javascript
MAX_INT32 === Math.pow( 2, 31 ) - 1;
```


## Examples

``` javascript
var MAX_INT32 = require( 'const-max-int32' );

console.log( MAX_INT32 );
// returns 2147483647
```

To run the example code from the top-level application directory,

``` bash
$ node ./examples/index.js
```


---
## Tests

### Unit

This repository uses [tape][tape] for unit tests. To run the tests, execute the following command in the top-level application directory:

``` bash
$ make test
```

All new feature development should have corresponding unit tests to validate correct functionality.


### Test Coverage

This repository uses [Istanbul][istanbul] as its code coverage tool. To generate a test coverage report, execute the following command in the top-level application directory:

``` bash
$ make test-cov
```

Istanbul creates a `./reports/coverage` directory. To access an HTML version of the report,

``` bash
$ make view-cov
```


### Browser Support

This repository uses [Testling][testling] for browser testing. To run the tests in a (headless) local web browser, execute the following command in the top-level application directory:

``` bash
$ make test-browsers
```

To view the tests in a local web browser,

``` bash
$ make view-browser-tests
```

<!-- [![browser support][browsers-image]][browsers-url] -->


---
## License

[MIT license](http://opensource.org/licenses/MIT). 


## Copyright

Copyright &copy; 2015-2016. The [Compute.io][compute-io] Authors.


[npm-image]: http://img.shields.io/npm/v/const-max-int32.svg
[npm-url]: https://npmjs.org/package/const-max-int32

[build-image]: http://img.shields.io/travis/const-io/max-int32/master.svg
[build-url]: https://travis-ci.org/const-io/max-int32

[coverage-image]: https://img.shields.io/codecov/c/github/const-io/max-int32/master.svg
[coverage-url]: https://codecov.io/github/const-io/max-int32?branch=master

[dependencies-image]: http://img.shields.io/david/const-io/max-int32.svg
[dependencies-url]: https://david-dm.org/const-io/max-int32

[dev-dependencies-image]: http://img.shields.io/david/dev/const-io/max-int32.svg
[dev-dependencies-url]: https://david-dm.org/dev/const-io/max-int32

[github-issues-image]: http://img.shields.io/github/issues/const-io/max-int32.svg
[github-issues-url]: https://github.com/const-io/max-int32/issues

[tape]: https://github.com/substack/tape
[istanbul]: https://github.com/gotwarlost/istanbul
[testling]: https://ci.testling.com

[compute-io]: https://github.com/compute-io
[max-int32]: http://en.wikipedia.org/wiki/2147483647
