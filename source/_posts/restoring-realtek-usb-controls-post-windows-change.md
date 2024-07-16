---
title: Restoring Realtek USB Controls Post-Windows Change
date: 2024-07-15T06:47:35.262Z
updated: 2024-07-16T06:47:35.262Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Restoring Realtek USB Controls Post-Windows Change
excerpt: This Article Describes Restoring Realtek USB Controls Post-Windows Change
thumbnail: https://thmb.techidaily.com/ab3bfec296887a8d448d8e35c0b03544ab7fa85c994173438d04396b799c480a.jpg
---

## Restoring Realtek USB Controls Post-Windows Change

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
<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
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
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
3) Then right-click Realtek PCIe GBE Family Controller option and choose **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de65b229a9.png)

 4) Go to**Advanced** tab, then choose**Speed & Duplex** option on the left side of the pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de6ed4d026.png)

 5) On the**Value** bar, change the default Auto Negotiation to **100 Mbps Full Duplex**  or some other options accordingly. We chose**100 Mbps Full Duplex** here, but yours could be different.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deb007e7e1.png)

 6) Now on the left side of the pane, choose**Energy Efficient Ethernet** option, then change the Value to**Disabled** . After the changes, hit**OK** to save.

<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deab52d9e0.png)

 7) Still, in the**Properties** window, this time, let’s go to**Power Management** tab. Un-tick the box for**Allow the computer to turn off this device to save power** . Then hit**OK** to save and exit.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://driver-error.techidaily.com/service-install-error-inf-correction-achieved/"><u>Service Install Error: INF Correction Achieved</u></a></li>
