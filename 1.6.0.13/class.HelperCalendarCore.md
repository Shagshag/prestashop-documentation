Class HelperCalendarCore
=====================





* Class name: HelperCalendarCore
* Parent class: [Helper](class.HelperCore.md)
* Source: [classes/helper/HelperCalendar.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L27)


Contents
--------

### Constants

* [DEFAULT_COMPARE_OPTION](#constant-DEFAULT_COMPARE_OPTION)
* [DEFAULT_DATE_FORMAT](#constant-DEFAULT_DATE_FORMAT)

### Properties

* [$_actions](#property-$_actions)
* [$_compare_actions](#property-$_compare_actions)
* [$_compare_date_from](#property-$_compare_date_from)
* [$_compare_date_option](#property-$_compare_date_option)
* [$_compare_date_to](#property-$_compare_date_to)
* [$_date_format](#property-$_date_format)
* [$_date_from](#property-$_date_from)
* [$_date_to](#property-$_date_to)
* [$_rtl](#property-$_rtl)

### Methods

* [__construct](#method-__construct)
* [addAction](#method-addAction)
* [addCompareAction](#method-addCompareAction)
* [generate](#method-generate)
* [getActions](#method-getActions)
* [getCompareActions](#method-getCompareActions)
* [getCompareDateFrom](#method-getCompareDateFrom)
* [getCompareDateTo](#method-getCompareDateTo)
* [getCompareOption](#method-getCompareOption)
* [getDateFormat](#method-getDateFormat)
* [getDateFrom](#method-getDateFrom)
* [getDateTo](#method-getDateTo)
* [isRTL](#method-isRTL)
* [setActions](#method-setActions)
* [setCompareActions](#method-setCompareActions)
* [setCompareDateFrom](#method-setCompareDateFrom)
* [setCompareDateTo](#method-setCompareDateTo)
* [setCompareOption](#method-setCompareOption)
* [setDateFormat](#method-setDateFormat)
* [setDateFrom](#method-setDateFrom)
* [setDateTo](#method-setDateTo)
* [setRTL](#method-setRTL)


Constants
----------


### <a name="constant-DEFAULT_COMPARE_OPTION"></a>DEFAULT_COMPARE_OPTION

```php
const DEFAULT_COMPARE_OPTION = 1
```





* Source: [classes/helper/HelperCalendar.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L30).


### <a name="constant-DEFAULT_DATE_FORMAT"></a>DEFAULT_DATE_FORMAT

```php
const DEFAULT_DATE_FORMAT = 'Y-mm-dd'
```





* Source: [classes/helper/HelperCalendar.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L29).


Properties
----------


### <a name="property-$_actions"></a>$_actions

```php
private mixed $_actions
```





* Visibility: **private**
* Source: [classes/helper/HelperCalendar.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L32).


### <a name="property-$_compare_actions"></a>$_compare_actions

```php
private mixed $_compare_actions
```





* Visibility: **private**
* Source: [classes/helper/HelperCalendar.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L33).


### <a name="property-$_compare_date_from"></a>$_compare_date_from

```php
private mixed $_compare_date_from
```





* Visibility: **private**
* Source: [classes/helper/HelperCalendar.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L34).


### <a name="property-$_compare_date_option"></a>$_compare_date_option

```php
private mixed $_compare_date_option
```





* Visibility: **private**
* Source: [classes/helper/HelperCalendar.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L36).


### <a name="property-$_compare_date_to"></a>$_compare_date_to

```php
private mixed $_compare_date_to
```





* Visibility: **private**
* Source: [classes/helper/HelperCalendar.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L35).


### <a name="property-$_date_format"></a>$_date_format

```php
private mixed $_date_format
```





* Visibility: **private**
* Source: [classes/helper/HelperCalendar.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L37).


### <a name="property-$_date_from"></a>$_date_from

```php
private mixed $_date_from
```





* Visibility: **private**
* Source: [classes/helper/HelperCalendar.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L38).


### <a name="property-$_date_to"></a>$_date_to

```php
private mixed $_date_to
```





* Visibility: **private**
* Source: [classes/helper/HelperCalendar.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L39).


### <a name="property-$_rtl"></a>$_rtl

```php
private mixed $_rtl
```





* Visibility: **private**
* Source: [classes/helper/HelperCalendar.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L40).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed HelperCalendarCore::__construct()
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L42)




### <a name="method-addAction"></a>addAction

```php
mixed HelperCalendarCore::addAction($action)
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L182)


#### Arguments
* $action **mixed**



### <a name="method-addCompareAction"></a>addCompareAction

```php
mixed HelperCalendarCore::addCompareAction($action)
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L192)


#### Arguments
* $action **mixed**



### <a name="method-generate"></a>generate

```php
mixed HelperCalendarCore::generate()
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L202)




### <a name="method-getActions"></a>getActions

```php
mixed HelperCalendarCore::getActions()
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L58)




### <a name="method-getCompareActions"></a>getCompareActions

```php
mixed HelperCalendarCore::getCompareActions()
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L75)




### <a name="method-getCompareDateFrom"></a>getCompareDateFrom

```php
mixed HelperCalendarCore::getCompareDateFrom()
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L89)




### <a name="method-getCompareDateTo"></a>getCompareDateTo

```php
mixed HelperCalendarCore::getCompareDateTo()
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L100)




### <a name="method-getCompareOption"></a>getCompareOption

```php
mixed HelperCalendarCore::getCompareOption()
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L111)




### <a name="method-getDateFormat"></a>getDateFormat

```php
mixed HelperCalendarCore::getDateFormat()
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L128)




### <a name="method-getDateFrom"></a>getDateFrom

```php
mixed HelperCalendarCore::getDateFrom()
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L148)




### <a name="method-getDateTo"></a>getDateTo

```php
mixed HelperCalendarCore::getDateTo()
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L168)




### <a name="method-isRTL"></a>isRTL

```php
mixed HelperCalendarCore::isRTL()
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 247](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L247)




### <a name="method-setActions"></a>setActions

```php
mixed HelperCalendarCore::setActions($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L49)


#### Arguments
* $value **mixed**



### <a name="method-setCompareActions"></a>setCompareActions

```php
mixed HelperCalendarCore::setCompareActions($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L66)


#### Arguments
* $value **mixed**



### <a name="method-setCompareDateFrom"></a>setCompareDateFrom

```php
mixed HelperCalendarCore::setCompareDateFrom($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L83)


#### Arguments
* $value **mixed**



### <a name="method-setCompareDateTo"></a>setCompareDateTo

```php
mixed HelperCalendarCore::setCompareDateTo($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L94)


#### Arguments
* $value **mixed**



### <a name="method-setCompareOption"></a>setCompareOption

```php
mixed HelperCalendarCore::setCompareOption($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L105)


#### Arguments
* $value **mixed**



### <a name="method-setDateFormat"></a>setDateFormat

```php
mixed HelperCalendarCore::setDateFormat($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L119)


#### Arguments
* $value **mixed**



### <a name="method-setDateFrom"></a>setDateFrom

```php
mixed HelperCalendarCore::setDateFrom($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L136)


#### Arguments
* $value **mixed**



### <a name="method-setDateTo"></a>setDateTo

```php
mixed HelperCalendarCore::setDateTo($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L156)


#### Arguments
* $value **mixed**



### <a name="method-setRTL"></a>setRTL

```php
mixed HelperCalendarCore::setRTL($value)
```





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.13/classes/helper/HelperCalendar.php#L176)


#### Arguments
* $value **mixed**


