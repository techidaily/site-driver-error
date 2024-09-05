---
title: Reinstating Functionality to Realtek LAN Drivers
date: 2024-09-04T12:46:17.019Z
updated: 2024-09-05T12:46:17.019Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Reinstating Functionality to Realtek LAN Drivers
excerpt: This Article Describes Reinstating Functionality to Realtek LAN Drivers
thumbnail: https://thmb.techidaily.com/836b19a99b81c291189dfbcf8add59f634c1fb8aacdfd70319b10cdaec65e638.jpg
---

## Reinstating Functionality to Realtek LAN Drivers

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

### **Option Three:** **Reinstall or Rollback Realtek Adapter Driver**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand the category**Network adapters** .
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094419/7443" target="_top" id="2094419">
  <img src="//a.impactradius-go.com/display-ad/7443-2094419" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094419/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094480/7443" target="_top" id="2094480">
  <img src="//a.impactradius-go.com/display-ad/7443-2094480" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094480/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

 Hit**OK** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)

<!-- affiliate ads begin -->
<span id="1982459">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982459.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982459">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982459.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982459%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982459/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 4) Go to the menu bar on the top and click the button for **Scan for hardware changes** .  
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee9a707c2.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2030385/7443" target="_top" id="2030385">
  <img src="//a.impactradius-go.com/display-ad/7443-2030385" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2030385/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 5) Windows will help you automatically install the correct driver that it can find. But there is no guarantee that the new driver is going to work since Windows has provided the not working one originally.

 If you clearly remember that your Ethernet stops working after you update to a certain version of the driver, it is suggested that you roll it back to the stage where it was working well.

---

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484939/16446" target="_top" id="1484939">
  <img src="//a.impactradius-go.com/display-ad/16446-1484939" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484939/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1531882">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1531882.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1531882">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1531882.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1531882%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1531882/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-ultimate-fb-video-player-guide-top-picks-listed/"><u>[New] 2024 Approved  Ultimate FB Video Player Guide  Top Picks Listed</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-classroom-vids-essential-editing-strategies/"><u>[New] Classroom Vids  Essential Editing Strategies</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-4-ways-record-your-screen-on-windows-8/"><u>[New] In 2024, 4 Ways Record Your Screen On Windows 8</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-setting-the-stage-for-seamless-video-playback-in-facebook-network/"><u>[New] In 2024, Setting the Stage for Seamless Video Playback in Facebook Network</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-uncovering-the-invisible-how-to-inspect-facebooks-data-trails/"><u>[New] Uncovering the Invisible  How to Inspect Facebook's Data Trails</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-examine-recorded-conversation/"><u>[Updated] 2024 Approved  Examine Recorded Conversation</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-inventory-management/"><u>[Updated] In 2024, Inventory Management</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-instantly-retire-your-digital-diaries-fb-for-2024/"><u>[Updated] Instantly Retire Your Digital Diaries (FB) for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-leveraging-hashtags-to-skyrocket-your-engagement-for-2024/"><u>[Updated] Leveraging Hashtags to Skyrocket Your Engagement for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-the-ultimate-guide-to-utilizing-zero-cost-clocks/"><u>2024 Approved  The Ultimate Guide to Utilizing Zero-Cost Clocks</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/canoscan-lide-120-driver-download-and-update/"><u>CanoScan LiDE 120 Driver Download & Update</u></a></li>
