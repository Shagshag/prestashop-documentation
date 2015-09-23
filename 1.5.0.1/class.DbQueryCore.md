Class DbQueryCore
=====================

SQL query builder



* Class name: DbQueryCore
* Source: [classes/db/DbQuery.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/DbQuery.php#L33)


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
* Source: [classes/db/DbQuery.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/DbQuery.php#L38).


Methods
-------


### <a name="method-__toString"></a>__toString

```php
mixed DbQueryCore::__toString()
```





* Visibility: **public**
* Source: [classes/db/DbQuery.php line 256](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/DbQuery.php#L256)




### <a name="method-build"></a>build

```php
string DbQueryCore::build()
```

Generate and get the query



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 224](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/DbQuery.php#L224)




### <a name="method-from"></a>from

```php
\DbQuery DbQueryCore::from(string $table)
```

Set table for FROM clause



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/DbQuery.php#L68)


#### Arguments
* $table **string** - Table name



### <a name="method-groupBy"></a>groupBy

```php
\DbQuery DbQueryCore::groupBy(string $fields)
```

Add a GROUP BY restriction



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/DbQuery.php#L192)


#### Arguments
* $fields **string** - List of fields to sort. E.g. $this-&gt;group(&#039;myField, b.mySecondField DESC&#039;)



### <a name="method-having"></a>having

```php
\DbQuery DbQueryCore::having(string $restriction)
```

Add a restriction in HAVING clause (each restriction will be separated by AND statement)



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/DbQuery.php#L164)


#### Arguments
* $restriction **string**



### <a name="method-innerJoin"></a>innerJoin

```php
mixed DbQueryCore::innerJoin(string $join)
```

Add INNER JOIN clause
	E.g. $this->innerJoin('product p ON .

..')

* Visibility: **public**
* Source: [classes/db/DbQuery.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/DbQuery.php#L110)


#### Arguments
* $join **string** - Table followed by ON claused



### <a name="method-join"></a>join

```php
\DbQuery DbQueryCore::join(string $join)
```

Add JOIN clause
	E.g. $this->join('RIGHT JOIN '._DB_PREFIX_.'product p ON .

..');

* Visibility: **public**
* Source: [classes/db/DbQuery.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/DbQuery.php#L82)


#### Arguments
* $join **string** - Complete string



### <a name="method-leftJoin"></a>leftJoin

```php
mixed DbQueryCore::leftJoin(string $join)
```

Add LEFT JOIN clause
	E.g. $this->leftJoin('product p ON .

..')

* Visibility: **public**
* Source: [classes/db/DbQuery.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/DbQuery.php#L96)


#### Arguments
* $join **string** - Table followed by ON claused



### <a name="method-leftOuterJoin"></a>leftOuterJoin

```php
mixed DbQueryCore::leftOuterJoin(string $join)
```

Add LEFT OUTER JOIN clause



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/DbQuery.php#L123)


#### Arguments
* $join **string** - Table followed by ON claused



### <a name="method-limit"></a>limit

```php
\DbQuery DbQueryCore::limit($limit, $offset)
```

Limit results in query



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 206](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/DbQuery.php#L206)


#### Arguments
* $limit **mixed**
* $offset **mixed**



### <a name="method-naturalJoin"></a>naturalJoin

```php
mixed DbQueryCore::naturalJoin(string $join)
```

Add NATURAL JOIN clause



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/DbQuery.php#L136)


#### Arguments
* $join **string**



### <a name="method-orderBy"></a>orderBy

```php
\DbQuery DbQueryCore::orderBy(string $fields)
```

Add an ORDER B restriction



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/DbQuery.php#L178)


#### Arguments
* $fields **string** - List of fields to sort. E.g. $this-&gt;order(&#039;myField, b.mySecondField DESC&#039;)



### <a name="method-select"></a>select

```php
\DbQuery DbQueryCore::select(string $fields)
```

Add fields in query selection



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/DbQuery.php#L55)


#### Arguments
* $fields **string** - List of fields to concat to other fields



### <a name="method-where"></a>where

```php
\DbQuery DbQueryCore::where(string $restriction)
```

Add a restriction in WHERE clause (each restriction will be separated by AND statement)



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/db/DbQuery.php#L150)


#### Arguments
* $restriction **string**


