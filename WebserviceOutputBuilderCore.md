WebserviceOutputBuilderCore
===============






* Class name: WebserviceOutputBuilderCore
* Namespace: 



Constants
----------


### VIEW_LIST

    const VIEW_LIST = 1





### VIEW_DETAILS

    const VIEW_DETAILS = 2





Properties
----------


### $wsUrl

    protected mixed $wsUrl





* Visibility: **protected**


### $output

    protected mixed $output





* Visibility: **protected**


### $objectRender

    public \WebserviceOutputInterface $objectRender





* Visibility: **public**


### $wsResource

    protected mixed $wsResource





* Visibility: **protected**


### $depth

    protected mixed $depth





* Visibility: **protected**


### $schemaToDisplay

    protected mixed $schemaToDisplay





* Visibility: **protected**


### $fieldsToDisplay

    protected mixed $fieldsToDisplay





* Visibility: **protected**


### $specificFields

    protected mixed $specificFields = array()





* Visibility: **protected**


### $virtualFields

    protected mixed $virtualFields = array()





* Visibility: **protected**


### $statusInt

    protected mixed $statusInt





* Visibility: **protected**


### $wsParamOverrides

    protected mixed $wsParamOverrides





* Visibility: **protected**


### $_cache_ws_parameters

    protected mixed $_cache_ws_parameters = array()





* Visibility: **protected**
* This property is **static**.


### $headerParams

    protected mixed $headerParams = array('Access-Time' => 0, 'X-Powered-By' => 0, 'PSWS-Version' => 0, 'Content-Type' => 0)





* Visibility: **protected**


### $status

    protected string $status





* Visibility: **protected**


Methods
-------


### __construct

    mixed WebserviceOutputBuilderCore::__construct($ws_url)





* Visibility: **public**


#### Arguments
* $ws_url **mixed**



### setObjectRender

    \WebserviceOutputBuilder WebserviceOutputBuilderCore::setObjectRender(\WebserviceOutputInterface $obj_render)

Set the render object for set the output format.

Set the Content-type for the http header.

* Visibility: **public**


#### Arguments
* $obj_render **[WebserviceOutputInterface](WebserviceOutputInterface.md)**



### getObjectRender

    \WebserviceOutputInterface WebserviceOutputBuilderCore::getObjectRender()

getter



* Visibility: **public**




### setWsResources

    \WebserviceOutputBuilder WebserviceOutputBuilderCore::setWsResources(array $resources)

Need to have the resource list to get the class name for an entity,
To build



* Visibility: **public**


#### Arguments
* $resources **array**



### buildHeader

    array WebserviceOutputBuilderCore::buildHeader()

This method return an array with each http header params for a content.

This check each required params.

If this method is overrided don't forget to check required specific params (for xml etc...)

* Visibility: **public**




### setHeaderParams

    \WebserviceOutputBuilder WebserviceOutputBuilderCore::setHeaderParams(string $key, string $value)





* Visibility: **public**


#### Arguments
* $key **string** - &lt;p&gt;The normalized key expected for an http response&lt;/p&gt;
* $value **string**



### getHeaderParams

    array|string WebserviceOutputBuilderCore::getHeaderParams(null|string $key)





* Visibility: **public**


#### Arguments
* $key **null|string** - &lt;p&gt;if null get all header params otherwise the params specified by the key&lt;/p&gt;



### resetHeaderParams

    \WebserviceOutputBuilder WebserviceOutputBuilderCore::resetHeaderParams()

Delete all Header parameters previously set.



* Visibility: **public**




### getStatus

    string WebserviceOutputBuilderCore::getStatus()





* Visibility: **public**




### getStatusInt

    mixed WebserviceOutputBuilderCore::getStatusInt()





* Visibility: **public**




### setStatus

    void WebserviceOutputBuilderCore::setStatus(integer $num)

Set the return header status



* Visibility: **public**


#### Arguments
* $num **integer** - &lt;p&gt;the Http status code&lt;/p&gt;



### getErrors

    string WebserviceOutputBuilderCore::getErrors(array $errors)

Build errors output using an error array



* Visibility: **public**


#### Arguments
* $errors **array**



### getResourcesList

    string WebserviceOutputBuilderCore::getResourcesList($key_permissions)

