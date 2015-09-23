Class WebserviceRequestCore
=====================





* Class name: WebserviceRequestCore
* Source: [classes/webservice/WebserviceRequest.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L27)


Contents
--------


### Properties

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

### Methods

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




Properties
----------


### <a name="property-$_authenticated"></a>$_authenticated

```php
protected boolean $_authenticated = false
```

Set if the authentication key was checked



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L64).


### <a name="property-$_available_languages"></a>$_available_languages

```php
protected mixed $_available_languages = null
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L29).


### <a name="property-$_docUrl"></a>$_docUrl

```php
protected string $_docUrl = 'http://doc.prestashop.com/display/PS15/Using+the+PrestaShop+Web+Service'
```

PrestaShop Webservice Documentation URL



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L58).


### <a name="property-$_inputXml"></a>$_inputXml

```php
protected string $_inputXml
```

If we are in PUT or POST case, we use this attribute to store the xml string value during process



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L143).


### <a name="property-$_instance"></a>$_instance

```php
protected \WebserviceRequest $_instance
```

Object instance for singleton



* Visibility: **protected**
* This property is **static**.
* Source: [classes/webservice/WebserviceRequest.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L149).


### <a name="property-$_key"></a>$_key

```php
protected string $_key
```

Key used for authentication



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L155).


### <a name="property-$_object"></a>$_object

```php
protected \ObjectModel $_object
```

The current object to support, it extends the PrestaShop ObjectModel



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L124).


### <a name="property-$_outputEnabled"></a>$_outputEnabled

```php
protected boolean $_outputEnabled = true
```

Set if return should display content or not



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L40).


### <a name="property-$_startTime"></a>$_startTime

```php
protected integer $_startTime
```

The time in microseconds of the start of the execution of the web service request



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L88).


### <a name="property-$depth"></a>$depth

```php
public integer $depth
```

This is used to have a deeper tree diagram.



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 161](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L161).


### <a name="property-$errors"></a>$errors

```php
public array $errors = array()
```

Errors triggered at execution



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L34).


### <a name="property-$fieldsToDisplay"></a>$fieldsToDisplay

```php
public string $fieldsToDisplay = 'minimum'
```

The fields to display. These fields will be displayed when retrieving objects



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L137).


### <a name="property-$keyPermissions"></a>$keyPermissions

```php
public array $keyPermissions
```

The permissions for the current key



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L106).


### <a name="property-$method"></a>$method

```php
public string $method
```

HTTP Method to support



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L70).


### <a name="property-$objOutput"></a>$objOutput

```php
protected \WebserviceOutputBuilder $objOutput
```

The object to build the output.



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L173).


### <a name="property-$objectSpecificManagement"></a>$objectSpecificManagement

```php
protected boolean $objectSpecificManagement = false
```

Set if the management is specific or if it is classic (entity management)



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L46).


### <a name="property-$objects"></a>$objects

```php
public array $objects
```

The list of objects to display



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L118).


### <a name="property-$outputFormat"></a>$outputFormat

```php
protected string $outputFormat = 'xml'
```

Name of the output format



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L167).


### <a name="property-$resourceConfiguration"></a>$resourceConfiguration

```php
public array $resourceConfiguration
```

The configuration parameters of the current resource



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L100).


### <a name="property-$resourceList"></a>$resourceList

```php
public array $resourceList
```

The list of each resources manageable via web service



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L94).


### <a name="property-$schemaToDisplay"></a>$schemaToDisplay

```php
public string $schemaToDisplay
```

The schema to display.

If null, no schema have to be displayed and normal management has to be performed

* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L131).


### <a name="property-$shopIDs"></a>$shopIDs

```php
public mixed $shopIDs
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/webservice/WebserviceRequest.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L182).


### <a name="property-$specificOutput"></a>$specificOutput

```php
protected string $specificOutput = ''
```

The XML string to display if web service call succeed



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L112).


### <a name="property-$urlFragments"></a>$urlFragments

```php
public array $urlFragments = array()
```

The segment list of the URL after the "api" segment



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L82).


### <a name="property-$urlSegment"></a>$urlSegment

```php
public array $urlSegment = array()
```

The segment of the URL



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L76).


### <a name="property-$wsUrl"></a>$wsUrl

```php
public string $wsUrl
```

Base PrestaShop webservice URL



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L52).


### <a name="property-$ws_current_classname"></a>$ws_current_classname

```php
public \ws_current_classname $ws_current_classname
```

Save the class name for override used in getInstance()



