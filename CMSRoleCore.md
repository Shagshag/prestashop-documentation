CMSRoleCore
===============






* Class name: CMSRoleCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in classes\CMSRole.php line 28





Properties
----------


### $name

    public string $name





* Visibility: **public**
* This property is defined in classes\CMSRole.php line 31


### $id_cms

    public integer $id_cms





* Visibility: **public**
* This property is defined in classes\CMSRole.php line 33


### $definition

    public mixed $definition = array('table' => 'cms_role', 'primary' => 'id_cms_role', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 50), 'id_cms' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt')))





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\CMSRole.php line 38


Methods
-------


### getRepositoryClassName

    mixed CMSRoleCore::getRepositoryClassName()





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\CMSRole.php line 47



