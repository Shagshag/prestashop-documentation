ProductDownloadCore
===============






* Class name: ProductDownloadCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/ProductDownload.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#L27)





Properties
----------


### $id_product

    public integer $id_product





* Visibility: **public**
* This property is defined in [classes/ProductDownload.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#30)


### $display_filename

    public string $display_filename





* Visibility: **public**
* This property is defined in [classes/ProductDownload.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#33)


### $filename

    public string $filename





* Visibility: **public**
* This property is defined in [classes/ProductDownload.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#36)


### $date_add

    public string $date_add





* Visibility: **public**
* This property is defined in [classes/ProductDownload.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#39)


### $date_expiration

    public string $date_expiration





* Visibility: **public**
* This property is defined in [classes/ProductDownload.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#42)


### $nb_days_accessible

    public string $nb_days_accessible





* Visibility: **public**
* This property is defined in [classes/ProductDownload.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#45)


### $nb_downloadable

    public string $nb_downloadable





* Visibility: **public**
* This property is defined in [classes/ProductDownload.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#48)


### $active

    public boolean $active = 1





* Visibility: **public**
* This property is defined in [classes/ProductDownload.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#51)


### $is_shareable

    public boolean $is_shareable





* Visibility: **public**
* This property is defined in [classes/ProductDownload.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#54)


### $_productIds

    protected mixed $_productIds = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/ProductDownload.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#56)


### $definition

    public mixed $definition = array('table' => 'product_download', 'primary' => 'id_product_download', 'fields' => array('id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'display_filename' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 255), 'filename' => array('type' => self::TYPE_STRING, 'validate' => 'isSha1', 'size' => 255), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_expiration' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'nb_days_accessible' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'size' => 10), 'nb_downloadable' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'size' => 10), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'is_shareable' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/ProductDownload.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#61)


Methods
-------


### __construct

    mixed ProductDownloadCore::__construct(integer $id_product_download)

Build a virtual product



* Visibility: **public**
* This method is defined in [classes/ProductDownload.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#82)


#### Arguments
* $id_product_download **integer** - &lt;p&gt;Existing productDownload id in order to load object (optional)&lt;/p&gt;



### getFields

    array ProductDownloadCore::getFields()





* Visibility: **public**
* This method is defined in [classes/ProductDownload.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#92)




### add

    mixed ProductDownloadCore::add($autodate, $null_values)





* Visibility: **public**
* This method is defined in [classes/ProductDownload.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#102)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### update

    mixed ProductDownloadCore::update($null_values)





* Visibility: **public**
* This method is defined in [classes/ProductDownload.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#107)


#### Arguments
* $null_values **mixed**



### delete

    mixed ProductDownloadCore::delete($delete_file)





* Visibility: **public**
* This method is defined in [classes/ProductDownload.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#117)


#### Arguments
* $delete_file **mixed**



### deleteFile

    boolean ProductDownloadCore::deleteFile(integer $id_product_download)

Delete the file



* Visibility: **public**
* This method is defined in [classes/ProductDownload.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#132)


#### Arguments
* $id_product_download **integer** - &lt;p&gt;: if we need to delete a specific product attribute file&lt;/p&gt;



### checkFile

    boolean ProductDownloadCore::checkFile()

Check if file exists



* Visibility: **public**
* This method is defined in [classes/ProductDownload.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#147)




### checkWritableDir

    boolean ProductDownloadCore::checkWritableDir()

Check if download repository is writable



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ProductDownload.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#160)




### getIdFromIdProduct

    integer ProductDownloadCore::getIdFromIdProduct(integer $id_product)

Return the id_product_download from an id_product



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ProductDownload.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#171)


#### Arguments
* $id_product **integer** - &lt;p&gt;Product the id&lt;/p&gt;



### getIdFromFilename

    integer ProductDownloadCore::getIdFromFilename(string $filename)

Return the display filename from a physical filename



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ProductDownload.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#198)


#### Arguments
* $filename **string** - &lt;p&gt;Filename physically&lt;/p&gt;



### getFilenameFromIdProduct

    string ProductDownloadCore::getFilenameFromIdProduct(integer $id_product)

Return the filename from an id_product



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ProductDownload.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#212)


#### Arguments
* $id_product **integer** - &lt;p&gt;Product the id&lt;/p&gt;



### getFilenameFromFilename

    string ProductDownloadCore::getFilenameFromFilename(string $filename)

Return the display filename from a physical filename



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ProductDownload.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#228)


#### Arguments
* $filename **string** - &lt;p&gt;Filename physically&lt;/p&gt;



### getTextLink

    string ProductDownloadCore::getTextLink(boolean $admin, string $hash)

Return html link



* Visibility: **public**
* This method is defined in [classes/ProductDownload.php line 244](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#244)


#### Arguments
* $admin **boolean** - &lt;p&gt;specific to backend (optionnal)&lt;/p&gt;
* $hash **string** - &lt;p&gt;hash code in table order detail (optionnal)&lt;/p&gt;



### getHtmlLink

    string ProductDownloadCore::getHtmlLink(string $class, boolean $admin, boolean $hash)

Return html link



* Visibility: **public**
* This method is defined in [classes/ProductDownload.php line 260](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#260)


#### Arguments
* $class **string** - &lt;p&gt;CSS selector&lt;/p&gt;
* $admin **boolean** - &lt;p&gt;specific to backend&lt;/p&gt;
* $hash **boolean** - &lt;p&gt;hash code in table order detail&lt;/p&gt;



### getDeadline

    string ProductDownloadCore::getDeadline()

Return a deadline



* Visibility: **public**
* This method is defined in [classes/ProductDownload.php line 276](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#276)




### getHash

    string ProductDownloadCore::getHash()

Return a hash for control download access



* Visibility: **public**
* This method is defined in [classes/ProductDownload.php line 290](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#290)




### getNewFilename

    string ProductDownloadCore::getNewFilename()

Return a sha1 filename



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ProductDownload.php line 301](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#301)




### isFeatureActive

    boolean ProductDownloadCore::isFeatureActive()

This method is allow to know if a feature is used or active



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ProductDownload.php line 314](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#314)



