Class WebserviceRequestCore
=====================





* Class name: WebserviceRequestCore
* Source: [classes/webservice/WebserviceRequest.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L27)


Contents
--------

### Constants

* [HTTP_GET](#constant-HTTP_GET)
* [HTTP_POST](#constant-HTTP_POST)
* [HTTP_PUT](#constant-HTTP_PUT)

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

```php
const HTTP_GET = 1
```





* Source: [classes/webservice/WebserviceRequest.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L29).


### <a name="constant-HTTP_POST"></a>HTTP_POST

```php
const HTTP_POST = 2
```





* Source: [classes/webservice/WebserviceRequest.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L30).


### <a name="constant-HTTP_PUT"></a>HTTP_PUT

```php
const HTTP_PUT = 4
```





* Source: [classes/webservice/WebserviceRequest.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L31).


Properties
----------


### <a name="property-$_authenticated"></a>$_authenticated

```php
protected boolean $_authenticated = false
```

Set if the authentication key was checked



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L68).


### <a name="property-$_available_languages"></a>$_available_languages

```php
protected mixed $_available_languages = null
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L33).


### <a name="property-$_docUrl"></a>$_docUrl

```php
protected string $_docUrl = 'http://doc.prestashop.com/display/PS16/Using+the+PrestaShop+Web+Service'
```

PrestaShop Webservice Documentation URL



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L62).


### <a name="property-$_inputXml"></a>$_inputXml

```php
protected string $_inputXml
```

If we are in PUT or POST case, we use this attribute to store the xml string value during process



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L147).


### <a name="property-$_instance"></a>$_instance

```php
protected \WebserviceRequest $_instance
```

Object instance for singleton



* Visibility: **protected**
* This property is **static**.
* Source: [classes/webservice/WebserviceRequest.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L153).


### <a name="property-$_key"></a>$_key

```php
protected string $_key
```

Key used for authentication



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L159).


### <a name="property-$_object"></a>$_object

```php
protected \ObjectModel $_object
```

The current object to support, it extends the PrestaShop ObjectModel



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L128).


### <a name="property-$_outputEnabled"></a>$_outputEnabled

```php
protected boolean $_outputEnabled = true
```

Set if return should display content or not



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L44).


### <a name="property-$_startTime"></a>$_startTime

```php
protected integer $_startTime
```

The time in microseconds of the start of the execution of the web service request



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L92).


### <a name="property-$depth"></a>$depth

```php
public integer $depth
```

This is used to have a deeper tree diagram.



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L165).


### <a name="property-$errors"></a>$errors

```php
public array $errors = array()
```

Errors triggered at execution



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L38).


### <a name="property-$fieldsToDisplay"></a>$fieldsToDisplay

```php
public string $fieldsToDisplay = 'minimum'
```

The fields to display. These fields will be displayed when retrieving objects



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L141).


### <a name="property-$keyPermissions"></a>$keyPermissions

```php
public array $keyPermissions
```

The permissions for the current key



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L110).


### <a name="property-$method"></a>$method

```php
public string $method
```

HTTP Method to support



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L74).


### <a name="property-$objOutput"></a>$objOutput

```php
protected \WebserviceOutputBuilder $objOutput
```

The object to build the output.



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 177](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L177).


### <a name="property-$objectSpecificManagement"></a>$objectSpecificManagement

```php
protected boolean $objectSpecificManagement = false
```

Set if the management is specific or if it is classic (entity management)



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L50).


### <a name="property-$objects"></a>$objects

```php
public array $objects
```

The list of objects to display



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L122).


### <a name="property-$outputFormat"></a>$outputFormat

```php
protected string $outputFormat = 'xml'
```

Name of the output format



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L171).


### <a name="property-$resourceConfiguration"></a>$resourceConfiguration

```php
public array $resourceConfiguration
```

The configuration parameters of the current resource



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L104).


### <a name="property-$resourceList"></a>$resourceList

```php
public array $resourceList
```

The list of each resources manageable via web service



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L98).


### <a name="property-$schemaToDisplay"></a>$schemaToDisplay

```php
public string $schemaToDisplay
```

The schema to display.

If null, no schema have to be displayed and normal management has to be performed

* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L135).


### <a name="property-$shopIDs"></a>$shopIDs

```php
public mixed $shopIDs
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/webservice/WebserviceRequest.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L186).


### <a name="property-$specificOutput"></a>$specificOutput

```php
protected string $specificOutput = ''
```

The XML string to display if web service call succeed



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L116).


