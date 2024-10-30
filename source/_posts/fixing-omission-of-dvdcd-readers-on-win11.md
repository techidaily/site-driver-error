---
title: Fixing Omission of DVD/CD Readers on Win11
date: 2024-10-23T01:23:59.544Z
updated: 2024-10-29T18:15:29.529Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Fixing Omission of DVD/CD Readers on Win11
excerpt: This Article Describes Fixing Omission of DVD/CD Readers on Win11
thumbnail: https://thmb.techidaily.com/36cb4ddf3fc78c71836e11f4a803426f35040ec4e34c37b6c57cca04ad1d4891.jpg
---

## Fixing Omission of DVD/CD Readers on Win11

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

## **3: Manually fix corrupted registry entries**

**IMPORTANT** : Before we move on, it’s strongly recommended that you [back-up and restore your registry](https://tools.techidaily.com/drivereasy/download/) first.

 If your registry entry is off, you’ll not be able to see certain device on your PC. To fix it:

 1) On your keyboard, press the**Windows logo key** and**R** at the same time to invoke a**Run** command. Type **regedit** and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cca701812e.png)

 2) Follow the path:
 **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Class\\ {4D36E965-E325-11CE-BFC1-08002BE10318}**

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595c55359b5aa.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027190/19272" target="_top" id="2027190">
  <img src="//a.impactradius-go.com/display-ad/19272-2027190" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027190/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Look for**UpperFilters** and**LowerFilters** strings on the right side panel. If you can’t see these two items, move on to Method 2\.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595c55543336b.jpg)

 4) **Delete**  them.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595c5576c70aa.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148633/16836" target="_top" id="2148633">
  <img src="//a.impactradius-go.com/display-ad/16836-2148633" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148633/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## **4: Create a registry subkey**

 If you can’t see**UpperFilters** and**LowerFilters** in the Registry pane, please follow the steps below.

 1) On your keyboard, press the**Windows logo key** and**R** at the same time to invoke a**Run** command. Type **regedit** and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cca701812e.png)

 2) Follow the path:
**HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Services\\atapi\\**

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd3791d37b.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082536/7443" target="_top" id="2082536">
  <img src="//a.impactradius-go.com/display-ad/7443-2082536" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082536/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Right-click the blank space on the right panel, when the**New** option pops up, click **Key** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd4e640268.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934188/19272" target="_top" id="1934188">
  <img src="//a.impactradius-go.com/display-ad/19272-1934188" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934188/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4) Create a new**Controller0** key under**atapi** key.

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd5bb9cfb9.png)

 5) Go to the new**Controller0** key. On the right side of the pane, right-click the blank space and click**DWORD(32-bit) Value** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd68603c2d.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925473/19272" target="_top" id="1925473">
  <img src="//a.impactradius-go.com/display-ad/19272-1925473" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925473/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 6) Set the name as**EnumDevice1** and press**Enter** . Double-click to set the**Value data** as **1** . Press**OK** to save.

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd71884038.png)

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
<li><a href="https://instagram-clips.techidaily.com/new-from-fast-pace-to-deliberate-motion-making-slow-movies-on-insta/"><u>[New] From Fast Pace to Deliberate Motion Making Slow Movies on Insta</u></a></li>
<li><a href="https://article-files.techidaily.com/new-in-2024-comparing-videography-power-in-prohero-and-keymission/"><u>[New] In 2024, Comparing Videography Power in ProHero and Keymission</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-psd-mastery-journey-unlimited-complimentary-texts/"><u>[New] PSD Mastery Journey Unlimited Complimentary Texts</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ransform-videos-into-stories-discover-the-top-10-reactions-for-2024/"><u>[New] Transform Videos Into Stories Discover the Top 10 Reactions for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-intel-corporation-driver-update-for-intelr-hd-graphics-4400-failed-issue/"><u>[Solved] Intel Corporation Driver Update for Intel(R) HD Graphics 4400 Failed Issue</u></a></li>
<li><a href="https://driver-error.techidaily.com/beat-the-gtx-950s-code-43-glitch-in-windows-10-with-these-expert-troubleshooting-tips-now-solved/"><u>Beat the GTX 950'S Code 43 Glitch in Windows 10 with These Expert Troubleshooting Tips - Now Solved!</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/bypass-reset-reno-8t-phone-screen-passcode-pattern-pin-by-drfone-android-unlock-android-unlock/"><u>Bypass/Reset Reno 8T Phone Screen Passcode/Pattern/Pin</u></a></li>
<li><a href="https://driver-error.techidaily.com/chromebook-pixel-non-detection-on-centos-linux-fix-applied/"><u>Chromebook Pixel Non-Detection on CentOS Linux (Fix Applied)</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-m-audio-m-track-2x2-driver-issue-easily-and-quickly/"><u>Fix M-Audio M-Track 2X2 Driver Issue Easily & Quickly</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721104877619-fix-built-in-wifi-and-bluetooth-on-my-laptop-refuse-to-shut-down-in-windows/"><u>Fix: Built-In Wifi and Bluetooth on My Laptop Refuse to Shut Down in Windows!</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixed-usb-hub-interrupts-after-kernel-patch/"><u>Fixed USB Hub Interrupts After Kernel Patch</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-phone-touchscreen-of-vivo-x100-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Phone Touchscreen Of Vivo X100 | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/how-to-optimizing-vlc-for-mac-performance/"><u>How-To Optimizing VLC for Mac Performance</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-recommendation-best-websites-to-download-game-of-thrones-ringtones/"><u>In 2024, Recommendation Best Websites to Download Game of Thrones Ringtones</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ase-click-through-with-best-youtube-thumbnail-fonts-for-2024/"><u>Increase Click-Through with Best YouTube Thumbnail Fonts for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/simple-solutions-to-fix-android-systemui-has-stopped-error-for-motorola-g54-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Simple Solutions to Fix Android SystemUI Has Stopped Error For Motorola G54 5G | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/systems-resource-inventory-shortfall/"><u>System's Resource Inventory Shortfall</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721103883540-unlock-the-magic-of-bluetech-on-new-pc-with-this-quick-guide-fixed-windows-11-bluescreen-issue-done/"><u>Unlock the Magic of BlueTech on New PC with This Quick Guide - Fixed Windows 11 Bluescreen Issue – Done</u></a></li>
<li><a href="https://driver-error.techidaily.com/unresponsive-kbs-windows-issue/"><u>Unresponsive KBs, Windows Issue</u></a></li>
</ul></div>

