Class CartControllerCore
=====================





* Class name: CartControllerCore
* Parent class: [FrontController](class.FrontControllerCore.md)
* Source: [controllers/front/CartController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CartController.php#L27)


Contents
--------


### Properties

* [$ajax_refresh](#property-$ajax_refresh)
* [$customization_id](#property-$customization_id)
* [$id_address_delivery](#property-$id_address_delivery)
* [$id_product](#property-$id_product)
* [$id_product_attribute](#property-$id_product_attribute)
* [$php_self](#property-$php_self)
* [$qty](#property-$qty)
* [$ssl](#property-$ssl)

### Methods

* [canonicalRedirection](#method-canonicalRedirection)
* [displayAjax](#method-displayAjax)
* [init](#method-init)
* [initContent](#method-initContent)
* [postProcess](#method-postProcess)
* [processAllowSeperatedPackage](#method-processAllowSeperatedPackage)
* [processChangeProductAddressDelivery](#method-processChangeProductAddressDelivery)
* [processChangeProductInCart](#method-processChangeProductInCart)
* [processDeleteProductInCart](#method-processDeleteProductInCart)
* [processDuplicateProduct](#method-processDuplicateProduct)
* [processRemoveDiscounts](#method-processRemoveDiscounts)




Properties
----------


### <a name="property-$ajax_refresh"></a>$ajax_refresh

```php
protected mixed $ajax_refresh = false
```





* Visibility: **protected**
* Source: [controllers/front/CartController.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CartController.php#L38).


### <a name="property-$customization_id"></a>$customization_id

```php
protected mixed $customization_id
```





* Visibility: **protected**
* Source: [controllers/front/CartController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CartController.php#L34).


### <a name="property-$id_address_delivery"></a>$id_address_delivery

```php
protected mixed $id_address_delivery
```





* Visibility: **protected**
* Source: [controllers/front/CartController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CartController.php#L33).


### <a name="property-$id_product"></a>$id_product

```php
protected mixed $id_product
```





* Visibility: **protected**
* Source: [controllers/front/CartController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CartController.php#L31).


### <a name="property-$id_product_attribute"></a>$id_product_attribute

```php
protected mixed $id_product_attribute
```





* Visibility: **protected**
* Source: [controllers/front/CartController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CartController.php#L32).


### <a name="property-$php_self"></a>$php_self

```php
public mixed $php_self = 'cart'
```





* Visibility: **public**
* Source: [controllers/front/CartController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CartController.php#L29).


### <a name="property-$qty"></a>$qty

```php
protected mixed $qty
```





* Visibility: **protected**
* Source: [controllers/front/CartController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CartController.php#L35).


### <a name="property-$ssl"></a>$ssl

```php
public mixed $ssl = true
```





* Visibility: **public**
* Source: [controllers/front/CartController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CartController.php#L36).


Methods
-------


### <a name="method-canonicalRedirection"></a>canonicalRedirection

```php
mixed CartControllerCore::canonicalRedirection($canonicalURL)
```

This is not a public page, so the canonical redirection is disabled



* Visibility: **public**
* Source: [controllers/front/CartController.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CartController.php#L43)


#### Arguments
* $canonicalURL **mixed**



### <a name="method-displayAjax"></a>displayAjax

```php
mixed CartControllerCore::displayAjax()
```

Display ajax content (this function is called instead of classic display, in ajax mode)



* Visibility: **public**
* Source: [controllers/front/CartController.php line 316](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CartController.php#L316)




### <a name="method-init"></a>init

```php
mixed CartControllerCore::init()
```

Initialize cart controller



* Visibility: **public**
* Source: [controllers/front/CartController.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CartController.php#L51)




### <a name="method-initContent"></a>initContent

```php
mixed CartControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/front/CartController.php line 306](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CartController.php#L306)




### <a name="method-postProcess"></a>postProcess

```php
mixed CartControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/front/CartController.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CartController.php#L66)




### <a name="method-processAllowSeperatedPackage"></a>processAllowSeperatedPackage

```php
mixed CartControllerCore::processAllowSeperatedPackage()
```





* Visibility: **protected**
* Source: [controllers/front/CartController.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CartController.php#L145)




### <a name="method-processChangeProductAddressDelivery"></a>processChangeProductAddressDelivery

```php
mixed CartControllerCore::processChangeProductAddressDelivery()
```





* Visibility: **protected**
* Source: [controllers/front/CartController.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CartController.php#L124)




### <a name="method-processChangeProductInCart"></a>processChangeProductInCart

```php
mixed CartControllerCore::processChangeProductInCart()
```

This process add or update a product in the cart



* Visibility: **protected**
* Source: [controllers/front/CartController.php line 179](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CartController.php#L179)




### <a name="method-processDeleteProductInCart"></a>processDeleteProductInCart

```php
mixed CartControllerCore::processDeleteProductInCart()
```

This process delete a product from the cart



* Visibility: **protected**
* Source: [controllers/front/CartController.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CartController.php#L107)




### <a name="method-processDuplicateProduct"></a>processDuplicateProduct

```php
mixed CartControllerCore::processDuplicateProduct()
```





* Visibility: **protected**
* Source: [controllers/front/CartController.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CartController.php#L158)




### <a name="method-processRemoveDiscounts"></a>processRemoveDiscounts

```php
mixed CartControllerCore::processRemoveDiscounts()
```

Remove discounts on cart



* Visibility: **protected**
* Source: [controllers/front/CartController.php line 297](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/front/CartController.php#L297)



