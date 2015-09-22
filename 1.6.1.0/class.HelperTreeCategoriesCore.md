Class HelperTreeCategoriesCore
=====================





* Class name: HelperTreeCategoriesCore
* Parent class: [TreeCore](class.TreeCore.md)
* Source: [classes/helper/HelperTreeCategories.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L27)


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
* [$_children_only](#property-$_children_only)
* [$_context](#property-$_context)
* [$_data](#property-$_data)
* [$_data_search](#property-$_data_search)
* [$_disabled_categories](#property-$_disabled_categories)
* [$_full_tree](#property-$_full_tree)
* [$_headerTemplate](#property-$_headerTemplate)
* [$_id](#property-$_id)
* [$_input_name](#property-$_input_name)
* [$_lang](#property-$_lang)
* [$_no_js](#property-$_no_js)
* [$_node_folder_template](#property-$_node_folder_template)
* [$_node_item_template](#property-$_node_item_template)
* [$_root_category](#property-$_root_category)
* [$_selected_categories](#property-$_selected_categories)
* [$_shop](#property-$_shop)
* [$_template](#property-$_template)
* [$_template_directory](#property-$_template_directory)
* [$_title](#property-$_title)
* [$_toolbar](#property-$_toolbar)
* [$_use_checkbox](#property-$_use_checkbox)
* [$_use_search](#property-$_use_search)
* [$_use_shop_restriction](#property-$_use_shop_restriction)

### Methods

* [__construct](#method-__construct)
* [__toString](#method-__toString)
* [_disableCategories](#method-_disableCategories)
* [_getSelectedChildNumbers](#method-_getSelectedChildNumbers)
* [_normalizeDirectory](#method-_normalizeDirectory)
* [addAction](#method-addAction)
* [fillTree](#method-fillTree)
* [getActions](#method-getActions)
* [getAttribute](#method-getAttribute)
* [getAttributes](#method-getAttributes)
* [getContext](#method-getContext)
* [getData](#method-getData)
* [getDataSearch](#method-getDataSearch)
* [getDisabledCategories](#method-getDisabledCategories)
* [getFullTree](#method-getFullTree)
* [getHeaderTemplate](#method-getHeaderTemplate)
* [getId](#method-getId)
* [getInputName](#method-getInputName)
* [getLang](#method-getLang)
* [getNodeFolderTemplate](#method-getNodeFolderTemplate)
* [getNodeItemTemplate](#method-getNodeItemTemplate)
* [getRootCategory](#method-getRootCategory)
* [getSelectedCategories](#method-getSelectedCategories)
* [getShop](#method-getShop)
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
* [setChildrenOnly](#method-setChildrenOnly)
* [setContext](#method-setContext)
* [setData](#method-setData)
* [setDataSearch](#method-setDataSearch)
* [setDisabledCategories](#method-setDisabledCategories)
* [setFullTree](#method-setFullTree)
* [setHeaderTemplate](#method-setHeaderTemplate)
* [setId](#method-setId)
* [setInputName](#method-setInputName)
* [setLang](#method-setLang)
* [setNoJS](#method-setNoJS)
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
* [setUseShopRestriction](#method-setUseShopRestriction)
* [useCheckBox](#method-useCheckBox)
* [useInput](#method-useInput)
* [useSearch](#method-useSearch)
* [useShopRestriction](#method-useShopRestriction)
* [useToolbar](#method-useToolbar)


Constants
----------


### <a name="constant-DEFAULT_HEADER_TEMPLATE"></a>DEFAULT_HEADER_TEMPLATE

```php
const DEFAULT_HEADER_TEMPLATE = 'tree_header.tpl'
```





* Source: [classes/helper/HelperTreeCategories.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L31).


### <a name="constant-DEFAULT_NODE_FOLDER_TEMPLATE"></a>DEFAULT_NODE_FOLDER_TEMPLATE

```php
const DEFAULT_NODE_FOLDER_TEMPLATE = 'tree_node_folder.tpl'
```





* Source: [classes/helper/HelperTreeCategories.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L32).


### <a name="constant-DEFAULT_NODE_ITEM_TEMPLATE"></a>DEFAULT_NODE_ITEM_TEMPLATE

```php
const DEFAULT_NODE_ITEM_TEMPLATE = 'tree_node_item.tpl'
```





* Source: [classes/helper/HelperTreeCategories.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L33).


### <a name="constant-DEFAULT_TEMPLATE"></a>DEFAULT_TEMPLATE

```php
const DEFAULT_TEMPLATE = 'tree.tpl'
```





* Source: [classes/helper/HelperTreeCategories.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L30).


### <a name="constant-DEFAULT_TEMPLATE_DIRECTORY"></a>DEFAULT_TEMPLATE_DIRECTORY

```php
const DEFAULT_TEMPLATE_DIRECTORY = 'helpers/tree'
```





* Source: [classes/helper/HelperTreeCategories.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L29).


Properties
----------


### <a name="property-$_attributes"></a>$_attributes

```php
protected mixed $_attributes
```





* Visibility: **protected**
* Source: [classes/helper/HelperTreeCategories.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L35).


### <a name="property-$_children_only"></a>$_children_only

```php
private mixed $_children_only = false
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L43).


### <a name="property-$_context"></a>$_context

```php
private mixed $_context
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L36).


### <a name="property-$_data"></a>$_data

```php
protected mixed $_data
```





* Visibility: **protected**
* Source: [classes/helper/HelperTreeCategories.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L37).


### <a name="property-$_data_search"></a>$_data_search

```php
protected mixed $_data_search
```





* Visibility: **protected**
* Source: [classes/helper/HelperTreeCategories.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L38).


### <a name="property-$_disabled_categories"></a>$_disabled_categories

```php
private mixed $_disabled_categories
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L33).


### <a name="property-$_full_tree"></a>$_full_tree

```php
private mixed $_full_tree = false
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L38).


### <a name="property-$_headerTemplate"></a>$_headerTemplate

```php
protected mixed $_headerTemplate
```





* Visibility: **protected**
* Source: [classes/helper/HelperTreeCategories.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L39).


### <a name="property-$_id"></a>$_id

```php
private mixed $_id
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L40).


### <a name="property-$_input_name"></a>$_input_name

```php
private mixed $_input_name
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L34).


### <a name="property-$_lang"></a>$_lang

```php
private mixed $_lang
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L35).


### <a name="property-$_no_js"></a>$_no_js

```php
private mixed $_no_js
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L48).


### <a name="property-$_node_folder_template"></a>$_node_folder_template

```php
protected mixed $_node_folder_template
```





* Visibility: **protected**
* Source: [classes/helper/HelperTreeCategories.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L41).


### <a name="property-$_node_item_template"></a>$_node_item_template

```php
protected mixed $_node_item_template
```





* Visibility: **protected**
* Source: [classes/helper/HelperTreeCategories.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L42).


### <a name="property-$_root_category"></a>$_root_category

```php
private mixed $_root_category
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L36).


### <a name="property-$_selected_categories"></a>$_selected_categories

```php
private mixed $_selected_categories
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L37).


### <a name="property-$_shop"></a>$_shop

```php
private mixed $_shop
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L39).


### <a name="property-$_template"></a>$_template

```php
protected mixed $_template
```





* Visibility: **protected**
* Source: [classes/helper/HelperTreeCategories.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L43).


### <a name="property-$_template_directory"></a>$_template_directory

```php
private string $_template_directory
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L46).


### <a name="property-$_title"></a>$_title

```php
private mixed $_title
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L47).


### <a name="property-$_toolbar"></a>$_toolbar

```php
private \TreeToolbar $_toolbar
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L51).


### <a name="property-$_use_checkbox"></a>$_use_checkbox

```php
private mixed $_use_checkbox
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L40).


### <a name="property-$_use_search"></a>$_use_search

```php
private mixed $_use_search
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L41).


### <a name="property-$_use_shop_restriction"></a>$_use_shop_restriction

```php
private mixed $_use_shop_restriction
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L42).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed HelperTreeCategoriesCore::__construct($id, $data)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L53)


#### Arguments
* $id **mixed**
* $data **mixed**



### <a name="method-__toString"></a>__toString

```php
mixed HelperTreeCategoriesCore::__toString()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L61)




### <a name="method-_disableCategories"></a>_disableCategories

```php
mixed HelperTreeCategoriesCore::_disableCategories($categories, $disabled_categories)
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 399](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L399)


#### Arguments
* $categories **mixed**
* $disabled_categories **mixed**



### <a name="method-_getSelectedChildNumbers"></a>_getSelectedChildNumbers

```php
mixed HelperTreeCategoriesCore::_getSelectedChildNumbers($categories, $selected, $parent)
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 414](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L414)


#### Arguments
* $categories **mixed**
* $selected **mixed**
* $parent **mixed**



### <a name="method-_normalizeDirectory"></a>_normalizeDirectory

```php
mixed HelperTreeCategoriesCore::_normalizeDirectory($directory)
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 442](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L442)


#### Arguments
* $directory **mixed**



### <a name="method-addAction"></a>addAction

```php
mixed HelperTreeCategoriesCore::addAction($action)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 326](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L326)


#### Arguments
* $action **mixed**



### <a name="method-fillTree"></a>fillTree

```php
mixed HelperTreeCategoriesCore::fillTree($categories, $id_category)
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L60)


#### Arguments
* $categories **mixed**
* $id_category **mixed**



### <a name="method-getActions"></a>getActions

```php
mixed HelperTreeCategoriesCore::getActions()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L75)




### <a name="method-getAttribute"></a>getAttribute

```php
mixed HelperTreeCategoriesCore::getAttribute($name)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L92)


#### Arguments
* $name **mixed**



### <a name="method-getAttributes"></a>getAttributes

```php
mixed HelperTreeCategoriesCore::getAttributes()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L106)




### <a name="method-getContext"></a>getContext

```php
mixed HelperTreeCategoriesCore::getContext()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L120)




### <a name="method-getData"></a>getData

```php
mixed HelperTreeCategoriesCore::getData()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L154)




### <a name="method-getDataSearch"></a>getDataSearch

```php
mixed HelperTreeCategoriesCore::getDataSearch()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L137)




### <a name="method-getDisabledCategories"></a>getDisabledCategories

```php
mixed HelperTreeCategoriesCore::getDisabledCategories()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L153)




### <a name="method-getFullTree"></a>getFullTree

```php
mixed HelperTreeCategoriesCore::getFullTree()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L141)




### <a name="method-getHeaderTemplate"></a>getHeaderTemplate

```php
mixed HelperTreeCategoriesCore::getHeaderTemplate()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L168)




### <a name="method-getId"></a>getId

```php
mixed HelperTreeCategoriesCore::getId()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L182)




### <a name="method-getInputName"></a>getInputName

```php
mixed HelperTreeCategoriesCore::getInputName()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L164)




### <a name="method-getLang"></a>getLang

```php
mixed HelperTreeCategoriesCore::getLang()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L178)




### <a name="method-getNodeFolderTemplate"></a>getNodeFolderTemplate

```php
mixed HelperTreeCategoriesCore::getNodeFolderTemplate()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 193](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L193)




### <a name="method-getNodeItemTemplate"></a>getNodeItemTemplate

```php
mixed HelperTreeCategoriesCore::getNodeItemTemplate()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 207](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L207)




### <a name="method-getRootCategory"></a>getRootCategory

```php
mixed HelperTreeCategoriesCore::getRootCategory()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 211](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L211)




### <a name="method-getSelectedCategories"></a>getSelectedCategories

```php
mixed HelperTreeCategoriesCore::getSelectedCategories()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 225](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L225)




### <a name="method-getShop"></a>getShop

```php
mixed HelperTreeCategoriesCore::getShop()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 239](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L239)




### <a name="method-getTemplate"></a>getTemplate

```php
mixed HelperTreeCategoriesCore::getTemplate()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L221)




### <a name="method-getTemplateDirectory"></a>getTemplateDirectory

```php
string HelperTreeCategoriesCore::getTemplateDirectory()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 243](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L243)




### <a name="method-getTemplateFile"></a>getTemplateFile

```php
mixed HelperTreeCategoriesCore::getTemplateFile($template)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 252](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L252)


#### Arguments
* $template **mixed**



### <a name="method-getTitle"></a>getTitle

```php
mixed HelperTreeCategoriesCore::getTitle()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 294](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L294)




### <a name="method-getToolbar"></a>getToolbar

```php
mixed HelperTreeCategoriesCore::getToolbar()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 313](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L313)




### <a name="method-removeActions"></a>removeActions

```php
mixed HelperTreeCategoriesCore::removeActions()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 335](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L335)




### <a name="method-render"></a>render

```php
mixed HelperTreeCategoriesCore::render($data)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 344](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L344)


#### Arguments
* $data **mixed**



### <a name="method-renderNodes"></a>renderNodes

```php
mixed HelperTreeCategoriesCore::renderNodes($data)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 394](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L394)


#### Arguments
* $data **mixed**



### <a name="method-renderToolbar"></a>renderToolbar

```php
mixed HelperTreeCategoriesCore::renderToolbar()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 427](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L427)




### <a name="method-setActions"></a>setActions

```php
mixed HelperTreeCategoriesCore::setActions($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L66)


#### Arguments
* $value **mixed**



### <a name="method-setAttribute"></a>setAttribute

```php
mixed HelperTreeCategoriesCore::setAttribute($name, $value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L83)


#### Arguments
* $name **mixed**
* $value **mixed**



### <a name="method-setAttributes"></a>setAttributes

```php
mixed HelperTreeCategoriesCore::setAttributes($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L97)


#### Arguments
* $value **mixed**



### <a name="method-setChildrenOnly"></a>setChildrenOnly

```php
mixed HelperTreeCategoriesCore::setChildrenOnly($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L129)


#### Arguments
* $value **mixed**



### <a name="method-setContext"></a>setContext

```php
mixed HelperTreeCategoriesCore::setContext($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L114)


#### Arguments
* $value **mixed**



### <a name="method-setData"></a>setData

```php
mixed HelperTreeCategoriesCore::setData($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L145)


#### Arguments
* $value **mixed**



### <a name="method-setDataSearch"></a>setDataSearch

```php
mixed HelperTreeCategoriesCore::setDataSearch($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L128)


#### Arguments
* $value **mixed**



### <a name="method-setDisabledCategories"></a>setDisabledCategories

```php
mixed HelperTreeCategoriesCore::setDisabledCategories($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L147)


#### Arguments
* $value **mixed**



### <a name="method-setFullTree"></a>setFullTree

```php
mixed HelperTreeCategoriesCore::setFullTree($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L135)


#### Arguments
* $value **mixed**



### <a name="method-setHeaderTemplate"></a>setHeaderTemplate

```php
mixed HelperTreeCategoriesCore::setHeaderTemplate($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L162)


#### Arguments
* $value **mixed**



### <a name="method-setId"></a>setId

```php
mixed HelperTreeCategoriesCore::setId($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L176)


#### Arguments
* $value **mixed**



### <a name="method-setInputName"></a>setInputName

```php
mixed HelperTreeCategoriesCore::setInputName($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L158)


#### Arguments
* $value **mixed**



### <a name="method-setLang"></a>setLang

```php
mixed HelperTreeCategoriesCore::setLang($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L172)


#### Arguments
* $value **mixed**



### <a name="method-setNoJS"></a>setNoJS

```php
mixed HelperTreeCategoriesCore::setNoJS($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 282](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L282)


#### Arguments
* $value **mixed**



### <a name="method-setNodeFolderTemplate"></a>setNodeFolderTemplate

```php
mixed HelperTreeCategoriesCore::setNodeFolderTemplate($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 187](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L187)


#### Arguments
* $value **mixed**



### <a name="method-setNodeItemTemplate"></a>setNodeItemTemplate

```php
mixed HelperTreeCategoriesCore::setNodeItemTemplate($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L201)


#### Arguments
* $value **mixed**



### <a name="method-setRootCategory"></a>setRootCategory

```php
mixed HelperTreeCategoriesCore::setRootCategory($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L202)


#### Arguments
* $value **mixed**



### <a name="method-setSelectedCategories"></a>setSelectedCategories

```php
mixed HelperTreeCategoriesCore::setSelectedCategories($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L216)


#### Arguments
* $value **mixed**



### <a name="method-setShop"></a>setShop

```php
mixed HelperTreeCategoriesCore::setShop($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 233](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L233)


#### Arguments
* $value **mixed**



### <a name="method-setTemplate"></a>setTemplate

```php
mixed HelperTreeCategoriesCore::setTemplate($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 215](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L215)


#### Arguments
* $value **mixed**



### <a name="method-setTemplateDirectory"></a>setTemplateDirectory

```php
\Tree HelperTreeCategoriesCore::setTemplateDirectory($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L234)


#### Arguments
* $value **mixed**



### <a name="method-setTitle"></a>setTitle

```php
mixed HelperTreeCategoriesCore::setTitle($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 288](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L288)


#### Arguments
* $value **mixed**



### <a name="method-setToolbar"></a>setToolbar

```php
mixed HelperTreeCategoriesCore::setToolbar($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 299](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L299)


#### Arguments
* $value **mixed**



### <a name="method-setUseCheckBox"></a>setUseCheckBox

```php
mixed HelperTreeCategoriesCore::setUseCheckBox($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 266](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L266)


#### Arguments
* $value **mixed**



### <a name="method-setUseSearch"></a>setUseSearch

```php
mixed HelperTreeCategoriesCore::setUseSearch($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L272)


#### Arguments
* $value **mixed**



### <a name="method-setUseShopRestriction"></a>setUseShopRestriction

```php
mixed HelperTreeCategoriesCore::setUseShopRestriction($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 278](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L278)


#### Arguments
* $value **mixed**



### <a name="method-useCheckBox"></a>useCheckBox

```php
mixed HelperTreeCategoriesCore::useCheckBox()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 284](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L284)




### <a name="method-useInput"></a>useInput

```php
mixed HelperTreeCategoriesCore::useInput()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 432](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L432)




### <a name="method-useSearch"></a>useSearch

```php
mixed HelperTreeCategoriesCore::useSearch()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 289](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L289)




### <a name="method-useShopRestriction"></a>useShopRestriction

```php
mixed HelperTreeCategoriesCore::useShopRestriction()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 294](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L294)




### <a name="method-useToolbar"></a>useToolbar

```php
mixed HelperTreeCategoriesCore::useToolbar()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 437](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/helper/HelperTreeCategories.php#L437)



