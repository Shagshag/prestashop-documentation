AdminProductsControllerCore
===============






* Class name: AdminProductsControllerCore
* Namespace: 
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in controllers\admin\AdminProductsController.php line 30





Properties
----------


### $max_file_size

    protected integer $max_file_size = null





* Visibility: **protected**
* This property is defined in controllers\admin\AdminProductsController.php line 35


### $max_image_size

    protected mixed $max_image_size = null





* Visibility: **protected**
* This property is defined in controllers\admin\AdminProductsController.php line 36


### $_category

    protected mixed $_category





* Visibility: **protected**
* This property is defined in controllers\admin\AdminProductsController.php line 38


### $tab_display

    protected string $tab_display





* Visibility: **protected**
* This property is defined in controllers\admin\AdminProductsController.php line 42


### $tab_display_module

    protected mixed $tab_display_module





* Visibility: **protected**
* This property is defined in controllers\admin\AdminProductsController.php line 43


### $available_tabs

    protected array $available_tabs = array()

The order in the array decides the order in the list of tab. If an element's value is a number, it will be preloaded.

The tabs are preloaded from the smallest to the highest number.

* Visibility: **protected**
* This property is defined in controllers\admin\AdminProductsController.php line 50


### $default_tab

    protected mixed $default_tab = 'Informations'





* Visibility: **protected**
* This property is defined in controllers\admin\AdminProductsController.php line 52


### $available_tabs_lang

    protected mixed $available_tabs_lang = array()





* Visibility: **protected**
* This property is defined in controllers\admin\AdminProductsController.php line 54


### $position_identifier

    protected mixed $position_identifier = 'id_product'





* Visibility: **protected**
* This property is defined in controllers\admin\AdminProductsController.php line 56


### $submitted_tabs

    protected mixed $submitted_tabs





* Visibility: **protected**
* This property is defined in controllers\admin\AdminProductsController.php line 58


### $id_current_category

    protected mixed $id_current_category





* Visibility: **protected**
* This property is defined in controllers\admin\AdminProductsController.php line 60


### $object

    public \Product $object





* Visibility: **public**
* This property is defined in controllers\admin\AdminProductsController.php line 30


Methods
-------


### __construct

    mixed AdminProductsControllerCore::__construct()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 62




### getQuantities

    mixed AdminProductsControllerCore::getQuantities($echo, $tr)





* Visibility: **public**
* This method is **static**.
* This method is defined in controllers\admin\AdminProductsController.php line 278


#### Arguments
* $echo **mixed**
* $tr **mixed**



### setMedia

    mixed AdminProductsControllerCore::setMedia()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 287




### _cleanMetaKeywords

    mixed AdminProductsControllerCore::_cleanMetaKeywords($keywords)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminProductsController.php line 307


#### Arguments
* $keywords **mixed**



### copyFromPost

    mixed AdminProductsControllerCore::copyFromPost(\Product|\ObjectModel $object, string $table)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminProductsController.php line 328


#### Arguments
* $object **[Product](ProductCore)|[Product](ObjectModelCore)**
* $table **string**



### checkMultishopBox

    mixed AdminProductsControllerCore::checkMultishopBox($field, $context)





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 373


#### Arguments
* $field **mixed**
* $context **mixed**



### getList

    mixed AdminProductsControllerCore::getList($id_lang, $orderBy, $orderWay, $start, $limit, $id_lang_shop)





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 401


#### Arguments
* $id_lang **mixed**
* $orderBy **mixed**
* $orderWay **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### loadObject

    mixed AdminProductsControllerCore::loadObject($opt)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminProductsController.php line 443


#### Arguments
* $opt **mixed**



### ajaxProcessGetCategoryTree

    mixed AdminProductsControllerCore::ajaxProcessGetCategoryTree()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 465




### ajaxProcessGetCountriesOptions

    mixed AdminProductsControllerCore::ajaxProcessGetCountriesOptions()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 492




### ajaxProcessGetCurrenciesOptions

    mixed AdminProductsControllerCore::ajaxProcessGetCurrenciesOptions()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 509




