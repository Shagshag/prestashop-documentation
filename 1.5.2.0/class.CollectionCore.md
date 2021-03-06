Class CollectionCore
=====================

Create a collection of ObjectModel objects



* Class name: CollectionCore
* Source: [classes/Collection.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L33)
* This class implements: Iterator, ArrayAccess, Countable

Contents
--------

### Constants

* [INNER_JOIN](#constant-INNER_JOIN)
* [LANG_ALIAS](#constant-LANG_ALIAS)
* [LEFT_JOIN](#constant-LEFT_JOIN)
* [LEFT_OUTER_JOIN](#constant-LEFT_OUTER_JOIN)

### Properties

* [$alias](#property-$alias)
* [$alias_iterator](#property-$alias_iterator)
* [$association_definition](#property-$association_definition)
* [$classname](#property-$classname)
* [$definition](#property-$definition)
* [$fields](#property-$fields)
* [$id_lang](#property-$id_lang)
* [$is_hydrated](#property-$is_hydrated)
* [$iterator](#property-$iterator)
* [$join_list](#property-$join_list)
* [$query](#property-$query)
* [$results](#property-$results)
* [$total](#property-$total)

### Methods

* [__construct](#method-__construct)
* [count](#method-count)
* [current](#method-current)
* [formatValue](#method-formatValue)
* [generateAlias](#method-generateAlias)
* [getAll](#method-getAll)
* [getDefinition](#method-getDefinition)
* [getFieldInfo](#method-getFieldInfo)
* [getFirst](#method-getFirst)
* [getResults](#method-getResults)
* [groupBy](#method-groupBy)
* [having](#method-having)
* [join](#method-join)
* [key](#method-key)
* [next](#method-next)
* [offsetExists](#method-offsetExists)
* [offsetGet](#method-offsetGet)
* [offsetSet](#method-offsetSet)
* [offsetUnset](#method-offsetUnset)
* [orderBy](#method-orderBy)
* [parseField](#method-parseField)
* [parseFields](#method-parseFields)
* [rewind](#method-rewind)
* [sqlGroupBy](#method-sqlGroupBy)
* [sqlHaving](#method-sqlHaving)
* [sqlOrderBy](#method-sqlOrderBy)
* [sqlWhere](#method-sqlWhere)
* [valid](#method-valid)
* [where](#method-where)


Constants
----------


### <a name="constant-INNER_JOIN"></a>INNER_JOIN

```php
const INNER_JOIN = 2
```





* Source: [classes/Collection.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L36).


### <a name="constant-LANG_ALIAS"></a>LANG_ALIAS

```php
const LANG_ALIAS = 'l'
```





* Source: [classes/Collection.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L85).


### <a name="constant-LEFT_JOIN"></a>LEFT_JOIN

```php
const LEFT_JOIN = 1
```





* Source: [classes/Collection.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L35).


### <a name="constant-LEFT_OUTER_JOIN"></a>LEFT_OUTER_JOIN

```php
const LEFT_OUTER_JOIN = 3
```





* Source: [classes/Collection.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L37).


Properties
----------


### <a name="property-$alias"></a>$alias

```php
protected mixed $alias = array()
```





* Visibility: **protected**
* Source: [classes/Collection.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L80).


### <a name="property-$alias_iterator"></a>$alias_iterator

```php
protected mixed $alias_iterator
```





* Visibility: **protected**
* Source: [classes/Collection.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L81).


### <a name="property-$association_definition"></a>$association_definition

```php
protected mixed $association_definition = array()
```





* Visibility: **protected**
* Source: [classes/Collection.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L83).


### <a name="property-$classname"></a>$classname

```php
protected string $classname
```





* Visibility: **protected**
* Source: [classes/Collection.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L42).


### <a name="property-$definition"></a>$definition

```php
protected array $definition = array()
```





* Visibility: **protected**
* Source: [classes/Collection.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L52).


### <a name="property-$fields"></a>$fields

```php
protected mixed $fields = array()
```





* Visibility: **protected**
* Source: [classes/Collection.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L79).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang
```





* Visibility: **protected**
* Source: [classes/Collection.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L47).


### <a name="property-$is_hydrated"></a>$is_hydrated

```php
protected boolean $is_hydrated = false
```





* Visibility: **protected**
* Source: [classes/Collection.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L67).


### <a name="property-$iterator"></a>$iterator

```php
protected integer $iterator
```





* Visibility: **protected**
* Source: [classes/Collection.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L72).


### <a name="property-$join_list"></a>$join_list

```php
protected mixed $join_list = array()
```





* Visibility: **protected**
* Source: [classes/Collection.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L82).


### <a name="property-$query"></a>$query

```php
protected \DbQuery $query
```





* Visibility: **protected**
* Source: [classes/Collection.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L57).


### <a name="property-$results"></a>$results

```php
protected array $results = array()
```





* Visibility: **protected**
* Source: [classes/Collection.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L62).


### <a name="property-$total"></a>$total

```php
protected integer $total
```





* Visibility: **protected**
* Source: [classes/Collection.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L77).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed CollectionCore::__construct(string $classname, integer $id_lang)
```





* Visibility: **public**
* Source: [classes/Collection.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L91)


#### Arguments
* $classname **string**
* $id_lang **integer**



### <a name="method-count"></a>count

```php
integer CollectionCore::count()
```

Get total of results



* Visibility: **public**
* Source: [classes/Collection.php line 435](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L435)




### <a name="method-current"></a>current

```php
\ObjectModel CollectionCore::current()
```

Get current result



* Visibility: **public**
* Source: [classes/Collection.php line 392](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L392)




### <a name="method-formatValue"></a>formatValue

```php
mixed CollectionCore::formatValue(mixed $value, string $field)
```

Format a value with the type of the given field



* Visibility: **protected**
* Source: [classes/Collection.php line 596](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L596)


#### Arguments
* $value **mixed**
* $field **string** - Field name



### <a name="method-generateAlias"></a>generateAlias

```php
string CollectionCore::generateAlias(string $association)
```

Generate uniq alias from association name



* Visibility: **protected**
* Source: [classes/Collection.php line 670](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L670)


#### Arguments
* $association **string** - Use empty association for alias on current table



### <a name="method-getAll"></a>getAll

```php
\Collection CollectionCore::getAll(boolean $display_query)
```

Launch sql query to create collection of objects



* Visibility: **public**
* Source: [classes/Collection.php line 301](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L301)


#### Arguments
* $display_query **boolean** - If true, query will be displayed (for debug purpose)



### <a name="method-getDefinition"></a>getDefinition

```php
array CollectionCore::getDefinition(string $association)
```

Get definition of an association



* Visibility: **protected**
* Source: [classes/Collection.php line 506](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L506)


#### Arguments
* $association **string**



### <a name="method-getFieldInfo"></a>getFieldInfo

```php
array CollectionCore::getFieldInfo(string $field)
```

Obtain some information on a field (alias, name, type, etc.)



* Visibility: **protected**
* Source: [classes/Collection.php line 615](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L615)


#### Arguments
* $field **string** - Field name



### <a name="method-getFirst"></a>getFirst

```php
\ObjectModel CollectionCore::getFirst()
```

Retrieve the first result



* Visibility: **public**
* Source: [classes/Collection.php line 354](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L354)




### <a name="method-getResults"></a>getResults

```php
array CollectionCore::getResults()
```

Get results array



* Visibility: **public**
* Source: [classes/Collection.php line 367](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L367)




### <a name="method-groupBy"></a>groupBy

```php
\Collection CollectionCore::groupBy(string $field)
```

Add GROUP BY restriction on query



* Visibility: **public**
* Source: [classes/Collection.php line 277](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L277)


#### Arguments
* $field **string** - Field name



### <a name="method-having"></a>having

```php
\Collection CollectionCore::having(string $field, string $operator, mixed $value)
```

Add HAVING restriction on query



* Visibility: **public**
* Source: [classes/Collection.php line 226](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L226)


#### Arguments
* $field **string** - Field name
* $operator **string** - List of operators : =, !=, , =, like, notlike, regexp, notregexp
* $value **mixed**



### <a name="method-join"></a>join

```php
\Collection CollectionCore::join($association, string $on, integer $type)
```

Join current entity to an associated entity



* Visibility: **public**
* Source: [classes/Collection.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L113)


#### Arguments
* $association **mixed** - Association name
* $on **string**
* $type **integer**



### <a name="method-key"></a>key

```php
integer CollectionCore::key()
```

Get current result index



* Visibility: **public**
* Source: [classes/Collection.php line 414](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L414)




### <a name="method-next"></a>next

```php
mixed CollectionCore::next()
```

Go to next result



* Visibility: **public**
* Source: [classes/Collection.php line 424](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L424)




### <a name="method-offsetExists"></a>offsetExists

```php
boolean CollectionCore::offsetExists($offset)
```

Check if a result exist



* Visibility: **public**
* Source: [classes/Collection.php line 448](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L448)


#### Arguments
* $offset **mixed**



### <a name="method-offsetGet"></a>offsetGet

```php
\ObjectModel CollectionCore::offsetGet($offset)
```

Get a result by offset



* Visibility: **public**
* Source: [classes/Collection.php line 461](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L461)


#### Arguments
* $offset **mixed**



### <a name="method-offsetSet"></a>offsetSet

```php
mixed CollectionCore::offsetSet($offset, $value)
```

Add an element in the collection



* Visibility: **public**
* Source: [classes/Collection.php line 476](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L476)


#### Arguments
* $offset **mixed**
* $value **mixed**



### <a name="method-offsetUnset"></a>offsetUnset

```php
mixed CollectionCore::offsetUnset($offset)
```

Delete an element from the collection



* Visibility: **public**
* Source: [classes/Collection.php line 494](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L494)


#### Arguments
* $offset **mixed**



### <a name="method-orderBy"></a>orderBy

```php
\Collection CollectionCore::orderBy(string $field, string $order)
```

Add ORDER BY restriction on query



* Visibility: **public**
* Source: [classes/Collection.php line 250](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L250)


#### Arguments
* $field **string** - Field name
* $order **string** - asc|desc



### <a name="method-parseField"></a>parseField

```php
string CollectionCore::parseField(string $field)
```

Replace a field with its SQL version (E.g. manufacturer.name with a2.name)



* Visibility: **protected**
* Source: [classes/Collection.php line 583](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L583)


#### Arguments
* $field **string** - Field name



### <a name="method-parseFields"></a>parseFields

```php
string CollectionCore::parseFields(string $str)
```

Parse all fields with {field} syntax in a string



* Visibility: **protected**
* Source: [classes/Collection.php line 569](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L569)


#### Arguments
* $str **string**



### <a name="method-rewind"></a>rewind

```php
mixed CollectionCore::rewind()
```

This method is called when a foreach begin



* Visibility: **public**
* Source: [classes/Collection.php line 378](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L378)




### <a name="method-sqlGroupBy"></a>sqlGroupBy

```php
\Collection CollectionCore::sqlGroupBy(string $sql)
```

Add GROUP BY restriction on query using real SQL syntax



* Visibility: **public**
* Source: [classes/Collection.php line 289](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L289)


#### Arguments
* $sql **string**



### <a name="method-sqlHaving"></a>sqlHaving

```php
\Collection CollectionCore::sqlHaving(string $sql)
```

Add HAVING restriction on query using real SQL syntax



* Visibility: **public**
* Source: [classes/Collection.php line 237](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L237)


#### Arguments
* $sql **string**



### <a name="method-sqlOrderBy"></a>sqlOrderBy

```php
\Collection CollectionCore::sqlOrderBy(string $sql)
```

Add ORDER BY restriction on query using real SQL syntax



* Visibility: **public**
* Source: [classes/Collection.php line 265](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L265)


#### Arguments
* $sql **string**



### <a name="method-sqlWhere"></a>sqlWhere

```php
\Collection CollectionCore::sqlWhere(string $sql)
```

Add WHERE restriction on query using real SQL syntax



* Visibility: **public**
* Source: [classes/Collection.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L212)


#### Arguments
* $sql **string**



### <a name="method-valid"></a>valid

```php
boolean CollectionCore::valid()
```

Check if there is a current result



* Visibility: **public**
* Source: [classes/Collection.php line 403](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L403)




### <a name="method-where"></a>where

```php
\Collection CollectionCore::where(string $field, string $operator, mixed $value, $method)
```

Add WHERE restriction on query



* Visibility: **public**
* Source: [classes/Collection.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/Collection.php#L148)


#### Arguments
* $field **string** - Field name
* $operator **string** - List of operators : =, !=, , =, like, notlike, regexp, notregexp
* $value **mixed**
* $method **mixed**


