# api documentation for  [react-bootstrap (v0.30.8)](https://react-bootstrap.github.io/)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-bootstrap.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-bootstrap) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-bootstrap.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-bootstrap)
#### Bootstrap 3 components built with React

[![NPM](https://nodei.co/npm/react-bootstrap.png?downloads=true)](https://www.npmjs.com/package/react-bootstrap)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-bootstrap/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-react-bootstrap_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-bootstrap/build..beta..travis-ci.org/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-bootstrap/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-bootstrap/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Stephen J. Collings",
        "email": "stevoland@gmail.com"
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
            "name": "stevoland",
            "email": "stevoland@gmail.com"
        },
        {
            "name": "mtscout6",
            "email": "mtscout6@gmail.com"
        },
        {
            "name": "taion",
            "email": "tesrin@gmail.com"
        },
        {
            "name": "monastic.panic",
            "email": "monastic.panic@gmail.com"
        }
    ],
    "module": "es/index.js",
    "name": "react-bootstrap",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": ">=0.14.0",
        "react-dom": ">=0.14.0"
    },
    "readme": "ERROR: No README data found!",
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



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module react-bootstrap](#apidoc.module.react-bootstrap)
1.  boolean <span class="apidocSignatureSpan">react-bootstrap.</span>__esModule
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Accordion ()](#apidoc.element.react-bootstrap.Accordion)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Alert ()](#apidoc.element.react-bootstrap.Alert)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Badge ()](#apidoc.element.react-bootstrap.Badge)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Breadcrumb ()](#apidoc.element.react-bootstrap.Breadcrumb)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>BreadcrumbItem ()](#apidoc.element.react-bootstrap.BreadcrumbItem)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Button ()](#apidoc.element.react-bootstrap.Button)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>ButtonGroup ()](#apidoc.element.react-bootstrap.ButtonGroup)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>ButtonToolbar ()](#apidoc.element.react-bootstrap.ButtonToolbar)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Carousel (props, context)](#apidoc.element.react-bootstrap.Carousel)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Carousel.Caption ()](#apidoc.element.react-bootstrap.Carousel.Caption)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>CarouselItem (props, context)](#apidoc.element.react-bootstrap.CarouselItem)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Checkbox ()](#apidoc.element.react-bootstrap.Checkbox)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Clearfix ()](#apidoc.element.react-bootstrap.Clearfix)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Col ()](#apidoc.element.react-bootstrap.Col)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Collapse (props, context)](#apidoc.element.react-bootstrap.Collapse)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>ControlLabel ()](#apidoc.element.react-bootstrap.ControlLabel)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Dropdown (props, context, updater)](#apidoc.element.react-bootstrap.Dropdown)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Dropdown.ControlledComponent (props, context)](#apidoc.element.react-bootstrap.Dropdown.ControlledComponent)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Dropdown.Menu (props)](#apidoc.element.react-bootstrap.Dropdown.Menu)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Dropdown.Toggle ()](#apidoc.element.react-bootstrap.Dropdown.Toggle)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>DropdownButton ()](#apidoc.element.react-bootstrap.DropdownButton)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Fade ()](#apidoc.element.react-bootstrap.Fade)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Form ()](#apidoc.element.react-bootstrap.Form)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>FormControl ()](#apidoc.element.react-bootstrap.FormControl)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>FormControl.Feedback ()](#apidoc.element.react-bootstrap.FormControl.Feedback)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>FormControl.Static ()](#apidoc.element.react-bootstrap.FormControl.Static)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>FormGroup ()](#apidoc.element.react-bootstrap.FormGroup)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Glyphicon ()](#apidoc.element.react-bootstrap.Glyphicon)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Grid ()](#apidoc.element.react-bootstrap.Grid)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>HelpBlock ()](#apidoc.element.react-bootstrap.HelpBlock)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Image ()](#apidoc.element.react-bootstrap.Image)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>InputGroup ()](#apidoc.element.react-bootstrap.InputGroup)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>InputGroup.Addon ()](#apidoc.element.react-bootstrap.InputGroup.Addon)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>InputGroup.Button ()](#apidoc.element.react-bootstrap.InputGroup.Button)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Jumbotron ()](#apidoc.element.react-bootstrap.Jumbotron)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Label ()](#apidoc.element.react-bootstrap.Label)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>ListGroup ()](#apidoc.element.react-bootstrap.ListGroup)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>ListGroupItem ()](#apidoc.element.react-bootstrap.ListGroupItem)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Media ()](#apidoc.element.react-bootstrap.Media)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Media.Body ()](#apidoc.element.react-bootstrap.Media.Body)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Media.Heading ()](#apidoc.element.react-bootstrap.Media.Heading)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Media.Left ()](#apidoc.element.react-bootstrap.Media.Left)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Media.List ()](#apidoc.element.react-bootstrap.Media.List)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Media.ListItem ()](#apidoc.element.react-bootstrap.Media.ListItem)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Media.Right ()](#apidoc.element.react-bootstrap.Media.Right)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>MenuItem (props, context)](#apidoc.element.react-bootstrap.MenuItem)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Modal (props, context)](#apidoc.element.react-bootstrap.Modal)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Modal.Dialog ()](#apidoc.element.react-bootstrap.Modal.Dialog)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>ModalBody ()](#apidoc.element.react-bootstrap.ModalBody)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>ModalFooter ()](#apidoc.element.react-bootstrap.ModalFooter)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>ModalHeader ()](#apidoc.element.react-bootstrap.ModalHeader)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>ModalTitle ()](#apidoc.element.react-bootstrap.ModalTitle)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Nav ()](#apidoc.element.react-bootstrap.Nav)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>NavDropdown ()](#apidoc.element.react-bootstrap.NavDropdown)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>NavItem (props, context)](#apidoc.element.react-bootstrap.NavItem)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Navbar (props, context, updater)](#apidoc.element.react-bootstrap.Navbar)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Navbar.Collapse ()](#apidoc.element.react-bootstrap.Navbar.Collapse)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Navbar.ControlledComponent (props, context)](#apidoc.element.react-bootstrap.Navbar.ControlledComponent)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Navbar.Header ()](#apidoc.element.react-bootstrap.Navbar.Header)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Navbar.Toggle ()](#apidoc.element.react-bootstrap.Navbar.Toggle)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>NavbarBrand ()](#apidoc.element.react-bootstrap.NavbarBrand)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Overlay ()](#apidoc.element.react-bootstrap.Overlay)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>OverlayTrigger (props, context)](#apidoc.element.react-bootstrap.OverlayTrigger)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>PageHeader ()](#apidoc.element.react-bootstrap.PageHeader)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>PageItem ()](#apidoc.element.react-bootstrap.PageItem)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Pager ()](#apidoc.element.react-bootstrap.Pager)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Pager.Item (props, context)](#apidoc.element.react-bootstrap.Pager.Item)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Pagination ()](#apidoc.element.react-bootstrap.Pagination)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>PaginationButton (props, context)](#apidoc.element.react-bootstrap.PaginationButton)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Panel (props, context)](#apidoc.element.react-bootstrap.Panel)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>PanelGroup (props, context)](#apidoc.element.react-bootstrap.PanelGroup)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Popover ()](#apidoc.element.react-bootstrap.Popover)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>ProgressBar ()](#apidoc.element.react-bootstrap.ProgressBar)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Radio ()](#apidoc.element.react-bootstrap.Radio)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>ResponsiveEmbed ()](#apidoc.element.react-bootstrap.ResponsiveEmbed)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Row ()](#apidoc.element.react-bootstrap.Row)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>SafeAnchor (props, context)](#apidoc.element.react-bootstrap.SafeAnchor)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>SplitButton ()](#apidoc.element.react-bootstrap.SplitButton)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>SplitButton.Toggle ()](#apidoc.element.react-bootstrap.SplitButton.Toggle)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Tab ()](#apidoc.element.react-bootstrap.Tab)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>TabContainer (props, context, updater)](#apidoc.element.react-bootstrap.TabContainer)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>TabContainer.ControlledComponent ()](#apidoc.element.react-bootstrap.TabContainer.ControlledComponent)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>TabContent (props, context)](#apidoc.element.react-bootstrap.TabContent)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>TabPane (props, context)](#apidoc.element.react-bootstrap.TabPane)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Table ()](#apidoc.element.react-bootstrap.Table)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Tabs (props, context, updater)](#apidoc.element.react-bootstrap.Tabs)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Tabs.ControlledComponent ()](#apidoc.element.react-bootstrap.Tabs.ControlledComponent)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Thumbnail ()](#apidoc.element.react-bootstrap.Thumbnail)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Tooltip ()](#apidoc.element.react-bootstrap.Tooltip)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Well ()](#apidoc.element.react-bootstrap.Well)
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Accordion.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Alert.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Alert.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Badge.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Badge.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Breadcrumb.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Breadcrumb.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>BreadcrumbItem.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>BreadcrumbItem.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Button.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Button.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>ButtonGroup.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>ButtonGroup.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>ButtonToolbar.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>ButtonToolbar.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Carousel.Caption.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Carousel.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Carousel.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>CarouselItem.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>CarouselItem.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Checkbox.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Checkbox.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Clearfix.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Clearfix.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Col.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Col.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Collapse.defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Collapse.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Collapse.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>ControlLabel.contextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>ControlLabel.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>ControlLabel.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Dropdown.ControlledComponent.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Dropdown.Menu.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Dropdown.Toggle.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Dropdown.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Dropdown.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Dropdown.prototype.__reactAutoBindPairs
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>DropdownButton.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>DropdownButton.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Fade.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Fade.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Form.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Form.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>FormControl.Feedback.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>FormControl.Static.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>FormControl.contextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>FormControl.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>FormControl.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>FormGroup.childContextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>FormGroup.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>FormGroup.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Glyphicon.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Glyphicon.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Grid.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Grid.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>HelpBlock.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>HelpBlock.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Image.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Image.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>InputGroup.Addon.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>InputGroup.Button.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>InputGroup.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>InputGroup.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Jumbotron.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Jumbotron.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Label.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Label.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>ListGroup.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>ListGroup.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>ListGroupItem.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>ListGroupItem.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Media.Body.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Media.Heading.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Media.Left.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Media.List.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Media.ListItem.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Media.Right.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Media.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Media.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>MenuItem.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>MenuItem.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Modal.Dialog.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Modal.childContextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Modal.defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Modal.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Modal.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>ModalBody.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>ModalBody.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>ModalFooter.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>ModalFooter.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>ModalHeader.contextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>ModalHeader.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>ModalHeader.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>ModalTitle.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>ModalTitle.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Nav.contextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Nav.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Nav.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>NavDropdown.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>NavDropdown.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>NavItem.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>NavItem.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Navbar.Collapse.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Navbar.ControlledComponent.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Navbar.Header.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Navbar.Toggle.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Navbar.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Navbar.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Navbar.prototype.__reactAutoBindPairs
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>NavbarBrand.contextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>NavbarBrand.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Overlay.defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Overlay.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Overlay.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>OverlayTrigger.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>OverlayTrigger.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>PageHeader.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>PageHeader.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>PageItem.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Pager.Item.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Pager.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Pager.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Pagination.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Pagination.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>PaginationButton.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Panel.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Panel.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>PanelGroup.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>PanelGroup.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Popover.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Popover.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>ProgressBar.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>ProgressBar.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Radio.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Radio.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>ResponsiveEmbed.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>ResponsiveEmbed.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Row.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Row.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>SafeAnchor.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>SafeAnchor.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>SplitButton.Toggle.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>SplitButton.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>SplitButton.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Tab.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Tab.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>TabContainer.ControlledComponent.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>TabContainer.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>TabContainer.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>TabContainer.prototype.__reactAutoBindPairs
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>TabContent.childContextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>TabContent.contextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>TabContent.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>TabContent.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>TabPane.childContextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>TabPane.contextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>TabPane.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>TabPane.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Table.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Table.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Tabs.ControlledComponent.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Tabs.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Tabs.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Tabs.prototype.__reactAutoBindPairs
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Thumbnail.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Thumbnail.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Tooltip.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Tooltip.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Well.propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>Well.prototype
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>utils
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>utils.ValidComponentChildren
1.  object <span class="apidocSignatureSpan">react-bootstrap.</span>utils.bootstrapUtils

#### [module react-bootstrap.Accordion](#apidoc.module.react-bootstrap.Accordion)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Accordion ()](#apidoc.element.react-bootstrap.Accordion.Accordion)

#### [module react-bootstrap.Accordion.prototype](#apidoc.module.react-bootstrap.Accordion.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Accordion.prototype.</span>render ()](#apidoc.element.react-bootstrap.Accordion.prototype.render)

#### [module react-bootstrap.Alert](#apidoc.module.react-bootstrap.Alert)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Alert ()](#apidoc.element.react-bootstrap.Alert.Alert)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Alert.</span>STYLES
1.  object <span class="apidocSignatureSpan">react-bootstrap.Alert.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Alert.</span>propTypes

#### [module react-bootstrap.Alert.propTypes](#apidoc.module.react-bootstrap.Alert.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Alert.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Alert.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Alert.propTypes.</span>bsStyle ()](#apidoc.element.react-bootstrap.Alert.propTypes.bsStyle)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Alert.propTypes.</span>closeLabel ()](#apidoc.element.react-bootstrap.Alert.propTypes.closeLabel)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Alert.propTypes.</span>onDismiss ()](#apidoc.element.react-bootstrap.Alert.propTypes.onDismiss)

#### [module react-bootstrap.Alert.prototype](#apidoc.module.react-bootstrap.Alert.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Alert.prototype.</span>render ()](#apidoc.element.react-bootstrap.Alert.prototype.render)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Alert.prototype.</span>renderDismissButton (onDismiss)](#apidoc.element.react-bootstrap.Alert.prototype.renderDismissButton)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Alert.prototype.</span>renderSrOnlyDismissButton (onDismiss, closeLabel)](#apidoc.element.react-bootstrap.Alert.prototype.renderSrOnlyDismissButton)

#### [module react-bootstrap.Badge](#apidoc.module.react-bootstrap.Badge)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Badge ()](#apidoc.element.react-bootstrap.Badge.Badge)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Badge.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Badge.</span>propTypes

#### [module react-bootstrap.Badge.propTypes](#apidoc.module.react-bootstrap.Badge.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Badge.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Badge.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Badge.propTypes.</span>pullRight ()](#apidoc.element.react-bootstrap.Badge.propTypes.pullRight)

#### [module react-bootstrap.Badge.prototype](#apidoc.module.react-bootstrap.Badge.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Badge.prototype.</span>hasContent (children)](#apidoc.element.react-bootstrap.Badge.prototype.hasContent)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Badge.prototype.</span>render ()](#apidoc.element.react-bootstrap.Badge.prototype.render)

#### [module react-bootstrap.Breadcrumb](#apidoc.module.react-bootstrap.Breadcrumb)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Breadcrumb ()](#apidoc.element.react-bootstrap.Breadcrumb.Breadcrumb)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Breadcrumb.</span>Item ()](#apidoc.element.react-bootstrap.Breadcrumb.Item)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Breadcrumb.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Breadcrumb.</span>propTypes

#### [module react-bootstrap.Breadcrumb.propTypes](#apidoc.module.react-bootstrap.Breadcrumb.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Breadcrumb.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Breadcrumb.propTypes.bsClass)

#### [module react-bootstrap.Breadcrumb.prototype](#apidoc.module.react-bootstrap.Breadcrumb.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Breadcrumb.prototype.</span>render ()](#apidoc.element.react-bootstrap.Breadcrumb.prototype.render)

#### [module react-bootstrap.BreadcrumbItem](#apidoc.module.react-bootstrap.BreadcrumbItem)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>BreadcrumbItem ()](#apidoc.element.react-bootstrap.BreadcrumbItem.BreadcrumbItem)
1.  object <span class="apidocSignatureSpan">react-bootstrap.BreadcrumbItem.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.BreadcrumbItem.</span>propTypes

#### [module react-bootstrap.BreadcrumbItem.propTypes](#apidoc.module.react-bootstrap.BreadcrumbItem.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.BreadcrumbItem.propTypes.</span>active ()](#apidoc.element.react-bootstrap.BreadcrumbItem.propTypes.active)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.BreadcrumbItem.propTypes.</span>href ()](#apidoc.element.react-bootstrap.BreadcrumbItem.propTypes.href)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.BreadcrumbItem.propTypes.</span>target ()](#apidoc.element.react-bootstrap.BreadcrumbItem.propTypes.target)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.BreadcrumbItem.propTypes.</span>title ()](#apidoc.element.react-bootstrap.BreadcrumbItem.propTypes.title)

#### [module react-bootstrap.BreadcrumbItem.prototype](#apidoc.module.react-bootstrap.BreadcrumbItem.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.BreadcrumbItem.prototype.</span>render ()](#apidoc.element.react-bootstrap.BreadcrumbItem.prototype.render)

#### [module react-bootstrap.Button](#apidoc.module.react-bootstrap.Button)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Button ()](#apidoc.element.react-bootstrap.Button.Button)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Button.</span>SIZES
1.  object <span class="apidocSignatureSpan">react-bootstrap.Button.</span>STYLES
1.  object <span class="apidocSignatureSpan">react-bootstrap.Button.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Button.</span>propTypes

#### [module react-bootstrap.Button.propTypes](#apidoc.module.react-bootstrap.Button.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Button.propTypes.</span>active ()](#apidoc.element.react-bootstrap.Button.propTypes.active)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Button.propTypes.</span>block ()](#apidoc.element.react-bootstrap.Button.propTypes.block)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Button.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Button.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Button.propTypes.</span>bsSize ()](#apidoc.element.react-bootstrap.Button.propTypes.bsSize)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Button.propTypes.</span>bsStyle ()](#apidoc.element.react-bootstrap.Button.propTypes.bsStyle)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Button.propTypes.</span>componentClass ()](#apidoc.element.react-bootstrap.Button.propTypes.componentClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Button.propTypes.</span>disabled ()](#apidoc.element.react-bootstrap.Button.propTypes.disabled)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Button.propTypes.</span>href ()](#apidoc.element.react-bootstrap.Button.propTypes.href)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Button.propTypes.</span>onClick ()](#apidoc.element.react-bootstrap.Button.propTypes.onClick)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Button.propTypes.</span>type ()](#apidoc.element.react-bootstrap.Button.propTypes.type)

#### [module react-bootstrap.Button.prototype](#apidoc.module.react-bootstrap.Button.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Button.prototype.</span>render ()](#apidoc.element.react-bootstrap.Button.prototype.render)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Button.prototype.</span>renderAnchor (elementProps, className)](#apidoc.element.react-bootstrap.Button.prototype.renderAnchor)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Button.prototype.</span>renderButton (_ref, className)](#apidoc.element.react-bootstrap.Button.prototype.renderButton)

#### [module react-bootstrap.ButtonGroup](#apidoc.module.react-bootstrap.ButtonGroup)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>ButtonGroup ()](#apidoc.element.react-bootstrap.ButtonGroup.ButtonGroup)
1.  object <span class="apidocSignatureSpan">react-bootstrap.ButtonGroup.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.ButtonGroup.</span>propTypes

#### [module react-bootstrap.ButtonGroup.propTypes](#apidoc.module.react-bootstrap.ButtonGroup.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ButtonGroup.propTypes.</span>block ()](#apidoc.element.react-bootstrap.ButtonGroup.propTypes.block)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ButtonGroup.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.ButtonGroup.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ButtonGroup.propTypes.</span>justified ()](#apidoc.element.react-bootstrap.ButtonGroup.propTypes.justified)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ButtonGroup.propTypes.</span>vertical ()](#apidoc.element.react-bootstrap.ButtonGroup.propTypes.vertical)

#### [module react-bootstrap.ButtonGroup.prototype](#apidoc.module.react-bootstrap.ButtonGroup.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ButtonGroup.prototype.</span>render ()](#apidoc.element.react-bootstrap.ButtonGroup.prototype.render)

#### [module react-bootstrap.ButtonToolbar](#apidoc.module.react-bootstrap.ButtonToolbar)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>ButtonToolbar ()](#apidoc.element.react-bootstrap.ButtonToolbar.ButtonToolbar)
1.  object <span class="apidocSignatureSpan">react-bootstrap.ButtonToolbar.</span>SIZES
1.  object <span class="apidocSignatureSpan">react-bootstrap.ButtonToolbar.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.ButtonToolbar.</span>propTypes

#### [module react-bootstrap.ButtonToolbar.propTypes](#apidoc.module.react-bootstrap.ButtonToolbar.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ButtonToolbar.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.ButtonToolbar.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ButtonToolbar.propTypes.</span>bsSize ()](#apidoc.element.react-bootstrap.ButtonToolbar.propTypes.bsSize)

#### [module react-bootstrap.ButtonToolbar.prototype](#apidoc.module.react-bootstrap.ButtonToolbar.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ButtonToolbar.prototype.</span>render ()](#apidoc.element.react-bootstrap.ButtonToolbar.prototype.render)

#### [module react-bootstrap.Carousel](#apidoc.module.react-bootstrap.Carousel)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Carousel (props, context)](#apidoc.element.react-bootstrap.Carousel.Carousel)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.</span>Caption ()](#apidoc.element.react-bootstrap.Carousel.Caption)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.</span>Item (props, context)](#apidoc.element.react-bootstrap.Carousel.Item)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Carousel.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Carousel.</span>propTypes

#### [module react-bootstrap.Carousel.Caption](#apidoc.module.react-bootstrap.Carousel.Caption)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.</span>Caption ()](#apidoc.element.react-bootstrap.Carousel.Caption.Caption)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Carousel.Caption.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Carousel.Caption.</span>propTypes

#### [module react-bootstrap.Carousel.Caption.prototype](#apidoc.module.react-bootstrap.Carousel.Caption.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.Caption.prototype.</span>render ()](#apidoc.element.react-bootstrap.Carousel.Caption.prototype.render)

#### [module react-bootstrap.Carousel.propTypes](#apidoc.module.react-bootstrap.Carousel.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>activeIndex ()](#apidoc.element.react-bootstrap.Carousel.propTypes.activeIndex)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Carousel.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>controls ()](#apidoc.element.react-bootstrap.Carousel.propTypes.controls)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>defaultActiveIndex ()](#apidoc.element.react-bootstrap.Carousel.propTypes.defaultActiveIndex)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>direction ()](#apidoc.element.react-bootstrap.Carousel.propTypes.direction)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>indicators ()](#apidoc.element.react-bootstrap.Carousel.propTypes.indicators)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>interval ()](#apidoc.element.react-bootstrap.Carousel.propTypes.interval)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>nextIcon ()](#apidoc.element.react-bootstrap.Carousel.propTypes.nextIcon)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>nextLabel ()](#apidoc.element.react-bootstrap.Carousel.propTypes.nextLabel)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>onSelect ()](#apidoc.element.react-bootstrap.Carousel.propTypes.onSelect)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>onSlideEnd ()](#apidoc.element.react-bootstrap.Carousel.propTypes.onSlideEnd)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>pauseOnHover ()](#apidoc.element.react-bootstrap.Carousel.propTypes.pauseOnHover)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>prevIcon ()](#apidoc.element.react-bootstrap.Carousel.propTypes.prevIcon)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>prevLabel ()](#apidoc.element.react-bootstrap.Carousel.propTypes.prevLabel)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>slide ()](#apidoc.element.react-bootstrap.Carousel.propTypes.slide)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>wrap ()](#apidoc.element.react-bootstrap.Carousel.propTypes.wrap)

#### [module react-bootstrap.Carousel.prototype](#apidoc.module.react-bootstrap.Carousel.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>componentDidMount ()](#apidoc.element.react-bootstrap.Carousel.prototype.componentDidMount)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.react-bootstrap.Carousel.prototype.componentWillReceiveProps)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>componentWillUnmount ()](#apidoc.element.react-bootstrap.Carousel.prototype.componentWillUnmount)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>getActiveIndex ()](#apidoc.element.react-bootstrap.Carousel.prototype.getActiveIndex)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>getDirection (prevIndex, index)](#apidoc.element.react-bootstrap.Carousel.prototype.getDirection)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>handleItemAnimateOutEnd ()](#apidoc.element.react-bootstrap.Carousel.prototype.handleItemAnimateOutEnd)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>handleMouseOut ()](#apidoc.element.react-bootstrap.Carousel.prototype.handleMouseOut)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>handleMouseOver ()](#apidoc.element.react-bootstrap.Carousel.prototype.handleMouseOver)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>handleNext (e)](#apidoc.element.react-bootstrap.Carousel.prototype.handleNext)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>handlePrev (e)](#apidoc.element.react-bootstrap.Carousel.prototype.handlePrev)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>pause ()](#apidoc.element.react-bootstrap.Carousel.prototype.pause)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>play ()](#apidoc.element.react-bootstrap.Carousel.prototype.play)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>render ()](#apidoc.element.react-bootstrap.Carousel.prototype.render)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>renderControls (properties)](#apidoc.element.react-bootstrap.Carousel.prototype.renderControls)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>renderIndicators (children, activeIndex, bsProps)](#apidoc.element.react-bootstrap.Carousel.prototype.renderIndicators)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>select (index, e, direction)](#apidoc.element.react-bootstrap.Carousel.prototype.select)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>waitForNext ()](#apidoc.element.react-bootstrap.Carousel.prototype.waitForNext)

#### [module react-bootstrap.CarouselItem](#apidoc.module.react-bootstrap.CarouselItem)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>CarouselItem (props, context)](#apidoc.element.react-bootstrap.CarouselItem.CarouselItem)
1.  object <span class="apidocSignatureSpan">react-bootstrap.CarouselItem.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.CarouselItem.</span>propTypes

#### [module react-bootstrap.CarouselItem.propTypes](#apidoc.module.react-bootstrap.CarouselItem.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.CarouselItem.propTypes.</span>active ()](#apidoc.element.react-bootstrap.CarouselItem.propTypes.active)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.CarouselItem.propTypes.</span>animateIn ()](#apidoc.element.react-bootstrap.CarouselItem.propTypes.animateIn)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.CarouselItem.propTypes.</span>animateOut ()](#apidoc.element.react-bootstrap.CarouselItem.propTypes.animateOut)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.CarouselItem.propTypes.</span>direction ()](#apidoc.element.react-bootstrap.CarouselItem.propTypes.direction)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.CarouselItem.propTypes.</span>index ()](#apidoc.element.react-bootstrap.CarouselItem.propTypes.index)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.CarouselItem.propTypes.</span>onAnimateOutEnd ()](#apidoc.element.react-bootstrap.CarouselItem.propTypes.onAnimateOutEnd)

#### [module react-bootstrap.CarouselItem.prototype](#apidoc.module.react-bootstrap.CarouselItem.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.CarouselItem.prototype.</span>componentDidUpdate (prevProps)](#apidoc.element.react-bootstrap.CarouselItem.prototype.componentDidUpdate)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.CarouselItem.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.react-bootstrap.CarouselItem.prototype.componentWillReceiveProps)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.CarouselItem.prototype.</span>componentWillUnmount ()](#apidoc.element.react-bootstrap.CarouselItem.prototype.componentWillUnmount)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.CarouselItem.prototype.</span>handleAnimateOutEnd ()](#apidoc.element.react-bootstrap.CarouselItem.prototype.handleAnimateOutEnd)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.CarouselItem.prototype.</span>render ()](#apidoc.element.react-bootstrap.CarouselItem.prototype.render)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.CarouselItem.prototype.</span>startAnimation ()](#apidoc.element.react-bootstrap.CarouselItem.prototype.startAnimation)

#### [module react-bootstrap.Checkbox](#apidoc.module.react-bootstrap.Checkbox)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Checkbox ()](#apidoc.element.react-bootstrap.Checkbox.Checkbox)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Checkbox.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Checkbox.</span>propTypes

#### [module react-bootstrap.Checkbox.propTypes](#apidoc.module.react-bootstrap.Checkbox.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Checkbox.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Checkbox.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Checkbox.propTypes.</span>disabled ()](#apidoc.element.react-bootstrap.Checkbox.propTypes.disabled)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Checkbox.propTypes.</span>inline ()](#apidoc.element.react-bootstrap.Checkbox.propTypes.inline)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Checkbox.propTypes.</span>inputRef ()](#apidoc.element.react-bootstrap.Checkbox.propTypes.inputRef)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Checkbox.propTypes.</span>validationState ()](#apidoc.element.react-bootstrap.Checkbox.propTypes.validationState)

#### [module react-bootstrap.Checkbox.prototype](#apidoc.module.react-bootstrap.Checkbox.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Checkbox.prototype.</span>render ()](#apidoc.element.react-bootstrap.Checkbox.prototype.render)

#### [module react-bootstrap.Clearfix](#apidoc.module.react-bootstrap.Clearfix)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Clearfix ()](#apidoc.element.react-bootstrap.Clearfix.Clearfix)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Clearfix.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Clearfix.</span>propTypes

#### [module react-bootstrap.Clearfix.propTypes](#apidoc.module.react-bootstrap.Clearfix.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Clearfix.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Clearfix.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Clearfix.propTypes.</span>componentClass ()](#apidoc.element.react-bootstrap.Clearfix.propTypes.componentClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Clearfix.propTypes.</span>visibleLgBlock ()](#apidoc.element.react-bootstrap.Clearfix.propTypes.visibleLgBlock)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Clearfix.propTypes.</span>visibleMdBlock ()](#apidoc.element.react-bootstrap.Clearfix.propTypes.visibleMdBlock)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Clearfix.propTypes.</span>visibleSmBlock ()](#apidoc.element.react-bootstrap.Clearfix.propTypes.visibleSmBlock)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Clearfix.propTypes.</span>visibleXsBlock ()](#apidoc.element.react-bootstrap.Clearfix.propTypes.visibleXsBlock)

#### [module react-bootstrap.Clearfix.prototype](#apidoc.module.react-bootstrap.Clearfix.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Clearfix.prototype.</span>render ()](#apidoc.element.react-bootstrap.Clearfix.prototype.render)

#### [module react-bootstrap.Col](#apidoc.module.react-bootstrap.Col)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Col ()](#apidoc.element.react-bootstrap.Col.Col)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Col.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Col.</span>propTypes

#### [module react-bootstrap.Col.propTypes](#apidoc.module.react-bootstrap.Col.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Col.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>componentClass ()](#apidoc.element.react-bootstrap.Col.propTypes.componentClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>lg ()](#apidoc.element.react-bootstrap.Col.propTypes.lg)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>lgHidden ()](#apidoc.element.react-bootstrap.Col.propTypes.lgHidden)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>lgOffset ()](#apidoc.element.react-bootstrap.Col.propTypes.lgOffset)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>lgPull ()](#apidoc.element.react-bootstrap.Col.propTypes.lgPull)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>lgPush ()](#apidoc.element.react-bootstrap.Col.propTypes.lgPush)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>md ()](#apidoc.element.react-bootstrap.Col.propTypes.md)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>mdHidden ()](#apidoc.element.react-bootstrap.Col.propTypes.mdHidden)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>mdOffset ()](#apidoc.element.react-bootstrap.Col.propTypes.mdOffset)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>mdPull ()](#apidoc.element.react-bootstrap.Col.propTypes.mdPull)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>mdPush ()](#apidoc.element.react-bootstrap.Col.propTypes.mdPush)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>sm ()](#apidoc.element.react-bootstrap.Col.propTypes.sm)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>smHidden ()](#apidoc.element.react-bootstrap.Col.propTypes.smHidden)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>smOffset ()](#apidoc.element.react-bootstrap.Col.propTypes.smOffset)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>smPull ()](#apidoc.element.react-bootstrap.Col.propTypes.smPull)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>smPush ()](#apidoc.element.react-bootstrap.Col.propTypes.smPush)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>xs ()](#apidoc.element.react-bootstrap.Col.propTypes.xs)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>xsHidden ()](#apidoc.element.react-bootstrap.Col.propTypes.xsHidden)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>xsOffset ()](#apidoc.element.react-bootstrap.Col.propTypes.xsOffset)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>xsPull ()](#apidoc.element.react-bootstrap.Col.propTypes.xsPull)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>xsPush ()](#apidoc.element.react-bootstrap.Col.propTypes.xsPush)

#### [module react-bootstrap.Col.prototype](#apidoc.module.react-bootstrap.Col.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Col.prototype.</span>render ()](#apidoc.element.react-bootstrap.Col.prototype.render)

#### [module react-bootstrap.Collapse](#apidoc.module.react-bootstrap.Collapse)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Collapse (props, context)](#apidoc.element.react-bootstrap.Collapse.Collapse)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Collapse.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Collapse.</span>propTypes

#### [module react-bootstrap.Collapse.defaultProps](#apidoc.module.react-bootstrap.Collapse.defaultProps)
1.  boolean <span class="apidocSignatureSpan">react-bootstrap.Collapse.defaultProps.</span>in
1.  boolean <span class="apidocSignatureSpan">react-bootstrap.Collapse.defaultProps.</span>mountOnEnter
1.  boolean <span class="apidocSignatureSpan">react-bootstrap.Collapse.defaultProps.</span>transitionAppear
1.  boolean <span class="apidocSignatureSpan">react-bootstrap.Collapse.defaultProps.</span>unmountOnExit
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Collapse.defaultProps.</span>getDimensionValue (dimension, elem)](#apidoc.element.react-bootstrap.Collapse.defaultProps.getDimensionValue)
1.  number <span class="apidocSignatureSpan">react-bootstrap.Collapse.defaultProps.</span>timeout
1.  string <span class="apidocSignatureSpan">react-bootstrap.Collapse.defaultProps.</span>dimension

#### [module react-bootstrap.Collapse.propTypes](#apidoc.module.react-bootstrap.Collapse.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Collapse.propTypes.</span>dimension ()](#apidoc.element.react-bootstrap.Collapse.propTypes.dimension)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Collapse.propTypes.</span>getDimensionValue ()](#apidoc.element.react-bootstrap.Collapse.propTypes.getDimensionValue)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Collapse.propTypes.</span>in ()](#apidoc.element.react-bootstrap.Collapse.propTypes.in)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Collapse.propTypes.</span>mountOnEnter ()](#apidoc.element.react-bootstrap.Collapse.propTypes.mountOnEnter)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Collapse.propTypes.</span>onEnter ()](#apidoc.element.react-bootstrap.Collapse.propTypes.onEnter)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Collapse.propTypes.</span>onEntered ()](#apidoc.element.react-bootstrap.Collapse.propTypes.onEntered)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Collapse.propTypes.</span>onEntering ()](#apidoc.element.react-bootstrap.Collapse.propTypes.onEntering)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Collapse.propTypes.</span>onExit ()](#apidoc.element.react-bootstrap.Collapse.propTypes.onExit)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Collapse.propTypes.</span>onExited ()](#apidoc.element.react-bootstrap.Collapse.propTypes.onExited)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Collapse.propTypes.</span>onExiting ()](#apidoc.element.react-bootstrap.Collapse.propTypes.onExiting)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Collapse.propTypes.</span>role ()](#apidoc.element.react-bootstrap.Collapse.propTypes.role)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Collapse.propTypes.</span>timeout ()](#apidoc.element.react-bootstrap.Collapse.propTypes.timeout)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Collapse.propTypes.</span>transitionAppear ()](#apidoc.element.react-bootstrap.Collapse.propTypes.transitionAppear)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Collapse.propTypes.</span>unmountOnExit ()](#apidoc.element.react-bootstrap.Collapse.propTypes.unmountOnExit)

#### [module react-bootstrap.Collapse.prototype](#apidoc.module.react-bootstrap.Collapse.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Collapse.prototype.</span>_dimension ()](#apidoc.element.react-bootstrap.Collapse.prototype._dimension)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Collapse.prototype.</span>_getScrollDimensionValue (elem, dimension)](#apidoc.element.react-bootstrap.Collapse.prototype._getScrollDimensionValue)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Collapse.prototype.</span>handleEnter (elem)](#apidoc.element.react-bootstrap.Collapse.prototype.handleEnter)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Collapse.prototype.</span>handleEntered (elem)](#apidoc.element.react-bootstrap.Collapse.prototype.handleEntered)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Collapse.prototype.</span>handleEntering (elem)](#apidoc.element.react-bootstrap.Collapse.prototype.handleEntering)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Collapse.prototype.</span>handleExit (elem)](#apidoc.element.react-bootstrap.Collapse.prototype.handleExit)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Collapse.prototype.</span>handleExiting (elem)](#apidoc.element.react-bootstrap.Collapse.prototype.handleExiting)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Collapse.prototype.</span>render ()](#apidoc.element.react-bootstrap.Collapse.prototype.render)

#### [module react-bootstrap.ControlLabel](#apidoc.module.react-bootstrap.ControlLabel)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>ControlLabel ()](#apidoc.element.react-bootstrap.ControlLabel.ControlLabel)
1.  object <span class="apidocSignatureSpan">react-bootstrap.ControlLabel.</span>contextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.ControlLabel.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.ControlLabel.</span>propTypes

#### [module react-bootstrap.ControlLabel.contextTypes](#apidoc.module.react-bootstrap.ControlLabel.contextTypes)

#### [module react-bootstrap.ControlLabel.propTypes](#apidoc.module.react-bootstrap.ControlLabel.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ControlLabel.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.ControlLabel.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ControlLabel.propTypes.</span>htmlFor ()](#apidoc.element.react-bootstrap.ControlLabel.propTypes.htmlFor)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ControlLabel.propTypes.</span>srOnly ()](#apidoc.element.react-bootstrap.ControlLabel.propTypes.srOnly)

#### [module react-bootstrap.ControlLabel.prototype](#apidoc.module.react-bootstrap.ControlLabel.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ControlLabel.prototype.</span>render ()](#apidoc.element.react-bootstrap.ControlLabel.prototype.render)

#### [module react-bootstrap.Dropdown](#apidoc.module.react-bootstrap.Dropdown)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Dropdown (props, context, updater)](#apidoc.element.react-bootstrap.Dropdown.Dropdown)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.</span>ControlledComponent (props, context)](#apidoc.element.react-bootstrap.Dropdown.ControlledComponent)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.</span>Menu (props)](#apidoc.element.react-bootstrap.Dropdown.Menu)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.</span>Toggle ()](#apidoc.element.react-bootstrap.Dropdown.Toggle)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.</span>deferControlTo (newComponent)](#apidoc.element.react-bootstrap.Dropdown.deferControlTo)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Dropdown.</span>propTypes
1.  string <span class="apidocSignatureSpan">react-bootstrap.Dropdown.</span>displayName

#### [module react-bootstrap.Dropdown.ControlledComponent](#apidoc.module.react-bootstrap.Dropdown.ControlledComponent)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.</span>ControlledComponent (props, context)](#apidoc.element.react-bootstrap.Dropdown.ControlledComponent.ControlledComponent)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Dropdown.ControlledComponent.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Dropdown.ControlledComponent.</span>propTypes

#### [module react-bootstrap.Dropdown.ControlledComponent.prototype](#apidoc.module.react-bootstrap.Dropdown.ControlledComponent.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.ControlledComponent.prototype.</span>componentDidMount ()](#apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.componentDidMount)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.ControlledComponent.prototype.</span>componentDidUpdate (prevProps)](#apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.componentDidUpdate)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.ControlledComponent.prototype.</span>componentWillUpdate (nextProps)](#apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.componentWillUpdate)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.ControlledComponent.prototype.</span>focus ()](#apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.focus)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.ControlledComponent.prototype.</span>focusNextOnOpen ()](#apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.focusNextOnOpen)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.ControlledComponent.prototype.</span>handleClick (event)](#apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.handleClick)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.ControlledComponent.prototype.</span>handleClose (event, eventDetails)](#apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.handleClose)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.ControlledComponent.prototype.</span>handleKeyDown (event)](#apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.handleKeyDown)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.ControlledComponent.prototype.</span>render ()](#apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.render)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.ControlledComponent.prototype.</span>renderMenu (child, _ref)](#apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.renderMenu)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.ControlledComponent.prototype.</span>renderToggle (child, props)](#apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.renderToggle)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.ControlledComponent.prototype.</span>toggleOpen (event, eventDetails)](#apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.toggleOpen)

#### [module react-bootstrap.Dropdown.Menu](#apidoc.module.react-bootstrap.Dropdown.Menu)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.</span>Menu (props)](#apidoc.element.react-bootstrap.Dropdown.Menu.Menu)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Dropdown.Menu.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Dropdown.Menu.</span>propTypes

#### [module react-bootstrap.Dropdown.Menu.prototype](#apidoc.module.react-bootstrap.Dropdown.Menu.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.Menu.prototype.</span>focusNext ()](#apidoc.element.react-bootstrap.Dropdown.Menu.prototype.focusNext)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.Menu.prototype.</span>focusPrevious ()](#apidoc.element.react-bootstrap.Dropdown.Menu.prototype.focusPrevious)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.Menu.prototype.</span>getFocusableMenuItems ()](#apidoc.element.react-bootstrap.Dropdown.Menu.prototype.getFocusableMenuItems)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.Menu.prototype.</span>getItemsAndActiveIndex ()](#apidoc.element.react-bootstrap.Dropdown.Menu.prototype.getItemsAndActiveIndex)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.Menu.prototype.</span>handleKeyDown (event)](#apidoc.element.react-bootstrap.Dropdown.Menu.prototype.handleKeyDown)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.Menu.prototype.</span>handleRootClose (event)](#apidoc.element.react-bootstrap.Dropdown.Menu.prototype.handleRootClose)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.Menu.prototype.</span>render ()](#apidoc.element.react-bootstrap.Dropdown.Menu.prototype.render)

#### [module react-bootstrap.Dropdown.Toggle](#apidoc.module.react-bootstrap.Dropdown.Toggle)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.</span>Toggle ()](#apidoc.element.react-bootstrap.Dropdown.Toggle.Toggle)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Dropdown.Toggle.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Dropdown.Toggle.</span>propTypes

#### [module react-bootstrap.Dropdown.Toggle.prototype](#apidoc.module.react-bootstrap.Dropdown.Toggle.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.Toggle.prototype.</span>render ()](#apidoc.element.react-bootstrap.Dropdown.Toggle.prototype.render)

#### [module react-bootstrap.Dropdown.propTypes](#apidoc.module.react-bootstrap.Dropdown.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.propTypes.</span>open (props, propName)](#apidoc.element.react-bootstrap.Dropdown.propTypes.open)

#### [module react-bootstrap.Dropdown.prototype](#apidoc.module.react-bootstrap.Dropdown.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.prototype.</span>componentWillMount ()](#apidoc.element.react-bootstrap.Dropdown.prototype.componentWillMount)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.react-bootstrap.Dropdown.prototype.componentWillReceiveProps)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.prototype.</span>constructor (props, context, updater)](#apidoc.element.react-bootstrap.Dropdown.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.prototype.</span>getControlledInstance ()](#apidoc.element.react-bootstrap.Dropdown.prototype.getControlledInstance)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.prototype.</span>render ()](#apidoc.element.react-bootstrap.Dropdown.prototype.render)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.prototype.</span>shouldComponentUpdate ()](#apidoc.element.react-bootstrap.Dropdown.prototype.shouldComponentUpdate)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Dropdown.prototype.</span>__reactAutoBindPairs
1.  object <span class="apidocSignatureSpan">react-bootstrap.Dropdown.prototype.</span>childContextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.Dropdown.prototype.</span>componentDidMount
1.  object <span class="apidocSignatureSpan">react-bootstrap.Dropdown.prototype.</span>componentDidUpdate
1.  object <span class="apidocSignatureSpan">react-bootstrap.Dropdown.prototype.</span>componentWillUnmount
1.  object <span class="apidocSignatureSpan">react-bootstrap.Dropdown.prototype.</span>componentWillUpdate
1.  object <span class="apidocSignatureSpan">react-bootstrap.Dropdown.prototype.</span>contextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.Dropdown.prototype.</span>getChildContext
1.  object <span class="apidocSignatureSpan">react-bootstrap.Dropdown.prototype.</span>getDefaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Dropdown.prototype.</span>getInitialState
1.  object <span class="apidocSignatureSpan">react-bootstrap.Dropdown.prototype.</span>mixins
1.  object <span class="apidocSignatureSpan">react-bootstrap.Dropdown.prototype.</span>propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.Dropdown.prototype.</span>statics
1.  object <span class="apidocSignatureSpan">react-bootstrap.Dropdown.prototype.</span>updateComponent

#### [module react-bootstrap.Dropdown.prototype.__reactAutoBindPairs](#apidoc.module.react-bootstrap.Dropdown.prototype.__reactAutoBindPairs)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.prototype.__reactAutoBindPairs.</span>1 ()](#apidoc.element.react-bootstrap.Dropdown.prototype.__reactAutoBindPairs.1)
1.  string <span class="apidocSignatureSpan">react-bootstrap.Dropdown.prototype.__reactAutoBindPairs.</span>0

#### [module react-bootstrap.DropdownButton](#apidoc.module.react-bootstrap.DropdownButton)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>DropdownButton ()](#apidoc.element.react-bootstrap.DropdownButton.DropdownButton)
1.  object <span class="apidocSignatureSpan">react-bootstrap.DropdownButton.</span>propTypes

#### [module react-bootstrap.DropdownButton.propTypes](#apidoc.module.react-bootstrap.DropdownButton.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.DropdownButton.propTypes.</span>bsSize ()](#apidoc.element.react-bootstrap.DropdownButton.propTypes.bsSize)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.DropdownButton.propTypes.</span>bsStyle ()](#apidoc.element.react-bootstrap.DropdownButton.propTypes.bsStyle)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.DropdownButton.propTypes.</span>children ()](#apidoc.element.react-bootstrap.DropdownButton.propTypes.children)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.DropdownButton.propTypes.</span>noCaret ()](#apidoc.element.react-bootstrap.DropdownButton.propTypes.noCaret)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.DropdownButton.propTypes.</span>open (props, propName)](#apidoc.element.react-bootstrap.DropdownButton.propTypes.open)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.DropdownButton.propTypes.</span>title ()](#apidoc.element.react-bootstrap.DropdownButton.propTypes.title)

#### [module react-bootstrap.DropdownButton.prototype](#apidoc.module.react-bootstrap.DropdownButton.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.DropdownButton.prototype.</span>render ()](#apidoc.element.react-bootstrap.DropdownButton.prototype.render)

#### [module react-bootstrap.Fade](#apidoc.module.react-bootstrap.Fade)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Fade ()](#apidoc.element.react-bootstrap.Fade.Fade)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Fade.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Fade.</span>propTypes

#### [module react-bootstrap.Fade.propTypes](#apidoc.module.react-bootstrap.Fade.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Fade.propTypes.</span>in ()](#apidoc.element.react-bootstrap.Fade.propTypes.in)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Fade.propTypes.</span>mountOnEnter ()](#apidoc.element.react-bootstrap.Fade.propTypes.mountOnEnter)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Fade.propTypes.</span>onEnter ()](#apidoc.element.react-bootstrap.Fade.propTypes.onEnter)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Fade.propTypes.</span>onEntered ()](#apidoc.element.react-bootstrap.Fade.propTypes.onEntered)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Fade.propTypes.</span>onEntering ()](#apidoc.element.react-bootstrap.Fade.propTypes.onEntering)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Fade.propTypes.</span>onExit ()](#apidoc.element.react-bootstrap.Fade.propTypes.onExit)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Fade.propTypes.</span>onExited ()](#apidoc.element.react-bootstrap.Fade.propTypes.onExited)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Fade.propTypes.</span>onExiting ()](#apidoc.element.react-bootstrap.Fade.propTypes.onExiting)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Fade.propTypes.</span>timeout ()](#apidoc.element.react-bootstrap.Fade.propTypes.timeout)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Fade.propTypes.</span>transitionAppear ()](#apidoc.element.react-bootstrap.Fade.propTypes.transitionAppear)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Fade.propTypes.</span>unmountOnExit ()](#apidoc.element.react-bootstrap.Fade.propTypes.unmountOnExit)

#### [module react-bootstrap.Fade.prototype](#apidoc.module.react-bootstrap.Fade.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Fade.prototype.</span>render ()](#apidoc.element.react-bootstrap.Fade.prototype.render)

#### [module react-bootstrap.Form](#apidoc.module.react-bootstrap.Form)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Form ()](#apidoc.element.react-bootstrap.Form.Form)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Form.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Form.</span>propTypes

#### [module react-bootstrap.Form.propTypes](#apidoc.module.react-bootstrap.Form.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Form.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Form.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Form.propTypes.</span>componentClass ()](#apidoc.element.react-bootstrap.Form.propTypes.componentClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Form.propTypes.</span>horizontal ()](#apidoc.element.react-bootstrap.Form.propTypes.horizontal)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Form.propTypes.</span>inline ()](#apidoc.element.react-bootstrap.Form.propTypes.inline)

#### [module react-bootstrap.Form.prototype](#apidoc.module.react-bootstrap.Form.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Form.prototype.</span>render ()](#apidoc.element.react-bootstrap.Form.prototype.render)

#### [module react-bootstrap.FormControl](#apidoc.module.react-bootstrap.FormControl)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>FormControl ()](#apidoc.element.react-bootstrap.FormControl.FormControl)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.FormControl.</span>Feedback ()](#apidoc.element.react-bootstrap.FormControl.Feedback)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.FormControl.</span>Static ()](#apidoc.element.react-bootstrap.FormControl.Static)
1.  object <span class="apidocSignatureSpan">react-bootstrap.FormControl.</span>SIZES
1.  object <span class="apidocSignatureSpan">react-bootstrap.FormControl.</span>contextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.FormControl.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.FormControl.</span>propTypes

#### [module react-bootstrap.FormControl.Feedback](#apidoc.module.react-bootstrap.FormControl.Feedback)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.FormControl.</span>Feedback ()](#apidoc.element.react-bootstrap.FormControl.Feedback.Feedback)
1.  object <span class="apidocSignatureSpan">react-bootstrap.FormControl.Feedback.</span>contextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.FormControl.Feedback.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.FormControl.Feedback.</span>propTypes

#### [module react-bootstrap.FormControl.Feedback.prototype](#apidoc.module.react-bootstrap.FormControl.Feedback.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.FormControl.Feedback.prototype.</span>getGlyph (validationState)](#apidoc.element.react-bootstrap.FormControl.Feedback.prototype.getGlyph)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.FormControl.Feedback.prototype.</span>render ()](#apidoc.element.react-bootstrap.FormControl.Feedback.prototype.render)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.FormControl.Feedback.prototype.</span>renderDefaultFeedback (formGroup, className, classes, elementProps)](#apidoc.element.react-bootstrap.FormControl.Feedback.prototype.renderDefaultFeedback)

#### [module react-bootstrap.FormControl.Static](#apidoc.module.react-bootstrap.FormControl.Static)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.FormControl.</span>Static ()](#apidoc.element.react-bootstrap.FormControl.Static.Static)
1.  object <span class="apidocSignatureSpan">react-bootstrap.FormControl.Static.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.FormControl.Static.</span>propTypes

#### [module react-bootstrap.FormControl.Static.prototype](#apidoc.module.react-bootstrap.FormControl.Static.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.FormControl.Static.prototype.</span>render ()](#apidoc.element.react-bootstrap.FormControl.Static.prototype.render)

#### [module react-bootstrap.FormControl.contextTypes](#apidoc.module.react-bootstrap.FormControl.contextTypes)

#### [module react-bootstrap.FormControl.propTypes](#apidoc.module.react-bootstrap.FormControl.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.FormControl.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.FormControl.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.FormControl.propTypes.</span>bsSize ()](#apidoc.element.react-bootstrap.FormControl.propTypes.bsSize)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.FormControl.propTypes.</span>componentClass ()](#apidoc.element.react-bootstrap.FormControl.propTypes.componentClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.FormControl.propTypes.</span>id ()](#apidoc.element.react-bootstrap.FormControl.propTypes.id)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.FormControl.propTypes.</span>inputRef ()](#apidoc.element.react-bootstrap.FormControl.propTypes.inputRef)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.FormControl.propTypes.</span>type ()](#apidoc.element.react-bootstrap.FormControl.propTypes.type)

#### [module react-bootstrap.FormControl.prototype](#apidoc.module.react-bootstrap.FormControl.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.FormControl.prototype.</span>render ()](#apidoc.element.react-bootstrap.FormControl.prototype.render)

#### [module react-bootstrap.FormGroup](#apidoc.module.react-bootstrap.FormGroup)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>FormGroup ()](#apidoc.element.react-bootstrap.FormGroup.FormGroup)
1.  object <span class="apidocSignatureSpan">react-bootstrap.FormGroup.</span>SIZES
1.  object <span class="apidocSignatureSpan">react-bootstrap.FormGroup.</span>childContextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.FormGroup.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.FormGroup.</span>propTypes

#### [module react-bootstrap.FormGroup.childContextTypes](#apidoc.module.react-bootstrap.FormGroup.childContextTypes)

#### [module react-bootstrap.FormGroup.propTypes](#apidoc.module.react-bootstrap.FormGroup.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.FormGroup.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.FormGroup.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.FormGroup.propTypes.</span>bsSize ()](#apidoc.element.react-bootstrap.FormGroup.propTypes.bsSize)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.FormGroup.propTypes.</span>controlId ()](#apidoc.element.react-bootstrap.FormGroup.propTypes.controlId)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.FormGroup.propTypes.</span>validationState ()](#apidoc.element.react-bootstrap.FormGroup.propTypes.validationState)

#### [module react-bootstrap.FormGroup.prototype](#apidoc.module.react-bootstrap.FormGroup.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.FormGroup.prototype.</span>getChildContext ()](#apidoc.element.react-bootstrap.FormGroup.prototype.getChildContext)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.FormGroup.prototype.</span>hasFeedback (children)](#apidoc.element.react-bootstrap.FormGroup.prototype.hasFeedback)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.FormGroup.prototype.</span>render ()](#apidoc.element.react-bootstrap.FormGroup.prototype.render)

#### [module react-bootstrap.Glyphicon](#apidoc.module.react-bootstrap.Glyphicon)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Glyphicon ()](#apidoc.element.react-bootstrap.Glyphicon.Glyphicon)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Glyphicon.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Glyphicon.</span>propTypes

#### [module react-bootstrap.Glyphicon.propTypes](#apidoc.module.react-bootstrap.Glyphicon.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Glyphicon.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Glyphicon.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Glyphicon.propTypes.</span>glyph ()](#apidoc.element.react-bootstrap.Glyphicon.propTypes.glyph)

#### [module react-bootstrap.Glyphicon.prototype](#apidoc.module.react-bootstrap.Glyphicon.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Glyphicon.prototype.</span>render ()](#apidoc.element.react-bootstrap.Glyphicon.prototype.render)

#### [module react-bootstrap.Grid](#apidoc.module.react-bootstrap.Grid)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Grid ()](#apidoc.element.react-bootstrap.Grid.Grid)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Grid.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Grid.</span>propTypes

#### [module react-bootstrap.Grid.propTypes](#apidoc.module.react-bootstrap.Grid.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Grid.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Grid.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Grid.propTypes.</span>componentClass ()](#apidoc.element.react-bootstrap.Grid.propTypes.componentClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Grid.propTypes.</span>fluid ()](#apidoc.element.react-bootstrap.Grid.propTypes.fluid)

#### [module react-bootstrap.Grid.prototype](#apidoc.module.react-bootstrap.Grid.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Grid.prototype.</span>render ()](#apidoc.element.react-bootstrap.Grid.prototype.render)

#### [module react-bootstrap.HelpBlock](#apidoc.module.react-bootstrap.HelpBlock)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>HelpBlock ()](#apidoc.element.react-bootstrap.HelpBlock.HelpBlock)
1.  object <span class="apidocSignatureSpan">react-bootstrap.HelpBlock.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.HelpBlock.</span>propTypes

#### [module react-bootstrap.HelpBlock.propTypes](#apidoc.module.react-bootstrap.HelpBlock.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.HelpBlock.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.HelpBlock.propTypes.bsClass)

#### [module react-bootstrap.HelpBlock.prototype](#apidoc.module.react-bootstrap.HelpBlock.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.HelpBlock.prototype.</span>render ()](#apidoc.element.react-bootstrap.HelpBlock.prototype.render)

#### [module react-bootstrap.Image](#apidoc.module.react-bootstrap.Image)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Image ()](#apidoc.element.react-bootstrap.Image.Image)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Image.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Image.</span>propTypes

#### [module react-bootstrap.Image.propTypes](#apidoc.module.react-bootstrap.Image.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Image.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Image.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Image.propTypes.</span>circle ()](#apidoc.element.react-bootstrap.Image.propTypes.circle)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Image.propTypes.</span>responsive ()](#apidoc.element.react-bootstrap.Image.propTypes.responsive)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Image.propTypes.</span>rounded ()](#apidoc.element.react-bootstrap.Image.propTypes.rounded)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Image.propTypes.</span>thumbnail ()](#apidoc.element.react-bootstrap.Image.propTypes.thumbnail)

#### [module react-bootstrap.Image.prototype](#apidoc.module.react-bootstrap.Image.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Image.prototype.</span>render ()](#apidoc.element.react-bootstrap.Image.prototype.render)

#### [module react-bootstrap.InputGroup](#apidoc.module.react-bootstrap.InputGroup)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>InputGroup ()](#apidoc.element.react-bootstrap.InputGroup.InputGroup)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.InputGroup.</span>Addon ()](#apidoc.element.react-bootstrap.InputGroup.Addon)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.InputGroup.</span>Button ()](#apidoc.element.react-bootstrap.InputGroup.Button)
1.  object <span class="apidocSignatureSpan">react-bootstrap.InputGroup.</span>SIZES
1.  object <span class="apidocSignatureSpan">react-bootstrap.InputGroup.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.InputGroup.</span>propTypes

#### [module react-bootstrap.InputGroup.Addon](#apidoc.module.react-bootstrap.InputGroup.Addon)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.InputGroup.</span>Addon ()](#apidoc.element.react-bootstrap.InputGroup.Addon.Addon)
1.  object <span class="apidocSignatureSpan">react-bootstrap.InputGroup.Addon.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.InputGroup.Addon.</span>propTypes

#### [module react-bootstrap.InputGroup.Addon.prototype](#apidoc.module.react-bootstrap.InputGroup.Addon.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.InputGroup.Addon.prototype.</span>render ()](#apidoc.element.react-bootstrap.InputGroup.Addon.prototype.render)

#### [module react-bootstrap.InputGroup.Button](#apidoc.module.react-bootstrap.InputGroup.Button)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.InputGroup.</span>Button ()](#apidoc.element.react-bootstrap.InputGroup.Button.Button)
1.  object <span class="apidocSignatureSpan">react-bootstrap.InputGroup.Button.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.InputGroup.Button.</span>propTypes

#### [module react-bootstrap.InputGroup.Button.prototype](#apidoc.module.react-bootstrap.InputGroup.Button.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.InputGroup.Button.prototype.</span>render ()](#apidoc.element.react-bootstrap.InputGroup.Button.prototype.render)

#### [module react-bootstrap.InputGroup.propTypes](#apidoc.module.react-bootstrap.InputGroup.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.InputGroup.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.InputGroup.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.InputGroup.propTypes.</span>bsSize ()](#apidoc.element.react-bootstrap.InputGroup.propTypes.bsSize)

#### [module react-bootstrap.InputGroup.prototype](#apidoc.module.react-bootstrap.InputGroup.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.InputGroup.prototype.</span>render ()](#apidoc.element.react-bootstrap.InputGroup.prototype.render)

#### [module react-bootstrap.Jumbotron](#apidoc.module.react-bootstrap.Jumbotron)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Jumbotron ()](#apidoc.element.react-bootstrap.Jumbotron.Jumbotron)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Jumbotron.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Jumbotron.</span>propTypes

#### [module react-bootstrap.Jumbotron.propTypes](#apidoc.module.react-bootstrap.Jumbotron.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Jumbotron.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Jumbotron.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Jumbotron.propTypes.</span>componentClass ()](#apidoc.element.react-bootstrap.Jumbotron.propTypes.componentClass)

#### [module react-bootstrap.Jumbotron.prototype](#apidoc.module.react-bootstrap.Jumbotron.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Jumbotron.prototype.</span>render ()](#apidoc.element.react-bootstrap.Jumbotron.prototype.render)

#### [module react-bootstrap.Label](#apidoc.module.react-bootstrap.Label)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Label ()](#apidoc.element.react-bootstrap.Label.Label)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Label.</span>STYLES
1.  object <span class="apidocSignatureSpan">react-bootstrap.Label.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Label.</span>propTypes

#### [module react-bootstrap.Label.propTypes](#apidoc.module.react-bootstrap.Label.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Label.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Label.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Label.propTypes.</span>bsStyle ()](#apidoc.element.react-bootstrap.Label.propTypes.bsStyle)

#### [module react-bootstrap.Label.prototype](#apidoc.module.react-bootstrap.Label.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Label.prototype.</span>hasContent (children)](#apidoc.element.react-bootstrap.Label.prototype.hasContent)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Label.prototype.</span>render ()](#apidoc.element.react-bootstrap.Label.prototype.render)

#### [module react-bootstrap.ListGroup](#apidoc.module.react-bootstrap.ListGroup)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>ListGroup ()](#apidoc.element.react-bootstrap.ListGroup.ListGroup)
1.  object <span class="apidocSignatureSpan">react-bootstrap.ListGroup.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.ListGroup.</span>propTypes

#### [module react-bootstrap.ListGroup.propTypes](#apidoc.module.react-bootstrap.ListGroup.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ListGroup.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.ListGroup.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ListGroup.propTypes.</span>componentClass ()](#apidoc.element.react-bootstrap.ListGroup.propTypes.componentClass)

#### [module react-bootstrap.ListGroup.prototype](#apidoc.module.react-bootstrap.ListGroup.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ListGroup.prototype.</span>render ()](#apidoc.element.react-bootstrap.ListGroup.prototype.render)

#### [module react-bootstrap.ListGroupItem](#apidoc.module.react-bootstrap.ListGroupItem)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>ListGroupItem ()](#apidoc.element.react-bootstrap.ListGroupItem.ListGroupItem)
1.  object <span class="apidocSignatureSpan">react-bootstrap.ListGroupItem.</span>STYLES
1.  object <span class="apidocSignatureSpan">react-bootstrap.ListGroupItem.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.ListGroupItem.</span>propTypes

#### [module react-bootstrap.ListGroupItem.propTypes](#apidoc.module.react-bootstrap.ListGroupItem.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ListGroupItem.propTypes.</span>active ()](#apidoc.element.react-bootstrap.ListGroupItem.propTypes.active)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ListGroupItem.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.ListGroupItem.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ListGroupItem.propTypes.</span>bsStyle ()](#apidoc.element.react-bootstrap.ListGroupItem.propTypes.bsStyle)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ListGroupItem.propTypes.</span>disabled ()](#apidoc.element.react-bootstrap.ListGroupItem.propTypes.disabled)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ListGroupItem.propTypes.</span>header ()](#apidoc.element.react-bootstrap.ListGroupItem.propTypes.header)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ListGroupItem.propTypes.</span>href ()](#apidoc.element.react-bootstrap.ListGroupItem.propTypes.href)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ListGroupItem.propTypes.</span>listItem ()](#apidoc.element.react-bootstrap.ListGroupItem.propTypes.listItem)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ListGroupItem.propTypes.</span>onClick ()](#apidoc.element.react-bootstrap.ListGroupItem.propTypes.onClick)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ListGroupItem.propTypes.</span>type ()](#apidoc.element.react-bootstrap.ListGroupItem.propTypes.type)

#### [module react-bootstrap.ListGroupItem.prototype](#apidoc.module.react-bootstrap.ListGroupItem.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ListGroupItem.prototype.</span>render ()](#apidoc.element.react-bootstrap.ListGroupItem.prototype.render)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ListGroupItem.prototype.</span>renderHeader (header, headingClassName)](#apidoc.element.react-bootstrap.ListGroupItem.prototype.renderHeader)

#### [module react-bootstrap.Media](#apidoc.module.react-bootstrap.Media)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Media ()](#apidoc.element.react-bootstrap.Media.Media)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Media.</span>Body ()](#apidoc.element.react-bootstrap.Media.Body)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Media.</span>Heading ()](#apidoc.element.react-bootstrap.Media.Heading)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Media.</span>Left ()](#apidoc.element.react-bootstrap.Media.Left)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Media.</span>List ()](#apidoc.element.react-bootstrap.Media.List)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Media.</span>ListItem ()](#apidoc.element.react-bootstrap.Media.ListItem)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Media.</span>Right ()](#apidoc.element.react-bootstrap.Media.Right)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Media.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Media.</span>propTypes

#### [module react-bootstrap.Media.Body](#apidoc.module.react-bootstrap.Media.Body)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Media.</span>Body ()](#apidoc.element.react-bootstrap.Media.Body.Body)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Media.Body.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Media.Body.</span>propTypes

#### [module react-bootstrap.Media.Body.prototype](#apidoc.module.react-bootstrap.Media.Body.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Media.Body.prototype.</span>render ()](#apidoc.element.react-bootstrap.Media.Body.prototype.render)

#### [module react-bootstrap.Media.Heading](#apidoc.module.react-bootstrap.Media.Heading)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Media.</span>Heading ()](#apidoc.element.react-bootstrap.Media.Heading.Heading)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Media.Heading.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Media.Heading.</span>propTypes

#### [module react-bootstrap.Media.Heading.prototype](#apidoc.module.react-bootstrap.Media.Heading.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Media.Heading.prototype.</span>render ()](#apidoc.element.react-bootstrap.Media.Heading.prototype.render)

#### [module react-bootstrap.Media.Left](#apidoc.module.react-bootstrap.Media.Left)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Media.</span>Left ()](#apidoc.element.react-bootstrap.Media.Left.Left)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Media.Left.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Media.Left.</span>propTypes

#### [module react-bootstrap.Media.Left.prototype](#apidoc.module.react-bootstrap.Media.Left.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Media.Left.prototype.</span>render ()](#apidoc.element.react-bootstrap.Media.Left.prototype.render)

#### [module react-bootstrap.Media.List](#apidoc.module.react-bootstrap.Media.List)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Media.</span>List ()](#apidoc.element.react-bootstrap.Media.List.List)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Media.List.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Media.List.</span>propTypes

#### [module react-bootstrap.Media.List.prototype](#apidoc.module.react-bootstrap.Media.List.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Media.List.prototype.</span>render ()](#apidoc.element.react-bootstrap.Media.List.prototype.render)

#### [module react-bootstrap.Media.ListItem](#apidoc.module.react-bootstrap.Media.ListItem)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Media.</span>ListItem ()](#apidoc.element.react-bootstrap.Media.ListItem.ListItem)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Media.ListItem.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Media.ListItem.</span>propTypes

#### [module react-bootstrap.Media.ListItem.prototype](#apidoc.module.react-bootstrap.Media.ListItem.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Media.ListItem.prototype.</span>render ()](#apidoc.element.react-bootstrap.Media.ListItem.prototype.render)

#### [module react-bootstrap.Media.Right](#apidoc.module.react-bootstrap.Media.Right)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Media.</span>Right ()](#apidoc.element.react-bootstrap.Media.Right.Right)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Media.Right.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Media.Right.</span>propTypes

#### [module react-bootstrap.Media.Right.prototype](#apidoc.module.react-bootstrap.Media.Right.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Media.Right.prototype.</span>render ()](#apidoc.element.react-bootstrap.Media.Right.prototype.render)

#### [module react-bootstrap.Media.propTypes](#apidoc.module.react-bootstrap.Media.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Media.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Media.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Media.propTypes.</span>componentClass ()](#apidoc.element.react-bootstrap.Media.propTypes.componentClass)

#### [module react-bootstrap.Media.prototype](#apidoc.module.react-bootstrap.Media.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Media.prototype.</span>render ()](#apidoc.element.react-bootstrap.Media.prototype.render)

#### [module react-bootstrap.MenuItem](#apidoc.module.react-bootstrap.MenuItem)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>MenuItem (props, context)](#apidoc.element.react-bootstrap.MenuItem.MenuItem)
1.  object <span class="apidocSignatureSpan">react-bootstrap.MenuItem.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.MenuItem.</span>propTypes

#### [module react-bootstrap.MenuItem.propTypes](#apidoc.module.react-bootstrap.MenuItem.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.MenuItem.propTypes.</span>active ()](#apidoc.element.react-bootstrap.MenuItem.propTypes.active)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.MenuItem.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.MenuItem.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.MenuItem.propTypes.</span>disabled ()](#apidoc.element.react-bootstrap.MenuItem.propTypes.disabled)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.MenuItem.propTypes.</span>divider ()](#apidoc.element.react-bootstrap.MenuItem.propTypes.divider)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.MenuItem.propTypes.</span>eventKey ()](#apidoc.element.react-bootstrap.MenuItem.propTypes.eventKey)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.MenuItem.propTypes.</span>header ()](#apidoc.element.react-bootstrap.MenuItem.propTypes.header)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.MenuItem.propTypes.</span>href ()](#apidoc.element.react-bootstrap.MenuItem.propTypes.href)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.MenuItem.propTypes.</span>onClick ()](#apidoc.element.react-bootstrap.MenuItem.propTypes.onClick)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.MenuItem.propTypes.</span>onSelect ()](#apidoc.element.react-bootstrap.MenuItem.propTypes.onSelect)

#### [module react-bootstrap.MenuItem.prototype](#apidoc.module.react-bootstrap.MenuItem.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.MenuItem.prototype.</span>handleClick (event)](#apidoc.element.react-bootstrap.MenuItem.prototype.handleClick)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.MenuItem.prototype.</span>render ()](#apidoc.element.react-bootstrap.MenuItem.prototype.render)

#### [module react-bootstrap.Modal](#apidoc.module.react-bootstrap.Modal)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Modal (props, context)](#apidoc.element.react-bootstrap.Modal.Modal)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.</span>Body ()](#apidoc.element.react-bootstrap.Modal.Body)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.</span>Dialog ()](#apidoc.element.react-bootstrap.Modal.Dialog)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.</span>Footer ()](#apidoc.element.react-bootstrap.Modal.Footer)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.</span>Header ()](#apidoc.element.react-bootstrap.Modal.Header)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.</span>Title ()](#apidoc.element.react-bootstrap.Modal.Title)
1.  number <span class="apidocSignatureSpan">react-bootstrap.Modal.</span>BACKDROP_TRANSITION_DURATION
1.  number <span class="apidocSignatureSpan">react-bootstrap.Modal.</span>TRANSITION_DURATION
1.  object <span class="apidocSignatureSpan">react-bootstrap.Modal.</span>SIZES
1.  object <span class="apidocSignatureSpan">react-bootstrap.Modal.</span>childContextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.Modal.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Modal.</span>propTypes

#### [module react-bootstrap.Modal.Dialog](#apidoc.module.react-bootstrap.Modal.Dialog)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.</span>Dialog ()](#apidoc.element.react-bootstrap.Modal.Dialog.Dialog)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Modal.Dialog.</span>SIZES
1.  object <span class="apidocSignatureSpan">react-bootstrap.Modal.Dialog.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Modal.Dialog.</span>propTypes

#### [module react-bootstrap.Modal.Dialog.prototype](#apidoc.module.react-bootstrap.Modal.Dialog.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.Dialog.prototype.</span>render ()](#apidoc.element.react-bootstrap.Modal.Dialog.prototype.render)

#### [module react-bootstrap.Modal.childContextTypes](#apidoc.module.react-bootstrap.Modal.childContextTypes)

#### [module react-bootstrap.Modal.defaultProps](#apidoc.module.react-bootstrap.Modal.defaultProps)
1.  boolean <span class="apidocSignatureSpan">react-bootstrap.Modal.defaultProps.</span>animation
1.  boolean <span class="apidocSignatureSpan">react-bootstrap.Modal.defaultProps.</span>autoFocus
1.  boolean <span class="apidocSignatureSpan">react-bootstrap.Modal.defaultProps.</span>backdrop
1.  boolean <span class="apidocSignatureSpan">react-bootstrap.Modal.defaultProps.</span>enforceFocus
1.  boolean <span class="apidocSignatureSpan">react-bootstrap.Modal.defaultProps.</span>keyboard
1.  boolean <span class="apidocSignatureSpan">react-bootstrap.Modal.defaultProps.</span>restoreFocus
1.  boolean <span class="apidocSignatureSpan">react-bootstrap.Modal.defaultProps.</span>show
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.defaultProps.</span>dialogComponentClass ()](#apidoc.element.react-bootstrap.Modal.defaultProps.dialogComponentClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.defaultProps.</span>onHide ()](#apidoc.element.react-bootstrap.Modal.defaultProps.onHide)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.defaultProps.</span>renderBackdrop (props)](#apidoc.element.react-bootstrap.Modal.defaultProps.renderBackdrop)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Modal.defaultProps.</span>manager
1.  string <span class="apidocSignatureSpan">react-bootstrap.Modal.defaultProps.</span>bsClass

#### [module react-bootstrap.Modal.propTypes](#apidoc.module.react-bootstrap.Modal.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>animation ()](#apidoc.element.react-bootstrap.Modal.propTypes.animation)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>autoFocus ()](#apidoc.element.react-bootstrap.Modal.propTypes.autoFocus)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>backdrop ()](#apidoc.element.react-bootstrap.Modal.propTypes.backdrop)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>backdropClassName ()](#apidoc.element.react-bootstrap.Modal.propTypes.backdropClassName)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>backdropStyle ()](#apidoc.element.react-bootstrap.Modal.propTypes.backdropStyle)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>backdropTransitionTimeout ()](#apidoc.element.react-bootstrap.Modal.propTypes.backdropTransitionTimeout)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Modal.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>bsSize ()](#apidoc.element.react-bootstrap.Modal.propTypes.bsSize)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>container ()](#apidoc.element.react-bootstrap.Modal.propTypes.container)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>containerClassName ()](#apidoc.element.react-bootstrap.Modal.propTypes.containerClassName)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>dialogClassName ()](#apidoc.element.react-bootstrap.Modal.propTypes.dialogClassName)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>dialogComponentClass ()](#apidoc.element.react-bootstrap.Modal.propTypes.dialogComponentClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>dialogTransitionTimeout ()](#apidoc.element.react-bootstrap.Modal.propTypes.dialogTransitionTimeout)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>enforceFocus ()](#apidoc.element.react-bootstrap.Modal.propTypes.enforceFocus)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>keyboard ()](#apidoc.element.react-bootstrap.Modal.propTypes.keyboard)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>manager ()](#apidoc.element.react-bootstrap.Modal.propTypes.manager)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>onBackdropClick ()](#apidoc.element.react-bootstrap.Modal.propTypes.onBackdropClick)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>onEnter ()](#apidoc.element.react-bootstrap.Modal.propTypes.onEnter)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>onEntered ()](#apidoc.element.react-bootstrap.Modal.propTypes.onEntered)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>onEntering ()](#apidoc.element.react-bootstrap.Modal.propTypes.onEntering)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>onEscapeKeyUp ()](#apidoc.element.react-bootstrap.Modal.propTypes.onEscapeKeyUp)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>onExit ()](#apidoc.element.react-bootstrap.Modal.propTypes.onExit)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>onExited ()](#apidoc.element.react-bootstrap.Modal.propTypes.onExited)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>onExiting ()](#apidoc.element.react-bootstrap.Modal.propTypes.onExiting)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>onHide ()](#apidoc.element.react-bootstrap.Modal.propTypes.onHide)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>onShow ()](#apidoc.element.react-bootstrap.Modal.propTypes.onShow)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>renderBackdrop ()](#apidoc.element.react-bootstrap.Modal.propTypes.renderBackdrop)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>restoreFocus ()](#apidoc.element.react-bootstrap.Modal.propTypes.restoreFocus)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>show ()](#apidoc.element.react-bootstrap.Modal.propTypes.show)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>transition ()](#apidoc.element.react-bootstrap.Modal.propTypes.transition)

#### [module react-bootstrap.Modal.prototype](#apidoc.module.react-bootstrap.Modal.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.prototype.</span>componentWillUnmount ()](#apidoc.element.react-bootstrap.Modal.prototype.componentWillUnmount)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.prototype.</span>getChildContext ()](#apidoc.element.react-bootstrap.Modal.prototype.getChildContext)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.prototype.</span>handleDialogClick (e)](#apidoc.element.react-bootstrap.Modal.prototype.handleDialogClick)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.prototype.</span>handleEntering ()](#apidoc.element.react-bootstrap.Modal.prototype.handleEntering)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.prototype.</span>handleExited ()](#apidoc.element.react-bootstrap.Modal.prototype.handleExited)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.prototype.</span>handleWindowResize ()](#apidoc.element.react-bootstrap.Modal.prototype.handleWindowResize)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.prototype.</span>render ()](#apidoc.element.react-bootstrap.Modal.prototype.render)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Modal.prototype.</span>updateStyle ()](#apidoc.element.react-bootstrap.Modal.prototype.updateStyle)

#### [module react-bootstrap.ModalBody](#apidoc.module.react-bootstrap.ModalBody)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>ModalBody ()](#apidoc.element.react-bootstrap.ModalBody.ModalBody)
1.  object <span class="apidocSignatureSpan">react-bootstrap.ModalBody.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.ModalBody.</span>propTypes

#### [module react-bootstrap.ModalBody.propTypes](#apidoc.module.react-bootstrap.ModalBody.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ModalBody.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.ModalBody.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ModalBody.propTypes.</span>componentClass ()](#apidoc.element.react-bootstrap.ModalBody.propTypes.componentClass)

#### [module react-bootstrap.ModalBody.prototype](#apidoc.module.react-bootstrap.ModalBody.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ModalBody.prototype.</span>render ()](#apidoc.element.react-bootstrap.ModalBody.prototype.render)

#### [module react-bootstrap.ModalFooter](#apidoc.module.react-bootstrap.ModalFooter)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>ModalFooter ()](#apidoc.element.react-bootstrap.ModalFooter.ModalFooter)
1.  object <span class="apidocSignatureSpan">react-bootstrap.ModalFooter.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.ModalFooter.</span>propTypes

#### [module react-bootstrap.ModalFooter.propTypes](#apidoc.module.react-bootstrap.ModalFooter.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ModalFooter.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.ModalFooter.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ModalFooter.propTypes.</span>componentClass ()](#apidoc.element.react-bootstrap.ModalFooter.propTypes.componentClass)

#### [module react-bootstrap.ModalFooter.prototype](#apidoc.module.react-bootstrap.ModalFooter.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ModalFooter.prototype.</span>render ()](#apidoc.element.react-bootstrap.ModalFooter.prototype.render)

#### [module react-bootstrap.ModalHeader](#apidoc.module.react-bootstrap.ModalHeader)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>ModalHeader ()](#apidoc.element.react-bootstrap.ModalHeader.ModalHeader)
1.  object <span class="apidocSignatureSpan">react-bootstrap.ModalHeader.</span>contextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.ModalHeader.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.ModalHeader.</span>propTypes

#### [module react-bootstrap.ModalHeader.contextTypes](#apidoc.module.react-bootstrap.ModalHeader.contextTypes)

#### [module react-bootstrap.ModalHeader.propTypes](#apidoc.module.react-bootstrap.ModalHeader.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ModalHeader.propTypes.</span>aria-label ()](#apidoc.element.react-bootstrap.ModalHeader.propTypes.aria-label)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ModalHeader.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.ModalHeader.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ModalHeader.propTypes.</span>closeButton ()](#apidoc.element.react-bootstrap.ModalHeader.propTypes.closeButton)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ModalHeader.propTypes.</span>onHide ()](#apidoc.element.react-bootstrap.ModalHeader.propTypes.onHide)

#### [module react-bootstrap.ModalHeader.prototype](#apidoc.module.react-bootstrap.ModalHeader.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ModalHeader.prototype.</span>render ()](#apidoc.element.react-bootstrap.ModalHeader.prototype.render)

#### [module react-bootstrap.ModalTitle](#apidoc.module.react-bootstrap.ModalTitle)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>ModalTitle ()](#apidoc.element.react-bootstrap.ModalTitle.ModalTitle)
1.  object <span class="apidocSignatureSpan">react-bootstrap.ModalTitle.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.ModalTitle.</span>propTypes

#### [module react-bootstrap.ModalTitle.propTypes](#apidoc.module.react-bootstrap.ModalTitle.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ModalTitle.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.ModalTitle.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ModalTitle.propTypes.</span>componentClass ()](#apidoc.element.react-bootstrap.ModalTitle.propTypes.componentClass)

#### [module react-bootstrap.ModalTitle.prototype](#apidoc.module.react-bootstrap.ModalTitle.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ModalTitle.prototype.</span>render ()](#apidoc.element.react-bootstrap.ModalTitle.prototype.render)

#### [module react-bootstrap.Nav](#apidoc.module.react-bootstrap.Nav)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Nav ()](#apidoc.element.react-bootstrap.Nav.Nav)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Nav.</span>STYLES
1.  object <span class="apidocSignatureSpan">react-bootstrap.Nav.</span>contextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.Nav.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Nav.</span>propTypes

#### [module react-bootstrap.Nav.contextTypes](#apidoc.module.react-bootstrap.Nav.contextTypes)

#### [module react-bootstrap.Nav.propTypes](#apidoc.module.react-bootstrap.Nav.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Nav.propTypes.</span>activeHref ()](#apidoc.element.react-bootstrap.Nav.propTypes.activeHref)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Nav.propTypes.</span>activeKey ()](#apidoc.element.react-bootstrap.Nav.propTypes.activeKey)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Nav.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Nav.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Nav.propTypes.</span>bsStyle ()](#apidoc.element.react-bootstrap.Nav.propTypes.bsStyle)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Nav.propTypes.</span>justified ()](#apidoc.element.react-bootstrap.Nav.propTypes.justified)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Nav.propTypes.</span>navbar ()](#apidoc.element.react-bootstrap.Nav.propTypes.navbar)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Nav.propTypes.</span>onSelect ()](#apidoc.element.react-bootstrap.Nav.propTypes.onSelect)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Nav.propTypes.</span>pullLeft ()](#apidoc.element.react-bootstrap.Nav.propTypes.pullLeft)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Nav.propTypes.</span>pullRight ()](#apidoc.element.react-bootstrap.Nav.propTypes.pullRight)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Nav.propTypes.</span>role ()](#apidoc.element.react-bootstrap.Nav.propTypes.role)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Nav.propTypes.</span>stacked ()](#apidoc.element.react-bootstrap.Nav.propTypes.stacked)

#### [module react-bootstrap.Nav.prototype](#apidoc.module.react-bootstrap.Nav.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Nav.prototype.</span>componentDidUpdate ()](#apidoc.element.react-bootstrap.Nav.prototype.componentDidUpdate)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Nav.prototype.</span>getActiveProps ()](#apidoc.element.react-bootstrap.Nav.prototype.getActiveProps)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Nav.prototype.</span>getNextActiveChild (offset)](#apidoc.element.react-bootstrap.Nav.prototype.getNextActiveChild)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Nav.prototype.</span>getTabProps (child, tabContainer, navRole, active, onSelect)](#apidoc.element.react-bootstrap.Nav.prototype.getTabProps)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Nav.prototype.</span>handleTabKeyDown (onSelect, event)](#apidoc.element.react-bootstrap.Nav.prototype.handleTabKeyDown)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Nav.prototype.</span>isActive (_ref2, activeKey, activeHref)](#apidoc.element.react-bootstrap.Nav.prototype.isActive)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Nav.prototype.</span>render ()](#apidoc.element.react-bootstrap.Nav.prototype.render)

#### [module react-bootstrap.NavDropdown](#apidoc.module.react-bootstrap.NavDropdown)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>NavDropdown ()](#apidoc.element.react-bootstrap.NavDropdown.NavDropdown)
1.  object <span class="apidocSignatureSpan">react-bootstrap.NavDropdown.</span>propTypes

#### [module react-bootstrap.NavDropdown.propTypes](#apidoc.module.react-bootstrap.NavDropdown.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.NavDropdown.propTypes.</span>active ()](#apidoc.element.react-bootstrap.NavDropdown.propTypes.active)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.NavDropdown.propTypes.</span>children ()](#apidoc.element.react-bootstrap.NavDropdown.propTypes.children)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.NavDropdown.propTypes.</span>noCaret ()](#apidoc.element.react-bootstrap.NavDropdown.propTypes.noCaret)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.NavDropdown.propTypes.</span>open (props, propName)](#apidoc.element.react-bootstrap.NavDropdown.propTypes.open)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.NavDropdown.propTypes.</span>title ()](#apidoc.element.react-bootstrap.NavDropdown.propTypes.title)

#### [module react-bootstrap.NavDropdown.prototype](#apidoc.module.react-bootstrap.NavDropdown.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.NavDropdown.prototype.</span>isActive (_ref, activeKey, activeHref)](#apidoc.element.react-bootstrap.NavDropdown.prototype.isActive)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.NavDropdown.prototype.</span>render ()](#apidoc.element.react-bootstrap.NavDropdown.prototype.render)

#### [module react-bootstrap.NavItem](#apidoc.module.react-bootstrap.NavItem)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>NavItem (props, context)](#apidoc.element.react-bootstrap.NavItem.NavItem)
1.  object <span class="apidocSignatureSpan">react-bootstrap.NavItem.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.NavItem.</span>propTypes

#### [module react-bootstrap.NavItem.propTypes](#apidoc.module.react-bootstrap.NavItem.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.NavItem.propTypes.</span>active ()](#apidoc.element.react-bootstrap.NavItem.propTypes.active)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.NavItem.propTypes.</span>disabled ()](#apidoc.element.react-bootstrap.NavItem.propTypes.disabled)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.NavItem.propTypes.</span>eventKey ()](#apidoc.element.react-bootstrap.NavItem.propTypes.eventKey)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.NavItem.propTypes.</span>href ()](#apidoc.element.react-bootstrap.NavItem.propTypes.href)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.NavItem.propTypes.</span>onClick ()](#apidoc.element.react-bootstrap.NavItem.propTypes.onClick)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.NavItem.propTypes.</span>onSelect ()](#apidoc.element.react-bootstrap.NavItem.propTypes.onSelect)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.NavItem.propTypes.</span>role ()](#apidoc.element.react-bootstrap.NavItem.propTypes.role)

#### [module react-bootstrap.NavItem.prototype](#apidoc.module.react-bootstrap.NavItem.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.NavItem.prototype.</span>handleClick (e)](#apidoc.element.react-bootstrap.NavItem.prototype.handleClick)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.NavItem.prototype.</span>render ()](#apidoc.element.react-bootstrap.NavItem.prototype.render)

#### [module react-bootstrap.Navbar](#apidoc.module.react-bootstrap.Navbar)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Navbar (props, context, updater)](#apidoc.element.react-bootstrap.Navbar.Navbar)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Navbar.</span>Brand ()](#apidoc.element.react-bootstrap.Navbar.Brand)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Navbar.</span>Collapse ()](#apidoc.element.react-bootstrap.Navbar.Collapse)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Navbar.</span>ControlledComponent (props, context)](#apidoc.element.react-bootstrap.Navbar.ControlledComponent)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Navbar.</span>Form (_ref, _ref2)](#apidoc.element.react-bootstrap.Navbar.Form)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Navbar.</span>Header ()](#apidoc.element.react-bootstrap.Navbar.Header)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Navbar.</span>Link (_ref, _ref2)](#apidoc.element.react-bootstrap.Navbar.Link)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Navbar.</span>Text (_ref, _ref2)](#apidoc.element.react-bootstrap.Navbar.Text)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Navbar.</span>Toggle ()](#apidoc.element.react-bootstrap.Navbar.Toggle)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Navbar.</span>deferControlTo (newComponent)](#apidoc.element.react-bootstrap.Navbar.deferControlTo)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Navbar.</span>STYLES
1.  object <span class="apidocSignatureSpan">react-bootstrap.Navbar.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Navbar.</span>propTypes
1.  string <span class="apidocSignatureSpan">react-bootstrap.Navbar.</span>displayName

#### [module react-bootstrap.Navbar.Collapse](#apidoc.module.react-bootstrap.Navbar.Collapse)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Navbar.</span>Collapse ()](#apidoc.element.react-bootstrap.Navbar.Collapse.Collapse)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Navbar.Collapse.</span>contextTypes

#### [module react-bootstrap.Navbar.Collapse.prototype](#apidoc.module.react-bootstrap.Navbar.Collapse.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Navbar.Collapse.prototype.</span>render ()](#apidoc.element.react-bootstrap.Navbar.Collapse.prototype.render)

#### [module react-bootstrap.Navbar.ControlledComponent](#apidoc.module.react-bootstrap.Navbar.ControlledComponent)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Navbar.</span>ControlledComponent (props, context)](#apidoc.element.react-bootstrap.Navbar.ControlledComponent.ControlledComponent)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Navbar.ControlledComponent.</span>childContextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.Navbar.ControlledComponent.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Navbar.ControlledComponent.</span>propTypes

#### [module react-bootstrap.Navbar.ControlledComponent.prototype](#apidoc.module.react-bootstrap.Navbar.ControlledComponent.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Navbar.ControlledComponent.prototype.</span>getChildContext ()](#apidoc.element.react-bootstrap.Navbar.ControlledComponent.prototype.getChildContext)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Navbar.ControlledComponent.prototype.</span>handleCollapse ()](#apidoc.element.react-bootstrap.Navbar.ControlledComponent.prototype.handleCollapse)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Navbar.ControlledComponent.prototype.</span>handleToggle ()](#apidoc.element.react-bootstrap.Navbar.ControlledComponent.prototype.handleToggle)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Navbar.ControlledComponent.prototype.</span>render ()](#apidoc.element.react-bootstrap.Navbar.ControlledComponent.prototype.render)

#### [module react-bootstrap.Navbar.Header](#apidoc.module.react-bootstrap.Navbar.Header)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Navbar.</span>Header ()](#apidoc.element.react-bootstrap.Navbar.Header.Header)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Navbar.Header.</span>contextTypes

#### [module react-bootstrap.Navbar.Header.prototype](#apidoc.module.react-bootstrap.Navbar.Header.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Navbar.Header.prototype.</span>render ()](#apidoc.element.react-bootstrap.Navbar.Header.prototype.render)

#### [module react-bootstrap.Navbar.Toggle](#apidoc.module.react-bootstrap.Navbar.Toggle)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Navbar.</span>Toggle ()](#apidoc.element.react-bootstrap.Navbar.Toggle.Toggle)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Navbar.Toggle.</span>contextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.Navbar.Toggle.</span>propTypes

#### [module react-bootstrap.Navbar.Toggle.prototype](#apidoc.module.react-bootstrap.Navbar.Toggle.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Navbar.Toggle.prototype.</span>render ()](#apidoc.element.react-bootstrap.Navbar.Toggle.prototype.render)

#### [module react-bootstrap.Navbar.propTypes](#apidoc.module.react-bootstrap.Navbar.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Navbar.propTypes.</span>bsStyle ()](#apidoc.element.react-bootstrap.Navbar.propTypes.bsStyle)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Navbar.propTypes.</span>expanded (props, propName)](#apidoc.element.react-bootstrap.Navbar.propTypes.expanded)

#### [module react-bootstrap.Navbar.prototype](#apidoc.module.react-bootstrap.Navbar.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Navbar.prototype.</span>componentWillMount ()](#apidoc.element.react-bootstrap.Navbar.prototype.componentWillMount)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Navbar.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.react-bootstrap.Navbar.prototype.componentWillReceiveProps)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Navbar.prototype.</span>constructor (props, context, updater)](#apidoc.element.react-bootstrap.Navbar.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Navbar.prototype.</span>getControlledInstance ()](#apidoc.element.react-bootstrap.Navbar.prototype.getControlledInstance)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Navbar.prototype.</span>render ()](#apidoc.element.react-bootstrap.Navbar.prototype.render)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Navbar.prototype.</span>shouldComponentUpdate ()](#apidoc.element.react-bootstrap.Navbar.prototype.shouldComponentUpdate)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Navbar.prototype.</span>__reactAutoBindPairs
1.  object <span class="apidocSignatureSpan">react-bootstrap.Navbar.prototype.</span>childContextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.Navbar.prototype.</span>componentDidMount
1.  object <span class="apidocSignatureSpan">react-bootstrap.Navbar.prototype.</span>componentDidUpdate
1.  object <span class="apidocSignatureSpan">react-bootstrap.Navbar.prototype.</span>componentWillUnmount
1.  object <span class="apidocSignatureSpan">react-bootstrap.Navbar.prototype.</span>componentWillUpdate
1.  object <span class="apidocSignatureSpan">react-bootstrap.Navbar.prototype.</span>contextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.Navbar.prototype.</span>getChildContext
1.  object <span class="apidocSignatureSpan">react-bootstrap.Navbar.prototype.</span>getDefaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Navbar.prototype.</span>getInitialState
1.  object <span class="apidocSignatureSpan">react-bootstrap.Navbar.prototype.</span>mixins
1.  object <span class="apidocSignatureSpan">react-bootstrap.Navbar.prototype.</span>propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.Navbar.prototype.</span>statics
1.  object <span class="apidocSignatureSpan">react-bootstrap.Navbar.prototype.</span>updateComponent

#### [module react-bootstrap.Navbar.prototype.__reactAutoBindPairs](#apidoc.module.react-bootstrap.Navbar.prototype.__reactAutoBindPairs)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Navbar.prototype.__reactAutoBindPairs.</span>1 ()](#apidoc.element.react-bootstrap.Navbar.prototype.__reactAutoBindPairs.1)
1.  string <span class="apidocSignatureSpan">react-bootstrap.Navbar.prototype.__reactAutoBindPairs.</span>0

#### [module react-bootstrap.NavbarBrand](#apidoc.module.react-bootstrap.NavbarBrand)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>NavbarBrand ()](#apidoc.element.react-bootstrap.NavbarBrand.NavbarBrand)
1.  object <span class="apidocSignatureSpan">react-bootstrap.NavbarBrand.</span>contextTypes

#### [module react-bootstrap.NavbarBrand.contextTypes](#apidoc.module.react-bootstrap.NavbarBrand.contextTypes)

#### [module react-bootstrap.NavbarBrand.prototype](#apidoc.module.react-bootstrap.NavbarBrand.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.NavbarBrand.prototype.</span>render ()](#apidoc.element.react-bootstrap.NavbarBrand.prototype.render)

#### [module react-bootstrap.Overlay](#apidoc.module.react-bootstrap.Overlay)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Overlay ()](#apidoc.element.react-bootstrap.Overlay.Overlay)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Overlay.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Overlay.</span>propTypes

#### [module react-bootstrap.Overlay.defaultProps](#apidoc.module.react-bootstrap.Overlay.defaultProps)
1.  boolean <span class="apidocSignatureSpan">react-bootstrap.Overlay.defaultProps.</span>rootClose
1.  boolean <span class="apidocSignatureSpan">react-bootstrap.Overlay.defaultProps.</span>show
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Overlay.defaultProps.</span>animation ()](#apidoc.element.react-bootstrap.Overlay.defaultProps.animation)
1.  string <span class="apidocSignatureSpan">react-bootstrap.Overlay.defaultProps.</span>placement

#### [module react-bootstrap.Overlay.propTypes](#apidoc.module.react-bootstrap.Overlay.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>animation ()](#apidoc.element.react-bootstrap.Overlay.propTypes.animation)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>container ()](#apidoc.element.react-bootstrap.Overlay.propTypes.container)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>containerPadding ()](#apidoc.element.react-bootstrap.Overlay.propTypes.containerPadding)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>onEnter ()](#apidoc.element.react-bootstrap.Overlay.propTypes.onEnter)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>onEntered ()](#apidoc.element.react-bootstrap.Overlay.propTypes.onEntered)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>onEntering ()](#apidoc.element.react-bootstrap.Overlay.propTypes.onEntering)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>onExit ()](#apidoc.element.react-bootstrap.Overlay.propTypes.onExit)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>onExited ()](#apidoc.element.react-bootstrap.Overlay.propTypes.onExited)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>onExiting ()](#apidoc.element.react-bootstrap.Overlay.propTypes.onExiting)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>onHide ()](#apidoc.element.react-bootstrap.Overlay.propTypes.onHide)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>placement ()](#apidoc.element.react-bootstrap.Overlay.propTypes.placement)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>rootClose ()](#apidoc.element.react-bootstrap.Overlay.propTypes.rootClose)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>shouldUpdatePosition ()](#apidoc.element.react-bootstrap.Overlay.propTypes.shouldUpdatePosition)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>show ()](#apidoc.element.react-bootstrap.Overlay.propTypes.show)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>target ()](#apidoc.element.react-bootstrap.Overlay.propTypes.target)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>transition ()](#apidoc.element.react-bootstrap.Overlay.propTypes.transition)

#### [module react-bootstrap.Overlay.prototype](#apidoc.module.react-bootstrap.Overlay.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Overlay.prototype.</span>render ()](#apidoc.element.react-bootstrap.Overlay.prototype.render)

#### [module react-bootstrap.OverlayTrigger](#apidoc.module.react-bootstrap.OverlayTrigger)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>OverlayTrigger (props, context)](#apidoc.element.react-bootstrap.OverlayTrigger.OverlayTrigger)
1.  object <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.</span>propTypes

#### [module react-bootstrap.OverlayTrigger.propTypes](#apidoc.module.react-bootstrap.OverlayTrigger.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>animation ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.animation)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>container ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.container)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>containerPadding ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.containerPadding)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>defaultOverlayShown ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.defaultOverlayShown)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>delay ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.delay)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>delayHide ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.delayHide)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>delayShow ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.delayShow)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>onBlur ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onBlur)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>onClick ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onClick)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>onEnter ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onEnter)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>onEntered ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onEntered)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>onEntering ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onEntering)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>onExit ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onExit)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>onExited ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onExited)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>onExiting ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onExiting)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>onFocus ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onFocus)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>onHide ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onHide)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>onMouseOut ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onMouseOut)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>onMouseOver ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onMouseOver)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>overlay ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.overlay)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>placement ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.placement)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>rootClose ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.rootClose)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>shouldUpdatePosition ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.shouldUpdatePosition)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>show ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.show)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>target ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.target)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>transition ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.transition)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>trigger ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.trigger)

#### [module react-bootstrap.OverlayTrigger.prototype](#apidoc.module.react-bootstrap.OverlayTrigger.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.prototype.</span>componentDidMount ()](#apidoc.element.react-bootstrap.OverlayTrigger.prototype.componentDidMount)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.prototype.</span>componentDidUpdate ()](#apidoc.element.react-bootstrap.OverlayTrigger.prototype.componentDidUpdate)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.prototype.</span>componentWillUnmount ()](#apidoc.element.react-bootstrap.OverlayTrigger.prototype.componentWillUnmount)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.prototype.</span>handleDelayedHide ()](#apidoc.element.react-bootstrap.OverlayTrigger.prototype.handleDelayedHide)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.prototype.</span>handleDelayedShow ()](#apidoc.element.react-bootstrap.OverlayTrigger.prototype.handleDelayedShow)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.prototype.</span>handleHide ()](#apidoc.element.react-bootstrap.OverlayTrigger.prototype.handleHide)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.prototype.</span>handleMouseOverOut (handler, e)](#apidoc.element.react-bootstrap.OverlayTrigger.prototype.handleMouseOverOut)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.prototype.</span>handleToggle ()](#apidoc.element.react-bootstrap.OverlayTrigger.prototype.handleToggle)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.prototype.</span>hide ()](#apidoc.element.react-bootstrap.OverlayTrigger.prototype.hide)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.prototype.</span>makeOverlay (overlay, props)](#apidoc.element.react-bootstrap.OverlayTrigger.prototype.makeOverlay)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.prototype.</span>render ()](#apidoc.element.react-bootstrap.OverlayTrigger.prototype.render)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.prototype.</span>renderOverlay ()](#apidoc.element.react-bootstrap.OverlayTrigger.prototype.renderOverlay)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.prototype.</span>show ()](#apidoc.element.react-bootstrap.OverlayTrigger.prototype.show)

#### [module react-bootstrap.PageHeader](#apidoc.module.react-bootstrap.PageHeader)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>PageHeader ()](#apidoc.element.react-bootstrap.PageHeader.PageHeader)
1.  object <span class="apidocSignatureSpan">react-bootstrap.PageHeader.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.PageHeader.</span>propTypes

#### [module react-bootstrap.PageHeader.propTypes](#apidoc.module.react-bootstrap.PageHeader.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.PageHeader.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.PageHeader.propTypes.bsClass)

#### [module react-bootstrap.PageHeader.prototype](#apidoc.module.react-bootstrap.PageHeader.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.PageHeader.prototype.</span>render ()](#apidoc.element.react-bootstrap.PageHeader.prototype.render)

#### [module react-bootstrap.PageItem](#apidoc.module.react-bootstrap.PageItem)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>PageItem ()](#apidoc.element.react-bootstrap.PageItem.PageItem)

#### [module react-bootstrap.PageItem.prototype](#apidoc.module.react-bootstrap.PageItem.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.PageItem.prototype.</span>componentWillMount ()](#apidoc.element.react-bootstrap.PageItem.prototype.componentWillMount)

#### [module react-bootstrap.Pager](#apidoc.module.react-bootstrap.Pager)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Pager ()](#apidoc.element.react-bootstrap.Pager.Pager)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Pager.</span>Item (props, context)](#apidoc.element.react-bootstrap.Pager.Item)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Pager.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Pager.</span>propTypes

#### [module react-bootstrap.Pager.Item](#apidoc.module.react-bootstrap.Pager.Item)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Pager.</span>Item (props, context)](#apidoc.element.react-bootstrap.Pager.Item.Item)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Pager.Item.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Pager.Item.</span>propTypes

#### [module react-bootstrap.Pager.Item.prototype](#apidoc.module.react-bootstrap.Pager.Item.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Pager.Item.prototype.</span>handleSelect (e)](#apidoc.element.react-bootstrap.Pager.Item.prototype.handleSelect)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Pager.Item.prototype.</span>render ()](#apidoc.element.react-bootstrap.Pager.Item.prototype.render)

#### [module react-bootstrap.Pager.propTypes](#apidoc.module.react-bootstrap.Pager.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Pager.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Pager.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Pager.propTypes.</span>onSelect ()](#apidoc.element.react-bootstrap.Pager.propTypes.onSelect)

#### [module react-bootstrap.Pager.prototype](#apidoc.module.react-bootstrap.Pager.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Pager.prototype.</span>render ()](#apidoc.element.react-bootstrap.Pager.prototype.render)

#### [module react-bootstrap.Pagination](#apidoc.module.react-bootstrap.Pagination)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Pagination ()](#apidoc.element.react-bootstrap.Pagination.Pagination)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Pagination.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Pagination.</span>propTypes

#### [module react-bootstrap.Pagination.propTypes](#apidoc.module.react-bootstrap.Pagination.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Pagination.propTypes.</span>activePage ()](#apidoc.element.react-bootstrap.Pagination.propTypes.activePage)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Pagination.propTypes.</span>boundaryLinks ()](#apidoc.element.react-bootstrap.Pagination.propTypes.boundaryLinks)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Pagination.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Pagination.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Pagination.propTypes.</span>buttonComponentClass ()](#apidoc.element.react-bootstrap.Pagination.propTypes.buttonComponentClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Pagination.propTypes.</span>ellipsis ()](#apidoc.element.react-bootstrap.Pagination.propTypes.ellipsis)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Pagination.propTypes.</span>first ()](#apidoc.element.react-bootstrap.Pagination.propTypes.first)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Pagination.propTypes.</span>items ()](#apidoc.element.react-bootstrap.Pagination.propTypes.items)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Pagination.propTypes.</span>last ()](#apidoc.element.react-bootstrap.Pagination.propTypes.last)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Pagination.propTypes.</span>maxButtons ()](#apidoc.element.react-bootstrap.Pagination.propTypes.maxButtons)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Pagination.propTypes.</span>next ()](#apidoc.element.react-bootstrap.Pagination.propTypes.next)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Pagination.propTypes.</span>onSelect ()](#apidoc.element.react-bootstrap.Pagination.propTypes.onSelect)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Pagination.propTypes.</span>prev ()](#apidoc.element.react-bootstrap.Pagination.propTypes.prev)

#### [module react-bootstrap.Pagination.prototype](#apidoc.module.react-bootstrap.Pagination.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Pagination.prototype.</span>render ()](#apidoc.element.react-bootstrap.Pagination.prototype.render)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Pagination.prototype.</span>renderPageButtons (activePage, items, maxButtons, boundaryLinks, ellipsis, buttonProps)](#apidoc.element.react-bootstrap.Pagination.prototype.renderPageButtons)

#### [module react-bootstrap.PaginationButton](#apidoc.module.react-bootstrap.PaginationButton)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>PaginationButton (props, context)](#apidoc.element.react-bootstrap.PaginationButton.PaginationButton)
1.  object <span class="apidocSignatureSpan">react-bootstrap.PaginationButton.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.PaginationButton.</span>propTypes

#### [module react-bootstrap.PaginationButton.prototype](#apidoc.module.react-bootstrap.PaginationButton.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.PaginationButton.prototype.</span>handleClick (event)](#apidoc.element.react-bootstrap.PaginationButton.prototype.handleClick)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.PaginationButton.prototype.</span>render ()](#apidoc.element.react-bootstrap.PaginationButton.prototype.render)

#### [module react-bootstrap.Panel](#apidoc.module.react-bootstrap.Panel)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Panel (props, context)](#apidoc.element.react-bootstrap.Panel.Panel)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Panel.</span>STYLES
1.  object <span class="apidocSignatureSpan">react-bootstrap.Panel.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Panel.</span>propTypes

#### [module react-bootstrap.Panel.propTypes](#apidoc.module.react-bootstrap.Panel.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Panel.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>bsStyle ()](#apidoc.element.react-bootstrap.Panel.propTypes.bsStyle)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>collapsible ()](#apidoc.element.react-bootstrap.Panel.propTypes.collapsible)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>defaultExpanded ()](#apidoc.element.react-bootstrap.Panel.propTypes.defaultExpanded)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>eventKey ()](#apidoc.element.react-bootstrap.Panel.propTypes.eventKey)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>expanded ()](#apidoc.element.react-bootstrap.Panel.propTypes.expanded)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>footer ()](#apidoc.element.react-bootstrap.Panel.propTypes.footer)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>header ()](#apidoc.element.react-bootstrap.Panel.propTypes.header)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>headerRole ()](#apidoc.element.react-bootstrap.Panel.propTypes.headerRole)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>id ()](#apidoc.element.react-bootstrap.Panel.propTypes.id)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>onEnter ()](#apidoc.element.react-bootstrap.Panel.propTypes.onEnter)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>onEntered ()](#apidoc.element.react-bootstrap.Panel.propTypes.onEntered)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>onEntering ()](#apidoc.element.react-bootstrap.Panel.propTypes.onEntering)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>onExit ()](#apidoc.element.react-bootstrap.Panel.propTypes.onExit)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>onExited ()](#apidoc.element.react-bootstrap.Panel.propTypes.onExited)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>onExiting ()](#apidoc.element.react-bootstrap.Panel.propTypes.onExiting)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>onSelect ()](#apidoc.element.react-bootstrap.Panel.propTypes.onSelect)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>panelRole ()](#apidoc.element.react-bootstrap.Panel.propTypes.panelRole)

#### [module react-bootstrap.Panel.prototype](#apidoc.module.react-bootstrap.Panel.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Panel.prototype.</span>handleClickTitle (e)](#apidoc.element.react-bootstrap.Panel.prototype.handleClickTitle)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Panel.prototype.</span>render ()](#apidoc.element.react-bootstrap.Panel.prototype.render)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Panel.prototype.</span>renderAnchor (header, id, role, expanded)](#apidoc.element.react-bootstrap.Panel.prototype.renderAnchor)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Panel.prototype.</span>renderBody (rawChildren, bsProps)](#apidoc.element.react-bootstrap.Panel.prototype.renderBody)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Panel.prototype.</span>renderCollapsibleBody (id, expanded, role, children, bsProps, animationHooks)](#apidoc.element.react-bootstrap.Panel.prototype.renderCollapsibleBody)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Panel.prototype.</span>renderHeader (collapsible, header, id, role, expanded, bsProps)](#apidoc.element.react-bootstrap.Panel.prototype.renderHeader)

#### [module react-bootstrap.PanelGroup](#apidoc.module.react-bootstrap.PanelGroup)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>PanelGroup (props, context)](#apidoc.element.react-bootstrap.PanelGroup.PanelGroup)
1.  object <span class="apidocSignatureSpan">react-bootstrap.PanelGroup.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.PanelGroup.</span>propTypes

#### [module react-bootstrap.PanelGroup.propTypes](#apidoc.module.react-bootstrap.PanelGroup.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.PanelGroup.propTypes.</span>accordion ()](#apidoc.element.react-bootstrap.PanelGroup.propTypes.accordion)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.PanelGroup.propTypes.</span>activeKey ()](#apidoc.element.react-bootstrap.PanelGroup.propTypes.activeKey)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.PanelGroup.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.PanelGroup.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.PanelGroup.propTypes.</span>defaultActiveKey ()](#apidoc.element.react-bootstrap.PanelGroup.propTypes.defaultActiveKey)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.PanelGroup.propTypes.</span>onSelect ()](#apidoc.element.react-bootstrap.PanelGroup.propTypes.onSelect)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.PanelGroup.propTypes.</span>role ()](#apidoc.element.react-bootstrap.PanelGroup.propTypes.role)

#### [module react-bootstrap.PanelGroup.prototype](#apidoc.module.react-bootstrap.PanelGroup.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.PanelGroup.prototype.</span>handleSelect (key, e)](#apidoc.element.react-bootstrap.PanelGroup.prototype.handleSelect)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.PanelGroup.prototype.</span>render ()](#apidoc.element.react-bootstrap.PanelGroup.prototype.render)

#### [module react-bootstrap.Popover](#apidoc.module.react-bootstrap.Popover)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Popover ()](#apidoc.element.react-bootstrap.Popover.Popover)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Popover.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Popover.</span>propTypes

#### [module react-bootstrap.Popover.propTypes](#apidoc.module.react-bootstrap.Popover.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Popover.propTypes.</span>arrowOffsetLeft ()](#apidoc.element.react-bootstrap.Popover.propTypes.arrowOffsetLeft)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Popover.propTypes.</span>arrowOffsetTop ()](#apidoc.element.react-bootstrap.Popover.propTypes.arrowOffsetTop)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Popover.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Popover.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Popover.propTypes.</span>id (props, propName, componentName, location, propFullName)](#apidoc.element.react-bootstrap.Popover.propTypes.id)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Popover.propTypes.</span>placement ()](#apidoc.element.react-bootstrap.Popover.propTypes.placement)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Popover.propTypes.</span>positionLeft ()](#apidoc.element.react-bootstrap.Popover.propTypes.positionLeft)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Popover.propTypes.</span>positionTop ()](#apidoc.element.react-bootstrap.Popover.propTypes.positionTop)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Popover.propTypes.</span>title ()](#apidoc.element.react-bootstrap.Popover.propTypes.title)

#### [module react-bootstrap.Popover.prototype](#apidoc.module.react-bootstrap.Popover.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Popover.prototype.</span>render ()](#apidoc.element.react-bootstrap.Popover.prototype.render)

#### [module react-bootstrap.ProgressBar](#apidoc.module.react-bootstrap.ProgressBar)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>ProgressBar ()](#apidoc.element.react-bootstrap.ProgressBar.ProgressBar)
1.  object <span class="apidocSignatureSpan">react-bootstrap.ProgressBar.</span>STYLES
1.  object <span class="apidocSignatureSpan">react-bootstrap.ProgressBar.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.ProgressBar.</span>propTypes

#### [module react-bootstrap.ProgressBar.propTypes](#apidoc.module.react-bootstrap.ProgressBar.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ProgressBar.propTypes.</span>active ()](#apidoc.element.react-bootstrap.ProgressBar.propTypes.active)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ProgressBar.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.ProgressBar.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ProgressBar.propTypes.</span>bsStyle ()](#apidoc.element.react-bootstrap.ProgressBar.propTypes.bsStyle)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ProgressBar.propTypes.</span>children (props, propName, componentName)](#apidoc.element.react-bootstrap.ProgressBar.propTypes.children)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ProgressBar.propTypes.</span>isChild ()](#apidoc.element.react-bootstrap.ProgressBar.propTypes.isChild)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ProgressBar.propTypes.</span>label ()](#apidoc.element.react-bootstrap.ProgressBar.propTypes.label)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ProgressBar.propTypes.</span>max ()](#apidoc.element.react-bootstrap.ProgressBar.propTypes.max)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ProgressBar.propTypes.</span>min ()](#apidoc.element.react-bootstrap.ProgressBar.propTypes.min)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ProgressBar.propTypes.</span>now ()](#apidoc.element.react-bootstrap.ProgressBar.propTypes.now)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ProgressBar.propTypes.</span>srOnly ()](#apidoc.element.react-bootstrap.ProgressBar.propTypes.srOnly)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ProgressBar.propTypes.</span>striped ()](#apidoc.element.react-bootstrap.ProgressBar.propTypes.striped)

#### [module react-bootstrap.ProgressBar.prototype](#apidoc.module.react-bootstrap.ProgressBar.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ProgressBar.prototype.</span>render ()](#apidoc.element.react-bootstrap.ProgressBar.prototype.render)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ProgressBar.prototype.</span>renderProgressBar (_ref)](#apidoc.element.react-bootstrap.ProgressBar.prototype.renderProgressBar)

#### [module react-bootstrap.Radio](#apidoc.module.react-bootstrap.Radio)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Radio ()](#apidoc.element.react-bootstrap.Radio.Radio)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Radio.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Radio.</span>propTypes

#### [module react-bootstrap.Radio.propTypes](#apidoc.module.react-bootstrap.Radio.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Radio.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Radio.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Radio.propTypes.</span>disabled ()](#apidoc.element.react-bootstrap.Radio.propTypes.disabled)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Radio.propTypes.</span>inline ()](#apidoc.element.react-bootstrap.Radio.propTypes.inline)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Radio.propTypes.</span>inputRef ()](#apidoc.element.react-bootstrap.Radio.propTypes.inputRef)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Radio.propTypes.</span>validationState ()](#apidoc.element.react-bootstrap.Radio.propTypes.validationState)

#### [module react-bootstrap.Radio.prototype](#apidoc.module.react-bootstrap.Radio.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Radio.prototype.</span>render ()](#apidoc.element.react-bootstrap.Radio.prototype.render)

#### [module react-bootstrap.ResponsiveEmbed](#apidoc.module.react-bootstrap.ResponsiveEmbed)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>ResponsiveEmbed ()](#apidoc.element.react-bootstrap.ResponsiveEmbed.ResponsiveEmbed)
1.  object <span class="apidocSignatureSpan">react-bootstrap.ResponsiveEmbed.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.ResponsiveEmbed.</span>propTypes

#### [module react-bootstrap.ResponsiveEmbed.propTypes](#apidoc.module.react-bootstrap.ResponsiveEmbed.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ResponsiveEmbed.propTypes.</span>a16by9 ()](#apidoc.element.react-bootstrap.ResponsiveEmbed.propTypes.a16by9)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ResponsiveEmbed.propTypes.</span>a4by3 ()](#apidoc.element.react-bootstrap.ResponsiveEmbed.propTypes.a4by3)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ResponsiveEmbed.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.ResponsiveEmbed.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ResponsiveEmbed.propTypes.</span>children ()](#apidoc.element.react-bootstrap.ResponsiveEmbed.propTypes.children)

#### [module react-bootstrap.ResponsiveEmbed.prototype](#apidoc.module.react-bootstrap.ResponsiveEmbed.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.ResponsiveEmbed.prototype.</span>render ()](#apidoc.element.react-bootstrap.ResponsiveEmbed.prototype.render)

#### [module react-bootstrap.Row](#apidoc.module.react-bootstrap.Row)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Row ()](#apidoc.element.react-bootstrap.Row.Row)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Row.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Row.</span>propTypes

#### [module react-bootstrap.Row.propTypes](#apidoc.module.react-bootstrap.Row.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Row.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Row.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Row.propTypes.</span>componentClass ()](#apidoc.element.react-bootstrap.Row.propTypes.componentClass)

#### [module react-bootstrap.Row.prototype](#apidoc.module.react-bootstrap.Row.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Row.prototype.</span>render ()](#apidoc.element.react-bootstrap.Row.prototype.render)

#### [module react-bootstrap.SafeAnchor](#apidoc.module.react-bootstrap.SafeAnchor)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>SafeAnchor (props, context)](#apidoc.element.react-bootstrap.SafeAnchor.SafeAnchor)
1.  object <span class="apidocSignatureSpan">react-bootstrap.SafeAnchor.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.SafeAnchor.</span>propTypes

#### [module react-bootstrap.SafeAnchor.propTypes](#apidoc.module.react-bootstrap.SafeAnchor.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.SafeAnchor.propTypes.</span>componentClass ()](#apidoc.element.react-bootstrap.SafeAnchor.propTypes.componentClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.SafeAnchor.propTypes.</span>disabled ()](#apidoc.element.react-bootstrap.SafeAnchor.propTypes.disabled)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.SafeAnchor.propTypes.</span>href ()](#apidoc.element.react-bootstrap.SafeAnchor.propTypes.href)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.SafeAnchor.propTypes.</span>onClick ()](#apidoc.element.react-bootstrap.SafeAnchor.propTypes.onClick)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.SafeAnchor.propTypes.</span>role ()](#apidoc.element.react-bootstrap.SafeAnchor.propTypes.role)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.SafeAnchor.propTypes.</span>tabIndex ()](#apidoc.element.react-bootstrap.SafeAnchor.propTypes.tabIndex)

#### [module react-bootstrap.SafeAnchor.prototype](#apidoc.module.react-bootstrap.SafeAnchor.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.SafeAnchor.prototype.</span>handleClick (event)](#apidoc.element.react-bootstrap.SafeAnchor.prototype.handleClick)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.SafeAnchor.prototype.</span>render ()](#apidoc.element.react-bootstrap.SafeAnchor.prototype.render)

#### [module react-bootstrap.SplitButton](#apidoc.module.react-bootstrap.SplitButton)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>SplitButton ()](#apidoc.element.react-bootstrap.SplitButton.SplitButton)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.SplitButton.</span>Toggle ()](#apidoc.element.react-bootstrap.SplitButton.Toggle)
1.  object <span class="apidocSignatureSpan">react-bootstrap.SplitButton.</span>propTypes

#### [module react-bootstrap.SplitButton.Toggle](#apidoc.module.react-bootstrap.SplitButton.Toggle)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.SplitButton.</span>Toggle ()](#apidoc.element.react-bootstrap.SplitButton.Toggle.Toggle)
1.  object <span class="apidocSignatureSpan">react-bootstrap.SplitButton.Toggle.</span>defaultProps

#### [module react-bootstrap.SplitButton.Toggle.prototype](#apidoc.module.react-bootstrap.SplitButton.Toggle.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.SplitButton.Toggle.prototype.</span>render ()](#apidoc.element.react-bootstrap.SplitButton.Toggle.prototype.render)

#### [module react-bootstrap.SplitButton.propTypes](#apidoc.module.react-bootstrap.SplitButton.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.SplitButton.propTypes.</span>bsSize ()](#apidoc.element.react-bootstrap.SplitButton.propTypes.bsSize)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.SplitButton.propTypes.</span>bsStyle ()](#apidoc.element.react-bootstrap.SplitButton.propTypes.bsStyle)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.SplitButton.propTypes.</span>children ()](#apidoc.element.react-bootstrap.SplitButton.propTypes.children)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.SplitButton.propTypes.</span>href ()](#apidoc.element.react-bootstrap.SplitButton.propTypes.href)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.SplitButton.propTypes.</span>onClick ()](#apidoc.element.react-bootstrap.SplitButton.propTypes.onClick)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.SplitButton.propTypes.</span>open (props, propName)](#apidoc.element.react-bootstrap.SplitButton.propTypes.open)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.SplitButton.propTypes.</span>title ()](#apidoc.element.react-bootstrap.SplitButton.propTypes.title)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.SplitButton.propTypes.</span>toggleLabel ()](#apidoc.element.react-bootstrap.SplitButton.propTypes.toggleLabel)

#### [module react-bootstrap.SplitButton.prototype](#apidoc.module.react-bootstrap.SplitButton.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.SplitButton.prototype.</span>render ()](#apidoc.element.react-bootstrap.SplitButton.prototype.render)

#### [module react-bootstrap.Tab](#apidoc.module.react-bootstrap.Tab)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Tab ()](#apidoc.element.react-bootstrap.Tab.Tab)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tab.</span>Container (props, context, updater)](#apidoc.element.react-bootstrap.Tab.Container)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tab.</span>Content (props, context)](#apidoc.element.react-bootstrap.Tab.Content)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tab.</span>Pane (props, context)](#apidoc.element.react-bootstrap.Tab.Pane)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Tab.</span>propTypes

#### [module react-bootstrap.Tab.propTypes](#apidoc.module.react-bootstrap.Tab.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>animation ()](#apidoc.element.react-bootstrap.Tab.propTypes.animation)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>aria-labelledby ()](#apidoc.element.react-bootstrap.Tab.propTypes.aria-labelledby)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Tab.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>disabled ()](#apidoc.element.react-bootstrap.Tab.propTypes.disabled)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>eventKey ()](#apidoc.element.react-bootstrap.Tab.propTypes.eventKey)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>id ()](#apidoc.element.react-bootstrap.Tab.propTypes.id)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>mountOnEnter ()](#apidoc.element.react-bootstrap.Tab.propTypes.mountOnEnter)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>onEnter ()](#apidoc.element.react-bootstrap.Tab.propTypes.onEnter)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>onEntered ()](#apidoc.element.react-bootstrap.Tab.propTypes.onEntered)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>onEntering ()](#apidoc.element.react-bootstrap.Tab.propTypes.onEntering)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>onExit ()](#apidoc.element.react-bootstrap.Tab.propTypes.onExit)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>onExited ()](#apidoc.element.react-bootstrap.Tab.propTypes.onExited)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>onExiting ()](#apidoc.element.react-bootstrap.Tab.propTypes.onExiting)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>tabClassName ()](#apidoc.element.react-bootstrap.Tab.propTypes.tabClassName)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>title ()](#apidoc.element.react-bootstrap.Tab.propTypes.title)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>unmountOnExit ()](#apidoc.element.react-bootstrap.Tab.propTypes.unmountOnExit)

#### [module react-bootstrap.Tab.prototype](#apidoc.module.react-bootstrap.Tab.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tab.prototype.</span>render ()](#apidoc.element.react-bootstrap.Tab.prototype.render)

#### [module react-bootstrap.TabContainer](#apidoc.module.react-bootstrap.TabContainer)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>TabContainer (props, context, updater)](#apidoc.element.react-bootstrap.TabContainer.TabContainer)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabContainer.</span>ControlledComponent ()](#apidoc.element.react-bootstrap.TabContainer.ControlledComponent)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabContainer.</span>deferControlTo (newComponent)](#apidoc.element.react-bootstrap.TabContainer.deferControlTo)
1.  object <span class="apidocSignatureSpan">react-bootstrap.TabContainer.</span>propTypes
1.  string <span class="apidocSignatureSpan">react-bootstrap.TabContainer.</span>displayName

#### [module react-bootstrap.TabContainer.ControlledComponent](#apidoc.module.react-bootstrap.TabContainer.ControlledComponent)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabContainer.</span>ControlledComponent ()](#apidoc.element.react-bootstrap.TabContainer.ControlledComponent.ControlledComponent)
1.  object <span class="apidocSignatureSpan">react-bootstrap.TabContainer.ControlledComponent.</span>childContextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.TabContainer.ControlledComponent.</span>propTypes

#### [module react-bootstrap.TabContainer.ControlledComponent.prototype](#apidoc.module.react-bootstrap.TabContainer.ControlledComponent.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabContainer.ControlledComponent.prototype.</span>getChildContext ()](#apidoc.element.react-bootstrap.TabContainer.ControlledComponent.prototype.getChildContext)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabContainer.ControlledComponent.prototype.</span>render ()](#apidoc.element.react-bootstrap.TabContainer.ControlledComponent.prototype.render)

#### [module react-bootstrap.TabContainer.propTypes](#apidoc.module.react-bootstrap.TabContainer.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabContainer.propTypes.</span>activeKey (props, propName)](#apidoc.element.react-bootstrap.TabContainer.propTypes.activeKey)

#### [module react-bootstrap.TabContainer.prototype](#apidoc.module.react-bootstrap.TabContainer.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabContainer.prototype.</span>componentWillMount ()](#apidoc.element.react-bootstrap.TabContainer.prototype.componentWillMount)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabContainer.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.react-bootstrap.TabContainer.prototype.componentWillReceiveProps)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabContainer.prototype.</span>constructor (props, context, updater)](#apidoc.element.react-bootstrap.TabContainer.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabContainer.prototype.</span>getControlledInstance ()](#apidoc.element.react-bootstrap.TabContainer.prototype.getControlledInstance)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabContainer.prototype.</span>render ()](#apidoc.element.react-bootstrap.TabContainer.prototype.render)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabContainer.prototype.</span>shouldComponentUpdate ()](#apidoc.element.react-bootstrap.TabContainer.prototype.shouldComponentUpdate)
1.  object <span class="apidocSignatureSpan">react-bootstrap.TabContainer.prototype.</span>__reactAutoBindPairs
1.  object <span class="apidocSignatureSpan">react-bootstrap.TabContainer.prototype.</span>childContextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.TabContainer.prototype.</span>componentDidMount
1.  object <span class="apidocSignatureSpan">react-bootstrap.TabContainer.prototype.</span>componentDidUpdate
1.  object <span class="apidocSignatureSpan">react-bootstrap.TabContainer.prototype.</span>componentWillUnmount
1.  object <span class="apidocSignatureSpan">react-bootstrap.TabContainer.prototype.</span>componentWillUpdate
1.  object <span class="apidocSignatureSpan">react-bootstrap.TabContainer.prototype.</span>contextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.TabContainer.prototype.</span>getChildContext
1.  object <span class="apidocSignatureSpan">react-bootstrap.TabContainer.prototype.</span>getDefaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.TabContainer.prototype.</span>getInitialState
1.  object <span class="apidocSignatureSpan">react-bootstrap.TabContainer.prototype.</span>mixins
1.  object <span class="apidocSignatureSpan">react-bootstrap.TabContainer.prototype.</span>propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.TabContainer.prototype.</span>statics
1.  object <span class="apidocSignatureSpan">react-bootstrap.TabContainer.prototype.</span>updateComponent

#### [module react-bootstrap.TabContainer.prototype.__reactAutoBindPairs](#apidoc.module.react-bootstrap.TabContainer.prototype.__reactAutoBindPairs)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabContainer.prototype.__reactAutoBindPairs.</span>1 ()](#apidoc.element.react-bootstrap.TabContainer.prototype.__reactAutoBindPairs.1)
1.  string <span class="apidocSignatureSpan">react-bootstrap.TabContainer.prototype.__reactAutoBindPairs.</span>0

#### [module react-bootstrap.TabContent](#apidoc.module.react-bootstrap.TabContent)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>TabContent (props, context)](#apidoc.element.react-bootstrap.TabContent.TabContent)
1.  object <span class="apidocSignatureSpan">react-bootstrap.TabContent.</span>childContextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.TabContent.</span>contextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.TabContent.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.TabContent.</span>propTypes

#### [module react-bootstrap.TabContent.childContextTypes](#apidoc.module.react-bootstrap.TabContent.childContextTypes)

#### [module react-bootstrap.TabContent.contextTypes](#apidoc.module.react-bootstrap.TabContent.contextTypes)

#### [module react-bootstrap.TabContent.propTypes](#apidoc.module.react-bootstrap.TabContent.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabContent.propTypes.</span>animation ()](#apidoc.element.react-bootstrap.TabContent.propTypes.animation)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabContent.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.TabContent.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabContent.propTypes.</span>componentClass ()](#apidoc.element.react-bootstrap.TabContent.propTypes.componentClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabContent.propTypes.</span>mountOnEnter ()](#apidoc.element.react-bootstrap.TabContent.propTypes.mountOnEnter)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabContent.propTypes.</span>unmountOnExit ()](#apidoc.element.react-bootstrap.TabContent.propTypes.unmountOnExit)

#### [module react-bootstrap.TabContent.prototype](#apidoc.module.react-bootstrap.TabContent.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabContent.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.react-bootstrap.TabContent.prototype.componentWillReceiveProps)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabContent.prototype.</span>componentWillUnmount ()](#apidoc.element.react-bootstrap.TabContent.prototype.componentWillUnmount)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabContent.prototype.</span>getChildContext ()](#apidoc.element.react-bootstrap.TabContent.prototype.getChildContext)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabContent.prototype.</span>getContainerActiveKey ()](#apidoc.element.react-bootstrap.TabContent.prototype.getContainerActiveKey)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabContent.prototype.</span>handlePaneEnter (child, childKey)](#apidoc.element.react-bootstrap.TabContent.prototype.handlePaneEnter)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabContent.prototype.</span>handlePaneExited (child)](#apidoc.element.react-bootstrap.TabContent.prototype.handlePaneExited)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabContent.prototype.</span>render ()](#apidoc.element.react-bootstrap.TabContent.prototype.render)

#### [module react-bootstrap.TabPane](#apidoc.module.react-bootstrap.TabPane)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>TabPane (props, context)](#apidoc.element.react-bootstrap.TabPane.TabPane)
1.  object <span class="apidocSignatureSpan">react-bootstrap.TabPane.</span>childContextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.TabPane.</span>contextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.TabPane.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.TabPane.</span>propTypes

#### [module react-bootstrap.TabPane.childContextTypes](#apidoc.module.react-bootstrap.TabPane.childContextTypes)

#### [module react-bootstrap.TabPane.contextTypes](#apidoc.module.react-bootstrap.TabPane.contextTypes)

#### [module react-bootstrap.TabPane.propTypes](#apidoc.module.react-bootstrap.TabPane.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabPane.propTypes.</span>animation ()](#apidoc.element.react-bootstrap.TabPane.propTypes.animation)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabPane.propTypes.</span>aria-labelledby ()](#apidoc.element.react-bootstrap.TabPane.propTypes.aria-labelledby)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabPane.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.TabPane.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabPane.propTypes.</span>eventKey ()](#apidoc.element.react-bootstrap.TabPane.propTypes.eventKey)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabPane.propTypes.</span>id ()](#apidoc.element.react-bootstrap.TabPane.propTypes.id)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabPane.propTypes.</span>mountOnEnter ()](#apidoc.element.react-bootstrap.TabPane.propTypes.mountOnEnter)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabPane.propTypes.</span>onEnter ()](#apidoc.element.react-bootstrap.TabPane.propTypes.onEnter)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabPane.propTypes.</span>onEntered ()](#apidoc.element.react-bootstrap.TabPane.propTypes.onEntered)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabPane.propTypes.</span>onEntering ()](#apidoc.element.react-bootstrap.TabPane.propTypes.onEntering)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabPane.propTypes.</span>onExit ()](#apidoc.element.react-bootstrap.TabPane.propTypes.onExit)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabPane.propTypes.</span>onExited ()](#apidoc.element.react-bootstrap.TabPane.propTypes.onExited)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabPane.propTypes.</span>onExiting ()](#apidoc.element.react-bootstrap.TabPane.propTypes.onExiting)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabPane.propTypes.</span>unmountOnExit ()](#apidoc.element.react-bootstrap.TabPane.propTypes.unmountOnExit)

#### [module react-bootstrap.TabPane.prototype](#apidoc.module.react-bootstrap.TabPane.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabPane.prototype.</span>componentDidMount ()](#apidoc.element.react-bootstrap.TabPane.prototype.componentDidMount)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabPane.prototype.</span>componentDidUpdate ()](#apidoc.element.react-bootstrap.TabPane.prototype.componentDidUpdate)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabPane.prototype.</span>componentWillUnmount ()](#apidoc.element.react-bootstrap.TabPane.prototype.componentWillUnmount)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabPane.prototype.</span>getAnimation ()](#apidoc.element.react-bootstrap.TabPane.prototype.getAnimation)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabPane.prototype.</span>getChildContext ()](#apidoc.element.react-bootstrap.TabPane.prototype.getChildContext)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabPane.prototype.</span>handleEnter ()](#apidoc.element.react-bootstrap.TabPane.prototype.handleEnter)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabPane.prototype.</span>handleExited ()](#apidoc.element.react-bootstrap.TabPane.prototype.handleExited)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabPane.prototype.</span>isActive ()](#apidoc.element.react-bootstrap.TabPane.prototype.isActive)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabPane.prototype.</span>render ()](#apidoc.element.react-bootstrap.TabPane.prototype.render)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.TabPane.prototype.</span>shouldBeIn ()](#apidoc.element.react-bootstrap.TabPane.prototype.shouldBeIn)

#### [module react-bootstrap.Table](#apidoc.module.react-bootstrap.Table)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Table ()](#apidoc.element.react-bootstrap.Table.Table)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Table.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Table.</span>propTypes

#### [module react-bootstrap.Table.propTypes](#apidoc.module.react-bootstrap.Table.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Table.propTypes.</span>bordered ()](#apidoc.element.react-bootstrap.Table.propTypes.bordered)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Table.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Table.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Table.propTypes.</span>condensed ()](#apidoc.element.react-bootstrap.Table.propTypes.condensed)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Table.propTypes.</span>hover ()](#apidoc.element.react-bootstrap.Table.propTypes.hover)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Table.propTypes.</span>responsive ()](#apidoc.element.react-bootstrap.Table.propTypes.responsive)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Table.propTypes.</span>striped ()](#apidoc.element.react-bootstrap.Table.propTypes.striped)

#### [module react-bootstrap.Table.prototype](#apidoc.module.react-bootstrap.Table.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Table.prototype.</span>render ()](#apidoc.element.react-bootstrap.Table.prototype.render)

#### [module react-bootstrap.Tabs](#apidoc.module.react-bootstrap.Tabs)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Tabs (props, context, updater)](#apidoc.element.react-bootstrap.Tabs.Tabs)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tabs.</span>ControlledComponent ()](#apidoc.element.react-bootstrap.Tabs.ControlledComponent)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tabs.</span>deferControlTo (newComponent)](#apidoc.element.react-bootstrap.Tabs.deferControlTo)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Tabs.</span>propTypes
1.  string <span class="apidocSignatureSpan">react-bootstrap.Tabs.</span>displayName

#### [module react-bootstrap.Tabs.ControlledComponent](#apidoc.module.react-bootstrap.Tabs.ControlledComponent)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tabs.</span>ControlledComponent ()](#apidoc.element.react-bootstrap.Tabs.ControlledComponent.ControlledComponent)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Tabs.ControlledComponent.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Tabs.ControlledComponent.</span>propTypes

#### [module react-bootstrap.Tabs.ControlledComponent.prototype](#apidoc.module.react-bootstrap.Tabs.ControlledComponent.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tabs.ControlledComponent.prototype.</span>render ()](#apidoc.element.react-bootstrap.Tabs.ControlledComponent.prototype.render)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tabs.ControlledComponent.prototype.</span>renderTab (child)](#apidoc.element.react-bootstrap.Tabs.ControlledComponent.prototype.renderTab)

#### [module react-bootstrap.Tabs.propTypes](#apidoc.module.react-bootstrap.Tabs.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tabs.propTypes.</span>activeKey (props, propName)](#apidoc.element.react-bootstrap.Tabs.propTypes.activeKey)

#### [module react-bootstrap.Tabs.prototype](#apidoc.module.react-bootstrap.Tabs.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tabs.prototype.</span>componentWillMount ()](#apidoc.element.react-bootstrap.Tabs.prototype.componentWillMount)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tabs.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.react-bootstrap.Tabs.prototype.componentWillReceiveProps)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tabs.prototype.</span>constructor (props, context, updater)](#apidoc.element.react-bootstrap.Tabs.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tabs.prototype.</span>getControlledInstance ()](#apidoc.element.react-bootstrap.Tabs.prototype.getControlledInstance)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tabs.prototype.</span>render ()](#apidoc.element.react-bootstrap.Tabs.prototype.render)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tabs.prototype.</span>shouldComponentUpdate ()](#apidoc.element.react-bootstrap.Tabs.prototype.shouldComponentUpdate)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Tabs.prototype.</span>__reactAutoBindPairs
1.  object <span class="apidocSignatureSpan">react-bootstrap.Tabs.prototype.</span>childContextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.Tabs.prototype.</span>componentDidMount
1.  object <span class="apidocSignatureSpan">react-bootstrap.Tabs.prototype.</span>componentDidUpdate
1.  object <span class="apidocSignatureSpan">react-bootstrap.Tabs.prototype.</span>componentWillUnmount
1.  object <span class="apidocSignatureSpan">react-bootstrap.Tabs.prototype.</span>componentWillUpdate
1.  object <span class="apidocSignatureSpan">react-bootstrap.Tabs.prototype.</span>contextTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.Tabs.prototype.</span>getChildContext
1.  object <span class="apidocSignatureSpan">react-bootstrap.Tabs.prototype.</span>getDefaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Tabs.prototype.</span>getInitialState
1.  object <span class="apidocSignatureSpan">react-bootstrap.Tabs.prototype.</span>mixins
1.  object <span class="apidocSignatureSpan">react-bootstrap.Tabs.prototype.</span>propTypes
1.  object <span class="apidocSignatureSpan">react-bootstrap.Tabs.prototype.</span>statics
1.  object <span class="apidocSignatureSpan">react-bootstrap.Tabs.prototype.</span>updateComponent

#### [module react-bootstrap.Tabs.prototype.__reactAutoBindPairs](#apidoc.module.react-bootstrap.Tabs.prototype.__reactAutoBindPairs)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tabs.prototype.__reactAutoBindPairs.</span>1 ()](#apidoc.element.react-bootstrap.Tabs.prototype.__reactAutoBindPairs.1)
1.  string <span class="apidocSignatureSpan">react-bootstrap.Tabs.prototype.__reactAutoBindPairs.</span>0

#### [module react-bootstrap.Thumbnail](#apidoc.module.react-bootstrap.Thumbnail)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Thumbnail ()](#apidoc.element.react-bootstrap.Thumbnail.Thumbnail)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Thumbnail.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Thumbnail.</span>propTypes

#### [module react-bootstrap.Thumbnail.propTypes](#apidoc.module.react-bootstrap.Thumbnail.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Thumbnail.propTypes.</span>alt ()](#apidoc.element.react-bootstrap.Thumbnail.propTypes.alt)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Thumbnail.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Thumbnail.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Thumbnail.propTypes.</span>href ()](#apidoc.element.react-bootstrap.Thumbnail.propTypes.href)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Thumbnail.propTypes.</span>src ()](#apidoc.element.react-bootstrap.Thumbnail.propTypes.src)

#### [module react-bootstrap.Thumbnail.prototype](#apidoc.module.react-bootstrap.Thumbnail.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Thumbnail.prototype.</span>render ()](#apidoc.element.react-bootstrap.Thumbnail.prototype.render)

#### [module react-bootstrap.Tooltip](#apidoc.module.react-bootstrap.Tooltip)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Tooltip ()](#apidoc.element.react-bootstrap.Tooltip.Tooltip)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Tooltip.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Tooltip.</span>propTypes

#### [module react-bootstrap.Tooltip.propTypes](#apidoc.module.react-bootstrap.Tooltip.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tooltip.propTypes.</span>arrowOffsetLeft ()](#apidoc.element.react-bootstrap.Tooltip.propTypes.arrowOffsetLeft)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tooltip.propTypes.</span>arrowOffsetTop ()](#apidoc.element.react-bootstrap.Tooltip.propTypes.arrowOffsetTop)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tooltip.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Tooltip.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tooltip.propTypes.</span>id (props, propName, componentName, location, propFullName)](#apidoc.element.react-bootstrap.Tooltip.propTypes.id)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tooltip.propTypes.</span>placement ()](#apidoc.element.react-bootstrap.Tooltip.propTypes.placement)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tooltip.propTypes.</span>positionLeft ()](#apidoc.element.react-bootstrap.Tooltip.propTypes.positionLeft)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tooltip.propTypes.</span>positionTop ()](#apidoc.element.react-bootstrap.Tooltip.propTypes.positionTop)

#### [module react-bootstrap.Tooltip.prototype](#apidoc.module.react-bootstrap.Tooltip.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Tooltip.prototype.</span>render ()](#apidoc.element.react-bootstrap.Tooltip.prototype.render)

#### [module react-bootstrap.Well](#apidoc.module.react-bootstrap.Well)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.</span>Well ()](#apidoc.element.react-bootstrap.Well.Well)
1.  object <span class="apidocSignatureSpan">react-bootstrap.Well.</span>SIZES
1.  object <span class="apidocSignatureSpan">react-bootstrap.Well.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-bootstrap.Well.</span>propTypes

#### [module react-bootstrap.Well.propTypes](#apidoc.module.react-bootstrap.Well.propTypes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Well.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Well.propTypes.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Well.propTypes.</span>bsSize ()](#apidoc.element.react-bootstrap.Well.propTypes.bsSize)

#### [module react-bootstrap.Well.prototype](#apidoc.module.react-bootstrap.Well.prototype)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.Well.prototype.</span>render ()](#apidoc.element.react-bootstrap.Well.prototype.render)

#### [module react-bootstrap.utils](#apidoc.module.react-bootstrap.utils)
1.  boolean <span class="apidocSignatureSpan">react-bootstrap.utils.</span>__esModule
1.  [function <span class="apidocSignatureSpan">react-bootstrap.utils.</span>createChainedFunction ()](#apidoc.element.react-bootstrap.utils.createChainedFunction)
1.  object <span class="apidocSignatureSpan">react-bootstrap.utils.</span>ValidComponentChildren
1.  object <span class="apidocSignatureSpan">react-bootstrap.utils.</span>bootstrapUtils

#### [module react-bootstrap.utils.ValidComponentChildren](#apidoc.module.react-bootstrap.utils.ValidComponentChildren)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.utils.ValidComponentChildren.</span>count (children)](#apidoc.element.react-bootstrap.utils.ValidComponentChildren.count)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.utils.ValidComponentChildren.</span>every (children, func, context)](#apidoc.element.react-bootstrap.utils.ValidComponentChildren.every)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.utils.ValidComponentChildren.</span>filter (children, func, context)](#apidoc.element.react-bootstrap.utils.ValidComponentChildren.filter)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.utils.ValidComponentChildren.</span>find (children, func, context)](#apidoc.element.react-bootstrap.utils.ValidComponentChildren.find)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.utils.ValidComponentChildren.</span>forEach (children, func, context)](#apidoc.element.react-bootstrap.utils.ValidComponentChildren.forEach)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.utils.ValidComponentChildren.</span>map (children, func, context)](#apidoc.element.react-bootstrap.utils.ValidComponentChildren.map)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.utils.ValidComponentChildren.</span>some (children, func, context)](#apidoc.element.react-bootstrap.utils.ValidComponentChildren.some)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.utils.ValidComponentChildren.</span>toArray (children)](#apidoc.element.react-bootstrap.utils.ValidComponentChildren.toArray)

#### [module react-bootstrap.utils.bootstrapUtils](#apidoc.module.react-bootstrap.utils.bootstrapUtils)
1.  boolean <span class="apidocSignatureSpan">react-bootstrap.utils.bootstrapUtils.</span>__esModule
1.  [function <span class="apidocSignatureSpan">react-bootstrap.utils.bootstrapUtils.</span>_curry (fn)](#apidoc.element.react-bootstrap.utils.bootstrapUtils._curry)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.utils.bootstrapUtils.</span>addStyle (Component)](#apidoc.element.react-bootstrap.utils.bootstrapUtils.addStyle)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.utils.bootstrapUtils.</span>bsClass ()](#apidoc.element.react-bootstrap.utils.bootstrapUtils.bsClass)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.utils.bootstrapUtils.</span>bsSizes ()](#apidoc.element.react-bootstrap.utils.bootstrapUtils.bsSizes)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.utils.bootstrapUtils.</span>bsStyles ()](#apidoc.element.react-bootstrap.utils.bootstrapUtils.bsStyles)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.utils.bootstrapUtils.</span>getClassSet (props)](#apidoc.element.react-bootstrap.utils.bootstrapUtils.getClassSet)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.utils.bootstrapUtils.</span>prefix (props, variant)](#apidoc.element.react-bootstrap.utils.bootstrapUtils.prefix)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.utils.bootstrapUtils.</span>splitBsProps (props)](#apidoc.element.react-bootstrap.utils.bootstrapUtils.splitBsProps)
1.  [function <span class="apidocSignatureSpan">react-bootstrap.utils.bootstrapUtils.</span>splitBsPropsAndOmit (props, omittedPropNames)](#apidoc.element.react-bootstrap.utils.bootstrapUtils.splitBsPropsAndOmit)



# <a name="apidoc.module.react-bootstrap"></a>[module react-bootstrap](#apidoc.module.react-bootstrap)

#### <a name="apidoc.element.react-bootstrap.Accordion"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Accordion ()](#apidoc.element.react-bootstrap.Accordion)
- description and source-code
```javascript
function Accordion() {
  (0, _classCallCheck3['default'])(this, Accordion);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Alert"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Alert ()](#apidoc.element.react-bootstrap.Alert)
- description and source-code
```javascript
function Alert() {
  (0, _classCallCheck3['default'])(this, Alert);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Badge"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Badge ()](#apidoc.element.react-bootstrap.Badge)
- description and source-code
```javascript
function Badge() {
  (0, _classCallCheck3['default'])(this, Badge);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Breadcrumb"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Breadcrumb ()](#apidoc.element.react-bootstrap.Breadcrumb)
- description and source-code
```javascript
function Breadcrumb() {
  (0, _classCallCheck3['default'])(this, Breadcrumb);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.BreadcrumbItem"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>BreadcrumbItem ()](#apidoc.element.react-bootstrap.BreadcrumbItem)
- description and source-code
```javascript
function BreadcrumbItem() {
  (0, _classCallCheck3['default'])(this, BreadcrumbItem);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Button"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Button ()](#apidoc.element.react-bootstrap.Button)
- description and source-code
```javascript
function Button() {
  (0, _classCallCheck3['default'])(this, Button);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ButtonGroup"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>ButtonGroup ()](#apidoc.element.react-bootstrap.ButtonGroup)
- description and source-code
```javascript
function ButtonGroup() {
  (0, _classCallCheck3['default'])(this, ButtonGroup);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ButtonToolbar"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>ButtonToolbar ()](#apidoc.element.react-bootstrap.ButtonToolbar)
- description and source-code
```javascript
function ButtonToolbar() {
  (0, _classCallCheck3['default'])(this, ButtonToolbar);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Carousel (props, context)](#apidoc.element.react-bootstrap.Carousel)
- description and source-code
```javascript
function Carousel(props, context) {
  (0, _classCallCheck3['default'])(this, Carousel);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleMouseOver = _this.handleMouseOver.bind(_this);
  _this.handleMouseOut = _this.handleMouseOut.bind(_this);
  _this.handlePrev = _this.handlePrev.bind(_this);
  _this.handleNext = _this.handleNext.bind(_this);
  _this.handleItemAnimateOutEnd = _this.handleItemAnimateOutEnd.bind(_this);

  var defaultActiveIndex = props.defaultActiveIndex;


  _this.state = {
    activeIndex: defaultActiveIndex != null ? defaultActiveIndex : 0,
    previousActiveIndex: null,
    direction: null
  };

  _this.isUnmounted = false;
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.Caption"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Carousel.Caption ()](#apidoc.element.react-bootstrap.Carousel.Caption)
- description and source-code
```javascript
function CarouselCaption() {
  (0, _classCallCheck3['default'])(this, CarouselCaption);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.CarouselItem"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>CarouselItem (props, context)](#apidoc.element.react-bootstrap.CarouselItem)
- description and source-code
```javascript
function CarouselItem(props, context) {
  (0, _classCallCheck3['default'])(this, CarouselItem);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleAnimateOutEnd = _this.handleAnimateOutEnd.bind(_this);

  _this.state = {
    direction: null
  };

  _this.isUnmounted = false;
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Checkbox"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Checkbox ()](#apidoc.element.react-bootstrap.Checkbox)
- description and source-code
```javascript
function Checkbox() {
  (0, _classCallCheck3['default'])(this, Checkbox);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Clearfix"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Clearfix ()](#apidoc.element.react-bootstrap.Clearfix)
- description and source-code
```javascript
function Clearfix() {
  (0, _classCallCheck3['default'])(this, Clearfix);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Col"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Col ()](#apidoc.element.react-bootstrap.Col)
- description and source-code
```javascript
function Col() {
  (0, _classCallCheck3['default'])(this, Col);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Collapse"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Collapse (props, context)](#apidoc.element.react-bootstrap.Collapse)
- description and source-code
```javascript
function Collapse(props, context) {
  (0, _classCallCheck3['default'])(this, Collapse);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleEnter = _this.handleEnter.bind(_this);
  _this.handleEntering = _this.handleEntering.bind(_this);
  _this.handleEntered = _this.handleEntered.bind(_this);
  _this.handleExit = _this.handleExit.bind(_this);
  _this.handleExiting = _this.handleExiting.bind(_this);
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ControlLabel"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>ControlLabel ()](#apidoc.element.react-bootstrap.ControlLabel)
- description and source-code
```javascript
function ControlLabel() {
  (0, _classCallCheck3['default'])(this, ControlLabel);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Dropdown"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Dropdown (props, context, updater)](#apidoc.element.react-bootstrap.Dropdown)
- description and source-code
```javascript
Dropdown = function (props, context, updater) {
  // This constructor gets overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : void 0;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindPairs.length) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (initialState === undefined && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : _prodInvariant('82',
Constructor.displayName || 'ReactCompositeComponent') : void 0;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Dropdown.ControlledComponent"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Dropdown.ControlledComponent (props, context)](#apidoc.element.react-bootstrap.Dropdown.ControlledComponent)
- description and source-code
```javascript
function Dropdown(props, context) {
  (0, _classCallCheck3['default'])(this, Dropdown);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleClick = _this.handleClick.bind(_this);
  _this.handleKeyDown = _this.handleKeyDown.bind(_this);
  _this.handleClose = _this.handleClose.bind(_this);

  _this._focusInDropdown = false;
  _this.lastOpenEventType = null;
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Dropdown.Menu"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Dropdown.Menu (props)](#apidoc.element.react-bootstrap.Dropdown.Menu)
- description and source-code
```javascript
function DropdownMenu(props) {
  (0, _classCallCheck3['default'])(this, DropdownMenu);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props));

  _this.handleRootClose = _this.handleRootClose.bind(_this);
  _this.handleKeyDown = _this.handleKeyDown.bind(_this);
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Dropdown.Toggle"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Dropdown.Toggle ()](#apidoc.element.react-bootstrap.Dropdown.Toggle)
- description and source-code
```javascript
function DropdownToggle() {
  (0, _classCallCheck3['default'])(this, DropdownToggle);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.DropdownButton"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>DropdownButton ()](#apidoc.element.react-bootstrap.DropdownButton)
- description and source-code
```javascript
function DropdownButton() {
  (0, _classCallCheck3['default'])(this, DropdownButton);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Fade"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Fade ()](#apidoc.element.react-bootstrap.Fade)
- description and source-code
```javascript
function Fade() {
  (0, _classCallCheck3['default'])(this, Fade);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Form"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Form ()](#apidoc.element.react-bootstrap.Form)
- description and source-code
```javascript
function Form() {
  (0, _classCallCheck3['default'])(this, Form);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.FormControl"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>FormControl ()](#apidoc.element.react-bootstrap.FormControl)
- description and source-code
```javascript
function FormControl() {
  (0, _classCallCheck3['default'])(this, FormControl);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.FormControl.Feedback"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>FormControl.Feedback ()](#apidoc.element.react-bootstrap.FormControl.Feedback)
- description and source-code
```javascript
function FormControlFeedback() {
  (0, _classCallCheck3['default'])(this, FormControlFeedback);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.FormControl.Static"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>FormControl.Static ()](#apidoc.element.react-bootstrap.FormControl.Static)
- description and source-code
```javascript
function FormControlStatic() {
  (0, _classCallCheck3['default'])(this, FormControlStatic);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.FormGroup"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>FormGroup ()](#apidoc.element.react-bootstrap.FormGroup)
- description and source-code
```javascript
function FormGroup() {
  (0, _classCallCheck3['default'])(this, FormGroup);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Glyphicon"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Glyphicon ()](#apidoc.element.react-bootstrap.Glyphicon)
- description and source-code
```javascript
function Glyphicon() {
  (0, _classCallCheck3['default'])(this, Glyphicon);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Grid"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Grid ()](#apidoc.element.react-bootstrap.Grid)
- description and source-code
```javascript
function Grid() {
  (0, _classCallCheck3['default'])(this, Grid);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.HelpBlock"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>HelpBlock ()](#apidoc.element.react-bootstrap.HelpBlock)
- description and source-code
```javascript
function HelpBlock() {
  (0, _classCallCheck3['default'])(this, HelpBlock);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Image"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Image ()](#apidoc.element.react-bootstrap.Image)
- description and source-code
```javascript
function Image() {
  (0, _classCallCheck3['default'])(this, Image);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.InputGroup"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>InputGroup ()](#apidoc.element.react-bootstrap.InputGroup)
- description and source-code
```javascript
function InputGroup() {
  (0, _classCallCheck3['default'])(this, InputGroup);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.InputGroup.Addon"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>InputGroup.Addon ()](#apidoc.element.react-bootstrap.InputGroup.Addon)
- description and source-code
```javascript
function InputGroupAddon() {
  (0, _classCallCheck3['default'])(this, InputGroupAddon);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.InputGroup.Button"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>InputGroup.Button ()](#apidoc.element.react-bootstrap.InputGroup.Button)
- description and source-code
```javascript
function InputGroupButton() {
  (0, _classCallCheck3['default'])(this, InputGroupButton);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Jumbotron"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Jumbotron ()](#apidoc.element.react-bootstrap.Jumbotron)
- description and source-code
```javascript
function Jumbotron() {
  (0, _classCallCheck3['default'])(this, Jumbotron);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Label"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Label ()](#apidoc.element.react-bootstrap.Label)
- description and source-code
```javascript
function Label() {
  (0, _classCallCheck3['default'])(this, Label);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ListGroup"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>ListGroup ()](#apidoc.element.react-bootstrap.ListGroup)
- description and source-code
```javascript
function ListGroup() {
  (0, _classCallCheck3['default'])(this, ListGroup);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ListGroupItem"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>ListGroupItem ()](#apidoc.element.react-bootstrap.ListGroupItem)
- description and source-code
```javascript
function ListGroupItem() {
  (0, _classCallCheck3['default'])(this, ListGroupItem);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Media"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Media ()](#apidoc.element.react-bootstrap.Media)
- description and source-code
```javascript
function Media() {
  (0, _classCallCheck3['default'])(this, Media);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Media.Body"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Media.Body ()](#apidoc.element.react-bootstrap.Media.Body)
- description and source-code
```javascript
function MediaBody() {
  (0, _classCallCheck3['default'])(this, MediaBody);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Media.Heading"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Media.Heading ()](#apidoc.element.react-bootstrap.Media.Heading)
- description and source-code
```javascript
function MediaHeading() {
  (0, _classCallCheck3['default'])(this, MediaHeading);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Media.Left"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Media.Left ()](#apidoc.element.react-bootstrap.Media.Left)
- description and source-code
```javascript
function MediaLeft() {
  (0, _classCallCheck3['default'])(this, MediaLeft);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Media.List"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Media.List ()](#apidoc.element.react-bootstrap.Media.List)
- description and source-code
```javascript
function MediaList() {
  (0, _classCallCheck3['default'])(this, MediaList);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Media.ListItem"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Media.ListItem ()](#apidoc.element.react-bootstrap.Media.ListItem)
- description and source-code
```javascript
function MediaListItem() {
  (0, _classCallCheck3['default'])(this, MediaListItem);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Media.Right"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Media.Right ()](#apidoc.element.react-bootstrap.Media.Right)
- description and source-code
```javascript
function MediaRight() {
  (0, _classCallCheck3['default'])(this, MediaRight);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.MenuItem"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>MenuItem (props, context)](#apidoc.element.react-bootstrap.MenuItem)
- description and source-code
```javascript
function MenuItem(props, context) {
  (0, _classCallCheck3['default'])(this, MenuItem);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleClick = _this.handleClick.bind(_this);
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Modal (props, context)](#apidoc.element.react-bootstrap.Modal)
- description and source-code
```javascript
function Modal(props, context) {
  (0, _classCallCheck3['default'])(this, Modal);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleEntering = _this.handleEntering.bind(_this);
  _this.handleExited = _this.handleExited.bind(_this);
  _this.handleWindowResize = _this.handleWindowResize.bind(_this);
  _this.handleDialogClick = _this.handleDialogClick.bind(_this);

  _this.state = {
    style: {}
  };
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.Dialog"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Modal.Dialog ()](#apidoc.element.react-bootstrap.Modal.Dialog)
- description and source-code
```javascript
function ModalDialog() {
  (0, _classCallCheck3['default'])(this, ModalDialog);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ModalBody"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>ModalBody ()](#apidoc.element.react-bootstrap.ModalBody)
- description and source-code
```javascript
function ModalBody() {
  (0, _classCallCheck3['default'])(this, ModalBody);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ModalFooter"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>ModalFooter ()](#apidoc.element.react-bootstrap.ModalFooter)
- description and source-code
```javascript
function ModalFooter() {
  (0, _classCallCheck3['default'])(this, ModalFooter);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ModalHeader"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>ModalHeader ()](#apidoc.element.react-bootstrap.ModalHeader)
- description and source-code
```javascript
function ModalHeader() {
  (0, _classCallCheck3['default'])(this, ModalHeader);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ModalTitle"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>ModalTitle ()](#apidoc.element.react-bootstrap.ModalTitle)
- description and source-code
```javascript
function ModalTitle() {
  (0, _classCallCheck3['default'])(this, ModalTitle);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Nav"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Nav ()](#apidoc.element.react-bootstrap.Nav)
- description and source-code
```javascript
function Nav() {
  (0, _classCallCheck3['default'])(this, Nav);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.NavDropdown"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>NavDropdown ()](#apidoc.element.react-bootstrap.NavDropdown)
- description and source-code
```javascript
function NavDropdown() {
  (0, _classCallCheck3['default'])(this, NavDropdown);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.NavItem"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>NavItem (props, context)](#apidoc.element.react-bootstrap.NavItem)
- description and source-code
```javascript
function NavItem(props, context) {
  (0, _classCallCheck3['default'])(this, NavItem);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleClick = _this.handleClick.bind(_this);
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Navbar"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Navbar (props, context, updater)](#apidoc.element.react-bootstrap.Navbar)
- description and source-code
```javascript
Navbar = function (props, context, updater) {
  // This constructor gets overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : void 0;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindPairs.length) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (initialState === undefined && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : _prodInvariant('82',
Constructor.displayName || 'ReactCompositeComponent') : void 0;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Navbar.Collapse"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Navbar.Collapse ()](#apidoc.element.react-bootstrap.Navbar.Collapse)
- description and source-code
```javascript
function NavbarCollapse() {
  (0, _classCallCheck3['default'])(this, NavbarCollapse);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Navbar.ControlledComponent"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Navbar.ControlledComponent (props, context)](#apidoc.element.react-bootstrap.Navbar.ControlledComponent)
- description and source-code
```javascript
function Navbar(props, context) {
  (0, _classCallCheck3['default'])(this, Navbar);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleToggle = _this.handleToggle.bind(_this);
  _this.handleCollapse = _this.handleCollapse.bind(_this);
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Navbar.Header"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Navbar.Header ()](#apidoc.element.react-bootstrap.Navbar.Header)
- description and source-code
```javascript
function NavbarHeader() {
  (0, _classCallCheck3['default'])(this, NavbarHeader);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Navbar.Toggle"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Navbar.Toggle ()](#apidoc.element.react-bootstrap.Navbar.Toggle)
- description and source-code
```javascript
function NavbarToggle() {
  (0, _classCallCheck3['default'])(this, NavbarToggle);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.NavbarBrand"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>NavbarBrand ()](#apidoc.element.react-bootstrap.NavbarBrand)
- description and source-code
```javascript
function NavbarBrand() {
  (0, _classCallCheck3['default'])(this, NavbarBrand);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Overlay"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Overlay ()](#apidoc.element.react-bootstrap.Overlay)
- description and source-code
```javascript
function Overlay() {
  (0, _classCallCheck3['default'])(this, Overlay);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>OverlayTrigger (props, context)](#apidoc.element.react-bootstrap.OverlayTrigger)
- description and source-code
```javascript
function OverlayTrigger(props, context) {
  (0, _classCallCheck3['default'])(this, OverlayTrigger);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleToggle = _this.handleToggle.bind(_this);
  _this.handleDelayedShow = _this.handleDelayedShow.bind(_this);
  _this.handleDelayedHide = _this.handleDelayedHide.bind(_this);
  _this.handleHide = _this.handleHide.bind(_this);

  _this.handleMouseOver = function (e) {
    return _this.handleMouseOverOut(_this.handleDelayedShow, e);
  };
  _this.handleMouseOut = function (e) {
    return _this.handleMouseOverOut(_this.handleDelayedHide, e);
  };

  _this._mountNode = null;

  _this.state = {
    show: props.defaultOverlayShown
  };
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.PageHeader"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>PageHeader ()](#apidoc.element.react-bootstrap.PageHeader)
- description and source-code
```javascript
function PageHeader() {
  (0, _classCallCheck3['default'])(this, PageHeader);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.PageItem"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>PageItem ()](#apidoc.element.react-bootstrap.PageItem)
- description and source-code
```javascript
function DeprecatedComponent() {
  (0, _classCallCheck3['default'])(this, DeprecatedComponent);
  return (0, _possibleConstructorReturn3['default'])(this, _Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Pager"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Pager ()](#apidoc.element.react-bootstrap.Pager)
- description and source-code
```javascript
function Pager() {
  (0, _classCallCheck3['default'])(this, Pager);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Pager.Item"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Pager.Item (props, context)](#apidoc.element.react-bootstrap.Pager.Item)
- description and source-code
```javascript
function PagerItem(props, context) {
  (0, _classCallCheck3['default'])(this, PagerItem);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleSelect = _this.handleSelect.bind(_this);
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Pagination"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Pagination ()](#apidoc.element.react-bootstrap.Pagination)
- description and source-code
```javascript
function Pagination() {
  (0, _classCallCheck3['default'])(this, Pagination);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.PaginationButton"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>PaginationButton (props, context)](#apidoc.element.react-bootstrap.PaginationButton)
- description and source-code
```javascript
function PaginationButton(props, context) {
  (0, _classCallCheck3['default'])(this, PaginationButton);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleClick = _this.handleClick.bind(_this);
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Panel"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Panel (props, context)](#apidoc.element.react-bootstrap.Panel)
- description and source-code
```javascript
function Panel(props, context) {
  (0, _classCallCheck3['default'])(this, Panel);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleClickTitle = _this.handleClickTitle.bind(_this);

  _this.state = {
    expanded: _this.props.defaultExpanded
  };
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.PanelGroup"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>PanelGroup (props, context)](#apidoc.element.react-bootstrap.PanelGroup)
- description and source-code
```javascript
function PanelGroup(props, context) {
  (0, _classCallCheck3['default'])(this, PanelGroup);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleSelect = _this.handleSelect.bind(_this);

  _this.state = {
    activeKey: props.defaultActiveKey
  };
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Popover"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Popover ()](#apidoc.element.react-bootstrap.Popover)
- description and source-code
```javascript
function Popover() {
  (0, _classCallCheck3['default'])(this, Popover);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ProgressBar"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>ProgressBar ()](#apidoc.element.react-bootstrap.ProgressBar)
- description and source-code
```javascript
function ProgressBar() {
  (0, _classCallCheck3['default'])(this, ProgressBar);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Radio"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Radio ()](#apidoc.element.react-bootstrap.Radio)
- description and source-code
```javascript
function Radio() {
  (0, _classCallCheck3['default'])(this, Radio);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ResponsiveEmbed"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>ResponsiveEmbed ()](#apidoc.element.react-bootstrap.ResponsiveEmbed)
- description and source-code
```javascript
function ResponsiveEmbed() {
  (0, _classCallCheck3['default'])(this, ResponsiveEmbed);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Row"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Row ()](#apidoc.element.react-bootstrap.Row)
- description and source-code
```javascript
function Row() {
  (0, _classCallCheck3['default'])(this, Row);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.SafeAnchor"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>SafeAnchor (props, context)](#apidoc.element.react-bootstrap.SafeAnchor)
- description and source-code
```javascript
function SafeAnchor(props, context) {
  (0, _classCallCheck3['default'])(this, SafeAnchor);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleClick = _this.handleClick.bind(_this);
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.SplitButton"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>SplitButton ()](#apidoc.element.react-bootstrap.SplitButton)
- description and source-code
```javascript
function SplitButton() {
  (0, _classCallCheck3['default'])(this, SplitButton);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.SplitButton.Toggle"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>SplitButton.Toggle ()](#apidoc.element.react-bootstrap.SplitButton.Toggle)
- description and source-code
```javascript
function SplitToggle() {
  (0, _classCallCheck3['default'])(this, SplitToggle);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tab"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Tab ()](#apidoc.element.react-bootstrap.Tab)
- description and source-code
```javascript
function Tab() {
  (0, _classCallCheck3['default'])(this, Tab);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabContainer"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>TabContainer (props, context, updater)](#apidoc.element.react-bootstrap.TabContainer)
- description and source-code
```javascript
TabContainer = function (props, context, updater) {
  // This constructor gets overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : void 0;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindPairs.length) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (initialState === undefined && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : _prodInvariant('82',
Constructor.displayName || 'ReactCompositeComponent') : void 0;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabContainer.ControlledComponent"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>TabContainer.ControlledComponent ()](#apidoc.element.react-bootstrap.TabContainer.ControlledComponent)
- description and source-code
```javascript
function TabContainer() {
  (0, _classCallCheck3['default'])(this, TabContainer);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabContent"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>TabContent (props, context)](#apidoc.element.react-bootstrap.TabContent)
- description and source-code
```javascript
function TabContent(props, context) {
  (0, _classCallCheck3['default'])(this, TabContent);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handlePaneEnter = _this.handlePaneEnter.bind(_this);
  _this.handlePaneExited = _this.handlePaneExited.bind(_this);

  // Active entries in state will be 'null' unless 'animation' is set. Need
  // to track active child in case keys swap and the active child changes
  // but the active key does not.
  _this.state = {
    activeKey: null,
    activeChild: null
  };
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabPane"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>TabPane (props, context)](#apidoc.element.react-bootstrap.TabPane)
- description and source-code
```javascript
function TabPane(props, context) {
  (0, _classCallCheck3['default'])(this, TabPane);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleEnter = _this.handleEnter.bind(_this);
  _this.handleExited = _this.handleExited.bind(_this);

  _this['in'] = false;
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Table"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Table ()](#apidoc.element.react-bootstrap.Table)
- description and source-code
```javascript
function Table() {
  (0, _classCallCheck3['default'])(this, Table);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tabs"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Tabs (props, context, updater)](#apidoc.element.react-bootstrap.Tabs)
- description and source-code
```javascript
Tabs = function (props, context, updater) {
  // This constructor gets overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : void 0;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindPairs.length) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (initialState === undefined && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : _prodInvariant('82',
Constructor.displayName || 'ReactCompositeComponent') : void 0;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tabs.ControlledComponent"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Tabs.ControlledComponent ()](#apidoc.element.react-bootstrap.Tabs.ControlledComponent)
- description and source-code
```javascript
function Tabs() {
  (0, _classCallCheck3['default'])(this, Tabs);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Thumbnail"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Thumbnail ()](#apidoc.element.react-bootstrap.Thumbnail)
- description and source-code
```javascript
function Thumbnail() {
  (0, _classCallCheck3['default'])(this, Thumbnail);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tooltip"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Tooltip ()](#apidoc.element.react-bootstrap.Tooltip)
- description and source-code
```javascript
function Tooltip() {
  (0, _classCallCheck3['default'])(this, Tooltip);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Well"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Well ()](#apidoc.element.react-bootstrap.Well)
- description and source-code
```javascript
function Well() {
  (0, _classCallCheck3['default'])(this, Well);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Accordion"></a>[module react-bootstrap.Accordion](#apidoc.module.react-bootstrap.Accordion)

#### <a name="apidoc.element.react-bootstrap.Accordion.Accordion"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Accordion ()](#apidoc.element.react-bootstrap.Accordion.Accordion)
- description and source-code
```javascript
function Accordion() {
  (0, _classCallCheck3['default'])(this, Accordion);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Accordion.prototype"></a>[module react-bootstrap.Accordion.prototype](#apidoc.module.react-bootstrap.Accordion.prototype)

#### <a name="apidoc.element.react-bootstrap.Accordion.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Accordion.prototype.</span>render ()](#apidoc.element.react-bootstrap.Accordion.prototype.render)
- description and source-code
```javascript
function render() {
  return _react2['default'].createElement(
    _PanelGroup2['default'],
    (0, _extends3['default'])({}, this.props, { accordion: true }),
    this.props.children
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Alert"></a>[module react-bootstrap.Alert](#apidoc.module.react-bootstrap.Alert)

#### <a name="apidoc.element.react-bootstrap.Alert.Alert"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Alert ()](#apidoc.element.react-bootstrap.Alert.Alert)
- description and source-code
```javascript
function Alert() {
  (0, _classCallCheck3['default'])(this, Alert);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Alert.propTypes"></a>[module react-bootstrap.Alert.propTypes](#apidoc.module.react-bootstrap.Alert.propTypes)

#### <a name="apidoc.element.react-bootstrap.Alert.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Alert.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Alert.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Alert.propTypes.bsStyle"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Alert.propTypes.</span>bsStyle ()](#apidoc.element.react-bootstrap.Alert.propTypes.bsStyle)
- description and source-code
```javascript
bsStyle = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Alert.propTypes.closeLabel"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Alert.propTypes.</span>closeLabel ()](#apidoc.element.react-bootstrap.Alert.propTypes.closeLabel)
- description and source-code
```javascript
closeLabel = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Alert.propTypes.onDismiss"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Alert.propTypes.</span>onDismiss ()](#apidoc.element.react-bootstrap.Alert.propTypes.onDismiss)
- description and source-code
```javascript
onDismiss = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Alert.prototype"></a>[module react-bootstrap.Alert.prototype](#apidoc.module.react-bootstrap.Alert.prototype)

#### <a name="apidoc.element.react-bootstrap.Alert.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Alert.prototype.</span>render ()](#apidoc.element.react-bootstrap.Alert.prototype.render)
- description and source-code
```javascript
function render() {
  var _extends2;

  var _props = this.props,
      onDismiss = _props.onDismiss,
      closeLabel = _props.closeLabel,
      className = _props.className,
      children = _props.children,
      props = (0, _objectWithoutProperties3['default'])(_props, ['onDismiss', 'closeLabel', 'className', 'children']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var dismissable = !!onDismiss;
  var classes = (0, _extends4['default'])({}, (0, _bootstrapUtils.getClassSet)(bsProps), (_extends2 = {}, _extends2[(0, _bootstrapUtils
.prefix)(bsProps, 'dismissable')] = dismissable, _extends2));

  return _react2['default'].createElement(
    'div',
    (0, _extends4['default'])({}, elementProps, {
      role: 'alert',
      className: (0, _classnames2['default'])(className, classes)
    }),
    dismissable && this.renderDismissButton(onDismiss),
    children,
    dismissable && this.renderSrOnlyDismissButton(onDismiss, closeLabel)
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Alert.prototype.renderDismissButton"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Alert.prototype.</span>renderDismissButton (onDismiss)](#apidoc.element.react-bootstrap.Alert.prototype.renderDismissButton)
- description and source-code
```javascript
function renderDismissButton(onDismiss) {
  return _react2['default'].createElement(
    'button',
    {
      type: 'button',
      className: 'close',
      onClick: onDismiss,
      'aria-hidden': 'true',
      tabIndex: '-1'
    },
    _react2['default'].createElement(
      'span',
      null,
      '\xD7'
    )
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Alert.prototype.renderSrOnlyDismissButton"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Alert.prototype.</span>renderSrOnlyDismissButton (onDismiss, closeLabel)](#apidoc.element.react-bootstrap.Alert.prototype.renderSrOnlyDismissButton)
- description and source-code
```javascript
function renderSrOnlyDismissButton(onDismiss, closeLabel) {
  return _react2['default'].createElement(
    'button',
    {
      type: 'button',
      className: 'close sr-only',
      onClick: onDismiss
    },
    closeLabel
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Badge"></a>[module react-bootstrap.Badge](#apidoc.module.react-bootstrap.Badge)

#### <a name="apidoc.element.react-bootstrap.Badge.Badge"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Badge ()](#apidoc.element.react-bootstrap.Badge.Badge)
- description and source-code
```javascript
function Badge() {
  (0, _classCallCheck3['default'])(this, Badge);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Badge.propTypes"></a>[module react-bootstrap.Badge.propTypes](#apidoc.module.react-bootstrap.Badge.propTypes)

#### <a name="apidoc.element.react-bootstrap.Badge.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Badge.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Badge.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Badge.propTypes.pullRight"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Badge.propTypes.</span>pullRight ()](#apidoc.element.react-bootstrap.Badge.propTypes.pullRight)
- description and source-code
```javascript
pullRight = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Badge.prototype"></a>[module react-bootstrap.Badge.prototype](#apidoc.module.react-bootstrap.Badge.prototype)

#### <a name="apidoc.element.react-bootstrap.Badge.prototype.hasContent"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Badge.prototype.</span>hasContent (children)](#apidoc.element.react-bootstrap.Badge.prototype.hasContent)
- description and source-code
```javascript
function hasContent(children) {
  var result = false;

  _react2['default'].Children.forEach(children, function (child) {
    if (result) {
      return;
    }

    if (child || child === 0) {
      result = true;
    }
  });

  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Badge.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Badge.prototype.</span>render ()](#apidoc.element.react-bootstrap.Badge.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      pullRight = _props.pullRight,
      className = _props.className,
      children = _props.children,
      props = (0, _objectWithoutProperties3['default'])(_props, ['pullRight', 'className', 'children']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _extends3['default'])({}, (0, _bootstrapUtils.getClassSet)(bsProps), {
    'pull-right': pullRight,

    // Hack for collapsing on IE8.
    hidden: !this.hasContent(children)
  });

  return _react2['default'].createElement(
    'span',
    (0, _extends3['default'])({}, elementProps, {
      className: (0, _classnames2['default'])(className, classes)
    }),
    children
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Breadcrumb"></a>[module react-bootstrap.Breadcrumb](#apidoc.module.react-bootstrap.Breadcrumb)

#### <a name="apidoc.element.react-bootstrap.Breadcrumb.Breadcrumb"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Breadcrumb ()](#apidoc.element.react-bootstrap.Breadcrumb.Breadcrumb)
- description and source-code
```javascript
function Breadcrumb() {
  (0, _classCallCheck3['default'])(this, Breadcrumb);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Breadcrumb.Item"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Breadcrumb.</span>Item ()](#apidoc.element.react-bootstrap.Breadcrumb.Item)
- description and source-code
```javascript
function BreadcrumbItem() {
  (0, _classCallCheck3['default'])(this, BreadcrumbItem);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Breadcrumb.propTypes"></a>[module react-bootstrap.Breadcrumb.propTypes](#apidoc.module.react-bootstrap.Breadcrumb.propTypes)

#### <a name="apidoc.element.react-bootstrap.Breadcrumb.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Breadcrumb.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Breadcrumb.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Breadcrumb.prototype"></a>[module react-bootstrap.Breadcrumb.prototype](#apidoc.module.react-bootstrap.Breadcrumb.prototype)

#### <a name="apidoc.element.react-bootstrap.Breadcrumb.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Breadcrumb.prototype.</span>render ()](#apidoc.element.react-bootstrap.Breadcrumb.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _bootstrapUtils.getClassSet)(bsProps);

  return _react2['default'].createElement('ol', (0, _extends3['default'])({}, elementProps, {
    role: 'navigation',
    'aria-label': 'breadcrumbs',
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.BreadcrumbItem"></a>[module react-bootstrap.BreadcrumbItem](#apidoc.module.react-bootstrap.BreadcrumbItem)

#### <a name="apidoc.element.react-bootstrap.BreadcrumbItem.BreadcrumbItem"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>BreadcrumbItem ()](#apidoc.element.react-bootstrap.BreadcrumbItem.BreadcrumbItem)
- description and source-code
```javascript
function BreadcrumbItem() {
  (0, _classCallCheck3['default'])(this, BreadcrumbItem);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.BreadcrumbItem.propTypes"></a>[module react-bootstrap.BreadcrumbItem.propTypes](#apidoc.module.react-bootstrap.BreadcrumbItem.propTypes)

#### <a name="apidoc.element.react-bootstrap.BreadcrumbItem.propTypes.active"></a>[function <span class="apidocSignatureSpan">react-bootstrap.BreadcrumbItem.propTypes.</span>active ()](#apidoc.element.react-bootstrap.BreadcrumbItem.propTypes.active)
- description and source-code
```javascript
active = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.BreadcrumbItem.propTypes.href"></a>[function <span class="apidocSignatureSpan">react-bootstrap.BreadcrumbItem.propTypes.</span>href ()](#apidoc.element.react-bootstrap.BreadcrumbItem.propTypes.href)
- description and source-code
```javascript
href = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.BreadcrumbItem.propTypes.target"></a>[function <span class="apidocSignatureSpan">react-bootstrap.BreadcrumbItem.propTypes.</span>target ()](#apidoc.element.react-bootstrap.BreadcrumbItem.propTypes.target)
- description and source-code
```javascript
target = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.BreadcrumbItem.propTypes.title"></a>[function <span class="apidocSignatureSpan">react-bootstrap.BreadcrumbItem.propTypes.</span>title ()](#apidoc.element.react-bootstrap.BreadcrumbItem.propTypes.title)
- description and source-code
```javascript
title = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.BreadcrumbItem.prototype"></a>[module react-bootstrap.BreadcrumbItem.prototype](#apidoc.module.react-bootstrap.BreadcrumbItem.prototype)

#### <a name="apidoc.element.react-bootstrap.BreadcrumbItem.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.BreadcrumbItem.prototype.</span>render ()](#apidoc.element.react-bootstrap.BreadcrumbItem.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      active = _props.active,
      href = _props.href,
      title = _props.title,
      target = _props.target,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['active', 'href', 'title', 'target', 'className']);

  // Don't try to render these props on non-active <span>.

  var linkProps = { href: href, title: title, target: target };

  return _react2['default'].createElement(
    'li',
    { className: (0, _classnames2['default'])(className, { active: active }) },
    active ? _react2['default'].createElement('span', props) : _react2['default'].createElement(_SafeAnchor2['default'], (0, _extends3
['default'])({}, props, linkProps))
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Button"></a>[module react-bootstrap.Button](#apidoc.module.react-bootstrap.Button)

#### <a name="apidoc.element.react-bootstrap.Button.Button"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Button ()](#apidoc.element.react-bootstrap.Button.Button)
- description and source-code
```javascript
function Button() {
  (0, _classCallCheck3['default'])(this, Button);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Button.propTypes"></a>[module react-bootstrap.Button.propTypes](#apidoc.module.react-bootstrap.Button.propTypes)

#### <a name="apidoc.element.react-bootstrap.Button.propTypes.active"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Button.propTypes.</span>active ()](#apidoc.element.react-bootstrap.Button.propTypes.active)
- description and source-code
```javascript
active = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Button.propTypes.block"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Button.propTypes.</span>block ()](#apidoc.element.react-bootstrap.Button.propTypes.block)
- description and source-code
```javascript
block = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Button.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Button.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Button.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Button.propTypes.bsSize"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Button.propTypes.</span>bsSize ()](#apidoc.element.react-bootstrap.Button.propTypes.bsSize)
- description and source-code
```javascript
bsSize = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Button.propTypes.bsStyle"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Button.propTypes.</span>bsStyle ()](#apidoc.element.react-bootstrap.Button.propTypes.bsStyle)
- description and source-code
```javascript
bsStyle = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Button.propTypes.componentClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Button.propTypes.</span>componentClass ()](#apidoc.element.react-bootstrap.Button.propTypes.componentClass)
- description and source-code
```javascript
componentClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Button.propTypes.disabled"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Button.propTypes.</span>disabled ()](#apidoc.element.react-bootstrap.Button.propTypes.disabled)
- description and source-code
```javascript
disabled = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Button.propTypes.href"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Button.propTypes.</span>href ()](#apidoc.element.react-bootstrap.Button.propTypes.href)
- description and source-code
```javascript
href = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Button.propTypes.onClick"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Button.propTypes.</span>onClick ()](#apidoc.element.react-bootstrap.Button.propTypes.onClick)
- description and source-code
```javascript
onClick = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Button.propTypes.type"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Button.propTypes.</span>type ()](#apidoc.element.react-bootstrap.Button.propTypes.type)
- description and source-code
```javascript
type = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Button.prototype"></a>[module react-bootstrap.Button.prototype](#apidoc.module.react-bootstrap.Button.prototype)

#### <a name="apidoc.element.react-bootstrap.Button.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Button.prototype.</span>render ()](#apidoc.element.react-bootstrap.Button.prototype.render)
- description and source-code
```javascript
function render() {
  var _extends2;

  var _props = this.props,
      active = _props.active,
      block = _props.block,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['active', 'block', 'className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _extends4['default'])({}, (0, _bootstrapUtils.getClassSet)(bsProps), (_extends2 = {
    active: active
  }, _extends2[(0, _bootstrapUtils.prefix)(bsProps, 'block')] = block, _extends2));
  var fullClassName = (0, _classnames2['default'])(className, classes);

  if (elementProps.href) {
    return this.renderAnchor(elementProps, fullClassName);
  }

  return this.renderButton(elementProps, fullClassName);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Button.prototype.renderAnchor"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Button.prototype.</span>renderAnchor (elementProps, className)](#apidoc.element.react-bootstrap.Button.prototype.renderAnchor)
- description and source-code
```javascript
function renderAnchor(elementProps, className) {
  return _react2['default'].createElement(_SafeAnchor2['default'], (0, _extends4['default'])({}, elementProps, {
    className: (0, _classnames2['default'])(className, elementProps.disabled && 'disabled')
  }));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Button.prototype.renderButton"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Button.prototype.</span>renderButton (_ref, className)](#apidoc.element.react-bootstrap.Button.prototype.renderButton)
- description and source-code
```javascript
function renderButton(_ref, className) {
  var componentClass = _ref.componentClass,
      elementProps = (0, _objectWithoutProperties3['default'])(_ref, ['componentClass']);

  var Component = componentClass || 'button';

  return _react2['default'].createElement(Component, (0, _extends4['default'])({}, elementProps, {
    type: elementProps.type || 'button',
    className: className
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ButtonGroup"></a>[module react-bootstrap.ButtonGroup](#apidoc.module.react-bootstrap.ButtonGroup)

#### <a name="apidoc.element.react-bootstrap.ButtonGroup.ButtonGroup"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>ButtonGroup ()](#apidoc.element.react-bootstrap.ButtonGroup.ButtonGroup)
- description and source-code
```javascript
function ButtonGroup() {
  (0, _classCallCheck3['default'])(this, ButtonGroup);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ButtonGroup.propTypes"></a>[module react-bootstrap.ButtonGroup.propTypes](#apidoc.module.react-bootstrap.ButtonGroup.propTypes)

#### <a name="apidoc.element.react-bootstrap.ButtonGroup.propTypes.block"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ButtonGroup.propTypes.</span>block ()](#apidoc.element.react-bootstrap.ButtonGroup.propTypes.block)
- description and source-code
```javascript
block = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ButtonGroup.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ButtonGroup.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.ButtonGroup.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ButtonGroup.propTypes.justified"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ButtonGroup.propTypes.</span>justified ()](#apidoc.element.react-bootstrap.ButtonGroup.propTypes.justified)
- description and source-code
```javascript
justified = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ButtonGroup.propTypes.vertical"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ButtonGroup.propTypes.</span>vertical ()](#apidoc.element.react-bootstrap.ButtonGroup.propTypes.vertical)
- description and source-code
```javascript
vertical = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ButtonGroup.prototype"></a>[module react-bootstrap.ButtonGroup.prototype](#apidoc.module.react-bootstrap.ButtonGroup.prototype)

#### <a name="apidoc.element.react-bootstrap.ButtonGroup.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ButtonGroup.prototype.</span>render ()](#apidoc.element.react-bootstrap.ButtonGroup.prototype.render)
- description and source-code
```javascript
function render() {
  var _extends2;

  var _props = this.props,
      block = _props.block,
      justified = _props.justified,
      vertical = _props.vertical,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['block', 'justified', 'vertical', 'className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _extends4['default'])({}, (0, _bootstrapUtils.getClassSet)(bsProps), (_extends2 = {}, _extends2[(0, _bootstrapUtils
.prefix)(bsProps)] = !vertical, _extends2[(0, _bootstrapUtils.prefix)(bsProps, 'vertical')] = vertical, _extends2[(0, _bootstrapUtils
.prefix)(bsProps, 'justified')] = justified, _extends2[(0, _bootstrapUtils.prefix)(_Button2['default'].defaultProps, 'block')] =
block, _extends2));

  return _react2['default'].createElement('div', (0, _extends4['default'])({}, elementProps, {
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ButtonToolbar"></a>[module react-bootstrap.ButtonToolbar](#apidoc.module.react-bootstrap.ButtonToolbar)

#### <a name="apidoc.element.react-bootstrap.ButtonToolbar.ButtonToolbar"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>ButtonToolbar ()](#apidoc.element.react-bootstrap.ButtonToolbar.ButtonToolbar)
- description and source-code
```javascript
function ButtonToolbar() {
  (0, _classCallCheck3['default'])(this, ButtonToolbar);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ButtonToolbar.propTypes"></a>[module react-bootstrap.ButtonToolbar.propTypes](#apidoc.module.react-bootstrap.ButtonToolbar.propTypes)

#### <a name="apidoc.element.react-bootstrap.ButtonToolbar.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ButtonToolbar.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.ButtonToolbar.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ButtonToolbar.propTypes.bsSize"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ButtonToolbar.propTypes.</span>bsSize ()](#apidoc.element.react-bootstrap.ButtonToolbar.propTypes.bsSize)
- description and source-code
```javascript
bsSize = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ButtonToolbar.prototype"></a>[module react-bootstrap.ButtonToolbar.prototype](#apidoc.module.react-bootstrap.ButtonToolbar.prototype)

#### <a name="apidoc.element.react-bootstrap.ButtonToolbar.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ButtonToolbar.prototype.</span>render ()](#apidoc.element.react-bootstrap.ButtonToolbar.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _bootstrapUtils.getClassSet)(bsProps);

  return _react2['default'].createElement('div', (0, _extends3['default'])({}, elementProps, {
    role: 'toolbar',
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Carousel"></a>[module react-bootstrap.Carousel](#apidoc.module.react-bootstrap.Carousel)

#### <a name="apidoc.element.react-bootstrap.Carousel.Carousel"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Carousel (props, context)](#apidoc.element.react-bootstrap.Carousel.Carousel)
- description and source-code
```javascript
function Carousel(props, context) {
  (0, _classCallCheck3['default'])(this, Carousel);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleMouseOver = _this.handleMouseOver.bind(_this);
  _this.handleMouseOut = _this.handleMouseOut.bind(_this);
  _this.handlePrev = _this.handlePrev.bind(_this);
  _this.handleNext = _this.handleNext.bind(_this);
  _this.handleItemAnimateOutEnd = _this.handleItemAnimateOutEnd.bind(_this);

  var defaultActiveIndex = props.defaultActiveIndex;


  _this.state = {
    activeIndex: defaultActiveIndex != null ? defaultActiveIndex : 0,
    previousActiveIndex: null,
    direction: null
  };

  _this.isUnmounted = false;
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.Caption"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.</span>Caption ()](#apidoc.element.react-bootstrap.Carousel.Caption)
- description and source-code
```javascript
function CarouselCaption() {
  (0, _classCallCheck3['default'])(this, CarouselCaption);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.Item"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.</span>Item (props, context)](#apidoc.element.react-bootstrap.Carousel.Item)
- description and source-code
```javascript
function CarouselItem(props, context) {
  (0, _classCallCheck3['default'])(this, CarouselItem);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleAnimateOutEnd = _this.handleAnimateOutEnd.bind(_this);

  _this.state = {
    direction: null
  };

  _this.isUnmounted = false;
  return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Carousel.Caption"></a>[module react-bootstrap.Carousel.Caption](#apidoc.module.react-bootstrap.Carousel.Caption)

#### <a name="apidoc.element.react-bootstrap.Carousel.Caption.Caption"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.</span>Caption ()](#apidoc.element.react-bootstrap.Carousel.Caption.Caption)
- description and source-code
```javascript
function CarouselCaption() {
  (0, _classCallCheck3['default'])(this, CarouselCaption);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Carousel.Caption.prototype"></a>[module react-bootstrap.Carousel.Caption.prototype](#apidoc.module.react-bootstrap.Carousel.Caption.prototype)

#### <a name="apidoc.element.react-bootstrap.Carousel.Caption.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.Caption.prototype.</span>render ()](#apidoc.element.react-bootstrap.Carousel.Caption.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      Component = _props.componentClass,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['componentClass', 'className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _bootstrapUtils.getClassSet)(bsProps);

  return _react2['default'].createElement(Component, (0, _extends3['default'])({}, elementProps, {
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Carousel.propTypes"></a>[module react-bootstrap.Carousel.propTypes](#apidoc.module.react-bootstrap.Carousel.propTypes)

#### <a name="apidoc.element.react-bootstrap.Carousel.propTypes.activeIndex"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>activeIndex ()](#apidoc.element.react-bootstrap.Carousel.propTypes.activeIndex)
- description and source-code
```javascript
activeIndex = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Carousel.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.propTypes.controls"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>controls ()](#apidoc.element.react-bootstrap.Carousel.propTypes.controls)
- description and source-code
```javascript
controls = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.propTypes.defaultActiveIndex"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>defaultActiveIndex ()](#apidoc.element.react-bootstrap.Carousel.propTypes.defaultActiveIndex)
- description and source-code
```javascript
defaultActiveIndex = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.propTypes.direction"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>direction ()](#apidoc.element.react-bootstrap.Carousel.propTypes.direction)
- description and source-code
```javascript
direction = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.propTypes.indicators"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>indicators ()](#apidoc.element.react-bootstrap.Carousel.propTypes.indicators)
- description and source-code
```javascript
indicators = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.propTypes.interval"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>interval ()](#apidoc.element.react-bootstrap.Carousel.propTypes.interval)
- description and source-code
```javascript
interval = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.propTypes.nextIcon"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>nextIcon ()](#apidoc.element.react-bootstrap.Carousel.propTypes.nextIcon)
- description and source-code
```javascript
nextIcon = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.propTypes.nextLabel"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>nextLabel ()](#apidoc.element.react-bootstrap.Carousel.propTypes.nextLabel)
- description and source-code
```javascript
nextLabel = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.propTypes.onSelect"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>onSelect ()](#apidoc.element.react-bootstrap.Carousel.propTypes.onSelect)
- description and source-code
```javascript
onSelect = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.propTypes.onSlideEnd"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>onSlideEnd ()](#apidoc.element.react-bootstrap.Carousel.propTypes.onSlideEnd)
- description and source-code
```javascript
onSlideEnd = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.propTypes.pauseOnHover"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>pauseOnHover ()](#apidoc.element.react-bootstrap.Carousel.propTypes.pauseOnHover)
- description and source-code
```javascript
pauseOnHover = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.propTypes.prevIcon"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>prevIcon ()](#apidoc.element.react-bootstrap.Carousel.propTypes.prevIcon)
- description and source-code
```javascript
prevIcon = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.propTypes.prevLabel"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>prevLabel ()](#apidoc.element.react-bootstrap.Carousel.propTypes.prevLabel)
- description and source-code
```javascript
prevLabel = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.propTypes.slide"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>slide ()](#apidoc.element.react-bootstrap.Carousel.propTypes.slide)
- description and source-code
```javascript
slide = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.propTypes.wrap"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.propTypes.</span>wrap ()](#apidoc.element.react-bootstrap.Carousel.propTypes.wrap)
- description and source-code
```javascript
wrap = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Carousel.prototype"></a>[module react-bootstrap.Carousel.prototype](#apidoc.module.react-bootstrap.Carousel.prototype)

#### <a name="apidoc.element.react-bootstrap.Carousel.prototype.componentDidMount"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>componentDidMount ()](#apidoc.element.react-bootstrap.Carousel.prototype.componentDidMount)
- description and source-code
```javascript
function componentDidMount() {
  this.waitForNext();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.prototype.componentWillReceiveProps"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.react-bootstrap.Carousel.prototype.componentWillReceiveProps)
- description and source-code
```javascript
function componentWillReceiveProps(nextProps) {
  var activeIndex = this.getActiveIndex();

  if (nextProps.activeIndex != null && nextProps.activeIndex !== activeIndex) {
    clearTimeout(this.timeout);

    this.setState({
      previousActiveIndex: activeIndex,
      direction: nextProps.direction != null ? nextProps.direction : this.getDirection(activeIndex, nextProps.activeIndex)
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.prototype.componentWillUnmount"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>componentWillUnmount ()](#apidoc.element.react-bootstrap.Carousel.prototype.componentWillUnmount)
- description and source-code
```javascript
function componentWillUnmount() {
  clearTimeout(this.timeout);
  this.isUnmounted = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.prototype.getActiveIndex"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>getActiveIndex ()](#apidoc.element.react-bootstrap.Carousel.prototype.getActiveIndex)
- description and source-code
```javascript
function getActiveIndex() {
  var activeIndexProp = this.props.activeIndex;
  return activeIndexProp != null ? activeIndexProp : this.state.activeIndex;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.prototype.getDirection"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>getDirection (prevIndex, index)](#apidoc.element.react-bootstrap.Carousel.prototype.getDirection)
- description and source-code
```javascript
function getDirection(prevIndex, index) {
  if (prevIndex === index) {
    return null;
  }

  return prevIndex > index ? 'prev' : 'next';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.prototype.handleItemAnimateOutEnd"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>handleItemAnimateOutEnd ()](#apidoc.element.react-bootstrap.Carousel.prototype.handleItemAnimateOutEnd)
- description and source-code
```javascript
function handleItemAnimateOutEnd() {
  var _this2 = this;

  this.setState({
    previousActiveIndex: null,
    direction: null
  }, function () {
    _this2.waitForNext();

    if (_this2.props.onSlideEnd) {
      _this2.props.onSlideEnd();
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.prototype.handleMouseOut"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>handleMouseOut ()](#apidoc.element.react-bootstrap.Carousel.prototype.handleMouseOut)
- description and source-code
```javascript
function handleMouseOut() {
  if (this.isPaused) {
    this.play();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.prototype.handleMouseOver"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>handleMouseOver ()](#apidoc.element.react-bootstrap.Carousel.prototype.handleMouseOver)
- description and source-code
```javascript
function handleMouseOver() {
  if (this.props.pauseOnHover) {
    this.pause();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.prototype.handleNext"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>handleNext (e)](#apidoc.element.react-bootstrap.Carousel.prototype.handleNext)
- description and source-code
```javascript
function handleNext(e) {
  var index = this.getActiveIndex() + 1;
  var count = _ValidComponentChildren2['default'].count(this.props.children);

  if (index > count - 1) {
    if (!this.props.wrap) {
      return;
    }
    index = 0;
  }

  this.select(index, e, 'next');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.prototype.handlePrev"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>handlePrev (e)](#apidoc.element.react-bootstrap.Carousel.prototype.handlePrev)
- description and source-code
```javascript
function handlePrev(e) {
  var index = this.getActiveIndex() - 1;

  if (index < 0) {
    if (!this.props.wrap) {
      return;
    }
    index = _ValidComponentChildren2['default'].count(this.props.children) - 1;
  }

  this.select(index, e, 'prev');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.prototype.pause"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>pause ()](#apidoc.element.react-bootstrap.Carousel.prototype.pause)
- description and source-code
```javascript
function pause() {
  this.isPaused = true;
  clearTimeout(this.timeout);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.prototype.play"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>play ()](#apidoc.element.react-bootstrap.Carousel.prototype.play)
- description and source-code
```javascript
function play() {
  this.isPaused = false;
  this.waitForNext();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>render ()](#apidoc.element.react-bootstrap.Carousel.prototype.render)
- description and source-code
```javascript
function render() {
  var _this4 = this;

  var _props2 = this.props,
      slide = _props2.slide,
      indicators = _props2.indicators,
      controls = _props2.controls,
      wrap = _props2.wrap,
      prevIcon = _props2.prevIcon,
      prevLabel = _props2.prevLabel,
      nextIcon = _props2.nextIcon,
      nextLabel = _props2.nextLabel,
      className = _props2.className,
      children = _props2.children,
      props = (0, _objectWithoutProperties3['default'])(_props2, ['slide', 'indicators', 'controls', 'wrap', 'prevIcon', 'prevLabel
', 'nextIcon', 'nextLabel', 'className', 'children']);
  var _state = this.state,
      previousActiveIndex = _state.previousActiveIndex,
      direction = _state.direction;

  var _splitBsPropsAndOmit = (0, _bootstrapUtils.splitBsPropsAndOmit)(props, ['interval', 'pauseOnHover', 'onSelect', 'onSlideEnd
', 'activeIndex', // Accessed via this.getActiveIndex().
  'defaultActiveIndex', 'direction']),
      bsProps = _splitBsPropsAndOmit[0],
      elementProps = _splitBsPropsAndOmit[1];

  var activeIndex = this.getActiveIndex();

  var classes = (0, _extends3['default'])({}, (0, _bootstrapUtils.getClassSet)(bsProps), {
    slide: slide
  });

  return _react2['default'].createElement(
    'div',
    (0, _extends3['default'])({}, elementProps, {
      className: (0, _classnames2['default'])(className, classes),
      onMouseOver: this.handleMouseOver,
      onMouseOut: this.handleMouseOut
    }),
    indicators && this.renderIndicators(children, activeIndex, bsProps),
    _react2['default'].createElement(
      'div',
      { className: (0, _bootstrapUtils.prefix)(bsProps, 'inner') },
      _ValidComponentChildren2['default'].map(children, function (child, index) {
        var active = index === activeIndex;
        var previousActive = slide && index === previousActiveIndex;

        return (0, _react.cloneElement)(child, {
          active: active,
          index: index,
          animateOut: previousActive,
          animateIn: active && previousActiveIndex != null && slide,
          direction: direction,
          onAnimateOutEnd: previousActive ? _this4.handleItemAnimateOutEnd : null
        });
      })
    ),
    controls && this.renderControls({
      wrap: wrap,
      children: children,
      activeIndex: activeIndex,
      prevIcon: prevIcon,
      prevLabel: prevLabel,
      nextIcon: nextIcon,
      nextLabel: nextLabel,
      bsProps: bsProps
    })
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.prototype.renderControls"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>renderControls (properties)](#apidoc.element.react-bootstrap.Carousel.prototype.renderControls)
- description and source-code
```javascript
function renderControls(properties) {
  var wrap = properties.wrap,
      children = properties.children,
      activeIndex = properties.activeIndex,
      prevIcon = properties.prevIcon,
      nextIcon = properties.nextIcon,
      bsProps = properties.bsProps,
      prevLabel = properties.prevLabel,
      nextLabel = properties.nextLabel;

  var controlClassName = (0, _bootstrapUtils.prefix)(bsProps, 'control');
  var count = _ValidComponentChildren2['default'].count(children);

  return [(wrap || activeIndex !== 0) && _react2['default'].createElement(
    _SafeAnchor2['default'],
    {
      key: 'prev',
      className: (0, _classnames2['default'])(controlClassName, 'left'),
      onClick: this.handlePrev
    },
    prevIcon,
    prevLabel && _react2['default'].createElement(
      'span',
      { className: 'sr-only' },
      prevLabel
    )
  ), (wrap || activeIndex !== count - 1) && _react2['default'].createElement(
    _SafeAnchor2['default'],
    {
      key: 'next',
      className: (0, _classnames2['default'])(controlClassName, 'right'),
      onClick: this.handleNext
    },
    nextIcon,
    nextLabel && _react2['default'].createElement(
      'span',
      { className: 'sr-only' },
      nextLabel
    )
  )];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.prototype.renderIndicators"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>renderIndicators (children, activeIndex, bsProps)](#apidoc.element.react-bootstrap.Carousel.prototype.renderIndicators)
- description and source-code
```javascript
function renderIndicators(children, activeIndex, bsProps) {
  var _this3 = this;

  var indicators = [];

  _ValidComponentChildren2['default'].forEach(children, function (child, index) {
    indicators.push(_react2['default'].createElement('li', {
      key: index,
      className: index === activeIndex ? 'active' : null,
      onClick: function onClick(e) {
        return _this3.select(index, e);
      }
    }),

    // Force whitespace between indicator elements. Bootstrap requires
    // this for correct spacing of elements.
    ' ');
  });

  return _react2['default'].createElement(
    'ol',
    { className: (0, _bootstrapUtils.prefix)(bsProps, 'indicators') },
    indicators
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.prototype.select"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>select (index, e, direction)](#apidoc.element.react-bootstrap.Carousel.prototype.select)
- description and source-code
```javascript
function select(index, e, direction) {
  clearTimeout(this.timeout);

  // TODO: Is this necessary? Seems like the only risk is if the component
  // unmounts while handleItemAnimateOutEnd fires.
  if (this.isUnmounted) {
    return;
  }

  var previousActiveIndex = this.props.slide ? this.getActiveIndex() : null;
  direction = direction || this.getDirection(previousActiveIndex, index);

  var onSelect = this.props.onSelect;


  if (onSelect) {
    if (onSelect.length > 1) {
      // React SyntheticEvents are pooled, so we need to remove this event
      // from the pool to add a custom property. To avoid unnecessarily
      // removing objects from the pool, only do this when the listener
      // actually wants the event.
      if (e) {
        e.persist();
        e.direction = direction;
      } else {
        e = { direction: direction };
      }

      onSelect(index, e);
    } else {
      onSelect(index);
    }
  }

  if (this.props.activeIndex == null && index !== previousActiveIndex) {
    if (this.state.previousActiveIndex != null) {
      // If currently animating don't activate the new index.
      // TODO: look into queueing this canceled call and
      // animating after the current animation has ended.
      return;
    }

    this.setState({
      activeIndex: index,
      previousActiveIndex: previousActiveIndex,
      direction: direction
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Carousel.prototype.waitForNext"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Carousel.prototype.</span>waitForNext ()](#apidoc.element.react-bootstrap.Carousel.prototype.waitForNext)
- description and source-code
```javascript
function waitForNext() {
  var _props = this.props,
      slide = _props.slide,
      interval = _props.interval,
      activeIndexProp = _props.activeIndex;


  if (!this.isPaused && slide && interval && activeIndexProp == null) {
    this.timeout = setTimeout(this.handleNext, interval);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.CarouselItem"></a>[module react-bootstrap.CarouselItem](#apidoc.module.react-bootstrap.CarouselItem)

#### <a name="apidoc.element.react-bootstrap.CarouselItem.CarouselItem"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>CarouselItem (props, context)](#apidoc.element.react-bootstrap.CarouselItem.CarouselItem)
- description and source-code
```javascript
function CarouselItem(props, context) {
  (0, _classCallCheck3['default'])(this, CarouselItem);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleAnimateOutEnd = _this.handleAnimateOutEnd.bind(_this);

  _this.state = {
    direction: null
  };

  _this.isUnmounted = false;
  return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.CarouselItem.propTypes"></a>[module react-bootstrap.CarouselItem.propTypes](#apidoc.module.react-bootstrap.CarouselItem.propTypes)

#### <a name="apidoc.element.react-bootstrap.CarouselItem.propTypes.active"></a>[function <span class="apidocSignatureSpan">react-bootstrap.CarouselItem.propTypes.</span>active ()](#apidoc.element.react-bootstrap.CarouselItem.propTypes.active)
- description and source-code
```javascript
active = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.CarouselItem.propTypes.animateIn"></a>[function <span class="apidocSignatureSpan">react-bootstrap.CarouselItem.propTypes.</span>animateIn ()](#apidoc.element.react-bootstrap.CarouselItem.propTypes.animateIn)
- description and source-code
```javascript
animateIn = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.CarouselItem.propTypes.animateOut"></a>[function <span class="apidocSignatureSpan">react-bootstrap.CarouselItem.propTypes.</span>animateOut ()](#apidoc.element.react-bootstrap.CarouselItem.propTypes.animateOut)
- description and source-code
```javascript
animateOut = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.CarouselItem.propTypes.direction"></a>[function <span class="apidocSignatureSpan">react-bootstrap.CarouselItem.propTypes.</span>direction ()](#apidoc.element.react-bootstrap.CarouselItem.propTypes.direction)
- description and source-code
```javascript
direction = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.CarouselItem.propTypes.index"></a>[function <span class="apidocSignatureSpan">react-bootstrap.CarouselItem.propTypes.</span>index ()](#apidoc.element.react-bootstrap.CarouselItem.propTypes.index)
- description and source-code
```javascript
index = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.CarouselItem.propTypes.onAnimateOutEnd"></a>[function <span class="apidocSignatureSpan">react-bootstrap.CarouselItem.propTypes.</span>onAnimateOutEnd ()](#apidoc.element.react-bootstrap.CarouselItem.propTypes.onAnimateOutEnd)
- description and source-code
```javascript
onAnimateOutEnd = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.CarouselItem.prototype"></a>[module react-bootstrap.CarouselItem.prototype](#apidoc.module.react-bootstrap.CarouselItem.prototype)

#### <a name="apidoc.element.react-bootstrap.CarouselItem.prototype.componentDidUpdate"></a>[function <span class="apidocSignatureSpan">react-bootstrap.CarouselItem.prototype.</span>componentDidUpdate (prevProps)](#apidoc.element.react-bootstrap.CarouselItem.prototype.componentDidUpdate)
- description and source-code
```javascript
function componentDidUpdate(prevProps) {
  var _this2 = this;

  var active = this.props.active;

  var prevActive = prevProps.active;

  if (!active && prevActive) {
    _TransitionEvents2['default'].addEndEventListener(_reactDom2['default'].findDOMNode(this), this.handleAnimateOutEnd);
  }

  if (active !== prevActive) {
    setTimeout(function () {
      return _this2.startAnimation();
    }, 20);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.CarouselItem.prototype.componentWillReceiveProps"></a>[function <span class="apidocSignatureSpan">react-bootstrap.CarouselItem.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.react-bootstrap.CarouselItem.prototype.componentWillReceiveProps)
- description and source-code
```javascript
function componentWillReceiveProps(nextProps) {
  if (this.props.active !== nextProps.active) {
    this.setState({ direction: null });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.CarouselItem.prototype.componentWillUnmount"></a>[function <span class="apidocSignatureSpan">react-bootstrap.CarouselItem.prototype.</span>componentWillUnmount ()](#apidoc.element.react-bootstrap.CarouselItem.prototype.componentWillUnmount)
- description and source-code
```javascript
function componentWillUnmount() {
  this.isUnmounted = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.CarouselItem.prototype.handleAnimateOutEnd"></a>[function <span class="apidocSignatureSpan">react-bootstrap.CarouselItem.prototype.</span>handleAnimateOutEnd ()](#apidoc.element.react-bootstrap.CarouselItem.prototype.handleAnimateOutEnd)
- description and source-code
```javascript
function handleAnimateOutEnd() {
  if (this.isUnmounted) {
    return;
  }

  if (this.props.onAnimateOutEnd) {
    this.props.onAnimateOutEnd(this.props.index);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.CarouselItem.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.CarouselItem.prototype.</span>render ()](#apidoc.element.react-bootstrap.CarouselItem.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      direction = _props.direction,
      active = _props.active,
      animateIn = _props.animateIn,
      animateOut = _props.animateOut,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['direction', 'active', 'animateIn', 'animateOut', 'className']);


  delete props.onAnimateOutEnd;
  delete props.index;

  var classes = {
    item: true,
    active: active && !animateIn || animateOut
  };
  if (direction && active && animateIn) {
    classes[direction] = true;
  }
  if (this.state.direction && (animateIn || animateOut)) {
    classes[this.state.direction] = true;
  }

  return _react2['default'].createElement('div', (0, _extends3['default'])({}, props, {
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.CarouselItem.prototype.startAnimation"></a>[function <span class="apidocSignatureSpan">react-bootstrap.CarouselItem.prototype.</span>startAnimation ()](#apidoc.element.react-bootstrap.CarouselItem.prototype.startAnimation)
- description and source-code
```javascript
function startAnimation() {
  if (this.isUnmounted) {
    return;
  }

  this.setState({
    direction: this.props.direction === 'prev' ? 'right' : 'left'
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Checkbox"></a>[module react-bootstrap.Checkbox](#apidoc.module.react-bootstrap.Checkbox)

#### <a name="apidoc.element.react-bootstrap.Checkbox.Checkbox"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Checkbox ()](#apidoc.element.react-bootstrap.Checkbox.Checkbox)
- description and source-code
```javascript
function Checkbox() {
  (0, _classCallCheck3['default'])(this, Checkbox);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Checkbox.propTypes"></a>[module react-bootstrap.Checkbox.propTypes](#apidoc.module.react-bootstrap.Checkbox.propTypes)

#### <a name="apidoc.element.react-bootstrap.Checkbox.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Checkbox.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Checkbox.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Checkbox.propTypes.disabled"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Checkbox.propTypes.</span>disabled ()](#apidoc.element.react-bootstrap.Checkbox.propTypes.disabled)
- description and source-code
```javascript
disabled = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Checkbox.propTypes.inline"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Checkbox.propTypes.</span>inline ()](#apidoc.element.react-bootstrap.Checkbox.propTypes.inline)
- description and source-code
```javascript
inline = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Checkbox.propTypes.inputRef"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Checkbox.propTypes.</span>inputRef ()](#apidoc.element.react-bootstrap.Checkbox.propTypes.inputRef)
- description and source-code
```javascript
inputRef = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Checkbox.propTypes.validationState"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Checkbox.propTypes.</span>validationState ()](#apidoc.element.react-bootstrap.Checkbox.propTypes.validationState)
- description and source-code
```javascript
validationState = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Checkbox.prototype"></a>[module react-bootstrap.Checkbox.prototype](#apidoc.module.react-bootstrap.Checkbox.prototype)

#### <a name="apidoc.element.react-bootstrap.Checkbox.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Checkbox.prototype.</span>render ()](#apidoc.element.react-bootstrap.Checkbox.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      inline = _props.inline,
      disabled = _props.disabled,
      validationState = _props.validationState,
      inputRef = _props.inputRef,
      className = _props.className,
      style = _props.style,
      children = _props.children,
      props = (0, _objectWithoutProperties3['default'])(_props, ['inline', 'disabled', 'validationState', 'inputRef', 'className
', 'style', 'children']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var input = _react2['default'].createElement('input', (0, _extends3['default'])({}, elementProps, {
    ref: inputRef,
    type: 'checkbox',
    disabled: disabled
  }));

  if (inline) {
    var _classes2;

    var _classes = (_classes2 = {}, _classes2[(0, _bootstrapUtils.prefix)(bsProps, 'inline')] = true, _classes2.disabled = disabled
, _classes2);

    // Use a warning here instead of in propTypes to get better-looking
    // generated documentation.
    process.env.NODE_ENV !== 'production' ? (0, _warning2['default'])(!validationState, ''validationState' is ignored on '<Checkbox
 inline>'. To display ' + 'validation state on an inline checkbox, set 'validationState' on a ' + 'parent '<FormGroup>' or other
 element instead.') : void 0;

    return _react2['default'].createElement(
      'label',
      { className: (0, _classnames2['default'])(className, _classes), style: style },
      input,
      children
    );
  }

  var classes = (0, _extends3['default'])({}, (0, _bootstrapUtils.getClassSet)(bsProps), {
    disabled: disabled
  });
  if (validationState) {
    classes['has-' + validationState] = true;
  }

  return _react2['default'].createElement(
    'div',
    { className: (0, _classnames2['default'])(className, classes), style: style },
    _react2['default'].createElement(
      'label',
      null,
      input,
      children
    )
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Clearfix"></a>[module react-bootstrap.Clearfix](#apidoc.module.react-bootstrap.Clearfix)

#### <a name="apidoc.element.react-bootstrap.Clearfix.Clearfix"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Clearfix ()](#apidoc.element.react-bootstrap.Clearfix.Clearfix)
- description and source-code
```javascript
function Clearfix() {
  (0, _classCallCheck3['default'])(this, Clearfix);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Clearfix.propTypes"></a>[module react-bootstrap.Clearfix.propTypes](#apidoc.module.react-bootstrap.Clearfix.propTypes)

#### <a name="apidoc.element.react-bootstrap.Clearfix.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Clearfix.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Clearfix.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Clearfix.propTypes.componentClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Clearfix.propTypes.</span>componentClass ()](#apidoc.element.react-bootstrap.Clearfix.propTypes.componentClass)
- description and source-code
```javascript
componentClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Clearfix.propTypes.visibleLgBlock"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Clearfix.propTypes.</span>visibleLgBlock ()](#apidoc.element.react-bootstrap.Clearfix.propTypes.visibleLgBlock)
- description and source-code
```javascript
visibleLgBlock = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Clearfix.propTypes.visibleMdBlock"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Clearfix.propTypes.</span>visibleMdBlock ()](#apidoc.element.react-bootstrap.Clearfix.propTypes.visibleMdBlock)
- description and source-code
```javascript
visibleMdBlock = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Clearfix.propTypes.visibleSmBlock"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Clearfix.propTypes.</span>visibleSmBlock ()](#apidoc.element.react-bootstrap.Clearfix.propTypes.visibleSmBlock)
- description and source-code
```javascript
visibleSmBlock = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Clearfix.propTypes.visibleXsBlock"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Clearfix.propTypes.</span>visibleXsBlock ()](#apidoc.element.react-bootstrap.Clearfix.propTypes.visibleXsBlock)
- description and source-code
```javascript
visibleXsBlock = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Clearfix.prototype"></a>[module react-bootstrap.Clearfix.prototype](#apidoc.module.react-bootstrap.Clearfix.prototype)

#### <a name="apidoc.element.react-bootstrap.Clearfix.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Clearfix.prototype.</span>render ()](#apidoc.element.react-bootstrap.Clearfix.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      Component = _props.componentClass,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['componentClass', 'className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _bootstrapUtils.getClassSet)(bsProps);

  _StyleConfig.DEVICE_SIZES.forEach(function (size) {
    var propName = 'visible' + (0, _capitalize2['default'])(size) + 'Block';
    if (elementProps[propName]) {
      classes['visible-' + size + '-block'] = true;
    }

    delete elementProps[propName];
  });

  return _react2['default'].createElement(Component, (0, _extends3['default'])({}, elementProps, {
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Col"></a>[module react-bootstrap.Col](#apidoc.module.react-bootstrap.Col)

#### <a name="apidoc.element.react-bootstrap.Col.Col"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Col ()](#apidoc.element.react-bootstrap.Col.Col)
- description and source-code
```javascript
function Col() {
  (0, _classCallCheck3['default'])(this, Col);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Col.propTypes"></a>[module react-bootstrap.Col.propTypes](#apidoc.module.react-bootstrap.Col.propTypes)

#### <a name="apidoc.element.react-bootstrap.Col.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Col.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Col.propTypes.componentClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>componentClass ()](#apidoc.element.react-bootstrap.Col.propTypes.componentClass)
- description and source-code
```javascript
componentClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Col.propTypes.lg"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>lg ()](#apidoc.element.react-bootstrap.Col.propTypes.lg)
- description and source-code
```javascript
lg = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Col.propTypes.lgHidden"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>lgHidden ()](#apidoc.element.react-bootstrap.Col.propTypes.lgHidden)
- description and source-code
```javascript
lgHidden = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Col.propTypes.lgOffset"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>lgOffset ()](#apidoc.element.react-bootstrap.Col.propTypes.lgOffset)
- description and source-code
```javascript
lgOffset = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Col.propTypes.lgPull"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>lgPull ()](#apidoc.element.react-bootstrap.Col.propTypes.lgPull)
- description and source-code
```javascript
lgPull = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Col.propTypes.lgPush"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>lgPush ()](#apidoc.element.react-bootstrap.Col.propTypes.lgPush)
- description and source-code
```javascript
lgPush = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Col.propTypes.md"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>md ()](#apidoc.element.react-bootstrap.Col.propTypes.md)
- description and source-code
```javascript
md = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Col.propTypes.mdHidden"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>mdHidden ()](#apidoc.element.react-bootstrap.Col.propTypes.mdHidden)
- description and source-code
```javascript
mdHidden = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Col.propTypes.mdOffset"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>mdOffset ()](#apidoc.element.react-bootstrap.Col.propTypes.mdOffset)
- description and source-code
```javascript
mdOffset = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Col.propTypes.mdPull"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>mdPull ()](#apidoc.element.react-bootstrap.Col.propTypes.mdPull)
- description and source-code
```javascript
mdPull = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Col.propTypes.mdPush"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>mdPush ()](#apidoc.element.react-bootstrap.Col.propTypes.mdPush)
- description and source-code
```javascript
mdPush = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Col.propTypes.sm"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>sm ()](#apidoc.element.react-bootstrap.Col.propTypes.sm)
- description and source-code
```javascript
sm = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Col.propTypes.smHidden"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>smHidden ()](#apidoc.element.react-bootstrap.Col.propTypes.smHidden)
- description and source-code
```javascript
smHidden = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Col.propTypes.smOffset"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>smOffset ()](#apidoc.element.react-bootstrap.Col.propTypes.smOffset)
- description and source-code
```javascript
smOffset = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Col.propTypes.smPull"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>smPull ()](#apidoc.element.react-bootstrap.Col.propTypes.smPull)
- description and source-code
```javascript
smPull = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Col.propTypes.smPush"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>smPush ()](#apidoc.element.react-bootstrap.Col.propTypes.smPush)
- description and source-code
```javascript
smPush = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Col.propTypes.xs"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>xs ()](#apidoc.element.react-bootstrap.Col.propTypes.xs)
- description and source-code
```javascript
xs = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Col.propTypes.xsHidden"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>xsHidden ()](#apidoc.element.react-bootstrap.Col.propTypes.xsHidden)
- description and source-code
```javascript
xsHidden = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Col.propTypes.xsOffset"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>xsOffset ()](#apidoc.element.react-bootstrap.Col.propTypes.xsOffset)
- description and source-code
```javascript
xsOffset = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Col.propTypes.xsPull"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>xsPull ()](#apidoc.element.react-bootstrap.Col.propTypes.xsPull)
- description and source-code
```javascript
xsPull = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Col.propTypes.xsPush"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Col.propTypes.</span>xsPush ()](#apidoc.element.react-bootstrap.Col.propTypes.xsPush)
- description and source-code
```javascript
xsPush = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Col.prototype"></a>[module react-bootstrap.Col.prototype](#apidoc.module.react-bootstrap.Col.prototype)

#### <a name="apidoc.element.react-bootstrap.Col.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Col.prototype.</span>render ()](#apidoc.element.react-bootstrap.Col.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      Component = _props.componentClass,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['componentClass', 'className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = [];

  _StyleConfig.DEVICE_SIZES.forEach(function (size) {
    function popProp(propSuffix, modifier) {
      var propName = '' + size + propSuffix;
      var propValue = elementProps[propName];

      if (propValue != null) {
        classes.push((0, _bootstrapUtils.prefix)(bsProps, '' + size + modifier + '-' + propValue));
      }

      delete elementProps[propName];
    }

    popProp('', '');
    popProp('Offset', '-offset');
    popProp('Push', '-push');
    popProp('Pull', '-pull');

    var hiddenPropName = size + 'Hidden';
    if (elementProps[hiddenPropName]) {
      classes.push('hidden-' + size);
    }
    delete elementProps[hiddenPropName];
  });

  return _react2['default'].createElement(Component, (0, _extends3['default'])({}, elementProps, {
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Collapse"></a>[module react-bootstrap.Collapse](#apidoc.module.react-bootstrap.Collapse)

#### <a name="apidoc.element.react-bootstrap.Collapse.Collapse"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Collapse (props, context)](#apidoc.element.react-bootstrap.Collapse.Collapse)
- description and source-code
```javascript
function Collapse(props, context) {
  (0, _classCallCheck3['default'])(this, Collapse);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleEnter = _this.handleEnter.bind(_this);
  _this.handleEntering = _this.handleEntering.bind(_this);
  _this.handleEntered = _this.handleEntered.bind(_this);
  _this.handleExit = _this.handleExit.bind(_this);
  _this.handleExiting = _this.handleExiting.bind(_this);
  return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Collapse.defaultProps"></a>[module react-bootstrap.Collapse.defaultProps](#apidoc.module.react-bootstrap.Collapse.defaultProps)

#### <a name="apidoc.element.react-bootstrap.Collapse.defaultProps.getDimensionValue"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Collapse.defaultProps.</span>getDimensionValue (dimension, elem)](#apidoc.element.react-bootstrap.Collapse.defaultProps.getDimensionValue)
- description and source-code
```javascript
function getDimensionValue(dimension, elem) {
  var value = elem['offset' + (0, _capitalize2['default'])(dimension)];
  var margins = MARGINS[dimension];

  return value + parseInt((0, _style2['default'])(elem, margins[0]), 10) + parseInt((0, _style2['default'])(elem, margins[1]), 10
);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Collapse.propTypes"></a>[module react-bootstrap.Collapse.propTypes](#apidoc.module.react-bootstrap.Collapse.propTypes)

#### <a name="apidoc.element.react-bootstrap.Collapse.propTypes.dimension"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Collapse.propTypes.</span>dimension ()](#apidoc.element.react-bootstrap.Collapse.propTypes.dimension)
- description and source-code
```javascript
dimension = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Collapse.propTypes.getDimensionValue"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Collapse.propTypes.</span>getDimensionValue ()](#apidoc.element.react-bootstrap.Collapse.propTypes.getDimensionValue)
- description and source-code
```javascript
getDimensionValue = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Collapse.propTypes.in"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Collapse.propTypes.</span>in ()](#apidoc.element.react-bootstrap.Collapse.propTypes.in)
- description and source-code
```javascript
in = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Collapse.propTypes.mountOnEnter"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Collapse.propTypes.</span>mountOnEnter ()](#apidoc.element.react-bootstrap.Collapse.propTypes.mountOnEnter)
- description and source-code
```javascript
mountOnEnter = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Collapse.propTypes.onEnter"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Collapse.propTypes.</span>onEnter ()](#apidoc.element.react-bootstrap.Collapse.propTypes.onEnter)
- description and source-code
```javascript
onEnter = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Collapse.propTypes.onEntered"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Collapse.propTypes.</span>onEntered ()](#apidoc.element.react-bootstrap.Collapse.propTypes.onEntered)
- description and source-code
```javascript
onEntered = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Collapse.propTypes.onEntering"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Collapse.propTypes.</span>onEntering ()](#apidoc.element.react-bootstrap.Collapse.propTypes.onEntering)
- description and source-code
```javascript
onEntering = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Collapse.propTypes.onExit"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Collapse.propTypes.</span>onExit ()](#apidoc.element.react-bootstrap.Collapse.propTypes.onExit)
- description and source-code
```javascript
onExit = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Collapse.propTypes.onExited"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Collapse.propTypes.</span>onExited ()](#apidoc.element.react-bootstrap.Collapse.propTypes.onExited)
- description and source-code
```javascript
onExited = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Collapse.propTypes.onExiting"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Collapse.propTypes.</span>onExiting ()](#apidoc.element.react-bootstrap.Collapse.propTypes.onExiting)
- description and source-code
```javascript
onExiting = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Collapse.propTypes.role"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Collapse.propTypes.</span>role ()](#apidoc.element.react-bootstrap.Collapse.propTypes.role)
- description and source-code
```javascript
role = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Collapse.propTypes.timeout"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Collapse.propTypes.</span>timeout ()](#apidoc.element.react-bootstrap.Collapse.propTypes.timeout)
- description and source-code
```javascript
timeout = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Collapse.propTypes.transitionAppear"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Collapse.propTypes.</span>transitionAppear ()](#apidoc.element.react-bootstrap.Collapse.propTypes.transitionAppear)
- description and source-code
```javascript
transitionAppear = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Collapse.propTypes.unmountOnExit"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Collapse.propTypes.</span>unmountOnExit ()](#apidoc.element.react-bootstrap.Collapse.propTypes.unmountOnExit)
- description and source-code
```javascript
unmountOnExit = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Collapse.prototype"></a>[module react-bootstrap.Collapse.prototype](#apidoc.module.react-bootstrap.Collapse.prototype)

#### <a name="apidoc.element.react-bootstrap.Collapse.prototype._dimension"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Collapse.prototype.</span>_dimension ()](#apidoc.element.react-bootstrap.Collapse.prototype._dimension)
- description and source-code
```javascript
function _dimension() {
  return typeof this.props.dimension === 'function' ? this.props.dimension() : this.props.dimension;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Collapse.prototype._getScrollDimensionValue"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Collapse.prototype.</span>_getScrollDimensionValue (elem, dimension)](#apidoc.element.react-bootstrap.Collapse.prototype._getScrollDimensionValue)
- description and source-code
```javascript
function _getScrollDimensionValue(elem, dimension) {
  return elem['scroll' + (0, _capitalize2['default'])(dimension)] + 'px';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Collapse.prototype.handleEnter"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Collapse.prototype.</span>handleEnter (elem)](#apidoc.element.react-bootstrap.Collapse.prototype.handleEnter)
- description and source-code
```javascript
function handleEnter(elem) {
  var dimension = this._dimension();
  elem.style[dimension] = '0';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Collapse.prototype.handleEntered"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Collapse.prototype.</span>handleEntered (elem)](#apidoc.element.react-bootstrap.Collapse.prototype.handleEntered)
- description and source-code
```javascript
function handleEntered(elem) {
  var dimension = this._dimension();
  elem.style[dimension] = null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Collapse.prototype.handleEntering"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Collapse.prototype.</span>handleEntering (elem)](#apidoc.element.react-bootstrap.Collapse.prototype.handleEntering)
- description and source-code
```javascript
function handleEntering(elem) {
  var dimension = this._dimension();
  elem.style[dimension] = this._getScrollDimensionValue(elem, dimension);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Collapse.prototype.handleExit"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Collapse.prototype.</span>handleExit (elem)](#apidoc.element.react-bootstrap.Collapse.prototype.handleExit)
- description and source-code
```javascript
function handleExit(elem) {
  var dimension = this._dimension();
  elem.style[dimension] = this.props.getDimensionValue(dimension, elem) + 'px';
  triggerBrowserReflow(elem);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Collapse.prototype.handleExiting"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Collapse.prototype.</span>handleExiting (elem)](#apidoc.element.react-bootstrap.Collapse.prototype.handleExiting)
- description and source-code
```javascript
function handleExiting(elem) {
  var dimension = this._dimension();
  elem.style[dimension] = '0';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Collapse.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Collapse.prototype.</span>render ()](#apidoc.element.react-bootstrap.Collapse.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      onEnter = _props.onEnter,
      onEntering = _props.onEntering,
      onEntered = _props.onEntered,
      onExit = _props.onExit,
      onExiting = _props.onExiting,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['onEnter', 'onEntering', 'onEntered', 'onExit', 'onExiting', 'className
']);


  delete props.dimension;
  delete props.getDimensionValue;

  var handleEnter = (0, _createChainedFunction2['default'])(this.handleEnter, onEnter);
  var handleEntering = (0, _createChainedFunction2['default'])(this.handleEntering, onEntering);
  var handleEntered = (0, _createChainedFunction2['default'])(this.handleEntered, onEntered);
  var handleExit = (0, _createChainedFunction2['default'])(this.handleExit, onExit);
  var handleExiting = (0, _createChainedFunction2['default'])(this.handleExiting, onExiting);

  var classes = {
    width: this._dimension() === 'width'
  };

  return _react2['default'].createElement(_Transition2['default'], (0, _extends3['default'])({}, props, {
    'aria-expanded': props.role ? props['in'] : null,
    className: (0, _classnames2['default'])(className, classes),
    exitedClassName: 'collapse',
    exitingClassName: 'collapsing',
    enteredClassName: 'collapse in',
    enteringClassName: 'collapsing',
    onEnter: handleEnter,
    onEntering: handleEntering,
    onEntered: handleEntered,
    onExit: handleExit,
    onExiting: handleExiting
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ControlLabel"></a>[module react-bootstrap.ControlLabel](#apidoc.module.react-bootstrap.ControlLabel)

#### <a name="apidoc.element.react-bootstrap.ControlLabel.ControlLabel"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>ControlLabel ()](#apidoc.element.react-bootstrap.ControlLabel.ControlLabel)
- description and source-code
```javascript
function ControlLabel() {
  (0, _classCallCheck3['default'])(this, ControlLabel);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ControlLabel.contextTypes"></a>[module react-bootstrap.ControlLabel.contextTypes](#apidoc.module.react-bootstrap.ControlLabel.contextTypes)



# <a name="apidoc.module.react-bootstrap.ControlLabel.propTypes"></a>[module react-bootstrap.ControlLabel.propTypes](#apidoc.module.react-bootstrap.ControlLabel.propTypes)

#### <a name="apidoc.element.react-bootstrap.ControlLabel.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ControlLabel.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.ControlLabel.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ControlLabel.propTypes.htmlFor"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ControlLabel.propTypes.</span>htmlFor ()](#apidoc.element.react-bootstrap.ControlLabel.propTypes.htmlFor)
- description and source-code
```javascript
htmlFor = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ControlLabel.propTypes.srOnly"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ControlLabel.propTypes.</span>srOnly ()](#apidoc.element.react-bootstrap.ControlLabel.propTypes.srOnly)
- description and source-code
```javascript
srOnly = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ControlLabel.prototype"></a>[module react-bootstrap.ControlLabel.prototype](#apidoc.module.react-bootstrap.ControlLabel.prototype)

#### <a name="apidoc.element.react-bootstrap.ControlLabel.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ControlLabel.prototype.</span>render ()](#apidoc.element.react-bootstrap.ControlLabel.prototype.render)
- description and source-code
```javascript
function render() {
  var formGroup = this.context.$bs_formGroup;
  var controlId = formGroup && formGroup.controlId;

  var _props = this.props,
      _props$htmlFor = _props.htmlFor,
      htmlFor = _props$htmlFor === undefined ? controlId : _props$htmlFor,
      srOnly = _props.srOnly,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['htmlFor', 'srOnly', 'className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  process.env.NODE_ENV !== 'production' ? (0, _warning2['default'])(controlId == null || htmlFor === controlId, ''controlId' is
ignored on '<ControlLabel>' when 'htmlFor' is specified.') : void 0;

  var classes = (0, _extends3['default'])({}, (0, _bootstrapUtils.getClassSet)(bsProps), {
    'sr-only': srOnly
  });

  return _react2['default'].createElement('label', (0, _extends3['default'])({}, elementProps, {
    htmlFor: htmlFor,
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Dropdown"></a>[module react-bootstrap.Dropdown](#apidoc.module.react-bootstrap.Dropdown)

#### <a name="apidoc.element.react-bootstrap.Dropdown.Dropdown"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Dropdown (props, context, updater)](#apidoc.element.react-bootstrap.Dropdown.Dropdown)
- description and source-code
```javascript
Dropdown = function (props, context, updater) {
  // This constructor gets overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : void 0;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindPairs.length) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (initialState === undefined && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : _prodInvariant('82',
Constructor.displayName || 'ReactCompositeComponent') : void 0;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Dropdown.ControlledComponent"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.</span>ControlledComponent (props, context)](#apidoc.element.react-bootstrap.Dropdown.ControlledComponent)
- description and source-code
```javascript
function Dropdown(props, context) {
  (0, _classCallCheck3['default'])(this, Dropdown);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleClick = _this.handleClick.bind(_this);
  _this.handleKeyDown = _this.handleKeyDown.bind(_this);
  _this.handleClose = _this.handleClose.bind(_this);

  _this._focusInDropdown = false;
  _this.lastOpenEventType = null;
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Dropdown.Menu"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.</span>Menu (props)](#apidoc.element.react-bootstrap.Dropdown.Menu)
- description and source-code
```javascript
function DropdownMenu(props) {
  (0, _classCallCheck3['default'])(this, DropdownMenu);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props));

  _this.handleRootClose = _this.handleRootClose.bind(_this);
  _this.handleKeyDown = _this.handleKeyDown.bind(_this);
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Dropdown.Toggle"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.</span>Toggle ()](#apidoc.element.react-bootstrap.Dropdown.Toggle)
- description and source-code
```javascript
function DropdownToggle() {
  (0, _classCallCheck3['default'])(this, DropdownToggle);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Dropdown.deferControlTo"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.</span>deferControlTo (newComponent)](#apidoc.element.react-bootstrap.Dropdown.deferControlTo)
- description and source-code
```javascript
deferControlTo = function (newComponent) {
  var additions = arguments.length <= 1 || arguments[1] === undefined ? {} : arguments[1];
  var nextMethods = arguments[2];

  return uncontrollable(newComponent, _extends({}, controlledValues, additions), nextMethods);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Dropdown.ControlledComponent"></a>[module react-bootstrap.Dropdown.ControlledComponent](#apidoc.module.react-bootstrap.Dropdown.ControlledComponent)

#### <a name="apidoc.element.react-bootstrap.Dropdown.ControlledComponent.ControlledComponent"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.</span>ControlledComponent (props, context)](#apidoc.element.react-bootstrap.Dropdown.ControlledComponent.ControlledComponent)
- description and source-code
```javascript
function Dropdown(props, context) {
  (0, _classCallCheck3['default'])(this, Dropdown);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleClick = _this.handleClick.bind(_this);
  _this.handleKeyDown = _this.handleKeyDown.bind(_this);
  _this.handleClose = _this.handleClose.bind(_this);

  _this._focusInDropdown = false;
  _this.lastOpenEventType = null;
  return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Dropdown.ControlledComponent.prototype"></a>[module react-bootstrap.Dropdown.ControlledComponent.prototype](#apidoc.module.react-bootstrap.Dropdown.ControlledComponent.prototype)

#### <a name="apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.componentDidMount"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.ControlledComponent.prototype.</span>componentDidMount ()](#apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.componentDidMount)
- description and source-code
```javascript
function componentDidMount() {
  this.focusNextOnOpen();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.componentDidUpdate"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.ControlledComponent.prototype.</span>componentDidUpdate (prevProps)](#apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.componentDidUpdate)
- description and source-code
```javascript
function componentDidUpdate(prevProps) {
  var open = this.props.open;

  var prevOpen = prevProps.open;

  if (open && !prevOpen) {
    this.focusNextOnOpen();
  }

  if (!open && prevOpen) {
    // if focus hasn't already moved from the menu lets return it
    // to the toggle
    if (this._focusInDropdown) {
      this._focusInDropdown = false;
      this.focus();
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.componentWillUpdate"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.ControlledComponent.prototype.</span>componentWillUpdate (nextProps)](#apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.componentWillUpdate)
- description and source-code
```javascript
function componentWillUpdate(nextProps) {
  if (!nextProps.open && this.props.open) {
    this._focusInDropdown = (0, _contains2['default'])(_reactDom2['default'].findDOMNode(this.menu), (0, _activeElement2['default
'])(document));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.focus"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.ControlledComponent.prototype.</span>focus ()](#apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.focus)
- description and source-code
```javascript
function focus() {
  var toggle = _reactDom2['default'].findDOMNode(this.toggle);

  if (toggle && toggle.focus) {
    toggle.focus();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.focusNextOnOpen"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.ControlledComponent.prototype.</span>focusNextOnOpen ()](#apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.focusNextOnOpen)
- description and source-code
```javascript
function focusNextOnOpen() {
  var menu = this.menu;

  if (!menu.focusNext) {
    return;
  }

  if (this.lastOpenEventType === 'keydown' || this.props.role === 'menuitem') {
    menu.focusNext();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.handleClick"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.ControlledComponent.prototype.</span>handleClick (event)](#apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.handleClick)
- description and source-code
```javascript
function handleClick(event) {
  if (this.props.disabled) {
    return;
  }

  this.toggleOpen(event, { source: 'click' });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.handleClose"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.ControlledComponent.prototype.</span>handleClose (event, eventDetails)](#apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.handleClose)
- description and source-code
```javascript
function handleClose(event, eventDetails) {
  if (!this.props.open) {
    return;
  }

  this.toggleOpen(event, eventDetails);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.handleKeyDown"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.ControlledComponent.prototype.</span>handleKeyDown (event)](#apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.handleKeyDown)
- description and source-code
```javascript
function handleKeyDown(event) {
  if (this.props.disabled) {
    return;
  }

  switch (event.keyCode) {
    case _keycode2['default'].codes.down:
      if (!this.props.open) {
        this.toggleOpen(event, { source: 'keydown' });
      } else if (this.menu.focusNext) {
        this.menu.focusNext();
      }
      event.preventDefault();
      break;
    case _keycode2['default'].codes.esc:
    case _keycode2['default'].codes.tab:
      this.handleClose(event, { source: 'keydown' });
      break;
    default:
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.ControlledComponent.prototype.</span>render ()](#apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.render)
- description and source-code
```javascript
function render() {
  var _classes,
      _this4 = this;

  var _props = this.props,
      Component = _props.componentClass,
      id = _props.id,
      dropup = _props.dropup,
      disabled = _props.disabled,
      pullRight = _props.pullRight,
      open = _props.open,
      onClose = _props.onClose,
      onSelect = _props.onSelect,
      role = _props.role,
      bsClass = _props.bsClass,
      className = _props.className,
      rootCloseEvent = _props.rootCloseEvent,
      children = _props.children,
      props = (0, _objectWithoutProperties3['default'])(_props, ['componentClass', 'id', 'dropup', 'disabled', 'pullRight', 'open
', 'onClose', 'onSelect', 'role', 'bsClass', 'className', 'rootCloseEvent', 'children']);


  delete props.onToggle;

  var classes = (_classes = {}, _classes[bsClass] = true, _classes.open = open, _classes.disabled = disabled, _classes);

  if (dropup) {
    classes[bsClass] = false;
    classes.dropup = true;
  }

  // This intentionally forwards bsSize and bsStyle (if set) to the
  // underlying component, to allow it to render size and style variants.

  return _react2['default'].createElement(
    Component,
    (0, _extends3['default'])({}, props, {
      className: (0, _classnames2['default'])(className, classes)
    }),
    _ValidComponentChildren2['default'].map(children, function (child) {
      switch (child.props.bsRole) {
        case TOGGLE_ROLE:
          return _this4.renderToggle(child, {
            id: id, disabled: disabled, open: open, role: role, bsClass: bsClass
          });
        case MENU_ROLE:
          return _this4.renderMenu(child, {
            id: id, open: open, pullRight: pullRight, bsClass: bsClass, onClose: onClose, onSelect: onSelect, rootCloseEvent: rootCloseEvent
          });
        default:
          return child;
      }
    })
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.renderMenu"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.ControlledComponent.prototype.</span>renderMenu (child, _ref)](#apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.renderMenu)
- description and source-code
```javascript
function renderMenu(child, _ref) {
  var _this3 = this;

  var id = _ref.id,
      onClose = _ref.onClose,
      onSelect = _ref.onSelect,
      rootCloseEvent = _ref.rootCloseEvent,
      props = (0, _objectWithoutProperties3['default'])(_ref, ['id', 'onClose', 'onSelect', 'rootCloseEvent']);

  var ref = function ref(c) {
    _this3.menu = c;
  };

  if (typeof child.ref === 'string') {
    process.env.NODE_ENV !== 'production' ? (0, _warning2['default'])(false, 'String refs are not supported on '<Dropdown.Menu>'
components. ' + 'To apply a ref to the component use the callback signature:\n\n ' + 'https://facebook.github.io/react/docs/more-about-refs.html#the-ref-callback-attribute') : void 0;
  } else {
    ref = (0, _createChainedFunction2['default'])(child.ref, ref);
  }

  return (0, _react.cloneElement)(child, (0, _extends3['default'])({}, props, {
    ref: ref,
    labelledBy: id,
    bsClass: (0, _bootstrapUtils.prefix)(props, 'menu'),
    onClose: (0, _createChainedFunction2['default'])(child.props.onClose, onClose, this.handleClose),
    onSelect: (0, _createChainedFunction2['default'])(child.props.onSelect, onSelect, function (key, event) {
      return _this3.handleClose(event, { source: 'select' });
    }),
    rootCloseEvent: rootCloseEvent
  }));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.renderToggle"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.ControlledComponent.prototype.</span>renderToggle (child, props)](#apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.renderToggle)
- description and source-code
```javascript
function renderToggle(child, props) {
  var _this2 = this;

  var ref = function ref(c) {
    _this2.toggle = c;
  };

  if (typeof child.ref === 'string') {
    process.env.NODE_ENV !== 'production' ? (0, _warning2['default'])(false, 'String refs are not supported on '<Dropdown.Toggle
>' components. ' + 'To apply a ref to the component use the callback signature:\n\n ' + 'https://facebook.github.io/react/docs/more-about-refs.html#the-ref-callback-attribute') : void 0;
  } else {
    ref = (0, _createChainedFunction2['default'])(child.ref, ref);
  }

  return (0, _react.cloneElement)(child, (0, _extends3['default'])({}, props, {
    ref: ref,
    bsClass: (0, _bootstrapUtils.prefix)(props, 'toggle'),
    onClick: (0, _createChainedFunction2['default'])(child.props.onClick, this.handleClick),
    onKeyDown: (0, _createChainedFunction2['default'])(child.props.onKeyDown, this.handleKeyDown)
  }));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.toggleOpen"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.ControlledComponent.prototype.</span>toggleOpen (event, eventDetails)](#apidoc.element.react-bootstrap.Dropdown.ControlledComponent.prototype.toggleOpen)
- description and source-code
```javascript
function toggleOpen(event, eventDetails) {
  var open = !this.props.open;

  if (open) {
    this.lastOpenEventType = eventDetails.source;
  }

  if (this.props.onToggle) {
    this.props.onToggle(open, event, eventDetails);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Dropdown.Menu"></a>[module react-bootstrap.Dropdown.Menu](#apidoc.module.react-bootstrap.Dropdown.Menu)

#### <a name="apidoc.element.react-bootstrap.Dropdown.Menu.Menu"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.</span>Menu (props)](#apidoc.element.react-bootstrap.Dropdown.Menu.Menu)
- description and source-code
```javascript
function DropdownMenu(props) {
  (0, _classCallCheck3['default'])(this, DropdownMenu);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props));

  _this.handleRootClose = _this.handleRootClose.bind(_this);
  _this.handleKeyDown = _this.handleKeyDown.bind(_this);
  return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Dropdown.Menu.prototype"></a>[module react-bootstrap.Dropdown.Menu.prototype](#apidoc.module.react-bootstrap.Dropdown.Menu.prototype)

#### <a name="apidoc.element.react-bootstrap.Dropdown.Menu.prototype.focusNext"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.Menu.prototype.</span>focusNext ()](#apidoc.element.react-bootstrap.Dropdown.Menu.prototype.focusNext)
- description and source-code
```javascript
function focusNext() {
  var _getItemsAndActiveInd = this.getItemsAndActiveIndex(),
      items = _getItemsAndActiveInd.items,
      activeIndex = _getItemsAndActiveInd.activeIndex;

  if (items.length === 0) {
    return;
  }

  var nextIndex = activeIndex === items.length - 1 ? 0 : activeIndex + 1;
  items[nextIndex].focus();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Dropdown.Menu.prototype.focusPrevious"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.Menu.prototype.</span>focusPrevious ()](#apidoc.element.react-bootstrap.Dropdown.Menu.prototype.focusPrevious)
- description and source-code
```javascript
function focusPrevious() {
  var _getItemsAndActiveInd2 = this.getItemsAndActiveIndex(),
      items = _getItemsAndActiveInd2.items,
      activeIndex = _getItemsAndActiveInd2.activeIndex;

  if (items.length === 0) {
    return;
  }

  var prevIndex = activeIndex === 0 ? items.length - 1 : activeIndex - 1;
  items[prevIndex].focus();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Dropdown.Menu.prototype.getFocusableMenuItems"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.Menu.prototype.</span>getFocusableMenuItems ()](#apidoc.element.react-bootstrap.Dropdown.Menu.prototype.getFocusableMenuItems)
- description and source-code
```javascript
function getFocusableMenuItems() {
  var node = _reactDom2['default'].findDOMNode(this);
  if (!node) {
    return [];
  }

  return (0, _from2['default'])(node.querySelectorAll('[tabIndex="-1"]'));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Dropdown.Menu.prototype.getItemsAndActiveIndex"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.Menu.prototype.</span>getItemsAndActiveIndex ()](#apidoc.element.react-bootstrap.Dropdown.Menu.prototype.getItemsAndActiveIndex)
- description and source-code
```javascript
function getItemsAndActiveIndex() {
  var items = this.getFocusableMenuItems();
  var activeIndex = items.indexOf(document.activeElement);

  return { items: items, activeIndex: activeIndex };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Dropdown.Menu.prototype.handleKeyDown"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.Menu.prototype.</span>handleKeyDown (event)](#apidoc.element.react-bootstrap.Dropdown.Menu.prototype.handleKeyDown)
- description and source-code
```javascript
function handleKeyDown(event) {
  switch (event.keyCode) {
    case _keycode2['default'].codes.down:
      this.focusNext();
      event.preventDefault();
      break;
    case _keycode2['default'].codes.up:
      this.focusPrevious();
      event.preventDefault();
      break;
    case _keycode2['default'].codes.esc:
    case _keycode2['default'].codes.tab:
      this.props.onClose(event, { source: 'keydown' });
      break;
    default:
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Dropdown.Menu.prototype.handleRootClose"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.Menu.prototype.</span>handleRootClose (event)](#apidoc.element.react-bootstrap.Dropdown.Menu.prototype.handleRootClose)
- description and source-code
```javascript
function handleRootClose(event) {
  this.props.onClose(event, { source: 'rootClose' });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Dropdown.Menu.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.Menu.prototype.</span>render ()](#apidoc.element.react-bootstrap.Dropdown.Menu.prototype.render)
- description and source-code
```javascript
function render() {
  var _extends2,
      _this2 = this;

  var _props = this.props,
      open = _props.open,
      pullRight = _props.pullRight,
      labelledBy = _props.labelledBy,
      onSelect = _props.onSelect,
      className = _props.className,
      rootCloseEvent = _props.rootCloseEvent,
      children = _props.children,
      props = (0, _objectWithoutProperties3['default'])(_props, ['open', 'pullRight', 'labelledBy', 'onSelect', 'className', 'rootCloseEvent
', 'children']);

  var _splitBsPropsAndOmit = (0, _bootstrapUtils.splitBsPropsAndOmit)(props, ['onClose']),
      bsProps = _splitBsPropsAndOmit[0],
      elementProps = _splitBsPropsAndOmit[1];

  var classes = (0, _extends4['default'])({}, (0, _bootstrapUtils.getClassSet)(bsProps), (_extends2 = {}, _extends2[(0, _bootstrapUtils
.prefix)(bsProps, 'right')] = pullRight, _extends2));

  return _react2['default'].createElement(
    _RootCloseWrapper2['default'],
    {
      disabled: !open,
      onRootClose: this.handleRootClose,
      event: rootCloseEvent
    },
    _react2['default'].createElement(
      'ul',
      (0, _extends4['default'])({}, elementProps, {
        role: 'menu',
        className: (0, _classnames2['default'])(className, classes),
        'aria-labelledby': labelledBy
      }),
      _ValidComponentChildren2['default'].map(children, function (child) {
        return _react2['default'].cloneElement(child, {
          onKeyDown: (0, _createChainedFunction2['default'])(child.props.onKeyDown, _this2.handleKeyDown),
          onSelect: (0, _createChainedFunction2['default'])(child.props.onSelect, onSelect)
        });
      })
    )
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Dropdown.Toggle"></a>[module react-bootstrap.Dropdown.Toggle](#apidoc.module.react-bootstrap.Dropdown.Toggle)

#### <a name="apidoc.element.react-bootstrap.Dropdown.Toggle.Toggle"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.</span>Toggle ()](#apidoc.element.react-bootstrap.Dropdown.Toggle.Toggle)
- description and source-code
```javascript
function DropdownToggle() {
  (0, _classCallCheck3['default'])(this, DropdownToggle);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Dropdown.Toggle.prototype"></a>[module react-bootstrap.Dropdown.Toggle.prototype](#apidoc.module.react-bootstrap.Dropdown.Toggle.prototype)

#### <a name="apidoc.element.react-bootstrap.Dropdown.Toggle.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.Toggle.prototype.</span>render ()](#apidoc.element.react-bootstrap.Dropdown.Toggle.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      noCaret = _props.noCaret,
      open = _props.open,
      useAnchor = _props.useAnchor,
      bsClass = _props.bsClass,
      className = _props.className,
      children = _props.children,
      props = (0, _objectWithoutProperties3['default'])(_props, ['noCaret', 'open', 'useAnchor', 'bsClass', 'className', 'children
']);


  delete props.bsRole;

  var Component = useAnchor ? _SafeAnchor2['default'] : _Button2['default'];
  var useCaret = !noCaret;

  // This intentionally forwards bsSize and bsStyle (if set) to the
  // underlying component, to allow it to render size and style variants.

  // FIXME: Should this really fall back to 'title' as children?

  return _react2['default'].createElement(
    Component,
    (0, _extends3['default'])({}, props, {
      role: 'button',
      className: (0, _classnames2['default'])(className, bsClass),
      'aria-haspopup': true,
      'aria-expanded': open
    }),
    children || props.title,
    useCaret && ' ',
    useCaret && _react2['default'].createElement('span', { className: 'caret' })
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Dropdown.propTypes"></a>[module react-bootstrap.Dropdown.propTypes](#apidoc.module.react-bootstrap.Dropdown.propTypes)

#### <a name="apidoc.element.react-bootstrap.Dropdown.propTypes.open"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.propTypes.</span>open (props, propName)](#apidoc.element.react-bootstrap.Dropdown.propTypes.open)
- description and source-code
```javascript
open = function (props, propName) {
  if (props[propName] !== undefined) {
    if (!props[handler]) {
      return new Error('You have provided a '' + propName + '' prop to ' + ''' + name + '' without an '' + handler + '' handler.
This will render a read-only field. ' + 'If the field should be mutable use '' + defaultKey(propName) + ''. Otherwise, set '' +
handler + ''');
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Dropdown.prototype"></a>[module react-bootstrap.Dropdown.prototype](#apidoc.module.react-bootstrap.Dropdown.prototype)

#### <a name="apidoc.element.react-bootstrap.Dropdown.prototype.componentWillMount"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.prototype.</span>componentWillMount ()](#apidoc.element.react-bootstrap.Dropdown.prototype.componentWillMount)
- description and source-code
```javascript
function componentWillMount() {
  var _this = this;

  var props = this.props;

  this._values = {};

  controlledProps.forEach(function (key) {
    _this._values[key] = props[utils.defaultKey(key)];
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Dropdown.prototype.componentWillReceiveProps"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.react-bootstrap.Dropdown.prototype.componentWillReceiveProps)
- description and source-code
```javascript
function componentWillReceiveProps(nextProps) {
  var _this2 = this;

  var props = this.props;

  controlledProps.forEach(function (key) {
    if (utils.getValue(nextProps, key) === undefined && utils.getValue(props, key) !== undefined) {
      _this2._values[key] = nextProps[utils.defaultKey(key)];
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Dropdown.prototype.constructor"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.prototype.</span>constructor (props, context, updater)](#apidoc.element.react-bootstrap.Dropdown.prototype.constructor)
- description and source-code
```javascript
constructor = function (props, context, updater) {
  // This constructor gets overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : void 0;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindPairs.length) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (initialState === undefined && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : _prodInvariant('82',
Constructor.displayName || 'ReactCompositeComponent') : void 0;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Dropdown.prototype.getControlledInstance"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.prototype.</span>getControlledInstance ()](#apidoc.element.react-bootstrap.Dropdown.prototype.getControlledInstance)
- description and source-code
```javascript
function getControlledInstance() {
  return this.refs.inner;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Dropdown.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.prototype.</span>render ()](#apidoc.element.react-bootstrap.Dropdown.prototype.render)
- description and source-code
```javascript
function render() {
  var _this3 = this;

  var newProps = {},
      props = omitProps(this.props);

  utils.each(controlledValues, function (handle, propName) {
    var linkPropName = utils.getLinkName(propName),
        prop = _this3.props[propName];

    if (linkPropName && !isProp(_this3.props, propName) && isProp(_this3.props, linkPropName)) {
      prop = _this3.props[linkPropName].value;
    }

    newProps[propName] = prop !== undefined ? prop : _this3._values[propName];

    newProps[handle] = setAndNotify.bind(_this3, propName);
  });

  newProps = _extends({}, props, newProps, {
    ref: isCompositeComponent ? 'inner' : null
  });

  return _react2.default.createElement(Component, newProps);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Dropdown.prototype.shouldComponentUpdate"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.prototype.</span>shouldComponentUpdate ()](#apidoc.element.react-bootstrap.Dropdown.prototype.shouldComponentUpdate)
- description and source-code
```javascript
function shouldComponentUpdate() {
  //let the forceUpdate trigger the update
  return !this._notifying;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Dropdown.prototype.__reactAutoBindPairs"></a>[module react-bootstrap.Dropdown.prototype.__reactAutoBindPairs](#apidoc.module.react-bootstrap.Dropdown.prototype.__reactAutoBindPairs)

#### <a name="apidoc.element.react-bootstrap.Dropdown.prototype.__reactAutoBindPairs.1"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Dropdown.prototype.__reactAutoBindPairs.</span>1 ()](#apidoc.element.react-bootstrap.Dropdown.prototype.__reactAutoBindPairs.1)
- description and source-code
```javascript
function getControlledInstance() {
  return this.refs.inner;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.DropdownButton"></a>[module react-bootstrap.DropdownButton](#apidoc.module.react-bootstrap.DropdownButton)

#### <a name="apidoc.element.react-bootstrap.DropdownButton.DropdownButton"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>DropdownButton ()](#apidoc.element.react-bootstrap.DropdownButton.DropdownButton)
- description and source-code
```javascript
function DropdownButton() {
  (0, _classCallCheck3['default'])(this, DropdownButton);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.DropdownButton.propTypes"></a>[module react-bootstrap.DropdownButton.propTypes](#apidoc.module.react-bootstrap.DropdownButton.propTypes)

#### <a name="apidoc.element.react-bootstrap.DropdownButton.propTypes.bsSize"></a>[function <span class="apidocSignatureSpan">react-bootstrap.DropdownButton.propTypes.</span>bsSize ()](#apidoc.element.react-bootstrap.DropdownButton.propTypes.bsSize)
- description and source-code
```javascript
bsSize = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.DropdownButton.propTypes.bsStyle"></a>[function <span class="apidocSignatureSpan">react-bootstrap.DropdownButton.propTypes.</span>bsStyle ()](#apidoc.element.react-bootstrap.DropdownButton.propTypes.bsStyle)
- description and source-code
```javascript
bsStyle = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.DropdownButton.propTypes.children"></a>[function <span class="apidocSignatureSpan">react-bootstrap.DropdownButton.propTypes.</span>children ()](#apidoc.element.react-bootstrap.DropdownButton.propTypes.children)
- description and source-code
```javascript
children = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.DropdownButton.propTypes.noCaret"></a>[function <span class="apidocSignatureSpan">react-bootstrap.DropdownButton.propTypes.</span>noCaret ()](#apidoc.element.react-bootstrap.DropdownButton.propTypes.noCaret)
- description and source-code
```javascript
noCaret = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.DropdownButton.propTypes.open"></a>[function <span class="apidocSignatureSpan">react-bootstrap.DropdownButton.propTypes.</span>open (props, propName)](#apidoc.element.react-bootstrap.DropdownButton.propTypes.open)
- description and source-code
```javascript
open = function (props, propName) {
  if (props[propName] !== undefined) {
    if (!props[handler]) {
      return new Error('You have provided a '' + propName + '' prop to ' + ''' + name + '' without an '' + handler + '' handler.
This will render a read-only field. ' + 'If the field should be mutable use '' + defaultKey(propName) + ''. Otherwise, set '' +
handler + ''');
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.DropdownButton.propTypes.title"></a>[function <span class="apidocSignatureSpan">react-bootstrap.DropdownButton.propTypes.</span>title ()](#apidoc.element.react-bootstrap.DropdownButton.propTypes.title)
- description and source-code
```javascript
title = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.DropdownButton.prototype"></a>[module react-bootstrap.DropdownButton.prototype](#apidoc.module.react-bootstrap.DropdownButton.prototype)

#### <a name="apidoc.element.react-bootstrap.DropdownButton.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.DropdownButton.prototype.</span>render ()](#apidoc.element.react-bootstrap.DropdownButton.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      bsSize = _props.bsSize,
      bsStyle = _props.bsStyle,
      title = _props.title,
      children = _props.children,
      props = (0, _objectWithoutProperties3['default'])(_props, ['bsSize', 'bsStyle', 'title', 'children']);

  var _splitComponentProps = (0, _splitComponentProps3['default'])(props, _Dropdown2['default'].ControlledComponent),
      dropdownProps = _splitComponentProps[0],
      toggleProps = _splitComponentProps[1];

  return _react2['default'].createElement(
    _Dropdown2['default'],
    (0, _extends3['default'])({}, dropdownProps, {
      bsSize: bsSize,
      bsStyle: bsStyle
    }),
    _react2['default'].createElement(
      _Dropdown2['default'].Toggle,
      (0, _extends3['default'])({}, toggleProps, {
        bsSize: bsSize,
        bsStyle: bsStyle
      }),
      title
    ),
    _react2['default'].createElement(
      _Dropdown2['default'].Menu,
      null,
      children
    )
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Fade"></a>[module react-bootstrap.Fade](#apidoc.module.react-bootstrap.Fade)

#### <a name="apidoc.element.react-bootstrap.Fade.Fade"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Fade ()](#apidoc.element.react-bootstrap.Fade.Fade)
- description and source-code
```javascript
function Fade() {
  (0, _classCallCheck3['default'])(this, Fade);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Fade.propTypes"></a>[module react-bootstrap.Fade.propTypes](#apidoc.module.react-bootstrap.Fade.propTypes)

#### <a name="apidoc.element.react-bootstrap.Fade.propTypes.in"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Fade.propTypes.</span>in ()](#apidoc.element.react-bootstrap.Fade.propTypes.in)
- description and source-code
```javascript
in = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Fade.propTypes.mountOnEnter"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Fade.propTypes.</span>mountOnEnter ()](#apidoc.element.react-bootstrap.Fade.propTypes.mountOnEnter)
- description and source-code
```javascript
mountOnEnter = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Fade.propTypes.onEnter"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Fade.propTypes.</span>onEnter ()](#apidoc.element.react-bootstrap.Fade.propTypes.onEnter)
- description and source-code
```javascript
onEnter = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Fade.propTypes.onEntered"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Fade.propTypes.</span>onEntered ()](#apidoc.element.react-bootstrap.Fade.propTypes.onEntered)
- description and source-code
```javascript
onEntered = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Fade.propTypes.onEntering"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Fade.propTypes.</span>onEntering ()](#apidoc.element.react-bootstrap.Fade.propTypes.onEntering)
- description and source-code
```javascript
onEntering = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Fade.propTypes.onExit"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Fade.propTypes.</span>onExit ()](#apidoc.element.react-bootstrap.Fade.propTypes.onExit)
- description and source-code
```javascript
onExit = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Fade.propTypes.onExited"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Fade.propTypes.</span>onExited ()](#apidoc.element.react-bootstrap.Fade.propTypes.onExited)
- description and source-code
```javascript
onExited = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Fade.propTypes.onExiting"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Fade.propTypes.</span>onExiting ()](#apidoc.element.react-bootstrap.Fade.propTypes.onExiting)
- description and source-code
```javascript
onExiting = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Fade.propTypes.timeout"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Fade.propTypes.</span>timeout ()](#apidoc.element.react-bootstrap.Fade.propTypes.timeout)
- description and source-code
```javascript
timeout = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Fade.propTypes.transitionAppear"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Fade.propTypes.</span>transitionAppear ()](#apidoc.element.react-bootstrap.Fade.propTypes.transitionAppear)
- description and source-code
```javascript
transitionAppear = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Fade.propTypes.unmountOnExit"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Fade.propTypes.</span>unmountOnExit ()](#apidoc.element.react-bootstrap.Fade.propTypes.unmountOnExit)
- description and source-code
```javascript
unmountOnExit = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Fade.prototype"></a>[module react-bootstrap.Fade.prototype](#apidoc.module.react-bootstrap.Fade.prototype)

#### <a name="apidoc.element.react-bootstrap.Fade.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Fade.prototype.</span>render ()](#apidoc.element.react-bootstrap.Fade.prototype.render)
- description and source-code
```javascript
function render() {
  return _react2['default'].createElement(_Transition2['default'], (0, _extends3['default'])({}, this.props, {
    className: (0, _classnames2['default'])(this.props.className, 'fade'),
    enteredClassName: 'in',
    enteringClassName: 'in'
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Form"></a>[module react-bootstrap.Form](#apidoc.module.react-bootstrap.Form)

#### <a name="apidoc.element.react-bootstrap.Form.Form"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Form ()](#apidoc.element.react-bootstrap.Form.Form)
- description and source-code
```javascript
function Form() {
  (0, _classCallCheck3['default'])(this, Form);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Form.propTypes"></a>[module react-bootstrap.Form.propTypes](#apidoc.module.react-bootstrap.Form.propTypes)

#### <a name="apidoc.element.react-bootstrap.Form.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Form.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Form.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Form.propTypes.componentClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Form.propTypes.</span>componentClass ()](#apidoc.element.react-bootstrap.Form.propTypes.componentClass)
- description and source-code
```javascript
componentClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Form.propTypes.horizontal"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Form.propTypes.</span>horizontal ()](#apidoc.element.react-bootstrap.Form.propTypes.horizontal)
- description and source-code
```javascript
horizontal = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Form.propTypes.inline"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Form.propTypes.</span>inline ()](#apidoc.element.react-bootstrap.Form.propTypes.inline)
- description and source-code
```javascript
inline = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Form.prototype"></a>[module react-bootstrap.Form.prototype](#apidoc.module.react-bootstrap.Form.prototype)

#### <a name="apidoc.element.react-bootstrap.Form.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Form.prototype.</span>render ()](#apidoc.element.react-bootstrap.Form.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      horizontal = _props.horizontal,
      inline = _props.inline,
      Component = _props.componentClass,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['horizontal', 'inline', 'componentClass', 'className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = [];
  if (horizontal) {
    classes.push((0, _bootstrapUtils.prefix)(bsProps, 'horizontal'));
  }
  if (inline) {
    classes.push((0, _bootstrapUtils.prefix)(bsProps, 'inline'));
  }

  return _react2['default'].createElement(Component, (0, _extends3['default'])({}, elementProps, {
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.FormControl"></a>[module react-bootstrap.FormControl](#apidoc.module.react-bootstrap.FormControl)

#### <a name="apidoc.element.react-bootstrap.FormControl.FormControl"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>FormControl ()](#apidoc.element.react-bootstrap.FormControl.FormControl)
- description and source-code
```javascript
function FormControl() {
  (0, _classCallCheck3['default'])(this, FormControl);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.FormControl.Feedback"></a>[function <span class="apidocSignatureSpan">react-bootstrap.FormControl.</span>Feedback ()](#apidoc.element.react-bootstrap.FormControl.Feedback)
- description and source-code
```javascript
function FormControlFeedback() {
  (0, _classCallCheck3['default'])(this, FormControlFeedback);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.FormControl.Static"></a>[function <span class="apidocSignatureSpan">react-bootstrap.FormControl.</span>Static ()](#apidoc.element.react-bootstrap.FormControl.Static)
- description and source-code
```javascript
function FormControlStatic() {
  (0, _classCallCheck3['default'])(this, FormControlStatic);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.FormControl.Feedback"></a>[module react-bootstrap.FormControl.Feedback](#apidoc.module.react-bootstrap.FormControl.Feedback)

#### <a name="apidoc.element.react-bootstrap.FormControl.Feedback.Feedback"></a>[function <span class="apidocSignatureSpan">react-bootstrap.FormControl.</span>Feedback ()](#apidoc.element.react-bootstrap.FormControl.Feedback.Feedback)
- description and source-code
```javascript
function FormControlFeedback() {
  (0, _classCallCheck3['default'])(this, FormControlFeedback);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.FormControl.Feedback.prototype"></a>[module react-bootstrap.FormControl.Feedback.prototype](#apidoc.module.react-bootstrap.FormControl.Feedback.prototype)

#### <a name="apidoc.element.react-bootstrap.FormControl.Feedback.prototype.getGlyph"></a>[function <span class="apidocSignatureSpan">react-bootstrap.FormControl.Feedback.prototype.</span>getGlyph (validationState)](#apidoc.element.react-bootstrap.FormControl.Feedback.prototype.getGlyph)
- description and source-code
```javascript
function getGlyph(validationState) {
  switch (validationState) {
    case 'success':
      return 'ok';
    case 'warning':
      return 'warning-sign';
    case 'error':
      return 'remove';
    default:
      return null;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.FormControl.Feedback.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.FormControl.Feedback.prototype.</span>render ()](#apidoc.element.react-bootstrap.FormControl.Feedback.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      className = _props.className,
      children = _props.children,
      props = (0, _objectWithoutProperties3['default'])(_props, ['className', 'children']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _bootstrapUtils.getClassSet)(bsProps);

  if (!children) {
    return this.renderDefaultFeedback(this.context.$bs_formGroup, className, classes, elementProps);
  }

  var child = _react2['default'].Children.only(children);
  return _react2['default'].cloneElement(child, (0, _extends3['default'])({}, elementProps, {
    className: (0, _classnames2['default'])(child.props.className, className, classes)
  }));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.FormControl.Feedback.prototype.renderDefaultFeedback"></a>[function <span class="apidocSignatureSpan">react-bootstrap.FormControl.Feedback.prototype.</span>renderDefaultFeedback (formGroup, className, classes, elementProps)](#apidoc.element.react-bootstrap.FormControl.Feedback.prototype.renderDefaultFeedback)
- description and source-code
```javascript
function renderDefaultFeedback(formGroup, className, classes, elementProps) {
  var glyph = this.getGlyph(formGroup && formGroup.validationState);
  if (!glyph) {
    return null;
  }

  return _react2['default'].createElement(_Glyphicon2['default'], (0, _extends3['default'])({}, elementProps, {
    glyph: glyph,
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.FormControl.Static"></a>[module react-bootstrap.FormControl.Static](#apidoc.module.react-bootstrap.FormControl.Static)

#### <a name="apidoc.element.react-bootstrap.FormControl.Static.Static"></a>[function <span class="apidocSignatureSpan">react-bootstrap.FormControl.</span>Static ()](#apidoc.element.react-bootstrap.FormControl.Static.Static)
- description and source-code
```javascript
function FormControlStatic() {
  (0, _classCallCheck3['default'])(this, FormControlStatic);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.FormControl.Static.prototype"></a>[module react-bootstrap.FormControl.Static.prototype](#apidoc.module.react-bootstrap.FormControl.Static.prototype)

#### <a name="apidoc.element.react-bootstrap.FormControl.Static.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.FormControl.Static.prototype.</span>render ()](#apidoc.element.react-bootstrap.FormControl.Static.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      Component = _props.componentClass,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['componentClass', 'className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _bootstrapUtils.getClassSet)(bsProps);

  return _react2['default'].createElement(Component, (0, _extends3['default'])({}, elementProps, {
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.FormControl.contextTypes"></a>[module react-bootstrap.FormControl.contextTypes](#apidoc.module.react-bootstrap.FormControl.contextTypes)



# <a name="apidoc.module.react-bootstrap.FormControl.propTypes"></a>[module react-bootstrap.FormControl.propTypes](#apidoc.module.react-bootstrap.FormControl.propTypes)

#### <a name="apidoc.element.react-bootstrap.FormControl.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.FormControl.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.FormControl.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.FormControl.propTypes.bsSize"></a>[function <span class="apidocSignatureSpan">react-bootstrap.FormControl.propTypes.</span>bsSize ()](#apidoc.element.react-bootstrap.FormControl.propTypes.bsSize)
- description and source-code
```javascript
bsSize = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.FormControl.propTypes.componentClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.FormControl.propTypes.</span>componentClass ()](#apidoc.element.react-bootstrap.FormControl.propTypes.componentClass)
- description and source-code
```javascript
componentClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.FormControl.propTypes.id"></a>[function <span class="apidocSignatureSpan">react-bootstrap.FormControl.propTypes.</span>id ()](#apidoc.element.react-bootstrap.FormControl.propTypes.id)
- description and source-code
```javascript
id = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.FormControl.propTypes.inputRef"></a>[function <span class="apidocSignatureSpan">react-bootstrap.FormControl.propTypes.</span>inputRef ()](#apidoc.element.react-bootstrap.FormControl.propTypes.inputRef)
- description and source-code
```javascript
inputRef = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.FormControl.propTypes.type"></a>[function <span class="apidocSignatureSpan">react-bootstrap.FormControl.propTypes.</span>type ()](#apidoc.element.react-bootstrap.FormControl.propTypes.type)
- description and source-code
```javascript
type = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.FormControl.prototype"></a>[module react-bootstrap.FormControl.prototype](#apidoc.module.react-bootstrap.FormControl.prototype)

#### <a name="apidoc.element.react-bootstrap.FormControl.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.FormControl.prototype.</span>render ()](#apidoc.element.react-bootstrap.FormControl.prototype.render)
- description and source-code
```javascript
function render() {
  var formGroup = this.context.$bs_formGroup;
  var controlId = formGroup && formGroup.controlId;

  var _props = this.props,
      Component = _props.componentClass,
      type = _props.type,
      _props$id = _props.id,
      id = _props$id === undefined ? controlId : _props$id,
      inputRef = _props.inputRef,
      className = _props.className,
      bsSize = _props.bsSize,
      props = (0, _objectWithoutProperties3['default'])(_props, ['componentClass', 'type', 'id', 'inputRef', 'className', 'bsSize
']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  process.env.NODE_ENV !== 'production' ? (0, _warning2['default'])(controlId == null || id === controlId, ''controlId' is ignored
 on '<FormControl>' when 'id' is specified.') : void 0;

  // input[type="file"] should not have .form-control.
  var classes = void 0;
  if (type !== 'file') {
    classes = (0, _bootstrapUtils.getClassSet)(bsProps);
  }

  // If user provides a size, make sure to append it to classes as input-
  // e.g. if bsSize is small, it will append input-sm
  if (bsSize) {
    var size = _StyleConfig.SIZE_MAP[bsSize] || bsSize;
    classes[(0, _bootstrapUtils.prefix)({ bsClass: 'input' }, size)] = true;
  }

  return _react2['default'].createElement(Component, (0, _extends3['default'])({}, elementProps, {
    type: type,
    id: id,
    ref: inputRef,
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.FormGroup"></a>[module react-bootstrap.FormGroup](#apidoc.module.react-bootstrap.FormGroup)

#### <a name="apidoc.element.react-bootstrap.FormGroup.FormGroup"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>FormGroup ()](#apidoc.element.react-bootstrap.FormGroup.FormGroup)
- description and source-code
```javascript
function FormGroup() {
  (0, _classCallCheck3['default'])(this, FormGroup);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.FormGroup.childContextTypes"></a>[module react-bootstrap.FormGroup.childContextTypes](#apidoc.module.react-bootstrap.FormGroup.childContextTypes)



# <a name="apidoc.module.react-bootstrap.FormGroup.propTypes"></a>[module react-bootstrap.FormGroup.propTypes](#apidoc.module.react-bootstrap.FormGroup.propTypes)

#### <a name="apidoc.element.react-bootstrap.FormGroup.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.FormGroup.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.FormGroup.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.FormGroup.propTypes.bsSize"></a>[function <span class="apidocSignatureSpan">react-bootstrap.FormGroup.propTypes.</span>bsSize ()](#apidoc.element.react-bootstrap.FormGroup.propTypes.bsSize)
- description and source-code
```javascript
bsSize = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.FormGroup.propTypes.controlId"></a>[function <span class="apidocSignatureSpan">react-bootstrap.FormGroup.propTypes.</span>controlId ()](#apidoc.element.react-bootstrap.FormGroup.propTypes.controlId)
- description and source-code
```javascript
controlId = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.FormGroup.propTypes.validationState"></a>[function <span class="apidocSignatureSpan">react-bootstrap.FormGroup.propTypes.</span>validationState ()](#apidoc.element.react-bootstrap.FormGroup.propTypes.validationState)
- description and source-code
```javascript
validationState = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.FormGroup.prototype"></a>[module react-bootstrap.FormGroup.prototype](#apidoc.module.react-bootstrap.FormGroup.prototype)

#### <a name="apidoc.element.react-bootstrap.FormGroup.prototype.getChildContext"></a>[function <span class="apidocSignatureSpan">react-bootstrap.FormGroup.prototype.</span>getChildContext ()](#apidoc.element.react-bootstrap.FormGroup.prototype.getChildContext)
- description and source-code
```javascript
function getChildContext() {
  var _props = this.props,
      controlId = _props.controlId,
      validationState = _props.validationState;


  return {
    $bs_formGroup: {
      controlId: controlId,
      validationState: validationState
    }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.FormGroup.prototype.hasFeedback"></a>[function <span class="apidocSignatureSpan">react-bootstrap.FormGroup.prototype.</span>hasFeedback (children)](#apidoc.element.react-bootstrap.FormGroup.prototype.hasFeedback)
- description and source-code
```javascript
function hasFeedback(children) {
  var _this2 = this;

  return _ValidComponentChildren2['default'].some(children, function (child) {
    return child.props.bsRole === 'feedback' || child.props.children && _this2.hasFeedback(child.props.children);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.FormGroup.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.FormGroup.prototype.</span>render ()](#apidoc.element.react-bootstrap.FormGroup.prototype.render)
- description and source-code
```javascript
function render() {
  var _props2 = this.props,
      validationState = _props2.validationState,
      className = _props2.className,
      children = _props2.children,
      props = (0, _objectWithoutProperties3['default'])(_props2, ['validationState', 'className', 'children']);

  var _splitBsPropsAndOmit = (0, _bootstrapUtils.splitBsPropsAndOmit)(props, ['controlId']),
      bsProps = _splitBsPropsAndOmit[0],
      elementProps = _splitBsPropsAndOmit[1];

  var classes = (0, _extends3['default'])({}, (0, _bootstrapUtils.getClassSet)(bsProps), {
    'has-feedback': this.hasFeedback(children)
  });
  if (validationState) {
    classes['has-' + validationState] = true;
  }

  return _react2['default'].createElement(
    'div',
    (0, _extends3['default'])({}, elementProps, {
      className: (0, _classnames2['default'])(className, classes)
    }),
    children
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Glyphicon"></a>[module react-bootstrap.Glyphicon](#apidoc.module.react-bootstrap.Glyphicon)

#### <a name="apidoc.element.react-bootstrap.Glyphicon.Glyphicon"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Glyphicon ()](#apidoc.element.react-bootstrap.Glyphicon.Glyphicon)
- description and source-code
```javascript
function Glyphicon() {
  (0, _classCallCheck3['default'])(this, Glyphicon);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Glyphicon.propTypes"></a>[module react-bootstrap.Glyphicon.propTypes](#apidoc.module.react-bootstrap.Glyphicon.propTypes)

#### <a name="apidoc.element.react-bootstrap.Glyphicon.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Glyphicon.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Glyphicon.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Glyphicon.propTypes.glyph"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Glyphicon.propTypes.</span>glyph ()](#apidoc.element.react-bootstrap.Glyphicon.propTypes.glyph)
- description and source-code
```javascript
glyph = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Glyphicon.prototype"></a>[module react-bootstrap.Glyphicon.prototype](#apidoc.module.react-bootstrap.Glyphicon.prototype)

#### <a name="apidoc.element.react-bootstrap.Glyphicon.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Glyphicon.prototype.</span>render ()](#apidoc.element.react-bootstrap.Glyphicon.prototype.render)
- description and source-code
```javascript
function render() {
  var _extends2;

  var _props = this.props,
      glyph = _props.glyph,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['glyph', 'className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _extends4['default'])({}, (0, _bootstrapUtils.getClassSet)(bsProps), (_extends2 = {}, _extends2[(0, _bootstrapUtils
.prefix)(bsProps, glyph)] = true, _extends2));

  return _react2['default'].createElement('span', (0, _extends4['default'])({}, elementProps, {
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Grid"></a>[module react-bootstrap.Grid](#apidoc.module.react-bootstrap.Grid)

#### <a name="apidoc.element.react-bootstrap.Grid.Grid"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Grid ()](#apidoc.element.react-bootstrap.Grid.Grid)
- description and source-code
```javascript
function Grid() {
  (0, _classCallCheck3['default'])(this, Grid);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Grid.propTypes"></a>[module react-bootstrap.Grid.propTypes](#apidoc.module.react-bootstrap.Grid.propTypes)

#### <a name="apidoc.element.react-bootstrap.Grid.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Grid.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Grid.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Grid.propTypes.componentClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Grid.propTypes.</span>componentClass ()](#apidoc.element.react-bootstrap.Grid.propTypes.componentClass)
- description and source-code
```javascript
componentClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Grid.propTypes.fluid"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Grid.propTypes.</span>fluid ()](#apidoc.element.react-bootstrap.Grid.propTypes.fluid)
- description and source-code
```javascript
fluid = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Grid.prototype"></a>[module react-bootstrap.Grid.prototype](#apidoc.module.react-bootstrap.Grid.prototype)

#### <a name="apidoc.element.react-bootstrap.Grid.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Grid.prototype.</span>render ()](#apidoc.element.react-bootstrap.Grid.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      fluid = _props.fluid,
      Component = _props.componentClass,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['fluid', 'componentClass', 'className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _bootstrapUtils.prefix)(bsProps, fluid && 'fluid');

  return _react2['default'].createElement(Component, (0, _extends3['default'])({}, elementProps, {
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.HelpBlock"></a>[module react-bootstrap.HelpBlock](#apidoc.module.react-bootstrap.HelpBlock)

#### <a name="apidoc.element.react-bootstrap.HelpBlock.HelpBlock"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>HelpBlock ()](#apidoc.element.react-bootstrap.HelpBlock.HelpBlock)
- description and source-code
```javascript
function HelpBlock() {
  (0, _classCallCheck3['default'])(this, HelpBlock);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.HelpBlock.propTypes"></a>[module react-bootstrap.HelpBlock.propTypes](#apidoc.module.react-bootstrap.HelpBlock.propTypes)

#### <a name="apidoc.element.react-bootstrap.HelpBlock.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.HelpBlock.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.HelpBlock.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.HelpBlock.prototype"></a>[module react-bootstrap.HelpBlock.prototype](#apidoc.module.react-bootstrap.HelpBlock.prototype)

#### <a name="apidoc.element.react-bootstrap.HelpBlock.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.HelpBlock.prototype.</span>render ()](#apidoc.element.react-bootstrap.HelpBlock.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _bootstrapUtils.getClassSet)(bsProps);

  return _react2['default'].createElement('span', (0, _extends3['default'])({}, elementProps, {
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Image"></a>[module react-bootstrap.Image](#apidoc.module.react-bootstrap.Image)

#### <a name="apidoc.element.react-bootstrap.Image.Image"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Image ()](#apidoc.element.react-bootstrap.Image.Image)
- description and source-code
```javascript
function Image() {
  (0, _classCallCheck3['default'])(this, Image);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Image.propTypes"></a>[module react-bootstrap.Image.propTypes](#apidoc.module.react-bootstrap.Image.propTypes)

#### <a name="apidoc.element.react-bootstrap.Image.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Image.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Image.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Image.propTypes.circle"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Image.propTypes.</span>circle ()](#apidoc.element.react-bootstrap.Image.propTypes.circle)
- description and source-code
```javascript
circle = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Image.propTypes.responsive"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Image.propTypes.</span>responsive ()](#apidoc.element.react-bootstrap.Image.propTypes.responsive)
- description and source-code
```javascript
responsive = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Image.propTypes.rounded"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Image.propTypes.</span>rounded ()](#apidoc.element.react-bootstrap.Image.propTypes.rounded)
- description and source-code
```javascript
rounded = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Image.propTypes.thumbnail"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Image.propTypes.</span>thumbnail ()](#apidoc.element.react-bootstrap.Image.propTypes.thumbnail)
- description and source-code
```javascript
thumbnail = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Image.prototype"></a>[module react-bootstrap.Image.prototype](#apidoc.module.react-bootstrap.Image.prototype)

#### <a name="apidoc.element.react-bootstrap.Image.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Image.prototype.</span>render ()](#apidoc.element.react-bootstrap.Image.prototype.render)
- description and source-code
```javascript
function render() {
  var _classes;

  var _props = this.props,
      responsive = _props.responsive,
      rounded = _props.rounded,
      circle = _props.circle,
      thumbnail = _props.thumbnail,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['responsive', 'rounded', 'circle', 'thumbnail', 'className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (_classes = {}, _classes[(0, _bootstrapUtils.prefix)(bsProps, 'responsive')] = responsive, _classes[(0, _bootstrapUtils
.prefix)(bsProps, 'rounded')] = rounded, _classes[(0, _bootstrapUtils.prefix)(bsProps, 'circle')] = circle, _classes[(0, _bootstrapUtils
.prefix)(bsProps, 'thumbnail')] = thumbnail, _classes);

  return _react2['default'].createElement('img', (0, _extends3['default'])({}, elementProps, {
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.InputGroup"></a>[module react-bootstrap.InputGroup](#apidoc.module.react-bootstrap.InputGroup)

#### <a name="apidoc.element.react-bootstrap.InputGroup.InputGroup"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>InputGroup ()](#apidoc.element.react-bootstrap.InputGroup.InputGroup)
- description and source-code
```javascript
function InputGroup() {
  (0, _classCallCheck3['default'])(this, InputGroup);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.InputGroup.Addon"></a>[function <span class="apidocSignatureSpan">react-bootstrap.InputGroup.</span>Addon ()](#apidoc.element.react-bootstrap.InputGroup.Addon)
- description and source-code
```javascript
function InputGroupAddon() {
  (0, _classCallCheck3['default'])(this, InputGroupAddon);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.InputGroup.Button"></a>[function <span class="apidocSignatureSpan">react-bootstrap.InputGroup.</span>Button ()](#apidoc.element.react-bootstrap.InputGroup.Button)
- description and source-code
```javascript
function InputGroupButton() {
  (0, _classCallCheck3['default'])(this, InputGroupButton);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.InputGroup.Addon"></a>[module react-bootstrap.InputGroup.Addon](#apidoc.module.react-bootstrap.InputGroup.Addon)

#### <a name="apidoc.element.react-bootstrap.InputGroup.Addon.Addon"></a>[function <span class="apidocSignatureSpan">react-bootstrap.InputGroup.</span>Addon ()](#apidoc.element.react-bootstrap.InputGroup.Addon.Addon)
- description and source-code
```javascript
function InputGroupAddon() {
  (0, _classCallCheck3['default'])(this, InputGroupAddon);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.InputGroup.Addon.prototype"></a>[module react-bootstrap.InputGroup.Addon.prototype](#apidoc.module.react-bootstrap.InputGroup.Addon.prototype)

#### <a name="apidoc.element.react-bootstrap.InputGroup.Addon.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.InputGroup.Addon.prototype.</span>render ()](#apidoc.element.react-bootstrap.InputGroup.Addon.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _bootstrapUtils.getClassSet)(bsProps);

  return _react2['default'].createElement('span', (0, _extends3['default'])({}, elementProps, {
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.InputGroup.Button"></a>[module react-bootstrap.InputGroup.Button](#apidoc.module.react-bootstrap.InputGroup.Button)

#### <a name="apidoc.element.react-bootstrap.InputGroup.Button.Button"></a>[function <span class="apidocSignatureSpan">react-bootstrap.InputGroup.</span>Button ()](#apidoc.element.react-bootstrap.InputGroup.Button.Button)
- description and source-code
```javascript
function InputGroupButton() {
  (0, _classCallCheck3['default'])(this, InputGroupButton);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.InputGroup.Button.prototype"></a>[module react-bootstrap.InputGroup.Button.prototype](#apidoc.module.react-bootstrap.InputGroup.Button.prototype)

#### <a name="apidoc.element.react-bootstrap.InputGroup.Button.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.InputGroup.Button.prototype.</span>render ()](#apidoc.element.react-bootstrap.InputGroup.Button.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _bootstrapUtils.getClassSet)(bsProps);

  return _react2['default'].createElement('span', (0, _extends3['default'])({}, elementProps, {
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.InputGroup.propTypes"></a>[module react-bootstrap.InputGroup.propTypes](#apidoc.module.react-bootstrap.InputGroup.propTypes)

#### <a name="apidoc.element.react-bootstrap.InputGroup.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.InputGroup.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.InputGroup.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.InputGroup.propTypes.bsSize"></a>[function <span class="apidocSignatureSpan">react-bootstrap.InputGroup.propTypes.</span>bsSize ()](#apidoc.element.react-bootstrap.InputGroup.propTypes.bsSize)
- description and source-code
```javascript
bsSize = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.InputGroup.prototype"></a>[module react-bootstrap.InputGroup.prototype](#apidoc.module.react-bootstrap.InputGroup.prototype)

#### <a name="apidoc.element.react-bootstrap.InputGroup.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.InputGroup.prototype.</span>render ()](#apidoc.element.react-bootstrap.InputGroup.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _bootstrapUtils.getClassSet)(bsProps);

  return _react2['default'].createElement('span', (0, _extends3['default'])({}, elementProps, {
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Jumbotron"></a>[module react-bootstrap.Jumbotron](#apidoc.module.react-bootstrap.Jumbotron)

#### <a name="apidoc.element.react-bootstrap.Jumbotron.Jumbotron"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Jumbotron ()](#apidoc.element.react-bootstrap.Jumbotron.Jumbotron)
- description and source-code
```javascript
function Jumbotron() {
  (0, _classCallCheck3['default'])(this, Jumbotron);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Jumbotron.propTypes"></a>[module react-bootstrap.Jumbotron.propTypes](#apidoc.module.react-bootstrap.Jumbotron.propTypes)

#### <a name="apidoc.element.react-bootstrap.Jumbotron.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Jumbotron.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Jumbotron.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Jumbotron.propTypes.componentClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Jumbotron.propTypes.</span>componentClass ()](#apidoc.element.react-bootstrap.Jumbotron.propTypes.componentClass)
- description and source-code
```javascript
componentClass = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Jumbotron.prototype"></a>[module react-bootstrap.Jumbotron.prototype](#apidoc.module.react-bootstrap.Jumbotron.prototype)

#### <a name="apidoc.element.react-bootstrap.Jumbotron.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Jumbotron.prototype.</span>render ()](#apidoc.element.react-bootstrap.Jumbotron.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      Component = _props.componentClass,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['componentClass', 'className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _bootstrapUtils.getClassSet)(bsProps);

  return _react2['default'].createElement(Component, (0, _extends3['default'])({}, elementProps, {
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Label"></a>[module react-bootstrap.Label](#apidoc.module.react-bootstrap.Label)

#### <a name="apidoc.element.react-bootstrap.Label.Label"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Label ()](#apidoc.element.react-bootstrap.Label.Label)
- description and source-code
```javascript
function Label() {
  (0, _classCallCheck3['default'])(this, Label);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Label.propTypes"></a>[module react-bootstrap.Label.propTypes](#apidoc.module.react-bootstrap.Label.propTypes)

#### <a name="apidoc.element.react-bootstrap.Label.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Label.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Label.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Label.propTypes.bsStyle"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Label.propTypes.</span>bsStyle ()](#apidoc.element.react-bootstrap.Label.propTypes.bsStyle)
- description and source-code
```javascript
bsStyle = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Label.prototype"></a>[module react-bootstrap.Label.prototype](#apidoc.module.react-bootstrap.Label.prototype)

#### <a name="apidoc.element.react-bootstrap.Label.prototype.hasContent"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Label.prototype.</span>hasContent (children)](#apidoc.element.react-bootstrap.Label.prototype.hasContent)
- description and source-code
```javascript
function hasContent(children) {
  var result = false;

  _react2['default'].Children.forEach(children, function (child) {
    if (result) {
      return;
    }

    if (child || child === 0) {
      result = true;
    }
  });

  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Label.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Label.prototype.</span>render ()](#apidoc.element.react-bootstrap.Label.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      className = _props.className,
      children = _props.children,
      props = (0, _objectWithoutProperties3['default'])(_props, ['className', 'children']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _extends3['default'])({}, (0, _bootstrapUtils.getClassSet)(bsProps), {

    // Hack for collapsing on IE8.
    hidden: !this.hasContent(children)
  });

  return _react2['default'].createElement(
    'span',
    (0, _extends3['default'])({}, elementProps, {
      className: (0, _classnames2['default'])(className, classes)
    }),
    children
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ListGroup"></a>[module react-bootstrap.ListGroup](#apidoc.module.react-bootstrap.ListGroup)

#### <a name="apidoc.element.react-bootstrap.ListGroup.ListGroup"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>ListGroup ()](#apidoc.element.react-bootstrap.ListGroup.ListGroup)
- description and source-code
```javascript
function ListGroup() {
  (0, _classCallCheck3['default'])(this, ListGroup);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ListGroup.propTypes"></a>[module react-bootstrap.ListGroup.propTypes](#apidoc.module.react-bootstrap.ListGroup.propTypes)

#### <a name="apidoc.element.react-bootstrap.ListGroup.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ListGroup.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.ListGroup.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ListGroup.propTypes.componentClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ListGroup.propTypes.</span>componentClass ()](#apidoc.element.react-bootstrap.ListGroup.propTypes.componentClass)
- description and source-code
```javascript
componentClass = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ListGroup.prototype"></a>[module react-bootstrap.ListGroup.prototype](#apidoc.module.react-bootstrap.ListGroup.prototype)

#### <a name="apidoc.element.react-bootstrap.ListGroup.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ListGroup.prototype.</span>render ()](#apidoc.element.react-bootstrap.ListGroup.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      children = _props.children,
      _props$componentClass = _props.componentClass,
      Component = _props$componentClass === undefined ? getDefaultComponent(children) : _props$componentClass,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['children', 'componentClass', 'className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _bootstrapUtils.getClassSet)(bsProps);

  var useListItem = Component === 'ul' && _ValidComponentChildren2['default'].every(children, function (child) {
    return child.type === _ListGroupItem2['default'];
  });

  return _react2['default'].createElement(
    Component,
    (0, _extends3['default'])({}, elementProps, {
      className: (0, _classnames2['default'])(className, classes)
    }),
    useListItem ? _ValidComponentChildren2['default'].map(children, function (child) {
      return (0, _react.cloneElement)(child, { listItem: true });
    }) : children
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ListGroupItem"></a>[module react-bootstrap.ListGroupItem](#apidoc.module.react-bootstrap.ListGroupItem)

#### <a name="apidoc.element.react-bootstrap.ListGroupItem.ListGroupItem"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>ListGroupItem ()](#apidoc.element.react-bootstrap.ListGroupItem.ListGroupItem)
- description and source-code
```javascript
function ListGroupItem() {
  (0, _classCallCheck3['default'])(this, ListGroupItem);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ListGroupItem.propTypes"></a>[module react-bootstrap.ListGroupItem.propTypes](#apidoc.module.react-bootstrap.ListGroupItem.propTypes)

#### <a name="apidoc.element.react-bootstrap.ListGroupItem.propTypes.active"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ListGroupItem.propTypes.</span>active ()](#apidoc.element.react-bootstrap.ListGroupItem.propTypes.active)
- description and source-code
```javascript
active = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ListGroupItem.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ListGroupItem.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.ListGroupItem.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ListGroupItem.propTypes.bsStyle"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ListGroupItem.propTypes.</span>bsStyle ()](#apidoc.element.react-bootstrap.ListGroupItem.propTypes.bsStyle)
- description and source-code
```javascript
bsStyle = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ListGroupItem.propTypes.disabled"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ListGroupItem.propTypes.</span>disabled ()](#apidoc.element.react-bootstrap.ListGroupItem.propTypes.disabled)
- description and source-code
```javascript
disabled = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ListGroupItem.propTypes.header"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ListGroupItem.propTypes.</span>header ()](#apidoc.element.react-bootstrap.ListGroupItem.propTypes.header)
- description and source-code
```javascript
header = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ListGroupItem.propTypes.href"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ListGroupItem.propTypes.</span>href ()](#apidoc.element.react-bootstrap.ListGroupItem.propTypes.href)
- description and source-code
```javascript
href = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ListGroupItem.propTypes.listItem"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ListGroupItem.propTypes.</span>listItem ()](#apidoc.element.react-bootstrap.ListGroupItem.propTypes.listItem)
- description and source-code
```javascript
listItem = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ListGroupItem.propTypes.onClick"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ListGroupItem.propTypes.</span>onClick ()](#apidoc.element.react-bootstrap.ListGroupItem.propTypes.onClick)
- description and source-code
```javascript
onClick = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ListGroupItem.propTypes.type"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ListGroupItem.propTypes.</span>type ()](#apidoc.element.react-bootstrap.ListGroupItem.propTypes.type)
- description and source-code
```javascript
type = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ListGroupItem.prototype"></a>[module react-bootstrap.ListGroupItem.prototype](#apidoc.module.react-bootstrap.ListGroupItem.prototype)

#### <a name="apidoc.element.react-bootstrap.ListGroupItem.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ListGroupItem.prototype.</span>render ()](#apidoc.element.react-bootstrap.ListGroupItem.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      active = _props.active,
      disabled = _props.disabled,
      className = _props.className,
      header = _props.header,
      listItem = _props.listItem,
      children = _props.children,
      props = (0, _objectWithoutProperties3['default'])(_props, ['active', 'disabled', 'className', 'header', 'listItem', 'children
']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _extends3['default'])({}, (0, _bootstrapUtils.getClassSet)(bsProps), {
    active: active,
    disabled: disabled
  });

  var Component = void 0;

  if (elementProps.href) {
    Component = 'a';
  } else if (elementProps.onClick) {
    Component = 'button';
    elementProps.type = elementProps.type || 'button';
  } else if (listItem) {
    Component = 'li';
  } else {
    Component = 'span';
  }

  elementProps.className = (0, _classnames2['default'])(className, classes);

  // TODO: Deprecate 'header' prop.
  if (header) {
    return _react2['default'].createElement(
      Component,
      elementProps,
      this.renderHeader(header, (0, _bootstrapUtils.prefix)(bsProps, 'heading')),
      _react2['default'].createElement(
        'p',
        { className: (0, _bootstrapUtils.prefix)(bsProps, 'text') },
        children
      )
    );
  }

  return _react2['default'].createElement(
    Component,
    elementProps,
    children
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ListGroupItem.prototype.renderHeader"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ListGroupItem.prototype.</span>renderHeader (header, headingClassName)](#apidoc.element.react-bootstrap.ListGroupItem.prototype.renderHeader)
- description and source-code
```javascript
function renderHeader(header, headingClassName) {
  if (_react2['default'].isValidElement(header)) {
    return (0, _react.cloneElement)(header, {
      className: (0, _classnames2['default'])(header.props.className, headingClassName)
    });
  }

  return _react2['default'].createElement(
    'h4',
    { className: headingClassName },
    header
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Media"></a>[module react-bootstrap.Media](#apidoc.module.react-bootstrap.Media)

#### <a name="apidoc.element.react-bootstrap.Media.Media"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Media ()](#apidoc.element.react-bootstrap.Media.Media)
- description and source-code
```javascript
function Media() {
  (0, _classCallCheck3['default'])(this, Media);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Media.Body"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Media.</span>Body ()](#apidoc.element.react-bootstrap.Media.Body)
- description and source-code
```javascript
function MediaBody() {
  (0, _classCallCheck3['default'])(this, MediaBody);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Media.Heading"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Media.</span>Heading ()](#apidoc.element.react-bootstrap.Media.Heading)
- description and source-code
```javascript
function MediaHeading() {
  (0, _classCallCheck3['default'])(this, MediaHeading);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Media.Left"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Media.</span>Left ()](#apidoc.element.react-bootstrap.Media.Left)
- description and source-code
```javascript
function MediaLeft() {
  (0, _classCallCheck3['default'])(this, MediaLeft);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Media.List"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Media.</span>List ()](#apidoc.element.react-bootstrap.Media.List)
- description and source-code
```javascript
function MediaList() {
  (0, _classCallCheck3['default'])(this, MediaList);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Media.ListItem"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Media.</span>ListItem ()](#apidoc.element.react-bootstrap.Media.ListItem)
- description and source-code
```javascript
function MediaListItem() {
  (0, _classCallCheck3['default'])(this, MediaListItem);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Media.Right"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Media.</span>Right ()](#apidoc.element.react-bootstrap.Media.Right)
- description and source-code
```javascript
function MediaRight() {
  (0, _classCallCheck3['default'])(this, MediaRight);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Media.Body"></a>[module react-bootstrap.Media.Body](#apidoc.module.react-bootstrap.Media.Body)

#### <a name="apidoc.element.react-bootstrap.Media.Body.Body"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Media.</span>Body ()](#apidoc.element.react-bootstrap.Media.Body.Body)
- description and source-code
```javascript
function MediaBody() {
  (0, _classCallCheck3['default'])(this, MediaBody);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Media.Body.prototype"></a>[module react-bootstrap.Media.Body.prototype](#apidoc.module.react-bootstrap.Media.Body.prototype)

#### <a name="apidoc.element.react-bootstrap.Media.Body.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Media.Body.prototype.</span>render ()](#apidoc.element.react-bootstrap.Media.Body.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      Component = _props.componentClass,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['componentClass', 'className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _bootstrapUtils.getClassSet)(bsProps);

  return _react2['default'].createElement(Component, (0, _extends3['default'])({}, elementProps, {
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Media.Heading"></a>[module react-bootstrap.Media.Heading](#apidoc.module.react-bootstrap.Media.Heading)

#### <a name="apidoc.element.react-bootstrap.Media.Heading.Heading"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Media.</span>Heading ()](#apidoc.element.react-bootstrap.Media.Heading.Heading)
- description and source-code
```javascript
function MediaHeading() {
  (0, _classCallCheck3['default'])(this, MediaHeading);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Media.Heading.prototype"></a>[module react-bootstrap.Media.Heading.prototype](#apidoc.module.react-bootstrap.Media.Heading.prototype)

#### <a name="apidoc.element.react-bootstrap.Media.Heading.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Media.Heading.prototype.</span>render ()](#apidoc.element.react-bootstrap.Media.Heading.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      Component = _props.componentClass,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['componentClass', 'className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _bootstrapUtils.getClassSet)(bsProps);

  return _react2['default'].createElement(Component, (0, _extends3['default'])({}, elementProps, {
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Media.Left"></a>[module react-bootstrap.Media.Left](#apidoc.module.react-bootstrap.Media.Left)

#### <a name="apidoc.element.react-bootstrap.Media.Left.Left"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Media.</span>Left ()](#apidoc.element.react-bootstrap.Media.Left.Left)
- description and source-code
```javascript
function MediaLeft() {
  (0, _classCallCheck3['default'])(this, MediaLeft);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Media.Left.prototype"></a>[module react-bootstrap.Media.Left.prototype](#apidoc.module.react-bootstrap.Media.Left.prototype)

#### <a name="apidoc.element.react-bootstrap.Media.Left.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Media.Left.prototype.</span>render ()](#apidoc.element.react-bootstrap.Media.Left.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      align = _props.align,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['align', 'className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _bootstrapUtils.getClassSet)(bsProps);

  if (align) {
    // The class is e.g. 'media-top', not 'media-left-top'.
    classes[(0, _bootstrapUtils.prefix)(_Media2['default'].defaultProps, align)] = true;
  }

  return _react2['default'].createElement('div', (0, _extends3['default'])({}, elementProps, {
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Media.List"></a>[module react-bootstrap.Media.List](#apidoc.module.react-bootstrap.Media.List)

#### <a name="apidoc.element.react-bootstrap.Media.List.List"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Media.</span>List ()](#apidoc.element.react-bootstrap.Media.List.List)
- description and source-code
```javascript
function MediaList() {
  (0, _classCallCheck3['default'])(this, MediaList);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Media.List.prototype"></a>[module react-bootstrap.Media.List.prototype](#apidoc.module.react-bootstrap.Media.List.prototype)

#### <a name="apidoc.element.react-bootstrap.Media.List.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Media.List.prototype.</span>render ()](#apidoc.element.react-bootstrap.Media.List.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _bootstrapUtils.getClassSet)(bsProps);

  return _react2['default'].createElement('ul', (0, _extends3['default'])({}, elementProps, {
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Media.ListItem"></a>[module react-bootstrap.Media.ListItem](#apidoc.module.react-bootstrap.Media.ListItem)

#### <a name="apidoc.element.react-bootstrap.Media.ListItem.ListItem"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Media.</span>ListItem ()](#apidoc.element.react-bootstrap.Media.ListItem.ListItem)
- description and source-code
```javascript
function MediaListItem() {
  (0, _classCallCheck3['default'])(this, MediaListItem);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Media.ListItem.prototype"></a>[module react-bootstrap.Media.ListItem.prototype](#apidoc.module.react-bootstrap.Media.ListItem.prototype)

#### <a name="apidoc.element.react-bootstrap.Media.ListItem.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Media.ListItem.prototype.</span>render ()](#apidoc.element.react-bootstrap.Media.ListItem.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _bootstrapUtils.getClassSet)(bsProps);

  return _react2['default'].createElement('li', (0, _extends3['default'])({}, elementProps, {
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Media.Right"></a>[module react-bootstrap.Media.Right](#apidoc.module.react-bootstrap.Media.Right)

#### <a name="apidoc.element.react-bootstrap.Media.Right.Right"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Media.</span>Right ()](#apidoc.element.react-bootstrap.Media.Right.Right)
- description and source-code
```javascript
function MediaRight() {
  (0, _classCallCheck3['default'])(this, MediaRight);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Media.Right.prototype"></a>[module react-bootstrap.Media.Right.prototype](#apidoc.module.react-bootstrap.Media.Right.prototype)

#### <a name="apidoc.element.react-bootstrap.Media.Right.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Media.Right.prototype.</span>render ()](#apidoc.element.react-bootstrap.Media.Right.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      align = _props.align,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['align', 'className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _bootstrapUtils.getClassSet)(bsProps);

  if (align) {
    // The class is e.g. 'media-top', not 'media-right-top'.
    classes[(0, _bootstrapUtils.prefix)(_Media2['default'].defaultProps, align)] = true;
  }

  return _react2['default'].createElement('div', (0, _extends3['default'])({}, elementProps, {
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Media.propTypes"></a>[module react-bootstrap.Media.propTypes](#apidoc.module.react-bootstrap.Media.propTypes)

#### <a name="apidoc.element.react-bootstrap.Media.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Media.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Media.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Media.propTypes.componentClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Media.propTypes.</span>componentClass ()](#apidoc.element.react-bootstrap.Media.propTypes.componentClass)
- description and source-code
```javascript
componentClass = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Media.prototype"></a>[module react-bootstrap.Media.prototype](#apidoc.module.react-bootstrap.Media.prototype)

#### <a name="apidoc.element.react-bootstrap.Media.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Media.prototype.</span>render ()](#apidoc.element.react-bootstrap.Media.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      Component = _props.componentClass,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['componentClass', 'className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _bootstrapUtils.getClassSet)(bsProps);

  return _react2['default'].createElement(Component, (0, _extends3['default'])({}, elementProps, {
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.MenuItem"></a>[module react-bootstrap.MenuItem](#apidoc.module.react-bootstrap.MenuItem)

#### <a name="apidoc.element.react-bootstrap.MenuItem.MenuItem"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>MenuItem (props, context)](#apidoc.element.react-bootstrap.MenuItem.MenuItem)
- description and source-code
```javascript
function MenuItem(props, context) {
  (0, _classCallCheck3['default'])(this, MenuItem);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleClick = _this.handleClick.bind(_this);
  return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.MenuItem.propTypes"></a>[module react-bootstrap.MenuItem.propTypes](#apidoc.module.react-bootstrap.MenuItem.propTypes)

#### <a name="apidoc.element.react-bootstrap.MenuItem.propTypes.active"></a>[function <span class="apidocSignatureSpan">react-bootstrap.MenuItem.propTypes.</span>active ()](#apidoc.element.react-bootstrap.MenuItem.propTypes.active)
- description and source-code
```javascript
active = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.MenuItem.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.MenuItem.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.MenuItem.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.MenuItem.propTypes.disabled"></a>[function <span class="apidocSignatureSpan">react-bootstrap.MenuItem.propTypes.</span>disabled ()](#apidoc.element.react-bootstrap.MenuItem.propTypes.disabled)
- description and source-code
```javascript
disabled = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.MenuItem.propTypes.divider"></a>[function <span class="apidocSignatureSpan">react-bootstrap.MenuItem.propTypes.</span>divider ()](#apidoc.element.react-bootstrap.MenuItem.propTypes.divider)
- description and source-code
```javascript
divider = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.MenuItem.propTypes.eventKey"></a>[function <span class="apidocSignatureSpan">react-bootstrap.MenuItem.propTypes.</span>eventKey ()](#apidoc.element.react-bootstrap.MenuItem.propTypes.eventKey)
- description and source-code
```javascript
eventKey = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.MenuItem.propTypes.header"></a>[function <span class="apidocSignatureSpan">react-bootstrap.MenuItem.propTypes.</span>header ()](#apidoc.element.react-bootstrap.MenuItem.propTypes.header)
- description and source-code
```javascript
header = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.MenuItem.propTypes.href"></a>[function <span class="apidocSignatureSpan">react-bootstrap.MenuItem.propTypes.</span>href ()](#apidoc.element.react-bootstrap.MenuItem.propTypes.href)
- description and source-code
```javascript
href = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.MenuItem.propTypes.onClick"></a>[function <span class="apidocSignatureSpan">react-bootstrap.MenuItem.propTypes.</span>onClick ()](#apidoc.element.react-bootstrap.MenuItem.propTypes.onClick)
- description and source-code
```javascript
onClick = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.MenuItem.propTypes.onSelect"></a>[function <span class="apidocSignatureSpan">react-bootstrap.MenuItem.propTypes.</span>onSelect ()](#apidoc.element.react-bootstrap.MenuItem.propTypes.onSelect)
- description and source-code
```javascript
onSelect = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.MenuItem.prototype"></a>[module react-bootstrap.MenuItem.prototype](#apidoc.module.react-bootstrap.MenuItem.prototype)

#### <a name="apidoc.element.react-bootstrap.MenuItem.prototype.handleClick"></a>[function <span class="apidocSignatureSpan">react-bootstrap.MenuItem.prototype.</span>handleClick (event)](#apidoc.element.react-bootstrap.MenuItem.prototype.handleClick)
- description and source-code
```javascript
function handleClick(event) {
  var _props = this.props,
      href = _props.href,
      disabled = _props.disabled,
      onSelect = _props.onSelect,
      eventKey = _props.eventKey;


  if (!href || disabled) {
    event.preventDefault();
  }

  if (disabled) {
    return;
  }

  if (onSelect) {
    onSelect(eventKey, event);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.MenuItem.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.MenuItem.prototype.</span>render ()](#apidoc.element.react-bootstrap.MenuItem.prototype.render)
- description and source-code
```javascript
function render() {
  var _props2 = this.props,
      active = _props2.active,
      disabled = _props2.disabled,
      divider = _props2.divider,
      header = _props2.header,
      onClick = _props2.onClick,
      className = _props2.className,
      style = _props2.style,
      props = (0, _objectWithoutProperties3['default'])(_props2, ['active', 'disabled', 'divider', 'header', 'onClick', 'className
', 'style']);

  var _splitBsPropsAndOmit = (0, _bootstrapUtils.splitBsPropsAndOmit)(props, ['eventKey', 'onSelect']),
      bsProps = _splitBsPropsAndOmit[0],
      elementProps = _splitBsPropsAndOmit[1];

  if (divider) {
    // Forcibly blank out the children; separators shouldn't render any.
    elementProps.children = undefined;

    return _react2['default'].createElement('li', (0, _extends3['default'])({}, elementProps, {
      role: 'separator',
      className: (0, _classnames2['default'])(className, 'divider'),
      style: style
    }));
  }

  if (header) {
    return _react2['default'].createElement('li', (0, _extends3['default'])({}, elementProps, {
      role: 'heading',
      className: (0, _classnames2['default'])(className, (0, _bootstrapUtils.prefix)(bsProps, 'header')),
      style: style
    }));
  }

  return _react2['default'].createElement(
    'li',
    {
      role: 'presentation',
      className: (0, _classnames2['default'])(className, { active: active, disabled: disabled }),
      style: style
    },
    _react2['default'].createElement(_SafeAnchor2['default'], (0, _extends3['default'])({}, elementProps, {
      role: 'menuitem',
      tabIndex: '-1',
      onClick: (0, _createChainedFunction2['default'])(onClick, this.handleClick)
    }))
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Modal"></a>[module react-bootstrap.Modal](#apidoc.module.react-bootstrap.Modal)

#### <a name="apidoc.element.react-bootstrap.Modal.Modal"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Modal (props, context)](#apidoc.element.react-bootstrap.Modal.Modal)
- description and source-code
```javascript
function Modal(props, context) {
  (0, _classCallCheck3['default'])(this, Modal);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleEntering = _this.handleEntering.bind(_this);
  _this.handleExited = _this.handleExited.bind(_this);
  _this.handleWindowResize = _this.handleWindowResize.bind(_this);
  _this.handleDialogClick = _this.handleDialogClick.bind(_this);

  _this.state = {
    style: {}
  };
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.Body"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.</span>Body ()](#apidoc.element.react-bootstrap.Modal.Body)
- description and source-code
```javascript
function ModalBody() {
  (0, _classCallCheck3['default'])(this, ModalBody);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.Dialog"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.</span>Dialog ()](#apidoc.element.react-bootstrap.Modal.Dialog)
- description and source-code
```javascript
function ModalDialog() {
  (0, _classCallCheck3['default'])(this, ModalDialog);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.Footer"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.</span>Footer ()](#apidoc.element.react-bootstrap.Modal.Footer)
- description and source-code
```javascript
function ModalFooter() {
  (0, _classCallCheck3['default'])(this, ModalFooter);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.Header"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.</span>Header ()](#apidoc.element.react-bootstrap.Modal.Header)
- description and source-code
```javascript
function ModalHeader() {
  (0, _classCallCheck3['default'])(this, ModalHeader);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.Title"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.</span>Title ()](#apidoc.element.react-bootstrap.Modal.Title)
- description and source-code
```javascript
function ModalTitle() {
  (0, _classCallCheck3['default'])(this, ModalTitle);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Modal.Dialog"></a>[module react-bootstrap.Modal.Dialog](#apidoc.module.react-bootstrap.Modal.Dialog)

#### <a name="apidoc.element.react-bootstrap.Modal.Dialog.Dialog"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.</span>Dialog ()](#apidoc.element.react-bootstrap.Modal.Dialog.Dialog)
- description and source-code
```javascript
function ModalDialog() {
  (0, _classCallCheck3['default'])(this, ModalDialog);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Modal.Dialog.prototype"></a>[module react-bootstrap.Modal.Dialog.prototype](#apidoc.module.react-bootstrap.Modal.Dialog.prototype)

#### <a name="apidoc.element.react-bootstrap.Modal.Dialog.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.Dialog.prototype.</span>render ()](#apidoc.element.react-bootstrap.Modal.Dialog.prototype.render)
- description and source-code
```javascript
function render() {
  var _extends2;

  var _props = this.props,
      dialogClassName = _props.dialogClassName,
      className = _props.className,
      style = _props.style,
      children = _props.children,
      props = (0, _objectWithoutProperties3['default'])(_props, ['dialogClassName', 'className', 'style', 'children']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var bsClassName = (0, _bootstrapUtils.prefix)(bsProps);

  var modalStyle = (0, _extends4['default'])({ display: 'block' }, style);

  var dialogClasses = (0, _extends4['default'])({}, (0, _bootstrapUtils.getClassSet)(bsProps), (_extends2 = {}, _extends2[bsClassName
] = false, _extends2[(0, _bootstrapUtils.prefix)(bsProps, 'dialog')] = true, _extends2));

  return _react2['default'].createElement(
    'div',
    (0, _extends4['default'])({}, elementProps, {
      tabIndex: '-1',
      role: 'dialog',
      style: modalStyle,
      className: (0, _classnames2['default'])(className, bsClassName)
    }),
    _react2['default'].createElement(
      'div',
      { className: (0, _classnames2['default'])(dialogClassName, dialogClasses) },
      _react2['default'].createElement(
        'div',
        { className: (0, _bootstrapUtils.prefix)(bsProps, 'content'), role: 'document' },
        children
      )
    )
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Modal.childContextTypes"></a>[module react-bootstrap.Modal.childContextTypes](#apidoc.module.react-bootstrap.Modal.childContextTypes)



# <a name="apidoc.module.react-bootstrap.Modal.defaultProps"></a>[module react-bootstrap.Modal.defaultProps](#apidoc.module.react-bootstrap.Modal.defaultProps)

#### <a name="apidoc.element.react-bootstrap.Modal.defaultProps.dialogComponentClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.defaultProps.</span>dialogComponentClass ()](#apidoc.element.react-bootstrap.Modal.defaultProps.dialogComponentClass)
- description and source-code
```javascript
function ModalDialog() {
  (0, _classCallCheck3['default'])(this, ModalDialog);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.defaultProps.onHide"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.defaultProps.</span>onHide ()](#apidoc.element.react-bootstrap.Modal.defaultProps.onHide)
- description and source-code
```javascript
function noop() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.defaultProps.renderBackdrop"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.defaultProps.</span>renderBackdrop (props)](#apidoc.element.react-bootstrap.Modal.defaultProps.renderBackdrop)
- description and source-code
```javascript
function renderBackdrop(props) {
  return _react2.default.createElement('div', props);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Modal.propTypes"></a>[module react-bootstrap.Modal.propTypes](#apidoc.module.react-bootstrap.Modal.propTypes)

#### <a name="apidoc.element.react-bootstrap.Modal.propTypes.animation"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>animation ()](#apidoc.element.react-bootstrap.Modal.propTypes.animation)
- description and source-code
```javascript
animation = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.propTypes.autoFocus"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>autoFocus ()](#apidoc.element.react-bootstrap.Modal.propTypes.autoFocus)
- description and source-code
```javascript
autoFocus = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.propTypes.backdrop"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>backdrop ()](#apidoc.element.react-bootstrap.Modal.propTypes.backdrop)
- description and source-code
```javascript
backdrop = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.propTypes.backdropClassName"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>backdropClassName ()](#apidoc.element.react-bootstrap.Modal.propTypes.backdropClassName)
- description and source-code
```javascript
backdropClassName = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.propTypes.backdropStyle"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>backdropStyle ()](#apidoc.element.react-bootstrap.Modal.propTypes.backdropStyle)
- description and source-code
```javascript
backdropStyle = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.propTypes.backdropTransitionTimeout"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>backdropTransitionTimeout ()](#apidoc.element.react-bootstrap.Modal.propTypes.backdropTransitionTimeout)
- description and source-code
```javascript
backdropTransitionTimeout = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Modal.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.propTypes.bsSize"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>bsSize ()](#apidoc.element.react-bootstrap.Modal.propTypes.bsSize)
- description and source-code
```javascript
bsSize = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.propTypes.container"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>container ()](#apidoc.element.react-bootstrap.Modal.propTypes.container)
- description and source-code
```javascript
container = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.propTypes.containerClassName"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>containerClassName ()](#apidoc.element.react-bootstrap.Modal.propTypes.containerClassName)
- description and source-code
```javascript
containerClassName = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.propTypes.dialogClassName"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>dialogClassName ()](#apidoc.element.react-bootstrap.Modal.propTypes.dialogClassName)
- description and source-code
```javascript
dialogClassName = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.propTypes.dialogComponentClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>dialogComponentClass ()](#apidoc.element.react-bootstrap.Modal.propTypes.dialogComponentClass)
- description and source-code
```javascript
dialogComponentClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.propTypes.dialogTransitionTimeout"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>dialogTransitionTimeout ()](#apidoc.element.react-bootstrap.Modal.propTypes.dialogTransitionTimeout)
- description and source-code
```javascript
dialogTransitionTimeout = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.propTypes.enforceFocus"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>enforceFocus ()](#apidoc.element.react-bootstrap.Modal.propTypes.enforceFocus)
- description and source-code
```javascript
enforceFocus = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.propTypes.keyboard"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>keyboard ()](#apidoc.element.react-bootstrap.Modal.propTypes.keyboard)
- description and source-code
```javascript
keyboard = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.propTypes.manager"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>manager ()](#apidoc.element.react-bootstrap.Modal.propTypes.manager)
- description and source-code
```javascript
manager = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.propTypes.onBackdropClick"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>onBackdropClick ()](#apidoc.element.react-bootstrap.Modal.propTypes.onBackdropClick)
- description and source-code
```javascript
onBackdropClick = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.propTypes.onEnter"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>onEnter ()](#apidoc.element.react-bootstrap.Modal.propTypes.onEnter)
- description and source-code
```javascript
onEnter = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.propTypes.onEntered"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>onEntered ()](#apidoc.element.react-bootstrap.Modal.propTypes.onEntered)
- description and source-code
```javascript
onEntered = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.propTypes.onEntering"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>onEntering ()](#apidoc.element.react-bootstrap.Modal.propTypes.onEntering)
- description and source-code
```javascript
onEntering = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.propTypes.onEscapeKeyUp"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>onEscapeKeyUp ()](#apidoc.element.react-bootstrap.Modal.propTypes.onEscapeKeyUp)
- description and source-code
```javascript
onEscapeKeyUp = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.propTypes.onExit"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>onExit ()](#apidoc.element.react-bootstrap.Modal.propTypes.onExit)
- description and source-code
```javascript
onExit = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.propTypes.onExited"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>onExited ()](#apidoc.element.react-bootstrap.Modal.propTypes.onExited)
- description and source-code
```javascript
onExited = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.propTypes.onExiting"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>onExiting ()](#apidoc.element.react-bootstrap.Modal.propTypes.onExiting)
- description and source-code
```javascript
onExiting = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.propTypes.onHide"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>onHide ()](#apidoc.element.react-bootstrap.Modal.propTypes.onHide)
- description and source-code
```javascript
onHide = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.propTypes.onShow"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>onShow ()](#apidoc.element.react-bootstrap.Modal.propTypes.onShow)
- description and source-code
```javascript
onShow = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.propTypes.renderBackdrop"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>renderBackdrop ()](#apidoc.element.react-bootstrap.Modal.propTypes.renderBackdrop)
- description and source-code
```javascript
renderBackdrop = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.propTypes.restoreFocus"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>restoreFocus ()](#apidoc.element.react-bootstrap.Modal.propTypes.restoreFocus)
- description and source-code
```javascript
restoreFocus = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.propTypes.show"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>show ()](#apidoc.element.react-bootstrap.Modal.propTypes.show)
- description and source-code
```javascript
show = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.propTypes.transition"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.propTypes.</span>transition ()](#apidoc.element.react-bootstrap.Modal.propTypes.transition)
- description and source-code
```javascript
transition = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Modal.prototype"></a>[module react-bootstrap.Modal.prototype](#apidoc.module.react-bootstrap.Modal.prototype)

#### <a name="apidoc.element.react-bootstrap.Modal.prototype.componentWillUnmount"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.prototype.</span>componentWillUnmount ()](#apidoc.element.react-bootstrap.Modal.prototype.componentWillUnmount)
- description and source-code
```javascript
function componentWillUnmount() {
  // Clean up the listener if we need to.
  this.handleExited();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.prototype.getChildContext"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.prototype.</span>getChildContext ()](#apidoc.element.react-bootstrap.Modal.prototype.getChildContext)
- description and source-code
```javascript
function getChildContext() {
  return {
    $bs_modal: {
      onHide: this.props.onHide
    }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.prototype.handleDialogClick"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.prototype.</span>handleDialogClick (e)](#apidoc.element.react-bootstrap.Modal.prototype.handleDialogClick)
- description and source-code
```javascript
function handleDialogClick(e) {
  if (e.target !== e.currentTarget) {
    return;
  }

  this.props.onHide();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.prototype.handleEntering"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.prototype.</span>handleEntering ()](#apidoc.element.react-bootstrap.Modal.prototype.handleEntering)
- description and source-code
```javascript
function handleEntering() {
  // FIXME: This should work even when animation is disabled.
  _events2['default'].on(window, 'resize', this.handleWindowResize);
  this.updateStyle();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.prototype.handleExited"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.prototype.</span>handleExited ()](#apidoc.element.react-bootstrap.Modal.prototype.handleExited)
- description and source-code
```javascript
function handleExited() {
  // FIXME: This should work even when animation is disabled.
  _events2['default'].off(window, 'resize', this.handleWindowResize);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.prototype.handleWindowResize"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.prototype.</span>handleWindowResize ()](#apidoc.element.react-bootstrap.Modal.prototype.handleWindowResize)
- description and source-code
```javascript
function handleWindowResize() {
  this.updateStyle();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.prototype.</span>render ()](#apidoc.element.react-bootstrap.Modal.prototype.render)
- description and source-code
```javascript
function render() {
  var _this2 = this;

  var _props = this.props,
      backdrop = _props.backdrop,
      animation = _props.animation,
      show = _props.show,
      Dialog = _props.dialogComponentClass,
      className = _props.className,
      style = _props.style,
      children = _props.children,
      onEntering = _props.onEntering,
      onExited = _props.onExited,
      props = (0, _objectWithoutProperties3['default'])(_props, ['backdrop', 'animation', 'show', 'dialogComponentClass', 'className
', 'style', 'children', 'onEntering', 'onExited']);

  var _splitComponentProps = (0, _splitComponentProps3['default'])(props, _Modal2['default']),
      baseModalProps = _splitComponentProps[0],
      dialogProps = _splitComponentProps[1];

  var inClassName = show && !animation && 'in';

  return _react2['default'].createElement(
    _Modal2['default'],
    (0, _extends3['default'])({}, baseModalProps, {
      ref: function ref(c) {
        _this2._modal = c;
      },
      show: show,
      onEntering: (0, _createChainedFunction2['default'])(onEntering, this.handleEntering),
      onExited: (0, _createChainedFunction2['default'])(onExited, this.handleExited),
      backdrop: backdrop,
      backdropClassName: (0, _classnames2['default'])((0, _bootstrapUtils.prefix)(props, 'backdrop'), inClassName),
      containerClassName: (0, _bootstrapUtils.prefix)(props, 'open'),
      transition: animation ? _Fade2['default'] : undefined,
      dialogTransitionTimeout: Modal.TRANSITION_DURATION,
      backdropTransitionTimeout: Modal.BACKDROP_TRANSITION_DURATION
    }),
    _react2['default'].createElement(
      Dialog,
      (0, _extends3['default'])({}, dialogProps, {
        style: (0, _extends3['default'])({}, this.state.style, style),
        className: (0, _classnames2['default'])(className, inClassName),
        onClick: backdrop === true ? this.handleDialogClick : null
      }),
      children
    )
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Modal.prototype.updateStyle"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Modal.prototype.</span>updateStyle ()](#apidoc.element.react-bootstrap.Modal.prototype.updateStyle)
- description and source-code
```javascript
function updateStyle() {
  if (!_inDOM2['default']) {
    return;
  }

  var dialogNode = this._modal.getDialogElement();
  var dialogHeight = dialogNode.scrollHeight;

  var document = (0, _ownerDocument2['default'])(dialogNode);
  var bodyIsOverflowing = (0, _isOverflowing2['default'])(_reactDom2['default'].findDOMNode(this.props.container || document.body
));
  var modalIsOverflowing = dialogHeight > document.documentElement.clientHeight;

  this.setState({
    style: {
      paddingRight: bodyIsOverflowing && !modalIsOverflowing ? (0, _scrollbarSize2['default'])() : undefined,
      paddingLeft: !bodyIsOverflowing && modalIsOverflowing ? (0, _scrollbarSize2['default'])() : undefined
    }
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ModalBody"></a>[module react-bootstrap.ModalBody](#apidoc.module.react-bootstrap.ModalBody)

#### <a name="apidoc.element.react-bootstrap.ModalBody.ModalBody"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>ModalBody ()](#apidoc.element.react-bootstrap.ModalBody.ModalBody)
- description and source-code
```javascript
function ModalBody() {
  (0, _classCallCheck3['default'])(this, ModalBody);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ModalBody.propTypes"></a>[module react-bootstrap.ModalBody.propTypes](#apidoc.module.react-bootstrap.ModalBody.propTypes)

#### <a name="apidoc.element.react-bootstrap.ModalBody.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ModalBody.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.ModalBody.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ModalBody.propTypes.componentClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ModalBody.propTypes.</span>componentClass ()](#apidoc.element.react-bootstrap.ModalBody.propTypes.componentClass)
- description and source-code
```javascript
componentClass = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ModalBody.prototype"></a>[module react-bootstrap.ModalBody.prototype](#apidoc.module.react-bootstrap.ModalBody.prototype)

#### <a name="apidoc.element.react-bootstrap.ModalBody.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ModalBody.prototype.</span>render ()](#apidoc.element.react-bootstrap.ModalBody.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      Component = _props.componentClass,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['componentClass', 'className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _bootstrapUtils.getClassSet)(bsProps);

  return _react2['default'].createElement(Component, (0, _extends3['default'])({}, elementProps, {
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ModalFooter"></a>[module react-bootstrap.ModalFooter](#apidoc.module.react-bootstrap.ModalFooter)

#### <a name="apidoc.element.react-bootstrap.ModalFooter.ModalFooter"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>ModalFooter ()](#apidoc.element.react-bootstrap.ModalFooter.ModalFooter)
- description and source-code
```javascript
function ModalFooter() {
  (0, _classCallCheck3['default'])(this, ModalFooter);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ModalFooter.propTypes"></a>[module react-bootstrap.ModalFooter.propTypes](#apidoc.module.react-bootstrap.ModalFooter.propTypes)

#### <a name="apidoc.element.react-bootstrap.ModalFooter.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ModalFooter.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.ModalFooter.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ModalFooter.propTypes.componentClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ModalFooter.propTypes.</span>componentClass ()](#apidoc.element.react-bootstrap.ModalFooter.propTypes.componentClass)
- description and source-code
```javascript
componentClass = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ModalFooter.prototype"></a>[module react-bootstrap.ModalFooter.prototype](#apidoc.module.react-bootstrap.ModalFooter.prototype)

#### <a name="apidoc.element.react-bootstrap.ModalFooter.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ModalFooter.prototype.</span>render ()](#apidoc.element.react-bootstrap.ModalFooter.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      Component = _props.componentClass,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['componentClass', 'className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _bootstrapUtils.getClassSet)(bsProps);

  return _react2['default'].createElement(Component, (0, _extends3['default'])({}, elementProps, {
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ModalHeader"></a>[module react-bootstrap.ModalHeader](#apidoc.module.react-bootstrap.ModalHeader)

#### <a name="apidoc.element.react-bootstrap.ModalHeader.ModalHeader"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>ModalHeader ()](#apidoc.element.react-bootstrap.ModalHeader.ModalHeader)
- description and source-code
```javascript
function ModalHeader() {
  (0, _classCallCheck3['default'])(this, ModalHeader);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ModalHeader.contextTypes"></a>[module react-bootstrap.ModalHeader.contextTypes](#apidoc.module.react-bootstrap.ModalHeader.contextTypes)



# <a name="apidoc.module.react-bootstrap.ModalHeader.propTypes"></a>[module react-bootstrap.ModalHeader.propTypes](#apidoc.module.react-bootstrap.ModalHeader.propTypes)

#### <a name="apidoc.element.react-bootstrap.ModalHeader.propTypes.aria-label"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ModalHeader.propTypes.</span>aria-label ()](#apidoc.element.react-bootstrap.ModalHeader.propTypes.aria-label)
- description and source-code
```javascript
aria-label = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ModalHeader.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ModalHeader.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.ModalHeader.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ModalHeader.propTypes.closeButton"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ModalHeader.propTypes.</span>closeButton ()](#apidoc.element.react-bootstrap.ModalHeader.propTypes.closeButton)
- description and source-code
```javascript
closeButton = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ModalHeader.propTypes.onHide"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ModalHeader.propTypes.</span>onHide ()](#apidoc.element.react-bootstrap.ModalHeader.propTypes.onHide)
- description and source-code
```javascript
onHide = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ModalHeader.prototype"></a>[module react-bootstrap.ModalHeader.prototype](#apidoc.module.react-bootstrap.ModalHeader.prototype)

#### <a name="apidoc.element.react-bootstrap.ModalHeader.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ModalHeader.prototype.</span>render ()](#apidoc.element.react-bootstrap.ModalHeader.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      label = _props['aria-label'],
      closeButton = _props.closeButton,
      onHide = _props.onHide,
      className = _props.className,
      children = _props.children,
      props = (0, _objectWithoutProperties3['default'])(_props, ['aria-label', 'closeButton', 'onHide', 'className', 'children']);


  var modal = this.context.$bs_modal;

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _bootstrapUtils.getClassSet)(bsProps);

  return _react2['default'].createElement(
    'div',
    (0, _extends3['default'])({}, elementProps, {
      className: (0, _classnames2['default'])(className, classes)
    }),
    closeButton && _react2['default'].createElement(
      'button',
      {
        type: 'button',
        className: 'close',
        'aria-label': label,
        onClick: (0, _createChainedFunction2['default'])(modal && modal.onHide, onHide)
      },
      _react2['default'].createElement(
        'span',
        { 'aria-hidden': 'true' },
        '\xD7'
      )
    ),
    children
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ModalTitle"></a>[module react-bootstrap.ModalTitle](#apidoc.module.react-bootstrap.ModalTitle)

#### <a name="apidoc.element.react-bootstrap.ModalTitle.ModalTitle"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>ModalTitle ()](#apidoc.element.react-bootstrap.ModalTitle.ModalTitle)
- description and source-code
```javascript
function ModalTitle() {
  (0, _classCallCheck3['default'])(this, ModalTitle);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ModalTitle.propTypes"></a>[module react-bootstrap.ModalTitle.propTypes](#apidoc.module.react-bootstrap.ModalTitle.propTypes)

#### <a name="apidoc.element.react-bootstrap.ModalTitle.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ModalTitle.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.ModalTitle.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ModalTitle.propTypes.componentClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ModalTitle.propTypes.</span>componentClass ()](#apidoc.element.react-bootstrap.ModalTitle.propTypes.componentClass)
- description and source-code
```javascript
componentClass = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ModalTitle.prototype"></a>[module react-bootstrap.ModalTitle.prototype](#apidoc.module.react-bootstrap.ModalTitle.prototype)

#### <a name="apidoc.element.react-bootstrap.ModalTitle.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ModalTitle.prototype.</span>render ()](#apidoc.element.react-bootstrap.ModalTitle.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      Component = _props.componentClass,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['componentClass', 'className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _bootstrapUtils.getClassSet)(bsProps);

  return _react2['default'].createElement(Component, (0, _extends3['default'])({}, elementProps, {
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Nav"></a>[module react-bootstrap.Nav](#apidoc.module.react-bootstrap.Nav)

#### <a name="apidoc.element.react-bootstrap.Nav.Nav"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Nav ()](#apidoc.element.react-bootstrap.Nav.Nav)
- description and source-code
```javascript
function Nav() {
  (0, _classCallCheck3['default'])(this, Nav);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Nav.contextTypes"></a>[module react-bootstrap.Nav.contextTypes](#apidoc.module.react-bootstrap.Nav.contextTypes)



# <a name="apidoc.module.react-bootstrap.Nav.propTypes"></a>[module react-bootstrap.Nav.propTypes](#apidoc.module.react-bootstrap.Nav.propTypes)

#### <a name="apidoc.element.react-bootstrap.Nav.propTypes.activeHref"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Nav.propTypes.</span>activeHref ()](#apidoc.element.react-bootstrap.Nav.propTypes.activeHref)
- description and source-code
```javascript
activeHref = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Nav.propTypes.activeKey"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Nav.propTypes.</span>activeKey ()](#apidoc.element.react-bootstrap.Nav.propTypes.activeKey)
- description and source-code
```javascript
activeKey = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Nav.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Nav.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Nav.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Nav.propTypes.bsStyle"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Nav.propTypes.</span>bsStyle ()](#apidoc.element.react-bootstrap.Nav.propTypes.bsStyle)
- description and source-code
```javascript
bsStyle = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Nav.propTypes.justified"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Nav.propTypes.</span>justified ()](#apidoc.element.react-bootstrap.Nav.propTypes.justified)
- description and source-code
```javascript
justified = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Nav.propTypes.navbar"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Nav.propTypes.</span>navbar ()](#apidoc.element.react-bootstrap.Nav.propTypes.navbar)
- description and source-code
```javascript
navbar = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Nav.propTypes.onSelect"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Nav.propTypes.</span>onSelect ()](#apidoc.element.react-bootstrap.Nav.propTypes.onSelect)
- description and source-code
```javascript
onSelect = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Nav.propTypes.pullLeft"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Nav.propTypes.</span>pullLeft ()](#apidoc.element.react-bootstrap.Nav.propTypes.pullLeft)
- description and source-code
```javascript
pullLeft = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Nav.propTypes.pullRight"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Nav.propTypes.</span>pullRight ()](#apidoc.element.react-bootstrap.Nav.propTypes.pullRight)
- description and source-code
```javascript
pullRight = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Nav.propTypes.role"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Nav.propTypes.</span>role ()](#apidoc.element.react-bootstrap.Nav.propTypes.role)
- description and source-code
```javascript
role = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Nav.propTypes.stacked"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Nav.propTypes.</span>stacked ()](#apidoc.element.react-bootstrap.Nav.propTypes.stacked)
- description and source-code
```javascript
stacked = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Nav.prototype"></a>[module react-bootstrap.Nav.prototype](#apidoc.module.react-bootstrap.Nav.prototype)

#### <a name="apidoc.element.react-bootstrap.Nav.prototype.componentDidUpdate"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Nav.prototype.</span>componentDidUpdate ()](#apidoc.element.react-bootstrap.Nav.prototype.componentDidUpdate)
- description and source-code
```javascript
function componentDidUpdate() {
  var _this2 = this;

  if (!this._needsRefocus) {
    return;
  }

  this._needsRefocus = false;

  var children = this.props.children;

  var _getActiveProps = this.getActiveProps(),
      activeKey = _getActiveProps.activeKey,
      activeHref = _getActiveProps.activeHref;

  var activeChild = _ValidComponentChildren2['default'].find(children, function (child) {
    return _this2.isActive(child, activeKey, activeHref);
  });

  var childrenArray = _ValidComponentChildren2['default'].toArray(children);
  var activeChildIndex = childrenArray.indexOf(activeChild);

  var childNodes = _reactDom2['default'].findDOMNode(this).children;
  var activeNode = childNodes && childNodes[activeChildIndex];

  if (!activeNode || !activeNode.firstChild) {
    return;
  }

  activeNode.firstChild.focus();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Nav.prototype.getActiveProps"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Nav.prototype.</span>getActiveProps ()](#apidoc.element.react-bootstrap.Nav.prototype.getActiveProps)
- description and source-code
```javascript
function getActiveProps() {
  var tabContainer = this.context.$bs_tabContainer;

  if (tabContainer) {
    process.env.NODE_ENV !== 'production' ? (0, _warning2['default'])(this.props.activeKey == null && !this.props.activeHref, 'Specifying
 a '<Nav>' 'activeKey' or 'activeHref' in the context of ' + 'a '<TabContainer>' is not supported. Instead use '<TabContainer ' + ('
activeKey={' + this.props.activeKey + '} />'.')) : void 0;

    return tabContainer;
  }

  return this.props;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Nav.prototype.getNextActiveChild"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Nav.prototype.</span>getNextActiveChild (offset)](#apidoc.element.react-bootstrap.Nav.prototype.getNextActiveChild)
- description and source-code
```javascript
function getNextActiveChild(offset) {
  var _this3 = this;

  var children = this.props.children;

  var validChildren = children.filter(function (child) {
    return child.props.eventKey && !child.props.disabled;
  });

  var _getActiveProps2 = this.getActiveProps(),
      activeKey = _getActiveProps2.activeKey,
      activeHref = _getActiveProps2.activeHref;

  var activeChild = _ValidComponentChildren2['default'].find(children, function (child) {
    return _this3.isActive(child, activeKey, activeHref);
  });

  // This assumes the active child is not disabled.
  var activeChildIndex = validChildren.indexOf(activeChild);
  if (activeChildIndex === -1) {
    // Something has gone wrong. Select the first valid child we can find.
    return validChildren[0];
  }

  var nextIndex = activeChildIndex + offset;
  var numValidChildren = validChildren.length;

  if (nextIndex >= numValidChildren) {
    nextIndex = 0;
  } else if (nextIndex < 0) {
    nextIndex = numValidChildren - 1;
  }

  return validChildren[nextIndex];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Nav.prototype.getTabProps"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Nav.prototype.</span>getTabProps (child, tabContainer, navRole, active, onSelect)](#apidoc.element.react-bootstrap.Nav.prototype.getTabProps)
- description and source-code
```javascript
function getTabProps(child, tabContainer, navRole, active, onSelect) {
  var _this4 = this;

  if (!tabContainer && navRole !== 'tablist') {
    // No tab props here.
    return null;
  }

  var _child$props = child.props,
      id = _child$props.id,
      controls = _child$props['aria-controls'],
      eventKey = _child$props.eventKey,
      role = _child$props.role,
      onKeyDown = _child$props.onKeyDown,
      tabIndex = _child$props.tabIndex;


  if (tabContainer) {
    process.env.NODE_ENV !== 'production' ? (0, _warning2['default'])(!id && !controls, 'In the context of a '<TabContainer>', '<
NavItem>'s are given ' + 'generated 'id' and 'aria-controls' attributes for the sake of ' + 'proper component accessibility. Any
 provided ones will be ignored. ' + 'To control these attributes directly, provide a 'generateChildId' ' + 'prop to the parent '<
TabContainer>'.') : void 0;

    id = tabContainer.getTabId(eventKey);
    controls = tabContainer.getPaneId(eventKey);
  }

  if (navRole === 'tablist') {
    role = role || 'tab';
    onKeyDown = (0, _createChainedFunction2['default'])(function (event) {
      return _this4.handleTabKeyDown(onSelect, event);
    }, onKeyDown);
    tabIndex = active ? tabIndex : -1;
  }

  return {
    id: id,
    role: role,
    onKeyDown: onKeyDown,
    'aria-controls': controls,
    tabIndex: tabIndex
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Nav.prototype.handleTabKeyDown"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Nav.prototype.</span>handleTabKeyDown (onSelect, event)](#apidoc.element.react-bootstrap.Nav.prototype.handleTabKeyDown)
- description and source-code
```javascript
function handleTabKeyDown(onSelect, event) {
  var nextActiveChild = void 0;

  switch (event.keyCode) {
    case _keycode2['default'].codes.left:
    case _keycode2['default'].codes.up:
      nextActiveChild = this.getNextActiveChild(-1);
      break;
    case _keycode2['default'].codes.right:
    case _keycode2['default'].codes.down:
      nextActiveChild = this.getNextActiveChild(1);
      break;
    default:
      // It was a different key; don't handle this keypress.
      return;
  }

  event.preventDefault();

  if (onSelect && nextActiveChild && nextActiveChild.props.eventKey) {
    onSelect(nextActiveChild.props.eventKey);
  }

  this._needsRefocus = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Nav.prototype.isActive"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Nav.prototype.</span>isActive (_ref2, activeKey, activeHref)](#apidoc.element.react-bootstrap.Nav.prototype.isActive)
- description and source-code
```javascript
function isActive(_ref2, activeKey, activeHref) {
  var props = _ref2.props;

  if (props.active || activeKey != null && props.eventKey === activeKey || activeHref && props.href === activeHref) {
    return true;
  }

  return props.active;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Nav.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Nav.prototype.</span>render ()](#apidoc.element.react-bootstrap.Nav.prototype.render)
- description and source-code
```javascript
function render() {
  var _extends2,
      _this5 = this;

  var _props = this.props,
      stacked = _props.stacked,
      justified = _props.justified,
      onSelect = _props.onSelect,
      propsRole = _props.role,
      propsNavbar = _props.navbar,
      pullRight = _props.pullRight,
      pullLeft = _props.pullLeft,
      className = _props.className,
      children = _props.children,
      props = (0, _objectWithoutProperties3['default'])(_props, ['stacked', 'justified', 'onSelect', 'role', 'navbar', 'pullRight
', 'pullLeft', 'className', 'children']);


  var tabContainer = this.context.$bs_tabContainer;
  var role = propsRole || (tabContainer ? 'tablist' : null);

  var _getActiveProps3 = this.getActiveProps(),
      activeKey = _getActiveProps3.activeKey,
      activeHref = _getActiveProps3.activeHref;

  delete props.activeKey; // Accessed via this.getActiveProps().
  delete props.activeHref; // Accessed via this.getActiveProps().

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _extends4['default'])({}, (0, _bootstrapUtils.getClassSet)(bsProps), (_extends2 = {}, _extends2[(0, _bootstrapUtils
.prefix)(bsProps, 'stacked')] = stacked, _extends2[(0, _bootstrapUtils.prefix)(bsProps, 'justified')] = justified, _extends2));

  var navbar = propsNavbar != null ? propsNavbar : this.context.$bs_navbar;
  var pullLeftClassName = void 0;
  var pullRightClassName = void 0;

  if (navbar) {
    var navbarProps = this.context.$bs_navbar || { bsClass: 'navbar' };

    classes[(0, _bootstrapUtils.prefix)(navbarProps, 'nav')] = true;

    pullRightClassName = (0, _bootstrapUtils.prefix)(navbarProps, 'right');
    pullLeftClassName = (0, _bootstrapUtils.prefix)(navbarProps, 'left');
  } else {
    pullRightClassName = 'pull-right';
    pullLeftClassName = 'pull-left';
  }

  classes[pullRightClassName] = pullRight;
  classes[pullLeftClassName] = pullLeft;

  return _react2['default'].createElement(
    'ul',
    (0, _extends4['default'])({}, elementProps, {
      role: role,
      className: (0, _classnames2['default'])(className, classes)
    }),
    _ValidComponentChildren2['default'].map(children, function (child) {
      var active = _this5.isActive(child, activeKey, activeHref);
      var childOnSelect = (0, _createChainedFunction2['default'])(child.props.onSelect, onSelect, navbar && navbar.onSelect, tabContainer
 && tabContainer.onSelect);

      return (0, _react.cloneElement)(child, (0, _extends4['default'])({}, _this5.getTabProps(child, tabContainer, role, active,
childOnSelect), {
        active: active,
        activeKey: activeKey,
        activeHref: activeHref,
        onSelect: childOnSelect
      }));
    })
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.NavDropdown"></a>[module react-bootstrap.NavDropdown](#apidoc.module.react-bootstrap.NavDropdown)

#### <a name="apidoc.element.react-bootstrap.NavDropdown.NavDropdown"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>NavDropdown ()](#apidoc.element.react-bootstrap.NavDropdown.NavDropdown)
- description and source-code
```javascript
function NavDropdown() {
  (0, _classCallCheck3['default'])(this, NavDropdown);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.NavDropdown.propTypes"></a>[module react-bootstrap.NavDropdown.propTypes](#apidoc.module.react-bootstrap.NavDropdown.propTypes)

#### <a name="apidoc.element.react-bootstrap.NavDropdown.propTypes.active"></a>[function <span class="apidocSignatureSpan">react-bootstrap.NavDropdown.propTypes.</span>active ()](#apidoc.element.react-bootstrap.NavDropdown.propTypes.active)
- description and source-code
```javascript
active = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.NavDropdown.propTypes.children"></a>[function <span class="apidocSignatureSpan">react-bootstrap.NavDropdown.propTypes.</span>children ()](#apidoc.element.react-bootstrap.NavDropdown.propTypes.children)
- description and source-code
```javascript
children = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.NavDropdown.propTypes.noCaret"></a>[function <span class="apidocSignatureSpan">react-bootstrap.NavDropdown.propTypes.</span>noCaret ()](#apidoc.element.react-bootstrap.NavDropdown.propTypes.noCaret)
- description and source-code
```javascript
noCaret = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.NavDropdown.propTypes.open"></a>[function <span class="apidocSignatureSpan">react-bootstrap.NavDropdown.propTypes.</span>open (props, propName)](#apidoc.element.react-bootstrap.NavDropdown.propTypes.open)
- description and source-code
```javascript
open = function (props, propName) {
  if (props[propName] !== undefined) {
    if (!props[handler]) {
      return new Error('You have provided a '' + propName + '' prop to ' + ''' + name + '' without an '' + handler + '' handler.
This will render a read-only field. ' + 'If the field should be mutable use '' + defaultKey(propName) + ''. Otherwise, set '' +
handler + ''');
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.NavDropdown.propTypes.title"></a>[function <span class="apidocSignatureSpan">react-bootstrap.NavDropdown.propTypes.</span>title ()](#apidoc.element.react-bootstrap.NavDropdown.propTypes.title)
- description and source-code
```javascript
title = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.NavDropdown.prototype"></a>[module react-bootstrap.NavDropdown.prototype](#apidoc.module.react-bootstrap.NavDropdown.prototype)

#### <a name="apidoc.element.react-bootstrap.NavDropdown.prototype.isActive"></a>[function <span class="apidocSignatureSpan">react-bootstrap.NavDropdown.prototype.</span>isActive (_ref, activeKey, activeHref)](#apidoc.element.react-bootstrap.NavDropdown.prototype.isActive)
- description and source-code
```javascript
function isActive(_ref, activeKey, activeHref) {
  var props = _ref.props;

  var _this2 = this;

  if (props.active || activeKey != null && props.eventKey === activeKey || activeHref && props.href === activeHref) {
    return true;
  }

  if (_ValidComponentChildren2['default'].some(props.children, function (child) {
    return _this2.isActive(child, activeKey, activeHref);
  })) {
    return true;
  }

  return props.active;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.NavDropdown.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.NavDropdown.prototype.</span>render ()](#apidoc.element.react-bootstrap.NavDropdown.prototype.render)
- description and source-code
```javascript
function render() {
  var _this3 = this;

  var _props = this.props,
      title = _props.title,
      activeKey = _props.activeKey,
      activeHref = _props.activeHref,
      className = _props.className,
      style = _props.style,
      children = _props.children,
      props = (0, _objectWithoutProperties3['default'])(_props, ['title', 'activeKey', 'activeHref', 'className', 'style', 'children
']);


  var active = this.isActive(this, activeKey, activeHref);
  delete props.active; // Accessed via this.isActive().
  delete props.eventKey; // Accessed via this.isActive().

  var _splitComponentProps = (0, _splitComponentProps3['default'])(props, _Dropdown2['default'].ControlledComponent),
      dropdownProps = _splitComponentProps[0],
      toggleProps = _splitComponentProps[1];

  // Unlike for the other dropdowns, styling needs to go to the '<Dropdown>'
  // rather than the '<Dropdown.Toggle>'.

  return _react2['default'].createElement(
    _Dropdown2['default'],
    (0, _extends3['default'])({}, dropdownProps, {
      componentClass: 'li',
      className: (0, _classnames2['default'])(className, { active: active }),
      style: style
    }),
    _react2['default'].createElement(
      _Dropdown2['default'].Toggle,
      (0, _extends3['default'])({}, toggleProps, { useAnchor: true }),
      title
    ),
    _react2['default'].createElement(
      _Dropdown2['default'].Menu,
      null,
      _ValidComponentChildren2['default'].map(children, function (child) {
        return _react2['default'].cloneElement(child, {
          active: _this3.isActive(child, activeKey, activeHref)
        });
      })
    )
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.NavItem"></a>[module react-bootstrap.NavItem](#apidoc.module.react-bootstrap.NavItem)

#### <a name="apidoc.element.react-bootstrap.NavItem.NavItem"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>NavItem (props, context)](#apidoc.element.react-bootstrap.NavItem.NavItem)
- description and source-code
```javascript
function NavItem(props, context) {
  (0, _classCallCheck3['default'])(this, NavItem);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleClick = _this.handleClick.bind(_this);
  return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.NavItem.propTypes"></a>[module react-bootstrap.NavItem.propTypes](#apidoc.module.react-bootstrap.NavItem.propTypes)

#### <a name="apidoc.element.react-bootstrap.NavItem.propTypes.active"></a>[function <span class="apidocSignatureSpan">react-bootstrap.NavItem.propTypes.</span>active ()](#apidoc.element.react-bootstrap.NavItem.propTypes.active)
- description and source-code
```javascript
active = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.NavItem.propTypes.disabled"></a>[function <span class="apidocSignatureSpan">react-bootstrap.NavItem.propTypes.</span>disabled ()](#apidoc.element.react-bootstrap.NavItem.propTypes.disabled)
- description and source-code
```javascript
disabled = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.NavItem.propTypes.eventKey"></a>[function <span class="apidocSignatureSpan">react-bootstrap.NavItem.propTypes.</span>eventKey ()](#apidoc.element.react-bootstrap.NavItem.propTypes.eventKey)
- description and source-code
```javascript
eventKey = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.NavItem.propTypes.href"></a>[function <span class="apidocSignatureSpan">react-bootstrap.NavItem.propTypes.</span>href ()](#apidoc.element.react-bootstrap.NavItem.propTypes.href)
- description and source-code
```javascript
href = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.NavItem.propTypes.onClick"></a>[function <span class="apidocSignatureSpan">react-bootstrap.NavItem.propTypes.</span>onClick ()](#apidoc.element.react-bootstrap.NavItem.propTypes.onClick)
- description and source-code
```javascript
onClick = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.NavItem.propTypes.onSelect"></a>[function <span class="apidocSignatureSpan">react-bootstrap.NavItem.propTypes.</span>onSelect ()](#apidoc.element.react-bootstrap.NavItem.propTypes.onSelect)
- description and source-code
```javascript
onSelect = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.NavItem.propTypes.role"></a>[function <span class="apidocSignatureSpan">react-bootstrap.NavItem.propTypes.</span>role ()](#apidoc.element.react-bootstrap.NavItem.propTypes.role)
- description and source-code
```javascript
role = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.NavItem.prototype"></a>[module react-bootstrap.NavItem.prototype](#apidoc.module.react-bootstrap.NavItem.prototype)

#### <a name="apidoc.element.react-bootstrap.NavItem.prototype.handleClick"></a>[function <span class="apidocSignatureSpan">react-bootstrap.NavItem.prototype.</span>handleClick (e)](#apidoc.element.react-bootstrap.NavItem.prototype.handleClick)
- description and source-code
```javascript
function handleClick(e) {
  if (this.props.onSelect) {
    e.preventDefault();

    if (!this.props.disabled) {
      this.props.onSelect(this.props.eventKey, e);
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.NavItem.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.NavItem.prototype.</span>render ()](#apidoc.element.react-bootstrap.NavItem.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      active = _props.active,
      disabled = _props.disabled,
      onClick = _props.onClick,
      className = _props.className,
      style = _props.style,
      props = (0, _objectWithoutProperties3['default'])(_props, ['active', 'disabled', 'onClick', 'className', 'style']);


  delete props.onSelect;
  delete props.eventKey;

  // These are injected down by '<Nav>' for building '<SubNav>'s.
  delete props.activeKey;
  delete props.activeHref;

  if (!props.role) {
    if (props.href === '#') {
      props.role = 'button';
    }
  } else if (props.role === 'tab') {
    props['aria-selected'] = active;
  }

  return _react2['default'].createElement(
    'li',
    {
      role: 'presentation',
      className: (0, _classnames2['default'])(className, { active: active, disabled: disabled }),
      style: style
    },
    _react2['default'].createElement(_SafeAnchor2['default'], (0, _extends3['default'])({}, props, {
      disabled: disabled,
      onClick: (0, _createChainedFunction2['default'])(onClick, this.handleClick)
    }))
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Navbar"></a>[module react-bootstrap.Navbar](#apidoc.module.react-bootstrap.Navbar)

#### <a name="apidoc.element.react-bootstrap.Navbar.Navbar"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Navbar (props, context, updater)](#apidoc.element.react-bootstrap.Navbar.Navbar)
- description and source-code
```javascript
Navbar = function (props, context, updater) {
  // This constructor gets overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : void 0;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindPairs.length) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (initialState === undefined && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : _prodInvariant('82',
Constructor.displayName || 'ReactCompositeComponent') : void 0;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Navbar.Brand"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Navbar.</span>Brand ()](#apidoc.element.react-bootstrap.Navbar.Brand)
- description and source-code
```javascript
function NavbarBrand() {
  (0, _classCallCheck3['default'])(this, NavbarBrand);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Navbar.Collapse"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Navbar.</span>Collapse ()](#apidoc.element.react-bootstrap.Navbar.Collapse)
- description and source-code
```javascript
function NavbarCollapse() {
  (0, _classCallCheck3['default'])(this, NavbarCollapse);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Navbar.ControlledComponent"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Navbar.</span>ControlledComponent (props, context)](#apidoc.element.react-bootstrap.Navbar.ControlledComponent)
- description and source-code
```javascript
function Navbar(props, context) {
  (0, _classCallCheck3['default'])(this, Navbar);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleToggle = _this.handleToggle.bind(_this);
  _this.handleCollapse = _this.handleCollapse.bind(_this);
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Navbar.Form"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Navbar.</span>Form (_ref, _ref2)](#apidoc.element.react-bootstrap.Navbar.Form)
- description and source-code
```javascript
function Wrapper(_ref, _ref2) {
  var _ref2$$bs_navbar = _ref2.$bs_navbar,
      navbarProps = _ref2$$bs_navbar === undefined ? { bsClass: 'navbar' } : _ref2$$bs_navbar;
  var Component = _ref.componentClass,
      className = _ref.className,
      pullRight = _ref.pullRight,
      pullLeft = _ref.pullLeft,
      props = (0, _objectWithoutProperties3['default'])(_ref, ['componentClass', 'className', 'pullRight', 'pullLeft']);
  return _react2['default'].createElement(Component, (0, _extends4['default'])({}, props, {
    className: (0, _classnames2['default'])(className, (0, _bootstrapUtils.prefix)(navbarProps, suffix), pullRight && (0, _bootstrapUtils
.prefix)(navbarProps, 'right'), pullLeft && (0, _bootstrapUtils.prefix)(navbarProps, 'left'))
  }));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Navbar.Header"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Navbar.</span>Header ()](#apidoc.element.react-bootstrap.Navbar.Header)
- description and source-code
```javascript
function NavbarHeader() {
  (0, _classCallCheck3['default'])(this, NavbarHeader);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Navbar.Link"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Navbar.</span>Link (_ref, _ref2)](#apidoc.element.react-bootstrap.Navbar.Link)
- description and source-code
```javascript
function Wrapper(_ref, _ref2) {
  var _ref2$$bs_navbar = _ref2.$bs_navbar,
      navbarProps = _ref2$$bs_navbar === undefined ? { bsClass: 'navbar' } : _ref2$$bs_navbar;
  var Component = _ref.componentClass,
      className = _ref.className,
      pullRight = _ref.pullRight,
      pullLeft = _ref.pullLeft,
      props = (0, _objectWithoutProperties3['default'])(_ref, ['componentClass', 'className', 'pullRight', 'pullLeft']);
  return _react2['default'].createElement(Component, (0, _extends4['default'])({}, props, {
    className: (0, _classnames2['default'])(className, (0, _bootstrapUtils.prefix)(navbarProps, suffix), pullRight && (0, _bootstrapUtils
.prefix)(navbarProps, 'right'), pullLeft && (0, _bootstrapUtils.prefix)(navbarProps, 'left'))
  }));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Navbar.Text"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Navbar.</span>Text (_ref, _ref2)](#apidoc.element.react-bootstrap.Navbar.Text)
- description and source-code
```javascript
function Wrapper(_ref, _ref2) {
  var _ref2$$bs_navbar = _ref2.$bs_navbar,
      navbarProps = _ref2$$bs_navbar === undefined ? { bsClass: 'navbar' } : _ref2$$bs_navbar;
  var Component = _ref.componentClass,
      className = _ref.className,
      pullRight = _ref.pullRight,
      pullLeft = _ref.pullLeft,
      props = (0, _objectWithoutProperties3['default'])(_ref, ['componentClass', 'className', 'pullRight', 'pullLeft']);
  return _react2['default'].createElement(Component, (0, _extends4['default'])({}, props, {
    className: (0, _classnames2['default'])(className, (0, _bootstrapUtils.prefix)(navbarProps, suffix), pullRight && (0, _bootstrapUtils
.prefix)(navbarProps, 'right'), pullLeft && (0, _bootstrapUtils.prefix)(navbarProps, 'left'))
  }));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Navbar.Toggle"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Navbar.</span>Toggle ()](#apidoc.element.react-bootstrap.Navbar.Toggle)
- description and source-code
```javascript
function NavbarToggle() {
  (0, _classCallCheck3['default'])(this, NavbarToggle);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Navbar.deferControlTo"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Navbar.</span>deferControlTo (newComponent)](#apidoc.element.react-bootstrap.Navbar.deferControlTo)
- description and source-code
```javascript
deferControlTo = function (newComponent) {
  var additions = arguments.length <= 1 || arguments[1] === undefined ? {} : arguments[1];
  var nextMethods = arguments[2];

  return uncontrollable(newComponent, _extends({}, controlledValues, additions), nextMethods);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Navbar.Collapse"></a>[module react-bootstrap.Navbar.Collapse](#apidoc.module.react-bootstrap.Navbar.Collapse)

#### <a name="apidoc.element.react-bootstrap.Navbar.Collapse.Collapse"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Navbar.</span>Collapse ()](#apidoc.element.react-bootstrap.Navbar.Collapse.Collapse)
- description and source-code
```javascript
function NavbarCollapse() {
  (0, _classCallCheck3['default'])(this, NavbarCollapse);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Navbar.Collapse.prototype"></a>[module react-bootstrap.Navbar.Collapse.prototype](#apidoc.module.react-bootstrap.Navbar.Collapse.prototype)

#### <a name="apidoc.element.react-bootstrap.Navbar.Collapse.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Navbar.Collapse.prototype.</span>render ()](#apidoc.element.react-bootstrap.Navbar.Collapse.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      children = _props.children,
      props = (0, _objectWithoutProperties3['default'])(_props, ['children']);

  var navbarProps = this.context.$bs_navbar || { bsClass: 'navbar' };

  var bsClassName = (0, _bootstrapUtils.prefix)(navbarProps, 'collapse');

  return _react2['default'].createElement(
    _Collapse2['default'],
    (0, _extends3['default'])({ 'in': navbarProps.expanded }, props),
    _react2['default'].createElement(
      'div',
      { className: bsClassName },
      children
    )
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Navbar.ControlledComponent"></a>[module react-bootstrap.Navbar.ControlledComponent](#apidoc.module.react-bootstrap.Navbar.ControlledComponent)

#### <a name="apidoc.element.react-bootstrap.Navbar.ControlledComponent.ControlledComponent"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Navbar.</span>ControlledComponent (props, context)](#apidoc.element.react-bootstrap.Navbar.ControlledComponent.ControlledComponent)
- description and source-code
```javascript
function Navbar(props, context) {
  (0, _classCallCheck3['default'])(this, Navbar);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleToggle = _this.handleToggle.bind(_this);
  _this.handleCollapse = _this.handleCollapse.bind(_this);
  return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Navbar.ControlledComponent.prototype"></a>[module react-bootstrap.Navbar.ControlledComponent.prototype](#apidoc.module.react-bootstrap.Navbar.ControlledComponent.prototype)

#### <a name="apidoc.element.react-bootstrap.Navbar.ControlledComponent.prototype.getChildContext"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Navbar.ControlledComponent.prototype.</span>getChildContext ()](#apidoc.element.react-bootstrap.Navbar.ControlledComponent.prototype.getChildContext)
- description and source-code
```javascript
function getChildContext() {
  var _props = this.props,
      bsClass = _props.bsClass,
      expanded = _props.expanded,
      onSelect = _props.onSelect,
      collapseOnSelect = _props.collapseOnSelect;


  return {
    $bs_navbar: {
      bsClass: bsClass,
      expanded: expanded,
      onToggle: this.handleToggle,
      onSelect: (0, _createChainedFunction2['default'])(onSelect, collapseOnSelect ? this.handleCollapse : null)
    }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Navbar.ControlledComponent.prototype.handleCollapse"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Navbar.ControlledComponent.prototype.</span>handleCollapse ()](#apidoc.element.react-bootstrap.Navbar.ControlledComponent.prototype.handleCollapse)
- description and source-code
```javascript
function handleCollapse() {
  var _props2 = this.props,
      onToggle = _props2.onToggle,
      expanded = _props2.expanded;


  if (expanded) {
    onToggle(false);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Navbar.ControlledComponent.prototype.handleToggle"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Navbar.ControlledComponent.prototype.</span>handleToggle ()](#apidoc.element.react-bootstrap.Navbar.ControlledComponent.prototype.handleToggle)
- description and source-code
```javascript
function handleToggle() {
  var _props3 = this.props,
      onToggle = _props3.onToggle,
      expanded = _props3.expanded;


  onToggle(!expanded);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Navbar.ControlledComponent.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Navbar.ControlledComponent.prototype.</span>render ()](#apidoc.element.react-bootstrap.Navbar.ControlledComponent.prototype.render)
- description and source-code
```javascript
function render() {
  var _extends2;

  var _props4 = this.props,
      Component = _props4.componentClass,
      fixedTop = _props4.fixedTop,
      fixedBottom = _props4.fixedBottom,
      staticTop = _props4.staticTop,
      inverse = _props4.inverse,
      fluid = _props4.fluid,
      className = _props4.className,
      children = _props4.children,
      props = (0, _objectWithoutProperties3['default'])(_props4, ['componentClass', 'fixedTop', 'fixedBottom', 'staticTop', 'inverse
', 'fluid', 'className', 'children']);

  var _splitBsPropsAndOmit = (0, _bootstrapUtils.splitBsPropsAndOmit)(props, ['expanded', 'onToggle', 'onSelect', 'collapseOnSelect
']),
      bsProps = _splitBsPropsAndOmit[0],
      elementProps = _splitBsPropsAndOmit[1];

  // will result in some false positives but that seems better
  // than false negatives. strict 'undefined' check allows explicit
  // "nulling" of the role if the user really doesn't want one


  if (elementProps.role === undefined && Component !== 'nav') {
    elementProps.role = 'navigation';
  }

  if (inverse) {
    bsProps.bsStyle = _StyleConfig.Style.INVERSE;
  }

  var classes = (0, _extends4['default'])({}, (0, _bootstrapUtils.getClassSet)(bsProps), (_extends2 = {}, _extends2[(0, _bootstrapUtils
.prefix)(bsProps, 'fixed-top')] = fixedTop, _extends2[(0, _bootstrapUtils.prefix)(bsProps, 'fixed-bottom')] = fixedBottom, _extends2
[(0, _bootstrapUtils.prefix)(bsProps, 'static-top')] = staticTop, _extends2));

  return _react2['default'].createElement(
    Component,
    (0, _extends4['default'])({}, elementProps, {
      className: (0, _classnames2['default'])(className, classes)
    }),
    _react2['default'].createElement(
      _Grid2['default'],
      { fluid: fluid },
      children
    )
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Navbar.Header"></a>[module react-bootstrap.Navbar.Header](#apidoc.module.react-bootstrap.Navbar.Header)

#### <a name="apidoc.element.react-bootstrap.Navbar.Header.Header"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Navbar.</span>Header ()](#apidoc.element.react-bootstrap.Navbar.Header.Header)
- description and source-code
```javascript
function NavbarHeader() {
  (0, _classCallCheck3['default'])(this, NavbarHeader);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Navbar.Header.prototype"></a>[module react-bootstrap.Navbar.Header.prototype](#apidoc.module.react-bootstrap.Navbar.Header.prototype)

#### <a name="apidoc.element.react-bootstrap.Navbar.Header.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Navbar.Header.prototype.</span>render ()](#apidoc.element.react-bootstrap.Navbar.Header.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['className']);

  var navbarProps = this.context.$bs_navbar || { bsClass: 'navbar' };

  var bsClassName = (0, _bootstrapUtils.prefix)(navbarProps, 'header');

  return _react2['default'].createElement('div', (0, _extends3['default'])({}, props, { className: (0, _classnames2['default'])(
className, bsClassName) }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Navbar.Toggle"></a>[module react-bootstrap.Navbar.Toggle](#apidoc.module.react-bootstrap.Navbar.Toggle)

#### <a name="apidoc.element.react-bootstrap.Navbar.Toggle.Toggle"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Navbar.</span>Toggle ()](#apidoc.element.react-bootstrap.Navbar.Toggle.Toggle)
- description and source-code
```javascript
function NavbarToggle() {
  (0, _classCallCheck3['default'])(this, NavbarToggle);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Navbar.Toggle.prototype"></a>[module react-bootstrap.Navbar.Toggle.prototype](#apidoc.module.react-bootstrap.Navbar.Toggle.prototype)

#### <a name="apidoc.element.react-bootstrap.Navbar.Toggle.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Navbar.Toggle.prototype.</span>render ()](#apidoc.element.react-bootstrap.Navbar.Toggle.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      onClick = _props.onClick,
      className = _props.className,
      children = _props.children,
      props = (0, _objectWithoutProperties3['default'])(_props, ['onClick', 'className', 'children']);

  var navbarProps = this.context.$bs_navbar || { bsClass: 'navbar' };

  var buttonProps = (0, _extends3['default'])({
    type: 'button'
  }, props, {
    onClick: (0, _createChainedFunction2['default'])(onClick, navbarProps.onToggle),
    className: (0, _classnames2['default'])(className, (0, _bootstrapUtils.prefix)(navbarProps, 'toggle'), !navbarProps.expanded
 && 'collapsed')
  });

  if (children) {
    return _react2['default'].createElement(
      'button',
      buttonProps,
      children
    );
  }

  return _react2['default'].createElement(
    'button',
    buttonProps,
    _react2['default'].createElement(
      'span',
      { className: 'sr-only' },
      'Toggle navigation'
    ),
    _react2['default'].createElement('span', { className: 'icon-bar' }),
    _react2['default'].createElement('span', { className: 'icon-bar' }),
    _react2['default'].createElement('span', { className: 'icon-bar' })
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Navbar.propTypes"></a>[module react-bootstrap.Navbar.propTypes](#apidoc.module.react-bootstrap.Navbar.propTypes)

#### <a name="apidoc.element.react-bootstrap.Navbar.propTypes.bsStyle"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Navbar.propTypes.</span>bsStyle ()](#apidoc.element.react-bootstrap.Navbar.propTypes.bsStyle)
- description and source-code
```javascript
bsStyle = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Navbar.propTypes.expanded"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Navbar.propTypes.</span>expanded (props, propName)](#apidoc.element.react-bootstrap.Navbar.propTypes.expanded)
- description and source-code
```javascript
expanded = function (props, propName) {
  if (props[propName] !== undefined) {
    if (!props[handler]) {
      return new Error('You have provided a '' + propName + '' prop to ' + ''' + name + '' without an '' + handler + '' handler.
This will render a read-only field. ' + 'If the field should be mutable use '' + defaultKey(propName) + ''. Otherwise, set '' +
handler + ''');
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Navbar.prototype"></a>[module react-bootstrap.Navbar.prototype](#apidoc.module.react-bootstrap.Navbar.prototype)

#### <a name="apidoc.element.react-bootstrap.Navbar.prototype.componentWillMount"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Navbar.prototype.</span>componentWillMount ()](#apidoc.element.react-bootstrap.Navbar.prototype.componentWillMount)
- description and source-code
```javascript
function componentWillMount() {
  var _this = this;

  var props = this.props;

  this._values = {};

  controlledProps.forEach(function (key) {
    _this._values[key] = props[utils.defaultKey(key)];
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Navbar.prototype.componentWillReceiveProps"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Navbar.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.react-bootstrap.Navbar.prototype.componentWillReceiveProps)
- description and source-code
```javascript
function componentWillReceiveProps(nextProps) {
  var _this2 = this;

  var props = this.props;

  controlledProps.forEach(function (key) {
    if (utils.getValue(nextProps, key) === undefined && utils.getValue(props, key) !== undefined) {
      _this2._values[key] = nextProps[utils.defaultKey(key)];
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Navbar.prototype.constructor"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Navbar.prototype.</span>constructor (props, context, updater)](#apidoc.element.react-bootstrap.Navbar.prototype.constructor)
- description and source-code
```javascript
constructor = function (props, context, updater) {
  // This constructor gets overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : void 0;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindPairs.length) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (initialState === undefined && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : _prodInvariant('82',
Constructor.displayName || 'ReactCompositeComponent') : void 0;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Navbar.prototype.getControlledInstance"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Navbar.prototype.</span>getControlledInstance ()](#apidoc.element.react-bootstrap.Navbar.prototype.getControlledInstance)
- description and source-code
```javascript
function getControlledInstance() {
  return this.refs.inner;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Navbar.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Navbar.prototype.</span>render ()](#apidoc.element.react-bootstrap.Navbar.prototype.render)
- description and source-code
```javascript
function render() {
  var _this3 = this;

  var newProps = {},
      props = omitProps(this.props);

  utils.each(controlledValues, function (handle, propName) {
    var linkPropName = utils.getLinkName(propName),
        prop = _this3.props[propName];

    if (linkPropName && !isProp(_this3.props, propName) && isProp(_this3.props, linkPropName)) {
      prop = _this3.props[linkPropName].value;
    }

    newProps[propName] = prop !== undefined ? prop : _this3._values[propName];

    newProps[handle] = setAndNotify.bind(_this3, propName);
  });

  newProps = _extends({}, props, newProps, {
    ref: isCompositeComponent ? 'inner' : null
  });

  return _react2.default.createElement(Component, newProps);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Navbar.prototype.shouldComponentUpdate"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Navbar.prototype.</span>shouldComponentUpdate ()](#apidoc.element.react-bootstrap.Navbar.prototype.shouldComponentUpdate)
- description and source-code
```javascript
function shouldComponentUpdate() {
  //let the forceUpdate trigger the update
  return !this._notifying;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Navbar.prototype.__reactAutoBindPairs"></a>[module react-bootstrap.Navbar.prototype.__reactAutoBindPairs](#apidoc.module.react-bootstrap.Navbar.prototype.__reactAutoBindPairs)

#### <a name="apidoc.element.react-bootstrap.Navbar.prototype.__reactAutoBindPairs.1"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Navbar.prototype.__reactAutoBindPairs.</span>1 ()](#apidoc.element.react-bootstrap.Navbar.prototype.__reactAutoBindPairs.1)
- description and source-code
```javascript
function getControlledInstance() {
  return this.refs.inner;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.NavbarBrand"></a>[module react-bootstrap.NavbarBrand](#apidoc.module.react-bootstrap.NavbarBrand)

#### <a name="apidoc.element.react-bootstrap.NavbarBrand.NavbarBrand"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>NavbarBrand ()](#apidoc.element.react-bootstrap.NavbarBrand.NavbarBrand)
- description and source-code
```javascript
function NavbarBrand() {
  (0, _classCallCheck3['default'])(this, NavbarBrand);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.NavbarBrand.contextTypes"></a>[module react-bootstrap.NavbarBrand.contextTypes](#apidoc.module.react-bootstrap.NavbarBrand.contextTypes)



# <a name="apidoc.module.react-bootstrap.NavbarBrand.prototype"></a>[module react-bootstrap.NavbarBrand.prototype](#apidoc.module.react-bootstrap.NavbarBrand.prototype)

#### <a name="apidoc.element.react-bootstrap.NavbarBrand.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.NavbarBrand.prototype.</span>render ()](#apidoc.element.react-bootstrap.NavbarBrand.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      className = _props.className,
      children = _props.children,
      props = (0, _objectWithoutProperties3['default'])(_props, ['className', 'children']);

  var navbarProps = this.context.$bs_navbar || { bsClass: 'navbar' };

  var bsClassName = (0, _bootstrapUtils.prefix)(navbarProps, 'brand');

  if (_react2['default'].isValidElement(children)) {
    return _react2['default'].cloneElement(children, {
      className: (0, _classnames2['default'])(children.props.className, className, bsClassName)
    });
  }

  return _react2['default'].createElement(
    'span',
    (0, _extends3['default'])({}, props, { className: (0, _classnames2['default'])(className, bsClassName) }),
    children
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Overlay"></a>[module react-bootstrap.Overlay](#apidoc.module.react-bootstrap.Overlay)

#### <a name="apidoc.element.react-bootstrap.Overlay.Overlay"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Overlay ()](#apidoc.element.react-bootstrap.Overlay.Overlay)
- description and source-code
```javascript
function Overlay() {
  (0, _classCallCheck3['default'])(this, Overlay);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Overlay.defaultProps"></a>[module react-bootstrap.Overlay.defaultProps](#apidoc.module.react-bootstrap.Overlay.defaultProps)

#### <a name="apidoc.element.react-bootstrap.Overlay.defaultProps.animation"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Overlay.defaultProps.</span>animation ()](#apidoc.element.react-bootstrap.Overlay.defaultProps.animation)
- description and source-code
```javascript
function Fade() {
  (0, _classCallCheck3['default'])(this, Fade);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Overlay.propTypes"></a>[module react-bootstrap.Overlay.propTypes](#apidoc.module.react-bootstrap.Overlay.propTypes)

#### <a name="apidoc.element.react-bootstrap.Overlay.propTypes.animation"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>animation ()](#apidoc.element.react-bootstrap.Overlay.propTypes.animation)
- description and source-code
```javascript
animation = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Overlay.propTypes.container"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>container ()](#apidoc.element.react-bootstrap.Overlay.propTypes.container)
- description and source-code
```javascript
container = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Overlay.propTypes.containerPadding"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>containerPadding ()](#apidoc.element.react-bootstrap.Overlay.propTypes.containerPadding)
- description and source-code
```javascript
containerPadding = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Overlay.propTypes.onEnter"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>onEnter ()](#apidoc.element.react-bootstrap.Overlay.propTypes.onEnter)
- description and source-code
```javascript
onEnter = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Overlay.propTypes.onEntered"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>onEntered ()](#apidoc.element.react-bootstrap.Overlay.propTypes.onEntered)
- description and source-code
```javascript
onEntered = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Overlay.propTypes.onEntering"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>onEntering ()](#apidoc.element.react-bootstrap.Overlay.propTypes.onEntering)
- description and source-code
```javascript
onEntering = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Overlay.propTypes.onExit"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>onExit ()](#apidoc.element.react-bootstrap.Overlay.propTypes.onExit)
- description and source-code
```javascript
onExit = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Overlay.propTypes.onExited"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>onExited ()](#apidoc.element.react-bootstrap.Overlay.propTypes.onExited)
- description and source-code
```javascript
onExited = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Overlay.propTypes.onExiting"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>onExiting ()](#apidoc.element.react-bootstrap.Overlay.propTypes.onExiting)
- description and source-code
```javascript
onExiting = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Overlay.propTypes.onHide"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>onHide ()](#apidoc.element.react-bootstrap.Overlay.propTypes.onHide)
- description and source-code
```javascript
onHide = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Overlay.propTypes.placement"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>placement ()](#apidoc.element.react-bootstrap.Overlay.propTypes.placement)
- description and source-code
```javascript
placement = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Overlay.propTypes.rootClose"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>rootClose ()](#apidoc.element.react-bootstrap.Overlay.propTypes.rootClose)
- description and source-code
```javascript
rootClose = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Overlay.propTypes.shouldUpdatePosition"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>shouldUpdatePosition ()](#apidoc.element.react-bootstrap.Overlay.propTypes.shouldUpdatePosition)
- description and source-code
```javascript
shouldUpdatePosition = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Overlay.propTypes.show"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>show ()](#apidoc.element.react-bootstrap.Overlay.propTypes.show)
- description and source-code
```javascript
show = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Overlay.propTypes.target"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>target ()](#apidoc.element.react-bootstrap.Overlay.propTypes.target)
- description and source-code
```javascript
target = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Overlay.propTypes.transition"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Overlay.propTypes.</span>transition ()](#apidoc.element.react-bootstrap.Overlay.propTypes.transition)
- description and source-code
```javascript
transition = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Overlay.prototype"></a>[module react-bootstrap.Overlay.prototype](#apidoc.module.react-bootstrap.Overlay.prototype)

#### <a name="apidoc.element.react-bootstrap.Overlay.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Overlay.prototype.</span>render ()](#apidoc.element.react-bootstrap.Overlay.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      animation = _props.animation,
      children = _props.children,
      props = (0, _objectWithoutProperties3['default'])(_props, ['animation', 'children']);


  var transition = animation === true ? _Fade2['default'] : animation || null;

  var child = void 0;

  if (!transition) {
    child = (0, _react.cloneElement)(children, {
      className: (0, _classnames2['default'])(children.props.className, 'in')
    });
  } else {
    child = children;
  }

  return _react2['default'].createElement(
    _Overlay2['default'],
    (0, _extends3['default'])({}, props, {
      transition: transition
    }),
    child
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.OverlayTrigger"></a>[module react-bootstrap.OverlayTrigger](#apidoc.module.react-bootstrap.OverlayTrigger)

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.OverlayTrigger"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>OverlayTrigger (props, context)](#apidoc.element.react-bootstrap.OverlayTrigger.OverlayTrigger)
- description and source-code
```javascript
function OverlayTrigger(props, context) {
  (0, _classCallCheck3['default'])(this, OverlayTrigger);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleToggle = _this.handleToggle.bind(_this);
  _this.handleDelayedShow = _this.handleDelayedShow.bind(_this);
  _this.handleDelayedHide = _this.handleDelayedHide.bind(_this);
  _this.handleHide = _this.handleHide.bind(_this);

  _this.handleMouseOver = function (e) {
    return _this.handleMouseOverOut(_this.handleDelayedShow, e);
  };
  _this.handleMouseOut = function (e) {
    return _this.handleMouseOverOut(_this.handleDelayedHide, e);
  };

  _this._mountNode = null;

  _this.state = {
    show: props.defaultOverlayShown
  };
  return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.OverlayTrigger.propTypes"></a>[module react-bootstrap.OverlayTrigger.propTypes](#apidoc.module.react-bootstrap.OverlayTrigger.propTypes)

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.propTypes.animation"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>animation ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.animation)
- description and source-code
```javascript
animation = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.propTypes.container"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>container ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.container)
- description and source-code
```javascript
container = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.propTypes.containerPadding"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>containerPadding ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.containerPadding)
- description and source-code
```javascript
containerPadding = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.propTypes.defaultOverlayShown"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>defaultOverlayShown ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.defaultOverlayShown)
- description and source-code
```javascript
defaultOverlayShown = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.propTypes.delay"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>delay ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.delay)
- description and source-code
```javascript
delay = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.propTypes.delayHide"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>delayHide ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.delayHide)
- description and source-code
```javascript
delayHide = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.propTypes.delayShow"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>delayShow ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.delayShow)
- description and source-code
```javascript
delayShow = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onBlur"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>onBlur ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onBlur)
- description and source-code
```javascript
onBlur = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onClick"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>onClick ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onClick)
- description and source-code
```javascript
onClick = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onEnter"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>onEnter ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onEnter)
- description and source-code
```javascript
onEnter = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onEntered"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>onEntered ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onEntered)
- description and source-code
```javascript
onEntered = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onEntering"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>onEntering ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onEntering)
- description and source-code
```javascript
onEntering = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onExit"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>onExit ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onExit)
- description and source-code
```javascript
onExit = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onExited"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>onExited ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onExited)
- description and source-code
```javascript
onExited = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onExiting"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>onExiting ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onExiting)
- description and source-code
```javascript
onExiting = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onFocus"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>onFocus ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onFocus)
- description and source-code
```javascript
onFocus = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onHide"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>onHide ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onHide)
- description and source-code
```javascript
onHide = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onMouseOut"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>onMouseOut ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onMouseOut)
- description and source-code
```javascript
onMouseOut = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onMouseOver"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>onMouseOver ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.onMouseOver)
- description and source-code
```javascript
onMouseOver = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.propTypes.overlay"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>overlay ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.overlay)
- description and source-code
```javascript
overlay = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.propTypes.placement"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>placement ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.placement)
- description and source-code
```javascript
placement = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.propTypes.rootClose"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>rootClose ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.rootClose)
- description and source-code
```javascript
rootClose = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.propTypes.shouldUpdatePosition"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>shouldUpdatePosition ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.shouldUpdatePosition)
- description and source-code
```javascript
shouldUpdatePosition = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.propTypes.show"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>show ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.show)
- description and source-code
```javascript
show = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.propTypes.target"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>target ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.target)
- description and source-code
```javascript
target = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.propTypes.transition"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>transition ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.transition)
- description and source-code
```javascript
transition = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.propTypes.trigger"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.propTypes.</span>trigger ()](#apidoc.element.react-bootstrap.OverlayTrigger.propTypes.trigger)
- description and source-code
```javascript
trigger = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.OverlayTrigger.prototype"></a>[module react-bootstrap.OverlayTrigger.prototype](#apidoc.module.react-bootstrap.OverlayTrigger.prototype)

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.prototype.componentDidMount"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.prototype.</span>componentDidMount ()](#apidoc.element.react-bootstrap.OverlayTrigger.prototype.componentDidMount)
- description and source-code
```javascript
function componentDidMount() {
  this._mountNode = document.createElement('div');
  this.renderOverlay();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.prototype.componentDidUpdate"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.prototype.</span>componentDidUpdate ()](#apidoc.element.react-bootstrap.OverlayTrigger.prototype.componentDidUpdate)
- description and source-code
```javascript
function componentDidUpdate() {
  this.renderOverlay();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.prototype.componentWillUnmount"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.prototype.</span>componentWillUnmount ()](#apidoc.element.react-bootstrap.OverlayTrigger.prototype.componentWillUnmount)
- description and source-code
```javascript
function componentWillUnmount() {
  _reactDom2['default'].unmountComponentAtNode(this._mountNode);
  this._mountNode = null;

  clearTimeout(this._hoverShowDelay);
  clearTimeout(this._hoverHideDelay);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.prototype.handleDelayedHide"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.prototype.</span>handleDelayedHide ()](#apidoc.element.react-bootstrap.OverlayTrigger.prototype.handleDelayedHide)
- description and source-code
```javascript
function handleDelayedHide() {
  var _this3 = this;

  if (this._hoverShowDelay != null) {
    clearTimeout(this._hoverShowDelay);
    this._hoverShowDelay = null;
    return;
  }

  if (!this.state.show || this._hoverHideDelay != null) {
    return;
  }

  var delay = this.props.delayHide != null ? this.props.delayHide : this.props.delay;

  if (!delay) {
    this.hide();
    return;
  }

  this._hoverHideDelay = setTimeout(function () {
    _this3._hoverHideDelay = null;
    _this3.hide();
  }, delay);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.prototype.handleDelayedShow"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.prototype.</span>handleDelayedShow ()](#apidoc.element.react-bootstrap.OverlayTrigger.prototype.handleDelayedShow)
- description and source-code
```javascript
function handleDelayedShow() {
  var _this2 = this;

  if (this._hoverHideDelay != null) {
    clearTimeout(this._hoverHideDelay);
    this._hoverHideDelay = null;
    return;
  }

  if (this.state.show || this._hoverShowDelay != null) {
    return;
  }

  var delay = this.props.delayShow != null ? this.props.delayShow : this.props.delay;

  if (!delay) {
    this.show();
    return;
  }

  this._hoverShowDelay = setTimeout(function () {
    _this2._hoverShowDelay = null;
    _this2.show();
  }, delay);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.prototype.handleHide"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.prototype.</span>handleHide ()](#apidoc.element.react-bootstrap.OverlayTrigger.prototype.handleHide)
- description and source-code
```javascript
function handleHide() {
  this.hide();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.prototype.handleMouseOverOut"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.prototype.</span>handleMouseOverOut (handler, e)](#apidoc.element.react-bootstrap.OverlayTrigger.prototype.handleMouseOverOut)
- description and source-code
```javascript
function handleMouseOverOut(handler, e) {
  var target = e.currentTarget;
  var related = e.relatedTarget || e.nativeEvent.toElement;

  if (!related || related !== target && !(0, _contains2['default'])(target, related)) {
    handler(e);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.prototype.handleToggle"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.prototype.</span>handleToggle ()](#apidoc.element.react-bootstrap.OverlayTrigger.prototype.handleToggle)
- description and source-code
```javascript
function handleToggle() {
  if (this.state.show) {
    this.hide();
  } else {
    this.show();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.prototype.hide"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.prototype.</span>hide ()](#apidoc.element.react-bootstrap.OverlayTrigger.prototype.hide)
- description and source-code
```javascript
function hide() {
  this.setState({ show: false });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.prototype.makeOverlay"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.prototype.</span>makeOverlay (overlay, props)](#apidoc.element.react-bootstrap.OverlayTrigger.prototype.makeOverlay)
- description and source-code
```javascript
function makeOverlay(overlay, props) {
  return _react2['default'].createElement(
    _Overlay2['default'],
    (0, _extends3['default'])({}, props, {
      show: this.state.show,
      onHide: this.handleHide,
      target: this
    }),
    overlay
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.prototype.</span>render ()](#apidoc.element.react-bootstrap.OverlayTrigger.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      trigger = _props.trigger,
      overlay = _props.overlay,
      children = _props.children,
      onBlur = _props.onBlur,
      onClick = _props.onClick,
      onFocus = _props.onFocus,
      onMouseOut = _props.onMouseOut,
      onMouseOver = _props.onMouseOver,
      props = (0, _objectWithoutProperties3['default'])(_props, ['trigger', 'overlay', 'children', 'onBlur', 'onClick', 'onFocus
', 'onMouseOut', 'onMouseOver']);


  delete props.delay;
  delete props.delayShow;
  delete props.delayHide;
  delete props.defaultOverlayShown;

  var child = _react2['default'].Children.only(children);
  var childProps = child.props;
  var triggerProps = {};

  if (this.state.show) {
    triggerProps['aria-describedby'] = overlay.props.id;
  }

  // FIXME: The logic here for passing through handlers on this component is
  // inconsistent. We shouldn't be passing any of these props through.

  triggerProps.onClick = (0, _createChainedFunction2['default'])(childProps.onClick, onClick);

  if (isOneOf('click', trigger)) {
    triggerProps.onClick = (0, _createChainedFunction2['default'])(triggerProps.onClick, this.handleToggle);
  }

  if (isOneOf('hover', trigger)) {
    process.env.NODE_ENV !== 'production' ? (0, _warning2['default'])(!(trigger === 'hover'), '[react-bootstrap] Specifying only
 the '"hover"' trigger limits the ' + 'visibility of the overlay to just mouse users. Consider also ' + 'including the '"focus"'
trigger so that touch and keyboard only ' + 'users can see the overlay as well.') : void 0;

    triggerProps.onMouseOver = (0, _createChainedFunction2['default'])(childProps.onMouseOver, onMouseOver, this.handleMouseOver
);
    triggerProps.onMouseOut = (0, _createChainedFunction2['default'])(childProps.onMouseOut, onMouseOut, this.handleMouseOut);
  }

  if (isOneOf('focus', trigger)) {
    triggerProps.onFocus = (0, _createChainedFunction2['default'])(childProps.onFocus, onFocus, this.handleDelayedShow);
    triggerProps.onBlur = (0, _createChainedFunction2['default'])(childProps.onBlur, onBlur, this.handleDelayedHide);
  }

  this._overlay = this.makeOverlay(overlay, props);

  return (0, _react.cloneElement)(child, triggerProps);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.prototype.renderOverlay"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.prototype.</span>renderOverlay ()](#apidoc.element.react-bootstrap.OverlayTrigger.prototype.renderOverlay)
- description and source-code
```javascript
function renderOverlay() {
  _reactDom2['default'].unstable_renderSubtreeIntoContainer(this, this._overlay, this._mountNode);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.OverlayTrigger.prototype.show"></a>[function <span class="apidocSignatureSpan">react-bootstrap.OverlayTrigger.prototype.</span>show ()](#apidoc.element.react-bootstrap.OverlayTrigger.prototype.show)
- description and source-code
```javascript
function show() {
  this.setState({ show: true });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.PageHeader"></a>[module react-bootstrap.PageHeader](#apidoc.module.react-bootstrap.PageHeader)

#### <a name="apidoc.element.react-bootstrap.PageHeader.PageHeader"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>PageHeader ()](#apidoc.element.react-bootstrap.PageHeader.PageHeader)
- description and source-code
```javascript
function PageHeader() {
  (0, _classCallCheck3['default'])(this, PageHeader);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.PageHeader.propTypes"></a>[module react-bootstrap.PageHeader.propTypes](#apidoc.module.react-bootstrap.PageHeader.propTypes)

#### <a name="apidoc.element.react-bootstrap.PageHeader.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.PageHeader.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.PageHeader.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.PageHeader.prototype"></a>[module react-bootstrap.PageHeader.prototype](#apidoc.module.react-bootstrap.PageHeader.prototype)

#### <a name="apidoc.element.react-bootstrap.PageHeader.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.PageHeader.prototype.</span>render ()](#apidoc.element.react-bootstrap.PageHeader.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      className = _props.className,
      children = _props.children,
      props = (0, _objectWithoutProperties3['default'])(_props, ['className', 'children']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _bootstrapUtils.getClassSet)(bsProps);

  return _react2['default'].createElement(
    'div',
    (0, _extends3['default'])({}, elementProps, {
      className: (0, _classnames2['default'])(className, classes)
    }),
    _react2['default'].createElement(
      'h1',
      null,
      children
    )
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.PageItem"></a>[module react-bootstrap.PageItem](#apidoc.module.react-bootstrap.PageItem)

#### <a name="apidoc.element.react-bootstrap.PageItem.PageItem"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>PageItem ()](#apidoc.element.react-bootstrap.PageItem.PageItem)
- description and source-code
```javascript
function DeprecatedComponent() {
  (0, _classCallCheck3['default'])(this, DeprecatedComponent);
  return (0, _possibleConstructorReturn3['default'])(this, _Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.PageItem.prototype"></a>[module react-bootstrap.PageItem.prototype](#apidoc.module.react-bootstrap.PageItem.prototype)

#### <a name="apidoc.element.react-bootstrap.PageItem.prototype.componentWillMount"></a>[function <span class="apidocSignatureSpan">react-bootstrap.PageItem.prototype.</span>componentWillMount ()](#apidoc.element.react-bootstrap.PageItem.prototype.componentWillMount)
- description and source-code
```javascript
function componentWillMount() {
  deprecationWarning.apply(undefined, args);

  if (_Component.prototype.componentWillMount) {
    var _Component$prototype$;

    for (var _len2 = arguments.length, methodArgs = Array(_len2), _key2 = 0; _key2 < _len2; _key2++) {
      methodArgs[_key2] = arguments[_key2];
    }

    (_Component$prototype$ = _Component.prototype.componentWillMount).call.apply(_Component$prototype$, [this].concat(methodArgs
));
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Pager"></a>[module react-bootstrap.Pager](#apidoc.module.react-bootstrap.Pager)

#### <a name="apidoc.element.react-bootstrap.Pager.Pager"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Pager ()](#apidoc.element.react-bootstrap.Pager.Pager)
- description and source-code
```javascript
function Pager() {
  (0, _classCallCheck3['default'])(this, Pager);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Pager.Item"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Pager.</span>Item (props, context)](#apidoc.element.react-bootstrap.Pager.Item)
- description and source-code
```javascript
function PagerItem(props, context) {
  (0, _classCallCheck3['default'])(this, PagerItem);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleSelect = _this.handleSelect.bind(_this);
  return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Pager.Item"></a>[module react-bootstrap.Pager.Item](#apidoc.module.react-bootstrap.Pager.Item)

#### <a name="apidoc.element.react-bootstrap.Pager.Item.Item"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Pager.</span>Item (props, context)](#apidoc.element.react-bootstrap.Pager.Item.Item)
- description and source-code
```javascript
function PagerItem(props, context) {
  (0, _classCallCheck3['default'])(this, PagerItem);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleSelect = _this.handleSelect.bind(_this);
  return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Pager.Item.prototype"></a>[module react-bootstrap.Pager.Item.prototype](#apidoc.module.react-bootstrap.Pager.Item.prototype)

#### <a name="apidoc.element.react-bootstrap.Pager.Item.prototype.handleSelect"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Pager.Item.prototype.</span>handleSelect (e)](#apidoc.element.react-bootstrap.Pager.Item.prototype.handleSelect)
- description and source-code
```javascript
function handleSelect(e) {
  var _props = this.props,
      disabled = _props.disabled,
      onSelect = _props.onSelect,
      eventKey = _props.eventKey;


  if (onSelect || disabled) {
    e.preventDefault();
  }

  if (disabled) {
    return;
  }

  if (onSelect) {
    onSelect(eventKey, e);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Pager.Item.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Pager.Item.prototype.</span>render ()](#apidoc.element.react-bootstrap.Pager.Item.prototype.render)
- description and source-code
```javascript
function render() {
  var _props2 = this.props,
      disabled = _props2.disabled,
      previous = _props2.previous,
      next = _props2.next,
      onClick = _props2.onClick,
      className = _props2.className,
      style = _props2.style,
      props = (0, _objectWithoutProperties3['default'])(_props2, ['disabled', 'previous', 'next', 'onClick', 'className', 'style
']);


  delete props.onSelect;
  delete props.eventKey;

  return _react2['default'].createElement(
    'li',
    {
      className: (0, _classnames2['default'])(className, { disabled: disabled, previous: previous, next: next }),
      style: style
    },
    _react2['default'].createElement(_SafeAnchor2['default'], (0, _extends3['default'])({}, props, {
      disabled: disabled,
      onClick: (0, _createChainedFunction2['default'])(onClick, this.handleSelect)
    }))
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Pager.propTypes"></a>[module react-bootstrap.Pager.propTypes](#apidoc.module.react-bootstrap.Pager.propTypes)

#### <a name="apidoc.element.react-bootstrap.Pager.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Pager.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Pager.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Pager.propTypes.onSelect"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Pager.propTypes.</span>onSelect ()](#apidoc.element.react-bootstrap.Pager.propTypes.onSelect)
- description and source-code
```javascript
onSelect = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Pager.prototype"></a>[module react-bootstrap.Pager.prototype](#apidoc.module.react-bootstrap.Pager.prototype)

#### <a name="apidoc.element.react-bootstrap.Pager.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Pager.prototype.</span>render ()](#apidoc.element.react-bootstrap.Pager.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      onSelect = _props.onSelect,
      className = _props.className,
      children = _props.children,
      props = (0, _objectWithoutProperties3['default'])(_props, ['onSelect', 'className', 'children']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _bootstrapUtils.getClassSet)(bsProps);

  return _react2['default'].createElement(
    'ul',
    (0, _extends3['default'])({}, elementProps, {
      className: (0, _classnames2['default'])(className, classes)
    }),
    _ValidComponentChildren2['default'].map(children, function (child) {
      return (0, _react.cloneElement)(child, {
        onSelect: (0, _createChainedFunction2['default'])(child.props.onSelect, onSelect)
      });
    })
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Pagination"></a>[module react-bootstrap.Pagination](#apidoc.module.react-bootstrap.Pagination)

#### <a name="apidoc.element.react-bootstrap.Pagination.Pagination"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Pagination ()](#apidoc.element.react-bootstrap.Pagination.Pagination)
- description and source-code
```javascript
function Pagination() {
  (0, _classCallCheck3['default'])(this, Pagination);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Pagination.propTypes"></a>[module react-bootstrap.Pagination.propTypes](#apidoc.module.react-bootstrap.Pagination.propTypes)

#### <a name="apidoc.element.react-bootstrap.Pagination.propTypes.activePage"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Pagination.propTypes.</span>activePage ()](#apidoc.element.react-bootstrap.Pagination.propTypes.activePage)
- description and source-code
```javascript
activePage = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Pagination.propTypes.boundaryLinks"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Pagination.propTypes.</span>boundaryLinks ()](#apidoc.element.react-bootstrap.Pagination.propTypes.boundaryLinks)
- description and source-code
```javascript
boundaryLinks = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Pagination.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Pagination.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Pagination.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Pagination.propTypes.buttonComponentClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Pagination.propTypes.</span>buttonComponentClass ()](#apidoc.element.react-bootstrap.Pagination.propTypes.buttonComponentClass)
- description and source-code
```javascript
buttonComponentClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Pagination.propTypes.ellipsis"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Pagination.propTypes.</span>ellipsis ()](#apidoc.element.react-bootstrap.Pagination.propTypes.ellipsis)
- description and source-code
```javascript
ellipsis = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Pagination.propTypes.first"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Pagination.propTypes.</span>first ()](#apidoc.element.react-bootstrap.Pagination.propTypes.first)
- description and source-code
```javascript
first = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Pagination.propTypes.items"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Pagination.propTypes.</span>items ()](#apidoc.element.react-bootstrap.Pagination.propTypes.items)
- description and source-code
```javascript
items = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Pagination.propTypes.last"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Pagination.propTypes.</span>last ()](#apidoc.element.react-bootstrap.Pagination.propTypes.last)
- description and source-code
```javascript
last = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Pagination.propTypes.maxButtons"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Pagination.propTypes.</span>maxButtons ()](#apidoc.element.react-bootstrap.Pagination.propTypes.maxButtons)
- description and source-code
```javascript
maxButtons = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Pagination.propTypes.next"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Pagination.propTypes.</span>next ()](#apidoc.element.react-bootstrap.Pagination.propTypes.next)
- description and source-code
```javascript
next = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Pagination.propTypes.onSelect"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Pagination.propTypes.</span>onSelect ()](#apidoc.element.react-bootstrap.Pagination.propTypes.onSelect)
- description and source-code
```javascript
onSelect = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Pagination.propTypes.prev"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Pagination.propTypes.</span>prev ()](#apidoc.element.react-bootstrap.Pagination.propTypes.prev)
- description and source-code
```javascript
prev = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Pagination.prototype"></a>[module react-bootstrap.Pagination.prototype](#apidoc.module.react-bootstrap.Pagination.prototype)

#### <a name="apidoc.element.react-bootstrap.Pagination.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Pagination.prototype.</span>render ()](#apidoc.element.react-bootstrap.Pagination.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      activePage = _props.activePage,
      items = _props.items,
      maxButtons = _props.maxButtons,
      boundaryLinks = _props.boundaryLinks,
      ellipsis = _props.ellipsis,
      first = _props.first,
      last = _props.last,
      prev = _props.prev,
      next = _props.next,
      onSelect = _props.onSelect,
      buttonComponentClass = _props.buttonComponentClass,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['activePage', 'items', 'maxButtons', 'boundaryLinks', 'ellipsis
', 'first', 'last', 'prev', 'next', 'onSelect', 'buttonComponentClass', 'className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _bootstrapUtils.getClassSet)(bsProps);

  var buttonProps = {
    onSelect: onSelect,
    componentClass: buttonComponentClass
  };

  return _react2['default'].createElement(
    'ul',
    (0, _extends3['default'])({}, elementProps, {
      className: (0, _classnames2['default'])(className, classes)
    }),
    first && _react2['default'].createElement(
      _PaginationButton2['default'],
      (0, _extends3['default'])({}, buttonProps, {
        eventKey: 1,
        disabled: activePage === 1
      }),
      _react2['default'].createElement(
        'span',
        { 'aria-label': 'First' },
        first === true ? '\xAB' : first
      )
    ),
    prev && _react2['default'].createElement(
      _PaginationButton2['default'],
      (0, _extends3['default'])({}, buttonProps, {
        eventKey: activePage - 1,
        disabled: activePage === 1
      }),
      _react2['default'].createElement(
        'span',
        { 'aria-label': 'Previous' },
        prev === true ? '\u2039' : prev
      )
    ),
    this.renderPageButtons(activePage, items, maxButtons, boundaryLinks, ellipsis, buttonProps),
    next && _react2['default'].createElement(
      _PaginationButton2['default'],
      (0, _extends3['default'])({}, buttonProps, {
        eventKey: activePage + 1,
        disabled: activePage >= items
      }),
      _react2['default'].createElement(
        'span',
        { 'aria-label': 'Next' },
        next === true ? '\u203A' : next
      )
    ),
    last && _react2['default'].createElement(
      _PaginationButton2['default'],
      (0, _extends3['default'])({}, buttonProps, {
        eventKey: items,
        disabled: activePage >= items
      }),
      _react2['default'].createElement(
        'span',
        { 'aria-label': 'Last' },
        last === true ? '\xBB' : last
      )
    )
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Pagination.prototype.renderPageButtons"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Pagination.prototype.</span>renderPageButtons (activePage, items, maxButtons, boundaryLinks, ellipsis, buttonProps)](#apidoc.element.react-bootstrap.Pagination.prototype.renderPageButtons)
- description and source-code
```javascript
function renderPageButtons(activePage, items, maxButtons, boundaryLinks, ellipsis, buttonProps) {
  var pageButtons = [];

  var startPage = void 0;
  var endPage = void 0;

  if (maxButtons && maxButtons < items) {
    startPage = Math.max(Math.min(activePage - Math.floor(maxButtons / 2, 10), items - maxButtons + 1), 1);
    endPage = startPage + maxButtons - 1;
  } else {
    startPage = 1;
    endPage = items;
  }

  for (var page = startPage; page <= endPage; ++page) {
    pageButtons.push(_react2['default'].createElement(
      _PaginationButton2['default'],
      (0, _extends3['default'])({}, buttonProps, {
        key: page,
        eventKey: page,
        active: page === activePage
      }),
      page
    ));
  }

  if (ellipsis && boundaryLinks && startPage > 1) {
    if (startPage > 2) {
      pageButtons.unshift(_react2['default'].createElement(
        _PaginationButton2['default'],
        {
          key: 'ellipsisFirst',
          disabled: true,
          componentClass: buttonProps.componentClass
        },
        _react2['default'].createElement(
          'span',
          { 'aria-label': 'More' },
          ellipsis === true ? '\u2026' : ellipsis
        )
      ));
    }

    pageButtons.unshift(_react2['default'].createElement(
      _PaginationButton2['default'],
      (0, _extends3['default'])({}, buttonProps, {
        key: 1,
        eventKey: 1,
        active: false
      }),
      '1'
    ));
  }

  if (ellipsis && endPage < items) {
    if (!boundaryLinks || endPage < items - 1) {
      pageButtons.push(_react2['default'].createElement(
        _PaginationButton2['default'],
        {
          key: 'ellipsis',
          disabled: true,
          componentClass: buttonProps.componentClass
        },
        _react2['default'].createElement(
          'span',
          { 'aria-label': 'More' },
          ellipsis === true ? '\u2026' : ellipsis
        )
      ));
    }

    if (boundaryLinks) {
      pageButtons.push(_react2['default'].createElement(
        _PaginationButton2['default'],
        (0, _extends3['default'])({}, buttonProps, {
          key: items,
          eventKey: items,
          active: false
        }),
        items
      ));
    }
  }

  return pageButtons;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.PaginationButton"></a>[module react-bootstrap.PaginationButton](#apidoc.module.react-bootstrap.PaginationButton)

#### <a name="apidoc.element.react-bootstrap.PaginationButton.PaginationButton"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>PaginationButton (props, context)](#apidoc.element.react-bootstrap.PaginationButton.PaginationButton)
- description and source-code
```javascript
function PaginationButton(props, context) {
  (0, _classCallCheck3['default'])(this, PaginationButton);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleClick = _this.handleClick.bind(_this);
  return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.PaginationButton.prototype"></a>[module react-bootstrap.PaginationButton.prototype](#apidoc.module.react-bootstrap.PaginationButton.prototype)

#### <a name="apidoc.element.react-bootstrap.PaginationButton.prototype.handleClick"></a>[function <span class="apidocSignatureSpan">react-bootstrap.PaginationButton.prototype.</span>handleClick (event)](#apidoc.element.react-bootstrap.PaginationButton.prototype.handleClick)
- description and source-code
```javascript
function handleClick(event) {
  var _props = this.props,
      disabled = _props.disabled,
      onSelect = _props.onSelect,
      eventKey = _props.eventKey;


  if (disabled) {
    return;
  }

  if (onSelect) {
    onSelect(eventKey, event);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.PaginationButton.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.PaginationButton.prototype.</span>render ()](#apidoc.element.react-bootstrap.PaginationButton.prototype.render)
- description and source-code
```javascript
function render() {
  var _props2 = this.props,
      Component = _props2.componentClass,
      active = _props2.active,
      disabled = _props2.disabled,
      onClick = _props2.onClick,
      className = _props2.className,
      style = _props2.style,
      props = (0, _objectWithoutProperties3['default'])(_props2, ['componentClass', 'active', 'disabled', 'onClick', 'className', '
style']);


  if (Component === _SafeAnchor2['default']) {
    // Assume that custom components want 'eventKey'.
    delete props.eventKey;
  }

  delete props.onSelect;

  return _react2['default'].createElement(
    'li',
    {
      className: (0, _classnames2['default'])(className, { active: active, disabled: disabled }),
      style: style
    },
    _react2['default'].createElement(Component, (0, _extends3['default'])({}, props, {
      disabled: disabled,
      onClick: (0, _createChainedFunction2['default'])(onClick, this.handleClick)
    }))
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Panel"></a>[module react-bootstrap.Panel](#apidoc.module.react-bootstrap.Panel)

#### <a name="apidoc.element.react-bootstrap.Panel.Panel"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Panel (props, context)](#apidoc.element.react-bootstrap.Panel.Panel)
- description and source-code
```javascript
function Panel(props, context) {
  (0, _classCallCheck3['default'])(this, Panel);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleClickTitle = _this.handleClickTitle.bind(_this);

  _this.state = {
    expanded: _this.props.defaultExpanded
  };
  return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Panel.propTypes"></a>[module react-bootstrap.Panel.propTypes](#apidoc.module.react-bootstrap.Panel.propTypes)

#### <a name="apidoc.element.react-bootstrap.Panel.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Panel.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Panel.propTypes.bsStyle"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>bsStyle ()](#apidoc.element.react-bootstrap.Panel.propTypes.bsStyle)
- description and source-code
```javascript
bsStyle = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Panel.propTypes.collapsible"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>collapsible ()](#apidoc.element.react-bootstrap.Panel.propTypes.collapsible)
- description and source-code
```javascript
collapsible = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Panel.propTypes.defaultExpanded"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>defaultExpanded ()](#apidoc.element.react-bootstrap.Panel.propTypes.defaultExpanded)
- description and source-code
```javascript
defaultExpanded = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Panel.propTypes.eventKey"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>eventKey ()](#apidoc.element.react-bootstrap.Panel.propTypes.eventKey)
- description and source-code
```javascript
eventKey = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Panel.propTypes.expanded"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>expanded ()](#apidoc.element.react-bootstrap.Panel.propTypes.expanded)
- description and source-code
```javascript
expanded = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Panel.propTypes.footer"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>footer ()](#apidoc.element.react-bootstrap.Panel.propTypes.footer)
- description and source-code
```javascript
footer = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Panel.propTypes.header"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>header ()](#apidoc.element.react-bootstrap.Panel.propTypes.header)
- description and source-code
```javascript
header = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Panel.propTypes.headerRole"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>headerRole ()](#apidoc.element.react-bootstrap.Panel.propTypes.headerRole)
- description and source-code
```javascript
headerRole = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Panel.propTypes.id"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>id ()](#apidoc.element.react-bootstrap.Panel.propTypes.id)
- description and source-code
```javascript
id = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Panel.propTypes.onEnter"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>onEnter ()](#apidoc.element.react-bootstrap.Panel.propTypes.onEnter)
- description and source-code
```javascript
onEnter = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Panel.propTypes.onEntered"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>onEntered ()](#apidoc.element.react-bootstrap.Panel.propTypes.onEntered)
- description and source-code
```javascript
onEntered = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Panel.propTypes.onEntering"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>onEntering ()](#apidoc.element.react-bootstrap.Panel.propTypes.onEntering)
- description and source-code
```javascript
onEntering = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Panel.propTypes.onExit"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>onExit ()](#apidoc.element.react-bootstrap.Panel.propTypes.onExit)
- description and source-code
```javascript
onExit = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Panel.propTypes.onExited"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>onExited ()](#apidoc.element.react-bootstrap.Panel.propTypes.onExited)
- description and source-code
```javascript
onExited = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Panel.propTypes.onExiting"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>onExiting ()](#apidoc.element.react-bootstrap.Panel.propTypes.onExiting)
- description and source-code
```javascript
onExiting = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Panel.propTypes.onSelect"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>onSelect ()](#apidoc.element.react-bootstrap.Panel.propTypes.onSelect)
- description and source-code
```javascript
onSelect = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Panel.propTypes.panelRole"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Panel.propTypes.</span>panelRole ()](#apidoc.element.react-bootstrap.Panel.propTypes.panelRole)
- description and source-code
```javascript
panelRole = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Panel.prototype"></a>[module react-bootstrap.Panel.prototype](#apidoc.module.react-bootstrap.Panel.prototype)

#### <a name="apidoc.element.react-bootstrap.Panel.prototype.handleClickTitle"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Panel.prototype.</span>handleClickTitle (e)](#apidoc.element.react-bootstrap.Panel.prototype.handleClickTitle)
- description and source-code
```javascript
function handleClickTitle(e) {
  // FIXME: What the heck? This API is horrible. This needs to go away!
  e.persist();
  e.selected = true;

  if (this.props.onSelect) {
    this.props.onSelect(this.props.eventKey, e);
  } else {
    e.preventDefault();
  }

  if (e.selected) {
    this.setState({ expanded: !this.state.expanded });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Panel.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Panel.prototype.</span>render ()](#apidoc.element.react-bootstrap.Panel.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      collapsible = _props.collapsible,
      header = _props.header,
      id = _props.id,
      footer = _props.footer,
      propsExpanded = _props.expanded,
      headerRole = _props.headerRole,
      panelRole = _props.panelRole,
      className = _props.className,
      children = _props.children,
      onEnter = _props.onEnter,
      onEntering = _props.onEntering,
      onEntered = _props.onEntered,
      onExit = _props.onExit,
      onExiting = _props.onExiting,
      onExited = _props.onExited,
      props = (0, _objectWithoutProperties3['default'])(_props, ['collapsible', 'header', 'id', 'footer', 'expanded', 'headerRole
', 'panelRole', 'className', 'children', 'onEnter', 'onEntering', 'onEntered', 'onExit', 'onExiting', 'onExited']);

  var _splitBsPropsAndOmit = (0, _bootstrapUtils.splitBsPropsAndOmit)(props, ['defaultExpanded', 'eventKey', 'onSelect']),
      bsProps = _splitBsPropsAndOmit[0],
      elementProps = _splitBsPropsAndOmit[1];

  var expanded = propsExpanded != null ? propsExpanded : this.state.expanded;

  var classes = (0, _bootstrapUtils.getClassSet)(bsProps);

  return _react2['default'].createElement(
    'div',
    (0, _extends3['default'])({}, elementProps, {
      className: (0, _classnames2['default'])(className, classes),
      id: collapsible ? null : id
    }),
    header && _react2['default'].createElement(
      'div',
      { className: (0, _bootstrapUtils.prefix)(bsProps, 'heading') },
      this.renderHeader(collapsible, header, id, headerRole, expanded, bsProps)
    ),
    collapsible ? this.renderCollapsibleBody(id, expanded, panelRole, children, bsProps, { onEnter: onEnter, onEntering: onEntering
, onEntered: onEntered, onExit: onExit, onExiting: onExiting, onExited: onExited }) : this.renderBody(children, bsProps),
    footer && _react2['default'].createElement(
      'div',
      { className: (0, _bootstrapUtils.prefix)(bsProps, 'footer') },
      footer
    )
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Panel.prototype.renderAnchor"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Panel.prototype.</span>renderAnchor (header, id, role, expanded)](#apidoc.element.react-bootstrap.Panel.prototype.renderAnchor)
- description and source-code
```javascript
function renderAnchor(header, id, role, expanded) {
  return _react2['default'].createElement(
    'a',
    {
      role: role,
      href: id && '#' + id,
      onClick: this.handleClickTitle,
      'aria-controls': id,
      'aria-expanded': expanded,
      'aria-selected': expanded,
      className: expanded ? null : 'collapsed'
    },
    header
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Panel.prototype.renderBody"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Panel.prototype.</span>renderBody (rawChildren, bsProps)](#apidoc.element.react-bootstrap.Panel.prototype.renderBody)
- description and source-code
```javascript
function renderBody(rawChildren, bsProps) {
  var children = [];
  var bodyChildren = [];

  var bodyClassName = (0, _bootstrapUtils.prefix)(bsProps, 'body');

  function maybeAddBody() {
    if (!bodyChildren.length) {
      return;
    }

    // Derive the key from the index here, since we need to make one up.
    children.push(_react2['default'].createElement(
      'div',
      { key: children.length, className: bodyClassName },
      bodyChildren
    ));

    bodyChildren = [];
  }

  // Convert to array so we can re-use keys.
  _react2['default'].Children.toArray(rawChildren).forEach(function (child) {
    if (_react2['default'].isValidElement(child) && child.props.fill) {
      maybeAddBody();

      // Remove the child's unknown 'fill' prop.
      children.push((0, _react.cloneElement)(child, { fill: undefined }));

      return;
    }

    bodyChildren.push(child);
  });

  maybeAddBody();

  return children;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Panel.prototype.renderCollapsibleBody"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Panel.prototype.</span>renderCollapsibleBody (id, expanded, role, children, bsProps, animationHooks)](#apidoc.element.react-bootstrap.Panel.prototype.renderCollapsibleBody)
- description and source-code
```javascript
function renderCollapsibleBody(id, expanded, role, children, bsProps, animationHooks) {
  return _react2['default'].createElement(
    _Collapse2['default'],
    (0, _extends3['default'])({ 'in': expanded }, animationHooks),
    _react2['default'].createElement(
      'div',
      {
        id: id,
        role: role,
        className: (0, _bootstrapUtils.prefix)(bsProps, 'collapse'),
        'aria-hidden': !expanded
      },
      this.renderBody(children, bsProps)
    )
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Panel.prototype.renderHeader"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Panel.prototype.</span>renderHeader (collapsible, header, id, role, expanded, bsProps)](#apidoc.element.react-bootstrap.Panel.prototype.renderHeader)
- description and source-code
```javascript
function renderHeader(collapsible, header, id, role, expanded, bsProps) {
  var titleClassName = (0, _bootstrapUtils.prefix)(bsProps, 'title');

  if (!collapsible) {
    if (!_react2['default'].isValidElement(header)) {
      return header;
    }

    return (0, _react.cloneElement)(header, {
      className: (0, _classnames2['default'])(header.props.className, titleClassName)
    });
  }

  if (!_react2['default'].isValidElement(header)) {
    return _react2['default'].createElement(
      'h4',
      { role: 'presentation', className: titleClassName },
      this.renderAnchor(header, id, role, expanded)
    );
  }

  return (0, _react.cloneElement)(header, {
    className: (0, _classnames2['default'])(header.props.className, titleClassName),
    children: this.renderAnchor(header.props.children, id, role, expanded)
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.PanelGroup"></a>[module react-bootstrap.PanelGroup](#apidoc.module.react-bootstrap.PanelGroup)

#### <a name="apidoc.element.react-bootstrap.PanelGroup.PanelGroup"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>PanelGroup (props, context)](#apidoc.element.react-bootstrap.PanelGroup.PanelGroup)
- description and source-code
```javascript
function PanelGroup(props, context) {
  (0, _classCallCheck3['default'])(this, PanelGroup);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleSelect = _this.handleSelect.bind(_this);

  _this.state = {
    activeKey: props.defaultActiveKey
  };
  return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.PanelGroup.propTypes"></a>[module react-bootstrap.PanelGroup.propTypes](#apidoc.module.react-bootstrap.PanelGroup.propTypes)

#### <a name="apidoc.element.react-bootstrap.PanelGroup.propTypes.accordion"></a>[function <span class="apidocSignatureSpan">react-bootstrap.PanelGroup.propTypes.</span>accordion ()](#apidoc.element.react-bootstrap.PanelGroup.propTypes.accordion)
- description and source-code
```javascript
accordion = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.PanelGroup.propTypes.activeKey"></a>[function <span class="apidocSignatureSpan">react-bootstrap.PanelGroup.propTypes.</span>activeKey ()](#apidoc.element.react-bootstrap.PanelGroup.propTypes.activeKey)
- description and source-code
```javascript
activeKey = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.PanelGroup.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.PanelGroup.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.PanelGroup.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.PanelGroup.propTypes.defaultActiveKey"></a>[function <span class="apidocSignatureSpan">react-bootstrap.PanelGroup.propTypes.</span>defaultActiveKey ()](#apidoc.element.react-bootstrap.PanelGroup.propTypes.defaultActiveKey)
- description and source-code
```javascript
defaultActiveKey = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.PanelGroup.propTypes.onSelect"></a>[function <span class="apidocSignatureSpan">react-bootstrap.PanelGroup.propTypes.</span>onSelect ()](#apidoc.element.react-bootstrap.PanelGroup.propTypes.onSelect)
- description and source-code
```javascript
onSelect = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.PanelGroup.propTypes.role"></a>[function <span class="apidocSignatureSpan">react-bootstrap.PanelGroup.propTypes.</span>role ()](#apidoc.element.react-bootstrap.PanelGroup.propTypes.role)
- description and source-code
```javascript
role = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.PanelGroup.prototype"></a>[module react-bootstrap.PanelGroup.prototype](#apidoc.module.react-bootstrap.PanelGroup.prototype)

#### <a name="apidoc.element.react-bootstrap.PanelGroup.prototype.handleSelect"></a>[function <span class="apidocSignatureSpan">react-bootstrap.PanelGroup.prototype.</span>handleSelect (key, e)](#apidoc.element.react-bootstrap.PanelGroup.prototype.handleSelect)
- description and source-code
```javascript
function handleSelect(key, e) {
  e.preventDefault();

  if (this.props.onSelect) {
    this.props.onSelect(key, e);
  }

  if (this.state.activeKey === key) {
    key = null;
  }

  this.setState({ activeKey: key });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.PanelGroup.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.PanelGroup.prototype.</span>render ()](#apidoc.element.react-bootstrap.PanelGroup.prototype.render)
- description and source-code
```javascript
function render() {
  var _this2 = this;

  var _props = this.props,
      accordion = _props.accordion,
      propsActiveKey = _props.activeKey,
      className = _props.className,
      children = _props.children,
      props = (0, _objectWithoutProperties3['default'])(_props, ['accordion', 'activeKey', 'className', 'children']);

  var _splitBsPropsAndOmit = (0, _bootstrapUtils.splitBsPropsAndOmit)(props, ['defaultActiveKey', 'onSelect']),
      bsProps = _splitBsPropsAndOmit[0],
      elementProps = _splitBsPropsAndOmit[1];

  var activeKey = void 0;
  if (accordion) {
    activeKey = propsActiveKey != null ? propsActiveKey : this.state.activeKey;
    elementProps.role = elementProps.role || 'tablist';
  }

  var classes = (0, _bootstrapUtils.getClassSet)(bsProps);

  return _react2['default'].createElement(
    'div',
    (0, _extends3['default'])({}, elementProps, {
      className: (0, _classnames2['default'])(className, classes)
    }),
    _ValidComponentChildren2['default'].map(children, function (child) {
      var childProps = {
        bsStyle: child.props.bsStyle || bsProps.bsStyle
      };

      if (accordion) {
        (0, _assign2['default'])(childProps, {
          headerRole: 'tab',
          panelRole: 'tabpanel',
          collapsible: true,
          expanded: child.props.eventKey === activeKey,
          onSelect: (0, _createChainedFunction2['default'])(_this2.handleSelect, child.props.onSelect)
        });
      }

      return (0, _react.cloneElement)(child, childProps);
    })
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Popover"></a>[module react-bootstrap.Popover](#apidoc.module.react-bootstrap.Popover)

#### <a name="apidoc.element.react-bootstrap.Popover.Popover"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Popover ()](#apidoc.element.react-bootstrap.Popover.Popover)
- description and source-code
```javascript
function Popover() {
  (0, _classCallCheck3['default'])(this, Popover);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Popover.propTypes"></a>[module react-bootstrap.Popover.propTypes](#apidoc.module.react-bootstrap.Popover.propTypes)

#### <a name="apidoc.element.react-bootstrap.Popover.propTypes.arrowOffsetLeft"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Popover.propTypes.</span>arrowOffsetLeft ()](#apidoc.element.react-bootstrap.Popover.propTypes.arrowOffsetLeft)
- description and source-code
```javascript
arrowOffsetLeft = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Popover.propTypes.arrowOffsetTop"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Popover.propTypes.</span>arrowOffsetTop ()](#apidoc.element.react-bootstrap.Popover.propTypes.arrowOffsetTop)
- description and source-code
```javascript
arrowOffsetTop = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Popover.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Popover.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Popover.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Popover.propTypes.id"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Popover.propTypes.</span>id (props, propName, componentName, location, propFullName)](#apidoc.element.react-bootstrap.Popover.propTypes.id)
- description and source-code
```javascript
function validate(props, propName, componentName, location, propFullName) {
  var componentNameSafe = componentName || '<<anonymous>>';
  var propFullNameSafe = propFullName || propName;

  if (props[propName] == null) {
    return new Error('The ' + location + ' '' + propFullNameSafe + '' is required to make ' + (''' + componentNameSafe + '' accessible
 for users of assistive ') + 'technologies such as screen readers.');
  }

  for (var _len = arguments.length, args = Array(_len > 5 ? _len - 5 : 0), _key = 5; _key < _len; _key++) {
    args[_key - 5] = arguments[_key];
  }

  return validator.apply(undefined, [props, propName, componentName, location, propFullName].concat(args));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Popover.propTypes.placement"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Popover.propTypes.</span>placement ()](#apidoc.element.react-bootstrap.Popover.propTypes.placement)
- description and source-code
```javascript
placement = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Popover.propTypes.positionLeft"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Popover.propTypes.</span>positionLeft ()](#apidoc.element.react-bootstrap.Popover.propTypes.positionLeft)
- description and source-code
```javascript
positionLeft = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Popover.propTypes.positionTop"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Popover.propTypes.</span>positionTop ()](#apidoc.element.react-bootstrap.Popover.propTypes.positionTop)
- description and source-code
```javascript
positionTop = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Popover.propTypes.title"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Popover.propTypes.</span>title ()](#apidoc.element.react-bootstrap.Popover.propTypes.title)
- description and source-code
```javascript
title = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Popover.prototype"></a>[module react-bootstrap.Popover.prototype](#apidoc.module.react-bootstrap.Popover.prototype)

#### <a name="apidoc.element.react-bootstrap.Popover.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Popover.prototype.</span>render ()](#apidoc.element.react-bootstrap.Popover.prototype.render)
- description and source-code
```javascript
function render() {
  var _extends2;

  var _props = this.props,
      placement = _props.placement,
      positionTop = _props.positionTop,
      positionLeft = _props.positionLeft,
      arrowOffsetTop = _props.arrowOffsetTop,
      arrowOffsetLeft = _props.arrowOffsetLeft,
      title = _props.title,
      className = _props.className,
      style = _props.style,
      children = _props.children,
      props = (0, _objectWithoutProperties3['default'])(_props, ['placement', 'positionTop', 'positionLeft', 'arrowOffsetTop', '
arrowOffsetLeft', 'title', 'className', 'style', 'children']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _extends4['default'])({}, (0, _bootstrapUtils.getClassSet)(bsProps), (_extends2 = {}, _extends2[placement] =
true, _extends2));

  var outerStyle = (0, _extends4['default'])({
    display: 'block',
    top: positionTop,
    left: positionLeft
  }, style);

  var arrowStyle = {
    top: arrowOffsetTop,
    left: arrowOffsetLeft
  };

  return _react2['default'].createElement(
    'div',
    (0, _extends4['default'])({}, elementProps, {
      role: 'tooltip',
      className: (0, _classnames2['default'])(className, classes),
      style: outerStyle
    }),
    _react2['default'].createElement('div', { className: 'arrow', style: arrowStyle }),
    title && _react2['default'].createElement(
      'h3',
      { className: (0, _bootstrapUtils.prefix)(bsProps, 'title') },
      title
    ),
    _react2['default'].createElement(
      'div',
      { className: (0, _bootstrapUtils.prefix)(bsProps, 'content') },
      children
    )
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ProgressBar"></a>[module react-bootstrap.ProgressBar](#apidoc.module.react-bootstrap.ProgressBar)

#### <a name="apidoc.element.react-bootstrap.ProgressBar.ProgressBar"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>ProgressBar ()](#apidoc.element.react-bootstrap.ProgressBar.ProgressBar)
- description and source-code
```javascript
function ProgressBar() {
  (0, _classCallCheck3['default'])(this, ProgressBar);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ProgressBar.propTypes"></a>[module react-bootstrap.ProgressBar.propTypes](#apidoc.module.react-bootstrap.ProgressBar.propTypes)

#### <a name="apidoc.element.react-bootstrap.ProgressBar.propTypes.active"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ProgressBar.propTypes.</span>active ()](#apidoc.element.react-bootstrap.ProgressBar.propTypes.active)
- description and source-code
```javascript
active = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ProgressBar.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ProgressBar.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.ProgressBar.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ProgressBar.propTypes.bsStyle"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ProgressBar.propTypes.</span>bsStyle ()](#apidoc.element.react-bootstrap.ProgressBar.propTypes.bsStyle)
- description and source-code
```javascript
bsStyle = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ProgressBar.propTypes.children"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ProgressBar.propTypes.</span>children (props, propName, componentName)](#apidoc.element.react-bootstrap.ProgressBar.propTypes.children)
- description and source-code
```javascript
function onlyProgressBar(props, propName, componentName) {
  var children = props[propName];
  if (!children) {
    return null;
  }

  var error = null;

  _react2['default'].Children.forEach(children, function (child) {
    if (error) {
      return;
    }

    if (child.type === ProgressBar) {
      // eslint-disable-line no-use-before-define
      return;
    }

    var childIdentifier = _react2['default'].isValidElement(child) ? child.type.displayName || child.type.name || child.type : child
;
    error = new Error('Children of ' + componentName + ' can contain only ProgressBar ' + ('components. Found ' + childIdentifier
 + '.'));
  });

  return error;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ProgressBar.propTypes.isChild"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ProgressBar.propTypes.</span>isChild ()](#apidoc.element.react-bootstrap.ProgressBar.propTypes.isChild)
- description and source-code
```javascript
isChild = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ProgressBar.propTypes.label"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ProgressBar.propTypes.</span>label ()](#apidoc.element.react-bootstrap.ProgressBar.propTypes.label)
- description and source-code
```javascript
label = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ProgressBar.propTypes.max"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ProgressBar.propTypes.</span>max ()](#apidoc.element.react-bootstrap.ProgressBar.propTypes.max)
- description and source-code
```javascript
max = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ProgressBar.propTypes.min"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ProgressBar.propTypes.</span>min ()](#apidoc.element.react-bootstrap.ProgressBar.propTypes.min)
- description and source-code
```javascript
min = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ProgressBar.propTypes.now"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ProgressBar.propTypes.</span>now ()](#apidoc.element.react-bootstrap.ProgressBar.propTypes.now)
- description and source-code
```javascript
now = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ProgressBar.propTypes.srOnly"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ProgressBar.propTypes.</span>srOnly ()](#apidoc.element.react-bootstrap.ProgressBar.propTypes.srOnly)
- description and source-code
```javascript
srOnly = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ProgressBar.propTypes.striped"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ProgressBar.propTypes.</span>striped ()](#apidoc.element.react-bootstrap.ProgressBar.propTypes.striped)
- description and source-code
```javascript
striped = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ProgressBar.prototype"></a>[module react-bootstrap.ProgressBar.prototype](#apidoc.module.react-bootstrap.ProgressBar.prototype)

#### <a name="apidoc.element.react-bootstrap.ProgressBar.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ProgressBar.prototype.</span>render ()](#apidoc.element.react-bootstrap.ProgressBar.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      isChild = _props.isChild,
      props = (0, _objectWithoutProperties3['default'])(_props, ['isChild']);


  if (isChild) {
    return this.renderProgressBar(props);
  }

  var min = props.min,
      now = props.now,
      max = props.max,
      label = props.label,
      srOnly = props.srOnly,
      striped = props.striped,
      active = props.active,
      bsClass = props.bsClass,
      bsStyle = props.bsStyle,
      className = props.className,
      children = props.children,
      wrapperProps = (0, _objectWithoutProperties3['default'])(props, ['min', 'now', 'max', 'label', 'srOnly', 'striped', 'active
', 'bsClass', 'bsStyle', 'className', 'children']);


  return _react2['default'].createElement(
    'div',
    (0, _extends4['default'])({}, wrapperProps, {
      className: (0, _classnames2['default'])(className, 'progress')
    }),
    children ? _ValidComponentChildren2['default'].map(children, function (child) {
      return (0, _react.cloneElement)(child, { isChild: true });
    }) : this.renderProgressBar({
      min: min, now: now, max: max, label: label, srOnly: srOnly, striped: striped, active: active, bsClass: bsClass, bsStyle: bsStyle
    })
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ProgressBar.prototype.renderProgressBar"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ProgressBar.prototype.</span>renderProgressBar (_ref)](#apidoc.element.react-bootstrap.ProgressBar.prototype.renderProgressBar)
- description and source-code
```javascript
function renderProgressBar(_ref) {
  var _extends2;

  var min = _ref.min,
      now = _ref.now,
      max = _ref.max,
      label = _ref.label,
      srOnly = _ref.srOnly,
      striped = _ref.striped,
      active = _ref.active,
      className = _ref.className,
      style = _ref.style,
      props = (0, _objectWithoutProperties3['default'])(_ref, ['min', 'now', 'max', 'label', 'srOnly', 'striped', 'active', 'className
', 'style']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _extends4['default'])({}, (0, _bootstrapUtils.getClassSet)(bsProps), (_extends2 = {
    active: active
  }, _extends2[(0, _bootstrapUtils.prefix)(bsProps, 'striped')] = active || striped, _extends2));

  return _react2['default'].createElement(
    'div',
    (0, _extends4['default'])({}, elementProps, {
      role: 'progressbar',
      className: (0, _classnames2['default'])(className, classes),
      style: (0, _extends4['default'])({ width: getPercentage(now, min, max) + '%' }, style),
      'aria-valuenow': now,
      'aria-valuemin': min,
      'aria-valuemax': max
    }),
    srOnly ? _react2['default'].createElement(
      'span',
      { className: 'sr-only' },
      label
    ) : label
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Radio"></a>[module react-bootstrap.Radio](#apidoc.module.react-bootstrap.Radio)

#### <a name="apidoc.element.react-bootstrap.Radio.Radio"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Radio ()](#apidoc.element.react-bootstrap.Radio.Radio)
- description and source-code
```javascript
function Radio() {
  (0, _classCallCheck3['default'])(this, Radio);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Radio.propTypes"></a>[module react-bootstrap.Radio.propTypes](#apidoc.module.react-bootstrap.Radio.propTypes)

#### <a name="apidoc.element.react-bootstrap.Radio.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Radio.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Radio.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Radio.propTypes.disabled"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Radio.propTypes.</span>disabled ()](#apidoc.element.react-bootstrap.Radio.propTypes.disabled)
- description and source-code
```javascript
disabled = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Radio.propTypes.inline"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Radio.propTypes.</span>inline ()](#apidoc.element.react-bootstrap.Radio.propTypes.inline)
- description and source-code
```javascript
inline = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Radio.propTypes.inputRef"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Radio.propTypes.</span>inputRef ()](#apidoc.element.react-bootstrap.Radio.propTypes.inputRef)
- description and source-code
```javascript
inputRef = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Radio.propTypes.validationState"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Radio.propTypes.</span>validationState ()](#apidoc.element.react-bootstrap.Radio.propTypes.validationState)
- description and source-code
```javascript
validationState = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Radio.prototype"></a>[module react-bootstrap.Radio.prototype](#apidoc.module.react-bootstrap.Radio.prototype)

#### <a name="apidoc.element.react-bootstrap.Radio.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Radio.prototype.</span>render ()](#apidoc.element.react-bootstrap.Radio.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      inline = _props.inline,
      disabled = _props.disabled,
      validationState = _props.validationState,
      inputRef = _props.inputRef,
      className = _props.className,
      style = _props.style,
      children = _props.children,
      props = (0, _objectWithoutProperties3['default'])(_props, ['inline', 'disabled', 'validationState', 'inputRef', 'className
', 'style', 'children']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var input = _react2['default'].createElement('input', (0, _extends3['default'])({}, elementProps, {
    ref: inputRef,
    type: 'radio',
    disabled: disabled
  }));

  if (inline) {
    var _classes2;

    var _classes = (_classes2 = {}, _classes2[(0, _bootstrapUtils.prefix)(bsProps, 'inline')] = true, _classes2.disabled = disabled
, _classes2);

    // Use a warning here instead of in propTypes to get better-looking
    // generated documentation.
    process.env.NODE_ENV !== 'production' ? (0, _warning2['default'])(!validationState, ''validationState' is ignored on '<Radio
 inline>'. To display ' + 'validation state on an inline radio, set 'validationState' on a ' + 'parent '<FormGroup>' or other element
 instead.') : void 0;

    return _react2['default'].createElement(
      'label',
      { className: (0, _classnames2['default'])(className, _classes), style: style },
      input,
      children
    );
  }

  var classes = (0, _extends3['default'])({}, (0, _bootstrapUtils.getClassSet)(bsProps), {
    disabled: disabled
  });
  if (validationState) {
    classes['has-' + validationState] = true;
  }

  return _react2['default'].createElement(
    'div',
    { className: (0, _classnames2['default'])(className, classes), style: style },
    _react2['default'].createElement(
      'label',
      null,
      input,
      children
    )
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ResponsiveEmbed"></a>[module react-bootstrap.ResponsiveEmbed](#apidoc.module.react-bootstrap.ResponsiveEmbed)

#### <a name="apidoc.element.react-bootstrap.ResponsiveEmbed.ResponsiveEmbed"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>ResponsiveEmbed ()](#apidoc.element.react-bootstrap.ResponsiveEmbed.ResponsiveEmbed)
- description and source-code
```javascript
function ResponsiveEmbed() {
  (0, _classCallCheck3['default'])(this, ResponsiveEmbed);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ResponsiveEmbed.propTypes"></a>[module react-bootstrap.ResponsiveEmbed.propTypes](#apidoc.module.react-bootstrap.ResponsiveEmbed.propTypes)

#### <a name="apidoc.element.react-bootstrap.ResponsiveEmbed.propTypes.a16by9"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ResponsiveEmbed.propTypes.</span>a16by9 ()](#apidoc.element.react-bootstrap.ResponsiveEmbed.propTypes.a16by9)
- description and source-code
```javascript
a16by9 = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ResponsiveEmbed.propTypes.a4by3"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ResponsiveEmbed.propTypes.</span>a4by3 ()](#apidoc.element.react-bootstrap.ResponsiveEmbed.propTypes.a4by3)
- description and source-code
```javascript
a4by3 = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ResponsiveEmbed.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ResponsiveEmbed.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.ResponsiveEmbed.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.ResponsiveEmbed.propTypes.children"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ResponsiveEmbed.propTypes.</span>children ()](#apidoc.element.react-bootstrap.ResponsiveEmbed.propTypes.children)
- description and source-code
```javascript
children = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.ResponsiveEmbed.prototype"></a>[module react-bootstrap.ResponsiveEmbed.prototype](#apidoc.module.react-bootstrap.ResponsiveEmbed.prototype)

#### <a name="apidoc.element.react-bootstrap.ResponsiveEmbed.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.ResponsiveEmbed.prototype.</span>render ()](#apidoc.element.react-bootstrap.ResponsiveEmbed.prototype.render)
- description and source-code
```javascript
function render() {
  var _extends2;

  var _props = this.props,
      a16by9 = _props.a16by9,
      a4by3 = _props.a4by3,
      className = _props.className,
      children = _props.children,
      props = (0, _objectWithoutProperties3['default'])(_props, ['a16by9', 'a4by3', 'className', 'children']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  process.env.NODE_ENV !== 'production' ? (0, _warning2['default'])(a16by9 || a4by3, 'Either 'a16by9' or 'a4by3' must be set.') :
void 0;
  process.env.NODE_ENV !== 'production' ? (0, _warning2['default'])(!(a16by9 && a4by3), 'Only one of 'a16by9' or 'a4by3' can be
set.') : void 0;

  var classes = (0, _extends4['default'])({}, (0, _bootstrapUtils.getClassSet)(bsProps), (_extends2 = {}, _extends2[(0, _bootstrapUtils
.prefix)(bsProps, '16by9')] = a16by9, _extends2[(0, _bootstrapUtils.prefix)(bsProps, '4by3')] = a4by3, _extends2));

  return _react2['default'].createElement(
    'div',
    { className: (0, _classnames2['default'])(classes) },
    (0, _react.cloneElement)(children, (0, _extends4['default'])({}, elementProps, {
      className: (0, _classnames2['default'])(className, (0, _bootstrapUtils.prefix)(bsProps, 'item'))
    }))
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Row"></a>[module react-bootstrap.Row](#apidoc.module.react-bootstrap.Row)

#### <a name="apidoc.element.react-bootstrap.Row.Row"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Row ()](#apidoc.element.react-bootstrap.Row.Row)
- description and source-code
```javascript
function Row() {
  (0, _classCallCheck3['default'])(this, Row);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Row.propTypes"></a>[module react-bootstrap.Row.propTypes](#apidoc.module.react-bootstrap.Row.propTypes)

#### <a name="apidoc.element.react-bootstrap.Row.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Row.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Row.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Row.propTypes.componentClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Row.propTypes.</span>componentClass ()](#apidoc.element.react-bootstrap.Row.propTypes.componentClass)
- description and source-code
```javascript
componentClass = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Row.prototype"></a>[module react-bootstrap.Row.prototype](#apidoc.module.react-bootstrap.Row.prototype)

#### <a name="apidoc.element.react-bootstrap.Row.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Row.prototype.</span>render ()](#apidoc.element.react-bootstrap.Row.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      Component = _props.componentClass,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['componentClass', 'className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _bootstrapUtils.getClassSet)(bsProps);

  return _react2['default'].createElement(Component, (0, _extends3['default'])({}, elementProps, {
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.SafeAnchor"></a>[module react-bootstrap.SafeAnchor](#apidoc.module.react-bootstrap.SafeAnchor)

#### <a name="apidoc.element.react-bootstrap.SafeAnchor.SafeAnchor"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>SafeAnchor (props, context)](#apidoc.element.react-bootstrap.SafeAnchor.SafeAnchor)
- description and source-code
```javascript
function SafeAnchor(props, context) {
  (0, _classCallCheck3['default'])(this, SafeAnchor);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleClick = _this.handleClick.bind(_this);
  return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.SafeAnchor.propTypes"></a>[module react-bootstrap.SafeAnchor.propTypes](#apidoc.module.react-bootstrap.SafeAnchor.propTypes)

#### <a name="apidoc.element.react-bootstrap.SafeAnchor.propTypes.componentClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.SafeAnchor.propTypes.</span>componentClass ()](#apidoc.element.react-bootstrap.SafeAnchor.propTypes.componentClass)
- description and source-code
```javascript
componentClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.SafeAnchor.propTypes.disabled"></a>[function <span class="apidocSignatureSpan">react-bootstrap.SafeAnchor.propTypes.</span>disabled ()](#apidoc.element.react-bootstrap.SafeAnchor.propTypes.disabled)
- description and source-code
```javascript
disabled = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.SafeAnchor.propTypes.href"></a>[function <span class="apidocSignatureSpan">react-bootstrap.SafeAnchor.propTypes.</span>href ()](#apidoc.element.react-bootstrap.SafeAnchor.propTypes.href)
- description and source-code
```javascript
href = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.SafeAnchor.propTypes.onClick"></a>[function <span class="apidocSignatureSpan">react-bootstrap.SafeAnchor.propTypes.</span>onClick ()](#apidoc.element.react-bootstrap.SafeAnchor.propTypes.onClick)
- description and source-code
```javascript
onClick = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.SafeAnchor.propTypes.role"></a>[function <span class="apidocSignatureSpan">react-bootstrap.SafeAnchor.propTypes.</span>role ()](#apidoc.element.react-bootstrap.SafeAnchor.propTypes.role)
- description and source-code
```javascript
role = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.SafeAnchor.propTypes.tabIndex"></a>[function <span class="apidocSignatureSpan">react-bootstrap.SafeAnchor.propTypes.</span>tabIndex ()](#apidoc.element.react-bootstrap.SafeAnchor.propTypes.tabIndex)
- description and source-code
```javascript
tabIndex = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.SafeAnchor.prototype"></a>[module react-bootstrap.SafeAnchor.prototype](#apidoc.module.react-bootstrap.SafeAnchor.prototype)

#### <a name="apidoc.element.react-bootstrap.SafeAnchor.prototype.handleClick"></a>[function <span class="apidocSignatureSpan">react-bootstrap.SafeAnchor.prototype.</span>handleClick (event)](#apidoc.element.react-bootstrap.SafeAnchor.prototype.handleClick)
- description and source-code
```javascript
function handleClick(event) {
  var _props = this.props,
      disabled = _props.disabled,
      href = _props.href,
      onClick = _props.onClick;


  if (disabled || isTrivialHref(href)) {
    event.preventDefault();
  }

  if (disabled) {
    event.stopPropagation();
    return;
  }

  if (onClick) {
    onClick(event);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.SafeAnchor.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.SafeAnchor.prototype.</span>render ()](#apidoc.element.react-bootstrap.SafeAnchor.prototype.render)
- description and source-code
```javascript
function render() {
  var _props2 = this.props,
      Component = _props2.componentClass,
      disabled = _props2.disabled,
      props = (0, _objectWithoutProperties3['default'])(_props2, ['componentClass', 'disabled']);


  if (isTrivialHref(props.href)) {
    props.role = props.role || 'button';
    // we want to make sure there is a href attribute on the node
    // otherwise, the cursor incorrectly styled (except with role='button')
    props.href = props.href || '#';
  }

  if (disabled) {
    props.tabIndex = -1;
    props.style = (0, _extends3['default'])({ pointerEvents: 'none' }, props.style);
  }

  return _react2['default'].createElement(Component, (0, _extends3['default'])({}, props, {
    onClick: this.handleClick
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.SplitButton"></a>[module react-bootstrap.SplitButton](#apidoc.module.react-bootstrap.SplitButton)

#### <a name="apidoc.element.react-bootstrap.SplitButton.SplitButton"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>SplitButton ()](#apidoc.element.react-bootstrap.SplitButton.SplitButton)
- description and source-code
```javascript
function SplitButton() {
  (0, _classCallCheck3['default'])(this, SplitButton);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.SplitButton.Toggle"></a>[function <span class="apidocSignatureSpan">react-bootstrap.SplitButton.</span>Toggle ()](#apidoc.element.react-bootstrap.SplitButton.Toggle)
- description and source-code
```javascript
function SplitToggle() {
  (0, _classCallCheck3['default'])(this, SplitToggle);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.SplitButton.Toggle"></a>[module react-bootstrap.SplitButton.Toggle](#apidoc.module.react-bootstrap.SplitButton.Toggle)

#### <a name="apidoc.element.react-bootstrap.SplitButton.Toggle.Toggle"></a>[function <span class="apidocSignatureSpan">react-bootstrap.SplitButton.</span>Toggle ()](#apidoc.element.react-bootstrap.SplitButton.Toggle.Toggle)
- description and source-code
```javascript
function SplitToggle() {
  (0, _classCallCheck3['default'])(this, SplitToggle);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.SplitButton.Toggle.prototype"></a>[module react-bootstrap.SplitButton.Toggle.prototype](#apidoc.module.react-bootstrap.SplitButton.Toggle.prototype)

#### <a name="apidoc.element.react-bootstrap.SplitButton.Toggle.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.SplitButton.Toggle.prototype.</span>render ()](#apidoc.element.react-bootstrap.SplitButton.Toggle.prototype.render)
- description and source-code
```javascript
function render() {
  return _react2['default'].createElement(_DropdownToggle2['default'], (0, _extends3['default'])({}, this.props, {
    useAnchor: false,
    noCaret: false
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.SplitButton.propTypes"></a>[module react-bootstrap.SplitButton.propTypes](#apidoc.module.react-bootstrap.SplitButton.propTypes)

#### <a name="apidoc.element.react-bootstrap.SplitButton.propTypes.bsSize"></a>[function <span class="apidocSignatureSpan">react-bootstrap.SplitButton.propTypes.</span>bsSize ()](#apidoc.element.react-bootstrap.SplitButton.propTypes.bsSize)
- description and source-code
```javascript
bsSize = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.SplitButton.propTypes.bsStyle"></a>[function <span class="apidocSignatureSpan">react-bootstrap.SplitButton.propTypes.</span>bsStyle ()](#apidoc.element.react-bootstrap.SplitButton.propTypes.bsStyle)
- description and source-code
```javascript
bsStyle = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.SplitButton.propTypes.children"></a>[function <span class="apidocSignatureSpan">react-bootstrap.SplitButton.propTypes.</span>children ()](#apidoc.element.react-bootstrap.SplitButton.propTypes.children)
- description and source-code
```javascript
children = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.SplitButton.propTypes.href"></a>[function <span class="apidocSignatureSpan">react-bootstrap.SplitButton.propTypes.</span>href ()](#apidoc.element.react-bootstrap.SplitButton.propTypes.href)
- description and source-code
```javascript
href = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.SplitButton.propTypes.onClick"></a>[function <span class="apidocSignatureSpan">react-bootstrap.SplitButton.propTypes.</span>onClick ()](#apidoc.element.react-bootstrap.SplitButton.propTypes.onClick)
- description and source-code
```javascript
onClick = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.SplitButton.propTypes.open"></a>[function <span class="apidocSignatureSpan">react-bootstrap.SplitButton.propTypes.</span>open (props, propName)](#apidoc.element.react-bootstrap.SplitButton.propTypes.open)
- description and source-code
```javascript
open = function (props, propName) {
  if (props[propName] !== undefined) {
    if (!props[handler]) {
      return new Error('You have provided a '' + propName + '' prop to ' + ''' + name + '' without an '' + handler + '' handler.
This will render a read-only field. ' + 'If the field should be mutable use '' + defaultKey(propName) + ''. Otherwise, set '' +
handler + ''');
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.SplitButton.propTypes.title"></a>[function <span class="apidocSignatureSpan">react-bootstrap.SplitButton.propTypes.</span>title ()](#apidoc.element.react-bootstrap.SplitButton.propTypes.title)
- description and source-code
```javascript
title = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.SplitButton.propTypes.toggleLabel"></a>[function <span class="apidocSignatureSpan">react-bootstrap.SplitButton.propTypes.</span>toggleLabel ()](#apidoc.element.react-bootstrap.SplitButton.propTypes.toggleLabel)
- description and source-code
```javascript
toggleLabel = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.SplitButton.prototype"></a>[module react-bootstrap.SplitButton.prototype](#apidoc.module.react-bootstrap.SplitButton.prototype)

#### <a name="apidoc.element.react-bootstrap.SplitButton.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.SplitButton.prototype.</span>render ()](#apidoc.element.react-bootstrap.SplitButton.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      bsSize = _props.bsSize,
      bsStyle = _props.bsStyle,
      title = _props.title,
      toggleLabel = _props.toggleLabel,
      children = _props.children,
      props = (0, _objectWithoutProperties3['default'])(_props, ['bsSize', 'bsStyle', 'title', 'toggleLabel', 'children']);

  var _splitComponentProps = (0, _splitComponentProps3['default'])(props, _Dropdown2['default'].ControlledComponent),
      dropdownProps = _splitComponentProps[0],
      buttonProps = _splitComponentProps[1];

  return _react2['default'].createElement(
    _Dropdown2['default'],
    (0, _extends3['default'])({}, dropdownProps, {
      bsSize: bsSize,
      bsStyle: bsStyle
    }),
    _react2['default'].createElement(
      _Button2['default'],
      (0, _extends3['default'])({}, buttonProps, {
        disabled: props.disabled,
        bsSize: bsSize,
        bsStyle: bsStyle
      }),
      title
    ),
    _react2['default'].createElement(_SplitToggle2['default'], {
      'aria-label': toggleLabel || title,
      bsSize: bsSize,
      bsStyle: bsStyle
    }),
    _react2['default'].createElement(
      _Dropdown2['default'].Menu,
      null,
      children
    )
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Tab"></a>[module react-bootstrap.Tab](#apidoc.module.react-bootstrap.Tab)

#### <a name="apidoc.element.react-bootstrap.Tab.Tab"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Tab ()](#apidoc.element.react-bootstrap.Tab.Tab)
- description and source-code
```javascript
function Tab() {
  (0, _classCallCheck3['default'])(this, Tab);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tab.Container"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tab.</span>Container (props, context, updater)](#apidoc.element.react-bootstrap.Tab.Container)
- description and source-code
```javascript
Container = function (props, context, updater) {
  // This constructor gets overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : void 0;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindPairs.length) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (initialState === undefined && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : _prodInvariant('82',
Constructor.displayName || 'ReactCompositeComponent') : void 0;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tab.Content"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tab.</span>Content (props, context)](#apidoc.element.react-bootstrap.Tab.Content)
- description and source-code
```javascript
function TabContent(props, context) {
  (0, _classCallCheck3['default'])(this, TabContent);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handlePaneEnter = _this.handlePaneEnter.bind(_this);
  _this.handlePaneExited = _this.handlePaneExited.bind(_this);

  // Active entries in state will be 'null' unless 'animation' is set. Need
  // to track active child in case keys swap and the active child changes
  // but the active key does not.
  _this.state = {
    activeKey: null,
    activeChild: null
  };
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tab.Pane"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tab.</span>Pane (props, context)](#apidoc.element.react-bootstrap.Tab.Pane)
- description and source-code
```javascript
function TabPane(props, context) {
  (0, _classCallCheck3['default'])(this, TabPane);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleEnter = _this.handleEnter.bind(_this);
  _this.handleExited = _this.handleExited.bind(_this);

  _this['in'] = false;
  return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Tab.propTypes"></a>[module react-bootstrap.Tab.propTypes](#apidoc.module.react-bootstrap.Tab.propTypes)

#### <a name="apidoc.element.react-bootstrap.Tab.propTypes.animation"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>animation ()](#apidoc.element.react-bootstrap.Tab.propTypes.animation)
- description and source-code
```javascript
animation = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tab.propTypes.aria-labelledby"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>aria-labelledby ()](#apidoc.element.react-bootstrap.Tab.propTypes.aria-labelledby)
- description and source-code
```javascript
aria-labelledby = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tab.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Tab.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tab.propTypes.disabled"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>disabled ()](#apidoc.element.react-bootstrap.Tab.propTypes.disabled)
- description and source-code
```javascript
disabled = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tab.propTypes.eventKey"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>eventKey ()](#apidoc.element.react-bootstrap.Tab.propTypes.eventKey)
- description and source-code
```javascript
eventKey = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tab.propTypes.id"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>id ()](#apidoc.element.react-bootstrap.Tab.propTypes.id)
- description and source-code
```javascript
id = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tab.propTypes.mountOnEnter"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>mountOnEnter ()](#apidoc.element.react-bootstrap.Tab.propTypes.mountOnEnter)
- description and source-code
```javascript
mountOnEnter = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tab.propTypes.onEnter"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>onEnter ()](#apidoc.element.react-bootstrap.Tab.propTypes.onEnter)
- description and source-code
```javascript
onEnter = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tab.propTypes.onEntered"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>onEntered ()](#apidoc.element.react-bootstrap.Tab.propTypes.onEntered)
- description and source-code
```javascript
onEntered = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tab.propTypes.onEntering"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>onEntering ()](#apidoc.element.react-bootstrap.Tab.propTypes.onEntering)
- description and source-code
```javascript
onEntering = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tab.propTypes.onExit"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>onExit ()](#apidoc.element.react-bootstrap.Tab.propTypes.onExit)
- description and source-code
```javascript
onExit = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tab.propTypes.onExited"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>onExited ()](#apidoc.element.react-bootstrap.Tab.propTypes.onExited)
- description and source-code
```javascript
onExited = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tab.propTypes.onExiting"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>onExiting ()](#apidoc.element.react-bootstrap.Tab.propTypes.onExiting)
- description and source-code
```javascript
onExiting = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tab.propTypes.tabClassName"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>tabClassName ()](#apidoc.element.react-bootstrap.Tab.propTypes.tabClassName)
- description and source-code
```javascript
tabClassName = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tab.propTypes.title"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>title ()](#apidoc.element.react-bootstrap.Tab.propTypes.title)
- description and source-code
```javascript
title = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tab.propTypes.unmountOnExit"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tab.propTypes.</span>unmountOnExit ()](#apidoc.element.react-bootstrap.Tab.propTypes.unmountOnExit)
- description and source-code
```javascript
unmountOnExit = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Tab.prototype"></a>[module react-bootstrap.Tab.prototype](#apidoc.module.react-bootstrap.Tab.prototype)

#### <a name="apidoc.element.react-bootstrap.Tab.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tab.prototype.</span>render ()](#apidoc.element.react-bootstrap.Tab.prototype.render)
- description and source-code
```javascript
function render() {
  var props = (0, _extends3['default'])({}, this.props);

  // These props are for the parent '<Tabs>' rather than the '<TabPane>'.
  delete props.title;
  delete props.disabled;
  delete props.tabClassName;

  return _react2['default'].createElement(_TabPane2['default'], props);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.TabContainer"></a>[module react-bootstrap.TabContainer](#apidoc.module.react-bootstrap.TabContainer)

#### <a name="apidoc.element.react-bootstrap.TabContainer.TabContainer"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>TabContainer (props, context, updater)](#apidoc.element.react-bootstrap.TabContainer.TabContainer)
- description and source-code
```javascript
TabContainer = function (props, context, updater) {
  // This constructor gets overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : void 0;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindPairs.length) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (initialState === undefined && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : _prodInvariant('82',
Constructor.displayName || 'ReactCompositeComponent') : void 0;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabContainer.ControlledComponent"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabContainer.</span>ControlledComponent ()](#apidoc.element.react-bootstrap.TabContainer.ControlledComponent)
- description and source-code
```javascript
function TabContainer() {
  (0, _classCallCheck3['default'])(this, TabContainer);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabContainer.deferControlTo"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabContainer.</span>deferControlTo (newComponent)](#apidoc.element.react-bootstrap.TabContainer.deferControlTo)
- description and source-code
```javascript
deferControlTo = function (newComponent) {
  var additions = arguments.length <= 1 || arguments[1] === undefined ? {} : arguments[1];
  var nextMethods = arguments[2];

  return uncontrollable(newComponent, _extends({}, controlledValues, additions), nextMethods);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.TabContainer.ControlledComponent"></a>[module react-bootstrap.TabContainer.ControlledComponent](#apidoc.module.react-bootstrap.TabContainer.ControlledComponent)

#### <a name="apidoc.element.react-bootstrap.TabContainer.ControlledComponent.ControlledComponent"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabContainer.</span>ControlledComponent ()](#apidoc.element.react-bootstrap.TabContainer.ControlledComponent.ControlledComponent)
- description and source-code
```javascript
function TabContainer() {
  (0, _classCallCheck3['default'])(this, TabContainer);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.TabContainer.ControlledComponent.prototype"></a>[module react-bootstrap.TabContainer.ControlledComponent.prototype](#apidoc.module.react-bootstrap.TabContainer.ControlledComponent.prototype)

#### <a name="apidoc.element.react-bootstrap.TabContainer.ControlledComponent.prototype.getChildContext"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabContainer.ControlledComponent.prototype.</span>getChildContext ()](#apidoc.element.react-bootstrap.TabContainer.ControlledComponent.prototype.getChildContext)
- description and source-code
```javascript
function getChildContext() {
  var _props = this.props,
      activeKey = _props.activeKey,
      onSelect = _props.onSelect,
      generateChildId = _props.generateChildId,
      id = _props.id;


  var getId = generateChildId || function (key, type) {
    return id ? id + '-' + type + '-' + key : null;
  };

  return {
    $bs_tabContainer: {
      activeKey: activeKey,
      onSelect: onSelect,
      getTabId: function getTabId(key) {
        return getId(key, TAB);
      },
      getPaneId: function getPaneId(key) {
        return getId(key, PANE);
      }
    }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabContainer.ControlledComponent.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabContainer.ControlledComponent.prototype.</span>render ()](#apidoc.element.react-bootstrap.TabContainer.ControlledComponent.prototype.render)
- description and source-code
```javascript
function render() {
  var _props2 = this.props,
      children = _props2.children,
      props = (0, _objectWithoutProperties3['default'])(_props2, ['children']);


  delete props.generateChildId;
  delete props.onSelect;
  delete props.activeKey;

  return _react2['default'].cloneElement(_react2['default'].Children.only(children), props);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.TabContainer.propTypes"></a>[module react-bootstrap.TabContainer.propTypes](#apidoc.module.react-bootstrap.TabContainer.propTypes)

#### <a name="apidoc.element.react-bootstrap.TabContainer.propTypes.activeKey"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabContainer.propTypes.</span>activeKey (props, propName)](#apidoc.element.react-bootstrap.TabContainer.propTypes.activeKey)
- description and source-code
```javascript
activeKey = function (props, propName) {
  if (props[propName] !== undefined) {
    if (!props[handler]) {
      return new Error('You have provided a '' + propName + '' prop to ' + ''' + name + '' without an '' + handler + '' handler.
This will render a read-only field. ' + 'If the field should be mutable use '' + defaultKey(propName) + ''. Otherwise, set '' +
handler + ''');
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.TabContainer.prototype"></a>[module react-bootstrap.TabContainer.prototype](#apidoc.module.react-bootstrap.TabContainer.prototype)

#### <a name="apidoc.element.react-bootstrap.TabContainer.prototype.componentWillMount"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabContainer.prototype.</span>componentWillMount ()](#apidoc.element.react-bootstrap.TabContainer.prototype.componentWillMount)
- description and source-code
```javascript
function componentWillMount() {
  var _this = this;

  var props = this.props;

  this._values = {};

  controlledProps.forEach(function (key) {
    _this._values[key] = props[utils.defaultKey(key)];
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabContainer.prototype.componentWillReceiveProps"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabContainer.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.react-bootstrap.TabContainer.prototype.componentWillReceiveProps)
- description and source-code
```javascript
function componentWillReceiveProps(nextProps) {
  var _this2 = this;

  var props = this.props;

  controlledProps.forEach(function (key) {
    if (utils.getValue(nextProps, key) === undefined && utils.getValue(props, key) !== undefined) {
      _this2._values[key] = nextProps[utils.defaultKey(key)];
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabContainer.prototype.constructor"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabContainer.prototype.</span>constructor (props, context, updater)](#apidoc.element.react-bootstrap.TabContainer.prototype.constructor)
- description and source-code
```javascript
constructor = function (props, context, updater) {
  // This constructor gets overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : void 0;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindPairs.length) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (initialState === undefined && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : _prodInvariant('82',
Constructor.displayName || 'ReactCompositeComponent') : void 0;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabContainer.prototype.getControlledInstance"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabContainer.prototype.</span>getControlledInstance ()](#apidoc.element.react-bootstrap.TabContainer.prototype.getControlledInstance)
- description and source-code
```javascript
function getControlledInstance() {
  return this.refs.inner;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabContainer.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabContainer.prototype.</span>render ()](#apidoc.element.react-bootstrap.TabContainer.prototype.render)
- description and source-code
```javascript
function render() {
  var _this3 = this;

  var newProps = {},
      props = omitProps(this.props);

  utils.each(controlledValues, function (handle, propName) {
    var linkPropName = utils.getLinkName(propName),
        prop = _this3.props[propName];

    if (linkPropName && !isProp(_this3.props, propName) && isProp(_this3.props, linkPropName)) {
      prop = _this3.props[linkPropName].value;
    }

    newProps[propName] = prop !== undefined ? prop : _this3._values[propName];

    newProps[handle] = setAndNotify.bind(_this3, propName);
  });

  newProps = _extends({}, props, newProps, {
    ref: isCompositeComponent ? 'inner' : null
  });

  return _react2.default.createElement(Component, newProps);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabContainer.prototype.shouldComponentUpdate"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabContainer.prototype.</span>shouldComponentUpdate ()](#apidoc.element.react-bootstrap.TabContainer.prototype.shouldComponentUpdate)
- description and source-code
```javascript
function shouldComponentUpdate() {
  //let the forceUpdate trigger the update
  return !this._notifying;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.TabContainer.prototype.__reactAutoBindPairs"></a>[module react-bootstrap.TabContainer.prototype.__reactAutoBindPairs](#apidoc.module.react-bootstrap.TabContainer.prototype.__reactAutoBindPairs)

#### <a name="apidoc.element.react-bootstrap.TabContainer.prototype.__reactAutoBindPairs.1"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabContainer.prototype.__reactAutoBindPairs.</span>1 ()](#apidoc.element.react-bootstrap.TabContainer.prototype.__reactAutoBindPairs.1)
- description and source-code
```javascript
function getControlledInstance() {
  return this.refs.inner;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.TabContent"></a>[module react-bootstrap.TabContent](#apidoc.module.react-bootstrap.TabContent)

#### <a name="apidoc.element.react-bootstrap.TabContent.TabContent"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>TabContent (props, context)](#apidoc.element.react-bootstrap.TabContent.TabContent)
- description and source-code
```javascript
function TabContent(props, context) {
  (0, _classCallCheck3['default'])(this, TabContent);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handlePaneEnter = _this.handlePaneEnter.bind(_this);
  _this.handlePaneExited = _this.handlePaneExited.bind(_this);

  // Active entries in state will be 'null' unless 'animation' is set. Need
  // to track active child in case keys swap and the active child changes
  // but the active key does not.
  _this.state = {
    activeKey: null,
    activeChild: null
  };
  return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.TabContent.childContextTypes"></a>[module react-bootstrap.TabContent.childContextTypes](#apidoc.module.react-bootstrap.TabContent.childContextTypes)



# <a name="apidoc.module.react-bootstrap.TabContent.contextTypes"></a>[module react-bootstrap.TabContent.contextTypes](#apidoc.module.react-bootstrap.TabContent.contextTypes)



# <a name="apidoc.module.react-bootstrap.TabContent.propTypes"></a>[module react-bootstrap.TabContent.propTypes](#apidoc.module.react-bootstrap.TabContent.propTypes)

#### <a name="apidoc.element.react-bootstrap.TabContent.propTypes.animation"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabContent.propTypes.</span>animation ()](#apidoc.element.react-bootstrap.TabContent.propTypes.animation)
- description and source-code
```javascript
animation = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabContent.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabContent.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.TabContent.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabContent.propTypes.componentClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabContent.propTypes.</span>componentClass ()](#apidoc.element.react-bootstrap.TabContent.propTypes.componentClass)
- description and source-code
```javascript
componentClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabContent.propTypes.mountOnEnter"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabContent.propTypes.</span>mountOnEnter ()](#apidoc.element.react-bootstrap.TabContent.propTypes.mountOnEnter)
- description and source-code
```javascript
mountOnEnter = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabContent.propTypes.unmountOnExit"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabContent.propTypes.</span>unmountOnExit ()](#apidoc.element.react-bootstrap.TabContent.propTypes.unmountOnExit)
- description and source-code
```javascript
unmountOnExit = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.TabContent.prototype"></a>[module react-bootstrap.TabContent.prototype](#apidoc.module.react-bootstrap.TabContent.prototype)

#### <a name="apidoc.element.react-bootstrap.TabContent.prototype.componentWillReceiveProps"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabContent.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.react-bootstrap.TabContent.prototype.componentWillReceiveProps)
- description and source-code
```javascript
function componentWillReceiveProps(nextProps) {
  if (!nextProps.animation && this.state.activeChild) {
    this.setState({ activeKey: null, activeChild: null });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabContent.prototype.componentWillUnmount"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabContent.prototype.</span>componentWillUnmount ()](#apidoc.element.react-bootstrap.TabContent.prototype.componentWillUnmount)
- description and source-code
```javascript
function componentWillUnmount() {
  this.isUnmounted = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabContent.prototype.getChildContext"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabContent.prototype.</span>getChildContext ()](#apidoc.element.react-bootstrap.TabContent.prototype.getChildContext)
- description and source-code
```javascript
function getChildContext() {
  var _props = this.props,
      bsClass = _props.bsClass,
      animation = _props.animation,
      mountOnEnter = _props.mountOnEnter,
      unmountOnExit = _props.unmountOnExit;


  var stateActiveKey = this.state.activeKey;
  var containerActiveKey = this.getContainerActiveKey();

  var activeKey = stateActiveKey != null ? stateActiveKey : containerActiveKey;
  var exiting = stateActiveKey != null && stateActiveKey !== containerActiveKey;

  return {
    $bs_tabContent: {
      bsClass: bsClass,
      animation: animation,
      activeKey: activeKey,
      mountOnEnter: mountOnEnter,
      unmountOnExit: unmountOnExit,
      onPaneEnter: this.handlePaneEnter,
      onPaneExited: this.handlePaneExited,
      exiting: exiting
    }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabContent.prototype.getContainerActiveKey"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabContent.prototype.</span>getContainerActiveKey ()](#apidoc.element.react-bootstrap.TabContent.prototype.getContainerActiveKey)
- description and source-code
```javascript
function getContainerActiveKey() {
  var tabContainer = this.context.$bs_tabContainer;
  return tabContainer && tabContainer.activeKey;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabContent.prototype.handlePaneEnter"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabContent.prototype.</span>handlePaneEnter (child, childKey)](#apidoc.element.react-bootstrap.TabContent.prototype.handlePaneEnter)
- description and source-code
```javascript
function handlePaneEnter(child, childKey) {
  if (!this.props.animation) {
    return false;
  }

  // It's possible that this child should be transitioning out.
  if (childKey !== this.getContainerActiveKey()) {
    return false;
  }

  this.setState({
    activeKey: childKey,
    activeChild: child
  });

  return true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabContent.prototype.handlePaneExited"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabContent.prototype.</span>handlePaneExited (child)](#apidoc.element.react-bootstrap.TabContent.prototype.handlePaneExited)
- description and source-code
```javascript
function handlePaneExited(child) {
  // This might happen as everything is unmounting.
  if (this.isUnmounted) {
    return;
  }

  this.setState(function (_ref) {
    var activeChild = _ref.activeChild;

    if (activeChild !== child) {
      return null;
    }

    return {
      activeKey: null,
      activeChild: null
    };
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabContent.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabContent.prototype.</span>render ()](#apidoc.element.react-bootstrap.TabContent.prototype.render)
- description and source-code
```javascript
function render() {
  var _props2 = this.props,
      Component = _props2.componentClass,
      className = _props2.className,
      props = (0, _objectWithoutProperties3['default'])(_props2, ['componentClass', 'className']);

  var _splitBsPropsAndOmit = (0, _bootstrapUtils.splitBsPropsAndOmit)(props, ['animation', 'mountOnEnter', 'unmountOnExit']),
      bsProps = _splitBsPropsAndOmit[0],
      elementProps = _splitBsPropsAndOmit[1];

  return _react2['default'].createElement(Component, (0, _extends3['default'])({}, elementProps, {
    className: (0, _classnames2['default'])(className, (0, _bootstrapUtils.prefix)(bsProps, 'content'))
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.TabPane"></a>[module react-bootstrap.TabPane](#apidoc.module.react-bootstrap.TabPane)

#### <a name="apidoc.element.react-bootstrap.TabPane.TabPane"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>TabPane (props, context)](#apidoc.element.react-bootstrap.TabPane.TabPane)
- description and source-code
```javascript
function TabPane(props, context) {
  (0, _classCallCheck3['default'])(this, TabPane);

  var _this = (0, _possibleConstructorReturn3['default'])(this, _React$Component.call(this, props, context));

  _this.handleEnter = _this.handleEnter.bind(_this);
  _this.handleExited = _this.handleExited.bind(_this);

  _this['in'] = false;
  return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.TabPane.childContextTypes"></a>[module react-bootstrap.TabPane.childContextTypes](#apidoc.module.react-bootstrap.TabPane.childContextTypes)



# <a name="apidoc.module.react-bootstrap.TabPane.contextTypes"></a>[module react-bootstrap.TabPane.contextTypes](#apidoc.module.react-bootstrap.TabPane.contextTypes)



# <a name="apidoc.module.react-bootstrap.TabPane.propTypes"></a>[module react-bootstrap.TabPane.propTypes](#apidoc.module.react-bootstrap.TabPane.propTypes)

#### <a name="apidoc.element.react-bootstrap.TabPane.propTypes.animation"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabPane.propTypes.</span>animation ()](#apidoc.element.react-bootstrap.TabPane.propTypes.animation)
- description and source-code
```javascript
animation = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabPane.propTypes.aria-labelledby"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabPane.propTypes.</span>aria-labelledby ()](#apidoc.element.react-bootstrap.TabPane.propTypes.aria-labelledby)
- description and source-code
```javascript
aria-labelledby = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabPane.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabPane.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.TabPane.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabPane.propTypes.eventKey"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabPane.propTypes.</span>eventKey ()](#apidoc.element.react-bootstrap.TabPane.propTypes.eventKey)
- description and source-code
```javascript
eventKey = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabPane.propTypes.id"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabPane.propTypes.</span>id ()](#apidoc.element.react-bootstrap.TabPane.propTypes.id)
- description and source-code
```javascript
id = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabPane.propTypes.mountOnEnter"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabPane.propTypes.</span>mountOnEnter ()](#apidoc.element.react-bootstrap.TabPane.propTypes.mountOnEnter)
- description and source-code
```javascript
mountOnEnter = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabPane.propTypes.onEnter"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabPane.propTypes.</span>onEnter ()](#apidoc.element.react-bootstrap.TabPane.propTypes.onEnter)
- description and source-code
```javascript
onEnter = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabPane.propTypes.onEntered"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabPane.propTypes.</span>onEntered ()](#apidoc.element.react-bootstrap.TabPane.propTypes.onEntered)
- description and source-code
```javascript
onEntered = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabPane.propTypes.onEntering"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabPane.propTypes.</span>onEntering ()](#apidoc.element.react-bootstrap.TabPane.propTypes.onEntering)
- description and source-code
```javascript
onEntering = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabPane.propTypes.onExit"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabPane.propTypes.</span>onExit ()](#apidoc.element.react-bootstrap.TabPane.propTypes.onExit)
- description and source-code
```javascript
onExit = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabPane.propTypes.onExited"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabPane.propTypes.</span>onExited ()](#apidoc.element.react-bootstrap.TabPane.propTypes.onExited)
- description and source-code
```javascript
onExited = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabPane.propTypes.onExiting"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabPane.propTypes.</span>onExiting ()](#apidoc.element.react-bootstrap.TabPane.propTypes.onExiting)
- description and source-code
```javascript
onExiting = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabPane.propTypes.unmountOnExit"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabPane.propTypes.</span>unmountOnExit ()](#apidoc.element.react-bootstrap.TabPane.propTypes.unmountOnExit)
- description and source-code
```javascript
unmountOnExit = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.TabPane.prototype"></a>[module react-bootstrap.TabPane.prototype](#apidoc.module.react-bootstrap.TabPane.prototype)

#### <a name="apidoc.element.react-bootstrap.TabPane.prototype.componentDidMount"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabPane.prototype.</span>componentDidMount ()](#apidoc.element.react-bootstrap.TabPane.prototype.componentDidMount)
- description and source-code
```javascript
function componentDidMount() {
  if (this.shouldBeIn()) {
    // In lieu of the action event firing.
    this.handleEnter();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabPane.prototype.componentDidUpdate"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabPane.prototype.</span>componentDidUpdate ()](#apidoc.element.react-bootstrap.TabPane.prototype.componentDidUpdate)
- description and source-code
```javascript
function componentDidUpdate() {
  if (this['in']) {
    if (!this.shouldBeIn()) {
      // We shouldn't be active any more. Notify the parent.
      this.handleExited();
    }
  } else if (this.shouldBeIn()) {
    // We are the active child. Notify the parent.
    this.handleEnter();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabPane.prototype.componentWillUnmount"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabPane.prototype.</span>componentWillUnmount ()](#apidoc.element.react-bootstrap.TabPane.prototype.componentWillUnmount)
- description and source-code
```javascript
function componentWillUnmount() {
  if (this['in']) {
    // In lieu of the action event firing.
    this.handleExited();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabPane.prototype.getAnimation"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabPane.prototype.</span>getAnimation ()](#apidoc.element.react-bootstrap.TabPane.prototype.getAnimation)
- description and source-code
```javascript
function getAnimation() {
  if (this.props.animation != null) {
    return this.props.animation;
  }

  var tabContent = this.context.$bs_tabContent;
  return tabContent && tabContent.animation;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabPane.prototype.getChildContext"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabPane.prototype.</span>getChildContext ()](#apidoc.element.react-bootstrap.TabPane.prototype.getChildContext)
- description and source-code
```javascript
function getChildContext() {
  return {
    $bs_tabContainer: null
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabPane.prototype.handleEnter"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabPane.prototype.</span>handleEnter ()](#apidoc.element.react-bootstrap.TabPane.prototype.handleEnter)
- description and source-code
```javascript
function handleEnter() {
  var tabContent = this.context.$bs_tabContent;
  if (!tabContent) {
    return;
  }

  this['in'] = tabContent.onPaneEnter(this, this.props.eventKey);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabPane.prototype.handleExited"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabPane.prototype.</span>handleExited ()](#apidoc.element.react-bootstrap.TabPane.prototype.handleExited)
- description and source-code
```javascript
function handleExited() {
  var tabContent = this.context.$bs_tabContent;
  if (!tabContent) {
    return;
  }

  tabContent.onPaneExited(this);
  this['in'] = false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabPane.prototype.isActive"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabPane.prototype.</span>isActive ()](#apidoc.element.react-bootstrap.TabPane.prototype.isActive)
- description and source-code
```javascript
function isActive() {
  var tabContent = this.context.$bs_tabContent;
  var activeKey = tabContent && tabContent.activeKey;

  return this.props.eventKey === activeKey;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabPane.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabPane.prototype.</span>render ()](#apidoc.element.react-bootstrap.TabPane.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      eventKey = _props.eventKey,
      className = _props.className,
      onEnter = _props.onEnter,
      onEntering = _props.onEntering,
      onEntered = _props.onEntered,
      onExit = _props.onExit,
      onExiting = _props.onExiting,
      onExited = _props.onExited,
      propsMountOnEnter = _props.mountOnEnter,
      propsUnmountOnExit = _props.unmountOnExit,
      props = (0, _objectWithoutProperties3['default'])(_props, ['eventKey', 'className', 'onEnter', 'onEntering', 'onEntered', '
onExit', 'onExiting', 'onExited', 'mountOnEnter', 'unmountOnExit']);
  var _context = this.context,
      tabContent = _context.$bs_tabContent,
      tabContainer = _context.$bs_tabContainer;

  var _splitBsPropsAndOmit = (0, _bootstrapUtils.splitBsPropsAndOmit)(props, ['animation']),
      bsProps = _splitBsPropsAndOmit[0],
      elementProps = _splitBsPropsAndOmit[1];

  var active = this.isActive();
  var animation = this.getAnimation();

  var mountOnEnter = propsMountOnEnter != null ? propsMountOnEnter : tabContent && tabContent.mountOnEnter;
  var unmountOnExit = propsUnmountOnExit != null ? propsUnmountOnExit : tabContent && tabContent.unmountOnExit;

  if (!active && !animation && unmountOnExit) {
    return null;
  }

  var Transition = animation === true ? _Fade2['default'] : animation || null;

  if (tabContent) {
    bsProps.bsClass = (0, _bootstrapUtils.prefix)(tabContent, 'pane');
  }

  var classes = (0, _extends3['default'])({}, (0, _bootstrapUtils.getClassSet)(bsProps), {
    active: active
  });

  if (tabContainer) {
    process.env.NODE_ENV !== 'production' ? (0, _warning2['default'])(!elementProps.id && !elementProps['aria-labelledby'], 'In
the context of a '<TabContainer>', '<TabPanes>' are given ' + 'generated 'id' and 'aria-labelledby' attributes for the sake of ' + '
proper component accessibility. Any provided ones will be ignored. ' + 'To control these attributes directly provide a 'generateChildId
' ' + 'prop to the parent '<TabContainer>'.') : void 0;

    elementProps.id = tabContainer.getPaneId(eventKey);
    elementProps['aria-labelledby'] = tabContainer.getTabId(eventKey);
  }

  var pane = _react2['default'].createElement('div', (0, _extends3['default'])({}, elementProps, {
    role: 'tabpanel',
    'aria-hidden': !active,
    className: (0, _classnames2['default'])(className, classes)
  }));

  if (Transition) {
    var exiting = tabContent && tabContent.exiting;

    return _react2['default'].createElement(
      Transition,
      {
        'in': active && !exiting,
        onEnter: (0, _createChainedFunction2['default'])(this.handleEnter, onEnter),
        onEntering: onEntering,
        onEntered: onEntered,
        onExit: onExit,
        onExiting: onExiting,
        onExited: (0, _createChainedFunction2['default'])(this.handleExited, onExited),
        mountOnEnter: mountOnEnter,
        unmountOnExit: unmountOnExit
      },
      pane
    );
  }

  return pane;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.TabPane.prototype.shouldBeIn"></a>[function <span class="apidocSignatureSpan">react-bootstrap.TabPane.prototype.</span>shouldBeIn ()](#apidoc.element.react-bootstrap.TabPane.prototype.shouldBeIn)
- description and source-code
```javascript
function shouldBeIn() {
  return this.getAnimation() && this.isActive();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Table"></a>[module react-bootstrap.Table](#apidoc.module.react-bootstrap.Table)

#### <a name="apidoc.element.react-bootstrap.Table.Table"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Table ()](#apidoc.element.react-bootstrap.Table.Table)
- description and source-code
```javascript
function Table() {
  (0, _classCallCheck3['default'])(this, Table);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Table.propTypes"></a>[module react-bootstrap.Table.propTypes](#apidoc.module.react-bootstrap.Table.propTypes)

#### <a name="apidoc.element.react-bootstrap.Table.propTypes.bordered"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Table.propTypes.</span>bordered ()](#apidoc.element.react-bootstrap.Table.propTypes.bordered)
- description and source-code
```javascript
bordered = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Table.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Table.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Table.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Table.propTypes.condensed"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Table.propTypes.</span>condensed ()](#apidoc.element.react-bootstrap.Table.propTypes.condensed)
- description and source-code
```javascript
condensed = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Table.propTypes.hover"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Table.propTypes.</span>hover ()](#apidoc.element.react-bootstrap.Table.propTypes.hover)
- description and source-code
```javascript
hover = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Table.propTypes.responsive"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Table.propTypes.</span>responsive ()](#apidoc.element.react-bootstrap.Table.propTypes.responsive)
- description and source-code
```javascript
responsive = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Table.propTypes.striped"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Table.propTypes.</span>striped ()](#apidoc.element.react-bootstrap.Table.propTypes.striped)
- description and source-code
```javascript
striped = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Table.prototype"></a>[module react-bootstrap.Table.prototype](#apidoc.module.react-bootstrap.Table.prototype)

#### <a name="apidoc.element.react-bootstrap.Table.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Table.prototype.</span>render ()](#apidoc.element.react-bootstrap.Table.prototype.render)
- description and source-code
```javascript
function render() {
  var _extends2;

  var _props = this.props,
      striped = _props.striped,
      bordered = _props.bordered,
      condensed = _props.condensed,
      hover = _props.hover,
      responsive = _props.responsive,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['striped', 'bordered', 'condensed', 'hover', 'responsive', 'className
']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _extends4['default'])({}, (0, _bootstrapUtils.getClassSet)(bsProps), (_extends2 = {}, _extends2[(0, _bootstrapUtils
.prefix)(bsProps, 'striped')] = striped, _extends2[(0, _bootstrapUtils.prefix)(bsProps, 'bordered')] = bordered, _extends2[(0, _bootstrapUtils
.prefix)(bsProps, 'condensed')] = condensed, _extends2[(0, _bootstrapUtils.prefix)(bsProps, 'hover')] = hover, _extends2));

  var table = _react2['default'].createElement('table', (0, _extends4['default'])({}, elementProps, {
    className: (0, _classnames2['default'])(className, classes)
  }));

  if (responsive) {
    return _react2['default'].createElement(
      'div',
      { className: (0, _bootstrapUtils.prefix)(bsProps, 'responsive') },
      table
    );
  }

  return table;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Tabs"></a>[module react-bootstrap.Tabs](#apidoc.module.react-bootstrap.Tabs)

#### <a name="apidoc.element.react-bootstrap.Tabs.Tabs"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Tabs (props, context, updater)](#apidoc.element.react-bootstrap.Tabs.Tabs)
- description and source-code
```javascript
Tabs = function (props, context, updater) {
  // This constructor gets overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : void 0;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindPairs.length) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (initialState === undefined && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : _prodInvariant('82',
Constructor.displayName || 'ReactCompositeComponent') : void 0;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tabs.ControlledComponent"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tabs.</span>ControlledComponent ()](#apidoc.element.react-bootstrap.Tabs.ControlledComponent)
- description and source-code
```javascript
function Tabs() {
  (0, _classCallCheck3['default'])(this, Tabs);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tabs.deferControlTo"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tabs.</span>deferControlTo (newComponent)](#apidoc.element.react-bootstrap.Tabs.deferControlTo)
- description and source-code
```javascript
deferControlTo = function (newComponent) {
  var additions = arguments.length <= 1 || arguments[1] === undefined ? {} : arguments[1];
  var nextMethods = arguments[2];

  return uncontrollable(newComponent, _extends({}, controlledValues, additions), nextMethods);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Tabs.ControlledComponent"></a>[module react-bootstrap.Tabs.ControlledComponent](#apidoc.module.react-bootstrap.Tabs.ControlledComponent)

#### <a name="apidoc.element.react-bootstrap.Tabs.ControlledComponent.ControlledComponent"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tabs.</span>ControlledComponent ()](#apidoc.element.react-bootstrap.Tabs.ControlledComponent.ControlledComponent)
- description and source-code
```javascript
function Tabs() {
  (0, _classCallCheck3['default'])(this, Tabs);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Tabs.ControlledComponent.prototype"></a>[module react-bootstrap.Tabs.ControlledComponent.prototype](#apidoc.module.react-bootstrap.Tabs.ControlledComponent.prototype)

#### <a name="apidoc.element.react-bootstrap.Tabs.ControlledComponent.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tabs.ControlledComponent.prototype.</span>render ()](#apidoc.element.react-bootstrap.Tabs.ControlledComponent.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      id = _props.id,
      onSelect = _props.onSelect,
      animation = _props.animation,
      mountOnEnter = _props.mountOnEnter,
      unmountOnExit = _props.unmountOnExit,
      bsClass = _props.bsClass,
      className = _props.className,
      style = _props.style,
      children = _props.children,
      _props$activeKey = _props.activeKey,
      activeKey = _props$activeKey === undefined ? getDefaultActiveKey(children) : _props$activeKey,
      props = (0, _objectWithoutProperties3['default'])(_props, ['id', 'onSelect', 'animation', 'mountOnEnter', 'unmountOnExit', '
bsClass', 'className', 'style', 'children', 'activeKey']);


  return _react2['default'].createElement(
    TabContainer,
    {
      id: id,
      activeKey: activeKey,
      onSelect: onSelect,
      className: className,
      style: style
    },
    _react2['default'].createElement(
      'div',
      null,
      _react2['default'].createElement(
        _Nav2['default'],
        (0, _extends3['default'])({}, props, {
          role: 'tablist'
        }),
        _ValidComponentChildren2['default'].map(children, this.renderTab)
      ),
      _react2['default'].createElement(
        _TabContent2['default'],
        {
          bsClass: bsClass,
          animation: animation,
          mountOnEnter: mountOnEnter,
          unmountOnExit: unmountOnExit
        },
        children
      )
    )
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tabs.ControlledComponent.prototype.renderTab"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tabs.ControlledComponent.prototype.</span>renderTab (child)](#apidoc.element.react-bootstrap.Tabs.ControlledComponent.prototype.renderTab)
- description and source-code
```javascript
function renderTab(child) {
  var _child$props = child.props,
      title = _child$props.title,
      eventKey = _child$props.eventKey,
      disabled = _child$props.disabled,
      tabClassName = _child$props.tabClassName;

  if (title == null) {
    return null;
  }

  return _react2['default'].createElement(
    _NavItem2['default'],
    {
      eventKey: eventKey,
      disabled: disabled,
      className: tabClassName
    },
    title
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Tabs.propTypes"></a>[module react-bootstrap.Tabs.propTypes](#apidoc.module.react-bootstrap.Tabs.propTypes)

#### <a name="apidoc.element.react-bootstrap.Tabs.propTypes.activeKey"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tabs.propTypes.</span>activeKey (props, propName)](#apidoc.element.react-bootstrap.Tabs.propTypes.activeKey)
- description and source-code
```javascript
activeKey = function (props, propName) {
  if (props[propName] !== undefined) {
    if (!props[handler]) {
      return new Error('You have provided a '' + propName + '' prop to ' + ''' + name + '' without an '' + handler + '' handler.
This will render a read-only field. ' + 'If the field should be mutable use '' + defaultKey(propName) + ''. Otherwise, set '' +
handler + ''');
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Tabs.prototype"></a>[module react-bootstrap.Tabs.prototype](#apidoc.module.react-bootstrap.Tabs.prototype)

#### <a name="apidoc.element.react-bootstrap.Tabs.prototype.componentWillMount"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tabs.prototype.</span>componentWillMount ()](#apidoc.element.react-bootstrap.Tabs.prototype.componentWillMount)
- description and source-code
```javascript
function componentWillMount() {
  var _this = this;

  var props = this.props;

  this._values = {};

  controlledProps.forEach(function (key) {
    _this._values[key] = props[utils.defaultKey(key)];
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tabs.prototype.componentWillReceiveProps"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tabs.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.react-bootstrap.Tabs.prototype.componentWillReceiveProps)
- description and source-code
```javascript
function componentWillReceiveProps(nextProps) {
  var _this2 = this;

  var props = this.props;

  controlledProps.forEach(function (key) {
    if (utils.getValue(nextProps, key) === undefined && utils.getValue(props, key) !== undefined) {
      _this2._values[key] = nextProps[utils.defaultKey(key)];
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tabs.prototype.constructor"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tabs.prototype.</span>constructor (props, context, updater)](#apidoc.element.react-bootstrap.Tabs.prototype.constructor)
- description and source-code
```javascript
constructor = function (props, context, updater) {
  // This constructor gets overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : void 0;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindPairs.length) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (initialState === undefined && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : _prodInvariant('82',
Constructor.displayName || 'ReactCompositeComponent') : void 0;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tabs.prototype.getControlledInstance"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tabs.prototype.</span>getControlledInstance ()](#apidoc.element.react-bootstrap.Tabs.prototype.getControlledInstance)
- description and source-code
```javascript
function getControlledInstance() {
  return this.refs.inner;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tabs.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tabs.prototype.</span>render ()](#apidoc.element.react-bootstrap.Tabs.prototype.render)
- description and source-code
```javascript
function render() {
  var _this3 = this;

  var newProps = {},
      props = omitProps(this.props);

  utils.each(controlledValues, function (handle, propName) {
    var linkPropName = utils.getLinkName(propName),
        prop = _this3.props[propName];

    if (linkPropName && !isProp(_this3.props, propName) && isProp(_this3.props, linkPropName)) {
      prop = _this3.props[linkPropName].value;
    }

    newProps[propName] = prop !== undefined ? prop : _this3._values[propName];

    newProps[handle] = setAndNotify.bind(_this3, propName);
  });

  newProps = _extends({}, props, newProps, {
    ref: isCompositeComponent ? 'inner' : null
  });

  return _react2.default.createElement(Component, newProps);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tabs.prototype.shouldComponentUpdate"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tabs.prototype.</span>shouldComponentUpdate ()](#apidoc.element.react-bootstrap.Tabs.prototype.shouldComponentUpdate)
- description and source-code
```javascript
function shouldComponentUpdate() {
  //let the forceUpdate trigger the update
  return !this._notifying;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Tabs.prototype.__reactAutoBindPairs"></a>[module react-bootstrap.Tabs.prototype.__reactAutoBindPairs](#apidoc.module.react-bootstrap.Tabs.prototype.__reactAutoBindPairs)

#### <a name="apidoc.element.react-bootstrap.Tabs.prototype.__reactAutoBindPairs.1"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tabs.prototype.__reactAutoBindPairs.</span>1 ()](#apidoc.element.react-bootstrap.Tabs.prototype.__reactAutoBindPairs.1)
- description and source-code
```javascript
function getControlledInstance() {
  return this.refs.inner;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Thumbnail"></a>[module react-bootstrap.Thumbnail](#apidoc.module.react-bootstrap.Thumbnail)

#### <a name="apidoc.element.react-bootstrap.Thumbnail.Thumbnail"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Thumbnail ()](#apidoc.element.react-bootstrap.Thumbnail.Thumbnail)
- description and source-code
```javascript
function Thumbnail() {
  (0, _classCallCheck3['default'])(this, Thumbnail);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Thumbnail.propTypes"></a>[module react-bootstrap.Thumbnail.propTypes](#apidoc.module.react-bootstrap.Thumbnail.propTypes)

#### <a name="apidoc.element.react-bootstrap.Thumbnail.propTypes.alt"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Thumbnail.propTypes.</span>alt ()](#apidoc.element.react-bootstrap.Thumbnail.propTypes.alt)
- description and source-code
```javascript
alt = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Thumbnail.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Thumbnail.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Thumbnail.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Thumbnail.propTypes.href"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Thumbnail.propTypes.</span>href ()](#apidoc.element.react-bootstrap.Thumbnail.propTypes.href)
- description and source-code
```javascript
href = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Thumbnail.propTypes.src"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Thumbnail.propTypes.</span>src ()](#apidoc.element.react-bootstrap.Thumbnail.propTypes.src)
- description and source-code
```javascript
src = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Thumbnail.prototype"></a>[module react-bootstrap.Thumbnail.prototype](#apidoc.module.react-bootstrap.Thumbnail.prototype)

#### <a name="apidoc.element.react-bootstrap.Thumbnail.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Thumbnail.prototype.</span>render ()](#apidoc.element.react-bootstrap.Thumbnail.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      src = _props.src,
      alt = _props.alt,
      className = _props.className,
      children = _props.children,
      props = (0, _objectWithoutProperties3['default'])(_props, ['src', 'alt', 'className', 'children']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var Component = elementProps.href ? _SafeAnchor2['default'] : 'div';
  var classes = (0, _bootstrapUtils.getClassSet)(bsProps);

  return _react2['default'].createElement(
    Component,
    (0, _extends3['default'])({}, elementProps, {
      className: (0, _classnames2['default'])(className, classes)
    }),
    _react2['default'].createElement('img', { src: src, alt: alt }),
    children && _react2['default'].createElement(
      'div',
      { className: 'caption' },
      children
    )
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Tooltip"></a>[module react-bootstrap.Tooltip](#apidoc.module.react-bootstrap.Tooltip)

#### <a name="apidoc.element.react-bootstrap.Tooltip.Tooltip"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Tooltip ()](#apidoc.element.react-bootstrap.Tooltip.Tooltip)
- description and source-code
```javascript
function Tooltip() {
  (0, _classCallCheck3['default'])(this, Tooltip);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Tooltip.propTypes"></a>[module react-bootstrap.Tooltip.propTypes](#apidoc.module.react-bootstrap.Tooltip.propTypes)

#### <a name="apidoc.element.react-bootstrap.Tooltip.propTypes.arrowOffsetLeft"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tooltip.propTypes.</span>arrowOffsetLeft ()](#apidoc.element.react-bootstrap.Tooltip.propTypes.arrowOffsetLeft)
- description and source-code
```javascript
arrowOffsetLeft = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tooltip.propTypes.arrowOffsetTop"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tooltip.propTypes.</span>arrowOffsetTop ()](#apidoc.element.react-bootstrap.Tooltip.propTypes.arrowOffsetTop)
- description and source-code
```javascript
arrowOffsetTop = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tooltip.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tooltip.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Tooltip.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tooltip.propTypes.id"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tooltip.propTypes.</span>id (props, propName, componentName, location, propFullName)](#apidoc.element.react-bootstrap.Tooltip.propTypes.id)
- description and source-code
```javascript
function validate(props, propName, componentName, location, propFullName) {
  var componentNameSafe = componentName || '<<anonymous>>';
  var propFullNameSafe = propFullName || propName;

  if (props[propName] == null) {
    return new Error('The ' + location + ' '' + propFullNameSafe + '' is required to make ' + (''' + componentNameSafe + '' accessible
 for users of assistive ') + 'technologies such as screen readers.');
  }

  for (var _len = arguments.length, args = Array(_len > 5 ? _len - 5 : 0), _key = 5; _key < _len; _key++) {
    args[_key - 5] = arguments[_key];
  }

  return validator.apply(undefined, [props, propName, componentName, location, propFullName].concat(args));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tooltip.propTypes.placement"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tooltip.propTypes.</span>placement ()](#apidoc.element.react-bootstrap.Tooltip.propTypes.placement)
- description and source-code
```javascript
placement = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tooltip.propTypes.positionLeft"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tooltip.propTypes.</span>positionLeft ()](#apidoc.element.react-bootstrap.Tooltip.propTypes.positionLeft)
- description and source-code
```javascript
positionLeft = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Tooltip.propTypes.positionTop"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tooltip.propTypes.</span>positionTop ()](#apidoc.element.react-bootstrap.Tooltip.propTypes.positionTop)
- description and source-code
```javascript
positionTop = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Tooltip.prototype"></a>[module react-bootstrap.Tooltip.prototype](#apidoc.module.react-bootstrap.Tooltip.prototype)

#### <a name="apidoc.element.react-bootstrap.Tooltip.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Tooltip.prototype.</span>render ()](#apidoc.element.react-bootstrap.Tooltip.prototype.render)
- description and source-code
```javascript
function render() {
  var _extends2;

  var _props = this.props,
      placement = _props.placement,
      positionTop = _props.positionTop,
      positionLeft = _props.positionLeft,
      arrowOffsetTop = _props.arrowOffsetTop,
      arrowOffsetLeft = _props.arrowOffsetLeft,
      className = _props.className,
      style = _props.style,
      children = _props.children,
      props = (0, _objectWithoutProperties3['default'])(_props, ['placement', 'positionTop', 'positionLeft', 'arrowOffsetTop', '
arrowOffsetLeft', 'className', 'style', 'children']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _extends4['default'])({}, (0, _bootstrapUtils.getClassSet)(bsProps), (_extends2 = {}, _extends2[placement] =
true, _extends2));

  var outerStyle = (0, _extends4['default'])({
    top: positionTop,
    left: positionLeft
  }, style);

  var arrowStyle = {
    top: arrowOffsetTop,
    left: arrowOffsetLeft
  };

  return _react2['default'].createElement(
    'div',
    (0, _extends4['default'])({}, elementProps, {
      role: 'tooltip',
      className: (0, _classnames2['default'])(className, classes),
      style: outerStyle
    }),
    _react2['default'].createElement('div', { className: (0, _bootstrapUtils.prefix)(bsProps, 'arrow'), style: arrowStyle }),
    _react2['default'].createElement(
      'div',
      { className: (0, _bootstrapUtils.prefix)(bsProps, 'inner') },
      children
    )
  );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Well"></a>[module react-bootstrap.Well](#apidoc.module.react-bootstrap.Well)

#### <a name="apidoc.element.react-bootstrap.Well.Well"></a>[function <span class="apidocSignatureSpan">react-bootstrap.</span>Well ()](#apidoc.element.react-bootstrap.Well.Well)
- description and source-code
```javascript
function Well() {
  (0, _classCallCheck3['default'])(this, Well);
  return (0, _possibleConstructorReturn3['default'])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Well.propTypes"></a>[module react-bootstrap.Well.propTypes](#apidoc.module.react-bootstrap.Well.propTypes)

#### <a name="apidoc.element.react-bootstrap.Well.propTypes.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Well.propTypes.</span>bsClass ()](#apidoc.element.react-bootstrap.Well.propTypes.bsClass)
- description and source-code
```javascript
bsClass = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.Well.propTypes.bsSize"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Well.propTypes.</span>bsSize ()](#apidoc.element.react-bootstrap.Well.propTypes.bsSize)
- description and source-code
```javascript
bsSize = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.Well.prototype"></a>[module react-bootstrap.Well.prototype](#apidoc.module.react-bootstrap.Well.prototype)

#### <a name="apidoc.element.react-bootstrap.Well.prototype.render"></a>[function <span class="apidocSignatureSpan">react-bootstrap.Well.prototype.</span>render ()](#apidoc.element.react-bootstrap.Well.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      className = _props.className,
      props = (0, _objectWithoutProperties3['default'])(_props, ['className']);

  var _splitBsProps = (0, _bootstrapUtils.splitBsProps)(props),
      bsProps = _splitBsProps[0],
      elementProps = _splitBsProps[1];

  var classes = (0, _bootstrapUtils.getClassSet)(bsProps);

  return _react2['default'].createElement('div', (0, _extends3['default'])({}, elementProps, {
    className: (0, _classnames2['default'])(className, classes)
  }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.utils"></a>[module react-bootstrap.utils](#apidoc.module.react-bootstrap.utils)

#### <a name="apidoc.element.react-bootstrap.utils.createChainedFunction"></a>[function <span class="apidocSignatureSpan">react-bootstrap.utils.</span>createChainedFunction ()](#apidoc.element.react-bootstrap.utils.createChainedFunction)
- description and source-code
```javascript
function createChainedFunction() {
  for (var _len = arguments.length, funcs = Array(_len), _key = 0; _key < _len; _key++) {
    funcs[_key] = arguments[_key];
  }

  return funcs.filter(function (f) {
    return f != null;
  }).reduce(function (acc, f) {
    if (typeof f !== 'function') {
      throw new Error('Invalid Argument Type, must only provide functions, undefined, or null.');
    }

    if (acc === null) {
      return f;
    }

    return function chainedFunction() {
      for (var _len2 = arguments.length, args = Array(_len2), _key2 = 0; _key2 < _len2; _key2++) {
        args[_key2] = arguments[_key2];
      }

      acc.apply(this, args);
      f.apply(this, args);
    };
  }, null);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.utils.ValidComponentChildren"></a>[module react-bootstrap.utils.ValidComponentChildren](#apidoc.module.react-bootstrap.utils.ValidComponentChildren)

#### <a name="apidoc.element.react-bootstrap.utils.ValidComponentChildren.count"></a>[function <span class="apidocSignatureSpan">react-bootstrap.utils.ValidComponentChildren.</span>count (children)](#apidoc.element.react-bootstrap.utils.ValidComponentChildren.count)
- description and source-code
```javascript
function count(children) {
  var result = 0;

  _react2['default'].Children.forEach(children, function (child) {
    if (!_react2['default'].isValidElement(child)) {
      return;
    }

    ++result;
  });

  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.utils.ValidComponentChildren.every"></a>[function <span class="apidocSignatureSpan">react-bootstrap.utils.ValidComponentChildren.</span>every (children, func, context)](#apidoc.element.react-bootstrap.utils.ValidComponentChildren.every)
- description and source-code
```javascript
function every(children, func, context) {
  var index = 0;
  var result = true;

  _react2['default'].Children.forEach(children, function (child) {
    if (!result) {
      return;
    }
    if (!_react2['default'].isValidElement(child)) {
      return;
    }

    if (!func.call(context, child, index++)) {
      result = false;
    }
  });

  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.utils.ValidComponentChildren.filter"></a>[function <span class="apidocSignatureSpan">react-bootstrap.utils.ValidComponentChildren.</span>filter (children, func, context)](#apidoc.element.react-bootstrap.utils.ValidComponentChildren.filter)
- description and source-code
```javascript
function filter(children, func, context) {
  var index = 0;
  var result = [];

  _react2['default'].Children.forEach(children, function (child) {
    if (!_react2['default'].isValidElement(child)) {
      return;
    }

    if (func.call(context, child, index++)) {
      result.push(child);
    }
  });

  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.utils.ValidComponentChildren.find"></a>[function <span class="apidocSignatureSpan">react-bootstrap.utils.ValidComponentChildren.</span>find (children, func, context)](#apidoc.element.react-bootstrap.utils.ValidComponentChildren.find)
- description and source-code
```javascript
function find(children, func, context) {
  var index = 0;
  var result = undefined;

  _react2['default'].Children.forEach(children, function (child) {
    if (result) {
      return;
    }
    if (!_react2['default'].isValidElement(child)) {
      return;
    }

    if (func.call(context, child, index++)) {
      result = child;
    }
  });

  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.utils.ValidComponentChildren.forEach"></a>[function <span class="apidocSignatureSpan">react-bootstrap.utils.ValidComponentChildren.</span>forEach (children, func, context)](#apidoc.element.react-bootstrap.utils.ValidComponentChildren.forEach)
- description and source-code
```javascript
function forEach(children, func, context) {
  var index = 0;

  _react2['default'].Children.forEach(children, function (child) {
    if (!_react2['default'].isValidElement(child)) {
      return;
    }

    func.call(context, child, index++);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.utils.ValidComponentChildren.map"></a>[function <span class="apidocSignatureSpan">react-bootstrap.utils.ValidComponentChildren.</span>map (children, func, context)](#apidoc.element.react-bootstrap.utils.ValidComponentChildren.map)
- description and source-code
```javascript
function map(children, func, context) {
  var index = 0;

  return _react2['default'].Children.map(children, function (child) {
    if (!_react2['default'].isValidElement(child)) {
      return child;
    }

    return func.call(context, child, index++);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.utils.ValidComponentChildren.some"></a>[function <span class="apidocSignatureSpan">react-bootstrap.utils.ValidComponentChildren.</span>some (children, func, context)](#apidoc.element.react-bootstrap.utils.ValidComponentChildren.some)
- description and source-code
```javascript
function some(children, func, context) {
  var index = 0;
  var result = false;

  _react2['default'].Children.forEach(children, function (child) {
    if (result) {
      return;
    }
    if (!_react2['default'].isValidElement(child)) {
      return;
    }

    if (func.call(context, child, index++)) {
      result = true;
    }
  });

  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.utils.ValidComponentChildren.toArray"></a>[function <span class="apidocSignatureSpan">react-bootstrap.utils.ValidComponentChildren.</span>toArray (children)](#apidoc.element.react-bootstrap.utils.ValidComponentChildren.toArray)
- description and source-code
```javascript
function toArray(children) {
  var result = [];

  _react2['default'].Children.forEach(children, function (child) {
    if (!_react2['default'].isValidElement(child)) {
      return;
    }

    result.push(child);
  });

  return result;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-bootstrap.utils.bootstrapUtils"></a>[module react-bootstrap.utils.bootstrapUtils](#apidoc.module.react-bootstrap.utils.bootstrapUtils)

#### <a name="apidoc.element.react-bootstrap.utils.bootstrapUtils._curry"></a>[function <span class="apidocSignatureSpan">react-bootstrap.utils.bootstrapUtils.</span>_curry (fn)](#apidoc.element.react-bootstrap.utils.bootstrapUtils._curry)
- description and source-code
```javascript
function curry(fn) {
  return function () {
    for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
      args[_key] = arguments[_key];
    }

    var last = args[args.length - 1];
    if (typeof last === 'function') {
      return fn.apply(undefined, args);
    }
    return function (Component) {
      return fn.apply(undefined, args.concat([Component]));
    };
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.utils.bootstrapUtils.addStyle"></a>[function <span class="apidocSignatureSpan">react-bootstrap.utils.bootstrapUtils.</span>addStyle (Component)](#apidoc.element.react-bootstrap.utils.bootstrapUtils.addStyle)
- description and source-code
```javascript
function addStyle(Component) {
  for (var _len2 = arguments.length, styleVariant = Array(_len2 > 1 ? _len2 - 1 : 0), _key2 = 1; _key2 < _len2; _key2++) {
    styleVariant[_key2 - 1] = arguments[_key2];
  }

  bsStyles(styleVariant, Component);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.utils.bootstrapUtils.bsClass"></a>[function <span class="apidocSignatureSpan">react-bootstrap.utils.bootstrapUtils.</span>bsClass ()](#apidoc.element.react-bootstrap.utils.bootstrapUtils.bsClass)
- description and source-code
```javascript
bsClass = function () {
  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  var last = args[args.length - 1];
  if (typeof last === 'function') {
    return fn.apply(undefined, args);
  }
  return function (Component) {
    return fn.apply(undefined, args.concat([Component]));
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.utils.bootstrapUtils.bsSizes"></a>[function <span class="apidocSignatureSpan">react-bootstrap.utils.bootstrapUtils.</span>bsSizes ()](#apidoc.element.react-bootstrap.utils.bootstrapUtils.bsSizes)
- description and source-code
```javascript
bsSizes = function () {
  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  var last = args[args.length - 1];
  if (typeof last === 'function') {
    return fn.apply(undefined, args);
  }
  return function (Component) {
    return fn.apply(undefined, args.concat([Component]));
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.utils.bootstrapUtils.bsStyles"></a>[function <span class="apidocSignatureSpan">react-bootstrap.utils.bootstrapUtils.</span>bsStyles ()](#apidoc.element.react-bootstrap.utils.bootstrapUtils.bsStyles)
- description and source-code
```javascript
bsStyles = function () {
  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  var last = args[args.length - 1];
  if (typeof last === 'function') {
    return fn.apply(undefined, args);
  }
  return function (Component) {
    return fn.apply(undefined, args.concat([Component]));
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.utils.bootstrapUtils.getClassSet"></a>[function <span class="apidocSignatureSpan">react-bootstrap.utils.bootstrapUtils.</span>getClassSet (props)](#apidoc.element.react-bootstrap.utils.bootstrapUtils.getClassSet)
- description and source-code
```javascript
function getClassSet(props) {
  var _classes;

  var classes = (_classes = {}, _classes[prefix(props)] = true, _classes);

  if (props.bsSize) {
    var bsSize = _StyleConfig.SIZE_MAP[props.bsSize] || props.bsSize;
    classes[prefix(props, bsSize)] = true;
  }

  if (props.bsStyle) {
    classes[prefix(props, props.bsStyle)] = true;
  }

  return classes;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.utils.bootstrapUtils.prefix"></a>[function <span class="apidocSignatureSpan">react-bootstrap.utils.bootstrapUtils.</span>prefix (props, variant)](#apidoc.element.react-bootstrap.utils.bootstrapUtils.prefix)
- description and source-code
```javascript
function prefix(props, variant) {
  !(props.bsClass != null) ? process.env.NODE_ENV !== 'production' ? (0, _invariant2['default'])(false, 'A 'bsClass' prop is required
 for this component') : (0, _invariant2['default'])(false) : void 0;
  return props.bsClass + (variant ? '-' + variant : '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.utils.bootstrapUtils.splitBsProps"></a>[function <span class="apidocSignatureSpan">react-bootstrap.utils.bootstrapUtils.</span>splitBsProps (props)](#apidoc.element.react-bootstrap.utils.bootstrapUtils.splitBsProps)
- description and source-code
```javascript
function splitBsProps(props) {
  var elementProps = {};
  (0, _entries2['default'])(props).forEach(function (_ref) {
    var propName = _ref[0],
        propValue = _ref[1];

    if (!isBsProp(propName)) {
      elementProps[propName] = propValue;
    }
  });

  return [getBsProps(props), elementProps];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-bootstrap.utils.bootstrapUtils.splitBsPropsAndOmit"></a>[function <span class="apidocSignatureSpan">react-bootstrap.utils.bootstrapUtils.</span>splitBsPropsAndOmit (props, omittedPropNames)](#apidoc.element.react-bootstrap.utils.bootstrapUtils.splitBsPropsAndOmit)
- description and source-code
```javascript
function splitBsPropsAndOmit(props, omittedPropNames) {
  var isOmittedProp = {};
  omittedPropNames.forEach(function (propName) {
    isOmittedProp[propName] = true;
  });

  var elementProps = {};
  (0, _entries2['default'])(props).forEach(function (_ref2) {
    var propName = _ref2[0],
        propValue = _ref2[1];

    if (!isBsProp(propName) && !isOmittedProp[propName]) {
      elementProps[propName] = propValue;
    }
  });

  return [getBsProps(props), elementProps];
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
