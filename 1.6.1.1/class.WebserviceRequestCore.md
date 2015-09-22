Class WebserviceRequestCore
=====================





* Class name: WebserviceRequestCore
* Source: [classes/webservice/WebserviceRequest.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L27)

Constants
----------

* [HTTP_GET](#constant-HTTP_GET)
* [HTTP_POST](#constant-HTTP_POST)
* [HTTP_PUT](#constant-HTTP_PUT)

Properties
----------

* [$_authenticated](#property-$_authenticated)
* [$_available_languages](#property-$_available_languages)
* [$_docUrl](#property-$_docUrl)
* [$_inputXml](#property-$_inputXml)
* [$_instance](#property-$_instance)
* [$_key](#property-$_key)
* [$_object](#property-$_object)
* [$_outputEnabled](#property-$_outputEnabled)
* [$_startTime](#property-$_startTime)
* [$depth](#property-$depth)
* [$errors](#property-$errors)
* [$fieldsToDisplay](#property-$fieldsToDisplay)
* [$keyPermissions](#property-$keyPermissions)
* [$method](#property-$method)
* [$objOutput](#property-$objOutput)
* [$objectSpecificManagement](#property-$objectSpecificManagement)
* [$objects](#property-$objects)
* [$outputFormat](#property-$outputFormat)
* [$resourceConfiguration](#property-$resourceConfiguration)
* [$resourceList](#property-$resourceList)
* [$schemaToDisplay](#property-$schemaToDisplay)
* [$shopIDs](#property-$shopIDs)
* [$specificOutput](#property-$specificOutput)
* [$urlFragments](#property-$urlFragments)
* [$urlSegment](#property-$urlSegment)
* [$wsUrl](#property-$wsUrl)
* [$ws_current_classname](#property-$ws_current_classname)

Methods
-------
* [authenticate](#method-authenticate)
* [checkHTTPMethod](#method-checkHTTPMethod)
* [checkResource](#method-checkResource)
* [executeEntityDelete](#method-executeEntityDelete)
* [executeEntityGetAndHead](#method-executeEntityGetAndHead)
* [executeEntityPost](#method-executeEntityPost)
* [executeEntityPut](#method-executeEntityPut)
* [fetch](#method-fetch)
* [filterLanguage](#method-filterLanguage)
* [getClosest](#method-getClosest)
* [getFilteredObjectDetails](#method-getFilteredObjectDetails)
* [getFilteredObjectList](#method-getFilteredObjectList)
* [getInstance](#method-getInstance)
* [getOutputEnabled](#method-getOutputEnabled)
* [getOutputObject](#method-getOutputObject)
* [getPriceForProduct](#method-getPriceForProduct)
* [getResources](#method-getResources)
* [getSQLRetrieveFilter](#method-getSQLRetrieveFilter)
* [getallheaders](#method-getallheaders)
* [groupShopExists](#method-groupShopExists)
* [hasErrors](#method-hasErrors)
* [isActivated](#method-isActivated)
* [manageFilters](#method-manageFilters)
* [parseDisplayFields](#method-parseDisplayFields)
* [returnOutput](#method-returnOutput)
* [saveEntityFromXml](#method-saveEntityFromXml)
* [setError](#method-setError)
* [setErrorDidYouMean](#method-setErrorDidYouMean)
* [setFieldsToDisplay](#method-setFieldsToDisplay)
* [setObjects](#method-setObjects)
* [setOutputEnabled](#method-setOutputEnabled)
* [shopExists](#method-shopExists)
* [shopHasRight](#method-shopHasRight)
* [specificPriceCalculation](#method-specificPriceCalculation)
* [specificPriceForCombination](#method-specificPriceForCombination)
* [specificPriceForProduct](#method-specificPriceForProduct)
* [webserviceChecks](#method-webserviceChecks)
* [webserviceErrorHandler](#method-webserviceErrorHandler)


Constants
----------


### <a name="constant-HTTP_GET"></a>HTTP_GET

    const HTTP_GET = 1



* Source: [classes/webservice/WebserviceRequest.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L29)


### <a name="constant-HTTP_POST"></a>HTTP_POST

    const HTTP_POST = 2



* Source: [classes/webservice/WebserviceRequest.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L30)


### <a name="constant-HTTP_PUT"></a>HTTP_PUT

    const HTTP_PUT = 4



* Source: [classes/webservice/WebserviceRequest.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L31)


Properties
----------


### <a name="property-$_authenticated"></a>$_authenticated

    protected boolean $_authenticated = false

Set if the authentication key was checked



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L68)


### <a name="property-$_available_languages"></a>$_available_languages

    protected mixed $_available_languages = null





* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L33)


### <a name="property-$_docUrl"></a>$_docUrl

    protected string $_docUrl = 'http://doc.prestashop.com/display/PS16/Using+the+PrestaShop+Web+Service'

PrestaShop Webservice Documentation URL



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L62)


### <a name="property-$_inputXml"></a>$_inputXml

    protected string $_inputXml

If we are in PUT or POST case, we use this attribute to store the xml string value during process



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L147)


### <a name="property-$_instance"></a>$_instance

    protected \WebserviceRequest $_instance

Object instance for singleton



* Visibility: **protected**
* This property is **static**.
* Source: [classes/webservice/WebserviceRequest.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L153)


### <a name="property-$_key"></a>$_key

    protected string $_key

Key used for authentication



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L159)


### <a name="property-$_object"></a>$_object

    protected \ObjectModel $_object

The current object to support, it extends the PrestaShop ObjectModel



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L128)


### <a name="property-$_outputEnabled"></a>$_outputEnabled

    protected boolean $_outputEnabled = true

Set if return should display content or not



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L44)


### <a name="property-$_startTime"></a>$_startTime

    protected integer $_startTime

The time in microseconds of the start of the execution of the web service request



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L92)


### <a name="property-$depth"></a>$depth

    public integer $depth

This is used to have a deeper tree diagram.



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L165)


### <a name="property-$errors"></a>$errors

    public array $errors = array()

Errors triggered at execution



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L38)


### <a name="property-$fieldsToDisplay"></a>$fieldsToDisplay

    public string $fieldsToDisplay = 'minimum'

The fields to display. These fields will be displayed when retrieving objects



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L141)


### <a name="property-$keyPermissions"></a>$keyPermissions

    public array $keyPermissions

The permissions for the current key



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L110)


### <a name="property-$method"></a>$method

    public string $method

HTTP Method to support



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L74)


### <a name="property-$objOutput"></a>$objOutput

    protected \WebserviceOutputBuilder $objOutput

The object to build the output.



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 177](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L177)


### <a name="property-$objectSpecificManagement"></a>$objectSpecificManagement

    protected \WebserviceSpecificManagementImages $objectSpecificManagement = false

Set if the management is specific or if it is classic (entity management)



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L50)


### <a name="property-$objects"></a>$objects

    public array $objects

The list of objects to display



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L122)


### <a name="property-$outputFormat"></a>$outputFormat

    protected string $outputFormat = 'xml'

Name of the output format



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L171)


### <a name="property-$resourceConfiguration"></a>$resourceConfiguration

    public array $resourceConfiguration

The configuration parameters of the current resource



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L104)


### <a name="property-$resourceList"></a>$resourceList

    public array $resourceList

The list of each resources manageable via web service



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L98)


### <a name="property-$schemaToDisplay"></a>$schemaToDisplay

    public string $schemaToDisplay

The schema to display.

If null, no schema have to be displayed and normal management has to be performed

* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L135)


### <a name="property-$shopIDs"></a>$shopIDs

    public mixed $shopIDs





* Visibility: **public**
* This property is **static**.
* Source: [classes/webservice/WebserviceRequest.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L186)


### <a name="property-$specificOutput"></a>$specificOutput

    protected string $specificOutput = ''

The XML string to display if web service call succeed



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L116)


### <a name="property-$urlFragments"></a>$urlFragments

    public array $urlFragments = array()

The segment list of the URL after the "api" segment



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L86)


### <a name="property-$urlSegment"></a>$urlSegment

    public array $urlSegment = array()

The segment of the URL



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L80)


### <a name="property-$wsUrl"></a>$wsUrl

    public string $wsUrl

Base PrestaShop webservice URL



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L56)


### <a name="property-$ws_current_classname"></a>$ws_current_classname

    public string $ws_current_classname

Save the class name for override used in getInstance()



* Visibility: **public**
* This property is **static**.
* Source: [classes/webservice/WebserviceRequest.php line 183](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L183)


Methods
-------


### <a name="method-authenticate"></a>authenticate

    boolean WebserviceRequestCore::authenticate()

Check request authentication



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 726](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L726)




### <a name="method-checkHTTPMethod"></a>checkHTTPMethod

    boolean WebserviceRequestCore::checkHTTPMethod()

Check HTTP method



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 835](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L835)




### <a name="method-checkResource"></a>checkResource

    boolean WebserviceRequestCore::checkResource()

Check resource validity



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 854](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L854)




### <a name="method-executeEntityDelete"></a>executeEntityDelete

    boolean WebserviceRequestCore::executeEntityDelete()

Execute DELETE method on a PrestaShop entity



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 1309](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L1309)




### <a name="method-executeEntityGetAndHead"></a>executeEntityGetAndHead

    boolean WebserviceRequestCore::executeEntityGetAndHead()

Execute GET and HEAD requests

Build filter
Build fields display
Build sort
Build limit

* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 1266](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L1266)




### <a name="method-executeEntityPost"></a>executeEntityPost

    boolean WebserviceRequestCore::executeEntityPost()

Execute POST method on a PrestaShop entity



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 1289](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L1289)




### <a name="method-executeEntityPut"></a>executeEntityPut

    boolean WebserviceRequestCore::executeEntityPut()

Execute PUT method on a PrestaShop entity



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 1299](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L1299)




### <a name="method-fetch"></a>fetch

    array WebserviceRequestCore::fetch(string $key, string $method, string $url, string $params, $bad_class_name, string $inputXml)

Start Webservice request
	Check webservice activation
	Check autentication
	Check resource
	Check HTTP Method
	Execute the action
	Display the result



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 425](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L425)


#### Arguments
* $key **string**
* $method **string**
* $url **string**
* $params **string**
* $bad_class_name **mixed**
* $inputXml **string**



### <a name="method-filterLanguage"></a>filterLanguage

    mixed WebserviceRequestCore::filterLanguage()





* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 1576](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L1576)




### <a name="method-getClosest"></a>getClosest

    string WebserviceRequestCore::getClosest(string $input, array $words)

Return the nearest value picked in the values list



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 613](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L613)


#### Arguments
* $input **string**
* $words **array**



### <a name="method-getFilteredObjectDetails"></a>getFilteredObjectDetails

    mixed WebserviceRequestCore::getFilteredObjectDetails()





* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 1210](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L1210)




### <a name="method-getFilteredObjectList"></a>getFilteredObjectList

    mixed WebserviceRequestCore::getFilteredObjectList()





* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 1178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L1178)




### <a name="method-getInstance"></a>getInstance

    object WebserviceRequestCore::getInstance()

Get WebserviceRequest object instance (Singleton)



* Visibility: **public**
* This method is **static**.
* Source: [classes/webservice/WebserviceRequest.php line 207](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L207)




### <a name="method-getOutputEnabled"></a>getOutputEnabled

    mixed WebserviceRequestCore::getOutputEnabled()





* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L189)




### <a name="method-getOutputObject"></a>getOutputObject

    mixed WebserviceRequestCore::getOutputObject($type)





* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L228)


#### Arguments
* $type **mixed**



### <a name="method-getPriceForProduct"></a>getPriceForProduct

    array WebserviceRequestCore::getPriceForProduct($field, $entity_object, $ws_params)

This method is used for calculate the price for products on the output details



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 340](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L340)


#### Arguments
* $field **mixed**
* $entity_object **mixed**
* $ws_params **mixed**



### <a name="method-getResources"></a>getResources

    mixed WebserviceRequestCore::getResources()





* Visibility: **public**
* This method is **static**.
* Source: [classes/webservice/WebserviceRequest.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L255)




### <a name="method-getSQLRetrieveFilter"></a>getSQLRetrieveFilter

    string WebserviceRequestCore::getSQLRetrieveFilter(string $sqlId, string $filterValue, string $tableAlias)

get SQL retrieve Filter



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 1538](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L1538)


#### Arguments
* $sqlId **string**
* $filterValue **string**
* $tableAlias **string** - = &#039;main.&#039;



### <a name="method-getallheaders"></a>getallheaders

    mixed WebserviceRequestCore::getallheaders()





* Visibility: **public**
* This method is **static**.
* Source: [classes/webservice/WebserviceRequest.php line 1733](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L1733)




### <a name="method-groupShopExists"></a>groupShopExists

    mixed WebserviceRequestCore::groupShopExists($params)





* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 815](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L815)


#### Arguments
* $params **mixed**



### <a name="method-hasErrors"></a>hasErrors

    boolean WebserviceRequestCore::hasErrors()

Check if there is one or more error



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 716](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L716)




### <a name="method-isActivated"></a>isActivated

    boolean WebserviceRequestCore::isActivated()

Check webservice activation



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 765](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L765)




### <a name="method-manageFilters"></a>manageFilters

    mixed WebserviceRequestCore::manageFilters()





* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 989](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L989)




### <a name="method-parseDisplayFields"></a>parseDisplayFields

    mixed WebserviceRequestCore::parseDisplayFields($str)





* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 903](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L903)


#### Arguments
* $str **mixed**



### <a name="method-returnOutput"></a>returnOutput

    array WebserviceRequestCore::returnOutput()

Thanks to the (WebserviceOutputBuilder) WebserviceKey::objOutput
Method build the output depend on the WebserviceRequest::outputFormat
and set HTTP header parameters.



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 1636](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L1636)




### <a name="method-saveEntityFromXml"></a>saveEntityFromXml

    boolean WebserviceRequestCore::saveEntityFromXml(integer $successReturnCode)

save Entity Object from XML



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 1364](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L1364)


#### Arguments
* $successReturnCode **integer**



### <a name="method-setError"></a>setError

    void WebserviceRequestCore::setError(integer $status, string $label, integer $code)

Set a webservice error



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 579](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L579)


#### Arguments
* $status **integer**
* $label **string**
* $code **integer**



### <a name="method-setErrorDidYouMean"></a>setErrorDidYouMean

    void WebserviceRequestCore::setErrorDidYouMean(integer $num, string $label, array $value, $available_values, integer $code)

Set a webservice error and propose a new value near from the available values



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 601](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L601)


#### Arguments
* $num **integer**
* $label **string**
* $value **array**
* $available_values **mixed**
* $code **integer**



### <a name="method-setFieldsToDisplay"></a>setFieldsToDisplay

    mixed WebserviceRequestCore::setFieldsToDisplay()





* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 946](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L946)




### <a name="method-setObjects"></a>setObjects

    mixed WebserviceRequestCore::setObjects()





* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 873](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L873)




### <a name="method-setOutputEnabled"></a>setOutputEnabled

    mixed WebserviceRequestCore::setOutputEnabled($bool)





* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 194](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L194)


#### Arguments
* $bool **mixed**



### <a name="method-shopExists"></a>shopExists

    mixed WebserviceRequestCore::shopExists($params)





* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 791](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L791)


#### Arguments
* $params **mixed**



### <a name="method-shopHasRight"></a>shopHasRight

    mixed WebserviceRequestCore::shopHasRight($key)





* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 774](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L774)


#### Arguments
* $key **mixed**



### <a name="method-specificPriceCalculation"></a>specificPriceCalculation

    mixed WebserviceRequestCore::specificPriceCalculation($parameters)





* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 366](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L366)


#### Arguments
* $parameters **mixed**



### <a name="method-specificPriceForCombination"></a>specificPriceForCombination

    array WebserviceRequestCore::specificPriceForCombination($entity_object, array $parameters)

This method is used for calculate the price for products on a virtual fields



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 398](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L398)


#### Arguments
* $entity_object **mixed**
* $parameters **array**



### <a name="method-specificPriceForProduct"></a>specificPriceForProduct

    array WebserviceRequestCore::specificPriceForProduct($entity_object, array $parameters)

This method is used for calculate the price for products on a virtual fields



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 357](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L357)


#### Arguments
* $entity_object **mixed**
* $parameters **array**



### <a name="method-webserviceChecks"></a>webserviceChecks

    mixed WebserviceRequestCore::webserviceChecks()





* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 566](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L566)




### <a name="method-webserviceErrorHandler"></a>webserviceErrorHandler

    boolean WebserviceRequestCore::webserviceErrorHandler(string $errno, array $errstr, array $errfile, array $errline)

Used to replace the default PHP error handler, in order to display PHP errors in a XML format



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 640](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceRequest.php#L640)


#### Arguments
* $errno **string** - contains the level of the error raised, as an integer
* $errstr **array** - contains the error message, as a string
* $errfile **array** - errfile, which contains the filename that the error was raised in, as a string
* $errline **array** - errline, which contains the line number the error was raised at, as an integer


