# npmtest-later

#### basic test coverage for  [later (v1.2.0)](https://github.com/bunkat/later#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-later.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-later) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-later.svg)](https://travis-ci.org/npmtest/node-npmtest-later)

#### Determine later (or previous) occurrences of recurring schedules

[![NPM](https://nodei.co/npm/later.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/later)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-later/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-later/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-later/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-later/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-later/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-later/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-later/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-later/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-later/tree/gh-pages/build)|

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
    "author": {
        "name": "BunKat"
    },
    "browserify": "index-browserify.js",
    "bugs": {
        "url": "https://github.com/bunkat/later/issues"
    },
    "dependencies": {},
    "description": "Determine later (or previous) occurrences of recurring schedules",
    "devDependencies": {
        "benchmark": "*",
        "jslint": "*",
        "mocha": "*",
        "should": ">=0.6.3",
        "smash": "~0.0.8",
        "uglify-js": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "f2cf6c4dd7956dd2f520adf0329836e9876bad0f",
        "tarball": "https://registry.npmjs.org/later/-/later-1.2.0.tgz"
    },
    "gitHead": "76bf6ed7da1dbebd65dd36fe7320df4edd593e00",
    "homepage": "https://github.com/bunkat/later#readme",
    "jam": {
        "main": "later.js",
        "shim": {
            "exports": "later"
        }
    },
    "keywords": [
        "schedule",
        "occurrences",
        "recur",
        "cron"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "bunkat"
        }
    ],
    "name": "later",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/bunkat/later.git"
    },
    "scripts": {
        "test": "mocha test/**/*-test.js --reporter dot"
    },
    "version": "1.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
