---
title: Restoring Functional Status of Realtek USB Networks
date: 2024-07-15T06:50:41.968Z
updated: 2024-07-16T06:50:41.968Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Restoring Functional Status of Realtek USB Networks
excerpt: This Article Describes Restoring Functional Status of Realtek USB Networks
thumbnail: https://thmb.techidaily.com/27d6b547bddc8e31d111fb6ac4a194fdf9932bb9effb0d2c901c0f3a526ef8b0.jpg
---

## Restoring Functional Status of Realtek USB Networks

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
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deb007e7e1.png)

 6) Now on the left side of the pane, choose**Energy Efficient Ethernet** option, then change the Value to**Disabled** . After the changes, hit**OK** to save.

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
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deab52d9e0.png)

 7) Still, in the**Properties** window, this time, let’s go to**Power Management** tab. Un-tick the box for**Allow the computer to turn off this device to save power** . Then hit**OK** to save and exit.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587decc3276b5.png)

---

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://driver-error.techidaily.com/cease-perpetual-bluetooth-signal-in-win10/"><u>Cease Perpetual Bluetooth Signal in Win10</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-iphone-flash-optimization-tips/"><u>In 2024, IPhone Flash Optimization Tips</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-filmoras-blueprint-for-stellar-youtube-trailers/"><u>In 2024, Filmora's Blueprint for Stellar YouTube Trailers</u></a></li>
<li><a href="https://driver-error.techidaily.com/driver-recovery-for-optimal-touchpad-usage/"><u>Driver Recovery for Optimal Touchpad Usage</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-5-ways-to-record-facetime-calls/"><u>[New] 5 Ways to Record FaceTime Calls</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-the-absence-of-coprocessor-drivers-in-windows-10-a-comprehensive-guide/"><u>Resolving the Absence of Coprocessor Drivers in Windows 10: A Comprehensive Guide</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-identify-missing-your-hardware-drivers-with-windows-device-manager-in-windows-11-by-drivereasy-guide/"><u>How to identify missing your hardware drivers with Windows Device Manager in Windows 11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-top-16-youtube-starting-points-to-enhance-view-count/"><u>[Updated] Top 16 YouTube Starting Points to Enhance View Count</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721102277438-wireless-harmony-windows-and-bluetooth-unite/"><u>Wireless Harmony: Windows & Bluetooth Unite!</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-audio-syncing-simplified-2023s-innovative-methods-for-perfectly-timed-video-content/"><u>2024 Approved Audio Syncing Simplified 2023S Innovative Methods for Perfectly Timed Video Content</u></a></li>
<li><a href="https://driver-error.techidaily.com/pinpointing-missing-signal-processor-on-win/"><u>Pinpointing Missing Signal Processor on Win</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/superior-fb-extra-tools-video-grabs-firefox-version-for-2024/"><u>Superior FB Extra Tools  Video Grabs, Firefox Version for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-maximizing-efficiency-video-capturing-in-adobe-presenter/"><u>[New] 2024 Approved  Maximizing Efficiency  Video Capturing in Adobe Presenter</u></a></li>
<li><a href="https://driver-error.techidaily.com/mastering-the-recovery-of-amds-radeon-wattman-overcoming-crash-and-default-restore-hurdles/"><u>Mastering the Recovery of AMD's Radeon WattMan: Overcoming Crash and Default Restore Hurdles</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-finding-fellowship-adding-friends-in-discord/"><u>[Updated] 2024 Approved  Finding Fellowship  Adding Friends in Discord</u></a></li>
<li><a href="https://driver-error.techidaily.com/breaking-barriers-decode-e52-for-smooth-drives/"><u>Breaking Barriers: Decode E52 for Smooth Drives</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-top-ranked-apps-for-video-conferencing-and-collaboration/"><u>In 2024, Top-Ranked Apps for Video Conferencing and Collaboration</u></a></li>
<li><a href="https://driver-error.techidaily.com/click-without-frustration-on-win10/"><u>Click Without Frustration on Win10</u></a></li>
<li><a href="https://youtube-help.techidaily.com/navigating-youtubes-creative-commons-framework-effectively-for-2024/"><u>Navigating YouTube's Creative Commons Framework Effectively for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-overcome-unrecognized-device-warnings-with-this-idt-software-package/"><u>How to Overcome Unrecognized Device Warnings with This IDT Software Package</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixed-ax201-not-linking-to-intel-wi-fi-6-networks/"><u>[FIXED] AX201 Not Linking to Intel Wi-Fi 6 Networks</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-optimal-method-for-integrating-gopro-footage-into-360-degree-films-for-2024/"><u>[Updated] Optimal Method for Integrating GoPro Footage Into 360-Degree Films for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/computer-trouble-keyboard-non-working/"><u>Computer Trouble: Keyboard Non-Working</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-restoring-iphone-x-identity-check-reviving-face-recognition/"><u>[New] Restoring iPhone X Identity Check  Reviving Face Recognition</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-guide-resolving-failed-to-install-hcmon-driver-issues/"><u>Step-by-Step Guide: Resolving 'Failed to Install HCMon Driver' Issues</u></a></li>
<li><a href="https://driver-error.techidaily.com/effortlessly-fix-bluetooth-radios-on-windows/"><u>Effortlessly Fix Bluetooth Radios on Windows</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-get-into-a-friends-live-showcase-effortlessly-for-2024/"><u>[New] Get Into a Friend's Live Showcase Effortlessly for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/seamless-visuals-on-screen-zooming-into-clarity/"><u>Seamless Visuals on Screen  Zooming Into Clarity</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-top-15-mac-and-pc-optimal-android-virtualization-tools/"><u>[New] Top 15 Mac & PC  Optimal Android Virtualization Tools</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-80211n-broadcom-wi-fi-adapter-fix-found/"><u>Windows 802.11N Broadcom Wi-Fi Adapter Fix Found</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-rtx-graphics-issues-in-gaming-heres-how-to-quickly-optimize/"><u>[Solved]: RTX Graphics Issues in Gaming – Here's How to Quickly Optimize</u></a></li>
<li><a href="https://driver-error.techidaily.com/error-corrected-in-service-installation-inf/"><u>Error Corrected in Service Installation INF</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-guide-eradicating-the-blue-screen-error-0x0000007e-in-windows-7/"><u>Step-by-Step Guide: Eradicating the Blue Screen Error 0X0000007E in Windows 7</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-bluetooth-hurdles-repairing-the-qualcomm-atheros-driver-for-optimal-performance-on-windows-10/"><u>Overcoming Bluetooth Hurdles: Repairing the Qualcomm Atheros Driver for Optimal Performance on Windows 10</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-the-pathway-to-immaculate-audio-integration-in-video-production-for-2024/"><u>Updated The Pathway to Immaculate Audio Integration in Video Production for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-complete-guide-for-apple-iphone-11-pro-max-lock-screen-drfone-by-drfone-ios/"><u>In 2024, Complete Guide For Apple iPhone 11 Pro Max Lock Screen | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-identify-missing-your-hardware-drivers-with-windows-device-manager-in-windows-10-and-7-by-drivereasy-guide/"><u>Use Device Manager to identify missing your hardware drivers with Windows Device Manager in Windows 10 & 7</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-exploring-platform-variations-youtube-vs-dailymention/"><u>In 2024, Exploring Platform Variations  YouTube Vs. DailyMention</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-exclusive-applications-for-global-collaboration-for-2024/"><u>[New] Exclusive Applications for Global Collaboration for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721102722057-rtp-unable-to-run-nvidia-graphics-games-our-expertise-can-solve-it/"><u>RTP: Unable to Run Nvidia Graphics Games? Our Expertise Can Solve It!</u></a></li>
<li><a href="https://driver-error.techidaily.com/eradicated-error-in-system-hub-45/"><u>Eradicated Error in System Hub: #45</u></a></li>
<li><a href="https://driver-error.techidaily.com/mitigating-issues-with-acpi-device-33a0/"><u>Mitigating Issues with ACPI: DEVICE 33A0</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-how-to-combine-twomore-gifs-into-one-gif-mergers-offered-for-2024/"><u>New How to Combine Two/More GIFs Into One GIF Mergers Offered for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/finest-pencil-masters-free-vs-paid-windows-apps-reviewed/"><u>Finest Pencil Masters  Free vs Paid Windows Apps Reviewed</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-issues-with-restored-defaults-on-your-amd-radeons-gpu-software/"><u>Resolving Issues with Restored Defaults on Your AMD Radeon's GPU Software</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-hcmon-driver-failed-to-install-expert-advice-and-solutions/"><u>Fixing 'HCMon Driver Failed to Install': Expert Advice and Solutions</u></a></li>
<li><a href="https://driver-error.techidaily.com/tackling-device-configuration-woes-a-step-by-step-solution-for-error-code-1/"><u>Tackling Device Configuration Woes - A Step-by-Step Solution for Error Code 1</u></a></li>
<li><a href="https://extra-skills.techidaily.com/optimizing-your-vlc-livestream-over-the-net-for-2024/"><u>Optimizing Your VLC Livestream over the Net for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-11-8-and-7-device-driver-troubleshooting-and-resolution-steps/"><u>Windows 11, 8 & 7 Device Driver Troubleshooting and Resolution Steps</u></a></li>
<li><a href="https://driver-error.techidaily.com/win11s-high-disk-usage-explained-and-solved/"><u>Win11's High Disk Usage Explained & Solved</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-9-xiaomi-14-ultra-monitoring-apps-for-parental-controls-drfone-by-drfone-virtual-android/"><u>In 2024, Top 9 Xiaomi 14 Ultra Monitoring Apps for Parental Controls | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-guide-to-fix-unrecognized-usb-in-w78/"><u>Step by Step Guide to Fix Unrecognized USB in W7/8</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/reverse-silent-tweets-audible-video-connection/"><u>Reverse Silent Tweets  Audible Video Connection</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-photos-files-from-oppo-find-x6-pro-by-fonelab-android-recover-photos/"><u>How To  Restore Missing Photos Files from Oppo Find X6 Pro.</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-no-cost-split-screen-video-editors-online-and-offline-options-reviewed/"><u>New In 2024, No-Cost Split Screen Video Editors Online and Offline Options Reviewed</u></a></li>
<li><a href="https://driver-error.techidaily.com/bluetooth-woes-windows-solutions-ready/"><u>Bluetooth Woes? Windows Solutions Ready</u></a></li>
<li><a href="https://driver-error.techidaily.com/win-usb-serial-link-resolving-nonoperational-issues/"><u>Win USB-Serial Link: Resolving Nonoperational Issues</u></a></li>
<li><a href="https://driver-error.techidaily.com/hands-on-remedy-for-disrupted-mtp-functionality/"><u>Hands-On Remedy for Disrupted MTP Functionality</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-digital-detox-how-to-turn-off-youtube-on-computers-and-phones/"><u>[Updated] In 2024, Digital Detox  How to Turn Off Youtube on Computers and Phones</u></a></li>
<li><a href="https://driver-error.techidaily.com/prevented-photo-lag-with-asus-webcam-optimization-on-win11/"><u>Prevented Photo Lag with ASUS Webcam: Optimization on Win11</u></a></li>
<li><a href="https://facebook.techidaily.com/social-media-surprise-whats-not-in-your-feed/"><u>Social Media Surprise: What's Not in Your Feed?</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721104801174-ultimate-guide-updating-and-downloading-drivers-for-your-hp-envy-20/"><u>Ultimate Guide: Updating and Downloading Drivers for Your HP Envy 20</u></a></li>
</ul></div>
