Class AdminProductsControllerCore
=====================





* Class name: AdminProductsControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminProductsController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L27)


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
* [ajaxProcessAddAttachment](#method-ajaxProcessAddAttachment)
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
* [setMedia](#method-setMedia)
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
* Source: [controllers/admin/AdminProductsController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L35).


### <a name="property-$available_tabs"></a>$available_tabs

```php
protected array $available_tabs = array()
```

The order in the array decides the order in the list of tab. If an element's value is a number, it will be preloaded.

The tabs are preloaded from the smallest to the highest number.

* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L47).


### <a name="property-$available_tabs_lang"></a>$available_tabs_lang

```php
protected mixed $available_tabs_lang = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L51).


### <a name="property-$default_tab"></a>$default_tab

```php
protected mixed $default_tab = 'Informations'
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L49).


### <a name="property-$id_current_category"></a>$id_current_category

```php
protected mixed $id_current_category
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L57).


### <a name="property-$max_file_size"></a>$max_file_size

```php
protected integer $max_file_size = null
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L32).


### <a name="property-$max_image_size"></a>$max_image_size

```php
protected mixed $max_image_size = null
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L33).


### <a name="property-$position_identifier"></a>$position_identifier

```php
protected mixed $position_identifier = 'id_product'
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L53).


### <a name="property-$submitted_tabs"></a>$submitted_tabs

```php
protected mixed $submitted_tabs
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L55).


### <a name="property-$tab_display"></a>$tab_display

```php
protected string $tab_display
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L39).


### <a name="property-$tab_display_module"></a>$tab_display_module

```php
protected mixed $tab_display_module
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L40).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminProductsControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L59)




### <a name="method-_applyTaxToEcotax"></a>_applyTaxToEcotax

```php
mixed AdminProductsControllerCore::_applyTaxToEcotax($product)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 2092](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L2092)


#### Arguments
* $product **mixed**



### <a name="method-_cleanMetaKeywords"></a>_cleanMetaKeywords

```php
mixed AdminProductsControllerCore::_cleanMetaKeywords($keywords)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 293](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L293)


#### Arguments
* $keywords **mixed**



### <a name="method-_displayDraftWarning"></a>_displayDraftWarning

```php
mixed AdminProductsControllerCore::_displayDraftWarning($active)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 2429](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L2429)


#### Arguments
* $active **mixed**



### <a name="method-_displayLabelField"></a>_displayLabelField

```php
mixed AdminProductsControllerCore::_displayLabelField($label, $languages, $default_language, $type, $fieldIds, $id_customization_field)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3420](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L3420)


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
* Source: [controllers/admin/AdminProductsController.php line 3439](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L3439)


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
* Source: [controllers/admin/AdminProductsController.php line 3214](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L3214)


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
* Source: [controllers/admin/AdminProductsController.php line 4504](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L4504)




### <a name="method-_getCustomizationFieldIds"></a>_getCustomizationFieldIds

```php
mixed AdminProductsControllerCore::_getCustomizationFieldIds($labels, $alreadyGenerated, $obj)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3402](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L3402)


#### Arguments
* $labels **mixed**
* $alreadyGenerated **mixed**
* $obj **mixed**



### <a name="method-_getFinalPrice"></a>_getFinalPrice

```php
mixed AdminProductsControllerCore::_getFinalPrice($specific_price, $product_price, $tax_rate)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3209](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L3209)


#### Arguments
* $specific_price **mixed**
* $product_price **mixed**
* $tax_rate **mixed**



### <a name="method-_removeTaxFromEcotax"></a>_removeTaxFromEcotax

```php
mixed AdminProductsControllerCore::_removeTaxFromEcotax()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 2085](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L2085)




### <a name="method-_validateSpecificPrice"></a>_validateSpecificPrice

