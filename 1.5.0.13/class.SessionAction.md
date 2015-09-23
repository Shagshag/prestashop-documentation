Class SessionAction
=====================

Session Action Class



* Class name: SessionAction
* Source: [admin-dev/ajaxfilemanager/inc/class.sessionaction.php line 9](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/admin-dev/ajaxfilemanager/inc/class.sessionaction.php#L9)


Contents
--------


### Properties

* [$actionIndex](#property-$actionIndex)
* [$fromFolderIndex](#property-$fromFolderIndex)
* [$selectedDocIndex](#property-$selectedDocIndex)

### Methods

* [SessionAction](#method-SessionAction)
* [__construct](#method-__construct)
* [count](#method-count)
* [get](#method-get)
* [getAction](#method-getAction)
* [getFolder](#method-getFolder)
* [set](#method-set)
* [setAction](#method-setAction)
* [setFolder](#method-setFolder)




Properties
----------


### <a name="property-$actionIndex"></a>$actionIndex

```php
public mixed $actionIndex = 'ajax_file_action'
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.sessionaction.php line 11](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/admin-dev/ajaxfilemanager/inc/class.sessionaction.php#L11).


### <a name="property-$fromFolderIndex"></a>$fromFolderIndex

```php
public mixed $fromFolderIndex = 'ajax_from_folder'
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.sessionaction.php line 13](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/admin-dev/ajaxfilemanager/inc/class.sessionaction.php#L13).


### <a name="property-$selectedDocIndex"></a>$selectedDocIndex

```php
public mixed $selectedDocIndex = 'ajax_selected_doc'
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.sessionaction.php line 12](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/admin-dev/ajaxfilemanager/inc/class.sessionaction.php#L12).


Methods
-------


### <a name="method-SessionAction"></a>SessionAction

```php
mixed SessionAction::SessionAction()
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.sessionaction.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/admin-dev/ajaxfilemanager/inc/class.sessionaction.php#L30)




### <a name="method-__construct"></a>__construct

```php
mixed SessionAction::__construct()
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.sessionaction.php line 14](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/admin-dev/ajaxfilemanager/inc/class.sessionaction.php#L14)




### <a name="method-count"></a>count

```php
mixed SessionAction::count()
```

count the  number of selected documents



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.sessionaction.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/admin-dev/ajaxfilemanager/inc/class.sessionaction.php#L38)




### <a name="method-get"></a>get

```php
array SessionAction::get()
```

get the selected documents



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.sessionaction.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/admin-dev/ajaxfilemanager/inc/class.sessionaction.php#L56)




### <a name="method-getAction"></a>getAction

```php
\unknown SessionAction::getAction()
```

get the action



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.sessionaction.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/admin-dev/ajaxfilemanager/inc/class.sessionaction.php#L70)




### <a name="method-getFolder"></a>getFolder

```php
string SessionAction::getFolder()
```

get the folder



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.sessionaction.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/admin-dev/ajaxfilemanager/inc/class.sessionaction.php#L88)




### <a name="method-set"></a>set

```php
mixed SessionAction::set(array $selectedDocuments)
```

assign the selected documents



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.sessionaction.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/admin-dev/ajaxfilemanager/inc/class.sessionaction.php#L47)


#### Arguments
* $selectedDocuments **array**



### <a name="method-setAction"></a>setAction

```php
mixed SessionAction::setAction($action)
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.sessionaction.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/admin-dev/ajaxfilemanager/inc/class.sessionaction.php#L61)


#### Arguments
* $action **mixed**



### <a name="method-setFolder"></a>setFolder

```php
mixed SessionAction::setFolder(string $folder)
```

set the folder



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.sessionaction.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/admin-dev/ajaxfilemanager/inc/class.sessionaction.php#L79)


#### Arguments
* $folder **string**


