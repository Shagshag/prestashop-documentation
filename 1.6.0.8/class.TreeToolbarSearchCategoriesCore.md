Class TreeToolbarSearchCategoriesCore
=====================





* Class name: TreeToolbarSearchCategoriesCore
* Parent class: [TreeToolbarButtonCore](class.TreeToolbarButtonCore.md)
* Source: [classes/tree/TreeToolbarSearchCategories.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L27)
* This class implements: [ITreeToolbarButtonCore](interface.ITreeToolbarButtonCore.md)

Contents
--------

### Constants

* [DEFAULT_TEMPLATE_DIRECTORY](#constant-DEFAULT_TEMPLATE_DIRECTORY)

### Properties

* [$_attributes](#property-$_attributes)
* [$_class](#property-$_class)
* [$_context](#property-$_context)
* [$_id](#property-$_id)
* [$_label](#property-$_label)
* [$_name](#property-$_name)
* [$_template](#property-$_template)
* [$_template_directory](#property-$_template_directory)

### Methods

* [__construct](#method-__construct)
* [__toString](#method-__toString)
* [_normalizeDirectory](#method-_normalizeDirectory)
* [_renderData](#method-_renderData)
* [getAttribute](#method-getAttribute)
* [getAttributes](#method-getAttributes)
* [getClass](#method-getClass)
* [getContext](#method-getContext)
* [getId](#method-getId)
* [getLabel](#method-getLabel)
* [getName](#method-getName)
* [getTemplate](#method-getTemplate)
* [getTemplateDirectory](#method-getTemplateDirectory)
* [getTemplateFile](#method-getTemplateFile)
* [hasAttribute](#method-hasAttribute)
* [render](#method-render)
* [setAttribute](#method-setAttribute)
* [setAttributes](#method-setAttributes)
* [setClass](#method-setClass)
* [setContext](#method-setContext)
* [setId](#method-setId)
* [setLabel](#method-setLabel)
* [setName](#method-setName)
* [setTemplate](#method-setTemplate)
* [setTemplateDirectory](#method-setTemplateDirectory)


Constants
----------


### <a name="constant-DEFAULT_TEMPLATE_DIRECTORY"></a>DEFAULT_TEMPLATE_DIRECTORY

```php
const DEFAULT_TEMPLATE_DIRECTORY = 'helpers/tree'
```





* Source: [classes/tree/TreeToolbarSearchCategories.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L29).


Properties
----------


### <a name="property-$_attributes"></a>$_attributes

```php
protected mixed $_attributes
```





* Visibility: **protected**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L31).


### <a name="property-$_class"></a>$_class

```php
private mixed $_class
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L32).


### <a name="property-$_context"></a>$_context

```php
private mixed $_context
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L33).


### <a name="property-$_id"></a>$_id

```php
private mixed $_id
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L34).


### <a name="property-$_label"></a>$_label

```php
private mixed $_label
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L35).


### <a name="property-$_name"></a>$_name

```php
private mixed $_name
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L36).


### <a name="property-$_template"></a>$_template

```php
protected mixed $_template
```





* Visibility: **protected**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L37).


### <a name="property-$_template_directory"></a>$_template_directory

```php
protected mixed $_template_directory
```





* Visibility: **protected**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L38).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed TreeToolbarSearchCategoriesCore::__construct($label, $id, $name, $class)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L40)


#### Arguments
* $label **mixed**
* $id **mixed**
* $name **mixed**
* $class **mixed**



### <a name="method-__toString"></a>__toString

```php
mixed TreeToolbarSearchCategoriesCore::__toString()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L48)




### <a name="method-_normalizeDirectory"></a>_normalizeDirectory

```php
mixed TreeToolbarSearchCategoriesCore::_normalizeDirectory($directory)
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 203](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L203)


#### Arguments
* $directory **mixed**



### <a name="method-_renderData"></a>_renderData

```php
mixed TreeToolbarSearchCategoriesCore::_renderData($data)
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L63)


#### Arguments
* $data **mixed**



### <a name="method-getAttribute"></a>getAttribute

```php
mixed TreeToolbarSearchCategoriesCore::getAttribute($name)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L62)


#### Arguments
* $name **mixed**



### <a name="method-getAttributes"></a>getAttributes

```php
mixed TreeToolbarSearchCategoriesCore::getAttributes()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L76)




### <a name="method-getClass"></a>getClass

```php
mixed TreeToolbarSearchCategoriesCore::getClass()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L89)




### <a name="method-getContext"></a>getContext

```php
mixed TreeToolbarSearchCategoriesCore::getContext()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L100)




### <a name="method-getId"></a>getId

```php
mixed TreeToolbarSearchCategoriesCore::getId()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L113)




### <a name="method-getLabel"></a>getLabel

```php
mixed TreeToolbarSearchCategoriesCore::getLabel()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L123)




### <a name="method-getName"></a>getName

```php
mixed TreeToolbarSearchCategoriesCore::getName()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L133)




### <a name="method-getTemplate"></a>getTemplate

```php
mixed TreeToolbarSearchCategoriesCore::getTemplate()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L144)




### <a name="method-getTemplateDirectory"></a>getTemplateDirectory

```php
mixed TreeToolbarSearchCategoriesCore::getTemplateDirectory()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L155)




### <a name="method-getTemplateFile"></a>getTemplateFile

```php
mixed TreeToolbarSearchCategoriesCore::getTemplateFile($template)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L163)


#### Arguments
* $template **mixed**



### <a name="method-hasAttribute"></a>hasAttribute

```php
mixed TreeToolbarSearchCategoriesCore::hasAttribute($name)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L189)


#### Arguments
* $name **mixed**



### <a name="method-render"></a>render

```php
mixed TreeToolbarSearchCategoriesCore::render()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L195)




### <a name="method-setAttribute"></a>setAttribute

```php
mixed TreeToolbarSearchCategoriesCore::setAttribute($name, $value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L53)


#### Arguments
* $name **mixed**
* $value **mixed**



### <a name="method-setAttributes"></a>setAttributes

```php
mixed TreeToolbarSearchCategoriesCore::setAttributes($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L67)


#### Arguments
* $value **mixed**



### <a name="method-setClass"></a>setClass

```php
mixed TreeToolbarSearchCategoriesCore::setClass($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L84)


#### Arguments
* $value **mixed**



### <a name="method-setContext"></a>setContext

```php
mixed TreeToolbarSearchCategoriesCore::setContext($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L94)


#### Arguments
* $value **mixed**



### <a name="method-setId"></a>setId

```php
mixed TreeToolbarSearchCategoriesCore::setId($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L108)


#### Arguments
* $value **mixed**



### <a name="method-setLabel"></a>setLabel

```php
mixed TreeToolbarSearchCategoriesCore::setLabel($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L118)


#### Arguments
* $value **mixed**



### <a name="method-setName"></a>setName

```php
mixed TreeToolbarSearchCategoriesCore::setName($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L128)


#### Arguments
* $value **mixed**



### <a name="method-setTemplate"></a>setTemplate

```php
mixed TreeToolbarSearchCategoriesCore::setTemplate($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L138)


#### Arguments
* $value **mixed**



### <a name="method-setTemplateDirectory"></a>setTemplateDirectory

```php
mixed TreeToolbarSearchCategoriesCore::setTemplateDirectory($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearchCategories.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/tree/TreeToolbarSearchCategories.php#L149)


#### Arguments
* $value **mixed**


