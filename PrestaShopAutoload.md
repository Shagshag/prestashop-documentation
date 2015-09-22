PrestaShopAutoload
===============






* Class name: PrestaShopAutoload
* This class is defined in [classes/PrestaShopAutoload.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopAutoload.php#L30)



Constants
----------


### INDEX_FILE

    const INDEX_FILE = 'cache/class_index.php'



* This constant is defined in [classes/PrestaShopAutoload.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopAutoload.php#35)


Properties
----------


### $instance

    protected \PrestaShopAutoload $instance





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/PrestaShopAutoload.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopAutoload.php#40)


### $root_dir

    protected string $root_dir





* Visibility: **protected**
* This property is defined in [classes/PrestaShopAutoload.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopAutoload.php#45)


### $index

    public array $index = array()





* Visibility: **public**
* This property is defined in [classes/PrestaShopAutoload.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopAutoload.php#50)


### $_include_override_path

    public mixed $_include_override_path = true





* Visibility: **public**
* This property is defined in [classes/PrestaShopAutoload.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopAutoload.php#52)


### $class_aliases

    protected mixed $class_aliases = array('Collection' => 'PrestaShopCollection', 'Autoload' => 'PrestaShopAutoload', 'Backup' => 'PrestaShopBackup', 'Logger' => 'PrestaShopLogger')





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/PrestaShopAutoload.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopAutoload.php#54)


Methods
-------


### __construct

    mixed PrestaShopAutoload::__construct()





* Visibility: **protected**
* This method is defined in [classes/PrestaShopAutoload.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopAutoload.php#61)




### getInstance

    \PrestaShopAutoload PrestaShopAutoload::getInstance()

Get instance of autoload (singleton)



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/PrestaShopAutoload.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopAutoload.php#77)




### load

    mixed PrestaShopAutoload::load(string $classname)

Retrieve informations about a class in classes index and load it



* Visibility: **public**
* This method is defined in [classes/PrestaShopAutoload.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopAutoload.php#91)


#### Arguments
* $classname **string**



### generateIndex

    mixed PrestaShopAutoload::generateIndex()

Generate classes index



* Visibility: **public**
* This method is defined in [classes/PrestaShopAutoload.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopAutoload.php#136)




### getClassesFromDir

    array PrestaShopAutoload::getClassesFromDir(string $path, $host_mode)

Retrieve recursively all classes in a directory and its subdirectories



* Visibility: **protected**
* This method is defined in [classes/PrestaShopAutoload.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopAutoload.php#179)


#### Arguments
* $path **string** - &lt;p&gt;Relativ path from root to the directory&lt;/p&gt;
* $host_mode **mixed**



### getClassPath

    mixed PrestaShopAutoload::getClassPath($classname)





* Visibility: **public**
* This method is defined in [classes/PrestaShopAutoload.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopAutoload.php#217)


#### Arguments
* $classname **mixed**



### normalizeDirectory

    mixed PrestaShopAutoload::normalizeDirectory($directory)





* Visibility: **private**
* This method is defined in [classes/PrestaShopAutoload.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopAutoload.php#222)


#### Arguments
* $directory **mixed**


