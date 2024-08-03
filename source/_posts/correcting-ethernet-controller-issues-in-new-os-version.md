---
title: Correcting Ethernet Controller Issues in New OS Version
date: 2024-08-02T07:31:44.933Z
updated: 2024-08-03T07:31:44.933Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Correcting Ethernet Controller Issues in New OS Version
excerpt: This Article Describes Correcting Ethernet Controller Issues in New OS Version
thumbnail: https://thmb.techidaily.com/778dacc021ae6d569afd3e62fa61bf15ba6fe429d937373bba78e772659986e3.jpg
---

## Correcting Ethernet Controller Issues in New OS Version

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b91ef1806793.jpg)

 Users have reported that their Realtek PCIe Family Controller (Ethernet) randomly stopped working after they upgraded to Windows 10\. There are still no answers from Microsoft or Realtek as to why would this happen, and this situation happens randomly on different occasions, so there are a lot of solutions that could be of help.

 If this is the problem you are experiencing now, please follow the instructions below to get it fixed by yourself.

[**Option One: Reset TCP/IP**](https://natural-cycles.sjv.io/vmebmr)
[**Option Two: Change Settings in Network Adapter Properties**](https://aofit.pxf.io/mmjyxq)
[**Option Three: Reinstall Realtek Adapter Driver**](https://westkiss.pxf.io/daqnaq)
[**Option Four: Update the Realtek Driver**](https://newchic.sjv.io/jzg4zq)

---

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
### **Option One: Reset TCP/IP**

1) On your keyboard, press the**Windows logo key** , type**cmd** , right-click**Command Prompt** from the results, and select**Run as administrator** .  
  
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
![how to open Command Prompt as an admin](https://images.drivereasy.com/wp-content/uploads/2023/10/win11-Command-Prompt-Run-as-administrator.jpg)

 When prompted with the following notification, hit**Yes** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de25ac8c94.jpg)

 2) Type in the following command:

netsh int ip reset c:\resetlog.txt

 Make sure that you have made no typo and hit**Enter** .

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de2ea5a2ef.png)

 This will help you reset your TCP/IP (Transmission Control Protocol/Internet Protocol). To make it easier to understand, TCP/IP is the language that your computer uses to communicate with the outside world. Reseting TCP/IP will help you revert your Internet settings to the stage where it still works.

---

### **Option Two:** **Change Settings in Network Adapter Properties**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
3) Then right-click Realtek PCIe GBE Family Controller option and choose **Properties** .

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de65b229a9.png)

 4) Go to**Advanced** tab, then choose**Speed & Duplex** option on the left side of the pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de6ed4d026.png)

 5) On the**Value** bar, change the default Auto Negotiation to **100 Mbps Full Duplex**  or some other options accordingly. We chose**100 Mbps Full Duplex** here, but yours could be different.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deb007e7e1.png)

 6) Now on the left side of the pane, choose**Energy Efficient Ethernet** option, then change the Value to**Disabled** . After the changes, hit**OK** to save.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deab52d9e0.png)

 7) Still, in the**Properties** window, this time, let’s go to**Power Management** tab. Un-tick the box for**Allow the computer to turn off this device to save power** . Then hit**OK** to save and exit.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587decc3276b5.png)

---

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
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

