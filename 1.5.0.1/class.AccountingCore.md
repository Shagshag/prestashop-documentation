Class AccountingCore
=====================





* Class name: AccountingCore
* Source: [classes/Accounting.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Accounting.php#L28)


Contents
--------



### Methods

* [getAccountNumberZoneShop](#method-getAccountNumberZoneShop)
* [getProductAccountNumberZoneShop](#method-getProductAccountNumberZoneShop)
* [saveProductAccountingInformations](#method-saveProductAccountingInformations)
* [setAccountNumberByZoneShop](#method-setAccountNumberByZoneShop)






Methods
-------


### <a name="method-getAccountNumberZoneShop"></a>getAccountNumberZoneShop

```php
array AccountingCore::getAccountNumberZoneShop($id_shop)
```

Get shop account number list by zone (will be refactoring for a dynamic use depending of the Controller)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Accounting.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Accounting.php#L104)


#### Arguments
* $id_shop **mixed**



### <a name="method-getProductAccountNumberZoneShop"></a>getProductAccountNumberZoneShop

```php
array AccountingCore::getProductAccountNumberZoneShop($id_product, $id_shop)
```

Get product account number list by zone (will be refactoring for a dynamic use depending of the Controller)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Accounting.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Accounting.php#L89)


#### Arguments
* $id_product **mixed**
* $id_shop **mixed**



### <a name="method-saveProductAccountingInformations"></a>saveProductAccountingInformations

```php
mixed AccountingCore::saveProductAccountingInformations($assoProductZoneShop)
```

Add or update product accounting information for a product (will be refactoring for a dynamic use depending of the Controller)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Accounting.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Accounting.php#L62)


#### Arguments
* $assoProductZoneShop **mixed**



### <a name="method-setAccountNumberByZoneShop"></a>setAccountNumberByZoneShop

```php
boolean AccountingCore::setAccountNumberByZoneShop($assoZoneShopList)
```

Set an account number to a zone (will be refactoring for a dynamic use depending of the Controller)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Accounting.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Accounting.php#L35)


#### Arguments
* $assoZoneShopList **mixed**


