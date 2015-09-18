WebserviceRequestCore
===============






* Class name: WebserviceRequestCore
* Namespace: 



Constants
----------


### HTTP_GET

    const HTTP_GET = 1





### HTTP_POST

    const HTTP_POST = 2





### HTTP_PUT

    const HTTP_PUT = 4





Properties
----------


### $_available_languages

    protected mixed $_available_languages = null





* Visibility: **protected**


### $errors

    public array $errors = array()

Errors triggered at execution



* Visibility: **public**


### $_outputEnabled

    protected boolean $_outputEnabled = true

Set if return should display content or not



* Visibility: **protected**


### $objectSpecificManagement

    protected \WebserviceSpecificManagementImages $objectSpecificManagement = false

Set if the management is specific or if it is classic (entity management)



* Visibility: **protected**


### $wsUrl

    public string $wsUrl

Base PrestaShop webservice URL



* Visibility: **public**


### $_docUrl

    protected string $_docUrl = 'http://doc.prestashop.com/display/PS16/Using+the+PrestaShop+Web+Service'

PrestaShop Webservice Documentation URL



* Visibility: **protected**


### $_authenticated

    protected boolean $_authenticated = false

Set if the authentication key was checked



* Visibility: **protected**


### $method

    public string $method

HTTP Method to support



* Visibility: **public**


### $urlSegment

    public array $urlSegment = array()

The segment of the URL



* Visibility: **public**


### $urlFragments

    public array $urlFragments = array()

The segment list of the URL after the "api" segment



* Visibility: **public**


### $_startTime

    protected integer $_startTime

The time in microseconds of the start of the execution of the web service request



* Visibility: **protected**


### $resourceList

    public array $resourceList

The list of each resources manageable via web service



* Visibility: **public**


### $resourceConfiguration

    public array $resourceConfiguration

The configuration parameters of the current resource



* Visibility: **public**


### $keyPermissions

    public array $keyPermissions

The permissions for the current key



* Visibility: **public**


### $specificOutput

    protected string $specificOutput = ''

The XML string to display if web service call succeed



* Visibility: **protected**


### $objects

    public array $objects

The list of objects to display



* Visibility: **public**


### $_object

    protected \ObjectModel $_object

The current object to support, it extends the PrestaShop ObjectModel



* Visibility: **protected**


### $schemaToDisplay

    public string $schemaToDisplay

The schema to display.

If null, no schema have to be displayed and normal management has to be performed

* Visibility: **public**


### $fieldsToDisplay

    public string $fieldsToDisplay = 'minimum'

The fields to display. These fields will be displayed when retrieving objects



* Visibility: **public**


### $_inputXml

    protected string $_inputXml

If we are in PUT or POST case, we use this attribute to store the xml string value during process



* Visibility: **protected**


### $_instance

    protected \WebserviceRequest $_instance

Object instance for singleton



* Visibility: **protected**
* This property is **static**.


### $_key

    protected string $_key

Key used for authentication



* Visibility: **protected**


### $depth

    public integer $depth

This is used to have a deeper tree diagram.



* Visibility: **public**


### $outputFormat

    protected string $outputFormat = 'xml'

Name of the output format



* Visibility: **protected**


### $objOutput

    protected \WebserviceOutputBuilder $objOutput

The object to build the output.



* Visibility: **protected**


### $ws_current_classname

    public string $ws_current_classname

Save the class name for override used in getInstance()



* Visibility: **public**
* This property is **static**.


### $shopIDs

    public mixed $shopIDs





* Visibility: **public**
* This property is **static**.


Methods
-------


### getOutputEnabled

    mixed WebserviceRequestCore::getOutputEnabled()





* Visibility: **public**




### setOutputEnabled

    mixed WebserviceRequestCore::setOutputEnabled($bool)





* Visibility: **public**


#### Arguments
* $bool **mixed**



### getInstance

    object WebserviceRequestCore::getInstance()

Get WebserviceRequest object instance (Singleton)



* Visibility: **public**
* This method is **static**.




### getOutputObject

    mixed WebserviceRequestCore::getOutputObject($type)





* Visibility: **protected**


#### Arguments
* $type **mixed**



### getResources

    mixed WebserviceRequestCore::getResources()





* Visibility: **public**
* This method is **static**.




### getPriceForProduct

    array WebserviceRequestCore::getPriceForProduct($field, $entity_object, $ws_params)

This method is used for calculate the price for products on the output details



* Visibility: **public**


#### Arguments
* $field **mixed**
* $entity_object **mixed**
* $ws_params **mixed**



### specificPriceForProduct

    array WebserviceRequestCore::specificPriceForProduct($entity_object, array $parameters)

This method is used for calculate the price for products on a virtual fields



* Visibility: **public**


#### Arguments
* $entity_object **mixed**
* $parameters **array**



### specificPriceCalculation

    mixed WebserviceRequestCore::specificPriceCalculation($parameters)





* Visibility: **public**


#### Arguments
* $parameters **mixed**



### specificPriceForCombination

    array WebserviceRequestCore::specificPriceForCombination($entity_object, array $parameters)

This method is used for calculate the price for products on a virtual fields



* Visibility: **public**


#### Arguments
* $entity_object **mixed**
* $parameters **array**



### fetch

    array WebserviceRequestCore::fetch(string $key, string $method, string $url, string $params, $bad_class_name, string $inputXml)

