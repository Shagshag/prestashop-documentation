Class pagination
=====================

Pagination Class



* Class name: pagination
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 8](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L8)


Contents
--------


### Properties

* [$baseUrl](#property-$baseUrl)
* [$currentPage](#property-$currentPage)
* [$excludedQueryStrings](#property-$excludedQueryStrings)
* [$firstText](#property-$firstText)
* [$friendlyUrl](#property-$friendlyUrl)
* [$groupLimit](#property-$groupLimit)
* [$itemsPerPage](#property-$itemsPerPage)
* [$lastText](#property-$lastText)
* [$limitIndex](#property-$limitIndex)
* [$limits](#property-$limits)
* [$nextText](#property-$nextText)
* [$pageIndex](#property-$pageIndex)
* [$previousText](#property-$previousText)
* [$totalItems](#property-$totalItems)
* [$totalPages](#property-$totalPages)
* [$url](#property-$url)

### Methods

* [__appendQueryString](#method-__appendQueryString)
* [__getBaseUrl](#method-__getBaseUrl)
* [__resetCurrentPage](#method-__resetCurrentPage)
* [__setBaseUrl](#method-__setBaseUrl)
* [getExcludedQueryString](#method-getExcludedQueryString)
* [getFirstItem](#method-getFirstItem)
* [getFirstUrl](#method-getFirstUrl)
* [getGroupLimit](#method-getGroupLimit)
* [getGroupUrls](#method-getGroupUrls)
* [getLastItem](#method-getLastItem)
* [getLastUrl](#method-getLastUrl)
* [getLimit](#method-getLimit)
* [getNextUrl](#method-getNextUrl)
* [getPageIndex](#method-getPageIndex)
* [getPageOffset](#method-getPageOffset)
* [getPaginationHTML](#method-getPaginationHTML)
* [getPreviousUrl](#method-getPreviousUrl)
* [getTotal](#method-getTotal)
* [getTotalPages](#method-getTotalPages)
* [getUrl](#method-getUrl)
* [pagination](#method-pagination)
* [setExcludedQueryString](#method-setExcludedQueryString)
* [setFirstText](#method-setFirstText)
* [setGroupLimit](#method-setGroupLimit)
* [setLastText](#method-setLastText)
* [setLimit](#method-setLimit)
* [setNextText](#method-setNextText)
* [setPageIndex](#method-setPageIndex)
* [setPreviousText](#method-setPreviousText)
* [setTotal](#method-setTotal)
* [setUrl](#method-setUrl)




Properties
----------


### <a name="property-$baseUrl"></a>$baseUrl

```php
public mixed $baseUrl = ""
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 14](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L14).


### <a name="property-$currentPage"></a>$currentPage

```php
public mixed $currentPage = 1
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 12](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L12).


### <a name="property-$excludedQueryStrings"></a>$excludedQueryStrings

```php
public mixed $excludedQueryStrings = array()
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 17](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L17).


### <a name="property-$firstText"></a>$firstText

```php
public mixed $firstText = "First"
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 23](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L23).


### <a name="property-$friendlyUrl"></a>$friendlyUrl

```php
public mixed $friendlyUrl = false
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 13](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L13).


### <a name="property-$groupLimit"></a>$groupLimit

```php
public mixed $groupLimit = 5
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 16](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L16).


### <a name="property-$itemsPerPage"></a>$itemsPerPage

```php
public mixed $itemsPerPage = 30
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 11](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L11).


### <a name="property-$lastText"></a>$lastText

```php
public mixed $lastText = "Last"
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 22](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L22).


### <a name="property-$limitIndex"></a>$limitIndex

```php
public mixed $limitIndex = 'limit'
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 24](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L24).


### <a name="property-$limits"></a>$limits

```php
public mixed $limits = array(5, 10, 20, 30, 50, 80, 150, 999)
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 25](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L25).


### <a name="property-$nextText"></a>$nextText

```php
public mixed $nextText = "Next"
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 21](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L21).


### <a name="property-$pageIndex"></a>$pageIndex

```php
public mixed $pageIndex = "page"
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 15](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L15).


### <a name="property-$previousText"></a>$previousText

```php
public mixed $previousText = "Previous"
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 20](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L20).


### <a name="property-$totalItems"></a>$totalItems

```php
public mixed $totalItems
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 10](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L10).


### <a name="property-$totalPages"></a>$totalPages

```php
public mixed $totalPages
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 18](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L18).


### <a name="property-$url"></a>$url

```php
public mixed $url = ""
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 19](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L19).


Methods
-------


### <a name="method-__appendQueryString"></a>__appendQueryString

```php
mixed pagination::__appendQueryString(string $baseUrl, string $extra)
```

add extra query stiring to a url



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 506](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L506)


#### Arguments
* $baseUrl **string**
* $extra **string** - the query string added to the base url



### <a name="method-__getBaseUrl"></a>__getBaseUrl

```php
mixed pagination::__getBaseUrl()
```

get base url for pagination links aftr excluded those key
identified on excluded query strings



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L200)




### <a name="method-__resetCurrentPage"></a>__resetCurrentPage

```php
mixed pagination::__resetCurrentPage()
```

initiate or reset the current page number



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L112)




### <a name="method-__setBaseUrl"></a>__setBaseUrl

```php
mixed pagination::__setBaseUrl()
```

set base url for pagination links after exculed those keys
identified on excluded query strings



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L160)




### <a name="method-getExcludedQueryString"></a>getExcludedQueryString

```php
mixed pagination::getExcludedQueryString()
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 495](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L495)




### <a name="method-getFirstItem"></a>getFirstItem

```php
\interger pagination::getFirstItem()
```

get the first item number



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L217)




### <a name="method-getFirstUrl"></a>getFirstUrl

```php
string pagination::getFirstUrl()
```

get the first url if any



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 315](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L315)




### <a name="method-getGroupLimit"></a>getGroupLimit

```php
integer pagination::getGroupLimit()
```

get page grouping limit



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 265](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L265)




### <a name="method-getGroupUrls"></a>getGroupUrls

```php
mixed pagination::getGroupUrls()
```

get the group page links  e.g. 1,2,3,4,5
return format
<a class="pagination_group" href='yoururl'>1</a>
<a class="pagination_group active" href='#'>2</a>
<a class="pagination_group" href='yoururl'>3</a>



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 397](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L397)




### <a name="method-getLastItem"></a>getLastItem

```php
\interger pagination::getLastItem()
```

get the last item number displayed within current page



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 233](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L233)




### <a name="method-getLastUrl"></a>getLastUrl

```php
string pagination::getLastUrl()
```

get the last url if any



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 284](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L284)




### <a name="method-getLimit"></a>getLimit

```php
integer pagination::getLimit()
```

get maximum number of items per page



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L54)




### <a name="method-getNextUrl"></a>getNextUrl

```php
string pagination::getNextUrl()
```

get the next page url if anywhere



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 369](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L369)




### <a name="method-getPageIndex"></a>getPageIndex

```php
mixed pagination::getPageIndex()
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L104)




### <a name="method-getPageOffset"></a>getPageOffset

```php
\iner pagination::getPageOffset()
```

get the page offset number
used for Query . e.g SELECT SQL_CALC_FOUND_ROWS *
						FROM mytable LIMIT getPageOffset(), getItemsPerPage()



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 276](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L276)




### <a name="method-getPaginationHTML"></a>getPaginationHTML

```php
mixed pagination::getPaginationHTML(integer $type, $cssClass)
```

return the html



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 523](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L523)


#### Arguments
* $type **integer**
* $cssClass **mixed**



### <a name="method-getPreviousUrl"></a>getPreviousUrl

```php
string pagination::getPreviousUrl()
```

get the previous page url if anywhere



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 342](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L342)




### <a name="method-getTotal"></a>getTotal

```php
integer pagination::getTotal()
```

get the total number of items



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L73)




### <a name="method-getTotalPages"></a>getTotalPages

```php
mixed pagination::getTotalPages()
```

get total pages will be used to display all records



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L81)




### <a name="method-getUrl"></a>getUrl

```php
string pagination::getUrl()
```

get the base url variable



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L145)




### <a name="method-pagination"></a>pagination

```php
mixed pagination::pagination(boolean $friendlyUrl)
```

Contructor



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L34)


#### Arguments
* $friendlyUrl **boolean** - set the returned url
as search engine friendly or Normal Url



### <a name="method-setExcludedQueryString"></a>setExcludedQueryString

```php
mixed pagination::setExcludedQueryString($values)
```

set the excluded query string from $_GET;



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 490](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L490)


#### Arguments
* $values **mixed**



### <a name="method-setFirstText"></a>setFirstText

```php
mixed pagination::setFirstText(string $value)
```

set the text of first page link



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 460](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L460)


#### Arguments
* $value **string**



### <a name="method-setGroupLimit"></a>setGroupLimit

```php
mixed pagination::setGroupLimit(\unknown_type $value)
```

set  page groupings limit
used for previous 1 2 3 4 5 next



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 256](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L256)


#### Arguments
* $value **unknown_type**



### <a name="method-setLastText"></a>setLastText

```php
mixed pagination::setLastText(string $value)
```

set the text of last page link



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 479](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L479)


#### Arguments
* $value **string**



### <a name="method-setLimit"></a>setLimit

```php
mixed pagination::setLimit(integer $value)
```

set maximum number of items per page



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L45)


#### Arguments
* $value **integer** - maximum number of items per page



### <a name="method-setNextText"></a>setNextText

```php
mixed pagination::setNextText(string $value)
```

set the text of next page link



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 470](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L470)


#### Arguments
* $value **string**



### <a name="method-setPageIndex"></a>setPageIndex

```php
mixed pagination::setPageIndex(string $value)
```

Set the index of URL Query String



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L97)


#### Arguments
* $value **string** - e.g. page



### <a name="method-setPreviousText"></a>setPreviousText

```php
mixed pagination::setPreviousText(string $value)
```

set the text of previous page link



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 451](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L451)


#### Arguments
* $value **string**



### <a name="method-setTotal"></a>setTotal

```php
mixed pagination::setTotal(integer $value)
```

set the total number of items



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L64)


#### Arguments
* $value **integer** - the total number of items



### <a name="method-setUrl"></a>setUrl

```php
mixed pagination::setUrl(string $value)
```

set the base url used in the links, default is $PHP_SELF



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.pagination.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/admin-dev/ajaxfilemanager/inc/class.pagination.php#L122)


#### Arguments
* $value **string** - the base url


