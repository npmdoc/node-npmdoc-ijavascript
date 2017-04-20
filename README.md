# npmdoc-ijavascript

#### api documentation for  [ijavascript (v5.0.19)](https://n-riesco.github.io/ijavascript)  [![npm package](https://img.shields.io/npm/v/npmdoc-ijavascript.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ijavascript) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ijavascript.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ijavascript)

#### IJavascript is a Javascript kernel for the Jupyter notebook

[![NPM](https://nodei.co/npm/ijavascript.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ijavascript)

- [https://npmdoc.github.io/node-npmdoc-ijavascript/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ijavascript/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ijavascript/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ijavascript/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-ijavascript/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-ijavascript/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ijavascript",
    "version": "5.0.19",
    "description": "IJavascript is a Javascript kernel for the Jupyter notebook",
    "keywords": [
        "javascript",
        "kernel",
        "ipython",
        "jupyter"
    ],
    "homepage": "https://n-riesco.github.io/ijavascript",
    "bugs": {
        "url": "https://github.com/n-riesco/ijavascript/issues"
    },
    "license": "BSD-3-Clause",
    "author": {
        "author": "Nicolas Riesco",
        "url": "http://www.nicolasriesco.net/"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/n-riesco/ijavascript.git"
    },
    "bin": {
        "ijs": "bin/ijavascript.js",
        "ijsconsole": "bin/ijsconsole.js",
        "ijsinstall": "bin/ijsinstall.js",
        "ijskernel": "lib/kernel.js",
        "ijsnotebook": "bin/ijsnotebook.js"
    },
    "dependencies": {
        "jp-kernel": "0.1.x"
    },
    "devDependencies": {
        "debug": "latest",
        "jsdoc": "latest",
        "jshint": "latest",
        "mocha": "3",
        "uuid": "^3.0.1"
    },
    "scripts": {
        "doc": "python scripts/doc-build.py",
        "doc:publish": "node scripts/doc-publish.js gh-pages https://github.com/n-riesco/ijavascript",
        "lint": "jshint bin lib",
        "test:ijskernel": "mocha test/ijskernel.js",
        "test": "npm run lint && npm run test:ijskernel"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
