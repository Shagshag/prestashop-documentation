DiscountCore
===============






* Class name: DiscountCore
* Namespace: 
* Parent class: CartRule
* **Warning:** this class is **deprecated**. This means that this class will likely be removed in a future version.



Constants
----------


### PERCENT

    const PERCENT = 1



* **Warning:** this constant is **deprecated**. This means that this constant will likely be removed in a future version.


### AMOUNT

    const AMOUNT = 2



* **Warning:** this constant is **deprecated**. This means that this constant will likely be removed in a future version.


### FREE_SHIPPING

    const FREE_SHIPPING = 3



* **Warning:** this constant is **deprecated**. This means that this constant will likely be removed in a future version.




Methods
-------


### __get

    mixed DiscountCore::__get($key)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.


#### Arguments
* $key **mixed**



### __set

    mixed DiscountCore::__set($key, $value)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.


#### Arguments
* $key **mixed**
* $value **mixed**



### __call

    mixed DiscountCore::__call($method, $args)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.


#### Arguments
* $method **mixed**
* $args **mixed**



### add

    mixed DiscountCore::add($autodate, $nullValues, $categories)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**
* $categories **mixed**



### update

    mixed DiscountCore::update($autodate, $nullValues, $categories)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**
* $categories **mixed**



### getIdByName

    mixed DiscountCore::getIdByName($code)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.


#### Arguments
* $code **mixed**



### getCustomerDiscounts

    mixed DiscountCore::getCustomerDiscounts($id_lang, $id_customer, $active, $includeGenericOnes, $hasStock, \Cart $cart)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.


#### Arguments
* $id_lang **mixed**
* $id_customer **mixed**
* $active **mixed**
* $includeGenericOnes **mixed**
* $hasStock **mixed**
* $cart **Cart**



### getVouchersToCartDisplay

    mixed DiscountCore::getVouchersToCartDisplay($id_lang, $id_customer)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.


#### Arguments
* $id_lang **mixed**
* $id_customer **mixed**



### getValue

    mixed DiscountCore::getValue($nb_discounts, $order_total_products, $shipping_fees, $id_cart, $useTax, \Currency $currency, \Shop $shop)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.


#### Arguments
* $nb_discounts **mixed**
* $order_total_products **mixed**
* $shipping_fees **mixed**
* $id_cart **mixed**
* $useTax **mixed**
* $currency **Currency**
* $shop **Shop**



### discountExists

    mixed DiscountCore::discountExists($discountName, $id_discount)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.


#### Arguments
* $discountName **mixed**
* $id_discount **mixed**



### createOrderDiscount

    \Discount DiscountCore::createOrderDiscount(\Order $order, $productList, $qtyList, $name, $shipping_cost, $id_category, $subcategory)





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.


#### Arguments
* $order **Order**
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


#### Arguments
* $value **mixed**
* $type **mixed**
* $currency **mixed**


