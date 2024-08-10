---
title: Ethernet Controller Bug in Win11 - Realtek Solution
date: 2024-08-09T08:56:26.973Z
updated: 2024-08-10T08:56:26.973Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Ethernet Controller Bug in Win11 - Realtek Solution
excerpt: This Article Describes Ethernet Controller Bug in Win11 - Realtek Solution
thumbnail: https://thmb.techidaily.com/a3ff3acad952490c637c7b896fc0975ebe957935337cd7ad7a4e6125800ac957.jpg
---

## Ethernet Controller Bug in Win11 - Realtek Solution

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b91ef1806793.jpg)

 Users have reported that their Realtek PCIe Family Controller (Ethernet) randomly stopped working after they upgraded to Windows 10\. There are still no answers from Microsoft or Realtek as to why would this happen, and this situation happens randomly on different occasions, so there are a lot of solutions that could be of help.

 If this is the problem you are experiencing now, please follow the instructions below to get it fixed by yourself.

[**Option One: Reset TCP/IP**](https://natural-cycles.sjv.io/vmebmr)
[**Option Two: Change Settings in Network Adapter Properties**](https://aofit.pxf.io/mmjyxq)
[**Option Three: Reinstall Realtek Adapter Driver**](https://westkiss.pxf.io/daqnaq)
[**Option Four: Update the Realtek Driver**](https://newchic.sjv.io/jzg4zq)

---

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
### **Option One: Reset TCP/IP**

1) On your keyboard, press the**Windows logo key** , type**cmd** , right-click**Command Prompt** from the results, and select**Run as administrator** .  
  
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
![how to open Command Prompt as an admin](https://images.drivereasy.com/wp-content/uploads/2023/10/win11-Command-Prompt-Run-as-administrator.jpg)

 When prompted with the following notification, hit**Yes** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de25ac8c94.jpg)

 2) Type in the following command:

netsh int ip reset c:\resetlog.txt

 Make sure that you have made no typo and hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de2ea5a2ef.png)

 This will help you reset your TCP/IP (Transmission Control Protocol/Internet Protocol). To make it easier to understand, TCP/IP is the language that your computer uses to communicate with the outside world. Reseting TCP/IP will help you revert your Internet settings to the stage where it still works.

---

<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Option Two:** **Change Settings in Network Adapter Properties**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand category**Network adapters** .

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
3) Then right-click Realtek PCIe GBE Family Controller option and choose **Properties** .

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
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de65b229a9.png)

 4) Go to**Advanced** tab, then choose**Speed & Duplex** option on the left side of the pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de6ed4d026.png)

 5) On the**Value** bar, change the default Auto Negotiation to **100 Mbps Full Duplex**  or some other options accordingly. We chose**100 Mbps Full Duplex** here, but yours could be different.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deb007e7e1.png)

 6) Now on the left side of the pane, choose**Energy Efficient Ethernet** option, then change the Value to**Disabled** . After the changes, hit**OK** to save.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deab52d9e0.png)

 7) Still, in the**Properties** window, this time, let’s go to**Power Management** tab. Un-tick the box for**Allow the computer to turn off this device to save power** . Then hit**OK** to save and exit.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587decc3276b5.png)

---

