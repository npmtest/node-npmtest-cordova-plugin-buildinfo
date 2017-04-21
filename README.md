# npmtest-cordova-plugin-buildinfo

#### basic test coverage for  [cordova-plugin-buildinfo (v1.1.0)](https://github.com/lynrin/cordova-plugin-buildinfo#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-cordova-plugin-buildinfo.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cordova-plugin-buildinfo) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cordova-plugin-buildinfo.svg)](https://travis-ci.org/npmtest/node-npmtest-cordova-plugin-buildinfo)

#### Cordova/Phonegap Build Information Plugin. Get PackageName, Version, Debug and more...

[![NPM](https://nodei.co/npm/cordova-plugin-buildinfo.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cordova-plugin-buildinfo)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cordova-plugin-buildinfo/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cordova-plugin-buildinfo/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cordova-plugin-buildinfo/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cordova-plugin-buildinfo/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cordova-plugin-buildinfo/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cordova-plugin-buildinfo/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cordova-plugin-buildinfo/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cordova-plugin-buildinfo/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cordova-plugin-buildinfo/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cordova-plugin-buildinfo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cordova-plugin-buildinfo/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cordova-plugin-buildinfo/build/test-report.html](https://npmtest.github.io/node-npmtest-cordova-plugin-buildinfo/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cordova-plugin-buildinfo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cordova-plugin-buildinfo/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cordova-plugin-buildinfo/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cordova-plugin-buildinfo/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cordova-plugin-buildinfo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cordova-plugin-buildinfo/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cordova-plugin-buildinfo/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cordova-plugin-buildinfo/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "cordova-plugin-buildinfo",
    "version": "1.1.0",
    "description": "Cordova/Phonegap Build Information Plugin. Get PackageName, Version, Debug and more...",
    "cordova": {
        "id": "cordova-plugin-buildinfo",
        "platforms": [
            "android",
            "ios"
        ]
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/lynrin/cordova-plugin-buildinfo.git"
    },
    "keywords": [
        "debug",
        "buildconfig",
        "buildinfo",
        "phonegap",
        "cordova",
        "ecosystem:cordova",
        "cordova-android",
        "cordova-ios"
    ],
    "scripts": {
        "test": "npm run jshint",
        "jshint": "node node_modules/jshint/bin/jshint www && node node_modules/jshint/bin/jshint src && node node_modules/jshint/bin/jshint tests"
    },
    "engines": [
        {
            "name": "cordova",
            "version": ">=4.0.0"
        }
    ],
    "author": "Mikihiro Hayashi",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/lynrin/cordova-plugin-buildinfo/issues"
    },
    "homepage": "https://github.com/lynrin/cordova-plugin-buildinfo#readme",
    "devDependencies": {
        "jshint": "^2.6.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
