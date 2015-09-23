Class AdminTaxRulesGroupControllerCore
=====================





* Class name: AdminTaxRulesGroupControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminTaxRulesGroupController.php#L27)


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
* [validateTaxRule](#method-validateTaxRule)




Properties
----------


### <a name="property-$errors_tax_rule"></a>$errors_tax_rule

```php
public mixed $errors_tax_rule
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminTaxRulesGroupController.php#L32).


### <a name="property-$selected_countries"></a>$selected_countries

```php
public mixed $selected_countries = array()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminTaxRulesGroupController.php#L30).


### <a name="property-$selected_states"></a>$selected_states

```php
public mixed $selected_states = array()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminTaxRulesGroupController.php#L31).


### <a name="property-$tax_rule"></a>$tax_rule

```php
public mixed $tax_rule
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminTaxRulesGroupController.php#L29).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminTaxRulesGroupControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminTaxRulesGroupController.php#L34)




### <a name="method-deleteTaxRule"></a>deleteTaxRule

```php
mixed AdminTaxRulesGroupControllerCore::deleteTaxRule(array $id_tax_rule_list)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 497](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminTaxRulesGroupController.php#L497)


#### Arguments
* $id_tax_rule_list **array**



### <a name="method-displayAjaxUpdateTaxRule"></a>displayAjaxUpdateTaxRule

```php
mixed AdminTaxRulesGroupControllerCore::displayAjaxUpdateTaxRule()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 524](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminTaxRulesGroupController.php#L524)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminTaxRulesGroupControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminTaxRulesGroupController.php#L71)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminTaxRulesGroupControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 375](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminTaxRulesGroupController.php#L375)




### <a name="method-initRuleForm"></a>initRuleForm

```php
mixed AdminTaxRulesGroupControllerCore::initRuleForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminTaxRulesGroupController.php#L229)




### <a name="method-initRulesList"></a>initRulesList

```php
mixed AdminTaxRulesGroupControllerCore::initRulesList($id_group)
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminTaxRulesGroupController.php#L91)


#### Arguments
* $id_group **mixed**



### <a name="method-processBulkDeleteTaxRules"></a>processBulkDeleteTaxRules

```php
mixed AdminTaxRulesGroupControllerCore::processBulkDeleteTaxRules()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 487](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminTaxRulesGroupController.php#L487)




### <a name="method-processCreateRule"></a>processCreateRule

```php
mixed AdminTaxRulesGroupControllerCore::processCreateRule()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 403](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminTaxRulesGroupController.php#L403)




### <a name="method-processDeleteTaxRule"></a>processDeleteTaxRule

```php
mixed AdminTaxRulesGroupControllerCore::processDeleteTaxRule()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 492](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminTaxRulesGroupController.php#L492)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminTaxRulesGroupControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminTaxRulesGroupController.php#L153)




### <a name="method-renderList"></a>renderList

```php
mixed AdminTaxRulesGroupControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminTaxRulesGroupController.php#L83)




### <a name="method-validateTaxRule"></a>validateTaxRule

```php
mixed AdminTaxRulesGroupControllerCore::validateTaxRule(\TaxRule $tr)
```

check if the tax rule could be added in the database



* Visibility: **protected**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 518](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminTaxRulesGroupController.php#L518)


#### Arguments
* $tr **[TaxRule](class.TaxRuleCore.md)**


