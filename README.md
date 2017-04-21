# npmtest-xbee-api

#### basic test coverage for  [xbee-api (v0.5.2)](https://github.com/jankolkmeier/xbee-api)  [![npm package](https://img.shields.io/npm/v/npmtest-xbee-api.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-xbee-api) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-xbee-api.svg)](https://travis-ci.org/npmtest/node-npmtest-xbee-api)

#### Node.js and Chrome communicate with XBee/ZigBee devices in API mode

[![NPM](https://nodei.co/npm/xbee-api.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/xbee-api)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-xbee-api/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-xbee-api/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-xbee-api/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-xbee-api/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-xbee-api/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-xbee-api/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-xbee-api/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-xbee-api/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-xbee-api/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-xbee-api/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-xbee-api/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-xbee-api/build/test-report.html](https://npmtest.github.io/node-npmtest-xbee-api/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-xbee-api/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-xbee-api/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-xbee-api/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-xbee-api/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-xbee-api/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-xbee-api/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-xbee-api/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-xbee-api/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "xbee-api",
    "description": "Node.js and Chrome communicate with XBee/ZigBee devices in API mode",
    "version": "0.5.2",
    "homepage": "https://github.com/jankolkmeier/xbee-api",
    "author": {
        "name": "Jan Kolkmeier",
        "url": "http://kolkmeier.com"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/jankolkmeier/xbee-api.git"
    },
    "bugs": {
        "url": "https://github.com/jankolkmeier/xbee-api/issues"
    },
    "licenses": "MIT",
    "main": "lib/xbee-api",
    "engines": {
        "node": ">=0.10.0"
    },
    "scripts": {
        "test": "grunt nodeunit"
    },
    "devDependencies": {
        "serialport": "~4.0.0",
        "grunt-contrib-jshint": "~1.0.0",
        "grunt-contrib-nodeunit": "~1.0.0",
        "grunt-contrib-watch": "~1.0.0",
        "grunt-browserify": "~5.0.0",
        "grunt": "~1.0.1"
    },
    "keywords": [],
    "dependencies": {
        "buffer-builder": "^0.2.0",
        "buffer-reader": "https://github.com/prodatakey/node-buffer-reader/archive/v0.0.3.tar.gz",
        "safe-buffer": "~5.0.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
