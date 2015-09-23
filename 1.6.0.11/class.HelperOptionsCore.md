Class HelperOptionsCore
=====================

Use this helper to generate preferences forms, with values stored in the configuration table



* Class name: HelperOptionsCore
* Parent class: [Helper](class.HelperCore.md)
* Source: [classes/helper/HelperOptions.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/helper/HelperOptions.php#L30)


Contents
--------


### Properties

* [$required](#property-$required)

### Methods

* [__construct](#method-__construct)
* [displayOptionTypeDisabled](#method-displayOptionTypeDisabled)
* [displayOptionTypeImage](#method-displayOptionTypeImage)
* [displayOptionTypePrice](#method-displayOptionTypePrice)
* [generateOptions](#method-generateOptions)
* [getOptionValue](#method-getOptionValue)




Properties
----------


### <a name="property-$required"></a>$required

```php
public mixed $required = false
```





* Visibility: **public**
* Source: [classes/helper/HelperOptions.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/helper/HelperOptions.php#L32).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed HelperOptionsCore::__construct()
```





* Visibility: **public**
* Source: [classes/helper/HelperOptions.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/helper/HelperOptions.php#L34)




### <a name="method-displayOptionTypeDisabled"></a>displayOptionTypeDisabled

```php
mixed HelperOptionsCore::displayOptionTypeDisabled($key, $field, $value)
```

Type = disabled



* Visibility: **public**
* Source: [classes/helper/HelperOptions.php line 265](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/helper/HelperOptions.php#L265)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-displayOptionTypeImage"></a>displayOptionTypeImage

```php
mixed HelperOptionsCore::displayOptionTypeImage($key, $field, $value)
```

Type = image



* Visibility: **public**
* Source: [classes/helper/HelperOptions.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/helper/HelperOptions.php#L228)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-displayOptionTypePrice"></a>displayOptionTypePrice

```php
mixed HelperOptionsCore::displayOptionTypePrice($key, $field, $value)
```

Type = price



* Visibility: **public**
* Source: [classes/helper/HelperOptions.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/helper/HelperOptions.php#L255)


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### <a name="method-generateOptions"></a>generateOptions

```php
string HelperOptionsCore::generateOptions($option_list)
```

Generate a form for options



* Visibility: **public**
* Source: [classes/helper/HelperOptions.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/helper/HelperOptions.php#L46)


#### Arguments
* $option_list **mixed**



### <a name="method-getOptionValue"></a>getOptionValue

```php
mixed HelperOptionsCore::getOptionValue($key, $field)
```





* Visibility: **public**
* Source: [classes/helper/HelperOptions.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/helper/HelperOptions.php#L270)


#### Arguments
* $key **mixed**
* $field **mixed**


