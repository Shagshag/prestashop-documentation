AttributeGroupCore
===============






* Class name: AttributeGroupCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/AttributeGroup.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#L27)





Properties
----------


### $name

    public string $name





* Visibility: **public**
* This property is defined in [classes/AttributeGroup.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#30)


### $is_color_group

    public mixed $is_color_group





* Visibility: **public**
* This property is defined in [classes/AttributeGroup.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#31)


### $position

    public mixed $position





* Visibility: **public**
* This property is defined in [classes/AttributeGroup.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#32)


### $group_type

    public mixed $group_type





* Visibility: **public**
* This property is defined in [classes/AttributeGroup.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#33)


### $public_name

    public string $public_name





* Visibility: **public**
* This property is defined in [classes/AttributeGroup.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#36)


### $definition

    public mixed $definition = array('table' => 'attribute_group', 'primary' => 'id_attribute_group', 'multilang' => true, 'fields' => array('is_color_group' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'group_type' => array('type' => self::TYPE_STRING, 'required' => true), 'position' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 128), 'public_name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 64)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/AttributeGroup.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#41)


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'product_options', 'objectNodeName' => 'product_option', 'fields' => array(), 'associations' => array('product_option_values' => array('resource' => 'product_option_value', 'fields' => array('id' => array()))))





* Visibility: **protected**
* This property is defined in [classes/AttributeGroup.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#57)


Methods
-------


### add

    mixed AttributeGroupCore::add($autodate, $nullValues)





* Visibility: **public**
* This method is defined in [classes/AttributeGroup.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#71)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### update

    mixed AttributeGroupCore::update($nullValues)





* Visibility: **public**
* This method is defined in [classes/AttributeGroup.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#88)


#### Arguments
* $nullValues **mixed**



### cleanDeadCombinations

    mixed AttributeGroupCore::cleanDeadCombinations()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/AttributeGroup.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#101)




### delete

    mixed AttributeGroupCore::delete()





* Visibility: **public**
* This method is defined in [classes/AttributeGroup.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#125)




### getAttributes

    array AttributeGroupCore::getAttributes(integer $id_lang, boolean $id_attribute_group)

Get all attributes for a given language / group



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/AttributeGroup.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#180)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;
* $id_attribute_group **boolean** - &lt;p&gt;Attribute group id&lt;/p&gt;



### getAttributesGroups

    array AttributeGroupCore::getAttributesGroups(integer $id_lang)

Get all attributes groups for a given language



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/AttributeGroup.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#202)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;



### deleteSelection

    mixed AttributeGroupCore::deleteSelection($selection)

Delete several objects from database

return boolean Deletion result

* Visibility: **public**
* This method is defined in [classes/AttributeGroup.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#223)


#### Arguments
* $selection **mixed**



### setWsProductOptionValues

    mixed AttributeGroupCore::setWsProductOptionValues($values)





* Visibility: **public**
* This method is defined in [classes/AttributeGroup.php line 235](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#235)


#### Arguments
* $values **mixed**



### getWsProductOptionValues

    mixed AttributeGroupCore::getWsProductOptionValues()





* Visibility: **public**
* This method is defined in [classes/AttributeGroup.php line 260](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#260)




### updatePosition

    boolean AttributeGroupCore::updatePosition(boolean $way, integer $position)

Move a group attribute



* Visibility: **public**
* This method is defined in [classes/AttributeGroup.php line 277](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#277)


#### Arguments
* $way **boolean** - &lt;p&gt;Up (1)  or Down (0)&lt;/p&gt;
* $position **integer**



### cleanPositions

    boolean AttributeGroupCore::cleanPositions()

Reorder group attribute position
Call it after deleting a group attribute.



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/AttributeGroup.php line 320](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#320)




### getHigherPosition

    integer AttributeGroupCore::getHigherPosition()

getHigherPosition

Get the higher group attribute position

* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/AttributeGroup.php line 348](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/AttributeGroup.php#348)



