Class Autoload
=====================





* Class name: Autoload
* Source: [classes/Autoload.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Autoload.php#L31)


Contents
--------

### Constants

* [INDEX_FILE](#constant-INDEX_FILE)

### Properties

* [$index](#property-$index)
* [$instance](#property-$instance)
* [$root_dir](#property-$root_dir)

### Methods

* [__construct](#method-__construct)
* [generateIndex](#method-generateIndex)
* [getClassesFromDir](#method-getClassesFromDir)
* [getInstance](#method-getInstance)
* [load](#method-load)


Constants
----------


### <a name="constant-INDEX_FILE"></a>INDEX_FILE

```php
const INDEX_FILE = 'cache/class_index.php'
```

File where classes index is stored



* Source: [classes/Autoload.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Autoload.php#L36).


Properties
----------


### <a name="property-$index"></a>$index

```php
public array $index = array()
```





* Visibility: **public**
* Source: [classes/Autoload.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Autoload.php#L51).


### <a name="property-$instance"></a>$instance

```php
protected \Autoload $instance
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Autoload.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Autoload.php#L41).


### <a name="property-$root_dir"></a>$root_dir

```php
protected string $root_dir
```





* Visibility: **protected**
* Source: [classes/Autoload.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Autoload.php#L46).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed Autoload::__construct()
```





* Visibility: **protected**
* Source: [classes/Autoload.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Autoload.php#L53)




### <a name="method-generateIndex"></a>generateIndex

```php
mixed Autoload::generateIndex()
```

Generate classes index



* Visibility: **public**
* Source: [classes/Autoload.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Autoload.php#L124)




### <a name="method-getClassesFromDir"></a>getClassesFromDir

```php
array Autoload::getClassesFromDir(string $path)
```

Retrieve recursively all classes in a directory and its subdirectories



* Visibility: **protected**
* Source: [classes/Autoload.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Autoload.php#L150)


#### Arguments
* $path **string** - Relativ path from root to the directory



### <a name="method-getInstance"></a>getInstance

```php
\Autoload Autoload::getInstance()
```

Get instance of autoload (singleton)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Autoload.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Autoload.php#L65)




### <a name="method-load"></a>load

```php
mixed Autoload::load(string $classname)
```

Retrieve informations about a class in classes index and load it



* Visibility: **public**
* Source: [classes/Autoload.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Autoload.php#L78)


#### Arguments
* $classname **string**


