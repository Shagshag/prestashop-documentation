ContactCore
===============






* Class name: ContactCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id

    public mixed $id





* Visibility: **public**


### $name

    public string $name





* Visibility: **public**


### $email

    public string $email





* Visibility: **public**


### $description

    public string $description





* Visibility: **public**


### $customer_service

    public mixed $customer_service





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'contact', 'primary' => 'id_contact', 'multilang' => true, 'fields' => array('email' => array('type' => self::TYPE_STRING, 'validate' => 'isEmail', 'size' => 128), 'customer_service' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 32), 'description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isCleanHtml')))





* Visibility: **public**
* This property is **static**.


Methods
-------


### getContacts

    array ContactCore::getContacts(integer $id_lang)

Return available contacts



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language ID&lt;/p&gt;



### getCategoriesContacts

    array ContactCore::getCategoriesContacts()

Return available categories contacts



* Visibility: **public**
* This method is **static**.



