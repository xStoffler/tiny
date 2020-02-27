# tiny
The tiniest npm module

<img alt="npm (scoped)" src="https://img.shields.io/npm/v/@stoffler/tiny">

Removes all spaces from a string.

## Install

```
$ npm install @stoffler/tiny
```

## Usage

```js
const tiny = require("@stoffler/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
