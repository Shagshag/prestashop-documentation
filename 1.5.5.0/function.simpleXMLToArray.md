Function simpleXMLToArray
===========================

Converts a simpleXML element into an array. Preserves attributes and everything.

You can choose to get your elements either flattened, or stored in a custom index that
you define.
For example, for a given element
<field name="someName" type="someType"/>
if you choose to flatten attributes, you would get:
$array['field']['name'] = 'someName';
$array['field']['type'] = 'someType';
If you choose not to flatten, you get:
$array['field']['@attributes']['name'] = 'someName';
_____________________________________
Repeating fields are stored in indexed arrays. so for a markup such as:
<parent>
<child>a</child>
<child>b</child>
<child>c</child>
</parent>
you array would be:
$array['parent']['child'][0] = 'a';
$array['parent']['child'][1] = 'b';
...And so on.
_____________________________________

```php
array simpleXMLToArray(\simpleXMLElement $xml, boolean $flattenValues, boolean $flattenAttributes, boolean $flattenChildren, string $valueKey, string $attributesKey, string $childrenKey)
```

* Function name: simpleXMLToArray
* Source: [admin-dev/functions.php line 339](https://github.com/PrestaShop/PrestaShop/blob/1.5.5.0/admin-dev/functions.php#L339).

Arguments
---------

* $xml **simpleXMLElement** - the XML to convert
* $flattenValues **boolean** - Choose wether to flatten values
                                   or to set them under a particular index.
                                   defaults to true;
* $flattenAttributes **boolean** - Choose wether to flatten attributes
                                   or to set them under a particular index.
                                   Defaults to true;
* $flattenChildren **boolean** - Choose wether to flatten children
                                   or to set them under a particular index.
                                   Defaults to true;
* $valueKey **string** - index for values, in case $flattenValues was set to
                       false. Defaults to &quot;@value&quot;
* $attributesKey **string** - index for attributes, in case $flattenAttributes was set to
                       false. Defaults to &quot;@attributes&quot;
* $childrenKey **string** - index for children, in case $flattenChildren was set to
                       false. Defaults to &quot;@children&quot;

