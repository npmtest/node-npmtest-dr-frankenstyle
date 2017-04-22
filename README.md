# npmtest-dr-frankenstyle

#### basic test coverage for  [dr-frankenstyle (v0.2.8)](https://github.com/pivotal-cf/dr-frankenstyle#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-dr-frankenstyle.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-dr-frankenstyle) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-dr-frankenstyle.svg)](https://travis-ci.org/npmtest/node-npmtest-dr-frankenstyle)

#### Resolves CSS dependencies between node packages

[![NPM](https://nodei.co/npm/dr-frankenstyle.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/dr-frankenstyle)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-dr-frankenstyle/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-dr-frankenstyle/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-dr-frankenstyle/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-dr-frankenstyle/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-dr-frankenstyle/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-dr-frankenstyle/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-dr-frankenstyle/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-dr-frankenstyle/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-dr-frankenstyle/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-dr-frankenstyle/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-dr-frankenstyle/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-dr-frankenstyle/build/test-report.html](https://npmtest.github.io/node-npmtest-dr-frankenstyle/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-dr-frankenstyle/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-dr-frankenstyle/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-dr-frankenstyle/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-dr-frankenstyle/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-dr-frankenstyle/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-dr-frankenstyle/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-dr-frankenstyle/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-dr-frankenstyle/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Pivotal Software, Inc"
    },
    "bin": {
        "dr-frankenstyle": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/pivotal-cf/dr-frankenstyle/issues"
    },
    "dependencies": {
        "babel-runtime": "5.5.4",
        "dag-map": "^1.0.2",
        "debuglog": "^1.0.1",
        "es6-promisify": "^1.1.1",
        "event-stream": "^3.3.1",
        "fs-promise": "^0.3.1",
        "glob": "^5.0.9",
        "lodash.uniq": "^3.1.0",
        "mkdirp": "^0.5.0",
        "stream-reduce": "^1.0.3",
        "through2": "^0.6.5",
        "vinyl": "^1.2.0",
        "vinyl-fs": "^2.4.3",
        "yargs": "^3.9.0"
    },
    "description": "Resolves CSS dependencies between node packages",
    "devDependencies": {
        "babel": "^5.5.4",
        "babel-eslint": "^4.0.10",
        "child-process-promise": "^1.1.0",
        "del": "^1.1.1",
        "gulp": "^3.8.11",
        "gulp-babel": "^5.1.0",
        "gulp-eslint": "^0.12.0",
        "gulp-header": "^1.2.2",
        "gulp-jasmine": "^2.0.1",
        "gulp-load-plugins": "^0.10.0",
        "gulp-plumber": "^1.0.0",
        "highland": "^2.5.0",
        "jasmine": "^2.2.0",
        "jasmine-es6": "0.0.2",
        "merge-stream": "^0.1.7",
        "npm": "^2.10.1",
        "proxyquire": "^1.5.0",
        "require-dir": "^0.3.0",
        "rimraf": "^2.3.2",
        "run-sequence": "^1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "aef782dadeac27cd3e543b13220c263d29ace946",
        "tarball": "https://registry.npmjs.org/dr-frankenstyle/-/dr-frankenstyle-0.2.8.tgz"
    },
    "homepage": "https://github.com/pivotal-cf/dr-frankenstyle#readme",
    "keywords": [
        "pivotal ui",
        "css"
    ],
    "license": "MIT",
    "main": "dr-frankenstyle.js",
    "maintainers": [
        {
            "name": "atomanyih"
        },
        {
            "name": "charleshansen"
        },
        {
            "name": "ctaymor"
        },
        {
            "name": "d-reinhold"
        },
        {
            "name": "kennyw1019"
        },
        {
            "name": "pivotal-ui"
        },
        {
            "name": "rdy"
        },
        {
            "name": "stubbornella"
        },
        {
            "name": "vinsonchuong"
        }
    ],
    "name": "dr-frankenstyle",
    "optionalDependencies": {},
    "preferGlobal": "true",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/pivotal-cf/dr-frankenstyle.git"
    },
    "scripts": {
        "test": "gulp"
    },
    "version": "0.2.8"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
