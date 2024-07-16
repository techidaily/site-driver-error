---
title: Windows Change Affects Realtek LAN Drivers Negatively
date: 2024-07-15T06:58:51.108Z
updated: 2024-07-16T06:58:51.108Z
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
<li><a href="https://driver-error.techidaily.com/clearing-up-elan-input-discrepanrancies-in-w11-os/"><u>Clearing Up Elan Input Discrepanrancies in W11 OS</u></a></li>
<li><a href="https://driver-error.techidaily.com/reviving-the-past-comprehensive-troubleshooting-for-vintage-usb-composite-units/"><u>Reviving the Past: Comprehensive Troubleshooting for Vintage USB Composite Units</u></a></li>
<li><a href="https://driver-error.techidaily.com/decoding-the-aged-usb-composite-apparatus-resolved-challenges-and-expert-advice/"><u>Decoding the Aged USB Composite Apparatus: Resolved Challenges and Expert Advice</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-recommended-best-applications-for-mirroring-your-oppo-reno-10-proplus-5g-screen-drfone-by-drfone-android/"><u>In 2024, Recommended Best Applications for Mirroring Your Oppo Reno 10 Pro+ 5G Screen | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/cheer-up-wacom-says-goodbye-to-connection-troubles/"><u>Cheer Up! Wacom Says Goodbye to Connection Troubles</u></a></li>
<li><a href="https://howto.techidaily.com/8-quick-fixes-unfortunately-snapchat-has-stopped-on-xiaomi-redmi-note-12-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Quick Fixes Unfortunately, Snapchat has Stopped on Xiaomi Redmi Note 12 5G | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/bluetooth-fixes-windows-problems-resolved/"><u>Bluetooth Fixes: Windows Problems Resolved</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-from-isolation-to-connection-discords-pathway/"><u>2024 Approved  From Isolation to Connection  Discord's Pathway</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-video-controller-driver-issue-in-windows-11-easily/"><u>Fix Video Controller Driver Issue in Windows 11. Easily</u></a></li>
<li><a href="https://driver-error.techidaily.com/inactive-keysight-on-asus-laptop/"><u>Inactive Keysight on Asus Laptop</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-restore-functionality-of-unresponsive-usb-wireless-keyboards-with-windows-os/"><u>How to Restore Functionality of Unresponsive USB Wireless Keyboards with Windows OS</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-battlefield-brilliance-unleashed-a-guide-to-top-7-total-war-triumphs/"><u>[Updated] Battlefield Brilliance Unleashed  A Guide to Top 7 Total War Triumphs</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-gtx-nvidia-950-code-43-issue-in-windows-10-a-comprehensive-guide/"><u>Resolving GTX Nvidia 950 'Code 43' Issue in Windows 10: A Comprehensive Guide</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-achieving-excellence-in-game-recording-techniques-windows-11-style/"><u>[Updated] Achieving Excellence in Game Recording Techniques, Windows 11 Style</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-solution-to-driver-problems-in-windows-11-8-or-7-get-your-devices-working-now/"><u>Step-by-Step Solution to Driver Problems in Windows 11, 8 or 7 – Get Your Devices Working Now</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-here-are-some-of-the-best-pokemon-discord-servers-to-join-on-realme-narzo-60-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some of the Best Pokemon Discord Servers to Join On Realme Narzo 60 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-effortlessly-blur-your-conference-backgrounds-on-teams/"><u>[Updated] In 2024, Effortlessly Blur Your Conference Backgrounds on Teams</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixed-devmgr-error-code-48/"><u>Fixed: DevMgr - Error Code #48</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-guide-to-fix-an-unresponsive-hp-wireless-keyboard/"><u>Step-by-Step Guide to Fix an Unresponsive HP Wireless Keyboard</u></a></li>
<li><a href="https://driver-error.techidaily.com/i-cant-locate-my-recently-updated-logitech-brio-webcam-heres-what-troubleshooting-steps-did-solved/"><u>I Can't Locate My Recently Updated Logitech Brio Webcam – Here’s What Troubleshooting Steps Did (Solved)</u></a></li>
<li><a href="https://driver-error.techidaily.com/ensuring-validity-of-service-setup-clause-in-inf/"><u>Ensuring Validity of Service Setup Clause in INF</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-the-complete-fix-for-a-missing-processor-coprocessor-in-windows-tenth/"><u>Resolved! The Complete Fix for a Missing Processor Coprocessor in Windows Tenth</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-users-heres-how-you-can-get-your-wi-fi-keyboard-back-in-action/"><u>Windows Users! Here's How You Can Get Your Wi-Fi Keyboard Back in Action</u></a></li>
<li><a href="https://driver-error.techidaily.com/correcting-the-setup-of-your-gadget-overcoming-code-1-hurdles/"><u>Correcting the Setup of Your Gadget - Overcoming Code 1 Hurdles</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713954125164-updated-2024-approved-how-to-become-a-youtuber/"><u>Updated 2024 Approved How to Become a Youtuber</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-videos-from-infinix-hot-30i-by-fonelab-android-recover-video/"><u>How to Rescue Lost Videos from Infinix Hot 30i</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-10-top-rated-open-source-video-editors-for-free/"><u>New In 2024, 10 Top-Rated Open-Source Video Editors for Free</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/iphone-14-pro-backup-password-never-set-but-still-asking-heres-the-fix-by-drfone-ios/"><u>iPhone 14 Pro Backup Password Never Set But Still Asking? Heres the Fix</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-tips-for-legacy-usb-composite-devices/"><u>Troubleshooting Tips for Legacy USB Composite Devices</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-final-cut-pro-voice-over-mastery-essential-techniques-for-success/"><u>New In 2024, Final Cut Pro Voice Over Mastery Essential Techniques for Success</u></a></li>
<li><a href="https://driver-error.techidaily.com/battling-windows-1110-disk-utilization-alerts/"><u>Battling Windows 11/10 Disk Utilization Alerts</u></a></li>
<li><a href="https://driver-error.techidaily.com/operating-system-keys-unresponsive/"><u>Operating System: Keys Unresponsive</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-reasons-why-pokemon-gps-does-not-work-on-vivo-v30-lite-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Reasons why Pokémon GPS does not Work On Vivo V30 Lite 5G? | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-the-issue-how-to-correctly-set-up-your-device-with-error-code-1/"><u>Fixing the Issue: How to Correctly Set Up Your Device with Error Code 1</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-errors-and-enhancing-performance-of-win1110s-sm-bus-controllers/"><u>Fixing Errors & Enhancing Performance of WIN11/10's SM Bus Controllers</u></a></li>
<li><a href="https://driver-error.techidaily.com/reviving-your-bluetooth-connection-solving-qualcomm-atheros-driver-glitches-in-windows-11/"><u>Reviving Your Bluetooth Connection: Solving Qualcomm Atheros Driver Glitches in Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-the-vanishing-act-of-a-touchpads-driver/"><u>Solving the Vanishing Act of a Touchpad's Driver</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-flawed-disc-detection-in-win-1011/"><u>Fixing Flawed Disc Detection in Win 10/11</u></a></li>
</ul></div>
