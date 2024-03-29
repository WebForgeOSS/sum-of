# sum-of

> Returns the sum of the values of the same property off all objects in the supplied list

[![Build Status](https://travis-ci.org/saxjst/sum-of.svg?branch=master)](https://travis-ci.org/saxjst/sum-of)
[![Coverage Status](https://coveralls.io/repos/github/saxjst/sum-of/badge.svg?branch=master)](https://coveralls.io/github/saxjst/sum-of?branch=master)
[![Maintainability](https://api.codeclimate.com/v1/badges/841af7743a474bb61775/maintainability)](https://codeclimate.com/github/saxjst/sum-of/maintainability)
[![Language grade: JavaScript](https://img.shields.io/lgtm/grade/javascript/g/saxjst/sum-of.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/saxjst/sum-of/context:javascript)
[![tested with jest](https://img.shields.io/badge/tested_with-jest-99424f.svg)](https://github.com/facebook/jest)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier/)

## Install

```
$ npm install sum-of
```

## Usage

```js
const sumOf = require("sum-of");

const objects = [{ a: 2 }, { a: 3, b: 1 }];

sumOf(["a"], objects); //=> 5
```

## API

### sumOf ⇒ `Number`

Returns the sum of the values of the same property off all objects in the supplied list

**Returns**: `Number` - sum of the selected properties  
**Sig**: [a] -> [a] -> Number

| Param   | Type       | Description                     |
| ------- | ---------- | ------------------------------- |
| path    | `String[]` | the path to work with           |
| objects | `Object[]` | objects to retrieve values from |

**Example**

```js
sumOf(["a"], [{ a: 2 }, { a: 3, b: 1 }]); //=> 5
```

## License

MIT © [muceres](https://forgetheweb.eu)
