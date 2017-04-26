# npmtest-simplecrawler

#### basic test coverage for  [simplecrawler (v1.1.1)](https://github.com/cgiffard/node-simplecrawler)  [![npm package](https://img.shields.io/npm/v/npmtest-simplecrawler.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-simplecrawler) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-simplecrawler.svg)](https://travis-ci.org/npmtest/node-npmtest-simplecrawler)

#### Very straightforward, event driven web crawler. Features a flexible queue interface and a basic cache mechanism with extensible backend.

[![NPM](https://nodei.co/npm/simplecrawler.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/simplecrawler)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-simplecrawler/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-simplecrawler/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-simplecrawler/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-simplecrawler/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-simplecrawler/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-simplecrawler/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-simplecrawler/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-simplecrawler/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-simplecrawler/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-simplecrawler/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-simplecrawler/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-simplecrawler/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-simplecrawler/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-simplecrawler/build/test-report.html](https://npmtest.github.io/node-npmtest-simplecrawler/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-simplecrawler/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-simplecrawler/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-simplecrawler/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-simplecrawler/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-simplecrawler/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-simplecrawler/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-simplecrawler/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-simplecrawler/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Christopher Giffard"
    },
    "bin": {
        "crawl": "./lib/cli.js"
    },
    "bugs": {
        "url": "https://github.com/cgiffard/node-simplecrawler/issues"
    },
    "dependencies": {
        "async": "^2.1.4",
        "iconv-lite": "^0.4.13",
        "robots-parser": "^1.0.0",
        "urijs": "^1.16.1"
    },
    "description": "Very straightforward, event driven web crawler. Features a flexible queue interface and a basic cache mechanism with extensible backend.",
    "devDependencies": {
        "chai": "^3.2.0",
        "eslint": "^2.0.0",
        "jsdoc": "^3.4.0",
        "mocha": "^3.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5893d24d25ca67ca1244d813ff56ca04fadbdbe9",
        "tarball": "https://registry.npmjs.org/simplecrawler/-/simplecrawler-1.1.1.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "lib"
    ],
    "gitHead": "28aee5dc5d9123efb6ab4314cea4d0b7a3a25b59",
    "homepage": "https://github.com/cgiffard/node-simplecrawler",
    "keywords": [
        "simple",
        "crawler",
        "spider",
        "cache",
        "queue",
        "simplecrawler",
        "eventemitter"
    ],
    "license": "BSD-2-Clause",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "cgiffard"
        },
        {
            "name": "fredrikekelund"
        }
    ],
    "name": "simplecrawler",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/cgiffard/node-simplecrawler.git"
    },
    "scripts": {
        "docs": "jsdoc -c jsdoc.json",
        "lint": "eslint example/ lib/ test/",
        "mocha": "mocha -R spec -t 5000",
        "test": "npm run lint && npm run mocha"
    },
    "version": "1.1.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
