# Lenovo-G480 （苏菲级完美支持10.15~11全系安装）

CPU    i3-3110-主频（2.4GHZ）

声卡    ALC-269

显卡    HD4000

无线网卡 AR9485 

无蓝牙



![ss](https://github.com/mjs520/Lenovo-G480/blob/main/screenshot0.jpg)
![ss](https://github.com/mjs520/Lenovo-G480/blob/main/QQ20210221-103454.png)
![ss](https://github.com/mjs520/Lenovo-G480/blob/main/QQ20210208-102305.png)




              联想G480已完善如下
睡眠正常

睡眠唤醒声音正常

触控板手势基本正常

Hacktool打缓冲针补丁，显卡HD4000驱动正常，显示PCI信息，注入EDID信息

修改显存2048mb

USB端口定制2.0、3.0正常

有线网卡正常

AR9485无线网卡正常

ALC269声卡仿冒正常

EC0重命名EC，ACPI添加仿冒SSDT-EC

添加了FixEDID修补，提高色彩温和度，增加了桌面分辨率选择

修改DSDT，加载LPC硬件ID加载原生电源管理

变频正常 (CPUFried+sSDTPRGen)

增加了XMPDetection(只适用DDR3)，即可将内存条自动超频到1600或更高值。

添加亮度DSDT~HD4000亮度补丁+(GFX0重命名IGUP)+ACPIBacklight.kext亮度滑块正常。

亮度、声音细腻调节（1/4格）｛小太阳快捷键-功能键+F5、F6，声音快捷键-功能键+F11、F12｝

添加热补丁(SSDT-ALS0+SMCLightsensors.kext)实现亮度保存，及自动调节选项。

添加ACPIbatterymanage.kext实现电池百分比正常

添加三码AppleStore正常下载，FaceTime，Imesge正常

添加DSDT～SMBus补丁加载SMBus成功

存在不足： AR9485驱动已停跟新，存在信号显示掉格不影响网速！
硬件无蓝牙。声卡Alc269存在极少情况无法驱动，重启电脑就好。
  
