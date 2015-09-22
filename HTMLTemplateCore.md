HTMLTemplateCore
===============






* Class name: HTMLTemplateCore
* Namespace: 
* This is an **abstract** class

* This class is defined in [classes/pdf/HTMLTemplate.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#30)





Properties
----------


### $title

    public mixed $title





* Visibility: **public**
* This property is defined in [classes/pdf/HTMLTemplate.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#32)


### $date

    public mixed $date





* Visibility: **public**
* This property is defined in [classes/pdf/HTMLTemplate.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#33)


### $available_in_your_account

    public mixed $available_in_your_account = true





* Visibility: **public**
* This property is defined in [classes/pdf/HTMLTemplate.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#34)


### $smarty

    public \Smarty $smarty





* Visibility: **public**
* This property is defined in [classes/pdf/HTMLTemplate.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#37)


### $shop

    public \Shop $shop





* Visibility: **public**
* This property is defined in [classes/pdf/HTMLTemplate.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#40)


Methods
-------


### getHeader

    string HTMLTemplateCore::getHeader()

Returns the template's HTML header



* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplate.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#47)




### getFooter

    string HTMLTemplateCore::getFooter()

Returns the template's HTML footer



* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplate.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#59)




### getShopAddress

    string HTMLTemplateCore::getShopAddress()

Returns the shop address



* Visibility: **protected**
* This method is defined in [classes/pdf/HTMLTemplate.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#82)




### getLogo

    mixed HTMLTemplateCore::getLogo()

Returns the invoice logo



* Visibility: **protected**
* This method is defined in [classes/pdf/HTMLTemplate.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#97)




### assignCommonHeaderData

    mixed HTMLTemplateCore::assignCommonHeaderData()

Assign common header data to smarty variables



* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplate.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#115)




### assignHookData

    mixed HTMLTemplateCore::assignHookData(\ObjectModel $object)

Assign hook data



* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplate.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#155)


#### Arguments
* $object **[ObjectModel](ObjectModelCore)** - &lt;p&gt;generally the object used in the constructor&lt;/p&gt;



### getContent

    string HTMLTemplateCore::getContent()

Returns the template's HTML content



* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/pdf/HTMLTemplate.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#170)




### getFilename

    string HTMLTemplateCore::getFilename()

Returns the template filename



* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/pdf/HTMLTemplate.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#178)




### getBulkFilename

    string HTMLTemplateCore::getBulkFilename()

Returns the template filename when using bulk rendering



* Visibility: **public**
* This method is **abstract**.
* This method is defined in [classes/pdf/HTMLTemplate.php line 185](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#185)




### getTemplate

    string HTMLTemplateCore::getTemplate($template_name)

If the template is not present in the theme directory, it will return the default template
in _PS_PDF_DIR_ directory



* Visibility: **protected**
* This method is defined in [classes/pdf/HTMLTemplate.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#195)


#### Arguments
* $template_name **mixed**



### l

    string HTMLTemplateCore::l(string $string)

Translation method



* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/pdf/HTMLTemplate.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#217)


#### Arguments
* $string **string**



### setShopId

    mixed HTMLTemplateCore::setShopId()





* Visibility: **protected**
* This method is defined in [classes/pdf/HTMLTemplate.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#222)



