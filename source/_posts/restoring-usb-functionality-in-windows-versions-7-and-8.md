---
title: Restoring USB Functionality in Windows Versions 7 & 8
date: 2024-09-04T12:48:28.825Z
updated: 2024-09-05T12:48:28.825Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Restoring USB Functionality in Windows Versions 7 & 8
excerpt: This Article Describes Restoring USB Functionality in Windows Versions 7 & 8
thumbnail: https://thmb.techidaily.com/fa549a8f4ea78a6f19c6043f8b4168f45b8a02a01f09c9a4cfb746e3a5491976.jpg
---

## Restoring USB Functionality in Windows Versions 7 & 8

![](https://images.drivereasy.com/wp-content/uploads/2016/08/usb-device-not-recognized.png) When you plug in your USB flash drive, a balloon warning in system tray would pop up to tell you that**USB Device Not Recognized**. Sometimes you don’t even see this notification and your USB flash driver just stops working. No worries, it’s possible and, in some cases, quite easy to fix. Here are 3 solutions for you to try. You may not need to try them all, just work your way down and find the one works for you.   **Method 1:[Reinstall USB Driver](https://versadesk.pxf.io/xyboxx) Method 2:[Update USB Driver Automatically (Recommended)](#update) Method 3: [Remove External Devices](https://laganoo.pxf.io/5g6ygn) Method 4:[Create INF Files](https://ancheer.sjv.io/y96bgp)**

## **Method 1: Reinstall USB Driver**

Faulty or outdated USB driver can render your USB devices not responding. To fix it: 1) On your keyboard, press the**Windows logo key**and**R**at the same time to invoke a Run command. Type**devmgmt.msc**in and press**Enter**.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59a9230c26f39.png)

2) Expand **Universal Serial Bus controllers**. See if you can a yellow exclamation mark in front of your**Host Controller**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/yellow-exclamation-marks-in-device-manager.jpg) If you cannot see such a device under **Universal Serial Bus controllers**, check if you can see it under**Other devices**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/unknown-device.png) 3) Double-click the device with a yellow exclamation mark. Go to**Driver**, click **Uninstall**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b6c64654e98.png) 4) Check the box for **Delete the driver software for this device**and click **OK.** ![](https://images.drivereasy.com/wp-content/uploads/2016/08/confirm-uninstall.png) 5) Reboot your computer with the USB flash drive connected. See if Microsoft helps you detect and install the new USB driver. If you have more than one**Host Controllers** with the yellow exclamation marks in front, repeat these procedures more than once.

## Method 2: Update USB driver automatically

If Microsoft fails to find the latest version of the USB driver for you, you might need to search for it by yourself. If you don’t have the time, patience or computer skills to update your drivers manually, you can do it automatically with [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/). Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version it takes just 2 clicks (and you get full support and a 30-day money back guarantee): 1)[**Download**](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy. 2) Run Driver Easy and click the**Scan Now**button. Driver Easy will then scan your computer and detect any problem drivers. ![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58e60dbd97325.png) 3) Click the**Update**button next to the flagged USB device to automatically download and install the correct version of this driver (you can do this with the FREE version). Or click**Update All**to automatically download and install the correct version of all the drivers that are missing or out of date on your system (this requires the [**Pro version**](https://tools.techidaily.com/drivereasy/download/)– you’ll be prompted to upgrade when you click Update All). ![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58e60dd5d26f7.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087239/19272" target="_top" id="2087239">
  <img src="//a.impactradius-go.com/display-ad/19272-2087239" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087239/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **Method 3: Remove External Devices**

If there are too many USB devices connected to your PC, some of them might not respond or work properly. To fix it, you can try clean restart your PC: Remove or disconnect all unnecessary discs and devices from your computer. Make sure that the computer is off, and then remove any discs and USB devices and the memory cards from the card reader slot. Disconnect non-essential devices such as camera, MP3-playersprinters, scanners, external hard drives etc., and leave mouse, keyboard and monitor connected. If you are a**laptop**user: 1) Turn off the computer and make sure you have disabled or disconnected all unnecessary external devices. Remove the computer from any port replicator or docking station. 2) Unplug the AC adapter from the computer and remove the battery from the battery compartment. 3) Press and hold the**Power**button for about 15 seconds to drain any residual electrical charge from the capacitors that protect the memory. 4) Insert the battery and AC adapter back into the laptop, but make sure you don’t connect any external devices just yet. 5) Press**Power**button to turn on the computer. Then reconnect the USB devices one by one. If you are using**desktop**: 1) Turn off the computer completely and disconnect the power cord from the back of the computer. 2) Press the power button on the computer for 5 seconds. 3) Reconnect the power cord and turn on the power. Then reconnect the USB devices one by one.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123750/7443" target="_top" id="2123750">
  <img src="//a.impactradius-go.com/display-ad/7443-2123750" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123750/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **Method 4: Create INF Files**

