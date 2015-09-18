ProductDownloadCore
===============






* Class name: ProductDownloadCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id_product

    public integer $id_product





* Visibility: **public**


### $display_filename

    public string $display_filename





* Visibility: **public**


### $filename

    public string $filename





* Visibility: **public**


### $date_add

    public string $date_add





* Visibility: **public**


### $date_expiration

    public string $date_expiration





* Visibility: **public**


### $nb_days_accessible

    public string $nb_days_accessible





* Visibility: **public**


### $nb_downloadable

    public string $nb_downloadable





* Visibility: **public**


### $active

    public boolean $active = 1





* Visibility: **public**


### $is_shareable

    public boolean $is_shareable





* Visibility: **public**


### $_productIds

    protected mixed $_productIds = array()





* Visibility: **protected**
* This property is **static**.


### $definition

    public mixed $definition = array('table' => 'product_download', 'primary' => 'id_product_download', 'fields' => array('id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'display_filename' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 255), 'filename' => array('type' => self::TYPE_STRING, 'validate' => 'isSha1', 'size' => 255), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_expiration' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'nb_days_accessible' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'size' => 10), 'nb_downloadable' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'size' => 10), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'is_shareable' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))





* Visibility: **public**
* This property is **static**.


Methods
-------


### __construct

    mixed ProductDownloadCore::__construct(integer $id_product_download)

Build a virtual product



* Visibility: **public**


#### Arguments
* $id_product_download **integer** - &lt;p&gt;Existing productDownload id in order to load object (optional)&lt;/p&gt;



### getFields

    array ProductDownloadCore::getFields()





* Visibility: **public**




### add

    mixed ProductDownloadCore::add($autodate, $null_values)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### update

    mixed ProductDownloadCore::update($null_values)





* Visibility: **public**


#### Arguments
* $null_values **mixed**



### delete

    mixed ProductDownloadCore::delete($delete_file)





* Visibility: **public**


#### Arguments
* $delete_file **mixed**



### deleteFile

    boolean ProductDownloadCore::deleteFile(integer $id_product_download)

Delete the file



* Visibility: **public**


#### Arguments
* $id_product_download **integer** - &lt;p&gt;: if we need to delete a specific product attribute file&lt;/p&gt;



### checkFile

    boolean ProductDownloadCore::checkFile()

Check if file exists



* Visibility: **public**




### checkWritableDir

    boolean ProductDownloadCore::checkWritableDir()

Check if download repository is writable



* Visibility: **public**
* This method is **static**.




### getIdFromIdProduct

    integer ProductDownloadCore::getIdFromIdProduct(integer $id_product)

Return the id_product_download from an id_product



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **integer** - &lt;p&gt;Product the id&lt;/p&gt;



### getIdFromFilename

    integer ProductDownloadCore::getIdFromFilename(string $filename)

Return the display filename from a physical filename



* Visibility: **public**
* This method is **static**.


#### Arguments
* $filename **string** - &lt;p&gt;Filename physically&lt;/p&gt;



### getFilenameFromIdProduct

    string ProductDownloadCore::getFilenameFromIdProduct(integer $id_product)

Return the filename from an id_product



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **integer** - &lt;p&gt;Product the id&lt;/p&gt;



### getFilenameFromFilename

    string ProductDownloadCore::getFilenameFromFilename(string $filename)

Return the display filename from a physical filename



* Visibility: **public**
* This method is **static**.


#### Arguments
* $filename **string** - &lt;p&gt;Filename physically&lt;/p&gt;



### getTextLink

    string ProductDownloadCore::getTextLink(boolean $admin, string $hash)

Return html link



* Visibility: **public**


#### Arguments
* $admin **boolean** - &lt;p&gt;specific to backend (optionnal)&lt;/p&gt;
* $hash **string** - &lt;p&gt;hash code in table order detail (optionnal)&lt;/p&gt;



### getHtmlLink

    string ProductDownloadCore::getHtmlLink(string $class, boolean $admin, boolean $hash)

Return html link



* Visibility: **public**


#### Arguments
* $class **string** - &lt;p&gt;CSS selector&lt;/p&gt;
* $admin **boolean** - &lt;p&gt;specific to backend&lt;/p&gt;
* $hash **boolean** - &lt;p&gt;hash code in table order detail&lt;/p&gt;



### getDeadline

    string ProductDownloadCore::getDeadline()

Return a deadline



* Visibility: **public**




### getHash

    string ProductDownloadCore::getHash()

Return a hash for control download access



* Visibility: **public**




### getNewFilename

    string ProductDownloadCore::getNewFilename()

Return a sha1 filename



* Visibility: **public**
* This method is **static**.




### isFeatureActive

    boolean ProductDownloadCore::isFeatureActive()

This method is allow to know if a feature is used or active



* Visibility: **public**
* This method is **static**.