```php
mixed AdminProductsControllerCore::_validateSpecificPrice($id_shop, $id_currency, $id_country, $id_group, $id_customer, $price, $from_quantity, $reduction, $reduction_type, $from, $to, $id_combination)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1578](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L1578)


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
* Source: [controllers/admin/AdminProductsController.php line 3654](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L3654)




### <a name="method-addProductImage"></a>addProductImage

```php
mixed AdminProductsControllerCore::addProductImage(object $product, $method)
```

Add or update a product image



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1633](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L1633)


#### Arguments
* $product **object** - Product object to add image
* $method **mixed**



### <a name="method-ajaxPreProcess"></a>ajaxPreProcess

```php
mixed AdminProductsControllerCore::ajaxPreProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1452](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L1452)




### <a name="method-ajaxProcessAddAttachment"></a>ajaxProcessAddAttachment

```php
mixed AdminProductsControllerCore::ajaxProcessAddAttachment()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 469](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L469)




### <a name="method-ajaxProcessCheckProductName"></a>ajaxProcessCheckProductName

```php
mixed AdminProductsControllerCore::ajaxProcessCheckProductName()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4514](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L4514)




### <a name="method-ajaxProcessDefaultProductAttribute"></a>ajaxProcessDefaultProductAttribute

```php
mixed AdminProductsControllerCore::ajaxProcessDefaultProductAttribute()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1409](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L1409)




### <a name="method-ajaxProcessDeleteProductAttribute"></a>ajaxProcessDeleteProductAttribute

```php
mixed AdminProductsControllerCore::ajaxProcessDeleteProductAttribute()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1368](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L1368)




### <a name="method-ajaxProcessDeleteProductImage"></a>ajaxProcessDeleteProductImage

```php
mixed AdminProductsControllerCore::ajaxProcessDeleteProductImage()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1541](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L1541)




### <a name="method-ajaxProcessDeleteSpecificPrice"></a>ajaxProcessDeleteSpecificPrice

```php
mixed AdminProductsControllerCore::ajaxProcessDeleteSpecificPrice()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1069](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L1069)




### <a name="method-ajaxProcessDeleteVirtualProduct"></a>ajaxProcessDeleteVirtualProduct

```php
mixed AdminProductsControllerCore::ajaxProcessDeleteVirtualProduct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 455](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L455)




### <a name="method-ajaxProcessEditProductAttribute"></a>ajaxProcessEditProductAttribute

```php
mixed AdminProductsControllerCore::ajaxProcessEditProductAttribute()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1435](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L1435)




### <a name="method-ajaxProcessGetCountriesOptions"></a>ajaxProcessGetCountriesOptions

```php
mixed AdminProductsControllerCore::ajaxProcessGetCountriesOptions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 407](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L407)




### <a name="method-ajaxProcessGetCurrenciesOptions"></a>ajaxProcessGetCurrenciesOptions

```php
mixed AdminProductsControllerCore::ajaxProcessGetCurrenciesOptions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 423](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L423)




### <a name="method-ajaxProcessGetGroupsOptions"></a>ajaxProcessGetGroupsOptions

```php
mixed AdminProductsControllerCore::ajaxProcessGetGroupsOptions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 439](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L439)




### <a name="method-ajaxProcessProductManufacturers"></a>ajaxProcessProductManufacturers

```php
mixed AdminProductsControllerCore::ajaxProcessProductManufacturers()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2373](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L2373)




### <a name="method-ajaxProcessProductQuantity"></a>ajaxProcessProductQuantity

```php
mixed AdminProductsControllerCore::ajaxProcessProductQuantity()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4343](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L4343)




### <a name="method-ajaxProcessPublishProduct"></a>ajaxProcessPublishProduct

```php
mixed AdminProductsControllerCore::ajaxProcessPublishProduct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4572](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L4572)




### <a name="method-ajaxProcessUpdateCover"></a>ajaxProcessUpdateCover

```php
mixed AdminProductsControllerCore::ajaxProcessUpdateCover()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1526](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L1526)




### <a name="method-ajaxProcessUpdateImagePosition"></a>ajaxProcessUpdateImagePosition

```php
mixed AdminProductsControllerCore::ajaxProcessUpdateImagePosition()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1505](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L1505)




### <a name="method-ajaxProcessUpdatePositions"></a>ajaxProcessUpdatePositions

