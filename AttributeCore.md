AttributeCore
===============






* Class name: AttributeCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in classes\Attribute.php line 27





Properties
----------


### $id_attribute_group

    public integer $id_attribute_group





* Visibility: **public**
* This property is defined in classes\Attribute.php line 30


### $name

    public string $name





* Visibility: **public**
* This property is defined in classes\Attribute.php line 33


### $color

    public mixed $color





* Visibility: **public**
* This property is defined in classes\Attribute.php line 34


### $position

    public mixed $position





* Visibility: **public**
* This property is defined in classes\Attribute.php line 35


### $default

    public mixed $default





* Visibility: **public**
* This property is defined in classes\Attribute.php line 36


### $definition

    public mixed $definition = array('table' => 'attribute', 'primary' => 'id_attribute', 'multilang' => true, 'fields' => array('id_attribute_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'color' => array('type' => self::TYPE_STRING, 'validate' => 'isColor'), 'position' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 128)))





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\Attribute.php line 41


### $image_dir

    protected mixed $image_dir = _PS_COL_IMG_DIR_





* Visibility: **protected**
* This property is defined in classes\Attribute.php line 56


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'product_option_values', 'objectNodeName' => 'product_option_value', 'fields' => array('id_attribute_group' => array('xlink_resource' => 'product_options')))





* Visibility: **protected**
* This property is defined in classes\Attribute.php line 58


Methods
-------


### __construct

    mixed AttributeCore::__construct($id, $id_lang, $id_shop)





* Visibility: **public**
* This method is defined in classes\Attribute.php line 66


#### Arguments
* $id **mixed**
* $id_lang **mixed**
* $id_shop **mixed**



### delete

    mixed AttributeCore::delete()





* Visibility: **public**
* This method is defined in classes\Attribute.php line 73




### update

    mixed AttributeCore::update($null_values)





* Visibility: **public**
* This method is defined in classes\Attribute.php line 114


#### Arguments
* $null_values **mixed**



### add

    mixed AttributeCore::add($autodate, $null_values)





* Visibility: **public**
* This method is defined in classes\Attribute.php line 125


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### getAttributes

    array AttributeCore::getAttributes(integer $id_lang, $not_null)

Get all attributes for a given language



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Attribute.php line 147


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;
* $not_null **mixed**



### isAttribute

    mixed AttributeCore::isAttribute($id_attribute_group, $name, $id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Attribute.php line 169


#### Arguments
* $id_attribute_group **mixed**
* $name **mixed**
* $id_lang **mixed**



### checkAttributeQty

    boolean AttributeCore::checkAttributeQty(integer $id_product_attribute, integer $qty, \Shop $shop)

Get quantity for a given attribute combination
Check if quantity is enough to deserve customer



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Attribute.php line 201


#### Arguments
* $id_product_attribute **integer** - &lt;p&gt;Product attribute combination id&lt;/p&gt;
* $qty **integer** - &lt;p&gt;Quantity needed&lt;/p&gt;
* $shop **[Shop](ShopCore)**



### getAttributeQty

    mixed AttributeCore::getAttributeQty($id_product)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Attribute.php line 215


#### Arguments
* $id_product **mixed**



### updateQtyProduct

    boolean AttributeCore::updateQtyProduct($arr)

Update array with veritable quantity



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Attribute.php line 229


#### Arguments
* $arr **mixed**



### isColorAttribute

    boolean AttributeCore::isColorAttribute()

Return true if attribute is color type



* Visibility: **public**
* This method is defined in classes\Attribute.php line 250




### getAttributeMinimalQty

    mixed AttributeCore::getAttributeMinimalQty(integer $id_product_attribute)

Get minimal quantity for product with attributes quantity



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Attribute.php line 273


#### Arguments
* $id_product_attribute **integer**



### updatePosition

    boolean AttributeCore::updatePosition(boolean $way, integer $position)

Move an attribute inside its group



* Visibility: **public**
* This method is defined in classes\Attribute.php line 295


#### Arguments
* $way **boolean** - &lt;p&gt;Up (1)  or Down (0)&lt;/p&gt;
* $position **integer**



### cleanPositions

    boolean AttributeCore::cleanPositions(integer $id_attribute_group, boolean $use_last_attribute)

Reorder attribute position in group $id_attribute_group.

Call it after deleting an attribute from a group.

* Visibility: **public**
* This method is defined in classes\Attribute.php line 352


#### Arguments
* $id_attribute_group **integer**
* $use_last_attribute **boolean**



### getHigherPosition

    integer AttributeCore::getHigherPosition(integer $id_attribute_group)

getHigherPosition

Get the higher attribute position from a group attribute

* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Attribute.php line 374


#### Arguments
* $id_attribute_group **integer**


