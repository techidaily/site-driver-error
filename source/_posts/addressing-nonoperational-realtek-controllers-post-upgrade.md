---
title: Addressing Nonoperational Realtek Controllers Post-Upgrade
date: 2024-08-02T07:32:02.802Z
updated: 2024-08-03T07:32:02.802Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Addressing Nonoperational Realtek Controllers Post-Upgrade
excerpt: This Article Describes Addressing Nonoperational Realtek Controllers Post-Upgrade
thumbnail: https://thmb.techidaily.com/5f042bcf8e18adcc53cbb8d889707c4f827028b312f2b21172b0735c2d2d47e0.jpeg
---

## Addressing Nonoperational Realtek Controllers Post-Upgrade

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de2ea5a2ef.png)

 This will help you reset your TCP/IP (Transmission Control Protocol/Internet Protocol). To make it easier to understand, TCP/IP is the language that your computer uses to communicate with the outside world. Reseting TCP/IP will help you revert your Internet settings to the stage where it still works.

---

### **Option Two:** **Change Settings in Network Adapter Properties**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand category**Network adapters** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
3) Then right-click Realtek PCIe GBE Family Controller option and choose **Properties** .

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de65b229a9.png)

 4) Go to**Advanced** tab, then choose**Speed & Duplex** option on the left side of the pane.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de6ed4d026.png)

 5) On the**Value** bar, change the default Auto Negotiation to **100 Mbps Full Duplex**  or some other options accordingly. We chose**100 Mbps Full Duplex** here, but yours could be different.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deb007e7e1.png)

 6) Now on the left side of the pane, choose**Energy Efficient Ethernet** option, then change the Value to**Disabled** . After the changes, hit**OK** to save.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deab52d9e0.png)

 7) Still, in the**Properties** window, this time, let’s go to**Power Management** tab. Un-tick the box for**Allow the computer to turn off this device to save power** . Then hit**OK** to save and exit.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587decc3276b5.png)

---

### **Option Three:** **Reinstall or Rollback Realtek Adapter Driver**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand the category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

 Hit**OK** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)

 4) Go to the menu bar on the top and click the button for **Scan for hardware changes** .  
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee9a707c2.png)

 5) Windows will help you automatically install the correct driver that it can find. But there is no guarantee that the new driver is going to work since Windows has provided the not working one originally.

 If you clearly remember that your Ethernet stops working after you update to a certain version of the driver, it is suggested that you roll it back to the stage where it was working well.

---

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Option Four: Update the Realtek Driver**

 The steps above may help you resolve the issue, but if they don’t, you can try to update the Realtek driver. If you don’t have time, patience, or computer skills to update the driver manually,  you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/) .**

