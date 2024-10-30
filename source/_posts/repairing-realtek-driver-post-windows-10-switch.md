---
title: Repairing Realtek Driver Post-Windows 10 Switch
date: 2024-10-23T21:07:26.589Z
updated: 2024-10-30T00:32:07.090Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Repairing Realtek Driver Post-Windows 10 Switch
excerpt: This Article Describes Repairing Realtek Driver Post-Windows 10 Switch
thumbnail: https://thmb.techidaily.com/2e8e3dda0fc4dbabc8c416bc34f849f91c6baaf77284dc2416882391f7639fad.jpg
---

## Repairing Realtek Driver Post-Windows 10 Switch

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037358/7443" target="_top" id="2037358">
  <img src="//a.impactradius-go.com/display-ad/7443-2037358" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037358/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151855/7443" target="_top" id="2151855">
  <img src="//a.impactradius-go.com/display-ad/7443-2151855" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151855/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

---

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137229/26400" target="_top" id="2137229">
  <img src="//a.impactradius-go.com/display-ad/26400-2137229" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137229/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### **Option Three:** **Reinstall or Rollback Realtek Adapter Driver**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand the category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416">
  <img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

 Hit**OK** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134223/18498" target="_top" id="2134223">
  <img src="//a.impactradius-go.com/display-ad/18498-2134223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134223/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4) Go to the menu bar on the top and click the button for **Scan for hardware changes** .  
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee9a707c2.png)

 5) Windows will help you automatically install the correct driver that it can find. But there is no guarantee that the new driver is going to work since Windows has provided the not working one originally.

 If you clearly remember that your Ethernet stops working after you update to a certain version of the driver, it is suggested that you roll it back to the stage where it was working well.

---

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118311/7443" target="_top" id="2118311">
  <img src="//a.impactradius-go.com/display-ad/7443-2118311" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118311/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-support.techidaily.com/new-navigating-the-art-of-3d-text-rendering-in-ps/"><u>[New] Navigating the Art of 3D Text Rendering in PS</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-hidden-treasures-on-youtube-understanding-unlisted-footage/"><u>[Updated] 2024 Approved Hidden Treasures on YouTube Understanding 'Unlisted' Footage</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-switch-onoff-youtubes-pip-mode-on-your-iphone/"><u>[Updated] 2024 Approved Switch On/Off YouTube's PIP Mode on Your iPhone</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-unlocking-the-art-of-iphone-podcast-downloads-with-ease/"><u>2024 Approved Unlocking the Art of iPhone Podcast Downloads with Ease</u></a></li>
<li><a href="https://driver-error.techidaily.com/a-comprehensible-guide-to-updating-razers-bios-driver-for-pc-users/"><u>A Comprehensible Guide to Updating Razer's BIOS Driver for PC Users</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/discover-the-15-greatest-free-applications-for-effortless-program-removal/"><u>Discover the 15 Greatest Free Applications for Effortless Program Removal</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-huawei-nova-y91-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On Huawei Nova Y91 | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/from-inactive-to-active-status/"><u>From Inactive to Active Status</u></a></li>
<li><a href="https://driver-error.techidaily.com/hardware-integration-limitation-for-graphic-driver/"><u>Hardware Integration Limitation for Graphic Driver</u></a></li>
<li><a href="https://driver-error.techidaily.com/name-seek-opengl-drivers-for-intels-chipset/"><u>Name Seek: OpenGL Drivers for Intel's Chipset</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-common-problems-with-hp-keyboards-a-comprehensive-guide/"><u>Resolving Common Problems with HP Keyboards: A Comprehensive Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-unsupported-hardware-errors-with-your-current-software-suite/"><u>Resolving Unsupported Hardware Errors with Your Current Software Suite</u></a></li>
<li><a href="https://extra-information.techidaily.com/resurrecting-windows-photo-viewer-a-compreehr-guide-for-win10-users/"><u>Resurrecting Windows Photo Viewer - A Compreehr Guide for Win10 Users</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/step-by-step-tutorial-restoring-audio-input-on-windows-11-pcs/"><u>Step-by-Step Tutorial: Restoring Audio Input on Windows 11 PCs</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-samsung-galaxy-s24-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Samsung Galaxy S24 Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/trouble-locating-your-new-pcs-prodigy-cam-no-more-stress-got-answers-and-fixes-to-look-into-fixed/"><u>Trouble Locating Your New PC's Prodigy Cam? No More Stress - Got Answers and Fixes to Look Into [Fixed]</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721104701290-windows-users-solve-your-wireless-keyboard-problem-today/"><u>Windows Users: Solve Your Wireless Keyboard Problem Today!</u></a></li>
</ul></div>

