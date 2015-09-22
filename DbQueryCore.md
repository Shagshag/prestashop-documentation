DbQueryCore
===============

SQL query builder




* Class name: DbQueryCore
* This class is defined in [classes/db/DbQuery.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L32)





Properties
----------

* [$query](#property-$query)

Methods
-------
* [type](#method-type)
* [select](#method-select)
* [from](#method-from)
* [join](#method-join)
* [leftJoin](#method-leftJoin)
* [innerJoin](#method-innerJoin)
* [leftOuterJoin](#method-leftOuterJoin)
* [naturalJoin](#method-naturalJoin)
* [rightJoin](#method-rightJoin)
* [where](#method-where)
* [having](#method-having)
* [orderBy](#method-orderBy)
* [groupBy](#method-groupBy)
* [limit](#method-limit)
* [build](#method-build)
* [__toString](#method-__toString)




Properties
----------


### <a name="property-$query"></a>$query

    protected array $query = array('type' => 'SELECT', 'select' => array(), 'from' => '', 'join' => array(), 'where' => array(), 'group' => array(), 'having' => array(), 'order' => array(), 'limit' => array('offset' => 0, 'limit' => 0))

List of data to build the query



* Visibility: **protected**
* This property is defined in [classes/db/DbQuery.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L39)


Methods
-------


### <a name="method-type"></a>type

    \DbQuery DbQueryCore::type(string $type)

Sets type of the query



* Visibility: **public**
* This method is defined in [classes/db/DbQuery.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L58)


#### Arguments
* $type **string** - &lt;p&gt;SELECT|DELETE&lt;/p&gt;



### <a name="method-select"></a>select

    \DbQuery DbQueryCore::select(string $fields)

Adds fields to SELECT clause



* Visibility: **public**
* This method is defined in [classes/db/DbQuery.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L76)


#### Arguments
* $fields **string** - &lt;p&gt;List of fields to concat to other fields&lt;/p&gt;



### <a name="method-from"></a>from

    \DbQuery DbQueryCore::from(string $table, string|null $alias)

Sets table for FROM clause



* Visibility: **public**
* This method is defined in [classes/db/DbQuery.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L93)


#### Arguments
* $table **string** - &lt;p&gt;Table name&lt;/p&gt;
* $alias **string|null** - &lt;p&gt;Table alias&lt;/p&gt;



### <a name="method-join"></a>join

    \DbQuery DbQueryCore::join(string $join)

Adds JOIN clause
E.g. $this->join('RIGHT JOIN '._DB_PREFIX_.'product p ON .

..');

* Visibility: **public**
* This method is defined in [classes/db/DbQuery.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L110)


#### Arguments
* $join **string** - &lt;p&gt;Complete string&lt;/p&gt;



### <a name="method-leftJoin"></a>leftJoin

    \DbQuery DbQueryCore::leftJoin(string $table, string|null $alias, string|null $on)

Adds a LEFT JOIN clause



* Visibility: **public**
* This method is defined in [classes/db/DbQuery.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L128)


#### Arguments
* $table **string** - &lt;p&gt;Table name (without prefix)&lt;/p&gt;
* $alias **string|null** - &lt;p&gt;Table alias&lt;/p&gt;
* $on **string|null** - &lt;p&gt;ON clause&lt;/p&gt;



### <a name="method-innerJoin"></a>innerJoin

    \DbQuery DbQueryCore::innerJoin(string $table, string|null $alias, string|null $on)

Adds an INNER JOIN clause
E.g. $this->innerJoin('product p ON .

..')

* Visibility: **public**
* This method is defined in [classes/db/DbQuery.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L143)


#### Arguments
* $table **string** - &lt;p&gt;Table name (without prefix)&lt;/p&gt;
* $alias **string|null** - &lt;p&gt;Table alias&lt;/p&gt;
* $on **string|null** - &lt;p&gt;ON clause&lt;/p&gt;



### <a name="method-leftOuterJoin"></a>leftOuterJoin

    \DbQuery DbQueryCore::leftOuterJoin(string $table, string|null $alias, string|null $on)

Adds a LEFT OUTER JOIN clause



* Visibility: **public**
* This method is defined in [classes/db/DbQuery.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L157)


#### Arguments
* $table **string** - &lt;p&gt;Table name (without prefix)&lt;/p&gt;
* $alias **string|null** - &lt;p&gt;Table alias&lt;/p&gt;
* $on **string|null** - &lt;p&gt;ON clause&lt;/p&gt;



### <a name="method-naturalJoin"></a>naturalJoin

    \DbQuery DbQueryCore::naturalJoin(string $table, string|null $alias)

Adds a NATURAL JOIN clause



* Visibility: **public**
* This method is defined in [classes/db/DbQuery.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L170)


#### Arguments
* $table **string** - &lt;p&gt;Table name (without prefix)&lt;/p&gt;
* $alias **string|null** - &lt;p&gt;Table alias&lt;/p&gt;



### <a name="method-rightJoin"></a>rightJoin

    \DbQuery DbQueryCore::rightJoin(string $table, string|null $alias, string|null $on)

Adds a RIGHT JOIN clause



* Visibility: **public**
* This method is defined in [classes/db/DbQuery.php line 184](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L184)


#### Arguments
* $table **string** - &lt;p&gt;Table name (without prefix)&lt;/p&gt;
* $alias **string|null** - &lt;p&gt;Table alias&lt;/p&gt;
* $on **string|null** - &lt;p&gt;ON clause&lt;/p&gt;



### <a name="method-where"></a>where

    \DbQuery DbQueryCore::where(string $restriction)

Adds a restriction in WHERE clause (each restriction will be separated by AND statement)



* Visibility: **public**
* This method is defined in [classes/db/DbQuery.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L196)


#### Arguments
* $restriction **string**



### <a name="method-having"></a>having

    \DbQuery DbQueryCore::having(string $restriction)

Adds a restriction in HAVING clause (each restriction will be separated by AND statement)



* Visibility: **public**
* This method is defined in [classes/db/DbQuery.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L212)


#### Arguments
* $restriction **string**



### <a name="method-orderBy"></a>orderBy

    \DbQuery DbQueryCore::orderBy(string $fields)

Adds an ORDER BY restriction



* Visibility: **public**
* This method is defined in [classes/db/DbQuery.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L228)


#### Arguments
* $fields **string** - &lt;p&gt;List of fields to sort. E.g. $this-&gt;order(&#039;myField, b.mySecondField DESC&#039;)&lt;/p&gt;



### <a name="method-groupBy"></a>groupBy

    \DbQuery DbQueryCore::groupBy(string $fields)

Adds a GROUP BY restriction



* Visibility: **public**
* This method is defined in [classes/db/DbQuery.php line 244](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L244)


#### Arguments
* $fields **string** - &lt;p&gt;List of fields to group. E.g. $this-&gt;group(&#039;myField1, myField2&#039;)&lt;/p&gt;



### <a name="method-limit"></a>limit

    \DbQuery DbQueryCore::limit(integer $limit, integer $offset)

Sets query offset and limit



* Visibility: **public**
* This method is defined in [classes/db/DbQuery.php line 261](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L261)


#### Arguments
* $limit **integer**
* $offset **integer**



### <a name="method-build"></a>build

    string DbQueryCore::build()

Generates query and return SQL string



* Visibility: **public**
* This method is defined in [classes/db/DbQuery.php line 282](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L282)




### <a name="method-__toString"></a>__toString

    string DbQueryCore::__toString()

Converts object to string



* Visibility: **public**
* This method is defined in [classes/db/DbQuery.php line 329](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/db/DbQuery.php#L329)



