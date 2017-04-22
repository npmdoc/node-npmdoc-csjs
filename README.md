# npmdoc-csjs

#### api documentation for  [csjs (v1.1.0)](https://github.com/rtsao/csjs)  [![npm package](https://img.shields.io/npm/v/npmdoc-csjs.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-csjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-csjs.svg)](https://travis-ci.org/npmdoc/node-npmdoc-csjs)

#### Cascading Style JavaScripts

[![NPM](https://nodei.co/npm/csjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/csjs)

- [https://npmdoc.github.io/node-npmdoc-csjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-csjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-csjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-csjs/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-csjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-csjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ryan Tsao"
    },
    "bugs": {
        "url": "https://github.com/rtsao/csjs/issues"
    },
    "dependencies": {},
    "description": "Cascading Style JavaScripts",
    "devDependencies": {
        "brfs": "^1.4.2",
        "bulk-require": "^0.2.1",
        "bulkify": "^1.1.1",
        "coveralls": "^2.11.4",
        "folderify": "https://github.com/rtsao/folderify/tarball/patch-1",
        "include-folder": "^1.0.0",
        "istanbul": "^0.4.0",
        "tape": "^4.2.0",
        "zuul": "^3.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "1b5753c6bd902da269deb369215585a5d8f1f380",
        "tarball": "https://registry.npmjs.org/csjs/-/csjs-1.1.0.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "37e5eacbab9c98d038002076af29628feab8365e",
    "homepage": "https://github.com/rtsao/csjs",
    "keywords": [
        "csjs",
        "css-modules",
        "scoped-css",
        "css-in-js",
        "modular-css",
        "css"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "rtsao"
        }
    ],
    "name": "csjs",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/rtsao/csjs.git"
    },
    "scripts": {
        "cover": "istanbul cover test/index.js",
        "test": "node test/index.js",
        "travis-test": "npm run cover && ((cat coverage/lcov.info | coveralls) || exit 0)",
        "travis-test-browser": "zuul -- test/index.js"
    },
    "version": "1.1.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
