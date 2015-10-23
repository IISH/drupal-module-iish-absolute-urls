# drupal-module-iish-absolute-urls

If a form action is not explicitly set the REQUEST_URI global wil be used.
This should lead to the same page the form is on.
If however the site is behind a proxy, and the $base_url contains a subdirectory, this may fail.
This module corrects this by adding the $base_url.

