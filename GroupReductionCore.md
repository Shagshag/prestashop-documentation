GroupReductionCore
===============






* Class name: GroupReductionCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)

* This class is defined in [classes/GroupReduction.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/GroupReduction.php#27)





Properties
----------


### $id_group

    public mixed $id_group





* Visibility: **public**
* This property is defined in [classes/GroupReduction.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/GroupReduction.php#29)


### $id_category

    public mixed $id_category





* Visibility: **public**
* This property is defined in [classes/GroupReduction.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/GroupReduction.php#30)


### $reduction

    public mixed $reduction





* Visibility: **public**
* This property is defined in [classes/GroupReduction.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/GroupReduction.php#31)


### $definition

    public mixed $definition = array('table' => 'group_reduction', 'primary' => 'id_group_reduction', 'fields' => array('id_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_category' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'reduction' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/GroupReduction.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/GroupReduction.php#36)


### $reduction_cache

    protected mixed $reduction_cache = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/GroupReduction.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/GroupReduction.php#46)


Methods
-------


### add

    mixed GroupReductionCore::add($autodate, $null_values)





* Visibility: **public**
* This method is defined in [classes/GroupReduction.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/GroupReduction.php#48)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### update

    mixed GroupReductionCore::update($null_values)





* Visibility: **public**
* This method is defined in [classes/GroupReduction.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/GroupReduction.php#53)


#### Arguments
* $null_values **mixed**



### delete

    mixed GroupReductionCore::delete()





* Visibility: **public**
* This method is defined in [classes/GroupReduction.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/GroupReduction.php#58)




### _clearCache

    mixed GroupReductionCore::_clearCache()





* Visibility: **protected**
* This method is defined in [classes/GroupReduction.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/GroupReduction.php#77)




### _setCache

    mixed GroupReductionCore::_setCache()





* Visibility: **protected**
* This method is defined in [classes/GroupReduction.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/GroupReduction.php#82)




### _updateCache

    mixed GroupReductionCore::_updateCache()





* Visibility: **protected**
* This method is defined in [classes/GroupReduction.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/GroupReduction.php#105)




### getGroupReductions

    mixed GroupReductionCore::getGroupReductions($id_group, $id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/GroupReduction.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/GroupReduction.php#128)


#### Arguments
* $id_group **mixed**
* $id_lang **mixed**



### getValueForProduct

    mixed GroupReductionCore::getValueForProduct($id_product, $id_group)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/GroupReduction.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/GroupReduction.php#139)


#### Arguments
* $id_product **mixed**
* $id_group **mixed**



### doesExist

    mixed GroupReductionCore::doesExist($id_group, $id_category)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/GroupReduction.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/GroupReduction.php#155)


#### Arguments
* $id_group **mixed**
* $id_category **mixed**



### getGroupsByCategoryId

    mixed GroupReductionCore::getGroupsByCategoryId($id_category)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/GroupReduction.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/GroupReduction.php#163)


#### Arguments
* $id_category **mixed**



### getGroupByCategoryId

    array|null GroupReductionCore::getGroupByCategoryId(integer $id_category)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/GroupReduction.php line 177](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/GroupReduction.php#177)


#### Arguments
* $id_category **integer**



### getGroupsReductionByCategoryId

    mixed GroupReductionCore::getGroupsReductionByCategoryId($id_category)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/GroupReduction.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/GroupReduction.php#186)


#### Arguments
* $id_category **mixed**



### getGroupReductionByCategoryId

    array|null GroupReductionCore::getGroupReductionByCategoryId(integer $id_category)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/GroupReduction.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/GroupReduction.php#200)


#### Arguments
* $id_category **integer**



### setProductReduction

    mixed GroupReductionCore::setProductReduction($id_product, $id_group, $id_category, $reduction)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/GroupReduction.php line 209](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/GroupReduction.php#209)


#### Arguments
* $id_product **mixed**
* $id_group **mixed**
* $id_category **mixed**
* $reduction **mixed**



### deleteProductReduction

    mixed GroupReductionCore::deleteProductReduction($id_product)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/GroupReduction.php line 231](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/GroupReduction.php#231)


#### Arguments
* $id_product **mixed**



### duplicateReduction

    mixed GroupReductionCore::duplicateReduction($id_product_old, $id_product)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/GroupReduction.php line 240](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/GroupReduction.php#240)


#### Arguments
* $id_product_old **mixed**
* $id_product **mixed**



### deleteCategory

    mixed GroupReductionCore::deleteCategory($id_category)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/GroupReduction.php line 262](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/GroupReduction.php#262)


#### Arguments
* $id_category **mixed**


