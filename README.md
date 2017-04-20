# npmdoc-monq

#### api documentation for  [monq (v0.3.7)](http://github.com/scttnlsn/monq)  [![npm package](https://img.shields.io/npm/v/npmdoc-monq.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-monq) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-monq.svg)](https://travis-ci.org/npmdoc/node-npmdoc-monq)

#### MongoDB-backed job queue for Node.js

[![NPM](https://nodei.co/npm/monq.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/monq)

- [https://npmdoc.github.io/node-npmdoc-monq/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-monq/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-monq/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-monq/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-monq/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-monq/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "monq",
    "version": "0.3.7",
    "description": "MongoDB-backed job queue for Node.js",
    "homepage": "http://github.com/scttnlsn/monq",
    "author": "Scott Nelson <scott@scttnlsn.com>",
    "license": "MIT",
    "main": "./lib/index",
    "scripts": {
        "test": "./node_modules/.bin/mocha",
        "jsdoc2md": "jsdoc2md lib/*.js > API.md"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/scttnlsn/monq.git"
    },
    "dependencies": {
        "mongojs": "^2.1.0"
    },
    "devDependencies": {
        "async": "^1.5.0",
        "jsdoc-to-markdown": "^2.0.1",
        "mocha": "^2.3.4",
        "sinon": "^1.17.2"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
