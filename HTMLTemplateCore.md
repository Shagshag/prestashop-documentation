HTMLTemplateCore
===============






* Class name: HTMLTemplateCore
* Namespace: 
* This is an **abstract** class





Properties
----------


### $title

    public mixed $title





* Visibility: **public**


### $date

    public mixed $date





* Visibility: **public**


### $available_in_your_account

    public mixed $available_in_your_account = true





* Visibility: **public**


### $smarty

    public \Smarty $smarty





* Visibility: **public**


### $shop

    public \Shop $shop





* Visibility: **public**


Methods
-------


### getHeader

    string HTMLTemplateCore::getHeader()

Returns the template's HTML header



* Visibility: **public**




### getFooter

    string HTMLTemplateCore::getFooter()

Returns the template's HTML footer



* Visibility: **public**




### getShopAddress

    string HTMLTemplateCore::getShopAddress()

Returns the shop address



* Visibility: **protected**




### getLogo

    mixed HTMLTemplateCore::getLogo()

Returns the invoice logo



* Visibility: **protected**




### assignCommonHeaderData

    mixed HTMLTemplateCore::assignCommonHeaderData()

Assign common header data to smarty variables



* Visibility: **public**




### assignHookData

    mixed HTMLTemplateCore::assignHookData(\ObjectModel $object)

Assign hook data



* Visibility: **public**


#### Arguments
* $object **ObjectModel** - &lt;p&gt;generally the object used in the constructor&lt;/p&gt;



### getContent

    string HTMLTemplateCore::getContent()

Returns the template's HTML content



* Visibility: **public**
* This method is **abstract**.




### getFilename

    string HTMLTemplateCore::getFilename()

Returns the template filename



* Visibility: **public**
* This method is **abstract**.




### getBulkFilename

    string HTMLTemplateCore::getBulkFilename()

Returns the template filename when using bulk rendering



* Visibility: **public**
* This method is **abstract**.




### getTemplate

    string HTMLTemplateCore::getTemplate($template_name)

If the template is not present in the theme directory, it will return the default template
in _PS_PDF_DIR_ directory



* Visibility: **protected**


#### Arguments
* $template_name **mixed**



### l

    string HTMLTemplateCore::l(string $string)

Translation method



* Visibility: **protected**
* This method is **static**.


#### Arguments
* $string **string**



### setShopId

    mixed HTMLTemplateCore::setShopId()





* Visibility: **protected**



