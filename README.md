# EFI_deskimini-h470

## 我实测平台电脑配置

| Items       | Model               |
| ----------- | ------------------- |
| Laptop      | 华擎deskmini-h470/海尔云悦mini N-T76 |
| Motherboard | 华擎|
| CPU         | Intel Core i9-10900es |
| Fans        | 利民 AXP-90 47mm 纯铜---[更换教程](https://www.someget.cn/other/2021/11/17/others-replace_fans01.html) |
| RAM         | SK Hynix 16G*2 2667 MHz |
| Hard Disk   | WDC PC SN730 SDBPNTY-512G-1101 512G M.2 NVMe SSD |
| GPU         | Intel Graphics UHD 630 |
| Sound Card  | Realtek ALC235 & Intel SST |
| Ethernet    | Realtek USB GbE Family Controller |
| WLAN        | Broadcom BCM94360CD |

**理论cpu、内存条、固态简单替换不影响使用本efi，固态不能是pm981a之类的雷盘**

## 注意事项
1. deskmini有两个音频孔，分别位于前面板c口和usb上面和下面，请插下面那个，下面带input和output输出，上面孔只有input的mic
2. efi默认替换了拆机卡，如果使用英特尔网卡需要自己打驱动，并且最好把博通驱动删掉

## 还存在的问题
deskimini有三个视频输出接口，分别是一个dp、一个hdmi、一个c口(使用dp协议)，目前efi三个都能单独正常驱动，一起使用的话有一点问题，具体问题如下
  1. hdmi+c开机会黑屏，需要单口开机，进入系统以后再接入两个屏幕
  3. 三个口一起输出尚未测试....手上没这么多显示器暂未测试...



**2022.01.25更新** 

------------------------------------------------------------------------------

因为入白了，m1真香，所以全套都已经出了，这个仓库不再更新了，纪念折腾的日子，如果你也是这个机型可以fork走然后再这个基础上改改，h470配i9是真的强没准啥时候我脑袋一热重新想要入，到时候康康大家没有更好的EFI。

<img src="https://mypicgogo.oss-cn-hangzhou.aliyuncs.com/tuchuang20220504111207.png" alt="image-20220504111207702" style="zoom:25%;" />

<center>纪念</center>

------------------------------------------------------------------------------

