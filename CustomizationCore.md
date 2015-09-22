CustomizationCore
===============






* Class name: CustomizationCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/Customization.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#L27)





Properties
----------

* [$id_product_attribute](#property-$id_product_attribute)
* [$id_address_delivery](#property-$id_address_delivery)
* [$id_cart](#property-$id_cart)
* [$id_product](#property-$id_product)
* [$quantity](#property-$quantity)
* [$quantity_refunded](#property-$quantity_refunded)
* [$quantity_returned](#property-$quantity_returned)
* [$in_cart](#property-$in_cart)
* [$definition](#property-$definition)
* [$webserviceParameters](#property-$webserviceParameters)

Methods
-------
* [getReturnedCustomizations](#method-getReturnedCustomizations)
* [getOrderedCustomizations](#method-getOrderedCustomizations)
* [countCustomizationQuantityByProduct](#method-countCustomizationQuantityByProduct)
* [getLabel](#method-getLabel)
* [retrieveQuantitiesFromIds](#method-retrieveQuantitiesFromIds)
* [countQuantityByCart](#method-countQuantityByCart)
* [isFeatureActive](#method-isFeatureActive)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [getWsCustomizedDataTextFields](#method-getWsCustomizedDataTextFields)
* [getWsCustomizedDataImages](#method-getWsCustomizedDataImages)
* [setWsCustomizedDataTextFields](#method-setWsCustomizedDataTextFields)




Properties
----------


### <a name="property-$id_product_attribute"></a>$id_product_attribute

    public integer $id_product_attribute





* Visibility: **public**
* This property is defined in [classes/Customization.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#L30)


### <a name="property-$id_address_delivery"></a>$id_address_delivery

    public integer $id_address_delivery





* Visibility: **public**
* This property is defined in [classes/Customization.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#L32)


### <a name="property-$id_cart"></a>$id_cart

    public integer $id_cart





* Visibility: **public**
* This property is defined in [classes/Customization.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#L34)


### <a name="property-$id_product"></a>$id_product

    public integer $id_product





* Visibility: **public**
* This property is defined in [classes/Customization.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#L36)


### <a name="property-$quantity"></a>$quantity

    public integer $quantity





* Visibility: **public**
* This property is defined in [classes/Customization.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#L38)


### <a name="property-$quantity_refunded"></a>$quantity_refunded

    public integer $quantity_refunded





* Visibility: **public**
* This property is defined in [classes/Customization.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#L40)


### <a name="property-$quantity_returned"></a>$quantity_returned

    public integer $quantity_returned





* Visibility: **public**
* This property is defined in [classes/Customization.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#L42)


### <a name="property-$in_cart"></a>$in_cart

    public boolean $in_cart





* Visibility: **public**
* This property is defined in [classes/Customization.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#L44)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'customization', 'primary' => 'id_customization', 'fields' => array('id_product_attribute' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_address_delivery' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_cart' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'quantity' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'quantity_refunded' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'quantity_returned' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'in_cart' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Customization.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#L49)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_address_delivery' => array('xlink_resource' => array('resourceName' => 'addresses')), 'id_cart' => array('xlink_resource' => array('resourceName' => 'carts')), 'id_product' => array('xlink_resource' => array('resourceName' => 'products'))), 'associations' => array('customized_data_text_fields' => array('resource' => 'customized_data_text_field', 'virtual_entity' => true, 'fields' => array('id_customization_field' => array('required' => true, 'xlink_resource' => 'product_customization_fields'), 'value' => array())), 'customized_data_images' => array('resource' => 'customized_data_image', 'virtual_entity' => true, 'setter' => false, 'fields' => array('id_customization_field' => array('xlink_resource' => 'product_customization_fields'), 'value' => array()))))





* Visibility: **protected**
* This property is defined in [classes/Customization.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#L64)


Methods
-------


### <a name="method-getReturnedCustomizations"></a>getReturnedCustomizations

    mixed CustomizationCore::getReturnedCustomizations($id_order)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Customization.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#L96)


#### Arguments
* $id_order **mixed**



### <a name="method-getOrderedCustomizations"></a>getOrderedCustomizations

    mixed CustomizationCore::getOrderedCustomizations($id_cart)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Customization.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#L112)


#### Arguments
* $id_cart **mixed**



### <a name="method-countCustomizationQuantityByProduct"></a>countCustomizationQuantityByProduct

    mixed CustomizationCore::countCustomizationQuantityByProduct($customizations)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Customization.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#L124)


#### Arguments
* $customizations **mixed**



### <a name="method-getLabel"></a>getLabel

    mixed CustomizationCore::getLabel($id_customization, $id_lang, $id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Customization.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#L133)


#### Arguments
* $id_customization **mixed**
* $id_lang **mixed**
* $id_shop **mixed**



### <a name="method-retrieveQuantitiesFromIds"></a>retrieveQuantitiesFromIds

    mixed CustomizationCore::retrieveQuantitiesFromIds($ids_customizations)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Customization.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#L152)


#### Arguments
* $ids_customizations **mixed**



### <a name="method-countQuantityByCart"></a>countQuantityByCart

    mixed CustomizationCore::countQuantityByCart($id_cart)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Customization.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#L178)


#### Arguments
* $id_cart **mixed**



### <a name="method-isFeatureActive"></a>isFeatureActive

    boolean CustomizationCore::isFeatureActive()

This method is allow to know if a feature is used or active



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Customization.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#L201)




### <a name="method-isCurrentlyUsed"></a>isCurrentlyUsed

    boolean CustomizationCore::isCurrentlyUsed($table, $has_active_column)

This method is allow to know if a Customization entity is currently used



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Customization.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#L213)


#### Arguments
* $table **mixed**
* $has_active_column **mixed**



### <a name="method-getWsCustomizedDataTextFields"></a>getWsCustomizedDataTextFields

    mixed CustomizationCore::getWsCustomizedDataTextFields()





* Visibility: **public**
* This method is defined in [classes/Customization.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#L221)




### <a name="method-getWsCustomizedDataImages"></a>getWsCustomizedDataImages

    mixed CustomizationCore::getWsCustomizedDataImages()





* Visibility: **public**
* This method is defined in [classes/Customization.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#L234)




### <a name="method-setWsCustomizedDataTextFields"></a>setWsCustomizedDataTextFields

    mixed CustomizationCore::setWsCustomizedDataTextFields($values)





* Visibility: **public**
* This method is defined in [classes/Customization.php line 247](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Customization.php#L247)


#### Arguments
* $values **mixed**


