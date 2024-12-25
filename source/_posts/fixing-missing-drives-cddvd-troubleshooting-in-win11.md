---
title: "Fixing Missing Drives: CD/DVD Troubleshooting in Win11"
date: 2024-12-19T07:36:46.217Z
updated: 2024-12-24T23:00:03.320Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rxyki8-Y630?si=dHLkIxG59zdlZeN0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fJlICvacgJY?si=jNeijBVj7ia4ammA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eMEJvwMM0vk?si=EQF_jo_4u9v5iJ_C" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **4: Create a registry subkey**

 If you can’t see**UpperFilters** and**LowerFilters** in the Registry pane, please follow the steps below.

 1) On your keyboard, press the**Windows logo key** and**R** at the same time to invoke a**Run** command. Type **regedit** and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cca701812e.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aqeO4ed766s?si=AWtKHxP4hvQRd_lk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 2) Follow the path:
**HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Services\\atapi\\**

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd3791d37b.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LI9nKlbhnw8?si=uUXFVbuEqXtFHHv0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Right-click the blank space on the right panel, when the**New** option pops up, click **Key** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd4e640268.png)

 4) Create a new**Controller0** key under**atapi** key.

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd5bb9cfb9.png)

 5) Go to the new**Controller0** key. On the right side of the pane, right-click the blank space and click**DWORD(32-bit) Value** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd68603c2d.png)

 6) Set the name as**EnumDevice1** and press**Enter** . Double-click to set the**Value data** as **1** . Press**OK** to save.

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd71884038.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FATJWpNYmio?si=72ugPTb3vJXz6cAM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-posts.techidaily.com/updated-2024-approved-gopros-camera-faceoff-master-360-versus-hero-11-pro/"><u>[Updated] 2024 Approved GoPro's Camera Faceoff Master 360 versus Hero 11 Pro</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-a-look-inside-magix-pixel-management/"><u>2024 Approved A Look Inside MAGIX Pixel Management</u></a></li>
<li><a href="https://driver-error.techidaily.com/device-revived-status-update-code-unlocked/"><u>Device Revived: Status Update - Code Unlocked</u></a></li>
<li><a href="https://driver-error.techidaily.com/device-struggles-with-available-resources-quota/"><u>Device Struggles with Available Resources Quota</u></a></li>
<li><a href="https://driver-error.techidaily.com/ensuring-reliability-of-your-nvidia-codebase/"><u>Ensuring Reliability of Your Nvidia Codebase</u></a></li>
<li><a href="https://driver-error.techidaily.com/eradicate-bus-latency-anomaly/"><u>Eradicate Bus Latency Anomaly</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-a-motorola-razr-40-ultra-phone-that-is-locked-by-drfone-android/"><u>How to Reset a Motorola Razr 40 Ultra Phone that is Locked?</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-windows-movie-maker-your-gateway-into-the-world-of-digital-cartoons/"><u>In 2024, Windows Movie Maker Your Gateway Into the World of Digital Cartoons</u></a></li>
<li><a href="https://win-howtos.techidaily.com/laptop-microphone-malfunction-heres-the-solution/"><u>Laptop Microphone Malfunction? Here's the Solution</u></a></li>
<li><a href="https://driver-error.techidaily.com/no-support-for-drivers-without-intel-card/"><u>No Support for Drivers Without Intel Card</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/2173157-9781848587021-nostradamus-other-prophets-and-seers/"><u>Nostradamus & Other Prophets and Seers | Free Book</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/pitting-two-titans-of-chatbots-gpt-and-huggingchat/"><u>Pitting Two Titans of ChatBots: GPT & HuggingChat</u></a></li>
<li><a href="https://driver-error.techidaily.com/simple-solutions-for-pc-users-how-to-activate-safe-mode-and-remove-graphics-driver-on-windows-8/"><u>Simple Solutions for PC Users: How to Activate Safe Mode & Remove Graphics Driver on Windows 8</u></a></li>
<li><a href="https://win-dash.techidaily.com/simplified-steps-to-download-and-update-microsoft-drivers-on-windows-systems/"><u>Simplified Steps to Download & Update Microsoft Drivers on Windows Systems</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-dolby-advanced-audio-unable-to-start-the-dolby-audio-driver-in-windows-10/"><u>Solved Dolby Advanced Audio: Unable to Start the Dolby Audio Driver in Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-hcomdevicenotfound-a-step-by-step-guide/"><u>Solving 'HcomDeviceNotFound' - A Step-by-Step Guide</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solving-the-issue-of-silent-videos-expert-advice-for-restoring-audio-in-your-facebook-movies-on-pc/"><u>Solving the Issue of Silent Videos: Expert Advice for Restoring Audio in Your Facebook Movies on PC</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-fix-hp-laptop-keyboard-not-working-issue/"><u>Step by Step Fix HP Laptop Keyboard Not Working Issue</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-fixes-how-to-restore-microphone-functionality-on-your-steelseries-arctis-prime/"><u>Troubleshooting Fixes: How to Restore Microphone Functionality on Your SteelSeries Arctis Prime</u></a></li>
</ul></div>

