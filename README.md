# smsmanager
用于部分随身wifi刷了Debian后的短信管理图形化界面，支持实时短信Email转发
使用.net开发，运行需要配置.net 5.0.15运行库
配置好后，进入程序的文件夹内，输入
sudo dotnet smsmanager.dll
即可运行程序，当然你也可以安装screen，在screen内运行程序从而达到后台运行的效果
程序运行后，访问设备的ip:8080即可进入管理页面，默认用户密码均为admin



新增短信转发至企业微信自建应用功能

 添加独立版本，无需安装dotnet runtime
 食用方法：在debian输入sudo apt install libicu67
 安装libicu，安装好后设置debian系统为中文（自行百度），接着下载本程序的独立版本(smsmanager_independent.zip)，解压上传至debian，打开本程序根目录，输入
 sudo chmod 777 ./smsmanager
 设置运行权限，接着输入
 sudo ./smsmanager
 即可运行短信转发程序
