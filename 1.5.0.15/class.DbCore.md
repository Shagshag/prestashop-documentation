Class DbCore
=====================





* Class name: DbCore
* This is an **abstract** class
* Source: [classes/db/Db.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L31)


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
* [checkEncoding](#method-checkEncoding)
* [connect](#method-connect)
* [delete](#method-delete)
* [disconnect](#method-disconnect)
* [displayError](#method-displayError)
* [ds](#method-ds)
* [escape](#method-escape)
* [execute](#method-execute)
* [executeS](#method-executeS)
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



* Source: [classes/db/Db.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L36).


### <a name="constant-INSERT_IGNORE"></a>INSERT_IGNORE

```php
const INSERT_IGNORE = 2
```





* Source: [classes/db/Db.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L37).


### <a name="constant-REPLACE"></a>REPLACE

```php
const REPLACE = 3
```





* Source: [classes/db/Db.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L38).


Properties
----------


### <a name="property-$_servers"></a>$_servers

```php
protected array $_servers = array(array('server' => _DB_SERVER_, 'user' => _DB_USER_, 'password' => _DB_PASSWD_, 'database' => _DB_NAME_))
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/db/Db.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L83).


### <a name="property-$database"></a>$database

```php
protected string $database
```





* Visibility: **protected**
* Source: [classes/db/Db.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L58).


### <a name="property-$instance"></a>$instance

```php
protected array $instance = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/db/Db.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L78).


### <a name="property-$is_cache_enabled"></a>$is_cache_enabled

```php
protected boolean $is_cache_enabled
```





* Visibility: **protected**
* Source: [classes/db/Db.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L63).


### <a name="property-$last_cached"></a>$last_cached

```php
protected string $last_cached
```

Last cached query



* Visibility: **protected**
* Source: [classes/db/Db.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L102).


### <a name="property-$last_query"></a>$last_query

```php
protected string $last_query
```

Store last executed query



* Visibility: **protected**
* Source: [classes/db/Db.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L95).


### <a name="property-$link"></a>$link

```php
protected mixed $link
```





* Visibility: **protected**
* Source: [classes/db/Db.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L68).


### <a name="property-$password"></a>$password

```php
protected string $password
```





* Visibility: **protected**
* Source: [classes/db/Db.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L53).


### <a name="property-$result"></a>$result

```php
protected mixed $result
```





* Visibility: **protected**
* Source: [classes/db/Db.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L73).


### <a name="property-$server"></a>$server

```php
protected string $server
```





* Visibility: **protected**
* Source: [classes/db/Db.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L43).


### <a name="property-$user"></a>$user

```php
protected string $user
```





* Visibility: **protected**
* Source: [classes/db/Db.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L48).


Methods
-------


### <a name="method-Affected_Rows"></a>Affected_Rows

```php
mixed DbCore::Affected_Rows()
```

Get number of affected rows in previous database operation



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L137)




### <a name="method-Insert_ID"></a>Insert_ID

```php
mixed DbCore::Insert_ID()
```

Get the ID generated from the previous INSERT operation



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L132)




### <a name="method-__construct"></a>__construct

```php
mixed DbCore::__construct(string $server, string $user, string $password, string $database, boolean $connect)
```

Instantiate database connection



* Visibility: **public**
* Source: [classes/db/Db.php line 231](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L231)


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
* Source: [classes/db/Db.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L249)




### <a name="method-_escape"></a>_escape

```php
string DbCore::_escape(string $str)
```

Protect string against SQL injections



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L159)


#### Arguments
* $str **string**



### <a name="method-_numRows"></a>_numRows

```php
mixed DbCore::_numRows(mixed $result)
```

Get number of rows in a result



* Visibility: **protected**
* This method is **abstract**.
* Source: [classes/db/Db.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L127)


#### Arguments
* $result **mixed**



### <a name="method-_query"></a>_query

```php
mixed DbCore::_query(string $sql)
```

Execute a query and get result resource



* Visibility: **protected**
* This method is **abstract**.
* Source: [classes/db/Db.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L120)


#### Arguments
* $sql **string**



### <a name="method-autoExecute"></a>autoExecute

```php
mixed DbCore::autoExecute($table, $data, $type, $where, $limit, $use_cache, $use_null)
```





* Visibility: **public**
* Source: [classes/db/Db.php line 258](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L258)


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
* Source: [classes/db/Db.php line 290](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L290)


#### Arguments
* $table **string** - Table where insert/update data
* $values **string** - Data to insert/update
* $type **string** - INSERT or UPDATE
* $where **string** - WHERE clause, only for UPDATE (optional)
* $limit **integer** - LIMIT clause (optional)



### <a name="method-checkConnection"></a>checkConnection

```php
integer DbCore::checkConnection(string $server, string $user, string $pwd, string $db, boolean $new_db_link, boolean $engine)
```

Try a connection to te database



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 640](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L640)


#### Arguments
* $server **string** - Server address
* $user **string** - Login for database connection
* $pwd **string** - Password for database connection
* $db **string** - Database name
* $new_db_link **boolean**
* $engine **boolean**



### <a name="method-checkEncoding"></a>checkEncoding

```php
integer DbCore::checkEncoding(string $server, string $user, string $pwd)
```

Try a connection to te database



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 653](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L653)


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
* Source: [classes/db/Db.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L107)




### <a name="method-delete"></a>delete

```php
boolean DbCore::delete(string $table, string $where, integer $limit, boolean $use_cache, boolean $add_prefix)
```

Execute a DELETE query



* Visibility: **public**
* Source: [classes/db/Db.php line 423](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L423)


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
* Source: [classes/db/Db.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L112)




### <a name="method-displayError"></a>displayError

```php
mixed DbCore::displayError(boolean $sql)
```

Display last SQL error



* Visibility: **public**
* Source: [classes/db/Db.php line 593](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L593)


#### Arguments
* $sql **boolean**



### <a name="method-ds"></a>ds

```php
mixed DbCore::ds($sql, $use_cache)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 696](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L696)


#### Arguments
* $sql **mixed**
* $use_cache **mixed**



### <a name="method-escape"></a>escape

```php
string DbCore::escape(string $string, boolean $html_ok)
```

Sanitize data which will be injected into SQL query



* Visibility: **public**
* Source: [classes/db/Db.php line 615](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L615)


#### Arguments
* $string **string** - SQL data which will be injected into SQL query
* $html_ok **boolean** - Does data contain HTML code ? (optional)



### <a name="method-execute"></a>execute

```php
boolean DbCore::execute(string $sql, boolean $use_cache)
```

Execute a query



* Visibility: **public**
* Source: [classes/db/Db.php line 443](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L443)


#### Arguments
* $sql **string**
* $use_cache **boolean**



### <a name="method-executeS"></a>executeS

```php
array DbCore::executeS(string $sql, boolean $array, boolean $use_cache)
```

ExecuteS return the result of $sql as array



* Visibility: **public**
* Source: [classes/db/Db.php line 462](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L462)


#### Arguments
* $sql **string** - query to execute
* $array **boolean** - return an array instead of a mysql_result object (deprecated since 1.5.0, use query method instead)
* $use_cache **boolean** - if query has been already executed, use its result



### <a name="method-getClass"></a>getClass

```php
string DbCore::getClass()
```

Get child layer class



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L212)




### <a name="method-getInstance"></a>getInstance

```php
\Db DbCore::getInstance(boolean $master)
```

Get Db object instance



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L180)


#### Arguments
* $master **boolean** - Decides whether the connection to be returned by the master server or the slave server



### <a name="method-getMsgError"></a>getMsgError

```php
mixed DbCore::getMsgError()
```

Returns the text of the error message from previous database operation



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L164)




### <a name="method-getNumberError"></a>getNumberError

```php
mixed DbCore::getNumberError()
```

Returns the number of the error from previous database operation



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L169)




### <a name="method-getRow"></a>getRow

```php
array DbCore::getRow(mixed $sql, boolean $use_cache)
```

getRow return an associative array containing the first row of the query
This function automatically add "limit 1" to the query



* Visibility: **public**
* Source: [classes/db/Db.php line 508](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L508)


#### Arguments
* $sql **mixed** - the select query (without &quot;LIMIT 1&quot;)
* $use_cache **boolean** - find it in cache first



### <a name="method-getValue"></a>getValue

```php
mixed DbCore::getValue(mixed $sql, boolean $use_cache)
```

getValue return the first item of a select query.



* Visibility: **public**
* Source: [classes/db/Db.php line 540](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L540)


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
* Source: [classes/db/Db.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L151)




### <a name="method-hasTableWithSamePrefix"></a>hasTableWithSamePrefix

```php
boolean DbCore::hasTableWithSamePrefix(string $server, string $user, string $pwd, string $db, string $prefix)
```

Try a connection to the database and check if at least one table with same prefix exists



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 668](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L668)


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
* Source: [classes/db/Db.php line 323](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L323)


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
* Source: [classes/db/Db.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L144)


#### Arguments
* $result **mixed**



### <a name="method-numRows"></a>numRows

```php
integer DbCore::numRows()
```

Get number of rows for last result



* Visibility: **public**
* Source: [classes/db/Db.php line 555](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L555)




### <a name="method-ps"></a>ps

```php
mixed DbCore::ps($sql, $use_cache)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 685](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L685)


#### Arguments
* $sql **mixed**
* $use_cache **mixed**



### <a name="method-q"></a>q

```php
mixed DbCore::q(string $sql, boolean $use_cache)
```

Execute a query



* Visibility: **protected**
* Source: [classes/db/Db.php line 576](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L576)


#### Arguments
* $sql **string**
* $use_cache **boolean**



### <a name="method-query"></a>query

```php
mixed DbCore::query(string $sql)
```

Execute a query and get result ressource



* Visibility: **public**
* Source: [classes/db/Db.php line 301](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L301)


#### Arguments
* $sql **string**



### <a name="method-s"></a>s

```php
mixed DbCore::s($sql, $use_cache)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 676](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L676)


#### Arguments
* $sql **mixed**
* $use_cache **mixed**



### <a name="method-set_db"></a>set_db

```php
mixed DbCore::set_db($db_name)
```





* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L172)


#### Arguments
* $db_name **mixed**



### <a name="method-update"></a>update

```php
boolean DbCore::update(string $table, array $data, string $where, integer $limit, boolean $null_values, boolean $use_cache, boolean $add_prefix)
```





* Visibility: **public**
* Source: [classes/db/Db.php line 386](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/db/Db.php#L386)


#### Arguments
* $table **string** - Table name without prefix
* $data **array** - Data to insert as associative array. If $data is a list of arrays, multiple insert will be done
* $where **string** - WHERE condition
* $limit **integer**
* $null_values **boolean** - If we want to use NULL values instead of empty quotes
* $use_cache **boolean**
* $add_prefix **boolean** - Add or not _DB_PREFIX_ before table name