Build the resource list in the output format specified by WebserviceOutputBuilder::objectRender



* Visibility: **public**


#### Arguments
* $key_permissions **mixed**



### registerOverrideWSParameters

    mixed WebserviceOutputBuilderCore::registerOverrideWSParameters($wsrObject, $method)





* Visibility: **public**


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


#### Arguments
* $object **ObjectModel** - &lt;p&gt;create by the entity&lt;/p&gt;
* $depth **integer** - &lt;p&gt;the depth for the tree diagram&lt;/p&gt;



### renderSchema

    string WebserviceOutputBuilderCore::renderSchema(\ObjectModel $object, array $ws_params)

Build a schema blank or synopsis



* Visibility: **protected**


#### Arguments
* $object **ObjectModel** - &lt;p&gt;create by the entity&lt;/p&gt;
* $ws_params **array** - &lt;p&gt;webserviceParams from the entity&lt;/p&gt;



### renderEntity

    string WebserviceOutputBuilderCore::renderEntity(\ObjectModel $object, integer $depth)

Build the entity detail.



* Visibility: **public**


#### Arguments
* $object **ObjectModel** - &lt;p&gt;create by the entity&lt;/p&gt;
* $depth **integer** - &lt;p&gt;the depth for the tree diagram&lt;/p&gt;



### renderField

    string WebserviceOutputBuilderCore::renderField(\ObjectModel $object, array $ws_params, string $field_name, array $field, integer $depth)

Build a field and use recursivity depend on the depth parameter.



* Visibility: **protected**


#### Arguments
* $object **ObjectModel** - &lt;p&gt;create by the entity&lt;/p&gt;
* $ws_params **array** - &lt;p&gt;webserviceParams from the entity&lt;/p&gt;
* $field_name **string**
* $field **array**
* $depth **integer**



### renderAssociations

    string WebserviceOutputBuilderCore::renderAssociations($object, $depth, $associations, $ws_params)





* Visibility: **protected**


#### Arguments
* $object **mixed**
* $depth **mixed**
* $associations **mixed**
* $ws_params **mixed**



### renderFlatAssociation

    mixed WebserviceOutputBuilderCore::renderFlatAssociation($object, $depth, $assoc_name, $resource_name, $fields_assoc, $object_assoc, $parent_details)





* Visibility: **protected**


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


#### Arguments
* $depth **mixed**



### getSynopsisDetails

    mixed WebserviceOutputBuilderCore::getSynopsisDetails($field)





* Visibility: **public**


#### Arguments
* $field **mixed**



### setSpecificField

    \WebserviceOutputBuilder WebserviceOutputBuilderCore::setSpecificField(string|object $object, string $method, $field_name, $entity_name)





* Visibility: **public**


#### Arguments
* $object **string|object**
* $method **string**
* $field_name **mixed**
* $entity_name **mixed**



### validateObjectAndMethod

    mixed WebserviceOutputBuilderCore::validateObjectAndMethod($object, $method)





* Visibility: **protected**


#### Arguments
* $object **mixed**
* $method **mixed**



### getSpecificField

    mixed WebserviceOutputBuilderCore::getSpecificField()





* Visibility: **public**




### overrideSpecificField

    mixed WebserviceOutputBuilderCore::overrideSpecificField($entity_name, $field_name, $field, $entity_object, $ws_params)





* Visibility: **protected**


#### Arguments
* $entity_name **mixed**
* $field_name **mixed**
* $field **mixed**
* $entity_object **mixed**
* $ws_params **mixed**



### setVirtualField

    mixed WebserviceOutputBuilderCore::setVirtualField($object, $method, $entity_name, $parameters)





* Visibility: **public**


#### Arguments
* $object **mixed**
* $method **mixed**
* $entity_name **mixed**
* $parameters **mixed**



### getVirtualFields

    mixed WebserviceOutputBuilderCore::getVirtualFields()





* Visibility: **public**




### addVirtualFields

    mixed WebserviceOutputBuilderCore::addVirtualFields($entity_name, $entity_object)





* Visibility: **public**


#### Arguments
* $entity_name **mixed**
* $entity_object **mixed**



### setFieldsToDisplay

    mixed WebserviceOutputBuilderCore::setFieldsToDisplay($fields)





* Visibility: **public**


#### Arguments
* $fields **mixed**


