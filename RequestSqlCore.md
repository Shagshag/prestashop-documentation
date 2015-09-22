RequestSqlCore
===============






* Class name: RequestSqlCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/RequestSql.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/RequestSql.php#L27)





Properties
----------

* [$name](#property-$name)
* [$sql](#property-$sql)
* [$definition](#property-$definition)
* [$tested](#property-$tested)
* [$attributes](#property-$attributes)
* [$error_sql](#property-$error_sql)

Methods
-------
* [getRequestSql](#method-getRequestSql)
* [getRequestSqlById](#method-getRequestSqlById)
* [parsingSql](#method-parsingSql)
* [validateParser](#method-validateParser)
* [validateSql](#method-validateSql)
* [getTables](#method-getTables)
* [getAttributesByTable](#method-getAttributesByTable)
* [cutJoin](#method-cutJoin)
* [cutAttribute](#method-cutAttribute)
* [returnNameTable](#method-returnNameTable)
* [attributExistInTable](#method-attributExistInTable)
* [testedRequired](#method-testedRequired)
* [testedUnauthorized](#method-testedUnauthorized)
* [checkedFrom](#method-checkedFrom)
* [checkedSelect](#method-checkedSelect)
* [checkedWhere](#method-checkedWhere)
* [checkedHaving](#method-checkedHaving)
* [checkedOrder](#method-checkedOrder)
* [checkedGroupBy](#method-checkedGroupBy)
* [checkedLimit](#method-checkedLimit)




Properties
----------


### <a name="property-$name"></a>$name

    public mixed $name





* Visibility: **public**
* This property is defined in [classes/RequestSql.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/RequestSql.php#L29)


### <a name="property-$sql"></a>$sql

    public mixed $sql





* Visibility: **public**
* This property is defined in [classes/RequestSql.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/RequestSql.php#L30)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'request_sql', 'primary' => 'id_request_sql', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isString', 'required' => true, 'size' => 200), 'sql' => array('type' => self::TYPE_SQL, 'validate' => 'isString', 'required' => true)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/RequestSql.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/RequestSql.php#L35)


### <a name="property-$tested"></a>$tested

    public array $tested = array('required' => array('SELECT', 'FROM'), 'option' => array('WHERE', 'ORDER', 'LIMIT', 'HAVING', 'GROUP', 'UNION'), 'operator' => array('AND', '&&', 'BETWEEN', 'AND', 'BINARY', '&', '~', '|', '^', 'CASE', 'WHEN', 'END', 'DIV', '/', '<=>', '=', '>=', '>', 'IS', 'NOT', 'NULL', '<<', '<=', '<', 'LIKE', '-', '%', '!=', '<>', 'REGEXP', '!', '||', 'OR', '+', '>>', 'RLIKE', 'SOUNDS', '*', '-', 'XOR', 'IN'), 'function' => array('AVG', 'SUM', 'COUNT', 'MIN', 'MAX', 'STDDEV', 'STDDEV_SAMP', 'STDDEV_POP', 'VARIANCE', 'VAR_SAMP', 'VAR_POP', 'GROUP_CONCAT', 'BIT_AND', 'BIT_OR', 'BIT_XOR'), 'unauthorized' => array('DELETE', 'ALTER', 'INSERT', 'REPLACE', 'CREATE', 'TRUNCATE', 'OPTIMIZE', 'GRANT', 'REVOKE', 'SHOW', 'HANDLER', 'LOAD', 'ROLLBACK', 'SAVEPOINT', 'UNLOCK', 'INSTALL', 'UNINSTALL', 'ANALZYE', 'BACKUP', 'CHECK', 'CHECKSUM', 'REPAIR', 'RESTORE', 'CACHE', 'DESCRIBE', 'EXPLAIN', 'USE', 'HELP', 'SET', 'DUPLICATE', 'VALUES', 'INTO', 'RENAME', 'CALL', 'PROCEDURE', 'FUNCTION', 'DATABASE', 'SERVER', 'LOGFILE', 'DEFINER', 'RETURNS', 'EVENT', 'TABLESPACE', 'VIEW', 'TRIGGER', 'DATA', 'DO', 'PASSWORD', 'USER', 'PLUGIN', 'FLUSH', 'KILL', 'RESET', 'START', 'STOP', 'PURGE', 'EXECUTE', 'PREPARE', 'DEALLOCATE', 'LOCK', 'USING', 'DROP', 'FOR', 'UPDATE', 'BEGIN', 'BY', 'ALL', 'SHARE', 'MODE', 'TO', 'KEY', 'DISTINCTROW', 'DISTINCT', 'HIGH_PRIORITY', 'LOW_PRIORITY', 'DELAYED', 'IGNORE', 'FORCE', 'STRAIGHT_JOIN', 'SQL_SMALL_RESULT', 'SQL_BIG_RESULT', 'QUICK', 'SQL_BUFFER_RESULT', 'SQL_CACHE', 'SQL_NO_CACHE', 'SQL_CALC_FOUND_ROWS', 'WITH'))





* Visibility: **public**
* This property is defined in [classes/RequestSql.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/RequestSql.php#L45)


### <a name="property-$attributes"></a>$attributes

    public mixed $attributes = array('passwd' => '*******************', 'secure_key' => '*******************')





* Visibility: **public**
* This property is defined in [classes/RequestSql.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/RequestSql.php#L68)


### <a name="property-$error_sql"></a>$error_sql

    public array $error_sql = array()





* Visibility: **public**
* This property is defined in [classes/RequestSql.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/RequestSql.php#L74)


Methods
-------


### <a name="method-getRequestSql"></a>getRequestSql

    array|boolean RequestSqlCore::getRequestSql()

Get list of request SQL



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/RequestSql.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/RequestSql.php#L81)




### <a name="method-getRequestSqlById"></a>getRequestSqlById

    array RequestSqlCore::getRequestSqlById($id)

Get list of request SQL by id request



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/RequestSql.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/RequestSql.php#L101)


#### Arguments
* $id **mixed**



### <a name="method-parsingSql"></a>parsingSql

    boolean RequestSqlCore::parsingSql($sql)

Call the parserSQL() method in Tools class
Cut the request in table for check it



* Visibility: **public**
* This method is defined in [classes/RequestSql.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/RequestSql.php#L113)


#### Arguments
* $sql **mixed**



### <a name="method-validateParser"></a>validateParser

    boolean RequestSqlCore::validateParser($tab, boolean $in, $sql)

Check if the parsing of the SQL request is good or not



* Visibility: **public**
* This method is defined in [classes/RequestSql.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/RequestSql.php#L126)


#### Arguments
* $tab **mixed**
* $in **boolean**
* $sql **mixed**



### <a name="method-validateSql"></a>validateSql

    boolean RequestSqlCore::validateSql($tab, $in, $sql)

Cut the request for check each cutting



* Visibility: **public**
* This method is defined in [classes/RequestSql.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/RequestSql.php#L151)


#### Arguments
* $tab **mixed**
* $in **mixed**
* $sql **mixed**



### <a name="method-getTables"></a>getTables

    array RequestSqlCore::getTables()

Get list of all tables



* Visibility: **public**
* This method is defined in [classes/RequestSql.php line 194](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/RequestSql.php#L194)




### <a name="method-getAttributesByTable"></a>getAttributesByTable

    array RequestSqlCore::getAttributesByTable($table)

Get list of all attributes by an table



* Visibility: **public**
* This method is defined in [classes/RequestSql.php line 210](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/RequestSql.php#L210)


#### Arguments
* $table **mixed**



### <a name="method-cutJoin"></a>cutJoin

    array|boolean RequestSqlCore::cutJoin($attrs, $from)

Cut an join sentence



* Visibility: **public**
* This method is defined in [classes/RequestSql.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/RequestSql.php#L222)


#### Arguments
* $attrs **mixed**
* $from **mixed**



### <a name="method-cutAttribute"></a>cutAttribute

    array|boolean RequestSqlCore::cutAttribute($attr, $from)

Cut an attribute with or without the alias



* Visibility: **public**
* This method is defined in [classes/RequestSql.php line 245](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/RequestSql.php#L245)


#### Arguments
* $attr **mixed**
* $from **mixed**



### <a name="method-returnNameTable"></a>returnNameTable

    array|boolean RequestSqlCore::returnNameTable(boolean $alias, $tables, $attr)

Get name of table by alias



* Visibility: **public**
* This method is defined in [classes/RequestSql.php line 278](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/RequestSql.php#L278)


#### Arguments
* $alias **boolean**
* $tables **mixed**
* $attr **mixed**



### <a name="method-attributExistInTable"></a>attributExistInTable

    boolean RequestSqlCore::attributExistInTable($attr, $table)

Check if an attributes existe in an table



* Visibility: **public**
* This method is defined in [classes/RequestSql.php line 317](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/RequestSql.php#L317)


#### Arguments
* $attr **mixed**
* $table **mixed**



### <a name="method-testedRequired"></a>testedRequired

    boolean RequestSqlCore::testedRequired($tab)

Check if all required sentence existing



* Visibility: **public**
* This method is defined in [classes/RequestSql.php line 340](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/RequestSql.php#L340)


#### Arguments
* $tab **mixed**



### <a name="method-testedUnauthorized"></a>testedUnauthorized

    boolean RequestSqlCore::testedUnauthorized($tab)

Check if an unauthorized existing in an array



* Visibility: **public**
* This method is defined in [classes/RequestSql.php line 357](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/RequestSql.php#L357)


#### Arguments
* $tab **mixed**



### <a name="method-checkedFrom"></a>checkedFrom

    boolean RequestSqlCore::checkedFrom($from)

Check a "FROM" sentence



* Visibility: **public**
* This method is defined in [classes/RequestSql.php line 374](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/RequestSql.php#L374)


#### Arguments
* $from **mixed**



### <a name="method-checkedSelect"></a>checkedSelect

    boolean RequestSqlCore::checkedSelect($select, $from, boolean $in)

Check a "SELECT" sentence



* Visibility: **public**
* This method is defined in [classes/RequestSql.php line 414](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/RequestSql.php#L414)


#### Arguments
* $select **mixed**
* $from **mixed**
* $in **boolean**



### <a name="method-checkedWhere"></a>checkedWhere

    boolean RequestSqlCore::checkedWhere($where, $from, $sql)

Check a "WHERE" sentence



* Visibility: **public**
* This method is defined in [classes/RequestSql.php line 452](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/RequestSql.php#L452)


#### Arguments
* $where **mixed**
* $from **mixed**
* $sql **mixed**



### <a name="method-checkedHaving"></a>checkedHaving

    boolean RequestSqlCore::checkedHaving($having, $from)

Check a "HAVING" sentence



* Visibility: **public**
* This method is defined in [classes/RequestSql.php line 492](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/RequestSql.php#L492)


#### Arguments
* $having **mixed**
* $from **mixed**



### <a name="method-checkedOrder"></a>checkedOrder

    boolean RequestSqlCore::checkedOrder($order, $from)

Check a "ORDER" sentence



* Visibility: **public**
* This method is defined in [classes/RequestSql.php line 531](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/RequestSql.php#L531)


#### Arguments
* $order **mixed**
* $from **mixed**



### <a name="method-checkedGroupBy"></a>checkedGroupBy

    boolean RequestSqlCore::checkedGroupBy($group, $from)

Check a "GROUP BY" sentence



* Visibility: **public**
* This method is defined in [classes/RequestSql.php line 560](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/RequestSql.php#L560)


#### Arguments
* $group **mixed**
* $from **mixed**



### <a name="method-checkedLimit"></a>checkedLimit

    boolean RequestSqlCore::checkedLimit($limit)

Check a "LIMIT" sentence



* Visibility: **public**
* This method is defined in [classes/RequestSql.php line 588](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/RequestSql.php#L588)


#### Arguments
* $limit **mixed**


