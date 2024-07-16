---
title: Unseen Blu-Ray Player in Win11? Here's the Fix
date: 2024-07-15T06:49:12.265Z
updated: 2024-07-16T06:49:12.265Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Unseen Blu-Ray Player in Win11? Here's the Fix
excerpt: This Article Describes Unseen Blu-Ray Player in Win11? Here's the Fix
thumbnail: https://thmb.techidaily.com/7f19cc98af8fc35bf3d4ed1bfe5dccfd58f56435c65265ee5832038cf529fed6.jpeg
---

## Unseen Blu-Ray Player in Win11? Here's the Fix

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cc5c859cb7.png)

 Use [Driver Easy](https://tools.techidaily.com/drivereasy/download/) to fix your not showing up disc, DVD or CD drives immediately!

 If you’ve recently upgraded to Windows 10, and you couldn’t find the**DVD drive** option in**This PC** (Windows 10 OS) window, you’re not alone. Some of you might not even see your DVD/CD ROM option in Device Manager. No need to worry too much about it, it’s possible to fix.

 Here are 4 fixes for you to try. You may not have to try them all; just work your way down until you find the one works for you.

 Method 1:[**Uninstall IDE ATA/ ATAPI controllers**](https://aligracehair.sjv.io/y209r3)
 Method 2:[**Update drivers**](https://cowinaudio.pxf.io/pyx40e)
 Method 3:[**Manually fix corrupted registry entries**](https://tidio.pxf.io/9grog5)
 Method 4:[**Create a registry subkey**](https://modlily.sjv.io/aw92wr)

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595c5576c70aa.jpg)

## **4: Create a registry subkey**

 If you can’t see**UpperFilters** and**LowerFilters** in the Registry pane, please follow the steps below.

 1) On your keyboard, press the**Windows logo key** and**R** at the same time to invoke a**Run** command. Type **regedit** and press**Enter** .

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cca701812e.png)

 2) Follow the path:
**HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Services\\atapi\\**

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd3791d37b.png)

 3) Right-click the blank space on the right panel, when the**New** option pops up, click **Key** .

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd4e640268.png)

 4) Create a new**Controller0** key under**atapi** key.

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd5bb9cfb9.png)

 5) Go to the new**Controller0** key. On the right side of the pane, right-click the blank space and click**DWORD(32-bit) Value** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd68603c2d.png)

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
<li><a href="https://video-capture.techidaily.com/2024-approved-prime-video-chat-solutions-for-pcs-and-phones/"><u>2024 Approved  Prime Video Chat Solutions for PCs & Phones</u></a></li>
<li><a href="https://driver-error.techidaily.com/reintroduce-hidden-dvds-to-windows-os/"><u>Reintroduce Hidden DVDs to Windows OS</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-epicmosaic-insta-video-fusion-for-iosandroid/"><u>In 2024, EpicMosaic  Insta Video Fusion for iOS/Android</u></a></li>
<li><a href="https://driver-error.techidaily.com/addressing-win10-asus-driver-and-acpi/"><u>Addressing Win10: Asus Driver and ACPI</u></a></li>
<li><a href="https://driver-error.techidaily.com/graphics-hardware-blockage-for-windows-10-system/"><u>Graphics Hardware Blockage for Windows 10 System</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-7-troubleshooting-overcoming-the-blue-screen-error-0x0000007e/"><u>Windows 7 Troubleshooting: Overcoming the Blue Screen Error 0X0000007E</u></a></li>
<li><a href="https://driver-error.techidaily.com/win-os-now-recognizes-latest-printer-hardware/"><u>Win OS Now Recognizes Latest Printer Hardware</u></a></li>
<li><a href="https://fake-location.techidaily.com/full-guide-to-fix-itoolab-anygo-not-working-on-htc-u23-pro-drfone-by-drfone-virtual-android/"><u>Full Guide to Fix iToolab AnyGO Not Working On HTC U23 Pro | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-maximize-fun-choose-from-heres-top-5-chrome-extensions-for-facebook-vids/"><u>[Updated] Maximize Fun  Choose From Here's Top 5 Chrome Extensions for Facebook Vids</u></a></li>
<li><a href="https://driver-error.techidaily.com/expert-advice-diagnosing-and-correcting-error-0x0000007e-bsod-issue-on-windows-7-systems/"><u>Expert Advice: Diagnosing and Correcting Error 0X0000007E BSOD Issue on Windows 7 Systems</u></a></li>
<li><a href="https://driver-error.techidaily.com/samsung-system-files-windows-download/"><u>Samsung System Files - Windows Download</u></a></li>
<li><a href="https://driver-error.techidaily.com/quick-method-to-solve-the-broken-key-issue-on-your-hp-notebooks-detailed-steps-included-article-title-407-chars/"><u>Quick Method to Solve the 'Broken' Key Issue on Your HP Notebooks — Detailed Steps Included! - Article Title (407 Chars)</u></a></li>
<li><a href="https://driver-error.techidaily.com/device-access-denial-windows-11-graphic-issue/"><u>Device Access Denial - Windows 11 Graphic Issue</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-capture-the-best-in-google-meet-with-top-screen-recorders/"><u>[New] Capture the Best in Google Meet with Top Screen Recorders</u></a></li>
<li><a href="https://driver-error.techidaily.com/bluetooth-enabling-for-lenovo-on-win11-platform/"><u>Bluetooth Enabling for Lenovo on Win11 Platform</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-where-is-the-best-place-to-catch-dratini-on-realme-v30-drfone-by-drfone-virtual-android/"><u>In 2024, Where Is the Best Place to Catch Dratini On Realme V30 | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721101178033-windows-hello-isnt-available-on-this-device-on-windows-10-solved/"><u>Windows Hello Isn't Available on This Device on Windows 10 [Solved]</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-acpi-driver-fault-id-33a0/"><u>Solving Acpi Driver Fault ID 33A0</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-the-common-device-setup-issue-code-1-not-configured-correctly-in-brand/"><u>Overcoming the Common Device Setup Issue (Code 1 Not Configured Correctly) in [Brand]</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-solution-for-battleye-initialization-failure-due-to-driver-loading-problems/"><u>Step-by-Step Solution for BattlEye Initialization Failure Due to Driver Loading Problems</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-overwatch-video-captures-done-right-made-simple/"><u>[New] In 2024, Overwatch Video Captures – Done Right, Made Simple</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/youtube-monetization-the-new-rules-everyone-hates-for-2024/"><u>YouTube Monetization  The New Rules Everyone Hates for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/turn-off-stubborn-bluetooth-on-windows-10-answer/"><u>Turn Off Stubborn Bluetooth on Windows 10 [Answer]</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-guide-correcting-the-failed-to-install-hcmon-driver-error/"><u>Step-by-Step Guide: Correcting the 'Failed to Install Hcmon Driver Error'</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-time-display-on-windows-11-taskbar/"><u>Mastering Time Display on Windows 11 Taskbar</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-repairing-an-inoperative-obs-video-feed/"><u>[New] Repairing an Inoperative OBS Video Feed</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/share-and-post-like-a-pro-mastering-instagram-gif-uploads-4-step-method/"><u>Share & Post Like a Pro  Mastering Instagram GIF Uploads (4-Step Method)</u></a></li>
<li><a href="https://extra-hints.techidaily.com/accelerate-artistry-in-windows-11-photoshop-for-2024/"><u>Accelerate Artistry in Windows 11 Photoshop for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/top-15-augmented-reality-games-like-pokemon-go-to-play-on-honor-magic5-ultimate-drfone-by-drfone-virtual-android/"><u>Top 15 Augmented Reality Games Like Pokémon GO To Play On Honor Magic5 Ultimate | Dr.fone</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-top-picks-the-ultimate-selection-of-4k-monitors-for-macos/"><u>[Updated] 2024 Approved  Top Picks  The Ultimate Selection of 4K Monitors for MacOS</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/in-2024-youtube-webinar-guide-host-without-spending/"><u>In 2024, YouTube Webinar Guide  Host Without Spending</u></a></li>
<li><a href="https://driver-error.techidaily.com/strategies-to-overcome-base-driver-issues-dm/"><u>Strategies to Overcome Base Driver Issues (DM)</u></a></li>
<li><a href="https://driver-error.techidaily.com/driver-failure-intel-hardware-missing/"><u>Driver Failure: Intel Hardware Missing</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/a-detailed-review-and-alternatives-of-vocaloid6-voice-generator/"><u>A Detailed Review & Alternatives of VOCALOID6 Voice Generator</u></a></li>
<li><a href="https://techidaily.com/how-to-erase-apple-iphone-14-pro-max-data-permanently-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>How To Erase Apple iPhone 14 Pro Max Data Permanently | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/common-problems-with-hp-wireless-peripherals-diagnosis-and-repair-tips/"><u>Common Problems with HP Wireless Peripherals: Diagnosis & Repair Tips</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-quickly-fix-bluetooth-not-working-on-tecno-phantom-v-flip-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Quickly Fix Bluetooth Not Working on Tecno Phantom V Flip | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/elevate-razer-hats-update-driver-in-win11-platform/"><u>Elevate Razer HATs: Update Driver in Win11 Platform</u></a></li>
<li><a href="https://driver-error.techidaily.com/error-rectified-hd-audio-bus/"><u>Error Rectified: HD Audio Bus</u></a></li>
<li><a href="https://driver-error.techidaily.com/efficient-troubleshooting-for-ndis-in-windows/"><u>Efficient Troubleshooting for NDIS in Windows</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-topline-numbers-pewdiepies-yearly-income/"><u>[Updated] In 2024, Topline Numbers  PewDiePie's Yearly Income</u></a></li>
<li><a href="https://driver-error.techidaily.com/put-an-end-to-self-removing-nvidia-drivers/"><u>Put an End to Self-Removing Nvidia Drivers</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-files-back-from-htc-u23-pro-by-fonelab-android-recover-data/"><u>Simple ways to get lost files back from HTC U23 Pro</u></a></li>
<li><a href="https://driver-error.techidaily.com/keyboard-stuck-on-windows-10/"><u>Keyboard Stuck on Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-intel-wireless-ac-9560-not-working-code-10/"><u>[SOLVED] Intel Wireless-AC 9560 Not Working (Code 10)</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixed-invalid-inf-for-service-installation/"><u>Fixed Invalid INF for Service Installation</u></a></li>
<li><a href="https://driver-error.techidaily.com/journey-through-time-demystifying-and-fixing-age-old-usb-composite-device-issues/"><u>Journey Through Time: Demystifying and Fixing Age-Old USB Composite Device Issues</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-foster-community-with-unique-insta-story-questions/"><u>[Updated] Foster Community with Unique Insta Story Questions</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/the-insider-guide-attending-live-tiktok-gigs/"><u>The Insider Guide  Attending Live TikTok Gigs</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-xiaomi-redmi-a2plus-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Xiaomi Redmi A2+ to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolve-device-unavailable-message-windows-xp/"><u>Resolve 'Device Unavailable' Message Windows XP</u></a></li>
<li><a href="https://driver-error.techidaily.com/restore-your-control-the-ultimate-guide-for-effortlessly-fixing-unresponsive-bluetech-in-windows-11-fix-revealed/"><u>Restore Your Control: The Ultimate Guide for Effortlessly Fixing Unresponsive BlueTech in Windows 11 (Fix Revealed)</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-an-airtag-from-your-apple-id-account-from-apple-iphone-13-by-drfone-ios/"><u>In 2024, How to Remove an AirTag from Your Apple ID Account From Apple iPhone 13?</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-and-solving-qualcomm-atheros-bluetooth-driver-problems-in-windows-11/"><u>Troubleshooting and Solving Qualcomm Atheros Bluetooth Driver Problems in Windows 11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/live-event-success-expertly-selecting-5-recording-hardware/"><u>Live Event Success  Expertly Selecting 5 Recording Hardware</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-the-iphone-mobile-host-controller-driver-problem-a-step-by-step-guide/"><u>Fixing the iPhone Mobile Host Controller Driver Problem: A Step-by-Step Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/guide-to-repairing-aged-usb-composite-device-connectivity-concerns-and-errors/"><u>Guide to Repairing Aged USB Composite Device Connectivity Concerns and Errors</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-unlock-apple-iphone-se-when-we-dont-have-apple-id-or-password-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone SE When We Dont Have Apple ID or Password?</u></a></li>
</ul></div>
