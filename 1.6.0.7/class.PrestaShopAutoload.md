Class PrestaShopAutoload
=====================





* Class name: PrestaShopAutoload
* Source: [classes/PrestaShopAutoload.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/PrestaShopAutoload.php#L30)


Contents
--------

### Constants

* [INDEX_FILE](#constant-INDEX_FILE)

### Properties

* [$_include_override_path](#property-$_include_override_path)
* [$class_aliases](#property-$class_aliases)
* [$index](#property-$index)
* [$instance](#property-$instance)
* [$root_dir](#property-$root_dir)

### Methods

* [__construct](#method-__construct)
* [generateIndex](#method-generateIndex)
* [getClassPath](#method-getClassPath)
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



* Source: [classes/PrestaShopAutoload.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/PrestaShopAutoload.php#L35).


Properties
----------


### <a name="property-$_include_override_path"></a>$_include_override_path

```php
public mixed $_include_override_path = true
```





* Visibility: **public**
* Source: [classes/PrestaShopAutoload.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/PrestaShopAutoload.php#L52).


### <a name="property-$class_aliases"></a>$class_aliases

```php
protected mixed $class_aliases = array('Collection' => 'PrestaShopCollection', 'Autoload' => 'PrestaShopAutoload', 'Backup' => 'PrestaShopBackup', 'Logger' => 'PrestaShopLogger')
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/PrestaShopAutoload.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/PrestaShopAutoload.php#L54).


### <a name="property-$index"></a>$index

```php
public array $index = array()
```





* Visibility: **public**
* Source: [classes/PrestaShopAutoload.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/PrestaShopAutoload.php#L50).


### <a name="property-$instance"></a>$instance

```php
protected \Autoload $instance
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/PrestaShopAutoload.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/PrestaShopAutoload.php#L40).


### <a name="property-$root_dir"></a>$root_dir

```php
protected string $root_dir
```





* Visibility: **protected**
* Source: [classes/PrestaShopAutoload.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/PrestaShopAutoload.php#L45).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed PrestaShopAutoload::__construct()
```





* Visibility: **protected**
* Source: [classes/PrestaShopAutoload.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/PrestaShopAutoload.php#L61)




### <a name="method-generateIndex"></a>generateIndex

```php
mixed PrestaShopAutoload::generateIndex()
```

Generate classes index



* Visibility: **public**
* Source: [classes/PrestaShopAutoload.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/PrestaShopAutoload.php#L128)




### <a name="method-getClassPath"></a>getClassPath

```php
mixed PrestaShopAutoload::getClassPath($classname)
```





* Visibility: **public**
* Source: [classes/PrestaShopAutoload.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/PrestaShopAutoload.php#L202)


#### Arguments
* $classname **mixed**



### <a name="method-getClassesFromDir"></a>getClassesFromDir

```php
array PrestaShopAutoload::getClassesFromDir(string $path)
```

Retrieve recursively all classes in a directory and its subdirectories



* Visibility: **protected**
* Source: [classes/PrestaShopAutoload.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/PrestaShopAutoload.php#L167)


#### Arguments
* $path **string** - Relativ path from root to the directory



### <a name="method-getInstance"></a>getInstance

```php
\Autoload PrestaShopAutoload::getInstance()
```

Get instance of autoload (singleton)



* Visibility: **public**
* This method is **static**.
* Source: [classes/PrestaShopAutoload.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/PrestaShopAutoload.php#L76)




### <a name="method-load"></a>load

```php
mixed PrestaShopAutoload::load(string $classname)
```

Retrieve informations about a class in classes index and load it



* Visibility: **public**
* Source: [classes/PrestaShopAutoload.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/PrestaShopAutoload.php#L89)


#### Arguments
* $classname **string**


