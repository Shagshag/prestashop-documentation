DbCore
===============

Class DbCore




* Class name: DbCore
* Namespace: 
* This is an **abstract** class

* This class is defined in [classes/db/Db.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#34)



Constants
----------


### INSERT

    const INSERT = 1



* This constant is defined in [classes/db/Db.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#37)


### INSERT_IGNORE

    const INSERT_IGNORE = 2



* This constant is defined in [classes/db/Db.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#40)


### REPLACE

    const REPLACE = 3



* This constant is defined in [classes/db/Db.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#43)


### ON_DUPLICATE_KEY

    const ON_DUPLICATE_KEY = 4



* This constant is defined in [classes/db/Db.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#46)


Properties
----------


### $server

    protected string $server





* Visibility: **protected**
* This property is defined in [classes/db/Db.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#49)


### $user

    protected string $user





* Visibility: **protected**
* This property is defined in [classes/db/Db.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#52)


### $password

    protected string $password





* Visibility: **protected**
* This property is defined in [classes/db/Db.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#55)


### $database

    protected string $database





* Visibility: **protected**
* This property is defined in [classes/db/Db.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#58)


### $is_cache_enabled

    protected boolean $is_cache_enabled





* Visibility: **protected**
* This property is defined in [classes/db/Db.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#61)


### $link

    protected \PDO $link





* Visibility: **protected**
* This property is defined in [classes/db/Db.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#64)


### $result

    protected \PDOStatement $result





* Visibility: **protected**
* This property is defined in [classes/db/Db.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#67)


### $instance

    public array $instance = array()





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/db/Db.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#70)


### $_servers

    public array $_servers = array()





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/db/Db.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#73)


### $_slave_servers_loaded

    public null $_slave_servers_loaded = null





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/db/Db.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#78)


### $last_query

    protected string $last_query

Store last executed query



* Visibility: **protected**
* This property is defined in [classes/db/Db.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#85)


### $last_query_hash

    protected string $last_query_hash

Store hash of the last executed query



* Visibility: **protected**
* This property is defined in [classes/db/Db.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#92)


### $last_cached

    protected string $last_cached

Last cached query



* Visibility: **protected**
* This property is defined in [classes/db/Db.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#99)


Methods
-------


### connect

    \PDO|\mysqli|resource DbCore::connect()

Opens a database connection



* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/db/Db.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#106)




### disconnect

    mixed DbCore::disconnect()

Closes database connection



* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/db/Db.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#111)




### _query

    \PDOStatement|\mysqli_result|resource|boolean DbCore::_query(string $sql)

Execute a query and get result resource



* Visibility: **protected**
* This method is **abstract**.
* This method is defined in [classes/db/Db.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#119)


#### Arguments
* $sql **string**



### _numRows

    integer DbCore::_numRows(mixed $result)

Get number of rows in a result



* Visibility: **protected**
* This method is **abstract**.
* This method is defined in [classes/db/Db.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#127)


#### Arguments
* $result **mixed**



### Insert_ID

    integer|string DbCore::Insert_ID()

Get the ID generated from the previous INSERT operation



* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/db/Db.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#134)




### Affected_Rows

    integer DbCore::Affected_Rows()

Get number of affected rows in previous database operation



* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/db/Db.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#141)




### nextRow

    array|object|false|null DbCore::nextRow(\PDOStatement|\mysqli_result|resource|boolean $result)

Get next row for a query which does not return an array



* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/db/Db.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#149)


#### Arguments
* $result **PDOStatement|mysqli_result|resource|boolean**



### getAll

    array DbCore::getAll(\PDOStatement|\mysqli_result|resource|boolean|null $result)

Get all rows for a query which return an array



* Visibility: **protected**
* This method is **abstract**.
* This method is defined in [classes/db/Db.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#157)


#### Arguments
* $result **PDOStatement|mysqli_result|resource|boolean|null**



### getVersion

    string DbCore::getVersion()

Get database version



* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/db/Db.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#164)




### _escape

    string DbCore::_escape(string $str)

Protect string against SQL injections



* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/db/Db.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#172)


#### Arguments
* $str **string**



### getMsgError

    string DbCore::getMsgError()

Returns the text of the error message from previous database operation



* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/db/Db.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#179)




### getNumberError

    integer DbCore::getNumberError()

Returns the number of the error from previous database operation



* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/db/Db.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#186)




### set_db

    boolean|integer DbCore::set_db(string $db_name)

Sets the current active database on the server that's associated with the specified link identifier.

Do not remove, useful for some modules.

* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/db/Db.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#195)


#### Arguments
* $db_name **string**



### getBestEngine

    string DbCore::getBestEngine()

Selects best table engine.



* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/db/Db.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#202)




### getInstance

    \Db DbCore::getInstance(boolean $master)

Returns database object instance.



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/Db.php line 210](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#210)


#### Arguments
* $master **boolean** - &lt;p&gt;Decides whether the connection to be returned by the master server or the slave server&lt;/p&gt;



### setInstanceForTesting

    mixed DbCore::setInstanceForTesting($test_db)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/Db.php line 250](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#250)


#### Arguments
* $test_db **mixed** - &lt;p&gt;Db
Unit testing purpose only&lt;/p&gt;



### deleteTestingInstance

    mixed DbCore::deleteTestingInstance()

Unit testing purpose only



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/Db.php line 258](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#258)




### loadSlaveServers

    mixed DbCore::loadSlaveServers()

Loads configuration settings for slave servers if needed.



* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/db/Db.php line 266](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#266)




### getClass

    string DbCore::getClass()

Returns the best child layer database class.



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/Db.php line 285](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#285)




### __construct

    mixed DbCore::__construct(string $server, string $user, string $password, string $database, boolean $connect)

Instantiates a database connection



* Visibility: **public**
* This method is defined in [classes/db/Db.php line 306](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#306)


#### Arguments
* $server **string** - &lt;p&gt;Server address&lt;/p&gt;
* $user **string** - &lt;p&gt;User login&lt;/p&gt;
* $password **string** - &lt;p&gt;User password&lt;/p&gt;
* $database **string** - &lt;p&gt;Database name&lt;/p&gt;
* $connect **boolean** - &lt;p&gt;If false, don&#039;t connect in constructor (since 1.5.0.1)&lt;/p&gt;



### disableCache

    mixed DbCore::disableCache()

Disable the use of the cache



* Visibility: **public**
* This method is defined in [classes/db/Db.php line 327](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#327)




### enableCache

    mixed DbCore::enableCache()

Enable & flush the cache



* Visibility: **public**
* This method is defined in [classes/db/Db.php line 336](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#336)




### __destruct

    mixed DbCore::__destruct()

Closes connection to database



* Visibility: **public**
* This method is defined in [classes/db/Db.php line 345](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#345)




### autoExecute

    boolean DbCore::autoExecute(string $table, array $data, string $type, string $where, integer $limit, boolean $use_cache, boolean $use_null)

Executes SQL query based on selected type



* Visibility: **public**
* This method is defined in [classes/db/Db.php line 366](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#366)


#### Arguments
* $table **string**
* $data **array**
* $type **string** - &lt;p&gt;(INSERT, INSERT IGNORE, REPLACE, UPDATE).&lt;/p&gt;
* $where **string**
* $limit **integer**
* $use_cache **boolean**
* $use_null **boolean**



### autoExecuteWithNullValues

    boolean DbCore::autoExecuteWithNullValues(string $table, array $values, string $type, string $where, integer $limit)

Filter SQL query within a blacklist



* Visibility: **public**
* This method is defined in [classes/db/Db.php line 398](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#398)


#### Arguments
* $table **string** - &lt;p&gt;Table where insert/update data&lt;/p&gt;
* $values **array** - &lt;p&gt;Data to insert/update&lt;/p&gt;
* $type **string** - &lt;p&gt;INSERT or UPDATE&lt;/p&gt;
* $where **string** - &lt;p&gt;WHERE clause, only for UPDATE (optional)&lt;/p&gt;
* $limit **integer** - &lt;p&gt;LIMIT clause (optional)&lt;/p&gt;



### query

    boolean|\mysqli_result|\PDOStatement|resource DbCore::query(string|\DbQuery $sql)

Execute a query and get result resource



* Visibility: **public**
* This method is defined in [classes/db/Db.php line 410](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#410)


#### Arguments
* $sql **string|[string](DbQueryCore)**



### insert

    boolean DbCore::insert(string $table, array $data, boolean $null_values, boolean $use_cache, integer $type, boolean $add_prefix)

Executes an INSERT query



* Visibility: **public**
* This method is defined in [classes/db/Db.php line 443](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#443)


#### Arguments
* $table **string** - &lt;p&gt;Table name without prefix&lt;/p&gt;
* $data **array** - &lt;p&gt;Data to insert as associative array. If $data is a list of arrays, multiple insert will be done&lt;/p&gt;
* $null_values **boolean** - &lt;p&gt;If we want to use NULL values instead of empty quotes&lt;/p&gt;
* $use_cache **boolean**
* $type **integer** - &lt;p&gt;Must be Db::INSERT or Db::INSERT_IGNORE or Db::REPLACE&lt;/p&gt;
* $add_prefix **boolean** - &lt;p&gt;Add or not _DB_PREFIX_ before table name&lt;/p&gt;



### update

    boolean DbCore::update(string $table, array $data, string $where, integer $limit, boolean $null_values, boolean $use_cache, boolean $add_prefix)

Executes an UPDATE query



* Visibility: **public**
* This method is defined in [classes/db/Db.php line 529](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#529)


#### Arguments
* $table **string** - &lt;p&gt;Table name without prefix&lt;/p&gt;
* $data **array** - &lt;p&gt;Data to insert as associative array. If $data is a list of arrays, multiple insert will be done&lt;/p&gt;
* $where **string** - &lt;p&gt;WHERE condition&lt;/p&gt;
* $limit **integer**
* $null_values **boolean** - &lt;p&gt;If we want to use NULL values instead of empty quotes&lt;/p&gt;
* $use_cache **boolean**
* $add_prefix **boolean** - &lt;p&gt;Add or not _DB_PREFIX_ before table name&lt;/p&gt;



### delete

    boolean DbCore::delete(string $table, string $where, integer $limit, boolean $use_cache, boolean $add_prefix)

Executes a DELETE query



* Visibility: **public**
* This method is defined in [classes/db/Db.php line 572](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#572)


#### Arguments
* $table **string** - &lt;p&gt;Name of the table to delete&lt;/p&gt;
* $where **string** - &lt;p&gt;WHERE clause on query&lt;/p&gt;
* $limit **integer** - &lt;p&gt;Number max of rows to delete&lt;/p&gt;
* $use_cache **boolean** - &lt;p&gt;Use cache or not&lt;/p&gt;
* $add_prefix **boolean** - &lt;p&gt;Add or not _DB_PREFIX_ before table name&lt;/p&gt;



### execute

    boolean DbCore::execute(string|\DbQuery $sql, boolean $use_cache)

Executes a query



* Visibility: **public**
* This method is defined in [classes/db/Db.php line 595](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#595)


#### Arguments
* $sql **string|[string](DbQueryCore)**
* $use_cache **boolean**



### executeS

    array|false|null|\mysqli_result|\PDOStatement|resource DbCore::executeS(string|\DbQuery $sql, boolean $array, boolean $use_cache)

Executes return the result of $sql as array



* Visibility: **public**
* This method is defined in [classes/db/Db.php line 618](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#618)


#### Arguments
* $sql **string|[string](DbQueryCore)** - &lt;p&gt;Query to execute&lt;/p&gt;
* $array **boolean** - &lt;p&gt;Return an array instead of a result object (deprecated since 1.5.0.1, use query method instead)&lt;/p&gt;
* $use_cache **boolean**



### getRow

    array|boolean|object|null DbCore::getRow(string|\DbQuery $sql, boolean $use_cache)

Returns an associative array containing the first row of the query
This function automatically adds "LIMIT 1" to the query



* Visibility: **public**
* This method is defined in [classes/db/Db.php line 672](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#672)


#### Arguments
* $sql **string|[string](DbQueryCore)** - &lt;p&gt;the select query (without &quot;LIMIT 1&quot;)&lt;/p&gt;
* $use_cache **boolean** - &lt;p&gt;Find it in cache first&lt;/p&gt;



### getValue

    string|false|null DbCore::getValue(string|\DbQuery $sql, boolean $use_cache)

Returns a value from the first row, first column of a SELECT query



* Visibility: **public**
* This method is defined in [classes/db/Db.php line 717](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#717)


#### Arguments
* $sql **string|[string](DbQueryCore)**
* $use_cache **boolean**



### numRows

    integer DbCore::numRows()

Get number of rows for last result



* Visibility: **public**
* This method is defined in [classes/db/Db.php line 735](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#735)




### q

    boolean|\mysqli_result|\PDOStatement|resource DbCore::q(string|\DbQuery $sql, boolean $use_cache)

Executes a query



* Visibility: **protected**
* This method is defined in [classes/db/Db.php line 756](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#756)


#### Arguments
* $sql **string|[string](DbQueryCore)**
* $use_cache **boolean**



### displayError

    mixed DbCore::displayError(string|boolean $sql)

Displays last SQL error



* Visibility: **public**
* This method is defined in [classes/db/Db.php line 781](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#781)


#### Arguments
* $sql **string|boolean**



### escape

    string DbCore::escape(string $string, boolean $html_ok, $bq_sql)

Sanitize data which will be injected into SQL query



* Visibility: **public**
* This method is defined in [classes/db/Db.php line 805](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#805)


#### Arguments
* $string **string** - &lt;p&gt;SQL data which will be injected into SQL query&lt;/p&gt;
* $html_ok **boolean** - &lt;p&gt;Does data contain HTML code ? (optional)&lt;/p&gt;
* $bq_sql **mixed**



### checkConnection

    integer DbCore::checkConnection(string $server, string $user, string $pwd, string $db, boolean $new_db_link, string|boolean $engine, integer $timeout)

Try a connection to the database



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/Db.php line 838](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#838)


#### Arguments
* $server **string** - &lt;p&gt;Server address&lt;/p&gt;
* $user **string** - &lt;p&gt;Login for database connection&lt;/p&gt;
* $pwd **string** - &lt;p&gt;Password for database connection&lt;/p&gt;
* $db **string** - &lt;p&gt;Database name&lt;/p&gt;
* $new_db_link **boolean**
* $engine **string|boolean**
* $timeout **integer**



### checkEncoding

    boolean DbCore::checkEncoding(string $server, string $user, string $pwd)

Try a connection to the database and set names to UTF-8



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/Db.php line 851](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#851)


#### Arguments
* $server **string** - &lt;p&gt;Server address&lt;/p&gt;
* $user **string** - &lt;p&gt;Login for database connection&lt;/p&gt;
* $pwd **string** - &lt;p&gt;Password for database connection&lt;/p&gt;



### hasTableWithSamePrefix

    boolean DbCore::hasTableWithSamePrefix(string $server, string $user, string $pwd, string $db, string $prefix)

Try a connection to the database and check if at least one table with same prefix exists



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/Db.php line 866](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#866)


#### Arguments
* $server **string** - &lt;p&gt;Server address&lt;/p&gt;
* $user **string** - &lt;p&gt;Login for database connection&lt;/p&gt;
* $pwd **string** - &lt;p&gt;Password for database connection&lt;/p&gt;
* $db **string** - &lt;p&gt;Database name&lt;/p&gt;
* $prefix **string** - &lt;p&gt;Tables prefix&lt;/p&gt;



### checkCreatePrivilege

    boolean|string DbCore::checkCreatePrivilege(string $server, string $user, string $pwd, string $db, string $prefix, string|null $engine)

Tries to connect to the database and create a table (checking creation privileges)



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/Db.php line 882](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#882)


#### Arguments
* $server **string**
* $user **string**
* $pwd **string**
* $db **string**
* $prefix **string**
* $engine **string|null** - &lt;p&gt;Table engine&lt;/p&gt;



### checkAutoIncrement

    boolean DbCore::checkAutoIncrement(string $server, string $user, string $pwd)

Checks if auto increment value and offset is 1



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/Db.php line 895](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#895)


#### Arguments
* $server **string**
* $user **string**
* $pwd **string**



### s

    array|boolean|\mysqli_result|\PDOStatement|resource DbCore::s(string|\DbQuery $sql, boolean $use_cache)

Executes a query



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/Db.php line 909](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#909)


#### Arguments
* $sql **string|[string](DbQueryCore)**
* $use_cache **boolean**



### ps

    array|boolean|\mysqli_result|\PDOStatement|resource DbCore::ps($sql, integer $use_cache)

Executes a query



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/Db.php line 923](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#923)


#### Arguments
* $sql **mixed**
* $use_cache **integer**



### ds

    mixed DbCore::ds($sql, integer $use_cache)

Executes a query and kills process (dies)



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/db/Db.php line 937](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#937)


#### Arguments
* $sql **mixed**
* $use_cache **integer**



### getLink

    \PDO|\mysqli|resource DbCore::getLink()

Get used link instance



* Visibility: **public**
* This method is defined in [classes/db/Db.php line 949](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#949)



