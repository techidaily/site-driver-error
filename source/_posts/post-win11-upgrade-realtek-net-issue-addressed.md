---
title: Post-Win11 Upgrade, Realtek Net Issue Addressed
date: 2024-07-15T06:54:21.191Z
updated: 2024-07-16T06:54:21.191Z
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
<li><a href="https://network-issues.techidaily.com/decrypting-nvidia-rtx-3080-gaming-woes-and-fixes/"><u>Decrypting NVIDIA RTX 3080 Gaming Woes & Fixes</u></a></li>
<li><a href="https://driver-error.techidaily.com/hidef-device-resolved-audio-driver-issue/"><u>HiDef Device Resolved: Audio Driver Issue</u></a></li>
<li><a href="https://driver-error.techidaily.com/exploring-the-past-and-present-of-usb-composite-devices-in-todays-tech-scene/"><u>Exploring the Past and Present of USB Composite Devices in Today's Tech Scene</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-motorola-moto-g14-drfone-by-drfone-android/"><u>In 2024, How To Use Allshare Cast To Turn On Screen Mirroring On Motorola Moto G14 | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/recovery-of-intel-me-operations/"><u>Recovery of Intel ME Operations</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixed-wdcsam64prewin8sys-no-core-isolation/"><u>Fixed: wdcsam64_prewin8.sys - No Core Isolation</u></a></li>
<li><a href="https://driver-error.techidaily.com/the-ultimate-solution-to-the-missing-enhanced-processor-driver-problem-in-windows-10-explained/"><u>The Ultimate Solution to the Missing Enhanced Processor Driver Problem in Windows 10 Explained</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-enhancing-visual-storytelling-adding-audio-elements-in-adobe-premiere-pro/"><u>New Enhancing Visual Storytelling Adding Audio Elements in Adobe Premiere Pro</u></a></li>
<li><a href="https://driver-error.techidaily.com/service-install-error-inf-correction-achieved/"><u>Service Install Error: INF Correction Achieved</u></a></li>
<li><a href="https://driver-error.techidaily.com/insufficient-system-resources-for-device/"><u>Insufficient System Resources for Device</u></a></li>
<li><a href="https://driver-error.techidaily.com/unable-to-load-devices-wudfrd-driver-event-id-219/"><u>Unable to Load Device's WudfRd Driver (Event ID: 219)</u></a></li>
<li><a href="https://driver-error.techidaily.com/swift-remediation-of-windows-drivers/"><u>Swift Remediation of Windows Drivers</u></a></li>
<li><a href="https://driver-error.techidaily.com/bring-back-sound-to-your-win10-pc-via-usb-device/"><u>Bring Back Sound to Your Win10 PC via USB Device</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-guide-how-to-resolve-missing-coprocessor-driver-issue-in-windows-11/"><u>Fix Guide: How To Resolve 'Missing Coprocessor Driver' Issue in Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-errors-with-your-final-usb-gadget-when-windows-fails-to-detect/"><u>Fixing Errors with Your Final USB Gadget: When Windows Fails to Detect</u></a></li>
<li><a href="https://driver-error.techidaily.com/lost-the-sight-of-my-logitech-brio-webcam-in-windows-heres-what-i-did-to-find-it-again-post-update-step-by-step-fixed/"><u>Lost the Sight of My Logitech Brio Webcam in Windows? Here's What I Did to Find It Again Post-Update (Step by Step) [Fixed]</u></a></li>
<li><a href="https://driver-error.techidaily.com/patched-audio-delay-with-asus-webcam-and-windows-11-blend/"><u>Patched Audio Delay with ASUS Webcam & Windows 11 Blend</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-adobe-premiere-pro-secrets-6-little-known-tips-for-stunning-videos-for-2024/"><u>Updated Adobe Premiere Pro Secrets 6 Little-Known Tips for Stunning Videos for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-struggles-with-devices-driver-search/"><u>Windows Struggles with Device's Driver Search</u></a></li>
<li><a href="https://driver-error.techidaily.com/cure-faulty-usb-serial-cables-in-windows/"><u>Cure Faulty USB-Serial Cables in Windows</u></a></li>
<li><a href="https://driver-error.techidaily.com/comprehensive-pci-card-installers-win-10-8-7/"><u>Comprehensive PCI Card Installers (Win 10, 8, 7)</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-correct-the-access-denied-hurdle-in-your-usb-device-setup-process/"><u>How To Correct the 'Access Denied' Hurdle in Your USB Device Setup Process</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-distinctive-fb-video-aspects/"><u>[Updated] 2024 Approved  Distinctive FB Video Aspects</u></a></li>
<li><a href="https://driver-error.techidaily.com/ultimate-tutorial-download-and-update-essential-software-for-your-hp-envy-20-system/"><u>Ultimate Tutorial: Download & Update Essential Software for Your HP ENVY 20 System</u></a></li>
<li><a href="https://driver-error.techidaily.com/intelladapter-absence-driver-installs-failed/"><u>IntellAdapter Absence: Driver Installs Failed</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-snapchat-recordings-techniques-for-your-phone/"><u>[Updated] Snapchat Recordings  Techniques for Your Phone</u></a></li>
<li><a href="https://driver-error.techidaily.com/unblock-your-nonworking-laptop-keys-a-simple-guide-to-restore-functionality-in-no-time-tech-talker-359-chars/"><u>Unblock Your Nonworking Laptop Keys: A Simple Guide to Restore Functionality in No Time - Tech Talker 359 Chars</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-brushstrokes-breakthrough-top-10-mac-drawers-at-no-cost/"><u>In 2024, Brushstrokes Breakthrough  Top 10 Mac Drawers at No Cost</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-nokia-g42-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to get the dragon scale and evolution-enabled pokemon On Nokia G42 5G? | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-and-resolving-nvidias-gtx-950-code-43-issue-in-windows-10-operating-system/"><u>Troubleshooting and Resolving NVIDIA's GTX 950 'Code 43' Issue in Windows 10 Operating System</u></a></li>
<li><a href="https://driver-error.techidaily.com/no-response-from-lenovo-thinkpad-t430-to-windows-vista-resolved/"><u>No Response From Lenovo Thinkpad T430 to Windows Vista [Resolved]</u></a></li>
<li><a href="https://driver-error.techidaily.com/dealing-with-old-school-usb-composite-devices-solutions-and-tips-for-seamless-connectivity/"><u>Dealing with Old-School USB Composite Devices: Solutions and Tips for Seamless Connectivity</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-laptop-and-mobile-commencing-a-google-meet-session/"><u>[New] 2024 Approved  Laptop & Mobile  Commencing a Google Meet Session</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-mastering-the-art-of-fishy-tones-a-guide-to-using-discords-clownfish-vocal-effect/"><u>In 2024, Mastering the Art of Fishy Tones A Guide to Using Discords Clownfish Vocal Effect</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-from-video-to-music-youtube-to-mp3-on-macos/"><u>[New] 2024 Approved  From Video to Music  YouTube to MP3 on MacOS</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/harnessing-viral-power-marketing-for-profit-on-tiktok/"><u>Harnessing Viral Power  Marketing for Profit on TikTok</u></a></li>
<li><a href="https://driver-error.techidaily.com/revealing-ms-bda-through-visual-rendering-insight/"><u>Revealing MS BDA Through Visual Rendering Insight</u></a></li>
<li><a href="https://driver-error.techidaily.com/reestablishing-enter-input-on-windows-os/"><u>Reestablishing Enter Input on Windows OS</u></a></li>
<li><a href="https://extra-information.techidaily.com/becoming-a-savvy-vr-tour-connoisseur-for-2024/"><u>Becoming a Savvy VR Tour Connoisseur for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/cant-install-drivers-due-to-lack-of-intel-card/"><u>Can't Install Drivers Due to Lack of Intel Card</u></a></li>
<li><a href="https://driver-error.techidaily.com/comprehensive-fixes-what-to-do-when-windows-10-doesnt-recognize-the-coprocessor-driver/"><u>Comprehensive Fixes: What to Do When Windows 10 Doesn't Recognize the Coprocessor Driver</u></a></li>
<li><a href="https://driver-error.techidaily.com/seamless-integration-of-updated-drivers-in-hp-envy-20-pcs-a-comprehensive-guide/"><u>Seamless Integration of Updated Drivers in HP Envy 20 PCs – A Comprehensive Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-ndis-troubleshooting-made-simple/"><u>Windows NDIS Troubleshooting Made Simple</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-code-37-windows-cannot-initialize-the-device-driver-for-this-hardware/"><u>[Solved] Code 37: Windows Cannot Initialize the Device Driver for This Hardware</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unlocking-the-power-of-high-dynamic-range-in-photography-for-2024/"><u>Unlocking the Power of High Dynamic Range in Photography for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-key-approaches-to-convert-youtube-videos-to-mp4/"><u>[New] 2024 Approved  Key Approaches to Convert YouTube Videos to MP4</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-how-to-post-twitter-videos-on-snapchat-in-2024/"><u>[New] How to Post Twitter Videos on Snapchat, In 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-from-flipbooks-to-frames-7-core-strategies-for-crafting-engaging-gifs/"><u>[Updated] From Flipbooks to Frames  7 Core Strategies for Crafting Engaging GIFs</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-installation-errors-why-your-device-driver-might-be-invalid/"><u>Solving Installation Errors: Why Your Device Driver Might Be Invalid</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-complete-guide-to-producing-high-impact-youtube-intros/"><u>[Updated] The Complete Guide to Producing High-Impact YouTube Intros</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-10-best-video-editors-for-webcam-videos/"><u>2024 Approved  10 Best Video Editors for Webcam Videos</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-erase-private-data-from-iphone-se-2022-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>How To Erase Private Data From iPhone SE (2022) | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-remove-cluttered-backgrounds-using-picarts-features/"><u>[New] Remove Cluttered Backgrounds Using PicArt's Features</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-exclusive-review-top-10-gratis-gaming-screen-recorder-apps/"><u>[New] In 2024, Exclusive Review  Top 10 Gratis Gaming Screen Recorder Apps</u></a></li>
</ul></div>
