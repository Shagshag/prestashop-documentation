SupplyOrderDetailCore
===============

Represents one product ordered




* Class name: SupplyOrderDetailCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id_supply_order

    public integer $id_supply_order





* Visibility: **public**


### $id_product

    public integer $id_product





* Visibility: **public**


### $id_product_attribute

    public integer $id_product_attribute





* Visibility: **public**


### $reference

    public string $reference





* Visibility: **public**


### $supplier_reference

    public string $supplier_reference





* Visibility: **public**


### $name

    public integer $name





* Visibility: **public**


### $ean13

    public integer $ean13





* Visibility: **public**


### $upc

    public string $upc





* Visibility: **public**


### $id_currency

    public integer $id_currency





* Visibility: **public**


### $exchange_rate

    public float $exchange_rate





* Visibility: **public**


### $unit_price_te

    public float $unit_price_te





* Visibility: **public**


### $quantity_expected

    public integer $quantity_expected





* Visibility: **public**


### $quantity_received

    public integer $quantity_received





* Visibility: **public**


### $price_te

    public float $price_te





* Visibility: **public**


### $discount_rate

    public float $discount_rate





* Visibility: **public**


### $discount_value_te

    public float $discount_value_te





* Visibility: **public**


### $price_with_discount_te

    public float $price_with_discount_te





* Visibility: **public**


### $tax_rate

    public integer $tax_rate





* Visibility: **public**


### $tax_value

    public float $tax_value





* Visibility: **public**


### $price_ti

    public float $price_ti





* Visibility: **public**


### $tax_value_with_order_discount

    public float $tax_value_with_order_discount





* Visibility: **public**


### $price_with_order_discount_te

    public float $price_with_order_discount_te





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'supply_order_detail', 'primary' => 'id_supply_order_detail', 'fields' => array('id_supply_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_product_attribute' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'reference' => array('type' => self::TYPE_STRING, 'validate' => 'isReference'), 'supplier_reference' => array('type' => self::TYPE_STRING, 'validate' => 'isReference'), 'name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true), 'ean13' => array('type' => self::TYPE_STRING, 'validate' => 'isEan13'), 'upc' => array('type' => self::TYPE_STRING, 'validate' => 'isUpc'), 'id_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'exchange_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'unit_price_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'quantity_expected' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'required' => true), 'quantity_received' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'price_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'discount_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'discount_value_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'price_with_discount_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'tax_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'tax_value' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'price_ti' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'tax_value_with_order_discount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'price_with_order_discount_te' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true)))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'supply_order_details', 'objectNodeName' => 'supply_order_detail', 'fields' => array('id_supply_order' => array('xlink_resource' => 'supply_orders'), 'id_product' => array('xlink_resource' => 'products'), 'id_product_attribute' => array('xlink_resource' => 'combinations')), 'hidden_fields' => array('id_currency'))





* Visibility: **protected**


Methods
-------


### update

    mixed SupplyOrderDetailCore::update($null_values)





* Visibility: **public**


#### Arguments
* $null_values **mixed**



### add

    mixed SupplyOrderDetailCore::add($autodate, $null_values)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### calculatePrices

    mixed SupplyOrderDetailCore::calculatePrices()

Calculates all prices for this product based on its quantity and unit price
Applies discount if necessary
Calculates tax value, function of tax rate



* Visibility: **protected**




### applyGlobalDiscount

    mixed SupplyOrderDetailCore::applyGlobalDiscount(float|integer $discount_rate)

Applies a global order discount rate, for the current product (i.e detail)
Calls ObjectModel::update()



* Visibility: **public**


#### Arguments
* $discount_rate **float|integer** - &lt;p&gt;The discount rate in percent (Ex. 5 for 5 percents)&lt;/p&gt;



### validateController

    array SupplyOrderDetailCore::validateController(boolean $htmlentities)





* Visibility: **public**


#### Arguments
* $htmlentities **boolean** - &lt;p&gt;Optional&lt;/p&gt;



### hydrate

    mixed SupplyOrderDetailCore::hydrate(array $data, $id_lang)





* Visibility: **public**


#### Arguments
* $data **array**
* $id_lang **mixed**


