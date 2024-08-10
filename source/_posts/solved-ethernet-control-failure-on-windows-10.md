---
title: Solved Ethernet Control Failure on Windows 10
date: 2024-08-09T08:51:45.376Z
updated: 2024-08-10T08:51:45.376Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Solved Ethernet Control Failure on Windows 10
excerpt: This Article Describes Solved Ethernet Control Failure on Windows 10
thumbnail: https://thmb.techidaily.com/5565177be356d6fd1f6d2b58dc2046c46dae913812fa6d796b06a5e79fd2f303.jpg
---

## Solved Ethernet Control Failure on Windows 10

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de2ea5a2ef.png)

 This will help you reset your TCP/IP (Transmission Control Protocol/Internet Protocol). To make it easier to understand, TCP/IP is the language that your computer uses to communicate with the outside world. Reseting TCP/IP will help you revert your Internet settings to the stage where it still works.

---

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Option Two:** **Change Settings in Network Adapter Properties**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand category**Network adapters** .

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
3) Then right-click Realtek PCIe GBE Family Controller option and choose **Properties** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de65b229a9.png)

 4) Go to**Advanced** tab, then choose**Speed & Duplex** option on the left side of the pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de6ed4d026.png)

 5) On the**Value** bar, change the default Auto Negotiation to **100 Mbps Full Duplex**  or some other options accordingly. We chose**100 Mbps Full Duplex** here, but yours could be different.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deb007e7e1.png)

 6) Now on the left side of the pane, choose**Energy Efficient Ethernet** option, then change the Value to**Disabled** . After the changes, hit**OK** to save.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deab52d9e0.png)

 7) Still, in the**Properties** window, this time, let’s go to**Power Management** tab. Un-tick the box for**Allow the computer to turn off this device to save power** . Then hit**OK** to save and exit.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587decc3276b5.png)

---

### **Option Three:** **Reinstall or Rollback Realtek Adapter Driver**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand the category**Network adapters** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

 Hit**OK** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)

 4) Go to the menu bar on the top and click the button for **Scan for hardware changes** .  
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

