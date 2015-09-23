Class DbPDOCore
=====================

This class is currently only here for tests



* Class name: DbPDOCore
* Parent class: [Db](class.DbCore.md)
* Source: [classes/db/DbPDO.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/DbPDO.php#L33)


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
* [tryToConnect](#method-tryToConnect)
* [tryUTF8](#method-tryUTF8)




Properties
----------


### <a name="property-$_servers"></a>$_servers

```php
protected array $_servers = array(array('server' => _DB_SERVER_, 'user' => _DB_USER_, 'password' => _DB_PASSWD_, 'database' => _DB_NAME_))
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L76).


### <a name="property-$database"></a>$database

```php
protected string $database
```





* Visibility: **protected**
* This property is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L51).


### <a name="property-$instance"></a>$instance

```php
protected array $instance = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L71).


### <a name="property-$is_cache_enabled"></a>$is_cache_enabled

```php
protected boolean $is_cache_enabled
```





* Visibility: **protected**
* This property is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L56).


### <a name="property-$last_cached"></a>$last_cached

```php
protected string $last_cached
```

Last cached query



* Visibility: **protected**
* This property is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L95).


### <a name="property-$last_query"></a>$last_query

```php
protected string $last_query
```

Store last executed query



* Visibility: **protected**
* This property is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L88).


### <a name="property-$link"></a>$link

```php
protected mixed $link
```





* Visibility: **protected**
* This property is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L61).


### <a name="property-$password"></a>$password

```php
protected string $password
```





* Visibility: **protected**
* This property is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L46).


### <a name="property-$result"></a>$result

```php
protected mixed $result
```





* Visibility: **protected**
* This property is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L66).


### <a name="property-$server"></a>$server

```php
protected string $server
```





* Visibility: **protected**
* This property is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L36).


### <a name="property-$user"></a>$user

```php
protected string $user
```





* Visibility: **protected**
* This property is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L41).


Methods
-------


### <a name="method-Affected_Rows"></a>Affected_Rows

```php
mixed DbPDOCore::Affected_Rows()
```





* Visibility: **public**
* Source: [classes/db/DbPDO.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/DbPDO.php#L101)




### <a name="method-Insert_ID"></a>Insert_ID

```php
mixed DbPDOCore::Insert_ID()
```





* Visibility: **public**
* Source: [classes/db/DbPDO.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/DbPDO.php#L93)




### <a name="method-__construct"></a>__construct

```php
mixed DbCore::__construct(string $server, string $user, string $password, string $database, boolean $connect)
```

Instantiate database connection



* Visibility: **public**
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 224](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L224)


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
* Source: [classes/db/Db.php line 242](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L242)




### <a name="method-_escape"></a>_escape

```php
mixed DbPDOCore::_escape($str)
```





* Visibility: **public**
* Source: [classes/db/DbPDO.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/DbPDO.php#L135)


#### Arguments
* $str **mixed**



### <a name="method-_numRows"></a>_numRows

```php
mixed DbPDOCore::_numRows($result)
```





* Visibility: **protected**
* Source: [classes/db/DbPDO.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/DbPDO.php#L85)


#### Arguments
* $result **mixed**



### <a name="method-_query"></a>_query

```php
mixed DbPDOCore::_query($sql)
```





* Visibility: **protected**
* Source: [classes/db/DbPDO.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/DbPDO.php#L67)


#### Arguments
* $sql **mixed**



### <a name="method-autoExecute"></a>autoExecute

```php
mixed|boolean DbCore::autoExecute(string $table, string $data, string $type, string $where, integer $limit, boolean $use_cache, boolean $use_null)
```

Filter SQL query within a blacklist



* Visibility: **public**
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 260](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L260)


#### Arguments
* $table **string** - Table where insert/update data
* $data **string** - Data to insert/update
* $type **string** - INSERT or INSERT IGNORE or REPLACE or UPDATE
* $where **string** - WHERE clause, only for UPDATE (optional)
* $limit **integer** - LIMIT clause (optional)
* $use_cache **boolean**
* $use_null **boolean** - If true, replace empty strings and NULL by a NULL value



### <a name="method-autoExecuteWithNullValues"></a>autoExecuteWithNullValues

```php
mixed|boolean DbCore::autoExecuteWithNullValues(string $table, string $values, string $type, string $where, integer $limit)
```

Filter SQL query within a blacklist



* Visibility: **public**
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 341](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L341)


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
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 586](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L586)


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
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 599](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L599)


#### Arguments
* $server **string** - Server address
* $user **string** - Login for database connection
* $pwd **string** - Password for database connection



### <a name="method-connect"></a>connect

