---
title: Restoring Functional Status of Realtek USB Networks
date: 2024-09-04T12:50:29.294Z
updated: 2024-09-05T12:50:29.294Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Restoring Functional Status of Realtek USB Networks
excerpt: This Article Describes Restoring Functional Status of Realtek USB Networks
thumbnail: https://thmb.techidaily.com/27d6b547bddc8e31d111fb6ac4a194fdf9932bb9effb0d2c901c0f3a526ef8b0.jpg
---

## Restoring Functional Status of Realtek USB Networks

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

 6) Now on the left side of the pane, choose**Energy Efficient Ethernet** option, then change the Value to**Disabled** . After the changes, hit**OK** to save.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deab52d9e0.png)

 7) Still, in the**Properties** window, this time, let’s go to**Power Management** tab. Un-tick the box for**Allow the computer to turn off this device to save power** . Then hit**OK** to save and exit.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587decc3276b5.png)

---

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094429/7443" target="_top" id="2094429">
  <img src="//a.impactradius-go.com/display-ad/7443-2094429" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094429/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Option Three:** **Reinstall or Rollback Realtek Adapter Driver**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand the category**Network adapters** .
<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1001453/11832" target="_top" id="1001453">
  <img src="//a.impactradius-go.com/display-ad/11832-1001453" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1001453/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .
<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1001446/11832" target="_top" id="1001446">
  <img src="//a.impactradius-go.com/display-ad/11832-1001446" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1001446/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

<!-- affiliate ads begin -->
<span id="1983549">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983549.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983549">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983549.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983549%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983549/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Hit**OK** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)

 4) Go to the menu bar on the top and click the button for **Scan for hardware changes** .  
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee9a707c2.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135405/19272" target="_top" id="2135405">
  <img src="//a.impactradius-go.com/display-ad/19272-2135405" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135405/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094422/7443" target="_top" id="2094422">
  <img src="//a.impactradius-go.com/display-ad/7443-2094422" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094422/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-info.techidaily.com/new-iconic-imagery-stories-a-deep-dive/"><u>[New] Iconic Imagery Stories  A Deep Dive</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-expert-tips-for-creating-dynamic-youtube-splits/"><u>[New] In 2024, Expert Tips for Creating Dynamic YouTube Splits</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-error-code-devhub-48/"><u>[SOLVED] Error Code - DevHub 48</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-beginners-guide-to-changing-speed-up-in-videos-on-snapchat-for-2024/"><u>[Updated] Beginner’s Guide to Changing Speed Up in Videos on Snapchat for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-navigating-the-world-of-insta-influencers-5-pivotal-moves-and-results/"><u>[Updated] In 2024, Navigating the World of Insta Influencers  5 Pivotal Moves and Results</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-professional-approaches-to-preserving-ps3-games-on-screen/"><u>[Updated] Professional Approaches to Preserving PS3 Games On Screen</u></a></li>
