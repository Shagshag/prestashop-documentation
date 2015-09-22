CompareProductCore
===============






* Class name: CompareProductCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in classes\CompareProduct.php line 27





Properties
----------


### $id_compare

    public mixed $id_compare





* Visibility: **public**
* This property is defined in classes\CompareProduct.php line 29


### $id_customer

    public mixed $id_customer





* Visibility: **public**
* This property is defined in classes\CompareProduct.php line 31


### $date_add

    public mixed $date_add





* Visibility: **public**
* This property is defined in classes\CompareProduct.php line 33


### $date_upd

    public mixed $date_upd





* Visibility: **public**
* This property is defined in classes\CompareProduct.php line 35


### $definition

    public mixed $definition = array('table' => 'compare', 'primary' => 'id_compare', 'fields' => array('id_compare' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'required' => true), 'id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'required' => true)))





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\CompareProduct.php line 40


Methods
-------


### getCompareProducts

    array CompareProductCore::getCompareProducts($id_compare)

Get all compare products of the customer



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\CompareProduct.php line 54


#### Arguments
* $id_compare **mixed**



### addCompareProduct

    boolean CompareProductCore::addCompareProduct($id_compare, $id_product)

Add a compare product for the customer



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\CompareProduct.php line 79


#### Arguments
* $id_compare **mixed**
* $id_product **mixed**



### removeCompareProduct

    boolean CompareProductCore::removeCompareProduct(integer $id_compare, integer $id_product)

Remove a compare product for the customer



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\CompareProduct.php line 111


#### Arguments
* $id_compare **integer**
* $id_product **integer**



### getNumberProducts

    integer CompareProductCore::getNumberProducts(integer $id_compare)

Get the number of compare products of the customer



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\CompareProduct.php line 125


#### Arguments
* $id_compare **integer**



### cleanCompareProducts

    void CompareProductCore::cleanCompareProducts(string $period)

Clean entries which are older than the period



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\CompareProduct.php line 139


#### Arguments
* $period **string**



### getIdCompareByIdCustomer

    integer CompareProductCore::getIdCompareByIdCustomer(integer $id_customer)

Get the id_compare by id_customer



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\CompareProduct.php line 163


#### Arguments
* $id_customer **integer**


