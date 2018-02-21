[![Build Status](https://travis-ci.org/zeroincombenze/account-payment.svg?branch=8.0)](https://travis-ci.org/zeroincombenze/account-payment)
[![license agpl](https://img.shields.io/badge/licence-AGPL--3-blue.svg)](http://www.gnu.org/licenses/agpl-3.0.html)
[![Coverage Status](https://coveralls.io/repos/github/zeroincombenze/account-payment/badge.svg?branch=8.0)](https://coveralls.io/github/zeroincombenze/account-payment?branch=8.0)
[![codecov](https://codecov.io/gh/zeroincombenze/account-payment/branch/8.0/graph/badge.svg)](https://codecov.io/gh/zeroincombenze/account-payment/branch/8.0)
[![OCA_project](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-oca-8.svg)](https://github.com/OCA/account-payment/tree/8.0)
[![Tech Doc](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-docs-8.svg)](http://wiki.zeroincombenze.org/en/Odoo/8.0/dev)
[![Help](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-help-8.svg)](http://wiki.zeroincombenze.org/en/Odoo/8.0/man/FI)
[![try it](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-try-it-8.svg)](http://erp8.zeroincombenze.it)
































[![en](http://www.shs-av.com/wp-content/en_US.png)](http://wiki.zeroincombenze.org/it/Odoo/7.0/man)

.. image:: https://img.shields.io/badge/licence-AGPL--3-blue.svg
   :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
   :alt: License: AGPL-3

Payment Order Sequence
======================

This module adds feature to create payment order reference
based on payment mode. Each payment mode could have different
sequence.

Installation
------------





To install this module, you need to:

1.  Clone the branch 8.0 of the repository https://github.com/OCA/account-payment
2.  Add the path to this repository in your configuration (addons-path)
3.  Update the module list
4.  Go to menu *Setting -> Modules -> Local Modules*
5.  Search For *Payment Order Sequence*
6.  Install the module


Configuration
-------------





To configure specific sequence for payment mode, you need to:

1. Open or create payment mode
2. Choose sequence to be used


Usage
-----







=====

To use this module, you need to:

1. Create payment order

Payment order reference will be created according sequence configuration
on payment mode. Payment mode with empty sequence will use original payment
order sequence.

.. image:: https://odoo-community.org/website/image/ir.attachment/5784_f2813bd/datas
   :alt: Try me on Runbot
   :target: https://runbot.odoo-community.org/runbot/96/8.0

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





Images

* Odoo Community Association: `Icon <https://github.com/OCA/maintainer-tools/blob/master/template/module/static/description/icon.svg>`_.





### Contributors





* Andhitia Rama <andhitia.r@gmail.com>

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
