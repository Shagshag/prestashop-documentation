Class DbCore
=====================

Class DbCore



* Class name: DbCore
* This is an **abstract** class
* Source: [classes/db/Db.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L34)

Constants
----------

* [INSERT](#constant-INSERT)
* [INSERT_IGNORE](#constant-INSERT_IGNORE)
* [ON_DUPLICATE_KEY](#constant-ON_DUPLICATE_KEY)
* [REPLACE](#constant-REPLACE)

Properties
----------

* [$_servers](#property-$_servers)
* [$_slave_servers_loaded](#property-$_slave_servers_loaded)
* [$database](#property-$database)
* [$instance](#property-$instance)
* [$is_cache_enabled](#property-$is_cache_enabled)
* [$last_cached](#property-$last_cached)
* [$last_query](#property-$last_query)
* [$last_query_hash](#property-$last_query_hash)
* [$link](#property-$link)
* [$password](#property-$password)
* [$result](#property-$result)
* [$server](#property-$server)
* [$user](#property-$user)

Methods
-------
* [Affected_Rows](#method-Affected_Rows)
* [Insert_ID](#method-Insert_ID)
* [__construct](#method-__construct)
* [__destruct](#method-__destruct)
* [_escape](#method-_escape)
* [_numRows](#method-_numRows)
* [_query](#method-_query)
* [autoExecute](#method-autoExecute)
* [autoExecuteWithNullValues](#method-autoExecuteWithNullValues)
* [checkAutoIncrement](#method-checkAutoIncrement)
* [checkConnection](#method-checkConnection)
* [checkCreatePrivilege](#method-checkCreatePrivilege)
* [checkEncoding](#method-checkEncoding)
* [connect](#method-connect)
* [delete](#method-delete)
* [deleteTestingInstance](#method-deleteTestingInstance)
* [disableCache](#method-disableCache)
* [disconnect](#method-disconnect)
* [displayError](#method-displayError)
* [ds](#method-ds)
* [enableCache](#method-enableCache)
* [escape](#method-escape)
* [execute](#method-execute)
* [executeS](#method-executeS)
* [getAll](#method-getAll)
* [getBestEngine](#method-getBestEngine)
* [getClass](#method-getClass)
* [getInstance](#method-getInstance)
* [getLink](#method-getLink)
* [getMsgError](#method-getMsgError)
* [getNumberError](#method-getNumberError)
* [getRow](#method-getRow)
* [getValue](#method-getValue)
* [getVersion](#method-getVersion)
* [hasTableWithSamePrefix](#method-hasTableWithSamePrefix)
* [insert](#method-insert)
* [loadSlaveServers](#method-loadSlaveServers)
* [nextRow](#method-nextRow)
* [numRows](#method-numRows)
* [ps](#method-ps)
* [q](#method-q)
* [query](#method-query)
* [s](#method-s)
* [setInstanceForTesting](#method-setInstanceForTesting)
* [set_db](#method-set_db)
* [update](#method-update)


Constants
----------


### <a name="constant-INSERT"></a>INSERT

    const INSERT = 1



* Source: [classes/db/Db.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L37)


### <a name="constant-INSERT_IGNORE"></a>INSERT_IGNORE

    const INSERT_IGNORE = 2



* Source: [classes/db/Db.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L40)


### <a name="constant-ON_DUPLICATE_KEY"></a>ON_DUPLICATE_KEY

    const ON_DUPLICATE_KEY = 4



* Source: [classes/db/Db.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L46)


### <a name="constant-REPLACE"></a>REPLACE

    const REPLACE = 3



* Source: [classes/db/Db.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L43)


Properties
----------


### <a name="property-$_servers"></a>$_servers

    public array $_servers = array()





* Visibility: **public**
* This property is **static**.
* Source: [classes/db/Db.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L73)


### <a name="property-$_slave_servers_loaded"></a>$_slave_servers_loaded

    public null $_slave_servers_loaded = null





* Visibility: **public**
* This property is **static**.
* Source: [classes/db/Db.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L78)


### <a name="property-$database"></a>$database

    protected string $database





* Visibility: **protected**
* Source: [classes/db/Db.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L58)


### <a name="property-$instance"></a>$instance

    public array $instance = array()





* Visibility: **public**
* This property is **static**.
* Source: [classes/db/Db.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L70)


### <a name="property-$is_cache_enabled"></a>$is_cache_enabled

    protected boolean $is_cache_enabled





* Visibility: **protected**
* Source: [classes/db/Db.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L61)


### <a name="property-$last_cached"></a>$last_cached

    protected string $last_cached

Last cached query



* Visibility: **protected**
* Source: [classes/db/Db.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L99)


### <a name="property-$last_query"></a>$last_query

    protected string $last_query

Store last executed query



* Visibility: **protected**
* Source: [classes/db/Db.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L85)


### <a name="property-$last_query_hash"></a>$last_query_hash

    protected string $last_query_hash

Store hash of the last executed query



* Visibility: **protected**
* Source: [classes/db/Db.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L92)


### <a name="property-$link"></a>$link

    protected \PDO $link





* Visibility: **protected**
* Source: [classes/db/Db.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L64)


### <a name="property-$password"></a>$password

    protected string $password





* Visibility: **protected**
* Source: [classes/db/Db.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L55)


### <a name="property-$result"></a>$result

    protected \PDOStatement $result





* Visibility: **protected**
* Source: [classes/db/Db.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L67)


### <a name="property-$server"></a>$server

    protected string $server





* Visibility: **protected**
* Source: [classes/db/Db.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L49)


### <a name="property-$user"></a>$user

    protected string $user





* Visibility: **protected**
* Source: [classes/db/Db.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L52)


Methods
-------


### <a name="method-Affected_Rows"></a>Affected_Rows

    integer DbCore::Affected_Rows()

Get number of affected rows in previous database operation



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L141)




### <a name="method-Insert_ID"></a>Insert_ID

    integer|string DbCore::Insert_ID()

Get the ID generated from the previous INSERT operation



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L134)




### <a name="method-__construct"></a>__construct

    mixed DbCore::__construct(string $server, string $user, string $password, string $database, boolean $connect)

Instantiates a database connection



* Visibility: **public**
* Source: [classes/db/Db.php line 306](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L306)


#### Arguments
* $server **string** - Server address
* $user **string** - User login
* $password **string** - User password
* $database **string** - Database name
* $connect **boolean** - If false, don&#039;t connect in constructor (since 1.5.0.1)



### <a name="method-__destruct"></a>__destruct

    mixed DbCore::__destruct()

Closes connection to database



* Visibility: **public**
* Source: [classes/db/Db.php line 345](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L345)




### <a name="method-_escape"></a>_escape

    string DbCore::_escape(string $str)

Protect string against SQL injections



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L172)


#### Arguments
* $str **string**



### <a name="method-_numRows"></a>_numRows

    integer DbCore::_numRows(mixed $result)

Get number of rows in a result



* Visibility: **protected**
* This method is **abstract**.
* Source: [classes/db/Db.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L127)


#### Arguments
* $result **mixed**



### <a name="method-_query"></a>_query

    \PDOStatement|\mysqli_result|resource|boolean DbCore::_query(string $sql)

Execute a query and get result resource



* Visibility: **protected**
* This method is **abstract**.
* Source: [classes/db/Db.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L119)


#### Arguments
* $sql **string**



### <a name="method-autoExecute"></a>autoExecute

    boolean DbCore::autoExecute(string $table, array $data, string $type, string $where, integer $limit, boolean $use_cache, boolean $use_null)

Executes SQL query based on selected type



* Visibility: **public**
* Source: [classes/db/Db.php line 366](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L366)


#### Arguments
* $table **string**
* $data **array**
* $type **string** - (INSERT, INSERT IGNORE, REPLACE, UPDATE).
* $where **string**
* $limit **integer**
* $use_cache **boolean**
* $use_null **boolean**



### <a name="method-autoExecuteWithNullValues"></a>autoExecuteWithNullValues

    boolean DbCore::autoExecuteWithNullValues(string $table, array $values, string $type, string $where, integer $limit)

Filter SQL query within a blacklist



* Visibility: **public**
* Source: [classes/db/Db.php line 398](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L398)


#### Arguments
* $table **string** - Table where insert/update data
* $values **array** - Data to insert/update
* $type **string** - INSERT or UPDATE
* $where **string** - WHERE clause, only for UPDATE (optional)
* $limit **integer** - LIMIT clause (optional)



### <a name="method-checkAutoIncrement"></a>checkAutoIncrement

    boolean DbCore::checkAutoIncrement(string $server, string $user, string $pwd)

Checks if auto increment value and offset is 1



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 895](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L895)


#### Arguments
* $server **string**
* $user **string**
* $pwd **string**



### <a name="method-checkConnection"></a>checkConnection

    integer DbCore::checkConnection(string $server, string $user, string $pwd, string $db, boolean $new_db_link, string|boolean $engine, integer $timeout)

Try a connection to the database



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 838](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L838)


#### Arguments
* $server **string** - Server address
* $user **string** - Login for database connection
* $pwd **string** - Password for database connection
* $db **string** - Database name
* $new_db_link **boolean**
* $engine **string|boolean**
* $timeout **integer**



### <a name="method-checkCreatePrivilege"></a>checkCreatePrivilege

    boolean|string DbCore::checkCreatePrivilege(string $server, string $user, string $pwd, string $db, string $prefix, string|null $engine)

Tries to connect to the database and create a table (checking creation privileges)



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 882](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L882)


#### Arguments
* $server **string**
* $user **string**
* $pwd **string**
* $db **string**
* $prefix **string**
* $engine **string|null** - Table engine



### <a name="method-checkEncoding"></a>checkEncoding

    boolean DbCore::checkEncoding(string $server, string $user, string $pwd)

Try a connection to the database and set names to UTF-8



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 851](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L851)


#### Arguments
* $server **string** - Server address
* $user **string** - Login for database connection
* $pwd **string** - Password for database connection



### <a name="method-connect"></a>connect

    \PDO|\mysqli|resource DbCore::connect()

Opens a database connection



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L106)




### <a name="method-delete"></a>delete

    boolean DbCore::delete(string $table, string $where, integer $limit, boolean $use_cache, boolean $add_prefix)

Executes a DELETE query



* Visibility: **public**
* Source: [classes/db/Db.php line 572](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L572)


#### Arguments
* $table **string** - Name of the table to delete
* $where **string** - WHERE clause on query
* $limit **integer** - Number max of rows to delete
* $use_cache **boolean** - Use cache or not
* $add_prefix **boolean** - Add or not _DB_PREFIX_ before table name



### <a name="method-deleteTestingInstance"></a>deleteTestingInstance

    mixed DbCore::deleteTestingInstance()

Unit testing purpose only



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 258](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L258)




### <a name="method-disableCache"></a>disableCache

    mixed DbCore::disableCache()

Disable the use of the cache



* Visibility: **public**
* Source: [classes/db/Db.php line 327](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L327)




### <a name="method-disconnect"></a>disconnect

    mixed DbCore::disconnect()

Closes database connection



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L111)




### <a name="method-displayError"></a>displayError

    mixed DbCore::displayError(string|boolean $sql)

Displays last SQL error



* Visibility: **public**
* Source: [classes/db/Db.php line 781](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L781)


#### Arguments
* $sql **string|boolean**



### <a name="method-ds"></a>ds

    mixed DbCore::ds($sql, integer $use_cache)

Executes a query and kills process (dies)



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 937](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L937)


#### Arguments
* $sql **mixed**
* $use_cache **integer**



### <a name="method-enableCache"></a>enableCache

    mixed DbCore::enableCache()

Enable & flush the cache



* Visibility: **public**
* Source: [classes/db/Db.php line 336](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L336)




### <a name="method-escape"></a>escape

    string DbCore::escape(string $string, boolean $html_ok, $bq_sql)

Sanitize data which will be injected into SQL query



* Visibility: **public**
* Source: [classes/db/Db.php line 805](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L805)


#### Arguments
* $string **string** - SQL data which will be injected into SQL query
* $html_ok **boolean** - Does data contain HTML code ? (optional)
* $bq_sql **mixed**



### <a name="method-execute"></a>execute

    boolean DbCore::execute(string|\DbQuery $sql, boolean $use_cache)

Executes a query



* Visibility: **public**
* Source: [classes/db/Db.php line 595](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L595)


#### Arguments
* $sql **string|[string](class.DbQueryCore.md)**
* $use_cache **boolean**



### <a name="method-executeS"></a>executeS

    array|false|null|\mysqli_result|\PDOStatement|resource DbCore::executeS(string|\DbQuery $sql, boolean $array, boolean $use_cache)

Executes return the result of $sql as array



* Visibility: **public**
* Source: [classes/db/Db.php line 618](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L618)


#### Arguments
* $sql **string|[string](class.DbQueryCore.md)** - Query to execute
* $array **boolean** - Return an array instead of a result object (deprecated since 1.5.0.1, use query method instead)
* $use_cache **boolean**



### <a name="method-getAll"></a>getAll

    array DbCore::getAll(\PDOStatement|\mysqli_result|resource|boolean|null $result)

Get all rows for a query which return an array



* Visibility: **protected**
* This method is **abstract**.
* Source: [classes/db/Db.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L157)


#### Arguments
* $result **PDOStatement|mysqli_result|resource|boolean|null**



### <a name="method-getBestEngine"></a>getBestEngine

    string DbCore::getBestEngine()

Selects best table engine.



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L202)




### <a name="method-getClass"></a>getClass

    string DbCore::getClass()

Returns the best child layer database class.



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 285](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L285)




### <a name="method-getInstance"></a>getInstance

    \Db DbCore::getInstance(boolean $master)

Returns database object instance.



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 210](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L210)


#### Arguments
* $master **boolean** - Decides whether the connection to be returned by the master server or the slave server



### <a name="method-getLink"></a>getLink

    \PDO|\mysqli|resource DbCore::getLink()

Get used link instance



* Visibility: **public**
* Source: [classes/db/Db.php line 949](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L949)




### <a name="method-getMsgError"></a>getMsgError

    string DbCore::getMsgError()

Returns the text of the error message from previous database operation



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L179)




### <a name="method-getNumberError"></a>getNumberError

    integer DbCore::getNumberError()

Returns the number of the error from previous database operation



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L186)




### <a name="method-getRow"></a>getRow

    array|boolean|object|null DbCore::getRow(string|\DbQuery $sql, boolean $use_cache)

Returns an associative array containing the first row of the query
This function automatically adds "LIMIT 1" to the query



* Visibility: **public**
* Source: [classes/db/Db.php line 672](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L672)


#### Arguments
* $sql **string|[string](class.DbQueryCore.md)** - the select query (without &quot;LIMIT 1&quot;)
* $use_cache **boolean** - Find it in cache first



### <a name="method-getValue"></a>getValue

    string|false|null DbCore::getValue(string|\DbQuery $sql, boolean $use_cache)

Returns a value from the first row, first column of a SELECT query



* Visibility: **public**
* Source: [classes/db/Db.php line 717](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L717)


#### Arguments
* $sql **string|[string](class.DbQueryCore.md)**
* $use_cache **boolean**



### <a name="method-getVersion"></a>getVersion

    string DbCore::getVersion()

Get database version



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L164)




### <a name="method-hasTableWithSamePrefix"></a>hasTableWithSamePrefix

    boolean DbCore::hasTableWithSamePrefix(string $server, string $user, string $pwd, string $db, string $prefix)

Try a connection to the database and check if at least one table with same prefix exists



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 866](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L866)


#### Arguments
* $server **string** - Server address
* $user **string** - Login for database connection
* $pwd **string** - Password for database connection
* $db **string** - Database name
* $prefix **string** - Tables prefix



### <a name="method-insert"></a>insert

    boolean DbCore::insert(string $table, array $data, boolean $null_values, boolean $use_cache, integer $type, boolean $add_prefix)

Executes an INSERT query



* Visibility: **public**
* Source: [classes/db/Db.php line 443](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L443)


#### Arguments
* $table **string** - Table name without prefix
* $data **array** - Data to insert as associative array. If $data is a list of arrays, multiple insert will be done
* $null_values **boolean** - If we want to use NULL values instead of empty quotes
* $use_cache **boolean**
* $type **integer** - Must be Db::INSERT or Db::INSERT_IGNORE or Db::REPLACE
* $add_prefix **boolean** - Add or not _DB_PREFIX_ before table name



### <a name="method-loadSlaveServers"></a>loadSlaveServers

    mixed DbCore::loadSlaveServers()

Loads configuration settings for slave servers if needed.



* Visibility: **protected**
* This method is **static**.
* Source: [classes/db/Db.php line 266](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L266)




### <a name="method-nextRow"></a>nextRow

    array|object|false|null DbCore::nextRow(\PDOStatement|\mysqli_result|resource|boolean $result)

Get next row for a query which does not return an array



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L149)


#### Arguments
* $result **PDOStatement|mysqli_result|resource|boolean**



### <a name="method-numRows"></a>numRows

    integer DbCore::numRows()

Get number of rows for last result



* Visibility: **public**
* Source: [classes/db/Db.php line 735](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L735)




### <a name="method-ps"></a>ps

    array|boolean|\mysqli_result|\PDOStatement|resource DbCore::ps($sql, integer $use_cache)

Executes a query



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 923](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L923)


#### Arguments
* $sql **mixed**
* $use_cache **integer**



### <a name="method-q"></a>q

    boolean|\mysqli_result|\PDOStatement|resource DbCore::q(string|\DbQuery $sql, boolean $use_cache)

Executes a query



* Visibility: **protected**
* Source: [classes/db/Db.php line 756](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L756)


#### Arguments
* $sql **string|[string](class.DbQueryCore.md)**
* $use_cache **boolean**



### <a name="method-query"></a>query

    boolean|\mysqli_result|\PDOStatement|resource DbCore::query(string|\DbQuery $sql)

Execute a query and get result resource



* Visibility: **public**
* Source: [classes/db/Db.php line 410](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L410)


#### Arguments
* $sql **string|[string](class.DbQueryCore.md)**



### <a name="method-s"></a>s

    array|boolean|\mysqli_result|\PDOStatement|resource DbCore::s(string|\DbQuery $sql, boolean $use_cache)

Executes a query



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 909](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L909)


#### Arguments
* $sql **string|[string](class.DbQueryCore.md)**
* $use_cache **boolean**



### <a name="method-setInstanceForTesting"></a>setInstanceForTesting

    mixed DbCore::setInstanceForTesting($test_db)





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 250](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L250)


#### Arguments
* $test_db **mixed** - Db
Unit testing purpose only



### <a name="method-set_db"></a>set_db

    boolean|integer DbCore::set_db(string $db_name)

Sets the current active database on the server that's associated with the specified link identifier.

Do not remove, useful for some modules.

* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L195)


#### Arguments
* $db_name **string**



### <a name="method-update"></a>update

    boolean DbCore::update(string $table, array $data, string $where, integer $limit, boolean $null_values, boolean $use_cache, boolean $add_prefix)

Executes an UPDATE query



* Visibility: **public**
* Source: [classes/db/Db.php line 529](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/Db.php#L529)


#### Arguments
* $table **string** - Table name without prefix
* $data **array** - Data to insert as associative array. If $data is a list of arrays, multiple insert will be done
* $where **string** - WHERE condition
* $limit **integer**
* $null_values **boolean** - If we want to use NULL values instead of empty quotes
* $use_cache **boolean**
* $add_prefix **boolean** - Add or not _DB_PREFIX_ before table name


