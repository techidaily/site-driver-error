---
title: Resolving USB Network Driver Not Working After Update
date: 2024-08-15T06:45:05.184Z
updated: 2024-08-16T06:45:05.184Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Resolving USB Network Driver Not Working After Update
excerpt: This Article Describes Resolving USB Network Driver Not Working After Update
thumbnail: https://thmb.techidaily.com/f4b94a6052a83b6c87620891bae2ef1d10a06ae6e718f7d201b09964291e2b88.jpg
---

## Resolving USB Network Driver Not Working After Update

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
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
 2) Locate and click the arrow to expand category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
3) Then right-click Realtek PCIe GBE Family Controller option and choose **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de65b229a9.png)

 4) Go to**Advanced** tab, then choose**Speed & Duplex** option on the left side of the pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de6ed4d026.png)
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->

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
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
 2) Locate and click the arrow to expand the category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)
<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Hit**OK** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->

 4) Go to the menu bar on the top and click the button for **Scan for hardware changes** .  
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee9a707c2.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->

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
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-high-resolution-sky-photography-10-preferred-pages/"><u>[New] 2024 Approved  High-Resolution Sky Photography  10 Preferred Pages</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-streamline-your-information-with-mematics-app/"><u>[New] In 2024, Streamline Your Information with Mematic's App</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-missing-display-on-pcs/"><u>[RESOLVED] Missing Display on PCs</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-usb-30-ports-not-working-after-fresh-windows-install/"><u>[Solved] USB 3.0 Ports Not Working After Fresh Windows Install</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-the-soundtrack-of-successful-snapchat-stories/"><u>[Updated] 2024 Approved  The Soundtrack of Successful Snapchat Stories</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-tips-for-recording-high-quality-mov-video-on-windows-11/"><u>[Updated] In 2024, Tips for Recording High-Quality MOV Video on Windows 11</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-seamless-access-watching-fb-videos-on-apple-tv-explained/"><u>[Updated] Seamless Access  Watching FB Videos on Apple TV Explained</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-the-ultimate-comprehensive-path-to-instagram-riches-for-2024/"><u>[Updated] The Ultimate Comprehensive Path to Instagram Riches for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-direct-to-fans-or-mass-market-twitch-vs-youtube-explored/"><u>2024 Approved  Direct-to-Fans or Mass-Market? Twitch Vs YouTube Explored</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-in-depth-study-of-the-dji-inspire-1-drone/"><u>2024 Approved  In-Depth Study of the DJI Inspire 1 Drone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-navigating-live-broadcast-platforms-simplified/"><u>2024 Approved  Navigating Live Broadcast Platforms Simplified</u></a></li>
<li><a href="https://extra-tips.techidaily.com/accumulating-prime-visuals-for-content-creation/"><u>Accumulating Prime Visuals for Content Creation</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/addressing-stretched-visual-field-in-widescreen-windows-10/"><u>Addressing Stretched Visual Field in Widescreen Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/bring-new-life-to-old-computers-mastering-the-art-of-damn-small-linux-installation/"><u>Bring New Life to Old Computers: Mastering the Art of Damn Small Linux Installation</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/confirmation-techniques-for-youtube-accounts-for-2024/"><u>Confirmation Techniques for Youtube Accounts for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/discovering-the-missed-nvidia-on-pcs/"><u>Discovering the Missed Nvidia on PCs</u></a></li>
<li><a href="https://driver-error.techidaily.com/diy-guide-overcoming-gtx-graphics-problems-error-43-in-windows-11-systems/"><u>DIY Guide: Overcoming GTX Graphics Problems (Error 43) in Windows 11 Systems</u></a></li>
<li><a href="https://driver-error.techidaily.com/driver-alerted-ideport0-control-issue/"><u>Driver Alerted: Ideport0 Control Issue</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/elevate-zooms-audio-tailored-settings-for-immersive-listening-for-2024/"><u>Elevate Zoom's Audio  Tailored Settings for Immersive Listening for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/eliminating-win1011-bus-controllers-faults/"><u>Eliminating Win10/11 Bus Controllers' Faults</u></a></li>
<li><a href="https://driver-error.techidaily.com/ethernet-controller-bug-in-win11-realtek-solution/"><u>Ethernet Controller Bug in Win11 - Realtek Solution</u></a></li>
<li><a href="https://driver-error.techidaily.com/extensive-device-drivers-collection-windows-10-7/"><u>Extensive Device Drivers Collection (Windows 10, 7)</u></a></li>
<li><a href="https://driver-error.techidaily.com/find-and-fix-uninstalled-device-drivers-on-windows-11-8-or-7-step-by-step-tutorial/"><u>Find and Fix Uninstalled Device Drivers on Windows 11, 8 or 7 - Step-by-Step Tutorial</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-qualcomm-atheros-bluetooth-issues-on-windows-10-step-by-step-guide/"><u>Fixing Qualcomm Atheros Bluetooth Issues on Windows 10: Step-by-Step Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-realtek-network-not-operational-in-10/"><u>Fixing Realtek Network Not Operational in 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/get-your-android-on-pc-samsung-edition/"><u>Get Your Android on PC - Samsung Edition</u></a></li>
<li><a href="https://driver-error.techidaily.com/guide-to-restoring-lost-intel-coprocessor-drivers-on-windows-10-devices/"><u>Guide to Restoring Lost Intel Coprocessor Drivers on Windows 10 Devices</u></a></li>
<li><a href="https://driver-error.techidaily.com/high-quality-sound-system-all-good-now/"><u>High-Quality Sound System: All Good Now</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-fix-no-installable-drivers-found-on-windows-1087/"><u>How to Fix 'No Installable Drivers Found' On Windows 10/8/7</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-fix-video-upside-down-issue-on-asus-laptop/"><u>How to Fix Video Upside Down Issue on ASUS Laptop</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-the-iphone-13-pro-sim-lock-4-easy-methods-by-drfone-ios/"><u>In 2024, How To Unlock The iPhone 13 Pro SIM Lock 4 Easy Methods</u></a></li>
<li><a href="https://driver-error.techidaily.com/intermittent-button-presses-windows-mouse-woes/"><u>Intermittent Button Presses - Windows Mouse Woes</u></a></li>
<li><a href="https://driver-error.techidaily.com/iphone-external-storage-troubles-fix-your-usb-mtp-drivers-now/"><u>IPhone External Storage Troubles? Fix Your USB MTP Drivers Now!</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/leading-chat-apps-to-replace-zoom-on-desktopmobile-devices/"><u>Leading Chat Apps to Replace Zoom on Desktop/Mobile Devices</u></a></li>
<li><a href="https://driver-error.techidaily.com/master-the-art-of-bios-tweaking-with-new-razer-deathadder-driver/"><u>Master the Art of BIOS Tweaking with New Razer Deathadder Driver</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/mastering-youtube-images-your-complete-thumbnail-handbook/"><u>Mastering YouTube Images  Your Complete Thumbnail Handbook</u></a></li>
<li><a href="https://driver-error.techidaily.com/my-laptops-built-in-wifibluetooth-is-not-responding-on-windows/"><u>My Laptop’s Built-In Wifi/Bluetooth Is Not Responding on Windows.</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/network-locked-sim-card-inserted-on-your-meizu-21-pro-phone-unlock-it-now-by-drfone-android/"><u>Network Locked SIM Card Inserted On Your Meizu 21 Pro Phone? Unlock It Now</u></a></li>
<li><a href="https://driver-error.techidaily.com/optical-drives-hidden-troubleshooting-guide-for-win11/"><u>Optical Drives Hidden: Troubleshooting Guide for Win11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/premium-3d-playback-with-superior-blu-ray-systems-for-2024/"><u>Premium 3D Playback with Superior Blu-Ray Systems for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/qualcomm-atheros-bluetooth-driver-not-working-on-windows-11-solved/"><u>Qualcomm Atheros Bluetooth Driver Not Working on Windows 11 [Solved]</u></a></li>
<li><a href="https://driver-error.techidaily.com/reinstate-your-pcs-audio-functionality-fixed-troubleshooting-the-non-functioning-dts-truehd-and-e628-solved/"><u>Reinstate Your PC's Audio Functionality, Fixed: Troubleshooting the Non-Functioning DTS™ TrueHD and E628 – Solved! ✅</u></a></li>
<li><a href="https://driver-error.techidaily.com/reinstating-enex-drivers-after-unsuccessful-load-on-windows-11/"><u>Reinstating eNEX Drivers After Unsuccessful Load on Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/revitalizing-faulty-serial-cables-on-win10/"><u>Revitalizing Faulty Serial Cables on Win10</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/social-media-post-resolution-guide/"><u>Social Media Post Resolution Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-fix-for-nonfunctional-qualcomm-atheros-bluetooth-drivers-on-your-windows-10-computer/"><u>Step-by-Step Fix for Nonfunctional Qualcomm Atheros Bluetooth Drivers on Your Windows 10 Computer</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-guide-resolve-usb-access-errors-on-your-computer-system/"><u>Step-by-Step Guide: Resolve USB Access Errors on Your Computer System</u></a></li>
<li><a href="https://tech-haven.techidaily.com/step-by-step-instructions-on-how-to-access-and-install-chatgpts-latest-plug-in-enhancements/"><u>Step-by-Step Instructions on How to Access and Install ChatGPT's Latest Plug-In Enhancements</u></a></li>
<li><a href="https://driver-error.techidaily.com/system-issue-bcm20702a0-hardware-malfunction/"><u>System Issue: BCM20702A0 Hardware Malfunction</u></a></li>
<li><a href="https://driver-error.techidaily.com/tackling-screen-reset-on-windows-10-elan-pad/"><u>Tackling Screen Reset on Windows 10, Elan Pad</u></a></li>
<li><a href="https://driver-error.techidaily.com/unlocking-the-mystery-getting-your-wireless-keyboard-functional-again-on-windows/"><u>Unlocking the Mystery: Getting Your Wireless Keyboard Functional Again on Windows</u></a></li>
<li><a href="https://driver-error.techidaily.com/unsuccessful-graphics-attempt-on-windows-11/"><u>Unsuccessful Graphics Attempt on Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/win11-bluetooth-refuses-to-shutdown/"><u>Win11: Bluetooth Refuses to Shutdown</u></a></li>
<li><a href="https://driver-error.techidaily.com/win11s-disk-space-anomalies-troubleshooting-guide/"><u>Win11's Disk Space Anomalies - Troubleshooting Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/win11s-high-def-audio-triumph/"><u>Win11's High-Def Audio Triumph</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-driver-suites-for-pci-technology/"><u>Windows Driver Suites for PCI Technology</u></a></li>
</ul></div>
