# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

<a name="3.2.3"></a>
## [3.2.3](https://github.com/kisenka/svg-sprite-loader/compare/v3.2.2...v3.2.3) (2017-08-18)


### Bug Fixes

* deal with deprecation warnings from webpack 3 ([d150035](https://github.com/kisenka/svg-sprite-loader/commit/d150035))



<a name="3.2.2"></a>
## [3.2.2](https://github.com/kisenka/svg-sprite-loader/compare/v3.2.1...v3.2.2) (2017-08-17)


### Bug Fixes

* **plugin:** webpack-manifest-plugin compatibility ([d88ac31](https://github.com/kisenka/svg-sprite-loader/commit/d88ac31))



<a name="3.2.1"></a>
## [3.2.1](https://github.com/kisenka/svg-sprite-loader/compare/v3.2.0...v3.2.1) (2017-08-16)


### Bug Fixes

* **runtime:** apply styles in dynamically appended symbols in Edge ([299bfe2](https://github.com/kisenka/svg-sprite-loader/commit/299bfe2))



<a name="3.2.0"></a>
# [3.2.0](https://github.com/kisenka/svg-sprite-loader/compare/v3.1.7...v3.2.0) (2017-08-16)


### Features

* **runtime:** add ability to create sprite from existing DOM node ([4056d7b](https://github.com/kisenka/svg-sprite-loader/commit/4056d7b))



<a name="3.1.7"></a>
## [3.1.7](https://github.com/kisenka/svg-sprite-loader/compare/v3.1.6...v3.1.7) (2017-08-15)


### Bug Fixes

* **runtime:** store global sprite object in window which allows to mount symbols in one place betwee ([13e3d47](https://github.com/kisenka/svg-sprite-loader/commit/13e3d47))



<a name="3.1.6"></a>
## [3.1.6](https://github.com/kisenka/webpack-svg-sprite-loader/compare/v3.1.5...v3.1.6) (2017-08-10)


### Bug Fixes

* **loader:** interpolate sprite filename properly ([b17e5e0](https://github.com/kisenka/webpack-svg-sprite-loader/commit/b17e5e0))



<a name="3.1.5"></a>
## [3.1.5](https://github.com/kisenka/webpack-svg-sprite-loader/compare/v3.1.4...v3.1.5) (2017-08-10)


### Bug Fixes

* **loader:** throw an exception if input is not valid SVG ([413246e](https://github.com/kisenka/webpack-svg-sprite-loader/commit/413246e)), closes [#170](https://github.com/kisenka/webpack-svg-sprite-loader/issues/170)



<a name="3.1.4"></a>
## [3.1.4](https://github.com/kisenka/webpack-svg-sprite-loader/compare/v3.1.3...v3.1.4) (2017-08-09)


### Bug Fixes

* **loader:** quick workaround for breaking changes in webpack@3.5 (`modules` prop dropped in ConcatenatedModule) ([f15030d](https://github.com/kisenka/webpack-svg-sprite-loader/commit/f15030d))



<a name="3.1.3"></a>
## [3.1.3](https://github.com/kisenka/webpack-svg-sprite-loader/compare/v3.1.2...v3.1.3) (2017-08-08)


### Bug Fixes

* **loader:** throw proper error message when runtime not found ([ef83fac](https://github.com/kisenka/webpack-svg-sprite-loader/commit/ef83fac))



<a name="3.1.2"></a>
## [3.1.2](https://github.com/kisenka/webpack-svg-sprite-loader/compare/v3.1.1...v3.1.2) (2017-08-05)


### Bug Fixes

* **loader:** decode entities in <style> tags ([36e6ba6](https://github.com/kisenka/webpack-svg-sprite-loader/commit/36e6ba6))



<a name="3.1.1"></a>
## [3.1.1](https://github.com/kisenka/webpack-svg-sprite-loader/compare/v3.1.0...v3.1.1) (2017-08-04)


### Bug Fixes

* **loader:** handle case when rule test is a function ([ace9f47](https://github.com/kisenka/webpack-svg-sprite-loader/commit/ace9f47))



<a name="3.1.0"></a>
# [3.1.0](https://github.com/kisenka/webpack-svg-sprite-loader/compare/v3.0.11...v3.1.0) (2017-08-03)


### Features

* **loader:** webpack 3 module concatenation interop in extract mode ([8a79536](https://github.com/kisenka/webpack-svg-sprite-loader/commit/8a79536))



<a name="3.0.11"></a>
## [3.0.11](https://github.com/kisenka/webpack-svg-sprite-loader/compare/v3.0.10...v3.0.11) (2017-08-03)


### Bug Fixes

* **runtime:** pass proper old URL in Angular workaround ([fbda8a2](https://github.com/kisenka/webpack-svg-sprite-loader/commit/fbda8a2))



<a name="3.0.10"></a>
## [3.0.10](https://github.com/kisenka/webpack-svg-sprite-loader/compare/v3.0.9...v3.0.10) (2017-07-31)

### Configuration

* **configuration:** add support for `symbolRegExp` pattern in symbol name interpolation ([e9de712](https://github.com/kisenka/svg-sprite-loader/commit/e9de712))



<a name="3.0.9"></a>
## [3.0.9](https://github.com/kisenka/webpack-svg-sprite-loader/compare/v3.0.8...v3.0.9) (2017-07-31)


### Bug Fixes

* **runtime:** fix IE/Edge rendering with SVG containing 'style' elements ([dcc9e27](https://github.com/kisenka/webpack-svg-sprite-loader/commit/dcc9e27))



<a name="3.0.8"></a>
## [3.0.8](https://github.com/kisenka/webpack-svg-sprite-loader/compare/v3.0.7...v3.0.8) (2017-07-28)


### Bug Fixes

* **runtime:** fallback to early sprite mount when document.body appears ([a71e67a](https://github.com/kisenka/webpack-svg-sprite-loader/commit/a71e67a))



<a name="3.0.7"></a>
## [3.0.7](https://github.com/kisenka/webpack-svg-sprite-loader/compare/v3.0.6...v3.0.7) (2017-07-24)


### Bug Fixes

* **runtime-generator:** return symbol id string in compat mode ([7641af0](https://github.com/kisenka/webpack-svg-sprite-loader/commit/7641af0))



<a name="3.0.6"></a>
## [3.0.6](https://github.com/kisenka/webpack-svg-sprite-loader/compare/v3.0.5...v3.0.6) (2017-07-17)


### Bug Fixes

* **loader:** add support for issuer when matching rules ([5d21b2f](https://github.com/kisenka/svg-sprite-loader/commit/5d21b2f))


<a name="3.0.5"></a>
## [3.0.5](https://github.com/kisenka/webpack-svg-sprite-loader/compare/v3.0.4...v3.0.5) (2017-06-02)


### Bug Fixes

* **loader:** replace sprite filename in whole source ([d4d4429](https://github.com/kisenka/webpack-svg-sprite-loader/commit/d4d4429))



<a name="3.0.4"></a>
## [3.0.4](https://github.com/kisenka/webpack-svg-sprite-loader/compare/v3.0.3...v3.0.4) (2017-05-31)


### Bug Fixes

* **utils:** properly replace path to image with sprite name on Windows ([6bdd6cd](https://github.com/kisenka/webpack-svg-sprite-loader/commit/6bdd6cd))



<a name="3.0.3"></a>
## [3.0.3](https://github.com/kisenka/webpack-svg-sprite-loader/compare/v3.0.2...v3.0.3) (2017-05-29)


### Bug Fixes

* **configuration:** proper configurator runtime selection based on \`target\` loader context ([a7365a2](https://github.com/kisenka/webpack-svg-sprite-loader/commit/a7365a2))



<a name="3.0.2"></a>
## [3.0.2](https://github.com/kisenka/webpack-svg-sprite-loader/compare/v3.0.1...v3.0.2) (2017-05-24)


### Bug Fixes

* **loader:** check module request properly in isModuleShouldBeExtracted with DLL Plugin ([ffb7b04](https://github.com/kisenka/webpack-svg-sprite-loader/commit/ffb7b04))



<a name="3.0.1"></a>
## [3.0.1](https://github.com/kisenka/webpack-svg-sprite-loader/compare/v3.0.0...v3.0.1) (2017-05-22)


### Bug Fixes

* **runtime-generator:** runtime generator in extract mode return object instead of string ([208b6dc](https://github.com/kisenka/webpack-svg-sprite-loader/commit/208b6dc))



<a name="3.0.0"></a>
# [3.0.0](https://github.com/kisenka/webpack-svg-sprite-loader/compare/v2.1.0...v3.0.0) (2017-05-21)


### Features

* **loader:** runtime exports an object in extract mode ([f0af0eb](https://github.com/kisenka/webpack-svg-sprite-loader/commit/f0af0eb))


### Reverts

* **tools:** rollback to standart-version :) ([b948e65](https://github.com/kisenka/webpack-svg-sprite-loader/commit/b948e65))


### BREAKING CHANGES

* **loader:** Generated runtime in extract mode is changed from string to object

ISSUES CLOSED: #123



<a name="2.1.0"></a>
# [2.1.0](https://github.com/kisenka/webpack-svg-sprite-loader/compare/v2.0.6...v2.1.0) (2017-05-13)


### Bug Fixes

* **multiple:** update svg-baker deps ([ead7d68](https://github.com/kisenka/webpack-svg-sprite-loader/commit/ead7d68)), closes [#101](https://github.com/kisenka/webpack-svg-sprite-loader/issues/101) [#103](https://github.com/kisenka/webpack-svg-sprite-loader/issues/103) [#112](https://github.com/kisenka/webpack-svg-sprite-loader/issues/112)
* **runtime:** update svg-baker-runtime with fixed angular workaround ([1543029](https://github.com/kisenka/webpack-svg-sprite-loader/commit/1543029)), closes [#103](https://github.com/kisenka/webpack-svg-sprite-loader/issues/103)


### Features

* add [hash] token substitution support ([87110f4](https://github.com/kisenka/webpack-svg-sprite-loader/commit/87110f4)), closes [#98](https://github.com/kisenka/webpack-svg-sprite-loader/issues/98) [#111](https://github.com/kisenka/webpack-svg-sprite-loader/issues/111)


<a name="2.0.6"></a>
## [2.0.6](https://github.com/kisenka/webpack-svg-sprite-loader/compare/v2.0.5...v2.0.6) (2017-05-13)


### Bug Fixes

* **configure:** use `browser-sprite``browser-symbol` for `electron-renderer` target ([b9a3ed0](https://github.com/kisenka/webpack-svg-sprite-loader/commit/b9a3ed0))


<a name="2.1.0-3"></a>
## [2.1.0-3](https://github.com/kisenka/webpack-svg-sprite-loader/compare/v2.1.0-2...v2.1.0-3) [beta] (2017-05-10)


### Bug Fixes

* **plugin:** properly replace paths on Windows ([0c70caa](https://github.com/kisenka/webpack-svg-sprite-loader/commit/0c70caa)), closes [#106](https://github.com/kisenka/webpack-svg-sprite-loader/issues/106)



<a name="2.1.0-2"></a>
## [2.1.0-2](https://github.com/kisenka/webpack-svg-sprite-loader/compare/v2.1.0-1...v2.1.0-2) [beta] (2017-05-09)


### Bug Fixes

* **loader:** symbol id interpolation ([18edd99](https://github.com/kisenka/webpack-svg-sprite-loader/commit/18edd99))



<a name="2.1.0-1"></a>
## [2.1.0-1](https://github.com/kisenka/webpack-svg-sprite-loader/compare/v2.1.0-0...v2.1.0-1) [beta] (2017-05-08)


### Bug Fixes

* **plugin:** properly generate symbol url in extract mode ([6af7230](https://github.com/kisenka/webpack-svg-sprite-loader/commit/6af7230))



<a name="2.1.0-0"></a>
## [2.1.0-0](https://github.com/kisenka/webpack-svg-sprite-loader/compare/v2.0.5...v2.1.0-0) [beta] (2017-05-07)


### Bug Fixes

* **utils:** fix default import ([0c34daa](https://github.com/kisenka/webpack-svg-sprite-loader/commit/0c34daa))


### Features

* **interop:** extract-text-webpack-plugin & html-webpack-plugin interop ([a38fdcc](https://github.com/kisenka/webpack-svg-sprite-loader/commit/a38fdcc))
* **interop:** extract-text-webpack-plugin with allChunks: true interoperability ([63d347d](https://github.com/kisenka/webpack-svg-sprite-loader/commit/63d347d))
* **spritehash:** add ability to use `[spritehash]` substitution token in spriteFilename ([f9eba1b](https://github.com/kisenka/webpack-svg-sprite-loader/commit/f9eba1b))


<a name="2.0.5"></a>
## [2.0.5](https://github.com/kisenka/webpack-svg-sprite-loader/compare/v2.0.4...v2.0.5) (2017-05-05)
