Class TreeToolbarSearchCore
=====================





* Class name: TreeToolbarSearchCore
* Parent class: [TreeToolbarButtonCore](class.TreeToolbarButtonCore.md)
* Source: [classes/tree/TreeToolbarSearch.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L27)
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





* Source: [classes/tree/TreeToolbarSearch.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L29).


Properties
----------


### <a name="property-$_attributes"></a>$_attributes

```php
protected mixed $_attributes
```





* Visibility: **protected**
* Source: [classes/tree/TreeToolbarSearch.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L31).


### <a name="property-$_class"></a>$_class

```php
private mixed $_class
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbarSearch.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L32).


### <a name="property-$_context"></a>$_context

```php
private mixed $_context
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbarSearch.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L33).


### <a name="property-$_id"></a>$_id

```php
private mixed $_id
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbarSearch.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L34).


### <a name="property-$_label"></a>$_label

```php
private mixed $_label
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbarSearch.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L35).


### <a name="property-$_name"></a>$_name

```php
private mixed $_name
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbarSearch.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L36).


### <a name="property-$_template"></a>$_template

```php
protected mixed $_template
```





* Visibility: **protected**
* Source: [classes/tree/TreeToolbarSearch.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L37).


### <a name="property-$_template_directory"></a>$_template_directory

```php
protected mixed $_template_directory
```





* Visibility: **protected**
* Source: [classes/tree/TreeToolbarSearch.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L38).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed TreeToolbarSearchCore::__construct($label, $id, $name, $class)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L40)


#### Arguments
* $label **mixed**
* $id **mixed**
* $name **mixed**
* $class **mixed**



### <a name="method-__toString"></a>__toString

```php
mixed TreeToolbarSearchCore::__toString()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L48)




### <a name="method-_normalizeDirectory"></a>_normalizeDirectory

```php
mixed TreeToolbarSearchCore::_normalizeDirectory($directory)
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbarSearch.php line 215](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L215)


#### Arguments
* $directory **mixed**



### <a name="method-_renderData"></a>_renderData

```php
mixed TreeToolbarSearchCore::_renderData($data)
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbarSearch.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L66)


#### Arguments
* $data **mixed**



### <a name="method-getAttribute"></a>getAttribute

```php
mixed TreeToolbarSearchCore::getAttribute($name)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L62)


#### Arguments
* $name **mixed**



### <a name="method-getAttributes"></a>getAttributes

```php
mixed TreeToolbarSearchCore::getAttributes()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L76)




### <a name="method-getClass"></a>getClass

```php
mixed TreeToolbarSearchCore::getClass()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L89)




### <a name="method-getContext"></a>getContext

```php
mixed TreeToolbarSearchCore::getContext()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L100)




### <a name="method-getId"></a>getId

```php
mixed TreeToolbarSearchCore::getId()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L113)




### <a name="method-getLabel"></a>getLabel

```php
mixed TreeToolbarSearchCore::getLabel()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L123)




### <a name="method-getName"></a>getName

```php
mixed TreeToolbarSearchCore::getName()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L133)




### <a name="method-getTemplate"></a>getTemplate

```php
mixed TreeToolbarSearchCore::getTemplate()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L144)




### <a name="method-getTemplateDirectory"></a>getTemplateDirectory

```php
mixed TreeToolbarSearchCore::getTemplateDirectory()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L155)




### <a name="method-getTemplateFile"></a>getTemplateFile

```php
mixed TreeToolbarSearchCore::getTemplateFile($template)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L163)


#### Arguments
* $template **mixed**



### <a name="method-hasAttribute"></a>hasAttribute

```php
mixed TreeToolbarSearchCore::hasAttribute($name)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L201)


#### Arguments
* $name **mixed**



### <a name="method-render"></a>render

```php
mixed TreeToolbarSearchCore::render()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 207](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L207)




### <a name="method-setAttribute"></a>setAttribute

```php
mixed TreeToolbarSearchCore::setAttribute($name, $value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L53)


#### Arguments
* $name **mixed**
* $value **mixed**



### <a name="method-setAttributes"></a>setAttributes

```php
mixed TreeToolbarSearchCore::setAttributes($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L67)


#### Arguments
* $value **mixed**



### <a name="method-setClass"></a>setClass

```php
mixed TreeToolbarSearchCore::setClass($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L84)


#### Arguments
* $value **mixed**



### <a name="method-setContext"></a>setContext

```php
mixed TreeToolbarSearchCore::setContext($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L94)


#### Arguments
* $value **mixed**



### <a name="method-setId"></a>setId

```php
mixed TreeToolbarSearchCore::setId($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L108)


#### Arguments
* $value **mixed**



### <a name="method-setLabel"></a>setLabel

```php
mixed TreeToolbarSearchCore::setLabel($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L118)


#### Arguments
* $value **mixed**



### <a name="method-setName"></a>setName

```php
mixed TreeToolbarSearchCore::setName($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L128)


#### Arguments
* $value **mixed**



### <a name="method-setTemplate"></a>setTemplate

```php
mixed TreeToolbarSearchCore::setTemplate($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L138)


#### Arguments
* $value **mixed**



### <a name="method-setTemplateDirectory"></a>setTemplateDirectory

```php
mixed TreeToolbarSearchCore::setTemplateDirectory($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarSearch.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tree/TreeToolbarSearch.php#L149)


#### Arguments
* $value **mixed**


