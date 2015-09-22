Class AdminCartRulesControllerCore
=====================





* Class name: AdminCartRulesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminCartRulesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCartRulesController.php#L30)


Contents
--------


### Properties

* [$object](#property-$object)

### Methods

* [__construct](#method-__construct)
* [afterAdd](#method-afterAdd)
* [afterUpdate](#method-afterUpdate)
* [ajaxProcess](#method-ajaxProcess)
* [ajaxProcessLoadCartRules](#method-ajaxProcessLoadCartRules)
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




Properties
----------


### <a name="property-$object"></a>$object

```php
public \CartRule $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCartRulesController.php#L30).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminCartRulesControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCartRulesController.php#L32)




### <a name="method-afterAdd"></a>afterAdd

```php
void AdminCartRulesControllerCore::afterAdd(\ObjectModel $currentObject)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCartRulesController.php line 256](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCartRulesController.php#L256)


#### Arguments
* $currentObject **[ObjectModel](class.ObjectModelCore.md)**



### <a name="method-afterUpdate"></a>afterUpdate

```php
mixed AdminCartRulesControllerCore::afterUpdate($current_object)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCartRulesController.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCartRulesController.php#L221)


#### Arguments
* $current_object **mixed**



### <a name="method-ajaxProcess"></a>ajaxProcess

```php
mixed AdminCartRulesControllerCore::ajaxProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 497](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCartRulesController.php#L497)




### <a name="method-ajaxProcessLoadCartRules"></a>ajaxProcessLoadCartRules

```php
mixed AdminCartRulesControllerCore::ajaxProcessLoadCartRules()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCartRulesController.php#L57)




### <a name="method-ajaxProcessSearchProducts"></a>ajaxProcessSearchProducts

```php
mixed AdminCartRulesControllerCore::ajaxProcessSearchProducts()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 567](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCartRulesController.php#L567)




### <a name="method-displayAjaxSearchCartRuleVouchers"></a>displayAjaxSearchCartRuleVouchers

```php
mixed AdminCartRulesControllerCore::displayAjaxSearchCartRuleVouchers()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 693](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCartRulesController.php#L693)




### <a name="method-getProductRuleDisplay"></a>getProductRuleDisplay

```php
mixed AdminCartRulesControllerCore::getProductRuleDisplay($product_rule_group_id, $product_rule_id, $product_rule_type, $selected)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 404](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCartRulesController.php#L404)


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
* Source: [controllers/admin/AdminCartRulesController.php line 395](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCartRulesController.php#L395)


#### Arguments
* $product_rule_group_id **mixed**
* $product_rule_group_quantity **mixed**
* $product_rules **mixed**



### <a name="method-getProductRuleGroupsDisplay"></a>getProductRuleGroupsDisplay

```php
array AdminCartRulesControllerCore::getProductRuleGroupsDisplay(\CartRule $cart_rule)
```

Retrieve the cart rule product rule groups in the POST data
if available, and in the database if there is none



* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 350](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCartRulesController.php#L350)


#### Arguments
* $cart_rule **[CartRule](class.CartRuleCore.md)**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminCartRulesControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCartRulesController.php#L127)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminCartRulesControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCartRulesController.php#L139)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminCartRulesControllerCore::processAdd()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 238](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCartRulesController.php#L238)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminCartRulesControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 573](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCartRulesController.php#L573)




### <a name="method-searchProducts"></a>searchProducts

```php
mixed AdminCartRulesControllerCore::searchProducts($search)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCartRulesController.php line 529](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCartRulesController.php#L529)


#### Arguments
* $search **mixed**



### <a name="method-setMedia"></a>setMedia

```php
mixed AdminCartRulesControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCartRulesController.php#L121)



