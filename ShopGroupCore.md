ShopGroupCore
===============






* Class name: ShopGroupCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $name

    public mixed $name





* Visibility: **public**


### $active

    public mixed $active = true





* Visibility: **public**


### $share_customer

    public mixed $share_customer





* Visibility: **public**


### $share_stock

    public mixed $share_stock





* Visibility: **public**


### $share_order

    public mixed $share_order





* Visibility: **public**


### $deleted

    public mixed $deleted





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'shop_group', 'primary' => 'id_shop_group', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 64), 'share_customer' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'share_order' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'share_stock' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))





* Visibility: **public**
* This property is **static**.


Methods
-------


### getFields

    array ShopGroupCore::getFields()





* Visibility: **public**




### getShopGroups

    mixed ShopGroupCore::getShopGroups($active)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $active **mixed**



### getTotalShopGroup

    integer ShopGroupCore::getTotalShopGroup($active)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $active **mixed**



### haveShops

    mixed ShopGroupCore::haveShops()





* Visibility: **public**




### getTotalShops

    mixed ShopGroupCore::getTotalShops()





* Visibility: **public**




### getShopsFromGroup

    mixed ShopGroupCore::getShopsFromGroup($id_group)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_group **mixed**



### getIdByName

    integer ShopGroupCore::getIdByName(string $name)

Return a group shop ID from group shop name



* Visibility: **public**
* This method is **static**.


#### Arguments
* $name **string**



### hasDependency

    boolean ShopGroupCore::hasDependency(integer $id_shop_group, string $check)

Detect dependency with customer or orders



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_shop_group **integer**
* $check **string** - &lt;p&gt;all|customer|order&lt;/p&gt;



### shopNameExists

    mixed ShopGroupCore::shopNameExists($name, $id_shop)





* Visibility: **public**


#### Arguments
* $name **mixed**
* $id_shop **mixed**


