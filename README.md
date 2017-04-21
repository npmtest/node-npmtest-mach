# npmtest-mach

#### basic test coverage for  [mach (v1.3.8)](https://github.com/mjackson/mach)  [![npm package](https://img.shields.io/npm/v/npmtest-mach.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mach) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mach.svg)](https://travis-ci.org/npmtest/node-npmtest-mach)

#### HTTP for JavaScript

[![NPM](https://nodei.co/npm/mach.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mach)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mach/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mach/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mach/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mach/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mach/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mach/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mach/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mach/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mach/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mach/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mach/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mach/build/test-report.html](https://npmtest.github.io/node-npmtest-mach/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mach/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mach/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mach/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mach/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mach/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mach/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mach/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mach/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Michael Jackson"
    },
    "browser": {
        "./modules/extensions/default.js": "./modules/extensions/default-browser.js",
        "./modules/utils/File.js": "./modules/utils/File-browser.js",
        "./modules/utils/parseURL.js": "./modules/utils/parseURL-browser.js",
        "./modules/utils/readFile.js": "./modules/utils/readFile-browser.js",
        "./modules/utils/sendRequest.js": "./modules/utils/sendRequest-browser.js"
    },
    "bugs": {
        "url": "https://github.com/mjackson/mach/issues"
    },
    "dependencies": {
        "bodec": "^1.1.0",
        "bufferedstream": "^3.1.1",
        "describe-property": "^1.0.0",
        "object-assign": "^2.0.0",
        "qs": "^2.3.3",
        "redis": "~0.11.0",
        "strftime": "^0.9.0",
        "when": "^3.6.4"
    },
    "description": "HTTP for JavaScript",
    "devDependencies": {
        "babel": "^4.5.5",
        "babel-core": "^4.5.5",
        "babel-loader": "^4.0.0",
        "expect": "^1.3.0",
        "jshint": "^2.5.10",
        "karma": "^0.12.28",
        "karma-chrome-launcher": "^0.1.7",
        "karma-cli": "0.0.4",
        "karma-mocha": "^0.1.10",
        "karma-sourcemap-loader": "^0.3.2",
        "karma-webpack": "^1.3.1",
        "mocha": "^2.0.1",
        "webpack": "^1.4.15",
        "webpack-dev-server": "^1.6.6"
    },
    "directories": {},
    "dist": {
        "shasum": "15770498925066b28fadfb87e9282c8601f72111",
        "tarball": "https://registry.npmjs.org/mach/-/mach-1.3.8.tgz"
    },
    "engines": {
        "node": "0.10.x"
    },
    "gitHead": "6237effafd59e17a51df9d0468cc5718fdc27da0",
    "homepage": "https://github.com/mjackson/mach",
    "keywords": [
        "web",
        "server",
        "http",
        "strata",
        "jsgi",
        "then",
        "promise",
        "promises"
    ],
    "license": "MIT",
    "main": "lib",
    "maintainers": [
        {
            "name": "mjackson"
        }
    ],
    "name": "mach",
    "optionalDependencies": {
        "redis": "~0.11.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mjackson/mach.git"
    },
    "scripts": {
        "build": "scripts/build.sh",
        "release": "scripts/release.sh",
        "test": "jshint . && mocha --require babel/register --reporter spec 'modules/**/__tests__/*-test.js'",
        "test-browser": "karma start"
    },
    "version": "1.3.8",
    "warnings": [
        {
            "code": "ENOTSUP",
            "required": {
                "node": "0.10.x"
            },
            "pkgid": "mach@1.3.8"
        },
        {
            "code": "ENOTSUP",
            "required": {
                "node": "0.10.x"
            },
            "pkgid": "mach@1.3.8"
        }
    ],
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
