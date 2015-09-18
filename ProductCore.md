ProductCore
===============






* Class name: ProductCore
* Namespace: 
* Parent class: ObjectModel



Constants
----------


### CUSTOMIZE_FILE

    const CUSTOMIZE_FILE = 0





### CUSTOMIZE_TEXTFIELD

    const CUSTOMIZE_TEXTFIELD = 1





### PTYPE_SIMPLE

    const PTYPE_SIMPLE = 0





### PTYPE_PACK

    const PTYPE_PACK = 1





### PTYPE_VIRTUAL

    const PTYPE_VIRTUAL = 2





Properties
----------


### $tax_name

    public string $tax_name





* Visibility: **public**


### $tax_rate

    public string $tax_rate





* Visibility: **public**


### $id_manufacturer

    public integer $id_manufacturer





* Visibility: **public**


### $id_supplier

    public integer $id_supplier





* Visibility: **public**


### $id_category_default

    public integer $id_category_default





* Visibility: **public**


### $id_shop_default

    public integer $id_shop_default





* Visibility: **public**


### $manufacturer_name

    public string $manufacturer_name





* Visibility: **public**


### $supplier_name

    public string $supplier_name





* Visibility: **public**


### $name

    public string $name





* Visibility: **public**


### $description

    public string $description





* Visibility: **public**


### $description_short

    public string $description_short





* Visibility: **public**


### $quantity

    public integer $quantity





* Visibility: **public**


### $minimal_quantity

    public integer $minimal_quantity = 1





* Visibility: **public**


### $available_now

    public string $available_now





* Visibility: **public**


### $available_later

    public string $available_later





* Visibility: **public**


### $price

    public float $price





* Visibility: **public**


### $specificPrice

    public mixed $specificPrice





* Visibility: **public**


### $additional_shipping_cost

    public float $additional_shipping_cost





* Visibility: **public**


### $wholesale_price

    public float $wholesale_price





* Visibility: **public**


### $on_sale

    public boolean $on_sale = false





* Visibility: **public**


### $online_only

    public boolean $online_only = false





* Visibility: **public**


### $unity

    public string $unity = null





* Visibility: **public**


### $unit_price

    public float $unit_price





* Visibility: **public**


### $unit_price_ratio

    public float $unit_price_ratio





* Visibility: **public**


### $ecotax

    public float $ecotax





* Visibility: **public**


### $reference

    public string $reference





* Visibility: **public**


### $supplier_reference

    public string $supplier_reference





* Visibility: **public**


### $location

    public string $location





* Visibility: **public**


### $width

    public string $width





* Visibility: **public**


### $height

    public string $height





* Visibility: **public**


### $depth

    public string $depth





* Visibility: **public**


### $weight

    public string $weight





* Visibility: **public**


### $ean13

    public string $ean13





* Visibility: **public**


### $upc

    public string $upc





* Visibility: **public**


### $link_rewrite

    public string $link_rewrite





* Visibility: **public**


### $meta_description

    public string $meta_description





* Visibility: **public**


### $meta_keywords

    public string $meta_keywords





* Visibility: **public**


### $meta_title

    public string $meta_title





* Visibility: **public**


### $quantity_discount

    public boolean $quantity_discount





* Visibility: **public**


### $customizable

    public boolean $customizable





* Visibility: **public**


### $new

    public boolean $new = null





* Visibility: **public**


### $uploadable_files

    public integer $uploadable_files





* Visibility: **public**


### $text_fields

    public integer $text_fields





* Visibility: **public**


### $active

    public boolean $active = true





* Visibility: **public**


### $redirect_type

    public boolean $redirect_type = ''





* Visibility: **public**


### $id_product_redirected

    public boolean $id_product_redirected





* Visibility: **public**


### $available_for_order

    public boolean $available_for_order = true





* Visibility: **public**


### $available_date

    public string $available_date = '0000-00-00'





* Visibility: **public**


### $condition

    public string $condition





* Visibility: **public**


### $show_price

    public boolean $show_price = true





* Visibility: **public**


### $indexed

    public boolean $indexed





* Visibility: **public**


### $visibility

    public string $visibility





* Visibility: **public**


### $date_add

    public string $date_add





* Visibility: **public**


### $date_upd

    public string $date_upd





* Visibility: **public**


### $tags

    public mixed $tags





* Visibility: **public**


### $base_price

    public float $base_price





* Visibility: **public**


### $id_tax_rules_group

    public mixed $id_tax_rules_group = 1





* Visibility: **public**


### $id_color_default

    public mixed $id_color_default

We keep this variable for retrocompatibility for themes



* Visibility: **public**


### $advanced_stock_management

    public boolean $advanced_stock_management





* Visibility: **public**


### $out_of_stock

    public mixed $out_of_stock





* Visibility: **public**


### $depends_on_stock

    public mixed $depends_on_stock





* Visibility: **public**


### $isFullyLoaded

    public mixed $isFullyLoaded = false





* Visibility: **public**


### $cache_is_pack

    public mixed $cache_is_pack





* Visibility: **public**


### $cache_has_attachments

    public mixed $cache_has_attachments





* Visibility: **public**


### $is_virtual

    public mixed $is_virtual





* Visibility: **public**


### $id_pack_product_attribute

    public mixed $id_pack_product_attribute





* Visibility: **public**


### $cache_default_attribute

    public mixed $cache_default_attribute





* Visibility: **public**


### $category

    public string $category





* Visibility: **public**


### $pack_stock_type

    public integer $pack_stock_type = 3





* Visibility: **public**


### $_taxCalculationMethod

    public mixed $_taxCalculationMethod = null





* Visibility: **public**
* This property is **static**.


### $_prices

    protected mixed $_prices = array()





* Visibility: **protected**
* This property is **static**.


### $_pricesLevel2

    protected mixed $_pricesLevel2 = array()





* Visibility: **protected**
* This property is **static**.


### $_incat

    protected mixed $_incat = array()





* Visibility: **protected**
* This property is **static**.


### $_cart_quantity

    protected array $_cart_quantity = array()





* Visibility: **protected**
* This property is **static**.


### $_tax_rules_group

    protected mixed $_tax_rules_group = array()





* Visibility: **protected**
* This property is **static**.


### $_cacheFeatures

    protected mixed $_cacheFeatures = array()





* Visibility: **protected**
* This property is **static**.


### $_frontFeaturesCache

    protected mixed $_frontFeaturesCache = array()





* Visibility: **protected**
* This property is **static**.


### $producPropertiesCache

    protected mixed $producPropertiesCache = array()





* Visibility: **protected**
* This property is **static**.


### $cacheStock

    protected array $cacheStock = array()





* Visibility: **protected**
* This property is **static**.


