ShopGroupCore
===============






* Class name: ShopGroupCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)

* This class is defined in [classes/shop/ShopGroup.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#30)





Properties
----------


### $name

    public mixed $name





* Visibility: **public**
* This property is defined in [classes/shop/ShopGroup.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#32)


### $active

    public mixed $active = true





* Visibility: **public**
* This property is defined in [classes/shop/ShopGroup.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#33)


### $share_customer

    public mixed $share_customer





* Visibility: **public**
* This property is defined in [classes/shop/ShopGroup.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#34)


### $share_stock

    public mixed $share_stock





* Visibility: **public**
* This property is defined in [classes/shop/ShopGroup.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#35)


### $share_order

    public mixed $share_order





* Visibility: **public**
* This property is defined in [classes/shop/ShopGroup.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#36)


### $deleted

    public mixed $deleted





* Visibility: **public**
* This property is defined in [classes/shop/ShopGroup.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#37)


### $definition

    public mixed $definition = array('table' => 'shop_group', 'primary' => 'id_shop_group', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 64), 'share_customer' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'share_order' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'share_stock' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/shop/ShopGroup.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#42)


Methods
-------


### getFields

    array ShopGroupCore::getFields()





* Visibility: **public**
* This method is defined in [classes/shop/ShopGroup.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#59)




### getShopGroups

    mixed ShopGroupCore::getShopGroups($active)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/ShopGroup.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#68)


#### Arguments
* $active **mixed**



### getTotalShopGroup

    integer ShopGroupCore::getTotalShopGroup($active)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/ShopGroup.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#81)


#### Arguments
* $active **mixed**



### haveShops

    mixed ShopGroupCore::haveShops()





* Visibility: **public**
* This method is defined in [classes/shop/ShopGroup.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#86)




### getTotalShops

    mixed ShopGroupCore::getTotalShops()





* Visibility: **public**
* This method is defined in [classes/shop/ShopGroup.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#91)




### getShopsFromGroup

    mixed ShopGroupCore::getShopsFromGroup($id_group)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/ShopGroup.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#99)


#### Arguments
* $id_group **mixed**



### getIdByName

    integer ShopGroupCore::getIdByName(string $name)

Return a group shop ID from group shop name



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/ShopGroup.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#113)


#### Arguments
* $name **string**



### hasDependency

    boolean ShopGroupCore::hasDependency(integer $id_shop_group, string $check)

Detect dependency with customer or orders



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/shop/ShopGroup.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#128)


#### Arguments
* $id_shop_group **integer**
* $check **string** - &lt;p&gt;all|customer|order&lt;/p&gt;



### shopNameExists

    mixed ShopGroupCore::shopNameExists($name, $id_shop)





* Visibility: **public**
* This method is defined in [classes/shop/ShopGroup.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#160)


#### Arguments
* $name **mixed**
* $id_shop **mixed**


