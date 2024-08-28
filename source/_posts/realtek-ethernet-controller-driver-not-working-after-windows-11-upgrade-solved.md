---
title: Realtek Ethernet Controller Driver Not Working After Windows 11 Upgrade [Solved]
date: 2024-08-27T06:58:48.082Z
updated: 2024-08-28T06:58:48.082Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Realtek Ethernet Controller Driver Not Working After Windows 11 Upgrade [Solved]
excerpt: This Article Describes Realtek Ethernet Controller Driver Not Working After Windows 11 Upgrade [Solved]
thumbnail: https://thmb.techidaily.com/852437a8f4dc8f33eb3a839d8b7d9a1e3df217c9c33ef7947ef934470397fa43.jpg
---

## Realtek Ethernet Controller Driver Not Working After Windows 11 Upgrade [Solved]

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b91ef1806793.jpg)

 Users have reported that their Realtek PCIe Family Controller (Ethernet) randomly stopped working after they upgraded to Windows 10\. There are still no answers from Microsoft or Realtek as to why would this happen, and this situation happens randomly on different occasions, so there are a lot of solutions that could be of help.

 If this is the problem you are experiencing now, please follow the instructions below to get it fixed by yourself.

[**Option One: Reset TCP/IP**](https://natural-cycles.sjv.io/vmebmr)
[**Option Two: Change Settings in Network Adapter Properties**](https://aofit.pxf.io/mmjyxq)
[**Option Three: Reinstall Realtek Adapter Driver**](https://westkiss.pxf.io/daqnaq)
[**Option Four: Update the Realtek Driver**](https://newchic.sjv.io/jzg4zq)

---

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Option One: Reset TCP/IP**

1) On your keyboard, press the**Windows logo key** , type**cmd** , right-click**Command Prompt** from the results, and select**Run as administrator** .  
  
![how to open Command Prompt as an admin](https://images.drivereasy.com/wp-content/uploads/2023/10/win11-Command-Prompt-Run-as-administrator.jpg)

 When prompted with the following notification, hit**Yes** to continue.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
3) Then right-click Realtek PCIe GBE Family Controller option and choose **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de65b229a9.png)

 4) Go to**Advanced** tab, then choose**Speed & Duplex** option on the left side of the pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de6ed4d026.png)

 5) On the**Value** bar, change the default Auto Negotiation to **100 Mbps Full Duplex**  or some other options accordingly. We chose**100 Mbps Full Duplex** here, but yours could be different.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
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
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

 Hit**OK** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)

 4) Go to the menu bar on the top and click the button for **Scan for hardware changes** .  
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee9a707c2.png)

 5) Windows will help you automatically install the correct driver that it can find. But there is no guarantee that the new driver is going to work since Windows has provided the not working one originally.

 If you clearly remember that your Ethernet stops working after you update to a certain version of the driver, it is suggested that you roll it back to the stage where it was working well.

---

### **Option Four: Update the Realtek Driver**

 The steps above may help you resolve the issue, but if they don’t, you can try to update the Realtek driver. If you don’t have time, patience, or computer skills to update the driver manually,  you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/) .**

