Class CMSCore
=====================





* Class name: CMSCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/CMS.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/CMS.php#L27)


Contents
--------


### Properties

* [$active](#property-$active)
* [$content](#property-$content)
* [$definition](#property-$definition)
* [$id_cms_category](#property-$id_cms_category)
* [$indexation](#property-$indexation)
* [$link_rewrite](#property-$link_rewrite)
* [$meta_description](#property-$meta_description)
* [$meta_keywords](#property-$meta_keywords)
* [$meta_title](#property-$meta_title)
* [$position](#property-$position)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [add](#method-add)
* [cleanPositions](#method-cleanPositions)
* [delete](#method-delete)
* [getCMSPages](#method-getCMSPages)
* [getLastPosition](#method-getLastPosition)
* [getLinks](#method-getLinks)
* [getUrlRewriteInformations](#method-getUrlRewriteInformations)
* [listCms](#method-listCms)
* [update](#method-update)
* [updatePosition](#method-updatePosition)




Properties
----------


### <a name="property-$active"></a>$active

```php
public mixed $active
```





* Visibility: **public**
* Source: [classes/CMS.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/CMS.php#L38).


### <a name="property-$content"></a>$content

```php
public mixed $content
```





* Visibility: **public**
* Source: [classes/CMS.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/CMS.php#L33).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'cms', 'primary' => 'id_cms', 'multilang' => true, 'fields' => array('id_cms_category' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'position' => array('type' => self::TYPE_INT), 'indexation' => array('type' => self::TYPE_BOOL), 'active' => array('type' => self::TYPE_BOOL), 'meta_description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_keywords' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_title' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 128), 'link_rewrite' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isLinkRewrite', 'required' => true, 'size' => 128), 'content' => array('type' => self::TYPE_HTML, 'lang' => true, 'validate' => 'isCleanHtml', 'size' => 3999999999999.0)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/CMS.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/CMS.php#L43).


### <a name="property-$id_cms_category"></a>$id_cms_category

```php
public mixed $id_cms_category
```





* Visibility: **public**
* Source: [classes/CMS.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/CMS.php#L35).


### <a name="property-$indexation"></a>$indexation

```php
public mixed $indexation
```





* Visibility: **public**
* Source: [classes/CMS.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/CMS.php#L37).


### <a name="property-$link_rewrite"></a>$link_rewrite

```php
public mixed $link_rewrite
```





* Visibility: **public**
* Source: [classes/CMS.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/CMS.php#L34).


### <a name="property-$meta_description"></a>$meta_description

```php
public mixed $meta_description
```





* Visibility: **public**
* Source: [classes/CMS.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/CMS.php#L31).


### <a name="property-$meta_keywords"></a>$meta_keywords

```php
public mixed $meta_keywords
```





* Visibility: **public**
* Source: [classes/CMS.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/CMS.php#L32).


### <a name="property-$meta_title"></a>$meta_title

```php
public string $meta_title
```





* Visibility: **public**
* Source: [classes/CMS.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/CMS.php#L30).


### <a name="property-$position"></a>$position

```php
public mixed $position
```





* Visibility: **public**
* Source: [classes/CMS.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/CMS.php#L36).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectNodeName' => 'content', 'objectsNodeName' => 'content_management_system')
```





* Visibility: **protected**
* Source: [classes/CMS.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/CMS.php#L62).


Methods
-------


### <a name="method-add"></a>add

```php
mixed CMSCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/CMS.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/CMS.php#L67)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-cleanPositions"></a>cleanPositions

```php
mixed CMSCore::cleanPositions($id_category)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMS.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/CMS.php#L162)


#### Arguments
* $id_category **mixed**



### <a name="method-delete"></a>delete

```php
mixed CMSCore::delete()
```





* Visibility: **public**
* Source: [classes/CMS.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/CMS.php#L80)




### <a name="method-getCMSPages"></a>getCMSPages

```php
mixed CMSCore::getCMSPages($id_lang, $id_cms_category, $active, $id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMS.php line 193](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/CMS.php#L193)


#### Arguments
* $id_lang **mixed**
* $id_cms_category **mixed**
* $active **mixed**
* $id_shop **mixed**



### <a name="method-getLastPosition"></a>getLastPosition

```php
mixed CMSCore::getLastPosition($id_category)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMS.php line 183](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/CMS.php#L183)


#### Arguments
* $id_category **mixed**



### <a name="method-getLinks"></a>getLinks

```php
mixed CMSCore::getLinks($id_lang, $selection, $active, \Link $link)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMS.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/CMS.php#L87)


#### Arguments
* $id_lang **mixed**
* $selection **mixed**
* $active **mixed**
* $link **[Link](class.LinkCore.md)**



### <a name="method-getUrlRewriteInformations"></a>getUrlRewriteInformations

```php
mixed CMSCore::getUrlRewriteInformations($id_cms)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMS.php line 215](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/CMS.php#L215)


#### Arguments
* $id_cms **mixed**



### <a name="method-listCms"></a>listCms

```php
mixed CMSCore::listCms($id_lang, $id_block, $active)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMS.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/CMS.php#L112)


#### Arguments
* $id_lang **mixed**
* $id_block **mixed**
* $active **mixed**



### <a name="method-update"></a>update

```php
mixed CMSCore::update($null_values)
```





* Visibility: **public**
* Source: [classes/CMS.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/CMS.php#L73)


#### Arguments
* $null_values **mixed**



### <a name="method-updatePosition"></a>updatePosition

```php
mixed CMSCore::updatePosition($way, $position)
```





* Visibility: **public**
* Source: [classes/CMS.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/CMS.php#L128)


#### Arguments
* $way **mixed**
* $position **mixed**


