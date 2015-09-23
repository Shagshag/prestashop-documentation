Class AdminProductsControllerCore
=====================





* Class name: AdminProductsControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminProductsController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L27)


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
* [getQuantities](#method-getQuantities)
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
* [processDeleteVirtualProduct](#method-processDeleteVirtualProduct)
* [processDuplicate](#method-processDuplicate)
* [processFeatures](#method-processFeatures)
* [processImage](#method-processImage)
* [processImageLegends](#method-processImageLegends)
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
* Source: [controllers/admin/AdminProductsController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L35).


### <a name="property-$available_tabs"></a>$available_tabs

```php
protected array $available_tabs = array()
```

The order in the array decides the order in the list of tab. If an element's value is a number, it will be preloaded.

The tabs are preloaded from the smallest to the highest number.

* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L47).


### <a name="property-$available_tabs_lang"></a>$available_tabs_lang

```php
protected mixed $available_tabs_lang = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L51).


### <a name="property-$default_tab"></a>$default_tab

```php
protected mixed $default_tab = 'Informations'
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L49).


### <a name="property-$id_current_category"></a>$id_current_category

```php
protected mixed $id_current_category
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L57).


### <a name="property-$max_file_size"></a>$max_file_size

```php
protected integer $max_file_size = null
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L32).


### <a name="property-$max_image_size"></a>$max_image_size

```php
protected mixed $max_image_size = null
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L33).


### <a name="property-$position_identifier"></a>$position_identifier

```php
protected mixed $position_identifier = 'id_product'
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L53).


### <a name="property-$submitted_tabs"></a>$submitted_tabs

```php
protected mixed $submitted_tabs
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L55).


### <a name="property-$tab_display"></a>$tab_display

```php
protected string $tab_display
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L39).


### <a name="property-$tab_display_module"></a>$tab_display_module

```php
protected mixed $tab_display_module
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L40).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminProductsControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L59)




### <a name="method-_applyTaxToEcotax"></a>_applyTaxToEcotax

```php
mixed AdminProductsControllerCore::_applyTaxToEcotax($product)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 2171](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L2171)


#### Arguments
* $product **mixed**



### <a name="method-_cleanMetaKeywords"></a>_cleanMetaKeywords

```php
mixed AdminProductsControllerCore::_cleanMetaKeywords($keywords)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 301](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L301)


#### Arguments
* $keywords **mixed**



### <a name="method-_displayDraftWarning"></a>_displayDraftWarning

```php
mixed AdminProductsControllerCore::_displayDraftWarning($active)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 2516](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L2516)


#### Arguments
* $active **mixed**



### <a name="method-_displayLabelField"></a>_displayLabelField

```php
mixed AdminProductsControllerCore::_displayLabelField($label, $languages, $default_language, $type, $fieldIds, $id_customization_field)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3596](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L3596)


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
* Source: [controllers/admin/AdminProductsController.php line 3624](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L3624)


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
* Source: [controllers/admin/AdminProductsController.php line 3367](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L3367)


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
* Source: [controllers/admin/AdminProductsController.php line 4741](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L4741)




### <a name="method-_getCustomizationFieldIds"></a>_getCustomizationFieldIds

```php
mixed AdminProductsControllerCore::_getCustomizationFieldIds($labels, $alreadyGenerated, $obj)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3578](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L3578)


#### Arguments
* $labels **mixed**
* $alreadyGenerated **mixed**
* $obj **mixed**



### <a name="method-_getFinalPrice"></a>_getFinalPrice

```php
mixed AdminProductsControllerCore::_getFinalPrice($specific_price, $product_price, $tax_rate)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3362](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L3362)


#### Arguments
* $specific_price **mixed**
* $product_price **mixed**
* $tax_rate **mixed**



### <a name="method-_removeTaxFromEcotax"></a>_removeTaxFromEcotax

```php
mixed AdminProductsControllerCore::_removeTaxFromEcotax()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 2165](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L2165)




### <a name="method-_validateSpecificPrice"></a>_validateSpecificPrice

