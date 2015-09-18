AdminProductsControllerCore
===============






* Class name: AdminProductsControllerCore
* Namespace: 
* Parent class: AdminController





Properties
----------


### $max_file_size

    protected integer $max_file_size = null





* Visibility: **protected**


### $max_image_size

    protected mixed $max_image_size = null





* Visibility: **protected**


### $_category

    protected mixed $_category





* Visibility: **protected**


### $tab_display

    protected string $tab_display





* Visibility: **protected**


### $tab_display_module

    protected mixed $tab_display_module





* Visibility: **protected**


### $available_tabs

    protected array $available_tabs = array()

The order in the array decides the order in the list of tab. If an element's value is a number, it will be preloaded.

The tabs are preloaded from the smallest to the highest number.

* Visibility: **protected**


### $default_tab

    protected mixed $default_tab = 'Informations'





* Visibility: **protected**


### $available_tabs_lang

    protected mixed $available_tabs_lang = array()





* Visibility: **protected**


### $position_identifier

    protected mixed $position_identifier = 'id_product'





* Visibility: **protected**


### $submitted_tabs

    protected mixed $submitted_tabs





* Visibility: **protected**


### $id_current_category

    protected mixed $id_current_category





* Visibility: **protected**


### $object

    public \Product $object





* Visibility: **public**


Methods
-------


### __construct

    mixed AdminProductsControllerCore::__construct()





* Visibility: **public**




### getQuantities

    mixed AdminProductsControllerCore::getQuantities($echo, $tr)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $echo **mixed**
* $tr **mixed**



### setMedia

    mixed AdminProductsControllerCore::setMedia()





* Visibility: **public**




### _cleanMetaKeywords

    mixed AdminProductsControllerCore::_cleanMetaKeywords($keywords)





* Visibility: **protected**


#### Arguments
* $keywords **mixed**



### copyFromPost

    mixed AdminProductsControllerCore::copyFromPost(\Product|\ObjectModel $object, string $table)





* Visibility: **protected**


#### Arguments
* $object **Product|ObjectModel**
* $table **string**



### checkMultishopBox

    mixed AdminProductsControllerCore::checkMultishopBox($field, $context)





* Visibility: **public**


#### Arguments
* $field **mixed**
* $context **mixed**



### getList

    mixed AdminProductsControllerCore::getList($id_lang, $orderBy, $orderWay, $start, $limit, $id_lang_shop)





* Visibility: **public**


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


#### Arguments
* $opt **mixed**



### ajaxProcessGetCategoryTree

    mixed AdminProductsControllerCore::ajaxProcessGetCategoryTree()





* Visibility: **public**




### ajaxProcessGetCountriesOptions

    mixed AdminProductsControllerCore::ajaxProcessGetCountriesOptions()





* Visibility: **public**




### ajaxProcessGetCurrenciesOptions

    mixed AdminProductsControllerCore::ajaxProcessGetCurrenciesOptions()





* Visibility: **public**




### ajaxProcessGetGroupsOptions

    mixed AdminProductsControllerCore::ajaxProcessGetGroupsOptions()





* Visibility: **public**




### processDeleteVirtualProduct

    mixed AdminProductsControllerCore::processDeleteVirtualProduct()





* Visibility: **public**




### ajaxProcessAddAttachment

    mixed AdminProductsControllerCore::ajaxProcessAddAttachment()





* Visibility: **public**




### processAttachments

    void AdminProductsControllerCore::processAttachments()

Attach an existing attachment to the product



* Visibility: **public**




### processDuplicate

    mixed AdminProductsControllerCore::processDuplicate()





* Visibility: **public**




### processDelete

    mixed AdminProductsControllerCore::processDelete()





* Visibility: **public**




### processImage

    mixed AdminProductsControllerCore::processImage()





* Visibility: **public**




### processBulkDelete

    mixed AdminProductsControllerCore::processBulkDelete()





* Visibility: **protected**




### processProductAttribute

    mixed AdminProductsControllerCore::processProductAttribute()





* Visibility: **public**




### processFeatures

    mixed AdminProductsControllerCore::processFeatures()





* Visibility: **public**




### processPricesModification

    mixed AdminProductsControllerCore::processPricesModification()

This function is never called at the moment (specific prices cannot be edited)



* Visibility: **public**




### processPriceAddition

    mixed AdminProductsControllerCore::processPriceAddition()





* Visibility: **public**




### ajaxProcessDeleteSpecificPrice

    mixed AdminProductsControllerCore::ajaxProcessDeleteSpecificPrice()





