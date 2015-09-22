WebserviceOutputBuilderCore
===============






* Class name: WebserviceOutputBuilderCore
* Namespace: 

* This class is defined in [classes/webservice/WebserviceOutputBuilder.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#30)



Constants
----------


### VIEW_LIST

    const VIEW_LIST = 1



* This constant is defined in [classes/webservice/WebserviceOutputBuilder.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#35)


### VIEW_DETAILS

    const VIEW_DETAILS = 2



* This constant is defined in [classes/webservice/WebserviceOutputBuilder.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#36)


Properties
----------


### $wsUrl

    protected mixed $wsUrl





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceOutputBuilder.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#38)


### $output

    protected mixed $output





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceOutputBuilder.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#39)


### $objectRender

    public \WebserviceOutputInterface $objectRender





* Visibility: **public**
* This property is defined in [classes/webservice/WebserviceOutputBuilder.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#42)


### $wsResource

    protected mixed $wsResource





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceOutputBuilder.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#43)


### $depth

    protected mixed $depth





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceOutputBuilder.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#44)


### $schemaToDisplay

    protected mixed $schemaToDisplay





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceOutputBuilder.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#45)


### $fieldsToDisplay

    protected mixed $fieldsToDisplay





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceOutputBuilder.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#46)


### $specificFields

    protected mixed $specificFields = array()





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceOutputBuilder.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#47)


### $virtualFields

    protected mixed $virtualFields = array()





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceOutputBuilder.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#48)


### $statusInt

    protected mixed $statusInt





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceOutputBuilder.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#49)


### $wsParamOverrides

    protected mixed $wsParamOverrides





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceOutputBuilder.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#50)


### $_cache_ws_parameters

    protected mixed $_cache_ws_parameters = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/webservice/WebserviceOutputBuilder.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#52)


### $headerParams

    protected mixed $headerParams = array('Access-Time' => 0, 'X-Powered-By' => 0, 'PSWS-Version' => 0, 'Content-Type' => 0)





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceOutputBuilder.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#55)


### $status

    protected string $status





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceOutputBuilder.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#65)


Methods
-------


### __construct

    mixed WebserviceOutputBuilderCore::__construct($ws_url)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputBuilder.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#67)


#### Arguments
* $ws_url **mixed**



### setObjectRender

    \WebserviceOutputBuilder WebserviceOutputBuilderCore::setObjectRender(\WebserviceOutputInterface $obj_render)

Set the render object for set the output format.

Set the Content-type for the http header.

* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputBuilder.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#85)


#### Arguments
* $obj_render **[WebserviceOutputInterface](WebserviceOutputInterface)**



### getObjectRender

    \WebserviceOutputInterface WebserviceOutputBuilderCore::getObjectRender()

getter



* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputBuilder.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#103)




### setWsResources

    \WebserviceOutputBuilder WebserviceOutputBuilderCore::setWsResources(array $resources)

Need to have the resource list to get the class name for an entity,
To build



* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputBuilder.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#116)


#### Arguments
* $resources **array**



### buildHeader

    array WebserviceOutputBuilderCore::buildHeader()

This method return an array with each http header params for a content.

This check each required params.

If this method is overrided don't forget to check required specific params (for xml etc...)

* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputBuilder.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#130)




### setHeaderParams

    \WebserviceOutputBuilder WebserviceOutputBuilderCore::setHeaderParams(string $key, string $value)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputBuilder.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#147)


#### Arguments
* $key **string** - &lt;p&gt;The normalized key expected for an http response&lt;/p&gt;
* $value **string**



### getHeaderParams

    array|string WebserviceOutputBuilderCore::getHeaderParams(null|string $key)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputBuilder.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#162)


#### Arguments
* $key **null|string** - &lt;p&gt;if null get all header params otherwise the params specified by the key&lt;/p&gt;



### resetHeaderParams

    \WebserviceOutputBuilder WebserviceOutputBuilderCore::resetHeaderParams()

Delete all Header parameters previously set.



* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputBuilder.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#186)




### getStatus

    string WebserviceOutputBuilderCore::getStatus()





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputBuilder.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#195)




### getStatusInt

    mixed WebserviceOutputBuilderCore::getStatusInt()





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputBuilder.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#200)




### setStatus

    void WebserviceOutputBuilderCore::setStatus(integer $num)

Set the return header status



* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputBuilder.php line 210](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#210)


#### Arguments
* $num **integer** - &lt;p&gt;the Http status code&lt;/p&gt;



### getErrors

    string WebserviceOutputBuilderCore::getErrors(array $errors)

Build errors output using an error array



* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputBuilder.php line 259](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#259)


#### Arguments
* $errors **array**



### getResourcesList

    string WebserviceOutputBuilderCore::getResourcesList($key_permissions)

Build the resource list in the output format specified by WebserviceOutputBuilder::objectRender



* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputBuilder.php line 285](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#285)


#### Arguments
* $key_permissions **mixed**



### registerOverrideWSParameters

    mixed WebserviceOutputBuilderCore::registerOverrideWSParameters($wsrObject, $method)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputBuilder.php line 329](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#329)


#### Arguments
* $wsrObject **mixed**
* $method **mixed**



### getContent

    string WebserviceOutputBuilderCore::getContent(array $objects, null|string $schema_to_display, string|array $fields_to_display, integer $depth, integer $type_of_view, $override)

Method is used for each content type
Different content types are :
		- list of entities,
		- tree diagram of entity details (full or minimum),
		- schema (synopsis & blank),



* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputBuilder.php line 349](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#349)


#### Arguments
* $objects **array** - &lt;p&gt;each object created by entity asked&lt;/p&gt;
&lt;pre&gt;&lt;code&gt;      @see WebserviceOutputBuilder::executeEntityGetAndHead&lt;/code&gt;&lt;/pre&gt;
* $schema_to_display **null|string** - &lt;p&gt;if null display the entities list or entity details.&lt;/p&gt;
* $fields_to_display **string|array** - &lt;p&gt;the fields allow for the output&lt;/p&gt;
* $depth **integer** - &lt;p&gt;depth for the tree diagram output.&lt;/p&gt;
* $type_of_view **integer** - &lt;p&gt;use the 2 constants WebserviceOutputBuilder::VIEW_LIST WebserviceOutputBuilder::VIEW_DETAILS&lt;/p&gt;
* $override **mixed**



### renderEntityMinimum

    string WebserviceOutputBuilderCore::renderEntityMinimum(\ObjectModel $object, integer $depth)

Create the tree diagram with no details



* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputBuilder.php line 411](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#411)


#### Arguments
* $object **[ObjectModel](ObjectModelCore)** - &lt;p&gt;create by the entity&lt;/p&gt;
* $depth **integer** - &lt;p&gt;the depth for the tree diagram&lt;/p&gt;



### renderSchema

    string WebserviceOutputBuilderCore::renderSchema(\ObjectModel $object, array $ws_params)

Build a schema blank or synopsis



* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceOutputBuilder.php line 432](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#432)


#### Arguments
* $object **[ObjectModel](ObjectModelCore)** - &lt;p&gt;create by the entity&lt;/p&gt;
* $ws_params **array** - &lt;p&gt;webserviceParams from the entity&lt;/p&gt;



### renderEntity

    string WebserviceOutputBuilderCore::renderEntity(\ObjectModel $object, integer $depth)

Build the entity detail.



* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputBuilder.php line 453](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#453)


#### Arguments
* $object **[ObjectModel](ObjectModelCore)** - &lt;p&gt;create by the entity&lt;/p&gt;
* $depth **integer** - &lt;p&gt;the depth for the tree diagram&lt;/p&gt;



### renderField

    string WebserviceOutputBuilderCore::renderField(\ObjectModel $object, array $ws_params, string $field_name, array $field, integer $depth)

Build a field and use recursivity depend on the depth parameter.



* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceOutputBuilder.php line 514](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#514)


#### Arguments
* $object **[ObjectModel](ObjectModelCore)** - &lt;p&gt;create by the entity&lt;/p&gt;
* $ws_params **array** - &lt;p&gt;webserviceParams from the entity&lt;/p&gt;
* $field_name **string**
* $field **array**
* $depth **integer**



### renderAssociations

    string WebserviceOutputBuilderCore::renderAssociations($object, $depth, $associations, $ws_params)





* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceOutputBuilder.php line 581](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#581)


#### Arguments
* $object **mixed**
* $depth **mixed**
* $associations **mixed**
* $ws_params **mixed**



### renderFlatAssociation

    mixed WebserviceOutputBuilderCore::renderFlatAssociation($object, $depth, $assoc_name, $resource_name, $fields_assoc, $object_assoc, $parent_details)





* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceOutputBuilder.php line 657](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#657)


#### Arguments
* $object **mixed**
* $depth **mixed**
* $assoc_name **mixed**
* $resource_name **mixed**
* $fields_assoc **mixed**
* $object_assoc **mixed**
* $parent_details **mixed**



### setIndent

    mixed WebserviceOutputBuilderCore::setIndent($depth)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputBuilder.php line 697](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#697)


#### Arguments
* $depth **mixed**



### getSynopsisDetails

    mixed WebserviceOutputBuilderCore::getSynopsisDetails($field)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputBuilder.php line 707](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#707)


#### Arguments
* $field **mixed**



### setSpecificField

    \WebserviceOutputBuilder WebserviceOutputBuilderCore::setSpecificField(string|object $object, string $method, $field_name, $entity_name)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputBuilder.php line 735](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#735)


#### Arguments
* $object **string|object**
* $method **string**
* $field_name **mixed**
* $entity_name **mixed**



### validateObjectAndMethod

    mixed WebserviceOutputBuilderCore::validateObjectAndMethod($object, $method)





* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceOutputBuilder.php line 746](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#746)


#### Arguments
* $object **mixed**
* $method **mixed**



### getSpecificField

    mixed WebserviceOutputBuilderCore::getSpecificField()





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputBuilder.php line 755](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#755)




### overrideSpecificField

    mixed WebserviceOutputBuilderCore::overrideSpecificField($entity_name, $field_name, $field, $entity_object, $ws_params)





* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceOutputBuilder.php line 759](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#759)


#### Arguments
* $entity_name **mixed**
* $field_name **mixed**
* $field **mixed**
* $entity_object **mixed**
* $ws_params **mixed**



### setVirtualField

    mixed WebserviceOutputBuilderCore::setVirtualField($object, $method, $entity_name, $parameters)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputBuilder.php line 772](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#772)


#### Arguments
* $object **mixed**
* $method **mixed**
* $entity_name **mixed**
* $parameters **mixed**



### getVirtualFields

    mixed WebserviceOutputBuilderCore::getVirtualFields()





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputBuilder.php line 783](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#783)




### addVirtualFields

    mixed WebserviceOutputBuilderCore::addVirtualFields($entity_name, $entity_object)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputBuilder.php line 788](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#788)


#### Arguments
* $entity_name **mixed**
* $entity_object **mixed**



### setFieldsToDisplay

    mixed WebserviceOutputBuilderCore::setFieldsToDisplay($fields)





* Visibility: **public**
* This method is defined in [classes/webservice/WebserviceOutputBuilder.php line 813](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceOutputBuilder.php#813)


#### Arguments
* $fields **mixed**


