Class DbMySQLiCore
=====================





* Class name: DbMySQLiCore
* Parent class: [Db](class.DbCore.md)
* Source: [classes/db/DbMySQLi.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/db/DbMySQLi.php#L30)


Contents
--------



### Methods

* [Affected_Rows](#method-Affected_Rows)
* [Insert_ID](#method-Insert_ID)
* [_escape](#method-_escape)
* [_numRows](#method-_numRows)
* [_query](#method-_query)
* [checkAutoIncrement](#method-checkAutoIncrement)
* [checkCreatePrivilege](#method-checkCreatePrivilege)
* [connect](#method-connect)
* [createDatabase](#method-createDatabase)
* [disconnect](#method-disconnect)
* [getAll](#method-getAll)
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
mixed DbMySQLiCore::Affected_Rows()
```





* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/db/DbMySQLi.php#L151)




### <a name="method-Insert_ID"></a>Insert_ID

```php
mixed DbMySQLiCore::Insert_ID()
```





* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/db/DbMySQLi.php#L143)




### <a name="method-_escape"></a>_escape

```php
mixed DbMySQLiCore::_escape($str)
```





* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 183](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/db/DbMySQLi.php#L183)


#### Arguments
* $str **mixed**



### <a name="method-_numRows"></a>_numRows

```php
mixed DbMySQLiCore::_numRows($result)
```





* Visibility: **protected**
* Source: [classes/db/DbMySQLi.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/db/DbMySQLi.php#L135)


#### Arguments
* $result **mixed**



### <a name="method-_query"></a>_query

```php
mixed DbMySQLiCore::_query($sql)
```





* Visibility: **protected**
* Source: [classes/db/DbMySQLi.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/db/DbMySQLi.php#L89)


#### Arguments
* $sql **mixed**



### <a name="method-checkAutoIncrement"></a>checkAutoIncrement

```php
mixed DbMySQLiCore::checkAutoIncrement($server, $user, $pwd)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/DbMySQLi.php line 287](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/db/DbMySQLi.php#L287)


#### Arguments
* $server **mixed**
* $user **mixed**
* $pwd **mixed**



### <a name="method-checkCreatePrivilege"></a>checkCreatePrivilege

```php
mixed DbMySQLiCore::checkCreatePrivilege($server, $user, $pwd, $db, $prefix, $engine)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/DbMySQLi.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/db/DbMySQLi.php#L255)


#### Arguments
* $server **mixed**
* $user **mixed**
* $pwd **mixed**
* $db **mixed**
* $prefix **mixed**
* $engine **mixed**



### <a name="method-connect"></a>connect

```php
mixed DbMySQLiCore::connect()
```





* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/db/DbMySQLi.php#L35)




### <a name="method-createDatabase"></a>createDatabase

```php
mixed DbMySQLiCore::createDatabase($host, $user, $password, $database, $dropit)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/DbMySQLi.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/db/DbMySQLi.php#L56)


#### Arguments
* $host **mixed**
* $user **mixed**
* $password **mixed**
* $database **mixed**
* $dropit **mixed**



### <a name="method-disconnect"></a>disconnect

```php
mixed DbMySQLiCore::disconnect()
```





* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/db/DbMySQLi.php#L81)




### <a name="method-getAll"></a>getAll

```php
mixed DbMySQLiCore::getAll($result)
```





* Visibility: **protected**
* Source: [classes/db/DbMySQLi.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/db/DbMySQLi.php#L111)


#### Arguments
* $result **mixed**



### <a name="method-getBestEngine"></a>getBestEngine

```php
mixed DbMySQLiCore::getBestEngine()
```





* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 230](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/db/DbMySQLi.php#L230)




### <a name="method-getMsgError"></a>getMsgError

```php
mixed DbMySQLiCore::getMsgError($query)
```





* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/db/DbMySQLi.php#L159)


#### Arguments
* $query **mixed**



### <a name="method-getNumberError"></a>getNumberError

```php
mixed DbMySQLiCore::getNumberError()
```





* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/db/DbMySQLi.php#L167)




### <a name="method-getVersion"></a>getVersion

```php
mixed DbMySQLiCore::getVersion()
```





* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/db/DbMySQLi.php#L175)




### <a name="method-hasTableWithSamePrefix"></a>hasTableWithSamePrefix

```php
mixed DbMySQLiCore::hasTableWithSamePrefix($server, $user, $pwd, $db, $prefix)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/DbMySQLi.php line 199](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/db/DbMySQLi.php#L199)


#### Arguments
* $server **mixed**
* $user **mixed**
* $pwd **mixed**
* $db **mixed**
* $prefix **mixed**



### <a name="method-nextRow"></a>nextRow

```php
mixed DbMySQLiCore::nextRow($result)
```





* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/db/DbMySQLi.php#L97)


#### Arguments
* $result **mixed**



### <a name="method-set_db"></a>set_db

```php
mixed DbMySQLiCore::set_db($db_name)
```





* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/db/DbMySQLi.php#L191)


#### Arguments
* $db_name **mixed**



### <a name="method-tryToConnect"></a>tryToConnect

```php
mixed DbMySQLiCore::tryToConnect($server, $user, $pwd, $db, $newDbLink, $engine, $timeout)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/DbMySQLi.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/db/DbMySQLi.php#L213)


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
mixed DbMySQLiCore::tryUTF8($server, $user, $pwd)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/DbMySQLi.php line 279](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/db/DbMySQLi.php#L279)


#### Arguments
* $server **mixed**
* $user **mixed**
* $pwd **mixed**


