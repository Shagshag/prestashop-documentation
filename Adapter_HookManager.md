Adapter_HookManager
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


* Class name: Adapter_HookManager
* This class is defined in [Adapter/Adapter_HookManager.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Adapter/Adapter_HookManager.php#L27)







Methods
-------


### exec

    \string/array Adapter_HookManager::exec(string $hook_name, array $hook_args, integer $id_module, boolean $array_return, boolean $check_exceptions, boolean $use_push, integer $id_shop)

Execute modules for specified hook



* Visibility: **public**
* This method is defined in [Adapter/Adapter_HookManager.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Adapter/Adapter_HookManager.php#44)


#### Arguments
* $hook_name **string** - &lt;p&gt;Hook Name&lt;/p&gt;
* $hook_args **array** - &lt;p&gt;Parameters for the functions&lt;/p&gt;
* $id_module **integer** - &lt;p&gt;Execute hook for this module only&lt;/p&gt;
* $array_return **boolean** - &lt;p&gt;If specified, module output will be set by name in an array&lt;/p&gt;
* $check_exceptions **boolean** - &lt;p&gt;Check permission exceptions&lt;/p&gt;
* $use_push **boolean** - &lt;p&gt;Force change to be refreshed on Dashboard widgets&lt;/p&gt;
* $id_shop **integer** - &lt;p&gt;If specified, hook will be execute the shop with this ID&lt;/p&gt;


