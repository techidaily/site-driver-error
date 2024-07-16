---
title: Solving Realtek LAN Driver Failure with Windows 11
date: 2024-07-15T06:58:14.095Z
updated: 2024-07-16T06:58:14.095Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Solving Realtek LAN Driver Failure with Windows 11
excerpt: This Article Describes Solving Realtek LAN Driver Failure with Windows 11
thumbnail: https://thmb.techidaily.com/7198dc888f65174fbf2046c2c24c70817b0458c73734644af430af59b81e9b9d.jpg
---

## Solving Realtek LAN Driver Failure with Windows 11

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
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de2ea5a2ef.png)

 This will help you reset your TCP/IP (Transmission Control Protocol/Internet Protocol). To make it easier to understand, TCP/IP is the language that your computer uses to communicate with the outside world. Reseting TCP/IP will help you revert your Internet settings to the stage where it still works.

---

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deb007e7e1.png)

 6) Now on the left side of the pane, choose**Energy Efficient Ethernet** option, then change the Value to**Disabled** . After the changes, hit**OK** to save.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deab52d9e0.png)

 7) Still, in the**Properties** window, this time, let’s go to**Power Management** tab. Un-tick the box for**Allow the computer to turn off this device to save power** . Then hit**OK** to save and exit.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://driver-error.techidaily.com/resolving-realtek-network-issues-in-windows-10/"><u>Resolving Realtek Network Issues in Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixed-asmedia-usb-host-controller-was-not-found-on-asus/"><u>Fixed: ASMedia USB Host Controller Was Not Found on Asus</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-update-or-downgrade-iphone-13-mini-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade iPhone 13 mini Without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-guide-resolving-failed-to-initialize-battleye-service-due-to-driver-loading-issues/"><u>Troubleshooting Guide: Resolving 'Failed to Initialize BattlEye Service' Due to Driver Loading Issues</u></a></li>
