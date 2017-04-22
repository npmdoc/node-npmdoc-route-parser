# npmdoc-route-parser

#### api documentation for  [route-parser (v0.0.5)](http://github.com/rcs/route-parser)  [![npm package](https://img.shields.io/npm/v/npmdoc-route-parser.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-route-parser) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-route-parser.svg)](https://travis-ci.org/npmdoc/node-npmdoc-route-parser)

#### A isomorphic, bullet-proof, ninja-ready route parsing, matching, and reversing library for Javascript in Node and the browser.

[![NPM](https://nodei.co/npm/route-parser.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/route-parser)

- [https://npmdoc.github.io/node-npmdoc-route-parser/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-route-parser/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-route-parser/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-route-parser/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-route-parser/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-route-parser/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ryan Sorensen",
        "url": "https://github.com/rcs"
    },
    "bugs": {
        "url": "http://github.com/rcs/route-parser/issues"
    },
    "dependencies": {},
    "description": "A isomorphic, bullet-proof, ninja-ready route parsing, matching, and reversing library for Javascript in Node and the browser. ",
    "devDependencies": {
        "chai": "~3.2.0",
        "es5-shim": "~4.1.10",
        "gulp": "~3.9.0",
        "gulp-exec": "~1.0.4",
        "gulp-jshint": "~1.11.2",
        "jison": "~0.4.17",
        "jison-lex": "~0.3.4",
        "jsdoc": "~3.3.0-alpha4",
        "jshint-stylish": "~0.1.5",
        "karma": "~0.12.36",
        "karma-mocha": "~0.1.1",
        "karma-phantomjs-launcher": "~0.2.0",
        "karma-webpack": "~1.6.0",
        "mocha": "~2.2.5",
        "webpack": "~1.10.5",
        "webpack-dev-server": "~1.10.1"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "7d1d09d335e49094031ea16991a4a79b01bbe1f4",
        "tarball": "https://registry.npmjs.org/route-parser/-/route-parser-0.0.5.tgz"
    },
    "engines": {
        "node": ">= 0.9"
    },
    "gitHead": "b91ee9cbb440e6d568430d439f010e6ae634864e",
    "homepage": "http://github.com/rcs/route-parser",
    "keywords": [
        "url",
        "matching",
        "routing",
        "route",
        "regex",
        "match"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "rcs"
        }
    ],
    "name": "route-parser",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/rcs/route-parser.git"
    },
    "scripts": {
        "clean-compile": "rm ./lib/route/compiled-grammar.js",
        "compile-parser": "scripts/compile_parser.js",
        "test": "mocha && karma start --singleRun",
        "test-client": "karma start --singleRun",
        "test-node": "mocha"
    },
    "version": "0.0.5",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
