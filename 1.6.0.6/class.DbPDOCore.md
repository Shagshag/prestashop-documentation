Class DbPDOCore
=====================





* Class name: DbPDOCore
* Parent class: [Db](class.DbCore.md)
* Source: [classes/db/DbPDO.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/DbPDO.php#L30)


Contents
--------



### Methods

* [Affected_Rows](#method-Affected_Rows)
* [Insert_ID](#method-Insert_ID)
* [_escape](#method-_escape)
* [_getPDO](#method-_getPDO)
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
mixed DbPDOCore::Affected_Rows()
```





* Visibility: **public**
* Source: [classes/db/DbPDO.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/DbPDO.php#L125)




### <a name="method-Insert_ID"></a>Insert_ID

```php
mixed DbPDOCore::Insert_ID()
```





* Visibility: **public**
* Source: [classes/db/DbPDO.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/DbPDO.php#L117)




### <a name="method-_escape"></a>_escape

```php
mixed DbPDOCore::_escape($str)
```





* Visibility: **public**
* Source: [classes/db/DbPDO.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/DbPDO.php#L159)


#### Arguments
* $str **mixed**



### <a name="method-_getPDO"></a>_getPDO

```php
mixed DbPDOCore::_getPDO($host, $user, $password, $dbname, $timeout)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/db/DbPDO.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/DbPDO.php#L32)


#### Arguments
* $host **mixed**
* $user **mixed**
* $password **mixed**
* $dbname **mixed**
* $timeout **mixed**



### <a name="method-_numRows"></a>_numRows

```php
mixed DbPDOCore::_numRows($result)
```





* Visibility: **protected**
* Source: [classes/db/DbPDO.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/DbPDO.php#L109)


#### Arguments
* $result **mixed**



### <a name="method-_query"></a>_query

```php
mixed DbPDOCore::_query($sql)
```





* Visibility: **protected**
* Source: [classes/db/DbPDO.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/DbPDO.php#L89)


#### Arguments
* $sql **mixed**



### <a name="method-checkCreatePrivilege"></a>checkCreatePrivilege

```php
mixed DbPDOCore::checkCreatePrivilege($server, $user, $pwd, $db, $prefix, $engine)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/DbPDO.php line 190](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/DbPDO.php#L190)


#### Arguments
* $server **mixed**
* $user **mixed**
* $pwd **mixed**
* $db **mixed**
* $prefix **mixed**
* $engine **mixed**



### <a name="method-connect"></a>connect

```php
mixed DbPDOCore::connect()
```





* Visibility: **public**
* Source: [classes/db/DbPDO.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/DbPDO.php#L63)




### <a name="method-createDatabase"></a>createDatabase

```php
mixed DbPDOCore::createDatabase($host, $user, $password, $dbname, $dropit)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/DbPDO.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/DbPDO.php#L47)


#### Arguments
* $host **mixed**
* $user **mixed**
* $password **mixed**
* $dbname **mixed**
* $dropit **mixed**



### <a name="method-disconnect"></a>disconnect

```php
mixed DbPDOCore::disconnect()
```





* Visibility: **public**
* Source: [classes/db/DbPDO.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/DbPDO.php#L81)




### <a name="method-getBestEngine"></a>getBestEngine

```php
mixed DbPDOCore::getBestEngine()
```





* Visibility: **public**
* Source: [classes/db/DbPDO.php line 226](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/DbPDO.php#L226)




### <a name="method-getMsgError"></a>getMsgError

```php
mixed DbPDOCore::getMsgError($query)
```





* Visibility: **public**
* Source: [classes/db/DbPDO.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/DbPDO.php#L133)


#### Arguments
* $query **mixed**



### <a name="method-getNumberError"></a>getNumberError

```php
mixed DbPDOCore::getNumberError()
```





* Visibility: **public**
* Source: [classes/db/DbPDO.php line 142](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/DbPDO.php#L142)




### <a name="method-getVersion"></a>getVersion

```php
mixed DbPDOCore::getVersion()
```





* Visibility: **public**
* Source: [classes/db/DbPDO.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/DbPDO.php#L151)




### <a name="method-hasTableWithSamePrefix"></a>hasTableWithSamePrefix

```php
mixed DbPDOCore::hasTableWithSamePrefix($server, $user, $pwd, $db, $prefix)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/DbPDO.php line 177](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/DbPDO.php#L177)


#### Arguments
* $server **mixed**
* $user **mixed**
* $pwd **mixed**
* $db **mixed**
* $prefix **mixed**



### <a name="method-nextRow"></a>nextRow

```php
mixed DbPDOCore::nextRow($result)
```





* Visibility: **public**
* Source: [classes/db/DbPDO.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/DbPDO.php#L97)


#### Arguments
* $result **mixed**



### <a name="method-set_db"></a>set_db

```php
mixed DbPDOCore::set_db($db_name)
```





* Visibility: **public**
* Source: [classes/db/DbPDO.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/DbPDO.php#L169)


#### Arguments
* $db_name **mixed**



### <a name="method-tryToConnect"></a>tryToConnect

```php
mixed DbPDOCore::tryToConnect($server, $user, $pwd, $db, $newDbLink, $engine, $timeout)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/DbPDO.php line 215](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/DbPDO.php#L215)


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
mixed DbPDOCore::tryUTF8($server, $user, $pwd)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/DbPDO.php line 254](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/db/DbPDO.php#L254)


#### Arguments
* $server **mixed**
* $user **mixed**
* $pwd **mixed**


