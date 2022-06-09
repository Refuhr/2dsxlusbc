# 2dsxlusbc

This is an adapter PCB designed to put an USB Type C port as the charging port of a Nintendo 2ds XL.  

![Finished Mod](https://github.com/Refuhr/2dsxlusbc/blob/main/images/port-in-shell.jpg)

# Features

This PCB allows your 2ds XL to be charged via USB Type C with an USB A to USB C cable. Additionally, if you use two 5.1k 0402 resistors it enables USB Type C Host charging, which means that your 2ds should now be compatible with any USB PD Charger (not tested yet).

# What you need

-the PCB, available from [oshpark](https://oshpark.com/shared_projects/KSdF5ITT) ($0.60 shipped in the US, about 0.70€ shipped in the EU), [gerbers](https://github.com/Refuhr/2dsxlusbc/blob/main/Gerber_PCB_2dsxlusbc_V4.zip)  
-the USB Type C port: [Ebay](https://www.ebay.com/itm/153460023680) or [Aliexpress](https://de.aliexpress.com/item/4000857925361.html) (search for: usb type c 6 pin)  
-optional (required for USB C Host charging): two 5.1K 0402 resistors (available at local electronics store)  
-soldering iron with solder  
-heat gun for removing the original charging port (can be done without an heat gun, I personally wouldn't recommend it)  
-desoldering braid/desoldering pump  
-flux  

# Installation

Instructions for assembly/installation can be found in [INSTALLATION.md](https://github.com/Refuhr/2dsxlusbc/blob/main/INSTALLATION.md)  

# PCB

By measuring the pads of the old charging port, I was able to design a [custom footprint](https://easyeda.com/component/d013406ddfa94d40b684a1f854966128) for the charging port of the 2ds xl in easyeda. The PCB with the USB Type C port is held down with solder at the original pads. It seems to be quite strong, but superglue wouldn't hurt to help with the rigidity of the port.  
Top layer:
![Top layer](https://github.com/Refuhr/2dsxlusbc/blob/main/images/top.png)
Bottom layer:
![Bottom layer](https://github.com/Refuhr/2dsxlusbc/blob/main/images/bottom.png)

# Thanks

Thank you to [rorosaurus](https://github.com/rorosaurus/3ds-xl-usb-c) and [makho](https://www.youtube.com/channel/UC5FYpo9lFqK1Y7wqjPuANFw) for the inspiration of this PCB!
