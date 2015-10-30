Class HelperTreeCategoriesCore
=====================





* Class name: HelperTreeCategoriesCore
* Parent class: [TreeCore](class.TreeCore.md)
* Source: [classes/helper/HelperTreeCategories.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L27)


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
* [$_id_tree](#property-$_id_tree)
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
* [getIdTree](#method-getIdTree)
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
* [setIdTree](#method-setIdTree)
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





* Source: [classes/helper/HelperTreeCategories.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L31).


### <a name="constant-DEFAULT_NODE_FOLDER_TEMPLATE"></a>DEFAULT_NODE_FOLDER_TEMPLATE

```php
const DEFAULT_NODE_FOLDER_TEMPLATE = 'tree_node_folder.tpl'
```





* Source: [classes/helper/HelperTreeCategories.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L32).


### <a name="constant-DEFAULT_NODE_ITEM_TEMPLATE"></a>DEFAULT_NODE_ITEM_TEMPLATE

```php
const DEFAULT_NODE_ITEM_TEMPLATE = 'tree_node_item.tpl'
```





* Source: [classes/helper/HelperTreeCategories.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L33).


### <a name="constant-DEFAULT_TEMPLATE"></a>DEFAULT_TEMPLATE

```php
const DEFAULT_TEMPLATE = 'tree.tpl'
```





* Source: [classes/helper/HelperTreeCategories.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L30).


### <a name="constant-DEFAULT_TEMPLATE_DIRECTORY"></a>DEFAULT_TEMPLATE_DIRECTORY

```php
const DEFAULT_TEMPLATE_DIRECTORY = 'helpers/tree'
```





* Source: [classes/helper/HelperTreeCategories.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L29).


Properties
----------


### <a name="property-$_attributes"></a>$_attributes

```php
protected mixed $_attributes
```





* Visibility: **protected**
* Source: [classes/helper/HelperTreeCategories.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L35).


### <a name="property-$_children_only"></a>$_children_only

```php
private mixed $_children_only = false
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L43).


### <a name="property-$_context"></a>$_context

```php
private mixed $_context
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L36).


### <a name="property-$_data"></a>$_data

```php
protected mixed $_data
```





* Visibility: **protected**
* Source: [classes/helper/HelperTreeCategories.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L37).


### <a name="property-$_data_search"></a>$_data_search

```php
protected mixed $_data_search
```





* Visibility: **protected**
* Source: [classes/helper/HelperTreeCategories.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L38).


### <a name="property-$_disabled_categories"></a>$_disabled_categories

```php
private mixed $_disabled_categories
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L33).


### <a name="property-$_full_tree"></a>$_full_tree

```php
private mixed $_full_tree = false
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L38).


### <a name="property-$_headerTemplate"></a>$_headerTemplate

```php
protected mixed $_headerTemplate
```





* Visibility: **protected**
* Source: [classes/helper/HelperTreeCategories.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L39).


### <a name="property-$_id"></a>$_id

```php
private mixed $_id
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L41).


### <a name="property-$_id_tree"></a>$_id_tree

```php
protected mixed $_id_tree
```





* Visibility: **protected**
* Source: [classes/helper/HelperTreeCategories.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L40).


### <a name="property-$_input_name"></a>$_input_name

```php
private mixed $_input_name
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L34).


### <a name="property-$_lang"></a>$_lang

```php
private mixed $_lang
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L35).


### <a name="property-$_no_js"></a>$_no_js

```php
private mixed $_no_js
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L49).


### <a name="property-$_node_folder_template"></a>$_node_folder_template

```php
protected mixed $_node_folder_template
```





* Visibility: **protected**
* Source: [classes/helper/HelperTreeCategories.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L42).


### <a name="property-$_node_item_template"></a>$_node_item_template

```php
protected mixed $_node_item_template
```





* Visibility: **protected**
* Source: [classes/helper/HelperTreeCategories.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L43).


### <a name="property-$_root_category"></a>$_root_category

```php
private mixed $_root_category
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L36).


### <a name="property-$_selected_categories"></a>$_selected_categories

```php
private mixed $_selected_categories
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L37).


