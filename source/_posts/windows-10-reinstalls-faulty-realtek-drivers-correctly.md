---
title: Windows 10 Reinstalls Faulty Realtek Drivers Correctly
date: 2024-09-04T12:43:56.714Z
updated: 2024-09-05T12:43:56.714Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Windows 10 Reinstalls Faulty Realtek Drivers Correctly
excerpt: This Article Describes Windows 10 Reinstalls Faulty Realtek Drivers Correctly
thumbnail: https://thmb.techidaily.com/2579e58fb859f12bcf75d41bfcd2bb7289ef81a099867df0bbc5e1bf070a408f.jpg
---

## Windows 10 Reinstalls Faulty Realtek Drivers Correctly

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

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2031472/7443" target="_top" id="2031472">
  <img src="//a.impactradius-go.com/display-ad/7443-2031472" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2031472/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Hit**OK** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1186802/12108" target="_top" id="1186802">
  <img src="//a.impactradius-go.com/display-ad/12108-1186802" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1186802/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 4) Go to the menu bar on the top and click the button for **Scan for hardware changes** .  
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee9a707c2.png)

<!-- affiliate ads begin -->
<span id="1993654">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993654.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993654">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993654.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993654%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993654/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 5) Windows will help you automatically install the correct driver that it can find. But there is no guarantee that the new driver is going to work since Windows has provided the not working one originally.

 If you clearly remember that your Ethernet stops working after you update to a certain version of the driver, it is suggested that you roll it back to the stage where it was working well.

---

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1175223/12108" target="_top" id="1175223">
  <img src="//a.impactradius-go.com/display-ad/12108-1175223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1175223/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Option Four: Update the Realtek Driver**

 The steps above may help you resolve the issue, but if they don’t, you can try to update the Realtek driver. If you don’t have time, patience, or computer skills to update the driver manually,  you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/) .**

