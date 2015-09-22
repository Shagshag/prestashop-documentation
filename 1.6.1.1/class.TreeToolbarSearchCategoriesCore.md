Class TreeToolbarSearchCategoriesCore
=====================





* Class name: TreeToolbarSearchCategoriesCore
* Parent class: [TreeToolbarButtonCore](class.TreeToolbarButtonCore.md)
* Source: [classes/tree/TreeToolbarSearchCategories.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L27)
* This class implements: [ITreeToolbarButtonCore](interface.ITreeToolbarButtonCore.md)
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





* Source: [classes/tree/TreeToolbarSearchCategories.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L29).


Properties
----------


### <a name="property-$_attributes"></a>$_attributes

    protected mixed $_attributes





* Visibility: **protected**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L31).


### <a name="property-$_class"></a>$_class

    private mixed $_class





* Visibility: **private**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L32).


### <a name="property-$_context"></a>$_context

    private mixed $_context





* Visibility: **private**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L33).


### <a name="property-$_id"></a>$_id

    private mixed $_id





* Visibility: **private**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L34).


### <a name="property-$_label"></a>$_label

    private mixed $_label





* Visibility: **private**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L35).


### <a name="property-$_name"></a>$_name

    private mixed $_name





* Visibility: **private**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L36).


### <a name="property-$_template"></a>$_template

    protected mixed $_template





* Visibility: **protected**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L37).


### <a name="property-$_template_directory"></a>$_template_directory

    protected mixed $_template_directory





* Visibility: **protected**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L38).


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed TreeToolbarSearchCategoriesCore::__construct($label, $id, $name, $class)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L40)


#### Arguments
* $label **mixed**
* $id **mixed**
* $name **mixed**
* $class **mixed**



### <a name="method-__toString"></a>__toString

    mixed TreeToolbarSearchCategoriesCore::__toString()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L48)




### <a name="method-_normalizeDirectory"></a>_normalizeDirectory

    mixed TreeToolbarSearchCategoriesCore::_normalizeDirectory($directory)





* Visibility: **private**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 210](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L210)


#### Arguments
* $directory **mixed**



### <a name="method-_renderData"></a>_renderData

    mixed TreeToolbarSearchCategoriesCore::_renderData($data)





* Visibility: **private**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L66)


#### Arguments
* $data **mixed**



### <a name="method-getAttribute"></a>getAttribute

    mixed TreeToolbarSearchCategoriesCore::getAttribute($name)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L63)


#### Arguments
* $name **mixed**



### <a name="method-getAttributes"></a>getAttributes

    mixed TreeToolbarSearchCategoriesCore::getAttributes()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L78)




### <a name="method-getClass"></a>getClass

    mixed TreeToolbarSearchCategoriesCore::getClass()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L92)




### <a name="method-getContext"></a>getContext

    mixed TreeToolbarSearchCategoriesCore::getContext()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L103)




### <a name="method-getId"></a>getId

    mixed TreeToolbarSearchCategoriesCore::getId()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L117)




### <a name="method-getLabel"></a>getLabel

    mixed TreeToolbarSearchCategoriesCore::getLabel()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L127)




### <a name="method-getName"></a>getName

    mixed TreeToolbarSearchCategoriesCore::getName()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L137)




### <a name="method-getTemplate"></a>getTemplate

    mixed TreeToolbarSearchCategoriesCore::getTemplate()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L148)




### <a name="method-getTemplateDirectory"></a>getTemplateDirectory

    mixed TreeToolbarSearchCategoriesCore::getTemplateDirectory()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L159)




### <a name="method-getTemplateFile"></a>getTemplateFile

    mixed TreeToolbarSearchCategoriesCore::getTemplateFile($template)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L168)


#### Arguments
* $template **mixed**



### <a name="method-hasAttribute"></a>hasAttribute

    mixed TreeToolbarSearchCategoriesCore::hasAttribute($name)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L196)


#### Arguments
* $name **mixed**



### <a name="method-render"></a>render

    mixed TreeToolbarSearchCategoriesCore::render()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L202)




### <a name="method-setAttribute"></a>setAttribute

    mixed TreeToolbarSearchCategoriesCore::setAttribute($name, $value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L53)


#### Arguments
* $name **mixed**
* $value **mixed**



### <a name="method-setAttributes"></a>setAttributes

    mixed TreeToolbarSearchCategoriesCore::setAttributes($value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L68)


#### Arguments
* $value **mixed**



### <a name="method-setClass"></a>setClass

    mixed TreeToolbarSearchCategoriesCore::setClass($value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L87)


#### Arguments
* $value **mixed**



### <a name="method-setContext"></a>setContext

    mixed TreeToolbarSearchCategoriesCore::setContext($value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L97)


#### Arguments
* $value **mixed**



### <a name="method-setId"></a>setId

    mixed TreeToolbarSearchCategoriesCore::setId($value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L112)


#### Arguments
* $value **mixed**



### <a name="method-setLabel"></a>setLabel

    mixed TreeToolbarSearchCategoriesCore::setLabel($value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L122)


#### Arguments
* $value **mixed**



### <a name="method-setName"></a>setName

    mixed TreeToolbarSearchCategoriesCore::setName($value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L132)


#### Arguments
* $value **mixed**



### <a name="method-setTemplate"></a>setTemplate

    mixed TreeToolbarSearchCategoriesCore::setTemplate($value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 142](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L142)


#### Arguments
* $value **mixed**



### <a name="method-setTemplateDirectory"></a>setTemplateDirectory

    mixed TreeToolbarSearchCategoriesCore::setTemplateDirectory($value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarSearchCategories.php#L153)


#### Arguments
* $value **mixed**


