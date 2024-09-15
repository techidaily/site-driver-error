---
title: "Fixing Missing Drives: CD/DVD Troubleshooting in Win11"
date: 2024-09-09T04:39:18.151Z
updated: 2024-09-14T16:14:55.068Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: "This Article Describes Fixing Missing Drives: CD/DVD Troubleshooting in Win11"
excerpt: "This Article Describes Fixing Missing Drives: CD/DVD Troubleshooting in Win11"
thumbnail: https://thmb.techidaily.com/a8faf3762ec0652876e641b0799340042cad57c242c2210395cb978ced6a8dea.jpg
---

## Fixing Missing Drives: CD/DVD Troubleshooting in Win11

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
<a href="https://aligracehair.sjv.io/c/5597632/2135364/19272" target="_top" id="2135364">
  <img src="//a.impactradius-go.com/display-ad/19272-2135364" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135364/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Right-click the blank space on the right panel, when the**New** option pops up, click **Key** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd4e640268.png)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137221/26400" target="_top" id="2137221">
  <img src="//a.impactradius-go.com/display-ad/26400-2137221" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137221/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4) Create a new**Controller0** key under**atapi** key.

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd5bb9cfb9.png)

 5) Go to the new**Controller0** key. On the right side of the pane, right-click the blank space and click**DWORD(32-bit) Value** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd68603c2d.png)

 6) Set the name as**EnumDevice1** and press**Enter** . Double-click to set the**Value data** as **1** . Press**OK** to save.

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd71884038.png)

<!-- affiliate ads begin -->
<span id="1975555">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975555.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975555">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975555.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975555%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975555/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://driver-error.techidaily.com/resolved-responsive-input-on-fixd-windows-11-pc/"><u>[Resolved]: Responsive Input on Fix'd Windows 11 PC</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-securely-shifting-snapchat-images-onto-your-device-storage-for-2024/"><u>[Updated] Securely Shifting SnapChat Images Onto Your Device Storage for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-easy-color-techniques-for-professional-outputs/"><u>2024 Approved Easy Color Techniques for Professional Outputs</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-top-asmr-sounds-promoting-deep-sleep/"><u>2024 Approved Top ASMR Sounds Promoting Deep Sleep</u></a></li>
<li><a href="https://extra-tips.techidaily.com/discover-the-ace-of-virtual-worlds-top-oculus-headsets/"><u>Discover the Ace of Virtual Worlds Top Oculus Headsets</u></a></li>
<li><a href="https://driver-error.techidaily.com/easy-setup-windows-plus-samsung-driver/"><u>Easy Setup: Windows + Samsung Driver</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-a-top-down-image-displacement-on-an-asus-desktoplaptop/"><u>Fixing a Top-Down Image Displacement on an ASUS Desktop/Laptop</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-xiaomi-civi-3-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Xiaomi Civi 3 Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-fcp-like-a-pro-top-5-editing-techniques-to-take-your-videos-to-the-next-level/"><u>New 2024 Approved FCP Like a Pro Top 5 Editing Techniques to Take Your Videos to the Next Level</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ntdlldll-troubleshooting-a-comprehensive-fix-manual-for-windows-platforms/"><u>Ntdll.dll Troubleshooting: A Comprehensive Fix Manual for Windows Platforms</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-videos-from-xiaomi-redmi-note-12r-by-fonelab-android-recover-video/"><u>Possible solutions to restore deleted videos from Xiaomi Redmi Note 12R</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-the-missing-pressed-button-in-windows/"><u>Solving the Missing Pressed Button in Windows</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unveil-windows-xp-professional-for-video-production-for-2024/"><u>Unveil Windows XP Professional for Video Production for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-11-hints-to-reveal-invisible-seagate-hd/"><u>Windows 11 Hints to Reveal Invisible Seagate HD</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-11-missing-coprocessor-drivers-fixes-and-guidance-provided/"><u>Windows 11 Missing Coprocessor Drivers - Fixes and Guidance Provided</u></a></li>
</ul></div>