![](https://images.drivereasy.com/wp-content/uploads/2023/03/Driver-Easy-download-needed-1200x900.jpg)

 3) Click the **Update** button next to the Realtek PCIe driver to automatically download the correct version of this driver, then you can manually install it (you can do this with the FREE version).

 Or click **Update All**  to automatically download and install the correct version of _all_   the drivers that are missing or out of date on your system (this requires the Pro version – you’ll be prompted to upgrade when you click Update All).

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
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
<li><a href="https://driver-error.techidaily.com/fixed-amd-software-has-stopped-working/"><u>[Fixed] AMD Software Has Stopped Working</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-discover-11-leading-streamers-audio-recorders-for-2024/"><u>[New] Discover 11 Leading Streamers' Audio Recorders for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-master-facebooks-live-broadcast-for-2024/"><u>[New] Master Facebook's Live Broadcast for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-unleashing-virality-steps-to-skyrocket-your-instagram-content/"><u>[Updated] 2024 Approved  Unleashing Virality  Steps to Skyrocket Your Instagram Content</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-guide-to-reinventing-facebook-video-coverages-step-by-step-for-2024/"><u>[Updated] Guide to Reinventing Facebook Video Coverages  Step-by-Step for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-2023s-ultimate-guide-apeaksoft-screen-capture-tech-unveiled/"><u>[Updated] In 2024, 2023'S Ultimate Guide  Apeaksoft Screen Capture Tech Unveiled</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-control-youtube-audio-mobiledesktop-approach/"><u>[Updated] In 2024, Control YouTube Audio  Mobile/Desktop Approach</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-how-to-use-aiseesoft-screen-recorder/"><u>[Updated] In 2024, How to Use Aiseesoft Screen Recorder</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-kickstart-a-successful-charity-contest-via-social-media/"><u>[Updated] Kickstart a Successful Charity Contest via Social Media</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-advanced-tips-perfecting-photos-with-onscreen-cropping/"><u>2024 Approved  Advanced Tips  Perfecting Photos with Onscreen Cropping</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-elevate-your-learning-and-work-habits-top-ideas-for-combining-tasks-with-podcasts/"><u>2024 Approved  Elevate Your Learning & Work Habits  Top Ideas for Combining Tasks with Podcasts</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-ultimate-guide-to-fostering-viewer-commitment-in-youtube-videos/"><u>2024 Approved  The Ultimate Guide to Fostering Viewer Commitment in YouTube Videos</u></a></li>
<li><a href="https://driver-error.techidaily.com/bypassing-the-code-43-hurdle-effective-fixes-for-gtx-950-on-windows-10-systems/"><u>Bypassing the 'Code 43' Hurdle: Effective Fixes for GTX 950 on Windows 10 Systems</u></a></li>
<li><a href="https://driver-error.techidaily.com/corrected-audio-driver-on-hidef-bus/"><u>Corrected Audio Driver on HiDef Bus</u></a></li>
<li><a href="https://driver-error.techidaily.com/easy-steps-install-latest-drivers-on-your-hp-envy-151720-laptop/"><u>Easy Steps: Install Latest Drivers on Your HP ENVY 15/17/20 Laptop</u></a></li>
<li><a href="https://driver-error.techidaily.com/effective-solutions-to-fix-a-malfunctioned-usb-recognition-issue-in-windows-os/"><u>Effective Solutions to Fix a Malfunctioned USB Recognition Issue in Windows OS</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-code-43-error-windows-has-stopped-this-device-because-it-has-reported-problems/"><u>Fix Code 43 Error: Windows Has Stopped This Device because It Has Reported Problems</u></a></li>
<li><a href="https://driver-error.techidaily.com/from-obsolete-to-essential-the-transformation-and-importance-of-usb-composite-devices-nowad-resolved/"><u>From Obsolete to Essential: The Transformation and Importance of USB Composite Devices Nowad [RESOLVED]</u></a></li>
<li><a href="https://driver-error.techidaily.com/graphics-illustration-of-ms-bda/"><u>Graphics Illustration of MS BDA</u></a></li>
<li><a href="https://driver-error.techidaily.com/gtx-ninety-five-error-code-43-issue-solved-for-windows-eleven-enthusiasts/"><u>GTX Ninety-Five 'Error Code 43' Issue: Solved for Windows Eleven Enthusiasts</u></a></li>
<li><a href="https://driver-error.techidaily.com/guide-to-fix-video-playback-reversed-horizontally-on-asus-laptops/"><u>Guide to Fix Video Playback Reversed Horizontally on ASUS Laptops</u></a></li>
<li><a href="https://driver-error.techidaily.com/hidef-audio-system-error-corrected/"><u>HiDef Audio System: Error Corrected</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-deal-with-a-code-forty-three-malfunction-on-your-gtx-ninety-five-and-windows-eleven/"><u>How To Deal With A Code Forty-Three Malfunction On Your GTX Ninety-Five And Windows Eleven</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fake-gps-on-infinix-hot-30-5g-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>How To Fake GPS On Infinix Hot 30 5G For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-fix-imaging-devices-missing-in-windows-11/"><u>How To Fix Imaging Devices Missing in Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-identify-and-fix-missing-seagate-hd-on-pc/"><u>How To Identify & Fix Missing Seagate HD on PC</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-zte-axon-40-lite-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your ZTE Axon 40 Lite</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-frp-from-xiaomi-mix-fold-3-by-drfone-android/"><u>In 2024, How to Bypass FRP from Xiaomi Mix Fold 3?</u></a></li>
<li><a href="https://driver-error.techidaily.com/locating-opengl-drivers-within-intels-sdk/"><u>Locating OpenGL Drivers Within Intel's SDK</u></a></li>
<li><a href="https://driver-error.techidaily.com/master-upgrading-driver-versions-a-comprehvew-for-owners-of-hp-envy-20-pcs-and-laptops/"><u>Master Upgrading Driver Versions: A Comprehvew for Owners of HP ENVY 20 PCs and Laptops</u></a></li>
<li><a href="https://driver-error.techidaily.com/operating-system-keys-unresponsive/"><u>Operating System: Keys Unresponsive</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-intel-management-engine-hurdles/"><u>Overcoming Intel Management Engine Hurdles</u></a></li>
<li><a href="https://extra-tips.techidaily.com/premium-listing-combining-global-network-and-neighborhood-channels-2024/"><u>Premium Listing  Combining Global Network & Neighborhood Channels, 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/preventing-maximum-disk-usage-on-win11-taskbar/"><u>Preventing Maximum Disk Usage on Win11 Taskbar</u></a></li>
<li><a href="https://driver-error.techidaily.com/quick-guide-tackling-windows-10s-asus-drivers/"><u>Quick Guide: Tackling Windows 10'S Asus Drivers</u></a></li>
<li><a href="https://driver-error.techidaily.com/quick-steps-to-resolve-faulty-mtp-usb/"><u>Quick Steps to Resolve Faulty MTP USB</u></a></li>
<li><a href="https://driver-error.techidaily.com/rapid-recovery-path-fixing-broken-mtp-drivers/"><u>Rapid Recovery Path: Fixing Broken MTP Drivers</u></a></li>
<li><a href="https://driver-error.techidaily.com/reconnecting-disabled-usb-gadgets-windows-fixes-guide/"><u>Reconnecting Disabled USB Gadgets: Windows Fixes Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-device-hub-showstopper-45/"><u>Resolved: Device Hub Showstopper #45</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-amd-radeon-wattman-malfunction-crashed-and-restored-expert-troubleshooting-guide/"><u>Resolving AMD Radeon Wattman Malfunction: Crashed and Restored - Expert Troubleshooting Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/revive-nonresponsive-serial-ports-on-os-windows/"><u>Revive Nonresponsive Serial Ports on OS WINDOWS</u></a></li>
<li><a href="https://driver-error.techidaily.com/solution-steps-for-the-critical-bsod-error-0x0000007e-on-your-windows-7-pc/"><u>Solution Steps for the Critical BSOD Error 0X0000007E on Your Windows 7 PC</u></a></li>
<li><a href="https://driver-error.techidaily.com/solutions-for-handling-unrecognized-hardware-messages-by-idt-software-products/"><u>Solutions for Handling Unrecognized Hardware Messages by IDT Software Products</u></a></li>
<li><a href="https://driver-error.techidaily.com/solutions-for-installing-drivers-that-arent-compatible-with-your-system/"><u>Solutions for Installing Drivers That Aren't Compatible with Your System</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-guide-updating-and-downloading-drivers-for-your-hp-envy-m6-spectre-x360/"><u>Step-by-Step Guide: Updating and Downloading Drivers for Your HP ENVY M6 Spectre X360</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-realme-12-5g-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Realme 12 5G? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-vivo-y100i-power-5g-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Vivo Y100i Power 5G? | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-error-messages-successfully-installing-incompatible-drivers/"><u>Troubleshooting Error Messages: Successfully Installing Incompatible Drivers</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-guide-fixing-initialization-issues-with-battleye-service-and-overcoming-driver-loading-errors/"><u>Troubleshooting Guide: Fixing Initialization Issues with BattlEye Service and Overcoming Driver Loading Errors</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-guide-resolving-non-functional-bluetooth-drivers-by-qualcomm-atheros-on-windows-10/"><u>Troubleshooting Guide: Resolving Non-Functional Bluetooth Drivers by Qualcomm Atheros on Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/win-printer-drivers-found-and-fixed/"><u>Win Printer Drivers - Found & Fixed</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-10-unable-to-stop-bluetooth-from-working/"><u>Windows 10: Unable to Stop Bluetooth From Working.</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-users-solve-your-wireless-keyboard-problem-today/"><u>Windows Users: Solve Your Wireless Keyboard Problem Today</u></a></li>
</ul></div>
