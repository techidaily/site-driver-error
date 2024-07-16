---
title: Guide to Reconnecting USB Devices in Win 7/8 OS
date: 2024-07-13 15:37:34
updated: 2024-07-16 10:17:30
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Guide to Reconnecting USB Devices in Win 7/8 OS
excerpt: This Article Describes Guide to Reconnecting USB Devices in Win 7/8 OS
thumbnail: https://thmb.techidaily.com/c773b247e1e0895c35ac3965c0957524900af663f812d6e184693495dab0728b.jpg
---

## Guide to Reconnecting USB Devices in Win 7/8 OS

![](https://images.drivereasy.com/wp-content/uploads/2016/08/usb-device-not-recognized.png) When you plug in your USB flash drive, a balloon warning in system tray would pop up to tell you that**USB Device Not Recognized**. Sometimes you don’t even see this notification and your USB flash driver just stops working. No worries, it’s possible and, in some cases, quite easy to fix. Here are 3 solutions for you to try. You may not need to try them all, just work your way down and find the one works for you.   **Method 1:[Reinstall USB Driver](https://versadesk.pxf.io/xyboxx) Method 2:[Update USB Driver Automatically (Recommended)](#update) Method 3: [Remove External Devices](https://laganoo.pxf.io/5g6ygn) Method 4:[Create INF Files](https://ancheer.sjv.io/y96bgp)**

## **Method 1: Reinstall USB Driver**

Faulty or outdated USB driver can render your USB devices not responding. To fix it: 1) On your keyboard, press the**Windows logo key**and**R**at the same time to invoke a Run command. Type**devmgmt.msc**in and press**Enter**.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59a9230c26f39.png)

2) Expand **Universal Serial Bus controllers**. See if you can a yellow exclamation mark in front of your**Host Controller**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/yellow-exclamation-marks-in-device-manager.jpg) If you cannot see such a device under **Universal Serial Bus controllers**, check if you can see it under**Other devices**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/unknown-device.png) 3) Double-click the device with a yellow exclamation mark. Go to**Driver**, click **Uninstall**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b6c64654e98.png) 4) Check the box for **Delete the driver software for this device**and click **OK.** ![](https://images.drivereasy.com/wp-content/uploads/2016/08/confirm-uninstall.png) 5) Reboot your computer with the USB flash drive connected. See if Microsoft helps you detect and install the new USB driver. If you have more than one**Host Controllers** with the yellow exclamation marks in front, repeat these procedures more than once.

## Method 2: Update USB driver automatically

If Microsoft fails to find the latest version of the USB driver for you, you might need to search for it by yourself. If you don’t have the time, patience or computer skills to update your drivers manually, you can do it automatically with [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/). Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version it takes just 2 clicks (and you get full support and a 30-day money back guarantee): 1)[**Download**](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy. 2) Run Driver Easy and click the**Scan Now**button. Driver Easy will then scan your computer and detect any problem drivers. ![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58e60dbd97325.png) 3) Click the**Update**button next to the flagged USB device to automatically download and install the correct version of this driver (you can do this with the FREE version). Or click**Update All**to automatically download and install the correct version of all the drivers that are missing or out of date on your system (this requires the [**Pro version**](https://tools.techidaily.com/drivereasy/download/)– you’ll be prompted to upgrade when you click Update All). ![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58e60dd5d26f7.jpg)

## **Method 3: Remove External Devices**

If there are too many USB devices connected to your PC, some of them might not respond or work properly. To fix it, you can try clean restart your PC: Remove or disconnect all unnecessary discs and devices from your computer. Make sure that the computer is off, and then remove any discs and USB devices and the memory cards from the card reader slot. Disconnect non-essential devices such as camera, MP3-playersprinters, scanners, external hard drives etc., and leave mouse, keyboard and monitor connected. If you are a**laptop**user: 1) Turn off the computer and make sure you have disabled or disconnected all unnecessary external devices. Remove the computer from any port replicator or docking station. 2) Unplug the AC adapter from the computer and remove the battery from the battery compartment. 3) Press and hold the**Power**button for about 15 seconds to drain any residual electrical charge from the capacitors that protect the memory. 4) Insert the battery and AC adapter back into the laptop, but make sure you don’t connect any external devices just yet. 5) Press**Power**button to turn on the computer. Then reconnect the USB devices one by one. If you are using**desktop**: 1) Turn off the computer completely and disconnect the power cord from the back of the computer. 2) Press the power button on the computer for 5 seconds. 3) Reconnect the power cord and turn on the power. Then reconnect the USB devices one by one.

## **Method 4: Create INF Files**

1) Go to**C:\\Windows\\inf**folder. Make sure you can see these files listed: (there could be other files)**usb.inf,** **usb2.inf,** **usbport.inf,** **usbprint.inf,** **usbstor.inf,** **usbvideo.inf** ![](https://images.drivereasy.com/wp-content/uploads/2016/08/usb-inf-file-folder.jpg) 3) If some of the above files are missing, you need to create them. If you have another computer with all the USB ports well functioned, look for the files in that computer, copy and paste them here. 4) If you don’t have another computer, here is the alternative for you. Download the mentioned files from this webpage <http://www.infdump.com/>. You can find the files by searching with the name of the files. Download the files**usb.inf,** **usb2.inf,** **usbport.inf,** **usbprint.inf,** **usbstor.inf,** **usbvideo.inf**, one by one. You can save them directly to the **C:\\Windows\\inf** folder when you are downloading or you can copy them to the**C:\\Windows\\inf** folder all together after you have downloaded all of them. 5) After the files are replaced or created, you need to unplug all of your USB devices and then plug them back in again. If necessary, you can also do a reboot. **Related post:** **[What to do if USB not recognized in Windows 10?](https://tools.techidaily.com/drivereasy/download/)**

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>