1) Go to**C:\\Windows\\inf**folder. Make sure you can see these files listed: (there could be other files)**usb.inf,** **usb2.inf,** **usbport.inf,** **usbprint.inf,** **usbstor.inf,** **usbvideo.inf** ![](https://images.drivereasy.com/wp-content/uploads/2016/08/usb-inf-file-folder.jpg) 3) If some of the above files are missing, you need to create them. If you have another computer with all the USB ports well functioned, look for the files in that computer, copy and paste them here. 4) If you don’t have another computer, here is the alternative for you. Download the mentioned files from this webpage <http://www.infdump.com/>. You can find the files by searching with the name of the files. Download the files**usb.inf,** **usb2.inf,** **usbport.inf,** **usbprint.inf,** **usbstor.inf,** **usbvideo.inf**, one by one. You can save them directly to the **C:\\Windows\\inf** folder when you are downloading or you can copy them to the**C:\\Windows\\inf** folder all together after you have downloaded all of them. 5) After the files are replaced or created, you need to unplug all of your USB devices and then plug them back in again. If necessary, you can also do a reboot. **Related post:** **[What to do if USB not recognized in Windows 10?](https://tools.techidaily.com/drivereasy/download/)**

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094477/7443" target="_top" id="2094477">
  <img src="//a.impactradius-go.com/display-ad/7443-2094477" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094477/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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



<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://driver-error.techidaily.com/adjustments-made-drivers-updated-system-stable-now/"><u>[ADJUSTMENTS MADE] Drivers Updated, System Stable Now</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixed-wireless-mouse-not-working-on-windows/"><u>[Fixed] Wireless Mouse Not Working on Windows</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-learn-how-to-setup-snapchat-on-a-mac-pc/"><u>[New] 2024 Approved  Learn How to Setup Snapchat on a Mac PC</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-the-inverted-illusion-guide-transforming-visual-content-through-angled-spins/"><u>[New] The Inverted Illusion Guide  Transforming Visual Content Through Angled Spins</u></a></li>
<li><a href="https://driver-error.techidaily.com/rendered-computer-unbootable-post-driver-install-attempt/"><u>[RENDERED] Computer Unbootable Post Driver Install Attempt</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-advanced-ai-for-professional-photography/"><u>2024 Approved  Advanced AI for Professional Photography</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-reel-in-real-time-the-top-5-innovative-recorder-apps-for-browsers/"><u>2024 Approved  Reel in Real-Time  The Top 5 Innovative Recorder Apps for Browsers</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-strategies-for-procuring-high-quality-clip-art-with-no-cost/"><u>2024 Approved  Strategies for Procuring High-Quality Clip Art with No Cost</u></a></li>
<li><a href="https://technical-tips.techidaily.com/a-comprehensive-fix-what-to-do-when-your-zoom-camera-wont-work/"><u>A Comprehensive Fix: What to Do When Your Zoom Camera Won't Work</u></a></li>
<li><a href="https://driver-error.techidaily.com/acpi-driver-fix-for-device-id-33a0/"><u>ACPI Driver Fix for Device ID 33A0</u></a></li>
<li><a href="https://android-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-poco-x6-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Poco X6</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-poco-c50-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Poco C50 Hard Reset | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/bluetooth-woes-for-lenovo-win11-resolution-revealed/"><u>Bluetooth Woes for Lenovo, Win11 Resolution Revealed</u></a></li>
<li><a href="https://driver-error.techidaily.com/bridging-the-gap-seagate-hd-and-win11-detection/"><u>Bridging the Gap: Seagate HD and Win11 Detection</u></a></li>
<li><a href="https://driver-error.techidaily.com/correcting-the-setup-of-your-gadget-overcoming-code-1-hurdles/"><u>Correcting the Setup of Your Gadget - Overcoming Code 1 Hurdles</u></a></li>
<li><a href="https://driver-error.techidaily.com/decoding-the-aged-usb-composite-apparatus-resolved-challenges-and-expert-advice/"><u>Decoding the Aged USB Composite Apparatus: Resolved Challenges and Expert Advice</u></a></li>
<li><a href="https://driver-error.techidaily.com/disc-drives-hidden-windows-11-troubleshooted/"><u>Disc Drives Hidden: Windows 11 Troubleshooted</u></a></li>
<li><a href="https://driver-error.techidaily.com/driving-machine-rejected-by-tech-device/"><u>Driving Machine Rejected by Tech Device</u></a></li>
<li><a href="https://driver-error.techidaily.com/effortless-troubleshooting-for-itbm-driver-not-found-message/"><u>Effortless Troubleshooting for ITBm Driver Not Found Message</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/exploring-the-features-of-the-huion-kamvas-gt-191-drawing-pad-an-in-depth-review/"><u>Exploring the Features of the Huion Kamvas GT-191 Drawing Pad: An In-Depth Review</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-qualcomm-atheros-bluetooth-issues-on-windows-10-complete-solution/"><u>Fixing Qualcomm Atheros Bluetooth Issues on Windows 10: Complete Solution</u></a></li>
<li><a href="https://driver-error.techidaily.com/free-resources-inaccessible-for-device-use/"><u>Free Resources Inaccessible for Device Use</u></a></li>
<li><a href="https://driver-error.techidaily.com/frustration-free-windows-11/"><u>Frustration-Free Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-correct-the-improper-configuration-issue-in-devices-error-101-solution/"><u>How to Correct the 'Improper Configuration' Issue in Devices (Error 101 Solution)</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-honor-magic-5-pro-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Honor Magic 5 Pro? | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-perfecting-auto-captioned-content-in-instagram-reels/"><u>In 2024, Perfecting Auto-Captioned Content in Instagram Reels</u></a></li>
<li><a href="https://driver-error.techidaily.com/nexus-one-non-detection-in-linux-mint-cinnamon-solution-found/"><u>Nexus One Non-Detection in Linux Mint Cinnamon, Solution Found!</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-bluetooth-issues-on-pcs-with-the-latest-os-update-easily-done/"><u>Overcoming Bluetooth Issues on PCs with the Latest OS Update [Easily Done]</u></a></li>
<li><a href="https://driver-error.techidaily.com/quick-fixes-for-the-driver-unavailable-issue-with-the-itbm-tool/"><u>Quick Fixes for the 'Driver Unavailable' Issue with the ITBM Tool</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-gtx-nvidia-950-code-43-issue-in-windows-10-a-comprehensive-guide/"><u>Resolving GTX Nvidia 950 'Code 43' Issue in Windows 10: A Comprehensive Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-realtek-network-issues-in-windows-10/"><u>Resolving Realtek Network Issues in Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-guide-to-fix-an-unresponsive-hp-wireless-keyboard/"><u>Step-by-Step Guide to Fix an Unresponsive HP Wireless Keyboard</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-solution-for-windows-7-blue-screen-error-code-0x0000007e/"><u>Step-by-Step Solution for Windows 7 Blue Screen Error (Code: 0X0000007E)</u></a></li>
<li><a href="https://driver-error.techidaily.com/syncing-sm-bus-controllers-on-windows-1011-platforms/"><u>Syncing SM Bus Controllers on Windows 10/11 Platforms</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-lenovos-bt-error-in-win11-ease/"><u>Troubleshooting Lenovo’s BT Error in Win11 Ease</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-techniques-for-radeon-wattman-resets-to-factory-settings-problems-and-fixes/"><u>Troubleshooting Techniques for 'Radeon WattMan Resets to Factory Settings': Problems & Fixes</u></a></li>
<li><a href="https://driver-error.techidaily.com/ultimate-fixes-overcoming-wireless-keyboard-malfunctions-in-your-windows-workspace/"><u>Ultimate Fixes: Overcoming Wireless Keyboard Malfunctions in Your Windows Workspace</u></a></li>
<li><a href="https://some-guidance.techidaily.com/ultimate-selection-of-economical-4k-projection-screens-for-2024/"><u>Ultimate Selection of Economical 4K Projection Screens for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/understanding-the-legacy-of-usb-composite-devices-a-detailed-explanation/"><u>Understanding the Legacy of USB Composite Devices - A Detailed Explanation</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-based-bluetooth-troubleshooting-tips/"><u>Windows-Based Bluetooth Troubleshooting Tips</u></a></li>
<li><a href="https://driver-error.techidaily.com/winning-against-the-notorious-code-43-error-on-your-gtx-950-while-using-windows-10-a-step-by-step-fix/"><u>Winning Against the Notorious Code 43 Error on Your GTX 950 While Using Windows 10 – A Step-by-Step Fix</u></a></li>
</ul></div>
