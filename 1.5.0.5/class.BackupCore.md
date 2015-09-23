Class BackupCore
=====================





* Class name: BackupCore
* Source: [classes/Backup.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/Backup.php#L28)


Contents
--------


### Properties

* [$backupDir](#property-$backupDir)
* [$customBackupDir](#property-$customBackupDir)
* [$error](#property-$error)
* [$id](#property-$id)
* [$psBackupAll](#property-$psBackupAll)
* [$psBackupDropTable](#property-$psBackupDropTable)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [delete](#method-delete)
* [deleteSelection](#method-deleteSelection)
* [getBackupPath](#method-getBackupPath)
* [getBackupURL](#method-getBackupURL)
* [getRealBackupPath](#method-getRealBackupPath)
* [setCustomBackupPath](#method-setCustomBackupPath)




Properties
----------


### <a name="property-$backupDir"></a>$backupDir

```php
public string $backupDir = '/backups/'
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Backup.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/Backup.php#L35).


### <a name="property-$customBackupDir"></a>$customBackupDir

```php
public string $customBackupDir = null
```





* Visibility: **public**
* Source: [classes/Backup.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/Backup.php#L37).


### <a name="property-$error"></a>$error

```php
public string $error
```





* Visibility: **public**
* Source: [classes/Backup.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/Backup.php#L33).


### <a name="property-$id"></a>$id

```php
public integer $id
```





* Visibility: **public**
* Source: [classes/Backup.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/Backup.php#L31).


### <a name="property-$psBackupAll"></a>$psBackupAll

```php
public mixed $psBackupAll = true
```





* Visibility: **public**
* Source: [classes/Backup.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/Backup.php#L39).


### <a name="property-$psBackupDropTable"></a>$psBackupDropTable

```php
public mixed $psBackupDropTable = true
```





* Visibility: **public**
* Source: [classes/Backup.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/Backup.php#L40).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed BackupCore::__construct(string $filename)
```

Creates a new backup object



* Visibility: **public**
* Source: [classes/Backup.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/Backup.php#L47)


#### Arguments
* $filename **string** - Filename of the backup file



### <a name="method-add"></a>add

```php
boolean BackupCore::add()
```

Creates a new backup file



* Visibility: **public**
* Source: [classes/Backup.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/Backup.php#L172)




### <a name="method-delete"></a>delete

```php
boolean BackupCore::delete()
```

Delete the current backup file



* Visibility: **public**
* Source: [classes/Backup.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/Backup.php#L138)




### <a name="method-deleteSelection"></a>deleteSelection

```php
boolean BackupCore::deleteSelection($list)
```

Deletes a range of backup files



* Visibility: **public**
* Source: [classes/Backup.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/Backup.php#L153)


#### Arguments
* $list **mixed**



### <a name="method-getBackupPath"></a>getBackupPath

```php
\The BackupCore::getBackupPath(string $filename)
```

Get the full path of the backup file



* Visibility: **public**
* This method is **static**.
* Source: [classes/Backup.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/Backup.php#L101)


#### Arguments
* $filename **string** - prefix of the backup file (datetime will be the second part)



### <a name="method-getBackupURL"></a>getBackupURL

```php
\The BackupCore::getBackupURL()
```

Get the URL used to retreive this backup file



* Visibility: **public**
* Source: [classes/Backup.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/Backup.php#L125)




### <a name="method-getRealBackupPath"></a>getRealBackupPath

```php
string BackupCore::getRealBackupPath(string $filename)
```

get the path to use for backup (customBackupDir if specified, or default)



* Visibility: **public**
* Source: [classes/Backup.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/Backup.php#L83)


#### Arguments
* $filename **string** - filename to use



### <a name="method-setCustomBackupPath"></a>setCustomBackupPath

```php
boolean BackupCore::setCustomBackupPath(string $dir)
```

you can set a different path with that function



* Visibility: **public**
* Source: [classes/Backup.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/Backup.php#L65)


#### Arguments
* $dir **string**


