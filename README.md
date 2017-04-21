# npmdoc-whoport

#### api documentation for  whoport (v0.1.2)  [![npm package](https://img.shields.io/npm/v/npmdoc-whoport.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-whoport) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-whoport.svg)](https://travis-ci.org/npmdoc/node-npmdoc-whoport)

#### A simple cli tool to help you identify and kill processes which use a given port.

[![NPM](https://nodei.co/npm/whoport.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/whoport)

- [https://npmdoc.github.io/node-npmdoc-whoport/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-whoport/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-whoport/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-whoport/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-whoport/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-whoport/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "whoport",
    "version": "0.1.2",
    "description": "A simple cli tool to help you identify and kill processes which use a given port.",
    "repository": {
        "type": "git",
        "url": "https://github.com/flipace/whoport.git"
    },
    "main": "index.js",
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "author": "Patrick Neschkudla <neschkudla@gmail.com>",
    "license": "MIT",
    "bin": {
        "whoport": "./index.js"
    },
    "dependencies": {
        "chalk": "^1.1.3",
        "co": "^4.6.0",
        "co-prompt": "^1.0.0",
        "commander": "^2.9.0",
        "shelljs": "^0.6.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
