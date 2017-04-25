# npmtest-helmet

#### basic test coverage for  [helmet (v3.5.0)](https://helmetjs.github.io/)  [![npm package](https://img.shields.io/npm/v/npmtest-helmet.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-helmet) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-helmet.svg)](https://travis-ci.org/npmtest/node-npmtest-helmet)

#### help secure Express/Connect apps with various HTTP headers

[![NPM](https://nodei.co/npm/helmet.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/helmet)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-helmet/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-helmet/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-helmet/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-helmet/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-helmet/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-helmet/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-helmet/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-helmet/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-helmet/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-helmet/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-helmet/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-helmet/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-helmet/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-helmet/build/test-report.html](https://npmtest.github.io/node-npmtest-helmet/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-helmet/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-helmet/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-helmet/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-helmet/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-helmet/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-helmet/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-helmet/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-helmet/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Adam Baldwin",
        "url": "http://andyet.net/team/baldwin"
    },
    "bugs": {
        "url": "https://github.com/helmetjs/helmet/issues"
    },
    "contributors": [
        {
            "name": "Evan Hahn",
            "url": "http://evanhahn.com"
        }
    ],
    "dependencies": {
        "connect": "3.6.0",
        "dns-prefetch-control": "0.1.0",
        "dont-sniff-mimetype": "1.0.0",
        "frameguard": "3.0.0",
        "helmet-csp": "2.4.0",
        "hide-powered-by": "1.0.0",
        "hpkp": "2.0.0",
        "hsts": "2.0.0",
        "ienoopen": "1.0.0",
        "nocache": "2.0.0",
        "referrer-policy": "1.1.0",
        "x-xss-protection": "1.0.0"
    },
    "description": "help secure Express/Connect apps with various HTTP headers",
    "devDependencies": {
        "mocha": "^3.2.0",
        "sinon": "^1.17.7",
        "standard": "^9.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "e1d6de27d2e3317d3182e00d672df3d0e1e12539",
        "tarball": "https://registry.npmjs.org/helmet/-/helmet-3.5.0.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "gitHead": "ebd0d35495470708be42750204060a7f96bbd01d",
    "homepage": "https://helmetjs.github.io/",
    "keywords": [
        "security",
        "headers",
        "express",
        "connect",
        "x-frame-options",
        "x-powered-by",
        "csp",
        "hsts",
        "clickjack"
    ],
    "license": "MIT",
    "main": "index",
    "maintainers": [
        {
            "name": "adam_baldwin"
        },
        {
            "name": "evanhahn"
        }
    ],
    "name": "helmet",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/helmetjs/helmet.git"
    },
    "scripts": {
        "pretest": "standard",
        "test": "mocha"
    },
    "standard": {
        "globals": [
            "describe",
            "it",
            "beforeEach",
            "afterEach"
        ]
    },
    "version": "3.5.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
