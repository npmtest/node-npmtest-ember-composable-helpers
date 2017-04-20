# npmtest-ember-composable-helpers

#### basic test coverage for  [ember-composable-helpers (v2.0.1)](https://github.com/DockYard/ember-composable-helpers)  [![npm package](https://img.shields.io/npm/v/npmtest-ember-composable-helpers.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ember-composable-helpers) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ember-composable-helpers.svg)](https://travis-ci.org/npmtest/node-npmtest-ember-composable-helpers)

#### Composable helpers for Ember

[![NPM](https://nodei.co/npm/ember-composable-helpers.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ember-composable-helpers)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ember-composable-helpers/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-composable-helpers/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ember-composable-helpers/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ember-composable-helpers/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ember-composable-helpers/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ember-composable-helpers/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ember-composable-helpers/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ember-composable-helpers/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ember-composable-helpers/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-composable-helpers/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ember-composable-helpers/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ember-composable-helpers/build/test-report.html](https://npmtest.github.io/node-npmtest-ember-composable-helpers/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ember-composable-helpers/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ember-composable-helpers/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ember-composable-helpers/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ember-composable-helpers/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ember-composable-helpers/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ember-composable-helpers/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ember-composable-helpers/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ember-composable-helpers/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ember-composable-helpers",
    "version": "2.0.1",
    "description": "Composable helpers for Ember",
    "directories": {
        "doc": "doc",
        "test": "tests"
    },
    "scripts": {
        "build": "ember build",
        "start": "ember server",
        "node-test": "mocha test --recursive --reporter spec",
        "test": "ember try:each"
    },
    "repository": "https://github.com/DockYard/ember-composable-helpers",
    "bugs": "https://github.com/DockYard/ember-composable-helpers/issues",
    "homepage": "https://github.com/DockYard/ember-composable-helpers",
    "engines": {
        "node": ">= 0.10.0"
    },
    "author": [
        "Lauren Tan <arr@sugarpirate.com>",
        "Marten Schilstra <mail@martenschilstra.nl>"
    ],
    "license": "MIT",
    "devDependencies": {
        "broccoli-asset-rev": "^2.4.5",
        "chai": "^3.5.0",
        "ember-ajax": "^2.4.1",
        "ember-cli": "2.11.0",
        "ember-cli-app-version": "^2.0.0",
        "ember-cli-dependency-checker": "^1.3.0",
        "ember-cli-htmlbars": "^1.1.1",
        "ember-cli-htmlbars-inline-precompile": "^0.3.3",
        "ember-cli-inject-live-reload": "^1.4.1",
        "ember-cli-jshint": "^2.0.1",
        "ember-cli-qunit": "^3.0.1",
        "ember-cli-release": "^0.2.9",
        "ember-cli-shims": "^1.0.2",
        "ember-cli-sri": "^2.1.0",
        "ember-cli-test-loader": "^1.1.0",
        "ember-cli-uglify": "^1.2.0",
        "ember-data": "2.11.0",
        "ember-disable-prototype-extensions": "^1.1.0",
        "ember-disable-proxy-controllers": "^1.0.1",
        "ember-each-in-polyfill": "^0.1.4",
        "ember-exam": "0.4.6",
        "ember-export-application-global": "^1.0.5",
        "ember-inflector": "1.9.6",
        "ember-load-initializers": "^0.6.0",
        "ember-resolver": "^2.0.3",
        "ember-sinon": "0.5.0",
        "ember-source": "^2.11.0",
        "ember-suave": "4.0.0",
        "loader.js": "^4.0.10",
        "mocha": "^2.4.5"
    },
    "keywords": [
        "ember-addon",
        "helpers",
        "compose",
        "group-by",
        "map-by",
        "filter-by",
        "sort-by",
        "take",
        "drop",
        "compute"
    ],
    "dependencies": {
        "broccoli-funnel": "^1.0.1",
        "ember-cli-babel": "^5.1.7"
    },
    "ember-addon": {
        "configPath": "tests/dummy/config"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
