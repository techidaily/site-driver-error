---
title: Windows 10 Reinstalls Faulty Realtek Drivers Correctly
date: 2024-07-15T06:53:05.168Z
updated: 2024-07-16T06:53:05.168Z
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
  
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![how to open Command Prompt as an admin](https://images.drivereasy.com/wp-content/uploads/2023/10/win11-Command-Prompt-Run-as-administrator.jpg)

 When prompted with the following notification, hit**Yes** to continue.
<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
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
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
3) Then right-click Realtek PCIe GBE Family Controller option and choose **Properties** .

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de65b229a9.png)

 4) Go to**Advanced** tab, then choose**Speed & Duplex** option on the left side of the pane.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
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
<li><a href="https://driver-error.techidaily.com/troubleshooting-steps-when-windows-ignores-your-latest-usb-attachment/"><u>Troubleshooting Steps When Windows Ignores Your Latest USB Attachment</u></a></li>
<li><a href="https://driver-error.techidaily.com/swift-remediation-of-windows-drivers/"><u>Swift Remediation of Windows Drivers</u></a></li>
<li><a href="https://driver-error.techidaily.com/bluetooth-cant-turn-off-on-windows-11-solved/"><u>Bluetooth Can't Turn Off on Windows 11 [Solved]</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ters-launchpad-7-funny-video-frameworks-for-comedians-for-2024/"><u>Laughter's Launchpad  7 Funny Video Frameworks for Comedians for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-and-resolving-nvidias-gtx-950-code-43-issue-in-windows-10-operating-system/"><u>Troubleshooting and Resolving NVIDIA's GTX 950 'Code 43' Issue in Windows 10 Operating System</u></a></li>
<li><a href="https://android-unlock.techidaily.com/the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-samsung-galaxy-f15-5g-device-by-drfone-android/"><u>The Ultimate Guide How to Bypass Swipe Screen to Unlock on Samsung Galaxy F15 5G Device</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-top-rated-ai-driven-dialogue-creation-tools/"><u>Updated Top-Rated AI-Driven Dialogue Creation Tools</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-correct-the-access-denied-hurdle-in-your-usb-device-setup-process/"><u>How To Correct the 'Access Denied' Hurdle in Your USB Device Setup Process</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-errors-with-your-final-usb-gadget-when-windows-fails-to-detect/"><u>Fixing Errors with Your Final USB Gadget: When Windows Fails to Detect</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-digital-dispatches-uncovering-twitters-most-popular-vids/"><u>[New] 2024 Approved  Digital Dispatches  Uncovering Twitter's Most Popular Vids</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-efficient-video-editing-with-timestamps-and-on-screen-text/"><u>2024 Approved  Efficient Video Editing with Timestamps & On-Screen Text</u></a></li>
<li><a href="https://video-capture.techidaily.com/exclusive-review-top-10-budget-friendly-video-meetup-apps-for-companies-and-schools/"><u>Exclusive Review  Top 10 Budget-Friendly Video Meetup Apps for Companies & Schools</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-devhub-48-issue/"><u>Resolved: DevHub #48 Issue</u></a></li>
<li><a href="https://driver-error.techidaily.com/lost-the-sight-of-my-logitech-brio-webcam-in-windows-heres-what-i-did-to-find-it-again-post-update-step-by-step-fixed/"><u>Lost the Sight of My Logitech Brio Webcam in Windows? Here's What I Did to Find It Again Post-Update (Step by Step) [Fixed]</u></a></li>
<li><a href="https://driver-error.techidaily.com/patched-audio-delay-with-asus-webcam-and-windows-11-blend/"><u>Patched Audio Delay with ASUS Webcam & Windows 11 Blend</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-flip-order-3-easy-steps-to-rewind-youtube-listeners/"><u>[Updated] In 2024, Flip Order  3 Easy Steps to Rewind Youtube Listeners</u></a></li>
<li><a href="https://driver-error.techidaily.com/force-abandoned-for-a-flawless-graphics-setup/"><u>Force Abandoned for a Flawless Graphics Setup</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-life360-notify-when-you-log-out-on-nokia-130-music-drfone-by-drfone-virtual-android/"><u>In 2024, Does Life360 Notify When You Log Out On Nokia 130 Music? | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/diagnosed-storage-system-issue/"><u>Diagnosed Storage System Issue</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/navigating-employment-and-video-content-creation-for-2024/"><u>Navigating Employment and Video Content Creation for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/reestablishing-enter-input-on-windows-os/"><u>Reestablishing Enter Input on Windows OS</u></a></li>
<li><a href="https://driver-error.techidaily.com/hidef-device-resolved-audio-driver-issue/"><u>HiDef Device Resolved: Audio Driver Issue</u></a></li>
<li><a href="https://driver-error.techidaily.com/hp-wireless-keyboard-malfunction-heres-how-you-can-repair-it/"><u>HP Wireless Keyboard Malfunction? Here's How You Can Repair It</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-prevent-your-amd-radeon-wattman-from-crashing-settings-restored-guide/"><u>How to Prevent Your AMD Radeon Wattman From Crashing: Settings Restored Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/recovery-of-intel-me-operations/"><u>Recovery of Intel ME Operations</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-dissecting-mr-beasts-financial-health/"><u>[Updated] Dissecting Mr. Beast’s Financial Health</u></a></li>
<li><a href="https://driver-error.techidaily.com/the-ultimate-solution-to-the-missing-enhanced-processor-driver-problem-in-windows-10-explained/"><u>The Ultimate Solution to the Missing Enhanced Processor Driver Problem in Windows 10 Explained</u></a></li>
<li><a href="https://extra-tips.techidaily.com/understanding-your-potential-earnings-as-a-podcaster/"><u>Understanding Your Potential Earnings as a Podcaster</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-intel-me-errors/"><u>Resolving Intel ME Errors</u></a></li>
<li><a href="https://driver-error.techidaily.com/unblock-your-nonworking-laptop-keys-a-simple-guide-to-restore-functionality-in-no-time-tech-talker-359-chars/"><u>Unblock Your Nonworking Laptop Keys: A Simple Guide to Restore Functionality in No Time - Tech Talker 359 Chars</u></a></li>
<li><a href="https://driver-error.techidaily.com/cant-install-drivers-due-to-lack-of-intel-card/"><u>Can't Install Drivers Due to Lack of Intel Card</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-compatibility-issues-when-idt-software-cant-support-detected-hardware/"><u>Fixing Compatibility Issues: When IDT Software Can’t Support Detected Hardware</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-code-37-windows-cannot-initialize-the-device-driver-for-this-hardware/"><u>[Solved] Code 37: Windows Cannot Initialize the Device Driver for This Hardware</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-top-7-skype-hacker-to-hack-any-skype-account-on-your-meizu-21-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Skype Hacker to Hack Any Skype Account On your Meizu 21 Pro | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/revealing-ms-bda-through-visual-rendering-insight/"><u>Revealing MS BDA Through Visual Rendering Insight</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-errors-ensuring-proper-driver-validation-for-your-pcs-hardware/"><u>Fixing Errors: Ensuring Proper Driver Validation for Your PC's Hardware</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-windows-camera-recording-retention/"><u>Expert Tips for Windows Camera Recording Retention</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-optimize-your-content-mix-twt-to-insta-video-sharing-techniques/"><u>[Updated] Optimize Your Content Mix  Twt-to-Insta Video Sharing Techniques</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/snapsizesecrets-perfecting-photo-and-video-sizes-in-instagram-for-2024/"><u>SnapSizeSecrets  Perfecting Photo and Video Sizes in Instagram for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-struggles-with-devices-driver-search/"><u>Windows Struggles with Device's Driver Search</u></a></li>
<li><a href="https://driver-error.techidaily.com/dealing-with-old-school-usb-composite-devices-solutions-and-tips-for-seamless-connectivity/"><u>Dealing with Old-School USB Composite Devices: Solutions and Tips for Seamless Connectivity</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-installation-errors-why-your-device-driver-might-be-invalid/"><u>Solving Installation Errors: Why Your Device Driver Might Be Invalid</u></a></li>
<li><a href="https://driver-error.techidaily.com/seamless-integration-of-updated-drivers-in-hp-envy-20-pcs-a-comprehensive-guide/"><u>Seamless Integration of Updated Drivers in HP Envy 20 PCs – A Comprehensive Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/unable-to-load-devices-wudfrd-driver-event-id-219/"><u>Unable to Load Device's WudfRd Driver (Event ID: 219)</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/-to-livecasting-google-meet-on-youtube/"><u>Guide to Livecasting Google Meet on YouTube</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-straightstreamerw11-ultra-simple-pc-screenshot-software/"><u>In 2024, StraightStreamerW11  Ultra-Simple PC Screenshot Software</u></a></li>
<li><a href="https://driver-error.techidaily.com/solve-detected-hardware-lacking-support-for-your-idt-software-system/"><u>Solve Detected Hardware Lacking Support for Your IDT Software System</u></a></li>
<li><a href="https://driver-error.techidaily.com/ultimate-tutorial-download-and-update-essential-software-for-your-hp-envy-20-system/"><u>Ultimate Tutorial: Download & Update Essential Software for Your HP ENVY 20 System</u></a></li>
<li><a href="https://driver-error.techidaily.com/comprehensive-pci-card-installers-win-10-8-7/"><u>Comprehensive PCI Card Installers (Win 10, 8, 7)</u></a></li>
<li><a href="https://driver-error.techidaily.com/comprehensive-fixes-what-to-do-when-windows-10-doesnt-recognize-the-coprocessor-driver/"><u>Comprehensive Fixes: What to Do When Windows 10 Doesn't Recognize the Coprocessor Driver</u></a></li>
</ul></div>
