Class UpgraderCore
=====================





* Class name: UpgraderCore
* Source: [classes/Upgrader.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Upgrader.php#L27)


Contents
--------

### Constants

* [DEFAULT_CHECK_VERSION_DELAY_HOURS](#constant-DEFAULT_CHECK_VERSION_DELAY_HOURS)

### Properties

* [$autoupgrade](#property-$autoupgrade)
* [$autoupgrade_last_version](#property-$autoupgrade_last_version)
* [$autoupgrade_module](#property-$autoupgrade_module)
* [$autoupgrade_module_link](#property-$autoupgrade_module_link)
* [$changed_files](#property-$changed_files)
* [$changelog](#property-$changelog)
* [$link](#property-$link)
* [$md5](#property-$md5)
* [$missing_files](#property-$missing_files)
* [$need_upgrade](#property-$need_upgrade)
* [$rss_md5file_link_dir](#property-$rss_md5file_link_dir)
* [$rss_version_link](#property-$rss_version_link)
* [$version_is_modified](#property-$version_is_modified)
* [$version_name](#property-$version_name)
* [$version_num](#property-$version_num)

### Methods

* [__construct](#method-__construct)
* [__get](#method-__get)
* [addChangedFile](#method-addChangedFile)
* [addMissingFile](#method-addMissingFile)
* [browseXmlAndCompare](#method-browseXmlAndCompare)
* [checkPSVersion](#method-checkPSVersion)
* [compareChecksum](#method-compareChecksum)
* [downloadLast](#method-downloadLast)
* [getChangedFilesList](#method-getChangedFilesList)
* [isAuthenticPrestashopVersion](#method-isAuthenticPrestashopVersion)
* [isLastVersion](#method-isLastVersion)
* [loadFromConfig](#method-loadFromConfig)


Constants
----------


### <a name="constant-DEFAULT_CHECK_VERSION_DELAY_HOURS"></a>DEFAULT_CHECK_VERSION_DELAY_HOURS

```php
const DEFAULT_CHECK_VERSION_DELAY_HOURS = 24
```





* Source: [classes/Upgrader.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Upgrader.php#L29).


Properties
----------


### <a name="property-$autoupgrade"></a>$autoupgrade

```php
public mixed $autoupgrade
```





* Visibility: **public**
* Source: [classes/Upgrader.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Upgrader.php#L46).


### <a name="property-$autoupgrade_last_version"></a>$autoupgrade_last_version

```php
public mixed $autoupgrade_last_version
```





* Visibility: **public**
* Source: [classes/Upgrader.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Upgrader.php#L48).


### <a name="property-$autoupgrade_module"></a>$autoupgrade_module

```php
public mixed $autoupgrade_module
```





* Visibility: **public**
* Source: [classes/Upgrader.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Upgrader.php#L47).


### <a name="property-$autoupgrade_module_link"></a>$autoupgrade_module_link

```php
public mixed $autoupgrade_module_link
```





* Visibility: **public**
* Source: [classes/Upgrader.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Upgrader.php#L49).


### <a name="property-$changed_files"></a>$changed_files

```php
protected mixed $changed_files = array()
```





* Visibility: **protected**
* Source: [classes/Upgrader.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Upgrader.php#L36).


### <a name="property-$changelog"></a>$changelog

```php
public mixed $changelog
```





* Visibility: **public**
* Source: [classes/Upgrader.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Upgrader.php#L50).


### <a name="property-$link"></a>$link

```php
public string $link
```





* Visibility: **public**
* Source: [classes/Upgrader.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Upgrader.php#L45).


### <a name="property-$md5"></a>$md5

```php
public mixed $md5
```





* Visibility: **public**
* Source: [classes/Upgrader.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Upgrader.php#L51).


### <a name="property-$missing_files"></a>$missing_files

```php
protected mixed $missing_files = array()
```





* Visibility: **protected**
* Source: [classes/Upgrader.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Upgrader.php#L37).


### <a name="property-$need_upgrade"></a>$need_upgrade

```php
protected boolean $need_upgrade = false
```





* Visibility: **protected**
* Source: [classes/Upgrader.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Upgrader.php#L35).


### <a name="property-$rss_md5file_link_dir"></a>$rss_md5file_link_dir

```php
public mixed $rss_md5file_link_dir = 'http://api.prestashop.com/xml/md5/'
```





* Visibility: **public**
* Source: [classes/Upgrader.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Upgrader.php#L31).


### <a name="property-$rss_version_link"></a>$rss_version_link

```php
public mixed $rss_version_link = 'http://api.prestashop.com/xml/upgrader.xml'
```





* Visibility: **public**
* Source: [classes/Upgrader.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Upgrader.php#L30).


### <a name="property-$version_is_modified"></a>$version_is_modified

```php
public mixed $version_is_modified = null
```





* Visibility: **public**
* Source: [classes/Upgrader.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Upgrader.php#L41).


### <a name="property-$version_name"></a>$version_name

```php
public mixed $version_name
```





* Visibility: **public**
* Source: [classes/Upgrader.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Upgrader.php#L39).


### <a name="property-$version_num"></a>$version_num

```php
public mixed $version_num
```





* Visibility: **public**
* Source: [classes/Upgrader.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Upgrader.php#L40).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed UpgraderCore::__construct($autoload)
```





* Visibility: **public**
* Source: [classes/Upgrader.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Upgrader.php#L53)


#### Arguments
* $autoload **mixed**



### <a name="method-__get"></a>__get

```php
mixed UpgraderCore::__get($var)
```





* Visibility: **public**
* Source: [classes/Upgrader.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Upgrader.php#L62)


#### Arguments
* $var **mixed**



### <a name="method-addChangedFile"></a>addChangedFile

```php
mixed UpgraderCore::addChangedFile(string $path)
```

populate $this->changed_files with $path
in sub arrays  mail, translation and core items



* Visibility: **protected**
* Source: [classes/Upgrader.php line 218](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Upgrader.php#L218)


#### Arguments
* $path **string** - filepath to add, relative to _PS_ROOT_DIR_



### <a name="method-addMissingFile"></a>addMissingFile

```php
mixed UpgraderCore::addMissingFile(string $path)
```

populate $this->missing_files with $path



* Visibility: **protected**
* Source: [classes/Upgrader.php line 240](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Upgrader.php#L240)


#### Arguments
* $path **string** - filepath to add, relative to _PS_ROOT_DIR_



### <a name="method-browseXmlAndCompare"></a>browseXmlAndCompare

```php
mixed UpgraderCore::browseXmlAndCompare($node, $current_path, $level)
```





* Visibility: **protected**
* Source: [classes/Upgrader.php line 246](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Upgrader.php#L246)


#### Arguments
* $node **mixed**
* $current_path **mixed**
* $level **mixed**



### <a name="method-checkPSVersion"></a>checkPSVersion

```php
mixed UpgraderCore::checkPSVersion($force)
```

checkPSVersion ask to prestashop.com if there is a new version. return an array if yes, false otherwise



* Visibility: **public**
* Source: [classes/Upgrader.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Upgrader.php#L102)


#### Arguments
* $force **mixed**



### <a name="method-compareChecksum"></a>compareChecksum

```php
mixed UpgraderCore::compareChecksum($path, $original_sum)
```





* Visibility: **protected**
* Source: [classes/Upgrader.php line 278](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Upgrader.php#L278)


#### Arguments
* $path **mixed**
* $original_sum **mixed**



### <a name="method-downloadLast"></a>downloadLast

```php
boolean UpgraderCore::downloadLast(string $dest, string $filename)
```

downloadLast download the last version of PrestaShop and save it in $dest/$filename



* Visibility: **public**
* Source: [classes/Upgrader.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Upgrader.php#L77)


#### Arguments
* $dest **string** - directory where to save the file
* $filename **string** - new filename



### <a name="method-getChangedFilesList"></a>getChangedFilesList

```php
array UpgraderCore::getChangedFilesList()
```

return an array of files
that the md5file does not match to the original md5file (provided by $rss_md5file_link_dir )



* Visibility: **public**
* Source: [classes/Upgrader.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Upgrader.php#L198)




### <a name="method-isAuthenticPrestashopVersion"></a>isAuthenticPrestashopVersion

```php
mixed UpgraderCore::isAuthenticPrestashopVersion()
```





* Visibility: **public**
* Source: [classes/Upgrader.php line 285](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Upgrader.php#L285)




### <a name="method-isLastVersion"></a>isLastVersion

```php
mixed UpgraderCore::isLastVersion()
```





* Visibility: **public**
* Source: [classes/Upgrader.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Upgrader.php#L88)




### <a name="method-loadFromConfig"></a>loadFromConfig

```php
\UpgraderCore UpgraderCore::loadFromConfig()
```

load the last version informations stocked in base



* Visibility: **public**
* Source: [classes/Upgrader.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Upgrader.php#L164)



