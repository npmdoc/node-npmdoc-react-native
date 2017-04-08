# api documentation for  [react-native (v0.43.2)](https://github.com/facebook/react-native#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-native.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-native) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-native.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-native)
#### A framework for building native apps using React

[![NPM](https://nodei.co/npm/react-native.png?downloads=true)](https://www.npmjs.com/package/react-native)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-native/build/screenCapture.buildNpmdoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-react-native%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-native/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-native/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-native/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "react-native": "local-cli/wrong-react-native.js"
    },
    "bugs": {
        "url": "https://github.com/facebook/react-native/issues"
    },
    "dependencies": {
        "absolute-path": "^0.0.0",
        "art": "^0.10.0",
        "async": "^2.0.1",
        "babel-core": "^6.21.0",
        "babel-generator": "^6.21.0",
        "babel-plugin-external-helpers": "^6.18.0",
        "babel-plugin-syntax-trailing-function-commas": "^6.20.0",
        "babel-plugin-transform-async-to-generator": "6.16.0",
        "babel-plugin-transform-flow-strip-types": "^6.21.0",
        "babel-plugin-transform-object-rest-spread": "^6.20.2",
        "babel-polyfill": "^6.20.0",
        "babel-preset-es2015-node": "^6.1.1",
        "babel-preset-fbjs": "^2.1.0",
        "babel-preset-react-native": "^1.9.1",
        "babel-register": "^6.18.0",
        "babel-runtime": "^6.20.0",
        "babel-traverse": "^6.21.0",
        "babel-types": "^6.21.0",
        "babylon": "^6.14.1",
        "base64-js": "^1.1.2",
        "bser": "^1.0.2",
        "chalk": "^1.1.1",
        "commander": "^2.9.0",
        "concat-stream": "^1.6.0",
        "connect": "^2.8.3",
        "core-js": "^2.2.2",
        "debug": "^2.2.0",
        "denodeify": "^1.2.1",
        "event-target-shim": "^1.0.5",
        "fbjs": "~0.8.9",
        "fbjs-scripts": "^0.7.0",
        "form-data": "^2.1.1",
        "fs-extra": "^0.26.2",
        "glob": "^5.0.15",
        "graceful-fs": "^4.1.3",
        "image-size": "^0.3.5",
        "immutable": "~3.7.6",
        "imurmurhash": "^0.1.4",
        "inquirer": "^0.12.0",
        "jest-haste-map": "19.0.0",
        "joi": "^6.6.1",
        "json-stable-stringify": "^1.0.1",
        "json5": "^0.4.0",
        "left-pad": "^1.1.3",
        "lodash": "^4.16.6",
        "mime": "^1.3.4",
        "mime-types": "2.1.11",
        "minimist": "^1.2.0",
        "mkdirp": "^0.5.1",
        "node-fetch": "^1.3.3",
        "npmlog": "^2.0.4",
        "opn": "^3.0.2",
        "optimist": "^0.6.1",
        "plist": "^1.2.0",
        "promise": "^7.1.1",
        "react-clone-referenced-element": "^1.0.1",
        "react-devtools-core": "^2.0.8",
        "react-timer-mixin": "^0.13.2",
        "react-transform-hmr": "^1.0.4",
        "rebound": "^0.0.13",
        "regenerator-runtime": "^0.9.5",
        "request": "^2.79.0",
        "rimraf": "^2.5.4",
        "sane": "~1.4.1",
        "semver": "^5.0.3",
        "shell-quote": "1.6.1",
        "source-map": "^0.5.6",
        "stacktrace-parser": "^0.1.3",
        "temp": "0.8.3",
        "throat": "^3.0.0",
        "uglify-js": "^2.6.2",
        "whatwg-fetch": "^1.0.0",
        "wordwrap": "^1.0.0",
        "worker-farm": "^1.3.1",
        "write-file-atomic": "^1.2.0",
        "ws": "^1.1.0",
        "xcode": "^0.8.9",
        "xmldoc": "^0.4.0",
        "xpipe": "^1.0.5",
        "yargs": "^6.4.0"
    },
    "description": "A framework for building native apps using React",
    "devDependencies": {
        "babel-eslint": "^7.1.1",
        "eslint": "^3.8.1",
        "eslint-plugin-babel": "^3.3.0",
        "eslint-plugin-flowtype": "^2.20.0",
        "eslint-plugin-react": "^6.4.1",
        "flow-bin": "^0.40.0",
        "jest": "19.0.2",
        "jest-repl": "19.0.2",
        "jest-runtime": "19.0.2",
        "mock-fs": "^3.11.0",
        "react": "16.0.0-alpha.6",
        "react-dom": "16.0.0-alpha.6",
        "react-test-renderer": "16.0.0-alpha.6",
        "shelljs": "0.6.0",
        "sinon": "^2.0.0-pre.2"
    },
    "directories": {},
    "dist": {
        "shasum": "83cdb23d7a9cba207acbb52ad2f0b167df9b42b0",
        "tarball": "https://registry.npmjs.org/react-native/-/react-native-0.43.2.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "files": [
        ".flowconfig",
        "android",
        "cli.js",
        "flow",
        "init.sh",
        "ios-install-third-party.sh",
        "jest-preset.json",
        "jest",
        "lib",
        "setupBabel.js",
        "Libraries",
        "LICENSE",
        "local-cli",
        "packager",
        "PATENTS",
        "react.gradle",
        "React.podspec",
        "React",
        "ReactAndroid",
        "ReactCommon",
        "README.md"
    ],
    "homepage": "https://github.com/facebook/react-native#readme",
    "jest": {
        "automock": true,
        "transform": {
            ".*": "./jest/preprocessor.js"
        },
        "setupFiles": [
            "./jest/setup.js"
        ],
        "timers": "fake",
        "moduleNameMapper": {
            "^React$": "<rootDir>/Libraries/react-native/React.js",
            "^[./a-zA-Z0-9$_-]+\\.png$": "RelativeImageStub"
        },
        "testPathIgnorePatterns": [
            "Libraries/Renderer",
            "/node_modules/",
            "/website/",
            "local-cli/templates/"
        ],
        "haste": {
            "defaultPlatform": "ios",
            "providesModuleNodeModules": [
                "react-native"
            ],
            "platforms": [
                "ios",
                "android"
            ]
        },
        "modulePathIgnorePatterns": [
            "Libraries/react-native/",
            "/node_modules/(?!react|fbjs|react-native|react-transform-hmr|core-js|promise)/",
            "node_modules/react/node_modules/fbjs/",
            "node_modules/react/lib/ReactDOM.js",
            "node_modules/fbjs/lib/Map.js",
            "node_modules/fbjs/lib/Promise.js",
            "node_modules/fbjs/lib/fetch.js",
            "node_modules/fbjs/lib/ErrorUtils.js",
            "node_modules/fbjs/lib/URI.js",
            "node_modules/fbjs/lib/Deferred.js",
            "node_modules/fbjs/lib/PromiseMap.js",
            "node_modules/fbjs/lib/UserAgent.js",
            "node_modules/fbjs/lib/areEqual.js",
            "node_modules/fbjs/lib/base62.js",
            "node_modules/fbjs/lib/crc32.js",
            "node_modules/fbjs/lib/everyObject.js",
            "node_modules/fbjs/lib/fetchWithRetries.js",
            "node_modules/fbjs/lib/filterObject.js",
            "node_modules/fbjs/lib/flattenArray.js",
            "node_modules/fbjs/lib/forEachObject.js",
            "node_modules/fbjs/lib/isEmpty.js",
            "node_modules/fbjs/lib/nullthrows.js",
            "node_modules/fbjs/lib/removeFromArray.js",
            "node_modules/fbjs/lib/resolveImmediate.js",
            "node_modules/fbjs/lib/someObject.js",
            "node_modules/fbjs/lib/sprintf.js",
            "node_modules/fbjs/lib/xhrSimpleDataSerializer.js",
            "node_modules/jest-cli",
            "node_modules/react/dist",
            "node_modules/fbjs/.*/__mocks__/",
            "node_modules/fbjs/node_modules/",
            "<rootDir>/website/"
        ],
        "unmockedModulePathPatterns": [
            "node_modules/react/",
            "Libraries/Renderer",
            "promise",
            "source-map",
            "fastpath",
            "denodeify",
            "fbjs",
            "sinon"
        ]
    },
    "license": "BSD-3-Clause",
    "main": "Libraries/react-native/react-native-implementation.js",
    "maintainers": [
        {
            "name": "amasad",
            "email": "amjad.masad@gmail.com"
        },
        {
            "name": "bestander",
            "email": "bestander@gmail.com"
        },
        {
            "name": "brentvatne",
            "email": "brentvatne@gmail.com"
        },
        {
            "name": "ericvicenti",
            "email": "ericvicenti@gmail.com"
        },
        {
            "name": "fb",
            "email": "opensource+npm@fb.com"
        },
        {
            "name": "foghina",
            "email": "felix@oghina.com"
        },
        {
            "name": "frantic",
            "email": "alex.frantic@gmail.com"
        },
        {
            "name": "ide",
            "email": "ide+npm@jameside.com"
        },
        {
            "name": "mkonicek",
            "email": "martin.konicek@gmail.com"
        },
        {
            "name": "spicyj",
            "email": "ben@benalpert.com"
        },
        {
            "name": "vjeux",
            "email": "vjeuxx@gmail.com"
        }
    ],
    "name": "react-native",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "16.0.0-alpha.6"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/facebook/react-native.git"
    },
    "scripts": {
        "flow": "flow",
        "lint": "eslint Examples/ Libraries/",
        "start": "/usr/bin/env bash -c './packager/packager.sh \"$@\" || true' --",
        "test": "jest",
        "test-android-all": "npm run test-android-build && npm run test-android-run-unit && npm run test-android-run-instrumentation && npm run test-android-run-e2e",
        "test-android-build": "docker build -t react/android -f ContainerShip/Dockerfile.android .",
        "test-android-e2e": "npm run test-android-build && npm run test-android-run-e2e",
        "test-android-instrumentation": "npm run test-android-build && npm run test-android-run-instrumentation",
        "test-android-run-e2e": "docker run -it react/android bash ContainerShip/scripts/run-ci-e2e-tests.sh --android --js",
        "test-android-run-instrumentation": "docker run --cap-add=SYS_ADMIN -it react/android bash ContainerShip/scripts/run-android-docker-instrumentation-tests.sh",
        "test-android-run-unit": "docker run --cap-add=SYS_ADMIN -it react/android bash ContainerShip/scripts/run-android-docker-unit-tests.sh",
        "test-android-setup": "docker pull containership/android-base:latest",
        "test-android-unit": "npm run test-android-build && npm run test-android-run-unit"
    },
    "version": "0.43.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module react-native](#apidoc.module.react-native)
