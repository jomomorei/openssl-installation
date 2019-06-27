# openssl-installation
openssl的安装流程

折腾了半天，终于安装结束

折腾的原因是之前参考了一个用c++的nmake命令去编译openssl包，好不容易装了c++的库，在编译的时候打不开windows.h库函数，而告终。
最终放弃。直接找了个现成的可执行文件，一步到位，非常方便。

### 1. 安装ActivePerl

下载地址：https://www.activestate.com/products/activeperl/downloads/

按部就班安装即可。

### 2.安装openssl

下载地址：http://slproweb.com/products/Win32OpenSSL.html

根据电脑配置选择64位或32位。

配置环境变量：把openssl安装路径bin的路径（如 C:\OpenSSL-Win64\bin）添加到系统环境变量Path中。

重启电脑

以管理员身份在cmd中运行openssl。

完成。

