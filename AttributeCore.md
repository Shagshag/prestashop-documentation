AttributeCore
===============






* Class name: AttributeCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id_attribute_group

    public integer $id_attribute_group





* Visibility: **public**


### $name

    public string $name





* Visibility: **public**


### $color

    public mixed $color





* Visibility: **public**


### $position

    public mixed $position





* Visibility: **public**


### $default

    public mixed $default





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'attribute', 'primary' => 'id_attribute', 'multilang' => true, 'fields' => array('id_attribute_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'color' => array('type' => self::TYPE_STRING, 'validate' => 'isColor'), 'position' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 128)))





* Visibility: **public**
* This property is **static**.


### $image_dir

    protected mixed $image_dir = _PS_COL_IMG_DIR_





* Visibility: **protected**


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'product_option_values', 'objectNodeName' => 'product_option_value', 'fields' => array('id_attribute_group' => array('xlink_resource' => 'product_options')))





* Visibility: **protected**


Methods
-------


### __construct

    mixed AttributeCore::__construct($id, $id_lang, $id_shop)





* Visibility: **public**


#### Arguments
* $id **mixed**
* $id_lang **mixed**
* $id_shop **mixed**



### delete

    mixed AttributeCore::delete()





* Visibility: **public**




### update

    mixed AttributeCore::update($null_values)





* Visibility: **public**


#### Arguments
* $null_values **mixed**



### add

    mixed AttributeCore::add($autodate, $null_values)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### getAttributes

    array AttributeCore::getAttributes(integer $id_lang, $not_null)

Get all attributes for a given language



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;
* $not_null **mixed**



### isAttribute

    mixed AttributeCore::isAttribute($id_attribute_group, $name, $id_lang)





* Visibility: **public**
* This method is **static**.


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


#### Arguments
* $id_product_attribute **integer** - &lt;p&gt;Product attribute combination id&lt;/p&gt;
* $qty **integer** - &lt;p&gt;Quantity needed&lt;/p&gt;
* $shop **Shop**



### getAttributeQty

    mixed AttributeCore::getAttributeQty($id_product)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**



### updateQtyProduct

    boolean AttributeCore::updateQtyProduct($arr)

Update array with veritable quantity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $arr **mixed**



### isColorAttribute

    boolean AttributeCore::isColorAttribute()

Return true if attribute is color type



* Visibility: **public**




### getAttributeMinimalQty

    mixed AttributeCore::getAttributeMinimalQty(integer $id_product_attribute)

Get minimal quantity for product with attributes quantity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product_attribute **integer**



### updatePosition

    boolean AttributeCore::updatePosition(boolean $way, integer $position)

Move an attribute inside its group



* Visibility: **public**


#### Arguments
* $way **boolean** - &lt;p&gt;Up (1)  or Down (0)&lt;/p&gt;
* $position **integer**



### cleanPositions

    boolean AttributeCore::cleanPositions(integer $id_attribute_group, boolean $use_last_attribute)

Reorder attribute position in group $id_attribute_group.

Call it after deleting an attribute from a group.

* Visibility: **public**


#### Arguments
* $id_attribute_group **integer**
* $use_last_attribute **boolean**



### getHigherPosition

    integer AttributeCore::getHigherPosition(integer $id_attribute_group)

getHigherPosition

Get the higher attribute position from a group attribute

* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_attribute_group **integer**