### <a name="property-$urlFragments"></a>$urlFragments

```php
public array $urlFragments = array()
```

The segment list of the URL after the "api" segment



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L86).


### <a name="property-$urlSegment"></a>$urlSegment

```php
public array $urlSegment = array()
```

The segment of the URL



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L80).


### <a name="property-$wsUrl"></a>$wsUrl

```php
public string $wsUrl
```

Base PrestaShop webservice URL



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L56).


### <a name="property-$ws_current_classname"></a>$ws_current_classname

```php
public \ws_current_classname $ws_current_classname
```

Save the class name for override used in getInstance()



* Visibility: **public**
* This property is **static**.
* Source: [classes/webservice/WebserviceRequest.php line 183](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L183).


Methods
-------


### <a name="method-authenticate"></a>authenticate

```php
boolean WebserviceRequestCore::authenticate()
```

Check request authentication



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 730](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L730)




### <a name="method-checkHTTPMethod"></a>checkHTTPMethod

```php
boolean WebserviceRequestCore::checkHTTPMethod()
```

Check HTTP method



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 855](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L855)




### <a name="method-checkResource"></a>checkResource

```php
boolean WebserviceRequestCore::checkResource()
```

Check resource validity



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 873](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L873)




### <a name="method-executeEntityDelete"></a>executeEntityDelete

```php
boolean WebserviceRequestCore::executeEntityDelete()
```

Execute DELETE method on a PrestaShop entity



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 1372](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L1372)




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
* Source: [classes/webservice/WebserviceRequest.php line 1330](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L1330)




### <a name="method-executeEntityPost"></a>executeEntityPost

```php
boolean WebserviceRequestCore::executeEntityPost()
```

Execute POST method on a PrestaShop entity



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 1352](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L1352)




### <a name="method-executeEntityPut"></a>executeEntityPut

```php
boolean WebserviceRequestCore::executeEntityPut()
```

Execute PUT method on a PrestaShop entity



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 1362](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L1362)




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
* Source: [classes/webservice/WebserviceRequest.php line 427](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L427)


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
* Source: [classes/webservice/WebserviceRequest.php line 1672](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L1672)




### <a name="method-getClosest"></a>getClosest

```php
string WebserviceRequestCore::getClosest(string $input, array $words)
```

Return the nearest value picked in the values list



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 614](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L614)


#### Arguments
* $input **string**
* $words **array**



### <a name="method-getFilteredObjectDetails"></a>getFilteredObjectDetails

```php
mixed WebserviceRequestCore::getFilteredObjectDetails()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 1274](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L1274)




### <a name="method-getFilteredObjectList"></a>getFilteredObjectList

```php
mixed WebserviceRequestCore::getFilteredObjectList()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 1240](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L1240)




### <a name="method-getInstance"></a>getInstance

```php
object WebserviceRequestCore::getInstance()
```

Get WebserviceRequest object instance (Singleton)



* Visibility: **public**
* This method is **static**.
* Source: [classes/webservice/WebserviceRequest.php line 206](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L206)




### <a name="method-getOutputEnabled"></a>getOutputEnabled

```php
mixed WebserviceRequestCore::getOutputEnabled()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L189)




### <a name="method-getOutputObject"></a>getOutputObject

```php
mixed WebserviceRequestCore::getOutputObject($type)
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 226](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L226)


#### Arguments
* $type **mixed**



### <a name="method-getPriceForProduct"></a>getPriceForProduct

```php
array WebserviceRequestCore::getPriceForProduct($field, $entity_object, $ws_params)
```

This method is used for calculate the price for products on the output details



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 338](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L338)


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
* Source: [classes/webservice/WebserviceRequest.php line 253](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L253)




### <a name="method-getSQLRetrieveFilter"></a>getSQLRetrieveFilter

```php
string WebserviceRequestCore::getSQLRetrieveFilter(string $sqlId, string $filterValue, string $tableAlias)
```

get SQL retrieve Filter



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 1629](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L1629)


