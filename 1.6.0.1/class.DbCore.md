Class DbCore
=====================





* Class name: DbCore
* This is an **abstract** class
* Source: [classes/db/Db.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L30)


Contents
--------

### Constants

* [INSERT](#constant-INSERT)
* [INSERT_IGNORE](#constant-INSERT_IGNORE)
* [REPLACE](#constant-REPLACE)

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
* [checkConnection](#method-checkConnection)
* [checkCreatePrivilege](#method-checkCreatePrivilege)
* [checkEncoding](#method-checkEncoding)
* [connect](#method-connect)
* [delete](#method-delete)
* [disconnect](#method-disconnect)
* [displayError](#method-displayError)
* [ds](#method-ds)
* [escape](#method-escape)
* [execute](#method-execute)
* [executeS](#method-executeS)
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
* [nextRow](#method-nextRow)
* [numRows](#method-numRows)
* [ps](#method-ps)
* [q](#method-q)
* [query](#method-query)
* [s](#method-s)
* [set_db](#method-set_db)
* [update](#method-update)


Constants
----------


### <a name="constant-INSERT"></a>INSERT

```php
const INSERT = 1
```

Constants used by insert() method



* Source: [classes/db/Db.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L35).


### <a name="constant-INSERT_IGNORE"></a>INSERT_IGNORE

```php
const INSERT_IGNORE = 2
```





* Source: [classes/db/Db.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L36).


### <a name="constant-REPLACE"></a>REPLACE

```php
const REPLACE = 3
```





* Source: [classes/db/Db.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L37).


Properties
----------


### <a name="property-$_servers"></a>$_servers

```php
protected array $_servers = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/db/Db.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L82).


### <a name="property-$database"></a>$database

```php
protected string $database
```





* Visibility: **protected**
* Source: [classes/db/Db.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L57).


### <a name="property-$instance"></a>$instance

```php
protected array $instance = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/db/Db.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L77).


### <a name="property-$is_cache_enabled"></a>$is_cache_enabled

```php
protected boolean $is_cache_enabled
```





* Visibility: **protected**
* Source: [classes/db/Db.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L62).


### <a name="property-$last_cached"></a>$last_cached

```php
protected string $last_cached
```

Last cached query



* Visibility: **protected**
* Source: [classes/db/Db.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L96).


### <a name="property-$last_query"></a>$last_query

```php
protected string $last_query
```

Store last executed query



* Visibility: **protected**
* Source: [classes/db/Db.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L89).


### <a name="property-$link"></a>$link

```php
protected mixed $link
```





* Visibility: **protected**
* Source: [classes/db/Db.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L67).


### <a name="property-$password"></a>$password

```php
protected string $password
```





* Visibility: **protected**
* Source: [classes/db/Db.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L52).


### <a name="property-$result"></a>$result

```php
protected mixed $result
```





* Visibility: **protected**
* Source: [classes/db/Db.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L72).


### <a name="property-$server"></a>$server

```php
protected string $server
```





* Visibility: **protected**
* Source: [classes/db/Db.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L42).


### <a name="property-$user"></a>$user

```php
protected string $user
```





* Visibility: **protected**
* Source: [classes/db/Db.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L47).


Methods
-------


### <a name="method-Affected_Rows"></a>Affected_Rows

```php
mixed DbCore::Affected_Rows()
```

Get number of affected rows in previous database operation



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L131)




### <a name="method-Insert_ID"></a>Insert_ID

```php
mixed DbCore::Insert_ID()
```

Get the ID generated from the previous INSERT operation



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L126)




### <a name="method-__construct"></a>__construct

```php
mixed DbCore::__construct(string $server, string $user, string $password, string $database, boolean $connect)
```

Instantiate database connection



* Visibility: **public**
* Source: [classes/db/Db.php line 236](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L236)


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
* Source: [classes/db/Db.php line 254](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L254)




### <a name="method-_escape"></a>_escape

```php
string DbCore::_escape(string $str)
```

Protect string against SQL injections



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L153)


#### Arguments
* $str **string**



### <a name="method-_numRows"></a>_numRows

```php
mixed DbCore::_numRows(mixed $result)
```

Get number of rows in a result



* Visibility: **protected**
* This method is **abstract**.
* Source: [classes/db/Db.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L121)


#### Arguments
* $result **mixed**



### <a name="method-_query"></a>_query

```php
mixed DbCore::_query(string $sql)
```

Execute a query and get result resource



* Visibility: **protected**
* This method is **abstract**.
* Source: [classes/db/Db.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L114)


#### Arguments
* $sql **string**



### <a name="method-autoExecute"></a>autoExecute

```php
mixed DbCore::autoExecute($table, $data, $type, $where, $limit, $use_cache, $use_null)
```





* Visibility: **public**
* Source: [classes/db/Db.php line 263](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L263)


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
* Source: [classes/db/Db.php line 295](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L295)


#### Arguments
* $table **string** - Table where insert/update data
* $values **string** - Data to insert/update
* $type **string** - INSERT or UPDATE
* $where **string** - WHERE clause, only for UPDATE (optional)
* $limit **integer** - LIMIT clause (optional)



### <a name="method-checkConnection"></a>checkConnection

```php
integer DbCore::checkConnection(string $server, string $user, string $pwd, string $db, boolean $new_db_link, boolean $engine, $timeout)
```

Try a connection to te database



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 650](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L650)


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
mixed DbCore::checkCreatePrivilege($server, $user, $pwd, $db, $prefix, $engine)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 683](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L683)


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
* Source: [classes/db/Db.php line 663](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L663)


#### Arguments
* $server **string** - Server address
* $user **string** - Login for database connection
* $pwd **string** - Password for database connection



### <a name="method-connect"></a>connect

```php
mixed DbCore::connect()
```

Open a connection



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L101)




### <a name="method-delete"></a>delete

```php
boolean DbCore::delete(string $table, string $where, integer $limit, boolean $use_cache, boolean $add_prefix)
```

Execute a DELETE query



* Visibility: **public**
* Source: [classes/db/Db.php line 428](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L428)


#### Arguments
* $table **string** - Name of the table to delete
* $where **string** - WHERE clause on query
* $limit **integer** - Number max of rows to delete
* $use_cache **boolean** - Use cache or not
* $add_prefix **boolean** - Add or not _DB_PREFIX_ before table name



### <a name="method-disconnect"></a>disconnect

```php
mixed DbCore::disconnect()
```

Close a connection



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L106)




### <a name="method-displayError"></a>displayError

```php
mixed DbCore::displayError(boolean $sql)
```

Display last SQL error



* Visibility: **public**
* Source: [classes/db/Db.php line 600](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L600)


#### Arguments
* $sql **boolean**



### <a name="method-ds"></a>ds

```php
mixed DbCore::ds($sql, $use_cache)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 711](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L711)


#### Arguments
* $sql **mixed**
* $use_cache **mixed**



### <a name="method-escape"></a>escape

```php
string DbCore::escape(string $string, boolean $html_ok)
```

Sanitize data which will be injected into SQL query



* Visibility: **public**
* Source: [classes/db/Db.php line 625](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L625)


#### Arguments
* $string **string** - SQL data which will be injected into SQL query
* $html_ok **boolean** - Does data contain HTML code ? (optional)



### <a name="method-execute"></a>execute

```php
boolean DbCore::execute(string $sql, boolean $use_cache)
```

Execute a query



* Visibility: **public**
* Source: [classes/db/Db.php line 448](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L448)


#### Arguments
* $sql **string**
* $use_cache **boolean**



### <a name="method-executeS"></a>executeS

```php
array DbCore::executeS(string $sql, boolean $array, boolean $use_cache)
```

ExecuteS return the result of $sql as array



* Visibility: **public**
* Source: [classes/db/Db.php line 467](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L467)


#### Arguments
* $sql **string** - query to execute
* $array **boolean** - return an array instead of a mysql_result object (deprecated since 1.5.0, use query method instead)
* $use_cache **boolean** - if query has been already executed, use its result



### <a name="method-getBestEngine"></a>getBestEngine

```php
mixed DbCore::getBestEngine()
```





* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L168)




### <a name="method-getClass"></a>getClass

```php
string DbCore::getClass()
```

Get child layer class



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L217)




### <a name="method-getInstance"></a>getInstance

```php
\Db DbCore::getInstance(boolean $master)
```

Get Db object instance



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L176)


#### Arguments
* $master **boolean** - Decides whether the connection to be returned by the master server or the slave server



### <a name="method-getMsgError"></a>getMsgError

```php
mixed DbCore::getMsgError()
```

Returns the text of the error message from previous database operation



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L158)




### <a name="method-getNumberError"></a>getNumberError

```php
mixed DbCore::getNumberError()
```

Returns the number of the error from previous database operation



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L163)




### <a name="method-getRow"></a>getRow

```php
array DbCore::getRow(mixed $sql, boolean $use_cache)
```

getRow return an associative array containing the first row of the query
This function automatically add "limit 1" to the query



* Visibility: **public**
* Source: [classes/db/Db.php line 513](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L513)


#### Arguments
* $sql **mixed** - the select query (without &quot;LIMIT 1&quot;)
* $use_cache **boolean** - find it in cache first



### <a name="method-getValue"></a>getValue

```php
mixed DbCore::getValue(mixed $sql, boolean $use_cache)
```

getValue return the first item of a select query.



* Visibility: **public**
* Source: [classes/db/Db.php line 545](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L545)


#### Arguments
* $sql **mixed**
* $use_cache **boolean**



### <a name="method-getVersion"></a>getVersion

```php
string DbCore::getVersion()
```

Get database version



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L145)




### <a name="method-hasTableWithSamePrefix"></a>hasTableWithSamePrefix

```php
boolean DbCore::hasTableWithSamePrefix(string $server, string $user, string $pwd, string $db, string $prefix)
```

Try a connection to the database and check if at least one table with same prefix exists



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 678](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L678)


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

Execute an INSERT query



* Visibility: **public**
* Source: [classes/db/Db.php line 328](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L328)


#### Arguments
* $table **string** - Table name without prefix
* $data **array** - Data to insert as associative array. If $data is a list of arrays, multiple insert will be done
* $null_values **boolean** - If we want to use NULL values instead of empty quotes
* $use_cache **boolean**
* $type **integer** - Must be Db::INSERT or Db::INSERT_IGNORE or Db::REPLACE
* $add_prefix **boolean** - Add or not _DB_PREFIX_ before table name



### <a name="method-nextRow"></a>nextRow

```php
mixed DbCore::nextRow(mixed $result)
```

Get next row for a query which doesn't return an array



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L138)


#### Arguments
* $result **mixed**



### <a name="method-numRows"></a>numRows

```php
integer DbCore::numRows()
```

Get number of rows for last result



* Visibility: **public**
* Source: [classes/db/Db.php line 560](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L560)




### <a name="method-ps"></a>ps

```php
mixed DbCore::ps($sql, $use_cache)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 700](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L700)


#### Arguments
* $sql **mixed**
* $use_cache **mixed**



### <a name="method-q"></a>q

```php
mixed DbCore::q(string $sql, boolean $use_cache)
```

Execute a query



* Visibility: **protected**
* Source: [classes/db/Db.php line 581](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L581)


#### Arguments
* $sql **string**
* $use_cache **boolean**



### <a name="method-query"></a>query

```php
mixed DbCore::query(string $sql)
```

Execute a query and get result ressource



* Visibility: **public**
* Source: [classes/db/Db.php line 306](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L306)


#### Arguments
* $sql **string**



### <a name="method-s"></a>s

```php
mixed DbCore::s($sql, $use_cache)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 691](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L691)


#### Arguments
* $sql **mixed**
* $use_cache **mixed**



### <a name="method-set_db"></a>set_db

```php
mixed DbCore::set_db($db_name)
```





* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L166)


#### Arguments
* $db_name **mixed**



### <a name="method-update"></a>update

```php
boolean DbCore::update(string $table, array $data, string $where, integer $limit, boolean $null_values, boolean $use_cache, boolean $add_prefix)
```





* Visibility: **public**
* Source: [classes/db/Db.php line 391](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/db/Db.php#L391)


#### Arguments
* $table **string** - Table name without prefix
* $data **array** - Data to insert as associative array. If $data is a list of arrays, multiple insert will be done
* $where **string** - WHERE condition
* $limit **integer**
* $null_values **boolean** - If we want to use NULL values instead of empty quotes
* $use_cache **boolean**
* $add_prefix **boolean** - Add or not _DB_PREFIX_ before table name


