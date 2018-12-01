
[![AUR version](https://img.shields.io/npm/v/@alfsnd/tiny.svg)](https://github.com/Sandalf/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/react.svg)](https://github.com/Sandalf/tiny)

# @alfsnd/tiny
Removes all spaces from a string

# Install

```shell
npm install @alfsnd/tiny
```

# Usage

```js
const tiny = require("@alfsnd/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//      at tiny (<anonymous>:2:41)
//      at <anonymous>:1:1
```