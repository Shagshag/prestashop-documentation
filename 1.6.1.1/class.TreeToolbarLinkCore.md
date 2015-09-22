Class TreeToolbarLinkCore
=====================





* Class name: TreeToolbarLinkCore
* Parent class: [TreeToolbarButtonCore](class.TreeToolbarButtonCore)
* Source: [classes/tree/TreeToolbarLink.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L27)
* This class implements: [ITreeToolbarButtonCore](interface.ITreeToolbarButtonCore)
Constants
----------

* [DEFAULT_TEMPLATE_DIRECTORY](#constant-DEFAULT_TEMPLATE_DIRECTORY)

Properties
----------

* [$_action](#property-$_action)
* [$_attributes](#property-$_attributes)
* [$_class](#property-$_class)
* [$_context](#property-$_context)
* [$_icon_class](#property-$_icon_class)
* [$_id](#property-$_id)
* [$_label](#property-$_label)
* [$_link](#property-$_link)
* [$_name](#property-$_name)
* [$_template](#property-$_template)
* [$_template_directory](#property-$_template_directory)

Methods
-------
* [__construct](#method-__construct)
* [__toString](#method-__toString)
* [_normalizeDirectory](#method-_normalizeDirectory)
* [getAction](#method-getAction)
* [getAttribute](#method-getAttribute)
* [getAttributes](#method-getAttributes)
* [getClass](#method-getClass)
* [getContext](#method-getContext)
* [getIconClass](#method-getIconClass)
* [getId](#method-getId)
* [getLabel](#method-getLabel)
* [getLink](#method-getLink)
* [getName](#method-getName)
* [getTemplate](#method-getTemplate)
* [getTemplateDirectory](#method-getTemplateDirectory)
* [getTemplateFile](#method-getTemplateFile)
* [hasAttribute](#method-hasAttribute)
* [render](#method-render)
* [setAction](#method-setAction)
* [setAttribute](#method-setAttribute)
* [setAttributes](#method-setAttributes)
* [setClass](#method-setClass)
* [setContext](#method-setContext)
* [setIconClass](#method-setIconClass)
* [setId](#method-setId)
* [setLabel](#method-setLabel)
* [setLink](#method-setLink)
* [setName](#method-setName)
* [setTemplate](#method-setTemplate)
* [setTemplateDirectory](#method-setTemplateDirectory)


Constants
----------


### <a name="constant-DEFAULT_TEMPLATE_DIRECTORY"></a>DEFAULT_TEMPLATE_DIRECTORY

    const DEFAULT_TEMPLATE_DIRECTORY = 'helpers/tree'



* Source: [classes/tree/TreeToolbarLink.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L29)


Properties
----------


### <a name="property-$_action"></a>$_action

    private mixed $_action





* Visibility: **private**
* Source: [classes/tree/TreeToolbarLink.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L30)


### <a name="property-$_attributes"></a>$_attributes

    protected mixed $_attributes





* Visibility: **protected**
* Source: [classes/tree/TreeToolbarLink.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L31)


### <a name="property-$_class"></a>$_class

    private mixed $_class





* Visibility: **private**
* Source: [classes/tree/TreeToolbarLink.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L32)


### <a name="property-$_context"></a>$_context

    private mixed $_context





* Visibility: **private**
* Source: [classes/tree/TreeToolbarLink.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L33)


### <a name="property-$_icon_class"></a>$_icon_class

    private mixed $_icon_class





* Visibility: **private**
* Source: [classes/tree/TreeToolbarLink.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L31)


### <a name="property-$_id"></a>$_id

    private mixed $_id





* Visibility: **private**
* Source: [classes/tree/TreeToolbarLink.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L34)


### <a name="property-$_label"></a>$_label

    private mixed $_label





* Visibility: **private**
* Source: [classes/tree/TreeToolbarLink.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L35)


### <a name="property-$_link"></a>$_link

    private mixed $_link





* Visibility: **private**
* Source: [classes/tree/TreeToolbarLink.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L32)


### <a name="property-$_name"></a>$_name

    private mixed $_name





* Visibility: **private**
* Source: [classes/tree/TreeToolbarLink.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L36)


### <a name="property-$_template"></a>$_template

    protected mixed $_template





* Visibility: **protected**
* Source: [classes/tree/TreeToolbarLink.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L37)


### <a name="property-$_template_directory"></a>$_template_directory

    protected mixed $_template_directory





* Visibility: **protected**
* Source: [classes/tree/TreeToolbarLink.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L38)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed TreeToolbarLinkCore::__construct($label, $id, $name, $class)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L40)


#### Arguments
* $label **mixed**
* $id **mixed**
* $name **mixed**
* $class **mixed**



### <a name="method-__toString"></a>__toString

    mixed TreeToolbarLinkCore::__toString()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L48)




### <a name="method-_normalizeDirectory"></a>_normalizeDirectory

    mixed TreeToolbarLinkCore::_normalizeDirectory($directory)





* Visibility: **private**
* Source: [classes/tree/TreeToolbarLink.php line 210](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L210)


#### Arguments
* $directory **mixed**



### <a name="method-getAction"></a>getAction

    mixed TreeToolbarLinkCore::getAction()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L49)




### <a name="method-getAttribute"></a>getAttribute

    mixed TreeToolbarLinkCore::getAttribute($name)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L63)


#### Arguments
* $name **mixed**



### <a name="method-getAttributes"></a>getAttributes

    mixed TreeToolbarLinkCore::getAttributes()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L78)




### <a name="method-getClass"></a>getClass

    mixed TreeToolbarLinkCore::getClass()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L92)




### <a name="method-getContext"></a>getContext

    mixed TreeToolbarLinkCore::getContext()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L103)




### <a name="method-getIconClass"></a>getIconClass

    mixed TreeToolbarLinkCore::getIconClass()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L59)




### <a name="method-getId"></a>getId

    mixed TreeToolbarLinkCore::getId()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L117)




### <a name="method-getLabel"></a>getLabel

    mixed TreeToolbarLinkCore::getLabel()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L127)




### <a name="method-getLink"></a>getLink

    mixed TreeToolbarLinkCore::getLink()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L69)




### <a name="method-getName"></a>getName

    mixed TreeToolbarLinkCore::getName()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L137)




### <a name="method-getTemplate"></a>getTemplate

    mixed TreeToolbarLinkCore::getTemplate()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L148)




### <a name="method-getTemplateDirectory"></a>getTemplateDirectory

    mixed TreeToolbarLinkCore::getTemplateDirectory()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L159)




### <a name="method-getTemplateFile"></a>getTemplateFile

    mixed TreeToolbarLinkCore::getTemplateFile($template)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L168)


#### Arguments
* $template **mixed**



### <a name="method-hasAttribute"></a>hasAttribute

    mixed TreeToolbarLinkCore::hasAttribute($name)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L196)


#### Arguments
* $name **mixed**



### <a name="method-render"></a>render

    mixed TreeToolbarLinkCore::render()





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L202)




### <a name="method-setAction"></a>setAction

    mixed TreeToolbarLinkCore::setAction($value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L44)


#### Arguments
* $value **mixed**



### <a name="method-setAttribute"></a>setAttribute

    mixed TreeToolbarLinkCore::setAttribute($name, $value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L53)


#### Arguments
* $name **mixed**
* $value **mixed**



### <a name="method-setAttributes"></a>setAttributes

    mixed TreeToolbarLinkCore::setAttributes($value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L68)


#### Arguments
* $value **mixed**



### <a name="method-setClass"></a>setClass

    mixed TreeToolbarLinkCore::setClass($value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L87)


#### Arguments
* $value **mixed**



### <a name="method-setContext"></a>setContext

    mixed TreeToolbarLinkCore::setContext($value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L97)


#### Arguments
* $value **mixed**



### <a name="method-setIconClass"></a>setIconClass

    mixed TreeToolbarLinkCore::setIconClass($value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L54)


#### Arguments
* $value **mixed**



### <a name="method-setId"></a>setId

    mixed TreeToolbarLinkCore::setId($value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L112)


#### Arguments
* $value **mixed**



### <a name="method-setLabel"></a>setLabel

    mixed TreeToolbarLinkCore::setLabel($value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L122)


#### Arguments
* $value **mixed**



### <a name="method-setLink"></a>setLink

    mixed TreeToolbarLinkCore::setLink($value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L64)


#### Arguments
* $value **mixed**



### <a name="method-setName"></a>setName

    mixed TreeToolbarLinkCore::setName($value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L132)


#### Arguments
* $value **mixed**



### <a name="method-setTemplate"></a>setTemplate

    mixed TreeToolbarLinkCore::setTemplate($value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 142](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L142)


#### Arguments
* $value **mixed**



### <a name="method-setTemplateDirectory"></a>setTemplateDirectory

    mixed TreeToolbarLinkCore::setTemplateDirectory($value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L153)


#### Arguments
* $value **mixed**


