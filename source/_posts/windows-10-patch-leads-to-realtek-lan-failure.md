---
title: Windows 10 Patch Leads to Realtek LAN Failure
date: 2024-08-15T06:53:32.617Z
updated: 2024-08-16T06:53:32.617Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Windows 10 Patch Leads to Realtek LAN Failure
excerpt: This Article Describes Windows 10 Patch Leads to Realtek LAN Failure
thumbnail: https://thmb.techidaily.com/ad227a8d5363831d078e6323942af2a72809395f7bf85c351306cae77a65bd05.jpg
---

## Windows 10 Patch Leads to Realtek LAN Failure

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
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) Then right-click Realtek PCIe GBE Family Controller option and choose **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de65b229a9.png)

 4) Go to**Advanced** tab, then choose**Speed & Duplex** option on the left side of the pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de6ed4d026.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->

 5) On the**Value** bar, change the default Auto Negotiation to **100 Mbps Full Duplex**  or some other options accordingly. We chose**100 Mbps Full Duplex** here, but yours could be different.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deb007e7e1.png)

 6) Now on the left side of the pane, choose**Energy Efficient Ethernet** option, then change the Value to**Disabled** . After the changes, hit**OK** to save.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deab52d9e0.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->

 7) Still, in the**Properties** window, this time, let’s go to**Power Management** tab. Un-tick the box for**Allow the computer to turn off this device to save power** . Then hit**OK** to save and exit.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587decc3276b5.png)
<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

---

### **Option Three:** **Reinstall or Rollback Realtek Adapter Driver**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand the category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

 Hit**OK** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->

 4) Go to the menu bar on the top and click the button for **Scan for hardware changes** .  
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee9a707c2.png)

 5) Windows will help you automatically install the correct driver that it can find. But there is no guarantee that the new driver is going to work since Windows has provided the not working one originally.

 If you clearly remember that your Ethernet stops working after you update to a certain version of the driver, it is suggested that you roll it back to the stage where it was working well.

