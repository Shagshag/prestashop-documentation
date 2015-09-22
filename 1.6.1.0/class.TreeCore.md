Class TreeCore
=====================





* Class name: TreeCore
* Source: [classes/tree/Tree.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L27)


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
* [$_no_js](#property-$_no_js)
* [$_node_folder_template](#property-$_node_folder_template)
* [$_node_item_template](#property-$_node_item_template)
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
* [getNodeFolderTemplate](#method-getNodeFolderTemplate)
* [getNodeItemTemplate](#method-getNodeItemTemplate)
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
* [setNoJS](#method-setNoJS)
* [setNodeFolderTemplate](#method-setNodeFolderTemplate)
* [setNodeItemTemplate](#method-setNodeItemTemplate)
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





* Source: [classes/tree/Tree.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L31).


### <a name="constant-DEFAULT_NODE_FOLDER_TEMPLATE"></a>DEFAULT_NODE_FOLDER_TEMPLATE

```php
const DEFAULT_NODE_FOLDER_TEMPLATE = 'tree_node_folder.tpl'
```





* Source: [classes/tree/Tree.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L32).


### <a name="constant-DEFAULT_NODE_ITEM_TEMPLATE"></a>DEFAULT_NODE_ITEM_TEMPLATE

```php
const DEFAULT_NODE_ITEM_TEMPLATE = 'tree_node_item.tpl'
```





* Source: [classes/tree/Tree.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L33).


### <a name="constant-DEFAULT_TEMPLATE"></a>DEFAULT_TEMPLATE

```php
const DEFAULT_TEMPLATE = 'tree.tpl'
```





* Source: [classes/tree/Tree.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L30).


### <a name="constant-DEFAULT_TEMPLATE_DIRECTORY"></a>DEFAULT_TEMPLATE_DIRECTORY

```php
const DEFAULT_TEMPLATE_DIRECTORY = 'helpers/tree'
```





* Source: [classes/tree/Tree.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L29).


Properties
----------


### <a name="property-$_attributes"></a>$_attributes

```php
protected mixed $_attributes
```





* Visibility: **protected**
* Source: [classes/tree/Tree.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L35).


### <a name="property-$_context"></a>$_context

```php
private mixed $_context
```





* Visibility: **private**
* Source: [classes/tree/Tree.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L36).


### <a name="property-$_data"></a>$_data

```php
protected mixed $_data
```





* Visibility: **protected**
* Source: [classes/tree/Tree.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L37).


### <a name="property-$_data_search"></a>$_data_search

```php
protected mixed $_data_search
```





* Visibility: **protected**
* Source: [classes/tree/Tree.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L38).


### <a name="property-$_headerTemplate"></a>$_headerTemplate

```php
protected mixed $_headerTemplate
```





* Visibility: **protected**
* Source: [classes/tree/Tree.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L39).


### <a name="property-$_id"></a>$_id

```php
private mixed $_id
```





* Visibility: **private**
* Source: [classes/tree/Tree.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L40).


### <a name="property-$_no_js"></a>$_no_js

```php
private mixed $_no_js
```





* Visibility: **private**
* Source: [classes/tree/Tree.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L48).


### <a name="property-$_node_folder_template"></a>$_node_folder_template

```php
protected mixed $_node_folder_template
```





* Visibility: **protected**
* Source: [classes/tree/Tree.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L41).


### <a name="property-$_node_item_template"></a>$_node_item_template

```php
protected mixed $_node_item_template
```





* Visibility: **protected**
* Source: [classes/tree/Tree.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L42).


### <a name="property-$_template"></a>$_template

```php
protected mixed $_template
```





* Visibility: **protected**
* Source: [classes/tree/Tree.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L43).


### <a name="property-$_template_directory"></a>$_template_directory

```php
private string $_template_directory
```





* Visibility: **private**
* Source: [classes/tree/Tree.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L46).


### <a name="property-$_title"></a>$_title

```php
private mixed $_title
```





* Visibility: **private**
* Source: [classes/tree/Tree.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L47).


### <a name="property-$_toolbar"></a>$_toolbar

```php
private \TreeToolbar $_toolbar
```





* Visibility: **private**
* Source: [classes/tree/Tree.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L51).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed TreeCore::__construct($id, $data)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L53)


#### Arguments
* $id **mixed**
* $data **mixed**



### <a name="method-__toString"></a>__toString

```php
mixed TreeCore::__toString()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L61)




### <a name="method-_normalizeDirectory"></a>_normalizeDirectory

```php
mixed TreeCore::_normalizeDirectory($directory)
```





* Visibility: **private**
* Source: [classes/tree/Tree.php line 442](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L442)


#### Arguments
* $directory **mixed**



### <a name="method-addAction"></a>addAction

```php
mixed TreeCore::addAction($action)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 326](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L326)


#### Arguments
* $action **mixed**



### <a name="method-getActions"></a>getActions

```php
mixed TreeCore::getActions()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L75)




### <a name="method-getAttribute"></a>getAttribute

```php
mixed TreeCore::getAttribute($name)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L92)


#### Arguments
* $name **mixed**



### <a name="method-getAttributes"></a>getAttributes

```php
mixed TreeCore::getAttributes()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L106)




### <a name="method-getContext"></a>getContext

```php
mixed TreeCore::getContext()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L120)




### <a name="method-getData"></a>getData

```php
mixed TreeCore::getData()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L154)




### <a name="method-getDataSearch"></a>getDataSearch

```php
mixed TreeCore::getDataSearch()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L137)




### <a name="method-getHeaderTemplate"></a>getHeaderTemplate

```php
mixed TreeCore::getHeaderTemplate()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L168)




### <a name="method-getId"></a>getId

```php
mixed TreeCore::getId()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L182)




### <a name="method-getNodeFolderTemplate"></a>getNodeFolderTemplate

```php
mixed TreeCore::getNodeFolderTemplate()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 193](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L193)




### <a name="method-getNodeItemTemplate"></a>getNodeItemTemplate

```php
mixed TreeCore::getNodeItemTemplate()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 207](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L207)




### <a name="method-getTemplate"></a>getTemplate

```php
mixed TreeCore::getTemplate()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L221)




### <a name="method-getTemplateDirectory"></a>getTemplateDirectory

```php
string TreeCore::getTemplateDirectory()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 243](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L243)




