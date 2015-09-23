Class TreeToolbarCore
=====================





* Class name: TreeToolbarCore
* Source: [classes/tree/TreeToolbar.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/tree/TreeToolbar.php#L27)
* This class implements: [ITreeToolbarCore](interface.ITreeToolbarCore.md)

Contents
--------

### Constants

* [DEFAULT_TEMPLATE](#constant-DEFAULT_TEMPLATE)
* [DEFAULT_TEMPLATE_DIRECTORY](#constant-DEFAULT_TEMPLATE_DIRECTORY)

### Properties

* [$_actions](#property-$_actions)
* [$_context](#property-$_context)
* [$_data](#property-$_data)
* [$_template](#property-$_template)
* [$_template_directory](#property-$_template_directory)

### Methods

* [__toString](#method-__toString)
* [_normalizeDirectory](#method-_normalizeDirectory)
* [addAction](#method-addAction)
* [getActions](#method-getActions)
* [getContext](#method-getContext)
* [getData](#method-getData)
* [getTemplate](#method-getTemplate)
* [getTemplateDirectory](#method-getTemplateDirectory)
* [getTemplateFile](#method-getTemplateFile)
* [render](#method-render)
* [setActions](#method-setActions)
* [setContext](#method-setContext)
* [setData](#method-setData)
* [setTemplate](#method-setTemplate)
* [setTemplateDirectory](#method-setTemplateDirectory)


Constants
----------


### <a name="constant-DEFAULT_TEMPLATE"></a>DEFAULT_TEMPLATE

```php
const DEFAULT_TEMPLATE = 'tree_toolbar.tpl'
```





* Source: [classes/tree/TreeToolbar.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/tree/TreeToolbar.php#L30).


### <a name="constant-DEFAULT_TEMPLATE_DIRECTORY"></a>DEFAULT_TEMPLATE_DIRECTORY

```php
const DEFAULT_TEMPLATE_DIRECTORY = 'helpers/tree'
```





* Source: [classes/tree/TreeToolbar.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/tree/TreeToolbar.php#L29).


Properties
----------


### <a name="property-$_actions"></a>$_actions

```php
private mixed $_actions
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbar.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/tree/TreeToolbar.php#L32).


### <a name="property-$_context"></a>$_context

```php
private mixed $_context
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbar.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/tree/TreeToolbar.php#L33).


### <a name="property-$_data"></a>$_data

```php
private mixed $_data
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbar.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/tree/TreeToolbar.php#L34).


### <a name="property-$_template"></a>$_template

```php
private mixed $_template
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbar.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/tree/TreeToolbar.php#L35).


### <a name="property-$_template_directory"></a>$_template_directory

```php
private mixed $_template_directory
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbar.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/tree/TreeToolbar.php#L36).


Methods
-------


### <a name="method-__toString"></a>__toString

```php
mixed TreeToolbarCore::__toString()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbar.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/tree/TreeToolbar.php#L38)




### <a name="method-_normalizeDirectory"></a>_normalizeDirectory

```php
mixed TreeToolbarCore::_normalizeDirectory($directory)
```





* Visibility: **private**
* Source: [classes/tree/TreeToolbar.php line 187](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/tree/TreeToolbar.php#L187)


#### Arguments
* $directory **mixed**



### <a name="method-addAction"></a>addAction

```php
mixed TreeToolbarCore::addAction($action)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbar.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/tree/TreeToolbar.php#L156)


#### Arguments
* $action **mixed**



### <a name="method-getActions"></a>getActions

```php
mixed TreeToolbarCore::getActions()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbar.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/tree/TreeToolbar.php#L52)




### <a name="method-getContext"></a>getContext

```php
mixed TreeToolbarCore::getContext()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbar.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/tree/TreeToolbar.php#L66)




### <a name="method-getData"></a>getData

```php
mixed TreeToolbarCore::getData()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbar.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/tree/TreeToolbar.php#L83)




### <a name="method-getTemplate"></a>getTemplate

```php
mixed TreeToolbarCore::getTemplate()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbar.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/tree/TreeToolbar.php#L94)




### <a name="method-getTemplateDirectory"></a>getTemplateDirectory

```php
mixed TreeToolbarCore::getTemplateDirectory()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbar.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/tree/TreeToolbar.php#L108)




### <a name="method-getTemplateFile"></a>getTemplateFile

```php
mixed TreeToolbarCore::getTemplateFile($template)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbar.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/tree/TreeToolbar.php#L118)


#### Arguments
* $template **mixed**



### <a name="method-render"></a>render

```php
mixed TreeToolbarCore::render()
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbar.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/tree/TreeToolbar.php#L176)




### <a name="method-setActions"></a>setActions

```php
mixed TreeToolbarCore::setActions($actions)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbar.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/tree/TreeToolbar.php#L43)


#### Arguments
* $actions **mixed**



### <a name="method-setContext"></a>setContext

```php
mixed TreeToolbarCore::setContext($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbar.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/tree/TreeToolbar.php#L60)


#### Arguments
* $value **mixed**



### <a name="method-setData"></a>setData

```php
mixed TreeToolbarCore::setData($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbar.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/tree/TreeToolbar.php#L74)


#### Arguments
* $value **mixed**



### <a name="method-setTemplate"></a>setTemplate

```php
mixed TreeToolbarCore::setTemplate($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbar.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/tree/TreeToolbar.php#L88)


#### Arguments
* $value **mixed**



### <a name="method-setTemplateDirectory"></a>setTemplateDirectory

```php
mixed TreeToolbarCore::setTemplateDirectory($value)
```





* Visibility: **public**
* Source: [classes/tree/TreeToolbar.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/tree/TreeToolbar.php#L102)


#### Arguments
* $value **mixed**


