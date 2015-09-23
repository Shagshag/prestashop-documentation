Class AdminCustomersControllerCore
=====================





* Class name: AdminCustomersControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminCustomersController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L27)


Contents
--------


### Properties

* [$_defaultOrderBy](#property-$_defaultOrderBy)
* [$_defaultOrderWay](#property-$_defaultOrderWay)
* [$can_add_customer](#property-$can_add_customer)
* [$delete_mode](#property-$delete_mode)

### Methods

* [__construct](#method-__construct)
* [_setDeletedMode](#method-_setDeletedMode)
* [afterDelete](#method-afterDelete)
* [ajaxProcessSearchCustomers](#method-ajaxProcessSearchCustomers)
* [ajaxProcessUpdateCustomerNote](#method-ajaxProcessUpdateCustomerNote)
* [beforeAdd](#method-beforeAdd)
* [displayDeleteLink](#method-displayDeleteLink)
* [initContent](#method-initContent)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [initToolbar](#method-initToolbar)
* [initToolbarTitle](#method-initToolbarTitle)
* [postProcess](#method-postProcess)
* [printNewsIcon](#method-printNewsIcon)
* [printOptinIcon](#method-printOptinIcon)
* [processAdd](#method-processAdd)
* [processBulkDelete](#method-processBulkDelete)
* [processChangeNewsletterVal](#method-processChangeNewsletterVal)
* [processChangeOptinVal](#method-processChangeOptinVal)
* [processDelete](#method-processDelete)
* [processGuestToCustomer](#method-processGuestToCustomer)
* [processSave](#method-processSave)
* [processUpdate](#method-processUpdate)
* [renderForm](#method-renderForm)
* [renderKpis](#method-renderKpis)
* [renderList](#method-renderList)
* [renderView](#method-renderView)




Properties
----------


### <a name="property-$_defaultOrderBy"></a>$_defaultOrderBy

```php
protected mixed $_defaultOrderBy = 'date_add'
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomersController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L31).


### <a name="property-$_defaultOrderWay"></a>$_defaultOrderWay

```php
protected mixed $_defaultOrderWay = 'DESC'
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomersController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L32).


### <a name="property-$can_add_customer"></a>$can_add_customer

```php
protected mixed $can_add_customer = true
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomersController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L33).


### <a name="property-$delete_mode"></a>$delete_mode

```php
protected mixed $delete_mode
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomersController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L29).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminCustomersControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L35)




### <a name="method-_setDeletedMode"></a>_setDeletedMode

```php
mixed AdminCustomersControllerCore::_setDeletedMode()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomersController.php line 792](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L792)




### <a name="method-afterDelete"></a>afterDelete

```php
mixed AdminCustomersControllerCore::afterDelete($object, $old_id)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomersController.php line 870](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L870)


#### Arguments
* $object **mixed**
* $old_id **mixed**



### <a name="method-ajaxProcessSearchCustomers"></a>ajaxProcessSearchCustomers

```php
void AdminCustomersControllerCore::ajaxProcessSearchCustomers()
```

add to $this->content the result of Customer::SearchByName
(encoded in json)



* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 972](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L972)




### <a name="method-ajaxProcessUpdateCustomerNote"></a>ajaxProcessUpdateCustomerNote

```php
void AdminCustomersControllerCore::ajaxProcessUpdateCustomerNote()
```

Uodate the customer note



* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 987](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L987)




### <a name="method-beforeAdd"></a>beforeAdd

```php
mixed AdminCustomersControllerCore::beforeAdd($customer)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 532](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L532)


#### Arguments
* $customer **mixed**



### <a name="method-displayDeleteLink"></a>displayDeleteLink

```php
mixed AdminCustomersControllerCore::displayDeleteLink(string $token, integer $id, string $name)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 948](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L948)


#### Arguments
* $token **string**
* $id **integer**
* $name **string**



### <a name="method-initContent"></a>initContent

```php
mixed AdminCustomersControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L153)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminCustomersControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L191)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminCustomersControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 203](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L203)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminCustomersControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L168)




### <a name="method-initToolbarTitle"></a>initToolbarTitle

```php
mixed AdminCustomersControllerCore::initToolbarTitle()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L182)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminCustomersControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L145)




### <a name="method-printNewsIcon"></a>printNewsIcon

```php
mixed AdminCustomersControllerCore::printNewsIcon($value, $customer)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 926](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L926)


#### Arguments
* $value **mixed**
* $customer **mixed**



### <a name="method-printOptinIcon"></a>printOptinIcon

```php
mixed AdminCustomersControllerCore::printOptinIcon($value, $customer)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 934](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L934)


#### Arguments
* $value **mixed**
* $customer **mixed**



### <a name="method-processAdd"></a>processAdd

```php
mixed AdminCustomersControllerCore::processAdd()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 811](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L811)




### <a name="method-processBulkDelete"></a>processBulkDelete

```php
mixed AdminCustomersControllerCore::processBulkDelete()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomersController.php line 805](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L805)




### <a name="method-processChangeNewsletterVal"></a>processChangeNewsletterVal

```php
mixed AdminCustomersControllerCore::processChangeNewsletterVal()
```

Toggle the newsletter flag



* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 901](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L901)




### <a name="method-processChangeOptinVal"></a>processChangeOptinVal

```php
mixed AdminCustomersControllerCore::processChangeOptinVal()
```

Toggle newsletter optin flag



* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 915](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L915)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminCustomersControllerCore::processDelete()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 786](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L786)




### <a name="method-processGuestToCustomer"></a>processGuestToCustomer

```php
mixed AdminCustomersControllerCore::processGuestToCustomer()
```

Transform a guest account into a registered customer account



* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 885](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L885)




### <a name="method-processSave"></a>processSave

```php
mixed AdminCustomersControllerCore::processSave()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 857](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L857)




### <a name="method-processUpdate"></a>processUpdate

```php
mixed AdminCustomersControllerCore::processUpdate()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 834](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L834)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminCustomersControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L249)




### <a name="method-renderKpis"></a>renderKpis

```php
mixed AdminCustomersControllerCore::renderKpis()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 537](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L537)




### <a name="method-renderList"></a>renderList

```php
mixed AdminCustomersControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 237](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L237)




### <a name="method-renderView"></a>renderView

```php
mixed AdminCustomersControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 597](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCustomersController.php#L597)



