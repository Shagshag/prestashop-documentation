Class ProductSupplierCore
=====================





* Class name: ProductSupplierCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/ProductSupplier.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductSupplier.php#L30)



Properties
----------

* [$definition](#property-$definition)
* [$id_currency](#property-$id_currency)
* [$id_product](#property-$id_product)
* [$id_product_attribute](#property-$id_product_attribute)
* [$id_supplier](#property-$id_supplier)
* [$product_supplier_price_te](#property-$product_supplier_price_te)
* [$product_supplier_reference](#property-$product_supplier_reference)
* [$webserviceParameters](#property-$webserviceParameters)

Methods
-------
* [delete](#method-delete)
* [getIdByProductAndSupplier](#method-getIdByProductAndSupplier)
* [getProductPrice](#method-getProductPrice)
* [getProductSupplierPrice](#method-getProductSupplierPrice)
* [getProductSupplierReference](#method-getProductSupplierReference)
* [getSupplierCollection](#method-getSupplierCollection)




Properties
----------


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'product_supplier', 'primary' => 'id_product_supplier', 'fields' => array('product_supplier_reference' => array('type' => self::TYPE_STRING, 'validate' => 'isReference', 'size' => 32), 'id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_product_attribute' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_supplier' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'product_supplier_price_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice'), 'id_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId')))





* Visibility: **public**
* This property is **static**.
* Source: [classes/ProductSupplier.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductSupplier.php#L65)


### <a name="property-$id_currency"></a>$id_currency

    public integer $id_currency





* Visibility: **public**
* Source: [classes/ProductSupplier.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductSupplier.php#L55)


### <a name="property-$id_product"></a>$id_product

    public integer $id_product





* Visibility: **public**
* Source: [classes/ProductSupplier.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductSupplier.php#L35)


### <a name="property-$id_product_attribute"></a>$id_product_attribute

    public integer $id_product_attribute





* Visibility: **public**
* Source: [classes/ProductSupplier.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductSupplier.php#L40)


### <a name="property-$id_supplier"></a>$id_supplier

    public integer $id_supplier





* Visibility: **public**
* Source: [classes/ProductSupplier.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductSupplier.php#L45)


### <a name="property-$product_supplier_price_te"></a>$product_supplier_price_te

    public string $product_supplier_price_te





* Visibility: **public**
* Source: [classes/ProductSupplier.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductSupplier.php#L60)


### <a name="property-$product_supplier_reference"></a>$product_supplier_reference

    public string $product_supplier_reference





* Visibility: **public**
* Source: [classes/ProductSupplier.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductSupplier.php#L50)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'product_suppliers', 'objectNodeName' => 'product_supplier', 'fields' => array('id_product' => array('xlink_resource' => 'products'), 'id_product_attribute' => array('xlink_resource' => 'combinations'), 'id_supplier' => array('xlink_resource' => 'suppliers'), 'id_currency' => array('xlink_resource' => 'currencies')))





* Visibility: **protected**
* Source: [classes/ProductSupplier.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductSupplier.php#L81)


Methods
-------


### <a name="method-delete"></a>delete

    mixed ProductSupplierCore::delete()





* Visibility: **public**
* Source: [classes/ProductSupplier.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductSupplier.php#L95)




### <a name="method-getIdByProductAndSupplier"></a>getIdByProductAndSupplier

    array ProductSupplierCore::getIdByProductAndSupplier(integer $id_product, integer $id_product_attribute, integer $id_supplier)

For a given product and supplier, gets corresponding ProductSupplier ID



* Visibility: **public**
* This method is **static**.
* Source: [classes/ProductSupplier.php line 177](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductSupplier.php#L177)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $id_supplier **integer**



### <a name="method-getProductPrice"></a>getProductPrice

    Array ProductSupplierCore::getProductPrice($id_supplier, integer $id_product, integer $id_product_attribute, boolean $converted_price)

For a given Supplier, Product, returns the purchased price



* Visibility: **public**
* This method is **static**.
* Source: [classes/ProductSupplier.php line 218](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductSupplier.php#L218)


#### Arguments
* $id_supplier **mixed**
* $id_product **integer**
* $id_product_attribute **integer** - Optional
* $converted_price **boolean** - Optional



### <a name="method-getProductSupplierPrice"></a>getProductSupplierPrice

    array ProductSupplierCore::getProductSupplierPrice(integer $id_product, integer $id_product_attribute, integer $id_supplier, boolean $with_currency)

For a given product and supplier, gets the product supplier unit price



* Visibility: **public**
* This method is **static**.
* Source: [classes/ProductSupplier.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductSupplier.php#L143)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $id_supplier **integer**
* $with_currency **boolean** - Optional



### <a name="method-getProductSupplierReference"></a>getProductSupplierReference

    string ProductSupplierCore::getProductSupplierReference(integer $id_product, integer $id_product_attribute, integer $id_supplier)

For a given product and supplier, gets the product supplier reference



* Visibility: **public**
* This method is **static**.
* Source: [classes/ProductSupplier.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductSupplier.php#L120)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer**
* $id_supplier **integer**



### <a name="method-getSupplierCollection"></a>getSupplierCollection

    \PrestaShopCollection ProductSupplierCore::getSupplierCollection(integer $id_product, integer $group_by_supplier)

For a given product, retrieves its suppliers



* Visibility: **public**
* This method is **static**.
* Source: [classes/ProductSupplier.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ProductSupplier.php#L198)


#### Arguments
* $id_product **integer**
* $group_by_supplier **integer**


