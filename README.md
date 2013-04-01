Pyro Custom Field Type
======================

PyroCMS field type to store multiple key-value data.

Features
--------
* Store multiple key value pairs
* Drag and drop sorting
* Add and remove items quickly

Installation
------------
* Just create a new folder 'keyvalue' in field_types and copy all content there.

How to Use
----------
You can use key and value within your field as:

``` html
<ul>
{{ your_field_slug }}
<li>{{ key }} : {{ value }}</li>
{{ /your_field_slug }}
</ul>
```

Copyright
---------

* Copyright (c) 2013 Faheem Akhtar <faheempiscean@gmail.com>
* Distributed under the GNU General Public License version 2 or later