### $definition

    public mixed $definition = array('table' => 'product', 'primary' => 'id_product', 'multilang' => true, 'multilang_shop' => true, 'fields' => array('id_shop_default' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_manufacturer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_supplier' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'reference' => array('type' => self::TYPE_STRING, 'validate' => 'isReference', 'size' => 32), 'supplier_reference' => array('type' => self::TYPE_STRING, 'validate' => 'isReference', 'size' => 32), 'location' => array('type' => self::TYPE_STRING, 'validate' => 'isReference', 'size' => 64), 'width' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat'), 'height' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat'), 'depth' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat'), 'weight' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat'), 'quantity_discount' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'ean13' => array('type' => self::TYPE_STRING, 'validate' => 'isEan13', 'size' => 13), 'upc' => array('type' => self::TYPE_STRING, 'validate' => 'isUpc', 'size' => 12), 'cache_is_pack' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'cache_has_attachments' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'is_virtual' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'id_category_default' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedId'), 'id_tax_rules_group' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedId'), 'on_sale' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'online_only' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'ecotax' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isPrice'), 'minimal_quantity' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedInt'), 'price' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isPrice', 'required' => true), 'wholesale_price' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isPrice'), 'unity' => array('type' => self::TYPE_STRING, 'shop' => true, 'validate' => 'isString'), 'unit_price_ratio' => array('type' => self::TYPE_FLOAT, 'shop' => true), 'additional_shipping_cost' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isPrice'), 'customizable' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedInt'), 'text_fields' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedInt'), 'uploadable_files' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedInt'), 'active' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'redirect_type' => array('type' => self::TYPE_STRING, 'shop' => true, 'validate' => 'isString'), 'id_product_redirected' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedId'), 'available_for_order' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'available_date' => array('type' => self::TYPE_DATE, 'shop' => true, 'validate' => 'isDateFormat'), 'condition' => array('type' => self::TYPE_STRING, 'shop' => true, 'validate' => 'isGenericName', 'values' => array('new', 'used', 'refurbished'), 'default' => 'new'), 'show_price' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'indexed' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'visibility' => array('type' => self::TYPE_STRING, 'shop' => true, 'validate' => 'isProductVisibility', 'values' => array('both', 'catalog', 'search', 'none'), 'default' => 'both'), 'cache_default_attribute' => array('type' => self::TYPE_INT, 'shop' => true), 'advanced_stock_management' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'date_add' => array('type' => self::TYPE_DATE, 'shop' => true, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'shop' => true, 'validate' => 'isDate'), 'pack_stock_type' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedInt'), 'meta_description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_keywords' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_title' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 128), 'link_rewrite' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isLinkRewrite', 'required' => true, 'size' => 128, 'ws_modifier' => array('http_method' => \WebserviceRequest::HTTP_POST, 'modifier' => 'modifierWsLinkRewrite')), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isCatalogName', 'required' => true, 'size' => 128), 'description' => array('type' => self::TYPE_HTML, 'lang' => true, 'validate' => 'isCleanHtml'), 'description_short' => array('type' => self::TYPE_HTML, 'lang' => true, 'validate' => 'isCleanHtml'), 'available_now' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'available_later' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'IsGenericName', 'size' => 255)), 'associations' => array('manufacturer' => array('type' => self::HAS_ONE), 'supplier' => array('type' => self::HAS_ONE), 'default_category' => array('type' => self::HAS_ONE, 'field' => 'id_category_default', 'object' => 'Category'), 'tax_rules_group' => array('type' => self::HAS_ONE), 'categories' => array('type' => self::HAS_MANY, 'field' => 'id_category', 'object' => 'Category', 'association' => 'category_product'), 'stock_availables' => array('type' => self::HAS_MANY, 'field' => 'id_stock_available', 'object' => 'StockAvailable', 'association' => 'stock_availables')))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectMethods' => array('add' => 'addWs', 'update' => 'updateWs'), 'objectNodeNames' => 'products', 'fields' => array('id_manufacturer' => array('xlink_resource' => 'manufacturers'), 'id_supplier' => array('xlink_resource' => 'suppliers'), 'id_category_default' => array('xlink_resource' => 'categories'), 'new' => array(), 'cache_default_attribute' => array(), 'id_default_image' => array('getter' => 'getCoverWs', 'setter' => 'setCoverWs', 'xlink_resource' => array('resourceName' => 'images', 'subResourceName' => 'products')), 'id_default_combination' => array('getter' => 'getWsDefaultCombination', 'setter' => 'setWsDefaultCombination', 'xlink_resource' => array('resourceName' => 'combinations')), 'id_tax_rules_group' => array('xlink_resource' => array('resourceName' => 'tax_rule_groups')), 'position_in_category' => array('getter' => 'getWsPositionInCategory', 'setter' => 'setWsPositionInCategory'), 'manufacturer_name' => array('getter' => 'getWsManufacturerName', 'setter' => false), 'quantity' => array('getter' => false, 'setter' => false), 'type' => array('getter' => 'getWsType', 'setter' => 'setWsType')), 'associations' => array('categories' => array('resource' => 'category', 'fields' => array('id' => array('required' => true))), 'images' => array('resource' => 'image', 'fields' => array('id' => array())), 'combinations' => array('resource' => 'combination', 'fields' => array('id' => array('required' => true))), 'product_option_values' => array('resource' => 'product_option_value', 'fields' => array('id' => array('required' => true))), 'product_features' => array('resource' => 'product_feature', 'fields' => array('id' => array('required' => true), 'id_feature_value' => array('required' => true, 'xlink_resource' => 'product_feature_values'))), 'tags' => array('resource' => 'tag', 'fields' => array('id' => array('required' => true))), 'stock_availables' => array('resource' => 'stock_available', 'fields' => array('id' => array('required' => true), 'id_product_attribute' => array('required' => true)), 'setter' => false), 'accessories' => array('resource' => 'product', 'api' => 'products', 'fields' => array('id' => array('required' => true, 'xlink_resource' => 'product'))), 'product_bundle' => array('resource' => 'product', 'api' => 'products', 'fields' => array('id' => array('required' => true), 'quantity' => array()))))





* Visibility: **protected**


Methods
-------


### __construct

    mixed ProductCore::__construct($id_product, $full, $id_lang, $id_shop, \Context $context)





* Visibility: **public**


#### Arguments
* $id_product **mixed**
* $full **mixed**
* $id_lang **mixed**
* $id_shop **mixed**
* $context **Context**



### getFieldsShop

    array ProductCore::getFieldsShop()





* Visibility: **public**




### add

    mixed ProductCore::add($autodate, $null_values)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### update

    mixed ProductCore::update($null_values)





* Visibility: **public**


#### Arguments
* $null_values **mixed**



### initPricesComputation

    mixed ProductCore::initPricesComputation($id_customer)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_customer **mixed**



### getTaxCalculationMethod

    mixed ProductCore::getTaxCalculationMethod($id_customer)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_customer **mixed**



### updatePosition

    mixed ProductCore::updatePosition(boolean $way, integer $position)

Move a product inside its category



* Visibility: **public**


#### Arguments
* $way **boolean** - &lt;p&gt;Up (1)  or Down (0)&lt;/p&gt;
* $position **integer** - &lt;p&gt;return boolean Update result&lt;/p&gt;



### cleanPositions

    mixed ProductCore::cleanPositions($id_category, $position)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_category **mixed**
* $position **mixed**



### getDefaultAttribute

    integer ProductCore::getDefaultAttribute($id_product, $minimum_quantity, $reset)

Get the default attribute for a product



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**
* $minimum_quantity **mixed**
* $reset **mixed**



### setAvailableDate

    mixed ProductCore::setAvailableDate($available_date)





* Visibility: **public**


#### Arguments
* $available_date **mixed**



### getAvailableDate

    \string/null ProductCore::getAvailableDate(integer $id_product, integer $id_product_attribute)

For a given id_product and id_product_attribute, return available date



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - &lt;p&gt;Optional&lt;/p&gt;



### updateIsVirtual

    mixed ProductCore::updateIsVirtual($id_product, $is_virtual)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**
