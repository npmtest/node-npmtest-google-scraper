# npmtest-google-scraper

#### basic test coverage for  google-scraper (v1.1.2)  [![npm package](https://img.shields.io/npm/v/npmtest-google-scraper.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-google-scraper) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-google-scraper.svg)](https://travis-ci.org/npmtest/node-npmtest-google-scraper)

#### Extract links from Google SERP

[![NPM](https://nodei.co/npm/google-scraper.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/google-scraper)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-google-scraper/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-google-scraper/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-google-scraper/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-google-scraper/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-google-scraper/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-google-scraper/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-google-scraper/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-google-scraper/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-google-scraper/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-google-scraper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-google-scraper/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-google-scraper/build/test-report.html](https://npmtest.github.io/node-npmtest-google-scraper/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-google-scraper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-google-scraper/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-google-scraper/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-google-scraper/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-google-scraper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-google-scraper/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-google-scraper/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-google-scraper/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "google-scraper",
    "main": "./index",
    "version": "1.1.2",
    "description": "Extract links from Google SERP",
    "author": "Thomas Blanc-hector <thomas.blanc.hector@gmail.com>",
    "keywords": [
        "google",
        "scrape",
        "scraping",
        "scraper"
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/jsnomad/Google-Scraper"
    },
    "license": "MIT",
    "scripts": {
        "compile": "babel -d lib/ src/",
        "prepublish": "npm run compile",
        "lint": "eslint ./src",
        "mocha": "./node_modules/.bin/mocha --timeout 15000 --compilers js:babel-register --require babel-polyfill",
        "test": "npm run compile && npm run lint && npm run mocha"
    },
    "dependencies": {
        "cheerio": "^0.22.0",
        "request": "^2.79.0"
    },
    "devDependencies": {
        "babel-cli": "^6.5.1",
        "babel-eslint": "^7.1.1",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-polyfill": "^6.5.0",
        "babel-preset-es2015": "^6.3.13",
        "babel-register": "^6.3.13",
        "chai": "^3.5.0",
        "eslint": "^3.12.2",
        "eslint-config-airbnb": "^13.0.0",
        "eslint-plugin-import": "^2.2.0",
        "mocha": "^3.2.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
