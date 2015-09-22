ContactCore
===============






* Class name: ContactCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)

* This class is defined in [classes/Contact.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Contact.php#27)





Properties
----------


### $id

    public mixed $id





* Visibility: **public**
* This property is defined in [classes/Contact.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Contact.php#29)


### $name

    public string $name





* Visibility: **public**
* This property is defined in [classes/Contact.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Contact.php#32)


### $email

    public string $email





* Visibility: **public**
* This property is defined in [classes/Contact.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Contact.php#35)


### $description

    public string $description





* Visibility: **public**
* This property is defined in [classes/Contact.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Contact.php#38)


### $customer_service

    public mixed $customer_service





* Visibility: **public**
* This property is defined in [classes/Contact.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Contact.php#40)


### $definition

    public mixed $definition = array('table' => 'contact', 'primary' => 'id_contact', 'multilang' => true, 'fields' => array('email' => array('type' => self::TYPE_STRING, 'validate' => 'isEmail', 'size' => 128), 'customer_service' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 32), 'description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isCleanHtml')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Contact.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Contact.php#45)


Methods
-------


### getContacts

    array ContactCore::getContacts(integer $id_lang)

Return available contacts



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Contact.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Contact.php#66)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language ID&lt;/p&gt;



### getCategoriesContacts

    array ContactCore::getCategoriesContacts()

Return available categories contacts



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Contact.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Contact.php#84)



