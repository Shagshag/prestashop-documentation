Class TreeCore
=====================





* Class name: TreeCore
* Source: [classes/tree/Tree.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L27)


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
* [$_headerTemplate](#property-$_headerTemplate)
* [$_id](#property-$_id)
* [$_node_folder_template](#property-$_node_folder_template)
* [$_node_item_template](#property-$_node_item_template)
* [$_template](#property-$_template)
* [$_template_directory](#property-$_template_directory)
* [$_title](#property-$_title)

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
* [setHeaderTemplate](#method-setHeaderTemplate)
* [setId](#method-setId)
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





* Source: [classes/tree/Tree.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L31).


### <a name="constant-DEFAULT_NODE_FOLDER_TEMPLATE"></a>DEFAULT_NODE_FOLDER_TEMPLATE

```php
const DEFAULT_NODE_FOLDER_TEMPLATE = 'tree_node_folder.tpl'
```





* Source: [classes/tree/Tree.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L32).


### <a name="constant-DEFAULT_NODE_ITEM_TEMPLATE"></a>DEFAULT_NODE_ITEM_TEMPLATE

```php
const DEFAULT_NODE_ITEM_TEMPLATE = 'tree_node_item.tpl'
```





* Source: [classes/tree/Tree.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L33).


### <a name="constant-DEFAULT_TEMPLATE"></a>DEFAULT_TEMPLATE

```php
const DEFAULT_TEMPLATE = 'tree.tpl'
```





* Source: [classes/tree/Tree.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L30).


### <a name="constant-DEFAULT_TEMPLATE_DIRECTORY"></a>DEFAULT_TEMPLATE_DIRECTORY

```php
const DEFAULT_TEMPLATE_DIRECTORY = 'helpers/tree'
```





* Source: [classes/tree/Tree.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L29).


Properties
----------


### <a name="property-$_attributes"></a>$_attributes

```php
protected mixed $_attributes
```





* Visibility: **protected**
* Source: [classes/tree/Tree.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L35).


### <a name="property-$_context"></a>$_context

```php
private mixed $_context
```





* Visibility: **private**
* Source: [classes/tree/Tree.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L36).


### <a name="property-$_data"></a>$_data

```php
protected mixed $_data
```





* Visibility: **protected**
* Source: [classes/tree/Tree.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L37).


### <a name="property-$_headerTemplate"></a>$_headerTemplate

```php
protected mixed $_headerTemplate
```





* Visibility: **protected**
* Source: [classes/tree/Tree.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L38).


### <a name="property-$_id"></a>$_id

```php
private mixed $_id
```





* Visibility: **private**
* Source: [classes/tree/Tree.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L39).


### <a name="property-$_node_folder_template"></a>$_node_folder_template

```php
protected mixed $_node_folder_template
```





* Visibility: **protected**
* Source: [classes/tree/Tree.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L40).


### <a name="property-$_node_item_template"></a>$_node_item_template

```php
protected mixed $_node_item_template
```





* Visibility: **protected**
* Source: [classes/tree/Tree.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L41).


### <a name="property-$_template"></a>$_template

```php
protected mixed $_template
```





* Visibility: **protected**
* Source: [classes/tree/Tree.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L42).


### <a name="property-$_template_directory"></a>$_template_directory

```php
private mixed $_template_directory
```





* Visibility: **private**
* Source: [classes/tree/Tree.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L43).


### <a name="property-$_title"></a>$_title

```php
private mixed $_title
```





* Visibility: **private**
* Source: [classes/tree/Tree.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L44).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed TreeCore::__construct($id, $data)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L46)


#### Arguments
* $id **mixed**
* $data **mixed**



### <a name="method-__toString"></a>__toString

```php
mixed TreeCore::__toString()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L54)




### <a name="method-_normalizeDirectory"></a>_normalizeDirectory

```php
mixed TreeCore::_normalizeDirectory($directory)
```





* Visibility: **private**
* Source: [classes/tree/Tree.php line 404](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L404)


#### Arguments
* $directory **mixed**



### <a name="method-addAction"></a>addAction

```php
mixed TreeCore::addAction($action)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 291](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L291)


#### Arguments
* $action **mixed**



### <a name="method-getActions"></a>getActions

```php
mixed TreeCore::getActions()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L68)




### <a name="method-getAttribute"></a>getAttribute

```php
mixed TreeCore::getAttribute($name)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L85)


#### Arguments
* $name **mixed**



### <a name="method-getAttributes"></a>getAttributes

```php
mixed TreeCore::getAttributes()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L99)




### <a name="method-getContext"></a>getContext

```php
mixed TreeCore::getContext()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L113)




### <a name="method-getData"></a>getData

```php
mixed TreeCore::getData()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L130)




### <a name="method-getHeaderTemplate"></a>getHeaderTemplate

```php
mixed TreeCore::getHeaderTemplate()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L144)




### <a name="method-getId"></a>getId

```php
mixed TreeCore::getId()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L158)




### <a name="method-getNodeFolderTemplate"></a>getNodeFolderTemplate

```php
mixed TreeCore::getNodeFolderTemplate()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L169)




### <a name="method-getNodeItemTemplate"></a>getNodeItemTemplate

```php
mixed TreeCore::getNodeItemTemplate()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 183](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L183)




### <a name="method-getTemplate"></a>getTemplate

```php
mixed TreeCore::getTemplate()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 197](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L197)




### <a name="method-getTemplateDirectory"></a>getTemplateDirectory

```php
mixed TreeCore::getTemplateDirectory()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 211](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L211)




### <a name="method-getTemplateFile"></a>getTemplateFile

```php
mixed TreeCore::getTemplateFile($template)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 220](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L220)


#### Arguments
* $template **mixed**



### <a name="method-getTitle"></a>getTitle

```php
mixed TreeCore::getTitle()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 264](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L264)




### <a name="method-getToolbar"></a>getToolbar

```php
mixed TreeCore::getToolbar()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 283](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L283)




