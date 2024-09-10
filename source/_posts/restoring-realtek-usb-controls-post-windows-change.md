---
title: Restoring Realtek USB Controls Post-Windows Change
date: 2024-09-09T03:09:22.822Z
updated: 2024-09-10T03:09:22.822Z
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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134244/18498" target="_top" id="2134244">
  <img src="//a.impactradius-go.com/display-ad/18498-2134244" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134244/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://review-au.sjv.io/c/5597632/2098701/14409" target="_top" id="2098701">
  <img src="//a.impactradius-go.com/display-ad/14409-2098701" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098701/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de65b229a9.png)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137226/26400" target="_top" id="2137226">
  <img src="//a.impactradius-go.com/display-ad/26400-2137226" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137226/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 4) Go to**Advanced** tab, then choose**Speed & Duplex** option on the left side of the pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de6ed4d026.png)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139116/17108" target="_top" id="2139116">
  <img src="//a.impactradius-go.com/display-ad/17108-2139116" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139116/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 5) On the**Value** bar, change the default Auto Negotiation to **100 Mbps Full Duplex**  or some other options accordingly. We chose**100 Mbps Full Duplex** here, but yours could be different.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deb007e7e1.png)

 6) Now on the left side of the pane, choose**Energy Efficient Ethernet** option, then change the Value to**Disabled** . After the changes, hit**OK** to save.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deab52d9e0.png)

 7) Still, in the**Properties** window, this time, let’s go to**Power Management** tab. Un-tick the box for**Allow the computer to turn off this device to save power** . Then hit**OK** to save and exit.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587decc3276b5.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118312/7443" target="_top" id="2118312">
  <img src="//a.impactradius-go.com/display-ad/7443-2118312" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118312/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
---

### **Option Three:** **Reinstall or Rollback Realtek Adapter Driver**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand the category**Network adapters** .
<!-- affiliate ads begin -->
<span id="1983582">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983582.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983582">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983582.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983582%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983582/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .
<!-- affiliate ads begin -->
<span id="1374820">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1374820.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1374820">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1374820.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1374820%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1374820/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2005184/22899" target="_top" id="2005184">
  <img src="//a.impactradius-go.com/display-ad/22899-2005184" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005184/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Hit**OK** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136625/26400" target="_top" id="2136625">
  <img src="//a.impactradius-go.com/display-ad/26400-2136625" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136625/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 4) Go to the menu bar on the top and click the button for **Scan for hardware changes** .  
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee9a707c2.png)

 5) Windows will help you automatically install the correct driver that it can find. But there is no guarantee that the new driver is going to work since Windows has provided the not working one originally.

 If you clearly remember that your Ethernet stops working after you update to a certain version of the driver, it is suggested that you roll it back to the stage where it was working well.

---

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115946/19272" target="_top" id="2115946">
  <img src="//a.impactradius-go.com/display-ad/19272-2115946" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115946/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Option Four: Update the Realtek Driver**

 The steps above may help you resolve the issue, but if they don’t, you can try to update the Realtek driver. If you don’t have time, patience, or computer skills to update the driver manually,  you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/) .**

