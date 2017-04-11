# test coverage for  [kraken-js (v2.1.0)](https://github.com/krakenjs/kraken-js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-kraken-js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-kraken-js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-kraken-js.svg)](https://travis-ci.org/npmtest/node-npmtest-kraken-js)
#### An express-based Node.js web application bootstrapping module.

[![NPM](https://nodei.co/npm/kraken-js.png?downloads=true)](https://www.npmjs.com/package/kraken-js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-kraken-js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-kraken-js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-kraken-js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-kraken-js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-kraken-js/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-kraken-js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-kraken-js/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-kraken-js/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-kraken-js/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-kraken-js/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-kraken-js%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-kraken-js/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-kraken-js/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-kraken-js%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-kraken-js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-kraken-js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-kraken-js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Erik Toth",
        "email": "ertoth@paypal.com"
    },
    "bugs": {
        "url": "https://github.com/krakenjs/kraken-js/issues"
    },
    "contributors": [
        {
            "name": "Jeff Harrell",
            "email": "jeharrell@paypal.com"
        },
        {
            "name": "Trevor Livingston",
            "email": "trlivingston@paypal.com"
        },
        {
            "name": "Lenny Markus",
            "email": "lmarkus@paypal.com"
        },
        {
            "name": "Jean-Charles Sisk",
            "email": "jsisk@paypal.com"
        }
    ],
    "dependencies": {
        "bluebird": "^2.9.24",
        "body-parser": "^1.12.2",
        "caller": "^1.0.0",
        "compression": "^1.4.3",
        "confit": "^2.0.3",
        "cookie-parser": "^1.3.4",
        "core-util-is": "^1.0.1",
        "debuglog": "^1.0.1",
        "depd": "^1.0.1",
        "endgame": "^1.0.0",
        "express-enrouten": "^1.2.0",
        "express-session": "^1.10.4",
        "formidable": "^1.0.17",
        "lusca": "^1.0.3",
        "meddleware": "^3.0.2",
        "morgan": "^1.5.2",
        "serve-favicon": "^2.2.0",
        "serve-static": "^1.9.2",
        "shortstop": "^1.0.1",
        "shortstop-handlers": "^1.0.0",
        "shortstop-resolve": "^1.0.1",
        "shush": "^1.0.0"
    },
    "description": "An express-based Node.js web application bootstrapping module.",
    "devDependencies": {
        "consolidate": "^0.12.1",
        "dustjs-linkedin": "^2.6.2",
        "ejs": "^2.3.1",
        "express": "^4.8.4",
        "istanbul": "^0.3.13",
        "jade": "^1.9.2",
        "jshint": "^2.6.3",
        "supertest": "^0.15.0",
        "tape": "^4.0.0"
    },
    "directories": {
        "example": "./example",
        "lib": "./lib",
        "test": "./test"
    },
    "dist": {
        "shasum": "7eef061f8153972f05e726a8b64032dbaea2e805",
        "tarball": "https://registry.npmjs.org/kraken-js/-/kraken-js-2.1.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "9bf2e97154292cd9d50e6fcbe8f6cdf793b3d588",
    "homepage": "https://github.com/krakenjs/kraken-js#readme",
    "keywords": [
        "node.js",
        "node",
        "javascript",
        "js",
        "web",
        "express",
        "connect"
    ],
    "licenses": [
        {
            "type": "Apache 2.0",
            "url": "http://www.apache.org/licenses/LICENSE-2.0.html"
        }
    ],
    "main": "index.js",
    "maintainers": [
        {
            "name": "totherik",
            "email": "totherik@gmail.com"
        },
        {
            "name": "jeffharrell",
            "email": "jeff@juxtadesign.com"
        },
        {
            "name": "pvenkatakrishnan",
            "email": "poo.leo@gmail.com"
        },
        {
            "name": "jasisk",
            "email": "jasisk@gmail.com"
        }
    ],
    "name": "kraken-js",
    "optionalDependencies": {},
    "peerDependencies": {
        "express": "^4.8.4"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/krakenjs/kraken-js.git"
    },
    "scripts": {
        "cover": "istanbul cover tape -- test/*.js",
        "lint": "jshint -c .jshintrc index.js lib/ middleware/",
        "test": "tape test/*.js"
    },
    "version": "2.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