### <a name="method-removeActions"></a>removeActions

```php
mixed TreeCore::removeActions()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 300](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L300)




### <a name="method-render"></a>render

```php
mixed TreeCore::render($data)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 309](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L309)


#### Arguments
* $data **mixed**



### <a name="method-renderNodes"></a>renderNodes

```php
mixed TreeCore::renderNodes($data)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 356](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L356)


#### Arguments
* $data **mixed**



### <a name="method-renderToolbar"></a>renderToolbar

```php
mixed TreeCore::renderToolbar()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 389](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L389)




### <a name="method-setActions"></a>setActions

```php
mixed TreeCore::setActions($value)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L59)


#### Arguments
* $value **mixed**



### <a name="method-setAttribute"></a>setAttribute

```php
mixed TreeCore::setAttribute($name, $value)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L76)


#### Arguments
* $name **mixed**
* $value **mixed**



### <a name="method-setAttributes"></a>setAttributes

```php
mixed TreeCore::setAttributes($value)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L90)


#### Arguments
* $value **mixed**



### <a name="method-setContext"></a>setContext

```php
mixed TreeCore::setContext($value)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L107)


#### Arguments
* $value **mixed**



### <a name="method-setData"></a>setData

```php
mixed TreeCore::setData($value)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L121)


#### Arguments
* $value **mixed**



### <a name="method-setHeaderTemplate"></a>setHeaderTemplate

```php
mixed TreeCore::setHeaderTemplate($value)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L138)


#### Arguments
* $value **mixed**



### <a name="method-setId"></a>setId

```php
mixed TreeCore::setId($value)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L152)


#### Arguments
* $value **mixed**



### <a name="method-setNodeFolderTemplate"></a>setNodeFolderTemplate

```php
mixed TreeCore::setNodeFolderTemplate($value)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L163)


#### Arguments
* $value **mixed**



### <a name="method-setNodeItemTemplate"></a>setNodeItemTemplate

```php
mixed TreeCore::setNodeItemTemplate($value)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 177](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L177)


#### Arguments
* $value **mixed**



### <a name="method-setTemplate"></a>setTemplate

```php
mixed TreeCore::setTemplate($value)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L191)


#### Arguments
* $value **mixed**



### <a name="method-setTemplateDirectory"></a>setTemplateDirectory

```php
mixed TreeCore::setTemplateDirectory($value)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 205](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L205)


#### Arguments
* $value **mixed**



### <a name="method-setTitle"></a>setTitle

```php
mixed TreeCore::setTitle($value)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 258](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L258)


#### Arguments
* $value **mixed**



### <a name="method-setToolbar"></a>setToolbar

```php
mixed TreeCore::setToolbar($value)
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 269](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L269)


#### Arguments
* $value **mixed**



### <a name="method-useInput"></a>useInput

```php
mixed TreeCore::useInput()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 394](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L394)




### <a name="method-useToolbar"></a>useToolbar

```php
mixed TreeCore::useToolbar()
```





* Visibility: **public**
* Source: [classes/tree/Tree.php line 399](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/tree/Tree.php#L399)



