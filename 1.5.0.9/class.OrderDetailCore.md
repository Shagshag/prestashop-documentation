Class OrderDetailCore
=====================





* Class name: OrderDetailCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/order/OrderDetail.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L28)


Contents
--------


### Properties

* [$context](#property-$context)
* [$customer](#property-$customer)
* [$definition](#property-$definition)
* [$discount_quantity_applied](#property-$discount_quantity_applied)
* [$download_deadline](#property-$download_deadline)
* [$download_hash](#property-$download_hash)
* [$download_nb](#property-$download_nb)
* [$ecotax](#property-$ecotax)
* [$ecotax_tax_rate](#property-$ecotax_tax_rate)
* [$group_reduction](#property-$group_reduction)
* [$id_order](#property-$id_order)
* [$id_order_detail](#property-$id_order_detail)
* [$id_order_invoice](#property-$id_order_invoice)
* [$id_warehouse](#property-$id_warehouse)
* [$outOfStock](#property-$outOfStock)
* [$product_attribute_id](#property-$product_attribute_id)
* [$product_ean13](#property-$product_ean13)
* [$product_id](#property-$product_id)
* [$product_name](#property-$product_name)
* [$product_price](#property-$product_price)
* [$product_quantity](#property-$product_quantity)
* [$product_quantity_discount](#property-$product_quantity_discount)
* [$product_quantity_in_stock](#property-$product_quantity_in_stock)
* [$product_quantity_refunded](#property-$product_quantity_refunded)
* [$product_quantity_reinjected](#property-$product_quantity_reinjected)
* [$product_quantity_return](#property-$product_quantity_return)
* [$product_reference](#property-$product_reference)
* [$product_supplier_reference](#property-$product_supplier_reference)
* [$product_upc](#property-$product_upc)
* [$product_weight](#property-$product_weight)
* [$reduction_amount](#property-$reduction_amount)
* [$reduction_amount_tax_excl](#property-$reduction_amount_tax_excl)
* [$reduction_amount_tax_incl](#property-$reduction_amount_tax_incl)
* [$reduction_percent](#property-$reduction_percent)
* [$specificPrice](#property-$specificPrice)
* [$tax_calculator](#property-$tax_calculator)
* [$tax_name](#property-$tax_name)
* [$tax_rate](#property-$tax_rate)
* [$total_price_tax_excl](#property-$total_price_tax_excl)
* [$total_price_tax_incl](#property-$total_price_tax_incl)
* [$total_shipping_price_tax_excl](#property-$total_shipping_price_tax_excl)
* [$total_shipping_price_tax_incl](#property-$total_shipping_price_tax_incl)
* [$unit_price_tax_excl](#property-$unit_price_tax_excl)
* [$unit_price_tax_incl](#property-$unit_price_tax_incl)
* [$vat_address](#property-$vat_address)
* [$webserviceParameters](#property-$webserviceParameters)
* [$def](#property-$def)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidate](#property-$fieldsValidate)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$id](#property-$id)
* [$id_lang](#property-$id_lang)
* [$id_shop](#property-$id_shop)
* [$identifier](#property-$identifier)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$table](#property-$table)
* [$tables](#property-$tables)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [associateTo](#method-associateTo)
* [checkProductStock](#method-checkProductStock)
* [clearCache](#method-clearCache)
* [create](#method-create)
* [createList](#method-createList)
* [delete](#method-delete)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [displayFieldName](#method-displayFieldName)
* [duplicateShops](#method-duplicateShops)
* [existsInDatabase](#method-existsInDatabase)
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [getDefinition](#method-getDefinition)
* [getDownloadFromHash](#method-getDownloadFromHash)
* [getFieldByLang](#method-getFieldByLang)
* [getFields](#method-getFields)
* [getFieldsLang](#method-getFieldsLang)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getList](#method-getList)
* [getStockState](#method-getStockState)
* [getTaxCalculator](#method-getTaxCalculator)
* [getTaxCalculatorStatic](#method-getTaxCalculatorStatic)
* [getTranslationsFields](#method-getTranslationsFields)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [getWsTaxes](#method-getWsTaxes)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [incrementDownload](#method-incrementDownload)
* [isAssociatedToGroupShop](#method-isAssociatedToGroupShop)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isLangMultishop](#method-isLangMultishop)
* [makeTranslationFields](#method-makeTranslationFields)
* [save](#method-save)
* [saveTaxCalculator](#method-saveTaxCalculator)
* [setDefinitionRetrocompatibility](#method-setDefinitionRetrocompatibility)
* [setDetailProductPrice](#method-setDetailProductPrice)
* [setProductTax](#method-setProductTax)
* [setShippingCost](#method-setShippingCost)
* [setSpecificPrice](#method-setSpecificPrice)
* [setVirtualProductInformation](#method-setVirtualProductInformation)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateField](#method-validateField)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)




Properties
----------


### <a name="property-$context"></a>$context

```php
protected \Context $context = null
```





* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L223).


### <a name="property-$customer"></a>$customer

```php
protected \Customer $customer = null
```





* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 220](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L220).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'order_detail', 'primary' => 'id_order_detail', 'fields' => array('id_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_order_invoice' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_warehouse' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'product_id' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'product_attribute_id' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'product_name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true), 'product_quantity' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'required' => true), 'product_quantity_in_stock' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'product_quantity_return' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'product_quantity_refunded' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'product_quantity_reinjected' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'product_price' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'reduction_percent' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'reduction_amount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'reduction_amount_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'reduction_amount_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'group_reduction' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'product_quantity_discount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'product_ean13' => array('type' => self::TYPE_STRING, 'validate' => 'isEan13'), 'product_upc' => array('type' => self::TYPE_STRING, 'validate' => 'isUpc'), 'product_reference' => array('type' => self::TYPE_STRING, 'validate' => 'isReference'), 'product_supplier_reference' => array('type' => self::TYPE_STRING, 'validate' => 'isReference'), 'product_weight' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'tax_name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName'), 'tax_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'ecotax' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'ecotax_tax_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'discount_quantity_applied' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'download_hash' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName'), 'download_nb' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'download_deadline' => array('type' => self::TYPE_DATE, 'validate' => 'isDateFormat'), 'unit_price_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'unit_price_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_price_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_price_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/order/OrderDetail.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L147).


### <a name="property-$discount_quantity_applied"></a>$discount_quantity_applied

```php
public integer $discount_quantity_applied
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L118).


### <a name="property-$download_deadline"></a>$download_deadline

```php
public \date $download_deadline
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L127).


### <a name="property-$download_hash"></a>$download_hash

```php
public string $download_hash
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L121).


### <a name="property-$download_nb"></a>$download_nb

```php
public integer $download_nb
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L124).


### <a name="property-$ecotax"></a>$ecotax

```php
public float $ecotax
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L112).


### <a name="property-$ecotax_tax_rate"></a>$ecotax_tax_rate

```php
public float $ecotax_tax_rate
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L115).


### <a name="property-$group_reduction"></a>$group_reduction

```php
public float $group_reduction
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L91).


### <a name="property-$id_order"></a>$id_order

```php
public integer $id_order
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L34).


### <a name="property-$id_order_detail"></a>$id_order_detail

```php
public integer $id_order_detail
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L31).


### <a name="property-$id_order_invoice"></a>$id_order_invoice

```php
public integer $id_order_invoice
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L37).


### <a name="property-$id_warehouse"></a>$id_warehouse

```php
public integer $id_warehouse
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L136).


### <a name="property-$outOfStock"></a>$outOfStock

```php
protected boolean $outOfStock = false
```





* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 208](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L208).


### <a name="property-$product_attribute_id"></a>$product_attribute_id

```php
public integer $product_attribute_id
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L43).


### <a name="property-$product_ean13"></a>$product_ean13

```php
public string $product_ean13
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L97).


### <a name="property-$product_id"></a>$product_id

```php
public integer $product_id
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L40).


### <a name="property-$product_name"></a>$product_name

```php
public string $product_name
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L46).


### <a name="property-$product_price"></a>$product_price

```php
public float $product_price
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L64).


### <a name="property-$product_quantity"></a>$product_quantity

```php
public integer $product_quantity
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L49).


### <a name="property-$product_quantity_discount"></a>$product_quantity_discount

```php
public float $product_quantity_discount
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L94).


### <a name="property-$product_quantity_in_stock"></a>$product_quantity_in_stock

```php
public integer $product_quantity_in_stock
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L52).


### <a name="property-$product_quantity_refunded"></a>$product_quantity_refunded

```php
public integer $product_quantity_refunded
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L58).


### <a name="property-$product_quantity_reinjected"></a>$product_quantity_reinjected

```php
public integer $product_quantity_reinjected
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L61).


### <a name="property-$product_quantity_return"></a>$product_quantity_return

```php
public integer $product_quantity_return
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L55).


### <a name="property-$product_reference"></a>$product_reference

```php
public string $product_reference
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L103).


### <a name="property-$product_supplier_reference"></a>$product_supplier_reference

```php
public string $product_supplier_reference
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L106).


### <a name="property-$product_upc"></a>$product_upc

```php
public string $product_upc
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L100).


### <a name="property-$product_weight"></a>$product_weight

```php
public float $product_weight
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L109).


### <a name="property-$reduction_amount"></a>$reduction_amount

```php
public float $reduction_amount
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L82).


### <a name="property-$reduction_amount_tax_excl"></a>$reduction_amount_tax_excl

```php
public float $reduction_amount_tax_excl
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L85).


### <a name="property-$reduction_amount_tax_incl"></a>$reduction_amount_tax_incl

```php
public float $reduction_amount_tax_incl
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L88).


### <a name="property-$reduction_percent"></a>$reduction_percent

```php
public float $reduction_percent
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L79).


### <a name="property-$specificPrice"></a>$specificPrice

```php
protected \Address $specificPrice = null
```





* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L217).


### <a name="property-$tax_calculator"></a>$tax_calculator

```php
protected \TaxCalculator $tax_calculator = null
```





* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 211](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L211).


### <a name="property-$tax_name"></a>$tax_name

```php
public string $tax_name
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L130).


### <a name="property-$tax_rate"></a>$tax_rate

```php
public float $tax_rate
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L133).


### <a name="property-$total_price_tax_excl"></a>$total_price_tax_excl

```php
public float $total_price_tax_excl
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L76).


### <a name="property-$total_price_tax_incl"></a>$total_price_tax_incl

```php
public float $total_price_tax_incl
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L73).


### <a name="property-$total_shipping_price_tax_excl"></a>$total_shipping_price_tax_excl

```php
public float $total_shipping_price_tax_excl
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L139).


### <a name="property-$total_shipping_price_tax_incl"></a>$total_shipping_price_tax_incl

```php
public float $total_shipping_price_tax_incl
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 142](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L142).


### <a name="property-$unit_price_tax_excl"></a>$unit_price_tax_excl

```php
public float $unit_price_tax_excl
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L70).


### <a name="property-$unit_price_tax_incl"></a>$unit_price_tax_incl

```php
public float $unit_price_tax_incl
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L67).


### <a name="property-$vat_address"></a>$vat_address

```php
protected \Address $vat_address = null
```





* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 214](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L214).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_order' => array('xlink_resource' => 'orders'), 'product_id' => array('xlink_resource' => 'products'), 'product_attribute_id' => array('xlink_resource' => 'combinations'), 'product_quantity_reinjected' => array(), 'group_reduction' => array(), 'discount_quantity_applied' => array(), 'download_hash' => array(), 'download_deadline' => array()), 'hidden_fields' => array('tax_rate', 'tax_name'), 'associations' => array('taxes' => array('resource' => 'tax', 'getter' => 'getWsTaxes', 'setter' => false, 'fields' => array('id' => array()))))
```





* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L189).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L122).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L72).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected mixed $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L57).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L87).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L77).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L92).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L82).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L97).


### <a name="property-$id"></a>$id

```php
public integer $id
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L48).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L51).


### <a name="property-$id_shop"></a>$id_shop

```php
protected mixed $id_shop = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L53).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L67).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L108).


### <a name="property-$image_format"></a>$image_format

```php
protected string $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L111).


### <a name="property-$table"></a>$table

```php
protected mixed $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L62).


### <a name="property-$tables"></a>$tables

```php
protected mixed $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L102).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed OrderDetailCore::__construct($id, $id_lang, $context)
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 225](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L225)


#### Arguments
* $id **mixed**
* $id_lang **mixed**
* $context **mixed**



### <a name="method-add"></a>add

```php
boolean ObjectModelCore::add(boolean $autodate, boolean $null_values)
```

Add current object to database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 372](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L372)


#### Arguments
* $autodate **boolean**
* $null_values **boolean**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 925](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L925)


#### Arguments
* $fields **mixed**



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops, string $type)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 973](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L973)


#### Arguments
* $id_shops **integer|array**
* $type **string**



### <a name="method-checkProductStock"></a>checkProductStock

```php
mixed OrderDetailCore::checkProductStock(array $product, integer $id_order_state)
```

Check the order state



* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 363](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L363)


#### Arguments
* $product **array**
* $id_order_state **integer**



### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 939](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L939)


#### Arguments
* $all **mixed**



### <a name="method-create"></a>create

```php
mixed OrderDetailCore::create(object $order, object $cart, array $product, $id_order_state, integer $id_order_invoice, boolean $use_taxes, $id_warehouse)
```

Create an order detail liable to an id_order



* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 490](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L490)


#### Arguments
* $order **object**
* $cart **object**
* $product **array**
* $id_order_state **mixed**
* $id_order_invoice **integer**
* $use_taxes **boolean** - set to false if you don&#039;t want to use taxes
* $id_warehouse **mixed**



### <a name="method-createList"></a>createList

```php
mixed OrderDetailCore::createList(object $order, object $cart, $id_order_state, $product_list, integer $id_order_invoice, boolean $use_taxes, $id_warehouse)
```

Create a list of order detail for a specified id_order using cart



* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 542](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L542)


#### Arguments
* $order **object**
* $cart **object**
* $id_order_state **mixed**
* $product_list **mixed**
* $id_order_invoice **integer**
* $use_taxes **boolean** - set to false if you don&#039;t want to use taxes
* $id_warehouse **mixed**



### <a name="method-delete"></a>delete

```php
boolean ObjectModelCore::delete()
```

Delete current object from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 521](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L521)




### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage()
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1047](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1047)




### <a name="method-deleteSelection"></a>deleteSelection

```php
boolean ObjectModelCore::deleteSelection(array $selection)
```

Delete several objects from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 559](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L559)


#### Arguments
* $selection **array**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $class, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 757](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L757)


#### Arguments
* $field **mixed**
* $class **mixed**
* $htmlentities **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-duplicateShops"></a>duplicateShops

```php
mixed ObjectModelCore::duplicateShops($id)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1017](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1017)


#### Arguments
* $id **mixed**



### <a name="method-existsInDatabase"></a>existsInDatabase

```php
boolean ObjectModelCore::existsInDatabase(integer $id_entity, string $table)
```

Specify if an ObjectModel is already in database



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1081](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1081)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $id_lang)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L272)


#### Arguments
* $id_lang **integer** - If this parameter is given, only take lang fields



### <a name="method-formatValue"></a>formatValue

```php
mixed ObjectModelCore::formatValue(mixed $value, integer $type, $with_quotes)
```

Format a data



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 319](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L319)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **mixed**



### <a name="method-getDefinition"></a>getDefinition

```php
array ObjectModelCore::getDefinition(string $class, string $field)
```

Get object definition



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1184](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1184)


#### Arguments
* $class **string** - Name of object
* $field **string** - Name of field if we want the definition of one field only



### <a name="method-getDownloadFromHash"></a>getDownloadFromHash

```php
mixed OrderDetailCore::getDownloadFromHash($hash)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderDetail.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L234)


#### Arguments
* $hash **mixed**



### <a name="method-getFieldByLang"></a>getFieldByLang

```php
mixed ObjectModelCore::getFieldByLang($field_name, null $id_lang)
```

Return the field value for the specified language if the field is multilang, else the field value.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1261](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1261)


#### Arguments
* $field_name **mixed**
* $id_lang **null**



### <a name="method-getFields"></a>getFields

```php
array ObjectModelCore::getFields()
```

Prepare fields for ObjectModel class (add, update)
All fields are verified (pSQL, intval.

..)

* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L234)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L249)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 917](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L917)


#### Arguments
* $all **mixed**



### <a name="method-getList"></a>getList

```php
array OrderDetailCore::getList(integer $id_order)
```

Get a detailed order list of an id_order



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderDetail.php line 328](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L328)


#### Arguments
* $id_order **integer**



### <a name="method-getStockState"></a>getStockState

```php
array OrderDetailCore::getStockState()
```

Get the state of the current stock product



* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 562](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L562)




### <a name="method-getTaxCalculator"></a>getTaxCalculator

```php
\TaxCalculator OrderDetailCore::getTaxCalculator()
```

Returns the tax calculator associated to this order detail.



* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 260](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L260)




### <a name="method-getTaxCalculatorStatic"></a>getTaxCalculatorStatic

```php
\TaxCalculator OrderDetailCore::getTaxCalculatorStatic(integer $id_order_detail)
```

Return the tax calculator associated to this order_detail



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderDetail.php line 271](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L271)


#### Arguments
* $id_order_detail **integer**



### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields($fields_array)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 595](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L595)


#### Arguments
* $fields_array **mixed**



### <a name="method-getValidationRules"></a>getValidationRules

```php
array ObjectModelCore::getValidationRules(string $class)
```

Returns object validation rules (fields validity)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L130)


#### Arguments
* $class **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed ObjectModelCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 890](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L890)


#### Arguments
* $sql_join **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**



### <a name="method-getWebserviceParameters"></a>getWebserviceParameters

```php
mixed ObjectModelCore::getWebserviceParameters($ws_params_attribute_name)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 816](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L816)


#### Arguments
* $ws_params_attribute_name **mixed**



### <a name="method-getWsTaxes"></a>getWsTaxes

```php
mixed OrderDetailCore::getWsTaxes()
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 586](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L586)




### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1116](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1116)


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
* Source: [classes/ObjectModel.php line 1135](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1135)


#### Arguments
* $class **string** - Class of objects to hydrate
* $datas **array** - List of data (multi-dimensional array)
* $id_lang **integer**



### <a name="method-incrementDownload"></a>incrementDownload

```php
mixed OrderDetailCore::incrementDownload($id_order_detail, $increment)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderDetail.php line 246](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L246)


#### Arguments
* $id_order_detail **mixed**
* $increment **mixed**



### <a name="method-isAssociatedToGroupShop"></a>isAssociatedToGroupShop

```php
boolean ObjectModelCore::isAssociatedToGroupShop(integer $id_group_shop)
```

Check if current object is associated to a group shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1003](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1003)


#### Arguments
* $id_group_shop **integer**



### <a name="method-isAssociatedToShop"></a>isAssociatedToShop

```php
boolean ObjectModelCore::isAssociatedToShop(integer $id_shop)
```

Check if current object is associated to a shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 954](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L954)


#### Arguments
* $id_shop **integer**



### <a name="method-isCurrentlyUsed"></a>isCurrentlyUsed

```php
boolean ObjectModelCore::isCurrentlyUsed(string $table, boolean $has_active_column)
```

This method is allow to know if a entity is currently used



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1099](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1099)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1037](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1037)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fields_array, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 611](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L611)


#### Arguments
* $fields **mixed**
* $fields_array **mixed**
* $id_language **mixed**



### <a name="method-save"></a>save

```php
boolean ObjectModelCore::save(boolean $null_values, boolean $autodate)
```

Save current object to database (add or update)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L360)


#### Arguments
* $null_values **boolean**
* $autodate **boolean**



### <a name="method-saveTaxCalculator"></a>saveTaxCalculator

```php
boolean OrderDetailCore::saveTaxCalculator()
```

Save the tax calculator



* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 296](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L296)




### <a name="method-setDefinitionRetrocompatibility"></a>setDefinitionRetrocompatibility

```php
mixed ObjectModelCore::setDefinitionRetrocompatibility()
```

Retrocompatibility for classes without $definition static
Remove this in 1.6 !



* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1207](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1207)




### <a name="method-setDetailProductPrice"></a>setDetailProductPrice

```php
mixed OrderDetailCore::setDetailProductPrice(object $order, object $cart, array $product)
```

Set detailed product price to the order detail



* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 432](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L432)


#### Arguments
* $order **object**
* $cart **object**
* $product **array**



### <a name="method-setProductTax"></a>setProductTax

```php
mixed OrderDetailCore::setProductTax(object $order, array $product)
```

Apply tax to the product



* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 380](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L380)


#### Arguments
* $order **object**
* $product **array**



### <a name="method-setShippingCost"></a>setShippingCost

```php
mixed OrderDetailCore::setShippingCost(\Order $order, $product)
```

Set the additional shipping information



* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 573](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L573)


#### Arguments
* $order **[Order](class.OrderCore.md)**
* $product **mixed**



### <a name="method-setSpecificPrice"></a>setSpecificPrice

```php
mixed OrderDetailCore::setSpecificPrice(object $order)
```

Set specific price of the product



* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 404](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L404)


#### Arguments
* $order **object**



### <a name="method-setVirtualProductInformation"></a>setVirtualProductInformation

```php
mixed OrderDetailCore::setVirtualProductInformation($product)
```





* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 342](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/order/OrderDetail.php#L342)


#### Arguments
* $product **mixed**



### <a name="method-toggleStatus"></a>toggleStatus

```php
boolean ObjectModelCore::toggleStatus()
```

Toggle object status in database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 575](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L575)




### <a name="method-update"></a>update

```php
boolean ObjectModelCore::update(boolean $null_values)
```

Update current object to database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 446](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L446)


#### Arguments
* $null_values **boolean**



### <a name="method-validateControler"></a>validateControler

```php
mixed ObjectModelCore::validateControler($htmlentities)
```

TODO: refactor rename all calls to this to validateController



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 772](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L772)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 778](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L778)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateField"></a>validateField

```php
boolean|string ObjectModelCore::validateField(string $field, mixed $value, integer $id_lang)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 710](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L710)


#### Arguments
* $field **string** - Field name
* $value **mixed** - Field value
* $id_lang **integer**



### <a name="method-validateFields"></a>validateFields

```php
boolean|string ObjectModelCore::validateFields(boolean $die, boolean $error_return)
```

Check for fields validity before database interaction



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 649](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L649)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-validateFieldsLang"></a>validateFieldsLang

```php
boolean|string ObjectModelCore::validateFieldsLang(boolean $die, boolean $error_return)
```

Check for multilingual fields validity before database interaction



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 675](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L675)


#### Arguments
* $die **boolean**
* $error_return **boolean**