### <a name="property-$_shop"></a>$_shop

```php
private mixed $_shop
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L39).


### <a name="property-$_template"></a>$_template

```php
protected mixed $_template
```





* Visibility: **protected**
* Source: [classes/helper/HelperTreeCategories.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L44).


### <a name="property-$_template_directory"></a>$_template_directory

```php
private string $_template_directory
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L47).


### <a name="property-$_title"></a>$_title

```php
private mixed $_title
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L48).


### <a name="property-$_toolbar"></a>$_toolbar

```php
private \TreeToolbar $_toolbar
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L52).


### <a name="property-$_use_checkbox"></a>$_use_checkbox

```php
private mixed $_use_checkbox
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L40).


### <a name="property-$_use_search"></a>$_use_search

```php
private mixed $_use_search
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L41).


### <a name="property-$_use_shop_restriction"></a>$_use_shop_restriction

```php
private mixed $_use_shop_restriction
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L42).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed HelperTreeCategoriesCore::__construct($id, $data)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L54)


#### Arguments
* $id **mixed**
* $data **mixed**



### <a name="method-__toString"></a>__toString

```php
mixed HelperTreeCategoriesCore::__toString()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L63)




### <a name="method-_disableCategories"></a>_disableCategories

```php
mixed HelperTreeCategoriesCore::_disableCategories($categories, $disabled_categories)
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 411](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L411)


#### Arguments
* $categories **mixed**
* $disabled_categories **mixed**



### <a name="method-_getSelectedChildNumbers"></a>_getSelectedChildNumbers

```php
mixed HelperTreeCategoriesCore::_getSelectedChildNumbers($categories, $selected, $parent)
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 425](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L425)


#### Arguments
* $categories **mixed**
* $selected **mixed**
* $parent **mixed**



### <a name="method-_normalizeDirectory"></a>_normalizeDirectory

```php
mixed HelperTreeCategoriesCore::_normalizeDirectory($directory)
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 479](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L479)


#### Arguments
* $directory **mixed**



### <a name="method-addAction"></a>addAction

```php
mixed HelperTreeCategoriesCore::addAction($action)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 358](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L358)


#### Arguments
* $action **mixed**



### <a name="method-fillTree"></a>fillTree

```php
mixed HelperTreeCategoriesCore::fillTree($categories, $id_category)
```





* Visibility: **private**
* Source: [classes/helper/HelperTreeCategories.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L62)


#### Arguments
* $categories **mixed**
* $id_category **mixed**



### <a name="method-getActions"></a>getActions

```php
mixed HelperTreeCategoriesCore::getActions()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L78)




### <a name="method-getAttribute"></a>getAttribute

```php
mixed HelperTreeCategoriesCore::getAttribute($name)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L97)


#### Arguments
* $name **mixed**



### <a name="method-getAttributes"></a>getAttributes

```php
mixed HelperTreeCategoriesCore::getAttributes()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L123)




### <a name="method-getContext"></a>getContext

```php
mixed HelperTreeCategoriesCore::getContext()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L138)




### <a name="method-getData"></a>getData

```php
mixed HelperTreeCategoriesCore::getData()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L176)




### <a name="method-getDataSearch"></a>getDataSearch

```php
mixed HelperTreeCategoriesCore::getDataSearch()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L157)




### <a name="method-getDisabledCategories"></a>getDisabledCategories

```php
mixed HelperTreeCategoriesCore::getDisabledCategories()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L156)




### <a name="method-getFullTree"></a>getFullTree

```php
mixed HelperTreeCategoriesCore::getFullTree()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L144)




### <a name="method-getHeaderTemplate"></a>getHeaderTemplate

```php
mixed HelperTreeCategoriesCore::getHeaderTemplate()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L191)




### <a name="method-getId"></a>getId

```php
mixed HelperTreeCategoriesCore::getId()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 206](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L206)




### <a name="method-getIdTree"></a>getIdTree

```php
mixed HelperTreeCategoriesCore::getIdTree()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L118)




### <a name="method-getInputName"></a>getInputName

```php
mixed HelperTreeCategoriesCore::getInputName()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L167)




