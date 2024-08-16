---
title: Overcoming Windows 10 Impact on Ethernet Driver
date: 2024-08-15T06:50:40.040Z
updated: 2024-08-16T06:50:40.040Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Overcoming Windows 10 Impact on Ethernet Driver
excerpt: This Article Describes Overcoming Windows 10 Impact on Ethernet Driver
thumbnail: https://thmb.techidaily.com/c616a530c3b86047af7fee8d712f3caf3cb46a3e47132cccfb907573c9519566.jpg
---

## Overcoming Windows 10 Impact on Ethernet Driver

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
 2) Locate and click the arrow to expand category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
3) Then right-click Realtek PCIe GBE Family Controller option and choose **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de65b229a9.png)

 4) Go to**Advanced** tab, then choose**Speed & Duplex** option on the left side of the pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de6ed4d026.png)

 5) On the**Value** bar, change the default Auto Negotiation to **100 Mbps Full Duplex**  or some other options accordingly. We chose**100 Mbps Full Duplex** here, but yours could be different.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deb007e7e1.png)
<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 6) Now on the left side of the pane, choose**Energy Efficient Ethernet** option, then change the Value to**Disabled** . After the changes, hit**OK** to save.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deab52d9e0.png)
<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 7) Still, in the**Properties** window, this time, let’s go to**Power Management** tab. Un-tick the box for**Allow the computer to turn off this device to save power** . Then hit**OK** to save and exit.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587decc3276b5.png)
<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

---

### **Option Three:** **Reinstall or Rollback Realtek Adapter Driver**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand the category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->

 Hit**OK** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)

 4) Go to the menu bar on the top and click the button for **Scan for hardware changes** .  
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee9a707c2.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->

 5) Windows will help you automatically install the correct driver that it can find. But there is no guarantee that the new driver is going to work since Windows has provided the not working one originally.

 If you clearly remember that your Ethernet stops working after you update to a certain version of the driver, it is suggested that you roll it back to the stage where it was working well.

---

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4693127&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.videosoftdev.com/images/video_editor/screenshots/1.jpg" border="0">
VSDC Pro Video Editor is a light professional non-linear video editing suite for creating a movie of any complexity. It supports the most popular video/audio formats and codecs, including 4K, HD and GoPro videos. Preconfigured profiles make the creation of videos for various multimedia and mobile devices absolutely hassle-free.

Key features:

•	Import from any devices and cams, including GoPro and drones. All formats supported. Сurrently the only free video editor that allows users to export in a new H265/HEVC codec, something essential for those working with 4K and HD.
•	Everything for hassle-free basic editing: cut, crop and merge files, add titles and favorite music
•	Visual effects, advanced color correction and trendy Instagram-like filters   
•	All multimedia processing done from one app: video editing capabilities reinforced by  a video converter, a screen capture, a video capture, a disc burner and a YouTube uploader
•	Non-linear editing: edit several files with simultaneously 
•	Easy export to social networks: special profiles for YouTube, Facebook, Vimeo, Twitter and Instagram
•	High quality export – no conversion quality loss, double export speed even of HD files due to hardware acceleration
•	Stabilization tool will turn shaky or jittery footage into a more stable video automatically. 
•	Essential toolset for professional video editing: blending modes, Mask tool, advanced multiple-color Chroma Key  
</a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<span id="1793213">
					<video width="1080" height="1620" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:1080px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-harness-the-hype-tactics-to-supercharge-your-social-media-status/"><u>[New] 2024 Approved  Harness the Hype  Tactics to Supercharge Your Social Media Status</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-decoding-instagrams-trends-reels-and-stories-comparison-for-2024/"><u>[New] Decoding Instagram's Trends  Reels & Stories Comparison for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-navigating-through-the-world-of-vlc-features-mac/"><u>[New] Navigating Through the World of VLC Features (Mac)</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-unveiling-top-10-trending-tweets-of-2023/"><u>[New] Unveiling Top 10 Trending Tweets of 2023</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-essential-skype-call-recording-tactics-for-pcsmacs/"><u>[Updated] 2024 Approved  Essential Skype Call Recording Tactics for PCs/Macs</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-rhythm-discoverers-toolkit-all-free-and-online/"><u>2024 Approved  Rhythm Discoverer’s Toolkit – All FREE & Online</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-unveiling-the-most-effective-obs-studio-edits-methods/"><u>2024 Approved  Unveiling the Most Effective OBS Studio Edits Methods</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/a-detailed-walkthrough-for-integrating-instagram-effects-on-archive-media/"><u>A Detailed Walkthrough for Integrating Instagram Effects on Archive Media</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/beating-the-market-top-file-managers/"><u>Beating the Market  Top File Managers</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/buyers-guide-5-critical-aspects-of-investing-in-second-hand-laptops/"><u>Buyer's Guide: 5 Critical Aspects of Investing in Second-Hand Laptops</u></a></li>
