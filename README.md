# S400CA-Hackintosh

如果你是中文用户，请看上面的README_zh-cn.md

I have installed MacOS sierra 10.12 at S400CA with some bugs

Please add FakeSMC.kext by yourself

### Note: 
   Will try 10.13 at the end of <del> july </del> Year

### Specifications:

    i5-3317U
    HD4000 
    VT1802P sound card
    AR8161 Ethernet Controller
    180GB intel Solid State Drive(changed)
    6GB DDR3 1600Mhz
### Working :

     Display Brightness
     Sound (extMic not work)
     Battery
     Camera
     Power Management
     Touch Screen (One finger)
     Trackpad gestures
     SD Card Reader(USB)
     Sleep
### NOT Working :
     VGA port
     boot slow — SLOVED via Flash BIOS,Boot into desktop won’t need more than 40 seconds
     wifi&BT(Has changed to QCA9565 , Although AR9485 has worked)
# Credits
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

# Change log

    2017.9.15  Combo update to prepare 10.13
    2017.9.8   Add Chinese Translation and BIOS File
    2017.8.18  Little update and use new way patch kext
    2017.7.18  Add Ethernet solution script
    2017.7.15  Fix USB caused Sleep issue(instant wake)
    2017.7.14  update patches for Fake Haswell
    2017.6.24  sync Lilu&AppleALC with official
    2017.6.23  simply update clover version to 4097
    2017.5.29  simply update clover version to 4077
    2017.3.24  update VT1802 source file to fake AppleHDA
    2017.2.23  create it
