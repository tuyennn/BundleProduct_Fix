# GhoSter Bundle Product Fix - Magento 1
---
On Admin-End while admin edit a bundle product, child products will be limit at ~200 and cannot be added more.
The problem came from child product ids were added to url and server cannot handle it as to many parameters exist on url request.
The fix was simply convert the product ids from url to put them into ajax object as a parameter, so we're no longer afraid of the url length.

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.me/thinghost)
![Version 1.0.0](https://img.shields.io/badge/Version-1.0.0-green.svg)

Facts
-----
- version: 1.0.0
- extension key: GhoSter_BundleProduct
- [extension on GitHub](https://github.com/tuyennn/BundleProduct_Fix)
- [direct download link](https://github.com/tuyennn/BundleProduct_Fix/tarball/master)

Description
-----------
On Admin-End while admin edit a bundle product, child products will be limit at ~200 and cannot be added more.
The problem came from child product ids were added to url and server cannot handle it as to many parameters exist on url request.
The fix was simply convert the product ids from url to put them into ajax object as a parameter, so we're no longer afraid of the url length.

Requirements
------------
- PHP >= 5.2.0
- Mage_Core

Compatibility
-------------
- Magento CE >= 1.4

Installation Instructions
-------------------------
1. Clone the module and copy into your document root.
2. Clear the cache, logout from the admin panel and then login again.

Uninstallation
--------------
1. Remove all extension files from your Magento installation


Licence
-------
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
