CartCore
===============






* Class name: CartCore
* Namespace: 
* Parent class: ObjectModel



Constants
----------


### ONLY_PRODUCTS

    const ONLY_PRODUCTS = 1





### ONLY_DISCOUNTS

    const ONLY_DISCOUNTS = 2





### BOTH

    const BOTH = 3





### BOTH_WITHOUT_SHIPPING

    const BOTH_WITHOUT_SHIPPING = 4





### ONLY_SHIPPING

    const ONLY_SHIPPING = 5





### ONLY_WRAPPING

    const ONLY_WRAPPING = 6





### ONLY_PRODUCTS_WITHOUT_SHIPPING

    const ONLY_PRODUCTS_WITHOUT_SHIPPING = 7





### ONLY_PHYSICAL_PRODUCTS_WITHOUT_SHIPPING

    const ONLY_PHYSICAL_PRODUCTS_WITHOUT_SHIPPING = 8





Properties
----------


### $id

    public mixed $id





* Visibility: **public**


### $id_shop_group

    public mixed $id_shop_group





* Visibility: **public**


### $id_shop

    public mixed $id_shop





* Visibility: **public**


### $id_address_delivery

    public integer $id_address_delivery





* Visibility: **public**


### $id_address_invoice

    public integer $id_address_invoice





* Visibility: **public**


### $id_currency

    public integer $id_currency





* Visibility: **public**


### $id_customer

    public integer $id_customer





* Visibility: **public**


### $id_guest

    public integer $id_guest





* Visibility: **public**


### $id_lang

    public integer $id_lang





* Visibility: **public**


### $recyclable

    public boolean $recyclable





* Visibility: **public**


### $gift

    public boolean $gift





* Visibility: **public**


### $gift_message

    public string $gift_message





* Visibility: **public**


### $mobile_theme

    public boolean $mobile_theme





* Visibility: **public**


### $date_add

    public string $date_add





* Visibility: **public**


### $secure_key

    public string $secure_key





* Visibility: **public**


### $id_carrier

    public integer $id_carrier





* Visibility: **public**


### $date_upd

    public string $date_upd





* Visibility: **public**


### $checkedTos

    public mixed $checkedTos = false





* Visibility: **public**


### $pictures

    public mixed $pictures





* Visibility: **public**


### $textFields

    public mixed $textFields





* Visibility: **public**


### $delivery_option

    public mixed $delivery_option





* Visibility: **public**


### $allow_seperated_package

    public boolean $allow_seperated_package = false





* Visibility: **public**


### $_nbProducts

    protected mixed $_nbProducts = array()





* Visibility: **protected**
* This property is **static**.


### $_isVirtualCart

    protected mixed $_isVirtualCart = array()





* Visibility: **protected**
* This property is **static**.


### $_products

    protected mixed $_products = null





* Visibility: **protected**


### $_totalWeight

    protected mixed $_totalWeight = array()





* Visibility: **protected**
* This property is **static**.


### $_taxCalculationMethod

    protected mixed $_taxCalculationMethod = PS_TAX_EXC





* Visibility: **protected**


### $_carriers

    protected mixed $_carriers = null





* Visibility: **protected**
* This property is **static**.


### $_taxes_rate

    protected mixed $_taxes_rate = null





* Visibility: **protected**
* This property is **static**.


### $_attributesLists

    protected mixed $_attributesLists = array()





* Visibility: **protected**
* This property is **static**.


### $_customer

    protected \Customer $_customer = null





* Visibility: **protected**
* This property is **static**.


