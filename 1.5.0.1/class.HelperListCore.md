Class HelperListCore
=====================





* Class name: HelperListCore
* Parent class: [Helper](class.HelperCore.md)
* Source: [classes/HelperList.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L28)


Contents
--------


### Properties

* [$_defaultOrderBy](#property-$_defaultOrderBy)
* [$_filter](#property-$_filter)
* [$_list](#property-$_list)
* [$_pagination](#property-$_pagination)
* [$_tmpTableFilter](#property-$_tmpTableFilter)
* [$actions](#property-$actions)
* [$ajax_params](#property-$ajax_params)
* [$bulk_actions](#property-$bulk_actions)
* [$cache_lang](#property-$cache_lang)
* [$colorOnBackground](#property-$colorOnBackground)
* [$content_tpl](#property-$content_tpl)
* [$deleted](#property-$deleted)
* [$fieldsDisplay](#property-$fieldsDisplay)
* [$footer_tpl](#property-$footer_tpl)
* [$header_tpl](#property-$header_tpl)
* [$identifier](#property-$identifier)
* [$identifiersDnd](#property-$identifiersDnd)
* [$is_cms](#property-$is_cms)
* [$is_dnd_identifier](#property-$is_dnd_identifier)
* [$listTotal](#property-$listTotal)
* [$list_skip_actions](#property-$list_skip_actions)
* [$no_back](#property-$no_back)
* [$no_link](#property-$no_link)
* [$orderBy](#property-$orderBy)
* [$orderWay](#property-$orderWay)
* [$simple_header](#property-$simple_header)
* [$specificConfirmDelete](#property-$specificConfirmDelete)
* [$title](#property-$title)
* [$tpl_delete_link_vars](#property-$tpl_delete_link_vars)
* [$base_folder](#property-$base_folder)
* [$base_tpl](#property-$base_tpl)
* [$context](#property-$context)
* [$currentIndex](#property-$currentIndex)
* [$override_folder](#property-$override_folder)
* [$ps_help_context](#property-$ps_help_context)
* [$show_toolbar](#property-$show_toolbar)
* [$table](#property-$table)
* [$token](#property-$token)
* [$toolbar_btn](#property-$toolbar_btn)
* [$toolbar_fix](#property-$toolbar_fix)
* [$tpl](#property-$tpl)
* [$tpl_vars](#property-$tpl_vars)

### Methods

* [__construct](#method-__construct)
* [buildHtmlOptions](#method-buildHtmlOptions)
* [createTemplate](#method-createTemplate)
* [displayAssoShop](#method-displayAssoShop)
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
* [selectInput](#method-selectInput)
* [setTpl](#method-setTpl)




Properties
----------


### <a name="property-$_defaultOrderBy"></a>$_defaultOrderBy

```php
public string $_defaultOrderBy = false
```





* Visibility: **public**
* Source: [classes/HelperList.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L49).


### <a name="property-$_filter"></a>$_filter

```php
protected array $_filter
```





* Visibility: **protected**
* Source: [classes/HelperList.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L37).


### <a name="property-$_list"></a>$_list

```php
protected array $_list = array()
```





* Visibility: **protected**
* Source: [classes/HelperList.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L31).


### <a name="property-$_pagination"></a>$_pagination

```php
protected array $_pagination = array(20, 50, 100, 300)
```





* Visibility: **protected**
* Source: [classes/HelperList.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L43).


### <a name="property-$_tmpTableFilter"></a>$_tmpTableFilter

```php
protected array $_tmpTableFilter = ''
```





* Visibility: **protected**
* Source: [classes/HelperList.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L40).


### <a name="property-$actions"></a>$actions

```php
public array $actions = array()
```





* Visibility: **public**
* Source: [classes/HelperList.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L87).


### <a name="property-$ajax_params"></a>$ajax_params

```php
public mixed $ajax_params = array()
```





* Visibility: **public**
* Source: [classes/HelperList.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L120).


### <a name="property-$bulk_actions"></a>$bulk_actions

```php
public mixed $bulk_actions = false
```





* Visibility: **public**
* Source: [classes/HelperList.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L92).


### <a name="property-$cache_lang"></a>$cache_lang

```php
public array $cache_lang = array()
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/HelperList.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L62).


### <a name="property-$colorOnBackground"></a>$colorOnBackground

```php
public mixed $colorOnBackground
```





* Visibility: **public**
* Source: [classes/HelperList.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L94).


### <a name="property-$content_tpl"></a>$content_tpl

```php
protected mixed $content_tpl = 'list_content.tpl'
```





* Visibility: **protected**
* Source: [classes/HelperList.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L83).


### <a name="property-$deleted"></a>$deleted

```php
protected mixed $deleted
```





* Visibility: **protected**
* Source: [classes/HelperList.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L59).


### <a name="property-$fieldsDisplay"></a>$fieldsDisplay

```php
protected mixed $fieldsDisplay
```





* Visibility: **protected**
* Source: [classes/HelperList.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L77).


### <a name="property-$footer_tpl"></a>$footer_tpl

```php
protected mixed $footer_tpl = 'list_footer.tpl'
```





* Visibility: **protected**
* Source: [classes/HelperList.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L84).


### <a name="property-$header_tpl"></a>$header_tpl

```php
protected mixed $header_tpl = 'list_header.tpl'
```





* Visibility: **protected**
* Source: [classes/HelperList.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L82).


### <a name="property-$identifier"></a>$identifier

```php
public mixed $identifier
```





* Visibility: **public**
* Source: [classes/HelperList.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L57).


### <a name="property-$identifiersDnd"></a>$identifiersDnd

```php
protected mixed $identifiersDnd = array('id_product' => 'id_product', 'id_category' => 'id_category_to_move', 'id_cms_category' => 'id_cms_category_to_move', 'id_cms' => 'id_cms', 'id_attribute' => 'id_attribute', 'id_attribute_group' => 'id_attribute_group', 'id_carrier' => 'id_carrier', 'id_tab' => 'id_tab', 'id_feature' => 'id_feature')
```





* Visibility: **protected**
* Source: [classes/HelperList.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L96).


### <a name="property-$is_cms"></a>$is_cms

```php
protected mixed $is_cms = false
```





* Visibility: **protected**
* Source: [classes/HelperList.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L64).


### <a name="property-$is_dnd_identifier"></a>$is_dnd_identifier

```php
protected mixed $is_dnd_identifier = false
```





* Visibility: **protected**
* Source: [classes/HelperList.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L66).


### <a name="property-$listTotal"></a>$listTotal

```php
public integer $listTotal
```





* Visibility: **public**
* Source: [classes/HelperList.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L34).


### <a name="property-$list_skip_actions"></a>$list_skip_actions

```php
public array $list_skip_actions = array()
```





* Visibility: **public**
* Source: [classes/HelperList.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L90).


### <a name="property-$no_back"></a>$no_back

```php
public boolean $no_back = true
```





* Visibility: **public**
* Source: [classes/HelperList.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L118).


### <a name="property-$no_link"></a>$no_link

```php
public boolean $no_link = false
```





* Visibility: **public**
* Source: [classes/HelperList.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L80).


### <a name="property-$orderBy"></a>$orderBy

```php
public string $orderBy
```





* Visibility: **public**
* Source: [classes/HelperList.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L46).


### <a name="property-$orderWay"></a>$orderWay

```php
public string $orderWay
```





* Visibility: **public**
* Source: [classes/HelperList.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L55).


### <a name="property-$simple_header"></a>$simple_header

```php
public boolean $simple_header = false
```





* Visibility: **public**
* Source: [classes/HelperList.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L112).


### <a name="property-$specificConfirmDelete"></a>$specificConfirmDelete

```php
public mixed $specificConfirmDelete
```





* Visibility: **public**
* Source: [classes/HelperList.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L93).


### <a name="property-$title"></a>$title

```php
public \if $title = null
```





* Visibility: **public**
* Source: [classes/HelperList.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L109).


### <a name="property-$tpl_delete_link_vars"></a>$tpl_delete_link_vars

```php
public array $tpl_delete_link_vars = array()
```





* Visibility: **public**
* Source: [classes/HelperList.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L52).


### <a name="property-$base_folder"></a>$base_folder

```php
public string $base_folder
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L47).


### <a name="property-$base_tpl"></a>$base_tpl

```php
public string $base_tpl = 'content.tpl'
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L60).


### <a name="property-$context"></a>$context

```php
public mixed $context
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L43).


### <a name="property-$currentIndex"></a>$currentIndex

```php
public mixed $currentIndex
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L35).


### <a name="property-$override_folder"></a>$override_folder

```php
public string $override_folder
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L50).


### <a name="property-$ps_help_context"></a>$ps_help_context

```php
public mixed $ps_help_context
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L40).


### <a name="property-$show_toolbar"></a>$show_toolbar

```php
public mixed $show_toolbar = true
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L42).


### <a name="property-$table"></a>$table

```php
public mixed $table
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L36).


### <a name="property-$token"></a>$token

```php
public mixed $token
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L38).


### <a name="property-$toolbar_btn"></a>$toolbar_btn

```php
public mixed $toolbar_btn
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L39).


### <a name="property-$toolbar_fix"></a>$toolbar_fix

```php
public mixed $toolbar_fix = false
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L44).


### <a name="property-$tpl"></a>$tpl

```php
protected \smartyTemplate $tpl
```





* Visibility: **protected**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L55).


### <a name="property-$tpl_vars"></a>$tpl_vars

```php
public mixed $tpl_vars = array()
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L62).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed HelperListCore::__construct()
```





* Visibility: **public**
* Source: [classes/HelperList.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L122)




### <a name="method-buildHtmlOptions"></a>buildHtmlOptions

```php
string HelperCore::buildHtmlOptions(array $html_options)
```

Create html a string containing html options
eg: buildHtmlOptions(array('name' => 'myInputName', 'id' => 'myInputId'));
    return => 'name="myInputName" id="myInputId"'



* Visibility: **protected**
* This method is **static**.
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 263](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L263)


#### Arguments
* $html_options **array**



### <a name="method-createTemplate"></a>createTemplate

```php
\Template HelperCore::createTemplate(string $tpl_name)
```

Create a template from the override file, else from the base file.



* Visibility: **public**
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L80)


#### Arguments
* $tpl_name **string** - filename



### <a name="method-displayAssoShop"></a>displayAssoShop

```php
mixed HelperCore::displayAssoShop($type)
```





* Visibility: **protected**
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 302](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L302)


#### Arguments
* $type **mixed**



### <a name="method-displayDeleteLink"></a>displayDeleteLink

```php
mixed HelperListCore::displayDeleteLink($token, $id)
```

Display delete action link



* Visibility: **protected**
* Source: [classes/HelperList.php line 445](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L445)


#### Arguments
* $token **mixed**
* $id **mixed**



### <a name="method-displayDetailsLink"></a>displayDetailsLink

```php
mixed HelperListCore::displayDetailsLink($token, $id)
```

Display action show details of a table row
This action need an ajax request with a return like this:
  {
    use_parent_structure: true // If false, data need to be an html
    data:
      [
        {field_name: 'value'}
      ],
    fields_display: // attribute $fieldsDisplay of the admin controller
  }
or somethins like this:
  {
    use_parent_structure: false // If false, data need to be an html
    data:
      '<p>My html content</p>',
    fields_display: // attribute $fieldsDisplay of the admin controller
  }



* Visibility: **protected**
* Source: [classes/HelperList.php line 390](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L390)


#### Arguments
* $token **mixed**
* $id **mixed**



### <a name="method-displayDuplicateLink"></a>displayDuplicateLink

```php
mixed HelperListCore::displayDuplicateLink($token, $id)
```

Display duplicate action link



* Visibility: **protected**
* Source: [classes/HelperList.php line 348](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L348)


#### Arguments
* $token **mixed**
* $id **mixed**



### <a name="method-displayEditLink"></a>displayEditLink

```php
mixed HelperListCore::displayEditLink($token, $id)
```

Display edit action link



* Visibility: **protected**
* Source: [classes/HelperList.php line 426](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L426)


#### Arguments
* $token **mixed**
* $id **mixed**



### <a name="method-displayEnableLink"></a>displayEnableLink

```php
mixed HelperListCore::displayEnableLink(string $token, integer $id, integer $value, string $active, integer $id_category, integer $id_product)
```

Fetch the template for action enable



* Visibility: **protected**
* Source: [classes/HelperList.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L178)


#### Arguments
* $token **string**
* $id **integer**
* $value **integer** - state enabled or not
* $active **string** - status
* $id_category **integer**
* $id_product **integer**



### <a name="method-displayListContent"></a>displayListContent

```php
mixed HelperListCore::displayListContent($token)
```





* Visibility: **public**
* Source: [classes/HelperList.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L189)


#### Arguments
* $token **mixed**



### <a name="method-displayListFooter"></a>displayListFooter

```php
mixed HelperListCore::displayListFooter($token)
```

Close list table and submit button



* Visibility: **public**
* Source: [classes/HelperList.php line 608](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L608)


#### Arguments
* $token **mixed**



### <a name="method-displayListHeader"></a>displayListHeader

```php
mixed HelperListCore::displayListHeader($token)
```

Display list header (filtering, pagination and column names)



* Visibility: **public**
* Source: [classes/HelperList.php line 467](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L467)


#### Arguments
* $token **mixed**



### <a name="method-displayViewLink"></a>displayViewLink

```php
mixed HelperListCore::displayViewLink($token, $id)
```

Display view action link



* Visibility: **protected**
* Source: [classes/HelperList.php line 408](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L408)


#### Arguments
* $token **mixed**
* $id **mixed**



### <a name="method-generate"></a>generate

```php
void HelperCore::generate()
```

default behaviour for helper is to return a tpl fetched



* Visibility: **public**
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L94)




### <a name="method-generateList"></a>generateList

```php
string HelperListCore::generateList(array $list, $fields_display)
```

Return an html list given the data to fill it up



* Visibility: **public**
* Source: [classes/HelperList.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/HelperList.php#L137)


#### Arguments
* $list **array** - entries to display (rows)
* $fields_display **mixed**



### <a name="method-l"></a>l

```php
string HelperCore::l(mixed $string, string $class, \boolan $addslashes, boolean $htmlentities)
```

use translations files to replace english expression.



* Visibility: **protected**
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 282](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L282)


#### Arguments
* $string **mixed** - term or expression in english
* $class **string**
* $addslashes **boolan** - if set to true, the return value will pass through addslashes(). Otherwise, stripslashes().
* $htmlentities **boolean** - if set to true(default), the return value will pass through htmlentities($string, ENT_QUOTES, &#039;utf-8&#039;)



### <a name="method-renderAdminCategorieTree"></a>renderAdminCategorieTree

```php
string HelperCore::renderAdminCategorieTree(\type $trads, \type $selected_cat, \type $input_name, $use_radio, $use_search, $disabled_categories)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L124)


#### Arguments
* $trads **type** - values of translations keys
				For the moment, translation are not automatic
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
                            [link_rewrite] =&gt; home
                      )
            )
* $input_name **type** - name of input
* $use_radio **mixed**
* $use_search **mixed**
* $disabled_categories **mixed**



### <a name="method-selectInput"></a>selectInput

```php
string HelperCore::selectInput(array $values, array $html_options, array $select_options)
```

Create a select input field



* Visibility: **public**
* This method is **static**.
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 219](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L219)


#### Arguments
* $values **array**
* $html_options **array** - any key =&gt; value options
* $select_options **array** - 
key: the array value that will be used as a key in my select (optional)
value: the array value that will be used as a label in my select (optional)
empty: the label displayed as an empty value (optional)
selected: the key corresponding to the selected value  (optional)




### <a name="method-setTpl"></a>setTpl

```php
mixed HelperCore::setTpl($tpl)
```





* Visibility: **public**
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/Helper.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Helper.php#L69)


#### Arguments
* $tpl **mixed**


