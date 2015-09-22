UpgraderCore
===============






* Class name: UpgraderCore
* This class is defined in [classes/Upgrader.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#L27)



Constants
----------

* [DEFAULT_CHECK_VERSION_DELAY_HOURS](#constant-DEFAULT_CHECK_VERSION_DELAY_HOURS)

Properties
----------

* [$rss_version_link](#property-$rss_version_link)
* [$rss_md5file_link_dir](#property-$rss_md5file_link_dir)
* [$need_upgrade](#property-$need_upgrade)
* [$changed_files](#property-$changed_files)
* [$missing_files](#property-$missing_files)
* [$version_name](#property-$version_name)
* [$version_num](#property-$version_num)
* [$version_is_modified](#property-$version_is_modified)
* [$link](#property-$link)
* [$autoupgrade](#property-$autoupgrade)
* [$autoupgrade_module](#property-$autoupgrade_module)
* [$autoupgrade_last_version](#property-$autoupgrade_last_version)
* [$autoupgrade_module_link](#property-$autoupgrade_module_link)
* [$changelog](#property-$changelog)
* [$md5](#property-$md5)

Methods
-------
* [__construct](#method-__construct)
* [__get](#method-__get)
* [downloadLast](#method-downloadLast)
* [isLastVersion](#method-isLastVersion)
* [checkPSVersion](#method-checkPSVersion)
* [loadFromConfig](#method-loadFromConfig)
* [getChangedFilesList](#method-getChangedFilesList)
* [addChangedFile](#method-addChangedFile)
* [addMissingFile](#method-addMissingFile)
* [browseXmlAndCompare](#method-browseXmlAndCompare)
* [compareChecksum](#method-compareChecksum)
* [isAuthenticPrestashopVersion](#method-isAuthenticPrestashopVersion)


Constants
----------


### <a name="constant-DEFAULT_CHECK_VERSION_DELAY_HOURS"></a>DEFAULT_CHECK_VERSION_DELAY_HOURS

    const DEFAULT_CHECK_VERSION_DELAY_HOURS = 24



* This constant is defined in [classes/Upgrader.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#L29)


Properties
----------


### <a name="property-$rss_version_link"></a>$rss_version_link

    public mixed $rss_version_link





* Visibility: **public**
* This property is defined in [classes/Upgrader.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#L30)


### <a name="property-$rss_md5file_link_dir"></a>$rss_md5file_link_dir

    public mixed $rss_md5file_link_dir





* Visibility: **public**
* This property is defined in [classes/Upgrader.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#L31)


### <a name="property-$need_upgrade"></a>$need_upgrade

    protected boolean $need_upgrade = false





* Visibility: **protected**
* This property is defined in [classes/Upgrader.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#L35)


### <a name="property-$changed_files"></a>$changed_files

    protected mixed $changed_files = array()





* Visibility: **protected**
* This property is defined in [classes/Upgrader.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#L36)


### <a name="property-$missing_files"></a>$missing_files

    protected mixed $missing_files = array()





* Visibility: **protected**
* This property is defined in [classes/Upgrader.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#L37)


### <a name="property-$version_name"></a>$version_name

    public mixed $version_name





* Visibility: **public**
* This property is defined in [classes/Upgrader.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#L39)


### <a name="property-$version_num"></a>$version_num

    public mixed $version_num





* Visibility: **public**
* This property is defined in [classes/Upgrader.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#L40)


### <a name="property-$version_is_modified"></a>$version_is_modified

    public mixed $version_is_modified = null





* Visibility: **public**
* This property is defined in [classes/Upgrader.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#L41)


### <a name="property-$link"></a>$link

    public string $link





* Visibility: **public**
* This property is defined in [classes/Upgrader.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#L45)


### <a name="property-$autoupgrade"></a>$autoupgrade

    public mixed $autoupgrade





* Visibility: **public**
* This property is defined in [classes/Upgrader.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#L46)


### <a name="property-$autoupgrade_module"></a>$autoupgrade_module

    public mixed $autoupgrade_module





* Visibility: **public**
* This property is defined in [classes/Upgrader.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#L47)


### <a name="property-$autoupgrade_last_version"></a>$autoupgrade_last_version

    public mixed $autoupgrade_last_version





* Visibility: **public**
* This property is defined in [classes/Upgrader.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#L48)


### <a name="property-$autoupgrade_module_link"></a>$autoupgrade_module_link

    public mixed $autoupgrade_module_link





* Visibility: **public**
* This property is defined in [classes/Upgrader.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#L49)


### <a name="property-$changelog"></a>$changelog

    public mixed $changelog





* Visibility: **public**
* This property is defined in [classes/Upgrader.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#L50)


### <a name="property-$md5"></a>$md5

    public mixed $md5





* Visibility: **public**
* This property is defined in [classes/Upgrader.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#L51)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed UpgraderCore::__construct($autoload)





* Visibility: **public**
* This method is defined in [classes/Upgrader.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#L53)


#### Arguments
* $autoload **mixed**



### <a name="method-__get"></a>__get

    mixed UpgraderCore::__get($var)





* Visibility: **public**
* This method is defined in [classes/Upgrader.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#L64)


#### Arguments
* $var **mixed**



### <a name="method-downloadLast"></a>downloadLast

    boolean UpgraderCore::downloadLast(string $dest, string $filename)

downloadLast download the last version of PrestaShop and save it in $dest/$filename



* Visibility: **public**
* This method is defined in [classes/Upgrader.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#L80)


#### Arguments
* $dest **string** - &lt;p&gt;directory where to save the file&lt;/p&gt;
* $filename **string** - &lt;p&gt;new filename&lt;/p&gt;



### <a name="method-isLastVersion"></a>isLastVersion

    mixed UpgraderCore::isLastVersion()





* Visibility: **public**
* This method is defined in [classes/Upgrader.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#L93)




### <a name="method-checkPSVersion"></a>checkPSVersion

    mixed UpgraderCore::checkPSVersion($force)

checkPSVersion ask to prestashop.com if there is a new version. return an array if yes, false otherwise



* Visibility: **public**
* This method is defined in [classes/Upgrader.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#L107)


#### Arguments
* $force **mixed**



### <a name="method-loadFromConfig"></a>loadFromConfig

    \Upgrader UpgraderCore::loadFromConfig()

load the last version informations stocked in base



* Visibility: **public**
* This method is defined in [classes/Upgrader.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#L165)




### <a name="method-getChangedFilesList"></a>getChangedFilesList

    array UpgraderCore::getChangedFilesList()

return an array of files
that the md5file does not match to the original md5file (provided by $rss_md5file_link_dir )



* Visibility: **public**
* This method is defined in [classes/Upgrader.php line 208](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#L208)




### <a name="method-addChangedFile"></a>addChangedFile

    mixed UpgraderCore::addChangedFile(string $path)

populate $this->changed_files with $path
in sub arrays  mail, translation and core items



* Visibility: **protected**
* This method is defined in [classes/Upgrader.php line 226](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#L226)


#### Arguments
* $path **string** - &lt;p&gt;filepath to add, relative to _PS_ROOT_DIR_&lt;/p&gt;



### <a name="method-addMissingFile"></a>addMissingFile

    mixed UpgraderCore::addMissingFile(string $path)

populate $this->missing_files with $path



* Visibility: **protected**
* This method is defined in [classes/Upgrader.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#L249)


#### Arguments
* $path **string** - &lt;p&gt;filepath to add, relative to _PS_ROOT_DIR_&lt;/p&gt;



### <a name="method-browseXmlAndCompare"></a>browseXmlAndCompare

    mixed UpgraderCore::browseXmlAndCompare($node, $current_path, $level)





* Visibility: **protected**
* This method is defined in [classes/Upgrader.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#L255)


#### Arguments
* $node **mixed**
* $current_path **mixed**
* $level **mixed**



### <a name="method-compareChecksum"></a>compareChecksum

    mixed UpgraderCore::compareChecksum($path, $original_sum)





* Visibility: **protected**
* This method is defined in [classes/Upgrader.php line 286](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#L286)


#### Arguments
* $path **mixed**
* $original_sum **mixed**



### <a name="method-isAuthenticPrestashopVersion"></a>isAuthenticPrestashopVersion

    mixed UpgraderCore::isAuthenticPrestashopVersion()





* Visibility: **public**
* This method is defined in [classes/Upgrader.php line 294](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#L294)



