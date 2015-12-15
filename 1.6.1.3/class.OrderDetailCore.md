Class OrderDetailCore
=====================





* Class name: OrderDetailCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/order/OrderDetail.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L27)


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
* [$id_shop](#property-$id_shop)
* [$id_tax_rules_group](#property-$id_tax_rules_group)
* [$id_warehouse](#property-$id_warehouse)
* [$original_product_price](#property-$original_product_price)
* [$original_wholesale_price](#property-$original_wholesale_price)
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
* [$purchase_supplier_price](#property-$purchase_supplier_price)
* [$reduction_amount](#property-$reduction_amount)
* [$reduction_amount_tax_excl](#property-$reduction_amount_tax_excl)
* [$reduction_amount_tax_incl](#property-$reduction_amount_tax_incl)
* [$reduction_percent](#property-$reduction_percent)
* [$specificPrice](#property-$specificPrice)
* [$tax_calculator](#property-$tax_calculator)
* [$tax_computation_method](#property-$tax_computation_method)
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
* [$id_lang](#property-$id_lang)
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
* [add](#method-add)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [associateTo](#method-associateTo)
* [cacheFieldsRequiredDatabase](#method-cacheFieldsRequiredDatabase)
* [checkProductStock](#method-checkProductStock)
* [clearCache](#method-clearCache)
* [create](#method-create)
* [createList](#method-createList)
* [delete](#method-delete)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [disableCache](#method-disableCache)
* [displayFieldName](#method-displayFieldName)
* [duplicateObject](#method-duplicateObject)
* [duplicateShops](#method-duplicateShops)
* [enableCache](#method-enableCache)
* [existsInDatabase](#method-existsInDatabase)
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [getAssociatedShops](#method-getAssociatedShops)
* [getCrossSells](#method-getCrossSells)
* [getDefinition](#method-getDefinition)
* [getDownloadFromHash](#method-getDownloadFromHash)
* [getFieldByLang](#method-getFieldByLang)
* [getFields](#method-getFields)
* [getFieldsLang](#method-getFieldsLang)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFieldsShop](#method-getFieldsShop)
* [getList](#method-getList)
* [getRepositoryClassName](#method-getRepositoryClassName)
* [getStockState](#method-getStockState)
* [getTaxCalculator](#method-getTaxCalculator)
* [getTaxCalculatorStatic](#method-getTaxCalculatorStatic)
* [getTaxList](#method-getTaxList)
* [getTaxListStatic](#method-getTaxListStatic)
* [getTranslationsFields](#method-getTranslationsFields)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [getWholeSalePrice](#method-getWholeSalePrice)
* [getWsTaxes](#method-getWsTaxes)
* [hasMultishopEntries](#method-hasMultishopEntries)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [incrementDownload](#method-incrementDownload)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isLangMultishop](#method-isLangMultishop)
* [isMultiShopField](#method-isMultiShopField)
* [isMultishop](#method-isMultishop)
* [makeTranslationFields](#method-makeTranslationFields)
* [save](#method-save)
* [saveTaxCalculator](#method-saveTaxCalculator)
* [setContext](#method-setContext)
* [setDefinitionRetrocompatibility](#method-setDefinitionRetrocompatibility)
* [setDetailProductPrice](#method-setDetailProductPrice)
* [setFieldsToUpdate](#method-setFieldsToUpdate)
* [setProductTax](#method-setProductTax)
* [setShippingCost](#method-setShippingCost)
* [setSpecificPrice](#method-setSpecificPrice)
* [setVirtualProductInformation](#method-setVirtualProductInformation)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [updateMultishopTable](#method-updateMultishopTable)
* [updateTaxAmount](#method-updateTaxAmount)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateField](#method-validateField)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)
* [validateFieldsRequiredDatabase](#method-validateFieldsRequiredDatabase)




Properties
----------


### <a name="property-$context"></a>$context

```php
protected \Context $context = null
```





* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 248](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L248).


### <a name="property-$customer"></a>$customer

```php
protected \Customer $customer = null
```





* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 245](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L245).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'order_detail', 'primary' => 'id_order_detail', 'fields' => array('id_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_order_invoice' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_warehouse' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_shop' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'product_id' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'product_attribute_id' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'product_name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true), 'product_quantity' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'required' => true), 'product_quantity_in_stock' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'product_quantity_return' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'product_quantity_refunded' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'product_quantity_reinjected' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'product_price' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'reduction_percent' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'reduction_amount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'reduction_amount_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'reduction_amount_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'group_reduction' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'product_quantity_discount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'product_ean13' => array('type' => self::TYPE_STRING, 'validate' => 'isEan13'), 'product_upc' => array('type' => self::TYPE_STRING, 'validate' => 'isUpc'), 'product_reference' => array('type' => self::TYPE_STRING, 'validate' => 'isReference'), 'product_supplier_reference' => array('type' => self::TYPE_STRING, 'validate' => 'isReference'), 'product_weight' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'tax_name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName'), 'tax_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'tax_computation_method' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_tax_rules_group' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'ecotax' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'ecotax_tax_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'discount_quantity_applied' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'download_hash' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName'), 'download_nb' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'download_deadline' => array('type' => self::TYPE_DATE, 'validate' => 'isDateFormat'), 'unit_price_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'unit_price_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_price_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_price_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_shipping_price_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'total_shipping_price_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'purchase_supplier_price' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'original_product_price' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'original_wholesale_price' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/order/OrderDetail.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L164).


### <a name="property-$discount_quantity_applied"></a>$discount_quantity_applied

```php
public integer $discount_quantity_applied
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L123).


### <a name="property-$download_deadline"></a>$download_deadline

```php
public \datetime $download_deadline
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L132).


### <a name="property-$download_hash"></a>$download_hash

```php
public string $download_hash
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L126).


### <a name="property-$download_nb"></a>$download_nb

```php
public integer $download_nb
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L129).


### <a name="property-$ecotax"></a>$ecotax

```php
public float $ecotax
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L117).


### <a name="property-$ecotax_tax_rate"></a>$ecotax_tax_rate

```php
public float $ecotax_tax_rate
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L120).


### <a name="property-$group_reduction"></a>$group_reduction

```php
public float $group_reduction
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L96).


### <a name="property-$id_order"></a>$id_order

```php
public integer $id_order
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L33).


### <a name="property-$id_order_detail"></a>$id_order_detail

```php
public integer $id_order_detail
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L30).


### <a name="property-$id_order_invoice"></a>$id_order_invoice

```php
public integer $id_order_invoice
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L36).


### <a name="property-$id_shop"></a>$id_shop

```php
public integer $id_shop
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L42).


### <a name="property-$id_tax_rules_group"></a>$id_tax_rules_group

```php
public integer $id_tax_rules_group
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L144).


### <a name="property-$id_warehouse"></a>$id_warehouse

```php
public integer $id_warehouse
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L147).


### <a name="property-$original_product_price"></a>$original_product_price

```php
public float $original_product_price
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L69).


### <a name="property-$original_wholesale_price"></a>$original_wholesale_price

```php
public float $original_wholesale_price
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L159).


### <a name="property-$outOfStock"></a>$outOfStock

```php
protected boolean $outOfStock = false
```





* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 233](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L233).


### <a name="property-$product_attribute_id"></a>$product_attribute_id

```php
public integer $product_attribute_id
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L45).


### <a name="property-$product_ean13"></a>$product_ean13

```php
public string $product_ean13
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L102).


### <a name="property-$product_id"></a>$product_id

```php
public integer $product_id
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L39).


### <a name="property-$product_name"></a>$product_name

```php
public string $product_name
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L48).


### <a name="property-$product_price"></a>$product_price

```php
public float $product_price
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L66).


### <a name="property-$product_quantity"></a>$product_quantity

```php
public integer $product_quantity
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L51).


### <a name="property-$product_quantity_discount"></a>$product_quantity_discount

```php
public float $product_quantity_discount
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L99).


### <a name="property-$product_quantity_in_stock"></a>$product_quantity_in_stock

```php
public integer $product_quantity_in_stock
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L54).


### <a name="property-$product_quantity_refunded"></a>$product_quantity_refunded

```php
public integer $product_quantity_refunded
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L60).


### <a name="property-$product_quantity_reinjected"></a>$product_quantity_reinjected

```php
public integer $product_quantity_reinjected
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L63).


### <a name="property-$product_quantity_return"></a>$product_quantity_return

```php
public integer $product_quantity_return
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L57).


### <a name="property-$product_reference"></a>$product_reference

```php
public string $product_reference
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L108).


### <a name="property-$product_supplier_reference"></a>$product_supplier_reference

```php
public string $product_supplier_reference
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L111).


### <a name="property-$product_upc"></a>$product_upc

```php
public string $product_upc
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L105).


### <a name="property-$product_weight"></a>$product_weight

```php
public float $product_weight
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L114).


### <a name="property-$purchase_supplier_price"></a>$purchase_supplier_price

```php
public float $purchase_supplier_price
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L156).


### <a name="property-$reduction_amount"></a>$reduction_amount

```php
public float $reduction_amount
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L87).


### <a name="property-$reduction_amount_tax_excl"></a>$reduction_amount_tax_excl

```php
public float $reduction_amount_tax_excl
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L90).


### <a name="property-$reduction_amount_tax_incl"></a>$reduction_amount_tax_incl

```php
public float $reduction_amount_tax_incl
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L93).


### <a name="property-$reduction_percent"></a>$reduction_percent

```php
public float $reduction_percent
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L84).


### <a name="property-$specificPrice"></a>$specificPrice

```php
protected \Address $specificPrice = null
```





* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 242](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L242).


### <a name="property-$tax_calculator"></a>$tax_calculator

```php
protected \TaxCalculator $tax_calculator = null
```





* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 236](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L236).


### <a name="property-$tax_computation_method"></a>$tax_computation_method

```php
public float $tax_computation_method
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L141).


### <a name="property-$tax_name"></a>$tax_name

```php
public string $tax_name
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L135).


### <a name="property-$tax_rate"></a>$tax_rate

```php
public float $tax_rate
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L138).


### <a name="property-$total_price_tax_excl"></a>$total_price_tax_excl

```php
public float $total_price_tax_excl
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L81).


### <a name="property-$total_price_tax_incl"></a>$total_price_tax_incl

```php
public float $total_price_tax_incl
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L78).


### <a name="property-$total_shipping_price_tax_excl"></a>$total_shipping_price_tax_excl

```php
public float $total_shipping_price_tax_excl
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L150).


### <a name="property-$total_shipping_price_tax_incl"></a>$total_shipping_price_tax_incl

```php
public float $total_shipping_price_tax_incl
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L153).


### <a name="property-$unit_price_tax_excl"></a>$unit_price_tax_excl

```php
public float $unit_price_tax_excl
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L75).


### <a name="property-$unit_price_tax_incl"></a>$unit_price_tax_incl

```php
public float $unit_price_tax_incl
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L72).


### <a name="property-$vat_address"></a>$vat_address

```php
protected \Address $vat_address = null
```





* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 239](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L239).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_order' => array('xlink_resource' => 'orders'), 'product_id' => array('xlink_resource' => 'products'), 'product_attribute_id' => array('xlink_resource' => 'combinations'), 'product_quantity_reinjected' => array(), 'group_reduction' => array(), 'discount_quantity_applied' => array(), 'download_hash' => array(), 'download_deadline' => array()), 'hidden_fields' => array('tax_rate', 'tax_name'), 'associations' => array('taxes' => array('resource' => 'tax', 'getter' => 'getWsTaxes', 'setter' => false, 'fields' => array('id' => array()))))
```





* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 214](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L214).


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


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L58).


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
mixed OrderDetailCore::__construct($id, $id_lang, $context)
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 250](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L250)


#### Arguments
* $id **mixed**
* $id_lang **mixed**
* $context **mixed**



### <a name="method-add"></a>add

```php
mixed OrderDetailCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 789](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L789)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



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



### <a name="method-checkProductStock"></a>checkProductStock

```php
mixed OrderDetailCore::checkProductStock(array $product, integer $id_order_state)
```

Check the order status



* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 468](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L468)


#### Arguments
* $product **array**
* $id_order_state **integer**



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



### <a name="method-create"></a>create

```php
mixed OrderDetailCore::create(object $order, object $cart, array $product, $id_order_state, integer $id_order_invoice, boolean $use_taxes, $id_warehouse)
```

Create an order detail liable to an id_order



* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 611](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L611)


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
* Source: [classes/order/OrderDetail.php line 669](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L669)


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
mixed OrderDetailCore::delete()
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 265](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L265)




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



### <a name="method-getAssociatedShops"></a>getAssociatedShops

```php
array ObjectModelCore::getAssociatedShops()
```

Gets the list of associated shop IDs



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1499](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1499)




### <a name="method-getCrossSells"></a>getCrossSells

```php
mixed OrderDetailCore::getCrossSells($id_product, $id_lang, $limit)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderDetail.php line 725](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L725)


#### Arguments
* $id_product **mixed**
* $id_lang **mixed**
* $limit **mixed**



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



### <a name="method-getDownloadFromHash"></a>getDownloadFromHash

```php
mixed OrderDetailCore::getDownloadFromHash($hash)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderDetail.php line 283](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L283)


#### Arguments
* $hash **mixed**



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
array ObjectModelCore::getFields()
```

Prepare fields for ObjectModel class (add, update)
All fields are verified (pSQL, intval, .

..)

* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 244](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L244)




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




### <a name="method-getList"></a>getList

```php
array OrderDetailCore::getList(integer $id_order)
```

Get a detailed order list of an id_order



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderDetail.php line 427](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L427)


#### Arguments
* $id_order **integer**



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




### <a name="method-getStockState"></a>getStockState

```php
array OrderDetailCore::getStockState()
```

Get the state of the current stock product



* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 690](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L690)




### <a name="method-getTaxCalculator"></a>getTaxCalculator

```php
\TaxCalculator OrderDetailCore::getTaxCalculator()
```

Returns the tax calculator associated to this order detail.



* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 310](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L310)




### <a name="method-getTaxCalculatorStatic"></a>getTaxCalculatorStatic

```php
\TaxCalculator OrderDetailCore::getTaxCalculatorStatic(integer $id_order_detail)
```

Return the tax calculator associated to this order_detail



* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderDetail.php line 321](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L321)


#### Arguments
* $id_order_detail **integer**



### <a name="method-getTaxList"></a>getTaxList

```php
mixed OrderDetailCore::getTaxList()
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 432](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L432)




### <a name="method-getTaxListStatic"></a>getTaxListStatic

```php
mixed OrderDetailCore::getTaxListStatic($id_order_detail)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderDetail.php line 437](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L437)


#### Arguments
* $id_order_detail **mixed**



### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
array ObjectModelCore::getTranslationsFields(array $fields_array)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 831](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L831)


#### Arguments
* $fields_array **array**



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



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
array|null ObjectModelCore::getWebserviceObjectList(string $sql_join, string $sql_filter, string $sql_sort, string $sql_limit)
```

Returns webservice object list.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1279](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1279)


#### Arguments
* $sql_join **string**
* $sql_filter **string**
* $sql_sort **string**
* $sql_limit **string**



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



### <a name="method-getWholeSalePrice"></a>getWholeSalePrice

```php
mixed OrderDetailCore::getWholeSalePrice()
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 806](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L806)




### <a name="method-getWsTaxes"></a>getWsTaxes

```php
mixed OrderDetailCore::getWsTaxes()
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 715](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L715)




### <a name="method-hasMultishopEntries"></a>hasMultishopEntries

```php
boolean ObjectModelCore::hasMultishopEntries()
```

Checks if there is more than one entry in associated shop table for current object.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1550](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1550)




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



### <a name="method-incrementDownload"></a>incrementDownload

```php
mixed OrderDetailCore::incrementDownload($id_order_detail, $increment)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/order/OrderDetail.php line 296](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L296)


#### Arguments
* $id_order_detail **mixed**
* $increment **mixed**



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



### <a name="method-saveTaxCalculator"></a>saveTaxCalculator

```php
boolean OrderDetailCore::saveTaxCalculator(\Order $order, $replace)
```

Save the tax calculator



* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 349](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L349)


#### Arguments
* $order **[Order](class.OrderCore.md)**
* $replace **mixed**



### <a name="method-setContext"></a>setContext

```php
mixed OrderDetailCore::setContext($id_shop)
```





* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 276](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L276)


#### Arguments
* $id_shop **mixed**



### <a name="method-setDefinitionRetrocompatibility"></a>setDefinitionRetrocompatibility

```php
mixed ObjectModelCore::setDefinitionRetrocompatibility()
```

Retrocompatibility for classes without $definition static



* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1855](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/ObjectModel.php#L1855)




### <a name="method-setDetailProductPrice"></a>setDetailProductPrice

```php
mixed OrderDetailCore::setDetailProductPrice(object $order, object $cart, array $product)
```

Set detailed product price to the order detail



* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 557](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L557)


#### Arguments
* $order **object**
* $cart **object**
* $product **array**



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



### <a name="method-setProductTax"></a>setProductTax

```php
mixed OrderDetailCore::setProductTax(object $order, array $product)
```

Apply tax to the product



* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 492](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L492)


#### Arguments
* $order **object**
* $product **array**



### <a name="method-setShippingCost"></a>setShippingCost

```php
mixed OrderDetailCore::setShippingCost(\Order $order, $product)
```

Set the additional shipping information



* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 701](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L701)


#### Arguments
* $order **[Order](class.OrderCore.md)**
* $product **mixed**



### <a name="method-setSpecificPrice"></a>setSpecificPrice

```php
mixed OrderDetailCore::setSpecificPrice(object $order, $product)
```

Set specific price of the product



* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 516](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L516)


#### Arguments
* $order **object**
* $product **mixed**



### <a name="method-setVirtualProductInformation"></a>setVirtualProductInformation

```php
mixed OrderDetailCore::setVirtualProductInformation($product)
```





* Visibility: **protected**
* Source: [classes/order/OrderDetail.php line 448](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L448)


#### Arguments
* $product **mixed**



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



### <a name="method-updateTaxAmount"></a>updateTaxAmount

```php
mixed OrderDetailCore::updateTaxAmount($order)
```





* Visibility: **public**
* Source: [classes/order/OrderDetail.php line 412](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/order/OrderDetail.php#L412)


#### Arguments
* $order **mixed**



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