![](https://images.drivereasy.com/wp-content/uploads/2023/03/Driver-Easy-download-needed-1200x900.jpg)

 3) Click the **Update** button next to the Realtek PCIe driver to automatically download the correct version of this driver, then you can manually install it (you can do this with the FREE version).

 Or click **Update All**  to automatically download and install the correct version of _all_   the drivers that are missing or out of date on your system (this requires the Pro version – you’ll be prompted to upgrade when you click Update All).

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://facebook-record-videos.techidaily.com/updated-dazzle-and-stand-out-50-free-youtube-branding-pieces/"><u>[Updated] Dazzle and Stand Out  50 FREE YouTube Branding Pieces!</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-maximizing-the-impact-of-outdoor-videos-live-streams-via-periscopefacebook-for-2024/"><u>[Updated] Maximizing the Impact of Outdoor Videos  Live Streams via Periscope/Facebook for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-unlock-potential-in-social-media-storytelling-fb-slideshows/"><u>2024 Approved  Unlock Potential in Social Media Storytelling  FB Slideshows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-motorola-moto-g34-5g-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track Motorola Moto G34 5G without App | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/7-ways-to-unlock-a-locked-motorola-moto-g13-phone-by-drfone-android/"><u>7 Ways to Unlock a Locked Motorola Moto G13 Phone</u></a></li>
<li><a href="https://android-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-motorola-moto-g23-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Motorola Moto G23</u></a></li>
<li><a href="https://tech-hub.techidaily.com/analyzing-the-yin-and-yang-of-ai-and-creativity/"><u>Analyzing the Yin & Yang of AI and Creativity</u></a></li>
<li><a href="https://driver-error.techidaily.com/breaking-barrier-error-52-in-car-systems/"><u>Breaking Barrier Error 52 in Car Systems</u></a></li>
<li><a href="https://extra-resources.techidaily.com/bridge-the-gap-transferring-files-from-pc-to-ios-for-2024/"><u>Bridge the Gap  Transferring Files From PC to iOS for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/ensuring-reliable-sm-bus-driver-on-windows-1011/"><u>Ensuring Reliable SM Bus Driver on Windows 10/11</u></a></li>
<li><a href="https://driver-error.techidaily.com/error-48-cleared-from-device-hub/"><u>Error 48 Cleared From Device Hub</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-usb-code-43-error-easily-with-pictures/"><u>Fix USB Code 43 Error Easily [with Pictures]</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-disappeared-bluetooth-manage-your-devices/"><u>Fixing: Disappeared Bluetooth, Manage Your Devices</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/from-compression-to-clarity-the-zip-srt-conversion-for-2024/"><u>From Compression to Clarity  The ZIP-SRT Conversion for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/hd-drivers-win11-success-story/"><u>HD Drivers: Win11 Success Story</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-fix-your-latest-cam-recognition-issue-post-windows-10-update-solutions-found-fixed/"><u>How to Fix Your Latest Cam Recognition Issue Post Windows 10 Update - Solutions Found [Fixed]</u></a></li>
<li><a href="https://driver-error.techidaily.com/make-your-computer-listen-a-quick-guide-to-fix-unresponsive-bluetooth-on-latest-os-update-guide-inside/"><u>Make Your Computer Listen: A Quick Guide To Fix Unresponsive Bluetooth on Latest OS Update [Guide Inside]</u></a></li>
<li><a href="https://driver-error.techidaily.com/missing-dvdcd-driver-on-win11-fixed/"><u>Missing DVD/CD Driver on Win11? Fixed!</u></a></li>
<li><a href="https://driver-error.techidaily.com/multi-os-pci-hardware-support-tools/"><u>Multi-OS PCI Hardware Support Tools</u></a></li>
<li><a href="https://extra-hints.techidaily.com/must-have-essentials-for-a-starry-drive-with-your-sj4000/"><u>Must-Have Essentials for a Starry Drive with Your SJ4000</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-drive-operation-anomaly/"><u>Resolved Drive Operation Anomaly</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-the-crash-and-reboot-default-radeon-wattman-setting-issue/"><u>Resolving the 'Crash & Reboot: Default Radeon Wattman Setting' Issue</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-windows-keystroke-issues-enter-key/"><u>Resolving Windows Keystroke Issues: Enter Key</u></a></li>
<li><a href="https://driver-error.techidaily.com/resurrecting-disabled-windows-10-usb-earbuds/"><u>Resurrecting Disabled Windows 10 USB Earbuds</u></a></li>
<li><a href="https://driver-error.techidaily.com/smoothing-over-elans-operational-snags-in-win10/"><u>Smoothing Over Elan's Operational Snags in Win10</u></a></li>
<li><a href="https://driver-error.techidaily.com/solve-your-hcmon-driver-problems-effective-fixes-for-installation-errors/"><u>Solve Your HCMon Driver Problems: Effective Fixes for Installation Errors</u></a></li>
<li><a href="https://driver-error.techidaily.com/sound-fix-no-more-driver-trouble-hd/"><u>Sound Fix: No More Driver Trouble (HD)</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-solution-fixing-qualcomm-atheros-bluetooth-connectivity-on-windows-11/"><u>Step-by-Step Solution: Fixing Qualcomm Atheros Bluetooth Connectivity on Windows 11</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-solutions-for-the-mss32dll-is-absent-or-cant-be-found-error/"><u>Step-by-Step Solutions for the 'mss32.dll' Is Absent or Can't Be Found Error</u></a></li>
<li><a href="https://driver-error.techidaily.com/the-companyinfo-given-that-i-want-this-question-forensicinia1098-735-kmkm-so-far-as-to-be-able-to-find-out-which-of-these-numbers-in-i-in-order-for-differen3/"><u>The Company_info = 'Given that I Want This Question. Forensicinia,1098-735 Km/Km, so Far as to Be Able to Find Out Which of These Numbers in (I) In Order for Different Languages</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-your-word-docs-seamlessly-into-pdfs-using-windows-11/"><u>Transform Your Word Docs Seamlessly Into PDFs Using Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/tweak-pointer-efficiency-for-dell-windows/"><u>Tweak Pointer Efficiency for Dell (Windows)</u></a></li>
<li><a href="https://driver-error.techidaily.com/understanding-the-legacy-of-usb-composite-devices-insights-and-solutions/"><u>Understanding the Legacy of USB Composite Devices: Insights and Solutions</u></a></li>
<li><a href="https://driver-error.techidaily.com/usb-speaker-lacks-volume-how-to-fix-it-on-win10/"><u>USB Speaker Lacks Volume - How to Fix It on Win10</u></a></li>
<li><a href="https://driver-error.techidaily.com/wi-fi-6ax201-connectivity-anomaly-addressed-now/"><u>Wi-Fi 6Ax201 Connectivity Anomaly - Addressed Now</u></a></li>
<li><a href="https://driver-error.techidaily.com/win11-install-realtek-ethernet-driver-error-resolved/"><u>Win11 Install: Realtek Ethernet Driver Error Resolved</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-7-bsod-troubleshooting-resolve-error-code-0x0000007e-step-by-step-guide/"><u>Windows 7 BSOD Troubleshooting: Resolve Error Code 0X0000007E Step-by-Step Guide</u></a></li>
</ul></div>