### **Option Three:** **Reinstall or Rollback Realtek Adapter Driver**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-the-screencast-guide-to-flawless-presentations-and-demos/"><u>[New] 2024 Approved  The Screencast Guide to Flawless Presentations and Demos</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-experts-guide-to-video-editors-picking-between-filmora-and-democreator-for-2024/"><u>[New] Expert's Guide to Video Editors  Picking Between Filmora and Democreator for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-how-to-light-your-youtube-video/"><u>[New] In 2024, How To Light Your YouTube Video</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-gear-interferes-with-car-load/"><u>[Solved] Gear Interferes with Car Load</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-intel-wi-fi-6-ax201-not-working/"><u>[SOLVED] Intel Wi-Fi 6 AX201 Not Working</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-7-crucial-gadgets-for-successful-metaverse-journey/"><u>[Updated] 7 Crucial Gadgets for Successful Metaverse Journey</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-goovision-promax-high-res-os-capturer/"><u>[Updated] In 2024, GooVision ProMax  High-Res OS Capturer</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-strategies-to-maximize-viewership-on-igtv-from-h-videos/"><u>[Updated] In 2024, Strategies to Maximize Viewership on IGTV From H-Videos</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/building-brands-earning-dollars-a-comprehensive-guide-to-insta-sponsorships-for-2024/"><u>Building Brands, Earning Dollars  A Comprehensive Guide to Insta-Sponsorships for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/cd-drive-absence-windows-11-issue-solved/"><u>CD Drive Absence: Windows 11 Issue Solved</u></a></li>
<li><a href="https://driver-error.techidaily.com/darkened-keys-on-asus-pc/"><u>Darkened Keys on Asus PC</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-wired-network-anomalies-in-poweredge-tower/"><u>Fix Wired Network Anomalies in PowerEdge Tower</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-photos-files-from-xiaomi-redmi-a2plus-by-fonelab-android-recover-photos/"><u>How To  Restore Missing Photos Files from Xiaomi Redmi A2+.</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-resolve-incompatibility-issues-between-hardware-and-idt-software-solutions/"><u>How to Resolve Incompatibility Issues Between Hardware and IDT Software Solutions</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-successfully-update-your-hcmon-driver-and-avoid-common-mistakes/"><u>How to Successfully Update Your HCMon Driver and Avoid Common Mistakes</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-update-iphone-8-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update iPhone 8 without iTunes? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-methods-to-change-gps-location-on-oneplus-ace-2-drfone-by-drfone-virtual-android/"><u>In 2024, Methods to Change GPS Location On OnePlus Ace 2 | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-7-phone-number-locators-to-track-oppo-reno-8t-5g-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Phone Number Locators To Track Oppo Reno 8T 5G Location | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-lava-blaze-curve-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Will Pokémon Go Ban the Account if You Use PGSharp On Lava Blaze Curve 5G | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/missing-external-drive-in-windows-10-the-seagate-dilemma/"><u>Missing External Drive in Windows 10: The Seagate Dilemma</u></a></li>
<li><a href="https://fox-links.techidaily.com/pinnacle-of-picture-perfection-top-10-screens-for-2024/"><u>Pinnacle of Picture Perfection  Top 10 Screens for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/quick-solution-to-persistent-amd-crashes/"><u>Quick Solution to Persistent AMD Crashes</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-code-1-fixing-improper-configuration-on-your-device/"><u>Resolving Code 1: Fixing Improper Configuration on Your Device</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-non-responsive-hp-wireless-keyboard-problems-effective-solutions-inside/"><u>Resolving Non-Responsive HP Wireless Keyboard Problems - Effective Solutions Inside</u></a></li>
<li><a href="https://driver-error.techidaily.com/resource-allocation-hurdles-in-device/"><u>Resource Allocation Hurdles in Device</u></a></li>
<li><a href="https://driver-error.techidaily.com/resource-utilization-challenges/"><u>Resource Utilization Challenges</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-microsoft-visual-cplusplus-runtime-library-error-in-windows-10/"><u>Solved: Microsoft Visual C++ Runtime Library Error in Windows 10</u></a></li>
<li><a href="https://extra-tips.techidaily.com/step-by-step-guide-for-text-superimposition-on-video-using-windows-photos/"><u>Step-by-Step Guide for Text Superimposition on Video Using Windows Photos</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-imei-unlokers-for-your-vivo-v27-pro-phone-by-drfone-android/"><u>Top IMEI Unlokers for Your Vivo V27 Pro Phone</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-guide-fixing-qualcomm-atheros-bluetooth-driver-issues-in-windows-11/"><u>Troubleshooting Guide: Fixing Qualcomm Atheros Bluetooth Driver Issues in Windows 11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-the-not-secured-network-alert-on-your-device/"><u>Troubleshooting the ‘Not Secured’ Network Alert on Your Device</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-unsupported-hardware-recognition-error-with-idt-software/"><u>Troubleshooting: Unsupported Hardware Recognition Error with IDT Software</u></a></li>
<li><a href="https://driver-error.techidaily.com/unused-space-on-devices-resource-table/"><u>Unused Space on Device's Resource Table</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-google-play-services-keeps-stopping-on-xiaomi-redmi-13c-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What to Do if Google Play Services Keeps Stopping on Xiaomi Redmi 13C 5G | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-realme-11x-5g-drfone-by-drfone-virtual-android/"><u>Will iSpoofer update On Realme 11X 5G | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-11-addressing-bus-controllers/"><u>Windows 11: Addressing Bus Controllers</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-users-heres-how-you-can-get-your-wi-fi-keyboard-back-in-action/"><u>Windows Users! Here's How You Can Get Your Wi-Fi Keyboard Back in Action</u></a></li>
</ul></div>