* Visibility: **public**
* This property is **static**.
* Source: [classes/webservice/WebserviceRequest.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L179).


Methods
-------


### <a name="method-authenticate"></a>authenticate

```php
boolean WebserviceRequestCore::authenticate()
```

Check request authentication



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 699](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L699)




### <a name="method-checkHTTPMethod"></a>checkHTTPMethod

```php
boolean WebserviceRequestCore::checkHTTPMethod()
```

Check HTTP method



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 839](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L839)




### <a name="method-checkResource"></a>checkResource

```php
boolean WebserviceRequestCore::checkResource()
```

Check resource validity



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 857](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L857)




### <a name="method-executeEntityDelete"></a>executeEntityDelete

```php
boolean WebserviceRequestCore::executeEntityDelete()
```

Execute DELETE method on a PrestaShop entity



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 1356](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L1356)




### <a name="method-executeEntityGetAndHead"></a>executeEntityGetAndHead

```php
boolean WebserviceRequestCore::executeEntityGetAndHead()
```

Execute GET and HEAD requests

Build filter
Build fields display
Build sort
Build limit

* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 1314](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L1314)




### <a name="method-executeEntityPost"></a>executeEntityPost

```php
boolean WebserviceRequestCore::executeEntityPost()
```

Execute POST method on a PrestaShop entity



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 1336](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L1336)




### <a name="method-executeEntityPut"></a>executeEntityPut

```php
boolean WebserviceRequestCore::executeEntityPut()
```

Execute PUT method on a PrestaShop entity



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 1346](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L1346)




### <a name="method-fetch"></a>fetch

```php
array WebserviceRequestCore::fetch(string $key, string $method, string $url, string $params, $bad_class_name, string $inputXml)
```

Start Webservice request
	Check webservice activation
	Check autentication
	Check resource
	Check HTTP Method
	Execute the action
	Display the result



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 393](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L393)


#### Arguments
* $key **string**
* $method **string**
* $url **string**
* $params **string**
* $bad_class_name **mixed**
* $inputXml **string**



### <a name="method-filterLanguage"></a>filterLanguage

```php
mixed WebserviceRequestCore::filterLanguage()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 1648](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L1648)




### <a name="method-getClosest"></a>getClosest

```php
string WebserviceRequestCore::getClosest(string $input, array $words)
```

Return the nearest value picked in the values list



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 583](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L583)


#### Arguments
* $input **string**
* $words **array**



### <a name="method-getFilteredObjectDetails"></a>getFilteredObjectDetails

```php
mixed WebserviceRequestCore::getFilteredObjectDetails()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 1258](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L1258)




### <a name="method-getFilteredObjectList"></a>getFilteredObjectList

```php
mixed WebserviceRequestCore::getFilteredObjectList()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 1224](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L1224)




### <a name="method-getInstance"></a>getInstance

```php
object WebserviceRequestCore::getInstance()
```

Get WebserviceRequest object instance (Singleton)



* Visibility: **public**
* This method is **static**.
* Source: [classes/webservice/WebserviceRequest.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L202)




### <a name="method-getOutputEnabled"></a>getOutputEnabled

```php
mixed WebserviceRequestCore::getOutputEnabled()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 185](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L185)




### <a name="method-getOutputObject"></a>getOutputObject

```php
mixed WebserviceRequestCore::getOutputObject($type)
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 209](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L209)


#### Arguments
* $type **mixed**



### <a name="method-getPriceForProduct"></a>getPriceForProduct

```php
array WebserviceRequestCore::getPriceForProduct($field, $entity_object, $ws_params)
```

This method is used for calculate the price for products on the output details



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 302](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L302)


#### Arguments
* $field **mixed**
* $entity_object **mixed**
* $ws_params **mixed**



### <a name="method-getResources"></a>getResources

```php
mixed WebserviceRequestCore::getResources()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/webservice/WebserviceRequest.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L221)




### <a name="method-getSQLRetrieveFilter"></a>getSQLRetrieveFilter

```php
string WebserviceRequestCore::getSQLRetrieveFilter(string $sqlId, string $filterValue, string $tableAlias)
```

get SQL retrieve Filter



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 1605](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L1605)


#### Arguments
* $sqlId **string**
* $filterValue **string**
* $tableAlias **string** - = &#039;main.&#039;



### <a name="method-groupShopExists"></a>groupShopExists

