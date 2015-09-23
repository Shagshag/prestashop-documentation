Class HelperListCore
=====================





* Class name: HelperListCore
* Parent class: [Helper](class.HelperCore.md)
* Source: [classes/helper/HelperList.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L31)


Contents
--------


### Properties

* [$_defaultOrderBy](#property-$_defaultOrderBy)
* [$_filter](#property-$_filter)
* [$_list](#property-$_list)
* [$_pagination](#property-$_pagination)
* [$actions](#property-$actions)
* [$ajax_params](#property-$ajax_params)
* [$bulk_actions](#property-$bulk_actions)
* [$cache_lang](#property-$cache_lang)
* [$colorOnBackground](#property-$colorOnBackground)
* [$content_tpl](#property-$content_tpl)
* [$deleted](#property-$deleted)
* [$fields_list](#property-$fields_list)
* [$footer_tpl](#property-$footer_tpl)
* [$header_tpl](#property-$header_tpl)
* [$identifier](#property-$identifier)
* [$is_cms](#property-$is_cms)
* [$listTotal](#property-$listTotal)
* [$list_skip_actions](#property-$list_skip_actions)
* [$no_link](#property-$no_link)
* [$orderBy](#property-$orderBy)
* [$orderWay](#property-$orderWay)
* [$position_identifier](#property-$position_identifier)
* [$row_hover](#property-$row_hover)
* [$simple_header](#property-$simple_header)
* [$specificConfirmDelete](#property-$specificConfirmDelete)
* [$title](#property-$title)
* [$tpl_delete_link_vars](#property-$tpl_delete_link_vars)
* [$base_folder](#property-$base_folder)
* [$base_tpl](#property-$base_tpl)
* [$context](#property-$context)
* [$currentIndex](#property-$currentIndex)
* [$module](#property-$module)
* [$override_folder](#property-$override_folder)
* [$ps_help_context](#property-$ps_help_context)
* [$show_toolbar](#property-$show_toolbar)
* [$table](#property-$table)
* [$token](#property-$token)
* [$toolbar_btn](#property-$toolbar_btn)
* [$toolbar_scroll](#property-$toolbar_scroll)
* [$tpl](#property-$tpl)
* [$tpl_vars](#property-$tpl_vars)

### Methods

* [__construct](#method-__construct)
* [createTemplate](#method-createTemplate)
* [displayDefaultLink](#method-displayDefaultLink)
* [displayDeleteLink](#method-displayDeleteLink)
* [displayDetailsLink](#method-displayDetailsLink)
* [displayDuplicateLink](#method-displayDuplicateLink)
* [displayEditLink](#method-displayEditLink)
* [displayEnableLink](#method-displayEnableLink)
* [displayListContent](#method-displayListContent)
* [displayListFooter](#method-displayListFooter)
* [displayListHeader](#method-displayListHeader)
* [displayViewLink](#method-displayViewLink)
* [generate](#method-generate)
* [generateList](#method-generateList)
* [l](#method-l)
* [renderAdminCategorieTree](#method-renderAdminCategorieTree)
* [renderCategoryTree](#method-renderCategoryTree)
* [renderRequiredFields](#method-renderRequiredFields)
* [renderShopList](#method-renderShopList)
* [setTpl](#method-setTpl)




Properties
----------


### <a name="property-$_defaultOrderBy"></a>$_defaultOrderBy

```php
public string $_defaultOrderBy = false
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L49).


### <a name="property-$_filter"></a>$_filter

```php
protected array $_filter
```





* Visibility: **protected**
* Source: [classes/helper/HelperList.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L40).


### <a name="property-$_list"></a>$_list

```php
protected array $_list = array()
```





* Visibility: **protected**
* Source: [classes/helper/HelperList.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L34).


### <a name="property-$_pagination"></a>$_pagination

```php
protected array $_pagination = array(20, 50, 100, 300)
```





* Visibility: **protected**
* Source: [classes/helper/HelperList.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L43).


### <a name="property-$actions"></a>$actions

```php
public array $actions = array()
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L88).


### <a name="property-$ajax_params"></a>$ajax_params

```php
public mixed $ajax_params = array()
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L106).


### <a name="property-$bulk_actions"></a>$bulk_actions

```php
public mixed $bulk_actions = false
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L93).


### <a name="property-$cache_lang"></a>$cache_lang

```php
public array $cache_lang = array()
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/helper/HelperList.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L62).


### <a name="property-$colorOnBackground"></a>$colorOnBackground

```php
public mixed $colorOnBackground
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L95).


### <a name="property-$content_tpl"></a>$content_tpl

```php
protected mixed $content_tpl = 'list_content.tpl'
```





* Visibility: **protected**
* Source: [classes/helper/HelperList.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L84).


### <a name="property-$deleted"></a>$deleted

```php
protected mixed $deleted
```





* Visibility: **protected**
* Source: [classes/helper/HelperList.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L59).


### <a name="property-$fields_list"></a>$fields_list

```php
protected string $fields_list
```





* Visibility: **protected**
* Source: [classes/helper/HelperList.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L78).


### <a name="property-$footer_tpl"></a>$footer_tpl

```php
protected mixed $footer_tpl = 'list_footer.tpl'
```





* Visibility: **protected**
* Source: [classes/helper/HelperList.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L85).


### <a name="property-$header_tpl"></a>$header_tpl

```php
protected mixed $header_tpl = 'list_header.tpl'
```





* Visibility: **protected**
* Source: [classes/helper/HelperList.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L83).


### <a name="property-$identifier"></a>$identifier

```php
public mixed $identifier
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L57).


### <a name="property-$is_cms"></a>$is_cms

```php
protected mixed $is_cms = false
```





* Visibility: **protected**
* Source: [classes/helper/HelperList.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L64).


### <a name="property-$listTotal"></a>$listTotal

```php
public integer $listTotal
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L37).


### <a name="property-$list_skip_actions"></a>$list_skip_actions

```php
public array $list_skip_actions = array()
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L91).


### <a name="property-$no_link"></a>$no_link

```php
public boolean $no_link = false
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L81).


### <a name="property-$orderBy"></a>$orderBy

```php
public string $orderBy
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L46).


### <a name="property-$orderWay"></a>$orderWay

```php
public string $orderWay
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L55).


### <a name="property-$position_identifier"></a>$position_identifier

```php
public mixed $position_identifier
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L66).


### <a name="property-$row_hover"></a>$row_hover

```php
public boolean $row_hover = true
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L98).


### <a name="property-$simple_header"></a>$simple_header

```php
public boolean $simple_header = false
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L104).


### <a name="property-$specificConfirmDelete"></a>$specificConfirmDelete

```php
public mixed $specificConfirmDelete = null
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L94).


### <a name="property-$title"></a>$title

```php
public \if $title = null
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L101).


### <a name="property-$tpl_delete_link_vars"></a>$tpl_delete_link_vars

```php
public array $tpl_delete_link_vars = array()
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L52).


### <a name="property-$base_folder"></a>$base_folder

```php
public string $base_folder
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/Helper.php#L47).


### <a name="property-$base_tpl"></a>$base_tpl

```php
public string $base_tpl = 'content.tpl'
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/Helper.php#L60).


### <a name="property-$context"></a>$context

```php
public mixed $context
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/Helper.php#L38).


### <a name="property-$currentIndex"></a>$currentIndex

```php
public mixed $currentIndex
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/Helper.php#L30).


### <a name="property-$module"></a>$module

```php
public \Module $module
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/Helper.php#L44).


### <a name="property-$override_folder"></a>$override_folder

```php
public string $override_folder
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/Helper.php#L50).


### <a name="property-$ps_help_context"></a>$ps_help_context

```php
public mixed $ps_help_context
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/Helper.php#L35).


### <a name="property-$show_toolbar"></a>$show_toolbar

```php
public mixed $show_toolbar = true
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/Helper.php#L37).


### <a name="property-$table"></a>$table

```php
public mixed $table
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/Helper.php#L31).


### <a name="property-$token"></a>$token

```php
public mixed $token
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/Helper.php#L33).


### <a name="property-$toolbar_btn"></a>$toolbar_btn

```php
public mixed $toolbar_btn
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/Helper.php#L34).


### <a name="property-$toolbar_scroll"></a>$toolbar_scroll

```php
public mixed $toolbar_scroll = false
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/Helper.php#L39).


### <a name="property-$tpl"></a>$tpl

```php
protected \smartyTemplate $tpl
```





* Visibility: **protected**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/Helper.php#L55).


### <a name="property-$tpl_vars"></a>$tpl_vars

```php
public mixed $tpl_vars = array()
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/Helper.php#L62).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed HelperListCore::__construct()
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L108)




### <a name="method-createTemplate"></a>createTemplate

```php
\Template HelperCore::createTemplate(string $tpl_name)
```

Create a template from the override file, else from the base file.



* Visibility: **public**
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/Helper.php#L80)


#### Arguments
* $tpl_name **string** - filename



### <a name="method-displayDefaultLink"></a>displayDefaultLink

```php
mixed HelperListCore::displayDefaultLink($token, $id, $name)
```

Display delete action link



* Visibility: **public**
* Source: [classes/helper/HelperList.php line 470](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L470)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### <a name="method-displayDeleteLink"></a>displayDeleteLink

```php
mixed HelperListCore::displayDeleteLink($token, $id, $name)
```

Display delete action link



* Visibility: **public**
* Source: [classes/helper/HelperList.php line 437](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L437)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### <a name="method-displayDetailsLink"></a>displayDetailsLink

```php
mixed HelperListCore::displayDetailsLink($token, $id, $name)
```

Display action show details of a table row
This action need an ajax request with a return like this:
  {
    use_parent_structure: true // If false, data need to be an html
    data:
      [
        {field_name: 'value'}
      ],
    fields_display: // attribute $fields_list of the admin controller
  }
or somethins like this:
  {
    use_parent_structure: false // If false, data need to be an html
    data:
      '<p>My html content</p>',
    fields_display: // attribute $fields_list of the admin controller
  }



* Visibility: **public**
* Source: [classes/helper/HelperList.php line 377](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L377)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### <a name="method-displayDuplicateLink"></a>displayDuplicateLink

```php
mixed HelperListCore::displayDuplicateLink($token, $id, $name)
```

Display duplicate action link



* Visibility: **public**
* Source: [classes/helper/HelperList.php line 335](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L335)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### <a name="method-displayEditLink"></a>displayEditLink

```php
mixed HelperListCore::displayEditLink($token, $id, $name)
```

Display edit action link



* Visibility: **public**
* Source: [classes/helper/HelperList.php line 419](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L419)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### <a name="method-displayEnableLink"></a>displayEnableLink

```php
string HelperListCore::displayEnableLink(string $token, integer $id, integer $value, string $active, integer $id_category, integer $id_product)
```

Fetch the template for action enable



* Visibility: **public**
* Source: [classes/helper/HelperList.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L164)


#### Arguments
* $token **string**
* $id **integer**
* $value **integer** - state enabled or not
* $active **string** - status
* $id_category **integer**
* $id_product **integer**



### <a name="method-displayListContent"></a>displayListContent

```php
mixed HelperListCore::displayListContent()
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L175)




### <a name="method-displayListFooter"></a>displayListFooter

```php
mixed HelperListCore::displayListFooter()
```

Close list table and submit button



* Visibility: **public**
* Source: [classes/helper/HelperList.php line 616](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L616)




### <a name="method-displayListHeader"></a>displayListHeader

```php
mixed HelperListCore::displayListHeader()
```

Display list header (filtering, pagination and column names)



* Visibility: **public**
* Source: [classes/helper/HelperList.php line 488](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L488)




### <a name="method-displayViewLink"></a>displayViewLink

```php
mixed HelperListCore::displayViewLink($token, $id, $name)
```

Display view action link



* Visibility: **public**
* Source: [classes/helper/HelperList.php line 401](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L401)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### <a name="method-generate"></a>generate

```php
void HelperCore::generate()
```

default behaviour for helper is to return a tpl fetched



* Visibility: **public**
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/Helper.php#L111)




### <a name="method-generateList"></a>generateList

```php
string HelperListCore::generateList(array $list, array $fields_display)
```

Return an html list given the data to fill it up



* Visibility: **public**
* Source: [classes/helper/HelperList.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/HelperList.php#L123)


#### Arguments
* $list **array** - entries to display (rows)
* $fields_display **array** - fields (cols)



### <a name="method-l"></a>l

```php
string HelperCore::l(mixed $string, string $class, \boolan $addslashes, boolean $htmlentities)
```

use translations files to replace english expression.



* Visibility: **protected**
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 308](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/Helper.php#L308)


#### Arguments
* $string **mixed** - term or expression in english
* $class **string**
* $addslashes **boolan** - if set to true, the return value will pass through addslashes(). Otherwise, stripslashes().
* $htmlentities **boolean** - if set to true(default), the return value will pass through htmlentities($string, ENT_QUOTES, &#039;utf-8&#039;)



### <a name="method-renderAdminCategorieTree"></a>renderAdminCategorieTree

```php
mixed HelperCore::renderAdminCategorieTree($translations, $selected_cat, $input_name, $use_radio, $use_search, $disabled_categories, $use_in_popup)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/Helper.php#L120)


#### Arguments
* $translations **mixed**
* $selected_cat **mixed**
* $input_name **mixed**
* $use_radio **mixed**
* $use_search **mixed**
* $disabled_categories **mixed**
* $use_in_popup **mixed**



### <a name="method-renderCategoryTree"></a>renderCategoryTree

```php
string HelperCore::renderCategoryTree(array $root, \type $selected_cat, string $input_name, boolean $use_radio, boolean $use_search, array $disabled_categories, boolean $use_in_popup, boolean $use_shop_context)
```





* Visibility: **public**
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/Helper.php#L168)


#### Arguments
* $root **array** - array with the name and ID of the tree root category, if null the Shop&#039;s root category will be used
* $selected_cat **type** - array of selected categories
            Format
                Array
                (
                     [0] =&gt; 1
                 [1] =&gt; 2
            )
                OR
            Array
            (
                 [1] =&gt; Array
                      (
                            [id_category] =&gt; 1
                            [name] =&gt; Home page
                      )
            )
* $input_name **string** - name of input
* $use_radio **boolean** - use radio tree or checkbox tree
* $use_search **boolean** - display a find category search box
* $disabled_categories **array**
* $use_in_popup **boolean**
* $use_shop_context **boolean**



### <a name="method-renderRequiredFields"></a>renderRequiredFields

```php
string HelperCore::renderRequiredFields(string $class_name, string $identifier, array $table_fields)
```

Render a form with potentials required fields



* Visibility: **public**
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 326](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/Helper.php#L326)


#### Arguments
* $class_name **string**
* $identifier **string**
* $table_fields **array**



### <a name="method-renderShopList"></a>renderShopList

```php
mixed HelperCore::renderShopList()
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 355](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/Helper.php#L355)




### <a name="method-setTpl"></a>setTpl

```php
mixed HelperCore::setTpl($tpl)
```





* Visibility: **public**
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.5.2.0/classes/helper/Helper.php#L69)


#### Arguments
* $tpl **mixed**


