Class ShopGroupCore
=====================





* Class name: ShopGroupCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/shop/ShopGroup.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#L30)


Contents
--------


### Properties

* [$active](#property-$active)
* [$definition](#property-$definition)
* [$deleted](#property-$deleted)
* [$name](#property-$name)
* [$share_customer](#property-$share_customer)
* [$share_order](#property-$share_order)
* [$share_stock](#property-$share_stock)

### Methods

* [getFields](#method-getFields)
* [getIdByName](#method-getIdByName)
* [getShopGroups](#method-getShopGroups)
* [getShopsFromGroup](#method-getShopsFromGroup)
* [getTotalShopGroup](#method-getTotalShopGroup)
* [getTotalShops](#method-getTotalShops)
* [hasDependency](#method-hasDependency)
* [haveShops](#method-haveShops)
* [shopNameExists](#method-shopNameExists)




Properties
----------


### <a name="property-$active"></a>$active

```php
public mixed $active = true
```





* Visibility: **public**
* Source: [classes/shop/ShopGroup.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#L33).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'shop_group', 'primary' => 'id_shop_group', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 64), 'share_customer' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'share_order' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'share_stock' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/shop/ShopGroup.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#L42).


### <a name="property-$deleted"></a>$deleted

```php
public mixed $deleted
```





* Visibility: **public**
* Source: [classes/shop/ShopGroup.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#L37).


### <a name="property-$name"></a>$name

```php
public mixed $name
```





* Visibility: **public**
* Source: [classes/shop/ShopGroup.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#L32).


### <a name="property-$share_customer"></a>$share_customer

```php
public mixed $share_customer
```





* Visibility: **public**
* Source: [classes/shop/ShopGroup.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#L34).


### <a name="property-$share_order"></a>$share_order

```php
public mixed $share_order
```





* Visibility: **public**
* Source: [classes/shop/ShopGroup.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#L36).


### <a name="property-$share_stock"></a>$share_stock

```php
public mixed $share_stock
```





* Visibility: **public**
* Source: [classes/shop/ShopGroup.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#L35).


Methods
-------


### <a name="method-getFields"></a>getFields

```php
array ShopGroupCore::getFields()
```





* Visibility: **public**
* Source: [classes/shop/ShopGroup.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#L59)




### <a name="method-getIdByName"></a>getIdByName

```php
integer ShopGroupCore::getIdByName(string $name)
```

Return a group shop ID from group shop name



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/ShopGroup.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#L113)


#### Arguments
* $name **string**



### <a name="method-getShopGroups"></a>getShopGroups

```php
mixed ShopGroupCore::getShopGroups($active)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/ShopGroup.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#L68)


#### Arguments
* $active **mixed**



### <a name="method-getShopsFromGroup"></a>getShopsFromGroup

```php
mixed ShopGroupCore::getShopsFromGroup($id_group)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/ShopGroup.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#L99)


#### Arguments
* $id_group **mixed**



### <a name="method-getTotalShopGroup"></a>getTotalShopGroup

```php
integer ShopGroupCore::getTotalShopGroup($active)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/ShopGroup.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#L81)


#### Arguments
* $active **mixed**



### <a name="method-getTotalShops"></a>getTotalShops

```php
mixed ShopGroupCore::getTotalShops()
```





* Visibility: **public**
* Source: [classes/shop/ShopGroup.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#L91)




### <a name="method-hasDependency"></a>hasDependency

```php
boolean ShopGroupCore::hasDependency(integer $id_shop_group, string $check)
```

Detect dependency with customer or orders



* Visibility: **public**
* This method is **static**.
* Source: [classes/shop/ShopGroup.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#L128)


#### Arguments
* $id_shop_group **integer**
* $check **string** - all|customer|order



### <a name="method-haveShops"></a>haveShops

```php
mixed ShopGroupCore::haveShops()
```





* Visibility: **public**
* Source: [classes/shop/ShopGroup.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#L86)




### <a name="method-shopNameExists"></a>shopNameExists

```php
mixed ShopGroupCore::shopNameExists($name, $id_shop)
```





* Visibility: **public**
* Source: [classes/shop/ShopGroup.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/shop/ShopGroup.php#L160)


#### Arguments
* $name **mixed**
* $id_shop **mixed**