### <a name="method-getLang"></a>getLang

```php
mixed HelperTreeCategoriesCore::getLang()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L182)




### <a name="method-getNodeFolderTemplate"></a>getNodeFolderTemplate

```php
mixed HelperTreeCategoriesCore::getNodeFolderTemplate()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L217)




### <a name="method-getNodeItemTemplate"></a>getNodeItemTemplate

```php
mixed HelperTreeCategoriesCore::getNodeItemTemplate()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L232)




### <a name="method-getRootCategory"></a>getRootCategory

```php
mixed HelperTreeCategoriesCore::getRootCategory()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 219](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L219)




### <a name="method-getSelectedCategories"></a>getSelectedCategories

```php
mixed HelperTreeCategoriesCore::getSelectedCategories()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L234)




### <a name="method-getShop"></a>getShop

```php
mixed HelperTreeCategoriesCore::getShop()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L249)




### <a name="method-getTemplate"></a>getTemplate

```php
mixed HelperTreeCategoriesCore::getTemplate()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 247](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L247)




### <a name="method-getTemplateDirectory"></a>getTemplateDirectory

```php
string HelperTreeCategoriesCore::getTemplateDirectory()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L270)




### <a name="method-getTemplateFile"></a>getTemplateFile

```php
mixed HelperTreeCategoriesCore::getTemplateFile($template)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 280](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L280)


#### Arguments
* $template **mixed**



### <a name="method-getTitle"></a>getTitle

```php
mixed HelperTreeCategoriesCore::getTitle()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 324](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L324)




### <a name="method-getToolbar"></a>getToolbar

```php
mixed HelperTreeCategoriesCore::getToolbar()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 345](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L345)




### <a name="method-removeActions"></a>removeActions

```php
mixed HelperTreeCategoriesCore::removeActions()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 368](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L368)




### <a name="method-render"></a>render

```php
mixed HelperTreeCategoriesCore::render($data)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 378](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L378)


#### Arguments
* $data **mixed**



### <a name="method-renderNodes"></a>renderNodes

```php
mixed HelperTreeCategoriesCore::renderNodes($data)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 429](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L429)


#### Arguments
* $data **mixed**



### <a name="method-renderToolbar"></a>renderToolbar

```php
mixed HelperTreeCategoriesCore::renderToolbar()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 464](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L464)




### <a name="method-setActions"></a>setActions

```php
mixed HelperTreeCategoriesCore::setActions($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L68)


#### Arguments
* $value **mixed**



### <a name="method-setAttribute"></a>setAttribute

```php
mixed HelperTreeCategoriesCore::setAttribute($name, $value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L87)


#### Arguments
* $name **mixed**
* $value **mixed**



### <a name="method-setAttributes"></a>setAttributes

```php
mixed HelperTreeCategoriesCore::setAttributes($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L102)


#### Arguments
* $value **mixed**



### <a name="method-setChildrenOnly"></a>setChildrenOnly

```php
mixed HelperTreeCategoriesCore::setChildrenOnly($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L132)


#### Arguments
* $value **mixed**



### <a name="method-setContext"></a>setContext

```php
mixed HelperTreeCategoriesCore::setContext($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L132)


#### Arguments
* $value **mixed**



### <a name="method-setData"></a>setData

```php
mixed HelperTreeCategoriesCore::setData($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L166)


#### Arguments
* $value **mixed**



### <a name="method-setDataSearch"></a>setDataSearch

```php
mixed HelperTreeCategoriesCore::setDataSearch($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L147)


#### Arguments
* $value **mixed**



### <a name="method-setDisabledCategories"></a>setDisabledCategories

```php
mixed HelperTreeCategoriesCore::setDisabledCategories($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L150)


#### Arguments
* $value **mixed**



### <a name="method-setFullTree"></a>setFullTree

```php
mixed HelperTreeCategoriesCore::setFullTree($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L138)


#### Arguments
* $value **mixed**



### <a name="method-setHeaderTemplate"></a>setHeaderTemplate

