---
title: Address Realtek LAN Problem Post-Windows 10 Upgrade
date: 2024-08-27T06:58:09.640Z
updated: 2024-08-28T06:58:09.640Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Address Realtek LAN Problem Post-Windows 10 Upgrade
excerpt: This Article Describes Address Realtek LAN Problem Post-Windows 10 Upgrade
thumbnail: https://thmb.techidaily.com/234a90d5c27844c283f4441b2b9e5e76ee9e8064b4a1ba5d5f5c1598b8d0670d.jpg
---

## Address Realtek LAN Problem Post-Windows 10 Upgrade

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

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deb007e7e1.png)

 6) Now on the left side of the pane, choose**Energy Efficient Ethernet** option, then change the Value to**Disabled** . After the changes, hit**OK** to save.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deab52d9e0.png)

 7) Still, in the**Properties** window, this time, let’s go to**Power Management** tab. Un-tick the box for**Allow the computer to turn off this device to save power** . Then hit**OK** to save and exit.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587decc3276b5.png)

---

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Option Three:** **Reinstall or Rollback Realtek Adapter Driver**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand the category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

 Hit**OK** to continue.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://driver-error.techidaily.com/fixed-dark-light-on-asus-keys/"><u>[FIXED] Dark Light on ASUS Keys</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-mastering-alias-transformation-on-google-meet-platforms-for-2024/"><u>[New] Mastering Alias Transformation on Google Meet Platforms for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-strengthen-your-content-identity-inserting-watermarklogo-in-videos/"><u>[New] Strengthen Your Content Identity  Inserting Watermark/Logo in Videos</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-optimized-bus-controller-in-windows-11/"><u>[SOLVED] Optimized Bus Controller in Windows 11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-deciphering-youtubes-shorts-funding-mechanism/"><u>[Updated] 2024 Approved  Deciphering YouTube's Shorts Funding Mechanism</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-quintessential-5-filters-for-depth-video/"><u>[Updated] Quintessential 5 Filters for Depth Video</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-recording-excellence-the-top-screen-recorder-list/"><u>[Updated] Recording Excellence  The Top Screen Recorder List</u></a></li>
<li><a href="https://driver-error.techidaily.com/warning-bluetooth-mouse-not-initializing-on-pc/"><u>[Warning] Bluetooth Mouse Not Initializing on PC</u></a></li>
<li><a href="https://driver-error.techidaily.com/acemagic-commemorates-may-4th-with-a-special-edition-x-wing-themed-gaming-pc-for-enthusiasts/"><u>AceMagic Commemorates May 4Th with a Special Edition X-Wing Themed Gaming PC for Enthusiasts</u></a></li>
<li><a href="https://common-error.techidaily.com/cyclic-redundancy-check-errors-a-comprehensive-guide-to-troubleshooting-and-resolution/"><u>Cyclic Redundancy Check Errors: A Comprehensive Guide to Troubleshooting and Resolution</u></a></li>
<li><a href="https://tech-hub.techidaily.com/explore-the-best-6-tools-for-chatting-with-documents-via-smart-technology/"><u>Explore the Best 6 Tools for Chatting with Documents via Smart Technology</u></a></li>
<li><a href="https://driver-error.techidaily.com/hardware-and-dev-driver-now-in-sync-with-win-os/"><u>Hardware and Dev Driver Now in Sync with Win OS</u></a></li>
<li><a href="https://driver-error.techidaily.com/inf-setup-error-now-corrected-and-validated/"><u>INF Setup Error - Now Corrected & Validated</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/introducing-the-new-magnetic-t-force-siren-cpu-cooler-by-teamgroup-simplifying-your-customization-process/"><u>Introducing the New Magnetic T-Force Siren CPU Cooler by TeamGroup: Simplifying Your Customization Process</u></a></li>
<li><a href="https://driver-error.techidaily.com/irql-issue-bypassed-in-win11-fix/"><u>Irql Issue Bypassed in Win11 Fix</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-gpt-creation-design-your-unique-chatai/"><u>Mastering GPT Creation: Design Your Unique ChatAI</u></a></li>
<li><a href="https://driver-error.techidaily.com/mended-hardware-commanding-glitches/"><u>Mended Hardware Commanding Glitches</u></a></li>
<li><a href="https://driver-error.techidaily.com/optical-drive-missing-windows-11-issue-addressed/"><u>Optical Drive Missing: Windows 11 Issue Addressed</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcome-error-48-in-devmgr/"><u>Overcome Error #48 in DevMgr</u></a></li>
<li><a href="https://driver-error.techidaily.com/reactivating-silenced-microphoneheadset-on-windows-10/"><u>Reactivating Silenced Microphone/Headset on Windows 10</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/reasons-why-pokemon-gps-does-not-work-on-lenovo-thinkphone-drfone-by-drfone-virtual-android/"><u>Reasons why Pokémon GPS does not Work On Lenovo ThinkPhone? | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/seagate-external-drive-detection-issue-solved-in-win11/"><u>Seagate External Drive Detection Issue Solved in Win11</u></a></li>
<li><a href="https://driver-error.techidaily.com/securing-smooth-operation-of-nvidia-drivers/"><u>Securing Smooth Operation of Nvidia Drivers</u></a></li>
<li><a href="https://driver-error.techidaily.com/solutions-what-to-do-when-a-driver-fails-compatibility-check/"><u>Solutions: What to Do When a Driver Fails Compatibility Check</u></a></li>
<li><a href="https://driver-error.techidaily.com/solve-ethernet-adapter-crash-in-thinkcentre-3000/"><u>Solve Ethernet Adapter Crash in ThinkCentre 3000</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-issue-of-unresponsive-keys-on-dell-laptops-practical-solutions/"><u>Solving the Issue of Unresponsive Keys on Dell Laptops: Practical Solutions</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/spotlight-on-huawei-mediapad-m5-elevating-your-viewing-and-listening-pleasure/"><u>Spotlight on Huawei MediaPad M5 – Elevating Your Viewing and Listening Pleasure</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-fix-for-uninitialized-directx-device/"><u>Step-by-Step Fix for 'Uninitialized DirectX Device'</u></a></li>
<li><a href="https://driver-error.techidaily.com/steps-to-stabilize-nvidia-graphics-codes/"><u>Steps to Stabilize Nvidia Graphics Codes</u></a></li>
<li><a href="https://buynow-info.techidaily.com/the-compact-sx620-powershot-for-practical-photography/"><u>The Compact SX620: PowerShot for Practical Photography</u></a></li>
<li><a href="https://driver-error.techidaily.com/the-end-of-the-self-removal-saga-for-nvidia-drivers/"><u>The End of the Self-Removal Saga for Nvidia Drivers</u></a></li>
<li><a href="https://driver-error.techidaily.com/tips-for-fixing-device-conflicts-in-dm/"><u>Tips for Fixing Device Conflicts in DM</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-samsung-galaxy-s23-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Samsung Galaxy S23 Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/unresponsive-keys-issue-in-10/"><u>Unresponsive Keys Issue in 10</u></a></li>
</ul></div>
