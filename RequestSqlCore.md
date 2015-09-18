RequestSqlCore
===============






* Class name: RequestSqlCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $name

    public mixed $name





* Visibility: **public**


### $sql

    public mixed $sql





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'request_sql', 'primary' => 'id_request_sql', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isString', 'required' => true, 'size' => 200), 'sql' => array('type' => self::TYPE_SQL, 'validate' => 'isString', 'required' => true)))





* Visibility: **public**
* This property is **static**.


### $tested

    public array $tested = array('required' => array('SELECT', 'FROM'), 'option' => array('WHERE', 'ORDER', 'LIMIT', 'HAVING', 'GROUP', 'UNION'), 'operator' => array('AND', '&&', 'BETWEEN', 'AND', 'BINARY', '&', '~', '|', '^', 'CASE', 'WHEN', 'END', 'DIV', '/', '<=>', '=', '>=', '>', 'IS', 'NOT', 'NULL', '<<', '<=', '<', 'LIKE', '-', '%', '!=', '<>', 'REGEXP', '!', '||', 'OR', '+', '>>', 'RLIKE', 'SOUNDS', '*', '-', 'XOR', 'IN'), 'function' => array('AVG', 'SUM', 'COUNT', 'MIN', 'MAX', 'STDDEV', 'STDDEV_SAMP', 'STDDEV_POP', 'VARIANCE', 'VAR_SAMP', 'VAR_POP', 'GROUP_CONCAT', 'BIT_AND', 'BIT_OR', 'BIT_XOR'), 'unauthorized' => array('DELETE', 'ALTER', 'INSERT', 'REPLACE', 'CREATE', 'TRUNCATE', 'OPTIMIZE', 'GRANT', 'REVOKE', 'SHOW', 'HANDLER', 'LOAD', 'ROLLBACK', 'SAVEPOINT', 'UNLOCK', 'INSTALL', 'UNINSTALL', 'ANALZYE', 'BACKUP', 'CHECK', 'CHECKSUM', 'REPAIR', 'RESTORE', 'CACHE', 'DESCRIBE', 'EXPLAIN', 'USE', 'HELP', 'SET', 'DUPLICATE', 'VALUES', 'INTO', 'RENAME', 'CALL', 'PROCEDURE', 'FUNCTION', 'DATABASE', 'SERVER', 'LOGFILE', 'DEFINER', 'RETURNS', 'EVENT', 'TABLESPACE', 'VIEW', 'TRIGGER', 'DATA', 'DO', 'PASSWORD', 'USER', 'PLUGIN', 'FLUSH', 'KILL', 'RESET', 'START', 'STOP', 'PURGE', 'EXECUTE', 'PREPARE', 'DEALLOCATE', 'LOCK', 'USING', 'DROP', 'FOR', 'UPDATE', 'BEGIN', 'BY', 'ALL', 'SHARE', 'MODE', 'TO', 'KEY', 'DISTINCTROW', 'DISTINCT', 'HIGH_PRIORITY', 'LOW_PRIORITY', 'DELAYED', 'IGNORE', 'FORCE', 'STRAIGHT_JOIN', 'SQL_SMALL_RESULT', 'SQL_BIG_RESULT', 'QUICK', 'SQL_BUFFER_RESULT', 'SQL_CACHE', 'SQL_NO_CACHE', 'SQL_CALC_FOUND_ROWS', 'WITH'))





* Visibility: **public**


### $attributes

    public mixed $attributes = array('passwd' => '*******************', 'secure_key' => '*******************')





* Visibility: **public**


### $error_sql

    public array $error_sql = array()





* Visibility: **public**


Methods
-------


### getRequestSql

    array|boolean RequestSqlCore::getRequestSql()

Get list of request SQL



* Visibility: **public**
* This method is **static**.




### getRequestSqlById

    array RequestSqlCore::getRequestSqlById($id)

Get list of request SQL by id request



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id **mixed**



### parsingSql

    boolean RequestSqlCore::parsingSql($sql)

Call the parserSQL() method in Tools class
Cut the request in table for check it



* Visibility: **public**


#### Arguments
* $sql **mixed**



### validateParser

    boolean RequestSqlCore::validateParser($tab, boolean $in, $sql)

Check if the parsing of the SQL request is good or not



* Visibility: **public**


#### Arguments
* $tab **mixed**
* $in **boolean**
* $sql **mixed**



### validateSql

    boolean RequestSqlCore::validateSql($tab, $in, $sql)

Cut the request for check each cutting



* Visibility: **public**


#### Arguments
* $tab **mixed**
* $in **mixed**
* $sql **mixed**



### getTables

    array RequestSqlCore::getTables()

Get list of all tables



* Visibility: **public**




### getAttributesByTable

    array RequestSqlCore::getAttributesByTable($table)

Get list of all attributes by an table



* Visibility: **public**


#### Arguments
* $table **mixed**



### cutJoin

    array|boolean RequestSqlCore::cutJoin($attrs, $from)

Cut an join sentence



* Visibility: **public**


#### Arguments
* $attrs **mixed**
* $from **mixed**



### cutAttribute

    array|boolean RequestSqlCore::cutAttribute($attr, $from)

Cut an attribute with or without the alias



* Visibility: **public**


#### Arguments
* $attr **mixed**
* $from **mixed**



### returnNameTable

    array|boolean RequestSqlCore::returnNameTable(boolean $alias, $tables, $attr)

Get name of table by alias



* Visibility: **public**


#### Arguments
* $alias **boolean**
* $tables **mixed**
* $attr **mixed**



### attributExistInTable

    boolean RequestSqlCore::attributExistInTable($attr, $table)

Check if an attributes existe in an table



* Visibility: **public**


#### Arguments
* $attr **mixed**
* $table **mixed**



### testedRequired

    boolean RequestSqlCore::testedRequired($tab)

Check if all required sentence existing



* Visibility: **public**


#### Arguments
* $tab **mixed**



### testedUnauthorized

    boolean RequestSqlCore::testedUnauthorized($tab)

Check if an unauthorized existing in an array



* Visibility: **public**


#### Arguments
* $tab **mixed**



### checkedFrom

    boolean RequestSqlCore::checkedFrom($from)

Check a "FROM" sentence



* Visibility: **public**


#### Arguments
* $from **mixed**



### checkedSelect

    boolean RequestSqlCore::checkedSelect($select, $from, boolean $in)

Check a "SELECT" sentence



* Visibility: **public**


#### Arguments
* $select **mixed**
* $from **mixed**
* $in **boolean**



### checkedWhere

    boolean RequestSqlCore::checkedWhere($where, $from, $sql)

Check a "WHERE" sentence



* Visibility: **public**


#### Arguments
* $where **mixed**
* $from **mixed**
* $sql **mixed**



### checkedHaving

    boolean RequestSqlCore::checkedHaving($having, $from)

Check a "HAVING" sentence



* Visibility: **public**


#### Arguments
* $having **mixed**
* $from **mixed**



### checkedOrder

    boolean RequestSqlCore::checkedOrder($order, $from)

Check a "ORDER" sentence



* Visibility: **public**


#### Arguments
* $order **mixed**
* $from **mixed**



### checkedGroupBy

    boolean RequestSqlCore::checkedGroupBy($group, $from)

Check a "GROUP BY" sentence



* Visibility: **public**


#### Arguments
* $group **mixed**
* $from **mixed**



### checkedLimit

    boolean RequestSqlCore::checkedLimit($limit)

Check a "LIMIT" sentence



* Visibility: **public**


#### Arguments
* $limit **mixed**


