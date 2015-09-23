Class AdminLanguagesControllerCore
=====================





* Class name: AdminLanguagesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminLanguagesController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminLanguagesController.php#L27)


Contents
--------



### Methods

* [__construct](#method-__construct)
* [afterImageUpload](#method-afterImageUpload)
* [ajaxProcessCheckLangPack](#method-ajaxProcessCheckLangPack)
* [checkDeletion](#method-checkDeletion)
* [checkDisableStatus](#method-checkDisableStatus)
* [checkEmployeeIdLang](#method-checkEmployeeIdLang)
* [copyFromPost](#method-copyFromPost)
* [copyNoPictureImage](#method-copyNoPictureImage)
* [deleteNoPictureImages](#method-deleteNoPictureImages)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [processAdd](#method-processAdd)
* [processBulkDelete](#method-processBulkDelete)
* [processBulkDisableSelection](#method-processBulkDisableSelection)
* [processDelete](#method-processDelete)
* [processStatus](#method-processStatus)
* [processUpdate](#method-processUpdate)
* [renderForm](#method-renderForm)
* [renderList](#method-renderList)






Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminLanguagesControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminLanguagesController.php#L29)




### <a name="method-afterImageUpload"></a>afterImageUpload

```php
mixed AdminLanguagesControllerCore::afterImageUpload()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 534](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminLanguagesController.php#L534)




### <a name="method-ajaxProcessCheckLangPack"></a>ajaxProcessCheckLangPack

```php
mixed AdminLanguagesControllerCore::ajaxProcessCheckLangPack()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 490](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminLanguagesController.php#L490)




### <a name="method-checkDeletion"></a>checkDeletion

```php
mixed AdminLanguagesControllerCore::checkDeletion($object)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 327](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminLanguagesController.php#L327)


#### Arguments
* $object **mixed**



### <a name="method-checkDisableStatus"></a>checkDisableStatus

```php
mixed AdminLanguagesControllerCore::checkDisableStatus($object)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 344](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminLanguagesController.php#L344)


#### Arguments
* $object **mixed**



### <a name="method-checkEmployeeIdLang"></a>checkEmployeeIdLang

```php
mixed AdminLanguagesControllerCore::checkEmployeeIdLang($current_id_lang)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 528](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminLanguagesController.php#L528)


#### Arguments
* $current_id_lang **mixed**



### <a name="method-copyFromPost"></a>copyFromPost

```php
mixed AdminLanguagesControllerCore::copyFromPost($object, $table)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 482](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminLanguagesController.php#L482)


#### Arguments
* $object **mixed**
* $table **mixed**



### <a name="method-copyNoPictureImage"></a>copyNoPictureImage

```php
mixed AdminLanguagesControllerCore::copyNoPictureImage(string $language)
```

Copy a no-product image



* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 424](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminLanguagesController.php#L424)


#### Arguments
* $language **string** - Language iso_code for no-picture image filename



### <a name="method-deleteNoPictureImages"></a>deleteNoPictureImages

```php
boolean AdminLanguagesControllerCore::deleteNoPictureImages(string $id_language)
```

deleteNoPictureImages will delete all default image created for the language id_language



* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 462](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminLanguagesController.php#L462)


#### Arguments
* $id_language **string**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminLanguagesControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminLanguagesController.php#L103)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminLanguagesControllerCore::processAdd()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 384](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminLanguagesController.php#L384)




### <a name="method-processBulkDelete"></a>processBulkDelete

```php
mixed AdminLanguagesControllerCore::processBulkDelete()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 307](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminLanguagesController.php#L307)




### <a name="method-processBulkDisableSelection"></a>processBulkDisableSelection

```php
mixed AdminLanguagesControllerCore::processBulkDisableSelection()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 369](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminLanguagesController.php#L369)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminLanguagesControllerCore::processDelete()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 296](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminLanguagesController.php#L296)




### <a name="method-processStatus"></a>processStatus

```php
mixed AdminLanguagesControllerCore::processStatus()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 358](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminLanguagesController.php#L358)




### <a name="method-processUpdate"></a>processUpdate

```php
mixed AdminLanguagesControllerCore::processUpdate()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 400](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminLanguagesController.php#L400)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminLanguagesControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminLanguagesController.php#L126)




### <a name="method-renderList"></a>renderList

```php
mixed AdminLanguagesControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminLanguagesController.php#L115)



