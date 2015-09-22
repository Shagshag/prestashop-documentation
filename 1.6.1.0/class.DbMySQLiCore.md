Class DbMySQLiCore
=====================

Class DbMySQLiCore



* Class name: DbMySQLiCore
* Parent class: [Db](class.DbCore.md)
* Source: [classes/db/DbMySQLi.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbMySQLi.php#L32)


Contents
--------


### Properties

* [$link](#property-$link)
* [$result](#property-$result)

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




Properties
----------


### <a name="property-$link"></a>$link

```php
protected \mysqli $link
```





* Visibility: **protected**
* Source: [classes/db/DbMySQLi.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbMySQLi.php#L35).


### <a name="property-$result"></a>$result

```php
protected mixed $result
```





* Visibility: **protected**
* Source: [classes/db/DbMySQLi.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbMySQLi.php#L38).


Methods
-------


### <a name="method-Affected_Rows"></a>Affected_Rows

```php
integer DbMySQLiCore::Affected_Rows()
```

Return the number of rows affected by the last SQL query.



* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 190](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbMySQLi.php#L190)




### <a name="method-Insert_ID"></a>Insert_ID

```php
string|integer DbMySQLiCore::Insert_ID()
```

Returns ID of the last inserted row.



* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbMySQLi.php#L179)




### <a name="method-_escape"></a>_escape

```php
string DbMySQLiCore::_escape(string $str)
```

Escapes illegal characters in a string.



* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 236](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbMySQLi.php#L236)


#### Arguments
* $str **string**



### <a name="method-_numRows"></a>_numRows

```php
integer DbMySQLiCore::_numRows(boolean|\mysqli_result $result)
```

Returns row count from the result set.



* Visibility: **protected**
* Source: [classes/db/DbMySQLi.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbMySQLi.php#L168)


#### Arguments
* $result **boolean|mysqli_result**



### <a name="method-_query"></a>_query

```php
boolean|\mysqli_result DbMySQLiCore::_query(string $sql)
```

Executes an SQL statement, returning a result set as a mysqli_result object or true/false.



* Visibility: **protected**
* Source: [classes/db/DbMySQLi.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbMySQLi.php#L110)


#### Arguments
* $sql **string**



### <a name="method-checkAutoIncrement"></a>checkAutoIncrement

```php
boolean DbMySQLiCore::checkAutoIncrement(string $server, string $user, string $pwd)
```

Checks if auto increment value and offset is 1



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/DbMySQLi.php line 393](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbMySQLi.php#L393)


#### Arguments
* $server **string**
* $user **string**
* $pwd **string**



### <a name="method-checkCreatePrivilege"></a>checkCreatePrivilege

```php
boolean|string DbMySQLiCore::checkCreatePrivilege(string $server, string $user, string $pwd, string $db, string $prefix, string|null $engine)
```

Tries to connect to the database and create a table (checking creation privileges)



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/DbMySQLi.php line 347](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbMySQLi.php#L347)


#### Arguments
* $server **string**
* $user **string**
* $pwd **string**
* $db **string**
* $prefix **string**
* $engine **string|null** - Table engine



### <a name="method-connect"></a>connect

```php
\mysqli DbMySQLiCore::connect()
```

Tries to connect to the database



* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbMySQLi.php#L47)




### <a name="method-createDatabase"></a>createDatabase

```php
boolean|\mysqli_result DbMySQLiCore::createDatabase(string $host, string|null $user, string|null $password, string|null $database, boolean $dropit)
```

Tries to connect and create a new database



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/DbMySQLi.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbMySQLi.php#L78)


#### Arguments
* $host **string**
* $user **string|null**
* $password **string|null**
* $database **string|null**
* $dropit **boolean** - If true, drops the created database.



### <a name="method-disconnect"></a>disconnect

```php
mixed DbMySQLiCore::disconnect()
```

Destroys the database connection link



* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbMySQLi.php#L98)




### <a name="method-getAll"></a>getAll

```php
array|false DbMySQLiCore::getAll(boolean|\mysqli_result $result)
```

Returns all rows from the result set.



* Visibility: **protected**
* Source: [classes/db/DbMySQLi.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbMySQLi.php#L140)


#### Arguments
* $result **boolean|mysqli_result**



### <a name="method-getBestEngine"></a>getBestEngine

```php
string DbMySQLiCore::getBestEngine()
```

Selects best table engine.



* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 310](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbMySQLi.php#L310)




### <a name="method-getMsgError"></a>getMsgError

```php
string DbMySQLiCore::getMsgError(boolean $query)
```

Returns error message.



* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbMySQLi.php#L202)


#### Arguments
* $query **boolean**



### <a name="method-getNumberError"></a>getNumberError

```php
integer DbMySQLiCore::getNumberError()
```

Returns error code.



* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbMySQLi.php#L213)




### <a name="method-getVersion"></a>getVersion

```php
string DbMySQLiCore::getVersion()
```

Returns database server version.



* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 224](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbMySQLi.php#L224)




### <a name="method-hasTableWithSamePrefix"></a>hasTableWithSamePrefix

```php
boolean DbMySQLiCore::hasTableWithSamePrefix(string $server, string $user, string $pwd, string $db, string $prefix)
```

Try a connection to the database and check if at least one table with same prefix exists



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/DbMySQLi.php line 264](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbMySQLi.php#L264)


#### Arguments
* $server **string** - Server address
* $user **string** - Login for database connection
* $pwd **string** - Password for database connection
* $db **string** - Database name
* $prefix **string** - Tables prefix



### <a name="method-nextRow"></a>nextRow

```php
array|boolean DbMySQLiCore::nextRow(boolean|\mysqli_result $result)
```

Returns the next row from the result set.



* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbMySQLi.php#L122)


#### Arguments
* $result **boolean|mysqli_result**



### <a name="method-set_db"></a>set_db

```php
boolean DbMySQLiCore::set_db(string $db_name)
```

Switches to a different database.



* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 248](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbMySQLi.php#L248)


#### Arguments
* $db_name **string**



### <a name="method-tryToConnect"></a>tryToConnect

```php
integer DbMySQLiCore::tryToConnect(string $server, string $user, string $pwd, string $db, $new_db_link, string|boolean $engine, integer $timeout)
```

Try a connection to the database



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/DbMySQLi.php line 288](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbMySQLi.php#L288)


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
boolean DbMySQLiCore::tryUTF8(string $server, string $user, string $pwd)
```

Try a connection to the database and set names to UTF-8



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/DbMySQLi.php line 377](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/DbMySQLi.php#L377)


#### Arguments
* $server **string** - Server address
* $user **string** - Login for database connection
* $pwd **string** - Password for database connection


