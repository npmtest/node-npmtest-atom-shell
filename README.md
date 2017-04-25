# npmtest-atom-shell

#### basic test coverage for  [atom-shell (v0.22.3-1)](https://github.com/mafintosh/atom-shell)  [![npm package](https://img.shields.io/npm/v/npmtest-atom-shell.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-atom-shell) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-atom-shell.svg)](https://travis-ci.org/npmtest/node-npmtest-atom-shell)

#### Install atom-shell prebuilts using npm

[![NPM](https://nodei.co/npm/atom-shell.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/atom-shell)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-atom-shell/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-atom-shell/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-atom-shell/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-atom-shell/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-atom-shell/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-atom-shell/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-atom-shell/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-atom-shell/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-atom-shell/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-atom-shell/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-atom-shell/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-atom-shell/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-atom-shell/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-atom-shell/build/test-report.html](https://npmtest.github.io/node-npmtest-atom-shell/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-atom-shell/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-atom-shell/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-atom-shell/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-atom-shell/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-atom-shell/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-atom-shell/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-atom-shell/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-atom-shell/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mathias Buus"
    },
    "bin": {
        "atom-shell": "run.bat"
    },
    "bugs": {
        "url": "https://github.com/mafintosh/atom-shell/issues"
    },
    "dependencies": {
        "extract-zip": "^1.0.3",
        "nugget": "^1.2.0"
    },
    "description": "Install atom-shell prebuilts using npm",
    "devDependencies": {
        "tape": "^3.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "ff3e68bce2654efc27a36d8e5d83bbcae4fff69b",
        "tarball": "https://registry.npmjs.org/atom-shell/-/atom-shell-0.22.3-1.tgz"
    },
    "gitHead": "aa795507965e5863cc8e5015e8bfa62f21ba4bd5",
    "homepage": "https://github.com/mafintosh/atom-shell",
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "mafintosh"
        },
        {
            "name": "maxogden"
        },
        {
            "name": "zcbenz"
        }
    ],
    "name": "atom-shell",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mafintosh/atom-shell.git"
    },
    "scripts": {
        "install": "node install.js",
        "test": "tape test/*.js"
    },
    "version": "0.22.3-1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
