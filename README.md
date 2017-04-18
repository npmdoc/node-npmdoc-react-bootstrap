# npmdoc-react-bootstrap

#### api documentation for  [react-bootstrap (v0.30.8)](https://react-bootstrap.github.io/)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-bootstrap.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-bootstrap) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-bootstrap.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-bootstrap)

#### Bootstrap 3 components built with React

[![NPM](https://nodei.co/npm/react-bootstrap.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-bootstrap)

- [https://npmdoc.github.io/node-npmdoc-react-bootstrap/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-bootstrap/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-bootstrap/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-bootstrap/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-bootstrap/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-bootstrap/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Stephen J. Collings"
    },
    "bugs": {
        "url": "https://github.com/react-bootstrap/react-bootstrap/issues"
    },
    "dependencies": {
        "babel-runtime": "^6.11.6",
        "classnames": "^2.2.5",
        "dom-helpers": "^3.2.0",
        "invariant": "^2.2.1",
        "keycode": "^2.1.2",
        "react-overlays": "^0.6.12",
        "react-prop-types": "^0.4.0",
        "uncontrollable": "^4.0.1",
        "warning": "^3.0.0"
    },
    "description": "Bootstrap 3 components built with React",
    "devDependencies": {
        "babel-cli": "^6.11.4",
        "babel-core": "^6.13.2",
        "babel-eslint": "^6.1.2",
        "babel-loader": "^6.2.5",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-plugin-dev-expression": "^0.2.1",
        "babel-plugin-istanbul": "^1.0.3",
        "babel-plugin-transform-es3-member-expression-literals": "^6.8.0",
        "babel-plugin-transform-es3-property-literals": "^6.8.0",
        "babel-plugin-transform-runtime": "^6.12.0",
        "babel-preset-es2015": "^6.13.2",
        "babel-preset-react": "^6.11.1",
        "babel-preset-stage-1": "^6.13.0",
        "babel-register": "^6.11.6",
        "babel-standalone": "^6.21.1",
        "bootstrap": "^3.3.6",
        "brfs": "^1.4.3",
        "chai": "^3.5.0",
        "child-process-promise": "^2.0.3",
        "codecov": "^1.0.1",
        "codemirror": "^5.16.0",
        "colors": "^1.1.2",
        "cross-env": "^2.0.0",
        "css-loader": "^0.23.1",
        "eslint": "^1.10.3",
        "eslint-config-airbnb": "^0.1.1",
        "eslint-plugin-babel": "^3.3.0",
        "eslint-plugin-mocha": "^1.1.0",
        "eslint-plugin-react": "^3.16.1",
        "express": "^4.14.0",
        "extract-text-webpack-plugin": "^1.0.1",
        "file-loader": "^0.9.0",
        "fs-extra": "^0.30.0",
        "fs-promise": "^0.5.0",
        "glob": "^7.1.0",
        "http-proxy": "^1.14.0",
        "ip": "^1.1.3",
        "json-loader": "^0.5.4",
        "karma": "^1.1.1",
        "karma-chrome-launcher": "^1.0.1",
        "karma-cli": "^1.0.1",
        "karma-coverage": "^1.1.0",
        "karma-firefox-launcher": "^1.0.0",
        "karma-mocha": "^1.1.1",
        "karma-mocha-reporter": "^2.0.4",
        "karma-sinon-chai": "^1.2.2",
        "karma-sourcemap-loader": "^0.3.7",
        "karma-webpack": "^1.7.0",
        "less": "^2.7.1",
        "less-loader": "^2.2.3",
        "lodash": "^4.13.1",
        "marked": "^0.3.6",
        "mocha": "^2.5.3",
        "node-libs-browser": "^1.0.0",
        "nodemon": "^1.9.2",
        "output-file-sync": "^1.1.2",
        "portfinder": "^1.0.3",
        "react": "^15.4.0",
        "react-addons-test-utils": "^15.4.0",
        "react-component-metadata": "^3.1.0",
        "react-dom": "^15.4.0",
        "react-hot-loader": "^1.3.0",
        "react-router": "^2.6.1",
        "react-waypoint": "^3.0.0",
        "release-script": "^1.0.2",
        "rimraf": "^2.5.3",
        "semver": "^5.2.0",
        "sinon": "^1.17.4",
        "sinon-chai": "^2.8.0",
        "style-loader": "^0.13.1",
        "teaspoon": "^6.4.2",
        "transform-loader": "^0.2.3",
        "webpack": "^1.13.1",
        "webpack-dev-server": "^1.14.1",
        "yargs": "^4.7.1"
    },
    "directories": {},
    "dist": {
        "shasum": "4ceca8e138ce2351228c4a58d59db00c003ca9c0",
        "tarball": "https://registry.npmjs.org/react-bootstrap/-/react-bootstrap-0.30.8.tgz"
    },
    "files": [
        "CHANGELOG.md",
        "lib",
        "dist",
        "es"
    ],
    "gitHead": "6adbf8a4756b0e14c4417e52e7befb88b258e6ca",
    "homepage": "https://react-bootstrap.github.io/",
    "jsnext:main": "es/index.js",
    "keywords": [
        "react",
        "ecosystem-react",
        "react-component",
        "bootstrap"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "stevoland"
        },
        {
            "name": "mtscout6"
        },
        {
            "name": "taion"
        },
        {
            "name": "monastic.panic"
        }
    ],
    "module": "es/index.js",
    "name": "react-bootstrap",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": ">=0.14.0",
        "react-dom": ">=0.14.0"
    },
    "release-script": {
        "bowerRepo": "git@github.com:react-bootstrap/react-bootstrap-bower.git",
        "docsRepo": "git@github.com:react-bootstrap/react-bootstrap.github.io.git"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/react-bootstrap/react-bootstrap.git"
    },
    "scripts": {
        "build": "babel-node tools/build-cli.js",
        "docs": "babel-node docs/dev-run.js",
        "docs-build": "babel-node tools/build-cli.js --docs-only",
        "docs-prod": "npm run docs-build && cross-env NODE_ENV=production babel-node docs/server.js",
        "docs-prod-unoptimized": "npm run docs-build -- --dev && cross-env NODE_ENV=production babel-node docs/server.js",
        "lint": "eslint docs src test tools webpack *.js",
        "release": "release",
        "tdd": "karma start",
        "test": "npm run lint && npm run test-browser && npm run test-node",
        "test-browser": "cross-env NODE_ENV=test karma start --single-run",
        "test-node": "mocha --compilers js:babel-register test/server/*Spec.js"
    },
    "version": "0.30.8"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