* $is_virtual **mixed**



### validateField

    mixed ProductCore::validateField($field, $value, $id_lang, $skip, $human_errors)





* Visibility: **public**


#### Arguments
* $field **mixed**
* $value **mixed**
* $id_lang **mixed**
* $skip **mixed**
* $human_errors **mixed**



### toggleStatus

    mixed ProductCore::toggleStatus()





* Visibility: **public**




### delete

    mixed ProductCore::delete()





* Visibility: **public**




### deleteSelection

    mixed ProductCore::deleteSelection($products)





* Visibility: **public**


#### Arguments
* $products **mixed**



### deleteFromCartRules

    mixed ProductCore::deleteFromCartRules()





* Visibility: **public**




### deleteFromSupplier

    mixed ProductCore::deleteFromSupplier()





* Visibility: **public**




### addToCategories

    boolean ProductCore::addToCategories(mixed $categories)

addToCategories add this product to the category/ies if not exists.



* Visibility: **public**


#### Arguments
* $categories **mixed** - &lt;p&gt;id_category or array of id_category&lt;/p&gt;



### updateCategories

    array ProductCore::updateCategories($categories, boolean $keeping_current_pos)

Update categories to index product into



* Visibility: **public**


#### Arguments
* $categories **mixed**
* $keeping_current_pos **boolean** - &lt;p&gt;(deprecated, no more used)&lt;/p&gt;



### deleteCategory

    boolean ProductCore::deleteCategory(mixed $id_category, mixed $clean_positions)

deleteCategory delete this product from the category $id_category



* Visibility: **public**


#### Arguments
* $id_category **mixed**
* $clean_positions **mixed**



### deleteCategories

    array ProductCore::deleteCategories(boolean $clean_positions)

Delete all association to category where product is indexed



* Visibility: **public**


#### Arguments
* $clean_positions **boolean** - &lt;p&gt;clean category positions after deletion&lt;/p&gt;



### deleteTags

    array ProductCore::deleteTags()

Delete products tags entries



* Visibility: **public**




### deleteCartProducts

    array ProductCore::deleteCartProducts()

Delete product from cart



* Visibility: **public**




### deleteImages

    boolean ProductCore::deleteImages()

Delete product images from database



* Visibility: **public**




### getProductAttributePrice

    mixed ProductCore::getProductAttributePrice($id_product_attribute)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product_attribute **mixed**



### getProducts

    array ProductCore::getProducts(integer $id_lang, integer $start, integer $limit, string $order_by, string $order_way, $id_category, $only_active, \Context $context)

Get all available products



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;
* $start **integer** - &lt;p&gt;Start number&lt;/p&gt;
* $limit **integer** - &lt;p&gt;Number of products to return&lt;/p&gt;
* $order_by **string** - &lt;p&gt;Field for ordering&lt;/p&gt;
* $order_way **string** - &lt;p&gt;Way for ordering (ASC or DESC)&lt;/p&gt;
* $id_category **mixed**
* $only_active **mixed**
* $context **Context**



### getSimpleProducts

    mixed ProductCore::getSimpleProducts($id_lang, \Context $context)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **mixed**
* $context **Context**



### isNew

    mixed ProductCore::isNew()





* Visibility: **public**




### productAttributeExists

    mixed ProductCore::productAttributeExists($attributes_list, $current_product_attribute, \Context $context, $all_shops, $return_id)





* Visibility: **public**


#### Arguments
* $attributes_list **mixed**
* $current_product_attribute **mixed**
* $context **Context**
* $all_shops **mixed**
* $return_id **mixed**



### addProductAttribute

    mixed ProductCore::addProductAttribute($price, $weight, $unit_impact, $ecotax, $quantity, $id_images, $reference, $id_supplier, $ean13, $default, $location, $upc, $minimal_quantity)

addProductAttribute is deprecated

The quantity params now set StockAvailable for the current shop with the specified quantity
The supplier_reference params now set the supplier reference of the default supplier of the product if possible

* Visibility: **public**


#### Arguments
* $price **mixed**
* $weight **mixed**
* $unit_impact **mixed**
* $ecotax **mixed**
* $quantity **mixed**
* $id_images **mixed**
* $reference **mixed**
* $id_supplier **mixed**
* $ean13 **mixed**
* $default **mixed**
* $location **mixed**
* $upc **mixed**
* $minimal_quantity **mixed**



### generateMultipleCombinations

    mixed ProductCore::generateMultipleCombinations($combinations, $attributes)





* Visibility: **public**


#### Arguments
* $combinations **mixed**
* $attributes **mixed**



### addCombinationEntity

    mixed ProductCore::addCombinationEntity($wholesale_price, $price, $weight, $unit_impact, $ecotax, integer $quantity, $id_images, $reference, $id_supplier, $ean13, $default, $location, $upc, $minimal_quantity, array $id_shop_list, $available_date)





* Visibility: **public**


#### Arguments
* $wholesale_price **mixed**
* $price **mixed**
* $weight **mixed**
* $unit_impact **mixed**
* $ecotax **mixed**
* $quantity **integer** - &lt;p&gt;DEPRECATED&lt;/p&gt;
* $id_images **mixed**
* $reference **mixed**
* $id_supplier **mixed**
* $ean13 **mixed**
* $default **mixed**
* $location **mixed**
* $upc **mixed**
* $minimal_quantity **mixed**
* $id_shop_list **array**
* $available_date **mixed**



### addProductAttributeMultiple

    array ProductCore::addProductAttributeMultiple($attributes, boolean $set_default)





* Visibility: **public**


#### Arguments
* $attributes **mixed**
* $set_default **boolean**



### deleteDefaultAttributes

    mixed ProductCore::deleteDefaultAttributes()

Del all default attributes for product



* Visibility: **public**




### setDefaultAttribute

    mixed ProductCore::setDefaultAttribute($id_product_attribute)





* Visibility: **public**


#### Arguments
* $id_product_attribute **mixed**



### updateDefaultAttribute

    mixed ProductCore::updateDefaultAttribute($id_product)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**



### updateProductAttribute

    mixed ProductCore::updateProductAttribute($id_product_attribute, $wholesale_price, $price, $weight, $unit, $ecotax, $id_images, $reference, $id_supplier, $ean13, $default, $location, $upc, $minimal_quantity, $available_date)

Update a product attribute



* Visibility: **public**


#### Arguments
* $id_product_attribute **mixed**
* $wholesale_price **mixed**
* $price **mixed**
* $weight **mixed**
* $unit **mixed**
* $ecotax **mixed**
* $id_images **mixed**
* $reference **mixed**
* $id_supplier **mixed**
* $ean13 **mixed**
* $default **mixed**
* $location **mixed**
* $upc **mixed**
* $minimal_quantity **mixed**
* $available_date **mixed**



### addSupplierReference

    mixed ProductCore::addSupplierReference(integer $id_supplier, integer $id_product_attribute, string $supplier_reference, float $price, integer $id_currency)

Sets or updates Supplier Reference



* Visibility: **public**


#### Arguments
* $id_supplier **integer**
* $id_product_attribute **integer**
* $supplier_reference **string**
* $price **float**
* $id_currency **integer**



### updateAttribute

    array ProductCore::updateAttribute(integer $id_product_attribute, float $wholesale_price, float $price, float $weight, float $unit, float $ecotax, $id_images, string $reference, string $ean13, integer $default, $location, string $upc, string $minimal_quantity, $available_date, $update_all_fields, array $id_shop_list)

