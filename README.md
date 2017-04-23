# npmtest-nativescript-cardview

#### basic test coverage for  [nativescript-cardview (v2.0.0-rc.0)](https://github.com/bradmartin/nativescript-cardview)  [![npm package](https://img.shields.io/npm/v/npmtest-nativescript-cardview.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-nativescript-cardview) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-nativescript-cardview.svg)](https://travis-ci.org/npmtest/node-npmtest-nativescript-cardview)

#### A NativeScript plugin for Material Design CardView component.

[![NPM](https://nodei.co/npm/nativescript-cardview.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nativescript-cardview)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-nativescript-cardview/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-nativescript-cardview/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-nativescript-cardview/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-nativescript-cardview/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-nativescript-cardview/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-nativescript-cardview/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-nativescript-cardview/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-nativescript-cardview/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-nativescript-cardview/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-nativescript-cardview/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-nativescript-cardview/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-nativescript-cardview/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-nativescript-cardview/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-nativescript-cardview/build/test-report.html](https://npmtest.github.io/node-npmtest-nativescript-cardview/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-nativescript-cardview/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-nativescript-cardview/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-nativescript-cardview/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nativescript-cardview/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nativescript-cardview/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nativescript-cardview/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-nativescript-cardview/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-nativescript-cardview/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "nativescript-cardview",
    "version": "2.0.0-rc.0",
    "description": "A NativeScript plugin for Material Design CardView component.",
    "main": "cardview",
    "typings": "index.d.ts",
    "nativescript": {
        "platforms": {
            "android": "2.3.0",
            "ios": "2.3.0"
        }
    },
    "scripts": {
        "build": "tsc",
        "demo.ios": "npm run preparedemo; cd demo; tns run ios --emulator",
        "demo.android": "npm run preparedemo; cd demo; tns run android --emulator",
        "preparedemo": "npm run build; cd demo; tns plugin remove nativescript-cardview; tns plugin add ..",
        "setup": "npm i && npm run build && cd demo && tns plugin add .. && cd .."
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/bradmartin/nativescript-cardview"
    },
    "keywords": [
        "NativeScript",
        "TypeScript",
        "Card",
        "android",
        "ios",
        "CardView",
        "Material Design"
    ],
    "contributors": [
        {
            "name": "Nathanael Anderson",
            "url": "https://github.com/nathanaela"
        },
        {
            "name": "Nathanael Walker",
            "url": "https://github.com/NathanWalker"
        },
        {
            "name": "Ned",
            "url": "https://github.com/manijak"
        },
        {
            "name": "Vladimir Nani",
            "url": "https://github.com/vladimirnani"
        },
        {
            "name": "Stanimira Vlaeva",
            "url": "https://github.com/sis0k0"
        },
        {
            "name": "Eddy Verbruggen",
            "url": "https://github.com/EddyVerbruggen"
        }
    ],
    "author": "Brad Martin <bradwaynemartin@gmail.com> (https://github.com/bradmartin)",
    "license": "Apache-2.0",
    "bugs": "https://github.com/bradmartin/nativescript-cardview/issues",
    "homepage": "https://github.com/bradmartin/nativescript-cardview",
    "peerDependencies": {
        "tns-core-modules": ">=3.0.0 || >=3.0.0-rc.1 || >=3.0.0-2017"
    },
    "devDependencies": {
        "tns-core-modules": "3.0.0-rc.2"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
