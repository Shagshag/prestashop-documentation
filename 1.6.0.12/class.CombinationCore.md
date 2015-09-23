Class CombinationCore
=====================





* Class name: CombinationCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Combination.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L27)


Contents
--------


### Properties

* [$available_date](#property-$available_date)
* [$default_on](#property-$default_on)
* [$definition](#property-$definition)
* [$ean13](#property-$ean13)
* [$ecotax](#property-$ecotax)
* [$id_product](#property-$id_product)
* [$location](#property-$location)
* [$minimal_quantity](#property-$minimal_quantity)
* [$price](#property-$price)
* [$quantity](#property-$quantity)
* [$reference](#property-$reference)
* [$supplier_reference](#property-$supplier_reference)
* [$unit_price_impact](#property-$unit_price_impact)
* [$upc](#property-$upc)
* [$webserviceParameters](#property-$webserviceParameters)
* [$weight](#property-$weight)
* [$wholesale_price](#property-$wholesale_price)

### Methods

* [add](#method-add)
* [delete](#method-delete)
* [deleteAssociations](#method-deleteAssociations)
* [deleteFromSupplier](#method-deleteFromSupplier)
* [getAttributesName](#method-getAttributesName)
* [getColorsAttributes](#method-getColorsAttributes)
* [getIdByReference](#method-getIdByReference)
* [getPrice](#method-getPrice)
* [getWsImages](#method-getWsImages)
* [getWsProductOptionValues](#method-getWsProductOptionValues)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isFeatureActive](#method-isFeatureActive)
* [setAttributes](#method-setAttributes)
* [setImages](#method-setImages)
* [setWsImages](#method-setWsImages)
* [setWsProductOptionValues](#method-setWsProductOptionValues)
* [update](#method-update)




Properties
----------


### <a name="property-$available_date"></a>$available_date

```php
public mixed $available_date = '0000-00-00'
```





* Visibility: **public**
* Source: [classes/Combination.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L57).


### <a name="property-$default_on"></a>$default_on

```php
public mixed $default_on
```





* Visibility: **public**
* Source: [classes/Combination.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L55).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'product_attribute', 'primary' => 'id_product_attribute', 'fields' => array('id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'location' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 64), 'ean13' => array('type' => self::TYPE_STRING, 'validate' => 'isEan13', 'size' => 13), 'upc' => array('type' => self::TYPE_STRING, 'validate' => 'isUpc', 'size' => 12), 'quantity' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'size' => 10), 'reference' => array('type' => self::TYPE_STRING, 'size' => 32), 'supplier_reference' => array('type' => self::TYPE_STRING, 'size' => 32), 'wholesale_price' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isPrice', 'size' => 27), 'price' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isNegativePrice', 'size' => 20), 'ecotax' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isPrice', 'size' => 20), 'weight' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isFloat'), 'unit_price_impact' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isNegativePrice', 'size' => 20), 'minimal_quantity' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedId', 'required' => true), 'default_on' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isBool'), 'available_date' => array('type' => self::TYPE_DATE, 'shop' => true, 'validate' => 'isDateFormat')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Combination.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L62).


### <a name="property-$ean13"></a>$ean13

```php
public mixed $ean13
```





* Visibility: **public**
* Source: [classes/Combination.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L37).


### <a name="property-$ecotax"></a>$ecotax

```php
public mixed $ecotax
```





* Visibility: **public**
* Source: [classes/Combination.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L47).


### <a name="property-$id_product"></a>$id_product

```php
public mixed $id_product
```





* Visibility: **public**
* Source: [classes/Combination.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L29).


### <a name="property-$location"></a>$location

```php
public mixed $location
```





* Visibility: **public**
* Source: [classes/Combination.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L35).


### <a name="property-$minimal_quantity"></a>$minimal_quantity

```php
public mixed $minimal_quantity = 1
```





* Visibility: **public**
* Source: [classes/Combination.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L49).


### <a name="property-$price"></a>$price

```php
public mixed $price
```





* Visibility: **public**
* Source: [classes/Combination.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L43).


### <a name="property-$quantity"></a>$quantity

```php
public mixed $quantity
```





* Visibility: **public**
* Source: [classes/Combination.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L51).


### <a name="property-$reference"></a>$reference

```php
public mixed $reference
```





* Visibility: **public**
* Source: [classes/Combination.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L31).


### <a name="property-$supplier_reference"></a>$supplier_reference

```php
public mixed $supplier_reference
```





* Visibility: **public**
* Source: [classes/Combination.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L33).


### <a name="property-$unit_price_impact"></a>$unit_price_impact

```php
public mixed $unit_price_impact
```





* Visibility: **public**
* Source: [classes/Combination.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L45).


### <a name="property-$upc"></a>$upc

```php
public mixed $upc
```





* Visibility: **public**
* Source: [classes/Combination.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L39).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectNodeName' => 'combination', 'objectsNodeName' => 'combinations', 'fields' => array('id_product' => array('required' => true, 'xlink_resource' => 'products')), 'associations' => array('product_option_values' => array('resource' => 'product_option_value'), 'images' => array('resource' => 'image', 'api' => 'images/products')))
```





* Visibility: **protected**
* Source: [classes/Combination.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L86).


### <a name="property-$weight"></a>$weight

```php
public mixed $weight
```





* Visibility: **public**
* Source: [classes/Combination.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L53).


### <a name="property-$wholesale_price"></a>$wholesale_price

```php
public mixed $wholesale_price
```





* Visibility: **public**
* Source: [classes/Combination.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L41).


Methods
-------


### <a name="method-add"></a>add

```php
mixed CombinationCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Combination.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L128)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-delete"></a>delete

```php
mixed CombinationCore::delete()
```





* Visibility: **public**
* Source: [classes/Combination.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L98)




### <a name="method-deleteAssociations"></a>deleteAssociations

```php
mixed CombinationCore::deleteAssociations()
```





* Visibility: **public**
* Source: [classes/Combination.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L154)




### <a name="method-deleteFromSupplier"></a>deleteFromSupplier

```php
mixed CombinationCore::deleteFromSupplier($id_product)
```





* Visibility: **public**
* Source: [classes/Combination.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L122)


#### Arguments
* $id_product **mixed**



### <a name="method-getAttributesName"></a>getAttributesName

```php
mixed CombinationCore::getAttributesName($id_lang)
```





* Visibility: **public**
* Source: [classes/Combination.php line 240](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L240)


#### Arguments
* $id_lang **mixed**



### <a name="method-getColorsAttributes"></a>getColorsAttributes

```php
mixed CombinationCore::getColorsAttributes()
```





* Visibility: **public**
* Source: [classes/Combination.php line 296](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L296)




### <a name="method-getIdByReference"></a>getIdByReference

```php
integer CombinationCore::getIdByReference(integer $id_product, string $reference)
```

For a given product_attribute reference, returns the corresponding id



* Visibility: **public**
* This method is **static**.
* Source: [classes/Combination.php line 282](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L282)


#### Arguments
* $id_product **integer**
* $reference **string**



### <a name="method-getPrice"></a>getPrice

```php
float CombinationCore::getPrice(integer $id_product_attribute)
```

Retrive the price of combination



* Visibility: **public**
* This method is **static**.
* Source: [classes/Combination.php line 314](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L314)


#### Arguments
* $id_product_attribute **integer**



### <a name="method-getWsImages"></a>getWsImages

```php
mixed CombinationCore::getWsImages()
```





* Visibility: **public**
* Source: [classes/Combination.php line 199](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L199)




### <a name="method-getWsProductOptionValues"></a>getWsProductOptionValues

```php
mixed CombinationCore::getWsProductOptionValues()
```





* Visibility: **public**
* Source: [classes/Combination.php line 188](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L188)




### <a name="method-isCurrentlyUsed"></a>isCurrentlyUsed

```php
boolean CombinationCore::isCurrentlyUsed($table, $has_active_column)
```

This method is allow to know if a Combination entity is currently used



* Visibility: **public**
* This method is **static**.
* Source: [classes/Combination.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L270)


#### Arguments
* $table **mixed**
* $has_active_column **mixed**



### <a name="method-isFeatureActive"></a>isFeatureActive

```php
boolean CombinationCore::isFeatureActive()
```

This method is allow to know if a feature is active



* Visibility: **public**
* This method is **static**.
* Source: [classes/Combination.php line 254](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L254)




### <a name="method-setAttributes"></a>setAttributes

```php
mixed CombinationCore::setAttributes($ids_attribute)
```





* Visibility: **public**
* Source: [classes/Combination.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L163)


#### Arguments
* $ids_attribute **mixed**



### <a name="method-setImages"></a>setImages

```php
mixed CombinationCore::setImages($ids_image)
```





* Visibility: **public**
* Source: [classes/Combination.php line 209](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L209)


#### Arguments
* $ids_image **mixed**



### <a name="method-setWsImages"></a>setWsImages

```php
mixed CombinationCore::setWsImages($values)
```





* Visibility: **public**
* Source: [classes/Combination.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L232)


#### Arguments
* $values **mixed**



### <a name="method-setWsProductOptionValues"></a>setWsProductOptionValues

```php
mixed CombinationCore::setWsProductOptionValues($values)
```





* Visibility: **public**
* Source: [classes/Combination.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L180)


#### Arguments
* $values **mixed**



### <a name="method-update"></a>update

```php
mixed CombinationCore::update($null_values)
```





* Visibility: **public**
* Source: [classes/Combination.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Combination.php#L146)


#### Arguments
* $null_values **mixed**


