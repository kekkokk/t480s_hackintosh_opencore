# Lenovo-t480s-catalina
CLOVER EFI for t480s osx Catalina

What's working:
Basically everything

* Trackpad with gestures (also trackpoint works, no need to disable in BIOS)
* Wifi + BT (Dell 1830 or 1560)
* Webcam
* Audio input/output
* HDMI + audio
* Usb-c
* Media keys
* Sleep / wake
* Sensors

Not Working:
* Fingerprint sensor

Not tested:
* Thunderbolt support but should work fine

The actual keyboard layout is IT.
You can change/replace the actual https://github.com/kekkokk/Lenovo-t480s-catalina/blob/master/kexts/Other/VoodooPS2Controller.kext/Contents/PlugIns/VoodooPS2Keyboard.kext/Contents/Info.plist

Also you can enable some interesting features of the trackpad here:
https://github.com/kekkokk/Lenovo-t480s-catalina/blob/ab67f63764db7f6fd9326731d7b33aa169847ac1/kexts/Other/VoodooSMBus.kext/Contents/Info.plist#L489

To do so, refer to the original guide:
https://github.com/leo-labs/VoodooSMBus/blob/master/README.md#configuration

# CREDITS
This repo is based on the awesome work done by https://github.com/linusyang92/macOS-ThinkPad-T480s

It also includes a fully functional trackpad support thanks to https://github.com/leo-labs/VoodooSMBus


