DiscountCore
===============






* Class name: DiscountCore
* Namespace: 
* Parent class: [CartRule](CartRuleCore)

* **Warning:** this class is **deprecated**. This means that this class will likely be removed in a future version.
* This class is defined in [classes/Discount.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#30)



Constants
----------


### PERCENT

    const PERCENT = 1



* **Warning:** this constant is **deprecated**. This means that this constant will likely be removed in a future version.
* This constant is defined in [classes/Discount.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#32)


### AMOUNT

    const AMOUNT = 2



* **Warning:** this constant is **deprecated**. This means that this constant will likely be removed in a future version.
* This constant is defined in [classes/Discount.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#33)


### FREE_SHIPPING

    const FREE_SHIPPING = 3



* **Warning:** this constant is **deprecated**. This means that this constant will likely be removed in a future version.
* This constant is defined in [classes/Discount.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#34)




Methods
-------


### __get

    mixed DiscountCore::__get($key)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/Discount.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#36)


#### Arguments
* $key **mixed**



### __set

    mixed DiscountCore::__set($key, $value)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/Discount.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#87)


#### Arguments
* $key **mixed**
* $value **mixed**



### __call

    mixed DiscountCore::__call($method, $args)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/Discount.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#137)


#### Arguments
* $method **mixed**
* $args **mixed**



### add

    mixed DiscountCore::add($autodate, $nullValues, $categories)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/Discount.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#150)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**
* $categories **mixed**



### update

    mixed DiscountCore::update($autodate, $nullValues, $categories)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/Discount.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#160)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**
* $categories **mixed**



### getIdByName

    mixed DiscountCore::getIdByName($code)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/Discount.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#170)


#### Arguments
* $code **mixed**



### getCustomerDiscounts

    mixed DiscountCore::getCustomerDiscounts($id_lang, $id_customer, $active, $includeGenericOnes, $hasStock, \Cart $cart)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/Discount.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#178)


#### Arguments
* $id_lang **mixed**
* $id_customer **mixed**
* $active **mixed**
* $includeGenericOnes **mixed**
* $hasStock **mixed**
* $cart **[Cart](CartCore)**



### getVouchersToCartDisplay

    mixed DiscountCore::getVouchersToCartDisplay($id_lang, $id_customer)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/Discount.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#186)


#### Arguments
* $id_lang **mixed**
* $id_customer **mixed**



### getValue

    mixed DiscountCore::getValue($nb_discounts, $order_total_products, $shipping_fees, $id_cart, $useTax, \Currency $currency, \Shop $shop)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/Discount.php line 194](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#194)


#### Arguments
* $nb_discounts **mixed**
* $order_total_products **mixed**
* $shipping_fees **mixed**
* $id_cart **mixed**
* $useTax **mixed**
* $currency **[Currency](CurrencyCore)**
* $shop **[Shop](ShopCore)**



### discountExists

    mixed DiscountCore::discountExists($discountName, $id_discount)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/Discount.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#212)


#### Arguments
* $discountName **mixed**
* $id_discount **mixed**



### createOrderDiscount

    \Discount DiscountCore::createOrderDiscount(\Order $order, $productList, $qtyList, $name, $shipping_cost, $id_category, $subcategory)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/Discount.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#222)


#### Arguments
* $order **[Order](OrderCore)**
* $productList **mixed**
* $qtyList **mixed**
* $name **mixed**
* $shipping_cost **mixed**
* $id_category **mixed**
* $subcategory **mixed**



### display

    mixed DiscountCore::display($value, $type, $currency)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/Discount.php line 277](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Discount.php#277)


#### Arguments
* $value **mixed**
* $type **mixed**
* $currency **mixed**


