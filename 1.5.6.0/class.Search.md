Class Search
=====================





* Class name: Search
* Source: [admin-dev/ajaxfilemanager/inc/class.search.php line 5](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/admin-dev/ajaxfilemanager/inc/class.search.php#L5)


Contents
--------


### Properties

* [$files](#property-$files)
* [$rootFolder](#property-$rootFolder)
* [$rootFolderInfo](#property-$rootFolderInfo)
* [$searchkeywords](#property-$searchkeywords)
* [$sessionAction](#property-$sessionAction)

### Methods

* [Search](#method-Search)
* [__construct](#method-__construct)
* [addSearchKeyword](#method-addSearchKeyword)
* [addSearchKeywords](#method-addSearchKeywords)
* [doSearch](#method-doSearch)
* [getFoundFiles](#method-getFoundFiles)
* [getRootFolderInfo](#method-getRootFolderInfo)




Properties
----------


### <a name="property-$files"></a>$files

```php
public mixed $files = array()
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.search.php line 8](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/admin-dev/ajaxfilemanager/inc/class.search.php#L8).


### <a name="property-$rootFolder"></a>$rootFolder

```php
public mixed $rootFolder = ''
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.search.php line 7](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/admin-dev/ajaxfilemanager/inc/class.search.php#L7).


### <a name="property-$rootFolderInfo"></a>$rootFolderInfo

```php
public mixed $rootFolderInfo = array()
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.search.php line 9](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/admin-dev/ajaxfilemanager/inc/class.search.php#L9).


### <a name="property-$searchkeywords"></a>$searchkeywords

```php
public mixed $searchkeywords = array('mtime_from' => '', 'mtime_to' => '', 'name' => '', 'size_from' => '', 'size_to' => '', 'recursive' => '0')
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.search.php line 10](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/admin-dev/ajaxfilemanager/inc/class.search.php#L10).


### <a name="property-$sessionAction"></a>$sessionAction

```php
public mixed $sessionAction = null
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.search.php line 19](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/admin-dev/ajaxfilemanager/inc/class.search.php#L19).


Methods
-------


### <a name="method-Search"></a>Search

```php
mixed Search::Search(string $rootFolder)
```

constructor



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.search.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/admin-dev/ajaxfilemanager/inc/class.search.php#L63)


#### Arguments
* $rootFolder **string**



### <a name="method-__construct"></a>__construct

```php
mixed Search::__construct(string $rootFolder)
```

constructor



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.search.php line 25](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/admin-dev/ajaxfilemanager/inc/class.search.php#L25)


#### Arguments
* $rootFolder **string**



### <a name="method-addSearchKeyword"></a>addSearchKeyword

```php
mixed Search::addSearchKeyword(string $key, string $value)
```

change the search keyword individually



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.search.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/admin-dev/ajaxfilemanager/inc/class.search.php#L74)


#### Arguments
* $key **string**
* $value **string**



### <a name="method-addSearchKeywords"></a>addSearchKeywords

```php
mixed Search::addSearchKeywords(array $keywords)
```

change the search keywords



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.search.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/admin-dev/ajaxfilemanager/inc/class.search.php#L83)


#### Arguments
* $keywords **array**



### <a name="method-doSearch"></a>doSearch

```php
mixed Search::doSearch($baseFolderPath)
```

get the file according to the search keywords



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.search.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/admin-dev/ajaxfilemanager/inc/class.search.php#L97)


#### Arguments
* $baseFolderPath **mixed**



### <a name="method-getFoundFiles"></a>getFoundFiles

```php
mixed Search::getFoundFiles()
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.search.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/admin-dev/ajaxfilemanager/inc/class.search.php#L173)




### <a name="method-getRootFolderInfo"></a>getRootFolderInfo

```php
mixed Search::getRootFolderInfo()
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.search.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.0/admin-dev/ajaxfilemanager/inc/class.search.php#L178)



