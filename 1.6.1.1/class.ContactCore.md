Class ContactCore
=====================





* Class name: ContactCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Contact.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Contact.php#L27)



Properties
----------

* [$customer_service](#property-$customer_service)
* [$definition](#property-$definition)
* [$description](#property-$description)
* [$email](#property-$email)
* [$id](#property-$id)
* [$name](#property-$name)

Methods
-------
* [getCategoriesContacts](#method-getCategoriesContacts)
* [getContacts](#method-getContacts)




Properties
----------


### <a name="property-$customer_service"></a>$customer_service

    public mixed $customer_service





* Visibility: **public**
* Source: [classes/Contact.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Contact.php#L40).


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'contact', 'primary' => 'id_contact', 'multilang' => true, 'fields' => array('email' => array('type' => self::TYPE_STRING, 'validate' => 'isEmail', 'size' => 128), 'customer_service' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 32), 'description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isCleanHtml')))





* Visibility: **public**
* This property is **static**.
* Source: [classes/Contact.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Contact.php#L45).


### <a name="property-$description"></a>$description

    public string $description





* Visibility: **public**
* Source: [classes/Contact.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Contact.php#L38).


### <a name="property-$email"></a>$email

    public string $email





* Visibility: **public**
* Source: [classes/Contact.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Contact.php#L35).


### <a name="property-$id"></a>$id

    public mixed $id





* Visibility: **public**
* Source: [classes/Contact.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Contact.php#L29).


### <a name="property-$name"></a>$name

    public string $name





* Visibility: **public**
* Source: [classes/Contact.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Contact.php#L32).


Methods
-------


### <a name="method-getCategoriesContacts"></a>getCategoriesContacts

    array ContactCore::getCategoriesContacts()

Return available categories contacts



* Visibility: **public**
* This method is **static**.
* Source: [classes/Contact.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Contact.php#L84)




### <a name="method-getContacts"></a>getContacts

    array ContactCore::getContacts(integer $id_lang)

Return available contacts



* Visibility: **public**
* This method is **static**.
* Source: [classes/Contact.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Contact.php#L66)


#### Arguments
* $id_lang **integer** - Language ID


