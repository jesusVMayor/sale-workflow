==============================
Sale Exception Public Holidays
==============================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:f72a7afa7c2a1035d53782a36ec7f5aec5f36d1876fce4564216ffaec5d5ef20
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fsale--workflow-lightgray.png?logo=github
    :target: https://github.com/OCA/sale-workflow/tree/16.0/sale_exception_holidays_public
    :alt: OCA/sale-workflow
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/sale-workflow-16-0/sale-workflow-16-0-sale_exception_holidays_public
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/sale-workflow&target_branch=16.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

This module raises a sale exception if there is a commitment_date on the SO and this date is a public holidays for the shipping partner address.

**Table of contents**

.. contents::
   :local:

Configuration
=============

#. Go to *Settings > Technical > Exception Rules*.
#. Activate the rule *Delivery Date is a public holiday*.

Usage
=====

#. Go to *Sales > Orders > Quotations*
#. Create a new quotation.
#. Set Delivery Date on a public holiday.
#. Confirm the order.
#. An exception will be displayed.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/sale-workflow/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/sale-workflow/issues/new?body=module:%20sale_exception_holidays_public%0Aversion:%2016.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* Camptocamp
* BCIM

Contributors
~~~~~~~~~~~~

* Nguyen Minh Chien <chien@trobz.com>

Other credits
~~~~~~~~~~~~~

The creation of this module to 16.0 was financially supported by Camptocamp.

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

.. |maintainer-jbaudoux| image:: https://github.com/jbaudoux.png?size=40px
    :target: https://github.com/jbaudoux
    :alt: jbaudoux

Current `maintainer <https://odoo-community.org/page/maintainer-role>`__:

|maintainer-jbaudoux| 

This module is part of the `OCA/sale-workflow <https://github.com/OCA/sale-workflow/tree/16.0/sale_exception_holidays_public>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
