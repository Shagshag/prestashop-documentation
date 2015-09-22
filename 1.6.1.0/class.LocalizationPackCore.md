Class LocalizationPackCore
=====================





* Class name: LocalizationPackCore
* Source: [classes/LocalizationPack.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/LocalizationPack.php#L27)


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
* Source: [classes/LocalizationPack.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/LocalizationPack.php#L34).


### <a name="property-$iso_code_lang"></a>$iso_code_lang

```php
protected mixed $iso_code_lang
```





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/LocalizationPack.php#L32).


### <a name="property-$iso_currency"></a>$iso_currency

```php
protected mixed $iso_currency
```





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/LocalizationPack.php#L33).


### <a name="property-$name"></a>$name

```php
public mixed $name
```





* Visibility: **public**
* Source: [classes/LocalizationPack.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/LocalizationPack.php#L29).


### <a name="property-$version"></a>$version

```php
public mixed $version
```





* Visibility: **public**
* Source: [classes/LocalizationPack.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/LocalizationPack.php#L30).


Methods
-------


### <a name="method-_installCurrencies"></a>_installCurrencies

```php
boolean LocalizationPackCore::_installCurrencies(\SimpleXMLElement $xml, boolean $install_mode)
```





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 286](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/LocalizationPack.php#L286)


#### Arguments
* $xml **SimpleXMLElement**
* $install_mode **boolean**



### <a name="method-_installGroups"></a>_installGroups

```php
boolean LocalizationPackCore::_installGroups(\SimpleXMLElement $xml)
```





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 457](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/LocalizationPack.php#L457)


#### Arguments
* $xml **SimpleXMLElement**



### <a name="method-_installLanguages"></a>_installLanguages

```php
boolean LocalizationPackCore::_installLanguages(\SimpleXMLElement $xml, boolean $install_mode)
```





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 338](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/LocalizationPack.php#L338)


#### Arguments
* $xml **SimpleXMLElement**
* $install_mode **boolean**



### <a name="method-_installStates"></a>_installStates

```php
boolean LocalizationPackCore::_installStates(\SimpleXMLElement $xml)
```





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/LocalizationPack.php#L104)


#### Arguments
* $xml **SimpleXMLElement**



### <a name="method-_installTaxes"></a>_installTaxes

```php
boolean LocalizationPackCore::_installTaxes(\SimpleXMLElement $xml)
```





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/LocalizationPack.php#L178)


#### Arguments
* $xml **SimpleXMLElement**



### <a name="method-_installUnits"></a>_installUnits

```php
boolean LocalizationPackCore::_installUnits(\SimpleXMLElement $xml)
```





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 366](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/LocalizationPack.php#L366)


#### Arguments
* $xml **SimpleXMLElement**



### <a name="method-getErrors"></a>getErrors

```php
mixed LocalizationPackCore::getErrors()
```





* Visibility: **public**
* Source: [classes/LocalizationPack.php line 490](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/LocalizationPack.php#L490)




### <a name="method-installConfiguration"></a>installConfiguration

```php
boolean LocalizationPackCore::installConfiguration(\SimpleXMLElement $xml)
```

Update a configuration variable from a localization file
<configuration>
<configuration name="variable_name" value="variable_value" />



* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 436](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/LocalizationPack.php#L436)


#### Arguments
* $xml **SimpleXMLElement**



### <a name="method-installModules"></a>installModules

```php
boolean LocalizationPackCore::installModules(\SimpleXMLElement $xml)
```

Install/Uninstall a module from a localization file
<modules>
<module name="module_name" [install="0|1"] />



* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 396](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/LocalizationPack.php#L396)


#### Arguments
* $xml **SimpleXMLElement**



### <a name="method-loadLocalisationPack"></a>loadLocalisationPack

```php
mixed LocalizationPackCore::loadLocalisationPack($file, $selection, $install_mode, $iso_localization_pack)
```





* Visibility: **public**
* Source: [classes/LocalizationPack.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/LocalizationPack.php#L36)


#### Arguments
* $file **mixed**
* $selection **mixed**
* $install_mode **mixed**
* $iso_localization_pack **mixed**



### <a name="method-updateDefaultGroupDisplayMethod"></a>updateDefaultGroupDisplayMethod

```php
boolean LocalizationPackCore::updateDefaultGroupDisplayMethod(\SimpleXMLElement $xml)
```





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 466](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/LocalizationPack.php#L466)


#### Arguments
* $xml **SimpleXMLElement**


