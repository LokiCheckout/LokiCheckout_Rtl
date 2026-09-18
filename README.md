# Yireo_Rtl

<!-- badges.specs.start -->
![Magento version](https://img.shields.io/badge/Magento-2.4.6%20%7C%202.4.9-orange)
![PHP version](https://img.shields.io/badge/PHP-8.2%E2%80%938.5-777BB4)
![License](https://img.shields.io/badge/License-OSL--3.0-blue)
![Latest Version](https://gitlab.yireo.com/loki-checkout/Yireo_Rtl/-/badges/release.svg)
<!-- badges.specs.end -->

> This module adds RTL support to Magento 2. It adds in a `dir="rtl"` attribute to the `<html>` tag.

**Thanks to @rbouma for setting this up.**

## Installation
Install this package via composer:
```bash
composer require yireo/magento2-rtl
```

Next, enable this module:
```bash
bin/magento module:enable Yireo_Rtl
```

## Usage
There is no usage of this module. The RTL-support that this module could be picked up by Tailwind 3+ by adding in Tailwind CSS classes like `rtl:mr-0 rtl:ml-4` (so, by adding a `rtl:` prefix). Note that with Loki, you can extend the `css_classes` of any HTML element in any PHTML template via the XML layout.


## Testing
To test this out, we have gone through the following steps:

- `composer require community-engineering/language-ar_sa`
- Add in a new Store View "Arab" with locale set to `ar_SA`


## Current status

<!-- badges.test.start -->
[![Static Tests](https://gitlab.yireo.com/loki-checkout/Yireo_Rtl/badges/main/pipeline.svg?job=static-tests)](https://gitlab.yireo.com/loki-checkout/Yireo_Rtl/-/pipelines)
[![Unit Tests](https://gitlab.yireo.com/loki-checkout/Yireo_Rtl/badges/main/pipeline.svg?job=unit-tests)](https://gitlab.yireo.com/loki-checkout/Yireo_Rtl/-/pipelines)
[![Integration Tests](https://gitlab.yireo.com/loki-checkout/Yireo_Rtl/badges/main/pipeline.svg?job=integration-tests)](https://gitlab.yireo.com/loki-checkout/Yireo_Rtl/-/pipelines)
[![Playwright](https://gitlab.yireo.com/loki-checkout/Yireo_Rtl/badges/main/pipeline.svg?job=playwright)](https://gitlab.yireo.com/loki-checkout/Yireo_Rtl/-/pipelines)
[![DI Compilation](https://gitlab.yireo.com/loki-checkout/Yireo_Rtl/badges/main/pipeline.svg?job=compile)](https://gitlab.yireo.com/loki-checkout/Yireo_Rtl/-/pipelines)
<!-- badges.test.end -->
