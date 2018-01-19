# esp8266-for-mac
esp8266加5v继电器 制作一个简单的物联网小灯

# 步骤
* 1、设备购买
* 2、电脑环境配置（for mac）
* 3、代码调试
* 4、代码上传，设备调试

### 1、设备购买

#### 物件一、
ESP8266串口wifi模块 物联网 V3开发板 兼容 ModeMCU Lua CH340
![图片](https://github.com/YYBT/esp8266-for-mac/blob/master/1.png?raw=true)
#### 物件二、
![图片](https://github.com/YYBT/esp8266-for-mac/blob/master/2.png?raw=true)
#### 物件三、
若干个不杜邦线

### 1、设电脑环境配置（for mac）
新买的Arduino开发板 USB转串口使用了CH340芯片，在Mac OS X Yosemite上正常安装驱动后，才能正常使用
开发板背后有写需要什么驱动 购买时可以仔细看看
##### CH341SER_MAC.zip （mac 驱动文件）
![图片](https://github.com/YYBT/esp8266-for-mac/blob/master/3.png?raw=true)
* 1.安装CH340驱动（驱动下载地址：http://www.wch.cn/download/CH341SER_MAC_ZIP.html）
* 2.打开终端运行以下命令：
sudo nvram boot-args="kext-dev-mode=1"
sudo Reboot