Update a product attribute



* Visibility: **public**


#### Arguments
* $id_product_attribute **integer** - &lt;p&gt;Product attribute id&lt;/p&gt;
* $wholesale_price **float** - &lt;p&gt;Wholesale price&lt;/p&gt;
* $price **float** - &lt;p&gt;Additional price&lt;/p&gt;
* $weight **float** - &lt;p&gt;Additional weight&lt;/p&gt;
* $unit **float**
* $ecotax **float** - &lt;p&gt;Additional ecotax&lt;/p&gt;
* $id_images **mixed**
* $reference **string** - &lt;p&gt;Reference&lt;/p&gt;
* $ean13 **string** - &lt;p&gt;Ean-13 barcode&lt;/p&gt;
* $default **integer** - &lt;p&gt;Default On&lt;/p&gt;
* $location **mixed**
* $upc **string** - &lt;p&gt;Upc barcode&lt;/p&gt;
* $minimal_quantity **string** - &lt;p&gt;Minimal quantity&lt;/p&gt;
* $available_date **mixed**
* $update_all_fields **mixed**
* $id_shop_list **array**



### addAttribute

    mixed ProductCore::addAttribute(float $price, float $weight, $unit_impact, float $ecotax, integer $id_images, string $reference, string $ean13, boolean $default, string $location, $upc, integer $minimal_quantity, array $id_shop_list, $available_date)

Add a product attribute



* Visibility: **public**


#### Arguments
* $price **float** - &lt;p&gt;Additional price&lt;/p&gt;
* $weight **float** - &lt;p&gt;Additional weight&lt;/p&gt;
* $unit_impact **mixed**
* $ecotax **float** - &lt;p&gt;Additional ecotax&lt;/p&gt;
* $id_images **integer** - &lt;p&gt;Image ids&lt;/p&gt;
* $reference **string** - &lt;p&gt;Reference&lt;/p&gt;
* $ean13 **string** - &lt;p&gt;Ean-13 barcode&lt;/p&gt;
* $default **boolean** - &lt;p&gt;Is default attribute for product&lt;/p&gt;
* $location **string** - &lt;p&gt;Location&lt;/p&gt;
* $upc **mixed**
* $minimal_quantity **integer** - &lt;p&gt;Minimal quantity to add to cart&lt;/p&gt;
* $id_shop_list **array**
* $available_date **mixed**



### updateQuantityProductWithAttributeQuantity

    mixed ProductCore::updateQuantityProductWithAttributeQuantity()





* Visibility: **public**




### deleteProductAttributes

    array ProductCore::deleteProductAttributes()

Delete product attributes



* Visibility: **public**




### deleteAttributesImpacts

    boolean ProductCore::deleteAttributesImpacts()

Delete product attributes impacts



* Visibility: **public**




### deleteProductFeatures

    array ProductCore::deleteProductFeatures()

Delete product features



* Visibility: **public**




### updateCacheAttachment

    mixed ProductCore::updateCacheAttachment($id_product)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**



### deleteAttachments

    array ProductCore::deleteAttachments($update_attachment_cache)

Delete product attachments



* Visibility: **public**


#### Arguments
* $update_attachment_cache **mixed**



### deleteCustomization

    array ProductCore::deleteCustomization()

Delete product customizations



* Visibility: **public**




### deletePack

    array ProductCore::deletePack()

Delete product pack details



* Visibility: **public**




### deleteProductSale

    array ProductCore::deleteProductSale()

Delete product sales



* Visibility: **public**




### deleteSceneProducts

    array ProductCore::deleteSceneProducts()

Delete product in its scenes



* Visibility: **public**




### deleteSearchIndexes

    array ProductCore::deleteSearchIndexes()

Delete product indexed words



* Visibility: **public**




### addAttributeCombinaison

    array ProductCore::addAttributeCombinaison(integer $id_product_attribute, array $attributes)

Add a product attributes combinaison



* Visibility: **public**


#### Arguments
* $id_product_attribute **integer** - &lt;p&gt;Product attribute id&lt;/p&gt;
* $attributes **array** - &lt;p&gt;Attributes to forge combinaison&lt;/p&gt;



### addAttributeCombinationMultiple

    boolean ProductCore::addAttributeCombinationMultiple($id_attributes, $combinations)





* Visibility: **public**


#### Arguments
* $id_attributes **mixed**
* $combinations **mixed**



### deleteAttributeCombination

    array ProductCore::deleteAttributeCombination(integer $id_product_attribute)

Delete a product attributes combination



* Visibility: **public**


#### Arguments
* $id_product_attribute **integer** - &lt;p&gt;Product attribute id&lt;/p&gt;



### deleteFeatures

    mixed ProductCore::deleteFeatures()

Delete features



* Visibility: **public**




### getAttributesResume

    array ProductCore::getAttributesResume(integer $id_lang, $attribute_value_separator, $attribute_separator)

Get all available product attributes resume



* Visibility: **public**


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;
* $attribute_value_separator **mixed**
* $attribute_separator **mixed**



### getAttributeCombinations

    array ProductCore::getAttributeCombinations(integer $id_lang)

Get all available product attributes combinations



* Visibility: **public**


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;



### getAttributeCombinationsById

    array ProductCore::getAttributeCombinationsById(integer $id_product_attribute, integer $id_lang)

Get product attribute combination by id_product_attribute



* Visibility: **public**


#### Arguments
* $id_product_attribute **integer**
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;



### getCombinationImages

    mixed ProductCore::getCombinationImages($id_lang)





* Visibility: **public**


#### Arguments
* $id_lang **mixed**



### getCombinationImageById

    mixed ProductCore::getCombinationImageById($id_product_attribute, $id_lang)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product_attribute **mixed**
* $id_lang **mixed**



### hasAttributes

    integer ProductCore::hasAttributes()

Check if product has attributes combinations



* Visibility: **public**




### getNewProducts

    array ProductCore::getNewProducts(integer $id_lang, $page_number, $nb_products, $count, $order_by, $order_way, \Context $context)

Get new products



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;
* $page_number **mixed**
* $nb_products **mixed**
* $count **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $context **Context**



### _getProductIdByDate

    mixed ProductCore::_getProductIdByDate($beginning, $ending, \Context $context, $with_combination)





* Visibility: **protected**
* This method is **static**.


#### Arguments
* $beginning **mixed**
* $ending **mixed**
* $context **Context**
* $with_combination **mixed**



### getRandomSpecial

    array ProductCore::getRandomSpecial(integer $id_lang, $beginning, $ending, \Context $context)

Get a random special



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;
* $beginning **mixed**
* $ending **mixed**
* $context **Context**



### getPricesDrop

    array ProductCore::getPricesDrop(integer $id_lang, $page_number, $nb_products, boolean $count, $order_by, $order_way, $beginning, $ending, \Context $context)

Get prices drop



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;
* $page_number **mixed**
* $nb_products **mixed**
* $count **boolean** - &lt;p&gt;Only in order to get total number (optional)&lt;/p&gt;
* $order_by **mixed**
* $order_way **mixed**
* $beginning **mixed**
* $ending **mixed**
* $context **Context**



### getProductCategories

    array ProductCore::getProductCategories($id_product)

getProductCategories return an array of categories which this product belongs to



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**



### getProductCategoriesFull

    mixed ProductCore::getProductCategoriesFull($id_product, $id_lang)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**
