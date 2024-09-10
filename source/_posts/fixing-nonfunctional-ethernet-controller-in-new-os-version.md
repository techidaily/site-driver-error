---
title: Fixing Nonfunctional Ethernet Controller in New OS Version
date: 2024-09-09T03:10:02.675Z
updated: 2024-09-10T03:10:02.675Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Fixing Nonfunctional Ethernet Controller in New OS Version
excerpt: This Article Describes Fixing Nonfunctional Ethernet Controller in New OS Version
thumbnail: https://thmb.techidaily.com/4622c737506cba1a23868ce6098299cf82c4724d17bc893106f7883eb3c1b7e3.jpg
---

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115943/19272" target="_top" id="2115943">
  <img src="//a.impactradius-go.com/display-ad/19272-2115943" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115943/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fixing Nonfunctional Ethernet Controller in New OS Version

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b91ef1806793.jpg)

 Users have reported that their Realtek PCIe Family Controller (Ethernet) randomly stopped working after they upgraded to Windows 10\. There are still no answers from Microsoft or Realtek as to why would this happen, and this situation happens randomly on different occasions, so there are a lot of solutions that could be of help.

 If this is the problem you are experiencing now, please follow the instructions below to get it fixed by yourself.

[**Option One: Reset TCP/IP**](https://natural-cycles.sjv.io/vmebmr)
[**Option Two: Change Settings in Network Adapter Properties**](https://aofit.pxf.io/mmjyxq)
[**Option Three: Reinstall Realtek Adapter Driver**](https://westkiss.pxf.io/daqnaq)
[**Option Four: Update the Realtek Driver**](https://newchic.sjv.io/jzg4zq)

---

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115909/19272" target="_top" id="2115909">
  <img src="//a.impactradius-go.com/display-ad/19272-2115909" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115909/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115950/19272" target="_top" id="2115950">
  <img src="//a.impactradius-go.com/display-ad/19272-2115950" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115950/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Option Two:** **Change Settings in Network Adapter Properties**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand category**Network adapters** .
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135409/19272" target="_top" id="2135409">
  <img src="//a.impactradius-go.com/display-ad/19272-2135409" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135409/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
3) Then right-click Realtek PCIe GBE Family Controller option and choose **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de65b229a9.png)

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098704/14409" target="_top" id="2098704">
  <img src="//a.impactradius-go.com/display-ad/14409-2098704" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098704/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 4) Go to**Advanced** tab, then choose**Speed & Duplex** option on the left side of the pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de6ed4d026.png)

 5) On the**Value** bar, change the default Auto Negotiation to **100 Mbps Full Duplex**  or some other options accordingly. We chose**100 Mbps Full Duplex** here, but yours could be different.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deb007e7e1.png)

 6) Now on the left side of the pane, choose**Energy Efficient Ethernet** option, then change the Value to**Disabled** . After the changes, hit**OK** to save.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deab52d9e0.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123733/7443" target="_top" id="2123733">
  <img src="//a.impactradius-go.com/display-ad/7443-2123733" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123733/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135351/19272" target="_top" id="2135351">
  <img src="//a.impactradius-go.com/display-ad/19272-2135351" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135351/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135415/19272" target="_top" id="2135415">
  <img src="//a.impactradius-go.com/display-ad/19272-2135415" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135415/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Hit**OK** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)

 4) Go to the menu bar on the top and click the button for **Scan for hardware changes** .  
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee9a707c2.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130886/7443" target="_top" id="2130886">
  <img src="//a.impactradius-go.com/display-ad/7443-2130886" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130886/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2128844/7443" target="_top" id="2128844">
  <img src="//a.impactradius-go.com/display-ad/7443-2128844" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2128844/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-guide-to-filming-and-refining-videos-via-adobe-connect/"><u>[New] Guide to Filming & Refining Videos via Adobe Connect</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-instasaver-the-leading-videophoto-downloaders-round-up-for-2024/"><u>[New] InstaSaver  The Leading Video/Photo Downloaders Round-Up for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/quick-fix-help-nvidia-games-running-slow-on-my-pc/"><u>[Quick-Fix] Help! Nvidia Games Running Slow on My PC?</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-windows-10-100-disk-usage-in-task-manager/"><u>[SOLVED] Windows 10 100%% Disk Usage in Task Manager</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-smooth-video-playback-for-televisions-with-youtube/"><u>[Updated] Smooth Video Playback for Televisions with YouTube</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-when-should-you-share-your-insta-story-for-2024/"><u>[Updated] When Should You Share Your Insta Story for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/amd-rx-driver-fix-for-windows-11-10-8-and-7/"><u>AMD RX Driver Fix for Windows 11, 10, 8 and 7</u></a></li>
