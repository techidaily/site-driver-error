---
title: Ethernet Woes in Win11 - Realtek Fix Found Here
date: 2024-07-15T06:51:04.419Z
updated: 2024-07-16T06:51:04.419Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Ethernet Woes in Win11 - Realtek Fix Found Here
excerpt: This Article Describes Ethernet Woes in Win11 - Realtek Fix Found Here
thumbnail: https://thmb.techidaily.com/2ade3a49b6280463f663d29a0a9aed4a110f8560d1f316c09a570158c78fc956.jpg
---

## Ethernet Woes in Win11 - Realtek Fix Found Here

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b91ef1806793.jpg)

 Users have reported that their Realtek PCIe Family Controller (Ethernet) randomly stopped working after they upgraded to Windows 10\. There are still no answers from Microsoft or Realtek as to why would this happen, and this situation happens randomly on different occasions, so there are a lot of solutions that could be of help.

 If this is the problem you are experiencing now, please follow the instructions below to get it fixed by yourself.

[**Option One: Reset TCP/IP**](https://natural-cycles.sjv.io/vmebmr)
[**Option Two: Change Settings in Network Adapter Properties**](https://aofit.pxf.io/mmjyxq)
[**Option Three: Reinstall Realtek Adapter Driver**](https://westkiss.pxf.io/daqnaq)
[**Option Four: Update the Realtek Driver**](https://newchic.sjv.io/jzg4zq)

---

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
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
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
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

![](https://images.drivereasy.com/wp-content/uploads/2023/03/Driver-Easy-download-needed-1200x900.jpg)

 3) Click the **Update** button next to the Realtek PCIe driver to automatically download the correct version of this driver, then you can manually install it (you can do this with the FREE version).

 Or click **Update All**  to automatically download and install the correct version of _all_   the drivers that are missing or out of date on your system (this requires the Pro version – you’ll be prompted to upgrade when you click Update All).

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
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
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-itel-p55-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On Itel P55? | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-searches-for-missing-driver/"><u>Windows Searches for Missing Driver</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/decoding-chroma-techniques-from-raw-footage-to-final-cut-for-2024/"><u>Decoding Chroma Techniques  From Raw Footage to Final Cut for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-guide-to-correct-a-gtx-ninety-five-code-43-error-on-windows-eleven/"><u>Step-by-Step Guide to Correct a GTX Ninety-Five 'Code 43 Error' On Windows Eleven</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-iphones-mass-storage-problem-update-your-usb-drivers/"><u>Fixing iPhone's Mass Storage Problem: Update Your USB Drivers</u></a></li>
<li><a href="https://driver-error.techidaily.com/check-for-any-conflicting-software-or-programs-running-in-the-background/"><u>Check for Any Conflicting Software or Programs Running in the Background</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-guide-fixing-your-wireless-keyboard-issues-in-windows/"><u>Troubleshooting Guide: Fixing Your Wireless Keyboard Issues in Windows</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-windows-11-irql-error/"><u>Resolved: Windows 11 Irql Error</u></a></li>
<li><a href="https://driver-error.techidaily.com/win11-hd-audio-smooth-operations/"><u>Win11 HD Audio: Smooth Operations</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-elevate-your-sound-10-best-music-video-directors/"><u>Updated In 2024, Elevate Your Sound 10 Best Music Video Directors</u></a></li>
<li><a href="https://driver-error.techidaily.com/this-device-cannot-start-code-10-error-solved/"><u>This Device Cannot Start Code 10 Error [Solved]</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-quick-tips-for-seamless-embedding-of-youtube-playlists-on-a-website/"><u>[Updated] Quick Tips for Seamless Embedding of YouTube Playlists on a Website</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-hd-audio-windows-quest/"><u>[Resolved] HD Audio Windows Quest</u></a></li>
<li><a href="https://driver-error.techidaily.com/fault-flagged-ideport0-control-mismatch/"><u>Fault Flagged: Ideport0 Control Mismatch</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-harmonized-technology-judgments-by-experts/"><u>In 2024, Harmonized Technology Judgments by Experts</u></a></li>
<li><a href="https://driver-error.techidaily.com/bringing-back-obscured-bluetooth-to-system-hub/"><u>Bringing Back: Obscured Bluetooth to System Hub</u></a></li>
<li><a href="https://driver-error.techidaily.com/reconnecting-usb-gadgets-in-windows-78-after-disconnection/"><u>Reconnecting USB Gadgets in Windows 7/8 After Disconnection</u></a></li>
<li><a href="https://driver-error.techidaily.com/unlocking-directx-9-startup-success-strategies/"><u>Unlocking DirectX 9 Startup Success Strategies</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-beginners-guide-to-video-editing-essential-software/"><u>New 2024 Approved Beginners Guide to Video Editing Essential Software</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/confundir-idiomas-50-frases-falsas-inglesa-espanola/"><u>Confundir Idiomas: 50 Frases Falsas Inglesa-Española</u></a></li>
<li><a href="https://driver-error.techidaily.com/restoring-windows-enter-button-operations/"><u>Restoring Windows Enter Button Operations</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-unveiling-the-best-practices-for-transmitting-media-in-discord/"><u>[New] In 2024, Unveiling the Best Practices for Transmitting Media in Discord</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/2024-approved-mastering-facebook-live-your-complete-guide-to-successful-streaming/"><u>2024 Approved Mastering Facebook Live Your Complete Guide to Successful Streaming</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-hcmom-drive-not-installed-issues-a-step-by-step-guide/"><u>Resolving 'Hcmom Drive Not Installed' Issues: A Step-by-Step Guide</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-partner-vids-for-rapid-channelnode-growth/"><u>[Updated] Partner Vids for Rapid Channelnode Growth</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-breaking-into-the-world-of-youtube-stellar-intros-in-imovie/"><u>[New] In 2024, Breaking Into the World of YouTube  Stellar Intros in iMovie</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-achieving-perfect-pitch-captures-in-rl-games-for-2024/"><u>[Updated] Achieving Perfect Pitch Captures in RL Games for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/easy-troubleshooting-tips-to-repair-qualcomm-atheros-bluetooth-driver-malfunctions-in-windows-10/"><u>Easy Troubleshooting Tips to Repair Qualcomm Atheros Bluetooth Driver Malfunctions in Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixed-incompatibility-between-premiere-pro-and-amdintel-drivers/"><u>Fixed Incompatibility Between Premiere Pro and AMD/Intel Drivers</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-text-messages-from-oneplus-ace-3-to-new-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Text Messages from OnePlus Ace 3 to New Phone | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/finalised-device-driver-successfully-installed-and-running/"><u>[FINALISED] Device Driver Successfully Installed and Running</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-notable-20-anime-series-theme-tracks/"><u>[Updated] Notable 20 Anime Series Theme Tracks</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-vivo-s18e-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Vivo S18e Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-incompatibility-issues-a-users-guide-to-validating-and-fixing-invalid-driver-installs/"><u>Overcoming Incompatibility Issues: A User's Guide to Validating and Fixing Invalid Driver Installs</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/everlasting-deactivation-tactics-against-youtubes-sneaky-snack/"><u>Everlasting Deactivation Tactics Against YouTube's Sneaky Snack</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-expand-your-horizons-with-a-bundle-of-youtube-videos/"><u>2024 Approved  Expand Your Horizons With A Bundle of YouTube Videos</u></a></li>
<li><a href="https://howto.techidaily.com/11-proven-solutions-to-fix-google-play-store-not-working-issue-on-tecno-spark-10-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Proven Solutions to Fix Google Play Store Not Working Issue on Tecno Spark 10 Pro | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/addressed-printer-no-start-error/"><u>Addressed Printer No Start Error</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-intelamd-driver-missing-from-premiere-pro/"><u>Solved: Intel/AMD Driver Missing From Premiere Pro</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-unbranded-video-merging-our-top-7-recommendations/"><u>New In 2024, Unbranded Video Merging Our Top 7 Recommendations</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-2024-approved-zoom-in-and-out-on-snapchat/"><u>Updated 2024 Approved Zoom In and Out on Snapchat</u></a></li>
<li><a href="https://driver-error.techidaily.com/exposing-ms-bda-through-graphical-display/"><u>Exposing MS BDA Through Graphical Display</u></a></li>
</ul></div>