```php
mixed AdminProductsControllerCore::ajaxProcessUpdatePositions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4537](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L4537)




### <a name="method-ajaxProcessUpdateProductImageShopAsso"></a>ajaxProcessUpdateProductImageShopAsso

```php
mixed AdminProductsControllerCore::ajaxProcessUpdateProductImageShopAsso()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1461](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L1461)




### <a name="method-ajaxProcessaddProductImage"></a>ajaxProcessaddProductImage

```php
mixed AdminProductsControllerCore::ajaxProcessaddProductImage()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3667](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L3667)




### <a name="method-checkFeatures"></a>checkFeatures

```php
mixed AdminProductsControllerCore::checkFeatures($languages, $feature_id)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1598](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L1598)


#### Arguments
* $languages **mixed**
* $feature_id **mixed**



### <a name="method-checkProduct"></a>checkProduct

```php
mixed AdminProductsControllerCore::checkProduct()
```

Check that a saved product is valid



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1934](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L1934)




### <a name="method-copyFromPost"></a>copyFromPost

```php
mixed AdminProductsControllerCore::copyFromPost($object, $table)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 311](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L311)


#### Arguments
* $object **mixed**
* $table **mixed**



### <a name="method-copyImage"></a>copyImage

```php
mixed AdminProductsControllerCore::copyImage(integer $id_product, integer $id_image, $method)
```

Copy a product image



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1668](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L1668)


#### Arguments
* $id_product **integer** - Product Id for product image filename
* $id_image **integer** - Image Id for product image filename
* $method **mixed**



### <a name="method-getCarrierList"></a>getCarrierList

```php
mixed AdminProductsControllerCore::getCarrierList()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3637](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L3637)




### <a name="method-getCombinationImagesJS"></a>getCombinationImagesJS

```php
mixed AdminProductsControllerCore::getCombinationImagesJS()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4400](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L4400)




### <a name="method-getL"></a>getL

```php
mixed AdminProductsControllerCore::getL($key)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4491](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L4491)


#### Arguments
* $key **mixed**



### <a name="method-getList"></a>getList

```php
mixed AdminProductsControllerCore::getList($id_lang, $orderBy, $orderWay, $start, $limit, $id_lang_shop)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 341](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L341)


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
* Source: [controllers/admin/AdminProductsController.php line 3087](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L3087)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-getPreviewUrl"></a>getPreviewUrl

```php
mixed AdminProductsControllerCore::getPreviewUrl(\Product $product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2653](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L2653)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-haveThisAccessory"></a>haveThisAccessory

```php
mixed AdminProductsControllerCore::haveThisAccessory($accessory_id, $accessories)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4418](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L4418)


#### Arguments
* $accessory_id **mixed**
* $accessories **mixed**



### <a name="method-initContent"></a>initContent

```php
mixed AdminProductsControllerCore::initContent($token)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2223](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L2223)


#### Arguments
* $token **mixed**



### <a name="method-initFormAssociations"></a>initFormAssociations

```php
mixed AdminProductsControllerCore::initFormAssociations($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2919](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L2919)


#### Arguments
* $obj **mixed**



### <a name="method-initFormAttachments"></a>initFormAttachments

```php
mixed AdminProductsControllerCore::initFormAttachments($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3486](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L3486)


#### Arguments
* $obj **mixed**



### <a name="method-initFormAttributes"></a>initFormAttributes

```php
mixed AdminProductsControllerCore::initFormAttributes($product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3847](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L3847)


#### Arguments
* $product **mixed**



### <a name="method-initFormCombinations"></a>initFormCombinations

```php
mixed AdminProductsControllerCore::initFormCombinations($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3842](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L3842)


#### Arguments
* $obj **mixed**



### <a name="method-initFormCustomization"></a>initFormCustomization

```php
mixed AdminProductsControllerCore::initFormCustomization($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3452](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L3452)


#### Arguments
* $obj **mixed**



### <a name="method-initFormFeatures"></a>initFormFeatures

```php
mixed AdminProductsControllerCore::initFormFeatures($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4294](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L4294)


#### Arguments
* $obj **mixed**



