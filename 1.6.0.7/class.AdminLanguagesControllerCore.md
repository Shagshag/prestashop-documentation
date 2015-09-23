Class AdminLanguagesControllerCore
=====================





* Class name: AdminLanguagesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminLanguagesController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminLanguagesController.php#L27)


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
* Source: [controllers/admin/AdminLanguagesController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminLanguagesController.php#L29)




### <a name="method-afterImageUpload"></a>afterImageUpload

```php
mixed AdminLanguagesControllerCore::afterImageUpload()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 554](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminLanguagesController.php#L554)




### <a name="method-ajaxProcessCheckLangPack"></a>ajaxProcessCheckLangPack

```php
mixed AdminLanguagesControllerCore::ajaxProcessCheckLangPack()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 510](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminLanguagesController.php#L510)




### <a name="method-checkDeletion"></a>checkDeletion

```php
mixed AdminLanguagesControllerCore::checkDeletion($object)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 324](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminLanguagesController.php#L324)


#### Arguments
* $object **mixed**



### <a name="method-checkDisableStatus"></a>checkDisableStatus

```php
mixed AdminLanguagesControllerCore::checkDisableStatus($object)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 347](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminLanguagesController.php#L347)


#### Arguments
* $object **mixed**



### <a name="method-checkEmployeeIdLang"></a>checkEmployeeIdLang

```php
mixed AdminLanguagesControllerCore::checkEmployeeIdLang($current_id_lang)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 548](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminLanguagesController.php#L548)


#### Arguments
* $current_id_lang **mixed**



### <a name="method-copyFromPost"></a>copyFromPost

```php
mixed AdminLanguagesControllerCore::copyFromPost($object, $table)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 502](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminLanguagesController.php#L502)


#### Arguments
* $object **mixed**
* $table **mixed**



### <a name="method-copyNoPictureImage"></a>copyNoPictureImage

```php
mixed AdminLanguagesControllerCore::copyNoPictureImage(string $language)
```

Copy a no-product image



* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 444](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminLanguagesController.php#L444)


#### Arguments
* $language **string** - Language iso_code for no_picture image filename



### <a name="method-deleteNoPictureImages"></a>deleteNoPictureImages

```php
boolean AdminLanguagesControllerCore::deleteNoPictureImages(string $id_language)
```

deleteNoPictureImages will delete all default image created for the language id_language



* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 482](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminLanguagesController.php#L482)


#### Arguments
* $id_language **string**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminLanguagesControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminLanguagesController.php#L105)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminLanguagesControllerCore::processAdd()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 392](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminLanguagesController.php#L392)




### <a name="method-processBulkDelete"></a>processBulkDelete

```php
mixed AdminLanguagesControllerCore::processBulkDelete()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 304](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminLanguagesController.php#L304)




### <a name="method-processBulkDisableSelection"></a>processBulkDisableSelection

```php
mixed AdminLanguagesControllerCore::processBulkDisableSelection()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 377](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminLanguagesController.php#L377)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminLanguagesControllerCore::processDelete()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 293](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminLanguagesController.php#L293)




### <a name="method-processStatus"></a>processStatus

```php
mixed AdminLanguagesControllerCore::processStatus()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 366](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminLanguagesController.php#L366)




### <a name="method-processUpdate"></a>processUpdate

```php
mixed AdminLanguagesControllerCore::processUpdate()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 414](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminLanguagesController.php#L414)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminLanguagesControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminLanguagesController.php#L128)




### <a name="method-renderList"></a>renderList

```php
mixed AdminLanguagesControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/controllers/admin/AdminLanguagesController.php#L117)



