Class WebserviceOutputBuilderCore
=====================





* Class name: WebserviceOutputBuilderCore
* Source: [classes/webservice/WebserviceOutputBuilder.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L31)


Contents
--------

### Constants

* [VIEW_DETAILS](#constant-VIEW_DETAILS)
* [VIEW_LIST](#constant-VIEW_LIST)

### Properties

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

### Methods

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

```php
const VIEW_DETAILS = 2
```





* Source: [classes/webservice/WebserviceOutputBuilder.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L38).


### <a name="constant-VIEW_LIST"></a>VIEW_LIST

```php
const VIEW_LIST = 1
```





* Source: [classes/webservice/WebserviceOutputBuilder.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L37).


Properties
----------


### <a name="property-$depth"></a>$depth

```php
protected mixed $depth
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L44).


### <a name="property-$fieldsToDisplay"></a>$fieldsToDisplay

```php
protected mixed $fieldsToDisplay
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L46).


### <a name="property-$headerParams"></a>$headerParams

```php
protected mixed $headerParams = array('Access-Time' => 0, 'X-Powered-By' => 0, 'PSWS-Version' => 0, 'Content-Type' => 0)
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L53).


### <a name="property-$objectRender"></a>$objectRender

```php
public mixed $objectRender
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L42).


### <a name="property-$output"></a>$output

```php
protected mixed $output
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L41).


### <a name="property-$schemaToDisplay"></a>$schemaToDisplay

```php
protected mixed $schemaToDisplay
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L45).


### <a name="property-$specificFields"></a>$specificFields

```php
protected mixed $specificFields = array()
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L47).


### <a name="property-$status"></a>$status

```php
protected string $status
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L63).


### <a name="property-$statusInt"></a>$statusInt

```php
protected mixed $statusInt
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L49).


### <a name="property-$virtualFields"></a>$virtualFields

```php
protected mixed $virtualFields = array()
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L48).


### <a name="property-$wsParamOverrides"></a>$wsParamOverrides

```php
protected mixed $wsParamOverrides
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L50).


### <a name="property-$wsResource"></a>$wsResource

```php
protected mixed $wsResource
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L43).


### <a name="property-$wsUrl"></a>$wsUrl

```php
protected mixed $wsUrl
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L40).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed WebserviceOutputBuilderCore::__construct($ws_url)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L65)


#### Arguments
* $ws_url **mixed**



### <a name="method-addVirtualFields"></a>addVirtualFields

```php
mixed WebserviceOutputBuilderCore::addVirtualFields($entity_name, $entity_object)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 758](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L758)


#### Arguments
* $entity_name **mixed**
* $entity_object **mixed**



### <a name="method-buildHeader"></a>buildHeader

```php
array WebserviceOutputBuilderCore::buildHeader()
```

This method return an array with each http header params for a content.

This check each required params.

If this method is overrided don't forget to check required specific params (for xml etc...)

* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L123)




### <a name="method-getContent"></a>getContent

```php
string WebserviceOutputBuilderCore::getContent(array $objects, null|string $schema_to_display, string|array $fields_to_display, integer $depth, integer $type_of_view, $override)
```

Method is used for each content type
Different content types are :
		- list of entities,
		- tree diagram of entity details (full or minimum),
		- schema (synopsis & blank),



* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 347](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L347)


#### Arguments
* $objects **array** - each object created by entity asked
      @see WebserviceOutputBuilder::executeEntityGetAndHead
* $schema_to_display **null|string** - if null display the entities list or entity details.
* $fields_to_display **string|array** - the fields allow for the output
* $depth **integer** - depth for the tree diagram output.
* $type_of_view **integer** - use the 2 constants WebserviceOutputBuilder::VIEW_LIST WebserviceOutputBuilder::VIEW_DETAILS
* $override **mixed**



### <a name="method-getErrors"></a>getErrors

```php
string WebserviceOutputBuilderCore::getErrors(array $errors)
```

Build errors output using an error array



* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 251](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L251)


#### Arguments
* $errors **array**



### <a name="method-getHeaderParams"></a>getHeaderParams

```php
array|string WebserviceOutputBuilderCore::getHeaderParams(null|string $key)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L155)


#### Arguments
* $key **null|string** - if null get all header params otherwise the params specified by the key



### <a name="method-getObjectRender"></a>getObjectRender

```php
\WebserviceOutputInterface WebserviceOutputBuilderCore::getObjectRender()
```

getter



* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L97)




### <a name="method-getResourcesList"></a>getResourcesList

```php
string WebserviceOutputBuilderCore::getResourcesList($key_permissions)
```

Build the resource list in the output format specified by WebserviceOutputBuilder::objectRender



* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 281](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L281)


#### Arguments
* $key_permissions **mixed**



### <a name="method-getSpecificField"></a>getSpecificField

```php
mixed WebserviceOutputBuilderCore::getSpecificField()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 727](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L727)




### <a name="method-getStatus"></a>getStatus

```php
string WebserviceOutputBuilderCore::getStatus()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 187](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L187)




### <a name="method-getStatusInt"></a>getStatusInt

```php
mixed WebserviceOutputBuilderCore::getStatusInt()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L191)




### <a name="method-getSynopsisDetails"></a>getSynopsisDetails

```php
mixed WebserviceOutputBuilderCore::getSynopsisDetails($field)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 691](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L691)


#### Arguments
* $field **mixed**



### <a name="method-getVirtualFields"></a>getVirtualFields

```php
mixed WebserviceOutputBuilderCore::getVirtualFields()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 754](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L754)




### <a name="method-overrideSpecificField"></a>overrideSpecificField

```php
mixed WebserviceOutputBuilderCore::overrideSpecificField($entity_name, $field_name, $field, $entity_object, $ws_params)
```





