# npmtest-svg2png

#### basic test coverage for  [svg2png (v4.1.1)](https://github.com/domenic/svg2png#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-svg2png.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-svg2png) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-svg2png.svg)](https://travis-ci.org/npmtest/node-npmtest-svg2png)

#### Converts SVGs to PNGs, using PhantomJS

[![NPM](https://nodei.co/npm/svg2png.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/svg2png)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-svg2png/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-svg2png/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-svg2png/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-svg2png/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-svg2png/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-svg2png/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-svg2png/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-svg2png/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-svg2png/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-svg2png/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-svg2png/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-svg2png/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-svg2png/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-svg2png/build/test-report.html](https://npmtest.github.io/node-npmtest-svg2png/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-svg2png/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-svg2png/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-svg2png/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-svg2png/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-svg2png/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-svg2png/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-svg2png/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-svg2png/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Domenic Denicola",
        "url": "https://domenic.me"
    },
    "bin": {
        "svg2png": "bin/svg2png-cli.js"
    },
    "bugs": {
        "url": "https://github.com/domenic/svg2png/issues"
    },
    "dependencies": {
        "file-url": "^2.0.0",
        "phantomjs-prebuilt": "^2.1.14",
        "pn": "^1.0.0",
        "yargs": "^6.5.0"
    },
    "description": "Converts SVGs to PNGs, using PhantomJS",
    "devDependencies": {
        "chai": "^3.5.0",
        "chai-as-promised": "^6.0.0",
        "eslint": "^3.12.2",
        "mkdirp": "^0.5.1",
        "mocha": "^3.2.0",
        "rimraf": "^2.5.4"
    },
    "directories": {},
    "dist": {
        "shasum": "6b9e0398aa418778b6436e127a2fb7f00d499c28",
        "tarball": "https://registry.npmjs.org/svg2png/-/svg2png-4.1.1.tgz"
    },
    "files": [
        "lib/",
        "bin/"
    ],
    "gitHead": "5997ae9452796f480c13506c32cb04d1dc38369e",
    "homepage": "https://github.com/domenic/svg2png#readme",
    "license": "WTFPL",
    "main": "lib/svg2png.js",
    "maintainers": [
        {
            "name": "domenic"
        }
    ],
    "name": "svg2png",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/domenic/svg2png.git"
    },
    "scripts": {
        "lint": "eslint lib test",
        "rebaseline": "node test/success-tests/rebaseline.js",
        "test": "mocha"
    },
    "version": "4.1.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
