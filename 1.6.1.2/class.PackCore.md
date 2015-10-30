Class PackCore
=====================





* Class name: PackCore
* Parent class: [Product](class.ProductCore.md)
* Source: [classes/Pack.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Pack.php#L27)


Contents
--------


### Properties

* [$cacheIsPack](#property-$cacheIsPack)
* [$cacheIsPacked](#property-$cacheIsPacked)
* [$cachePackItems](#property-$cachePackItems)
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
* [addItem](#method-addItem)
* [addProductAttribute](#method-addProductAttribute)
* [addProductAttributeMultiple](#method-addProductAttributeMultiple)
* [addStockMvt](#method-addStockMvt)
* [addSupplierReference](#method-addSupplierReference)
* [addToCategories](#method-addToCategories)
* [addWs](#method-addWs)
* [allUsesAdvancedStockManagement](#method-allUsesAdvancedStockManagement)
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
* [deleteItems](#method-deleteItems)
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
* [duplicate](#method-duplicate)
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
* [getItemTable](#method-getItemTable)
* [getItems](#method-getItems)
* [getLink](#method-getLink)
* [getNewProducts](#method-getNewProducts)
* [getNoPackPrice](#method-getNoPackPrice)
* [getPacksContainingItem](#method-getPacksContainingItem)
* [getPacksTable](#method-getPacksTable)
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
* [isFeatureActive](#method-isFeatureActive)
* [isInStock](#method-isInStock)
* [isLangMultishop](#method-isLangMultishop)
* [isMultiShopField](#method-isMultiShopField)
* [isMultishop](#method-isMultishop)
* [isNew](#method-isNew)
* [isPack](#method-isPack)
* [isPacked](#method-isPacked)
* [loadStockData](#method-loadStockData)
* [makeTranslationFields](#method-makeTranslationFields)
* [modifierWsLinkRewrite](#method-modifierWsLinkRewrite)
* [noPackPrice](#method-noPackPrice)
* [noPackWholesalePrice](#method-noPackWholesalePrice)
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




Properties
----------


### <a name="property-$cacheIsPack"></a>$cacheIsPack

```php
protected mixed $cacheIsPack = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Pack.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Pack.php#L30).


### <a name="property-$cacheIsPacked"></a>$cacheIsPacked

```php
protected mixed $cacheIsPacked = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Pack.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Pack.php#L31).


### <a name="property-$cachePackItems"></a>$cachePackItems

```php
protected mixed $cachePackItems = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Pack.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Pack.php#L29).


### <a name="property-$_cacheFeatures"></a>$_cacheFeatures

```php
protected mixed $_cacheFeatures = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 254](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L254).


### <a name="property-$_cart_quantity"></a>$_cart_quantity

```php
protected array $_cart_quantity = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 251](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L251).


### <a name="property-$_frontFeaturesCache"></a>$_frontFeaturesCache

```php
protected mixed $_frontFeaturesCache = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L255).


### <a name="property-$_incat"></a>$_incat

```php
protected mixed $_incat = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 245](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L245).


### <a name="property-$_prices"></a>$_prices

```php
protected mixed $_prices = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 243](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L243).


### <a name="property-$_pricesLevel2"></a>$_pricesLevel2

```php
protected mixed $_pricesLevel2 = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 244](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L244).


### <a name="property-$_taxCalculationMethod"></a>$_taxCalculationMethod

```php
public mixed $_taxCalculationMethod = null
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 242](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L242).


### <a name="property-$_tax_rules_group"></a>$_tax_rules_group

```php
protected mixed $_tax_rules_group = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 253](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L253).


### <a name="property-$active"></a>$active

```php
public boolean $active = true
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L167).


### <a name="property-$additional_shipping_cost"></a>$additional_shipping_cost

```php
public float $additional_shipping_cost
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L89).


### <a name="property-$advanced_stock_management"></a>$advanced_stock_management

```php
public boolean $advanced_stock_management
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 220](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L220).


### <a name="property-$available_date"></a>$available_date

```php
public string $available_date = '0000-00-00'
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L179).


### <a name="property-$available_for_order"></a>$available_for_order

```php
public boolean $available_for_order = true
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L176).


### <a name="property-$available_later"></a>$available_later

```php
public string $available_later
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L81).


### <a name="property-$available_now"></a>$available_now

```php
public string $available_now
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L78).


### <a name="property-$base_price"></a>$base_price

```php
public float $base_price
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 206](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L206).


### <a name="property-$cacheStock"></a>$cacheStock

```php
protected array $cacheStock = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 259](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L259).


### <a name="property-$cache_default_attribute"></a>$cache_default_attribute

```php
public mixed $cache_default_attribute
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 230](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L230).


### <a name="property-$cache_has_attachments"></a>$cache_has_attachments

```php
public mixed $cache_has_attachments
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 227](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L227).


### <a name="property-$cache_is_pack"></a>$cache_is_pack

```php
public mixed $cache_is_pack
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 226](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L226).


### <a name="property-$category"></a>$category

```php
public string $category
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 235](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L235).


### <a name="property-$condition"></a>$condition

```php
public string $condition
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L182).


### <a name="property-$customizable"></a>$customizable

```php
public boolean $customizable
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L155).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 194](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L194).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 197](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L197).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'product', 'primary' => 'id_product', 'multilang' => true, 'multilang_shop' => true, 'fields' => array('id_shop_default' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_manufacturer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_supplier' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'reference' => array('type' => self::TYPE_STRING, 'validate' => 'isReference', 'size' => 32), 'supplier_reference' => array('type' => self::TYPE_STRING, 'validate' => 'isReference', 'size' => 32), 'location' => array('type' => self::TYPE_STRING, 'validate' => 'isReference', 'size' => 64), 'width' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat'), 'height' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat'), 'depth' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat'), 'weight' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat'), 'quantity_discount' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'ean13' => array('type' => self::TYPE_STRING, 'validate' => 'isEan13', 'size' => 13), 'upc' => array('type' => self::TYPE_STRING, 'validate' => 'isUpc', 'size' => 12), 'cache_is_pack' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'cache_has_attachments' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'is_virtual' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'id_category_default' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedId'), 'id_tax_rules_group' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedId'), 'on_sale' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'online_only' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'ecotax' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isPrice'), 'minimal_quantity' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedInt'), 'price' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isPrice', 'required' => true), 'wholesale_price' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isPrice'), 'unity' => array('type' => self::TYPE_STRING, 'shop' => true, 'validate' => 'isString'), 'unit_price_ratio' => array('type' => self::TYPE_FLOAT, 'shop' => true), 'additional_shipping_cost' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isPrice'), 'customizable' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedInt'), 'text_fields' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedInt'), 'uploadable_files' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedInt'), 'active' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'redirect_type' => array('type' => self::TYPE_STRING, 'shop' => true, 'validate' => 'isString'), 'id_product_redirected' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedId'), 'available_for_order' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'available_date' => array('type' => self::TYPE_DATE, 'shop' => true, 'validate' => 'isDateFormat'), 'condition' => array('type' => self::TYPE_STRING, 'shop' => true, 'validate' => 'isGenericName', 'values' => array('new', 'used', 'refurbished'), 'default' => 'new'), 'show_price' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'indexed' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'visibility' => array('type' => self::TYPE_STRING, 'shop' => true, 'validate' => 'isProductVisibility', 'values' => array('both', 'catalog', 'search', 'none'), 'default' => 'both'), 'cache_default_attribute' => array('type' => self::TYPE_INT, 'shop' => true), 'advanced_stock_management' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'date_add' => array('type' => self::TYPE_DATE, 'shop' => true, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'shop' => true, 'validate' => 'isDate'), 'pack_stock_type' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedInt'), 'meta_description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_keywords' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_title' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 128), 'link_rewrite' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isLinkRewrite', 'required' => true, 'size' => 128, 'ws_modifier' => array('http_method' => \WebserviceRequest::HTTP_POST, 'modifier' => 'modifierWsLinkRewrite')), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isCatalogName', 'required' => true, 'size' => 128), 'description' => array('type' => self::TYPE_HTML, 'lang' => true, 'validate' => 'isCleanHtml'), 'description_short' => array('type' => self::TYPE_HTML, 'lang' => true, 'validate' => 'isCleanHtml'), 'available_now' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'available_later' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'IsGenericName', 'size' => 255)), 'associations' => array('manufacturer' => array('type' => self::HAS_ONE), 'supplier' => array('type' => self::HAS_ONE), 'default_category' => array('type' => self::HAS_ONE, 'field' => 'id_category_default', 'object' => 'Category'), 'tax_rules_group' => array('type' => self::HAS_ONE), 'categories' => array('type' => self::HAS_MANY, 'field' => 'id_category', 'object' => 'Category', 'association' => 'category_product'), 'stock_availables' => array('type' => self::HAS_MANY, 'field' => 'id_stock_available', 'object' => 'StockAvailable', 'association' => 'stock_availables')))
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 261](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L261).


### <a name="property-$depends_on_stock"></a>$depends_on_stock

```php
public mixed $depends_on_stock
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L222).


### <a name="property-$depth"></a>$depth

```php
public string $depth
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L128).


### <a name="property-$description"></a>$description

```php
public string $description
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L66).


### <a name="property-$description_short"></a>$description_short

```php
public string $description_short
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L69).


### <a name="property-$ean13"></a>$ean13

```php
public string $ean13
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L134).


### <a name="property-$ecotax"></a>$ecotax

```php
public float $ecotax
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L110).


### <a name="property-$height"></a>$height

```php
public string $height
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L125).


### <a name="property-$id_category_default"></a>$id_category_default

```php
public integer $id_category_default
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L51).


### <a name="property-$id_color_default"></a>$id_color_default

```php
public mixed $id_color_default
```

We keep this variable for retrocompatibility for themes



* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 214](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L214).


### <a name="property-$id_manufacturer"></a>$id_manufacturer

```php
public integer $id_manufacturer
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L45).


### <a name="property-$id_pack_product_attribute"></a>$id_pack_product_attribute

```php
public mixed $id_pack_product_attribute
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L229).


### <a name="property-$id_product_redirected"></a>$id_product_redirected

```php
public boolean $id_product_redirected
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L173).


### <a name="property-$id_shop_default"></a>$id_shop_default

```php
public integer $id_shop_default
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L54).


