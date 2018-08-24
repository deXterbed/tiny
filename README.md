# @themadkhajit/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@themadkhajit/tiny.svg)](https://www.npmjs.com/package/@themadkhajit/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@themadkhajit/tiny.svg)](https://www.npmjs.com/package/@themadkhajit/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @themadkhajit/tiny
```

## Usage

```js
const tiny = require("@themadkhajit/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```