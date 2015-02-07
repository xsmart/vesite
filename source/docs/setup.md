title: Setup
---

## Install ##
#### Windows ####
Download *OpenCVR xxx.msi*  from 
[https://sourceforge.net/projects/vscloud/](https://sourceforge.net/projects/vscloud/) 

    Add Path "C:\Program Files\Java\jdk1.8.0_25\jre\bin\server" for HDFS

#### Linux ####
ubuntu: sudo apt-get install libx11-dev yasm libxext-dev libgl1-mesa-dev  zlib1g-dev
centos: sudo yum install nasm xorg-x11-server-devel zlib-devel

Download *OpenCVR-Ubuntu(CentOS)-xxx-32bit(64bit)-201xxxxx.tar.gz*  from
[https://sourceforge.net/projects/vscloud/](https://sourceforge.net/projects/vscloud/)

##### 64bit #####
	1.Install qt-opensource-linux-x64-5.4.0.run 
	http://download.qt-project.org/official_releases/qt/5.4/5.4.0/qt-opensource-linux-x64-5.4.0.run 
	   ---> add below 2 line into /etc/profile
	export  PATH=/home/xxx/Qt5.4.0/5.4/gcc_64/bin:/home/xxx/Qt5.4.0/Tools/QtCreator/bin/:$PATH
	export  VE_QTDIR=/home/xxx/Qt5.4.0/5.4/gcc_64/
	2.edit the env.sh LD_LIBRARY_PATH for the current dir
	   ./root.sh
	   source ./env.sh
	   ./start.sh
		
##### 32bit #####
	1.Install qt-opensource-linux-x86-5.4.0.run 
	http://download.qt-project.org/official_releases/qt/5.4/5.4.0/qt-opensource-linux-x86-5.4.0.run 
	   ---> add below 2 line into /etc/profile
	export  PATH=/home/xxx/Qt5.4.0/5.4/gcc/bin:/home/xxx/Qt5.4.0/Tools/QtCreator/bin/:$PATH
	export  VE_QTDIR=/home/xxx/Qt5.4.0/5.4/gcc/
	2.edit the env.sh LD_LIBRARY_PATH for the current dir
	   ./root.sh
	   source ./env.sh
	   ./start.sh

![](https://github.com/xsmart/ve-img/raw/master/document/started/setup.png)
