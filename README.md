# npmtest-algoliasearch

#### basic test-coverage for  [algoliasearch (v3.22.1)](https://github.com/algolia/algoliasearch-client-js)  [![npm package](https://img.shields.io/npm/v/npmtest-algoliasearch.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-algoliasearch) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-algoliasearch.svg)](https://travis-ci.org/npmtest/node-npmtest-algoliasearch)

#### AlgoliaSearch API JavaScript client

[![NPM](https://nodei.co/npm/algoliasearch.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/algoliasearch)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-algoliasearch/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-algoliasearch/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-algoliasearch/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-algoliasearch/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-algoliasearch/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-algoliasearch/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-algoliasearch/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-algoliasearch/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-algoliasearch/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-algoliasearch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-algoliasearch/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-algoliasearch/build/test-report.html](https://npmtest.github.io/node-npmtest-algoliasearch/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-algoliasearch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-algoliasearch/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-algoliasearch/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-algoliasearch/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-algoliasearch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-algoliasearch/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-algoliasearch/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-algoliasearch/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Algolia SAS",
        "url": "https://www.algolia.com"
    },
    "browser": {
        "./index.js": "./src/browser/builds/algoliasearch.js",
        "./lite.js": "./src/browser/builds/algoliasearchLite.js"
    },
    "browserify": {
        "transform": [
            "envify"
        ]
    },
    "bugs": {
        "url": "https://github.com/algolia/algoliasearch-client-js/issues"
    },
    "contributors": [
        {
            "name": "Algolia Team",
            "url": "http://www.algolia.com"
        }
    ],
    "dependencies": {
        "agentkeepalive": "^2.1.1",
        "debug": "2.3.3",
        "envify": "^4.0.0",
        "es6-promise": "^4.0.5",
        "events": "^1.1.0",
        "foreach": "^2.0.5",
        "global": "^4.3.0",
        "inherits": "^2.0.1",
        "isarray": "^2.0.1",
        "load-script": "^1.0.0",
        "object-keys": "^1.0.11",
        "querystring-es3": "^0.2.1",
        "reduce": "^1.0.1",
        "semver": "^5.1.0",
        "tunnel-agent": "^0.4.3"
    },
    "description": "AlgoliaSearch API JavaScript client",
    "devDependencies": {
        "angular": "^1.6.2",
        "async": "^1.5.2",
        "babel-eslint": "^4.1.6",
        "bowser": "^1.3.0",
        "browserify": "^13.3.0",
        "browzers": "^1.3.0",
        "bulk-require": "^1.0.0",
        "bulkify": "^1.2.0",
        "bundle-collapser": "^1.2.1",
        "chance": "^1.0.3",
        "compression": "^1.6.2",
        "deumdify": "^1.2.3",
        "domready": "0.3.0",
        "eslint": "^1.7.3",
        "eslint-config-airbnb": "^0.1.0",
        "eslint-config-algolia": "4.2.0",
        "eslint-plugin-react": "^3.6.3",
        "express": "^4.14.1",
        "faux-jax": "^5.0.6",
        "http-proxy": "^1.13.3",
        "http-server": "^0.9.0",
        "jquery": "^3.0.0",
        "jquery-ajax-transport-xdomainrequest": "^1.0.4",
        "lodash-compat": "^3.10.2",
        "morgan": "^1.8.0",
        "mversion": "^1.10.1",
        "pretty-bytes": "^2.0.1",
        "proxy": "^0.2.4",
        "proxy-agent": "^2.0.0",
        "self-signed": "^1.3.1",
        "server-destroy-vvo": "^1.0.1",
        "sinon": "^1.17.7",
        "superagent": "^3.3.2",
        "tap-bail": "^1.0.0",
        "tap-dot": "^1.0.5",
        "tape": "^4.5.1",
        "uglify-js": "2.6.4",
        "url-parse": "^1.1.1",
        "watchify": "^3.9.0",
        "webpack": "^1.13.1",
        "xhr": "^2.3.3",
        "zuul": "^3.10.1",
        "zuul-ngrok": "^4.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "132abb11134c52a3fd3ded3fcf6acb64f5eb738d",
        "tarball": "https://registry.npmjs.org/algoliasearch/-/algoliasearch-3.22.1.tgz"
    },
    "engines": {
        "node": ">=0.8"
    },
    "files": [
        "src",
        "dist",
        "plugins",
        "index.js",
        "lite.js",
        "reactnative.js",
        "bower.json"
    ],
    "gitHead": "9ebf47d60c54efc81ceee997d8749557df0254fe",
    "homepage": "https://github.com/algolia/algoliasearch-client-js",
    "keywords": [
        "algolia",
        "search",
        "search api",
        "instant search",
        "realtime",
        "autocomplete"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "bobylito"
        },
        {
            "name": "iam4x"
        },
        {
            "name": "pixelastic"
        },
        {
            "name": "proudlygeek"
        },
        {
            "name": "redox"
        },
        {
            "name": "speedblue"
        },
        {
            "name": "vvo"
        }
    ],
    "name": "algoliasearch",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/algolia/algoliasearch-client-js.git"
    },
    "scripts": {
        "build": "./scripts/build",
        "dev": "APP_ENV=development DEBUG=zuul* zuul --no-coverage --local 8080 -- test/run-browser.js",
        "dev-integration": "APP_ENV=development DEBUG=zuul* zuul --no-coverage --local 8080 -- test/run-integration.js",
        "examples": "http-server . -a 0.0.0.0",
        "lint": "./scripts/lint",
        "release": "git clean dist/ -f && git checkout dist/ && yarn && ./scripts/release && APP_ENV=production npm run build",
        "test": "./scripts/test",
        "test-ci": "./scripts/test-ci",
        "watch": "watchify index.js -d -v -s algoliasearch -o dist/algoliasearch.js"
    },
    "version": "3.22.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
