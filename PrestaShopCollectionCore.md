PrestaShopCollectionCore
===============

Create a collection of ObjectModel objects




* Class name: PrestaShopCollectionCore
* Namespace: 
* This class implements: Iterator, ArrayAccess, Countable
* This class is defined in [classes/PrestaShopCollection.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#32)



Constants
----------


### LEFT_JOIN

    const LEFT_JOIN = 1



* This constant is defined in [classes/PrestaShopCollection.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#34)


### INNER_JOIN

    const INNER_JOIN = 2



* This constant is defined in [classes/PrestaShopCollection.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#35)


### LEFT_OUTER_JOIN

    const LEFT_OUTER_JOIN = 3



* This constant is defined in [classes/PrestaShopCollection.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#36)


### LANG_ALIAS

    const LANG_ALIAS = 'l'



* This constant is defined in [classes/PrestaShopCollection.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#94)


Properties
----------


### $classname

    protected string $classname





* Visibility: **protected**
* This property is defined in [classes/PrestaShopCollection.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#41)


### $id_lang

    protected integer $id_lang





* Visibility: **protected**
* This property is defined in [classes/PrestaShopCollection.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#46)


### $definition

    protected array $definition = array()





* Visibility: **protected**
* This property is defined in [classes/PrestaShopCollection.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#51)


### $query

    protected \DbQuery $query





* Visibility: **protected**
* This property is defined in [classes/PrestaShopCollection.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#56)


### $results

    protected array $results = array()





* Visibility: **protected**
* This property is defined in [classes/PrestaShopCollection.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#61)


### $is_hydrated

    protected boolean $is_hydrated = false





* Visibility: **protected**
* This property is defined in [classes/PrestaShopCollection.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#66)


### $iterator

    protected integer $iterator





* Visibility: **protected**
* This property is defined in [classes/PrestaShopCollection.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#71)


### $total

    protected integer $total





* Visibility: **protected**
* This property is defined in [classes/PrestaShopCollection.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#76)


### $page_number

    protected integer $page_number





* Visibility: **protected**
* This property is defined in [classes/PrestaShopCollection.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#81)


### $page_size

    protected integer $page_size





* Visibility: **protected**
* This property is defined in [classes/PrestaShopCollection.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#86)


### $fields

    protected mixed $fields = array()





* Visibility: **protected**
* This property is defined in [classes/PrestaShopCollection.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#88)


### $alias

    protected mixed $alias = array()





* Visibility: **protected**
* This property is defined in [classes/PrestaShopCollection.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#89)


### $alias_iterator

    protected mixed $alias_iterator





* Visibility: **protected**
* This property is defined in [classes/PrestaShopCollection.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#90)


### $join_list

    protected mixed $join_list = array()





* Visibility: **protected**
* This property is defined in [classes/PrestaShopCollection.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#91)


### $association_definition

    protected mixed $association_definition = array()





* Visibility: **protected**
* This property is defined in [classes/PrestaShopCollection.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#92)


Methods
-------


### __construct

    mixed PrestaShopCollectionCore::__construct(string $classname, integer $id_lang)





* Visibility: **public**
* This method is defined in [classes/PrestaShopCollection.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#100)


#### Arguments
* $classname **string**
* $id_lang **integer**



### join

    \PrestaShopCollection PrestaShopCollectionCore::join(string $association, string $on, integer $type)

Join current entity to an associated entity



* Visibility: **public**
* This method is defined in [classes/PrestaShopCollection.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#123)


#### Arguments
* $association **string** - &lt;p&gt;Association name&lt;/p&gt;
* $on **string**
* $type **integer**



### where

    \PrestaShopCollection PrestaShopCollectionCore::where(string $field, string $operator, mixed $value, $method)

Add WHERE restriction on query



* Visibility: **public**
* This method is defined in [classes/PrestaShopCollection.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#160)


#### Arguments
* $field **string** - &lt;p&gt;Field name&lt;/p&gt;
* $operator **string** - &lt;p&gt;List of operators : =, !=, &lt;&gt;, &lt;, &lt;=, &gt;, &gt;=, like, notlike, regexp, notregexp&lt;/p&gt;
* $value **mixed**
* $method **mixed**



### sqlWhere

    \PrestaShopCollection PrestaShopCollectionCore::sqlWhere(string $sql)

Add WHERE restriction on query using real SQL syntax



* Visibility: **public**
* This method is defined in [classes/PrestaShopCollection.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#221)


#### Arguments
* $sql **string**



### having

    \PrestaShopCollection PrestaShopCollectionCore::having(string $field, string $operator, mixed $value)

Add HAVING restriction on query



* Visibility: **public**
* This method is defined in [classes/PrestaShopCollection.php line 235](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#235)


#### Arguments
* $field **string** - &lt;p&gt;Field name&lt;/p&gt;
* $operator **string** - &lt;p&gt;List of operators : =, !=, &lt;&gt;, &lt;, &lt;=, &gt;, &gt;=, like, notlike, regexp, notregexp&lt;/p&gt;
* $value **mixed**



### sqlHaving

    \PrestaShopCollection PrestaShopCollectionCore::sqlHaving(string $sql)

Add HAVING restriction on query using real SQL syntax



* Visibility: **public**
* This method is defined in [classes/PrestaShopCollection.php line 246](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#246)


#### Arguments
* $sql **string**



### orderBy

    \PrestaShopCollection PrestaShopCollectionCore::orderBy(string $field, string $order)

Add ORDER BY restriction on query



* Visibility: **public**
* This method is defined in [classes/PrestaShopCollection.php line 259](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#259)


#### Arguments
* $field **string** - &lt;p&gt;Field name&lt;/p&gt;
* $order **string** - &lt;p&gt;asc|desc&lt;/p&gt;



### sqlOrderBy

    \PrestaShopCollection PrestaShopCollectionCore::sqlOrderBy(string $sql)

Add ORDER BY restriction on query using real SQL syntax



* Visibility: **public**
* This method is defined in [classes/PrestaShopCollection.php line 275](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#275)


#### Arguments
* $sql **string**



### groupBy

    \PrestaShopCollection PrestaShopCollectionCore::groupBy(string $field)

Add GROUP BY restriction on query



* Visibility: **public**
* This method is defined in [classes/PrestaShopCollection.php line 287](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#287)


#### Arguments
* $field **string** - &lt;p&gt;Field name&lt;/p&gt;



### sqlGroupBy

    \PrestaShopCollection PrestaShopCollectionCore::sqlGroupBy(string $sql)

Add GROUP BY restriction on query using real SQL syntax



* Visibility: **public**
* This method is defined in [classes/PrestaShopCollection.php line 299](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#299)


#### Arguments
* $sql **string**



### getAll

    \PrestaShopCollection PrestaShopCollectionCore::getAll(boolean $display_query)

Launch sql query to create collection of objects



* Visibility: **public**
* This method is defined in [classes/PrestaShopCollection.php line 311](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#311)


#### Arguments
* $display_query **boolean** - &lt;p&gt;If true, query will be displayed (for debug purpose)&lt;/p&gt;



### getFirst

    \ObjectModel PrestaShopCollectionCore::getFirst()

Retrieve the first result



* Visibility: **public**
* This method is defined in [classes/PrestaShopCollection.php line 370](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#370)




### getResults

    array PrestaShopCollectionCore::getResults()

Get results array



* Visibility: **public**
* This method is defined in [classes/PrestaShopCollection.php line 384](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#384)




### rewind

    mixed PrestaShopCollectionCore::rewind()

This method is called when a foreach begin



* Visibility: **public**
* This method is defined in [classes/PrestaShopCollection.php line 395](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#395)




### current

    \ObjectModel PrestaShopCollectionCore::current()

Get current result



* Visibility: **public**
* This method is defined in [classes/PrestaShopCollection.php line 409](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#409)




### valid

    boolean PrestaShopCollectionCore::valid()

Check if there is a current result



* Visibility: **public**
* This method is defined in [classes/PrestaShopCollection.php line 420](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#420)




### key

    integer PrestaShopCollectionCore::key()

Get current result index



* Visibility: **public**
* This method is defined in [classes/PrestaShopCollection.php line 431](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#431)




### next

    mixed PrestaShopCollectionCore::next()

Go to next result



* Visibility: **public**
* This method is defined in [classes/PrestaShopCollection.php line 441](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#441)




### count

    integer PrestaShopCollectionCore::count()

Get total of results



* Visibility: **public**
* This method is defined in [classes/PrestaShopCollection.php line 452](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#452)




### offsetExists

    boolean PrestaShopCollectionCore::offsetExists($offset)

Check if a result exist



* Visibility: **public**
* This method is defined in [classes/PrestaShopCollection.php line 465](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#465)


#### Arguments
* $offset **mixed**



### offsetGet

    \ObjectModel PrestaShopCollectionCore::offsetGet($offset)

Get a result by offset



* Visibility: **public**
* This method is defined in [classes/PrestaShopCollection.php line 478](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#478)


#### Arguments
* $offset **mixed**



### offsetSet

    mixed PrestaShopCollectionCore::offsetSet($offset, $value)

Add an element in the collection



* Visibility: **public**
* This method is defined in [classes/PrestaShopCollection.php line 494](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#494)


#### Arguments
* $offset **mixed**
* $value **mixed**



### offsetUnset

    mixed PrestaShopCollectionCore::offsetUnset($offset)

Delete an element from the collection



* Visibility: **public**
* This method is defined in [classes/PrestaShopCollection.php line 514](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#514)


#### Arguments
* $offset **mixed**



### getDefinition

    array PrestaShopCollectionCore::getDefinition(string $association)

Get definition of an association



* Visibility: **protected**
* This method is defined in [classes/PrestaShopCollection.php line 526](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#526)


#### Arguments
* $association **string**



### parseFields

    string PrestaShopCollectionCore::parseFields(string $str)

Parse all fields with {field} syntax in a string



* Visibility: **protected**
* This method is defined in [classes/PrestaShopCollection.php line 590](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#590)


#### Arguments
* $str **string**



### parseField

    string PrestaShopCollectionCore::parseField(string $field)

Replace a field with its SQL version (E.g. manufacturer.name with a2.name)



* Visibility: **protected**
* This method is defined in [classes/PrestaShopCollection.php line 605](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#605)


#### Arguments
* $field **string** - &lt;p&gt;Field name&lt;/p&gt;



### formatValue

    mixed PrestaShopCollectionCore::formatValue(mixed $value, string $field)

Format a value with the type of the given field



* Visibility: **protected**
* This method is defined in [classes/PrestaShopCollection.php line 618](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#618)


#### Arguments
* $value **mixed**
* $field **string** - &lt;p&gt;Field name&lt;/p&gt;



### getFieldInfo

    array PrestaShopCollectionCore::getFieldInfo(string $field)

Obtain some information on a field (alias, name, type, etc.)



* Visibility: **protected**
* This method is defined in [classes/PrestaShopCollection.php line 637](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#637)


#### Arguments
* $field **string** - &lt;p&gt;Field name&lt;/p&gt;



### setPageNumber

    \PrestaShopCollection PrestaShopCollectionCore::setPageNumber(integer $page_number)

Set the page number



* Visibility: **public**
* This method is defined in [classes/PrestaShopCollection.php line 690](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#690)


#### Arguments
* $page_number **integer**



### setPageSize

    \PrestaShopCollection PrestaShopCollectionCore::setPageSize(integer $page_size)

Set the nuber of item per page



* Visibility: **public**
* This method is defined in [classes/PrestaShopCollection.php line 707](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#707)


#### Arguments
* $page_size **integer**



### generateAlias

    string PrestaShopCollectionCore::generateAlias(string $association)

Generate uniq alias from association name



* Visibility: **protected**
* This method is defined in [classes/PrestaShopCollection.php line 719](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopCollection.php#719)


#### Arguments
* $association **string** - &lt;p&gt;Use empty association for alias on current table&lt;/p&gt;


