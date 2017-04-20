# npmtest-npm-registry-client

#### basic test coverage for  [npm-registry-client (v8.1.1)](https://github.com/npm/npm-registry-client#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-npm-registry-client.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-npm-registry-client) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-npm-registry-client.svg)](https://travis-ci.org/npmtest/node-npmtest-npm-registry-client)

#### Client for the npm registry

[![NPM](https://nodei.co/npm/npm-registry-client.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/npm-registry-client)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-npm-registry-client/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-npm-registry-client/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-npm-registry-client/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-npm-registry-client/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-npm-registry-client/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-npm-registry-client/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-npm-registry-client/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-npm-registry-client/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-npm-registry-client/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-npm-registry-client/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-npm-registry-client/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-npm-registry-client/build/test-report.html](https://npmtest.github.io/node-npmtest-npm-registry-client/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-npm-registry-client/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-npm-registry-client/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-npm-registry-client/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-npm-registry-client/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npm-registry-client/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npm-registry-client/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-npm-registry-client/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-npm-registry-client/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Isaac Z. Schlueter",
        "url": "http://blog.izs.me/"
    },
    "bugs": {
        "url": "https://github.com/npm/npm-registry-client/issues"
    },
    "dependencies": {
        "concat-stream": "^1.5.2",
        "graceful-fs": "^4.1.6",
        "normalize-package-data": "~1.0.1 || ^2.0.0",
        "npm-package-arg": "^3.0.0 || ^4.0.0 || ^5.0.0",
        "npmlog": "2 || ^3.1.0 || ^4.0.0",
        "once": "^1.3.3",
        "request": "^2.74.0",
        "retry": "^0.10.0",
        "semver": "2 >=2.2.1 || 3.x || 4 || 5",
        "slide": "^1.1.3"
    },
    "description": "Client for the npm registry",
    "devDependencies": {
        "negotiator": "^0.6.1",
        "nock": "^9.0.9",
        "readable-stream": "^2.1.5",
        "require-inject": "^1.4.0",
        "rimraf": "^2.5.4",
        "standard": "^9.0.0",
        "tap": "^10.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "831476455423ca0a265c6ffdb6100fcc042b36cf",
        "tarball": "https://registry.npmjs.org/npm-registry-client/-/npm-registry-client-8.1.1.tgz"
    },
    "files": [
        "lib",
        "index.js"
    ],
    "gitHead": "81afb2ce59d82c2a1179211d8c1bc789c9f6128c",
    "homepage": "https://github.com/npm/npm-registry-client#readme",
    "license": "ISC",
    "main": "index.js",
    "maintainers": [
        {
            "name": "iarna"
        }
    ],
    "name": "npm-registry-client",
    "optionalDependencies": {
        "npmlog": "2 || ^3.1.0 || ^4.0.0"
    },
    "repository": {
        "url": "git+https://github.com/npm/npm-registry-client.git"
    },
    "scripts": {
        "test": "standard && tap test/*.js"
    },
    "version": "8.1.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
