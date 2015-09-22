Class WebserviceOutputBuilderCore
=====================





* Class name: WebserviceOutputBuilderCore
* Source: [classes/webservice/WebserviceOutputBuilder.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L30)

Constants
----------

* [VIEW_DETAILS](#constant-VIEW_DETAILS)
* [VIEW_LIST](#constant-VIEW_LIST)

Properties
----------

* [$_cache_ws_parameters](#property-$_cache_ws_parameters)
* [$depth](#property-$depth)
* [$fieldsToDisplay](#property-$fieldsToDisplay)
* [$headerParams](#property-$headerParams)
* [$objectRender](#property-$objectRender)
* [$output](#property-$output)
* [$schemaToDisplay](#property-$schemaToDisplay)
* [$specificFields](#property-$specificFields)
* [$status](#property-$status)
* [$statusInt](#property-$statusInt)
* [$virtualFields](#property-$virtualFields)
* [$wsParamOverrides](#property-$wsParamOverrides)
* [$wsResource](#property-$wsResource)
* [$wsUrl](#property-$wsUrl)

Methods
-------
* [__construct](#method-__construct)
* [addVirtualFields](#method-addVirtualFields)
* [buildHeader](#method-buildHeader)
* [getContent](#method-getContent)
* [getErrors](#method-getErrors)
* [getHeaderParams](#method-getHeaderParams)
* [getObjectRender](#method-getObjectRender)
* [getResourcesList](#method-getResourcesList)
* [getSpecificField](#method-getSpecificField)
* [getStatus](#method-getStatus)
* [getStatusInt](#method-getStatusInt)
* [getSynopsisDetails](#method-getSynopsisDetails)
* [getVirtualFields](#method-getVirtualFields)
* [overrideSpecificField](#method-overrideSpecificField)
* [registerOverrideWSParameters](#method-registerOverrideWSParameters)
* [renderAssociations](#method-renderAssociations)
* [renderEntity](#method-renderEntity)
* [renderEntityMinimum](#method-renderEntityMinimum)
* [renderField](#method-renderField)
* [renderFlatAssociation](#method-renderFlatAssociation)
* [renderSchema](#method-renderSchema)
* [resetHeaderParams](#method-resetHeaderParams)
* [setFieldsToDisplay](#method-setFieldsToDisplay)
* [setHeaderParams](#method-setHeaderParams)
* [setIndent](#method-setIndent)
* [setObjectRender](#method-setObjectRender)
* [setSpecificField](#method-setSpecificField)
* [setStatus](#method-setStatus)
* [setVirtualField](#method-setVirtualField)
* [setWsResources](#method-setWsResources)
* [validateObjectAndMethod](#method-validateObjectAndMethod)


Constants
----------


### <a name="constant-VIEW_DETAILS"></a>VIEW_DETAILS

    const VIEW_DETAILS = 2



* Source: [classes/webservice/WebserviceOutputBuilder.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L36)


### <a name="constant-VIEW_LIST"></a>VIEW_LIST

    const VIEW_LIST = 1



* Source: [classes/webservice/WebserviceOutputBuilder.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L35)


Properties
----------


### <a name="property-$_cache_ws_parameters"></a>$_cache_ws_parameters

    protected mixed $_cache_ws_parameters = array()





* Visibility: **protected**
* This property is **static**.
* Source: [classes/webservice/WebserviceOutputBuilder.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L52)


### <a name="property-$depth"></a>$depth

    protected mixed $depth





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L44)


### <a name="property-$fieldsToDisplay"></a>$fieldsToDisplay

    protected mixed $fieldsToDisplay





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L46)


### <a name="property-$headerParams"></a>$headerParams

    protected mixed $headerParams = array('Access-Time' => 0, 'X-Powered-By' => 0, 'PSWS-Version' => 0, 'Content-Type' => 0)





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L55)


### <a name="property-$objectRender"></a>$objectRender

    public \WebserviceOutputInterface $objectRender





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L42)


### <a name="property-$output"></a>$output

    protected mixed $output





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L39)


### <a name="property-$schemaToDisplay"></a>$schemaToDisplay

    protected mixed $schemaToDisplay





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L45)


### <a name="property-$specificFields"></a>$specificFields

    protected mixed $specificFields = array()





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L47)


### <a name="property-$status"></a>$status

    protected string $status





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L65)


### <a name="property-$statusInt"></a>$statusInt

    protected mixed $statusInt





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L49)


### <a name="property-$virtualFields"></a>$virtualFields

    protected mixed $virtualFields = array()





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L48)


### <a name="property-$wsParamOverrides"></a>$wsParamOverrides

    protected mixed $wsParamOverrides





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L50)


### <a name="property-$wsResource"></a>$wsResource

    protected mixed $wsResource





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L43)


### <a name="property-$wsUrl"></a>$wsUrl

    protected mixed $wsUrl





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L38)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed WebserviceOutputBuilderCore::__construct($ws_url)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L67)


#### Arguments
* $ws_url **mixed**



### <a name="method-addVirtualFields"></a>addVirtualFields

    mixed WebserviceOutputBuilderCore::addVirtualFields($entity_name, $entity_object)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 788](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L788)


#### Arguments
* $entity_name **mixed**
* $entity_object **mixed**



### <a name="method-buildHeader"></a>buildHeader

    array WebserviceOutputBuilderCore::buildHeader()

This method return an array with each http header params for a content.

This check each required params.

If this method is overrided don't forget to check required specific params (for xml etc...)

* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L130)




### <a name="method-getContent"></a>getContent

    string WebserviceOutputBuilderCore::getContent(array $objects, null|string $schema_to_display, string|array $fields_to_display, integer $depth, integer $type_of_view, $override)

Method is used for each content type
Different content types are :
		- list of entities,
		- tree diagram of entity details (full or minimum),
		- schema (synopsis & blank),



* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 349](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L349)


#### Arguments
* $objects **array** - each object created by entity asked
      @see WebserviceOutputBuilder::executeEntityGetAndHead
* $schema_to_display **null|string** - if null display the entities list or entity details.
* $fields_to_display **string|array** - the fields allow for the output
* $depth **integer** - depth for the tree diagram output.
* $type_of_view **integer** - use the 2 constants WebserviceOutputBuilder::VIEW_LIST WebserviceOutputBuilder::VIEW_DETAILS
* $override **mixed**



### <a name="method-getErrors"></a>getErrors

    string WebserviceOutputBuilderCore::getErrors(array $errors)

Build errors output using an error array



* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 259](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L259)


#### Arguments
* $errors **array**



### <a name="method-getHeaderParams"></a>getHeaderParams

    array|string WebserviceOutputBuilderCore::getHeaderParams(null|string $key)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L162)


#### Arguments
* $key **null|string** - if null get all header params otherwise the params specified by the key



### <a name="method-getObjectRender"></a>getObjectRender

    \WebserviceOutputInterface WebserviceOutputBuilderCore::getObjectRender()

getter



* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L103)




### <a name="method-getResourcesList"></a>getResourcesList

    string WebserviceOutputBuilderCore::getResourcesList($key_permissions)

Build the resource list in the output format specified by WebserviceOutputBuilder::objectRender



* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 285](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L285)


#### Arguments
* $key_permissions **mixed**



### <a name="method-getSpecificField"></a>getSpecificField

    mixed WebserviceOutputBuilderCore::getSpecificField()





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 755](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L755)




### <a name="method-getStatus"></a>getStatus

    string WebserviceOutputBuilderCore::getStatus()





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L195)




### <a name="method-getStatusInt"></a>getStatusInt

    mixed WebserviceOutputBuilderCore::getStatusInt()





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L200)




### <a name="method-getSynopsisDetails"></a>getSynopsisDetails

    mixed WebserviceOutputBuilderCore::getSynopsisDetails($field)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 707](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L707)


#### Arguments
* $field **mixed**



### <a name="method-getVirtualFields"></a>getVirtualFields

    mixed WebserviceOutputBuilderCore::getVirtualFields()





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 783](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L783)




### <a name="method-overrideSpecificField"></a>overrideSpecificField

    mixed WebserviceOutputBuilderCore::overrideSpecificField($entity_name, $field_name, $field, $entity_object, $ws_params)





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 759](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L759)


#### Arguments
* $entity_name **mixed**
* $field_name **mixed**
* $field **mixed**
* $entity_object **mixed**
* $ws_params **mixed**



### <a name="method-registerOverrideWSParameters"></a>registerOverrideWSParameters

    mixed WebserviceOutputBuilderCore::registerOverrideWSParameters($wsrObject, $method)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 329](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L329)


#### Arguments
* $wsrObject **mixed**
* $method **mixed**



### <a name="method-renderAssociations"></a>renderAssociations

    string WebserviceOutputBuilderCore::renderAssociations($object, $depth, $associations, $ws_params)





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 581](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L581)


#### Arguments
* $object **mixed**
* $depth **mixed**
* $associations **mixed**
* $ws_params **mixed**



### <a name="method-renderEntity"></a>renderEntity

    string WebserviceOutputBuilderCore::renderEntity(\ObjectModel $object, integer $depth)

Build the entity detail.



* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 453](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L453)


#### Arguments
* $object **[ObjectModel](class.ObjectModelCore)** - create by the entity
* $depth **integer** - the depth for the tree diagram



### <a name="method-renderEntityMinimum"></a>renderEntityMinimum

    string WebserviceOutputBuilderCore::renderEntityMinimum(\ObjectModel $object, integer $depth)

Create the tree diagram with no details



* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 411](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L411)


#### Arguments
* $object **[ObjectModel](class.ObjectModelCore)** - create by the entity
* $depth **integer** - the depth for the tree diagram



### <a name="method-renderField"></a>renderField

    string WebserviceOutputBuilderCore::renderField(\ObjectModel $object, array $ws_params, string $field_name, array $field, integer $depth)

Build a field and use recursivity depend on the depth parameter.



* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 514](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L514)


#### Arguments
* $object **[ObjectModel](class.ObjectModelCore)** - create by the entity
* $ws_params **array** - webserviceParams from the entity
* $field_name **string**
* $field **array**
* $depth **integer**



### <a name="method-renderFlatAssociation"></a>renderFlatAssociation

    mixed WebserviceOutputBuilderCore::renderFlatAssociation($object, $depth, $assoc_name, $resource_name, $fields_assoc, $object_assoc, $parent_details)





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 657](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L657)


#### Arguments
* $object **mixed**
* $depth **mixed**
* $assoc_name **mixed**
* $resource_name **mixed**
* $fields_assoc **mixed**
* $object_assoc **mixed**
* $parent_details **mixed**



### <a name="method-renderSchema"></a>renderSchema

    string WebserviceOutputBuilderCore::renderSchema(\ObjectModel $object, array $ws_params)

Build a schema blank or synopsis



* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 432](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L432)


#### Arguments
* $object **[ObjectModel](class.ObjectModelCore)** - create by the entity
* $ws_params **array** - webserviceParams from the entity



### <a name="method-resetHeaderParams"></a>resetHeaderParams

    \WebserviceOutputBuilder WebserviceOutputBuilderCore::resetHeaderParams()

Delete all Header parameters previously set.



* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L186)




### <a name="method-setFieldsToDisplay"></a>setFieldsToDisplay

    mixed WebserviceOutputBuilderCore::setFieldsToDisplay($fields)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 813](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L813)


#### Arguments
* $fields **mixed**



### <a name="method-setHeaderParams"></a>setHeaderParams

    \WebserviceOutputBuilder WebserviceOutputBuilderCore::setHeaderParams(string $key, string $value)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L147)


#### Arguments
* $key **string** - The normalized key expected for an http response
* $value **string**



### <a name="method-setIndent"></a>setIndent

    mixed WebserviceOutputBuilderCore::setIndent($depth)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 697](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L697)


#### Arguments
* $depth **mixed**



### <a name="method-setObjectRender"></a>setObjectRender

    \WebserviceOutputBuilder WebserviceOutputBuilderCore::setObjectRender(\WebserviceOutputInterface $obj_render)

Set the render object for set the output format.

Set the Content-type for the http header.

* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L85)


#### Arguments
* $obj_render **WebserviceOutputInterface**



### <a name="method-setSpecificField"></a>setSpecificField

    \WebserviceOutputBuilder WebserviceOutputBuilderCore::setSpecificField(string|object $object, string $method, $field_name, $entity_name)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 735](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L735)


#### Arguments
* $object **string|object**
* $method **string**
* $field_name **mixed**
* $entity_name **mixed**



### <a name="method-setStatus"></a>setStatus

    void WebserviceOutputBuilderCore::setStatus(integer $num)

Set the return header status



* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 210](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L210)


#### Arguments
* $num **integer** - the Http status code



### <a name="method-setVirtualField"></a>setVirtualField

    mixed WebserviceOutputBuilderCore::setVirtualField($object, $method, $entity_name, $parameters)





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 772](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L772)


#### Arguments
* $object **mixed**
* $method **mixed**
* $entity_name **mixed**
* $parameters **mixed**



### <a name="method-setWsResources"></a>setWsResources

    \WebserviceOutputBuilder WebserviceOutputBuilderCore::setWsResources(array $resources)

Need to have the resource list to get the class name for an entity,
To build



* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L116)


#### Arguments
* $resources **array**



### <a name="method-validateObjectAndMethod"></a>validateObjectAndMethod

    mixed WebserviceOutputBuilderCore::validateObjectAndMethod($object, $method)





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 746](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#L746)


#### Arguments
* $object **mixed**
* $method **mixed**


