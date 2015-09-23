Class OrderOpcControllerCore
=====================





* Class name: OrderOpcControllerCore
* Parent class: [ParentOrderController](class.ParentOrderControllerCore.md)
* Source: [controllers/front/OrderOpcController.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/controllers/front/OrderOpcController.php#L28)


Contents
--------


### Properties

* [$isLogged](#property-$isLogged)
* [$php_self](#property-$php_self)
* [$nbProducts](#property-$nbProducts)
* [$ssl](#property-$ssl)
* [$auth](#property-$auth)
* [$authRedirection](#property-$authRedirection)
* [$cart](#property-$cart)
* [$cookie](#property-$cookie)
* [$currentCustomerGroups](#property-$currentCustomerGroups)
* [$display_column_left](#property-$display_column_left)
* [$display_column_right](#property-$display_column_right)
* [$errors](#property-$errors)
* [$guestAllowed](#property-$guestAllowed)
* [$initialized](#property-$initialized)
* [$iso](#property-$iso)
* [$link](#property-$link)
* [$maintenance](#property-$maintenance)
* [$n](#property-$n)
* [$nb_items_per_page](#property-$nb_items_per_page)
* [$orderBy](#property-$orderBy)
* [$orderWay](#property-$orderWay)
* [$p](#property-$p)
* [$restrictedCountry](#property-$restrictedCountry)
* [$smarty](#property-$smarty)
* [$ajax](#property-$ajax)
* [$content_only](#property-$content_only)
* [$context](#property-$context)
* [$css_files](#property-$css_files)
* [$display_footer](#property-$display_footer)
* [$display_header](#property-$display_header)
* [$hook_list](#property-$hook_list)
* [$js_files](#property-$js_files)
* [$json](#property-$json)
* [$redirect_after](#property-$redirect_after)
* [$status](#property-$status)
* [$template](#property-$template)

### Methods

* [__construct](#method-__construct)
* [_assignAddress](#method-_assignAddress)
* [_assignCarrier](#method-_assignCarrier)
* [_assignPayment](#method-_assignPayment)
* [_assignSummaryInformations](#method-_assignSummaryInformations)
* [_assignWrappingAndTOS](#method-_assignWrappingAndTOS)
* [_checkFreeOrder](#method-_checkFreeOrder)
* [_getCarrierList](#method-_getCarrierList)
* [_getGuestInformations](#method-_getGuestInformations)
* [_getPaymentMethods](#method-_getPaymentMethods)
* [_processAddressFormat](#method-_processAddressFormat)
* [_processCarrier](#method-_processCarrier)
* [_setDefaultCarrierSelection](#method-_setDefaultCarrierSelection)
* [_updateMessage](#method-_updateMessage)
* [addCSS](#method-addCSS)
* [addJS](#method-addJS)
* [addJquery](#method-addJquery)
* [addJqueryPlugin](#method-addJqueryPlugin)
* [addJqueryUI](#method-addJqueryUI)
* [canonicalRedirection](#method-canonicalRedirection)
* [checkAccess](#method-checkAccess)
* [display](#method-display)
* [displayFooter](#method-displayFooter)
* [displayHeader](#method-displayHeader)
* [displayMaintenancePage](#method-displayMaintenancePage)
* [displayRestrictedCountryPage](#method-displayRestrictedCountryPage)
* [geolocationManagement](#method-geolocationManagement)
* [getController](#method-getController)
* [getCurrentCustomerGroups](#method-getCurrentCustomerGroups)
* [getLiveEditFooter](#method-getLiveEditFooter)
* [init](#method-init)
* [initContent](#method-initContent)
* [initCursedPage](#method-initCursedPage)
* [initFooter](#method-initFooter)
* [initHeader](#method-initHeader)
* [isInWhitelistForGeolocation](#method-isInWhitelistForGeolocation)
* [isTokenValid](#method-isTokenValid)
* [pagination](#method-pagination)
* [postProcess](#method-postProcess)
* [preProcess](#method-preProcess)
* [process](#method-process)
* [productSort](#method-productSort)
* [recoverCart](#method-recoverCart)
* [redirect](#method-redirect)
* [run](#method-run)
* [setDefaultCarrierSelection](#method-setDefaultCarrierSelection)
* [setMedia](#method-setMedia)
* [setNoCarrier](#method-setNoCarrier)
* [setTemplate](#method-setTemplate)
* [validateDeliveryOption](#method-validateDeliveryOption)




Properties
----------


### <a name="property-$isLogged"></a>$isLogged

```php
public mixed $isLogged
```





* Visibility: **public**
* Source: [controllers/front/OrderOpcController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/controllers/front/OrderOpcController.php#L31).


### <a name="property-$php_self"></a>$php_self

```php
public mixed $php_self = 'order-opc'
```





* Visibility: **public**
* Source: [controllers/front/OrderOpcController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/controllers/front/OrderOpcController.php#L30).


### <a name="property-$nbProducts"></a>$nbProducts

```php
public mixed $nbProducts
```





* Visibility: **public**
* This property is defined by [ParentOrderControllerCore](class.ParentOrderControllerCore.md).
* Source: [controllers/front/ParentOrderController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/controllers/front/ParentOrderController.php#L40).


### <a name="property-$ssl"></a>$ssl

```php
public mixed $ssl = true
```





* Visibility: **public**
* This property is defined by [ParentOrderControllerCore](class.ParentOrderControllerCore.md).
* Source: [controllers/front/ParentOrderController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/controllers/front/ParentOrderController.php#L37).


### <a name="property-$auth"></a>$auth

```php
public mixed $auth = false
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L44).


### <a name="property-$authRedirection"></a>$authRedirection

```php
public mixed $authRedirection = false
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L46).


### <a name="property-$cart"></a>$cart

```php
protected mixed $cart
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L35).


### <a name="property-$cookie"></a>$cookie

```php
protected mixed $cookie
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L35).


### <a name="property-$currentCustomerGroups"></a>$currentCustomerGroups

```php
protected mixed $currentCustomerGroups
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L57).


### <a name="property-$display_column_left"></a>$display_column_left

```php
public mixed $display_column_left = true
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L52).


### <a name="property-$display_column_right"></a>$display_column_right

```php
public mixed $display_column_right = true
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L53).


### <a name="property-$errors"></a>$errors

```php
public mixed $errors = array()
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L30).


### <a name="property-$guestAllowed"></a>$guestAllowed

```php
public mixed $guestAllowed = false
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L45).


### <a name="property-$initialized"></a>$initialized

```php
public mixed $initialized = false
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L55).


### <a name="property-$iso"></a>$iso

```php
public mixed $iso
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L37).


### <a name="property-$link"></a>$link

```php
protected mixed $link
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L35).


### <a name="property-$maintenance"></a>$maintenance

```php
protected mixed $maintenance = false
```





* Visibility: **protected**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L50).


### <a name="property-$n"></a>$n

```php
public mixed $n
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L42).


### <a name="property-$nb_items_per_page"></a>$nb_items_per_page

```php
public mixed $nb_items_per_page
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L59).


### <a name="property-$orderBy"></a>$orderBy

```php
public mixed $orderBy
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L39).


### <a name="property-$orderWay"></a>$orderWay

```php
public mixed $orderWay
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L40).


### <a name="property-$p"></a>$p

```php
public mixed $p
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L41).


### <a name="property-$restrictedCountry"></a>$restrictedCountry

```php
protected mixed $restrictedCountry = false
```





* Visibility: **protected**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L49).


### <a name="property-$smarty"></a>$smarty

```php
protected mixed $smarty
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L35).


### <a name="property-$ajax"></a>$ajax

```php
protected boolean $ajax = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Controller.php#L71).


### <a name="property-$content_only"></a>$content_only

```php
protected string $content_only = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Controller.php#L66).


### <a name="property-$context"></a>$context

```php
protected \Context $context
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Controller.php#L36).


### <a name="property-$css_files"></a>$css_files

```php
public array $css_files = array()
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Controller.php#L41).


### <a name="property-$display_footer"></a>$display_footer

```php
protected string $display_footer
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Controller.php#L61).


### <a name="property-$display_header"></a>$display_header

```php
protected boolean $display_header
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Controller.php#L51).


### <a name="property-$hook_list"></a>$hook_list

```php
public mixed $hook_list = array()
```

hook_list is used with liveEdit



* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Controller.php#L78).


### <a name="property-$js_files"></a>$js_files

```php
public array $js_files = array()
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Controller.php#L46).


### <a name="property-$json"></a>$json

```php
protected mixed $json = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Controller.php#L72).


### <a name="property-$redirect_after"></a>$redirect_after

```php
protected mixed $redirect_after = null
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Controller.php#L75).


### <a name="property-$status"></a>$status

```php
protected mixed $status = ''
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Controller.php#L73).


### <a name="property-$template"></a>$template

```php
protected string $template
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Controller.php#L56).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed FrontControllerCore::__construct()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L61)




### <a name="method-_assignAddress"></a>_assignAddress

```php
mixed ParentOrderControllerCore::_assignAddress()
```





* Visibility: **protected**
* This method is defined by [ParentOrderControllerCore](class.ParentOrderControllerCore.md).
* Source: [controllers/front/ParentOrderController.php line 319](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/controllers/front/ParentOrderController.php#L319)




### <a name="method-_assignCarrier"></a>_assignCarrier

```php
mixed OrderOpcControllerCore::_assignCarrier()
```





* Visibility: **protected**
* Source: [controllers/front/OrderOpcController.php line 358](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/controllers/front/OrderOpcController.php#L358)




### <a name="method-_assignPayment"></a>_assignPayment

```php
mixed OrderOpcControllerCore::_assignPayment()
```





* Visibility: **protected**
* Source: [controllers/front/OrderOpcController.php line 377](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/controllers/front/OrderOpcController.php#L377)




### <a name="method-_assignSummaryInformations"></a>_assignSummaryInformations

```php
mixed ParentOrderControllerCore::_assignSummaryInformations()
```





* Visibility: **protected**
* This method is defined by [ParentOrderControllerCore](class.ParentOrderControllerCore.md).
* Source: [controllers/front/ParentOrderController.php line 266](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/controllers/front/ParentOrderController.php#L266)




### <a name="method-_assignWrappingAndTOS"></a>_assignWrappingAndTOS

```php
mixed ParentOrderControllerCore::_assignWrappingAndTOS()
```





* Visibility: **protected**
* This method is defined by [ParentOrderControllerCore](class.ParentOrderControllerCore.md).
* Source: [controllers/front/ParentOrderController.php line 418](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/controllers/front/ParentOrderController.php#L418)




### <a name="method-_checkFreeOrder"></a>_checkFreeOrder

```php
boolean ParentOrderControllerCore::_checkFreeOrder()
```

Check if order is free



* Visibility: **protected**
* This method is defined by [ParentOrderControllerCore](class.ParentOrderControllerCore.md).
* Source: [controllers/front/ParentOrderController.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/controllers/front/ParentOrderController.php#L155)




### <a name="method-_getCarrierList"></a>_getCarrierList

```php
mixed OrderOpcControllerCore::_getCarrierList()
```





* Visibility: **protected**
* Source: [controllers/front/OrderOpcController.php line 433](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/controllers/front/OrderOpcController.php#L433)




### <a name="method-_getGuestInformations"></a>_getGuestInformations

```php
mixed OrderOpcControllerCore::_getGuestInformations()
```





* Visibility: **protected**
* Source: [controllers/front/OrderOpcController.php line 321](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/controllers/front/OrderOpcController.php#L321)




### <a name="method-_getPaymentMethods"></a>_getPaymentMethods

```php
mixed OrderOpcControllerCore::_getPaymentMethods()
```





* Visibility: **protected**
* Source: [controllers/front/OrderOpcController.php line 385](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/controllers/front/OrderOpcController.php#L385)




### <a name="method-_processAddressFormat"></a>_processAddressFormat

```php
mixed OrderOpcControllerCore::_processAddressFormat()
```





* Visibility: **protected**
* Source: [controllers/front/OrderOpcController.php line 490](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/controllers/front/OrderOpcController.php#L490)




### <a name="method-_processCarrier"></a>_processCarrier

```php
mixed ParentOrderControllerCore::_processCarrier()
```





* Visibility: **protected**
* This method is defined by [ParentOrderControllerCore](class.ParentOrderControllerCore.md).
* Source: [controllers/front/ParentOrderController.php line 199](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/controllers/front/ParentOrderController.php#L199)




### <a name="method-_setDefaultCarrierSelection"></a>_setDefaultCarrierSelection

```php
\number ParentOrderControllerCore::_setDefaultCarrierSelection(array $carriers)
```

Decides what the default carrier is and update the cart with it



* Visibility: **protected**
* This method is defined by [ParentOrderControllerCore](class.ParentOrderControllerCore.md).
* Source: [controllers/front/ParentOrderController.php line 514](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/controllers/front/ParentOrderController.php#L514)


#### Arguments
* $carriers **array**



### <a name="method-_updateMessage"></a>_updateMessage

```php
mixed ParentOrderControllerCore::_updateMessage($messageContent)
```





* Visibility: **protected**
* This method is defined by [ParentOrderControllerCore](class.ParentOrderControllerCore.md).
* Source: [controllers/front/ParentOrderController.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/controllers/front/ParentOrderController.php#L167)


#### Arguments
* $messageContent **mixed**



### <a name="method-addCSS"></a>addCSS

```php
mixed FrontControllerCore::addCSS($css_uri, $css_media_type)
```

Add one or several CSS for front, checking if css files are overriden in theme/css/modules/ directory



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 805](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L805)


#### Arguments
* $css_uri **mixed**
* $css_media_type **mixed**



### <a name="method-addJS"></a>addJS

```php
mixed FrontControllerCore::addJS($js_uri)
```

Add one or several JS files for front, checking if js files are overriden in theme/js/modules/ directory



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 828](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L828)


#### Arguments
* $js_uri **mixed**



### <a name="method-addJquery"></a>addJquery

```php
void ControllerCore::addJquery($version, $folder, $minifier)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 283](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Controller.php#L283)


#### Arguments
* $version **mixed**
* $folder **mixed**
* $minifier **mixed**



### <a name="method-addJqueryPlugin"></a>addJqueryPlugin

```php
void ControllerCore::addJqueryPlugin($name, $folder)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 313](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Controller.php#L313)


#### Arguments
* $name **mixed**
* $folder **mixed**



### <a name="method-addJqueryUI"></a>addJqueryUI

```php
void ControllerCore::addJqueryUI($component, $theme, $check_dependencies)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 294](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Controller.php#L294)


#### Arguments
* $component **mixed**
* $theme **mixed**
* $check_dependencies **mixed**



### <a name="method-canonicalRedirection"></a>canonicalRedirection

```php
mixed FrontControllerCore::canonicalRedirection($canonicalURL)
```





* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 534](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L534)


#### Arguments
* $canonicalURL **mixed**



### <a name="method-checkAccess"></a>checkAccess

```php
void FrontControllerCore::checkAccess()
```

checkAccess



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L74)




### <a name="method-display"></a>display

```php
mixed FrontControllerCore::display()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 455](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L455)




### <a name="method-displayFooter"></a>displayFooter

```php
mixed FrontControllerCore::displayFooter($display)
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 430](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L430)


#### Arguments
* $display **mixed**



### <a name="method-displayHeader"></a>displayHeader

```php
mixed FrontControllerCore::displayHeader($display)
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 398](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L398)


#### Arguments
* $display **mixed**



### <a name="method-displayMaintenancePage"></a>displayMaintenancePage

```php
mixed FrontControllerCore::displayMaintenancePage()
```





* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 516](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L516)




### <a name="method-displayRestrictedCountryPage"></a>displayRestrictedCountryPage

```php
mixed FrontControllerCore::displayRestrictedCountryPage()
```





* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 527](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L527)




### <a name="method-geolocationManagement"></a>geolocationManagement

```php
mixed FrontControllerCore::geolocationManagement($defaultCountry)
```





* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 559](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L559)


#### Arguments
* $defaultCountry **mixed**



### <a name="method-getController"></a>getController

```php
mixed ControllerCore::getController(string $class_name, boolean $auth, boolean $ssl)
```

Get an instance of a controller



* Visibility: **public**
* This method is **static**.
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Controller.php#L122)


#### Arguments
* $class_name **string**
* $auth **boolean**
* $ssl **boolean**



### <a name="method-getCurrentCustomerGroups"></a>getCurrentCustomerGroups

```php
mixed FrontControllerCore::getCurrentCustomerGroups()
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 759](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L759)




### <a name="method-getLiveEditFooter"></a>getLiveEditFooter

```php
mixed FrontControllerCore::getLiveEditFooter()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 662](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L662)




### <a name="method-init"></a>init

```php
mixed OrderOpcControllerCore::init()
```

Initialize order opc controller



* Visibility: **public**
* Source: [controllers/front/OrderOpcController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/controllers/front/OrderOpcController.php#L37)




### <a name="method-initContent"></a>initContent

```php
mixed OrderOpcControllerCore::initContent()
```

Assign template vars related to page content



* Visibility: **public**
* Source: [controllers/front/OrderOpcController.php line 263](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/controllers/front/OrderOpcController.php#L263)




### <a name="method-initCursedPage"></a>initCursedPage

```php
mixed FrontControllerCore::initCursedPage()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 441](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L441)




### <a name="method-initFooter"></a>initFooter

```php
mixed FrontControllerCore::initFooter()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 654](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L654)




### <a name="method-initHeader"></a>initHeader

```php
mixed FrontControllerCore::initHeader()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 636](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L636)




### <a name="method-isInWhitelistForGeolocation"></a>isInWhitelistForGeolocation

```php
mixed FrontControllerCore::isInWhitelistForGeolocation()
```





* Visibility: **protected**
* This method is **static**.
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 777](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L777)




### <a name="method-isTokenValid"></a>isTokenValid

```php
boolean FrontControllerCore::isTokenValid()
```

Check if token is valid



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 795](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L795)




### <a name="method-pagination"></a>pagination

```php
mixed FrontControllerCore::pagination($nbProducts)
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 708](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L708)


#### Arguments
* $nbProducts **mixed**



### <a name="method-postProcess"></a>postProcess

```php
mixed FrontControllerCore::postProcess()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 363](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L363)




### <a name="method-preProcess"></a>preProcess

```php
mixed FrontControllerCore::preProcess()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 379](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L379)




### <a name="method-process"></a>process

```php
mixed FrontControllerCore::process()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 446](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L446)




### <a name="method-productSort"></a>productSort

```php
mixed FrontControllerCore::productSort()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 681](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L681)




### <a name="method-recoverCart"></a>recoverCart

```php
mixed FrontControllerCore::recoverCart()
```





* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 847](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L847)




### <a name="method-redirect"></a>redirect

```php
mixed FrontControllerCore::redirect()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/FrontController.php line 450](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/FrontController.php#L450)




### <a name="method-run"></a>run

```php
mixed ControllerCore::run()
```

Start controller process (this method shouldn't be overriden !)



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Controller.php#L143)




### <a name="method-setDefaultCarrierSelection"></a>setDefaultCarrierSelection

```php
\number ParentOrderControllerCore::setDefaultCarrierSelection(array $carriers)
```

Decides what the default carrier is and update the cart with it



* Visibility: **protected**
* This method is defined by [ParentOrderControllerCore](class.ParentOrderControllerCore.md).
* Source: [controllers/front/ParentOrderController.php line 479](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/controllers/front/ParentOrderController.php#L479)


#### Arguments
* $carriers **array**



### <a name="method-setMedia"></a>setMedia

```php
mixed OrderOpcControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/front/OrderOpcController.php line 247](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/controllers/front/OrderOpcController.php#L247)




### <a name="method-setNoCarrier"></a>setNoCarrier

```php
mixed ParentOrderControllerCore::setNoCarrier()
```

Set id_carrier to 0 (no shipping price)



* Visibility: **protected**
* This method is defined by [ParentOrderControllerCore](class.ParentOrderControllerCore.md).
* Source: [controllers/front/ParentOrderController.php line 462](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/controllers/front/ParentOrderController.php#L462)




### <a name="method-setTemplate"></a>setTemplate

```php
mixed ControllerCore::setTemplate($template)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/Controller.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Controller.php#L196)


#### Arguments
* $template **mixed**



### <a name="method-validateDeliveryOption"></a>validateDeliveryOption

```php
mixed ParentOrderControllerCore::validateDeliveryOption(array $delivery_option)
```

Validate get/post param delivery option



* Visibility: **protected**
* This method is defined by [ParentOrderControllerCore](class.ParentOrderControllerCore.md).
* Source: [controllers/front/ParentOrderController.php line 254](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/controllers/front/ParentOrderController.php#L254)


#### Arguments
* $delivery_option **array**


