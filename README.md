# EFI_deskimini-h470-
## 我实测平台电脑配置
| Items       | Model               |
| ----------- | ------------------- |
| Laptop      | 华擎deskmini-h470/海尔云悦mini N-T76 |
| Motherboard | 华擎|
| CPU         | Intel Core i5-10400(打算马上升级i7-10900es) |
| Fans        | 利民 AXP-90 47mm 纯铜---[更换教程](https://www.someget.cn/other/2021/11/17/others-replace_fans01.html) |
| RAM         | SK Hynix 16G*2 2667 MHz |
| Hard Disk   | WDC PC SN730 SDBPNTY-512G-1101 512G M.2 NVMe SSD |
| GPU         | Intel Graphics UHD 630 |
| Sound Card  | Realtek ALC235 & Intel SST |
| Ethernet    | Realtek USB GbE Family Controller |
| WLAN        | Broadcom BCM94360CD |

**理论cpu、内存条、固态简单替换不影响使用本efi，但cpu不能是es不显版，固态不能是pm981a之类的雷盘**

## 注意事项
1. deskmini有两个音频孔，分别位于前面板c口和usb上面和下面，请插下面那个，下面带input和output输出，上面孔只有input的mic
2. deskimini有三个视频输出接口，分别是一个dp、一个hdmi、一个c口(使用dp协议)，目前efi三个都能单独正常驱动，一起使用的话有一点问题，具体问题如下
  1. hdmi+dp开机会花屏，花屏三秒后正常，dp口的显示器分辨率不正常，睡眠再次唤醒以后就正常
  2. hdmi+c显示正常，但是c口会随机性黑屏然后亮屏，并且前面的usb口信号衰弱严重，具体表现接鼠标会掉帧，不知道是不是我电脑问题
  3. 三个口一起输出....手上没这么多显示器暂未测试...
3. efi默认替换了拆机卡，如果使用英特尔网卡需要自己打驱动，并且最好把博通驱动删掉

## 还存在的问题
1. 上述说的视频输出问题
  