### ajaxProcessGetGroupsOptions

    mixed AdminProductsControllerCore::ajaxProcessGetGroupsOptions()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 526




### processDeleteVirtualProduct

    mixed AdminProductsControllerCore::processDeleteVirtualProduct()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 543




### ajaxProcessAddAttachment

    mixed AdminProductsControllerCore::ajaxProcessAddAttachment()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 561




### processAttachments

    void AdminProductsControllerCore::processAttachments()

Attach an existing attachment to the product



* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 694




### processDuplicate

    mixed AdminProductsControllerCore::processDuplicate()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 705




### processDelete

    mixed AdminProductsControllerCore::processDelete()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 753




### processImage

    mixed AdminProductsControllerCore::processImage()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 792




### processBulkDelete

    mixed AdminProductsControllerCore::processBulkDelete()





* Visibility: **protected**
* This method is defined in controllers\admin\AdminProductsController.php line 827




### processProductAttribute

    mixed AdminProductsControllerCore::processProductAttribute()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 893




### processFeatures

    mixed AdminProductsControllerCore::processFeatures()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 1033




### processPricesModification

    mixed AdminProductsControllerCore::processPricesModification()

This function is never called at the moment (specific prices cannot be edited)



* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 1071




### processPriceAddition

    mixed AdminProductsControllerCore::processPriceAddition()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 1114




### ajaxProcessDeleteSpecificPrice

    mixed AdminProductsControllerCore::ajaxProcessDeleteSpecificPrice()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 1171




### processSpecificPricePriorities

    mixed AdminProductsControllerCore::processSpecificPricePriorities()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 1202




### processCustomizationConfiguration

    mixed AdminProductsControllerCore::processCustomizationConfiguration()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 1220




### processProductCustomization

    mixed AdminProductsControllerCore::processProductCustomization()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 1249




### processPosition

    mixed AdminProductsControllerCore::processPosition()

Overrides parent for custom redirect link



* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 1271




### initProcess

    mixed AdminProductsControllerCore::initProcess()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 1288




### postProcess

    void AdminProductsControllerCore::postProcess()

postProcess handle every checks before saving products information



* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 1437




### ajaxProcessDeleteProductAttribute

    mixed AdminProductsControllerCore::ajaxProcessDeleteProductAttribute()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 1481




### ajaxProcessDefaultProductAttribute

    mixed AdminProductsControllerCore::ajaxProcessDefaultProductAttribute()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 1537




### ajaxProcessEditProductAttribute

    mixed AdminProductsControllerCore::ajaxProcessEditProductAttribute()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 1562




### ajaxPreProcess

    mixed AdminProductsControllerCore::ajaxPreProcess()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 1578




### ajaxProcessUpdateProductImageShopAsso

    mixed AdminProductsControllerCore::ajaxProcessUpdateProductImageShopAsso()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 1586




### ajaxProcessUpdateImagePosition

    mixed AdminProductsControllerCore::ajaxProcessUpdateImagePosition()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 1637




### ajaxProcessUpdateCover

    mixed AdminProductsControllerCore::ajaxProcessUpdateCover()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 1660




### ajaxProcessDeleteProductImage

    mixed AdminProductsControllerCore::ajaxProcessDeleteProductImage()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 1679




### _validateSpecificPrice

    mixed AdminProductsControllerCore::_validateSpecificPrice($id_shop, $id_currency, $id_country, $id_group, $id_customer, $price, $from_quantity, $reduction, $reduction_type, $from, $to, $id_combination)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminProductsController.php line 1718


#### Arguments
* $id_shop **mixed**
* $id_currency **mixed**
* $id_country **mixed**
* $id_group **mixed**
* $id_customer **mixed**
* $price **mixed**
* $from_quantity **mixed**
* $reduction **mixed**
* $reduction_type **mixed**
* $from **mixed**
* $to **mixed**
* $id_combination **mixed**



### checkFeatures

    mixed AdminProductsControllerCore::checkFeatures($languages, $feature_id)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminProductsController.php line 1739


#### Arguments
* $languages **mixed**
* $feature_id **mixed**



