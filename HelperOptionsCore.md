HelperOptionsCore
===============

Use this helper to generate preferences forms, with values stored in the configuration table




* Class name: HelperOptionsCore
* Namespace: 
* Parent class: Helper





Properties
----------


### $required

    public mixed $required = false





* Visibility: **public**


Methods
-------


### __construct

    mixed HelperOptionsCore::__construct()





* Visibility: **public**




### generateOptions

    string HelperOptionsCore::generateOptions(array $option_list)

Generate a form for options



* Visibility: **public**


#### Arguments
* $option_list **array**



### displayOptionTypeImage

    mixed HelperOptionsCore::displayOptionTypeImage($key, $field, $value)

Type = image



* Visibility: **public**


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### displayOptionTypePrice

    mixed HelperOptionsCore::displayOptionTypePrice($key, $field, $value)

Type = price



* Visibility: **public**


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### displayOptionTypeDisabled

    mixed HelperOptionsCore::displayOptionTypeDisabled($key, $field, $value)

Type = disabled



* Visibility: **public**


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### getOptionValue

    mixed HelperOptionsCore::getOptionValue($key, $field)





* Visibility: **public**


#### Arguments
* $key **mixed**
* $field **mixed**


