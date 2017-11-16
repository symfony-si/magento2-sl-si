# Magento 2 Slovenian translations

![Progress](http://progressed.io/bar/100?title=completed)
[![Open Software License v. 3.0](https://img.shields.io/badge/License-OSL--3.0-blue.svg)][license]
[![Latest Release](https://img.shields.io/github/release/symfony-si/magento2-sl-si.svg)][latest-release]

Slovenian (Slovenia) - `sl_SI` translations for [Magento](https://magento.com/)
Community Edition 2.x.

Translations follow Slovenian grammar and translation rules from
[Lugos](https://wiki.lugos.si/slovenjenje:pravila).

## Installation

### Option 1: Composer

To install this language package with [Composer](https://getcomposer.org), run
the following in your Magento 2 root folder:

```bash
composer require symfonysi/magento2-sl-si
bin/magento setup:static-content:deploy sl_SI
bin/magento cache:clean
bin/magento setup:upgrade
bin/magento cache:flush
```

### Option 2: Manual installation

Download the ZIP file of the latest available [release][latest-release] and extract
it to your Magento root folder at `app/i18n/SymfonySi/sl_SI`. Also don't forget
to deploy static files for the locale, run the upgrade setup script and cleaning
cache:

```bash
bin/magento setup:static-content:deploy sl_SI
bin/magento cache:clean
bin/magento setup:upgrade
bin/magento cache:flush
```

## See also

* [Magento user guide - Adding a Language](http://devdocs.magento.com/guides/v2.2/frontend-dev-guide/translations/xlate.html)
* [Translation mechanism in Magento 2](https://gist.github.com/antonmakarenko/7538216)
* [Magento 1 Slovenian Translations](https://github.com/symfony-si/magento1-sl-si)
* [Crowdin](https://crowdin.com/project/magento-2) - Community effort to
  centralize Magento translations. Inactive, new target languages are not being
  added.

## Supported Magento versions

Supported Magento Community Edition `2.2`, `2.1`, and `2.0` versions:

* `2.2.1`, `2.2.0`
* `2.1.10`, `2.1.9`, `2.1.8`, `2.1.7`, `2.1.6`, `2.1.5`, `2.1.4`, `2.1.3`, `2.1.2`, `2.1.1`, `2.1.0`
* `2.0.4`, `2.0.3`, `2.0.2`, `2.0.1`, `2.0.0`

## Contributing and License

Project is open sourced and contributors are welcome. Please check the
[contributing](https://github.com/symfony-si/magento2-sl-si/blob/master/CONTRIBUTING.md)
document how to help.

This repository is released under the [Open Software License v. 3.0][license].


[license]: https://github.com/symfony-si/magento2-sl-si/blob/master/LICENSE
[latest-release]: https://github.com/symfony-si/magento2-sl-si/releases/latest
