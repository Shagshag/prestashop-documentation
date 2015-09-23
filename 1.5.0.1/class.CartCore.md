Class CartCore
=====================





* Class name: CartCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Cart.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L28)


Contents
--------

### Constants

* [BOTH](#constant-BOTH)
* [BOTH_WITHOUT_SHIPPING](#constant-BOTH_WITHOUT_SHIPPING)
* [ONLY_DISCOUNTS](#constant-ONLY_DISCOUNTS)
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
* [$delivery_option](#property-$delivery_option)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsValidate](#property-$fieldsValidate)
* [$gift](#property-$gift)
* [$gift_message](#property-$gift_message)
* [$id](#property-$id)
* [$id_address_delivery](#property-$id_address_delivery)
* [$id_address_invoice](#property-$id_address_invoice)
* [$id_carrier](#property-$id_carrier)
* [$id_currency](#property-$id_currency)
* [$id_customer](#property-$id_customer)
* [$id_group_shop](#property-$id_group_shop)
* [$id_guest](#property-$id_guest)
* [$id_lang](#property-$id_lang)
* [$id_shop](#property-$id_shop)
* [$identifier](#property-$identifier)
* [$pictures](#property-$pictures)
* [$recyclable](#property-$recyclable)
* [$secure_key](#property-$secure_key)
* [$table](#property-$table)
* [$textFields](#property-$textFields)
* [$webserviceParameters](#property-$webserviceParameters)
* [$_cache](#property-$_cache)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$langMultiShop](#property-$langMultiShop)
* [$tables](#property-$tables)

### Methods

* [__construct](#method-__construct)
* [_addCustomization](#method-_addCustomization)
* [_deleteCustomization](#method-_deleteCustomization)
* [_updateCustomizationQuantity](#method-_updateCustomizationQuantity)
* [add](#method-add)
* [addCartRule](#method-addCartRule)
* [addDiscount](#method-addDiscount)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [addPictureToProduct](#method-addPictureToProduct)
* [addTextFieldToProduct](#method-addTextFieldToProduct)
* [associateTo](#method-associateTo)
* [autosetProductAddress](#method-autosetProductAddress)
* [cacheSomeAttributesLists](#method-cacheSomeAttributesLists)
* [checkDiscountValidity](#method-checkDiscountValidity)
* [checkQuantities](#method-checkQuantities)
* [clearCache](#method-clearCache)
* [containsProduct](#method-containsProduct)
* [delete](#method-delete)
* [deleteAssociations](#method-deleteAssociations)
* [deleteCustomizationToProduct](#method-deleteCustomizationToProduct)
* [deleteDiscount](#method-deleteDiscount)
* [deleteImage](#method-deleteImage)
* [deleteProduct](#method-deleteProduct)
* [deleteSelection](#method-deleteSelection)
* [displayFieldName](#method-displayFieldName)
* [duplicate](#method-duplicate)
* [duplicateProduct](#method-duplicateProduct)
* [duplicateShops](#method-duplicateShops)
* [existsInDatabase](#method-existsInDatabase)
* [getAddressCollection](#method-getAddressCollection)
* [getCartByOrderId](#method-getCartByOrderId)
* [getCartIdByOrderId](#method-getCartIdByOrderId)
* [getCartRules](#method-getCartRules)
* [getCustomerCarts](#method-getCustomerCarts)
* [getDeliveryOption](#method-getDeliveryOption)
* [getDeliveryOptionList](#method-getDeliveryOptionList)
* [getDiscounts](#method-getDiscounts)
* [getDiscountsCustomer](#method-getDiscountsCustomer)
* [getFields](#method-getFields)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFieldsValidateLang](#method-getFieldsValidateLang)
* [getIdCarrierFromDeliveryOption](#method-getIdCarrierFromDeliveryOption)
* [getIdentifier](#method-getIdentifier)
* [getLastProduct](#method-getLastProduct)
* [getNbProducts](#method-getNbProducts)
* [getOrderShippingCost](#method-getOrderShippingCost)
* [getOrderTotal](#method-getOrderTotal)
* [getOrderTotalUsingTaxCalculationMethod](#method-getOrderTotalUsingTaxCalculationMethod)
* [getPackageList](#method-getPackageList)
* [getPackageShippingCost](#method-getPackageShippingCost)
* [getProductCustomization](#method-getProductCustomization)
* [getProducts](#method-getProducts)
* [getSummaryDetails](#method-getSummaryDetails)
* [getTaxesAverageUsed](#method-getTaxesAverageUsed)
* [getTotalCart](#method-getTotalCart)
* [getTotalShippingCost](#method-getTotalShippingCost)
* [getTotalWeight](#method-getTotalWeight)
* [getTranslationsFields](#method-getTranslationsFields)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [getWsCartRows](#method-getWsCartRows)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [isAssociatedToGroupShop](#method-isAssociatedToGroupShop)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCarrierInRange](#method-isCarrierInRange)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isGuestCartByCartId](#method-isGuestCartByCartId)
* [isLangMultishop](#method-isLangMultishop)
* [isMultiAddressDelivery](#method-isMultiAddressDelivery)
* [isVirtualCart](#method-isVirtualCart)
* [lastNoneOrderedCart](#method-lastNoneOrderedCart)
* [makeTranslationFields](#method-makeTranslationFields)
* [nbProducts](#method-nbProducts)
* [orderExists](#method-orderExists)
* [removeCartRule](#method-removeCartRule)
* [replaceZeroByShopName](#method-replaceZeroByShopName)
* [save](#method-save)
* [setDeliveryOption](#method-setDeliveryOption)
* [setNoMultishipping](#method-setNoMultishipping)
* [setProductAddressDelivery](#method-setProductAddressDelivery)
* [setWsCartRows](#method-setWsCartRows)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [updateQty](#method-updateQty)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)


Constants
----------


### <a name="constant-BOTH"></a>BOTH

```php
const BOTH = 3
```





* Source: [classes/Cart.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L123).


### <a name="constant-BOTH_WITHOUT_SHIPPING"></a>BOTH_WITHOUT_SHIPPING

```php
const BOTH_WITHOUT_SHIPPING = 4
```





* Source: [classes/Cart.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L124).


### <a name="constant-ONLY_DISCOUNTS"></a>ONLY_DISCOUNTS

```php
const ONLY_DISCOUNTS = 2
```





* Source: [classes/Cart.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L122).


### <a name="constant-ONLY_PRODUCTS"></a>ONLY_PRODUCTS

```php
const ONLY_PRODUCTS = 1
```





* Source: [classes/Cart.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L121).


### <a name="constant-ONLY_PRODUCTS_WITHOUT_SHIPPING"></a>ONLY_PRODUCTS_WITHOUT_SHIPPING

```php
const ONLY_PRODUCTS_WITHOUT_SHIPPING = 7
```





* Source: [classes/Cart.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L127).


### <a name="constant-ONLY_SHIPPING"></a>ONLY_SHIPPING

```php
const ONLY_SHIPPING = 5
```





* Source: [classes/Cart.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L125).


### <a name="constant-ONLY_WRAPPING"></a>ONLY_WRAPPING

```php
const ONLY_WRAPPING = 6
```





* Source: [classes/Cart.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L126).


Properties
----------


### <a name="property-$_attributesLists"></a>$_attributesLists

```php
protected mixed $_attributesLists = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Cart.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L98).


### <a name="property-$_carriers"></a>$_carriers

```php
protected mixed $_carriers = null
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Cart.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L96).


### <a name="property-$_isVirtualCart"></a>$_isVirtualCart

```php
protected mixed $_isVirtualCart = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Cart.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L85).


### <a name="property-$_nbProducts"></a>$_nbProducts

```php
protected mixed $_nbProducts = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Cart.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L84).


### <a name="property-$_products"></a>$_products

```php
protected mixed $_products = null
```





* Visibility: **protected**
* Source: [classes/Cart.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L93).


### <a name="property-$_taxCalculationMethod"></a>$_taxCalculationMethod

```php
protected mixed $_taxCalculationMethod = PS_TAX_EXC
```





* Visibility: **protected**
* Source: [classes/Cart.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L95).


### <a name="property-$_taxes_rate"></a>$_taxes_rate

```php
protected mixed $_taxes_rate = null
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Cart.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L97).


### <a name="property-$_totalWeight"></a>$_totalWeight

```php
protected mixed $_totalWeight = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Cart.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L94).


### <a name="property-$allow_seperated_package"></a>$allow_seperated_package

```php
public boolean $allow_seperated_package = false
```





* Visibility: **public**
* Source: [classes/Cart.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L82).


### <a name="property-$checkedTos"></a>$checkedTos

```php
public mixed $checkedTos = false
```





* Visibility: **public**
* Source: [classes/Cart.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L75).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/Cart.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L64).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* Source: [classes/Cart.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L73).


### <a name="property-$delivery_option"></a>$delivery_option

```php
public mixed $delivery_option
```





* Visibility: **public**
* Source: [classes/Cart.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L79).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array('id_currency', 'id_lang')
```





* Visibility: **protected**
* Source: [classes/Cart.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L87).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array('id_address_delivery' => 'isUnsignedId', 'id_carrier' => 'isUnsignedId', 'id_address_invoice' => 'isUnsignedId', 'id_currency' => 'isUnsignedId', 'id_customer' => 'isUnsignedId', 'id_guest' => 'isUnsignedId', 'id_lang' => 'isUnsignedId', 'recyclable' => 'isBool', 'gift' => 'isBool', 'gift_message' => 'isMessage', 'allow_seperated_package' => 'isBool')
```





* Visibility: **protected**
* Source: [classes/Cart.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L88).


### <a name="property-$gift"></a>$gift

```php
public boolean $gift
```





* Visibility: **public**
* Source: [classes/Cart.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L58).


### <a name="property-$gift_message"></a>$gift_message

```php
public string $gift_message
```





* Visibility: **public**
* Source: [classes/Cart.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L61).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/Cart.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L30).


### <a name="property-$id_address_delivery"></a>$id_address_delivery

```php
public integer $id_address_delivery
```





* Visibility: **public**
* Source: [classes/Cart.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L37).


### <a name="property-$id_address_invoice"></a>$id_address_invoice

```php
public integer $id_address_invoice
```





* Visibility: **public**
* Source: [classes/Cart.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L40).


### <a name="property-$id_carrier"></a>$id_carrier

```php
public mixed $id_carrier
```





* Visibility: **public**
* Source: [classes/Cart.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L70).


### <a name="property-$id_currency"></a>$id_currency

```php
public integer $id_currency
```





* Visibility: **public**
* Source: [classes/Cart.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L43).


### <a name="property-$id_customer"></a>$id_customer

```php
public integer $id_customer
```





* Visibility: **public**
* Source: [classes/Cart.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L46).


### <a name="property-$id_group_shop"></a>$id_group_shop

```php
public mixed $id_group_shop
```





* Visibility: **public**
* Source: [classes/Cart.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L32).


### <a name="property-$id_guest"></a>$id_guest

```php
public integer $id_guest
```





* Visibility: **public**
* Source: [classes/Cart.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L49).


### <a name="property-$id_lang"></a>$id_lang

```php
public integer $id_lang
```





* Visibility: **public**
* Source: [classes/Cart.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L52).


### <a name="property-$id_shop"></a>$id_shop

```php
public mixed $id_shop
```





* Visibility: **public**
* Source: [classes/Cart.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L34).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier = 'id_cart'
```





* Visibility: **protected**
* Source: [classes/Cart.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L100).


### <a name="property-$pictures"></a>$pictures

```php
public mixed $pictures
```





* Visibility: **public**
* Source: [classes/Cart.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L76).


### <a name="property-$recyclable"></a>$recyclable

```php
public boolean $recyclable = 1
```





* Visibility: **public**
* Source: [classes/Cart.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L55).


### <a name="property-$secure_key"></a>$secure_key

```php
public string $secure_key
```





* Visibility: **public**
* Source: [classes/Cart.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L67).


### <a name="property-$table"></a>$table

```php
protected mixed $table = 'cart'
```





* Visibility: **protected**
* Source: [classes/Cart.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L99).


### <a name="property-$textFields"></a>$textFields

```php
public mixed $textFields
```





* Visibility: **public**
* Source: [classes/Cart.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L77).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_address_delivery' => array('xlink_resource' => 'addresses'), 'id_address_invoice' => array('xlink_resource' => 'addresses'), 'id_currency' => array('xlink_resource' => 'currencies'), 'id_customer' => array('xlink_resource' => 'customers'), 'id_guest' => array('xlink_resource' => 'guests'), 'id_lang' => array('xlink_resource' => 'languages')), 'associations' => array('cart_rows' => array('resource' => 'cart_row', 'virtual_entity' => true, 'fields' => array('id_product' => array('required' => true, 'xlink_resource' => 'products'), 'id_product_attribute' => array('required' => true, 'xlink_resource' => 'combinations'), 'quantity' => array('required' => true)))))
```





* Visibility: **protected**
* Source: [classes/Cart.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L102).


### <a name="property-$_cache"></a>$_cache

```php
protected mixed $_cache = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L75).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected \fieldsRequiredDatabase $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L50).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected array $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L59).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected array $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L53).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected array $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L62).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected array $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L65).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L78).


### <a name="property-$image_format"></a>$image_format

```php
protected string $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L81).


### <a name="property-$langMultiShop"></a>$langMultiShop

```php
protected mixed $langMultiShop = false
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L67).


### <a name="property-$tables"></a>$tables

```php
protected array $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L70).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed CartCore::__construct($id, $id_lang)
```





* Visibility: **public**
* Source: [classes/Cart.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L155)


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### <a name="method-_addCustomization"></a>_addCustomization

```php
boolean CartCore::_addCustomization(integer $id_product, integer $id_product_attribute, integer $index, integer $type, string $field, integer $quantity)
```

Add customization item to database



* Visibility: **public**
* Source: [classes/Cart.php line 759](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L759)


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
* Source: [classes/Cart.php line 899](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L899)


#### Arguments
* $id_customization **integer**
* $id_product **mixed**
* $id_product_attribute **mixed**
* $id_address_delivery **mixed**



### <a name="method-_updateCustomizationQuantity"></a>_updateCustomizationQuantity

```php
mixed CartCore::_updateCustomizationQuantity($quantity, $id_customization, $id_product, $id_product_attribute, $operator)
```





* Visibility: **protected**
* Source: [classes/Cart.php line 705](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L705)


#### Arguments
* $quantity **mixed**
* $id_customization **mixed**
* $id_product **mixed**
* $id_product_attribute **mixed**
* $operator **mixed**



### <a name="method-add"></a>add

```php
mixed CartCore::add($autodate, $nullValues)
```





* Visibility: **public**
* Source: [classes/Cart.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L173)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### <a name="method-addCartRule"></a>addCartRule

```php
mixed CartCore::addCartRule($id_cart_rule)
```





* Visibility: **public**
* Source: [classes/Cart.php line 565](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L565)


#### Arguments
* $id_cart_rule **mixed**



### <a name="method-addDiscount"></a>addDiscount

```php
mixed CartCore::addDiscount($id_cart_rule)
```





* Visibility: **public**
* Source: [classes/Cart.php line 559](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L559)


#### Arguments
* $id_cart_rule **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 780](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L780)


#### Arguments
* $fields **mixed**



### <a name="method-addPictureToProduct"></a>addPictureToProduct

```php
mixed CartCore::addPictureToProduct($id_product, $index, $type, $file)
```





* Visibility: **public**
* Source: [classes/Cart.php line 2040](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L2040)


#### Arguments
* $id_product **mixed**
* $index **mixed**
* $type **mixed**
* $file **mixed**



### <a name="method-addTextFieldToProduct"></a>addTextFieldToProduct

```php
mixed CartCore::addTextFieldToProduct($id_product, $index, $type, $textValue)
```





* Visibility: **public**
* Source: [classes/Cart.php line 2027](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L2027)


#### Arguments
* $id_product **mixed**
* $index **mixed**
* $type **mixed**
* $textValue **mixed**



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops, string $type)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 828](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L828)


#### Arguments
* $id_shops **integer|array**
* $type **string**



### <a name="method-autosetProductAddress"></a>autosetProductAddress

```php
mixed CartCore::autosetProductAddress()
```

Set an address to all products on the cart without address delivery



* Visibility: **public**
* Source: [classes/Cart.php line 2414](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L2414)




### <a name="method-cacheSomeAttributesLists"></a>cacheSomeAttributesLists

```php
mixed CartCore::cacheSomeAttributesLists($ipaList, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Cart.php line 495](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L495)


#### Arguments
* $ipaList **mixed**
* $id_lang **mixed**



### <a name="method-checkDiscountValidity"></a>checkDiscountValidity

```php
mixed CartCore::checkDiscountValidity($obj, $discounts, $order_total, $products, $checkCartDiscount)
```





* Visibility: **public**
* Source: [classes/Cart.php line 1901](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L1901)


#### Arguments
* $obj **mixed**
* $discounts **mixed**
* $order_total **mixed**
* $products **mixed**
* $checkCartDiscount **mixed**



### <a name="method-checkQuantities"></a>checkQuantities

```php
mixed CartCore::checkQuantities()
```





* Visibility: **public**
* Source: [classes/Cart.php line 1954](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L1954)




### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 794](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L794)


#### Arguments
* $all **mixed**



### <a name="method-containsProduct"></a>containsProduct

```php
mixed CartCore::containsProduct($id_product, $id_product_attribute, $id_customization, $id_address_delivery)
```





* Visibility: **public**
* Source: [classes/Cart.php line 570](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L570)


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
* Source: [classes/Cart.php line 194](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L194)




### <a name="method-deleteAssociations"></a>deleteAssociations

```php
mixed CartCore::deleteAssociations()
```





* Visibility: **public**
* Source: [classes/Cart.php line 2448](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L2448)




### <a name="method-deleteCustomizationToProduct"></a>deleteCustomizationToProduct

```php
mixed CartCore::deleteCustomizationToProduct($id_product, $index)
```





* Visibility: **public**
* Source: [classes/Cart.php line 2050](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L2050)


#### Arguments
* $id_product **mixed**
* $index **mixed**



### <a name="method-deleteDiscount"></a>deleteDiscount

```php
mixed CartCore::deleteDiscount($id_cart_rule)
```





* Visibility: **public**
* Source: [classes/Cart.php line 817](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L817)


#### Arguments
* $id_cart_rule **mixed**



### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage()
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 898](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L898)




### <a name="method-deleteProduct"></a>deleteProduct

```php
boolean CartCore::deleteProduct(integer $id_product, integer $id_product_attribute, integer $id_customization, $id_address_delivery)
```

Delete a product from the cart



* Visibility: **public**
* Source: [classes/Cart.php line 836](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L836)


#### Arguments
* $id_product **integer** - Product ID
* $id_product_attribute **integer** - Attribute ID if needed
* $id_customization **integer** - Customization id
* $id_address_delivery **mixed**



### <a name="method-deleteSelection"></a>deleteSelection

```php
mixed ObjectModelCore::deleteSelection($selection)
```

Delete several objects from database

return boolean Deletion result

* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 387](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L387)


#### Arguments
* $selection **mixed**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $className, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 558](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L558)


#### Arguments
* $field **mixed**
* $className **mixed**
* $htmlentities **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-duplicate"></a>duplicate

```php
mixed CartCore::duplicate()
```





* Visibility: **public**
* Source: [classes/Cart.php line 2116](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L2116)




### <a name="method-duplicateProduct"></a>duplicateProduct

```php
mixed CartCore::duplicateProduct($id_product, $id_product_attribute, $id_address_delivery, $new_id_address_delivery, $quantity, $keep_quantity)
```





* Visibility: **public**
* Source: [classes/Cart.php line 2264](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L2264)


#### Arguments
* $id_product **mixed**
* $id_product_attribute **mixed**
* $id_address_delivery **mixed**
* $new_id_address_delivery **mixed**
* $quantity **mixed**
* $keep_quantity **mixed**



### <a name="method-duplicateShops"></a>duplicateShops

```php
mixed ObjectModelCore::duplicateShops($id)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 868](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L868)


#### Arguments
* $id **mixed**



### <a name="method-existsInDatabase"></a>existsInDatabase

```php
boolean ObjectModelCore::existsInDatabase($id_entity, $table)
```

Specify if an ObjectModel is already in database



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 931](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L931)


#### Arguments
* $id_entity **mixed** - entity id
* $table **mixed**



### <a name="method-getAddressCollection"></a>getAddressCollection

```php
mixed CartCore::getAddressCollection()
```

Get all delivery addresses object for the current cart



* Visibility: **public**
* Source: [classes/Cart.php line 1503](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L1503)




### <a name="method-getCartByOrderId"></a>getCartByOrderId

```php
mixed CartCore::getCartByOrderId($id_order)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Cart.php line 2006](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L2006)


#### Arguments
* $id_order **mixed**



### <a name="method-getCartIdByOrderId"></a>getCartIdByOrderId

```php
mixed CartCore::getCartIdByOrderId($id_order)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Cart.php line 2014](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L2014)


#### Arguments
* $id_order **mixed**



### <a name="method-getCartRules"></a>getCartRules

```php
mixed CartCore::getCartRules()
```





* Visibility: **public**
* Source: [classes/Cart.php line 268](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L268)




### <a name="method-getCustomerCarts"></a>getCustomerCarts

```php
mixed CartCore::getCustomerCarts($id_customer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Cart.php line 2101](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L2101)


#### Arguments
* $id_customer **mixed**



### <a name="method-getDeliveryOption"></a>getDeliveryOption

```php
array CartCore::getDeliveryOption($default_country)
```

Get the delivery option seleted, or if no delivery option was selected, the cheapest option for each address



* Visibility: **public**
* Source: [classes/Cart.php line 1548](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L1548)


#### Arguments
* $default_country **mixed**



### <a name="method-getDeliveryOptionList"></a>getDeliveryOptionList

```php
array CartCore::getDeliveryOptionList(\Country $default_country)
```

Get all deliveries options available for the current cart



* Visibility: **public**
* Source: [classes/Cart.php line 1323](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L1323)


#### Arguments
* $default_country **[Country](class.CountryCore.md)**



### <a name="method-getDiscounts"></a>getDiscounts

```php
mixed CartCore::getDiscounts($lite, $refresh)
```





* Visibility: **public**
* Source: [classes/Cart.php line 262](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L262)


#### Arguments
* $lite **mixed**
* $refresh **mixed**



### <a name="method-getDiscountsCustomer"></a>getDiscountsCustomer

```php
mixed CartCore::getDiscountsCustomer($id_cart_rule)
```





* Visibility: **public**
* Source: [classes/Cart.php line 303](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L303)


#### Arguments
* $id_cart_rule **mixed**



### <a name="method-getFields"></a>getFields

```php
mixed CartCore::getFields()
```





* Visibility: **public**
* Source: [classes/Cart.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L129)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 772](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L772)


#### Arguments
* $all **mixed**



### <a name="method-getFieldsValidateLang"></a>getFieldsValidateLang

```php
array ObjectModelCore::getFieldsValidateLang()
```

Get list of fields related to language to validate



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 975](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L975)




### <a name="method-getIdCarrierFromDeliveryOption"></a>getIdCarrierFromDeliveryOption

```php
mixed CartCore::getIdCarrierFromDeliveryOption($delivery_option)
```





* Visibility: **private**
* Source: [classes/Cart.php line 1534](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L1534)


#### Arguments
* $delivery_option **mixed**



### <a name="method-getIdentifier"></a>getIdentifier

```php
string ObjectModelCore::getIdentifier()
```

Get object identifier name



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 964](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L964)




### <a name="method-getLastProduct"></a>getLastProduct

```php
mixed CartCore::getLastProduct()
```





* Visibility: **public**
* Source: [classes/Cart.php line 314](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L314)




### <a name="method-getNbProducts"></a>getNbProducts

```php
mixed CartCore::getNbProducts($id)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Cart.php line 544](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L544)


#### Arguments
* $id **mixed**



### <a name="method-getOrderShippingCost"></a>getOrderShippingCost

```php
float CartCore::getOrderShippingCost(integer $id_carrier, \booleal $useTax, \Country $default_country, Array $product_list)
```

Return shipping total
This function is dépreciate, use getTotalShippingCost or getPackageShippingCost



* Visibility: **public**
* Source: [classes/Cart.php line 1606](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L1606)


#### Arguments
* $id_carrier **integer** - Carrier ID (default : current carrier)
* $useTax **booleal**
* $default_country **[Country](class.CountryCore.md)**
* $product_list **Array**



### <a name="method-getOrderTotal"></a>getOrderTotal

```php
float CartCore::getOrderTotal(boolean $withTaxes, integer $type, $products, $id_carrier)
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

* Visibility: **public**
* Source: [classes/Cart.php line 970](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L970)


#### Arguments
* $withTaxes **boolean** - With or without taxes
* $type **integer** - Total type
* $products **mixed**
* $id_carrier **mixed**



### <a name="method-getOrderTotalUsingTaxCalculationMethod"></a>getOrderTotalUsingTaxCalculationMethod

```php
mixed CartCore::getOrderTotalUsingTaxCalculationMethod($id_cart)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Cart.php line 949](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L949)


#### Arguments
* $id_cart **mixed**



### <a name="method-getPackageList"></a>getPackageList

```php
array CartCore::getPackageList()
```

Get products grouped by package and by addresses to be sent individualy (one package = one shipping cost).



* Visibility: **public**
* Source: [classes/Cart.php line 1087](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L1087)




### <a name="method-getPackageShippingCost"></a>getPackageShippingCost

```php
float CartCore::getPackageShippingCost(integer $id_carrier, \booleal $useTax, \Country $default_country, Array $product_list)
```

Return package shipping cost



* Visibility: **public**
* Source: [classes/Cart.php line 1622](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L1622)


#### Arguments
* $id_carrier **integer** - Carrier ID (default : current carrier)
* $useTax **booleal**
* $default_country **[Country](class.CountryCore.md)**
* $product_list **Array**



### <a name="method-getProductCustomization"></a>getProductCustomization

```php
array CartCore::getProductCustomization(integer $id_product, integer $type, boolean $not_in_cart)
```

Return custom pictures in this cart for a specified product



* Visibility: **public**
* Source: [classes/Cart.php line 2084](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L2084)


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
* Source: [classes/Cart.php line 334](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L334)


#### Arguments
* $refresh **mixed**
* $id_product **mixed**
* $id_country **mixed**



### <a name="method-getSummaryDetails"></a>getSummaryDetails

```php
array CartCore::getSummaryDetails($id_lang)
```

Return useful informations for cart



* Visibility: **public**
* Source: [classes/Cart.php line 1914](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L1914)


#### Arguments
* $id_lang **mixed**



### <a name="method-getTaxesAverageUsed"></a>getTaxesAverageUsed

```php
mixed CartCore::getTaxesAverageUsed($id_cart)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Cart.php line 230](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L230)


#### Arguments
* $id_cart **mixed**



### <a name="method-getTotalCart"></a>getTotalCart

```php
mixed CartCore::getTotalCart($id_cart, $use_tax_display)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Cart.php line 939](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L939)


#### Arguments
* $id_cart **mixed**
* $use_tax_display **mixed**



### <a name="method-getTotalShippingCost"></a>getTotalShippingCost

```php
float CartCore::getTotalShippingCost(array $delivery_option, \booleal $useTax, \Country $default_country)
```

Return shipping total for the cart



* Visibility: **public**
* Source: [classes/Cart.php line 1573](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L1573)


#### Arguments
* $delivery_option **array** - Array of the delivery option for each address
* $useTax **booleal**
* $default_country **[Country](class.CountryCore.md)**



### <a name="method-getTotalWeight"></a>getTotalWeight

```php
float CartCore::getTotalWeight($products)
```

Return cart weight



* Visibility: **public**
* Source: [classes/Cart.php line 1858](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L1858)


#### Arguments
* $products **mixed**



### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields(array $fieldsArray)
```

Prepare multilingual fields for database insertion



* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 430](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L430)


#### Arguments
* $fieldsArray **array** - Multilingual fields to prepare
return array Prepared fields for database insertion



### <a name="method-getValidationRules"></a>getValidationRules

```php
array ObjectModelCore::getValidationRules(string $className)
```

Returns object validation rules (fields validity)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L89)


#### Arguments
* $className **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed ObjectModelCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 747](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L747)


#### Arguments
* $sql_join **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**



### <a name="method-getWebserviceParameters"></a>getWebserviceParameters

```php
mixed ObjectModelCore::getWebserviceParameters($wsParamsAttributeName)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 617](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L617)


#### Arguments
* $wsParamsAttributeName **mixed**



### <a name="method-getWsCartRows"></a>getWsCartRows

```php
mixed CartCore::getWsCartRows()
```





* Visibility: **public**
* Source: [classes/Cart.php line 2180](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L2180)




### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 987](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L987)


#### Arguments
* $data **array**
* $id_lang **integer**



### <a name="method-hydrateCollection"></a>hydrateCollection

```php
array ObjectModelCore::hydrateCollection(string $class, array $datas, integer $id_lang)
```

Fill (hydrate) a list of objects in order to get a collection of these objects



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1006](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L1006)


#### Arguments
* $class **string** - Class of objects to hydrate
* $datas **array** - List of data (multi-dimensional array)
* $id_lang **integer**



### <a name="method-isAssociatedToGroupShop"></a>isAssociatedToGroupShop

```php
boolean ObjectModelCore::isAssociatedToGroupShop(integer $id_group_shop)
```

Check if current object is associated to a group shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 854](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L854)


#### Arguments
* $id_group_shop **integer**



### <a name="method-isAssociatedToShop"></a>isAssociatedToShop

```php
boolean ObjectModelCore::isAssociatedToShop(integer $id_shop)
```

Check if current object is associated to a shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 809](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L809)


#### Arguments
* $id_shop **integer**



### <a name="method-isCarrierInRange"></a>isCarrierInRange

```php
mixed CartCore::isCarrierInRange($id_carrier, $id_zone)
```

isCarrierInRange

Check if the specified carrier is in range

* Visibility: **public**
* Source: [classes/Cart.php line 2480](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L2480)


#### Arguments
* $id_carrier **mixed**
* $id_zone **mixed**



### <a name="method-isCurrentlyUsed"></a>isCurrentlyUsed

```php
boolean ObjectModelCore::isCurrentlyUsed(string $table, boolean $has_active_column)
```

This method is allow to know if a entity is currently used



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 948](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L948)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isGuestCartByCartId"></a>isGuestCartByCartId

```php
boolean CartCore::isGuestCartByCartId(integer $id_cart)
```

isGuestCartByCartId



* Visibility: **public**
* This method is **static**.
* Source: [classes/Cart.php line 2461](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L2461)


#### Arguments
* $id_cart **integer**



### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 888](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L888)




### <a name="method-isMultiAddressDelivery"></a>isMultiAddressDelivery

```php
mixed CartCore::isMultiAddressDelivery()
```

Does the cart use multiple



* Visibility: **public**
* Source: [classes/Cart.php line 1490](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L1490)




### <a name="method-isVirtualCart"></a>isVirtualCart

```php
boolean CartCore::isVirtualCart($strict)
```

Check if cart contains only virtual products



* Visibility: **public**
* Source: [classes/Cart.php line 1983](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L1983)


#### Arguments
* $strict **mixed**



### <a name="method-lastNoneOrderedCart"></a>lastNoneOrderedCart

```php
mixed CartCore::lastNoneOrderedCart($id_customer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Cart.php line 1964](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L1964)


#### Arguments
* $id_customer **mixed**



### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fieldsArray, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 447](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L447)


#### Arguments
* $fields **mixed**
* $fieldsArray **mixed**
* $id_language **mixed**



### <a name="method-nbProducts"></a>nbProducts

```php
mixed CartCore::nbProducts()
```

Return cart products quantity



* Visibility: **public**
* Source: [classes/Cart.php line 537](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L537)




### <a name="method-orderExists"></a>orderExists

```php
boolean CartCore::orderExists()
```

Check if order has already been placed



* Visibility: **public**
* Source: [classes/Cart.php line 809](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L809)




### <a name="method-removeCartRule"></a>removeCartRule

```php
mixed CartCore::removeCartRule($id_cart_rule)
```





* Visibility: **public**
* Source: [classes/Cart.php line 823](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L823)


#### Arguments
* $id_cart_rule **mixed**



### <a name="method-replaceZeroByShopName"></a>replaceZeroByShopName

```php
mixed CartCore::replaceZeroByShopName($echo, $tr)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Cart.php line 2111](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L2111)


#### Arguments
* $echo **mixed**
* $tr **mixed**



### <a name="method-save"></a>save

```php
mixed ObjectModelCore::save($nullValues, $autodate)
```

Save current object to database (add or update)

return boolean Insertion result

* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L192)


#### Arguments
* $nullValues **mixed**
* $autodate **mixed**



### <a name="method-setDeliveryOption"></a>setDeliveryOption

```php
mixed CartCore::setDeliveryOption($delivery_option)
```

Set the delivery option and id_carrier, if there is only one carrier



* Visibility: **public**
* Source: [classes/Cart.php line 1519](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L1519)


#### Arguments
* $delivery_option **mixed**



### <a name="method-setNoMultishipping"></a>setNoMultishipping

```php
mixed CartCore::setNoMultishipping()
```

Update products cart address delivery with the address delivery of the cart



* Visibility: **public**
* Source: [classes/Cart.php line 2354](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L2354)




### <a name="method-setProductAddressDelivery"></a>setProductAddressDelivery

```php
mixed CartCore::setProductAddressDelivery($id_product, $id_product_attribute, $old_id_address_delivery, $new_id_address_delivery)
```





* Visibility: **public**
* Source: [classes/Cart.php line 2201](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L2201)


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
* Source: [classes/Cart.php line 2189](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L2189)


#### Arguments
* $values **mixed**



### <a name="method-toggleStatus"></a>toggleStatus

```php
mixed ObjectModelCore::toggleStatus()
```

Toggle object status in database

return boolean Update result

* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 405](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L405)




### <a name="method-update"></a>update

```php
mixed CartCore::update($nullValues)
```





* Visibility: **public**
* Source: [classes/Cart.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L182)


#### Arguments
* $nullValues **mixed**



### <a name="method-updateQty"></a>updateQty

```php
mixed CartCore::updateQty(integer $quantity, integer $id_product, integer $id_product_attribute, $id_customization, $id_address_delivery, string $operator, \Shop $shop)
```

Update product quantity



* Visibility: **public**
* Source: [classes/Cart.php line 588](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Cart.php#L588)


#### Arguments
* $quantity **integer** - Quantity to add (or substract)
* $id_product **integer** - Product ID
* $id_product_attribute **integer** - Attribute ID if needed
* $id_customization **mixed**
* $id_address_delivery **mixed**
* $operator **string** - Indicate if quantity must be increased or decreased
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-validateControler"></a>validateControler

```php
mixed ObjectModelCore::validateControler($htmlentities)
```

TODO: refactor rename all calls to this to validateController



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 571](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L571)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 577](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L577)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateFields"></a>validateFields

```php
mixed ObjectModelCore::validateFields($die, $errorReturn)
```

Check for fields validity before database interaction



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 481](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L481)


#### Arguments
* $die **mixed**
* $errorReturn **mixed**



### <a name="method-validateFieldsLang"></a>validateFieldsLang

```php
mixed ObjectModelCore::validateFieldsLang($die, $errorReturn)
```

Check for multilingual fields validity before database interaction



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 514](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L514)


#### Arguments
* $die **mixed**
* $errorReturn **mixed**


