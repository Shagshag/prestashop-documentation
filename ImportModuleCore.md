ImportModuleCore
===============

ImportModule class, ImportModule.php
Import module management




* Class name: ImportModuleCore
* This is an **abstract** class
* Parent class: [Module](ModuleCore)
* This class is defined in [classes/module/ImportModule.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ImportModule.php#L34)





Properties
----------

* [$_link](#property-$_link)
* [$server](#property-$server)
* [$user](#property-$user)
* [$passwd](#property-$passwd)
* [$database](#property-$database)
* [$prefix](#property-$prefix)

Methods
-------
* [__destruct](#method-__destruct)
* [initDatabaseConnection](#method-initDatabaseConnection)
* [ExecuteS](#method-ExecuteS)
* [Execute](#method-Execute)
* [getValue](#method-getValue)
* [getImportModulesOnDisk](#method-getImportModulesOnDisk)
* [getDefaultIdLang](#method-getDefaultIdLang)




Properties
----------


### <a name="property-$_link"></a>$_link

    protected mixed $_link = null





* Visibility: **protected**
* This property is defined in [classes/module/ImportModule.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ImportModule.php#L36)


### <a name="property-$server"></a>$server

    public mixed $server





* Visibility: **public**
* This property is defined in [classes/module/ImportModule.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ImportModule.php#L38)


### <a name="property-$user"></a>$user

    public mixed $user





* Visibility: **public**
* This property is defined in [classes/module/ImportModule.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ImportModule.php#L40)


### <a name="property-$passwd"></a>$passwd

    public mixed $passwd





* Visibility: **public**
* This property is defined in [classes/module/ImportModule.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ImportModule.php#L42)


### <a name="property-$database"></a>$database

    public mixed $database





* Visibility: **public**
* This property is defined in [classes/module/ImportModule.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ImportModule.php#L44)


### <a name="property-$prefix"></a>$prefix

    public string $prefix





* Visibility: **public**
* This property is defined in [classes/module/ImportModule.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ImportModule.php#L47)


Methods
-------


### <a name="method-__destruct"></a>__destruct

    mixed ImportModuleCore::__destruct()





* Visibility: **public**
* This method is defined in [classes/module/ImportModule.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ImportModule.php#L50)




### <a name="method-initDatabaseConnection"></a>initDatabaseConnection

    mixed ImportModuleCore::initDatabaseConnection()





* Visibility: **protected**
* This method is defined in [classes/module/ImportModule.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ImportModule.php#L57)




### <a name="method-ExecuteS"></a>ExecuteS

    mixed ImportModuleCore::ExecuteS($query)





* Visibility: **public**
* This method is defined in [classes/module/ImportModule.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ImportModule.php#L75)


#### Arguments
* $query **mixed**



### <a name="method-Execute"></a>Execute

    mixed ImportModuleCore::Execute($query)





* Visibility: **public**
* This method is defined in [classes/module/ImportModule.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ImportModule.php#L88)


#### Arguments
* $query **mixed**



### <a name="method-getValue"></a>getValue

    mixed ImportModuleCore::getValue($query)





* Visibility: **public**
* This method is defined in [classes/module/ImportModule.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ImportModule.php#L94)


#### Arguments
* $query **mixed**



### <a name="method-getImportModulesOnDisk"></a>getImportModulesOnDisk

    mixed ImportModuleCore::getImportModulesOnDisk()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/module/ImportModule.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ImportModule.php#L105)




### <a name="method-getDefaultIdLang"></a>getDefaultIdLang

    mixed ImportModuleCore::getDefaultIdLang()





* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/module/ImportModule.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ImportModule.php#L116)



