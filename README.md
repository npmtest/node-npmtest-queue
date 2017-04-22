# npmtest-queue

#### basic test coverage for  [queue (v4.2.1)](https://github.com/jessetane/queue#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-queue.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-queue) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-queue.svg)](https://travis-ci.org/npmtest/node-npmtest-queue)

#### asynchronous function queue with adjustable concurrency

[![NPM](https://nodei.co/npm/queue.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/queue)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-queue/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-queue/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-queue/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-queue/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-queue/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-queue/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-queue/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-queue/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-queue/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-queue/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-queue/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-queue/build/test-report.html](https://npmtest.github.io/node-npmtest-queue/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-queue/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-queue/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-queue/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-queue/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-queue/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-queue/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-queue/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-queue/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jesse Tane"
    },
    "bugs": {
        "url": "https://github.com/jessetane/queue/issues"
    },
    "dependencies": {
        "inherits": "~2.0.0"
    },
    "description": "asynchronous function queue with adjustable concurrency",
    "devDependencies": {
        "browserify": "^5.9.1",
        "coveralls": "^2.11.2",
        "istanbul": "^0.3.2",
        "standard": "^8.6.0",
        "tape": "^2.14.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5318ed8a227a9734e6bfeeb24a057782922751db",
        "tarball": "https://registry.npmjs.org/queue/-/queue-4.2.1.tgz"
    },
    "gitHead": "74ae20f7433a2ed6c50bef78bb10ba1cf74514c0",
    "homepage": "https://github.com/jessetane/queue#readme",
    "keywords": [
        "queue",
        "async",
        "asynchronous",
        "synchronous",
        "job",
        "task",
        "concurrency",
        "concurrent"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "jessetane"
        }
    ],
    "name": "queue",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jessetane/queue.git"
    },
    "scripts": {
        "example": "node example",
        "lint": "standard",
        "test": "standard && node test",
        "test-browser": "standard && browserify test/index.js > test/bundle.js && echo \"open test/index.html in your browser\"",
        "travis": "standard && istanbul cover test --report lcovonly && cat coverage/lcov.info | coveralls"
    },
    "version": "4.2.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
