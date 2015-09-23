Class ProductCore
=====================





* Class name: ProductCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Product.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L36)


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
* [$price](#property-$price)
* [$producPropertiesCache](#property-$producPropertiesCache)
* [$quantity](#property-$quantity)
* [$quantity_discount](#property-$quantity_discount)
* [$redirect_type](#property-$redirect_type)
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
* [$visibility](#property-$visibility)
* [$webserviceParameters](#property-$webserviceParameters)
* [$weight](#property-$weight)
* [$wholesale_price](#property-$wholesale_price)
* [$width](#property-$width)

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
* [addProductAttribute](#method-addProductAttribute)
* [addProductAttributeMultiple](#method-addProductAttributeMultiple)
* [addStockMvt](#method-addStockMvt)
* [addSupplierReference](#method-addSupplierReference)
* [addToCategories](#method-addToCategories)
* [addWs](#method-addWs)
* [cacheFrontFeatures](#method-cacheFrontFeatures)
* [cacheProductsFeatures](#method-cacheProductsFeatures)
* [changeAccessories](#method-changeAccessories)
* [checkAccess](#method-checkAccess)
* [checkDefaultAttributes](#method-checkDefaultAttributes)
* [checkQty](#method-checkQty)
* [cleanPositions](#method-cleanPositions)
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
* [displayWtPrice](#method-displayWtPrice)
* [displayWtPriceWithCurrency](#method-displayWtPriceWithCurrency)
* [duplicateAccessories](#method-duplicateAccessories)
* [duplicateAttachments](#method-duplicateAttachments)
* [duplicateAttributes](#method-duplicateAttributes)
* [duplicateCustomizationFields](#method-duplicateCustomizationFields)
* [duplicateDownload](#method-duplicateDownload)
* [duplicateFeatures](#method-duplicateFeatures)
* [duplicateSpecificPrices](#method-duplicateSpecificPrices)
* [duplicateTags](#method-duplicateTags)
* [existsRefInDatabase](#method-existsRefInDatabase)
* [flushPriceCache](#method-flushPriceCache)
* [generateMultipleCombinations](#method-generateMultipleCombinations)
* [getAccessories](#method-getAccessories)
* [getAccessoriesLight](#method-getAccessoriesLight)
* [getAccessoryById](#method-getAccessoryById)
* [getAllCustomizedDatas](#method-getAllCustomizedDatas)
* [getAnchor](#method-getAnchor)
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
* [getCombinationImages](#method-getCombinationImages)
* [getCover](#method-getCover)
* [getCoverWs](#method-getCoverWs)
* [getCustomizationFieldIds](#method-getCustomizationFieldIds)
* [getCustomizationFields](#method-getCustomizationFields)
* [getDefaultAttribute](#method-getDefaultAttribute)
* [getDefaultCategory](#method-getDefaultCategory)
* [getDefaultIdProductAttribute](#method-getDefaultIdProductAttribute)
* [getFeatures](#method-getFeatures)
* [getFeaturesStatic](#method-getFeaturesStatic)
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
* [getRequiredCustomizableFields](#method-getRequiredCustomizableFields)
* [getRequiredCustomizableFieldsStatic](#method-getRequiredCustomizableFieldsStatic)
* [getShopsByProduct](#method-getShopsByProduct)
* [getSimpleProducts](#method-getSimpleProducts)
* [getStockMvts](#method-getStockMvts)
* [getTags](#method-getTags)
* [getTaxCalculationMethod](#method-getTaxCalculationMethod)
* [getTaxesInformations](#method-getTaxesInformations)
* [getTaxesRate](#method-getTaxesRate)
* [getType](#method-getType)
* [getUrlRewriteInformations](#method-getUrlRewriteInformations)
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
* [idIsOnCategoryId](#method-idIsOnCategoryId)
* [initPricesComputation](#method-initPricesComputation)
* [isAvailableWhenOutOfStock](#method-isAvailableWhenOutOfStock)
* [isColorUnavailable](#method-isColorUnavailable)
* [isDiscounted](#method-isDiscounted)
* [isNew](#method-isNew)
* [loadStockData](#method-loadStockData)
* [modifierWsLinkRewrite](#method-modifierWsLinkRewrite)
* [priceCalculation](#method-priceCalculation)
* [productAttributeExists](#method-productAttributeExists)
* [reinjectQuantities](#method-reinjectQuantities)
* [resetEcoTax](#method-resetEcoTax)
* [searchByName](#method-searchByName)
* [setAdvancedStockManagement](#method-setAdvancedStockManagement)
* [setAvailableDate](#method-setAvailableDate)
* [setCarriers](#method-setCarriers)
* [setCoverWs](#method-setCoverWs)
* [setDefaultAttribute](#method-setDefaultAttribute)
* [setGroupReduction](#method-setGroupReduction)
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
* [updatePosition](#method-updatePosition)
* [updateProductAttribute](#method-updateProductAttribute)
* [updateQuantity](#method-updateQuantity)
* [updateQuantityProductWithAttributeQuantity](#method-updateQuantityProductWithAttributeQuantity)
* [updateWs](#method-updateWs)
* [useAdvancedStockManagement](#method-useAdvancedStockManagement)
* [usesAdvancedStockManagement](#method-usesAdvancedStockManagement)
* [validateField](#method-validateField)


Constants
----------


### <a name="constant-CUSTOMIZE_FILE"></a>CUSTOMIZE_FILE

```php
const CUSTOMIZE_FILE = 0
```





* Source: [classes/Product.php line 451](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L451).


### <a name="constant-CUSTOMIZE_TEXTFIELD"></a>CUSTOMIZE_TEXTFIELD

```php
const CUSTOMIZE_TEXTFIELD = 1
```





* Source: [classes/Product.php line 452](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L452).


### <a name="constant-PTYPE_PACK"></a>PTYPE_PACK

```php
const PTYPE_PACK = 1
```





* Source: [classes/Product.php line 458](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L458).


### <a name="constant-PTYPE_SIMPLE"></a>PTYPE_SIMPLE

```php
const PTYPE_SIMPLE = 0
```

Note:  prefix is "PTYPE" because TYPE_ is used in ObjectModel (definition)



* Source: [classes/Product.php line 457](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L457).


### <a name="constant-PTYPE_VIRTUAL"></a>PTYPE_VIRTUAL

```php
const PTYPE_VIRTUAL = 2
```





* Source: [classes/Product.php line 459](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L459).


Properties
----------


### <a name="property-$_cacheFeatures"></a>$_cacheFeatures

```php
protected mixed $_cacheFeatures = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Product.php line 240](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L240).


### <a name="property-$_cart_quantity"></a>$_cart_quantity

```php
protected array $_cart_quantity = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Product.php line 237](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L237).


### <a name="property-$_frontFeaturesCache"></a>$_frontFeaturesCache

```php
protected mixed $_frontFeaturesCache = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Product.php line 241](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L241).


### <a name="property-$_incat"></a>$_incat

```php
protected mixed $_incat = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Product.php line 231](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L231).


### <a name="property-$_prices"></a>$_prices

```php
protected mixed $_prices = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Product.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L229).


### <a name="property-$_pricesLevel2"></a>$_pricesLevel2

```php
protected mixed $_pricesLevel2 = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Product.php line 230](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L230).


### <a name="property-$_taxCalculationMethod"></a>$_taxCalculationMethod

```php
public mixed $_taxCalculationMethod = null
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Product.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L228).


### <a name="property-$_tax_rules_group"></a>$_tax_rules_group

```php
protected mixed $_tax_rules_group = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Product.php line 239](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L239).


### <a name="property-$active"></a>$active

```php
public boolean $active = true
```





* Visibility: **public**
* Source: [classes/Product.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L165).


### <a name="property-$additional_shipping_cost"></a>$additional_shipping_cost

```php
public float $additional_shipping_cost
```





* Visibility: **public**
* Source: [classes/Product.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L87).


### <a name="property-$advanced_stock_management"></a>$advanced_stock_management

```php
public boolean $advanced_stock_management
```





* Visibility: **public**
* Source: [classes/Product.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L212).


### <a name="property-$available_date"></a>$available_date

```php
public string $available_date = '0000-00-00'
```





* Visibility: **public**
* Source: [classes/Product.php line 177](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L177).


### <a name="property-$available_for_order"></a>$available_for_order

```php
public boolean $available_for_order = true
```





* Visibility: **public**
* Source: [classes/Product.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L174).


### <a name="property-$available_later"></a>$available_later

```php
public string $available_later
```





* Visibility: **public**
* Source: [classes/Product.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L81).


### <a name="property-$available_now"></a>$available_now

```php
public string $available_now
```





* Visibility: **public**
* Source: [classes/Product.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L78).


### <a name="property-$cacheStock"></a>$cacheStock

```php
protected array $cacheStock = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Product.php line 245](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L245).


### <a name="property-$cache_default_attribute"></a>$cache_default_attribute

```php
public mixed $cache_default_attribute
```





* Visibility: **public**
* Source: [classes/Product.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L221).


### <a name="property-$cache_has_attachments"></a>$cache_has_attachments

```php
public mixed $cache_has_attachments
```





* Visibility: **public**
* Source: [classes/Product.php line 219](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L219).


### <a name="property-$cache_is_pack"></a>$cache_is_pack

```php
public mixed $cache_is_pack
```





* Visibility: **public**
* Source: [classes/Product.php line 218](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L218).


### <a name="property-$category"></a>$category

```php
public string $category
```





* Visibility: **public**
* Source: [classes/Product.php line 226](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L226).


### <a name="property-$condition"></a>$condition

```php
public \enum $condition
```





* Visibility: **public**
* Source: [classes/Product.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L180).


### <a name="property-$customizable"></a>$customizable

```php
public boolean $customizable
```





* Visibility: **public**
* Source: [classes/Product.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L153).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/Product.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L192).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* Source: [classes/Product.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L195).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'product', 'primary' => 'id_product', 'multilang' => true, 'multilang_shop' => true, 'fields' => array('id_shop_default' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_manufacturer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_supplier' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'reference' => array('type' => self::TYPE_STRING, 'validate' => 'isReference', 'size' => 32), 'supplier_reference' => array('type' => self::TYPE_STRING, 'validate' => 'isReference', 'size' => 32), 'location' => array('type' => self::TYPE_STRING, 'validate' => 'isReference', 'size' => 64), 'width' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat'), 'height' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat'), 'depth' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat'), 'weight' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat'), 'quantity_discount' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'ean13' => array('type' => self::TYPE_STRING, 'validate' => 'isEan13', 'size' => 13), 'upc' => array('type' => self::TYPE_STRING, 'validate' => 'isUpc', 'size' => 12), 'cache_is_pack' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'cache_has_attachments' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'is_virtual' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'id_category_default' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedId'), 'id_tax_rules_group' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedId'), 'on_sale' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'online_only' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'ecotax' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isPrice'), 'minimal_quantity' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedInt'), 'price' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isPrice', 'required' => true), 'wholesale_price' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isPrice'), 'unity' => array('type' => self::TYPE_STRING, 'shop' => true, 'validate' => 'isString'), 'unit_price_ratio' => array('type' => self::TYPE_FLOAT, 'shop' => true), 'additional_shipping_cost' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isPrice'), 'customizable' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedInt'), 'text_fields' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedInt'), 'uploadable_files' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedInt'), 'active' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'redirect_type' => array('type' => self::TYPE_STRING, 'shop' => true, 'validate' => 'isString'), 'id_product_redirected' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedId'), 'available_for_order' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'available_date' => array('type' => self::TYPE_DATE, 'shop' => true, 'validate' => 'isDateFormat'), 'condition' => array('type' => self::TYPE_STRING, 'shop' => true, 'validate' => 'isGenericName', 'values' => array('new', 'used', 'refurbished'), 'default' => 'new'), 'show_price' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'indexed' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'visibility' => array('type' => self::TYPE_STRING, 'shop' => true, 'validate' => 'isProductVisibility', 'values' => array('both', 'catalog', 'search', 'none'), 'default' => 'both'), 'cache_default_attribute' => array('type' => self::TYPE_INT, 'shop' => true), 'advanced_stock_management' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'date_add' => array('type' => self::TYPE_DATE, 'shop' => true, 'validate' => 'isDateFormat'), 'date_upd' => array('type' => self::TYPE_DATE, 'shop' => true, 'validate' => 'isDateFormat'), 'meta_description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_keywords' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_title' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 128), 'link_rewrite' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isLinkRewrite', 'required' => true, 'size' => 128, 'ws_modifier' => array('http_method' => \WebserviceRequest::HTTP_POST, 'modifier' => 'modifierWsLinkRewrite')), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isCatalogName', 'required' => true, 'size' => 128), 'description' => array('type' => self::TYPE_HTML, 'lang' => true, 'validate' => 'isCleanHtml'), 'description_short' => array('type' => self::TYPE_HTML, 'lang' => true, 'validate' => 'isCleanHtml'), 'available_now' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'available_later' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'IsGenericName', 'size' => 255)), 'associations' => array('manufacturer' => array('type' => self::HAS_ONE), 'supplier' => array('type' => self::HAS_ONE), 'default_category' => array('type' => self::HAS_ONE, 'field' => 'id_category_default', 'object' => 'Category'), 'tax_rules_group' => array('type' => self::HAS_ONE), 'categories' => array('type' => self::HAS_MANY, 'field' => 'id_category', 'object' => 'Category', 'association' => 'category_product'), 'stock_availables' => array('type' => self::HAS_MANY, 'field' => 'id_stock_available', 'object' => 'StockAvailable', 'association' => 'stock_availables')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Product.php line 247](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L247).


### <a name="property-$depends_on_stock"></a>$depends_on_stock

```php
public mixed $depends_on_stock
```





* Visibility: **public**
* Source: [classes/Product.php line 214](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L214).


### <a name="property-$depth"></a>$depth

```php
public string $depth
```





* Visibility: **public**
* Source: [classes/Product.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L126).


### <a name="property-$description"></a>$description

```php
public string $description
```





* Visibility: **public**
* Source: [classes/Product.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L66).


### <a name="property-$description_short"></a>$description_short

```php
public string $description_short
```





* Visibility: **public**
* Source: [classes/Product.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L69).


### <a name="property-$ean13"></a>$ean13

```php
public string $ean13
```





* Visibility: **public**
* Source: [classes/Product.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L132).


### <a name="property-$ecotax"></a>$ecotax

```php
public float $ecotax
```





* Visibility: **public**
* Source: [classes/Product.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L108).


### <a name="property-$height"></a>$height

```php
public string $height
```





* Visibility: **public**
* Source: [classes/Product.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L123).


### <a name="property-$id_category_default"></a>$id_category_default

```php
public integer $id_category_default
```





* Visibility: **public**
* Source: [classes/Product.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L51).


### <a name="property-$id_color_default"></a>$id_color_default

```php
public mixed $id_color_default
```

We keep this variable for retrocompatibility for themes



* Visibility: **public**
* Source: [classes/Product.php line 206](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L206).


### <a name="property-$id_manufacturer"></a>$id_manufacturer

```php
public integer $id_manufacturer
```





* Visibility: **public**
* Source: [classes/Product.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L45).


### <a name="property-$id_product_redirected"></a>$id_product_redirected

```php
public boolean $id_product_redirected
```





* Visibility: **public**
* Source: [classes/Product.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L171).


### <a name="property-$id_shop_default"></a>$id_shop_default

```php
public integer $id_shop_default
```





* Visibility: **public**
* Source: [classes/Product.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L54).


### <a name="property-$id_supplier"></a>$id_supplier

```php
public integer $id_supplier
```





* Visibility: **public**
* Source: [classes/Product.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L48).


### <a name="property-$id_tax_rules_group"></a>$id_tax_rules_group

```php
public mixed $id_tax_rules_group = 1
```





* Visibility: **public**
* Source: [classes/Product.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L200).


### <a name="property-$indexed"></a>$indexed

```php
public boolean $indexed
```





* Visibility: **public**
* Source: [classes/Product.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L186).


### <a name="property-$isFullyLoaded"></a>$isFullyLoaded

```php
public mixed $isFullyLoaded = false
```





* Visibility: **public**
* Source: [classes/Product.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L216).


### <a name="property-$is_virtual"></a>$is_virtual

```php
public mixed $is_virtual
```





* Visibility: **public**
* Source: [classes/Product.php line 220](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L220).


### <a name="property-$link_rewrite"></a>$link_rewrite

```php
public string $link_rewrite
```





* Visibility: **public**
* Source: [classes/Product.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L138).


### <a name="property-$location"></a>$location

```php
public string $location
```





* Visibility: **public**
* Source: [classes/Product.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L117).


### <a name="property-$manufacturer_name"></a>$manufacturer_name

```php
public string $manufacturer_name
```





* Visibility: **public**
* Source: [classes/Product.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L57).


### <a name="property-$meta_description"></a>$meta_description

```php
public string $meta_description
```





* Visibility: **public**
* Source: [classes/Product.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L141).


### <a name="property-$meta_keywords"></a>$meta_keywords

```php
public string $meta_keywords
```





* Visibility: **public**
* Source: [classes/Product.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L144).


### <a name="property-$meta_title"></a>$meta_title

```php
public string $meta_title
```





* Visibility: **public**
* Source: [classes/Product.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L147).


### <a name="property-$minimal_quantity"></a>$minimal_quantity

```php
public integer $minimal_quantity = 1
```





* Visibility: **public**
* Source: [classes/Product.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L75).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/Product.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L63).


### <a name="property-$new"></a>$new

```php
public boolean $new = null
```





* Visibility: **public**
* Source: [classes/Product.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L156).


### <a name="property-$on_sale"></a>$on_sale

```php
public boolean $on_sale = false
```





* Visibility: **public**
* Source: [classes/Product.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L93).


### <a name="property-$online_only"></a>$online_only

```php
public boolean $online_only = false
```





* Visibility: **public**
* Source: [classes/Product.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L96).


### <a name="property-$out_of_stock"></a>$out_of_stock

```php
public mixed $out_of_stock
```





* Visibility: **public**
* Source: [classes/Product.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L213).


### <a name="property-$price"></a>$price

```php
public float $price
```





* Visibility: **public**
* Source: [classes/Product.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L84).


### <a name="property-$producPropertiesCache"></a>$producPropertiesCache

```php
protected mixed $producPropertiesCache = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Product.php line 242](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L242).


### <a name="property-$quantity"></a>$quantity

```php
public integer $quantity
```





* Visibility: **public**
* Source: [classes/Product.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L72).


### <a name="property-$quantity_discount"></a>$quantity_discount

```php
public boolean $quantity_discount
```





* Visibility: **public**
* Source: [classes/Product.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L150).


### <a name="property-$redirect_type"></a>$redirect_type

```php
public boolean $redirect_type = ''
```





* Visibility: **public**
* Source: [classes/Product.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L168).


### <a name="property-$reference"></a>$reference

```php
public string $reference
```





* Visibility: **public**
* Source: [classes/Product.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L111).


### <a name="property-$show_price"></a>$show_price

```php
public boolean $show_price = true
```





* Visibility: **public**
* Source: [classes/Product.php line 183](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L183).


### <a name="property-$supplier_name"></a>$supplier_name

```php
public string $supplier_name
```





* Visibility: **public**
* Source: [classes/Product.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L60).


### <a name="property-$supplier_reference"></a>$supplier_reference

```php
public string $supplier_reference
```





* Visibility: **public**
* Source: [classes/Product.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L114).


### <a name="property-$tags"></a>$tags

```php
public mixed $tags
```





* Visibility: **public**
* Source: [classes/Product.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L198).


### <a name="property-$tax_name"></a>$tax_name

```php
public string $tax_name
```





* Visibility: **public**
* Source: [classes/Product.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L39).


### <a name="property-$tax_rate"></a>$tax_rate

```php
public string $tax_rate
```





* Visibility: **public**
* Source: [classes/Product.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L42).


### <a name="property-$text_fields"></a>$text_fields

```php
public integer $text_fields
```





* Visibility: **public**
* Source: [classes/Product.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L162).


### <a name="property-$unit_price"></a>$unit_price

```php
public float $unit_price
```





* Visibility: **public**
* Source: [classes/Product.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L102).


### <a name="property-$unit_price_ratio"></a>$unit_price_ratio

```php
public float $unit_price_ratio
```





* Visibility: **public**
* Source: [classes/Product.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L105).


### <a name="property-$unity"></a>$unity

```php
public string $unity = null
```





* Visibility: **public**
* Source: [classes/Product.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L99).


### <a name="property-$upc"></a>$upc

```php
public string $upc
```





* Visibility: **public**
* Source: [classes/Product.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L135).


### <a name="property-$uploadable_files"></a>$uploadable_files

```php
public integer $uploadable_files
```





* Visibility: **public**
* Source: [classes/Product.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L159).


### <a name="property-$visibility"></a>$visibility

```php
public string $visibility
```





* Visibility: **public**
* Source: [classes/Product.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L189).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectMethods' => array('add' => 'addWs', 'update' => 'updateWs'), 'objectNodeNames' => 'products', 'fields' => array('id_manufacturer' => array('xlink_resource' => 'manufacturers'), 'id_supplier' => array('xlink_resource' => 'suppliers'), 'id_category_default' => array('xlink_resource' => 'categories'), 'new' => array(), 'cache_default_attribute' => array(), 'id_default_image' => array('getter' => 'getCoverWs', 'setter' => 'setCoverWs', 'xlink_resource' => array('resourceName' => 'images', 'subResourceName' => 'products')), 'id_default_combination' => array('getter' => 'getWsDefaultCombination', 'setter' => 'setWsDefaultCombination', 'xlink_resource' => array('resourceName' => 'combinations')), 'id_tax_rules_group' => array('xlink_resource' => array('resourceName' => 'tax_rule_groups')), 'position_in_category' => array('getter' => 'getWsPositionInCategory', 'setter' => 'setWsPositionInCategory'), 'manufacturer_name' => array('getter' => 'getWsManufacturerName', 'setter' => false), 'quantity' => array('getter' => false, 'setter' => false), 'type' => array('getter' => 'getWsType', 'setter' => 'setWsType')), 'associations' => array('categories' => array('resource' => 'category', 'fields' => array('id' => array('required' => true))), 'images' => array('resource' => 'image', 'fields' => array('id' => array())), 'combinations' => array('resource' => 'combination', 'fields' => array('id' => array('required' => true))), 'product_option_values' => array('resource' => 'product_option_value', 'fields' => array('id' => array('required' => true))), 'product_features' => array('resource' => 'product_feature', 'fields' => array('id' => array('required' => true), 'custom' => array('required' => false), 'id_feature_value' => array('required' => true, 'xlink_resource' => 'product_feature_values'))), 'tags' => array('resource' => 'tag', 'fields' => array('id' => array('required' => true))), 'stock_availables' => array('resource' => 'stock_available', 'fields' => array('id' => array('required' => true), 'id_product_attribute' => array('required' => true)), 'setter' => false), 'accessories' => array('resource' => 'product', 'api' => 'products', 'fields' => array('id' => array('required' => true, 'xlink_resource' => 'product'))), 'product_bundle' => array('resource' => 'product', 'api' => 'products', 'fields' => array('id' => array('required' => true), 'quantity' => array()))))
```





* Visibility: **protected**
* Source: [classes/Product.php line 331](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L331).


### <a name="property-$weight"></a>$weight

```php
public string $weight
```





* Visibility: **public**
* Source: [classes/Product.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L129).


### <a name="property-$wholesale_price"></a>$wholesale_price

```php
public float $wholesale_price
```





* Visibility: **public**
* Source: [classes/Product.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L90).


### <a name="property-$width"></a>$width

```php
public string $width
```





* Visibility: **public**
* Source: [classes/Product.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L120).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ProductCore::__construct($id_product, $full, $id_lang, $id_shop, \Context $context)
```





* Visibility: **public**
* Source: [classes/Product.php line 461](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L461)


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
* Source: [classes/Product.php line 4180](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4180)


#### Arguments
* $field **mixed**
* $value **mixed**



### <a name="method-_createLabel"></a>_createLabel

```php
mixed ProductCore::_createLabel($languages, $type)
```





* Visibility: **protected**
* Source: [classes/Product.php line 4261](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4261)


#### Arguments
* $languages **mixed**
* $type **mixed**



### <a name="method-_deleteOldLabels"></a>_deleteOldLabels

```php
mixed ProductCore::_deleteOldLabels()
```





* Visibility: **protected**
* Source: [classes/Product.php line 4190](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4190)




### <a name="method-_getAttributeImageAssociations"></a>_getAttributeImageAssociations

```php
array ProductCore::_getAttributeImageAssociations(integer $id_product_attribute)
```

Get product attribute image associations



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3576](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3576)


#### Arguments
* $id_product_attribute **integer**



### <a name="method-_getCustomizationFieldsNLabels"></a>_getCustomizationFieldsNLabels

```php
mixed ProductCore::_getCustomizationFieldsNLabels($product_id)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/Product.php line 3731](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3731)


#### Arguments
* $product_id **mixed**



### <a name="method-_getProductIdByDate"></a>_getProductIdByDate

```php
mixed ProductCore::_getProductIdByDate($beginning, $ending, \Context $context, $with_combination)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/Product.php line 2129](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L2129)


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
* Source: [classes/Product.php line 510](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L510)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addAttribute"></a>addAttribute

```php
mixed ProductCore::addAttribute(float $price, float $weight, $unit_impact, float $ecotax, integer $id_images, string $reference, string $ean13, boolean $default, string $location, $upc, integer $minimal_quantity, array $id_shop_list, $available_date)
```

Add a product attribute



* Visibility: **public**
* Source: [classes/Product.php line 1501](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1501)


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
* Source: [classes/Product.php line 1730](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1730)


#### Arguments
* $id_product_attribute **integer** - Product attribute id
* $attributes **array** - Attributes to forge combinaison



### <a name="method-addAttributeCombinationMultiple"></a>addAttributeCombinationMultiple

```php
mixed ProductCore::addAttributeCombinationMultiple($id_attributes, $combinations)
```





* Visibility: **public**
* Source: [classes/Product.php line 1742](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1742)


#### Arguments
* $id_attributes **mixed**
* $combinations **mixed**



### <a name="method-addCombinationEntity"></a>addCombinationEntity

```php
mixed ProductCore::addCombinationEntity($wholesale_price, $price, $weight, $unit_impact, $ecotax, integer $quantity, $id_images, $reference, $id_supplier, $ean13, $default, $location, $upc, $minimal_quantity, array $id_shop_list, $available_date)
```





* Visibility: **public**
* Source: [classes/Product.php line 1269](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1269)


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
* Source: [classes/Product.php line 4119](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4119)


#### Arguments
* $products **mixed**
* $customized_datas **mixed**



### <a name="method-addFeatureProductImport"></a>addFeatureProductImport

```php
mixed ProductCore::addFeatureProductImport($id_product, $id_feature, $id_feature_value)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3316](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3316)


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
* Source: [classes/Product.php line 3295](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3295)


#### Arguments
* $id_value **mixed**
* $lang **mixed**
* $cust **mixed**



### <a name="method-addFeaturesToDB"></a>addFeaturesToDB

```php
mixed ProductCore::addFeaturesToDB($id_feature, $id_value, $cust)
```





* Visibility: **public**
* Source: [classes/Product.php line 3301](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3301)


#### Arguments
* $id_feature **mixed**
* $id_value **mixed**
* $cust **mixed**



### <a name="method-addProductAttribute"></a>addProductAttribute

```php
mixed ProductCore::addProductAttribute($price, $weight, $unit_impact, $ecotax, $quantity, $id_images, $reference, $id_supplier, $ean13, $default, $location, $upc, $minimal_quantity)
```

addProductAttribute is deprecated

The quantity params now set StockAvailable for the current shop with the specified quantity
The supplier_reference params now set the supplier reference of the default supplier of the product if possible

* Visibility: **public**
* Source: [classes/Product.php line 1207](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1207)


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
mixed ProductCore::addProductAttributeMultiple($attributes, $set_default)
```





* Visibility: **public**
* Source: [classes/Product.php line 1287](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1287)


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
* Source: [classes/Product.php line 4486](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4486)


#### Arguments
* $quantity **integer**
* $id_reason **integer** - 
useless

* $id_product_attribute **integer**
* $id_order **integer** - 
useless

* $id_employee **integer** - 
useless




### <a name="method-addSupplierReference"></a>addSupplierReference

```php
mixed ProductCore::addSupplierReference(integer $id_supplier, integer $id_product_attribute, string $supplier_reference, float $price, integer $id_currency)
```

Sets or updates Supplier Reference



* Visibility: **public**
* Source: [classes/Product.php line 1392](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1392)


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
* Source: [classes/Product.php line 882](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L882)


#### Arguments
* $categories **mixed** - id_category or array of id_category



### <a name="method-addWs"></a>addWs

```php
mixed ProductCore::addWs($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Product.php line 5318](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5318)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-cacheFrontFeatures"></a>cacheFrontFeatures

```php
mixed ProductCore::cacheFrontFeatures($product_ids, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3373](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3373)


#### Arguments
* $product_ids **mixed**
* $id_lang **mixed**



### <a name="method-cacheProductsFeatures"></a>cacheProductsFeatures

```php
mixed ProductCore::cacheProductsFeatures($product_ids)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3349](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3349)


#### Arguments
* $product_ids **mixed**



### <a name="method-changeAccessories"></a>changeAccessories

```php
mixed ProductCore::changeAccessories(array $accessories_id)
```

Link accessories with product



* Visibility: **public**
* Source: [classes/Product.php line 3283](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3283)


#### Arguments
* $accessories_id **array** - Accessories ids



### <a name="method-checkAccess"></a>checkAccess

```php
mixed ProductCore::checkAccess($id_customer)
```





* Visibility: **public**
* Source: [classes/Product.php line 4443](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4443)


#### Arguments
* $id_customer **mixed**



### <a name="method-checkDefaultAttributes"></a>checkDefaultAttributes

```php
mixed ProductCore::checkDefaultAttributes()
```

Check if there is no default attribute and create it if not



* Visibility: **public**
* Source: [classes/Product.php line 3071](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3071)




### <a name="method-checkQty"></a>checkQty

```php
boolean ProductCore::checkQty(integer $qty)
```

Check product availability



* Visibility: **public**
* Source: [classes/Product.php line 3052](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3052)


#### Arguments
* $qty **integer** - Quantity desired



### <a name="method-cleanPositions"></a>cleanPositions

```php
mixed ProductCore::cleanPositions($id_category)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 619](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L619)


#### Arguments
* $id_category **mixed**



### <a name="method-convertAndFormatPrice"></a>convertAndFormatPrice

```php
mixed ProductCore::convertAndFormatPrice($price, $currency, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2824](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L2824)


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
* Source: [classes/Product.php line 2919](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L2919)


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
* Source: [classes/Product.php line 2931](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L2931)


#### Arguments
* $params **array**
* $smarty **object** - DEPRECATED



### <a name="method-createLabels"></a>createLabels

```php
mixed ProductCore::createLabels($uploadable_files, $text_fields)
```





* Visibility: **public**
* Source: [classes/Product.php line 4287](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4287)


#### Arguments
* $uploadable_files **mixed**
* $text_fields **mixed**



### <a name="method-defineProductImage"></a>defineProductImage

```php
mixed ProductCore::defineProductImage($row, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3841](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3841)


#### Arguments
* $row **mixed**
* $id_lang **mixed**



### <a name="method-delete"></a>delete

```php
mixed ProductCore::delete()
```





* Visibility: **public**
* Source: [classes/Product.php line 796](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L796)




### <a name="method-deleteAccessories"></a>deleteAccessories

```php
mixed ProductCore::deleteAccessories()
```

Delete product accessories



* Visibility: **public**
* Source: [classes/Product.php line 3185](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3185)




### <a name="method-deleteAttachments"></a>deleteAttachments

```php
array ProductCore::deleteAttachments($update_attachment_cache)
```

Delete product attachments



* Visibility: **public**
* Source: [classes/Product.php line 1625](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1625)


#### Arguments
* $update_attachment_cache **mixed**



### <a name="method-deleteAttributeCombinaison"></a>deleteAttributeCombinaison

```php
mixed ProductCore::deleteAttributeCombinaison(integer $id_product_attribute)
```





* Visibility: **public**
* Source: [classes/Product.php line 5507](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5507)


#### Arguments
* $id_product_attribute **integer**



### <a name="method-deleteAttributeCombination"></a>deleteAttributeCombination

```php
array ProductCore::deleteAttributeCombination(integer $id_product_attribute)
```

Delete a product attributes combination



* Visibility: **public**
* Source: [classes/Product.php line 1764](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1764)


#### Arguments
* $id_product_attribute **integer** - Product attribute id



### <a name="method-deleteAttributesImpacts"></a>deleteAttributesImpacts

```php
\Deletion ProductCore::deleteAttributesImpacts()
```

Delete product attributes impacts



* Visibility: **public**
* Source: [classes/Product.php line 1586](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1586)




### <a name="method-deleteCartProducts"></a>deleteCartProducts

```php
array ProductCore::deleteCartProducts()
```

Delete product from cart



* Visibility: **public**
* Source: [classes/Product.php line 1023](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1023)




### <a name="method-deleteCategories"></a>deleteCategories

```php
array ProductCore::deleteCategories(boolean $clean_positions)
```

Delete all association to category where product is indexed



* Visibility: **public**
* Source: [classes/Product.php line 990](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L990)


#### Arguments
* $clean_positions **boolean** - clean category positions after deletion



### <a name="method-deleteCategory"></a>deleteCategory

```php
boolean ProductCore::deleteCategory(mixed $id_category, mixed $clean_positions)
```

deleteCategory delete this product from the category $id_category



* Visibility: **public**
* Source: [classes/Product.php line 967](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L967)


#### Arguments
* $id_category **mixed**
* $clean_positions **mixed**



### <a name="method-deleteCustomization"></a>deleteCustomization

```php
array ProductCore::deleteCustomization()
```

Delete product customizations



* Visibility: **public**
* Source: [classes/Product.php line 1643](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1643)




### <a name="method-deleteDefaultAttributes"></a>deleteDefaultAttributes

```php
mixed ProductCore::deleteDefaultAttributes()
```

Del all default attributes for product



* Visibility: **public**
* Source: [classes/Product.php line 1323](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1323)




### <a name="method-deleteDownload"></a>deleteDownload

```php
boolean ProductCore::deleteDownload()
```

Remove all downloadable files for product and its attributes



* Visibility: **public**
* Source: [classes/Product.php line 5481](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5481)




### <a name="method-deleteFeatures"></a>deleteFeatures

```php
mixed ProductCore::deleteFeatures()
```

Delete features



* Visibility: **public**
* Source: [classes/Product.php line 1788](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1788)




### <a name="method-deleteFromAccessories"></a>deleteFromAccessories

```php
mixed ProductCore::deleteFromAccessories()
```

Delete product from other products accessories



* Visibility: **public**
* Source: [classes/Product.php line 3195](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3195)




### <a name="method-deleteFromCartRules"></a>deleteFromCartRules

```php
mixed ProductCore::deleteFromCartRules()
```





* Visibility: **public**
* Source: [classes/Product.php line 865](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L865)




### <a name="method-deleteFromSupplier"></a>deleteFromSupplier

```php
mixed ProductCore::deleteFromSupplier()
```





* Visibility: **public**
* Source: [classes/Product.php line 871](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L871)




### <a name="method-deleteImages"></a>deleteImages

```php
boolean ProductCore::deleteImages()
```

Delete product images from database



* Visibility: **public**
* Source: [classes/Product.php line 1033](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1033)




### <a name="method-deletePack"></a>deletePack

```php
array ProductCore::deletePack()
```

Delete product pack details



* Visibility: **public**
* Source: [classes/Product.php line 1664](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1664)




### <a name="method-deleteProductAttributes"></a>deleteProductAttributes

```php
array ProductCore::deleteProductAttributes()
```

Delete product attributes



* Visibility: **public**
* Source: [classes/Product.php line 1567](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1567)




### <a name="method-deleteProductFeatures"></a>deleteProductFeatures

```php
array ProductCore::deleteProductFeatures()
```

Delete product features



* Visibility: **public**
* Source: [classes/Product.php line 1599](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1599)




### <a name="method-deleteProductSale"></a>deleteProductSale

```php
array ProductCore::deleteProductSale()
```

Delete product sales



* Visibility: **public**
* Source: [classes/Product.php line 1678](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1678)




### <a name="method-deleteSceneProducts"></a>deleteSceneProducts

```php
array ProductCore::deleteSceneProducts()
```

Delete product in its scenes



* Visibility: **public**
* Source: [classes/Product.php line 1691](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1691)




### <a name="method-deleteSearchIndexes"></a>deleteSearchIndexes

```php
array ProductCore::deleteSearchIndexes()
```

Delete product indexed words



* Visibility: **public**
* Source: [classes/Product.php line 1704](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1704)




### <a name="method-deleteSelection"></a>deleteSelection

```php
mixed ProductCore::deleteSelection($products)
```





* Visibility: **public**
* Source: [classes/Product.php line 847](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L847)


#### Arguments
* $products **mixed**



### <a name="method-deleteTags"></a>deleteTags

```php
array ProductCore::deleteTags()
```

Delete products tags entries



* Visibility: **public**
* Source: [classes/Product.php line 1012](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1012)




### <a name="method-deleteWsTags"></a>deleteWsTags

```php
array ProductCore::deleteWsTags()
```

Delete products tags entries without delete tags for webservice usage



* Visibility: **public**
* Source: [classes/Product.php line 4992](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4992)




### <a name="method-displayWtPrice"></a>displayWtPrice

```php
mixed ProductCore::displayWtPrice($params, $smarty)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2936](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L2936)


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
* Source: [classes/Product.php line 2948](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L2948)


#### Arguments
* $params **array**
* $smarty **mixed**



### <a name="method-duplicateAccessories"></a>duplicateAccessories

```php
mixed ProductCore::duplicateAccessories($id_product_old, $id_product_new)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3588](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3588)


#### Arguments
* $id_product_old **mixed**
* $id_product_new **mixed**



### <a name="method-duplicateAttachments"></a>duplicateAttachments

```php
mixed ProductCore::duplicateAttachments($id_product_old, $id_product_new)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3652](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3652)


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
* Source: [classes/Product.php line 3469](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3469)


#### Arguments
* $id_product_old **integer** - Old product id
* $id_product_new **integer** - New product id



### <a name="method-duplicateCustomizationFields"></a>duplicateCustomizationFields

```php
mixed ProductCore::duplicateCustomizationFields($old_product_id, $product_id)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3775](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3775)


#### Arguments
* $old_product_id **mixed**
* $product_id **mixed**



### <a name="method-duplicateDownload"></a>duplicateDownload

```php
mixed ProductCore::duplicateDownload($id_product_old, $id_product_new)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3622](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3622)


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
* Source: [classes/Product.php line 3682](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3682)


#### Arguments
* $id_product_old **integer** - Old product id
* $id_product_new **mixed**



### <a name="method-duplicateSpecificPrices"></a>duplicateSpecificPrices

```php
mixed ProductCore::duplicateSpecificPrices($old_product_id, $product_id)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3764](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3764)


#### Arguments
* $old_product_id **mixed**
* $product_id **mixed**



### <a name="method-duplicateTags"></a>duplicateTags

```php
mixed ProductCore::duplicateTags($id_product_old, $id_product_new)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3606](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3606)


#### Arguments
* $id_product_old **mixed**
* $id_product_new **mixed**



### <a name="method-existsRefInDatabase"></a>existsRefInDatabase

```php
boolean ProductCore::existsRefInDatabase($reference)
```

Checks if reference exists



* Visibility: **public**
* Source: [classes/Product.php line 5022](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5022)


#### Arguments
* $reference **mixed**



### <a name="method-flushPriceCache"></a>flushPriceCache

```php
mixed ProductCore::flushPriceCache()
```

This method allows to flush price cache



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 5381](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5381)




### <a name="method-generateMultipleCombinations"></a>generateMultipleCombinations

```php
mixed ProductCore::generateMultipleCombinations($combinations, $attributes)
```





* Visibility: **public**
* Source: [classes/Product.php line 1226](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1226)


#### Arguments
* $combinations **mixed**
* $attributes **mixed**



### <a name="method-getAccessories"></a>getAccessories

```php
array ProductCore::getAccessories(integer $id_lang, $active, \Context $context)
```

Get product accessories



* Visibility: **public**
* Source: [classes/Product.php line 3231](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3231)


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
* Source: [classes/Product.php line 3207](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3207)


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
* Source: [classes/Product.php line 3273](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3273)


#### Arguments
* $accessory_id **mixed**



### <a name="method-getAllCustomizedDatas"></a>getAllCustomizedDatas

```php
mixed ProductCore::getAllCustomizedDatas($id_cart, $id_lang, $only_in_cart)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 4075](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4075)


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
* Source: [classes/Product.php line 5259](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5259)


#### Arguments
* $id_product_attribute **integer**



### <a name="method-getAttachments"></a>getAttachments

```php
mixed ProductCore::getAttachments($id_lang)
```





* Visibility: **public**
* Source: [classes/Product.php line 4066](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4066)


#### Arguments
* $id_lang **mixed**



### <a name="method-getAttachmentsStatic"></a>getAttachmentsStatic

```php
mixed ProductCore::getAttachmentsStatic($id_lang, $id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 4056](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4056)


#### Arguments
* $id_lang **mixed**
* $id_product **mixed**



### <a name="method-getAttributeCombinaisons"></a>getAttributeCombinaisons

```php
mixed ProductCore::getAttributeCombinaisons(integer $id_lang)
```





* Visibility: **public**
* Source: [classes/Product.php line 5496](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5496)


#### Arguments
* $id_lang **integer**



### <a name="method-getAttributeCombinations"></a>getAttributeCombinations

```php
array ProductCore::getAttributeCombinations(integer $id_lang)
```

Get all available product attributes combinations



* Visibility: **public**
* Source: [classes/Product.php line 1877](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1877)


#### Arguments
* $id_lang **integer** - Language id



### <a name="method-getAttributeCombinationsById"></a>getAttributeCombinationsById

```php
array ProductCore::getAttributeCombinationsById(integer $id_product_attribute, integer $id_lang)
```

Get product attribute combination by id_product_attribute



* Visibility: **public**
* Source: [classes/Product.php line 1921](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1921)


#### Arguments
* $id_product_attribute **integer**
* $id_lang **integer** - Language id



### <a name="method-getAttributesColorList"></a>getAttributesColorList

```php
mixed ProductCore::getAttributesColorList(array $products, $have_stock)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3111](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3111)


#### Arguments
* $products **array**
* $have_stock **mixed**



### <a name="method-getAttributesGroups"></a>getAttributesGroups

```php
array ProductCore::getAttributesGroups(integer $id_lang)
```

Get all available attribute groups



* Visibility: **public**
* Source: [classes/Product.php line 3154](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3154)


#### Arguments
* $id_lang **integer** - Language id



### <a name="method-getAttributesImpacts"></a>getAttributesImpacts

```php
mixed ProductCore::getAttributesImpacts($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3553](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3553)


#### Arguments
* $id_product **mixed**



### <a name="method-getAttributesInformationsByProduct"></a>getAttributesInformationsByProduct

```php
mixed ProductCore::getAttributesInformationsByProduct(integer $id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 5152](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5152)


#### Arguments
* $id_product **integer**



### <a name="method-getAttributesParams"></a>getAttributesParams

```php
array ProductCore::getAttributesParams(integer $id_product, $id_product_attribute)
```

Get label by lang and value by lang too



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 5055](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5055)


#### Arguments
* $id_product **integer**
* $id_product_attribute **mixed**



### <a name="method-getAttributesResume"></a>getAttributesResume

```php
array ProductCore::getAttributesResume(integer $id_lang, $attribute_value_separator, $attribute_separator)
```

Get all available product attributes resume



* Visibility: **public**
* Source: [classes/Product.php line 1822](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1822)


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
* Source: [classes/Product.php line 719](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L719)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - Optional



### <a name="method-getCarriers"></a>getCarriers

```php
mixed ProductCore::getCarriers()
```

Gets carriers assigned to the product



* Visibility: **public**
* Source: [classes/Product.php line 2405](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L2405)




### <a name="method-getCategories"></a>getCategories

```php
array ProductCore::getCategories()
```

getCategories return an array of categories which this product belongs to



* Visibility: **public**
* Source: [classes/Product.php line 2397](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L2397)




### <a name="method-getColorsListCacheId"></a>getColorsListCacheId

```php
mixed ProductCore::getColorsListCacheId($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 5663](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5663)


#### Arguments
* $id_product **mixed**



### <a name="method-getCombinationImages"></a>getCombinationImages

```php
mixed ProductCore::getCombinationImages($id_lang)
```





* Visibility: **public**
* Source: [classes/Product.php line 1958](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1958)


#### Arguments
* $id_lang **mixed**



### <a name="method-getCover"></a>getCover

```php
array ProductCore::getCover($id_product, \Context $context)
```

Get product cover image



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2471](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L2471)


#### Arguments
* $id_product **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getCoverWs"></a>getCoverWs

```php
integer ProductCore::getCoverWs()
```

Webservice getter : get virtual field id_default_image in category



* Visibility: **public**
* Source: [classes/Product.php line 4906](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4906)




### <a name="method-getCustomizationFieldIds"></a>getCustomizationFieldIds

```php
mixed ProductCore::getCustomizationFieldIds()
```





* Visibility: **public**
* Source: [classes/Product.php line 4360](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4360)




### <a name="method-getCustomizationFields"></a>getCustomizationFields

```php
mixed ProductCore::getCustomizationFields($id_lang)
```





* Visibility: **public**
* Source: [classes/Product.php line 4337](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4337)


#### Arguments
* $id_lang **mixed**



### <a name="method-getDefaultAttribute"></a>getDefaultAttribute

```php
integer ProductCore::getDefaultAttribute($id_product, $minimum_quantity)
```

Get the default attribute for a product



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 644](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L644)


#### Arguments
* $id_product **mixed**
* $minimum_quantity **mixed**



### <a name="method-getDefaultCategory"></a>getDefaultCategory

```php
mixed ProductCore::getDefaultCategory()
```

get the default category according to the shop



* Visibility: **public**
* Source: [classes/Product.php line 5453](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5453)




### <a name="method-getDefaultIdProductAttribute"></a>getDefaultIdProductAttribute

```php
mixed ProductCore::getDefaultIdProductAttribute()
```





* Visibility: **public**
* Source: [classes/Product.php line 2891](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L2891)




### <a name="method-getFeatures"></a>getFeatures

```php
array ProductCore::getFeatures()
```

Select all features for the object



* Visibility: **public**
* Source: [classes/Product.php line 3330](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3330)




### <a name="method-getFeaturesStatic"></a>getFeaturesStatic

```php
mixed ProductCore::getFeaturesStatic($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3335](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3335)


#### Arguments
* $id_product **mixed**



### <a name="method-getFieldsShop"></a>getFieldsShop

```php
array ProductCore::getFieldsShop()
```





* Visibility: **public**
* Source: [classes/Product.php line 500](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L500)




### <a name="method-getFrontFeatures"></a>getFrontFeatures

```php
mixed ProductCore::getFrontFeatures($id_lang)
```





* Visibility: **public**
* Source: [classes/Product.php line 4051](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4051)


#### Arguments
* $id_lang **mixed**



### <a name="method-getFrontFeaturesStatic"></a>getFrontFeaturesStatic

```php
mixed ProductCore::getFrontFeaturesStatic($id_lang, $id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 4031](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4031)


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
* Source: [classes/Product.php line 5564](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5564)


#### Arguments
* $ean13 **string**



### <a name="method-getIdProductAttributeMostExpensive"></a>getIdProductAttributeMostExpensive

```php
mixed ProductCore::getIdProductAttributeMostExpensive()
```





* Visibility: **public**
* Source: [classes/Product.php line 2876](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L2876)




### <a name="method-getIdTaxRulesGroup"></a>getIdTaxRulesGroup

```php
mixed ProductCore::getIdTaxRulesGroup()
```





* Visibility: **public**
* Source: [classes/Product.php line 4551](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4551)




### <a name="method-getIdTaxRulesGroupByIdProduct"></a>getIdTaxRulesGroupByIdProduct

```php
mixed ProductCore::getIdTaxRulesGroupByIdProduct($id_product, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 4556](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4556)


#### Arguments
* $id_product **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getIdTaxRulesGroupMostUsed"></a>getIdTaxRulesGroupMostUsed

```php
mixed ProductCore::getIdTaxRulesGroupMostUsed()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 5541](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5541)




### <a name="method-getImages"></a>getImages

```php
array ProductCore::getImages(integer $id_lang, \Context $context)
```

Get product images and legends



* Visibility: **public**
* Source: [classes/Product.php line 2452](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L2452)


#### Arguments
* $id_lang **integer** - Language id for multilingual legends
* $context **[Context](class.ContextCore.md)**



### <a name="method-getLink"></a>getLink

```php
mixed ProductCore::getLink(\Context $context)
```

Get the link of the product page of this product



* Visibility: **public**
* Source: [classes/Product.php line 3819](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3819)


#### Arguments
* $context **[Context](class.ContextCore.md)**



### <a name="method-getNewProducts"></a>getNewProducts

```php
array ProductCore::getNewProducts(integer $id_lang, $page_number, $nb_products, $count, $order_by, $order_way, \Context $context)
```

Get new products



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2021](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L2021)


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
* Source: [classes/Product.php line 4438](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4438)




### <a name="method-getParentCategories"></a>getParentCategories

```php
array ProductCore::getParentCategories(integer $id_lang)
```

Get list of parent categories



* Visibility: **public**
* Source: [classes/Product.php line 5394](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5394)


#### Arguments
* $id_lang **integer**



### <a name="method-getPrice"></a>getPrice

```php
float ProductCore::getPrice(boolean $tax, integer $id_product_attribute, integer $decimals, integer $divisor, $only_reduc, $usereduc, $quantity)
```

Get product price
Same as static function getPriceStatic, no need to specify product id



* Visibility: **public**
* Source: [classes/Product.php line 2862](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L2862)


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
* Source: [classes/Product.php line 2510](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L2510)


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
* Source: [classes/Product.php line 2907](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L2907)


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
* Source: [classes/Product.php line 2241](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L2241)


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
* Source: [classes/Product.php line 1054](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1054)


#### Arguments
* $id_product_attribute **mixed**



### <a name="method-getProductAttributesIds"></a>getProductAttributesIds

```php
array ProductCore::getProductAttributesIds(integer $id_product, $shop_only)
```

Get all product attributes ids



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 5039](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5039)


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
* Source: [classes/Product.php line 2355](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L2355)


#### Arguments
* $id_product **mixed**



### <a name="method-getProductCategoriesFull"></a>getProductCategoriesFull

```php
mixed ProductCore::getProductCategoriesFull($id_product, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2371](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L2371)


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
* Source: [classes/Product.php line 5281](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5281)


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
* Source: [classes/Product.php line 3849](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3849)


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
* Source: [classes/Product.php line 1069](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1069)


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
* Source: [classes/Product.php line 4013](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4013)


#### Arguments
* $id_lang **mixed**
* $query_result **mixed**



### <a name="method-getPublicPrice"></a>getPublicPrice

```php
mixed ProductCore::getPublicPrice($tax, $id_product_attribute, $decimals, $divisor, $only_reduc, $usereduc, $quantity)
```





* Visibility: **public**
* Source: [classes/Product.php line 2868](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L2868)


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
* Source: [classes/Product.php line 2960](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L2960)


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
* Source: [classes/Product.php line 2156](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L2156)


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
* Source: [classes/Product.php line 5344](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5344)


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
* Source: [classes/Product.php line 4370](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4370)




### <a name="method-getRequiredCustomizableFieldsStatic"></a>getRequiredCustomizableFieldsStatic

```php
mixed ProductCore::getRequiredCustomizableFieldsStatic($id)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 4377](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4377)


#### Arguments
* $id **mixed**



### <a name="method-getShopsByProduct"></a>getShopsByProduct

```php
mixed ProductCore::getShopsByProduct($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 5468](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5468)


#### Arguments
* $id_product **mixed**



### <a name="method-getSimpleProducts"></a>getSimpleProducts

```php
mixed ProductCore::getSimpleProducts($id_lang, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 1117](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1117)


#### Arguments
* $id_lang **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getStockMvts"></a>getStockMvts

```php
mixed ProductCore::getStockMvts($id_lang)
```





* Visibility: **public**
* Source: [classes/Product.php line 4506](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4506)


#### Arguments
* $id_lang **mixed**



### <a name="method-getTags"></a>getTags

```php
mixed ProductCore::getTags($id_lang)
```





* Visibility: **public**
* Source: [classes/Product.php line 3826](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3826)


#### Arguments
* $id_lang **mixed**



### <a name="method-getTaxCalculationMethod"></a>getTaxCalculationMethod

```php
mixed ProductCore::getTaxCalculationMethod($id_customer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 565](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L565)


#### Arguments
* $id_customer **mixed**



### <a name="method-getTaxesInformations"></a>getTaxesInformations

```php
mixed ProductCore::getTaxesInformations($row, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3993](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3993)


#### Arguments
* $row **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getTaxesRate"></a>getTaxesRate

```php
\the ProductCore::getTaxesRate(\Address $address)
```





* Visibility: **public**
* Source: [classes/Product.php line 4574](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4574)


#### Arguments
* $address **[Address](class.AddressCore.md)**



### <a name="method-getType"></a>getType

```php
integer ProductCore::getType()
```

Get the product type (simple, virtual, pack)



* Visibility: **public**
* Source: [classes/Product.php line 5519](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5519)




### <a name="method-getUrlRewriteInformations"></a>getUrlRewriteInformations

```php
mixed ProductCore::getUrlRewriteInformations($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 4537](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4537)


#### Arguments
* $id_product **mixed**



### <a name="method-getWsAccessories"></a>getWsAccessories

```php
array ProductCore::getWsAccessories()
```

Webservice getter : get product accessories ids of current product for association



* Visibility: **public**
* Source: [classes/Product.php line 4732](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4732)




### <a name="method-getWsCategories"></a>getWsCategories

```php
array ProductCore::getWsCategories()
```

Webservice getter : get category ids of current product for association



* Visibility: **public**
* Source: [classes/Product.php line 4687](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4687)




### <a name="method-getWsCombinations"></a>getWsCombinations

```php
array ProductCore::getWsCombinations()
```

Webservice getter : get combination ids of current product for association



* Visibility: **public**
* Source: [classes/Product.php line 4764](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4764)




### <a name="method-getWsDefaultCombination"></a>getWsDefaultCombination

```php
integer ProductCore::getWsDefaultCombination()
```

Webservice getter : get virtual field default combination



* Visibility: **public**
* Source: [classes/Product.php line 4666](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4666)




### <a name="method-getWsImages"></a>getWsImages

```php
array ProductCore::getWsImages()
```

Webservice getter : get image ids of current product for association



* Visibility: **public**
* Source: [classes/Product.php line 4934](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4934)




### <a name="method-getWsManufacturerName"></a>getWsManufacturerName

```php
mixed ProductCore::getWsManufacturerName()
```





* Visibility: **public**
* Source: [classes/Product.php line 4998](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4998)




### <a name="method-getWsPositionInCategory"></a>getWsPositionInCategory

```php
integer ProductCore::getWsPositionInCategory()
```

Webservice getter : get virtual field position in category



* Visibility: **public**
* Source: [classes/Product.php line 4855](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4855)




### <a name="method-getWsProductBundle"></a>getWsProductBundle

```php
mixed ProductCore::getWsProductBundle()
```





* Visibility: **public**
* Source: [classes/Product.php line 5606](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5606)




### <a name="method-getWsProductFeatures"></a>getWsProductFeatures

```php
array ProductCore::getWsProductFeatures()
```

Webservice getter : get product features association



* Visibility: **public**
* Source: [classes/Product.php line 4590](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4590)




### <a name="method-getWsProductOptionValues"></a>getWsProductOptionValues

```php
array ProductCore::getWsProductOptionValues()
```

Webservice getter : get product option ids of current product for association



* Visibility: **public**
* Source: [classes/Product.php line 4840](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4840)




### <a name="method-getWsStockAvailables"></a>getWsStockAvailables

```php
mixed ProductCore::getWsStockAvailables()
```





* Visibility: **public**
* Source: [classes/Product.php line 4944](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4944)




### <a name="method-getWsTags"></a>getWsTags

```php
mixed ProductCore::getWsTags()
```





* Visibility: **public**
* Source: [classes/Product.php line 4951](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4951)




### <a name="method-getWsType"></a>getWsType

```php
mixed ProductCore::getWsType()
```





* Visibility: **public**
* Source: [classes/Product.php line 5580](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5580)




### <a name="method-hasAllRequiredCustomizableFields"></a>hasAllRequiredCustomizableFields

```php
mixed ProductCore::hasAllRequiredCustomizableFields(\Context $context)
```





* Visibility: **public**
* Source: [classes/Product.php line 4389](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4389)


#### Arguments
* $context **[Context](class.ContextCore.md)**



### <a name="method-hasAttributes"></a>hasAttributes

```php
integer ProductCore::hasAttributes()
```

Check if product has attributes combinations



* Visibility: **public**
* Source: [classes/Product.php line 2001](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L2001)




### <a name="method-hasAttributesInOtherShops"></a>hasAttributesInOtherShops

```php
mixed ProductCore::hasAttributesInOtherShops()
```





* Visibility: **public**
* Source: [classes/Product.php line 5531](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5531)




### <a name="method-idIsOnCategoryId"></a>idIsOnCategoryId

```php
boolean ProductCore::idIsOnCategoryId(integer $id_product, array $categories)
```

Checks if the product is in at least one of the submited categories



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 4419](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4419)


#### Arguments
* $id_product **integer**
* $categories **array** - array of category arrays



### <a name="method-initPricesComputation"></a>initPricesComputation

```php
mixed ProductCore::initPricesComputation($id_customer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 541](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L541)


#### Arguments
* $id_customer **mixed**



### <a name="method-isAvailableWhenOutOfStock"></a>isAvailableWhenOutOfStock

```php
mixed ProductCore::isAvailableWhenOutOfStock($out_of_stock)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3039](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3039)


#### Arguments
* $out_of_stock **mixed**



### <a name="method-isColorUnavailable"></a>isColorUnavailable

```php
mixed ProductCore::isColorUnavailable($id_attribute, $id_shop)
```





* Visibility: **public**
* Source: [classes/Product.php line 5646](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5646)


#### Arguments
* $id_attribute **mixed**
* $id_shop **mixed**



### <a name="method-isDiscounted"></a>isDiscounted

```php
mixed ProductCore::isDiscounted($id_product, $quantity, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2833](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L2833)


#### Arguments
* $id_product **mixed**
* $quantity **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-isNew"></a>isNew

```php
mixed ProductCore::isNew()
```





* Visibility: **public**
* Source: [classes/Product.php line 1136](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1136)




### <a name="method-loadStockData"></a>loadStockData

```php
mixed ProductCore::loadStockData()
```

Fill the variables used for stock management



* Visibility: **public**
* Source: [classes/Product.php line 5412](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5412)




### <a name="method-modifierWsLinkRewrite"></a>modifierWsLinkRewrite

```php
mixed ProductCore::modifierWsLinkRewrite()
```





* Visibility: **public**
* Source: [classes/Product.php line 5593](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5593)




### <a name="method-priceCalculation"></a>priceCalculation

```php
float ProductCore::priceCalculation(integer $id_shop, integer $id_product, integer $id_product_attribute, integer $id_country, integer $id_state, $zipcode, integer $id_currency, integer $id_group, integer $quantity, boolean $use_tax, integer $decimals, boolean $only_reduc, boolean $use_reduc, boolean $with_ecotax, $specific_price, $use_group_reduction, $id_customer, $use_customer_price, $id_cart, $real_quantity)
```

Price calculation / Get product price



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2648](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L2648)


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
* $real_quantity **mixed**



### <a name="method-productAttributeExists"></a>productAttributeExists

```php
mixed ProductCore::productAttributeExists($attributes_list, $current_product_attribute, \Context $context, $all_shops, $return_id)
```





* Visibility: **public**
* Source: [classes/Product.php line 1154](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1154)


#### Arguments
* $attributes_list **mixed**
* $current_product_attribute **mixed**
* $context **[Context](class.ContextCore.md)**
* $all_shops **mixed**
* $return_id **mixed**



### <a name="method-reinjectQuantities"></a>reinjectQuantities

```php
mixed ProductCore::reinjectQuantities()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3032](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3032)




### <a name="method-resetEcoTax"></a>resetEcoTax

```php
mixed ProductCore::resetEcoTax()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 5003](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5003)




### <a name="method-searchByName"></a>searchByName

```php
array ProductCore::searchByName(integer $id_lang, string $query, \Context $context)
```

Admin panel product search



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3411](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3411)


#### Arguments
* $id_lang **integer** - Language id
* $query **string** - Search query
* $context **[Context](class.ContextCore.md)**



### <a name="method-setAdvancedStockManagement"></a>setAdvancedStockManagement

```php
mixed ProductCore::setAdvancedStockManagement($value)
```





* Visibility: **public**
* Source: [classes/Product.php line 5434](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5434)


#### Arguments
* $value **mixed**



### <a name="method-setAvailableDate"></a>setAvailableDate

```php
mixed ProductCore::setAvailableDate($available_date)
```





* Visibility: **public**
* Source: [classes/Product.php line 702](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L702)


#### Arguments
* $available_date **mixed**



### <a name="method-setCarriers"></a>setCarriers

```php
mixed ProductCore::setCarriers($carrier_list)
```

Sets carriers assigned to the product



* Visibility: **public**
* Source: [classes/Product.php line 2419](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L2419)


#### Arguments
* $carrier_list **mixed**



### <a name="method-setCoverWs"></a>setCoverWs

```php
boolean ProductCore::setCoverWs($id_image)
```

Webservice setter : set virtual field id_default_image in category



* Visibility: **public**
* Source: [classes/Product.php line 4917](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4917)


#### Arguments
* $id_image **mixed**



### <a name="method-setDefaultAttribute"></a>setDefaultAttribute

```php
mixed ProductCore::setDefaultAttribute($id_product_attribute)
```





* Visibility: **public**
* Source: [classes/Product.php line 1330](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1330)


#### Arguments
* $id_product_attribute **mixed**



### <a name="method-setGroupReduction"></a>setGroupReduction

```php
mixed ProductCore::setGroupReduction()
```

Set Group reduction if needed



* Visibility: **public**
* Source: [classes/Product.php line 5013](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5013)




### <a name="method-setWsAccessories"></a>setWsAccessories

```php
mixed ProductCore::setWsAccessories($accessories)
```

Webservice setter : set product accessories ids of current product for association



* Visibility: **public**
* Source: [classes/Product.php line 4750](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4750)


#### Arguments
* $accessories **mixed** - product ids



### <a name="method-setWsCategories"></a>setWsCategories

```php
mixed ProductCore::setWsCategories($category_ids)
```

Webservice setter : set category ids of current product for association



* Visibility: **public**
* Source: [classes/Product.php line 4704](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4704)


#### Arguments
* $category_ids **mixed** - category ids



### <a name="method-setWsCombinations"></a>setWsCombinations

```php
mixed ProductCore::setWsCombinations($combinations)
```

Webservice setter : set combination ids of current product for association



* Visibility: **public**
* Source: [classes/Product.php line 4781](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4781)


#### Arguments
* $combinations **mixed** - combination ids



### <a name="method-setWsDefaultCombination"></a>setWsDefaultCombination

```php
mixed ProductCore::setWsDefaultCombination($id_combination)
```

Webservice setter : set virtual field default combination



* Visibility: **public**
* Source: [classes/Product.php line 4676](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4676)


#### Arguments
* $id_combination **mixed** - id default combination



### <a name="method-setWsPositionInCategory"></a>setWsPositionInCategory

```php
boolean ProductCore::setWsPositionInCategory($position)
```

Webservice setter : set virtual field position in category



* Visibility: **public**
* Source: [classes/Product.php line 4871](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4871)


#### Arguments
* $position **mixed**



### <a name="method-setWsProductBundle"></a>setWsProductBundle

```php
mixed ProductCore::setWsProductBundle($items)
```





* Visibility: **public**
* Source: [classes/Product.php line 5633](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5633)


#### Arguments
* $items **mixed**



### <a name="method-setWsProductFeatures"></a>setWsProductFeatures

```php
boolean ProductCore::setWsProductFeatures($product_features)
```

Webservice setter : set product features association



* Visibility: **public**
* Source: [classes/Product.php line 4615](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4615)


#### Arguments
* $product_features **mixed**



### <a name="method-setWsTags"></a>setWsTags

```php
mixed ProductCore::setWsTags($tag_ids)
```

Webservice setter : set tag ids of current product for association



* Visibility: **public**
* Source: [classes/Product.php line 4964](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4964)


#### Arguments
* $tag_ids **mixed** - tag ids



### <a name="method-setWsType"></a>setWsType

```php
mixed ProductCore::setWsType($type_str)
```





* Visibility: **public**
* Source: [classes/Product.php line 5611](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5611)


#### Arguments
* $type_str **mixed**



### <a name="method-sqlStock"></a>sqlStock

```php
string ProductCore::sqlStock($product_alias, $product_attribute, $inner_join, \Shop $shop)
```

Create JOIN query with 'stock_available' table



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 2981](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L2981)


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
* Source: [classes/Product.php line 777](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L777)




### <a name="method-update"></a>update

```php
mixed ProductCore::update($null_values)
```





* Visibility: **public**
* Source: [classes/Product.php line 529](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L529)


#### Arguments
* $null_values **mixed**



### <a name="method-updateAttribute"></a>updateAttribute

```php
array ProductCore::updateAttribute(integer $id_product_attribute, float $wholesale_price, float $price, float $weight, float $unit, float $ecotax, $id_images, string $reference, string $ean13, integer $default, $location, string $upc, string $minimal_quantity, $available_date, $update_all_fields, array $id_shop_list)
```

Update a product attribute



* Visibility: **public**
* Source: [classes/Product.php line 1436](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1436)


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
* Source: [classes/Product.php line 1606](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1606)


#### Arguments
* $id_product **mixed**



### <a name="method-updateCategories"></a>updateCategories

```php
array ProductCore::updateCategories($categories, boolean $keeping_current_pos)
```

Update categories to index product into



* Visibility: **public**
* Source: [classes/Product.php line 932](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L932)


#### Arguments
* $categories **mixed**
* $keeping_current_pos **boolean** - (deprecated, no more used)



### <a name="method-updateDefaultAttribute"></a>updateDefaultAttribute

```php
mixed ProductCore::updateDefaultAttribute($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 1343](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1343)


#### Arguments
* $id_product **mixed**



### <a name="method-updateIsVirtual"></a>updateIsVirtual

```php
mixed ProductCore::updateIsVirtual($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 751](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L751)


#### Arguments
* $id_product **mixed**



### <a name="method-updateLabels"></a>updateLabels

```php
mixed ProductCore::updateLabels()
```





* Visibility: **public**
* Source: [classes/Product.php line 4303](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L4303)




### <a name="method-updatePosition"></a>updatePosition

```php
mixed ProductCore::updatePosition(boolean $way, integer $position)
```

Move a product inside its category



* Visibility: **public**
* Source: [classes/Product.php line 579](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L579)


#### Arguments
* $way **boolean** - Up (1)  or Down (0)
* $position **integer** - return boolean Update result



### <a name="method-updateProductAttribute"></a>updateProductAttribute

```php
mixed ProductCore::updateProductAttribute($id_product_attribute, $wholesale_price, $price, $weight, $unit, $ecotax, $id_images, $reference, $id_supplier, $ean13, $default, $location, $upc, $minimal_quantity, $available_date)
```

Update a product attribute



* Visibility: **public**
* Source: [classes/Product.php line 1369](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1369)


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
mixed ProductCore::updateQuantity()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 3015](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L3015)




### <a name="method-updateQuantityProductWithAttributeQuantity"></a>updateQuantityProductWithAttributeQuantity

```php
mixed ProductCore::updateQuantityProductWithAttributeQuantity()
```





* Visibility: **public**
* Source: [classes/Product.php line 1548](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L1548)




### <a name="method-updateWs"></a>updateWs

```php
mixed ProductCore::updateWs($null_values)
```





* Visibility: **public**
* Source: [classes/Product.php line 5326](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5326)


#### Arguments
* $null_values **mixed**



### <a name="method-useAdvancedStockManagement"></a>useAdvancedStockManagement

```php
mixed ProductCore::useAdvancedStockManagement()
```





* Visibility: **public**
* Source: [classes/Product.php line 5425](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5425)




### <a name="method-usesAdvancedStockManagement"></a>usesAdvancedStockManagement

```php
boolean ProductCore::usesAdvancedStockManagement(integer $id_product)
```

For a given product, tells if it uses the advanced stock management



* Visibility: **public**
* This method is **static**.
* Source: [classes/Product.php line 5365](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L5365)


#### Arguments
* $id_product **integer**



### <a name="method-validateField"></a>validateField

```php
mixed ProductCore::validateField($field, $value, $id_lang, $skip, $human_errors)
```





* Visibility: **public**
* Source: [classes/Product.php line 761](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Product.php#L761)


#### Arguments
* $field **mixed**
* $value **mixed**
* $id_lang **mixed**
* $skip **mixed**
* $human_errors **mixed**


