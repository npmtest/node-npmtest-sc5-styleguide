# test coverage for  [sc5-styleguide (v1.6.0)](https://github.com/SC5/sc5-styleguide#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-sc5-styleguide.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sc5-styleguide) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sc5-styleguide.svg)](https://travis-ci.org/npmtest/node-npmtest-sc5-styleguide)
#### Styleguide generator is a handy little tool that helps you generate good looking styleguides from stylesheets using KSS notation.

[![NPM](https://nodei.co/npm/sc5-styleguide.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sc5-styleguide)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sc5-styleguide/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sc5-styleguide/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sc5-styleguide/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sc5-styleguide/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sc5-styleguide/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sc5-styleguide/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sc5-styleguide/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sc5-styleguide/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sc5-styleguide/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sc5-styleguide/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sc5-styleguide/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sc5-styleguide/build/test-report.html](https://npmtest.github.io/node-npmtest-sc5-styleguide/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sc5-styleguide/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sc5-styleguide/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sc5-styleguide/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sc5-styleguide/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sc5-styleguide/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sc5-styleguide/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sc5-styleguide/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sc5-styleguide/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "SC5"
    },
    "bin": {
        "styleguide": "./bin/styleguide"
    },
    "bugs": {
        "url": "https://github.com/SC5/sc5-styleguide/issues"
    },
    "dependencies": {
        "autoprefixer": "^6.3.2",
        "basic-auth-connect": "~1.0.0",
        "bemto.pug": "^2.1.0",
        "body-parser": "~1.14.1",
        "chalk": "~1.1.1",
        "cheerio": "^0.19.0",
        "cookie-parser": "~1.4.0",
        "css": "~2.2.0",
        "cssnext": "^1.8.4",
        "express": "~4.13.0",
        "fs-extra": "^0.26.2",
        "gonzales-pe": "4.0.3",
        "gulp": "~3.9.0",
        "gulp-concat": "~2.6.0",
        "gulp-cssnext": "^1.0.1",
        "gulp-mustache": "~2.0.1",
        "gulp-postcss": "^6.1.0",
        "gulp-rename": "^1.2.2",
        "gulp-replace": "^0.5.3",
        "gulp-util": "~3.0.5",
        "kss": "~2.1.0",
        "lodash": "~3.10.1",
        "markdown-it": "^5.1.0",
        "minimatch": "~3.0.0",
        "minimist": "^1.2.0",
        "morgan": "~1.6.0",
        "node-localcache": "^0.1.3",
        "postcss": "^5.0.14",
        "postcss-advanced-variables": "^1.2.2",
        "postcss-color-alpha": "^1.0.3",
        "postcss-color-function": "^2.0.0",
        "postcss-conditionals": "^2.0.1",
        "postcss-custom-media": "^5.0.1",
        "postcss-import": "^8.0.2",
        "postcss-inline-comment": "^2.0.0",
        "postcss-mixins": "^4.0.0",
        "postcss-nested": "^1.0.0",
        "postcss-partial-import": "^1.3.0",
        "pug": "^2.0.0-beta6",
        "q": "~1.4.1",
        "run-sequence": "~1.1.0",
        "socket.io": "~1.4.0",
        "through2": "~2.0.0",
        "vinyl": "~1.1.0",
        "vinyl-fs": "~2.2.1",
        "yargs": "~3.30.0"
    },
    "description": "Styleguide generator is a handy little tool that helps you generate good looking styleguides from stylesheets using KSS notation.",
    "devDependencies": {
        "babel-core": "^6.7.2",
        "babel-preset-es2015": "^6.1.18",
        "babel-register": "^6.7.2",
        "babel-root-import": "^3.2.2",
        "chai": "~3.4.1",
        "conventional-changelog": "git://github.com/sc5/conventional-changelog.git#features/sc-styleguide",
        "coveralls": "~2.11.2",
        "del": "~2.1.0",
        "dependency-check": "~2.5.1",
        "gulp-babel": "^6.1.0",
        "gulp-bower": "~0.0.10",
        "gulp-clean": "^0.3.2",
        "gulp-cssmin": "^0.1.7",
        "gulp-doctoc": "^0.1.2",
        "gulp-gh-pages": "^0.5.4",
        "gulp-ignore": "^2.0.2",
        "gulp-istanbul": "~0.10.0",
        "gulp-jscs": "~3.0.2",
        "gulp-jshint": "~2.0.0",
        "gulp-mocha": "~2.2.0",
        "gulp-ng-annotate": "~1.1.0",
        "gulp-plumber": "~1.0.1",
        "gulp-rimraf": "^0.2.0",
        "gulp-webserver": "^0.9.1",
        "istanbul": "~0.4.1",
        "jscs": "~2.6.0",
        "jshint": "~2.9.1",
        "karma": "~0.13.15",
        "karma-coverage": "~0.5.3",
        "karma-mocha": "~0.2.1",
        "karma-mocha-reporter": "~1.1.2",
        "karma-phantomjs-launcher": "~1.0.0",
        "karma-sinon-chai": "~1.1.0",
        "main-bower-files": "~2.9.0",
        "node-localcache": "^0.1.3",
        "phantomjs-prebuilt": "2.1.7",
        "proxyquire": "~1.7.3",
        "requirefrom": "~0.2.0",
        "sinon": "~1.17.2",
        "sinon-chai": "~2.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "c649b55338d0db84d7bd48df4de10475b1ce633c",
        "tarball": "https://registry.npmjs.org/sc5-styleguide/-/sc5-styleguide-1.6.0.tgz"
    },
    "files": [
        "bin/",
        "lib/",
        "test/",
        ".bowerrc",
        ".jscsrc",
        "demo-gulpfile.js",
        "bower.json",
        "CHANGELOG.md",
        "CHANGELOG_LATEST.md",
        "LICENSE",
        "README.md"
    ],
    "gitHead": "954b9d7937fb66537d02861506f0dead51b76606",
    "homepage": "https://github.com/SC5/sc5-styleguide#readme",
    "keywords": [
        "styleguide"
    ],
    "license": "MIT",
    "main": "./lib/styleguide.js",
    "maintainers": [
        {
            "name": "hannu"
        },
        {
            "name": "jpbackman"
        },
        {
            "name": "junaidrsd"
        },
        {
            "name": "matudelic"
        },
        {
            "name": "simkall"
        },
        {
            "name": "varya"
        }
    ],
    "name": "sc5-styleguide",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/SC5/sc5-styleguide.git"
    },
    "scripts": {
        "build": "gulp build",
        "demo": "gulp --gulpfile ./demo-gulpfile.js watch",
        "depcheck": "dependency-check . --unused --no-dev --entry gulpfile.js --entry demo-gulpfile.js --entry lib/styleguide.js",
        "posttest": "gulp generate-coverage-report",
        "prepublish": "gulp build",
        "pretest": "gulp clean-coverage",
        "test": "gulp test"
    },
    "version": "1.6.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
