Class ProductDownloadCore
=====================





* Class name: ProductDownloadCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/ProductDownload.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ProductDownload.php#L27)


Contents
--------


### Properties

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

### Methods

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

```php
protected mixed $_productIds = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/ProductDownload.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ProductDownload.php#L56).


### <a name="property-$active"></a>$active

```php
public boolean $active = 1
```





* Visibility: **public**
* Source: [classes/ProductDownload.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ProductDownload.php#L51).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/ProductDownload.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ProductDownload.php#L39).


### <a name="property-$date_expiration"></a>$date_expiration

```php
public string $date_expiration
```





* Visibility: **public**
* Source: [classes/ProductDownload.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ProductDownload.php#L42).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'product_download', 'primary' => 'id_product_download', 'fields' => array('id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'display_filename' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 255), 'filename' => array('type' => self::TYPE_STRING, 'validate' => 'isSha1', 'size' => 255), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_expiration' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'nb_days_accessible' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'size' => 10), 'nb_downloadable' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'size' => 10), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'is_shareable' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/ProductDownload.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ProductDownload.php#L61).


### <a name="property-$display_filename"></a>$display_filename

```php
public string $display_filename
```





* Visibility: **public**
* Source: [classes/ProductDownload.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ProductDownload.php#L33).


### <a name="property-$filename"></a>$filename

```php
public string $filename
```





* Visibility: **public**
* Source: [classes/ProductDownload.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ProductDownload.php#L36).


### <a name="property-$id_product"></a>$id_product

```php
public integer $id_product
```





* Visibility: **public**
* Source: [classes/ProductDownload.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ProductDownload.php#L30).


### <a name="property-$is_shareable"></a>$is_shareable

```php
public boolean $is_shareable
```





* Visibility: **public**
* Source: [classes/ProductDownload.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ProductDownload.php#L54).


### <a name="property-$nb_days_accessible"></a>$nb_days_accessible

```php
public string $nb_days_accessible
```





* Visibility: **public**
* Source: [classes/ProductDownload.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ProductDownload.php#L45).


### <a name="property-$nb_downloadable"></a>$nb_downloadable

```php
public string $nb_downloadable
```





* Visibility: **public**
* Source: [classes/ProductDownload.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ProductDownload.php#L48).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ProductDownloadCore::__construct(integer $id_product_download)
```

Build a virtual product



* Visibility: **public**
* Source: [classes/ProductDownload.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ProductDownload.php#L82)


#### Arguments
* $id_product_download **integer** - Existing productDownload id in order to load object (optional)



### <a name="method-add"></a>add

```php
mixed ProductDownloadCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/ProductDownload.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ProductDownload.php#L101)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-checkFile"></a>checkFile

```php
boolean ProductDownloadCore::checkFile()
```

Check if file exists



* Visibility: **public**
* Source: [classes/ProductDownload.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ProductDownload.php#L152)




### <a name="method-checkWritableDir"></a>checkWritableDir

```php
boolean ProductDownloadCore::checkWritableDir()
```

Check if download repository is writable



* Visibility: **public**
* This method is **static**.
* Source: [classes/ProductDownload.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ProductDownload.php#L163)




### <a name="method-delete"></a>delete

```php
mixed ProductDownloadCore::delete($delete_file)
```





* Visibility: **public**
* Source: [classes/ProductDownload.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ProductDownload.php#L124)


#### Arguments
* $delete_file **mixed**



### <a name="method-deleteFile"></a>deleteFile

```php
boolean ProductDownloadCore::deleteFile(integer $id_product_download)
```

Delete the file



* Visibility: **public**
* Source: [classes/ProductDownload.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ProductDownload.php#L138)


#### Arguments
* $id_product_download **integer** - : if we need to delete a specific product attribute file



### <a name="method-getDeadline"></a>getDeadline

```php
string ProductDownloadCore::getDeadline()
```

Return a deadline



* Visibility: **public**
* Source: [classes/ProductDownload.php line 276](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ProductDownload.php#L276)




### <a name="method-getFields"></a>getFields

```php
array ProductDownloadCore::getFields()
```





* Visibility: **public**
* Source: [classes/ProductDownload.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ProductDownload.php#L92)




### <a name="method-getFilenameFromFilename"></a>getFilenameFromFilename

```php
string ProductDownloadCore::getFilenameFromFilename(string $filename)
```

Return the display filename from a physical filename



* Visibility: **public**
* This method is **static**.
* Source: [classes/ProductDownload.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ProductDownload.php#L229)


#### Arguments
* $filename **string** - Filename physically



### <a name="method-getFilenameFromIdProduct"></a>getFilenameFromIdProduct

```php
string ProductDownloadCore::getFilenameFromIdProduct(integer $id_product)
```

Return the filename from an id_product



* Visibility: **public**
* This method is **static**.
* Source: [classes/ProductDownload.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ProductDownload.php#L213)


#### Arguments
* $id_product **integer** - Product the id



### <a name="method-getHash"></a>getHash

```php
string ProductDownloadCore::getHash()
```

Return a hash for control download access



* Visibility: **public**
* Source: [classes/ProductDownload.php line 289](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ProductDownload.php#L289)




### <a name="method-getHtmlLink"></a>getHtmlLink

```php
string ProductDownloadCore::getHtmlLink(string $class, boolean $admin, boolean $hash)
```

Return html link



* Visibility: **public**
* Source: [classes/ProductDownload.php line 261](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ProductDownload.php#L261)


#### Arguments
* $class **string** - CSS selector
* $admin **boolean** - specific to backend
* $hash **boolean** - hash code in table order detail



### <a name="method-getIdFromFilename"></a>getIdFromFilename

```php
integer ProductDownloadCore::getIdFromFilename(string $filename)
```

Return the display filename from a physical filename



* Visibility: **public**
* This method is **static**.
* Source: [classes/ProductDownload.php line 199](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ProductDownload.php#L199)


#### Arguments
* $filename **string** - Filename physically



### <a name="method-getIdFromIdProduct"></a>getIdFromIdProduct

```php
integer ProductDownloadCore::getIdFromIdProduct(integer $id_product)
```

Return the id_product_download from an id_product



* Visibility: **public**
* This method is **static**.
* Source: [classes/ProductDownload.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ProductDownload.php#L174)


#### Arguments
* $id_product **integer** - Product the id



### <a name="method-getNewFilename"></a>getNewFilename

```php
string ProductDownloadCore::getNewFilename()
```

Return a sha1 filename



* Visibility: **public**
* This method is **static**.
* Source: [classes/ProductDownload.php line 300](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ProductDownload.php#L300)




### <a name="method-getTextLink"></a>getTextLink

```php
string ProductDownloadCore::getTextLink(boolean $admin, string $hash)
```

Return html link



* Visibility: **public**
* Source: [classes/ProductDownload.php line 245](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ProductDownload.php#L245)


#### Arguments
* $admin **boolean** - specific to backend (optionnal)
* $hash **string** - hash code in table order detail (optionnal)



### <a name="method-isFeatureActive"></a>isFeatureActive

```php
boolean ProductDownloadCore::isFeatureActive()
```

This method is allow to know if a feature is used or active



* Visibility: **public**
* This method is **static**.
* Source: [classes/ProductDownload.php line 313](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ProductDownload.php#L313)




### <a name="method-update"></a>update

```php
mixed ProductDownloadCore::update($null_values)
```





* Visibility: **public**
* Source: [classes/ProductDownload.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ProductDownload.php#L113)


#### Arguments
* $null_values **mixed**


