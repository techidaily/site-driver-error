---
title: Fixing Realtek's Nonfunctional Interface After Upgrade
date: 2024-08-15T06:37:00.162Z
updated: 2024-08-16T06:37:00.162Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Fixing Realtek's Nonfunctional Interface After Upgrade
excerpt: This Article Describes Fixing Realtek's Nonfunctional Interface After Upgrade
thumbnail: https://thmb.techidaily.com/de7e32da454b1a64d1a9e174bd2f0af6c1c09ee741804b69375cf4ed02faf5de.jpg
---

## Fixing Realtek's Nonfunctional Interface After Upgrade

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b91ef1806793.jpg)

 Users have reported that their Realtek PCIe Family Controller (Ethernet) randomly stopped working after they upgraded to Windows 10\. There are still no answers from Microsoft or Realtek as to why would this happen, and this situation happens randomly on different occasions, so there are a lot of solutions that could be of help.

 If this is the problem you are experiencing now, please follow the instructions below to get it fixed by yourself.

[**Option One: Reset TCP/IP**](https://natural-cycles.sjv.io/vmebmr)
[**Option Two: Change Settings in Network Adapter Properties**](https://aofit.pxf.io/mmjyxq)
[**Option Three: Reinstall Realtek Adapter Driver**](https://westkiss.pxf.io/daqnaq)
[**Option Four: Update the Realtek Driver**](https://newchic.sjv.io/jzg4zq)

---

### **Option One: Reset TCP/IP**

1) On your keyboard, press the**Windows logo key** , type**cmd** , right-click**Command Prompt** from the results, and select**Run as administrator** .  
  
![how to open Command Prompt as an admin](https://images.drivereasy.com/wp-content/uploads/2023/10/win11-Command-Prompt-Run-as-administrator.jpg)

 When prompted with the following notification, hit**Yes** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de25ac8c94.jpg)

 2) Type in the following command:

netsh int ip reset c:\resetlog.txt

 Make sure that you have made no typo and hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de2ea5a2ef.png)

 This will help you reset your TCP/IP (Transmission Control Protocol/Internet Protocol). To make it easier to understand, TCP/IP is the language that your computer uses to communicate with the outside world. Reseting TCP/IP will help you revert your Internet settings to the stage where it still works.

---

### **Option Two:** **Change Settings in Network Adapter Properties**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
3) Then right-click Realtek PCIe GBE Family Controller option and choose **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de65b229a9.png)

 4) Go to**Advanced** tab, then choose**Speed & Duplex** option on the left side of the pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de6ed4d026.png)

 5) On the**Value** bar, change the default Auto Negotiation to **100 Mbps Full Duplex**  or some other options accordingly. We chose**100 Mbps Full Duplex** here, but yours could be different.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deb007e7e1.png)

 6) Now on the left side of the pane, choose**Energy Efficient Ethernet** option, then change the Value to**Disabled** . After the changes, hit**OK** to save.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deab52d9e0.png)

 7) Still, in the**Properties** window, this time, let’s go to**Power Management** tab. Un-tick the box for**Allow the computer to turn off this device to save power** . Then hit**OK** to save and exit.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587decc3276b5.png)

---

### **Option Three:** **Reinstall or Rollback Realtek Adapter Driver**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand the category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

 Hit**OK** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)

 4) Go to the menu bar on the top and click the button for **Scan for hardware changes** .  
<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee9a707c2.png)

 5) Windows will help you automatically install the correct driver that it can find. But there is no guarantee that the new driver is going to work since Windows has provided the not working one originally.

 If you clearly remember that your Ethernet stops working after you update to a certain version of the driver, it is suggested that you roll it back to the stage where it was working well.

---

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
### **Option Four: Update the Realtek Driver**

 The steps above may help you resolve the issue, but if they don’t, you can try to update the Realtek driver. If you don’t have time, patience, or computer skills to update the driver manually,  you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/) .**

**IMPORTANT:**  If you can’t have access to the internet due to the network driver issues, you can use **[Driver Easy Offline Scan Feature](https://tools.techidaily.com/drivereasy/download/)**  to download and install a new network driver.

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version, it takes just 2 clicks (and you get full support and a 30-day money-back guarantee):

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/03/Driver-Easy-download-needed-1200x900.jpg)

 3) Click the **Update** button next to the Realtek PCIe driver to automatically download the correct version of this driver, then you can manually install it (you can do this with the FREE version).

 Or click **Update All**  to automatically download and install the correct version of _all_   the drivers that are missing or out of date on your system (this requires the Pro version – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2020/11/update-network-adapter-driver.jpg)

 Hopefully the tips above help you fix the Realtek Ethernet Controller driver not working issue. If you have any questions or ideas, feel free to leave your comments below, please.

