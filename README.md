# npmdoc-camel-case

#### api documentation for  [camel-case (v3.0.0)](https://github.com/blakeembrey/camel-case)  [![npm package](https://img.shields.io/npm/v/npmdoc-camel-case.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-camel-case) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-camel-case.svg)](https://travis-ci.org/npmdoc/node-npmdoc-camel-case)

#### Camel case a string

[![NPM](https://nodei.co/npm/camel-case.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/camel-case)

- [https://npmdoc.github.io/node-npmdoc-camel-case/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-camel-case/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-camel-case/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-camel-case/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-camel-case/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-camel-case/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Blake Embrey",
        "url": "http://blakeembrey.me"
    },
    "bugs": {
        "url": "https://github.com/blakeembrey/camel-case/issues"
    },
    "dependencies": {
        "no-case": "^2.2.0",
        "upper-case": "^1.1.1"
    },
    "description": "Camel case a string",
    "devDependencies": {
        "istanbul": "^0.4.3",
        "mocha": "^2.2.1",
        "standard": "^7.1.2"
    },
    "directories": {},
    "dist": {
        "shasum": "ca3c3688a4e9cf3a4cda777dc4dcbc713249cf73",
        "tarball": "https://registry.npmjs.org/camel-case/-/camel-case-3.0.0.tgz"
    },
    "files": [
        "camel-case.js",
        "camel-case.d.ts",
        "LICENSE"
    ],
    "gitHead": "719ebc39a5bf828f794db64bb1a78c8dd8fef133",
    "homepage": "https://github.com/blakeembrey/camel-case",
    "keywords": [
        "camel",
        "case",
        "camelcase",
        "camel-case",
        "dash",
        "hyphen",
        "dot",
        "underscore",
        "lodash",
        "separator",
        "string",
        "text",
        "convert"
    ],
    "license": "MIT",
    "main": "camel-case.js",
    "maintainers": [
        {
            "name": "blakeembrey"
        }
    ],
    "name": "camel-case",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/blakeembrey/camel-case.git"
    },
    "scripts": {
        "lint": "standard",
        "test": "npm run lint && npm run test-cov",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- -R spec --bail",
        "test-spec": "mocha -- -R spec --bail"
    },
    "typings": "camel-case.d.ts",
    "version": "3.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
