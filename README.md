# npmtest-datadog-metrics

#### basic test coverage for  [datadog-metrics (v0.4.0)](https://github.com/dbader/node-datadog-metrics#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-datadog-metrics.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-datadog-metrics) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-datadog-metrics.svg)](https://travis-ci.org/npmtest/node-npmtest-datadog-metrics)

#### Buffered metrics reporting via the DataDog HTTP API

[![NPM](https://nodei.co/npm/datadog-metrics.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/datadog-metrics)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-datadog-metrics/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-datadog-metrics/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-datadog-metrics/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-datadog-metrics/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-datadog-metrics/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-datadog-metrics/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-datadog-metrics/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-datadog-metrics/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-datadog-metrics/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-datadog-metrics/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-datadog-metrics/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-datadog-metrics/build/test-report.html](https://npmtest.github.io/node-npmtest-datadog-metrics/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-datadog-metrics/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-datadog-metrics/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-datadog-metrics/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-datadog-metrics/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-datadog-metrics/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-datadog-metrics/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-datadog-metrics/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-datadog-metrics/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Daniel Bader",
        "url": "http://dbader.org/"
    },
    "bugs": {
        "url": "https://github.com/dbader/node-datadog-metrics/issues"
    },
    "dependencies": {
        "debug": "2.2.0",
        "dogapi": "1.1.0"
    },
    "description": "Buffered metrics reporting via the DataDog HTTP API",
    "devDependencies": {
        "chai": "3.5.0",
        "chai-string": "1.1.6",
        "jscs": "2.9.0",
        "jshint": "2.9.1",
        "jshint-stylish-ex": "0.2.0",
        "mocha": "2.4.5"
    },
    "directories": {},
    "dist": {
        "shasum": "06566a9b147858cf02caf269332677c875b49e4f",
        "tarball": "https://registry.npmjs.org/datadog-metrics/-/datadog-metrics-0.4.0.tgz"
    },
    "gitHead": "6ffe18554a8403004ba67e97c4bd8205ae70dd2a",
    "homepage": "https://github.com/dbader/node-datadog-metrics#readme",
    "keywords": [
        "datadog",
        "metrics",
        "stats"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "csabapalfi"
        },
        {
            "name": "dbader"
        }
    ],
    "name": "datadog-metrics",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/dbader/node-datadog-metrics.git"
    },
    "scripts": {
        "test": "mocha --reporter spec && ./node_modules/.bin/jshint --reporter node_modules/jshint-stylish-ex/stylish.js *.js ./lib/*.js ./test/*.js && ./node_modules/.bin/jscs --config .jscsrc *.js ./lib/*.js ./test/*.js"
    },
    "version": "0.4.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
