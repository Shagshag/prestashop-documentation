Class AdminCartRulesControllerCore
=====================





* Class name: AdminCartRulesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminCartRulesController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/controllers/admin/AdminCartRulesController.php#L27)


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
* Source: [controllers/admin/AdminCartRulesController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/controllers/admin/AdminCartRulesController.php#L29)




### <a name="method-afterAdd"></a>afterAdd

```php
mixed AdminCartRulesControllerCore::afterAdd($currentObject)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCartRulesController.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/controllers/admin/AdminCartRulesController.php#L176)


#### Arguments
* $currentObject **mixed**



### <a name="method-afterUpdate"></a>afterUpdate

```php
mixed AdminCartRulesControllerCore::afterUpdate($current_object)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCartRulesController.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/controllers/admin/AdminCartRulesController.php#L153)


#### Arguments
* $current_object **mixed**



### <a name="method-ajaxProcess"></a>ajaxProcess

```php
mixed AdminCartRulesControllerCore::ajaxProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 404](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/controllers/admin/AdminCartRulesController.php#L404)




### <a name="method-ajaxProcessSearchProducts"></a>ajaxProcessSearchProducts

```php
mixed AdminCartRulesControllerCore::ajaxProcessSearchProducts()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 474](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/controllers/admin/AdminCartRulesController.php#L474)




### <a name="method-displayAjaxSearchCartRuleVouchers"></a>displayAjaxSearchCartRuleVouchers

```php
mixed AdminCartRulesControllerCore::displayAjaxSearchCartRuleVouchers()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 596](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/controllers/admin/AdminCartRulesController.php#L596)




### <a name="method-getProductRuleDisplay"></a>getProductRuleDisplay

```php
mixed AdminCartRulesControllerCore::getProductRuleDisplay($product_rule_group_id, $product_rule_id, $product_rule_type, $selected)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 311](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/controllers/admin/AdminCartRulesController.php#L311)


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
* Source: [controllers/admin/AdminCartRulesController.php line 303](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/controllers/admin/AdminCartRulesController.php#L303)


#### Arguments
* $product_rule_group_id **mixed**
* $product_rule_group_quantity **mixed**
* $product_rules **mixed**



### <a name="method-getProductRuleGroupsDisplay"></a>getProductRuleGroupsDisplay

```php
mixed AdminCartRulesControllerCore::getProductRuleGroupsDisplay($cart_rule)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 258](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/controllers/admin/AdminCartRulesController.php#L258)


#### Arguments
* $cart_rule **mixed**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminCartRulesControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/controllers/admin/AdminCartRulesController.php#L60)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminCartRulesControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/controllers/admin/AdminCartRulesController.php#L72)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminCartRulesControllerCore::processAdd()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/controllers/admin/AdminCartRulesController.php#L166)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminCartRulesControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 480](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/controllers/admin/AdminCartRulesController.php#L480)




### <a name="method-searchProducts"></a>searchProducts

```php
mixed AdminCartRulesControllerCore::searchProducts($search)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCartRulesController.php line 436](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/controllers/admin/AdminCartRulesController.php#L436)


#### Arguments
* $search **mixed**



### <a name="method-setMedia"></a>setMedia

```php
mixed AdminCartRulesControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/controllers/admin/AdminCartRulesController.php#L54)



