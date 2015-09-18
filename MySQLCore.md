MySQLCore
===============

Class MySQLCore




* Class name: MySQLCore
* Namespace: 
* Parent class: Db





Properties
----------


### $link

    protected resource $link





* Visibility: **protected**


### $result

    protected mixed $result





* Visibility: **protected**


Methods
-------


### connect

    resource MySQLCore::connect()

Tries to connect to the database



* Visibility: **public**




### createDatabase

    boolean|resource MySQLCore::createDatabase(string $host, string $user, string $password, string $dbname, boolean $dropit)

Tries to connect and create a new database



* Visibility: **public**
* This method is **static**.


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




### _query

    resource MySQLCore::_query(string $sql)

Executes an SQL statement, returning a result set as a result resource object.



* Visibility: **protected**


#### Arguments
* $sql **string**



### nextRow

    array|boolean MySQLCore::nextRow(boolean|resource $result)

Returns the next row from the result set.



* Visibility: **public**


#### Arguments
* $result **boolean|resource**



### _numRows

    integer MySQLCore::_numRows(resource $result)

Returns the next row from the result set.



* Visibility: **protected**


#### Arguments
* $result **resource**



### Insert_ID

    integer MySQLCore::Insert_ID()

Returns ID of the last inserted row.



* Visibility: **public**




### Affected_Rows

    integer MySQLCore::Affected_Rows()

Return the number of rows affected by the last SQL query.



* Visibility: **public**




### getMsgError

    string MySQLCore::getMsgError(boolean $query)

Returns error message.



* Visibility: **public**


#### Arguments
* $query **boolean**



### getNumberError

    integer MySQLCore::getNumberError()

Returns error code.



* Visibility: **public**




### getVersion

    string MySQLCore::getVersion()

Returns database server version.



* Visibility: **public**




### _escape

    string MySQLCore::_escape(string $str)

Escapes illegal characters in a string.



* Visibility: **public**


#### Arguments
* $str **string**



### set_db

    boolean MySQLCore::set_db(string $db_name)

Switches to a different database.



* Visibility: **public**


#### Arguments
* $db_name **string**



### getAll

    array MySQLCore::getAll(boolean|resource $result)

Returns all rows from the result set.



* Visibility: **protected**


#### Arguments
* $result **boolean|resource**



### hasTableWithSamePrefix

    boolean MySQLCore::hasTableWithSamePrefix(string $server, string $user, string $pwd, string $db, string $prefix)

Try a connection to the database and check if at least one table with same prefix exists



* Visibility: **public**
* This method is **static**.


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




### checkCreatePrivilege

    boolean|string MySQLCore::checkCreatePrivilege(string $server, string $user, string $pwd, string $db, string $prefix, string|null $engine)

Tries to connect to the database and create a table (checking creation privileges)



* Visibility: **public**
* This method is **static**.


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


#### Arguments
* $server **string** - &lt;p&gt;Server address&lt;/p&gt;
* $user **string** - &lt;p&gt;Login for database connection&lt;/p&gt;
* $pwd **string** - &lt;p&gt;Password for database connection&lt;/p&gt;



### checkAutoIncrement

    boolean MySQLCore::checkAutoIncrement(string $server, string $user, string $pwd)

Checks if auto increment value and offset is 1



* Visibility: **public**
* This method is **static**.


#### Arguments
* $server **string**
* $user **string**
* $pwd **string**


