# S400CA-Hackintosh
EDIT...
I have installed MacOS 10.12 at S400CA with some bugs

### Specifications:

    i5-3317U
    HD4000 
    VT1802P sound card
    AR8161 Ethernet Controller
    180GB intel Solid State Drive(changed)
    6GB DDR3 1600Mhz
### Working :

     Display Brightness
     Sound (extMic not working)
     Battery
     camera
     Power Management
     Touch Screen (One finger)
     Trackpad gestures
     SD Card Reader(USB)
     Sleep(sometimes not work when AC adapter plugin)
### NOT Working :
     VGA port
     boot slow (up to 1 minutes)
     wifi&BT(Has changed to QCA9565 , Although AR9485 has worked)
# Credits
    kavenliang's clover file on 10.10
    EMlyDinEsH for ApplePS2SmartTouchPad kext
    Pike R. Alpha for SSDTPRGen.sh
    Rehabman's laptop DSDT patches and some kexts
    PMheart for get XCPM and Fake Haswell Cpu work
    syscl for enable-HiDPI.sh
    Mieze's Atheros Killer E2200 driver
    vit9696's AppleALC project
    etc.

# Change log

    2017.3.24  update VT1802 source file to fake AppleHDA
    2017.2.23  create it