Start Webservice request
	Check webservice activation
	Check autentication
	Check resource
	Check HTTP Method
	Execute the action
	Display the result



* Visibility: **public**


#### Arguments
* $key **string**
* $method **string**
* $url **string**
* $params **string**
* $bad_class_name **mixed**
* $inputXml **string**



### webserviceChecks

    mixed WebserviceRequestCore::webserviceChecks()





* Visibility: **protected**




### setError

    void WebserviceRequestCore::setError(integer $status, string $label, integer $code)

Set a webservice error



* Visibility: **public**


#### Arguments
* $status **integer**
* $label **string**
* $code **integer**



### setErrorDidYouMean

    void WebserviceRequestCore::setErrorDidYouMean(integer $num, string $label, array $value, $available_values, integer $code)

Set a webservice error and propose a new value near from the available values



* Visibility: **public**


#### Arguments
* $num **integer**
* $label **string**
* $value **array**
* $available_values **mixed**
* $code **integer**



### getClosest

    string WebserviceRequestCore::getClosest(string $input, array $words)

Return the nearest value picked in the values list



* Visibility: **protected**


#### Arguments
* $input **string**
* $words **array**



### webserviceErrorHandler

    boolean WebserviceRequestCore::webserviceErrorHandler(string $errno, array $errstr, array $errfile, array $errline)

Used to replace the default PHP error handler, in order to display PHP errors in a XML format



* Visibility: **public**


#### Arguments
* $errno **string** - &lt;p&gt;contains the level of the error raised, as an integer&lt;/p&gt;
* $errstr **array** - &lt;p&gt;contains the error message, as a string&lt;/p&gt;
* $errfile **array** - &lt;p&gt;errfile, which contains the filename that the error was raised in, as a string&lt;/p&gt;
* $errline **array** - &lt;p&gt;errline, which contains the line number the error was raised at, as an integer&lt;/p&gt;



### hasErrors

    boolean WebserviceRequestCore::hasErrors()

Check if there is one or more error



* Visibility: **protected**




### authenticate

    boolean WebserviceRequestCore::authenticate()

Check request authentication



* Visibility: **protected**




### isActivated

    boolean WebserviceRequestCore::isActivated()

Check webservice activation



* Visibility: **protected**




### shopHasRight

    mixed WebserviceRequestCore::shopHasRight($key)





* Visibility: **protected**


#### Arguments
* $key **mixed**



### shopExists

    mixed WebserviceRequestCore::shopExists($params)





* Visibility: **protected**


#### Arguments
* $params **mixed**



### groupShopExists

    mixed WebserviceRequestCore::groupShopExists($params)





* Visibility: **protected**


#### Arguments
* $params **mixed**



### checkHTTPMethod

    boolean WebserviceRequestCore::checkHTTPMethod()

Check HTTP method



* Visibility: **protected**




### checkResource

    boolean WebserviceRequestCore::checkResource()

Check resource validity



* Visibility: **protected**




### setObjects

    mixed WebserviceRequestCore::setObjects()





* Visibility: **protected**




### parseDisplayFields

    mixed WebserviceRequestCore::parseDisplayFields($str)





* Visibility: **protected**


#### Arguments
* $str **mixed**



### setFieldsToDisplay

    mixed WebserviceRequestCore::setFieldsToDisplay()





* Visibility: **public**




### manageFilters

    mixed WebserviceRequestCore::manageFilters()





* Visibility: **protected**




### getFilteredObjectList

    mixed WebserviceRequestCore::getFilteredObjectList()





* Visibility: **public**




### getFilteredObjectDetails

    mixed WebserviceRequestCore::getFilteredObjectDetails()





* Visibility: **public**




### executeEntityGetAndHead

    boolean WebserviceRequestCore::executeEntityGetAndHead()

Execute GET and HEAD requests

Build filter
Build fields display
Build sort
Build limit

* Visibility: **public**




### executeEntityPost

    boolean WebserviceRequestCore::executeEntityPost()

Execute POST method on a PrestaShop entity



* Visibility: **protected**




### executeEntityPut

    boolean WebserviceRequestCore::executeEntityPut()

Execute PUT method on a PrestaShop entity



* Visibility: **protected**




### executeEntityDelete

    boolean WebserviceRequestCore::executeEntityDelete()

Execute DELETE method on a PrestaShop entity



* Visibility: **protected**




### saveEntityFromXml

    boolean WebserviceRequestCore::saveEntityFromXml(integer $successReturnCode)

save Entity Object from XML



* Visibility: **protected**


#### Arguments
* $successReturnCode **integer**



### getSQLRetrieveFilter

    string WebserviceRequestCore::getSQLRetrieveFilter(string $sqlId, string $filterValue, string $tableAlias)

get SQL retrieve Filter



* Visibility: **protected**


#### Arguments
* $sqlId **string**
* $filterValue **string**
* $tableAlias **string** - &lt;p&gt;= &#039;main.&#039;&lt;/p&gt;



### filterLanguage

    mixed WebserviceRequestCore::filterLanguage()





* Visibility: **public**




### returnOutput

    array WebserviceRequestCore::returnOutput()

Thanks to the (WebserviceOutputBuilder) WebserviceKey::objOutput
Method build the output depend on the WebserviceRequest::outputFormat
and set HTTP header parameters.



* Visibility: **protected**




### getallheaders

    mixed WebserviceRequestCore::getallheaders()





* Visibility: **public**
* This method is **static**.



