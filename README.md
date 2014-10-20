form_rules
==========

This module enables the calculation for a destination field based on some other param fields.

================

Configurations:
================

```
$conf['checking_form_number'] = 'number of the forms you want the calculation happen'
$conf['calculation_form_id_x'] = 'webform_client_form_xxxx';
$conf['base_field_key_1_x'] = 'xxxx';
$conf['base_field_key_2_x'] = 'xxxx';
$conf['multiplier_field_key_1_x'] = 'xxxx';
$conf['multiplier_field_key_2_x'] = 'xxxx';
$conf['destination_field_key_x'] = 'xxxx';

...

$conf['calculation_form_id_(x+1)'] = 'webform_client_form_xxxx';
$conf['base_field_key_1_(x+1)'] = 'xxxx';
$conf['base_field_key_2_(x+1)'] = 'xxxx';
$conf['multiplier_field_key_1_(x+1)'] = 'xxxx';
$conf['multiplier_field_key_2_(x+1)'] = 'xxxx';
$conf['destination_field_key_(x+1)'] = 'xxxx';

```
================
Please notice that same fields in a webform should not be used more than once.
