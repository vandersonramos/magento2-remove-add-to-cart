# magento2 - Remove add to cart button

## Overview
Magento 2 module to disable add to cart button from product and category page for guest.


## Installation details
1. Run `composer require vandersonramos/magento2-remove-add-to-cart:dev-master `
2. Run `php bin/magento setup:upgrade`
3. Run `php bin/magento cache:clean`


## Configuration details
1. Go to Magento admin 
2. Find option in `Stores > Configuration > Catalog > Catalog`
3. Under the `Storfront` tab you will find the `Remove add to cart button for guests` option  
5. `Enable` this option to activate this module


