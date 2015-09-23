Class DbCore
=====================





* Class name: DbCore
* This is an **abstract** class
* Source: [classes/db/Db.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L31)


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
* [nextRow](#method-nextRow)
* [numRows](#method-numRows)
* [ps](#method-ps)
* [q](#method-q)
* [query](#method-query)
* [s](#method-s)
* [set_db](#method-set_db)




Properties
----------


### <a name="property-$_servers"></a>$_servers

```php
protected array $_servers = array(array('server' => _DB_SERVER_, 'user' => _DB_USER_, 'password' => _DB_PASSWD_, 'database' => _DB_NAME_))
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/db/Db.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L76).


### <a name="property-$database"></a>$database

```php
protected string $database
```





* Visibility: **protected**
* Source: [classes/db/Db.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L51).


### <a name="property-$instance"></a>$instance

```php
protected array $instance = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/db/Db.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L71).


### <a name="property-$is_cache_enabled"></a>$is_cache_enabled

```php
protected boolean $is_cache_enabled
```





* Visibility: **protected**
* Source: [classes/db/Db.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L56).


### <a name="property-$last_cached"></a>$last_cached

```php
protected string $last_cached
```

Last cached query



* Visibility: **protected**
* Source: [classes/db/Db.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L95).


### <a name="property-$last_query"></a>$last_query

```php
protected string $last_query
```

Store last executed query



* Visibility: **protected**
* Source: [classes/db/Db.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L88).


### <a name="property-$link"></a>$link

```php
protected mixed $link
```





* Visibility: **protected**
* Source: [classes/db/Db.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L61).


### <a name="property-$password"></a>$password

```php
protected string $password
```





* Visibility: **protected**
* Source: [classes/db/Db.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L46).


### <a name="property-$result"></a>$result

```php
protected mixed $result
```





* Visibility: **protected**
* Source: [classes/db/Db.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L66).


### <a name="property-$server"></a>$server

```php
protected string $server
```





* Visibility: **protected**
* Source: [classes/db/Db.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L36).


### <a name="property-$user"></a>$user

```php
protected string $user
```





* Visibility: **protected**
* Source: [classes/db/Db.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L41).


Methods
-------


### <a name="method-Affected_Rows"></a>Affected_Rows

```php
mixed DbCore::Affected_Rows()
```

Get number of affected rows in previous databse operation



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L128)




### <a name="method-Insert_ID"></a>Insert_ID

```php
mixed DbCore::Insert_ID()
```

Get the ID generated from the previous INSERT operation



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L123)




### <a name="method-__construct"></a>__construct

```php
mixed DbCore::__construct(string $server, string $user, string $password, string $database, boolean $connect)
```

Instantiate database connection



* Visibility: **public**
* Source: [classes/db/Db.php line 220](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L220)


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
* Source: [classes/db/Db.php line 238](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L238)




### <a name="method-_escape"></a>_escape

```php
string DbCore::_escape(string $str)
```

Protect string against SQL injections



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L148)


#### Arguments
* $str **string**



### <a name="method-_numRows"></a>_numRows

```php
mixed DbCore::_numRows($result)
```

Get number of rows in a result



* Visibility: **protected**
* This method is **abstract**.
* Source: [classes/db/Db.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L118)


#### Arguments
* $result **mixed**



### <a name="method-_query"></a>_query

```php
mixed DbCore::_query(string $sql)
```

Execute a query and get result ressource



* Visibility: **protected**
* This method is **abstract**.
* Source: [classes/db/Db.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L113)


#### Arguments
* $sql **string**



### <a name="method-autoExecute"></a>autoExecute

```php
mixed|boolean DbCore::autoExecute(string $table, string $data, string $type, string $where, string $limit, $use_cache, boolean $use_null)
```

Filter SQL query within a blacklist



* Visibility: **public**
* Source: [classes/db/Db.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L255)


#### Arguments
* $table **string** - Table where insert/update data
* $data **string** - Data to insert/update
* $type **string** - INSERT or INSERT IGNORE or UPDATE
* $where **string** - WHERE clause, only for UPDATE (optional)
* $limit **string** - LIMIT clause (optional)
* $use_cache **mixed**
* $use_null **boolean** - If true, replace empty strings and NULL by a NULL value



### <a name="method-autoExecuteWithNullValues"></a>autoExecuteWithNullValues

```php
mixed|boolean DbCore::autoExecuteWithNullValues(string $table, string $values, string $type, string $where, string $limit)
```

Filter SQL query within a blacklist



* Visibility: **public**
* Source: [classes/db/Db.php line 336](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L336)


#### Arguments
* $table **string** - Table where insert/update data
* $values **string** - Data to insert/update
* $type **string** - INSERT or UPDATE
* $where **string** - WHERE clause, only for UPDATE (optional)
* $limit **string** - LIMIT clause (optional)



### <a name="method-checkConnection"></a>checkConnection

```php
integer DbCore::checkConnection(string $server, string $user, string $pwd, string $db, $new_db_link, $engine)
```

Try a connection to te database



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 570](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L570)


#### Arguments
* $server **string** - Server address
* $user **string** - Login for database connection
* $pwd **string** - Password for database connection
* $db **string** - Database name
* $new_db_link **mixed**
* $engine **mixed**



### <a name="method-checkEncoding"></a>checkEncoding

```php
integer DbCore::checkEncoding(string $server, string $user, string $pwd)
```

Try a connection to te database



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 583](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L583)


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
* Source: [classes/db/Db.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L100)




### <a name="method-delete"></a>delete

```php
boolean DbCore::delete(string $table, string $where, integer $limit, boolean $use_cache)
```

Execute a DELETE query



* Visibility: **public**
* Source: [classes/db/Db.php line 365](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L365)


#### Arguments
* $table **string** - Name of the table to delete
* $where **string** - WHERE clause on query
* $limit **integer** - Number max of rows to delete
* $use_cache **boolean** - Use cache or not



### <a name="method-disconnect"></a>disconnect

```php
mixed DbCore::disconnect()
```

Close a connection



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L105)




