CartCore
===============






* Class name: CartCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/Cart.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L27)



Constants
----------

* [ONLY_PRODUCTS](#constant-ONLY_PRODUCTS)
* [ONLY_DISCOUNTS](#constant-ONLY_DISCOUNTS)
* [BOTH](#constant-BOTH)
* [BOTH_WITHOUT_SHIPPING](#constant-BOTH_WITHOUT_SHIPPING)
* [ONLY_SHIPPING](#constant-ONLY_SHIPPING)
* [ONLY_WRAPPING](#constant-ONLY_WRAPPING)
* [ONLY_PRODUCTS_WITHOUT_SHIPPING](#constant-ONLY_PRODUCTS_WITHOUT_SHIPPING)
* [ONLY_PHYSICAL_PRODUCTS_WITHOUT_SHIPPING](#constant-ONLY_PHYSICAL_PRODUCTS_WITHOUT_SHIPPING)

Properties
----------

* [$id](#property-$id)
* [$id_shop_group](#property-$id_shop_group)
* [$id_shop](#property-$id_shop)
* [$id_address_delivery](#property-$id_address_delivery)
* [$id_address_invoice](#property-$id_address_invoice)
* [$id_currency](#property-$id_currency)
* [$id_customer](#property-$id_customer)
* [$id_guest](#property-$id_guest)
* [$id_lang](#property-$id_lang)
* [$recyclable](#property-$recyclable)
* [$gift](#property-$gift)
* [$gift_message](#property-$gift_message)
* [$mobile_theme](#property-$mobile_theme)
* [$date_add](#property-$date_add)
* [$secure_key](#property-$secure_key)
* [$id_carrier](#property-$id_carrier)
* [$date_upd](#property-$date_upd)
* [$checkedTos](#property-$checkedTos)
* [$pictures](#property-$pictures)
* [$textFields](#property-$textFields)
* [$delivery_option](#property-$delivery_option)
* [$allow_seperated_package](#property-$allow_seperated_package)
* [$_nbProducts](#property-$_nbProducts)
* [$_isVirtualCart](#property-$_isVirtualCart)
* [$_products](#property-$_products)
* [$_totalWeight](#property-$_totalWeight)
* [$_taxCalculationMethod](#property-$_taxCalculationMethod)
* [$_carriers](#property-$_carriers)
* [$_taxes_rate](#property-$_taxes_rate)
* [$_attributesLists](#property-$_attributesLists)
* [$_customer](#property-$_customer)
* [$definition](#property-$definition)
* [$webserviceParameters](#property-$webserviceParameters)

Methods
-------
* [__construct](#method-__construct)
* [setTaxCalculationMethod](#method-setTaxCalculationMethod)
* [add](#method-add)
* [update](#method-update)
* [updateAddressId](#method-updateAddressId)
* [delete](#method-delete)
* [getTaxesAverageUsed](#method-getTaxesAverageUsed)
* [getAverageProductsTaxRate](#method-getAverageProductsTaxRate)
* [getDiscounts](#method-getDiscounts)
* [getCartRules](#method-getCartRules)
* [getOrderedCartRulesIds](#method-getOrderedCartRulesIds)
* [getDiscountsCustomer](#method-getDiscountsCustomer)
* [getLastProduct](#method-getLastProduct)
* [getProducts](#method-getProducts)
* [cacheSomeAttributesLists](#method-cacheSomeAttributesLists)
* [nbProducts](#method-nbProducts)
* [getNbProducts](#method-getNbProducts)
* [addDiscount](#method-addDiscount)
* [addCartRule](#method-addCartRule)
* [containsProduct](#method-containsProduct)
* [updateQty](#method-updateQty)
* [_updateCustomizationQuantity](#method-_updateCustomizationQuantity)
* [_addCustomization](#method-_addCustomization)
* [orderExists](#method-orderExists)
* [deleteDiscount](#method-deleteDiscount)
* [removeCartRule](#method-removeCartRule)
* [deleteProduct](#method-deleteProduct)
* [_deleteCustomization](#method-_deleteCustomization)
* [getTotalCart](#method-getTotalCart)
* [getOrderTotalUsingTaxCalculationMethod](#method-getOrderTotalUsingTaxCalculationMethod)
* [getOrderTotal](#method-getOrderTotal)
* [getGiftWrappingPrice](#method-getGiftWrappingPrice)
* [getNbOfPackages](#method-getNbOfPackages)
* [getPackageList](#method-getPackageList)
* [getPackageIdWarehouse](#method-getPackageIdWarehouse)
* [getDeliveryOptionList](#method-getDeliveryOptionList)
* [sortDeliveryOptionList](#method-sortDeliveryOptionList)
* [carrierIsSelected](#method-carrierIsSelected)
* [simulateCarriersOutput](#method-simulateCarriersOutput)
* [simulateCarrierSelectedOutput](#method-simulateCarrierSelectedOutput)
* [intifier](#method-intifier)
* [desintifier](#method-desintifier)
* [isMultiAddressDelivery](#method-isMultiAddressDelivery)
* [getAddressCollection](#method-getAddressCollection)
* [setDeliveryOption](#method-setDeliveryOption)
* [getIdCarrierFromDeliveryOption](#method-getIdCarrierFromDeliveryOption)
* [getDeliveryOption](#method-getDeliveryOption)
* [getTotalShippingCost](#method-getTotalShippingCost)
* [getCarrierCost](#method-getCarrierCost)
* [getOrderShippingCost](#method-getOrderShippingCost)
* [getPackageShippingCost](#method-getPackageShippingCost)
* [getTotalWeight](#method-getTotalWeight)
* [checkDiscountValidity](#method-checkDiscountValidity)
* [getSummaryDetails](#method-getSummaryDetails)
* [checkQuantities](#method-checkQuantities)
* [checkProductsAccess](#method-checkProductsAccess)
* [lastNoneOrderedCart](#method-lastNoneOrderedCart)
* [isVirtualCart](#method-isVirtualCart)
* [getCartByOrderId](#method-getCartByOrderId)
* [getCartIdByOrderId](#method-getCartIdByOrderId)
* [addTextFieldToProduct](#method-addTextFieldToProduct)
* [addPictureToProduct](#method-addPictureToProduct)
* [deletePictureToProduct](#method-deletePictureToProduct)
* [deleteCustomizationToProduct](#method-deleteCustomizationToProduct)
* [getProductCustomization](#method-getProductCustomization)
* [getCustomerCarts](#method-getCustomerCarts)
* [replaceZeroByShopName](#method-replaceZeroByShopName)
* [duplicate](#method-duplicate)
* [getWsCartRows](#method-getWsCartRows)
* [setWsCartRows](#method-setWsCartRows)
* [setProductAddressDelivery](#method-setProductAddressDelivery)
* [duplicateProduct](#method-duplicateProduct)
* [setNoMultishipping](#method-setNoMultishipping)
* [autosetProductAddress](#method-autosetProductAddress)
* [deleteAssociations](#method-deleteAssociations)
* [isGuestCartByCartId](#method-isGuestCartByCartId)
* [isCarrierInRange](#method-isCarrierInRange)
* [isAllProductsInStock](#method-isAllProductsInStock)
* [addExtraCarriers](#method-addExtraCarriers)
* [getDeliveryAddressesWithoutCarriers](#method-getDeliveryAddressesWithoutCarriers)


Constants
----------


### <a name="constant-ONLY_PRODUCTS"></a>ONLY_PRODUCTS

    const ONLY_PRODUCTS = 1



* This constant is defined in [classes/Cart.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L147)


### <a name="constant-ONLY_DISCOUNTS"></a>ONLY_DISCOUNTS

    const ONLY_DISCOUNTS = 2



* This constant is defined in [classes/Cart.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L148)


### <a name="constant-BOTH"></a>BOTH

    const BOTH = 3



* This constant is defined in [classes/Cart.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L149)


### <a name="constant-BOTH_WITHOUT_SHIPPING"></a>BOTH_WITHOUT_SHIPPING

    const BOTH_WITHOUT_SHIPPING = 4



* This constant is defined in [classes/Cart.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L150)


### <a name="constant-ONLY_SHIPPING"></a>ONLY_SHIPPING

    const ONLY_SHIPPING = 5



* This constant is defined in [classes/Cart.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L151)


### <a name="constant-ONLY_WRAPPING"></a>ONLY_WRAPPING

    const ONLY_WRAPPING = 6



* This constant is defined in [classes/Cart.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L152)


### <a name="constant-ONLY_PRODUCTS_WITHOUT_SHIPPING"></a>ONLY_PRODUCTS_WITHOUT_SHIPPING

    const ONLY_PRODUCTS_WITHOUT_SHIPPING = 7



* This constant is defined in [classes/Cart.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L153)


### <a name="constant-ONLY_PHYSICAL_PRODUCTS_WITHOUT_SHIPPING"></a>ONLY_PHYSICAL_PRODUCTS_WITHOUT_SHIPPING

    const ONLY_PHYSICAL_PRODUCTS_WITHOUT_SHIPPING = 8



* This constant is defined in [classes/Cart.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L154)


Properties
----------


### <a name="property-$id"></a>$id

    public mixed $id





* Visibility: **public**
* This property is defined in [classes/Cart.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L29)


### <a name="property-$id_shop_group"></a>$id_shop_group

    public mixed $id_shop_group





* Visibility: **public**
* This property is defined in [classes/Cart.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L31)


### <a name="property-$id_shop"></a>$id_shop

    public mixed $id_shop





* Visibility: **public**
* This property is defined in [classes/Cart.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L33)


### <a name="property-$id_address_delivery"></a>$id_address_delivery

    public integer $id_address_delivery





* Visibility: **public**
* This property is defined in [classes/Cart.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L36)


### <a name="property-$id_address_invoice"></a>$id_address_invoice

    public integer $id_address_invoice





* Visibility: **public**
* This property is defined in [classes/Cart.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L39)


### <a name="property-$id_currency"></a>$id_currency

    public integer $id_currency





* Visibility: **public**
* This property is defined in [classes/Cart.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L42)


### <a name="property-$id_customer"></a>$id_customer

    public integer $id_customer





* Visibility: **public**
* This property is defined in [classes/Cart.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L45)


### <a name="property-$id_guest"></a>$id_guest

    public integer $id_guest





* Visibility: **public**
* This property is defined in [classes/Cart.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L48)


### <a name="property-$id_lang"></a>$id_lang

    public integer $id_lang





* Visibility: **public**
* This property is defined in [classes/Cart.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L51)


### <a name="property-$recyclable"></a>$recyclable

    public boolean $recyclable





* Visibility: **public**
* This property is defined in [classes/Cart.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L54)


### <a name="property-$gift"></a>$gift

    public boolean $gift





* Visibility: **public**
* This property is defined in [classes/Cart.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L57)


### <a name="property-$gift_message"></a>$gift_message

    public string $gift_message





* Visibility: **public**
* This property is defined in [classes/Cart.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L60)


### <a name="property-$mobile_theme"></a>$mobile_theme

    public boolean $mobile_theme





* Visibility: **public**
* This property is defined in [classes/Cart.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L63)


### <a name="property-$date_add"></a>$date_add

    public string $date_add





* Visibility: **public**
* This property is defined in [classes/Cart.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L66)


### <a name="property-$secure_key"></a>$secure_key

    public string $secure_key





* Visibility: **public**
* This property is defined in [classes/Cart.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L69)


### <a name="property-$id_carrier"></a>$id_carrier

    public integer $id_carrier





* Visibility: **public**
* This property is defined in [classes/Cart.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L72)


### <a name="property-$date_upd"></a>$date_upd

    public string $date_upd





* Visibility: **public**
* This property is defined in [classes/Cart.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L75)


### <a name="property-$checkedTos"></a>$checkedTos

    public mixed $checkedTos = false





* Visibility: **public**
* This property is defined in [classes/Cart.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L77)


### <a name="property-$pictures"></a>$pictures

    public mixed $pictures





* Visibility: **public**
* This property is defined in [classes/Cart.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L78)


### <a name="property-$textFields"></a>$textFields

    public mixed $textFields





* Visibility: **public**
* This property is defined in [classes/Cart.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L79)


### <a name="property-$delivery_option"></a>$delivery_option

    public mixed $delivery_option





* Visibility: **public**
* This property is defined in [classes/Cart.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L81)


### <a name="property-$allow_seperated_package"></a>$allow_seperated_package

    public boolean $allow_seperated_package = false





* Visibility: **public**
* This property is defined in [classes/Cart.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L84)


### <a name="property-$_nbProducts"></a>$_nbProducts

    protected mixed $_nbProducts = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Cart.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L86)


### <a name="property-$_isVirtualCart"></a>$_isVirtualCart

    protected mixed $_isVirtualCart = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Cart.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L87)


### <a name="property-$_products"></a>$_products

    protected mixed $_products = null





* Visibility: **protected**
* This property is defined in [classes/Cart.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L89)


### <a name="property-$_totalWeight"></a>$_totalWeight

    protected mixed $_totalWeight = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Cart.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L90)


### <a name="property-$_taxCalculationMethod"></a>$_taxCalculationMethod

    protected mixed $_taxCalculationMethod = PS_TAX_EXC





* Visibility: **protected**
* This property is defined in [classes/Cart.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L91)


### <a name="property-$_carriers"></a>$_carriers

    protected mixed $_carriers = null





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Cart.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L92)


### <a name="property-$_taxes_rate"></a>$_taxes_rate

    protected mixed $_taxes_rate = null





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Cart.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L93)


### <a name="property-$_attributesLists"></a>$_attributesLists

    protected mixed $_attributesLists = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Cart.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L94)


### <a name="property-$_customer"></a>$_customer

    protected \Customer $_customer = null





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Cart.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L97)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'cart', 'primary' => 'id_cart', 'fields' => array('id_shop_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_shop' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_address_delivery' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_address_invoice' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_carrier' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_guest' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_lang' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'recyclable' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'gift' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'gift_message' => array('type' => self::TYPE_STRING, 'validate' => 'isMessage'), 'mobile_theme' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'delivery_option' => array('type' => self::TYPE_STRING), 'secure_key' => array('type' => self::TYPE_STRING, 'size' => 32), 'allow_seperated_package' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Cart.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L102)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_address_delivery' => array('xlink_resource' => 'addresses'), 'id_address_invoice' => array('xlink_resource' => 'addresses'), 'id_currency' => array('xlink_resource' => 'currencies'), 'id_customer' => array('xlink_resource' => 'customers'), 'id_guest' => array('xlink_resource' => 'guests'), 'id_lang' => array('xlink_resource' => 'languages')), 'associations' => array('cart_rows' => array('resource' => 'cart_row', 'virtual_entity' => true, 'fields' => array('id_product' => array('required' => true, 'xlink_resource' => 'products'), 'id_product_attribute' => array('required' => true, 'xlink_resource' => 'combinations'), 'id_address_delivery' => array('required' => true, 'xlink_resource' => 'addresses'), 'quantity' => array('required' => true)))))





* Visibility: **protected**
* This property is defined in [classes/Cart.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L127)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed CartCore::__construct($id, $id_lang)





* Visibility: **public**
* This method is defined in [classes/Cart.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L156)


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### <a name="method-setTaxCalculationMethod"></a>setTaxCalculationMethod

    mixed CartCore::setTaxCalculationMethod()





* Visibility: **public**
* This method is defined in [classes/Cart.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L182)




### <a name="method-add"></a>add

    mixed CartCore::add($autodate, $null_values)





* Visibility: **public**
* This method is defined in [classes/Cart.php line 187](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L187)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-update"></a>update

    mixed CartCore::update($null_values)





* Visibility: **public**
* This method is defined in [classes/Cart.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L202)


#### Arguments
* $null_values **mixed**



### <a name="method-updateAddressId"></a>updateAddressId

    mixed CartCore::updateAddressId(integer $id_address, integer $id_address_new)

Update the address id of the cart



* Visibility: **public**
* This method is defined in [classes/Cart.php line 225](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L225)


#### Arguments
* $id_address **integer** - &lt;p&gt;Current address id to change&lt;/p&gt;
* $id_address_new **integer** - &lt;p&gt;New address id&lt;/p&gt;



### <a name="method-delete"></a>delete

    mixed CartCore::delete()





* Visibility: **public**
* This method is defined in [classes/Cart.php line 253](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L253)




### <a name="method-getTaxesAverageUsed"></a>getTaxesAverageUsed

    mixed CartCore::getTaxesAverageUsed($id_cart)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Cart.php line 293](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L293)


#### Arguments
* $id_cart **mixed**



### <a name="method-getAverageProductsTaxRate"></a>getAverageProductsTaxRate

    mixed CartCore::getAverageProductsTaxRate($cart_amount_te, $cart_amount_ti)

The arguments are optional and only serve as return values in case caller needs the details.



* Visibility: **public**
* This method is defined in [classes/Cart.php line 341](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L341)


#### Arguments
* $cart_amount_te **mixed**
* $cart_amount_ti **mixed**



### <a name="method-getDiscounts"></a>getDiscounts

    mixed CartCore::getDiscounts($lite, $refresh)





* Visibility: **public**
* This method is defined in [classes/Cart.php line 358](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L358)


#### Arguments
* $lite **mixed**
* $refresh **mixed**



### <a name="method-getCartRules"></a>getCartRules

    mixed CartCore::getCartRules($filter)





* Visibility: **public**
* This method is defined in [classes/Cart.php line 364](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L364)


#### Arguments
* $filter **mixed**



### <a name="method-getOrderedCartRulesIds"></a>getOrderedCartRulesIds

    array CartCore::getOrderedCartRulesIds($filter)

Return the cart rules Ids on the cart.



* Visibility: **public**
* This method is defined in [classes/Cart.php line 414](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L414)


#### Arguments
* $filter **mixed**



### <a name="method-getDiscountsCustomer"></a>getDiscountsCustomer

    mixed CartCore::getDiscountsCustomer($id_cart_rule)





* Visibility: **public**
* This method is defined in [classes/Cart.php line 440](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L440)


#### Arguments
* $id_cart_rule **mixed**



### <a name="method-getLastProduct"></a>getLastProduct

    mixed CartCore::getLastProduct()





* Visibility: **public**
* This method is defined in [classes/Cart.php line 457](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L457)




### <a name="method-getProducts"></a>getProducts

    mixed CartCore::getProducts($refresh, $id_product, $id_country)

Return cart products



* Visibility: **public**
* This method is defined in [classes/Cart.php line 486](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L486)


#### Arguments
* $refresh **mixed**
* $id_product **mixed**
* $id_country **mixed**



### <a name="method-cacheSomeAttributesLists"></a>cacheSomeAttributesLists

    mixed CartCore::cacheSomeAttributesLists($ipa_list, $id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Cart.php line 747](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L747)


#### Arguments
* $ipa_list **mixed**
* $id_lang **mixed**



### <a name="method-nbProducts"></a>nbProducts

    mixed CartCore::nbProducts()

Return cart products quantity



* Visibility: **public**
* This method is defined in [classes/Cart.php line 806](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L806)




### <a name="method-getNbProducts"></a>getNbProducts

    mixed CartCore::getNbProducts($id)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Cart.php line 815](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L815)


#### Arguments
* $id **mixed**



### <a name="method-addDiscount"></a>addDiscount

    mixed CartCore::addDiscount($id_cart_rule)





* Visibility: **public**
* This method is defined in [classes/Cart.php line 834](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L834)


#### Arguments
* $id_cart_rule **mixed**



### <a name="method-addCartRule"></a>addCartRule

    mixed CartCore::addCartRule($id_cart_rule)





* Visibility: **public**
* This method is defined in [classes/Cart.php line 840](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L840)


#### Arguments
* $id_cart_rule **mixed**



### <a name="method-containsProduct"></a>containsProduct

    mixed CartCore::containsProduct($id_product, $id_product_attribute, $id_customization, $id_address_delivery)





* Visibility: **public**
* This method is defined in [classes/Cart.php line 878](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L878)


#### Arguments
* $id_product **mixed**
* $id_product_attribute **mixed**
* $id_customization **mixed**
* $id_address_delivery **mixed**



### <a name="method-updateQty"></a>updateQty

    mixed CartCore::updateQty(integer $quantity, integer $id_product, integer $id_product_attribute, $id_customization, string $operator, $id_address_delivery, \Shop $shop, $auto_add_cart_rule)

Update product quantity



* Visibility: **public**
* This method is defined in [classes/Cart.php line 913](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L913)


#### Arguments
* $quantity **integer** - &lt;p&gt;Quantity to add (or substract)&lt;/p&gt;
* $id_product **integer** - &lt;p&gt;Product ID&lt;/p&gt;
* $id_product_attribute **integer** - &lt;p&gt;Attribute ID if needed&lt;/p&gt;
* $id_customization **mixed**
* $operator **string** - &lt;p&gt;Indicate if quantity must be increased or decreased&lt;/p&gt;
* $id_address_delivery **mixed**
* $shop **[Shop](ShopCore)**
* $auto_add_cart_rule **mixed**



### <a name="method-_updateCustomizationQuantity"></a>_updateCustomizationQuantity

    mixed CartCore::_updateCustomizationQuantity($quantity, $id_customization, $id_product, $id_product_attribute, $id_address_delivery, $operator)





* Visibility: **protected**
* This method is defined in [classes/Cart.php line 1089](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L1089)


#### Arguments
* $quantity **mixed**
* $id_customization **mixed**
* $id_product **mixed**
* $id_product_attribute **mixed**
* $id_address_delivery **mixed**
* $operator **mixed**



### <a name="method-_addCustomization"></a>_addCustomization

    boolean CartCore::_addCustomization(integer $id_product, integer $id_product_attribute, integer $index, integer $type, string $field, integer $quantity)

Add customization item to database



* Visibility: **public**
* This method is defined in [classes/Cart.php line 1152](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L1152)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $index **integer**
* $type **integer**
* $field **string**
* $quantity **integer**



### <a name="method-orderExists"></a>orderExists

    boolean CartCore::orderExists()

Check if order has already been placed



* Visibility: **public**
* This method is defined in [classes/Cart.php line 1202](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L1202)




### <a name="method-deleteDiscount"></a>deleteDiscount

    mixed CartCore::deleteDiscount($id_cart_rule)





* Visibility: **public**
* This method is defined in [classes/Cart.php line 1216](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L1216)


#### Arguments
* $id_cart_rule **mixed**



### <a name="method-removeCartRule"></a>removeCartRule

    mixed CartCore::removeCartRule($id_cart_rule)





* Visibility: **public**
* This method is defined in [classes/Cart.php line 1222](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L1222)


#### Arguments
* $id_cart_rule **mixed**



### <a name="method-deleteProduct"></a>deleteProduct

    boolean CartCore::deleteProduct(integer $id_product, integer $id_product_attribute, integer $id_customization, $id_address_delivery)

Delete a product from the cart



* Visibility: **public**
* This method is defined in [classes/Cart.php line 1252](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L1252)


#### Arguments
* $id_product **integer** - &lt;p&gt;Product ID&lt;/p&gt;
* $id_product_attribute **integer** - &lt;p&gt;Attribute ID if needed&lt;/p&gt;
* $id_customization **integer** - &lt;p&gt;Customization id&lt;/p&gt;
* $id_address_delivery **mixed**



### <a name="method-_deleteCustomization"></a>_deleteCustomization

    boolean CartCore::_deleteCustomization(integer $id_customization, $id_product, $id_product_attribute, $id_address_delivery)

Delete a customization from the cart. If customization is a Picture,
then the image is also deleted



* Visibility: **protected**
* This method is defined in [classes/Cart.php line 1338](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L1338)


#### Arguments
* $id_customization **integer**
* $id_product **mixed**
* $id_product_attribute **mixed**
* $id_address_delivery **mixed**



### <a name="method-getTotalCart"></a>getTotalCart

    mixed CartCore::getTotalCart($id_cart, $use_tax_display, $type)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Cart.php line 1384](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L1384)


#### Arguments
* $id_cart **mixed**
* $use_tax_display **mixed**
* $type **mixed**



### <a name="method-getOrderTotalUsingTaxCalculationMethod"></a>getOrderTotalUsingTaxCalculationMethod

    mixed CartCore::getOrderTotalUsingTaxCalculationMethod($id_cart)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Cart.php line 1396](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L1396)


#### Arguments
* $id_cart **mixed**



### <a name="method-getOrderTotal"></a>getOrderTotal

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
* This method is defined in [classes/Cart.php line 1419](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L1419)


#### Arguments
* $with_taxes **mixed**
* $type **integer** - &lt;p&gt;Total type&lt;/p&gt;
* $products **mixed**
* $id_carrier **mixed**
* $use_cache **boolean** - &lt;p&gt;Allow using cache of the method CartRule::getContextualValue&lt;/p&gt;



### <a name="method-getGiftWrappingPrice"></a>getGiftWrappingPrice

    float CartCore::getGiftWrappingPrice(boolean $with_taxes, $id_address)

Get the gift wrapping price



* Visibility: **public**
* This method is defined in [classes/Cart.php line 1695](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L1695)


#### Arguments
* $with_taxes **boolean** - &lt;p&gt;With or without taxes&lt;/p&gt;
* $id_address **mixed**



### <a name="method-getNbOfPackages"></a>getNbOfPackages

    integer CartCore::getNbOfPackages()

Get the number of packages



* Visibility: **public**
* This method is defined in [classes/Cart.php line 1743](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L1743)




### <a name="method-getPackageList"></a>getPackageList

    array CartCore::getPackageList($flush)

Get products grouped by package and by addresses to be sent individualy (one package = one shipping cost).



* Visibility: **public**
* This method is defined in [classes/Cart.php line 1771](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L1771)


#### Arguments
* $flush **mixed**



### <a name="method-getPackageIdWarehouse"></a>getPackageIdWarehouse

    mixed CartCore::getPackageIdWarehouse($package, $id_carrier)





* Visibility: **public**
* This method is defined in [classes/Cart.php line 2010](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L2010)


#### Arguments
* $package **mixed**
* $id_carrier **mixed**



### <a name="method-getDeliveryOptionList"></a>getDeliveryOptionList

    array CartCore::getDeliveryOptionList(\Country $default_country, boolean $flush)

Get all deliveries options available for the current cart



* Visibility: **public**
* This method is defined in [classes/Cart.php line 2063](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L2063)


#### Arguments
* $default_country **[Country](CountryCore)**
* $flush **boolean** - &lt;p&gt;Force flushing cache&lt;/p&gt;



### <a name="method-sortDeliveryOptionList"></a>sortDeliveryOptionList

    integer CartCore::sortDeliveryOptionList($option1, $option2)

Sort list of option delivery by parameters define in the BO



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Cart.php line 2338](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L2338)


#### Arguments
* $option1 **mixed**
* $option2 **mixed**



### <a name="method-carrierIsSelected"></a>carrierIsSelected

    mixed CartCore::carrierIsSelected($id_carrier, $id_address)





* Visibility: **public**
* This method is defined in [classes/Cart.php line 2365](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L2365)


#### Arguments
* $id_carrier **mixed**
* $id_address **mixed**



### <a name="method-simulateCarriersOutput"></a>simulateCarriersOutput

    mixed CartCore::simulateCarriersOutput(\Country $default_country, boolean $flush)

Get all deliveries options available for the current cart formated like Carriers::getCarriersForOrder
This method was wrote for retrocompatibility with 1.4 theme
New theme need to use Cart::getDeliveryOptionList() to generate carriers option in the checkout process



* Visibility: **public**
* This method is defined in [classes/Cart.php line 2396](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L2396)


#### Arguments
* $default_country **[Country](CountryCore)**
* $flush **boolean** - &lt;p&gt;Force flushing cache&lt;/p&gt;



### <a name="method-simulateCarrierSelectedOutput"></a>simulateCarrierSelectedOutput

    mixed CartCore::simulateCarrierSelectedOutput($use_cache)





* Visibility: **public**
* This method is defined in [classes/Cart.php line 2444](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L2444)


#### Arguments
* $use_cache **mixed**



### <a name="method-intifier"></a>intifier

    integer CartCore::intifier($string, $delimiter)

Translate a string option_delivery identifier ('24,3,') in a int (3240002000)

The  option_delivery identifier is a list of integers separated by a ','.
This method replace the delimiter by a sequence of '0'.
The size of this sequence is fixed by the first digit of the return

* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Cart.php line 2464](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L2464)


#### Arguments
* $string **mixed**
* $delimiter **mixed**



### <a name="method-desintifier"></a>desintifier

    mixed CartCore::desintifier($int, $delimiter)

Translate a int option_delivery identifier (3240002000) in a string ('24,3,')



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Cart.php line 2474](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L2474)


#### Arguments
* $int **mixed**
* $delimiter **mixed**



### <a name="method-isMultiAddressDelivery"></a>isMultiAddressDelivery

    boolean CartCore::isMultiAddressDelivery()

Does the cart use multiple address



* Visibility: **public**
* This method is defined in [classes/Cart.php line 2486](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L2486)




### <a name="method-getAddressCollection"></a>getAddressCollection

    mixed CartCore::getAddressCollection()

Get all delivery addresses object for the current cart



* Visibility: **public**
* This method is defined in [classes/Cart.php line 2504](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L2504)




### <a name="method-setDeliveryOption"></a>setDeliveryOption

    mixed CartCore::setDeliveryOption($delivery_option)

Set the delivery option and id_carrier, if there is only one carrier



* Visibility: **public**
* This method is defined in [classes/Cart.php line 2532](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L2532)


#### Arguments
* $delivery_option **mixed**



### <a name="method-getIdCarrierFromDeliveryOption"></a>getIdCarrierFromDeliveryOption

    mixed CartCore::getIdCarrierFromDeliveryOption($delivery_option)





* Visibility: **protected**
* This method is defined in [classes/Cart.php line 2560](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L2560)


#### Arguments
* $delivery_option **mixed**



### <a name="method-getDeliveryOption"></a>getDeliveryOption

    array|boolean|mixed CartCore::getDeliveryOption(\Country|null $default_country, boolean $dontAutoSelectOptions, boolean $use_cache)

Get the delivery option selected, or if no delivery option was selected,
the cheapest option for each address



* Visibility: **public**
* This method is defined in [classes/Cart.php line 2584](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L2584)


#### Arguments
* $default_country **[Country](CountryCore)|null**
* $dontAutoSelectOptions **boolean**
* $use_cache **boolean**



### <a name="method-getTotalShippingCost"></a>getTotalShippingCost

    float CartCore::getTotalShippingCost(array|null $delivery_option, boolean $use_tax, \Country|null $default_country)

Return shipping total for the cart



* Visibility: **public**
* This method is defined in [classes/Cart.php line 2650](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L2650)


#### Arguments
* $delivery_option **array|null** - &lt;p&gt;Array of the delivery option for each address&lt;/p&gt;
* $use_tax **boolean**
* $default_country **[Country](CountryCore)|null**



### <a name="method-getCarrierCost"></a>getCarrierCost

    float CartCore::getCarrierCost(integer $id_carrier, boolean $useTax, \Country|null $default_country, array $delivery_option)

Return shipping total of a specific carriers for the cart



* Visibility: **public**
* This method is defined in [classes/Cart.php line 2685](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L2685)


#### Arguments
* $id_carrier **integer**
* $useTax **boolean**
* $default_country **[Country](CountryCore)|null**
* $delivery_option **array** - &lt;p&gt;Array of the delivery option for each address&lt;/p&gt;



### <a name="method-getOrderShippingCost"></a>getOrderShippingCost

    mixed CartCore::getOrderShippingCost($id_carrier, $use_tax, \Country $default_country, $product_list)





* Visibility: **public**
* This method is defined in [classes/Cart.php line 2714](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L2714)


#### Arguments
* $id_carrier **mixed**
* $use_tax **mixed**
* $default_country **[Country](CountryCore)**
* $product_list **mixed**



### <a name="method-getPackageShippingCost"></a>getPackageShippingCost

    float CartCore::getPackageShippingCost(integer $id_carrier, boolean $use_tax, \Country|null $default_country, array|null $product_list, integer|null $id_zone)

Return package shipping cost



* Visibility: **public**
* This method is defined in [classes/Cart.php line 2732](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L2732)


#### Arguments
* $id_carrier **integer** - &lt;p&gt;Carrier ID (default : current carrier)&lt;/p&gt;
* $use_tax **boolean**
* $default_country **[Country](CountryCore)|null**
* $product_list **array|null** - &lt;p&gt;List of product concerned by the shipping.
                                     If null, all the product of the cart are used to calculate the shipping cost&lt;/p&gt;
* $id_zone **integer|null**



### <a name="method-getTotalWeight"></a>getTotalWeight

    float CartCore::getTotalWeight($products)

Return cart weight



* Visibility: **public**
* This method is defined in [classes/Cart.php line 3044](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L3044)


#### Arguments
* $products **mixed**



### <a name="method-checkDiscountValidity"></a>checkDiscountValidity

    boolean|string CartCore::checkDiscountValidity(\CartRule $obj, $discounts, $order_total, $products, $check_cart_discount)





* Visibility: **public**
* This method is defined in [classes/Cart.php line 3089](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L3089)


#### Arguments
* $obj **[CartRule](CartRuleCore)**
* $discounts **mixed**
* $order_total **mixed**
* $products **mixed**
* $check_cart_discount **mixed**



### <a name="method-getSummaryDetails"></a>getSummaryDetails

    array CartCore::getSummaryDetails($id_lang, $refresh)

Return useful informations for cart



* Visibility: **public**
* This method is defined in [classes/Cart.php line 3103](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L3103)


#### Arguments
* $id_lang **mixed**
* $refresh **mixed**



### <a name="method-checkQuantities"></a>checkQuantities

    mixed CartCore::checkQuantities($return_product)





* Visibility: **public**
* This method is defined in [classes/Cart.php line 3259](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L3259)


#### Arguments
* $return_product **mixed**



### <a name="method-checkProductsAccess"></a>checkProductsAccess

    mixed CartCore::checkProductsAccess()





* Visibility: **public**
* This method is defined in [classes/Cart.php line 3279](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L3279)




### <a name="method-lastNoneOrderedCart"></a>lastNoneOrderedCart

    mixed CartCore::lastNoneOrderedCart($id_customer)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Cart.php line 3295](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L3295)


#### Arguments
* $id_customer **mixed**



### <a name="method-isVirtualCart"></a>isVirtualCart

    boolean CartCore::isVirtualCart($strict)

Check if cart contains only virtual products



* Visibility: **public**
* This method is defined in [classes/Cart.php line 3317](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L3317)


#### Arguments
* $strict **mixed**



### <a name="method-getCartByOrderId"></a>getCartByOrderId

    \Cart|boolean CartCore::getCartByOrderId(integer $id_order)

Build cart object from provided id_order



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Cart.php line 3347](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L3347)


#### Arguments
* $id_order **integer**



### <a name="method-getCartIdByOrderId"></a>getCartIdByOrderId

    mixed CartCore::getCartIdByOrderId($id_order)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Cart.php line 3356](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L3356)


#### Arguments
* $id_order **mixed**



### <a name="method-addTextFieldToProduct"></a>addTextFieldToProduct

    boolean CartCore::addTextFieldToProduct($id_product, $index, $type, $text_value)

Add customer's text



* Visibility: **public**
* This method is defined in [classes/Cart.php line 3375](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L3375)


#### Arguments
* $id_product **mixed**
* $index **mixed**
* $type **mixed**
* $text_value **mixed**



### <a name="method-addPictureToProduct"></a>addPictureToProduct

    boolean CartCore::addPictureToProduct($id_product, $index, $type, $file)

Add customer's pictures



* Visibility: **public**
* This method is defined in [classes/Cart.php line 3385](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L3385)


#### Arguments
* $id_product **mixed**
* $index **mixed**
* $type **mixed**
* $file **mixed**



### <a name="method-deletePictureToProduct"></a>deletePictureToProduct

    boolean CartCore::deletePictureToProduct(integer $id_product, $index)





* Visibility: **public**
* This method is defined in [classes/Cart.php line 3396](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L3396)


#### Arguments
* $id_product **integer**
* $index **mixed**



### <a name="method-deleteCustomizationToProduct"></a>deleteCustomizationToProduct

    boolean CartCore::deleteCustomizationToProduct(integer $id_product, integer $index)

Remove a customer's customization



* Visibility: **public**
* This method is defined in [classes/Cart.php line 3409](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L3409)


#### Arguments
* $id_product **integer**
* $index **integer**



### <a name="method-getProductCustomization"></a>getProductCustomization

    array CartCore::getProductCustomization(integer $id_product, integer $type, boolean $not_in_cart)

Return custom pictures in this cart for a specified product



* Visibility: **public**
* This method is defined in [classes/Cart.php line 3444](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L3444)


#### Arguments
* $id_product **integer**
* $type **integer** - &lt;p&gt;only return customization of this type&lt;/p&gt;
* $not_in_cart **boolean** - &lt;p&gt;only return customizations that are not in cart already&lt;/p&gt;



### <a name="method-getCustomerCarts"></a>getCustomerCarts

    mixed CartCore::getCustomerCarts($id_customer, $with_order)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Cart.php line 3463](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L3463)


#### Arguments
* $id_customer **mixed**
* $with_order **mixed**



### <a name="method-replaceZeroByShopName"></a>replaceZeroByShopName

    mixed CartCore::replaceZeroByShopName($echo, $tr)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Cart.php line 3473](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L3473)


#### Arguments
* $echo **mixed**
* $tr **mixed**



### <a name="method-duplicate"></a>duplicate

    mixed CartCore::duplicate()





* Visibility: **public**
* This method is defined in [classes/Cart.php line 3478](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L3478)




### <a name="method-getWsCartRows"></a>getWsCartRows

    mixed CartCore::getWsCartRows()





* Visibility: **public**
* This method is defined in [classes/Cart.php line 3589](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L3589)




### <a name="method-setWsCartRows"></a>setWsCartRows

    mixed CartCore::setWsCartRows($values)





* Visibility: **public**
* This method is defined in [classes/Cart.php line 3598](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L3598)


#### Arguments
* $values **mixed**



### <a name="method-setProductAddressDelivery"></a>setProductAddressDelivery

    mixed CartCore::setProductAddressDelivery($id_product, $id_product_attribute, $old_id_address_delivery, $new_id_address_delivery)





* Visibility: **public**
* This method is defined in [classes/Cart.php line 3616](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L3616)


#### Arguments
* $id_product **mixed**
* $id_product_attribute **mixed**
* $old_id_address_delivery **mixed**
* $new_id_address_delivery **mixed**



### <a name="method-duplicateProduct"></a>duplicateProduct

    mixed CartCore::duplicateProduct($id_product, $id_product_attribute, $id_address_delivery, $new_id_address_delivery, $quantity, $keep_quantity)





* Visibility: **public**
* This method is defined in [classes/Cart.php line 3683](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L3683)


#### Arguments
* $id_product **mixed**
* $id_product_attribute **mixed**
* $id_address_delivery **mixed**
* $new_id_address_delivery **mixed**
* $quantity **mixed**
* $keep_quantity **mixed**



### <a name="method-setNoMultishipping"></a>setNoMultishipping

    mixed CartCore::setNoMultishipping()

Update products cart address delivery with the address delivery of the cart



* Visibility: **public**
* This method is defined in [classes/Cart.php line 3798](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L3798)




### <a name="method-autosetProductAddress"></a>autosetProductAddress

    mixed CartCore::autosetProductAddress()

Set an address to all products on the cart without address delivery



* Visibility: **public**
* This method is defined in [classes/Cart.php line 3871](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L3871)




### <a name="method-deleteAssociations"></a>deleteAssociations

    mixed CartCore::deleteAssociations()





* Visibility: **public**
* This method is defined in [classes/Cart.php line 3901](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L3901)




### <a name="method-isGuestCartByCartId"></a>isGuestCartByCartId

    boolean CartCore::isGuestCartByCartId(integer $id_cart)

isGuestCartByCartId



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Cart.php line 3914](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L3914)


#### Arguments
* $id_cart **integer**



### <a name="method-isCarrierInRange"></a>isCarrierInRange

    mixed CartCore::isCarrierInRange($id_carrier, $id_zone)

isCarrierInRange

Check if the specified carrier is in range

* Visibility: **public**
* This method is defined in [classes/Cart.php line 3934](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L3934)


#### Arguments
* $id_carrier **mixed**
* $id_zone **mixed**



### <a name="method-isAllProductsInStock"></a>isAllProductsInStock

    boolean CartCore::isAllProductsInStock(boolean $ignore_virtual, boolean $exclusive)





* Visibility: **public**
* This method is defined in [classes/Cart.php line 3978](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L3978)


#### Arguments
* $ignore_virtual **boolean** - &lt;p&gt;Ignore virtual product&lt;/p&gt;
* $exclusive **boolean** - &lt;p&gt;If true, the validation is exclusive : it must be present product in stock and out of stock&lt;/p&gt;



### <a name="method-addExtraCarriers"></a>addExtraCarriers

    mixed CartCore::addExtraCarriers(array $array)

Execute hook displayCarrierList (extraCarrier) and merge theme to the $array



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Cart.php line 4011](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L4011)


#### Arguments
* $array **array**



### <a name="method-getDeliveryAddressesWithoutCarriers"></a>getDeliveryAddressesWithoutCarriers

    array CartCore::getDeliveryAddressesWithoutCarriers(boolean $return_collection, $error)

Get all the ids of the delivery addresses without carriers



* Visibility: **public**
* This method is defined in [classes/Cart.php line 4040](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Cart.php#L4040)


#### Arguments
* $return_collection **boolean** - &lt;p&gt;Return a collection&lt;/p&gt;
* $error **mixed**


