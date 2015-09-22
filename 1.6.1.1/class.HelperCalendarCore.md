Class HelperCalendarCore
=====================





* Class name: HelperCalendarCore
* Parent class: [Helper](class.HelperCore.md)
* Source: [classes/helper/HelperCalendar.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L27)

Constants
----------

* [DEFAULT_COMPARE_OPTION](#constant-DEFAULT_COMPARE_OPTION)
* [DEFAULT_DATE_FORMAT](#constant-DEFAULT_DATE_FORMAT)

Properties
----------

* [$_actions](#property-$_actions)
* [$_compare_actions](#property-$_compare_actions)
* [$_compare_date_from](#property-$_compare_date_from)
* [$_compare_date_option](#property-$_compare_date_option)
* [$_compare_date_to](#property-$_compare_date_to)
* [$_date_format](#property-$_date_format)
* [$_date_from](#property-$_date_from)
* [$_date_to](#property-$_date_to)
* [$_rtl](#property-$_rtl)

Methods
-------
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

    const DEFAULT_COMPARE_OPTION = 1





* Source: [classes/helper/HelperCalendar.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L30).


### <a name="constant-DEFAULT_DATE_FORMAT"></a>DEFAULT_DATE_FORMAT

    const DEFAULT_DATE_FORMAT = 'Y-mm-dd'





* Source: [classes/helper/HelperCalendar.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L29).


Properties
----------


### <a name="property-$_actions"></a>$_actions

    private mixed $_actions





* Visibility: **private**
* Source: [classes/helper/HelperCalendar.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L32).


### <a name="property-$_compare_actions"></a>$_compare_actions

    private mixed $_compare_actions





* Visibility: **private**
* Source: [classes/helper/HelperCalendar.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L33).


### <a name="property-$_compare_date_from"></a>$_compare_date_from

    private mixed $_compare_date_from





* Visibility: **private**
* Source: [classes/helper/HelperCalendar.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L34).


### <a name="property-$_compare_date_option"></a>$_compare_date_option

    private mixed $_compare_date_option





* Visibility: **private**
* Source: [classes/helper/HelperCalendar.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L36).


### <a name="property-$_compare_date_to"></a>$_compare_date_to

    private mixed $_compare_date_to





* Visibility: **private**
* Source: [classes/helper/HelperCalendar.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L35).


### <a name="property-$_date_format"></a>$_date_format

    private mixed $_date_format





* Visibility: **private**
* Source: [classes/helper/HelperCalendar.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L37).


### <a name="property-$_date_from"></a>$_date_from

    private mixed $_date_from





* Visibility: **private**
* Source: [classes/helper/HelperCalendar.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L38).


### <a name="property-$_date_to"></a>$_date_to

    private mixed $_date_to





* Visibility: **private**
* Source: [classes/helper/HelperCalendar.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L39).


### <a name="property-$_rtl"></a>$_rtl

    private mixed $_rtl





* Visibility: **private**
* Source: [classes/helper/HelperCalendar.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L40).


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed HelperCalendarCore::__construct()





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L42)




### <a name="method-addAction"></a>addAction

    mixed HelperCalendarCore::addAction($action)





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L195)


#### Arguments
* $action **mixed**



### <a name="method-addCompareAction"></a>addCompareAction

    mixed HelperCalendarCore::addCompareAction($action)





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 206](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L206)


#### Arguments
* $action **mixed**



### <a name="method-generate"></a>generate

    mixed HelperCalendarCore::generate()





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L217)




### <a name="method-getActions"></a>getActions

    mixed HelperCalendarCore::getActions()





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L59)




### <a name="method-getCompareActions"></a>getCompareActions

    mixed HelperCalendarCore::getCompareActions()





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L78)




### <a name="method-getCompareDateFrom"></a>getCompareDateFrom

    mixed HelperCalendarCore::getCompareDateFrom()





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L93)




### <a name="method-getCompareDateTo"></a>getCompareDateTo

    mixed HelperCalendarCore::getCompareDateTo()





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L104)




### <a name="method-getCompareOption"></a>getCompareOption

    mixed HelperCalendarCore::getCompareOption()





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L115)




### <a name="method-getDateFormat"></a>getDateFormat

    mixed HelperCalendarCore::getDateFormat()





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L134)




### <a name="method-getDateFrom"></a>getDateFrom

    mixed HelperCalendarCore::getDateFrom()





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L157)




### <a name="method-getDateTo"></a>getDateTo

    mixed HelperCalendarCore::getDateTo()





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L180)




### <a name="method-isRTL"></a>isRTL

    mixed HelperCalendarCore::isRTL()





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 260](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L260)




### <a name="method-setActions"></a>setActions

    mixed HelperCalendarCore::setActions($value)





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L49)


#### Arguments
* $value **mixed**



### <a name="method-setCompareActions"></a>setCompareActions

    mixed HelperCalendarCore::setCompareActions($value)





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L68)


#### Arguments
* $value **mixed**



### <a name="method-setCompareDateFrom"></a>setCompareDateFrom

    mixed HelperCalendarCore::setCompareDateFrom($value)





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L87)


#### Arguments
* $value **mixed**



### <a name="method-setCompareDateTo"></a>setCompareDateTo

    mixed HelperCalendarCore::setCompareDateTo($value)





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L98)


#### Arguments
* $value **mixed**



### <a name="method-setCompareOption"></a>setCompareOption

    mixed HelperCalendarCore::setCompareOption($value)





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L109)


#### Arguments
* $value **mixed**



### <a name="method-setDateFormat"></a>setDateFormat

    mixed HelperCalendarCore::setDateFormat($value)





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L124)


#### Arguments
* $value **mixed**



### <a name="method-setDateFrom"></a>setDateFrom

    mixed HelperCalendarCore::setDateFrom($value)





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L143)


#### Arguments
* $value **mixed**



### <a name="method-setDateTo"></a>setDateTo

    mixed HelperCalendarCore::setDateTo($value)





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L166)


#### Arguments
* $value **mixed**



### <a name="method-setRTL"></a>setRTL

    mixed HelperCalendarCore::setRTL($value)





* Visibility: **public**
* Source: [classes/helper/HelperCalendar.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperCalendar.php#L189)


#### Arguments
* $value **mixed**


