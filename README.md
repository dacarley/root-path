# root-path

Normalize paths, joined with project's root path

[![NPM Version](http://img.shields.io/npm/v/root-path.svg)](https://www.npmjs.org/package/root-path)

__NOTE:__ The directory with package.json is considered a project's root directory.

## install

```
npm install --save root-path
```

## usage

```js
var root = require('root-path');

var x1 = root();
// returns {PROJECT_ROOT}

var x2 = root('path');
// returns {PROJECT_ROOT}/path

var x3 = root('path1', 'path2');
// returns {PROJECT_ROOT}/path1/path2
```
