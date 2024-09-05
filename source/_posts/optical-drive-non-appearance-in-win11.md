---
title: Optical Drive Non-Appearance in Win11
date: 2024-09-04T12:43:39.211Z
updated: 2024-09-05T12:43:39.211Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Optical Drive Non-Appearance in Win11
excerpt: This Article Describes Optical Drive Non-Appearance in Win11
thumbnail: https://thmb.techidaily.com/3322edcb2b3700ce4baa5c0677a8f300e23dbf74c5228f8bd6ca0d33294791ed.png
---

## Optical Drive Non-Appearance in Win11

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cc5c859cb7.png)

 Use [Driver Easy](https://tools.techidaily.com/drivereasy/download/) to fix your not showing up disc, DVD or CD drives immediately!

 If you’ve recently upgraded to Windows 10, and you couldn’t find the**DVD drive** option in**This PC** (Windows 10 OS) window, you’re not alone. Some of you might not even see your DVD/CD ROM option in Device Manager. No need to worry too much about it, it’s possible to fix.

 Here are 4 fixes for you to try. You may not have to try them all; just work your way down until you find the one works for you.

 Method 1:[**Uninstall IDE ATA/ ATAPI controllers**](https://aligracehair.sjv.io/y209r3)
 Method 2:[**Update drivers**](https://cowinaudio.pxf.io/pyx40e)
 Method 3:[**Manually fix corrupted registry entries**](https://tidio.pxf.io/9grog5)
 Method 4:[**Create a registry subkey**](https://modlily.sjv.io/aw92wr)

## **1: Uninstall IDE ATA/ ATAPI controllers**

 One of the reasons why you can’t see DVD/CD-ROM in your Windows 10 PC could be faulty device drivers. You can reinstall the drivers to fix it. Here is how:

 1) On your keyboard, press the**Windows logo key** and**R** at the same time, click**Device Manager** .

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b6098ec3402.png)

 2) Locate**IDE ATA/ ATAPI controllers** .
 3) Right-click **ATA Channel 0** and click **Uninstall** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577e194a84fe7.png)

 4) Right-click **ATA Channel 1** and click**Uninstall** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577e199372f3c.png)

 5) If you have more options under**IDE/ ATAPI controllers** category, right-click them and click**Uninstall** as above procedures.

 6) Reboot your computer after these changes.

 7) Your computer will be able to help you with the detection of the DVD for Windows 10\.

## **2: Update drivers**

 If uninstalling the IDE ATA/ ATAPI controller drivers doesn’t solve the problem for you, it’s likely that you’re using the wrong driver altogether.

 There are two ways you can get the right drivers for your disc /DVD drive: manually or automatically.

**Manual driver update**  – You can update your disc drive driver manually by going to the manufacturer’s website for your computer, and searching for the most recent correct driver for it. Be sure to choose only driver that is compatible with your variant of Windows 10.

**Automatic driver update** –  If you don’t have the time, patience or computer skills to update your drivers manually, you can do it automatically with [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) .  Driver Easy will automatically recognize your system and find the correct driver for your exact disc drive, and your variant of Windows 10, and it will download and install it correctly :

 1)[**Download**](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.

 2) Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b60a61a4afa.png)

 3) Click the**Update** button next to all flagged devices to automatically download and install the correct version of their drivers (you can do this with the FREE version).

 Or click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (this requires the [**Pro version**](https://tools.techidaily.com/drivereasy/download/) – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b60ab0d5aa9.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997635/19272" target="_top" id="1997635">
  <img src="//a.impactradius-go.com/display-ad/19272-1997635" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997635/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **3: Manually fix corrupted registry entries**

**IMPORTANT** : Before we move on, it’s strongly recommended that you [back-up and restore your registry](https://tools.techidaily.com/drivereasy/download/) first.

 If your registry entry is off, you’ll not be able to see certain device on your PC. To fix it:

 1) On your keyboard, press the**Windows logo key** and**R** at the same time to invoke a**Run** command. Type **regedit** and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cca701812e.png)

 2) Follow the path:
 **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Class\\ {4D36E965-E325-11CE-BFC1-08002BE10318}**

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595c55359b5aa.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135361/19272" target="_top" id="2135361">
  <img src="//a.impactradius-go.com/display-ad/19272-2135361" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135361/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) Look for**UpperFilters** and**LowerFilters** strings on the right side panel. If you can’t see these two items, move on to Method 2\.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595c55543336b.jpg)

 4) **Delete**  them.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595c5576c70aa.jpg)

