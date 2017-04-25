# npmtest-tishadow

#### basic test coverage for  tishadow (v2.9.1)  [![npm package](https://img.shields.io/npm/v/npmtest-tishadow.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-tishadow) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-tishadow.svg)](https://travis-ci.org/npmtest/node-npmtest-tishadow)

#### Quick Titanium previews across devices

[![NPM](https://nodei.co/npm/tishadow.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/tishadow)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-tishadow/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-tishadow/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-tishadow/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-tishadow/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-tishadow/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-tishadow/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-tishadow/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-tishadow/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-tishadow/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-tishadow/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-tishadow/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-tishadow/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-tishadow/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-tishadow/build/test-report.html](https://npmtest.github.io/node-npmtest-tishadow/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-tishadow/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-tishadow/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-tishadow/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-tishadow/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-tishadow/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-tishadow/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-tishadow/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-tishadow/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "tishadow",
    "version": "2.9.1",
    "dependencies": {
        "archiver": "^1.3.0",
        "async": "^0.2.10",
        "body-parser": "^1.14.1",
        "chokidar": "^1.6.0",
        "colors": "^1.1.2",
        "commander": "^1.0.5",
        "express": "^3.3.8",
        "form-data": "^0.1.4",
        "glob": "^3.2.11",
        "ipselector": "^0.1.4",
        "istanbul": "^0.3.22",
        "jade": "^1.11.0",
        "jshint": "^0.9.1",
        "lazystream": "^0.1.0",
        "mkdirp": "^0.3.5",
        "mocha": "^1.12.1",
        "multiparty": "^4.1.2",
        "node-notifier": "^4.6.0",
        "pkginfo": "^0.2.3",
        "socket.io": "^0.9.17",
        "socket.io-client": "^0.9.17",
        "tiapp": "0.0.3",
        "uglify-js": "^2.7.5",
        "underscore": "^1.8.3",
        "update-notifier": "^0.1.10",
        "wrench": "~1.4.4",
        "ws": "^1.1.1"
    },
    "devDependencies": {},
    "optionalDependencies": {},
    "engines": {
        "node": ">=0.12"
    },
    "author": "David Bankier <david@yydigital.com> (http://www.yydigital.com)",
    "description": "Quick Titanium previews across devices",
    "repository": {
        "type": "git",
        "url": "git://github.com/dbankier/TiShadow.git"
    },
    "bin": {
        "tishadow": "./cli/tishadow",
        "ts": "./cli/tishadow"
    },
    "scripts": {
        "postinstall": "node cli/tishadow express"
    },
    "license": "Apache-2.0",
    "framework": "none",
    "main": "server/app.js"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
