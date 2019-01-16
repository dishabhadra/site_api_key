CONTENTS OF THIS FILE
---------------------

* Introduction
* Requirements
* Installation
* Configuration
* Maintainer
* References
* Total time

Introduction
------------

* The Site API Key module adds a new textfield called "Site API Key"
in "Site Information" form which can be found at the path 
"/admin/config/system/site-information".
* This module also provides a URL that responds with a JSON representation of a 
given node of "page" content type, Provided the correct "Site API Key" is 
entered in the URL.

Example URL : http://example.com/page_json/{Site API Key}/{Node ID}
 
Requirements
------------

This module requires the following module:
* System (Provided by Drupal core)

Installation
------------

* Login as an Administrator.
* Go to /admin/modules.
* Find the module called "Site API Key".
* Check the checkbox against this module.
* Click Install button from the bottom of the page.

Configuration
-------------

* Configure your "Site API Key" in the Site Information form located at 
"/admin/config/system/site-information".
 
Maintainer
-----------

* Disha Bhadra (dishabhadra) - https://github.com/dishabhadra

References
----------

* For adding new form field to existing admin config form, I referred
https://drupal.stackexchange.com/questions/245990/add-config-forms-to-existing-admin-page
* For adding parameters in routes, I referred
https://www.drupal.org/docs/8/api/routing-system/using-parameters-in-routes

Total time
----------

I took around 5 hours to build this module.
