WebserviceRequestCore
===============






* Class name: WebserviceRequestCore
* Namespace: 
* This class is defined in classes\webservice\WebserviceRequest.php line 27



Constants
----------


### HTTP_GET

    const HTTP_GET = 1



* This constant is defined in classes\webservice\WebserviceRequest.php line 29


### HTTP_POST

    const HTTP_POST = 2



* This constant is defined in classes\webservice\WebserviceRequest.php line 30


### HTTP_PUT

    const HTTP_PUT = 4



* This constant is defined in classes\webservice\WebserviceRequest.php line 31


Properties
----------


### $_available_languages

    protected mixed $_available_languages = null





* Visibility: **protected**
* This property is defined in classes\webservice\WebserviceRequest.php line 33


### $errors

    public array $errors = array()

Errors triggered at execution



* Visibility: **public**
* This property is defined in classes\webservice\WebserviceRequest.php line 38


### $_outputEnabled

    protected boolean $_outputEnabled = true

Set if return should display content or not



* Visibility: **protected**
* This property is defined in classes\webservice\WebserviceRequest.php line 44


### $objectSpecificManagement

    protected \WebserviceSpecificManagementImages $objectSpecificManagement = false

Set if the management is specific or if it is classic (entity management)



* Visibility: **protected**
* This property is defined in classes\webservice\WebserviceRequest.php line 50


### $wsUrl

    public string $wsUrl

Base PrestaShop webservice URL



* Visibility: **public**
* This property is defined in classes\webservice\WebserviceRequest.php line 56


### $_docUrl

    protected string $_docUrl = 'http://doc.prestashop.com/display/PS16/Using+the+PrestaShop+Web+Service'

PrestaShop Webservice Documentation URL



* Visibility: **protected**
* This property is defined in classes\webservice\WebserviceRequest.php line 62


### $_authenticated

    protected boolean $_authenticated = false

Set if the authentication key was checked



* Visibility: **protected**
* This property is defined in classes\webservice\WebserviceRequest.php line 68


### $method

    public string $method

HTTP Method to support



* Visibility: **public**
* This property is defined in classes\webservice\WebserviceRequest.php line 74


### $urlSegment

    public array $urlSegment = array()

The segment of the URL



* Visibility: **public**
* This property is defined in classes\webservice\WebserviceRequest.php line 80


### $urlFragments

    public array $urlFragments = array()

The segment list of the URL after the "api" segment



* Visibility: **public**
* This property is defined in classes\webservice\WebserviceRequest.php line 86


### $_startTime

    protected integer $_startTime

The time in microseconds of the start of the execution of the web service request



* Visibility: **protected**
* This property is defined in classes\webservice\WebserviceRequest.php line 92


### $resourceList

    public array $resourceList

The list of each resources manageable via web service



* Visibility: **public**
* This property is defined in classes\webservice\WebserviceRequest.php line 98


### $resourceConfiguration

    public array $resourceConfiguration

The configuration parameters of the current resource



* Visibility: **public**
* This property is defined in classes\webservice\WebserviceRequest.php line 104


### $keyPermissions

    public array $keyPermissions

The permissions for the current key



* Visibility: **public**
* This property is defined in classes\webservice\WebserviceRequest.php line 110


### $specificOutput

    protected string $specificOutput = ''

The XML string to display if web service call succeed



* Visibility: **protected**
* This property is defined in classes\webservice\WebserviceRequest.php line 116


### $objects

    public array $objects

The list of objects to display



* Visibility: **public**
* This property is defined in classes\webservice\WebserviceRequest.php line 122


### $_object

    protected \ObjectModel $_object

The current object to support, it extends the PrestaShop ObjectModel



* Visibility: **protected**
* This property is defined in classes\webservice\WebserviceRequest.php line 128


### $schemaToDisplay

    public string $schemaToDisplay

The schema to display.

If null, no schema have to be displayed and normal management has to be performed

* Visibility: **public**
* This property is defined in classes\webservice\WebserviceRequest.php line 135


### $fieldsToDisplay

    public string $fieldsToDisplay = 'minimum'

The fields to display. These fields will be displayed when retrieving objects



* Visibility: **public**
* This property is defined in classes\webservice\WebserviceRequest.php line 141


### $_inputXml

    protected string $_inputXml

If we are in PUT or POST case, we use this attribute to store the xml string value during process



* Visibility: **protected**
* This property is defined in classes\webservice\WebserviceRequest.php line 147


### $_instance

    protected \WebserviceRequest $_instance

Object instance for singleton



* Visibility: **protected**
* This property is **static**.
* This property is defined in classes\webservice\WebserviceRequest.php line 153


### $_key

    protected string $_key

Key used for authentication



* Visibility: **protected**
* This property is defined in classes\webservice\WebserviceRequest.php line 159


### $depth

    public integer $depth

This is used to have a deeper tree diagram.