**IMPORTANT:**  If you can’t have access to the internet due to the network driver issues, you can use **[Driver Easy Offline Scan Feature](https://tools.techidaily.com/drivereasy/download/)**  to download and install a new network driver.

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version, it takes just 2 clicks (and you get full support and a 30-day money-back guarantee):

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
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
<li><a href="https://driver-error.techidaily.com/fixed-car-load-error-on-gadget/"><u>[Fixed] Car Load Error on Gadget</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixed-dark-light-on-asus-keys/"><u>[FIXED] Dark Light on ASUS Keys</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-tech-savvy-strategies-to-maximize-whiteboard-functionality-across-devices/"><u>[New] 2024 Approved  Tech-Savvy Strategies to Maximize Whiteboard Functionality Across Devices</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-amazon-primes-trending-series-twitters-choice-2023/"><u>[New] Amazon Prime's Trending Series - Twitter's Choice, 2023</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-best-video-recording-gear-guide/"><u>[New] Best Video Recording Gear Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-optimized-bus-controller-in-windows-11/"><u>[SOLVED] Optimized Bus Controller in Windows 11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-watch-unseen-selective-tools-for-insta-enthusiasts/"><u>[Updated] 2024 Approved  Watch Unseen  Selective Tools for Insta Enthusiasts</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-best-unsung-free-speech-to-text-apps-for-your-mac/"><u>[Updated] Best Unsung Free Speech-to-Text Apps for Your Mac</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-digital-dynamo-women-the-fastest-growing-female-channel-owners-for-2024/"><u>[Updated] Digital Dynamo Women  The Fastest-Growing Female Channel Owners for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/warning-bluetooth-mouse-not-initializing-on-pc/"><u>[Warning] Bluetooth Mouse Not Initializing on PC</u></a></li>
<li><a href="https://driver-error.techidaily.com/acemagic-commemorates-may-4th-with-a-special-edition-x-wing-themed-gaming-pc-for-enthusiasts/"><u>AceMagic Commemorates May 4Th with a Special Edition X-Wing Themed Gaming PC for Enthusiasts</u></a></li>
<li><a href="https://driver-error.techidaily.com/disabling-permanent-bluetooth-issue-on-windows-10/"><u>Disabling Permanent Bluetooth Issue on Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/hardware-and-dev-driver-now-in-sync-with-win-os/"><u>Hardware and Dev Driver Now in Sync with Win OS</u></a></li>
<li><a href="https://driver-error.techidaily.com/hardware-now-ready-on-windows/"><u>Hardware Now Ready on Windows</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-prevent-and-solve-obs-frames-skipping-expert-advice/"><u>How to Prevent and Solve OBS Frames Skipping: Expert Advice</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-resolve-dolby-digital-sound-not-working-in-win-10-after-installation-done/"><u>How to Resolve Dolby Digital® Sound Not Working in Win 10 After Installation – Done!✨</u></a></li>
<li><a href="https://network-issues.techidaily.com/improve-windows-graphics-by-installing-current-intel-drivers/"><u>Improve Windows Graphics by Installing Current Intel Drivers</u></a></li>
<li><a href="https://driver-error.techidaily.com/inf-setup-error-now-corrected-and-validated/"><u>INF Setup Error - Now Corrected & Validated</u></a></li>
<li><a href="https://driver-error.techidaily.com/irql-issue-bypassed-in-win11-fix/"><u>Irql Issue Bypassed in Win11 Fix</u></a></li>
<li><a href="https://driver-error.techidaily.com/mended-hardware-commanding-glitches/"><u>Mended Hardware Commanding Glitches</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-get-creative-top-free-mobile-apps-for-adding-video-special-effects-for-2024/"><u>New Get Creative Top Free Mobile Apps for Adding Video Special Effects for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/optical-drive-missing-windows-11-issue-addressed/"><u>Optical Drive Missing: Windows 11 Issue Addressed</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcome-error-48-in-devmgr/"><u>Overcome Error #48 in DevMgr</u></a></li>
<li><a href="https://driver-error.techidaily.com/reactivating-silenced-microphoneheadset-on-windows-10/"><u>Reactivating Silenced Microphone/Headset on Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/restoring-usb-functionality-post-adb-error/"><u>Restoring USB Functionality Post ADB Error</u></a></li>
<li><a href="https://driver-error.techidaily.com/revived-device-manager-error-48/"><u>Revived Device Manager - Error 48</u></a></li>
<li><a href="https://driver-error.techidaily.com/samsung-galaxy-tab-a6-not-recognized-by-arch-linux-fixed-it/"><u>Samsung Galaxy Tab A6 Not Recognized by Arch Linux, Fixed It</u></a></li>
<li><a href="https://driver-error.techidaily.com/seagate-external-drive-detection-issue-solved-in-win11/"><u>Seagate External Drive Detection Issue Solved in Win11</u></a></li>
<li><a href="https://driver-error.techidaily.com/securing-smooth-operation-of-nvidia-drivers/"><u>Securing Smooth Operation of Nvidia Drivers</u></a></li>
<li><a href="https://driver-error.techidaily.com/solutions-what-to-do-when-a-driver-fails-compatibility-check/"><u>Solutions: What to Do When a Driver Fails Compatibility Check</u></a></li>
<li><a href="https://driver-error.techidaily.com/solve-ethernet-adapter-crash-in-thinkcentre-3000/"><u>Solve Ethernet Adapter Crash in ThinkCentre 3000</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-fix-for-uninitialized-directx-device/"><u>Step-by-Step Fix for 'Uninitialized DirectX Device'</u></a></li>
<li><a href="https://driver-error.techidaily.com/steps-to-stabilize-nvidia-graphics-codes/"><u>Steps to Stabilize Nvidia Graphics Codes</u></a></li>
<li><a href="https://driver-error.techidaily.com/the-end-of-the-self-removal-saga-for-nvidia-drivers/"><u>The End of the Self-Removal Saga for Nvidia Drivers</u></a></li>
<li><a href="https://driver-error.techidaily.com/tips-for-fixing-device-conflicts-in-dm/"><u>Tips for Fixing Device Conflicts in DM</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-bluetooth-connectivity-problems-with-qualcomm-on-windows-11-systems/"><u>Troubleshooting Bluetooth Connectivity Problems with Qualcomm on Windows 11 Systems</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-driver-issues-solving-no-driver-found-for-windows-devices-in-versions-11-8-and-7/"><u>Troubleshooting Driver Issues: Solving 'No Driver Found' For Windows Devices in Versions 11, 8 and 7</u></a></li>
<li><a href="https://driver-error.techidaily.com/ultimate-guide-updating-and-downloading-drivers-for-your-hp-envy-20/"><u>Ultimate Guide: Updating and Downloading Drivers for Your HP ENVY 20</u></a></li>
<li><a href="https://apple-account.techidaily.com/unlock-apple-id-without-phone-number-on-apple-iphone-14-by-drfone-ios/"><u>Unlock Apple ID without Phone Number On Apple iPhone 14</u></a></li>
<li><a href="https://driver-error.techidaily.com/unresponsive-keys-issue-in-10/"><u>Unresponsive Keys Issue in 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/usb-drives-vanishing-from-windows-1011/"><u>USB Drives Vanishing From Windows 10/11</u></a></li>
<li><a href="https://driver-error.techidaily.com/why-is-my-seagate-external-not-recognized-by-win11/"><u>Why Is My Seagate External Not Recognized by Win11?</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-troubleshooting-expedite-ndis-fixes/"><u>Windows Troubleshooting: Expedite NDIS Fixes</u></a></li>
</ul></div>
