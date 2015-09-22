Class HookCore
=====================

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
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Hook.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L27)



Properties
----------

* [$_hook_modules_cache](#property-$_hook_modules_cache)
* [$_hook_modules_cache_exec](#property-$_hook_modules_cache_exec)
* [$definition](#property-$definition)
* [$description](#property-$description)
* [$executed_hooks](#property-$executed_hooks)
* [$live_edit](#property-$live_edit)
* [$name](#property-$name)
* [$native_module](#property-$native_module)
* [$position](#property-$position)
* [$title](#property-$title)

Methods
-------
* [PDFInvoice](#method-PDFInvoice)
* [add](#method-add)
* [addProduct](#method-addProduct)
* [backBeforePayment](#method-backBeforePayment)
* [coreCallHook](#method-coreCallHook)
* [deleteProduct](#method-deleteProduct)
* [exec](#method-exec)
* [get](#method-get)
* [getHookAliasList](#method-getHookAliasList)
* [getHookModuleExecList](#method-getHookModuleExecList)
* [getHookModuleList](#method-getHookModuleList)
* [getHooks](#method-getHooks)
* [getIdByName](#method-getIdByName)
* [getLiveEditById](#method-getLiveEditById)
* [getModulesFromHook](#method-getModulesFromHook)
* [getNameById](#method-getNameById)
* [getRetroHookName](#method-getRetroHookName)
* [newOrder](#method-newOrder)
* [orderConfirmation](#method-orderConfirmation)
* [paymentReturn](#method-paymentReturn)
* [postUpdateOrderStatus](#method-postUpdateOrderStatus)
* [preloadHookModulesCache](#method-preloadHookModulesCache)
* [productFooter](#method-productFooter)
* [productOutOfStock](#method-productOutOfStock)
* [updateCarrier](#method-updateCarrier)
* [updateOrderStatus](#method-updateOrderStatus)
* [updateProduct](#method-updateProduct)
* [updateProductAttribute](#method-updateProductAttribute)
* [updateQuantity](#method-updateQuantity)
* [wrapLiveEdit](#method-wrapLiveEdit)




Properties
----------


### <a name="property-$_hook_modules_cache"></a>$_hook_modules_cache

    protected mixed $_hook_modules_cache = null





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Hook.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L79)


### <a name="property-$_hook_modules_cache_exec"></a>$_hook_modules_cache_exec

    protected mixed $_hook_modules_cache_exec = null





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Hook.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L84)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'hook', 'primary' => 'id_hook', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isHookName', 'required' => true, 'size' => 64), 'title' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName'), 'description' => array('type' => self::TYPE_HTML, 'validate' => 'isCleanHtml'), 'position' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'live_edit' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))





* Visibility: **public**
* This property is **static**.
* Source: [classes/Hook.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L64)


### <a name="property-$description"></a>$description

    public string $description





* Visibility: **public**
* Source: [classes/Hook.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L42)


### <a name="property-$executed_hooks"></a>$executed_hooks

    public array $executed_hooks = array()





* Visibility: **public**
* This property is **static**.
* Source: [classes/Hook.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L57)


### <a name="property-$live_edit"></a>$live_edit

    public boolean $live_edit = false





* Visibility: **public**
* Source: [classes/Hook.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L52)


### <a name="property-$name"></a>$name

    public string $name





* Visibility: **public**
* Source: [classes/Hook.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L32)


### <a name="property-$native_module"></a>$native_module

    public mixed $native_module





* Visibility: **public**
* This property is **static**.
* Source: [classes/Hook.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L59)


### <a name="property-$position"></a>$position

    public boolean $position = false





* Visibility: **public**
* Source: [classes/Hook.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L47)


### <a name="property-$title"></a>$title

    public string $title





* Visibility: **public**
* Source: [classes/Hook.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L37)


Methods
-------


### <a name="method-PDFInvoice"></a>PDFInvoice

    mixed HookCore::PDFInvoice($pdf, $id_order)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 699](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L699)


#### Arguments
* $pdf **mixed**
* $id_order **mixed**



### <a name="method-add"></a>add

    mixed HookCore::add($autodate, $null_values)





* Visibility: **public**
* Source: [classes/Hook.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L86)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addProduct"></a>addProduct

    mixed HookCore::addProduct($product)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 829](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L829)


#### Arguments
* $product **mixed**



### <a name="method-backBeforePayment"></a>backBeforePayment

    mixed HookCore::backBeforePayment($module)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 711](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L711)


#### Arguments
* $module **mixed**



### <a name="method-coreCallHook"></a>coreCallHook

    mixed HookCore::coreCallHook($module, $method, $params)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 574](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L574)


#### Arguments
* $module **mixed**
* $method **mixed**
* $params **mixed**



### <a name="method-deleteProduct"></a>deleteProduct

    mixed HookCore::deleteProduct($product)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 847](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L847)


#### Arguments
* $product **mixed**



### <a name="method-exec"></a>exec

    \string/array HookCore::exec(string $hook_name, array $hook_args, integer $id_module, boolean $array_return, boolean $check_exceptions, boolean $use_push, integer $id_shop)

Execute modules for specified hook



* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 421](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L421)


#### Arguments
* $hook_name **string** - Hook Name
* $hook_args **array** - Parameters for the functions
* $id_module **integer** - Execute hook for this module only
* $array_return **boolean** - If specified, module output will be set by name in an array
* $check_exceptions **boolean** - Check permission exceptions
* $use_push **boolean** - Force change to be refreshed on Dashboard widgets
* $id_shop **integer** - If specified, hook will be execute the shop with this ID



### <a name="method-get"></a>get

    integer HookCore::get(string $hook_name)

Return hook ID from name



* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 758](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L758)


#### Arguments
* $hook_name **string** - Hook name



### <a name="method-getHookAliasList"></a>getHookAliasList

    array HookCore::getHookAliasList()

Get list of hook alias



* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 183](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L183)




### <a name="method-getHookModuleExecList"></a>getHookModuleExecList

    array HookCore::getHookModuleExecList(string $hook_name)

Get list of modules we can execute per hook



* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 291](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L291)


#### Arguments
* $hook_name **string** - Get list of modules for this hook if given



### <a name="method-getHookModuleList"></a>getHookModuleList

    array HookCore::getHookModuleList()

Get list of all registered hooks with modules



* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 227](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L227)




### <a name="method-getHooks"></a>getHooks

    array HookCore::getHooks(boolean $position)

Return Hooks List



* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L98)


#### Arguments
* $position **boolean**



### <a name="method-getIdByName"></a>getIdByName

    integer HookCore::getIdByName(string $hook_name)

Return hook ID from name



* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L113)


#### Arguments
* $hook_name **string** - Hook name



### <a name="method-getLiveEditById"></a>getLiveEditById

    mixed HookCore::getLiveEditById($hook_id)

Return hook live edit bool from ID



* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L163)


#### Arguments
* $hook_id **mixed**



### <a name="method-getModulesFromHook"></a>getModulesFromHook

    array HookCore::getModulesFromHook(integer $id_hook, integer $id_module)

Return Hooks List



* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 273](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L273)


#### Arguments
* $id_hook **integer**
* $id_module **integer**



### <a name="method-getNameById"></a>getNameById

    mixed HookCore::getNameById($hook_id)

Return hook ID from name



* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L146)


#### Arguments
* $hook_id **mixed**



### <a name="method-getRetroHookName"></a>getRetroHookName

    integer HookCore::getRetroHookName(string $hook_name)

Return backward compatibility hook name



* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 207](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L207)


#### Arguments
* $hook_name **string** - Hook name



### <a name="method-newOrder"></a>newOrder

    string HookCore::newOrder(\Cart $cart, \Order $order, \Customer $customer, \Currency $currency, $order_status)

Called when quantity of a product is updated.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 788](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L788)


#### Arguments
* $cart **[Cart](class.CartCore.md)**
* $order **[Order](class.OrderCore.md)**
* $customer **[Customer](class.CustomerCore.md)**
* $currency **[Currency](class.CurrencyCore.md)**
* $order_status **mixed**



### <a name="method-orderConfirmation"></a>orderConfirmation

    mixed HookCore::orderConfirmation($id_order)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 651](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L651)


#### Arguments
* $id_order **mixed**



### <a name="method-paymentReturn"></a>paymentReturn

    mixed HookCore::paymentReturn($id_order, $id_module)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 675](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L675)


#### Arguments
* $id_order **mixed**
* $id_module **mixed**



### <a name="method-postUpdateOrderStatus"></a>postUpdateOrderStatus

    mixed HookCore::postUpdateOrderStatus($new_order_status_id, $id_order)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 639](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L639)


#### Arguments
* $new_order_status_id **mixed**
* $id_order **mixed**



### <a name="method-preloadHookModulesCache"></a>preloadHookModulesCache

    boolean HookCore::preloadHookModulesCache()

Preload hook modules cache



* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 738](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L738)




### <a name="method-productFooter"></a>productFooter

    mixed HookCore::productFooter($product, $category)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 811](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L811)


#### Arguments
* $product **mixed**
* $category **mixed**



### <a name="method-productOutOfStock"></a>productOutOfStock

    mixed HookCore::productOutOfStock($product)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 820](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L820)


#### Arguments
* $product **mixed**



### <a name="method-updateCarrier"></a>updateCarrier

    mixed HookCore::updateCarrier($id_carrier, $carrier)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 722](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L722)


#### Arguments
* $id_carrier **mixed**
* $carrier **mixed**



### <a name="method-updateOrderStatus"></a>updateOrderStatus

    mixed HookCore::updateOrderStatus($new_order_status_id, $id_order)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 625](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L625)


#### Arguments
* $new_order_status_id **mixed**
* $id_order **mixed**



### <a name="method-updateProduct"></a>updateProduct

    mixed HookCore::updateProduct($product)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 838](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L838)


#### Arguments
* $product **mixed**



### <a name="method-updateProductAttribute"></a>updateProductAttribute

    mixed HookCore::updateProductAttribute($id_product_attribute)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 856](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L856)


#### Arguments
* $id_product_attribute **mixed**



### <a name="method-updateQuantity"></a>updateQuantity

    mixed HookCore::updateQuantity($product, $order)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 802](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L802)


#### Arguments
* $product **mixed**
* $order **mixed**



### <a name="method-wrapLiveEdit"></a>wrapLiveEdit

    mixed HookCore::wrapLiveEdit($display, $moduleInstance, $id_hook)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Hook.php line 607](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Hook.php#L607)


#### Arguments
* $display **mixed**
* $moduleInstance **mixed**
* $id_hook **mixed**


