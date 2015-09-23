Class AttributeCore
=====================





* Class name: AttributeCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Attribute.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Attribute.php#L27)


Contents
--------


### Properties

* [$color](#property-$color)
* [$default](#property-$default)
* [$definition](#property-$definition)
* [$id_attribute_group](#property-$id_attribute_group)
* [$image_dir](#property-$image_dir)
* [$name](#property-$name)
* [$position](#property-$position)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [checkAttributeQty](#method-checkAttributeQty)
* [cleanPositions](#method-cleanPositions)
* [delete](#method-delete)
* [getAttributeMinimalQty](#method-getAttributeMinimalQty)
* [getAttributeQty](#method-getAttributeQty)
* [getAttributes](#method-getAttributes)
* [getHigherPosition](#method-getHigherPosition)
* [isAttribute](#method-isAttribute)
* [isColorAttribute](#method-isColorAttribute)
* [update](#method-update)
* [updatePosition](#method-updatePosition)
* [updateQtyProduct](#method-updateQtyProduct)




Properties
----------


### <a name="property-$color"></a>$color

```php
public mixed $color
```





* Visibility: **public**
* Source: [classes/Attribute.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Attribute.php#L34).


### <a name="property-$default"></a>$default

```php
public mixed $default
```





* Visibility: **public**
* Source: [classes/Attribute.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Attribute.php#L36).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'attribute', 'primary' => 'id_attribute', 'multilang' => true, 'fields' => array('id_attribute_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'color' => array('type' => self::TYPE_STRING, 'validate' => 'isColor'), 'position' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 128)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Attribute.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Attribute.php#L41).


### <a name="property-$id_attribute_group"></a>$id_attribute_group

```php
public integer $id_attribute_group
```





* Visibility: **public**
* Source: [classes/Attribute.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Attribute.php#L30).


### <a name="property-$image_dir"></a>$image_dir

```php
protected mixed $image_dir = _PS_COL_IMG_DIR_
```





* Visibility: **protected**
* Source: [classes/Attribute.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Attribute.php#L56).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/Attribute.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Attribute.php#L33).


### <a name="property-$position"></a>$position

```php
public mixed $position
```





* Visibility: **public**
* Source: [classes/Attribute.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Attribute.php#L35).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectsNodeName' => 'product_option_values', 'objectNodeName' => 'product_option_value', 'fields' => array('id_attribute_group' => array('xlink_resource' => 'product_options')))
```





* Visibility: **protected**
* Source: [classes/Attribute.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Attribute.php#L58).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AttributeCore::__construct($id, $id_lang, $id_shop)
```





* Visibility: **public**
* Source: [classes/Attribute.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Attribute.php#L66)


#### Arguments
* $id **mixed**
* $id_lang **mixed**
* $id_shop **mixed**



### <a name="method-add"></a>add

```php
mixed AttributeCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Attribute.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Attribute.php#L124)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-checkAttributeQty"></a>checkAttributeQty

```php
boolean AttributeCore::checkAttributeQty(integer $id_product_attribute, integer $qty, \Shop $shop)
```

Get quantity for a given attribute combination
Check if quantity is enough to deserve customer



* Visibility: **public**
* This method is **static**.
* Source: [classes/Attribute.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Attribute.php#L196)


#### Arguments
* $id_product_attribute **integer** - Product attribute combination id
* $qty **integer** - Quantity needed
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-cleanPositions"></a>cleanPositions

```php
boolean AttributeCore::cleanPositions(integer $id_attribute_group, boolean $use_last_attribute)
```

Reorder attribute position in group $id_attribute_group.

Call it after deleting an attribute from a group.

* Visibility: **public**
* Source: [classes/Attribute.php line 340](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Attribute.php#L340)


#### Arguments
* $id_attribute_group **integer**
* $use_last_attribute **boolean**



### <a name="method-delete"></a>delete

```php
mixed AttributeCore::delete()
```





* Visibility: **public**
* Source: [classes/Attribute.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Attribute.php#L73)




### <a name="method-getAttributeMinimalQty"></a>getAttributeMinimalQty

```php
mixed AttributeCore::getAttributeMinimalQty(integer $id_product_attribute)
```

Get minimal quantity for product with attributes quantity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Attribute.php line 267](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Attribute.php#L267)


#### Arguments
* $id_product_attribute **integer**



### <a name="method-getAttributeQty"></a>getAttributeQty

```php
mixed AttributeCore::getAttributeQty($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Attribute.php line 209](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Attribute.php#L209)


#### Arguments
* $id_product **mixed**



### <a name="method-getAttributes"></a>getAttributes

```php
array AttributeCore::getAttributes(integer $id_lang, $not_null)
```

Get all attributes for a given language



* Visibility: **public**
* This method is **static**.
* Source: [classes/Attribute.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Attribute.php#L144)


#### Arguments
* $id_lang **integer** - Language id
* $not_null **mixed**



### <a name="method-getHigherPosition"></a>getHigherPosition

```php
integer AttributeCore::getHigherPosition(integer $id_attribute_group)
```

getHigherPosition

Get the higher attribute position from a group attribute

* Visibility: **public**
* This method is **static**.
* Source: [classes/Attribute.php line 377](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Attribute.php#L377)


#### Arguments
* $id_attribute_group **integer**



### <a name="method-isAttribute"></a>isAttribute

```php
mixed AttributeCore::isAttribute($id_attribute_group, $name, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Attribute.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Attribute.php#L165)


#### Arguments
* $id_attribute_group **mixed**
* $name **mixed**
* $id_lang **mixed**



### <a name="method-isColorAttribute"></a>isColorAttribute

```php
boolean AttributeCore::isColorAttribute()
```

Return true if attribute is color type



* Visibility: **public**
* Source: [classes/Attribute.php line 245](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Attribute.php#L245)




### <a name="method-update"></a>update

```php
mixed AttributeCore::update($null_values)
```





* Visibility: **public**
* Source: [classes/Attribute.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Attribute.php#L114)


#### Arguments
* $null_values **mixed**



### <a name="method-updatePosition"></a>updatePosition

```php
boolean AttributeCore::updatePosition(boolean $way, integer $position)
```

Move an attribute inside its group



* Visibility: **public**
* Source: [classes/Attribute.php line 288](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Attribute.php#L288)


#### Arguments
* $way **boolean** - Up (1)  or Down (0)
* $position **integer**



### <a name="method-updateQtyProduct"></a>updateQtyProduct

```php
boolean AttributeCore::updateQtyProduct($arr)
```

Update array with veritable quantity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Attribute.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Attribute.php#L223)


#### Arguments
* $arr **mixed**


