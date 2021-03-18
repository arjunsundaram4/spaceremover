https://img.shields.io/npm/v/@arjunsundaram4/spaceremover
# @arjunsundaram4/spaceremover

[![npm (scoped)](https://img.shields.io/npm/v/@arjunsundaram4/spaceremover)](https://img.shields.io/npm/v/@arjunsundaram4/spaceremover)
[![npm bundle size (minified)](https://img.shields.io/npm/v/@arjunsundaram4/spaceremover)](https://img.shields.io/npm/v/@arjunsundaram4/spaceremover)

Removes all spaces from a string.

## Install

```
$ npm install @arjunsundaram4/spaceremover
```

## Usage

```js
const tiny = require("@arjunsundaram4/spaceremover");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
