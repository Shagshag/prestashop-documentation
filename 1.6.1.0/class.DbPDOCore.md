Class DbPDOCore
=====================

Class DbPDOCore



* Class name: DbPDOCore
* Parent class: [Db](class.DbCore.md)
* Source: [classes/db/DbPDO.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbPDO.php#L32)


Contents
--------


### Properties

* [$link](#property-$link)
* [$result](#property-$result)

### Methods

* [Affected_Rows](#method-Affected_Rows)
* [Insert_ID](#method-Insert_ID)
* [_escape](#method-_escape)
* [_getPDO](#method-_getPDO)
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




Properties
----------


### <a name="property-$link"></a>$link

```php
protected \PDO $link
```





* Visibility: **protected**
* Source: [classes/db/DbPDO.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbPDO.php#L35).


### <a name="property-$result"></a>$result

```php
protected mixed $result
```





* Visibility: **protected**
* Source: [classes/db/DbPDO.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbPDO.php#L38).


Methods
-------


### <a name="method-Affected_Rows"></a>Affected_Rows

```php
integer DbPDOCore::Affected_Rows()
```

Return the number of rows affected by the last SQL query.



* Visibility: **public**
* Source: [classes/db/DbPDO.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbPDO.php#L196)




### <a name="method-Insert_ID"></a>Insert_ID

```php
string|integer DbPDOCore::Insert_ID()
```

Returns ID of the last inserted row.



* Visibility: **public**
* Source: [classes/db/DbPDO.php line 185](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbPDO.php#L185)




### <a name="method-_escape"></a>_escape

```php
string DbPDOCore::_escape(string $str)
```

Escapes illegal characters in a string.



* Visibility: **public**
* Source: [classes/db/DbPDO.php line 244](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbPDO.php#L244)


#### Arguments
* $str **string**



### <a name="method-_getPDO"></a>_getPDO

```php
\PDO DbPDOCore::_getPDO(string $host, string $user, string $password, string $dbname, integer $timeout)
```

Returns a new PDO object (database link)



* Visibility: **protected**
* This method is **static**.
* Source: [classes/db/DbPDO.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbPDO.php#L50)


#### Arguments
* $host **string**
* $user **string**
* $password **string**
* $dbname **string**
* $timeout **integer**



### <a name="method-_numRows"></a>_numRows

```php
integer DbPDOCore::_numRows(\PDOStatement $result)
```

Returns row count from the result set.



* Visibility: **protected**
* Source: [classes/db/DbPDO.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbPDO.php#L174)


#### Arguments
* $result **PDOStatement**



### <a name="method-_query"></a>_query

```php
\PDOStatement DbPDOCore::_query(string $sql)
```

Executes an SQL statement, returning a result set as a PDOStatement object or true/false.



* Visibility: **protected**
* Source: [classes/db/DbPDO.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbPDO.php#L126)


#### Arguments
* $sql **string**



### <a name="method-checkAutoIncrement"></a>checkAutoIncrement

```php
boolean DbPDOCore::checkAutoIncrement(string $server, string $user, string $pwd)
```

Checks if auto increment value and offset is 1



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/DbPDO.php line 408](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbPDO.php#L408)


#### Arguments
* $server **string**
* $user **string**
* $pwd **string**



### <a name="method-checkCreatePrivilege"></a>checkCreatePrivilege

```php
boolean|string DbPDOCore::checkCreatePrivilege(string $server, string $user, string $pwd, string $db, string $prefix, string|null $engine)
```

Tries to connect to the database and create a table (checking creation privileges)



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/DbPDO.php line 298](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbPDO.php#L298)


#### Arguments
* $server **string**
* $user **string**
* $pwd **string**
* $db **string**
* $prefix **string**
* $engine **string|null** - Table engine



### <a name="method-connect"></a>connect

```php
\PDO DbPDOCore::connect()
```

Tries to connect to the database



* Visibility: **public**
* Source: [classes/db/DbPDO.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbPDO.php#L94)




### <a name="method-createDatabase"></a>createDatabase

```php
boolean|integer DbPDOCore::createDatabase(string $host, string $user, string $password, string $dbname, boolean $dropit)
```

Tries to connect and create a new database



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/DbPDO.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbPDO.php#L75)


#### Arguments
* $host **string**
* $user **string**
* $password **string**
* $dbname **string**
* $dropit **boolean** - If true, drops the created database.



### <a name="method-disconnect"></a>disconnect

```php
mixed DbPDOCore::disconnect()
```

Destroys the database connection link



* Visibility: **public**
* Source: [classes/db/DbPDO.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbPDO.php#L114)




### <a name="method-getAll"></a>getAll

```php
array|false|null DbPDOCore::getAll(boolean $result)
```

Returns all rows from the result set.



* Visibility: **protected**
* Source: [classes/db/DbPDO.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbPDO.php#L156)


#### Arguments
* $result **boolean**



### <a name="method-getBestEngine"></a>getBestEngine

```php
string DbPDOCore::getBestEngine()
```

Selects best table engine.



* Visibility: **public**
* Source: [classes/db/DbPDO.php line 352](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbPDO.php#L352)




### <a name="method-getMsgError"></a>getMsgError

```php
string DbPDOCore::getMsgError(boolean $query)
```

Returns error message.



* Visibility: **public**
* Source: [classes/db/DbPDO.php line 208](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbPDO.php#L208)


#### Arguments
* $query **boolean**



### <a name="method-getNumberError"></a>getNumberError

```php
integer DbPDOCore::getNumberError()
```

Returns error code.



* Visibility: **public**
* Source: [classes/db/DbPDO.php line 220](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbPDO.php#L220)




### <a name="method-getVersion"></a>getVersion

```php
string DbPDOCore::getVersion()
```

Returns database server version.



* Visibility: **public**
* Source: [classes/db/DbPDO.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbPDO.php#L232)




### <a name="method-hasTableWithSamePrefix"></a>hasTableWithSamePrefix

```php
boolean DbPDOCore::hasTableWithSamePrefix(string $server, string $user, string $pwd, string $db, string $prefix)
```

Try a connection to the database and check if at least one table with same prefix exists



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/DbPDO.php line 274](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbPDO.php#L274)


#### Arguments
* $server **string** - Server address
* $user **string** - Login for database connection
* $pwd **string** - Password for database connection
* $db **string** - Database name
* $prefix **string** - Tables prefix



### <a name="method-nextRow"></a>nextRow

```php
array|false|null DbPDOCore::nextRow(boolean $result)
```

Returns the next row from the result set.



* Visibility: **public**
* Source: [classes/db/DbPDO.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbPDO.php#L138)


#### Arguments
* $result **boolean**



### <a name="method-set_db"></a>set_db

```php
integer DbPDOCore::set_db(string $db_name)
```

Switches to a different database.



* Visibility: **public**
* Source: [classes/db/DbPDO.php line 258](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbPDO.php#L258)


#### Arguments
* $db_name **string**



### <a name="method-tryToConnect"></a>tryToConnect

```php
integer DbPDOCore::tryToConnect(string $server, string $user, string $pwd, string $db, $new_db_link, string|boolean $engine, integer $timeout)
```

Try a connection to the database



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/DbPDO.php line 335](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbPDO.php#L335)


#### Arguments
* $server **string** - Server address
* $user **string** - Login for database connection
* $pwd **string** - Password for database connection
* $db **string** - Database name
* $new_db_link **mixed**
* $engine **string|boolean**
* $timeout **integer**



### <a name="method-tryUTF8"></a>tryUTF8

```php
boolean DbPDOCore::tryUTF8(string $server, string $user, string $pwd)
```

Try a connection to the database and set names to UTF-8



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/DbPDO.php line 387](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbPDO.php#L387)


#### Arguments
* $server **string** - Server address
* $user **string** - Login for database connection
* $pwd **string** - Password for database connection


