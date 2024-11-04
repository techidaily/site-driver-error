---
title: Fixing Ethernet Driver Not Working After Upgrade
date: 2024-10-31T18:09:53.505Z
updated: 2024-11-04T21:43:40.284Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Fixing Ethernet Driver Not Working After Upgrade
excerpt: This Article Describes Fixing Ethernet Driver Not Working After Upgrade
thumbnail: https://thmb.techidaily.com/6304baca930779dbe6ae3412704c6577c66eb8d788b6fe6b67667ffd209c0a5f.jpg
---

## Fixing Ethernet Driver Not Working After Upgrade

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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137215/26400" target="_top" id="2137215">
  <img src="//a.impactradius-go.com/display-ad/26400-2137215" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137215/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 5) On the**Value** bar, change the default Auto Negotiation to **100 Mbps Full Duplex**  or some other options accordingly. We chose**100 Mbps Full Duplex** here, but yours could be different.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deb007e7e1.png)

 6) Now on the left side of the pane, choose**Energy Efficient Ethernet** option, then change the Value to**Disabled** . After the changes, hit**OK** to save.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deab52d9e0.png)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139109/17108" target="_top" id="2139109">
  <img src="//a.impactradius-go.com/display-ad/17108-2139109" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139109/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 7) Still, in the**Properties** window, this time, let’s go to**Power Management** tab. Un-tick the box for**Allow the computer to turn off this device to save power** . Then hit**OK** to save and exit.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587decc3276b5.png)

---

### **Option Three:** **Reinstall or Rollback Realtek Adapter Driver**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand the category**Network adapters** .

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134493/18498" target="_top" id="2134493">
  <img src="//a.impactradius-go.com/display-ad/18498-2134493" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134493/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .

<!-- affiliate ads begin -->
<span id="1265663">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1265663.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/4482-1265663">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1265663.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fmartinic.evyy.net%2Fc%2F5597632%2F1265663%2F4482'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1265663/4482" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137229/26400" target="_top" id="2137229">
  <img src="//a.impactradius-go.com/display-ad/26400-2137229" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137229/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Hit**OK** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)

 4) Go to the menu bar on the top and click the button for **Scan for hardware changes** .  
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee9a707c2.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896527/19272" target="_top" id="1896527">
  <img src="//a.impactradius-go.com/display-ad/19272-1896527" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896527/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://driver-error.techidaily.com/download-samsung-android-driver-for-windows/"><u>[Download] Samsung Android Driver for Windows</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-perfecting-your-sims-4-live-action/"><u>[New] 2024 Approved Perfecting Your Sims 4 Live Action</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-the-ultimate-visual-fidelity-in-a-box-eizos-cg318-4k/"><u>[New] The Ultimate Visual Fidelity in a Box – EIZO's CG318-4K</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-the-a-list-playbook-swiftly-climb-the-social-ladder-on-instagram-with-these-essentials/"><u>[Updated] 2024 Approved The A-List Playbook Swiftly Climb the Social Ladder on Instagram with These Essentials</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-professional-webcam-recording-solutions-explored-for-2024/"><u>[Updated] Professional WebCam Recording Solutions Explored for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ing-your-channel-strategies-for-skyrocketing-view-counts/"><u>Boosting Your Channel Strategies for Skyrocketing View Counts</u></a></li>
<li><a href="https://driver-error.techidaily.com/conquered-nmi-driver-malfunction/"><u>Conquered NMI Driver Malfunction</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/easy-tutorial-on-inserting-captions-in-instagram-story-posts-for-better-engagement/"><u>Easy Tutorial on Inserting Captions in Instagram Story Posts for Better Engagement</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-enjoy-amazon-prime-shows-without-subtitles-a-users-guide/"><u>How to Enjoy Amazon Prime Shows Without Subtitles - A User's Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-fix-a-non-responsive-qualcomm-atheros-bluetooth-driver-in-windows-10-solutions-unveiled/"><u>How to Fix a Non-Responsive Qualcomm Atheros Bluetooth Driver in Windows 10 - Solutions Unveiled</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-fix-pokemon-go-route-not-working-on-honor-90-gt-drfone-by-drfone-virtual-android/"><u>How to Fix Pokemon Go Route Not Working On Honor 90 GT? | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-fix-qualcomm-atheros-bluetooth-issues-on-windows-10/"><u>How to Fix Qualcomm Atheros Bluetooth Issues on Windows 10</u></a></li>
<li><a href="https://fox-direct.techidaily.com/mastering-the-art-of-decreasing-decibents-a-guide-to-fading-out-sounds/"><u>Mastering the Art of Decreasing Decibents A Guide to Fading Out Sounds</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-the-issue-unrecognized-or-invalid-drivers-installation-on-your-pc/"><u>Resolving the Issue: Unrecognized or Invalid Drivers Installation on Your PC</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-vanishing-bluetooth-issue-guide-to-device-manager/"><u>Solving Vanishing BlueTooth Issue: Guide to Device Manager</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-guide-booting-windows-8-into-safe-mode-and-removing-graphics-drivers/"><u>Step-by-Step Guide: Booting Windows 8 Into Safe Mode & Removing Graphics Drivers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-fix-for-when-your-laptop-stares-back-at-you-with-a-white-screen/"><u>The Ultimate Fix for When Your Laptop Stares Back at You with a White Screen</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-11-hidden-cd-drive-fixed/"><u>Windows 11: Hidden CD Drive Fixed</u></a></li>
<li><a href="https://driver-error.techidaily.com/xbox-360-controller-driver-not-working-on-windows-10-solved/"><u>Xbox 360 Controller Driver Not Working on Windows 10 [Solved]</u></a></li>
</ul></div>