### <a name="property-$id_supplier"></a>$id_supplier

```php
public integer $id_supplier
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L48).


### <a name="property-$id_tax_rules_group"></a>$id_tax_rules_group

```php
public mixed $id_tax_rules_group = 1
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 208](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L208).


### <a name="property-$indexed"></a>$indexed

```php
public boolean $indexed
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 188](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L188).


### <a name="property-$isFullyLoaded"></a>$isFullyLoaded

```php
public mixed $isFullyLoaded = false
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 224](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L224).


### <a name="property-$is_virtual"></a>$is_virtual

```php
public mixed $is_virtual
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L228).


### <a name="property-$link_rewrite"></a>$link_rewrite

```php
public string $link_rewrite
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L140).


### <a name="property-$location"></a>$location

```php
public string $location
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L119).


### <a name="property-$manufacturer_name"></a>$manufacturer_name

```php
public string $manufacturer_name
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L57).


### <a name="property-$meta_description"></a>$meta_description

```php
public string $meta_description
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L143).


### <a name="property-$meta_keywords"></a>$meta_keywords

```php
public string $meta_keywords
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L146).


### <a name="property-$meta_title"></a>$meta_title

```php
public string $meta_title
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L149).


### <a name="property-$minimal_quantity"></a>$minimal_quantity

```php
public integer $minimal_quantity = 1
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L75).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L63).


### <a name="property-$new"></a>$new

```php
public boolean $new = null
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L158).


### <a name="property-$on_sale"></a>$on_sale

```php
public boolean $on_sale = false
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L95).


### <a name="property-$online_only"></a>$online_only

```php
public boolean $online_only = false
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L98).


### <a name="property-$out_of_stock"></a>$out_of_stock

```php
public mixed $out_of_stock
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L221).


### <a name="property-$pack_stock_type"></a>$pack_stock_type

```php
public integer $pack_stock_type = 3
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 240](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L240).


### <a name="property-$price"></a>$price

```php
public float $price
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L84).


### <a name="property-$producPropertiesCache"></a>$producPropertiesCache

```php
protected mixed $producPropertiesCache = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 256](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L256).


### <a name="property-$quantity"></a>$quantity

```php
public integer $quantity
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L72).


### <a name="property-$quantity_discount"></a>$quantity_discount

```php
public boolean $quantity_discount
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L152).


### <a name="property-$redirect_type"></a>$redirect_type

```php
public boolean $redirect_type = ''
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L170).


### <a name="property-$reference"></a>$reference

```php
public string $reference
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L113).


### <a name="property-$show_price"></a>$show_price

```php
public boolean $show_price = true
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 185](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L185).


### <a name="property-$specificPrice"></a>$specificPrice

```php
public mixed $specificPrice
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L86).


### <a name="property-$supplier_name"></a>$supplier_name

```php
public string $supplier_name
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L60).


### <a name="property-$supplier_reference"></a>$supplier_reference

```php
public string $supplier_reference
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L116).


### <a name="property-$tags"></a>$tags

```php
public mixed $tags
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L200).


### <a name="property-$tax_name"></a>$tax_name

```php
public string $tax_name
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L39).


### <a name="property-$tax_rate"></a>$tax_rate

```php
public string $tax_rate
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L42).


### <a name="property-$text_fields"></a>$text_fields

```php
public integer $text_fields
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L164).


### <a name="property-$unit_price"></a>$unit_price

```php
public float $unit_price
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L104).


### <a name="property-$unit_price_ratio"></a>$unit_price_ratio

```php
public float $unit_price_ratio
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L107).


### <a name="property-$unity"></a>$unity

```php
public string $unity = null
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L101).


### <a name="property-$upc"></a>$upc

```php
public string $upc
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L137).


### <a name="property-$uploadable_files"></a>$uploadable_files

```php
public integer $uploadable_files
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 161](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L161).


### <a name="property-$visibility"></a>$visibility

```php
public string $visibility
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L191).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectMethods' => array('add' => 'addWs', 'update' => 'updateWs'), 'objectNodeNames' => 'products', 'fields' => array('id_manufacturer' => array('xlink_resource' => 'manufacturers'), 'id_supplier' => array('xlink_resource' => 'suppliers'), 'id_category_default' => array('xlink_resource' => 'categories'), 'new' => array(), 'cache_default_attribute' => array(), 'id_default_image' => array('getter' => 'getCoverWs', 'setter' => 'setCoverWs', 'xlink_resource' => array('resourceName' => 'images', 'subResourceName' => 'products')), 'id_default_combination' => array('getter' => 'getWsDefaultCombination', 'setter' => 'setWsDefaultCombination', 'xlink_resource' => array('resourceName' => 'combinations')), 'id_tax_rules_group' => array('xlink_resource' => array('resourceName' => 'tax_rule_groups')), 'position_in_category' => array('getter' => 'getWsPositionInCategory', 'setter' => 'setWsPositionInCategory'), 'manufacturer_name' => array('getter' => 'getWsManufacturerName', 'setter' => false), 'quantity' => array('getter' => false, 'setter' => false), 'type' => array('getter' => 'getWsType', 'setter' => 'setWsType')), 'associations' => array('categories' => array('resource' => 'category', 'fields' => array('id' => array('required' => true))), 'images' => array('resource' => 'image', 'fields' => array('id' => array())), 'combinations' => array('resource' => 'combination', 'fields' => array('id' => array('required' => true))), 'product_option_values' => array('resource' => 'product_option_value', 'fields' => array('id' => array('required' => true))), 'product_features' => array('resource' => 'product_feature', 'fields' => array('id' => array('required' => true), 'id_feature_value' => array('required' => true, 'xlink_resource' => 'product_feature_values'))), 'tags' => array('resource' => 'tag', 'fields' => array('id' => array('required' => true))), 'stock_availables' => array('resource' => 'stock_available', 'fields' => array('id' => array('required' => true), 'id_product_attribute' => array('required' => true)), 'setter' => false), 'accessories' => array('resource' => 'product', 'api' => 'products', 'fields' => array('id' => array('required' => true, 'xlink_resource' => 'product'))), 'product_bundle' => array('resource' => 'product', 'api' => 'products', 'fields' => array('id' => array('required' => true), 'quantity' => array()))))
```





