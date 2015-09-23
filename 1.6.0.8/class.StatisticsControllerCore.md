Class StatisticsControllerCore
=====================





* Class name: StatisticsControllerCore
* Parent class: [FrontController](class.FrontControllerCore.md)
* Source: [controllers/front/StatisticsController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/front/StatisticsController.php#L27)


Contents
--------


### Properties

* [$display_footer](#property-$display_footer)
* [$display_header](#property-$display_header)
* [$param_token](#property-$param_token)

### Methods

* [postProcess](#method-postProcess)
* [processNavigationStats](#method-processNavigationStats)
* [processPageTime](#method-processPageTime)




Properties
----------


### <a name="property-$display_footer"></a>$display_footer

```php
public mixed $display_footer = false
```





* Visibility: **public**
* Source: [controllers/front/StatisticsController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/front/StatisticsController.php#L30).


### <a name="property-$display_header"></a>$display_header

```php
public mixed $display_header = false
```





* Visibility: **public**
* Source: [controllers/front/StatisticsController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/front/StatisticsController.php#L29).


### <a name="property-$param_token"></a>$param_token

```php
protected mixed $param_token
```





* Visibility: **protected**
* Source: [controllers/front/StatisticsController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/front/StatisticsController.php#L32).


Methods
-------


### <a name="method-postProcess"></a>postProcess

```php
mixed StatisticsControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/front/StatisticsController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/front/StatisticsController.php#L34)




### <a name="method-processNavigationStats"></a>processNavigationStats

```php
mixed StatisticsControllerCore::processNavigationStats()
```

Log statistics on navigation (resolution, plugins, etc.)



* Visibility: **protected**
* Source: [controllers/front/StatisticsController.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/front/StatisticsController.php#L51)




### <a name="method-processPageTime"></a>processPageTime

```php
mixed StatisticsControllerCore::processPageTime()
```

Log statistics on time spend on pages



* Visibility: **protected**
* Source: [controllers/front/StatisticsController.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/front/StatisticsController.php#L74)



