Class CustomizationCore
=====================





* Class name: CustomizationCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Customization.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customization.php#L27)


Contents
--------


### Properties

* [$definition](#property-$definition)
* [$id_address_delivery](#property-$id_address_delivery)
* [$id_cart](#property-$id_cart)
* [$id_product](#property-$id_product)
* [$id_product_attribute](#property-$id_product_attribute)
* [$in_cart](#property-$in_cart)
* [$quantity](#property-$quantity)
* [$quantity_refunded](#property-$quantity_refunded)
* [$quantity_returned](#property-$quantity_returned)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [countCustomizationQuantityByProduct](#method-countCustomizationQuantityByProduct)
* [countQuantityByCart](#method-countQuantityByCart)
* [getLabel](#method-getLabel)
* [getOrderedCustomizations](#method-getOrderedCustomizations)
* [getReturnedCustomizations](#method-getReturnedCustomizations)
* [getWsCustomizedDataImages](#method-getWsCustomizedDataImages)
* [getWsCustomizedDataTextFields](#method-getWsCustomizedDataTextFields)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isFeatureActive](#method-isFeatureActive)
* [retrieveQuantitiesFromIds](#method-retrieveQuantitiesFromIds)
* [setWsCustomizedDataTextFields](#method-setWsCustomizedDataTextFields)




Properties
----------


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'customization', 'primary' => 'id_customization', 'fields' => array('id_product_attribute' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_address_delivery' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_cart' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'quantity' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'quantity_refunded' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'quantity_returned' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'in_cart' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Customization.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customization.php#L49).


### <a name="property-$id_address_delivery"></a>$id_address_delivery

```php
public integer $id_address_delivery
```





* Visibility: **public**
* Source: [classes/Customization.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customization.php#L32).


### <a name="property-$id_cart"></a>$id_cart

```php
public integer $id_cart
```





* Visibility: **public**
* Source: [classes/Customization.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customization.php#L34).


### <a name="property-$id_product"></a>$id_product

```php
public integer $id_product
```





* Visibility: **public**
* Source: [classes/Customization.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customization.php#L36).


### <a name="property-$id_product_attribute"></a>$id_product_attribute

```php
public integer $id_product_attribute
```





* Visibility: **public**
* Source: [classes/Customization.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customization.php#L30).


### <a name="property-$in_cart"></a>$in_cart

```php
public boolean $in_cart
```





* Visibility: **public**
* Source: [classes/Customization.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customization.php#L44).


### <a name="property-$quantity"></a>$quantity

```php
public integer $quantity
```





* Visibility: **public**
* Source: [classes/Customization.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customization.php#L38).


### <a name="property-$quantity_refunded"></a>$quantity_refunded

```php
public integer $quantity_refunded
```





* Visibility: **public**
* Source: [classes/Customization.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customization.php#L40).


### <a name="property-$quantity_returned"></a>$quantity_returned

```php
public integer $quantity_returned
```





* Visibility: **public**
* Source: [classes/Customization.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customization.php#L42).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_address_delivery' => array('xlink_resource' => array('resourceName' => 'addresses')), 'id_cart' => array('xlink_resource' => array('resourceName' => 'carts')), 'id_product' => array('xlink_resource' => array('resourceName' => 'products'))), 'associations' => array('customized_data_text_fields' => array('resource' => 'customized_data_text_field', 'virtual_entity' => true, 'fields' => array('id_customization_field' => array('required' => true, 'xlink_resource' => 'product_customization_fields'), 'value' => array())), 'customized_data_images' => array('resource' => 'customized_data_image', 'virtual_entity' => true, 'setter' => false, 'fields' => array('id_customization_field' => array('xlink_resource' => 'product_customization_fields'), 'value' => array()))))
```





* Visibility: **protected**
* Source: [classes/Customization.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customization.php#L64).


Methods
-------


### <a name="method-countCustomizationQuantityByProduct"></a>countCustomizationQuantityByProduct

```php
mixed CustomizationCore::countCustomizationQuantityByProduct($customizations)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customization.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customization.php#L120)


#### Arguments
* $customizations **mixed**



### <a name="method-countQuantityByCart"></a>countQuantityByCart

```php
mixed CustomizationCore::countQuantityByCart($id_cart)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customization.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customization.php#L170)


#### Arguments
* $id_cart **mixed**



### <a name="method-getLabel"></a>getLabel

```php
mixed CustomizationCore::getLabel($id_customization, $id_lang, $id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customization.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customization.php#L128)


#### Arguments
* $id_customization **mixed**
* $id_lang **mixed**
* $id_shop **mixed**



### <a name="method-getOrderedCustomizations"></a>getOrderedCustomizations

```php
mixed CustomizationCore::getOrderedCustomizations($id_cart)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customization.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customization.php#L110)


#### Arguments
* $id_cart **mixed**



### <a name="method-getReturnedCustomizations"></a>getReturnedCustomizations

```php
mixed CustomizationCore::getReturnedCustomizations($id_order)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customization.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customization.php#L96)


#### Arguments
* $id_order **mixed**



### <a name="method-getWsCustomizedDataImages"></a>getWsCustomizedDataImages

```php
mixed CustomizationCore::getWsCustomizedDataImages()
```





* Visibility: **public**
* Source: [classes/Customization.php line 224](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customization.php#L224)




### <a name="method-getWsCustomizedDataTextFields"></a>getWsCustomizedDataTextFields

```php
mixed CustomizationCore::getWsCustomizedDataTextFields()
```





* Visibility: **public**
* Source: [classes/Customization.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customization.php#L212)




### <a name="method-isCurrentlyUsed"></a>isCurrentlyUsed

```php
boolean CustomizationCore::isCurrentlyUsed($table, $has_active_column)
```

This method is allow to know if a Customization entity is currently used



* Visibility: **public**
* This method is **static**.
* Source: [classes/Customization.php line 204](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customization.php#L204)


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
* Source: [classes/Customization.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customization.php#L192)




### <a name="method-retrieveQuantitiesFromIds"></a>retrieveQuantitiesFromIds

```php
mixed CustomizationCore::retrieveQuantitiesFromIds($ids_customizations)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Customization.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customization.php#L145)


#### Arguments
* $ids_customizations **mixed**



### <a name="method-setWsCustomizedDataTextFields"></a>setWsCustomizedDataTextFields

```php
mixed CustomizationCore::setWsCustomizedDataTextFields($values)
```





* Visibility: **public**
* Source: [classes/Customization.php line 236](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/Customization.php#L236)


#### Arguments
* $values **mixed**


