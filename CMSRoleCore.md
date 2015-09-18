CMSRoleCore
===============






* Class name: CMSRoleCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $name

    public string $name





* Visibility: **public**


### $id_cms

    public integer $id_cms





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'cms_role', 'primary' => 'id_cms_role', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 50), 'id_cms' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt')))





* Visibility: **public**
* This property is **static**.


Methods
-------


### getRepositoryClassName

    mixed CMSRoleCore::getRepositoryClassName()





* Visibility: **public**
* This method is **static**.



