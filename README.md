# npmtest-postcss-smart-import

#### basic test coverage for  [postcss-smart-import (v0.6.12)](https://github.com/sebastian-software/postcss-smart-import#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-postcss-smart-import.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-postcss-smart-import) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-postcss-smart-import.svg)](https://travis-ci.org/npmtest/node-npmtest-postcss-smart-import)

#### PostCSS plugin to import CSS/SugarSS files

[![NPM](https://nodei.co/npm/postcss-smart-import.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/postcss-smart-import)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-postcss-smart-import/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-postcss-smart-import/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-postcss-smart-import/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-postcss-smart-import/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-postcss-smart-import/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-postcss-smart-import/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-postcss-smart-import/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-postcss-smart-import/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-postcss-smart-import/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-postcss-smart-import/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-postcss-smart-import/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-postcss-smart-import/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-postcss-smart-import/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-postcss-smart-import/build/test-report.html](https://npmtest.github.io/node-npmtest-postcss-smart-import/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-postcss-smart-import/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-postcss-smart-import/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-postcss-smart-import/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-postcss-smart-import/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-postcss-smart-import/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-postcss-smart-import/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-postcss-smart-import/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-postcss-smart-import/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sebastian Werner"
    },
    "ava": {
        "require": [
            "babel-register"
        ],
        "babel": "inherit",
        "failWithoutAssertions": false
    },
    "bugs": {
        "url": "https://github.com/sebastian-software/postcss-smart-import/issues"
    },
    "dependencies": {
        "babel-runtime": "^6.23.0",
        "lodash": "^4.17.4",
        "object-assign": "^4.1.1",
        "postcss": "^5.2.17",
        "postcss-sass": "^0.1.0",
        "postcss-scss": "^0.4.1",
        "postcss-value-parser": "^3.3.0",
        "promise-each": "^2.2.0",
        "read-cache": "^1.0.0",
        "resolve": "^1.3.3",
        "sugarss": "^0.2.0"
    },
    "description": "PostCSS plugin to import CSS/SugarSS files",
    "devDependencies": {
        "ava": "^0.19.1",
        "babel-cli": "^6.24.1",
        "babel-core": "^6.24.1",
        "babel-plugin-transform-runtime": "^6.23.0",
        "babel-preset-env": "^1.4.0",
        "babel-register": "^6.24.1",
        "espower": "^2.0.3",
        "flow-bin": "^0.44.2",
        "fs-extra": "^2.1.2",
        "prepublish": "^0.15.4",
        "readable-code": "^2.0.0",
        "rimraf": "^2.6.1"
    },
    "directories": {},
    "dist": {
        "shasum": "6bd50846547383d15332206615265b87b4a6ae89",
        "tarball": "https://registry.npmjs.org/postcss-smart-import/-/postcss-smart-import-0.6.12.tgz"
    },
    "engines": {
        "node": ">=6.0.0",
        "npm": ">=4.0.0",
        "yarn": ">=0.17.0"
    },
    "es2015": "lib/index.es2015.esmodule.js",
    "gitHead": "262d123df9e6ce61e15b09596c38fdb4798270a0",
    "homepage": "https://github.com/sebastian-software/postcss-smart-import#readme",
    "jsnext:main": "lib/index.classic.esmodule.js",
    "keywords": [
        "css",
        "postcss",
        "postcss-plugin",
        "import",
        "sugarss",
        "sass",
        "scss"
    ],
    "license": "MIT",
    "main": "lib/index.classic.commonjs.js",
    "main:modern": "lib/index.modern.commonjs.js",
    "maintainers": [
        {
            "name": "swernerx"
        }
    ],
    "module": "lib/index.classic.esmodule.js",
    "module:modern": "lib/index.modern.esmodule.js",
    "name": "postcss-smart-import",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sebastian-software/postcss-smart-import.git"
    },
    "scripts": {
        "prepublish": "rimraf lib && prepublish",
        "release": "release-it --github.release --npm.publish --non-interactive",
        "release:major": "release-it --github.release --npm.publish --non-interactive --increment major",
        "release:minor": "release-it --github.release --npm.publish --non-interactive --increment minor",
        "test": "ava"
    },
    "version": "0.6.12",
    "warnings": [
        {
            "code": "ENOTSUP",
            "required": {
                "node": ">=6.0.0",
                "npm": ">=4.0.0",
                "yarn": ">=0.17.0"
            },
            "pkgid": "postcss-smart-import@0.6.12"
        },
        {
            "code": "ENOTSUP",
            "required": {
                "node": ">=6.0.0",
                "npm": ">=4.0.0",
                "yarn": ">=0.17.0"
            },
            "pkgid": "postcss-smart-import@0.6.12"
        }
    ],
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
