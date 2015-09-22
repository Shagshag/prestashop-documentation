Class DiscountCore
=====================





* Class name: DiscountCore
* Parent class: [CartRule](class.CartRuleCore)
* **Warning:** this class is **deprecated**. This means that this class will likely be removed in a future version.
* Source: [classes/Discount.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#L30)

Constants
----------

* [AMOUNT](#constant-AMOUNT)
* [FREE_SHIPPING](#constant-FREE_SHIPPING)
* [PERCENT](#constant-PERCENT)



Methods
-------
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

    const AMOUNT = 2



* **Warning:** this constant is **deprecated**. This means that this constant will likely be removed in a future version.
* Source: [classes/Discount.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#L33)


### <a name="constant-FREE_SHIPPING"></a>FREE_SHIPPING

    const FREE_SHIPPING = 3



* **Warning:** this constant is **deprecated**. This means that this constant will likely be removed in a future version.
* Source: [classes/Discount.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#L34)


### <a name="constant-PERCENT"></a>PERCENT

    const PERCENT = 1



* **Warning:** this constant is **deprecated**. This means that this constant will likely be removed in a future version.
* Source: [classes/Discount.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#L32)




Methods
-------


### <a name="method-__call"></a>__call

    mixed DiscountCore::__call($method, $args)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#L137)


#### Arguments
* $method **mixed**
* $args **mixed**



### <a name="method-__get"></a>__get

    mixed DiscountCore::__get($key)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#L36)


#### Arguments
* $key **mixed**



### <a name="method-__set"></a>__set

    mixed DiscountCore::__set($key, $value)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#L87)


#### Arguments
* $key **mixed**
* $value **mixed**



### <a name="method-add"></a>add

    mixed DiscountCore::add($autodate, $nullValues, $categories)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#L150)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**
* $categories **mixed**



### <a name="method-createOrderDiscount"></a>createOrderDiscount

    \Discount DiscountCore::createOrderDiscount(\Order $order, $productList, $qtyList, $name, $shipping_cost, $id_category, $subcategory)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#L222)


#### Arguments
* $order **[Order](class.OrderCore)**
* $productList **mixed**
* $qtyList **mixed**
* $name **mixed**
* $shipping_cost **mixed**
* $id_category **mixed**
* $subcategory **mixed**



### <a name="method-discountExists"></a>discountExists

    mixed DiscountCore::discountExists($discountName, $id_discount)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#L212)


#### Arguments
* $discountName **mixed**
* $id_discount **mixed**



### <a name="method-display"></a>display

    mixed DiscountCore::display($value, $type, $currency)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 277](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#L277)


#### Arguments
* $value **mixed**
* $type **mixed**
* $currency **mixed**



### <a name="method-getCustomerDiscounts"></a>getCustomerDiscounts

    mixed DiscountCore::getCustomerDiscounts($id_lang, $id_customer, $active, $includeGenericOnes, $hasStock, \Cart $cart)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#L178)


#### Arguments
* $id_lang **mixed**
* $id_customer **mixed**
* $active **mixed**
* $includeGenericOnes **mixed**
* $hasStock **mixed**
* $cart **[Cart](class.CartCore)**



### <a name="method-getIdByName"></a>getIdByName

    mixed DiscountCore::getIdByName($code)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#L170)


#### Arguments
* $code **mixed**



### <a name="method-getValue"></a>getValue

    mixed DiscountCore::getValue($nb_discounts, $order_total_products, $shipping_fees, $id_cart, $useTax, \Currency $currency, \Shop $shop)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 194](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#L194)


#### Arguments
* $nb_discounts **mixed**
* $order_total_products **mixed**
* $shipping_fees **mixed**
* $id_cart **mixed**
* $useTax **mixed**
* $currency **[Currency](class.CurrencyCore)**
* $shop **[Shop](class.ShopCore)**



### <a name="method-getVouchersToCartDisplay"></a>getVouchersToCartDisplay

    mixed DiscountCore::getVouchersToCartDisplay($id_lang, $id_customer)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#L186)


#### Arguments
* $id_lang **mixed**
* $id_customer **mixed**



### <a name="method-update"></a>update

    mixed DiscountCore::update($autodate, $nullValues, $categories)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#L160)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**
* $categories **mixed**

