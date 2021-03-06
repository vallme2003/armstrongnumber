# armstrongnumber [![NPM version](https://img.shields.io/npm/v/armstrongnumber.svg?style=flat)](https://www.npmjs.com/package/armstrongnumber) [![NPM monthly downloads](https://img.shields.io/npm/dm/armstrongnumber.svg?style=flat)](https://npmjs.org/package/armstrongnumber) [![NPM total downloads](https://img.shields.io/npm/dt/armstrongnumber.svg?style=flat)](https://npmjs.org/package/armstrongnumber) [![Linux Build Status](https://img.shields.io/travis/jonschlinkert/armstrongnumber.svg?style=flat&label=Travis)](https://travis-ci.org/jonschlinkert/armstrongnumber)

> Returns true if the given number is an armstrong number, and is an integer that does not exceed the JavaScript MAXIMUM_SAFE_INTEGER.

Please consider following this project's author, [Valliappan Thenappan](https://github.com/vallme2003), and consider starring the project to show your :heart: and support.

## Install

Install with [npm](https://www.npmjs.com/):

```sh
$ npm install --save armstrongnumber
```

## Usage

Works with numbers.

```js
const isArmStrongNumber = require('armstrongnumber');

console.log(isArmStrongNumber(153)); //=> true
console.log(isArmStrongNumber(1)); //=> true

console.log(isArmStrongNumber(2)); //=> false
console.log(isArmStrongNumber(1534)); //=> false
```

## About

<details>
<summary><strong>Contributing</strong></summary>

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](../../issues/new).

</details>

<details>
<summary><strong>Building docs</strong></summary>

_(This project's readme.md is generated by [verb](https://github.com/verbose/verb-generate-readme), please don't edit the readme directly. Any changes to the readme must be made in the [.verb.md](.verb.md) readme template.)_

To generate the readme, run the following command:

```sh
$ npm install -g verbose/verb#dev verb-generate-readme && verb
```

</details>


### Contributors

| **Commits** | **Contributor** | 
| --- | --- |
| 3 | [vallme2003](https://github.com/vallme2003) |

### Author

**Valliappan Thenappan**

* [LinkedIn Profile](https://linkedin.com/in/vallme2003)
* [GitHub Profile](https://github.com/vallme2003)
* [Twitter Profile](https://twitter.com/vallme2003)

### License

Copyright © 2020, [Valliappan Thenappan](https://github.com/vallme2003).
Released under the [ISC License](LICENSE).

***

_This file was generated by [verb-generate-readme](https://github.com/verbose/verb-generate-readme), v0.6.0, on Jun 21, 2020._
