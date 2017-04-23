# npmtest-mocha-phantomjs

#### basic test coverage for  mocha-phantomjs (v4.1.0)  [![npm package](https://img.shields.io/npm/v/npmtest-mocha-phantomjs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mocha-phantomjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mocha-phantomjs.svg)](https://travis-ci.org/npmtest/node-npmtest-mocha-phantomjs)

#### Run mocha browser tests in phantomjs via the command line

[![NPM](https://nodei.co/npm/mocha-phantomjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mocha-phantomjs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mocha-phantomjs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mocha-phantomjs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mocha-phantomjs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mocha-phantomjs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mocha-phantomjs/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-mocha-phantomjs/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-mocha-phantomjs/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mocha-phantomjs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mocha-phantomjs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mocha-phantomjs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mocha-phantomjs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mocha-phantomjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mocha-phantomjs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mocha-phantomjs/build/test-report.html](https://npmtest.github.io/node-npmtest-mocha-phantomjs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mocha-phantomjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mocha-phantomjs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mocha-phantomjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mocha-phantomjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mocha-phantomjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mocha-phantomjs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mocha-phantomjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mocha-phantomjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "mocha-phantomjs",
    "description": "Run mocha browser tests in phantomjs via the command line",
    "keywords": [
        "phantomjs",
        "mocha",
        "test",
        "runner",
        "command line",
        "browser"
    ],
    "version": "4.1.0",
    "author": "Nathan Black <nathan@nathanblack.org> (http://nathanblack.org)",
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/nathanboktae/mocha-phantomjs/blob/master/MIT-LICENSE"
        }
    ],
    "contributors": [
        "Jonathan Chapman <chafnan@gmail.com> (https://github.com/chafnan)",
        "Ken Collins <ken@metaskills.net> (http://metaskills.net/)"
    ],
    "repository": {
        "type": "git",
        "url": "http://github.com/nathanboktae/mocha-phantomjs.git"
    },
    "bugs": {
        "url": "http://github.com/nathanboktae/mocha-phantomjs/issues"
    },
    "main": "./bin/mocha-phantomjs",
    "bin": {
        "mocha-phantomjs": "./bin/mocha-phantomjs"
    },
    "scripts": {
        "test": "mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000"
    },
    "dependencies": {
        "phantomjs": "1.9.7-15",
        "mocha-phantomjs-core": "^1.1.0",
        "commander": "^2.8.1"
    },
    "devDependencies": {
        "bluebird": "^2.9.25",
        "chai": "^2.3.0",
        "co-mocha": "^1.1.0",
        "coffee-script": "^1.9.2"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