## **4: Create a registry subkey**

 If you can’t see**UpperFilters** and**LowerFilters** in the Registry pane, please follow the steps below.

 1) On your keyboard, press the**Windows logo key** and**R** at the same time to invoke a**Run** command. Type **regedit** and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cca701812e.png)

 2) Follow the path:
**HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Services\\atapi\\**

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd3791d37b.png)

<!-- affiliate ads begin -->
<span id="1770526">
					<video width="240" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1770526.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20702-1770526">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1770526.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftokenmetrics.sjv.io%2Fc%2F5597632%2F1770526%2F20702'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1770526/20702" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) Right-click the blank space on the right panel, when the**New** option pops up, click **Key** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd4e640268.png)

 4) Create a new**Controller0** key under**atapi** key.

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd5bb9cfb9.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012434/19272" target="_top" id="2012434">
  <img src="//a.impactradius-go.com/display-ad/19272-2012434" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012434/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 5) Go to the new**Controller0** key. On the right side of the pane, right-click the blank space and click**DWORD(32-bit) Value** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd68603c2d.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1884021/19272" target="_top" id="1884021">
  <img src="//a.impactradius-go.com/display-ad/19272-1884021" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1884021/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 6) Set the name as**EnumDevice1** and press**Enter** . Double-click to set the**Value data** as **1** . Press**OK** to save.

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd71884038.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2030391/7443" target="_top" id="2030391">
  <img src="//a.impactradius-go.com/display-ad/7443-2030391" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2030391/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7) Exit Registry Editor.

