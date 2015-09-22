Class TreeToolbarCore
=====================





* Class name: TreeToolbarCore
* Source: [classes/tree/TreeToolbar.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L27)
* This class implements: [ITreeToolbarCore](interface.ITreeToolbarCore)
Constants
----------

* [DEFAULT_TEMPLATE](#constant-DEFAULT_TEMPLATE)
* [DEFAULT_TEMPLATE_DIRECTORY](#constant-DEFAULT_TEMPLATE_DIRECTORY)

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
* [_normalizeDirectory](#method-_normalizeDirectory)
* [addAction](#method-addAction)
* [getActions](#method-getActions)
* [getContext](#method-getContext)
* [getData](#method-getData)
* [getTemplate](#method-getTemplate)
* [getTemplateDirectory](#method-getTemplateDirectory)
* [getTemplateFile](#method-getTemplateFile)
* [removeActions](#method-removeActions)
* [render](#method-render)
* [setActions](#method-setActions)
* [setContext](#method-setContext)
* [setData](#method-setData)
* [setTemplate](#method-setTemplate)
* [setTemplateDirectory](#method-setTemplateDirectory)


Constants
----------


### <a name="constant-DEFAULT_TEMPLATE"></a>DEFAULT_TEMPLATE

    const DEFAULT_TEMPLATE = 'tree_toolbar.tpl'



* Source: [classes/tree/TreeToolbar.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L30)


### <a name="constant-DEFAULT_TEMPLATE_DIRECTORY"></a>DEFAULT_TEMPLATE_DIRECTORY

    const DEFAULT_TEMPLATE_DIRECTORY = 'helpers/tree'



* Source: [classes/tree/TreeToolbar.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L29)


Properties
----------


### <a name="property-$_actions"></a>$_actions

    private mixed $_actions





* Visibility: **private**
* Source: [classes/tree/TreeToolbar.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L32)


### <a name="property-$_context"></a>$_context

    private mixed $_context





* Visibility: **private**
* Source: [classes/tree/TreeToolbar.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L33)


### <a name="property-$_data"></a>$_data

    private mixed $_data





* Visibility: **private**
* Source: [classes/tree/TreeToolbar.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L34)


### <a name="property-$_template"></a>$_template

    private mixed $_template





* Visibility: **private**
* Source: [classes/tree/TreeToolbar.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L35)


### <a name="property-$_template_directory"></a>$_template_directory

    private mixed $_template_directory





* Visibility: **private**
* Source: [classes/tree/TreeToolbar.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L36)


Methods
-------


### <a name="method-__toString"></a>__toString

    mixed TreeToolbarCore::__toString()





* Visibility: **public**
* Source: [classes/tree/TreeToolbar.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L38)




### <a name="method-_normalizeDirectory"></a>_normalizeDirectory

    mixed TreeToolbarCore::_normalizeDirectory($directory)





* Visibility: **private**
* Source: [classes/tree/TreeToolbar.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L201)


#### Arguments
* $directory **mixed**



### <a name="method-addAction"></a>addAction

    \TreeToolbar TreeToolbarCore::addAction(\ITreeToolbarButton $action)





* Visibility: **public**
* Source: [classes/tree/TreeToolbar.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L158)


#### Arguments
* $action **ITreeToolbarButton**



### <a name="method-getActions"></a>getActions

    mixed TreeToolbarCore::getActions()





* Visibility: **public**
* Source: [classes/tree/TreeToolbar.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L54)




### <a name="method-getContext"></a>getContext

    mixed TreeToolbarCore::getContext()





* Visibility: **public**
* Source: [classes/tree/TreeToolbar.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L69)




### <a name="method-getData"></a>getData

    mixed TreeToolbarCore::getData()





* Visibility: **public**
* Source: [classes/tree/TreeToolbar.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L88)




### <a name="method-getTemplate"></a>getTemplate

    mixed TreeToolbarCore::getTemplate()





* Visibility: **public**
* Source: [classes/tree/TreeToolbar.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L99)




### <a name="method-getTemplateDirectory"></a>getTemplateDirectory

    mixed TreeToolbarCore::getTemplateDirectory()





* Visibility: **public**
* Source: [classes/tree/TreeToolbar.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L114)




### <a name="method-getTemplateFile"></a>getTemplateFile

    mixed TreeToolbarCore::getTemplateFile($template)





* Visibility: **public**
* Source: [classes/tree/TreeToolbar.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L124)


#### Arguments
* $template **mixed**



### <a name="method-removeActions"></a>removeActions

    mixed TreeToolbarCore::removeActions()





* Visibility: **public**
* Source: [classes/tree/TreeToolbar.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L182)




### <a name="method-render"></a>render

    mixed TreeToolbarCore::render()





* Visibility: **public**
* Source: [classes/tree/TreeToolbar.php line 188](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L188)




### <a name="method-setActions"></a>setActions

    mixed TreeToolbarCore::setActions($actions)





* Visibility: **public**
* Source: [classes/tree/TreeToolbar.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L43)


#### Arguments
* $actions **mixed**



### <a name="method-setContext"></a>setContext

    mixed TreeToolbarCore::setContext($value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbar.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L63)


#### Arguments
* $value **mixed**



### <a name="method-setData"></a>setData

    mixed TreeToolbarCore::setData($value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbar.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L78)


#### Arguments
* $value **mixed**



### <a name="method-setTemplate"></a>setTemplate

    mixed TreeToolbarCore::setTemplate($value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbar.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L93)


#### Arguments
* $value **mixed**



### <a name="method-setTemplateDirectory"></a>setTemplateDirectory

    mixed TreeToolbarCore::setTemplateDirectory($value)





* Visibility: **public**
* Source: [classes/tree/TreeToolbar.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tree/TreeToolbar.php#L108)


#### Arguments
* $value **mixed**


