LocalizationPackCore
===============






* Class name: LocalizationPackCore
* This class is defined in [classes/LocalizationPack.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#L27)





Properties
----------


### $name

    public mixed $name





* Visibility: **public**
* This property is defined in [classes/LocalizationPack.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#29)


### $version

    public mixed $version





* Visibility: **public**
* This property is defined in [classes/LocalizationPack.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#30)


### $iso_code_lang

    protected mixed $iso_code_lang





* Visibility: **protected**
* This property is defined in [classes/LocalizationPack.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#32)


### $iso_currency

    protected mixed $iso_currency





* Visibility: **protected**
* This property is defined in [classes/LocalizationPack.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#33)


### $_errors

    protected mixed $_errors = array()





* Visibility: **protected**
* This property is defined in [classes/LocalizationPack.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#34)


Methods
-------


### loadLocalisationPack

    mixed LocalizationPackCore::loadLocalisationPack($file, $selection, $install_mode, $iso_localization_pack)





* Visibility: **public**
* This method is defined in [classes/LocalizationPack.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#36)


#### Arguments
* $file **mixed**
* $selection **mixed**
* $install_mode **mixed**
* $iso_localization_pack **mixed**



### _installStates

    boolean LocalizationPackCore::_installStates(\SimpleXMLElement $xml)





* Visibility: **protected**
* This method is defined in [classes/LocalizationPack.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#109)


#### Arguments
* $xml **SimpleXMLElement**



### _installTaxes

    boolean LocalizationPackCore::_installTaxes(\SimpleXMLElement $xml)





* Visibility: **protected**
* This method is defined in [classes/LocalizationPack.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#175)


#### Arguments
* $xml **SimpleXMLElement**



### _installCurrencies

    boolean LocalizationPackCore::_installCurrencies(\SimpleXMLElement $xml, boolean $install_mode)





* Visibility: **protected**
* This method is defined in [classes/LocalizationPack.php line 280](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#280)


#### Arguments
* $xml **SimpleXMLElement**
* $install_mode **boolean**



### _installLanguages

    boolean LocalizationPackCore::_installLanguages(\SimpleXMLElement $xml, boolean $install_mode)





* Visibility: **protected**
* This method is defined in [classes/LocalizationPack.php line 330](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#330)


#### Arguments
* $xml **SimpleXMLElement**
* $install_mode **boolean**



### _installUnits

    boolean LocalizationPackCore::_installUnits(\SimpleXMLElement $xml)





* Visibility: **protected**
* This method is defined in [classes/LocalizationPack.php line 361](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#361)


#### Arguments
* $xml **SimpleXMLElement**



### installModules

    boolean LocalizationPackCore::installModules(\SimpleXMLElement $xml)

Install/Uninstall a module from a localization file
<modules>
<module name="module_name" [install="0|1"] />



* Visibility: **protected**
* This method is defined in [classes/LocalizationPack.php line 389](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#389)


#### Arguments
* $xml **SimpleXMLElement**



### installConfiguration

    boolean LocalizationPackCore::installConfiguration(\SimpleXMLElement $xml)

Update a configuration variable from a localization file
<configuration>
<configuration name="variable_name" value="variable_value" />



* Visibility: **protected**
* This method is defined in [classes/LocalizationPack.php line 429](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#429)


#### Arguments
* $xml **SimpleXMLElement**



### _installGroups

    boolean LocalizationPackCore::_installGroups(\SimpleXMLElement $xml)





* Visibility: **protected**
* This method is defined in [classes/LocalizationPack.php line 452](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#452)


#### Arguments
* $xml **SimpleXMLElement**



### updateDefaultGroupDisplayMethod

    boolean LocalizationPackCore::updateDefaultGroupDisplayMethod(\SimpleXMLElement $xml)





* Visibility: **protected**
* This method is defined in [classes/LocalizationPack.php line 461](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#461)


#### Arguments
* $xml **SimpleXMLElement**



### getErrors

    mixed LocalizationPackCore::getErrors()





* Visibility: **public**
* This method is defined in [classes/LocalizationPack.php line 483](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/LocalizationPack.php#483)



