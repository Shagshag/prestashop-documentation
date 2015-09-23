Class AdminCartRulesControllerCore
=====================





* Class name: AdminCartRulesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminCartRulesController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCartRulesController.php#L27)


Contents
--------



### Methods

* [__construct](#method-__construct)
* [afterAdd](#method-afterAdd)
* [afterUpdate](#method-afterUpdate)
* [ajaxProcess](#method-ajaxProcess)
* [ajaxProcessSearchProducts](#method-ajaxProcessSearchProducts)
* [displayAjaxSearchCartRuleVouchers](#method-displayAjaxSearchCartRuleVouchers)
* [getProductRuleDisplay](#method-getProductRuleDisplay)
* [getProductRuleGroupDisplay](#method-getProductRuleGroupDisplay)
* [getProductRuleGroupsDisplay](#method-getProductRuleGroupsDisplay)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [postProcess](#method-postProcess)
* [processAdd](#method-processAdd)
* [renderForm](#method-renderForm)
* [searchProducts](#method-searchProducts)
* [setMedia](#method-setMedia)






Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminCartRulesControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCartRulesController.php#L29)




### <a name="method-afterAdd"></a>afterAdd

```php
mixed AdminCartRulesControllerCore::afterAdd($currentObject)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCartRulesController.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCartRulesController.php#L174)


#### Arguments
* $currentObject **mixed**



### <a name="method-afterUpdate"></a>afterUpdate

```php
mixed AdminCartRulesControllerCore::afterUpdate($current_object)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCartRulesController.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCartRulesController.php#L151)


#### Arguments
* $current_object **mixed**



### <a name="method-ajaxProcess"></a>ajaxProcess

```php
mixed AdminCartRulesControllerCore::ajaxProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 402](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCartRulesController.php#L402)




### <a name="method-ajaxProcessSearchProducts"></a>ajaxProcessSearchProducts

```php
mixed AdminCartRulesControllerCore::ajaxProcessSearchProducts()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 472](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCartRulesController.php#L472)




### <a name="method-displayAjaxSearchCartRuleVouchers"></a>displayAjaxSearchCartRuleVouchers

```php
mixed AdminCartRulesControllerCore::displayAjaxSearchCartRuleVouchers()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 593](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCartRulesController.php#L593)




### <a name="method-getProductRuleDisplay"></a>getProductRuleDisplay

```php
mixed AdminCartRulesControllerCore::getProductRuleDisplay($product_rule_group_id, $product_rule_id, $product_rule_type, $selected)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 309](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCartRulesController.php#L309)


#### Arguments
* $product_rule_group_id **mixed**
* $product_rule_id **mixed**
* $product_rule_type **mixed**
* $selected **mixed**



### <a name="method-getProductRuleGroupDisplay"></a>getProductRuleGroupDisplay

```php
mixed AdminCartRulesControllerCore::getProductRuleGroupDisplay($product_rule_group_id, $product_rule_group_quantity, $product_rules)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 301](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCartRulesController.php#L301)


#### Arguments
* $product_rule_group_id **mixed**
* $product_rule_group_quantity **mixed**
* $product_rules **mixed**



### <a name="method-getProductRuleGroupsDisplay"></a>getProductRuleGroupsDisplay

```php
mixed AdminCartRulesControllerCore::getProductRuleGroupsDisplay($cart_rule)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 256](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCartRulesController.php#L256)


#### Arguments
* $cart_rule **mixed**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminCartRulesControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCartRulesController.php#L60)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminCartRulesControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCartRulesController.php#L72)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminCartRulesControllerCore::processAdd()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCartRulesController.php#L164)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminCartRulesControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 478](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCartRulesController.php#L478)




### <a name="method-searchProducts"></a>searchProducts

```php
mixed AdminCartRulesControllerCore::searchProducts($search)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCartRulesController.php line 434](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCartRulesController.php#L434)


#### Arguments
* $search **mixed**



### <a name="method-setMedia"></a>setMedia

```php
mixed AdminCartRulesControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCartRulesController.php#L53)



