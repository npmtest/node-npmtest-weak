# npmtest-weak

#### basic test coverage for  [weak (v1.0.1)](https://github.com/TooTallNate/node-weak#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-weak.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-weak) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-weak.svg)](https://travis-ci.org/npmtest/node-npmtest-weak)

#### Make weak references to JavaScript Objects.

[![NPM](https://nodei.co/npm/weak.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/weak)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-weak/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-weak/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-weak/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-weak/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-weak/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-weak/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-weak/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-weak/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-weak/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-weak/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-weak/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-weak/build/test-report.html](https://npmtest.github.io/node-npmtest-weak/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-weak/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-weak/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-weak/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-weak/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-weak/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-weak/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-weak/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-weak/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ben Noordhuis"
    },
    "bugs": {
        "url": "https://github.com/TooTallNate/node-weak/issues"
    },
    "contributors": [
        {
            "name": "Nathan Rajlich",
            "url": "http://tootallnate.net"
        }
    ],
    "dependencies": {
        "bindings": "^1.2.1",
        "nan": "^2.0.5"
    },
    "description": "Make weak references to JavaScript Objects.",
    "devDependencies": {
        "mocha": "~2.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "ab99aab30706959aa0200cb8cf545bb9cb33b99e",
        "tarball": "https://registry.npmjs.org/weak/-/weak-1.0.1.tgz"
    },
    "gitHead": "1c3b0376dab966782e5d1fcf06f9fcb1309cb2c0",
    "gypfile": true,
    "homepage": "https://github.com/TooTallNate/node-weak#readme",
    "keywords": [
        "weak",
        "reference",
        "js",
        "javascript",
        "object",
        "function",
        "callback"
    ],
    "license": "MIT",
    "main": "lib/weak.js",
    "maintainers": [
        {
            "name": "TooTallNate"
        },
        {
            "name": "tootallnate"
        }
    ],
    "name": "weak",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/TooTallNate/node-weak.git"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "test": "mocha -gc --reporter spec"
    },
    "version": "1.0.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
