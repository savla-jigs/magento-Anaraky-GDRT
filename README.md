# Magento: Google Dynamic Remarketing Tag [![Notice](https://img.shields.io/badge/fork-discontinued-red.svg)](#)

Google remarketing can help you reach people who have previously visited your website as they visit other sites on the Google Display Network or search on Google. Using remarketing, you can show these customers messages tailored to them based on which sections of your site they visited.

With Anaraky GDRT you can simply and easy integrate the Google Dynamic Remarketing Tag in your store's pages.

## Unmaintained:

This was a fork of a free module from magento connect and is discontinued from 12/2017.  New repo is here: [https://github.com/sreichel/magento-Sr-GDRT](https://github.com/sreichel/magento-Sr-GDRT)

### Changes

- fixed product load in loop (what i've introduced :( )
- removed observer code and use layout update via XML instead, fixes [#1](https://github.com/sreichel/magento-Anaraky-GDRT/issues/1) [#2](https://github.com/sreichel/magento-Anaraky-GDRT/issues/2)
- support "Google Tag Manager", fixes [#6](https://github.com/sreichel/magento-Anaraky-GDRT/issues/6)

## Features:
- Very easy to set up.
- Safe (it does not change any core files or structure of database in the Magento).
- Multi-stores support.
- Possibility to choose what to use for product id (SKU or ID).
- Possibility to choose the calculation of total value ('ecomm_totalvalue') with or without taxes.
- Possibility to change page types.

## Compatible with:
- 1.5
- 1.6
- 1.6.1
- 1.6.2.0
- 1.7
- 1.8
- 1.8.1
- 1.9


## Magento Connect: 
http://www.magentocommerce.com/magento-connect/anaraky-gdrt-google-dynamic-remarketing-tag-for-magento.html

## Installation:

### Via modman
```
modman clone https://github.com/sreichel/magento-Anaraky-GDRT.git
```
### Via composer:
```
{
    "require": {
        "anaraky/gdrt": "*",
    },
    "repositories": [
        {
            "type": "vcs",
            "url":  "https://github.com/sreichel/magento-Anaraky-GDRT.git"
        }
    ]
}