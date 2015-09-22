Class Core_Business_Stock_StockManager
=====================

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
* Source: [Core/Business/Stock/Core_Business_Stock_StockManager.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Stock/Core_Business_Stock_StockManager.php#L27)


Contents
--------



### Methods

* [updatePackQuantity](#method-updatePackQuantity)
* [updatePacksQuantityContainingProduct](#method-updatePacksQuantityContainingProduct)
* [updateQuantity](#method-updateQuantity)






Methods
-------


### <a name="method-updatePackQuantity"></a>updatePackQuantity

```php
mixed Core_Business_Stock_StockManager::updatePackQuantity(\Product $product, \StockAvailable $stock_available, integer $delta_quantity, integer|null $id_shop)
```

This will update a Pack quantity and will decrease the quantity of containing Products if needed.



* Visibility: **public**
* Source: [Core/Business/Stock/Core_Business_Stock_StockManager.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Stock/Core_Business_Stock_StockManager.php#L37)


#### Arguments
* $product **[Product](class.ProductCore.md)** - A product pack object to update its quantity
* $stock_available **[StockAvailable](class.StockAvailableCore.md)** - the stock of the product to fix with correct quantity
* $delta_quantity **integer** - The movement of the stock (negative for a decrease)
* $id_shop **integer|null** - Opional shop ID



### <a name="method-updatePacksQuantityContainingProduct"></a>updatePacksQuantityContainingProduct

```php
mixed Core_Business_Stock_StockManager::updatePacksQuantityContainingProduct(\Product $product, integer $id_product_attribute, \StockAvailable $stock_available, integer|null $id_shop)
```

This will decrease (if needed) Packs containing this product
(with the right declinaison) if there is not enough product in stocks.



* Visibility: **public**
* Source: [Core/Business/Stock/Core_Business_Stock_StockManager.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Stock/Core_Business_Stock_StockManager.php#L72)


#### Arguments
* $product **[Product](class.ProductCore.md)** - A product object to update its quantity
* $id_product_attribute **integer** - The product attribute to update
* $stock_available **[StockAvailable](class.StockAvailableCore.md)** - the stock of the product to fix with correct quantity
* $id_shop **integer|null** - Opional shop ID



### <a name="method-updateQuantity"></a>updateQuantity

```php
mixed Core_Business_Stock_StockManager::updateQuantity(\Product $product, integer $id_product_attribute, integer $delta_quantity, integer|null $id_shop)
```

Will update Product available stock int he given declinaison. If product is a Pack, could decrease the sub products.

If Product is contained in a Pack, Pack could be decreased or not (only if sub product stocks become not sufficient).

* Visibility: **public**
* Source: [Core/Business/Stock/Core_Business_Stock_StockManager.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Stock/Core_Business_Stock_StockManager.php#L112)


#### Arguments
* $product **[Product](class.ProductCore.md)** - The product to update its stockAvailable
* $id_product_attribute **integer** - The declinaison to update (null if not)
* $delta_quantity **integer** - The quantity change (positive or negative)
* $id_shop **integer|null** - Optional


