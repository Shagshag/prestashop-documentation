Class CartCore
=====================





* Class name: CartCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Cart.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L27)


Contents
--------

### Constants

* [BOTH](#constant-BOTH)
* [BOTH_WITHOUT_SHIPPING](#constant-BOTH_WITHOUT_SHIPPING)
* [ONLY_DISCOUNTS](#constant-ONLY_DISCOUNTS)
* [ONLY_PHYSICAL_PRODUCTS_WITHOUT_SHIPPING](#constant-ONLY_PHYSICAL_PRODUCTS_WITHOUT_SHIPPING)
* [ONLY_PRODUCTS](#constant-ONLY_PRODUCTS)
* [ONLY_PRODUCTS_WITHOUT_SHIPPING](#constant-ONLY_PRODUCTS_WITHOUT_SHIPPING)
* [ONLY_SHIPPING](#constant-ONLY_SHIPPING)
* [ONLY_WRAPPING](#constant-ONLY_WRAPPING)

### Properties

* [$_attributesLists](#property-$_attributesLists)
* [$_carriers](#property-$_carriers)
* [$_isVirtualCart](#property-$_isVirtualCart)
* [$_nbProducts](#property-$_nbProducts)
* [$_products](#property-$_products)
* [$_taxCalculationMethod](#property-$_taxCalculationMethod)
* [$_taxes_rate](#property-$_taxes_rate)
* [$_totalWeight](#property-$_totalWeight)
* [$allow_seperated_package](#property-$allow_seperated_package)
* [$checkedTos](#property-$checkedTos)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$delivery_option](#property-$delivery_option)
* [$gift](#property-$gift)
* [$gift_message](#property-$gift_message)
* [$id](#property-$id)
* [$id_address_delivery](#property-$id_address_delivery)
* [$id_address_invoice](#property-$id_address_invoice)
* [$id_carrier](#property-$id_carrier)
* [$id_currency](#property-$id_currency)
* [$id_customer](#property-$id_customer)
* [$id_guest](#property-$id_guest)
* [$id_lang](#property-$id_lang)
* [$id_shop](#property-$id_shop)
* [$id_shop_group](#property-$id_shop_group)
* [$mobile_theme](#property-$mobile_theme)
* [$pictures](#property-$pictures)
* [$recyclable](#property-$recyclable)
* [$secure_key](#property-$secure_key)
* [$textFields](#property-$textFields)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [__construct](#method-__construct)
* [_addCustomization](#method-_addCustomization)
* [_deleteCustomization](#method-_deleteCustomization)
* [_updateCustomizationQuantity](#method-_updateCustomizationQuantity)
* [add](#method-add)
* [addCartRule](#method-addCartRule)
* [addDiscount](#method-addDiscount)
* [addExtraCarriers](#method-addExtraCarriers)
* [addPictureToProduct](#method-addPictureToProduct)
* [addTextFieldToProduct](#method-addTextFieldToProduct)
* [autosetProductAddress](#method-autosetProductAddress)
* [cacheSomeAttributesLists](#method-cacheSomeAttributesLists)
* [carrierIsSelected](#method-carrierIsSelected)
* [checkDiscountValidity](#method-checkDiscountValidity)
* [checkQuantities](#method-checkQuantities)
* [containsProduct](#method-containsProduct)
* [delete](#method-delete)
* [deleteAssociations](#method-deleteAssociations)
* [deleteCustomizationToProduct](#method-deleteCustomizationToProduct)
* [deleteDiscount](#method-deleteDiscount)
* [deletePictureToProduct](#method-deletePictureToProduct)
* [deleteProduct](#method-deleteProduct)
* [desintifier](#method-desintifier)
* [duplicate](#method-duplicate)
* [duplicateProduct](#method-duplicateProduct)
* [getAddressCollection](#method-getAddressCollection)
* [getCarrierCost](#method-getCarrierCost)
* [getCartByOrderId](#method-getCartByOrderId)
* [getCartIdByOrderId](#method-getCartIdByOrderId)
* [getCartRules](#method-getCartRules)
* [getCustomerCarts](#method-getCustomerCarts)
* [getDeliveryAddressesWithoutCarriers](#method-getDeliveryAddressesWithoutCarriers)
* [getDeliveryOption](#method-getDeliveryOption)
* [getDeliveryOptionList](#method-getDeliveryOptionList)
* [getDiscounts](#method-getDiscounts)
* [getDiscountsCustomer](#method-getDiscountsCustomer)
* [getGiftWrappingPrice](#method-getGiftWrappingPrice)
* [getIdCarrierFromDeliveryOption](#method-getIdCarrierFromDeliveryOption)
* [getLastProduct](#method-getLastProduct)
* [getNbOfPackages](#method-getNbOfPackages)
* [getNbProducts](#method-getNbProducts)
* [getOrderShippingCost](#method-getOrderShippingCost)
* [getOrderTotal](#method-getOrderTotal)
* [getOrderTotalUsingTaxCalculationMethod](#method-getOrderTotalUsingTaxCalculationMethod)
* [getPackageIdWarehouse](#method-getPackageIdWarehouse)
* [getPackageList](#method-getPackageList)
* [getPackageShippingCost](#method-getPackageShippingCost)
* [getProductCustomization](#method-getProductCustomization)
* [getProducts](#method-getProducts)
* [getSummaryDetails](#method-getSummaryDetails)
* [getTaxesAverageUsed](#method-getTaxesAverageUsed)
* [getTotalCart](#method-getTotalCart)
* [getTotalShippingCost](#method-getTotalShippingCost)
* [getTotalWeight](#method-getTotalWeight)
* [getWsCartRows](#method-getWsCartRows)
* [intifier](#method-intifier)
* [isAllProductsInStock](#method-isAllProductsInStock)
* [isCarrierInRange](#method-isCarrierInRange)
* [isGuestCartByCartId](#method-isGuestCartByCartId)
* [isMultiAddressDelivery](#method-isMultiAddressDelivery)
* [isVirtualCart](#method-isVirtualCart)
* [lastNoneOrderedCart](#method-lastNoneOrderedCart)
* [nbProducts](#method-nbProducts)
* [orderExists](#method-orderExists)
* [removeCartRule](#method-removeCartRule)
* [replaceZeroByShopName](#method-replaceZeroByShopName)
* [setDeliveryOption](#method-setDeliveryOption)
* [setNoMultishipping](#method-setNoMultishipping)
* [setProductAddressDelivery](#method-setProductAddressDelivery)
* [setWsCartRows](#method-setWsCartRows)
* [simulateCarrierSelectedOutput](#method-simulateCarrierSelectedOutput)
* [simulateCarriersOutput](#method-simulateCarriersOutput)
* [sortDeliveryOptionList](#method-sortDeliveryOptionList)
* [update](#method-update)
* [updateAddressId](#method-updateAddressId)
* [updateQty](#method-updateQty)


Constants
----------


### <a name="constant-BOTH"></a>BOTH

```php
const BOTH = 3
```





* Source: [classes/Cart.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L146).


### <a name="constant-BOTH_WITHOUT_SHIPPING"></a>BOTH_WITHOUT_SHIPPING

```php
const BOTH_WITHOUT_SHIPPING = 4
```





* Source: [classes/Cart.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L147).


### <a name="constant-ONLY_DISCOUNTS"></a>ONLY_DISCOUNTS

```php
const ONLY_DISCOUNTS = 2
```





* Source: [classes/Cart.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L145).


### <a name="constant-ONLY_PHYSICAL_PRODUCTS_WITHOUT_SHIPPING"></a>ONLY_PHYSICAL_PRODUCTS_WITHOUT_SHIPPING

```php
const ONLY_PHYSICAL_PRODUCTS_WITHOUT_SHIPPING = 8
```





* Source: [classes/Cart.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L151).


### <a name="constant-ONLY_PRODUCTS"></a>ONLY_PRODUCTS

```php
const ONLY_PRODUCTS = 1
```





* Source: [classes/Cart.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L144).


### <a name="constant-ONLY_PRODUCTS_WITHOUT_SHIPPING"></a>ONLY_PRODUCTS_WITHOUT_SHIPPING

```php
const ONLY_PRODUCTS_WITHOUT_SHIPPING = 7
```





* Source: [classes/Cart.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L150).


### <a name="constant-ONLY_SHIPPING"></a>ONLY_SHIPPING

```php
const ONLY_SHIPPING = 5
```





* Source: [classes/Cart.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L148).


### <a name="constant-ONLY_WRAPPING"></a>ONLY_WRAPPING

```php
const ONLY_WRAPPING = 6
```





* Source: [classes/Cart.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L149).


Properties
----------


### <a name="property-$_attributesLists"></a>$_attributesLists

```php
protected mixed $_attributesLists = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Cart.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L94).


### <a name="property-$_carriers"></a>$_carriers

```php
protected mixed $_carriers = null
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Cart.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L92).


### <a name="property-$_isVirtualCart"></a>$_isVirtualCart

```php
protected mixed $_isVirtualCart = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Cart.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L87).


### <a name="property-$_nbProducts"></a>$_nbProducts

```php
protected mixed $_nbProducts = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Cart.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L86).


### <a name="property-$_products"></a>$_products

```php
protected mixed $_products = null
```





* Visibility: **protected**
* Source: [classes/Cart.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L89).


### <a name="property-$_taxCalculationMethod"></a>$_taxCalculationMethod

```php
protected mixed $_taxCalculationMethod = PS_TAX_EXC
```





* Visibility: **protected**
* Source: [classes/Cart.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L91).


### <a name="property-$_taxes_rate"></a>$_taxes_rate

```php
protected mixed $_taxes_rate = null
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Cart.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L93).


### <a name="property-$_totalWeight"></a>$_totalWeight

```php
protected mixed $_totalWeight = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Cart.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L90).


### <a name="property-$allow_seperated_package"></a>$allow_seperated_package

```php
public boolean $allow_seperated_package = false
```





* Visibility: **public**
* Source: [classes/Cart.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L84).


### <a name="property-$checkedTos"></a>$checkedTos

```php
public mixed $checkedTos = false
```





* Visibility: **public**
* Source: [classes/Cart.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L77).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/Cart.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L66).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* Source: [classes/Cart.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L75).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'cart', 'primary' => 'id_cart', 'fields' => array('id_shop_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_shop' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_address_delivery' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_address_invoice' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_carrier' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_guest' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_lang' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'recyclable' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'gift' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'gift_message' => array('type' => self::TYPE_STRING, 'validate' => 'isMessage'), 'mobile_theme' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'delivery_option' => array('type' => self::TYPE_STRING), 'secure_key' => array('type' => self::TYPE_STRING, 'size' => 32), 'allow_seperated_package' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDateFormat'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDateFormat')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Cart.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L99).


### <a name="property-$delivery_option"></a>$delivery_option

```php
public mixed $delivery_option
```





* Visibility: **public**
* Source: [classes/Cart.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L81).


### <a name="property-$gift"></a>$gift

```php
public boolean $gift
```





* Visibility: **public**
* Source: [classes/Cart.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L57).


### <a name="property-$gift_message"></a>$gift_message

```php
public string $gift_message
```





* Visibility: **public**
* Source: [classes/Cart.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L60).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/Cart.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L29).


### <a name="property-$id_address_delivery"></a>$id_address_delivery

```php
public integer $id_address_delivery
```





* Visibility: **public**
* Source: [classes/Cart.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L36).


### <a name="property-$id_address_invoice"></a>$id_address_invoice

```php
public integer $id_address_invoice
```





* Visibility: **public**
* Source: [classes/Cart.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L39).


### <a name="property-$id_carrier"></a>$id_carrier

```php
public integer $id_carrier
```





* Visibility: **public**
* Source: [classes/Cart.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L72).


### <a name="property-$id_currency"></a>$id_currency

```php
public integer $id_currency
```





* Visibility: **public**
* Source: [classes/Cart.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L42).


### <a name="property-$id_customer"></a>$id_customer

```php
public integer $id_customer
```





* Visibility: **public**
* Source: [classes/Cart.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L45).


### <a name="property-$id_guest"></a>$id_guest

```php
public integer $id_guest
```





* Visibility: **public**
* Source: [classes/Cart.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L48).


### <a name="property-$id_lang"></a>$id_lang

```php
public integer $id_lang
```





* Visibility: **public**
* Source: [classes/Cart.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L51).


### <a name="property-$id_shop"></a>$id_shop

```php
public mixed $id_shop
```





* Visibility: **public**
* Source: [classes/Cart.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L33).


### <a name="property-$id_shop_group"></a>$id_shop_group

```php
public mixed $id_shop_group
```





* Visibility: **public**
* Source: [classes/Cart.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L31).


### <a name="property-$mobile_theme"></a>$mobile_theme

```php
public boolean $mobile_theme
```





* Visibility: **public**
* Source: [classes/Cart.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L63).


### <a name="property-$pictures"></a>$pictures

```php
public mixed $pictures
```





* Visibility: **public**
* Source: [classes/Cart.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L78).


### <a name="property-$recyclable"></a>$recyclable

```php
public boolean $recyclable
```





* Visibility: **public**
* Source: [classes/Cart.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L54).


### <a name="property-$secure_key"></a>$secure_key

```php
public string $secure_key
```





* Visibility: **public**
* Source: [classes/Cart.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L69).


### <a name="property-$textFields"></a>$textFields

```php
public mixed $textFields
```





* Visibility: **public**
* Source: [classes/Cart.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L79).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_address_delivery' => array('xlink_resource' => 'addresses'), 'id_address_invoice' => array('xlink_resource' => 'addresses'), 'id_currency' => array('xlink_resource' => 'currencies'), 'id_customer' => array('xlink_resource' => 'customers'), 'id_guest' => array('xlink_resource' => 'guests'), 'id_lang' => array('xlink_resource' => 'languages')), 'associations' => array('cart_rows' => array('resource' => 'cart_row', 'virtual_entity' => true, 'fields' => array('id_product' => array('required' => true, 'xlink_resource' => 'products'), 'id_product_attribute' => array('required' => true, 'xlink_resource' => 'combinations'), 'id_address_delivery' => array('required' => true, 'xlink_resource' => 'addresses'), 'quantity' => array('required' => true)))))
```





* Visibility: **protected**
* Source: [classes/Cart.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L124).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed CartCore::__construct($id, $id_lang)
```





* Visibility: **public**
* Source: [classes/Cart.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L153)


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### <a name="method-_addCustomization"></a>_addCustomization

```php
boolean CartCore::_addCustomization(integer $id_product, integer $id_product_attribute, integer $index, integer $type, string $field, integer $quantity)
```

Add customization item to database



* Visibility: **public**
* Source: [classes/Cart.php line 1053](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L1053)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $index **integer**
* $type **integer**
* $field **string**
* $quantity **integer**



### <a name="method-_deleteCustomization"></a>_deleteCustomization

```php
boolean CartCore::_deleteCustomization(integer $id_customization, $id_product, $id_product_attribute, $id_address_delivery)
```

Delete a customization from the cart. If customization is a Picture,
then the image is also deleted



* Visibility: **protected**
* Source: [classes/Cart.php line 1239](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L1239)


#### Arguments
* $id_customization **integer**
* $id_product **mixed**
* $id_product_attribute **mixed**
* $id_address_delivery **mixed**



### <a name="method-_updateCustomizationQuantity"></a>_updateCustomizationQuantity

```php
mixed CartCore::_updateCustomizationQuantity($quantity, $id_customization, $id_product, $id_product_attribute, $id_address_delivery, $operator)
```





* Visibility: **protected**
* Source: [classes/Cart.php line 989](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L989)


#### Arguments
* $quantity **mixed**
* $id_customization **mixed**
* $id_product **mixed**
* $id_product_attribute **mixed**
* $id_address_delivery **mixed**
* $operator **mixed**



### <a name="method-add"></a>add

```php
mixed CartCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Cart.php line 177](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L177)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addCartRule"></a>addCartRule

```php
mixed CartCore::addCartRule($id_cart_rule)
```





* Visibility: **public**
* Source: [classes/Cart.php line 775](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L775)


#### Arguments
* $id_cart_rule **mixed**



### <a name="method-addDiscount"></a>addDiscount

```php
mixed CartCore::addDiscount($id_cart_rule)
```





* Visibility: **public**
* Source: [classes/Cart.php line 769](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L769)


#### Arguments
* $id_cart_rule **mixed**



### <a name="method-addExtraCarriers"></a>addExtraCarriers

```php
mixed CartCore::addExtraCarriers(array $array)
```

Execute hook displayCarrierList (extraCarrier) and merge theme to the $array



* Visibility: **public**
* This method is **static**.
* Source: [classes/Cart.php line 3665](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L3665)


#### Arguments
* $array **array**



### <a name="method-addPictureToProduct"></a>addPictureToProduct

```php
boolean CartCore::addPictureToProduct($id_product, $index, $type, $file)
```

Add customer's pictures



* Visibility: **public**
* Source: [classes/Cart.php line 3093](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L3093)


#### Arguments
* $id_product **mixed**
* $index **mixed**
* $type **mixed**
* $file **mixed**



### <a name="method-addTextFieldToProduct"></a>addTextFieldToProduct

```php
boolean CartCore::addTextFieldToProduct($id_product, $index, $type, $text_value)
```

Add customer's text



* Visibility: **public**
* Source: [classes/Cart.php line 3083](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L3083)


#### Arguments
* $id_product **mixed**
* $index **mixed**
* $type **mixed**
* $text_value **mixed**



### <a name="method-autosetProductAddress"></a>autosetProductAddress

```php
mixed CartCore::autosetProductAddress()
```

Set an address to all products on the cart without address delivery



* Visibility: **public**
* Source: [classes/Cart.php line 3532](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L3532)




### <a name="method-cacheSomeAttributesLists"></a>cacheSomeAttributesLists

```php
mixed CartCore::cacheSomeAttributesLists($ipa_list, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Cart.php line 684](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L684)


#### Arguments
* $ipa_list **mixed**
* $id_lang **mixed**



### <a name="method-carrierIsSelected"></a>carrierIsSelected

```php
mixed CartCore::carrierIsSelected($id_carrier, $id_address)
```





* Visibility: **public**
* Source: [classes/Cart.php line 2178](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L2178)


#### Arguments
* $id_carrier **mixed**
* $id_address **mixed**



### <a name="method-checkDiscountValidity"></a>checkDiscountValidity

```php
mixed CartCore::checkDiscountValidity($obj, $discounts, $order_total, $products, $check_cart_discount)
```





* Visibility: **public**
* Source: [classes/Cart.php line 2856](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L2856)


#### Arguments
* $obj **mixed**
* $discounts **mixed**
* $order_total **mixed**
* $products **mixed**
* $check_cart_discount **mixed**



### <a name="method-checkQuantities"></a>checkQuantities

```php
mixed CartCore::checkQuantities()
```





* Visibility: **public**
* Source: [classes/Cart.php line 2995](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L2995)




### <a name="method-containsProduct"></a>containsProduct

```php
mixed CartCore::containsProduct($id_product, $id_product_attribute, $id_customization, $id_address_delivery)
```





* Visibility: **public**
* Source: [classes/Cart.php line 804](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L804)


#### Arguments
* $id_product **mixed**
* $id_product_attribute **mixed**
* $id_customization **mixed**
* $id_address_delivery **mixed**



### <a name="method-delete"></a>delete

```php
mixed CartCore::delete()
```





* Visibility: **public**
* Source: [classes/Cart.php line 240](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L240)




### <a name="method-deleteAssociations"></a>deleteAssociations

```php
mixed CartCore::deleteAssociations()
```





* Visibility: **public**
* Source: [classes/Cart.php line 3560](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L3560)




### <a name="method-deleteCustomizationToProduct"></a>deleteCustomizationToProduct

```php
boolean CartCore::deleteCustomizationToProduct(integer $id_product, integer $index)
```

Remove a customer's customization



* Visibility: **public**
* Source: [classes/Cart.php line 3111](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L3111)


#### Arguments
* $id_product **integer**
* $index **integer**



### <a name="method-deleteDiscount"></a>deleteDiscount

```php
mixed CartCore::deleteDiscount($id_cart_rule)
```





* Visibility: **public**
* Source: [classes/Cart.php line 1122](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L1122)


#### Arguments
* $id_cart_rule **mixed**



### <a name="method-deletePictureToProduct"></a>deletePictureToProduct

```php
mixed CartCore::deletePictureToProduct($id_product, $index)
```





* Visibility: **public**
* Source: [classes/Cart.php line 3098](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L3098)


#### Arguments
* $id_product **mixed**
* $index **mixed**



### <a name="method-deleteProduct"></a>deleteProduct

```php
boolean CartCore::deleteProduct(integer $id_product, integer $id_product_attribute, integer $id_customization, $id_address_delivery)
```

Delete a product from the cart



* Visibility: **public**
* Source: [classes/Cart.php line 1156](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L1156)


#### Arguments
* $id_product **integer** - Product ID
* $id_product_attribute **integer** - Attribute ID if needed
* $id_customization **integer** - Customization id
* $id_address_delivery **mixed**



### <a name="method-desintifier"></a>desintifier

```php
mixed CartCore::desintifier($int, $delimiter)
```

Translate a int option_delivery identifier (3240002000) in a string ('24,3,')



* Visibility: **public**
* This method is **static**.
* Source: [classes/Cart.php line 2283](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L2283)


#### Arguments
* $int **mixed**
* $delimiter **mixed**



### <a name="method-duplicate"></a>duplicate

```php
mixed CartCore::duplicate()
```





* Visibility: **public**
* Source: [classes/Cart.php line 3178](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L3178)




### <a name="method-duplicateProduct"></a>duplicateProduct

```php
mixed CartCore::duplicateProduct($id_product, $id_product_attribute, $id_address_delivery, $new_id_address_delivery, $quantity, $keep_quantity)
```





* Visibility: **public**
* Source: [classes/Cart.php line 3349](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L3349)


#### Arguments
* $id_product **mixed**
* $id_product_attribute **mixed**
* $id_address_delivery **mixed**
* $new_id_address_delivery **mixed**
* $quantity **mixed**
* $keep_quantity **mixed**



### <a name="method-getAddressCollection"></a>getAddressCollection

```php
mixed CartCore::getAddressCollection()
```

Get all delivery addresses object for the current cart



* Visibility: **public**
* Source: [classes/Cart.php line 2314](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L2314)




### <a name="method-getCarrierCost"></a>getCarrierCost

```php
float CartCore::getCarrierCost(integer $id_carrier, \booleal $useTax, \Country $default_country, array $delivery_option)
```

Return shipping total of a specific carriers for the cart



* Visibility: **public**
* Source: [classes/Cart.php line 2481](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L2481)


#### Arguments
* $id_carrier **integer**
* $useTax **booleal**
* $default_country **[Country](class.CountryCore.md)**
* $delivery_option **array** - Array of the delivery option for each address



### <a name="method-getCartByOrderId"></a>getCartByOrderId

```php
\Cart|boolean CartCore::getCartByOrderId(integer $id_order)
```

Build cart object from provided id_order



* Visibility: **public**
* This method is **static**.
* Source: [classes/Cart.php line 3057](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L3057)


#### Arguments
* $id_order **integer**



### <a name="method-getCartIdByOrderId"></a>getCartIdByOrderId

```php
mixed CartCore::getCartIdByOrderId($id_order)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Cart.php line 3065](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L3065)


#### Arguments
* $id_order **mixed**



### <a name="method-getCartRules"></a>getCartRules

```php
mixed CartCore::getCartRules($filter)
```





* Visibility: **public**
* Source: [classes/Cart.php line 326](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L326)


#### Arguments
* $filter **mixed**



### <a name="method-getCustomerCarts"></a>getCustomerCarts

```php
mixed CartCore::getCustomerCarts($id_customer, $with_order)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Cart.php line 3163](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L3163)


#### Arguments
* $id_customer **mixed**
* $with_order **mixed**



### <a name="method-getDeliveryAddressesWithoutCarriers"></a>getDeliveryAddressesWithoutCarriers

```php
array CartCore::getDeliveryAddressesWithoutCarriers(boolean $return_collection)
```

Get all the ids of the delivery addresses without carriers



* Visibility: **public**
* Source: [classes/Cart.php line 3696](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L3696)


#### Arguments
* $return_collection **boolean** - Return a collection



### <a name="method-getDeliveryOption"></a>getDeliveryOption

```php
array CartCore::getDeliveryOption($default_country, $dontAutoSelectOptions, $use_cache)
```

Get the delivery option seleted, or if no delivery option was selected, the cheapest option for each address



* Visibility: **public**
* Source: [classes/Cart.php line 2381](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L2381)


#### Arguments
* $default_country **mixed**
* $dontAutoSelectOptions **mixed**
* $use_cache **mixed**



### <a name="method-getDeliveryOptionList"></a>getDeliveryOptionList

```php
array CartCore::getDeliveryOptionList(\Country $default_country, boolean $flush)
```

Get all deliveries options available for the current cart



* Visibility: **public**
* Source: [classes/Cart.php line 1908](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L1908)


#### Arguments
* $default_country **[Country](class.CountryCore.md)**
* $flush **boolean** - Force flushing cache



### <a name="method-getDiscounts"></a>getDiscounts

```php
mixed CartCore::getDiscounts($lite, $refresh)
```





* Visibility: **public**
* Source: [classes/Cart.php line 320](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L320)


#### Arguments
* $lite **mixed**
* $refresh **mixed**



### <a name="method-getDiscountsCustomer"></a>getDiscountsCustomer

```php
mixed CartCore::getDiscountsCustomer($id_cart_rule)
```





* Visibility: **public**
* Source: [classes/Cart.php line 371](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L371)


#### Arguments
* $id_cart_rule **mixed**



### <a name="method-getGiftWrappingPrice"></a>getGiftWrappingPrice

```php
float CartCore::getGiftWrappingPrice(boolean $with_taxes, $id_address)
```

Get the gift wrapping price



* Visibility: **public**
* Source: [classes/Cart.php line 1568](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L1568)


#### Arguments
* $with_taxes **boolean** - With or without taxes
* $id_address **mixed**



### <a name="method-getIdCarrierFromDeliveryOption"></a>getIdCarrierFromDeliveryOption

```php
mixed CartCore::getIdCarrierFromDeliveryOption($delivery_option)
```





* Visibility: **protected**
* Source: [classes/Cart.php line 2366](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L2366)


#### Arguments
* $delivery_option **mixed**



### <a name="method-getLastProduct"></a>getLastProduct

```php
mixed CartCore::getLastProduct()
```





* Visibility: **public**
* Source: [classes/Cart.php line 387](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L387)




### <a name="method-getNbOfPackages"></a>getNbOfPackages

```php
integer CartCore::getNbOfPackages()
```

Get the number of packages



* Visibility: **public**
* Source: [classes/Cart.php line 1594](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L1594)




### <a name="method-getNbProducts"></a>getNbProducts

```php
mixed CartCore::getNbProducts($id)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Cart.php line 751](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L751)


#### Arguments
* $id **mixed**



### <a name="method-getOrderShippingCost"></a>getOrderShippingCost

```php
mixed CartCore::getOrderShippingCost($id_carrier, $use_tax, \Country $default_country, $product_list)
```





* Visibility: **public**
* Source: [classes/Cart.php line 2510](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L2510)


#### Arguments
* $id_carrier **mixed**
* $use_tax **mixed**
* $default_country **[Country](class.CountryCore.md)**
* $product_list **mixed**



### <a name="method-getOrderTotal"></a>getOrderTotal

```php
float CartCore::getOrderTotal($with_taxes, integer $type, $products, $id_carrier, boolean $use_cache)
```

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
* Source: [classes/Cart.php line 1317](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L1317)


#### Arguments
* $with_taxes **mixed**
* $type **integer** - Total type
* $products **mixed**
* $id_carrier **mixed**
* $use_cache **boolean** - Allow using cache of the method CartRule::getContextualValue



### <a name="method-getOrderTotalUsingTaxCalculationMethod"></a>getOrderTotalUsingTaxCalculationMethod

```php
mixed CartCore::getOrderTotalUsingTaxCalculationMethod($id_cart)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Cart.php line 1294](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L1294)


#### Arguments
* $id_cart **mixed**



### <a name="method-getPackageIdWarehouse"></a>getPackageIdWarehouse

```php
mixed CartCore::getPackageIdWarehouse($package, $id_carrier)
```





* Visibility: **public**
* Source: [classes/Cart.php line 1858](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L1858)


#### Arguments
* $package **mixed**
* $id_carrier **mixed**



### <a name="method-getPackageList"></a>getPackageList

```php
array CartCore::getPackageList($flush)
```

Get products grouped by package and by addresses to be sent individualy (one package = one shipping cost).



* Visibility: **public**
* Source: [classes/Cart.php line 1619](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L1619)


#### Arguments
* $flush **mixed**



### <a name="method-getPackageShippingCost"></a>getPackageShippingCost

```php
float CartCore::getPackageShippingCost(integer $id_carrier, \booleal $use_tax, \Country $default_country, Array $product_list, $id_zone)
```

Return package shipping cost



* Visibility: **public**
* Source: [classes/Cart.php line 2527](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L2527)


#### Arguments
* $id_carrier **integer** - Carrier ID (default : current carrier)
* $use_tax **booleal**
* $default_country **[Country](class.CountryCore.md)**
* $product_list **Array**
* $id_zone **mixed**



### <a name="method-getProductCustomization"></a>getProductCustomization

```php
array CartCore::getProductCustomization(integer $id_product, integer $type, boolean $not_in_cart)
```

Return custom pictures in this cart for a specified product



* Visibility: **public**
* Source: [classes/Cart.php line 3145](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L3145)


#### Arguments
* $id_product **integer**
* $type **integer** - only return customization of this type
* $not_in_cart **boolean** - only return customizations that are not in cart already



### <a name="method-getProducts"></a>getProducts

```php
mixed CartCore::getProducts($refresh, $id_product, $id_country)
```

Return cart products



* Visibility: **public**
* Source: [classes/Cart.php line 413](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L413)


#### Arguments
* $refresh **mixed**
* $id_product **mixed**
* $id_country **mixed**



### <a name="method-getSummaryDetails"></a>getSummaryDetails

```php
array CartCore::getSummaryDetails($id_lang, $refresh)
```

Return useful informations for cart



* Visibility: **public**
* Source: [classes/Cart.php line 2870](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L2870)


#### Arguments
* $id_lang **mixed**
* $refresh **mixed**



### <a name="method-getTaxesAverageUsed"></a>getTaxesAverageUsed

```php
mixed CartCore::getTaxesAverageUsed($id_cart)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Cart.php line 279](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L279)


#### Arguments
* $id_cart **mixed**



### <a name="method-getTotalCart"></a>getTotalCart

```php
mixed CartCore::getTotalCart($id_cart, $use_tax_display, $type)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Cart.php line 1283](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L1283)


#### Arguments
* $id_cart **mixed**
* $use_tax_display **mixed**
* $type **mixed**



### <a name="method-getTotalShippingCost"></a>getTotalShippingCost

```php
float CartCore::getTotalShippingCost(array $delivery_option, \booleal $use_tax, \Country $default_country)
```

Return shipping total for the cart



* Visibility: **public**
* Source: [classes/Cart.php line 2451](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L2451)


#### Arguments
* $delivery_option **array** - Array of the delivery option for each address
* $use_tax **booleal**
* $default_country **[Country](class.CountryCore.md)**



### <a name="method-getTotalWeight"></a>getTotalWeight

```php
float CartCore::getTotalWeight($products)
```

Return cart weight



* Visibility: **public**
* Source: [classes/Cart.php line 2812](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L2812)


#### Arguments
* $products **mixed**



### <a name="method-getWsCartRows"></a>getWsCartRows

```php
mixed CartCore::getWsCartRows()
```





* Visibility: **public**
* Source: [classes/Cart.php line 3258](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L3258)




### <a name="method-intifier"></a>intifier

```php
integer CartCore::intifier($string, $delimiter)
```

Translate a string option_delivery identifier ('24,3,') in a int (3240002000)

The  option_delivery identifier is a list of integers separated by a ','.
This method replace the delimiter by a sequence of '0'.
The size of this sequence is fixed by the first digit of the return

* Visibility: **public**
* This method is **static**.
* Source: [classes/Cart.php line 2273](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L2273)


#### Arguments
* $string **mixed**
* $delimiter **mixed**



### <a name="method-isAllProductsInStock"></a>isAllProductsInStock

```php
boolean CartCore::isAllProductsInStock(boolean $ignore_virtual, boolean $exclusive)
```





* Visibility: **public**
* Source: [classes/Cart.php line 3632](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L3632)


#### Arguments
* $ignore_virtual **boolean** - Ignore virtual product
* $exclusive **boolean** - If true, the validation is exclusive : it must be present product in stock and out of stock



### <a name="method-isCarrierInRange"></a>isCarrierInRange

```php
mixed CartCore::isCarrierInRange($id_carrier, $id_zone)
```

isCarrierInRange

Check if the specified carrier is in range

* Visibility: **public**
* Source: [classes/Cart.php line 3592](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L3592)


#### Arguments
* $id_carrier **mixed**
* $id_zone **mixed**



### <a name="method-isGuestCartByCartId"></a>isGuestCartByCartId

```php
boolean CartCore::isGuestCartByCartId(integer $id_cart)
```

isGuestCartByCartId



* Visibility: **public**
* This method is **static**.
* Source: [classes/Cart.php line 3573](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L3573)


#### Arguments
* $id_cart **integer**



### <a name="method-isMultiAddressDelivery"></a>isMultiAddressDelivery

```php
boolean CartCore::isMultiAddressDelivery()
```

Does the cart use multiple address



* Visibility: **public**
* Source: [classes/Cart.php line 2295](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L2295)




### <a name="method-isVirtualCart"></a>isVirtualCart

```php
boolean CartCore::isVirtualCart($strict)
```

Check if cart contains only virtual products



* Visibility: **public**
* Source: [classes/Cart.php line 3028](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L3028)


#### Arguments
* $strict **mixed**



### <a name="method-lastNoneOrderedCart"></a>lastNoneOrderedCart

```php
mixed CartCore::lastNoneOrderedCart($id_customer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Cart.php line 3008](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L3008)


#### Arguments
* $id_customer **mixed**



### <a name="method-nbProducts"></a>nbProducts

```php
mixed CartCore::nbProducts()
```

Return cart products quantity



* Visibility: **public**
* Source: [classes/Cart.php line 743](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L743)




### <a name="method-orderExists"></a>orderExists

```php
boolean CartCore::orderExists()
```

Check if order has already been placed



* Visibility: **public**
* Source: [classes/Cart.php line 1108](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L1108)




### <a name="method-removeCartRule"></a>removeCartRule

```php
mixed CartCore::removeCartRule($id_cart_rule)
```





* Visibility: **public**
* Source: [classes/Cart.php line 1128](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L1128)


#### Arguments
* $id_cart_rule **mixed**



### <a name="method-replaceZeroByShopName"></a>replaceZeroByShopName

```php
mixed CartCore::replaceZeroByShopName($echo, $tr)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Cart.php line 3173](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L3173)


#### Arguments
* $echo **mixed**
* $tr **mixed**



### <a name="method-setDeliveryOption"></a>setDeliveryOption

```php
mixed CartCore::setDeliveryOption($delivery_option)
```

Set the delivery option and id_carrier, if there is only one carrier



* Visibility: **public**
* Source: [classes/Cart.php line 2340](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L2340)


#### Arguments
* $delivery_option **mixed**



### <a name="method-setNoMultishipping"></a>setNoMultishipping

```php
mixed CartCore::setNoMultishipping()
```

Update products cart address delivery with the address delivery of the cart



* Visibility: **public**
* Source: [classes/Cart.php line 3460](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L3460)




### <a name="method-setProductAddressDelivery"></a>setProductAddressDelivery

```php
mixed CartCore::setProductAddressDelivery($id_product, $id_product_attribute, $old_id_address_delivery, $new_id_address_delivery)
```





* Visibility: **public**
* Source: [classes/Cart.php line 3285](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L3285)


#### Arguments
* $id_product **mixed**
* $id_product_attribute **mixed**
* $old_id_address_delivery **mixed**
* $new_id_address_delivery **mixed**



### <a name="method-setWsCartRows"></a>setWsCartRows

```php
mixed CartCore::setWsCartRows($values)
```





* Visibility: **public**
* Source: [classes/Cart.php line 3267](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L3267)


#### Arguments
* $values **mixed**



### <a name="method-simulateCarrierSelectedOutput"></a>simulateCarrierSelectedOutput

```php
mixed CartCore::simulateCarrierSelectedOutput()
```





* Visibility: **public**
* Source: [classes/Cart.php line 2254](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L2254)




### <a name="method-simulateCarriersOutput"></a>simulateCarriersOutput

```php
mixed CartCore::simulateCarriersOutput(\Country $default_country, boolean $flush)
```

Get all deliveries options available for the current cart formated like Carriers::getCarriersForOrder
This method was wrote for retrocompatibility with 1.4 theme
New theme need to use Cart::getDeliveryOptionList() to generate carriers option in the checkout process



* Visibility: **public**
* Source: [classes/Cart.php line 2206](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L2206)


#### Arguments
* $default_country **[Country](class.CountryCore.md)**
* $flush **boolean** - Force flushing cache



### <a name="method-sortDeliveryOptionList"></a>sortDeliveryOptionList

```php
integer CartCore::sortDeliveryOptionList($option1, $option2)
```

Sort list of option delivery by parameters define in the BO



* Visibility: **public**
* This method is **static**.
* Source: [classes/Cart.php line 2157](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L2157)


#### Arguments
* $option1 **mixed**
* $option2 **mixed**



### <a name="method-update"></a>update

```php
mixed CartCore::update($null_values)
```





* Visibility: **public**
* Source: [classes/Cart.php line 190](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L190)


#### Arguments
* $null_values **mixed**



### <a name="method-updateAddressId"></a>updateAddressId

```php
mixed CartCore::updateAddressId(integer $id_address, integer $id_address_new)
```

Update the address id of the cart



* Visibility: **public**
* Source: [classes/Cart.php line 211](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L211)


#### Arguments
* $id_address **integer** - Current address id to change
* $id_address_new **integer** - New address id



### <a name="method-updateQty"></a>updateQty

```php
mixed CartCore::updateQty(integer $quantity, integer $id_product, integer $id_product_attribute, $id_customization, string $operator, $id_address_delivery, \Shop $shop, $auto_add_cart_rule)
```

Update product quantity



* Visibility: **public**
* Source: [classes/Cart.php line 836](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Cart.php#L836)


#### Arguments
* $quantity **integer** - Quantity to add (or substract)
* $id_product **integer** - Product ID
* $id_product_attribute **integer** - Attribute ID if needed
* $id_customization **mixed**
* $operator **string** - Indicate if quantity must be increased or decreased
* $id_address_delivery **mixed**
* $shop **[Shop](class.ShopCore.md)**
* $auto_add_cart_rule **mixed**


