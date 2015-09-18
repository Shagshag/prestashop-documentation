CustomizationCore
===============






* Class name: CustomizationCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id_product_attribute

    public integer $id_product_attribute





* Visibility: **public**


### $id_address_delivery

    public integer $id_address_delivery





* Visibility: **public**


### $id_cart

    public integer $id_cart





* Visibility: **public**


### $id_product

    public integer $id_product





* Visibility: **public**


### $quantity

    public integer $quantity





* Visibility: **public**


### $quantity_refunded

    public integer $quantity_refunded





* Visibility: **public**


### $quantity_returned

    public integer $quantity_returned





* Visibility: **public**


### $in_cart

    public boolean $in_cart





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'customization', 'primary' => 'id_customization', 'fields' => array('id_product_attribute' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_address_delivery' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_cart' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'quantity' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'quantity_refunded' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'quantity_returned' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'in_cart' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true)))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_address_delivery' => array('xlink_resource' => array('resourceName' => 'addresses')), 'id_cart' => array('xlink_resource' => array('resourceName' => 'carts')), 'id_product' => array('xlink_resource' => array('resourceName' => 'products'))), 'associations' => array('customized_data_text_fields' => array('resource' => 'customized_data_text_field', 'virtual_entity' => true, 'fields' => array('id_customization_field' => array('required' => true, 'xlink_resource' => 'product_customization_fields'), 'value' => array())), 'customized_data_images' => array('resource' => 'customized_data_image', 'virtual_entity' => true, 'setter' => false, 'fields' => array('id_customization_field' => array('xlink_resource' => 'product_customization_fields'), 'value' => array()))))





* Visibility: **protected**


Methods
-------


### getReturnedCustomizations

    mixed CustomizationCore::getReturnedCustomizations($id_order)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_order **mixed**



### getOrderedCustomizations

    mixed CustomizationCore::getOrderedCustomizations($id_cart)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_cart **mixed**



### countCustomizationQuantityByProduct

    mixed CustomizationCore::countCustomizationQuantityByProduct($customizations)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $customizations **mixed**



### getLabel

    mixed CustomizationCore::getLabel($id_customization, $id_lang, $id_shop)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_customization **mixed**
* $id_lang **mixed**
* $id_shop **mixed**



### retrieveQuantitiesFromIds

    mixed CustomizationCore::retrieveQuantitiesFromIds($ids_customizations)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $ids_customizations **mixed**



### countQuantityByCart

    mixed CustomizationCore::countQuantityByCart($id_cart)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_cart **mixed**



### isFeatureActive

    boolean CustomizationCore::isFeatureActive()

This method is allow to know if a feature is used or active



* Visibility: **public**
* This method is **static**.




### isCurrentlyUsed

    boolean CustomizationCore::isCurrentlyUsed($table, $has_active_column)

This method is allow to know if a Customization entity is currently used



* Visibility: **public**
* This method is **static**.


#### Arguments
* $table **mixed**
* $has_active_column **mixed**



### getWsCustomizedDataTextFields

    mixed CustomizationCore::getWsCustomizedDataTextFields()





* Visibility: **public**




### getWsCustomizedDataImages

    mixed CustomizationCore::getWsCustomizedDataImages()





* Visibility: **public**




### setWsCustomizedDataTextFields

    mixed CustomizationCore::setWsCustomizedDataTextFields($values)





* Visibility: **public**


#### Arguments
* $values **mixed**