* Visibility: **protected**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 346](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L346).


### <a name="property-$weight"></a>$weight

```php
public string $weight
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L131).


### <a name="property-$wholesale_price"></a>$wholesale_price

```php
public float $wholesale_price
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L92).


### <a name="property-$width"></a>$width

```php
public string $width
```





* Visibility: **public**
* This property is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L122).


### <a name="property-$cache_objects"></a>$cache_objects

```php
protected boolean $cache_objects = true
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L164).


### <a name="property-$db"></a>$db

```php
protected \Db $db = false
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L156).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L150).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected array $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L88).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected array $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L70).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected array $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L106).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected array $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L94).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected array $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L112).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected array $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L100).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected array $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L118).


### <a name="property-$force_id"></a>$force_id

```php
public boolean $force_id = false
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L159).


### <a name="property-$get_shop_from_context"></a>$get_shop_from_context

```php
protected boolean $get_shop_from_context = true
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L67).


### <a name="property-$id"></a>$id

```php
public integer $id
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L55).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L58).


### <a name="property-$id_shop"></a>$id_shop

```php
protected integer $id_shop = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L61).


### <a name="property-$id_shop_list"></a>$id_shop_list

```php
public array $id_shop_list = null
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L64).


### <a name="property-$identifier"></a>$identifier

```php
protected string $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L82).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L130).


### <a name="property-$image_format"></a>$image_format

```php
protected String $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L133).


### <a name="property-$loaded_classes"></a>$loaded_classes

```php
protected array $loaded_classes = array()
```

Holds compiled definitions of each ObjectModel class.

Values are assigned during object initialization.

* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L147).


### <a name="property-$table"></a>$table

```php
protected string $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L76).


### <a name="property-$tables"></a>$tables

```php
protected array $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L124).


### <a name="property-$update_fields"></a>$update_fields

```php
protected array $update_fields = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L153).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ProductCore::__construct($id_product, $full, $id_lang, $id_shop, \Context $context)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 475](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L475)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4585](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4585)


#### Arguments
* $field **mixed**
* $value **mixed**



### <a name="method-_createLabel"></a>_createLabel

```php
mixed ProductCore::_createLabel($languages, $type)
```





* Visibility: **protected**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4661](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4661)


#### Arguments
* $languages **mixed**
* $type **mixed**



### <a name="method-_deleteOldLabels"></a>_deleteOldLabels

```php
mixed ProductCore::_deleteOldLabels()
```





* Visibility: **protected**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4597](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4597)




### <a name="method-_getAttributeImageAssociations"></a>_getAttributeImageAssociations

```php
array ProductCore::_getAttributeImageAssociations(integer $id_product_attribute)
```

Get product attribute image associations



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3920](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3920)


#### Arguments
* $id_product_attribute **integer**



### <a name="method-_getCustomizationFieldsNLabels"></a>_getCustomizationFieldsNLabels

```php
mixed ProductCore::_getCustomizationFieldsNLabels($product_id, $id_shop)
```





* Visibility: **protected**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4076](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4076)


#### Arguments
* $product_id **mixed**
* $id_shop **mixed**



### <a name="method-_getProductIdByDate"></a>_getProductIdByDate

```php
mixed ProductCore::_getProductIdByDate($beginning, $ending, \Context $context, $with_combination)
```





* Visibility: **protected**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2362](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L2362)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 528](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L528)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addAttribute"></a>addAttribute

```php
mixed ProductCore::addAttribute(float $price, float $weight, $unit_impact, float $ecotax, integer $id_images, string $reference, string $ean13, boolean $default, string $location, $upc, integer $minimal_quantity, array $id_shop_list, $available_date)
```

Add a product attribute



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1654](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1654)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1909](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1909)


#### Arguments
* $id_product_attribute **integer** - Product attribute id
* $attributes **array** - Attributes to forge combinaison



### <a name="method-addAttributeCombinationMultiple"></a>addAttributeCombinationMultiple

```php
boolean ProductCore::addAttributeCombinationMultiple($id_attributes, $combinations)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1930](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1930)


#### Arguments
* $id_attributes **mixed**
* $combinations **mixed**



### <a name="method-addCombinationEntity"></a>addCombinationEntity

```php
mixed ProductCore::addCombinationEntity($wholesale_price, $price, $weight, $unit_impact, $ecotax, integer $quantity, $id_images, $reference, $id_supplier, $ean13, $default, $location, $upc, $minimal_quantity, array $id_shop_list, $available_date)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1403](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1403)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4528](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4528)


#### Arguments
* $products **mixed**
* $customized_datas **mixed**



### <a name="method-addFeatureProductImport"></a>addFeatureProductImport

```php
mixed ProductCore::addFeatureProductImport($id_product, $id_feature, $id_feature_value)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3645](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3645)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3624](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3624)


#### Arguments
* $id_value **mixed**
* $lang **mixed**
* $cust **mixed**



### <a name="method-addFeaturesToDB"></a>addFeaturesToDB

```php
mixed ProductCore::addFeaturesToDB($id_feature, $id_value, $cust)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3630](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3630)


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
* Source: [classes/ObjectModel.php line 1390](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1390)


#### Arguments
* $fields **array**



### <a name="method-addItem"></a>addItem

```php
boolean PackCore::addItem(integer $id_product, integer $id_item, integer $qty, integer $id_attribute_item)
```

Add an item to the pack



* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 307](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Pack.php#L307)


#### Arguments
* $id_product **integer**
* $id_item **integer**
* $qty **integer**
* $id_attribute_item **integer**



### <a name="method-addProductAttribute"></a>addProductAttribute

```php
mixed ProductCore::addProductAttribute($price, $weight, $unit_impact, $ecotax, $quantity, $id_images, $reference, $id_supplier, $ean13, $default, $location, $upc, $minimal_quantity)
```

addProductAttribute is deprecated

The quantity params now set StockAvailable for the current shop with the specified quantity
The supplier_reference params now set the supplier reference of the default supplier of the product if possible

* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1341](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1341)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1427](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1427)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4941](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4941)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1532](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1532)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 988](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L988)


#### Arguments
* $categories **mixed** - id_category or array of id_category



### <a name="method-addWs"></a>addWs

```php
mixed ProductCore::addWs($autodate, $null_values)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5756](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5756)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-allUsesAdvancedStockManagement"></a>allUsesAdvancedStockManagement

```php
boolean PackCore::allUsesAdvancedStockManagement(integer $id_product)
```

For a given pack, tells if all products using the advanced stock management



* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 384](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Pack.php#L384)


#### Arguments
* $id_product **integer** - id_pack



### <a name="method-associateTo"></a>associateTo

```php
boolean|void ObjectModelCore::associateTo(integer|array $id_shops)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1464](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1464)


#### Arguments
* $id_shops **integer|array**



### <a name="method-cacheFieldsRequiredDatabase"></a>cacheFieldsRequiredDatabase

```php
mixed ObjectModelCore::cacheFieldsRequiredDatabase(boolean $all)
```

Caches data about required objects fields in memory



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1368](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1368)


#### Arguments
* $all **boolean** - If true, caches required fields of all object classes.



### <a name="method-cacheFrontFeatures"></a>cacheFrontFeatures

```php
mixed ProductCore::cacheFrontFeatures($product_ids, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3708](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3708)


#### Arguments
* $product_ids **mixed**
* $id_lang **mixed**



### <a name="method-cacheProductsFeatures"></a>cacheProductsFeatures

```php
mixed ProductCore::cacheProductsFeatures($product_ids)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3680](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3680)


#### Arguments
* $product_ids **mixed**



### <a name="method-changeAccessories"></a>changeAccessories

```php
mixed ProductCore::changeAccessories(array $accessories_id)
```

Link accessories with product



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3611](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3611)


#### Arguments
* $accessories_id **array** - Accessories ids



### <a name="method-checkAccess"></a>checkAccess

```php
mixed ProductCore::checkAccess($id_customer)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4890](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4890)


#### Arguments
* $id_customer **mixed**



### <a name="method-checkAccessStatic"></a>checkAccessStatic

```php
mixed ProductCore::checkAccessStatic($id_product, $id_customer)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4895](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4895)


