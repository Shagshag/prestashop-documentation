UpgraderCore
===============






* Class name: UpgraderCore
* Namespace: 



Constants
----------


### DEFAULT_CHECK_VERSION_DELAY_HOURS

    const DEFAULT_CHECK_VERSION_DELAY_HOURS = 24





Properties
----------


### $rss_version_link

    public mixed $rss_version_link





* Visibility: **public**


### $rss_md5file_link_dir

    public mixed $rss_md5file_link_dir





* Visibility: **public**


### $need_upgrade

    protected boolean $need_upgrade = false





* Visibility: **protected**


### $changed_files

    protected mixed $changed_files = array()





* Visibility: **protected**


### $missing_files

    protected mixed $missing_files = array()





* Visibility: **protected**


### $version_name

    public mixed $version_name





* Visibility: **public**


### $version_num

    public mixed $version_num





* Visibility: **public**


### $version_is_modified

    public mixed $version_is_modified = null





* Visibility: **public**


### $link

    public string $link





* Visibility: **public**


### $autoupgrade

    public mixed $autoupgrade





* Visibility: **public**


### $autoupgrade_module

    public mixed $autoupgrade_module





* Visibility: **public**


### $autoupgrade_last_version

    public mixed $autoupgrade_last_version





* Visibility: **public**


### $autoupgrade_module_link

    public mixed $autoupgrade_module_link





* Visibility: **public**


### $changelog

    public mixed $changelog





* Visibility: **public**


### $md5

    public mixed $md5





* Visibility: **public**


Methods
-------


### __construct

    mixed UpgraderCore::__construct($autoload)





* Visibility: **public**


#### Arguments
* $autoload **mixed**



### __get

    mixed UpgraderCore::__get($var)





* Visibility: **public**


#### Arguments
* $var **mixed**



### downloadLast

    boolean UpgraderCore::downloadLast(string $dest, string $filename)

downloadLast download the last version of PrestaShop and save it in $dest/$filename



* Visibility: **public**


#### Arguments
* $dest **string** - &lt;p&gt;directory where to save the file&lt;/p&gt;
* $filename **string** - &lt;p&gt;new filename&lt;/p&gt;



### isLastVersion

    mixed UpgraderCore::isLastVersion()





* Visibility: **public**




### checkPSVersion

    mixed UpgraderCore::checkPSVersion($force)

checkPSVersion ask to prestashop.com if there is a new version. return an array if yes, false otherwise



* Visibility: **public**


#### Arguments
* $force **mixed**



### loadFromConfig

    \Upgrader UpgraderCore::loadFromConfig()

load the last version informations stocked in base



* Visibility: **public**




### getChangedFilesList

    array UpgraderCore::getChangedFilesList()

return an array of files
that the md5file does not match to the original md5file (provided by $rss_md5file_link_dir )



* Visibility: **public**




### addChangedFile

    mixed UpgraderCore::addChangedFile(string $path)

populate $this->changed_files with $path
in sub arrays  mail, translation and core items



* Visibility: **protected**


#### Arguments
* $path **string** - &lt;p&gt;filepath to add, relative to _PS_ROOT_DIR_&lt;/p&gt;



### addMissingFile

    mixed UpgraderCore::addMissingFile(string $path)

populate $this->missing_files with $path



* Visibility: **protected**


#### Arguments
* $path **string** - &lt;p&gt;filepath to add, relative to _PS_ROOT_DIR_&lt;/p&gt;



### browseXmlAndCompare

    mixed UpgraderCore::browseXmlAndCompare($node, $current_path, $level)





* Visibility: **protected**


#### Arguments
* $node **mixed**
* $current_path **mixed**
* $level **mixed**



### compareChecksum

    mixed UpgraderCore::compareChecksum($path, $original_sum)





* Visibility: **protected**


#### Arguments
* $path **mixed**
* $original_sum **mixed**



### isAuthenticPrestashopVersion

    mixed UpgraderCore::isAuthenticPrestashopVersion()





* Visibility: **public**



