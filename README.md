# npmdoc-sonos

#### api documentation for  sonos (v0.14.1)  [![npm package](https://img.shields.io/npm/v/npmdoc-sonos.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-sonos) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-sonos.svg)](https://travis-ci.org/npmdoc/node-npmdoc-sonos)

#### Node.js Sonos Interface

[![NPM](https://nodei.co/npm/sonos.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sonos)

- [https://npmdoc.github.io/node-npmdoc-sonos/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sonos/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sonos/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sonos/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-sonos/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-sonos/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "sonos",
    "version": "0.14.1",
    "description": "Node.js Sonos Interface",
    "main": "index.js",
    "scripts": {
        "lint": "standard",
        "test": "mocha test/sonos.test.js",
        "test-onsite": "mocha test/",
        "env-run": "npm run $CMD"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/bencevans/node-sonos.git"
    },
    "keywords": [
        "sonos",
        "music",
        "control",
        "play",
        "interface"
    ],
    "author": "Ben Evans <ben@bensbit.co.uk> (http://bensbit.co.uk)",
    "contributors": [
        {
            "name": "Marshall Rose"
        },
        {
            "name": "Stephen Wan"
        }
    ],
    "license": "MIT",
    "dependencies": {
        "debug": "^2.3.3",
        "ip": "1.1.4",
        "request": "^2.79.0",
        "underscore": "1.8.3",
        "upnp-client": "0.0.1",
        "xml2js": "0.4.17"
    },
    "bugs": {
        "url": "http://github.com/bencevans/node-sonos/issues"
    },
    "devDependencies": {
        "mocha": "^3.2.0",
        "standard": "*"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
