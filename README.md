# npmtest-osprey

#### test coverage for  [osprey (v0.4.1)](https://github.com/mulesoft/osprey)  [![npm package](https://img.shields.io/npm/v/npmtest-osprey.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-osprey) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-osprey.svg)](https://travis-ci.org/npmtest/node-npmtest-osprey)

#### Generate an API proxy from a RAML definition, which can be used locally or globally for validating API requests and responses

[![NPM](https://nodei.co/npm/osprey.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/osprey)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-osprey/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-osprey/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-osprey/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-osprey/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-osprey/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-osprey/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-osprey/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-osprey/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-osprey/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-osprey/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-osprey/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-osprey/build/test-report.html](https://npmtest.github.io/node-npmtest-osprey/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-osprey/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-osprey/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-osprey/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-osprey/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-osprey/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-osprey/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-osprey/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-osprey/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "MuleSoft, Inc."
    },
    "bin": {
        "osprey": "bin/osprey.js"
    },
    "bugs": {
        "url": "https://github.com/mulesoft/osprey/issues"
    },
    "dependencies": {
        "arrify": "^1.0.0",
        "body-parser": "^1.15.2",
        "compose-middleware": "^2.0.1",
        "compression": "^1.5.2",
        "cookie-session": "^1.2.0",
        "cors": "^2.7.1",
        "datatype-expansion": "^0.1.0",
        "debug": "^2.2.0",
        "finalhandler": "^0.4.0",
        "form-data": "^1.0.0-rc3",
        "http-errors": "^1.3.1",
        "invariant": "^2.2.2",
        "oauth2orize": "^1.0.1",
        "osprey-method-handler": "^0.11.1",
        "osprey-resources": "^0.7.1",
        "osprey-router": "^0.5.1",
        "parseurl": "^1.3.0",
        "passport": "^0.3.0",
        "passport-http": "^0.3.0",
        "passport-http-bearer": "^1.0.1",
        "passport-oauth2-client-password": "^0.1.2",
        "raml-1-parser": "^1.1.19",
        "request-error-handler": "^1.0.0",
        "type-is": "^1.5.5",
        "xtend": "^4.0.0",
        "yargs": "^4.1.0"
    },
    "description": "Generate an API proxy from a RAML definition, which can be used locally or globally for validating API requests and responses",
    "devDependencies": {
        "busboy": "^0.2.9",
        "chai": "^3.5.0",
        "client-oauth2": "^2.0.0",
        "es6-promise": "^3.0.2",
        "express": "^4.13.3",
        "istanbul": "^0.4.5",
        "mocha": "^3.1.0",
        "popsicle": "^5.0.0",
        "popsicle-basic-auth": "^0.1.0",
        "popsicle-server": "^1.0.0",
        "pre-commit": "^1.0.5",
        "rewire": "^2.5.2",
        "server-address": "^1.0.1",
        "standard": "^8.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "9624172098c67386d15d1fe5a4145555ce9269d2",
        "tarball": "https://registry.npmjs.org/osprey/-/osprey-0.4.1.tgz"
    },
    "files": [
        "osprey.js",
        "lib/**",
        "bin/**",
        "LICENSE"
    ],
    "gitHead": "3db55ebf40dc64f499e50b2f33dc6a2ef8247768",
    "homepage": "https://github.com/mulesoft/osprey",
    "keywords": [
        "raml",
        "api",
        "validation",
        "json",
        "security",
        "errors",
        "proxy",
        "xml",
        "query",
        "headers",
        "form"
    ],
    "license": "Apache-2.0",
    "main": "osprey.js",
    "maintainers": [
        {
            "name": "cesaraugustogarcia"
        },
        {
            "name": "christianvogel"
        },
        {
            "name": "jstoiko"
        },
        {
            "name": "juan.coen"
        },
        {
            "name": "mulesoft-npm"
        }
    ],
    "name": "osprey",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/mulesoft/osprey.git"
    },
    "scripts": {
        "lint": "standard",
        "test": "npm run lint && npm run test-cov",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- -R spec --bail --require test/support/globals",
        "test-spec": "mocha -R spec --bail --require test/support/globals"
    },
    "version": "0.4.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
