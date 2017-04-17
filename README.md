# test coverage for  [react-mdl (v1.10.0)](https://github.com/tleunen/react-mdl#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-react-mdl.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-mdl) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-mdl.svg)](https://travis-ci.org/npmtest/node-npmtest-react-mdl)
#### React Components for Material Design Lite

[![NPM](https://nodei.co/npm/react-mdl.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-mdl)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-mdl/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-mdl/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-mdl/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-mdl/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-mdl/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-mdl/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-mdl/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-mdl/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-mdl/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-mdl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-mdl/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-mdl/build/test-report.html](https://npmtest.github.io/node-npmtest-react-mdl/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-mdl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-mdl/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-mdl/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-mdl/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-mdl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-mdl/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-mdl/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-mdl/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tommy Leunen",
        "url": "http://tommyleunen.com/"
    },
    "bugs": {
        "url": "https://github.com/tleunen/react-mdl/issues"
    },
    "dependencies": {
        "clamp": "^1.0.1",
        "classnames": "^2.2.3",
        "lodash.isequal": "^4.4.0",
        "prop-types": "^15.5.0"
    },
    "description": "React Components for Material Design Lite",
    "devDependencies": {
        "add-stream": "^1.0.0",
        "babel-cli": "^6.11.4",
        "babel-core": "^6.13.2",
        "babel-loader": "^6.2.5",
        "babel-plugin-__coverage__": "^11.0.0",
        "babel-plugin-transform-object-rest-spread": "^6.6.5",
        "babel-polyfill": "^6.13.0",
        "babel-preset-es2015": "^6.13.2",
        "babel-preset-react": "^6.5.0",
        "chai": "^3.5.0",
        "chai-enzyme": "^0.6.1",
        "conventional-changelog": "^1.1.0",
        "cross-env": "^4.0.0",
        "enzyme": "^2.4.1",
        "eslint": "^2.7.0",
        "eslint-config-airbnb": "^9.0.1",
        "eslint-plugin-import": "^1.13.0",
        "eslint-plugin-jsx-a11y": "^1.5.3",
        "eslint-plugin-react": "5.1.1",
        "expect": "^1.16.0",
        "gatsby": "^0.12.43",
        "gh-pages": "^0.12.0",
        "isparta": "^4.0.0",
        "isparta-loader": "^2.0.0",
        "json-loader": "^0.5.4",
        "karma": "^1.2.0",
        "karma-chai": "^0.1.0",
        "karma-chrome-launcher": "^1.0.1",
        "karma-cli": "^1.0.0",
        "karma-coverage": "^1.1.1",
        "karma-mocha": "^1.0.1",
        "karma-mocha-reporter": "^2.1.0",
        "karma-sinon": "^1.0.5",
        "karma-sourcemap-loader": "^0.3.7",
        "karma-webpack": "^1.8.0",
        "mocha": "^3.0.2",
        "react": "^15.3.1",
        "react-addons-test-utils": "^15.3.1",
        "react-dom": "^15.3.1",
        "react-router": "^2.6.1",
        "rimraf": "^2.5.4",
        "sinon": "^2.1.0",
        "standard-version": "^4.0.0",
        "webpack": "^1.13.2",
        "webpack-dev-server": "^1.14.1"
    },
    "directories": {},
    "dist": {
        "shasum": "7fadddddbc2fe269c74516d4fac0822c5cce205f",
        "tarball": "https://registry.npmjs.org/react-mdl/-/react-mdl-1.10.0.tgz"
    },
    "gitHead": "6c8036353cb280a4e27663c2eac1677fff9014a9",
    "homepage": "https://github.com/tleunen/react-mdl#readme",
    "jsnext:main": "src/index.js",
    "keywords": [
        "react",
        "react-component",
        "mdl",
        "material-design",
        "badge",
        "button",
        "card",
        "checkbox",
        "data-table",
        "fab-button",
        "icon",
        "icon-button",
        "icon-toggle",
        "radio",
        "radio-group",
        "switch",
        "textfield",
        "progress",
        "progress-bar",
        "spinner",
        "slider",
        "tooltip",
        "menu",
        "dropdown",
        "Layout",
        "Drawer",
        "Grid",
        "Tabs"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "tleunen"
        }
    ],
    "name": "react-mdl",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "0.14.x || ^15.0.0-rc",
        "react-dom": "0.14.x || ^15.0.0-rc"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/tleunen/react-mdl.git"
    },
    "scripts": {
        "build-docs": "cd docs && ./node_modules/.bin/gatsby build --prefix-links",
        "build-min": "cross-env NODE_ENV=production webpack -p src/index.js out/ReactMDL.min.js --output-library ReactMDL --output-library-target umd",
        "build-umd": "cross-env NODE_ENV=production webpack src/index.js out/ReactMDL.js --output-library ReactMDL --output-library-target umd",
        "clean": "rimraf coverage lib out",
        "compile": "rimraf lib && babel src --ignore __tests__ --out-dir lib",
        "lint": "eslint src scripts",
        "pretest": "npm run lint",
        "react:14": "npm run react:clean && npm i react@0.14 react-dom@0.14 react-addons-test-utils@0.14",
        "react:15": "npm run react:clean && npm i react@15 react-dom@15 react-addons-test-utils@15",
        "react:clean": "rimraf node_modules/react node_modules/react-dom node_modules/react-addons-test-utils",
        "release": "./scripts/release.sh",
        "release-docs": "gh-pages -d docs/public/ -m 'Updates v'$npm_package_version",
        "serve-docs": "cd docs && ./node_modules/.bin/gatsby develop",
        "test": "npm run test:react:14 && npm run test:react:15",
        "test:react:14": "npm run react:14 && npm run test:suite",
        "test:react:15": "npm run react:15 && npm run test:suite",
        "test:suite": "karma start --single-run",
        "test:watch": "karma start --auto-watch"
    },
    "version": "1.10.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
