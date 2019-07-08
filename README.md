Odoo
----

Odoo is a suite of web based open source business apps.

The main Odoo Apps include an <a href="https://www.odoo.com/page/crm">Open Source CRM</a>,
<a href="https://www.odoo.com/page/website-builder">Website Builder</a>,
<a href="https://www.odoo.com/page/e-commerce">eCommerce</a>,
<a href="https://www.odoo.com/page/warehouse">Warehouse Management</a>,
<a href="https://www.odoo.com/page/project-management">Project Management</a>,
<a href="https://www.odoo.com/page/accounting">Billing &amp; Accounting</a>,
<a href="https://www.odoo.com/page/point-of-sale">Point of Sale</a>,
<a href="https://www.odoo.com/page/employees">Human Resources</a>,
<a href="https://www.odoo.com/page/lead-automation">Marketing</a>,
<a href="https://www.odoo.com/page/manufacturing">Manufacturing</a>,
<a href="https://www.odoo.com/page/purchase">Purchase Management</a>,
<a href="https://www.odoo.com/#apps">...</a>

Odoo Apps can be used as stand-alone applications, but they also integrate seamlessly so you get
a full-featured <a href="https://www.odoo.com">Open Source ERP</a> when you install several Apps.


Getting started with Odoo
-------------------------
For a standard installation please follow the <a href="https://www.odoo.com/documentation/master/setup/install.html">Setup instructions</a>
from the documentation.

Then follow <a href="https://www.odoo.com/documentation/master/tutorials.html">the developer tutorials</a>

## 🚀 Create an application on AWS Elastic Beanstalk via awsebcli

1.  **Initialize your EB CLI repository with the eb init command**

    ```sh
    eb init -p python-3.6 odoo-elastic-beanstalk --region ap-southeast-1
    ```   
1.  **Run eb init again to configure a default keypair so that you can connect to the EC2 instance running your application with SSH**

    ```sh
    eb init
    ```    
1.  **Create an environment and deploy your application**

    ```sh
    eb create odoo11-env
    ```    
1.  **When the environment creation process completes, open your web site with eb open**

    ```sh
    eb open
    ```    