```php
mixed AdminProductsControllerCore::_validateSpecificPrice($id_shop, $id_currency, $id_country, $id_group, $id_customer, $price, $from_quantity, $reduction, $reduction_type, $from, $to, $id_combination)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1629](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L1629)


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
mixed AdminProductsControllerCore::addCarriers($product)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3848](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L3848)


#### Arguments
* $product **mixed**



### <a name="method-addProductImage"></a>addProductImage

```php
mixed AdminProductsControllerCore::addProductImage(object $product, $method)
```

Add or update a product image



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1684](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L1684)


#### Arguments
* $product **object** - Product object to add image
* $method **mixed**



### <a name="method-ajaxPreProcess"></a>ajaxPreProcess

```php
mixed AdminProductsControllerCore::ajaxPreProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1503](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L1503)




### <a name="method-ajaxProcessAddAttachment"></a>ajaxProcessAddAttachment

```php
mixed AdminProductsControllerCore::ajaxProcessAddAttachment()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 486](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L486)




### <a name="method-ajaxProcessCheckProductName"></a>ajaxProcessCheckProductName

```php
mixed AdminProductsControllerCore::ajaxProcessCheckProductName()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4751](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L4751)




### <a name="method-ajaxProcessDefaultProductAttribute"></a>ajaxProcessDefaultProductAttribute

```php
mixed AdminProductsControllerCore::ajaxProcessDefaultProductAttribute()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1460](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L1460)




### <a name="method-ajaxProcessDeleteProductAttribute"></a>ajaxProcessDeleteProductAttribute

```php
mixed AdminProductsControllerCore::ajaxProcessDeleteProductAttribute()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1403](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L1403)




### <a name="method-ajaxProcessDeleteProductImage"></a>ajaxProcessDeleteProductImage

```php
mixed AdminProductsControllerCore::ajaxProcessDeleteProductImage()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1592](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L1592)




### <a name="method-ajaxProcessDeleteSpecificPrice"></a>ajaxProcessDeleteSpecificPrice

```php
mixed AdminProductsControllerCore::ajaxProcessDeleteSpecificPrice()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1090](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L1090)




### <a name="method-ajaxProcessEditProductAttribute"></a>ajaxProcessEditProductAttribute

```php
mixed AdminProductsControllerCore::ajaxProcessEditProductAttribute()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1486](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L1486)




### <a name="method-ajaxProcessGetCountriesOptions"></a>ajaxProcessGetCountriesOptions

```php
mixed AdminProductsControllerCore::ajaxProcessGetCountriesOptions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 420](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L420)




### <a name="method-ajaxProcessGetCurrenciesOptions"></a>ajaxProcessGetCurrenciesOptions

```php
mixed AdminProductsControllerCore::ajaxProcessGetCurrenciesOptions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 436](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L436)




### <a name="method-ajaxProcessGetGroupsOptions"></a>ajaxProcessGetGroupsOptions

```php
mixed AdminProductsControllerCore::ajaxProcessGetGroupsOptions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 452](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L452)




### <a name="method-ajaxProcessProductManufacturers"></a>ajaxProcessProductManufacturers

```php
mixed AdminProductsControllerCore::ajaxProcessProductManufacturers()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2456](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L2456)




### <a name="method-ajaxProcessProductQuantity"></a>ajaxProcessProductQuantity

```php
mixed AdminProductsControllerCore::ajaxProcessProductQuantity()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4571](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L4571)




### <a name="method-ajaxProcessPublishProduct"></a>ajaxProcessPublishProduct

```php
mixed AdminProductsControllerCore::ajaxProcessPublishProduct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4809](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L4809)




### <a name="method-ajaxProcessUpdateCover"></a>ajaxProcessUpdateCover

```php
mixed AdminProductsControllerCore::ajaxProcessUpdateCover()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1577](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L1577)




### <a name="method-ajaxProcessUpdateImagePosition"></a>ajaxProcessUpdateImagePosition

```php
mixed AdminProductsControllerCore::ajaxProcessUpdateImagePosition()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1556](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L1556)




### <a name="method-ajaxProcessUpdatePositions"></a>ajaxProcessUpdatePositions

```php
mixed AdminProductsControllerCore::ajaxProcessUpdatePositions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4774](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L4774)




### <a name="method-ajaxProcessUpdateProductImageShopAsso"></a>ajaxProcessUpdateProductImageShopAsso

