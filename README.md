# npmdoc-node-osc

#### api documentation for  node-osc (v2.1.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-osc.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-osc) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-osc.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-osc)

#### pyOSC inspired library

[![NPM](https://nodei.co/npm/node-osc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-osc)

- [https://npmdoc.github.io/node-npmdoc-node-osc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-osc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-osc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-osc/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-osc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-osc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "node-osc",
    "description": "pyOSC inspired library",
    "version": "2.1.0",
    "main": "lib/index.js",
    "author": {
        "name": "Myles Borins"
    },
    "license": "LGPL-2.1",
    "scripts": {
        "test": "npm run lint && npm run tap",
        "tap": "tap test/*.js",
        "lint": "eslint **/*.js"
    },
    "contributors": [
        {
            "name": "Hans Hübner"
        },
        {
            "name": "Andy Smith"
        },
        {
            "name": "Myles Borins"
        }
    ],
    "dependencies": {
        "jspack": "0.0.4",
        "osc-min": "^1.1.1",
        "semver": "^5.1.0"
    },
    "keywords": [
        "osc",
        "udp"
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/MylesBorins/node-osc.git"
    },
    "devDependencies": {
        "eslint": "^3.18.0",
        "tap": "^10.3.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
