---
title: Fixing Omission of DVD/CD Readers on Win11
date: 2024-08-15T06:38:32.778Z
updated: 2024-08-16T06:38:32.778Z
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
<li><a href="https://driver-error.techidaily.com/fixed-detection-issue-for-graphic-cards/"><u>[FIXED] Detection Issue for Graphic Cards</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixed-intel-wi-fi-ax201-signal-strength-issue/"><u>[FIXED] Intel Wi-Fi AX201 Signal Strength Issue</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-simplify-storytelling-transform-vimeo-into-captivating-gifs-for-2024/"><u>[New] Simplify Storytelling  Transform Vimeo Into Captivating GIFs for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-windows-ignores-nvidia-graphics/"><u>[RESOLVED] Windows Ignores Nvidia Graphics</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-how-to-fix-wpd-filesystem-volume-driver-issues/"><u>[SOLVED] How to Fix WPD FileSystem Volume Driver Issues</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-ipad-users-create-professional-time-lapse-videos/"><u>[Updated] 2024 Approved  IPad Users  Create Professional Time-Lapse Videos</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-bite-sized-urls-essential-tools-for-youtubers-to-streamline-sharing/"><u>[Updated] Bite-Sized URLs  Essential Tools for Youtubers to Streamline Sharing</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-proven-ways-to-record-and-save-ps4-games/"><u>[Updated] In 2024, Proven Ways to Record and Save PS4 Games</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-ultimate-choice-10-excellent-camera-lenses/"><u>2024 Approved  Ultimate Choice  10 Excellent Camera Lenses</u></a></li>
<li><a href="https://driver-error.techidaily.com/acemagic-admits-to-accidental-inclusion-of-spyware-in-their-just-released-lineup-of-mini-computers-limited-impact-confirmed/"><u>AceMagic Admits to Accidental Inclusion of Spyware in Their Just-Released Lineup of Mini Computers - Limited Impact Confirmed</u></a></li>
<li><a href="https://driver-error.techidaily.com/diagnosing-and-repairing-your-last-plugged-in-usb-gear-that-windows-cant-detect/"><u>Diagnosing and Repairing Your Last Plugged-In USB Gear That Windows Can't Detect</u></a></li>
<li><a href="https://driver-error.techidaily.com/direct-fix-reconnecting-with-mtp-drivers/"><u>Direct Fix: Reconnecting with MTP Drivers</u></a></li>
<li><a href="https://common-error.techidaily.com/diy-repair-strategies-to-correct-oculus-equipment-failures-in-the-new-year-2024-edition/"><u>DIY Repair Strategies to Correct Oculus Equipment Failures in the New Year, 2024 Edition</u></a></li>
<li><a href="https://driver-error.techidaily.com/eliminate-usb-port-malfunction-in-dell-notebook/"><u>Eliminate USB Port Malfunction in Dell Notebook</u></a></li>
<li><a href="https://driver-error.techidaily.com/end-automatic-uninstall-cycle-for-drivers-solution-found/"><u>End Automatic Uninstall Cycle for Drivers: Solution Found</u></a></li>
<li><a href="https://driver-error.techidaily.com/enhance-performance-in-win11/"><u>Enhance Performance in Win11</u></a></li>
<li><a href="https://driver-error.techidaily.com/error-22-rectified-activation-successful/"><u>Error 22 Rectified; Activation Successful</u></a></li>
<li><a href="https://driver-error.techidaily.com/expert-advice-navigating-to-safe-mode-and-disabling-graphics-card-software-in-windows-8-systems/"><u>Expert Advice: Navigating to Safe Mode and Disabling Graphics Card Software in Windows 8 Systems</u></a></li>
<li><a href="https://win-blog.techidaily.com/expert-tips-on-correcting-the-palworld-session-search-malfunction/"><u>Expert Tips on Correcting the Palworld Session Search Malfunction</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-missing-driver-issues-on-windows-10-8-and-7-a-comprehensive-guide/"><u>Fixing Missing Driver Issues on Windows 10, 8, and 7: A Comprehensive Guide</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-your-amd-ati-radeon-hd-3450-up-to-date-quick-and-easy-drivers-download/"><u>Get Your AMD ATI Radeon HD 3450 Up to Date: Quick & Easy Drivers Download</u></a></li>
<li><a href="https://driver-error.techidaily.com/guide-to-reviving-classic-usb-composite-devices/"><u>Guide to Reviving Classic USB Composite Devices</u></a></li>
<li><a href="https://driver-error.techidaily.com/halt-the-cycle-no-more-nvidia-driver-deletions/"><u>Halt the Cycle: No More Nvidia Driver Deletions</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-can-i-make-my-seagate-disk-appear-on-windows-10/"><u>How Can I Make My Seagate Disk Appear on Windows 10?</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-initiate-safe-mode-in-windows-navigate-through-the-process-of-uninstalling-your-graphics-card-driver/"><u>How to Initiate Safe Mode in Windows Navigate Through the Process of Uninstalling Your Graphics Card Driver?</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-troubleshoot-with-safe-mode-graphics-card-driver-removal-techniques-for-window-8-users/"><u>How To Troubleshoot with Safe Mode: Graphics Card Driver Removal Techniques for Window 8 Users</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-upgrade-or-downgrade-iphone-8-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade iPhone 8 Without iTunes? | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-catalyze-viewers-interest-tutorial-for-traffic-triumphs/"><u>In 2024, Catalyze Viewers' Interest  Tutorial for Traffic Triumphs</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/in-2024-how-to-download-youtube-playlist-step-by-step/"><u>In 2024, How to Download YouTube Playlist-Step by Step!</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-vivo-y78-5g-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Vivo Y78 5G to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-universal-unlock-pattern-for-vivo-y200-by-drfone-android/"><u>In 2024, Universal Unlock Pattern for Vivo Y200</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-pursuit-of-perfection-does-picku-outshine-other-android-tools-in-2024/"><u>In Pursuit of Perfection  Does PickU Outshine Other Android Tools, In 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/mastering-troubleshooting-entering-safe-mode-and-removing-graphics-card-software-in-window-8/"><u>Mastering Troubleshooting: Entering Safe Mode and Removing Graphics Card Software in Window 8</u></a></li>
<li><a href="https://driver-error.techidaily.com/mouse-lags-freezes-stutters-in-windows-11-fixed/"><u>Mouse Lags, Freezes, Stutters in Windows 11 [Fixed]</u></a></li>
<li><a href="https://driver-error.techidaily.com/my-computer-wont-recognize-my-latest-era-logitech-prodigy-cam-post-10-update-heres-why-and-how-to-fix-it-solved/"><u>My Computer Won't Recognize My Latest-Era Logitech Prodigy Cam, Post 10 Update – Here’s Why and How to Fix It ![Solved]</u></a></li>
<li><a href="https://driver-error.techidaily.com/nvidia-drivers-installation-fixed-and-successful/"><u>Nvidia Drivers Installation Fixed and Successful</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-the-issue-of-non-supported-hardware-in-your-device-configuration-software/"><u>Overcoming the Issue of Non-Supported Hardware in Your Device Configuration Software</u></a></li>
<li><a href="https://howto.techidaily.com/poco-x5-pro-not-receiving-texts-10-hassle-free-solutions-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Poco X5 Pro Not Receiving Texts? 10 Hassle-Free Solutions Here | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/prevented-faulty-device-communication/"><u>Prevented Faulty Device Communication</u></a></li>
<li><a href="https://driver-error.techidaily.com/repairing-the-loading-error-of-enex-in-win11-environment/"><u>Repairing the Loading Error of eNEX in Win11 Environment</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-how-to-install-missing-drivers-on-your-windows-10-8-or-7-machine/"><u>Resolved: How to Install Missing Drivers on Your Windows 10, 8 or 7 Machine</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-non-functional-bluetooth-drivers-for-qualcomm-atheros-devices-on-windows-11/"><u>Resolving Non-Functional Bluetooth Drivers for Qualcomm Atheros Devices on Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-the-invalid-inf-configuration-error/"><u>Solving the Invalid INF Configuration Error</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-win10-no-display-for-seagate-hdd/"><u>Solving Win10: No Display for Seagate HDD</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-google-pixel-fold-drfone-by-drfone-virtual-android/"><u>The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Google Pixel Fold | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/tightening-up-inf-service-setup-issues/"><u>Tightening Up INF Service Setup Issues</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-and-installing-missing-drivers-for-your-device-on-windows-operating-systems-11-8-and-aturdays-a-comprehensive-guide/"><u>Troubleshooting and Installing Missing Drivers for Your Device on Windows Operating Systems (11, 8 & Aturdays) - A Comprehensive Guide!</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-logitech-brio-webcam-unrecognized-post-windows-10-update-solved/"><u>Troubleshooting Logitech Brio Webcam Unrecognized Post-Windows 10 Update [Solved]</u></a></li>
<li><a href="https://driver-error.techidaily.com/tutorial-keeping-your-hp-envy-20-series-device-current-with-latest-drivers/"><u>Tutorial: Keeping Your HP Envy 20 Series Device Current with Latest Drivers</u></a></li>
<li><a href="https://driver-error.techidaily.com/ultimate-guide-to-get-the-latest-driver-updates-for-your-hp-envy-20-notebook/"><u>Ultimate Guide to Get the Latest Driver Updates for Your HP ENVY 20 Notebook</u></a></li>
<li><a href="https://driver-error.techidaily.com/uninstall-troubleshooting-stubborn-nvidia-driver/"><u>Uninstall Troubleshooting: Stubborn Nvidia Driver</u></a></li>
<li><a href="https://driver-error.techidaily.com/wi-fi-80211n-broadcoms-solved-problem-on-windows-platform/"><u>Wi-Fi 802.11N: Broadcom's Solved Problem on Windows Platform</u></a></li>
<li><a href="https://driver-error.techidaily.com/win10-woes-fixing-elan-touchpad-errors/"><u>Win10 Woes: Fixing Elan Touchpad Errors</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-10-ignoring-seagate-external-drive-fix-tips/"><u>Windows 10 Ignoring Seagate External Drive - Fix Tips</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-10-streamline-your-bluetooth-drivers/"><u>Windows 10: Streamline Your Bluetooth Drivers</u></a></li>
</ul></div>