**IMPORTANT:**  If you can’t have access to the internet due to the network driver issues, you can use **[Driver Easy Offline Scan Feature](https://tools.techidaily.com/drivereasy/download/)**  to download and install a new network driver.

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version, it takes just 2 clicks (and you get full support and a 30-day money-back guarantee):

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-insta-cover-chronicles-top-tier-tech-edition/"><u>[New] 2024 Approved  Insta Cover Chronicles  Top-Tier Tech Edition</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-intel-wireless-ac-9560-not-working-code-10/"><u>[SOLVED] Intel Wireless-AC 9560 Not Working (Code 10)</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-how-to-fix-full-screen-error-in-obs/"><u>[Updated] 2024 Approved  How to Fix Full Screen Error in OBS</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-stardews-guide-ginger-isle-essentials/"><u>[Updated] 2024 Approved  Stardew's Guide  Ginger Isle Essentials</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-prime-microphones-for-high-resolution-4k-video-shooting/"><u>[Updated] Prime Microphones for High-Resolution 4K Video Shooting</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-a-friendly-tour-how-to-join-and-chill-with-peers-live-on-tiktok/"><u>2024 Approved  A Friendly Tour  How To Join and Chill with Peers Live on TikTok</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-affordable-wonders-in-virtual-reality-headsets-from-china/"><u>2024 Approved  Affordable Wonders in Virtual Reality Headsets From China</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-meme-mastery-money-making-the-financial-figures-of-a-video-virtuoso/"><u>2024 Approved  Meme Mastery Money-Making  The Financial Figures of a Video Virtuoso</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-step-by-step-guide-instal-subtitles-on-mediaplayer/"><u>2024 Approved  Step-by-Step Guide  Instal Subtitles on MediaPlayer</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-top-2-secrets-to-convert-instagram-videos-into-premium-mp4/"><u>2024 Approved  Top 2 Secrets to Convert Instagram Videos Into Premium MP4</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/8-best-apps-for-screen-mirroring-motorola-defy-2-pc-drfone-by-drfone-android/"><u>8 Best Apps for Screen Mirroring Motorola Defy 2 PC | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/addressing-win10-asus-driver-and-acpi/"><u>Addressing Win10: Asus Driver and ACPI</u></a></li>
<li><a href="https://driver-error.techidaily.com/bluetooth-enabling-for-lenovo-on-win11-platform/"><u>Bluetooth Enabling for Lenovo on Win11 Platform</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-i-recover-permanently-deleted-photos-from-130-music-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>Can I recover permanently deleted photos from 130 Music</u></a></li>
<li><a href="https://driver-error.techidaily.com/common-problems-with-hp-wireless-peripherals-diagnosis-and-repair-tips/"><u>Common Problems with HP Wireless Peripherals: Diagnosis & Repair Tips</u></a></li>
<li><a href="https://driver-error.techidaily.com/driver-failure-intel-hardware-missing/"><u>Driver Failure: Intel Hardware Missing</u></a></li>
<li><a href="https://driver-error.techidaily.com/elevate-razer-hats-update-driver-in-win11-platform/"><u>Elevate Razer HATs: Update Driver in Win11 Platform</u></a></li>
<li><a href="https://driver-error.techidaily.com/error-rectified-hd-audio-bus/"><u>Error Rectified: HD Audio Bus</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-vivo-y27-5g-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on Vivo Y27 5G | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixed-invalid-inf-for-service-installation/"><u>Fixed Invalid INF for Service Installation</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-the-iphone-mobile-host-controller-driver-problem-a-step-by-step-guide/"><u>Fixing the iPhone Mobile Host Controller Driver Problem: A Step-by-Step Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/graphics-hardware-blockage-for-windows-10-system/"><u>Graphics Hardware Blockage for Windows 10 System</u></a></li>
<li><a href="https://driver-error.techidaily.com/guide-to-repairing-aged-usb-composite-device-connectivity-concerns-and-errors/"><u>Guide to Repairing Aged USB Composite Device Connectivity Concerns and Errors</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-guide-to-mirror-your-oppo-a38-to-other-android-devices-drfone-by-drfone-android/"><u>In 2024, Guide to Mirror Your Oppo A38 to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-how-to-make-vimeo-videos/"><u>In 2024, How to Make Vimeo Videos</u></a></li>
<li><a href="https://driver-error.techidaily.com/journey-through-time-demystifying-and-fixing-age-old-usb-composite-device-issues/"><u>Journey Through Time: Demystifying and Fixing Age-Old USB Composite Device Issues</u></a></li>
<li><a href="https://driver-error.techidaily.com/keyboard-stuck-on-windows-10/"><u>Keyboard Stuck on Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-the-common-device-setup-issue-code-1-not-configured-correctly-in-brand/"><u>Overcoming the Common Device Setup Issue (Code 1 Not Configured Correctly) in [Brand]</u></a></li>
<li><a href="https://driver-error.techidaily.com/put-an-end-to-self-removing-nvidia-drivers/"><u>Put an End to Self-Removing Nvidia Drivers</u></a></li>
<li><a href="https://driver-error.techidaily.com/quick-method-to-solve-the-broken-key-issue-on-your-hp-notebooks-detailed-steps-included-article-title-407-chars/"><u>Quick Method to Solve the 'Broken' Key Issue on Your HP Notebooks — Detailed Steps Included! - Article Title (407 Chars)</u></a></li>
<li><a href="https://driver-error.techidaily.com/reintroduce-hidden-dvds-to-windows-os/"><u>Reintroduce Hidden DVDs to Windows OS</u></a></li>
<li><a href="https://driver-error.techidaily.com/restore-your-control-the-ultimate-guide-for-effortlessly-fixing-unresponsive-bluetech-in-windows-11-fix-revealed/"><u>Restore Your Control: The Ultimate Guide for Effortlessly Fixing Unresponsive BlueTech in Windows 11 (Fix Revealed)</u></a></li>
<li><a href="https://driver-error.techidaily.com/samsung-system-files-windows-download/"><u>Samsung System Files - Windows Download</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-guide-correcting-the-failed-to-install-hcmon-driver-error/"><u>Step-by-Step Guide: Correcting the 'Failed to Install Hcmon Driver Error'</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-solution-for-battleye-initialization-failure-due-to-driver-loading-problems/"><u>Step-by-Step Solution for BattlEye Initialization Failure Due to Driver Loading Problems</u></a></li>
<li><a href="https://driver-error.techidaily.com/strategies-to-overcome-base-driver-issues-dm/"><u>Strategies to Overcome Base Driver Issues (DM)</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-and-solving-qualcomm-atheros-bluetooth-driver-problems-in-windows-11/"><u>Troubleshooting and Solving Qualcomm Atheros Bluetooth Driver Problems in Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/turn-off-stubborn-bluetooth-on-windows-10-answer/"><u>Turn Off Stubborn Bluetooth on Windows 10 [Answer]</u></a></li>
<li><a href="https://driver-error.techidaily.com/win-os-now-recognizes-latest-printer-hardware/"><u>Win OS Now Recognizes Latest Printer Hardware</u></a></li>
</ul></div>
