# @chaunguyen4392/tiny
Test tiny npm module

[![npm (scoped)](https://img.shields.io/npm/v/@chaunguyen4392/tiny.svg)](https://www.npmjs.com/package/@chaunguyen4392/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@chaunguyen4392/tiny.svg)](https://www.npmjs.com/package/@chaunguyen4392/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @chaunguyen4392/tiny
```

## Usage

```js
const tiny = require("@chaunguyen4392/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
`` 
