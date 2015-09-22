Class AdminTaxRulesGroupControllerCore
=====================





* Class name: AdminTaxRulesGroupControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTaxRulesGroupController.php#L30)


Contents
--------


### Properties

* [$errors_tax_rule](#property-$errors_tax_rule)
* [$object](#property-$object)
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
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTaxRulesGroupController.php#L35).


### <a name="property-$object"></a>$object

```php
public \TaxRulesGroup $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTaxRulesGroupController.php#L30).


### <a name="property-$selected_countries"></a>$selected_countries

```php
public mixed $selected_countries = array()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTaxRulesGroupController.php#L33).


### <a name="property-$selected_states"></a>$selected_states

```php
public mixed $selected_states = array()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTaxRulesGroupController.php#L34).


### <a name="property-$tax_rule"></a>$tax_rule

```php
public mixed $tax_rule
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTaxRulesGroupController.php#L32).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminTaxRulesGroupControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTaxRulesGroupController.php#L37)




### <a name="method-deleteTaxRule"></a>deleteTaxRule

```php
mixed AdminTaxRulesGroupControllerCore::deleteTaxRule(array $id_tax_rule_list)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 513](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTaxRulesGroupController.php#L513)


#### Arguments
* $id_tax_rule_list **array**



### <a name="method-displayAjaxUpdateTaxRule"></a>displayAjaxUpdateTaxRule

```php
mixed AdminTaxRulesGroupControllerCore::displayAjaxUpdateTaxRule()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 548](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTaxRulesGroupController.php#L548)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminTaxRulesGroupControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTaxRulesGroupController.php#L78)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminTaxRulesGroupControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 380](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTaxRulesGroupController.php#L380)




### <a name="method-initRuleForm"></a>initRuleForm

```php
mixed AdminTaxRulesGroupControllerCore::initRuleForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 238](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTaxRulesGroupController.php#L238)




### <a name="method-initRulesList"></a>initRulesList

```php
mixed AdminTaxRulesGroupControllerCore::initRulesList($id_group)
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTaxRulesGroupController.php#L98)


#### Arguments
* $id_group **mixed**



### <a name="method-processBulkDeleteTaxRules"></a>processBulkDeleteTaxRules

```php
mixed AdminTaxRulesGroupControllerCore::processBulkDeleteTaxRules()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 503](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTaxRulesGroupController.php#L503)




### <a name="method-processCreateRule"></a>processCreateRule

```php
mixed AdminTaxRulesGroupControllerCore::processCreateRule()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 408](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTaxRulesGroupController.php#L408)




### <a name="method-processDeleteTaxRule"></a>processDeleteTaxRule

```php
mixed AdminTaxRulesGroupControllerCore::processDeleteTaxRule()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 508](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTaxRulesGroupController.php#L508)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminTaxRulesGroupControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTaxRulesGroupController.php#L163)




### <a name="method-renderList"></a>renderList

```php
mixed AdminTaxRulesGroupControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTaxRulesGroupController.php#L90)




### <a name="method-updateTaxRulesGroup"></a>updateTaxRulesGroup

```php
\TaxRulesGroup AdminTaxRulesGroupControllerCore::updateTaxRulesGroup(\TaxRulesGroup $object)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 566](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTaxRulesGroupController.php#L566)


#### Arguments
* $object **[TaxRulesGroup](class.TaxRulesGroupCore.md)**



### <a name="method-validateTaxRule"></a>validateTaxRule

```php
array AdminTaxRulesGroupControllerCore::validateTaxRule(\TaxRule $tr)
```

Check if the tax rule could be added in the database



* Visibility: **protected**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 542](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminTaxRulesGroupController.php#L542)


#### Arguments
* $tr **[TaxRule](class.TaxRuleCore.md)**