```php
mixed HelperTreeCategoriesCore::setHeaderTemplate($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 185](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L185)


#### Arguments
* $value **mixed**



### <a name="method-setId"></a>setId

```php
mixed HelperTreeCategoriesCore::setId($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L200)


#### Arguments
* $value **mixed**



### <a name="method-setIdTree"></a>setIdTree

```php
mixed HelperTreeCategoriesCore::setIdTree($id_tree)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L112)


#### Arguments
* $id_tree **mixed**



### <a name="method-setInputName"></a>setInputName

```php
mixed HelperTreeCategoriesCore::setInputName($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 161](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L161)


#### Arguments
* $value **mixed**



### <a name="method-setLang"></a>setLang

```php
mixed HelperTreeCategoriesCore::setLang($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L176)


#### Arguments
* $value **mixed**



### <a name="method-setNoJS"></a>setNoJS

```php
mixed HelperTreeCategoriesCore::setNoJS($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 312](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L312)


#### Arguments
* $value **mixed**



### <a name="method-setNodeFolderTemplate"></a>setNodeFolderTemplate

```php
mixed HelperTreeCategoriesCore::setNodeFolderTemplate($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 211](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L211)


#### Arguments
* $value **mixed**



### <a name="method-setNodeItemTemplate"></a>setNodeItemTemplate

```php
mixed HelperTreeCategoriesCore::setNodeItemTemplate($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 226](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L226)


#### Arguments
* $value **mixed**



### <a name="method-setRootCategory"></a>setRootCategory

```php
mixed HelperTreeCategoriesCore::setRootCategory($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 209](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L209)


#### Arguments
* $value **mixed**



### <a name="method-setSelectedCategories"></a>setSelectedCategories

```php
mixed HelperTreeCategoriesCore::setSelectedCategories($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 224](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L224)


#### Arguments
* $value **mixed**



### <a name="method-setShop"></a>setShop

```php
mixed HelperTreeCategoriesCore::setShop($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 243](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L243)


#### Arguments
* $value **mixed**



### <a name="method-setTemplate"></a>setTemplate

```php
mixed HelperTreeCategoriesCore::setTemplate($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 241](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L241)


#### Arguments
* $value **mixed**



### <a name="method-setTemplateDirectory"></a>setTemplateDirectory

```php
\Tree HelperTreeCategoriesCore::setTemplateDirectory($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 261](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L261)


#### Arguments
* $value **mixed**



### <a name="method-setTitle"></a>setTitle

```php
mixed HelperTreeCategoriesCore::setTitle($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 318](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L318)


#### Arguments
* $value **mixed**



### <a name="method-setToolbar"></a>setToolbar

```php
mixed HelperTreeCategoriesCore::setToolbar($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 329](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L329)


#### Arguments
* $value **mixed**



### <a name="method-setUseCheckBox"></a>setUseCheckBox

```php
mixed HelperTreeCategoriesCore::setUseCheckBox($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 275](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L275)


#### Arguments
* $value **mixed**



### <a name="method-setUseSearch"></a>setUseSearch

```php
mixed HelperTreeCategoriesCore::setUseSearch($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 281](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L281)


#### Arguments
* $value **mixed**



### <a name="method-setUseShopRestriction"></a>setUseShopRestriction

```php
mixed HelperTreeCategoriesCore::setUseShopRestriction($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 287](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L287)


#### Arguments
* $value **mixed**



### <a name="method-useCheckBox"></a>useCheckBox

```php
mixed HelperTreeCategoriesCore::useCheckBox()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 293](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L293)




### <a name="method-useInput"></a>useInput

```php
mixed HelperTreeCategoriesCore::useInput()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 469](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L469)




### <a name="method-useSearch"></a>useSearch

```php
mixed HelperTreeCategoriesCore::useSearch()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 298](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L298)




### <a name="method-useShopRestriction"></a>useShopRestriction

```php
mixed HelperTreeCategoriesCore::useShopRestriction()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 303](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L303)




### <a name="method-useToolbar"></a>useToolbar

```php
mixed HelperTreeCategoriesCore::useToolbar()
```





* Visibility: **public**
* Source: [classes/helper/HelperTreeCategories.php line 474](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperTreeCategories.php#L474)



