---
title: Ethernet Woes in Win11 - Realtek Fix Found Here
date: 2024-09-04T12:48:58.716Z
updated: 2024-09-05T12:48:58.716Z
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
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2030370/7443" target="_top" id="2030370">
  <img src="//a.impactradius-go.com/display-ad/7443-2030370" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2030370/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2024333/7443" target="_top" id="2024333">
  <img src="//a.impactradius-go.com/display-ad/7443-2024333" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2024333/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Hit**OK** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)

<!-- affiliate ads begin -->
<span id="1495277">
					<video width="1536" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1495277.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/17189-1495277">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1495277.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:960px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ffunwhole.sjv.io%2Fc%2F5597632%2F1495277%2F17189'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1495277/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 4) Go to the menu bar on the top and click the button for **Scan for hardware changes** .  
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee9a707c2.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902278/19272" target="_top" id="1902278">
  <img src="//a.impactradius-go.com/display-ad/19272-1902278" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902278/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111995/7443" target="_top" id="2111995">
  <img src="//a.impactradius-go.com/display-ad/7443-2111995" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111995/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) Click the **Update** button next to the Realtek PCIe driver to automatically download the correct version of this driver, then you can manually install it (you can do this with the FREE version).

 Or click **Update All**  to automatically download and install the correct version of _all_   the drivers that are missing or out of date on your system (this requires the Pro version – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2020/11/update-network-adapter-driver.jpg)

<!-- affiliate ads begin -->
<span id="701707">
					<video width="1536" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/701707.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/7443-701707">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/701707.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:960px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fappsumo.8odi.net%2Fc%2F5597632%2F701707%2F7443'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/701707/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://driver-error.techidaily.com/alert-intermittent-mouse-functionality-in-window-10/"><u>[Alert]: Intermittent Mouse Functionality in Window 10</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-instagram-video-limits-explained-in-detail/"><u>[New] Instagram Video Limits Explained in Detail</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-content-creation-in-todays-revenue-landscape/"><u>[Updated] 2024 Approved  Content Creation in Today’s Revenue Landscape</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-2024-approved-finding-your-custom-scored-youtube-tunes/"><u>[Updated] 2024 Approved  Finding Your Custom-Scored YouTube Tunes</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-avoiding-the-blank-thumbnail-scenario-in-shorts/"><u>[Updated] In 2024, Avoiding the Blank Thumbnail Scenario in Shorts</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-propel-promotions-with-select-words-and-phrases/"><u>2024 Approved  Propel Promotions with Select Words and Phrases</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-meizu-21-drfone-by-drfone-virtual-android/"><u>3 Ways to Fake GPS Without Root On Meizu 21 | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/7-fixes-for-unfortunately-phone-has-stopped-on-vivo-y02t-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Fixes for Unfortunately, Phone Has Stopped on Vivo Y02T | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/a-comprehensive-guide-to-troubleshooting-historical-usb-composite-device-quandaries/"><u>A Comprehensive Guide to Troubleshooting Historical USB Composite Device Quandaries</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721104805110-a-step-by-step-approach-to-correctly-orient-images-and-videos-in-asus-laptop-displays/"><u>A Step-by-Step Approach to Correctly Orient Images and Videos in ASUS Laptop Displays.</u></a></li>