```php
mixed AdminProductsControllerCore::ajaxProcessUpdateProductImageShopAsso()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1512](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L1512)




### <a name="method-ajaxProcessaddProductImage"></a>ajaxProcessaddProductImage

```php
mixed AdminProductsControllerCore::ajaxProcessaddProductImage()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3864](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L3864)




### <a name="method-checkFeatures"></a>checkFeatures

```php
mixed AdminProductsControllerCore::checkFeatures($languages, $feature_id)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1649](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L1649)


#### Arguments
* $languages **mixed**
* $feature_id **mixed**



### <a name="method-checkProduct"></a>checkProduct

```php
mixed AdminProductsControllerCore::checkProduct()
```

Check that a saved product is valid



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2014](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L2014)




### <a name="method-copyFromPost"></a>copyFromPost

```php
mixed AdminProductsControllerCore::copyFromPost($object, $table)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 319](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L319)


#### Arguments
* $object **mixed**
* $table **mixed**



### <a name="method-copyImage"></a>copyImage

```php
mixed AdminProductsControllerCore::copyImage(integer $id_product, integer $id_image, $method)
```

Copy a product image



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1719](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L1719)


#### Arguments
* $id_product **integer** - Product Id for product image filename
* $id_image **integer** - Image Id for product image filename
* $method **mixed**



### <a name="method-getCarrierList"></a>getCarrierList

```php
mixed AdminProductsControllerCore::getCarrierList()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3831](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L3831)




### <a name="method-getCombinationImagesJS"></a>getCombinationImagesJS

```php
mixed AdminProductsControllerCore::getCombinationImagesJS()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4637](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L4637)




### <a name="method-getL"></a>getL

```php
mixed AdminProductsControllerCore::getL($key)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4728](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L4728)


#### Arguments
* $key **mixed**



### <a name="method-getList"></a>getList

```php
mixed AdminProductsControllerCore::getList($id_lang, $orderBy, $orderWay, $start, $limit, $id_lang_shop)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 354](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L354)


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
* Source: [controllers/admin/AdminProductsController.php line 3212](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L3212)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-getPreviewUrl"></a>getPreviewUrl

```php
mixed AdminProductsControllerCore::getPreviewUrl(\Product $product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2736](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L2736)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-getQuantities"></a>getQuantities

```php
mixed AdminProductsControllerCore::getQuantities($echo, $tr)
```





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminProductsController.php line 274](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L274)


#### Arguments
* $echo **mixed**
* $tr **mixed**



### <a name="method-haveThisAccessory"></a>haveThisAccessory

```php
mixed AdminProductsControllerCore::haveThisAccessory($accessory_id, $accessories)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4655](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L4655)


#### Arguments
* $accessory_id **mixed**
* $accessories **mixed**



### <a name="method-initContent"></a>initContent

```php
mixed AdminProductsControllerCore::initContent($token)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2301](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L2301)


#### Arguments
* $token **mixed**



### <a name="method-initFormAssociations"></a>initFormAssociations

```php
mixed AdminProductsControllerCore::initFormAssociations($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3011](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L3011)


#### Arguments
* $obj **mixed**



### <a name="method-initFormAttachments"></a>initFormAttachments

```php
mixed AdminProductsControllerCore::initFormAttachments($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3671](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L3671)


#### Arguments
* $obj **mixed**



### <a name="method-initFormAttributes"></a>initFormAttributes

```php
mixed AdminProductsControllerCore::initFormAttributes($product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4067](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L4067)


#### Arguments
* $product **mixed**



### <a name="method-initFormCombinations"></a>initFormCombinations

```php
mixed AdminProductsControllerCore::initFormCombinations($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4062](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L4062)


#### Arguments
* $obj **mixed**



### <a name="method-initFormCustomization"></a>initFormCustomization

```php
mixed AdminProductsControllerCore::initFormCustomization($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3637](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L3637)


#### Arguments
* $obj **mixed**



### <a name="method-initFormFeatures"></a>initFormFeatures

```php
mixed AdminProductsControllerCore::initFormFeatures($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4517](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L4517)


#### Arguments
* $obj **mixed**



### <a name="method-initFormImages"></a>initFormImages

```php
mixed AdminProductsControllerCore::initFormImages($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3986](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L3986)


