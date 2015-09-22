Class AdminTaxRulesGroupControllerCore
=====================





* Class name: AdminTaxRulesGroupControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminTaxRulesGroupController.php#L27)


Contents
--------


### Properties

* [$errors_tax_rule](#property-$errors_tax_rule)
* [$selected_countries](#property-$selected_countries)
* [$selected_states](#property-$selected_states)
* [$tax_rule](#property-$tax_rule)

### Methods

* [__construct](#method-__construct)
* [deleteTaxRule](#method-deleteTaxRule)
* [displayAjaxUpdateTaxRule](#method-displayAjaxUpdateTaxRule)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [initRuleForm](#method-initRuleForm)
* [initRulesList](#method-initRulesList)
* [processBulkDeleteTaxRules](#method-processBulkDeleteTaxRules)
* [processCreateRule](#method-processCreateRule)
* [processDeleteTaxRule](#method-processDeleteTaxRule)
* [renderForm](#method-renderForm)
* [renderList](#method-renderList)
* [updateTaxRulesGroup](#method-updateTaxRulesGroup)
* [validateTaxRule](#method-validateTaxRule)




Properties
----------


### <a name="property-$errors_tax_rule"></a>$errors_tax_rule

```php
public mixed $errors_tax_rule
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminTaxRulesGroupController.php#L32).


### <a name="property-$selected_countries"></a>$selected_countries

```php
public mixed $selected_countries = array()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminTaxRulesGroupController.php#L30).


### <a name="property-$selected_states"></a>$selected_states

```php
public mixed $selected_states = array()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminTaxRulesGroupController.php#L31).


### <a name="property-$tax_rule"></a>$tax_rule

```php
public mixed $tax_rule
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminTaxRulesGroupController.php#L29).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminTaxRulesGroupControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminTaxRulesGroupController.php#L34)




### <a name="method-deleteTaxRule"></a>deleteTaxRule

```php
mixed AdminTaxRulesGroupControllerCore::deleteTaxRule(array $id_tax_rule_list)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 509](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminTaxRulesGroupController.php#L509)


#### Arguments
* $id_tax_rule_list **array**



### <a name="method-displayAjaxUpdateTaxRule"></a>displayAjaxUpdateTaxRule

```php
mixed AdminTaxRulesGroupControllerCore::displayAjaxUpdateTaxRule()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 542](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminTaxRulesGroupController.php#L542)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminTaxRulesGroupControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminTaxRulesGroupController.php#L75)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminTaxRulesGroupControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 376](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminTaxRulesGroupController.php#L376)




### <a name="method-initRuleForm"></a>initRuleForm

```php
mixed AdminTaxRulesGroupControllerCore::initRuleForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminTaxRulesGroupController.php#L234)




### <a name="method-initRulesList"></a>initRulesList

```php
mixed AdminTaxRulesGroupControllerCore::initRulesList($id_group)
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminTaxRulesGroupController.php#L95)


#### Arguments
* $id_group **mixed**



### <a name="method-processBulkDeleteTaxRules"></a>processBulkDeleteTaxRules

```php
mixed AdminTaxRulesGroupControllerCore::processBulkDeleteTaxRules()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 499](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminTaxRulesGroupController.php#L499)




### <a name="method-processCreateRule"></a>processCreateRule

```php
mixed AdminTaxRulesGroupControllerCore::processCreateRule()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 404](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminTaxRulesGroupController.php#L404)




### <a name="method-processDeleteTaxRule"></a>processDeleteTaxRule

```php
mixed AdminTaxRulesGroupControllerCore::processDeleteTaxRule()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 504](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminTaxRulesGroupController.php#L504)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminTaxRulesGroupControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminTaxRulesGroupController.php#L159)




### <a name="method-renderList"></a>renderList

```php
mixed AdminTaxRulesGroupControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminTaxRulesGroupController.php#L87)




### <a name="method-updateTaxRulesGroup"></a>updateTaxRulesGroup

```php
mixed AdminTaxRulesGroupControllerCore::updateTaxRulesGroup($object)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 555](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminTaxRulesGroupController.php#L555)


#### Arguments
* $object **mixed**



### <a name="method-validateTaxRule"></a>validateTaxRule

```php
mixed AdminTaxRulesGroupControllerCore::validateTaxRule(\TaxRule $tr)
```

check if the tax rule could be added in the database



* Visibility: **protected**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 536](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminTaxRulesGroupController.php#L536)


#### Arguments
* $tr **[TaxRule](class.TaxRuleCore.md)**


