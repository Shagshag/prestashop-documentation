PrestaShopBackupCore
===============






* Class name: PrestaShopBackupCore
* Namespace: 
* This class is defined in classes\PrestaShopBackup.php line 27





Properties
----------


### $id

    public integer $id





* Visibility: **public**
* This property is defined in classes\PrestaShopBackup.php line 30


### $error

    public string $error





* Visibility: **public**
* This property is defined in classes\PrestaShopBackup.php line 32


### $backupDir

    public string $backupDir = '/backups/'





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\PrestaShopBackup.php line 34


### $customBackupDir

    public string $customBackupDir = null





* Visibility: **public**
* This property is defined in classes\PrestaShopBackup.php line 36


### $psBackupAll

    public mixed $psBackupAll = true





* Visibility: **public**
* This property is defined in classes\PrestaShopBackup.php line 38


### $psBackupDropTable

    public mixed $psBackupDropTable = true





* Visibility: **public**
* This property is defined in classes\PrestaShopBackup.php line 39


Methods
-------


### __construct

    mixed PrestaShopBackupCore::__construct(string $filename)

Creates a new backup object



* Visibility: **public**
* This method is defined in classes\PrestaShopBackup.php line 46


#### Arguments
* $filename **string** - &lt;p&gt;Filename of the backup file&lt;/p&gt;



### setCustomBackupPath

    boolean PrestaShopBackupCore::setCustomBackupPath(string $dir)

you can set a different path with that function



* Visibility: **public**
* This method is defined in classes\PrestaShopBackup.php line 65


#### Arguments
* $dir **string**



### getRealBackupPath

    string PrestaShopBackupCore::getRealBackupPath(string $filename)

get the path to use for backup (customBackupDir if specified, or default)



* Visibility: **public**
* This method is defined in classes\PrestaShopBackup.php line 83


#### Arguments
* $filename **string** - &lt;p&gt;filename to use&lt;/p&gt;



### getBackupPath

    string PrestaShopBackupCore::getBackupPath(string $filename)

Get the full path of the backup file



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\PrestaShopBackup.php line 103


#### Arguments
* $filename **string** - &lt;p&gt;prefix of the backup file (datetime will be the second part)&lt;/p&gt;



### backupExist

    boolean PrestaShopBackupCore::backupExist(string $filename)

Check if a backup file exist



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\PrestaShopBackup.php line 131


#### Arguments
* $filename **string** - &lt;p&gt;prefix of the backup file (datetime will be the second part)&lt;/p&gt;



### getBackupURL

    string PrestaShopBackupCore::getBackupURL()

Get the URL used to retrieve this backup file



* Visibility: **public**
* This method is defined in classes\PrestaShopBackup.php line 146




### delete

    boolean PrestaShopBackupCore::delete()

Delete the current backup file



* Visibility: **public**
* This method is defined in classes\PrestaShopBackup.php line 156




### deleteSelection

    boolean PrestaShopBackupCore::deleteSelection($list)

Deletes a range of backup files



* Visibility: **public**
* This method is defined in classes\PrestaShopBackup.php line 171


#### Arguments
* $list **mixed**



### add

    boolean PrestaShopBackupCore::add()

Creates a new backup file



* Visibility: **public**
* This method is defined in classes\PrestaShopBackup.php line 188



