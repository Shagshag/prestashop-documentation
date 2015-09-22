CMSRoleCore
===============






* Class name: CMSRoleCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/CMSRole.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSRole.php#L28)





Properties
----------

* [$name](#property-$name)
* [$id_cms](#property-$id_cms)
* [$definition](#property-$definition)

Methods
-------
* [getRepositoryClassName](#method-getRepositoryClassName)




Properties
----------


### <a name="property-$name"></a>$name

    public string $name





* Visibility: **public**
* This property is defined in [classes/CMSRole.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSRole.php#L31)


### <a name="property-$id_cms"></a>$id_cms

    public integer $id_cms





* Visibility: **public**
* This property is defined in [classes/CMSRole.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSRole.php#L33)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'cms_role', 'primary' => 'id_cms_role', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 50), 'id_cms' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/CMSRole.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSRole.php#L38)


Methods
-------


### <a name="method-getRepositoryClassName"></a>getRepositoryClassName

    mixed CMSRoleCore::getRepositoryClassName()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CMSRole.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSRole.php#L47)



