Class MySQLCore
=====================





* Class name: MySQLCore
* Parent class: [Db](class.DbCore.md)
* Source: [classes/db/MySQL.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/MySQL.php#L27)


Contents
--------



### Methods

* [Affected_Rows](#method-Affected_Rows)
* [Insert_ID](#method-Insert_ID)
* [_escape](#method-_escape)
* [_numRows](#method-_numRows)
* [_query](#method-_query)
* [checkCreatePrivilege](#method-checkCreatePrivilege)
* [connect](#method-connect)
* [createDatabase](#method-createDatabase)
* [disconnect](#method-disconnect)
* [getBestEngine](#method-getBestEngine)
* [getMsgError](#method-getMsgError)
* [getNumberError](#method-getNumberError)
* [getVersion](#method-getVersion)
* [hasTableWithSamePrefix](#method-hasTableWithSamePrefix)
* [nextRow](#method-nextRow)
* [set_db](#method-set_db)
* [tryToConnect](#method-tryToConnect)
* [tryUTF8](#method-tryUTF8)






Methods
-------


### <a name="method-Affected_Rows"></a>Affected_Rows

```php
mixed MySQLCore::Affected_Rows()
```





* Visibility: **public**
* Source: [classes/db/MySQL.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/MySQL.php#L107)




### <a name="method-Insert_ID"></a>Insert_ID

```php
mixed MySQLCore::Insert_ID()
```





* Visibility: **public**
* Source: [classes/db/MySQL.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/MySQL.php#L99)




### <a name="method-_escape"></a>_escape

```php
mixed MySQLCore::_escape($str)
```





* Visibility: **public**
* Source: [classes/db/MySQL.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/MySQL.php#L139)


#### Arguments
* $str **mixed**



### <a name="method-_numRows"></a>_numRows

```php
mixed MySQLCore::_numRows($result)
```





* Visibility: **protected**
* Source: [classes/db/MySQL.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/MySQL.php#L91)


#### Arguments
* $result **mixed**



### <a name="method-_query"></a>_query

```php
mixed MySQLCore::_query($sql)
```





* Visibility: **protected**
* Source: [classes/db/MySQL.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/MySQL.php#L70)


#### Arguments
* $sql **mixed**



### <a name="method-checkCreatePrivilege"></a>checkCreatePrivilege

```php
mixed MySQLCore::checkCreatePrivilege($server, $user, $pwd, $db, $prefix, $engine)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/MySQL.php line 206](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/MySQL.php#L206)


#### Arguments
* $server **mixed**
* $user **mixed**
* $pwd **mixed**
* $db **mixed**
* $prefix **mixed**
* $engine **mixed**



### <a name="method-connect"></a>connect

```php
mixed MySQLCore::connect()
```





* Visibility: **public**
* Source: [classes/db/MySQL.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/MySQL.php#L32)




### <a name="method-createDatabase"></a>createDatabase

```php
mixed MySQLCore::createDatabase($host, $user, $password, $dbname, $dropit)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/MySQL.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/MySQL.php#L50)


#### Arguments
* $host **mixed**
* $user **mixed**
* $password **mixed**
* $dbname **mixed**
* $dropit **mixed**



### <a name="method-disconnect"></a>disconnect

```php
mixed MySQLCore::disconnect()
```





* Visibility: **public**
* Source: [classes/db/MySQL.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/MySQL.php#L62)




### <a name="method-getBestEngine"></a>getBestEngine

```php
mixed MySQLCore::getBestEngine()
```





* Visibility: **public**
* Source: [classes/db/MySQL.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/MySQL.php#L181)




### <a name="method-getMsgError"></a>getMsgError

```php
mixed MySQLCore::getMsgError($query)
```





* Visibility: **public**
* Source: [classes/db/MySQL.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/MySQL.php#L115)


#### Arguments
* $query **mixed**



### <a name="method-getNumberError"></a>getNumberError

```php
mixed MySQLCore::getNumberError()
```





* Visibility: **public**
* Source: [classes/db/MySQL.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/MySQL.php#L123)




### <a name="method-getVersion"></a>getVersion

```php
mixed MySQLCore::getVersion()
```





* Visibility: **public**
* Source: [classes/db/MySQL.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/MySQL.php#L131)




### <a name="method-hasTableWithSamePrefix"></a>hasTableWithSamePrefix

```php
mixed MySQLCore::hasTableWithSamePrefix($server, $user, $pwd, $db, $prefix)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/MySQL.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/MySQL.php#L155)


#### Arguments
* $server **mixed**
* $user **mixed**
* $pwd **mixed**
* $db **mixed**
* $prefix **mixed**



### <a name="method-nextRow"></a>nextRow

```php
mixed MySQLCore::nextRow($result)
```





* Visibility: **public**
* Source: [classes/db/MySQL.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/MySQL.php#L78)


#### Arguments
* $result **mixed**



### <a name="method-set_db"></a>set_db

```php
mixed MySQLCore::set_db($db_name)
```





* Visibility: **public**
* Source: [classes/db/MySQL.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/MySQL.php#L147)


#### Arguments
* $db_name **mixed**



### <a name="method-tryToConnect"></a>tryToConnect

```php
mixed MySQLCore::tryToConnect($server, $user, $pwd, $db, $newDbLink, $engine, $timeout)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/MySQL.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/MySQL.php#L170)


#### Arguments
* $server **mixed**
* $user **mixed**
* $pwd **mixed**
* $db **mixed**
* $newDbLink **mixed**
* $engine **mixed**
* $timeout **mixed**



### <a name="method-tryUTF8"></a>tryUTF8

```php
mixed MySQLCore::tryUTF8($server, $user, $pwd)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/MySQL.php line 231](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/MySQL.php#L231)


#### Arguments
* $server **mixed**
* $user **mixed**
* $pwd **mixed**


