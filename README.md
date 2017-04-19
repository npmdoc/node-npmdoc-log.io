# npmdoc-log.io

#### api documentation for  [log.io (v0.3.4)](http://logio.org)  [![npm package](https://img.shields.io/npm/v/npmdoc-log.io.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-log.io) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-log.io.svg)](https://travis-ci.org/npmdoc/node-npmdoc-log.io)

#### Realtime log monitoring in your browser

[![NPM](https://nodei.co/npm/log.io.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/log.io)

- [https://npmdoc.github.io/node-npmdoc-log.io/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-log.io/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-log.io/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-log.io/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-log.io/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-log.io/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mike Smathers"
    },
    "bin": {
        "log.io-server": "./bin/log.io-server",
        "log.io-harvester": "./bin/log.io-harvester"
    },
    "contributors": [
        {
            "name": "Mike Smathers"
        }
    ],
    "dependencies": {
        "backbone": "~0.9.10",
        "coffee-script": "~1.4.0",
        "express": "~3.0.1",
        "jquery": "~1.8.1",
        "jquery-browserify": "~1.8.1",
        "socket.io": "~0.9.13",
        "socket.io-client": "~0.9.11",
        "underscore": "~1.4.3",
        "winston": "~0.6.2"
    },
    "description": "Realtime log monitoring in your browser",
    "devDependencies": {
        "browserify": "~1.16.6",
        "chai": "~1.4.0",
        "less": "~1.3.3",
        "mocha": "~1.7.4",
        "sinon": "~1.5.2",
        "sinon-chai": "~2.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "db949ff0fac46b84ae69947b9bf68b9f7a69b1eb",
        "tarball": "https://registry.npmjs.org/log.io/-/log.io-0.3.4.tgz"
    },
    "gitHead": "9ecd8991eca00e7a31db986ab0873262e4c49c6d",
    "homepage": "http://logio.org",
    "keywords": [
        "logs",
        "monitoring",
        "realtime",
        "socket.io",
        "node.js",
        "ajax"
    ],
    "maintainers": [
        {
            "name": "msmathers"
        }
    ],
    "name": "log.io",
    "optionalDependencies": {},
    "scripts": {
        "postinstall": "cake ensure:configuration",
        "prepublish": "cake build"
    },
    "version": "0.3.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
