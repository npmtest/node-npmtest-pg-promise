# test coverage for  [pg-promise (v5.6.4)](https://github.com/vitaly-t/pg-promise)  [![npm package](https://img.shields.io/npm/v/npmtest-pg-promise.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pg-promise) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pg-promise.svg)](https://travis-ci.org/npmtest/node-npmtest-pg-promise)
#### Promises interface for PostgreSQL

[![NPM](https://nodei.co/npm/pg-promise.png?downloads=true)](https://www.npmjs.com/package/pg-promise)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pg-promise/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pg-promise/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pg-promise/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pg-promise/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pg-promise/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pg-promise/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pg-promise/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pg-promise/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-pg-promise/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-pg-promise/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-pg-promise%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pg-promise/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pg-promise/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-pg-promise%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pg-promise/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pg-promise/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pg-promise/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Vitaly Tomilov",
        "email": "vitaly.tomilov@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/vitaly-t/pg-promise/issues",
        "email": "vitaly.tomilov@gmail.com"
    },
    "dependencies": {
        "manakin": "0.4",
        "pg": "5.1",
        "pg-minify": "0.4",
        "spex": "1.2"
    },
    "description": "Promises interface for PostgreSQL",
    "devDependencies": {
        "@types/node": "6.x",
        "JSONStream": "1.x",
        "bluebird": "3.x",
        "coveralls": "2.11",
        "eslint": "3.x",
        "istanbul": "0.4",
        "jasmine-node": "1.x",
        "jsdoc": "3.x",
        "pg-query-stream": "1.x",
        "typescript": "2.x"
    },
    "directories": {},
    "dist": {
        "shasum": "80b18a2a1bdd9af7fb0087e01a1b87ada8559a71",
        "tarball": "https://registry.npmjs.org/pg-promise/-/pg-promise-5.6.4.tgz"
    },
    "engines": {
        "node": ">=4.0",
        "npm": ">=2.15"
    },
    "files": [
        "lib",
        "typescript"
    ],
    "gitHead": "2e381403ff346114e169884e6ab8613989cb5356",
    "homepage": "https://github.com/vitaly-t/pg-promise",
    "keywords": [
        "pg",
        "promise",
        "postgres"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "vitaly.tomilov",
            "email": "vitaly.tomilov@gmail.com"
        }
    ],
    "name": "pg-promise",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/vitaly-t/pg-promise.git"
    },
    "scripts": {
        "coverage": "istanbul cover ./node_modules/jasmine-node/bin/jasmine-node test",
        "doc": "jsdoc -c ./jsdoc/jsDoc.json ./jsdoc/README.md",
        "lint": "eslint ./lib",
        "test": "jasmine-node test",
        "test-native": "jasmine-node test --config PG_NATIVE true",
        "travis": "npm run lint && istanbul cover ./node_modules/jasmine-node/bin/jasmine-node test --captureExceptions && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage"
    },
    "typings": "typescript/pg-promise.d.ts",
    "version": "5.6.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
