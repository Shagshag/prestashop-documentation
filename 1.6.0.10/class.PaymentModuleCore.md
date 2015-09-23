Class PaymentModuleCore
=====================





* Class name: PaymentModuleCore
* This is an **abstract** class
* Parent class: [Module](class.ModuleCore.md)
* Source: [classes/PaymentModule.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/PaymentModule.php#L27)


Contents
--------

### Constants

* [DEBUG_MODE](#constant-DEBUG_MODE)

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
* [getEmailTemplateContent](#method-getEmailTemplateContent)
* [getInstalledPaymentModules](#method-getInstalledPaymentModules)
* [install](#method-install)
* [preCall](#method-preCall)
* [uninstall](#method-uninstall)
* [validateOrder](#method-validateOrder)


Constants
----------


### <a name="constant-DEBUG_MODE"></a>DEBUG_MODE

```php
const DEBUG_MODE = false
```





* Source: [classes/PaymentModule.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/PaymentModule.php#L34).


Properties
----------


### <a name="property-$currencies"></a>$currencies

```php
public mixed $currencies = true
```





* Visibility: **public**
* Source: [classes/PaymentModule.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/PaymentModule.php#L31).


### <a name="property-$currencies_mode"></a>$currencies_mode

```php
public mixed $currencies_mode = 'checkbox'
```





* Visibility: **public**
* Source: [classes/PaymentModule.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/PaymentModule.php#L32).


### <a name="property-$currentOrder"></a>$currentOrder

```php
public integer $currentOrder
```





* Visibility: **public**
* Source: [classes/PaymentModule.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/PaymentModule.php#L30).


Methods
-------


### <a name="method-_getFormatedAddress"></a>_getFormatedAddress

```php
String PaymentModuleCore::_getFormatedAddress(\Address $the_address, $line_sep, $fields_style)
```





* Visibility: **protected**
* Source: [classes/PaymentModule.php line 844](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/PaymentModule.php#L844)


#### Arguments
* $the_address **[Address](class.AddressCore.md)**
* $line_sep **mixed**
* $fields_style **mixed**



### <a name="method-_getTxtFormatedAddress"></a>_getTxtFormatedAddress

```php
String PaymentModuleCore::_getTxtFormatedAddress($the_address)
```





* Visibility: **protected**
* Source: [classes/PaymentModule.php line 820](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/PaymentModule.php#L820)


#### Arguments
* $the_address **mixed**



### <a name="method-addCheckboxCountryRestrictionsForModule"></a>addCheckboxCountryRestrictionsForModule

```php
boolean PaymentModuleCore::addCheckboxCountryRestrictionsForModule(array $shops)
```

Add checkbox country restrictions for a new module



* Visibility: **public**
* Source: [classes/PaymentModule.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/PaymentModule.php#L125)


#### Arguments
* $shops **array**



### <a name="method-addCheckboxCurrencyRestrictionsForModule"></a>addCheckboxCurrencyRestrictionsForModule

```php
boolean PaymentModuleCore::addCheckboxCurrencyRestrictionsForModule(array $shops)
```

Add checkbox currency restrictions for a new module



* Visibility: **public**
* Source: [classes/PaymentModule.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/PaymentModule.php#L86)


#### Arguments
* $shops **array**



### <a name="method-addCurrencyPermissions"></a>addCurrencyPermissions

```php
boolean PaymentModuleCore::addCurrencyPermissions(integer $id_currency, array $id_module_list)
```

Allows specified payment modules to be used by a specific currency



* Visibility: **public**
* This method is **static**.
* Source: [classes/PaymentModule.php line 890](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/PaymentModule.php#L890)


#### Arguments
* $id_currency **integer**
* $id_module_list **array**



### <a name="method-addRadioCurrencyRestrictionsForModule"></a>addRadioCurrencyRestrictionsForModule

```php
boolean PaymentModuleCore::addRadioCurrencyRestrictionsForModule(array $shops)
```

Add radio currency restrictions for a new module



* Visibility: **public**
* Source: [classes/PaymentModule.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/PaymentModule.php#L107)


#### Arguments
* $shops **array**



### <a name="method-formatProductAndVoucherForEmail"></a>formatProductAndVoucherForEmail

```php
mixed PaymentModuleCore::formatProductAndVoucherForEmail($content)
```





* Visibility: **public**
* Source: [classes/PaymentModule.php line 810](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/PaymentModule.php#L810)


#### Arguments
* $content **mixed**



### <a name="method-getCurrency"></a>getCurrency

```php
\Currency PaymentModuleCore::getCurrency($current_id_currency)
```





* Visibility: **public**
* Source: [classes/PaymentModule.php line 853](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/PaymentModule.php#L853)


#### Arguments
* $current_id_currency **mixed**



### <a name="method-getEmailTemplateContent"></a>getEmailTemplateContent

```php
string PaymentModuleCore::getEmailTemplateContent(string $template_name, integer $mail_type, array $var)
```

Fetch the content of $template_name inside the folder current_theme/mails/current_iso_lang/ if found, otherwise in mails/current_iso_lang



* Visibility: **protected**
* Source: [classes/PaymentModule.php line 957](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/PaymentModule.php#L957)


#### Arguments
* $template_name **string** - template name with extension
* $mail_type **integer** - Mail::TYPE_HTML or Mail::TYPE_TXT
* $var **array** - list send to smarty



### <a name="method-getInstalledPaymentModules"></a>getInstalledPaymentModules

```php
array PaymentModuleCore::getInstalledPaymentModules()
```

List all installed and active payment modules



* Visibility: **public**
* This method is **static**.
* Source: [classes/PaymentModule.php line 921](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/PaymentModule.php#L921)




### <a name="method-install"></a>install

```php
mixed PaymentModuleCore::install()
```





* Visibility: **public**
* Source: [classes/PaymentModule.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/PaymentModule.php#L36)




### <a name="method-preCall"></a>preCall

```php
mixed PaymentModuleCore::preCall($module_name)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/PaymentModule.php line 936](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/PaymentModule.php#L936)


#### Arguments
* $module_name **mixed**



### <a name="method-uninstall"></a>uninstall

```php
mixed PaymentModuleCore::uninstall()
```





* Visibility: **public**
* Source: [classes/PaymentModule.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/PaymentModule.php#L70)




### <a name="method-validateOrder"></a>validateOrder

```php
boolean PaymentModuleCore::validateOrder(integer $id_cart, integer $id_order_state, float $amount_paid, string $payment_method, null $message, array $extra_vars, null $currency_special, boolean $dont_touch_amount, boolean $secure_key, \Shop $shop)
```

Validate an order in database
Function called from a payment module



* Visibility: **public**
* Source: [classes/PaymentModule.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/PaymentModule.php#L152)


#### Arguments
* $id_cart **integer**
* $id_order_state **integer**
* $amount_paid **float** - Amount really paid by customer (in the default currency)
* $payment_method **string** - Payment method (eg. &#039;Credit card&#039;)
* $message **null** - Message to attach to order
* $extra_vars **array**
* $currency_special **null**
* $dont_touch_amount **boolean**
* $secure_key **boolean**
* $shop **[Shop](class.ShopCore.md)**