```php
mixed DbPDOCore::connect()
```





* Visibility: **public**
* Source: [classes/db/DbPDO.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/DbPDO.php#L38)




### <a name="method-delete"></a>delete

```php
boolean DbCore::delete(string $table, string $where, integer $limit, boolean $use_cache)
```

Execute a DELETE query



* Visibility: **public**
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 372](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L372)


#### Arguments
* $table **string** - Name of the table to delete
* $where **string** - WHERE clause on query
* $limit **integer** - Number max of rows to delete
* $use_cache **boolean** - Use cache or not



### <a name="method-disconnect"></a>disconnect

```php
mixed DbPDOCore::disconnect()
```





* Visibility: **public**
* Source: [classes/db/DbPDO.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/DbPDO.php#L59)




### <a name="method-displayError"></a>displayError

```php
mixed DbCore::displayError(boolean $sql)
```

Display last SQL error



* Visibility: **public**
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 539](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L539)


#### Arguments
* $sql **boolean**



### <a name="method-ds"></a>ds

```php
mixed DbCore::ds($sql, $use_cache)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 616](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L616)


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
* Source: [classes/db/Db.php line 561](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L561)


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
* Source: [classes/db/Db.php line 389](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L389)


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
* Source: [classes/db/Db.php line 408](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L408)


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
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 205](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L205)




### <a name="method-getInstance"></a>getInstance

```php
\Db DbCore::getInstance(boolean $master)
```

Get Db object instance



* Visibility: **public**
* This method is **static**.
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L173)


#### Arguments
* $master **boolean** - Decides wether the connection to be returned by the master server or the slave server



### <a name="method-getMsgError"></a>getMsgError

```php
mixed DbPDOCore::getMsgError($query)
```





* Visibility: **public**
* Source: [classes/db/DbPDO.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/DbPDO.php#L109)


#### Arguments
* $query **mixed**



### <a name="method-getNumberError"></a>getNumberError

```php
mixed DbPDOCore::getNumberError()
```





* Visibility: **public**
* Source: [classes/db/DbPDO.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/DbPDO.php#L118)




### <a name="method-getRow"></a>getRow

```php
array DbCore::getRow(mixed $sql, boolean $use_cache)
```

getRow return an associative array containing the first row of the query
This function automatically add "limit 1" to the query



* Visibility: **public**
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 454](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L454)


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
* Source: [classes/db/Db.php line 486](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L486)


#### Arguments
* $sql **mixed**
* $use_cache **boolean**



### <a name="method-getVersion"></a>getVersion

```php
mixed DbPDOCore::getVersion()
```





* Visibility: **public**
* Source: [classes/db/DbPDO.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/DbPDO.php#L127)




### <a name="method-nextRow"></a>nextRow

```php
mixed DbPDOCore::nextRow($result)
```





* Visibility: **public**
* Source: [classes/db/DbPDO.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/DbPDO.php#L75)


#### Arguments
* $result **mixed**



### <a name="method-numRows"></a>numRows

```php
integer DbCore::numRows()
```

Get number of rows for last result



* Visibility: **public**
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 501](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L501)




### <a name="method-ps"></a>ps

```php
mixed DbCore::ps($sql, $use_cache)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 609](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L609)


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
* Source: [classes/db/Db.php line 522](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L522)


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
* Source: [classes/db/Db.php line 352](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L352)


#### Arguments
* $sql **string**



### <a name="method-s"></a>s

```php
mixed DbCore::s($sql, $use_cache)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [DbCore](class.DbCore.md).
* Source: [classes/db/Db.php line 604](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/Db.php#L604)


#### Arguments
* $sql **mixed**
* $use_cache **mixed**



### <a name="method-set_db"></a>set_db

```php
mixed DbPDOCore::set_db($db_name)
```





* Visibility: **public**
* Source: [classes/db/DbPDO.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/DbPDO.php#L146)


#### Arguments
* $db_name **mixed**



### <a name="method-tryToConnect"></a>tryToConnect

```php
mixed DbPDOCore::tryToConnect($server, $user, $pwd, $db, $newDbLink, $engine)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/DbPDO.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/DbPDO.php#L154)


#### Arguments
* $server **mixed**
* $user **mixed**
* $pwd **mixed**
* $db **mixed**
* $newDbLink **mixed**
* $engine **mixed**



### <a name="method-tryUTF8"></a>tryUTF8

```php
mixed DbPDOCore::tryUTF8($server, $user, $pwd)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/db/DbPDO.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/db/DbPDO.php#L182)


#### Arguments
* $server **mixed**
* $user **mixed**
* $pwd **mixed**


