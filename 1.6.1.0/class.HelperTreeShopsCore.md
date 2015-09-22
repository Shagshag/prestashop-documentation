Class HelperTreeShopsCore
=====================





* Class name: HelperTreeShopsCore
* Parent class: [TreeCore](class.TreeCore.md)
* Source: [classes/helper/HelperTreeShops.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L27)


Contents
--------

### Constants

* [DEFAULT_HEADER_TEMPLATE](#constant-DEFAULT_HEADER_TEMPLATE)
* [DEFAULT_NODE_FOLDER_TEMPLATE](#constant-DEFAULT_NODE_FOLDER_TEMPLATE)
* [DEFAULT_NODE_ITEM_TEMPLATE](#constant-DEFAULT_NODE_ITEM_TEMPLATE)
* [DEFAULT_TEMPLATE](#constant-DEFAULT_TEMPLATE)
* [DEFAULT_TEMPLATE_DIRECTORY](#constant-DEFAULT_TEMPLATE_DIRECTORY)

### Properties

* [$_attributes](#property-$_attributes)
* [$_context](#property-$_context)
* [$_data](#property-$_data)
* [$_data_search](#property-$_data_search)
* [$_headerTemplate](#property-$_headerTemplate)
* [$_id](#property-$_id)
* [$_lang](#property-$_lang)
* [$_no_js](#property-$_no_js)
* [$_node_folder_template](#property-$_node_folder_template)
* [$_node_item_template](#property-$_node_item_template)
* [$_selected_shops](#property-$_selected_shops)
* [$_template](#property-$_template)
* [$_template_directory](#property-$_template_directory)
* [$_title](#property-$_title)
* [$_toolbar](#property-$_toolbar)

### Methods

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

```php
const DEFAULT_HEADER_TEMPLATE = 'tree_header.tpl'
```





* Source: [classes/helper/HelperTreeShops.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L31).


### <a name="constant-DEFAULT_NODE_FOLDER_TEMPLATE"></a>DEFAULT_NODE_FOLDER_TEMPLATE

```php
const DEFAULT_NODE_FOLDER_TEMPLATE = 'tree_node_folder.tpl'
```





* Source: [classes/helper/HelperTreeShops.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L32).


### <a name="constant-DEFAULT_NODE_ITEM_TEMPLATE"></a>DEFAULT_NODE_ITEM_TEMPLATE

```php
const DEFAULT_NODE_ITEM_TEMPLATE = 'tree_node_item.tpl'
```





* Source: [classes/helper/HelperTreeShops.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L33).


### <a name="constant-DEFAULT_TEMPLATE"></a>DEFAULT_TEMPLATE

```php
const DEFAULT_TEMPLATE = 'tree.tpl'
```





* Source: [classes/helper/HelperTreeShops.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L30).


### <a name="constant-DEFAULT_TEMPLATE_DIRECTORY"></a>DEFAULT_TEMPLATE_DIRECTORY

```php
const DEFAULT_TEMPLATE_DIRECTORY = 'helpers/tree'
```





* Source: [classes/helper/HelperTreeShops.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L29).


Properties
----------


### <a name="property-$_attributes"></a>$_attributes

```php
protected mixed $_attributes
```





* Visibility: **protected**
* Source: [classes/helper/HelperTreeShops.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L35).


### <a name="property-$_context"></a>$_context

```php
private mixed $_context
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeShops.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L36).


### <a name="property-$_data"></a>$_data

```php
protected mixed $_data
```





* Visibility: **protected**
* Source: [classes/helper/HelperTreeShops.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L37).


### <a name="property-$_data_search"></a>$_data_search

```php
protected mixed $_data_search
```





* Visibility: **protected**
* Source: [classes/helper/HelperTreeShops.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L38).


### <a name="property-$_headerTemplate"></a>$_headerTemplate

```php
protected mixed $_headerTemplate
```





* Visibility: **protected**
* Source: [classes/helper/HelperTreeShops.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L39).


### <a name="property-$_id"></a>$_id

```php
private mixed $_id
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeShops.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L40).


### <a name="property-$_lang"></a>$_lang

```php
private mixed $_lang
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeShops.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L33).


### <a name="property-$_no_js"></a>$_no_js

```php
private mixed $_no_js
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeShops.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L48).


### <a name="property-$_node_folder_template"></a>$_node_folder_template

```php
protected mixed $_node_folder_template
```





* Visibility: **protected**
* Source: [classes/helper/HelperTreeShops.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L41).


### <a name="property-$_node_item_template"></a>$_node_item_template

```php
protected mixed $_node_item_template
```





* Visibility: **protected**
* Source: [classes/helper/HelperTreeShops.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L42).


### <a name="property-$_selected_shops"></a>$_selected_shops

```php
private mixed $_selected_shops
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeShops.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L34).


### <a name="property-$_template"></a>$_template

```php
protected mixed $_template
```





* Visibility: **protected**
* Source: [classes/helper/HelperTreeShops.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L43).


### <a name="property-$_template_directory"></a>$_template_directory

```php
private string $_template_directory
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeShops.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L46).


### <a name="property-$_title"></a>$_title

```php
private mixed $_title
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeShops.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L47).


### <a name="property-$_toolbar"></a>$_toolbar

```php
private \TreeToolbar $_toolbar
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeShops.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L51).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed HelperTreeShopsCore::__construct($id, $data)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L53)


#### Arguments
* $id **mixed**
* $data **mixed**



### <a name="method-__toString"></a>__toString

```php
mixed HelperTreeShopsCore::__toString()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L61)




### <a name="method-_normalizeDirectory"></a>_normalizeDirectory

```php
mixed HelperTreeShopsCore::_normalizeDirectory($directory)
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeShops.php line 442](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L442)


#### Arguments
* $directory **mixed**



### <a name="method-addAction"></a>addAction

```php
mixed HelperTreeShopsCore::addAction($action)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 326](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L326)


#### Arguments
* $action **mixed**



### <a name="method-getActions"></a>getActions

```php
mixed HelperTreeShopsCore::getActions()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L75)




### <a name="method-getAttribute"></a>getAttribute

```php
mixed HelperTreeShopsCore::getAttribute($name)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L92)


#### Arguments
* $name **mixed**



### <a name="method-getAttributes"></a>getAttributes

```php
mixed HelperTreeShopsCore::getAttributes()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L106)




### <a name="method-getContext"></a>getContext

```php
mixed HelperTreeShopsCore::getContext()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L120)




### <a name="method-getData"></a>getData

```php
mixed HelperTreeShopsCore::getData()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L154)




### <a name="method-getDataSearch"></a>getDataSearch

```php
mixed HelperTreeShopsCore::getDataSearch()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L137)




### <a name="method-getHeaderTemplate"></a>getHeaderTemplate

```php
mixed HelperTreeShopsCore::getHeaderTemplate()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L168)




### <a name="method-getId"></a>getId

```php
mixed HelperTreeShopsCore::getId()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L182)




### <a name="method-getLang"></a>getLang

```php
mixed HelperTreeShopsCore::getLang()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L60)




### <a name="method-getNodeFolderTemplate"></a>getNodeFolderTemplate

```php
mixed HelperTreeShopsCore::getNodeFolderTemplate()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 193](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L193)




### <a name="method-getNodeItemTemplate"></a>getNodeItemTemplate

```php
mixed HelperTreeShopsCore::getNodeItemTemplate()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 207](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L207)




### <a name="method-getSelectedShops"></a>getSelectedShops

```php
mixed HelperTreeShopsCore::getSelectedShops()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L93)




### <a name="method-getTemplate"></a>getTemplate

```php
mixed HelperTreeShopsCore::getTemplate()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L221)




### <a name="method-getTemplateDirectory"></a>getTemplateDirectory

```php
string HelperTreeShopsCore::getTemplateDirectory()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 243](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L243)




### <a name="method-getTemplateFile"></a>getTemplateFile

```php
mixed HelperTreeShopsCore::getTemplateFile($template)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 252](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L252)


#### Arguments
* $template **mixed**



### <a name="method-getTitle"></a>getTitle

```php
mixed HelperTreeShopsCore::getTitle()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 294](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L294)




### <a name="method-getToolbar"></a>getToolbar

```php
mixed HelperTreeShopsCore::getToolbar()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 313](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L313)




### <a name="method-removeActions"></a>removeActions

```php
mixed HelperTreeShopsCore::removeActions()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 335](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L335)




### <a name="method-render"></a>render

```php
mixed HelperTreeShopsCore::render($data)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 344](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L344)


#### Arguments
* $data **mixed**



### <a name="method-renderNodes"></a>renderNodes

```php
mixed HelperTreeShopsCore::renderNodes($data)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 394](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L394)


#### Arguments
* $data **mixed**



### <a name="method-renderToolbar"></a>renderToolbar

```php
mixed HelperTreeShopsCore::renderToolbar()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 427](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L427)




### <a name="method-setActions"></a>setActions

```php
mixed HelperTreeShopsCore::setActions($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L66)


#### Arguments
* $value **mixed**



### <a name="method-setAttribute"></a>setAttribute

```php
mixed HelperTreeShopsCore::setAttribute($name, $value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L83)


#### Arguments
* $name **mixed**
* $value **mixed**



### <a name="method-setAttributes"></a>setAttributes

```php
mixed HelperTreeShopsCore::setAttributes($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L97)


#### Arguments
* $value **mixed**



### <a name="method-setContext"></a>setContext

```php
mixed HelperTreeShopsCore::setContext($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L114)


#### Arguments
* $value **mixed**



### <a name="method-setData"></a>setData

```php
mixed HelperTreeShopsCore::setData($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L145)


#### Arguments
* $value **mixed**



### <a name="method-setDataSearch"></a>setDataSearch

```php
mixed HelperTreeShopsCore::setDataSearch($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L128)


#### Arguments
* $value **mixed**



### <a name="method-setHeaderTemplate"></a>setHeaderTemplate

```php
mixed HelperTreeShopsCore::setHeaderTemplate($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L162)


#### Arguments
* $value **mixed**



### <a name="method-setId"></a>setId

```php
mixed HelperTreeShopsCore::setId($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L176)


#### Arguments
* $value **mixed**



### <a name="method-setLang"></a>setLang

```php
mixed HelperTreeShopsCore::setLang($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L54)


#### Arguments
* $value **mixed**



### <a name="method-setNoJS"></a>setNoJS

```php
mixed HelperTreeShopsCore::setNoJS($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 282](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L282)


#### Arguments
* $value **mixed**



### <a name="method-setNodeFolderTemplate"></a>setNodeFolderTemplate

```php
mixed HelperTreeShopsCore::setNodeFolderTemplate($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 187](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L187)


#### Arguments
* $value **mixed**



### <a name="method-setNodeItemTemplate"></a>setNodeItemTemplate

```php
mixed HelperTreeShopsCore::setNodeItemTemplate($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L201)


#### Arguments
* $value **mixed**



### <a name="method-setSelectedShops"></a>setSelectedShops

```php
mixed HelperTreeShopsCore::setSelectedShops($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L84)


#### Arguments
* $value **mixed**



### <a name="method-setTemplate"></a>setTemplate

```php
mixed HelperTreeShopsCore::setTemplate($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 215](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L215)


#### Arguments
* $value **mixed**



### <a name="method-setTemplateDirectory"></a>setTemplateDirectory

```php
\Tree HelperTreeShopsCore::setTemplateDirectory($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L234)


#### Arguments
* $value **mixed**



### <a name="method-setTitle"></a>setTitle

```php
mixed HelperTreeShopsCore::setTitle($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 288](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L288)


#### Arguments
* $value **mixed**



### <a name="method-setToolbar"></a>setToolbar

```php
mixed HelperTreeShopsCore::setToolbar($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 299](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L299)


#### Arguments
* $value **mixed**



### <a name="method-useInput"></a>useInput

```php
mixed HelperTreeShopsCore::useInput()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 432](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L432)




### <a name="method-useToolbar"></a>useToolbar

```php
mixed HelperTreeShopsCore::useToolbar()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeShops.php line 437](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeShops.php#L437)



