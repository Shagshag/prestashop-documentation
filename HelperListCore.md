HelperListCore
===============






* Class name: HelperListCore
* Namespace: 
* Parent class: Helper





Properties
----------


### $_list

    protected array $_list = array()





* Visibility: **protected**


### $listTotal

    public integer $listTotal





* Visibility: **public**


### $_filter

    protected array $_filter





* Visibility: **protected**


### $_pagination

    public array $_pagination = array(20, 50, 100, 300, 1000)





* Visibility: **public**


### $_default_pagination

    public integer $_default_pagination = 50





* Visibility: **public**


### $orderBy

    public string $orderBy





* Visibility: **public**


### $_defaultOrderBy

    public string $_defaultOrderBy = false





* Visibility: **public**


### $tpl_delete_link_vars

    public array $tpl_delete_link_vars = array()





* Visibility: **public**


### $orderWay

    public string $orderWay





* Visibility: **public**


### $identifier

    public mixed $identifier





* Visibility: **public**


### $deleted

    protected mixed $deleted





* Visibility: **protected**


### $cache_lang

    public array $cache_lang = array()





* Visibility: **public**
* This property is **static**.


### $is_cms

    public mixed $is_cms = false





* Visibility: **public**


### $position_identifier

    public mixed $position_identifier





* Visibility: **public**


### $table_id

    public mixed $table_id





* Visibility: **public**


### $fields_list

    protected array $fields_list





* Visibility: **protected**


### $no_link

    public boolean $no_link = false





* Visibility: **public**


### $header_tpl

    protected \Smarty_Internal_Template $header_tpl = 'list_header.tpl'





* Visibility: **protected**


### $content_tpl

    protected \Smarty_Internal_Template $content_tpl = 'list_content.tpl'





* Visibility: **protected**


### $footer_tpl

    protected \Smarty_Internal_Template $footer_tpl = 'list_footer.tpl'





* Visibility: **protected**


### $actions

    public array $actions = array()





* Visibility: **public**


### $list_skip_actions

    public array $list_skip_actions = array()





* Visibility: **public**


### $bulk_actions

    public mixed $bulk_actions = false





* Visibility: **public**


### $force_show_bulk_actions

    public mixed $force_show_bulk_actions = false





* Visibility: **public**


### $specificConfirmDelete

    public mixed $specificConfirmDelete = null





* Visibility: **public**


### $colorOnBackground

    public mixed $colorOnBackground





* Visibility: **public**


### $row_hover

    public boolean $row_hover = true





* Visibility: **public**


### $title

    public string $title = null





* Visibility: **public**


### $simple_header

    public boolean $simple_header = false





* Visibility: **public**


### $ajax_params

    public mixed $ajax_params = array()





* Visibility: **public**


### $page

    public mixed $page





* Visibility: **public**


Methods
-------


### __construct

    mixed HelperListCore::__construct()





* Visibility: **public**




### generateList

    string HelperListCore::generateList(array $list, array $fields_display)

Return an html list given the data to fill it up



* Visibility: **public**


#### Arguments
* $list **array** - &lt;p&gt;entries to display (rows)&lt;/p&gt;
* $fields_display **array** - &lt;p&gt;fields (cols)&lt;/p&gt;



### displayEnableLink

    string HelperListCore::displayEnableLink(string $token, string $id, integer $value, string $active, integer $id_category, integer $id_product, $ajax)

Fetch the template for action enable



* Visibility: **public**


#### Arguments
* $token **string**
* $id **string**
* $value **integer** - &lt;p&gt;state enabled or not&lt;/p&gt;
* $active **string** - &lt;p&gt;status&lt;/p&gt;
* $id_category **integer**
* $id_product **integer**
* $ajax **mixed**



### displayListContent

    mixed HelperListCore::displayListContent()





* Visibility: **public**




### displayDuplicateLink

    mixed HelperListCore::displayDuplicateLink($token, $id, $name)

Display duplicate action link



* Visibility: **public**


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### displayDetailsLink

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


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### displayViewLink

    mixed HelperListCore::displayViewLink($token, $id, $name)

Display view action link



* Visibility: **public**


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### displayEditLink

    mixed HelperListCore::displayEditLink($token, $id, $name)

Display edit action link



* Visibility: **public**


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### displayDeleteLink

    mixed HelperListCore::displayDeleteLink($token, $id, $name)

Display delete action link



* Visibility: **public**


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### displayDefaultLink

    mixed HelperListCore::displayDefaultLink($token, $id, $name)

Display default action link



* Visibility: **public**


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### displayListHeader

    mixed HelperListCore::displayListHeader()

Display list header (filtering, pagination and column names)



* Visibility: **public**




### hasBulkActions

    mixed HelperListCore::hasBulkActions($has_value)





* Visibility: **public**


#### Arguments
* $has_value **mixed**



### displayListFooter

    mixed HelperListCore::displayListFooter()

Close list table and submit button



* Visibility: **public**



