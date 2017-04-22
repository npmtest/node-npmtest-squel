# npmtest-squel

#### basic test coverage for  [squel (v5.9.1)](https://github.com/hiddentao/squel#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-squel.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-squel) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-squel.svg)](https://travis-ci.org/npmtest/node-npmtest-squel)

#### SQL query string builder

[![NPM](https://nodei.co/npm/squel.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/squel)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-squel/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-squel/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-squel/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-squel/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-squel/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-squel/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-squel/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-squel/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-squel/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-squel/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-squel/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-squel/build/test-report.html](https://npmtest.github.io/node-npmtest-squel/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-squel/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-squel/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-squel/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-squel/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-squel/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-squel/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-squel/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-squel/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ramesh Nair",
        "url": "http://www.hiddentao.com/"
    },
    "bugs": {
        "url": "https://github.com/hiddentao/squel/issues"
    },
    "contributors": [
        {
            "name": "Ramesh Nair",
            "url": "http://www.hiddentao.com/"
        },
        {
            "name": "Sergej Brjuchanov"
        }
    ],
    "dependencies": {},
    "description": "SQL query string builder",
    "devDependencies": {
        "babel-preset-es2015": "^6.6.0",
        "chai": "1.5.x",
        "coffee-script": "^1.10.0",
        "gulp": "^3.9.1",
        "gulp-babel": "^6.1.2",
        "gulp-concat": "^2.6.0",
        "gulp-insert": "^0.5.0",
        "gulp-istanbul": "^1.1.1",
        "gulp-mocha": "^2.2.0",
        "gulp-replace": "^0.5.4",
        "gulp-uglify": "^1.5.3",
        "gulp-umd": "^0.2.0",
        "load-grunt-tasks": "~0.1.0",
        "mocha": "1.9.x",
        "run-sequence": "^1.1.5",
        "sinon": "1.6.x",
        "time-grunt": "~0.1.1",
        "uglify-js": "1.3.x",
        "underscore": "1.4.x",
        "yargs": "^4.7.1"
    },
    "directories": {},
    "dist": {
        "shasum": "126b6a55a863d72af5bac97fbf1b6f02591ebc93",
        "tarball": "https://registry.npmjs.org/squel/-/squel-5.9.1.tgz"
    },
    "engines": {
        "node": ">= 0.12.0"
    },
    "gitHead": "1bde13554eb6f04349e8b14d018281cda905e967",
    "homepage": "https://github.com/hiddentao/squel#readme",
    "keywords": [
        "sql",
        "database",
        "rdbms"
    ],
    "main": "dist/squel.js",
    "maintainers": [
        {
            "name": "hiddentao"
        }
    ],
    "name": "squel",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/hiddentao/squel.git"
    },
    "scripts": {
        "build": "gulp",
        "prepublish": "npm run build",
        "test": "gulp"
    },
    "version": "5.9.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
