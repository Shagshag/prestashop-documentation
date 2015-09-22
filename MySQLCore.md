MySQLCore
===============

Class MySQLCore




* Class name: MySQLCore
* Parent class: [Db](DbCore)
* This class is defined in [classes/db/MySQL.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#L30)





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
* [_numRows](#method-_numRows)
* [Insert_ID](#method-Insert_ID)
* [Affected_Rows](#method-Affected_Rows)
* [getMsgError](#method-getMsgError)
* [getNumberError](#method-getNumberError)
* [getVersion](#method-getVersion)
* [_escape](#method-_escape)
* [set_db](#method-set_db)
* [getAll](#method-getAll)
* [hasTableWithSamePrefix](#method-hasTableWithSamePrefix)
* [tryToConnect](#method-tryToConnect)
* [getBestEngine](#method-getBestEngine)
* [checkCreatePrivilege](#method-checkCreatePrivilege)
* [tryUTF8](#method-tryUTF8)
* [checkAutoIncrement](#method-checkAutoIncrement)




Properties
----------


### <a name="property-$link"></a>$link

    protected resource $link





* Visibility: **protected**
* This property is defined in [classes/db/MySQL.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#L33)


### <a name="property-$result"></a>$result

    protected mixed $result





* Visibility: **protected**
* This property is defined in [classes/db/MySQL.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#L36)


Methods
-------


### <a name="method-connect"></a>connect

    resource MySQLCore::connect()

Tries to connect to the database



* Visibility: **public**
* This method is defined in [classes/db/MySQL.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#L45)




### <a name="method-createDatabase"></a>createDatabase

    boolean|resource MySQLCore::createDatabase(string $host, string $user, string $password, string $dbname, boolean $dropit)

Tries to connect and create a new database



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/MySQL.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#L77)


#### Arguments
* $host **string**
* $user **string**
* $password **string**
* $dbname **string**
* $dropit **boolean** - &lt;p&gt;If true, drops the created database.&lt;/p&gt;



### <a name="method-disconnect"></a>disconnect

    mixed MySQLCore::disconnect()

Destroys the database connection link



* Visibility: **public**
* This method is defined in [classes/db/MySQL.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#L93)




### <a name="method-_query"></a>_query

    resource MySQLCore::_query(string $sql)

Executes an SQL statement, returning a result set as a result resource object.



* Visibility: **protected**
* This method is defined in [classes/db/MySQL.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#L105)


#### Arguments
* $sql **string**



### <a name="method-nextRow"></a>nextRow

    array|boolean MySQLCore::nextRow(boolean|resource $result)

Returns the next row from the result set.



* Visibility: **public**
* This method is defined in [classes/db/MySQL.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#L117)


#### Arguments
* $result **boolean|resource**



### <a name="method-_numRows"></a>_numRows

    integer MySQLCore::_numRows(resource $result)

Returns the next row from the result set.



* Visibility: **protected**
* This method is defined in [classes/db/MySQL.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#L136)


#### Arguments
* $result **resource**



### <a name="method-Insert_ID"></a>Insert_ID

    integer MySQLCore::Insert_ID()

Returns ID of the last inserted row.



* Visibility: **public**
* This method is defined in [classes/db/MySQL.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#L147)




### <a name="method-Affected_Rows"></a>Affected_Rows

    integer MySQLCore::Affected_Rows()

Return the number of rows affected by the last SQL query.



* Visibility: **public**
* This method is defined in [classes/db/MySQL.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#L158)




### <a name="method-getMsgError"></a>getMsgError

    string MySQLCore::getMsgError(boolean $query)

Returns error message.



* Visibility: **public**
* This method is defined in [classes/db/MySQL.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#L170)


#### Arguments
* $query **boolean**



### <a name="method-getNumberError"></a>getNumberError

    integer MySQLCore::getNumberError()

Returns error code.



* Visibility: **public**
* This method is defined in [classes/db/MySQL.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#L181)




### <a name="method-getVersion"></a>getVersion

    string MySQLCore::getVersion()

Returns database server version.



* Visibility: **public**
* This method is defined in [classes/db/MySQL.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#L192)




### <a name="method-_escape"></a>_escape

    string MySQLCore::_escape(string $str)

Escapes illegal characters in a string.



* Visibility: **public**
* This method is defined in [classes/db/MySQL.php line 204](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#L204)


#### Arguments
* $str **string**



### <a name="method-set_db"></a>set_db

    boolean MySQLCore::set_db(string $db_name)

Switches to a different database.



* Visibility: **public**
* This method is defined in [classes/db/MySQL.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#L216)


#### Arguments
* $db_name **string**



### <a name="method-getAll"></a>getAll

    array MySQLCore::getAll(boolean|resource $result)

Returns all rows from the result set.



* Visibility: **protected**
* This method is defined in [classes/db/MySQL.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#L228)


#### Arguments
* $result **boolean|resource**



### <a name="method-hasTableWithSamePrefix"></a>hasTableWithSamePrefix

    boolean MySQLCore::hasTableWithSamePrefix(string $server, string $user, string $pwd, string $db, string $prefix)

Try a connection to the database and check if at least one table with same prefix exists



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/MySQL.php line 253](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#L253)


#### Arguments
* $server **string** - &lt;p&gt;Server address&lt;/p&gt;
* $user **string** - &lt;p&gt;Login for database connection&lt;/p&gt;
* $pwd **string** - &lt;p&gt;Password for database connection&lt;/p&gt;
* $db **string** - &lt;p&gt;Database name&lt;/p&gt;
* $prefix **string** - &lt;p&gt;Tables prefix&lt;/p&gt;



### <a name="method-tryToConnect"></a>tryToConnect

    integer MySQLCore::tryToConnect(string $server, string $user, string $pwd, string $db, $new_db_link, string|null $engine, integer $timeout)

Try a connection to the database



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/MySQL.php line 280](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#L280)


#### Arguments
* $server **string** - &lt;p&gt;Server address&lt;/p&gt;
* $user **string** - &lt;p&gt;Login for database connection&lt;/p&gt;
* $pwd **string** - &lt;p&gt;Password for database connection&lt;/p&gt;
* $db **string** - &lt;p&gt;Database name&lt;/p&gt;
* $new_db_link **mixed**
* $engine **string|null**
* $timeout **integer**



### <a name="method-getBestEngine"></a>getBestEngine

    string MySQLCore::getBestEngine()

Selects best table engine.



* Visibility: **public**
* This method is defined in [classes/db/MySQL.php line 299](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#L299)




### <a name="method-checkCreatePrivilege"></a>checkCreatePrivilege

    boolean|string MySQLCore::checkCreatePrivilege(string $server, string $user, string $pwd, string $db, string $prefix, string|null $engine)

Tries to connect to the database and create a table (checking creation privileges)



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/MySQL.php line 339](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#L339)


#### Arguments
* $server **string**
* $user **string**
* $pwd **string**
* $db **string**
* $prefix **string**
* $engine **string|null** - &lt;p&gt;Table engine&lt;/p&gt;



### <a name="method-tryUTF8"></a>tryUTF8

    boolean MySQLCore::tryUTF8(string $server, string $user, string $pwd)

Try a connection to the database and set names to UTF-8



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/MySQL.php line 375](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#L375)


#### Arguments
* $server **string** - &lt;p&gt;Server address&lt;/p&gt;
* $user **string** - &lt;p&gt;Login for database connection&lt;/p&gt;
* $pwd **string** - &lt;p&gt;Password for database connection&lt;/p&gt;



### <a name="method-checkAutoIncrement"></a>checkAutoIncrement

    boolean MySQLCore::checkAutoIncrement(string $server, string $user, string $pwd)

Checks if auto increment value and offset is 1



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/MySQL.php line 391](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#L391)


#### Arguments
* $server **string**
* $user **string**
* $pwd **string**


