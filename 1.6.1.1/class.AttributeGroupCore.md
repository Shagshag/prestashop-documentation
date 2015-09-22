Class AttributeGroupCore
=====================





* Class name: AttributeGroupCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/AttributeGroup.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#L27)


Contents
--------


### Properties

* [$definition](#property-$definition)
* [$group_type](#property-$group_type)
* [$is_color_group](#property-$is_color_group)
* [$name](#property-$name)
* [$position](#property-$position)
* [$public_name](#property-$public_name)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [add](#method-add)
* [cleanDeadCombinations](#method-cleanDeadCombinations)
* [cleanPositions](#method-cleanPositions)
* [delete](#method-delete)
* [deleteSelection](#method-deleteSelection)
* [getAttributes](#method-getAttributes)
* [getAttributesGroups](#method-getAttributesGroups)
* [getHigherPosition](#method-getHigherPosition)
* [getWsProductOptionValues](#method-getWsProductOptionValues)
* [setWsProductOptionValues](#method-setWsProductOptionValues)
* [update](#method-update)
* [updatePosition](#method-updatePosition)




Properties
----------


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'attribute_group', 'primary' => 'id_attribute_group', 'multilang' => true, 'fields' => array('is_color_group' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'group_type' => array('type' => self::TYPE_STRING, 'required' => true), 'position' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 128), 'public_name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 64)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/AttributeGroup.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#L41).


### <a name="property-$group_type"></a>$group_type

```php
public mixed $group_type
```





* Visibility: **public**
* Source: [classes/AttributeGroup.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#L33).


### <a name="property-$is_color_group"></a>$is_color_group

```php
public mixed $is_color_group
```





* Visibility: **public**
* Source: [classes/AttributeGroup.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#L31).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/AttributeGroup.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#L30).


### <a name="property-$position"></a>$position

```php
public mixed $position
```





* Visibility: **public**
* Source: [classes/AttributeGroup.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#L32).


### <a name="property-$public_name"></a>$public_name

```php
public string $public_name
```





* Visibility: **public**
* Source: [classes/AttributeGroup.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#L36).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectsNodeName' => 'product_options', 'objectNodeName' => 'product_option', 'fields' => array(), 'associations' => array('product_option_values' => array('resource' => 'product_option_value', 'fields' => array('id' => array()))))
```





* Visibility: **protected**
* Source: [classes/AttributeGroup.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#L57).


Methods
-------


### <a name="method-add"></a>add

```php
mixed AttributeGroupCore::add($autodate, $nullValues)
```





* Visibility: **public**
* Source: [classes/AttributeGroup.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#L71)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### <a name="method-cleanDeadCombinations"></a>cleanDeadCombinations

```php
mixed AttributeGroupCore::cleanDeadCombinations()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/AttributeGroup.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#L101)




### <a name="method-cleanPositions"></a>cleanPositions

```php
boolean AttributeGroupCore::cleanPositions()
```

Reorder group attribute position
Call it after deleting a group attribute.



* Visibility: **public**
* This method is **static**.
* Source: [classes/AttributeGroup.php line 320](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#L320)




### <a name="method-delete"></a>delete

```php
mixed AttributeGroupCore::delete()
```





* Visibility: **public**
* Source: [classes/AttributeGroup.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#L125)




### <a name="method-deleteSelection"></a>deleteSelection

```php
mixed AttributeGroupCore::deleteSelection($selection)
```

Delete several objects from database

return boolean Deletion result

* Visibility: **public**
* Source: [classes/AttributeGroup.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#L223)


#### Arguments
* $selection **mixed**



### <a name="method-getAttributes"></a>getAttributes

```php
array AttributeGroupCore::getAttributes(integer $id_lang, boolean $id_attribute_group)
```

Get all attributes for a given language / group



* Visibility: **public**
* This method is **static**.
* Source: [classes/AttributeGroup.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#L180)


#### Arguments
* $id_lang **integer** - Language id
* $id_attribute_group **boolean** - Attribute group id



### <a name="method-getAttributesGroups"></a>getAttributesGroups

```php
array AttributeGroupCore::getAttributesGroups(integer $id_lang)
```

Get all attributes groups for a given language



* Visibility: **public**
* This method is **static**.
* Source: [classes/AttributeGroup.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#L202)


#### Arguments
* $id_lang **integer** - Language id



### <a name="method-getHigherPosition"></a>getHigherPosition

```php
integer AttributeGroupCore::getHigherPosition()
```

getHigherPosition

Get the higher group attribute position

* Visibility: **public**
* This method is **static**.
* Source: [classes/AttributeGroup.php line 348](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#L348)




### <a name="method-getWsProductOptionValues"></a>getWsProductOptionValues

```php
mixed AttributeGroupCore::getWsProductOptionValues()
```





* Visibility: **public**
* Source: [classes/AttributeGroup.php line 260](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#L260)




### <a name="method-setWsProductOptionValues"></a>setWsProductOptionValues

```php
mixed AttributeGroupCore::setWsProductOptionValues($values)
```





* Visibility: **public**
* Source: [classes/AttributeGroup.php line 235](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#L235)


#### Arguments
* $values **mixed**



### <a name="method-update"></a>update

```php
mixed AttributeGroupCore::update($nullValues)
```





* Visibility: **public**
* Source: [classes/AttributeGroup.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#L88)


#### Arguments
* $nullValues **mixed**



### <a name="method-updatePosition"></a>updatePosition

```php
boolean AttributeGroupCore::updatePosition(boolean $way, integer $position)
```

Move a group attribute



* Visibility: **public**
* Source: [classes/AttributeGroup.php line 277](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#L277)


#### Arguments
* $way **boolean** - Up (1)  or Down (0)
* $position **integer**


