# Linux 命令学习

![ARC logo](http://www.lyarc.com/images/logo.jpg)

[ARC](http://www.lyarc.com "艾克科技")

<madalin@lyarc.com>

 ### 安装设置工具
    yum install setuptool ntsysv system-config-firewall-tui system-config-network-tui
 
 ## 修改开机等待时间
    vi /boot/grub/menu.lst  //timeout部分修改
 
 ## 显示操作历史
    history

 ## 删除操作历史
    history -c 

 ## 设置服务自动启动
    chkconfig mysqld on  //将mysql服务设置为开机启动

 ## 查看内存
    free -m    //这是按M 显示，-h显示为易读

 ## 安装`Apache`软件
    yum install httpd -y
    service httpd start //启动服务
    chkconfig httpd on //设置开机启动
    service httpd status //查看服务运行状态
    vi /etc/httpd/conf/httpd.conf  //查看








 

 

 