* $id_lang **mixed**



### getCategories

    array ProductCore::getCategories()

getCategories return an array of categories which this product belongs to



* Visibility: **public**




### getCarriers

    mixed ProductCore::getCarriers()

Gets carriers assigned to the product



* Visibility: **public**




### setCarriers

    mixed ProductCore::setCarriers($carrier_list)

Sets carriers assigned to the product



* Visibility: **public**


#### Arguments
* $carrier_list **mixed**



### getImages

    array ProductCore::getImages(integer $id_lang, \Context $context)

Get product images and legends



* Visibility: **public**


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id for multilingual legends&lt;/p&gt;
* $context **Context**



### getCover

    array ProductCore::getCover($id_product, \Context $context)

Get product cover image



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**
* $context **Context**



### getPriceStatic

    float ProductCore::getPriceStatic(integer $id_product, boolean $usetax, integer|null $id_product_attribute, integer $decimals, integer|null $divisor, boolean $only_reduc, boolean $usereduc, integer $quantity, boolean $force_associated_tax, integer|null $id_customer, integer|null $id_cart, integer|null $id_address, null $specific_price_output, boolean $with_ecotax, boolean $use_group_reduction, \Context $context, boolean $use_customer_price)

Returns product price



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **integer** - &lt;p&gt;Product id&lt;/p&gt;
* $usetax **boolean** - &lt;p&gt;With taxes or not (optional)&lt;/p&gt;
* $id_product_attribute **integer|null** - &lt;p&gt;Product attribute id (optional).&lt;/p&gt;
&lt;pre&gt;&lt;code&gt;                                   If set to false, do not apply the combination price impact.
                                   NULL does apply the default combination price impact.&lt;/code&gt;&lt;/pre&gt;
* $decimals **integer** - &lt;p&gt;Number of decimals (optional)&lt;/p&gt;
* $divisor **integer|null** - &lt;p&gt;Useful when paying many time without fees (optional)&lt;/p&gt;
* $only_reduc **boolean** - &lt;p&gt;Returns only the reduction amount&lt;/p&gt;
* $usereduc **boolean** - &lt;p&gt;Set if the returned amount will include reduction&lt;/p&gt;
* $quantity **integer** - &lt;p&gt;Required for quantity discount application (default value: 1)&lt;/p&gt;
* $force_associated_tax **boolean** - &lt;p&gt;DEPRECATED - NOT USED Force to apply the associated tax.&lt;/p&gt;
&lt;pre&gt;&lt;code&gt;                                   Only works when the parameter $usetax is true&lt;/code&gt;&lt;/pre&gt;
* $id_customer **integer|null** - &lt;p&gt;Customer ID (for customer group reduction)&lt;/p&gt;
* $id_cart **integer|null** - &lt;p&gt;Cart ID. Required when the cookie is not accessible&lt;/p&gt;
&lt;pre&gt;&lt;code&gt;                                   (e.g., inside a payment module, a cron task...)&lt;/code&gt;&lt;/pre&gt;
* $id_address **integer|null** - &lt;p&gt;Customer address ID. Required for price (tax included)&lt;/p&gt;
&lt;pre&gt;&lt;code&gt;                                   calculation regarding the guest localization&lt;/code&gt;&lt;/pre&gt;
* $specific_price_output **null** - &lt;p&gt;If a specific price applies regarding the previous parameters,
                                       this variable is filled with the corresponding SpecificPrice object&lt;/p&gt;
* $with_ecotax **boolean** - &lt;p&gt;Insert ecotax in price output.&lt;/p&gt;
* $use_group_reduction **boolean**
* $context **Context**
* $use_customer_price **boolean**



### priceCalculation

    float ProductCore::priceCalculation(integer $id_shop, integer $id_product, integer $id_product_attribute, integer $id_country, integer $id_state, string $zipcode, integer $id_currency, integer $id_group, integer $quantity, boolean $use_tax, integer $decimals, boolean $only_reduc, boolean $use_reduc, boolean $with_ecotax, null $specific_price, boolean $use_group_reduction, integer $id_customer, boolean $use_customer_price, integer $id_cart, integer $real_quantity)

Price calculation / Get product price



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_shop **integer** - &lt;p&gt;Shop id&lt;/p&gt;
* $id_product **integer** - &lt;p&gt;Product id&lt;/p&gt;
* $id_product_attribute **integer** - &lt;p&gt;Product attribute id&lt;/p&gt;
* $id_country **integer** - &lt;p&gt;Country id&lt;/p&gt;
* $id_state **integer** - &lt;p&gt;State id&lt;/p&gt;
* $zipcode **string**
* $id_currency **integer** - &lt;p&gt;Currency id&lt;/p&gt;
* $id_group **integer** - &lt;p&gt;Group id&lt;/p&gt;
* $quantity **integer** - &lt;p&gt;Quantity Required for Specific prices : quantity discount application&lt;/p&gt;
* $use_tax **boolean** - &lt;p&gt;with (1) or without (0) tax&lt;/p&gt;
* $decimals **integer** - &lt;p&gt;Number of decimals returned&lt;/p&gt;
* $only_reduc **boolean** - &lt;p&gt;Returns only the reduction amount&lt;/p&gt;
* $use_reduc **boolean** - &lt;p&gt;Set if the returned amount will include reduction&lt;/p&gt;
* $with_ecotax **boolean** - &lt;p&gt;insert ecotax in price output.&lt;/p&gt;
* $specific_price **null** - &lt;p&gt;If a specific price applies regarding the previous parameters,
                              this variable is filled with the corresponding SpecificPrice object&lt;/p&gt;
* $use_group_reduction **boolean**
* $id_customer **integer**
* $use_customer_price **boolean**
* $id_cart **integer**
* $real_quantity **integer**



### convertAndFormatPrice

    mixed ProductCore::convertAndFormatPrice($price, $currency, \Context $context)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $price **mixed**
* $currency **mixed**
* $context **Context**



### isDiscounted

    mixed ProductCore::isDiscounted($id_product, $quantity, \Context $context)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**
* $quantity **mixed**
* $context **Context**



### getPrice

    float ProductCore::getPrice(boolean $tax, integer $id_product_attribute, integer $decimals, integer $divisor, $only_reduc, $usereduc, $quantity)

Get product price
Same as static function getPriceStatic, no need to specify product id



* Visibility: **public**


#### Arguments
* $tax **boolean** - &lt;p&gt;With taxes or not (optional)&lt;/p&gt;
* $id_product_attribute **integer** - &lt;p&gt;Product attribute id (optional)&lt;/p&gt;
* $decimals **integer** - &lt;p&gt;Number of decimals (optional)&lt;/p&gt;
* $divisor **integer** - &lt;p&gt;Util when paying many time without fees (optional)&lt;/p&gt;
* $only_reduc **mixed**
* $usereduc **mixed**
* $quantity **mixed**



### getPublicPrice

    mixed ProductCore::getPublicPrice($tax, $id_product_attribute, $decimals, $divisor, $only_reduc, $usereduc, $quantity)





* Visibility: **public**


#### Arguments
* $tax **mixed**
* $id_product_attribute **mixed**
* $decimals **mixed**
* $divisor **mixed**
* $only_reduc **mixed**
* $usereduc **mixed**
* $quantity **mixed**



### getIdProductAttributeMostExpensive

    mixed ProductCore::getIdProductAttributeMostExpensive()





* Visibility: **public**




