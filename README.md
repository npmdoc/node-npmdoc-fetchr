# npmdoc-fetchr

#### basic api documentation for  [fetchr (v0.5.37)](https://github.com/yahoo/fetchr#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-fetchr.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-fetchr) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-fetchr.svg)](https://travis-ci.org/npmdoc/node-npmdoc-fetchr)

#### Fetchr augments Flux applications by allowing Flux stores to be used on server and client to fetch data

[![NPM](https://nodei.co/npm/fetchr.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/fetchr)

- [https://npmdoc.github.io/node-npmdoc-fetchr/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-fetchr/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-fetchr/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-fetchr/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-fetchr/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-fetchr/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Rajiv Tirumalareddy"
    },
    "browser": "./libs/fetcher.client.js",
    "bugs": {
        "url": "https://github.com/yahoo/fetchr/issues"
    },
    "dependencies": {
        "debug": "^2.6.3",
        "es6-promise": "^4.0.2",
        "fumble": "^0.1.0",
        "lodash": "^4.0.1",
        "object-assign": "^4.0.1",
        "xhr": "^2.4.0"
    },
    "description": "Fetchr augments Flux applications by allowing Flux stores to be used on server and client to fetch data",
    "devDependencies": {
        "body-parser": "^1.17.0",
        "chai": "^3.0.0",
        "coveralls": "^2.11.1",
        "express": "^4.15.0",
        "istanbul": "^0.4.5",
        "jshint": "^2.5.1",
        "mocha": "^3.0.2",
        "mockery": "^2.0.0",
        "pre-commit": "^1.0.0",
        "qs": "^6.2.1",
        "request": "^2.81.0",
        "sinon": "^2.0.0",
        "supertest": "^3.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "484dee9f47215a27d5f19b96165be24e0248de62",
        "tarball": "https://registry.npmjs.org/fetchr/-/fetchr-0.5.37.tgz"
    },
    "gitHead": "ebb12000577f59379f6f2c8cf2c0b8aa437a5198",
    "homepage": "https://github.com/yahoo/fetchr#readme",
    "jshintConfig": {
        "node": true
    },
    "keywords": [
        "yahoo",
        "flux",
        "react",
        "fetchr",
        "dispatchr"
    ],
    "licenses": [
        {
            "type": "BSD",
            "url": "https://github.com/yahoo/fetchr/blob/master/LICENSE.md"
        }
    ],
    "main": "index.js",
    "maintainers": [
        {
            "name": "vijar"
        },
        {
            "name": "mridgway"
        },
        {
            "name": "redonkulus"
        },
        {
            "name": "lingyan"
        },
        {
            "name": "kaesonho"
        }
    ],
    "name": "fetchr",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/yahoo/fetchr.git"
    },
    "scripts": {
        "cover": "istanbul cover --dir artifacts -- ./node_modules/mocha/bin/_mocha tests/unit/ --recursive --reporter spec --timeout 20000",
        "lint": "jshint libs tests",
        "test": "NODE_ENV=test mocha tests/unit/ --recursive --reporter spec --timeout 20000"
    },
    "version": "0.5.37",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
