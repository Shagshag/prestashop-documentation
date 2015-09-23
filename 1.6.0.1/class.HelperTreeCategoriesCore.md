Class HelperTreeCategoriesCore
=====================





* Class name: HelperTreeCategoriesCore
* Parent class: [TreeCore](class.TreeCore.md)
* Source: [classes/helper/HelperTreeCategories.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L27)


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
* [$_disabled_categories](#property-$_disabled_categories)
* [$_headerTemplate](#property-$_headerTemplate)
* [$_id](#property-$_id)
* [$_lang](#property-$_lang)
* [$_node_folder_template](#property-$_node_folder_template)
* [$_node_item_template](#property-$_node_item_template)
* [$_root_category](#property-$_root_category)
* [$_selected_categories](#property-$_selected_categories)
* [$_shop](#property-$_shop)
* [$_template](#property-$_template)
* [$_template_directory](#property-$_template_directory)
* [$_title](#property-$_title)
* [$_use_checkbox](#property-$_use_checkbox)
* [$_use_search](#property-$_use_search)

### Methods

* [__construct](#method-__construct)
* [__toString](#method-__toString)
* [_disableCategories](#method-_disableCategories)
* [_normalizeDirectory](#method-_normalizeDirectory)
* [addAction](#method-addAction)
* [getActions](#method-getActions)
* [getAttribute](#method-getAttribute)
* [getAttributes](#method-getAttributes)
* [getContext](#method-getContext)
* [getData](#method-getData)
* [getDisabledCategories](#method-getDisabledCategories)
* [getHeaderTemplate](#method-getHeaderTemplate)
* [getId](#method-getId)
* [getLang](#method-getLang)
* [getNodeFolderTemplate](#method-getNodeFolderTemplate)
* [getNodeItemTemplate](#method-getNodeItemTemplate)
* [getRootCategory](#method-getRootCategory)
* [getSelectedCatgories](#method-getSelectedCatgories)
* [getShop](#method-getShop)
* [getTemplate](#method-getTemplate)
* [getTemplateDirectory](#method-getTemplateDirectory)
* [getTemplateFile](#method-getTemplateFile)
* [getTitle](#method-getTitle)
* [getToolbar](#method-getToolbar)
* [render](#method-render)
* [renderNodes](#method-renderNodes)
* [renderToolbar](#method-renderToolbar)
* [setActions](#method-setActions)
* [setAttribute](#method-setAttribute)
* [setAttributes](#method-setAttributes)
* [setContext](#method-setContext)
* [setData](#method-setData)
* [setDisabledCategories](#method-setDisabledCategories)
* [setHeaderTemplate](#method-setHeaderTemplate)
* [setId](#method-setId)
* [setLang](#method-setLang)
* [setNodeFolderTemplate](#method-setNodeFolderTemplate)
* [setNodeItemTemplate](#method-setNodeItemTemplate)
* [setRootCategory](#method-setRootCategory)
* [setSelectedCategories](#method-setSelectedCategories)
* [setShop](#method-setShop)
* [setTemplate](#method-setTemplate)
* [setTemplateDirectory](#method-setTemplateDirectory)
* [setTitle](#method-setTitle)
* [setToolbar](#method-setToolbar)
* [setUseCheckBox](#method-setUseCheckBox)
* [setUseSearch](#method-setUseSearch)
* [useCheckBox](#method-useCheckBox)
* [useInput](#method-useInput)
* [useSearch](#method-useSearch)
* [useToolbar](#method-useToolbar)


Constants
----------


### <a name="constant-DEFAULT_HEADER_TEMPLATE"></a>DEFAULT_HEADER_TEMPLATE

```php
const DEFAULT_HEADER_TEMPLATE = 'tree_header.tpl'
```





* Source: [classes/helper/HelperTreeCategories.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L31).


### <a name="constant-DEFAULT_NODE_FOLDER_TEMPLATE"></a>DEFAULT_NODE_FOLDER_TEMPLATE

```php
const DEFAULT_NODE_FOLDER_TEMPLATE = 'tree_node_folder.tpl'
```





* Source: [classes/helper/HelperTreeCategories.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L32).


### <a name="constant-DEFAULT_NODE_ITEM_TEMPLATE"></a>DEFAULT_NODE_ITEM_TEMPLATE

```php
const DEFAULT_NODE_ITEM_TEMPLATE = 'tree_node_item.tpl'
```





* Source: [classes/helper/HelperTreeCategories.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L33).


### <a name="constant-DEFAULT_TEMPLATE"></a>DEFAULT_TEMPLATE

```php
const DEFAULT_TEMPLATE = 'tree.tpl'
```





* Source: [classes/helper/HelperTreeCategories.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L30).


### <a name="constant-DEFAULT_TEMPLATE_DIRECTORY"></a>DEFAULT_TEMPLATE_DIRECTORY

```php
const DEFAULT_TEMPLATE_DIRECTORY = 'helpers/tree'
```





* Source: [classes/helper/HelperTreeCategories.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L29).


Properties
----------


### <a name="property-$_attributes"></a>$_attributes

```php
protected mixed $_attributes
```





* Visibility: **protected**
* Source: [classes/helper/HelperTreeCategories.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L35).


### <a name="property-$_context"></a>$_context

```php
private mixed $_context
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L36).


### <a name="property-$_data"></a>$_data

```php
protected mixed $_data
```





* Visibility: **protected**
* Source: [classes/helper/HelperTreeCategories.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L37).


### <a name="property-$_disabled_categories"></a>$_disabled_categories

```php
private mixed $_disabled_categories
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L33).


### <a name="property-$_headerTemplate"></a>$_headerTemplate

```php
protected mixed $_headerTemplate
```





* Visibility: **protected**
* Source: [classes/helper/HelperTreeCategories.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L38).


### <a name="property-$_id"></a>$_id

```php
private mixed $_id
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L39).


### <a name="property-$_lang"></a>$_lang

```php
private mixed $_lang
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L34).


### <a name="property-$_node_folder_template"></a>$_node_folder_template

```php
protected mixed $_node_folder_template
```





* Visibility: **protected**
* Source: [classes/helper/HelperTreeCategories.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L40).


### <a name="property-$_node_item_template"></a>$_node_item_template

```php
protected mixed $_node_item_template
```





* Visibility: **protected**
* Source: [classes/helper/HelperTreeCategories.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L41).


### <a name="property-$_root_category"></a>$_root_category

```php
private mixed $_root_category
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L35).


### <a name="property-$_selected_categories"></a>$_selected_categories

```php
private mixed $_selected_categories
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L36).


### <a name="property-$_shop"></a>$_shop

```php
private mixed $_shop
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L37).


### <a name="property-$_template"></a>$_template

```php
protected mixed $_template
```





* Visibility: **protected**
* Source: [classes/helper/HelperTreeCategories.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L42).


### <a name="property-$_template_directory"></a>$_template_directory

```php
private mixed $_template_directory
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L43).


### <a name="property-$_title"></a>$_title

```php
private mixed $_title
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L44).


### <a name="property-$_use_checkbox"></a>$_use_checkbox

```php
private mixed $_use_checkbox
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L38).


### <a name="property-$_use_search"></a>$_use_search

```php
private mixed $_use_search
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L39).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed HelperTreeCategoriesCore::__construct($id, $data)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L46)


#### Arguments
* $id **mixed**
* $data **mixed**



### <a name="method-__toString"></a>__toString

```php
mixed HelperTreeCategoriesCore::__toString()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L54)




### <a name="method-_disableCategories"></a>_disableCategories

```php
mixed HelperTreeCategoriesCore::_disableCategories($categories, $disabled_categories)
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 257](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L257)


#### Arguments
* $categories **mixed**
* $disabled_categories **mixed**



### <a name="method-_normalizeDirectory"></a>_normalizeDirectory

```php
mixed HelperTreeCategoriesCore::_normalizeDirectory($directory)
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 398](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L398)


#### Arguments
* $directory **mixed**



### <a name="method-addAction"></a>addAction

```php
mixed HelperTreeCategoriesCore::addAction($action)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 291](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L291)


#### Arguments
* $action **mixed**



### <a name="method-getActions"></a>getActions

```php
mixed HelperTreeCategoriesCore::getActions()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L68)




### <a name="method-getAttribute"></a>getAttribute

```php
mixed HelperTreeCategoriesCore::getAttribute($name)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L85)


#### Arguments
* $name **mixed**



### <a name="method-getAttributes"></a>getAttributes

```php
mixed HelperTreeCategoriesCore::getAttributes()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L99)




### <a name="method-getContext"></a>getContext

```php
mixed HelperTreeCategoriesCore::getContext()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L113)




### <a name="method-getData"></a>getData

```php
mixed HelperTreeCategoriesCore::getData()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L130)




### <a name="method-getDisabledCategories"></a>getDisabledCategories

```php
mixed HelperTreeCategoriesCore::getDisabledCategories()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L71)




### <a name="method-getHeaderTemplate"></a>getHeaderTemplate

```php
mixed HelperTreeCategoriesCore::getHeaderTemplate()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L144)




### <a name="method-getId"></a>getId

```php
mixed HelperTreeCategoriesCore::getId()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L158)




### <a name="method-getLang"></a>getLang

```php
mixed HelperTreeCategoriesCore::getLang()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L82)




### <a name="method-getNodeFolderTemplate"></a>getNodeFolderTemplate

```php
mixed HelperTreeCategoriesCore::getNodeFolderTemplate()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L169)




### <a name="method-getNodeItemTemplate"></a>getNodeItemTemplate

```php
mixed HelperTreeCategoriesCore::getNodeItemTemplate()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 183](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L183)




### <a name="method-getRootCategory"></a>getRootCategory

```php
mixed HelperTreeCategoriesCore::getRootCategory()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L115)




### <a name="method-getSelectedCatgories"></a>getSelectedCatgories

```php
mixed HelperTreeCategoriesCore::getSelectedCatgories()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L133)




### <a name="method-getShop"></a>getShop

```php
mixed HelperTreeCategoriesCore::getShop()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L147)




### <a name="method-getTemplate"></a>getTemplate

```php
mixed HelperTreeCategoriesCore::getTemplate()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 197](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L197)




### <a name="method-getTemplateDirectory"></a>getTemplateDirectory

```php
mixed HelperTreeCategoriesCore::getTemplateDirectory()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 211](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L211)




### <a name="method-getTemplateFile"></a>getTemplateFile

```php
mixed HelperTreeCategoriesCore::getTemplateFile($template)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 220](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L220)


#### Arguments
* $template **mixed**



### <a name="method-getTitle"></a>getTitle

```php
mixed HelperTreeCategoriesCore::getTitle()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 264](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L264)




### <a name="method-getToolbar"></a>getToolbar

```php
mixed HelperTreeCategoriesCore::getToolbar()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 283](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L283)




### <a name="method-render"></a>render

```php
mixed HelperTreeCategoriesCore::render($data)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 300](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L300)


#### Arguments
* $data **mixed**



### <a name="method-renderNodes"></a>renderNodes

```php
mixed HelperTreeCategoriesCore::renderNodes($data)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 350](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L350)


#### Arguments
* $data **mixed**



### <a name="method-renderToolbar"></a>renderToolbar

```php
mixed HelperTreeCategoriesCore::renderToolbar()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 383](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L383)




### <a name="method-setActions"></a>setActions

```php
mixed HelperTreeCategoriesCore::setActions($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L59)


#### Arguments
* $value **mixed**



### <a name="method-setAttribute"></a>setAttribute

```php
mixed HelperTreeCategoriesCore::setAttribute($name, $value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L76)


#### Arguments
* $name **mixed**
* $value **mixed**



### <a name="method-setAttributes"></a>setAttributes

```php
mixed HelperTreeCategoriesCore::setAttributes($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L90)


#### Arguments
* $value **mixed**



### <a name="method-setContext"></a>setContext

```php
mixed HelperTreeCategoriesCore::setContext($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L107)


#### Arguments
* $value **mixed**



### <a name="method-setData"></a>setData

```php
mixed HelperTreeCategoriesCore::setData($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L121)


#### Arguments
* $value **mixed**



### <a name="method-setDisabledCategories"></a>setDisabledCategories

```php
mixed HelperTreeCategoriesCore::setDisabledCategories($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L65)


#### Arguments
* $value **mixed**



### <a name="method-setHeaderTemplate"></a>setHeaderTemplate

```php
mixed HelperTreeCategoriesCore::setHeaderTemplate($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L138)


#### Arguments
* $value **mixed**



### <a name="method-setId"></a>setId

```php
mixed HelperTreeCategoriesCore::setId($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L152)


#### Arguments
* $value **mixed**



### <a name="method-setLang"></a>setLang

```php
mixed HelperTreeCategoriesCore::setLang($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L76)


#### Arguments
* $value **mixed**



### <a name="method-setNodeFolderTemplate"></a>setNodeFolderTemplate

```php
mixed HelperTreeCategoriesCore::setNodeFolderTemplate($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L163)


#### Arguments
* $value **mixed**



### <a name="method-setNodeItemTemplate"></a>setNodeItemTemplate

```php
mixed HelperTreeCategoriesCore::setNodeItemTemplate($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 177](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L177)


#### Arguments
* $value **mixed**



### <a name="method-setRootCategory"></a>setRootCategory

```php
mixed HelperTreeCategoriesCore::setRootCategory($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L106)


#### Arguments
* $value **mixed**



### <a name="method-setSelectedCategories"></a>setSelectedCategories

```php
mixed HelperTreeCategoriesCore::setSelectedCategories($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L124)


#### Arguments
* $value **mixed**



### <a name="method-setShop"></a>setShop

```php
mixed HelperTreeCategoriesCore::setShop($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L141)


#### Arguments
* $value **mixed**



### <a name="method-setTemplate"></a>setTemplate

```php
mixed HelperTreeCategoriesCore::setTemplate($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L191)


#### Arguments
* $value **mixed**



### <a name="method-setTemplateDirectory"></a>setTemplateDirectory

```php
mixed HelperTreeCategoriesCore::setTemplateDirectory($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 205](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L205)


#### Arguments
* $value **mixed**



### <a name="method-setTitle"></a>setTitle

```php
mixed HelperTreeCategoriesCore::setTitle($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 258](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L258)


#### Arguments
* $value **mixed**



### <a name="method-setToolbar"></a>setToolbar

```php
mixed HelperTreeCategoriesCore::setToolbar($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 269](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L269)


#### Arguments
* $value **mixed**



### <a name="method-setUseCheckBox"></a>setUseCheckBox

```php
mixed HelperTreeCategoriesCore::setUseCheckBox($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L174)


#### Arguments
* $value **mixed**



### <a name="method-setUseSearch"></a>setUseSearch

```php
mixed HelperTreeCategoriesCore::setUseSearch($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L180)


#### Arguments
* $value **mixed**



### <a name="method-useCheckBox"></a>useCheckBox

```php
mixed HelperTreeCategoriesCore::useCheckBox()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L186)




### <a name="method-useInput"></a>useInput

```php
mixed HelperTreeCategoriesCore::useInput()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 388](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L388)




### <a name="method-useSearch"></a>useSearch

```php
mixed HelperTreeCategoriesCore::useSearch()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L191)




### <a name="method-useToolbar"></a>useToolbar

```php
mixed HelperTreeCategoriesCore::useToolbar()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 393](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/helper/HelperTreeCategories.php#L393)



