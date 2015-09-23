Class DiscountCore
=====================





* Class name: DiscountCore
* Parent class: [CartRule](class.CartRuleCore.md)
* **Warning:** this class is **deprecated**. This means that this class will likely be removed in a future version.
* Source: [classes/Discount.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Discount.php#L30)


Contents
--------

### Constants

* [AMOUNT](#constant-AMOUNT)
* [FREE_SHIPPING](#constant-FREE_SHIPPING)
* [PERCENT](#constant-PERCENT)


### Methods

* [__call](#method-__call)
* [__get](#method-__get)
* [__set](#method-__set)
* [add](#method-add)
* [createOrderDiscount](#method-createOrderDiscount)
* [discountExists](#method-discountExists)
* [display](#method-display)
* [getCustomerDiscounts](#method-getCustomerDiscounts)
* [getIdByName](#method-getIdByName)
* [getValue](#method-getValue)
* [getVouchersToCartDisplay](#method-getVouchersToCartDisplay)
* [update](#method-update)


Constants
----------


### <a name="constant-AMOUNT"></a>AMOUNT

```php
const AMOUNT = 2
```





* **Warning:** this constant is **deprecated**. This means that this constant will likely be removed in a future version.
* Source: [classes/Discount.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Discount.php#L33).


### <a name="constant-FREE_SHIPPING"></a>FREE_SHIPPING

```php
const FREE_SHIPPING = 3
```





* **Warning:** this constant is **deprecated**. This means that this constant will likely be removed in a future version.
* Source: [classes/Discount.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Discount.php#L34).


### <a name="constant-PERCENT"></a>PERCENT

```php
const PERCENT = 1
```





* **Warning:** this constant is **deprecated**. This means that this constant will likely be removed in a future version.
* Source: [classes/Discount.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Discount.php#L32).




Methods
-------


### <a name="method-__call"></a>__call

```php
mixed DiscountCore::__call($method, $args)
```





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Discount.php#L124)


#### Arguments
* $method **mixed**
* $args **mixed**



### <a name="method-__get"></a>__get

```php
mixed DiscountCore::__get($key)
```





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Discount.php#L36)


#### Arguments
* $key **mixed**



### <a name="method-__set"></a>__set

```php
mixed DiscountCore::__set($key, $value)
```





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Discount.php#L76)


#### Arguments
* $key **mixed**
* $value **mixed**



### <a name="method-add"></a>add

```php
mixed DiscountCore::add($autodate, $nullValues, $categories)
```





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Discount.php#L136)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**
* $categories **mixed**



### <a name="method-createOrderDiscount"></a>createOrderDiscount

```php
mixed DiscountCore::createOrderDiscount($order, $productList, $qtyList, $name, $shipping_cost, $id_category, $subcategory)
```





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 203](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Discount.php#L203)


#### Arguments
* $order **mixed**
* $productList **mixed**
* $qtyList **mixed**
* $name **mixed**
* $shipping_cost **mixed**
* $id_category **mixed**
* $subcategory **mixed**



### <a name="method-discountExists"></a>discountExists

```php
mixed DiscountCore::discountExists($discountName, $id_discount)
```





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Discount.php#L195)


#### Arguments
* $discountName **mixed**
* $id_discount **mixed**



### <a name="method-display"></a>display

```php
mixed DiscountCore::display($value, $type, $currency)
```





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Discount.php#L255)


#### Arguments
* $value **mixed**
* $type **mixed**
* $currency **mixed**



### <a name="method-getCustomerDiscounts"></a>getCustomerDiscounts

```php
mixed DiscountCore::getCustomerDiscounts($id_lang, $id_customer, $active, $includeGenericOnes, $hasStock, \Cart $cart)
```





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Discount.php#L164)


#### Arguments
* $id_lang **mixed**
* $id_customer **mixed**
* $active **mixed**
* $includeGenericOnes **mixed**
* $hasStock **mixed**
* $cart **[Cart](class.CartCore.md)**



### <a name="method-getIdByName"></a>getIdByName

```php
mixed DiscountCore::getIdByName($code)
```





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Discount.php#L156)


#### Arguments
* $code **mixed**



### <a name="method-getValue"></a>getValue

```php
mixed DiscountCore::getValue($nb_discounts, $order_total_products, $shipping_fees, $id_cart, $useTax, \Currency $currency, \Shop $shop)
```





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Discount.php#L180)


#### Arguments
* $nb_discounts **mixed**
* $order_total_products **mixed**
* $shipping_fees **mixed**
* $id_cart **mixed**
* $useTax **mixed**
* $currency **[Currency](class.CurrencyCore.md)**
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-getVouchersToCartDisplay"></a>getVouchersToCartDisplay

```php
mixed DiscountCore::getVouchersToCartDisplay($id_lang, $id_customer)
```





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Discount.php#L172)


#### Arguments
* $id_lang **mixed**
* $id_customer **mixed**



### <a name="method-update"></a>update

```php
mixed DiscountCore::update($autodate, $nullValues, $categories)
```





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Discount.php#L146)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**
* $categories **mixed**


