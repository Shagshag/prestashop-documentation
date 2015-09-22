Class TreeToolbarButtonCore
=====================





* Class name: TreeToolbarButtonCore
* This is an **abstract** class
* Source: [classes/tree/TreeToolbarButton.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L27)


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





* Source: [classes/tree/TreeToolbarButton.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L29).


Properties
----------


### <a name="property-$_attributes"></a>$_attributes

```php
protected mixed $_attributes
```





* Visibility: **protected**
* Source: [classes/tree/TreeToolbarButton.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L31).


### <a name="property-$_class"></a>$_class

```php
private mixed $_class
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbarButton.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L32).


### <a name="property-$_context"></a>$_context

```php
private mixed $_context
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbarButton.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L33).


### <a name="property-$_id"></a>$_id

```php
private mixed $_id
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbarButton.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L34).


### <a name="property-$_label"></a>$_label

```php
private mixed $_label
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbarButton.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L35).


### <a name="property-$_name"></a>$_name

```php
private mixed $_name
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbarButton.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L36).


### <a name="property-$_template"></a>$_template

```php
protected mixed $_template
```





* Visibility: **protected**
* Source: [classes/tree/TreeToolbarButton.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L37).


### <a name="property-$_template_directory"></a>$_template_directory

```php
protected mixed $_template_directory
```





* Visibility: **protected**
* Source: [classes/tree/TreeToolbarButton.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L38).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed TreeToolbarButtonCore::__construct($label, $id, $name, $class)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarButton.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L40)


#### Arguments
* $label **mixed**
* $id **mixed**
* $name **mixed**
* $class **mixed**



### <a name="method-__toString"></a>__toString

```php
mixed TreeToolbarButtonCore::__toString()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarButton.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L48)




### <a name="method-_normalizeDirectory"></a>_normalizeDirectory

```php
mixed TreeToolbarButtonCore::_normalizeDirectory($directory)
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbarButton.php line 203](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L203)


#### Arguments
* $directory **mixed**



### <a name="method-getAttribute"></a>getAttribute

```php
mixed TreeToolbarButtonCore::getAttribute($name)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarButton.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L62)


#### Arguments
* $name **mixed**



### <a name="method-getAttributes"></a>getAttributes

```php
mixed TreeToolbarButtonCore::getAttributes()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarButton.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L76)




### <a name="method-getClass"></a>getClass

```php
mixed TreeToolbarButtonCore::getClass()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarButton.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L89)




### <a name="method-getContext"></a>getContext

```php
mixed TreeToolbarButtonCore::getContext()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarButton.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L100)




### <a name="method-getId"></a>getId

```php
mixed TreeToolbarButtonCore::getId()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarButton.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L113)




### <a name="method-getLabel"></a>getLabel

```php
mixed TreeToolbarButtonCore::getLabel()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarButton.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L123)




### <a name="method-getName"></a>getName

```php
mixed TreeToolbarButtonCore::getName()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarButton.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L133)




### <a name="method-getTemplate"></a>getTemplate

```php
mixed TreeToolbarButtonCore::getTemplate()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarButton.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L144)




### <a name="method-getTemplateDirectory"></a>getTemplateDirectory

```php
mixed TreeToolbarButtonCore::getTemplateDirectory()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarButton.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L155)




### <a name="method-getTemplateFile"></a>getTemplateFile

```php
mixed TreeToolbarButtonCore::getTemplateFile($template)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarButton.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L163)


#### Arguments
* $template **mixed**



### <a name="method-hasAttribute"></a>hasAttribute

```php
mixed TreeToolbarButtonCore::hasAttribute($name)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarButton.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L189)


#### Arguments
* $name **mixed**



### <a name="method-render"></a>render

```php
mixed TreeToolbarButtonCore::render()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarButton.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L195)




### <a name="method-setAttribute"></a>setAttribute

```php
mixed TreeToolbarButtonCore::setAttribute($name, $value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarButton.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L53)


#### Arguments
* $name **mixed**
* $value **mixed**



### <a name="method-setAttributes"></a>setAttributes

```php
mixed TreeToolbarButtonCore::setAttributes($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarButton.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L67)


#### Arguments
* $value **mixed**



### <a name="method-setClass"></a>setClass

```php
mixed TreeToolbarButtonCore::setClass($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarButton.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L84)


#### Arguments
* $value **mixed**



### <a name="method-setContext"></a>setContext

```php
mixed TreeToolbarButtonCore::setContext($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarButton.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L94)


#### Arguments
* $value **mixed**



### <a name="method-setId"></a>setId

```php
mixed TreeToolbarButtonCore::setId($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarButton.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L108)


#### Arguments
* $value **mixed**



### <a name="method-setLabel"></a>setLabel

```php
mixed TreeToolbarButtonCore::setLabel($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarButton.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L118)


#### Arguments
* $value **mixed**



### <a name="method-setName"></a>setName

```php
mixed TreeToolbarButtonCore::setName($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarButton.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L128)


#### Arguments
* $value **mixed**



### <a name="method-setTemplate"></a>setTemplate

```php
mixed TreeToolbarButtonCore::setTemplate($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarButton.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L138)


#### Arguments
* $value **mixed**



### <a name="method-setTemplateDirectory"></a>setTemplateDirectory

```php
mixed TreeToolbarButtonCore::setTemplateDirectory($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarButton.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/tree/TreeToolbarButton.php#L149)


#### Arguments
* $value **mixed**


