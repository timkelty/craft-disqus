# Disqus Changelog

## 1.1.2 - 2019.08.15
### Added
* Fixed a regression that could cause an exception to be thrown when editing the plugin settings

## 1.1.1 - 2019.08.10
### Added
* `disqusPublicKey` and `disqusSecretKey` can now be environmental variables

### Changed
* Fixed a deprecation error for `craft.config.get()`

## 1.1.0 - 2019.01.04
### Added
* Disqus JavaScript is now lazy loaded, only when the comments scroll into the viewport

## 1.0.7 - 2018.02.01
### Added
* Renamed the composer package name to `craft-disqus`

## 1.0.6 - 2018.01.12
### Added
* Added the `disqusCount()` and `craft.disqus.disqusCount()` for getting the number of comments for a given Disqus thread

### Changed
* Cleaned up the code, added try/catch wrappers

## 1.0.5 - 2017.12.06
### Changed
* Updated to require craftcms/cms `^3.0.0-RC1`
* Switched to `Craft::$app->view->registerTwigExtension` to register the Twig extension

## 1.0.4 - 2017.08.05
### Changed
* Craft 3 beta 23 compatibility

## 1.0.3 - 2017.07.12
### Changed
* Craft 3 beta 20 compatibility

## 1.0.2 - 2017.03.24
### Changed
* `hasSettings` -> `hasCpSettings` for Craft 3 beta 8 compatibility
* Added Craft 3 beta 8 compatible settings
* Modified config service calls for Craft 3 beta 8

## 1.0.1 - 2017.03.20
### Changed
* Fixed broken SSO implementation by moving it all to one template
* Deprecated the separate `outputSSOTag()` functions
* Removed errant (and unneeded) `|escape('js')` filters
* Updated `README.md`

## 1.0.0 - 2017.03.18
### Added
* Initial release
