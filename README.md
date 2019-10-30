# demo_pkg
demo_pkg


# @rituvesh/demo_pkg

[![npm (scoped)](https://img.shields.io/npm/v/@rituvesh/demo_pkg.svg)](https://www.npmjs.com/package/@rituvesh/demo_pkg)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@rituvesh/demo_pkg.svg)](https://www.npmjs.com/package/@rituvesh/demo_pkg)

Demo return 
## Install

```
$ npm install @rituvesh/demo_pkg
```

## Usage

```js
const demoPkg = require("@rituvesh/demo_pkg");

demoPkg();
//=> "Hi!, return from demo_pkg"


```
#### run below commands to create very basic npm package
##### login to your npm account
```js
npm adduser
npm login
```
##### Create basic files and directory 
```js
mkdir demo_pkg
cd demo_pkg
touch package.json
```
##### add below to package.json 
```
{
  "name": "@rituvesh/demo_pkg",
  "version": "1.0.0"
}
```
##### finally publish it public
``` 
npm publish --access=public
```

##### and see the package at 

[demo_pkg](https://www.npmjs.com/package/@rituvesh/demo_pkg)
