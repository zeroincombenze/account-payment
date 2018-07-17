[![Build Status](https://travis-ci.org/zeroincombenze/account-payment.svg?branch=9.0)](https://travis-ci.org/zeroincombenze/account-payment)
[![license agpl](https://img.shields.io/badge/licence-AGPL--3-blue.svg)](http://www.gnu.org/licenses/agpl-3.0.html)
[![Coverage Status](https://coveralls.io/repos/github/zeroincombenze/account-payment/badge.svg?branch=9.0)](https://coveralls.io/github/zeroincombenze/account-payment?branch=9.0)
[![codecov](https://codecov.io/gh/zeroincombenze/account-payment/branch/9.0/graph/badge.svg)](https://codecov.io/gh/zeroincombenze/account-payment/branch/9.0)
[![OCA_project](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-oca-9.svg)](https://github.com/OCA/account-payment/tree/9.0)
[![Tech Doc](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-docs-9.svg)](http://wiki.zeroincombenze.org/en/Odoo/9.0/dev)
[![Help](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-help-9.svg)](http://wiki.zeroincombenze.org/en/Odoo/9.0/man/FI)
[![try it](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-try-it-9.svg)](http://erp9.zeroincombenze.it)










































































[![en](http://www.shs-av.com/wp-content/en_US.png)](http://wiki.zeroincombenze.org/it/Odoo/7.0/man)

   :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
   :alt: License: AGPL-3

Account Due List Days Overdue
=============================

This module adds to the 'Payments and due list' view the number of days that
 an open item is overdue, and classifies the amount due in separate terms
 columns  (e.g. 1-30, 31-60, +61).

The terms columns to show in the list and the number of days for within each
term can be configured.


Installation
------------





Configuration
-------------






* Go to 'Invoicing / Configuration / Overdue Terms', and add the terms,
  providing the day from, date to and a name that will be displayed in the
  Payments and due list as column.

* It is recommended to always add a last term '+ X' where the 'to days' value
  is a very big value like 99999.


Usage
-----






=====

To use this module, you need to go to:

* Invoicing / Journal Entries / Payments and due list

.. image:: https://odoo-community.org/website/image/ir.attachment/5784_f2813bd/datas
   :alt: Try me on Runbot
   :target: https://runbot.odoo-community.org/runbot/96/9.0


Known issues / Roadmap
----------------------





Bug Tracker
-----------






Bugs are tracked on `GitHub Issues
<https://github.com/OCA/account-payment/issues>`_. In case of trouble, please
check there if your issue has already been reported. If you spotted it first,
help us smashing it by providing a detailed and welcomed feedback.


Credits
-------











### Contributors






* Jordi Ballester Alomar <jordi.ballester@eficent.com>
* Holger Brunn <hbrunn@therp.nl>

### Funders

### Maintainer










.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

This module is maintained by the OCA.

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

To contribute to this module, please visit https://odoo-community.org.

[//]: # (copyright)

----

**Odoo** is a trademark of [Odoo S.A.](https://www.odoo.com/) (formerly OpenERP, formerly TinyERP)

**OCA**, or the [Odoo Community Association](http://odoo-community.org/), is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

**zeroincombenze®** is a trademark of [SHS-AV s.r.l.](http://www.shs-av.com/)
which distributes and promotes **Odoo** ready-to-use on its own cloud infrastructure.
[Zeroincombenze® distribution](http://wiki.zeroincombenze.org/en/Odoo)
is mainly designed for Italian law and markeplace.
Everytime, every Odoo DB and customized code can be deployed on local server too.

[//]: # (end copyright)

[//]: # (addons)

[//]: # (end addons)

[![chat with us](https://www.shs-av.com/wp-content/chat_with_us.gif)](https://tawk.to/85d4f6e06e68dd4e358797643fe5ee67540e408b)