### $definition

    public mixed $definition = array('table' => 'cart', 'primary' => 'id_cart', 'fields' => array('id_shop_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_shop' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_address_delivery' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_address_invoice' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_carrier' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_guest' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_lang' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'recyclable' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'gift' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'gift_message' => array('type' => self::TYPE_STRING, 'validate' => 'isMessage'), 'mobile_theme' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'delivery_option' => array('type' => self::TYPE_STRING), 'secure_key' => array('type' => self::TYPE_STRING, 'size' => 32), 'allow_seperated_package' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_address_delivery' => array('xlink_resource' => 'addresses'), 'id_address_invoice' => array('xlink_resource' => 'addresses'), 'id_currency' => array('xlink_resource' => 'currencies'), 'id_customer' => array('xlink_resource' => 'customers'), 'id_guest' => array('xlink_resource' => 'guests'), 'id_lang' => array('xlink_resource' => 'languages')), 'associations' => array('cart_rows' => array('resource' => 'cart_row', 'virtual_entity' => true, 'fields' => array('id_product' => array('required' => true, 'xlink_resource' => 'products'), 'id_product_attribute' => array('required' => true, 'xlink_resource' => 'combinations'), 'id_address_delivery' => array('required' => true, 'xlink_resource' => 'addresses'), 'quantity' => array('required' => true)))))





* Visibility: **protected**


Methods
-------


### __construct

    mixed CartCore::__construct($id, $id_lang)





* Visibility: **public**


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### setTaxCalculationMethod

    mixed CartCore::setTaxCalculationMethod()





* Visibility: **public**




### add

    mixed CartCore::add($autodate, $null_values)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### update

    mixed CartCore::update($null_values)





* Visibility: **public**


#### Arguments
* $null_values **mixed**



### updateAddressId

    mixed CartCore::updateAddressId(integer $id_address, integer $id_address_new)

Update the address id of the cart



* Visibility: **public**


#### Arguments
* $id_address **integer** - &lt;p&gt;Current address id to change&lt;/p&gt;
* $id_address_new **integer** - &lt;p&gt;New address id&lt;/p&gt;



### delete

    mixed CartCore::delete()





* Visibility: **public**




### getTaxesAverageUsed

    mixed CartCore::getTaxesAverageUsed($id_cart)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_cart **mixed**



### getAverageProductsTaxRate

    mixed CartCore::getAverageProductsTaxRate($cart_amount_te, $cart_amount_ti)

The arguments are optional and only serve as return values in case caller needs the details.



* Visibility: **public**


#### Arguments
* $cart_amount_te **mixed**
* $cart_amount_ti **mixed**



### getDiscounts

    mixed CartCore::getDiscounts($lite, $refresh)





* Visibility: **public**


#### Arguments
* $lite **mixed**
* $refresh **mixed**



### getCartRules

    mixed CartCore::getCartRules($filter)





* Visibility: **public**


#### Arguments
* $filter **mixed**



### getOrderedCartRulesIds

    array CartCore::getOrderedCartRulesIds($filter)

Return the cart rules Ids on the cart.



* Visibility: **public**


#### Arguments
* $filter **mixed**



### getDiscountsCustomer

    mixed CartCore::getDiscountsCustomer($id_cart_rule)





* Visibility: **public**


#### Arguments
* $id_cart_rule **mixed**



### getLastProduct

    mixed CartCore::getLastProduct()





* Visibility: **public**




### getProducts

    mixed CartCore::getProducts($refresh, $id_product, $id_country)

Return cart products



* Visibility: **public**


#### Arguments
* $refresh **mixed**
* $id_product **mixed**
* $id_country **mixed**



### cacheSomeAttributesLists

    mixed CartCore::cacheSomeAttributesLists($ipa_list, $id_lang)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $ipa_list **mixed**
* $id_lang **mixed**



### nbProducts

    mixed CartCore::nbProducts()

Return cart products quantity



* Visibility: **public**




