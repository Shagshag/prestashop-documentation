Class HelpAccessCore
=====================





* Class name: HelpAccessCore
* Source: [classes/HelpAccess.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/HelpAccess.php#L29)


Contents
--------

### Constants

* [URL](#constant-URL)


### Methods

* [getVersion](#method-getVersion)
* [retrieveInfos](#method-retrieveInfos)
* [trackClick](#method-trackClick)


Constants
----------


### <a name="constant-URL"></a>URL

```php
const URL = 'http://help.prestashop.com'
```





* Source: [classes/HelpAccess.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/HelpAccess.php#L31).




Methods
-------


### <a name="method-getVersion"></a>getVersion

```php
mixed HelpAccessCore::getVersion($label)
```

Returns the last version seen of a help page seen by the user



* Visibility: **public**
* This method is **static**.
* Source: [classes/HelpAccess.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/HelpAccess.php#L55)


#### Arguments
* $label **mixed**



### <a name="method-retrieveInfos"></a>retrieveInfos

```php
array HelpAccessCore::retrieveInfos($label, $iso_lang, $country, $version)
```

Fetch information from the help website in order to know:
- if the help page exists
- his version
- the associated tooltip



* Visibility: **public**
* This method is **static**.
* Source: [classes/HelpAccess.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/HelpAccess.php#L77)


#### Arguments
* $label **mixed**
* $iso_lang **mixed**
* $country **mixed**
* $version **mixed**



### <a name="method-trackClick"></a>trackClick

```php
mixed HelpAccessCore::trackClick($label, $version)
```

Store in the local database that the user has seen a specific help page



* Visibility: **public**
* This method is **static**.
* Source: [classes/HelpAccess.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/HelpAccess.php#L40)


#### Arguments
* $label **mixed**
* $version **mixed**


