DbPDOCore
===============

Class DbPDOCore




* Class name: DbPDOCore
* Parent class: [Db](DbCore)
* This class is defined in [classes/db/DbPDO.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#L32)





Properties
----------

* [$link](#property-$link)
* [$result](#property-$result)

Methods
-------
* [_getPDO](#method-_getPDO)
* [createDatabase](#method-createDatabase)
* [connect](#method-connect)
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
* [checkCreatePrivilege](#method-checkCreatePrivilege)
* [tryToConnect](#method-tryToConnect)
* [getBestEngine](#method-getBestEngine)
* [tryUTF8](#method-tryUTF8)
* [checkAutoIncrement](#method-checkAutoIncrement)




Properties
----------


### <a name="property-$link"></a>$link

    protected \PDO $link





* Visibility: **protected**
* This property is defined in [classes/db/DbPDO.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#L35)


### <a name="property-$result"></a>$result

    protected mixed $result





* Visibility: **protected**
* This property is defined in [classes/db/DbPDO.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#L38)


Methods
-------


### <a name="method-_getPDO"></a>_getPDO

    \PDO DbPDOCore::_getPDO(string $host, string $user, string $password, string $dbname, integer $timeout)

Returns a new PDO object (database link)



* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/db/DbPDO.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#L50)


#### Arguments
* $host **string**
* $user **string**
* $password **string**
* $dbname **string**
* $timeout **integer**



### <a name="method-createDatabase"></a>createDatabase

    boolean|integer DbPDOCore::createDatabase(string $host, string $user, string $password, string $dbname, boolean $dropit)

Tries to connect and create a new database



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/DbPDO.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#L77)


#### Arguments
* $host **string**
* $user **string**
* $password **string**
* $dbname **string**
* $dropit **boolean** - &lt;p&gt;If true, drops the created database.&lt;/p&gt;



### <a name="method-connect"></a>connect

    \PDO DbPDOCore::connect()

Tries to connect to the database



* Visibility: **public**
* This method is defined in [classes/db/DbPDO.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#L97)




### <a name="method-disconnect"></a>disconnect

    mixed DbPDOCore::disconnect()

Destroys the database connection link



* Visibility: **public**
* This method is defined in [classes/db/DbPDO.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#L118)




### <a name="method-_query"></a>_query

    \PDOStatement DbPDOCore::_query(string $sql)

Executes an SQL statement, returning a result set as a PDOStatement object or true/false.



* Visibility: **protected**
* This method is defined in [classes/db/DbPDO.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#L130)


#### Arguments
* $sql **string**



### <a name="method-nextRow"></a>nextRow

    array|false|null DbPDOCore::nextRow(boolean $result)

Returns the next row from the result set.



* Visibility: **public**
* This method is defined in [classes/db/DbPDO.php line 142](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#L142)


#### Arguments
* $result **boolean**



### <a name="method-getAll"></a>getAll

    array|false|null DbPDOCore::getAll(boolean $result)

Returns all rows from the result set.



* Visibility: **protected**
* This method is defined in [classes/db/DbPDO.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#L162)


#### Arguments
* $result **boolean**



### <a name="method-_numRows"></a>_numRows

    integer DbPDOCore::_numRows(\PDOStatement $result)

Returns row count from the result set.



* Visibility: **protected**
* This method is defined in [classes/db/DbPDO.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#L182)


#### Arguments
* $result **PDOStatement**



### <a name="method-Insert_ID"></a>Insert_ID

    string|integer DbPDOCore::Insert_ID()

Returns ID of the last inserted row.



* Visibility: **public**
* This method is defined in [classes/db/DbPDO.php line 193](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#L193)




### <a name="method-Affected_Rows"></a>Affected_Rows

    integer DbPDOCore::Affected_Rows()

Return the number of rows affected by the last SQL query.



* Visibility: **public**
* This method is defined in [classes/db/DbPDO.php line 204](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#L204)




### <a name="method-getMsgError"></a>getMsgError

    string DbPDOCore::getMsgError(boolean $query)

Returns error message.



* Visibility: **public**
* This method is defined in [classes/db/DbPDO.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#L216)


#### Arguments
* $query **boolean**



### <a name="method-getNumberError"></a>getNumberError

    integer DbPDOCore::getNumberError()

Returns error code.



* Visibility: **public**
* This method is defined in [classes/db/DbPDO.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#L228)




### <a name="method-getVersion"></a>getVersion

    string DbPDOCore::getVersion()

Returns database server version.



* Visibility: **public**
* This method is defined in [classes/db/DbPDO.php line 240](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#L240)




### <a name="method-_escape"></a>_escape

    string DbPDOCore::_escape(string $str)

Escapes illegal characters in a string.



* Visibility: **public**
* This method is defined in [classes/db/DbPDO.php line 252](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#L252)


#### Arguments
* $str **string**



### <a name="method-set_db"></a>set_db

    integer DbPDOCore::set_db(string $db_name)

Switches to a different database.



* Visibility: **public**
* This method is defined in [classes/db/DbPDO.php line 266](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#L266)


#### Arguments
* $db_name **string**



### <a name="method-hasTableWithSamePrefix"></a>hasTableWithSamePrefix

    boolean DbPDOCore::hasTableWithSamePrefix(string $server, string $user, string $pwd, string $db, string $prefix)

Try a connection to the database and check if at least one table with same prefix exists



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/DbPDO.php line 282](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#L282)


#### Arguments
* $server **string** - &lt;p&gt;Server address&lt;/p&gt;
* $user **string** - &lt;p&gt;Login for database connection&lt;/p&gt;
* $pwd **string** - &lt;p&gt;Password for database connection&lt;/p&gt;
* $db **string** - &lt;p&gt;Database name&lt;/p&gt;
* $prefix **string** - &lt;p&gt;Tables prefix&lt;/p&gt;



### <a name="method-checkCreatePrivilege"></a>checkCreatePrivilege

    boolean|string DbPDOCore::checkCreatePrivilege(string $server, string $user, string $pwd, string $db, string $prefix, string|null $engine)

Tries to connect to the database and create a table (checking creation privileges)



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/DbPDO.php line 306](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#L306)


#### Arguments
* $server **string**
* $user **string**
* $pwd **string**
* $db **string**
* $prefix **string**
* $engine **string|null** - &lt;p&gt;Table engine&lt;/p&gt;



### <a name="method-tryToConnect"></a>tryToConnect

    integer DbPDOCore::tryToConnect(string $server, string $user, string $pwd, string $db, $new_db_link, string|boolean $engine, integer $timeout)

Try a connection to the database



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/DbPDO.php line 343](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#L343)


#### Arguments
* $server **string** - &lt;p&gt;Server address&lt;/p&gt;
* $user **string** - &lt;p&gt;Login for database connection&lt;/p&gt;
* $pwd **string** - &lt;p&gt;Password for database connection&lt;/p&gt;
* $db **string** - &lt;p&gt;Database name&lt;/p&gt;
* $new_db_link **mixed**
* $engine **string|boolean**
* $timeout **integer**



### <a name="method-getBestEngine"></a>getBestEngine

    string DbPDOCore::getBestEngine()

Selects best table engine.



* Visibility: **public**
* This method is defined in [classes/db/DbPDO.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#L360)




### <a name="method-tryUTF8"></a>tryUTF8

    boolean DbPDOCore::tryUTF8(string $server, string $user, string $pwd)

Try a connection to the database and set names to UTF-8



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/DbPDO.php line 398](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#L398)


#### Arguments
* $server **string** - &lt;p&gt;Server address&lt;/p&gt;
* $user **string** - &lt;p&gt;Login for database connection&lt;/p&gt;
* $pwd **string** - &lt;p&gt;Password for database connection&lt;/p&gt;



### <a name="method-checkAutoIncrement"></a>checkAutoIncrement

    boolean DbPDOCore::checkAutoIncrement(string $server, string $user, string $pwd)

Checks if auto increment value and offset is 1



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/DbPDO.php line 419](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#L419)


#### Arguments
* $server **string**
* $user **string**
* $pwd **string**


