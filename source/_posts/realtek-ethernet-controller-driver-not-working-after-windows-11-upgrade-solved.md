---
title: Realtek Ethernet Controller Driver Not Working After Windows 11 Upgrade [Solved]
date: 2024-07-15T06:55:37.600Z
updated: 2024-07-16T06:55:37.600Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Realtek Ethernet Controller Driver Not Working After Windows 11 Upgrade [Solved]
excerpt: This Article Describes Realtek Ethernet Controller Driver Not Working After Windows 11 Upgrade [Solved]
thumbnail: https://thmb.techidaily.com/852437a8f4dc8f33eb3a839d8b7d9a1e3df217c9c33ef7947ef934470397fa43.jpg
---

## Realtek Ethernet Controller Driver Not Working After Windows 11 Upgrade [Solved]

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b91ef1806793.jpg)

 Users have reported that their Realtek PCIe Family Controller (Ethernet) randomly stopped working after they upgraded to Windows 10\. There are still no answers from Microsoft or Realtek as to why would this happen, and this situation happens randomly on different occasions, so there are a lot of solutions that could be of help.

 If this is the problem you are experiencing now, please follow the instructions below to get it fixed by yourself.

[**Option One: Reset TCP/IP**](https://natural-cycles.sjv.io/vmebmr)
[**Option Two: Change Settings in Network Adapter Properties**](https://aofit.pxf.io/mmjyxq)
[**Option Three: Reinstall Realtek Adapter Driver**](https://westkiss.pxf.io/daqnaq)
[**Option Four: Update the Realtek Driver**](https://newchic.sjv.io/jzg4zq)

---

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Option One: Reset TCP/IP**

1) On your keyboard, press the**Windows logo key** , type**cmd** , right-click**Command Prompt** from the results, and select**Run as administrator** .  
  
![how to open Command Prompt as an admin](https://images.drivereasy.com/wp-content/uploads/2023/10/win11-Command-Prompt-Run-as-administrator.jpg)

 When prompted with the following notification, hit**Yes** to continue.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
3) Then right-click Realtek PCIe GBE Family Controller option and choose **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de65b229a9.png)

 4) Go to**Advanced** tab, then choose**Speed & Duplex** option on the left side of the pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de6ed4d026.png)

 5) On the**Value** bar, change the default Auto Negotiation to **100 Mbps Full Duplex**  or some other options accordingly. We chose**100 Mbps Full Duplex** here, but yours could be different.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
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
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
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
<li><a href="https://driver-error.techidaily.com/how-to-stop-self-removal-of-nvidia-drivers/"><u>How To Stop Self-Removal of Nvidia Drivers</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-selective-slideshow-software-for-xrxsx-models/"><u>In 2024, Selective Slideshow Software for Xr/XS/X Models</u></a></li>
<li><a href="https://driver-error.techidaily.com/win11-reliable-multitasking-experience/"><u>Win11: Reliable Multitasking Experience</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-hp-notebook-keys-that-are-not-responding-or-stuck-how-to-fix-in-minutes-article-title-detailed-user-friendly-guide-tech-talker406-chars/"><u>Solving HP Notebook Keys That Are ‘Not Responding’ or Stuck – How To Fix in Minutes (Article Title)– Detailed, User Friendly Guide | Tech Talker—406 Chars</u></a></li>
<li><a href="https://driver-error.techidaily.com/streamlining-windows-10-touchpad-compatibility-elan/"><u>Streamlining Windows 10 Touchpad Compatibility, Elan</u></a></li>
<li><a href="https://driver-error.techidaily.com/driver-installation-woes-learn-how-to-verify-and-correct-unvalidated-drivers-on-your-system/"><u>Driver Installation Woes? Learn How To Verify And Correct Unvalidated Drivers On Your System</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-the-unexpected-reset-of-your-radeon-wattman-stable-performance-now-achievable/"><u>Fixing the Unexpected Reset of Your Radeon Wattman - Stable Performance Now Achievable!</u></a></li>
<li><a href="https://driver-error.techidaily.com/swift-mousing-overcoming-system-stutters/"><u>Swift Mousing: Overcoming System Stutters</u></a></li>
<li><a href="https://driver-error.techidaily.com/easy-steps-to-update-or-install-drivers-on-windows-computers-windows-7-8-and-10-covered/"><u>Easy Steps to Update or Install Drivers on Windows Computers - Windows 7, 8 & 10 Covered</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-how-to-promote-youtube-channel-step-by-step/"><u>New How to Promote YouTube Channel Step-by-Step</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/ideal-fullscreen-recording-software-roundup-pcmac-edition/"><u>Ideal Fullscreen Recording Software Roundup  PC/Mac Edition</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-pc-wont-stop-responding-when-i-try-to-turn-off-the-built-in-bluetooth-adapter-any-ideas/"><u>Windows PC Won't Stop Responding when I Try to Turn Off the Built-In Bluetooth Adapter - Any Ideas?</u></a></li>
<li><a href="https://driver-error.techidaily.com/unified-windows-drivers-for-pci-cards/"><u>Unified Windows Drivers for PCI Cards</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-scaling-success-the-tactics-for-increasing-youtube-audiences/"><u>In 2024, Scaling Success  The Tactics for Increasing YouTube Audiences</u></a></li>
<li><a href="https://driver-error.techidaily.com/eliminate-error-unifying-receiver-not-detected/"><u>Eliminate Error: Unifying Receiver Not Detected</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-mp4-video-tag-editor-roundup-best-options-for-windows-and-mac/"><u>Updated 2024 Approved MP4 Video Tag Editor Roundup Best Options for Windows and Mac</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-enhance-tv-broadcasts-with-seamless-video-loops-from-youtube/"><u>In 2024, Enhance TV Broadcasts with Seamless Video Loops From YouTube</u></a></li>
<li><a href="https://driver-error.techidaily.com/usb-headset-not-working-on-windows-10-solved/"><u>USB Headset Not Working on Windows 10 [Solved]</u></a></li>
<li><a href="https://driver-error.techidaily.com/end-bluetooth-disturbance-in-win10/"><u>End Bluetooth Disturbance in Win10</u></a></li>
<li><a href="https://driver-error.techidaily.com/recovering-bluetooth-links-device-manager-lack/"><u>Recovering: Bluetooth Links, Device Manager Lack</u></a></li>
<li><a href="https://driver-error.techidaily.com/win2k-fix-no-device-detected-issue-on-pc/"><u>Win2K: Fix No Device Detected Issue on PC</u></a></li>
<li><a href="https://driver-error.techidaily.com/driver-irql-not-less-or-equal-on-windows-11-fixed/"><u>Driver Irql Not Less Or Equal on Windows 11 [Fixed]</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-chromebooks-best-capture-tools-no-cost/"><u>[New] 2024 Approved  Chromebook's Best Capture Tools (No Cost)</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-how-to-start-a-successful-youtube-gaming-channel-for-2024/"><u>[New] How to Start a Successful YouTube Gaming Channel for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/overview-of-the-best-vivo-y02t-screen-mirroring-app-drfone-by-drfone-android/"><u>Overview of the Best Vivo Y02T Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-honor-100-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Honor 100? | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/correcting-unify-disconnect-issue-on-pcs/"><u>Correcting Unify Disconnect Issue on PCs</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-quick-and-simple-methods-for-controlling-audio-playback-speed/"><u>Updated In 2024, Quick and Simple Methods for Controlling Audio Playback Speed</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-qualcomm-atheros-wireless-network-adapter-driver-issue-for-windows-10/"><u>Fix Qualcomm Atheros Wireless Network Adapter Driver Issue for Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/solutions-for-usb-installer-issues-handling-access-is-blocked-notifications/"><u>Solutions for USB Installer Issues: Handling Access Is Blocked Notifications</u></a></li>
<li><a href="https://driver-error.techidaily.com/restoring-realtek-usb-controls-post-windows-change/"><u>Restoring Realtek USB Controls Post-Windows Change</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-convenient-tips-for-iphone-screen-recording-setup/"><u>In 2024, Convenient Tips for iPhone Screen Recording Setup</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-xs-apples-new-iphone-drfone-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone XS, Apples New iPhone | Dr.fone</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-best-online-stop-motion-creators-a-comprehensive-review-for-2024/"><u>New Best Online Stop Motion Creators A Comprehensive Review for 2024</u></a></li>
</ul></div>
