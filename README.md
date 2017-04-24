# npmtest-restangular

#### basic test coverage for  [restangular (v1.6.1)](https://github.com/mgonto/restangular)  [![npm package](https://img.shields.io/npm/v/npmtest-restangular.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-restangular) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-restangular.svg)](https://travis-ci.org/npmtest/node-npmtest-restangular)

#### Restful Resources service for AngularJS apps

[![NPM](https://nodei.co/npm/restangular.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/restangular)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-restangular/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-restangular/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-restangular/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-restangular/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-restangular/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-restangular/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-restangular/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-restangular/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-restangular/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-restangular/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-restangular/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-restangular/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-restangular/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-restangular/build/test-report.html](https://npmtest.github.io/node-npmtest-restangular/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-restangular/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-restangular/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-restangular/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-restangular/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-restangular/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-restangular/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-restangular/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-restangular/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "restangular",
    "description": "Restful Resources service for AngularJS apps",
    "version": "1.6.1",
    "filename": "restangular.min.js",
    "main": "./dist/restangular.js",
    "homepage": "https://github.com/mgonto/restangular",
    "author": "Martin Gontovnikas <martin@gon.to>",
    "repository": {
        "type": "git",
        "url": "git://github.com/mgonto/restangular.git"
    },
    "engines": {
        "node": ">= 0.9"
    },
    "keywords": [
        "angular",
        "client",
        "browser",
        "restful",
        "resources",
        "rest",
        "api"
    ],
    "maintainers": [
        {
            "name": "Martin Gontovnikas",
            "website": "http://gon.to/"
        }
    ],
    "dependencies": {
        "lodash": "~4.17.0"
    },
    "peerDependencies": {
        "angular": ">=1.3.12"
    },
    "devDependencies": {
        "angular-mocks": "^1.4.8",
        "grunt": "^1.0.0",
        "grunt-bower": "*",
        "grunt-bower-task": "*",
        "grunt-cli": "^1.2.0",
        "grunt-contrib-concat": "*",
        "grunt-contrib-jshint": "*",
        "grunt-contrib-uglify": "*",
        "grunt-conventional-changelog": "latest",
        "grunt-coveralls": "^1.0.1",
        "grunt-karma": "latest",
        "grunt-zip": "*",
        "jasmine-core": "^2.5.2",
        "karma": "^1.3.0",
        "karma-chrome-launcher": "~2.0.0",
        "karma-coverage": "^1.1.1",
        "karma-firefox-launcher": "~v1.0.0",
        "karma-jasmine": "^1.1.0",
        "karma-mocha-reporter": "^2.2.0",
        "karma-phantomjs-launcher": "~v1.0.2"
    },
    "scripts": {
        "test": "grunt test --verbose"
    },
    "license": "MIT",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
