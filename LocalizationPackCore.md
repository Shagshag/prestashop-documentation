LocalizationPackCore
===============






* Class name: LocalizationPackCore
* Namespace: 





Properties
----------


### $name

    public mixed $name





* Visibility: **public**


### $version

    public mixed $version





* Visibility: **public**


### $iso_code_lang

    protected mixed $iso_code_lang





* Visibility: **protected**


### $iso_currency

    protected mixed $iso_currency





* Visibility: **protected**


### $_errors

    protected mixed $_errors = array()





* Visibility: **protected**


Methods
-------


### loadLocalisationPack

    mixed LocalizationPackCore::loadLocalisationPack($file, $selection, $install_mode, $iso_localization_pack)





* Visibility: **public**


#### Arguments
* $file **mixed**
* $selection **mixed**
* $install_mode **mixed**
* $iso_localization_pack **mixed**



### _installStates

    boolean LocalizationPackCore::_installStates(\SimpleXMLElement $xml)





* Visibility: **protected**


#### Arguments
* $xml **SimpleXMLElement**



### _installTaxes

    boolean LocalizationPackCore::_installTaxes(\SimpleXMLElement $xml)





* Visibility: **protected**


#### Arguments
* $xml **SimpleXMLElement**



### _installCurrencies

    boolean LocalizationPackCore::_installCurrencies(\SimpleXMLElement $xml, boolean $install_mode)





* Visibility: **protected**


#### Arguments
* $xml **SimpleXMLElement**
* $install_mode **boolean**



### _installLanguages

    boolean LocalizationPackCore::_installLanguages(\SimpleXMLElement $xml, boolean $install_mode)





* Visibility: **protected**


#### Arguments
* $xml **SimpleXMLElement**
* $install_mode **boolean**



### _installUnits

    boolean LocalizationPackCore::_installUnits(\SimpleXMLElement $xml)





* Visibility: **protected**


#### Arguments
* $xml **SimpleXMLElement**



### installModules

    boolean LocalizationPackCore::installModules(\SimpleXMLElement $xml)

Install/Uninstall a module from a localization file
<modules>
<module name="module_name" [install="0|1"] />



* Visibility: **protected**


#### Arguments
* $xml **SimpleXMLElement**



### installConfiguration

    boolean LocalizationPackCore::installConfiguration(\SimpleXMLElement $xml)

Update a configuration variable from a localization file
<configuration>
<configuration name="variable_name" value="variable_value" />



* Visibility: **protected**


#### Arguments
* $xml **SimpleXMLElement**



### _installGroups

    boolean LocalizationPackCore::_installGroups(\SimpleXMLElement $xml)





* Visibility: **protected**


#### Arguments
* $xml **SimpleXMLElement**



### updateDefaultGroupDisplayMethod

    boolean LocalizationPackCore::updateDefaultGroupDisplayMethod(\SimpleXMLElement $xml)





* Visibility: **protected**


#### Arguments
* $xml **SimpleXMLElement**



### getErrors

    mixed LocalizationPackCore::getErrors()





* Visibility: **public**



