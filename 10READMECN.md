C:\Users\Administrator\PycharmProjects\OCB\venv64\Scripts\python.exe C:/Users/Administrator/PycharmProjects/OCB/odoo-bin -r odoo -w 222.133.8.86 --addons-path=C:/Users/Administrator/PycharmProjects/OCB/addons,C:/Users/Administrator/PycharmProjects/OCB/odoo/addons

注意 [wiki](https://try.ucaitu.com/1CIO/OCB/wiki)
____

要下载 pywin32-221.win32-py2.7.exe 最新版本是221，安装win32而不是64

https://github.com/mhammond/pywin32/releases

安装自动备份插件需要安装pysftp
psycopg2==2.7.1
python-ldap==2.4.27

[windows下安装](http://www.jianshu.com/p/b4b46fc11c74)

pip install python_ldap-2.4.38-cp27-cp27m-win_amd64.whl

[pg安装](https://doc.odoo.com/6.0/zh_CN/install/windows/postgres/)

[详细安装指导例如安装pypiwin32](https://www.odoo.com/documentation/10.0/setup/install.html)

如果碰到页面无法正常显示问题，则http://127.0.0.1:8069/web?debug，激活开发者模式

npm install -g less

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
For a standard installation please follow the <a href="https://www.odoo.com/documentation/10.0/setup/install.html">Setup instructions</a>
from the documentation.

If you are a developer you may type the following command at your terminal:

    wget -O- https://raw.githubusercontent.com/odoo/odoo/10.0/setup/setup_dev.py | python

Then follow <a href="https://www.odoo.com/documentation/10.0/tutorials.html">the developer tutorials</a>


For Odoo employees
------------------

To add the odoo-dev remote use this command:

    $ ./setup/setup_dev.py setup_git_dev

To fetch odoo merge pull requests refs use this command:

    $ ./setup/setup_dev.py setup_git_review

