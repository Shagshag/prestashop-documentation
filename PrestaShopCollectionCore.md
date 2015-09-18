PrestaShopCollectionCore
===============

Create a collection of ObjectModel objects




* Class name: PrestaShopCollectionCore
* Namespace: 
* This class implements: Iterator, ArrayAccess, Countable


Constants
----------


### LEFT_JOIN

    const LEFT_JOIN = 1





### INNER_JOIN

    const INNER_JOIN = 2





### LEFT_OUTER_JOIN

    const LEFT_OUTER_JOIN = 3





### LANG_ALIAS

    const LANG_ALIAS = 'l'





Properties
----------


### $classname

    protected string $classname





* Visibility: **protected**


### $id_lang

    protected integer $id_lang





* Visibility: **protected**


### $definition

    protected array $definition = array()





* Visibility: **protected**


### $query

    protected \DbQuery $query





* Visibility: **protected**


### $results

    protected array $results = array()





* Visibility: **protected**


### $is_hydrated

    protected boolean $is_hydrated = false





* Visibility: **protected**


### $iterator

    protected integer $iterator





* Visibility: **protected**


### $total

    protected integer $total





* Visibility: **protected**


### $page_number

    protected integer $page_number





* Visibility: **protected**


### $page_size

    protected integer $page_size





* Visibility: **protected**


### $fields

    protected mixed $fields = array()





* Visibility: **protected**


### $alias

    protected mixed $alias = array()





* Visibility: **protected**


### $alias_iterator

    protected mixed $alias_iterator





* Visibility: **protected**


### $join_list

    protected mixed $join_list = array()





* Visibility: **protected**


### $association_definition

    protected mixed $association_definition = array()





* Visibility: **protected**


Methods
-------


### __construct

    mixed PrestaShopCollectionCore::__construct(string $classname, integer $id_lang)





* Visibility: **public**


#### Arguments
* $classname **string**
* $id_lang **integer**



### join

    \PrestaShopCollection PrestaShopCollectionCore::join(string $association, string $on, integer $type)

Join current entity to an associated entity



* Visibility: **public**


#### Arguments
* $association **string** - &lt;p&gt;Association name&lt;/p&gt;
* $on **string**
* $type **integer**



### where

    \PrestaShopCollection PrestaShopCollectionCore::where(string $field, string $operator, mixed $value, $method)

Add WHERE restriction on query



* Visibility: **public**


#### Arguments
* $field **string** - &lt;p&gt;Field name&lt;/p&gt;
* $operator **string** - &lt;p&gt;List of operators : =, !=, &lt;&gt;, &lt;, &lt;=, &gt;, &gt;=, like, notlike, regexp, notregexp&lt;/p&gt;
* $value **mixed**
* $method **mixed**



### sqlWhere

    \PrestaShopCollection PrestaShopCollectionCore::sqlWhere(string $sql)

Add WHERE restriction on query using real SQL syntax



* Visibility: **public**


#### Arguments
* $sql **string**



### having

    \PrestaShopCollection PrestaShopCollectionCore::having(string $field, string $operator, mixed $value)

Add HAVING restriction on query



* Visibility: **public**


#### Arguments
* $field **string** - &lt;p&gt;Field name&lt;/p&gt;
* $operator **string** - &lt;p&gt;List of operators : =, !=, &lt;&gt;, &lt;, &lt;=, &gt;, &gt;=, like, notlike, regexp, notregexp&lt;/p&gt;
* $value **mixed**



### sqlHaving

    \PrestaShopCollection PrestaShopCollectionCore::sqlHaving(string $sql)

Add HAVING restriction on query using real SQL syntax



* Visibility: **public**


#### Arguments
* $sql **string**



### orderBy

    \PrestaShopCollection PrestaShopCollectionCore::orderBy(string $field, string $order)

Add ORDER BY restriction on query



* Visibility: **public**


#### Arguments
* $field **string** - &lt;p&gt;Field name&lt;/p&gt;
* $order **string** - &lt;p&gt;asc|desc&lt;/p&gt;



### sqlOrderBy

    \PrestaShopCollection PrestaShopCollectionCore::sqlOrderBy(string $sql)

Add ORDER BY restriction on query using real SQL syntax



* Visibility: **public**