1.  [function <span class="apidocSignatureSpan">react-native.</span>babelRegisterOnly (onlyList)](#apidoc.element.react-native.babelRegisterOnly)
1.  [function <span class="apidocSignatureSpan">react-native.</span>setupBabel ()](#apidoc.element.react-native.setupBabel)
1.  object <span class="apidocSignatureSpan">react-native.</span>preprocessor
1.  object <span class="apidocSignatureSpan">react-native.</span>react_packager
1.  object <span class="apidocSignatureSpan">react-native.</span>transformer

#### [module react-native.babelRegisterOnly](#apidoc.module.react-native.babelRegisterOnly)
1.  [function <span class="apidocSignatureSpan">react-native.</span>babelRegisterOnly (onlyList)](#apidoc.element.react-native.babelRegisterOnly.babelRegisterOnly)
1.  [function <span class="apidocSignatureSpan">react-native.babelRegisterOnly.</span>config (onlyList)](#apidoc.element.react-native.babelRegisterOnly.config)

#### [module react-native.preprocessor](#apidoc.module.react-native.preprocessor)
1.  [function <span class="apidocSignatureSpan">react-native.preprocessor.</span>getCacheKey (src, file, configString)](#apidoc.element.react-native.preprocessor.getCacheKey)
1.  [function <span class="apidocSignatureSpan">react-native.preprocessor.</span>process (src, file)](#apidoc.element.react-native.preprocessor.process)

#### [module react-native.react_packager](#apidoc.module.react-native.react_packager)
1.  [function <span class="apidocSignatureSpan">react-native.react_packager.</span>buildBundle (options, bundleOptions)](#apidoc.element.react-native.react_packager.buildBundle)
1.  [function <span class="apidocSignatureSpan">react-native.react_packager.</span>createServer (options)](#apidoc.element.react-native.react_packager.createServer)
1.  [function <span class="apidocSignatureSpan">react-native.react_packager.</span>getOrderedDependencyPaths (options, bundleOptions)](#apidoc.element.react-native.react_packager.getOrderedDependencyPaths)
1.  object <span class="apidocSignatureSpan">react-native.react_packager.</span>Logger

#### [module react-native.setupBabel](#apidoc.module.react-native.setupBabel)
1.  [function <span class="apidocSignatureSpan">react-native.</span>setupBabel ()](#apidoc.element.react-native.setupBabel.setupBabel)
1.  [function <span class="apidocSignatureSpan">react-native.setupBabel.</span>buildRegExps (basePath, dirPaths)](#apidoc.element.react-native.setupBabel.buildRegExps)
1.  [function <span class="apidocSignatureSpan">react-native.setupBabel.</span>getOnlyList ()](#apidoc.element.react-native.setupBabel.getOnlyList)

#### [module react-native.transformer](#apidoc.module.react-native.transformer)
1.  [function <span class="apidocSignatureSpan">react-native.transformer.</span>transform (src, filename, options)](#apidoc.element.react-native.transformer.transform)



# <a name="apidoc.module.react-native"></a>[module react-native](#apidoc.module.react-native)

#### <a name="apidoc.element.react-native.babelRegisterOnly"></a>[function <span class="apidocSignatureSpan">react-native.</span>babelRegisterOnly (onlyList)](#apidoc.element.react-native.babelRegisterOnly)
- description and source-code
```javascript
function registerOnly(onlyList) {
  require('babel-register')(config(onlyList));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-native.setupBabel"></a>[function <span class="apidocSignatureSpan">react-native.</span>setupBabel ()](#apidoc.element.react-native.setupBabel)
- description and source-code
```javascript
function setupBabel() {
  babelRegisterOnly(getOnlyList());
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-native.babelRegisterOnly"></a>[module react-native.babelRegisterOnly](#apidoc.module.react-native.babelRegisterOnly)

#### <a name="apidoc.element.react-native.babelRegisterOnly.babelRegisterOnly"></a>[function <span class="apidocSignatureSpan">react-native.</span>babelRegisterOnly (onlyList)](#apidoc.element.react-native.babelRegisterOnly.babelRegisterOnly)
- description and source-code
```javascript
function registerOnly(onlyList) {
  require('babel-register')(config(onlyList));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-native.babelRegisterOnly.config"></a>[function <span class="apidocSignatureSpan">react-native.babelRegisterOnly.</span>config (onlyList)](#apidoc.element.react-native.babelRegisterOnly.config)
- description and source-code
```javascript
function config(onlyList) {
  _only = _only.concat(onlyList);
  return {
    presets: ['es2015-node'],
    plugins: [
      'transform-flow-strip-types',
      'syntax-trailing-function-commas',
      'transform-object-rest-spread',
      'transform-async-to-generator',
    ],
    only: _only,
    retainLines: true,
    sourceMaps: 'inline',
    babelrc: false,
  };
}
```
- example usage
```shell
...
const createCacheKeyFunction = require('fbjs-scripts/jest/createCacheKeyFunction');
const path = require('path');

const nodeFiles = RegExp([
'/local-cli/',
'/packager/(?!src/Resolver/polyfills/)',
].join('|'));
const nodeOptions = babelRegisterOnly.config([nodeFiles]);

babelRegisterOnly([]);
// has to be required after setting up babelRegisterOnly
const transformer = require('../packager/transformer.js');

module.exports = {
process(src, file) {
...
```



# <a name="apidoc.module.react-native.preprocessor"></a>[module react-native.preprocessor](#apidoc.module.react-native.preprocessor)

#### <a name="apidoc.element.react-native.preprocessor.getCacheKey"></a>[function <span class="apidocSignatureSpan">react-native.preprocessor.</span>getCacheKey (src, file, configString)](#apidoc.element.react-native.preprocessor.getCacheKey)
- description and source-code
```javascript
(src, file, configString) => crypto.createHash('md5')
.update(cacheKey)
.update(src + file + configString)
.digest('hex')
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-native.preprocessor.process"></a>[function <span class="apidocSignatureSpan">react-native.preprocessor.</span>process (src, file)](#apidoc.element.react-native.preprocessor.process)
- description and source-code
```javascript
process(src, file) {
  if (nodeFiles.test(file)) { // node specific transforms only
    return babel.transform(
      src,
      Object.assign({filename: file}, nodeOptions)
    ).code;
  }

  return transformer.transform(src, file, {inlineRequires: true}).code;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-native.react_packager"></a>[module react-native.react_packager](#apidoc.module.react-native.react_packager)

#### <a name="apidoc.element.react-native.react_packager.buildBundle"></a>[function <span class="apidocSignatureSpan">react-native.react_packager.</span>buildBundle (options, bundleOptions)](#apidoc.element.react-native.react_packager.buildBundle)
- description and source-code
```javascript
buildBundle = function (options, bundleOptions) {
  var server = createNonPersistentServer(options);
  return server.buildBundle(bundleOptions).
  then(p => {
    server.end();
    return p;
  });
}
```
- example usage
```shell
...
  projectRoots: Array<string>,
  reporter: Reporter,
  watch?: boolean,
};

exports.buildBundle = function(options: Options, bundleOptions: {}) {
  var server = createNonPersistentServer(options);
  return server.buildBundle(bundleOptions)
    .then(p => {
      server.end();
      return p;
    });
};

exports.getOrderedDependencyPaths = function(options: Options, bundleOptions: {}) {
...
```

#### <a name="apidoc.element.react-native.react_packager.createServer"></a>[function <span class="apidocSignatureSpan">react-native.react_packager.</span>createServer (options)](#apidoc.element.react-native.react_packager.createServer)
- description and source-code
```javascript
function createServer(options) {
  // the debug module is configured globally, we need to enable debugging
  // *before* requiring any packages that use 'debug' for logging
  if (options.verbose) {
    enableDebug();
  }

  // Some callsites may not be Flowified yet.
  invariant(options.reporter != null, 'createServer() requires reporter');
  const serverOptions = Object.assign({}, options);
  delete serverOptions.verbose;
  var Server = require('./src/Server');
  return new Server(serverOptions);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-native.react_packager.getOrderedDependencyPaths"></a>[function <span class="apidocSignatureSpan">react-native.react_packager.</span>getOrderedDependencyPaths (options, bundleOptions)](#apidoc.element.react-native.react_packager.getOrderedDependencyPaths)
- description and source-code
```javascript
getOrderedDependencyPaths = function (options, bundleOptions) {
  var server = createNonPersistentServer(options);
  return server.getOrderedDependencyPaths(bundleOptions).
  then(function (paths) {
    server.end();
    return paths;
  });
}
```
- example usage
```shell
...
      server.end();
      return p;
    });
};

exports.getOrderedDependencyPaths = function(options: Options, bundleOptions: {}) {
  var server = createNonPersistentServer(options);
  return server.getOrderedDependencyPaths(bundleOptions)
    .then(function(paths) {
      server.end();
      return paths;
    });
};

function enableDebug() {
...
```



# <a name="apidoc.module.react-native.setupBabel"></a>[module react-native.setupBabel](#apidoc.module.react-native.setupBabel)

#### <a name="apidoc.element.react-native.setupBabel.setupBabel"></a>[function <span class="apidocSignatureSpan">react-native.</span>setupBabel ()](#apidoc.element.react-native.setupBabel.setupBabel)
- description and source-code
```javascript
function setupBabel() {
  babelRegisterOnly(getOnlyList());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-native.setupBabel.buildRegExps"></a>[function <span class="apidocSignatureSpan">react-native.setupBabel.</span>buildRegExps (basePath, dirPaths)](#apidoc.element.react-native.setupBabel.buildRegExps)
- description and source-code
```javascript
function buildRegExps(basePath, dirPaths) {
  return dirPaths.map(folderPath =>
    // Babel 'only' option works with forward slashes in the RegExp so replace
    // backslashes for Windows.
    new RegExp('^${escapeRegExp(path.resolve(basePath, folderPath).replace(/\\/g, '/'))}')
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-native.setupBabel.getOnlyList"></a>[function <span class="apidocSignatureSpan">react-native.setupBabel.</span>getOnlyList ()](#apidoc.element.react-native.setupBabel.getOnlyList)
- description and source-code
```javascript
function getOnlyList() {
  return buildRegExps(__dirname, BABEL_ENABLED_PATHS);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-native.transformer"></a>[module react-native.transformer](#apidoc.module.react-native.transformer)

#### <a name="apidoc.element.react-native.transformer.transform"></a>[function <span class="apidocSignatureSpan">react-native.transformer.</span>transform (src, filename, options)](#apidoc.element.react-native.transformer.transform)
- description and source-code
```javascript
function transform(src, filename, options) {
  options = options || {};

  const OLD_BABEL_ENV = process.env.BABEL_ENV;
  process.env.BABEL_ENV = options.dev ? 'development' : 'production';

  try {
    const babelConfig = buildBabelConfig(filename, options);
    const { ast } = babel.transform(src, babelConfig);
    const result = generate(ast, {
      comments: false,
      compact: false,
      filename,
      sourceFileName: filename,
      sourceMaps: true },
    src);

    return {
      ast,
      code: result.code,
      filename,
      map: options.generateSourceMaps ? result.map : result.rawMappings.map(compactMapping) };

  } finally {
    process.env.BABEL_ENV = OLD_BABEL_ENV;
  }
}
```
- example usage
```shell
...
babelRegisterOnly([]);
// has to be required after setting up babelRegisterOnly
const transformer = require('../packager/transformer.js');

module.exports = {
process(src, file) {
  if (nodeFiles.test(file)) { // node specific transforms only
    return babel.transform(
      src,
      Object.assign({filename: file}, nodeOptions)
    ).code;
  }

  return transformer.transform(src, file, {inlineRequires: true}).code;
},
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
