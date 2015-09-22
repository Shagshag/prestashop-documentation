TreeToolbarLinkCore
===============






* Class name: TreeToolbarLinkCore
* Parent class: [TreeToolbarButtonCore](TreeToolbarButtonCore)
* This class is defined in [classes/tree/TreeToolbarLink.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L27)
* This class implements: [ITreeToolbarButtonCore](ITreeToolbarButtonCore)


Constants
----------

* [DEFAULT_TEMPLATE_DIRECTORY](#constant-DEFAULT_TEMPLATE_DIRECTORY)

Properties
----------

* [$_action](#property-$_action)
* [$_icon_class](#property-$_icon_class)
* [$_link](#property-$_link)
* [$_template](#property-$_template)
* [$_attributes](#property-$_attributes)
* [$_class](#property-$_class)
* [$_context](#property-$_context)
* [$_id](#property-$_id)
* [$_label](#property-$_label)
* [$_name](#property-$_name)
* [$_template_directory](#property-$_template_directory)

Methods
-------
* [__construct](#method-__construct)
* [setAction](#method-setAction)
* [getAction](#method-getAction)
* [setIconClass](#method-setIconClass)
* [getIconClass](#method-getIconClass)
* [setLink](#method-setLink)
* [getLink](#method-getLink)
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



* This constant is defined in [classes/tree/TreeToolbarLink.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L29)


Properties
----------


### <a name="property-$_action"></a>$_action

    private mixed $_action





* Visibility: **private**
* This property is defined in [classes/tree/TreeToolbarLink.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L30)


### <a name="property-$_icon_class"></a>$_icon_class

    private mixed $_icon_class





* Visibility: **private**
* This property is defined in [classes/tree/TreeToolbarLink.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L31)


### <a name="property-$_link"></a>$_link

    private mixed $_link





* Visibility: **private**
* This property is defined in [classes/tree/TreeToolbarLink.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L32)


### <a name="property-$_template"></a>$_template

    protected mixed $_template





* Visibility: **protected**
* This property is defined in [classes/tree/TreeToolbarLink.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L37)


### <a name="property-$_attributes"></a>$_attributes

    protected mixed $_attributes





* Visibility: **protected**
* This property is defined in [classes/tree/TreeToolbarLink.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L31)


### <a name="property-$_class"></a>$_class

    private mixed $_class





* Visibility: **private**
* This property is defined in [classes/tree/TreeToolbarLink.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L32)


### <a name="property-$_context"></a>$_context

    private mixed $_context





* Visibility: **private**
* This property is defined in [classes/tree/TreeToolbarLink.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L33)


### <a name="property-$_id"></a>$_id

    private mixed $_id





* Visibility: **private**
* This property is defined in [classes/tree/TreeToolbarLink.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L34)


### <a name="property-$_label"></a>$_label

    private mixed $_label





* Visibility: **private**
* This property is defined in [classes/tree/TreeToolbarLink.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L35)


### <a name="property-$_name"></a>$_name

    private mixed $_name





* Visibility: **private**
* This property is defined in [classes/tree/TreeToolbarLink.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L36)


### <a name="property-$_template_directory"></a>$_template_directory

    protected mixed $_template_directory





* Visibility: **protected**
* This property is defined in [classes/tree/TreeToolbarLink.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L38)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed TreeToolbarButtonCore::__construct($label, $id, $name, $class)





* Visibility: **public**
* This method is defined by [TreeToolbarButtonCore](TreeToolbarButtonCore)
* This method is defined in [classes/tree/TreeToolbarLink.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L40)


#### Arguments
* $label **mixed**
* $id **mixed**
* $name **mixed**
* $class **mixed**



### <a name="method-setAction"></a>setAction

    mixed TreeToolbarLinkCore::setAction($value)





* Visibility: **public**
* This method is defined in [classes/tree/TreeToolbarLink.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L44)


#### Arguments
* $value **mixed**



### <a name="method-getAction"></a>getAction

    mixed TreeToolbarLinkCore::getAction()





* Visibility: **public**
* This method is defined in [classes/tree/TreeToolbarLink.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L49)




### <a name="method-setIconClass"></a>setIconClass

    mixed TreeToolbarLinkCore::setIconClass($value)





* Visibility: **public**
* This method is defined in [classes/tree/TreeToolbarLink.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L54)


#### Arguments
* $value **mixed**



### <a name="method-getIconClass"></a>getIconClass

    mixed TreeToolbarLinkCore::getIconClass()





* Visibility: **public**
* This method is defined in [classes/tree/TreeToolbarLink.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L59)




### <a name="method-setLink"></a>setLink

    mixed TreeToolbarLinkCore::setLink($value)





* Visibility: **public**
* This method is defined in [classes/tree/TreeToolbarLink.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L64)


#### Arguments
* $value **mixed**



### <a name="method-getLink"></a>getLink

    mixed TreeToolbarLinkCore::getLink()





* Visibility: **public**
* This method is defined in [classes/tree/TreeToolbarLink.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L69)




### <a name="method-__toString"></a>__toString

    mixed ITreeToolbarButtonCore::__toString()





* Visibility: **public**
* This method is defined by [ITreeToolbarButtonCore](ITreeToolbarButtonCore)
* This method is defined in [classes/tree/TreeToolbarLink.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L29)




### <a name="method-setAttribute"></a>setAttribute

    mixed ITreeToolbarButtonCore::setAttribute($name, $value)





* Visibility: **public**
* This method is defined by [ITreeToolbarButtonCore](ITreeToolbarButtonCore)
* This method is defined in [classes/tree/TreeToolbarLink.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L30)


#### Arguments
* $name **mixed**
* $value **mixed**



### <a name="method-getAttribute"></a>getAttribute

    mixed ITreeToolbarButtonCore::getAttribute($name)





* Visibility: **public**
* This method is defined by [ITreeToolbarButtonCore](ITreeToolbarButtonCore)
* This method is defined in [classes/tree/TreeToolbarLink.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L31)


#### Arguments
* $name **mixed**



### <a name="method-setAttributes"></a>setAttributes

    mixed ITreeToolbarButtonCore::setAttributes($value)





* Visibility: **public**
* This method is defined by [ITreeToolbarButtonCore](ITreeToolbarButtonCore)
* This method is defined in [classes/tree/TreeToolbarLink.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L32)


#### Arguments
* $value **mixed**



### <a name="method-getAttributes"></a>getAttributes

    mixed ITreeToolbarButtonCore::getAttributes()





* Visibility: **public**
* This method is defined by [ITreeToolbarButtonCore](ITreeToolbarButtonCore)
* This method is defined in [classes/tree/TreeToolbarLink.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L33)




### <a name="method-setClass"></a>setClass

    mixed ITreeToolbarButtonCore::setClass($value)





* Visibility: **public**
* This method is defined by [ITreeToolbarButtonCore](ITreeToolbarButtonCore)
* This method is defined in [classes/tree/TreeToolbarLink.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L34)


#### Arguments
* $value **mixed**



### <a name="method-getClass"></a>getClass

    mixed ITreeToolbarButtonCore::getClass()





* Visibility: **public**
* This method is defined by [ITreeToolbarButtonCore](ITreeToolbarButtonCore)
* This method is defined in [classes/tree/TreeToolbarLink.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L35)




### <a name="method-setContext"></a>setContext

    mixed ITreeToolbarButtonCore::setContext($value)





* Visibility: **public**
* This method is defined by [ITreeToolbarButtonCore](ITreeToolbarButtonCore)
* This method is defined in [classes/tree/TreeToolbarLink.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L36)


#### Arguments
* $value **mixed**



### <a name="method-getContext"></a>getContext

    mixed ITreeToolbarButtonCore::getContext()





* Visibility: **public**
* This method is defined by [ITreeToolbarButtonCore](ITreeToolbarButtonCore)
* This method is defined in [classes/tree/TreeToolbarLink.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L37)




### <a name="method-setId"></a>setId

    mixed ITreeToolbarButtonCore::setId($value)





* Visibility: **public**
* This method is defined by [ITreeToolbarButtonCore](ITreeToolbarButtonCore)
* This method is defined in [classes/tree/TreeToolbarLink.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L38)


#### Arguments
* $value **mixed**



### <a name="method-getId"></a>getId

    mixed ITreeToolbarButtonCore::getId()





* Visibility: **public**
* This method is defined by [ITreeToolbarButtonCore](ITreeToolbarButtonCore)
* This method is defined in [classes/tree/TreeToolbarLink.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L39)




### <a name="method-setLabel"></a>setLabel

    mixed ITreeToolbarButtonCore::setLabel($value)





* Visibility: **public**
* This method is defined by [ITreeToolbarButtonCore](ITreeToolbarButtonCore)
* This method is defined in [classes/tree/TreeToolbarLink.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L40)


#### Arguments
* $value **mixed**



### <a name="method-getLabel"></a>getLabel

    mixed ITreeToolbarButtonCore::getLabel()





* Visibility: **public**
* This method is defined by [ITreeToolbarButtonCore](ITreeToolbarButtonCore)
* This method is defined in [classes/tree/TreeToolbarLink.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L41)




### <a name="method-setName"></a>setName

    mixed ITreeToolbarButtonCore::setName($value)





* Visibility: **public**
* This method is defined by [ITreeToolbarButtonCore](ITreeToolbarButtonCore)
* This method is defined in [classes/tree/TreeToolbarLink.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L42)


#### Arguments
* $value **mixed**



### <a name="method-getName"></a>getName

    mixed ITreeToolbarButtonCore::getName()





* Visibility: **public**
* This method is defined by [ITreeToolbarButtonCore](ITreeToolbarButtonCore)
* This method is defined in [classes/tree/TreeToolbarLink.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L43)




### <a name="method-setTemplate"></a>setTemplate

    mixed ITreeToolbarButtonCore::setTemplate($value)





* Visibility: **public**
* This method is defined by [ITreeToolbarButtonCore](ITreeToolbarButtonCore)
* This method is defined in [classes/tree/TreeToolbarLink.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L44)


#### Arguments
* $value **mixed**



### <a name="method-getTemplate"></a>getTemplate

    mixed ITreeToolbarButtonCore::getTemplate()





* Visibility: **public**
* This method is defined by [ITreeToolbarButtonCore](ITreeToolbarButtonCore)
* This method is defined in [classes/tree/TreeToolbarLink.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L45)




### <a name="method-setTemplateDirectory"></a>setTemplateDirectory

    mixed ITreeToolbarButtonCore::setTemplateDirectory($value)





* Visibility: **public**
* This method is defined by [ITreeToolbarButtonCore](ITreeToolbarButtonCore)
* This method is defined in [classes/tree/TreeToolbarLink.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L46)


#### Arguments
* $value **mixed**



### <a name="method-getTemplateDirectory"></a>getTemplateDirectory

    mixed ITreeToolbarButtonCore::getTemplateDirectory()





* Visibility: **public**
* This method is defined by [ITreeToolbarButtonCore](ITreeToolbarButtonCore)
* This method is defined in [classes/tree/TreeToolbarLink.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L47)




### <a name="method-getTemplateFile"></a>getTemplateFile

    mixed TreeToolbarButtonCore::getTemplateFile($template)





* Visibility: **public**
* This method is defined by [TreeToolbarButtonCore](TreeToolbarButtonCore)
* This method is defined in [classes/tree/TreeToolbarLink.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L168)


#### Arguments
* $template **mixed**



### <a name="method-hasAttribute"></a>hasAttribute

    mixed ITreeToolbarButtonCore::hasAttribute($name)





* Visibility: **public**
* This method is defined by [ITreeToolbarButtonCore](ITreeToolbarButtonCore)
* This method is defined in [classes/tree/TreeToolbarLink.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L48)


#### Arguments
* $name **mixed**



### <a name="method-render"></a>render

    mixed ITreeToolbarButtonCore::render()





* Visibility: **public**
* This method is defined by [ITreeToolbarButtonCore](ITreeToolbarButtonCore)
* This method is defined in [classes/tree/TreeToolbarLink.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L49)




### <a name="method-_normalizeDirectory"></a>_normalizeDirectory

    mixed TreeToolbarButtonCore::_normalizeDirectory($directory)





* Visibility: **private**
* This method is defined by [TreeToolbarButtonCore](TreeToolbarButtonCore)
* This method is defined in [classes/tree/TreeToolbarLink.php line 210](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbarLink.php#L210)


#### Arguments
* $directory **mixed**