### <a name="method-displayError"></a>displayError

```php
mixed DbCore::displayError(\unknown_type $sql)
```

Display last SQL error



* Visibility: **public**
* Source: [classes/db/Db.php line 524](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L524)


#### Arguments
* $sql **unknown_type**



### <a name="method-ds"></a>ds

```php
mixed DbCore::ds($sql, $use_cache)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 606](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L606)


#### Arguments
* $sql **mixed**
* $use_cache **mixed**



### <a name="method-escape"></a>escape

```php
string DbCore::escape(string $string, boolean $html_ok)
```

Sanitize data which will be injected into SQL query



* Visibility: **public**
* Source: [classes/db/Db.php line 546](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L546)


#### Arguments
* $string **string** - SQL data which will be injected into SQL query
* $html_ok **boolean** - Does data contain HTML code ? (optional)



### <a name="method-execute"></a>execute

```php
mixed DbCore::execute(string $sql, boolean $use_cache)
```

Execute a query



* Visibility: **public**
* Source: [classes/db/Db.php line 382](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L382)


#### Arguments
* $sql **string**
* $use_cache **boolean**



### <a name="method-executeS"></a>executeS

```php
array DbCore::executeS(string $sql, boolean $array, integer $use_cache)
```

ExecuteS return the result of $sql as array



* Visibility: **public**
* Source: [classes/db/Db.php line 399](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L399)


#### Arguments
* $sql **string** - query to execute
* $array **boolean** - return an array instead of a mysql_result object
* $use_cache **integer** - if query has been already executed, use its result



### <a name="method-getClass"></a>getClass

```php
string DbCore::getClass()
```

Get child layer class



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L201)




### <a name="method-getInstance"></a>getInstance

```php
\Db DbCore::getInstance(boolean $master)
```

Get Db object instance



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L169)


#### Arguments
* $master **boolean** - Decides wether the connection to be returned by the master server or the slave server



### <a name="method-getMsgError"></a>getMsgError

```php
mixed DbCore::getMsgError()
```

Returns the text of the error message from previous database operation



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L153)




### <a name="method-getNumberError"></a>getNumberError

```php
mixed DbCore::getNumberError()
```

Returns the number of the error from previous database operation



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L158)




### <a name="method-getRow"></a>getRow

```php
array DbCore::getRow(mixed $sql, integer $use_cache)
```

getRow return an associative array containing the first row of the query
This function automatically add "limit 1" to the query



* Visibility: **public**
* Source: [classes/db/Db.php line 444](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L444)


#### Arguments
* $sql **mixed** - the select query (without &quot;LIMIT 1&quot;)
* $use_cache **integer** - find it in cache first



### <a name="method-getValue"></a>getValue

```php
void DbCore::getValue(mixed $sql, integer $use_cache)
```

getValue return the first item of a select query.



* Visibility: **public**
* Source: [classes/db/Db.php line 474](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L474)


#### Arguments
* $sql **mixed**
* $use_cache **integer**



### <a name="method-getVersion"></a>getVersion

```php
string DbCore::getVersion()
```

Get database version



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L140)




### <a name="method-nextRow"></a>nextRow

```php
mixed DbCore::nextRow($result)
```

Get next row for a query which doesn't return an array



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L133)


#### Arguments
* $result **mixed**



### <a name="method-numRows"></a>numRows

```php
integer DbCore::numRows()
```

Get number of rows for last result



* Visibility: **public**
* Source: [classes/db/Db.php line 487](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L487)




### <a name="method-ps"></a>ps

```php
mixed DbCore::ps($sql, $use_cache)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 599](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L599)


#### Arguments
* $sql **mixed**
* $use_cache **mixed**



### <a name="method-q"></a>q

```php
mixed DbCore::q(string $sql, boolean $use_cache)
```

Execute a query



* Visibility: **protected**
* Source: [classes/db/Db.php line 507](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L507)


#### Arguments
* $sql **string**
* $use_cache **boolean**



### <a name="method-query"></a>query

```php
mixed DbCore::query(string $sql)
```

Execute a query and get result ressource



* Visibility: **public**
* Source: [classes/db/Db.php line 347](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L347)


#### Arguments
* $sql **string**



### <a name="method-s"></a>s

```php
array DbCore::s($sql, $use_cache)
```

Alias of Db::getInstance()->ExecuteS



* Visibility: **public**
* This method is **static**.
* Source: [classes/db/Db.php line 594](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L594)


#### Arguments
* $sql **mixed**
* $use_cache **mixed**



### <a name="method-set_db"></a>set_db

```php
mixed DbCore::set_db($db_name)
```





* Visibility: **public**
* This method is **abstract**.
* Source: [classes/db/Db.php line 161](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/Db.php#L161)


#### Arguments
* $db_name **mixed**