### addProductImage

    integer|false AdminProductsControllerCore::addProductImage(\Product $product, string $method)

Add or update a product image



* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 1780


#### Arguments
* $product **[Product](ProductCore)** - &lt;p&gt;Product object to add image&lt;/p&gt;
* $method **string**



### copyImage

    void|false AdminProductsControllerCore::copyImage(integer $id_product, integer $id_image, string $method)

Copy a product image



* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 1822


#### Arguments
* $id_product **integer** - &lt;p&gt;Product Id for product image filename&lt;/p&gt;
* $id_image **integer** - &lt;p&gt;Image Id for product image filename&lt;/p&gt;
* $method **string**



### updateAssoShop

    mixed AdminProductsControllerCore::updateAssoShop($id_object)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminProductsController.php line 1853


#### Arguments
* $id_object **mixed**



### processAdd

    mixed AdminProductsControllerCore::processAdd()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 1859




### isTabSubmitted

    mixed AdminProductsControllerCore::isTabSubmitted($tab_name)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminProductsController.php line 1940


#### Arguments
* $tab_name **mixed**



### processStatus

    mixed AdminProductsControllerCore::processStatus()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 1953




### processUpdate

    mixed AdminProductsControllerCore::processUpdate()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 1983




### checkProduct

    mixed AdminProductsControllerCore::checkProduct()

Check that a saved product is valid



* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 2133




### isProductFieldUpdated

    boolean AdminProductsControllerCore::isProductFieldUpdated(string $field, integer $id_lang)

Check if a field is edited (if the checkbox is checked)
This method will do something only for multishop with a context all / group



* Visibility: **protected**
* This method is defined in controllers\admin\AdminProductsController.php line 2287


#### Arguments
* $field **string** - &lt;p&gt;Name of field&lt;/p&gt;
* $id_lang **integer**



### _removeTaxFromEcotax

    mixed AdminProductsControllerCore::_removeTaxFromEcotax()





* Visibility: **protected**
* This method is defined in controllers\admin\AdminProductsController.php line 2306




### _applyTaxToEcotax

    mixed AdminProductsControllerCore::_applyTaxToEcotax($product)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminProductsController.php line 2313


#### Arguments
* $product **mixed**



### updateDownloadProduct

    boolean AdminProductsControllerCore::updateDownloadProduct(\Product $product, integer $edit)

Update product download



* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 2328


#### Arguments
* $product **[Product](ProductCore)**
* $edit **integer**



### updateAccessories

    mixed AdminProductsControllerCore::updateAccessories(object $product)

Update product accessories



* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 2404


#### Arguments
* $product **object** - &lt;p&gt;Product&lt;/p&gt;



### updateTags

    boolean AdminProductsControllerCore::updateTags(array $languages, object $product)

Update product tags



* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 2423


#### Arguments
* $languages **array** - &lt;p&gt;Array languages&lt;/p&gt;
* $product **object** - &lt;p&gt;Product&lt;/p&gt;



### initContent

    mixed AdminProductsControllerCore::initContent($token)





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 2444


#### Arguments
* $token **mixed**



### renderKpis

    mixed AdminProductsControllerCore::renderKpis()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 2520




### renderList

    mixed AdminProductsControllerCore::renderList()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 2593




### ajaxProcessProductManufacturers

    mixed AdminProductsControllerCore::ajaxProcessProductManufacturers()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 2602




### recurseCategoryForInclude

    string AdminProductsControllerCore::recurseCategoryForInclude($id_obj, array $indexedCategories, array $categories, $current, null $id_category, null $id_category_default, array $has_suite)

Build a categories tree



* Visibility: **public**
* This method is **static**.
* This method is defined in controllers\admin\AdminProductsController.php line 2630


#### Arguments
* $id_obj **mixed**
* $indexedCategories **array** - &lt;p&gt;Array with categories where product is indexed (in order to check checkbox)&lt;/p&gt;
* $categories **array** - &lt;p&gt;Categories to list&lt;/p&gt;
* $current **mixed**
* $id_category **null** - &lt;p&gt;Current category ID&lt;/p&gt;
* $id_category_default **null**
* $has_suite **array**



