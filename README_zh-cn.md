# S400CA-Hackintosh

If you are Englsh User , Please See README.md

I have installed MacOS 10.13 at S400CA with some bugs

请自行手动添加 FakeSMC.kext

### 注:

 对于后续版本的MacOS，只更新 clover,kext 的版本 应该就可以
 <del> 将在今年年底尝试10.13 </del> 

### 电脑配置:

    i5-3317U
    HD4000 
    VT1802P sound card
    AR8161 Ethernet Controller
    180GB intel Solid State Drive(changed)
    6GB DDR3 1600Mhz
### 已经工作的 :

     Display Brightness
     Sound (extMic not work)
     Battery
     Camera
     Power Management
     Touch Screen (One finger)
     Trackpad gestures
     SD Card Reader(USB)
     Sleep
### 不工作的 :
     VGA port
     boot slow ————已由刷BIOS解决，开机进桌面不会超过40秒
     wifi&BT(Has changed to QCA9565 , Although AR9485 has worked)
# 致谢
    kavenliang's clover file on 10.10
    EMlyDinEsH for ApplePS2SmartTouchPad kext
    Pike R. Alpha for SSDTPRGen.sh and freqVectorsEdit.sh
    Rehabman's laptop DSDT patches and some kexts
    PMheart for get XCPM and Fake Haswell Cpu work
    syscl for enable-HiDPI.sh
    Mieze's Atheros Killer E2200 driver
    vit9696's Lilu&AppleALC project
    Mirone’s VT1802 audio data base


    etc.

# 更改日志

    2017.9.30  已更新10.13 , 更新kext驱动版本
    2017.9.15  为10.13准备更新
    2017.9.8   添加中文翻译和BIOS文件
    2017.8.18  小更新 和 用新方式给kext打补丁
    2017.7.18  添加网线接口不可用的解决脚本
    2017.7.15  修复USB导致的睡眠问题(instant wake)
    2017.7.14  更新仿冒Haswell架构的补丁
    2017.6.24  从Lilu&AppleALC官方同步版本
    2017.6.23  简单的更新clover版本到4097
    2017.5.29  简单的更新clover版本到4077
    2017.3.24  更新VT1802原文件来仿冒AppleHDA
    2017.2.23  创建它
