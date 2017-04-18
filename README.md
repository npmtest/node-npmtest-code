# test coverage for  [code (v4.0.0)](https://github.com/hapijs/code#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-code.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-code) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-code.svg)](https://travis-ci.org/npmtest/node-npmtest-code)
#### assertion library

[![NPM](https://nodei.co/npm/code.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/code)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-code/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-code/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-code/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-code/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-code/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-code/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-code/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-code/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-code/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-code/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-code/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-code/build/test-report.html](https://npmtest.github.io/node-npmtest-code/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-code/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-code/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-code/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-code/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-code/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-code/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-code/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-code/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/hapijs/code/issues"
    },
    "dependencies": {
        "hoek": "4.x.x"
    },
    "description": "assertion library",
    "devDependencies": {
        "lab": "11.x.x",
        "markdown-toc": "0.12.x"
    },
    "directories": {},
    "dist": {
        "shasum": "ec7953fd79190052cea2569d63d7b4c0d47c0204",
        "tarball": "https://registry.npmjs.org/code/-/code-4.0.0.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "7ff3fdb75869c8c0e98f9b828f6592683fd4dda3",
    "homepage": "https://github.com/hapijs/code#readme",
    "keywords": [
        "test",
        "expect",
        "assertion"
    ],
    "license": "BSD-3-Clause",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "hueniverse"
        },
        {
            "name": "cjihrig"
        }
    ],
    "name": "code",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/hapijs/code.git"
    },
    "scripts": {
        "test": "lab -v -t 100 -L",
        "test-cov-html": "lab -L -r html -o coverage.html",
        "toc": "node generate-api-toc.js",
        "version": "npm run toc && git add API.md"
    },
    "version": "4.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
