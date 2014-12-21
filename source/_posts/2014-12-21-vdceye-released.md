title: vdceye 2015 R1 Released
---
![](https://github.com/xsmart/ve-img/raw/master/snapshot/20141203.png)

#### Release Version ####
[https://sourceforge.net/projects/vscloud/](https://sourceforge.net/projects/vscloud/)

	2015.0101
	1. Full support video storage & playback, support multi disk(IPSAN,Network disk)
	2. Change UI style to same.
	3. Add File base video source support.
	4. Add Camera Group support.
	5. Change to QT 5.4 Release version.
	6. Show no Video if no video.

### Functions ###
	ONVIF profile S support.
    Unlimited timeline playback.
	Anti file system fragment recording system.
	Multi Display screen support.
	Alarm Support
	PTZ Support
	ONVIF ProfileS simulator
	Emap
	Data Mining
	HDFS Video Recording

### Building ###
#### Windows ####
	1. Install VS2013
	2. Install QT 5.4.0 in the http://download.qt-project.org/official_releases/qt/5.4/5.4.0/qt-opensource-windows-x86-msvc2013-5.4.0.exe
	3. http://download.qt-project.org/official_releases/vsaddin/qt-vs-addin-1.2.4-opensource.exe
	4. Open the veapp\prj_win32\VSCloudNode.sln to build

#### Linux ####
	ubuntu: sudo apt-get install libx11-dev yasm libxext-dev libgl1-mesa-dev  zlib1g-dev
	centos: sudo yum install nasm xorg-x11-server-devel zlib-devel
	
	Install qt-opensource-linux-x64-5.4.0.run
	http://download.qt-project.org/official_releases/qt/5.4/5.4.0/qt-opensource-linux-x64-5.4.0.run
		export  PATH=$PATH:/home/xxx/Qt5.4.0/5.4/gcc_64/bin:/home/xxx/Qt5.4.0/Tools/QtCreator/bin/

For more guide
[http://www.vdceye.com/](http://www.vdceye.com/)

[xsmart@vdceye.com](xsmart@vdceye.com)

### Note: ###
	Please Delete C:\videodb if use vdcEye Manager V2014-0630.msi and before.
		


		