### getNbProducts

    mixed CartCore::getNbProducts($id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id **mixed**



### addDiscount

    mixed CartCore::addDiscount($id_cart_rule)





* Visibility: **public**


#### Arguments
* $id_cart_rule **mixed**



### addCartRule

    mixed CartCore::addCartRule($id_cart_rule)





* Visibility: **public**


#### Arguments
* $id_cart_rule **mixed**



### containsProduct

    mixed CartCore::containsProduct($id_product, $id_product_attribute, $id_customization, $id_address_delivery)





* Visibility: **public**


#### Arguments
* $id_product **mixed**
* $id_product_attribute **mixed**
* $id_customization **mixed**
* $id_address_delivery **mixed**



### updateQty

    mixed CartCore::updateQty(integer $quantity, integer $id_product, integer $id_product_attribute, $id_customization, string $operator, $id_address_delivery, \Shop $shop, $auto_add_cart_rule)

Update product quantity



* Visibility: **public**


#### Arguments
* $quantity **integer** - &lt;p&gt;Quantity to add (or substract)&lt;/p&gt;
* $id_product **integer** - &lt;p&gt;Product ID&lt;/p&gt;
* $id_product_attribute **integer** - &lt;p&gt;Attribute ID if needed&lt;/p&gt;
* $id_customization **mixed**
* $operator **string** - &lt;p&gt;Indicate if quantity must be increased or decreased&lt;/p&gt;
* $id_address_delivery **mixed**
* $shop **Shop**
* $auto_add_cart_rule **mixed**



### _updateCustomizationQuantity

    mixed CartCore::_updateCustomizationQuantity($quantity, $id_customization, $id_product, $id_product_attribute, $id_address_delivery, $operator)





* Visibility: **protected**


#### Arguments
* $quantity **mixed**
* $id_customization **mixed**
* $id_product **mixed**
* $id_product_attribute **mixed**
* $id_address_delivery **mixed**
* $operator **mixed**



### _addCustomization

    boolean CartCore::_addCustomization(integer $id_product, integer $id_product_attribute, integer $index, integer $type, string $field, integer $quantity)

Add customization item to database



* Visibility: **public**


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $index **integer**
* $type **integer**
* $field **string**
* $quantity **integer**



### orderExists

    boolean CartCore::orderExists()

Check if order has already been placed



* Visibility: **public**




### deleteDiscount

    mixed CartCore::deleteDiscount($id_cart_rule)





* Visibility: **public**


#### Arguments
* $id_cart_rule **mixed**



### removeCartRule

    mixed CartCore::removeCartRule($id_cart_rule)





* Visibility: **public**


#### Arguments
* $id_cart_rule **mixed**



### deleteProduct

    boolean CartCore::deleteProduct(integer $id_product, integer $id_product_attribute, integer $id_customization, $id_address_delivery)

Delete a product from the cart



* Visibility: **public**


#### Arguments
* $id_product **integer** - &lt;p&gt;Product ID&lt;/p&gt;
* $id_product_attribute **integer** - &lt;p&gt;Attribute ID if needed&lt;/p&gt;
* $id_customization **integer** - &lt;p&gt;Customization id&lt;/p&gt;
* $id_address_delivery **mixed**



### _deleteCustomization

    boolean CartCore::_deleteCustomization(integer $id_customization, $id_product, $id_product_attribute, $id_address_delivery)

Delete a customization from the cart. If customization is a Picture,
then the image is also deleted



* Visibility: **protected**


#### Arguments
* $id_customization **integer**
* $id_product **mixed**
* $id_product_attribute **mixed**
* $id_address_delivery **mixed**



### getTotalCart

    mixed CartCore::getTotalCart($id_cart, $use_tax_display, $type)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_cart **mixed**
* $use_tax_display **mixed**
* $type **mixed**



### getOrderTotalUsingTaxCalculationMethod

    mixed CartCore::getOrderTotalUsingTaxCalculationMethod($id_cart)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_cart **mixed**



### getOrderTotal

    float CartCore::getOrderTotal($with_taxes, integer $type, $products, $id_carrier, boolean $use_cache)

This function returns the total cart amount

Possible values for $type:
Cart::ONLY_PRODUCTS
Cart::ONLY_DISCOUNTS
Cart::BOTH
Cart::BOTH_WITHOUT_SHIPPING
Cart::ONLY_SHIPPING
Cart::ONLY_WRAPPING
Cart::ONLY_PRODUCTS_WITHOUT_SHIPPING
Cart::ONLY_PHYSICAL_PRODUCTS_WITHOUT_SHIPPING

* Visibility: **public**


#### Arguments
* $with_taxes **mixed**
* $type **integer** - &lt;p&gt;Total type&lt;/p&gt;
* $products **mixed**
* $id_carrier **mixed**
* $use_cache **boolean** - &lt;p&gt;Allow using cache of the method CartRule::getContextualValue&lt;/p&gt;



### getGiftWrappingPrice

    float CartCore::getGiftWrappingPrice(boolean $with_taxes, $id_address)

Get the gift wrapping price



* Visibility: **public**


#### Arguments
* $with_taxes **boolean** - &lt;p&gt;With or without taxes&lt;/p&gt;
* $id_address **mixed**



### getNbOfPackages

    integer CartCore::getNbOfPackages()

Get the number of packages



* Visibility: **public**




### getPackageList

    array CartCore::getPackageList($flush)

Get products grouped by package and by addresses to be sent individualy (one package = one shipping cost).



* Visibility: **public**


#### Arguments
* $flush **mixed**



### getPackageIdWarehouse

    mixed CartCore::getPackageIdWarehouse($package, $id_carrier)





* Visibility: **public**


#### Arguments
* $package **mixed**
* $id_carrier **mixed**



### getDeliveryOptionList

    array CartCore::getDeliveryOptionList(\Country $default_country, boolean $flush)

Get all deliveries options available for the current cart



* Visibility: **public**


#### Arguments
* $default_country **Country**
* $flush **boolean** - &lt;p&gt;Force flushing cache&lt;/p&gt;



### sortDeliveryOptionList

    integer CartCore::sortDeliveryOptionList($option1, $option2)

Sort list of option delivery by parameters define in the BO



* Visibility: **public**
* This method is **static**.


#### Arguments
* $option1 **mixed**
* $option2 **mixed**



### carrierIsSelected

    mixed CartCore::carrierIsSelected($id_carrier, $id_address)





* Visibility: **public**


#### Arguments
* $id_carrier **mixed**
* $id_address **mixed**



### simulateCarriersOutput

    mixed CartCore::simulateCarriersOutput(\Country $default_country, boolean $flush)

Get all deliveries options available for the current cart formated like Carriers::getCarriersForOrder
This method was wrote for retrocompatibility with 1.4 theme
New theme need to use Cart::getDeliveryOptionList() to generate carriers option in the checkout process



* Visibility: **public**


#### Arguments
* $default_country **Country**
* $flush **boolean** - &lt;p&gt;Force flushing cache&lt;/p&gt;



### simulateCarrierSelectedOutput

    mixed CartCore::simulateCarrierSelectedOutput($use_cache)





* Visibility: **public**


#### Arguments
* $use_cache **mixed**



### intifier

    integer CartCore::intifier($string, $delimiter)

Translate a string option_delivery identifier ('24,3,') in a int (3240002000)

The  option_delivery identifier is a list of integers separated by a ','.
This method replace the delimiter by a sequence of '0'.
The size of this sequence is fixed by the first digit of the return

* Visibility: **public**
* This method is **static**.


#### Arguments
* $string **mixed**
* $delimiter **mixed**



### desintifier

    mixed CartCore::desintifier($int, $delimiter)

Translate a int option_delivery identifier (3240002000) in a string ('24,3,')



* Visibility: **public**
* This method is **static**.


#### Arguments
* $int **mixed**
* $delimiter **mixed**



### isMultiAddressDelivery

    boolean CartCore::isMultiAddressDelivery()

Does the cart use multiple address



* Visibility: **public**




### getAddressCollection

    mixed CartCore::getAddressCollection()

Get all delivery addresses object for the current cart



* Visibility: **public**




### setDeliveryOption

    mixed CartCore::setDeliveryOption($delivery_option)

Set the delivery option and id_carrier, if there is only one carrier



* Visibility: **public**


#### Arguments
* $delivery_option **mixed**



### getIdCarrierFromDeliveryOption

    mixed CartCore::getIdCarrierFromDeliveryOption($delivery_option)





* Visibility: **protected**


#### Arguments
* $delivery_option **mixed**



### getDeliveryOption

    array|boolean|mixed CartCore::getDeliveryOption(\Country|null $default_country, boolean $dontAutoSelectOptions, boolean $use_cache)

Get the delivery option selected, or if no delivery option was selected,
the cheapest option for each address



* Visibility: **public**


#### Arguments
* $default_country **Country|null**
* $dontAutoSelectOptions **boolean**
* $use_cache **boolean**



### getTotalShippingCost

    float CartCore::getTotalShippingCost(array|null $delivery_option, boolean $use_tax, \Country|null $default_country)

Return shipping total for the cart



* Visibility: **public**


#### Arguments
* $delivery_option **array|null** - &lt;p&gt;Array of the delivery option for each address&lt;/p&gt;
* $use_tax **boolean**
* $default_country **Country|null**



### getCarrierCost

    float CartCore::getCarrierCost(integer $id_carrier, boolean $useTax, \Country|null $default_country, array $delivery_option)

Return shipping total of a specific carriers for the cart



* Visibility: **public**


#### Arguments
* $id_carrier **integer**
* $useTax **boolean**
* $default_country **Country|null**
* $delivery_option **array** - &lt;p&gt;Array of the delivery option for each address&lt;/p&gt;



### getOrderShippingCost

    mixed CartCore::getOrderShippingCost($id_carrier, $use_tax, \Country $default_country, $product_list)





* Visibility: **public**


#### Arguments
* $id_carrier **mixed**
* $use_tax **mixed**
* $default_country **Country**
* $product_list **mixed**



### getPackageShippingCost

    float CartCore::getPackageShippingCost(integer $id_carrier, boolean $use_tax, \Country|null $default_country, array|null $product_list, integer|null $id_zone)

Return package shipping cost



* Visibility: **public**


#### Arguments
* $id_carrier **integer** - &lt;p&gt;Carrier ID (default : current carrier)&lt;/p&gt;
* $use_tax **boolean**
* $default_country **Country|null**
* $product_list **array|null** - &lt;p&gt;List of product concerned by the shipping.
                                     If null, all the product of the cart are used to calculate the shipping cost&lt;/p&gt;
* $id_zone **integer|null**



### getTotalWeight

    float CartCore::getTotalWeight($products)

Return cart weight



* Visibility: **public**


#### Arguments
* $products **mixed**



### checkDiscountValidity

    boolean|string CartCore::checkDiscountValidity(\CartRule $obj, $discounts, $order_total, $products, $check_cart_discount)





* Visibility: **public**


#### Arguments
* $obj **CartRule**
* $discounts **mixed**
* $order_total **mixed**
* $products **mixed**
* $check_cart_discount **mixed**



### getSummaryDetails

    array CartCore::getSummaryDetails($id_lang, $refresh)

Return useful informations for cart



* Visibility: **public**


#### Arguments
* $id_lang **mixed**
* $refresh **mixed**



### checkQuantities

    mixed CartCore::checkQuantities($return_product)





* Visibility: **public**


#### Arguments
* $return_product **mixed**



### checkProductsAccess

    mixed CartCore::checkProductsAccess()





* Visibility: **public**




### lastNoneOrderedCart

    mixed CartCore::lastNoneOrderedCart($id_customer)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_customer **mixed**



### isVirtualCart

    boolean CartCore::isVirtualCart($strict)

Check if cart contains only virtual products



* Visibility: **public**


#### Arguments
* $strict **mixed**



### getCartByOrderId

    \Cart|boolean CartCore::getCartByOrderId(integer $id_order)

Build cart object from provided id_order



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_order **integer**



### getCartIdByOrderId

    mixed CartCore::getCartIdByOrderId($id_order)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_order **mixed**



### addTextFieldToProduct

    boolean CartCore::addTextFieldToProduct($id_product, $index, $type, $text_value)

Add customer's text



* Visibility: **public**


#### Arguments
* $id_product **mixed**
* $index **mixed**
* $type **mixed**
* $text_value **mixed**



### addPictureToProduct

    boolean CartCore::addPictureToProduct($id_product, $index, $type, $file)

Add customer's pictures



* Visibility: **public**


#### Arguments
* $id_product **mixed**
* $index **mixed**
* $type **mixed**
* $file **mixed**



### deletePictureToProduct

    boolean CartCore::deletePictureToProduct(integer $id_product, $index)





* Visibility: **public**


#### Arguments
* $id_product **integer**
* $index **mixed**



### deleteCustomizationToProduct

    boolean CartCore::deleteCustomizationToProduct(integer $id_product, integer $index)

Remove a customer's customization



* Visibility: **public**


#### Arguments
* $id_product **integer**
* $index **integer**



### getProductCustomization

    array CartCore::getProductCustomization(integer $id_product, integer $type, boolean $not_in_cart)

Return custom pictures in this cart for a specified product



* Visibility: **public**


#### Arguments
* $id_product **integer**
* $type **integer** - &lt;p&gt;only return customization of this type&lt;/p&gt;
* $not_in_cart **boolean** - &lt;p&gt;only return customizations that are not in cart already&lt;/p&gt;



### getCustomerCarts

    mixed CartCore::getCustomerCarts($id_customer, $with_order)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_customer **mixed**
* $with_order **mixed**



### replaceZeroByShopName

    mixed CartCore::replaceZeroByShopName($echo, $tr)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $echo **mixed**
* $tr **mixed**



### duplicate

    mixed CartCore::duplicate()





* Visibility: **public**




### getWsCartRows

    mixed CartCore::getWsCartRows()





* Visibility: **public**




### setWsCartRows

    mixed CartCore::setWsCartRows($values)





* Visibility: **public**


#### Arguments
* $values **mixed**



### setProductAddressDelivery

    mixed CartCore::setProductAddressDelivery($id_product, $id_product_attribute, $old_id_address_delivery, $new_id_address_delivery)





* Visibility: **public**


#### Arguments
* $id_product **mixed**
* $id_product_attribute **mixed**
* $old_id_address_delivery **mixed**
* $new_id_address_delivery **mixed**



### duplicateProduct

    mixed CartCore::duplicateProduct($id_product, $id_product_attribute, $id_address_delivery, $new_id_address_delivery, $quantity, $keep_quantity)





* Visibility: **public**


#### Arguments
* $id_product **mixed**
* $id_product_attribute **mixed**
* $id_address_delivery **mixed**
* $new_id_address_delivery **mixed**
* $quantity **mixed**
* $keep_quantity **mixed**



### setNoMultishipping

    mixed CartCore::setNoMultishipping()

Update products cart address delivery with the address delivery of the cart



* Visibility: **public**




### autosetProductAddress

    mixed CartCore::autosetProductAddress()

Set an address to all products on the cart without address delivery



* Visibility: **public**




### deleteAssociations

    mixed CartCore::deleteAssociations()





* Visibility: **public**




### isGuestCartByCartId

    boolean CartCore::isGuestCartByCartId(integer $id_cart)

isGuestCartByCartId



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_cart **integer**



### isCarrierInRange

    mixed CartCore::isCarrierInRange($id_carrier, $id_zone)

isCarrierInRange

Check if the specified carrier is in range

* Visibility: **public**


#### Arguments
* $id_carrier **mixed**
* $id_zone **mixed**



### isAllProductsInStock

    boolean CartCore::isAllProductsInStock(boolean $ignore_virtual, boolean $exclusive)





* Visibility: **public**


#### Arguments
* $ignore_virtual **boolean** - &lt;p&gt;Ignore virtual product&lt;/p&gt;
* $exclusive **boolean** - &lt;p&gt;If true, the validation is exclusive : it must be present product in stock and out of stock&lt;/p&gt;



### addExtraCarriers

    mixed CartCore::addExtraCarriers(array $array)

Execute hook displayCarrierList (extraCarrier) and merge theme to the $array



* Visibility: **public**
* This method is **static**.


#### Arguments
* $array **array**



### getDeliveryAddressesWithoutCarriers

    array CartCore::getDeliveryAddressesWithoutCarriers(boolean $return_collection, $error)

Get all the ids of the delivery addresses without carriers



* Visibility: **public**


#### Arguments
* $return_collection **boolean** - &lt;p&gt;Return a collection&lt;/p&gt;
* $error **mixed**