```php
mixed WebserviceRequestCore::groupShopExists($params)
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 817](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L817)


#### Arguments
* $params **mixed**



### <a name="method-hasErrors"></a>hasErrors

```php
boolean WebserviceRequestCore::hasErrors()
```

Check if there is one or more error



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 689](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L689)




### <a name="method-isActivated"></a>isActivated

```php
boolean WebserviceRequestCore::isActivated()
```

Check webservice activation



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 759](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L759)




### <a name="method-manageFilters"></a>manageFilters

```php
mixed WebserviceRequestCore::manageFilters()
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 1010](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L1010)




### <a name="method-parseDisplayFields"></a>parseDisplayFields

```php
mixed WebserviceRequestCore::parseDisplayFields($str)
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 918](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L918)


#### Arguments
* $str **mixed**



### <a name="method-returnOutput"></a>returnOutput

```php
array WebserviceRequestCore::returnOutput()
```

Thanks to the (WebserviceOutputBuilder) WebserviceKey::objOutput
Method build the output depend on the WebserviceRequest::outputFormat
and set HTTP header parameters.



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 1714](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L1714)




### <a name="method-saveEntityFromXml"></a>saveEntityFromXml

```php
boolean WebserviceRequestCore::saveEntityFromXml(integer $successReturnCode)
```

save Entity Object from XML



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 1418](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L1418)


#### Arguments
* $successReturnCode **integer**



### <a name="method-setError"></a>setError

```php
void WebserviceRequestCore::setError(integer $status, string $label, integer $code)
```

Set a webservice error



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 551](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L551)


#### Arguments
* $status **integer**
* $label **string**
* $code **integer**



### <a name="method-setErrorDidYouMean"></a>setErrorDidYouMean

```php
void WebserviceRequestCore::setErrorDidYouMean(integer $num, string $label, array $value, $available_values, integer $code)
```

Set a webservice error and propose a new value near from the available values



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 571](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L571)


#### Arguments
* $num **integer**
* $label **string**
* $value **array**
* $available_values **mixed**
* $code **integer**



### <a name="method-setFieldsToDisplay"></a>setFieldsToDisplay

```php
mixed WebserviceRequestCore::setFieldsToDisplay()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 958](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L958)




### <a name="method-setObjects"></a>setObjects

```php
mixed WebserviceRequestCore::setObjects()
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 880](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L880)




### <a name="method-setOutputEnabled"></a>setOutputEnabled

```php
mixed WebserviceRequestCore::setOutputEnabled($bool)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 190](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L190)


#### Arguments
* $bool **mixed**



### <a name="method-shopExists"></a>shopExists

```php
mixed WebserviceRequestCore::shopExists($params)
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 788](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L788)


#### Arguments
* $params **mixed**



### <a name="method-shopHasRight"></a>shopHasRight

```php
mixed WebserviceRequestCore::shopHasRight($key)
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 769](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L769)


#### Arguments
* $key **mixed**



### <a name="method-specificPriceCalculation"></a>specificPriceCalculation

```php
mixed WebserviceRequestCore::specificPriceCalculation($parameters)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 330](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L330)


#### Arguments
* $parameters **mixed**



### <a name="method-specificPriceForCombination"></a>specificPriceForCombination

```php
array WebserviceRequestCore::specificPriceForCombination($entity_object, array $parameters)
```

This method is used for calculate the price for products on a virtual fields



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 365](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L365)


#### Arguments
* $entity_object **mixed**
* $parameters **array**



### <a name="method-specificPriceForProduct"></a>specificPriceForProduct

```php
array WebserviceRequestCore::specificPriceForProduct($entity_object, array $parameters)
```

This method is used for calculate the price for products on a virtual fields



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 320](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L320)


#### Arguments
* $entity_object **mixed**
* $parameters **array**



### <a name="method-webserviceChecks"></a>webserviceChecks

```php
mixed WebserviceRequestCore::webserviceChecks()
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 538](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L538)




### <a name="method-webserviceErrorHandler"></a>webserviceErrorHandler

```php
boolean WebserviceRequestCore::webserviceErrorHandler(string $errno, array $errstr, array $errfile, array $errline)
```

Used to replace the default PHP error handler, in order to display PHP errors in a XML format



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 613](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.2/classes/webservice/WebserviceRequest.php#L613)


#### Arguments
* $errno **string** - contains the level of the error raised, as an integer
* $errstr **array** - contains the error message, as a string
* $errfile **array** - errfile, which contains the filename that the error was raised in, as a string
* $errline **array** - errline, which contains the line number the error was raised at, as an integer


