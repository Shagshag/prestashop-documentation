Class OrderCore
=====================





* Class name: OrderCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/order/Order.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L27)


Contents
--------

### Constants

* [ROUND_ITEM](#constant-ROUND_ITEM)
* [ROUND_LINE](#constant-ROUND_LINE)
* [ROUND_TOTAL](#constant-ROUND_TOTAL)

### Properties

* [$_historyCache](#property-$_historyCache)
* [$_taxCalculationMethod](#property-$_taxCalculationMethod)
* [$cacheCustomer](#property-$cacheCustomer)
* [$carrier_tax_rate](#property-$carrier_tax_rate)
* [$conversion_rate](#property-$conversion_rate)
* [$current_state](#property-$current_state)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$delivery_date](#property-$delivery_date)
* [$delivery_number](#property-$delivery_number)
* [$gift](#property-$gift)
* [$gift_message](#property-$gift_message)
* [$id_address_delivery](#property-$id_address_delivery)
* [$id_address_invoice](#property-$id_address_invoice)
* [$id_carrier](#property-$id_carrier)
* [$id_cart](#property-$id_cart)
* [$id_currency](#property-$id_currency)
* [$id_customer](#property-$id_customer)
* [$id_lang](#property-$id_lang)
* [$id_shop](#property-$id_shop)
* [$id_shop_group](#property-$id_shop_group)
* [$invoice_date](#property-$invoice_date)
* [$invoice_number](#property-$invoice_number)
* [$mobile_theme](#property-$mobile_theme)
* [$module](#property-$module)
* [$payment](#property-$payment)
* [$recyclable](#property-$recyclable)
* [$reference](#property-$reference)
* [$round_mode](#property-$round_mode)
* [$round_type](#property-$round_type)
* [$secure_key](#property-$secure_key)
* [$shipping_number](#property-$shipping_number)
* [$total_discounts](#property-$total_discounts)
* [$total_discounts_tax_excl](#property-$total_discounts_tax_excl)
* [$total_discounts_tax_incl](#property-$total_discounts_tax_incl)
* [$total_paid](#property-$total_paid)
* [$total_paid_real](#property-$total_paid_real)
* [$total_paid_tax_excl](#property-$total_paid_tax_excl)
* [$total_paid_tax_incl](#property-$total_paid_tax_incl)
* [$total_products](#property-$total_products)
* [$total_products_wt](#property-$total_products_wt)
* [$total_shipping](#property-$total_shipping)
* [$total_shipping_tax_excl](#property-$total_shipping_tax_excl)
* [$total_shipping_tax_incl](#property-$total_shipping_tax_incl)
* [$total_wrapping](#property-$total_wrapping)
* [$total_wrapping_tax_excl](#property-$total_wrapping_tax_excl)
* [$total_wrapping_tax_incl](#property-$total_wrapping_tax_incl)
* [$valid](#property-$valid)
* [$webserviceParameters](#property-$webserviceParameters)
* [$cache_objects](#property-$cache_objects)
* [$db](#property-$db)
* [$def](#property-$def)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidate](#property-$fieldsValidate)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$force_id](#property-$force_id)
* [$get_shop_from_context](#property-$get_shop_from_context)
* [$id](#property-$id)
* [$id_shop_list](#property-$id_shop_list)
* [$identifier](#property-$identifier)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$loaded_classes](#property-$loaded_classes)
* [$table](#property-$table)
* [$tables](#property-$tables)
* [$update_fields](#property-$update_fields)

### Methods

* [__construct](#method-__construct)
* [_deleteProduct](#method-_deleteProduct)
* [add](#method-add)
* [addCartRule](#method-addCartRule)
* [addDiscount](#method-addDiscount)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [addOrderPayment](#method-addOrderPayment)
* [addWs](#method-addWs)
* [associateTo](#method-associateTo)
* [cacheFieldsRequiredDatabase](#method-cacheFieldsRequiredDatabase)
* [clearCache](#method-clearCache)
* [delete](#method-delete)
* [deleteAssociations](#method-deleteAssociations)
* [deleteCustomization](#method-deleteCustomization)
* [deleteImage](#method-deleteImage)
* [deleteProduct](#method-deleteProduct)
* [deleteSelection](#method-deleteSelection)
* [disableCache](#method-disableCache)
* [displayFieldName](#method-displayFieldName)
* [duplicateObject](#method-duplicateObject)
* [duplicateShops](#method-duplicateShops)
* [enableCache](#method-enableCache)
* [existsInDatabase](#method-existsInDatabase)
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [generateReference](#method-generateReference)
* [getAssociatedShops](#method-getAssociatedShops)
* [getBrother](#method-getBrother)
* [getByDelivery](#method-getByDelivery)
* [getByReference](#method-getByReference)
* [getCartIdStatic](#method-getCartIdStatic)
* [getCartProducts](#method-getCartProducts)
* [getCartRules](#method-getCartRules)
* [getCurrentOrderState](#method-getCurrentOrderState)
* [getCurrentState](#method-getCurrentState)
* [getCurrentStateFull](#method-getCurrentStateFull)
* [getCustomer](#method-getCustomer)
* [getCustomerNbOrders](#method-getCustomerNbOrders)
* [getCustomerOrders](#method-getCustomerOrders)
* [getDefinition](#method-getDefinition)
* [getDeliveryNumber](#method-getDeliveryNumber)
* [getDeliverySlipsCollection](#method-getDeliverySlipsCollection)
* [getDiscounts](#method-getDiscounts)
* [getDiscountsCustomer](#method-getDiscountsCustomer)
* [getDocuments](#method-getDocuments)
* [getEcoTaxTaxesBreakdown](#method-getEcoTaxTaxesBreakdown)
* [getFieldByLang](#method-getFieldByLang)
* [getFields](#method-getFields)
* [getFieldsLang](#method-getFieldsLang)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFieldsShop](#method-getFieldsShop)
* [getFirstMessage](#method-getFirstMessage)
* [getHistory](#method-getHistory)
* [getIdOrderCarrier](#method-getIdOrderCarrier)
* [getIdOrderProduct](#method-getIdOrderProduct)
* [getInvoice](#method-getInvoice)
* [getInvoiceNumber](#method-getInvoiceNumber)
* [getInvoicesCollection](#method-getInvoicesCollection)
* [getLastInvoiceNumber](#method-getLastInvoiceNumber)
* [getNextOrderId](#method-getNextOrderId)
* [getNotPaidInvoicesCollection](#method-getNotPaidInvoicesCollection)
* [getNumberOfDays](#method-getNumberOfDays)
* [getOrderByCartId](#method-getOrderByCartId)
* [getOrderDetailList](#method-getOrderDetailList)
* [getOrderDetailTaxes](#method-getOrderDetailTaxes)
* [getOrderIdsByStatus](#method-getOrderIdsByStatus)
* [getOrderInvoiceIdIfHasDelivery](#method-getOrderInvoiceIdIfHasDelivery)
* [getOrderPaymentCollection](#method-getOrderPaymentCollection)
* [getOrderPayments](#method-getOrderPayments)
* [getOrderSlipsCollection](#method-getOrderSlipsCollection)
* [getOrdersIdByDate](#method-getOrdersIdByDate)
* [getOrdersIdInvoiceByDate](#method-getOrdersIdInvoiceByDate)
* [getOrdersTotalPaid](#method-getOrdersTotalPaid)
* [getOrdersWithInformations](#method-getOrdersWithInformations)
* [getPreviousOrderId](#method-getPreviousOrderId)
* [getProductTaxesBreakdown](#method-getProductTaxesBreakdown)
* [getProductTaxesDetails](#method-getProductTaxesDetails)
* [getProducts](#method-getProducts)
* [getProductsDetail](#method-getProductsDetail)
* [getRepositoryClassName](#method-getRepositoryClassName)
* [getReturn](#method-getReturn)
* [getShipping](#method-getShipping)
* [getShippingTaxesBreakdown](#method-getShippingTaxesBreakdown)
* [getTaxCalculationMethod](#method-getTaxCalculationMethod)
* [getTaxesAverageUsed](#method-getTaxesAverageUsed)
* [getTotalPaid](#method-getTotalPaid)
* [getTotalProductsWithTaxes](#method-getTotalProductsWithTaxes)
* [getTotalProductsWithoutTaxes](#method-getTotalProductsWithoutTaxes)
* [getTotalWeight](#method-getTotalWeight)
* [getTranslationsFields](#method-getTranslationsFields)
* [getUniqReference](#method-getUniqReference)
* [getUniqReferenceOf](#method-getUniqReferenceOf)
* [getValidationRules](#method-getValidationRules)
* [getVirtualProducts](#method-getVirtualProducts)
* [getWarehouseList](#method-getWarehouseList)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [getWrappingTaxesBreakdown](#method-getWrappingTaxesBreakdown)
* [getWsCurrentState](#method-getWsCurrentState)
* [getWsOrderRows](#method-getWsOrderRows)
* [getWsShippingNumber](#method-getWsShippingNumber)
* [hasBeenDelivered](#method-hasBeenDelivered)
* [hasBeenPaid](#method-hasBeenPaid)
* [hasBeenShipped](#method-hasBeenShipped)
* [hasDelivery](#method-hasDelivery)
* [hasInvoice](#method-hasInvoice)
* [hasMultishopEntries](#method-hasMultishopEntries)
* [hasProductReturned](#method-hasProductReturned)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [isAssociatedAtGuest](#method-isAssociatedAtGuest)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isInPreparation](#method-isInPreparation)
* [isLangMultishop](#method-isLangMultishop)
* [isMultiShopField](#method-isMultiShopField)
* [isMultishop](#method-isMultishop)
* [isPaidAndShipped](#method-isPaidAndShipped)
* [isReturnable](#method-isReturnable)
* [isVirtual](#method-isVirtual)
* [makeTranslationFields](#method-makeTranslationFields)
* [orderContainProduct](#method-orderContainProduct)
* [save](#method-save)
* [setCurrentState](#method-setCurrentState)
* [setDefinitionRetrocompatibility](#method-setDefinitionRetrocompatibility)
* [setDelivery](#method-setDelivery)
* [setDeliveryNumber](#method-setDeliveryNumber)
* [setDeliverySlip](#method-setDeliverySlip)
* [setFieldsToUpdate](#method-setFieldsToUpdate)
* [setInvoice](#method-setInvoice)
* [setInvoiceDetails](#method-setInvoiceDetails)
* [setLastInvoiceNumber](#method-setLastInvoiceNumber)
* [setProductCurrentStock](#method-setProductCurrentStock)
* [setProductCustomizedDatas](#method-setProductCustomizedDatas)
* [setProductImageInformations](#method-setProductImageInformations)
* [setProductPrices](#method-setProductPrices)
* [setWsCurrentState](#method-setWsCurrentState)
* [setWsShippingNumber](#method-setWsShippingNumber)
* [sortDocuments](#method-sortDocuments)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [updateMultishopTable](#method-updateMultishopTable)
* [updateOrderDetailTax](#method-updateOrderDetailTax)
* [updateShippingCost](#method-updateShippingCost)
* [useOneAfterAnotherTaxComputationMethod](#method-useOneAfterAnotherTaxComputationMethod)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateField](#method-validateField)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)
* [validateFieldsRequiredDatabase](#method-validateFieldsRequiredDatabase)


Constants
----------


### <a name="constant-ROUND_ITEM"></a>ROUND_ITEM

```php
const ROUND_ITEM = 1
```





* Source: [classes/order/Order.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L29).


### <a name="constant-ROUND_LINE"></a>ROUND_LINE

```php
const ROUND_LINE = 2
```





* Source: [classes/order/Order.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L30).


### <a name="constant-ROUND_TOTAL"></a>ROUND_TOTAL

```php
const ROUND_TOTAL = 3
```





* Source: [classes/order/Order.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L31).


Properties
----------


### <a name="property-$_historyCache"></a>$_historyCache

```php
protected mixed $_historyCache = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/order/Order.php line 279](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L279).


### <a name="property-$_taxCalculationMethod"></a>$_taxCalculationMethod

```php
protected mixed $_taxCalculationMethod = PS_TAX_EXC
```





* Visibility: **protected**
* Source: [classes/order/Order.php line 277](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L277).


### <a name="property-$cacheCustomer"></a>$cacheCustomer

```php
protected mixed $cacheCustomer = null
```

used to cache order customer



* Visibility: **protected**
* Source: [classes/order/Order.php line 1048](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1048).


### <a name="property-$carrier_tax_rate"></a>$carrier_tax_rate

```php
public float $carrier_tax_rate
```





* Visibility: **public**
* Source: [classes/order/Order.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L127).


### <a name="property-$conversion_rate"></a>$conversion_rate

```php
public float $conversion_rate
```





* Visibility: **public**
* Source: [classes/order/Order.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L72).


### <a name="property-$current_state"></a>$current_state

```php
public integer $current_state
```





* Visibility: **public**
* Source: [classes/order/Order.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L60).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/order/Order.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L154).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* Source: [classes/order/Order.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L157).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'orders', 'primary' => 'id_order', 'fields' => array('id_address_delivery' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_address_invoice' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_cart' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_shop_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_shop' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_lang' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_carrier' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'current_state' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'secure_key' => array('type' => self::TYPE_STRING, 'validate' => 'isMd5'), 'payment' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true), 'module' => array('type' => self::TYPE_STRING, 'validate' => 'isModuleName', 'required' => true), 'recyclable' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'gift' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'gift_message' => array('type' => self::TYPE_STRING, 'validate' => 'isMessage'), 'mobile_theme' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'total_discounts' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_discounts_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_discounts_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_paid' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'total_paid_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_paid_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_paid_real' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'total_products' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'total_products_wt' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'total_shipping' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_shipping_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_shipping_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'carrier_tax_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'total_wrapping' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_wrapping_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_wrapping_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'round_mode' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'round_type' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'shipping_number' => array('type' => self::TYPE_STRING, 'validate' => 'isTrackingNumber'), 'conversion_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'invoice_number' => array('type' => self::TYPE_INT), 'delivery_number' => array('type' => self::TYPE_INT), 'invoice_date' => array('type' => self::TYPE_DATE), 'delivery_date' => array('type' => self::TYPE_DATE), 'valid' => array('type' => self::TYPE_BOOL), 'reference' => array('type' => self::TYPE_STRING), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/order/Order.php line 177](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L177).


### <a name="property-$delivery_date"></a>$delivery_date

```php
public string $delivery_date
```





* Visibility: **public**
* Source: [classes/order/Order.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L148).


### <a name="property-$delivery_number"></a>$delivery_number

```php
public integer $delivery_number
```





* Visibility: **public**
* Source: [classes/order/Order.php line 142](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L142).


### <a name="property-$gift"></a>$gift

```php
public boolean $gift
```





* Visibility: **public**
* Source: [classes/order/Order.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L78).


### <a name="property-$gift_message"></a>$gift_message

```php
public string $gift_message
```





* Visibility: **public**
* Source: [classes/order/Order.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L81).


### <a name="property-$id_address_delivery"></a>$id_address_delivery

```php
public integer $id_address_delivery
```





* Visibility: **public**
* Source: [classes/order/Order.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L35).


### <a name="property-$id_address_invoice"></a>$id_address_invoice

```php
public integer $id_address_invoice
```





* Visibility: **public**
* Source: [classes/order/Order.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L38).


### <a name="property-$id_carrier"></a>$id_carrier

```php
public integer $id_carrier
```





* Visibility: **public**
* Source: [classes/order/Order.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L57).


### <a name="property-$id_cart"></a>$id_cart

```php
public integer $id_cart
```





* Visibility: **public**
* Source: [classes/order/Order.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L45).


### <a name="property-$id_currency"></a>$id_currency

```php
public integer $id_currency
```





* Visibility: **public**
* Source: [classes/order/Order.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L48).


### <a name="property-$id_customer"></a>$id_customer

```php
public integer $id_customer
```





* Visibility: **public**
* Source: [classes/order/Order.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L54).


### <a name="property-$id_lang"></a>$id_lang

```php
public integer $id_lang
```





* Visibility: **public**
* Source: [classes/order/Order.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L51).


### <a name="property-$id_shop"></a>$id_shop

```php
public mixed $id_shop
```





* Visibility: **public**
* Source: [classes/order/Order.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L42).


### <a name="property-$id_shop_group"></a>$id_shop_group

```php
public mixed $id_shop_group
```





* Visibility: **public**
* Source: [classes/order/Order.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L40).


### <a name="property-$invoice_date"></a>$invoice_date

```php
public string $invoice_date
```





* Visibility: **public**
* Source: [classes/order/Order.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L145).


### <a name="property-$invoice_number"></a>$invoice_number

```php
public integer $invoice_number
```





* Visibility: **public**
* Source: [classes/order/Order.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L139).


### <a name="property-$mobile_theme"></a>$mobile_theme

```php
public boolean $mobile_theme
```





* Visibility: **public**
* Source: [classes/order/Order.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L84).


### <a name="property-$module"></a>$module

```php
public string $module
```





* Visibility: **public**
* Source: [classes/order/Order.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L69).


### <a name="property-$payment"></a>$payment

```php
public string $payment
```





* Visibility: **public**
* Source: [classes/order/Order.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L66).


### <a name="property-$recyclable"></a>$recyclable

```php
public boolean $recyclable = 1
```





* Visibility: **public**
* Source: [classes/order/Order.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L75).


### <a name="property-$reference"></a>$reference

```php
public string $reference
```





* Visibility: **public**
* Source: [classes/order/Order.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L162).


### <a name="property-$round_mode"></a>$round_mode

```php
public integer $round_mode
```





* Visibility: **public**
* Source: [classes/order/Order.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L167).


### <a name="property-$round_type"></a>$round_type

```php
public integer $round_type
```





* Visibility: **public**
* Source: [classes/order/Order.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L172).


### <a name="property-$secure_key"></a>$secure_key

```php
public string $secure_key
```





* Visibility: **public**
* Source: [classes/order/Order.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L63).


### <a name="property-$shipping_number"></a>$shipping_number

```php
public string $shipping_number
```





* Visibility: **public**
* Source: [classes/order/Order.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L91).


### <a name="property-$total_discounts"></a>$total_discounts

```php
public float $total_discounts
```





* Visibility: **public**
* Source: [classes/order/Order.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L94).


### <a name="property-$total_discounts_tax_excl"></a>$total_discounts_tax_excl

```php
public mixed $total_discounts_tax_excl
```





* Visibility: **public**
* Source: [classes/order/Order.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L97).


### <a name="property-$total_discounts_tax_incl"></a>$total_discounts_tax_incl

```php
public mixed $total_discounts_tax_incl
```





* Visibility: **public**
* Source: [classes/order/Order.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L96).


### <a name="property-$total_paid"></a>$total_paid

```php
public float $total_paid
```





* Visibility: **public**
* Source: [classes/order/Order.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L100).


### <a name="property-$total_paid_real"></a>$total_paid_real

```php
public float $total_paid_real
```





* Visibility: **public**
* Source: [classes/order/Order.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L109).


### <a name="property-$total_paid_tax_excl"></a>$total_paid_tax_excl

```php
public float $total_paid_tax_excl
```





* Visibility: **public**
* Source: [classes/order/Order.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L106).


### <a name="property-$total_paid_tax_incl"></a>$total_paid_tax_incl

```php
public float $total_paid_tax_incl
```





* Visibility: **public**
* Source: [classes/order/Order.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L103).


### <a name="property-$total_products"></a>$total_products

```php
public float $total_products
```





* Visibility: **public**
* Source: [classes/order/Order.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L112).


### <a name="property-$total_products_wt"></a>$total_products_wt

```php
public float $total_products_wt
```





* Visibility: **public**
* Source: [classes/order/Order.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L115).


### <a name="property-$total_shipping"></a>$total_shipping

```php
public float $total_shipping
```





* Visibility: **public**
* Source: [classes/order/Order.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L118).


### <a name="property-$total_shipping_tax_excl"></a>$total_shipping_tax_excl

```php
public float $total_shipping_tax_excl
```





* Visibility: **public**
* Source: [classes/order/Order.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L124).


### <a name="property-$total_shipping_tax_incl"></a>$total_shipping_tax_incl

```php
public float $total_shipping_tax_incl
```





* Visibility: **public**
* Source: [classes/order/Order.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L121).


### <a name="property-$total_wrapping"></a>$total_wrapping

```php
public float $total_wrapping
```





* Visibility: **public**
* Source: [classes/order/Order.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L130).


### <a name="property-$total_wrapping_tax_excl"></a>$total_wrapping_tax_excl

```php
public float $total_wrapping_tax_excl
```





* Visibility: **public**
* Source: [classes/order/Order.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L136).


### <a name="property-$total_wrapping_tax_incl"></a>$total_wrapping_tax_incl

```php
public float $total_wrapping_tax_incl
```





* Visibility: **public**
* Source: [classes/order/Order.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L133).


### <a name="property-$valid"></a>$valid

```php
public boolean $valid
```





* Visibility: **public**
* Source: [classes/order/Order.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L151).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectMethods' => array('add' => 'addWs'), 'objectNodeName' => 'order', 'objectsNodeName' => 'orders', 'fields' => array('id_address_delivery' => array('xlink_resource' => 'addresses'), 'id_address_invoice' => array('xlink_resource' => 'addresses'), 'id_cart' => array('xlink_resource' => 'carts'), 'id_currency' => array('xlink_resource' => 'currencies'), 'id_lang' => array('xlink_resource' => 'languages'), 'id_customer' => array('xlink_resource' => 'customers'), 'id_carrier' => array('xlink_resource' => 'carriers'), 'current_state' => array('xlink_resource' => 'order_states', 'setter' => 'setWsCurrentState'), 'module' => array('required' => true), 'invoice_number' => array(), 'invoice_date' => array(), 'delivery_number' => array(), 'delivery_date' => array(), 'valid' => array(), 'date_add' => array(), 'date_upd' => array(), 'shipping_number' => array('getter' => 'getWsShippingNumber', 'setter' => 'setWsShippingNumber')), 'associations' => array('order_rows' => array('resource' => 'order_row', 'setter' => false, 'virtual_entity' => true, 'fields' => array('id' => array(), 'product_id' => array('required' => true), 'product_attribute_id' => array('required' => true), 'product_quantity' => array('required' => true), 'product_name' => array('setter' => false), 'product_reference' => array('setter' => false), 'product_ean13' => array('setter' => false), 'product_upc' => array('setter' => false), 'product_price' => array('setter' => false), 'unit_price_tax_incl' => array('setter' => false), 'unit_price_tax_excl' => array('setter' => false)))))
```





* Visibility: **protected**
* Source: [classes/order/Order.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L229).


### <a name="property-$cache_objects"></a>$cache_objects

```php
protected boolean $cache_objects = true
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L164).


### <a name="property-$db"></a>$db

```php
protected \Db $db = false
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L156).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L150).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected array $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L88).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected array $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L70).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected array $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L106).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected array $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L94).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected array $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L112).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected array $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L100).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected array $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L118).


### <a name="property-$force_id"></a>$force_id

```php
public boolean $force_id = false
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L159).


### <a name="property-$get_shop_from_context"></a>$get_shop_from_context

```php
protected boolean $get_shop_from_context = true
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L67).


### <a name="property-$id"></a>$id

```php
public integer $id
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L55).


### <a name="property-$id_shop_list"></a>$id_shop_list

```php
public array $id_shop_list = null
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L64).


### <a name="property-$identifier"></a>$identifier

```php
protected string $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L82).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L130).


### <a name="property-$image_format"></a>$image_format

```php
protected String $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L133).


### <a name="property-$loaded_classes"></a>$loaded_classes

```php
protected array $loaded_classes = array()
```

Holds compiled definitions of each ObjectModel class.

Values are assigned during object initialization.

* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L147).


### <a name="property-$table"></a>$table

```php
protected string $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L76).


### <a name="property-$tables"></a>$tables

```php
protected array $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L124).


### <a name="property-$update_fields"></a>$update_fields

```php
protected array $update_fields = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L153).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed OrderCore::__construct($id, $id_lang)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 281](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L281)


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### <a name="method-_deleteProduct"></a>_deleteProduct

```php
boolean OrderCore::_deleteProduct(\OrderDetail $order_detail, integer $quantity)
```

DOES delete the product



* Visibility: **protected**
* Source: [classes/order/Order.php line 390](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L390)


#### Arguments
* $order_detail **[OrderDetail](class.OrderDetailCore.md)**
* $quantity **integer**



### <a name="method-add"></a>add

```php
mixed OrderCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 307](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L307)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addCartRule"></a>addCartRule

```php
boolean OrderCore::addCartRule(integer $id_cart_rule, string $name, array $values, integer $id_order_invoice, $free_shipping)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1120](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1120)


#### Arguments
* $id_cart_rule **integer**
* $name **string**
* $values **array**
* $id_order_invoice **integer**
* $free_shipping **mixed**



### <a name="method-addDiscount"></a>addDiscount

```php
boolean OrderCore::addDiscount(integer $id_cart_rule, string $name, float $value)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1106)


#### Arguments
* $id_cart_rule **integer**
* $name **string**
* $value **float**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
boolean ObjectModelCore::addFieldsRequiredDatabase(array $fields)
```

Sets required field for this class in the database.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1390](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1390)


#### Arguments
* $fields **array**



### <a name="method-addOrderPayment"></a>addOrderPayment

```php
boolean OrderCore::addOrderPayment(float $amount_paid, string $payment_method, string $payment_transaction_id, \Currency $currency, string $date, \OrderInvoice $order_invoice)
```

This method allows to add a payment to the current order



* Visibility: **public**
* Source: [classes/order/Order.php line 1686](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1686)


#### Arguments
* $amount_paid **float**
* $payment_method **string**
* $payment_transaction_id **string**
* $currency **[Currency](class.CurrencyCore.md)**
* $date **string**
* $order_invoice **[OrderInvoice](class.OrderInvoiceCore.md)**



### <a name="method-addWs"></a>addWs

```php
mixed OrderCore::addWs($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1567](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1567)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-associateTo"></a>associateTo

```php
boolean|void ObjectModelCore::associateTo(integer|array $id_shops)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1464](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1464)


#### Arguments
* $id_shops **integer|array**



### <a name="method-cacheFieldsRequiredDatabase"></a>cacheFieldsRequiredDatabase

```php
mixed ObjectModelCore::cacheFieldsRequiredDatabase(boolean $all)
```

Caches data about required objects fields in memory



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1368](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1368)


#### Arguments
* $all **boolean** - If true, caches required fields of all object classes.



### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache(boolean $all)
```

Clears cache entries that have this object's ID.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1414](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1414)


#### Arguments
* $all **boolean** - If true, clears cache for all objects



### <a name="method-delete"></a>delete

```php
boolean ObjectModelCore::delete()
```

Deletes current object from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 743](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L743)




### <a name="method-deleteAssociations"></a>deleteAssociations

```php
mixed OrderCore::deleteAssociations()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1577](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1577)




### <a name="method-deleteCustomization"></a>deleteCustomization

```php
mixed OrderCore::deleteCustomization($id_customization, $quantity, $order_detail)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 461](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L461)


#### Arguments
* $id_customization **mixed**
* $quantity **mixed**
* $order_detail **mixed**



### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage(boolean $force_delete)
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1643](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1643)


#### Arguments
* $force_delete **boolean**



### <a name="method-deleteProduct"></a>deleteProduct

```php
boolean OrderCore::deleteProduct($order, \OrderDetail $order_detail, integer $quantity)
```

Does NOT delete a product but "cancel" it (which means return/refund/delete it depending of the case)



* Visibility: **public**
* Source: [classes/order/Order.php line 329](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L329)


#### Arguments
* $order **mixed**
* $order_detail **[OrderDetail](class.OrderDetailCore.md)**
* $quantity **integer**



### <a name="method-deleteSelection"></a>deleteSelection

```php
boolean ObjectModelCore::deleteSelection(array $ids)
```

Deletes multiple objects from the database at once



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 790](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L790)


#### Arguments
* $ids **array** - Array of objects IDs.



### <a name="method-disableCache"></a>disableCache

```php
mixed ObjectModelCore::disableCache()
```

Disables object caching



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1969](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1969)




### <a name="method-displayFieldName"></a>displayFieldName

```php
string ObjectModelCore::displayFieldName(string $field, string $class, boolean $htmlentities, \Context|null $context)
```

Returns field name translation



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1083](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1083)


#### Arguments
* $field **string** - Field name
* $class **string** - ObjectModel class name
* $htmlentities **boolean** - If true, applies htmlentities() to result string
* $context **[Context](class.ContextCore.md)|null** - Context object



### <a name="method-duplicateObject"></a>duplicateObject

```php
\ObjectModel|false ObjectModelCore::duplicateObject()
```

Takes current object ID, gets its values from database,
saves them in a new row and loads newly saved values as a new object.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 549](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L549)




### <a name="method-duplicateShops"></a>duplicateShops

```php
boolean|void ObjectModelCore::duplicateShops($id)
```

Copies shop association data from object with specified ID.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1523](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1523)


#### Arguments
* $id **mixed**



### <a name="method-enableCache"></a>enableCache

```php
mixed ObjectModelCore::enableCache()
```

Enables object caching



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1961](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1961)




### <a name="method-existsInDatabase"></a>existsInDatabase

```php
boolean ObjectModelCore::existsInDatabase(integer $id_entity, string $table)
```

Checks if an object exists in database.



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1686](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1686)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $type, integer $id_lang)
```

Formats values of each fields.



* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 327](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L327)


#### Arguments
* $type **integer** - FORMAT_COMMON or FORMAT_LANG or FORMAT_SHOP
* $id_lang **integer** - If this parameter is given, only take lang fields



### <a name="method-formatValue"></a>formatValue

```php
mixed ObjectModelCore::formatValue(mixed $value, integer $type, boolean $with_quotes, boolean $purify, boolean $allow_null)
```

Formats a value



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 381](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L381)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **boolean**
* $purify **boolean**
* $allow_null **boolean**



### <a name="method-generateReference"></a>generateReference

```php
String OrderCore::generateReference()
```

Gennerate a unique reference for orders generated with the same cart id
This references, is usefull for check payment



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 1629](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1629)




### <a name="method-getAssociatedShops"></a>getAssociatedShops

```php
array ObjectModelCore::getAssociatedShops()
```

Gets the list of associated shop IDs



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1499](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1499)




### <a name="method-getBrother"></a>getBrother

```php
mixed OrderCore::getBrother()
```

Get all other orders with the same reference



* Visibility: **public**
* Source: [classes/order/Order.php line 2112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L2112)




### <a name="method-getByDelivery"></a>getByDelivery

```php
mixed OrderCore::getByDelivery($id_delivery)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 1442](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1442)


#### Arguments
* $id_delivery **mixed**



### <a name="method-getByReference"></a>getByReference

```php
\PrestaShopCollection OrderCore::getByReference(string $reference)
```

Get a collection of orders using reference



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 1460](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1460)


#### Arguments
* $reference **string**



### <a name="method-getCartIdStatic"></a>getCartIdStatic

```php
integer OrderCore::getCartIdStatic(integer $id_order, integer $id_customer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 1510](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1510)


#### Arguments
* $id_order **integer**
* $id_customer **integer** - optionnal



### <a name="method-getCartProducts"></a>getCartProducts

```php
array OrderCore::getCartProducts()
```

This function return products of the orders
It's similar to Order::getProducts but with similar outputs of Cart::getProducts



* Visibility: **public**
* Source: [classes/order/Order.php line 354](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L354)




### <a name="method-getCartRules"></a>getCartRules

```php
mixed OrderCore::getCartRules()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 779](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L779)




### <a name="method-getCurrentOrderState"></a>getCurrentOrderState

```php
\OrderState OrderCore::getCurrentOrderState()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 2090](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L2090)




### <a name="method-getCurrentState"></a>getCurrentState

```php
integer OrderCore::getCurrentState()
```

Get current order status (eg. Awaiting payment, Delivered.

..)

* Visibility: **public**
* Source: [classes/order/Order.php line 807](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L807)




### <a name="method-getCurrentStateFull"></a>getCurrentStateFull

```php
array OrderCore::getCurrentStateFull($id_lang)
```

Get current order status name (eg. Awaiting payment, Delivered.

..)

* Visibility: **public**
* Source: [classes/order/Order.php line 817](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L817)


#### Arguments
* $id_lang **mixed**



### <a name="method-getCustomer"></a>getCustomer

```php
\Customer OrderCore::getCustomer()
```

Get order customer



* Visibility: **public**
* Source: [classes/order/Order.php line 1055](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1055)




### <a name="method-getCustomerNbOrders"></a>getCustomerNbOrders

```php
array OrderCore::getCustomerNbOrders(integer $id_customer)
```

Get customer orders number



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 1070](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1070)


#### Arguments
* $id_customer **integer** - Customer id



### <a name="method-getCustomerOrders"></a>getCustomerOrders

```php
array OrderCore::getCustomerOrders(integer $id_customer, boolean $show_hidden_status, \Context $context)
```

Get customer orders



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 882](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L882)


#### Arguments
* $id_customer **integer** - Customer id
* $show_hidden_status **boolean** - Display or not hidden order statuses
* $context **[Context](class.ContextCore.md)**



### <a name="method-getDefinition"></a>getDefinition

```php
array ObjectModelCore::getDefinition(string $class, string|null $field)
```

Returns object definition



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1809](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1809)


#### Arguments
* $class **string** - Name of object
* $field **string|null** - Name of field if we want the definition of one field only



### <a name="method-getDeliveryNumber"></a>getDeliveryNumber

```php
mixed OrderCore::getDeliveryNumber($order_invoice_id)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1404](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1404)


#### Arguments
* $order_invoice_id **mixed**



### <a name="method-getDeliverySlipsCollection"></a>getDeliverySlipsCollection

```php
\PrestaShopCollection OrderCore::getDeliverySlipsCollection()
```

Get all delivery slips for the current order



* Visibility: **public**
* Source: [classes/order/Order.php line 1822](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1822)




### <a name="method-getDiscounts"></a>getDiscounts

```php
mixed OrderCore::getDiscounts($details)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 773](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L773)


#### Arguments
* $details **mixed**



### <a name="method-getDiscountsCustomer"></a>getDiscountsCustomer

```php
mixed OrderCore::getDiscountsCustomer($id_customer, $id_cart_rule)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 787](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L787)


#### Arguments
* $id_customer **mixed**
* $id_cart_rule **mixed**



### <a name="method-getDocuments"></a>getDocuments

```php
array OrderCore::getDocuments()
```

Returns the correct product taxes breakdown.

Get all documents linked to the current order

* Visibility: **public**
* Source: [classes/order/Order.php line 1738](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1738)




### <a name="method-getEcoTaxTaxesBreakdown"></a>getEcoTaxTaxesBreakdown

```php
array OrderCore::getEcoTaxTaxesBreakdown()
```

Returns the ecotax taxes breakdown



* Visibility: **public**
* Source: [classes/order/Order.php line 2015](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L2015)




### <a name="method-getFieldByLang"></a>getFieldByLang

```php
mixed ObjectModelCore::getFieldByLang(string $field_name, integer|null $id_lang)
```

Return the field value for the specified language if the field is multilang,
else the field value.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1927](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1927)


#### Arguments
* $field_name **string**
* $id_lang **integer|null**



### <a name="method-getFields"></a>getFields

```php
array OrderCore::getFields()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 298](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L298)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 288](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L288)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
array|null ObjectModelCore::getFieldsRequiredDatabase(boolean $all)
```

Returns an array of required fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1355](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1355)


#### Arguments
* $all **boolean** - If true, returns required fields of all object classes.



### <a name="method-getFieldsShop"></a>getFieldsShop

```php
array ObjectModelCore::getFieldsShop()
```

Prepare fields for multishop
Fields are not validated here, we consider they are already validated in getFields() method,
this is not the best solution but this is the only one possible for retro compatibility.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L270)




### <a name="method-getFirstMessage"></a>getFirstMessage

```php
mixed OrderCore::getFirstMessage()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 554](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L554)




### <a name="method-getHistory"></a>getHistory

```php
array OrderCore::getHistory(integer $id_lang, integer $id_order_state, integer $no_hidden, integer $filters)
```

Get order history



* Visibility: **public**
* Source: [classes/order/Order.php line 491](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L491)


#### Arguments
* $id_lang **integer** - Language id
* $id_order_state **integer** - Filter a specific order status
* $no_hidden **integer** - Filter no hidden status
* $filters **integer** - Flag to use specific field filter



### <a name="method-getIdOrderCarrier"></a>getIdOrderCarrier

```php
mixed OrderCore::getIdOrderCarrier()
```

Return id of carrier

Get id of the carrier used in order

* Visibility: **public**
* Source: [classes/order/Order.php line 2175](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L2175)




### <a name="method-getIdOrderProduct"></a>getIdOrderProduct

```php
mixed OrderCore::getIdOrderProduct($id_customer, $id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 648](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L648)


#### Arguments
* $id_customer **mixed**
* $id_product **mixed**



### <a name="method-getInvoice"></a>getInvoice

```php
mixed OrderCore::getInvoice(integer $id_invoice)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 1481](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1481)


#### Arguments
* $id_invoice **integer**



### <a name="method-getInvoiceNumber"></a>getInvoiceNumber

```php
mixed OrderCore::getInvoiceNumber($order_invoice_id)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1202](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1202)


#### Arguments
* $order_invoice_id **mixed**



### <a name="method-getInvoicesCollection"></a>getInvoicesCollection

```php
\PrestaShopCollection OrderCore::getInvoicesCollection()
```

Get all invoices for the current order



* Visibility: **public**
* Source: [classes/order/Order.php line 1809](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1809)




### <a name="method-getLastInvoiceNumber"></a>getLastInvoiceNumber

```php
mixed OrderCore::getLastInvoiceNumber()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 1166](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1166)




### <a name="method-getNextOrderId"></a>getNextOrderId

```php
integer OrderCore::getNextOrderId()
```

This method return the ID of the next order



* Visibility: **public**
* Source: [classes/order/Order.php line 1604](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1604)




### <a name="method-getNotPaidInvoicesCollection"></a>getNotPaidInvoicesCollection

```php
\PrestaShopCollection OrderCore::getNotPaidInvoicesCollection()
```

Get all not paid invoices for the current order



* Visibility: **public**
* Source: [classes/order/Order.php line 1835](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1835)




### <a name="method-getNumberOfDays"></a>getNumberOfDays

```php
mixed OrderCore::getNumberOfDays()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1137](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1137)




### <a name="method-getOrderByCartId"></a>getOrderByCartId

```php
array OrderCore::getOrderByCartId(integer $id_cart)
```

Get an order by its cart id



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 1087](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1087)


#### Arguments
* $id_cart **integer** - Cart id



### <a name="method-getOrderDetailList"></a>getOrderDetailList

```php
array OrderCore::getOrderDetailList()
```

Get the an order detail list of the current order



* Visibility: **public**
* Source: [classes/order/Order.php line 1618](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1618)




### <a name="method-getOrderDetailTaxes"></a>getOrderDetailTaxes

```php
mixed OrderCore::getOrderDetailTaxes()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 2424](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L2424)




### <a name="method-getOrderIdsByStatus"></a>getOrderIdsByStatus

```php
array OrderCore::getOrderIdsByStatus($id_order_state)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 990](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L990)


#### Arguments
* $id_order_state **mixed**



### <a name="method-getOrderInvoiceIdIfHasDelivery"></a>getOrderInvoiceIdIfHasDelivery

```php
integer OrderCore::getOrderInvoiceIdIfHasDelivery()
```

Get order invoice id if has delivery return id_order_invoice if this order has already a delivery slip



* Visibility: **public**
* Source: [classes/order/Order.php line 2053](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L2053)




### <a name="method-getOrderPaymentCollection"></a>getOrderPaymentCollection

```php
\PrestaShopCollection OrderCore::getOrderPaymentCollection()
```

This method allows to get all Order Payment for the current order



* Visibility: **public**
* Source: [classes/order/Order.php line 1667](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1667)




### <a name="method-getOrderPayments"></a>getOrderPayments

```php
mixed OrderCore::getOrderPayments()
```

Get a collection of order payments



* Visibility: **public**
* Source: [classes/order/Order.php line 2125](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L2125)




### <a name="method-getOrderSlipsCollection"></a>getOrderSlipsCollection

```php
\PrestaShopCollection OrderCore::getOrderSlipsCollection()
```

Get all order_slips for the current order



* Visibility: **public**
* Source: [classes/order/Order.php line 1796](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1796)




### <a name="method-getOrdersIdByDate"></a>getOrdersIdByDate

```php
mixed OrderCore::getOrdersIdByDate($date_from, $date_to, $id_customer, $type)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 916](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L916)


#### Arguments
* $date_from **mixed**
* $date_to **mixed**
* $id_customer **mixed**
* $type **mixed**



### <a name="method-getOrdersIdInvoiceByDate"></a>getOrdersIdInvoiceByDate

```php
array OrderCore::getOrdersIdInvoiceByDate($date_from, $date_to, $id_customer, $type)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 965](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L965)


#### Arguments
* $date_from **mixed**
* $date_to **mixed**
* $id_customer **mixed**
* $type **mixed**



### <a name="method-getOrdersTotalPaid"></a>getOrdersTotalPaid

```php
float OrderCore::getOrdersTotalPaid()
```

Get the sum of total_paid_tax_incl of the orders with similar reference



* Visibility: **public**
* Source: [classes/order/Order.php line 1887](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1887)




### <a name="method-getOrdersWithInformations"></a>getOrdersWithInformations

```php
mixed OrderCore::getOrdersWithInformations($limit, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 933](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L933)


#### Arguments
* $limit **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getPreviousOrderId"></a>getPreviousOrderId

```php
integer OrderCore::getPreviousOrderId()
```

This method return the ID of the previous order



* Visibility: **public**
* Source: [classes/order/Order.php line 1589](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1589)




### <a name="method-getProductTaxesBreakdown"></a>getProductTaxesBreakdown

```php
array OrderCore::getProductTaxesBreakdown()
```

Returns the correct product taxes breakdown.



* Visibility: **public**
* Source: [classes/order/Order.php line 1926](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1926)




### <a name="method-getProductTaxesDetails"></a>getProductTaxesDetails

```php
array OrderCore::getProductTaxesDetails($limitToOrderDetails)
```

By default this function was made for invoice, to compute tax amounts and balance delta (because of computation made on round values).

If you provide $limitToOrderDetails, only these item will be taken into account. This option is usefull for order slip for example,
where only sublist of the order is refunded.

* Visibility: **public**
* Source: [classes/order/Order.php line 2245](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L2245)


#### Arguments
* $limitToOrderDetails **mixed** - Optional array of OrderDetails to take into account. False by default to take all OrderDetails from the current Order.



### <a name="method-getProducts"></a>getProducts

```php
array OrderCore::getProducts($products, $selected_products, $selected_qty)
```

Get order products



* Visibility: **public**
* Source: [classes/order/Order.php line 597](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L597)


#### Arguments
* $products **mixed**
* $selected_products **mixed**
* $selected_qty **mixed**



### <a name="method-getProductsDetail"></a>getProductsDetail

```php
mixed OrderCore::getProductsDetail()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 544](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L544)




### <a name="method-getRepositoryClassName"></a>getRepositoryClassName

```php
mixed ObjectModelCore::getRepositoryClassName()
```

Returns the name of the repository class for this entity.

If unspecified, a generic repository will be used for the entity.

* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L166)




### <a name="method-getReturn"></a>getReturn

```php
mixed OrderCore::getReturn()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1763](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1763)




### <a name="method-getShipping"></a>getShipping

```php
array OrderCore::getShipping()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1772](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1772)




### <a name="method-getShippingTaxesBreakdown"></a>getShippingTaxesBreakdown

```php
array OrderCore::getShippingTaxesBreakdown()
```

Returns the shipping taxes breakdown



* Visibility: **public**
* Source: [classes/order/Order.php line 1981](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1981)




### <a name="method-getTaxCalculationMethod"></a>getTaxCalculationMethod

```php
mixed OrderCore::getTaxCalculationMethod()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 315](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L315)




### <a name="method-getTaxesAverageUsed"></a>getTaxesAverageUsed

```php
mixed OrderCore::getTaxesAverageUsed()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 723](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L723)




### <a name="method-getTotalPaid"></a>getTotalPaid

```php
float OrderCore::getTotalPaid(\Currency $currency)
```

Get total paid



* Visibility: **public**
* Source: [classes/order/Order.php line 1855](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1855)


#### Arguments
* $currency **[Currency](class.CurrencyCore.md)** - currency used for the total paid of the current order



### <a name="method-getTotalProductsWithTaxes"></a>getTotalProductsWithTaxes

```php
\Product OrderCore::getTotalProductsWithTaxes($products)
```

Get product total with taxes



* Visibility: **public**
* Source: [classes/order/Order.php line 1022](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1022)


#### Arguments
* $products **mixed**



### <a name="method-getTotalProductsWithoutTaxes"></a>getTotalProductsWithoutTaxes

```php
\Product OrderCore::getTotalProductsWithoutTaxes($products)
```

Get product total without taxes



* Visibility: **public**
* Source: [classes/order/Order.php line 1012](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1012)


#### Arguments
* $products **mixed**



### <a name="method-getTotalWeight"></a>getTotalWeight

```php
mixed OrderCore::getTotalWeight()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1467](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1467)




### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
array ObjectModelCore::getTranslationsFields(array $fields_array)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 831](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L831)


#### Arguments
* $fields_array **array**



### <a name="method-getUniqReference"></a>getUniqReference

```php
mixed OrderCore::getUniqReference()
```

Return a unique reference like : GWJTHMZUN#2

With multishipping, order reference are the same for all orders made with the same cart
in this case this method suffix the order reference by a # and the order number

* Visibility: **public**
* Source: [classes/order/Order.php line 2138](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L2138)




### <a name="method-getUniqReferenceOf"></a>getUniqReferenceOf

```php
mixed OrderCore::getUniqReferenceOf($id_order)
```

Return a unique reference like : GWJTHMZUN#2

With multishipping, order reference are the same for all orders made with the same cart
in this case this method suffix the order reference by a # and the order number

* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 2162](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L2162)


#### Arguments
* $id_order **mixed**



### <a name="method-getValidationRules"></a>getValidationRules

```php
array ObjectModelCore::getValidationRules(string $class)
```

Returns object validation rules (fields validity)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L178)


#### Arguments
* $class **string** - Child class name for static use (optional)



### <a name="method-getVirtualProducts"></a>getVirtualProducts

```php
integer OrderCore::getVirtualProducts()
```

Count virtual products in order



* Visibility: **public**
* Source: [classes/order/Order.php line 733](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L733)




### <a name="method-getWarehouseList"></a>getWarehouseList

```php
mixed OrderCore::getWarehouseList()
```

Get warehouse associated to the order

return array List of warehouse

* Visibility: **public**
* Source: [classes/order/Order.php line 2067](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L2067)




### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed OrderCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 2101](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L2101)


#### Arguments
* $sql_join **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**



### <a name="method-getWebserviceParameters"></a>getWebserviceParameters

```php
array ObjectModelCore::getWebserviceParameters(string|null $ws_params_attribute_name)
```

Returns webservice parameters of this object.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1176](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1176)


#### Arguments
* $ws_params_attribute_name **string|null**



### <a name="method-getWrappingTaxesBreakdown"></a>getWrappingTaxesBreakdown

```php
array OrderCore::getWrappingTaxesBreakdown()
```

Returns the wrapping taxes breakdown



* Visibility: **public**
* Source: [classes/order/Order.php line 2003](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L2003)




### <a name="method-getWsCurrentState"></a>getWsCurrentState

```php
mixed OrderCore::getWsCurrentState()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 2223](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L2223)




### <a name="method-getWsOrderRows"></a>getWsOrderRows

```php
mixed OrderCore::getWsOrderRows()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1519](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1519)




### <a name="method-getWsShippingNumber"></a>getWsShippingNumber

```php
mixed OrderCore::getWsShippingNumber()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 2191](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L2191)




### <a name="method-hasBeenDelivered"></a>hasBeenDelivered

```php
mixed OrderCore::hasBeenDelivered()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 826](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L826)




### <a name="method-hasBeenPaid"></a>hasBeenPaid

```php
mixed OrderCore::hasBeenPaid()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 846](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L846)




### <a name="method-hasBeenShipped"></a>hasBeenShipped

```php
mixed OrderCore::hasBeenShipped()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 851](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L851)




### <a name="method-hasDelivery"></a>hasDelivery

```php
boolean OrderCore::hasDelivery()
```

Has Delivery return true if this order has already a delivery slip



* Visibility: **public**
* Source: [classes/order/Order.php line 2043](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L2043)




### <a name="method-hasInvoice"></a>hasInvoice

```php
boolean OrderCore::hasInvoice()
```

Has invoice return true if this order has already an invoice



* Visibility: **public**
* Source: [classes/order/Order.php line 2028](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L2028)




### <a name="method-hasMultishopEntries"></a>hasMultishopEntries

```php
boolean ObjectModelCore::hasMultishopEntries()
```

Checks if there is more than one entry in associated shop table for current object.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1550](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1550)




### <a name="method-hasProductReturned"></a>hasProductReturned

```php
mixed OrderCore::hasProductReturned()
```

Has products returned by the merchant or by the customer?



* Visibility: **public**
* Source: [classes/order/Order.php line 834](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L834)




### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer|null $id_lang)
```

Fill an object with given data. Data must be an array with this syntax:
array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1730](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1730)


#### Arguments
* $data **array**
* $id_lang **integer|null**



### <a name="method-hydrateCollection"></a>hydrateCollection

```php
array ObjectModelCore::hydrateCollection(string $class, array $datas, integer|null $id_lang)
```

Fill (hydrate) a list of objects in order to get a collection of these objects



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1755](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1755)


#### Arguments
* $class **string** - Class of objects to hydrate
* $datas **array** - List of data (multi-dimensional array)
* $id_lang **integer|null**



### <a name="method-isAssociatedAtGuest"></a>isAssociatedAtGuest

```php
mixed OrderCore::isAssociatedAtGuest($email)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1490](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1490)


#### Arguments
* $email **mixed**



### <a name="method-isAssociatedToShop"></a>isAssociatedToShop

```php
boolean ObjectModelCore::isAssociatedToShop(integer|null $id_shop)
```

Checks if current object is associated to a shop.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1430](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1430)


#### Arguments
* $id_shop **integer|null**



### <a name="method-isCurrentlyUsed"></a>isCurrentlyUsed

```php
boolean ObjectModelCore::isCurrentlyUsed(string|null $table, boolean $has_active_column)
```

Checks if an object type exists in the database.



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1706](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1706)


#### Arguments
* $table **string|null** - Name of table linked to entity
* $has_active_column **boolean** - True if the table has an active column



### <a name="method-isInPreparation"></a>isInPreparation

```php
mixed OrderCore::isInPreparation()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 856](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L856)




### <a name="method-isLangMultishop"></a>isLangMultishop

```php
boolean ObjectModelCore::isLangMultishop()
```

Checks if the object is both multi-language and multi-shop.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1586](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1586)




### <a name="method-isMultiShopField"></a>isMultiShopField

```php
boolean ObjectModelCore::isMultiShopField(string $field)
```

Checks if a field is a multi-shop field.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1576](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1576)


#### Arguments
* $field **string**



### <a name="method-isMultishop"></a>isMultishop

```php
boolean ObjectModelCore::isMultishop()
```

Checks if object is multi-shop object.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1564](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1564)




### <a name="method-isPaidAndShipped"></a>isPaidAndShipped

```php
boolean OrderCore::isPaidAndShipped()
```

Checks if the current order status is paid and shipped



* Visibility: **public**
* Source: [classes/order/Order.php line 866](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L866)




### <a name="method-isReturnable"></a>isReturnable

```php
boolean OrderCore::isReturnable()
```

Can this order be returned by the client?



* Visibility: **public**
* Source: [classes/order/Order.php line 1157](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1157)




### <a name="method-isVirtual"></a>isVirtual

```php
boolean OrderCore::isVirtual(boolean $strict)
```

Check if order contains (only) virtual products



* Visibility: **public**
* Source: [classes/order/Order.php line 750](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L750)


#### Arguments
* $strict **boolean** - If false return true if there are at least one product virtual



### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields(array $fields, array $fields_array, integer $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 854](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L854)


#### Arguments
* $fields **array**
* $fields_array **array**
* $id_language **integer**



### <a name="method-orderContainProduct"></a>orderContainProduct

```php
mixed OrderCore::orderContainProduct($id_product)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1634](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1634)


#### Arguments
* $id_product **mixed**



### <a name="method-save"></a>save

```php
boolean ObjectModelCore::save(boolean $null_values, boolean $auto_date)
```

Saves current object to database (add or update)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 443](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L443)


#### Arguments
* $null_values **boolean**
* $auto_date **boolean**



### <a name="method-setCurrentState"></a>setCurrentState

```php
mixed OrderCore::setCurrentState(integer $id_order_state, integer $id_employee)
```

Set current order status



* Visibility: **public**
* Source: [classes/order/Order.php line 1545](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1545)


#### Arguments
* $id_order_state **integer**
* $id_employee **integer** - (/!\ not optional except for Webservice.



### <a name="method-setDefinitionRetrocompatibility"></a>setDefinitionRetrocompatibility

```php
mixed ObjectModelCore::setDefinitionRetrocompatibility()
```

Retrocompatibility for classes without $definition static



* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1855](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1855)




### <a name="method-setDelivery"></a>setDelivery

```php
mixed OrderCore::setDelivery()
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1416](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1416)




### <a name="method-setDeliveryNumber"></a>setDeliveryNumber

```php
mixed OrderCore::setDeliveryNumber($order_invoice_id, $id_shop)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 1376](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1376)


#### Arguments
* $order_invoice_id **mixed**
* $id_shop **mixed**



### <a name="method-setDeliverySlip"></a>setDeliverySlip

```php
mixed OrderCore::setDeliverySlip()
```

This method allows to generate first delivery slip of the current order



* Visibility: **public**
* Source: [classes/order/Order.php line 1363](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1363)




### <a name="method-setFieldsToUpdate"></a>setFieldsToUpdate

```php
mixed ObjectModelCore::setFieldsToUpdate(array $fields)
```

Set a list of specific fields to update
array(field1 => true, field2 => false,
langfield1 => array(1 => true, 2 => false))



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1953](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1953)


#### Arguments
* $fields **array**



### <a name="method-setInvoice"></a>setInvoice

```php
mixed OrderCore::setInvoice($use_existing_payment)
```

This method allows to generate first invoice of the current order



* Visibility: **public**
* Source: [classes/order/Order.php line 1217](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1217)


#### Arguments
* $use_existing_payment **mixed**



### <a name="method-setInvoiceDetails"></a>setInvoiceDetails

```php
mixed OrderCore::setInvoiceDetails($order_invoice)
```

This method allows to fulfill the object order_invoice with sales figures



* Visibility: **protected**
* Source: [classes/order/Order.php line 1313](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1313)


#### Arguments
* $order_invoice **mixed**



### <a name="method-setLastInvoiceNumber"></a>setLastInvoiceNumber

```php
mixed OrderCore::setLastInvoiceNumber($order_invoice_id, $id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 1175](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1175)


#### Arguments
* $order_invoice_id **mixed**
* $id_shop **mixed**



### <a name="method-setProductCurrentStock"></a>setProductCurrentStock

```php
mixed OrderCore::setProductCurrentStock($product)
```

This method allow to add stock information on a product detail

If advanced stock management is active, get physical stock of this product in the warehouse associated to the ptoduct for the current order
Else get the available quantity of the product in fucntion of the shop associated to the order

* Visibility: **protected**
* Source: [classes/order/Order.php line 680](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L680)


#### Arguments
* $product **mixed**



### <a name="method-setProductCustomizedDatas"></a>setProductCustomizedDatas

```php
mixed OrderCore::setProductCustomizedDatas($product, $customized_datas)
```





* Visibility: **protected**
* Source: [classes/order/Order.php line 661](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L661)


#### Arguments
* $product **mixed**
* $customized_datas **mixed**



### <a name="method-setProductImageInformations"></a>setProductImageInformations

```php
mixed OrderCore::setProductImageInformations($product)
```

This method allow to add image information on a product detail



* Visibility: **protected**
* Source: [classes/order/Order.php line 696](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L696)


#### Arguments
* $product **mixed**



### <a name="method-setProductPrices"></a>setProductPrices

```php
mixed OrderCore::setProductPrices($row)
```

Marked as deprecated but should not throw any "deprecated" message
This function is used in order to keep front office backward compatibility 14 -> 1.5
(Order History)



* Visibility: **public**
* Source: [classes/order/Order.php line 571](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L571)


#### Arguments
* $row **mixed**



### <a name="method-setWsCurrentState"></a>setWsCurrentState

```php
mixed OrderCore::setWsCurrentState($state)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 2228](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L2228)


#### Arguments
* $state **mixed**



### <a name="method-setWsShippingNumber"></a>setWsShippingNumber

```php
mixed OrderCore::setWsShippingNumber($shipping_number)
```





* Visibility: **public**
* Source: [classes/order/Order.php line 2204](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L2204)


#### Arguments
* $shipping_number **mixed**



### <a name="method-sortDocuments"></a>sortDocuments

```php
mixed OrderCore::sortDocuments($a, $b)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/Order.php line 2183](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L2183)


#### Arguments
* $a **mixed**
* $b **mixed**



### <a name="method-toggleStatus"></a>toggleStatus

```php
boolean ObjectModelCore::toggleStatus()
```

Toggles object status in database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 807](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L807)




### <a name="method-update"></a>update

```php
boolean ObjectModelCore::update(boolean $null_values)
```

Updates the current object in the database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 619](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L619)


#### Arguments
* $null_values **boolean**



### <a name="method-updateMultishopTable"></a>updateMultishopTable

```php
boolean ObjectModelCore::updateMultishopTable(string $classname, array $data, string $where, string $specific_where)
```

Updates a table and splits the common datas and the shop datas.



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1602](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1602)


#### Arguments
* $classname **string**
* $data **array**
* $where **string**
* $specific_where **string** - Only executed for common table



### <a name="method-updateOrderDetailTax"></a>updateOrderDetailTax

```php
mixed OrderCore::updateOrderDetailTax()
```

The primary purpose of this method is to be
called at the end of the generation of each order
in PaymentModule::validateOrder, to fill in
the order_detail_tax table with taxes
that will add up in such a way that
the sum of the tax amounts in the product tax breakdown
is equal to the difference between products with tax and
products without tax.



* Visibility: **public**
* Source: [classes/order/Order.php line 2398](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L2398)




### <a name="method-updateShippingCost"></a>updateShippingCost

```php
boolean OrderCore::updateShippingCost(float $amount)
```

This method allows to change the shipping cost of the current order



* Visibility: **public**
* Source: [classes/order/Order.php line 1903](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1903)


#### Arguments
* $amount **float**



### <a name="method-useOneAfterAnotherTaxComputationMethod"></a>useOneAfterAnotherTaxComputationMethod

```php
boolean OrderCore::useOneAfterAnotherTaxComputationMethod()
```

This method returns true if at least one order details uses the
One After Another tax computation method.



* Visibility: **public**
* Source: [classes/order/Order.php line 1651](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/Order.php#L1651)




### <a name="method-validateControler"></a>validateControler

```php
array ObjectModelCore::validateControler(boolean $htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1105](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1105)


#### Arguments
* $htmlentities **boolean**



### <a name="method-validateController"></a>validateController

```php
array ObjectModelCore::validateController(boolean $htmlentities)
```

Validates submitted values and returns an array of errors, if any.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1118)


#### Arguments
* $htmlentities **boolean** - If true, uses htmlentities() for field name translations in errors.



### <a name="method-validateField"></a>validateField

```php
true|string ObjectModelCore::validateField(string $field, mixed $value, integer|null $id_lang, array $skip, boolean $human_errors)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 977](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L977)


#### Arguments
* $field **string** - Field name
* $value **mixed** - Field value
* $id_lang **integer|null** - Language ID
* $skip **array** - Array of fields to skip.
* $human_errors **boolean** - If true, uses more descriptive, translatable error strings.



### <a name="method-validateFields"></a>validateFields

```php
boolean|string ObjectModelCore::validateFields(boolean $die, boolean $error_return)
```

Checks if object field values are valid before database interaction



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 895](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L895)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-validateFieldsLang"></a>validateFieldsLang

```php
boolean|string ObjectModelCore::validateFieldsLang(boolean $die, boolean $error_return)
```

Checks if multilingual object field values are valid before database interaction.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 927](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L927)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-validateFieldsRequiredDatabase"></a>validateFieldsRequiredDatabase

```php
array ObjectModelCore::validateFieldsRequiredDatabase(boolean $htmlentities)
```

Validate required fields.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1322](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1322)


#### Arguments
* $htmlentities **boolean**