* Visibility: **public**
* This property is defined in classes\webservice\WebserviceRequest.php line 165


### $outputFormat

    protected string $outputFormat = 'xml'

Name of the output format



* Visibility: **protected**
* This property is defined in classes\webservice\WebserviceRequest.php line 171


### $objOutput

    protected \WebserviceOutputBuilder $objOutput

The object to build the output.



* Visibility: **protected**
* This property is defined in classes\webservice\WebserviceRequest.php line 177


### $ws_current_classname

    public string $ws_current_classname

Save the class name for override used in getInstance()



* Visibility: **public**
* This property is **static**.
* This property is defined in classes\webservice\WebserviceRequest.php line 183


### $shopIDs

    public mixed $shopIDs





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\webservice\WebserviceRequest.php line 186


Methods
-------


### getOutputEnabled

    mixed WebserviceRequestCore::getOutputEnabled()





* Visibility: **public**
* This method is defined in classes\webservice\WebserviceRequest.php line 189




### setOutputEnabled

    mixed WebserviceRequestCore::setOutputEnabled($bool)





* Visibility: **public**
* This method is defined in classes\webservice\WebserviceRequest.php line 194


#### Arguments
* $bool **mixed**



### getInstance

    object WebserviceRequestCore::getInstance()

Get WebserviceRequest object instance (Singleton)



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\webservice\WebserviceRequest.php line 207




### getOutputObject

    mixed WebserviceRequestCore::getOutputObject($type)





* Visibility: **protected**
* This method is defined in classes\webservice\WebserviceRequest.php line 228


#### Arguments
* $type **mixed**



### getResources

    mixed WebserviceRequestCore::getResources()





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\webservice\WebserviceRequest.php line 255




### getPriceForProduct

    array WebserviceRequestCore::getPriceForProduct($field, $entity_object, $ws_params)

This method is used for calculate the price for products on the output details



* Visibility: **public**
* This method is defined in classes\webservice\WebserviceRequest.php line 340


#### Arguments
* $field **mixed**
* $entity_object **mixed**
* $ws_params **mixed**



### specificPriceForProduct

    array WebserviceRequestCore::specificPriceForProduct($entity_object, array $parameters)

This method is used for calculate the price for products on a virtual fields



* Visibility: **public**
* This method is defined in classes\webservice\WebserviceRequest.php line 357


#### Arguments
* $entity_object **mixed**
* $parameters **array**



### specificPriceCalculation

    mixed WebserviceRequestCore::specificPriceCalculation($parameters)





* Visibility: **public**
* This method is defined in classes\webservice\WebserviceRequest.php line 366


#### Arguments
* $parameters **mixed**



### specificPriceForCombination

    array WebserviceRequestCore::specificPriceForCombination($entity_object, array $parameters)

This method is used for calculate the price for products on a virtual fields



* Visibility: **public**
* This method is defined in classes\webservice\WebserviceRequest.php line 398


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
* This method is defined in classes\webservice\WebserviceRequest.php line 425


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
* This method is defined in classes\webservice\WebserviceRequest.php line 566




### setError

    void WebserviceRequestCore::setError(integer $status, string $label, integer $code)

Set a webservice error



* Visibility: **public**
* This method is defined in classes\webservice\WebserviceRequest.php line 579


#### Arguments
* $status **integer**
* $label **string**
* $code **integer**



### setErrorDidYouMean

    void WebserviceRequestCore::setErrorDidYouMean(integer $num, string $label, array $value, $available_values, integer $code)

Set a webservice error and propose a new value near from the available values



* Visibility: **public**
* This method is defined in classes\webservice\WebserviceRequest.php line 601


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
* This method is defined in classes\webservice\WebserviceRequest.php line 613


#### Arguments
* $input **string**
* $words **array**



### webserviceErrorHandler

    boolean WebserviceRequestCore::webserviceErrorHandler(string $errno, array $errstr, array $errfile, array $errline)

Used to replace the default PHP error handler, in order to display PHP errors in a XML format



* Visibility: **public**
* This method is defined in classes\webservice\WebserviceRequest.php line 640


#### Arguments
* $errno **string** - &lt;p&gt;contains the level of the error raised, as an integer&lt;/p&gt;
* $errstr **array** - &lt;p&gt;contains the error message, as a string&lt;/p&gt;
* $errfile **array** - &lt;p&gt;errfile, which contains the filename that the error was raised in, as a string&lt;/p&gt;
* $errline **array** - &lt;p&gt;errline, which contains the line number the error was raised at, as an integer&lt;/p&gt;



### hasErrors

    boolean WebserviceRequestCore::hasErrors()

Check if there is one or more error



* Visibility: **protected**
* This method is defined in classes\webservice\WebserviceRequest.php line 716




### authenticate

    boolean WebserviceRequestCore::authenticate()

Check request authentication



