[![GitHub issues](https://img.shields.io/github/issues/rikyperdana/tiny)](https://github.com/rikyperdana/tiny/issues)
[![GitHub forks](https://img.shields.io/github/forks/rikyperdana/tiny)](https://github.com/rikyperdana/tiny/network)
[![GitHub license](https://img.shields.io/github/license/rikyperdana/tiny)](https://github.com/rikyperdana/tiny)

Removes all spaces from a string.

# Install
`$ npm install @rikyperdana/tiny`

# Usage
```
const tiny = require('@rikyperdana/tiny');

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
