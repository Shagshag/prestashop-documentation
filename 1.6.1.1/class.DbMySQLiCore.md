Class DbMySQLiCore
=====================

Class DbMySQLiCore



* Class name: DbMySQLiCore
* Parent class: [Db](class.DbCore)
* Source: [classes/db/DbMySQLi.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L32)



Properties
----------

* [$link](#property-$link)
* [$result](#property-$result)

Methods
-------
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

    protected \mysqli $link





* Visibility: **protected**
* Source: [classes/db/DbMySQLi.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L35)


### <a name="property-$result"></a>$result

    protected mixed $result





* Visibility: **protected**
* Source: [classes/db/DbMySQLi.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L38)


Methods
-------


### <a name="method-Affected_Rows"></a>Affected_Rows

    integer DbMySQLiCore::Affected_Rows()

Return the number of rows affected by the last SQL query.



* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L195)




### <a name="method-Insert_ID"></a>Insert_ID

    string|integer DbMySQLiCore::Insert_ID()

Returns ID of the last inserted row.



* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 184](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L184)




### <a name="method-_escape"></a>_escape

    string DbMySQLiCore::_escape(string $str)

Escapes illegal characters in a string.



* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 241](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L241)


#### Arguments
* $str **string**



### <a name="method-_numRows"></a>_numRows

    integer DbMySQLiCore::_numRows(boolean|\mysqli_result $result)

Returns row count from the result set.



* Visibility: **protected**
* Source: [classes/db/DbMySQLi.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L173)


#### Arguments
* $result **boolean|mysqli_result**



### <a name="method-_query"></a>_query

    boolean|\mysqli_result DbMySQLiCore::_query(string $sql)

Executes an SQL statement, returning a result set as a mysqli_result object or true/false.



* Visibility: **protected**
* Source: [classes/db/DbMySQLi.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L111)


#### Arguments
* $sql **string**



### <a name="method-checkAutoIncrement"></a>checkAutoIncrement

    boolean DbMySQLiCore::checkAutoIncrement(string $server, string $user, string $pwd)

Checks if auto increment value and offset is 1



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/DbMySQLi.php line 408](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L408)


#### Arguments
* $server **string**
* $user **string**
* $pwd **string**



### <a name="method-checkCreatePrivilege"></a>checkCreatePrivilege

    boolean|string DbMySQLiCore::checkCreatePrivilege(string $server, string $user, string $pwd, string $db, string $prefix, string|null $engine)

Tries to connect to the database and create a table (checking creation privileges)



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/DbMySQLi.php line 359](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L359)


#### Arguments
* $server **string**
* $user **string**
* $pwd **string**
* $db **string**
* $prefix **string**
* $engine **string|null** - Table engine



### <a name="method-connect"></a>connect

    \mysqli DbMySQLiCore::connect()

Tries to connect to the database



* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L47)




### <a name="method-createDatabase"></a>createDatabase

    boolean|\mysqli_result DbMySQLiCore::createDatabase(string $host, string|null $user, string|null $password, string|null $database, boolean $dropit)

Tries to connect and create a new database



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/DbMySQLi.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L79)


#### Arguments
* $host **string**
* $user **string|null**
* $password **string|null**
* $database **string|null**
* $dropit **boolean** - If true, drops the created database.



### <a name="method-disconnect"></a>disconnect

    mixed DbMySQLiCore::disconnect()

Destroys the database connection link



* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L99)




### <a name="method-getAll"></a>getAll

    array|false DbMySQLiCore::getAll(boolean|\mysqli_result $result)

Returns all rows from the result set.



* Visibility: **protected**
* Source: [classes/db/DbMySQLi.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L143)


#### Arguments
* $result **boolean|mysqli_result**



### <a name="method-getBestEngine"></a>getBestEngine

    string DbMySQLiCore::getBestEngine()

Selects best table engine.



* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 319](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L319)




### <a name="method-getMsgError"></a>getMsgError

    string DbMySQLiCore::getMsgError(boolean $query)

Returns error message.



* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 207](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L207)


#### Arguments
* $query **boolean**



### <a name="method-getNumberError"></a>getNumberError

    integer DbMySQLiCore::getNumberError()

Returns error code.



* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 218](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L218)




### <a name="method-getVersion"></a>getVersion

    string DbMySQLiCore::getVersion()

Returns database server version.



* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L229)




### <a name="method-hasTableWithSamePrefix"></a>hasTableWithSamePrefix

    boolean DbMySQLiCore::hasTableWithSamePrefix(string $server, string $user, string $pwd, string $db, string $prefix)

Try a connection to the database and check if at least one table with same prefix exists



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/DbMySQLi.php line 269](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L269)


#### Arguments
* $server **string** - Server address
* $user **string** - Login for database connection
* $pwd **string** - Password for database connection
* $db **string** - Database name
* $prefix **string** - Tables prefix



### <a name="method-nextRow"></a>nextRow

    array|boolean DbMySQLiCore::nextRow(boolean|\mysqli_result $result)

Returns the next row from the result set.



* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L123)


#### Arguments
* $result **boolean|mysqli_result**



### <a name="method-set_db"></a>set_db

    boolean DbMySQLiCore::set_db(string $db_name)

Switches to a different database.



* Visibility: **public**
* Source: [classes/db/DbMySQLi.php line 253](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L253)


#### Arguments
* $db_name **string**



### <a name="method-tryToConnect"></a>tryToConnect

    integer DbMySQLiCore::tryToConnect(string $server, string $user, string $pwd, string $db, $new_db_link, string|boolean $engine, integer $timeout)

Try a connection to the database



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/DbMySQLi.php line 294](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L294)


#### Arguments
* $server **string** - Server address
* $user **string** - Login for database connection
* $pwd **string** - Password for database connection
* $db **string** - Database name
* $new_db_link **mixed**
* $engine **string|boolean**
* $timeout **integer**



### <a name="method-tryUTF8"></a>tryUTF8

    boolean DbMySQLiCore::tryUTF8(string $server, string $user, string $pwd)

Try a connection to the database and set names to UTF-8



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/DbMySQLi.php line 392](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L392)


#### Arguments
* $server **string** - Server address
* $user **string** - Login for database connection
* $pwd **string** - Password for database connection


