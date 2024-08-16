---
title: Windows Change Affects Realtek LAN Drivers Negatively
date: 2024-08-15T06:42:19.696Z
updated: 2024-08-16T06:42:19.696Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Windows Change Affects Realtek LAN Drivers Negatively
excerpt: This Article Describes Windows Change Affects Realtek LAN Drivers Negatively
thumbnail: https://thmb.techidaily.com/05c8c6fd73c6fec22a2f538188954b893a706bcf3ee5edf935baeb75dd083d47.jpg
---

## Windows Change Affects Realtek LAN Drivers Negatively

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
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de25ac8c94.jpg)

 2) Type in the following command:

netsh int ip reset c:\resetlog.txt

 Make sure that you have made no typo and hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de2ea5a2ef.png)

 This will help you reset your TCP/IP (Transmission Control Protocol/Internet Protocol). To make it easier to understand, TCP/IP is the language that your computer uses to communicate with the outside world. Reseting TCP/IP will help you revert your Internet settings to the stage where it still works.

---

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Option Two:** **Change Settings in Network Adapter Properties**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
3) Then right-click Realtek PCIe GBE Family Controller option and choose **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de65b229a9.png)

 4) Go to**Advanced** tab, then choose**Speed & Duplex** option on the left side of the pane.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

 Hit**OK** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)

 4) Go to the menu bar on the top and click the button for **Scan for hardware changes** .  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-tips.techidaily.com/new-add-background-scores-via-premiere-pro/"><u>[New] Add Background Scores via Premiere Pro</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-google-meet-for-non-paying-professionals-complete-insights-and-tips/"><u>[New] In 2024, Google Meet for Non-Paying Professionals  Complete Insights and Tips</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-instagram-video-orientation-whats-the-flip/"><u>[New] Instagram Video Orientation - What's the Flip?</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-intel-wi-fi-6-ax201-not-working/"><u>[SOLVED] Intel Wi-Fi 6 AX201 Not Working</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-investigating-whether-photostabilizer-transforms-image-quality-for-2024/"><u>[Updated] Investigating Whether PhotoStabilizer Transforms Image Quality for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-chromebooks-and-hp-perfect-your-video-capture/"><u>2024 Approved  Chromebooks and HP  Perfect Your Video Capture</u></a></li>
<li><a href="https://common-error.techidaily.com/bypassing-the-hassle-of-error-8007000e-on-your-pc/"><u>Bypassing the Hassle of Error 8007000E on Your PC</u></a></li>
<li><a href="https://driver-error.techidaily.com/cd-drive-absence-windows-11-issue-solved/"><u>CD Drive Absence: Windows 11 Issue Solved</u></a></li>
<li><a href="https://driver-error.techidaily.com/correcting-erroneous-sections-in-service-inf/"><u>Correcting Erroneous Sections in Service INF</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-mass-storage-controller-driver-issue-on-windows-11-solved/"><u>Fix Mass Storage Controller Driver Issue on Windows 11 [Solved]</u></a></li>
<li><a href="https://win-dash.techidaily.com/fixing-connectivity-problems-the-ultimate-guide-to-asus-pce-ac56-drivers-on-modern-windows-os/"><u>Fixing Connectivity Problems: The Ultimate Guide to ASUS PCE-AC56 Drivers on Modern Windows OS</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721099236532-happy-campers-wacom-connected-everywhere/"><u>Happy Campers: Wacom Connected, Everywhere!</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-fix-imaging-devices-missing-in-windows-10/"><u>How To Fix Imaging Devices Missing in Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-repair-non-verified-hardware-drivers-for-your-computer/"><u>How to Repair: Non-Verified Hardware Drivers for Your Computer</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-successfully-update-your-hcmon-driver-and-avoid-common-mistakes/"><u>How to Successfully Update Your HCMon Driver and Avoid Common Mistakes</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-google-play-location-on-xiaomi-redmi-note-12-4g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Google Play Location On Xiaomi Redmi Note 12 4G | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-key-features-of-mozillas-innovative-popup-window/"><u>In 2024, Key Features of Mozilla's Innovative Popup Window</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-refurbished-apple-iphone-xr-everything-you-need-to-know-drfone-by-drfone-transfer-from-ios/"><u>In 2024, Refurbished Apple iPhone XR Everything You Need to Know | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/keyboard-driver-interrupts-reconciled/"><u>Keyboard Driver Interrupts Reconciled</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/list-of-pokemon-go-joysticks-on-apple-iphone-se-2020-drfone-by-drfone-virtual-ios/"><u>List of Pokémon Go Joysticks On Apple iPhone SE (2020) | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/quick-solution-found-resolving-windows-11s-stubborn-bluescreen-issue-heres-how-no-more-headaches/"><u>Quick Solution Found! Resolving Windows 11'S Stubborn Bluescreen Issue - Here’s How (No More Headaches!)</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolve-vanishing-signal-proc-on-pcs/"><u>Resolve Vanishing Signal Proc on PCs</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-problem-unsupported-intelamd-drivers-not-supported-by-premiere-pro/"><u>Resolved Problem: Unsupported Intel/AMD Drivers Not Supported by Premiere Pro</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-non-responsive-hp-wireless-keyboard-problems-effective-solutions-inside/"><u>Resolving Non-Responsive HP Wireless Keyboard Problems - Effective Solutions Inside</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-the-default-radeon-wattman-issue-crashes-fixed-and-system-restored/"><u>Resolving the Default Radeon Wattman Issue: Crashes Fixed & System Restored</u></a></li>
<li><a href="https://driver-error.techidaily.com/resource-allocation-hurdles-in-device/"><u>Resource Allocation Hurdles in Device</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-issues-with-older-usb-composite-devices-for-better-compatibility-today/"><u>Solving Issues with Older USB Composite Devices for Better Compatibility Today</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-fix-overcoming-challenges-in-hcmon-driver-implementation/"><u>Step-by-Step Fix: Overcoming Challenges in Hcmon Driver Implementation</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-guide-to-correcting-access-denied-for-proper-usb-drivers-setup/"><u>Step-by-Step Guide to Correcting 'Access Denied' For Proper USB Drivers Setup</u></a></li>
<li><a href="https://driver-error.techidaily.com/triumph-over-missing-touchpad-driver-solutions-explored/"><u>Triumph Over Missing Touchpad Driver: Solutions Explored</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-the-bsod-error-code-0x0000007e-in-windows-7-a-step-by-step-guide/"><u>Troubleshooting the BSoD Error Code 0X0000007E in Windows 7: A Step-by-Step Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-unsupported-hardware-recognition-error-with-idt-software/"><u>Troubleshooting: Unsupported Hardware Recognition Error with IDT Software</u></a></li>
<li><a href="https://driver-error.techidaily.com/uncomplicating-windows-ndis-challenges/"><u>Uncomplicating Windows' NDIS Challenges</u></a></li>
<li><a href="https://driver-error.techidaily.com/understanding-and-resolving-aged-usb-composite-device-problems/"><u>Understanding and Resolving Aged USB Composite Device Problems</u></a></li>
<li><a href="https://driver-error.techidaily.com/understanding-and-troubleshooting-the-legacy-usb-composite-device/"><u>Understanding and Troubleshooting the Legacy USB Composite Device</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-11-addressing-bus-controllers/"><u>Windows 11: Addressing Bus Controllers</u></a></li>
</ul></div>
