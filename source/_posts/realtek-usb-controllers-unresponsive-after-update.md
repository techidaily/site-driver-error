---
title: Realtek USB Controllers Unresponsive After Update
date: 2024-10-07T16:20:38.383Z
updated: 2024-10-12T16:03:03.863Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Realtek USB Controllers Unresponsive After Update
excerpt: This Article Describes Realtek USB Controllers Unresponsive After Update
thumbnail: https://thmb.techidaily.com/c1db4ec27c5136dcd8d29377fc669f9488ff5fcb91d758bff8fe15d9459484d0.jpg
---

## Realtek USB Controllers Unresponsive After Update

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

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134503/19576" target="_top" id="2134503">
  <img src="//a.impactradius-go.com/display-ad/19576-2134503" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134503/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de65b229a9.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948876/19272" target="_top" id="1948876">
  <img src="//a.impactradius-go.com/display-ad/19272-1948876" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948876/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4) Go to**Advanced** tab, then choose**Speed & Duplex** option on the left side of the pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de6ed4d026.png)

 5) On the**Value** bar, change the default Auto Negotiation to **100 Mbps Full Duplex**  or some other options accordingly. We chose**100 Mbps Full Duplex** here, but yours could be different.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deb007e7e1.png)

 6) Now on the left side of the pane, choose**Energy Efficient Ethernet** option, then change the Value to**Disabled** . After the changes, hit**OK** to save.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deab52d9e0.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100533/7443" target="_top" id="2100533">
  <img src="//a.impactradius-go.com/display-ad/7443-2100533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100533/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 7) Still, in the**Properties** window, this time, let’s go to**Power Management** tab. Un-tick the box for**Allow the computer to turn off this device to save power** . Then hit**OK** to save and exit.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587decc3276b5.png)

---

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135408/19272" target="_top" id="2135408">
  <img src="//a.impactradius-go.com/display-ad/19272-2135408" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135408/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### **Option Three:** **Reinstall or Rollback Realtek Adapter Driver**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand the category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012429/19272" target="_top" id="2012429">
  <img src="//a.impactradius-go.com/display-ad/19272-2012429" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012429/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137214/26400" target="_top" id="2137214">
  <img src="//a.impactradius-go.com/display-ad/26400-2137214" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137214/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-mastering-the-art-of-instagram-highlight-curation/"><u>[New] In 2024, Mastering the Art of Instagram Highlight Curation</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-streamlined-strategy-to-create-your-custom-youtube-queue/"><u>[New] Streamlined Strategy to Create Your Custom YouTube Queue</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-voyage-for-valuables-5-prime-map-expeditions-for-2024/"><u>[New] Voyage for Valuables 5 Prime Map Expeditions for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-nvidia-drivers-not-installing-2024/"><u>[SOLVED] NVIDIA Drivers Not Installing – 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-optimizing-your-hp-experience-expert-guide-to-screen-capture-for-2024/"><u>[Updated] Optimizing Your HP Experience Expert Guide to Screen Capture for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-handheld-gyro-stabilization-upgrade/"><u>2024 Approved Handheld Gyro Stabilization Upgrade</u></a></li>
<li><a href="https://driver-error.techidaily.com/boosting-performance-win11-and-deathadder-drivers/"><u>Boosting Performance: Win11 & DeathAdder Drivers</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-unresponsive-serial-ports-on-windows-os/"><u>Fixing Unresponsive Serial Ports on Windows OS</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-change-credit-card-from-your-iphone-8-apple-id-and-apple-pay-by-drfone-ios/"><u>How to Change Credit Card from Your iPhone 8 Apple ID and Apple Pay</u></a></li>
<li><a href="https://program-issues.techidaily.com/how-to-fix-origin-failed-to-launch-on-windows-10-and-11/"><u>How to Fix 'Origin Failed to Launch' On Windows 10 & 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/ideport0-fault-alarm-triggered/"><u>Ideport0 Fault Alarm Triggered</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-optimizing-latency-for-real-time-obs-viewing/"><u>In 2024, Optimizing Latency for Real-Time OBS Viewing</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-6-appsservices-to-trace-any-lava-agni-2-5g-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, Top 6 Apps/Services to Trace Any Lava Agni 2 5G Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/logitech-brio-webcam-doesnt-show-in-windows-after-recent-update-a-quick-fix-for-you-all-105-answered/"><u>Logitech Brio Webcam Doesn't Show in Windows After Recent Update - A Quick Fix for You All (10/5) [Answered]</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-non-recognized-device-hurdles-in-win-78/"><u>Overcoming Non-Recognized Device Hurdles in Win 7/8</u></a></li>
<li><a href="https://driver-error.techidaily.com/re-pair-and-recognize-your-logitech-brio-webcam-in-new-pc-version-how-it-worked-for-me-answered/"><u>Re-Pair and Recognize Your Logitech Brio Webcam in New PC Version – How It Worked for Me (Answered)</u></a></li>
<li><a href="https://driver-error.techidaily.com/win1110-resolving-issues-with-stable-sm-bus-drivers/"><u>Win11/10: Resolving Issues with Stable Sm Bus Drivers</u></a></li>
</ul></div>

