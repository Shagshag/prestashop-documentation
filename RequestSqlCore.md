RequestSqlCore
===============






* Class name: RequestSqlCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in classes\RequestSql.php line 27





Properties
----------


### $name

    public mixed $name





* Visibility: **public**
* This property is defined in classes\RequestSql.php line 29


### $sql

    public mixed $sql





* Visibility: **public**
* This property is defined in classes\RequestSql.php line 30


### $definition

    public mixed $definition = array('table' => 'request_sql', 'primary' => 'id_request_sql', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isString', 'required' => true, 'size' => 200), 'sql' => array('type' => self::TYPE_SQL, 'validate' => 'isString', 'required' => true)))





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\RequestSql.php line 35


### $tested

    public array $tested = array('required' => array('SELECT', 'FROM'), 'option' => array('WHERE', 'ORDER', 'LIMIT', 'HAVING', 'GROUP', 'UNION'), 'operator' => array('AND', '&&', 'BETWEEN', 'AND', 'BINARY', '&', '~', '|', '^', 'CASE', 'WHEN', 'END', 'DIV', '/', '<=>', '=', '>=', '>', 'IS', 'NOT', 'NULL', '<<', '<=', '<', 'LIKE', '-', '%', '!=', '<>', 'REGEXP', '!', '||', 'OR', '+', '>>', 'RLIKE', 'SOUNDS', '*', '-', 'XOR', 'IN'), 'function' => array('AVG', 'SUM', 'COUNT', 'MIN', 'MAX', 'STDDEV', 'STDDEV_SAMP', 'STDDEV_POP', 'VARIANCE', 'VAR_SAMP', 'VAR_POP', 'GROUP_CONCAT', 'BIT_AND', 'BIT_OR', 'BIT_XOR'), 'unauthorized' => array('DELETE', 'ALTER', 'INSERT', 'REPLACE', 'CREATE', 'TRUNCATE', 'OPTIMIZE', 'GRANT', 'REVOKE', 'SHOW', 'HANDLER', 'LOAD', 'ROLLBACK', 'SAVEPOINT', 'UNLOCK', 'INSTALL', 'UNINSTALL', 'ANALZYE', 'BACKUP', 'CHECK', 'CHECKSUM', 'REPAIR', 'RESTORE', 'CACHE', 'DESCRIBE', 'EXPLAIN', 'USE', 'HELP', 'SET', 'DUPLICATE', 'VALUES', 'INTO', 'RENAME', 'CALL', 'PROCEDURE', 'FUNCTION', 'DATABASE', 'SERVER', 'LOGFILE', 'DEFINER', 'RETURNS', 'EVENT', 'TABLESPACE', 'VIEW', 'TRIGGER', 'DATA', 'DO', 'PASSWORD', 'USER', 'PLUGIN', 'FLUSH', 'KILL', 'RESET', 'START', 'STOP', 'PURGE', 'EXECUTE', 'PREPARE', 'DEALLOCATE', 'LOCK', 'USING', 'DROP', 'FOR', 'UPDATE', 'BEGIN', 'BY', 'ALL', 'SHARE', 'MODE', 'TO', 'KEY', 'DISTINCTROW', 'DISTINCT', 'HIGH_PRIORITY', 'LOW_PRIORITY', 'DELAYED', 'IGNORE', 'FORCE', 'STRAIGHT_JOIN', 'SQL_SMALL_RESULT', 'SQL_BIG_RESULT', 'QUICK', 'SQL_BUFFER_RESULT', 'SQL_CACHE', 'SQL_NO_CACHE', 'SQL_CALC_FOUND_ROWS', 'WITH'))





* Visibility: **public**
* This property is defined in classes\RequestSql.php line 45


### $attributes

    public mixed $attributes = array('passwd' => '*******************', 'secure_key' => '*******************')





* Visibility: **public**
* This property is defined in classes\RequestSql.php line 68


### $error_sql

    public array $error_sql = array()





* Visibility: **public**
* This property is defined in classes\RequestSql.php line 74


Methods
-------


### getRequestSql

    array|boolean RequestSqlCore::getRequestSql()

Get list of request SQL



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\RequestSql.php line 81




### getRequestSqlById

    array RequestSqlCore::getRequestSqlById($id)

Get list of request SQL by id request



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\RequestSql.php line 101


#### Arguments
* $id **mixed**



### parsingSql

    boolean RequestSqlCore::parsingSql($sql)

Call the parserSQL() method in Tools class
Cut the request in table for check it



* Visibility: **public**
* This method is defined in classes\RequestSql.php line 113


#### Arguments
* $sql **mixed**



### validateParser

    boolean RequestSqlCore::validateParser($tab, boolean $in, $sql)

Check if the parsing of the SQL request is good or not



* Visibility: **public**
* This method is defined in classes\RequestSql.php line 126


#### Arguments
* $tab **mixed**
* $in **boolean**
* $sql **mixed**



### validateSql

    boolean RequestSqlCore::validateSql($tab, $in, $sql)

Cut the request for check each cutting



* Visibility: **public**
* This method is defined in classes\RequestSql.php line 151


#### Arguments
* $tab **mixed**
* $in **mixed**
* $sql **mixed**



### getTables

    array RequestSqlCore::getTables()

Get list of all tables



* Visibility: **public**
* This method is defined in classes\RequestSql.php line 194




### getAttributesByTable

    array RequestSqlCore::getAttributesByTable($table)

Get list of all attributes by an table



* Visibility: **public**
* This method is defined in classes\RequestSql.php line 210


#### Arguments
* $table **mixed**



### cutJoin

    array|boolean RequestSqlCore::cutJoin($attrs, $from)

Cut an join sentence



* Visibility: **public**
* This method is defined in classes\RequestSql.php line 222


#### Arguments
* $attrs **mixed**
* $from **mixed**



### cutAttribute

    array|boolean RequestSqlCore::cutAttribute($attr, $from)

Cut an attribute with or without the alias



* Visibility: **public**
* This method is defined in classes\RequestSql.php line 245


#### Arguments
* $attr **mixed**
* $from **mixed**



### returnNameTable

    array|boolean RequestSqlCore::returnNameTable(boolean $alias, $tables, $attr)

Get name of table by alias



* Visibility: **public**
* This method is defined in classes\RequestSql.php line 278


#### Arguments
* $alias **boolean**
* $tables **mixed**
* $attr **mixed**



### attributExistInTable

    boolean RequestSqlCore::attributExistInTable($attr, $table)

Check if an attributes existe in an table



* Visibility: **public**
* This method is defined in classes\RequestSql.php line 317


#### Arguments
* $attr **mixed**
* $table **mixed**



### testedRequired

    boolean RequestSqlCore::testedRequired($tab)

Check if all required sentence existing



* Visibility: **public**
* This method is defined in classes\RequestSql.php line 340


#### Arguments
* $tab **mixed**



### testedUnauthorized

    boolean RequestSqlCore::testedUnauthorized($tab)

Check if an unauthorized existing in an array



* Visibility: **public**
* This method is defined in classes\RequestSql.php line 357


#### Arguments
* $tab **mixed**



### checkedFrom

    boolean RequestSqlCore::checkedFrom($from)

Check a "FROM" sentence



* Visibility: **public**
* This method is defined in classes\RequestSql.php line 374


#### Arguments
* $from **mixed**



### checkedSelect

    boolean RequestSqlCore::checkedSelect($select, $from, boolean $in)

Check a "SELECT" sentence



* Visibility: **public**
* This method is defined in classes\RequestSql.php line 414


#### Arguments
* $select **mixed**
* $from **mixed**
* $in **boolean**



### checkedWhere

    boolean RequestSqlCore::checkedWhere($where, $from, $sql)

Check a "WHERE" sentence



* Visibility: **public**
* This method is defined in classes\RequestSql.php line 452


#### Arguments
* $where **mixed**
* $from **mixed**
* $sql **mixed**



### checkedHaving

    boolean RequestSqlCore::checkedHaving($having, $from)

Check a "HAVING" sentence



* Visibility: **public**
* This method is defined in classes\RequestSql.php line 492


#### Arguments
* $having **mixed**
* $from **mixed**



### checkedOrder

    boolean RequestSqlCore::checkedOrder($order, $from)

Check a "ORDER" sentence



* Visibility: **public**
* This method is defined in classes\RequestSql.php line 531


#### Arguments
* $order **mixed**
* $from **mixed**



### checkedGroupBy

    boolean RequestSqlCore::checkedGroupBy($group, $from)

Check a "GROUP BY" sentence



* Visibility: **public**
* This method is defined in classes\RequestSql.php line 560


#### Arguments
* $group **mixed**
* $from **mixed**



### checkedLimit

    boolean RequestSqlCore::checkedLimit($limit)

Check a "LIMIT" sentence



* Visibility: **public**
* This method is defined in classes\RequestSql.php line 588


#### Arguments
* $limit **mixed**


