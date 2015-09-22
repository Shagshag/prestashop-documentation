ProductCore
===============






* Class name: ProductCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/Product.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L36)



Constants
----------

* [CUSTOMIZE_FILE](#constant-CUSTOMIZE_FILE)
* [CUSTOMIZE_TEXTFIELD](#constant-CUSTOMIZE_TEXTFIELD)
* [PTYPE_SIMPLE](#constant-PTYPE_SIMPLE)
* [PTYPE_PACK](#constant-PTYPE_PACK)
* [PTYPE_VIRTUAL](#constant-PTYPE_VIRTUAL)

Properties
----------

* [$tax_name](#property-$tax_name)
* [$tax_rate](#property-$tax_rate)
* [$id_manufacturer](#property-$id_manufacturer)
* [$id_supplier](#property-$id_supplier)
* [$id_category_default](#property-$id_category_default)
* [$id_shop_default](#property-$id_shop_default)
* [$manufacturer_name](#property-$manufacturer_name)
* [$supplier_name](#property-$supplier_name)
* [$name](#property-$name)
* [$description](#property-$description)
* [$description_short](#property-$description_short)
* [$quantity](#property-$quantity)
* [$minimal_quantity](#property-$minimal_quantity)
* [$available_now](#property-$available_now)
* [$available_later](#property-$available_later)
* [$price](#property-$price)
* [$specificPrice](#property-$specificPrice)
* [$additional_shipping_cost](#property-$additional_shipping_cost)
* [$wholesale_price](#property-$wholesale_price)
* [$on_sale](#property-$on_sale)
* [$online_only](#property-$online_only)
* [$unity](#property-$unity)
* [$unit_price](#property-$unit_price)
* [$unit_price_ratio](#property-$unit_price_ratio)
* [$ecotax](#property-$ecotax)
* [$reference](#property-$reference)
* [$supplier_reference](#property-$supplier_reference)
* [$location](#property-$location)
* [$width](#property-$width)
* [$height](#property-$height)
* [$depth](#property-$depth)
* [$weight](#property-$weight)
* [$ean13](#property-$ean13)
* [$upc](#property-$upc)
* [$link_rewrite](#property-$link_rewrite)
* [$meta_description](#property-$meta_description)
* [$meta_keywords](#property-$meta_keywords)
* [$meta_title](#property-$meta_title)
* [$quantity_discount](#property-$quantity_discount)
* [$customizable](#property-$customizable)
* [$new](#property-$new)
* [$uploadable_files](#property-$uploadable_files)
* [$text_fields](#property-$text_fields)
* [$active](#property-$active)
* [$redirect_type](#property-$redirect_type)
* [$id_product_redirected](#property-$id_product_redirected)
* [$available_for_order](#property-$available_for_order)
* [$available_date](#property-$available_date)
* [$condition](#property-$condition)
* [$show_price](#property-$show_price)
* [$indexed](#property-$indexed)
* [$visibility](#property-$visibility)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$tags](#property-$tags)
* [$base_price](#property-$base_price)
* [$id_tax_rules_group](#property-$id_tax_rules_group)
* [$id_color_default](#property-$id_color_default)
* [$advanced_stock_management](#property-$advanced_stock_management)
* [$out_of_stock](#property-$out_of_stock)
* [$depends_on_stock](#property-$depends_on_stock)
* [$isFullyLoaded](#property-$isFullyLoaded)
* [$cache_is_pack](#property-$cache_is_pack)
* [$cache_has_attachments](#property-$cache_has_attachments)
* [$is_virtual](#property-$is_virtual)
* [$id_pack_product_attribute](#property-$id_pack_product_attribute)
* [$cache_default_attribute](#property-$cache_default_attribute)
* [$category](#property-$category)
* [$pack_stock_type](#property-$pack_stock_type)
* [$_taxCalculationMethod](#property-$_taxCalculationMethod)
* [$_prices](#property-$_prices)
* [$_pricesLevel2](#property-$_pricesLevel2)
* [$_incat](#property-$_incat)
* [$_cart_quantity](#property-$_cart_quantity)
* [$_tax_rules_group](#property-$_tax_rules_group)
* [$_cacheFeatures](#property-$_cacheFeatures)
* [$_frontFeaturesCache](#property-$_frontFeaturesCache)
* [$producPropertiesCache](#property-$producPropertiesCache)
* [$cacheStock](#property-$cacheStock)
* [$definition](#property-$definition)
* [$webserviceParameters](#property-$webserviceParameters)

Methods
-------
* [__construct](#method-__construct)
* [getFieldsShop](#method-getFieldsShop)
* [add](#method-add)
* [update](#method-update)
* [initPricesComputation](#method-initPricesComputation)
* [getTaxCalculationMethod](#method-getTaxCalculationMethod)
* [updatePosition](#method-updatePosition)
* [cleanPositions](#method-cleanPositions)
* [getDefaultAttribute](#method-getDefaultAttribute)
* [setAvailableDate](#method-setAvailableDate)
* [getAvailableDate](#method-getAvailableDate)
* [updateIsVirtual](#method-updateIsVirtual)
* [validateField](#method-validateField)
* [toggleStatus](#method-toggleStatus)
* [delete](#method-delete)
* [deleteSelection](#method-deleteSelection)
* [deleteFromCartRules](#method-deleteFromCartRules)
* [deleteFromSupplier](#method-deleteFromSupplier)
* [addToCategories](#method-addToCategories)
* [updateCategories](#method-updateCategories)
* [deleteCategory](#method-deleteCategory)
* [deleteCategories](#method-deleteCategories)
* [deleteTags](#method-deleteTags)
* [deleteCartProducts](#method-deleteCartProducts)
* [deleteImages](#method-deleteImages)
* [getProductAttributePrice](#method-getProductAttributePrice)
* [getProducts](#method-getProducts)
* [getSimpleProducts](#method-getSimpleProducts)
* [isNew](#method-isNew)
* [productAttributeExists](#method-productAttributeExists)
* [addProductAttribute](#method-addProductAttribute)
* [generateMultipleCombinations](#method-generateMultipleCombinations)
* [addCombinationEntity](#method-addCombinationEntity)
* [addProductAttributeMultiple](#method-addProductAttributeMultiple)
* [deleteDefaultAttributes](#method-deleteDefaultAttributes)
* [setDefaultAttribute](#method-setDefaultAttribute)
* [updateDefaultAttribute](#method-updateDefaultAttribute)
* [updateProductAttribute](#method-updateProductAttribute)
* [addSupplierReference](#method-addSupplierReference)
* [updateAttribute](#method-updateAttribute)
* [addAttribute](#method-addAttribute)
* [updateQuantityProductWithAttributeQuantity](#method-updateQuantityProductWithAttributeQuantity)
* [deleteProductAttributes](#method-deleteProductAttributes)
* [deleteAttributesImpacts](#method-deleteAttributesImpacts)
* [deleteProductFeatures](#method-deleteProductFeatures)
* [updateCacheAttachment](#method-updateCacheAttachment)
* [deleteAttachments](#method-deleteAttachments)
* [deleteCustomization](#method-deleteCustomization)
* [deletePack](#method-deletePack)
* [deleteProductSale](#method-deleteProductSale)
* [deleteSceneProducts](#method-deleteSceneProducts)
* [deleteSearchIndexes](#method-deleteSearchIndexes)
* [addAttributeCombinaison](#method-addAttributeCombinaison)
* [addAttributeCombinationMultiple](#method-addAttributeCombinationMultiple)
* [deleteAttributeCombination](#method-deleteAttributeCombination)
* [deleteFeatures](#method-deleteFeatures)
* [getAttributesResume](#method-getAttributesResume)
* [getAttributeCombinations](#method-getAttributeCombinations)
* [getAttributeCombinationsById](#method-getAttributeCombinationsById)
* [getCombinationImages](#method-getCombinationImages)
* [getCombinationImageById](#method-getCombinationImageById)
* [hasAttributes](#method-hasAttributes)
* [getNewProducts](#method-getNewProducts)
* [_getProductIdByDate](#method-_getProductIdByDate)
* [getRandomSpecial](#method-getRandomSpecial)
* [getPricesDrop](#method-getPricesDrop)
* [getProductCategories](#method-getProductCategories)
* [getProductCategoriesFull](#method-getProductCategoriesFull)
* [getCategories](#method-getCategories)
* [getCarriers](#method-getCarriers)
* [setCarriers](#method-setCarriers)
* [getImages](#method-getImages)
* [getCover](#method-getCover)
* [getPriceStatic](#method-getPriceStatic)
* [priceCalculation](#method-priceCalculation)
* [convertAndFormatPrice](#method-convertAndFormatPrice)
* [isDiscounted](#method-isDiscounted)
* [getPrice](#method-getPrice)
* [getPublicPrice](#method-getPublicPrice)
* [getIdProductAttributeMostExpensive](#method-getIdProductAttributeMostExpensive)
* [getDefaultIdProductAttribute](#method-getDefaultIdProductAttribute)
* [getPriceWithoutReduct](#method-getPriceWithoutReduct)
* [convertPrice](#method-convertPrice)
* [convertPriceWithCurrency](#method-convertPriceWithCurrency)
* [displayWtPrice](#method-displayWtPrice)
* [displayWtPriceWithCurrency](#method-displayWtPriceWithCurrency)
* [getQuantity](#method-getQuantity)
* [sqlStock](#method-sqlStock)
* [updateQuantity](#method-updateQuantity)
* [reinjectQuantities](#method-reinjectQuantities)
* [isAvailableWhenOutOfStock](#method-isAvailableWhenOutOfStock)
* [checkQty](#method-checkQty)
* [checkDefaultAttributes](#method-checkDefaultAttributes)
* [getAttributesColorList](#method-getAttributesColorList)
* [getAttributesGroups](#method-getAttributesGroups)
* [deleteAccessories](#method-deleteAccessories)
* [deleteFromAccessories](#method-deleteFromAccessories)
* [getAccessoriesLight](#method-getAccessoriesLight)
* [getAccessories](#method-getAccessories)
* [getAccessoryById](#method-getAccessoryById)
* [changeAccessories](#method-changeAccessories)
* [addFeaturesCustomToDB](#method-addFeaturesCustomToDB)
* [addFeaturesToDB](#method-addFeaturesToDB)
* [addFeatureProductImport](#method-addFeatureProductImport)
* [getFeatures](#method-getFeatures)
* [getFeaturesStatic](#method-getFeaturesStatic)
* [cacheProductsFeatures](#method-cacheProductsFeatures)
* [cacheFrontFeatures](#method-cacheFrontFeatures)
* [searchByName](#method-searchByName)
* [duplicateAttributes](#method-duplicateAttributes)
* [getAttributesImpacts](#method-getAttributesImpacts)
* [_getAttributeImageAssociations](#method-_getAttributeImageAssociations)
* [duplicateAccessories](#method-duplicateAccessories)
* [duplicateTags](#method-duplicateTags)
* [duplicateDownload](#method-duplicateDownload)
* [duplicateAttachments](#method-duplicateAttachments)
* [duplicateFeatures](#method-duplicateFeatures)
* [_getCustomizationFieldsNLabels](#method-_getCustomizationFieldsNLabels)
* [duplicateSpecificPrices](#method-duplicateSpecificPrices)
* [duplicateCustomizationFields](#method-duplicateCustomizationFields)
* [duplicateSuppliers](#method-duplicateSuppliers)
* [getLink](#method-getLink)
* [getTags](#method-getTags)
* [defineProductImage](#method-defineProductImage)
* [getProductProperties](#method-getProductProperties)
* [getTaxesInformations](#method-getTaxesInformations)
* [getProductsProperties](#method-getProductsProperties)
* [getFrontFeaturesStatic](#method-getFrontFeaturesStatic)
* [getFrontFeatures](#method-getFrontFeatures)
* [getAttachmentsStatic](#method-getAttachmentsStatic)
* [getAttachments](#method-getAttachments)
* [getAllCustomizedDatas](#method-getAllCustomizedDatas)
* [addCustomizationPrice](#method-addCustomizationPrice)
* [_checkLabelField](#method-_checkLabelField)
* [_deleteOldLabels](#method-_deleteOldLabels)
* [_createLabel](#method-_createLabel)
* [createLabels](#method-createLabels)
* [updateLabels](#method-updateLabels)
* [getCustomizationFields](#method-getCustomizationFields)
* [getCustomizationFieldIds](#method-getCustomizationFieldIds)
* [getRequiredCustomizableFields](#method-getRequiredCustomizableFields)
* [getRequiredCustomizableFieldsStatic](#method-getRequiredCustomizableFieldsStatic)
* [hasAllRequiredCustomizableFields](#method-hasAllRequiredCustomizableFields)
* [idIsOnCategoryId](#method-idIsOnCategoryId)
* [getNoPackPrice](#method-getNoPackPrice)
* [checkAccess](#method-checkAccess)
* [checkAccessStatic](#method-checkAccessStatic)
* [addStockMvt](#method-addStockMvt)
* [getStockMvts](#method-getStockMvts)
* [getUrlRewriteInformations](#method-getUrlRewriteInformations)
* [getIdTaxRulesGroup](#method-getIdTaxRulesGroup)
* [getIdTaxRulesGroupByIdProduct](#method-getIdTaxRulesGroupByIdProduct)
* [getTaxesRate](#method-getTaxesRate)
* [getWsProductFeatures](#method-getWsProductFeatures)
* [setWsProductFeatures](#method-setWsProductFeatures)
* [getWsDefaultCombination](#method-getWsDefaultCombination)
* [setWsDefaultCombination](#method-setWsDefaultCombination)
* [getWsCategories](#method-getWsCategories)
* [setWsCategories](#method-setWsCategories)
* [getWsAccessories](#method-getWsAccessories)
* [setWsAccessories](#method-setWsAccessories)
* [getWsCombinations](#method-getWsCombinations)
* [setWsCombinations](#method-setWsCombinations)
* [getWsProductOptionValues](#method-getWsProductOptionValues)
* [getWsPositionInCategory](#method-getWsPositionInCategory)
* [setWsPositionInCategory](#method-setWsPositionInCategory)
* [getCoverWs](#method-getCoverWs)
* [setCoverWs](#method-setCoverWs)
* [getWsImages](#method-getWsImages)
* [getWsStockAvailables](#method-getWsStockAvailables)
* [getWsTags](#method-getWsTags)
* [setWsTags](#method-setWsTags)
* [deleteWsTags](#method-deleteWsTags)
* [getWsManufacturerName](#method-getWsManufacturerName)
* [resetEcoTax](#method-resetEcoTax)
* [setGroupReduction](#method-setGroupReduction)
* [existsRefInDatabase](#method-existsRefInDatabase)
* [getProductAttributesIds](#method-getProductAttributesIds)
* [getAttributesParams](#method-getAttributesParams)
* [getAttributesInformationsByProduct](#method-getAttributesInformationsByProduct)
* [getAnchor](#method-getAnchor)
* [getProductName](#method-getProductName)
* [addWs](#method-addWs)
* [updateWs](#method-updateWs)
* [getRealQuantity](#method-getRealQuantity)
* [usesAdvancedStockManagement](#method-usesAdvancedStockManagement)
* [flushPriceCache](#method-flushPriceCache)
* [getParentCategories](#method-getParentCategories)
* [loadStockData](#method-loadStockData)
* [useAdvancedStockManagement](#method-useAdvancedStockManagement)
* [setAdvancedStockManagement](#method-setAdvancedStockManagement)
* [getDefaultCategory](#method-getDefaultCategory)
* [getShopsByProduct](#method-getShopsByProduct)
* [deleteDownload](#method-deleteDownload)
* [getAttributeCombinaisons](#method-getAttributeCombinaisons)
* [deleteAttributeCombinaison](#method-deleteAttributeCombinaison)
* [getType](#method-getType)
* [hasAttributesInOtherShops](#method-hasAttributesInOtherShops)
* [getIdTaxRulesGroupMostUsed](#method-getIdTaxRulesGroupMostUsed)
* [getIdByEan13](#method-getIdByEan13)
* [getWsType](#method-getWsType)
* [modifierWsLinkRewrite](#method-modifierWsLinkRewrite)
* [getWsProductBundle](#method-getWsProductBundle)
* [setWsType](#method-setWsType)
* [setWsProductBundle](#method-setWsProductBundle)
* [isColorUnavailable](#method-isColorUnavailable)
* [getColorsListCacheId](#method-getColorsListCacheId)
* [setPackStockType](#method-setPackStockType)


Constants
----------


### <a name="constant-CUSTOMIZE_FILE"></a>CUSTOMIZE_FILE

    const CUSTOMIZE_FILE = 0



* This constant is defined in [classes/Product.php line 465](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L465)


### <a name="constant-CUSTOMIZE_TEXTFIELD"></a>CUSTOMIZE_TEXTFIELD

    const CUSTOMIZE_TEXTFIELD = 1



* This constant is defined in [classes/Product.php line 466](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L466)


### <a name="constant-PTYPE_SIMPLE"></a>PTYPE_SIMPLE

    const PTYPE_SIMPLE = 0



* This constant is defined in [classes/Product.php line 471](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L471)


### <a name="constant-PTYPE_PACK"></a>PTYPE_PACK

    const PTYPE_PACK = 1



* This constant is defined in [classes/Product.php line 472](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L472)


### <a name="constant-PTYPE_VIRTUAL"></a>PTYPE_VIRTUAL

    const PTYPE_VIRTUAL = 2



* This constant is defined in [classes/Product.php line 473](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L473)


Properties
----------


### <a name="property-$tax_name"></a>$tax_name

    public string $tax_name





* Visibility: **public**
* This property is defined in [classes/Product.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L39)


### <a name="property-$tax_rate"></a>$tax_rate

    public string $tax_rate





* Visibility: **public**
* This property is defined in [classes/Product.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L42)


### <a name="property-$id_manufacturer"></a>$id_manufacturer

    public integer $id_manufacturer





* Visibility: **public**
* This property is defined in [classes/Product.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L45)


### <a name="property-$id_supplier"></a>$id_supplier

    public integer $id_supplier





* Visibility: **public**
* This property is defined in [classes/Product.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L48)


### <a name="property-$id_category_default"></a>$id_category_default

    public integer $id_category_default





* Visibility: **public**
* This property is defined in [classes/Product.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L51)


### <a name="property-$id_shop_default"></a>$id_shop_default

    public integer $id_shop_default





* Visibility: **public**
* This property is defined in [classes/Product.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L54)


### <a name="property-$manufacturer_name"></a>$manufacturer_name

    public string $manufacturer_name





* Visibility: **public**
* This property is defined in [classes/Product.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L57)


### <a name="property-$supplier_name"></a>$supplier_name

    public string $supplier_name





* Visibility: **public**
* This property is defined in [classes/Product.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L60)


### <a name="property-$name"></a>$name

    public string $name





* Visibility: **public**
* This property is defined in [classes/Product.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L63)


### <a name="property-$description"></a>$description

    public string $description





* Visibility: **public**
* This property is defined in [classes/Product.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L66)


### <a name="property-$description_short"></a>$description_short

    public string $description_short





* Visibility: **public**
* This property is defined in [classes/Product.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L69)


### <a name="property-$quantity"></a>$quantity

    public integer $quantity





* Visibility: **public**
* This property is defined in [classes/Product.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L72)


### <a name="property-$minimal_quantity"></a>$minimal_quantity

    public integer $minimal_quantity = 1





* Visibility: **public**
* This property is defined in [classes/Product.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L75)


### <a name="property-$available_now"></a>$available_now

    public string $available_now





* Visibility: **public**
* This property is defined in [classes/Product.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L78)


### <a name="property-$available_later"></a>$available_later

    public string $available_later





* Visibility: **public**
* This property is defined in [classes/Product.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L81)


### <a name="property-$price"></a>$price

    public float $price





* Visibility: **public**
* This property is defined in [classes/Product.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L84)


### <a name="property-$specificPrice"></a>$specificPrice

    public mixed $specificPrice





* Visibility: **public**
* This property is defined in [classes/Product.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L86)


### <a name="property-$additional_shipping_cost"></a>$additional_shipping_cost

    public float $additional_shipping_cost





* Visibility: **public**
* This property is defined in [classes/Product.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L89)


### <a name="property-$wholesale_price"></a>$wholesale_price

    public float $wholesale_price





* Visibility: **public**
* This property is defined in [classes/Product.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L92)


### <a name="property-$on_sale"></a>$on_sale

    public boolean $on_sale = false





* Visibility: **public**
* This property is defined in [classes/Product.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L95)


### <a name="property-$online_only"></a>$online_only

    public boolean $online_only = false





* Visibility: **public**
* This property is defined in [classes/Product.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L98)


### <a name="property-$unity"></a>$unity

    public string $unity = null





* Visibility: **public**
* This property is defined in [classes/Product.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L101)


### <a name="property-$unit_price"></a>$unit_price

    public float $unit_price





* Visibility: **public**
* This property is defined in [classes/Product.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L104)


### <a name="property-$unit_price_ratio"></a>$unit_price_ratio

    public float $unit_price_ratio





* Visibility: **public**
* This property is defined in [classes/Product.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L107)


### <a name="property-$ecotax"></a>$ecotax

    public float $ecotax





* Visibility: **public**
* This property is defined in [classes/Product.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L110)


### <a name="property-$reference"></a>$reference

    public string $reference





* Visibility: **public**
* This property is defined in [classes/Product.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L113)


### <a name="property-$supplier_reference"></a>$supplier_reference

    public string $supplier_reference





* Visibility: **public**
* This property is defined in [classes/Product.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L116)


### <a name="property-$location"></a>$location

    public string $location





* Visibility: **public**
* This property is defined in [classes/Product.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L119)


### <a name="property-$width"></a>$width

    public string $width





* Visibility: **public**
* This property is defined in [classes/Product.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L122)


### <a name="property-$height"></a>$height

    public string $height





* Visibility: **public**
* This property is defined in [classes/Product.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L125)


### <a name="property-$depth"></a>$depth

    public string $depth





* Visibility: **public**
* This property is defined in [classes/Product.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L128)


### <a name="property-$weight"></a>$weight

    public string $weight





* Visibility: **public**
* This property is defined in [classes/Product.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L131)


### <a name="property-$ean13"></a>$ean13

    public string $ean13





* Visibility: **public**
* This property is defined in [classes/Product.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L134)


### <a name="property-$upc"></a>$upc

    public string $upc





* Visibility: **public**
* This property is defined in [classes/Product.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L137)


### <a name="property-$link_rewrite"></a>$link_rewrite

    public string $link_rewrite





* Visibility: **public**
* This property is defined in [classes/Product.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L140)


### <a name="property-$meta_description"></a>$meta_description

    public string $meta_description





* Visibility: **public**
* This property is defined in [classes/Product.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L143)


### <a name="property-$meta_keywords"></a>$meta_keywords

    public string $meta_keywords





* Visibility: **public**
* This property is defined in [classes/Product.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L146)


### <a name="property-$meta_title"></a>$meta_title

    public string $meta_title





* Visibility: **public**
* This property is defined in [classes/Product.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L149)


### <a name="property-$quantity_discount"></a>$quantity_discount

    public boolean $quantity_discount





* Visibility: **public**
* This property is defined in [classes/Product.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L152)


### <a name="property-$customizable"></a>$customizable

    public boolean $customizable





* Visibility: **public**
* This property is defined in [classes/Product.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L155)


### <a name="property-$new"></a>$new

    public boolean $new = null





* Visibility: **public**
* This property is defined in [classes/Product.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L158)


### <a name="property-$uploadable_files"></a>$uploadable_files

    public integer $uploadable_files





* Visibility: **public**
* This property is defined in [classes/Product.php line 161](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L161)


### <a name="property-$text_fields"></a>$text_fields

    public integer $text_fields





* Visibility: **public**
* This property is defined in [classes/Product.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L164)


### <a name="property-$active"></a>$active

    public boolean $active = true





* Visibility: **public**
* This property is defined in [classes/Product.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L167)


### <a name="property-$redirect_type"></a>$redirect_type

    public boolean $redirect_type = ''





* Visibility: **public**
* This property is defined in [classes/Product.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L170)


### <a name="property-$id_product_redirected"></a>$id_product_redirected

    public boolean $id_product_redirected





* Visibility: **public**
* This property is defined in [classes/Product.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L173)


### <a name="property-$available_for_order"></a>$available_for_order

    public boolean $available_for_order = true





* Visibility: **public**
* This property is defined in [classes/Product.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L176)


### <a name="property-$available_date"></a>$available_date

    public string $available_date = '0000-00-00'





* Visibility: **public**
* This property is defined in [classes/Product.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L179)


### <a name="property-$condition"></a>$condition

    public string $condition





* Visibility: **public**
* This property is defined in [classes/Product.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L182)


### <a name="property-$show_price"></a>$show_price

    public boolean $show_price = true





* Visibility: **public**
* This property is defined in [classes/Product.php line 185](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L185)


### <a name="property-$indexed"></a>$indexed

    public boolean $indexed





* Visibility: **public**
* This property is defined in [classes/Product.php line 188](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L188)


### <a name="property-$visibility"></a>$visibility

    public string $visibility





* Visibility: **public**
* This property is defined in [classes/Product.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L191)


### <a name="property-$date_add"></a>$date_add

    public string $date_add





* Visibility: **public**
* This property is defined in [classes/Product.php line 194](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L194)


### <a name="property-$date_upd"></a>$date_upd

    public string $date_upd





* Visibility: **public**
* This property is defined in [classes/Product.php line 197](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L197)


### <a name="property-$tags"></a>$tags

    public mixed $tags





* Visibility: **public**
* This property is defined in [classes/Product.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L200)


### <a name="property-$base_price"></a>$base_price

    public float $base_price





* Visibility: **public**
* This property is defined in [classes/Product.php line 206](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L206)


### <a name="property-$id_tax_rules_group"></a>$id_tax_rules_group

    public mixed $id_tax_rules_group = 1





* Visibility: **public**
* This property is defined in [classes/Product.php line 208](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L208)


### <a name="property-$id_color_default"></a>$id_color_default

    public mixed $id_color_default

We keep this variable for retrocompatibility for themes



* Visibility: **public**
* This property is defined in [classes/Product.php line 214](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L214)


### <a name="property-$advanced_stock_management"></a>$advanced_stock_management

    public boolean $advanced_stock_management





* Visibility: **public**
* This property is defined in [classes/Product.php line 220](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L220)


### <a name="property-$out_of_stock"></a>$out_of_stock

    public mixed $out_of_stock





* Visibility: **public**
* This property is defined in [classes/Product.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L221)


### <a name="property-$depends_on_stock"></a>$depends_on_stock

    public mixed $depends_on_stock





* Visibility: **public**
* This property is defined in [classes/Product.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L222)


### <a name="property-$isFullyLoaded"></a>$isFullyLoaded

    public mixed $isFullyLoaded = false





* Visibility: **public**
* This property is defined in [classes/Product.php line 224](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L224)


### <a name="property-$cache_is_pack"></a>$cache_is_pack

    public mixed $cache_is_pack





* Visibility: **public**
* This property is defined in [classes/Product.php line 226](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L226)


### <a name="property-$cache_has_attachments"></a>$cache_has_attachments

    public mixed $cache_has_attachments





* Visibility: **public**
* This property is defined in [classes/Product.php line 227](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L227)


### <a name="property-$is_virtual"></a>$is_virtual

    public mixed $is_virtual





* Visibility: **public**
* This property is defined in [classes/Product.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L228)


### <a name="property-$id_pack_product_attribute"></a>$id_pack_product_attribute

    public mixed $id_pack_product_attribute





* Visibility: **public**
* This property is defined in [classes/Product.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L229)


### <a name="property-$cache_default_attribute"></a>$cache_default_attribute

    public mixed $cache_default_attribute





* Visibility: **public**
* This property is defined in [classes/Product.php line 230](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L230)


### <a name="property-$category"></a>$category

    public string $category





* Visibility: **public**
* This property is defined in [classes/Product.php line 235](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L235)


### <a name="property-$pack_stock_type"></a>$pack_stock_type

    public integer $pack_stock_type = 3





* Visibility: **public**
* This property is defined in [classes/Product.php line 240](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L240)


### <a name="property-$_taxCalculationMethod"></a>$_taxCalculationMethod

    public mixed $_taxCalculationMethod = null





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Product.php line 242](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L242)


### <a name="property-$_prices"></a>$_prices

    protected mixed $_prices = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Product.php line 243](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L243)


### <a name="property-$_pricesLevel2"></a>$_pricesLevel2

    protected mixed $_pricesLevel2 = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Product.php line 244](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L244)


### <a name="property-$_incat"></a>$_incat

    protected mixed $_incat = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Product.php line 245](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L245)


### <a name="property-$_cart_quantity"></a>$_cart_quantity

    protected array $_cart_quantity = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Product.php line 251](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L251)


### <a name="property-$_tax_rules_group"></a>$_tax_rules_group

    protected mixed $_tax_rules_group = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Product.php line 253](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L253)


### <a name="property-$_cacheFeatures"></a>$_cacheFeatures

    protected mixed $_cacheFeatures = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Product.php line 254](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L254)


### <a name="property-$_frontFeaturesCache"></a>$_frontFeaturesCache

    protected mixed $_frontFeaturesCache = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Product.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L255)


### <a name="property-$producPropertiesCache"></a>$producPropertiesCache

    protected mixed $producPropertiesCache = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Product.php line 256](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L256)


### <a name="property-$cacheStock"></a>$cacheStock

    protected array $cacheStock = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Product.php line 259](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L259)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'product', 'primary' => 'id_product', 'multilang' => true, 'multilang_shop' => true, 'fields' => array('id_shop_default' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_manufacturer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_supplier' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'reference' => array('type' => self::TYPE_STRING, 'validate' => 'isReference', 'size' => 32), 'supplier_reference' => array('type' => self::TYPE_STRING, 'validate' => 'isReference', 'size' => 32), 'location' => array('type' => self::TYPE_STRING, 'validate' => 'isReference', 'size' => 64), 'width' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat'), 'height' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat'), 'depth' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat'), 'weight' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat'), 'quantity_discount' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'ean13' => array('type' => self::TYPE_STRING, 'validate' => 'isEan13', 'size' => 13), 'upc' => array('type' => self::TYPE_STRING, 'validate' => 'isUpc', 'size' => 12), 'cache_is_pack' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'cache_has_attachments' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'is_virtual' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'id_category_default' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedId'), 'id_tax_rules_group' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedId'), 'on_sale' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'online_only' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'ecotax' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isPrice'), 'minimal_quantity' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedInt'), 'price' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isPrice', 'required' => true), 'wholesale_price' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isPrice'), 'unity' => array('type' => self::TYPE_STRING, 'shop' => true, 'validate' => 'isString'), 'unit_price_ratio' => array('type' => self::TYPE_FLOAT, 'shop' => true), 'additional_shipping_cost' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isPrice'), 'customizable' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedInt'), 'text_fields' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedInt'), 'uploadable_files' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedInt'), 'active' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'redirect_type' => array('type' => self::TYPE_STRING, 'shop' => true, 'validate' => 'isString'), 'id_product_redirected' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedId'), 'available_for_order' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'available_date' => array('type' => self::TYPE_DATE, 'shop' => true, 'validate' => 'isDateFormat'), 'condition' => array('type' => self::TYPE_STRING, 'shop' => true, 'validate' => 'isGenericName', 'values' => array('new', 'used', 'refurbished'), 'default' => 'new'), 'show_price' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'indexed' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'visibility' => array('type' => self::TYPE_STRING, 'shop' => true, 'validate' => 'isProductVisibility', 'values' => array('both', 'catalog', 'search', 'none'), 'default' => 'both'), 'cache_default_attribute' => array('type' => self::TYPE_INT, 'shop' => true), 'advanced_stock_management' => array('type' => self::TYPE_BOOL, 'shop' => true, 'validate' => 'isBool'), 'date_add' => array('type' => self::TYPE_DATE, 'shop' => true, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'shop' => true, 'validate' => 'isDate'), 'pack_stock_type' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedInt'), 'meta_description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_keywords' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_title' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 128), 'link_rewrite' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isLinkRewrite', 'required' => true, 'size' => 128, 'ws_modifier' => array('http_method' => \WebserviceRequest::HTTP_POST, 'modifier' => 'modifierWsLinkRewrite')), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isCatalogName', 'required' => true, 'size' => 128), 'description' => array('type' => self::TYPE_HTML, 'lang' => true, 'validate' => 'isCleanHtml'), 'description_short' => array('type' => self::TYPE_HTML, 'lang' => true, 'validate' => 'isCleanHtml'), 'available_now' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'available_later' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'IsGenericName', 'size' => 255)), 'associations' => array('manufacturer' => array('type' => self::HAS_ONE), 'supplier' => array('type' => self::HAS_ONE), 'default_category' => array('type' => self::HAS_ONE, 'field' => 'id_category_default', 'object' => 'Category'), 'tax_rules_group' => array('type' => self::HAS_ONE), 'categories' => array('type' => self::HAS_MANY, 'field' => 'id_category', 'object' => 'Category', 'association' => 'category_product'), 'stock_availables' => array('type' => self::HAS_MANY, 'field' => 'id_stock_available', 'object' => 'StockAvailable', 'association' => 'stock_availables')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Product.php line 261](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L261)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('objectMethods' => array('add' => 'addWs', 'update' => 'updateWs'), 'objectNodeNames' => 'products', 'fields' => array('id_manufacturer' => array('xlink_resource' => 'manufacturers'), 'id_supplier' => array('xlink_resource' => 'suppliers'), 'id_category_default' => array('xlink_resource' => 'categories'), 'new' => array(), 'cache_default_attribute' => array(), 'id_default_image' => array('getter' => 'getCoverWs', 'setter' => 'setCoverWs', 'xlink_resource' => array('resourceName' => 'images', 'subResourceName' => 'products')), 'id_default_combination' => array('getter' => 'getWsDefaultCombination', 'setter' => 'setWsDefaultCombination', 'xlink_resource' => array('resourceName' => 'combinations')), 'id_tax_rules_group' => array('xlink_resource' => array('resourceName' => 'tax_rule_groups')), 'position_in_category' => array('getter' => 'getWsPositionInCategory', 'setter' => 'setWsPositionInCategory'), 'manufacturer_name' => array('getter' => 'getWsManufacturerName', 'setter' => false), 'quantity' => array('getter' => false, 'setter' => false), 'type' => array('getter' => 'getWsType', 'setter' => 'setWsType')), 'associations' => array('categories' => array('resource' => 'category', 'fields' => array('id' => array('required' => true))), 'images' => array('resource' => 'image', 'fields' => array('id' => array())), 'combinations' => array('resource' => 'combination', 'fields' => array('id' => array('required' => true))), 'product_option_values' => array('resource' => 'product_option_value', 'fields' => array('id' => array('required' => true))), 'product_features' => array('resource' => 'product_feature', 'fields' => array('id' => array('required' => true), 'id_feature_value' => array('required' => true, 'xlink_resource' => 'product_feature_values'))), 'tags' => array('resource' => 'tag', 'fields' => array('id' => array('required' => true))), 'stock_availables' => array('resource' => 'stock_available', 'fields' => array('id' => array('required' => true), 'id_product_attribute' => array('required' => true)), 'setter' => false), 'accessories' => array('resource' => 'product', 'api' => 'products', 'fields' => array('id' => array('required' => true, 'xlink_resource' => 'product'))), 'product_bundle' => array('resource' => 'product', 'api' => 'products', 'fields' => array('id' => array('required' => true), 'quantity' => array()))))





* Visibility: **protected**
* This property is defined in [classes/Product.php line 346](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L346)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed ProductCore::__construct($id_product, $full, $id_lang, $id_shop, \Context $context)





* Visibility: **public**
* This method is defined in [classes/Product.php line 475](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L475)


#### Arguments
* $id_product **mixed**
* $full **mixed**
* $id_lang **mixed**
* $id_shop **mixed**
* $context **[Context](ContextCore)**



### <a name="method-getFieldsShop"></a>getFieldsShop

    array ProductCore::getFieldsShop()





* Visibility: **public**
* This method is defined in [classes/Product.php line 517](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L517)




### <a name="method-add"></a>add

    mixed ProductCore::add($autodate, $null_values)





* Visibility: **public**
* This method is defined in [classes/Product.php line 528](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L528)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-update"></a>update

    mixed ProductCore::update($null_values)





* Visibility: **public**
* This method is defined in [classes/Product.php line 554](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L554)


#### Arguments
* $null_values **mixed**



### <a name="method-initPricesComputation"></a>initPricesComputation

    mixed ProductCore::initPricesComputation($id_customer)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 577](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L577)


#### Arguments
* $id_customer **mixed**



### <a name="method-getTaxCalculationMethod"></a>getTaxCalculationMethod

    mixed ProductCore::getTaxCalculationMethod($id_customer)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 603](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L603)


#### Arguments
* $id_customer **mixed**



### <a name="method-updatePosition"></a>updatePosition

    mixed ProductCore::updatePosition(boolean $way, integer $position)

Move a product inside its category



* Visibility: **public**
* This method is defined in [classes/Product.php line 618](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L618)


#### Arguments
* $way **boolean** - &lt;p&gt;Up (1)  or Down (0)&lt;/p&gt;
* $position **integer** - &lt;p&gt;return boolean Update result&lt;/p&gt;



### <a name="method-cleanPositions"></a>cleanPositions

    mixed ProductCore::cleanPositions($id_category, $position)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 662](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L662)


#### Arguments
* $id_category **mixed**
* $position **mixed**



### <a name="method-getDefaultAttribute"></a>getDefaultAttribute

    integer ProductCore::getDefaultAttribute($id_product, $minimum_quantity, $reset)

Get the default attribute for a product



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 694](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L694)


#### Arguments
* $id_product **mixed**
* $minimum_quantity **mixed**
* $reset **mixed**



### <a name="method-setAvailableDate"></a>setAvailableDate

    mixed ProductCore::setAvailableDate($available_date)





* Visibility: **public**
* This method is defined in [classes/Product.php line 763](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L763)


#### Arguments
* $available_date **mixed**



### <a name="method-getAvailableDate"></a>getAvailableDate

    \string/null ProductCore::getAvailableDate(integer $id_product, integer $id_product_attribute)

For a given id_product and id_product_attribute, return available date



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 779](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L779)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - &lt;p&gt;Optional&lt;/p&gt;



### <a name="method-updateIsVirtual"></a>updateIsVirtual

    mixed ProductCore::updateIsVirtual($id_product, $is_virtual)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 816](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L816)


#### Arguments
* $id_product **mixed**
* $is_virtual **mixed**



### <a name="method-validateField"></a>validateField

    mixed ProductCore::validateField($field, $value, $id_lang, $skip, $human_errors)





* Visibility: **public**
* This method is defined in [classes/Product.php line 826](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L826)


#### Arguments
* $field **mixed**
* $value **mixed**
* $id_lang **mixed**
* $skip **mixed**
* $human_errors **mixed**



### <a name="method-toggleStatus"></a>toggleStatus

    mixed ProductCore::toggleStatus()





* Visibility: **public**
* This method is defined in [classes/Product.php line 841](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L841)




### <a name="method-delete"></a>delete

    mixed ProductCore::delete()





* Visibility: **public**
* This method is defined in [classes/Product.php line 857](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L857)




### <a name="method-deleteSelection"></a>deleteSelection

    mixed ProductCore::deleteSelection($products)





* Visibility: **public**
* This method is defined in [classes/Product.php line 921](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L921)


#### Arguments
* $products **mixed**



### <a name="method-deleteFromCartRules"></a>deleteFromCartRules

    mixed ProductCore::deleteFromCartRules()





* Visibility: **public**
* This method is defined in [classes/Product.php line 938](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L938)




### <a name="method-deleteFromSupplier"></a>deleteFromSupplier

    mixed ProductCore::deleteFromSupplier()





* Visibility: **public**
* This method is defined in [classes/Product.php line 944](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L944)




### <a name="method-addToCategories"></a>addToCategories

    boolean ProductCore::addToCategories(mixed $categories)

addToCategories add this product to the category/ies if not exists.



* Visibility: **public**
* This method is defined in [classes/Product.php line 955](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L955)


#### Arguments
* $categories **mixed** - &lt;p&gt;id_category or array of id_category&lt;/p&gt;



### <a name="method-updateCategories"></a>updateCategories

    array ProductCore::updateCategories($categories, boolean $keeping_current_pos)

Update categories to index product into



* Visibility: **public**
* This method is defined in [classes/Product.php line 1012](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1012)


#### Arguments
* $categories **mixed**
* $keeping_current_pos **boolean** - &lt;p&gt;(deprecated, no more used)&lt;/p&gt;



### <a name="method-deleteCategory"></a>deleteCategory

    boolean ProductCore::deleteCategory(mixed $id_category, mixed $clean_positions)

deleteCategory delete this product from the category $id_category



* Visibility: **public**
* This method is defined in [classes/Product.php line 1051](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1051)


#### Arguments
* $id_category **mixed**
* $clean_positions **mixed**



### <a name="method-deleteCategories"></a>deleteCategories

    array ProductCore::deleteCategories(boolean $clean_positions)

Delete all association to category where product is indexed



* Visibility: **public**
* This method is defined in [classes/Product.php line 1076](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1076)


#### Arguments
* $clean_positions **boolean** - &lt;p&gt;clean category positions after deletion&lt;/p&gt;



### <a name="method-deleteTags"></a>deleteTags

    array ProductCore::deleteTags()

Delete products tags entries



* Visibility: **public**
* This method is defined in [classes/Product.php line 1101](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1101)




### <a name="method-deleteCartProducts"></a>deleteCartProducts

    array ProductCore::deleteCartProducts()

Delete product from cart



* Visibility: **public**
* This method is defined in [classes/Product.php line 1113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1113)




### <a name="method-deleteImages"></a>deleteImages

    boolean ProductCore::deleteImages()

Delete product images from database



* Visibility: **public**
* This method is defined in [classes/Product.php line 1123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1123)




### <a name="method-getProductAttributePrice"></a>getProductAttributePrice

    mixed ProductCore::getProductAttributePrice($id_product_attribute)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 1144](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1144)


#### Arguments
* $id_product_attribute **mixed**



### <a name="method-getProducts"></a>getProducts

    array ProductCore::getProducts(integer $id_lang, integer $start, integer $limit, string $order_by, string $order_way, $id_category, $only_active, \Context $context)

Get all available products



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 1159](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1159)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;
* $start **integer** - &lt;p&gt;Start number&lt;/p&gt;
* $limit **integer** - &lt;p&gt;Number of products to return&lt;/p&gt;
* $order_by **string** - &lt;p&gt;Field for ordering&lt;/p&gt;
* $order_way **string** - &lt;p&gt;Way for ordering (ASC or DESC)&lt;/p&gt;
* $id_category **mixed**
* $only_active **mixed**
* $context **[Context](ContextCore)**



### <a name="method-getSimpleProducts"></a>getSimpleProducts

    mixed ProductCore::getSimpleProducts($id_lang, \Context $context)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 1212](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1212)


#### Arguments
* $id_lang **mixed**
* $context **[Context](ContextCore)**



### <a name="method-isNew"></a>isNew

    mixed ProductCore::isNew()





* Visibility: **public**
* This method is defined in [classes/Product.php line 1233](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1233)




### <a name="method-productAttributeExists"></a>productAttributeExists

    mixed ProductCore::productAttributeExists($attributes_list, $current_product_attribute, \Context $context, $all_shops, $return_id)





* Visibility: **public**
* This method is defined in [classes/Product.php line 1251](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1251)


#### Arguments
* $attributes_list **mixed**
* $current_product_attribute **mixed**
* $context **[Context](ContextCore)**
* $all_shops **mixed**
* $return_id **mixed**



### <a name="method-addProductAttribute"></a>addProductAttribute

    mixed ProductCore::addProductAttribute($price, $weight, $unit_impact, $ecotax, $quantity, $id_images, $reference, $id_supplier, $ean13, $default, $location, $upc, $minimal_quantity)

addProductAttribute is deprecated

The quantity params now set StockAvailable for the current shop with the specified quantity
The supplier_reference params now set the supplier reference of the default supplier of the product if possible

* Visibility: **public**
* This method is defined in [classes/Product.php line 1310](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1310)


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



### <a name="method-generateMultipleCombinations"></a>generateMultipleCombinations

    mixed ProductCore::generateMultipleCombinations($combinations, $attributes)





* Visibility: **public**
* This method is defined in [classes/Product.php line 1330](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1330)


#### Arguments
* $combinations **mixed**
* $attributes **mixed**



### <a name="method-addCombinationEntity"></a>addCombinationEntity

    mixed ProductCore::addCombinationEntity($wholesale_price, $price, $weight, $unit_impact, $ecotax, integer $quantity, $id_images, $reference, $id_supplier, $ean13, $default, $location, $upc, $minimal_quantity, array $id_shop_list, $available_date)





* Visibility: **public**
* This method is defined in [classes/Product.php line 1372](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1372)


#### Arguments
* $wholesale_price **mixed**
* $price **mixed**
* $weight **mixed**
* $unit_impact **mixed**
* $ecotax **mixed**
* $quantity **integer** - &lt;p&gt;DEPRECATED&lt;/p&gt;
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



### <a name="method-addProductAttributeMultiple"></a>addProductAttributeMultiple

    array ProductCore::addProductAttributeMultiple($attributes, boolean $set_default)





* Visibility: **public**
* This method is defined in [classes/Product.php line 1396](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1396)


#### Arguments
* $attributes **mixed**
* $set_default **boolean**



### <a name="method-deleteDefaultAttributes"></a>deleteDefaultAttributes

    mixed ProductCore::deleteDefaultAttributes()

Del all default attributes for product



* Visibility: **public**
* This method is defined in [classes/Product.php line 1431](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1431)




### <a name="method-setDefaultAttribute"></a>setDefaultAttribute

    mixed ProductCore::setDefaultAttribute($id_product_attribute)





* Visibility: **public**
* This method is defined in [classes/Product.php line 1438](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1438)


#### Arguments
* $id_product_attribute **mixed**



### <a name="method-updateDefaultAttribute"></a>updateDefaultAttribute

    mixed ProductCore::updateDefaultAttribute($id_product)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 1451](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1451)


#### Arguments
* $id_product **mixed**



### <a name="method-updateProductAttribute"></a>updateProductAttribute

    mixed ProductCore::updateProductAttribute($id_product_attribute, $wholesale_price, $price, $weight, $unit, $ecotax, $id_images, $reference, $id_supplier, $ean13, $default, $location, $upc, $minimal_quantity, $available_date)

Update a product attribute



* Visibility: **public**
* This method is defined in [classes/Product.php line 1478](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1478)


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



### <a name="method-addSupplierReference"></a>addSupplierReference

    mixed ProductCore::addSupplierReference(integer $id_supplier, integer $id_product_attribute, string $supplier_reference, float $price, integer $id_currency)

Sets or updates Supplier Reference



* Visibility: **public**
* This method is defined in [classes/Product.php line 1501](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1501)


#### Arguments
* $id_supplier **integer**
* $id_product_attribute **integer**
* $supplier_reference **string**
* $price **float**
* $id_currency **integer**



### <a name="method-updateAttribute"></a>updateAttribute

    array ProductCore::updateAttribute(integer $id_product_attribute, float $wholesale_price, float $price, float $weight, float $unit, float $ecotax, $id_images, string $reference, string $ean13, integer $default, $location, string $upc, string $minimal_quantity, $available_date, $update_all_fields, array $id_shop_list)

Update a product attribute



* Visibility: **public**
* This method is defined in [classes/Product.php line 1544](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1544)


#### Arguments
* $id_product_attribute **integer** - &lt;p&gt;Product attribute id&lt;/p&gt;
* $wholesale_price **float** - &lt;p&gt;Wholesale price&lt;/p&gt;
* $price **float** - &lt;p&gt;Additional price&lt;/p&gt;
* $weight **float** - &lt;p&gt;Additional weight&lt;/p&gt;
* $unit **float**
* $ecotax **float** - &lt;p&gt;Additional ecotax&lt;/p&gt;
* $id_images **mixed**
* $reference **string** - &lt;p&gt;Reference&lt;/p&gt;
* $ean13 **string** - &lt;p&gt;Ean-13 barcode&lt;/p&gt;
* $default **integer** - &lt;p&gt;Default On&lt;/p&gt;
* $location **mixed**
* $upc **string** - &lt;p&gt;Upc barcode&lt;/p&gt;
* $minimal_quantity **string** - &lt;p&gt;Minimal quantity&lt;/p&gt;
* $available_date **mixed**
* $update_all_fields **mixed**
* $id_shop_list **array**



### <a name="method-addAttribute"></a>addAttribute

    mixed ProductCore::addAttribute(float $price, float $weight, $unit_impact, float $ecotax, integer $id_images, string $reference, string $ean13, boolean $default, string $location, $upc, integer $minimal_quantity, array $id_shop_list, $available_date)

Add a product attribute



* Visibility: **public**
* This method is defined in [classes/Product.php line 1623](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1623)


#### Arguments
* $price **float** - &lt;p&gt;Additional price&lt;/p&gt;
* $weight **float** - &lt;p&gt;Additional weight&lt;/p&gt;
* $unit_impact **mixed**
* $ecotax **float** - &lt;p&gt;Additional ecotax&lt;/p&gt;
* $id_images **integer** - &lt;p&gt;Image ids&lt;/p&gt;
* $reference **string** - &lt;p&gt;Reference&lt;/p&gt;
* $ean13 **string** - &lt;p&gt;Ean-13 barcode&lt;/p&gt;
* $default **boolean** - &lt;p&gt;Is default attribute for product&lt;/p&gt;
* $location **string** - &lt;p&gt;Location&lt;/p&gt;
* $upc **mixed**
* $minimal_quantity **integer** - &lt;p&gt;Minimal quantity to add to cart&lt;/p&gt;
* $id_shop_list **array**
* $available_date **mixed**



### <a name="method-updateQuantityProductWithAttributeQuantity"></a>updateQuantityProductWithAttributeQuantity

    mixed ProductCore::updateQuantityProductWithAttributeQuantity()





* Visibility: **public**
* This method is defined in [classes/Product.php line 1700](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1700)




### <a name="method-deleteProductAttributes"></a>deleteProductAttributes

    array ProductCore::deleteProductAttributes()

Delete product attributes



* Visibility: **public**
* This method is defined in [classes/Product.php line 1719](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1719)




### <a name="method-deleteAttributesImpacts"></a>deleteAttributesImpacts

    boolean ProductCore::deleteAttributesImpacts()

Delete product attributes impacts



* Visibility: **public**
* This method is defined in [classes/Product.php line 1739](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1739)




### <a name="method-deleteProductFeatures"></a>deleteProductFeatures

    array ProductCore::deleteProductFeatures()

Delete product features



* Visibility: **public**
* This method is defined in [classes/Product.php line 1752](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1752)




### <a name="method-updateCacheAttachment"></a>updateCacheAttachment

    mixed ProductCore::updateCacheAttachment($id_product)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 1759](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1759)


#### Arguments
* $id_product **mixed**



### <a name="method-deleteAttachments"></a>deleteAttachments

    array ProductCore::deleteAttachments($update_attachment_cache)

Delete product attachments



* Visibility: **public**
* This method is defined in [classes/Product.php line 1778](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1778)


#### Arguments
* $update_attachment_cache **mixed**



### <a name="method-deleteCustomization"></a>deleteCustomization

    array ProductCore::deleteCustomization()

Delete product customizations



* Visibility: **public**
* This method is defined in [classes/Product.php line 1797](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1797)




### <a name="method-deletePack"></a>deletePack

    array ProductCore::deletePack()

Delete product pack details



* Visibility: **public**
* This method is defined in [classes/Product.php line 1818](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1818)




### <a name="method-deleteProductSale"></a>deleteProductSale

    array ProductCore::deleteProductSale()

Delete product sales



* Visibility: **public**
* This method is defined in [classes/Product.php line 1832](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1832)




### <a name="method-deleteSceneProducts"></a>deleteSceneProducts

    array ProductCore::deleteSceneProducts()

Delete product in its scenes



* Visibility: **public**
* This method is defined in [classes/Product.php line 1845](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1845)




### <a name="method-deleteSearchIndexes"></a>deleteSearchIndexes

    array ProductCore::deleteSearchIndexes()

Delete product indexed words



* Visibility: **public**
* This method is defined in [classes/Product.php line 1858](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1858)




### <a name="method-addAttributeCombinaison"></a>addAttributeCombinaison

    array ProductCore::addAttributeCombinaison(integer $id_product_attribute, array $attributes)

Add a product attributes combinaison



* Visibility: **public**
* This method is defined in [classes/Product.php line 1878](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1878)


#### Arguments
* $id_product_attribute **integer** - &lt;p&gt;Product attribute id&lt;/p&gt;
* $attributes **array** - &lt;p&gt;Attributes to forge combinaison&lt;/p&gt;



### <a name="method-addAttributeCombinationMultiple"></a>addAttributeCombinationMultiple

    boolean ProductCore::addAttributeCombinationMultiple($id_attributes, $combinations)





* Visibility: **public**
* This method is defined in [classes/Product.php line 1899](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1899)


#### Arguments
* $id_attributes **mixed**
* $combinations **mixed**



### <a name="method-deleteAttributeCombination"></a>deleteAttributeCombination

    array ProductCore::deleteAttributeCombination(integer $id_product_attribute)

Delete a product attributes combination



* Visibility: **public**
* This method is defined in [classes/Product.php line 1924](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1924)


#### Arguments
* $id_product_attribute **integer** - &lt;p&gt;Product attribute id&lt;/p&gt;



### <a name="method-deleteFeatures"></a>deleteFeatures

    mixed ProductCore::deleteFeatures()

Delete features



* Visibility: **public**
* This method is defined in [classes/Product.php line 1949](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1949)




### <a name="method-getAttributesResume"></a>getAttributesResume

    array ProductCore::getAttributesResume(integer $id_lang, $attribute_value_separator, $attribute_separator)

Get all available product attributes resume



* Visibility: **public**
* This method is defined in [classes/Product.php line 1983](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L1983)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;
* $attribute_value_separator **mixed**
* $attribute_separator **mixed**



### <a name="method-getAttributeCombinations"></a>getAttributeCombinations

    array ProductCore::getAttributeCombinations(integer $id_lang)

Get all available product attributes combinations



* Visibility: **public**
* This method is defined in [classes/Product.php line 2042](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L2042)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;



### <a name="method-getAttributeCombinationsById"></a>getAttributeCombinationsById

    array ProductCore::getAttributeCombinationsById(integer $id_product_attribute, integer $id_lang)

Get product attribute combination by id_product_attribute



* Visibility: **public**
* This method is defined in [classes/Product.php line 2087](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L2087)


#### Arguments
* $id_product_attribute **integer**
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;



### <a name="method-getCombinationImages"></a>getCombinationImages

    mixed ProductCore::getCombinationImages($id_lang)





* Visibility: **public**
* This method is defined in [classes/Product.php line 2127](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L2127)


#### Arguments
* $id_lang **mixed**



### <a name="method-getCombinationImageById"></a>getCombinationImageById

    mixed ProductCore::getCombinationImageById($id_product_attribute, $id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 2170](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L2170)


#### Arguments
* $id_product_attribute **mixed**
* $id_lang **mixed**



### <a name="method-hasAttributes"></a>hasAttributes

    integer ProductCore::hasAttributes()

Check if product has attributes combinations



* Visibility: **public**
* This method is defined in [classes/Product.php line 2196](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L2196)




### <a name="method-getNewProducts"></a>getNewProducts

    array ProductCore::getNewProducts(integer $id_lang, $page_number, $nb_products, $count, $order_by, $order_way, \Context $context)

Get new products



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 2217](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L2217)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;
* $page_number **mixed**
* $nb_products **mixed**
* $count **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $context **[Context](ContextCore)**



### <a name="method-_getProductIdByDate"></a>_getProductIdByDate

    mixed ProductCore::_getProductIdByDate($beginning, $ending, \Context $context, $with_combination)





* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/Product.php line 2330](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L2330)


#### Arguments
* $beginning **mixed**
* $ending **mixed**
* $context **[Context](ContextCore)**
* $with_combination **mixed**



### <a name="method-getRandomSpecial"></a>getRandomSpecial

    array ProductCore::getRandomSpecial(integer $id_lang, $beginning, $ending, \Context $context)

Get a random special



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 2358](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L2358)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;
* $beginning **mixed**
* $ending **mixed**
* $context **[Context](ContextCore)**



### <a name="method-getPricesDrop"></a>getPricesDrop

    array ProductCore::getPricesDrop(integer $id_lang, $page_number, $nb_products, boolean $count, $order_by, $order_way, $beginning, $ending, \Context $context)

Get prices drop



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 2448](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L2448)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;
* $page_number **mixed**
* $nb_products **mixed**
* $count **boolean** - &lt;p&gt;Only in order to get total number (optional)&lt;/p&gt;
* $order_by **mixed**
* $order_way **mixed**
* $beginning **mixed**
* $ending **mixed**
* $context **[Context](ContextCore)**



### <a name="method-getProductCategories"></a>getProductCategories

    array ProductCore::getProductCategories($id_product)

getProductCategories return an array of categories which this product belongs to



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 2574](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L2574)


#### Arguments
* $id_product **mixed**



### <a name="method-getProductCategoriesFull"></a>getProductCategoriesFull

    mixed ProductCore::getProductCategoriesFull($id_product, $id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 2596](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L2596)


#### Arguments
* $id_product **mixed**
* $id_lang **mixed**



### <a name="method-getCategories"></a>getCategories

    array ProductCore::getCategories()

getCategories return an array of categories which this product belongs to



* Visibility: **public**
* This method is defined in [classes/Product.php line 2624](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L2624)




### <a name="method-getCarriers"></a>getCarriers

    mixed ProductCore::getCarriers()

Gets carriers assigned to the product



* Visibility: **public**
* This method is defined in [classes/Product.php line 2632](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L2632)




### <a name="method-setCarriers"></a>setCarriers

    mixed ProductCore::setCarriers($carrier_list)

Sets carriers assigned to the product



* Visibility: **public**
* This method is defined in [classes/Product.php line 2646](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L2646)


#### Arguments
* $carrier_list **mixed**



### <a name="method-getImages"></a>getImages

    array ProductCore::getImages(integer $id_lang, \Context $context)

Get product images and legends



* Visibility: **public**
* This method is defined in [classes/Product.php line 2681](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L2681)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id for multilingual legends&lt;/p&gt;
* $context **[Context](ContextCore)**



### <a name="method-getCover"></a>getCover

    array ProductCore::getCover($id_product, \Context $context)

Get product cover image



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 2698](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L2698)


#### Arguments
* $id_product **mixed**
* $context **[Context](ContextCore)**



### <a name="method-getPriceStatic"></a>getPriceStatic

    float ProductCore::getPriceStatic(integer $id_product, boolean $usetax, integer|null $id_product_attribute, integer $decimals, integer|null $divisor, boolean $only_reduc, boolean $usereduc, integer $quantity, boolean $force_associated_tax, integer|null $id_customer, integer|null $id_cart, integer|null $id_address, null $specific_price_output, boolean $with_ecotax, boolean $use_group_reduction, \Context $context, boolean $use_customer_price)

Returns product price



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 2745](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L2745)


#### Arguments
* $id_product **integer** - &lt;p&gt;Product id&lt;/p&gt;
* $usetax **boolean** - &lt;p&gt;With taxes or not (optional)&lt;/p&gt;
* $id_product_attribute **integer|null** - &lt;p&gt;Product attribute id (optional).&lt;/p&gt;
&lt;pre&gt;&lt;code&gt;                                   If set to false, do not apply the combination price impact.
                                   NULL does apply the default combination price impact.&lt;/code&gt;&lt;/pre&gt;
* $decimals **integer** - &lt;p&gt;Number of decimals (optional)&lt;/p&gt;
* $divisor **integer|null** - &lt;p&gt;Useful when paying many time without fees (optional)&lt;/p&gt;
* $only_reduc **boolean** - &lt;p&gt;Returns only the reduction amount&lt;/p&gt;
* $usereduc **boolean** - &lt;p&gt;Set if the returned amount will include reduction&lt;/p&gt;
* $quantity **integer** - &lt;p&gt;Required for quantity discount application (default value: 1)&lt;/p&gt;
* $force_associated_tax **boolean** - &lt;p&gt;DEPRECATED - NOT USED Force to apply the associated tax.&lt;/p&gt;
&lt;pre&gt;&lt;code&gt;                                   Only works when the parameter $usetax is true&lt;/code&gt;&lt;/pre&gt;
* $id_customer **integer|null** - &lt;p&gt;Customer ID (for customer group reduction)&lt;/p&gt;
* $id_cart **integer|null** - &lt;p&gt;Cart ID. Required when the cookie is not accessible&lt;/p&gt;
&lt;pre&gt;&lt;code&gt;                                   (e.g., inside a payment module, a cron task...)&lt;/code&gt;&lt;/pre&gt;
* $id_address **integer|null** - &lt;p&gt;Customer address ID. Required for price (tax included)&lt;/p&gt;
&lt;pre&gt;&lt;code&gt;                                   calculation regarding the guest localization&lt;/code&gt;&lt;/pre&gt;
* $specific_price_output **null** - &lt;p&gt;If a specific price applies regarding the previous parameters,
                                       this variable is filled with the corresponding SpecificPrice object&lt;/p&gt;
* $with_ecotax **boolean** - &lt;p&gt;Insert ecotax in price output.&lt;/p&gt;
* $use_group_reduction **boolean**
* $context **[Context](ContextCore)**
* $use_customer_price **boolean**



### <a name="method-priceCalculation"></a>priceCalculation

    float ProductCore::priceCalculation(integer $id_shop, integer $id_product, integer $id_product_attribute, integer $id_country, integer $id_state, string $zipcode, integer $id_currency, integer $id_group, integer $quantity, boolean $use_tax, integer $decimals, boolean $only_reduc, boolean $use_reduc, boolean $with_ecotax, null $specific_price, boolean $use_group_reduction, integer $id_customer, boolean $use_customer_price, integer $id_cart, integer $real_quantity)

Price calculation / Get product price



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 2896](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L2896)


#### Arguments
* $id_shop **integer** - &lt;p&gt;Shop id&lt;/p&gt;
* $id_product **integer** - &lt;p&gt;Product id&lt;/p&gt;
* $id_product_attribute **integer** - &lt;p&gt;Product attribute id&lt;/p&gt;
* $id_country **integer** - &lt;p&gt;Country id&lt;/p&gt;
* $id_state **integer** - &lt;p&gt;State id&lt;/p&gt;
* $zipcode **string**
* $id_currency **integer** - &lt;p&gt;Currency id&lt;/p&gt;
* $id_group **integer** - &lt;p&gt;Group id&lt;/p&gt;
* $quantity **integer** - &lt;p&gt;Quantity Required for Specific prices : quantity discount application&lt;/p&gt;
* $use_tax **boolean** - &lt;p&gt;with (1) or without (0) tax&lt;/p&gt;
* $decimals **integer** - &lt;p&gt;Number of decimals returned&lt;/p&gt;
* $only_reduc **boolean** - &lt;p&gt;Returns only the reduction amount&lt;/p&gt;
* $use_reduc **boolean** - &lt;p&gt;Set if the returned amount will include reduction&lt;/p&gt;
* $with_ecotax **boolean** - &lt;p&gt;insert ecotax in price output.&lt;/p&gt;
* $specific_price **null** - &lt;p&gt;If a specific price applies regarding the previous parameters,
                              this variable is filled with the corresponding SpecificPrice object&lt;/p&gt;
* $use_group_reduction **boolean**
* $id_customer **integer**
* $use_customer_price **boolean**
* $id_cart **integer**
* $real_quantity **integer**



### <a name="method-convertAndFormatPrice"></a>convertAndFormatPrice

    mixed ProductCore::convertAndFormatPrice($price, $currency, \Context $context)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 3095](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3095)


#### Arguments
* $price **mixed**
* $currency **mixed**
* $context **[Context](ContextCore)**



### <a name="method-isDiscounted"></a>isDiscounted

    mixed ProductCore::isDiscounted($id_product, $quantity, \Context $context)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 3106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3106)


#### Arguments
* $id_product **mixed**
* $quantity **mixed**
* $context **[Context](ContextCore)**



### <a name="method-getPrice"></a>getPrice

    float ProductCore::getPrice(boolean $tax, integer $id_product_attribute, integer $decimals, integer $divisor, $only_reduc, $usereduc, $quantity)

Get product price
Same as static function getPriceStatic, no need to specify product id



* Visibility: **public**
* This method is defined in [classes/Product.php line 3136](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3136)


#### Arguments
* $tax **boolean** - &lt;p&gt;With taxes or not (optional)&lt;/p&gt;
* $id_product_attribute **integer** - &lt;p&gt;Product attribute id (optional)&lt;/p&gt;
* $decimals **integer** - &lt;p&gt;Number of decimals (optional)&lt;/p&gt;
* $divisor **integer** - &lt;p&gt;Util when paying many time without fees (optional)&lt;/p&gt;
* $only_reduc **mixed**
* $usereduc **mixed**
* $quantity **mixed**



### <a name="method-getPublicPrice"></a>getPublicPrice

    mixed ProductCore::getPublicPrice($tax, $id_product_attribute, $decimals, $divisor, $only_reduc, $usereduc, $quantity)





* Visibility: **public**
* This method is defined in [classes/Product.php line 3142](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3142)


#### Arguments
* $tax **mixed**
* $id_product_attribute **mixed**
* $decimals **mixed**
* $divisor **mixed**
* $only_reduc **mixed**
* $usereduc **mixed**
* $quantity **mixed**



### <a name="method-getIdProductAttributeMostExpensive"></a>getIdProductAttributeMostExpensive

    mixed ProductCore::getIdProductAttributeMostExpensive()





* Visibility: **public**
* This method is defined in [classes/Product.php line 3150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3150)




### <a name="method-getDefaultIdProductAttribute"></a>getDefaultIdProductAttribute

    mixed ProductCore::getDefaultIdProductAttribute()





* Visibility: **public**
* This method is defined in [classes/Product.php line 3166](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3166)




### <a name="method-getPriceWithoutReduct"></a>getPriceWithoutReduct

    mixed ProductCore::getPriceWithoutReduct($notax, $id_product_attribute, $decimals)





* Visibility: **public**
* This method is defined in [classes/Product.php line 3183](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3183)


#### Arguments
* $notax **mixed**
* $id_product_attribute **mixed**
* $decimals **mixed**



### <a name="method-convertPrice"></a>convertPrice

    string ProductCore::convertPrice(array $params, $smarty)

Display price with right format and currency



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 3195](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3195)


#### Arguments
* $params **array** - &lt;p&gt;Params&lt;/p&gt;
* $smarty **mixed** - &lt;p&gt;Smarty object&lt;/p&gt;



### <a name="method-convertPriceWithCurrency"></a>convertPriceWithCurrency

    string ProductCore::convertPriceWithCurrency(array $params, object $smarty)

Convert price with currency



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 3207](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3207)


#### Arguments
* $params **array**
* $smarty **object** - &lt;p&gt;DEPRECATED&lt;/p&gt;



### <a name="method-displayWtPrice"></a>displayWtPrice

    mixed ProductCore::displayWtPrice($params, $smarty)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 3212](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3212)


#### Arguments
* $params **mixed**
* $smarty **mixed**



### <a name="method-displayWtPriceWithCurrency"></a>displayWtPriceWithCurrency

    string ProductCore::displayWtPriceWithCurrency(array $params, \Smarty $smarty)

Display WT price with currency



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 3224](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3224)


#### Arguments
* $params **array**
* $smarty **Smarty** - &lt;p&gt;DEPRECATED&lt;/p&gt;



### <a name="method-getQuantity"></a>getQuantity

    integer ProductCore::getQuantity(integer $id_product, integer $id_product_attribute, $cache_is_pack)

Get available product quantities



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 3236](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3236)


#### Arguments
* $id_product **integer** - &lt;p&gt;Product id&lt;/p&gt;
* $id_product_attribute **integer** - &lt;p&gt;Product attribute id (optional)&lt;/p&gt;
* $cache_is_pack **mixed**



### <a name="method-sqlStock"></a>sqlStock

    string ProductCore::sqlStock($product_alias, $product_attribute, $inner_join, \Shop $shop)

Create JOIN query with 'stock_available' table



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 3257](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3257)


#### Arguments
* $product_alias **mixed**
* $product_attribute **mixed**
* $inner_join **mixed**
* $shop **[Shop](ShopCore)**



### <a name="method-updateQuantity"></a>updateQuantity

    false ProductCore::updateQuantity()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 3291](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3291)




### <a name="method-reinjectQuantities"></a>reinjectQuantities

    false ProductCore::reinjectQuantities()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 3309](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3309)




### <a name="method-isAvailableWhenOutOfStock"></a>isAvailableWhenOutOfStock

    mixed ProductCore::isAvailableWhenOutOfStock($out_of_stock)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 3316](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3316)


#### Arguments
* $out_of_stock **mixed**



### <a name="method-checkQty"></a>checkQty

    boolean ProductCore::checkQty(integer $qty)

Check product availability



* Visibility: **public**
* This method is defined in [classes/Product.php line 3342](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3342)


#### Arguments
* $qty **integer** - &lt;p&gt;Quantity desired&lt;/p&gt;



### <a name="method-checkDefaultAttributes"></a>checkDefaultAttributes

    mixed ProductCore::checkDefaultAttributes()

Check if there is no default attribute and create it if not



* Visibility: **public**
* This method is defined in [classes/Product.php line 3364](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3364)




### <a name="method-getAttributesColorList"></a>getAttributesColorList

    mixed ProductCore::getAttributesColorList(array $products, $have_stock)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 3408](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3408)


#### Arguments
* $products **array**
* $have_stock **mixed**



### <a name="method-getAttributesGroups"></a>getAttributesGroups

    array ProductCore::getAttributesGroups(integer $id_lang)

Get all available attribute groups



* Visibility: **public**
* This method is defined in [classes/Product.php line 3453](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3453)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;



### <a name="method-deleteAccessories"></a>deleteAccessories

    mixed ProductCore::deleteAccessories()

Delete product accessories



* Visibility: **public**
* This method is defined in [classes/Product.php line 3485](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3485)




### <a name="method-deleteFromAccessories"></a>deleteFromAccessories

    mixed ProductCore::deleteFromAccessories()

Delete product from other products accessories



* Visibility: **public**
* This method is defined in [classes/Product.php line 3495](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3495)




### <a name="method-getAccessoriesLight"></a>getAccessoriesLight

    array ProductCore::getAccessoriesLight(integer $id_lang, integer $id_product)

Get product accessories (only names)



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 3507](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3507)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;
* $id_product **integer** - &lt;p&gt;Product id&lt;/p&gt;



### <a name="method-getAccessories"></a>getAccessories

    array ProductCore::getAccessories(integer $id_lang, $active)

Get product accessories



* Visibility: **public**
* This method is defined in [classes/Product.php line 3528](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3528)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;
* $active **mixed**



### <a name="method-getAccessoryById"></a>getAccessoryById

    mixed ProductCore::getAccessoryById($accessory_id)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 3573](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3573)


#### Arguments
* $accessory_id **mixed**



### <a name="method-changeAccessories"></a>changeAccessories

    mixed ProductCore::changeAccessories(array $accessories_id)

Link accessories with product



* Visibility: **public**
* This method is defined in [classes/Product.php line 3583](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3583)


#### Arguments
* $accessories_id **array** - &lt;p&gt;Accessories ids&lt;/p&gt;



### <a name="method-addFeaturesCustomToDB"></a>addFeaturesCustomToDB

    mixed ProductCore::addFeaturesCustomToDB($id_value, $lang, $cust)

Add new feature to product



* Visibility: **public**
* This method is defined in [classes/Product.php line 3596](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3596)


#### Arguments
* $id_value **mixed**
* $lang **mixed**
* $cust **mixed**



### <a name="method-addFeaturesToDB"></a>addFeaturesToDB

    mixed ProductCore::addFeaturesToDB($id_feature, $id_value, $cust)





* Visibility: **public**
* This method is defined in [classes/Product.php line 3602](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3602)


#### Arguments
* $id_feature **mixed**
* $id_value **mixed**
* $cust **mixed**



### <a name="method-addFeatureProductImport"></a>addFeatureProductImport

    mixed ProductCore::addFeatureProductImport($id_product, $id_feature, $id_feature_value)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 3617](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3617)


#### Arguments
* $id_product **mixed**
* $id_feature **mixed**
* $id_feature_value **mixed**



### <a name="method-getFeatures"></a>getFeatures

    array ProductCore::getFeatures()

Select all features for the object



* Visibility: **public**
* This method is defined in [classes/Product.php line 3631](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3631)




### <a name="method-getFeaturesStatic"></a>getFeaturesStatic

    mixed ProductCore::getFeaturesStatic($id_product)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 3636](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3636)


#### Arguments
* $id_product **mixed**



### <a name="method-cacheProductsFeatures"></a>cacheProductsFeatures

    mixed ProductCore::cacheProductsFeatures($product_ids)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 3652](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3652)


#### Arguments
* $product_ids **mixed**



### <a name="method-cacheFrontFeatures"></a>cacheFrontFeatures

    mixed ProductCore::cacheFrontFeatures($product_ids, $id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 3680](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3680)


#### Arguments
* $product_ids **mixed**
* $id_lang **mixed**



### <a name="method-searchByName"></a>searchByName

    array ProductCore::searchByName(integer $id_lang, string $query, \Context $context)

Admin panel product search



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 3723](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3723)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;
* $query **string** - &lt;p&gt;Search query&lt;/p&gt;
* $context **[Context](ContextCore)**



### <a name="method-duplicateAttributes"></a>duplicateAttributes

    mixed ProductCore::duplicateAttributes(integer $id_product_old, integer $id_product_new)

Duplicate attributes when duplicating a product



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 3778](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3778)


#### Arguments
* $id_product_old **integer** - &lt;p&gt;Old product id&lt;/p&gt;
* $id_product_new **integer** - &lt;p&gt;New product id&lt;/p&gt;



### <a name="method-getAttributesImpacts"></a>getAttributesImpacts

    mixed ProductCore::getAttributesImpacts($id_product)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 3869](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3869)


#### Arguments
* $id_product **mixed**



### <a name="method-_getAttributeImageAssociations"></a>_getAttributeImageAssociations

    array ProductCore::_getAttributeImageAssociations(integer $id_product_attribute)

Get product attribute image associations



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 3892](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3892)


#### Arguments
* $id_product_attribute **integer**



### <a name="method-duplicateAccessories"></a>duplicateAccessories

    mixed ProductCore::duplicateAccessories($id_product_old, $id_product_new)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 3905](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3905)


#### Arguments
* $id_product_old **mixed**
* $id_product_new **mixed**



### <a name="method-duplicateTags"></a>duplicateTags

    mixed ProductCore::duplicateTags($id_product_old, $id_product_new)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 3922](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3922)


#### Arguments
* $id_product_old **mixed**
* $id_product_new **mixed**



### <a name="method-duplicateDownload"></a>duplicateDownload

    mixed ProductCore::duplicateDownload($id_product_old, $id_product_new)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 3941](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3941)


#### Arguments
* $id_product_old **mixed**
* $id_product_new **mixed**



### <a name="method-duplicateAttachments"></a>duplicateAttachments

    mixed ProductCore::duplicateAttachments($id_product_old, $id_product_new)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 3971](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L3971)


#### Arguments
* $id_product_old **mixed**
* $id_product_new **mixed**



### <a name="method-duplicateFeatures"></a>duplicateFeatures

    mixed ProductCore::duplicateFeatures(integer $id_product_old, $id_product_new)

Duplicate features when duplicating a product



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 4003](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4003)


#### Arguments
* $id_product_old **integer** - &lt;p&gt;Old product id&lt;/p&gt;
* $id_product_new **mixed**



### <a name="method-_getCustomizationFieldsNLabels"></a>_getCustomizationFieldsNLabels

    mixed ProductCore::_getCustomizationFieldsNLabels($product_id, $id_shop)





* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/Product.php line 4048](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4048)


#### Arguments
* $product_id **mixed**
* $id_shop **mixed**



### <a name="method-duplicateSpecificPrices"></a>duplicateSpecificPrices

    mixed ProductCore::duplicateSpecificPrices($old_product_id, $product_id)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 4091](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4091)


#### Arguments
* $old_product_id **mixed**
* $product_id **mixed**



### <a name="method-duplicateCustomizationFields"></a>duplicateCustomizationFields

    mixed ProductCore::duplicateCustomizationFields($old_product_id, $product_id)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 4102](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4102)


#### Arguments
* $old_product_id **mixed**
* $product_id **mixed**



### <a name="method-duplicateSuppliers"></a>duplicateSuppliers

    mixed ProductCore::duplicateSuppliers(integer $id_product_old, integer $id_product_new)

Adds suppliers from old product onto a newly duplicated product



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 4149](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4149)


#### Arguments
* $id_product_old **integer**
* $id_product_new **integer**



### <a name="method-getLink"></a>getLink

    mixed ProductCore::getLink(\Context $context)

Get the link of the product page of this product



* Visibility: **public**
* This method is defined in [classes/Product.php line 4170](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4170)


#### Arguments
* $context **[Context](ContextCore)**



### <a name="method-getTags"></a>getTags

    mixed ProductCore::getTags($id_lang)





* Visibility: **public**
* This method is defined in [classes/Product.php line 4178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4178)


#### Arguments
* $id_lang **mixed**



### <a name="method-defineProductImage"></a>defineProductImage

    mixed ProductCore::defineProductImage($row, $id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 4196](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4196)


#### Arguments
* $row **mixed**
* $id_lang **mixed**



### <a name="method-getProductProperties"></a>getProductProperties

    mixed ProductCore::getProductProperties($id_lang, $row, \Context $context)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 4205](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4205)


#### Arguments
* $id_lang **mixed**
* $row **mixed**
* $context **[Context](ContextCore)**



### <a name="method-getTaxesInformations"></a>getTaxesInformations

    mixed ProductCore::getTaxesInformations($row, \Context $context)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 4359](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4359)


#### Arguments
* $row **mixed**
* $context **[Context](ContextCore)**



### <a name="method-getProductsProperties"></a>getProductsProperties

    mixed ProductCore::getProductsProperties($id_lang, $query_result)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 4381](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4381)


#### Arguments
* $id_lang **mixed**
* $query_result **mixed**



### <a name="method-getFrontFeaturesStatic"></a>getFrontFeaturesStatic

    mixed ProductCore::getFrontFeaturesStatic($id_lang, $id_product)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 4402](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4402)


#### Arguments
* $id_lang **mixed**
* $id_product **mixed**



### <a name="method-getFrontFeatures"></a>getFrontFeatures

    mixed ProductCore::getFrontFeatures($id_lang)





* Visibility: **public**
* This method is defined in [classes/Product.php line 4422](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4422)


#### Arguments
* $id_lang **mixed**



### <a name="method-getAttachmentsStatic"></a>getAttachmentsStatic

    mixed ProductCore::getAttachmentsStatic($id_lang, $id_product)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 4427](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4427)


#### Arguments
* $id_lang **mixed**
* $id_product **mixed**



### <a name="method-getAttachments"></a>getAttachments

    mixed ProductCore::getAttachments($id_lang)





* Visibility: **public**
* This method is defined in [classes/Product.php line 4437](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4437)


#### Arguments
* $id_lang **mixed**



### <a name="method-getAllCustomizedDatas"></a>getAllCustomizedDatas

    mixed ProductCore::getAllCustomizedDatas($id_cart, $id_lang, $only_in_cart, $id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 4446](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4446)


#### Arguments
* $id_cart **mixed**
* $id_lang **mixed**
* $only_in_cart **mixed**
* $id_shop **mixed**



### <a name="method-addCustomizationPrice"></a>addCustomizationPrice

    mixed ProductCore::addCustomizationPrice($products, $customized_datas)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 4500](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4500)


#### Arguments
* $products **mixed**
* $customized_datas **mixed**



### <a name="method-_checkLabelField"></a>_checkLabelField

    mixed ProductCore::_checkLabelField($field, $value)





* Visibility: **protected**
* This method is defined in [classes/Product.php line 4557](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4557)


#### Arguments
* $field **mixed**
* $value **mixed**



### <a name="method-_deleteOldLabels"></a>_deleteOldLabels

    mixed ProductCore::_deleteOldLabels()





* Visibility: **protected**
* This method is defined in [classes/Product.php line 4569](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4569)




### <a name="method-_createLabel"></a>_createLabel

    mixed ProductCore::_createLabel($languages, $type)





* Visibility: **protected**
* This method is defined in [classes/Product.php line 4633](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4633)


#### Arguments
* $languages **mixed**
* $type **mixed**



### <a name="method-createLabels"></a>createLabels

    mixed ProductCore::createLabels($uploadable_files, $text_fields)





* Visibility: **public**
* This method is defined in [classes/Product.php line 4665](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4665)


#### Arguments
* $uploadable_files **mixed**
* $text_fields **mixed**



### <a name="method-updateLabels"></a>updateLabels

    mixed ProductCore::updateLabels()





* Visibility: **public**
* This method is defined in [classes/Product.php line 4687](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4687)




### <a name="method-getCustomizationFields"></a>getCustomizationFields

    mixed ProductCore::getCustomizationFields($id_lang, $id_shop)





* Visibility: **public**
* This method is defined in [classes/Product.php line 4735](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4735)


#### Arguments
* $id_lang **mixed**
* $id_shop **mixed**



### <a name="method-getCustomizationFieldIds"></a>getCustomizationFieldIds

    mixed ProductCore::getCustomizationFieldIds()





* Visibility: **public**
* This method is defined in [classes/Product.php line 4767](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4767)




### <a name="method-getRequiredCustomizableFields"></a>getRequiredCustomizableFields

    mixed ProductCore::getRequiredCustomizableFields()





* Visibility: **public**
* This method is defined in [classes/Product.php line 4778](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4778)




### <a name="method-getRequiredCustomizableFieldsStatic"></a>getRequiredCustomizableFieldsStatic

    mixed ProductCore::getRequiredCustomizableFieldsStatic($id)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 4786](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4786)


#### Arguments
* $id **mixed**



### <a name="method-hasAllRequiredCustomizableFields"></a>hasAllRequiredCustomizableFields

    mixed ProductCore::hasAllRequiredCustomizableFields(\Context $context)





* Visibility: **public**
* This method is defined in [classes/Product.php line 4799](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4799)


#### Arguments
* $context **[Context](ContextCore)**



### <a name="method-idIsOnCategoryId"></a>idIsOnCategoryId

    boolean ProductCore::idIsOnCategoryId(integer $id_product, array $categories)

Checks if the product is in at least one of the submited categories



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 4836](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4836)


#### Arguments
* $id_product **integer**
* $categories **array** - &lt;p&gt;array of category arrays&lt;/p&gt;



### <a name="method-getNoPackPrice"></a>getNoPackPrice

    mixed ProductCore::getNoPackPrice()





* Visibility: **public**
* This method is defined in [classes/Product.php line 4857](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4857)




### <a name="method-checkAccess"></a>checkAccess

    mixed ProductCore::checkAccess($id_customer)





* Visibility: **public**
* This method is defined in [classes/Product.php line 4862](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4862)


#### Arguments
* $id_customer **mixed**



### <a name="method-checkAccessStatic"></a>checkAccessStatic

    mixed ProductCore::checkAccessStatic($id_product, $id_customer)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 4867](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4867)


#### Arguments
* $id_product **mixed**
* $id_customer **mixed**



### <a name="method-addStockMvt"></a>addStockMvt

    boolean ProductCore::addStockMvt(integer $quantity, integer $id_reason, integer $id_product_attribute, integer $id_order, integer $id_employee)

Add a stock movement for current product

Since 1.5, this method only permit to add/remove available quantities of the current product in the current shop

* Visibility: **public**
* This method is defined in [classes/Product.php line 4913](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4913)


#### Arguments
* $quantity **integer**
* $id_reason **integer** - &lt;ul&gt;
&lt;li&gt;useless&lt;/li&gt;
&lt;/ul&gt;
* $id_product_attribute **integer**
* $id_order **integer** - &lt;ul&gt;
&lt;li&gt;DEPRECATED&lt;/li&gt;
&lt;/ul&gt;
* $id_employee **integer** - &lt;ul&gt;
&lt;li&gt;DEPRECATED&lt;/li&gt;
&lt;/ul&gt;



### <a name="method-getStockMvts"></a>getStockMvts

    mixed ProductCore::getStockMvts($id_lang)





* Visibility: **public**
* This method is defined in [classes/Product.php line 4936](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4936)


#### Arguments
* $id_lang **mixed**



### <a name="method-getUrlRewriteInformations"></a>getUrlRewriteInformations

    mixed ProductCore::getUrlRewriteInformations($id_product)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 4967](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4967)


#### Arguments
* $id_product **mixed**



### <a name="method-getIdTaxRulesGroup"></a>getIdTaxRulesGroup

    mixed ProductCore::getIdTaxRulesGroup()





* Visibility: **public**
* This method is defined in [classes/Product.php line 4981](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4981)




### <a name="method-getIdTaxRulesGroupByIdProduct"></a>getIdTaxRulesGroupByIdProduct

    mixed ProductCore::getIdTaxRulesGroupByIdProduct($id_product, \Context $context)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 4986](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L4986)


#### Arguments
* $id_product **mixed**
* $context **[Context](ContextCore)**



### <a name="method-getTaxesRate"></a>getTaxesRate

    float ProductCore::getTaxesRate(\Address|null $address)

Returns tax rate.



* Visibility: **public**
* This method is defined in [classes/Product.php line 5009](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5009)


#### Arguments
* $address **[Address](AddressCore)|null**



### <a name="method-getWsProductFeatures"></a>getWsProductFeatures

    array ProductCore::getWsProductFeatures()

Webservice getter : get product features association



* Visibility: **public**
* This method is defined in [classes/Product.php line 5026](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5026)




### <a name="method-setWsProductFeatures"></a>setWsProductFeatures

    boolean ProductCore::setWsProductFeatures($product_features)

Webservice setter : set product features association



* Visibility: **public**
* This method is defined in [classes/Product.php line 5049](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5049)


#### Arguments
* $product_features **mixed** - &lt;p&gt;Product Feature ids&lt;/p&gt;



### <a name="method-getWsDefaultCombination"></a>getWsDefaultCombination

    integer ProductCore::getWsDefaultCombination()

Webservice getter : get virtual field default combination



* Visibility: **public**
* This method is defined in [classes/Product.php line 5066](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5066)




### <a name="method-setWsDefaultCombination"></a>setWsDefaultCombination

    boolean ProductCore::setWsDefaultCombination(integer $id_combination)

Webservice setter : set virtual field default combination



* Visibility: **public**
* This method is defined in [classes/Product.php line 5077](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5077)


#### Arguments
* $id_combination **integer** - &lt;p&gt;id default combination&lt;/p&gt;



### <a name="method-getWsCategories"></a>getWsCategories

    array ProductCore::getWsCategories()

Webservice getter : get category ids of current product for association



* Visibility: **public**
* This method is defined in [classes/Product.php line 5088](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5088)




### <a name="method-setWsCategories"></a>setWsCategories

    boolean ProductCore::setWsCategories(array $category_ids)

Webservice setter : set category ids of current product for association



* Visibility: **public**
* This method is defined in [classes/Product.php line 5106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5106)


#### Arguments
* $category_ids **array** - &lt;p&gt;category ids&lt;/p&gt;



### <a name="method-getWsAccessories"></a>getWsAccessories

    array ProductCore::getWsAccessories()

Webservice getter : get product accessories ids of current product for association



* Visibility: **public**
* This method is defined in [classes/Product.php line 5136](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5136)




### <a name="method-setWsAccessories"></a>setWsAccessories

    mixed ProductCore::setWsAccessories($accessories)

Webservice setter : set product accessories ids of current product for association



* Visibility: **public**
* This method is defined in [classes/Product.php line 5154](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5154)


#### Arguments
* $accessories **mixed** - &lt;p&gt;product ids&lt;/p&gt;



### <a name="method-getWsCombinations"></a>getWsCombinations

    array ProductCore::getWsCombinations()

Webservice getter : get combination ids of current product for association



* Visibility: **public**
* This method is defined in [classes/Product.php line 5169](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5169)




### <a name="method-setWsCombinations"></a>setWsCombinations

    mixed ProductCore::setWsCombinations($combinations)

Webservice setter : set combination ids of current product for association



* Visibility: **public**
* This method is defined in [classes/Product.php line 5186](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5186)


#### Arguments
* $combinations **mixed** - &lt;p&gt;combination ids&lt;/p&gt;



### <a name="method-getWsProductOptionValues"></a>getWsProductOptionValues

    array ProductCore::getWsProductOptionValues()

Webservice getter : get product option ids of current product for association



* Visibility: **public**
* This method is defined in [classes/Product.php line 5254](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5254)




### <a name="method-getWsPositionInCategory"></a>getWsPositionInCategory

    integer ProductCore::getWsPositionInCategory()

Webservice getter : get virtual field position in category



* Visibility: **public**
* This method is defined in [classes/Product.php line 5269](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5269)




### <a name="method-setWsPositionInCategory"></a>setWsPositionInCategory

    boolean ProductCore::setWsPositionInCategory($position)

Webservice setter : set virtual field position in category



* Visibility: **public**
* This method is defined in [classes/Product.php line 5286](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5286)


#### Arguments
* $position **mixed**



### <a name="method-getCoverWs"></a>getCoverWs

    integer ProductCore::getCoverWs()

Webservice getter : get virtual field id_default_image in category



* Visibility: **public**
* This method is defined in [classes/Product.php line 5325](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5325)




### <a name="method-setCoverWs"></a>setCoverWs

    boolean ProductCore::setCoverWs($id_image)

Webservice setter : set virtual field id_default_image in category



* Visibility: **public**
* This method is defined in [classes/Product.php line 5336](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5336)


#### Arguments
* $id_image **mixed**



### <a name="method-getWsImages"></a>getWsImages

    array ProductCore::getWsImages()

Webservice getter : get image ids of current product for association



* Visibility: **public**
* This method is defined in [classes/Product.php line 5353](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5353)




### <a name="method-getWsStockAvailables"></a>getWsStockAvailables

    mixed ProductCore::getWsStockAvailables()





* Visibility: **public**
* This method is defined in [classes/Product.php line 5363](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5363)




### <a name="method-getWsTags"></a>getWsTags

    mixed ProductCore::getWsTags()





* Visibility: **public**
* This method is defined in [classes/Product.php line 5370](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5370)




### <a name="method-setWsTags"></a>setWsTags

    mixed ProductCore::setWsTags($tag_ids)

Webservice setter : set tag ids of current product for association



* Visibility: **public**
* This method is defined in [classes/Product.php line 5383](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5383)


#### Arguments
* $tag_ids **mixed** - &lt;p&gt;tag ids&lt;/p&gt;



### <a name="method-deleteWsTags"></a>deleteWsTags

    array ProductCore::deleteWsTags()

Delete products tags entries without delete tags for webservice usage



* Visibility: **public**
* This method is defined in [classes/Product.php line 5412](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5412)




### <a name="method-getWsManufacturerName"></a>getWsManufacturerName

    mixed ProductCore::getWsManufacturerName()





* Visibility: **public**
* This method is defined in [classes/Product.php line 5418](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5418)




### <a name="method-resetEcoTax"></a>resetEcoTax

    mixed ProductCore::resetEcoTax()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 5423](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5423)




### <a name="method-setGroupReduction"></a>setGroupReduction

    mixed ProductCore::setGroupReduction()

Set Group reduction if needed



* Visibility: **public**
* This method is defined in [classes/Product.php line 5433](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5433)




### <a name="method-existsRefInDatabase"></a>existsRefInDatabase

    boolean ProductCore::existsRefInDatabase($reference)

Checks if reference exists



* Visibility: **public**
* This method is defined in [classes/Product.php line 5442](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5442)


#### Arguments
* $reference **mixed**



### <a name="method-getProductAttributesIds"></a>getProductAttributesIds

    array ProductCore::getProductAttributesIds(integer $id_product, $shop_only)

Get all product attributes ids



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 5459](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5459)


#### Arguments
* $id_product **integer** - &lt;p&gt;the id of the product&lt;/p&gt;
* $shop_only **mixed**



### <a name="method-getAttributesParams"></a>getAttributesParams

    array ProductCore::getAttributesParams(integer $id_product, $id_product_attribute)

Get label by lang and value by lang too



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 5475](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5475)


#### Arguments
* $id_product **integer**
* $id_product_attribute **mixed**



### <a name="method-getAttributesInformationsByProduct"></a>getAttributesInformationsByProduct

    mixed ProductCore::getAttributesInformationsByProduct(integer $id_product)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 5568](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5568)


#### Arguments
* $id_product **integer**



### <a name="method-getAnchor"></a>getAnchor

    string ProductCore::getAnchor(integer $id_product_attribute, $with_id)

Get the combination url anchor of the product



* Visibility: **public**
* This method is defined in [classes/Product.php line 5667](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5667)


#### Arguments
* $id_product_attribute **integer**
* $with_id **mixed**



### <a name="method-getProductName"></a>getProductName

    string ProductCore::getProductName(integer $id_product, integer $id_product_attribute, integer $id_lang)

Gets the name of a given product, in the given lang



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 5690](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5690)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - &lt;p&gt;Optional&lt;/p&gt;
* $id_lang **integer** - &lt;p&gt;Optional&lt;/p&gt;



### <a name="method-addWs"></a>addWs

    mixed ProductCore::addWs($autodate, $null_values)





* Visibility: **public**
* This method is defined in [classes/Product.php line 5728](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5728)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-updateWs"></a>updateWs

    mixed ProductCore::updateWs($null_values)





* Visibility: **public**
* This method is defined in [classes/Product.php line 5737](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5737)


#### Arguments
* $null_values **mixed**



### <a name="method-getRealQuantity"></a>getRealQuantity

    integer ProductCore::getRealQuantity(integer $id_product, integer $id_product_attribute, integer $id_warehouse, integer $id_shop)

For a given product, returns its real quantity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 5757](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5757)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $id_warehouse **integer**
* $id_shop **integer**



### <a name="method-usesAdvancedStockManagement"></a>usesAdvancedStockManagement

    boolean ProductCore::usesAdvancedStockManagement(integer $id_product)

For a given product, tells if it uses the advanced stock management



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 5780](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5780)


#### Arguments
* $id_product **integer**



### <a name="method-flushPriceCache"></a>flushPriceCache

    mixed ProductCore::flushPriceCache()

This method allows to flush price cache



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 5796](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5796)




### <a name="method-getParentCategories"></a>getParentCategories

    array ProductCore::getParentCategories(integer $id_lang)

Get list of parent categories



* Visibility: **public**
* This method is defined in [classes/Product.php line 5809](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5809)


#### Arguments
* $id_lang **integer**



### <a name="method-loadStockData"></a>loadStockData

    mixed ProductCore::loadStockData()

Fill the variables used for stock management



* Visibility: **public**
* This method is defined in [classes/Product.php line 5828](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5828)




### <a name="method-useAdvancedStockManagement"></a>useAdvancedStockManagement

    mixed ProductCore::useAdvancedStockManagement()





* Visibility: **public**
* This method is defined in [classes/Product.php line 5841](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5841)




### <a name="method-setAdvancedStockManagement"></a>setAdvancedStockManagement

    mixed ProductCore::setAdvancedStockManagement($value)





* Visibility: **public**
* This method is defined in [classes/Product.php line 5850](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5850)


#### Arguments
* $value **mixed**



### <a name="method-getDefaultCategory"></a>getDefaultCategory

    mixed ProductCore::getDefaultCategory()

get the default category according to the shop



* Visibility: **public**
* This method is defined in [classes/Product.php line 5868](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5868)




### <a name="method-getShopsByProduct"></a>getShopsByProduct

    mixed ProductCore::getShopsByProduct($id_product)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 5883](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5883)


#### Arguments
* $id_product **mixed**



### <a name="method-deleteDownload"></a>deleteDownload

    boolean ProductCore::deleteDownload()

Remove all downloadable files for product and its attributes



* Visibility: **public**
* This method is defined in [classes/Product.php line 5896](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5896)




### <a name="method-getAttributeCombinaisons"></a>getAttributeCombinaisons

    mixed ProductCore::getAttributeCombinaisons(integer $id_lang)





* Visibility: **public**
* This method is defined in [classes/Product.php line 5913](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5913)


#### Arguments
* $id_lang **integer**



### <a name="method-deleteAttributeCombinaison"></a>deleteAttributeCombinaison

    mixed ProductCore::deleteAttributeCombinaison(integer $id_product_attribute)





* Visibility: **public**
* This method is defined in [classes/Product.php line 5924](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5924)


#### Arguments
* $id_product_attribute **integer**



### <a name="method-getType"></a>getType

    integer ProductCore::getType()

Get the product type (simple, virtual, pack)



* Visibility: **public**
* This method is defined in [classes/Product.php line 5936](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5936)




### <a name="method-hasAttributesInOtherShops"></a>hasAttributesInOtherShops

    mixed ProductCore::hasAttributesInOtherShops()





* Visibility: **public**
* This method is defined in [classes/Product.php line 5951](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5951)




### <a name="method-getIdTaxRulesGroupMostUsed"></a>getIdTaxRulesGroupMostUsed

    mixed ProductCore::getIdTaxRulesGroupMostUsed()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 5961](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5961)




### <a name="method-getIdByEan13"></a>getIdByEan13

    integer ProductCore::getIdByEan13(string $ean13)

For a given ean13 reference, returns the corresponding id



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 5984](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L5984)


#### Arguments
* $ean13 **string**



### <a name="method-getWsType"></a>getWsType

    mixed ProductCore::getWsType()





* Visibility: **public**
* This method is defined in [classes/Product.php line 6002](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L6002)




### <a name="method-modifierWsLinkRewrite"></a>modifierWsLinkRewrite

    mixed ProductCore::modifierWsLinkRewrite()





* Visibility: **public**
* This method is defined in [classes/Product.php line 6015](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L6015)




### <a name="method-getWsProductBundle"></a>getWsProductBundle

    mixed ProductCore::getWsProductBundle()





* Visibility: **public**
* This method is defined in [classes/Product.php line 6028](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L6028)




### <a name="method-setWsType"></a>setWsType

    mixed ProductCore::setWsType($type_str)





* Visibility: **public**
* This method is defined in [classes/Product.php line 6033](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L6033)


#### Arguments
* $type_str **mixed**



### <a name="method-setWsProductBundle"></a>setWsProductBundle

    mixed ProductCore::setWsProductBundle($items)





* Visibility: **public**
* This method is defined in [classes/Product.php line 6057](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L6057)


#### Arguments
* $items **mixed**



### <a name="method-isColorUnavailable"></a>isColorUnavailable

    mixed ProductCore::isColorUnavailable($id_attribute, $id_shop)





* Visibility: **public**
* This method is defined in [classes/Product.php line 6073](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L6073)


#### Arguments
* $id_attribute **mixed**
* $id_shop **mixed**



### <a name="method-getColorsListCacheId"></a>getColorsListCacheId

    mixed ProductCore::getColorsListCacheId($id_product)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 6092](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L6092)


#### Arguments
* $id_product **mixed**



### <a name="method-setPackStockType"></a>setPackStockType

    mixed ProductCore::setPackStockType($id_product, $pack_stock_type)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Product.php line 6097](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Product.php#L6097)


#### Arguments
* $id_product **mixed**
* $pack_stock_type **mixed**


