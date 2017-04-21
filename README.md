# npmdoc-autoprefixer-stylus

#### api documentation for  autoprefixer-stylus (v0.13.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-autoprefixer-stylus.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-autoprefixer-stylus) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-autoprefixer-stylus.svg)](https://travis-ci.org/npmdoc/node-npmdoc-autoprefixer-stylus)

#### autoprefixer for stylus

[![NPM](https://nodei.co/npm/autoprefixer-stylus.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/autoprefixer-stylus)

- [https://npmdoc.github.io/node-npmdoc-autoprefixer-stylus/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-autoprefixer-stylus/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-autoprefixer-stylus/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-autoprefixer-stylus/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-autoprefixer-stylus/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-autoprefixer-stylus/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "autoprefixer-stylus",
    "description": "autoprefixer for stylus",
    "version": "0.13.0",
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "git://github.com/jescalan/autoprefixer-stylus.git"
    },
    "devDependencies": {
        "chai": "3.5.0",
        "coffee-script": "1.12.1",
        "coveralls": "2.11.15",
        "css-parse": "2.0.0",
        "istanbul": "0.4.5",
        "mocha": "3.2.0",
        "mocha-lcov-reporter": "1.2.0",
        "stylus": "0.54.5"
    },
    "author": "Jeff Escalante",
    "main": "index.js",
    "scripts": {
        "test": "mocha",
        "coveralls": "istanbul cover _mocha --report lcovonly -- -R spec && cat ./coverage/lcov.info | coveralls && rm -rf ./coverage",
        "coverage": "istanbul cover _mocha --report html -- -R spec && open coverage/index.html"
    },
    "engines": {
        "node": ">= 4"
    },
    "dependencies": {
        "autoprefixer": "6.6.1",
        "multi-stage-sourcemap": "0.2.1",
        "postcss": "5.2.8"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
