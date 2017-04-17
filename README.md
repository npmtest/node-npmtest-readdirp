# test coverage for  [readdirp (v2.1.0)](https://github.com/thlorenz/readdirp)  [![npm package](https://img.shields.io/npm/v/npmtest-readdirp.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-readdirp) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-readdirp.svg)](https://travis-ci.org/npmtest/node-npmtest-readdirp)
#### Recursive version of fs.readdir with streaming api.

[![NPM](https://nodei.co/npm/readdirp.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/readdirp)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-readdirp/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-readdirp/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-readdirp/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-readdirp/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-readdirp/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-readdirp/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-readdirp/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-readdirp/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-readdirp/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-readdirp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-readdirp/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-readdirp/build/test-report.html](https://npmtest.github.io/node-npmtest-readdirp/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-readdirp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-readdirp/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-readdirp/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-readdirp/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-readdirp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-readdirp/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-readdirp/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-readdirp/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Thorsten Lorenz",
        "url": "thlorenz.com"
    },
    "bugs": {
        "url": "https://github.com/thlorenz/readdirp/issues"
    },
    "dependencies": {
        "graceful-fs": "^4.1.2",
        "minimatch": "^3.0.2",
        "readable-stream": "^2.0.2",
        "set-immediate-shim": "^1.0.1"
    },
    "description": "Recursive version of fs.readdir with streaming api.",
    "devDependencies": {
        "nave": "^0.5.1",
        "proxyquire": "^1.7.9",
        "tap": "1.3.2",
        "through2": "^2.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "4ed0ad060df3073300c48440373f72d1cc642d78",
        "tarball": "https://registry.npmjs.org/readdirp/-/readdirp-2.1.0.tgz"
    },
    "engines": {
        "node": ">=0.6"
    },
    "gitHead": "5a3751f86a1c2bbbb8e3a42685d4191992631e6c",
    "homepage": "https://github.com/thlorenz/readdirp",
    "keywords": [
        "recursive",
        "fs",
        "stream",
        "streams",
        "readdir",
        "filesystem",
        "find",
        "filter"
    ],
    "license": "MIT",
    "main": "readdirp.js",
    "maintainers": [
        {
            "name": "thlorenz"
        }
    ],
    "name": "readdirp",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/thlorenz/readdirp.git"
    },
    "scripts": {
        "test": "if [ -e $TRAVIS ]; then npm run test-all; else npm run test-main; fi",
        "test-0.10": "nave use 0.10 npm run test-main",
        "test-0.12": "nave use 0.12 npm run test-main",
        "test-4": "nave use 4.4 npm run test-main",
        "test-6": "nave use 6.2 npm run test-main",
        "test-all": "npm run test-main && npm run test-0.10 && npm run test-0.12 && npm run test-4 && npm run test-6",
        "test-main": "(cd test && set -e; for t in ./*.js; do node $t; done)"
    },
    "version": "2.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
