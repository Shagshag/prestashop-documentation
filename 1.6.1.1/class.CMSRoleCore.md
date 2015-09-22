Class CMSRoleCore
=====================





* Class name: CMSRoleCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/CMSRole.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSRole.php#L28)


Contents
--------


### Properties

* [$definition](#property-$definition)
* [$id_cms](#property-$id_cms)
* [$name](#property-$name)

### Methods

* [getRepositoryClassName](#method-getRepositoryClassName)




Properties
----------


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'cms_role', 'primary' => 'id_cms_role', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 50), 'id_cms' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/CMSRole.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSRole.php#L38).


### <a name="property-$id_cms"></a>$id_cms

```php
public integer $id_cms
```





* Visibility: **public**
* Source: [classes/CMSRole.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSRole.php#L33).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/CMSRole.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSRole.php#L31).


Methods
-------


### <a name="method-getRepositoryClassName"></a>getRepositoryClassName

```php
mixed CMSRoleCore::getRepositoryClassName()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSRole.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMSRole.php#L47)



