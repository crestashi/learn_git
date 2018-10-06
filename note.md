# git学习笔记
## 安装git
### 1. debian/ubuntu
    apt-get install libcurl4-gnutls-dev libexpat1-dev gettext \ libz-dev libssl-dev  //安装依赖工具，若不是root用户，则需要在命令最前方添加 "sudo"命令 
    apt-get install git-core    //安装git核心   
    git --version   //查看版本号    
### 2. centos/redhat
    yum install curl-devel expat-devel gettext-devel \ openssl-devel zlib-devel    //安装依赖工具，若不是root用户，则需要在命令最前方添加"sudo"命令     
    yum -y install git-core     //安装核心      
     git --version   //查看版本号   
### 3. windows
    下载".exe"文件进行安装
### 4. mac
[foo]: http://sourceforge.net/projects/git-osx-installer/ "下载gui图像安装程序"
