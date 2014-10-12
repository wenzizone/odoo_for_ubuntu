# README #

odoo是一个开源的ERP,CRM系统，这是一份使用ansible在ubuntu上安装odoo的配置文件

使用方法：
----------
		1，clone出此repo
		2，运行ansible-playbook -i hosts site.yml -k -K -v命令根据提示输入登陆密码和sudo密码

需要修改的文件
---------------
### hosts文件
    修改odoo下面的ip为服务器ip
    
### site.yml文件
		1, dbname 数据库名称
		2, dbpasswd    数据库连接密码
		3, domain_name   odoo网站的域名
		4, remote_user  连接服务器的用户名
