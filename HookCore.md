HookCore
===============

2007-2015 PrestaShop

NOTICE OF LICENSE

This source file is subject to the Open Software License (OSL 3.0)
that is bundled with this package in the file LICENSE.txt.
It is also available through the world-wide-web at this URL:
http://opensource.org/licenses/osl-3.0.php
If you did not receive a copy of the license and are unable to
obtain it through the world-wide-web, please send an email
to license@prestashop.com so we can send you a copy immediately.

DISCLAIMER

Do not edit or add to this file if you wish to upgrade PrestaShop to newer
versions in the future. If you wish to customize PrestaShop for your
needs please refer to http://www.prestashop.com for more information.


* Class name: HookCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)

* This class is defined in [classes/Hook.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#27)





Properties
----------


### $name

    public string $name





* Visibility: **public**
* This property is defined in [classes/Hook.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#32)


### $title

    public string $title





* Visibility: **public**
* This property is defined in [classes/Hook.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#37)


### $description

    public string $description





* Visibility: **public**
* This property is defined in [classes/Hook.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#42)


### $position

    public boolean $position = false





* Visibility: **public**
* This property is defined in [classes/Hook.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#47)


### $live_edit

    public boolean $live_edit = false





* Visibility: **public**
* This property is defined in [classes/Hook.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#52)


### $executed_hooks

    public array $executed_hooks = array()





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Hook.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#57)


### $native_module

    public mixed $native_module





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Hook.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#59)


### $definition

    public mixed $definition = array('table' => 'hook', 'primary' => 'id_hook', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isHookName', 'required' => true, 'size' => 64), 'title' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName'), 'description' => array('type' => self::TYPE_HTML, 'validate' => 'isCleanHtml'), 'position' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'live_edit' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Hook.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#64)


### $_hook_modules_cache

    protected mixed $_hook_modules_cache = null





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Hook.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#79)


### $_hook_modules_cache_exec

    protected mixed $_hook_modules_cache_exec = null





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Hook.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#84)


Methods
-------


### add

    mixed HookCore::add($autodate, $null_values)





* Visibility: **public**
* This method is defined in [classes/Hook.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#86)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### getHooks

    array HookCore::getHooks(boolean $position)

Return Hooks List



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Hook.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#98)


#### Arguments
* $position **boolean**



### getIdByName

    integer HookCore::getIdByName(string $hook_name)

Return hook ID from name



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Hook.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#113)


#### Arguments
* $hook_name **string** - &lt;p&gt;Hook name&lt;/p&gt;



### getNameById

    mixed HookCore::getNameById($hook_id)

Return hook ID from name



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Hook.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#146)


#### Arguments
* $hook_id **mixed**



### getLiveEditById

    mixed HookCore::getLiveEditById($hook_id)

Return hook live edit bool from ID



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Hook.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#163)


#### Arguments
* $hook_id **mixed**



### getHookAliasList

    array HookCore::getHookAliasList()

Get list of hook alias



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Hook.php line 183](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#183)




### getRetroHookName

    integer HookCore::getRetroHookName(string $hook_name)

Return backward compatibility hook name



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Hook.php line 207](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#207)


#### Arguments
* $hook_name **string** - &lt;p&gt;Hook name&lt;/p&gt;



### getHookModuleList

    array HookCore::getHookModuleList()

Get list of all registered hooks with modules



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Hook.php line 227](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#227)




### getModulesFromHook

    array HookCore::getModulesFromHook(integer $id_hook, integer $id_module)

Return Hooks List



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Hook.php line 273](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#273)


#### Arguments
* $id_hook **integer**
* $id_module **integer**



### getHookModuleExecList

    array HookCore::getHookModuleExecList(string $hook_name)

Get list of modules we can execute per hook



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Hook.php line 291](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#291)


#### Arguments
* $hook_name **string** - &lt;p&gt;Get list of modules for this hook if given&lt;/p&gt;



### exec

    \string/array HookCore::exec(string $hook_name, array $hook_args, integer $id_module, boolean $array_return, boolean $check_exceptions, boolean $use_push, integer $id_shop)

Execute modules for specified hook



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Hook.php line 421](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#421)


#### Arguments
* $hook_name **string** - &lt;p&gt;Hook Name&lt;/p&gt;
* $hook_args **array** - &lt;p&gt;Parameters for the functions&lt;/p&gt;
* $id_module **integer** - &lt;p&gt;Execute hook for this module only&lt;/p&gt;
* $array_return **boolean** - &lt;p&gt;If specified, module output will be set by name in an array&lt;/p&gt;
* $check_exceptions **boolean** - &lt;p&gt;Check permission exceptions&lt;/p&gt;
* $use_push **boolean** - &lt;p&gt;Force change to be refreshed on Dashboard widgets&lt;/p&gt;
* $id_shop **integer** - &lt;p&gt;If specified, hook will be execute the shop with this ID&lt;/p&gt;



### coreCallHook

    mixed HookCore::coreCallHook($module, $method, $params)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Hook.php line 574](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#574)


#### Arguments
* $module **mixed**
* $method **mixed**
* $params **mixed**



### wrapLiveEdit

    mixed HookCore::wrapLiveEdit($display, $moduleInstance, $id_hook)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Hook.php line 607](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#607)


#### Arguments
* $display **mixed**
* $moduleInstance **mixed**
* $id_hook **mixed**



### updateOrderStatus

    mixed HookCore::updateOrderStatus($new_order_status_id, $id_order)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Hook.php line 625](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#625)


#### Arguments
* $new_order_status_id **mixed**
* $id_order **mixed**



### postUpdateOrderStatus

    mixed HookCore::postUpdateOrderStatus($new_order_status_id, $id_order)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Hook.php line 639](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#639)


#### Arguments
* $new_order_status_id **mixed**
* $id_order **mixed**



### orderConfirmation

    mixed HookCore::orderConfirmation($id_order)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Hook.php line 651](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#651)


#### Arguments
* $id_order **mixed**



### paymentReturn

    mixed HookCore::paymentReturn($id_order, $id_module)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Hook.php line 675](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#675)


#### Arguments
* $id_order **mixed**
* $id_module **mixed**



### PDFInvoice

    mixed HookCore::PDFInvoice($pdf, $id_order)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Hook.php line 699](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#699)


#### Arguments
* $pdf **mixed**
* $id_order **mixed**



### backBeforePayment

    mixed HookCore::backBeforePayment($module)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Hook.php line 711](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#711)


#### Arguments
* $module **mixed**



### updateCarrier

    mixed HookCore::updateCarrier($id_carrier, $carrier)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Hook.php line 722](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#722)


#### Arguments
* $id_carrier **mixed**
* $carrier **mixed**



### preloadHookModulesCache

    boolean HookCore::preloadHookModulesCache()

Preload hook modules cache



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Hook.php line 738](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#738)




### get

    integer HookCore::get(string $hook_name)

Return hook ID from name



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Hook.php line 758](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#758)


#### Arguments
* $hook_name **string** - &lt;p&gt;Hook name&lt;/p&gt;



### newOrder

    string HookCore::newOrder(\Cart $cart, \Order $order, \Customer $customer, \Currency $currency, $order_status)

Called when quantity of a product is updated.



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Hook.php line 788](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#788)


#### Arguments
* $cart **[Cart](CartCore)**
* $order **[Order](OrderCore)**
* $customer **[Customer](CustomerCore)**
* $currency **[Currency](CurrencyCore)**
* $order_status **mixed**



### updateQuantity

    mixed HookCore::updateQuantity($product, $order)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Hook.php line 802](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#802)


#### Arguments
* $product **mixed**
* $order **mixed**



### productFooter

    mixed HookCore::productFooter($product, $category)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Hook.php line 811](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#811)


#### Arguments
* $product **mixed**
* $category **mixed**



### productOutOfStock

    mixed HookCore::productOutOfStock($product)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Hook.php line 820](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#820)


#### Arguments
* $product **mixed**



### addProduct

    mixed HookCore::addProduct($product)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Hook.php line 829](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#829)


#### Arguments
* $product **mixed**



### updateProduct

    mixed HookCore::updateProduct($product)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Hook.php line 838](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#838)


#### Arguments
* $product **mixed**



### deleteProduct

    mixed HookCore::deleteProduct($product)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Hook.php line 847](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#847)


#### Arguments
* $product **mixed**



### updateProductAttribute

    mixed HookCore::updateProductAttribute($id_product_attribute)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Hook.php line 856](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#856)


#### Arguments
* $id_product_attribute **mixed**


