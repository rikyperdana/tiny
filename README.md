![npm](https://img.shields/badge/npm-1.0.0-blue "npm version")
![minified](https://img.shields/badge/minified_size-257_B-blue "minified size")

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
