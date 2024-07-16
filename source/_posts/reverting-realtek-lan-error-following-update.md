---
title: Reverting Realtek LAN Error Following Update
date: 2024-07-15T06:48:45.305Z
updated: 2024-07-16T06:48:45.305Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Reverting Realtek LAN Error Following Update
excerpt: This Article Describes Reverting Realtek LAN Error Following Update
thumbnail: https://thmb.techidaily.com/ad4388017aad038e4020bb83bed704ce1407b9c4acd2fda68cb5e54d580ca0be.jpg
---

## Reverting Realtek LAN Error Following Update

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
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
3) Then right-click Realtek PCIe GBE Family Controller option and choose **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de65b229a9.png)

 4) Go to**Advanced** tab, then choose**Speed & Duplex** option on the left side of the pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de6ed4d026.png)

 5) On the**Value** bar, change the default Auto Negotiation to **100 Mbps Full Duplex**  or some other options accordingly. We chose**100 Mbps Full Duplex** here, but yours could be different.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deb007e7e1.png)

 6) Now on the left side of the pane, choose**Energy Efficient Ethernet** option, then change the Value to**Disabled** . After the changes, hit**OK** to save.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

 Hit**OK** to continue.
<!-- affiliate ads begin -->

<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)

 4) Go to the menu bar on the top and click the button for **Scan for hardware changes** .  
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee9a707c2.png)

 5) Windows will help you automatically install the correct driver that it can find. But there is no guarantee that the new driver is going to work since Windows has provided the not working one originally.

 If you clearly remember that your Ethernet stops working after you update to a certain version of the driver, it is suggested that you roll it back to the stage where it was working well.