#### Arguments
* $obj **mixed**



### <a name="method-initFormInformations"></a>initFormInformations

```php
mixed AdminProductsControllerCore::initFormInformations($product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3725](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L3725)


#### Arguments
* $product **mixed**



### <a name="method-initFormModules"></a>initFormModules

```php
mixed AdminProductsControllerCore::initFormModules($obj)
```

AdminProducts display hook



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4689](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L4689)


#### Arguments
* $obj **mixed**



### <a name="method-initFormPack"></a>initFormPack

```php
mixed AdminProductsControllerCore::initFormPack($product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3261](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L3261)


#### Arguments
* $product **mixed**



### <a name="method-initFormPrices"></a>initFormPrices

```php
mixed AdminProductsControllerCore::initFormPrices($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3077](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L3077)


#### Arguments
* $obj **mixed**



### <a name="method-initFormQuantities"></a>initFormQuantities

```php
mixed AdminProductsControllerCore::initFormQuantities($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4239](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L4239)


#### Arguments
* $obj **mixed**



### <a name="method-initFormSeo"></a>initFormSeo

```php
mixed AdminProductsControllerCore::initFormSeo($product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3187](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L3187)


#### Arguments
* $product **mixed**



### <a name="method-initFormShipping"></a>initFormShipping

```php
mixed AdminProductsControllerCore::initFormShipping($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3817](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L3817)


#### Arguments
* $obj **mixed**



### <a name="method-initFormSuppliers"></a>initFormSuppliers

```php
mixed AdminProductsControllerCore::initFormSuppliers($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4389](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L4389)


#### Arguments
* $obj **mixed**



### <a name="method-initFormVirtualProduct"></a>initFormVirtualProduct

```php
mixed AdminProductsControllerCore::initFormVirtualProduct($product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3296](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L3296)


#### Arguments
* $product **mixed**



### <a name="method-initFormWarehouses"></a>initFormWarehouses

```php
mixed AdminProductsControllerCore::initFormWarehouses($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4467](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L4467)


#### Arguments
* $obj **mixed**



### <a name="method-initPack"></a>initPack

```php
mixed AdminProductsControllerCore::initPack(\Product $product)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 4663](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L4663)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminProductsControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2526](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L2526)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminProductsControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1202](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L1202)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminProductsControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2580](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L2580)




### <a name="method-isProductFieldUpdated"></a>isProductFieldUpdated

```php
boolean AdminProductsControllerCore::isProductFieldUpdated(string $field, integer $id_lang)
```

Check if a field is edited (if the checkbox is checked)
This method will do something only for multishop with a context all / group



* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 2149](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L2149)


#### Arguments
* $field **string** - Name of field
* $id_lang **integer**



### <a name="method-isTabSubmitted"></a>isTabSubmitted

```php
mixed AdminProductsControllerCore::isTabSubmitted($tab_name)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1837](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L1837)


#### Arguments
* $tab_name **mixed**



### <a name="method-loadObject"></a>loadObject

```php
mixed AdminProductsControllerCore::loadObject($opt)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 397](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L397)


#### Arguments
* $opt **mixed**



### <a name="method-postProcess"></a>postProcess

```php
void AdminProductsControllerCore::postProcess()
```

postProcess handle every checks before saving products information



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1359](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L1359)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminProductsControllerCore::processAdd()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1756](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L1756)




### <a name="method-processAttachments"></a>processAttachments

```php
void AdminProductsControllerCore::processAttachments()
```

Attach an existing attachment to the product



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 612](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L612)




### <a name="method-processBulkDelete"></a>processBulkDelete

```php
mixed AdminProductsControllerCore::processBulkDelete()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 757](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L757)




### <a name="method-processCustomizationConfiguration"></a>processCustomizationConfiguration

```php
mixed AdminProductsControllerCore::processCustomizationConfiguration()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1138](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L1138)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminProductsControllerCore::processDelete()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 672](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L672)




### <a name="method-processDeleteVirtualProduct"></a>processDeleteVirtualProduct

```php
mixed AdminProductsControllerCore::processDeleteVirtualProduct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 468](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L468)




### <a name="method-processDuplicate"></a>processDuplicate

```php
mixed AdminProductsControllerCore::processDuplicate()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 623](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L623)




