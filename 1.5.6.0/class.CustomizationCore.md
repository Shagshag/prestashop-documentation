Class CustomizationCore
=====================





* Class name: CustomizationCore
* Source: [classes/Customization.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Customization.php#L27)


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
* Source: [classes/Customization.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Customization.php#L53)


#### Arguments
* $customizations **mixed**



### <a name="method-countQuantityByCart"></a>countQuantityByCart

```php
mixed CustomizationCore::countQuantityByCart($id_cart)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customization.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Customization.php#L101)


#### Arguments
* $id_cart **mixed**



### <a name="method-getLabel"></a>getLabel

```php
mixed CustomizationCore::getLabel($id_customization, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customization.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Customization.php#L61)


#### Arguments
* $id_customization **mixed**
* $id_lang **mixed**



### <a name="method-getOrderedCustomizations"></a>getOrderedCustomizations

```php
mixed CustomizationCore::getOrderedCustomizations($id_cart)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customization.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Customization.php#L43)


#### Arguments
* $id_cart **mixed**



### <a name="method-getReturnedCustomizations"></a>getReturnedCustomizations

```php
mixed CustomizationCore::getReturnedCustomizations($id_order)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customization.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Customization.php#L29)


#### Arguments
* $id_order **mixed**



### <a name="method-isCurrentlyUsed"></a>isCurrentlyUsed

```php
boolean CustomizationCore::isCurrentlyUsed($table, $has_active_column)
```

This method is allow to know if a Customization entity is currently used



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customization.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Customization.php#L135)


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
* Source: [classes/Customization.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Customization.php#L123)




### <a name="method-retrieveQuantitiesFromIds"></a>retrieveQuantitiesFromIds

```php
mixed CustomizationCore::retrieveQuantitiesFromIds($ids_customizations)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customization.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/classes/Customization.php#L76)


#### Arguments
* $ids_customizations **mixed**


