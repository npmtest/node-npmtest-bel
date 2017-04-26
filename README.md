# npmtest-bel

#### basic test coverage for  [bel (v4.6.0)](https://github.com/shama/bel)  [![npm package](https://img.shields.io/npm/v/npmtest-bel.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-bel) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-bel.svg)](https://travis-ci.org/npmtest/node-npmtest-bel)

#### A simple extension to native elements

[![NPM](https://nodei.co/npm/bel.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bel)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-bel/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-bel/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-bel/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-bel/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-bel/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-bel/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-bel/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-bel/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-bel/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-bel/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-bel/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-bel/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-bel/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-bel/build/test-report.html](https://npmtest.github.io/node-npmtest-bel/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-bel/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-bel/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-bel/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bel/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bel/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bel/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-bel/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-bel/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kyle Robinson Young",
        "url": "http://dontkry.com"
    },
    "bugs": {
        "url": "https://github.com/shama/bel/issues"
    },
    "dependencies": {
        "global": "^4.3.0",
        "hyperx": "^2.3.0",
        "on-load": "^3.2.0"
    },
    "description": "A simple extension to native elements",
    "devDependencies": {
        "browser-process-hrtime": "^0.1.2",
        "browserify": "^14.1.0",
        "electron-prebuilt": "^0.36.9",
        "morphdom": "^2.1.1",
        "standard": "^9.0.2",
        "tape": "^4.6.0",
        "testron": "^1.2.0",
        "wzrd": "^1.4.0"
    },
    "directories": {},
    "dist": {
        "shasum": "3ade16e236ab2204d8d1c66eac4bd573793ac999",
        "tarball": "https://registry.npmjs.org/bel/-/bel-4.6.0.tgz"
    },
    "files": [
        "index.js",
        "create.js"
    ],
    "gitHead": "67096071dfb3e4f1a38867cc18f1c6cf4a86f145",
    "homepage": "https://github.com/shama/bel",
    "keywords": [
        "virtual-dom",
        "element",
        "diffhtml"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "chromakode"
        },
        {
            "name": "shama"
        },
        {
            "name": "yoshuawuyts"
        }
    ],
    "name": "bel",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/shama/bel.git"
    },
    "scripts": {
        "bench": "wzrd bench/index.js:bundle.js",
        "start": "wzrd test/index.js:bundle.js",
        "test": "standard && node test/server.js && browserify test/index.js | testron"
    },
    "version": "4.6.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
