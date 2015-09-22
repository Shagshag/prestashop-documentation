HelperOptionsCore
===============

Use this helper to generate preferences forms, with values stored in the configuration table




* Class name: HelperOptionsCore
* Namespace: 
* Parent class: [Helper](HelperCore)
* This class is defined in classes\helper\HelperOptions.php line 30





Properties
----------


### $required

    public mixed $required = false





* Visibility: **public**
* This property is defined in classes\helper\HelperOptions.php line 32


Methods
-------


### __construct

    mixed HelperOptionsCore::__construct()





* Visibility: **public**
* This method is defined in classes\helper\HelperOptions.php line 34




### generateOptions

    string HelperOptionsCore::generateOptions(array $option_list)

Generate a form for options



* Visibility: **public**
* This method is defined in classes\helper\HelperOptions.php line 46


#### Arguments
* $option_list **array**



### displayOptionTypeImage

    mixed HelperOptionsCore::displayOptionTypeImage($key, $field, $value)

Type = image



* Visibility: **public**
* This method is defined in classes\helper\HelperOptions.php line 233


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### displayOptionTypePrice

    mixed HelperOptionsCore::displayOptionTypePrice($key, $field, $value)

Type = price



* Visibility: **public**
* This method is defined in classes\helper\HelperOptions.php line 260


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### displayOptionTypeDisabled

    mixed HelperOptionsCore::displayOptionTypeDisabled($key, $field, $value)

Type = disabled



* Visibility: **public**
* This method is defined in classes\helper\HelperOptions.php line 270


#### Arguments
* $key **mixed**
* $field **mixed**
* $value **mixed**



### getOptionValue

    mixed HelperOptionsCore::getOptionValue($key, $field)





* Visibility: **public**
* This method is defined in classes\helper\HelperOptions.php line 275


#### Arguments
* $key **mixed**
* $field **mixed**