<li><a href="https://driver-error.techidaily.com/dispatched-hardware-dysfunction/"><u>Dispatched Hardware Dysfunction</u></a></li>
<li><a href="https://driver-error.techidaily.com/driverless-woes-in-windows-1187-heres-how-you-can-resolve-it-easily/"><u>Driverless Woes in Windows 11/8/7? Here's How You Can Resolve It Easily</u></a></li>
<li><a href="https://driver-error.techidaily.com/end-of-struggle-graphics-driver-deployed-correctly/"><u>End of Struggle: Graphics Driver Deployed Correctly</u></a></li>
<li><a href="https://driver-error.techidaily.com/guide-to-repairing-the-error-when-your-final-usb-peripheral-is-unseen-by-windows/"><u>Guide to Repairing the Error When Your Final USB Peripheral Is Unseen by Windows</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-many-attempts-to-unlock-iphone-8-plus-by-drfone-ios/"><u>How Many Attempts To Unlock iPhone 8 Plus</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-life360-shows-wrong-location-on-samsung-galaxy-a15-5g-drfone-by-drfone-virtual-android/"><u>How to Fix Life360 Shows Wrong Location On Samsung Galaxy A15 5G? | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-overcome-invalid-driver-installation-on-your-system/"><u>How to Overcome Invalid Driver Installation on Your System</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-revive-unify-linker-writes-for-pcs/"><u>How to Revive Unify Linker' Writes for PCs</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/improving-vimeo-playback-pace-for-2024/"><u>Improving Vimeo Playback Pace for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-find-my-friends-work-on-xiaomi-redmi-note-12-4g-drfone-by-drfone-virtual-android/"><u>In 2024, Does find my friends work on Xiaomi Redmi Note 12 4G | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-activation-lock-on-apple-iphone-6-plus-or-ipad-by-drfone-ios/"><u>In 2024, How to Bypass Activation Lock on Apple iPhone 6 Plus or iPad?</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/1715759908153-in-2024-how-to-record-audio-with-audacity-on-mac/"><u>In 2024, How to Record Audio with Audacity on Mac</u></a></li>
<li><a href="https://driver-error.techidaily.com/make-windows-11s-bluetech-respect-you-heres-how-to-fix-unresponsive-connection-step-by-step/"><u>Make Windows 11'S BlueTech Respect You: Here’s How To Fix Unresponsive Connection (Step-by-Step)</u></a></li>
<li><a href="https://driver-error.techidaily.com/mastering-movement-on-laggy-windows/"><u>Mastering Movement on Laggy Windows</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mastering-the-new-ios-16-a-step-by-step-guide-to-using-photo-cutout-on-your-iphone/"><u>Mastering the New iOS 16: A Step-by-Step Guide to Using Photo Cutout on Your iPhone</u></a></li>
<li><a href="https://driver-error.techidaily.com/maximize-your-savings-on-an-affordable-ibuypower-esports-pc-build-for-competitive-play/"><u>Maximize Your Savings on an Affordable iBUYPOWER Esports PC Build for Competitive Play</u></a></li>
<li><a href="https://driver-error.techidaily.com/navigating-safe-mode-in-windows-cufflinks-8-a-comprehensive-walkthrough-to-uninstall-graphic-drivers/"><u>Navigating Safe Mode in Windows Cufflinks 8: A Comprehensive Walkthrough to Uninstall Graphic Drivers</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcame-freezing-issue-fixed-asus-webcam-on-win11-pcs/"><u>Overcame Freezing Issue: Fixed ASUS Webcam on Win11 PCs</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-no-device-found-in-windows-7/"><u>Overcoming 'No Device Found' In WIndows 7</u></a></li>
<li><a href="https://driver-error.techidaily.com/prevent-recurring-amd-driver-failures/"><u>Prevent Recurring AMD Driver Failures</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-distorted-video-from-asus-usb20-in-win11-setup/"><u>Solved Distorted Video From ASUS USB2.0 in Win11 Setup</u></a></li>
<li><a href="https://driver-error.techidaily.com/triumph-over-win11-bsod-with-irql-fix/"><u>Triumph over Win11 BSOD with Irql Fix</u></a></li>
<li><a href="https://buynow-info.techidaily.com/twelve-south-compass-pro-review-cleverly-designed-for-maximum-stability/"><u>Twelve South Compass Pro Review: Cleverly Designed For Maximum Stability</u></a></li>
<li><a href="https://driver-error.techidaily.com/unveiling-microsofts-basic-display-adapter-bda-via-graphics/"><u>Unveiling Microsoft's Basic Display Adapter (BDA) via Graphics</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-11-and-the-notorious-gtx-error-code-43-tips-to-get-back-on-track/"><u>Windows 11 and the Notorious GTX Error Code #43 – Tips to Get Back on Track</u></a></li>
</ul></div>
