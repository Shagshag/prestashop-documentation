Class HelperListCore
=====================





* Class name: HelperListCore
* Parent class: [Helper](class.HelperCore.md)
* Source: [classes/helper/HelperList.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L30)


Contents
--------


### Properties

* [$_defaultOrderBy](#property-$_defaultOrderBy)
* [$_default_pagination](#property-$_default_pagination)
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
* [$force_show_bulk_actions](#property-$force_show_bulk_actions)
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
* [$table_id](#property-$table_id)
* [$title](#property-$title)
* [$tpl_delete_link_vars](#property-$tpl_delete_link_vars)

### Methods

* [__construct](#method-__construct)
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
* [generateList](#method-generateList)
* [hasBulkActions](#method-hasBulkActions)




Properties
----------


### <a name="property-$_defaultOrderBy"></a>$_defaultOrderBy

```php
public string $_defaultOrderBy = false
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L51).


### <a name="property-$_default_pagination"></a>$_default_pagination

```php
protected integer $_default_pagination = 50
```





* Visibility: **protected**
* Source: [classes/helper/HelperList.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L45).


### <a name="property-$_filter"></a>$_filter

```php
protected array $_filter
```





* Visibility: **protected**
* Source: [classes/helper/HelperList.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L39).


### <a name="property-$_list"></a>$_list

```php
protected array $_list = array()
```





* Visibility: **protected**
* Source: [classes/helper/HelperList.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L33).


### <a name="property-$_pagination"></a>$_pagination

```php
protected array $_pagination = array(20, 50, 100, 300, 1000)
```





* Visibility: **protected**
* Source: [classes/helper/HelperList.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L42).


### <a name="property-$actions"></a>$actions

```php
public array $actions = array()
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L92).


### <a name="property-$ajax_params"></a>$ajax_params

```php
public mixed $ajax_params = array()
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L111).


### <a name="property-$bulk_actions"></a>$bulk_actions

```php
public mixed $bulk_actions = false
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L97).


### <a name="property-$cache_lang"></a>$cache_lang

```php
public array $cache_lang = array()
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/helper/HelperList.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L64).


### <a name="property-$colorOnBackground"></a>$colorOnBackground

```php
public mixed $colorOnBackground
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L100).


### <a name="property-$content_tpl"></a>$content_tpl

```php
protected mixed $content_tpl = 'list_content.tpl'
```





* Visibility: **protected**
* Source: [classes/helper/HelperList.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L88).


### <a name="property-$deleted"></a>$deleted

```php
protected mixed $deleted
```





* Visibility: **protected**
* Source: [classes/helper/HelperList.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L61).


### <a name="property-$fields_list"></a>$fields_list

```php
protected array $fields_list
```





* Visibility: **protected**
* Source: [classes/helper/HelperList.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L82).


### <a name="property-$footer_tpl"></a>$footer_tpl

```php
protected mixed $footer_tpl = 'list_footer.tpl'
```





* Visibility: **protected**
* Source: [classes/helper/HelperList.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L89).


### <a name="property-$force_show_bulk_actions"></a>$force_show_bulk_actions

```php
public mixed $force_show_bulk_actions = false
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L98).


### <a name="property-$header_tpl"></a>$header_tpl

```php
protected mixed $header_tpl = 'list_header.tpl'
```





* Visibility: **protected**
* Source: [classes/helper/HelperList.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L87).


### <a name="property-$identifier"></a>$identifier

```php
public mixed $identifier
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L59).


### <a name="property-$is_cms"></a>$is_cms

```php
public mixed $is_cms = false
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L66).


### <a name="property-$listTotal"></a>$listTotal

```php
public integer $listTotal
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L36).


### <a name="property-$list_skip_actions"></a>$list_skip_actions

```php
public array $list_skip_actions = array()
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L95).


### <a name="property-$no_link"></a>$no_link

```php
public boolean $no_link = false
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L85).


### <a name="property-$orderBy"></a>$orderBy

```php
public string $orderBy
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L48).


### <a name="property-$orderWay"></a>$orderWay

```php
public string $orderWay
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L57).


### <a name="property-$position_identifier"></a>$position_identifier

```php
public mixed $position_identifier
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L68).


### <a name="property-$row_hover"></a>$row_hover

```php
public boolean $row_hover = true
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L103).


### <a name="property-$simple_header"></a>$simple_header

```php
public boolean $simple_header = false
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L109).


### <a name="property-$specificConfirmDelete"></a>$specificConfirmDelete

```php
public mixed $specificConfirmDelete = null
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L99).


### <a name="property-$table_id"></a>$table_id

```php
public mixed $table_id
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L70).


### <a name="property-$title"></a>$title

```php
public \if $title = null
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L106).


### <a name="property-$tpl_delete_link_vars"></a>$tpl_delete_link_vars

```php
public array $tpl_delete_link_vars = array()
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L54).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed HelperListCore::__construct()
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L113)




### <a name="method-displayDefaultLink"></a>displayDefaultLink

```php
mixed HelperListCore::displayDefaultLink($token, $id, $name)
```

Display delete action link



* Visibility: **public**
* Source: [classes/helper/HelperList.php line 486](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L486)


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
* Source: [classes/helper/HelperList.php line 453](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L453)


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
* Source: [classes/helper/HelperList.php line 392](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L392)


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
* Source: [classes/helper/HelperList.php line 350](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L350)


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
* Source: [classes/helper/HelperList.php line 435](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L435)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### <a name="method-displayEnableLink"></a>displayEnableLink

```php
string HelperListCore::displayEnableLink(string $token, integer $id, integer $value, string $active, integer $id_category, integer $id_product, $ajax)
```

Fetch the template for action enable



* Visibility: **public**
* Source: [classes/helper/HelperList.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L167)


#### Arguments
* $token **string**
* $id **integer**
* $value **integer** - state enabled or not
* $active **string** - status
* $id_category **integer**
* $id_product **integer**
* $ajax **mixed**



### <a name="method-displayListContent"></a>displayListContent

```php
mixed HelperListCore::displayListContent()
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L179)




### <a name="method-displayListFooter"></a>displayListFooter

```php
mixed HelperListCore::displayListFooter()
```

Close list table and submit button



* Visibility: **public**
* Source: [classes/helper/HelperList.php line 686](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L686)




### <a name="method-displayListHeader"></a>displayListHeader

```php
mixed HelperListCore::displayListHeader()
```

Display list header (filtering, pagination and column names)



* Visibility: **public**
* Source: [classes/helper/HelperList.php line 504](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L504)




### <a name="method-displayViewLink"></a>displayViewLink

```php
mixed HelperListCore::displayViewLink($token, $id, $name)
```

Display view action link



* Visibility: **public**
* Source: [classes/helper/HelperList.php line 417](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L417)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### <a name="method-generateList"></a>generateList

```php
string HelperListCore::generateList(array $list, array $fields_display)
```

Return an html list given the data to fill it up



* Visibility: **public**
* Source: [classes/helper/HelperList.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L128)


#### Arguments
* $list **array** - entries to display (rows)
* $fields_display **array** - fields (cols)



### <a name="method-hasBulkActions"></a>hasBulkActions

```php
mixed HelperListCore::hasBulkActions($has_value)
```





* Visibility: **public**
* Source: [classes/helper/HelperList.php line 658](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/helper/HelperList.php#L658)


#### Arguments
* $has_value **mixed**


