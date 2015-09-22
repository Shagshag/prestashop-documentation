Class ProductDownloadCore
=====================





* Class name: ProductDownloadCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/ProductDownload.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#L27)



Properties
----------

* [$_productIds](#property-$_productIds)
* [$active](#property-$active)
* [$date_add](#property-$date_add)
* [$date_expiration](#property-$date_expiration)
* [$definition](#property-$definition)
* [$display_filename](#property-$display_filename)
* [$filename](#property-$filename)
* [$id_product](#property-$id_product)
* [$is_shareable](#property-$is_shareable)
* [$nb_days_accessible](#property-$nb_days_accessible)
* [$nb_downloadable](#property-$nb_downloadable)

Methods
-------
* [__construct](#method-__construct)
* [add](#method-add)
* [checkFile](#method-checkFile)
* [checkWritableDir](#method-checkWritableDir)
* [delete](#method-delete)
* [deleteFile](#method-deleteFile)
* [getDeadline](#method-getDeadline)
* [getFields](#method-getFields)
* [getFilenameFromFilename](#method-getFilenameFromFilename)
* [getFilenameFromIdProduct](#method-getFilenameFromIdProduct)
* [getHash](#method-getHash)
* [getHtmlLink](#method-getHtmlLink)
* [getIdFromFilename](#method-getIdFromFilename)
* [getIdFromIdProduct](#method-getIdFromIdProduct)
* [getNewFilename](#method-getNewFilename)
* [getTextLink](#method-getTextLink)
* [isFeatureActive](#method-isFeatureActive)
* [update](#method-update)




Properties
----------


### <a name="property-$_productIds"></a>$_productIds

    protected mixed $_productIds = array()





* Visibility: **protected**
* This property is **static**.
* Source: [classes/ProductDownload.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#L56).


### <a name="property-$active"></a>$active

    public boolean $active = 1





* Visibility: **public**
* Source: [classes/ProductDownload.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#L51).


### <a name="property-$date_add"></a>$date_add

    public string $date_add





* Visibility: **public**
* Source: [classes/ProductDownload.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#L39).


### <a name="property-$date_expiration"></a>$date_expiration

    public string $date_expiration





* Visibility: **public**
* Source: [classes/ProductDownload.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#L42).


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'product_download', 'primary' => 'id_product_download', 'fields' => array('id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'display_filename' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 255), 'filename' => array('type' => self::TYPE_STRING, 'validate' => 'isSha1', 'size' => 255), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_expiration' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'nb_days_accessible' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'size' => 10), 'nb_downloadable' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'size' => 10), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'is_shareable' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))





* Visibility: **public**
* This property is **static**.
* Source: [classes/ProductDownload.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#L61).


### <a name="property-$display_filename"></a>$display_filename

    public string $display_filename





* Visibility: **public**
* Source: [classes/ProductDownload.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#L33).


### <a name="property-$filename"></a>$filename

    public string $filename





* Visibility: **public**
* Source: [classes/ProductDownload.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#L36).


### <a name="property-$id_product"></a>$id_product

    public integer $id_product





* Visibility: **public**
* Source: [classes/ProductDownload.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#L30).


### <a name="property-$is_shareable"></a>$is_shareable

    public boolean $is_shareable





* Visibility: **public**
* Source: [classes/ProductDownload.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#L54).


### <a name="property-$nb_days_accessible"></a>$nb_days_accessible

    public string $nb_days_accessible





* Visibility: **public**
* Source: [classes/ProductDownload.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#L45).


### <a name="property-$nb_downloadable"></a>$nb_downloadable

    public string $nb_downloadable





* Visibility: **public**
* Source: [classes/ProductDownload.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#L48).


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed ProductDownloadCore::__construct(integer $id_product_download)

Build a virtual product



* Visibility: **public**
* Source: [classes/ProductDownload.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#L82)


#### Arguments
* $id_product_download **integer** - Existing productDownload id in order to load object (optional)



### <a name="method-add"></a>add

    mixed ProductDownloadCore::add($autodate, $null_values)





* Visibility: **public**
* Source: [classes/ProductDownload.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#L102)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-checkFile"></a>checkFile

    boolean ProductDownloadCore::checkFile()

Check if file exists



* Visibility: **public**
* Source: [classes/ProductDownload.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#L147)




### <a name="method-checkWritableDir"></a>checkWritableDir

    boolean ProductDownloadCore::checkWritableDir()

Check if download repository is writable



* Visibility: **public**
* This method is **static**.
* Source: [classes/ProductDownload.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#L160)




### <a name="method-delete"></a>delete

    mixed ProductDownloadCore::delete($delete_file)





* Visibility: **public**
* Source: [classes/ProductDownload.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#L117)


#### Arguments
* $delete_file **mixed**



### <a name="method-deleteFile"></a>deleteFile

    boolean ProductDownloadCore::deleteFile(integer $id_product_download)

Delete the file



* Visibility: **public**
* Source: [classes/ProductDownload.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#L132)


#### Arguments
* $id_product_download **integer** - : if we need to delete a specific product attribute file



### <a name="method-getDeadline"></a>getDeadline

    string ProductDownloadCore::getDeadline()

Return a deadline



* Visibility: **public**
* Source: [classes/ProductDownload.php line 276](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#L276)




### <a name="method-getFields"></a>getFields

    array ProductDownloadCore::getFields()





* Visibility: **public**
* Source: [classes/ProductDownload.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#L92)




### <a name="method-getFilenameFromFilename"></a>getFilenameFromFilename

    string ProductDownloadCore::getFilenameFromFilename(string $filename)

Return the display filename from a physical filename



* Visibility: **public**
* This method is **static**.
* Source: [classes/ProductDownload.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#L228)


#### Arguments
* $filename **string** - Filename physically



### <a name="method-getFilenameFromIdProduct"></a>getFilenameFromIdProduct

    string ProductDownloadCore::getFilenameFromIdProduct(integer $id_product)

Return the filename from an id_product



* Visibility: **public**
* This method is **static**.
* Source: [classes/ProductDownload.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#L212)


#### Arguments
* $id_product **integer** - Product the id



### <a name="method-getHash"></a>getHash

    string ProductDownloadCore::getHash()

Return a hash for control download access



* Visibility: **public**
* Source: [classes/ProductDownload.php line 290](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#L290)




### <a name="method-getHtmlLink"></a>getHtmlLink

    string ProductDownloadCore::getHtmlLink(string $class, boolean $admin, boolean $hash)

Return html link



* Visibility: **public**
* Source: [classes/ProductDownload.php line 260](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#L260)


#### Arguments
* $class **string** - CSS selector
* $admin **boolean** - specific to backend
* $hash **boolean** - hash code in table order detail



### <a name="method-getIdFromFilename"></a>getIdFromFilename

    integer ProductDownloadCore::getIdFromFilename(string $filename)

Return the display filename from a physical filename



* Visibility: **public**
* This method is **static**.
* Source: [classes/ProductDownload.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#L198)


#### Arguments
* $filename **string** - Filename physically



### <a name="method-getIdFromIdProduct"></a>getIdFromIdProduct

    integer ProductDownloadCore::getIdFromIdProduct(integer $id_product)

Return the id_product_download from an id_product



* Visibility: **public**
* This method is **static**.
* Source: [classes/ProductDownload.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#L171)


#### Arguments
* $id_product **integer** - Product the id



### <a name="method-getNewFilename"></a>getNewFilename

    string ProductDownloadCore::getNewFilename()

Return a sha1 filename



* Visibility: **public**
* This method is **static**.
* Source: [classes/ProductDownload.php line 301](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#L301)




### <a name="method-getTextLink"></a>getTextLink

    string ProductDownloadCore::getTextLink(boolean $admin, string $hash)

Return html link



* Visibility: **public**
* Source: [classes/ProductDownload.php line 244](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#L244)


#### Arguments
* $admin **boolean** - specific to backend (optionnal)
* $hash **string** - hash code in table order detail (optionnal)



### <a name="method-isFeatureActive"></a>isFeatureActive

    boolean ProductDownloadCore::isFeatureActive()

This method is allow to know if a feature is used or active



* Visibility: **public**
* This method is **static**.
* Source: [classes/ProductDownload.php line 314](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#L314)




### <a name="method-update"></a>update

    mixed ProductDownloadCore::update($null_values)





* Visibility: **public**
* Source: [classes/ProductDownload.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductDownload.php#L107)


#### Arguments
* $null_values **mixed**


