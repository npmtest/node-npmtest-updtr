# npmtest-updtr

#### basic test coverage for  [updtr (v1.0.0)](https://github.com/peerigon/updtr#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-updtr.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-updtr) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-updtr.svg)](https://travis-ci.org/npmtest/node-npmtest-updtr)

#### Update outdated npm modules with zero pain™

[![NPM](https://nodei.co/npm/updtr.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/updtr)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-updtr/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-updtr/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-updtr/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-updtr/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-updtr/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-updtr/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-updtr/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-updtr/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-updtr/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-updtr/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-updtr/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-updtr/build/test-report.html](https://npmtest.github.io/node-npmtest-updtr/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-updtr/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-updtr/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-updtr/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-updtr/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-updtr/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-updtr/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-updtr/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-updtr/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "peerigon"
    },
    "bin": {
        "updtr": "./bin/updtr"
    },
    "bugs": {
        "url": "https://github.com/peerigon/updtr/issues"
    },
    "dependencies": {
        "async": "^1.4.2",
        "cli-spinner": "^0.2.5",
        "colors": "^1.1.2",
        "commander": "^2.8.1",
        "semver": "^5.1.0",
        "unicons": "0.0.3"
    },
    "description": "Update outdated npm modules with zero pain™",
    "devDependencies": {
        "chai": "^3.3.0",
        "eslint": "^2.9.0",
        "eslint-config-peerigon": "^5.0.0",
        "eslint-plugin-jsdoc": "^2.3.1",
        "istanbul": "^0.4.3",
        "mocha": "^2.3.3",
        "rewire": "^2.5.2",
        "sinon": "^1.17.4",
        "sinon-chai": "^2.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "70ea34a58df8ac1228129e1a9ce35051b691b1ee",
        "tarball": "https://registry.npmjs.org/updtr/-/updtr-1.0.0.tgz"
    },
    "engines": {
        "node": ">= 0.10.0",
        "npm": ">= 2.5.0"
    },
    "gitHead": "fb2990930ebd3580afffa4546a51f7d9eece13cb",
    "homepage": "https://github.com/peerigon/updtr#readme",
    "license": "Unlicense",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "flootr"
        },
        {
            "name": "jhnns"
        },
        {
            "name": "matthaias"
        },
        {
            "name": "meaku"
        },
        {
            "name": "peeri"
        }
    ],
    "name": "updtr",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/peerigon/updtr.git"
    },
    "scripts": {
        "coverage": "istanbul cover _mocha -- -R spec",
        "lint": "eslint --fix bin lib test",
        "posttest": "npm run lint",
        "test": "mocha --recursive -R spec",
        "test:watch": "npm run test -- -w -G"
    },
    "version": "1.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
