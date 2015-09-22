Class TreeToolbarSearchCore
=====================





* Class name: TreeToolbarSearchCore
* Parent class: [TreeToolbarButtonCore](class.TreeToolbarButtonCore)
* Source: [classes/tree/TreeToolbarSearch.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L27)
* This class implements: [ITreeToolbarButtonCore](interface.ITreeToolbarButtonCore)
Constants
----------

* [DEFAULT_TEMPLATE_DIRECTORY](#constant-DEFAULT_TEMPLATE_DIRECTORY)

Properties
----------

* [$_attributes](#property-$_attributes)
* [$_class](#property-$_class)
* [$_context](#property-$_context)
* [$_id](#property-$_id)
* [$_label](#property-$_label)
* [$_name](#property-$_name)
* [$_template](#property-$_template)
* [$_template_directory](#property-$_template_directory)

Methods
-------
* [__construct](#method-__construct)
* [__toString](#method-__toString)
* [_normalizeDirectory](#method-_normalizeDirectory)
* [_renderData](#method-_renderData)
* [getAttribute](#method-getAttribute)
* [getAttributes](#method-getAttributes)
* [getClass](#method-getClass)
* [getContext](#method-getContext)
* [getId](#method-getId)
* [getLabel](#method-getLabel)
* [getName](#method-getName)
* [getTemplate](#method-getTemplate)
* [getTemplateDirectory](#method-getTemplateDirectory)
* [getTemplateFile](#method-getTemplateFile)
* [hasAttribute](#method-hasAttribute)
* [render](#method-render)
* [setAttribute](#method-setAttribute)
* [setAttributes](#method-setAttributes)
* [setClass](#method-setClass)
* [setContext](#method-setContext)
* [setId](#method-setId)
* [setLabel](#method-setLabel)
* [setName](#method-setName)
* [setTemplate](#method-setTemplate)
* [setTemplateDirectory](#method-setTemplateDirectory)


Constants
----------


### <a name="constant-DEFAULT_TEMPLATE_DIRECTORY"></a>DEFAULT_TEMPLATE_DIRECTORY

    const DEFAULT_TEMPLATE_DIRECTORY = 'helpers/tree'



* Source: [classes/tree/TreeToolbarSearch.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L29)


Properties
----------


### <a name="property-$_attributes"></a>$_attributes

    protected mixed $_attributes





* Visibility: **protected**
* Source: [classes/tree/TreeToolbarSearch.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L31)


### <a name="property-$_class"></a>$_class

    private mixed $_class





* Visibility: **private**
* Source: [classes/tree/TreeToolbarSearch.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L32)


### <a name="property-$_context"></a>$_context

    private mixed $_context





* Visibility: **private**
* Source: [classes/tree/TreeToolbarSearch.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L33)


### <a name="property-$_id"></a>$_id

    private mixed $_id





* Visibility: **private**
* Source: [classes/tree/TreeToolbarSearch.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L34)


### <a name="property-$_label"></a>$_label

    private mixed $_label





* Visibility: **private**
* Source: [classes/tree/TreeToolbarSearch.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L35)


### <a name="property-$_name"></a>$_name

    private mixed $_name





* Visibility: **private**
* Source: [classes/tree/TreeToolbarSearch.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L36)


### <a name="property-$_template"></a>$_template

    protected mixed $_template





* Visibility: **protected**
* Source: [classes/tree/TreeToolbarSearch.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L37)


### <a name="property-$_template_directory"></a>$_template_directory

    protected mixed $_template_directory





* Visibility: **protected**
* Source: [classes/tree/TreeToolbarSearch.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L38)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed TreeToolbarSearchCore::__construct($label, $id, $name, $class)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L40)


#### Arguments
* $label **mixed**
* $id **mixed**
* $name **mixed**
* $class **mixed**



### <a name="method-__toString"></a>__toString

    mixed TreeToolbarSearchCore::__toString()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L48)




### <a name="method-_normalizeDirectory"></a>_normalizeDirectory

    mixed TreeToolbarSearchCore::_normalizeDirectory($directory)





* Visibility: **private**
* Source: [classes/tree/TreeToolbarSearch.php line 210](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L210)


#### Arguments
* $directory **mixed**



### <a name="method-_renderData"></a>_renderData

    mixed TreeToolbarSearchCore::_renderData($data)





* Visibility: **private**
* Source: [classes/tree/TreeToolbarSearch.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L69)


#### Arguments
* $data **mixed**



### <a name="method-getAttribute"></a>getAttribute

    mixed TreeToolbarSearchCore::getAttribute($name)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L63)


#### Arguments
* $name **mixed**



### <a name="method-getAttributes"></a>getAttributes

    mixed TreeToolbarSearchCore::getAttributes()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L78)




### <a name="method-getClass"></a>getClass

    mixed TreeToolbarSearchCore::getClass()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L92)




### <a name="method-getContext"></a>getContext

    mixed TreeToolbarSearchCore::getContext()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L103)




### <a name="method-getId"></a>getId

    mixed TreeToolbarSearchCore::getId()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L117)




### <a name="method-getLabel"></a>getLabel

    mixed TreeToolbarSearchCore::getLabel()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L127)




### <a name="method-getName"></a>getName

    mixed TreeToolbarSearchCore::getName()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L137)




### <a name="method-getTemplate"></a>getTemplate

    mixed TreeToolbarSearchCore::getTemplate()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L148)




### <a name="method-getTemplateDirectory"></a>getTemplateDirectory

    mixed TreeToolbarSearchCore::getTemplateDirectory()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L159)




### <a name="method-getTemplateFile"></a>getTemplateFile

    mixed TreeToolbarSearchCore::getTemplateFile($template)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L168)


#### Arguments
* $template **mixed**



### <a name="method-hasAttribute"></a>hasAttribute

    mixed TreeToolbarSearchCore::hasAttribute($name)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L196)


#### Arguments
* $name **mixed**



### <a name="method-render"></a>render

    mixed TreeToolbarSearchCore::render()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L202)




### <a name="method-setAttribute"></a>setAttribute

    mixed TreeToolbarSearchCore::setAttribute($name, $value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L53)


#### Arguments
* $name **mixed**
* $value **mixed**



### <a name="method-setAttributes"></a>setAttributes

    mixed TreeToolbarSearchCore::setAttributes($value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L68)


#### Arguments
* $value **mixed**



### <a name="method-setClass"></a>setClass

    mixed TreeToolbarSearchCore::setClass($value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L87)


#### Arguments
* $value **mixed**



### <a name="method-setContext"></a>setContext

    mixed TreeToolbarSearchCore::setContext($value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L97)


#### Arguments
* $value **mixed**



### <a name="method-setId"></a>setId

    mixed TreeToolbarSearchCore::setId($value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L112)


#### Arguments
* $value **mixed**



### <a name="method-setLabel"></a>setLabel

    mixed TreeToolbarSearchCore::setLabel($value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L122)


#### Arguments
* $value **mixed**



### <a name="method-setName"></a>setName

    mixed TreeToolbarSearchCore::setName($value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L132)


#### Arguments
* $value **mixed**



### <a name="method-setTemplate"></a>setTemplate

    mixed TreeToolbarSearchCore::setTemplate($value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 142](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L142)


#### Arguments
* $value **mixed**



### <a name="method-setTemplateDirectory"></a>setTemplateDirectory

    mixed TreeToolbarSearchCore::setTemplateDirectory($value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearch.php#L153)


#### Arguments
* $value **mixed**


