PrestaShopBackupCore
===============






* Class name: PrestaShopBackupCore
* Namespace: 





Properties
----------


### $id

    public integer $id





* Visibility: **public**


### $error

    public string $error





* Visibility: **public**


### $backupDir

    public string $backupDir = '/backups/'





* Visibility: **public**
* This property is **static**.


### $customBackupDir

    public string $customBackupDir = null





* Visibility: **public**


### $psBackupAll

    public mixed $psBackupAll = true





* Visibility: **public**


### $psBackupDropTable

    public mixed $psBackupDropTable = true





* Visibility: **public**


Methods
-------


### __construct

    mixed PrestaShopBackupCore::__construct(string $filename)

Creates a new backup object



* Visibility: **public**


#### Arguments
* $filename **string** - &lt;p&gt;Filename of the backup file&lt;/p&gt;



### setCustomBackupPath

    boolean PrestaShopBackupCore::setCustomBackupPath(string $dir)

you can set a different path with that function



* Visibility: **public**


#### Arguments
* $dir **string**



### getRealBackupPath

    string PrestaShopBackupCore::getRealBackupPath(string $filename)

get the path to use for backup (customBackupDir if specified, or default)



* Visibility: **public**


#### Arguments
* $filename **string** - &lt;p&gt;filename to use&lt;/p&gt;



### getBackupPath

    string PrestaShopBackupCore::getBackupPath(string $filename)

Get the full path of the backup file



* Visibility: **public**
* This method is **static**.


#### Arguments
* $filename **string** - &lt;p&gt;prefix of the backup file (datetime will be the second part)&lt;/p&gt;



### backupExist

    boolean PrestaShopBackupCore::backupExist(string $filename)

Check if a backup file exist



* Visibility: **public**
* This method is **static**.


#### Arguments
* $filename **string** - &lt;p&gt;prefix of the backup file (datetime will be the second part)&lt;/p&gt;



### getBackupURL

    string PrestaShopBackupCore::getBackupURL()

Get the URL used to retrieve this backup file



* Visibility: **public**




### delete

    boolean PrestaShopBackupCore::delete()

Delete the current backup file



* Visibility: **public**




### deleteSelection

    boolean PrestaShopBackupCore::deleteSelection($list)

Deletes a range of backup files



* Visibility: **public**


#### Arguments
* $list **mixed**



### add

    boolean PrestaShopBackupCore::add()

Creates a new backup file



* Visibility: **public**



