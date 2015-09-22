AdminGroupsControllerCore
===============






* Class name: AdminGroupsControllerCore
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in [controllers/admin/AdminGroupsController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminGroupsController.php#L30)





Properties
----------

* [$object](#property-$object)

Methods
-------
* [__construct](#method-__construct)
* [setMedia](#method-setMedia)
* [initToolbar](#method-initToolbar)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [renderView](#method-renderView)
* [renderCustomersList](#method-renderCustomersList)
* [renderForm](#method-renderForm)
* [formatCategoryDiscountList](#method-formatCategoryDiscountList)
* [formatModuleListAuth](#method-formatModuleListAuth)
* [processSave](#method-processSave)
* [validateDiscount](#method-validateDiscount)
* [ajaxProcessAddCategoryReduction](#method-ajaxProcessAddCategoryReduction)
* [updateRestrictions](#method-updateRestrictions)
* [updateCategoryReduction](#method-updateCategoryReduction)
* [processChangeShowPricesVal](#method-processChangeShowPricesVal)
* [printShowPricesIcon](#method-printShowPricesIcon)
* [renderList](#method-renderList)
* [displayEditLink](#method-displayEditLink)




Properties
----------


### <a name="property-$object"></a>$object

    public \Group $object





* Visibility: **public**
* This property is defined in [controllers/admin/AdminGroupsController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminGroupsController.php#L30)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminGroupsControllerCore::__construct()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminGroupsController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminGroupsController.php#L32)




### <a name="method-setMedia"></a>setMedia

    mixed AdminGroupsControllerCore::setMedia()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminGroupsController.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminGroupsController.php#L141)




### <a name="method-initToolbar"></a>initToolbar

    mixed AdminGroupsControllerCore::initToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminGroupsController.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminGroupsController.php#L148)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminGroupsControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminGroupsController.php line 161](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminGroupsController.php#L161)




### <a name="method-initProcess"></a>initProcess

    mixed AdminGroupsControllerCore::initProcess()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminGroupsController.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminGroupsController.php#L174)




### <a name="method-renderView"></a>renderView

    mixed AdminGroupsControllerCore::renderView()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminGroupsController.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminGroupsController.php#L195)




### <a name="method-renderCustomersList"></a>renderCustomersList

    mixed AdminGroupsControllerCore::renderCustomersList($group)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminGroupsController.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminGroupsController.php#L212)


#### Arguments
* $group **mixed**



### <a name="method-renderForm"></a>renderForm

    mixed AdminGroupsControllerCore::renderForm()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminGroupsController.php line 251](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminGroupsController.php#L251)




### <a name="method-formatCategoryDiscountList"></a>formatCategoryDiscountList

    mixed AdminGroupsControllerCore::formatCategoryDiscountList($id_group)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminGroupsController.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminGroupsController.php#L360)


#### Arguments
* $id_group **mixed**



### <a name="method-formatModuleListAuth"></a>formatModuleListAuth

    mixed AdminGroupsControllerCore::formatModuleListAuth($id_group)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminGroupsController.php line 393](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminGroupsController.php#L393)


#### Arguments
* $id_group **mixed**



### <a name="method-processSave"></a>processSave

    mixed AdminGroupsControllerCore::processSave()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminGroupsController.php line 444](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminGroupsController.php#L444)




### <a name="method-validateDiscount"></a>validateDiscount

    mixed AdminGroupsControllerCore::validateDiscount($reduction)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminGroupsController.php line 456](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminGroupsController.php#L456)


#### Arguments
* $reduction **mixed**



### <a name="method-ajaxProcessAddCategoryReduction"></a>ajaxProcessAddCategoryReduction

    mixed AdminGroupsControllerCore::ajaxProcessAddCategoryReduction()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminGroupsController.php line 465](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminGroupsController.php#L465)




### <a name="method-updateRestrictions"></a>updateRestrictions

    mixed AdminGroupsControllerCore::updateRestrictions()

Update (or create) restrictions for modules by group



* Visibility: **protected**
* This method is defined in [controllers/admin/AdminGroupsController.php line 489](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminGroupsController.php#L489)




### <a name="method-updateCategoryReduction"></a>updateCategoryReduction

    mixed AdminGroupsControllerCore::updateCategoryReduction()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminGroupsController.php line 504](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminGroupsController.php#L504)




### <a name="method-processChangeShowPricesVal"></a>processChangeShowPricesVal

    mixed AdminGroupsControllerCore::processChangeShowPricesVal()

Toggle show prices flag



* Visibility: **public**
* This method is defined in [controllers/admin/AdminGroupsController.php line 540](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminGroupsController.php#L540)




### <a name="method-printShowPricesIcon"></a>printShowPricesIcon

    string AdminGroupsControllerCore::printShowPricesIcon($id_group, $tr)

Print enable / disable icon for show prices option



* Visibility: **public**
* This method is defined in [controllers/admin/AdminGroupsController.php line 561](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminGroupsController.php#L561)


#### Arguments
* $id_group **mixed** - &lt;p&gt;integer Group ID&lt;/p&gt;
* $tr **mixed** - &lt;p&gt;array Row data&lt;/p&gt;



### <a name="method-renderList"></a>renderList

    mixed AdminGroupsControllerCore::renderList()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminGroupsController.php line 572](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminGroupsController.php#L572)




### <a name="method-displayEditLink"></a>displayEditLink

    mixed AdminGroupsControllerCore::displayEditLink($token, $id, $name)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminGroupsController.php line 598](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminGroupsController.php#L598)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**


