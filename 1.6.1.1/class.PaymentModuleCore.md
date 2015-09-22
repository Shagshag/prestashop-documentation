Class PaymentModuleCore
=====================





* Class name: PaymentModuleCore
* This is an **abstract** class
* Parent class: [Module](class.ModuleCore)
* Source: [classes/PaymentModule.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#L27)

Constants
----------

* [DEBUG_MODE](#constant-DEBUG_MODE)

Properties
----------

* [$currencies](#property-$currencies)
* [$currencies_mode](#property-$currencies_mode)
* [$currentOrder](#property-$currentOrder)

Methods
-------
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

    const DEBUG_MODE = false



* Source: [classes/PaymentModule.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#L34)


Properties
----------


### <a name="property-$currencies"></a>$currencies

    public mixed $currencies = true





* Visibility: **public**
* Source: [classes/PaymentModule.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#L31)


### <a name="property-$currencies_mode"></a>$currencies_mode

    public mixed $currencies_mode = 'checkbox'





* Visibility: **public**
* Source: [classes/PaymentModule.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#L32)


### <a name="property-$currentOrder"></a>$currentOrder

    public integer $currentOrder





* Visibility: **public**
* Source: [classes/PaymentModule.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#L30)


Methods
-------


### <a name="method-_getFormatedAddress"></a>_getFormatedAddress

    String PaymentModuleCore::_getFormatedAddress(\Address $the_address, $line_sep, $fields_style)





* Visibility: **protected**
* Source: [classes/PaymentModule.php line 867](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#L867)


#### Arguments
* $the_address **[Address](class.AddressCore)**
* $line_sep **mixed**
* $fields_style **mixed**



### <a name="method-_getTxtFormatedAddress"></a>_getTxtFormatedAddress

    String PaymentModuleCore::_getTxtFormatedAddress($the_address)





* Visibility: **protected**
* Source: [classes/PaymentModule.php line 845](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#L845)


#### Arguments
* $the_address **mixed**



### <a name="method-addCheckboxCountryRestrictionsForModule"></a>addCheckboxCountryRestrictionsForModule

    boolean PaymentModuleCore::addCheckboxCountryRestrictionsForModule(array $shops)

Add checkbox country restrictions for a new module



* Visibility: **public**
* Source: [classes/PaymentModule.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#L134)


#### Arguments
* $shops **array**



### <a name="method-addCheckboxCurrencyRestrictionsForModule"></a>addCheckboxCurrencyRestrictionsForModule

    boolean PaymentModuleCore::addCheckboxCurrencyRestrictionsForModule(array $shops)

Add checkbox currency restrictions for a new module



* Visibility: **public**
* Source: [classes/PaymentModule.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#L91)


#### Arguments
* $shops **array**



### <a name="method-addCurrencyPermissions"></a>addCurrencyPermissions

    boolean PaymentModuleCore::addCurrencyPermissions(integer $id_currency, array $id_module_list)

Allows specified payment modules to be used by a specific currency



* Visibility: **public**
* This method is **static**.
* Source: [classes/PaymentModule.php line 914](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#L914)


#### Arguments
* $id_currency **integer**
* $id_module_list **array**



### <a name="method-addRadioCurrencyRestrictionsForModule"></a>addRadioCurrencyRestrictionsForModule

    boolean PaymentModuleCore::addRadioCurrencyRestrictionsForModule(array $shops)

Add radio currency restrictions for a new module



* Visibility: **public**
* Source: [classes/PaymentModule.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#L113)


#### Arguments
* $shops **array**



### <a name="method-formatProductAndVoucherForEmail"></a>formatProductAndVoucherForEmail

    mixed PaymentModuleCore::formatProductAndVoucherForEmail(mixed $content)





* Visibility: **public**
* Source: [classes/PaymentModule.php line 835](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#L835)


#### Arguments
* $content **mixed**



### <a name="method-getCurrency"></a>getCurrency

    \Currency PaymentModuleCore::getCurrency($current_id_currency)





* Visibility: **public**
* Source: [classes/PaymentModule.php line 876](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#L876)


#### Arguments
* $current_id_currency **mixed**



### <a name="method-getEmailTemplateContent"></a>getEmailTemplateContent

    string PaymentModuleCore::getEmailTemplateContent(string $template_name, integer $mail_type, array $var)

Fetch the content of $template_name inside the folder current_theme/mails/current_iso_lang/ if found, otherwise in mails/current_iso_lang



* Visibility: **protected**
* Source: [classes/PaymentModule.php line 987](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#L987)


#### Arguments
* $template_name **string** - template name with extension
* $mail_type **integer** - Mail::TYPE_HTML or Mail::TYPE_TXT
* $var **array** - list send to smarty



### <a name="method-getInstalledPaymentModules"></a>getInstalledPaymentModules

    array PaymentModuleCore::getInstalledPaymentModules()

List all installed and active payment modules



* Visibility: **public**
* This method is **static**.
* Source: [classes/PaymentModule.php line 945](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#L945)




### <a name="method-install"></a>install

    mixed PaymentModuleCore::install()





* Visibility: **public**
* Source: [classes/PaymentModule.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#L36)




### <a name="method-preCall"></a>preCall

    mixed PaymentModuleCore::preCall($module_name)





* Visibility: **public**
* This method is **static**.
* Source: [classes/PaymentModule.php line 962](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#L962)


#### Arguments
* $module_name **mixed**



### <a name="method-uninstall"></a>uninstall

    mixed PaymentModuleCore::uninstall()





* Visibility: **public**
* Source: [classes/PaymentModule.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#L74)




### <a name="method-validateOrder"></a>validateOrder

    boolean PaymentModuleCore::validateOrder(integer $id_cart, integer $id_order_state, float $amount_paid, string $payment_method, null $message, array $extra_vars, null $currency_special, boolean $dont_touch_amount, boolean $secure_key, \Shop $shop)

Validate an order in database
Function called from a payment module



* Visibility: **public**
* Source: [classes/PaymentModule.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#L162)


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
* $shop **[Shop](class.ShopCore)**


