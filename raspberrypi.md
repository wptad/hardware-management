#raspberrypi

## install

* [Download](http://www.raspberrypi.org/downloads/) RASPBIAN
* make a usb disk 
* * FAT32 format
* * Better using windows, faster
* * [win32diskimager](http://sourceforge.net/projects/win32diskimager/)
* [开机指南](http://pan.baidu.com/s/1zKMIx), [英文版](http://www.raspberrypi.org/wp-content/uploads/2012/04/quick-start-guide-v2_1.pdf)

* REFER <http://www.cnblogs.com/abel/p/3441175.html>
* REFER <http://blog.csdn.net/rk2900/article/details/8632713>
* REFER <http://shumeipai.nxez.com/download>


* login

```
默认账号是pi
默认密码是raspberry
```


## command

* pi的配置

```
sudo raspi-config
```

* 关机

```
poweroff

```
	
* 查看USB设备类型，寻找USB无线网卡是否已经被系统识别

```
lsusb
```
* 查看内核模块是否支持你的设备

```
lsmod
```

* 查看无线设备配置

```
iwconfig
```



## mirror


```
Default:

deb http://mirrors.hustunique.com/raspbian/raspbian wheezy main contrib non-free rpi

CN: 

deb http://raspbian.cnssuestc.org/raspbian/ wheezy main contrib non-free rpi


```

## Node.js Environment

```
apt-get remove nodered -y
apt-get remove nodejs nodejs-legacy -y
apt-get remove npm  -y # if you installed npm
curl -sL https://deb.nodesource.com/setup_6.x | sudo bash -
apt-get install nodejs -y
```

## camera


```
sudo apt-get update
sudo apt-get upgrade
sudo raspi-config

```

* [Document in Chinese](http://shumeipai.nxez.com/2014/09/21/raspicam-documentation.html)
* REFER <http://shumeipai.nxez.com/2013/10/07/raspberry-pi-to-install-the-camera-module.html>

* based on VLC <http://www.doepiccoding.com/blog/?p=212>
* [based on motion](http://www.codeproject.com/Articles/665518/Raspberry-Pi-as-low-cost-HD-surveillance-camera)
* [based on MJPG-streamer](http://blog.miguelgrinberg.com/post/how-to-build-and-run-mjpg-streamer-on-the-raspberry-pi)
* [based on MJPG-Streamer 2](http://blog.miguelgrinberg.com/post/stream-video-from-the-raspberry-pi-camera-to-web-browsers-even-on-ios-and-android)


##google tv

<http://blog.donaldderek.com/2013/06/build-your-own-google-tv-using-raspberrypi-nodejs-and-socket-io/>
