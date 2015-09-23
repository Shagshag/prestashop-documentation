Class LocalizationPackCore
=====================





* Class name: LocalizationPackCore
* Source: [classes/LocalizationPack.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/LocalizationPack.php#L27)


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
* [_installGroups](#method-_installGroups)
* [_installLanguages](#method-_installLanguages)
* [_installStates](#method-_installStates)
* [_installTaxes](#method-_installTaxes)
* [_installUnits](#method-_installUnits)
* [getErrors](#method-getErrors)
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
* Source: [classes/LocalizationPack.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/LocalizationPack.php#L34).


### <a name="property-$iso_code_lang"></a>$iso_code_lang

```php
protected mixed $iso_code_lang
```





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/LocalizationPack.php#L32).


### <a name="property-$iso_currency"></a>$iso_currency

```php
protected mixed $iso_currency
```





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/LocalizationPack.php#L33).


### <a name="property-$name"></a>$name

```php
public mixed $name
```





* Visibility: **public**
* Source: [classes/LocalizationPack.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/LocalizationPack.php#L29).


### <a name="property-$version"></a>$version

```php
public mixed $version
```





* Visibility: **public**
* Source: [classes/LocalizationPack.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/LocalizationPack.php#L30).


Methods
-------


### <a name="method-_installCurrencies"></a>_installCurrencies

```php
mixed LocalizationPackCore::_installCurrencies($xml, $install_mode)
```





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 257](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/LocalizationPack.php#L257)


#### Arguments
* $xml **mixed**
* $install_mode **mixed**



### <a name="method-_installGroups"></a>_installGroups

```php
mixed LocalizationPackCore::_installGroups($xml)
```





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 402](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/LocalizationPack.php#L402)


#### Arguments
* $xml **mixed**



### <a name="method-_installLanguages"></a>_installLanguages

```php
mixed LocalizationPackCore::_installLanguages($xml, $install_mode)
```





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 303](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/LocalizationPack.php#L303)


#### Arguments
* $xml **mixed**
* $install_mode **mixed**



### <a name="method-_installStates"></a>_installStates

```php
mixed LocalizationPackCore::_installStates($xml)
```





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/LocalizationPack.php#L93)


#### Arguments
* $xml **mixed**



### <a name="method-_installTaxes"></a>_installTaxes

```php
mixed LocalizationPackCore::_installTaxes($xml)
```





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 161](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/LocalizationPack.php#L161)


#### Arguments
* $xml **mixed**



### <a name="method-_installUnits"></a>_installUnits

```php
mixed LocalizationPackCore::_installUnits($xml)
```





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 324](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/LocalizationPack.php#L324)


#### Arguments
* $xml **mixed**



### <a name="method-getErrors"></a>getErrors

```php
mixed LocalizationPackCore::getErrors()
```





* Visibility: **public**
* Source: [classes/LocalizationPack.php line 429](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/LocalizationPack.php#L429)




### <a name="method-installConfiguration"></a>installConfiguration

```php
mixed LocalizationPackCore::installConfiguration($xml)
```

Update a configuration variable from a localization file
<configuration>
<configuration name="variable_name" value="variable_value" />



* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 386](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/LocalizationPack.php#L386)


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
* Source: [classes/LocalizationPack.php line 350](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/LocalizationPack.php#L350)


#### Arguments
* $xml **mixed**



### <a name="method-loadLocalisationPack"></a>loadLocalisationPack

```php
mixed LocalizationPackCore::loadLocalisationPack($file, $selection, $install_mode, $iso_localization_pack)
```





* Visibility: **public**
* Source: [classes/LocalizationPack.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/LocalizationPack.php#L36)


#### Arguments
* $file **mixed**
* $selection **mixed**
* $install_mode **mixed**
* $iso_localization_pack **mixed**



### <a name="method-updateDefaultGroupDisplayMethod"></a>updateDefaultGroupDisplayMethod

```php
mixed LocalizationPackCore::updateDefaultGroupDisplayMethod($xml)
```





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 407](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/LocalizationPack.php#L407)


#### Arguments
* $xml **mixed**


