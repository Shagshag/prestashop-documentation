Class CollectionCore
=====================

Create a collection of ObjectModel objects



* Class name: CollectionCore
* Source: [classes/Collection.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L32)
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
* [$page_number](#property-$page_number)
* [$page_size](#property-$page_size)
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
* [setPageNumber](#method-setPageNumber)
* [setPageSize](#method-setPageSize)
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





* Source: [classes/Collection.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L35).


### <a name="constant-LANG_ALIAS"></a>LANG_ALIAS

```php
const LANG_ALIAS = 'l'
```





* Source: [classes/Collection.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L94).


### <a name="constant-LEFT_JOIN"></a>LEFT_JOIN

```php
const LEFT_JOIN = 1
```





* Source: [classes/Collection.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L34).


### <a name="constant-LEFT_OUTER_JOIN"></a>LEFT_OUTER_JOIN

```php
const LEFT_OUTER_JOIN = 3
```





* Source: [classes/Collection.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L36).


Properties
----------


### <a name="property-$alias"></a>$alias

```php
protected mixed $alias = array()
```





* Visibility: **protected**
* Source: [classes/Collection.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L89).


### <a name="property-$alias_iterator"></a>$alias_iterator

```php
protected mixed $alias_iterator
```





* Visibility: **protected**
* Source: [classes/Collection.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L90).


### <a name="property-$association_definition"></a>$association_definition

```php
protected mixed $association_definition = array()
```





* Visibility: **protected**
* Source: [classes/Collection.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L92).


### <a name="property-$classname"></a>$classname

```php
protected string $classname
```





* Visibility: **protected**
* Source: [classes/Collection.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L41).


### <a name="property-$definition"></a>$definition

```php
protected array $definition = array()
```





* Visibility: **protected**
* Source: [classes/Collection.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L51).


### <a name="property-$fields"></a>$fields

```php
protected mixed $fields = array()
```





* Visibility: **protected**
* Source: [classes/Collection.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L88).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang
```





* Visibility: **protected**
* Source: [classes/Collection.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L46).


### <a name="property-$is_hydrated"></a>$is_hydrated

```php
protected boolean $is_hydrated = false
```





* Visibility: **protected**
* Source: [classes/Collection.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L66).


### <a name="property-$iterator"></a>$iterator

```php
protected integer $iterator
```





* Visibility: **protected**
* Source: [classes/Collection.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L71).


### <a name="property-$join_list"></a>$join_list

```php
protected mixed $join_list = array()
```





* Visibility: **protected**
* Source: [classes/Collection.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L91).


### <a name="property-$page_number"></a>$page_number

```php
protected integer $page_number
```





* Visibility: **protected**
* Source: [classes/Collection.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L81).


### <a name="property-$page_size"></a>$page_size

```php
protected integer $page_size
```





* Visibility: **protected**
* Source: [classes/Collection.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L86).


### <a name="property-$query"></a>$query

```php
protected \DbQuery $query
```





* Visibility: **protected**
* Source: [classes/Collection.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L56).


### <a name="property-$results"></a>$results

```php
protected array $results = array()
```





* Visibility: **protected**
* Source: [classes/Collection.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L61).


### <a name="property-$total"></a>$total

```php
protected integer $total
```





* Visibility: **protected**
* Source: [classes/Collection.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L76).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed CollectionCore::__construct(string $classname, integer $id_lang)
```





* Visibility: **public**
* Source: [classes/Collection.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L100)


#### Arguments
* $classname **string**
* $id_lang **integer**



### <a name="method-count"></a>count

```php
integer CollectionCore::count()
```

Get total of results



* Visibility: **public**
* Source: [classes/Collection.php line 449](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L449)




### <a name="method-current"></a>current

```php
\ObjectModel CollectionCore::current()
```

Get current result



* Visibility: **public**
* Source: [classes/Collection.php line 406](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L406)




### <a name="method-formatValue"></a>formatValue

```php
mixed CollectionCore::formatValue(mixed $value, string $field)
```

Format a value with the type of the given field



* Visibility: **protected**
* Source: [classes/Collection.php line 610](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L610)


#### Arguments
* $value **mixed**
* $field **string** - Field name



### <a name="method-generateAlias"></a>generateAlias

```php
string CollectionCore::generateAlias(string $association)
```

Generate uniq alias from association name



* Visibility: **protected**
* Source: [classes/Collection.php line 712](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L712)


#### Arguments
* $association **string** - Use empty association for alias on current table



### <a name="method-getAll"></a>getAll

```php
\Collection CollectionCore::getAll(boolean $display_query)
```

Launch sql query to create collection of objects



* Visibility: **public**
* Source: [classes/Collection.php line 310](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L310)


#### Arguments
* $display_query **boolean** - If true, query will be displayed (for debug purpose)



### <a name="method-getDefinition"></a>getDefinition

```php
array CollectionCore::getDefinition(string $association)
```

Get definition of an association



* Visibility: **protected**
* Source: [classes/Collection.php line 520](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L520)


#### Arguments
* $association **string**



### <a name="method-getFieldInfo"></a>getFieldInfo

```php
array CollectionCore::getFieldInfo(string $field)
```

Obtain some information on a field (alias, name, type, etc.)



* Visibility: **protected**
* Source: [classes/Collection.php line 629](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L629)


#### Arguments
* $field **string** - Field name



### <a name="method-getFirst"></a>getFirst

```php
\ObjectModel CollectionCore::getFirst()
```

Retrieve the first result



* Visibility: **public**
* Source: [classes/Collection.php line 368](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L368)




### <a name="method-getResults"></a>getResults

```php
array CollectionCore::getResults()
```

Get results array



* Visibility: **public**
* Source: [classes/Collection.php line 381](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L381)




### <a name="method-groupBy"></a>groupBy

```php
\Collection CollectionCore::groupBy(string $field)
```

Add GROUP BY restriction on query



* Visibility: **public**
* Source: [classes/Collection.php line 286](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L286)


#### Arguments
* $field **string** - Field name



### <a name="method-having"></a>having

```php
\Collection CollectionCore::having(string $field, string $operator, mixed $value)
```

Add HAVING restriction on query



* Visibility: **public**
* Source: [classes/Collection.php line 235](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L235)


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
* Source: [classes/Collection.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L122)


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
* Source: [classes/Collection.php line 428](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L428)




### <a name="method-next"></a>next

```php
mixed CollectionCore::next()
```

Go to next result



* Visibility: **public**
* Source: [classes/Collection.php line 438](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L438)




### <a name="method-offsetExists"></a>offsetExists

```php
boolean CollectionCore::offsetExists($offset)
```

Check if a result exist



* Visibility: **public**
* Source: [classes/Collection.php line 462](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L462)


#### Arguments
* $offset **mixed**



### <a name="method-offsetGet"></a>offsetGet

```php
\ObjectModel CollectionCore::offsetGet($offset)
```

Get a result by offset



* Visibility: **public**
* Source: [classes/Collection.php line 475](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L475)


#### Arguments
* $offset **mixed**



### <a name="method-offsetSet"></a>offsetSet

```php
mixed CollectionCore::offsetSet($offset, $value)
```

Add an element in the collection



* Visibility: **public**
* Source: [classes/Collection.php line 490](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L490)


#### Arguments
* $offset **mixed**
* $value **mixed**



### <a name="method-offsetUnset"></a>offsetUnset

```php
mixed CollectionCore::offsetUnset($offset)
```

Delete an element from the collection



* Visibility: **public**
* Source: [classes/Collection.php line 508](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L508)


#### Arguments
* $offset **mixed**



### <a name="method-orderBy"></a>orderBy

```php
\Collection CollectionCore::orderBy(string $field, string $order)
```

Add ORDER BY restriction on query



* Visibility: **public**
* Source: [classes/Collection.php line 259](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L259)


#### Arguments
* $field **string** - Field name
* $order **string** - asc|desc



### <a name="method-parseField"></a>parseField

```php
string CollectionCore::parseField(string $field)
```

Replace a field with its SQL version (E.g. manufacturer.name with a2.name)



* Visibility: **protected**
* Source: [classes/Collection.php line 597](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L597)


#### Arguments
* $field **string** - Field name



### <a name="method-parseFields"></a>parseFields

```php
string CollectionCore::parseFields(string $str)
```

Parse all fields with {field} syntax in a string



* Visibility: **protected**
* Source: [classes/Collection.php line 583](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L583)


#### Arguments
* $str **string**



### <a name="method-rewind"></a>rewind

```php
mixed CollectionCore::rewind()
```

This method is called when a foreach begin



* Visibility: **public**
* Source: [classes/Collection.php line 392](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L392)




### <a name="method-setPageNumber"></a>setPageNumber

```php
\Collection CollectionCore::setPageNumber(integer $page_number)
```

Set the page number



* Visibility: **public**
* Source: [classes/Collection.php line 684](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L684)


#### Arguments
* $page_number **integer**



### <a name="method-setPageSize"></a>setPageSize

```php
\Collection CollectionCore::setPageSize(integer $page_size)
```

Set the nuber of item per page



* Visibility: **public**
* Source: [classes/Collection.php line 700](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L700)


#### Arguments
* $page_size **integer**



### <a name="method-sqlGroupBy"></a>sqlGroupBy

```php
\Collection CollectionCore::sqlGroupBy(string $sql)
```

Add GROUP BY restriction on query using real SQL syntax



* Visibility: **public**
* Source: [classes/Collection.php line 298](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L298)


#### Arguments
* $sql **string**



### <a name="method-sqlHaving"></a>sqlHaving

```php
\Collection CollectionCore::sqlHaving(string $sql)
```

Add HAVING restriction on query using real SQL syntax



* Visibility: **public**
* Source: [classes/Collection.php line 246](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L246)


#### Arguments
* $sql **string**



### <a name="method-sqlOrderBy"></a>sqlOrderBy

```php
\Collection CollectionCore::sqlOrderBy(string $sql)
```

Add ORDER BY restriction on query using real SQL syntax



* Visibility: **public**
* Source: [classes/Collection.php line 274](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L274)


#### Arguments
* $sql **string**



### <a name="method-sqlWhere"></a>sqlWhere

```php
\Collection CollectionCore::sqlWhere(string $sql)
```

Add WHERE restriction on query using real SQL syntax



* Visibility: **public**
* Source: [classes/Collection.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L221)


#### Arguments
* $sql **string**



### <a name="method-valid"></a>valid

```php
boolean CollectionCore::valid()
```

Check if there is a current result



* Visibility: **public**
* Source: [classes/Collection.php line 417](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L417)




### <a name="method-where"></a>where

```php
\Collection CollectionCore::where(string $field, string $operator, mixed $value, $method)
```

Add WHERE restriction on query



* Visibility: **public**
* Source: [classes/Collection.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/classes/Collection.php#L157)


#### Arguments
* $field **string** - Field name
* $operator **string** - List of operators : =, !=, , =, like, notlike, regexp, notregexp
* $value **mixed**
* $method **mixed**