8) Restart your computer.

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
<li><a href="https://driver-error.techidaily.com/fixed-sm-bus-integration-in-windows-11/"><u>[FIXED] Sm Bus Integration in Windows 11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-best-5-non-youtube-editing-tools-for-vids-for-2024/"><u>[New] Best 5 Non-YouTube Editing Tools for Vids for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-discovering-androids-finest-multiplayer-battles/"><u>[New] Discovering Android's Finest Multiplayer Battles</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-virtual-enhancer-facebook-story-sinker-for-2024/"><u>[New] Virtual Enhancer  Facebook Story Sinker for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-why-cant-i-see-videos-on-sony-a6400-in-2024/"><u>[New] Why Can’t I See Videos on Sony A6400, In 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-syncing-webcam-footage-with-screen-recording/"><u>[Updated] In 2024, Syncing Webcam Footage with Screen Recording</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-bridging-gaps-transforming-trend-data-into-video-concepts/"><u>2024 Approved  Bridging Gaps  Transforming Trend Data Into Video Concepts</u></a></li>
<li><a href="https://fix-guide.techidaily.com/4-most-known-ways-to-find-someone-on-tinder-for-tecno-pova-6-pro-5g-by-name-drfone-by-drfone-virtual-android/"><u>4 Most-Known Ways to Find Someone on Tinder For Tecno Pova 6 Pro 5G by Name | Dr.fone</u></a></li>
<li><a href="https://article-files.techidaily.com/beyond-binary-boundaries-metaverse-vs-multiverse-for-2024/"><u>Beyond Binary Boundaries  Metaverse V/S Multiverse for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/driver-installer-conqueror-no-more-errors/"><u>Driver Installer Conqueror – No More Errors</u></a></li>
<li><a href="https://driver-error.techidaily.com/enhanced-performance-win11s-sm-bus-control/"><u>Enhanced Performance: Win11's SM Bus Control</u></a></li>
<li><a href="https://driver-error.techidaily.com/finding-the-missing-opengl-driver-in-intel-icd/"><u>Finding the Missing OpenGL Driver in Intel ICD</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-your-non-functional-hp-laptop-keys-step-by-step-guide-356-chars/"><u>Fix Your Non-Functional HP Laptop Keys Step By Step Guide – 356 Chars</u></a></li>
<li><a href="https://driver-error.techidaily.com/geforce-experience-game-cannot-be-optimized-solved/"><u>GeForce Experience Game Cannot Be Optimized [Solved]</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-make-win1011-see-logitech-receiver/"><u>How to Make Win10/11 See Logitech Receiver</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-get-and-use-pokemon-go-promo-codes-on-vivo-y27-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Get and Use Pokemon Go Promo Codes On Vivo Y27 5G | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-maximizing-your-iphones-creative-capabilities/"><u>In 2024, Maximizing Your iPhone's Creative Capabilities</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1722178257833-navigating-the-impact-of-intelligent-systems-on-psychological-support-and-well-being-improvement/"><u>Navigating the Impact of Intelligent Systems on Psychological Support and Well-Being Improvement.</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-expert-recommended-video-animation-apps-for-mobile/"><u>New 2024 Approved Expert-Recommended Video Animation Apps for Mobile</u></a></li>
<li><a href="https://driver-error.techidaily.com/reinstating-lost-connection-fix-disappearing-bluetooth-hub/"><u>Reinstating Lost Connection: Fix Disappearing Bluetooth Hub</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-hcmon-driver-installation-failure-step-by-step-guide/"><u>Resolving 'Hcmon Driver Installation Failure': Step-by-Step Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-itbm-driver-errors-swiftly-a-step-by-step-rescue-plan/"><u>Resolving ITBM Driver Errors Swiftly: A Step-by-Step Rescue Plan</u></a></li>
<li><a href="https://driver-error.techidaily.com/restore-your-touchpad-with-proven-driver-fixes/"><u>Restore Your Touchpad with Proven Driver Fixes</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-iphone-driver-is-not-installed-waiting-for-windows-update/"><u>Solved: IPhone Driver Is Not Installed. Waiting for Windows Update</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-solutions-for-windows-7-critical-process-died-error-0x0000007e/"><u>Step-by-Step Solutions for Windows 7 'CRITICAL PROCESS DIED' Error (0X0000007E)</u></a></li>
<li><a href="https://driver-error.techidaily.com/tackle-pci-controller-loss-on-win-1011/"><u>Tackle PCI Controller Loss on Win 10/11</u></a></li>
<li><a href="https://driver-error.techidaily.com/tackling-sm-bus-driver-woes-on-win11/"><u>Tackling SM Bus Driver Woes on Win11</u></a></li>
<li><a href="https://driver-error.techidaily.com/the-evolution-and-resolution-of-older-usb-composite-device-issues/"><u>The Evolution and Resolution of Older USB Composite Device Issues</u></a></li>
<li><a href="https://driver-error.techidaily.com/this-is-an-article-for-this-case-the-daylightning-disease-of-the-other-handicaps/"><u>This Is an Article for This Case the Daylightning Disease of the Other Handicaps</u></a></li>
<li><a href="https://driver-error.techidaily.com/triumph-over-troublesome-bluetooth-connections-a-simple-guide-in-windows-11-solved-today/"><u>Triumph Over Troublesome Bluetooth Connections - A Simple Guide in Windows 11 [Solved Today]</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-guide-fixing-a-non-responsive-wireless-keyboard-on-pc/"><u>Troubleshooting Guide: Fixing a Non-Responsive Wireless Keyboard on PC</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-guide-fixing-hp-wireless-keyboard-connectivity-issues/"><u>Troubleshooting Guide: Fixing HP Wireless Keyboard Connectivity Issues</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-tips-enabling-safe-mode-and-discarding-gpu-drivers-in-windows-8-system/"><u>Troubleshooting Tips: Enabling Safe Mode and Discarding GPU Drivers in Windows 8 System</u></a></li>
<li><a href="https://driver-error.techidaily.com/vehicular-compatibility-hurdle/"><u>Vehicular Compatibility Hurdle</u></a></li>
<li><a href="https://driver-error.techidaily.com/win1011-optimizing-sm-bus-drivers-efficiency/"><u>Win10/11: Optimizing Sm Bus Drivers Efficiency</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-11-and-qualcomm-atheros-bluetooth-woes-heres-your-ultimate-fix/"><u>Windows 11 and Qualcomm Atheros Bluetooth Woes? Here's Your Ultimate Fix</u></a></li>
</ul></div>
