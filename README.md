# npmtest-bson

#### basic test coverage for  [bson (v1.0.4)](https://github.com/mongodb/js-bson#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-bson.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-bson) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-bson.svg)](https://travis-ci.org/npmtest/node-npmtest-bson)

#### A bson parser for node.js and the browser

[![NPM](https://nodei.co/npm/bson.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bson)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-bson/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-bson/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-bson/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-bson/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-bson/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-bson/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-bson/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-bson/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-bson/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-bson/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-bson/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-bson/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-bson/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-bson/build/test-report.html](https://npmtest.github.io/node-npmtest-bson/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-bson/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-bson/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-bson/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bson/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bson/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bson/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-bson/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-bson/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Christian Amor Kvalheim"
    },
    "browser": "lib/bson/bson.js",
    "bugs": {
        "url": "https://github.com/mongodb/js-bson/issues"
    },
    "config": {
        "native": false
    },
    "contributors": [],
    "dependencies": {},
    "description": "A bson parser for node.js and the browser",
    "devDependencies": {
        "babel-core": "^6.14.0",
        "babel-loader": "^6.2.5",
        "babel-polyfill": "^6.13.0",
        "babel-preset-es2015": "^6.14.0",
        "babel-preset-stage-0": "^6.5.0",
        "babel-register": "^6.14.0",
        "benchmark": "1.0.0",
        "colors": "1.1.0",
        "nodeunit": "0.9.0",
        "webpack": "^1.13.2",
        "webpack-polyfills-plugin": "0.0.9"
    },
    "directories": {
        "lib": "./lib/bson"
    },
    "dist": {
        "shasum": "93c10d39eaa5b58415cbc4052f3e53e562b0b72c",
        "tarball": "https://registry.npmjs.org/bson/-/bson-1.0.4.tgz"
    },
    "engines": {
        "node": ">=0.6.19"
    },
    "files": [
        "lib",
        "index.js",
        "browser_build",
        "bower.json"
    ],
    "gitHead": "8dd35ca73c30a2bcab61615ccc5edd053aeb868b",
    "homepage": "https://github.com/mongodb/js-bson#readme",
    "keywords": [
        "mongodb",
        "bson",
        "parser"
    ],
    "license": "Apache-2.0",
    "main": "./index",
    "maintainers": [
        {
            "name": "octave"
        },
        {
            "name": "christkv"
        }
    ],
    "name": "bson",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mongodb/js-bson.git"
    },
    "scripts": {
        "build": "webpack --config ./webpack.dist.config.js",
        "test": "nodeunit ./test/node"
    },
    "version": "1.0.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
