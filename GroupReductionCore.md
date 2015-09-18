GroupReductionCore
===============






* Class name: GroupReductionCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id_group

    public mixed $id_group





* Visibility: **public**


### $id_category

    public mixed $id_category





* Visibility: **public**


### $reduction

    public mixed $reduction





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'group_reduction', 'primary' => 'id_group_reduction', 'fields' => array('id_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_category' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'reduction' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true)))





* Visibility: **public**
* This property is **static**.


### $reduction_cache

    protected mixed $reduction_cache = array()





* Visibility: **protected**
* This property is **static**.


Methods
-------


### add

    mixed GroupReductionCore::add($autodate, $null_values)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### update

    mixed GroupReductionCore::update($null_values)





* Visibility: **public**


#### Arguments
* $null_values **mixed**



### delete

    mixed GroupReductionCore::delete()





* Visibility: **public**




### _clearCache

    mixed GroupReductionCore::_clearCache()





* Visibility: **protected**




### _setCache

    mixed GroupReductionCore::_setCache()





* Visibility: **protected**




### _updateCache

    mixed GroupReductionCore::_updateCache()





* Visibility: **protected**




### getGroupReductions

    mixed GroupReductionCore::getGroupReductions($id_group, $id_lang)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_group **mixed**
* $id_lang **mixed**



### getValueForProduct

    mixed GroupReductionCore::getValueForProduct($id_product, $id_group)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**
* $id_group **mixed**



### doesExist

    mixed GroupReductionCore::doesExist($id_group, $id_category)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_group **mixed**
* $id_category **mixed**



### getGroupsByCategoryId

    mixed GroupReductionCore::getGroupsByCategoryId($id_category)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_category **mixed**



### getGroupByCategoryId

    array|null GroupReductionCore::getGroupByCategoryId(integer $id_category)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_category **integer**



### getGroupsReductionByCategoryId

    mixed GroupReductionCore::getGroupsReductionByCategoryId($id_category)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_category **mixed**



### getGroupReductionByCategoryId

    array|null GroupReductionCore::getGroupReductionByCategoryId(integer $id_category)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_category **integer**



### setProductReduction

    mixed GroupReductionCore::setProductReduction($id_product, $id_group, $id_category, $reduction)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**
* $id_group **mixed**
* $id_category **mixed**
* $reduction **mixed**



### deleteProductReduction

    mixed GroupReductionCore::deleteProductReduction($id_product)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**



### duplicateReduction

    mixed GroupReductionCore::duplicateReduction($id_product_old, $id_product)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product_old **mixed**
* $id_product **mixed**



### deleteCategory

    mixed GroupReductionCore::deleteCategory($id_category)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_category **mixed**


