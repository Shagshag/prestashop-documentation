Class AccountingCore
=====================





* Class name: AccountingCore
* Source: [classes/Accounting.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Accounting.php#L28)


Contents
--------

### Constants

* [CONF_NAME](#constant-CONF_NAME)

### Properties

* [$acc_conf](#property-$acc_conf)
* [$acc_conf_cached](#property-$acc_conf_cached)

### Methods

* [getAccountNumberZoneShop](#method-getAccountNumberZoneShop)
* [getConfiguration](#method-getConfiguration)
* [getDisplayedCustomerAccount](#method-getDisplayedCustomerAccount)
* [getExportedList](#method-getExportedList)
* [getProductAccountNumberZoneShop](#method-getProductAccountNumberZoneShop)
* [saveProductAccountingInformations](#method-saveProductAccountingInformations)
* [setAccountNumberByZoneShop](#method-setAccountNumberByZoneShop)
* [updateConfiguration](#method-updateConfiguration)


Constants
----------


### <a name="constant-CONF_NAME"></a>CONF_NAME

```php
const CONF_NAME = 'ACCOUNTING_CONFIGURATION'
```





* Source: [classes/Accounting.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Accounting.php#L30).


Properties
----------


### <a name="property-$acc_conf"></a>$acc_conf

```php
public array $acc_conf = array('customer_prefix' => '', 'journal' => '', 'account_length' => '', 'account_submit_shipping_charge' => '', 'account_unsubmit_shipping_charge' => '', 'account_gift_wripping' => '', 'account_handling' => '')
```

Default Values
All key modification have to be changed into the localization pack and xml
This configuration is applied for a specific shop



* Visibility: **public**
* This property is **static**.
* Source: [classes/Accounting.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Accounting.php#L39).


### <a name="property-$acc_conf_cached"></a>$acc_conf_cached

```php
public mixed $acc_conf_cached = false
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Accounting.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Accounting.php#L49).


Methods
-------


### <a name="method-getAccountNumberZoneShop"></a>getAccountNumberZoneShop

```php
array AccountingCore::getAccountNumberZoneShop($id_shop)
```

Get shop account number list by zone (will be refactoring for a dynamic use depending of the Controller)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Accounting.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Accounting.php#L125)


#### Arguments
* $id_shop **mixed**



### <a name="method-getConfiguration"></a>getConfiguration

```php
array|boolean AccountingCore::getConfiguration(null $key)
```

Get the Accounting Configuration
If a key is defined, then it will try to get the value



* Visibility: **public**
* This method is **static**.
* Source: [classes/Accounting.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Accounting.php#L141)


#### Arguments
* $key **null**



### <a name="method-getDisplayedCustomerAccount"></a>getDisplayedCustomerAccount

```php
string AccountingCore::getDisplayedCustomerAccount($id_customer, $default_value)
```

Get the displayed customer account.

Pad with / without prefix if the account is set

* Visibility: **public**
* This method is **static**.
* Source: [classes/Accounting.php line 188](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Accounting.php#L188)


#### Arguments
* $id_customer **mixed**
* $default_value **mixed**



### <a name="method-getExportedList"></a>getExportedList

```php
array AccountingCore::getExportedList()
```

Get the list of export done



* Visibility: **public**
* This method is **static**.
* Source: [classes/Accounting.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Accounting.php#L173)




### <a name="method-getProductAccountNumberZoneShop"></a>getProductAccountNumberZoneShop

```php
array AccountingCore::getProductAccountNumberZoneShop($id_product, $id_shop)
```

Get product account number list by zone (will be refactoring for a dynamic use depending of the Controller)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Accounting.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Accounting.php#L110)


#### Arguments
* $id_product **mixed**
* $id_shop **mixed**



### <a name="method-saveProductAccountingInformations"></a>saveProductAccountingInformations

```php
mixed AccountingCore::saveProductAccountingInformations(array $asso_product_zone_shop)
```

Add or update product accounting information for a product (will be refactoring for a dynamic use depending of the Controller)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Accounting.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Accounting.php#L83)


#### Arguments
* $asso_product_zone_shop **array**



### <a name="method-setAccountNumberByZoneShop"></a>setAccountNumberByZoneShop

```php
boolean AccountingCore::setAccountNumberByZoneShop($asso_zone_shop_list)
```

Set an account number to a zone (will be refactoring for a dynamic use depending of the Controller)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Accounting.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Accounting.php#L56)


#### Arguments
* $asso_zone_shop_list **mixed**



### <a name="method-updateConfiguration"></a>updateConfiguration

```php
mixed AccountingCore::updateConfiguration($acc_conf)
```

Update Accounting configuration



* Visibility: **public**
* This method is **static**.
* Source: [classes/Accounting.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Accounting.php#L162)


#### Arguments
* $acc_conf **mixed**