### <a name="method-processFeatures"></a>processFeatures

```php
mixed AdminProductsControllerCore::processFeatures()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 957](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L957)




### <a name="method-processImage"></a>processImage

```php
mixed AdminProductsControllerCore::processImage()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 714](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L714)




### <a name="method-processImageLegends"></a>processImageLegends

```php
mixed AdminProductsControllerCore::processImageLegends()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4834](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L4834)




### <a name="method-processPosition"></a>processPosition

```php
mixed AdminProductsControllerCore::processPosition()
```

Overrides parent for custom redirect link



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1184](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L1184)




### <a name="method-processPriceAddition"></a>processPriceAddition

```php
mixed AdminProductsControllerCore::processPriceAddition()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1041](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L1041)




### <a name="method-processPricesModification"></a>processPricesModification

```php
mixed AdminProductsControllerCore::processPricesModification()
```

This function is never called at the moment (specific prices cannot be edited)



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 999](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L999)




### <a name="method-processProductAttribute"></a>processProductAttribute

```php
mixed AdminProductsControllerCore::processProductAttribute()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 827](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L827)




### <a name="method-processProductCustomization"></a>processProductCustomization

```php
mixed AdminProductsControllerCore::processProductCustomization()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1165](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L1165)




### <a name="method-processSpecificPricePriorities"></a>processSpecificPricePriorities

```php
mixed AdminProductsControllerCore::processSpecificPricePriorities()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1121](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L1121)




### <a name="method-processStatus"></a>processStatus

```php
mixed AdminProductsControllerCore::processStatus()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1848](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L1848)




### <a name="method-processSuppliers"></a>processSuppliers

```php
mixed AdminProductsControllerCore::processSuppliers()
```

Post treatment for suppliers



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2768](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L2768)




### <a name="method-processUpdate"></a>processUpdate

```php
mixed AdminProductsControllerCore::processUpdate()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1866](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L1866)




### <a name="method-processWarehouses"></a>processWarehouses

```php
mixed AdminProductsControllerCore::processWarehouses()
```

Post treatment for warehouses



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2934](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L2934)




### <a name="method-recurseCategoryForInclude"></a>recurseCategoryForInclude

```php
mixed AdminProductsControllerCore::recurseCategoryForInclude($id_obj, array $indexedCategories, array $categories, array $current, integer $id_category, $id_category_default, $has_suite)
```

Build a categories tree



* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminProductsController.php line 2474](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L2474)


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
string|void AdminProductsControllerCore::renderForm()
```

renderForm contains all necessary initialization needed for all tabs



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2620](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L2620)




### <a name="method-renderKpis"></a>renderKpis

```php
mixed AdminProductsControllerCore::renderKpis()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2379](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L2379)




### <a name="method-renderList"></a>renderList

```php
mixed AdminProductsControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2448](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L2448)




### <a name="method-renderListAttributes"></a>renderListAttributes

```php
mixed AdminProductsControllerCore::renderListAttributes($product, $currency)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4143](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L4143)


#### Arguments
* $product **mixed**
* $currency **mixed**



### <a name="method-setMedia"></a>setMedia

```php
mixed AdminProductsControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 282](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L282)




### <a name="method-updateAccessories"></a>updateAccessories

```php
mixed AdminProductsControllerCore::updateAccessories(object $product)
```

Update product accessories



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2263](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L2263)


#### Arguments
* $product **object** - Product



### <a name="method-updateAssoShop"></a>updateAssoShop

```php
mixed AdminProductsControllerCore::updateAssoShop($id_object)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1750](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L1750)


#### Arguments
* $id_object **mixed**



### <a name="method-updateDownloadProduct"></a>updateDownloadProduct

```php
boolean AdminProductsControllerCore::updateDownloadProduct(object $product, $edit)
```

Update product download



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2183](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L2183)


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
* Source: [controllers/admin/AdminProductsController.php line 4702](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L4702)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-updateTags"></a>updateTags

```php
boolean AdminProductsControllerCore::updateTags($languages, object $product)
```

Update product tags



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2284](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminProductsController.php#L2284)


#### Arguments
* $languages **mixed**
* $product **object** - Product


