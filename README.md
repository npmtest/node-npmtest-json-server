# npmtest-json-server

#### basic test coverage for  [json-server (v0.10.0)](https://github.com/typicode/json-server)  [![npm package](https://img.shields.io/npm/v/npmtest-json-server.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-json-server) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-json-server.svg)](https://travis-ci.org/npmtest/node-npmtest-json-server)

#### Serves JSON files through REST routes.

[![NPM](https://nodei.co/npm/json-server.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/json-server)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-json-server/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-json-server/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-json-server/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-json-server/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-json-server/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-json-server/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-json-server/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-json-server/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-json-server/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-json-server/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-json-server/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-json-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-json-server/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-json-server/build/test-report.html](https://npmtest.github.io/node-npmtest-json-server/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-json-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-json-server/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-json-server/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-json-server/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-json-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-json-server/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-json-server/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-json-server/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Typicode"
    },
    "bin": {
        "json-server": "./bin/index.js"
    },
    "bugs": {
        "url": "https://github.com/typicode/json-server/issues"
    },
    "dependencies": {
        "body-parser": "^1.15.2",
        "chalk": "^1.1.3",
        "compression": "^1.6.0",
        "connect-pause": "^0.1.0",
        "cors": "^2.3.0",
        "errorhandler": "^1.2.0",
        "express": "^4.9.5",
        "json-parse-helpfulerror": "^1.0.3",
        "lodash": "^4.11.2",
        "lodash-id": "^0.13.0",
        "lowdb": "^0.15.0",
        "method-override": "^2.1.2",
        "morgan": "^1.3.1",
        "object-assign": "^4.0.1",
        "pluralize": "^3.0.0",
        "request": "^2.72.0",
        "server-destroy": "^1.0.1",
        "shortid": "^2.2.6",
        "update-notifier": "^1.0.2",
        "yargs": "^6.0.0"
    },
    "description": "Serves JSON files through REST routes.",
    "devDependencies": {
        "babel-cli": "^6.24.0",
        "babel-preset-env": "^1.3.2",
        "babel-register": "^6.16.3",
        "cross-env": "^2.0.1",
        "husky": "^0.13.0",
        "markdown-toc": "^0.13.0",
        "mkdirp": "^0.5.1",
        "mocha": "^3.2.0",
        "os-tmpdir": "^1.0.1",
        "pkg-ok": "^1.0.1",
        "rimraf": "^2.5.2",
        "server-ready": "^0.3.1",
        "standard": "^8.3.0",
        "supertest": "^3.0.0",
        "temp-write": "^2.1.0"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "1afc729f3fdaa833eef264df0cfbb756e8dc6417",
        "tarball": "https://registry.npmjs.org/json-server/-/json-server-0.10.0.tgz"
    },
    "engines": {
        "node": ">= 4"
    },
    "gitHead": "5ee5640ef76debbe8e1da7f0741e859d0576ce48",
    "homepage": "https://github.com/typicode/json-server",
    "keywords": [
        "JSON",
        "server",
        "fake",
        "REST",
        "API",
        "prototyping",
        "mock",
        "mocking",
        "test",
        "testing",
        "rest",
        "data",
        "dummy",
        "sandbox"
    ],
    "license": "MIT",
    "main": "./lib/server/index.js",
    "maintainers": [
        {
            "name": "typicode"
        }
    ],
    "name": "json-server",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/typicode/json-server.git"
    },
    "scripts": {
        "build": "babel src -d lib --copy-files",
        "precommit": "npm test",
        "prepublish": "npm run build && pkg-ok",
        "start": "babel-node src/cli/bin",
        "test": "npm run test:cli && npm run test:server && standard",
        "test:cli": "npm run build && cross-env NODE_ENV=test mocha test/cli/*.js",
        "test:server": "cross-env NODE_ENV=test mocha test/server/*.js",
        "toc": "markdown-toc -i README.md"
    },
    "standard": {
        "fix": true,
        "env": {
            "mocha": true
        }
    },
    "version": "0.10.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
