ProductSupplierCore
===============






* Class name: ProductSupplierCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in classes\ProductSupplier.php line 30





Properties
----------


### $id_product

    public integer $id_product





* Visibility: **public**
* This property is defined in classes\ProductSupplier.php line 35


### $id_product_attribute

    public integer $id_product_attribute





* Visibility: **public**
* This property is defined in classes\ProductSupplier.php line 40


### $id_supplier

    public integer $id_supplier





* Visibility: **public**
* This property is defined in classes\ProductSupplier.php line 45


### $product_supplier_reference

    public string $product_supplier_reference





* Visibility: **public**
* This property is defined in classes\ProductSupplier.php line 50


### $id_currency

    public integer $id_currency





* Visibility: **public**
* This property is defined in classes\ProductSupplier.php line 55


### $product_supplier_price_te

    public string $product_supplier_price_te





* Visibility: **public**
* This property is defined in classes\ProductSupplier.php line 60


### $definition

    public mixed $definition = array('table' => 'product_supplier', 'primary' => 'id_product_supplier', 'fields' => array('product_supplier_reference' => array('type' => self::TYPE_STRING, 'validate' => 'isReference', 'size' => 32), 'id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_product_attribute' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_supplier' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'product_supplier_price_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'id_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId')))





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\ProductSupplier.php line 65


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'product_suppliers', 'objectNodeName' => 'product_supplier', 'fields' => array('id_product' => array('xlink_resource' => 'products'), 'id_product_attribute' => array('xlink_resource' => 'combinations'), 'id_supplier' => array('xlink_resource' => 'suppliers'), 'id_currency' => array('xlink_resource' => 'currencies')))





* Visibility: **protected**
* This property is defined in classes\ProductSupplier.php line 81


Methods
-------


### delete

    mixed ProductSupplierCore::delete()





* Visibility: **public**
* This method is defined in classes\ProductSupplier.php line 95




### getProductSupplierReference

    string ProductSupplierCore::getProductSupplierReference(integer $id_product, integer $id_product_attribute, integer $id_supplier)

For a given product and supplier, gets the product supplier reference



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ProductSupplier.php line 120


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $id_supplier **integer**



### getProductSupplierPrice

    array ProductSupplierCore::getProductSupplierPrice(integer $id_product, integer $id_product_attribute, integer $id_supplier, boolean $with_currency)

For a given product and supplier, gets the product supplier unit price



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ProductSupplier.php line 143


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $id_supplier **integer**
* $with_currency **boolean** - &lt;p&gt;Optional&lt;/p&gt;



### getIdByProductAndSupplier

    array ProductSupplierCore::getIdByProductAndSupplier(integer $id_product, integer $id_product_attribute, integer $id_supplier)

For a given product and supplier, gets corresponding ProductSupplier ID



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ProductSupplier.php line 177


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $id_supplier **integer**



### getSupplierCollection

    \PrestaShopCollection ProductSupplierCore::getSupplierCollection(integer $id_product, integer $group_by_supplier)

For a given product, retrieves its suppliers



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ProductSupplier.php line 198


#### Arguments
* $id_product **integer**
* $group_by_supplier **integer**



### getProductPrice

    Array ProductSupplierCore::getProductPrice($id_supplier, integer $id_product, integer $id_product_attribute, boolean $converted_price)

For a given Supplier, Product, returns the purchased price



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ProductSupplier.php line 218


#### Arguments
* $id_supplier **mixed**
* $id_product **integer**
* $id_product_attribute **integer** - &lt;p&gt;Optional&lt;/p&gt;
* $converted_price **boolean** - &lt;p&gt;Optional&lt;/p&gt;


