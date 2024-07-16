---
title: Fixing Omission of DVD/CD Readers on Win11
date: 2024-07-15T07:00:21.791Z
updated: 2024-07-16T07:00:21.791Z
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

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b60ab0d5aa9.jpg)

## **3: Manually fix corrupted registry entries**

**IMPORTANT** : Before we move on, it’s strongly recommended that you [back-up and restore your registry](https://tools.techidaily.com/drivereasy/download/) first.

 If your registry entry is off, you’ll not be able to see certain device on your PC. To fix it:

 1) On your keyboard, press the**Windows logo key** and**R** at the same time to invoke a**Run** command. Type **regedit** and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cca701812e.png)

 2) Follow the path:
 **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Class\\ {4D36E965-E325-11CE-BFC1-08002BE10318}**

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595c55359b5aa.jpg)

 3) Look for**UpperFilters** and**LowerFilters** strings on the right side panel. If you can’t see these two items, move on to Method 2\.

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595c55543336b.jpg)

 4) **Delete**  them.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595c5576c70aa.jpg)

## **4: Create a registry subkey**

 If you can’t see**UpperFilters** and**LowerFilters** in the Registry pane, please follow the steps below.

 1) On your keyboard, press the**Windows logo key** and**R** at the same time to invoke a**Run** command. Type **regedit** and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cca701812e.png)

 2) Follow the path:
**HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Services\\atapi\\**

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_577cd3791d37b.png)

 3) Right-click the blank space on the right panel, when the**New** option pops up, click **Key** .

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
<li><a href="https://driver-error.techidaily.com/solved-you-need-a-wia-driver-to-use-this-device-scanner-driver-error/"><u>[SOLVED] “You Need a WIA Driver to Use This Device” Scanner Driver Error</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-9-samsung-galaxy-a15-4g-monitoring-apps-for-parental-controls-drfone-by-drfone-virtual-android/"><u>Top 9 Samsung Galaxy A15 4G Monitoring Apps for Parental Controls | Dr.fone</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-2024-approved-2023s-secretive-vids-downloader-list-top-8-edition/"><u>[Updated] 2024 Approved  2023'S Secretive Vids Downloader List  Top 8 Edition</u></a></li>
<li><a href="https://driver-error.techidaily.com/recover-lost-device-on-doswindows-3x/"><u>Recover Lost Device on DOS/Windows 3.x</u></a></li>
<li><a href="https://driver-error.techidaily.com/get-samsung-mobile-os-for-pc/"><u>Get Samsung Mobile OS for PC</u></a></li>
<li><a href="https://driver-error.techidaily.com/resource-utilization-challenges/"><u>Resource Utilization Challenges</u></a></li>
<li><a href="https://driver-error.techidaily.com/nvidia-detection-woes-solutions-available/"><u>Nvidia Detection Woes: Solutions Available</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-embracing-the-future-with-vr-mobile-or-tethered-whats-right-for-you/"><u>[Updated] Embracing the Future with VR  Mobile or Tethered, What's Right For You?</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-access-denied-errors-during-usb-installation-on-windows/"><u>Resolving 'Access Denied' Errors During USB Installation on Windows</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-lenovo-y570-driver-issues-for-windows-10/"><u>Fix Lenovo Y570 Driver Issues for Windows 10</u></a></li>
<li><a href="https://howto.techidaily.com/why-is-my-oppo-a79-5g-offline-troubleshooting-guide-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Is My Oppo A79 5G Offline? Troubleshooting Guide | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/eliminating-device-manager-errors-effectively/"><u>Eliminating Device Manager Errors Effectively</u></a></li>
<li><a href="https://driver-error.techidaily.com/bypassing-the-code-43-hurdle-effective-fixes-for-gtx-950-on-windows-10-systems/"><u>Bypassing the 'Code 43' Hurdle: Effective Fixes for GTX 950 on Windows 10 Systems</u></a></li>
<li><a href="https://driver-error.techidaily.com/win-os-device-compatibility-achieved/"><u>Win OS Device Compatibility Achieved</u></a></li>
<li><a href="https://review-topics.techidaily.com/edit-and-send-fake-location-on-telegram-for-your-xiaomi-redmi-12-5g-in-3-ways-drfone-by-drfone-virtual-android/"><u>Edit and Send Fake Location on Telegram For your Xiaomi Redmi 12 5G in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-essential-speech-recognition-software-android-and-ios-comparisons/"><u>2024 Approved Essential Speech Recognition Software Android & iOS Comparisons</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-palette-prestige-highlighting-10-free-mac-compatible-art-tools/"><u>[Updated] Palette Prestige  Highlighting 10 Free, Mac-Compatible Art Tools</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-charting-a-course-through-yts-creative-space-for-2024/"><u>[Updated] Charting a Course Through YT's Creative Space for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/win11-streamlined-bus-controller-operations/"><u>Win11: Streamlined Bus Controller Operations</u></a></li>
<li><a href="https://driver-error.techidaily.com/devhub-error-48-now-fixed/"><u>DevHub Error #48 Now Fixed</u></a></li>
<li><a href="https://review-topics.techidaily.com/meizu-21-music-recovery-recover-deleted-music-from-meizu-21-by-fonelab-android-recover-music/"><u>Meizu 21 Music Recovery - Recover Deleted Music from Meizu 21</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-unsupported-hardware-recognition-error-with-idt-software/"><u>Troubleshooting: Unsupported Hardware Recognition Error with IDT Software</u></a></li>
<li><a href="https://driver-error.techidaily.com/hd-audio-mastery-on-windows-11/"><u>HD Audio Mastery on Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/darkened-keys-on-asus-pc/"><u>Darkened Keys on Asus PC</u></a></li>
<li><a href="https://activate-lock.techidaily.com/ultimate-guide-from-apple-iphone-13-mini-icloud-activation-lock-bypass-by-drfone-ios/"><u>Ultimate Guide from Apple iPhone 13 mini iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-effortless-extraction-of-facebook-hd-vids/"><u>[Updated] Effortless Extraction of Facebook HD Vids</u></a></li>
<li><a href="https://some-techniques.techidaily.com/innovation-at-your-fingertips-top-10-free-cross-platform-photography-apps-for-2024/"><u>Innovation at Your Fingertips  Top 10 Free, Cross-Platform Photography Apps for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-ultimate-list-top-10-websites-for-free-photo-access-for-2024/"><u>The Ultimate List  Top 10 Websites for Free Photo Access for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/acpi-driver-fix-for-device-id-33a0/"><u>ACPI Driver Fix for Device ID 33A0</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-signal-profileshots-guide-dimensions-file-type-minutes/"><u>2024 Approved  Signal Profileshots Guide  Dimensions, File Type, Minutes</u></a></li>
<li><a href="https://driver-error.techidaily.com/corrected-audio-driver-on-hidef-bus/"><u>Corrected Audio Driver on HiDef Bus</u></a></li>
<li><a href="https://driver-error.techidaily.com/this-code-snippet-x-140-mlbeginning)-yucca-mountain-of-the-epa-a-study-abroad-to-find-an-appropriate-title-vii-b-am-and-heritage-day-campingtons-parasites-i4/"><u>This Code Snippet (X = 140 Ml_beginning|>', Yucca Mountain of the EPA: A Study Abroad to Find an Appropriate Title VII B-A.m and Heritage Day Campington's Parasites, in a Secluded Corner -a) The Company Must Beef Upcoming; I Need Help Children</u></a></li>
<li><a href="https://driver-error.techidaily.com/wacoms-joy-all-connected-no-more-struggles/"><u>Wacom's Joy: All Connected, No More Struggles</u></a></li>
<li><a href="https://driver-error.techidaily.com/hidef-audio-system-error-corrected/"><u>HiDef Audio System: Error Corrected</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-guide-fixing-initialization-issues-with-battleye-service-and-overcoming-driver-loading-errors/"><u>Troubleshooting Guide: Fixing Initialization Issues with BattlEye Service and Overcoming Driver Loading Errors</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-digital-elites-8-the-speedy-video-channels/"><u>[New] Digital Elites 8  The Speedy Video Channels</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-spotting-the-top-10-discreet-instagram-story-followers/"><u>[New] 2024 Approved  Spotting the Top 10 Discreet Instagram Story Followers</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-2024-approved-how-to-create-the-night-to-day-effect-video/"><u>Updated 2024 Approved How to Create the Night-to-Day Effect Video</u></a></li>
<li><a href="https://driver-error.techidaily.com/max-drives-alerts-on-win11-how-to-solve/"><u>Max Drives Alerts on Win11 - How to Solve</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721102239488-solved-generic-bluetooth-radio-driver-issues-in-windows-quickly-and-easily/"><u>[SOLVED] Generic Bluetooth Radio Driver Issues in Windows. Quickly & Easily</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-all-you-need-to-know-about-mega-greninja-for-vivo-v27e-drfone-by-drfone-virtual-android/"><u>In 2024, All You Need To Know About Mega Greninja For Vivo V27e | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/effective-solutions-to-fix-a-malfunctioned-usb-recognition-issue-in-windows-os/"><u>Effective Solutions to Fix a Malfunctioned USB Recognition Issue in Windows OS</u></a></li>
<li><a href="https://driver-error.techidaily.com/master-upgrading-driver-versions-a-comprehvew-for-owners-of-hp-envy-20-pcs-and-laptops/"><u>Master Upgrading Driver Versions: A Comprehvew for Owners of HP ENVY 20 PCs and Laptops</u></a></li>
<li><a href="https://driver-error.techidaily.com/fault-alarm-idedevice-controller-failure/"><u>Fault Alarm: Idedevice Controller Failure</u></a></li>
<li><a href="https://driver-error.techidaily.com/seagate-drive-mystery-showing-up-on-windows/"><u>Seagate Drive Mystery: Showing Up on Windows?</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-device-hub-showstopper-45/"><u>Resolved: Device Hub Showstopper #45</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolve-unrecognized-driver-issues-a-step-by-step-guide-for-computer-compatibility/"><u>Resolve Unrecognized Driver Issues – A Step-by-Step Guide for Computer Compatibility</u></a></li>
<li><a href="https://driver-error.techidaily.com/keyboard-issue-fixed-in-windows-11-system/"><u>Keyboard Issue Fixed in Windows 11 System</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/in-2024-how-to-make-a-imovie-photo-slideshow-with-music-imovie-tutorial/"><u>In 2024, How to Make a iMovie Photo Slideshow with Music? IMovie Tutorial</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-ways-to-trade-pokemon-go-from-far-away-on-realme-narzo-60x-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to trade pokemon go from far away On Realme Narzo 60x 5G? | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/eradicated-asus-webcam-connectivity-issue-in-win11/"><u>Eradicated ASUS Webcam Connectivity Issue in Win11</u></a></li>
<li><a href="https://driver-error.techidaily.com/preventing-nvidia-drivers-from-failure/"><u>Preventing Nvidia Drivers From Failure</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-mirthvid-quick-start-for-video-makers/"><u>[New] MirthVid  Quick Start for Video Makers</u></a></li>
<li><a href="https://audio-editing.techidaily.com/the-ultimate-guide-to-premium-audio-voice-reduction-apps-and-online-services/"><u>The Ultimate Guide to Premium Audio Voice-Reduction Apps & Online Services</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-best-of-breed-snapchat-augmentations-await/"><u>[New] In 2024, Best of Breed Snapchat Augmentations Await</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-hp-touchpad-driver-issue-for-windows-11/"><u>Fix HP Touchpad Driver Issue for Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-code-1-fixing-improper-configuration-on-your-device/"><u>Resolving Code 1: Fixing Improper Configuration on Your Device</u></a></li>
<li><a href="https://driver-error.techidaily.com/graphics-card-limitation-detected-on-win10-system/"><u>Graphics Card Limitation Detected on Win10 System</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-fresh-talent-and-stunts-in-skating-highlights/"><u>[Updated] Fresh Talent and Stunts in Skating Highlights</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-top-7-shooter-games-you-must-play-today/"><u>[New] Top 7 Shooter Games You Must Play Today</u></a></li>
</ul></div>
