Class Autoload
=====================





* Class name: Autoload
* Source: [classes/Autoload.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Autoload.php#L30)


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



* Source: [classes/Autoload.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Autoload.php#L35).


Properties
----------


### <a name="property-$index"></a>$index

```php
public array $index = array()
```





* Visibility: **public**
* Source: [classes/Autoload.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Autoload.php#L50).


### <a name="property-$instance"></a>$instance

```php
protected \Autoload $instance
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Autoload.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Autoload.php#L40).


### <a name="property-$root_dir"></a>$root_dir

```php
protected string $root_dir
```





* Visibility: **protected**
* Source: [classes/Autoload.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Autoload.php#L45).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed Autoload::__construct()
```





* Visibility: **protected**
* Source: [classes/Autoload.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Autoload.php#L52)




### <a name="method-generateIndex"></a>generateIndex

```php
mixed Autoload::generateIndex()
```

Generate classes index



* Visibility: **public**
* Source: [classes/Autoload.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Autoload.php#L118)




### <a name="method-getClassPath"></a>getClassPath

```php
mixed Autoload::getClassPath($classname)
```





* Visibility: **public**
* Source: [classes/Autoload.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Autoload.php#L195)


#### Arguments
* $classname **mixed**



### <a name="method-getClassesFromDir"></a>getClassesFromDir

```php
array Autoload::getClassesFromDir(string $path)
```

Retrieve recursively all classes in a directory and its subdirectories



* Visibility: **protected**
* Source: [classes/Autoload.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Autoload.php#L167)


#### Arguments
* $path **string** - Relativ path from root to the directory



### <a name="method-getInstance"></a>getInstance

```php
\Autoload Autoload::getInstance()
```

Get instance of autoload (singleton)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Autoload.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Autoload.php#L64)




### <a name="method-load"></a>load

```php
mixed Autoload::load(string $classname)
```

Retrieve informations about a class in classes index and load it



* Visibility: **public**
* Source: [classes/Autoload.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/Autoload.php#L77)


#### Arguments
* $classname **string**


