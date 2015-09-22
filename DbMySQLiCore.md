DbMySQLiCore
===============

Class DbMySQLiCore




* Class name: DbMySQLiCore
* Parent class: [Db](DbCore)
* This class is defined in [classes/db/DbMySQLi.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L32)





Properties
----------

* [$link](#property-$link)
* [$result](#property-$result)

Methods
-------
* [connect](#method-connect)
* [createDatabase](#method-createDatabase)
* [disconnect](#method-disconnect)
* [_query](#method-_query)
* [nextRow](#method-nextRow)
* [getAll](#method-getAll)
* [_numRows](#method-_numRows)
* [Insert_ID](#method-Insert_ID)
* [Affected_Rows](#method-Affected_Rows)
* [getMsgError](#method-getMsgError)
* [getNumberError](#method-getNumberError)
* [getVersion](#method-getVersion)
* [_escape](#method-_escape)
* [set_db](#method-set_db)
* [hasTableWithSamePrefix](#method-hasTableWithSamePrefix)
* [tryToConnect](#method-tryToConnect)
* [getBestEngine](#method-getBestEngine)
* [checkCreatePrivilege](#method-checkCreatePrivilege)
* [tryUTF8](#method-tryUTF8)
* [checkAutoIncrement](#method-checkAutoIncrement)




Properties
----------


### <a name="property-$link"></a>$link

    protected \mysqli $link





* Visibility: **protected**
* This property is defined in [classes/db/DbMySQLi.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L35)


### <a name="property-$result"></a>$result

    protected mixed $result





* Visibility: **protected**
* This property is defined in [classes/db/DbMySQLi.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L38)


Methods
-------


### <a name="method-connect"></a>connect

    \mysqli DbMySQLiCore::connect()

Tries to connect to the database



* Visibility: **public**
* This method is defined in [classes/db/DbMySQLi.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L47)




### <a name="method-createDatabase"></a>createDatabase

    boolean|\mysqli_result DbMySQLiCore::createDatabase(string $host, string|null $user, string|null $password, string|null $database, boolean $dropit)

Tries to connect and create a new database



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/DbMySQLi.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L79)


#### Arguments
* $host **string**
* $user **string|null**
* $password **string|null**
* $database **string|null**
* $dropit **boolean** - &lt;p&gt;If true, drops the created database.&lt;/p&gt;



### <a name="method-disconnect"></a>disconnect

    mixed DbMySQLiCore::disconnect()

Destroys the database connection link



* Visibility: **public**
* This method is defined in [classes/db/DbMySQLi.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L99)




### <a name="method-_query"></a>_query

    boolean|\mysqli_result DbMySQLiCore::_query(string $sql)

Executes an SQL statement, returning a result set as a mysqli_result object or true/false.



* Visibility: **protected**
* This method is defined in [classes/db/DbMySQLi.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L111)


#### Arguments
* $sql **string**



### <a name="method-nextRow"></a>nextRow

    array|boolean DbMySQLiCore::nextRow(boolean|\mysqli_result $result)

Returns the next row from the result set.



* Visibility: **public**
* This method is defined in [classes/db/DbMySQLi.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L123)


#### Arguments
* $result **boolean|mysqli_result**



### <a name="method-getAll"></a>getAll

    array|false DbMySQLiCore::getAll(boolean|\mysqli_result $result)

Returns all rows from the result set.



* Visibility: **protected**
* This method is defined in [classes/db/DbMySQLi.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L143)


#### Arguments
* $result **boolean|mysqli_result**



### <a name="method-_numRows"></a>_numRows

    integer DbMySQLiCore::_numRows(boolean|\mysqli_result $result)

Returns row count from the result set.



* Visibility: **protected**
* This method is defined in [classes/db/DbMySQLi.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L173)


#### Arguments
* $result **boolean|mysqli_result**



### <a name="method-Insert_ID"></a>Insert_ID

    string|integer DbMySQLiCore::Insert_ID()

Returns ID of the last inserted row.



* Visibility: **public**
* This method is defined in [classes/db/DbMySQLi.php line 184](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L184)




### <a name="method-Affected_Rows"></a>Affected_Rows

    integer DbMySQLiCore::Affected_Rows()

Return the number of rows affected by the last SQL query.



* Visibility: **public**
* This method is defined in [classes/db/DbMySQLi.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L195)




### <a name="method-getMsgError"></a>getMsgError

    string DbMySQLiCore::getMsgError(boolean $query)

Returns error message.



* Visibility: **public**
* This method is defined in [classes/db/DbMySQLi.php line 207](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L207)


#### Arguments
* $query **boolean**



### <a name="method-getNumberError"></a>getNumberError

    integer DbMySQLiCore::getNumberError()

Returns error code.



* Visibility: **public**
* This method is defined in [classes/db/DbMySQLi.php line 218](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L218)




### <a name="method-getVersion"></a>getVersion

    string DbMySQLiCore::getVersion()

Returns database server version.



* Visibility: **public**
* This method is defined in [classes/db/DbMySQLi.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L229)




### <a name="method-_escape"></a>_escape

    string DbMySQLiCore::_escape(string $str)

Escapes illegal characters in a string.



* Visibility: **public**
* This method is defined in [classes/db/DbMySQLi.php line 241](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L241)


#### Arguments
* $str **string**



### <a name="method-set_db"></a>set_db

    boolean DbMySQLiCore::set_db(string $db_name)

Switches to a different database.



* Visibility: **public**
* This method is defined in [classes/db/DbMySQLi.php line 253](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L253)


#### Arguments
* $db_name **string**



### <a name="method-hasTableWithSamePrefix"></a>hasTableWithSamePrefix

    boolean DbMySQLiCore::hasTableWithSamePrefix(string $server, string $user, string $pwd, string $db, string $prefix)

Try a connection to the database and check if at least one table with same prefix exists



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/DbMySQLi.php line 269](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L269)


#### Arguments
* $server **string** - &lt;p&gt;Server address&lt;/p&gt;
* $user **string** - &lt;p&gt;Login for database connection&lt;/p&gt;
* $pwd **string** - &lt;p&gt;Password for database connection&lt;/p&gt;
* $db **string** - &lt;p&gt;Database name&lt;/p&gt;
* $prefix **string** - &lt;p&gt;Tables prefix&lt;/p&gt;



### <a name="method-tryToConnect"></a>tryToConnect

    integer DbMySQLiCore::tryToConnect(string $server, string $user, string $pwd, string $db, $new_db_link, string|boolean $engine, integer $timeout)

Try a connection to the database



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/DbMySQLi.php line 294](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L294)


#### Arguments
* $server **string** - &lt;p&gt;Server address&lt;/p&gt;
* $user **string** - &lt;p&gt;Login for database connection&lt;/p&gt;
* $pwd **string** - &lt;p&gt;Password for database connection&lt;/p&gt;
* $db **string** - &lt;p&gt;Database name&lt;/p&gt;
* $new_db_link **mixed**
* $engine **string|boolean**
* $timeout **integer**



### <a name="method-getBestEngine"></a>getBestEngine

    string DbMySQLiCore::getBestEngine()

Selects best table engine.



* Visibility: **public**
* This method is defined in [classes/db/DbMySQLi.php line 319](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L319)




### <a name="method-checkCreatePrivilege"></a>checkCreatePrivilege

    boolean|string DbMySQLiCore::checkCreatePrivilege(string $server, string $user, string $pwd, string $db, string $prefix, string|null $engine)

Tries to connect to the database and create a table (checking creation privileges)



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/DbMySQLi.php line 359](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L359)


#### Arguments
* $server **string**
* $user **string**
* $pwd **string**
* $db **string**
* $prefix **string**
* $engine **string|null** - &lt;p&gt;Table engine&lt;/p&gt;



### <a name="method-tryUTF8"></a>tryUTF8

    boolean DbMySQLiCore::tryUTF8(string $server, string $user, string $pwd)

Try a connection to the database and set names to UTF-8



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/DbMySQLi.php line 392](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L392)


#### Arguments
* $server **string** - &lt;p&gt;Server address&lt;/p&gt;
* $user **string** - &lt;p&gt;Login for database connection&lt;/p&gt;
* $pwd **string** - &lt;p&gt;Password for database connection&lt;/p&gt;



### <a name="method-checkAutoIncrement"></a>checkAutoIncrement

    boolean DbMySQLiCore::checkAutoIncrement(string $server, string $user, string $pwd)

Checks if auto increment value and offset is 1



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/DbMySQLi.php line 408](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbMySQLi.php#L408)


#### Arguments
* $server **string**
* $user **string**
* $pwd **string**


