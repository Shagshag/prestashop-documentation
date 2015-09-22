Class AdminAttributeGeneratorControllerCore
=====================





* Class name: AdminAttributeGeneratorControllerCore
* Parent class: [AdminController](class.AdminControllerCore)
* Source: [controllers/admin/AdminAttributeGeneratorController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributeGeneratorController.php#L32)



Properties
----------

* [$combinations](#property-$combinations)
* [$object](#property-$object)
* [$product](#property-$product)

Methods
-------
* [__construct](#method-__construct)
* [addAttribute](#method-addAttribute)
* [createCombinations](#method-createCombinations)
* [initBreadcrumbs](#method-initBreadcrumbs)
* [initContent](#method-initContent)
* [initGroupTable](#method-initGroupTable)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [postProcess](#method-postProcess)
* [processGenerate](#method-processGenerate)
* [setAttributesImpacts](#method-setAttributesImpacts)
* [setMedia](#method-setMedia)




Properties
----------


### <a name="property-$combinations"></a>$combinations

    protected mixed $combinations = array()





* Visibility: **protected**
* Source: [controllers/admin/AdminAttributeGeneratorController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributeGeneratorController.php#L34)


### <a name="property-$object"></a>$object

    public \Product $object





* Visibility: **public**
* Source: [controllers/admin/AdminAttributeGeneratorController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributeGeneratorController.php#L32)


### <a name="property-$product"></a>$product

    protected \Product $product





* Visibility: **protected**
* Source: [controllers/admin/AdminAttributeGeneratorController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributeGeneratorController.php#L37)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminAttributeGeneratorControllerCore::__construct()





* Visibility: **public**
* Source: [controllers/admin/AdminAttributeGeneratorController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributeGeneratorController.php#L39)




### <a name="method-addAttribute"></a>addAttribute

    mixed AdminAttributeGeneratorControllerCore::addAttribute($attributes, $price, $weight)





* Visibility: **protected**
* Source: [controllers/admin/AdminAttributeGeneratorController.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributeGeneratorController.php#L55)


#### Arguments
* $attributes **mixed**
* $price **mixed**
* $weight **mixed**



### <a name="method-createCombinations"></a>createCombinations

    mixed AdminAttributeGeneratorControllerCore::createCombinations($list)





* Visibility: **protected**
* This method is **static**.
* Source: [controllers/admin/AdminAttributeGeneratorController.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributeGeneratorController.php#L76)


#### Arguments
* $list **mixed**



### <a name="method-initBreadcrumbs"></a>initBreadcrumbs

    mixed AdminAttributeGeneratorControllerCore::initBreadcrumbs($tab_id, $tabs)





* Visibility: **public**
* Source: [controllers/admin/AdminAttributeGeneratorController.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributeGeneratorController.php#L223)


#### Arguments
* $tab_id **mixed**
* $tabs **mixed**



### <a name="method-initContent"></a>initContent

    mixed AdminAttributeGeneratorControllerCore::initContent()





* Visibility: **public**
* Source: [controllers/admin/AdminAttributeGeneratorController.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributeGeneratorController.php#L229)




### <a name="method-initGroupTable"></a>initGroupTable

    mixed AdminAttributeGeneratorControllerCore::initGroupTable()





* Visibility: **public**
* Source: [controllers/admin/AdminAttributeGeneratorController.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributeGeneratorController.php#L192)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminAttributeGeneratorControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* Source: [controllers/admin/AdminAttributeGeneratorController.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributeGeneratorController.php#L212)




### <a name="method-initProcess"></a>initProcess

    mixed AdminAttributeGeneratorControllerCore::initProcess()





* Visibility: **public**
* Source: [controllers/admin/AdminAttributeGeneratorController.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributeGeneratorController.php#L92)




### <a name="method-postProcess"></a>postProcess

    mixed AdminAttributeGeneratorControllerCore::postProcess()





* Visibility: **public**
* Source: [controllers/admin/AdminAttributeGeneratorController.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributeGeneratorController.php#L108)




### <a name="method-processGenerate"></a>processGenerate

    mixed AdminAttributeGeneratorControllerCore::processGenerate()





* Visibility: **public**
* Source: [controllers/admin/AdminAttributeGeneratorController.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributeGeneratorController.php#L115)




### <a name="method-setAttributesImpacts"></a>setAttributesImpacts

    mixed AdminAttributeGeneratorControllerCore::setAttributesImpacts($id_product, $tab)





* Visibility: **protected**
* This method is **static**.
* Source: [controllers/admin/AdminAttributeGeneratorController.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributeGeneratorController.php#L175)


#### Arguments
* $id_product **mixed**
* $tab **mixed**



### <a name="method-setMedia"></a>setMedia

    mixed AdminAttributeGeneratorControllerCore::setMedia()





* Visibility: **public**
* Source: [controllers/admin/AdminAttributeGeneratorController.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminAttributeGeneratorController.php#L49)



