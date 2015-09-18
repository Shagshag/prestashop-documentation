PrestaShopAutoload
===============






* Class name: PrestaShopAutoload
* Namespace: 



Constants
----------


### INDEX_FILE

    const INDEX_FILE = 'cache/class_index.php'





Properties
----------


### $instance

    protected \PrestaShopAutoload $instance





* Visibility: **protected**
* This property is **static**.


### $root_dir

    protected string $root_dir





* Visibility: **protected**


### $index

    public array $index = array()





* Visibility: **public**


### $_include_override_path

    public mixed $_include_override_path = true





* Visibility: **public**


### $class_aliases

    protected mixed $class_aliases = array('Collection' => 'PrestaShopCollection', 'Autoload' => 'PrestaShopAutoload', 'Backup' => 'PrestaShopBackup', 'Logger' => 'PrestaShopLogger')





* Visibility: **protected**
* This property is **static**.


Methods
-------


### __construct

    mixed PrestaShopAutoload::__construct()





* Visibility: **protected**




### getInstance

    \PrestaShopAutoload PrestaShopAutoload::getInstance()

Get instance of autoload (singleton)



* Visibility: **public**
* This method is **static**.




### load

    mixed PrestaShopAutoload::load(string $classname)

Retrieve informations about a class in classes index and load it



* Visibility: **public**


#### Arguments
* $classname **string**



### generateIndex

    mixed PrestaShopAutoload::generateIndex()

Generate classes index



* Visibility: **public**




### getClassesFromDir

    array PrestaShopAutoload::getClassesFromDir(string $path, $host_mode)

Retrieve recursively all classes in a directory and its subdirectories



* Visibility: **protected**


#### Arguments
* $path **string** - &lt;p&gt;Relativ path from root to the directory&lt;/p&gt;
* $host_mode **mixed**



### getClassPath

    mixed PrestaShopAutoload::getClassPath($classname)





* Visibility: **public**


#### Arguments
* $classname **mixed**



### normalizeDirectory

    mixed PrestaShopAutoload::normalizeDirectory($directory)





* Visibility: **private**


#### Arguments
* $directory **mixed**


