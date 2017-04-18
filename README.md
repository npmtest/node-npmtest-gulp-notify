# npmtest-gulp-notify

#### test coverage for  [gulp-notify (v3.0.0)](https://github.com/mikaelbr/gulp-notify)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-notify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-notify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-notify.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-notify)

#### gulp plugin to send messages based on Vinyl Files or Errors to Mac OS X, Linux or Windows using the node-notifier module. Fallbacks to Growl or simply logging

[![NPM](https://nodei.co/npm/gulp-notify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-notify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-notify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-notify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-notify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-notify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-notify/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-notify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-notify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-notify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-notify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-notify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-notify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-notify/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-notify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-notify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-notify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-notify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-notify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-notify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-notify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-notify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-notify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mikael Brevik",
        "url": "https://github.com/mikaelbr"
    },
    "bugs": {
        "url": "https://github.com/mikaelbr/gulp-notify/issues"
    },
    "dependencies": {
        "gulp-util": "^3.0.8",
        "lodash.template": "^4.4.0",
        "node-notifier": "^5.0.1",
        "node.extend": "^1.1.6",
        "through2": "^2.0.3"
    },
    "description": "gulp plugin to send messages based on Vinyl Files or Errors to Mac OS X, Linux or Windows using the node-notifier module. Fallbacks to Growl or simply logging",
    "devDependencies": {
        "gulp": "^3.8.10",
        "gulp-plumber": "^1.1.0",
        "mocha": "^3.2.0",
        "should": "^11.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "a04b8af9acdbe4e63c845678ce0c3d30694c59a3",
        "tarball": "https://registry.npmjs.org/gulp-notify/-/gulp-notify-3.0.0.tgz"
    },
    "engines": {
        "node": ">=0.8.0",
        "npm": ">=1.2.10"
    },
    "gitHead": "658efc5d81ae0d5224a053100653d46000319373",
    "homepage": "https://github.com/mikaelbr/gulp-notify",
    "keywords": [
        "gulpplugin",
        "notify",
        "gulp",
        "notification",
        "reporter",
        "windows notification",
        "mac notification",
        "notify-send",
        "notify-osd",
        "growl"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "mikaelb"
        }
    ],
    "name": "gulp-notify",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/mikaelbr/gulp-notify.git"
    },
    "scripts": {
        "gulp": "gulp --gulpfile ./examples/gulpfile.js",
        "test": "mocha -R spec"
    },
    "version": "3.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
