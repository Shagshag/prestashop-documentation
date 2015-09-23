Class ProductCore
=====================





* Class name: ProductCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Product.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L37)


Contents
--------

### Constants

* [CUSTOMIZE_FILE](#constant-CUSTOMIZE_FILE)
* [CUSTOMIZE_TEXTFIELD](#constant-CUSTOMIZE_TEXTFIELD)

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
* [$cacheStock](#property-$cacheStock)
* [$cache_default_attribute](#property-$cache_default_attribute)
* [$cache_has_attachments](#property-$cache_has_attachments)
* [$cache_is_pack](#property-$cache_is_pack)
* [$condition](#property-$condition)
* [$customizable](#property-$customizable)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$depth](#property-$depth)
* [$description](#property-$description)
* [$description_short](#property-$description_short)
* [$ean13](#property-$ean13)
* [$ecotax](#property-$ecotax)
* [$height](#property-$height)
* [$id_category_default](#property-$id_category_default)
* [$id_manufacturer](#property-$id_manufacturer)
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
* [$price](#property-$price)
* [$producPropertiesCache](#property-$producPropertiesCache)
* [$quantity](#property-$quantity)
* [$quantity_discount](#property-$quantity_discount)
* [$reference](#property-$reference)
* [$show_price](#property-$show_price)
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
* [$webserviceParameters](#property-$webserviceParameters)
* [$weight](#property-$weight)
* [$wholesale_price](#property-$wholesale_price)
* [$width](#property-$width)
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
* [addToCategories](#method-addToCategories)
* [addWs](#method-addWs)
* [associateTo](#method-associateTo)
* [cacheFrontFeatures](#method-cacheFrontFeatures)
* [cacheProductsFeatures](#method-cacheProductsFeatures)
* [changeAccessories](#method-changeAccessories)
* [checkAccess](#method-checkAccess)
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
* [deleteAttributesImpacts](#method-deleteAttributesImpacts)
* [deleteCartProducts](#method-deleteCartProducts)
* [deleteCategories](#method-deleteCategories)
* [deleteCategory](#method-deleteCategory)
* [deleteCustomization](#method-deleteCustomization)
* [deleteDefaultAttributes](#method-deleteDefaultAttributes)
* [deleteFeatures](#method-deleteFeatures)
* [deleteFromAccessories](#method-deleteFromAccessories)
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
* [displayFieldName](#method-displayFieldName)
* [displayWtPrice](#method-displayWtPrice)
* [displayWtPriceWithCurrency](#method-displayWtPriceWithCurrency)
* [duplicateAccessories](#method-duplicateAccessories)
* [duplicateAttributes](#method-duplicateAttributes)
* [duplicateCustomizationFields](#method-duplicateCustomizationFields)
* [duplicateDownload](#method-duplicateDownload)
* [duplicateFeatures](#method-duplicateFeatures)
* [duplicateShops](#method-duplicateShops)
* [duplicateSpecificPrices](#method-duplicateSpecificPrices)
* [duplicateTags](#method-duplicateTags)
* [existsInDatabase](#method-existsInDatabase)
* [existsRefInDatabase](#method-existsRefInDatabase)
* [flushPriceCache](#method-flushPriceCache)
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [getAccessories](#method-getAccessories)
* [getAccessoriesLight](#method-getAccessoriesLight)
* [getAccessoryById](#method-getAccessoryById)
* [getAllCustomizedDatas](#method-getAllCustomizedDatas)
* [getAnchor](#method-getAnchor)
* [getAttachments](#method-getAttachments)
* [getAttachmentsStatic](#method-getAttachmentsStatic)
* [getAttributeCombinaisons](#method-getAttributeCombinaisons)
* [getAttributeCombinaisonsById](#method-getAttributeCombinaisonsById)
* [getAttributesGroups](#method-getAttributesGroups)
* [getAttributesInformationsByProduct](#method-getAttributesInformationsByProduct)
* [getAttributesParams](#method-getAttributesParams)
* [getAttributesResume](#method-getAttributesResume)
* [getCarriers](#method-getCarriers)
* [getCategories](#method-getCategories)
* [getCombinationImages](#method-getCombinationImages)
* [getCover](#method-getCover)
* [getCoverWs](#method-getCoverWs)
* [getCustomizationFieldIds](#method-getCustomizationFieldIds)
* [getCustomizationFields](#method-getCustomizationFields)
* [getDefaultAttribute](#method-getDefaultAttribute)
* [getDefinition](#method-getDefinition)
* [getEntity](#method-getEntity)
* [getFeatures](#method-getFeatures)
* [getFeaturesStatic](#method-getFeaturesStatic)
* [getFields](#method-getFields)
* [getFieldsLang](#method-getFieldsLang)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFrontFeatures](#method-getFrontFeatures)
* [getFrontFeaturesStatic](#method-getFrontFeaturesStatic)
* [getIdProductAttributeMostExpensive](#method-getIdProductAttributeMostExpensive)
* [getIdTaxRulesGroupByIdProduct](#method-getIdTaxRulesGroupByIdProduct)
* [getImages](#method-getImages)
* [getLink](#method-getLink)
* [getNewProducts](#method-getNewProducts)
* [getNoPackPrice](#method-getNoPackPrice)
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
* [getRequiredCustomizableFields](#method-getRequiredCustomizableFields)
* [getSimpleProducts](#method-getSimpleProducts)
* [getStockMvts](#method-getStockMvts)
* [getTags](#method-getTags)
* [getTaxCalculationMethod](#method-getTaxCalculationMethod)
* [getTaxesRate](#method-getTaxesRate)
* [getTranslationsFields](#method-getTranslationsFields)
* [getUrlRewriteInformations](#method-getUrlRewriteInformations)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [getWsCategories](#method-getWsCategories)
* [getWsCombinations](#method-getWsCombinations)
* [getWsDefaultCombination](#method-getWsDefaultCombination)
* [getWsImages](#method-getWsImages)
* [getWsManufacturerName](#method-getWsManufacturerName)
* [getWsPositionInCategory](#method-getWsPositionInCategory)
* [getWsProductFeatures](#method-getWsProductFeatures)
* [getWsProductOptionValues](#method-getWsProductOptionValues)
* [getWsTags](#method-getWsTags)
* [hasAllRequiredCustomizableFields](#method-hasAllRequiredCustomizableFields)
* [hasAttributes](#method-hasAttributes)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [idIsOnCategoryId](#method-idIsOnCategoryId)
* [initPricesComputation](#method-initPricesComputation)
* [isAssociatedToGroupShop](#method-isAssociatedToGroupShop)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isAvailableWhenOutOfStock](#method-isAvailableWhenOutOfStock)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isDiscounted](#method-isDiscounted)
* [isLangMultishop](#method-isLangMultishop)
* [isNew](#method-isNew)
* [makeTranslationFields](#method-makeTranslationFields)
* [priceCalculation](#method-priceCalculation)
* [productAttributeExists](#method-productAttributeExists)
* [reinjectQuantities](#method-reinjectQuantities)
* [resetEcoTax](#method-resetEcoTax)
* [save](#method-save)
* [searchByName](#method-searchByName)
* [setCarriers](#method-setCarriers)
* [setCoverWs](#method-setCoverWs)
* [setDefaultAttribute](#method-setDefaultAttribute)
* [setDefinitionRetrocompatibility](#method-setDefinitionRetrocompatibility)
* [setGroupReduction](#method-setGroupReduction)
* [setWsCategories](#method-setWsCategories)
* [setWsCombinations](#method-setWsCombinations)
* [setWsDefaultCombination](#method-setWsDefaultCombination)
* [setWsProductFeatures](#method-setWsProductFeatures)
* [sqlStock](#method-sqlStock)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [updateAttribute](#method-updateAttribute)
* [updateCategories](#method-updateCategories)
* [updateDefaultAttribute](#method-updateDefaultAttribute)
* [updateIsVirtual](#method-updateIsVirtual)
* [updateLabels](#method-updateLabels)
* [updatePosition](#method-updatePosition)
* [updateProductAttribute](#method-updateProductAttribute)
* [updateQuantity](#method-updateQuantity)
* [updateQuantityProductWithAttributeQuantity](#method-updateQuantityProductWithAttributeQuantity)
* [updateWs](#method-updateWs)
* [usesAdvancedStockManagement](#method-usesAdvancedStockManagement)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateField](#method-validateField)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)


Constants
----------


### <a name="constant-CUSTOMIZE_FILE"></a>CUSTOMIZE_FILE

```php
const CUSTOMIZE_FILE = 0
```





* Source: [classes/Product.php line 366](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L366).


### <a name="constant-CUSTOMIZE_TEXTFIELD"></a>CUSTOMIZE_TEXTFIELD

```php
const CUSTOMIZE_TEXTFIELD = 1
```





* Source: [classes/Product.php line 367](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L367).


Properties
----------


### <a name="property-$_cacheFeatures"></a>$_cacheFeatures

```php
protected mixed $_cacheFeatures = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Product.php line 210](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L210).


### <a name="property-$_cart_quantity"></a>$_cart_quantity

```php
protected mixed $_cart_quantity = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Product.php line 208](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L208).


### <a name="property-$_frontFeaturesCache"></a>$_frontFeaturesCache

```php
protected mixed $_frontFeaturesCache = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Product.php line 211](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L211).


### <a name="property-$_incat"></a>$_incat

```php
protected mixed $_incat = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Product.php line 207](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L207).


### <a name="property-$_prices"></a>$_prices

```php
protected mixed $_prices = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Product.php line 205](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L205).


### <a name="property-$_pricesLevel2"></a>$_pricesLevel2

```php
protected mixed $_pricesLevel2 = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Product.php line 206](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L206).


### <a name="property-$_taxCalculationMethod"></a>$_taxCalculationMethod

```php
public mixed $_taxCalculationMethod = PS_TAX_EXC
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Product.php line 204](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L204).


### <a name="property-$_tax_rules_group"></a>$_tax_rules_group

```php
protected mixed $_tax_rules_group = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Product.php line 209](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L209).


### <a name="property-$active"></a>$active

```php
public boolean $active = 1
```





* Visibility: **public**
* Source: [classes/Product.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L166).


### <a name="property-$additional_shipping_cost"></a>$additional_shipping_cost

```php
public float $additional_shipping_cost
```





* Visibility: **public**
* Source: [classes/Product.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L88).


### <a name="property-$advanced_stock_management"></a>$advanced_stock_management

```php
public boolean $advanced_stock_management
```





* Visibility: **public**
* Source: [classes/Product.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L195).


### <a name="property-$available_date"></a>$available_date

```php
public string $available_date
```





* Visibility: **public**
* Source: [classes/Product.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L172).


### <a name="property-$available_for_order"></a>$available_for_order

```php
public boolean $available_for_order = 1
```





* Visibility: **public**
* Source: [classes/Product.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L169).


### <a name="property-$available_later"></a>$available_later

```php
public string $available_later
```





* Visibility: **public**
* Source: [classes/Product.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L82).


### <a name="property-$available_now"></a>$available_now

```php
public string $available_now
```





* Visibility: **public**
* Source: [classes/Product.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L79).


### <a name="property-$cacheStock"></a>$cacheStock

```php
protected array $cacheStock = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Product.php line 215](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L215).


### <a name="property-$cache_default_attribute"></a>$cache_default_attribute

```php
public mixed $cache_default_attribute
```





* Visibility: **public**
* Source: [classes/Product.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L202).


### <a name="property-$cache_has_attachments"></a>$cache_has_attachments

```php
public mixed $cache_has_attachments
```





* Visibility: **public**
* Source: [classes/Product.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L200).


### <a name="property-$cache_is_pack"></a>$cache_is_pack

```php
public mixed $cache_is_pack
```





* Visibility: **public**
* Source: [classes/Product.php line 199](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L199).


### <a name="property-$condition"></a>$condition

```php
public \enum $condition
```





* Visibility: **public**
* Source: [classes/Product.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L175).


### <a name="property-$customizable"></a>$customizable

```php
public boolean $customizable
```





* Visibility: **public**
* Source: [classes/Product.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L154).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/Product.php line 183](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L183).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* Source: [classes/Product.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L186).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'product', 'primary' => 'id_product', 'multilang' => true, 'multishop' => true, 'fields' => array('id_tax_rules_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_manufacturer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_supplier' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_category_default' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'minimal_quantity' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'price' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'additional_shipping_cost' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'wholesale_price' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'on_sale' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'online_only' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'ecotax' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'unity' => array('type' => self::TYPE_STRING, 'validate' => 'isString'), 'unit_price_ratio' => array('type' => self::TYPE_FLOAT), 'reference' => array('type' => self::TYPE_STRING, 'validate' => 'isReference', 'size' => 32), 'supplier_reference' => array('type' => self::TYPE_STRING, 'validate' => 'isReference', 'size' => 32), 'location' => array('type' => self::TYPE_STRING, 'validate' => 'isReference', 'size' => 64), 'width' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat'), 'height' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat'), 'depth' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat'), 'weight' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat'), 'quantity_discount' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'customizable' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'uploadable_files' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'text_fields' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'available_for_order' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'available_date' => array('type' => self::TYPE_DATE, 'validate' => 'isDateFormat'), 'condition' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName'), 'show_price' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'ean13' => array('type' => self::TYPE_STRING, 'validate' => 'isEan13', 'size' => 13), 'upc' => array('type' => self::TYPE_STRING, 'validate' => 'isUpc', 'size' => 12), 'indexed' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'cache_is_pack' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'cache_default_attribute' => array('type' => self::TYPE_INT), 'is_virtual' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'cache_has_attachments' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDateFormat'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDateFormat'), 'advanced_stock_management' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'meta_description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_keywords' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_title' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 128), 'link_rewrite' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isLinkRewrite', 'required' => true, 'size' => 128), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isCatalogName', 'required' => true, 'size' => 128), 'description' => array('type' => self::TYPE_HTML, 'lang' => true, 'validate' => 'isString'), 'description_short' => array('type' => self::TYPE_HTML, 'lang' => true, 'validate' => 'isString'), 'available_now' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'available_later' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'IsGenericName', 'size' => 255)), 'associations' => array('manufacturer' => array('type' => self::HAS_ONE), 'supplier' => array('type' => self::HAS_ONE), 'default_category' => array('type' => self::HAS_ONE, 'field' => 'id_category_default', 'object' => 'Category'), 'tax_rules_group' => array('type' => self::HAS_ONE), 'categories' => array('type' => self::HAS_MANY, 'field' => 'id_category', 'object' => 'Category', 'association' => 'category_product')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Product.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L217).


### <a name="property-$depth"></a>$depth

```php
public string $depth
```





* Visibility: **public**
* Source: [classes/Product.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L127).


### <a name="property-$description"></a>$description

```php
public string $description
```





* Visibility: **public**
* Source: [classes/Product.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L67).


### <a name="property-$description_short"></a>$description_short

```php
public string $description_short
```





* Visibility: **public**
* Source: [classes/Product.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L70).


### <a name="property-$ean13"></a>$ean13

```php
public string $ean13
```





* Visibility: **public**
* Source: [classes/Product.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L133).


### <a name="property-$ecotax"></a>$ecotax

```php
public float $ecotax
```





* Visibility: **public**
* Source: [classes/Product.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L109).


### <a name="property-$height"></a>$height

```php
public string $height
```





* Visibility: **public**
* Source: [classes/Product.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L124).


### <a name="property-$id_category_default"></a>$id_category_default

```php
public integer $id_category_default
```





* Visibility: **public**
* Source: [classes/Product.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L55).


### <a name="property-$id_manufacturer"></a>$id_manufacturer

```php
public integer $id_manufacturer
```





* Visibility: **public**
* Source: [classes/Product.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L49).


### <a name="property-$id_supplier"></a>$id_supplier

```php
public integer $id_supplier
```





* Visibility: **public**
* Source: [classes/Product.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L52).


### <a name="property-$id_tax_rules_group"></a>$id_tax_rules_group

```php
public string $id_tax_rules_group
```





* Visibility: **public**
* Source: [classes/Product.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L46).


### <a name="property-$indexed"></a>$indexed

```php
public mixed $indexed
```





* Visibility: **public**
* Source: [classes/Product.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L180).


### <a name="property-$isFullyLoaded"></a>$isFullyLoaded

```php
public mixed $isFullyLoaded = false
```





* Visibility: **public**
* Source: [classes/Product.php line 197](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L197).


### <a name="property-$is_virtual"></a>$is_virtual

```php
public mixed $is_virtual
```





* Visibility: **public**
* Source: [classes/Product.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L201).


### <a name="property-$link_rewrite"></a>$link_rewrite

```php
public string $link_rewrite
```





* Visibility: **public**
* Source: [classes/Product.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L139).


### <a name="property-$location"></a>$location

```php
public string $location
```





* Visibility: **public**
* Source: [classes/Product.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L118).


### <a name="property-$manufacturer_name"></a>$manufacturer_name

```php
public string $manufacturer_name
```





* Visibility: **public**
* Source: [classes/Product.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L58).


### <a name="property-$meta_description"></a>$meta_description

```php
public string $meta_description
```





* Visibility: **public**
* Source: [classes/Product.php line 142](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L142).


### <a name="property-$meta_keywords"></a>$meta_keywords

```php
public string $meta_keywords
```





* Visibility: **public**
* Source: [classes/Product.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L145).


### <a name="property-$meta_title"></a>$meta_title

```php
public string $meta_title
```





* Visibility: **public**
* Source: [classes/Product.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L148).


### <a name="property-$minimal_quantity"></a>$minimal_quantity

```php
public integer $minimal_quantity = 1
```





* Visibility: **public**
* Source: [classes/Product.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L76).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/Product.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L64).


### <a name="property-$new"></a>$new

```php
public boolean $new = null
```





* Visibility: **public**
* Source: [classes/Product.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L157).


### <a name="property-$on_sale"></a>$on_sale

```php
public boolean $on_sale = false
```





* Visibility: **public**
* Source: [classes/Product.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L94).


### <a name="property-$online_only"></a>$online_only

```php
public boolean $online_only = false
```





* Visibility: **public**
* Source: [classes/Product.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L97).


### <a name="property-$price"></a>$price

```php
public float $price
```





* Visibility: **public**
* Source: [classes/Product.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L85).


### <a name="property-$producPropertiesCache"></a>$producPropertiesCache

```php
protected mixed $producPropertiesCache = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Product.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L212).


### <a name="property-$quantity"></a>$quantity

```php
public integer $quantity
```





* Visibility: **public**
* Source: [classes/Product.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L73).


### <a name="property-$quantity_discount"></a>$quantity_discount

```php
public boolean $quantity_discount
```





* Visibility: **public**
* Source: [classes/Product.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L151).


### <a name="property-$reference"></a>$reference

```php
public string $reference
```





* Visibility: **public**
* Source: [classes/Product.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L112).


### <a name="property-$show_price"></a>$show_price

```php
public boolean $show_price = 1
```





* Visibility: **public**
* Source: [classes/Product.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L178).


### <a name="property-$supplier_name"></a>$supplier_name

```php
public string $supplier_name
```





* Visibility: **public**
* Source: [classes/Product.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L61).


### <a name="property-$supplier_reference"></a>$supplier_reference

```php
public string $supplier_reference
```





* Visibility: **public**
* Source: [classes/Product.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L115).


### <a name="property-$tags"></a>$tags

```php
public mixed $tags
```





* Visibility: **public**
* Source: [classes/Product.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L189).


### <a name="property-$tax_name"></a>$tax_name

```php
public string $tax_name
```





* Visibility: **public**
* Source: [classes/Product.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L40).


### <a name="property-$tax_rate"></a>$tax_rate

```php
public string $tax_rate
```





* Visibility: **public**
* Source: [classes/Product.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L43).


### <a name="property-$text_fields"></a>$text_fields

```php
public \interger $text_fields
```





* Visibility: **public**
* Source: [classes/Product.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L163).


### <a name="property-$unit_price"></a>$unit_price

```php
public float $unit_price
```





* Visibility: **public**
* Source: [classes/Product.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L103).


### <a name="property-$unit_price_ratio"></a>$unit_price_ratio

```php
public float $unit_price_ratio
```





* Visibility: **public**
* Source: [classes/Product.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L106).


### <a name="property-$unity"></a>$unity

```php
public string $unity = null
```





* Visibility: **public**
* Source: [classes/Product.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L100).


### <a name="property-$upc"></a>$upc

```php
public string $upc
```





* Visibility: **public**
* Source: [classes/Product.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L136).


### <a name="property-$uploadable_files"></a>$uploadable_files

```php
public integer $uploadable_files
```





* Visibility: **public**
* Source: [classes/Product.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L160).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectMethods' => array('add' => 'addWs', 'update' => 'updateWs'), 'objectNodeNames' => 'products', 'fields' => array('id_manufacturer' => array('xlink_resource' => 'manufacturers'), 'id_supplier' => array('xlink_resource' => 'suppliers'), 'id_category_default' => array('xlink_resource' => 'categories'), 'new' => array(), 'cache_default_attribute' => array(), 'id_default_image' => array('getter' => 'getCoverWs', 'setter' => 'setCoverWs', 'xlink_resource' => array('resourceName' => 'images', 'subResourceName' => 'products')), 'id_default_combination' => array('getter' => 'getWsDefaultCombination', 'setter' => 'setWsDefaultCombination', 'xlink_resource' => array('resourceName' => 'combinations')), 'position_in_category' => array('getter' => 'getWsPositionInCategory', 'setter' => false), 'manufacturer_name' => array('getter' => 'getWsManufacturerName', 'setter' => false)), 'associations' => array('categories' => array('resource' => 'category', 'fields' => array('id' => array('required' => true))), 'images' => array('resource' => 'image', 'fields' => array('id' => array())), 'combinations' => array('resource' => 'combinations', 'fields' => array('id' => array('required' => true))), 'product_option_values' => array('resource' => 'product_options_values', 'fields' => array('id' => array('required' => true))), 'product_features' => array('resource' => 'product_feature', 'fields' => array('id' => array('required' => true), 'id_feature_value' => array('required' => true, 'xlink_resource' => 'product_feature_values'))), 'tags' => array('resource' => 'tag', 'fields' => array('id' => array('required' => true)))))
```





* Visibility: **protected**
* Source: [classes/Product.php line 284](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L284).


### <a name="property-$weight"></a>$weight

```php
public string $weight
```





* Visibility: **public**
* Source: [classes/Product.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L130).


### <a name="property-$wholesale_price"></a>$wholesale_price

```php
public float $wholesale_price
```





* Visibility: **public**
* Source: [classes/Product.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L91).


### <a name="property-$width"></a>$width

```php
public string $width
```





* Visibility: **public**
* Source: [classes/Product.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L121).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L122).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L72).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected mixed $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L57).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L87).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L77).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L92).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L82).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L97).


### <a name="property-$id"></a>$id

```php
public integer $id
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L48).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L51).


### <a name="property-$id_shop"></a>$id_shop

```php
protected mixed $id_shop = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L53).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L67).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L108).


### <a name="property-$image_format"></a>$image_format

```php
protected string $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L111).


### <a name="property-$table"></a>$table

```php
protected mixed $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L62).


### <a name="property-$tables"></a>$tables

```php
protected mixed $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L102).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ProductCore::__construct($id_product, $full, $id_lang, $id_shop, \Context $context)
```





* Visibility: **public**
* Source: [classes/Product.php line 369](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L369)


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
* Source: [classes/Product.php line 3681](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3681)


#### Arguments
* $field **mixed**
* $value **mixed**



### <a name="method-_createLabel"></a>_createLabel

```php
mixed ProductCore::_createLabel($languages, $type)
```





* Visibility: **protected**
* Source: [classes/Product.php line 3762](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3762)


#### Arguments
* $languages **mixed**
* $type **mixed**



### <a name="method-_deleteOldLabels"></a>_deleteOldLabels

```php
mixed ProductCore::_deleteOldLabels()
```





* Visibility: **protected**
* Source: [classes/Product.php line 3691](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3691)




### <a name="method-_getAttributeImageAssociations"></a>_getAttributeImageAssociations

```php
array ProductCore::_getAttributeImageAssociations(integer $id_product_attribute)
```

Get product attribute image associations



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3161](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3161)


#### Arguments
* $id_product_attribute **integer**



### <a name="method-_getCustomizationFieldsNLabels"></a>_getCustomizationFieldsNLabels

```php
mixed ProductCore::_getCustomizationFieldsNLabels($product_id)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/Product.php line 3275](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3275)


#### Arguments
* $product_id **mixed**



### <a name="method-_getProductIdByDate"></a>_getProductIdByDate

```php
mixed ProductCore::_getProductIdByDate($beginning, $ending, \Context $context)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/Product.php line 1881](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L1881)


#### Arguments
* $beginning **mixed**
* $ending **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-add"></a>add

```php
mixed ProductCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Product.php line 417](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L417)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addAttribute"></a>addAttribute

```php
mixed ProductCore::addAttribute(float $price, float $weight, $unit_impact, float $ecotax, integer $id_images, string $reference, string $ean13, boolean $default, string $location, $upc, integer $minimal_quantity)
```

Add a product attribute



* Visibility: **public**
* Source: [classes/Product.php line 1048](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L1048)


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



### <a name="method-addAttributeCombinaison"></a>addAttributeCombinaison

```php
array ProductCore::addAttributeCombinaison(integer $id_product_attribute, array $attributes)
```

Add a product attributes combinaison



* Visibility: **public**
* Source: [classes/Product.php line 1476](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L1476)


#### Arguments
* $id_product_attribute **integer** - Product attribute id
* $attributes **array** - Attributes to forge combinaison



### <a name="method-addAttributeCombinationMultiple"></a>addAttributeCombinationMultiple

```php
mixed ProductCore::addAttributeCombinationMultiple($id_attributes, $combinations)
```





* Visibility: **public**
* Source: [classes/Product.php line 1498](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L1498)


#### Arguments
* $id_attributes **mixed**
* $combinations **mixed**



### <a name="method-addCombinationEntity"></a>addCombinationEntity

```php
mixed ProductCore::addCombinationEntity($wholesale_price, $price, $weight, $unit_impact, $ecotax, integer $quantity, $id_images, $reference, string $supplier_reference, $ean13, $default, $location, $upc, $minimal_quantity)
```





* Visibility: **public**
* Source: [classes/Product.php line 1093](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L1093)


#### Arguments
* $wholesale_price **mixed**
* $price **mixed**
* $weight **mixed**
* $unit_impact **mixed**
* $ecotax **mixed**
* $quantity **integer** - DEPRECATED
* $id_images **mixed**
* $reference **mixed**
* $supplier_reference **string** - DEPRECATED
* $ean13 **mixed**
* $default **mixed**
* $location **mixed**
* $upc **mixed**
* $minimal_quantity **mixed**



### <a name="method-addCustomizationPrice"></a>addCustomizationPrice

```php
mixed ProductCore::addCustomizationPrice($products, $customized_datas)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3627](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3627)


#### Arguments
* $products **mixed**
* $customized_datas **mixed**



### <a name="method-addFeatureProductImport"></a>addFeatureProductImport

```php
mixed ProductCore::addFeatureProductImport($id_product, $id_feature, $id_feature_value)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2981](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2981)


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
* Source: [classes/Product.php line 2961](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2961)


#### Arguments
* $id_value **mixed**
* $lang **mixed**
* $cust **mixed**



### <a name="method-addFeaturesToDB"></a>addFeaturesToDB

```php
mixed ProductCore::addFeaturesToDB($id_feature, $id_value, $cust)
```





* Visibility: **public**
* Source: [classes/Product.php line 2967](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2967)


#### Arguments
* $id_feature **mixed**
* $id_value **mixed**
* $cust **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 961](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L961)


#### Arguments
* $fields **mixed**



### <a name="method-addProductAttribute"></a>addProductAttribute

```php
mixed ProductCore::addProductAttribute($price, $weight, $unit_impact, $ecotax, $quantity, $id_images, $reference, $supplier_reference, $ean13, $default, $location, $upc, $minimal_quantity)
```

addProductAttribute is deprecated

The quantity params now set StockAvailable for the current shop with the specified quantity
The supplier_reference params now set the supplier reference of the default supplier of the product if possible

* Visibility: **public**
* Source: [classes/Product.php line 992](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L992)


#### Arguments
* $price **mixed**
* $weight **mixed**
* $unit_impact **mixed**
* $ecotax **mixed**
* $quantity **mixed**
* $id_images **mixed**
* $reference **mixed**
* $supplier_reference **mixed**
* $ean13 **mixed**
* $default **mixed**
* $location **mixed**
* $upc **mixed**
* $minimal_quantity **mixed**



### <a name="method-addProductAttributeMultiple"></a>addProductAttributeMultiple

```php
mixed ProductCore::addProductAttributeMultiple($attributes, $set_default)
```





* Visibility: **public**
* Source: [classes/Product.php line 1113](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L1113)


#### Arguments
* $attributes **mixed**
* $set_default **mixed**



### <a name="method-addStockMvt"></a>addStockMvt

```php
boolean ProductCore::addStockMvt(integer $quantity, integer $id_reason, integer $id_product_attribute, integer $id_order, integer $id_employee)
```

Add a stock movement for current product

Since 1.5, this method only permit to add/remove available quantities of the current product in the current shop

* Visibility: **public**
* Source: [classes/Product.php line 3969](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3969)


#### Arguments
* $quantity **integer**
* $id_reason **integer** - 
useless

* $id_product_attribute **integer**
* $id_order **integer** - 
useless

* $id_employee **integer** - 
useless




### <a name="method-addToCategories"></a>addToCategories

```php
boolean ProductCore::addToCategories(mixed $categories)
```

addToCategories add this product to the category/ies if not exists.



* Visibility: **public**
* Source: [classes/Product.php line 673](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L673)


#### Arguments
* $categories **mixed** - id_category or array of id_category



### <a name="method-addWs"></a>addWs

```php
mixed ProductCore::addWs($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Product.php line 4635](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L4635)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops, string $type)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1009](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1009)


#### Arguments
* $id_shops **integer|array**
* $type **string**



### <a name="method-cacheFrontFeatures"></a>cacheFrontFeatures

```php
mixed ProductCore::cacheFrontFeatures($product_ids, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3037](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3037)


#### Arguments
* $product_ids **mixed**
* $id_lang **mixed**



### <a name="method-cacheProductsFeatures"></a>cacheProductsFeatures

```php
mixed ProductCore::cacheProductsFeatures($product_ids)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3013](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3013)


#### Arguments
* $product_ids **mixed**



### <a name="method-changeAccessories"></a>changeAccessories

```php
mixed ProductCore::changeAccessories(array $accessories_id)
```

Link accessories with product



* Visibility: **public**
* Source: [classes/Product.php line 2945](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2945)


#### Arguments
* $accessories_id **array** - Accessories ids



### <a name="method-checkAccess"></a>checkAccess

```php
mixed ProductCore::checkAccess($id_customer)
```





* Visibility: **public**
* Source: [classes/Product.php line 3934](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3934)


#### Arguments
* $id_customer **mixed**



### <a name="method-checkDefaultAttributes"></a>checkDefaultAttributes

```php
mixed ProductCore::checkDefaultAttributes()
```

Check if there is not a default attribute and create it not



* Visibility: **public**
* Source: [classes/Product.php line 2787](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2787)




### <a name="method-checkQty"></a>checkQty

```php
boolean ProductCore::checkQty(integer $qty)
```

Check product availability



* Visibility: **public**
* Source: [classes/Product.php line 2768](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2768)


#### Arguments
* $qty **integer** - Quantity desired



### <a name="method-cleanPositions"></a>cleanPositions

```php
mixed ProductCore::cleanPositions($id_category)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 500](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L500)


#### Arguments
* $id_category **mixed**



### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 975](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L975)


#### Arguments
* $all **mixed**



### <a name="method-convertAndFormatPrice"></a>convertAndFormatPrice

```php
mixed ProductCore::convertAndFormatPrice($price, $currency, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2490](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2490)


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
* Source: [classes/Product.php line 2568](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2568)


#### Arguments
* $params **array** - Params
* $smarty **mixed** - Smarty object



### <a name="method-convertPriceWithCurrency"></a>convertPriceWithCurrency

```php
\Ambigous ProductCore::convertPriceWithCurrency(array $params, object $smarty)
```

Convert price with currency



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2580](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2580)


#### Arguments
* $params **array**
* $smarty **object** - DEPRECATED



### <a name="method-createLabels"></a>createLabels

```php
mixed ProductCore::createLabels($uploadable_files, $text_fields)
```





* Visibility: **public**
* Source: [classes/Product.php line 3788](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3788)


#### Arguments
* $uploadable_files **mixed**
* $text_fields **mixed**



### <a name="method-defineProductImage"></a>defineProductImage

```php
mixed ProductCore::defineProductImage($row, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3383](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3383)


#### Arguments
* $row **mixed**
* $id_lang **mixed**



### <a name="method-delete"></a>delete

```php
mixed ProductCore::delete()
```





* Visibility: **public**
* Source: [classes/Product.php line 601](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L601)




### <a name="method-deleteAccessories"></a>deleteAccessories

```php
mixed ProductCore::deleteAccessories()
```

Delete product accessories



* Visibility: **public**
* Source: [classes/Product.php line 2847](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2847)




### <a name="method-deleteAttachments"></a>deleteAttachments

```php
array ProductCore::deleteAttachments()
```

Delete product attachments



* Visibility: **public**
* Source: [classes/Product.php line 1377](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L1377)




### <a name="method-deleteAttributeCombinaison"></a>deleteAttributeCombinaison

```php
array ProductCore::deleteAttributeCombinaison(integer $id_product_attribute)
```

Delete a product attributes combinaison



* Visibility: **public**
* Source: [classes/Product.php line 1520](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L1520)


#### Arguments
* $id_product_attribute **integer** - Product attribute id



### <a name="method-deleteAttributesImpacts"></a>deleteAttributesImpacts

```php
\Deletion ProductCore::deleteAttributesImpacts()
```

Delete product attributes impacts



* Visibility: **public**
* Source: [classes/Product.php line 1354](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L1354)




### <a name="method-deleteCartProducts"></a>deleteCartProducts

```php
array ProductCore::deleteCartProducts()
```

Delete product from cart



* Visibility: **public**
* Source: [classes/Product.php line 827](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L827)




### <a name="method-deleteCategories"></a>deleteCategories

```php
array ProductCore::deleteCategories(boolean $clean_positions)
```

Delete all association to category where product is indexed



* Visibility: **public**
* Source: [classes/Product.php line 780](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L780)


#### Arguments
* $clean_positions **boolean** - clean category positions after deletion



### <a name="method-deleteCategory"></a>deleteCategory

```php
boolean ProductCore::deleteCategory(mixed $id_category, mixed $clean_positions)
```

deleteCategory delete this product from the category $id_category



* Visibility: **public**
* Source: [classes/Product.php line 754](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L754)


#### Arguments
* $id_category **mixed**
* $clean_positions **mixed**



### <a name="method-deleteCustomization"></a>deleteCustomization

```php
array ProductCore::deleteCustomization()
```

Delete product customizations



* Visibility: **public**
* Source: [classes/Product.php line 1390](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L1390)




### <a name="method-deleteDefaultAttributes"></a>deleteDefaultAttributes

```php
mixed ProductCore::deleteDefaultAttributes()
```

Del all default attributes for product



* Visibility: **public**
* Source: [classes/Product.php line 1165](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L1165)




### <a name="method-deleteFeatures"></a>deleteFeatures

```php
mixed ProductCore::deleteFeatures()
```

Delete features



* Visibility: **public**
* Source: [classes/Product.php line 1553](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L1553)




### <a name="method-deleteFromAccessories"></a>deleteFromAccessories

```php
mixed ProductCore::deleteFromAccessories()
```

Delete product from other products accessories



* Visibility: **public**
* Source: [classes/Product.php line 2857](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2857)




### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage()
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1079](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1079)




### <a name="method-deleteImages"></a>deleteImages

```php
boolean ProductCore::deleteImages()
```

Delete product images from database



* Visibility: **public**
* Source: [classes/Product.php line 840](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L840)




### <a name="method-deletePack"></a>deletePack

```php
array ProductCore::deletePack()
```

Delete product pack details



* Visibility: **public**
* Source: [classes/Product.php line 1411](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L1411)




### <a name="method-deleteProductAttributes"></a>deleteProductAttributes

```php
array ProductCore::deleteProductAttributes()
```

Delete product attributes



* Visibility: **public**
* Source: [classes/Product.php line 1323](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L1323)




### <a name="method-deleteProductFeatures"></a>deleteProductFeatures

```php
array ProductCore::deleteProductFeatures()
```

Delete product features



* Visibility: **public**
* Source: [classes/Product.php line 1367](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L1367)




### <a name="method-deleteProductSale"></a>deleteProductSale

```php
array ProductCore::deleteProductSale()
```

Delete product sales



* Visibility: **public**
* Source: [classes/Product.php line 1425](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L1425)




### <a name="method-deleteSceneProducts"></a>deleteSceneProducts

```php
array ProductCore::deleteSceneProducts()
```

Delete product in its scenes



* Visibility: **public**
* Source: [classes/Product.php line 1438](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L1438)




### <a name="method-deleteSearchIndexes"></a>deleteSearchIndexes

```php
array ProductCore::deleteSearchIndexes()
```

Delete product indexed words



* Visibility: **public**
* Source: [classes/Product.php line 1451](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L1451)




### <a name="method-deleteSelection"></a>deleteSelection

```php
mixed ProductCore::deleteSelection($products)
```





* Visibility: **public**
* Source: [classes/Product.php line 656](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L656)


#### Arguments
* $products **mixed**



### <a name="method-deleteTags"></a>deleteTags

```php
array ProductCore::deleteTags()
```

Delete products tags entries



* Visibility: **public**
* Source: [classes/Product.php line 806](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L806)




### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $className, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 740](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L740)


#### Arguments
* $field **mixed**
* $className **mixed**
* $htmlentities **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-displayWtPrice"></a>displayWtPrice

```php
mixed ProductCore::displayWtPrice($params, $smarty)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2587](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2587)


#### Arguments
* $params **mixed**
* $smarty **mixed**



### <a name="method-displayWtPriceWithCurrency"></a>displayWtPriceWithCurrency

```php
\Ambigous ProductCore::displayWtPriceWithCurrency(array $params, $smarty)
```

Display WT price with currency



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2599](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2599)


#### Arguments
* $params **array**
* $smarty **mixed**



### <a name="method-duplicateAccessories"></a>duplicateAccessories

```php
mixed ProductCore::duplicateAccessories($id_product_old, $id_product_new)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3173](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3173)


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
* Source: [classes/Product.php line 3120](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3120)


#### Arguments
* $id_product_old **integer** - Old product id
* $id_product_new **integer** - New product id



### <a name="method-duplicateCustomizationFields"></a>duplicateCustomizationFields

```php
mixed ProductCore::duplicateCustomizationFields($old_product_id, $product_id)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3319](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3319)


#### Arguments
* $old_product_id **mixed**
* $product_id **mixed**



### <a name="method-duplicateDownload"></a>duplicateDownload

```php
mixed ProductCore::duplicateDownload($id_product_old, $id_product_new)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3203](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3203)


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
* Source: [classes/Product.php line 3232](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3232)


#### Arguments
* $id_product_old **integer** - Old product id
* $id_product_new **mixed**



### <a name="method-duplicateShops"></a>duplicateShops

```php
mixed ObjectModelCore::duplicateShops($id)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1049](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1049)


#### Arguments
* $id **mixed**



### <a name="method-duplicateSpecificPrices"></a>duplicateSpecificPrices

```php
mixed ProductCore::duplicateSpecificPrices($old_product_id, $product_id)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3308](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3308)


#### Arguments
* $old_product_id **mixed**
* $product_id **mixed**



### <a name="method-duplicateTags"></a>duplicateTags

```php
mixed ProductCore::duplicateTags($id_product_old, $id_product_new)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3191](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3191)


#### Arguments
* $id_product_old **mixed**
* $id_product_new **mixed**



### <a name="method-existsInDatabase"></a>existsInDatabase

```php
boolean ObjectModelCore::existsInDatabase(integer $id_entity, string $table)
```

Specify if an ObjectModel is already in database



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1113](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1113)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-existsRefInDatabase"></a>existsRefInDatabase

```php
boolean ProductCore::existsRefInDatabase($reference)
```

Checks if reference exists



* Visibility: **public**
* Source: [classes/Product.php line 4342](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L4342)


#### Arguments
* $reference **mixed**



### <a name="method-flushPriceCache"></a>flushPriceCache

```php
mixed ProductCore::flushPriceCache()
```

This method allows to flush price cache



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 4700](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L4700)




### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $id_lang)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L272)


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
* Source: [classes/ObjectModel.php line 319](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L319)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **mixed**



### <a name="method-getAccessories"></a>getAccessories

```php
array ProductCore::getAccessories(integer $id_lang, $active, \Context $context)
```

Get product accessories



* Visibility: **public**
* Source: [classes/Product.php line 2893](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2893)


#### Arguments
* $id_lang **integer** - Language id
* $active **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getAccessoriesLight"></a>getAccessoriesLight

```php
array ProductCore::getAccessoriesLight(integer $id_lang, integer $id_product, \Context $context)
```

Get product accessories (only names)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2869](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2869)


#### Arguments
* $id_lang **integer** - Language id
* $id_product **integer** - Product id
* $context **[Context](class.ContextCore.md)**



### <a name="method-getAccessoryById"></a>getAccessoryById

```php
mixed ProductCore::getAccessoryById($accessory_id)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2935](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2935)


#### Arguments
* $accessory_id **mixed**



### <a name="method-getAllCustomizedDatas"></a>getAllCustomizedDatas

```php
mixed ProductCore::getAllCustomizedDatas($id_cart, $id_lang, $only_in_cart)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3583](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3583)


#### Arguments
* $id_cart **mixed**
* $id_lang **mixed**
* $only_in_cart **mixed**



### <a name="method-getAnchor"></a>getAnchor

```php
string ProductCore::getAnchor(integer $id_product_attribute)
```

Get the combination url anchor of the product



* Visibility: **public**
* Source: [classes/Product.php line 4576](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L4576)


#### Arguments
* $id_product_attribute **integer**



### <a name="method-getAttachments"></a>getAttachments

```php
mixed ProductCore::getAttachments($id_lang)
```





* Visibility: **public**
* Source: [classes/Product.php line 3574](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3574)


#### Arguments
* $id_lang **mixed**



### <a name="method-getAttachmentsStatic"></a>getAttachmentsStatic

```php
mixed ProductCore::getAttachmentsStatic($id_lang, $id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3564](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3564)


#### Arguments
* $id_lang **mixed**
* $id_product **mixed**



### <a name="method-getAttributeCombinaisons"></a>getAttributeCombinaisons

```php
array ProductCore::getAttributeCombinaisons(integer $id_lang)
```

Get all available product attributes combinaisons



* Visibility: **public**
* Source: [classes/Product.php line 1626](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L1626)


#### Arguments
* $id_lang **integer** - Language id



### <a name="method-getAttributeCombinaisonsById"></a>getAttributeCombinaisonsById

```php
array ProductCore::getAttributeCombinaisonsById(integer $id_product_attribute, integer $id_lang)
```

Get product attribute combinaison by id_product_attribute



* Visibility: **public**
* Source: [classes/Product.php line 1668](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L1668)


#### Arguments
* $id_product_attribute **integer**
* $id_lang **integer** - Language id



### <a name="method-getAttributesGroups"></a>getAttributesGroups

```php
array ProductCore::getAttributesGroups(integer $id_lang)
```

Get all available attribute groups



* Visibility: **public**
* Source: [classes/Product.php line 2820](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2820)


#### Arguments
* $id_lang **integer** - Language id



### <a name="method-getAttributesInformationsByProduct"></a>getAttributesInformationsByProduct

```php
mixed ProductCore::getAttributesInformationsByProduct(integer $id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 4476](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L4476)


#### Arguments
* $id_product **integer**



### <a name="method-getAttributesParams"></a>getAttributesParams

```php
array ProductCore::getAttributesParams(integer $id_product, $id_product_attribute)
```

Get label by lang and value by lang too



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 4374](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L4374)


#### Arguments
* $id_product **integer**
* $id_product_attribute **mixed**



### <a name="method-getAttributesResume"></a>getAttributesResume

```php
array ProductCore::getAttributesResume(integer $id_lang, $attribute_value_separator, $attribute_separator)
```

Get all available product attributes resume



* Visibility: **public**
* Source: [classes/Product.php line 1585](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L1585)


#### Arguments
* $id_lang **integer** - Language id
* $attribute_value_separator **mixed**
* $attribute_separator **mixed**



### <a name="method-getCarriers"></a>getCarriers

```php
mixed ProductCore::getCarriers()
```

Gets carriers assigned to the product



* Visibility: **public**
* Source: [classes/Product.php line 2104](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2104)




### <a name="method-getCategories"></a>getCategories

```php
array ProductCore::getCategories()
```

getCategories return an array of categories which this product belongs to



* Visibility: **public**
* Source: [classes/Product.php line 2096](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2096)




### <a name="method-getCombinationImages"></a>getCombinationImages

```php
mixed ProductCore::getCombinationImages($id_lang)
```





* Visibility: **public**
* Source: [classes/Product.php line 1703](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L1703)


#### Arguments
* $id_lang **mixed**



### <a name="method-getCover"></a>getCover

```php
array ProductCore::getCover($id_product, \Context $context)
```

Get product cover image



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2165](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2165)


#### Arguments
* $id_product **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getCoverWs"></a>getCoverWs

```php
integer ProductCore::getCoverWs()
```

Webservice getter : get virtual field id_default_image in category



* Visibility: **public**
* Source: [classes/Product.php line 4263](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L4263)




### <a name="method-getCustomizationFieldIds"></a>getCustomizationFieldIds

```php
mixed ProductCore::getCustomizationFieldIds()
```





* Visibility: **public**
* Source: [classes/Product.php line 3861](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3861)




### <a name="method-getCustomizationFields"></a>getCustomizationFields

```php
mixed ProductCore::getCustomizationFields($id_lang)
```





* Visibility: **public**
* Source: [classes/Product.php line 3838](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3838)


#### Arguments
* $id_lang **mixed**



### <a name="method-getDefaultAttribute"></a>getDefaultAttribute

```php
integer ProductCore::getDefaultAttribute($id_product, $minimum_quantity)
```

Get the default attribute for a product



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 525](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L525)


#### Arguments
* $id_product **mixed**
* $minimum_quantity **mixed**



### <a name="method-getDefinition"></a>getDefinition

```php
mixed ObjectModelCore::getDefinition($class, $field)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1209](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1209)


#### Arguments
* $class **mixed**
* $field **mixed**



### <a name="method-getEntity"></a>getEntity

```php
mixed ObjectModelCore::getEntity($entity)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1269](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1269)


#### Arguments
* $entity **mixed**



### <a name="method-getFeatures"></a>getFeatures

```php
array ProductCore::getFeatures()
```

Select all features for the object



* Visibility: **public**
* Source: [classes/Product.php line 2995](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2995)




### <a name="method-getFeaturesStatic"></a>getFeaturesStatic

```php
mixed ProductCore::getFeaturesStatic($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3000](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3000)


#### Arguments
* $id_product **mixed**



### <a name="method-getFields"></a>getFields

```php
array ProductCore::getFields()
```





* Visibility: **public**
* Source: [classes/Product.php line 409](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L409)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L249)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 953](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L953)


#### Arguments
* $all **mixed**



### <a name="method-getFrontFeatures"></a>getFrontFeatures

```php
mixed ProductCore::getFrontFeatures($id_lang)
```





* Visibility: **public**
* Source: [classes/Product.php line 3559](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3559)


#### Arguments
* $id_lang **mixed**



### <a name="method-getFrontFeaturesStatic"></a>getFrontFeaturesStatic

```php
mixed ProductCore::getFrontFeaturesStatic($id_lang, $id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3540](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3540)


#### Arguments
* $id_lang **mixed**
* $id_product **mixed**



### <a name="method-getIdProductAttributeMostExpensive"></a>getIdProductAttributeMostExpensive

```php
mixed ProductCore::getIdProductAttributeMostExpensive()
```





* Visibility: **public**
* Source: [classes/Product.php line 2542](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2542)




### <a name="method-getIdTaxRulesGroupByIdProduct"></a>getIdTaxRulesGroupByIdProduct

```php
mixed ProductCore::getIdTaxRulesGroupByIdProduct($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 4029](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L4029)


#### Arguments
* $id_product **mixed**



### <a name="method-getImages"></a>getImages

```php
array ProductCore::getImages(integer $id_lang, \Context $context)
```

Get product images and legends



* Visibility: **public**
* Source: [classes/Product.php line 2146](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2146)


#### Arguments
* $id_lang **integer** - Language id for multilingual legends
* $context **[Context](class.ContextCore.md)**



### <a name="method-getLink"></a>getLink

```php
mixed ProductCore::getLink(\Context $context)
```

Get the link of the product page of this product



* Visibility: **public**
* Source: [classes/Product.php line 3361](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3361)


#### Arguments
* $context **[Context](class.ContextCore.md)**



### <a name="method-getNewProducts"></a>getNewProducts

```php
array ProductCore::getNewProducts(integer $id_lang, $page_number, $nb_products, $count, $order_by, $order_way, \Context $context)
```

Get new products



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 1765](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L1765)


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
* Source: [classes/Product.php line 3929](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3929)




### <a name="method-getPrice"></a>getPrice

```php
float ProductCore::getPrice(boolean $tax, integer $id_product_attribute, integer $decimals, integer $divisor, $only_reduc, $usereduc, $quantity)
```

Get product price
Same as static function getPriceStatic, no need to specify product id



* Visibility: **public**
* Source: [classes/Product.php line 2528](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2528)


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
float ProductCore::getPriceStatic(integer $id_product, boolean $usetax, integer $id_product_attribute, integer $decimals, integer $divisor, boolean $only_reduc, boolean $usereduc, integer $quantity, $force_associated_tax, integer $id_customer, integer $id_cart, integer $id_address, $specific_price_output, boolean $with_ecotax, $use_group_reduction, \Context $context, $use_customer_price)
```

Get product price



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2199](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2199)


#### Arguments
* $id_product **integer** - Product id
* $usetax **boolean** - With taxes or not (optional)
* $id_product_attribute **integer** - Product attribute id (optional).
If set to false, do not apply the combination price impact. NULL does apply the default combination price impact.
* $decimals **integer** - Number of decimals (optional)
* $divisor **integer** - Useful when paying many time without fees (optional)
* $only_reduc **boolean** - Returns only the reduction amount
* $usereduc **boolean** - Set if the returned amount will include reduction
* $quantity **integer** - Required for quantity discount application (default value: 1)
* $force_associated_tax **mixed**
* $id_customer **integer** - Customer ID (for customer group reduction)
* $id_cart **integer** - Cart ID. Required when the cookie is not accessible (e.g., inside a payment module, a cron task...)
* $id_address **integer** - Customer address ID. Required for price (tax included) calculation regarding the guest localization
* $specific_price_output **mixed**
* $with_ecotax **boolean** - insert ecotax in price output.
* $use_group_reduction **mixed**
* $context **[Context](class.ContextCore.md)**
* $use_customer_price **mixed**



### <a name="method-getPriceWithoutReduct"></a>getPriceWithoutReduct

```php
mixed ProductCore::getPriceWithoutReduct($notax, $id_product_attribute)
```





* Visibility: **public**
* Source: [classes/Product.php line 2556](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2556)


#### Arguments
* $notax **mixed**
* $id_product_attribute **mixed**



### <a name="method-getPricesDrop"></a>getPricesDrop

```php
array ProductCore::getPricesDrop(integer $id_lang, $page_number, $nb_products, boolean $count, $order_by, $order_way, $beginning, $ending, \Context $context)
```

Get prices drop



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 1965](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L1965)


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
* Source: [classes/Product.php line 858](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L858)


#### Arguments
* $id_product_attribute **mixed**



### <a name="method-getProductAttributesIds"></a>getProductAttributesIds

```php
array ProductCore::getProductAttributesIds(integer $id_product)
```

Get all product attributes ids



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 4359](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L4359)


#### Arguments
* $id_product **integer** - the id of the product



### <a name="method-getProductCategories"></a>getProductCategories

```php
array ProductCore::getProductCategories($id_product)
```

getProductCategories return an array of categories which this product belongs to



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2059](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2059)


#### Arguments
* $id_product **mixed**



### <a name="method-getProductCategoriesFull"></a>getProductCategoriesFull

```php
mixed ProductCore::getProductCategoriesFull($id_product, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2075](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2075)


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
* Source: [classes/Product.php line 4598](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L4598)


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
* Source: [classes/Product.php line 3392](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3392)


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
* Source: [classes/Product.php line 877](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L877)


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
* Source: [classes/Product.php line 3522](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3522)


#### Arguments
* $id_lang **mixed**
* $query_result **mixed**



### <a name="method-getPublicPrice"></a>getPublicPrice

```php
mixed ProductCore::getPublicPrice($tax, $id_product_attribute, $decimals, $divisor, $only_reduc, $usereduc, $quantity)
```





* Visibility: **public**
* Source: [classes/Product.php line 2534](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2534)


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
* Source: [classes/Product.php line 2611](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2611)


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
* Source: [classes/Product.php line 1906](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L1906)


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
* Source: [classes/Product.php line 4661](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L4661)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $id_warehouse **integer**
* $id_shop **integer**



### <a name="method-getRequiredCustomizableFields"></a>getRequiredCustomizableFields

```php
mixed ProductCore::getRequiredCustomizableFields()
```





* Visibility: **public**
* Source: [classes/Product.php line 3871](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3871)




### <a name="method-getSimpleProducts"></a>getSimpleProducts

```php
mixed ProductCore::getSimpleProducts($id_lang, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 914](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L914)


#### Arguments
* $id_lang **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getStockMvts"></a>getStockMvts

```php
mixed ProductCore::getStockMvts($id_lang)
```





* Visibility: **public**
* Source: [classes/Product.php line 3985](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3985)


#### Arguments
* $id_lang **mixed**



### <a name="method-getTags"></a>getTags

```php
mixed ProductCore::getTags($id_lang)
```





* Visibility: **public**
* Source: [classes/Product.php line 3368](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3368)


#### Arguments
* $id_lang **mixed**



### <a name="method-getTaxCalculationMethod"></a>getTaxCalculationMethod

```php
mixed ProductCore::getTaxCalculationMethod($id_customer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 447](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L447)


#### Arguments
* $id_customer **mixed**



### <a name="method-getTaxesRate"></a>getTaxesRate

```php
\the ProductCore::getTaxesRate(\Address $address)
```





* Visibility: **public**
* Source: [classes/Product.php line 4045](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L4045)


#### Arguments
* $address **[Address](class.AddressCore.md)**



### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields($fieldsArray)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 589](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L589)


#### Arguments
* $fieldsArray **mixed**



### <a name="method-getUrlRewriteInformations"></a>getUrlRewriteInformations

```php
mixed ProductCore::getUrlRewriteInformations($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 4016](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L4016)


#### Arguments
* $id_product **mixed**



### <a name="method-getValidationRules"></a>getValidationRules

```php
array ObjectModelCore::getValidationRules(string $className)
```

Returns object validation rules (fields validity)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L130)


#### Arguments
* $className **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed ObjectModelCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 929](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L929)


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
* Source: [classes/ObjectModel.php line 799](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L799)


#### Arguments
* $wsParamsAttributeName **mixed**



### <a name="method-getWsCategories"></a>getWsCategories

```php
array ProductCore::getWsCategories()
```

Webservice getter : get category ids of current product for association



* Visibility: **public**
* Source: [classes/Product.php line 4120](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L4120)




### <a name="method-getWsCombinations"></a>getWsCombinations

```php
array ProductCore::getWsCombinations()
```

Webservice getter : get combination ids of current product for association



* Visibility: **public**
* Source: [classes/Product.php line 4163](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L4163)




### <a name="method-getWsDefaultCombination"></a>getWsDefaultCombination

```php
integer ProductCore::getWsDefaultCombination()
```

Webservice getter : get virtual field default combination



* Visibility: **public**
* Source: [classes/Product.php line 4099](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L4099)




### <a name="method-getWsImages"></a>getWsImages

```php
array ProductCore::getWsImages()
```

Webservice getter : get image ids of current product for association



* Visibility: **public**
* Source: [classes/Product.php line 4291](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L4291)




### <a name="method-getWsManufacturerName"></a>getWsManufacturerName

```php
mixed ProductCore::getWsManufacturerName()
```





* Visibility: **public**
* Source: [classes/Product.php line 4309](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L4309)




### <a name="method-getWsPositionInCategory"></a>getWsPositionInCategory

```php
integer ProductCore::getWsPositionInCategory()
```

Webservice getter : get virtual field position in category



* Visibility: **public**
* Source: [classes/Product.php line 4247](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L4247)




### <a name="method-getWsProductFeatures"></a>getWsProductFeatures

```php
array ProductCore::getWsProductFeatures()
```

Webservice getter : get product features association



* Visibility: **public**
* Source: [classes/Product.php line 4061](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L4061)




### <a name="method-getWsProductOptionValues"></a>getWsProductOptionValues

```php
array ProductCore::getWsProductOptionValues()
```

Webservice getter : get product option ids of current product for association



* Visibility: **public**
* Source: [classes/Product.php line 4233](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L4233)




### <a name="method-getWsTags"></a>getWsTags

```php
mixed ProductCore::getWsTags()
```





* Visibility: **public**
* Source: [classes/Product.php line 4300](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L4300)




### <a name="method-hasAllRequiredCustomizableFields"></a>hasAllRequiredCustomizableFields

```php
mixed ProductCore::hasAllRequiredCustomizableFields(\Context $context)
```





* Visibility: **public**
* Source: [classes/Product.php line 3883](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3883)


#### Arguments
* $context **[Context](class.ContextCore.md)**



### <a name="method-hasAttributes"></a>hasAttributes

```php
integer ProductCore::hasAttributes()
```

Check if product has attributes combinaisons



* Visibility: **public**
* Source: [classes/Product.php line 1746](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L1746)




### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1148](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1148)


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
* Source: [classes/ObjectModel.php line 1167](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1167)


#### Arguments
* $class **string** - Class of objects to hydrate
* $datas **array** - List of data (multi-dimensional array)
* $id_lang **integer**



### <a name="method-idIsOnCategoryId"></a>idIsOnCategoryId

```php
boolean ProductCore::idIsOnCategoryId(integer $id_product, array $categories)
```

Checks if the product is in at least one of the submited categories



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3911](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3911)


#### Arguments
* $id_product **integer**
* $categories **array** - array of category arrays



### <a name="method-initPricesComputation"></a>initPricesComputation

```php
mixed ProductCore::initPricesComputation($id_customer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 432](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L432)


#### Arguments
* $id_customer **mixed**



### <a name="method-isAssociatedToGroupShop"></a>isAssociatedToGroupShop

```php
boolean ObjectModelCore::isAssociatedToGroupShop(integer $id_group_shop)
```

Check if current object is associated to a group shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1035](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1035)


#### Arguments
* $id_group_shop **integer**



### <a name="method-isAssociatedToShop"></a>isAssociatedToShop

```php
boolean ObjectModelCore::isAssociatedToShop(integer $id_shop)
```

Check if current object is associated to a shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 990](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L990)


#### Arguments
* $id_shop **integer**



### <a name="method-isAvailableWhenOutOfStock"></a>isAvailableWhenOutOfStock

```php
mixed ProductCore::isAvailableWhenOutOfStock($out_of_stock)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2755](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2755)


#### Arguments
* $out_of_stock **mixed**



### <a name="method-isCurrentlyUsed"></a>isCurrentlyUsed

```php
boolean ObjectModelCore::isCurrentlyUsed(string $table, boolean $has_active_column)
```

This method is allow to know if a entity is currently used



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1131](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1131)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isDiscounted"></a>isDiscounted

```php
mixed ProductCore::isDiscounted($id_product, $quantity, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2499](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2499)


#### Arguments
* $id_product **mixed**
* $quantity **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1069](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1069)




### <a name="method-isNew"></a>isNew

```php
mixed ProductCore::isNew()
```





* Visibility: **public**
* Source: [classes/Product.php line 928](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L928)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fieldsArray, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 605](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L605)


#### Arguments
* $fields **mixed**
* $fieldsArray **mixed**
* $id_language **mixed**



### <a name="method-priceCalculation"></a>priceCalculation

```php
float ProductCore::priceCalculation(integer $id_shop, integer $id_product, integer $id_product_attribute, integer $id_country, integer $id_state, $zipcode, integer $id_currency, integer $id_group, integer $quantity, boolean $use_tax, integer $decimals, boolean $only_reduc, boolean $use_reduc, boolean $with_ecotax, $specific_price, $use_group_reduction, $id_customer, $use_customer_price, $id_cart)
```

Price calculation / Get product price



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2336](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2336)


#### Arguments
* $id_shop **integer** - Shop id
* $id_product **integer** - Product id
* $id_product_attribute **integer** - Product attribute id
* $id_country **integer** - Country id
* $id_state **integer** - State id
* $zipcode **mixed**
* $id_currency **integer** - Currency id
* $id_group **integer** - Group id
* $quantity **integer** - Quantity Required for Specific prices : quantity discount application
* $use_tax **boolean** - with (1) or without (0) tax
* $decimals **integer** - Number of decimals returned
* $only_reduc **boolean** - Returns only the reduction amount
* $use_reduc **boolean** - Set if the returned amount will include reduction
* $with_ecotax **boolean** - insert ecotax in price output.
* $specific_price **mixed**
* $use_group_reduction **mixed**
* $id_customer **mixed**
* $use_customer_price **mixed**
* $id_cart **mixed**



### <a name="method-productAttributeExists"></a>productAttributeExists

```php
mixed ProductCore::productAttributeExists($attributes_list, $current_product_attribute)
```





* Visibility: **public**
* Source: [classes/Product.php line 945](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L945)


#### Arguments
* $attributes_list **mixed**
* $current_product_attribute **mixed**



### <a name="method-reinjectQuantities"></a>reinjectQuantities

```php
mixed ProductCore::reinjectQuantities($orderDetail, $quantity, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2727](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2727)


#### Arguments
* $orderDetail **mixed**
* $quantity **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-resetEcoTax"></a>resetEcoTax

```php
mixed ProductCore::resetEcoTax()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 4314](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L4314)




### <a name="method-save"></a>save

```php
boolean ObjectModelCore::save(boolean $null_values, boolean $autodate)
```

Save current object to database (add or update)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L360)


#### Arguments
* $null_values **boolean**
* $autodate **boolean**



### <a name="method-searchByName"></a>searchByName

```php
array ProductCore::searchByName(integer $id_lang, string $query, \Context $context)
```

Admin panel product search



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3071](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3071)


#### Arguments
* $id_lang **integer** - Language id
* $query **string** - Search query
* $context **[Context](class.ContextCore.md)**



### <a name="method-setCarriers"></a>setCarriers

```php
mixed ProductCore::setCarriers($carrier_list)
```

Sets carriers assigned to the product



* Visibility: **public**
* Source: [classes/Product.php line 2118](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2118)


#### Arguments
* $carrier_list **mixed**



### <a name="method-setCoverWs"></a>setCoverWs

```php
boolean ProductCore::setCoverWs($id_image)
```

Webservice setter : set virtual field id_default_image in category



* Visibility: **public**
* Source: [classes/Product.php line 4274](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L4274)


#### Arguments
* $id_image **mixed**



### <a name="method-setDefaultAttribute"></a>setDefaultAttribute

```php
mixed ProductCore::setDefaultAttribute($id_product_attribute)
```





* Visibility: **public**
* Source: [classes/Product.php line 1173](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L1173)


#### Arguments
* $id_product_attribute **mixed**



### <a name="method-setDefinitionRetrocompatibility"></a>setDefinitionRetrocompatibility

```php
mixed ObjectModelCore::setDefinitionRetrocompatibility()
```

Retrocompatibility for classes without $definition static
Remove this in 1.6 !



* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1224](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1224)




### <a name="method-setGroupReduction"></a>setGroupReduction

```php
mixed ProductCore::setGroupReduction()
```

Set Group reduction if needed



* Visibility: **public**
* Source: [classes/Product.php line 4325](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L4325)




### <a name="method-setWsCategories"></a>setWsCategories

```php
mixed ProductCore::setWsCategories($category_ids)
```

Webservice setter : set category ids of current product for association



* Visibility: **public**
* Source: [classes/Product.php line 4135](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L4135)


#### Arguments
* $category_ids **mixed** - category ids



### <a name="method-setWsCombinations"></a>setWsCombinations

```php
mixed ProductCore::setWsCombinations($combinations)
```

Webservice setter : set combination ids of current product for association



* Visibility: **public**
* Source: [classes/Product.php line 4179](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L4179)


#### Arguments
* $combinations **mixed** - combination ids



### <a name="method-setWsDefaultCombination"></a>setWsDefaultCombination

```php
mixed ProductCore::setWsDefaultCombination($id_combination)
```

Webservice setter : set virtual field default combination



* Visibility: **public**
* Source: [classes/Product.php line 4109](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L4109)


#### Arguments
* $id_combination **mixed** - id default combination



### <a name="method-setWsProductFeatures"></a>setWsProductFeatures

```php
boolean ProductCore::setWsProductFeatures($product_features)
```

Webservice setter : set product features association



* Visibility: **public**
* Source: [classes/Product.php line 4086](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L4086)


#### Arguments
* $product_features **mixed**



### <a name="method-sqlStock"></a>sqlStock

```php
string ProductCore::sqlStock($product_alias, $product_attribute, $inner_join, \Shop $shop, \DbQuery $sql)
```

Create JOIN query with 'stock_available' table



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2633](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2633)


#### Arguments
* $product_alias **mixed**
* $product_attribute **mixed**
* $inner_join **mixed**
* $shop **[Shop](class.ShopCore.md)**
* $sql **[DbQuery](class.DbQueryCore.md)**



### <a name="method-toggleStatus"></a>toggleStatus

```php
boolean ObjectModelCore::toggleStatus()
```

Toggle object status in database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 569](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L569)




### <a name="method-update"></a>update

```php
mixed ProductCore::update($null_values)
```





* Visibility: **public**
* Source: [classes/Product.php line 425](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L425)


#### Arguments
* $null_values **mixed**



### <a name="method-updateAttribute"></a>updateAttribute

```php
array ProductCore::updateAttribute(integer $id_product_attribute, float $wholesale_price, float $price, float $weight, float $unit, float $ecotax, $id_images, string $reference, string $ean13, integer $default, $location, string $upc, string $minimal_quantity, $available_date)
```

Update a product attribute



* Visibility: **public**
* Source: [classes/Product.php line 1245](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L1245)


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



### <a name="method-updateCategories"></a>updateCategories

```php
array ProductCore::updateCategories($categories, boolean $keeping_current_pos)
```

Update categories to index product into



* Visibility: **public**
* Source: [classes/Product.php line 722](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L722)


#### Arguments
* $categories **mixed**
* $keeping_current_pos **boolean** - (deprecated, no more used)



### <a name="method-updateDefaultAttribute"></a>updateDefaultAttribute

```php
mixed ProductCore::updateDefaultAttribute($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 567](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L567)


#### Arguments
* $id_product **mixed**



### <a name="method-updateIsVirtual"></a>updateIsVirtual

```php
mixed ProductCore::updateIsVirtual($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 578](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L578)


#### Arguments
* $id_product **mixed**



### <a name="method-updateLabels"></a>updateLabels

```php
mixed ProductCore::updateLabels()
```





* Visibility: **public**
* Source: [classes/Product.php line 3804](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L3804)




### <a name="method-updatePosition"></a>updatePosition

```php
mixed ProductCore::updatePosition(boolean $way, integer $position)
```

Move a product inside its category



* Visibility: **public**
* Source: [classes/Product.php line 460](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L460)


#### Arguments
* $way **boolean** - Up (1)  or Down (0)
* $position **integer** - return boolean Update result



### <a name="method-updateProductAttribute"></a>updateProductAttribute

```php
mixed ProductCore::updateProductAttribute($id_product_attribute, $wholesale_price, $price, $weight, $unit, $ecotax, $id_images, $reference, $supplier_reference, $ean13, $default, $location, $upc, $minimal_quantity, $available_date)
```

Update a product attribute



* Visibility: **public**
* Source: [classes/Product.php line 1194](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L1194)


#### Arguments
* $id_product_attribute **mixed**
* $wholesale_price **mixed**
* $price **mixed**
* $weight **mixed**
* $unit **mixed**
* $ecotax **mixed**
* $id_images **mixed**
* $reference **mixed**
* $supplier_reference **mixed**
* $ean13 **mixed**
* $default **mixed**
* $location **mixed**
* $upc **mixed**
* $minimal_quantity **mixed**
* $available_date **mixed**



### <a name="method-updateQuantity"></a>updateQuantity

```php
mixed ProductCore::updateQuantity(array $product, $id_order)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2688](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L2688)


#### Arguments
* $product **array** - Array with ordered product (quantity, id_product_attribute if applicable)
* $id_order **mixed**



### <a name="method-updateQuantityProductWithAttributeQuantity"></a>updateQuantityProductWithAttributeQuantity

```php
mixed ProductCore::updateQuantityProductWithAttributeQuantity()
```





* Visibility: **public**
* Source: [classes/Product.php line 1304](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L1304)




### <a name="method-updateWs"></a>updateWs

```php
mixed ProductCore::updateWs($null_values)
```





* Visibility: **public**
* Source: [classes/Product.php line 4643](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L4643)


#### Arguments
* $null_values **mixed**



### <a name="method-usesAdvancedStockManagement"></a>usesAdvancedStockManagement

```php
boolean ProductCore::usesAdvancedStockManagement(integer $id_product)
```

For a given product, tells if it uses the advanced stock management



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 4685](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L4685)


#### Arguments
* $id_product **integer**



### <a name="method-validateControler"></a>validateControler

```php
mixed ObjectModelCore::validateControler($htmlentities)
```

TODO: refactor rename all calls to this to validateController



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 753](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L753)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 759](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L759)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateField"></a>validateField

```php
boolean|string ObjectModelCore::validateField(string $field, mixed $value, integer $id_lang)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 704](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L704)


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
* Source: [classes/ObjectModel.php line 643](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L643)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-validateFieldsLang"></a>validateFieldsLang

```php
mixed ProductCore::validateFieldsLang($die, $error_return)
```





* Visibility: **public**
* Source: [classes/Product.php line 591](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Product.php#L591)


#### Arguments
* $die **mixed**
* $error_return **mixed**


