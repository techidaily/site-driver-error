---
title: Repairing Realtek Driver Post-Windows 10 Switch
date: 2024-08-22T14:12:11.042Z
updated: 2024-08-23T14:12:11.042Z
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
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

<!-- affiliate ads begin -->
<span id="1793213">
					<video width="1080" height="1620" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:1080px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Hit**OK** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)

 4) Go to the menu bar on the top and click the button for **Scan for hardware changes** .  
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee9a707c2.png)

 5) Windows will help you automatically install the correct driver that it can find. But there is no guarantee that the new driver is going to work since Windows has provided the not working one originally.

 If you clearly remember that your Ethernet stops working after you update to a certain version of the driver, it is suggested that you roll it back to the stage where it was working well.

---

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) Click the **Update** button next to the Realtek PCIe driver to automatically download the correct version of this driver, then you can manually install it (you can do this with the FREE version).

 Or click **Update All**  to automatically download and install the correct version of _all_   the drivers that are missing or out of date on your system (this requires the Pro version – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2020/11/update-network-adapter-driver.jpg)

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
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
<li><a href="https://youtube-web.techidaily.com/024-approved-pictorial-narration-framework/"><u>[New] 2024 Approved  Pictorial Narration Framework</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-from-footage-to-followers-uploading-on-twitter/"><u>[New] From Footage to Followers  Uploading on Twitter</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-the-mystic-art-of-invisible-storytelling-on-snapchat/"><u>[New] The Mystic Art of Invisible Storytelling on Snapchat</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-mastering-the-art-of-moving-twitter-videos-into-whatsapp/"><u>[Updated] 2024 Approved  Mastering the Art of Moving Twitter Videos Into WhatsApp</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-captivating-your-network-streamlining-content-via-wirecast-to-facebook-for-2024/"><u>[Updated] Captivating Your Network  Streamlining Content via Wirecast to Facebook for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-discover-12-cutting-edge-flip-screen-cams-for-video-content/"><u>[Updated] Discover 12 Cutting-Edge Flip-Screen Cams for Video Content</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-snap-into-action-a-compelling-ig-gallery-of-inspiration-for-2024/"><u>[Updated] Snap Into Action! A Compelling IG Gallery of Inspiration for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-a-step-by-step-guide-to-collecting-excellent-visual-content/"><u>2024 Approved  A Step-by-Step Guide to Collecting Excellent Visual Content</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-mastering-the-art-of-digital-comedy-in-the-metaverse/"><u>2024 Approved  Mastering the Art of Digital Comedy in the Metaverse</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/a-working-guide-for-pachirisu-pokemon-go-map-on-tecno-pova-5-pro-drfone-by-drfone-virtual-android/"><u>A Working Guide For Pachirisu Pokemon Go Map On Tecno Pova 5 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-defenses-steps-to-turn-on-tpm-and-secure-boot-in-windows-11/"><u>Boosting Defenses: Steps to Turn On TPM and Secure Boot in Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/decoding-technology-high-performance-insights-from-toms-world/"><u>Decoding Technology: High-Performance Insights From Tom's World</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-install-epson-gt-s50-driver-for-windows-os-windows-7810/"><u>Download and Install Epson GT S50 Driver for Windows OS (Windows 7/8/10)</u></a></li>
<li><a href="https://driver-error.techidaily.com/easy-troubleshooting-guide-for-installed-device-drivers-windows-10-8-and-7-issue-solved/"><u>Easy Troubleshooting Guide for Installed Device Drivers: Windows 10, 8 and 7 (ISSUE SOLVED)</u></a></li>
<li><a href="https://driver-error.techidaily.com/easy-tutorial-for-enabling-safe-mode-and-updating-intel-gpu-software-on-win8-computers/"><u>Easy Tutorial for Enabling Safe Mode & Updating Intel GPU Software on Win8 Computers</u></a></li>
<li><a href="https://driver-error.techidaily.com/enhanced-sm-bus-functionality-in-win11/"><u>Enhanced Sm Bus Functionality in Win11</u></a></li>
<li><a href="https://driver-install.techidaily.com/essential-canon-software-drivers-for-new-win11-os/"><u>Essential Canon Software: Drivers for New Win11 OS</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-the-gtx-warton-950-code-43-problem-in-windows-11-comprehensive-guide/"><u>Fixing the GTX Warton 950 'Code 43' Problem in Windows 11 - Comprehensive Guide</u></a></li>
<li><a href="https://howto.techidaily.com/gmail-not-working-on-tecno-spark-20-proplus-7-common-problems-and-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Gmail Not Working on Tecno Spark 20 Pro+ 7 Common Problems & Fixes | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/graphical-access-restriction-in-win11-os/"><u>Graphical Access Restriction in Win11 OS</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-address-and-fix-driver-validation-problems-during-computer-updates/"><u>How to Address and Fix Driver Validation Problems During Computer Updates</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-re-earn-lost-achievement-points-on-steam/"><u>How to Re-Earn Lost Achievement Points on Steam</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-resolve-critical-process-died-snipped-0x0000007e-blue-screen-issue-on-windows-vista-and-7/"><u>How to Resolve Critical Process Died, Snipped 0X0000007E Blue Screen Issue on Windows Vista and 7</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-update-your-idt-software-for-new-hardware-support-and-avoid-common-issues/"><u>How to Update Your IDT Software for New Hardware Support and Avoid Common Issues</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-peak-popularity-on-reddit-10-most-upvoted-stories/"><u>In 2024, Peak Popularity on Reddit  10 Most Upvoted Stories</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-oppo-a59-5g-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On Oppo A59 5G? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/insta-video-backup-two-methods-for-seamless-access-for-2024/"><u>Insta Video Backup  Two Methods for Seamless Access for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/leveraging-colored-backdrops-for-seamless-edits-for-2024/"><u>Leveraging Colored Backdrops for Seamless Edits for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/loading-wudfrd-driver-encountered-problem-id-219/"><u>Loading WudfRd Driver Encountered Problem (ID: 219)</u></a></li>
<li><a href="https://driver-error.techidaily.com/mastered-disk-drive-troubleshooting/"><u>Mastered Disk Drive Troubleshooting</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcome-radiosyncrasies-with-ease-windows-style/"><u>Overcome Radiosyncrasies with Ease, Windows Style!</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-incompatibilities-fixing-unsupported-device-alerts-in-idt-software-systems/"><u>Overcoming Incompatibilities: Fixing Unsupported Device Alerts in IDT Software Systems</u></a></li>
<li><a href="https://driver-error.techidaily.com/pioneering-pcs-uncovered-in-storage-boxes-housekeepers-stumble-upon-original-q1-desktops-with-vintage-intel-processing-technology-and-minimal-ram/"><u>Pioneering PCs Uncovered in Storage Boxes: Housekeepers Stumble Upon Original Q1 Desktops with Vintage Intel Processing Technology and Minimal RAM</u></a></li>
<li><a href="https://driver-error.techidaily.com/repairing-missing-windows-enter-functionality/"><u>Repairing Missing Windows Enter Functionality</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-qualcomm-atheros-bluetooth-malfunction-on-windows-11-systems/"><u>Resolved: Qualcomm Atheros Bluetooth Malfunction on Windows 11 Systems</u></a></li>
<li><a href="https://driver-error.techidaily.com/revitalized-keyboard-works-flawlessly-post-fix-in-windows-11/"><u>Revitalized Keyboard, Works Flawlessly Post-Fix in Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-post-update-issues-with-realtek-lan-controls/"><u>Solving Post-Update Issues with Realtek LAN Controls</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-screen-flip-issues-on-asus-notebooks-a-guide/"><u>Solving Screen Flip Issues on Asus Notebooks - A Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-the-itbm-driver-unavailable-issue-with-simple-steps/"><u>Solving the 'ITBM Driver Unavailable' Issue with Simple Steps</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-windows-sm-bus-controller-hurdles/"><u>Solving Windows SM Bus Controller Hurdles</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-solution-to-install-essential-device-drivers-missing-on-windows-computers/"><u>Step-by-Step Solution to Install Essential Device Drivers Missing on Windows Computers</u></a></li>
<li><a href="https://driver-error.techidaily.com/the-evolution-and-functionality-of-compatible-usb-composite-gadgets-final-answer/"><u>The Evolution and Functionality of Compatible USB Composite Gadgets [FINAL ANSWER]</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-top-things-to-think-about-before-buying-your-next-video-grabbing-device/"><u>The Top Things to Think About Before Buying Your Next Video Grabbing Device</u></a></li>
<li><a href="https://driver-error.techidaily.com/the-ultimate-guide-stop-windows-11s-persistent-bluetooth/"><u>The Ultimate Guide: Stop Windows 11'S Persistent Bluetooth</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-and-fixing-mtp-issues-in-iphones-for-smooth-usb-connectivity/"><u>Troubleshooting and Fixing MTP Issues in iPhones for Smooth USB Connectivity</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-and-fixing-the-absent-cpu-accelerator-driver-on-your-windows-10-machine-solved/"><u>Troubleshooting and Fixing the Absent CPU Accelerator Driver on Your Windows 10 Machine [Solved]</u></a></li>
<li><a href="https://driver-error.techidaily.com/universal-drivers-package-pci-windows-compatible/"><u>Universal Drivers Package (PCI Windows Compatible)</u></a></li>
<li><a href="https://driver-error.techidaily.com/unlocking-lenovos-full-potential-in-windows-11/"><u>Unlocking Lenovo's Full Potential in Windows 11</u></a></li>
<li><a href="https://ai-voice.techidaily.com/updated-2024-approved-best-10-free-ai-voice-generators-to-use-in-daily-life/"><u>Updated 2024 Approved Best 10 Free AI Voice Generators to Use in Daily Life</u></a></li>
<li><a href="https://driver-error.techidaily.com/win11-mystery-of-missing-disk-drive-explained/"><u>Win11: Mystery of Missing Disk Drive Explained</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-1110-fix-pci-controller-loss/"><u>Windows 11/10: Fix PCI Controller Loss</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-wireless-mouse-disconnects-regularly/"><u>Windows Wireless Mouse Disconnects Regularly</u></a></li>
<li><a href="https://driver-error.techidaily.com/winning-the-battle-against-broken-qualcomm-atheros-bluetooth-drivers-on-windows-10/"><u>Winning the Battle Against Broken Qualcomm Atheros Bluetooth Drivers on Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/wireless-mastery-quick-solutions-for-windows-users/"><u>Wireless Mastery: Quick Solutions for Windows Users</u></a></li>
</ul></div>
