# magento2-traduccion-chile
# Magento 2 Spanish Language Pack Chile version 1.0.0

Spanish translation for Magento 2. Translation es_CL (Spanish Chile).

Traduction de Magento 2 en Spanish.

See documentation: https://www.magentochile.cl/m2-spanish-language-pack.html


## Supported versions

* Magento v2.0.0
* Magento v2.0.1
* Magento v2.0.2
* Magento v2.0.3
* Magento v2.0.4
* Magento v2.0.5
* Magento v2.0.6
* Magento v2.0.7
* Magento v2.0.8
* Magento v2.1.0
* Magento v2.1.1
* Magento v2.1.2
* Magento v2.1.3

## Links

* Website: https://www.magentochile.cl/
* Packagist: https://packagist.org/packages/magentochile/magento2-traduccion-chile
* Github: https://github.com/magentochile/magento2-traduccion-chile/
* Official version: https://www.magentochile.cl/m2-spanish-language-pack.html

## BUG Magento 2
For some strange reason, and most likely it is a Magento 2 bug, it is that it does not update the shopping cart. It has been tested with es_CL and does not start the update of the cart, but with es_ES it updates the shopping cart!!!

The solution the BUG? Good for the moment is to use, this pack of Spanish language Chile (es_CL) for the Admin of Magento 2, and for the frontend occupy our other pack of Spanish language (es_ES): https://github.com/magentochile/magento2-translation-spanish

## Official version
Remember that for a translation if you want a more complete translation and adapted to the country Chile, you can acquire the official language pack of Magento Chile in: https://www.magentochile.cl/m2-spanish-language-pack.html

## Important Note: 
This pack of languages, only contains the skeleton for translations, which you can install and once installed can translate the file es_CL respectively.

## Installation
composer require magentochile/magento2-traduccion-chile dev-master

php -d memory_limit=-1 bin/magento setup:static-content:deploy es_CL

php bin/magento cache:clean

## End
