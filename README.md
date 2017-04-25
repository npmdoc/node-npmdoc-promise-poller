# npmdoc-promise-poller

#### basic api documentation for  [promise-poller (v1.5.2)](https://github.com/joeattardi/promise-poller)  [![npm package](https://img.shields.io/npm/v/npmdoc-promise-poller.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-promise-poller) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-promise-poller.svg)](https://travis-ci.org/npmdoc/node-npmdoc-promise-poller)

#### A basic poller built on top of promises

[![NPM](https://nodei.co/npm/promise-poller.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/promise-poller)

- [https://npmdoc.github.io/node-npmdoc-promise-poller/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-promise-poller/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-promise-poller/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-promise-poller/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-promise-poller/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-promise-poller/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Joe Attardi",
        "url": "http://www.thinksincode.com/"
    },
    "bugs": {
        "url": "https://github.com/joeattardi/promise-poller/issues"
    },
    "dependencies": {
        "bluebird": "^3.3.1",
        "debug": "^2.2.0"
    },
    "description": "A basic poller built on top of promises",
    "devDependencies": {
        "babel-cli": "^6.11.4",
        "babel-eslint": "^7.0.0",
        "babel-preset-es2015": "^6.5.0",
        "eslint": "^3.7.1",
        "jasmine": "^2.4.1",
        "jasmine-core": "^2.4.1"
    },
    "directories": {},
    "dist": {
        "shasum": "288b466b0d0b9737acbd928ff54787d01a08cd33",
        "tarball": "https://registry.npmjs.org/promise-poller/-/promise-poller-1.5.2.tgz"
    },
    "gitHead": "de5fbd30cc9d5acfe8644fb5d35a5c62aefcb5bb",
    "homepage": "https://github.com/joeattardi/promise-poller",
    "keywords": [
        "promise",
        "promises",
        "poller",
        "polling",
        "poll",
        "timeout",
        "ajax"
    ],
    "license": "MIT",
    "main": "dist/lib/promise-poller.js",
    "maintainers": [
        {
            "name": "joeattardi"
        }
    ],
    "name": "promise-poller",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/joeattardi/promise-poller.git"
    },
    "scripts": {
        "build": "npm run lint && npm test",
        "clean": "rm -rf dist",
        "compile": "babel -d dist src",
        "lint": "eslint src",
        "prepublish": "npm run build",
        "test": "npm run compile && jasmine JASMINE_CONFIG_PATH=jasmine.json"
    },
    "version": "1.5.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
