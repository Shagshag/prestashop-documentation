DbPDOCore
===============

Class DbPDOCore




* Class name: DbPDOCore
* Namespace: 
* Parent class: [Db](DbCore)

* This class is defined in [classes/db/DbPDO.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#32)





Properties
----------


### $link

    protected \PDO $link





* Visibility: **protected**
* This property is defined in [classes/db/DbPDO.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#35)


### $result

    protected mixed $result





* Visibility: **protected**
* This property is defined in [classes/db/DbPDO.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#38)


Methods
-------


### _getPDO

    \PDO DbPDOCore::_getPDO(string $host, string $user, string $password, string $dbname, integer $timeout)

Returns a new PDO object (database link)



* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/db/DbPDO.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#50)


#### Arguments
* $host **string**
* $user **string**
* $password **string**
* $dbname **string**
* $timeout **integer**



### createDatabase

    boolean|integer DbPDOCore::createDatabase(string $host, string $user, string $password, string $dbname, boolean $dropit)

Tries to connect and create a new database



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/DbPDO.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#77)


#### Arguments
* $host **string**
* $user **string**
* $password **string**
* $dbname **string**
* $dropit **boolean** - &lt;p&gt;If true, drops the created database.&lt;/p&gt;



### connect

    \PDO DbPDOCore::connect()

Tries to connect to the database



* Visibility: **public**
* This method is defined in [classes/db/DbPDO.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#97)




### disconnect

    mixed DbPDOCore::disconnect()

Destroys the database connection link



* Visibility: **public**
* This method is defined in [classes/db/DbPDO.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#118)




### _query

    \PDOStatement DbPDOCore::_query(string $sql)

Executes an SQL statement, returning a result set as a PDOStatement object or true/false.



* Visibility: **protected**
* This method is defined in [classes/db/DbPDO.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#130)


#### Arguments
* $sql **string**



### nextRow

    array|false|null DbPDOCore::nextRow(boolean $result)

Returns the next row from the result set.



* Visibility: **public**
* This method is defined in [classes/db/DbPDO.php line 142](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#142)


#### Arguments
* $result **boolean**



### getAll

    array|false|null DbPDOCore::getAll(boolean $result)

Returns all rows from the result set.



* Visibility: **protected**
* This method is defined in [classes/db/DbPDO.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#162)


#### Arguments
* $result **boolean**



### _numRows

    integer DbPDOCore::_numRows(\PDOStatement $result)

Returns row count from the result set.



* Visibility: **protected**
* This method is defined in [classes/db/DbPDO.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#182)


#### Arguments
* $result **PDOStatement**



### Insert_ID

    string|integer DbPDOCore::Insert_ID()

Returns ID of the last inserted row.



* Visibility: **public**
* This method is defined in [classes/db/DbPDO.php line 193](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#193)




### Affected_Rows

    integer DbPDOCore::Affected_Rows()

Return the number of rows affected by the last SQL query.



* Visibility: **public**
* This method is defined in [classes/db/DbPDO.php line 204](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#204)




### getMsgError

    string DbPDOCore::getMsgError(boolean $query)

Returns error message.



* Visibility: **public**
* This method is defined in [classes/db/DbPDO.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#216)


#### Arguments
* $query **boolean**



### getNumberError

    integer DbPDOCore::getNumberError()

Returns error code.



* Visibility: **public**
* This method is defined in [classes/db/DbPDO.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#228)




### getVersion

    string DbPDOCore::getVersion()

Returns database server version.



* Visibility: **public**
* This method is defined in [classes/db/DbPDO.php line 240](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#240)




### _escape

    string DbPDOCore::_escape(string $str)

Escapes illegal characters in a string.



* Visibility: **public**
* This method is defined in [classes/db/DbPDO.php line 252](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#252)


#### Arguments
* $str **string**



### set_db

    integer DbPDOCore::set_db(string $db_name)

Switches to a different database.



* Visibility: **public**
* This method is defined in [classes/db/DbPDO.php line 266](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#266)


#### Arguments
* $db_name **string**



### hasTableWithSamePrefix

    boolean DbPDOCore::hasTableWithSamePrefix(string $server, string $user, string $pwd, string $db, string $prefix)

Try a connection to the database and check if at least one table with same prefix exists



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/DbPDO.php line 282](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#282)


#### Arguments
* $server **string** - &lt;p&gt;Server address&lt;/p&gt;
* $user **string** - &lt;p&gt;Login for database connection&lt;/p&gt;
* $pwd **string** - &lt;p&gt;Password for database connection&lt;/p&gt;
* $db **string** - &lt;p&gt;Database name&lt;/p&gt;
* $prefix **string** - &lt;p&gt;Tables prefix&lt;/p&gt;



### checkCreatePrivilege

    boolean|string DbPDOCore::checkCreatePrivilege(string $server, string $user, string $pwd, string $db, string $prefix, string|null $engine)

Tries to connect to the database and create a table (checking creation privileges)



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/DbPDO.php line 306](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#306)


#### Arguments
* $server **string**
* $user **string**
* $pwd **string**
* $db **string**
* $prefix **string**
* $engine **string|null** - &lt;p&gt;Table engine&lt;/p&gt;



### tryToConnect

    integer DbPDOCore::tryToConnect(string $server, string $user, string $pwd, string $db, $new_db_link, string|boolean $engine, integer $timeout)

Try a connection to the database



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/DbPDO.php line 343](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#343)


#### Arguments
* $server **string** - &lt;p&gt;Server address&lt;/p&gt;
* $user **string** - &lt;p&gt;Login for database connection&lt;/p&gt;
* $pwd **string** - &lt;p&gt;Password for database connection&lt;/p&gt;
* $db **string** - &lt;p&gt;Database name&lt;/p&gt;
* $new_db_link **mixed**
* $engine **string|boolean**
* $timeout **integer**



### getBestEngine

    string DbPDOCore::getBestEngine()

Selects best table engine.



* Visibility: **public**
* This method is defined in [classes/db/DbPDO.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#360)




### tryUTF8

    boolean DbPDOCore::tryUTF8(string $server, string $user, string $pwd)

Try a connection to the database and set names to UTF-8



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/DbPDO.php line 398](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#398)


#### Arguments
* $server **string** - &lt;p&gt;Server address&lt;/p&gt;
* $user **string** - &lt;p&gt;Login for database connection&lt;/p&gt;
* $pwd **string** - &lt;p&gt;Password for database connection&lt;/p&gt;



### checkAutoIncrement

    boolean DbPDOCore::checkAutoIncrement(string $server, string $user, string $pwd)

Checks if auto increment value and offset is 1



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/DbPDO.php line 419](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbPDO.php#419)


#### Arguments
* $server **string**
* $user **string**
* $pwd **string**


