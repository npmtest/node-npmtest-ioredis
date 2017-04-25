# npmtest-ioredis

#### basic test coverage for  [ioredis (v2.5.0)](https://github.com/luin/ioredis#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-ioredis.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ioredis) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ioredis.svg)](https://travis-ci.org/npmtest/node-npmtest-ioredis)

#### A delightful, performance-focused Redis client for Node and io.js

[![NPM](https://nodei.co/npm/ioredis.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ioredis)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ioredis/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ioredis/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ioredis/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ioredis/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ioredis/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-ioredis/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-ioredis/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ioredis/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ioredis/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ioredis/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ioredis/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ioredis/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ioredis/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ioredis/build/test-report.html](https://npmtest.github.io/node-npmtest-ioredis/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ioredis/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ioredis/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ioredis/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ioredis/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ioredis/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ioredis/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ioredis/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ioredis/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "luin",
        "url": "http://zihua.li"
    },
    "bugs": {
        "url": "https://github.com/luin/ioredis/issues"
    },
    "config": {
        "commitizen": {
            "path": "./node_modules/cz-conventional-changelog"
        }
    },
    "dependencies": {
        "bluebird": "^3.3.4",
        "cluster-key-slot": "^1.0.6",
        "debug": "^2.2.0",
        "double-ended-queue": "^2.1.0-0",
        "flexbuffer": "0.0.6",
        "lodash": "^4.8.2",
        "redis-commands": "^1.2.0",
        "redis-parser": "^1.3.0"
    },
    "description": "A delightful, performance-focused Redis client for Node and io.js",
    "devDependencies": {
        "chai": "^3.5.0",
        "codeclimate-test-reporter": "0.3.1",
        "cz-conventional-changelog": "^1.1.5",
        "istanbul": "^0.4.2",
        "jsdoc": "^3.4.0",
        "jsdoc-to-markdown": "^1.3.3",
        "matcha": "^0.7.0",
        "mocha": "^2.4.5",
        "redis": "^2.4.2",
        "server-destroy": "^1.0.1",
        "sinon": "^1.17.3"
    },
    "directories": {},
    "dist": {
        "shasum": "fb6fdf0a1a7e0974614c67b6e5e11308a8cf95b9",
        "tarball": "https://registry.npmjs.org/ioredis/-/ioredis-2.5.0.tgz"
    },
    "engines": {
        "iojs": ">= 1.0.0",
        "node": ">= 0.10.16"
    },
    "files": [
        "index.js",
        "lib/"
    ],
    "gitHead": "865219c7776cc8378dd51ab1c1cf89a0db3f7496",
    "homepage": "https://github.com/luin/ioredis#readme",
    "keywords": [
        "redis",
        "cluster",
        "sentinel",
        "pipelining"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "luin"
        }
    ],
    "name": "ioredis",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/luin/ioredis.git"
    },
    "scripts": {
        "bench": "matcha benchmarks/*.js",
        "generate-docs": "jsdoc2md lib/redis.js lib/cluster/index.js lib/commander.js > API.md",
        "test": "NODE_ENV=test mocha",
        "test:cov": "NODE_ENV=test node ./node_modules/istanbul/lib/cli.js cover --preserve-comments ./node_modules/mocha/bin/_mocha -- -R spec"
    },
    "version": "2.5.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
