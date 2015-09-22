UpgraderCore
===============






* Class name: UpgraderCore
* Namespace: 

* This class is defined in [classes/Upgrader.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#27)



Constants
----------


### DEFAULT_CHECK_VERSION_DELAY_HOURS

    const DEFAULT_CHECK_VERSION_DELAY_HOURS = 24



* This constant is defined in [classes/Upgrader.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#29)


Properties
----------


### $rss_version_link

    public mixed $rss_version_link





* Visibility: **public**
* This property is defined in [classes/Upgrader.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#30)


### $rss_md5file_link_dir

    public mixed $rss_md5file_link_dir





* Visibility: **public**
* This property is defined in [classes/Upgrader.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#31)


### $need_upgrade

    protected boolean $need_upgrade = false





* Visibility: **protected**
* This property is defined in [classes/Upgrader.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#35)


### $changed_files

    protected mixed $changed_files = array()





* Visibility: **protected**
* This property is defined in [classes/Upgrader.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#36)


### $missing_files

    protected mixed $missing_files = array()





* Visibility: **protected**
* This property is defined in [classes/Upgrader.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#37)


### $version_name

    public mixed $version_name





* Visibility: **public**
* This property is defined in [classes/Upgrader.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#39)


### $version_num

    public mixed $version_num





* Visibility: **public**
* This property is defined in [classes/Upgrader.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#40)


### $version_is_modified

    public mixed $version_is_modified = null





* Visibility: **public**
* This property is defined in [classes/Upgrader.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#41)


### $link

    public string $link





* Visibility: **public**
* This property is defined in [classes/Upgrader.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#45)


### $autoupgrade

    public mixed $autoupgrade





* Visibility: **public**
* This property is defined in [classes/Upgrader.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#46)


### $autoupgrade_module

    public mixed $autoupgrade_module





* Visibility: **public**
* This property is defined in [classes/Upgrader.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#47)


### $autoupgrade_last_version

    public mixed $autoupgrade_last_version





* Visibility: **public**
* This property is defined in [classes/Upgrader.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#48)


### $autoupgrade_module_link

    public mixed $autoupgrade_module_link





* Visibility: **public**
* This property is defined in [classes/Upgrader.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#49)


### $changelog

    public mixed $changelog





* Visibility: **public**
* This property is defined in [classes/Upgrader.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#50)


### $md5

    public mixed $md5





* Visibility: **public**
* This property is defined in [classes/Upgrader.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#51)


Methods
-------


### __construct

    mixed UpgraderCore::__construct($autoload)





* Visibility: **public**
* This method is defined in [classes/Upgrader.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#53)


#### Arguments
* $autoload **mixed**



### __get

    mixed UpgraderCore::__get($var)





* Visibility: **public**
* This method is defined in [classes/Upgrader.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#64)


#### Arguments
* $var **mixed**



### downloadLast

    boolean UpgraderCore::downloadLast(string $dest, string $filename)

downloadLast download the last version of PrestaShop and save it in $dest/$filename



* Visibility: **public**
* This method is defined in [classes/Upgrader.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#80)


#### Arguments
* $dest **string** - &lt;p&gt;directory where to save the file&lt;/p&gt;
* $filename **string** - &lt;p&gt;new filename&lt;/p&gt;



### isLastVersion

    mixed UpgraderCore::isLastVersion()





* Visibility: **public**
* This method is defined in [classes/Upgrader.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#93)




### checkPSVersion

    mixed UpgraderCore::checkPSVersion($force)

checkPSVersion ask to prestashop.com if there is a new version. return an array if yes, false otherwise



* Visibility: **public**
* This method is defined in [classes/Upgrader.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#107)


#### Arguments
* $force **mixed**



### loadFromConfig

    \Upgrader UpgraderCore::loadFromConfig()

load the last version informations stocked in base



* Visibility: **public**
* This method is defined in [classes/Upgrader.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#165)




### getChangedFilesList

    array UpgraderCore::getChangedFilesList()

return an array of files
that the md5file does not match to the original md5file (provided by $rss_md5file_link_dir )



* Visibility: **public**
* This method is defined in [classes/Upgrader.php line 208](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#208)




### addChangedFile

    mixed UpgraderCore::addChangedFile(string $path)

populate $this->changed_files with $path
in sub arrays  mail, translation and core items



* Visibility: **protected**
* This method is defined in [classes/Upgrader.php line 226](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#226)


#### Arguments
* $path **string** - &lt;p&gt;filepath to add, relative to _PS_ROOT_DIR_&lt;/p&gt;



### addMissingFile

    mixed UpgraderCore::addMissingFile(string $path)

populate $this->missing_files with $path



* Visibility: **protected**
* This method is defined in [classes/Upgrader.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#249)


#### Arguments
* $path **string** - &lt;p&gt;filepath to add, relative to _PS_ROOT_DIR_&lt;/p&gt;



### browseXmlAndCompare

    mixed UpgraderCore::browseXmlAndCompare($node, $current_path, $level)





* Visibility: **protected**
* This method is defined in [classes/Upgrader.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#255)


#### Arguments
* $node **mixed**
* $current_path **mixed**
* $level **mixed**



### compareChecksum

    mixed UpgraderCore::compareChecksum($path, $original_sum)





* Visibility: **protected**
* This method is defined in [classes/Upgrader.php line 286](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#286)


#### Arguments
* $path **mixed**
* $original_sum **mixed**



### isAuthenticPrestashopVersion

    mixed UpgraderCore::isAuthenticPrestashopVersion()





* Visibility: **public**
* This method is defined in [classes/Upgrader.php line 294](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Upgrader.php#294)



