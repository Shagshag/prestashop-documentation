Class DbQueryCore
=====================

SQL query builder



* Class name: DbQueryCore
* Source: [classes/db/DbQuery.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/db/DbQuery.php#L33)


Contents
--------


### Properties

* [$query](#property-$query)

### Methods

* [__toString](#method-__toString)
* [build](#method-build)
* [from](#method-from)
* [groupBy](#method-groupBy)
* [having](#method-having)
* [innerJoin](#method-innerJoin)
* [join](#method-join)
* [leftJoin](#method-leftJoin)
* [leftOuterJoin](#method-leftOuterJoin)
* [limit](#method-limit)
* [naturalJoin](#method-naturalJoin)
* [orderBy](#method-orderBy)
* [select](#method-select)
* [where](#method-where)




Properties
----------


### <a name="property-$query"></a>$query

```php
protected array $query = array('select' => array(), 'from' => '', 'join' => array(), 'where' => array(), 'group' => array(), 'having' => array(), 'order' => array(), 'limit' => array('offset' => 0, 'limit' => 0))
```





* Visibility: **protected**
* Source: [classes/db/DbQuery.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/db/DbQuery.php#L38).


Methods
-------


### <a name="method-__toString"></a>__toString

```php
mixed DbQueryCore::__toString()
```





* Visibility: **public**
* Source: [classes/db/DbQuery.php line 250](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/db/DbQuery.php#L250)




### <a name="method-build"></a>build

```php
string DbQueryCore::build()
```

Generate and get the query



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 218](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/db/DbQuery.php#L218)




### <a name="method-from"></a>from

```php
\DbQuery DbQueryCore::from(string $table, $alias)
```

Set table for FROM clause



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/db/DbQuery.php#L68)


#### Arguments
* $table **string** - Table name
* $alias **mixed**



### <a name="method-groupBy"></a>groupBy

```php
\DbQuery DbQueryCore::groupBy(string $fields)
```

Add a GROUP BY restriction



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/db/DbQuery.php#L186)


#### Arguments
* $fields **string** - List of fields to sort. E.g. $this-&gt;group(&#039;myField, b.mySecondField DESC&#039;)



### <a name="method-having"></a>having

```php
\DbQuery DbQueryCore::having(string $restriction)
```

Add a restriction in HAVING clause (each restriction will be separated by AND statement)



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/db/DbQuery.php#L158)


#### Arguments
* $restriction **string**



### <a name="method-innerJoin"></a>innerJoin

```php
mixed DbQueryCore::innerJoin(string $table, string $alias, string $on)
```

Add INNER JOIN clause
	E.g. $this->innerJoin('product p ON .

..')

* Visibility: **public**
* Source: [classes/db/DbQuery.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/db/DbQuery.php#L110)


#### Arguments
* $table **string** - Table name (without prefix)
* $alias **string** - Table alias
* $on **string** - ON clause



### <a name="method-join"></a>join

```php
\DbQuery DbQueryCore::join(string $join)
```

Add JOIN clause
	E.g. $this->join('RIGHT JOIN '._DB_PREFIX_.'product p ON .

..');

* Visibility: **public**
* Source: [classes/db/DbQuery.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/db/DbQuery.php#L82)


#### Arguments
* $join **string** - Complete string



### <a name="method-leftJoin"></a>leftJoin

```php
mixed DbQueryCore::leftJoin(string $table, string $alias, string $on)
```

Add LEFT JOIN clause



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/db/DbQuery.php#L97)


#### Arguments
* $table **string** - Table name (without prefix)
* $alias **string** - Table alias
* $on **string** - ON clause



### <a name="method-leftOuterJoin"></a>leftOuterJoin

```php
mixed DbQueryCore::leftOuterJoin(string $table, string $alias, string $on)
```

Add LEFT OUTER JOIN clause



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/db/DbQuery.php#L122)


#### Arguments
* $table **string** - Table name (without prefix)
* $alias **string** - Table alias
* $on **string** - ON clause



### <a name="method-limit"></a>limit

```php
\DbQuery DbQueryCore::limit($limit, $offset)
```

Limit results in query



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/db/DbQuery.php#L200)


#### Arguments
* $limit **mixed**
* $offset **mixed**



### <a name="method-naturalJoin"></a>naturalJoin

```php
mixed DbQueryCore::naturalJoin(string $table, string $alias)
```

Add NATURAL JOIN clause



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/db/DbQuery.php#L133)


#### Arguments
* $table **string** - Table name (without prefix)
* $alias **string** - Table alias



### <a name="method-orderBy"></a>orderBy

```php
\DbQuery DbQueryCore::orderBy(string $fields)
```

Add an ORDER B restriction



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/db/DbQuery.php#L172)


#### Arguments
* $fields **string** - List of fields to sort. E.g. $this-&gt;order(&#039;myField, b.mySecondField DESC&#039;)



### <a name="method-select"></a>select

```php
\DbQuery DbQueryCore::select(string $fields)
```

Add fields in query selection



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/db/DbQuery.php#L55)


#### Arguments
* $fields **string** - List of fields to concat to other fields



### <a name="method-where"></a>where

```php
\DbQuery DbQueryCore::where(string $restriction)
```

Add a restriction in WHERE clause (each restriction will be separated by AND statement)



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/db/DbQuery.php#L144)


#### Arguments
* $restriction **string**


