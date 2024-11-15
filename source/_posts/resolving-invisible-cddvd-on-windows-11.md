---
title: Resolving Invisible CD/DVD on Windows 11
date: 2024-11-11T20:30:27.206Z
updated: 2024-11-14T20:59:03.571Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Resolving Invisible CD/DVD on Windows 11
excerpt: This Article Describes Resolving Invisible CD/DVD on Windows 11
thumbnail: https://thmb.techidaily.com/85222e642fd060b94196ff7371463ce7792d618f66f107a750ec12115071e0dc.jpg
---

## Resolving Invisible CD/DVD on Windows 11

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135365/19272" target="_top" id="2135365">
  <img src="//a.impactradius-go.com/display-ad/19272-2135365" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135365/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://appsumo.8odi.net/c/5597632/2130889/7443" target="_top" id="2130889">
  <img src="//a.impactradius-go.com/display-ad/7443-2130889" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130889/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Look for**UpperFilters** and**LowerFilters** strings on the right side panel. If you can’t see these two items, move on to Method 2\.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595c55543336b.jpg)

 4) **Delete**  them.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595c5576c70aa.jpg)

## **4: Create a registry subkey**

 If you can’t see**UpperFilters** and**LowerFilters** in the Registry pane, please follow the steps below.

 1) On your keyboard, press the**Windows logo key** and**R** at the same time to invoke a**Run** command. Type **regedit** and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cca701812e.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094419/7443" target="_top" id="2094419">
  <img src="//a.impactradius-go.com/display-ad/7443-2094419" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094419/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 2) Follow the path:
**HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Services\\atapi\\**

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd3791d37b.png)

 3) Right-click the blank space on the right panel, when the**New** option pops up, click **Key** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd4e640268.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151884/7443" target="_top" id="2151884">
  <img src="//a.impactradius-go.com/display-ad/7443-2151884" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151884/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4) Create a new**Controller0** key under**atapi** key.

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd5bb9cfb9.png)

 5) Go to the new**Controller0** key. On the right side of the pane, right-click the blank space and click**DWORD(32-bit) Value** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd68603c2d.png)

 6) Set the name as**EnumDevice1** and press**Enter** . Double-click to set the**Value data** as **1** . Press**OK** to save.

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd71884038.png)

<!-- affiliate ads begin -->
<span id="1424529">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424529.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424529">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424529.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424529%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424529/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-sure.techidaily.com/rom-barely-there-to-top-rated-the-youtube-growth-arc/"><u>[New] From Barely There to Top Rated The Youtube Growth Arc</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-blending-past-and-present-film-aesthetics/"><u>[New] In 2024, Blending Past and Present Film Aesthetics</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-snapshots-and-snickers-the-art-of-memery/"><u>[New] In 2024, Snapshots and Snickers The Art of Memery</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-prime-backdrops-for-effective-virtual-gatherings/"><u>2024 Approved Prime Backdrops for Effective Virtual Gatherings</u></a></li>
<li><a href="https://driver-error.techidaily.com/acpi-driver-fix-for-devices-33a0/"><u>Acpi Driver Fix for Devices 33A0</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/advanced-techniques-to-manage-safe-area-multitasking-for-2024/"><u>Advanced Techniques to Manage Safe Area Multitasking for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/driver-irql-not-less-or-equal-on-windows-10-fixed/"><u>Driver Irql Not Less Or Equal on Windows 10 [Fixed]</u></a></li>
<li><a href="https://buynow-info.techidaily.com/experience-excellence-with-nokia-72-the-mid-tier-powerhouse-that-surpasses-competitors/"><u>Experience Excellence with Nokia 7.2 – The Mid-Tier Powerhouse that Surpasses Competitors!</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-lenovo-y570-driver-issues-for-windows-10/"><u>Fix Lenovo Y570 Driver Issues for Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-omission-of-dvdcd-readers-on-win11/"><u>Fixing Omission of DVD/CD Readers on Win11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-top-10-password-cracking-tools-for-xiaomi-redmi-12-by-drfone-android/"><u>In 2024, Top 10 Password Cracking Tools For Xiaomi Redmi 12</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-unlock-fb-potential-link-your-youtube-video/"><u>In 2024, Unlock FB Potential Link Your YouTube Video</u></a></li>
<li><a href="https://driver-error.techidaily.com/quick-fix-updating-drivers-for-your-hp-envy-20-a-step-by-step-tutorial/"><u>Quick Fix: Updating Drivers for Your HP Envy 20 - A Step-by-Step Tutorial</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-how-to-install-missing-drivers-on-your-pc-for-windows-11-8-and-7/"><u>Resolved: How to Install Missing Drivers on Your PC for Windows 11, 8 & 7</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-realtek-lan-driver-failure-with-windows-11/"><u>Solving Realtek LAN Driver Failure with Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/stop-repeat-uninstalls-fix-nvidia-software-issue/"><u>Stop Repeat Uninstalls: Fix Nvidia Software Issue</u></a></li>
<li><a href="https://article-files.techidaily.com/venture-into-virtuality-critical-reviews-of-tech/"><u>Venture Into Virtuality - Critical Reviews of Tech</u></a></li>
</ul></div>

