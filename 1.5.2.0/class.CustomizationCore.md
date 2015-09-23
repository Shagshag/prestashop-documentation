Class CustomizationCore
=====================





* Class name: CustomizationCore
* Source: [classes/Customization.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customization.php#L28)


Contents
--------



### Methods

* [countCustomizationQuantityByProduct](#method-countCustomizationQuantityByProduct)
* [countQuantityByCart](#method-countQuantityByCart)
* [getLabel](#method-getLabel)
* [getOrderedCustomizations](#method-getOrderedCustomizations)
* [getReturnedCustomizations](#method-getReturnedCustomizations)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isFeatureActive](#method-isFeatureActive)
* [retrieveQuantitiesFromIds](#method-retrieveQuantitiesFromIds)






Methods
-------


### <a name="method-countCustomizationQuantityByProduct"></a>countCustomizationQuantityByProduct

```php
mixed CustomizationCore::countCustomizationQuantityByProduct($customizations)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customization.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customization.php#L54)


#### Arguments
* $customizations **mixed**



### <a name="method-countQuantityByCart"></a>countQuantityByCart

```php
mixed CustomizationCore::countQuantityByCart($id_cart)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customization.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customization.php#L102)


#### Arguments
* $id_cart **mixed**



### <a name="method-getLabel"></a>getLabel

```php
mixed CustomizationCore::getLabel($id_customization, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customization.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customization.php#L62)


#### Arguments
* $id_customization **mixed**
* $id_lang **mixed**



### <a name="method-getOrderedCustomizations"></a>getOrderedCustomizations

```php
mixed CustomizationCore::getOrderedCustomizations($id_cart)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customization.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customization.php#L44)


#### Arguments
* $id_cart **mixed**



### <a name="method-getReturnedCustomizations"></a>getReturnedCustomizations

```php
mixed CustomizationCore::getReturnedCustomizations($id_order)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customization.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customization.php#L30)


#### Arguments
* $id_order **mixed**



### <a name="method-isCurrentlyUsed"></a>isCurrentlyUsed

```php
boolean CustomizationCore::isCurrentlyUsed($table, $has_active_column)
```

This method is allow to know if a Customization entity is currently used



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customization.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customization.php#L136)


#### Arguments
* $table **mixed**
* $has_active_column **mixed**



### <a name="method-isFeatureActive"></a>isFeatureActive

```php
boolean CustomizationCore::isFeatureActive()
```

This method is allow to know if a feature is used or active



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customization.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customization.php#L124)




### <a name="method-retrieveQuantitiesFromIds"></a>retrieveQuantitiesFromIds

```php
mixed CustomizationCore::retrieveQuantitiesFromIds($ids_customizations)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customization.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Customization.php#L77)


#### Arguments
* $ids_customizations **mixed**


