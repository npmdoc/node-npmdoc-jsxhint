# npmdoc-jsxhint

#### api documentation for  [jsxhint (v0.15.1)](https://github.com/STRML/JSXHint)  [![npm package](https://img.shields.io/npm/v/npmdoc-jsxhint.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-jsxhint) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-jsxhint.svg)](https://travis-ci.org/npmdoc/node-npmdoc-jsxhint)

#### Wrapper for JSHint to allow hinting of JSX files

[![NPM](https://nodei.co/npm/jsxhint.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jsxhint)

- [https://npmdoc.github.io/node-npmdoc-jsxhint/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jsxhint/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jsxhint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jsxhint/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-jsxhint/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-jsxhint/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Samuel Reed"
    },
    "bin": {
        "jsxhint": "./cli.js"
    },
    "bugs": {
        "url": "https://github.com/STRML/JSXHint/issues"
    },
    "contributors": [
        {
            "name": "Casey Foster"
        }
    ],
    "dependencies": {
        "bluebird": "^2.9.14",
        "debug": "~2.1.0",
        "fs-extra": "^0.16.5",
        "glob-all": "^3.0.1",
        "jshint": "^2.6.0",
        "jstransform": "^11.0.1",
        "through": "~2.3.6"
    },
    "description": "Wrapper for JSHint to allow hinting of JSX files",
    "devDependencies": {
        "babel": "^5.4.0",
        "precommit-hook": "~1.0.7",
        "tap": "~0.4.13"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "fa005fb5a4db7cfdc055ef5043b2debb9fe35a54",
        "tarball": "https://registry.npmjs.org/jsxhint/-/jsxhint-0.15.1.tgz"
    },
    "engine": "node >= 0.8",
    "gitHead": "85ad803297347d2779b5c07980ea6d1e2136a953",
    "homepage": "https://github.com/STRML/JSXHint",
    "keywords": [
        "jshint",
        "jsx",
        "react",
        "lint",
        "jslint",
        "reactjs"
    ],
    "license": "MIT",
    "main": "jsxhint.js",
    "maintainers": [
        {
            "name": "strml"
        }
    ],
    "name": "jsxhint",
    "optionalDependencies": {},
    "prefer_global": true,
    "publishConfig": {
        "registry": "https://registry.npmjs.org"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/STRML/JSXHint.git"
    },
    "scripts": {
        "lint": "jshint",
        "test": "node ./node_modules/tap/bin/tap test/test.js"
    },
    "version": "0.15.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
