Class DbQueryCore
=====================

SQL query builder



* Class name: DbQueryCore
* Source: [classes/db/DbQuery.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L32)


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
* [rightJoin](#method-rightJoin)
* [select](#method-select)
* [type](#method-type)
* [where](#method-where)




Properties
----------


### <a name="property-$query"></a>$query

```php
protected array $query = array('type' => 'SELECT', 'select' => array(), 'from' => '', 'join' => array(), 'where' => array(), 'group' => array(), 'having' => array(), 'order' => array(), 'limit' => array('offset' => 0, 'limit' => 0))
```

List of data to build the query



* Visibility: **protected**
* Source: [classes/db/DbQuery.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L39).


Methods
-------


### <a name="method-__toString"></a>__toString

```php
string DbQueryCore::__toString()
```

Converts object to string



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 329](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L329)




### <a name="method-build"></a>build

```php
string DbQueryCore::build()
```

Generates query and return SQL string



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 282](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L282)




### <a name="method-from"></a>from

```php
\DbQuery DbQueryCore::from(string $table, string|null $alias)
```

Sets table for FROM clause



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L93)


#### Arguments
* $table **string** - Table name
* $alias **string|null** - Table alias



### <a name="method-groupBy"></a>groupBy

```php
\DbQuery DbQueryCore::groupBy(string $fields)
```

Adds a GROUP BY restriction



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 244](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L244)


#### Arguments
* $fields **string** - List of fields to group. E.g. $this-&gt;group(&#039;myField1, myField2&#039;)



### <a name="method-having"></a>having

```php
\DbQuery DbQueryCore::having(string $restriction)
```

Adds a restriction in HAVING clause (each restriction will be separated by AND statement)



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L212)


#### Arguments
* $restriction **string**



### <a name="method-innerJoin"></a>innerJoin

```php
\DbQuery DbQueryCore::innerJoin(string $table, string|null $alias, string|null $on)
```

Adds an INNER JOIN clause
E.g. $this->innerJoin('product p ON .

..')

* Visibility: **public**
* Source: [classes/db/DbQuery.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L143)


#### Arguments
* $table **string** - Table name (without prefix)
* $alias **string|null** - Table alias
* $on **string|null** - ON clause



### <a name="method-join"></a>join

```php
\DbQuery DbQueryCore::join(string $join)
```

Adds JOIN clause
E.g. $this->join('RIGHT JOIN '._DB_PREFIX_.'product p ON .

..');

* Visibility: **public**
* Source: [classes/db/DbQuery.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L110)


#### Arguments
* $join **string** - Complete string



### <a name="method-leftJoin"></a>leftJoin

```php
\DbQuery DbQueryCore::leftJoin(string $table, string|null $alias, string|null $on)
```

Adds a LEFT JOIN clause



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L128)


#### Arguments
* $table **string** - Table name (without prefix)
* $alias **string|null** - Table alias
* $on **string|null** - ON clause



### <a name="method-leftOuterJoin"></a>leftOuterJoin

```php
\DbQuery DbQueryCore::leftOuterJoin(string $table, string|null $alias, string|null $on)
```

Adds a LEFT OUTER JOIN clause



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L157)


#### Arguments
* $table **string** - Table name (without prefix)
* $alias **string|null** - Table alias
* $on **string|null** - ON clause



### <a name="method-limit"></a>limit

```php
\DbQuery DbQueryCore::limit(integer $limit, integer $offset)
```

Sets query offset and limit



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 261](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L261)


#### Arguments
* $limit **integer**
* $offset **integer**



### <a name="method-naturalJoin"></a>naturalJoin

```php
\DbQuery DbQueryCore::naturalJoin(string $table, string|null $alias)
```

Adds a NATURAL JOIN clause



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L170)


#### Arguments
* $table **string** - Table name (without prefix)
* $alias **string|null** - Table alias



### <a name="method-orderBy"></a>orderBy

```php
\DbQuery DbQueryCore::orderBy(string $fields)
```

Adds an ORDER BY restriction



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L228)


#### Arguments
* $fields **string** - List of fields to sort. E.g. $this-&gt;order(&#039;myField, b.mySecondField DESC&#039;)



### <a name="method-rightJoin"></a>rightJoin

```php
\DbQuery DbQueryCore::rightJoin(string $table, string|null $alias, string|null $on)
```

Adds a RIGHT JOIN clause



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 184](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L184)


#### Arguments
* $table **string** - Table name (without prefix)
* $alias **string|null** - Table alias
* $on **string|null** - ON clause



### <a name="method-select"></a>select

```php
\DbQuery DbQueryCore::select(string $fields)
```

Adds fields to SELECT clause



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L76)


#### Arguments
* $fields **string** - List of fields to concat to other fields



### <a name="method-type"></a>type

```php
\DbQuery DbQueryCore::type(string $type)
```

Sets type of the query



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L58)


#### Arguments
* $type **string** - SELECT|DELETE



### <a name="method-where"></a>where

```php
\DbQuery DbQueryCore::where(string $restriction)
```

Adds a restriction in WHERE clause (each restriction will be separated by AND statement)



* Visibility: **public**
* Source: [classes/db/DbQuery.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L196)


#### Arguments
* $restriction **string**