* Visibility: **public**




### processSpecificPricePriorities

    mixed AdminProductsControllerCore::processSpecificPricePriorities()





* Visibility: **public**




### processCustomizationConfiguration

    mixed AdminProductsControllerCore::processCustomizationConfiguration()





* Visibility: **public**




### processProductCustomization

    mixed AdminProductsControllerCore::processProductCustomization()





* Visibility: **public**




### processPosition

    mixed AdminProductsControllerCore::processPosition()

Overrides parent for custom redirect link



* Visibility: **public**




### initProcess

    mixed AdminProductsControllerCore::initProcess()





* Visibility: **public**




### postProcess

    void AdminProductsControllerCore::postProcess()

postProcess handle every checks before saving products information



* Visibility: **public**




### ajaxProcessDeleteProductAttribute

    mixed AdminProductsControllerCore::ajaxProcessDeleteProductAttribute()





* Visibility: **public**




### ajaxProcessDefaultProductAttribute

    mixed AdminProductsControllerCore::ajaxProcessDefaultProductAttribute()





* Visibility: **public**




### ajaxProcessEditProductAttribute

    mixed AdminProductsControllerCore::ajaxProcessEditProductAttribute()





* Visibility: **public**




### ajaxPreProcess

    mixed AdminProductsControllerCore::ajaxPreProcess()





* Visibility: **public**




### ajaxProcessUpdateProductImageShopAsso

    mixed AdminProductsControllerCore::ajaxProcessUpdateProductImageShopAsso()





* Visibility: **public**




### ajaxProcessUpdateImagePosition

    mixed AdminProductsControllerCore::ajaxProcessUpdateImagePosition()





* Visibility: **public**




### ajaxProcessUpdateCover

    mixed AdminProductsControllerCore::ajaxProcessUpdateCover()





* Visibility: **public**




### ajaxProcessDeleteProductImage

    mixed AdminProductsControllerCore::ajaxProcessDeleteProductImage()





* Visibility: **public**




### _validateSpecificPrice

    mixed AdminProductsControllerCore::_validateSpecificPrice($id_shop, $id_currency, $id_country, $id_group, $id_customer, $price, $from_quantity, $reduction, $reduction_type, $from, $to, $id_combination)





* Visibility: **protected**


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


#### Arguments
* $languages **mixed**
* $feature_id **mixed**



### addProductImage

    integer|false AdminProductsControllerCore::addProductImage(\Product $product, string $method)

Add or update a product image



* Visibility: **public**


#### Arguments
* $product **Product** - &lt;p&gt;Product object to add image&lt;/p&gt;
* $method **string**



### copyImage

    void|false AdminProductsControllerCore::copyImage(integer $id_product, integer $id_image, string $method)

Copy a product image



* Visibility: **public**


#### Arguments
* $id_product **integer** - &lt;p&gt;Product Id for product image filename&lt;/p&gt;
* $id_image **integer** - &lt;p&gt;Image Id for product image filename&lt;/p&gt;
* $method **string**



### updateAssoShop

    mixed AdminProductsControllerCore::updateAssoShop($id_object)





* Visibility: **protected**


#### Arguments
* $id_object **mixed**



### processAdd

    mixed AdminProductsControllerCore::processAdd()





* Visibility: **public**




### isTabSubmitted

    mixed AdminProductsControllerCore::isTabSubmitted($tab_name)





* Visibility: **protected**


#### Arguments
* $tab_name **mixed**



### processStatus

    mixed AdminProductsControllerCore::processStatus()





* Visibility: **public**




### processUpdate

    mixed AdminProductsControllerCore::processUpdate()





* Visibility: **public**




### checkProduct

    mixed AdminProductsControllerCore::checkProduct()

Check that a saved product is valid



* Visibility: **public**




### isProductFieldUpdated

    boolean AdminProductsControllerCore::isProductFieldUpdated(string $field, integer $id_lang)

Check if a field is edited (if the checkbox is checked)
This method will do something only for multishop with a context all / group



* Visibility: **protected**


#### Arguments
* $field **string** - &lt;p&gt;Name of field&lt;/p&gt;
* $id_lang **integer**



### _removeTaxFromEcotax

    mixed AdminProductsControllerCore::_removeTaxFromEcotax()





* Visibility: **protected**




### _applyTaxToEcotax

    mixed AdminProductsControllerCore::_applyTaxToEcotax($product)





* Visibility: **protected**


#### Arguments
* $product **mixed**



### updateDownloadProduct

    boolean AdminProductsControllerCore::updateDownloadProduct(\Product $product, integer $edit)

