# npmdoc-faker

#### api documentation for  [faker (v4.1.0)](https://github.com/Marak/Faker.js#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-faker.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-faker) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-faker.svg)](https://travis-ci.org/npmdoc/node-npmdoc-faker)

#### Generate massive amounts of fake contextual data

[![NPM](https://nodei.co/npm/faker.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/faker)

- [https://npmdoc.github.io/node-npmdoc-faker/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-faker/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-faker/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-faker/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-faker/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-faker/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/Marak/Faker.js/issues"
    },
    "contributors": [
        {
            "name": "Marak Squires"
        }
    ],
    "dependencies": {},
    "description": "Generate massive amounts of fake contextual data",
    "devDependencies": {
        "browserify": "5.11.1",
        "gulp": "^3.9.1",
        "gulp-gh-pages": "^0.5.4",
        "gulp-jsdoc3": "^0.2.1",
        "gulp-mustache": "0.4.0",
        "gulp-rename": "1.2.0",
        "gulp-uglify": "1.0.1",
        "ink-docstrap": "1.1.4",
        "jsdoc": "^3.4.0",
        "jshint": "0.9.0",
        "lodash": "^4.6.1",
        "mocha": "^3.2.0",
        "node-minify": "*",
        "optimist": "0.3.5",
        "sinon": "1.4.2",
        "through2": "2.0.0",
        "vinyl-transform": "0.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "1e45bbbecc6774b3c195fad2835109c6d748cc3f",
        "tarball": "https://registry.npmjs.org/faker/-/faker-4.1.0.tgz"
    },
    "gitHead": "57a16b10307f0765fd13a23a3dcc95ec5db19c13",
    "homepage": "https://github.com/Marak/Faker.js#readme",
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "marak"
        }
    ],
    "name": "faker",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/Marak/Faker.js.git"
    },
    "scripts": {
        "build": "cd build && ../node_modules/.bin/gulp && cd ../",
        "doc": "jsdoc -c conf.json -t ./node_modules/ink-docstrap/template -R README.md lib",
        "lint": "jshint ./lib --config ./.jshintrc",
        "test": "mocha test/*.*.js"
    },
    "version": "4.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
