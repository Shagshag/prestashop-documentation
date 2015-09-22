PaymentModuleCore
===============






* Class name: PaymentModuleCore
* This is an **abstract** class
* Parent class: [Module](ModuleCore)
* This class is defined in [classes/PaymentModule.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#L27)



Constants
----------


### DEBUG_MODE

    const DEBUG_MODE = false



* This constant is defined in [classes/PaymentModule.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#34)


Properties
----------


### $currentOrder

    public integer $currentOrder





* Visibility: **public**
* This property is defined in [classes/PaymentModule.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#30)


### $currencies

    public mixed $currencies = true





* Visibility: **public**
* This property is defined in [classes/PaymentModule.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#31)


### $currencies_mode

    public mixed $currencies_mode = 'checkbox'





* Visibility: **public**
* This property is defined in [classes/PaymentModule.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#32)


Methods
-------


### install

    mixed PaymentModuleCore::install()





* Visibility: **public**
* This method is defined in [classes/PaymentModule.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#36)




### uninstall

    mixed PaymentModuleCore::uninstall()





* Visibility: **public**
* This method is defined in [classes/PaymentModule.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#74)




### addCheckboxCurrencyRestrictionsForModule

    boolean PaymentModuleCore::addCheckboxCurrencyRestrictionsForModule(array $shops)

Add checkbox currency restrictions for a new module



* Visibility: **public**
* This method is defined in [classes/PaymentModule.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#91)


#### Arguments
* $shops **array**



### addRadioCurrencyRestrictionsForModule

    boolean PaymentModuleCore::addRadioCurrencyRestrictionsForModule(array $shops)

Add radio currency restrictions for a new module



* Visibility: **public**
* This method is defined in [classes/PaymentModule.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#113)


#### Arguments
* $shops **array**



### addCheckboxCountryRestrictionsForModule

    boolean PaymentModuleCore::addCheckboxCountryRestrictionsForModule(array $shops)

Add checkbox country restrictions for a new module



* Visibility: **public**
* This method is defined in [classes/PaymentModule.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#134)


#### Arguments
* $shops **array**



### validateOrder

    boolean PaymentModuleCore::validateOrder(integer $id_cart, integer $id_order_state, float $amount_paid, string $payment_method, null $message, array $extra_vars, null $currency_special, boolean $dont_touch_amount, boolean $secure_key, \Shop $shop)

Validate an order in database
Function called from a payment module



* Visibility: **public**
* This method is defined in [classes/PaymentModule.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#162)


#### Arguments
* $id_cart **integer**
* $id_order_state **integer**
* $amount_paid **float** - &lt;p&gt;Amount really paid by customer (in the default currency)&lt;/p&gt;
* $payment_method **string** - &lt;p&gt;Payment method (eg. &#039;Credit card&#039;)&lt;/p&gt;
* $message **null** - &lt;p&gt;Message to attach to order&lt;/p&gt;
* $extra_vars **array**
* $currency_special **null**
* $dont_touch_amount **boolean**
* $secure_key **boolean**
* $shop **[Shop](ShopCore)**



### formatProductAndVoucherForEmail

    mixed PaymentModuleCore::formatProductAndVoucherForEmail(mixed $content)





* Visibility: **public**
* This method is defined in [classes/PaymentModule.php line 835](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#835)


#### Arguments
* $content **mixed**



### _getTxtFormatedAddress

    String PaymentModuleCore::_getTxtFormatedAddress($the_address)





* Visibility: **protected**
* This method is defined in [classes/PaymentModule.php line 845](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#845)


#### Arguments
* $the_address **mixed**



### _getFormatedAddress

    String PaymentModuleCore::_getFormatedAddress(\Address $the_address, $line_sep, $fields_style)





* Visibility: **protected**
* This method is defined in [classes/PaymentModule.php line 867](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#867)


#### Arguments
* $the_address **[Address](AddressCore)**
* $line_sep **mixed**
* $fields_style **mixed**



### getCurrency

    \Currency PaymentModuleCore::getCurrency($current_id_currency)





* Visibility: **public**
* This method is defined in [classes/PaymentModule.php line 876](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#876)


#### Arguments
* $current_id_currency **mixed**



### addCurrencyPermissions

    boolean PaymentModuleCore::addCurrencyPermissions(integer $id_currency, array $id_module_list)

Allows specified payment modules to be used by a specific currency



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/PaymentModule.php line 914](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#914)


#### Arguments
* $id_currency **integer**
* $id_module_list **array**



### getInstalledPaymentModules

    array PaymentModuleCore::getInstalledPaymentModules()

List all installed and active payment modules



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/PaymentModule.php line 945](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#945)




### preCall

    mixed PaymentModuleCore::preCall($module_name)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/PaymentModule.php line 962](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#962)


#### Arguments
* $module_name **mixed**



### getEmailTemplateContent

    string PaymentModuleCore::getEmailTemplateContent(string $template_name, integer $mail_type, array $var)

Fetch the content of $template_name inside the folder current_theme/mails/current_iso_lang/ if found, otherwise in mails/current_iso_lang



* Visibility: **protected**
* This method is defined in [classes/PaymentModule.php line 987](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentModule.php#987)


#### Arguments
* $template_name **string** - &lt;p&gt;template name with extension&lt;/p&gt;
* $mail_type **integer** - &lt;p&gt;Mail::TYPE_HTML or Mail::TYPE_TXT&lt;/p&gt;
* $var **array** - &lt;p&gt;list send to smarty&lt;/p&gt;