### _displayDraftWarning

    mixed AdminProductsControllerCore::_displayDraftWarning($active)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminProductsController.php line 2679


#### Arguments
* $active **mixed**



### initPageHeaderToolbar

    mixed AdminProductsControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 2689




### initToolbar

    mixed AdminProductsControllerCore::initToolbar()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 2750




### renderForm

    string|void AdminProductsControllerCore::renderForm()

renderForm contains all necessary initialization needed for all tabs



* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 2790




### getPreviewUrl

    mixed AdminProductsControllerCore::getPreviewUrl(\Product $product)





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 2911


#### Arguments
* $product **[Product](ProductCore)**



### processSuppliers

    mixed AdminProductsControllerCore::processSuppliers()

Post treatment for suppliers



* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 2943




### processWarehouses

    mixed AdminProductsControllerCore::processWarehouses()

Post treatment for warehouses



* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 3104




### initFormAssociations

    mixed AdminProductsControllerCore::initFormAssociations(\Product $obj)





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 3180


#### Arguments
* $obj **[Product](ProductCore)**



### initFormPrices

    mixed AdminProductsControllerCore::initFormPrices(\Product $obj)





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 3254


#### Arguments
* $obj **[Product](ProductCore)**



### initFormSeo

    mixed AdminProductsControllerCore::initFormSeo($product)





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 3364


#### Arguments
* $product **mixed**



### getPackItems

    array AdminProductsControllerCore::getPackItems(\Product $product)

Get an array of pack items for display from the product object if specified, else from POST/GET values



* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 3401


#### Arguments
* $product **[Product](ProductCore)**



### initFormPack

    mixed AdminProductsControllerCore::initFormPack(\Product $product)





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 3449


#### Arguments
* $product **[Product](ProductCore)**



### initFormVirtualProduct

    mixed AdminProductsControllerCore::initFormVirtualProduct($product)





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 3480


#### Arguments
* $product **mixed**



### _getFinalPrice

    mixed AdminProductsControllerCore::_getFinalPrice($specific_price, $product_price, $tax_rate)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminProductsController.php line 3547


#### Arguments
* $specific_price **mixed**
* $product_price **mixed**
* $tax_rate **mixed**



### _displaySpecificPriceModificationForm

    mixed AdminProductsControllerCore::_displaySpecificPriceModificationForm($defaultCurrency, $shops, $currencies, $countries, $groups)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminProductsController.php line 3552


#### Arguments
* $defaultCurrency **mixed**
* $shops **mixed**
* $currencies **mixed**
* $countries **mixed**
* $groups **mixed**



### _getCustomizationFieldIds

    mixed AdminProductsControllerCore::_getCustomizationFieldIds($labels, $alreadyGenerated, $obj)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminProductsController.php line 3769


#### Arguments
* $labels **mixed**
* $alreadyGenerated **mixed**
* $obj **mixed**



### _displayLabelField

    mixed AdminProductsControllerCore::_displayLabelField($label, $languages, $default_language, $type, $fieldIds, $id_customization_field)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminProductsController.php line 3793


#### Arguments
* $label **mixed**
* $languages **mixed**
* $default_language **mixed**
* $type **mixed**
* $fieldIds **mixed**
* $id_customization_field **mixed**



### _displayLabelFields

    mixed AdminProductsControllerCore::_displayLabelFields($obj, $labels, $languages, $default_language, $type)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminProductsController.php line 3822


#### Arguments
* $obj **mixed**
* $labels **mixed**
* $languages **mixed**
* $default_language **mixed**
* $type **mixed**



### initFormCustomization

    mixed AdminProductsControllerCore::initFormCustomization(\Product $obj)





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 3842


#### Arguments
* $obj **[Product](ProductCore)**



### initFormAttachments

    mixed AdminProductsControllerCore::initFormAttachments($obj)





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 3874


#### Arguments
* $obj **mixed**



### initFormInformations

    mixed AdminProductsControllerCore::initFormInformations(\Product $product)





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 3930


#### Arguments
* $product **[Product](ProductCore)**



