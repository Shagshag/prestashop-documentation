Class ProductCore
=====================





* Class name: ProductCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Product.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L36)


Contents
--------

### Constants

* [CUSTOMIZE_FILE](#constant-CUSTOMIZE_FILE)
* [CUSTOMIZE_TEXTFIELD](#constant-CUSTOMIZE_TEXTFIELD)
* [PTYPE_PACK](#constant-PTYPE_PACK)
* [PTYPE_SIMPLE](#constant-PTYPE_SIMPLE)
* [PTYPE_VIRTUAL](#constant-PTYPE_VIRTUAL)

### Properties

* [$_cacheFeatures](#property-$_cacheFeatures)
* [$_cart_quantity](#property-$_cart_quantity)
* [$_frontFeaturesCache](#property-$_frontFeaturesCache)
* [$_incat](#property-$_incat)
* [$_prices](#property-$_prices)
* [$_pricesLevel2](#property-$_pricesLevel2)
* [$_taxCalculationMethod](#property-$_taxCalculationMethod)
* [$_tax_rules_group](#property-$_tax_rules_group)
* [$active](#property-$active)
* [$additional_shipping_cost](#property-$additional_shipping_cost)
* [$advanced_stock_management](#property-$advanced_stock_management)
* [$available_date](#property-$available_date)
* [$available_for_order](#property-$available_for_order)
* [$available_later](#property-$available_later)
* [$available_now](#property-$available_now)
* [$base_price](#property-$base_price)
* [$cacheStock](#property-$cacheStock)
* [$cache_default_attribute](#property-$cache_default_attribute)
* [$cache_has_attachments](#property-$cache_has_attachments)
* [$cache_is_pack](#property-$cache_is_pack)
* [$category](#property-$category)
* [$condition](#property-$condition)
* [$customizable](#property-$customizable)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$depends_on_stock](#property-$depends_on_stock)
* [$depth](#property-$depth)
* [$description](#property-$description)
* [$description_short](#property-$description_short)
* [$ean13](#property-$ean13)
* [$ecotax](#property-$ecotax)
* [$height](#property-$height)
* [$id_category_default](#property-$id_category_default)
* [$id_color_default](#property-$id_color_default)
* [$id_manufacturer](#property-$id_manufacturer)
* [$id_pack_product_attribute](#property-$id_pack_product_attribute)
* [$id_product_redirected](#property-$id_product_redirected)
* [$id_shop_default](#property-$id_shop_default)
* [$id_supplier](#property-$id_supplier)
* [$id_tax_rules_group](#property-$id_tax_rules_group)
* [$indexed](#property-$indexed)
* [$isFullyLoaded](#property-$isFullyLoaded)
* [$is_virtual](#property-$is_virtual)
* [$link_rewrite](#property-$link_rewrite)
* [$location](#property-$location)
* [$manufacturer_name](#property-$manufacturer_name)
* [$meta_description](#property-$meta_description)
* [$meta_keywords](#property-$meta_keywords)
* [$meta_title](#property-$meta_title)
* [$minimal_quantity](#property-$minimal_quantity)
* [$name](#property-$name)
* [$new](#property-$new)
* [$on_sale](#property-$on_sale)
* [$online_only](#property-$online_only)
* [$out_of_stock](#property-$out_of_stock)
* [$pack_stock_type](#property-$pack_stock_type)
* [$price](#property-$price)
* [$producPropertiesCache](#property-$producPropertiesCache)
* [$quantity](#property-$quantity)
* [$quantity_discount](#property-$quantity_discount)
* [$redirect_type](#property-$redirect_type)
* [$reference](#property-$reference)
* [$show_price](#property-$show_price)
* [$specificPrice](#property-$specificPrice)
* [$supplier_name](#property-$supplier_name)
* [$supplier_reference](#property-$supplier_reference)
* [$tags](#property-$tags)
* [$tax_name](#property-$tax_name)
* [$tax_rate](#property-$tax_rate)
* [$text_fields](#property-$text_fields)
* [$unit_price](#property-$unit_price)
* [$unit_price_ratio](#property-$unit_price_ratio)
* [$unity](#property-$unity)
* [$upc](#property-$upc)
* [$uploadable_files](#property-$uploadable_files)
* [$visibility](#property-$visibility)
* [$webserviceParameters](#property-$webserviceParameters)
* [$weight](#property-$weight)
* [$wholesale_price](#property-$wholesale_price)
* [$width](#property-$width)
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
* [$id_shop](#property-$id_shop)
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
* [_checkLabelField](#method-_checkLabelField)
* [_createLabel](#method-_createLabel)
* [_deleteOldLabels](#method-_deleteOldLabels)
* [_getAttributeImageAssociations](#method-_getAttributeImageAssociations)
* [_getCustomizationFieldsNLabels](#method-_getCustomizationFieldsNLabels)
* [_getProductIdByDate](#method-_getProductIdByDate)
* [add](#method-add)
* [addAttribute](#method-addAttribute)
* [addAttributeCombinaison](#method-addAttributeCombinaison)
* [addAttributeCombinationMultiple](#method-addAttributeCombinationMultiple)
* [addCombinationEntity](#method-addCombinationEntity)
* [addCustomizationPrice](#method-addCustomizationPrice)
* [addFeatureProductImport](#method-addFeatureProductImport)
* [addFeaturesCustomToDB](#method-addFeaturesCustomToDB)
* [addFeaturesToDB](#method-addFeaturesToDB)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [addProductAttribute](#method-addProductAttribute)
* [addProductAttributeMultiple](#method-addProductAttributeMultiple)
* [addStockMvt](#method-addStockMvt)
* [addSupplierReference](#method-addSupplierReference)
* [addToCategories](#method-addToCategories)
* [addWs](#method-addWs)
* [associateTo](#method-associateTo)
* [cacheFieldsRequiredDatabase](#method-cacheFieldsRequiredDatabase)
* [cacheFrontFeatures](#method-cacheFrontFeatures)
* [cacheProductsFeatures](#method-cacheProductsFeatures)
* [changeAccessories](#method-changeAccessories)
* [checkAccess](#method-checkAccess)
* [checkAccessStatic](#method-checkAccessStatic)
* [checkDefaultAttributes](#method-checkDefaultAttributes)
* [checkQty](#method-checkQty)
* [cleanPositions](#method-cleanPositions)
* [clearCache](#method-clearCache)
* [convertAndFormatPrice](#method-convertAndFormatPrice)
* [convertPrice](#method-convertPrice)
* [convertPriceWithCurrency](#method-convertPriceWithCurrency)
* [createLabels](#method-createLabels)
* [defineProductImage](#method-defineProductImage)
* [delete](#method-delete)
* [deleteAccessories](#method-deleteAccessories)
* [deleteAttachments](#method-deleteAttachments)
* [deleteAttributeCombinaison](#method-deleteAttributeCombinaison)
* [deleteAttributeCombination](#method-deleteAttributeCombination)
* [deleteAttributesImpacts](#method-deleteAttributesImpacts)
* [deleteCartProducts](#method-deleteCartProducts)
* [deleteCategories](#method-deleteCategories)
* [deleteCategory](#method-deleteCategory)
* [deleteCustomization](#method-deleteCustomization)
* [deleteDefaultAttributes](#method-deleteDefaultAttributes)
* [deleteDownload](#method-deleteDownload)
* [deleteFeatures](#method-deleteFeatures)
* [deleteFromAccessories](#method-deleteFromAccessories)
* [deleteFromCartRules](#method-deleteFromCartRules)
* [deleteFromSupplier](#method-deleteFromSupplier)
* [deleteImage](#method-deleteImage)
* [deleteImages](#method-deleteImages)
* [deletePack](#method-deletePack)
* [deleteProductAttributes](#method-deleteProductAttributes)
* [deleteProductFeatures](#method-deleteProductFeatures)
* [deleteProductSale](#method-deleteProductSale)
* [deleteSceneProducts](#method-deleteSceneProducts)
* [deleteSearchIndexes](#method-deleteSearchIndexes)
* [deleteSelection](#method-deleteSelection)
* [deleteTags](#method-deleteTags)
* [deleteWsTags](#method-deleteWsTags)
* [disableCache](#method-disableCache)
* [displayFieldName](#method-displayFieldName)
* [displayWtPrice](#method-displayWtPrice)
* [displayWtPriceWithCurrency](#method-displayWtPriceWithCurrency)
* [duplicateAccessories](#method-duplicateAccessories)
* [duplicateAttachments](#method-duplicateAttachments)
* [duplicateAttributes](#method-duplicateAttributes)
* [duplicateCustomizationFields](#method-duplicateCustomizationFields)
* [duplicateDownload](#method-duplicateDownload)
* [duplicateFeatures](#method-duplicateFeatures)
* [duplicateObject](#method-duplicateObject)
* [duplicateShops](#method-duplicateShops)
* [duplicateSpecificPrices](#method-duplicateSpecificPrices)
* [duplicateSuppliers](#method-duplicateSuppliers)
* [duplicateTags](#method-duplicateTags)
* [enableCache](#method-enableCache)
* [existsInDatabase](#method-existsInDatabase)
* [existsRefInDatabase](#method-existsRefInDatabase)
* [flushPriceCache](#method-flushPriceCache)
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [generateMultipleCombinations](#method-generateMultipleCombinations)
* [getAccessories](#method-getAccessories)
* [getAccessoriesLight](#method-getAccessoriesLight)
* [getAccessoryById](#method-getAccessoryById)
* [getAllCustomizedDatas](#method-getAllCustomizedDatas)
* [getAnchor](#method-getAnchor)
* [getAssociatedShops](#method-getAssociatedShops)
* [getAttachments](#method-getAttachments)
* [getAttachmentsStatic](#method-getAttachmentsStatic)
* [getAttributeCombinaisons](#method-getAttributeCombinaisons)
* [getAttributeCombinations](#method-getAttributeCombinations)
* [getAttributeCombinationsById](#method-getAttributeCombinationsById)
* [getAttributesColorList](#method-getAttributesColorList)
* [getAttributesGroups](#method-getAttributesGroups)
* [getAttributesImpacts](#method-getAttributesImpacts)
* [getAttributesInformationsByProduct](#method-getAttributesInformationsByProduct)
* [getAttributesParams](#method-getAttributesParams)
* [getAttributesResume](#method-getAttributesResume)
* [getAvailableDate](#method-getAvailableDate)
* [getCarriers](#method-getCarriers)
* [getCategories](#method-getCategories)
* [getColorsListCacheId](#method-getColorsListCacheId)
* [getCombinationImageById](#method-getCombinationImageById)
* [getCombinationImages](#method-getCombinationImages)
* [getCover](#method-getCover)
* [getCoverWs](#method-getCoverWs)
* [getCustomizationFieldIds](#method-getCustomizationFieldIds)
* [getCustomizationFields](#method-getCustomizationFields)
* [getDefaultAttribute](#method-getDefaultAttribute)
* [getDefaultCategory](#method-getDefaultCategory)
* [getDefaultIdProductAttribute](#method-getDefaultIdProductAttribute)
* [getDefinition](#method-getDefinition)
* [getFeatures](#method-getFeatures)
* [getFeaturesStatic](#method-getFeaturesStatic)
* [getFieldByLang](#method-getFieldByLang)
* [getFields](#method-getFields)
* [getFieldsLang](#method-getFieldsLang)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFieldsShop](#method-getFieldsShop)
* [getFrontFeatures](#method-getFrontFeatures)
* [getFrontFeaturesStatic](#method-getFrontFeaturesStatic)
* [getIdByEan13](#method-getIdByEan13)
* [getIdProductAttributeMostExpensive](#method-getIdProductAttributeMostExpensive)
* [getIdTaxRulesGroup](#method-getIdTaxRulesGroup)
* [getIdTaxRulesGroupByIdProduct](#method-getIdTaxRulesGroupByIdProduct)
* [getIdTaxRulesGroupMostUsed](#method-getIdTaxRulesGroupMostUsed)
* [getImages](#method-getImages)
* [getLink](#method-getLink)
* [getNewProducts](#method-getNewProducts)
* [getNoPackPrice](#method-getNoPackPrice)
* [getParentCategories](#method-getParentCategories)
* [getPrice](#method-getPrice)
* [getPriceStatic](#method-getPriceStatic)
* [getPriceWithoutReduct](#method-getPriceWithoutReduct)
* [getPricesDrop](#method-getPricesDrop)
* [getProductAttributePrice](#method-getProductAttributePrice)
* [getProductAttributesIds](#method-getProductAttributesIds)
* [getProductCategories](#method-getProductCategories)
* [getProductCategoriesFull](#method-getProductCategoriesFull)
* [getProductName](#method-getProductName)
* [getProductProperties](#method-getProductProperties)
* [getProducts](#method-getProducts)
* [getProductsProperties](#method-getProductsProperties)
* [getPublicPrice](#method-getPublicPrice)
* [getQuantity](#method-getQuantity)
* [getRandomSpecial](#method-getRandomSpecial)
* [getRealQuantity](#method-getRealQuantity)
* [getRepositoryClassName](#method-getRepositoryClassName)
* [getRequiredCustomizableFields](#method-getRequiredCustomizableFields)
* [getRequiredCustomizableFieldsStatic](#method-getRequiredCustomizableFieldsStatic)
* [getShopsByProduct](#method-getShopsByProduct)
* [getSimpleProducts](#method-getSimpleProducts)
* [getStockMvts](#method-getStockMvts)
* [getTags](#method-getTags)
* [getTaxCalculationMethod](#method-getTaxCalculationMethod)
* [getTaxesInformations](#method-getTaxesInformations)
* [getTaxesRate](#method-getTaxesRate)
* [getTranslationsFields](#method-getTranslationsFields)
* [getType](#method-getType)
* [getUrlRewriteInformations](#method-getUrlRewriteInformations)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [getWsAccessories](#method-getWsAccessories)
* [getWsCategories](#method-getWsCategories)
* [getWsCombinations](#method-getWsCombinations)
* [getWsDefaultCombination](#method-getWsDefaultCombination)
* [getWsImages](#method-getWsImages)
* [getWsManufacturerName](#method-getWsManufacturerName)
* [getWsPositionInCategory](#method-getWsPositionInCategory)
* [getWsProductBundle](#method-getWsProductBundle)
* [getWsProductFeatures](#method-getWsProductFeatures)
* [getWsProductOptionValues](#method-getWsProductOptionValues)
* [getWsStockAvailables](#method-getWsStockAvailables)
* [getWsTags](#method-getWsTags)
* [getWsType](#method-getWsType)
* [hasAllRequiredCustomizableFields](#method-hasAllRequiredCustomizableFields)
* [hasAttributes](#method-hasAttributes)
* [hasAttributesInOtherShops](#method-hasAttributesInOtherShops)
* [hasMultishopEntries](#method-hasMultishopEntries)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [idIsOnCategoryId](#method-idIsOnCategoryId)
* [initPricesComputation](#method-initPricesComputation)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isAvailableWhenOutOfStock](#method-isAvailableWhenOutOfStock)
* [isColorUnavailable](#method-isColorUnavailable)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isDiscounted](#method-isDiscounted)
* [isLangMultishop](#method-isLangMultishop)
* [isMultiShopField](#method-isMultiShopField)
* [isMultishop](#method-isMultishop)
* [isNew](#method-isNew)
* [loadStockData](#method-loadStockData)
* [makeTranslationFields](#method-makeTranslationFields)
* [modifierWsLinkRewrite](#method-modifierWsLinkRewrite)
* [priceCalculation](#method-priceCalculation)
* [productAttributeExists](#method-productAttributeExists)
* [reinjectQuantities](#method-reinjectQuantities)
* [resetEcoTax](#method-resetEcoTax)
* [save](#method-save)
* [searchByName](#method-searchByName)
* [setAdvancedStockManagement](#method-setAdvancedStockManagement)
* [setAvailableDate](#method-setAvailableDate)
* [setCarriers](#method-setCarriers)
* [setCoverWs](#method-setCoverWs)
* [setDefaultAttribute](#method-setDefaultAttribute)
* [setDefinitionRetrocompatibility](#method-setDefinitionRetrocompatibility)
* [setFieldsToUpdate](#method-setFieldsToUpdate)
* [setGroupReduction](#method-setGroupReduction)
* [setPackStockType](#method-setPackStockType)
* [setWsAccessories](#method-setWsAccessories)
* [setWsCategories](#method-setWsCategories)
* [setWsCombinations](#method-setWsCombinations)
* [setWsDefaultCombination](#method-setWsDefaultCombination)
* [setWsPositionInCategory](#method-setWsPositionInCategory)
* [setWsProductBundle](#method-setWsProductBundle)
* [setWsProductFeatures](#method-setWsProductFeatures)
* [setWsTags](#method-setWsTags)
* [setWsType](#method-setWsType)
* [sqlStock](#method-sqlStock)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [updateAttribute](#method-updateAttribute)
* [updateCacheAttachment](#method-updateCacheAttachment)
* [updateCategories](#method-updateCategories)
* [updateDefaultAttribute](#method-updateDefaultAttribute)
* [updateIsVirtual](#method-updateIsVirtual)
* [updateLabels](#method-updateLabels)
* [updateMultishopTable](#method-updateMultishopTable)
* [updatePosition](#method-updatePosition)
* [updateProductAttribute](#method-updateProductAttribute)
* [updateQuantity](#method-updateQuantity)
* [updateQuantityProductWithAttributeQuantity](#method-updateQuantityProductWithAttributeQuantity)
* [updateWs](#method-updateWs)
* [useAdvancedStockManagement](#method-useAdvancedStockManagement)
* [usesAdvancedStockManagement](#method-usesAdvancedStockManagement)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateField](#method-validateField)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)
* [validateFieldsRequiredDatabase](#method-validateFieldsRequiredDatabase)


Constants
----------


### <a name="constant-CUSTOMIZE_FILE"></a>CUSTOMIZE_FILE

```php
const CUSTOMIZE_FILE = 0
```





* Source: [classes/Product.php line 465](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L465).


### <a name="constant-CUSTOMIZE_TEXTFIELD"></a>CUSTOMIZE_TEXTFIELD

```php
const CUSTOMIZE_TEXTFIELD = 1
```





* Source: [classes/Product.php line 466](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L466).


### <a name="constant-PTYPE_PACK"></a>PTYPE_PACK

```php
const PTYPE_PACK = 1
```





* Source: [classes/Product.php line 472](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L472).


### <a name="constant-PTYPE_SIMPLE"></a>PTYPE_SIMPLE

```php
const PTYPE_SIMPLE = 0
```

Note:  prefix is "PTYPE" because TYPE_ is used in ObjectModel (definition)



* Source: [classes/Product.php line 471](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L471).


### <a name="constant-PTYPE_VIRTUAL"></a>PTYPE_VIRTUAL

```php
const PTYPE_VIRTUAL = 2
```





* Source: [classes/Product.php line 473](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L473).


Properties
----------


### <a name="property-$_cacheFeatures"></a>$_cacheFeatures

```php
protected mixed $_cacheFeatures = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Product.php line 254](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L254).


### <a name="property-$_cart_quantity"></a>$_cart_quantity

```php
protected array $_cart_quantity = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Product.php line 251](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L251).


### <a name="property-$_frontFeaturesCache"></a>$_frontFeaturesCache

```php
protected mixed $_frontFeaturesCache = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Product.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L255).


### <a name="property-$_incat"></a>$_incat

```php
protected mixed $_incat = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Product.php line 245](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L245).


### <a name="property-$_prices"></a>$_prices

```php
protected mixed $_prices = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Product.php line 243](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L243).


### <a name="property-$_pricesLevel2"></a>$_pricesLevel2

```php
protected mixed $_pricesLevel2 = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Product.php line 244](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L244).


### <a name="property-$_taxCalculationMethod"></a>$_taxCalculationMethod

```php
public mixed $_taxCalculationMethod = null
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Product.php line 242](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L242).


### <a name="property-$_tax_rules_group"></a>$_tax_rules_group

```php
protected mixed $_tax_rules_group = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Product.php line 253](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L253).


### <a name="property-$active"></a>$active

```php
public boolean $active = true
```





* Visibility: **public**
* Source: [classes/Product.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L167).


### <a name="property-$additional_shipping_cost"></a>$additional_shipping_cost

```php
public float $additional_shipping_cost
```





* Visibility: **public**
* Source: [classes/Product.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L89).


### <a name="property-$advanced_stock_management"></a>$advanced_stock_management

```php
public boolean $advanced_stock_management
```





* Visibility: **public**
* Source: [classes/Product.php line 220](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L220).


### <a name="property-$available_date"></a>$available_date

```php
public string $available_date = '0000-00-00'
```





* Visibility: **public**
* Source: [classes/Product.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L179).


### <a name="property-$available_for_order"></a>$available_for_order

```php
public boolean $available_for_order = true
```





* Visibility: **public**
* Source: [classes/Product.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L176).


### <a name="property-$available_later"></a>$available_later

```php
public string $available_later
```





* Visibility: **public**
* Source: [classes/Product.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L81).


### <a name="property-$available_now"></a>$available_now

```php
public string $available_now
```





* Visibility: **public**
* Source: [classes/Product.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L78).


### <a name="property-$base_price"></a>$base_price

```php
public float $base_price
```





* Visibility: **public**
* Source: [classes/Product.php line 206](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L206).


### <a name="property-$cacheStock"></a>$cacheStock

```php
protected array $cacheStock = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Product.php line 259](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L259).


### <a name="property-$cache_default_attribute"></a>$cache_default_attribute

```php
public mixed $cache_default_attribute
```





* Visibility: **public**
* Source: [classes/Product.php line 230](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L230).


### <a name="property-$cache_has_attachments"></a>$cache_has_attachments

```php
public mixed $cache_has_attachments
```





* Visibility: **public**
* Source: [classes/Product.php line 227](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L227).


### <a name="property-$cache_is_pack"></a>$cache_is_pack

```php
public mixed $cache_is_pack
```





* Visibility: **public**
* Source: [classes/Product.php line 226](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L226).


### <a name="property-$category"></a>$category

```php
public string $category
```





* Visibility: **public**
* Source: [classes/Product.php line 235](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L235).


### <a name="property-$condition"></a>$condition

```php
public string $condition
```





* Visibility: **public**
* Source: [classes/Product.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L182).


### <a name="property-$customizable"></a>$customizable

```php
public boolean $customizable
```





* Visibility: **public**
* Source: [classes/Product.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L155).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/Product.php line 194](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L194).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* Source: [classes/Product.php line 197](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L197).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'product', 'primary' => 'id_product', 'multilang' => true, 'multilang_shop' => true, 'fields' => array('id_shop_default' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_manufacturer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_supplier' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'reference' => array('type' => self::TYPE_STRING, 'validate' => 'isReference', 'size' => 32), 'supplier_reference' => array('type' => self::TYPE_STRING, 'validate' => 'isReference', 'size' => 32), 'location' => array('type' => self::TYPE_STRING, 'validate' => 'isReference', 'size' => 64), 'width' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat'), 'height' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat'), 'depth' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat'), 'weight' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat'), 'quantity_discount' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'ean13' => array('type' => self::TYPE_STRING, 'validate' => 'isEan13', 'size' => 13), 'upc' => array('type' => self::TYPE_STRING, 'validate' => 'isUpc', 'size' => 12), 'cache_is_pack' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'cache_has_attachments' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'is_virtual' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'id_category_default' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedId'), 'id_tax_rules_group' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedId'), 'on_sale' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'online_only' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'ecotax' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isPrice'), 'minimal_quantity' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedInt'), 'price' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isPrice', 'required' => true), 'wholesale_price' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isPrice'), 'unity' => array('type' => self::TYPE_STRING, 'shop' => true, 'validate' => 'isString'), 'unit_price_ratio' => array('type' => self::TYPE_FLOAT, 'shop' => true), 'additional_shipping_cost' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isPrice'), 'customizable' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedInt'), 'text_fields' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedInt'), 'uploadable_files' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedInt'), 'active' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'redirect_type' => array('type' => self::TYPE_STRING, 'shop' => true, 'validate' => 'isString'), 'id_product_redirected' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedId'), 'available_for_order' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'available_date' => array('type' => self::TYPE_DATE, 'shop' => true, 'validate' => 'isDateFormat'), 'condition' => array('type' => self::TYPE_STRING, 'shop' => true, 'validate' => 'isGenericName', 'values' => array('new', 'used', 'refurbished'), 'default' => 'new'), 'show_price' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'indexed' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'visibility' => array('type' => self::TYPE_STRING, 'shop' => true, 'validate' => 'isProductVisibility', 'values' => array('both', 'catalog', 'search', 'none'), 'default' => 'both'), 'cache_default_attribute' => array('type' => self::TYPE_INT, 'shop' => true), 'advanced_stock_management' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'date_add' => array('type' => self::TYPE_DATE, 'shop' => true, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'shop' => true, 'validate' => 'isDate'), 'pack_stock_type' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedInt'), 'meta_description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_keywords' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_title' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 128), 'link_rewrite' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isLinkRewrite', 'required' => true, 'size' => 128, 'ws_modifier' => array('http_method' => \WebserviceRequest::HTTP_POST, 'modifier' => 'modifierWsLinkRewrite')), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isCatalogName', 'required' => true, 'size' => 128), 'description' => array('type' => self::TYPE_HTML, 'lang' => true, 'validate' => 'isCleanHtml'), 'description_short' => array('type' => self::TYPE_HTML, 'lang' => true, 'validate' => 'isCleanHtml'), 'available_now' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'available_later' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'IsGenericName', 'size' => 255)), 'associations' => array('manufacturer' => array('type' => self::HAS_ONE), 'supplier' => array('type' => self::HAS_ONE), 'default_category' => array('type' => self::HAS_ONE, 'field' => 'id_category_default', 'object' => 'Category'), 'tax_rules_group' => array('type' => self::HAS_ONE), 'categories' => array('type' => self::HAS_MANY, 'field' => 'id_category', 'object' => 'Category', 'association' => 'category_product'), 'stock_availables' => array('type' => self::HAS_MANY, 'field' => 'id_stock_available', 'object' => 'StockAvailable', 'association' => 'stock_availables')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Product.php line 261](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L261).


### <a name="property-$depends_on_stock"></a>$depends_on_stock

```php
public mixed $depends_on_stock
```





* Visibility: **public**
* Source: [classes/Product.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L222).


### <a name="property-$depth"></a>$depth

```php
public string $depth
```





* Visibility: **public**
* Source: [classes/Product.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L128).


### <a name="property-$description"></a>$description

```php
public string $description
```





* Visibility: **public**
* Source: [classes/Product.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L66).


### <a name="property-$description_short"></a>$description_short

```php
public string $description_short
```





* Visibility: **public**
* Source: [classes/Product.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L69).


### <a name="property-$ean13"></a>$ean13

```php
public string $ean13
```





* Visibility: **public**
* Source: [classes/Product.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L134).


### <a name="property-$ecotax"></a>$ecotax

```php
public float $ecotax
```





* Visibility: **public**
* Source: [classes/Product.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L110).


### <a name="property-$height"></a>$height

```php
public string $height
```





* Visibility: **public**
* Source: [classes/Product.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L125).


### <a name="property-$id_category_default"></a>$id_category_default

```php
public integer $id_category_default
```





* Visibility: **public**
* Source: [classes/Product.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L51).


### <a name="property-$id_color_default"></a>$id_color_default

```php
public mixed $id_color_default
```

We keep this variable for retrocompatibility for themes



* Visibility: **public**
* Source: [classes/Product.php line 214](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L214).


### <a name="property-$id_manufacturer"></a>$id_manufacturer

```php
public integer $id_manufacturer
```





* Visibility: **public**
* Source: [classes/Product.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L45).


### <a name="property-$id_pack_product_attribute"></a>$id_pack_product_attribute

```php
public mixed $id_pack_product_attribute
```





* Visibility: **public**
* Source: [classes/Product.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L229).


### <a name="property-$id_product_redirected"></a>$id_product_redirected

```php
public boolean $id_product_redirected
```





* Visibility: **public**
* Source: [classes/Product.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L173).


### <a name="property-$id_shop_default"></a>$id_shop_default

```php
public integer $id_shop_default
```





* Visibility: **public**
* Source: [classes/Product.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L54).


### <a name="property-$id_supplier"></a>$id_supplier

```php
public integer $id_supplier
```





* Visibility: **public**
* Source: [classes/Product.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L48).


### <a name="property-$id_tax_rules_group"></a>$id_tax_rules_group

```php
public mixed $id_tax_rules_group = 1
```





* Visibility: **public**
* Source: [classes/Product.php line 208](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L208).


### <a name="property-$indexed"></a>$indexed

```php
public boolean $indexed
```





* Visibility: **public**
* Source: [classes/Product.php line 188](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L188).


### <a name="property-$isFullyLoaded"></a>$isFullyLoaded

```php
public mixed $isFullyLoaded = false
```





* Visibility: **public**
* Source: [classes/Product.php line 224](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L224).


### <a name="property-$is_virtual"></a>$is_virtual

```php
public mixed $is_virtual
```





* Visibility: **public**
* Source: [classes/Product.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L228).


### <a name="property-$link_rewrite"></a>$link_rewrite

```php
public string $link_rewrite
```





* Visibility: **public**
* Source: [classes/Product.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L140).


### <a name="property-$location"></a>$location

```php
public string $location
```





* Visibility: **public**
* Source: [classes/Product.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L119).


### <a name="property-$manufacturer_name"></a>$manufacturer_name

```php
public string $manufacturer_name
```





* Visibility: **public**
* Source: [classes/Product.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L57).


### <a name="property-$meta_description"></a>$meta_description

```php
public string $meta_description
```





* Visibility: **public**
* Source: [classes/Product.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L143).


### <a name="property-$meta_keywords"></a>$meta_keywords

```php
public string $meta_keywords
```





* Visibility: **public**
* Source: [classes/Product.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L146).


### <a name="property-$meta_title"></a>$meta_title

```php
public string $meta_title
```





* Visibility: **public**
* Source: [classes/Product.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L149).


### <a name="property-$minimal_quantity"></a>$minimal_quantity

```php
public integer $minimal_quantity = 1
```





* Visibility: **public**
* Source: [classes/Product.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L75).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/Product.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L63).


### <a name="property-$new"></a>$new

```php
public boolean $new = null
```





* Visibility: **public**
* Source: [classes/Product.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L158).


### <a name="property-$on_sale"></a>$on_sale

```php
public boolean $on_sale = false
```





* Visibility: **public**
* Source: [classes/Product.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L95).


### <a name="property-$online_only"></a>$online_only

```php
public boolean $online_only = false
```





* Visibility: **public**
* Source: [classes/Product.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L98).


### <a name="property-$out_of_stock"></a>$out_of_stock

```php
public mixed $out_of_stock
```





* Visibility: **public**
* Source: [classes/Product.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L221).


### <a name="property-$pack_stock_type"></a>$pack_stock_type

```php
public integer $pack_stock_type = 3
```





* Visibility: **public**
* Source: [classes/Product.php line 240](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L240).


### <a name="property-$price"></a>$price

```php
public float $price
```





* Visibility: **public**
* Source: [classes/Product.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L84).


### <a name="property-$producPropertiesCache"></a>$producPropertiesCache

```php
protected mixed $producPropertiesCache = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Product.php line 256](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L256).


### <a name="property-$quantity"></a>$quantity

```php
public integer $quantity
```





* Visibility: **public**
* Source: [classes/Product.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L72).


### <a name="property-$quantity_discount"></a>$quantity_discount

```php
public boolean $quantity_discount
```





* Visibility: **public**
* Source: [classes/Product.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L152).


### <a name="property-$redirect_type"></a>$redirect_type

```php
public boolean $redirect_type = ''
```





* Visibility: **public**
* Source: [classes/Product.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L170).


### <a name="property-$reference"></a>$reference

```php
public string $reference
```





* Visibility: **public**
* Source: [classes/Product.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L113).


### <a name="property-$show_price"></a>$show_price

```php
public boolean $show_price = true
```





* Visibility: **public**
* Source: [classes/Product.php line 185](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L185).


### <a name="property-$specificPrice"></a>$specificPrice

```php
public mixed $specificPrice
```





* Visibility: **public**
* Source: [classes/Product.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L86).


### <a name="property-$supplier_name"></a>$supplier_name

```php
public string $supplier_name
```





* Visibility: **public**
* Source: [classes/Product.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L60).


### <a name="property-$supplier_reference"></a>$supplier_reference

```php
public string $supplier_reference
```





* Visibility: **public**
* Source: [classes/Product.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L116).


### <a name="property-$tags"></a>$tags

```php
public mixed $tags
```





* Visibility: **public**
* Source: [classes/Product.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L200).


### <a name="property-$tax_name"></a>$tax_name

```php
public string $tax_name
```





* Visibility: **public**
* Source: [classes/Product.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L39).


### <a name="property-$tax_rate"></a>$tax_rate

```php
public string $tax_rate
```





* Visibility: **public**
* Source: [classes/Product.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L42).


### <a name="property-$text_fields"></a>$text_fields

```php
public integer $text_fields
```





* Visibility: **public**
* Source: [classes/Product.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L164).


### <a name="property-$unit_price"></a>$unit_price

```php
public float $unit_price
```





* Visibility: **public**
* Source: [classes/Product.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L104).


### <a name="property-$unit_price_ratio"></a>$unit_price_ratio

```php
public float $unit_price_ratio
```





* Visibility: **public**
* Source: [classes/Product.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L107).


### <a name="property-$unity"></a>$unity

```php
public string $unity = null
```





* Visibility: **public**
* Source: [classes/Product.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L101).


### <a name="property-$upc"></a>$upc

```php
public string $upc
```





* Visibility: **public**
* Source: [classes/Product.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L137).


### <a name="property-$uploadable_files"></a>$uploadable_files

```php
public integer $uploadable_files
```





* Visibility: **public**
* Source: [classes/Product.php line 161](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L161).


### <a name="property-$visibility"></a>$visibility

```php
public string $visibility
```





* Visibility: **public**
* Source: [classes/Product.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L191).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectMethods' => array('add' => 'addWs', 'update' => 'updateWs'), 'objectNodeNames' => 'products', 'fields' => array('id_manufacturer' => array('xlink_resource' => 'manufacturers'), 'id_supplier' => array('xlink_resource' => 'suppliers'), 'id_category_default' => array('xlink_resource' => 'categories'), 'new' => array(), 'cache_default_attribute' => array(), 'id_default_image' => array('getter' => 'getCoverWs', 'setter' => 'setCoverWs', 'xlink_resource' => array('resourceName' => 'images', 'subResourceName' => 'products')), 'id_default_combination' => array('getter' => 'getWsDefaultCombination', 'setter' => 'setWsDefaultCombination', 'xlink_resource' => array('resourceName' => 'combinations')), 'id_tax_rules_group' => array('xlink_resource' => array('resourceName' => 'tax_rule_groups')), 'position_in_category' => array('getter' => 'getWsPositionInCategory', 'setter' => 'setWsPositionInCategory'), 'manufacturer_name' => array('getter' => 'getWsManufacturerName', 'setter' => false), 'quantity' => array('getter' => false, 'setter' => false), 'type' => array('getter' => 'getWsType', 'setter' => 'setWsType')), 'associations' => array('categories' => array('resource' => 'category', 'fields' => array('id' => array('required' => true))), 'images' => array('resource' => 'image', 'fields' => array('id' => array())), 'combinations' => array('resource' => 'combination', 'fields' => array('id' => array('required' => true))), 'product_option_values' => array('resource' => 'product_option_value', 'fields' => array('id' => array('required' => true))), 'product_features' => array('resource' => 'product_feature', 'fields' => array('id' => array('required' => true), 'id_feature_value' => array('required' => true, 'xlink_resource' => 'product_feature_values'))), 'tags' => array('resource' => 'tag', 'fields' => array('id' => array('required' => true))), 'stock_availables' => array('resource' => 'stock_available', 'fields' => array('id' => array('required' => true), 'id_product_attribute' => array('required' => true)), 'setter' => false), 'accessories' => array('resource' => 'product', 'api' => 'products', 'fields' => array('id' => array('required' => true, 'xlink_resource' => 'product'))), 'product_bundle' => array('resource' => 'product', 'api' => 'products', 'fields' => array('id' => array('required' => true), 'quantity' => array()))))
```





* Visibility: **protected**
* Source: [classes/Product.php line 346](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L346).


### <a name="property-$weight"></a>$weight

```php
public string $weight
```





* Visibility: **public**
* Source: [classes/Product.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L131).


### <a name="property-$wholesale_price"></a>$wholesale_price

```php
public float $wholesale_price
```





* Visibility: **public**
* Source: [classes/Product.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L92).


### <a name="property-$width"></a>$width

```php
public string $width
```





* Visibility: **public**
* Source: [classes/Product.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L122).


### <a name="property-$cache_objects"></a>$cache_objects

```php
protected boolean $cache_objects = true
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L164).


### <a name="property-$db"></a>$db

```php
protected \Db $db = false
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L156).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L150).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected array $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L88).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected array $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L70).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected array $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L106).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected array $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L94).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected array $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L112).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected array $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L100).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected array $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L118).


### <a name="property-$force_id"></a>$force_id

```php
public boolean $force_id = false
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L159).


### <a name="property-$get_shop_from_context"></a>$get_shop_from_context

```php
protected boolean $get_shop_from_context = true
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L67).


### <a name="property-$id"></a>$id

```php
public integer $id
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L55).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L58).


### <a name="property-$id_shop"></a>$id_shop

```php
protected integer $id_shop = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L61).


### <a name="property-$id_shop_list"></a>$id_shop_list

```php
public array $id_shop_list = null
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L64).


### <a name="property-$identifier"></a>$identifier

```php
protected string $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L82).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L130).


### <a name="property-$image_format"></a>$image_format

```php
protected String $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L133).


### <a name="property-$loaded_classes"></a>$loaded_classes

```php
protected array $loaded_classes = array()
```

Holds compiled definitions of each ObjectModel class.

Values are assigned during object initialization.

* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L147).


### <a name="property-$table"></a>$table

```php
protected string $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L76).


### <a name="property-$tables"></a>$tables

```php
protected array $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L124).


### <a name="property-$update_fields"></a>$update_fields

```php
protected array $update_fields = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L153).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ProductCore::__construct($id_product, $full, $id_lang, $id_shop, \Context $context)
```





* Visibility: **public**
* Source: [classes/Product.php line 475](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L475)


#### Arguments
* $id_product **mixed**
* $full **mixed**
* $id_lang **mixed**
* $id_shop **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-_checkLabelField"></a>_checkLabelField

```php
mixed ProductCore::_checkLabelField($field, $value)
```





* Visibility: **protected**
* Source: [classes/Product.php line 4364](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4364)


#### Arguments
* $field **mixed**
* $value **mixed**



### <a name="method-_createLabel"></a>_createLabel

```php
mixed ProductCore::_createLabel($languages, $type)
```





* Visibility: **protected**
* Source: [classes/Product.php line 4433](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4433)


#### Arguments
* $languages **mixed**
* $type **mixed**



### <a name="method-_deleteOldLabels"></a>_deleteOldLabels

```php
mixed ProductCore::_deleteOldLabels()
```





* Visibility: **protected**
* Source: [classes/Product.php line 4374](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4374)




### <a name="method-_getAttributeImageAssociations"></a>_getAttributeImageAssociations

```php
array ProductCore::_getAttributeImageAssociations(integer $id_product_attribute)
```

Get product attribute image associations



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3729](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3729)


#### Arguments
* $id_product_attribute **integer**



### <a name="method-_getCustomizationFieldsNLabels"></a>_getCustomizationFieldsNLabels

```php
mixed ProductCore::_getCustomizationFieldsNLabels($product_id, $id_shop)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/Product.php line 3885](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3885)


#### Arguments
* $product_id **mixed**
* $id_shop **mixed**



### <a name="method-_getProductIdByDate"></a>_getProductIdByDate

```php
mixed ProductCore::_getProductIdByDate($beginning, $ending, \Context $context, $with_combination)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/Product.php line 2233](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L2233)


#### Arguments
* $beginning **mixed**
* $ending **mixed**
* $context **[Context](class.ContextCore.md)**
* $with_combination **mixed**



### <a name="method-add"></a>add

```php
mixed ProductCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Product.php line 524](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L524)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addAttribute"></a>addAttribute

```php
mixed ProductCore::addAttribute(float $price, float $weight, $unit_impact, float $ecotax, integer $id_images, string $reference, string $ean13, boolean $default, string $location, $upc, integer $minimal_quantity, array $id_shop_list, $available_date)
```

Add a product attribute



* Visibility: **public**
* Source: [classes/Product.php line 1559](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1559)


#### Arguments
* $price **float** - Additional price
* $weight **float** - Additional weight
* $unit_impact **mixed**
* $ecotax **float** - Additional ecotax
* $id_images **integer** - Image ids
* $reference **string** - Reference
* $ean13 **string** - Ean-13 barcode
* $default **boolean** - Is default attribute for product
* $location **string** - Location
* $upc **mixed**
* $minimal_quantity **integer** - Minimal quantity to add to cart
* $id_shop_list **array**
* $available_date **mixed**



### <a name="method-addAttributeCombinaison"></a>addAttributeCombinaison

```php
array ProductCore::addAttributeCombinaison(integer $id_product_attribute, array $attributes)
```

Add a product attributes combinaison



* Visibility: **public**
* Source: [classes/Product.php line 1808](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1808)


#### Arguments
* $id_product_attribute **integer** - Product attribute id
* $attributes **array** - Attributes to forge combinaison



### <a name="method-addAttributeCombinationMultiple"></a>addAttributeCombinationMultiple

```php
boolean ProductCore::addAttributeCombinationMultiple($id_attributes, $combinations)
```





* Visibility: **public**
* Source: [classes/Product.php line 1827](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1827)


#### Arguments
* $id_attributes **mixed**
* $combinations **mixed**



### <a name="method-addCombinationEntity"></a>addCombinationEntity

```php
mixed ProductCore::addCombinationEntity($wholesale_price, $price, $weight, $unit_impact, $ecotax, integer $quantity, $id_images, $reference, $id_supplier, $ean13, $default, $location, $upc, $minimal_quantity, array $id_shop_list, $available_date)
```





* Visibility: **public**
* Source: [classes/Product.php line 1313](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1313)


#### Arguments
* $wholesale_price **mixed**
* $price **mixed**
* $weight **mixed**
* $unit_impact **mixed**
* $ecotax **mixed**
* $quantity **integer** - DEPRECATED
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



### <a name="method-addCustomizationPrice"></a>addCustomizationPrice

```php
mixed ProductCore::addCustomizationPrice($products, $customized_datas)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 4303](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4303)


#### Arguments
* $products **mixed**
* $customized_datas **mixed**



### <a name="method-addFeatureProductImport"></a>addFeatureProductImport

```php
mixed ProductCore::addFeatureProductImport($id_product, $id_feature, $id_feature_value)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3457](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3457)


#### Arguments
* $id_product **mixed**
* $id_feature **mixed**
* $id_feature_value **mixed**



### <a name="method-addFeaturesCustomToDB"></a>addFeaturesCustomToDB

```php
mixed ProductCore::addFeaturesCustomToDB($id_value, $lang, $cust)
```

Add new feature to product



* Visibility: **public**
* Source: [classes/Product.php line 3436](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3436)


#### Arguments
* $id_value **mixed**
* $lang **mixed**
* $cust **mixed**



### <a name="method-addFeaturesToDB"></a>addFeaturesToDB

```php
mixed ProductCore::addFeaturesToDB($id_feature, $id_value, $cust)
```





* Visibility: **public**
* Source: [classes/Product.php line 3442](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3442)


#### Arguments
* $id_feature **mixed**
* $id_value **mixed**
* $cust **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
boolean ObjectModelCore::addFieldsRequiredDatabase(array $fields)
```

Sets required field for this class in the database.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1340](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1340)


#### Arguments
* $fields **array**



### <a name="method-addProductAttribute"></a>addProductAttribute

```php
mixed ProductCore::addProductAttribute($price, $weight, $unit_impact, $ecotax, $quantity, $id_images, $reference, $id_supplier, $ean13, $default, $location, $upc, $minimal_quantity)
```

addProductAttribute is deprecated

The quantity params now set StockAvailable for the current shop with the specified quantity
The supplier_reference params now set the supplier reference of the default supplier of the product if possible

* Visibility: **public**
* Source: [classes/Product.php line 1251](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1251)


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



### <a name="method-addProductAttributeMultiple"></a>addProductAttributeMultiple

```php
array ProductCore::addProductAttributeMultiple($attributes, boolean $set_default)
```





* Visibility: **public**
* Source: [classes/Product.php line 1336](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1336)


#### Arguments
* $attributes **mixed**
* $set_default **boolean**



### <a name="method-addStockMvt"></a>addStockMvt

```php
boolean ProductCore::addStockMvt(integer $quantity, integer $id_reason, integer $id_product_attribute, integer $id_order, integer $id_employee)
```

Add a stock movement for current product

Since 1.5, this method only permit to add/remove available quantities of the current product in the current shop

* Visibility: **public**
* Source: [classes/Product.php line 4680](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4680)


#### Arguments
* $quantity **integer**
* $id_reason **integer** - 
useless

* $id_product_attribute **integer**
* $id_order **integer** - 
DEPRECATED

* $id_employee **integer** - 
DEPRECATED




### <a name="method-addSupplierReference"></a>addSupplierReference

```php
mixed ProductCore::addSupplierReference(integer $id_supplier, integer $id_product_attribute, string $supplier_reference, float $price, integer $id_currency)
```

Sets or updates Supplier Reference



* Visibility: **public**
* Source: [classes/Product.php line 1441](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1441)


#### Arguments
* $id_supplier **integer**
* $id_product_attribute **integer**
* $supplier_reference **string**
* $price **float**
* $id_currency **integer**



### <a name="method-addToCategories"></a>addToCategories

```php
boolean ProductCore::addToCategories(mixed $categories)
```

addToCategories add this product to the category/ies if not exists.



* Visibility: **public**
* Source: [classes/Product.php line 925](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L925)


#### Arguments
* $categories **mixed** - id_category or array of id_category



### <a name="method-addWs"></a>addWs

```php
mixed ProductCore::addWs($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Product.php line 5495](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5495)


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
* Source: [classes/ObjectModel.php line 1408](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1408)


#### Arguments
* $id_shops **integer|array**



### <a name="method-cacheFieldsRequiredDatabase"></a>cacheFieldsRequiredDatabase

```php
mixed ObjectModelCore::cacheFieldsRequiredDatabase(boolean $all)
```

Caches data about required objects fields in memory



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1319](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1319)


#### Arguments
* $all **boolean** - If true, caches required fields of all object classes.



### <a name="method-cacheFrontFeatures"></a>cacheFrontFeatures

```php
mixed ProductCore::cacheFrontFeatures($product_ids, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3514](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3514)


#### Arguments
* $product_ids **mixed**
* $id_lang **mixed**



### <a name="method-cacheProductsFeatures"></a>cacheProductsFeatures

```php
mixed ProductCore::cacheProductsFeatures($product_ids)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3490](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3490)


#### Arguments
* $product_ids **mixed**



### <a name="method-changeAccessories"></a>changeAccessories

```php
mixed ProductCore::changeAccessories(array $accessories_id)
```

Link accessories with product



* Visibility: **public**
* Source: [classes/Product.php line 3424](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3424)


#### Arguments
* $accessories_id **array** - Accessories ids



### <a name="method-checkAccess"></a>checkAccess

```php
mixed ProductCore::checkAccess($id_customer)
```





* Visibility: **public**
* Source: [classes/Product.php line 4630](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4630)


#### Arguments
* $id_customer **mixed**



### <a name="method-checkAccessStatic"></a>checkAccessStatic

```php
mixed ProductCore::checkAccessStatic($id_product, $id_customer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 4635](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4635)


#### Arguments
* $id_product **mixed**
* $id_customer **mixed**



### <a name="method-checkDefaultAttributes"></a>checkDefaultAttributes

```php
mixed ProductCore::checkDefaultAttributes()
```

Check if there is no default attribute and create it if not



* Visibility: **public**
* Source: [classes/Product.php line 3215](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3215)




### <a name="method-checkQty"></a>checkQty

```php
boolean ProductCore::checkQty(integer $qty)
```

Check product availability



* Visibility: **public**
* Source: [classes/Product.php line 3196](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3196)


#### Arguments
* $qty **integer** - Quantity desired



### <a name="method-cleanPositions"></a>cleanPositions

```php
mixed ProductCore::cleanPositions($id_category, $position)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 646](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L646)


#### Arguments
* $id_category **mixed**
* $position **mixed**



### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache(boolean $all)
```

Clears cache entries that have this object's ID.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1360](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1360)


#### Arguments
* $all **boolean** - If true, clears cache for all objects



### <a name="method-convertAndFormatPrice"></a>convertAndFormatPrice

```php
mixed ProductCore::convertAndFormatPrice($price, $currency, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2955](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L2955)


#### Arguments
* $price **mixed**
* $currency **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-convertPrice"></a>convertPrice

```php
string ProductCore::convertPrice(array $params, $smarty)
```

Display price with right format and currency



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3050](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3050)


#### Arguments
* $params **array** - Params
* $smarty **mixed** - Smarty object



### <a name="method-convertPriceWithCurrency"></a>convertPriceWithCurrency

```php
string ProductCore::convertPriceWithCurrency(array $params, object $smarty)
```

Convert price with currency



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3062](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3062)


#### Arguments
* $params **array**
* $smarty **object** - DEPRECATED



### <a name="method-createLabels"></a>createLabels

```php
mixed ProductCore::createLabels($uploadable_files, $text_fields)
```





* Visibility: **public**
* Source: [classes/Product.php line 4461](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4461)


#### Arguments
* $uploadable_files **mixed**
* $text_fields **mixed**



### <a name="method-defineProductImage"></a>defineProductImage

```php
mixed ProductCore::defineProductImage($row, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 4020](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4020)


#### Arguments
* $row **mixed**
* $id_lang **mixed**



### <a name="method-delete"></a>delete

```php
mixed ProductCore::delete()
```





* Visibility: **public**
* Source: [classes/Product.php line 839](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L839)




### <a name="method-deleteAccessories"></a>deleteAccessories

```php
mixed ProductCore::deleteAccessories()
```

Delete product accessories



* Visibility: **public**
* Source: [classes/Product.php line 3328](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3328)




### <a name="method-deleteAttachments"></a>deleteAttachments

```php
array ProductCore::deleteAttachments($update_attachment_cache)
```

Delete product attachments



* Visibility: **public**
* Source: [classes/Product.php line 1709](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1709)


#### Arguments
* $update_attachment_cache **mixed**



### <a name="method-deleteAttributeCombinaison"></a>deleteAttributeCombinaison

```php
mixed ProductCore::deleteAttributeCombinaison(integer $id_product_attribute)
```





* Visibility: **public**
* Source: [classes/Product.php line 5688](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5688)


#### Arguments
* $id_product_attribute **integer**



### <a name="method-deleteAttributeCombination"></a>deleteAttributeCombination

```php
array ProductCore::deleteAttributeCombination(integer $id_product_attribute)
```

Delete a product attributes combination



* Visibility: **public**
* Source: [classes/Product.php line 1849](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1849)


#### Arguments
* $id_product_attribute **integer** - Product attribute id



### <a name="method-deleteAttributesImpacts"></a>deleteAttributesImpacts

```php
boolean ProductCore::deleteAttributesImpacts()
```

Delete product attributes impacts



* Visibility: **public**
* Source: [classes/Product.php line 1670](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1670)




### <a name="method-deleteCartProducts"></a>deleteCartProducts

```php
array ProductCore::deleteCartProducts()
```

Delete product from cart



* Visibility: **public**
* Source: [classes/Product.php line 1067](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1067)




### <a name="method-deleteCategories"></a>deleteCategories

```php
array ProductCore::deleteCategories(boolean $clean_positions)
```

Delete all association to category where product is indexed



* Visibility: **public**
* Source: [classes/Product.php line 1033](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1033)


#### Arguments
* $clean_positions **boolean** - clean category positions after deletion



### <a name="method-deleteCategory"></a>deleteCategory

```php
boolean ProductCore::deleteCategory(mixed $id_category, mixed $clean_positions)
```

deleteCategory delete this product from the category $id_category



* Visibility: **public**
* Source: [classes/Product.php line 1010](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1010)


#### Arguments
* $id_category **mixed**
* $clean_positions **mixed**



### <a name="method-deleteCustomization"></a>deleteCustomization

```php
array ProductCore::deleteCustomization()
```

Delete product customizations



* Visibility: **public**
* Source: [classes/Product.php line 1727](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1727)




### <a name="method-deleteDefaultAttributes"></a>deleteDefaultAttributes

```php
mixed ProductCore::deleteDefaultAttributes()
```

Del all default attributes for product



* Visibility: **public**
* Source: [classes/Product.php line 1372](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1372)




### <a name="method-deleteDownload"></a>deleteDownload

```php
boolean ProductCore::deleteDownload()
```

Remove all downloadable files for product and its attributes



* Visibility: **public**
* Source: [classes/Product.php line 5659](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5659)




### <a name="method-deleteFeatures"></a>deleteFeatures

```php
mixed ProductCore::deleteFeatures()
```

Delete features



* Visibility: **public**
* Source: [classes/Product.php line 1873](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1873)




### <a name="method-deleteFromAccessories"></a>deleteFromAccessories

```php
mixed ProductCore::deleteFromAccessories()
```

Delete product from other products accessories



* Visibility: **public**
* Source: [classes/Product.php line 3338](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3338)




### <a name="method-deleteFromCartRules"></a>deleteFromCartRules

```php
mixed ProductCore::deleteFromCartRules()
```





* Visibility: **public**
* Source: [classes/Product.php line 908](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L908)




### <a name="method-deleteFromSupplier"></a>deleteFromSupplier

```php
mixed ProductCore::deleteFromSupplier()
```





* Visibility: **public**
* Source: [classes/Product.php line 914](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L914)




### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage(boolean $force_delete)
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1585](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1585)


#### Arguments
* $force_delete **boolean**



### <a name="method-deleteImages"></a>deleteImages

```php
boolean ProductCore::deleteImages()
```

Delete product images from database



* Visibility: **public**
* Source: [classes/Product.php line 1077](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1077)




### <a name="method-deletePack"></a>deletePack

```php
array ProductCore::deletePack()
```

Delete product pack details



* Visibility: **public**
* Source: [classes/Product.php line 1748](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1748)




### <a name="method-deleteProductAttributes"></a>deleteProductAttributes

```php
array ProductCore::deleteProductAttributes()
```

Delete product attributes



* Visibility: **public**
* Source: [classes/Product.php line 1651](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1651)




### <a name="method-deleteProductFeatures"></a>deleteProductFeatures

```php
array ProductCore::deleteProductFeatures()
```

Delete product features



* Visibility: **public**
* Source: [classes/Product.php line 1683](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1683)




### <a name="method-deleteProductSale"></a>deleteProductSale

```php
array ProductCore::deleteProductSale()
```

Delete product sales



* Visibility: **public**
* Source: [classes/Product.php line 1762](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1762)




### <a name="method-deleteSceneProducts"></a>deleteSceneProducts

```php
array ProductCore::deleteSceneProducts()
```

Delete product in its scenes



* Visibility: **public**
* Source: [classes/Product.php line 1775](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1775)




### <a name="method-deleteSearchIndexes"></a>deleteSearchIndexes

```php
array ProductCore::deleteSearchIndexes()
```

Delete product indexed words



* Visibility: **public**
* Source: [classes/Product.php line 1788](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1788)




### <a name="method-deleteSelection"></a>deleteSelection

```php
mixed ProductCore::deleteSelection($products)
```





* Visibility: **public**
* Source: [classes/Product.php line 890](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L890)


#### Arguments
* $products **mixed**



### <a name="method-deleteTags"></a>deleteTags

```php
array ProductCore::deleteTags()
```

Delete products tags entries



* Visibility: **public**
* Source: [classes/Product.php line 1055](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1055)




### <a name="method-deleteWsTags"></a>deleteWsTags

```php
array ProductCore::deleteWsTags()
```

Delete products tags entries without delete tags for webservice usage



* Visibility: **public**
* Source: [classes/Product.php line 5167](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5167)




### <a name="method-disableCache"></a>disableCache

```php
mixed ObjectModelCore::disableCache()
```

Disables object caching



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1892](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1892)




### <a name="method-displayFieldName"></a>displayFieldName

```php
string ObjectModelCore::displayFieldName(string $field, string $class, boolean $htmlentities, \Context|null $context)
```

Returns field name translation



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1051](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1051)


#### Arguments
* $field **string** - Field name
* $class **string** - ObjectModel class name
* $htmlentities **boolean** - If true, applies htmlentities() to result string
* $context **[Context](class.ContextCore.md)|null** - Context object



### <a name="method-displayWtPrice"></a>displayWtPrice

```php
mixed ProductCore::displayWtPrice($params, $smarty)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3067](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3067)


#### Arguments
* $params **mixed**
* $smarty **mixed**



### <a name="method-displayWtPriceWithCurrency"></a>displayWtPriceWithCurrency

```php
string ProductCore::displayWtPriceWithCurrency(array $params, \Smarty $smarty)
```

Display WT price with currency



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3079](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3079)


#### Arguments
* $params **array**
* $smarty **Smarty** - DEPRECATED



### <a name="method-duplicateAccessories"></a>duplicateAccessories

```php
mixed ProductCore::duplicateAccessories($id_product_old, $id_product_new)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3741](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3741)


#### Arguments
* $id_product_old **mixed**
* $id_product_new **mixed**



### <a name="method-duplicateAttachments"></a>duplicateAttachments

```php
mixed ProductCore::duplicateAttachments($id_product_old, $id_product_new)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3806](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3806)


#### Arguments
* $id_product_old **mixed**
* $id_product_new **mixed**



### <a name="method-duplicateAttributes"></a>duplicateAttributes

```php
mixed ProductCore::duplicateAttributes(integer $id_product_old, integer $id_product_new)
```

Duplicate attributes when duplicating a product



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3607](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3607)


#### Arguments
* $id_product_old **integer** - Old product id
* $id_product_new **integer** - New product id



### <a name="method-duplicateCustomizationFields"></a>duplicateCustomizationFields

```php
mixed ProductCore::duplicateCustomizationFields($old_product_id, $product_id)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3932](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3932)


#### Arguments
* $old_product_id **mixed**
* $product_id **mixed**



### <a name="method-duplicateDownload"></a>duplicateDownload

```php
mixed ProductCore::duplicateDownload($id_product_old, $id_product_new)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3776](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3776)


#### Arguments
* $id_product_old **mixed**
* $id_product_new **mixed**



### <a name="method-duplicateFeatures"></a>duplicateFeatures

```php
mixed ProductCore::duplicateFeatures(integer $id_product_old, $id_product_new)
```

Duplicate features when duplicating a product



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3836](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3836)


#### Arguments
* $id_product_old **integer** - Old product id
* $id_product_new **mixed**



### <a name="method-duplicateObject"></a>duplicateObject

```php
\ObjectModel|false ObjectModelCore::duplicateObject()
```

Takes current object ID, gets its values from database,
saves them in a new row and loads newly saved values as a new object.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 534](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L534)




### <a name="method-duplicateShops"></a>duplicateShops

```php
boolean|void ObjectModelCore::duplicateShops($id)
```

Copies shop association data from object with specified ID.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1462](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1462)


#### Arguments
* $id **mixed**



### <a name="method-duplicateSpecificPrices"></a>duplicateSpecificPrices

```php
mixed ProductCore::duplicateSpecificPrices($old_product_id, $product_id)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3921](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3921)


#### Arguments
* $old_product_id **mixed**
* $product_id **mixed**



### <a name="method-duplicateSuppliers"></a>duplicateSuppliers

```php
mixed ProductCore::duplicateSuppliers(integer $id_product_old, integer $id_product_new)
```

Adds suppliers from old product onto a newly duplicated product



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3977](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3977)


#### Arguments
* $id_product_old **integer**
* $id_product_new **integer**



### <a name="method-duplicateTags"></a>duplicateTags

```php
mixed ProductCore::duplicateTags($id_product_old, $id_product_new)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3759](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3759)


#### Arguments
* $id_product_old **mixed**
* $id_product_new **mixed**



### <a name="method-enableCache"></a>enableCache

```php
mixed ObjectModelCore::enableCache()
```

Enables object caching



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1884](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1884)




### <a name="method-existsInDatabase"></a>existsInDatabase

```php
boolean ObjectModelCore::existsInDatabase(integer $id_entity, string $table)
```

Checks if an object exists in database.



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1624](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1624)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-existsRefInDatabase"></a>existsRefInDatabase

```php
boolean ProductCore::existsRefInDatabase($reference)
```

Checks if reference exists



* Visibility: **public**
* Source: [classes/Product.php line 5197](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5197)


#### Arguments
* $reference **mixed**



### <a name="method-flushPriceCache"></a>flushPriceCache

```php
mixed ProductCore::flushPriceCache()
```

This method allows to flush price cache



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 5559](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5559)




### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $type, integer $id_lang)
```

Formats values of each fields.



* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 322](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L322)


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
* Source: [classes/ObjectModel.php line 373](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L373)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **boolean**
* $purify **boolean**
* $allow_null **boolean**



### <a name="method-generateMultipleCombinations"></a>generateMultipleCombinations

```php
mixed ProductCore::generateMultipleCombinations($combinations, $attributes)
```





* Visibility: **public**
* Source: [classes/Product.php line 1270](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1270)


#### Arguments
* $combinations **mixed**
* $attributes **mixed**



### <a name="method-getAccessories"></a>getAccessories

```php
array ProductCore::getAccessories(integer $id_lang, $active)
```

Get product accessories



* Visibility: **public**
* Source: [classes/Product.php line 3371](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3371)


#### Arguments
* $id_lang **integer** - Language id
* $active **mixed**



### <a name="method-getAccessoriesLight"></a>getAccessoriesLight

```php
array ProductCore::getAccessoriesLight(integer $id_lang, integer $id_product)
```

Get product accessories (only names)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3350](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3350)


#### Arguments
* $id_lang **integer** - Language id
* $id_product **integer** - Product id



### <a name="method-getAccessoryById"></a>getAccessoryById

```php
mixed ProductCore::getAccessoryById($accessory_id)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3414](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3414)


#### Arguments
* $accessory_id **mixed**



### <a name="method-getAllCustomizedDatas"></a>getAllCustomizedDatas

```php
mixed ProductCore::getAllCustomizedDatas($id_cart, $id_lang, $only_in_cart, $id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 4255](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4255)


#### Arguments
* $id_cart **mixed**
* $id_lang **mixed**
* $only_in_cart **mixed**
* $id_shop **mixed**



### <a name="method-getAnchor"></a>getAnchor

```php
string ProductCore::getAnchor(integer $id_product_attribute, $with_id)
```

Get the combination url anchor of the product



* Visibility: **public**
* Source: [classes/Product.php line 5435](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5435)


#### Arguments
* $id_product_attribute **integer**
* $with_id **mixed**



### <a name="method-getAssociatedShops"></a>getAssociatedShops

```php
array ObjectModelCore::getAssociatedShops()
```

Gets the list of associated shop IDs



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1440](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1440)




### <a name="method-getAttachments"></a>getAttachments

```php
mixed ProductCore::getAttachments($id_lang)
```





* Visibility: **public**
* Source: [classes/Product.php line 4246](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4246)


#### Arguments
* $id_lang **mixed**



### <a name="method-getAttachmentsStatic"></a>getAttachmentsStatic

```php
mixed ProductCore::getAttachmentsStatic($id_lang, $id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 4236](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4236)


#### Arguments
* $id_lang **mixed**
* $id_product **mixed**



### <a name="method-getAttributeCombinaisons"></a>getAttributeCombinaisons

```php
mixed ProductCore::getAttributeCombinaisons(integer $id_lang)
```





* Visibility: **public**
* Source: [classes/Product.php line 5677](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5677)


#### Arguments
* $id_lang **integer**



### <a name="method-getAttributeCombinations"></a>getAttributeCombinations

```php
array ProductCore::getAttributeCombinations(integer $id_lang)
```

Get all available product attributes combinations



* Visibility: **public**
* Source: [classes/Product.php line 1964](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1964)


#### Arguments
* $id_lang **integer** - Language id



### <a name="method-getAttributeCombinationsById"></a>getAttributeCombinationsById

```php
array ProductCore::getAttributeCombinationsById(integer $id_product_attribute, integer $id_lang)
```

Get product attribute combination by id_product_attribute



* Visibility: **public**
* Source: [classes/Product.php line 2008](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L2008)


#### Arguments
* $id_product_attribute **integer**
* $id_lang **integer** - Language id



### <a name="method-getAttributesColorList"></a>getAttributesColorList

```php
mixed ProductCore::getAttributesColorList(array $products, $have_stock)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3254](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3254)


#### Arguments
* $products **array**
* $have_stock **mixed**



### <a name="method-getAttributesGroups"></a>getAttributesGroups

```php
array ProductCore::getAttributesGroups(integer $id_lang)
```

Get all available attribute groups



* Visibility: **public**
* Source: [classes/Product.php line 3297](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3297)


#### Arguments
* $id_lang **integer** - Language id



### <a name="method-getAttributesImpacts"></a>getAttributesImpacts

```php
mixed ProductCore::getAttributesImpacts($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3706](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3706)


#### Arguments
* $id_product **mixed**



### <a name="method-getAttributesInformationsByProduct"></a>getAttributesInformationsByProduct

```php
mixed ProductCore::getAttributesInformationsByProduct(integer $id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 5328](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5328)


#### Arguments
* $id_product **integer**



### <a name="method-getAttributesParams"></a>getAttributesParams

```php
array ProductCore::getAttributesParams(integer $id_product, $id_product_attribute)
```

Get label by lang and value by lang too



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 5230](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5230)


#### Arguments
* $id_product **integer**
* $id_product_attribute **mixed**



### <a name="method-getAttributesResume"></a>getAttributesResume

```php
array ProductCore::getAttributesResume(integer $id_lang, $attribute_value_separator, $attribute_separator)
```

Get all available product attributes resume



* Visibility: **public**
* Source: [classes/Product.php line 1907](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1907)


#### Arguments
* $id_lang **integer** - Language id
* $attribute_value_separator **mixed**
* $attribute_separator **mixed**



### <a name="method-getAvailableDate"></a>getAvailableDate

```php
\string/null ProductCore::getAvailableDate(integer $id_product, integer $id_product_attribute)
```

For a given id_product and id_product_attribute, return available date



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 763](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L763)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - Optional



### <a name="method-getCarriers"></a>getCarriers

```php
mixed ProductCore::getCarriers()
```

Gets carriers assigned to the product



* Visibility: **public**
* Source: [classes/Product.php line 2511](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L2511)




### <a name="method-getCategories"></a>getCategories

```php
array ProductCore::getCategories()
```

getCategories return an array of categories which this product belongs to



* Visibility: **public**
* Source: [classes/Product.php line 2503](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L2503)




### <a name="method-getColorsListCacheId"></a>getColorsListCacheId

```php
mixed ProductCore::getColorsListCacheId($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 5846](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5846)


#### Arguments
* $id_product **mixed**



### <a name="method-getCombinationImageById"></a>getCombinationImageById

```php
mixed ProductCore::getCombinationImageById($id_product_attribute, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2087](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L2087)


#### Arguments
* $id_product_attribute **mixed**
* $id_lang **mixed**



### <a name="method-getCombinationImages"></a>getCombinationImages

```php
mixed ProductCore::getCombinationImages($id_lang)
```





* Visibility: **public**
* Source: [classes/Product.php line 2049](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L2049)


#### Arguments
* $id_lang **mixed**



### <a name="method-getCover"></a>getCover

```php
array ProductCore::getCover($id_product, \Context $context)
```

Get product cover image



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2575](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L2575)


#### Arguments
* $id_product **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getCoverWs"></a>getCoverWs

```php
integer ProductCore::getCoverWs()
```

Webservice getter : get virtual field id_default_image in category



* Visibility: **public**
* Source: [classes/Product.php line 5078](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5078)




### <a name="method-getCustomizationFieldIds"></a>getCustomizationFieldIds

```php
mixed ProductCore::getCustomizationFieldIds()
```





* Visibility: **public**
* Source: [classes/Product.php line 4547](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4547)




### <a name="method-getCustomizationFields"></a>getCustomizationFields

```php
mixed ProductCore::getCustomizationFields($id_lang, $id_shop)
```





* Visibility: **public**
* Source: [classes/Product.php line 4520](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4520)


#### Arguments
* $id_lang **mixed**
* $id_shop **mixed**



### <a name="method-getDefaultAttribute"></a>getDefaultAttribute

```php
integer ProductCore::getDefaultAttribute($id_product, $minimum_quantity, $reset)
```

Get the default attribute for a product



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 679](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L679)


#### Arguments
* $id_product **mixed**
* $minimum_quantity **mixed**
* $reset **mixed**



### <a name="method-getDefaultCategory"></a>getDefaultCategory

```php
mixed ProductCore::getDefaultCategory()
```

get the default category according to the shop



* Visibility: **public**
* Source: [classes/Product.php line 5631](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5631)




### <a name="method-getDefaultIdProductAttribute"></a>getDefaultIdProductAttribute

```php
mixed ProductCore::getDefaultIdProductAttribute()
```





* Visibility: **public**
* Source: [classes/Product.php line 3022](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3022)




### <a name="method-getDefinition"></a>getDefinition

```php
array ObjectModelCore::getDefinition(string $class, string|null $field)
```

Returns object definition



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1740](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1740)


#### Arguments
* $class **string** - Name of object
* $field **string|null** - Name of field if we want the definition of one field only



### <a name="method-getFeatures"></a>getFeatures

```php
array ProductCore::getFeatures()
```

Select all features for the object



* Visibility: **public**
* Source: [classes/Product.php line 3471](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3471)




### <a name="method-getFeaturesStatic"></a>getFeaturesStatic

```php
mixed ProductCore::getFeaturesStatic($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3476](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3476)


#### Arguments
* $id_product **mixed**



### <a name="method-getFieldByLang"></a>getFieldByLang

```php
mixed ObjectModelCore::getFieldByLang(string $field_name, integer|null $id_lang)
```

Return the field value for the specified language if the field is multilang,
else the field value.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1849](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1849)


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
* Source: [classes/ObjectModel.php line 243](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L243)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 284](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L284)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
array|null ObjectModelCore::getFieldsRequiredDatabase(boolean $all)
```

Returns an array of required fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1306](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1306)


#### Arguments
* $all **boolean** - If true, returns required fields of all object classes.



### <a name="method-getFieldsShop"></a>getFieldsShop

```php
array ProductCore::getFieldsShop()
```





* Visibility: **public**
* Source: [classes/Product.php line 514](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L514)




### <a name="method-getFrontFeatures"></a>getFrontFeatures

```php
mixed ProductCore::getFrontFeatures($id_lang)
```





* Visibility: **public**
* Source: [classes/Product.php line 4231](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4231)


#### Arguments
* $id_lang **mixed**



### <a name="method-getFrontFeaturesStatic"></a>getFrontFeaturesStatic

```php
mixed ProductCore::getFrontFeaturesStatic($id_lang, $id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 4211](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4211)


#### Arguments
* $id_lang **mixed**
* $id_product **mixed**



### <a name="method-getIdByEan13"></a>getIdByEan13

```php
integer ProductCore::getIdByEan13(string $ean13)
```

For a given ean13 reference, returns the corresponding id



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 5745](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5745)


#### Arguments
* $ean13 **string**



### <a name="method-getIdProductAttributeMostExpensive"></a>getIdProductAttributeMostExpensive

```php
mixed ProductCore::getIdProductAttributeMostExpensive()
```





* Visibility: **public**
* Source: [classes/Product.php line 3007](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3007)




### <a name="method-getIdTaxRulesGroup"></a>getIdTaxRulesGroup

```php
mixed ProductCore::getIdTaxRulesGroup()
```





* Visibility: **public**
* Source: [classes/Product.php line 4745](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4745)




### <a name="method-getIdTaxRulesGroupByIdProduct"></a>getIdTaxRulesGroupByIdProduct

```php
mixed ProductCore::getIdTaxRulesGroupByIdProduct($id_product, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 4750](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4750)


#### Arguments
* $id_product **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getIdTaxRulesGroupMostUsed"></a>getIdTaxRulesGroupMostUsed

```php
mixed ProductCore::getIdTaxRulesGroupMostUsed()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 5722](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5722)




### <a name="method-getImages"></a>getImages

```php
array ProductCore::getImages(integer $id_lang, \Context $context)
```

Get product images and legends



* Visibility: **public**
* Source: [classes/Product.php line 2558](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L2558)


#### Arguments
* $id_lang **integer** - Language id for multilingual legends
* $context **[Context](class.ContextCore.md)**



### <a name="method-getLink"></a>getLink

```php
mixed ProductCore::getLink(\Context $context)
```

Get the link of the product page of this product



* Visibility: **public**
* Source: [classes/Product.php line 3998](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3998)


#### Arguments
* $context **[Context](class.ContextCore.md)**



### <a name="method-getNewProducts"></a>getNewProducts

```php
array ProductCore::getNewProducts(integer $id_lang, $page_number, $nb_products, $count, $order_by, $order_way, \Context $context)
```

Get new products



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2131](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L2131)


#### Arguments
* $id_lang **integer** - Language id
* $page_number **mixed**
* $nb_products **mixed**
* $count **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getNoPackPrice"></a>getNoPackPrice

```php
mixed ProductCore::getNoPackPrice()
```





* Visibility: **public**
* Source: [classes/Product.php line 4625](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4625)




### <a name="method-getParentCategories"></a>getParentCategories

```php
array ProductCore::getParentCategories(integer $id_lang)
```

Get list of parent categories



* Visibility: **public**
* Source: [classes/Product.php line 5572](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5572)


#### Arguments
* $id_lang **integer**



### <a name="method-getPrice"></a>getPrice

```php
float ProductCore::getPrice(boolean $tax, integer $id_product_attribute, integer $decimals, integer $divisor, $only_reduc, $usereduc, $quantity)
```

Get product price
Same as static function getPriceStatic, no need to specify product id



* Visibility: **public**
* Source: [classes/Product.php line 2993](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L2993)


#### Arguments
* $tax **boolean** - With taxes or not (optional)
* $id_product_attribute **integer** - Product attribute id (optional)
* $decimals **integer** - Number of decimals (optional)
* $divisor **integer** - Util when paying many time without fees (optional)
* $only_reduc **mixed**
* $usereduc **mixed**
* $quantity **mixed**



### <a name="method-getPriceStatic"></a>getPriceStatic

```php
float ProductCore::getPriceStatic(integer $id_product, boolean $usetax, integer|null $id_product_attribute, integer $decimals, integer|null $divisor, boolean $only_reduc, boolean $usereduc, integer $quantity, boolean $force_associated_tax, integer|null $id_customer, integer|null $id_cart, integer|null $id_address, null $specific_price_output, boolean $with_ecotax, boolean $use_group_reduction, \Context $context, boolean $use_customer_price)
```

Returns product price



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2622](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L2622)


#### Arguments
* $id_product **integer** - Product id
* $usetax **boolean** - With taxes or not (optional)
* $id_product_attribute **integer|null** - Product attribute id (optional).
                                   If set to false, do not apply the combination price impact.
                                   NULL does apply the default combination price impact.
* $decimals **integer** - Number of decimals (optional)
* $divisor **integer|null** - Useful when paying many time without fees (optional)
* $only_reduc **boolean** - Returns only the reduction amount
* $usereduc **boolean** - Set if the returned amount will include reduction
* $quantity **integer** - Required for quantity discount application (default value: 1)
* $force_associated_tax **boolean** - DEPRECATED - NOT USED Force to apply the associated tax.
                                   Only works when the parameter $usetax is true
* $id_customer **integer|null** - Customer ID (for customer group reduction)
* $id_cart **integer|null** - Cart ID. Required when the cookie is not accessible
                                   (e.g., inside a payment module, a cron task...)
* $id_address **integer|null** - Customer address ID. Required for price (tax included)
                                   calculation regarding the guest localization
* $specific_price_output **null** - If a specific price applies regarding the previous parameters,
                                       this variable is filled with the corresponding SpecificPrice object
* $with_ecotax **boolean** - Insert ecotax in price output.
* $use_group_reduction **boolean**
* $context **[Context](class.ContextCore.md)**
* $use_customer_price **boolean**



### <a name="method-getPriceWithoutReduct"></a>getPriceWithoutReduct

```php
mixed ProductCore::getPriceWithoutReduct($notax, $id_product_attribute, $decimals)
```





* Visibility: **public**
* Source: [classes/Product.php line 3038](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3038)


#### Arguments
* $notax **mixed**
* $id_product_attribute **mixed**
* $decimals **mixed**



### <a name="method-getPricesDrop"></a>getPricesDrop

```php
array ProductCore::getPricesDrop(integer $id_lang, $page_number, $nb_products, boolean $count, $order_by, $order_way, $beginning, $ending, \Context $context)
```

Get prices drop



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2345](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L2345)


#### Arguments
* $id_lang **integer** - Language id
* $page_number **mixed**
* $nb_products **mixed**
* $count **boolean** - Only in order to get total number (optional)
* $order_by **mixed**
* $order_way **mixed**
* $beginning **mixed**
* $ending **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getProductAttributePrice"></a>getProductAttributePrice

```php
mixed ProductCore::getProductAttributePrice($id_product_attribute)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 1098](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1098)


#### Arguments
* $id_product_attribute **mixed**



### <a name="method-getProductAttributesIds"></a>getProductAttributesIds

```php
array ProductCore::getProductAttributesIds(integer $id_product, $shop_only)
```

Get all product attributes ids



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 5214](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5214)


#### Arguments
* $id_product **integer** - the id of the product
* $shop_only **mixed**



### <a name="method-getProductCategories"></a>getProductCategories

```php
array ProductCore::getProductCategories($id_product)
```

getProductCategories return an array of categories which this product belongs to



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2456](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L2456)


#### Arguments
* $id_product **mixed**



### <a name="method-getProductCategoriesFull"></a>getProductCategoriesFull

```php
mixed ProductCore::getProductCategoriesFull($id_product, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2477](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L2477)


#### Arguments
* $id_product **mixed**
* $id_lang **mixed**



### <a name="method-getProductName"></a>getProductName

```php
string ProductCore::getProductName(integer $id_product, integer $id_product_attribute, integer $id_lang)
```

Gets the name of a given product, in the given lang



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 5458](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5458)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - Optional
* $id_lang **integer** - Optional



### <a name="method-getProductProperties"></a>getProductProperties

```php
mixed ProductCore::getProductProperties($id_lang, $row, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 4028](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4028)


#### Arguments
* $id_lang **mixed**
* $row **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getProducts"></a>getProducts

```php
array ProductCore::getProducts(integer $id_lang, integer $start, integer $limit, string $order_by, string $order_way, $id_category, $only_active, \Context $context)
```

Get all available products



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 1113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1113)


#### Arguments
* $id_lang **integer** - Language id
* $start **integer** - Start number
* $limit **integer** - Number of products to return
* $order_by **string** - Field for ordering
* $order_way **string** - Way for ordering (ASC or DESC)
* $id_category **mixed**
* $only_active **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getProductsProperties"></a>getProductsProperties

```php
mixed ProductCore::getProductsProperties($id_lang, $query_result)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 4193](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4193)


#### Arguments
* $id_lang **mixed**
* $query_result **mixed**



### <a name="method-getPublicPrice"></a>getPublicPrice

```php
mixed ProductCore::getPublicPrice($tax, $id_product_attribute, $decimals, $divisor, $only_reduc, $usereduc, $quantity)
```





* Visibility: **public**
* Source: [classes/Product.php line 2999](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L2999)


#### Arguments
* $tax **mixed**
* $id_product_attribute **mixed**
* $decimals **mixed**
* $divisor **mixed**
* $only_reduc **mixed**
* $usereduc **mixed**
* $quantity **mixed**



### <a name="method-getQuantity"></a>getQuantity

```php
integer ProductCore::getQuantity(integer $id_product, integer $id_product_attribute, $cache_is_pack)
```

Get available product quantities



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3091](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3091)


#### Arguments
* $id_product **integer** - Product id
* $id_product_attribute **integer** - Product attribute id (optional)
* $cache_is_pack **mixed**



### <a name="method-getRandomSpecial"></a>getRandomSpecial

```php
array ProductCore::getRandomSpecial(integer $id_lang, $beginning, $ending, \Context $context)
```

Get a random special



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2260](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L2260)


#### Arguments
* $id_lang **integer** - Language id
* $beginning **mixed**
* $ending **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getRealQuantity"></a>getRealQuantity

```php
integer ProductCore::getRealQuantity(integer $id_product, integer $id_product_attribute, integer $id_warehouse, integer $id_shop)
```

For a given product, returns its real quantity



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 5522](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5522)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $id_warehouse **integer**
* $id_shop **integer**



### <a name="method-getRepositoryClassName"></a>getRepositoryClassName

```php
mixed ObjectModelCore::getRepositoryClassName()
```

Returns the name of the repository class for this entity.

If unspecified, a generic repository will be used for the entity.

* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L166)




### <a name="method-getRequiredCustomizableFields"></a>getRequiredCustomizableFields

```php
mixed ProductCore::getRequiredCustomizableFields()
```





* Visibility: **public**
* Source: [classes/Product.php line 4557](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4557)




### <a name="method-getRequiredCustomizableFieldsStatic"></a>getRequiredCustomizableFieldsStatic

```php
mixed ProductCore::getRequiredCustomizableFieldsStatic($id)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 4564](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4564)


#### Arguments
* $id **mixed**



### <a name="method-getShopsByProduct"></a>getShopsByProduct

```php
mixed ProductCore::getShopsByProduct($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 5646](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5646)


#### Arguments
* $id_product **mixed**



### <a name="method-getSimpleProducts"></a>getSimpleProducts

```php
mixed ProductCore::getSimpleProducts($id_lang, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 1161](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1161)


#### Arguments
* $id_lang **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getStockMvts"></a>getStockMvts

```php
mixed ProductCore::getStockMvts($id_lang)
```





* Visibility: **public**
* Source: [classes/Product.php line 4700](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4700)


#### Arguments
* $id_lang **mixed**



### <a name="method-getTags"></a>getTags

```php
mixed ProductCore::getTags($id_lang)
```





* Visibility: **public**
* Source: [classes/Product.php line 4005](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4005)


#### Arguments
* $id_lang **mixed**



### <a name="method-getTaxCalculationMethod"></a>getTaxCalculationMethod

```php
mixed ProductCore::getTaxCalculationMethod($id_customer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 592](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L592)


#### Arguments
* $id_customer **mixed**



### <a name="method-getTaxesInformations"></a>getTaxesInformations

```php
mixed ProductCore::getTaxesInformations($row, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 4173](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4173)


#### Arguments
* $row **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getTaxesRate"></a>getTaxesRate

```php
float ProductCore::getTaxesRate(\Address|null $address)
```

Returns tax rate.



* Visibility: **public**
* Source: [classes/Product.php line 4773](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4773)


#### Arguments
* $address **[Address](class.AddressCore.md)|null**



### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
array ObjectModelCore::getTranslationsFields(array $fields_array)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 806](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L806)


#### Arguments
* $fields_array **array**



### <a name="method-getType"></a>getType

```php
integer ProductCore::getType()
```

Get the product type (simple, virtual, pack)



* Visibility: **public**
* Source: [classes/Product.php line 5700](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5700)




### <a name="method-getUrlRewriteInformations"></a>getUrlRewriteInformations

```php
mixed ProductCore::getUrlRewriteInformations($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 4731](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4731)


#### Arguments
* $id_product **mixed**



### <a name="method-getValidationRules"></a>getValidationRules

```php
array ObjectModelCore::getValidationRules(string $class)
```

Returns object validation rules (fields validity)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L178)


#### Arguments
* $class **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
array|null ObjectModelCore::getWebserviceObjectList(string $sql_join, string $sql_filter, string $sql_sort, string $sql_limit)
```

Returns webservice object list.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1230](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1230)


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
* Source: [classes/ObjectModel.php line 1140](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1140)


#### Arguments
* $ws_params_attribute_name **string|null**



### <a name="method-getWsAccessories"></a>getWsAccessories

```php
array ProductCore::getWsAccessories()
```

Webservice getter : get product accessories ids of current product for association



* Visibility: **public**
* Source: [classes/Product.php line 4901](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4901)




### <a name="method-getWsCategories"></a>getWsCategories

```php
array ProductCore::getWsCategories()
```

Webservice getter : get category ids of current product for association



* Visibility: **public**
* Source: [classes/Product.php line 4853](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4853)




### <a name="method-getWsCombinations"></a>getWsCombinations

```php
array ProductCore::getWsCombinations()
```

Webservice getter : get combination ids of current product for association



* Visibility: **public**
* Source: [classes/Product.php line 4933](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4933)




### <a name="method-getWsDefaultCombination"></a>getWsDefaultCombination

```php
integer ProductCore::getWsDefaultCombination()
```

Webservice getter : get virtual field default combination



* Visibility: **public**
* Source: [classes/Product.php line 4831](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4831)




### <a name="method-getWsImages"></a>getWsImages

```php
array ProductCore::getWsImages()
```

Webservice getter : get image ids of current product for association



* Visibility: **public**
* Source: [classes/Product.php line 5106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5106)




### <a name="method-getWsManufacturerName"></a>getWsManufacturerName

```php
mixed ProductCore::getWsManufacturerName()
```





* Visibility: **public**
* Source: [classes/Product.php line 5173](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5173)




### <a name="method-getWsPositionInCategory"></a>getWsPositionInCategory

```php
integer ProductCore::getWsPositionInCategory()
```

Webservice getter : get virtual field position in category



* Visibility: **public**
* Source: [classes/Product.php line 5024](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5024)




### <a name="method-getWsProductBundle"></a>getWsProductBundle

```php
mixed ProductCore::getWsProductBundle()
```





* Visibility: **public**
* Source: [classes/Product.php line 5787](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5787)




### <a name="method-getWsProductFeatures"></a>getWsProductFeatures

```php
array ProductCore::getWsProductFeatures()
```

Webservice getter : get product features association



* Visibility: **public**
* Source: [classes/Product.php line 4789](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4789)




### <a name="method-getWsProductOptionValues"></a>getWsProductOptionValues

```php
array ProductCore::getWsProductOptionValues()
```

Webservice getter : get product option ids of current product for association



* Visibility: **public**
* Source: [classes/Product.php line 5009](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5009)




### <a name="method-getWsStockAvailables"></a>getWsStockAvailables

```php
mixed ProductCore::getWsStockAvailables()
```





* Visibility: **public**
* Source: [classes/Product.php line 5116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5116)




### <a name="method-getWsTags"></a>getWsTags

```php
mixed ProductCore::getWsTags()
```





* Visibility: **public**
* Source: [classes/Product.php line 5123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5123)




### <a name="method-getWsType"></a>getWsType

```php
mixed ProductCore::getWsType()
```





* Visibility: **public**
* Source: [classes/Product.php line 5761](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5761)




### <a name="method-hasAllRequiredCustomizableFields"></a>hasAllRequiredCustomizableFields

```php
mixed ProductCore::hasAllRequiredCustomizableFields(\Context $context)
```





* Visibility: **public**
* Source: [classes/Product.php line 4576](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4576)


#### Arguments
* $context **[Context](class.ContextCore.md)**



### <a name="method-hasAttributes"></a>hasAttributes

```php
integer ProductCore::hasAttributes()
```

Check if product has attributes combinations



* Visibility: **public**
* Source: [classes/Product.php line 2111](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L2111)




### <a name="method-hasAttributesInOtherShops"></a>hasAttributesInOtherShops

```php
mixed ProductCore::hasAttributesInOtherShops()
```





* Visibility: **public**
* Source: [classes/Product.php line 5712](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5712)




### <a name="method-hasMultishopEntries"></a>hasMultishopEntries

```php
boolean ObjectModelCore::hasMultishopEntries()
```

Checks if there is more than one entry in associated shop table for current object.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1488](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1488)




### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer|null $id_lang)
```

Fill an object with given data. Data must be an array with this syntax:
array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1666](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1666)


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
* Source: [classes/ObjectModel.php line 1688](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1688)


#### Arguments
* $class **string** - Class of objects to hydrate
* $datas **array** - List of data (multi-dimensional array)
* $id_lang **integer|null**



### <a name="method-idIsOnCategoryId"></a>idIsOnCategoryId

```php
boolean ProductCore::idIsOnCategoryId(integer $id_product, array $categories)
```

Checks if the product is in at least one of the submited categories



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 4606](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4606)


#### Arguments
* $id_product **integer**
* $categories **array** - array of category arrays



### <a name="method-initPricesComputation"></a>initPricesComputation

```php
mixed ProductCore::initPricesComputation($id_customer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 568](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L568)


#### Arguments
* $id_customer **mixed**



### <a name="method-isAssociatedToShop"></a>isAssociatedToShop

```php
boolean ObjectModelCore::isAssociatedToShop(integer|null $id_shop)
```

Checks if current object is associated to a shop.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1375](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1375)


#### Arguments
* $id_shop **integer|null**



### <a name="method-isAvailableWhenOutOfStock"></a>isAvailableWhenOutOfStock

```php
mixed ProductCore::isAvailableWhenOutOfStock($out_of_stock)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3171](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3171)


#### Arguments
* $out_of_stock **mixed**



### <a name="method-isColorUnavailable"></a>isColorUnavailable

```php
mixed ProductCore::isColorUnavailable($id_attribute, $id_shop)
```





* Visibility: **public**
* Source: [classes/Product.php line 5827](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5827)


#### Arguments
* $id_attribute **mixed**
* $id_shop **mixed**



### <a name="method-isCurrentlyUsed"></a>isCurrentlyUsed

```php
boolean ObjectModelCore::isCurrentlyUsed(string|null $table, boolean $has_active_column)
```

Checks if an object type exists in the database.



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1644](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1644)


#### Arguments
* $table **string|null** - Name of table linked to entity
* $has_active_column **boolean** - True if the table has an active column



### <a name="method-isDiscounted"></a>isDiscounted

```php
mixed ProductCore::isDiscounted($id_product, $quantity, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2964](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L2964)


#### Arguments
* $id_product **mixed**
* $quantity **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-isLangMultishop"></a>isLangMultishop

```php
boolean ObjectModelCore::isLangMultishop()
```

Checks if the object is both multi-language and multi-shop.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1523](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1523)




### <a name="method-isMultiShopField"></a>isMultiShopField

```php
boolean ObjectModelCore::isMultiShopField(string $field)
```

Checks if a field is a multi-shop field.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1513](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1513)


#### Arguments
* $field **string**



### <a name="method-isMultishop"></a>isMultishop

```php
boolean ObjectModelCore::isMultishop()
```

Checks if object is multi-shop object.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1501](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1501)




### <a name="method-isNew"></a>isNew

```php
mixed ProductCore::isNew()
```





* Visibility: **public**
* Source: [classes/Product.php line 1180](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1180)




### <a name="method-loadStockData"></a>loadStockData

```php
mixed ProductCore::loadStockData()
```

Fill the variables used for stock management



* Visibility: **public**
* Source: [classes/Product.php line 5590](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5590)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields(array $fields, array $fields_array, integer $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 827](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L827)


#### Arguments
* $fields **array**
* $fields_array **array**
* $id_language **integer**



### <a name="method-modifierWsLinkRewrite"></a>modifierWsLinkRewrite

```php
mixed ProductCore::modifierWsLinkRewrite()
```





* Visibility: **public**
* Source: [classes/Product.php line 5774](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5774)




### <a name="method-priceCalculation"></a>priceCalculation

```php
float ProductCore::priceCalculation(integer $id_shop, integer $id_product, integer $id_product_attribute, integer $id_country, integer $id_state, string $zipcode, integer $id_currency, integer $id_group, integer $quantity, boolean $use_tax, integer $decimals, boolean $only_reduc, boolean $use_reduc, boolean $with_ecotax, null $specific_price, boolean $use_group_reduction, integer $id_customer, boolean $use_customer_price, integer $id_cart, integer $real_quantity)
```

Price calculation / Get product price



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2769](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L2769)


#### Arguments
* $id_shop **integer** - Shop id
* $id_product **integer** - Product id
* $id_product_attribute **integer** - Product attribute id
* $id_country **integer** - Country id
* $id_state **integer** - State id
* $zipcode **string**
* $id_currency **integer** - Currency id
* $id_group **integer** - Group id
* $quantity **integer** - Quantity Required for Specific prices : quantity discount application
* $use_tax **boolean** - with (1) or without (0) tax
* $decimals **integer** - Number of decimals returned
* $only_reduc **boolean** - Returns only the reduction amount
* $use_reduc **boolean** - Set if the returned amount will include reduction
* $with_ecotax **boolean** - insert ecotax in price output.
* $specific_price **null** - If a specific price applies regarding the previous parameters,
                              this variable is filled with the corresponding SpecificPrice object
* $use_group_reduction **boolean**
* $id_customer **integer**
* $use_customer_price **boolean**
* $id_cart **integer**
* $real_quantity **integer**



### <a name="method-productAttributeExists"></a>productAttributeExists

```php
mixed ProductCore::productAttributeExists($attributes_list, $current_product_attribute, \Context $context, $all_shops, $return_id)
```





* Visibility: **public**
* Source: [classes/Product.php line 1198](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1198)


#### Arguments
* $attributes_list **mixed**
* $current_product_attribute **mixed**
* $context **[Context](class.ContextCore.md)**
* $all_shops **mixed**
* $return_id **mixed**



### <a name="method-reinjectQuantities"></a>reinjectQuantities

```php
false ProductCore::reinjectQuantities()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3164](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3164)




### <a name="method-resetEcoTax"></a>resetEcoTax

```php
mixed ProductCore::resetEcoTax()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 5178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5178)




### <a name="method-save"></a>save

```php
boolean ObjectModelCore::save(boolean $null_values, boolean $auto_date)
```

Saves current object to database (add or update)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 429](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L429)


#### Arguments
* $null_values **boolean**
* $auto_date **boolean**



### <a name="method-searchByName"></a>searchByName

```php
array ProductCore::searchByName(integer $id_lang, string $query, \Context $context)
```

Admin panel product search



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3552](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3552)


#### Arguments
* $id_lang **integer** - Language id
* $query **string** - Search query
* $context **[Context](class.ContextCore.md)**



### <a name="method-setAdvancedStockManagement"></a>setAdvancedStockManagement

```php
mixed ProductCore::setAdvancedStockManagement($value)
```





* Visibility: **public**
* Source: [classes/Product.php line 5612](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5612)


#### Arguments
* $value **mixed**



### <a name="method-setAvailableDate"></a>setAvailableDate

```php
mixed ProductCore::setAvailableDate($available_date)
```





* Visibility: **public**
* Source: [classes/Product.php line 746](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L746)


#### Arguments
* $available_date **mixed**



### <a name="method-setCarriers"></a>setCarriers

```php
mixed ProductCore::setCarriers($carrier_list)
```

Sets carriers assigned to the product



* Visibility: **public**
* Source: [classes/Product.php line 2525](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L2525)


#### Arguments
* $carrier_list **mixed**



### <a name="method-setCoverWs"></a>setCoverWs

```php
boolean ProductCore::setCoverWs($id_image)
```

Webservice setter : set virtual field id_default_image in category



* Visibility: **public**
* Source: [classes/Product.php line 5089](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5089)


#### Arguments
* $id_image **mixed**



### <a name="method-setDefaultAttribute"></a>setDefaultAttribute

```php
mixed ProductCore::setDefaultAttribute($id_product_attribute)
```





* Visibility: **public**
* Source: [classes/Product.php line 1379](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1379)


#### Arguments
* $id_product_attribute **mixed**



### <a name="method-setDefinitionRetrocompatibility"></a>setDefinitionRetrocompatibility

```php
mixed ObjectModelCore::setDefinitionRetrocompatibility()
```

Retrocompatibility for classes without $definition static



* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1778](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1778)




### <a name="method-setFieldsToUpdate"></a>setFieldsToUpdate

```php
mixed ObjectModelCore::setFieldsToUpdate(array $fields)
```

Set a list of specific fields to update
array(field1 => true, field2 => false,
langfield1 => array(1 => true, 2 => false))



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1876](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1876)


#### Arguments
* $fields **array**



### <a name="method-setGroupReduction"></a>setGroupReduction

```php
mixed ProductCore::setGroupReduction()
```

Set Group reduction if needed



* Visibility: **public**
* Source: [classes/Product.php line 5188](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5188)




### <a name="method-setPackStockType"></a>setPackStockType

```php
mixed ProductCore::setPackStockType($id_product, $pack_stock_type)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 5851](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5851)


#### Arguments
* $id_product **mixed**
* $pack_stock_type **mixed**



### <a name="method-setWsAccessories"></a>setWsAccessories

```php
mixed ProductCore::setWsAccessories($accessories)
```

Webservice setter : set product accessories ids of current product for association



* Visibility: **public**
* Source: [classes/Product.php line 4919](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4919)


#### Arguments
* $accessories **mixed** - product ids



### <a name="method-setWsCategories"></a>setWsCategories

```php
boolean ProductCore::setWsCategories(array $category_ids)
```

Webservice setter : set category ids of current product for association



* Visibility: **public**
* Source: [classes/Product.php line 4871](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4871)


#### Arguments
* $category_ids **array** - category ids



### <a name="method-setWsCombinations"></a>setWsCombinations

```php
mixed ProductCore::setWsCombinations($combinations)
```

Webservice setter : set combination ids of current product for association



* Visibility: **public**
* Source: [classes/Product.php line 4950](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4950)


#### Arguments
* $combinations **mixed** - combination ids



### <a name="method-setWsDefaultCombination"></a>setWsDefaultCombination

```php
boolean ProductCore::setWsDefaultCombination(integer $id_combination)
```

Webservice setter : set virtual field default combination



* Visibility: **public**
* Source: [classes/Product.php line 4842](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4842)


#### Arguments
* $id_combination **integer** - id default combination



### <a name="method-setWsPositionInCategory"></a>setWsPositionInCategory

```php
boolean ProductCore::setWsPositionInCategory($position)
```

Webservice setter : set virtual field position in category



* Visibility: **public**
* Source: [classes/Product.php line 5040](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5040)


#### Arguments
* $position **mixed**



### <a name="method-setWsProductBundle"></a>setWsProductBundle

```php
mixed ProductCore::setWsProductBundle($items)
```





* Visibility: **public**
* Source: [classes/Product.php line 5814](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5814)


#### Arguments
* $items **mixed**



### <a name="method-setWsProductFeatures"></a>setWsProductFeatures

```php
boolean ProductCore::setWsProductFeatures($product_features)
```

Webservice setter : set product features association



* Visibility: **public**
* Source: [classes/Product.php line 4815](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4815)


#### Arguments
* $product_features **mixed** - Product Feature ids



### <a name="method-setWsTags"></a>setWsTags

```php
mixed ProductCore::setWsTags($tag_ids)
```

Webservice setter : set tag ids of current product for association



* Visibility: **public**
* Source: [classes/Product.php line 5136](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5136)


#### Arguments
* $tag_ids **mixed** - tag ids



### <a name="method-setWsType"></a>setWsType

```php
mixed ProductCore::setWsType($type_str)
```





* Visibility: **public**
* Source: [classes/Product.php line 5792](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5792)


#### Arguments
* $type_str **mixed**



### <a name="method-sqlStock"></a>sqlStock

```php
string ProductCore::sqlStock($product_alias, $product_attribute, $inner_join, \Shop $shop)
```

Create JOIN query with 'stock_available' table



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3112)


#### Arguments
* $product_alias **mixed**
* $product_attribute **mixed**
* $inner_join **mixed**
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-toggleStatus"></a>toggleStatus

```php
mixed ProductCore::toggleStatus()
```





* Visibility: **public**
* Source: [classes/Product.php line 820](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L820)




### <a name="method-update"></a>update

```php
mixed ProductCore::update($null_values)
```





* Visibility: **public**
* Source: [classes/Product.php line 547](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L547)


#### Arguments
* $null_values **mixed**



### <a name="method-updateAttribute"></a>updateAttribute

```php
array ProductCore::updateAttribute(integer $id_product_attribute, float $wholesale_price, float $price, float $weight, float $unit, float $ecotax, $id_images, string $reference, string $ean13, integer $default, $location, string $upc, string $minimal_quantity, $available_date, $update_all_fields, array $id_shop_list)
```

Update a product attribute



* Visibility: **public**
* Source: [classes/Product.php line 1485](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1485)


#### Arguments
* $id_product_attribute **integer** - Product attribute id
* $wholesale_price **float** - Wholesale price
* $price **float** - Additional price
* $weight **float** - Additional weight
* $unit **float**
* $ecotax **float** - Additional ecotax
* $id_images **mixed**
* $reference **string** - Reference
* $ean13 **string** - Ean-13 barcode
* $default **integer** - Default On
* $location **mixed**
* $upc **string** - Upc barcode
* $minimal_quantity **string** - Minimal quantity
* $available_date **mixed**
* $update_all_fields **mixed**
* $id_shop_list **array**



### <a name="method-updateCacheAttachment"></a>updateCacheAttachment

```php
mixed ProductCore::updateCacheAttachment($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 1690](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1690)


#### Arguments
* $id_product **mixed**



### <a name="method-updateCategories"></a>updateCategories

```php
array ProductCore::updateCategories($categories, boolean $keeping_current_pos)
```

Update categories to index product into



* Visibility: **public**
* Source: [classes/Product.php line 975](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L975)


#### Arguments
* $categories **mixed**
* $keeping_current_pos **boolean** - (deprecated, no more used)



### <a name="method-updateDefaultAttribute"></a>updateDefaultAttribute

```php
mixed ProductCore::updateDefaultAttribute($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 1392](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1392)


#### Arguments
* $id_product **mixed**



### <a name="method-updateIsVirtual"></a>updateIsVirtual

```php
mixed ProductCore::updateIsVirtual($id_product, $is_virtual)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 795](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L795)


#### Arguments
* $id_product **mixed**
* $is_virtual **mixed**



### <a name="method-updateLabels"></a>updateLabels

```php
mixed ProductCore::updateLabels()
```





* Visibility: **public**
* Source: [classes/Product.php line 4477](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L4477)




### <a name="method-updateMultishopTable"></a>updateMultishopTable

```php
boolean ObjectModelCore::updateMultishopTable(string $classname, array $data, string $where, string $specific_where)
```

Updates a table and splits the common datas and the shop datas.



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1539](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1539)


#### Arguments
* $classname **string**
* $data **array**
* $where **string**
* $specific_where **string** - Only executed for common table



### <a name="method-updatePosition"></a>updatePosition

```php
mixed ProductCore::updatePosition(boolean $way, integer $position)
```

Move a product inside its category



* Visibility: **public**
* Source: [classes/Product.php line 606](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L606)


#### Arguments
* $way **boolean** - Up (1)  or Down (0)
* $position **integer** - return boolean Update result



### <a name="method-updateProductAttribute"></a>updateProductAttribute

```php
mixed ProductCore::updateProductAttribute($id_product_attribute, $wholesale_price, $price, $weight, $unit, $ecotax, $id_images, $reference, $id_supplier, $ean13, $default, $location, $upc, $minimal_quantity, $available_date)
```

Update a product attribute



* Visibility: **public**
* Source: [classes/Product.php line 1418](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1418)


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



### <a name="method-updateQuantity"></a>updateQuantity

```php
false ProductCore::updateQuantity()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3146](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L3146)




### <a name="method-updateQuantityProductWithAttributeQuantity"></a>updateQuantityProductWithAttributeQuantity

```php
mixed ProductCore::updateQuantityProductWithAttributeQuantity()
```





* Visibility: **public**
* Source: [classes/Product.php line 1632](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L1632)




### <a name="method-updateWs"></a>updateWs

```php
mixed ProductCore::updateWs($null_values)
```





* Visibility: **public**
* Source: [classes/Product.php line 5503](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5503)


#### Arguments
* $null_values **mixed**



### <a name="method-useAdvancedStockManagement"></a>useAdvancedStockManagement

```php
mixed ProductCore::useAdvancedStockManagement()
```





* Visibility: **public**
* Source: [classes/Product.php line 5603](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5603)




### <a name="method-usesAdvancedStockManagement"></a>usesAdvancedStockManagement

```php
boolean ProductCore::usesAdvancedStockManagement(integer $id_product)
```

For a given product, tells if it uses the advanced stock management



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 5543](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L5543)


#### Arguments
* $id_product **integer**



### <a name="method-validateControler"></a>validateControler

```php
array ObjectModelCore::validateControler(boolean $htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1071](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1071)


#### Arguments
* $htmlentities **boolean**



### <a name="method-validateController"></a>validateController

```php
array ObjectModelCore::validateController(boolean $htmlentities)
```

Validates submitted values and returns an array of errors, if any.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1084](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1084)


#### Arguments
* $htmlentities **boolean** - If true, uses htmlentities() for field name translations in errors.



### <a name="method-validateField"></a>validateField

```php
mixed ProductCore::validateField($field, $value, $id_lang, $skip, $human_errors)
```





* Visibility: **public**
* Source: [classes/Product.php line 805](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Product.php#L805)


#### Arguments
* $field **mixed**
* $value **mixed**
* $id_lang **mixed**
* $skip **mixed**
* $human_errors **mixed**



### <a name="method-validateFields"></a>validateFields

```php
boolean|string ObjectModelCore::validateFields(boolean $die, boolean $error_return)
```

Checks if object field values are valid before database interaction



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 867](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L867)


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
* Source: [classes/ObjectModel.php line 898](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L898)


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
* Source: [classes/ObjectModel.php line 1275](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/ObjectModel.php#L1275)


#### Arguments
* $htmlentities **boolean**


