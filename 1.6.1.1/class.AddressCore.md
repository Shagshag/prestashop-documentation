Class AddressCore
=====================

2007-2015 PrestaShop

NOTICE OF LICENSE

This source file is subject to the Open Software License (OSL 3.0)
that is bundled with this package in the file LICENSE.txt.
It is also available through the world-wide-web at this URL:
http://opensource.org/licenses/osl-3.0.php
If you did not receive a copy of the license and are unable to
obtain it through the world-wide-web, please send an email
to license@prestashop.com so we can send you a copy immediately.

DISCLAIMER

Do not edit or add to this file if you wish to upgrade PrestaShop to newer
versions in the future. If you wish to customize PrestaShop for your
needs please refer to http://www.prestashop.com for more information.

* Class name: AddressCore
* Parent class: [ObjectModel](class.ObjectModelCore)
* Source: [classes/Address.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L27)



Properties
----------

* [$_idCountries](#property-$_idCountries)
* [$_idZones](#property-$_idZones)
* [$_includeContainer](#property-$_includeContainer)
* [$_includeVars](#property-$_includeVars)
* [$address1](#property-$address1)
* [$address2](#property-$address2)
* [$alias](#property-$alias)
* [$city](#property-$city)
* [$company](#property-$company)
* [$country](#property-$country)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$deleted](#property-$deleted)
* [$dni](#property-$dni)
* [$firstname](#property-$firstname)
* [$id_country](#property-$id_country)
* [$id_customer](#property-$id_customer)
* [$id_manufacturer](#property-$id_manufacturer)
* [$id_state](#property-$id_state)
* [$id_supplier](#property-$id_supplier)
* [$id_warehouse](#property-$id_warehouse)
* [$lastname](#property-$lastname)
* [$other](#property-$other)
* [$phone](#property-$phone)
* [$phone_mobile](#property-$phone_mobile)
* [$postcode](#property-$postcode)
* [$vat_number](#property-$vat_number)
* [$webserviceParameters](#property-$webserviceParameters)

Methods
-------
* [__construct](#method-__construct)
* [add](#method-add)
* [addressExists](#method-addressExists)
* [aliasExist](#method-aliasExist)
* [delete](#method-delete)
* [getAddressIdBySupplierId](#method-getAddressIdBySupplierId)
* [getCountryAndState](#method-getCountryAndState)
* [getFieldsRequiredDB](#method-getFieldsRequiredDB)
* [getFieldsValidate](#method-getFieldsValidate)
* [getFirstCustomerAddressId](#method-getFirstCustomerAddressId)
* [getZoneById](#method-getZoneById)
* [initialize](#method-initialize)
* [isCountryActiveById](#method-isCountryActiveById)
* [isUsed](#method-isUsed)
* [update](#method-update)
* [validateController](#method-validateController)




Properties
----------


### <a name="property-$_idCountries"></a>$_idCountries

    protected mixed $_idCountries = array()





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Address.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L102)


### <a name="property-$_idZones"></a>$_idZones

    protected mixed $_idZones = array()





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Address.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L101)


### <a name="property-$_includeContainer"></a>$_includeContainer

    protected mixed $_includeContainer = false





* Visibility: **protected**
* Source: [classes/Address.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L137)


### <a name="property-$_includeVars"></a>$_includeVars

    protected mixed $_includeVars = array('addressType' => 'table')





* Visibility: **protected**
* Source: [classes/Address.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L136)


### <a name="property-$address1"></a>$address1

    public string $address1





* Visibility: **public**
* Source: [classes/Address.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L66)


### <a name="property-$address2"></a>$address2

    public string $address2





* Visibility: **public**
* Source: [classes/Address.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L69)


### <a name="property-$alias"></a>$alias

    public string $alias





* Visibility: **public**
* Source: [classes/Address.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L54)


### <a name="property-$city"></a>$city

    public string $city





* Visibility: **public**
* Source: [classes/Address.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L75)


### <a name="property-$company"></a>$company

    public string $company





* Visibility: **public**
* Source: [classes/Address.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L57)


### <a name="property-$country"></a>$country

    public string $country





* Visibility: **public**
* Source: [classes/Address.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L51)


### <a name="property-$date_add"></a>$date_add

    public string $date_add





* Visibility: **public**
* Source: [classes/Address.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L93)


### <a name="property-$date_upd"></a>$date_upd

    public string $date_upd





* Visibility: **public**
* Source: [classes/Address.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L96)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'address', 'primary' => 'id_address', 'fields' => array('id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isNullOrUnsignedId', 'copy_post' => false), 'id_manufacturer' => array('type' => self::TYPE_INT, 'validate' => 'isNullOrUnsignedId', 'copy_post' => false), 'id_supplier' => array('type' => self::TYPE_INT, 'validate' => 'isNullOrUnsignedId', 'copy_post' => false), 'id_warehouse' => array('type' => self::TYPE_INT, 'validate' => 'isNullOrUnsignedId', 'copy_post' => false), 'id_country' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_state' => array('type' => self::TYPE_INT, 'validate' => 'isNullOrUnsignedId'), 'alias' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 32), 'company' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 64), 'lastname' => array('type' => self::TYPE_STRING, 'validate' => 'isName', 'required' => true, 'size' => 32), 'firstname' => array('type' => self::TYPE_STRING, 'validate' => 'isName', 'required' => true, 'size' => 32), 'vat_number' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName'), 'address1' => array('type' => self::TYPE_STRING, 'validate' => 'isAddress', 'required' => true, 'size' => 128), 'address2' => array('type' => self::TYPE_STRING, 'validate' => 'isAddress', 'size' => 128), 'postcode' => array('type' => self::TYPE_STRING, 'validate' => 'isPostCode', 'size' => 12), 'city' => array('type' => self::TYPE_STRING, 'validate' => 'isCityName', 'required' => true, 'size' => 64), 'other' => array('type' => self::TYPE_STRING, 'validate' => 'isMessage', 'size' => 300), 'phone' => array('type' => self::TYPE_STRING, 'validate' => 'isPhoneNumber', 'size' => 32), 'phone_mobile' => array('type' => self::TYPE_STRING, 'validate' => 'isPhoneNumber', 'size' => 32), 'dni' => array('type' => self::TYPE_STRING, 'validate' => 'isDniLite', 'size' => 16), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'copy_post' => false), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'copy_post' => false), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'copy_post' => false)))





* Visibility: **public**
* This property is **static**.
* Source: [classes/Address.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L107)


### <a name="property-$deleted"></a>$deleted

    public boolean $deleted





* Visibility: **public**
* Source: [classes/Address.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L99)


### <a name="property-$dni"></a>$dni

    public string $dni





* Visibility: **public**
* Source: [classes/Address.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L90)


### <a name="property-$firstname"></a>$firstname

    public string $firstname





* Visibility: **public**
* Source: [classes/Address.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L63)


### <a name="property-$id_country"></a>$id_country

    public integer $id_country





* Visibility: **public**
* Source: [classes/Address.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L45)


### <a name="property-$id_customer"></a>$id_customer

    public integer $id_customer = null





* Visibility: **public**
* Source: [classes/Address.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L30)


### <a name="property-$id_manufacturer"></a>$id_manufacturer

    public integer $id_manufacturer = null





* Visibility: **public**
* Source: [classes/Address.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L33)


### <a name="property-$id_state"></a>$id_state

    public integer $id_state





* Visibility: **public**
* Source: [classes/Address.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L48)


### <a name="property-$id_supplier"></a>$id_supplier

    public integer $id_supplier = null





* Visibility: **public**
* Source: [classes/Address.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L36)


### <a name="property-$id_warehouse"></a>$id_warehouse

    public integer $id_warehouse = null





* Visibility: **public**
* Source: [classes/Address.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L42)


### <a name="property-$lastname"></a>$lastname

    public string $lastname





* Visibility: **public**
* Source: [classes/Address.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L60)


### <a name="property-$other"></a>$other

    public string $other





* Visibility: **public**
* Source: [classes/Address.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L78)


### <a name="property-$phone"></a>$phone

    public string $phone





* Visibility: **public**
* Source: [classes/Address.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L81)


### <a name="property-$phone_mobile"></a>$phone_mobile

    public string $phone_mobile





* Visibility: **public**
* Source: [classes/Address.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L84)


### <a name="property-$postcode"></a>$postcode

    public string $postcode





* Visibility: **public**
* Source: [classes/Address.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L72)


### <a name="property-$vat_number"></a>$vat_number

    public string $vat_number





* Visibility: **public**
* Source: [classes/Address.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L87)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'addresses', 'fields' => array('id_customer' => array('xlink_resource' => 'customers'), 'id_manufacturer' => array('xlink_resource' => 'manufacturers'), 'id_supplier' => array('xlink_resource' => 'suppliers'), 'id_warehouse' => array('xlink_resource' => 'warehouse'), 'id_country' => array('xlink_resource' => 'countries'), 'id_state' => array('xlink_resource' => 'states')))





* Visibility: **protected**
* Source: [classes/Address.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L139)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AddressCore::__construct(integer $id_address, $id_lang)

Build an address



* Visibility: **public**
* Source: [classes/Address.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L156)


#### Arguments
* $id_address **integer** - Existing address id in order to load object (optional)
* $id_lang **mixed**



### <a name="method-add"></a>add

    mixed AddressCore::add($autodate, $null_values)





* Visibility: **public**
* Source: [classes/Address.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L169)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addressExists"></a>addressExists

    boolean AddressCore::addressExists(integer $id_address)

Specify if an address is already in base



* Visibility: **public**
* This method is **static**.
* Source: [classes/Address.php line 340](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L340)


#### Arguments
* $id_address **integer** - Address id



### <a name="method-aliasExist"></a>aliasExist

    mixed AddressCore::aliasExist($alias, $id_address, $id_customer)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Address.php line 441](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L441)


#### Arguments
* $alias **mixed**
* $id_address **mixed**
* $id_customer **mixed**



### <a name="method-delete"></a>delete

    mixed AddressCore::delete()





* Visibility: **public**
* Source: [classes/Address.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L201)




### <a name="method-getAddressIdBySupplierId"></a>getAddressIdBySupplierId

    integer AddressCore::getAddressIdBySupplierId(integer $id_supplier)

Returns id_address for a given id_supplier



* Visibility: **public**
* This method is **static**.
* Source: [classes/Address.php line 428](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L428)


#### Arguments
* $id_supplier **integer**



### <a name="method-getCountryAndState"></a>getCountryAndState

    mixed AddressCore::getCountryAndState($id_address)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Address.php line 318](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L318)


#### Arguments
* $id_address **mixed**



### <a name="method-getFieldsRequiredDB"></a>getFieldsRequiredDB

    mixed AddressCore::getFieldsRequiredDB()





* Visibility: **public**
* Source: [classes/Address.php line 454](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L454)




### <a name="method-getFieldsValidate"></a>getFieldsValidate

    array AddressCore::getFieldsValidate()

Returns fields required for an address in an array hash



* Visibility: **public**
* This method is **static**.
* Source: [classes/Address.php line 219](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L219)




### <a name="method-getFirstCustomerAddressId"></a>getFirstCustomerAddressId

    mixed AddressCore::getFirstCustomerAddressId($id_customer, $active)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Address.php line 351](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L351)


#### Arguments
* $id_customer **mixed**
* $active **mixed**



### <a name="method-getZoneById"></a>getZoneById

    integer AddressCore::getZoneById(integer $id_address)

Get zone id for a given address



* Visibility: **public**
* This method is **static**.
* Source: [classes/Address.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L249)


#### Arguments
* $id_address **integer** - Address id for which we want to get zone id



### <a name="method-initialize"></a>initialize

    \Address AddressCore::initialize(integer $id_address, boolean $with_geoloc)

Initiliaze an address corresponding to the specified id address or if empty to the
default shop configuration



* Visibility: **public**
* This method is **static**.
* Source: [classes/Address.php line 379](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L379)


#### Arguments
* $id_address **integer**
* $with_geoloc **boolean**



### <a name="method-isCountryActiveById"></a>isCountryActiveById

    integer AddressCore::isCountryActiveById(integer $id_address)

Check if country is active for a given address



* Visibility: **public**
* This method is **static**.
* Source: [classes/Address.php line 283](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L283)


#### Arguments
* $id_address **integer** - Address id for which we want to get country status



### <a name="method-isUsed"></a>isUsed

    integer AddressCore::isUsed()

Check if address is used (at least one order placed)



* Visibility: **public**
* Source: [classes/Address.php line 307](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L307)




### <a name="method-update"></a>update

    mixed AddressCore::update($null_values)





* Visibility: **public**
* Source: [classes/Address.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L181)


#### Arguments
* $null_values **mixed**



### <a name="method-validateController"></a>validateController

    mixed AddressCore::validateController($htmlentities)





* Visibility: **public**
* Source: [classes/Address.php line 231](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Address.php#L231)


#### Arguments
* $htmlentities **mixed**


