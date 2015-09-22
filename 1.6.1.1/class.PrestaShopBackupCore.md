Class PrestaShopBackupCore
=====================





* Class name: PrestaShopBackupCore
* Source: [classes/PrestaShopBackup.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L27)


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
* [backupExist](#method-backupExist)
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
* Source: [classes/PrestaShopBackup.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L34).


### <a name="property-$customBackupDir"></a>$customBackupDir

```php
public string $customBackupDir = null
```





* Visibility: **public**
* Source: [classes/PrestaShopBackup.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L36).


### <a name="property-$error"></a>$error

```php
public string $error
```





* Visibility: **public**
* Source: [classes/PrestaShopBackup.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L32).


### <a name="property-$id"></a>$id

```php
public integer $id
```





* Visibility: **public**
* Source: [classes/PrestaShopBackup.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L30).


### <a name="property-$psBackupAll"></a>$psBackupAll

```php
public mixed $psBackupAll = true
```





* Visibility: **public**
* Source: [classes/PrestaShopBackup.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L38).


### <a name="property-$psBackupDropTable"></a>$psBackupDropTable

```php
public mixed $psBackupDropTable = true
```





* Visibility: **public**
* Source: [classes/PrestaShopBackup.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L39).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed PrestaShopBackupCore::__construct(string $filename)
```

Creates a new backup object



* Visibility: **public**
* Source: [classes/PrestaShopBackup.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L46)


#### Arguments
* $filename **string** - Filename of the backup file



### <a name="method-add"></a>add

```php
boolean PrestaShopBackupCore::add()
```

Creates a new backup file



* Visibility: **public**
* Source: [classes/PrestaShopBackup.php line 188](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L188)




### <a name="method-backupExist"></a>backupExist

```php
boolean PrestaShopBackupCore::backupExist(string $filename)
```

Check if a backup file exist



* Visibility: **public**
* This method is **static**.
* Source: [classes/PrestaShopBackup.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L131)


#### Arguments
* $filename **string** - prefix of the backup file (datetime will be the second part)



### <a name="method-delete"></a>delete

```php
boolean PrestaShopBackupCore::delete()
```

Delete the current backup file



* Visibility: **public**
* Source: [classes/PrestaShopBackup.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L156)




### <a name="method-deleteSelection"></a>deleteSelection

```php
boolean PrestaShopBackupCore::deleteSelection($list)
```

Deletes a range of backup files



* Visibility: **public**
* Source: [classes/PrestaShopBackup.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L171)


#### Arguments
* $list **mixed**



### <a name="method-getBackupPath"></a>getBackupPath

```php
string PrestaShopBackupCore::getBackupPath(string $filename)
```

Get the full path of the backup file



* Visibility: **public**
* This method is **static**.
* Source: [classes/PrestaShopBackup.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L103)


#### Arguments
* $filename **string** - prefix of the backup file (datetime will be the second part)



### <a name="method-getBackupURL"></a>getBackupURL

```php
string PrestaShopBackupCore::getBackupURL()
```

Get the URL used to retrieve this backup file



* Visibility: **public**
* Source: [classes/PrestaShopBackup.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L146)




### <a name="method-getRealBackupPath"></a>getRealBackupPath

```php
string PrestaShopBackupCore::getRealBackupPath(string $filename)
```

get the path to use for backup (customBackupDir if specified, or default)



* Visibility: **public**
* Source: [classes/PrestaShopBackup.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L83)


#### Arguments
* $filename **string** - filename to use



### <a name="method-setCustomBackupPath"></a>setCustomBackupPath

```php
boolean PrestaShopBackupCore::setCustomBackupPath(string $dir)
```

you can set a different path with that function



* Visibility: **public**
* Source: [classes/PrestaShopBackup.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopBackup.php#L65)


#### Arguments
* $dir **string**


