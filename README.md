# Doc settings

This module is an alternative to using iframes for dispaying external documentation.

# Install

Place this module in drupal/modules/custom/ 

It should look like the drupal/modules/custom/doc_page

Activate the module on the "extend" page. (/admin/modules)

#Use

Go to the permission page and add the permission: "Administer documentation page" to the role that should have access. This is not needed if you are user 1.

Navigate to /admin/config/content/doc and enter the url for the documentation page source. This for is also linked from the Configuration page.

Documentation should no be shown on: /doc 

Create an url alias if you want a different url for this page.

