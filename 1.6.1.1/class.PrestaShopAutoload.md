Class PrestaShopAutoload
=====================





* Class name: PrestaShopAutoload
* Source: [classes/PrestaShopAutoload.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopAutoload.php#L30)

Constants
----------

* [INDEX_FILE](#constant-INDEX_FILE)

Properties
----------

* [$_include_override_path](#property-$_include_override_path)
* [$class_aliases](#property-$class_aliases)
* [$index](#property-$index)
* [$instance](#property-$instance)
* [$root_dir](#property-$root_dir)

Methods
-------
* [__construct](#method-__construct)
* [generateIndex](#method-generateIndex)
* [getClassPath](#method-getClassPath)
* [getClassesFromDir](#method-getClassesFromDir)
* [getInstance](#method-getInstance)
* [load](#method-load)
* [normalizeDirectory](#method-normalizeDirectory)


Constants
----------


### <a name="constant-INDEX_FILE"></a>INDEX_FILE

    const INDEX_FILE = 'cache/class_index.php'

File where classes index is stored



* Source: [classes/PrestaShopAutoload.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopAutoload.php#L35).


Properties
----------


### <a name="property-$_include_override_path"></a>$_include_override_path

    public mixed $_include_override_path = true





* Visibility: **public**
* Source: [classes/PrestaShopAutoload.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopAutoload.php#L52).


### <a name="property-$class_aliases"></a>$class_aliases

    protected mixed $class_aliases = array('Collection' => 'PrestaShopCollection', 'Autoload' => 'PrestaShopAutoload', 'Backup' => 'PrestaShopBackup', 'Logger' => 'PrestaShopLogger')





* Visibility: **protected**
* This property is **static**.
* Source: [classes/PrestaShopAutoload.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopAutoload.php#L54).


### <a name="property-$index"></a>$index

    public array $index = array()





* Visibility: **public**
* Source: [classes/PrestaShopAutoload.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopAutoload.php#L50).


### <a name="property-$instance"></a>$instance

    protected \PrestaShopAutoload $instance





* Visibility: **protected**
* This property is **static**.
* Source: [classes/PrestaShopAutoload.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopAutoload.php#L40).


### <a name="property-$root_dir"></a>$root_dir

    protected string $root_dir





* Visibility: **protected**
* Source: [classes/PrestaShopAutoload.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopAutoload.php#L45).


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed PrestaShopAutoload::__construct()





* Visibility: **protected**
* Source: [classes/PrestaShopAutoload.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopAutoload.php#L61)




### <a name="method-generateIndex"></a>generateIndex

    mixed PrestaShopAutoload::generateIndex()

Generate classes index



* Visibility: **public**
* Source: [classes/PrestaShopAutoload.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopAutoload.php#L136)




### <a name="method-getClassPath"></a>getClassPath

    mixed PrestaShopAutoload::getClassPath($classname)





* Visibility: **public**
* Source: [classes/PrestaShopAutoload.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopAutoload.php#L217)


#### Arguments
* $classname **mixed**



### <a name="method-getClassesFromDir"></a>getClassesFromDir

    array PrestaShopAutoload::getClassesFromDir(string $path, $host_mode)

Retrieve recursively all classes in a directory and its subdirectories



* Visibility: **protected**
* Source: [classes/PrestaShopAutoload.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopAutoload.php#L179)


#### Arguments
* $path **string** - Relativ path from root to the directory
* $host_mode **mixed**



### <a name="method-getInstance"></a>getInstance

    \PrestaShopAutoload PrestaShopAutoload::getInstance()

Get instance of autoload (singleton)



* Visibility: **public**
* This method is **static**.
* Source: [classes/PrestaShopAutoload.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopAutoload.php#L77)




### <a name="method-load"></a>load

    mixed PrestaShopAutoload::load(string $classname)

Retrieve informations about a class in classes index and load it



* Visibility: **public**
* Source: [classes/PrestaShopAutoload.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopAutoload.php#L91)


#### Arguments
* $classname **string**



### <a name="method-normalizeDirectory"></a>normalizeDirectory

    mixed PrestaShopAutoload::normalizeDirectory($directory)





* Visibility: **private**
* Source: [classes/PrestaShopAutoload.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopAutoload.php#L222)


#### Arguments
* $directory **mixed**