<li><a href="https://driver-error.techidaily.com/alleviating-driver-conflicts-device-venint33a0/"><u>Alleviating Driver Conflicts - Device VEN_INT33A0</u></a></li>
<li><a href="https://driver-error.techidaily.com/bcm20702a0-device-not-found-error/"><u>BCM20702A0 Device Not Found Error</u></a></li>
<li><a href="https://driver-error.techidaily.com/comprehensive-guide-resolving-issues-with-vintage-usb-composite-devices/"><u>Comprehensive Guide: Resolving Issues with Vintage USB Composite Devices</u></a></li>
<li><a href="https://driver-error.techidaily.com/comprehensive-walkthrough-uninstalling-graphics-driver-in-safe-mode-on-window-8-systems/"><u>Comprehensive Walkthrough: Uninstalling Graphics Driver in Safe Mode on Window 8 Systems</u></a></li>
<li><a href="https://driver-error.techidaily.com/demystifying-the-legacy-usb-composite-device-problems-now-fixed/"><u>Demystifying the Legacy USB Composite Device Problems - Now Fixed!</u></a></li>
<li><a href="https://driver-error.techidaily.com/driver-irql-not-less-or-equal-on-windows-11-fixed/"><u>Driver Irql Not Less Or Equal on Windows 11 [Fixed]</u></a></li>
<li><a href="https://article-posts.techidaily.com/essential-mixer-streaming-tips-for-mac-users-for-2024/"><u>Essential Mixer Streaming Tips for Mac Users for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-your-hands-on-the-latest-free-drivers-realtek-pcie-controller-family-windows-11-ready/"><u>Get Your Hands on the Latest Free Drivers: Realtek PCIe Controller Family - Windows 11 Ready.</u></a></li>
<li><a href="https://driver-error.techidaily.com/graphical-interrupt-received-rejection-by-win11/"><u>Graphical Interrupt Received Rejection by Win11</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-do-you-arete-dicta-by-jillian-hormones-samsungin-the-firstiin-this-problem-statement-of-what-and-then-i-need-to-beings-as-an-integerlnger-when-used-thro1/"><u>How Do You Arete Dicta by Jillian Hormone's Samsung’in the First_i|In This Problem Statement of What?, And Then I Need to Beings, as an Integerlnger when Used Throughout Each Other`m^2014-July</u></a></li>
<li><a href="https://driver-error.techidaily.com/immediate-fix-persistent-amd-driver-glitches/"><u>Immediate Fix: Persistent AMD Driver Glitches</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/interactive-intelligence-acquire-new-language-skills-virtually/"><u>Interactive Intelligence: Acquire New Language Skills Virtually</u></a></li>
<li><a href="https://review-topics.techidaily.com/iphone-15-pro-data-recovery-an-infographic-to-conquer-iphone-data-loss-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>iPhone 15 Pro Data Recovery – An Infographic to Conquer iPhone Data Loss | Stellar</u></a></li>
<li><a href="https://driver-error.techidaily.com/mastering-amd-radeon-wattman-overcoming-configuration-setbacks-and-resets/"><u>Mastering AMD Radeon Wattman: Overcoming Configuration Setbacks & Resets</u></a></li>
<li><a href="https://driver-error.techidaily.com/mastering-your-graphics-settings-default-radeon-wattman-stability-achieved/"><u>Mastering Your Graphics Settings: Default Radeon Wattman Stability Achieved</u></a></li>
<li><a href="https://driver-error.techidaily.com/navigating-and-fixing-ndis-on-pcs-swiftly/"><u>Navigating and Fixing NDIS on PCs Swiftly</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-access-denied-solving-usb-installation-troubles-on-your-pc/"><u>Overcoming 'Access Denied': Solving USB Installation Troubles on Your PC</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-glitches-lenovo-in-windows-10/"><u>Overcoming Glitches: Lenovo in Windows 10</u></a></li>
<li><a href="https://program-issues.techidaily.com/pc-players-heres-how-to-overcome-crashes-in-yakuza-n-the-song-of-life/"><u>PC Players! Here's How to Overcome Crashes in Yakuza N: The Song of Life</u></a></li>
<li><a href="https://driver-error.techidaily.com/quick-solutions-resolve-driver-unavailable-itbm-errors-instantly/"><u>Quick Solutions: Resolve 'Driver Unavailable' ITBM Errors Instantly</u></a></li>
<li><a href="https://driver-error.techidaily.com/reactivation-of-dormant-bluetooth-on-your-pc/"><u>Reactivation Of: Dormant Bluetooth on Your PC</u></a></li>
<li><a href="https://driver-error.techidaily.com/reclaim-absent-discs-and-drives-from-windows-1110/"><u>Reclaim Absent Discs & Drives From Windows 11/10</u></a></li>
<li><a href="https://driver-error.techidaily.com/reorienting-content-display-a-comprehensive-fix-for-topsy-turvy-video-playback-on-asus-systems/"><u>Reorienting Content Display: A Comprehensive Fix for Topsy-Turvy Video Playback on ASUS Systems</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-hub-error-48/"><u>Resolved Hub Error #48</u></a></li>
<li><a href="https://driver-error.techidaily.com/run-a-system-file-checker-scan-to-verify-and-repair-corrupted-files/"><u>Run a System File Checker Scan to Verify and Repair Corrupted Files.</u></a></li>
<li><a href="https://driver-error.techidaily.com/service-install-error-inf-correction-achieved/"><u>Service Install Error: INF Correction Achieved</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-hp-notebook-keys-that-are-not-responding-or-stuck-how-to-fix-in-minutes-article-title-detailed-user-friendly-guide-tech-talker406-chars/"><u>Solving HP Notebook Keys That Are ‘Not Responding’ or Stuck – How To Fix in Minutes (Article Title)– Detailed, User Friendly Guide | Tech Talker—406 Chars</u></a></li>
<li><a href="https://sound-issues.techidaily.com/step-by-step-fixes-addressing-microphone-failures-across-the-kotion-g2000-range/"><u>Step-by-Step Fixes: Addressing Microphone Failures Across the Kotion G2000 Range</u></a></li>
<li><a href="https://driver-error.techidaily.com/streamlining-windows-10-touchpad-compatibility-elan/"><u>Streamlining Windows 10 Touchpad Compatibility, Elan</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-5-panoramic-capture-models-for-2024/"><u>Top 5 Panoramic Capture Models for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/universal-pc-card-drivers-for-windows-series/"><u>Universal PC Card Drivers for Windows Series</u></a></li>
<li><a href="https://driver-error.techidaily.com/win-keyboards-refusing-to-work/"><u>Win Keyboards Refusing to Work</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-navigate-and-fix-your-qualcomm-atheros-bluetooth-driver-problems-now/"><u>Windows Navigate and Fix Your Qualcomm Atheros Bluetooth Driver Problems Now</u></a></li>
</ul></div>
