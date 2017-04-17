# test coverage for  [gemini (v4.18.1)](https://github.com/gemini-testing/gemini)  [![npm package](https://img.shields.io/npm/v/npmtest-gemini.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gemini) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gemini.svg)](https://travis-ci.org/npmtest/node-npmtest-gemini)
#### UI Screenshot testing utility

[![NPM](https://nodei.co/npm/gemini.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gemini)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gemini/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gemini/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gemini/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gemini/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gemini/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gemini/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gemini/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gemini/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gemini/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gemini/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gemini/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gemini/build/test-report.html](https://npmtest.github.io/node-npmtest-gemini/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gemini/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gemini/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gemini/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gemini/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gemini/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gemini/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gemini/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gemini/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sergey Tatarintsev",
        "url": "https://github.com/SevInf"
    },
    "bin": {
        "gemini": "./bin/gemini"
    },
    "bugs": {
        "url": "https://github.com/gemini-testing/gemini/issues"
    },
    "contributors": [
        {
            "name": "The following authors have created the source code of \"Gemini\""
        },
        {
            "name": "published and distributed by YANDEX LLC as the owner:"
        },
        {
            "name": "Sergey Tatarintsev"
        },
        {
            "name": "Anton Usmansky"
        },
        {
            "name": "Evgeniy Konstantinov"
        },
        {
            "name": "Vladimir Alaev"
        },
        {
            "name": "Evgeniy Gavryushin"
        },
        {
            "name": "Andrey Kuznecov"
        },
        {
            "name": "Rostislav Shtanko"
        },
        {
            "name": "Sergey Belov"
        },
        {
            "name": "Ilia Isupov"
        },
        {
            "name": "Dmitriy Dudkevich"
        },
        {
            "name": "Contributors:"
        },
        {
            "name": "Roman Hatipov"
        },
        {
            "name": "Alexandr Tikvach"
        },
        {
            "name": "Leonid Rudenko"
        },
        {
            "name": "Angelina Konstantinova"
        },
        {
            "name": "Misha Berezin"
        },
        {
            "name": "Maxime"
        },
        {
            "name": "David Chin"
        },
        {
            "name": "Ben Edwards"
        },
        {
            "name": "Oleg Apostol"
        },
        {
            "name": "Inna Belaya"
        },
        {
            "name": "Alex Baumgertner"
        },
        {
            "name": "Anton Rudeshko",
            "url": "Tesla"
        }
    ],
    "dependencies": {
        "aliasify": "^1.7.2",
        "bluebird": "^3.4.6",
        "bluebird-q": "^2.1.1",
        "browserify": "^13.0.0",
        "chalk": "^1.1.3",
        "clipboard": "^1.5.15",
        "commander": "^2.8.1",
        "css": "^2.1.0",
        "debug": "^2.2.0",
        "fs-extra": "^0.30.0",
        "gemini-configparser": "^0.1.1",
        "gemini-core": "^1.0.0",
        "gemini-coverage": "^1.0.0",
        "handlebars": "^4.0.5",
        "inherit": "~2.2.1",
        "js-yaml": "^3.2.5",
        "lodash": "^4.15.0",
        "looks-same": "^3.0.0",
        "micromatch": "^2.3.11",
        "node-fetch": "^1.6.3",
        "plugins-loader": "^1.0.1",
        "png-img": "^2.1.0",
        "q-promise-utils": "^1.1.0",
        "qemitter": "^1.0.0",
        "resolve": "^1.1.0",
        "sizzle": "^2.2.0",
        "source-map": "^0.5.3",
        "striptags": "2.1.1",
        "temp": "~0.8.0",
        "uglify-js": "^2.7.3",
        "uglifyify": "^3.0.1",
        "wd": "^0.4.0",
        "worker-farm": "^1.3.1"
    },
    "description": "UI Screenshot testing utility",
    "devDependencies": {
        "app-module-path": "^1.1.0",
        "chai": "^3.5.0",
        "chai-as-promised": "^5.2.0",
        "conventional-changelog-lint": "^1.0.1",
        "coveralls": "^2.11.2",
        "eslint": "^3.1.1",
        "eslint-config-gemini-testing": "^2.0.0",
        "gitbook-cli": "^2.3.0",
        "glob-extra": "^2.0.0",
        "husky": "^0.11.4",
        "istanbul": "^0.4.5",
        "mocha": "^2.1.0",
        "proxyquire": "^1.7.3",
        "sinon": "^1.17.3",
        "standard-version": "^3.0.0"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "0a98cd1ea078daf56aa3c01e50ded7b8ad042777",
        "tarball": "https://registry.npmjs.org/gemini/-/gemini-4.18.1.tgz"
    },
    "engines": {
        "node": ">= 4.0.0"
    },
    "gitHead": "fa6a61c106ee1e0b3840f18373f042c5f2bc9c7f",
    "homepage": "https://github.com/gemini-testing/gemini",
    "keywords": [
        "test",
        "testing",
        "screenshot",
        "selenium",
        "layout"
    ],
    "license": "MIT",
    "main": "api.js",
    "maintainers": [
        {
            "name": "dudagod"
        },
        {
            "name": "egavr"
        },
        {
            "name": "j0tunn"
        },
        {
            "name": "rostik404"
        },
        {
            "name": "scf"
        },
        {
            "name": "seth2810"
        },
        {
            "name": "sevinf"
        },
        {
            "name": "sipayrt"
        },
        {
            "name": "swinx"
        },
        {
            "name": "tormozz48"
        },
        {
            "name": "unlok"
        }
    ],
    "name": "gemini",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/gemini-testing/gemini.git"
    },
    "scripts": {
        "build-site": "npm run prepare-site && gitbook build",
        "commitmsg": "conventional-changelog-lint -e",
        "lint": "eslint .",
        "postpublish": "npm run publish-site",
        "precommit": "npm run lint",
        "prepare-calibrate-script": "uglifyjs ./lib/browser/client-scripts/gemini.calibrate.js -m > ./lib/browser/client-scripts/gemini.calibrate.min.js --support-ie8",
        "prepare-report-script": "browserify ./lib/reporters/html/static/report.js | uglifyjs -o ./lib/reporters/html/static/report.min.js",
        "prepare-site": "gitbook install",
        "prepublish": "npm run prepare-calibrate-script && npm run prepare-report-script",
        "preversion": "npm run lint && npm test",
        "publish-site": "npm run build-site && cd _book && git init && git add -A && git commit -m 'Update site' && git push --force git@github.com:gemini-testing/gemini-testing.github.io.git master",
        "release": "standard-version",
        "test": "istanbul test _mocha -- --recursive test/unit test/functional test/browser",
        "test-browser": "istanbul test _mocha test/browser",
        "test-func": "istanbul test _mocha test/functional",
        "test-unit": "istanbul test _mocha -- --recursive test/unit"
    },
    "version": "4.18.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