#### Arguments
* $id_product **mixed**
* $id_customer **mixed**



### <a name="method-checkDefaultAttributes"></a>checkDefaultAttributes

```php
mixed ProductCore::checkDefaultAttributes()
```

Check if there is no default attribute and create it if not



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3392](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3392)




### <a name="method-checkQty"></a>checkQty

```php
boolean ProductCore::checkQty(integer $qty)
```

Check product availability



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3370](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3370)


#### Arguments
* $qty **integer** - Quantity desired



### <a name="method-cleanPositions"></a>cleanPositions

```php
mixed ProductCore::cleanPositions($id_category, $position)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 672](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L672)


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
* Source: [classes/ObjectModel.php line 1414](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1414)


#### Arguments
* $all **boolean** - If true, clears cache for all objects



### <a name="method-convertAndFormatPrice"></a>convertAndFormatPrice

```php
mixed ProductCore::convertAndFormatPrice($price, $currency, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3128)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3223](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3223)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3235](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3235)


#### Arguments
* $params **array**
* $smarty **object** - DEPRECATED



### <a name="method-createLabels"></a>createLabels

```php
mixed ProductCore::createLabels($uploadable_files, $text_fields)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4693](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4693)


#### Arguments
* $uploadable_files **mixed**
* $text_fields **mixed**



### <a name="method-defineProductImage"></a>defineProductImage

```php
mixed ProductCore::defineProductImage($row, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4224](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4224)


#### Arguments
* $row **mixed**
* $id_lang **mixed**



### <a name="method-delete"></a>delete

```php
mixed ProductCore::delete()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 890](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L890)




### <a name="method-deleteAccessories"></a>deleteAccessories

```php
mixed ProductCore::deleteAccessories()
```

Delete product accessories



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3513](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3513)




### <a name="method-deleteAttachments"></a>deleteAttachments

```php
array ProductCore::deleteAttachments($update_attachment_cache)
```

Delete product attachments



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1809](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1809)


#### Arguments
* $update_attachment_cache **mixed**



### <a name="method-deleteAttributeCombinaison"></a>deleteAttributeCombinaison

```php
mixed ProductCore::deleteAttributeCombinaison(integer $id_product_attribute)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5952](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5952)


#### Arguments
* $id_product_attribute **integer**



### <a name="method-deleteAttributeCombination"></a>deleteAttributeCombination

```php
array ProductCore::deleteAttributeCombination(integer $id_product_attribute)
```

Delete a product attributes combination



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1955](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1955)


#### Arguments
* $id_product_attribute **integer** - Product attribute id



### <a name="method-deleteAttributesImpacts"></a>deleteAttributesImpacts

```php
boolean ProductCore::deleteAttributesImpacts()
```

Delete product attributes impacts



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1770](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1770)




### <a name="method-deleteCartProducts"></a>deleteCartProducts

```php
array ProductCore::deleteCartProducts()
```

Delete product from cart



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1144](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1144)




### <a name="method-deleteCategories"></a>deleteCategories

```php
array ProductCore::deleteCategories(boolean $clean_positions)
```

Delete all association to category where product is indexed



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1109](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1109)


#### Arguments
* $clean_positions **boolean** - clean category positions after deletion



### <a name="method-deleteCategory"></a>deleteCategory

```php
boolean ProductCore::deleteCategory(mixed $id_category, mixed $clean_positions)
```

deleteCategory delete this product from the category $id_category



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1084](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1084)


#### Arguments
* $id_category **mixed**
* $clean_positions **mixed**



### <a name="method-deleteCustomization"></a>deleteCustomization

```php
array ProductCore::deleteCustomization()
```

Delete product customizations



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1828](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1828)




### <a name="method-deleteDefaultAttributes"></a>deleteDefaultAttributes

```php
mixed ProductCore::deleteDefaultAttributes()
```

Del all default attributes for product



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1462](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1462)




### <a name="method-deleteDownload"></a>deleteDownload

```php
boolean ProductCore::deleteDownload()
```

Remove all downloadable files for product and its attributes



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5924](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5924)




### <a name="method-deleteFeatures"></a>deleteFeatures

```php
mixed ProductCore::deleteFeatures()
```

Delete features



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1980](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1980)




### <a name="method-deleteFromAccessories"></a>deleteFromAccessories

```php
mixed ProductCore::deleteFromAccessories()
```

Delete product from other products accessories



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3523](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3523)




### <a name="method-deleteFromCartRules"></a>deleteFromCartRules

```php
mixed ProductCore::deleteFromCartRules()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 971](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L971)




### <a name="method-deleteFromSupplier"></a>deleteFromSupplier

```php
mixed ProductCore::deleteFromSupplier()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 977](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L977)




### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage(boolean $force_delete)
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1643](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1643)


#### Arguments
* $force_delete **boolean**



### <a name="method-deleteImages"></a>deleteImages

```php
boolean ProductCore::deleteImages()
```

Delete product images from database



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1154](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1154)




### <a name="method-deleteItems"></a>deleteItems

```php
mixed PackCore::deleteItems($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 290](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Pack.php#L290)


#### Arguments
* $id_product **mixed**



### <a name="method-deletePack"></a>deletePack

```php
array ProductCore::deletePack()
```

Delete product pack details



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1849](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1849)




### <a name="method-deleteProductAttributes"></a>deleteProductAttributes

```php
array ProductCore::deleteProductAttributes()
```

Delete product attributes



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1750](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1750)




### <a name="method-deleteProductFeatures"></a>deleteProductFeatures

```php
array ProductCore::deleteProductFeatures()
```

Delete product features



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1783](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1783)




### <a name="method-deleteProductSale"></a>deleteProductSale

```php
array ProductCore::deleteProductSale()
```

Delete product sales



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1863](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1863)




### <a name="method-deleteSceneProducts"></a>deleteSceneProducts

```php
array ProductCore::deleteSceneProducts()
```

Delete product in its scenes



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1876](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1876)




### <a name="method-deleteSearchIndexes"></a>deleteSearchIndexes

```php
array ProductCore::deleteSearchIndexes()
```

Delete product indexed words



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1889](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1889)




### <a name="method-deleteSelection"></a>deleteSelection

```php
mixed ProductCore::deleteSelection($products)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 954](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L954)


#### Arguments
* $products **mixed**



### <a name="method-deleteTags"></a>deleteTags

```php
array ProductCore::deleteTags()
```

Delete products tags entries



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1134](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1134)




### <a name="method-deleteWsTags"></a>deleteWsTags

```php
array ProductCore::deleteWsTags()
```

Delete products tags entries without delete tags for webservice usage



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5440](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5440)




### <a name="method-disableCache"></a>disableCache

```php
mixed ObjectModelCore::disableCache()
```

Disables object caching



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1969](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1969)




### <a name="method-displayFieldName"></a>displayFieldName

```php
string ObjectModelCore::displayFieldName(string $field, string $class, boolean $htmlentities, \Context|null $context)
```

Returns field name translation



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1083](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1083)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3240](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3240)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3252](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3252)


#### Arguments
* $params **array**
* $smarty **Smarty** - DEPRECATED



### <a name="method-duplicate"></a>duplicate

```php
mixed PackCore::duplicate($id_product_old, $id_product_new)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 320](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Pack.php#L320)


#### Arguments
* $id_product_old **mixed**
* $id_product_new **mixed**



### <a name="method-duplicateAccessories"></a>duplicateAccessories

```php
mixed ProductCore::duplicateAccessories($id_product_old, $id_product_new)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3933](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3933)


#### Arguments
* $id_product_old **mixed**
* $id_product_new **mixed**



### <a name="method-duplicateAttachments"></a>duplicateAttachments

```php
mixed ProductCore::duplicateAttachments($id_product_old, $id_product_new)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3999](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3999)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3806](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3806)


#### Arguments
* $id_product_old **integer** - Old product id
* $id_product_new **integer** - New product id



### <a name="method-duplicateCustomizationFields"></a>duplicateCustomizationFields

```php
mixed ProductCore::duplicateCustomizationFields($old_product_id, $product_id)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4130](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4130)


#### Arguments
* $old_product_id **mixed**
* $product_id **mixed**



### <a name="method-duplicateDownload"></a>duplicateDownload