---

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://driver-error.techidaily.com/how-to-fix-qualcomm-atheros-bluetooth-issues-on-windows-10/"><u>How to Fix Qualcomm Atheros Bluetooth Issues on Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/addressing-non-recognized-usb-in-older-windows-systems/"><u>Addressing Non-Recognized USB in Older Windows Systems</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-bridging-social-gaps-efficiently-share-video-content-between-platforms/"><u>[Updated] In 2024, Bridging Social Gaps  Efficiently Share Video Content Between Platforms</u></a></li>
<li><a href="https://driver-error.techidaily.com/broadcoms-win-fix-restored-working-state-of-broadcom-wi-fi-adapter/"><u>Broadcom's Win Fix: Restored Working State of Broadcom Wi-Fi Adapter</u></a></li>
<li><a href="https://driver-error.techidaily.com/seamless-sound-in-the-windows-11-world/"><u>Seamless Sound in the Windows 11 World</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-not-recognizing-nvidia-gpus/"><u>Windows Not Recognizing Nvidia GPUs</u></a></li>
<li><a href="https://driver-error.techidaily.com/making-invisible-seagate-hard-disk-visible-on-win11/"><u>Making Invisible Seagate Hard Disk Visible on Win11</u></a></li>
<li><a href="https://driver-error.techidaily.com/a-step-by-step-approach-to-correctly-orient-images-and-videos-in-asus-laptop-displays/"><u>A Step-by-Step Approach to Correctly Orient Images and Videos in ASUS Laptop Displays</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-expert-insights-on-ps3-gameplay-documentation/"><u>[Updated] 2024 Approved  Expert Insights on PS3 Gameplay Documentation</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-mastering-podcast-playback-on-mac-with-top-apps/"><u>[New] Mastering Podcast Playback on Mac with Top Apps</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-in-2024-linux-on-a-chromebook-the-complete-installation-and-setup-guide/"><u>Updated In 2024, Linux on a Chromebook The Complete Installation and Setup Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-the-windows-11-error-missing-hardware-acceleration-coprocessor-driver/"><u>Resolving the Windows 11 Error: Missing Hardware Acceleration Coprocessor Driver</u></a></li>
<li><a href="https://driver-error.techidaily.com/graphics-card-oversight-by-windows/"><u>Graphics Card Oversight by Windows</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/starting-an-impactful-fb-community-giving-campaign-for-2024/"><u>Starting an Impactful FB Community Giving Campaign for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-vintage-vs-modern-ranking-radio-sound-effects/"><u>Updated In 2024, Vintage Vs. Modern Ranking Radio Sound Effects</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixed-arch-bluetooth-mouse-not-working-after-windows-11-creators-update/"><u>[FIXED] Arch Bluetooth Mouse Not Working After Windows 11 Creators Update</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-install-missing-device-drivers-on-windows-11-8-and-7-complete-guide-fixed/"><u>How To Install Missing Device Drivers on Windows 11, 8 & 7 - Complete Guide [FIXED]</u></a></li>
<li><a href="https://driver-error.techidaily.com/win11-meets-lenovo-bluetooth-driver-fix-explained/"><u>Win11 Meets Lenovo: Bluetooth Driver Fix Explained</u></a></li>
<li><a href="https://fix-guide.techidaily.com/strategies-for-apps-that-wont-download-from-play-store-on-realme-gt-5-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Strategies for Apps That Wont Download From Play Store On Realme GT 5 Pro | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-step-by-step-photo-addition-to-instagram/"><u>[New] Step-by-Step Photo Addition to Instagram</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-elite-uploader-mp4-files-directly-for-fb/"><u>[Updated] In 2024, Elite Uploader  MP4 Files Directly for FB</u></a></li>
<li><a href="https://driver-error.techidaily.com/ultimate-troubleshooting-initiating-safe-mode-and-disabling-graphics-card-drivers-in-windows-8/"><u>Ultimate Troubleshooting: Initiating Safe Mode & Disabling Graphics Card Drivers in Windows 8</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/2024-approved-the-art-of-slow-motion-how-to-make-jaw-dropping-videos-on-kapwing/"><u>2024 Approved The Art of Slow Motion How to Make Jaw-Dropping Videos on Kapwing</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-driver-hurdles-in-win11/"><u>Overcoming Driver Hurdles in Win11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-webcam-master-ultimate-live-recording-guide/"><u>[Updated] WebCam Master  Ultimate Live Recording Guide</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-mastering-top-10-crafting-winning-tiktok-marketing-campaigns-for-2024/"><u>[New] Mastering Top 10  Crafting Winning TikTok Marketing Campaigns for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/fault-alarm-ideport0-system-disturbance/"><u>Fault Alarm: Ideport0 System Disturbance</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unlocking-the-full-potential-of-iphones-hdr-capabilities/"><u>[Updated] Unlocking the Full Potential of iPhone's HDR Capabilities</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-unveiling-youtubes-new-era-post-vidcon-events/"><u>[New] Unveiling Youtube's New Era  Post-VidCon Events</u></a></li>
<li><a href="https://driver-error.techidaily.com/eradicating-stutter-mice-in-windows-10/"><u>Eradicating Stutter Mice in Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/bluetooth-driver-update-for-lenovo-on-windows-11/"><u>Bluetooth Driver Update for Lenovo on Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/unavailable-driver-error-bcm20702a0/"><u>Unavailable Driver Error - BCM20702A0</u></a></li>
<li><a href="https://driver-error.techidaily.com/optimize-your-gameplay-streamline-deadriver-in-win10/"><u>Optimize Your Gameplay: Streamline DeaDriver in Win10</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-perfecting-audio-rates-in-youtube-playback/"><u>[Updated] Perfecting Audio Rates in YouTube Playback</u></a></li>
<li><a href="https://driver-error.techidaily.com/diagnose-and-resolve-wireless-keyboard-issues-in-windows-computers-easily/"><u>Diagnose and Resolve Wireless Keyboard Issues in Windows Computers Easily</u></a></li>
<li><a href="https://driver-error.techidaily.com/hdr-audio-hub-no-more-glitches/"><u>HDR Audio Hub: No More Glitches</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-above-the-mainstage-significant-youtube-meetings-for-2024/"><u>[Updated] Above the Mainstage  Significant YouTube Meetings for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/taskmgr-full-disk-use-windows-10/"><u>TaskMgr: Full Disk Use - Windows 10</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/aufforderungen-in-einem-respektvollen-ton-deutsch/"><u>Aufforderungen in Einem Respektvollen Ton: Deutsch</u></a></li>
<li><a href="https://driver-error.techidaily.com/disk-management-solutions-for-win11-users/"><u>Disk Management Solutions for Win11 Users</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-podcast-renaming-made-easy-with-these-ai-tools/"><u>[New] Podcast Renaming Made Easy with These AI Tools</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-apple-iphone-15-plus-online-here-are-6-easy-ways-by-drfone-ios/"><u>How to Unlock Apple iPhone 15 Plus Online? Here are 6 Easy Ways</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-triller-vs-tiktok-similarities-and-differences-a-complete-guide/"><u>[Updated] 2024 Approved  Triller Vs. TikTok - Similarities & Differences - A Complete Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/bluetooth-never-turns-off-on-windows-11-fix/"><u>Bluetooth Never Turns Off on Windows 11 [Fix]</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-dolby-advanced-audio-unable-to-start-the-dolby-audio-driver-in-windows-11/"><u>Solved Dolby Advanced Audio: Unable to Start the Dolby Audio Driver in Windows 11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/2024-approved-where-are-my-youtube-comments-desktopiosandroid-strategies/"><u>2024 Approved  Where Are My YouTube Comments? Desktop/iOS/Android Strategies</u></a></li>
<li><a href="https://driver-error.techidaily.com/adjusting-non-loading-conditions-for-enex-on-win11/"><u>Adjusting Non-Loading Conditions for eNEX on Win11</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-windows-inactive-enter-key/"><u>Resolving Windows' Inactive Enter Key</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-ax201-unable-to-communicate-with-wi-fi-6/"><u>[SOLVED] AX201 Unable to Communicate with Wi-Fi 6</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-adjust-and-fix-sideways-video-display-errors-in-asus-systems/"><u>How to Adjust and Fix Sideways Video Display Errors in ASUS Systems</u></a></li>
<li><a href="https://driver-error.techidaily.com/reconnecting-bluetooth-disappeared-from-devices-hub/"><u>Reconnecting: Bluetooth Disappeared From Devices Hub</u></a></li>
<li><a href="https://driver-error.techidaily.com/nvidia-cards-unseen-by-windows-variants/"><u>Nvidia Cards Unseen by Windows Variants</u></a></li>
<li><a href="https://driver-error.techidaily.com/comprehensive-guide-correcting-issues-with-installing-hcmondriver-drivers-efficiently/"><u>Comprehensive Guide: Correcting Issues with Installing Hcmondriver Drivers Efficiently</u></a></li>
</ul></div>
