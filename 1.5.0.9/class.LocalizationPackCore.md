Class LocalizationPackCore
=====================





* Class name: LocalizationPackCore
* Source: [classes/LocalizationPack.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/LocalizationPack.php#L30)


Contents
--------


### Properties

* [$_errors](#property-$_errors)
* [$iso_code_lang](#property-$iso_code_lang)
* [$iso_currency](#property-$iso_currency)
* [$name](#property-$name)
* [$version](#property-$version)

### Methods

* [_installCurrencies](#method-_installCurrencies)
* [_installLanguages](#method-_installLanguages)
* [_installStates](#method-_installStates)
* [_installTaxes](#method-_installTaxes)
* [_installUnits](#method-_installUnits)
* [getErrors](#method-getErrors)
* [installAccounting](#method-installAccounting)
* [installConfiguration](#method-installConfiguration)
* [installModules](#method-installModules)
* [loadLocalisationPack](#method-loadLocalisationPack)
* [updateDefaultGroupDisplayMethod](#method-updateDefaultGroupDisplayMethod)




Properties
----------


### <a name="property-$_errors"></a>$_errors

```php
protected mixed $_errors = array()
```





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/LocalizationPack.php#L37).


### <a name="property-$iso_code_lang"></a>$iso_code_lang

```php
protected mixed $iso_code_lang
```





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/LocalizationPack.php#L35).


### <a name="property-$iso_currency"></a>$iso_currency

```php
protected mixed $iso_currency
```





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/LocalizationPack.php#L36).


### <a name="property-$name"></a>$name

```php
public mixed $name
```





* Visibility: **public**
* Source: [classes/LocalizationPack.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/LocalizationPack.php#L32).


### <a name="property-$version"></a>$version

```php
public mixed $version
```





* Visibility: **public**
* Source: [classes/LocalizationPack.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/LocalizationPack.php#L33).


Methods
-------


### <a name="method-_installCurrencies"></a>_installCurrencies

```php
mixed LocalizationPackCore::_installCurrencies($xml, $install_mode)
```





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 263](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/LocalizationPack.php#L263)


#### Arguments
* $xml **mixed**
* $install_mode **mixed**



### <a name="method-_installLanguages"></a>_installLanguages

```php
mixed LocalizationPackCore::_installLanguages($xml, $install_mode)
```





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 312](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/LocalizationPack.php#L312)


#### Arguments
* $xml **mixed**
* $install_mode **mixed**



### <a name="method-_installStates"></a>_installStates

```php
mixed LocalizationPackCore::_installStates($xml)
```





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/LocalizationPack.php#L103)


#### Arguments
* $xml **mixed**



### <a name="method-_installTaxes"></a>_installTaxes

```php
mixed LocalizationPackCore::_installTaxes($xml)
```





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/LocalizationPack.php#L166)


#### Arguments
* $xml **mixed**



### <a name="method-_installUnits"></a>_installUnits

```php
mixed LocalizationPackCore::_installUnits($xml)
```





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 372](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/LocalizationPack.php#L372)


#### Arguments
* $xml **mixed**



### <a name="method-getErrors"></a>getErrors

```php
mixed LocalizationPackCore::getErrors()
```





* Visibility: **public**
* Source: [classes/LocalizationPack.php line 469](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/LocalizationPack.php#L469)




### <a name="method-installAccounting"></a>installAccounting

```php
true LocalizationPackCore::installAccounting($xml)
```

Install the default value for accounting



* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/LocalizationPack.php#L85)


#### Arguments
* $xml **mixed**



### <a name="method-installConfiguration"></a>installConfiguration

```php
mixed LocalizationPackCore::installConfiguration($xml)
```

Update a configuration variable from a localization file
<configuration>
<configuration name="variable_name" value="variable_value" />



* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 434](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/LocalizationPack.php#L434)


#### Arguments
* $xml **mixed**



### <a name="method-installModules"></a>installModules

```php
mixed LocalizationPackCore::installModules($xml)
```

Install/Uninstall a module from a localization file
<modules>
<module name="module_name" [install="0|1"] />



* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 398](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/LocalizationPack.php#L398)


#### Arguments
* $xml **mixed**



### <a name="method-loadLocalisationPack"></a>loadLocalisationPack

```php
mixed LocalizationPackCore::loadLocalisationPack($file, $selection, $install_mode)
```





* Visibility: **public**
* Source: [classes/LocalizationPack.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/LocalizationPack.php#L39)


#### Arguments
* $file **mixed**
* $selection **mixed**
* $install_mode **mixed**



### <a name="method-updateDefaultGroupDisplayMethod"></a>updateDefaultGroupDisplayMethod

```php
mixed LocalizationPackCore::updateDefaultGroupDisplayMethod($xml)
```





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 450](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/LocalizationPack.php#L450)


#### Arguments
* $xml **mixed**