Update product download



* Visibility: **public**


#### Arguments
* $product **Product**
* $edit **integer**



### updateAccessories

    mixed AdminProductsControllerCore::updateAccessories(object $product)

Update product accessories



* Visibility: **public**


#### Arguments
* $product **object** - &lt;p&gt;Product&lt;/p&gt;



### updateTags

    boolean AdminProductsControllerCore::updateTags(array $languages, object $product)

Update product tags



* Visibility: **public**


#### Arguments
* $languages **array** - &lt;p&gt;Array languages&lt;/p&gt;
* $product **object** - &lt;p&gt;Product&lt;/p&gt;



### initContent

    mixed AdminProductsControllerCore::initContent($token)





* Visibility: **public**


#### Arguments
* $token **mixed**



### renderKpis

    mixed AdminProductsControllerCore::renderKpis()





* Visibility: **public**




### renderList

    mixed AdminProductsControllerCore::renderList()





* Visibility: **public**




### ajaxProcessProductManufacturers

    mixed AdminProductsControllerCore::ajaxProcessProductManufacturers()





* Visibility: **public**




### recurseCategoryForInclude

    string AdminProductsControllerCore::recurseCategoryForInclude($id_obj, array $indexedCategories, array $categories, $current, null $id_category, null $id_category_default, array $has_suite)

Build a categories tree



* Visibility: **public**
* This method is **static**.


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


#### Arguments
* $active **mixed**



### initPageHeaderToolbar

    mixed AdminProductsControllerCore::initPageHeaderToolbar()





* Visibility: **public**




### initToolbar

    mixed AdminProductsControllerCore::initToolbar()





* Visibility: **public**




### renderForm

    string|void AdminProductsControllerCore::renderForm()

renderForm contains all necessary initialization needed for all tabs



* Visibility: **public**




### getPreviewUrl

    mixed AdminProductsControllerCore::getPreviewUrl(\Product $product)





* Visibility: **public**


#### Arguments
* $product **Product**



### processSuppliers

    mixed AdminProductsControllerCore::processSuppliers()

Post treatment for suppliers



* Visibility: **public**




### processWarehouses

    mixed AdminProductsControllerCore::processWarehouses()

Post treatment for warehouses



* Visibility: **public**




### initFormAssociations

    mixed AdminProductsControllerCore::initFormAssociations(\Product $obj)





* Visibility: **public**


#### Arguments
* $obj **Product**



### initFormPrices

    mixed AdminProductsControllerCore::initFormPrices(\Product $obj)





* Visibility: **public**


#### Arguments
* $obj **Product**



### initFormSeo

    mixed AdminProductsControllerCore::initFormSeo($product)





* Visibility: **public**


#### Arguments
* $product **mixed**



### getPackItems

    array AdminProductsControllerCore::getPackItems(\Product $product)

Get an array of pack items for display from the product object if specified, else from POST/GET values



* Visibility: **public**


#### Arguments
* $product **Product**



### initFormPack

    mixed AdminProductsControllerCore::initFormPack(\Product $product)





* Visibility: **public**


#### Arguments
* $product **Product**



### initFormVirtualProduct

    mixed AdminProductsControllerCore::initFormVirtualProduct($product)





* Visibility: **public**


#### Arguments
* $product **mixed**



### _getFinalPrice

    mixed AdminProductsControllerCore::_getFinalPrice($specific_price, $product_price, $tax_rate)





* Visibility: **protected**


#### Arguments
* $specific_price **mixed**
* $product_price **mixed**
* $tax_rate **mixed**



### _displaySpecificPriceModificationForm

    mixed AdminProductsControllerCore::_displaySpecificPriceModificationForm($defaultCurrency, $shops, $currencies, $countries, $groups)





* Visibility: **protected**


#### Arguments
* $defaultCurrency **mixed**
* $shops **mixed**
* $currencies **mixed**
* $countries **mixed**
* $groups **mixed**



### _getCustomizationFieldIds

    mixed AdminProductsControllerCore::_getCustomizationFieldIds($labels, $alreadyGenerated, $obj)





* Visibility: **protected**


#### Arguments
* $labels **mixed**
* $alreadyGenerated **mixed**
* $obj **mixed**



### _displayLabelField

    mixed AdminProductsControllerCore::_displayLabelField($label, $languages, $default_language, $type, $fieldIds, $id_customization_field)





* Visibility: **protected**


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


#### Arguments
* $obj **mixed**
* $labels **mixed**
* $languages **mixed**
* $default_language **mixed**
* $type **mixed**