**IMPORTANT:**  If you can’t have access to the internet due to the network driver issues, you can use **[Driver Easy Offline Scan Feature](https://tools.techidaily.com/drivereasy/download/)**  to download and install a new network driver.

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version, it takes just 2 clicks (and you get full support and a 30-day money-back guarantee):

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2023/03/Driver-Easy-download-needed-1200x900.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115927/19272" target="_top" id="2115927">
  <img src="//a.impactradius-go.com/display-ad/19272-2115927" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115927/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-effortless-embedding-techniques-for-streaming-video-in-presentations/"><u>[New] In 2024, Effortless Embedding Techniques for Streaming Video in Presentations</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-turned-off-core-isolation-for-wdcsam64prewin8sys/"><u>[Resolved] Turned OFF Core Isolation for wdcsam64_prewin8.sys</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-iphone-mtp-usb-device-driver-issue/"><u>[Solved] iPhone MTP USB Device Driver Issue</u></a></li>
<li><a href="https://driver-error.techidaily.com/status-change-dev-driver-integrated/"><u>[Status Change: Dev Driver Integrated]</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-truthful-insights-into-recordcast-functionality/"><u>[Updated] 2024 Approved Truthful Insights Into RecordCast Functionality</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-navigating-through-paid-product-evaluations-online/"><u>2024 Approved Navigating Through Paid Product Evaluations Online</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/drone-balance-7-top-rated-gimbals/"><u>Drone Balance 7 Top-Rated Gimbals</u></a></li>
<li><a href="https://driver-error.techidaily.com/effective-fixes-for-non-functional-qualcomm-atheros-bluetooth-drivers-on-windows-10/"><u>Effective Fixes for Non-Functional Qualcomm Atheros Bluetooth Drivers on Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-the-default-radeon-wattman-driver-issue-a-step-by-step-guide/"><u>Fixing the Default Radeon Wattman Driver Issue: A Step-by-Step Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-the-wireless-keyboard-connection-issue-on-pc-a-step-by-step-guide/"><u>Fixing the Wireless Keyboard Connection Issue on PC: A Step-by-Step Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/gadget-disallows-car-load/"><u>Gadget Disallows Car Load</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-vivo-y27-5g-location-is-wrong-drfone-by-drfone-virtual-android/"><u>How to Fix My Vivo Y27 5G Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-successfully-launch-battleye-service-after-encountering-driver-initialization-error-1450/"><u>How to Successfully Launch BattlEye Service After Encountering Driver Initialization Error 1450</u></a></li>
<li><a href="https://driver-error.techidaily.com/intel-adapter-missing-system-drive-incompatibility/"><u>Intel Adapter Missing: System Drive Incompatibility</u></a></li>
<li><a href="https://driver-error.techidaily.com/keyboard-fixed-operating-smoothly-on-windows-11/"><u>Keyboard Fixed, Operating Smoothly on Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/keyboard-problem-in-win-10-system/"><u>Keyboard Problem in Win 10 System</u></a></li>
<li><a href="https://driver-error.techidaily.com/macos-high-sierra-not-detecting-dell-xps-laptop-issue-resolved/"><u>MacOS High Sierra Not Detecting Dell XPS Laptop, Issue Resolved</u></a></li>
<li><a href="https://os-tips.techidaily.com/must-have-budget-friendly-iphone-add-on-for-all-trips/"><u>Must-Have Budget-Friendly iPhone Add-On for All Trips!</u></a></li>
<li><a href="https://driver-error.techidaily.com/no-complications-for-driver-reinstallation/"><u>No Complications for Driver Reinstallation</u></a></li>
<li><a href="https://discover-blog.techidaily.com/pressing-issues-exploring-how-analytics-automation-and-process-intelligence-complement-each-other-in-our-upcoming-webinar/"><u>Pressing Issues: Exploring How Analytics Automation & Process Intelligence Complement Each Other in Our Upcoming Webinar</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/protecting-imessage-and-mail-on-icloud-the-role-of-dual-authentication/"><u>Protecting iMessage and Mail on iCloud: The Role of Dual-Authentication</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-resolving-skype-video-issues-on-windows-11/"><u>Quick Solutions: Resolving Skype Video Issues on Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/rapid-response-to-mtp-connection-issues/"><u>Rapid Response to MTP Connection Issues</u></a></li>
<li><a href="https://driver-error.techidaily.com/realtek-network-card-unresponsive-after-win11-transition-solved/"><u>Realtek Network Card Unresponsive After Win11 Transition (Solved)</u></a></li>
<li><a href="https://driver-error.techidaily.com/recovery-of-missing-bluetooth-restore-it-now/"><u>Recovery Of: Missing BlueTooth, Restore It Now</u></a></li>
<li><a href="https://driver-error.techidaily.com/reviving-your-dead-wireless-keyboard-a-step-by-step-fix-for-windows-users/"><u>Reviving Your Dead Wireless Keyboard: A Step-by-Step Fix for Windows Users</u></a></li>
<li><a href="https://driver-error.techidaily.com/solve-instant-amd-software-issues/"><u>Solve Instant AMD Software Issues</u></a></li>
<li><a href="https://driver-error.techidaily.com/successful-repair-working-keyboard-on-windows-11/"><u>Successful Repair: Working Keyboard on Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/successfully-repairing-non-functional-qualcomm-atheros-bluetooth-drivers-for-windows-10/"><u>Successfully Repairing Non-Functional Qualcomm Atheros Bluetooth Drivers for Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/the-ultimate-solution-for-the-inoperative-keyboard-on-your-beloved-hp-notebook-fix-it-today-article-title-article-title-with-phase-descriptions402-character5/"><u>The Ultimate Solution for the 'Inoperative' Keyboard on Your Beloved HP Notebook - Fix It Today! (Article Title) — Article Title with Phase Descriptions—402 Characters</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-non-responsive-bluetooth-keyboards-in-windows-environments/"><u>Troubleshooting Non-Responsive Bluetooth Keyboards in Windows Environments</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-the-social-sphere-selecting-the-best-marketing-focused-podcasts-for-todays-businesses/"><u>Updated 2024 Approved The Social Sphere Selecting the Best Marketing-Focused Podcasts for Todays Businesses</u></a></li>
<li><a href="https://driver-error.techidaily.com/urgently-need-stopping-my-bluetooth-in-windows-help-please/"><u>Urgently Need Stopping My Bluetooth in Windows – Help Please?</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-11-system-stabilized-keyboard-ok/"><u>Windows 11 System Stabilized: Keyboard OK</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/eyxh-kalwn-piatwn-gkreman/"><u>Ευχή Καλών Πιάτων Γκρεμάν</u></a></li>
</ul></div>
