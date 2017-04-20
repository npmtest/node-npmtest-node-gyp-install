# npmtest-node-gyp-install

#### basic test coverage for  [node-gyp-install (v2.2.0)](https://github.com/mafintosh/node-gyp-install)  [![npm package](https://img.shields.io/npm/v/npmtest-node-gyp-install.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-gyp-install) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-gyp-install.svg)](https://travis-ci.org/npmtest/node-npmtest-node-gyp-install)

#### Manually download node/iojs header files for usage with node-gyp.

[![NPM](https://nodei.co/npm/node-gyp-install.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-gyp-install)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-gyp-install/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-gyp-install/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-gyp-install/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-gyp-install/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-gyp-install/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-gyp-install/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-gyp-install/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-gyp-install/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-gyp-install/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-gyp-install/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-gyp-install/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-gyp-install/build/test-report.html](https://npmtest.github.io/node-npmtest-node-gyp-install/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-gyp-install/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-gyp-install/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-gyp-install/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-gyp-install/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-gyp-install/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-gyp-install/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-gyp-install/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-gyp-install/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mathias Buus",
        "url": "@mafintosh"
    },
    "bin": {
        "node-gyp-install": "./bin.js"
    },
    "bugs": {
        "url": "https://github.com/mafintosh/node-gyp-install/issues"
    },
    "dependencies": {
        "after-all": "^2.0.2",
        "minimist": "^1.1.2",
        "multi-write-stream": "^1.0.3",
        "npmlog": "^1.2.1",
        "pump": "^1.0.0",
        "semver": "~5.0.3",
        "simple-get": "^1.4.2",
        "tar-fs": "^1.4.2",
        "tar-map-stream": "^1.0.0"
    },
    "description": "Manually download node/iojs header files for usage with node-gyp.",
    "devDependencies": {
        "standard": "^4.5.4"
    },
    "directories": {},
    "dist": {
        "shasum": "11e6e9c5ec29e30311922d5adeb53c478b257d7e",
        "tarball": "https://registry.npmjs.org/node-gyp-install/-/node-gyp-install-2.2.0.tgz"
    },
    "gitHead": "9311919f555fcacc4b997626a8eed427b6311487",
    "homepage": "https://github.com/mafintosh/node-gyp-install",
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "mafintosh"
        },
        {
            "name": "ralphtheninja"
        }
    ],
    "name": "node-gyp-install",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mafintosh/node-gyp-install.git"
    },
    "scripts": {
        "test": "standard && node bin.js && node bin.js"
    },
    "version": "2.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
