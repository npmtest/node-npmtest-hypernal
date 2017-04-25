# npmtest-hypernal

#### basic test coverage for  [hypernal (v0.3.0)](https://github.com/thlorenz/hypernal)  [![npm package](https://img.shields.io/npm/v/npmtest-hypernal.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-hypernal) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-hypernal.svg)](https://travis-ci.org/npmtest/node-npmtest-hypernal)

#### Renders terminal output as html to simplify reusing server side modules in the browser.

[![NPM](https://nodei.co/npm/hypernal.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hypernal)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-hypernal/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-hypernal/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-hypernal/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-hypernal/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-hypernal/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-hypernal/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-hypernal/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-hypernal/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-hypernal/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-hypernal/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-hypernal/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-hypernal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-hypernal/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-hypernal/build/test-report.html](https://npmtest.github.io/node-npmtest-hypernal/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-hypernal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-hypernal/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-hypernal/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hypernal/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hypernal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hypernal/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-hypernal/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-hypernal/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Thorsten Lorenz",
        "url": "http://thlorenz.com"
    },
    "bugs": {
        "url": "https://github.com/thlorenz/hypernal/issues"
    },
    "dependencies": {
        "through": "~2.3.4"
    },
    "description": "Renders terminal output as html to simplify reusing server side modules in the browser.",
    "devDependencies": {
        "browserify": "~2.11.0",
        "difflet": "~0.2.3"
    },
    "directories": {},
    "dist": {
        "shasum": "19f3e8a7e85f751a5885225f631e91d37459b6bf",
        "tarball": "https://registry.npmjs.org/hypernal/-/hypernal-0.3.0.tgz"
    },
    "engine": {
        "node": ">=0.6"
    },
    "gitHead": "779a52981f5222a4f855146ff7b436afd2d1533e",
    "homepage": "https://github.com/thlorenz/hypernal",
    "keywords": [
        "terminal",
        "render",
        "browser",
        "ansi",
        "colors"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "thlorenz"
        }
    ],
    "name": "hypernal",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/thlorenz/hypernal.git"
    },
    "scripts": {
        "demo": "node example/build && npm install opener && opener example/index.html",
        "test": "echo 'no tests yet :('"
    },
    "version": "0.3.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
