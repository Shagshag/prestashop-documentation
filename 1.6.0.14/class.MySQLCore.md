Class MySQLCore
=====================





* Class name: MySQLCore
* Parent class: [Db](class.DbCore.md)
* Source: [classes/db/MySQL.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/MySQL.php#L27)


Contents
--------


### Properties

* [$_servers](#property-$_servers)
* [$database](#property-$database)
* [$instance](#property-$instance)
* [$is_cache_enabled](#property-$is_cache_enabled)
* [$last_cached](#property-$last_cached)
* [$last_query](#property-$last_query)
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
* [createDatabase](#method-createDatabase)
* [delete](#method-delete)
* [disconnect](#method-disconnect)
* [displayError](#method-displayError)
* [ds](#method-ds)
* [escape](#method-escape)
* [execute](#method-execute)
* [executeS](#method-executeS)
* [getAll](#method-getAll)
* [getBestEngine](#method-getBestEngine)
* [getClass](#method-getClass)
* [getInstance](#method-getInstance)
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
* [set_db](#method-set_db)
* [tryToConnect](#method-tryToConnect)
* [tryUTF8](#method-tryUTF8)
* [update](#method-update)




Properties
----------


### <a name="property-$_servers"></a>$_servers

```php
protected array $_servers = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L82).


### <a name="property-$database"></a>$database

```php
protected string $database
```





* Visibility: **protected**
* This property is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L57).


### <a name="property-$instance"></a>$instance

```php
protected array $instance = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L77).


### <a name="property-$is_cache_enabled"></a>$is_cache_enabled

```php
protected boolean $is_cache_enabled
```





* Visibility: **protected**
* This property is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L62).


### <a name="property-$last_cached"></a>$last_cached

```php
protected string $last_cached
```

Last cached query



* Visibility: **protected**
* This property is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L96).


### <a name="property-$last_query"></a>$last_query

```php
protected string $last_query
```

Store last executed query



* Visibility: **protected**
* This property is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L89).


### <a name="property-$link"></a>$link

```php
protected mixed $link
```





* Visibility: **protected**
* This property is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L67).


### <a name="property-$password"></a>$password

```php
protected string $password
```





* Visibility: **protected**
* This property is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L52).


### <a name="property-$result"></a>$result

```php
protected mixed $result
```





* Visibility: **protected**
* This property is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L72).


### <a name="property-$server"></a>$server

```php
protected string $server
```





* Visibility: **protected**
* This property is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L42).


### <a name="property-$user"></a>$user

```php
protected string $user
```





* Visibility: **protected**
* This property is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L47).


Methods
-------


### <a name="method-Affected_Rows"></a>Affected_Rows

```php
mixed MySQLCore::Affected_Rows()
```





* Visibility: **public**
* Source: [classes/db/MySQL.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/MySQL.php#L107)




### <a name="method-Insert_ID"></a>Insert_ID

```php
mixed MySQLCore::Insert_ID()
```





* Visibility: **public**
* Source: [classes/db/MySQL.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/MySQL.php#L99)




### <a name="method-__construct"></a>__construct

```php
mixed DbCore::__construct(string $server, string $user, string $password, string $database, boolean $connect)
```

Instantiate database connection



* Visibility: **public**
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 256](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L256)


#### Arguments
* $server **string** - Server address
* $user **string** - User login
* $password **string** - User password
* $database **string** - Database name
* $connect **boolean** - If false, don&#039;t connect in constructor (since 1.5.0)



### <a name="method-__destruct"></a>__destruct

```php
mixed DbCore::__destruct()
```

Close connection to database



* Visibility: **public**
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 274](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L274)




### <a name="method-_escape"></a>_escape

```php
mixed MySQLCore::_escape($str)
```





* Visibility: **public**
* Source: [classes/db/MySQL.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/MySQL.php#L139)


#### Arguments
* $str **mixed**



### <a name="method-_numRows"></a>_numRows

```php
mixed MySQLCore::_numRows($result)
```





* Visibility: **protected**
* Source: [classes/db/MySQL.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/MySQL.php#L91)


#### Arguments
* $result **mixed**



### <a name="method-_query"></a>_query

```php
mixed MySQLCore::_query($sql)
```





* Visibility: **protected**
* Source: [classes/db/MySQL.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/MySQL.php#L70)


#### Arguments
* $sql **mixed**



### <a name="method-autoExecute"></a>autoExecute

```php
mixed DbCore::autoExecute($table, $data, $type, $where, $limit, $use_cache, $use_null)
```





* Visibility: **public**
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 283](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L283)


#### Arguments
* $table **mixed**
* $data **mixed**
* $type **mixed**
* $where **mixed**
* $limit **mixed**
* $use_cache **mixed**
* $use_null **mixed**



### <a name="method-autoExecuteWithNullValues"></a>autoExecuteWithNullValues

```php
mixed|boolean DbCore::autoExecuteWithNullValues(string $table, string $values, string $type, string $where, integer $limit)
```

Filter SQL query within a blacklist



* Visibility: **public**
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 315](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L315)


#### Arguments
* $table **string** - Table where insert/update data
* $values **string** - Data to insert/update
* $type **string** - INSERT or UPDATE
* $where **string** - WHERE clause, only for UPDATE (optional)
* $limit **integer** - LIMIT clause (optional)



### <a name="method-checkAutoIncrement"></a>checkAutoIncrement

```php
mixed MySQLCore::checkAutoIncrement($server, $user, $pwd)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/MySQL.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/MySQL.php#L255)


#### Arguments
* $server **mixed**
* $user **mixed**
* $pwd **mixed**



### <a name="method-checkConnection"></a>checkConnection

```php
integer DbCore::checkConnection(string $server, string $user, string $pwd, string $db, boolean $new_db_link, boolean $engine, $timeout)
```

Try a connection to te database



* Visibility: **public**
* This method is **static**.
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 683](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L683)


#### Arguments
* $server **string** - Server address
* $user **string** - Login for database connection
* $pwd **string** - Password for database connection
* $db **string** - Database name
* $new_db_link **boolean**
* $engine **boolean**
* $timeout **mixed**



### <a name="method-checkCreatePrivilege"></a>checkCreatePrivilege

```php
mixed MySQLCore::checkCreatePrivilege($server, $user, $pwd, $db, $prefix, $engine)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/MySQL.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/MySQL.php#L221)


#### Arguments
* $server **mixed**
* $user **mixed**
* $pwd **mixed**
* $db **mixed**
* $prefix **mixed**
* $engine **mixed**



### <a name="method-checkEncoding"></a>checkEncoding

```php
integer DbCore::checkEncoding(string $server, string $user, string $pwd)
```

Try a connection to te database



* Visibility: **public**
* This method is **static**.
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 696](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L696)


#### Arguments
* $server **string** - Server address
* $user **string** - Login for database connection
* $pwd **string** - Password for database connection



### <a name="method-connect"></a>connect

```php
mixed MySQLCore::connect()
```





* Visibility: **public**
* Source: [classes/db/MySQL.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/MySQL.php#L32)




### <a name="method-createDatabase"></a>createDatabase

```php
mixed MySQLCore::createDatabase($host, $user, $password, $dbname, $dropit)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/MySQL.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/MySQL.php#L50)


#### Arguments
* $host **mixed**
* $user **mixed**
* $password **mixed**
* $dbname **mixed**
* $dropit **mixed**



### <a name="method-delete"></a>delete

```php
boolean DbCore::delete(string $table, string $where, integer $limit, boolean $use_cache, boolean $add_prefix)
```

Execute a DELETE query



* Visibility: **public**
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 455](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L455)


#### Arguments
* $table **string** - Name of the table to delete
* $where **string** - WHERE clause on query
* $limit **integer** - Number max of rows to delete
* $use_cache **boolean** - Use cache or not
* $add_prefix **boolean** - Add or not _DB_PREFIX_ before table name



### <a name="method-disconnect"></a>disconnect

```php
mixed MySQLCore::disconnect()
```





* Visibility: **public**
* Source: [classes/db/MySQL.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/MySQL.php#L62)




### <a name="method-displayError"></a>displayError

```php
mixed DbCore::displayError(boolean $sql)
```

Display last SQL error



* Visibility: **public**
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 633](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L633)


#### Arguments
* $sql **boolean**



### <a name="method-ds"></a>ds

```php
mixed DbCore::ds($sql, $use_cache)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 748](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L748)


#### Arguments
* $sql **mixed**
* $use_cache **mixed**



### <a name="method-escape"></a>escape

```php
string DbCore::escape(string $string, boolean $html_ok)
```

Sanitize data which will be injected into SQL query



* Visibility: **public**
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 658](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L658)


#### Arguments
* $string **string** - SQL data which will be injected into SQL query
* $html_ok **boolean** - Does data contain HTML code ? (optional)



### <a name="method-execute"></a>execute

```php
boolean DbCore::execute(string $sql, boolean $use_cache)
```

Execute a query



* Visibility: **public**
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 475](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L475)


#### Arguments
* $sql **string**
* $use_cache **boolean**



### <a name="method-executeS"></a>executeS

```php
array DbCore::executeS(string $sql, boolean $array, boolean $use_cache)
```

ExecuteS return the result of $sql as array



* Visibility: **public**
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 494](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L494)


#### Arguments
* $sql **string** - query to execute
* $array **boolean** - return an array instead of a mysql_result object (deprecated since 1.5.0, use query method instead)
* $use_cache **boolean** - if query has been already executed, use its result



### <a name="method-getAll"></a>getAll

```php
mixed MySQLCore::getAll($result)
```





* Visibility: **protected**
* Source: [classes/db/MySQL.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/MySQL.php#L155)


#### Arguments
* $result **mixed**



### <a name="method-getBestEngine"></a>getBestEngine

```php
mixed MySQLCore::getBestEngine()
```





* Visibility: **public**
* Source: [classes/db/MySQL.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/MySQL.php#L196)




### <a name="method-getClass"></a>getClass

```php
string DbCore::getClass()
```

Get child layer class



* Visibility: **public**
* This method is **static**.
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 237](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L237)




### <a name="method-getInstance"></a>getInstance

```php
\Db DbCore::getInstance(boolean $master)
```

Get Db object instance



* Visibility: **public**
* This method is **static**.
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 184](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L184)


#### Arguments
* $master **boolean** - Decides whether the connection to be returned by the master server or the slave server



### <a name="method-getMsgError"></a>getMsgError

```php
mixed MySQLCore::getMsgError($query)
```





* Visibility: **public**
* Source: [classes/db/MySQL.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/MySQL.php#L115)


#### Arguments
* $query **mixed**



### <a name="method-getNumberError"></a>getNumberError

```php
mixed MySQLCore::getNumberError()
```





* Visibility: **public**
* Source: [classes/db/MySQL.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/MySQL.php#L123)




### <a name="method-getRow"></a>getRow

```php
array DbCore::getRow(mixed $sql, boolean $use_cache)
```

getRow return an associative array containing the first row of the query
This function automatically add "limit 1" to the query



* Visibility: **public**
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 545](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L545)


#### Arguments
* $sql **mixed** - the select query (without &quot;LIMIT 1&quot;)
* $use_cache **boolean** - find it in cache first



### <a name="method-getValue"></a>getValue

```php
mixed DbCore::getValue(mixed $sql, boolean $use_cache)
```

getValue return the first item of a select query.



* Visibility: **public**
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 578](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L578)


#### Arguments
* $sql **mixed**
* $use_cache **boolean**



### <a name="method-getVersion"></a>getVersion

```php
mixed MySQLCore::getVersion()
```





* Visibility: **public**
* Source: [classes/db/MySQL.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/MySQL.php#L131)




### <a name="method-hasTableWithSamePrefix"></a>hasTableWithSamePrefix

```php
mixed MySQLCore::hasTableWithSamePrefix($server, $user, $pwd, $db, $prefix)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/MySQL.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/MySQL.php#L170)


#### Arguments
* $server **mixed**
* $user **mixed**
* $pwd **mixed**
* $db **mixed**
* $prefix **mixed**



### <a name="method-insert"></a>insert

```php
boolean DbCore::insert(string $table, array $data, boolean $null_values, boolean $use_cache, integer $type, boolean $add_prefix)
```

Execute an INSERT query



* Visibility: **public**
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 355](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L355)


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





* Visibility: **protected**
* This method is **static**.
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 219](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L219)




### <a name="method-nextRow"></a>nextRow

```php
mixed MySQLCore::nextRow($result)
```





* Visibility: **public**
* Source: [classes/db/MySQL.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/MySQL.php#L78)


#### Arguments
* $result **mixed**



### <a name="method-numRows"></a>numRows

```php
integer DbCore::numRows()
```

Get number of rows for last result



* Visibility: **public**
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 593](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L593)




### <a name="method-ps"></a>ps

```php
mixed DbCore::ps($sql, $use_cache)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 738](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L738)


#### Arguments
* $sql **mixed**
* $use_cache **mixed**



### <a name="method-q"></a>q

```php
mixed DbCore::q(string $sql, boolean $use_cache)
```

Execute a query



* Visibility: **protected**
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 614](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L614)


#### Arguments
* $sql **string**
* $use_cache **boolean**



### <a name="method-query"></a>query

```php
mixed DbCore::query(string $sql)
```

Execute a query and get result ressource



* Visibility: **public**
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 326](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L326)


#### Arguments
* $sql **string**



### <a name="method-s"></a>s

```php
mixed DbCore::s($sql, $use_cache)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 729](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L729)


#### Arguments
* $sql **mixed**
* $use_cache **mixed**



### <a name="method-set_db"></a>set_db

```php
mixed MySQLCore::set_db($db_name)
```





* Visibility: **public**
* Source: [classes/db/MySQL.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/MySQL.php#L147)


#### Arguments
* $db_name **mixed**



### <a name="method-tryToConnect"></a>tryToConnect

```php
mixed MySQLCore::tryToConnect($server, $user, $pwd, $db, $newDbLink, $engine, $timeout)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/MySQL.php line 185](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/MySQL.php#L185)


#### Arguments
* $server **mixed**
* $user **mixed**
* $pwd **mixed**
* $db **mixed**
* $newDbLink **mixed**
* $engine **mixed**
* $timeout **mixed**



### <a name="method-tryUTF8"></a>tryUTF8

```php
mixed MySQLCore::tryUTF8($server, $user, $pwd)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/MySQL.php line 247](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/MySQL.php#L247)


#### Arguments
* $server **mixed**
* $user **mixed**
* $pwd **mixed**



### <a name="method-update"></a>update

```php
boolean DbCore::update(string $table, array $data, string $where, integer $limit, boolean $null_values, boolean $use_cache, boolean $add_prefix)
```





* Visibility: **public**
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 418](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/db/Db.php#L418)


#### Arguments
* $table **string** - Table name without prefix
* $data **array** - Data to insert as associative array. If $data is a list of arrays, multiple insert will be done
* $where **string** - WHERE condition
* $limit **integer**
* $null_values **boolean** - If we want to use NULL values instead of empty quotes
* $use_cache **boolean**
* $add_prefix **boolean** - Add or not _DB_PREFIX_ before table name