#### Arguments
* $sql **string**



### groupBy

    \PrestaShopCollection PrestaShopCollectionCore::groupBy(string $field)

Add GROUP BY restriction on query



* Visibility: **public**


#### Arguments
* $field **string** - &lt;p&gt;Field name&lt;/p&gt;



### sqlGroupBy

    \PrestaShopCollection PrestaShopCollectionCore::sqlGroupBy(string $sql)

Add GROUP BY restriction on query using real SQL syntax



* Visibility: **public**


#### Arguments
* $sql **string**



### getAll

    \PrestaShopCollection PrestaShopCollectionCore::getAll(boolean $display_query)

Launch sql query to create collection of objects



* Visibility: **public**


#### Arguments
* $display_query **boolean** - &lt;p&gt;If true, query will be displayed (for debug purpose)&lt;/p&gt;



### getFirst

    \ObjectModel PrestaShopCollectionCore::getFirst()

Retrieve the first result



* Visibility: **public**




### getResults

    array PrestaShopCollectionCore::getResults()

Get results array



* Visibility: **public**




### rewind

    mixed PrestaShopCollectionCore::rewind()

This method is called when a foreach begin



* Visibility: **public**




### current

    \ObjectModel PrestaShopCollectionCore::current()

Get current result



* Visibility: **public**




### valid

    boolean PrestaShopCollectionCore::valid()

Check if there is a current result



* Visibility: **public**




### key

    integer PrestaShopCollectionCore::key()

Get current result index



* Visibility: **public**




### next

    mixed PrestaShopCollectionCore::next()

Go to next result



* Visibility: **public**




### count

    integer PrestaShopCollectionCore::count()

Get total of results



* Visibility: **public**




### offsetExists

    boolean PrestaShopCollectionCore::offsetExists($offset)

Check if a result exist



* Visibility: **public**


#### Arguments
* $offset **mixed**



### offsetGet

    \ObjectModel PrestaShopCollectionCore::offsetGet($offset)

Get a result by offset



* Visibility: **public**


#### Arguments
* $offset **mixed**



### offsetSet

    mixed PrestaShopCollectionCore::offsetSet($offset, $value)

Add an element in the collection



* Visibility: **public**


#### Arguments
* $offset **mixed**
* $value **mixed**



### offsetUnset

    mixed PrestaShopCollectionCore::offsetUnset($offset)

Delete an element from the collection



* Visibility: **public**


#### Arguments
* $offset **mixed**



### getDefinition

    array PrestaShopCollectionCore::getDefinition(string $association)

Get definition of an association



* Visibility: **protected**


#### Arguments
* $association **string**



### parseFields

    string PrestaShopCollectionCore::parseFields(string $str)

Parse all fields with {field} syntax in a string



* Visibility: **protected**


#### Arguments
* $str **string**



### parseField

    string PrestaShopCollectionCore::parseField(string $field)

Replace a field with its SQL version (E.g. manufacturer.name with a2.name)



* Visibility: **protected**


#### Arguments
* $field **string** - &lt;p&gt;Field name&lt;/p&gt;



### formatValue

    mixed PrestaShopCollectionCore::formatValue(mixed $value, string $field)

Format a value with the type of the given field



* Visibility: **protected**


#### Arguments
* $value **mixed**
* $field **string** - &lt;p&gt;Field name&lt;/p&gt;



### getFieldInfo

    array PrestaShopCollectionCore::getFieldInfo(string $field)

Obtain some information on a field (alias, name, type, etc.)



* Visibility: **protected**


#### Arguments
* $field **string** - &lt;p&gt;Field name&lt;/p&gt;



### setPageNumber

    \PrestaShopCollection PrestaShopCollectionCore::setPageNumber(integer $page_number)

Set the page number



* Visibility: **public**


#### Arguments
* $page_number **integer**



### setPageSize

    \PrestaShopCollection PrestaShopCollectionCore::setPageSize(integer $page_size)

Set the nuber of item per page



* Visibility: **public**


#### Arguments
* $page_size **integer**



### generateAlias

    string PrestaShopCollectionCore::generateAlias(string $association)

Generate uniq alias from association name



* Visibility: **protected**


#### Arguments
* $association **string** - &lt;p&gt;Use empty association for alias on current table&lt;/p&gt;


