# npmtest-fakeredis

#### basic test coverage for  fakeredis (v2.0.0)  [![npm package](https://img.shields.io/npm/v/npmtest-fakeredis.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-fakeredis) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-fakeredis.svg)](https://travis-ci.org/npmtest/node-npmtest-fakeredis)

#### Fake redis for testing, works as a drop-in replacement for node_redis

[![NPM](https://nodei.co/npm/fakeredis.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/fakeredis)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-fakeredis/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-fakeredis/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-fakeredis/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-fakeredis/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-fakeredis/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-fakeredis/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-fakeredis/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-fakeredis/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-fakeredis/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-fakeredis/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-fakeredis/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-fakeredis/build/test-report.html](https://npmtest.github.io/node-npmtest-fakeredis/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-fakeredis/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-fakeredis/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-fakeredis/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-fakeredis/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-fakeredis/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-fakeredis/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-fakeredis/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-fakeredis/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "fakeredis",
    "version": "2.0.0",
    "description": "Fake redis for testing, works as a drop-in replacement for node_redis",
    "keywords": [
        "test",
        "spec",
        "fake",
        "redis",
        "simulated",
        "implementation",
        "client"
    ],
    "author": "Hristo Dachev <tutini@gmail.com>",
    "main": "./main.js",
    "dependencies": {
        "redis": "2.6.0-0"
    },
    "license": "MIT",
    "bugs": {
        "mail": "tutini@gmail.com",
        "url": "http://github.com/hdachev/fakeredis/issues"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/hdachev/fakeredis.git"
    },
    "scripts": {
        "test": "./runtest",
        "coverage": "./covertest"
    },
    "devDependencies": {
        "coveralls": "^2.11.6",
        "istanbul": "^0.4.2",
        "lcov-result-merger": "^1.0.2"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