### <a name="method-initFormImages"></a>initFormImages

```php
mixed AdminProductsControllerCore::initFormImages($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3767](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L3767)


#### Arguments
* $obj **mixed**



### <a name="method-initFormInformations"></a>initFormInformations

```php
mixed AdminProductsControllerCore::initFormInformations($product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3537](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L3537)


#### Arguments
* $product **mixed**



### <a name="method-initFormModules"></a>initFormModules

```php
mixed AdminProductsControllerCore::initFormModules($obj)
```

AdminProducts display hook



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4452](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L4452)


#### Arguments
* $obj **mixed**



### <a name="method-initFormPack"></a>initFormPack

```php
mixed AdminProductsControllerCore::initFormPack($product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3128](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L3128)


#### Arguments
* $product **mixed**



### <a name="method-initFormPrices"></a>initFormPrices

```php
mixed AdminProductsControllerCore::initFormPrices($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2985](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L2985)


#### Arguments
* $obj **mixed**



### <a name="method-initFormQuantities"></a>initFormQuantities

```php
mixed AdminProductsControllerCore::initFormQuantities($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4020](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L4020)


#### Arguments
* $obj **mixed**



### <a name="method-initFormSeo"></a>initFormSeo

```php
mixed AdminProductsControllerCore::initFormSeo($product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3066](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L3066)


#### Arguments
* $product **mixed**



### <a name="method-initFormShipping"></a>initFormShipping

```php
mixed AdminProductsControllerCore::initFormShipping($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3623](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L3623)


#### Arguments
* $obj **mixed**



### <a name="method-initFormSuppliers"></a>initFormSuppliers

```php
mixed AdminProductsControllerCore::initFormSuppliers($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4166](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L4166)


#### Arguments
* $obj **mixed**



### <a name="method-initFormVirtualProduct"></a>initFormVirtualProduct

```php
mixed AdminProductsControllerCore::initFormVirtualProduct($product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3163](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L3163)


#### Arguments
* $product **mixed**



### <a name="method-initFormWarehouses"></a>initFormWarehouses

```php
mixed AdminProductsControllerCore::initFormWarehouses($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4244](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L4244)


#### Arguments
* $obj **mixed**



### <a name="method-initPack"></a>initPack

```php
mixed AdminProductsControllerCore::initPack(\Product $product)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 4426](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L4426)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminProductsControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2439](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L2439)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminProductsControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1181](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L1181)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminProductsControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2499](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L2499)




### <a name="method-isProductFieldUpdated"></a>isProductFieldUpdated

```php
boolean AdminProductsControllerCore::isProductFieldUpdated(string $field, integer $id_lang)
```

Check if a field is edited (if the checkbox is checked)
This method will do something only for multishop with a context all / group



* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 2069](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L2069)


#### Arguments
* $field **string** - Name of field
* $id_lang **integer**



### <a name="method-isTabSubmitted"></a>isTabSubmitted

```php
mixed AdminProductsControllerCore::isTabSubmitted($tab_name)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1767](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L1767)


#### Arguments
* $tab_name **mixed**



### <a name="method-loadObject"></a>loadObject

```php
mixed AdminProductsControllerCore::loadObject($opt)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 384](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L384)


#### Arguments
* $opt **mixed**



### <a name="method-postProcess"></a>postProcess

```php
void AdminProductsControllerCore::postProcess()
```

postProcess handle every checks before saving products information



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1321](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L1321)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminProductsControllerCore::processAdd()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1705](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L1705)




### <a name="method-processAttachments"></a>processAttachments

```php
void AdminProductsControllerCore::processAttachments()
```

Attach an existing attachment to the product



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 595](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L595)




### <a name="method-processBulkDelete"></a>processBulkDelete

```php
mixed AdminProductsControllerCore::processBulkDelete()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 740](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L740)




### <a name="method-processCustomizationConfiguration"></a>processCustomizationConfiguration

```php
mixed AdminProductsControllerCore::processCustomizationConfiguration()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1117](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L1117)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminProductsControllerCore::processDelete()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 655](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L655)




### <a name="method-processDuplicate"></a>processDuplicate

```php
mixed AdminProductsControllerCore::processDuplicate()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 606](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L606)