### getDefaultIdProductAttribute

    mixed ProductCore::getDefaultIdProductAttribute()





* Visibility: **public**




### getPriceWithoutReduct

    mixed ProductCore::getPriceWithoutReduct($notax, $id_product_attribute, $decimals)





* Visibility: **public**


#### Arguments
* $notax **mixed**
* $id_product_attribute **mixed**
* $decimals **mixed**



### convertPrice

    string ProductCore::convertPrice(array $params, $smarty)

Display price with right format and currency



* Visibility: **public**
* This method is **static**.


#### Arguments
* $params **array** - &lt;p&gt;Params&lt;/p&gt;
* $smarty **mixed** - &lt;p&gt;Smarty object&lt;/p&gt;



### convertPriceWithCurrency

    string ProductCore::convertPriceWithCurrency(array $params, object $smarty)

Convert price with currency



* Visibility: **public**
* This method is **static**.


#### Arguments
* $params **array**
* $smarty **object** - &lt;p&gt;DEPRECATED&lt;/p&gt;



### displayWtPrice

    mixed ProductCore::displayWtPrice($params, $smarty)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $params **mixed**
* $smarty **mixed**



### displayWtPriceWithCurrency

    string ProductCore::displayWtPriceWithCurrency(array $params, \Smarty $smarty)

Display WT price with currency



* Visibility: **public**
* This method is **static**.


#### Arguments
* $params **array**
* $smarty **Smarty** - &lt;p&gt;DEPRECATED&lt;/p&gt;



### getQuantity

    integer ProductCore::getQuantity(integer $id_product, integer $id_product_attribute, $cache_is_pack)

Get available product quantities



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **integer** - &lt;p&gt;Product id&lt;/p&gt;
* $id_product_attribute **integer** - &lt;p&gt;Product attribute id (optional)&lt;/p&gt;
* $cache_is_pack **mixed**



### sqlStock

    string ProductCore::sqlStock($product_alias, $product_attribute, $inner_join, \Shop $shop)

Create JOIN query with 'stock_available' table



* Visibility: **public**
* This method is **static**.


#### Arguments
* $product_alias **mixed**
* $product_attribute **mixed**
* $inner_join **mixed**
* $shop **Shop**



### updateQuantity

    false ProductCore::updateQuantity()





* Visibility: **public**
* This method is **static**.




### reinjectQuantities

    false ProductCore::reinjectQuantities()





* Visibility: **public**
* This method is **static**.




### isAvailableWhenOutOfStock

    mixed ProductCore::isAvailableWhenOutOfStock($out_of_stock)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $out_of_stock **mixed**



### checkQty

    boolean ProductCore::checkQty(integer $qty)

Check product availability



* Visibility: **public**


#### Arguments
* $qty **integer** - &lt;p&gt;Quantity desired&lt;/p&gt;



### checkDefaultAttributes

    mixed ProductCore::checkDefaultAttributes()

Check if there is no default attribute and create it if not



* Visibility: **public**




### getAttributesColorList

    mixed ProductCore::getAttributesColorList(array $products, $have_stock)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $products **array**
* $have_stock **mixed**



### getAttributesGroups

    array ProductCore::getAttributesGroups(integer $id_lang)

Get all available attribute groups



* Visibility: **public**


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;



### deleteAccessories

    mixed ProductCore::deleteAccessories()

Delete product accessories



* Visibility: **public**




### deleteFromAccessories

    mixed ProductCore::deleteFromAccessories()

Delete product from other products accessories



* Visibility: **public**




### getAccessoriesLight

    array ProductCore::getAccessoriesLight(integer $id_lang, integer $id_product)

Get product accessories (only names)



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;
* $id_product **integer** - &lt;p&gt;Product id&lt;/p&gt;



### getAccessories

    array ProductCore::getAccessories(integer $id_lang, $active)

Get product accessories



* Visibility: **public**


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;
* $active **mixed**



