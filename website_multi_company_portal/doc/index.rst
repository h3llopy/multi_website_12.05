======================
 Multi Website Portal
======================

Installation
============

* `Install <https://eagle-development.readthedocs.io/en/latest/eagle/usage/install-module.html>`__ this module in a usual way

Configuration
=============

Follow instruction of the base module `Real Multi Website <https://www.eagle.com/apps/modules/12.0/website_multi_company/>`__.

For internal (employee) users multi-company mode in portal works only for companies specified in  **Allowed Companies**	field.

Usage
=====

* For some user create orders, invoices that belongs to different companies (via backend or eCommerce application)
* Login to portal as that user at first website
* RESULT:

  * you see only orders, invoices from that company.
  * link to download invoices at Sale Order page works
  * when you click ``[ (->) Pay Now ]`` button, it shows proper payment acquirer

* Login to portal as that user at another website that belongs to second company
* RESULT: same as above, but for second company
