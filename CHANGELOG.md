# Changelog

_This file has been auto-generated from the contents of changelog.json_

## 2.1.0

### Feature

* allow multiple version checking url's to cater for download sources that might have different mechanisms for fetching information about latest driver versions
* new path variables for having partial version in file names: major (X), major-minor (X.Y)
* retry driver download when download failed for some reason (2 retries)

### Maintenance

* introduced the use of Static Code Analysis tools
* code downgraded so to make the package installable on relatively old php versions

Links: [src](https://github.com/vaimo/webdriver-binary-downloader/tree/2.1.0) [diff](https://github.com/vaimo/webdriver-binary-downloader/compare/2.0.0...2.1.0)

## 2.0.0 (2018-12-12)

### Breaking

* (config) version polling output parser switched to use RegEx pattern matching instead of relying on sscanf

### Feature

* allow driver version polling to use version aliases (required for some drivers that use multiple versioning schemes (like EdgeDriver))
* try version polling with escaped path on Windows if normal call results in blank response

Links: [src](https://github.com/vaimo/webdriver-binary-downloader/tree/2.0.0) [diff](https://github.com/vaimo/webdriver-binary-downloader/compare/1.0.0...2.0.0)

## 1.0.0 (2018-12-12)

### Feature

* allow webdriver binary download based on passed-in configuration

Links: [src](https://github.com/vaimo/webdriver-binary-downloader/tree/1.0.0) [diff](https://github.com/vaimo/webdriver-binary-downloader/compare/7d40067f71ec830a9589bf63b6117753c1e77746...1.0.0)