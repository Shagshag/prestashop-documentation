HelperListCore
===============






* Class name: HelperListCore
* Parent class: [Helper](HelperCore)
* This class is defined in [classes/helper/HelperList.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L30)





Properties
----------

* [$_list](#property-$_list)
* [$listTotal](#property-$listTotal)
* [$_filter](#property-$_filter)
* [$_pagination](#property-$_pagination)
* [$_default_pagination](#property-$_default_pagination)
* [$orderBy](#property-$orderBy)
* [$_defaultOrderBy](#property-$_defaultOrderBy)
* [$tpl_delete_link_vars](#property-$tpl_delete_link_vars)
* [$orderWay](#property-$orderWay)
* [$identifier](#property-$identifier)
* [$deleted](#property-$deleted)
* [$cache_lang](#property-$cache_lang)
* [$is_cms](#property-$is_cms)
* [$position_identifier](#property-$position_identifier)
* [$table_id](#property-$table_id)
* [$fields_list](#property-$fields_list)
* [$no_link](#property-$no_link)
* [$header_tpl](#property-$header_tpl)
* [$content_tpl](#property-$content_tpl)
* [$footer_tpl](#property-$footer_tpl)
* [$actions](#property-$actions)
* [$list_skip_actions](#property-$list_skip_actions)
* [$bulk_actions](#property-$bulk_actions)
* [$force_show_bulk_actions](#property-$force_show_bulk_actions)
* [$specificConfirmDelete](#property-$specificConfirmDelete)
* [$colorOnBackground](#property-$colorOnBackground)
* [$row_hover](#property-$row_hover)
* [$title](#property-$title)
* [$simple_header](#property-$simple_header)
* [$ajax_params](#property-$ajax_params)
* [$page](#property-$page)

Methods
-------
* [__construct](#method-__construct)
* [generateList](#method-generateList)
* [displayEnableLink](#method-displayEnableLink)
* [displayListContent](#method-displayListContent)
* [displayDuplicateLink](#method-displayDuplicateLink)
* [displayDetailsLink](#method-displayDetailsLink)
* [displayViewLink](#method-displayViewLink)
* [displayEditLink](#method-displayEditLink)
* [displayDeleteLink](#method-displayDeleteLink)
* [displayDefaultLink](#method-displayDefaultLink)
* [displayListHeader](#method-displayListHeader)
* [hasBulkActions](#method-hasBulkActions)
* [displayListFooter](#method-displayListFooter)




Properties
----------


### <a name="property-$_list"></a>$_list

    protected array $_list = array()





* Visibility: **protected**
* This property is defined in [classes/helper/HelperList.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L33)


### <a name="property-$listTotal"></a>$listTotal

    public integer $listTotal





* Visibility: **public**
* This property is defined in [classes/helper/HelperList.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L36)


### <a name="property-$_filter"></a>$_filter

    protected array $_filter





* Visibility: **protected**
* This property is defined in [classes/helper/HelperList.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L39)


### <a name="property-$_pagination"></a>$_pagination

    public array $_pagination = array(20, 50, 100, 300, 1000)





* Visibility: **public**
* This property is defined in [classes/helper/HelperList.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L42)


### <a name="property-$_default_pagination"></a>$_default_pagination

    public integer $_default_pagination = 50





* Visibility: **public**
* This property is defined in [classes/helper/HelperList.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L45)


### <a name="property-$orderBy"></a>$orderBy

    public string $orderBy





* Visibility: **public**
* This property is defined in [classes/helper/HelperList.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L48)


### <a name="property-$_defaultOrderBy"></a>$_defaultOrderBy

    public string $_defaultOrderBy = false





* Visibility: **public**
* This property is defined in [classes/helper/HelperList.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L51)


### <a name="property-$tpl_delete_link_vars"></a>$tpl_delete_link_vars

    public array $tpl_delete_link_vars = array()





* Visibility: **public**
* This property is defined in [classes/helper/HelperList.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L54)


### <a name="property-$orderWay"></a>$orderWay

    public string $orderWay





* Visibility: **public**
* This property is defined in [classes/helper/HelperList.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L57)


### <a name="property-$identifier"></a>$identifier

    public mixed $identifier





* Visibility: **public**
* This property is defined in [classes/helper/HelperList.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L59)


### <a name="property-$deleted"></a>$deleted

    protected mixed $deleted





* Visibility: **protected**
* This property is defined in [classes/helper/HelperList.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L61)


### <a name="property-$cache_lang"></a>$cache_lang

    public array $cache_lang = array()





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/helper/HelperList.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L64)


### <a name="property-$is_cms"></a>$is_cms

    public mixed $is_cms = false





* Visibility: **public**
* This property is defined in [classes/helper/HelperList.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L66)


### <a name="property-$position_identifier"></a>$position_identifier

    public mixed $position_identifier





* Visibility: **public**
* This property is defined in [classes/helper/HelperList.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L68)


### <a name="property-$table_id"></a>$table_id

    public mixed $table_id





* Visibility: **public**
* This property is defined in [classes/helper/HelperList.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L70)


### <a name="property-$fields_list"></a>$fields_list

    protected array $fields_list





* Visibility: **protected**
* This property is defined in [classes/helper/HelperList.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L82)


### <a name="property-$no_link"></a>$no_link

    public boolean $no_link = false





* Visibility: **public**
* This property is defined in [classes/helper/HelperList.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L85)


### <a name="property-$header_tpl"></a>$header_tpl

    protected \Smarty_Internal_Template $header_tpl = 'list_header.tpl'





* Visibility: **protected**
* This property is defined in [classes/helper/HelperList.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L88)


### <a name="property-$content_tpl"></a>$content_tpl

    protected \Smarty_Internal_Template $content_tpl = 'list_content.tpl'





* Visibility: **protected**
* This property is defined in [classes/helper/HelperList.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L91)


### <a name="property-$footer_tpl"></a>$footer_tpl

    protected \Smarty_Internal_Template $footer_tpl = 'list_footer.tpl'





* Visibility: **protected**
* This property is defined in [classes/helper/HelperList.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L94)


### <a name="property-$actions"></a>$actions

    public array $actions = array()





* Visibility: **public**
* This property is defined in [classes/helper/HelperList.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L97)


### <a name="property-$list_skip_actions"></a>$list_skip_actions

    public array $list_skip_actions = array()





* Visibility: **public**
* This property is defined in [classes/helper/HelperList.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L100)


### <a name="property-$bulk_actions"></a>$bulk_actions

    public mixed $bulk_actions = false





* Visibility: **public**
* This property is defined in [classes/helper/HelperList.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L102)


### <a name="property-$force_show_bulk_actions"></a>$force_show_bulk_actions

    public mixed $force_show_bulk_actions = false





* Visibility: **public**
* This property is defined in [classes/helper/HelperList.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L103)


### <a name="property-$specificConfirmDelete"></a>$specificConfirmDelete

    public mixed $specificConfirmDelete = null





* Visibility: **public**
* This property is defined in [classes/helper/HelperList.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L104)


### <a name="property-$colorOnBackground"></a>$colorOnBackground

    public mixed $colorOnBackground





* Visibility: **public**
* This property is defined in [classes/helper/HelperList.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L105)


### <a name="property-$row_hover"></a>$row_hover

    public boolean $row_hover = true





* Visibility: **public**
* This property is defined in [classes/helper/HelperList.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L108)


### <a name="property-$title"></a>$title

    public string $title = null





* Visibility: **public**
* This property is defined in [classes/helper/HelperList.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L111)


### <a name="property-$simple_header"></a>$simple_header

    public boolean $simple_header = false





* Visibility: **public**
* This property is defined in [classes/helper/HelperList.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L114)


### <a name="property-$ajax_params"></a>$ajax_params

    public mixed $ajax_params = array()





* Visibility: **public**
* This property is defined in [classes/helper/HelperList.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L116)


### <a name="property-$page"></a>$page

    public mixed $page





* Visibility: **public**
* This property is defined in [classes/helper/HelperList.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L118)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed HelperListCore::__construct()





* Visibility: **public**
* This method is defined in [classes/helper/HelperList.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L120)




### <a name="method-generateList"></a>generateList

    string HelperListCore::generateList(array $list, array $fields_display)

Return an html list given the data to fill it up



* Visibility: **public**
* This method is defined in [classes/helper/HelperList.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L135)


#### Arguments
* $list **array** - &lt;p&gt;entries to display (rows)&lt;/p&gt;
* $fields_display **array** - &lt;p&gt;fields (cols)&lt;/p&gt;



### <a name="method-displayEnableLink"></a>displayEnableLink

    string HelperListCore::displayEnableLink(string $token, string $id, integer $value, string $active, integer $id_category, integer $id_product, $ajax)

Fetch the template for action enable



* Visibility: **public**
* This method is defined in [classes/helper/HelperList.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L173)


#### Arguments
* $token **string**
* $id **string**
* $value **integer** - &lt;p&gt;state enabled or not&lt;/p&gt;
* $active **string** - &lt;p&gt;status&lt;/p&gt;
* $id_category **integer**
* $id_product **integer**
* $ajax **mixed**



### <a name="method-displayListContent"></a>displayListContent

    mixed HelperListCore::displayListContent()





* Visibility: **public**
* This method is defined in [classes/helper/HelperList.php line 185](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L185)




### <a name="method-displayDuplicateLink"></a>displayDuplicateLink

    mixed HelperListCore::displayDuplicateLink($token, $id, $name)

Display duplicate action link



* Visibility: **public**
* This method is defined in [classes/helper/HelperList.php line 362](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L362)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### <a name="method-displayDetailsLink"></a>displayDetailsLink

    mixed HelperListCore::displayDetailsLink($token, $id, $name)

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
* This method is defined in [classes/helper/HelperList.php line 412](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L412)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### <a name="method-displayViewLink"></a>displayViewLink

    mixed HelperListCore::displayViewLink($token, $id, $name)

Display view action link



* Visibility: **public**
* This method is defined in [classes/helper/HelperList.php line 439](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L439)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### <a name="method-displayEditLink"></a>displayEditLink

    mixed HelperListCore::displayEditLink($token, $id, $name)

Display edit action link



* Visibility: **public**
* This method is defined in [classes/helper/HelperList.php line 457](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L457)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### <a name="method-displayDeleteLink"></a>displayDeleteLink

    mixed HelperListCore::displayDeleteLink($token, $id, $name)

Display delete action link



* Visibility: **public**
* This method is defined in [classes/helper/HelperList.php line 476](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L476)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### <a name="method-displayDefaultLink"></a>displayDefaultLink

    mixed HelperListCore::displayDefaultLink($token, $id, $name)

Display default action link



* Visibility: **public**
* This method is defined in [classes/helper/HelperList.php line 514](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L514)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### <a name="method-displayListHeader"></a>displayListHeader

    mixed HelperListCore::displayListHeader()

Display list header (filtering, pagination and column names)



* Visibility: **public**
* This method is defined in [classes/helper/HelperList.php line 533](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L533)




### <a name="method-hasBulkActions"></a>hasBulkActions

    mixed HelperListCore::hasBulkActions($has_value)





* Visibility: **public**
* This method is defined in [classes/helper/HelperList.php line 707](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L707)


#### Arguments
* $has_value **mixed**



### <a name="method-displayListFooter"></a>displayListFooter

    mixed HelperListCore::displayListFooter()

Close list table and submit button



* Visibility: **public**
* This method is defined in [classes/helper/HelperList.php line 738](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperList.php#L738)



