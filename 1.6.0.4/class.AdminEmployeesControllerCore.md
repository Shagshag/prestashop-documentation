Class AdminEmployeesControllerCore
=====================





* Class name: AdminEmployeesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminEmployeesController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminEmployeesController.php#L27)


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
* Source: [controllers/admin/AdminEmployeesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminEmployeesController.php#L30).


### <a name="property-$restrict_edition"></a>$restrict_edition

```php
protected mixed $restrict_edition = false
```





* Visibility: **protected**
* Source: [controllers/admin/AdminEmployeesController.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminEmployeesController.php#L38).


### <a name="property-$tabs_list"></a>$tabs_list

```php
protected array $tabs_list = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminEmployeesController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminEmployeesController.php#L36).


### <a name="property-$themes"></a>$themes

```php
protected array $themes = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminEmployeesController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminEmployeesController.php#L33).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminEmployeesControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminEmployeesController.php#L40)




### <a name="method-_childValidation"></a>_childValidation

```php
mixed AdminEmployeesControllerCore::_childValidation()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminEmployeesController.php line 422](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminEmployeesController.php#L422)




### <a name="method-afterUpdate"></a>afterUpdate

```php
mixed AdminEmployeesControllerCore::afterUpdate($object)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminEmployeesController.php line 604](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminEmployeesController.php#L604)


#### Arguments
* $object **mixed**



### <a name="method-ajaxProcessFormLanguage"></a>ajaxProcessFormLanguage

```php
mixed AdminEmployeesControllerCore::ajaxProcessFormLanguage()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminEmployeesController.php line 615](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminEmployeesController.php#L615)




### <a name="method-ajaxProcessGetTabByIdProfile"></a>ajaxProcessGetTabByIdProfile

```php
mixed AdminEmployeesControllerCore::ajaxProcessGetTabByIdProfile()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 628](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminEmployeesController.php#L628)




### <a name="method-ajaxProcessToggleMenu"></a>ajaxProcessToggleMenu

```php
mixed AdminEmployeesControllerCore::ajaxProcessToggleMenu()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminEmployeesController.php line 623](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminEmployeesController.php#L623)




### <a name="method-canModifyEmployee"></a>canModifyEmployee

```php
mixed AdminEmployeesControllerCore::canModifyEmployee()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminEmployeesController.php line 448](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminEmployeesController.php#L448)




### <a name="method-initContent"></a>initContent

```php
mixed AdminEmployeesControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 596](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminEmployeesController.php#L596)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminEmployeesControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminEmployeesController.php#L169)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminEmployeesControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 584](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminEmployeesController.php#L584)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminEmployeesControllerCore::processDelete()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 432](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminEmployeesController.php#L432)




### <a name="method-processSave"></a>processSave

```php
mixed AdminEmployeesControllerCore::processSave()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 474](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminEmployeesController.php#L474)




### <a name="method-processStatus"></a>processStatus

```php
mixed AdminEmployeesControllerCore::processStatus()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 440](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminEmployeesController.php#L440)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminEmployeesControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 203](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminEmployeesController.php#L203)




### <a name="method-renderList"></a>renderList

```php
mixed AdminEmployeesControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 193](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminEmployeesController.php#L193)




### <a name="method-setMedia"></a>setMedia

```php
mixed AdminEmployeesControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 161](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminEmployeesController.php#L161)




### <a name="method-validateRules"></a>validateRules

```php
mixed AdminEmployeesControllerCore::validateRules($class_name)
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 573](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/controllers/admin/AdminEmployeesController.php#L573)


#### Arguments
* $class_name **mixed**


