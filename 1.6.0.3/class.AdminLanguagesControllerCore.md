Class AdminLanguagesControllerCore
=====================





* Class name: AdminLanguagesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminLanguagesController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminLanguagesController.php#L27)


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
* Source: [controllers/admin/AdminLanguagesController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminLanguagesController.php#L29)




### <a name="method-afterImageUpload"></a>afterImageUpload

```php
mixed AdminLanguagesControllerCore::afterImageUpload()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 529](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminLanguagesController.php#L529)




### <a name="method-ajaxProcessCheckLangPack"></a>ajaxProcessCheckLangPack

```php
mixed AdminLanguagesControllerCore::ajaxProcessCheckLangPack()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 485](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminLanguagesController.php#L485)




### <a name="method-checkDeletion"></a>checkDeletion

```php
mixed AdminLanguagesControllerCore::checkDeletion($object)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 322](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminLanguagesController.php#L322)


#### Arguments
* $object **mixed**



### <a name="method-checkDisableStatus"></a>checkDisableStatus

```php
mixed AdminLanguagesControllerCore::checkDisableStatus($object)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 339](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminLanguagesController.php#L339)


#### Arguments
* $object **mixed**



### <a name="method-checkEmployeeIdLang"></a>checkEmployeeIdLang

```php
mixed AdminLanguagesControllerCore::checkEmployeeIdLang($current_id_lang)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 523](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminLanguagesController.php#L523)


#### Arguments
* $current_id_lang **mixed**



### <a name="method-copyFromPost"></a>copyFromPost

```php
mixed AdminLanguagesControllerCore::copyFromPost($object, $table)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 477](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminLanguagesController.php#L477)


#### Arguments
* $object **mixed**
* $table **mixed**



### <a name="method-copyNoPictureImage"></a>copyNoPictureImage

```php
mixed AdminLanguagesControllerCore::copyNoPictureImage(string $language)
```

Copy a no-product image



* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 419](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminLanguagesController.php#L419)


#### Arguments
* $language **string** - Language iso_code for no_picture image filename



### <a name="method-deleteNoPictureImages"></a>deleteNoPictureImages

```php
boolean AdminLanguagesControllerCore::deleteNoPictureImages(string $id_language)
```

deleteNoPictureImages will delete all default image created for the language id_language



* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 457](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminLanguagesController.php#L457)


#### Arguments
* $id_language **string**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminLanguagesControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminLanguagesController.php#L103)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminLanguagesControllerCore::processAdd()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 379](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminLanguagesController.php#L379)




### <a name="method-processBulkDelete"></a>processBulkDelete

```php
mixed AdminLanguagesControllerCore::processBulkDelete()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 302](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminLanguagesController.php#L302)




### <a name="method-processBulkDisableSelection"></a>processBulkDisableSelection

```php
mixed AdminLanguagesControllerCore::processBulkDisableSelection()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 364](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminLanguagesController.php#L364)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminLanguagesControllerCore::processDelete()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 291](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminLanguagesController.php#L291)




### <a name="method-processStatus"></a>processStatus

```php
mixed AdminLanguagesControllerCore::processStatus()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 353](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminLanguagesController.php#L353)




### <a name="method-processUpdate"></a>processUpdate

```php
mixed AdminLanguagesControllerCore::processUpdate()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 395](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminLanguagesController.php#L395)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminLanguagesControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminLanguagesController.php#L126)




### <a name="method-renderList"></a>renderList

```php
mixed AdminLanguagesControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/controllers/admin/AdminLanguagesController.php#L115)



