Class AdminEmployeesControllerCore
=====================





* Class name: AdminEmployeesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminEmployeesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L30)


Contents
--------


### Properties

* [$object](#property-$object)
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
* [processBulkDelete](#method-processBulkDelete)
* [processDelete](#method-processDelete)
* [processSave](#method-processSave)
* [processStatus](#method-processStatus)
* [renderForm](#method-renderForm)
* [renderList](#method-renderList)
* [setMedia](#method-setMedia)
* [validateRules](#method-validateRules)




Properties
----------


### <a name="property-$object"></a>$object

```php
public \Employee $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L30).


### <a name="property-$profiles_array"></a>$profiles_array

```php
protected array $profiles_array = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminEmployeesController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L33).


### <a name="property-$restrict_edition"></a>$restrict_edition

```php
protected mixed $restrict_edition = false
```





* Visibility: **protected**
* Source: [controllers/admin/AdminEmployeesController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L41).


### <a name="property-$tabs_list"></a>$tabs_list

```php
protected array $tabs_list = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminEmployeesController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L39).


### <a name="property-$themes"></a>$themes

```php
protected array $themes = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminEmployeesController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L36).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminEmployeesControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L43)




### <a name="method-_childValidation"></a>_childValidation

```php
mixed AdminEmployeesControllerCore::_childValidation()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminEmployeesController.php line 430](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L430)




### <a name="method-afterUpdate"></a>afterUpdate

```php
boolean AdminEmployeesControllerCore::afterUpdate(\Employee $object)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminEmployeesController.php line 640](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L640)


#### Arguments
* $object **[Employee](class.EmployeeCore.md)**



### <a name="method-ajaxProcessFormLanguage"></a>ajaxProcessFormLanguage

```php
mixed AdminEmployeesControllerCore::ajaxProcessFormLanguage()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminEmployeesController.php line 661](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L661)




### <a name="method-ajaxProcessGetTabByIdProfile"></a>ajaxProcessGetTabByIdProfile

```php
mixed AdminEmployeesControllerCore::ajaxProcessGetTabByIdProfile()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 675](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L675)




### <a name="method-ajaxProcessToggleMenu"></a>ajaxProcessToggleMenu

```php
mixed AdminEmployeesControllerCore::ajaxProcessToggleMenu()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminEmployeesController.php line 670](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L670)




### <a name="method-canModifyEmployee"></a>canModifyEmployee

```php
mixed AdminEmployeesControllerCore::canModifyEmployee()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminEmployeesController.php line 479](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L479)




### <a name="method-initContent"></a>initContent

```php
mixed AdminEmployeesControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 626](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L626)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminEmployeesControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L176)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminEmployeesControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 615](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L615)




### <a name="method-processBulkDelete"></a>processBulkDelete

```php
mixed AdminEmployeesControllerCore::processBulkDelete()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminEmployeesController.php line 465](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L465)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminEmployeesControllerCore::processDelete()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 447](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L447)




### <a name="method-processSave"></a>processSave

```php
mixed AdminEmployeesControllerCore::processSave()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 502](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L502)




### <a name="method-processStatus"></a>processStatus

```php
mixed AdminEmployeesControllerCore::processStatus()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 456](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L456)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminEmployeesControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 211](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L211)




### <a name="method-renderList"></a>renderList

```php
mixed AdminEmployeesControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L200)




### <a name="method-setMedia"></a>setMedia

```php
mixed AdminEmployeesControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L168)




### <a name="method-validateRules"></a>validateRules

```php
mixed AdminEmployeesControllerCore::validateRules($class_name)
```





* Visibility: **public**
* Source: [controllers/admin/AdminEmployeesController.php line 603](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminEmployeesController.php#L603)


#### Arguments
* $class_name **mixed**