#### Arguments
* $sqlId **string**
* $filterValue **string**
* $tableAlias **string** - = &#039;main.&#039;



### <a name="method-getallheaders"></a>getallheaders

```php
mixed WebserviceRequestCore::getallheaders()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/webservice/WebserviceRequest.php line 1840](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L1840)




### <a name="method-groupShopExists"></a>groupShopExists

```php
mixed WebserviceRequestCore::groupShopExists($params)
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 833](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L833)


#### Arguments
* $params **mixed**



### <a name="method-hasErrors"></a>hasErrors

```php
boolean WebserviceRequestCore::hasErrors()
```

Check if there is one or more error



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 720](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L720)




### <a name="method-isActivated"></a>isActivated

```php
boolean WebserviceRequestCore::isActivated()
```

Check webservice activation



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 775](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L775)




### <a name="method-manageFilters"></a>manageFilters

```php
mixed WebserviceRequestCore::manageFilters()
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 1026](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L1026)




### <a name="method-parseDisplayFields"></a>parseDisplayFields

```php
mixed WebserviceRequestCore::parseDisplayFields($str)
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 934](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L934)


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
* Source: [classes/webservice/WebserviceRequest.php line 1738](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L1738)




### <a name="method-saveEntityFromXml"></a>saveEntityFromXml

```php
boolean WebserviceRequestCore::saveEntityFromXml(integer $successReturnCode)
```

save Entity Object from XML



* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 1434](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L1434)


#### Arguments
* $successReturnCode **integer**



### <a name="method-setError"></a>setError

```php
void WebserviceRequestCore::setError(integer $status, string $label, integer $code)
```

Set a webservice error



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 582](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L582)


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
* Source: [classes/webservice/WebserviceRequest.php line 602](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L602)


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
* Source: [classes/webservice/WebserviceRequest.php line 974](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L974)




### <a name="method-setObjects"></a>setObjects

```php
mixed WebserviceRequestCore::setObjects()
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 896](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L896)




### <a name="method-setOutputEnabled"></a>setOutputEnabled

```php
mixed WebserviceRequestCore::setOutputEnabled($bool)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 194](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L194)


#### Arguments
* $bool **mixed**



### <a name="method-shopExists"></a>shopExists

```php
mixed WebserviceRequestCore::shopExists($params)
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 804](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L804)


#### Arguments
* $params **mixed**



### <a name="method-shopHasRight"></a>shopHasRight

```php
mixed WebserviceRequestCore::shopHasRight($key)
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 785](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L785)


#### Arguments
* $key **mixed**



### <a name="method-specificPriceCalculation"></a>specificPriceCalculation

```php
mixed WebserviceRequestCore::specificPriceCalculation($parameters)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 366](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L366)


#### Arguments
* $parameters **mixed**



### <a name="method-specificPriceForCombination"></a>specificPriceForCombination

```php
array WebserviceRequestCore::specificPriceForCombination($entity_object, array $parameters)
```

This method is used for calculate the price for products on a virtual fields



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 399](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L399)


#### Arguments
* $entity_object **mixed**
* $parameters **array**



### <a name="method-specificPriceForProduct"></a>specificPriceForProduct

```php
array WebserviceRequestCore::specificPriceForProduct($entity_object, array $parameters)
```

This method is used for calculate the price for products on a virtual fields



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 356](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L356)


#### Arguments
* $entity_object **mixed**
* $parameters **array**



### <a name="method-webserviceChecks"></a>webserviceChecks

```php
mixed WebserviceRequestCore::webserviceChecks()
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceRequest.php line 569](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L569)




### <a name="method-webserviceErrorHandler"></a>webserviceErrorHandler

```php
boolean WebserviceRequestCore::webserviceErrorHandler(string $errno, array $errstr, array $errfile, array $errline)
```

Used to replace the default PHP error handler, in order to display PHP errors in a XML format



* Visibility: **public**
* Source: [classes/webservice/WebserviceRequest.php line 644](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/webservice/WebserviceRequest.php#L644)


#### Arguments
* $errno **string** - contains the level of the error raised, as an integer
* $errstr **array** - contains the error message, as a string
* $errfile **array** - errfile, which contains the filename that the error was raised in, as a string
* $errline **array** - errline, which contains the line number the error was raised at, as an integer


