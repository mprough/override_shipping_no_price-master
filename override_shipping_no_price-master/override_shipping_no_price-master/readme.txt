Zen Cart Override Shipping No Price Module v 1.1
Version Release Date: 08/01/2014
Publisher: PRO-Webs, Inc
Released for Zen Cart v 1.5.3 but will likely work with most older versions.
Tested on PHP 5.4.30

This installation is considered a intermediate level Zen Cart module installation.


If you need installation, please visit our store here:
https://zencart.codes/


This Zen Cart shipping module allows you to set a product and instead
of charging any shipping cost/or charging a set shipping cost in checkout 
deliver a message such as "we will contact you with your freight for this order" 
and no shipping cost or your set cost charged at checkout.

Other free shipping products are not affected and continue to work as they always have.
Admin configurations

Configuration >> Shipping/Packaging
- Product ids to be included as this special case in a comma seperated list
- Override Shipping No Price Title
- Override Shipping No Price Description
- Override Shipping No Price Enabled/Disabled

Modules >> Shipping >> Freight
- Install/Uninstall
- Enable/Disable Override No Price Shipping
- Shipping Cost if any
- Tax Class
- Tax Basis
- Shipping Zone
- Sort Order


INSTALLATION INSTRUCTIONS
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

1. FIRST MAKE A FULLE BACKUP OF YOUR WEBSITE'S FILES AND DATABASE!

2. Upload the /includes/ directory to your catalog root. There are no overwrites.

3. Rename the /YOUR_ADMIN/ directory to match your own admin directory folder 
   name, and upload the files. There are no overwrites.

4. In the /includes-merge-core-files/ directory carefully merge 2 core files
   with the one in your existing installation.

5. That's all. You will find your shipping module in Modules >> Shipping >> Freight
   and configurations for it in Configuration >> Shipping/Packaging. 
   
   ** You will need to refresh your admin interface to load the new menu item.
      

INFORMATION
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Core file Edits: 1 file includes/functions/functions_general.php
Database Changes: Adds configurations and admin page registrations.


UNINSTALL
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Simply remove the package files and database changes for a full uninstall.


SUPPORT
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Please seek support here https://pro-webs-support.com/


VERSION HISTORY
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Beta Release PRO-Webs 08/01/2014
Bug Fix PRO-Webs 08/11/2014


Copyright (c) 2014 PRO-Webs, Inc.