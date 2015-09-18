DbQueryCore
===============

SQL query builder




* Class name: DbQueryCore
* Namespace: 





Properties
----------


### $query

    protected array $query = array('type' => 'SELECT', 'select' => array(), 'from' => '', 'join' => array(), 'where' => array(), 'group' => array(), 'having' => array(), 'order' => array(), 'limit' => array('offset' => 0, 'limit' => 0))

List of data to build the query



* Visibility: **protected**


Methods
-------


### type

    \DbQuery DbQueryCore::type(string $type)

Sets type of the query



* Visibility: **public**


#### Arguments
* $type **string** - &lt;p&gt;SELECT|DELETE&lt;/p&gt;



### select

    \DbQuery DbQueryCore::select(string $fields)

Adds fields to SELECT clause



* Visibility: **public**


#### Arguments
* $fields **string** - &lt;p&gt;List of fields to concat to other fields&lt;/p&gt;



### from

    \DbQuery DbQueryCore::from(string $table, string|null $alias)

Sets table for FROM clause



* Visibility: **public**


#### Arguments
* $table **string** - &lt;p&gt;Table name&lt;/p&gt;
* $alias **string|null** - &lt;p&gt;Table alias&lt;/p&gt;



### join

    \DbQuery DbQueryCore::join(string $join)

Adds JOIN clause
E.g. $this->join('RIGHT JOIN '._DB_PREFIX_.'product p ON .

..');

* Visibility: **public**


#### Arguments
* $join **string** - &lt;p&gt;Complete string&lt;/p&gt;



### leftJoin

    \DbQuery DbQueryCore::leftJoin(string $table, string|null $alias, string|null $on)

Adds a LEFT JOIN clause



* Visibility: **public**


#### Arguments
* $table **string** - &lt;p&gt;Table name (without prefix)&lt;/p&gt;
* $alias **string|null** - &lt;p&gt;Table alias&lt;/p&gt;
* $on **string|null** - &lt;p&gt;ON clause&lt;/p&gt;



### innerJoin

    \DbQuery DbQueryCore::innerJoin(string $table, string|null $alias, string|null $on)

Adds an INNER JOIN clause
E.g. $this->innerJoin('product p ON .

..')

* Visibility: **public**


#### Arguments
* $table **string** - &lt;p&gt;Table name (without prefix)&lt;/p&gt;
* $alias **string|null** - &lt;p&gt;Table alias&lt;/p&gt;
* $on **string|null** - &lt;p&gt;ON clause&lt;/p&gt;



### leftOuterJoin

    \DbQuery DbQueryCore::leftOuterJoin(string $table, string|null $alias, string|null $on)

Adds a LEFT OUTER JOIN clause



* Visibility: **public**


#### Arguments
* $table **string** - &lt;p&gt;Table name (without prefix)&lt;/p&gt;
* $alias **string|null** - &lt;p&gt;Table alias&lt;/p&gt;
* $on **string|null** - &lt;p&gt;ON clause&lt;/p&gt;



### naturalJoin

    \DbQuery DbQueryCore::naturalJoin(string $table, string|null $alias)

Adds a NATURAL JOIN clause



* Visibility: **public**


#### Arguments
* $table **string** - &lt;p&gt;Table name (without prefix)&lt;/p&gt;
* $alias **string|null** - &lt;p&gt;Table alias&lt;/p&gt;



### rightJoin

    \DbQuery DbQueryCore::rightJoin(string $table, string|null $alias, string|null $on)

Adds a RIGHT JOIN clause



* Visibility: **public**


#### Arguments
* $table **string** - &lt;p&gt;Table name (without prefix)&lt;/p&gt;
* $alias **string|null** - &lt;p&gt;Table alias&lt;/p&gt;
* $on **string|null** - &lt;p&gt;ON clause&lt;/p&gt;



### where

    \DbQuery DbQueryCore::where(string $restriction)

Adds a restriction in WHERE clause (each restriction will be separated by AND statement)



* Visibility: **public**


#### Arguments
* $restriction **string**



### having

    \DbQuery DbQueryCore::having(string $restriction)

Adds a restriction in HAVING clause (each restriction will be separated by AND statement)



* Visibility: **public**


#### Arguments
* $restriction **string**



### orderBy

    \DbQuery DbQueryCore::orderBy(string $fields)

Adds an ORDER BY restriction



* Visibility: **public**


#### Arguments
* $fields **string** - &lt;p&gt;List of fields to sort. E.g. $this-&gt;order(&#039;myField, b.mySecondField DESC&#039;)&lt;/p&gt;



### groupBy

    \DbQuery DbQueryCore::groupBy(string $fields)

Adds a GROUP BY restriction



* Visibility: **public**


#### Arguments
* $fields **string** - &lt;p&gt;List of fields to group. E.g. $this-&gt;group(&#039;myField1, myField2&#039;)&lt;/p&gt;



### limit

    \DbQuery DbQueryCore::limit(integer $limit, integer $offset)

Sets query offset and limit



* Visibility: **public**


#### Arguments
* $limit **integer**
* $offset **integer**



### build

    string DbQueryCore::build()

Generates query and return SQL string



* Visibility: **public**




### __toString

    string DbQueryCore::__toString()

Converts object to string



* Visibility: **public**