### initFormCustomization

    mixed AdminProductsControllerCore::initFormCustomization(\Product $obj)





* Visibility: **public**


#### Arguments
* $obj **Product**



### initFormAttachments

    mixed AdminProductsControllerCore::initFormAttachments($obj)





* Visibility: **public**


#### Arguments
* $obj **mixed**



### initFormInformations

    mixed AdminProductsControllerCore::initFormInformations(\Product $product)





* Visibility: **public**


#### Arguments
* $product **Product**



### initFormShipping

    mixed AdminProductsControllerCore::initFormShipping($obj)





* Visibility: **public**


#### Arguments
* $obj **mixed**



### getCarrierList

    mixed AdminProductsControllerCore::getCarrierList()





* Visibility: **protected**




### addCarriers

    mixed AdminProductsControllerCore::addCarriers($product)





* Visibility: **protected**


#### Arguments
* $product **mixed**



### ajaxProcessaddProductImage

    mixed AdminProductsControllerCore::ajaxProcessaddProductImage()





* Visibility: **public**




### initFormImages

    mixed AdminProductsControllerCore::initFormImages(\Product $obj)





* Visibility: **public**


#### Arguments
* $obj **Product**



### initFormCombinations

    mixed AdminProductsControllerCore::initFormCombinations($obj)





* Visibility: **public**


#### Arguments
* $obj **mixed**



### initFormAttributes

    mixed AdminProductsControllerCore::initFormAttributes(\Product $product)





* Visibility: **public**


#### Arguments
* $product **Product**



### renderListAttributes

    string AdminProductsControllerCore::renderListAttributes(\Product $product, \Currency|array|integer $currency)





* Visibility: **public**


#### Arguments
* $product **Product**
* $currency **Currency|array|integer**



### initFormQuantities

    mixed AdminProductsControllerCore::initFormQuantities(\Product $obj)





* Visibility: **public**


#### Arguments
* $obj **Product**



### initFormSuppliers

    mixed AdminProductsControllerCore::initFormSuppliers(\Product $obj)





* Visibility: **public**


#### Arguments
* $obj **Product**



### initFormWarehouses

    mixed AdminProductsControllerCore::initFormWarehouses(\Product $obj)





* Visibility: **public**


#### Arguments
* $obj **Product**



### initFormFeatures

    mixed AdminProductsControllerCore::initFormFeatures(\Product $obj)





* Visibility: **public**


#### Arguments
* $obj **Product**



### ajaxProcessProductQuantity

    mixed AdminProductsControllerCore::ajaxProcessProductQuantity()





* Visibility: **public**




### getCombinationImagesJS

    mixed AdminProductsControllerCore::getCombinationImagesJS()





* Visibility: **public**




### haveThisAccessory

    mixed AdminProductsControllerCore::haveThisAccessory($accessory_id, $accessories)





* Visibility: **public**


#### Arguments
* $accessory_id **mixed**
* $accessories **mixed**



### initPack

    mixed AdminProductsControllerCore::initPack(\Product $product)





* Visibility: **protected**


#### Arguments
* $product **Product**



### initFormModules

    mixed AdminProductsControllerCore::initFormModules($obj)

AdminProducts display hook



* Visibility: **public**


#### Arguments
* $obj **mixed**



### updatePackItems

    boolean AdminProductsControllerCore::updatePackItems(\Product $product)

delete all items in pack, then check if type_product value is 2.

if yes, add the pack items from input "inputPackItems"

* Visibility: **public**


#### Arguments
* $product **Product**



### getL

    mixed AdminProductsControllerCore::getL($key)





* Visibility: **public**


#### Arguments
* $key **mixed**



### _displayUnavailableProductWarning

    mixed AdminProductsControllerCore::_displayUnavailableProductWarning()





* Visibility: **protected**




### ajaxProcessCheckProductName

    mixed AdminProductsControllerCore::ajaxProcessCheckProductName()





* Visibility: **public**




### ajaxProcessUpdatePositions

    mixed AdminProductsControllerCore::ajaxProcessUpdatePositions()





* Visibility: **public**




### ajaxProcessPublishProduct

    mixed AdminProductsControllerCore::ajaxProcessPublishProduct()





* Visibility: **public**




### processImageLegends

    mixed AdminProductsControllerCore::processImageLegends()





* Visibility: **public**




### displayPreviewLink

    mixed AdminProductsControllerCore::displayPreviewLink($token, $id, $name)





* Visibility: **public**


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**


