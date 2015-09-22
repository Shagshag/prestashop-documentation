CustomizationCore
===============






* Class name: CustomizationCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/Customization.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#L27)





Properties
----------


### $id_product_attribute

    public integer $id_product_attribute





* Visibility: **public**
* This property is defined in [classes/Customization.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#30)


### $id_address_delivery

    public integer $id_address_delivery





* Visibility: **public**
* This property is defined in [classes/Customization.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#32)


### $id_cart

    public integer $id_cart





* Visibility: **public**
* This property is defined in [classes/Customization.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#34)


### $id_product

    public integer $id_product





* Visibility: **public**
* This property is defined in [classes/Customization.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#36)


### $quantity

    public integer $quantity





* Visibility: **public**
* This property is defined in [classes/Customization.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#38)


### $quantity_refunded

    public integer $quantity_refunded





* Visibility: **public**
* This property is defined in [classes/Customization.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#40)


### $quantity_returned

    public integer $quantity_returned





* Visibility: **public**
* This property is defined in [classes/Customization.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#42)


### $in_cart

    public boolean $in_cart





* Visibility: **public**
* This property is defined in [classes/Customization.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#44)


### $definition

    public mixed $definition = array('table' => 'customization', 'primary' => 'id_customization', 'fields' => array('id_product_attribute' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_address_delivery' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_cart' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'quantity' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'quantity_refunded' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'quantity_returned' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'in_cart' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Customization.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#49)


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_address_delivery' => array('xlink_resource' => array('resourceName' => 'addresses')), 'id_cart' => array('xlink_resource' => array('resourceName' => 'carts')), 'id_product' => array('xlink_resource' => array('resourceName' => 'products'))), 'associations' => array('customized_data_text_fields' => array('resource' => 'customized_data_text_field', 'virtual_entity' => true, 'fields' => array('id_customization_field' => array('required' => true, 'xlink_resource' => 'product_customization_fields'), 'value' => array())), 'customized_data_images' => array('resource' => 'customized_data_image', 'virtual_entity' => true, 'setter' => false, 'fields' => array('id_customization_field' => array('xlink_resource' => 'product_customization_fields'), 'value' => array()))))





* Visibility: **protected**
* This property is defined in [classes/Customization.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#64)


Methods
-------


### getReturnedCustomizations

    mixed CustomizationCore::getReturnedCustomizations($id_order)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Customization.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#96)


#### Arguments
* $id_order **mixed**



### getOrderedCustomizations

    mixed CustomizationCore::getOrderedCustomizations($id_cart)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Customization.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#112)


#### Arguments
* $id_cart **mixed**



### countCustomizationQuantityByProduct

    mixed CustomizationCore::countCustomizationQuantityByProduct($customizations)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Customization.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#124)


#### Arguments
* $customizations **mixed**



### getLabel

    mixed CustomizationCore::getLabel($id_customization, $id_lang, $id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Customization.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#133)


#### Arguments
* $id_customization **mixed**
* $id_lang **mixed**
* $id_shop **mixed**



### retrieveQuantitiesFromIds

    mixed CustomizationCore::retrieveQuantitiesFromIds($ids_customizations)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Customization.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#152)


#### Arguments
* $ids_customizations **mixed**



### countQuantityByCart

    mixed CustomizationCore::countQuantityByCart($id_cart)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Customization.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#178)


#### Arguments
* $id_cart **mixed**



### isFeatureActive

    boolean CustomizationCore::isFeatureActive()

This method is allow to know if a feature is used or active



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Customization.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#201)




### isCurrentlyUsed

    boolean CustomizationCore::isCurrentlyUsed($table, $has_active_column)

This method is allow to know if a Customization entity is currently used



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Customization.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#213)


#### Arguments
* $table **mixed**
* $has_active_column **mixed**



### getWsCustomizedDataTextFields

    mixed CustomizationCore::getWsCustomizedDataTextFields()





* Visibility: **public**
* This method is defined in [classes/Customization.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#221)




### getWsCustomizedDataImages

    mixed CustomizationCore::getWsCustomizedDataImages()





* Visibility: **public**
* This method is defined in [classes/Customization.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#234)




### setWsCustomizedDataTextFields

    mixed CustomizationCore::setWsCustomizedDataTextFields($values)





* Visibility: **public**
* This method is defined in [classes/Customization.php line 247](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#247)


#### Arguments
* $values **mixed**


