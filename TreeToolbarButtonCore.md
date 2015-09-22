TreeToolbarButtonCore
===============






* Class name: TreeToolbarButtonCore
* This is an **abstract** class
* This class is defined in [classes/tree/TreeToolbarButton.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L27)



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
* [setAttribute](#method-setAttribute)
* [getAttribute](#method-getAttribute)
* [setAttributes](#method-setAttributes)
* [getAttributes](#method-getAttributes)
* [setClass](#method-setClass)
* [getClass](#method-getClass)
* [setContext](#method-setContext)
* [getContext](#method-getContext)
* [setId](#method-setId)
* [getId](#method-getId)
* [setLabel](#method-setLabel)
* [getLabel](#method-getLabel)
* [setName](#method-setName)
* [getName](#method-getName)
* [setTemplate](#method-setTemplate)
* [getTemplate](#method-getTemplate)
* [setTemplateDirectory](#method-setTemplateDirectory)
* [getTemplateDirectory](#method-getTemplateDirectory)
* [getTemplateFile](#method-getTemplateFile)
* [hasAttribute](#method-hasAttribute)
* [render](#method-render)
* [_normalizeDirectory](#method-_normalizeDirectory)


Constants
----------


### <a name="constant-DEFAULT_TEMPLATE_DIRECTORY"></a>DEFAULT_TEMPLATE_DIRECTORY

    const DEFAULT_TEMPLATE_DIRECTORY = 'helpers/tree'



* This constant is defined in [classes/tree/TreeToolbarButton.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L29)


Properties
----------


### <a name="property-$_attributes"></a>$_attributes

    protected mixed $_attributes





* Visibility: **protected**
* This property is defined in [classes/tree/TreeToolbarButton.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L31)


### <a name="property-$_class"></a>$_class

    private mixed $_class





* Visibility: **private**
* This property is defined in [classes/tree/TreeToolbarButton.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L32)


### <a name="property-$_context"></a>$_context

    private mixed $_context





* Visibility: **private**
* This property is defined in [classes/tree/TreeToolbarButton.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L33)


### <a name="property-$_id"></a>$_id

    private mixed $_id





* Visibility: **private**
* This property is defined in [classes/tree/TreeToolbarButton.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L34)


### <a name="property-$_label"></a>$_label

    private mixed $_label





* Visibility: **private**
* This property is defined in [classes/tree/TreeToolbarButton.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L35)


### <a name="property-$_name"></a>$_name

    private mixed $_name





* Visibility: **private**
* This property is defined in [classes/tree/TreeToolbarButton.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L36)


### <a name="property-$_template"></a>$_template

    protected mixed $_template





* Visibility: **protected**
* This property is defined in [classes/tree/TreeToolbarButton.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L37)


### <a name="property-$_template_directory"></a>$_template_directory

    protected mixed $_template_directory





* Visibility: **protected**
* This property is defined in [classes/tree/TreeToolbarButton.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L38)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed TreeToolbarButtonCore::__construct($label, $id, $name, $class)





* Visibility: **public**
* This method is defined in [classes/tree/TreeToolbarButton.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L40)


#### Arguments
* $label **mixed**
* $id **mixed**
* $name **mixed**
* $class **mixed**



### <a name="method-__toString"></a>__toString

    mixed TreeToolbarButtonCore::__toString()





* Visibility: **public**
* This method is defined in [classes/tree/TreeToolbarButton.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L48)




### <a name="method-setAttribute"></a>setAttribute

    mixed TreeToolbarButtonCore::setAttribute($name, $value)





* Visibility: **public**
* This method is defined in [classes/tree/TreeToolbarButton.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L53)


#### Arguments
* $name **mixed**
* $value **mixed**



### <a name="method-getAttribute"></a>getAttribute

    mixed TreeToolbarButtonCore::getAttribute($name)





* Visibility: **public**
* This method is defined in [classes/tree/TreeToolbarButton.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L63)


#### Arguments
* $name **mixed**



### <a name="method-setAttributes"></a>setAttributes

    mixed TreeToolbarButtonCore::setAttributes($value)





* Visibility: **public**
* This method is defined in [classes/tree/TreeToolbarButton.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L68)


#### Arguments
* $value **mixed**



### <a name="method-getAttributes"></a>getAttributes

    mixed TreeToolbarButtonCore::getAttributes()





* Visibility: **public**
* This method is defined in [classes/tree/TreeToolbarButton.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L78)




### <a name="method-setClass"></a>setClass

    mixed TreeToolbarButtonCore::setClass($value)





* Visibility: **public**
* This method is defined in [classes/tree/TreeToolbarButton.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L87)


#### Arguments
* $value **mixed**



### <a name="method-getClass"></a>getClass

    mixed TreeToolbarButtonCore::getClass()





* Visibility: **public**
* This method is defined in [classes/tree/TreeToolbarButton.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L92)




### <a name="method-setContext"></a>setContext

    mixed TreeToolbarButtonCore::setContext($value)





* Visibility: **public**
* This method is defined in [classes/tree/TreeToolbarButton.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L97)


#### Arguments
* $value **mixed**



### <a name="method-getContext"></a>getContext

    mixed TreeToolbarButtonCore::getContext()





* Visibility: **public**
* This method is defined in [classes/tree/TreeToolbarButton.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L103)




### <a name="method-setId"></a>setId

    mixed TreeToolbarButtonCore::setId($value)





* Visibility: **public**
* This method is defined in [classes/tree/TreeToolbarButton.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L112)


#### Arguments
* $value **mixed**



### <a name="method-getId"></a>getId

    mixed TreeToolbarButtonCore::getId()





* Visibility: **public**
* This method is defined in [classes/tree/TreeToolbarButton.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L117)




### <a name="method-setLabel"></a>setLabel

    mixed TreeToolbarButtonCore::setLabel($value)





* Visibility: **public**
* This method is defined in [classes/tree/TreeToolbarButton.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L122)


#### Arguments
* $value **mixed**



### <a name="method-getLabel"></a>getLabel

    mixed TreeToolbarButtonCore::getLabel()





* Visibility: **public**
* This method is defined in [classes/tree/TreeToolbarButton.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L127)




### <a name="method-setName"></a>setName

    mixed TreeToolbarButtonCore::setName($value)





* Visibility: **public**
* This method is defined in [classes/tree/TreeToolbarButton.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L132)


#### Arguments
* $value **mixed**



### <a name="method-getName"></a>getName

    mixed TreeToolbarButtonCore::getName()





* Visibility: **public**
* This method is defined in [classes/tree/TreeToolbarButton.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L137)




### <a name="method-setTemplate"></a>setTemplate

    mixed TreeToolbarButtonCore::setTemplate($value)





* Visibility: **public**
* This method is defined in [classes/tree/TreeToolbarButton.php line 142](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L142)


#### Arguments
* $value **mixed**



### <a name="method-getTemplate"></a>getTemplate

    mixed TreeToolbarButtonCore::getTemplate()





* Visibility: **public**
* This method is defined in [classes/tree/TreeToolbarButton.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L148)




### <a name="method-setTemplateDirectory"></a>setTemplateDirectory

    mixed TreeToolbarButtonCore::setTemplateDirectory($value)





* Visibility: **public**
* This method is defined in [classes/tree/TreeToolbarButton.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L153)


#### Arguments
* $value **mixed**



### <a name="method-getTemplateDirectory"></a>getTemplateDirectory

    mixed TreeToolbarButtonCore::getTemplateDirectory()





* Visibility: **public**
* This method is defined in [classes/tree/TreeToolbarButton.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L159)




### <a name="method-getTemplateFile"></a>getTemplateFile

    mixed TreeToolbarButtonCore::getTemplateFile($template)





* Visibility: **public**
* This method is defined in [classes/tree/TreeToolbarButton.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L168)


#### Arguments
* $template **mixed**



### <a name="method-hasAttribute"></a>hasAttribute

    mixed TreeToolbarButtonCore::hasAttribute($name)





* Visibility: **public**
* This method is defined in [classes/tree/TreeToolbarButton.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L196)


#### Arguments
* $name **mixed**



### <a name="method-render"></a>render

    mixed TreeToolbarButtonCore::render()





* Visibility: **public**
* This method is defined in [classes/tree/TreeToolbarButton.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L202)




### <a name="method-_normalizeDirectory"></a>_normalizeDirectory

    mixed TreeToolbarButtonCore::_normalizeDirectory($directory)





* Visibility: **private**
* This method is defined in [classes/tree/TreeToolbarButton.php line 210](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarButton.php#L210)


#### Arguments
* $directory **mixed**


