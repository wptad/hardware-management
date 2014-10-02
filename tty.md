# terminal

## minicom


### install 

```
brew install minicom
```

### usage

* first time setting required

```
minicom -s
```


* 出现配置菜单：选serial port setup
* 进入串口配置
* 输入A配置串口驱动为/dev/ttyS0
* 输入E配置速率为115200 8N1
* 输入F将 Hardware Flow Control 设 为 NO
* 退出并保存


### setting

```
Esc+z
```


* <http://pbxbook.com/other/mac-tty.html>


## mac drivers

* PL2303  <http://www.prolific.com.tw/US/ShowProduct.aspx?p_id=229&pcid=41>
* FTDI	<http://www.ftdichip.com/Drivers/VCP.htm>
* CH340	<http://www.wch.cn/downloads.php?name=pro&proid=178>