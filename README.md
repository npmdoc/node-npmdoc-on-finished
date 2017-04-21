# npmdoc-on-finished

#### api documentation for  on-finished (v2.3.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-on-finished.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-on-finished) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-on-finished.svg)](https://travis-ci.org/npmdoc/node-npmdoc-on-finished)

#### Execute a callback when a request closes, finishes, or errors

[![NPM](https://nodei.co/npm/on-finished.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/on-finished)

- [https://npmdoc.github.io/node-npmdoc-on-finished/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-on-finished/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-on-finished/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-on-finished/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-on-finished/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-on-finished/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "on-finished",
    "description": "Execute a callback when a request closes, finishes, or errors",
    "version": "2.3.0",
    "contributors": [
        "Douglas Christopher Wilson <doug@somethingdoug.com>",
        "Jonathan Ong <me@jongleberry.com> (http://jongleberry.com)"
    ],
    "license": "MIT",
    "repository": "jshttp/on-finished",
    "dependencies": {
        "ee-first": "1.1.1"
    },
    "devDependencies": {
        "istanbul": "0.3.9",
        "mocha": "2.2.5"
    },
    "engines": {
        "node": ">= 0.8"
    },
    "files": [
        "HISTORY.md",
        "LICENSE",
        "index.js"
    ],
    "scripts": {
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