```php
mixed ProductCore::duplicateDownload($id_product_old, $id_product_new)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3969](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3969)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4031](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4031)


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
* Source: [classes/ObjectModel.php line 549](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L549)




### <a name="method-duplicateShops"></a>duplicateShops

```php
boolean|void ObjectModelCore::duplicateShops($id)
```

Copies shop association data from object with specified ID.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1523](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1523)


#### Arguments
* $id **mixed**



### <a name="method-duplicateSpecificPrices"></a>duplicateSpecificPrices

```php
mixed ProductCore::duplicateSpecificPrices($old_product_id, $product_id)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4119](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4119)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4177](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4177)


#### Arguments
* $id_product_old **integer**
* $id_product_new **integer**



### <a name="method-duplicateTags"></a>duplicateTags

```php
mixed ProductCore::duplicateTags($id_product_old, $id_product_new)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3950](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3950)


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
* Source: [classes/ObjectModel.php line 1961](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1961)




### <a name="method-existsInDatabase"></a>existsInDatabase

```php
boolean ObjectModelCore::existsInDatabase(integer $id_entity, string $table)
```

Checks if an object exists in database.



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1686](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1686)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-existsRefInDatabase"></a>existsRefInDatabase

```php
boolean ProductCore::existsRefInDatabase($reference)
```

Checks if reference exists



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5470](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5470)


#### Arguments
* $reference **mixed**



### <a name="method-flushPriceCache"></a>flushPriceCache

```php
mixed ProductCore::flushPriceCache()
```

This method allows to flush price cache



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5824](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5824)




### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $type, integer $id_lang)
```

Formats values of each fields.



* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 327](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L327)


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
* Source: [classes/ObjectModel.php line 381](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L381)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1361](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1361)


#### Arguments
* $combinations **mixed**
* $attributes **mixed**



### <a name="method-getAccessories"></a>getAccessories

```php
array ProductCore::getAccessories(integer $id_lang, $active)
```

Get product accessories



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3556](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3556)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3535](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3535)


#### Arguments
* $id_lang **integer** - Language id
* $id_product **integer** - Product id



### <a name="method-getAccessoryById"></a>getAccessoryById

```php
mixed ProductCore::getAccessoryById($accessory_id)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3601](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3601)


#### Arguments
* $accessory_id **mixed**



### <a name="method-getAllCustomizedDatas"></a>getAllCustomizedDatas

```php
mixed ProductCore::getAllCustomizedDatas($id_cart, $id_lang, $only_in_cart, $id_shop)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4474](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4474)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5695](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5695)


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
* Source: [classes/ObjectModel.php line 1499](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1499)




### <a name="method-getAttachments"></a>getAttachments

```php
mixed ProductCore::getAttachments($id_lang)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4465](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4465)


#### Arguments
* $id_lang **mixed**



### <a name="method-getAttachmentsStatic"></a>getAttachmentsStatic

```php
mixed ProductCore::getAttachmentsStatic($id_lang, $id_product)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4455](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4455)


#### Arguments
* $id_lang **mixed**
* $id_product **mixed**



### <a name="method-getAttributeCombinaisons"></a>getAttributeCombinaisons

```php
mixed ProductCore::getAttributeCombinaisons(integer $id_lang)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5941](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5941)


#### Arguments
* $id_lang **integer**



### <a name="method-getAttributeCombinations"></a>getAttributeCombinations

```php
array ProductCore::getAttributeCombinations(integer $id_lang)
```

Get all available product attributes combinations



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2073](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L2073)


#### Arguments
* $id_lang **integer** - Language id



### <a name="method-getAttributeCombinationsById"></a>getAttributeCombinationsById

```php
array ProductCore::getAttributeCombinationsById(integer $id_product_attribute, integer $id_lang)
```

Get product attribute combination by id_product_attribute



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L2118)


#### Arguments
* $id_product_attribute **integer**
* $id_lang **integer** - Language id



### <a name="method-getAttributesColorList"></a>getAttributesColorList

```php
mixed ProductCore::getAttributesColorList(array $products, $have_stock)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3436](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3436)


#### Arguments
* $products **array**
* $have_stock **mixed**



### <a name="method-getAttributesGroups"></a>getAttributesGroups

```php
array ProductCore::getAttributesGroups(integer $id_lang)
```

Get all available attribute groups



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3481](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3481)


#### Arguments
* $id_lang **integer** - Language id



### <a name="method-getAttributesImpacts"></a>getAttributesImpacts

```php
mixed ProductCore::getAttributesImpacts($id_product)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3897](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3897)


#### Arguments
* $id_product **mixed**



### <a name="method-getAttributesInformationsByProduct"></a>getAttributesInformationsByProduct

```php
mixed ProductCore::getAttributesInformationsByProduct(integer $id_product)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5596](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5596)


#### Arguments
* $id_product **integer**



### <a name="method-getAttributesParams"></a>getAttributesParams

```php
array ProductCore::getAttributesParams(integer $id_product, $id_product_attribute)
```

Get label by lang and value by lang too



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5503](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5503)


#### Arguments
* $id_product **integer**
* $id_product_attribute **mixed**



### <a name="method-getAttributesResume"></a>getAttributesResume

```php
array ProductCore::getAttributesResume(integer $id_lang, $attribute_value_separator, $attribute_separator)
```

Get all available product attributes resume



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2014](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L2014)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 812](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L812)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - Optional



### <a name="method-getCarriers"></a>getCarriers

```php
mixed ProductCore::getCarriers()
```

Gets carriers assigned to the product



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2665](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L2665)




### <a name="method-getCategories"></a>getCategories

```php
array ProductCore::getCategories()
```

getCategories return an array of categories which this product belongs to



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2657](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L2657)




### <a name="method-getColorsListCacheId"></a>getColorsListCacheId

```php
mixed ProductCore::getColorsListCacheId($id_product, $full)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 6120](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L6120)


#### Arguments
* $id_product **mixed**
* $full **mixed**



### <a name="method-getCombinationImageById"></a>getCombinationImageById

```php
mixed ProductCore::getCombinationImageById($id_product_attribute, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2201](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L2201)


#### Arguments
* $id_product_attribute **mixed**
* $id_lang **mixed**



### <a name="method-getCombinationImages"></a>getCombinationImages

```php
mixed ProductCore::getCombinationImages($id_lang)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2158](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L2158)


#### Arguments
* $id_lang **mixed**



### <a name="method-getCover"></a>getCover

```php
array ProductCore::getCover($id_product, \Context $context)
```

Get product cover image



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2731](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L2731)


#### Arguments
* $id_product **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getCoverWs"></a>getCoverWs

```php
integer ProductCore::getCoverWs()
```

Webservice getter : get virtual field id_default_image in category



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5353](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5353)




### <a name="method-getCustomizationFieldIds"></a>getCustomizationFieldIds

```php
mixed ProductCore::getCustomizationFieldIds()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4795](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4795)




### <a name="method-getCustomizationFields"></a>getCustomizationFields

```php
mixed ProductCore::getCustomizationFields($id_lang, $id_shop)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4763](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4763)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 727](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L727)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5896](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5896)




### <a name="method-getDefaultIdProductAttribute"></a>getDefaultIdProductAttribute

```php
mixed ProductCore::getDefaultIdProductAttribute()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3196](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3196)




### <a name="method-getDefinition"></a>getDefinition

```php
array ObjectModelCore::getDefinition(string $class, string|null $field)
```

Returns object definition



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1809](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1809)


#### Arguments
* $class **string** - Name of object
* $field **string|null** - Name of field if we want the definition of one field only



### <a name="method-getFeatures"></a>getFeatures

```php
array ProductCore::getFeatures()
```

Select all features for the object



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3659](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3659)




### <a name="method-getFeaturesStatic"></a>getFeaturesStatic

```php
mixed ProductCore::getFeaturesStatic($id_product)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3664](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3664)


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
* Source: [classes/ObjectModel.php line 1927](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1927)


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
* Source: [classes/ObjectModel.php line 244](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L244)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 288](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L288)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
array|null ObjectModelCore::getFieldsRequiredDatabase(boolean $all)
```

Returns an array of required fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1355](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1355)


#### Arguments
* $all **boolean** - If true, returns required fields of all object classes.



### <a name="method-getFieldsShop"></a>getFieldsShop

