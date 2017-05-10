# Magento 2 Slovenian Translations

![Progress](http://progressed.io/bar/100?title=completed)
[![Magento Marketplace](https://img.shields.io/badge/Magento-Marketplace-orange.svg)][marketplace]
[![Open Software License v. 3.0](https://img.shields.io/badge/License-OSL--3.0-blue.svg)][license]
[![Latest Release](https://img.shields.io/github/release/symfony-si/magento2-sl_si.svg)][latest-release]

Slovenian (Slovenia) - `sl_SI` translations for [Magento][magento] Community Edition
2.x.

Translations follow Slovenian grammar and translation rules from [Lugos][lugos].

## Installation

### Option 1: Composer

To install this language package with [Composer](https://getcomposer.org), run
the following in your Magento 2 root folder:

```bash
$ composer require symfony-si/magento2-sl_si
$ bin/magento setup:static-content:deploy sl_SI
$ bin/magento cache:clean
$ bin/magento setup:upgrade
$ bin/magento cache:flush
```

### Option 2: Manual Installation

Download the ZIP file of the latest available [release][latest-release] and extract it to your
Magento root folder at `app/i18n/SymfonySi/sl_SI`. Also don't forget to deploy
static files for the locale, run the upgrade setup script and cleaning cache:

```bash
$ bin/magento setup:static-content:deploy sl_SI
$ bin/magento cache:clean
$ bin/magento setup:upgrade
$ bin/magento cache:flush
```

### Option 3: Marketplace

Magento [Marketplace][marketplace] stores free and paid extensions. Coming up
soon...

## See Also

* [Magento user guide - Adding a Language](http://devdocs.magento.com/guides/v2.1/frontend-dev-guide/translations/xlate.html)
* [Translation mechanism in Magento 2](https://gist.github.com/antonmakarenko/7538216)
* [Magento Connect](https://www.magentocommerce.com/magento-connect/magento-2) - Magento
  2 section on Magento Connect. There is a new Marketplace to search for Magento
  2 extensions though.
* [Magento 1 Slovenian Translations](https://github.com/symfony-si/magento1-sl-si)
* [Crowdin](https://crowdin.com/project/magento-2) - Community effort to
  centralize Magento translations. Inactive, new target languages are not being
  added.

## Supported Magento versions

The following Magento Community Edition versions work with this translation:

* `2.1.5`
* `2.1.4`
* `2.1.3`
* `2.1.2`
* `2.1.1`
* `2.1.0`
* `2.0.4`
* `2.0.3`
* `2.0.2`
* `2.0.1`
* `2.0.0`

## Contributing and License

Project is open sourced and contributors are welcome. Please check the
[contributing](CONTRIBUTING.md) document how to help.

This repository is released under the [Open Software License v. 3.0][license].


[license]: https://github.com/symfony-si/magento2-sl_si/blob/master/LICENSE
[lugos]: https://wiki.lugos.si/slovenjenje:pravila
[magento]: https://magento.com/
[marketplace]: https://marketplace.magento.com
[latest-release]: https://github.com/symfony-si/magento2-sl_si/releases/latest
