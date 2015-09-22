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

    array simpleXMLToArray(\simpleXMLElement $xml, boolean $flatten_values, boolean $flatten_attributes, boolean $flatten_children, string $value_key, string $attributes_key, string $children_key)

* Function name: simpleXMLToArray
* Source: [admin-dev/functions.php line 343](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/admin-dev/functions.php#L343)

#### Arguments
* $xml **simpleXMLElement** - the XML to convert
* $flatten_values **boolean** - Choose wether to flatten values
                                   or to set them under a particular index.
                                   defaults to true;
* $flatten_attributes **boolean** - Choose wether to flatten attributes
                                   or to set them under a particular index.
                                   Defaults to true;
* $flatten_children **boolean** - Choose wether to flatten children
                                   or to set them under a particular index.
                                   Defaults to true;
* $value_key **string** - index for values, in case $flatten_values was set to false. Defaults to &quot;@value&quot;
* $attributes_key **string** - index for attributes, in case $flatten_attributes was set to false. Defaults to &quot;@attributes&quot;
* $children_key **string** - index for children, in case $flatten_children was set to false. Defaults to &quot;@children&quot;

