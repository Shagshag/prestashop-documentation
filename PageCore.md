PageCore
===============






* Class name: PageCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in classes\Page.php line 27





Properties
----------


### $id_page_type

    public mixed $id_page_type





* Visibility: **public**
* This property is defined in classes\Page.php line 29


### $id_object

    public mixed $id_object





* Visibility: **public**
* This property is defined in classes\Page.php line 30


### $name

    public mixed $name





* Visibility: **public**
* This property is defined in classes\Page.php line 32


### $definition

    public mixed $definition = array('table' => 'page', 'primary' => 'id_page', 'fields' => array('id_page_type' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_object' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId')))





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\Page.php line 37


Methods
-------


### getCurrentId

    integer PageCore::getCurrentId()





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Page.php line 49




### getPageTypeByName

    mixed PageCore::getPageTypeByName(string $name)

Return page type ID from page name



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Page.php line 91


#### Arguments
* $name **string** - &lt;p&gt;Page name (E.g. product.php)&lt;/p&gt;



### setPageViewed

    mixed PageCore::setPageViewed($id_page)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Page.php line 107


#### Arguments
* $id_page **mixed**


