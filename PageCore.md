PageCore
===============






* Class name: PageCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id_page_type

    public mixed $id_page_type





* Visibility: **public**


### $id_object

    public mixed $id_object





* Visibility: **public**


### $name

    public mixed $name





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'page', 'primary' => 'id_page', 'fields' => array('id_page_type' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_object' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId')))





* Visibility: **public**
* This property is **static**.


Methods
-------


### getCurrentId

    integer PageCore::getCurrentId()





* Visibility: **public**
* This method is **static**.




### getPageTypeByName

    mixed PageCore::getPageTypeByName(string $name)

Return page type ID from page name



* Visibility: **public**
* This method is **static**.


#### Arguments
* $name **string** - &lt;p&gt;Page name (E.g. product.php)&lt;/p&gt;



### setPageViewed

    mixed PageCore::setPageViewed($id_page)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_page **mixed**


