TreeToolbarCore
===============






* Class name: TreeToolbarCore
* This class is defined in [classes/tree/TreeToolbar.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L27)
* This class implements: [ITreeToolbarCore](ITreeToolbarCore)


Constants
----------

* [DEFAULT_TEMPLATE_DIRECTORY](#constant-DEFAULT_TEMPLATE_DIRECTORY)
* [DEFAULT_TEMPLATE](#constant-DEFAULT_TEMPLATE)

Properties
----------

* [$_actions](#property-$_actions)
* [$_context](#property-$_context)
* [$_data](#property-$_data)
* [$_template](#property-$_template)
* [$_template_directory](#property-$_template_directory)

Methods
-------
* [__toString](#method-__toString)
* [setActions](#method-setActions)
* [getActions](#method-getActions)
* [setContext](#method-setContext)
* [getContext](#method-getContext)
* [setData](#method-setData)
* [getData](#method-getData)
* [setTemplate](#method-setTemplate)
* [getTemplate](#method-getTemplate)
* [setTemplateDirectory](#method-setTemplateDirectory)
* [getTemplateDirectory](#method-getTemplateDirectory)
* [getTemplateFile](#method-getTemplateFile)
* [addAction](#method-addAction)
* [removeActions](#method-removeActions)
* [render](#method-render)
* [_normalizeDirectory](#method-_normalizeDirectory)


Constants
----------


### <a name="constant-DEFAULT_TEMPLATE_DIRECTORY"></a>DEFAULT_TEMPLATE_DIRECTORY

    const DEFAULT_TEMPLATE_DIRECTORY = 'helpers/tree'



* This constant is defined in [classes/tree/TreeToolbar.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L29)


### <a name="constant-DEFAULT_TEMPLATE"></a>DEFAULT_TEMPLATE

    const DEFAULT_TEMPLATE = 'tree_toolbar.tpl'



* This constant is defined in [classes/tree/TreeToolbar.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L30)


Properties
----------


### <a name="property-$_actions"></a>$_actions

    private mixed $_actions





* Visibility: **private**
* This property is defined in [classes/tree/TreeToolbar.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L32)


### <a name="property-$_context"></a>$_context

    private mixed $_context





* Visibility: **private**
* This property is defined in [classes/tree/TreeToolbar.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L33)


### <a name="property-$_data"></a>$_data

    private mixed $_data





* Visibility: **private**
* This property is defined in [classes/tree/TreeToolbar.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L34)


### <a name="property-$_template"></a>$_template

    private mixed $_template





* Visibility: **private**
* This property is defined in [classes/tree/TreeToolbar.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L35)


### <a name="property-$_template_directory"></a>$_template_directory

    private mixed $_template_directory





* Visibility: **private**
* This property is defined in [classes/tree/TreeToolbar.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L36)


Methods
-------


### <a name="method-__toString"></a>__toString

    mixed ITreeToolbarCore::__toString()





* Visibility: **public**
* This method is defined by [ITreeToolbarCore](ITreeToolbarCore)
* This method is defined in [classes/tree/TreeToolbar.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L29)




### <a name="method-setActions"></a>setActions

    mixed ITreeToolbarCore::setActions($value)





* Visibility: **public**
* This method is defined by [ITreeToolbarCore](ITreeToolbarCore)
* This method is defined in [classes/tree/TreeToolbar.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L30)


#### Arguments
* $value **mixed**



### <a name="method-getActions"></a>getActions

    mixed ITreeToolbarCore::getActions()





* Visibility: **public**
* This method is defined by [ITreeToolbarCore](ITreeToolbarCore)
* This method is defined in [classes/tree/TreeToolbar.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L31)




### <a name="method-setContext"></a>setContext

    mixed ITreeToolbarCore::setContext($value)





* Visibility: **public**
* This method is defined by [ITreeToolbarCore](ITreeToolbarCore)
* This method is defined in [classes/tree/TreeToolbar.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L32)


#### Arguments
* $value **mixed**



### <a name="method-getContext"></a>getContext

    mixed ITreeToolbarCore::getContext()





* Visibility: **public**
* This method is defined by [ITreeToolbarCore](ITreeToolbarCore)
* This method is defined in [classes/tree/TreeToolbar.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L33)




### <a name="method-setData"></a>setData

    mixed ITreeToolbarCore::setData($value)





* Visibility: **public**
* This method is defined by [ITreeToolbarCore](ITreeToolbarCore)
* This method is defined in [classes/tree/TreeToolbar.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L34)


#### Arguments
* $value **mixed**



### <a name="method-getData"></a>getData

    mixed ITreeToolbarCore::getData()





* Visibility: **public**
* This method is defined by [ITreeToolbarCore](ITreeToolbarCore)
* This method is defined in [classes/tree/TreeToolbar.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L35)




### <a name="method-setTemplate"></a>setTemplate

    mixed ITreeToolbarCore::setTemplate($value)





* Visibility: **public**
* This method is defined by [ITreeToolbarCore](ITreeToolbarCore)
* This method is defined in [classes/tree/TreeToolbar.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L36)


#### Arguments
* $value **mixed**



### <a name="method-getTemplate"></a>getTemplate

    mixed ITreeToolbarCore::getTemplate()





* Visibility: **public**
* This method is defined by [ITreeToolbarCore](ITreeToolbarCore)
* This method is defined in [classes/tree/TreeToolbar.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L37)




### <a name="method-setTemplateDirectory"></a>setTemplateDirectory

    mixed ITreeToolbarCore::setTemplateDirectory($value)





* Visibility: **public**
* This method is defined by [ITreeToolbarCore](ITreeToolbarCore)
* This method is defined in [classes/tree/TreeToolbar.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L38)


#### Arguments
* $value **mixed**



### <a name="method-getTemplateDirectory"></a>getTemplateDirectory

    mixed ITreeToolbarCore::getTemplateDirectory()





* Visibility: **public**
* This method is defined by [ITreeToolbarCore](ITreeToolbarCore)
* This method is defined in [classes/tree/TreeToolbar.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L39)




### <a name="method-getTemplateFile"></a>getTemplateFile

    mixed TreeToolbarCore::getTemplateFile($template)





* Visibility: **public**
* This method is defined in [classes/tree/TreeToolbar.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L124)


#### Arguments
* $template **mixed**



### <a name="method-addAction"></a>addAction

    mixed ITreeToolbarCore::addAction($action)





* Visibility: **public**
* This method is defined by [ITreeToolbarCore](ITreeToolbarCore)
* This method is defined in [classes/tree/TreeToolbar.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L40)


#### Arguments
* $action **mixed**



### <a name="method-removeActions"></a>removeActions

    mixed ITreeToolbarCore::removeActions()





* Visibility: **public**
* This method is defined by [ITreeToolbarCore](ITreeToolbarCore)
* This method is defined in [classes/tree/TreeToolbar.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L41)




### <a name="method-render"></a>render

    mixed ITreeToolbarCore::render()





* Visibility: **public**
* This method is defined by [ITreeToolbarCore](ITreeToolbarCore)
* This method is defined in [classes/tree/TreeToolbar.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L42)




### <a name="method-_normalizeDirectory"></a>_normalizeDirectory

    mixed TreeToolbarCore::_normalizeDirectory($directory)





* Visibility: **private**
* This method is defined in [classes/tree/TreeToolbar.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L201)


#### Arguments
* $directory **mixed**


