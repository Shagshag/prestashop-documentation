Class AdminProductsControllerCore
=====================





* Class name: AdminProductsControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminProductsController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L27)


Contents
--------


### Properties

* [$_category](#property-$_category)
* [$available_tabs](#property-$available_tabs)
* [$available_tabs_lang](#property-$available_tabs_lang)
* [$default_tab](#property-$default_tab)
* [$id_current_category](#property-$id_current_category)
* [$max_file_size](#property-$max_file_size)
* [$max_image_size](#property-$max_image_size)
* [$position_identifier](#property-$position_identifier)
* [$submitted_tabs](#property-$submitted_tabs)
* [$tab_display](#property-$tab_display)
* [$tab_display_module](#property-$tab_display_module)

### Methods

* [__construct](#method-__construct)
* [_applyTaxToEcotax](#method-_applyTaxToEcotax)
* [_cleanMetaKeywords](#method-_cleanMetaKeywords)
* [_displayDraftWarning](#method-_displayDraftWarning)
* [_displayLabelField](#method-_displayLabelField)
* [_displayLabelFields](#method-_displayLabelFields)
* [_displaySpecificPriceModificationForm](#method-_displaySpecificPriceModificationForm)
* [_displayUnavailableProductWarning](#method-_displayUnavailableProductWarning)
* [_getCustomizationFieldIds](#method-_getCustomizationFieldIds)
* [_getFinalPrice](#method-_getFinalPrice)
* [_removeTaxFromEcotax](#method-_removeTaxFromEcotax)
* [_validateSpecificPrice](#method-_validateSpecificPrice)
* [addCarriers](#method-addCarriers)
* [addProductImage](#method-addProductImage)
* [ajaxPreProcess](#method-ajaxPreProcess)
* [ajaxProcessCheckProductName](#method-ajaxProcessCheckProductName)
* [ajaxProcessDefaultProductAttribute](#method-ajaxProcessDefaultProductAttribute)
* [ajaxProcessDeleteProductAttribute](#method-ajaxProcessDeleteProductAttribute)
* [ajaxProcessDeleteProductImage](#method-ajaxProcessDeleteProductImage)
* [ajaxProcessDeleteSpecificPrice](#method-ajaxProcessDeleteSpecificPrice)
* [ajaxProcessDeleteVirtualProduct](#method-ajaxProcessDeleteVirtualProduct)
* [ajaxProcessEditProductAttribute](#method-ajaxProcessEditProductAttribute)
* [ajaxProcessGetCountriesOptions](#method-ajaxProcessGetCountriesOptions)
* [ajaxProcessGetCurrenciesOptions](#method-ajaxProcessGetCurrenciesOptions)
* [ajaxProcessGetGroupsOptions](#method-ajaxProcessGetGroupsOptions)
* [ajaxProcessProductManufacturers](#method-ajaxProcessProductManufacturers)
* [ajaxProcessProductQuantity](#method-ajaxProcessProductQuantity)
* [ajaxProcessPublishProduct](#method-ajaxProcessPublishProduct)
* [ajaxProcessUpdateCover](#method-ajaxProcessUpdateCover)
* [ajaxProcessUpdateImagePosition](#method-ajaxProcessUpdateImagePosition)
* [ajaxProcessUpdatePositions](#method-ajaxProcessUpdatePositions)
* [ajaxProcessUpdateProductImageShopAsso](#method-ajaxProcessUpdateProductImageShopAsso)
* [ajaxProcessaddProductImage](#method-ajaxProcessaddProductImage)
* [checkFeatures](#method-checkFeatures)
* [checkProduct](#method-checkProduct)
* [copyFromPost](#method-copyFromPost)
* [copyImage](#method-copyImage)
* [getCarrierList](#method-getCarrierList)
* [getCombinationImagesJS](#method-getCombinationImagesJS)
* [getL](#method-getL)
* [getList](#method-getList)
* [getPackItems](#method-getPackItems)
* [getPreviewUrl](#method-getPreviewUrl)
* [haveThisAccessory](#method-haveThisAccessory)
* [initContent](#method-initContent)
* [initFormAssociations](#method-initFormAssociations)
* [initFormAttachments](#method-initFormAttachments)
* [initFormAttributes](#method-initFormAttributes)
* [initFormCombinations](#method-initFormCombinations)
* [initFormCustomization](#method-initFormCustomization)
* [initFormFeatures](#method-initFormFeatures)
* [initFormImages](#method-initFormImages)
* [initFormInformations](#method-initFormInformations)
* [initFormModules](#method-initFormModules)
* [initFormPack](#method-initFormPack)
* [initFormPrices](#method-initFormPrices)
* [initFormQuantities](#method-initFormQuantities)
* [initFormSeo](#method-initFormSeo)
* [initFormShipping](#method-initFormShipping)
* [initFormSuppliers](#method-initFormSuppliers)
* [initFormVirtualProduct](#method-initFormVirtualProduct)
* [initFormWarehouses](#method-initFormWarehouses)
* [initPack](#method-initPack)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [initToolbar](#method-initToolbar)
* [isProductFieldUpdated](#method-isProductFieldUpdated)
* [isTabSubmitted](#method-isTabSubmitted)
* [loadObject](#method-loadObject)
* [postProcess](#method-postProcess)
* [processAdd](#method-processAdd)
* [processAddAttachments](#method-processAddAttachments)
* [processAttachments](#method-processAttachments)
* [processBulkDelete](#method-processBulkDelete)
* [processCustomizationConfiguration](#method-processCustomizationConfiguration)
* [processDelete](#method-processDelete)
* [processDuplicate](#method-processDuplicate)
* [processFeatures](#method-processFeatures)
* [processImage](#method-processImage)
* [processPosition](#method-processPosition)
* [processPriceAddition](#method-processPriceAddition)
* [processPricesModification](#method-processPricesModification)
* [processProductAttribute](#method-processProductAttribute)
* [processProductCustomization](#method-processProductCustomization)
* [processSpecificPricePriorities](#method-processSpecificPricePriorities)
* [processStatus](#method-processStatus)
* [processSuppliers](#method-processSuppliers)
* [processUpdate](#method-processUpdate)
* [processWarehouses](#method-processWarehouses)
* [recurseCategoryForInclude](#method-recurseCategoryForInclude)
* [renderForm](#method-renderForm)
* [renderKpis](#method-renderKpis)
* [renderList](#method-renderList)
* [renderListAttributes](#method-renderListAttributes)
* [updateAccessories](#method-updateAccessories)
* [updateAssoShop](#method-updateAssoShop)
* [updateDownloadProduct](#method-updateDownloadProduct)
* [updatePackItems](#method-updatePackItems)
* [updateTags](#method-updateTags)




Properties
----------


### <a name="property-$_category"></a>$_category

```php
protected mixed $_category
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L35).


### <a name="property-$available_tabs"></a>$available_tabs

```php
protected array $available_tabs = array()
```

The order in the array decides the order in the list of tab. If an element's value is a number, it will be preloaded.

The tabs are preloaded from the smallest to the highest number.

* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L47).


### <a name="property-$available_tabs_lang"></a>$available_tabs_lang

```php
protected mixed $available_tabs_lang = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L51).


### <a name="property-$default_tab"></a>$default_tab

```php
protected mixed $default_tab = 'Informations'
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L49).


### <a name="property-$id_current_category"></a>$id_current_category

```php
protected mixed $id_current_category
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L57).


### <a name="property-$max_file_size"></a>$max_file_size

```php
protected integer $max_file_size = null
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L32).


### <a name="property-$max_image_size"></a>$max_image_size

```php
protected mixed $max_image_size = null
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L33).


### <a name="property-$position_identifier"></a>$position_identifier

```php
protected mixed $position_identifier = 'id_product'
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L53).


### <a name="property-$submitted_tabs"></a>$submitted_tabs

```php
protected mixed $submitted_tabs
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L55).


### <a name="property-$tab_display"></a>$tab_display

```php
protected string $tab_display
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L39).


### <a name="property-$tab_display_module"></a>$tab_display_module

```php
protected mixed $tab_display_module
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L40).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminProductsControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L59)




### <a name="method-_applyTaxToEcotax"></a>_applyTaxToEcotax

```php
mixed AdminProductsControllerCore::_applyTaxToEcotax($product)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 2054](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L2054)


#### Arguments
* $product **mixed**



### <a name="method-_cleanMetaKeywords"></a>_cleanMetaKeywords

```php
mixed AdminProductsControllerCore::_cleanMetaKeywords($keywords)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 271](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L271)


#### Arguments
* $keywords **mixed**



### <a name="method-_displayDraftWarning"></a>_displayDraftWarning

```php
mixed AdminProductsControllerCore::_displayDraftWarning($active)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 2391](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L2391)


#### Arguments
* $active **mixed**



### <a name="method-_displayLabelField"></a>_displayLabelField

```php
mixed AdminProductsControllerCore::_displayLabelField($label, $languages, $default_language, $type, $fieldIds, $id_customization_field)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3371](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L3371)


#### Arguments
* $label **mixed**
* $languages **mixed**
* $default_language **mixed**
* $type **mixed**
* $fieldIds **mixed**
* $id_customization_field **mixed**



### <a name="method-_displayLabelFields"></a>_displayLabelFields

```php
mixed AdminProductsControllerCore::_displayLabelFields($obj, $labels, $languages, $default_language, $type)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3390](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L3390)


#### Arguments
* $obj **mixed**
* $labels **mixed**
* $languages **mixed**
* $default_language **mixed**
* $type **mixed**



### <a name="method-_displaySpecificPriceModificationForm"></a>_displaySpecificPriceModificationForm

```php
mixed AdminProductsControllerCore::_displaySpecificPriceModificationForm($defaultCurrency, $shops, $currencies, $countries, $groups)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3165](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L3165)


#### Arguments
* $defaultCurrency **mixed**
* $shops **mixed**
* $currencies **mixed**
* $countries **mixed**
* $groups **mixed**



### <a name="method-_displayUnavailableProductWarning"></a>_displayUnavailableProductWarning

```php
mixed AdminProductsControllerCore::_displayUnavailableProductWarning()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 4450](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L4450)




### <a name="method-_getCustomizationFieldIds"></a>_getCustomizationFieldIds

```php
mixed AdminProductsControllerCore::_getCustomizationFieldIds($labels, $alreadyGenerated, $obj)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3353](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L3353)


#### Arguments
* $labels **mixed**
* $alreadyGenerated **mixed**
* $obj **mixed**



### <a name="method-_getFinalPrice"></a>_getFinalPrice

```php
mixed AdminProductsControllerCore::_getFinalPrice($specific_price, $product_price, $tax_rate)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3160](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L3160)


#### Arguments
* $specific_price **mixed**
* $product_price **mixed**
* $tax_rate **mixed**



### <a name="method-_removeTaxFromEcotax"></a>_removeTaxFromEcotax

```php
mixed AdminProductsControllerCore::_removeTaxFromEcotax()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 2047](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L2047)




### <a name="method-_validateSpecificPrice"></a>_validateSpecificPrice

```php
mixed AdminProductsControllerCore::_validateSpecificPrice($id_shop, $id_currency, $id_country, $id_group, $id_customer, $price, $from_quantity, $reduction, $reduction_type, $from, $to, $id_combination)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1546](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L1546)


#### Arguments
* $id_shop **mixed**
* $id_currency **mixed**
* $id_country **mixed**
* $id_group **mixed**
* $id_customer **mixed**
* $price **mixed**
* $from_quantity **mixed**
* $reduction **mixed**
* $reduction_type **mixed**
* $from **mixed**
* $to **mixed**
* $id_combination **mixed**



### <a name="method-addCarriers"></a>addCarriers

```php
mixed AdminProductsControllerCore::addCarriers()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3598](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L3598)




### <a name="method-addProductImage"></a>addProductImage

```php
mixed AdminProductsControllerCore::addProductImage(object $product, $method)
```

Add or update a product image



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1601](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L1601)


#### Arguments
* $product **object** - Product object to add image
* $method **mixed**



### <a name="method-ajaxPreProcess"></a>ajaxPreProcess

```php
mixed AdminProductsControllerCore::ajaxPreProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1420](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L1420)




### <a name="method-ajaxProcessCheckProductName"></a>ajaxProcessCheckProductName

```php
mixed AdminProductsControllerCore::ajaxProcessCheckProductName()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4460](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L4460)




### <a name="method-ajaxProcessDefaultProductAttribute"></a>ajaxProcessDefaultProductAttribute

```php
mixed AdminProductsControllerCore::ajaxProcessDefaultProductAttribute()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1377](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L1377)




### <a name="method-ajaxProcessDeleteProductAttribute"></a>ajaxProcessDeleteProductAttribute

```php
mixed AdminProductsControllerCore::ajaxProcessDeleteProductAttribute()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1336](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L1336)




### <a name="method-ajaxProcessDeleteProductImage"></a>ajaxProcessDeleteProductImage

```php
mixed AdminProductsControllerCore::ajaxProcessDeleteProductImage()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1509](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L1509)




### <a name="method-ajaxProcessDeleteSpecificPrice"></a>ajaxProcessDeleteSpecificPrice

```php
mixed AdminProductsControllerCore::ajaxProcessDeleteSpecificPrice()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1022](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L1022)




### <a name="method-ajaxProcessDeleteVirtualProduct"></a>ajaxProcessDeleteVirtualProduct

```php
mixed AdminProductsControllerCore::ajaxProcessDeleteVirtualProduct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 433](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L433)




### <a name="method-ajaxProcessEditProductAttribute"></a>ajaxProcessEditProductAttribute

```php
mixed AdminProductsControllerCore::ajaxProcessEditProductAttribute()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1403](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L1403)




### <a name="method-ajaxProcessGetCountriesOptions"></a>ajaxProcessGetCountriesOptions

```php
mixed AdminProductsControllerCore::ajaxProcessGetCountriesOptions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 385](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L385)




### <a name="method-ajaxProcessGetCurrenciesOptions"></a>ajaxProcessGetCurrenciesOptions

```php
mixed AdminProductsControllerCore::ajaxProcessGetCurrenciesOptions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 401](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L401)




### <a name="method-ajaxProcessGetGroupsOptions"></a>ajaxProcessGetGroupsOptions

```php
mixed AdminProductsControllerCore::ajaxProcessGetGroupsOptions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 417](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L417)




### <a name="method-ajaxProcessProductManufacturers"></a>ajaxProcessProductManufacturers

```php
mixed AdminProductsControllerCore::ajaxProcessProductManufacturers()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2335](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L2335)




### <a name="method-ajaxProcessProductQuantity"></a>ajaxProcessProductQuantity

```php
mixed AdminProductsControllerCore::ajaxProcessProductQuantity()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4289](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L4289)




### <a name="method-ajaxProcessPublishProduct"></a>ajaxProcessPublishProduct

```php
mixed AdminProductsControllerCore::ajaxProcessPublishProduct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4518](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L4518)




### <a name="method-ajaxProcessUpdateCover"></a>ajaxProcessUpdateCover

```php
mixed AdminProductsControllerCore::ajaxProcessUpdateCover()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1494](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L1494)




### <a name="method-ajaxProcessUpdateImagePosition"></a>ajaxProcessUpdateImagePosition

```php
mixed AdminProductsControllerCore::ajaxProcessUpdateImagePosition()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1473](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L1473)




### <a name="method-ajaxProcessUpdatePositions"></a>ajaxProcessUpdatePositions

```php
mixed AdminProductsControllerCore::ajaxProcessUpdatePositions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4483](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L4483)




### <a name="method-ajaxProcessUpdateProductImageShopAsso"></a>ajaxProcessUpdateProductImageShopAsso

```php
mixed AdminProductsControllerCore::ajaxProcessUpdateProductImageShopAsso()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1429](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L1429)




### <a name="method-ajaxProcessaddProductImage"></a>ajaxProcessaddProductImage

```php
mixed AdminProductsControllerCore::ajaxProcessaddProductImage()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3611](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L3611)




### <a name="method-checkFeatures"></a>checkFeatures

```php
mixed AdminProductsControllerCore::checkFeatures($languages, $feature_id)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1566](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L1566)


#### Arguments
* $languages **mixed**
* $feature_id **mixed**



### <a name="method-checkProduct"></a>checkProduct

```php
mixed AdminProductsControllerCore::checkProduct()
```

Check that a saved product is valid



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1896](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L1896)




### <a name="method-copyFromPost"></a>copyFromPost

```php
mixed AdminProductsControllerCore::copyFromPost($object, $table)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 289](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L289)


#### Arguments
* $object **mixed**
* $table **mixed**



### <a name="method-copyImage"></a>copyImage

```php
mixed AdminProductsControllerCore::copyImage(integer $id_product, integer $id_image, $method)
```

Copy a product image



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1636](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L1636)


#### Arguments
* $id_product **integer** - Product Id for product image filename
* $id_image **integer** - Image Id for product image filename
* $method **mixed**



### <a name="method-getCarrierList"></a>getCarrierList

```php
mixed AdminProductsControllerCore::getCarrierList()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3581](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L3581)




### <a name="method-getCombinationImagesJS"></a>getCombinationImagesJS

```php
mixed AdminProductsControllerCore::getCombinationImagesJS()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4346](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L4346)




### <a name="method-getL"></a>getL

```php
mixed AdminProductsControllerCore::getL($key)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4437](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L4437)


#### Arguments
* $key **mixed**



### <a name="method-getList"></a>getList

```php
mixed AdminProductsControllerCore::getList($id_lang, $orderBy, $orderWay, $start, $limit, $id_lang_shop)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 319](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L319)


#### Arguments
* $id_lang **mixed**
* $orderBy **mixed**
* $orderWay **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### <a name="method-getPackItems"></a>getPackItems

```php
array AdminProductsControllerCore::getPackItems(\Product $product)
```

Get an array of pack items for display from the product object if specified, else from POST/GET values



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3038](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L3038)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-getPreviewUrl"></a>getPreviewUrl

```php
mixed AdminProductsControllerCore::getPreviewUrl(\Product $product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2608](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L2608)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-haveThisAccessory"></a>haveThisAccessory

```php
mixed AdminProductsControllerCore::haveThisAccessory($accessory_id, $accessories)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4364](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L4364)


#### Arguments
* $accessory_id **mixed**
* $accessories **mixed**



### <a name="method-initContent"></a>initContent

```php
mixed AdminProductsControllerCore::initContent($token)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2185](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L2185)


#### Arguments
* $token **mixed**



### <a name="method-initFormAssociations"></a>initFormAssociations

```php
mixed AdminProductsControllerCore::initFormAssociations($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2870](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L2870)


#### Arguments
* $obj **mixed**



### <a name="method-initFormAttachments"></a>initFormAttachments

```php
mixed AdminProductsControllerCore::initFormAttachments($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3437](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L3437)


#### Arguments
* $obj **mixed**



### <a name="method-initFormAttributes"></a>initFormAttributes

```php
mixed AdminProductsControllerCore::initFormAttributes($product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3793](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L3793)


#### Arguments
* $product **mixed**



### <a name="method-initFormCombinations"></a>initFormCombinations

```php
mixed AdminProductsControllerCore::initFormCombinations($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3788](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L3788)


#### Arguments
* $obj **mixed**



### <a name="method-initFormCustomization"></a>initFormCustomization

```php
mixed AdminProductsControllerCore::initFormCustomization($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3403](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L3403)


#### Arguments
* $obj **mixed**



### <a name="method-initFormFeatures"></a>initFormFeatures

```php
mixed AdminProductsControllerCore::initFormFeatures($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4240](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L4240)


#### Arguments
* $obj **mixed**



### <a name="method-initFormImages"></a>initFormImages

```php
mixed AdminProductsControllerCore::initFormImages($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3713](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L3713)


#### Arguments
* $obj **mixed**



### <a name="method-initFormInformations"></a>initFormInformations

```php
mixed AdminProductsControllerCore::initFormInformations($product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3481](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L3481)


#### Arguments
* $product **mixed**



### <a name="method-initFormModules"></a>initFormModules

```php
mixed AdminProductsControllerCore::initFormModules($obj)
```

AdminProducts display hook



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4398](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L4398)


#### Arguments
* $obj **mixed**



### <a name="method-initFormPack"></a>initFormPack

```php
mixed AdminProductsControllerCore::initFormPack($product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3079](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L3079)


#### Arguments
* $product **mixed**



### <a name="method-initFormPrices"></a>initFormPrices

```php
mixed AdminProductsControllerCore::initFormPrices($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2936](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L2936)


#### Arguments
* $obj **mixed**



### <a name="method-initFormQuantities"></a>initFormQuantities

```php
mixed AdminProductsControllerCore::initFormQuantities($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3966](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L3966)


#### Arguments
* $obj **mixed**



### <a name="method-initFormSeo"></a>initFormSeo

```php
mixed AdminProductsControllerCore::initFormSeo($product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3017](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L3017)


#### Arguments
* $product **mixed**



### <a name="method-initFormShipping"></a>initFormShipping

```php
mixed AdminProductsControllerCore::initFormShipping($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3567](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L3567)


#### Arguments
* $obj **mixed**



### <a name="method-initFormSuppliers"></a>initFormSuppliers

```php
mixed AdminProductsControllerCore::initFormSuppliers($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4112](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L4112)


#### Arguments
* $obj **mixed**



### <a name="method-initFormVirtualProduct"></a>initFormVirtualProduct

```php
mixed AdminProductsControllerCore::initFormVirtualProduct($product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3114](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L3114)


#### Arguments
* $product **mixed**



### <a name="method-initFormWarehouses"></a>initFormWarehouses

```php
mixed AdminProductsControllerCore::initFormWarehouses($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4190](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L4190)


#### Arguments
* $obj **mixed**



### <a name="method-initPack"></a>initPack

```php
mixed AdminProductsControllerCore::initPack(\Product $product)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 4372](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L4372)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminProductsControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2401](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L2401)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminProductsControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1134](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L1134)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminProductsControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2461](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L2461)




### <a name="method-isProductFieldUpdated"></a>isProductFieldUpdated

```php
boolean AdminProductsControllerCore::isProductFieldUpdated(string $field, integer $id_lang)
```

Check if a field is edited (if the checkbox is checked)
This method will do something only for multishop with a context all / group



* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 2031](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L2031)


#### Arguments
* $field **string** - Name of field
* $id_lang **integer**



### <a name="method-isTabSubmitted"></a>isTabSubmitted

```php
mixed AdminProductsControllerCore::isTabSubmitted($tab_name)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1735](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L1735)


#### Arguments
* $tab_name **mixed**



### <a name="method-loadObject"></a>loadObject

```php
mixed AdminProductsControllerCore::loadObject($opt)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 362](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L362)


#### Arguments
* $opt **mixed**



### <a name="method-postProcess"></a>postProcess

```php
void AdminProductsControllerCore::postProcess()
```

postProcess handle every checks before saving products information



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1286](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L1286)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminProductsControllerCore::processAdd()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1673](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L1673)




### <a name="method-processAddAttachments"></a>processAddAttachments

```php
void AdminProductsControllerCore::processAddAttachments()
```

Upload new attachment



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 452](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L452)




### <a name="method-processAttachments"></a>processAttachments

```php
void AdminProductsControllerCore::processAttachments()
```

Attach an existing attachment to the product



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 548](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L548)




### <a name="method-processBulkDelete"></a>processBulkDelete

```php
mixed AdminProductsControllerCore::processBulkDelete()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 693](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L693)




### <a name="method-processCustomizationConfiguration"></a>processCustomizationConfiguration

```php
mixed AdminProductsControllerCore::processCustomizationConfiguration()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1070](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L1070)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminProductsControllerCore::processDelete()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 608](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L608)




### <a name="method-processDuplicate"></a>processDuplicate

```php
mixed AdminProductsControllerCore::processDuplicate()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 559](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L559)




### <a name="method-processFeatures"></a>processFeatures

```php
mixed AdminProductsControllerCore::processFeatures()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 891](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L891)




### <a name="method-processImage"></a>processImage

```php
mixed AdminProductsControllerCore::processImage()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 650](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L650)




### <a name="method-processPosition"></a>processPosition

```php
mixed AdminProductsControllerCore::processPosition()
```

Overrides parent for custom redirect link



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1116](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L1116)




### <a name="method-processPriceAddition"></a>processPriceAddition

```php
mixed AdminProductsControllerCore::processPriceAddition()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 975](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L975)




### <a name="method-processPricesModification"></a>processPricesModification

```php
mixed AdminProductsControllerCore::processPricesModification()
```

This function is never called at the moment (specific prices cannot be edited)



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 933](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L933)




### <a name="method-processProductAttribute"></a>processProductAttribute

```php
mixed AdminProductsControllerCore::processProductAttribute()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 763](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L763)




### <a name="method-processProductCustomization"></a>processProductCustomization

```php
mixed AdminProductsControllerCore::processProductCustomization()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1097](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L1097)




### <a name="method-processSpecificPricePriorities"></a>processSpecificPricePriorities

```php
mixed AdminProductsControllerCore::processSpecificPricePriorities()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1053](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L1053)




### <a name="method-processStatus"></a>processStatus

```php
mixed AdminProductsControllerCore::processStatus()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1746](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L1746)




### <a name="method-processSuppliers"></a>processSuppliers

```php
mixed AdminProductsControllerCore::processSuppliers()
```

Post treatment for suppliers



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2640](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L2640)




### <a name="method-processUpdate"></a>processUpdate

```php
mixed AdminProductsControllerCore::processUpdate()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1759](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L1759)




### <a name="method-processWarehouses"></a>processWarehouses

```php
mixed AdminProductsControllerCore::processWarehouses()
```

Post treatment for warehouses



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2793](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L2793)




### <a name="method-recurseCategoryForInclude"></a>recurseCategoryForInclude

```php
mixed AdminProductsControllerCore::recurseCategoryForInclude($id_obj, array $indexedCategories, array $categories, array $current, integer $id_category, $id_category_default, $has_suite)
```

Build a categories tree



* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminProductsController.php line 2353](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L2353)


#### Arguments
* $id_obj **mixed**
* $indexedCategories **array** - Array with categories where product is indexed (in order to check checkbox)
* $categories **array** - Categories to list
* $current **array** - Current category
* $id_category **integer** - Current category id
* $id_category_default **mixed**
* $has_suite **mixed**



### <a name="method-renderForm"></a>renderForm

```php
void AdminProductsControllerCore::renderForm()
```

renderForm contains all necessary initialization needed for all tabs



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2496](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L2496)




### <a name="method-renderKpis"></a>renderKpis

```php
mixed AdminProductsControllerCore::renderKpis()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2267](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L2267)




### <a name="method-renderList"></a>renderList

```php
mixed AdminProductsControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2327](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L2327)




### <a name="method-renderListAttributes"></a>renderListAttributes

```php
mixed AdminProductsControllerCore::renderListAttributes($product, $currency)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3869](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L3869)


#### Arguments
* $product **mixed**
* $currency **mixed**



### <a name="method-updateAccessories"></a>updateAccessories

```php
mixed AdminProductsControllerCore::updateAccessories(object $product)
```

Update product accessories



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2147](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L2147)


#### Arguments
* $product **object** - Product



### <a name="method-updateAssoShop"></a>updateAssoShop

```php
mixed AdminProductsControllerCore::updateAssoShop($id_object)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1667](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L1667)


#### Arguments
* $id_object **mixed**



### <a name="method-updateDownloadProduct"></a>updateDownloadProduct

```php
boolean AdminProductsControllerCore::updateDownloadProduct(object $product, $edit)
```

Update product download



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2067](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L2067)


#### Arguments
* $product **object** - Product
* $edit **mixed**



### <a name="method-updatePackItems"></a>updatePackItems

```php
boolean AdminProductsControllerCore::updatePackItems(\Product $product)
```

delete all items in pack, then check if type_product value is 2.

if yes, add the pack items from input "inputPackItems"

* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4411](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L4411)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-updateTags"></a>updateTags

```php
boolean AdminProductsControllerCore::updateTags($languages, object $product)
```

Update product tags



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2168](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminProductsController.php#L2168)


#### Arguments
* $languages **mixed**
* $product **object** - Product