<li><a href="https://driver-error.techidaily.com/decoding-technology-high-performance-insights-from-toms-world/"><u>Decoding Technology: High-Performance Insights From Tom's World</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-realme-12-pro-5g-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Realme 12 Pro 5G Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/easy-steps-to-enter-the-computers-motherboard-information-in-windows-11/"><u>Easy Steps to Enter the Computer's Motherboard Information in Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/easy-troubleshooting-guide-for-installed-device-drivers-windows-10-8-and-7-issue-solved/"><u>Easy Troubleshooting Guide for Installed Device Drivers: Windows 10, 8 and 7 (ISSUE SOLVED)</u></a></li>
<li><a href="https://driver-error.techidaily.com/easy-tutorial-for-enabling-safe-mode-and-updating-intel-gpu-software-on-win8-computers/"><u>Easy Tutorial for Enabling Safe Mode & Updating Intel GPU Software on Win8 Computers</u></a></li>
<li><a href="https://driver-error.techidaily.com/enhanced-sm-bus-functionality-in-win11/"><u>Enhanced Sm Bus Functionality in Win11</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-the-gtx-warton-950-code-43-problem-in-windows-11-comprehensive-guide/"><u>Fixing the GTX Warton 950 'Code 43' Problem in Windows 11 - Comprehensive Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-address-and-fix-driver-validation-problems-during-computer-updates/"><u>How to Address and Fix Driver Validation Problems During Computer Updates</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-resolve-critical-process-died-snipped-0x0000007e-blue-screen-issue-on-windows-vista-and-7/"><u>How to Resolve Critical Process Died, Snipped 0X0000007E Blue Screen Issue on Windows Vista and 7</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-update-your-idt-software-for-new-hardware-support-and-avoid-common-issues/"><u>How to Update Your IDT Software for New Hardware Support and Avoid Common Issues</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-remove-flashlight-from-iphone-se-2022-lock-screen-drfone-by-drfone-ios/"><u>In 2024, How To Remove Flashlight From iPhone SE (2022) Lock Screen | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/loading-wudfrd-driver-encountered-problem-id-219/"><u>Loading WudfRd Driver Encountered Problem (ID: 219)</u></a></li>
<li><a href="https://driver-error.techidaily.com/mastered-disk-drive-troubleshooting/"><u>Mastered Disk Drive Troubleshooting</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcome-radiosyncrasies-with-ease-windows-style/"><u>Overcome Radiosyncrasies with Ease, Windows Style!</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-incompatibilities-fixing-unsupported-device-alerts-in-idt-software-systems/"><u>Overcoming Incompatibilities: Fixing Unsupported Device Alerts in IDT Software Systems</u></a></li>
<li><a href="https://driver-error.techidaily.com/pioneering-pcs-uncovered-in-storage-boxes-housekeepers-stumble-upon-original-q1-desktops-with-vintage-intel-processing-technology-and-minimal-ram/"><u>Pioneering PCs Uncovered in Storage Boxes: Housekeepers Stumble Upon Original Q1 Desktops with Vintage Intel Processing Technology and Minimal RAM</u></a></li>
<li><a href="https://fix-guide.techidaily.com/realme-narzo-60-pro-5g-stuck-on-screen-finding-solutions-for-stuck-on-boot-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Realme Narzo 60 Pro 5G Stuck on Screen – Finding Solutions For Stuck on Boot | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/repairing-missing-windows-enter-functionality/"><u>Repairing Missing Windows Enter Functionality</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-qualcomm-atheros-bluetooth-malfunction-on-windows-11-systems/"><u>Resolved: Qualcomm Atheros Bluetooth Malfunction on Windows 11 Systems</u></a></li>
<li><a href="https://driver-error.techidaily.com/revitalized-keyboard-works-flawlessly-post-fix-in-windows-11/"><u>Revitalized Keyboard, Works Flawlessly Post-Fix in Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-post-update-issues-with-realtek-lan-controls/"><u>Solving Post-Update Issues with Realtek LAN Controls</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-screen-flip-issues-on-asus-notebooks-a-guide/"><u>Solving Screen Flip Issues on Asus Notebooks - A Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-the-itbm-driver-unavailable-issue-with-simple-steps/"><u>Solving the 'ITBM Driver Unavailable' Issue with Simple Steps</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-windows-sm-bus-controller-hurdles/"><u>Solving Windows SM Bus Controller Hurdles</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-solution-to-install-essential-device-drivers-missing-on-windows-computers/"><u>Step-by-Step Solution to Install Essential Device Drivers Missing on Windows Computers</u></a></li>
<li><a href="https://driver-error.techidaily.com/the-evolution-and-functionality-of-compatible-usb-composite-gadgets-final-answer/"><u>The Evolution and Functionality of Compatible USB Composite Gadgets [FINAL ANSWER]</u></a></li>
<li><a href="https://driver-error.techidaily.com/the-ultimate-guide-stop-windows-11s-persistent-bluetooth/"><u>The Ultimate Guide: Stop Windows 11'S Persistent Bluetooth</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-and-fixing-mtp-issues-in-iphones-for-smooth-usb-connectivity/"><u>Troubleshooting and Fixing MTP Issues in iPhones for Smooth USB Connectivity</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-and-fixing-the-absent-cpu-accelerator-driver-on-your-windows-10-machine-solved/"><u>Troubleshooting and Fixing the Absent CPU Accelerator Driver on Your Windows 10 Machine [Solved]</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/tunemaster-pro-how-to-download-and-assess-for-2024/"><u>TuneMaster Pro  How to Download & Assess for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/universal-drivers-package-pci-windows-compatible/"><u>Universal Drivers Package (PCI Windows Compatible)</u></a></li>
<li><a href="https://driver-error.techidaily.com/unlocking-lenovos-full-potential-in-windows-11/"><u>Unlocking Lenovo's Full Potential in Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/win11-mystery-of-missing-disk-drive-explained/"><u>Win11: Mystery of Missing Disk Drive Explained</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-1110-fix-pci-controller-loss/"><u>Windows 11/10: Fix PCI Controller Loss</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-wireless-mouse-disconnects-regularly/"><u>Windows Wireless Mouse Disconnects Regularly</u></a></li>
<li><a href="https://driver-error.techidaily.com/winning-the-battle-against-broken-qualcomm-atheros-bluetooth-drivers-on-windows-10/"><u>Winning the Battle Against Broken Qualcomm Atheros Bluetooth Drivers on Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/wireless-mastery-quick-solutions-for-windows-users/"><u>Wireless Mastery: Quick Solutions for Windows Users</u></a></li>
</ul></div>
