MySQLCore
===============

Class MySQLCore




* Class name: MySQLCore
* Parent class: [Db](DbCore)
* This class is defined in [classes/db/MySQL.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#L30)





Properties
----------


### $link

    protected resource $link





* Visibility: **protected**
* This property is defined in [classes/db/MySQL.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#33)


### $result

    protected mixed $result





* Visibility: **protected**
* This property is defined in [classes/db/MySQL.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#36)


Methods
-------


### connect

    resource MySQLCore::connect()

Tries to connect to the database



* Visibility: **public**
* This method is defined in [classes/db/MySQL.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#45)




### createDatabase

    boolean|resource MySQLCore::createDatabase(string $host, string $user, string $password, string $dbname, boolean $dropit)

Tries to connect and create a new database



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/MySQL.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#77)


#### Arguments
* $host **string**
* $user **string**
* $password **string**
* $dbname **string**
* $dropit **boolean** - &lt;p&gt;If true, drops the created database.&lt;/p&gt;



### disconnect

    mixed MySQLCore::disconnect()

Destroys the database connection link



* Visibility: **public**
* This method is defined in [classes/db/MySQL.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#93)




### _query

    resource MySQLCore::_query(string $sql)

Executes an SQL statement, returning a result set as a result resource object.



* Visibility: **protected**
* This method is defined in [classes/db/MySQL.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#105)


#### Arguments
* $sql **string**



### nextRow

    array|boolean MySQLCore::nextRow(boolean|resource $result)

Returns the next row from the result set.



* Visibility: **public**
* This method is defined in [classes/db/MySQL.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#117)


#### Arguments
* $result **boolean|resource**



### _numRows

    integer MySQLCore::_numRows(resource $result)

Returns the next row from the result set.



* Visibility: **protected**
* This method is defined in [classes/db/MySQL.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#136)


#### Arguments
* $result **resource**



### Insert_ID

    integer MySQLCore::Insert_ID()

Returns ID of the last inserted row.



* Visibility: **public**
* This method is defined in [classes/db/MySQL.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#147)




### Affected_Rows

    integer MySQLCore::Affected_Rows()

Return the number of rows affected by the last SQL query.



* Visibility: **public**
* This method is defined in [classes/db/MySQL.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#158)




### getMsgError

    string MySQLCore::getMsgError(boolean $query)

Returns error message.



* Visibility: **public**
* This method is defined in [classes/db/MySQL.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#170)


#### Arguments
* $query **boolean**



### getNumberError

    integer MySQLCore::getNumberError()

Returns error code.



* Visibility: **public**
* This method is defined in [classes/db/MySQL.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#181)




### getVersion

    string MySQLCore::getVersion()

Returns database server version.



* Visibility: **public**
* This method is defined in [classes/db/MySQL.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#192)




### _escape

    string MySQLCore::_escape(string $str)

Escapes illegal characters in a string.



* Visibility: **public**
* This method is defined in [classes/db/MySQL.php line 204](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#204)


#### Arguments
* $str **string**



### set_db

    boolean MySQLCore::set_db(string $db_name)

Switches to a different database.



* Visibility: **public**
* This method is defined in [classes/db/MySQL.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#216)


#### Arguments
* $db_name **string**



### getAll

    array MySQLCore::getAll(boolean|resource $result)

Returns all rows from the result set.



* Visibility: **protected**
* This method is defined in [classes/db/MySQL.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#228)


#### Arguments
* $result **boolean|resource**



### hasTableWithSamePrefix

    boolean MySQLCore::hasTableWithSamePrefix(string $server, string $user, string $pwd, string $db, string $prefix)

Try a connection to the database and check if at least one table with same prefix exists



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/MySQL.php line 253](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#253)


#### Arguments
* $server **string** - &lt;p&gt;Server address&lt;/p&gt;
* $user **string** - &lt;p&gt;Login for database connection&lt;/p&gt;
* $pwd **string** - &lt;p&gt;Password for database connection&lt;/p&gt;
* $db **string** - &lt;p&gt;Database name&lt;/p&gt;
* $prefix **string** - &lt;p&gt;Tables prefix&lt;/p&gt;



### tryToConnect

    integer MySQLCore::tryToConnect(string $server, string $user, string $pwd, string $db, $new_db_link, string|null $engine, integer $timeout)

Try a connection to the database



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/MySQL.php line 280](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#280)


#### Arguments
* $server **string** - &lt;p&gt;Server address&lt;/p&gt;
* $user **string** - &lt;p&gt;Login for database connection&lt;/p&gt;
* $pwd **string** - &lt;p&gt;Password for database connection&lt;/p&gt;
* $db **string** - &lt;p&gt;Database name&lt;/p&gt;
* $new_db_link **mixed**
* $engine **string|null**
* $timeout **integer**



### getBestEngine

    string MySQLCore::getBestEngine()

Selects best table engine.



* Visibility: **public**
* This method is defined in [classes/db/MySQL.php line 299](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#299)




### checkCreatePrivilege

    boolean|string MySQLCore::checkCreatePrivilege(string $server, string $user, string $pwd, string $db, string $prefix, string|null $engine)

Tries to connect to the database and create a table (checking creation privileges)



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/MySQL.php line 339](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#339)


#### Arguments
* $server **string**
* $user **string**
* $pwd **string**
* $db **string**
* $prefix **string**
* $engine **string|null** - &lt;p&gt;Table engine&lt;/p&gt;



### tryUTF8

    boolean MySQLCore::tryUTF8(string $server, string $user, string $pwd)

Try a connection to the database and set names to UTF-8



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/MySQL.php line 375](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#375)


#### Arguments
* $server **string** - &lt;p&gt;Server address&lt;/p&gt;
* $user **string** - &lt;p&gt;Login for database connection&lt;/p&gt;
* $pwd **string** - &lt;p&gt;Password for database connection&lt;/p&gt;



### checkAutoIncrement

    boolean MySQLCore::checkAutoIncrement(string $server, string $user, string $pwd)

Checks if auto increment value and offset is 1



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/MySQL.php line 391](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/MySQL.php#391)


#### Arguments
* $server **string**
* $user **string**
* $pwd **string**


