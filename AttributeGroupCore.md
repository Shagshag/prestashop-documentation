AttributeGroupCore
===============






* Class name: AttributeGroupCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $name

    public string $name





* Visibility: **public**


### $is_color_group

    public mixed $is_color_group





* Visibility: **public**


### $position

    public mixed $position





* Visibility: **public**


### $group_type

    public mixed $group_type





* Visibility: **public**


### $public_name

    public string $public_name





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'attribute_group', 'primary' => 'id_attribute_group', 'multilang' => true, 'fields' => array('is_color_group' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'group_type' => array('type' => self::TYPE_STRING, 'required' => true), 'position' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 128), 'public_name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 64)))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'product_options', 'objectNodeName' => 'product_option', 'fields' => array(), 'associations' => array('product_option_values' => array('resource' => 'product_option_value', 'fields' => array('id' => array()))))





* Visibility: **protected**


Methods
-------


### add

    mixed AttributeGroupCore::add($autodate, $nullValues)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### update

    mixed AttributeGroupCore::update($nullValues)





* Visibility: **public**


#### Arguments
* $nullValues **mixed**



### cleanDeadCombinations

    mixed AttributeGroupCore::cleanDeadCombinations()





* Visibility: **public**
* This method is **static**.




### delete

    mixed AttributeGroupCore::delete()





* Visibility: **public**




### getAttributes

    array AttributeGroupCore::getAttributes(integer $id_lang, boolean $id_attribute_group)

Get all attributes for a given language / group



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;
* $id_attribute_group **boolean** - &lt;p&gt;Attribute group id&lt;/p&gt;



### getAttributesGroups

    array AttributeGroupCore::getAttributesGroups(integer $id_lang)

Get all attributes groups for a given language



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;



### deleteSelection

    mixed AttributeGroupCore::deleteSelection($selection)

Delete several objects from database

return boolean Deletion result

* Visibility: **public**


#### Arguments
* $selection **mixed**



### setWsProductOptionValues

    mixed AttributeGroupCore::setWsProductOptionValues($values)





* Visibility: **public**


#### Arguments
* $values **mixed**



### getWsProductOptionValues

    mixed AttributeGroupCore::getWsProductOptionValues()





* Visibility: **public**




### updatePosition

    boolean AttributeGroupCore::updatePosition(boolean $way, integer $position)

Move a group attribute



* Visibility: **public**


#### Arguments
* $way **boolean** - &lt;p&gt;Up (1)  or Down (0)&lt;/p&gt;
* $position **integer**



### cleanPositions

    boolean AttributeGroupCore::cleanPositions()

Reorder group attribute position
Call it after deleting a group attribute.



* Visibility: **public**
* This method is **static**.




### getHigherPosition

    integer AttributeGroupCore::getHigherPosition()

getHigherPosition

Get the higher group attribute position

* Visibility: **public**
* This method is **static**.



