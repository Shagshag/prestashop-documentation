Adapter_ServiceLocator
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


* Class name: Adapter_ServiceLocator
* Namespace: 





Properties
----------


### $service_container

    private \Core_Foundation_IoC_Container $service_container

Set a service container Instance



* Visibility: **private**
* This property is **static**.


Methods
-------


### setServiceContainerInstance

    mixed Adapter_ServiceLocator::setServiceContainerInstance(\Core_Foundation_IoC_Container $container)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $container **[Core_Foundation_IoC_Container](Core_Foundation_IoC_Container.md)**



### get

    mixed|object Adapter_ServiceLocator::get($serviceName)

Get a service depending on its given $serviceName



* Visibility: **public**
* This method is **static**.


#### Arguments
* $serviceName **mixed**


