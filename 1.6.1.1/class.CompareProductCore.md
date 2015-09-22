Class CompareProductCore
=====================





* Class name: CompareProductCore
* Parent class: [ObjectModel](class.ObjectModelCore)
* Source: [classes/CompareProduct.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CompareProduct.php#L27)



Properties
----------

* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$id_compare](#property-$id_compare)
* [$id_customer](#property-$id_customer)

Methods
-------
* [addCompareProduct](#method-addCompareProduct)
* [cleanCompareProducts](#method-cleanCompareProducts)
* [getCompareProducts](#method-getCompareProducts)
* [getIdCompareByIdCustomer](#method-getIdCompareByIdCustomer)
* [getNumberProducts](#method-getNumberProducts)
* [removeCompareProduct](#method-removeCompareProduct)




Properties
----------


### <a name="property-$date_add"></a>$date_add

    public mixed $date_add





* Visibility: **public**
* Source: [classes/CompareProduct.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CompareProduct.php#L33)


### <a name="property-$date_upd"></a>$date_upd

    public mixed $date_upd





* Visibility: **public**
* Source: [classes/CompareProduct.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CompareProduct.php#L35)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'compare', 'primary' => 'id_compare', 'fields' => array('id_compare' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'required' => true), 'id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'required' => true)))





* Visibility: **public**
* This property is **static**.
* Source: [classes/CompareProduct.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CompareProduct.php#L40)


### <a name="property-$id_compare"></a>$id_compare

    public mixed $id_compare





* Visibility: **public**
* Source: [classes/CompareProduct.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CompareProduct.php#L29)


### <a name="property-$id_customer"></a>$id_customer

    public mixed $id_customer





* Visibility: **public**
* Source: [classes/CompareProduct.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CompareProduct.php#L31)


Methods
-------


### <a name="method-addCompareProduct"></a>addCompareProduct

    boolean CompareProductCore::addCompareProduct($id_compare, $id_product)

Add a compare product for the customer



* Visibility: **public**
* This method is **static**.
* Source: [classes/CompareProduct.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CompareProduct.php#L79)


#### Arguments
* $id_compare **mixed**
* $id_product **mixed**



### <a name="method-cleanCompareProducts"></a>cleanCompareProducts

    void CompareProductCore::cleanCompareProducts(string $period)

Clean entries which are older than the period



* Visibility: **public**
* This method is **static**.
* Source: [classes/CompareProduct.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CompareProduct.php#L139)


#### Arguments
* $period **string**



### <a name="method-getCompareProducts"></a>getCompareProducts

    array CompareProductCore::getCompareProducts($id_compare)

Get all compare products of the customer



* Visibility: **public**
* This method is **static**.
* Source: [classes/CompareProduct.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CompareProduct.php#L54)


#### Arguments
* $id_compare **mixed**



### <a name="method-getIdCompareByIdCustomer"></a>getIdCompareByIdCustomer

    integer CompareProductCore::getIdCompareByIdCustomer(integer $id_customer)

Get the id_compare by id_customer



* Visibility: **public**
* This method is **static**.
* Source: [classes/CompareProduct.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CompareProduct.php#L163)


#### Arguments
* $id_customer **integer**



### <a name="method-getNumberProducts"></a>getNumberProducts

    integer CompareProductCore::getNumberProducts(integer $id_compare)

Get the number of compare products of the customer



* Visibility: **public**
* This method is **static**.
* Source: [classes/CompareProduct.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CompareProduct.php#L125)


#### Arguments
* $id_compare **integer**



### <a name="method-removeCompareProduct"></a>removeCompareProduct

    boolean CompareProductCore::removeCompareProduct(integer $id_compare, integer $id_product)

Remove a compare product for the customer



* Visibility: **public**
* This method is **static**.
* Source: [classes/CompareProduct.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CompareProduct.php#L111)


#### Arguments
* $id_compare **integer**
* $id_product **integer**