* Visibility: **private**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 731](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L731)


#### Arguments
* $entity_name **mixed**
* $field_name **mixed**
* $field **mixed**
* $entity_object **mixed**
* $ws_params **mixed**



### <a name="method-registerOverrideWSParameters"></a>registerOverrideWSParameters

```php
mixed WebserviceOutputBuilderCore::registerOverrideWSParameters($wsrObject, $method)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 327](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L327)


#### Arguments
* $wsrObject **mixed**
* $method **mixed**



### <a name="method-renderAssociations"></a>renderAssociations

```php
string WebserviceOutputBuilderCore::renderAssociations($object, $depth, $associations, $ws_params)
```





* Visibility: **private**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 563](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L563)


#### Arguments
* $object **mixed**
* $depth **mixed**
* $associations **mixed**
* $ws_params **mixed**



### <a name="method-renderEntity"></a>renderEntity

```php
string WebserviceOutputBuilderCore::renderEntity(\ObjectModel $object, integer $depth)
```

Build the entity detail.



* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 446](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L446)


#### Arguments
* $object **[ObjectModel](class.ObjectModelCore.md)** - create by the entity
* $depth **integer** - the depth for the tree diagram



### <a name="method-renderEntityMinimum"></a>renderEntityMinimum

```php
string WebserviceOutputBuilderCore::renderEntityMinimum($object, $depth)
```

Create the tree diagram with no details



* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 407](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L407)


#### Arguments
* $object **mixed** - create by the entity
* $depth **mixed** - the depth for the tree diagram



### <a name="method-renderField"></a>renderField

```php
string WebserviceOutputBuilderCore::renderField(\ObjectModel $object, array $ws_params, string $field_name, array $field, integer $depth)
```

Build a field and use recursivity depend on the depth parameter.



* Visibility: **private**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 502](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L502)


#### Arguments
* $object **[ObjectModel](class.ObjectModelCore.md)** - create by the entity
* $ws_params **array** - webserviceParams from the entity
* $field_name **string**
* $field **array**
* $depth **integer**



### <a name="method-renderFlatAssociation"></a>renderFlatAssociation

```php
mixed WebserviceOutputBuilderCore::renderFlatAssociation($object, $depth, $assoc_name, $resource_name, $fields_assoc, $object_assoc, $parent_details)
```





* Visibility: **private**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 642](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L642)


#### Arguments
* $object **mixed**
* $depth **mixed**
* $assoc_name **mixed**
* $resource_name **mixed**
* $fields_assoc **mixed**
* $object_assoc **mixed**
* $parent_details **mixed**



### <a name="method-renderSchema"></a>renderSchema

```php
string WebserviceOutputBuilderCore::renderSchema($object, $ws_params)
```

Build a schema blank or synopsis



* Visibility: **private**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 423](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L423)


#### Arguments
* $object **mixed** - create by the entity
* $ws_params **mixed** - webserviceParams from the entity



### <a name="method-resetHeaderParams"></a>resetHeaderParams

```php
\WebserviceOutputBuilderCore WebserviceOutputBuilderCore::resetHeaderParams()
```

Delete all Header parameters previously set.



* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L178)




### <a name="method-setFieldsToDisplay"></a>setFieldsToDisplay

```php
mixed WebserviceOutputBuilderCore::setFieldsToDisplay($fields)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 784](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L784)


#### Arguments
* $fields **mixed**



### <a name="method-setHeaderParams"></a>setHeaderParams

```php
\WebserviceOutputBuilderCore WebserviceOutputBuilderCore::setHeaderParams($key, $value)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L141)


#### Arguments
* $key **mixed** - The normalized key expected for an http response
* $value **mixed**



### <a name="method-setIndent"></a>setIndent

```php
mixed WebserviceOutputBuilderCore::setIndent($depth)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 682](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L682)


#### Arguments
* $depth **mixed**



### <a name="method-setObjectRender"></a>setObjectRender

```php
\WebserviceOutputBuilderCore WebserviceOutputBuilderCore::setObjectRender(\WebserviceOutputInterface $obj_render)
```

Set the render object for set the output format.

Set the Content-type for the http header.

* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L81)


#### Arguments
* $obj_render **WebserviceOutputInterface**



### <a name="method-setSpecificField"></a>setSpecificField

```php
\WebserviceOutputBuilderCore WebserviceOutputBuilderCore::setSpecificField(string|object $object, string $method, $field_name, $entity_name)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 709](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L709)


#### Arguments
* $object **string|object**
* $method **string**
* $field_name **mixed**
* $entity_name **mixed**



### <a name="method-setStatus"></a>setStatus

```php
void WebserviceOutputBuilderCore::setStatus(integer $num)
```

Set the return header status



* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L201)


#### Arguments
* $num **integer** - the Http status code



### <a name="method-setVirtualField"></a>setVirtualField

```php
mixed WebserviceOutputBuilderCore::setVirtualField($object, $method, $entity_name, $parameters)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 744](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L744)


#### Arguments
* $object **mixed**
* $method **mixed**
* $entity_name **mixed**
* $parameters **mixed**



### <a name="method-setWsResources"></a>setWsResources

```php
\WebserviceOutputBuilderCore WebserviceOutputBuilderCore::setWsResources(array $resources)
```

Need to have the resource list to get the class name for an entity,
To build



* Visibility: **public**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L109)


#### Arguments
* $resources **array**



### <a name="method-validateObjectAndMethod"></a>validateObjectAndMethod

```php
mixed WebserviceOutputBuilderCore::validateObjectAndMethod($object, $method)
```





* Visibility: **private**
* Source: [classes/webservice/WebserviceOutputBuilder.php line 720](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceOutputBuilder.php#L720)


#### Arguments
* $object **mixed**
* $method **mixed**


