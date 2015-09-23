Class HelpAccessCore
=====================





* Class name: HelpAccessCore
* Source: [classes/HelpAccess.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/HelpAccess.php#L29)


Contents
--------

### Constants

* [URL](#constant-URL)

### Properties

* [$_images](#property-$_images)

### Methods

* [displayHelp](#method-displayHelp)
* [getHelp](#method-getHelp)
* [getVersion](#method-getVersion)
* [retrieveInfos](#method-retrieveInfos)
* [trackClick](#method-trackClick)


Constants
----------


### <a name="constant-URL"></a>URL

```php
const URL = 'http://help.prestashop.com'
```





* Source: [classes/HelpAccess.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/HelpAccess.php#L31).


Properties
----------


### <a name="property-$_images"></a>$_images

```php
protected mixed $_images = array(0 => 'none', 1 => 'help2.png', 2 => 'help-new.png')
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/HelpAccess.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/HelpAccess.php#L33).


Methods
-------


### <a name="method-displayHelp"></a>displayHelp

```php
mixed HelpAccessCore::displayHelp($label, $iso_lang, $country, $ps_version)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/HelpAccess.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/HelpAccess.php#L84)


#### Arguments
* $label **mixed**
* $iso_lang **mixed**
* $country **mixed**
* $ps_version **mixed**



### <a name="method-getHelp"></a>getHelp

```php
mixed HelpAccessCore::getHelp($label, $iso_lang, $country, $ps_version)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/HelpAccess.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/HelpAccess.php#L89)


#### Arguments
* $label **mixed**
* $iso_lang **mixed**
* $country **mixed**
* $ps_version **mixed**



### <a name="method-getVersion"></a>getVersion

```php
mixed HelpAccessCore::getVersion($label)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/HelpAccess.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/HelpAccess.php#L45)


#### Arguments
* $label **mixed**



### <a name="method-retrieveInfos"></a>retrieveInfos

```php
mixed HelpAccessCore::retrieveInfos($label, $iso_lang, $country, $version)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/HelpAccess.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/HelpAccess.php#L53)


#### Arguments
* $label **mixed**
* $iso_lang **mixed**
* $country **mixed**
* $version **mixed**



### <a name="method-trackClick"></a>trackClick

```php
mixed HelpAccessCore::trackClick($label, $version)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/HelpAccess.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/HelpAccess.php#L37)


#### Arguments
* $label **mixed**
* $version **mixed**


