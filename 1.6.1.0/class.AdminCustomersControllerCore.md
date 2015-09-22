Class AdminCustomersControllerCore
=====================





* Class name: AdminCustomersControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminCustomersController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L30)


Contents
--------


### Properties

* [$_defaultOrderBy](#property-$_defaultOrderBy)
* [$_defaultOrderWay](#property-$_defaultOrderWay)
* [$can_add_customer](#property-$can_add_customer)
* [$delete_mode](#property-$delete_mode)
* [$meaning_status](#property-$meaning_status)
* [$object](#property-$object)

### Methods

* [__construct](#method-__construct)
* [_setDeletedMode](#method-_setDeletedMode)
* [afterDelete](#method-afterDelete)
* [ajaxProcessSearchCustomers](#method-ajaxProcessSearchCustomers)
* [ajaxProcessUpdateCustomerNote](#method-ajaxProcessUpdateCustomerNote)
* [beforeAdd](#method-beforeAdd)
* [displayDeleteLink](#method-displayDeleteLink)
* [getList](#method-getList)
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
* Source: [controllers/admin/AdminCustomersController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L34).


### <a name="property-$_defaultOrderWay"></a>$_defaultOrderWay

```php
protected mixed $_defaultOrderWay = 'DESC'
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomersController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L35).


### <a name="property-$can_add_customer"></a>$can_add_customer

```php
protected mixed $can_add_customer = true
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomersController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L36).


### <a name="property-$delete_mode"></a>$delete_mode

```php
protected mixed $delete_mode
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomersController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L32).


### <a name="property-$meaning_status"></a>$meaning_status

```php
protected mixed $meaning_status = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [controllers/admin/AdminCustomersController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L37).


### <a name="property-$object"></a>$object

```php
public \Customer $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L30).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminCustomersControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L39)




### <a name="method-_setDeletedMode"></a>_setDeletedMode

```php
mixed AdminCustomersControllerCore::_setDeletedMode()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomersController.php line 863](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L863)




### <a name="method-afterDelete"></a>afterDelete

```php
mixed AdminCustomersControllerCore::afterDelete($object, $old_id)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomersController.php line 947](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L947)


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
* Source: [controllers/admin/AdminCustomersController.php line 1049](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L1049)




### <a name="method-ajaxProcessUpdateCustomerNote"></a>ajaxProcessUpdateCustomerNote

```php
void AdminCustomersControllerCore::ajaxProcessUpdateCustomerNote()
```

Uodate the customer note



* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 1076](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L1076)




### <a name="method-beforeAdd"></a>beforeAdd

```php
mixed AdminCustomersControllerCore::beforeAdd($customer)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 613](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L613)


#### Arguments
* $customer **mixed**



### <a name="method-displayDeleteLink"></a>displayDeleteLink

```php
mixed AdminCustomersControllerCore::displayDeleteLink(string $token, integer $id, string $name)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 1025](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L1025)


#### Arguments
* $token **string**
* $id **integer**
* $name **string**



### <a name="method-getList"></a>getList

```php
mixed AdminCustomersControllerCore::getList($id_lang, $orderBy, $orderWay, $start, $limit, $id_lang_shop)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L222)


#### Arguments
* $id_lang **mixed**
* $orderBy **mixed**
* $orderWay **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### <a name="method-initContent"></a>initContent

```php
mixed AdminCustomersControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 194](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L194)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminCustomersControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 265](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L265)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminCustomersControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 277](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L277)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminCustomersControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 209](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L209)




### <a name="method-initToolbarTitle"></a>initToolbarTitle

```php
mixed AdminCustomersControllerCore::initToolbarTitle()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L232)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminCustomersControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L186)




### <a name="method-printNewsIcon"></a>printNewsIcon

```php
mixed AdminCustomersControllerCore::printNewsIcon($value, $customer)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 1003](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L1003)


#### Arguments
* $value **mixed**
* $customer **mixed**



### <a name="method-printOptinIcon"></a>printOptinIcon

```php
mixed AdminCustomersControllerCore::printOptinIcon($value, $customer)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 1011](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L1011)


#### Arguments
* $value **mixed**
* $customer **mixed**



### <a name="method-processAdd"></a>processAdd

```php
mixed AdminCustomersControllerCore::processAdd()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 882](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L882)




### <a name="method-processBulkDelete"></a>processBulkDelete

```php
mixed AdminCustomersControllerCore::processBulkDelete()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCustomersController.php line 876](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L876)




### <a name="method-processChangeNewsletterVal"></a>processChangeNewsletterVal

```php
mixed AdminCustomersControllerCore::processChangeNewsletterVal()
```

Toggle the newsletter flag



* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 978](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L978)




### <a name="method-processChangeOptinVal"></a>processChangeOptinVal

```php
mixed AdminCustomersControllerCore::processChangeOptinVal()
```

Toggle newsletter optin flag



* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 992](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L992)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminCustomersControllerCore::processDelete()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 857](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L857)




### <a name="method-processGuestToCustomer"></a>processGuestToCustomer

```php
mixed AdminCustomersControllerCore::processGuestToCustomer()
```

Transform a guest account into a registered customer account



* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 962](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L962)




### <a name="method-processSave"></a>processSave

```php
mixed AdminCustomersControllerCore::processSave()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 934](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L934)




### <a name="method-processUpdate"></a>processUpdate

```php
mixed AdminCustomersControllerCore::processUpdate()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 911](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L911)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminCustomersControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 323](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L323)




### <a name="method-renderKpis"></a>renderKpis

```php
mixed AdminCustomersControllerCore::renderKpis()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 618](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L618)




### <a name="method-renderList"></a>renderList

```php
mixed AdminCustomersControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 311](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L311)




### <a name="method-renderView"></a>renderView

```php
mixed AdminCustomersControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCustomersController.php line 678](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCustomersController.php#L678)



