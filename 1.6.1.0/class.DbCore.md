Class DbCore
=====================

Class DbCore



* Class name: DbCore
* This is an **abstract** class
* Source: [classes/db/Db.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L33)


Contents
--------

### Constants

* [INSERT](#constant-INSERT)
* [INSERT_IGNORE](#constant-INSERT_IGNORE)
* [ON_DUPLICATE_KEY](#constant-ON_DUPLICATE_KEY)
* [REPLACE](#constant-REPLACE)

### Properties

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

### Methods

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

```php
const INSERT = 1
```





* Source: [classes/db/Db.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L36).


### <a name="constant-INSERT_IGNORE"></a>INSERT_IGNORE

```php
const INSERT_IGNORE = 2
```





* Source: [classes/db/Db.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L39).


### <a name="constant-ON_DUPLICATE_KEY"></a>ON_DUPLICATE_KEY

```php
const ON_DUPLICATE_KEY = 4
```





* Source: [classes/db/Db.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L45).


### <a name="constant-REPLACE"></a>REPLACE

```php
const REPLACE = 3
```





* Source: [classes/db/Db.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L42).


Properties
----------


### <a name="property-$_servers"></a>$_servers

```php
public array $_servers = array()
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/db/Db.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L72).


### <a name="property-$_slave_servers_loaded"></a>$_slave_servers_loaded

```php
public null $_slave_servers_loaded = null
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/db/Db.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L77).


### <a name="property-$database"></a>$database

```php
protected string $database
```





* Visibility: **protected**
* Source: [classes/db/Db.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L57).


### <a name="property-$instance"></a>$instance

```php
public array $instance = array()
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/db/Db.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L69).


### <a name="property-$is_cache_enabled"></a>$is_cache_enabled

```php
protected boolean $is_cache_enabled
```





* Visibility: **protected**
* Source: [classes/db/Db.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L60).


### <a name="property-$last_cached"></a>$last_cached

```php
protected string $last_cached
```

Last cached query



* Visibility: **protected**
* Source: [classes/db/Db.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L98).


### <a name="property-$last_query"></a>$last_query

```php
protected string $last_query
```

Store last executed query



* Visibility: **protected**
* Source: [classes/db/Db.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L84).


### <a name="property-$last_query_hash"></a>$last_query_hash

```php
protected string $last_query_hash
```

Store hash of the last executed query



* Visibility: **protected**
* Source: [classes/db/Db.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L91).


### <a name="property-$link"></a>$link

```php
protected \PDO $link
```





* Visibility: **protected**
* Source: [classes/db/Db.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L63).


### <a name="property-$password"></a>$password

```php
protected string $password
```





* Visibility: **protected**
* Source: [classes/db/Db.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L54).


### <a name="property-$result"></a>$result

```php
protected \PDOStatement $result
```





* Visibility: **protected**
* Source: [classes/db/Db.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L66).


### <a name="property-$server"></a>$server

```php
protected string $server
```





* Visibility: **protected**
* Source: [classes/db/Db.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L48).


### <a name="property-$user"></a>$user

```php
protected string $user
```





* Visibility: **protected**
* Source: [classes/db/Db.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L51).


Methods
-------


### <a name="method-Affected_Rows"></a>Affected_Rows

```php
integer DbCore::Affected_Rows()
```

Get number of affected rows in previous database operation



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L140)




### <a name="method-Insert_ID"></a>Insert_ID

```php
integer|string DbCore::Insert_ID()
```

Get the ID generated from the previous INSERT operation



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L133)




### <a name="method-__construct"></a>__construct

```php
mixed DbCore::__construct(string $server, string $user, string $password, string $database, boolean $connect)
```

Instantiates a database connection



* Visibility: **public**
* Source: [classes/db/Db.php line 302](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L302)


#### Arguments
* $server **string** - Server address
* $user **string** - User login
* $password **string** - User password
* $database **string** - Database name
* $connect **boolean** - If false, don&#039;t connect in constructor (since 1.5.0.1)



### <a name="method-__destruct"></a>__destruct

```php
mixed DbCore::__destruct()
```

Closes connection to database



* Visibility: **public**
* Source: [classes/db/Db.php line 339](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L339)




### <a name="method-_escape"></a>_escape

```php
string DbCore::_escape(string $str)
```

Protect string against SQL injections



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L171)


#### Arguments
* $str **string**



### <a name="method-_numRows"></a>_numRows

```php
integer DbCore::_numRows(mixed $result)
```

Get number of rows in a result



* Visibility: **protected**
* This method is **abstract**.
* Source: [classes/db/Db.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L126)


#### Arguments
* $result **mixed**



### <a name="method-_query"></a>_query

```php
\PDOStatement|\mysqli_result|resource|boolean DbCore::_query(string $sql)
```

Execute a query and get result resource



* Visibility: **protected**
* This method is **abstract**.
* Source: [classes/db/Db.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L118)


#### Arguments
* $sql **string**



### <a name="method-autoExecute"></a>autoExecute

```php
boolean DbCore::autoExecute(string $table, array $data, string $type, string $where, integer $limit, boolean $use_cache, boolean $use_null)
```

Executes SQL query based on selected type



* Visibility: **public**
* Source: [classes/db/Db.php line 359](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L359)


#### Arguments
* $table **string**
* $data **array**
* $type **string** - (INSERT, INSERT IGNORE, REPLACE, UPDATE).
* $where **string**
* $limit **integer**
* $use_cache **boolean**
* $use_null **boolean**



### <a name="method-autoExecuteWithNullValues"></a>autoExecuteWithNullValues

```php
boolean DbCore::autoExecuteWithNullValues(string $table, array $values, string $type, string $where, integer $limit)
```

Filter SQL query within a blacklist



* Visibility: **public**
* Source: [classes/db/Db.php line 392](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L392)


#### Arguments
* $table **string** - Table where insert/update data
* $values **array** - Data to insert/update
* $type **string** - INSERT or UPDATE
* $where **string** - WHERE clause, only for UPDATE (optional)
* $limit **integer** - LIMIT clause (optional)



### <a name="method-checkAutoIncrement"></a>checkAutoIncrement

```php
boolean DbCore::checkAutoIncrement(string $server, string $user, string $pwd)
```

Checks if auto increment value and offset is 1



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 866](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L866)


#### Arguments
* $server **string**
* $user **string**
* $pwd **string**



### <a name="method-checkConnection"></a>checkConnection

```php
integer DbCore::checkConnection(string $server, string $user, string $pwd, string $db, boolean $new_db_link, string|boolean $engine, integer $timeout)
```

Try a connection to the database



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 809](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L809)


#### Arguments
* $server **string** - Server address
* $user **string** - Login for database connection
* $pwd **string** - Password for database connection
* $db **string** - Database name
* $new_db_link **boolean**
* $engine **string|boolean**
* $timeout **integer**



### <a name="method-checkCreatePrivilege"></a>checkCreatePrivilege

```php
boolean|string DbCore::checkCreatePrivilege(string $server, string $user, string $pwd, string $db, string $prefix, string|null $engine)
```

Tries to connect to the database and create a table (checking creation privileges)



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 853](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L853)


#### Arguments
* $server **string**
* $user **string**
* $pwd **string**
* $db **string**
* $prefix **string**
* $engine **string|null** - Table engine



### <a name="method-checkEncoding"></a>checkEncoding

```php
boolean DbCore::checkEncoding(string $server, string $user, string $pwd)
```

Try a connection to the database and set names to UTF-8



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 822](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L822)


#### Arguments
* $server **string** - Server address
* $user **string** - Login for database connection
* $pwd **string** - Password for database connection



### <a name="method-connect"></a>connect

```php
\PDO|\mysqli|resource DbCore::connect()
```

Opens a database connection



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L105)




### <a name="method-delete"></a>delete

```php
boolean DbCore::delete(string $table, string $where, integer $limit, boolean $use_cache, boolean $add_prefix)
```

Executes a DELETE query



* Visibility: **public**
* Source: [classes/db/Db.php line 552](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L552)


#### Arguments
* $table **string** - Name of the table to delete
* $where **string** - WHERE clause on query
* $limit **integer** - Number max of rows to delete
* $use_cache **boolean** - Use cache or not
* $add_prefix **boolean** - Add or not _DB_PREFIX_ before table name



### <a name="method-deleteTestingInstance"></a>deleteTestingInstance

```php
mixed DbCore::deleteTestingInstance()
```

Unit testing purpose only



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 257](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L257)




### <a name="method-disableCache"></a>disableCache

```php
mixed DbCore::disableCache()
```

Disable the use of the cache



* Visibility: **public**
* Source: [classes/db/Db.php line 321](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L321)




### <a name="method-disconnect"></a>disconnect

```php
mixed DbCore::disconnect()
```

Closes database connection



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L110)




### <a name="method-displayError"></a>displayError

```php
mixed DbCore::displayError(string|boolean $sql)
```

Displays last SQL error



* Visibility: **public**
* Source: [classes/db/Db.php line 752](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L752)


#### Arguments
* $sql **string|boolean**



### <a name="method-ds"></a>ds

```php
mixed DbCore::ds($sql, integer $use_cache)
```

Executes a query and kills process (dies)



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 908](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L908)


#### Arguments
* $sql **mixed**
* $use_cache **integer**



### <a name="method-enableCache"></a>enableCache

```php
mixed DbCore::enableCache()
```

Enable & flush the cache



* Visibility: **public**
* Source: [classes/db/Db.php line 330](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L330)




### <a name="method-escape"></a>escape

```php
string DbCore::escape(string $string, boolean $html_ok, $bq_sql)
```

Sanitize data which will be injected into SQL query



* Visibility: **public**
* Source: [classes/db/Db.php line 778](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L778)


#### Arguments
* $string **string** - SQL data which will be injected into SQL query
* $html_ok **boolean** - Does data contain HTML code ? (optional)
* $bq_sql **mixed**



### <a name="method-execute"></a>execute

```php
boolean DbCore::execute(string|\DbQuery $sql, boolean $use_cache)
```

Executes a query



* Visibility: **public**
* Source: [classes/db/Db.php line 573](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L573)


#### Arguments
* $sql **string|[string](class.DbQueryCore.md)**
* $use_cache **boolean**



### <a name="method-executeS"></a>executeS

```php
array|false|null|\mysqli_result|\PDOStatement|resource DbCore::executeS(string|\DbQuery $sql, boolean $array, boolean $use_cache)
```

Executes return the result of $sql as array



* Visibility: **public**
* Source: [classes/db/Db.php line 594](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L594)


#### Arguments
* $sql **string|[string](class.DbQueryCore.md)** - Query to execute
* $array **boolean** - Return an array instead of a result object (deprecated since 1.5.0.1, use query method instead)
* $use_cache **boolean**



### <a name="method-getAll"></a>getAll

```php
array DbCore::getAll(\PDOStatement|\mysqli_result|resource|boolean|null $result)
```

Get all rows for a query which return an array



* Visibility: **protected**
* This method is **abstract**.
* Source: [classes/db/Db.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L156)


#### Arguments
* $result **PDOStatement|mysqli_result|resource|boolean|null**



### <a name="method-getBestEngine"></a>getBestEngine

```php
string DbCore::getBestEngine()
```

Selects best table engine.



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L201)




### <a name="method-getClass"></a>getClass

```php
string DbCore::getClass()
```

Returns the best child layer database class.



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 282](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L282)




### <a name="method-getInstance"></a>getInstance

```php
\Db DbCore::getInstance(boolean $master)
```

Returns database object instance.



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 209](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L209)


#### Arguments
* $master **boolean** - Decides whether the connection to be returned by the master server or the slave server



### <a name="method-getLink"></a>getLink

```php
\PDO|\mysqli|resource DbCore::getLink()
```

Get used link instance



* Visibility: **public**
* Source: [classes/db/Db.php line 920](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L920)




### <a name="method-getMsgError"></a>getMsgError

```php
string DbCore::getMsgError()
```

Returns the text of the error message from previous database operation



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L178)




### <a name="method-getNumberError"></a>getNumberError

```php
integer DbCore::getNumberError()
```

Returns the number of the error from previous database operation



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 185](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L185)




### <a name="method-getRow"></a>getRow

```php
array|boolean|object|null DbCore::getRow(string|\DbQuery $sql, boolean $use_cache)
```

Returns an associative array containing the first row of the query
This function automatically adds "LIMIT 1" to the query



* Visibility: **public**
* Source: [classes/db/Db.php line 650](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L650)


#### Arguments
* $sql **string|[string](class.DbQueryCore.md)** - the select query (without &quot;LIMIT 1&quot;)
* $use_cache **boolean** - Find it in cache first



### <a name="method-getValue"></a>getValue

```php
string|false|null DbCore::getValue(string|\DbQuery $sql, boolean $use_cache)
```

Returns a value from the first row, first column of a SELECT query



* Visibility: **public**
* Source: [classes/db/Db.php line 693](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L693)


#### Arguments
* $sql **string|[string](class.DbQueryCore.md)**
* $use_cache **boolean**



### <a name="method-getVersion"></a>getVersion

```php
string DbCore::getVersion()
```

Get database version



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L163)




### <a name="method-hasTableWithSamePrefix"></a>hasTableWithSamePrefix

```php
boolean DbCore::hasTableWithSamePrefix(string $server, string $user, string $pwd, string $db, string $prefix)
```

Try a connection to the database and check if at least one table with same prefix exists



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 837](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L837)


#### Arguments
* $server **string** - Server address
* $user **string** - Login for database connection
* $pwd **string** - Password for database connection
* $db **string** - Database name
* $prefix **string** - Tables prefix



### <a name="method-insert"></a>insert

```php
boolean DbCore::insert(string $table, array $data, boolean $null_values, boolean $use_cache, integer $type, boolean $add_prefix)
```

Executes an INSERT query



* Visibility: **public**
* Source: [classes/db/Db.php line 435](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L435)


#### Arguments
* $table **string** - Table name without prefix
* $data **array** - Data to insert as associative array. If $data is a list of arrays, multiple insert will be done
* $null_values **boolean** - If we want to use NULL values instead of empty quotes
* $use_cache **boolean**
* $type **integer** - Must be Db::INSERT or Db::INSERT_IGNORE or Db::REPLACE
* $add_prefix **boolean** - Add or not _DB_PREFIX_ before table name



### <a name="method-loadSlaveServers"></a>loadSlaveServers

```php
mixed DbCore::loadSlaveServers()
```

Loads configuration settings for slave servers if needed.



* Visibility: **protected**
* This method is **static**.
* Source: [classes/db/Db.php line 265](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L265)




### <a name="method-nextRow"></a>nextRow

```php
array|object|false|null DbCore::nextRow(\PDOStatement|\mysqli_result|resource|boolean $result)
```

Get next row for a query which does not return an array



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L148)


#### Arguments
* $result **PDOStatement|mysqli_result|resource|boolean**



### <a name="method-numRows"></a>numRows

```php
integer DbCore::numRows()
```

Get number of rows for last result



* Visibility: **public**
* Source: [classes/db/Db.php line 709](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L709)




### <a name="method-ps"></a>ps

```php
array|boolean|\mysqli_result|\PDOStatement|resource DbCore::ps($sql, integer $use_cache)
```

Executes a query



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 894](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L894)


#### Arguments
* $sql **mixed**
* $use_cache **integer**



### <a name="method-q"></a>q

```php
boolean|\mysqli_result|\PDOStatement|resource DbCore::q(string|\DbQuery $sql, boolean $use_cache)
```

Executes a query



* Visibility: **protected**
* Source: [classes/db/Db.php line 730](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L730)


#### Arguments
* $sql **string|[string](class.DbQueryCore.md)**
* $use_cache **boolean**



### <a name="method-query"></a>query

```php
boolean|\mysqli_result|\PDOStatement|resource DbCore::query(string|\DbQuery $sql)
```

Execute a query and get result resource



* Visibility: **public**
* Source: [classes/db/Db.php line 404](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L404)


#### Arguments
* $sql **string|[string](class.DbQueryCore.md)**



### <a name="method-s"></a>s

```php
array|boolean|\mysqli_result|\PDOStatement|resource DbCore::s(string|\DbQuery $sql, boolean $use_cache)
```

Executes a query



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 880](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L880)


#### Arguments
* $sql **string|[string](class.DbQueryCore.md)**
* $use_cache **boolean**



### <a name="method-setInstanceForTesting"></a>setInstanceForTesting

```php
mixed DbCore::setInstanceForTesting($test_db)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L249)


#### Arguments
* $test_db **mixed** - Db
Unit testing purpose only



### <a name="method-set_db"></a>set_db

```php
boolean|integer DbCore::set_db(string $db_name)
```

Sets the current active database on the server that's associated with the specified link identifier.

Do not remove, useful for some modules.

* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 194](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L194)


#### Arguments
* $db_name **string**



### <a name="method-update"></a>update

```php
boolean DbCore::update(string $table, array $data, string $where, integer $limit, boolean $null_values, boolean $use_cache, boolean $add_prefix)
```

Executes an UPDATE query



* Visibility: **public**
* Source: [classes/db/Db.php line 514](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/db/Db.php#L514)


#### Arguments
* $table **string** - Table name without prefix
* $data **array** - Data to insert as associative array. If $data is a list of arrays, multiple insert will be done
* $where **string** - WHERE condition
* $limit **integer**
* $null_values **boolean** - If we want to use NULL values instead of empty quotes
* $use_cache **boolean**
* $add_prefix **boolean** - Add or not _DB_PREFIX_ before table name


