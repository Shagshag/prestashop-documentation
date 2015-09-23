Class ImportModuleCore
=====================

ImportModule class, ImportModule.php
Import module management



* Class name: ImportModuleCore
* This is an **abstract** class
* Parent class: [Module](class.ModuleCore.md)
* Source: [classes/module/ImportModule.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/module/ImportModule.php#L34)


Contents
--------


### Properties

* [$_link](#property-$_link)
* [$database](#property-$database)
* [$passwd](#property-$passwd)
* [$prefix](#property-$prefix)
* [$server](#property-$server)
* [$user](#property-$user)

### Methods

* [Execute](#method-Execute)
* [ExecuteS](#method-ExecuteS)
* [__destruct](#method-__destruct)
* [getDefaultIdLang](#method-getDefaultIdLang)
* [getImportModulesOnDisk](#method-getImportModulesOnDisk)
* [getValue](#method-getValue)
* [initDatabaseConnection](#method-initDatabaseConnection)




Properties
----------


### <a name="property-$_link"></a>$_link

```php
protected mixed $_link = null
```





* Visibility: **protected**
* Source: [classes/module/ImportModule.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/module/ImportModule.php#L36).


### <a name="property-$database"></a>$database

```php
public mixed $database
```





* Visibility: **public**
* Source: [classes/module/ImportModule.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/module/ImportModule.php#L44).


### <a name="property-$passwd"></a>$passwd

```php
public mixed $passwd
```





* Visibility: **public**
* Source: [classes/module/ImportModule.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/module/ImportModule.php#L42).


### <a name="property-$prefix"></a>$prefix

```php
public string $prefix
```





* Visibility: **public**
* Source: [classes/module/ImportModule.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/module/ImportModule.php#L47).


### <a name="property-$server"></a>$server

```php
public mixed $server
```





* Visibility: **public**
* Source: [classes/module/ImportModule.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/module/ImportModule.php#L38).


### <a name="property-$user"></a>$user

```php
public mixed $user
```





* Visibility: **public**
* Source: [classes/module/ImportModule.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/module/ImportModule.php#L40).


Methods
-------


### <a name="method-Execute"></a>Execute

```php
mixed ImportModuleCore::Execute($query)
```





* Visibility: **public**
* Source: [classes/module/ImportModule.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/module/ImportModule.php#L83)


#### Arguments
* $query **mixed**



### <a name="method-ExecuteS"></a>ExecuteS

```php
mixed ImportModuleCore::ExecuteS($query)
```





* Visibility: **public**
* Source: [classes/module/ImportModule.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/module/ImportModule.php#L72)


#### Arguments
* $query **mixed**



### <a name="method-__destruct"></a>__destruct

```php
mixed ImportModuleCore::__destruct()
```





* Visibility: **public**
* Source: [classes/module/ImportModule.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/module/ImportModule.php#L50)




### <a name="method-getDefaultIdLang"></a>getDefaultIdLang

```php
mixed ImportModuleCore::getDefaultIdLang()
```





* Visibility: **public**
* This method is **abstract**.
* Source: [classes/module/ImportModule.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/module/ImportModule.php#L108)




### <a name="method-getImportModulesOnDisk"></a>getImportModulesOnDisk

```php
mixed ImportModuleCore::getImportModulesOnDisk()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/module/ImportModule.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/module/ImportModule.php#L99)




### <a name="method-getValue"></a>getValue

```php
mixed ImportModuleCore::getValue($query)
```





* Visibility: **public**
* Source: [classes/module/ImportModule.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/module/ImportModule.php#L89)


#### Arguments
* $query **mixed**



### <a name="method-initDatabaseConnection"></a>initDatabaseConnection

```php
mixed ImportModuleCore::initDatabaseConnection()
```





* Visibility: **protected**
* Source: [classes/module/ImportModule.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/module/ImportModule.php#L56)



