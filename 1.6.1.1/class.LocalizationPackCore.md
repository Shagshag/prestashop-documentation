Class LocalizationPackCore
=====================





* Class name: LocalizationPackCore
* Source: [classes/LocalizationPack.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#L27)



Properties
----------

* [$_errors](#property-$_errors)
* [$iso_code_lang](#property-$iso_code_lang)
* [$iso_currency](#property-$iso_currency)
* [$name](#property-$name)
* [$version](#property-$version)

Methods
-------
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

    protected mixed $_errors = array()





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#L34)


### <a name="property-$iso_code_lang"></a>$iso_code_lang

    protected mixed $iso_code_lang





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#L32)


### <a name="property-$iso_currency"></a>$iso_currency

    protected mixed $iso_currency





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#L33)


### <a name="property-$name"></a>$name

    public mixed $name





* Visibility: **public**
* Source: [classes/LocalizationPack.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#L29)


### <a name="property-$version"></a>$version

    public mixed $version





* Visibility: **public**
* Source: [classes/LocalizationPack.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#L30)


Methods
-------


### <a name="method-_installCurrencies"></a>_installCurrencies

    boolean LocalizationPackCore::_installCurrencies(\SimpleXMLElement $xml, boolean $install_mode)





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 280](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#L280)


#### Arguments
* $xml **SimpleXMLElement**
* $install_mode **boolean**



### <a name="method-_installGroups"></a>_installGroups

    boolean LocalizationPackCore::_installGroups(\SimpleXMLElement $xml)





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 452](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#L452)


#### Arguments
* $xml **SimpleXMLElement**



### <a name="method-_installLanguages"></a>_installLanguages

    boolean LocalizationPackCore::_installLanguages(\SimpleXMLElement $xml, boolean $install_mode)





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 330](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#L330)


#### Arguments
* $xml **SimpleXMLElement**
* $install_mode **boolean**



### <a name="method-_installStates"></a>_installStates

    boolean LocalizationPackCore::_installStates(\SimpleXMLElement $xml)





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#L109)


#### Arguments
* $xml **SimpleXMLElement**



### <a name="method-_installTaxes"></a>_installTaxes

    boolean LocalizationPackCore::_installTaxes(\SimpleXMLElement $xml)





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#L175)


#### Arguments
* $xml **SimpleXMLElement**



### <a name="method-_installUnits"></a>_installUnits

    boolean LocalizationPackCore::_installUnits(\SimpleXMLElement $xml)





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 361](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#L361)


#### Arguments
* $xml **SimpleXMLElement**



### <a name="method-getErrors"></a>getErrors

    mixed LocalizationPackCore::getErrors()





* Visibility: **public**
* Source: [classes/LocalizationPack.php line 483](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#L483)




### <a name="method-installConfiguration"></a>installConfiguration

    boolean LocalizationPackCore::installConfiguration(\SimpleXMLElement $xml)

Update a configuration variable from a localization file
<configuration>
<configuration name="variable_name" value="variable_value" />



* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 429](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#L429)


#### Arguments
* $xml **SimpleXMLElement**



### <a name="method-installModules"></a>installModules

    boolean LocalizationPackCore::installModules(\SimpleXMLElement $xml)

Install/Uninstall a module from a localization file
<modules>
<module name="module_name" [install="0|1"] />



* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 389](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#L389)


#### Arguments
* $xml **SimpleXMLElement**



### <a name="method-loadLocalisationPack"></a>loadLocalisationPack

    mixed LocalizationPackCore::loadLocalisationPack($file, $selection, $install_mode, $iso_localization_pack)





* Visibility: **public**
* Source: [classes/LocalizationPack.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#L36)


#### Arguments
* $file **mixed**
* $selection **mixed**
* $install_mode **mixed**
* $iso_localization_pack **mixed**



### <a name="method-updateDefaultGroupDisplayMethod"></a>updateDefaultGroupDisplayMethod

    boolean LocalizationPackCore::updateDefaultGroupDisplayMethod(\SimpleXMLElement $xml)





* Visibility: **protected**
* Source: [classes/LocalizationPack.php line 461](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#L461)


#### Arguments
* $xml **SimpleXMLElement**