### getAccessoryById

    mixed ProductCore::getAccessoryById($accessory_id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $accessory_id **mixed**



### changeAccessories

    mixed ProductCore::changeAccessories(array $accessories_id)

Link accessories with product



* Visibility: **public**


#### Arguments
* $accessories_id **array** - &lt;p&gt;Accessories ids&lt;/p&gt;



### addFeaturesCustomToDB

    mixed ProductCore::addFeaturesCustomToDB($id_value, $lang, $cust)

Add new feature to product



* Visibility: **public**


#### Arguments
* $id_value **mixed**
* $lang **mixed**
* $cust **mixed**



### addFeaturesToDB

    mixed ProductCore::addFeaturesToDB($id_feature, $id_value, $cust)





* Visibility: **public**


#### Arguments
* $id_feature **mixed**
* $id_value **mixed**
* $cust **mixed**



### addFeatureProductImport

    mixed ProductCore::addFeatureProductImport($id_product, $id_feature, $id_feature_value)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**
* $id_feature **mixed**
* $id_feature_value **mixed**



### getFeatures

    array ProductCore::getFeatures()

Select all features for the object



* Visibility: **public**




### getFeaturesStatic

    mixed ProductCore::getFeaturesStatic($id_product)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**



### cacheProductsFeatures

    mixed ProductCore::cacheProductsFeatures($product_ids)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $product_ids **mixed**



### cacheFrontFeatures

    mixed ProductCore::cacheFrontFeatures($product_ids, $id_lang)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $product_ids **mixed**
* $id_lang **mixed**



### searchByName

    array ProductCore::searchByName(integer $id_lang, string $query, \Context $context)

Admin panel product search



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;
* $query **string** - &lt;p&gt;Search query&lt;/p&gt;
* $context **Context**



### duplicateAttributes

    mixed ProductCore::duplicateAttributes(integer $id_product_old, integer $id_product_new)

Duplicate attributes when duplicating a product



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product_old **integer** - &lt;p&gt;Old product id&lt;/p&gt;
* $id_product_new **integer** - &lt;p&gt;New product id&lt;/p&gt;



### getAttributesImpacts

    mixed ProductCore::getAttributesImpacts($id_product)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**



### _getAttributeImageAssociations

    array ProductCore::_getAttributeImageAssociations(integer $id_product_attribute)

Get product attribute image associations



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product_attribute **integer**



### duplicateAccessories

    mixed ProductCore::duplicateAccessories($id_product_old, $id_product_new)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product_old **mixed**
* $id_product_new **mixed**



### duplicateTags

    mixed ProductCore::duplicateTags($id_product_old, $id_product_new)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product_old **mixed**
* $id_product_new **mixed**



### duplicateDownload

    mixed ProductCore::duplicateDownload($id_product_old, $id_product_new)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product_old **mixed**
* $id_product_new **mixed**



### duplicateAttachments

    mixed ProductCore::duplicateAttachments($id_product_old, $id_product_new)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product_old **mixed**
* $id_product_new **mixed**



### duplicateFeatures

    mixed ProductCore::duplicateFeatures(integer $id_product_old, $id_product_new)

Duplicate features when duplicating a product



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product_old **integer** - &lt;p&gt;Old product id&lt;/p&gt;
* $id_product_new **mixed**



### _getCustomizationFieldsNLabels

    mixed ProductCore::_getCustomizationFieldsNLabels($product_id, $id_shop)





* Visibility: **protected**
* This method is **static**.


#### Arguments
* $product_id **mixed**
* $id_shop **mixed**



### duplicateSpecificPrices

    mixed ProductCore::duplicateSpecificPrices($old_product_id, $product_id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $old_product_id **mixed**
* $product_id **mixed**



### duplicateCustomizationFields

    mixed ProductCore::duplicateCustomizationFields($old_product_id, $product_id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $old_product_id **mixed**
* $product_id **mixed**



### duplicateSuppliers

    mixed ProductCore::duplicateSuppliers(integer $id_product_old, integer $id_product_new)

Adds suppliers from old product onto a newly duplicated product



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product_old **integer**
* $id_product_new **integer**



### getLink

    mixed ProductCore::getLink(\Context $context)

Get the link of the product page of this product



* Visibility: **public**


#### Arguments
* $context **Context**



### getTags

    mixed ProductCore::getTags($id_lang)





* Visibility: **public**


#### Arguments
* $id_lang **mixed**



### defineProductImage

    mixed ProductCore::defineProductImage($row, $id_lang)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $row **mixed**
* $id_lang **mixed**



### getProductProperties

    mixed ProductCore::getProductProperties($id_lang, $row, \Context $context)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **mixed**
* $row **mixed**
* $context **Context**



### getTaxesInformations

    mixed ProductCore::getTaxesInformations($row, \Context $context)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $row **mixed**
* $context **Context**



### getProductsProperties

    mixed ProductCore::getProductsProperties($id_lang, $query_result)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **mixed**
* $query_result **mixed**



### getFrontFeaturesStatic

    mixed ProductCore::getFrontFeaturesStatic($id_lang, $id_product)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **mixed**
* $id_product **mixed**



### getFrontFeatures

    mixed ProductCore::getFrontFeatures($id_lang)





* Visibility: **public**


#### Arguments
* $id_lang **mixed**



### getAttachmentsStatic

    mixed ProductCore::getAttachmentsStatic($id_lang, $id_product)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **mixed**
* $id_product **mixed**



### getAttachments

    mixed ProductCore::getAttachments($id_lang)





* Visibility: **public**


#### Arguments
* $id_lang **mixed**



### getAllCustomizedDatas

    mixed ProductCore::getAllCustomizedDatas($id_cart, $id_lang, $only_in_cart, $id_shop)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_cart **mixed**
* $id_lang **mixed**
* $only_in_cart **mixed**
* $id_shop **mixed**



### addCustomizationPrice

    mixed ProductCore::addCustomizationPrice($products, $customized_datas)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $products **mixed**
* $customized_datas **mixed**



### _checkLabelField

    mixed ProductCore::_checkLabelField($field, $value)





* Visibility: **protected**


#### Arguments
* $field **mixed**
* $value **mixed**



### _deleteOldLabels

    mixed ProductCore::_deleteOldLabels()





* Visibility: **protected**




### _createLabel

    mixed ProductCore::_createLabel($languages, $type)





* Visibility: **protected**


#### Arguments
* $languages **mixed**
* $type **mixed**



### createLabels

    mixed ProductCore::createLabels($uploadable_files, $text_fields)





* Visibility: **public**


#### Arguments
* $uploadable_files **mixed**
* $text_fields **mixed**



### updateLabels

    mixed ProductCore::updateLabels()





* Visibility: **public**




### getCustomizationFields

    mixed ProductCore::getCustomizationFields($id_lang, $id_shop)





* Visibility: **public**


#### Arguments
* $id_lang **mixed**
* $id_shop **mixed**



### getCustomizationFieldIds

    mixed ProductCore::getCustomizationFieldIds()





* Visibility: **public**




### getRequiredCustomizableFields

    mixed ProductCore::getRequiredCustomizableFields()





* Visibility: **public**




### getRequiredCustomizableFieldsStatic

    mixed ProductCore::getRequiredCustomizableFieldsStatic($id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id **mixed**



### hasAllRequiredCustomizableFields

    mixed ProductCore::hasAllRequiredCustomizableFields(\Context $context)





* Visibility: **public**


#### Arguments
* $context **Context**



### idIsOnCategoryId

    boolean ProductCore::idIsOnCategoryId(integer $id_product, array $categories)

Checks if the product is in at least one of the submited categories



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **integer**
* $categories **array** - &lt;p&gt;array of category arrays&lt;/p&gt;



### getNoPackPrice

    mixed ProductCore::getNoPackPrice()





* Visibility: **public**




### checkAccess

    mixed ProductCore::checkAccess($id_customer)





* Visibility: **public**


#### Arguments
* $id_customer **mixed**



### checkAccessStatic

    mixed ProductCore::checkAccessStatic($id_product, $id_customer)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**
* $id_customer **mixed**



### addStockMvt

    boolean ProductCore::addStockMvt(integer $quantity, integer $id_reason, integer $id_product_attribute, integer $id_order, integer $id_employee)

Add a stock movement for current product

Since 1.5, this method only permit to add/remove available quantities of the current product in the current shop

* Visibility: **public**


#### Arguments
* $quantity **integer**
* $id_reason **integer** - &lt;ul&gt;
&lt;li&gt;useless&lt;/li&gt;
&lt;/ul&gt;
* $id_product_attribute **integer**
* $id_order **integer** - &lt;ul&gt;
&lt;li&gt;DEPRECATED&lt;/li&gt;
&lt;/ul&gt;
* $id_employee **integer** - &lt;ul&gt;
&lt;li&gt;DEPRECATED&lt;/li&gt;
&lt;/ul&gt;



### getStockMvts

    mixed ProductCore::getStockMvts($id_lang)





* Visibility: **public**


#### Arguments
* $id_lang **mixed**



### getUrlRewriteInformations

    mixed ProductCore::getUrlRewriteInformations($id_product)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**



### getIdTaxRulesGroup

    mixed ProductCore::getIdTaxRulesGroup()





* Visibility: **public**




### getIdTaxRulesGroupByIdProduct

    mixed ProductCore::getIdTaxRulesGroupByIdProduct($id_product, \Context $context)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**
* $context **Context**



### getTaxesRate

    float ProductCore::getTaxesRate(\Address|null $address)

Returns tax rate.



* Visibility: **public**


#### Arguments
* $address **Address|null**



### getWsProductFeatures

    array ProductCore::getWsProductFeatures()

Webservice getter : get product features association



* Visibility: **public**




### setWsProductFeatures

    boolean ProductCore::setWsProductFeatures($product_features)

Webservice setter : set product features association



* Visibility: **public**


#### Arguments
* $product_features **mixed** - &lt;p&gt;Product Feature ids&lt;/p&gt;



### getWsDefaultCombination

    integer ProductCore::getWsDefaultCombination()

Webservice getter : get virtual field default combination



* Visibility: **public**




### setWsDefaultCombination

    boolean ProductCore::setWsDefaultCombination(integer $id_combination)

Webservice setter : set virtual field default combination



* Visibility: **public**


#### Arguments
* $id_combination **integer** - &lt;p&gt;id default combination&lt;/p&gt;



### getWsCategories

    array ProductCore::getWsCategories()

Webservice getter : get category ids of current product for association



* Visibility: **public**




### setWsCategories

    boolean ProductCore::setWsCategories(array $category_ids)

Webservice setter : set category ids of current product for association



* Visibility: **public**


#### Arguments
* $category_ids **array** - &lt;p&gt;category ids&lt;/p&gt;



### getWsAccessories

    array ProductCore::getWsAccessories()

Webservice getter : get product accessories ids of current product for association



* Visibility: **public**




### setWsAccessories

    mixed ProductCore::setWsAccessories($accessories)

Webservice setter : set product accessories ids of current product for association



* Visibility: **public**


#### Arguments
* $accessories **mixed** - &lt;p&gt;product ids&lt;/p&gt;



### getWsCombinations

    array ProductCore::getWsCombinations()

Webservice getter : get combination ids of current product for association



* Visibility: **public**




### setWsCombinations

    mixed ProductCore::setWsCombinations($combinations)

Webservice setter : set combination ids of current product for association



* Visibility: **public**


#### Arguments
* $combinations **mixed** - &lt;p&gt;combination ids&lt;/p&gt;



### getWsProductOptionValues

    array ProductCore::getWsProductOptionValues()

Webservice getter : get product option ids of current product for association



* Visibility: **public**




### getWsPositionInCategory

    integer ProductCore::getWsPositionInCategory()

Webservice getter : get virtual field position in category



* Visibility: **public**




### setWsPositionInCategory

    boolean ProductCore::setWsPositionInCategory($position)

Webservice setter : set virtual field position in category



* Visibility: **public**


#### Arguments
* $position **mixed**



### getCoverWs

    integer ProductCore::getCoverWs()

Webservice getter : get virtual field id_default_image in category



* Visibility: **public**




### setCoverWs

    boolean ProductCore::setCoverWs($id_image)

Webservice setter : set virtual field id_default_image in category



* Visibility: **public**


#### Arguments
* $id_image **mixed**



### getWsImages

    array ProductCore::getWsImages()

Webservice getter : get image ids of current product for association



* Visibility: **public**




### getWsStockAvailables

    mixed ProductCore::getWsStockAvailables()





* Visibility: **public**




### getWsTags

    mixed ProductCore::getWsTags()





* Visibility: **public**




### setWsTags

    mixed ProductCore::setWsTags($tag_ids)

Webservice setter : set tag ids of current product for association



* Visibility: **public**


#### Arguments
* $tag_ids **mixed** - &lt;p&gt;tag ids&lt;/p&gt;



### deleteWsTags

    array ProductCore::deleteWsTags()

Delete products tags entries without delete tags for webservice usage



* Visibility: **public**




### getWsManufacturerName

    mixed ProductCore::getWsManufacturerName()





* Visibility: **public**




### resetEcoTax

    mixed ProductCore::resetEcoTax()





* Visibility: **public**
* This method is **static**.




### setGroupReduction

    mixed ProductCore::setGroupReduction()

Set Group reduction if needed



* Visibility: **public**




### existsRefInDatabase

    boolean ProductCore::existsRefInDatabase($reference)

Checks if reference exists



* Visibility: **public**


#### Arguments
* $reference **mixed**



### getProductAttributesIds

    array ProductCore::getProductAttributesIds(integer $id_product, $shop_only)

Get all product attributes ids



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **integer** - &lt;p&gt;the id of the product&lt;/p&gt;
* $shop_only **mixed**



### getAttributesParams

    array ProductCore::getAttributesParams(integer $id_product, $id_product_attribute)

Get label by lang and value by lang too



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **integer**
* $id_product_attribute **mixed**



### getAttributesInformationsByProduct

    mixed ProductCore::getAttributesInformationsByProduct(integer $id_product)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **integer**



### getAnchor

    string ProductCore::getAnchor(integer $id_product_attribute, $with_id)

Get the combination url anchor of the product



* Visibility: **public**


#### Arguments
* $id_product_attribute **integer**
* $with_id **mixed**



### getProductName

    string ProductCore::getProductName(integer $id_product, integer $id_product_attribute, integer $id_lang)

Gets the name of a given product, in the given lang



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - &lt;p&gt;Optional&lt;/p&gt;
* $id_lang **integer** - &lt;p&gt;Optional&lt;/p&gt;



### addWs

    mixed ProductCore::addWs($autodate, $null_values)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### updateWs

    mixed ProductCore::updateWs($null_values)





* Visibility: **public**


#### Arguments
* $null_values **mixed**



### getRealQuantity

    integer ProductCore::getRealQuantity(integer $id_product, integer $id_product_attribute, integer $id_warehouse, integer $id_shop)

For a given product, returns its real quantity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $id_warehouse **integer**
* $id_shop **integer**



### usesAdvancedStockManagement

    boolean ProductCore::usesAdvancedStockManagement(integer $id_product)

For a given product, tells if it uses the advanced stock management



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **integer**



### flushPriceCache

    mixed ProductCore::flushPriceCache()

This method allows to flush price cache



* Visibility: **public**
* This method is **static**.




### getParentCategories

    array ProductCore::getParentCategories(integer $id_lang)

Get list of parent categories



* Visibility: **public**


#### Arguments
* $id_lang **integer**



### loadStockData

    mixed ProductCore::loadStockData()

Fill the variables used for stock management



* Visibility: **public**




### useAdvancedStockManagement

    mixed ProductCore::useAdvancedStockManagement()





* Visibility: **public**




### setAdvancedStockManagement

    mixed ProductCore::setAdvancedStockManagement($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### getDefaultCategory

    mixed ProductCore::getDefaultCategory()

get the default category according to the shop



* Visibility: **public**




### getShopsByProduct

    mixed ProductCore::getShopsByProduct($id_product)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**



### deleteDownload

    boolean ProductCore::deleteDownload()

Remove all downloadable files for product and its attributes



* Visibility: **public**




### getAttributeCombinaisons

    mixed ProductCore::getAttributeCombinaisons(integer $id_lang)





* Visibility: **public**


#### Arguments
* $id_lang **integer**



### deleteAttributeCombinaison

    mixed ProductCore::deleteAttributeCombinaison(integer $id_product_attribute)





* Visibility: **public**


#### Arguments
* $id_product_attribute **integer**



### getType

    integer ProductCore::getType()

Get the product type (simple, virtual, pack)



* Visibility: **public**




### hasAttributesInOtherShops

    mixed ProductCore::hasAttributesInOtherShops()





* Visibility: **public**




### getIdTaxRulesGroupMostUsed

    mixed ProductCore::getIdTaxRulesGroupMostUsed()





* Visibility: **public**
* This method is **static**.




### getIdByEan13

    integer ProductCore::getIdByEan13(string $ean13)

For a given ean13 reference, returns the corresponding id



* Visibility: **public**
* This method is **static**.


#### Arguments
* $ean13 **string**



### getWsType

    mixed ProductCore::getWsType()





* Visibility: **public**




### modifierWsLinkRewrite

    mixed ProductCore::modifierWsLinkRewrite()





* Visibility: **public**




### getWsProductBundle

    mixed ProductCore::getWsProductBundle()





* Visibility: **public**




### setWsType

    mixed ProductCore::setWsType($type_str)





* Visibility: **public**


#### Arguments
* $type_str **mixed**



### setWsProductBundle

    mixed ProductCore::setWsProductBundle($items)





* Visibility: **public**


#### Arguments
* $items **mixed**



### isColorUnavailable

    mixed ProductCore::isColorUnavailable($id_attribute, $id_shop)





* Visibility: **public**


#### Arguments
* $id_attribute **mixed**
* $id_shop **mixed**



### getColorsListCacheId

    mixed ProductCore::getColorsListCacheId($id_product)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**



### setPackStockType

    mixed ProductCore::setPackStockType($id_product, $pack_stock_type)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**
* $pack_stock_type **mixed**