### <a name="method-processFeatures"></a>processFeatures

```php
mixed AdminProductsControllerCore::processFeatures()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 938](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L938)




### <a name="method-processImage"></a>processImage

```php
mixed AdminProductsControllerCore::processImage()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 697](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L697)




### <a name="method-processPosition"></a>processPosition

```php
mixed AdminProductsControllerCore::processPosition()
```

Overrides parent for custom redirect link



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1163](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L1163)




### <a name="method-processPriceAddition"></a>processPriceAddition

```php
mixed AdminProductsControllerCore::processPriceAddition()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1022](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L1022)




### <a name="method-processPricesModification"></a>processPricesModification

```php
mixed AdminProductsControllerCore::processPricesModification()
```

This function is never called at the moment (specific prices cannot be edited)



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 980](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L980)




### <a name="method-processProductAttribute"></a>processProductAttribute

```php
mixed AdminProductsControllerCore::processProductAttribute()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 810](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L810)




### <a name="method-processProductCustomization"></a>processProductCustomization

```php
mixed AdminProductsControllerCore::processProductCustomization()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1144](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L1144)




### <a name="method-processSpecificPricePriorities"></a>processSpecificPricePriorities

```php
mixed AdminProductsControllerCore::processSpecificPricePriorities()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1100](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L1100)




### <a name="method-processStatus"></a>processStatus

```php
mixed AdminProductsControllerCore::processStatus()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1778](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L1778)




### <a name="method-processSuppliers"></a>processSuppliers

```php
mixed AdminProductsControllerCore::processSuppliers()
```

Post treatment for suppliers



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2685](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L2685)




### <a name="method-processUpdate"></a>processUpdate

```php
mixed AdminProductsControllerCore::processUpdate()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1797](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L1797)




### <a name="method-processWarehouses"></a>processWarehouses

```php
mixed AdminProductsControllerCore::processWarehouses()
```

Post treatment for warehouses



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2842](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L2842)




### <a name="method-recurseCategoryForInclude"></a>recurseCategoryForInclude

```php
mixed AdminProductsControllerCore::recurseCategoryForInclude($id_obj, array $indexedCategories, array $categories, array $current, integer $id_category, $id_category_default, $has_suite)
```

Build a categories tree



* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminProductsController.php line 2391](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L2391)


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
* Source: [controllers/admin/AdminProductsController.php line 2539](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L2539)




### <a name="method-renderKpis"></a>renderKpis

```php
mixed AdminProductsControllerCore::renderKpis()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2305](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L2305)




### <a name="method-renderList"></a>renderList

```php
mixed AdminProductsControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2365](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L2365)




### <a name="method-renderListAttributes"></a>renderListAttributes

```php
mixed AdminProductsControllerCore::renderListAttributes($product, $currency)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3923](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L3923)


#### Arguments
* $product **mixed**
* $currency **mixed**



### <a name="method-setMedia"></a>setMedia

```php
mixed AdminProductsControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 271](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L271)




### <a name="method-updateAccessories"></a>updateAccessories

```php
mixed AdminProductsControllerCore::updateAccessories(object $product)
```

Update product accessories



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2185](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L2185)


#### Arguments
* $product **object** - Product



### <a name="method-updateAssoShop"></a>updateAssoShop

```php
mixed AdminProductsControllerCore::updateAssoShop($id_object)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1699](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L1699)


#### Arguments
* $id_object **mixed**



### <a name="method-updateDownloadProduct"></a>updateDownloadProduct

```php
boolean AdminProductsControllerCore::updateDownloadProduct(object $product, $edit)
```

Update product download



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2105](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L2105)


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
* Source: [controllers/admin/AdminProductsController.php line 4465](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L4465)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-updateTags"></a>updateTags

```php
boolean AdminProductsControllerCore::updateTags($languages, object $product)
```

Update product tags



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2206](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminProductsController.php#L2206)


#### Arguments
* $languages **mixed**
* $product **object** - Product