<li><a href="https://review-topics.techidaily.com/change-location-on-yik-yak-for-your-honor-magic-6-lite-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>Change Location on Yik Yak For your Honor Magic 6 Lite to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-asgardian-fury-final-conflict-era/"><u>[Updated] In 2024, Asgardian Fury  Final Conflict Era</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-do-you-arete-dicta-by-jillian-hormones-samsungin-the-firstiin-this-problem-statement-of-what-and-then-i-need-to-beings-as-an-integerlnger-when-used-thro1/"><u>How Do You Arete Dicta by Jillian Hormone's Samsung’in the First_i|In This Problem Statement of What?, And Then I Need to Beings, as an Integerlnger when Used Throughout Each Other`m^2014-July</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-glitches-lenovo-in-windows-10/"><u>Overcoming Glitches: Lenovo in Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/navigating-and-fixing-ndis-on-pcs-swiftly/"><u>Navigating and Fixing NDIS on PCs Swiftly</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-navigate-and-fix-your-qualcomm-atheros-bluetooth-driver-problems-now/"><u>Windows Navigate and Fix Your Qualcomm Atheros Bluetooth Driver Problems Now</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-crafting-compact-cities-for-a-sustainable-future/"><u>In 2024, Crafting Compact Cities for a Sustainable Future</u></a></li>
<li><a href="https://driver-error.techidaily.com/demystifying-the-legacy-usb-composite-device-problems-now-fixed/"><u>Demystifying the Legacy USB Composite Device Problems - Now Fixed!</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-how-to-use-zoom-webinars-beginners-guide/"><u>2024 Approved  How to Use Zoom Webinars [Beginner’s Guide]</u></a></li>
<li><a href="https://driver-error.techidaily.com/reorienting-content-display-a-comprehensive-fix-for-topsy-turvy-video-playback-on-asus-systems/"><u>Reorienting Content Display: A Comprehensive Fix for Topsy-Turvy Video Playback on ASUS Systems</u></a></li>
<li><a href="https://driver-error.techidaily.com/comprehensive-guide-resolving-issues-with-vintage-usb-composite-devices/"><u>Comprehensive Guide: Resolving Issues with Vintage USB Composite Devices</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-hub-error-48/"><u>Resolved Hub Error #48</u></a></li>
<li><a href="https://driver-error.techidaily.com/reactivation-of-dormant-bluetooth-on-your-pc/"><u>Reactivation Of: Dormant Bluetooth on Your PC</u></a></li>
<li><a href="https://driver-error.techidaily.com/quick-solutions-resolve-driver-unavailable-itbm-errors-instantly/"><u>Quick Solutions: Resolve 'Driver Unavailable' ITBM Errors Instantly</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/restore-normal-screen-orientation-for-windows-10/"><u>Restore Normal Screen Orientation for Windows 10</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-lock-your-oppo-find-n3-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>In 2024, Lock Your Oppo Find N3 Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-elevate-instagram-clips-incorporating-borders-effectively/"><u>[Updated] 2024 Approved  Elevate Instagram Clips  Incorporating Borders Effectively</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-access-denied-solving-usb-installation-troubles-on-your-pc/"><u>Overcoming 'Access Denied': Solving USB Installation Troubles on Your PC</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-error-code-devhub-48/"><u>[SOLVED] Error Code - DevHub 48</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-mastery-through-art-the-ultimate-list-of-free-mac-drawing-apps/"><u>[New] Mastery Through Art  The Ultimate List of FREE Mac Drawing Apps</u></a></li>
<li><a href="https://review-topics.techidaily.com/mkv-playback-issues-on-samsung-galaxy-a24-by-aiseesoft-video-converter-play-mkv-on-android/"><u>MKV playback issues on Samsung Galaxy A24</u></a></li>
<li><a href="https://driver-error.techidaily.com/reclaim-absent-discs-and-drives-from-windows-1110/"><u>Reclaim Absent Discs & Drives From Windows 11/10</u></a></li>
<li><a href="https://driver-error.techidaily.com/mastering-amd-radeon-wattman-overcoming-configuration-setbacks-and-resets/"><u>Mastering AMD Radeon Wattman: Overcoming Configuration Setbacks & Resets</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-how-to-trimcrop-video-in-microsoft-powerpoint-for-2024/"><u>Updated How to Trim/Crop Video in Microsoft Powerpoint for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/alleviating-driver-conflicts-device-venint33a0/"><u>Alleviating Driver Conflicts - Device VEN_INT33A0</u></a></li>
<li><a href="https://driver-error.techidaily.com/immediate-fix-persistent-amd-driver-glitches/"><u>Immediate Fix: Persistent AMD Driver Glitches</u></a></li>
<li><a href="https://driver-error.techidaily.com/universal-pc-card-drivers-for-windows-series/"><u>Universal PC Card Drivers for Windows Series</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-stylish-snaps-essential-lenses-and-filters-for-you-now-for-2024/"><u>[Updated] Stylish Snaps  Essential Lenses and Filters for You Now for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/mastering-your-graphics-settings-default-radeon-wattman-stability-achieved/"><u>Mastering Your Graphics Settings: Default Radeon Wattman Stability Achieved</u></a></li>
<li><a href="https://driver-error.techidaily.com/graphical-interrupt-received-rejection-by-win11/"><u>Graphical Interrupt Received Rejection by Win11</u></a></li>
<li><a href="https://driver-error.techidaily.com/run-a-system-file-checker-scan-to-verify-and-repair-corrupted-files/"><u>Run a System File Checker Scan to Verify and Repair Corrupted Files.</u></a></li>
<li><a href="https://driver-error.techidaily.com/bcm20702a0-device-not-found-error/"><u>BCM20702A0 Device Not Found Error</u></a></li>
<li><a href="https://driver-error.techidaily.com/win-keyboards-refusing-to-work/"><u>Win Keyboards Refusing to Work</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-qualcomm-atheros-wireless-network-adapter-driver-issue-for-windows-10/"><u>Fix Qualcomm Atheros Wireless Network Adapter Driver Issue for Windows 10</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-forgot-pattern-lock-heres-how-you-can-unlock-realme-c67-4g-pattern-lock-screen-by-drfone-android/"><u>In 2024, Forgot Pattern Lock? Heres How You Can Unlock Realme C67 4G Pattern Lock Screen</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-25-top-free-tips-to-stream-online-learning-events-effectively/"><u>In 2024, 25 Top Free Tips to Stream Online Learning Events Effectively</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-skyrocketing-video-performance-in-instagram-stories-mobile/"><u>[Updated] Skyrocketing Video Performance in Instagram Stories (Mobile)</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-master-your-mobile-photos-ios-and-androids-finest-apps/"><u>[Updated] Master Your Mobile Photos  IOS & Android's Finest Apps</u></a></li>
</ul></div>
