# npmtest-grunt-sync

#### basic test coverage for  [grunt-sync (v0.6.2)](https://github.com/tomusdrw/grunt-sync.git)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-sync.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-sync) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-sync.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-sync)

#### Task to synchronize two directories. Similar to grunt-copy but updates only files that have been changed.

[![NPM](https://nodei.co/npm/grunt-sync.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-sync)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-sync/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-sync/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-sync/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-sync/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-sync/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-sync/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-sync/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-sync/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-sync/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-sync/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-sync/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-sync/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-sync/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-sync/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-sync/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-sync/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-sync/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-sync/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-sync/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-sync/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-sync/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tomasz Drwiega",
        "url": "http://blacksoft.eu"
    },
    "bugs": {
        "url": "https://github.com/tomusdrw/grunt-sync/issues"
    },
    "dependencies": {
        "glob": "^7.0.5",
        "lodash": "^4.14.2",
        "md5-file": "^2.0.3",
        "promised-io": "0.3.5"
    },
    "description": "Task to synchronize two directories. Similar to grunt-copy but updates only files that have been changed.",
    "devDependencies": {
        "chai": "1.4.2",
        "grunt": "0.4.x",
        "grunt-complexity": "^0.1.51",
        "grunt-contrib-jshint": "0.1.x",
        "grunt-simple-mocha": "0.3.x",
        "mocha": "~1.8.1",
        "semistandard": "^6.1.2",
        "time-grunt": "^0.4.0"
    },
    "directories": {},
    "dist": {
        "shasum": "d9acb65b4205d017bd6462e49fec2d9071ace47b",
        "tarball": "https://registry.npmjs.org/grunt-sync/-/grunt-sync-0.6.2.tgz"
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "gitHead": "ca10eb6f815d0c502e54dfbe667adab4854f644d",
    "homepage": "https://github.com/tomusdrw/grunt-sync.git",
    "keywords": [
        "gruntplugin",
        "sync",
        "synchronize",
        "copy"
    ],
    "licences": [
        {
            "type": "MIT",
            "url": "http://opensource.org/licenses/MIT"
        }
    ],
    "main": "Gruntfile.js",
    "maintainers": [
        {
            "name": "tomusdrw"
        }
    ],
    "name": "grunt-sync",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/tomusdrw/grunt-sync.git"
    },
    "scripts": {
        "lint": "semistandard",
        "test": "mocha"
    },
    "version": "0.6.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
