AdminGroupsControllerCore
===============






* Class name: AdminGroupsControllerCore
* Namespace: 
* Parent class: AdminController





Properties
----------


### $object

    public \Group $object





* Visibility: **public**


Methods
-------


### __construct

    mixed AdminGroupsControllerCore::__construct()





* Visibility: **public**




### setMedia

    mixed AdminGroupsControllerCore::setMedia()





* Visibility: **public**




### initToolbar

    mixed AdminGroupsControllerCore::initToolbar()





* Visibility: **public**




### initPageHeaderToolbar

    mixed AdminGroupsControllerCore::initPageHeaderToolbar()





* Visibility: **public**




### initProcess

    mixed AdminGroupsControllerCore::initProcess()





* Visibility: **public**




### renderView

    mixed AdminGroupsControllerCore::renderView()





* Visibility: **public**




### renderCustomersList

    mixed AdminGroupsControllerCore::renderCustomersList($group)





* Visibility: **protected**


#### Arguments
* $group **mixed**



### renderForm

    mixed AdminGroupsControllerCore::renderForm()





* Visibility: **public**




### formatCategoryDiscountList

    mixed AdminGroupsControllerCore::formatCategoryDiscountList($id_group)





* Visibility: **protected**


#### Arguments
* $id_group **mixed**



### formatModuleListAuth

    mixed AdminGroupsControllerCore::formatModuleListAuth($id_group)





* Visibility: **public**


#### Arguments
* $id_group **mixed**



### processSave

    mixed AdminGroupsControllerCore::processSave()





* Visibility: **public**




### validateDiscount

    mixed AdminGroupsControllerCore::validateDiscount($reduction)





* Visibility: **protected**


#### Arguments
* $reduction **mixed**



### ajaxProcessAddCategoryReduction

    mixed AdminGroupsControllerCore::ajaxProcessAddCategoryReduction()





* Visibility: **public**




### updateRestrictions

    mixed AdminGroupsControllerCore::updateRestrictions()

Update (or create) restrictions for modules by group



* Visibility: **protected**




### updateCategoryReduction

    mixed AdminGroupsControllerCore::updateCategoryReduction()





* Visibility: **protected**




### processChangeShowPricesVal

    mixed AdminGroupsControllerCore::processChangeShowPricesVal()

Toggle show prices flag



* Visibility: **public**




### printShowPricesIcon

    string AdminGroupsControllerCore::printShowPricesIcon($id_group, $tr)

Print enable / disable icon for show prices option



* Visibility: **public**


#### Arguments
* $id_group **mixed** - &lt;p&gt;integer Group ID&lt;/p&gt;
* $tr **mixed** - &lt;p&gt;array Row data&lt;/p&gt;



### renderList

    mixed AdminGroupsControllerCore::renderList()





* Visibility: **public**




### displayEditLink

    mixed AdminGroupsControllerCore::displayEditLink($token, $id, $name)





* Visibility: **public**


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**