<li><a href="https://driver-error.techidaily.com/comprehensive-solution-for-the-missing-coprocessor-driver-error-in-windows-10/"><u>Comprehensive Solution for the 'Missing Coprocessor Driver' Error in Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/device-lockout-graphic-hardware-in-windows/"><u>Device Lockout: Graphic Hardware in Windows</u></a></li>
<li><a href="https://driver-error.techidaily.com/disk-space-management-tips-for-win11-users/"><u>Disk Space Management - Tips for Win11 Users</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-vivo-s18-drfone-by-drfone-virtual-android/"><u>Dose Life360 Notify Me When Someone Checks My Location On Vivo S18? | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/elevate-pcs-capabilities-by-updating-deathadder-on-win11/"><u>Elevate PC's Capabilities by Updating DeathAdder on WIN11</u></a></li>
<li><a href="https://driver-error.techidaily.com/eliminate-bluetooth-auto-connect-on-windows-10/"><u>Eliminate Bluetooth Auto-Connect on Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/enhanced-video-feeds-fixing-asus-webcam-in-w10/"><u>Enhanced Video Feeds: Fixing ASUS Webcam in W10</u></a></li>
<li><a href="https://driver-error.techidaily.com/external-graphics-prevention-in-win10-environment/"><u>External Graphics Prevention in Win10 Environment</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-network-controller-driver-issue-on-dell-laptop/"><u>Fix Network Controller Driver Issue on Dell Laptop</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-wd-ses-usb-device-issue/"><u>Fix WD SES USB Device Issue</u></a></li>
<li><a href="https://win-able.techidaily.com/fixing-launch-problems-with-far-cry-6-on-pc-solutions-unveiled/"><u>Fixing Launch Problems with Far Cry 6 on PC – Solutions Unveiled</u></a></li>
<li><a href="https://driver-error.techidaily.com/graphics-integration-blocked-for-win10-device/"><u>Graphics Integration Blocked for Win10 Device</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-fix-the-usb-installer-unable-to-access-device-problem/"><u>How to Fix the USB Installer Unable to Access Device Problem</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-repair-broken-qualcomm-atheros-bluetooth-drivers-in-windows-11-detailed-guide/"><u>How to Repair Broken Qualcomm Atheros Bluetooth Drivers in Windows 11 [Detailed Guide]</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-tackle-problems-with-antique-usb-composite-gadgets-expert-advice-revealed/"><u>How to Tackle Problems With Antique USB Composite Gadgets – Expert Advice Revealed</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-clipcomposer-critique-full-report/"><u>In 2024, ClipComposer Critique – Full Report</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-logic-pros-way-to-softly-diminish-loud-passages/"><u>In 2024, Logic Pro's Way to Softly Diminish Loud Passages</u></a></li>
<li><a href="https://driver-error.techidaily.com/intel-wi-fi-ax201-connectivity-issue-resolved-successfully/"><u>Intel Wi-Fi AX201 Connectivity Issue - Resolved Successfully</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/introduction-to-basic-animation-in-graphic-design-for-2024/"><u>Introduction to Basic Animation in Graphic Design for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/little-gamers-treasure-trove-of-joy-for-2024/"><u>Little Gamers' Treasure Trove of Joy for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-failed-to-install-hcmon-driver-issues-a-step-by-step-guide/"><u>Resolving 'Failed to Install HCMon Driver' Issues: A Step-by-Step Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-nvidia-control-panel-not-working-on-windows-10/"><u>Solved: NVIDIA Control Panel Not Working on Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/streamlining-hardware-compatibility-in-win11/"><u>Streamlining Hardware Compatibility in WIN11</u></a></li>
<li><a href="https://driver-error.techidaily.com/tackling-issues-in-acpi-device-33a0/"><u>Tackling Issues in ACPI: DEVICE 33A0</u></a></li>
<li><a href="https://driver-error.techidaily.com/taming-technical-turbulence-with-code-resolution-e52/"><u>Taming Technical Turbulence with Code Resolution E52</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-photos-on-honor-magic-6-without-backup-by-fonelab-android-recover-photos/"><u>The way to recover deleted photos on Honor Magic 6 without backup.</u></a></li>
<li><a href="https://driver-error.techidaily.com/touchpad-not-working-issues-on-windows-1111-solved/"><u>Touchpad Not Working Issues on Windows 11/11 [Solved]</u></a></li>
<li><a href="https://driver-error.techidaily.com/unlocking-windows-11-from-enex-system-file-lockup/"><u>Unlocking Windows 11 From eNEX System File Lockup</u></a></li>
<li><a href="https://driver-error.techidaily.com/upgraded-hat-support-on-the-latest-windows-os/"><u>Upgraded HAT Support on the Latest Windows OS</u></a></li>
<li><a href="https://win-blog.techidaily.com/war-thunder-optimization-blueprint-eliminate-low-fps-issues-with-proven-techniques/"><u>War Thunder Optimization Blueprint: Eliminate Low FPS Issues with Proven Techniques</u></a></li>
<li><a href="https://driver-error.techidaily.com/win10-disallows-hardware-graphical-use/"><u>Win10 Disallows Hardware Graphical Use</u></a></li>
</ul></div>