```php
array ProductCore::getFieldsShop()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 517](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L517)




### <a name="method-getFrontFeatures"></a>getFrontFeatures

```php
mixed ProductCore::getFrontFeatures($id_lang)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4450](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4450)


#### Arguments
* $id_lang **mixed**



### <a name="method-getFrontFeaturesStatic"></a>getFrontFeaturesStatic

```php
mixed ProductCore::getFrontFeaturesStatic($id_lang, $id_product)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4430](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4430)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 6012](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L6012)


#### Arguments
* $ean13 **string**



### <a name="method-getIdProductAttributeMostExpensive"></a>getIdProductAttributeMostExpensive

```php
mixed ProductCore::getIdProductAttributeMostExpensive()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3182](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3182)




### <a name="method-getIdTaxRulesGroup"></a>getIdTaxRulesGroup

```php
mixed ProductCore::getIdTaxRulesGroup()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5009](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5009)




### <a name="method-getIdTaxRulesGroupByIdProduct"></a>getIdTaxRulesGroupByIdProduct

```php
mixed ProductCore::getIdTaxRulesGroupByIdProduct($id_product, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5014](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5014)


#### Arguments
* $id_product **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getIdTaxRulesGroupMostUsed"></a>getIdTaxRulesGroupMostUsed

```php
mixed ProductCore::getIdTaxRulesGroupMostUsed()
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5989](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5989)




### <a name="method-getImages"></a>getImages

```php
array ProductCore::getImages(integer $id_lang, \Context $context)
```

Get product images and legends



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2714](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L2714)


#### Arguments
* $id_lang **integer** - Language id for multilingual legends
* $context **[Context](class.ContextCore.md)**



### <a name="method-getItemTable"></a>getItemTable

```php
mixed PackCore::getItemTable($id_product, $id_lang, $full)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Pack.php#L171)


#### Arguments
* $id_product **mixed**
* $id_lang **mixed**
* $full **mixed**



### <a name="method-getItems"></a>getItems

```php
mixed PackCore::getItems($id_product, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Pack.php#L113)


#### Arguments
* $id_product **mixed**
* $id_lang **mixed**



### <a name="method-getLink"></a>getLink

```php
mixed ProductCore::getLink(\Context $context)
```

Get the link of the product page of this product



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4198](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4198)


#### Arguments
* $context **[Context](class.ContextCore.md)**



### <a name="method-getNewProducts"></a>getNewProducts

```php
array ProductCore::getNewProducts(integer $id_lang, $page_number, $nb_products, $count, $order_by, $order_way, \Context $context)
```

Get new products



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2248](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L2248)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4885](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4885)




### <a name="method-getPacksContainingItem"></a>getPacksContainingItem

```php
\array[Product] PackCore::getPacksContainingItem(integer $id_item, integer $id_attribute_item, integer $id_lang)
```

Returns Packs that conatins the given product in the right declinaison.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 409](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Pack.php#L409)


#### Arguments
* $id_item **integer** - Product item id that could be contained in a|many pack(s)
* $id_attribute_item **integer** - The declinaison of the product
* $id_lang **integer**



### <a name="method-getPacksTable"></a>getPacksTable

```php
mixed PackCore::getPacksTable($id_product, $id_lang, $full, $limit)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 242](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Pack.php#L242)


#### Arguments
* $id_product **mixed**
* $id_lang **mixed**
* $full **mixed**
* $limit **mixed**



### <a name="method-getParentCategories"></a>getParentCategories

```php
array ProductCore::getParentCategories(integer $id_lang)
```

Get list of parent categories



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5837](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5837)


#### Arguments
* $id_lang **integer**



### <a name="method-getPrice"></a>getPrice

```php
float ProductCore::getPrice(boolean $tax, integer $id_product_attribute, integer $decimals, integer $divisor, $only_reduc, $usereduc, $quantity)
```

Get product price
Same as static function getPriceStatic, no need to specify product id



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3169](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3169)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2778](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L2778)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3211](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3211)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2482](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L2482)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1175](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1175)


#### Arguments
* $id_product_attribute **mixed**



### <a name="method-getProductAttributesIds"></a>getProductAttributesIds

```php
array ProductCore::getProductAttributesIds(integer $id_product, $shop_only)
```

Get all product attributes ids



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5487](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5487)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2607](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L2607)


#### Arguments
* $id_product **mixed**



### <a name="method-getProductCategoriesFull"></a>getProductCategoriesFull

```php
mixed ProductCore::getProductCategoriesFull($id_product, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2629](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L2629)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5718](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5718)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4233](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4233)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1190](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1190)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4409](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4409)


#### Arguments
* $id_lang **mixed**
* $query_result **mixed**



### <a name="method-getPublicPrice"></a>getPublicPrice

```php
mixed ProductCore::getPublicPrice($tax, $id_product_attribute, $decimals, $divisor, $only_reduc, $usereduc, $quantity)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3175](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3175)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3264](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3264)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2390](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L2390)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5785](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5785)


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
* Source: [classes/ObjectModel.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L166)




### <a name="method-getRequiredCustomizableFields"></a>getRequiredCustomizableFields

```php
mixed ProductCore::getRequiredCustomizableFields()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4806](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4806)




### <a name="method-getRequiredCustomizableFieldsStatic"></a>getRequiredCustomizableFieldsStatic

```php
mixed ProductCore::getRequiredCustomizableFieldsStatic($id)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4814](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4814)


#### Arguments
* $id **mixed**



### <a name="method-getShopsByProduct"></a>getShopsByProduct

```php
mixed ProductCore::getShopsByProduct($id_product)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5911](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5911)


#### Arguments
* $id_product **mixed**



### <a name="method-getSimpleProducts"></a>getSimpleProducts

```php
mixed ProductCore::getSimpleProducts($id_lang, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1243](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1243)


#### Arguments
* $id_lang **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getStockMvts"></a>getStockMvts

```php
mixed ProductCore::getStockMvts($id_lang)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4964](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4964)


#### Arguments
* $id_lang **mixed**



### <a name="method-getTags"></a>getTags

```php
mixed ProductCore::getTags($id_lang)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4206](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4206)


#### Arguments
* $id_lang **mixed**



### <a name="method-getTaxCalculationMethod"></a>getTaxCalculationMethod

```php
mixed ProductCore::getTaxCalculationMethod($id_customer)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 603](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L603)


#### Arguments
* $id_customer **mixed**



### <a name="method-getTaxesInformations"></a>getTaxesInformations

```php
mixed ProductCore::getTaxesInformations($row, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4387](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4387)


#### Arguments
* $row **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getTaxesRate"></a>getTaxesRate

```php
float ProductCore::getTaxesRate(\Address|null $address)
```

Returns tax rate.



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5037](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5037)


#### Arguments
* $address **[Address](class.AddressCore.md)|null**



### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
array ObjectModelCore::getTranslationsFields(array $fields_array)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 831](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L831)


#### Arguments
* $fields_array **array**



### <a name="method-getType"></a>getType

```php
integer ProductCore::getType()
```

Get the product type (simple, virtual, pack)



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5964](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5964)




### <a name="method-getUrlRewriteInformations"></a>getUrlRewriteInformations

```php
mixed ProductCore::getUrlRewriteInformations($id_product)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4995](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4995)


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
* Source: [classes/ObjectModel.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L178)


#### Arguments
* $class **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
array|null ObjectModelCore::getWebserviceObjectList(string $sql_join, string $sql_filter, string $sql_sort, string $sql_limit)
```

Returns webservice object list.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1279](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1279)


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
* Source: [classes/ObjectModel.php line 1176](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1176)


#### Arguments
* $ws_params_attribute_name **string|null**



### <a name="method-getWsAccessories"></a>getWsAccessories

```php
array ProductCore::getWsAccessories()
```

Webservice getter : get product accessories ids of current product for association



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5164](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5164)




### <a name="method-getWsCategories"></a>getWsCategories

```php
array ProductCore::getWsCategories()
```

Webservice getter : get category ids of current product for association



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5116)




### <a name="method-getWsCombinations"></a>getWsCombinations

```php
array ProductCore::getWsCombinations()
```

Webservice getter : get combination ids of current product for association



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5197](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5197)




### <a name="method-getWsDefaultCombination"></a>getWsDefaultCombination

