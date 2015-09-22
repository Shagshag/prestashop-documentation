Class StatisticsControllerCore
=====================





* Class name: StatisticsControllerCore
* Parent class: [FrontController](class.FrontControllerCore.md)
* Source: [controllers/front/StatisticsController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/StatisticsController.php#L27)



Properties
----------

* [$display_footer](#property-$display_footer)
* [$display_header](#property-$display_header)
* [$param_token](#property-$param_token)

Methods
-------
* [postProcess](#method-postProcess)
* [processNavigationStats](#method-processNavigationStats)
* [processPageTime](#method-processPageTime)




Properties
----------


### <a name="property-$display_footer"></a>$display_footer

    public mixed $display_footer = false





* Visibility: **public**
* Source: [controllers/front/StatisticsController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/StatisticsController.php#L30).


### <a name="property-$display_header"></a>$display_header

    public mixed $display_header = false





* Visibility: **public**
* Source: [controllers/front/StatisticsController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/StatisticsController.php#L29).


### <a name="property-$param_token"></a>$param_token

    protected mixed $param_token





* Visibility: **protected**
* Source: [controllers/front/StatisticsController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/StatisticsController.php#L32).


Methods
-------


### <a name="method-postProcess"></a>postProcess

    mixed StatisticsControllerCore::postProcess()





* Visibility: **public**
* Source: [controllers/front/StatisticsController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/StatisticsController.php#L34)




### <a name="method-processNavigationStats"></a>processNavigationStats

    mixed StatisticsControllerCore::processNavigationStats()

Log statistics on navigation (resolution, plugins, etc.)



* Visibility: **protected**
* Source: [controllers/front/StatisticsController.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/StatisticsController.php#L53)




### <a name="method-processPageTime"></a>processPageTime

    mixed StatisticsControllerCore::processPageTime()

Log statistics on time spend on pages



* Visibility: **protected**
* Source: [controllers/front/StatisticsController.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/StatisticsController.php#L77)



