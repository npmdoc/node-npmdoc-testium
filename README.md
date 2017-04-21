# npmdoc-testium

#### api documentation for  [testium (v3.3.1)](https://github.com/groupon-testium/testium)  [![npm package](https://img.shields.io/npm/v/npmdoc-testium.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-testium) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-testium.svg)](https://travis-ci.org/npmdoc/node-npmdoc-testium)

#### Synchronous integration testing with Node.js bindings for WebDriver

[![NPM](https://nodei.co/npm/testium.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/testium)

- [https://npmdoc.github.io/node-npmdoc-testium/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-testium/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-testium/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-testium/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-testium/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-testium/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "testium",
    "version": "3.3.1",
    "description": "Synchronous integration testing with Node.js bindings for WebDriver",
    "license": "BSD-3-Clause",
    "keywords": [
        "testing",
        "selenium",
        "webdriver"
    ],
    "homepage": "https://github.com/groupon-testium/testium",
    "bugs": {
        "url": "https://github.com/groupon-testium/testium/issues"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/groupon-testium/testium"
    },
    "author": {
        "name": "Sean Massa"
    },
    "publishConfig": {
        "registry": "https://registry.npmjs.org",
        "license": {
            "exclude": [
                "cli.js",
                "lib",
                "test"
            ]
        }
    },
    "main": "lib/testium.js",
    "bin": "cli.js",
    "scripts": {
        "test": "make all"
    },
    "engines": {
        "node": ">=0.10.16"
    },
    "dependencies": {
        "assertive": "^1.4.0",
        "debug": "^2.1.0",
        "lodash": "^3.9.3",
        "mkdirp": "~0.5.0",
        "selenium-download": "^2.0.0",
        "testium-core": "^1.3.0",
        "testium-driver-sync": "^2.1.0",
        "testium-mocha": "^1.0.0"
    },
    "devDependencies": {
        "coffee-script": "1.9.3",
        "mocha": "^2.3.3",
        "npub": "^2.2.0",
        "rimraf": "^2.2.8",
        "testium-example-app": "^2.0.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
