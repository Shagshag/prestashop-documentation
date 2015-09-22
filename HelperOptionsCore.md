HelperOptionsCore
===============

Use this helper to generate preferences forms, with values stored in the configuration table




* Class name: HelperOptionsCore
* Parent class: [Helper](HelperCore)
* This class is defined in [classes/helper/HelperOptions.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperOptions.php#L30)





Properties
----------

* [$required](#property-$required)

Methods
-------
* [__construct](#method-__construct)
* [generateOptions](#method-generateOptions)
* [displayOptionTypeImage](#method-displayOptionTypeImage)
* [displayOptionTypePrice](#method-displayOptionTypePrice)
* [displayOptionTypeDisabled](#method-displayOptionTypeDisabled)
* [getOptionValue](#method-getOptionValue)




Properties
----------


### <a name="property-$required"></a>$required

    public mixed $required = false





* Visibility: **public**
* This property is defined in [classes/helper/HelperOptions.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperOptions.php#L32)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed HelperOptionsCore::__construct()





* Visibility: **public**
* This method is defined in [classes/helper/HelperOptions.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperOptions.php#L34)




### <a name="method-generateOptions"></a>generateOptions

    string HelperOptionsCore::generateOptions(array $option_list)

Generate a form for options



* Visibility: **public**
* This method is defined in [classes/helper/HelperOptions.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperOptions.php#L46)


#### Arguments
* $option_list **array**



### <a name="method-displayOptionTypeImage"></a>displayOptionTypeImage

    mixed HelperOptionsCore::displayOptionTypeImage($key, $field, $value)

Type = image



* Visibility: **public**
* This method is defined in [classes/helper/HelperOptions.php line 233](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperOptions.php#L233)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-displayOptionTypePrice"></a>displayOptionTypePrice

    mixed HelperOptionsCore::displayOptionTypePrice($key, $field, $value)

Type = price



* Visibility: **public**
* This method is defined in [classes/helper/HelperOptions.php line 260](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperOptions.php#L260)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-displayOptionTypeDisabled"></a>displayOptionTypeDisabled

    mixed HelperOptionsCore::displayOptionTypeDisabled($key, $field, $value)

Type = disabled



* Visibility: **public**
* This method is defined in [classes/helper/HelperOptions.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperOptions.php#L270)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-getOptionValue"></a>getOptionValue

    mixed HelperOptionsCore::getOptionValue($key, $field)





* Visibility: **public**
* This method is defined in [classes/helper/HelperOptions.php line 275](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperOptions.php#L275)


#### Arguments
* $key **mixed**
* $field **mixed**


