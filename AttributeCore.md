AttributeCore
===============






* Class name: AttributeCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/Attribute.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attribute.php#L27)





Properties
----------

* [$id_attribute_group](#property-$id_attribute_group)
* [$name](#property-$name)
* [$color](#property-$color)
* [$position](#property-$position)
* [$default](#property-$default)
* [$definition](#property-$definition)
* [$image_dir](#property-$image_dir)
* [$webserviceParameters](#property-$webserviceParameters)

Methods
-------
* [__construct](#method-__construct)
* [delete](#method-delete)
* [update](#method-update)
* [add](#method-add)
* [getAttributes](#method-getAttributes)
* [isAttribute](#method-isAttribute)
* [checkAttributeQty](#method-checkAttributeQty)
* [getAttributeQty](#method-getAttributeQty)
* [updateQtyProduct](#method-updateQtyProduct)
* [isColorAttribute](#method-isColorAttribute)
* [getAttributeMinimalQty](#method-getAttributeMinimalQty)
* [updatePosition](#method-updatePosition)
* [cleanPositions](#method-cleanPositions)
* [getHigherPosition](#method-getHigherPosition)




Properties
----------


### <a name="property-$id_attribute_group"></a>$id_attribute_group

    public integer $id_attribute_group





* Visibility: **public**
* This property is defined in [classes/Attribute.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attribute.php#L30)


### <a name="property-$name"></a>$name

    public string $name





* Visibility: **public**
* This property is defined in [classes/Attribute.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attribute.php#L33)


### <a name="property-$color"></a>$color

    public mixed $color





* Visibility: **public**
* This property is defined in [classes/Attribute.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attribute.php#L34)


### <a name="property-$position"></a>$position

    public mixed $position





* Visibility: **public**
* This property is defined in [classes/Attribute.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attribute.php#L35)


### <a name="property-$default"></a>$default

    public mixed $default





* Visibility: **public**
* This property is defined in [classes/Attribute.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attribute.php#L36)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'attribute', 'primary' => 'id_attribute', 'multilang' => true, 'fields' => array('id_attribute_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'color' => array('type' => self::TYPE_STRING, 'validate' => 'isColor'), 'position' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 128)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Attribute.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attribute.php#L41)


### <a name="property-$image_dir"></a>$image_dir

    protected mixed $image_dir = _PS_COL_IMG_DIR_





* Visibility: **protected**
* This property is defined in [classes/Attribute.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attribute.php#L56)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'product_option_values', 'objectNodeName' => 'product_option_value', 'fields' => array('id_attribute_group' => array('xlink_resource' => 'product_options')))





* Visibility: **protected**
* This property is defined in [classes/Attribute.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attribute.php#L58)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AttributeCore::__construct($id, $id_lang, $id_shop)





* Visibility: **public**
* This method is defined in [classes/Attribute.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attribute.php#L66)


#### Arguments
* $id **mixed**
* $id_lang **mixed**
* $id_shop **mixed**



### <a name="method-delete"></a>delete

    mixed AttributeCore::delete()





* Visibility: **public**
* This method is defined in [classes/Attribute.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attribute.php#L73)




### <a name="method-update"></a>update

    mixed AttributeCore::update($null_values)





* Visibility: **public**
* This method is defined in [classes/Attribute.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attribute.php#L114)


#### Arguments
* $null_values **mixed**



### <a name="method-add"></a>add

    mixed AttributeCore::add($autodate, $null_values)





* Visibility: **public**
* This method is defined in [classes/Attribute.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attribute.php#L125)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-getAttributes"></a>getAttributes

    array AttributeCore::getAttributes(integer $id_lang, $not_null)

Get all attributes for a given language



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Attribute.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attribute.php#L147)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;
* $not_null **mixed**



### <a name="method-isAttribute"></a>isAttribute

    mixed AttributeCore::isAttribute($id_attribute_group, $name, $id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Attribute.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attribute.php#L169)


#### Arguments
* $id_attribute_group **mixed**
* $name **mixed**
* $id_lang **mixed**



### <a name="method-checkAttributeQty"></a>checkAttributeQty

    boolean AttributeCore::checkAttributeQty(integer $id_product_attribute, integer $qty, \Shop $shop)

Get quantity for a given attribute combination
Check if quantity is enough to deserve customer



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Attribute.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attribute.php#L201)


#### Arguments
* $id_product_attribute **integer** - &lt;p&gt;Product attribute combination id&lt;/p&gt;
* $qty **integer** - &lt;p&gt;Quantity needed&lt;/p&gt;
* $shop **[Shop](ShopCore)**



### <a name="method-getAttributeQty"></a>getAttributeQty

    mixed AttributeCore::getAttributeQty($id_product)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Attribute.php line 215](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attribute.php#L215)


#### Arguments
* $id_product **mixed**



### <a name="method-updateQtyProduct"></a>updateQtyProduct

    boolean AttributeCore::updateQtyProduct($arr)

Update array with veritable quantity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Attribute.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attribute.php#L229)


#### Arguments
* $arr **mixed**



### <a name="method-isColorAttribute"></a>isColorAttribute

    boolean AttributeCore::isColorAttribute()

Return true if attribute is color type



* Visibility: **public**
* This method is defined in [classes/Attribute.php line 250](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attribute.php#L250)




### <a name="method-getAttributeMinimalQty"></a>getAttributeMinimalQty

    mixed AttributeCore::getAttributeMinimalQty(integer $id_product_attribute)

Get minimal quantity for product with attributes quantity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Attribute.php line 273](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attribute.php#L273)


#### Arguments
* $id_product_attribute **integer**



### <a name="method-updatePosition"></a>updatePosition

    boolean AttributeCore::updatePosition(boolean $way, integer $position)

Move an attribute inside its group



* Visibility: **public**
* This method is defined in [classes/Attribute.php line 295](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attribute.php#L295)


#### Arguments
* $way **boolean** - &lt;p&gt;Up (1)  or Down (0)&lt;/p&gt;
* $position **integer**



### <a name="method-cleanPositions"></a>cleanPositions

    boolean AttributeCore::cleanPositions(integer $id_attribute_group, boolean $use_last_attribute)

Reorder attribute position in group $id_attribute_group.

Call it after deleting an attribute from a group.

* Visibility: **public**
* This method is defined in [classes/Attribute.php line 352](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attribute.php#L352)


#### Arguments
* $id_attribute_group **integer**
* $use_last_attribute **boolean**



### <a name="method-getHigherPosition"></a>getHigherPosition

    integer AttributeCore::getHigherPosition(integer $id_attribute_group)

getHigherPosition

Get the higher attribute position from a group attribute

* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Attribute.php line 374](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attribute.php#L374)


#### Arguments
* $id_attribute_group **integer**