<li><a href="https://driver-error.techidaily.com/address-erratic-dell-pointing-device-win7/"><u>Address Erratic Dell Pointing Device (Win7)</u></a></li>
<li><a href="https://driver-error.techidaily.com/android-wrapper-for-windows-samsung/"><u>Android Wrapper for Windows (Samsung)</u></a></li>
<li><a href="https://driver-error.techidaily.com/armored-fixed-asus-usb-webcam-link-with-win11-os/"><u>Armored Fixed ASUS USB-Webcam Link with Win11 OS</u></a></li>
<li><a href="https://driver-error.techidaily.com/asus-keyboard-brightness-not-working/"><u>ASUS Keyboard Brightness Not Working</u></a></li>
<li><a href="https://driver-error.techidaily.com/bluetooth-not-working-on-windows-11-solved/"><u>Bluetooth Not Working on Windows 11 [Solved]</u></a></li>
<li><a href="https://driver-error.techidaily.com/bluray-drive-not-visible-windows-11-fix-unveiled/"><u>BluRay Drive Not Visible: Windows 11 Fix Unveiled</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/boost-your-instagrams-accessibility-with-easy-caption-features-for-2024/"><u>Boost Your Instagram's Accessibility with Easy Caption Features for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/bridging-the-gap-unblocking-missing-bluetooth-links/"><u>Bridging the Gap: Unblocking Missing Bluetooth Links</u></a></li>
<li><a href="https://driver-error.techidaily.com/bring-back-functionality-fix-a-missing-touchpad-driver/"><u>Bring Back Functionality: Fix a Missing Touchpad Driver</u></a></li>
<li><a href="https://driver-error.techidaily.com/bring-back-lost-connection-revive-the-invisible-logitech-brio-webcam-in-new-windows-environment-answered/"><u>Bring Back Lost Connection: Revive the Invisible Logitech Brio Webcam in New Windows Environment [Answered]</u></a></li>
<li><a href="https://driver-error.techidaily.com/bt-compatibility-made-simple-for-lenovo-and-win11/"><u>BT Compatibility Made Simple for Lenovo & Win11</u></a></li>
<li><a href="https://driver-error.techidaily.com/closed-non-supported-intelligentamd-graphics-driver-issue-with-premiere-pro/"><u>Closed: Non-Supported Intelligent/AMD Graphics Driver Issue with Premiere Pro</u></a></li>
<li><a href="https://driver-error.techidaily.com/comprehensive-fix-for-hcmon-driver-error-during-setup-process/"><u>Comprehensive Fix for HCMON Driver Error During Setup Process</u></a></li>
<li><a href="https://driver-error.techidaily.com/comprehensive-guide-to-older-versions-of-usb-composite-devices/"><u>Comprehensive Guide to Older Versions of USB Composite Devices</u></a></li>
<li><a href="https://driver-error.techidaily.com/comprehensive-guide-to-repairing-driver-loading-glitch-in-battleye-service-error-145ebyte/"><u>Comprehensive Guide to Repairing Driver Loading Glitch in BattlEye Service Error 145Ebyte</u></a></li>
<li><a href="https://driver-error.techidaily.com/configuring-your-device-right-a-comprehensive-approach-to-solve-the-code-1-error-message/"><u>Configuring Your Device Right: A Comprehensive Approach to Solve the 'Code 1' Error Message</u></a></li>
<li><a href="https://driver-error.techidaily.com/correct-nic-instability-in-thinkcentre-series/"><u>Correct NIC Instability in ThinkCentre Series</u></a></li>
<li><a href="https://driver-error.techidaily.com/corrected-photo-output-glitch-for-asus-webcam-in-win11/"><u>Corrected Photo Output Glitch for ASUS Webcam in Win11</u></a></li>
<li><a href="https://driver-error.techidaily.com/correcting-unsupported-usb-errors-in-win-78-environment/"><u>Correcting Unsupported USB Errors in Win 7/8 Environment</u></a></li>
<li><a href="https://driver-error.techidaily.com/cracking-the-case-for-missing-signal-proc-on-pc/"><u>Cracking the Case for Missing Signal Proc on PC</u></a></li>
<li><a href="https://driver-error.techidaily.com/cracking-the-code-43-problem-effective-solutions-for-nvidia-gtx-950-on-windows-11-systems/"><u>Cracking the Code 43 Problem: Effective Solutions for NVIDIA GTX 950 on Windows 11 Systems</u></a></li>
<li><a href="https://driver-error.techidaily.com/cracking-the-code-on-usb-cannot-be-installed-access-is-denied-expert-solutions-for-windows-users/"><u>Cracking the Code on 'USB Cannot Be Installed, Access Is Denied': Expert Solutions for Windows Users</u></a></li>
<li><a href="https://driver-error.techidaily.com/dealing-with-unsupported-hardware-strategies-for-successful-software-integration/"><u>Dealing with 'Unsupported Hardware' – Strategies for Successful Software Integration</u></a></li>
<li><a href="https://driver-error.techidaily.com/dealing-with-iphones-and-mtp-driver-woes-master-these-troubleshooting-tips/"><u>Dealing With iPhones and MTP Driver Woes? Master These Troubleshooting Tips</u></a></li>
<li><a href="https://driver-error.techidaily.com/decoding-bda-graphics-through-visual-rendering/"><u>Decoding BDA Graphics Through Visual Rendering</u></a></li>
<li><a href="https://driver-error.techidaily.com/demystifying-elan-driver-conflicts-in-windows/"><u>Demystifying Elan Driver Conflicts in Windows</u></a></li>
<li><a href="https://driver-error.techidaily.com/device-back-in-service/"><u>Device Back in Service</u></a></li>
<li><a href="https://driver-error.techidaily.com/device-device-event-code-219-wudfrd-failure-load/"><u>Device Device Event Code 219: WudfRd Failure Load</u></a></li>
<li><a href="https://driver-error.techidaily.com/device-driver-loaded-on-win-os/"><u>Device Driver Loaded on Win OS</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721105119398-fix-pci-to-pci-bridge-driver-issue-easy-and-quick/"><u>Fix PCI-to-PCI Bridge Driver Issue Easy and Quick!</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721102972909-fix-radeon-software-and-driver-versions-do-not-match/"><u>Fix: ‘Radeon Software and Driver Versions Do Not Match’</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-red-glitch-in-windows-11-operating-system/"><u>Fixing the Red Glitch in Windows 11 Operating System</u></a></li>
<li><a href="https://solve-news.techidaily.com/free-video-streaming-tools-ranked-by-performance-and-features-for-easy-download/"><u>Free Video Streaming Tools Ranked by Performance and Features for Easy Download</u></a></li>
<li><a href="https://extra-information.techidaily.com/how-to-boost-youtube-video-spacing/"><u>How to Boost YouTube Video Spacing</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-vivo-y78t-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>How to Cast Vivo Y78t to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-tiktok-to-see-more-content-on-your-vivo-v29e-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location on TikTok to See More Content On your Vivo V29e | Dr.fone</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/in-2024-mastering-ai-powered-vocal-replication-two-techniques-for-authenticity/"><u>In 2024, Mastering AI-Powered Vocal Replication Two Techniques for Authenticity</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-ways-to-find-unlocking-codes-for-tecno-spark-go-2023-phones-by-drfone-android/"><u>In 2024, Ways To Find Unlocking Codes For Tecno Spark Go (2023) Phones</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721103877616-iphone-cant-connect-correct-your-phones-mtp-drivers-today/"><u>IPhone Can't Connect? Correct Your Phone's MTP Drivers Today</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721101503379-solved-no-valid-dx11-video-card-found-black-ops-error/"><u>Solved: No Valid DX11 Video Card Found Black Ops Ⅲ Error</u></a></li>
<li><a href="https://driver-download.techidaily.com/supercharge-your-gaming-experience-the-power-of-a-revamped-asus-rog-strix-geforce-rtx-2060-gpu-upgrade/"><u>Supercharge Your Gaming: Experience the Power of a Revamped Asus ROG Strix GeForce RTX 2060 GPU Upgrade</u></a></li>
<li><a href="https://tech-hub.techidaily.com/top-4-artificial-intelligence-story-creation-tools-to-enhance-your-writing/"><u>Top 4 Artificial Intelligence Story Creation Tools to Enhance Your Writing</u></a></li>
<li><a href="https://fox-that.techidaily.com/troubleshoot-your-phone-not-charging-when-held-down-with-these-8-fixes/"><u>Troubleshoot Your Phone Not Charging When Held Down with These 8 Fixes</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721102935039-troubleshooting-guide-installing-device-drivers-on-windows-1087-solution/"><u>Troubleshooting Guide: Installing Device Drivers on Windows 10/8/7 - SOLUTION</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721098927238-troubleshooting-qualcomm-atheros-bluetooth-driver-problems-in-windows-10-solved/"><u>Troubleshooting Qualcomm Atheros Bluetooth Driver Problems in Windows 10 - Solved!</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721101427175-win-printer-drivers-found-and-fixed/"><u>Win Printer Drivers - Found & Fixed!</u></a></li>
</ul></div>
