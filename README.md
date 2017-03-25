# api documentation for  [faker (v4.1.0)](https://github.com/Marak/Faker.js#readme)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-faker.svg)](https://travis-ci.org/npmdoc/node-npmdoc-faker)
#### Generate massive amounts of fake contextual data

[![NPM](https://nodei.co/npm/faker.png?downloads=true)](https://www.npmjs.com/package/faker)

[![apidoc](https://npmdoc.github.io/node-npmdoc-faker/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-faker_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-faker/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-faker/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/Marak/Faker.js/issues"
    },
    "contributors": [
        {
            "name": "Marak Squires",
            "email": "marak.squires@gmail.com"
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
            "name": "marak",
            "email": "marak.squires@gmail.com"
        }
    ],
    "name": "faker",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
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



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module faker](#apidoc.module.faker)
1.  [function <span class="apidocSignatureSpan">faker.</span>fake (str)](#apidoc.element.faker.fake)
1.  [function <span class="apidocSignatureSpan">faker.</span>index (opts)](#apidoc.element.faker.index)
1.  object <span class="apidocSignatureSpan">faker.</span>address
1.  object <span class="apidocSignatureSpan">faker.</span>commerce
1.  object <span class="apidocSignatureSpan">faker.</span>company
1.  object <span class="apidocSignatureSpan">faker.</span>database
1.  object <span class="apidocSignatureSpan">faker.</span>date
1.  object <span class="apidocSignatureSpan">faker.</span>definitions
1.  object <span class="apidocSignatureSpan">faker.</span>finance
1.  object <span class="apidocSignatureSpan">faker.</span>hacker
1.  object <span class="apidocSignatureSpan">faker.</span>helpers
1.  object <span class="apidocSignatureSpan">faker.</span>iban
1.  object <span class="apidocSignatureSpan">faker.</span>image
1.  object <span class="apidocSignatureSpan">faker.</span>index.prototype
1.  object <span class="apidocSignatureSpan">faker.</span>internet
1.  object <span class="apidocSignatureSpan">faker.</span>locales
1.  object <span class="apidocSignatureSpan">faker.</span>lorem
1.  object <span class="apidocSignatureSpan">faker.</span>name
1.  object <span class="apidocSignatureSpan">faker.</span>phone
1.  object <span class="apidocSignatureSpan">faker.</span>random
1.  object <span class="apidocSignatureSpan">faker.</span>system
1.  string <span class="apidocSignatureSpan">faker.</span>locale
1.  string <span class="apidocSignatureSpan">faker.</span>localeFallback

#### [module faker.address](#apidoc.module.faker.address)
1.  [function <span class="apidocSignatureSpan">faker.address.</span>city ()](#apidoc.element.faker.address.city)
1.  [function <span class="apidocSignatureSpan">faker.address.</span>cityPrefix ()](#apidoc.element.faker.address.cityPrefix)
1.  [function <span class="apidocSignatureSpan">faker.address.</span>citySuffix ()](#apidoc.element.faker.address.citySuffix)
1.  [function <span class="apidocSignatureSpan">faker.address.</span>country ()](#apidoc.element.faker.address.country)
1.  [function <span class="apidocSignatureSpan">faker.address.</span>countryCode ()](#apidoc.element.faker.address.countryCode)
1.  [function <span class="apidocSignatureSpan">faker.address.</span>county ()](#apidoc.element.faker.address.county)
1.  [function <span class="apidocSignatureSpan">faker.address.</span>latitude ()](#apidoc.element.faker.address.latitude)
1.  [function <span class="apidocSignatureSpan">faker.address.</span>longitude ()](#apidoc.element.faker.address.longitude)
1.  [function <span class="apidocSignatureSpan">faker.address.</span>secondaryAddress ()](#apidoc.element.faker.address.secondaryAddress)
1.  [function <span class="apidocSignatureSpan">faker.address.</span>state ()](#apidoc.element.faker.address.state)
1.  [function <span class="apidocSignatureSpan">faker.address.</span>stateAbbr ()](#apidoc.element.faker.address.stateAbbr)
1.  [function <span class="apidocSignatureSpan">faker.address.</span>streetAddress ()](#apidoc.element.faker.address.streetAddress)
1.  [function <span class="apidocSignatureSpan">faker.address.</span>streetName ()](#apidoc.element.faker.address.streetName)
1.  [function <span class="apidocSignatureSpan">faker.address.</span>streetPrefix ()](#apidoc.element.faker.address.streetPrefix)
1.  [function <span class="apidocSignatureSpan">faker.address.</span>streetSuffix ()](#apidoc.element.faker.address.streetSuffix)
1.  [function <span class="apidocSignatureSpan">faker.address.</span>zipCode ()](#apidoc.element.faker.address.zipCode)

#### [module faker.commerce](#apidoc.module.faker.commerce)
1.  [function <span class="apidocSignatureSpan">faker.commerce.</span>color ()](#apidoc.element.faker.commerce.color)
1.  [function <span class="apidocSignatureSpan">faker.commerce.</span>department ()](#apidoc.element.faker.commerce.department)
1.  [function <span class="apidocSignatureSpan">faker.commerce.</span>price ()](#apidoc.element.faker.commerce.price)
1.  [function <span class="apidocSignatureSpan">faker.commerce.</span>product ()](#apidoc.element.faker.commerce.product)
1.  [function <span class="apidocSignatureSpan">faker.commerce.</span>productAdjective ()](#apidoc.element.faker.commerce.productAdjective)
1.  [function <span class="apidocSignatureSpan">faker.commerce.</span>productMaterial ()](#apidoc.element.faker.commerce.productMaterial)
1.  [function <span class="apidocSignatureSpan">faker.commerce.</span>productName ()](#apidoc.element.faker.commerce.productName)

#### [module faker.company](#apidoc.module.faker.company)
1.  [function <span class="apidocSignatureSpan">faker.company.</span>bs ()](#apidoc.element.faker.company.bs)
1.  [function <span class="apidocSignatureSpan">faker.company.</span>bsAdjective ()](#apidoc.element.faker.company.bsAdjective)
1.  [function <span class="apidocSignatureSpan">faker.company.</span>bsBuzz ()](#apidoc.element.faker.company.bsBuzz)
1.  [function <span class="apidocSignatureSpan">faker.company.</span>bsNoun ()](#apidoc.element.faker.company.bsNoun)
1.  [function <span class="apidocSignatureSpan">faker.company.</span>catchPhrase ()](#apidoc.element.faker.company.catchPhrase)
1.  [function <span class="apidocSignatureSpan">faker.company.</span>catchPhraseAdjective ()](#apidoc.element.faker.company.catchPhraseAdjective)
1.  [function <span class="apidocSignatureSpan">faker.company.</span>catchPhraseDescriptor ()](#apidoc.element.faker.company.catchPhraseDescriptor)
1.  [function <span class="apidocSignatureSpan">faker.company.</span>catchPhraseNoun ()](#apidoc.element.faker.company.catchPhraseNoun)
1.  [function <span class="apidocSignatureSpan">faker.company.</span>companyName ()](#apidoc.element.faker.company.companyName)
1.  [function <span class="apidocSignatureSpan">faker.company.</span>companySuffix ()](#apidoc.element.faker.company.companySuffix)
1.  [function <span class="apidocSignatureSpan">faker.company.</span>suffixes ()](#apidoc.element.faker.company.suffixes)

#### [module faker.database](#apidoc.module.faker.database)
1.  [function <span class="apidocSignatureSpan">faker.database.</span>collation ()](#apidoc.element.faker.database.collation)
1.  [function <span class="apidocSignatureSpan">faker.database.</span>column ()](#apidoc.element.faker.database.column)
1.  [function <span class="apidocSignatureSpan">faker.database.</span>engine ()](#apidoc.element.faker.database.engine)
1.  [function <span class="apidocSignatureSpan">faker.database.</span>type ()](#apidoc.element.faker.database.type)

#### [module faker.date](#apidoc.module.faker.date)
1.  [function <span class="apidocSignatureSpan">faker.date.</span>between ()](#apidoc.element.faker.date.between)
1.  [function <span class="apidocSignatureSpan">faker.date.</span>future ()](#apidoc.element.faker.date.future)
1.  [function <span class="apidocSignatureSpan">faker.date.</span>month ()](#apidoc.element.faker.date.month)
1.  [function <span class="apidocSignatureSpan">faker.date.</span>past ()](#apidoc.element.faker.date.past)
1.  [function <span class="apidocSignatureSpan">faker.date.</span>recent ()](#apidoc.element.faker.date.recent)
1.  [function <span class="apidocSignatureSpan">faker.date.</span>weekday ()](#apidoc.element.faker.date.weekday)

#### [module faker.finance](#apidoc.module.faker.finance)
1.  [function <span class="apidocSignatureSpan">faker.finance.</span>account ()](#apidoc.element.faker.finance.account)
1.  [function <span class="apidocSignatureSpan">faker.finance.</span>accountName ()](#apidoc.element.faker.finance.accountName)
1.  [function <span class="apidocSignatureSpan">faker.finance.</span>amount ()](#apidoc.element.faker.finance.amount)
1.  [function <span class="apidocSignatureSpan">faker.finance.</span>bic ()](#apidoc.element.faker.finance.bic)
1.  [function <span class="apidocSignatureSpan">faker.finance.</span>bitcoinAddress ()](#apidoc.element.faker.finance.bitcoinAddress)
1.  [function <span class="apidocSignatureSpan">faker.finance.</span>currencyCode ()](#apidoc.element.faker.finance.currencyCode)
1.  [function <span class="apidocSignatureSpan">faker.finance.</span>currencyName ()](#apidoc.element.faker.finance.currencyName)
1.  [function <span class="apidocSignatureSpan">faker.finance.</span>currencySymbol ()](#apidoc.element.faker.finance.currencySymbol)
1.  [function <span class="apidocSignatureSpan">faker.finance.</span>iban ()](#apidoc.element.faker.finance.iban)
1.  [function <span class="apidocSignatureSpan">faker.finance.</span>mask ()](#apidoc.element.faker.finance.mask)
1.  [function <span class="apidocSignatureSpan">faker.finance.</span>transactionType ()](#apidoc.element.faker.finance.transactionType)

#### [module faker.hacker](#apidoc.module.faker.hacker)
1.  [function <span class="apidocSignatureSpan">faker.hacker.</span>abbreviation ()](#apidoc.element.faker.hacker.abbreviation)
1.  [function <span class="apidocSignatureSpan">faker.hacker.</span>adjective ()](#apidoc.element.faker.hacker.adjective)
1.  [function <span class="apidocSignatureSpan">faker.hacker.</span>ingverb ()](#apidoc.element.faker.hacker.ingverb)
1.  [function <span class="apidocSignatureSpan">faker.hacker.</span>noun ()](#apidoc.element.faker.hacker.noun)
1.  [function <span class="apidocSignatureSpan">faker.hacker.</span>phrase ()](#apidoc.element.faker.hacker.phrase)
1.  [function <span class="apidocSignatureSpan">faker.hacker.</span>verb ()](#apidoc.element.faker.hacker.verb)

#### [module faker.helpers](#apidoc.module.faker.helpers)
1.  [function <span class="apidocSignatureSpan">faker.helpers.</span>contextualCard ()](#apidoc.element.faker.helpers.contextualCard)
1.  [function <span class="apidocSignatureSpan">faker.helpers.</span>createCard ()](#apidoc.element.faker.helpers.createCard)
1.  [function <span class="apidocSignatureSpan">faker.helpers.</span>createTransaction ()](#apidoc.element.faker.helpers.createTransaction)
1.  [function <span class="apidocSignatureSpan">faker.helpers.</span>mustache (str, data)](#apidoc.element.faker.helpers.mustache)
1.  [function <span class="apidocSignatureSpan">faker.helpers.</span>randomize (array)](#apidoc.element.faker.helpers.randomize)
1.  [function <span class="apidocSignatureSpan">faker.helpers.</span>replaceSymbolWithNumber (string, symbol)](#apidoc.element.faker.helpers.replaceSymbolWithNumber)
1.  [function <span class="apidocSignatureSpan">faker.helpers.</span>replaceSymbols (string)](#apidoc.element.faker.helpers.replaceSymbols)
1.  [function <span class="apidocSignatureSpan">faker.helpers.</span>shuffle (o)](#apidoc.element.faker.helpers.shuffle)
1.  [function <span class="apidocSignatureSpan">faker.helpers.</span>slugify (string)](#apidoc.element.faker.helpers.slugify)
1.  [function <span class="apidocSignatureSpan">faker.helpers.</span>userCard ()](#apidoc.element.faker.helpers.userCard)

#### [module faker.iban](#apidoc.module.faker.iban)
1.  [function <span class="apidocSignatureSpan">faker.iban.</span>mod97 (digitStr)](#apidoc.element.faker.iban.mod97)
1.  [function <span class="apidocSignatureSpan">faker.iban.</span>toDigitString (str)](#apidoc.element.faker.iban.toDigitString)
1.  object <span class="apidocSignatureSpan">faker.iban.</span>alpha
1.  object <span class="apidocSignatureSpan">faker.iban.</span>formats
1.  object <span class="apidocSignatureSpan">faker.iban.</span>iso3166
1.  object <span class="apidocSignatureSpan">faker.iban.</span>pattern10
1.  object <span class="apidocSignatureSpan">faker.iban.</span>pattern100

#### [module faker.image](#apidoc.module.faker.image)
1.  [function <span class="apidocSignatureSpan">faker.</span>image ()](#apidoc.element.faker.image.image)
1.  [function <span class="apidocSignatureSpan">faker.image.</span>abstract ()](#apidoc.element.faker.image.abstract)
1.  [function <span class="apidocSignatureSpan">faker.image.</span>animals ()](#apidoc.element.faker.image.animals)
1.  [function <span class="apidocSignatureSpan">faker.image.</span>avatar ()](#apidoc.element.faker.image.avatar)
1.  [function <span class="apidocSignatureSpan">faker.image.</span>business ()](#apidoc.element.faker.image.business)
1.  [function <span class="apidocSignatureSpan">faker.image.</span>cats ()](#apidoc.element.faker.image.cats)
1.  [function <span class="apidocSignatureSpan">faker.image.</span>city ()](#apidoc.element.faker.image.city)
1.  [function <span class="apidocSignatureSpan">faker.image.</span>dataUri ()](#apidoc.element.faker.image.dataUri)
1.  [function <span class="apidocSignatureSpan">faker.image.</span>fashion ()](#apidoc.element.faker.image.fashion)
1.  [function <span class="apidocSignatureSpan">faker.image.</span>food ()](#apidoc.element.faker.image.food)
1.  [function <span class="apidocSignatureSpan">faker.image.</span>imageUrl ()](#apidoc.element.faker.image.imageUrl)
1.  [function <span class="apidocSignatureSpan">faker.image.</span>nature ()](#apidoc.element.faker.image.nature)
1.  [function <span class="apidocSignatureSpan">faker.image.</span>nightlife ()](#apidoc.element.faker.image.nightlife)
1.  [function <span class="apidocSignatureSpan">faker.image.</span>people ()](#apidoc.element.faker.image.people)
1.  [function <span class="apidocSignatureSpan">faker.image.</span>sports ()](#apidoc.element.faker.image.sports)
1.  [function <span class="apidocSignatureSpan">faker.image.</span>technics ()](#apidoc.element.faker.image.technics)
1.  [function <span class="apidocSignatureSpan">faker.image.</span>transport ()](#apidoc.element.faker.image.transport)

#### [module faker.index](#apidoc.module.faker.index)
1.  [function <span class="apidocSignatureSpan">faker.</span>index (opts)](#apidoc.element.faker.index.index)

#### [module faker.index.prototype](#apidoc.module.faker.index.prototype)
1.  [function <span class="apidocSignatureSpan">faker.index.prototype.</span>seed (value)](#apidoc.element.faker.index.prototype.seed)

#### [module faker.internet](#apidoc.module.faker.internet)
1.  [function <span class="apidocSignatureSpan">faker.internet.</span>avatar ()](#apidoc.element.faker.internet.avatar)
1.  [function <span class="apidocSignatureSpan">faker.internet.</span>color ()](#apidoc.element.faker.internet.color)
1.  [function <span class="apidocSignatureSpan">faker.internet.</span>domainName ()](#apidoc.element.faker.internet.domainName)
1.  [function <span class="apidocSignatureSpan">faker.internet.</span>domainSuffix ()](#apidoc.element.faker.internet.domainSuffix)
1.  [function <span class="apidocSignatureSpan">faker.internet.</span>domainWord ()](#apidoc.element.faker.internet.domainWord)
1.  [function <span class="apidocSignatureSpan">faker.internet.</span>email ()](#apidoc.element.faker.internet.email)
1.  [function <span class="apidocSignatureSpan">faker.internet.</span>exampleEmail ()](#apidoc.element.faker.internet.exampleEmail)
1.  [function <span class="apidocSignatureSpan">faker.internet.</span>ip ()](#apidoc.element.faker.internet.ip)
1.  [function <span class="apidocSignatureSpan">faker.internet.</span>ipv6 ()](#apidoc.element.faker.internet.ipv6)
1.  [function <span class="apidocSignatureSpan">faker.internet.</span>mac ()](#apidoc.element.faker.internet.mac)
1.  [function <span class="apidocSignatureSpan">faker.internet.</span>password ()](#apidoc.element.faker.internet.password)
1.  [function <span class="apidocSignatureSpan">faker.internet.</span>protocol ()](#apidoc.element.faker.internet.protocol)
1.  [function <span class="apidocSignatureSpan">faker.internet.</span>url ()](#apidoc.element.faker.internet.url)
1.  [function <span class="apidocSignatureSpan">faker.internet.</span>userAgent ()](#apidoc.element.faker.internet.userAgent)
1.  [function <span class="apidocSignatureSpan">faker.internet.</span>userName ()](#apidoc.element.faker.internet.userName)

#### [module faker.lorem](#apidoc.module.faker.lorem)
1.  [function <span class="apidocSignatureSpan">faker.lorem.</span>lines ()](#apidoc.element.faker.lorem.lines)
1.  [function <span class="apidocSignatureSpan">faker.lorem.</span>paragraph ()](#apidoc.element.faker.lorem.paragraph)
1.  [function <span class="apidocSignatureSpan">faker.lorem.</span>paragraphs ()](#apidoc.element.faker.lorem.paragraphs)
1.  [function <span class="apidocSignatureSpan">faker.lorem.</span>sentence ()](#apidoc.element.faker.lorem.sentence)
1.  [function <span class="apidocSignatureSpan">faker.lorem.</span>sentences ()](#apidoc.element.faker.lorem.sentences)
1.  [function <span class="apidocSignatureSpan">faker.lorem.</span>slug ()](#apidoc.element.faker.lorem.slug)
1.  [function <span class="apidocSignatureSpan">faker.lorem.</span>text ()](#apidoc.element.faker.lorem.text)
1.  [function <span class="apidocSignatureSpan">faker.lorem.</span>word ()](#apidoc.element.faker.lorem.word)
1.  [function <span class="apidocSignatureSpan">faker.lorem.</span>words ()](#apidoc.element.faker.lorem.words)

#### [module faker.name](#apidoc.module.faker.name)
1.  [function <span class="apidocSignatureSpan">faker.name.</span>findName ()](#apidoc.element.faker.name.findName)
1.  [function <span class="apidocSignatureSpan">faker.name.</span>firstName ()](#apidoc.element.faker.name.firstName)
1.  [function <span class="apidocSignatureSpan">faker.name.</span>jobArea ()](#apidoc.element.faker.name.jobArea)
1.  [function <span class="apidocSignatureSpan">faker.name.</span>jobDescriptor ()](#apidoc.element.faker.name.jobDescriptor)
1.  [function <span class="apidocSignatureSpan">faker.name.</span>jobTitle ()](#apidoc.element.faker.name.jobTitle)
1.  [function <span class="apidocSignatureSpan">faker.name.</span>jobType ()](#apidoc.element.faker.name.jobType)
1.  [function <span class="apidocSignatureSpan">faker.name.</span>lastName ()](#apidoc.element.faker.name.lastName)
1.  [function <span class="apidocSignatureSpan">faker.name.</span>prefix ()](#apidoc.element.faker.name.prefix)
1.  [function <span class="apidocSignatureSpan">faker.name.</span>suffix ()](#apidoc.element.faker.name.suffix)
1.  [function <span class="apidocSignatureSpan">faker.name.</span>title ()](#apidoc.element.faker.name.title)

#### [module faker.phone](#apidoc.module.faker.phone)
1.  [function <span class="apidocSignatureSpan">faker.phone.</span>phoneFormats ()](#apidoc.element.faker.phone.phoneFormats)
1.  [function <span class="apidocSignatureSpan">faker.phone.</span>phoneNumber ()](#apidoc.element.faker.phone.phoneNumber)
1.  [function <span class="apidocSignatureSpan">faker.phone.</span>phoneNumberFormat ()](#apidoc.element.faker.phone.phoneNumberFormat)

#### [module faker.random](#apidoc.module.faker.random)
1.  [function <span class="apidocSignatureSpan">faker.random.</span>alphaNumeric ()](#apidoc.element.faker.random.alphaNumeric)
1.  [function <span class="apidocSignatureSpan">faker.random.</span>arrayElement ()](#apidoc.element.faker.random.arrayElement)
1.  [function <span class="apidocSignatureSpan">faker.random.</span>boolean ()](#apidoc.element.faker.random.boolean)
1.  [function <span class="apidocSignatureSpan">faker.random.</span>image ()](#apidoc.element.faker.random.image)
1.  [function <span class="apidocSignatureSpan">faker.random.</span>locale ()](#apidoc.element.faker.random.locale)
1.  [function <span class="apidocSignatureSpan">faker.random.</span>number ()](#apidoc.element.faker.random.number)
1.  [function <span class="apidocSignatureSpan">faker.random.</span>objectElement ()](#apidoc.element.faker.random.objectElement)
1.  [function <span class="apidocSignatureSpan">faker.random.</span>uuid ()](#apidoc.element.faker.random.uuid)
1.  [function <span class="apidocSignatureSpan">faker.random.</span>word ()](#apidoc.element.faker.random.word)
1.  [function <span class="apidocSignatureSpan">faker.random.</span>words ()](#apidoc.element.faker.random.words)

#### [module faker.system](#apidoc.module.faker.system)
1.  [function <span class="apidocSignatureSpan">faker.system.</span>commonFileExt ()](#apidoc.element.faker.system.commonFileExt)
1.  [function <span class="apidocSignatureSpan">faker.system.</span>commonFileName ()](#apidoc.element.faker.system.commonFileName)
1.  [function <span class="apidocSignatureSpan">faker.system.</span>commonFileType ()](#apidoc.element.faker.system.commonFileType)
1.  [function <span class="apidocSignatureSpan">faker.system.</span>directoryPath ()](#apidoc.element.faker.system.directoryPath)
1.  [function <span class="apidocSignatureSpan">faker.system.</span>fileExt ()](#apidoc.element.faker.system.fileExt)
1.  [function <span class="apidocSignatureSpan">faker.system.</span>fileName ()](#apidoc.element.faker.system.fileName)
1.  [function <span class="apidocSignatureSpan">faker.system.</span>filePath ()](#apidoc.element.faker.system.filePath)
1.  [function <span class="apidocSignatureSpan">faker.system.</span>fileType ()](#apidoc.element.faker.system.fileType)
1.  [function <span class="apidocSignatureSpan">faker.system.</span>mimeType ()](#apidoc.element.faker.system.mimeType)
1.  [function <span class="apidocSignatureSpan">faker.system.</span>semver ()](#apidoc.element.faker.system.semver)



# <a name="apidoc.module.faker"></a>[module faker](#apidoc.module.faker)

#### <a name="apidoc.element.faker.fake"></a>[function <span class="apidocSignatureSpan">faker.</span>fake (str)](#apidoc.element.faker.fake)
- description and source-code
```javascript
function fake(str) {
  // setup default response as empty string
  var res = '';

  // if incoming str parameter is not provided, return error message
  if (typeof str !== 'string' || str.length === 0) {
    res = 'string parameter is required!';
    return res;
  }

  // find first matching {{ and }}
  var start = str.search('{{');
  var end = str.search('}}');

  // if no {{ and }} is found, we are done
  if (start === -1 && end === -1) {
    return str;
  }

  // console.log('attempting to parse', str);

  // extract method name from between the {{ }} that we found
  // for example: {{name.firstName}}
  var token = str.substr(start + 2,  end - start - 2);
  var method = token.replace('}}', '').replace('{{', '');

  // console.log('method', method)

  // extract method parameters
  var regExp = /\(([^)]+)\)/;
  var matches = regExp.exec(method);
  var parameters = '';
  if (matches) {
    method = method.replace(regExp, '');
    parameters = matches[1];
  }

  // split the method into module and function
  var parts = method.split('.');

  if (typeof faker[parts[0]] === "undefined") {
    throw new Error('Invalid module: ' + parts[0]);
  }

  if (typeof faker[parts[0]][parts[1]] === "undefined") {
    throw new Error('Invalid method: ' + parts[0] + "." + parts[1]);
  }

  // assign the function from the module.function namespace
  var fn = faker[parts[0]][parts[1]];

  // If parameters are populated here, they are always going to be of string type
  // since we might actually be dealing with an object or array,
  // we always attempt to the parse the incoming parameters into JSON
  var params;
  // Note: we experience a small performance hit here due to JSON.parse try / catch
  // If anyone actually needs to optimize this specific code path, please open a support issue on github
  try {
    params = JSON.parse(parameters)
  } catch (err) {
    // since JSON.parse threw an error, assume parameters was actually a string
    params = parameters;
  }

  var result;
  if (typeof params === "string" && params.length === 0) {
    result = fn.call(this);
  } else {
    result = fn.call(this, params);
  }

  // replace the found tag with the returned fake value
  res = str.replace('{{' + token + '}}', result);

  // return the response recursively until we are done finding all tags
  return fake(res);
}
```
- example usage
```shell
...
    var randomName = faker.name.findName(); // Rowan Nikolaus
    var randomEmail = faker.internet.email(); // Kassandra.Haley@erich.biz
    var randomCard = faker.helpers.createCard(); // random contact card containing many properties

## API


### Faker.fake()

faker.js contains a super useful generator method 'Faker.fake' for combining faker API methods using a mustache string format.

**Example:**

''' js
console.log(faker.fake("{{name.lastName}}, {{name.firstName}} {{name.suffix}}"));
...
```

#### <a name="apidoc.element.faker.index"></a>[function <span class="apidocSignatureSpan">faker.</span>index (opts)](#apidoc.element.faker.index)
- description and source-code
```javascript
function Faker(opts) {

  var self = this;

  opts = opts || {};

  // assign options
  var locales = self.locales || opts.locales || {};
  var locale = self.locale || opts.locale || "en";
  var localeFallback = self.localeFallback || opts.localeFallback || "en";

  self.locales = locales;
  self.locale = locale;
  self.localeFallback = localeFallback;

  self.definitions = {};

  function bindAll(obj) {
      Object.keys(obj).forEach(function(meth) {
          if (typeof obj[meth] === 'function') {
              obj[meth] = obj[meth].bind(obj);
          }
      });
      return obj;
  }

  var Fake = require('./fake');
  self.fake = new Fake(self).fake;

  var Random = require('./random');
  self.random = bindAll(new Random(self));

  var Helpers = require('./helpers');
  self.helpers = new Helpers(self);

  var Name = require('./name');
  self.name = bindAll(new Name(self));

  var Address = require('./address');
  self.address = bindAll(new Address(self));

  var Company = require('./company');
  self.company = bindAll(new Company(self));

  var Finance = require('./finance');
  self.finance = bindAll(new Finance(self));

  var Image = require('./image');
  self.image = bindAll(new Image(self));

  var Lorem = require('./lorem');
  self.lorem = bindAll(new Lorem(self));

  var Hacker = require('./hacker');
  self.hacker = bindAll(new Hacker(self));

  var Internet = require('./internet');
  self.internet = bindAll(new Internet(self));

  var Database = require('./database');
  self.database = bindAll(new Database(self));

  var Phone = require('./phone_number');
  self.phone = bindAll(new Phone(self));

  var _Date = require('./date');
  self.date = bindAll(new _Date(self));

  var Commerce = require('./commerce');
  self.commerce = bindAll(new Commerce(self));

  var System = require('./system');
  self.system = bindAll(new System(self));

  var _definitions = {
    "name": ["first_name", "last_name", "prefix", "suffix", "title", "male_first_name", "female_first_name", "male_middle_name", "
female_middle_name", "male_last_name", "female_last_name"],
    "address": ["city_prefix", "city_suffix", "street_suffix", "county", "country", "country_code", "state", "state_abbr", "street_prefix
", "postcode"],
    "company": ["adjective", "noun", "descriptor", "bs_adjective", "bs_noun", "bs_verb", "suffix"],
    "lorem": ["words"],
    "hacker": ["abbreviation", "adjective", "noun", "verb", "ingverb"],
    "phone_number": ["formats"],
    "finance": ["account_type", "transaction_type", "currency", "iban"],
    "internet": ["avatar_uri", "domain_suffix", "free_email", "example_email", "password"],
    "commerce": ["color", "department", "product_name", "price", "categories"],
    "database": ["collation", "column", "engine", "type"],
    "system": ["mimeTypes"],
    "date": ["month", "weekday"],
    "title": "",
    "separator": ""
  };

  // Create a Getter for all definitions.foo.bar properties
  Object.keys(_definitions).forEach(function(d){
    if (typeof self.definitions[d] === "undefined") {
      self.definitions[d] = {};
    }

    if (typeof _definitions[d] === "string") {
        self.definitions[d] = _definitions[d];
      return;
    }

    _definitions[d].forEach(function(p){
      Object.defineProperty(self.definitions[d], p, {
        get: function () {
          if (typeof self.locales[self.locale][d] === "undefined" || typeof self.locales[self.locale][d][p] === "undefined") {
            // certain localization sets contain less data then others.
            // in the case of a missing definition, use the default localeFallback to substitute the missing set data
            // throw new Error('unknown property ' + d + p)
            return self.locales[localeFallback][d][p];
          } else {
            // return localized data
            return self.locales[self.locale][d][p];
          }
        }
      });
    });
  });

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.faker.address"></a>[module faker.address](#apidoc.module.faker.address)

#### <a name="apidoc.element.faker.address.city"></a>[function <span class="apidocSignatureSpan">faker.address.</span>city ()](#apidoc.element.faker.address.city)
- description and source-code
```javascript
city = function () { [native code] }
```
- example usage
```shell
...
"username": faker.internet.userName(),
"email": faker.internet.email(),
"address": {
    "streetA": faker.address.streetName(),
    "streetB": faker.address.streetAddress(),
    "streetC": faker.address.streetAddress(true),
    "streetD": faker.address.secondaryAddress(),
    "city": faker.address.city(),
    "state": faker.address.state(),
    "country": faker.address.country(),
    "zipcode": faker.address.zipCode(),
    "geo": {
        "lat": faker.address.latitude(),
        "lng": faker.address.longitude()
    }
...
```

#### <a name="apidoc.element.faker.address.cityPrefix"></a>[function <span class="apidocSignatureSpan">faker.address.</span>cityPrefix ()](#apidoc.element.faker.address.cityPrefix)
- description and source-code
```javascript
cityPrefix = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.address.citySuffix"></a>[function <span class="apidocSignatureSpan">faker.address.</span>citySuffix ()](#apidoc.element.faker.address.citySuffix)
- description and source-code
```javascript
citySuffix = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.address.country"></a>[function <span class="apidocSignatureSpan">faker.address.</span>country ()](#apidoc.element.faker.address.country)
- description and source-code
```javascript
country = function () { [native code] }
```
- example usage
```shell
...
"address": {
    "streetA": faker.address.streetName(),
    "streetB": faker.address.streetAddress(),
    "streetC": faker.address.streetAddress(true),
    "streetD": faker.address.secondaryAddress(),
    "city": faker.address.city(),
    "state": faker.address.state(),
    "country": faker.address.country(),
    "zipcode": faker.address.zipCode(),
    "geo": {
        "lat": faker.address.latitude(),
        "lng": faker.address.longitude()
    }
},
"phone": faker.phone.phoneNumber(),
...
```

#### <a name="apidoc.element.faker.address.countryCode"></a>[function <span class="apidocSignatureSpan">faker.address.</span>countryCode ()](#apidoc.element.faker.address.countryCode)
- description and source-code
```javascript
countryCode = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.address.county"></a>[function <span class="apidocSignatureSpan">faker.address.</span>county ()](#apidoc.element.faker.address.county)
- description and source-code
```javascript
county = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.address.latitude"></a>[function <span class="apidocSignatureSpan">faker.address.</span>latitude ()](#apidoc.element.faker.address.latitude)
- description and source-code
```javascript
latitude = function () { [native code] }
```
- example usage
```shell
...
    "streetC": faker.address.streetAddress(true),
    "streetD": faker.address.secondaryAddress(),
    "city": faker.address.city(),
    "state": faker.address.state(),
    "country": faker.address.country(),
    "zipcode": faker.address.zipCode(),
    "geo": {
        "lat": faker.address.latitude(),
        "lng": faker.address.longitude()
    }
},
"phone": faker.phone.phoneNumber(),
"website": faker.internet.domainName(),
"company": {
    "name": faker.company.companyName(),
...
```

#### <a name="apidoc.element.faker.address.longitude"></a>[function <span class="apidocSignatureSpan">faker.address.</span>longitude ()](#apidoc.element.faker.address.longitude)
- description and source-code
```javascript
longitude = function () { [native code] }
```
- example usage
```shell
...
    "streetD": faker.address.secondaryAddress(),
    "city": faker.address.city(),
    "state": faker.address.state(),
    "country": faker.address.country(),
    "zipcode": faker.address.zipCode(),
    "geo": {
        "lat": faker.address.latitude(),
        "lng": faker.address.longitude()
    }
},
"phone": faker.phone.phoneNumber(),
"website": faker.internet.domainName(),
"company": {
    "name": faker.company.companyName(),
    "catchPhrase": faker.company.catchPhrase(),
...
```

#### <a name="apidoc.element.faker.address.secondaryAddress"></a>[function <span class="apidocSignatureSpan">faker.address.</span>secondaryAddress ()](#apidoc.element.faker.address.secondaryAddress)
- description and source-code
```javascript
secondaryAddress = function () { [native code] }
```
- example usage
```shell
...
    case 1:
        address = Helpers.replaceSymbolWithNumber("####") +  " " + faker.address.streetName();
        break;
    case 2:
        address = Helpers.replaceSymbolWithNumber("###") + " " + faker.address.streetName();
        break;
    }
    return useFullAddress ? (address + " " + faker.address.secondaryAddress()) : address;
}

/**
 * streetSuffix
 *
 * @method faker.address.streetSuffix
 */
...
```

#### <a name="apidoc.element.faker.address.state"></a>[function <span class="apidocSignatureSpan">faker.address.</span>state ()](#apidoc.element.faker.address.state)
- description and source-code
```javascript
state = function () { [native code] }
```
- example usage
```shell
...
"email": faker.internet.email(),
"address": {
    "streetA": faker.address.streetName(),
    "streetB": faker.address.streetAddress(),
    "streetC": faker.address.streetAddress(true),
    "streetD": faker.address.secondaryAddress(),
    "city": faker.address.city(),
    "state": faker.address.state(),
    "country": faker.address.country(),
    "zipcode": faker.address.zipCode(),
    "geo": {
        "lat": faker.address.latitude(),
        "lng": faker.address.longitude()
    }
},
...
```

#### <a name="apidoc.element.faker.address.stateAbbr"></a>[function <span class="apidocSignatureSpan">faker.address.</span>stateAbbr ()](#apidoc.element.faker.address.stateAbbr)
- description and source-code
```javascript
stateAbbr = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.address.streetAddress"></a>[function <span class="apidocSignatureSpan">faker.address.</span>streetAddress ()](#apidoc.element.faker.address.streetAddress)
- description and source-code
```javascript
streetAddress = function () { [native code] }
```
- example usage
```shell
...
  self.createCard = function () {
return {
    "name": faker.name.findName(),
    "username": faker.internet.userName(),
    "email": faker.internet.email(),
    "address": {
        "streetA": faker.address.streetName(),
        "streetB": faker.address.streetAddress(),
        "streetC": faker.address.streetAddress(true),
        "streetD": faker.address.secondaryAddress(),
        "city": faker.address.city(),
        "state": faker.address.state(),
        "country": faker.address.country(),
        "zipcode": faker.address.zipCode(),
        "geo": {
...
```

#### <a name="apidoc.element.faker.address.streetName"></a>[function <span class="apidocSignatureSpan">faker.address.</span>streetName ()](#apidoc.element.faker.address.streetName)
- description and source-code
```javascript
streetName = function () { [native code] }
```
- example usage
```shell
...
 * @param {Boolean} useFullAddress
 */
this.streetAddress = function (useFullAddress) {
    if (useFullAddress === undefined) { useFullAddress = false; }
    var address = "";
    switch (faker.random.number(2)) {
    case 0:
        address = Helpers.replaceSymbolWithNumber("#####") + " " + faker.address.streetName();
        break;
    case 1:
        address = Helpers.replaceSymbolWithNumber("####") +  " " + faker.address.streetName();
        break;
    case 2:
        address = Helpers.replaceSymbolWithNumber("###") + " " + faker.address.streetName();
        break;
...
```

#### <a name="apidoc.element.faker.address.streetPrefix"></a>[function <span class="apidocSignatureSpan">faker.address.</span>streetPrefix ()](#apidoc.element.faker.address.streetPrefix)
- description and source-code
```javascript
streetPrefix = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.address.streetSuffix"></a>[function <span class="apidocSignatureSpan">faker.address.</span>streetSuffix ()](#apidoc.element.faker.address.streetSuffix)
- description and source-code
```javascript
streetSuffix = function () { [native code] }
```
- example usage
```shell
...
  /**
   * Returns a random localized street name
   *
   * @method faker.address.streetName
   */
  this.streetName = function () {
var result;
var suffix = faker.address.streetSuffix();
if (suffix !== "") {
    suffix = " " + suffix
}

switch (faker.random.number(1)) {
case 0:
    result = faker.name.lastName() + suffix;
...
```

#### <a name="apidoc.element.faker.address.zipCode"></a>[function <span class="apidocSignatureSpan">faker.address.</span>zipCode ()](#apidoc.element.faker.address.zipCode)
- description and source-code
```javascript
zipCode = function () { [native code] }
```
- example usage
```shell
...
    "streetA": faker.address.streetName(),
    "streetB": faker.address.streetAddress(),
    "streetC": faker.address.streetAddress(true),
    "streetD": faker.address.secondaryAddress(),
    "city": faker.address.city(),
    "state": faker.address.state(),
    "country": faker.address.country(),
    "zipcode": faker.address.zipCode(),
    "geo": {
        "lat": faker.address.latitude(),
        "lng": faker.address.longitude()
    }
},
"phone": faker.phone.phoneNumber(),
"website": faker.internet.domainName(),
...
```



# <a name="apidoc.module.faker.commerce"></a>[module faker.commerce](#apidoc.module.faker.commerce)

#### <a name="apidoc.element.faker.commerce.color"></a>[function <span class="apidocSignatureSpan">faker.commerce.</span>color ()](#apidoc.element.faker.commerce.color)
- description and source-code
```javascript
color = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.commerce.department"></a>[function <span class="apidocSignatureSpan">faker.commerce.</span>department ()](#apidoc.element.faker.commerce.department)
- description and source-code
```javascript
department = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.commerce.price"></a>[function <span class="apidocSignatureSpan">faker.commerce.</span>price ()](#apidoc.element.faker.commerce.price)
- description and source-code
```javascript
price = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.commerce.product"></a>[function <span class="apidocSignatureSpan">faker.commerce.</span>product ()](#apidoc.element.faker.commerce.product)
- description and source-code
```javascript
product = function () { [native code] }
```
- example usage
```shell
...
 * productName
 *
 * @method faker.commerce.productName
 */
self.productName = function() {
    return faker.commerce.productAdjective() + " " +
            faker.commerce.productMaterial() + " " +
            faker.commerce.product();
};

/**
 * price
 *
 * @method faker.commerce.price
 * @param {number} min
...
```

#### <a name="apidoc.element.faker.commerce.productAdjective"></a>[function <span class="apidocSignatureSpan">faker.commerce.</span>productAdjective ()](#apidoc.element.faker.commerce.productAdjective)
- description and source-code
```javascript
productAdjective = function () { [native code] }
```
- example usage
```shell
...

/**
 * productName
 *
 * @method faker.commerce.productName
 */
self.productName = function() {
    return faker.commerce.productAdjective() + " " +
            faker.commerce.productMaterial() + " " +
            faker.commerce.product();
};

/**
 * price
 *
...
```

#### <a name="apidoc.element.faker.commerce.productMaterial"></a>[function <span class="apidocSignatureSpan">faker.commerce.</span>productMaterial ()](#apidoc.element.faker.commerce.productMaterial)
- description and source-code
```javascript
productMaterial = function () { [native code] }
```
- example usage
```shell
...
/**
 * productName
 *
 * @method faker.commerce.productName
 */
self.productName = function() {
    return faker.commerce.productAdjective() + " " +
            faker.commerce.productMaterial() + " " +
            faker.commerce.product();
};

/**
 * price
 *
 * @method faker.commerce.price
...
```

#### <a name="apidoc.element.faker.commerce.productName"></a>[function <span class="apidocSignatureSpan">faker.commerce.</span>productName ()](#apidoc.element.faker.commerce.productName)
- description and source-code
```javascript
productName = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.faker.company"></a>[module faker.company](#apidoc.module.faker.company)

#### <a name="apidoc.element.faker.company.bs"></a>[function <span class="apidocSignatureSpan">faker.company.</span>bs ()](#apidoc.element.faker.company.bs)
- description and source-code
```javascript
bs = function () { [native code] }
```
- example usage
```shell
...
    }
},
"phone": faker.phone.phoneNumber(),
"website": faker.internet.domainName(),
"company": {
    "name": faker.company.companyName(),
    "catchPhrase": faker.company.catchPhrase(),
    "bs": faker.company.bs()
},
"posts": [
    {
        "words": faker.lorem.words(),
        "sentence": faker.lorem.sentence(),
        "sentences": faker.lorem.sentences(),
        "paragraph": faker.lorem.paragraph()
...
```

#### <a name="apidoc.element.faker.company.bsAdjective"></a>[function <span class="apidocSignatureSpan">faker.company.</span>bsAdjective ()](#apidoc.element.faker.company.bsAdjective)
- description and source-code
```javascript
bsAdjective = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.company.bsBuzz"></a>[function <span class="apidocSignatureSpan">faker.company.</span>bsBuzz ()](#apidoc.element.faker.company.bsBuzz)
- description and source-code
```javascript
bsBuzz = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.company.bsNoun"></a>[function <span class="apidocSignatureSpan">faker.company.</span>bsNoun ()](#apidoc.element.faker.company.bsNoun)
- description and source-code
```javascript
bsNoun = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.company.catchPhrase"></a>[function <span class="apidocSignatureSpan">faker.company.</span>catchPhrase ()](#apidoc.element.faker.company.catchPhrase)
- description and source-code
```javascript
catchPhrase = function () { [native code] }
```
- example usage
```shell
...
        "lng": faker.address.longitude()
    }
},
"phone": faker.phone.phoneNumber(),
"website": faker.internet.domainName(),
"company": {
    "name": faker.company.companyName(),
    "catchPhrase": faker.company.catchPhrase(),
    "bs": faker.company.bs()
},
"posts": [
    {
        "words": faker.lorem.words(),
        "sentence": faker.lorem.sentence(),
        "sentences": faker.lorem.sentences(),
...
```

#### <a name="apidoc.element.faker.company.catchPhraseAdjective"></a>[function <span class="apidocSignatureSpan">faker.company.</span>catchPhraseAdjective ()](#apidoc.element.faker.company.catchPhraseAdjective)
- description and source-code
```javascript
catchPhraseAdjective = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.company.catchPhraseDescriptor"></a>[function <span class="apidocSignatureSpan">faker.company.</span>catchPhraseDescriptor ()](#apidoc.element.faker.company.catchPhraseDescriptor)
- description and source-code
```javascript
catchPhraseDescriptor = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.company.catchPhraseNoun"></a>[function <span class="apidocSignatureSpan">faker.company.</span>catchPhraseNoun ()](#apidoc.element.faker.company.catchPhraseNoun)
- description and source-code
```javascript
catchPhraseNoun = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.company.companyName"></a>[function <span class="apidocSignatureSpan">faker.company.</span>companyName ()](#apidoc.element.faker.company.companyName)
- description and source-code
```javascript
companyName = function () { [native code] }
```
- example usage
```shell
...
        "lat": faker.address.latitude(),
        "lng": faker.address.longitude()
    }
},
"phone": faker.phone.phoneNumber(),
"website": faker.internet.domainName(),
"company": {
    "name": faker.company.companyName(),
    "catchPhrase": faker.company.catchPhrase(),
    "bs": faker.company.bs()
},
"posts": [
    {
        "words": faker.lorem.words(),
        "sentence": faker.lorem.sentence(),
...
```

#### <a name="apidoc.element.faker.company.companySuffix"></a>[function <span class="apidocSignatureSpan">faker.company.</span>companySuffix ()](#apidoc.element.faker.company.companySuffix)
- description and source-code
```javascript
companySuffix = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.company.suffixes"></a>[function <span class="apidocSignatureSpan">faker.company.</span>suffixes ()](#apidoc.element.faker.company.suffixes)
- description and source-code
```javascript
suffixes = function () { [native code] }
```
- example usage
```shell
...

/**
 * companySuffix
 *
 * @method faker.company.companySuffix
 */
this.companySuffix = function () {
    return faker.random.arrayElement(faker.company.suffixes());
}

/**
 * catchPhrase
 *
 * @method faker.company.catchPhrase
 */
...
```



# <a name="apidoc.module.faker.database"></a>[module faker.database](#apidoc.module.faker.database)

#### <a name="apidoc.element.faker.database.collation"></a>[function <span class="apidocSignatureSpan">faker.database.</span>collation ()](#apidoc.element.faker.database.collation)
- description and source-code
```javascript
collation = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.database.column"></a>[function <span class="apidocSignatureSpan">faker.database.</span>column ()](#apidoc.element.faker.database.column)
- description and source-code
```javascript
column = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.database.engine"></a>[function <span class="apidocSignatureSpan">faker.database.</span>engine ()](#apidoc.element.faker.database.engine)
- description and source-code
```javascript
engine = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.database.type"></a>[function <span class="apidocSignatureSpan">faker.database.</span>type ()](#apidoc.element.faker.database.type)
- description and source-code
```javascript
type = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.faker.date"></a>[module faker.date](#apidoc.module.faker.date)

#### <a name="apidoc.element.faker.date.between"></a>[function <span class="apidocSignatureSpan">faker.date.</span>between ()](#apidoc.element.faker.date.between)
- description and source-code
```javascript
between = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.date.future"></a>[function <span class="apidocSignatureSpan">faker.date.</span>future ()](#apidoc.element.faker.date.future)
- description and source-code
```javascript
future = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.date.month"></a>[function <span class="apidocSignatureSpan">faker.date.</span>month ()](#apidoc.element.faker.date.month)
- description and source-code
```javascript
month = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.date.past"></a>[function <span class="apidocSignatureSpan">faker.date.</span>past ()](#apidoc.element.faker.date.past)
- description and source-code
```javascript
past = function () { [native code] }
```
- example usage
```shell
...
var name = faker.name.firstName(),
    userName = faker.internet.userName(name);
return {
    "name": name,
    "username": userName,
    "avatar": faker.internet.avatar(),
    "email": faker.internet.email(userName),
    "dob": faker.date.past(50, new Date("Sat Sep 20 1992 21:35:02 GMT+0200 (CEST)")),
    "phone": faker.phone.phoneNumber(),
    "address": {
        "street": faker.address.streetName(true),
        "suite": faker.address.secondaryAddress(),
        "city": faker.address.city(),
        "zipcode": faker.address.zipCode(),
        "geo": {
...
```

#### <a name="apidoc.element.faker.date.recent"></a>[function <span class="apidocSignatureSpan">faker.date.</span>recent ()](#apidoc.element.faker.date.recent)
- description and source-code
```javascript
recent = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.date.weekday"></a>[function <span class="apidocSignatureSpan">faker.date.</span>weekday ()](#apidoc.element.faker.date.weekday)
- description and source-code
```javascript
weekday = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.faker.finance"></a>[module faker.finance](#apidoc.module.faker.finance)

#### <a name="apidoc.element.faker.finance.account"></a>[function <span class="apidocSignatureSpan">faker.finance.</span>account ()](#apidoc.element.faker.finance.account)
- description and source-code
```javascript
account = function () { [native code] }
```
- example usage
```shell
...
  self.createTransaction = function(){
    return {
      "amount" : faker.finance.amount(),
      "date" : new Date(2012, 1, 2),  //TODO: add a ranged date method
      "business": faker.company.companyName(),
      "name": [faker.finance.accountName(), faker.finance.mask()].join(' '),
      "type" : self.randomize(faker.definitions.finance.transaction_type),
      "account" : faker.finance.account()
    };
  };

  return self;

};
...
```

#### <a name="apidoc.element.faker.finance.accountName"></a>[function <span class="apidocSignatureSpan">faker.finance.</span>accountName ()](#apidoc.element.faker.finance.accountName)
- description and source-code
```javascript
accountName = function () { [native code] }
```
- example usage
```shell
...
 * @method faker.helpers.createTransaction
 */
self.createTransaction = function(){
  return {
    "amount" : faker.finance.amount(),
    "date" : new Date(2012, 1, 2),  //TODO: add a ranged date method
    "business": faker.company.companyName(),
    "name": [faker.finance.accountName(), faker.finance.mask()].join(' '),
    "type" : self.randomize(faker.definitions.finance.transaction_type),
    "account" : faker.finance.account()
  };
};

return self;
...
```

#### <a name="apidoc.element.faker.finance.amount"></a>[function <span class="apidocSignatureSpan">faker.finance.</span>amount ()](#apidoc.element.faker.finance.amount)
- description and source-code
```javascript
amount = function () { [native code] }
```
- example usage
```shell
...
/**
 * createTransaction
 *
 * @method faker.helpers.createTransaction
 */
self.createTransaction = function(){
  return {
    "amount" : faker.finance.amount(),
    "date" : new Date(2012, 1, 2),  //TODO: add a ranged date method
    "business": faker.company.companyName(),
    "name": [faker.finance.accountName(), faker.finance.mask()].join(' '),
    "type" : self.randomize(faker.definitions.finance.transaction_type),
    "account" : faker.finance.account()
  };
};
...
```

#### <a name="apidoc.element.faker.finance.bic"></a>[function <span class="apidocSignatureSpan">faker.finance.</span>bic ()](#apidoc.element.faker.finance.bic)
- description and source-code
```javascript
bic = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.finance.bitcoinAddress"></a>[function <span class="apidocSignatureSpan">faker.finance.</span>bitcoinAddress ()](#apidoc.element.faker.finance.bitcoinAddress)
- description and source-code
```javascript
bitcoinAddress = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.finance.currencyCode"></a>[function <span class="apidocSignatureSpan">faker.finance.</span>currencyCode ()](#apidoc.element.faker.finance.currencyCode)
- description and source-code
```javascript
currencyCode = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.finance.currencyName"></a>[function <span class="apidocSignatureSpan">faker.finance.</span>currencyName ()](#apidoc.element.faker.finance.currencyName)
- description and source-code
```javascript
currencyName = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.finance.currencySymbol"></a>[function <span class="apidocSignatureSpan">faker.finance.</span>currencySymbol ()](#apidoc.element.faker.finance.currencySymbol)
- description and source-code
```javascript
currencySymbol = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.finance.iban"></a>[function <span class="apidocSignatureSpan">faker.finance.</span>iban ()](#apidoc.element.faker.finance.iban)
- description and source-code
```javascript
iban = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.finance.mask"></a>[function <span class="apidocSignatureSpan">faker.finance.</span>mask ()](#apidoc.element.faker.finance.mask)
- description and source-code
```javascript
mask = function () { [native code] }
```
- example usage
```shell
...
 * @method faker.helpers.createTransaction
 */
self.createTransaction = function(){
  return {
    "amount" : faker.finance.amount(),
    "date" : new Date(2012, 1, 2),  //TODO: add a ranged date method
    "business": faker.company.companyName(),
    "name": [faker.finance.accountName(), faker.finance.mask()].join(' '),
    "type" : self.randomize(faker.definitions.finance.transaction_type),
    "account" : faker.finance.account()
  };
};

return self;
...
```

#### <a name="apidoc.element.faker.finance.transactionType"></a>[function <span class="apidocSignatureSpan">faker.finance.</span>transactionType ()](#apidoc.element.faker.finance.transactionType)
- description and source-code
```javascript
transactionType = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.faker.hacker"></a>[module faker.hacker](#apidoc.module.faker.hacker)

#### <a name="apidoc.element.faker.hacker.abbreviation"></a>[function <span class="apidocSignatureSpan">faker.hacker.</span>abbreviation ()](#apidoc.element.faker.hacker.abbreviation)
- description and source-code
```javascript
abbreviation = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.hacker.adjective"></a>[function <span class="apidocSignatureSpan">faker.hacker.</span>adjective ()](#apidoc.element.faker.hacker.adjective)
- description and source-code
```javascript
adjective = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.hacker.ingverb"></a>[function <span class="apidocSignatureSpan">faker.hacker.</span>ingverb ()](#apidoc.element.faker.hacker.ingverb)
- description and source-code
```javascript
ingverb = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.hacker.noun"></a>[function <span class="apidocSignatureSpan">faker.hacker.</span>noun ()](#apidoc.element.faker.hacker.noun)
- description and source-code
```javascript
noun = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.hacker.phrase"></a>[function <span class="apidocSignatureSpan">faker.hacker.</span>phrase ()](#apidoc.element.faker.hacker.phrase)
- description and source-code
```javascript
phrase = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.hacker.verb"></a>[function <span class="apidocSignatureSpan">faker.hacker.</span>verb ()](#apidoc.element.faker.hacker.verb)
- description and source-code
```javascript
verb = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.faker.helpers"></a>[module faker.helpers](#apidoc.module.faker.helpers)

#### <a name="apidoc.element.faker.helpers.contextualCard"></a>[function <span class="apidocSignatureSpan">faker.helpers.</span>contextualCard ()](#apidoc.element.faker.helpers.contextualCard)
- description and source-code
```javascript
contextualCard = function () {
  var name = faker.name.firstName(),
      userName = faker.internet.userName(name);
  return {
      "name": name,
      "username": userName,
      "avatar": faker.internet.avatar(),
      "email": faker.internet.email(userName),
      "dob": faker.date.past(50, new Date("Sat Sep 20 1992 21:35:02 GMT+0200 (CEST)")),
      "phone": faker.phone.phoneNumber(),
      "address": {
          "street": faker.address.streetName(true),
          "suite": faker.address.secondaryAddress(),
          "city": faker.address.city(),
          "zipcode": faker.address.zipCode(),
          "geo": {
              "lat": faker.address.latitude(),
              "lng": faker.address.longitude()
          }
      },
      "website": faker.internet.domainName(),
      "company": {
          "name": faker.company.companyName(),
          "catchPhrase": faker.company.catchPhrase(),
          "bs": faker.company.bs()
      }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.helpers.createCard"></a>[function <span class="apidocSignatureSpan">faker.helpers.</span>createCard ()](#apidoc.element.faker.helpers.createCard)
- description and source-code
```javascript
createCard = function () {
    return {
        "name": faker.name.findName(),
        "username": faker.internet.userName(),
        "email": faker.internet.email(),
        "address": {
            "streetA": faker.address.streetName(),
            "streetB": faker.address.streetAddress(),
            "streetC": faker.address.streetAddress(true),
            "streetD": faker.address.secondaryAddress(),
            "city": faker.address.city(),
            "state": faker.address.state(),
            "country": faker.address.country(),
            "zipcode": faker.address.zipCode(),
            "geo": {
                "lat": faker.address.latitude(),
                "lng": faker.address.longitude()
            }
        },
        "phone": faker.phone.phoneNumber(),
        "website": faker.internet.domainName(),
        "company": {
            "name": faker.company.companyName(),
            "catchPhrase": faker.company.catchPhrase(),
            "bs": faker.company.bs()
        },
        "posts": [
            {
                "words": faker.lorem.words(),
                "sentence": faker.lorem.sentence(),
                "sentences": faker.lorem.sentences(),
                "paragraph": faker.lorem.paragraph()
            },
            {
                "words": faker.lorem.words(),
                "sentence": faker.lorem.sentence(),
                "sentences": faker.lorem.sentences(),
                "paragraph": faker.lorem.paragraph()
            },
            {
                "words": faker.lorem.words(),
                "sentence": faker.lorem.sentence(),
                "sentences": faker.lorem.sentences(),
                "paragraph": faker.lorem.paragraph()
            }
        ],
        "accountHistory": [faker.helpers.createTransaction(), faker.helpers.createTransaction(), faker.helpers.createTransaction
()]
    };
}
```
- example usage
```shell
...

### Browser

<script src = "faker.js" type = "text/javascript"></script>
<script>
  var randomName = faker.name.findName(); // Caitlyn Kerluke
  var randomEmail = faker.internet.email(); // Rusty@arne.info
  var randomCard = faker.helpers.createCard(); // random contact card containing many properties
</script>

### Node.js

var faker = require('faker');

var randomName = faker.name.findName(); // Rowan Nikolaus
...
```

#### <a name="apidoc.element.faker.helpers.createTransaction"></a>[function <span class="apidocSignatureSpan">faker.helpers.</span>createTransaction ()](#apidoc.element.faker.helpers.createTransaction)
- description and source-code
```javascript
createTransaction = function (){
  return {
    "amount" : faker.finance.amount(),
    "date" : new Date(2012, 1, 2),  //TODO: add a ranged date method
    "business": faker.company.companyName(),
    "name": [faker.finance.accountName(), faker.finance.mask()].join(' '),
    "type" : self.randomize(faker.definitions.finance.transaction_type),
    "account" : faker.finance.account()
  };
}
```
- example usage
```shell
...
            {
                "words": faker.lorem.words(),
                "sentence": faker.lorem.sentence(),
                "sentences": faker.lorem.sentences(),
                "paragraph": faker.lorem.paragraph()
            }
        ],
        "accountHistory": [faker.helpers.createTransaction(), faker.helpers.createTransaction(), faker.helpers.createTransaction
()]
    };
};

/**
 * contextualCard
 *
 * @method faker.helpers.contextualCard
...
```

#### <a name="apidoc.element.faker.helpers.mustache"></a>[function <span class="apidocSignatureSpan">faker.helpers.</span>mustache (str, data)](#apidoc.element.faker.helpers.mustache)
- description and source-code
```javascript
mustache = function (str, data) {
  if (typeof str === 'undefined') {
    return '';
  }
  for(var p in data) {
    var re = new RegExp('{{' + p + '}}', 'g')
    str = str.replace(re, data[p]);
  }
  return str;
}
```
- example usage
```shell
...
      "You can't {{verb}} the {{noun}} without {{ingverb}} the {{adjective}} {{abbreviation}} {{noun}}!",
      "Use the {{adjective}} {{abbreviation}} {{noun}}, then you can {{verb}} the {{adjective}} {{noun}}!",
      "The {{abbreviation}} {{noun}} is down, {{verb}} the {{adjective}} {{noun}} so we can {{verb}} the {{abbreviation}} {{noun
}}!",
      "{{ingverb}} the {{noun}} won't do anything, we need to {{verb}} the {{adjective}} {{abbreviation}} {{noun}}!",
      "I'll {{verb}} the {{adjective}} {{abbreviation}} {{noun}}, that should {{noun}} the {{abbreviation}} {{noun}}!"
   ]);

   return faker.helpers.mustache(phrase, data);

  };

  return self;
};

module['exports'] = Hacker;
...
```

#### <a name="apidoc.element.faker.helpers.randomize"></a>[function <span class="apidocSignatureSpan">faker.helpers.</span>randomize (array)](#apidoc.element.faker.helpers.randomize)
- description and source-code
```javascript
randomize = function (array) {
    array = array || ["a", "b", "c"];
    return faker.random.arrayElement(array);
}
```
- example usage
```shell
...
/**
 * accountName
 *
 * @method faker.finance.accountName
 */
self.accountName = function () {

    return [Helpers.randomize(faker.definitions.finance.account_type), 'Account'].join(' ');
};

/**
 * mask
 *
 * @method faker.finance.mask
 * @param {number} length
...
```

#### <a name="apidoc.element.faker.helpers.replaceSymbolWithNumber"></a>[function <span class="apidocSignatureSpan">faker.helpers.</span>replaceSymbolWithNumber (string, symbol)](#apidoc.element.faker.helpers.replaceSymbolWithNumber)
- description and source-code
```javascript
replaceSymbolWithNumber = function (string, symbol) {
    string = string || "";
    // default symbol is '#'
    if (symbol === undefined) {
        symbol = '#';
    }

    var str = '';
    for (var i = 0; i < string.length; i++) {
        if (string.charAt(i) == symbol) {
            str += faker.random.number(9);
        } else {
            str += string.charAt(i);
        }
    }
    return str;
}
```
- example usage
```shell
...
 * @param {Boolean} useFullAddress
 */
this.streetAddress = function (useFullAddress) {
    if (useFullAddress === undefined) { useFullAddress = false; }
    var address = "";
    switch (faker.random.number(2)) {
    case 0:
        address = Helpers.replaceSymbolWithNumber("#####") + " " + faker.address.streetName();
        break;
    case 1:
        address = Helpers.replaceSymbolWithNumber("####") +  " " + faker.address.streetName();
        break;
    case 2:
        address = Helpers.replaceSymbolWithNumber("###") + " " + faker.address.streetName();
        break;
...
```

#### <a name="apidoc.element.faker.helpers.replaceSymbols"></a>[function <span class="apidocSignatureSpan">faker.helpers.</span>replaceSymbols (string)](#apidoc.element.faker.helpers.replaceSymbols)
- description and source-code
```javascript
replaceSymbols = function (string) {
    string = string || "";
    var alpha = ['A','B','C','D','E','F','G','H','I','J','K','L','M','N','O','P','Q','R','S','T','U','V','W','X','Y','Z']
    var str = '';

    for (var i = 0; i < string.length; i++) {
        if (string.charAt(i) == "#") {
            str += faker.random.number(9);
        } else if (string.charAt(i) == "?") {
            str += faker.random.arrayElement(alpha);
        } else {
            str += string.charAt(i);
        }
    }
    return str;
}
```
- example usage
```shell
...
    var localeFormat = faker.definitions.address.postcode;
    if (typeof localeFormat === 'string') {
      format = localeFormat;
    } else {
      format = faker.random.arrayElement(localeFormat);
    }
  }
  return Helpers.replaceSymbols(format);
}

/**
 * Generates a random localized city name. The format string can contain any
 * method provided by faker wrapped in '{{}}', e.g. '{{name.firstName}}' in
 * order to build the city name.
 *
...
```

#### <a name="apidoc.element.faker.helpers.shuffle"></a>[function <span class="apidocSignatureSpan">faker.helpers.</span>shuffle (o)](#apidoc.element.faker.helpers.shuffle)
- description and source-code
```javascript
shuffle = function (o) {
    if (typeof o === 'undefined' || o.length === 0) {
      return [];
    }
    o = o || ["a", "b", "c"];
    for (var j, x, i = o.length-1; i; j = faker.random.number(i), x = o[--i], o[i] = o[j], o[j] = x);
    return o;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.helpers.slugify"></a>[function <span class="apidocSignatureSpan">faker.helpers.</span>slugify (string)](#apidoc.element.faker.helpers.slugify)
- description and source-code
```javascript
slugify = function (string) {
    string = string || "";
    return string.replace(/ /g, '-').replace(/[^\w\.\-]+/g, '');
}
```
- example usage
```shell
...
 * @method faker.internet.email
 * @param {string} firstName
 * @param {string} lastName
 * @param {string} provider
 */
self.email = function (firstName, lastName, provider) {
    provider = provider || faker.random.arrayElement(faker.definitions.internet.free_email);
    return  faker.helpers.slugify(faker.internet.userName(firstName, lastName)) + "@" + provider;
};

self.email.schema = {
  "description": "Generates a valid email address based on optional input criteria",
  "sampleResults": ["foo.bar@gmail.com"],
  "properties": {
    "firstName": {
...
```

#### <a name="apidoc.element.faker.helpers.userCard"></a>[function <span class="apidocSignatureSpan">faker.helpers.</span>userCard ()](#apidoc.element.faker.helpers.userCard)
- description and source-code
```javascript
userCard = function () {
    return {
        "name": faker.name.findName(),
        "username": faker.internet.userName(),
        "email": faker.internet.email(),
        "address": {
            "street": faker.address.streetName(true),
            "suite": faker.address.secondaryAddress(),
            "city": faker.address.city(),
            "zipcode": faker.address.zipCode(),
            "geo": {
                "lat": faker.address.latitude(),
                "lng": faker.address.longitude()
            }
        },
        "phone": faker.phone.phoneNumber(),
        "website": faker.internet.domainName(),
        "company": {
            "name": faker.company.companyName(),
            "catchPhrase": faker.company.catchPhrase(),
            "bs": faker.company.bs()
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.faker.iban"></a>[module faker.iban](#apidoc.module.faker.iban)

#### <a name="apidoc.element.faker.iban.mod97"></a>[function <span class="apidocSignatureSpan">faker.iban.</span>mod97 (digitStr)](#apidoc.element.faker.iban.mod97)
- description and source-code
```javascript
mod97 = function (digitStr) {
    var m = 0;
    for (var i = 0; i < digitStr.length; i++) {
        m = ((m * 10) + (digitStr[i] |0)) % 97;
    }
    return m;
}
```
- example usage
```shell
...
                    s += faker.random.number(9);
                }
            }
            c--;
        }
        s = s.substring(0, count);
    }
    var checksum = 98 - ibanLib.mod97(ibanLib.toDigitString(s + ibanFormat.country + "00"));
    if (checksum < 10) {
        checksum = "0" + checksum;
    }
    var iban = ibanFormat.country + checksum + s;
    return formatted ? iban.match(/.{1,4}/g).join(" ") : iban;
};
...
```

#### <a name="apidoc.element.faker.iban.toDigitString"></a>[function <span class="apidocSignatureSpan">faker.iban.</span>toDigitString (str)](#apidoc.element.faker.iban.toDigitString)
- description and source-code
```javascript
toDigitString = function (str) {
    return str.replace(/[A-Z]/gi, function(match) {
        return match.toUpperCase().charCodeAt(0) - 55;
    });
}
```
- example usage
```shell
...
                    s += faker.random.number(9);
                }
            }
            c--;
        }
        s = s.substring(0, count);
    }
    var checksum = 98 - ibanLib.mod97(ibanLib.toDigitString(s + ibanFormat.country + "00"));
    if (checksum < 10) {
        checksum = "0" + checksum;
    }
    var iban = ibanFormat.country + checksum + s;
    return formatted ? iban.match(/.{1,4}/g).join(" ") : iban;
};
...
```



# <a name="apidoc.module.faker.image"></a>[module faker.image](#apidoc.module.faker.image)

#### <a name="apidoc.element.faker.image.image"></a>[function <span class="apidocSignatureSpan">faker.</span>image ()](#apidoc.element.faker.image.image)
- description and source-code
```javascript
image = function () { [native code] }
```
- example usage
```shell
...

/**
 * locale
 *
 * @method faker.random.image
 */
this.image = function randomImage () {
  return faker.image.image();
}

/**
 * locale
 *
 * @method faker.random.locale
 */
...
```

#### <a name="apidoc.element.faker.image.abstract"></a>[function <span class="apidocSignatureSpan">faker.image.</span>abstract ()](#apidoc.element.faker.image.abstract)
- description and source-code
```javascript
abstract = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.image.animals"></a>[function <span class="apidocSignatureSpan">faker.image.</span>animals ()](#apidoc.element.faker.image.animals)
- description and source-code
```javascript
animals = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.image.avatar"></a>[function <span class="apidocSignatureSpan">faker.image.</span>avatar ()](#apidoc.element.faker.image.avatar)
- description and source-code
```javascript
avatar = function () { [native code] }
```
- example usage
```shell
...
 */
self.contextualCard = function () {
  var name = faker.name.firstName(),
      userName = faker.internet.userName(name);
  return {
      "name": name,
      "username": userName,
      "avatar": faker.internet.avatar(),
      "email": faker.internet.email(userName),
      "dob": faker.date.past(50, new Date("Sat Sep 20 1992 21:35:02 GMT+0200 (CEST)")),
      "phone": faker.phone.phoneNumber(),
      "address": {
          "street": faker.address.streetName(true),
          "suite": faker.address.secondaryAddress(),
          "city": faker.address.city(),
...
```

#### <a name="apidoc.element.faker.image.business"></a>[function <span class="apidocSignatureSpan">faker.image.</span>business ()](#apidoc.element.faker.image.business)
- description and source-code
```javascript
business = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.image.cats"></a>[function <span class="apidocSignatureSpan">faker.image.</span>cats ()](#apidoc.element.faker.image.cats)
- description and source-code
```javascript
cats = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.image.city"></a>[function <span class="apidocSignatureSpan">faker.image.</span>city ()](#apidoc.element.faker.image.city)
- description and source-code
```javascript
city = function () { [native code] }
```
- example usage
```shell
...
"username": faker.internet.userName(),
"email": faker.internet.email(),
"address": {
    "streetA": faker.address.streetName(),
    "streetB": faker.address.streetAddress(),
    "streetC": faker.address.streetAddress(true),
    "streetD": faker.address.secondaryAddress(),
    "city": faker.address.city(),
    "state": faker.address.state(),
    "country": faker.address.country(),
    "zipcode": faker.address.zipCode(),
    "geo": {
        "lat": faker.address.latitude(),
        "lng": faker.address.longitude()
    }
...
```

#### <a name="apidoc.element.faker.image.dataUri"></a>[function <span class="apidocSignatureSpan">faker.image.</span>dataUri ()](#apidoc.element.faker.image.dataUri)
- description and source-code
```javascript
dataUri = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.image.fashion"></a>[function <span class="apidocSignatureSpan">faker.image.</span>fashion ()](#apidoc.element.faker.image.fashion)
- description and source-code
```javascript
fashion = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.image.food"></a>[function <span class="apidocSignatureSpan">faker.image.</span>food ()](#apidoc.element.faker.image.food)
- description and source-code
```javascript
food = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.image.imageUrl"></a>[function <span class="apidocSignatureSpan">faker.image.</span>imageUrl ()](#apidoc.element.faker.image.imageUrl)
- description and source-code
```javascript
imageUrl = function () { [native code] }
```
- example usage
```shell
...
 *
 * @param {number} width
 * @param {number} height
 * @param {boolean} randomize
 * @method faker.image.abstract
 */
self.abstract = function (width, height, randomize) {
  return faker.image.imageUrl(width, height, 'abstract', randomize);
};
/**
 * animals
 *
 * @param {number} width
 * @param {number} height
 * @param {boolean} randomize
...
```

#### <a name="apidoc.element.faker.image.nature"></a>[function <span class="apidocSignatureSpan">faker.image.</span>nature ()](#apidoc.element.faker.image.nature)
- description and source-code
```javascript
nature = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.image.nightlife"></a>[function <span class="apidocSignatureSpan">faker.image.</span>nightlife ()](#apidoc.element.faker.image.nightlife)
- description and source-code
```javascript
nightlife = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.image.people"></a>[function <span class="apidocSignatureSpan">faker.image.</span>people ()](#apidoc.element.faker.image.people)
- description and source-code
```javascript
people = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.image.sports"></a>[function <span class="apidocSignatureSpan">faker.image.</span>sports ()](#apidoc.element.faker.image.sports)
- description and source-code
```javascript
sports = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.image.technics"></a>[function <span class="apidocSignatureSpan">faker.image.</span>technics ()](#apidoc.element.faker.image.technics)
- description and source-code
```javascript
technics = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.image.transport"></a>[function <span class="apidocSignatureSpan">faker.image.</span>transport ()](#apidoc.element.faker.image.transport)
- description and source-code
```javascript
transport = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.faker.index"></a>[module faker.index](#apidoc.module.faker.index)

#### <a name="apidoc.element.faker.index.index"></a>[function <span class="apidocSignatureSpan">faker.</span>index (opts)](#apidoc.element.faker.index.index)
- description and source-code
```javascript
function Faker(opts) {

  var self = this;

  opts = opts || {};

  // assign options
  var locales = self.locales || opts.locales || {};
  var locale = self.locale || opts.locale || "en";
  var localeFallback = self.localeFallback || opts.localeFallback || "en";

  self.locales = locales;
  self.locale = locale;
  self.localeFallback = localeFallback;

  self.definitions = {};

  function bindAll(obj) {
      Object.keys(obj).forEach(function(meth) {
          if (typeof obj[meth] === 'function') {
              obj[meth] = obj[meth].bind(obj);
          }
      });
      return obj;
  }

  var Fake = require('./fake');
  self.fake = new Fake(self).fake;

  var Random = require('./random');
  self.random = bindAll(new Random(self));

  var Helpers = require('./helpers');
  self.helpers = new Helpers(self);

  var Name = require('./name');
  self.name = bindAll(new Name(self));

  var Address = require('./address');
  self.address = bindAll(new Address(self));

  var Company = require('./company');
  self.company = bindAll(new Company(self));

  var Finance = require('./finance');
  self.finance = bindAll(new Finance(self));

  var Image = require('./image');
  self.image = bindAll(new Image(self));

  var Lorem = require('./lorem');
  self.lorem = bindAll(new Lorem(self));

  var Hacker = require('./hacker');
  self.hacker = bindAll(new Hacker(self));

  var Internet = require('./internet');
  self.internet = bindAll(new Internet(self));

  var Database = require('./database');
  self.database = bindAll(new Database(self));

  var Phone = require('./phone_number');
  self.phone = bindAll(new Phone(self));

  var _Date = require('./date');
  self.date = bindAll(new _Date(self));

  var Commerce = require('./commerce');
  self.commerce = bindAll(new Commerce(self));

  var System = require('./system');
  self.system = bindAll(new System(self));

  var _definitions = {
    "name": ["first_name", "last_name", "prefix", "suffix", "title", "male_first_name", "female_first_name", "male_middle_name", "
female_middle_name", "male_last_name", "female_last_name"],
    "address": ["city_prefix", "city_suffix", "street_suffix", "county", "country", "country_code", "state", "state_abbr", "street_prefix
", "postcode"],
    "company": ["adjective", "noun", "descriptor", "bs_adjective", "bs_noun", "bs_verb", "suffix"],
    "lorem": ["words"],
    "hacker": ["abbreviation", "adjective", "noun", "verb", "ingverb"],
    "phone_number": ["formats"],
    "finance": ["account_type", "transaction_type", "currency", "iban"],
    "internet": ["avatar_uri", "domain_suffix", "free_email", "example_email", "password"],
    "commerce": ["color", "department", "product_name", "price", "categories"],
    "database": ["collation", "column", "engine", "type"],
    "system": ["mimeTypes"],
    "date": ["month", "weekday"],
    "title": "",
    "separator": ""
  };

  // Create a Getter for all definitions.foo.bar properties
  Object.keys(_definitions).forEach(function(d){
    if (typeof self.definitions[d] === "undefined") {
      self.definitions[d] = {};
    }

    if (typeof _definitions[d] === "string") {
        self.definitions[d] = _definitions[d];
      return;
    }

    _definitions[d].forEach(function(p){
      Object.defineProperty(self.definitions[d], p, {
        get: function () {
          if (typeof self.locales[self.locale][d] === "undefined" || typeof self.locales[self.locale][d][p] === "undefined") {
            // certain localization sets contain less data then others.
            // in the case of a missing definition, use the default localeFallback to substitute the missing set data
            // throw new Error('unknown property ' + d + p)
            return self.locales[localeFallback][d][p];
          } else {
            // return localized data
            return self.locales[self.locale][d][p];
          }
        }
      });
    });
  });

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.faker.index.prototype"></a>[module faker.index.prototype](#apidoc.module.faker.index.prototype)

#### <a name="apidoc.element.faker.index.prototype.seed"></a>[function <span class="apidocSignatureSpan">faker.index.prototype.</span>seed (value)](#apidoc.element.faker.index.prototype.seed)
- description and source-code
```javascript
seed = function (value) {
  var Random = require('./random');
  this.seedValue = value;
  this.random = new Random(this, this.seedValue);
}
```
- example usage
```shell
...
'''

## Setting a randomness seed

If you want consistent results, you can set your own seed:

'''js
faker.seed(123);

var firstRandom = faker.random.number();

// Setting the seed again resets the sequence.
faker.seed(123);

var secondRandom = faker.random.number();
...
```



# <a name="apidoc.module.faker.internet"></a>[module faker.internet](#apidoc.module.faker.internet)

#### <a name="apidoc.element.faker.internet.avatar"></a>[function <span class="apidocSignatureSpan">faker.internet.</span>avatar ()](#apidoc.element.faker.internet.avatar)
- description and source-code
```javascript
avatar = function () { [native code] }
```
- example usage
```shell
...
 */
self.contextualCard = function () {
  var name = faker.name.firstName(),
      userName = faker.internet.userName(name);
  return {
      "name": name,
      "username": userName,
      "avatar": faker.internet.avatar(),
      "email": faker.internet.email(userName),
      "dob": faker.date.past(50, new Date("Sat Sep 20 1992 21:35:02 GMT+0200 (CEST)")),
      "phone": faker.phone.phoneNumber(),
      "address": {
          "street": faker.address.streetName(true),
          "suite": faker.address.secondaryAddress(),
          "city": faker.address.city(),
...
```

#### <a name="apidoc.element.faker.internet.color"></a>[function <span class="apidocSignatureSpan">faker.internet.</span>color ()](#apidoc.element.faker.internet.color)
- description and source-code
```javascript
color = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.internet.domainName"></a>[function <span class="apidocSignatureSpan">faker.internet.</span>domainName ()](#apidoc.element.faker.internet.domainName)
- description and source-code
```javascript
domainName = function () { [native code] }
```
- example usage
```shell
...
    "zipcode": faker.address.zipCode(),
    "geo": {
        "lat": faker.address.latitude(),
        "lng": faker.address.longitude()
    }
},
"phone": faker.phone.phoneNumber(),
"website": faker.internet.domainName(),
"company": {
    "name": faker.company.companyName(),
    "catchPhrase": faker.company.catchPhrase(),
    "bs": faker.company.bs()
},
"posts": [
    {
...
```

#### <a name="apidoc.element.faker.internet.domainSuffix"></a>[function <span class="apidocSignatureSpan">faker.internet.</span>domainSuffix ()](#apidoc.element.faker.internet.domainSuffix)
- description and source-code
```javascript
domainSuffix = function () { [native code] }
```
- example usage
```shell
...

/**
 * domainName
 *
 * @method faker.internet.domainName
 */
self.domainName = function () {
    return faker.internet.domainWord() + "." + faker.internet.domainSuffix();
};

self.domainName.schema = {
  "description": "Generates a random domain name.",
  "sampleResults": ["marvin.org"]
};
...
```

#### <a name="apidoc.element.faker.internet.domainWord"></a>[function <span class="apidocSignatureSpan">faker.internet.</span>domainWord ()](#apidoc.element.faker.internet.domainWord)
- description and source-code
```javascript
domainWord = function () { [native code] }
```
- example usage
```shell
...

/**
 * domainName
 *
 * @method faker.internet.domainName
 */
self.domainName = function () {
    return faker.internet.domainWord() + "." + faker.internet.domainSuffix();
};

self.domainName.schema = {
  "description": "Generates a random domain name.",
  "sampleResults": ["marvin.org"]
};
...
```

#### <a name="apidoc.element.faker.internet.email"></a>[function <span class="apidocSignatureSpan">faker.internet.</span>email ()](#apidoc.element.faker.internet.email)
- description and source-code
```javascript
email = function () { [native code] }
```
- example usage
```shell
...
## Usage

### Browser

<script src = "faker.js" type = "text/javascript"></script>
<script>
  var randomName = faker.name.findName(); // Caitlyn Kerluke
  var randomEmail = faker.internet.email(); // Rusty@arne.info
  var randomCard = faker.helpers.createCard(); // random contact card containing many properties
</script>

### Node.js

var faker = require('faker');
...
```

#### <a name="apidoc.element.faker.internet.exampleEmail"></a>[function <span class="apidocSignatureSpan">faker.internet.</span>exampleEmail ()](#apidoc.element.faker.internet.exampleEmail)
- description and source-code
```javascript
exampleEmail = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.internet.ip"></a>[function <span class="apidocSignatureSpan">faker.internet.</span>ip ()](#apidoc.element.faker.internet.ip)
- description and source-code
```javascript
ip = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.internet.ipv6"></a>[function <span class="apidocSignatureSpan">faker.internet.</span>ipv6 ()](#apidoc.element.faker.internet.ipv6)
- description and source-code
```javascript
ipv6 = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.internet.mac"></a>[function <span class="apidocSignatureSpan">faker.internet.</span>mac ()](#apidoc.element.faker.internet.mac)
- description and source-code
```javascript
mac = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.internet.password"></a>[function <span class="apidocSignatureSpan">faker.internet.</span>password ()](#apidoc.element.faker.internet.password)
- description and source-code
```javascript
password = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.internet.protocol"></a>[function <span class="apidocSignatureSpan">faker.internet.</span>protocol ()](#apidoc.element.faker.internet.protocol)
- description and source-code
```javascript
protocol = function () { [native code] }
```
- example usage
```shell
...

/**
 * url
 *
 * @method faker.internet.url
 */
self.url = function () {
    return faker.internet.protocol() + '://' + faker.internet.domainName();
};

self.url.schema = {
  "description": "Generates a random URL. The URL could be secure or insecure.",
  "sampleResults": [
    "http://rashawn.name",
    "https://rashawn.name"
...
```

#### <a name="apidoc.element.faker.internet.url"></a>[function <span class="apidocSignatureSpan">faker.internet.</span>url ()](#apidoc.element.faker.internet.url)
- description and source-code
```javascript
url = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.internet.userAgent"></a>[function <span class="apidocSignatureSpan">faker.internet.</span>userAgent ()](#apidoc.element.faker.internet.userAgent)
- description and source-code
```javascript
userAgent = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.internet.userName"></a>[function <span class="apidocSignatureSpan">faker.internet.</span>userName ()](#apidoc.element.faker.internet.userName)
- description and source-code
```javascript
userName = function () { [native code] }
```
- example usage
```shell
...
 * createCard
 *
 * @method faker.helpers.createCard
 */
self.createCard = function () {
    return {
        "name": faker.name.findName(),
        "username": faker.internet.userName(),
        "email": faker.internet.email(),
        "address": {
            "streetA": faker.address.streetName(),
            "streetB": faker.address.streetAddress(),
            "streetC": faker.address.streetAddress(true),
            "streetD": faker.address.secondaryAddress(),
            "city": faker.address.city(),
...
```



# <a name="apidoc.module.faker.lorem"></a>[module faker.lorem](#apidoc.module.faker.lorem)

#### <a name="apidoc.element.faker.lorem.lines"></a>[function <span class="apidocSignatureSpan">faker.lorem.</span>lines ()](#apidoc.element.faker.lorem.lines)
- description and source-code
```javascript
lines = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.lorem.paragraph"></a>[function <span class="apidocSignatureSpan">faker.lorem.</span>paragraph ()](#apidoc.element.faker.lorem.paragraph)
- description and source-code
```javascript
paragraph = function () { [native code] }
```
- example usage
```shell
...
    "bs": faker.company.bs()
},
"posts": [
    {
        "words": faker.lorem.words(),
        "sentence": faker.lorem.sentence(),
        "sentences": faker.lorem.sentences(),
        "paragraph": faker.lorem.paragraph()
    },
    {
        "words": faker.lorem.words(),
        "sentence": faker.lorem.sentence(),
        "sentences": faker.lorem.sentences(),
        "paragraph": faker.lorem.paragraph()
    },
...
```

#### <a name="apidoc.element.faker.lorem.paragraphs"></a>[function <span class="apidocSignatureSpan">faker.lorem.</span>paragraphs ()](#apidoc.element.faker.lorem.paragraphs)
- description and source-code
```javascript
paragraphs = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.lorem.sentence"></a>[function <span class="apidocSignatureSpan">faker.lorem.</span>sentence ()](#apidoc.element.faker.lorem.sentence)
- description and source-code
```javascript
sentence = function () { [native code] }
```
- example usage
```shell
...
    "name": faker.company.companyName(),
    "catchPhrase": faker.company.catchPhrase(),
    "bs": faker.company.bs()
},
"posts": [
    {
        "words": faker.lorem.words(),
        "sentence": faker.lorem.sentence(),
        "sentences": faker.lorem.sentences(),
        "paragraph": faker.lorem.paragraph()
    },
    {
        "words": faker.lorem.words(),
        "sentence": faker.lorem.sentence(),
        "sentences": faker.lorem.sentences(),
...
```

#### <a name="apidoc.element.faker.lorem.sentences"></a>[function <span class="apidocSignatureSpan">faker.lorem.</span>sentences ()](#apidoc.element.faker.lorem.sentences)
- description and source-code
```javascript
sentences = function () { [native code] }
```
- example usage
```shell
...
    "catchPhrase": faker.company.catchPhrase(),
    "bs": faker.company.bs()
},
"posts": [
    {
        "words": faker.lorem.words(),
        "sentence": faker.lorem.sentence(),
        "sentences": faker.lorem.sentences(),
        "paragraph": faker.lorem.paragraph()
    },
    {
        "words": faker.lorem.words(),
        "sentence": faker.lorem.sentence(),
        "sentences": faker.lorem.sentences(),
        "paragraph": faker.lorem.paragraph()
...
```

#### <a name="apidoc.element.faker.lorem.slug"></a>[function <span class="apidocSignatureSpan">faker.lorem.</span>slug ()](#apidoc.element.faker.lorem.slug)
- description and source-code
```javascript
slug = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.lorem.text"></a>[function <span class="apidocSignatureSpan">faker.lorem.</span>text ()](#apidoc.element.faker.lorem.text)
- description and source-code
```javascript
text = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.lorem.word"></a>[function <span class="apidocSignatureSpan">faker.lorem.</span>word ()](#apidoc.element.faker.lorem.word)
- description and source-code
```javascript
word = function () { [native code] }
```
- example usage
```shell
...
 * @method faker.lorem.words
 * @param {number} num number of words, defaults to 3
 */
self.words = function (num) {
    if (typeof num == 'undefined') { num = 3; }
    var words = [];
    for (var i = 0; i < num; i++) {
      words.push(faker.lorem.word());
    }
    return words.join(' ');
};

/**
 * sentence
 *
...
```

#### <a name="apidoc.element.faker.lorem.words"></a>[function <span class="apidocSignatureSpan">faker.lorem.</span>words ()](#apidoc.element.faker.lorem.words)
- description and source-code
```javascript
words = function () { [native code] }
```
- example usage
```shell
...
"company": {
    "name": faker.company.companyName(),
    "catchPhrase": faker.company.catchPhrase(),
    "bs": faker.company.bs()
},
"posts": [
    {
        "words": faker.lorem.words(),
        "sentence": faker.lorem.sentence(),
        "sentences": faker.lorem.sentences(),
        "paragraph": faker.lorem.paragraph()
    },
    {
        "words": faker.lorem.words(),
        "sentence": faker.lorem.sentence(),
...
```



# <a name="apidoc.module.faker.name"></a>[module faker.name](#apidoc.module.faker.name)

#### <a name="apidoc.element.faker.name.findName"></a>[function <span class="apidocSignatureSpan">faker.name.</span>findName ()](#apidoc.element.faker.name.findName)
- description and source-code
```javascript
findName = function () { [native code] }
```
- example usage
```shell
...

## Usage

### Browser

<script src = "faker.js" type = "text/javascript"></script>
<script>
  var randomName = faker.name.findName(); // Caitlyn Kerluke
  var randomEmail = faker.internet.email(); // Rusty@arne.info
  var randomCard = faker.helpers.createCard(); // random contact card containing many properties
</script>

### Node.js

var faker = require('faker');
...
```

#### <a name="apidoc.element.faker.name.firstName"></a>[function <span class="apidocSignatureSpan">faker.name.</span>firstName ()](#apidoc.element.faker.name.firstName)
- description and source-code
```javascript
firstName = function () { [native code] }
```
- example usage
```shell
...
**Example:**

''' js
console.log(faker.fake("{{name.lastName}}, {{name.firstName}} {{name.suffix}}"));
// outputs: "Marks, Dean Sr."
'''

This will interpolate the format string with the value of methods 'name.lastName()', 'name.firstName()', and 'name.suffix()'

### JSDoc API Browser

[http://marak.github.io/faker.js/](http://marak.github.io/faker.js/)

### API Methods
...
```

#### <a name="apidoc.element.faker.name.jobArea"></a>[function <span class="apidocSignatureSpan">faker.name.</span>jobArea ()](#apidoc.element.faker.name.jobArea)
- description and source-code
```javascript
jobArea = function () { [native code] }
```
- example usage
```shell
...
 * jobTitle
 *
 * @method jobTitle
 * @memberof faker.name
 */
this.jobTitle = function () {
  return  faker.name.jobDescriptor() + " " +
    faker.name.jobArea() + " " +
    faker.name.jobType();
};

/**
 * prefix
 *
 * @method prefix
...
```

#### <a name="apidoc.element.faker.name.jobDescriptor"></a>[function <span class="apidocSignatureSpan">faker.name.</span>jobDescriptor ()](#apidoc.element.faker.name.jobDescriptor)
- description and source-code
```javascript
jobDescriptor = function () { [native code] }
```
- example usage
```shell
...
/**
 * jobTitle
 *
 * @method jobTitle
 * @memberof faker.name
 */
this.jobTitle = function () {
  return  faker.name.jobDescriptor() + " " +
    faker.name.jobArea() + " " +
    faker.name.jobType();
};

/**
 * prefix
 *
...
```

#### <a name="apidoc.element.faker.name.jobTitle"></a>[function <span class="apidocSignatureSpan">faker.name.</span>jobTitle ()](#apidoc.element.faker.name.jobTitle)
- description and source-code
```javascript
jobTitle = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.name.jobType"></a>[function <span class="apidocSignatureSpan">faker.name.</span>jobType ()](#apidoc.element.faker.name.jobType)
- description and source-code
```javascript
jobType = function () { [native code] }
```
- example usage
```shell
...
 *
 * @method jobTitle
 * @memberof faker.name
 */
this.jobTitle = function () {
  return  faker.name.jobDescriptor() + " " +
    faker.name.jobArea() + " " +
    faker.name.jobType();
};

/**
 * prefix
 *
 * @method prefix
 * @param {mixed} gender
...
```

#### <a name="apidoc.element.faker.name.lastName"></a>[function <span class="apidocSignatureSpan">faker.name.</span>lastName ()](#apidoc.element.faker.name.lastName)
- description and source-code
```javascript
lastName = function () { [native code] }
```
- example usage
```shell
...
**Example:**

''' js
console.log(faker.fake("{{name.lastName}}, {{name.firstName}} {{name.suffix}}"));
// outputs: "Marks, Dean Sr."
'''

This will interpolate the format string with the value of methods 'name.lastName()', 'name.firstName()', and 'name.suffix()'

### JSDoc API Browser

[http://marak.github.io/faker.js/](http://marak.github.io/faker.js/)

### API Methods
...
```

#### <a name="apidoc.element.faker.name.prefix"></a>[function <span class="apidocSignatureSpan">faker.name.</span>prefix ()](#apidoc.element.faker.name.prefix)
- description and source-code
```javascript
prefix = function () { [native code] }
```
- example usage
```shell
...
if (typeof gender !== 'number') {
  gender = faker.random.number(1);
}
firstName = firstName || faker.name.firstName(gender);
lastName = lastName || faker.name.lastName(gender);
switch (r) {
case 0:
    prefix = faker.name.prefix(gender);
    if (prefix) {
        return prefix + " " + firstName + " " + lastName;
    }
case 1:
    suffix = faker.name.suffix(gender);
    if (suffix) {
        return firstName + " " + lastName + " " + suffix;
...
```

#### <a name="apidoc.element.faker.name.suffix"></a>[function <span class="apidocSignatureSpan">faker.name.</span>suffix ()](#apidoc.element.faker.name.suffix)
- description and source-code
```javascript
suffix = function () { [native code] }
```
- example usage
```shell
...
**Example:**

''' js
console.log(faker.fake("{{name.lastName}}, {{name.firstName}} {{name.suffix}}"));
// outputs: "Marks, Dean Sr."
'''

This will interpolate the format string with the value of methods 'name.lastName()', 'name.firstName()', and 'name.suffix()'

### JSDoc API Browser

[http://marak.github.io/faker.js/](http://marak.github.io/faker.js/)

### API Methods
...
```

#### <a name="apidoc.element.faker.name.title"></a>[function <span class="apidocSignatureSpan">faker.name.</span>title ()](#apidoc.element.faker.name.title)
- description and source-code
```javascript
title = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.faker.phone"></a>[module faker.phone](#apidoc.module.faker.phone)

#### <a name="apidoc.element.faker.phone.phoneFormats"></a>[function <span class="apidocSignatureSpan">faker.phone.</span>phoneFormats ()](#apidoc.element.faker.phone.phoneFormats)
- description and source-code
```javascript
phoneFormats = function () { [native code] }
```
- example usage
```shell
...
/**
 * phoneNumber
 *
 * @method faker.phone.phoneNumber
 * @param {string} format
 */
self.phoneNumber = function (format) {
    format = format || faker.phone.phoneFormats();
    return faker.helpers.replaceSymbolWithNumber(format);
};

// FIXME: this is strange passing in an array index.
/**
 * phoneNumberFormat
 *
...
```

#### <a name="apidoc.element.faker.phone.phoneNumber"></a>[function <span class="apidocSignatureSpan">faker.phone.</span>phoneNumber ()](#apidoc.element.faker.phone.phoneNumber)
- description and source-code
```javascript
phoneNumber = function () { [native code] }
```
- example usage
```shell
...
    "country": faker.address.country(),
    "zipcode": faker.address.zipCode(),
    "geo": {
        "lat": faker.address.latitude(),
        "lng": faker.address.longitude()
    }
},
"phone": faker.phone.phoneNumber(),
"website": faker.internet.domainName(),
"company": {
    "name": faker.company.companyName(),
    "catchPhrase": faker.company.catchPhrase(),
    "bs": faker.company.bs()
},
"posts": [
...
```

#### <a name="apidoc.element.faker.phone.phoneNumberFormat"></a>[function <span class="apidocSignatureSpan">faker.phone.</span>phoneNumberFormat ()](#apidoc.element.faker.phone.phoneNumberFormat)
- description and source-code
```javascript
phoneNumberFormat = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.faker.random"></a>[module faker.random](#apidoc.module.faker.random)

#### <a name="apidoc.element.faker.random.alphaNumeric"></a>[function <span class="apidocSignatureSpan">faker.random.</span>alphaNumeric ()](#apidoc.element.faker.random.alphaNumeric)
- description and source-code
```javascript
alphaNumeric = function () { [native code] }
```
- example usage
```shell
...
 */
self.bitcoinAddress = function () {
  var addressLength = faker.random.number({ min: 27, max: 34 });

  var address = faker.random.arrayElement(['1', '3']);

  for (var i = 0; i < addressLength - 1; i++)
    address += faker.random.alphaNumeric().toUpperCase();

  return address;
};

/**
 * iban
 *
...
```

#### <a name="apidoc.element.faker.random.arrayElement"></a>[function <span class="apidocSignatureSpan">faker.random.</span>arrayElement ()](#apidoc.element.faker.random.arrayElement)
- description and source-code
```javascript
arrayElement = function () { [native code] }
```
- example usage
```shell
...
this.zipCode = function(format) {
  // if zip format is not specified, use the zip format defined for the locale
  if (typeof format === 'undefined') {
    var localeFormat = faker.definitions.address.postcode;
    if (typeof localeFormat === 'string') {
      format = localeFormat;
    } else {
      format = faker.random.arrayElement(localeFormat);
    }
  }
  return Helpers.replaceSymbols(format);
}

/**
 * Generates a random localized city name. The format string can contain any
...
```

#### <a name="apidoc.element.faker.random.boolean"></a>[function <span class="apidocSignatureSpan">faker.random.</span>boolean ()](#apidoc.element.faker.random.boolean)
- description and source-code
```javascript
boolean = function () { [native code] }
```
- example usage
```shell
...
    if (faker.random.number(100) < 80) {
        s += faker.random.number(9);
    } else {
        s += faker.random.arrayElement(ibanLib.alpha);
    }
} else {
    if (c >= 3 && faker.random.number(100) < 30) {
        if (faker.random.boolean()) {
            s += faker.random.arrayElement(ibanLib.pattern100);
            c -= 2;
        } else {
            s += faker.random.arrayElement(ibanLib.pattern10);
            c--;
        }
    } else {
...
```

#### <a name="apidoc.element.faker.random.image"></a>[function <span class="apidocSignatureSpan">faker.random.</span>image ()](#apidoc.element.faker.random.image)
- description and source-code
```javascript
image = function () { [native code] }
```
- example usage
```shell
...

/**
 * locale
 *
 * @method faker.random.image
 */
this.image = function randomImage () {
  return faker.image.image();
}

/**
 * locale
 *
 * @method faker.random.locale
 */
...
```

#### <a name="apidoc.element.faker.random.locale"></a>[function <span class="apidocSignatureSpan">faker.random.</span>locale ()](#apidoc.element.faker.random.locale)
- description and source-code
```javascript
locale = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.random.number"></a>[function <span class="apidocSignatureSpan">faker.random.</span>number ()](#apidoc.element.faker.random.number)
- description and source-code
```javascript
number = function () { [native code] }
```
- example usage
```shell
...
## Setting a randomness seed

If you want consistent results, you can set your own seed:

'''js
faker.seed(123);

var firstRandom = faker.random.number();

// Setting the seed again resets the sequence.
faker.seed(123);

var secondRandom = faker.random.number();

console.log(firstRandom === secondRandom);
...
```

#### <a name="apidoc.element.faker.random.objectElement"></a>[function <span class="apidocSignatureSpan">faker.random.</span>objectElement ()](#apidoc.element.faker.random.objectElement)
- description and source-code
```javascript
objectElement = function () { [native code] }
```
- example usage
```shell
...

/**
 * currencyCode
 *
 * @method faker.finance.currencyCode
 */
self.currencyCode = function () {
    return faker.random.objectElement(faker.definitions.finance.currency)['code'];
};

/**
 * currencyName
 *
 * @method faker.finance.currencyName
 */
...
```

#### <a name="apidoc.element.faker.random.uuid"></a>[function <span class="apidocSignatureSpan">faker.random.</span>uuid ()](#apidoc.element.faker.random.uuid)
- description and source-code
```javascript
uuid = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.random.word"></a>[function <span class="apidocSignatureSpan">faker.random.</span>word ()](#apidoc.element.faker.random.word)
- description and source-code
```javascript
word = function () { [native code] }
```
- example usage
```shell
...
 * @method faker.lorem.words
 * @param {number} num number of words, defaults to 3
 */
self.words = function (num) {
    if (typeof num == 'undefined') { num = 3; }
    var words = [];
    for (var i = 0; i < num; i++) {
      words.push(faker.lorem.word());
    }
    return words.join(' ');
};

/**
 * sentence
 *
...
```

#### <a name="apidoc.element.faker.random.words"></a>[function <span class="apidocSignatureSpan">faker.random.</span>words ()](#apidoc.element.faker.random.words)
- description and source-code
```javascript
words = function () { [native code] }
```
- example usage
```shell
...
"company": {
    "name": faker.company.companyName(),
    "catchPhrase": faker.company.catchPhrase(),
    "bs": faker.company.bs()
},
"posts": [
    {
        "words": faker.lorem.words(),
        "sentence": faker.lorem.sentence(),
        "sentences": faker.lorem.sentences(),
        "paragraph": faker.lorem.paragraph()
    },
    {
        "words": faker.lorem.words(),
        "sentence": faker.lorem.sentence(),
...
```



# <a name="apidoc.module.faker.system"></a>[module faker.system](#apidoc.module.faker.system)

#### <a name="apidoc.element.faker.system.commonFileExt"></a>[function <span class="apidocSignatureSpan">faker.system.</span>commonFileExt ()](#apidoc.element.faker.system.commonFileExt)
- description and source-code
```javascript
commonFileExt = function () { [native code] }
```
- example usage
```shell
...
 * commonFileName
 *
 * @method faker.system.commonFileName
 * @param {string} ext
 * @param {string} type
 */
this.commonFileName = function (ext, type) {
  var str = faker.random.words() + "." + (ext || faker.system.commonFileExt());
  str = str.replace(/ /g, '_');
  str = str.replace(/\,/g, '_');
  str = str.replace(/\-/g, '_');
  str = str.replace(/\\/g, '_');
  str = str.replace(/\//g, '_');
  str = str.toLowerCase();
  return str;
...
```

#### <a name="apidoc.element.faker.system.commonFileName"></a>[function <span class="apidocSignatureSpan">faker.system.</span>commonFileName ()](#apidoc.element.faker.system.commonFileName)
- description and source-code
```javascript
commonFileName = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.system.commonFileType"></a>[function <span class="apidocSignatureSpan">faker.system.</span>commonFileType ()](#apidoc.element.faker.system.commonFileType)
- description and source-code
```javascript
commonFileType = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.system.directoryPath"></a>[function <span class="apidocSignatureSpan">faker.system.</span>directoryPath ()](#apidoc.element.faker.system.directoryPath)
- description and source-code
```javascript
directoryPath = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.system.fileExt"></a>[function <span class="apidocSignatureSpan">faker.system.</span>fileExt ()](#apidoc.element.faker.system.fileExt)
- description and source-code
```javascript
fileExt = function () { [native code] }
```
- example usage
```shell
...
    'image/png',
    'image/jpeg',
    'image/gif',
    'video/mp4',
    'video/mpeg',
    'text/html'
  ];
  return faker.system.fileExt(faker.random.arrayElement(types));
};


/**
 * returns any file type available as mime-type
 *
 * @method faker.system.fileType
...
```

#### <a name="apidoc.element.faker.system.fileName"></a>[function <span class="apidocSignatureSpan">faker.system.</span>fileName ()](#apidoc.element.faker.system.fileName)
- description and source-code
```javascript
fileName = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.system.filePath"></a>[function <span class="apidocSignatureSpan">faker.system.</span>filePath ()](#apidoc.element.faker.system.filePath)
- description and source-code
```javascript
filePath = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.system.fileType"></a>[function <span class="apidocSignatureSpan">faker.system.</span>fileType ()](#apidoc.element.faker.system.fileType)
- description and source-code
```javascript
fileType = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.system.mimeType"></a>[function <span class="apidocSignatureSpan">faker.system.</span>mimeType ()](#apidoc.element.faker.system.mimeType)
- description and source-code
```javascript
mimeType = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.faker.system.semver"></a>[function <span class="apidocSignatureSpan">faker.system.</span>semver ()](#apidoc.element.faker.system.semver)
- description and source-code
```javascript
semver = function () { [native code] }
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
