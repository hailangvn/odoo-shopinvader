=================
Shopinvader image
=================

.. !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-shopinvader%2Fodoo--shopinvader-lightgray.png?logo=github
    :target: https://github.com/shopinvader/odoo-shopinvader/tree/14.0/shopinvader_image
    :alt: shopinvader/odoo-shopinvader

|badge1| |badge2| |badge3| 

This module builds up on functionality defined in storage_image to define new Shopinvader-specific functionality,
and implements them on the Shopinvader version of categories and variants.

**Table of contents**

.. contents::
   :local:

Installation
============

Follow the documentation of the storage_backend module

Usage
=====

Essentially, call _compute_images whenever you want to refresh all image thumbnails/resizes
on your records. Resized images are then accessible through the "images" serialized field.

For an example of full implementation on a new model, you can view shopinvader_banner.

Changelog
=========

10.0.1.0.0 (2018-05-02)
~~~~~~~~~~~~~~~~~~~~~~~

* [ADD] First draft to have image into dict/json exported

12.0.1.0.0 (2019-06-03)
~~~~~~~~~~~~~~~~~~~~~~~

* [12.0][MIG] shopinvader_image

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/shopinvader/odoo-shopinvader/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us smashing it by providing a detailed and welcomed
`feedback <https://github.com/shopinvader/odoo-shopinvader/issues/new?body=module:%20shopinvader_image%0Aversion:%2014.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* Akretion

Contributors
~~~~~~~~~~~~

* Sebastien BEAU <sebastien.beau@akretion.com>
* Laurent Mignon <laurent.mignon@acsone.com>
* François Honoré <francois.honore@acsone.eu>
* Raphaël Reverdy <raphael.reverdy@akretion.com>
* Denis Roussel <denis.roussel@acsone.eu>

Maintainers
~~~~~~~~~~~

This module is part of the `shopinvader/odoo-shopinvader <https://github.com/shopinvader/odoo-shopinvader/tree/14.0/shopinvader_image>`_ project on GitHub.

You are welcome to contribute.
