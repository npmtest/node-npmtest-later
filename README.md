# npmtest-later

#### basic test coverage for  later (v1.2.0)  [![npm package](https://img.shields.io/npm/v/npmtest-later.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-later) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-later.svg)](https://travis-ci.org/npmtest/node-npmtest-later)

#### Determine later (or previous) occurrences of recurring schedules

[![NPM](https://nodei.co/npm/later.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/later)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-later/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-later/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-later/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-later/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-later/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-later/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-later/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-later/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-later/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-later/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-later/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-later/build/test-report.html](https://npmtest.github.io/node-npmtest-later/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-later/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-later/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-later/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-later/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-later/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-later/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-later/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-later/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "later",
    "version": "1.2.0",
    "description": "Determine later (or previous) occurrences of recurring schedules",
    "keywords": [
        "schedule",
        "occurrences",
        "recur",
        "cron"
    ],
    "author": "BunKat <bill@levelstory.com>",
    "repository": {
        "type": "git",
        "url": "git://github.com/bunkat/later.git"
    },
    "main": "index.js",
    "browserify": "index-browserify.js",
    "jam": {
        "main": "later.js",
        "shim": {
            "exports": "later"
        }
    },
    "devDependencies": {
        "smash": "~0.0.8",
        "mocha": "*",
        "should": ">=0.6.3",
        "jslint": "*",
        "uglify-js": "*",
        "benchmark": "*"
    },
    "license": "MIT",
    "scripts": {
        "test": "./node_modules/.bin/mocha test/**/*-test.js --reporter dot"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
