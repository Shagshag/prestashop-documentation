Class AdminLanguagesControllerCore
=====================





* Class name: AdminLanguagesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminLanguagesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminLanguagesController.php#L30)


Contents
--------


### Properties

* [$object](#property-$object)

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




Properties
----------


### <a name="property-$object"></a>$object

```php
public \Language $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminLanguagesController.php#L30).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminLanguagesControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminLanguagesController.php#L32)




### <a name="method-afterImageUpload"></a>afterImageUpload

```php
mixed AdminLanguagesControllerCore::afterImageUpload()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 566](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminLanguagesController.php#L566)




### <a name="method-ajaxProcessCheckLangPack"></a>ajaxProcessCheckLangPack

```php
mixed AdminLanguagesControllerCore::ajaxProcessCheckLangPack()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 522](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminLanguagesController.php#L522)




### <a name="method-checkDeletion"></a>checkDeletion

```php
mixed AdminLanguagesControllerCore::checkDeletion($object)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 328](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminLanguagesController.php#L328)


#### Arguments
* $object **mixed**



### <a name="method-checkDisableStatus"></a>checkDisableStatus

```php
mixed AdminLanguagesControllerCore::checkDisableStatus($object)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 351](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminLanguagesController.php#L351)


#### Arguments
* $object **mixed**



### <a name="method-checkEmployeeIdLang"></a>checkEmployeeIdLang

```php
mixed AdminLanguagesControllerCore::checkEmployeeIdLang($current_id_lang)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 560](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminLanguagesController.php#L560)


#### Arguments
* $current_id_lang **mixed**



### <a name="method-copyFromPost"></a>copyFromPost

```php
mixed AdminLanguagesControllerCore::copyFromPost(\Language $object, string $table)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 514](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminLanguagesController.php#L514)


#### Arguments
* $object **[Language](class.LanguageCore.md)**
* $table **string**



### <a name="method-copyNoPictureImage"></a>copyNoPictureImage

```php
void|false AdminLanguagesControllerCore::copyNoPictureImage(string $language)
```

Copy a no-product image



* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 452](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminLanguagesController.php#L452)


#### Arguments
* $language **string** - Language iso_code for no_picture image filename



### <a name="method-deleteNoPictureImages"></a>deleteNoPictureImages

```php
boolean AdminLanguagesControllerCore::deleteNoPictureImages(string $id_language)
```

deleteNoPictureImages will delete all default image created for the language id_language



* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 490](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminLanguagesController.php#L490)


#### Arguments
* $id_language **string**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminLanguagesControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminLanguagesController.php#L108)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminLanguagesControllerCore::processAdd()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 396](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminLanguagesController.php#L396)




### <a name="method-processBulkDelete"></a>processBulkDelete

```php
mixed AdminLanguagesControllerCore::processBulkDelete()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 308](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminLanguagesController.php#L308)




### <a name="method-processBulkDisableSelection"></a>processBulkDisableSelection

```php
mixed AdminLanguagesControllerCore::processBulkDisableSelection()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminLanguagesController.php line 381](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminLanguagesController.php#L381)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminLanguagesControllerCore::processDelete()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 297](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminLanguagesController.php#L297)




### <a name="method-processStatus"></a>processStatus

```php
mixed AdminLanguagesControllerCore::processStatus()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 370](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminLanguagesController.php#L370)




### <a name="method-processUpdate"></a>processUpdate

```php
mixed AdminLanguagesControllerCore::processUpdate()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 418](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminLanguagesController.php#L418)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminLanguagesControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminLanguagesController.php#L131)




### <a name="method-renderList"></a>renderList

```php
mixed AdminLanguagesControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminLanguagesController.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminLanguagesController.php#L120)



