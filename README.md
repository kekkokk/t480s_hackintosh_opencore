# Lenovo-t480s-hackintosh
OPENCORE CONFIG for t480s running Big Sur
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
* Thunderbolt hot plug

Not Working:
* Fingerprint sensor

Also you can enable some interesting features of the trackpad editing the config in VoodooSMBus.kext/Contents/Info.plist

To do so, refer to the original guide:
https://github.com/leo-labs/VoodooSMBus/blob/master/README.md#configuration

# CONFIGURE
The only thing you need to generate are the system UUIDs: https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html#generate-a-new-serial

# EXTRA
You can also install https://github.com/MSzturc/ThinkpadAssistant to enable all the keyboard specific functionalities like mute mic, adjust brighness, enable/disable wifi, etc.
The SSDTs are already there and ready.
Just install the app.

# CREDITS
This repo is a complete rework of the original awesome work done by https://github.com/linusyang92/macOS-ThinkPad-T480s

It also includes a fully functional trackpad support thanks to https://github.com/leo-labs/VoodooSMBus


