---
title: Post-Win11 Upgrade, Realtek Net Issue Addressed
date: 2024-08-31T10:50:51.293Z
updated: 2024-09-01T10:50:51.293Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Post-Win11 Upgrade, Realtek Net Issue Addressed
excerpt: This Article Describes Post-Win11 Upgrade, Realtek Net Issue Addressed
thumbnail: https://thmb.techidaily.com/6644f0a2d74892fa3a39d2d46d9f44395a7ca3377bb37001448c4704afb2e518.jpg
---

## Post-Win11 Upgrade, Realtek Net Issue Addressed

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
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de25ac8c94.jpg)

 2) Type in the following command:

netsh int ip reset c:\resetlog.txt

 Make sure that you have made no typo and hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de2ea5a2ef.png)

 This will help you reset your TCP/IP (Transmission Control Protocol/Internet Protocol). To make it easier to understand, TCP/IP is the language that your computer uses to communicate with the outside world. Reseting TCP/IP will help you revert your Internet settings to the stage where it still works.

---

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Option Two:** **Change Settings in Network Adapter Properties**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
3) Then right-click Realtek PCIe GBE Family Controller option and choose **Properties** .

<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-choreograph-comic-characters/"><u>[New] 2024 Approved  Choreograph Comic Characters</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-hardware-cant-communicate-due-to-boot-issue/"><u>[RESOLVED] Hardware Can't Communicate Due to Boot Issue</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-acpivenintanddev33a0-driver-issues/"><u>[Solved] ACPIVEN_INT&DEV_33A0 Driver Issues</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-windows-11-100-disk-usage-in-task-manager/"><u>[SOLVED] Windows 11 100%% Disk Usage in Task Manager</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-engaging-audiences-making-popular-youtube-shorts/"><u>[Updated] 2024 Approved  Engaging Audiences  Making Popular YouTube Shorts</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-best-toy-quadcopters-reviewed-kids-edition-for-2024/"><u>[Updated] Best Toy Quadcopters Reviewed (Kids Edition) for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-for-beginners-leveraging-facebook-data-with-ease/"><u>[Updated] In 2024, For Beginners  Leveraging Facebook Data with Ease</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-prime-8-transformative-lenses-for-virtual-conferencing/"><u>[Updated] Prime 8 Transformative Lenses for Virtual Conferencing</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-unlocking-youtubes-potential-with-personalized-plays/"><u>[Updated] Unlocking Youtube’s Potential with Personalized Plays</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-handpicked-selections-ringtones-directly-from-snap/"><u>2024 Approved  Handpicked Selections  Ringtones Directly From Snap</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-understanding-the-impact-activating-auto-hdr-feature-on-windows-11/"><u>2024 Approved  Understanding the Impact  Activating Auto HDR Feature on Windows 11</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-issues-with-youtube-shorts-thumbnails-for-2024/"><u>Common Issues with YouTube Shorts Thumbnails for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/driver-load-problem-solved-correcting-the-battleye-error-1450/"><u>Driver Load Problem Solved: Correcting the BattlEye (Error 1450)</u></a></li>
<li><a href="https://driver-error.techidaily.com/effortless-use-of-win11/"><u>Effortless Use of Win11</u></a></li>
<li><a href="https://driver-error.techidaily.com/expert-tips-to-overcome-the-failed-to-install-hcmondriver-problem/"><u>Expert Tips to Overcome the 'Failed to Install Hcmondriver' Problem</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-guide-retrieving-required-drivers-for-devices-not-recognized-in-win1087-solved/"><u>Fix Guide: Retrieving Required Drivers for Devices Not Recognized in Win10/8/7 [SOLVED]</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-pci-serial-port-driver-issues-on-windows/"><u>Fix PCI Serial Port Driver Issues on Windows</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-windows-10-for-swift-mousing-action/"><u>Fix Windows 10 for Swift Mousing Action</u></a></li>
<li><a href="https://youtube-help.techidaily.com/from-genres-to-gems-building-a-personalized-youtube-music-mix-onlinemobile-for-2024/"><u>From Genres to Gems  Building a Personalized YouTube Music Mix Online/Mobile for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/google-meetings-archive/"><u>Google Meetings Archive</u></a></li>
<li><a href="https://driver-error.techidaily.com/gtx-950-code-43-fixing-techniques-for-windows-11-users-expert-tips-and-tricks/"><u>GTX 950 'Code 43' Fixing Techniques for Windows 11 Users - Expert Tips & Tricks</u></a></li>
<li><a href="https://driver-error.techidaily.com/hdr-audio-hub-fixed-complaint-addressed/"><u>HDR Audio Hub: Fixed Complaint Addressed</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-on-itel-p55-5g-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location on Itel P55 5G | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-fix-pci-memory-controller-driver-issues/"><u>How to Fix PCI Memory Controller Driver Issues</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-fix-the-absent-coprocessor-driver-issue-in-windows-10-easy-guide/"><u>How to Fix the Absent Coprocessor Driver Issue in Windows 10 - Easy Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/hp-envy-20-pc-updates-unveiled-a-step-by-step-driver-download-and-installation-guide/"><u>HP Envy 20 PC Updates Unveiled: A Step-by-Step Driver Download & Installation Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/hp-pavilion-g3-not-detected-by-ubuntu-1804-issue-resolved/"><u>HP Pavilion G3 Not Detected by Ubuntu 18.04 (Issue Resolved)</u></a></li>
<li><a href="https://driver-error.techidaily.com/idt-software-compatibility-issue-correcting-the-detected-hardware-is-not-supported-message/"><u>IDT Software Compatibility Issue: Correcting the Detected Hardware Is Not Supported Message</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-make-the-most-of-your-iphone-15-plus-lock-screen-with-notifications-drfone-by-drfone-ios/"><u>In 2024, How to Make the Most of Your iPhone 15 Plus Lock Screen with Notifications? | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-animators-companion-expertly-reviewed-3d-modeling-software/"><u>In 2024, The Animator's Companion  Expertly Reviewed 3D Modeling Software</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-the-ultimate-guide-to-oneplus-nord-3-5g-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Ultimate Guide to OnePlus Nord 3 5G Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://driver-error.techidaily.com/kb-malfunction-detected-in-windows-10/"><u>Kb Malfunction Detected in Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/mastery-of-windows-solving-ndis-fast-and-easy/"><u>Mastery of Windows: Solving NDIS Fast & Easy</u></a></li>
<li><a href="https://driver-error.techidaily.com/navigating-issue-52-drivers-at-a-crossroads/"><u>Navigating Issue #52: Drivers at a Crossroads</u></a></li>
<li><a href="https://driver-error.techidaily.com/no-intel-devices-on-system-driver-issues-appear/"><u>No Intel Devices on System; Driver Issues Appear</u></a></li>
<li><a href="https://driver-error.techidaily.com/preventing-sm-bus-errors-in-windows-1011-devices/"><u>Preventing SM Bus Errors in Windows 10/11 Devices</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-the-service-inf-configuration-error/"><u>Resolving the Service INF Configuration Error</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/slash-and-save-how-to-edit-youtube-videos-quickly-for-2024/"><u>Slash and Save  How to Edit YouTube Videos Quickly for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/solve-windows-1011-unifying-receiver-woes/"><u>Solve Windows 10/11 Unifying Receiver Woes</u></a></li>
<li><a href="https://driver-error.techidaily.com/stop-bluetooth-auto-connect-on-windows-10/"><u>Stop Bluetooth Auto-Connect on Windows 10</u></a></li>
<li><a href="https://howto.techidaily.com/super-easy-ways-to-deal-with-samsung-galaxy-a24-unresponsive-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Super Easy Ways To Deal with Samsung Galaxy A24 Unresponsive Screen | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/tackling-vintage-usb-composite-unit-issues-solutions-for-a-smarter-connection/"><u>Tackling Vintage USB Composite Unit Issues - Solutions for a Smarter Connection</u></a></li>
<li><a href="https://buynow-help.techidaily.com/the-ultimate-review-unpacking-the-apple-iphone-ses-sensible-elegance-in-2020/"><u>The Ultimate Review: Unpacking the Apple iPhone SE's Sensible Elegance in 2020</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-cyberpunk-2077-error-2024-a-comprehensive-guide/"><u>Troubleshooting Cyberpunk 2077 Error 2024 - A Comprehensive Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-non-responsive-windows-enter-key/"><u>Troubleshooting Non-Responsive Windows Enter Key</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-usb-connection-failures-deal-with-access-denied/"><u>Troubleshooting USB Connection Failures – Deal With 'Access Denied'</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/unlocking-youtubes-hidden-view-tracking-method/"><u>Unlocking YouTube’s Hidden View Tracking Method</u></a></li>
<li><a href="https://driver-error.techidaily.com/unveiling-secrets-to-overcome-asus-driver-issues/"><u>Unveiling Secrets to Overcome ASUS Driver Issues</u></a></li>
<li><a href="https://driver-error.techidaily.com/win11-bluetooth-reviving-lenovo-connectivity-magic/"><u>Win11 Bluetooth: Reviving Lenovo Connectivity Magic</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-ndis-troubleshooting-done-in-a-flash/"><u>Windows NDIS Troubleshooting, Done in a Flash</u></a></li>
</ul></div>
