Core_Business_Stock_StockManager
===============

2007-2015 PrestaShop

NOTICE OF LICENSE

This source file is subject to the Open Software License (OSL 3.0)
that is bundled with this package in the file LICENSE.txt.
It is also available through the world-wide-web at this URL:
http://opensource.org/licenses/osl-3.0.php
If you did not receive a copy of the license and are unable to
obtain it through the world-wide-web, please send an email
to license@prestashop.com so we can send you a copy immediately.

DISCLAIMER

Do not edit or add to this file if you wish to upgrade PrestaShop to newer
versions in the future. If you wish to customize PrestaShop for your
needs please refer to http://www.prestashop.com for more information.


* Class name: Core_Business_Stock_StockManager
* Namespace: 

* This class is defined in [Core/Business/Stock/Core_Business_Stock_StockManager.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Stock/Core_Business_Stock_StockManager.php#27)







Methods
-------


### updatePackQuantity

    mixed Core_Business_Stock_StockManager::updatePackQuantity(\Product $product, \StockAvailable $stock_available, integer $delta_quantity, integer|null $id_shop)

This will update a Pack quantity and will decrease the quantity of containing Products if needed.



* Visibility: **public**
* This method is defined in [Core/Business/Stock/Core_Business_Stock_StockManager.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Stock/Core_Business_Stock_StockManager.php#37)


#### Arguments
* $product **[Product](ProductCore)** - &lt;p&gt;A product pack object to update its quantity&lt;/p&gt;
* $stock_available **[StockAvailable](StockAvailableCore)** - &lt;p&gt;the stock of the product to fix with correct quantity&lt;/p&gt;
* $delta_quantity **integer** - &lt;p&gt;The movement of the stock (negative for a decrease)&lt;/p&gt;
* $id_shop **integer|null** - &lt;p&gt;Opional shop ID&lt;/p&gt;



### updatePacksQuantityContainingProduct

    mixed Core_Business_Stock_StockManager::updatePacksQuantityContainingProduct(\Product $product, integer $id_product_attribute, \StockAvailable $stock_available, integer|null $id_shop)

This will decrease (if needed) Packs containing this product
(with the right declinaison) if there is not enough product in stocks.



* Visibility: **public**
* This method is defined in [Core/Business/Stock/Core_Business_Stock_StockManager.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Stock/Core_Business_Stock_StockManager.php#72)


#### Arguments
* $product **[Product](ProductCore)** - &lt;p&gt;A product object to update its quantity&lt;/p&gt;
* $id_product_attribute **integer** - &lt;p&gt;The product attribute to update&lt;/p&gt;
* $stock_available **[StockAvailable](StockAvailableCore)** - &lt;p&gt;the stock of the product to fix with correct quantity&lt;/p&gt;
* $id_shop **integer|null** - &lt;p&gt;Opional shop ID&lt;/p&gt;



### updateQuantity

    mixed Core_Business_Stock_StockManager::updateQuantity(\Product $product, integer $id_product_attribute, integer $delta_quantity, integer|null $id_shop)

Will update Product available stock int he given declinaison. If product is a Pack, could decrease the sub products.

If Product is contained in a Pack, Pack could be decreased or not (only if sub product stocks become not sufficient).

* Visibility: **public**
* This method is defined in [Core/Business/Stock/Core_Business_Stock_StockManager.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Stock/Core_Business_Stock_StockManager.php#112)


#### Arguments
* $product **[Product](ProductCore)** - &lt;p&gt;The product to update its stockAvailable&lt;/p&gt;
* $id_product_attribute **integer** - &lt;p&gt;The declinaison to update (null if not)&lt;/p&gt;
* $delta_quantity **integer** - &lt;p&gt;The quantity change (positive or negative)&lt;/p&gt;
* $id_shop **integer|null** - &lt;p&gt;Optional&lt;/p&gt;