### initFormShipping

    mixed AdminProductsControllerCore::initFormShipping($obj)





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 4034


#### Arguments
* $obj **mixed**



### getCarrierList

    mixed AdminProductsControllerCore::getCarrierList()





* Visibility: **protected**
* This method is defined in controllers\admin\AdminProductsController.php line 4048




### addCarriers

    mixed AdminProductsControllerCore::addCarriers($product)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminProductsController.php line 4067


#### Arguments
* $product **mixed**



### ajaxProcessaddProductImage

    mixed AdminProductsControllerCore::ajaxProcessaddProductImage()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 4084




### initFormImages

    mixed AdminProductsControllerCore::initFormImages(\Product $obj)





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 4216


#### Arguments
* $obj **[Product](ProductCore)**



### initFormCombinations

    mixed AdminProductsControllerCore::initFormCombinations($obj)





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 4297


#### Arguments
* $obj **mixed**



### initFormAttributes

    mixed AdminProductsControllerCore::initFormAttributes(\Product $product)





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 4307


#### Arguments
* $product **[Product](ProductCore)**



### renderListAttributes

    string AdminProductsControllerCore::renderListAttributes(\Product $product, \Currency|array|integer $currency)





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 4385


#### Arguments
* $product **[Product](ProductCore)**
* $currency **[Currency](CurrencyCore)|array|integer**



### initFormQuantities

    mixed AdminProductsControllerCore::initFormQuantities(\Product $obj)





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 4484


#### Arguments
* $obj **[Product](ProductCore)**



### initFormSuppliers

    mixed AdminProductsControllerCore::initFormSuppliers(\Product $obj)





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 4638


#### Arguments
* $obj **[Product](ProductCore)**



### initFormWarehouses

    mixed AdminProductsControllerCore::initFormWarehouses(\Product $obj)





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 4720


#### Arguments
* $obj **[Product](ProductCore)**



### initFormFeatures

    mixed AdminProductsControllerCore::initFormFeatures(\Product $obj)





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 4775


#### Arguments
* $obj **[Product](ProductCore)**



### ajaxProcessProductQuantity

    mixed AdminProductsControllerCore::ajaxProcessProductQuantity()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 4834




### getCombinationImagesJS

    mixed AdminProductsControllerCore::getCombinationImagesJS()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 4935




### haveThisAccessory

    mixed AdminProductsControllerCore::haveThisAccessory($accessory_id, $accessories)





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 4956


#### Arguments
* $accessory_id **mixed**
* $accessories **mixed**



### initPack

    mixed AdminProductsControllerCore::initPack(\Product $product)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminProductsController.php line 4966


#### Arguments
* $product **[Product](ProductCore)**



### initFormModules

    mixed AdminProductsControllerCore::initFormModules($obj)

AdminProducts display hook



* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 4999


#### Arguments
* $obj **mixed**



### updatePackItems

    boolean AdminProductsControllerCore::updatePackItems(\Product $product)

delete all items in pack, then check if type_product value is 2.

if yes, add the pack items from input "inputPackItems"

* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 5012


#### Arguments
* $product **[Product](ProductCore)**



### getL

    mixed AdminProductsControllerCore::getL($key)





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 5040


#### Arguments
* $key **mixed**



### _displayUnavailableProductWarning

    mixed AdminProductsControllerCore::_displayUnavailableProductWarning()





* Visibility: **protected**
* This method is defined in controllers\admin\AdminProductsController.php line 5053




### ajaxProcessCheckProductName

    mixed AdminProductsControllerCore::ajaxProcessCheckProductName()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 5063




### ajaxProcessUpdatePositions

    mixed AdminProductsControllerCore::ajaxProcessUpdatePositions()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 5086




### ajaxProcessPublishProduct

    mixed AdminProductsControllerCore::ajaxProcessPublishProduct()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 5126




### processImageLegends

    mixed AdminProductsControllerCore::processImageLegends()





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 5152




### displayPreviewLink

    mixed AdminProductsControllerCore::displayPreviewLink($token, $id, $name)





* Visibility: **public**
* This method is defined in controllers\admin\AdminProductsController.php line 5169


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**


