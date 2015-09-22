Class HelperTreeShopsCore
=====================





* Class name: HelperTreeShopsCore
* Parent class: [TreeCore](class.TreeCore)
* Source: [classes/helper/HelperTreeShops.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L27)

Constants
----------

* [DEFAULT_HEADER_TEMPLATE](#constant-DEFAULT_HEADER_TEMPLATE)
* [DEFAULT_NODE_FOLDER_TEMPLATE](#constant-DEFAULT_NODE_FOLDER_TEMPLATE)
* [DEFAULT_NODE_ITEM_TEMPLATE](#constant-DEFAULT_NODE_ITEM_TEMPLATE)
* [DEFAULT_TEMPLATE](#constant-DEFAULT_TEMPLATE)
* [DEFAULT_TEMPLATE_DIRECTORY](#constant-DEFAULT_TEMPLATE_DIRECTORY)

Properties
----------

* [$_attributes](#property-$_attributes)
* [$_context](#property-$_context)
* [$_data](#property-$_data)
* [$_data_search](#property-$_data_search)
* [$_headerTemplate](#property-$_headerTemplate)
* [$_id](#property-$_id)
* [$_id_tree](#property-$_id_tree)
* [$_lang](#property-$_lang)
* [$_no_js](#property-$_no_js)
* [$_node_folder_template](#property-$_node_folder_template)
* [$_node_item_template](#property-$_node_item_template)
* [$_selected_shops](#property-$_selected_shops)
* [$_template](#property-$_template)
* [$_template_directory](#property-$_template_directory)
* [$_title](#property-$_title)
* [$_toolbar](#property-$_toolbar)

Methods
-------
* [__construct](#method-__construct)
* [__toString](#method-__toString)
* [_normalizeDirectory](#method-_normalizeDirectory)
* [addAction](#method-addAction)
* [getActions](#method-getActions)
* [getAttribute](#method-getAttribute)
* [getAttributes](#method-getAttributes)
* [getContext](#method-getContext)
* [getData](#method-getData)
* [getDataSearch](#method-getDataSearch)
* [getHeaderTemplate](#method-getHeaderTemplate)
* [getId](#method-getId)
* [getIdTree](#method-getIdTree)
* [getLang](#method-getLang)
* [getNodeFolderTemplate](#method-getNodeFolderTemplate)
* [getNodeItemTemplate](#method-getNodeItemTemplate)
* [getSelectedShops](#method-getSelectedShops)
* [getTemplate](#method-getTemplate)
* [getTemplateDirectory](#method-getTemplateDirectory)
* [getTemplateFile](#method-getTemplateFile)
* [getTitle](#method-getTitle)
* [getToolbar](#method-getToolbar)
* [removeActions](#method-removeActions)
* [render](#method-render)
* [renderNodes](#method-renderNodes)
* [renderToolbar](#method-renderToolbar)
* [setActions](#method-setActions)
* [setAttribute](#method-setAttribute)
* [setAttributes](#method-setAttributes)
* [setContext](#method-setContext)
* [setData](#method-setData)
* [setDataSearch](#method-setDataSearch)
* [setHeaderTemplate](#method-setHeaderTemplate)
* [setId](#method-setId)
* [setIdTree](#method-setIdTree)
* [setLang](#method-setLang)
* [setNoJS](#method-setNoJS)
* [setNodeFolderTemplate](#method-setNodeFolderTemplate)
* [setNodeItemTemplate](#method-setNodeItemTemplate)
* [setSelectedShops](#method-setSelectedShops)
* [setTemplate](#method-setTemplate)
* [setTemplateDirectory](#method-setTemplateDirectory)
* [setTitle](#method-setTitle)
* [setToolbar](#method-setToolbar)
* [useInput](#method-useInput)
* [useToolbar](#method-useToolbar)


Constants
----------


### <a name="constant-DEFAULT_HEADER_TEMPLATE"></a>DEFAULT_HEADER_TEMPLATE

    const DEFAULT_HEADER_TEMPLATE = 'tree_header.tpl'



* Source: [classes/helper/HelperTreeShops.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L31)


### <a name="constant-DEFAULT_NODE_FOLDER_TEMPLATE"></a>DEFAULT_NODE_FOLDER_TEMPLATE

    const DEFAULT_NODE_FOLDER_TEMPLATE = 'tree_node_folder.tpl'



* Source: [classes/helper/HelperTreeShops.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L32)


### <a name="constant-DEFAULT_NODE_ITEM_TEMPLATE"></a>DEFAULT_NODE_ITEM_TEMPLATE

    const DEFAULT_NODE_ITEM_TEMPLATE = 'tree_node_item.tpl'



* Source: [classes/helper/HelperTreeShops.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L33)


### <a name="constant-DEFAULT_TEMPLATE"></a>DEFAULT_TEMPLATE

    const DEFAULT_TEMPLATE = 'tree.tpl'



* Source: [classes/helper/HelperTreeShops.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L30)


### <a name="constant-DEFAULT_TEMPLATE_DIRECTORY"></a>DEFAULT_TEMPLATE_DIRECTORY

    const DEFAULT_TEMPLATE_DIRECTORY = 'helpers/tree'



* Source: [classes/helper/HelperTreeShops.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L29)


Properties
----------


### <a name="property-$_attributes"></a>$_attributes

    protected mixed $_attributes





* Visibility: **protected**
* Source: [classes/helper/HelperTreeShops.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L35)


### <a name="property-$_context"></a>$_context

    private mixed $_context





* Visibility: **private**
* Source: [classes/helper/HelperTreeShops.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L36)


### <a name="property-$_data"></a>$_data

    protected mixed $_data





* Visibility: **protected**
* Source: [classes/helper/HelperTreeShops.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L37)


### <a name="property-$_data_search"></a>$_data_search

    protected mixed $_data_search





* Visibility: **protected**
* Source: [classes/helper/HelperTreeShops.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L38)


### <a name="property-$_headerTemplate"></a>$_headerTemplate

    protected mixed $_headerTemplate





* Visibility: **protected**
* Source: [classes/helper/HelperTreeShops.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L39)


### <a name="property-$_id"></a>$_id

    private mixed $_id





* Visibility: **private**
* Source: [classes/helper/HelperTreeShops.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L41)


### <a name="property-$_id_tree"></a>$_id_tree

    protected mixed $_id_tree





* Visibility: **protected**
* Source: [classes/helper/HelperTreeShops.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L40)


### <a name="property-$_lang"></a>$_lang

    private mixed $_lang





* Visibility: **private**
* Source: [classes/helper/HelperTreeShops.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L33)


### <a name="property-$_no_js"></a>$_no_js

    private mixed $_no_js





* Visibility: **private**
* Source: [classes/helper/HelperTreeShops.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L49)


### <a name="property-$_node_folder_template"></a>$_node_folder_template

    protected mixed $_node_folder_template





* Visibility: **protected**
* Source: [classes/helper/HelperTreeShops.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L42)


### <a name="property-$_node_item_template"></a>$_node_item_template

    protected mixed $_node_item_template





* Visibility: **protected**
* Source: [classes/helper/HelperTreeShops.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L43)


### <a name="property-$_selected_shops"></a>$_selected_shops

    private mixed $_selected_shops





* Visibility: **private**
* Source: [classes/helper/HelperTreeShops.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L34)


### <a name="property-$_template"></a>$_template

    protected mixed $_template





* Visibility: **protected**
* Source: [classes/helper/HelperTreeShops.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L44)


### <a name="property-$_template_directory"></a>$_template_directory

    private string $_template_directory





* Visibility: **private**
* Source: [classes/helper/HelperTreeShops.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L47)


### <a name="property-$_title"></a>$_title

    private mixed $_title





* Visibility: **private**
* Source: [classes/helper/HelperTreeShops.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L48)


### <a name="property-$_toolbar"></a>$_toolbar

    private \TreeToolbar $_toolbar





* Visibility: **private**
* Source: [classes/helper/HelperTreeShops.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L52)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed HelperTreeShopsCore::__construct($id, $data)





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L54)


#### Arguments
* $id **mixed**
* $data **mixed**



### <a name="method-__toString"></a>__toString

    mixed HelperTreeShopsCore::__toString()





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L63)




### <a name="method-_normalizeDirectory"></a>_normalizeDirectory

    mixed HelperTreeShopsCore::_normalizeDirectory($directory)





* Visibility: **private**
* Source: [classes/helper/HelperTreeShops.php line 479](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L479)


#### Arguments
* $directory **mixed**



### <a name="method-addAction"></a>addAction

    mixed HelperTreeShopsCore::addAction($action)





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 358](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L358)


#### Arguments
* $action **mixed**



### <a name="method-getActions"></a>getActions

    mixed HelperTreeShopsCore::getActions()





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L78)




### <a name="method-getAttribute"></a>getAttribute

    mixed HelperTreeShopsCore::getAttribute($name)





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L97)


#### Arguments
* $name **mixed**



### <a name="method-getAttributes"></a>getAttributes

    mixed HelperTreeShopsCore::getAttributes()





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L123)




### <a name="method-getContext"></a>getContext

    mixed HelperTreeShopsCore::getContext()





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L138)




### <a name="method-getData"></a>getData

    mixed HelperTreeShopsCore::getData()





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L176)




### <a name="method-getDataSearch"></a>getDataSearch

    mixed HelperTreeShopsCore::getDataSearch()





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L157)




### <a name="method-getHeaderTemplate"></a>getHeaderTemplate

    mixed HelperTreeShopsCore::getHeaderTemplate()





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L191)




### <a name="method-getId"></a>getId

    mixed HelperTreeShopsCore::getId()





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 206](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L206)




### <a name="method-getIdTree"></a>getIdTree

    mixed HelperTreeShopsCore::getIdTree()





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L118)




### <a name="method-getLang"></a>getLang

    mixed HelperTreeShopsCore::getLang()





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L62)




### <a name="method-getNodeFolderTemplate"></a>getNodeFolderTemplate

    mixed HelperTreeShopsCore::getNodeFolderTemplate()





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L217)




### <a name="method-getNodeItemTemplate"></a>getNodeItemTemplate

    mixed HelperTreeShopsCore::getNodeItemTemplate()





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L232)




### <a name="method-getSelectedShops"></a>getSelectedShops

    mixed HelperTreeShopsCore::getSelectedShops()





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L99)




### <a name="method-getTemplate"></a>getTemplate

    mixed HelperTreeShopsCore::getTemplate()





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 247](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L247)




### <a name="method-getTemplateDirectory"></a>getTemplateDirectory

    string HelperTreeShopsCore::getTemplateDirectory()





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L270)




### <a name="method-getTemplateFile"></a>getTemplateFile

    mixed HelperTreeShopsCore::getTemplateFile($template)





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 280](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L280)


#### Arguments
* $template **mixed**



### <a name="method-getTitle"></a>getTitle

    mixed HelperTreeShopsCore::getTitle()





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 324](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L324)




### <a name="method-getToolbar"></a>getToolbar

    mixed HelperTreeShopsCore::getToolbar()





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 345](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L345)




### <a name="method-removeActions"></a>removeActions

    mixed HelperTreeShopsCore::removeActions()





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 368](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L368)




### <a name="method-render"></a>render

    mixed HelperTreeShopsCore::render($data)





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 378](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L378)


#### Arguments
* $data **mixed**



### <a name="method-renderNodes"></a>renderNodes

    mixed HelperTreeShopsCore::renderNodes($data)





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 429](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L429)


#### Arguments
* $data **mixed**



### <a name="method-renderToolbar"></a>renderToolbar

    mixed HelperTreeShopsCore::renderToolbar()





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 464](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L464)




### <a name="method-setActions"></a>setActions

    mixed HelperTreeShopsCore::setActions($value)





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L68)


#### Arguments
* $value **mixed**



### <a name="method-setAttribute"></a>setAttribute

    mixed HelperTreeShopsCore::setAttribute($name, $value)





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L87)


#### Arguments
* $name **mixed**
* $value **mixed**



### <a name="method-setAttributes"></a>setAttributes

    mixed HelperTreeShopsCore::setAttributes($value)





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L102)


#### Arguments
* $value **mixed**



### <a name="method-setContext"></a>setContext

    mixed HelperTreeShopsCore::setContext($value)





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L132)


#### Arguments
* $value **mixed**



### <a name="method-setData"></a>setData

    mixed HelperTreeShopsCore::setData($value)





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L166)


#### Arguments
* $value **mixed**



### <a name="method-setDataSearch"></a>setDataSearch

    mixed HelperTreeShopsCore::setDataSearch($value)





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L147)


#### Arguments
* $value **mixed**



### <a name="method-setHeaderTemplate"></a>setHeaderTemplate

    mixed HelperTreeShopsCore::setHeaderTemplate($value)





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 185](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L185)


#### Arguments
* $value **mixed**



### <a name="method-setId"></a>setId

    mixed HelperTreeShopsCore::setId($value)





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L200)


#### Arguments
* $value **mixed**



### <a name="method-setIdTree"></a>setIdTree

    mixed HelperTreeShopsCore::setIdTree($id_tree)





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L112)


#### Arguments
* $id_tree **mixed**



### <a name="method-setLang"></a>setLang

    mixed HelperTreeShopsCore::setLang($value)





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L56)


#### Arguments
* $value **mixed**



### <a name="method-setNoJS"></a>setNoJS

    mixed HelperTreeShopsCore::setNoJS($value)





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 312](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L312)


#### Arguments
* $value **mixed**



### <a name="method-setNodeFolderTemplate"></a>setNodeFolderTemplate

    mixed HelperTreeShopsCore::setNodeFolderTemplate($value)





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 211](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L211)


#### Arguments
* $value **mixed**



### <a name="method-setNodeItemTemplate"></a>setNodeItemTemplate

    mixed HelperTreeShopsCore::setNodeItemTemplate($value)





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 226](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L226)


#### Arguments
* $value **mixed**



### <a name="method-setSelectedShops"></a>setSelectedShops

    mixed HelperTreeShopsCore::setSelectedShops($value)





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L89)


#### Arguments
* $value **mixed**



### <a name="method-setTemplate"></a>setTemplate

    mixed HelperTreeShopsCore::setTemplate($value)





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 241](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L241)


#### Arguments
* $value **mixed**



### <a name="method-setTemplateDirectory"></a>setTemplateDirectory

    \Tree HelperTreeShopsCore::setTemplateDirectory($value)





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 261](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L261)


#### Arguments
* $value **mixed**



### <a name="method-setTitle"></a>setTitle

    mixed HelperTreeShopsCore::setTitle($value)





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 318](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L318)


#### Arguments
* $value **mixed**



### <a name="method-setToolbar"></a>setToolbar

    mixed HelperTreeShopsCore::setToolbar($value)





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 329](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L329)


#### Arguments
* $value **mixed**



### <a name="method-useInput"></a>useInput

    mixed HelperTreeShopsCore::useInput()





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 469](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L469)




### <a name="method-useToolbar"></a>useToolbar

    mixed HelperTreeShopsCore::useToolbar()





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 474](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperTreeShops.php#L474)