```php
integer ProductCore::getWsDefaultCombination()
```

Webservice getter : get virtual field default combination



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5094](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5094)




### <a name="method-getWsImages"></a>getWsImages

```php
array ProductCore::getWsImages()
```

Webservice getter : get image ids of current product for association



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5381](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5381)




### <a name="method-getWsManufacturerName"></a>getWsManufacturerName

```php
mixed ProductCore::getWsManufacturerName()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5446](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5446)




### <a name="method-getWsPositionInCategory"></a>getWsPositionInCategory

```php
integer ProductCore::getWsPositionInCategory()
```

Webservice getter : get virtual field position in category



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5297](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5297)




### <a name="method-getWsProductBundle"></a>getWsProductBundle

```php
mixed ProductCore::getWsProductBundle()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 6056](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L6056)




### <a name="method-getWsProductFeatures"></a>getWsProductFeatures

```php
array ProductCore::getWsProductFeatures()
```

Webservice getter : get product features association



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5054](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5054)




### <a name="method-getWsProductOptionValues"></a>getWsProductOptionValues

```php
array ProductCore::getWsProductOptionValues()
```

Webservice getter : get product option ids of current product for association



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5282](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5282)




### <a name="method-getWsStockAvailables"></a>getWsStockAvailables

```php
mixed ProductCore::getWsStockAvailables()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5391](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5391)




### <a name="method-getWsTags"></a>getWsTags

```php
mixed ProductCore::getWsTags()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5398](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5398)




### <a name="method-getWsType"></a>getWsType

```php
mixed ProductCore::getWsType()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 6030](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L6030)




### <a name="method-hasAllRequiredCustomizableFields"></a>hasAllRequiredCustomizableFields

```php
mixed ProductCore::hasAllRequiredCustomizableFields(\Context $context)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4827](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4827)


#### Arguments
* $context **[Context](class.ContextCore.md)**



### <a name="method-hasAttributes"></a>hasAttributes

```php
integer ProductCore::hasAttributes()
```

Check if product has attributes combinations



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2227](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L2227)




### <a name="method-hasAttributesInOtherShops"></a>hasAttributesInOtherShops

```php
mixed ProductCore::hasAttributesInOtherShops()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5979](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5979)




### <a name="method-hasMultishopEntries"></a>hasMultishopEntries

```php
boolean ObjectModelCore::hasMultishopEntries()
```

Checks if there is more than one entry in associated shop table for current object.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1550](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1550)




### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer|null $id_lang)
```

Fill an object with given data. Data must be an array with this syntax:
array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1730](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1730)


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
* Source: [classes/ObjectModel.php line 1755](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1755)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4864](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4864)


#### Arguments
* $id_product **integer**
* $categories **array** - array of category arrays



### <a name="method-initPricesComputation"></a>initPricesComputation

```php
mixed ProductCore::initPricesComputation($id_customer)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 577](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L577)


#### Arguments
* $id_customer **mixed**



### <a name="method-isAssociatedToShop"></a>isAssociatedToShop

```php
boolean ObjectModelCore::isAssociatedToShop(integer|null $id_shop)
```

Checks if current object is associated to a shop.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1430](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1430)


#### Arguments
* $id_shop **integer|null**



### <a name="method-isAvailableWhenOutOfStock"></a>isAvailableWhenOutOfStock

```php
mixed ProductCore::isAvailableWhenOutOfStock($out_of_stock)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3344](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3344)


#### Arguments
* $out_of_stock **mixed**



### <a name="method-isColorUnavailable"></a>isColorUnavailable

```php
mixed ProductCore::isColorUnavailable($id_attribute, $id_shop)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 6101](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L6101)


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
* Source: [classes/ObjectModel.php line 1706](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1706)


#### Arguments
* $table **string|null** - Name of table linked to entity
* $has_active_column **boolean** - True if the table has an active column



### <a name="method-isDiscounted"></a>isDiscounted

```php
mixed ProductCore::isDiscounted($id_product, $quantity, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3139](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3139)


#### Arguments
* $id_product **mixed**
* $quantity **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-isFeatureActive"></a>isFeatureActive

```php
boolean PackCore::isFeatureActive()
```

This method is allow to know if a feature is used or active



* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 334](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Pack.php#L334)




### <a name="method-isInStock"></a>isInStock

```php
mixed PackCore::isInStock($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Pack.php#L153)


#### Arguments
* $id_product **mixed**



### <a name="method-isLangMultishop"></a>isLangMultishop

```php
boolean ObjectModelCore::isLangMultishop()
```

Checks if the object is both multi-language and multi-shop.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1586](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1586)




### <a name="method-isMultiShopField"></a>isMultiShopField

```php
boolean ObjectModelCore::isMultiShopField(string $field)
```

Checks if a field is a multi-shop field.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1576](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1576)


#### Arguments
* $field **string**



### <a name="method-isMultishop"></a>isMultishop

```php
boolean ObjectModelCore::isMultishop()
```

Checks if object is multi-shop object.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1564](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1564)




### <a name="method-isNew"></a>isNew

```php
mixed ProductCore::isNew()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1264](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1264)




### <a name="method-isPack"></a>isPack

```php
boolean PackCore::isPack($id_product)
```

Is product a pack?



* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Pack.php#L39)


#### Arguments
* $id_product **mixed**



### <a name="method-isPacked"></a>isPacked

```php
boolean PackCore::isPacked($id_product, $id_product_attribute)
```

Is product in a pack?
If $id_product_attribute specified, then will restrict search on the given combination,
else this method will match a product if at least one of all its combination is in a pack.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Pack.php#L65)


#### Arguments
* $id_product **mixed**
* $id_product_attribute **mixed** - Optional combination of the product



### <a name="method-loadStockData"></a>loadStockData

```php
mixed ProductCore::loadStockData()
```

Fill the variables used for stock management



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5856](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5856)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields(array $fields, array $fields_array, integer $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 854](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L854)


#### Arguments
* $fields **array**
* $fields_array **array**
* $id_language **integer**



### <a name="method-modifierWsLinkRewrite"></a>modifierWsLinkRewrite

```php
mixed ProductCore::modifierWsLinkRewrite()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 6043](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L6043)




### <a name="method-noPackPrice"></a>noPackPrice

```php
mixed PackCore::noPackPrice($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Pack.php#L90)


#### Arguments
* $id_product **mixed**



### <a name="method-noPackWholesalePrice"></a>noPackWholesalePrice

```php
mixed PackCore::noPackWholesalePrice($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Pack.php#L103)


#### Arguments
* $id_product **mixed**



### <a name="method-priceCalculation"></a>priceCalculation

```php
float ProductCore::priceCalculation(integer $id_shop, integer $id_product, integer $id_product_attribute, integer $id_country, integer $id_state, string $zipcode, integer $id_currency, integer $id_group, integer $quantity, boolean $use_tax, integer $decimals, boolean $only_reduc, boolean $use_reduc, boolean $with_ecotax, null $specific_price, boolean $use_group_reduction, integer $id_customer, boolean $use_customer_price, integer $id_cart, integer $real_quantity)
```

Price calculation / Get product price



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2929](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L2929)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1282](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1282)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3337](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3337)




### <a name="method-resetEcoTax"></a>resetEcoTax

```php
mixed ProductCore::resetEcoTax()
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5451](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5451)




### <a name="method-save"></a>save

```php
boolean ObjectModelCore::save(boolean $null_values, boolean $auto_date)
```

Saves current object to database (add or update)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 443](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L443)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3751](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3751)


#### Arguments
* $id_lang **integer** - Language id
* $query **string** - Search query
* $context **[Context](class.ContextCore.md)**



### <a name="method-setAdvancedStockManagement"></a>setAdvancedStockManagement

```php
mixed ProductCore::setAdvancedStockManagement($value)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5878](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5878)


#### Arguments
* $value **mixed**



### <a name="method-setAvailableDate"></a>setAvailableDate

```php
mixed ProductCore::setAvailableDate($available_date)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 796](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L796)


#### Arguments
* $available_date **mixed**



### <a name="method-setCarriers"></a>setCarriers

```php
mixed ProductCore::setCarriers($carrier_list)
```

Sets carriers assigned to the product



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 2679](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L2679)


