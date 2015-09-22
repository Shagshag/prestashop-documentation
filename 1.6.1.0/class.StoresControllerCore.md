Class StoresControllerCore
=====================





* Class name: StoresControllerCore
* Parent class: [FrontController](class.FrontControllerCore.md)
* Source: [controllers/front/StoresController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/StoresController.php#L27)


Contents
--------


### Properties

* [$php_self](#property-$php_self)

### Methods

* [assignStores](#method-assignStores)
* [assignStoresSimplified](#method-assignStoresSimplified)
* [displayAjax](#method-displayAjax)
* [getStores](#method-getStores)
* [init](#method-init)
* [initContent](#method-initContent)
* [processStoreAddress](#method-processStoreAddress)
* [renderStoreWorkingHours](#method-renderStoreWorkingHours)
* [setMedia](#method-setMedia)




Properties
----------


### <a name="property-$php_self"></a>$php_self

```php
public mixed $php_self = 'stores'
```





* Visibility: **public**
* Source: [controllers/front/StoresController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/StoresController.php#L29).


Methods
-------


### <a name="method-assignStores"></a>assignStores

```php
mixed StoresControllerCore::assignStores()
```

Assign template vars for classical stores



* Visibility: **protected**
* Source: [controllers/front/StoresController.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/StoresController.php#L217)




### <a name="method-assignStoresSimplified"></a>assignStoresSimplified

```php
mixed StoresControllerCore::assignStoresSimplified()
```

Assign template vars for simplified stores



* Visibility: **protected**
* Source: [controllers/front/StoresController.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/StoresController.php#L92)




### <a name="method-displayAjax"></a>displayAjax

```php
mixed StoresControllerCore::displayAjax()
```

Display the Xml for showing the nodes in the google map



* Visibility: **protected**
* Source: [controllers/front/StoresController.php line 235](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/StoresController.php#L235)




### <a name="method-getStores"></a>getStores

```php
mixed StoresControllerCore::getStores()
```





* Visibility: **public**
* Source: [controllers/front/StoresController.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/StoresController.php#L168)




### <a name="method-init"></a>init

```php
mixed StoresControllerCore::init()
```

Initialize stores controller



* Visibility: **public**
* Source: [controllers/front/StoresController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/StoresController.php#L35)




### <a name="method-initContent"></a>initContent

```php
mixed StoresControllerCore::initContent()
```

Assign template vars related to page content



* Visibility: **public**
* Source: [controllers/front/StoresController.php line 268](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/StoresController.php#L268)




### <a name="method-processStoreAddress"></a>processStoreAddress

```php
string StoresControllerCore::processStoreAddress(array $store)
```

Get formatted string address



* Visibility: **protected**
* Source: [controllers/front/StoresController.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/StoresController.php#L53)


#### Arguments
* $store **array**



### <a name="method-renderStoreWorkingHours"></a>renderStoreWorkingHours

```php
mixed StoresControllerCore::renderStoreWorkingHours($store)
```





* Visibility: **public**
* Source: [controllers/front/StoresController.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/StoresController.php#L127)


#### Arguments
* $store **mixed**



### <a name="method-setMedia"></a>setMedia

```php
mixed StoresControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/front/StoresController.php line 288](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/front/StoresController.php#L288)



