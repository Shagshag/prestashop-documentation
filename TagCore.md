TagCore
===============






* Class name: TagCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in classes\Tag.php line 27





Properties
----------


### $id_lang

    public integer $id_lang





* Visibility: **public**
* This property is defined in classes\Tag.php line 30


### $name

    public string $name





* Visibility: **public**
* This property is defined in classes\Tag.php line 33


### $definition

    public mixed $definition = array('table' => 'tag', 'primary' => 'id_tag', 'fields' => array('id_lang' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 32)))





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\Tag.php line 38


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_lang' => array('xlink_resource' => 'languages')))





* Visibility: **protected**
* This property is defined in classes\Tag.php line 48


Methods
-------


### __construct

    mixed TagCore::__construct($id, $name, $id_lang)





* Visibility: **public**
* This method is defined in classes\Tag.php line 54


#### Arguments
* $id **mixed**
* $name **mixed**
* $id_lang **mixed**



### add

    mixed TagCore::add($autodate, $null_values)





* Visibility: **public**
* This method is defined in classes\Tag.php line 75


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### addTags

    boolean TagCore::addTags(integer $id_lang, integer $id_product, string|array $tag_list, $separator)

Add several tags in database and link it to a product



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Tag.php line 93


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;
* $id_product **integer** - &lt;p&gt;Product id to link tags with&lt;/p&gt;
* $tag_list **string|array** - &lt;p&gt;List of tags, as array or as a string with comas&lt;/p&gt;
* $separator **mixed**



### updateTagCount

    mixed TagCore::updateTagCount()





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Tag.php line 138




### getMainTags

    mixed TagCore::getMainTags($id_lang, $nb)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Tag.php line 170


#### Arguments
* $id_lang **mixed**
* $nb **mixed**



### getProductTags

    mixed TagCore::getProductTags($id_product)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Tag.php line 194


#### Arguments
* $id_product **mixed**



### getProducts

    mixed TagCore::getProducts($associated, \Context $context)





* Visibility: **public**
* This method is defined in classes\Tag.php line 210


#### Arguments
* $associated **mixed**
* $context **[Context](ContextCore)**



### setProducts

    mixed TagCore::setProducts($array)





* Visibility: **public**
* This method is defined in classes\Tag.php line 233


#### Arguments
* $array **mixed**



### deleteTagsForProduct

    mixed TagCore::deleteTagsForProduct($id_product)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Tag.php line 255


#### Arguments
* $id_product **mixed**