**IMPORTANT:**  If you can’t have access to the internet due to the network driver issues, you can use **[Driver Easy Offline Scan Feature](https://tools.techidaily.com/drivereasy/download/)**  to download and install a new network driver.

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version, it takes just 2 clicks (and you get full support and a 30-day money-back guarantee):

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2023/03/Driver-Easy-download-needed-1200x900.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934188/19272" target="_top" id="1934188">
  <img src="//a.impactradius-go.com/display-ad/19272-1934188" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934188/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) Click the **Update** button next to the Realtek PCIe driver to automatically download the correct version of this driver, then you can manually install it (you can do this with the FREE version).

 Or click **Update All**  to automatically download and install the correct version of _all_   the drivers that are missing or out of date on your system (this requires the Pro version – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2020/11/update-network-adapter-driver.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902294/19272" target="_top" id="1902294">
  <img src="//a.impactradius-go.com/display-ad/19272-1902294" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902294/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-tips.techidaily.com/0-top-rated-digital-video-cutting-tools-for-2024/"><u>[New] 10 Top-Rated Digital Video Cutting Tools for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-the-ultimate-guide-to-stunning-ig-video-creation/"><u>[New] In 2024, The Ultimate Guide to Stunning IG Video Creation</u></a></li>
<li><a href="https://youtube-web.techidaily.com/n-2024-where-custom-visuals-for-youtube-live-and-breathe/"><u>[New] In 2024, Where Custom Visuals for YouTube Live and Breathe</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-true-color-equalizer/"><u>[New] True Color Equalizer</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-essential-skillset-how-to-execute-screen-recording-on-mac/"><u>[Updated] Essential Skillset  How to Execute Screen Recording on Mac</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-snapspectacular-high-quality-windowsmac-screenshots/"><u>[Updated] In 2024, SnapSpectacular  High-Quality Windows/Mac Screenshots</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-nikon-1-j5-4k-camera-review/"><u>2024 Approved  Nikon 1 J5 4K Camera Review</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-start-saving-youtube-videos-as-screen-captures-today-completely-free/"><u>2024 Approved  Start Saving YouTube Videos as Screen Captures Today - Completely Free</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-unraveling-the-benefits-of-rapid-youtube-subscription/"><u>2024 Approved  Unraveling the Benefits of Rapid YouTube Subscription</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-methods-to-mirror-poco-m6-pro-5g-to-roku-drfone-by-drfone-android/"><u>3 Methods to Mirror Poco M6 Pro 5G to Roku | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721098332496-bluetooth-unresponsive-windows-10-a-step-by-step-guide/"><u>Bluetooth Unresponsive – Windows 10: A Step by Step Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/boost-your-pc-with-new-razer-deadriver-on-windows-10/"><u>Boost Your PC with New Razer DeaDriver on Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/correcting-unify-disconnect-issue-on-pcs/"><u>Correcting Unify Disconnect Issue on PCs</u></a></li>
<li><a href="https://tech-haven.techidaily.com/deciphering-ai-jargon-how-gpt-4-gpt-4-turbo-and-gpt-4o-stand-out-from-each-other/"><u>Deciphering AI Jargon: How GPT-4, GPT-4 Turbo, and GPT-4o Stand Out From Each Other</u></a></li>
<li><a href="https://driver-error.techidaily.com/device-compatibility-flaws-wudfrd-loading-issue-id-219/"><u>Device Compatibility Flaws, WudfRd Loading Issue ID: 219</u></a></li>
<li><a href="https://driver-error.techidaily.com/easy-instructions-how-to-install-driver-updates-for-the-hp-envy-20-laptop/"><u>Easy Instructions: How to Install Driver Updates for the HP Envy 20 Laptop</u></a></li>
<li><a href="https://driver-error.techidaily.com/easy-steps-to-update-or-install-drivers-on-windows-computers-windows-7-8-and-10-covered/"><u>Easy Steps to Update or Install Drivers on Windows Computers - Windows 7, 8 & 10 Covered</u></a></li>
<li><a href="https://driver-error.techidaily.com/eliminate-error-unifying-receiver-not-detected/"><u>Eliminate Error: Unifying Receiver Not Detected</u></a></li>
<li><a href="https://driver-error.techidaily.com/end-bluetooth-disturbance-in-win10/"><u>End Bluetooth Disturbance in Win10</u></a></li>
<li><a href="https://driver-error.techidaily.com/enhance-dell-pointer-efficacy-win7/"><u>Enhance Dell Pointer Efficacy (Win7)</u></a></li>
<li><a href="https://driver-error.techidaily.com/expert-tips-for-diagnosing-and-repairing-the-dll-rpc-server-process-failure-on-windows-vista-and-7/"><u>Expert Tips for Diagnosing and Repairing the 'DLL RPC Server Process' Failure on Windows Vista & 7</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-qualcomm-atheros-wireless-network-adapter-driver-issue-for-windows-10/"><u>Fix Qualcomm Atheros Wireless Network Adapter Driver Issue for Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721097052069-fix-your-gpu-problem-for-better-gameplay-solution-inside/"><u>Fix Your GPU Problem for Better Gameplay - Solution Inside!</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-the-unexpected-reset-of-your-radeon-wattman-stable-performance-now-achievable/"><u>Fixing the Unexpected Reset of Your Radeon Wattman - Stable Performance Now Achievable!</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-the-windows-7-blue-screen-error-code-0x0000007e/"><u>Fixing the Windows 7 'Blue Screen' Error Code 0X0000007E</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/forgot-iphone-passcode-again-unlock-iphone-se-2020-without-passcode-now-drfone-by-drfone-ios/"><u>Forgot iPhone Passcode Again? Unlock iPhone SE (2020) Without Passcode Now | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/guide-to-efficiently-downloading-and-installing-new-drivers-for-your-hp-envy-20-computer/"><u>Guide to Efficiently Downloading and Installing New Drivers for Your HP ENVY 20 Computer</u></a></li>
<li><a href="https://driver-error.techidaily.com/hdr-sound-ready-error-cleared-on-bus/"><u>HDR Sound Ready: Error Cleared on Bus</u></a></li>
<li><a href="https://driver-error.techidaily.com/help-latest-camera-not-detected-on-updated-laptop-here-are-quick-fixed-tips-for-you-answered/"><u>Help! Latest Camera Not Detected on Updated Laptop, Here Are Quick Fixed Tips for You (Answered)</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-fix-headset-no-sound-on-win10-system/"><u>How To Fix Headset No Sound on WIN10 System</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-fix-iphones-external-storage-connectivity-via-usb-an-ultimate-guide/"><u>How to Fix iPhone's External Storage Connectivity via USB: An Ultimate Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-solve-wireless-keyboard-problems-with-your-windows-computer-easily/"><u>How to Solve Wireless Keyboard Problems with Your Windows Computer Easily</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-stop-self-removal-of-nvidia-drivers/"><u>How To Stop Self-Removal of Nvidia Drivers</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fixing-foneazy-mockgo-not-working-on-xiaomi-civi-3-disney-100th-anniversary-edition-drfone-by-drfone-virtual-android/"><u>In 2024, Fixing Foneazy MockGo Not Working On Xiaomi Civi 3 Disney 100th Anniversary Edition | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-ultimate-guides-to-3d-type-exploration/"><u>In 2024, Ultimate Guides to 3D Type Exploration</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/instatilecraft-create-impressive-androidplusios-vids-for-2024/"><u>InstaTilecraft  Create Impressive Android+iOS Vids for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/mastering-touchpad-fixes-for-windows-users-with-elan/"><u>Mastering Touchpad Fixes for Windows Users with Elan</u></a></li>
<li><a href="https://youtube-web.techidaily.com/-videos-in-the-spotlight-who-wins-youtube-shorts-or-tiktok-in-2024/"><u>Micro-Videos in the Spotlight  Who Wins, YouTube Shorts or TikTok, In 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-make-a-heartfelt-video-montage-with-pictures-and-songs/"><u>New Make a Heartfelt Video Montage with Pictures and Songs</u></a></li>
<li><a href="https://driver-error.techidaily.com/newly-installed-compatible-and-reliable-nvidia-drivers/"><u>Newly Installed: Compatible and Reliable Nvidia Drivers</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/rank-8-real-world-video-promoters-for-success-for-2024/"><u>Rank 8 Real-World Video Promoters for Success for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/remedied-video-ram-access-interruptions/"><u>Remedied Video RAM Access Interruptions</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-crash-and-restore-the-default-radeon-wattman-configuration-fixed/"><u>Resolving 'Crash & Restore': The Default Radeon Wattman Configuration Fixed</u></a></li>
<li><a href="https://driver-error.techidaily.com/restoring-realtek-usb-controls-post-windows-change/"><u>Restoring Realtek USB Controls Post-Windows Change</u></a></li>
<li><a href="https://driver-error.techidaily.com/solutions-for-usb-installer-issues-handling-access-is-blocked-notifications/"><u>Solutions for USB Installer Issues: Handling Access Is Blocked Notifications</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-repair-for-nonfunctional-wireless-keyboards-in-windows-environments/"><u>Step-by-Step Repair for Nonfunctional Wireless Keyboards in Windows Environments</u></a></li>
<li><a href="https://driver-error.techidaily.com/swift-mousing-overcoming-system-stutters/"><u>Swift Mousing: Overcoming System Stutters</u></a></li>
<li><a href="https://driver-error.techidaily.com/trouble-with-your-logitech-brio-webcam-post-windows-creators-upgrade-heres-what-i-did-to-find-a-solution-solved/"><u>Trouble with Your Logitech Brio Webcam? Post Windows Creators Upgrade – Here's What I Did to Find a Solution (Solved)</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-guide-resolving-issues-with-unrecognized-final-usb-device-on-windows/"><u>Troubleshooting Guide: Resolving Issues with Unrecognized Final USB Device on Windows</u></a></li>
<li><a href="https://article-posts.techidaily.com/uncover-the-past-your-complete-guide-to-digitizing-and-preserving-old-photographs-for-2024/"><u>Uncover the Past  Your Complete Guide to Digitizing & Preserving Old Photographs for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/unified-windows-drivers-for-pci-cards/"><u>Unified Windows Drivers for PCI Cards</u></a></li>
<li><a href="https://driver-error.techidaily.com/unlocking-potential-lenovo-bt-driver-for-win10/"><u>Unlocking Potential: Lenovo BT Driver for Win10</u></a></li>
<li><a href="https://driver-error.techidaily.com/unlocking-right-click-on-windows-11-touchpad-done/"><u>Unlocking Right-Click on Windows 11 Touchpad [Done]</u></a></li>
<li><a href="https://driver-error.techidaily.com/usb-headset-not-working-on-windows-10-solved/"><u>USB Headset Not Working on Windows 10 [Solved]</u></a></li>
<li><a href="https://driver-error.techidaily.com/weve-found-a-quick-resolution-for-your-gpu-related-gaming-woes/"><u>We've Found a Quick Resolution for Your GPU-Related Gaming Woes</u></a></li>
<li><a href="https://driver-error.techidaily.com/win11-reliable-multitasking-experience/"><u>Win11: Reliable Multitasking Experience</u></a></li>
<li><a href="https://driver-error.techidaily.com/win2k-fix-no-device-detected-issue-on-pc/"><u>Win2K: Fix No Device Detected Issue on PC</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-11-error-code-eliminated-irql/"><u>Windows 11 Error Code Eliminated: IRQL</u></a></li>
</ul></div>
