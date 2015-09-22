Class AdminTaxesControllerCore
=====================





* Class name: AdminTaxesControllerCore
* Parent class: [AdminController](class.AdminControllerCore)
* Source: [controllers/admin/AdminTaxesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxesController.php#L30)



Properties
----------

* [$object](#property-$object)

Methods
-------
* [__construct](#method-__construct)
* [displayDeleteLink](#method-displayDeleteLink)
* [displayEnableLink](#method-displayEnableLink)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [postProcess](#method-postProcess)
* [renderForm](#method-renderForm)
* [updateOptionPsUseEcotax](#method-updateOptionPsUseEcotax)




Properties
----------


### <a name="property-$object"></a>$object

    public \Tax $object





* Visibility: **public**
* Source: [controllers/admin/AdminTaxesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxesController.php#L30)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminTaxesControllerCore::__construct()





* Visibility: **public**
* Source: [controllers/admin/AdminTaxesController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxesController.php#L32)




### <a name="method-displayDeleteLink"></a>displayDeleteLink

    string AdminTaxesControllerCore::displayDeleteLink(string|null $token, integer $id)

Display delete action link



* Visibility: **public**
* Source: [controllers/admin/AdminTaxesController.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxesController.php#L140)


#### Arguments
* $token **string|null**
* $id **integer**



### <a name="method-displayEnableLink"></a>displayEnableLink

    mixed AdminTaxesControllerCore::displayEnableLink(string $token, integer $id, integer $value, string $active, integer $id_category, integer $id_product)

Fetch the template for action enable



* Visibility: **public**
* Source: [controllers/admin/AdminTaxesController.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxesController.php#L173)


#### Arguments
* $token **string**
* $id **integer**
* $value **integer** - state enabled or not
* $active **string** - status
* $id_category **integer**
* $id_product **integer**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminTaxesControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* Source: [controllers/admin/AdminTaxesController.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxesController.php#L117)




### <a name="method-postProcess"></a>postProcess

    mixed AdminTaxesControllerCore::postProcess()





* Visibility: **public**
* Source: [controllers/admin/AdminTaxesController.php line 241](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxesController.php#L241)




### <a name="method-renderForm"></a>renderForm

    mixed AdminTaxesControllerCore::renderForm()





* Visibility: **public**
* Source: [controllers/admin/AdminTaxesController.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxesController.php#L189)




### <a name="method-updateOptionPsUseEcotax"></a>updateOptionPsUseEcotax

    mixed AdminTaxesControllerCore::updateOptionPsUseEcotax($value)





* Visibility: **public**
* Source: [controllers/admin/AdminTaxesController.php line 284](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxesController.php#L284)


#### Arguments
* $value **mixed**


