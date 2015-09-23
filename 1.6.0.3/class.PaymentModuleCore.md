Class PaymentModuleCore
=====================





* Class name: PaymentModuleCore
* This is an **abstract** class
* Parent class: [Module](class.ModuleCore.md)
* Source: [classes/PaymentModule.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/PaymentModule.php#L27)


Contents
--------


### Properties

* [$currencies](#property-$currencies)
* [$currencies_mode](#property-$currencies_mode)
* [$currentOrder](#property-$currentOrder)

### Methods

* [_getFormatedAddress](#method-_getFormatedAddress)
* [_getTxtFormatedAddress](#method-_getTxtFormatedAddress)
* [addCheckboxCountryRestrictionsForModule](#method-addCheckboxCountryRestrictionsForModule)
* [addCheckboxCurrencyRestrictionsForModule](#method-addCheckboxCurrencyRestrictionsForModule)
* [addCurrencyPermissions](#method-addCurrencyPermissions)
* [addRadioCurrencyRestrictionsForModule](#method-addRadioCurrencyRestrictionsForModule)
* [formatProductAndVoucherForEmail](#method-formatProductAndVoucherForEmail)
* [getCurrency](#method-getCurrency)
* [getInstalledPaymentModules](#method-getInstalledPaymentModules)
* [install](#method-install)
* [preCall](#method-preCall)
* [uninstall](#method-uninstall)
* [validateOrder](#method-validateOrder)




Properties
----------


### <a name="property-$currencies"></a>$currencies

```php
public mixed $currencies = true
```





* Visibility: **public**
* Source: [classes/PaymentModule.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/PaymentModule.php#L31).


### <a name="property-$currencies_mode"></a>$currencies_mode

```php
public mixed $currencies_mode = 'checkbox'
```





* Visibility: **public**
* Source: [classes/PaymentModule.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/PaymentModule.php#L32).


### <a name="property-$currentOrder"></a>$currentOrder

```php
public integer $currentOrder
```





* Visibility: **public**
* Source: [classes/PaymentModule.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/PaymentModule.php#L30).


Methods
-------


### <a name="method-_getFormatedAddress"></a>_getFormatedAddress

```php
String PaymentModuleCore::_getFormatedAddress(\Address $the_address, $line_sep, $fields_style)
```





* Visibility: **protected**
* Source: [classes/PaymentModule.php line 859](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/PaymentModule.php#L859)


#### Arguments
* $the_address **[Address](class.AddressCore.md)**
* $line_sep **mixed**
* $fields_style **mixed**



### <a name="method-_getTxtFormatedAddress"></a>_getTxtFormatedAddress

```php
String PaymentModuleCore::_getTxtFormatedAddress($the_address)
```





* Visibility: **protected**
* Source: [classes/PaymentModule.php line 835](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/PaymentModule.php#L835)


#### Arguments
* $the_address **mixed**



### <a name="method-addCheckboxCountryRestrictionsForModule"></a>addCheckboxCountryRestrictionsForModule

```php
mixed PaymentModuleCore::addCheckboxCountryRestrictionsForModule(array $shops)
```

Add checkbox country restrictions for a new module



* Visibility: **public**
* Source: [classes/PaymentModule.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/PaymentModule.php#L120)


#### Arguments
* $shops **array**



### <a name="method-addCheckboxCurrencyRestrictionsForModule"></a>addCheckboxCurrencyRestrictionsForModule

```php
mixed PaymentModuleCore::addCheckboxCurrencyRestrictionsForModule(array $shops)
```

Add checkbox currency restrictions for a new module



* Visibility: **public**
* Source: [classes/PaymentModule.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/PaymentModule.php#L83)


#### Arguments
* $shops **array**



### <a name="method-addCurrencyPermissions"></a>addCurrencyPermissions

```php
boolean PaymentModuleCore::addCurrencyPermissions(integer $id_currency, array $id_module_list)
```

Allows specified payment modules to be used by a specific currency



* Visibility: **public**
* This method is **static**.
* Source: [classes/PaymentModule.php line 904](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/PaymentModule.php#L904)


#### Arguments
* $id_currency **integer**
* $id_module_list **array**



### <a name="method-addRadioCurrencyRestrictionsForModule"></a>addRadioCurrencyRestrictionsForModule

```php
mixed PaymentModuleCore::addRadioCurrencyRestrictionsForModule(array $shops)
```

Add radio currency restrictions for a new module



* Visibility: **public**
* Source: [classes/PaymentModule.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/PaymentModule.php#L103)


#### Arguments
* $shops **array**



### <a name="method-formatProductAndVoucherForEmail"></a>formatProductAndVoucherForEmail

```php
mixed PaymentModuleCore::formatProductAndVoucherForEmail($content)
```





* Visibility: **public**
* Source: [classes/PaymentModule.php line 826](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/PaymentModule.php#L826)


#### Arguments
* $content **mixed**



### <a name="method-getCurrency"></a>getCurrency

```php
\Currency PaymentModuleCore::getCurrency($current_id_currency)
```





* Visibility: **public**
* Source: [classes/PaymentModule.php line 868](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/PaymentModule.php#L868)


#### Arguments
* $current_id_currency **mixed**



### <a name="method-getInstalledPaymentModules"></a>getInstalledPaymentModules

```php
array PaymentModuleCore::getInstalledPaymentModules()
```

List all installed and active payment modules



* Visibility: **public**
* This method is **static**.
* Source: [classes/PaymentModule.php line 936](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/PaymentModule.php#L936)




### <a name="method-install"></a>install

```php
mixed PaymentModuleCore::install()
```





* Visibility: **public**
* Source: [classes/PaymentModule.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/PaymentModule.php#L34)




### <a name="method-preCall"></a>preCall

```php
mixed PaymentModuleCore::preCall($module_name)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/PaymentModule.php line 953](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/PaymentModule.php#L953)


#### Arguments
* $module_name **mixed**



### <a name="method-uninstall"></a>uninstall

```php
mixed PaymentModuleCore::uninstall()
```





* Visibility: **public**
* Source: [classes/PaymentModule.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/PaymentModule.php#L68)




### <a name="method-validateOrder"></a>validateOrder

```php
mixed PaymentModuleCore::validateOrder(integer $id_cart, integer $id_order_state, float $amount_paid, string $payment_method, string $message, $extra_vars, $currency_special, $dont_touch_amount, $secure_key, \Shop $shop)
```

Validate an order in database
Function called from a payment module



* Visibility: **public**
* Source: [classes/PaymentModule.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/PaymentModule.php#L139)


#### Arguments
* $id_cart **integer** - Value
* $id_order_state **integer** - Value
* $amount_paid **float** - Amount really paid by customer (in the default currency)
* $payment_method **string** - Payment method (eg. &#039;Credit card&#039;)
* $message **string** - Message to attach to order
* $extra_vars **mixed**
* $currency_special **mixed**
* $dont_touch_amount **mixed**
* $secure_key **mixed**
* $shop **[Shop](class.ShopCore.md)**


