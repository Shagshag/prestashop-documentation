Class AdminEmployeesControllerCore
=====================





* Class name: AdminEmployeesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminEmployeesController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminEmployeesController.php#L27)


Contents
--------


### Properties

* [$profiles_array](#property-$profiles_array)
* [$restrict_edition](#property-$restrict_edition)
* [$tabs_list](#property-$tabs_list)
* [$themes](#property-$themes)

### Methods

* [__construct](#method-__construct)
* [_childValidation](#method-_childValidation)
* [afterUpdate](#method-afterUpdate)
* [ajaxProcessFormLanguage](#method-ajaxProcessFormLanguage)
* [ajaxProcessGetTabByIdProfile](#method-ajaxProcessGetTabByIdProfile)
* [ajaxProcessToggleMenu](#method-ajaxProcessToggleMenu)
* [canModifyEmployee](#method-canModifyEmployee)
* [initContent](#method-initContent)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [postProcess](#method-postProcess)
* [processDelete](#method-processDelete)
* [processSave](#method-processSave)
* [processStatus](#method-processStatus)
* [renderForm](#method-renderForm)
* [renderList](#method-renderList)
* [setMedia](#method-setMedia)
* [validateRules](#method-validateRules)




Properties
----------


### <a name="property-$profiles_array"></a>$profiles_array

```php
protected array $profiles_array = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminEmployeesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminEmployeesController.php#L30).


### <a name="property-$restrict_edition"></a>$restrict_edition

```php
protected mixed $restrict_edition = false
```





* Visibility: **protected**
* Source: [controllers/admin/AdminEmployeesController.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminEmployeesController.php#L38).


### <a name="property-$tabs_list"></a>$tabs_list

```php
protected array $tabs_list = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminEmployeesController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminEmployeesController.php#L36).


### <a name="property-$themes"></a>$themes

```php
protected array $themes = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminEmployeesController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminEmployeesController.php#L33).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminEmployeesControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminEmployeesController.php#L40)




### <a name="method-_childValidation"></a>_childValidation

```php
mixed AdminEmployeesControllerCore::_childValidation()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminEmployeesController.php line 421](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminEmployeesController.php#L421)




### <a name="method-afterUpdate"></a>afterUpdate

```php
mixed AdminEmployeesControllerCore::afterUpdate($object)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminEmployeesController.php line 607](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminEmployeesController.php#L607)


#### Arguments
* $object **mixed**



### <a name="method-ajaxProcessFormLanguage"></a>ajaxProcessFormLanguage

```php
mixed AdminEmployeesControllerCore::ajaxProcessFormLanguage()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminEmployeesController.php line 630](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminEmployeesController.php#L630)




### <a name="method-ajaxProcessGetTabByIdProfile"></a>ajaxProcessGetTabByIdProfile

```php
mixed AdminEmployeesControllerCore::ajaxProcessGetTabByIdProfile()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 643](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminEmployeesController.php#L643)




### <a name="method-ajaxProcessToggleMenu"></a>ajaxProcessToggleMenu

```php
mixed AdminEmployeesControllerCore::ajaxProcessToggleMenu()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminEmployeesController.php line 638](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminEmployeesController.php#L638)




### <a name="method-canModifyEmployee"></a>canModifyEmployee

```php
mixed AdminEmployeesControllerCore::canModifyEmployee()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminEmployeesController.php line 451](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminEmployeesController.php#L451)




### <a name="method-initContent"></a>initContent

```php
mixed AdminEmployeesControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 599](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminEmployeesController.php#L599)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminEmployeesControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminEmployeesController.php#L171)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminEmployeesControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 587](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminEmployeesController.php#L587)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminEmployeesControllerCore::processDelete()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 435](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminEmployeesController.php#L435)




### <a name="method-processSave"></a>processSave

```php
mixed AdminEmployeesControllerCore::processSave()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 477](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminEmployeesController.php#L477)




### <a name="method-processStatus"></a>processStatus

```php
mixed AdminEmployeesControllerCore::processStatus()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 443](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminEmployeesController.php#L443)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminEmployeesControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 205](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminEmployeesController.php#L205)




### <a name="method-renderList"></a>renderList

```php
mixed AdminEmployeesControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminEmployeesController.php#L195)




### <a name="method-setMedia"></a>setMedia

```php
mixed AdminEmployeesControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminEmployeesController.php#L163)




### <a name="method-validateRules"></a>validateRules

```php
mixed AdminEmployeesControllerCore::validateRules($class_name)
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 576](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminEmployeesController.php#L576)


#### Arguments
* $class_name **mixed**