* [Realtek](https://store.drivereasy.com/order/cart.php?PRODS=4731822&QTY=1&AFFILIATE=108875)

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
<li><a href="https://driver-error.techidaily.com/fixed-drivers-installation-failed-completely/"><u>[FIXED] Drivers Installation Failed Completely</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-elevate-your-contents-visibility-strategic-use-of-imagery-in-video-thumbnails/"><u>[New] In 2024, Elevate Your Content's Visibility  Strategic Use of Imagery in Video Thumbnails</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-outrageous-odyssey-your-roadmap-to-the-funniest-tiktok-challenges/"><u>[New] Outrageous Odyssey  Your Roadmap to the Funniest TikTok Challenges</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-elevating-your-content-creation-leveraging-vimeo-recorder/"><u>[Updated] Elevating Your Content Creation  Leveraging Vimeo Recorder</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-capturing-counter-strike-global-offensive-play-seamlessly/"><u>2024 Approved  Capturing Counter-Strike  Global Offensive Play Seamlessly</u></a></li>
<li><a href="https://fox-access.techidaily.com/a-comprehensive-list-of-15-competitors-to-gopro-cameras/"><u>A Comprehensive List of 15 Competitors to GoPro Cameras</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/chronic-removal-method-for-youtubes-bite-sized-videos/"><u>Chronic Removal Method for YouTube's Bite-Sized Videos</u></a></li>
<li><a href="https://driver-error.techidaily.com/driver-installation-failure-intel-card-missing/"><u>Driver Installation Failure - Intel Card Missing</u></a></li>
<li><a href="https://driver-error.techidaily.com/enhancing-win1110s-sm-bus-driver-reliability/"><u>Enhancing WIN11/10's Sm Bus Driver Reliability</u></a></li>
<li><a href="https://driver-error.techidaily.com/expert-tips-enabling-safe-mode-and-ejecting-video-card-drivers-in-windows-8-for-a-smooth-computing-experience/"><u>Expert Tips: Enabling Safe Mode & Ejecting Video Card Drivers in Windows 8 for a Smooth Computing Experience</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/from-footage-to-frame-crafting-youtube-thumbnails-on-mobile-devices/"><u>From Footage to Frame  Crafting YouTube Thumbnails on Mobile Devices</u></a></li>
<li><a href="https://android-unlock.techidaily.com/full-guide-to-unlock-your-motorola-moto-g73-5g-by-drfone-android/"><u>Full Guide to Unlock Your Motorola Moto G73 5G</u></a></li>
<li><a href="https://driver-error.techidaily.com/get-mobile-access-to-samsung-os-for-pc/"><u>Get Mobile Access to Samsung OS for PC</u></a></li>
<li><a href="https://driver-error.techidaily.com/guide-disabling-graphics-card-on-windows-8-via-safe-mode-deletion/"><u>Guide: Disabling Graphics Card on Windows 8 via Safe Mode Deletion</u></a></li>
<li><a href="https://driver-error.techidaily.com/hardware-unlock-access-denied-on-win11/"><u>Hardware Unlock: Access Denied on Win11</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-can-we-bypass-poco-frp-by-drfone-android/"><u>How Can We Bypass Poco FRP?</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-detect-and-connect-overlooked-seagate-drive-in-w10/"><u>How To Detect & Connect Overlooked Seagate Drive in W10</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-fix-unable-to-initialize-directx-9-device-in-5-easy-steps/"><u>How to Fix ‘Unable to Initialize DirectX 9 Device’ in 5 Easy Steps</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-fix-the-last-usb-device-malfunctioned-and-windows-doesnt-recognize-it/"><u>How to Fix The Last USB Device Malfunctioned and Windows Doesn’t Recognize It</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-free-location-spoofers-to-fake-gps-location-on-your-samsung-galaxy-s23-fe-drfone-by-drfone-virtual/"><u>In 2024, 10 Free Location Spoofers to Fake GPS Location on your Samsung Galaxy S23 FE | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-dose-life360-notify-me-when-someone-checks-my-location-on-apple-iphone-8-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, Dose Life360 Notify Me When Someone Checks My Location On Apple iPhone 8 Plus? | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-leaders-in-learning-select-sci-yt-channels/"><u>In 2024, Leaders in Learning  Select Sci-YT Channels</u></a></li>
<li><a href="https://driver-error.techidaily.com/keeping-up-to-date-the-guide-to-installing-deadriver-on-windows-10/"><u>Keeping Up-to-Date: The Guide to Installing DeaDriver on Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/long-hours-no-pain-a-closer-look-at-the-ergohead-standing-desk-mat-experience/"><u>Long Hours, No Pain: A Closer Look at the ErgoHead Standing Desk Mat Experience</u></a></li>
<li><a href="https://driver-error.techidaily.com/mastering-iphone-file-transfer-overcoming-usb-connectivity-challenges/"><u>Mastering iPhone File Transfer: Overcoming USB Connectivity Challenges</u></a></li>
<li><a href="https://driver-error.techidaily.com/mending-the-disappearing-touchpad-driver-problem/"><u>Mending the Disappearing Touchpad Driver Problem</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcome-auto-uninstall-anomaly-in-nvidia-driver/"><u>Overcome Auto-Uninstall Anomaly in Nvidia Driver</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-the-unmountable-boot-volume-bug-error-0x0000007e-in-your-windows-vista7-pc/"><u>Overcoming the Unmountable Boot Volume Bug (Error 0X0000007E) in Your Windows Vista/7 PC</u></a></li>
<li><a href="https://driver-error.techidaily.com/pci-missing-hardware-issue-windows-fix/"><u>PCI Missing Hardware Issue: Windows Fix</u></a></li>
<li><a href="https://driver-error.techidaily.com/preventing-problematic-sm-bus-controllers-in-windows-1011/"><u>Preventing Problematic SM Bus Controllers in Windows 10/11</u></a></li>
<li><a href="https://driver-error.techidaily.com/qualcomm-atheros-and-windows-11-effective-solutions-for-faulty-bluetooth-drivers/"><u>Qualcomm Atheros & Windows 11: Effective Solutions for Faulty Bluetooth Drivers</u></a></li>
<li><a href="https://driver-error.techidaily.com/rectification-of-service-section-in-inf-file/"><u>Rectification of Service Section in INF File</u></a></li>
<li><a href="https://driver-error.techidaily.com/repair-your-qualcomm-atheros-bluetooth-connection-on-windows-10-easy-fixes-revealed/"><u>Repair Your Qualcomm Atheros Bluetooth Connection on Windows 10 - Easy Fixes Revealed</u></a></li>
<li><a href="https://driver-error.techidaily.com/simplified-troubleshoot-for-mtp-drivers/"><u>Simplified Troubleshoot for MTP Drivers</u></a></li>
<li><a href="https://driver-error.techidaily.com/sound-system-error-no-more-hd/"><u>Sound System Error No More! (HD)</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-resolving-windows-update-defeat-error-0x800736cc/"><u>Swiftly Resolving Windows Update: Defeat Error 0X800736CC</u></a></li>
<li><a href="https://driver-error.techidaily.com/toms-innovative-solutions-a-closer-look-at-cutting-edge-hardware/"><u>Tom’s Innovative Solutions: A Closer Look at Cutting-Edge Hardware</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-driver-installation-for-windows-devices-windows-10-8-and-7-tips/"><u>Troubleshooting Driver Installation for Windows Devices: Windows 10, 8 & 7 Tips</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-invalid-driver-installs-how-to-ensure-device-compatibility/"><u>Troubleshooting Invalid Driver Installs: How to Ensure Device Compatibility</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-fixing-unsupported-device-detected-by-software-package-issues/"><u>Troubleshooting: Fixing 'Unsupported Device Detected' By Software Package Issues</u></a></li>
<li><a href="https://driver-error.techidaily.com/understanding-and-fixing-incorrect-device-configuration-overcoming-code-1-problems/"><u>Understanding and Fixing Incorrect Device Configuration: Overcoming Code 1 Problems</u></a></li>
<li><a href="https://driver-error.techidaily.com/win10-audio-device-issue-resolved-usb-headset/"><u>Win10 Audio Device Issue: Resolved USB Headset</u></a></li>
</ul></div>
