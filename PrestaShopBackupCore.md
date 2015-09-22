PrestaShopBackupCore
===============






* Class name: PrestaShopBackupCore
* This class is defined in [classes/PrestaShopBackup.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L27)





Properties
----------

* [$id](#property-$id)
* [$error](#property-$error)
* [$backupDir](#property-$backupDir)
* [$customBackupDir](#property-$customBackupDir)
* [$psBackupAll](#property-$psBackupAll)
* [$psBackupDropTable](#property-$psBackupDropTable)

Methods
-------
* [__construct](#method-__construct)
* [setCustomBackupPath](#method-setCustomBackupPath)
* [getRealBackupPath](#method-getRealBackupPath)
* [getBackupPath](#method-getBackupPath)
* [backupExist](#method-backupExist)
* [getBackupURL](#method-getBackupURL)
* [delete](#method-delete)
* [deleteSelection](#method-deleteSelection)
* [add](#method-add)




Properties
----------


### <a name="property-$id"></a>$id

    public integer $id





* Visibility: **public**
* This property is defined in [classes/PrestaShopBackup.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L30)


### <a name="property-$error"></a>$error

    public string $error





* Visibility: **public**
* This property is defined in [classes/PrestaShopBackup.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L32)


### <a name="property-$backupDir"></a>$backupDir

    public string $backupDir = '/backups/'





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/PrestaShopBackup.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L34)


### <a name="property-$customBackupDir"></a>$customBackupDir

    public string $customBackupDir = null





* Visibility: **public**
* This property is defined in [classes/PrestaShopBackup.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L36)


### <a name="property-$psBackupAll"></a>$psBackupAll

    public mixed $psBackupAll = true





* Visibility: **public**
* This property is defined in [classes/PrestaShopBackup.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L38)


### <a name="property-$psBackupDropTable"></a>$psBackupDropTable

    public mixed $psBackupDropTable = true





* Visibility: **public**
* This property is defined in [classes/PrestaShopBackup.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L39)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed PrestaShopBackupCore::__construct(string $filename)

Creates a new backup object



* Visibility: **public**
* This method is defined in [classes/PrestaShopBackup.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L46)


#### Arguments
* $filename **string** - &lt;p&gt;Filename of the backup file&lt;/p&gt;



### <a name="method-setCustomBackupPath"></a>setCustomBackupPath

    boolean PrestaShopBackupCore::setCustomBackupPath(string $dir)

you can set a different path with that function



* Visibility: **public**
* This method is defined in [classes/PrestaShopBackup.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L65)


#### Arguments
* $dir **string**



### <a name="method-getRealBackupPath"></a>getRealBackupPath

    string PrestaShopBackupCore::getRealBackupPath(string $filename)

get the path to use for backup (customBackupDir if specified, or default)



* Visibility: **public**
* This method is defined in [classes/PrestaShopBackup.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L83)


#### Arguments
* $filename **string** - &lt;p&gt;filename to use&lt;/p&gt;



### <a name="method-getBackupPath"></a>getBackupPath

    string PrestaShopBackupCore::getBackupPath(string $filename)

Get the full path of the backup file



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/PrestaShopBackup.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L103)


#### Arguments
* $filename **string** - &lt;p&gt;prefix of the backup file (datetime will be the second part)&lt;/p&gt;



### <a name="method-backupExist"></a>backupExist

    boolean PrestaShopBackupCore::backupExist(string $filename)

Check if a backup file exist



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/PrestaShopBackup.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L131)


#### Arguments
* $filename **string** - &lt;p&gt;prefix of the backup file (datetime will be the second part)&lt;/p&gt;



### <a name="method-getBackupURL"></a>getBackupURL

    string PrestaShopBackupCore::getBackupURL()

Get the URL used to retrieve this backup file



* Visibility: **public**
* This method is defined in [classes/PrestaShopBackup.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L146)




### <a name="method-delete"></a>delete

    boolean PrestaShopBackupCore::delete()

Delete the current backup file



* Visibility: **public**
* This method is defined in [classes/PrestaShopBackup.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L156)




### <a name="method-deleteSelection"></a>deleteSelection

    boolean PrestaShopBackupCore::deleteSelection($list)

Deletes a range of backup files



* Visibility: **public**
* This method is defined in [classes/PrestaShopBackup.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L171)


#### Arguments
* $list **mixed**



### <a name="method-add"></a>add

    boolean PrestaShopBackupCore::add()

Creates a new backup file



* Visibility: **public**
* This method is defined in [classes/PrestaShopBackup.php line 188](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L188)



