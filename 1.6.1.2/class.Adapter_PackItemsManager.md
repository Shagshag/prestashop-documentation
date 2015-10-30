Class Adapter_PackItemsManager
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

* Class name: Adapter_PackItemsManager
* Source: [Adapter/Adapter_PackItemsManager.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/Adapter/Adapter_PackItemsManager.php#L27)


Contents
--------



### Methods

* [getPackItems](#method-getPackItems)
* [getPacksContainingItem](#method-getPacksContainingItem)
* [isPack](#method-isPack)
* [isPacked](#method-isPacked)






Methods
-------


### <a name="method-getPackItems"></a>getPackItems

```php
\Array[Product] Adapter_PackItemsManager::getPackItems(\Pack $pack, integer $id_lang)
```

Get the Products contained in the given Pack.



* Visibility: **public**
* Source: [Adapter/Adapter_PackItemsManager.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/Adapter/Adapter_PackItemsManager.php#L36)


#### Arguments
* $pack **[Pack](class.PackCore.md)**
* $id_lang **integer** - Optional



### <a name="method-getPacksContainingItem"></a>getPacksContainingItem

```php
\Array[Pack] Adapter_PackItemsManager::getPacksContainingItem(\Product $item, integer $item_attribute_id, integer $id_lang)
```

Get all Packs that contains the given item in the corresponding declination.



* Visibility: **public**
* Source: [Adapter/Adapter_PackItemsManager.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/Adapter/Adapter_PackItemsManager.php#L53)


#### Arguments
* $item **[Product](class.ProductCore.md)**
* $item_attribute_id **integer**
* $id_lang **integer** - Optional



### <a name="method-isPack"></a>isPack

```php
boolean Adapter_PackItemsManager::isPack(\Product $product)
```

Is this product a pack?



* Visibility: **public**
* Source: [Adapter/Adapter_PackItemsManager.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/Adapter/Adapter_PackItemsManager.php#L68)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-isPacked"></a>isPacked

```php
boolean Adapter_PackItemsManager::isPacked(\Product $product, integer $id_product_attribute)
```

Is this product in a pack?
If $id_product_attribute specified, then will restrict search on the given combination,
else this method will match a product if at least one of all its combination is in a pack.



* Visibility: **public**
* Source: [Adapter/Adapter_PackItemsManager.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/Adapter/Adapter_PackItemsManager.php#L82)


#### Arguments
* $product **[Product](class.ProductCore.md)**
* $id_product_attribute **integer** - Optional combination of the product


