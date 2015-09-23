Class HelpAccessCore
=====================





* Class name: HelpAccessCore
* Source: [classes/HelpAccess.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/HelpAccess.php#L28)


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





* Source: [classes/HelpAccess.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/HelpAccess.php#L30).




Methods
-------


### <a name="method-getVersion"></a>getVersion

```php
mixed HelpAccessCore::getVersion($label)
```

Returns the last version seen of a help page seen by the user



* Visibility: **public**
* This method is **static**.
* Source: [classes/HelpAccess.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/HelpAccess.php#L54)


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
* Source: [classes/HelpAccess.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/HelpAccess.php#L76)


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
* Source: [classes/HelpAccess.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/HelpAccess.php#L39)


#### Arguments
* $label **mixed**
* $version **mixed**