<li><a href="https://driver-error.techidaily.com/win11-disallows-graphics-card-use/"><u>Win11 Disallows Graphics Card Use</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-the-premier-collection-excellent-business-simulators-roundup-for-2024/"><u>[New] The Premier Collection  Excellent Business Simulators' Roundup for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-guide-resolving-windows-7s-0x0000007e-blue-screen-failure/"><u>Troubleshooting Guide: Resolving Windows 7'S 0X0000007E Blue Screen Failure</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-straighten-the-orientation-of-video-outputs-on-your-asus-computer-monitor/"><u>How To Straighten The Orientation Of Video Outputs On Your Asus Computer Monitor</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-guide-booting-into-safe-mode-and-removing-gpu-drivers-on-windows-8/"><u>Step-by-Step Guide: Booting Into Safe Mode & Removing GPU Drivers on Windows 8</u></a></li>
<li><a href="https://driver-error.techidaily.com/unmasking-ms-bda-via-visual-rendering/"><u>Unmasking MS BDA via Visual Rendering</u></a></li>
<li><a href="https://extra-tips.techidaily.com/exclusive-top-quintessential-4k-hd-gear-list/"><u>Exclusive Top Quintessential 4K HD Gear List</u></a></li>
<li><a href="https://extra-hints.techidaily.com/attention-magnet-article-initiator-for-2024/"><u>Attention Magnet  Article Initiator for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-mastering-aspect-ratios-in-final-cut-pro-a-beginners-guide/"><u>Updated Mastering Aspect Ratios in Final Cut Pro A Beginners Guide</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-spotify-location-after-moving-to-another-country-on-apple-iphone-12-pro-max-drfone-by-drfone-virtual-ios/"><u>How to Change Spotify Location After Moving to Another Country On Apple iPhone 12 Pro Max | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/the-definitive-guide-to-download-and-refresh-drivers-on-the-hp-envy-20-computer-series/"><u>The Definitive Guide to Download & Refresh Drivers on the HP ENVY 20 Computer Series</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-gear-up-with-smart-techniques-elevating-your-ps4-gameplay-capture-abilities/"><u>In 2024, Gear Up with Smart Techniques  Elevating Your PS4 Gameplay Capture Abilities</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-4-effective-methods-fake-gps-location-on-apple-iphone-xripad-drfone-by-drfone-virtual-ios/"><u>In 2024, 4 Effective Methods Fake GPS Location on Apple iPhone XR/iPad | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixed-endless-windows-11-bluetooth-activation/"><u>Fixed Endless Windows 11 Bluetooth Activation</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-skyrocketing-subscribers-on-youtube-step-by-step/"><u>2024 Approved  Skyrocketing Subscribers on YouTube Step-by-Step</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-did-your-iphone-6s-passcode-change-itself-unlock-it-now-by-drfone-ios/"><u>In 2024, Did Your iPhone 6s Passcode Change Itself? Unlock It Now</u></a></li>
<li><a href="https://driver-error.techidaily.com/upgraded-hat-support-on-the-latest-windows-os/"><u>Upgraded HAT Support on the Latest Windows OS</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-tips-to-restore-functionality-in-frozen-obs-screen/"><u>[Updated] Tips to Restore Functionality in Frozen OBS Screen</u></a></li>
<li><a href="https://driver-error.techidaily.com/win11-prevents-gpu-use-attempt/"><u>Win11 Prevents GPU Use Attempt</u></a></li>
<li><a href="https://driver-error.techidaily.com/reconnecting-seagate-hdd-to-windows-11-system/"><u>Reconnecting Seagate HDD to Windows 11 System</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-activation-lock-from-the-iphone-14-plus-without-previous-owner-by-drfone-ios/"><u>How to Remove Activation Lock From the iPhone 14 Plus Without Previous Owner?</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-audacity-and-you-a-step-by-step-approach-for-creating-exceptional-podcasts-for-2024/"><u>Updated Audacity and You A Step-by-Step Approach for Creating Exceptional Podcasts for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-a-curated-selection-top-8-streaming-audio-tools-to-enhance-your-broadcasts/"><u>Updated 2024 Approved A Curated Selection Top 8 Streaming Audio Tools to Enhance Your Broadcasts</u></a></li>
<li><a href="https://driver-error.techidaily.com/unraveling-the-mystery-of-driver-52-troubles/"><u>Unraveling the Mystery of Driver #52 Troubles</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-overcoming-connectivity-problems-with-your-hp-wireless-keyboard/"><u>Solved! Overcoming Connectivity Problems with Your HP Wireless Keyboard</u></a></li>
<li><a href="https://driver-error.techidaily.com/unraveling-the-mystery-of-directx-9-not-initializing/"><u>Unraveling the Mystery of DirectX 9 Not Initializing</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-mastering-whatsapp-key-tricks-and-invisible-functions/"><u>[Updated] Mastering WhatsApp  Key Tricks & Invisible Functions</u></a></li>
<li><a href="https://extra-support.techidaily.com/leaders-list-of-best-12-motion-recording-devices-location-aware-for-2024/"><u>Leader's List of Best 12 Motion Recording Devices  Location Aware for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-the-ultimate-trifecta-for-instagram-video-borders/"><u>[Updated] In 2024, The Ultimate Trifecta for Instagram Video Borders</u></a></li>
<li><a href="https://driver-error.techidaily.com/vga-controller-fix-interrupts-are-now-smooth/"><u>VGA Controller Fix: Interrupts Are Now Smooth</u></a></li>
<li><a href="https://driver-error.techidaily.com/comprehensive-fixes-to-address-the-bsod-stop-code-0x0000007e-on-windows/"><u>Comprehensive Fixes to Address the BSOD Stop Code 0X0000007E on Windows</u></a></li>
<li><a href="https://driver-error.techidaily.com/identifying-and-correcting-unrecognized-usb-errors-in-win-78/"><u>Identifying and Correcting Unrecognized USB Errors in Win 7/8</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-monetized-critique-videos-the-truth-unveiled/"><u>[Updated] Monetized Critique Videos  The Truth Unveiled</u></a></li>
</ul></div>
