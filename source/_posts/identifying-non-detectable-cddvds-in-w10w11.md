---
title: Identifying Non-Detectable CD/DVDs in W10/W11
date: 2024-12-07T16:38:48.462Z
updated: 2024-12-10T04:11:14.450Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Identifying Non-Detectable CD/DVDs in W10/W11
excerpt: This Article Describes Identifying Non-Detectable CD/DVDs in W10/W11
thumbnail: https://thmb.techidaily.com/4f2d8016e3108f947ee3774ed234e522592c51bdb9d218a2d3fa1a7e34081e27.jpg
---

## Identifying Non-Detectable CD/DVDs in W10/W11

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RhLjZsruC9M?si=-861oUSfrUde2Ykt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 2) Locate**IDE ATA/ ATAPI controllers** .
 3) Right-click **ATA Channel 0** and click **Uninstall** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577e194a84fe7.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/kiW7sLvL65k?si=IHSeRFsYCrfqpn2o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Look for**UpperFilters** and**LowerFilters** strings on the right side panel. If you can’t see these two items, move on to Method 2\.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595c55543336b.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DBMTAJBx-X4?si=sje5pFJXiHzJJGbP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 4) **Delete**  them.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595c5576c70aa.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **4: Create a registry subkey**

 If you can’t see**UpperFilters** and**LowerFilters** in the Registry pane, please follow the steps below.

 1) On your keyboard, press the**Windows logo key** and**R** at the same time to invoke a**Run** command. Type **regedit** and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cca701812e.png)

 2) Follow the path:
**HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Services\\atapi\\**

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd3791d37b.png)

 3) Right-click the blank space on the right panel, when the**New** option pops up, click **Key** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd4e640268.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaGNHfAT92w?si=bvHo1iYK2JBIPtRo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 4) Create a new**Controller0** key under**atapi** key.

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd5bb9cfb9.png)

 5) Go to the new**Controller0** key. On the right side of the pane, right-click the blank space and click**DWORD(32-bit) Value** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd68603c2d.png)

 6) Set the name as**EnumDevice1** and press**Enter** . Double-click to set the**Value data** as **1** . Press**OK** to save.

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd71884038.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X4q6gyaEojM?si=ImdFm6Zsr0azykqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://some-skills.techidaily.com/new-nextgen-android-for-immersive-3d-viewing/"><u>[New] NextGen Android for Immersive 3D Viewing</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-step-by-step-strategies-for-discord-video-streamers-for-2024/"><u>[New] Step-By-Step Strategies for Discord Video Streamers for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/adjusting-win1011-for-stable-sm-bus-driver/"><u>Adjusting Win10/11 for Stable Sm Bus Driver</u></a></li>
<li><a href="https://driver-error.techidaily.com/battleye-setup-error-overcoming-the-driver-load-error-hurdle-in-your-gameplay-experience/"><u>BattlEye Setup Error: Overcoming the 'Driver Load Error' Hurdle in Your Gameplay Experience</u></a></li>
<li><a href="https://driver-error.techidaily.com/bluetooth-peripheral-device-driver-not-found-on-windows-7-solved/"><u>Bluetooth Peripheral Device Driver Not Found on Windows 7 [Solved]</u></a></li>
<li><a href="https://driver-error.techidaily.com/bring-back-lost-lfe-channel-with-your-pcs-audio-system-after-dynaudio-driver-installation-fixed-yes/"><u>Bring Back Lost LFE Channel with Your PC’s Audio System After Dynaudio Driver Installation, Fixed - Yes!✔️</u></a></li>
<li><a href="https://driver-error.techidaily.com/correcting-errors-in-the-service-configuration-segment-of-inf/"><u>Correcting Errors in the Service Configuration Segment of INF</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ng-edge-techniques-for-excellent-sound-no-mic-included/"><u>Cutting-Edge Techniques for Excellent Sound, No Mic Included</u></a></li>
<li><a href="https://driver-error.techidaily.com/device-initialization-success-for-code-37/"><u>Device Initialization Success for Code 37</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721098903197-efficiently-tackle-wireless-issues-windows-style/"><u>Efficiently Tackle Wireless Issues, Windows Style</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/embrace-a-holistic-approach-to-health-with-fitbit-sense-vs-apple-watch/"><u>Embrace a Holistic Approach to Health with Fitbit Sense Vs. Apple Watch</u></a></li>
<li><a href="https://win-community.techidaily.com/gratis-software-de-duplicacao-e-ripagem-para-drives-hddssd-aulas-detalhadas/"><u>Grátis Software De Duplicação E Ripagem Para Drives HDD/SSD: Aulas Detalhadas</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-accelerating-or-decelerating-mastering-snapchats-timeline-controls/"><u>In 2024, Accelerating or Decelerating Mastering Snapchat's Timeline Controls</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/in-depth-analysis-of-sumind-bt70b-bluetooth-unit-perfect-companion-for-on-the-go-music-streaming/"><u>In-Depth Analysis of Sumind BT70B Bluetooth Unit – Perfect Companion for On-The-Go Music Streaming</u></a></li>
<li><a href="https://screen-capture.techidaily.com/maximize-fun-5-windows-11-gamers-recording-tactics/"><u>Maximize Fun 5 Windows 11 Gamers' Recording Tactics</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-the-speakers-selection-top-rated-audio-recording-applications-of-the-year/"><u>New In 2024, The Speakers Selection Top-Rated Audio Recording Applications of the Year</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-30-best-gmail-keyboard-shortcuts/"><u>The 30 Best Gmail Keyboard Shortcuts</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721104996068-troubles-with-your-recently-updated-pc-cant-find-my-dear-old-prodigy-cam-heres-what-i-learned-to-do-about-it-solved/"><u>Troubles with Your Recently Updated PC? Can't Find My Dear Old Prodigy Cam – Here’s What I Learned to Do About It ![Solved]</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721096890246-windowstechissue-my-pc-wont-stop-responding-to-my-built-in-wifibluetooth-commands/"><u>WindowsTechIssue - My PC Won’t Stop Responding to My Built-In WIFI/Bluetooth Commands</u></a></li>
</ul></div>

