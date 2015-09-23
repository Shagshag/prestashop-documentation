Class TreeToolbarLinkCore
=====================





* Class name: TreeToolbarLinkCore
* Parent class: [TreeToolbarButtonCore](class.TreeToolbarButtonCore.md)
* Source: [classes/tree/TreeToolbarLink.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L27)
* This class implements: [ITreeToolbarButtonCore](interface.ITreeToolbarButtonCore.md)

Contents
--------

### Constants

* [DEFAULT_TEMPLATE_DIRECTORY](#constant-DEFAULT_TEMPLATE_DIRECTORY)

### Properties

* [$_action](#property-$_action)
* [$_attributes](#property-$_attributes)
* [$_class](#property-$_class)
* [$_context](#property-$_context)
* [$_icon_class](#property-$_icon_class)
* [$_id](#property-$_id)
* [$_label](#property-$_label)
* [$_link](#property-$_link)
* [$_name](#property-$_name)
* [$_template](#property-$_template)
* [$_template_directory](#property-$_template_directory)

### Methods

* [__construct](#method-__construct)
* [__toString](#method-__toString)
* [_normalizeDirectory](#method-_normalizeDirectory)
* [getAction](#method-getAction)
* [getAttribute](#method-getAttribute)
* [getAttributes](#method-getAttributes)
* [getClass](#method-getClass)
* [getContext](#method-getContext)
* [getIconClass](#method-getIconClass)
* [getId](#method-getId)
* [getLabel](#method-getLabel)
* [getLink](#method-getLink)
* [getName](#method-getName)
* [getTemplate](#method-getTemplate)
* [getTemplateDirectory](#method-getTemplateDirectory)
* [getTemplateFile](#method-getTemplateFile)
* [hasAttribute](#method-hasAttribute)
* [render](#method-render)
* [setAction](#method-setAction)
* [setAttribute](#method-setAttribute)
* [setAttributes](#method-setAttributes)
* [setClass](#method-setClass)
* [setContext](#method-setContext)
* [setIconClass](#method-setIconClass)
* [setId](#method-setId)
* [setLabel](#method-setLabel)
* [setLink](#method-setLink)
* [setName](#method-setName)
* [setTemplate](#method-setTemplate)
* [setTemplateDirectory](#method-setTemplateDirectory)


Constants
----------


### <a name="constant-DEFAULT_TEMPLATE_DIRECTORY"></a>DEFAULT_TEMPLATE_DIRECTORY

```php
const DEFAULT_TEMPLATE_DIRECTORY = 'helpers/tree'
```





* Source: [classes/tree/TreeToolbarLink.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L29).


Properties
----------


### <a name="property-$_action"></a>$_action

```php
private mixed $_action
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbarLink.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L30).


### <a name="property-$_attributes"></a>$_attributes

```php
protected mixed $_attributes
```





* Visibility: **protected**
* Source: [classes/tree/TreeToolbarLink.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L31).


### <a name="property-$_class"></a>$_class

```php
private mixed $_class
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbarLink.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L32).


### <a name="property-$_context"></a>$_context

```php
private mixed $_context
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbarLink.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L33).


### <a name="property-$_icon_class"></a>$_icon_class

```php
private mixed $_icon_class
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbarLink.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L31).


### <a name="property-$_id"></a>$_id

```php
private mixed $_id
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbarLink.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L34).


### <a name="property-$_label"></a>$_label

```php
private mixed $_label
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbarLink.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L35).


### <a name="property-$_link"></a>$_link

```php
private mixed $_link
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbarLink.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L32).


### <a name="property-$_name"></a>$_name

```php
private mixed $_name
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbarLink.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L36).


### <a name="property-$_template"></a>$_template

```php
protected mixed $_template
```





* Visibility: **protected**
* Source: [classes/tree/TreeToolbarLink.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L37).


### <a name="property-$_template_directory"></a>$_template_directory

```php
protected mixed $_template_directory
```





* Visibility: **protected**
* Source: [classes/tree/TreeToolbarLink.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L38).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed TreeToolbarLinkCore::__construct($label, $id, $name, $class)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L40)


#### Arguments
* $label **mixed**
* $id **mixed**
* $name **mixed**
* $class **mixed**



### <a name="method-__toString"></a>__toString

```php
mixed TreeToolbarLinkCore::__toString()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L48)




### <a name="method-_normalizeDirectory"></a>_normalizeDirectory

```php
mixed TreeToolbarLinkCore::_normalizeDirectory($directory)
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbarLink.php line 203](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L203)


#### Arguments
* $directory **mixed**



### <a name="method-getAction"></a>getAction

```php
mixed TreeToolbarLinkCore::getAction()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L49)




### <a name="method-getAttribute"></a>getAttribute

```php
mixed TreeToolbarLinkCore::getAttribute($name)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L62)


#### Arguments
* $name **mixed**



### <a name="method-getAttributes"></a>getAttributes

```php
mixed TreeToolbarLinkCore::getAttributes()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L76)




### <a name="method-getClass"></a>getClass

```php
mixed TreeToolbarLinkCore::getClass()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L89)




### <a name="method-getContext"></a>getContext

```php
mixed TreeToolbarLinkCore::getContext()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L100)




### <a name="method-getIconClass"></a>getIconClass

```php
mixed TreeToolbarLinkCore::getIconClass()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L59)




### <a name="method-getId"></a>getId

```php
mixed TreeToolbarLinkCore::getId()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L113)




### <a name="method-getLabel"></a>getLabel

```php
mixed TreeToolbarLinkCore::getLabel()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L123)




### <a name="method-getLink"></a>getLink

```php
mixed TreeToolbarLinkCore::getLink()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L69)




### <a name="method-getName"></a>getName

```php
mixed TreeToolbarLinkCore::getName()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L133)




### <a name="method-getTemplate"></a>getTemplate

```php
mixed TreeToolbarLinkCore::getTemplate()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L144)




### <a name="method-getTemplateDirectory"></a>getTemplateDirectory

```php
mixed TreeToolbarLinkCore::getTemplateDirectory()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L155)




### <a name="method-getTemplateFile"></a>getTemplateFile

```php
mixed TreeToolbarLinkCore::getTemplateFile($template)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L163)


#### Arguments
* $template **mixed**



### <a name="method-hasAttribute"></a>hasAttribute

```php
mixed TreeToolbarLinkCore::hasAttribute($name)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L189)


#### Arguments
* $name **mixed**



### <a name="method-render"></a>render

```php
mixed TreeToolbarLinkCore::render()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L195)




### <a name="method-setAction"></a>setAction

```php
mixed TreeToolbarLinkCore::setAction($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L44)


#### Arguments
* $value **mixed**



### <a name="method-setAttribute"></a>setAttribute

```php
mixed TreeToolbarLinkCore::setAttribute($name, $value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L53)


#### Arguments
* $name **mixed**
* $value **mixed**



### <a name="method-setAttributes"></a>setAttributes

```php
mixed TreeToolbarLinkCore::setAttributes($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L67)


#### Arguments
* $value **mixed**



### <a name="method-setClass"></a>setClass

```php
mixed TreeToolbarLinkCore::setClass($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L84)


#### Arguments
* $value **mixed**



### <a name="method-setContext"></a>setContext

```php
mixed TreeToolbarLinkCore::setContext($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L94)


#### Arguments
* $value **mixed**



### <a name="method-setIconClass"></a>setIconClass

```php
mixed TreeToolbarLinkCore::setIconClass($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L54)


#### Arguments
* $value **mixed**



### <a name="method-setId"></a>setId

```php
mixed TreeToolbarLinkCore::setId($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L108)


#### Arguments
* $value **mixed**



### <a name="method-setLabel"></a>setLabel

```php
mixed TreeToolbarLinkCore::setLabel($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L118)


#### Arguments
* $value **mixed**



### <a name="method-setLink"></a>setLink

```php
mixed TreeToolbarLinkCore::setLink($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L64)


#### Arguments
* $value **mixed**



### <a name="method-setName"></a>setName

```php
mixed TreeToolbarLinkCore::setName($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L128)


#### Arguments
* $value **mixed**



### <a name="method-setTemplate"></a>setTemplate

```php
mixed TreeToolbarLinkCore::setTemplate($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L138)


#### Arguments
* $value **mixed**



### <a name="method-setTemplateDirectory"></a>setTemplateDirectory

```php
mixed TreeToolbarLinkCore::setTemplateDirectory($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbarLink.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/tree/TreeToolbarLink.php#L149)


#### Arguments
* $value **mixed**