---

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
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
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-guide-to-choosing-ideal-youtube-thumbnail-shapes/"><u>[New] 2024 Approved  Guide to Choosing Ideal Youtube Thumbnail Shapes</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/dd-youtube-melodies-in-imovie-without-hurdles/"><u>[New] Add YouTube Melodies in iMovie Without Hurdles</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-error-code-devhub-48/"><u>[SOLVED] Error Code - DevHub 48</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-nextgen-editing-best-4k-displays-to-watch/"><u>[Updated] In 2024, NextGen Editing  Best 4K Displays to Watch</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-viral-talent-quest-episodes-1-10/"><u>[Updated] Viral Talent Quest Episodes #1-10</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-navigating-the-setup-of-obs-and-streamlabs-for-mac-users/"><u>2024 Approved  Navigating the Setup of OBS & Streamlabs for Mac Users</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unravel-the-potential-of-multiple-screen-usage-in-netflix/"><u>2024 Approved  Unravel The Potential of Multiple Screen Usage in Netflix</u></a></li>
<li><a href="https://driver-error.techidaily.com/alleviating-driver-conflicts-device-venint33a0/"><u>Alleviating Driver Conflicts - Device VEN_INT33A0</u></a></li>
<li><a href="https://driver-error.techidaily.com/bcm20702a0-device-not-found-error/"><u>BCM20702A0 Device Not Found Error</u></a></li>
<li><a href="https://fox-http.techidaily.com/best-of-the-best-15-4k-video-capture-units-for-2024/"><u>Best of the Best  #15 4K Video Capture Units for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/best-ways-to-bypass-icloud-activation-lock-from-apple-iphone-12-miniipadipod-by-drfone-ios/"><u>Best Ways to Bypass iCloud Activation Lock from Apple iPhone 12 mini/iPad/iPod</u></a></li>
<li><a href="https://driver-error.techidaily.com/comprehensive-guide-resolving-issues-with-vintage-usb-composite-devices/"><u>Comprehensive Guide: Resolving Issues with Vintage USB Composite Devices</u></a></li>
<li><a href="https://driver-error.techidaily.com/comprehensive-walkthrough-uninstalling-graphics-driver-in-safe-mode-on-window-8-systems/"><u>Comprehensive Walkthrough: Uninstalling Graphics Driver in Safe Mode on Window 8 Systems</u></a></li>
<li><a href="https://driver-error.techidaily.com/demystifying-the-legacy-usb-composite-device-problems-now-fixed/"><u>Demystifying the Legacy USB Composite Device Problems - Now Fixed!</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/dont-miss-out-discover-why-you-need-a-3d-printer-on-black-friday-reason-1-5/"><u>Don't Miss Out! Discover Why You Need a 3D Printer on Black Friday (Reason #1-#5)</u></a></li>
<li><a href="https://driver-error.techidaily.com/driver-installation-woes-learn-how-to-verify-and-correct-unvalidated-drivers-on-your-system/"><u>Driver Installation Woes? Learn How To Verify And Correct Unvalidated Drivers On Your System</u></a></li>
<li><a href="https://driver-error.techidaily.com/driver-irql-not-less-or-equal-on-windows-11-fixed/"><u>Driver Irql Not Less Or Equal on Windows 11 [Fixed]</u></a></li>
<li><a href="https://win-answers.techidaily.com/efficient-tactics-to-solve-your-acrocefexe-malfunction-issues/"><u>Efficient Tactics to Solve Your AcroCEF.exe Malfunction Issues</u></a></li>
<li><a href="https://driver-error.techidaily.com/graphical-interrupt-received-rejection-by-win11/"><u>Graphical Interrupt Received Rejection by Win11</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-do-you-arete-dicta-by-jillian-hormones-samsungin-the-firstiin-this-problem-statement-of-what-and-then-i-need-to-beings-as-an-integerlnger-when-used-thro1/"><u>How Do You Arete Dicta by Jillian Hormone's Samsung’in the First_i|In This Problem Statement of What?, And Then I Need to Beings, as an Integerlnger when Used Throughout Each Other`m^2014-July</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/-mics-for-bloggers-educators-and-entertainment-clips/"><u>Ideal Mics for Bloggers, Educators, & Entertainment Clips</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-best-3-software-to-transfer-files-tofrom-your-honor-magic-6-pro-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Best 3 Software to Transfer Files to/from Your Honor Magic 6 Pro via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-bypass-activation-lock-from-iphone-14-plus-4-easy-ways-by-drfone-ios/"><u>In 2024, Bypass Activation Lock From iPhone 14 Plus - 4 Easy Ways</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-show-wi-fi-password-on-sony-xperia-10-v-by-drfone-android/"><u>In 2024, How to Show Wi-Fi Password on Sony Xperia 10 V</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-leading-learners-the-teachers-guide-to-visual-pedagogy/"><u>In 2024, Leading Learners  The Teacher's Guide to Visual Pedagogy</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/live-broadcast-converter-decoder/"><u>Live Broadcast Converter Decoder</u></a></li>
<li><a href="https://driver-error.techidaily.com/mastering-amd-radeon-wattman-overcoming-configuration-setbacks-and-resets/"><u>Mastering AMD Radeon Wattman: Overcoming Configuration Setbacks & Resets</u></a></li>
<li><a href="https://driver-error.techidaily.com/mastering-your-graphics-settings-default-radeon-wattman-stability-achieved/"><u>Mastering Your Graphics Settings: Default Radeon Wattman Stability Achieved</u></a></li>
<li><a href="https://driver-error.techidaily.com/navigating-and-fixing-ndis-on-pcs-swiftly/"><u>Navigating and Fixing NDIS on PCs Swiftly</u></a></li>
<li><a href="https://buynow-help.techidaily.com/oneplus-6t-review/"><u>OnePlus 6T Review</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-access-denied-solving-usb-installation-troubles-on-your-pc/"><u>Overcoming 'Access Denied': Solving USB Installation Troubles on Your PC</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-glitches-lenovo-in-windows-10/"><u>Overcoming Glitches: Lenovo in Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/quick-solutions-resolve-driver-unavailable-itbm-errors-instantly/"><u>Quick Solutions: Resolve 'Driver Unavailable' ITBM Errors Instantly</u></a></li>
<li><a href="https://driver-error.techidaily.com/reclaim-absent-discs-and-drives-from-windows-1110/"><u>Reclaim Absent Discs & Drives From Windows 11/10</u></a></li>
<li><a href="https://driver-error.techidaily.com/recovering-bluetooth-links-device-manager-lack/"><u>Recovering: Bluetooth Links, Device Manager Lack</u></a></li>
<li><a href="https://driver-error.techidaily.com/reorienting-content-display-a-comprehensive-fix-for-topsy-turvy-video-playback-on-asus-systems/"><u>Reorienting Content Display: A Comprehensive Fix for Topsy-Turvy Video Playback on ASUS Systems</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-hub-error-48/"><u>Resolved Hub Error #48</u></a></li>
<li><a href="https://driver-error.techidaily.com/restoring-realtek-usb-controls-post-windows-change/"><u>Restoring Realtek USB Controls Post-Windows Change</u></a></li>
<li><a href="https://driver-error.techidaily.com/run-a-system-file-checker-scan-to-verify-and-repair-corrupted-files/"><u>Run a System File Checker Scan to Verify and Repair Corrupted Files.</u></a></li>
<li><a href="https://network-issues.techidaily.com/shed-light-on-dark-lcd-in-lenovo-models/"><u>Shed Light on Dark LCD in Lenovo Models</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-hp-notebook-keys-that-are-not-responding-or-stuck-how-to-fix-in-minutes-article-title-detailed-user-friendly-guide-tech-talker406-chars/"><u>Solving HP Notebook Keys That Are ‘Not Responding’ or Stuck – How To Fix in Minutes (Article Title)– Detailed, User Friendly Guide | Tech Talker—406 Chars</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-solve-memory-failure-in-windows/"><u>Strategies to Solve Memory Failure in Windows</u></a></li>
<li><a href="https://driver-error.techidaily.com/streamlining-windows-10-touchpad-compatibility-elan/"><u>Streamlining Windows 10 Touchpad Compatibility, Elan</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/tailored-timeline-management-best-twitter-unfollow-tools-ranked-for-2024/"><u>Tailored Timeline Management  Best Twitter Unfollow Tools Ranked for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-essential-quickstart-to-srt-to-txt-file-alteration-for-2024/"><u>The Essential Quickstart to SRT to TXT File Alteration for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/universal-pc-card-drivers-for-windows-series/"><u>Universal PC Card Drivers for Windows Series</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-unleash-your-creative-potential-with-these-5-leading-audio-distortion-programs/"><u>Updated In 2024, Unleash Your Creative Potential with These 5 Leading Audio Distortion Programs</u></a></li>
<li><a href="https://driver-error.techidaily.com/win-keyboards-refusing-to-work/"><u>Win Keyboards Refusing to Work</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-navigate-and-fix-your-qualcomm-atheros-bluetooth-driver-problems-now/"><u>Windows Navigate and Fix Your Qualcomm Atheros Bluetooth Driver Problems Now</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-pc-wont-stop-responding-when-i-try-to-turn-off-the-built-in-bluetooth-adapter-any-ideas/"><u>Windows PC Won't Stop Responding when I Try to Turn Off the Built-In Bluetooth Adapter - Any Ideas?</u></a></li>
</ul></div>