#### Arguments
* $carrier_list **mixed**



### <a name="method-setCoverWs"></a>setCoverWs

```php
boolean ProductCore::setCoverWs($id_image)
```

Webservice setter : set virtual field id_default_image in category



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5364](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5364)


#### Arguments
* $id_image **mixed**



### <a name="method-setDefaultAttribute"></a>setDefaultAttribute

```php
mixed ProductCore::setDefaultAttribute($id_product_attribute)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1469](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1469)


#### Arguments
* $id_product_attribute **mixed**



### <a name="method-setDefinitionRetrocompatibility"></a>setDefinitionRetrocompatibility

```php
mixed ObjectModelCore::setDefinitionRetrocompatibility()
```

Retrocompatibility for classes without $definition static



* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1855](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1855)




### <a name="method-setFieldsToUpdate"></a>setFieldsToUpdate

```php
mixed ObjectModelCore::setFieldsToUpdate(array $fields)
```

Set a list of specific fields to update
array(field1 => true, field2 => false,
langfield1 => array(1 => true, 2 => false))



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1953](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1953)


#### Arguments
* $fields **array**



### <a name="method-setGroupReduction"></a>setGroupReduction

```php
mixed ProductCore::setGroupReduction()
```

Set Group reduction if needed



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5461](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5461)




### <a name="method-setPackStockType"></a>setPackStockType

```php
mixed ProductCore::setPackStockType($id_product, $pack_stock_type)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 6134](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L6134)


#### Arguments
* $id_product **mixed**
* $pack_stock_type **mixed**



### <a name="method-setWsAccessories"></a>setWsAccessories

```php
mixed ProductCore::setWsAccessories($accessories)
```

Webservice setter : set product accessories ids of current product for association



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5182](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5182)


#### Arguments
* $accessories **mixed** - product ids



### <a name="method-setWsCategories"></a>setWsCategories

```php
boolean ProductCore::setWsCategories(array $category_ids)
```

Webservice setter : set category ids of current product for association



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5134](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5134)


#### Arguments
* $category_ids **array** - category ids



### <a name="method-setWsCombinations"></a>setWsCombinations

```php
mixed ProductCore::setWsCombinations($combinations)
```

Webservice setter : set combination ids of current product for association



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5214](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5214)


#### Arguments
* $combinations **mixed** - combination ids



### <a name="method-setWsDefaultCombination"></a>setWsDefaultCombination

```php
boolean ProductCore::setWsDefaultCombination(integer $id_combination)
```

Webservice setter : set virtual field default combination



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5105](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5105)


#### Arguments
* $id_combination **integer** - id default combination



### <a name="method-setWsPositionInCategory"></a>setWsPositionInCategory

```php
boolean ProductCore::setWsPositionInCategory($position)
```

Webservice setter : set virtual field position in category



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5314](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5314)


#### Arguments
* $position **mixed**



### <a name="method-setWsProductBundle"></a>setWsProductBundle

```php
mixed ProductCore::setWsProductBundle($items)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 6085](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L6085)


#### Arguments
* $items **mixed**



### <a name="method-setWsProductFeatures"></a>setWsProductFeatures

```php
boolean ProductCore::setWsProductFeatures($product_features)
```

Webservice setter : set product features association



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5077](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5077)


#### Arguments
* $product_features **mixed** - Product Feature ids



### <a name="method-setWsTags"></a>setWsTags

```php
mixed ProductCore::setWsTags($tag_ids)
```

Webservice setter : set tag ids of current product for association



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5411](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5411)


#### Arguments
* $tag_ids **mixed** - tag ids



### <a name="method-setWsType"></a>setWsType

```php
mixed ProductCore::setWsType($type_str)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 6061](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L6061)


#### Arguments
* $type_str **mixed**



### <a name="method-sqlStock"></a>sqlStock

```php
string ProductCore::sqlStock($product_alias, $product_attribute, $inner_join, \Shop $shop)
```

Create JOIN query with 'stock_available' table



* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3285](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3285)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 874](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L874)




### <a name="method-update"></a>update

```php
mixed ProductCore::update($null_values)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 554](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L554)


#### Arguments
* $null_values **mixed**



### <a name="method-updateAttribute"></a>updateAttribute

```php
array ProductCore::updateAttribute(integer $id_product_attribute, float $wholesale_price, float $price, float $weight, float $unit, float $ecotax, $id_images, string $reference, string $ean13, integer $default, $location, string $upc, string $minimal_quantity, $available_date, $update_all_fields, array $id_shop_list)
```

Update a product attribute



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1575](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1575)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1790](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1790)


#### Arguments
* $id_product **mixed**



### <a name="method-updateCategories"></a>updateCategories

```php
array ProductCore::updateCategories($categories, boolean $keeping_current_pos)
```

Update categories to index product into



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1045](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1045)


#### Arguments
* $categories **mixed**
* $keeping_current_pos **boolean** - (deprecated, no more used)



### <a name="method-updateDefaultAttribute"></a>updateDefaultAttribute

```php
mixed ProductCore::updateDefaultAttribute($id_product)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1482](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1482)


#### Arguments
* $id_product **mixed**



### <a name="method-updateIsVirtual"></a>updateIsVirtual

```php
mixed ProductCore::updateIsVirtual($id_product, $is_virtual)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 849](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L849)


#### Arguments
* $id_product **mixed**
* $is_virtual **mixed**



### <a name="method-updateLabels"></a>updateLabels

```php
mixed ProductCore::updateLabels()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 4715](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L4715)




### <a name="method-updateMultishopTable"></a>updateMultishopTable

```php
boolean ObjectModelCore::updateMultishopTable(string $classname, array $data, string $where, string $specific_where)
```

Updates a table and splits the common datas and the shop datas.



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1602](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1602)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 618](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L618)


#### Arguments
* $way **boolean** - Up (1)  or Down (0)
* $position **integer** - return boolean Update result



### <a name="method-updateProductAttribute"></a>updateProductAttribute

```php
mixed ProductCore::updateProductAttribute($id_product_attribute, $wholesale_price, $price, $weight, $unit, $ecotax, $id_images, $reference, $id_supplier, $ean13, $default, $location, $upc, $minimal_quantity, $available_date)
```

Update a product attribute



* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1509](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1509)


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
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 3319](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L3319)




### <a name="method-updateQuantityProductWithAttributeQuantity"></a>updateQuantityProductWithAttributeQuantity

```php
mixed ProductCore::updateQuantityProductWithAttributeQuantity()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 1731](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L1731)




### <a name="method-updateWs"></a>updateWs

```php
mixed ProductCore::updateWs($null_values)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5765](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5765)


#### Arguments
* $null_values **mixed**



### <a name="method-useAdvancedStockManagement"></a>useAdvancedStockManagement

```php
mixed ProductCore::useAdvancedStockManagement()
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 5869](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L5869)




### <a name="method-usesAdvancedStockManagement"></a>usesAdvancedStockManagement

```php
boolean PackCore::usesAdvancedStockManagement(integer $id_product)
```

For a given pack, tells if it has at least one product using the advanced stock management



* Visibility: **public**
* This method is **static**.
* Source: [classes/Pack.php line 361](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Pack.php#L361)


#### Arguments
* $id_product **integer** - id_pack



### <a name="method-validateControler"></a>validateControler

```php
array ObjectModelCore::validateControler(boolean $htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1105](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1105)


#### Arguments
* $htmlentities **boolean**



### <a name="method-validateController"></a>validateController

```php
array ObjectModelCore::validateController(boolean $htmlentities)
```

Validates submitted values and returns an array of errors, if any.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1118)


#### Arguments
* $htmlentities **boolean** - If true, uses htmlentities() for field name translations in errors.



### <a name="method-validateField"></a>validateField

```php
mixed ProductCore::validateField($field, $value, $id_lang, $skip, $human_errors)
```





* Visibility: **public**
* This method is defined by [ProductCore](class.ProductCore.md).
* Source: [classes/Product.php line 859](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/Product.php#L859)


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
* Source: [classes/ObjectModel.php line 895](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L895)


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
* Source: [classes/ObjectModel.php line 927](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L927)


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
* Source: [classes/ObjectModel.php line 1322](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/ObjectModel.php#L1322)


#### Arguments
* $htmlentities **boolean**


