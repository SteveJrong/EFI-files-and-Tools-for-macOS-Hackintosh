# EFI files and Tools for macOS Hackintosh
 
#### 介绍 
特定设备引导黑苹果操作系统的EFI文件及特定设备附带的工具。

#### 说明
1. 支持的设备：
- Intel平台：  
微星ZH77A G43 Plus台式电脑  
惠普ZBook 15 G2笔记本电脑  
惠普ProDesk 400 G3 Desktop Mini（DM）微型台式电脑  
戴尔Optiplex 3050 Micro（MFF）微型台式电脑  
戴尔Venue 11 Pro 7130MS二合一笔记本电脑  
- AMD平台：  
华擎A320M HDV R4.0台式电脑  

#### 如何使用
将特定设备目录中对应操作系统版本号下的EFI引导文件压缩包解压后，覆盖到U盘内EFI分区内对应目录中即可。  
若启动卡代码报错，请视实际情况对EFI引导文件进行适当微调后再试。

#### 版本信息
1.0

#### 更新日志
2021/01/08：  
初版提交，支持6种特定设备。

2021/01/12：  
增加适用于```戴尔Venue 11 Pro 7130MS```设备在```macOS Mojave 10.14.6```操作系统下的EFI引导文件。  
成功驱动```戴尔Venue 11 Pro 7130MS```设备在```macOS Mojave 10.14.6```操作系统下的```HD4200```核显（关键在于其核显的```ig-platform-id```使用的是台式机的```0x0d220003```，而非移动版的```0x0a260006```），更新其EFI引导文件。