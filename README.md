# api documentation for  [gulp-template (v4.0.0)](https://github.com/sindresorhus/gulp-template#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-template.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-template) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-template.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-template)
#### Render/precompile Lo-Dash/Underscore templates

[![NPM](https://nodei.co/npm/gulp-template.png?downloads=true)](https://www.npmjs.com/package/gulp-template)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-template/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-gulp-template_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-template/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-template/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-template/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sindre Sorhus",
        "email": "sindresorhus@gmail.com",
        "url": "sindresorhus.com"
    },
    "bugs": {
        "url": "https://github.com/sindresorhus/gulp-template/issues"
    },
    "dependencies": {
        "gulp-util": "^3.0.0",
        "lodash": "^4.8.2",
        "through2": "^2.0.0"
    },
    "description": "Render/precompile Lo-Dash/Underscore templates",
    "devDependencies": {
        "gulp-data": "^1.0.2",
        "mocha": "*",
        "xo": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "05de36808c6fb9966578d5a94ee72cee08cdc53b",
        "tarball": "https://registry.npmjs.org/gulp-template/-/gulp-template-4.0.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "e032d9e29e502157f6289e7c2b5684163b33d731",
    "homepage": "https://github.com/sindresorhus/gulp-template#readme",
    "keywords": [
        "gulpplugin",
        "lodash",
        "underscore",
        "template",
        "compile",
        "html",
        "render",
        "rendering",
        "precompile"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "sindresorhus",
            "email": "sindresorhus@gmail.com"
        }
    ],
    "name": "gulp-template",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sindresorhus/gulp-template.git"
    },
    "scripts": {
        "test": "xo && mocha"
    },
    "version": "4.0.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module gulp-template](#apidoc.module.gulp-template)
1.  [function <span class="apidocSignatureSpan">gulp-template.</span>precompile (options)](#apidoc.element.gulp-template.precompile)



# <a name="apidoc.module.gulp-template"></a>[module gulp-template](#apidoc.module.gulp-template)

#### <a name="apidoc.element.gulp-template.precompile"></a>[function <span class="apidocSignatureSpan">gulp-template.</span>precompile (options)](#apidoc.element.gulp-template.precompile)
- description and source-code
```javascript
precompile = function (options) {
	return compile(options);
}
```
- example usage
```shell
...

## API

### template(data, [options])

Render a template using the provided 'data'.

### template.precompile([options])

Precompile a template for rendering dynamically at a later time.

#### data

Type: 'object'
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