### <a name="method-getTemplateFile"></a>getTemplateFile

```php
mixed TreeCore::getTemplateFile($template)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 252](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L252)


#### Arguments
* $template **mixed**



### <a name="method-getTitle"></a>getTitle

```php
mixed TreeCore::getTitle()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 294](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L294)




### <a name="method-getToolbar"></a>getToolbar

```php
mixed TreeCore::getToolbar()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 313](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L313)




### <a name="method-removeActions"></a>removeActions

```php
mixed TreeCore::removeActions()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 335](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L335)




### <a name="method-render"></a>render

```php
mixed TreeCore::render($data)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 344](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L344)


#### Arguments
* $data **mixed**



### <a name="method-renderNodes"></a>renderNodes

```php
mixed TreeCore::renderNodes($data)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 394](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L394)


#### Arguments
* $data **mixed**



### <a name="method-renderToolbar"></a>renderToolbar

```php
mixed TreeCore::renderToolbar()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 427](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L427)




### <a name="method-setActions"></a>setActions

```php
mixed TreeCore::setActions($value)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L66)


#### Arguments
* $value **mixed**



### <a name="method-setAttribute"></a>setAttribute

```php
mixed TreeCore::setAttribute($name, $value)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L83)


#### Arguments
* $name **mixed**
* $value **mixed**



### <a name="method-setAttributes"></a>setAttributes

```php
mixed TreeCore::setAttributes($value)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L97)


#### Arguments
* $value **mixed**



### <a name="method-setContext"></a>setContext

```php
mixed TreeCore::setContext($value)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L114)


#### Arguments
* $value **mixed**



### <a name="method-setData"></a>setData

```php
mixed TreeCore::setData($value)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L145)


#### Arguments
* $value **mixed**



### <a name="method-setDataSearch"></a>setDataSearch

```php
mixed TreeCore::setDataSearch($value)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L128)


#### Arguments
* $value **mixed**



### <a name="method-setHeaderTemplate"></a>setHeaderTemplate

```php
mixed TreeCore::setHeaderTemplate($value)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L162)


#### Arguments
* $value **mixed**



### <a name="method-setId"></a>setId

```php
mixed TreeCore::setId($value)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L176)


#### Arguments
* $value **mixed**



### <a name="method-setNoJS"></a>setNoJS

```php
mixed TreeCore::setNoJS($value)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 282](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L282)


#### Arguments
* $value **mixed**



### <a name="method-setNodeFolderTemplate"></a>setNodeFolderTemplate

```php
mixed TreeCore::setNodeFolderTemplate($value)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 187](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L187)


#### Arguments
* $value **mixed**



### <a name="method-setNodeItemTemplate"></a>setNodeItemTemplate

```php
mixed TreeCore::setNodeItemTemplate($value)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L201)


#### Arguments
* $value **mixed**



### <a name="method-setTemplate"></a>setTemplate

```php
mixed TreeCore::setTemplate($value)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 215](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L215)


#### Arguments
* $value **mixed**



### <a name="method-setTemplateDirectory"></a>setTemplateDirectory

```php
\Tree TreeCore::setTemplateDirectory($value)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L234)


#### Arguments
* $value **mixed**



### <a name="method-setTitle"></a>setTitle

```php
mixed TreeCore::setTitle($value)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 288](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L288)


#### Arguments
* $value **mixed**



### <a name="method-setToolbar"></a>setToolbar

```php
mixed TreeCore::setToolbar($value)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 299](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L299)


#### Arguments
* $value **mixed**



### <a name="method-useInput"></a>useInput

```php
mixed TreeCore::useInput()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 432](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L432)




### <a name="method-useToolbar"></a>useToolbar

```php
mixed TreeCore::useToolbar()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 437](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tree/Tree.php#L437)



