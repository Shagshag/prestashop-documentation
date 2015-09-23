Class CollectionCore
=====================

Create a collection of ObjectModel objects



* Class name: CollectionCore
* Source: [classes/Collection.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L33)
* This class implements: Iterator, ArrayAccess, Countable

Contents
--------


### Properties

* [$alias](#property-$alias)
* [$alias_iterator](#property-$alias_iterator)
* [$classname](#property-$classname)
* [$definition](#property-$definition)
* [$fields](#property-$fields)
* [$id_lang](#property-$id_lang)
* [$is_hydrated](#property-$is_hydrated)
* [$iterator](#property-$iterator)
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
* [getFieldInfo](#method-getFieldInfo)
* [getResults](#method-getResults)
* [groupBy](#method-groupBy)
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
* [sqlWhere](#method-sqlWhere)
* [valid](#method-valid)
* [where](#method-where)




Properties
----------


### <a name="property-$alias"></a>$alias

```php
protected mixed $alias = array()
```





* Visibility: **protected**
* Source: [classes/Collection.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L76).


### <a name="property-$alias_iterator"></a>$alias_iterator

```php
protected mixed $alias_iterator
```





* Visibility: **protected**
* Source: [classes/Collection.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L77).


### <a name="property-$classname"></a>$classname

```php
protected string $classname
```





* Visibility: **protected**
* Source: [classes/Collection.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L38).


### <a name="property-$definition"></a>$definition

```php
protected array $definition = array()
```





* Visibility: **protected**
* Source: [classes/Collection.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L48).


### <a name="property-$fields"></a>$fields

```php
protected mixed $fields = array()
```





* Visibility: **protected**
* Source: [classes/Collection.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L75).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang
```





* Visibility: **protected**
* Source: [classes/Collection.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L43).


### <a name="property-$is_hydrated"></a>$is_hydrated

```php
protected boolean $is_hydrated = false
```





* Visibility: **protected**
* Source: [classes/Collection.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L63).


### <a name="property-$iterator"></a>$iterator

```php
protected integer $iterator
```





* Visibility: **protected**
* Source: [classes/Collection.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L68).


### <a name="property-$query"></a>$query

```php
protected \DbQuery $query
```





* Visibility: **protected**
* Source: [classes/Collection.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L53).


### <a name="property-$results"></a>$results

```php
protected array $results = array()
```





* Visibility: **protected**
* Source: [classes/Collection.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L58).


### <a name="property-$total"></a>$total

```php
protected integer $total
```





* Visibility: **protected**
* Source: [classes/Collection.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L73).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed CollectionCore::__construct(string $classname, integer $id_lang)
```





* Visibility: **public**
* Source: [classes/Collection.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L83)


#### Arguments
* $classname **string**
* $id_lang **integer**



### <a name="method-count"></a>count

```php
integer CollectionCore::count()
```

Get total of results



* Visibility: **public**
* Source: [classes/Collection.php line 307](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L307)




### <a name="method-current"></a>current

```php
\ObjectModel CollectionCore::current()
```

Get current result



* Visibility: **public**
* Source: [classes/Collection.php line 264](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L264)




### <a name="method-formatValue"></a>formatValue

```php
mixed CollectionCore::formatValue(mixed $value, string $field)
```

Format a value with the type of the given field



* Visibility: **protected**
* Source: [classes/Collection.php line 404](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L404)


#### Arguments
* $value **mixed**
* $field **string** - Field name



### <a name="method-generateAlias"></a>generateAlias

```php
string CollectionCore::generateAlias(string $association)
```

Generate uniq alias from association name



* Visibility: **protected**
* Source: [classes/Collection.php line 462](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L462)


#### Arguments
* $association **string** - Use empty association for alias on current table



### <a name="method-getAll"></a>getAll

```php
\Collection CollectionCore::getAll(boolean $display_query)
```

Launch sql query to create collection of objects



* Visibility: **public**
* Source: [classes/Collection.php line 219](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L219)


#### Arguments
* $display_query **boolean** - If true, query will be displayed (for debug purpose)



### <a name="method-getFieldInfo"></a>getFieldInfo

```php
array CollectionCore::getFieldInfo(string $field)
```

Obtain some information on a field (alias, name, type, etc.)



* Visibility: **protected**
* Source: [classes/Collection.php line 423](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L423)


#### Arguments
* $field **string** - Field name



### <a name="method-getResults"></a>getResults

```php
array CollectionCore::getResults()
```

Get results array



* Visibility: **public**
* Source: [classes/Collection.php line 239](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L239)




### <a name="method-groupBy"></a>groupBy

```php
\Collection CollectionCore::groupBy(string $field)
```

Add GROUP BY restriction on query



* Visibility: **public**
* Source: [classes/Collection.php line 207](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L207)


#### Arguments
* $field **string** - Field name



### <a name="method-key"></a>key

```php
integer CollectionCore::key()
```

Get current result index



* Visibility: **public**
* Source: [classes/Collection.php line 286](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L286)




### <a name="method-next"></a>next

```php
mixed CollectionCore::next()
```

Go to next result



* Visibility: **public**
* Source: [classes/Collection.php line 296](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L296)




### <a name="method-offsetExists"></a>offsetExists

```php
boolean CollectionCore::offsetExists($offset)
```

Check if a result exist



* Visibility: **public**
* Source: [classes/Collection.php line 320](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L320)


#### Arguments
* $offset **mixed**



### <a name="method-offsetGet"></a>offsetGet

```php
\ObjectModel CollectionCore::offsetGet($offset)
```

Get a result by offset



* Visibility: **public**
* Source: [classes/Collection.php line 333](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L333)


#### Arguments
* $offset **mixed**



### <a name="method-offsetSet"></a>offsetSet

```php
mixed CollectionCore::offsetSet($offset, $value)
```

Add an element in the collection



* Visibility: **public**
* Source: [classes/Collection.php line 348](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L348)


#### Arguments
* $offset **mixed**
* $value **mixed**



### <a name="method-offsetUnset"></a>offsetUnset

```php
mixed CollectionCore::offsetUnset($offset)
```

Delete an element from the collection



* Visibility: **public**
* Source: [classes/Collection.php line 366](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L366)


#### Arguments
* $offset **mixed**



### <a name="method-orderBy"></a>orderBy

```php
\Collection CollectionCore::orderBy(string $field, string $order)
```

Add ORDER BY restriction on query



* Visibility: **public**
* Source: [classes/Collection.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L192)


#### Arguments
* $field **string** - Field name
* $order **string** - asc|desc



### <a name="method-parseField"></a>parseField

```php
string CollectionCore::parseField(string $field)
```

Replace a field with its SQL version (E.g. manufacturer.name with a2.name)



* Visibility: **protected**
* Source: [classes/Collection.php line 392](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L392)


#### Arguments
* $field **string** - Field name



### <a name="method-parseFields"></a>parseFields

```php
string CollectionCore::parseFields(string $str)
```

Parse all fields with {field} syntax in a string



* Visibility: **protected**
* Source: [classes/Collection.php line 378](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L378)


#### Arguments
* $str **string**



### <a name="method-rewind"></a>rewind

```php
mixed CollectionCore::rewind()
```

This method is called when a foreach begin



* Visibility: **public**
* Source: [classes/Collection.php line 250](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L250)




### <a name="method-sqlWhere"></a>sqlWhere

```php
mixed CollectionCore::sqlWhere(string $sql)
```

Add WHERE restriction on query using real SQL syntax



* Visibility: **public**
* Source: [classes/Collection.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L179)


#### Arguments
* $sql **string**



### <a name="method-valid"></a>valid

```php
boolean CollectionCore::valid()
```

Check if there is a current result



* Visibility: **public**
* Source: [classes/Collection.php line 275](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L275)




### <a name="method-where"></a>where

```php
\Collection CollectionCore::where(string $field, string $operator, mixed $value)
```

Add WHERE restriction on query



* Visibility: **public**
* Source: [classes/Collection.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Collection.php#L119)


#### Arguments
* $field **string** - Field name
* $operator **string** - List of operators : =, !=, , =, like, notlike, regexp, notregexp
* $value **mixed**