* Visibility: **protected**
* This method is defined in classes\webservice\WebserviceRequest.php line 726




### isActivated

    boolean WebserviceRequestCore::isActivated()

Check webservice activation



* Visibility: **protected**
* This method is defined in classes\webservice\WebserviceRequest.php line 765




### shopHasRight

    mixed WebserviceRequestCore::shopHasRight($key)





* Visibility: **protected**
* This method is defined in classes\webservice\WebserviceRequest.php line 774


#### Arguments
* $key **mixed**



### shopExists

    mixed WebserviceRequestCore::shopExists($params)





* Visibility: **protected**
* This method is defined in classes\webservice\WebserviceRequest.php line 791


#### Arguments
* $params **mixed**



### groupShopExists

    mixed WebserviceRequestCore::groupShopExists($params)





* Visibility: **protected**
* This method is defined in classes\webservice\WebserviceRequest.php line 815


#### Arguments
* $params **mixed**



### checkHTTPMethod

    boolean WebserviceRequestCore::checkHTTPMethod()

Check HTTP method



* Visibility: **protected**
* This method is defined in classes\webservice\WebserviceRequest.php line 835




### checkResource

    boolean WebserviceRequestCore::checkResource()

Check resource validity



* Visibility: **protected**
* This method is defined in classes\webservice\WebserviceRequest.php line 854




### setObjects

    mixed WebserviceRequestCore::setObjects()





* Visibility: **protected**
* This method is defined in classes\webservice\WebserviceRequest.php line 873




### parseDisplayFields

    mixed WebserviceRequestCore::parseDisplayFields($str)





* Visibility: **protected**
* This method is defined in classes\webservice\WebserviceRequest.php line 903


#### Arguments
* $str **mixed**



### setFieldsToDisplay

    mixed WebserviceRequestCore::setFieldsToDisplay()





* Visibility: **public**
* This method is defined in classes\webservice\WebserviceRequest.php line 946




### manageFilters

    mixed WebserviceRequestCore::manageFilters()





* Visibility: **protected**
* This method is defined in classes\webservice\WebserviceRequest.php line 989




### getFilteredObjectList

    mixed WebserviceRequestCore::getFilteredObjectList()





* Visibility: **public**
* This method is defined in classes\webservice\WebserviceRequest.php line 1178




### getFilteredObjectDetails

    mixed WebserviceRequestCore::getFilteredObjectDetails()





* Visibility: **public**
* This method is defined in classes\webservice\WebserviceRequest.php line 1210




### executeEntityGetAndHead

    boolean WebserviceRequestCore::executeEntityGetAndHead()

Execute GET and HEAD requests

Build filter
Build fields display
Build sort
Build limit

* Visibility: **public**
* This method is defined in classes\webservice\WebserviceRequest.php line 1266




### executeEntityPost

    boolean WebserviceRequestCore::executeEntityPost()

Execute POST method on a PrestaShop entity



* Visibility: **protected**
* This method is defined in classes\webservice\WebserviceRequest.php line 1289




### executeEntityPut

    boolean WebserviceRequestCore::executeEntityPut()

Execute PUT method on a PrestaShop entity



* Visibility: **protected**
* This method is defined in classes\webservice\WebserviceRequest.php line 1299




### executeEntityDelete

    boolean WebserviceRequestCore::executeEntityDelete()

Execute DELETE method on a PrestaShop entity



* Visibility: **protected**
* This method is defined in classes\webservice\WebserviceRequest.php line 1309




### saveEntityFromXml

    boolean WebserviceRequestCore::saveEntityFromXml(integer $successReturnCode)

save Entity Object from XML



* Visibility: **protected**
* This method is defined in classes\webservice\WebserviceRequest.php line 1364


#### Arguments
* $successReturnCode **integer**



### getSQLRetrieveFilter

    string WebserviceRequestCore::getSQLRetrieveFilter(string $sqlId, string $filterValue, string $tableAlias)

get SQL retrieve Filter



* Visibility: **protected**
* This method is defined in classes\webservice\WebserviceRequest.php line 1538


#### Arguments
* $sqlId **string**
* $filterValue **string**
* $tableAlias **string** - &lt;p&gt;= &#039;main.&#039;&lt;/p&gt;



### filterLanguage

    mixed WebserviceRequestCore::filterLanguage()





* Visibility: **public**
* This method is defined in classes\webservice\WebserviceRequest.php line 1576




### returnOutput

    array WebserviceRequestCore::returnOutput()

Thanks to the (WebserviceOutputBuilder) WebserviceKey::objOutput
Method build the output depend on the WebserviceRequest::outputFormat
and set HTTP header parameters.



* Visibility: **protected**
* This method is defined in classes\webservice\WebserviceRequest.php line 1636




### getallheaders

    mixed WebserviceRequestCore::getallheaders()





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\webservice\WebserviceRequest.php line 1733



