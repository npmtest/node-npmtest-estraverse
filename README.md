# test coverage for  [estraverse (v4.2.0)](https://github.com/estools/estraverse)  [![npm package](https://img.shields.io/npm/v/npmtest-estraverse.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-estraverse) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-estraverse.svg)](https://travis-ci.org/npmtest/node-npmtest-estraverse)
#### ECMAScript JS AST traversal functions

[![NPM](https://nodei.co/npm/estraverse.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/estraverse)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-estraverse/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-estraverse/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-estraverse/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-estraverse/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-estraverse/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-estraverse/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-estraverse/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-estraverse/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-estraverse/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-estraverse/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-estraverse/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-estraverse/build/test-report.html](https://npmtest.github.io/node-npmtest-estraverse/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-estraverse/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-estraverse/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-estraverse/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-estraverse/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-estraverse/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-estraverse/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-estraverse/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-estraverse/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/estools/estraverse/issues"
    },
    "dependencies": {},
    "description": "ECMAScript JS AST traversal functions",
    "devDependencies": {
        "babel-preset-es2015": "^6.3.13",
        "babel-register": "^6.3.13",
        "chai": "^2.1.1",
        "espree": "^1.11.0",
        "gulp": "^3.8.10",
        "gulp-bump": "^0.2.2",
        "gulp-filter": "^2.0.0",
        "gulp-git": "^1.0.1",
        "gulp-tag-version": "^1.2.1",
        "jshint": "^2.5.6",
        "mocha": "^2.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "0dee3fed31fcd469618ce7342099fc1afa0bdb13",
        "tarball": "https://registry.npmjs.org/estraverse/-/estraverse-4.2.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "6f6a4e99653908e859c7c10d04d9518bf4844ede",
    "homepage": "https://github.com/estools/estraverse",
    "license": "BSD-2-Clause",
    "main": "estraverse.js",
    "maintainers": [
        {
            "name": "constellation"
        },
        {
            "name": "michaelficarra"
        },
        {
            "name": "nzakas"
        }
    ],
    "name": "estraverse",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/estools/estraverse.git"
    },
    "scripts": {
        "lint": "jshint estraverse.js",
        "test": "npm run-script lint && npm run-script unit-test",
        "unit-test": "mocha --compilers js:babel-register"
    },
    "version": "4.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
