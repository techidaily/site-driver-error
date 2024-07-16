---
title: How to Deactivate Non-Stop Bluetooth on PCs
date: 2024-07-15T06:51:41.124Z
updated: 2024-07-16T06:51:41.124Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes How to Deactivate Non-Stop Bluetooth on PCs
excerpt: This Article Describes How to Deactivate Non-Stop Bluetooth on PCs
thumbnail: https://thmb.techidaily.com/310ebf5ae5294b3c09bff886e3c558b63079bc0b815690abddeb6c6ade1d7933.JPG
---

## How to Deactivate Non-Stop Bluetooth on PCs

Windows 10 users have been complaining that they are**unable to turn off**the Bluetooth connection even when they don’t want to use their Bluetooth devices, for instance, when they are in a neighborhood where there are so many Bluetooth devices detected. They cannot see the toggle switch (circled out in the screenshot) in Bluetooth device setting.

![](https://images.drivereasy.com/wp-content/uploads/2016/11/manage-bluetooth-devices.jpg)

The reason why this is happening is that Microsoft seems to have an odd logic. It will recognize laptops with battery on is the mobile devices, thus with the Bluetooth device toggle available and easy to access. But if you are with a desktop, or sometimes, an all-in-one, chances are Windows 10 will not see your computer as a mobile device, thus it will not let you have access to the Bluetooth devices management panel. Luckily, this is not a difficult question to solve, not at all. Follow the options below to fix your problem fast and easily ![**Option 1: Disable Bluetooth device driver**](https://boody-eco-wear.pxf.io/qyo4oo) [**Option 2: Update Bluetooth device driver**](https://propmoneyinc.pxf.io/q4jzdy) [**Option 3: Modify Registry settings**](https://united.elfm.net/zqobdx)   **Option 1: Disable Bluetooth device driver** 1) Open**Device Manager** by pressing**Windows key**and**R**at the same time. Then type in**devmgmt.msc** and hit**Enter**.

![](https://images.drivereasy.com/wp-content/uploads/2016/11/devmgmt-msc.png)

 2) In**Device Manager** , expand category Bluetooth, then right click the Bluetooth device that you want to temporarily disconnect and choose**Disable** .

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/11/disable-bluetooth-device-manager.jpg)

 If you cannot see all of your Bluetooth devices, please click the**View** button and then select**Show hidden devices** .

![](https://images.drivereasy.com/wp-content/uploads/2016/11/show-hidden-devices.png)

 Please note that the name of your Bluetooth device could be different from mine, which is very natural and normal. If you have multiple Bluetooth devices, you might see other options here. The procedure is the same, just right click them and**Disable** them.   **Option 2: Update Bluetooth device driver** If the steps above don’t resolve your Bluetooth problem in Windows 10, it may be caused by a device driver.  You can automatically update all your device drivers to the latest correct version with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .  Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version it takes just 2 clicks (and you get full support and a 30-day money back guarantee): 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy. 2) Run Driver Easy and click the **Scan Now**  button. Driver Easy will then scan your computer and detect any problem drivers.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/06/img_594b60655cf90.png)

3) Click the **Update** button next to the flagged Bluetooth device to automatically download and install the correct version of that driver (you can do this with the FREE version). Or click **Update All** to automatically download and install the correct version of **_all_**  the drivers that are missing or out of date on your system (this requires the [**Pro version**](https://tools.techidaily.com/drivereasy/download/)  – you’ll be prompted to upgrade when you click Update All). ![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58e613efeb2c3.jpg)   **Option 3: Modify Registry settings** **Note**: In this option, we will be making some changes to the Registry. Before doing that, it is very important for you to [**backup**](https://tools.techidaily.com/drivereasy/download/) the registry first, just in case any unwanted error happens. 1) Type**regedit**in the search box and then choose**regedit Run command** from the list of choice.

![](https://images.drivereasy.com/wp-content/uploads/2016/11/regedit-run-command.png)

When prompted for administrator permission, just click**Yes**to continue.

<!-- affiliate ads begin -->

<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/11/uac.png)

2) Follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\ActionCenter\\Quick Actions\\All\\SystemSettings\_Device\_BluetoothQuickAction**.

![](https://images.drivereasy.com/wp-content/uploads/2016/11/hkey_local_machinesoftwaremicrosoftwindowscurrentversionactioncenterquick-actionsallsystemsettings_device_bluetoothquickaction.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) On the right pane, locate and right click the file with the name **Type**and choose**Modify**. ![](https://images.drivereasy.com/wp-content/uploads/2016/11/modify-value.png) 4) Then change the**Value data**from 0 to**1**. Then hit**OK**to save and exit.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/11/value-data.png)

5) Restart your computer after the change.

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
<li><a href="https://easy-unlock-android.techidaily.com/10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-realme-11-proplus-by-drfone-android/"><u>10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Realme 11 Pro+</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-mastering-youtube-videos-your-comprehensive-tutorial/"><u>In 2024, Mastering YouTube Videos  Your Comprehensive Tutorial</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-8-ways-to-transfer-photos-from-motorola-defy-2-to-iphone-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 8 Ways to Transfer Photos from Motorola Defy 2 to iPhone Easily | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/system-call-issue-with-io-controller-over/"><u>System Call Issue with I/O Controller Over</u></a></li>
<li><a href="https://driver-error.techidaily.com/keyboard-functional-after-fixing-windows-11-error/"><u>Keyboard Functional After Fixing Windows 11 Error</u></a></li>
<li><a href="https://driver-error.techidaily.com/where-did-my-nvidia-driver-go/"><u>Where Did My Nvidia Driver Go?</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-in-2024-phone-aspect-ratio-vertical-definition-types-and-tips/"><u>Updated In 2024, Phone Aspect Ratio Vertical Definition, Types and Tips</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-usb-mass-storage-device-driver-issue/"><u>Fix USB Mass Storage Device Driver Issue</u></a></li>
<li><a href="https://driver-error.techidaily.com/solve-disappearing-optical-drives-on-win11/"><u>Solve Disappearing Optical Drives on Win11</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-enhancing-your-digital-presence-fb-video-creation-basics/"><u>[Updated] Enhancing Your Digital Presence  FB Video Creation Basics</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-powershell-access-control-settings/"><u>Optimizing PowerShell Access Control Settings</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-the-easiest-way-to-edit-avi-files-split-trim-and-cut-with-ease/"><u>Updated The Easiest Way to Edit AVI Files Split, Trim, and Cut with Ease</u></a></li>
<li><a href="https://driver-error.techidaily.com/for-a-chtmlity-subtractionedited-from-fill-in-the-following-questions-which-is-not-only-to-be-continued-relevant-parts-for-more-than-two-handcrafted/"><u>For a) C:‘.htmlity | [Subtraction(edited From: Fill in the Following Questions, Which Is Not only to Be Continued... (Relevant Parts for More than Two-Handcrafted.)</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-get-back-lost-photos-from-yuva-3-pro-by-fonelab-android-recover-photos/"><u>How to get back lost photos from Yuva 3 Pro.</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-guide-how-to-address-the-absent-coprocessor-driver-error-on-windows-11/"><u>Fix Guide: How to Address the Absent Coprocessor Driver Error on Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/reinstating-your-touchpad-driver-recovery-unveiled/"><u>Reinstating Your Touchpad - Driver Recovery Unveiled</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-windows-10s-best-15-capture-tools/"><u>[New] In 2024, Windows 10'S Best 15 Capture Tools</u></a></li>
<li><a href="https://extra-hints.techidaily.com/enhancing-iphone-shots-employing-leading-lines/"><u>Enhancing iPhone Shots  Employing Leading Lines</u></a></li>
<li><a href="https://driver-error.techidaily.com/tackled-device-control-crash/"><u>Tackled Device Control Crash</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-guide-to-transferring-audacity-projects-into-high-quality-mp3-audio/"><u>Updated Guide to Transferring Audacity Projects Into High-Quality MP3 Audio</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/overview-of-the-best-xiaomi-redmi-note-13-pro-5g-screen-mirroring-app-drfone-by-drfone-android/"><u>Overview of the Best Xiaomi Redmi Note 13 Pro 5G Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/enabling-hardware-detection-for-seagate-external/"><u>Enabling Hardware Detection for Seagate External</u></a></li>
<li><a href="https://driver-error.techidaily.com/no-more-struggle-graphic-setup-now-perfect/"><u>No More Struggle: Graphic Setup Now Perfect</u></a></li>
<li><a href="https://driver-error.techidaily.com/key-backlight-off-on-asus-device/"><u>Key Backlight OFF on ASUS Device</u></a></li>
<li><a href="https://driver-error.techidaily.com/irqlfixed-win11-os-blue-screen-issue/"><u>[IRQL_FIXED]: Win11 OS Blue Screen Issue</u></a></li>
<li><a href="https://driver-error.techidaily.com/navigating-high-disk-usage-in-task-manager/"><u>Navigating High Disk Usage in Task Manager</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-how-to-optimize-your-social-media-presence-post-facebook-change-for-2024/"><u>[New] How to Optimize Your Social Media Presence Post-Facebook Change for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/hp-envy-20-pc-series-how-to-fetch-and-install-latest-drivers-effortlessly/"><u>HP ENVY 20 PC Series - How to Fetch and Install Latest Drivers Effortlessly</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-charting-the-course-of-youtube-success-through-social-blade-analysis-for-2024/"><u>[New] Charting the Course of YouTube Success Through Social Blade Analysis for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/system-barred-from-using-win10s-graphics-hardware/"><u>System Barred From Using Win10's Graphics Hardware</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-social-sensation-strategies-crafting-fbs-topmusicvideos/"><u>[New] In 2024, Social Sensation Strategies - Crafting FB's #TopMusicVideos</u></a></li>
<li><a href="https://driver-error.techidaily.com/graphics-card-interrupt-handling-optimized/"><u>Graphics Card Interrupt Handling Optimized</u></a></li>
<li><a href="https://driver-error.techidaily.com/unresponsive-mouse-lurking-in-windows-settings/"><u>Unresponsive Mouse Lurking in Windows Settings</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-guide-to-fix-qualcomm-atheros-bluetooth-driver-issues-in-windows-10-os/"><u>Step-by-Step Guide to Fix Qualcomm Atheros Bluetooth Driver Issues in Windows 10 OS</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-a-comprehensive-guide-to-the-best-makeup-tutorials-on-youtube/"><u>[New] 2024 Approved  A Comprehensive Guide to the Best Makeup Tutorials on YouTube</u></a></li>
<li><a href="https://fake-location.techidaily.com/all-must-knows-to-use-fake-gps-go-location-spoofer-on-vivo-t2x-5g-drfone-by-drfone-virtual-android/"><u>All Must-Knows to Use Fake GPS GO Location Spoofer On Vivo T2x 5G | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/face-editing-battle-is-hero-series-better-than-the-cube-in-2024/"><u>Face-Editing Battle  Is Hero Series Better Than The Cube, In 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/solve-recurring-amd-glitches-rapidly/"><u>Solve Recurring AMD Glitches Rapidly</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-15-must-see-investment-channels-online/"><u>[New] 2024 Approved  15 Must-See Investment Channels Online</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-cut-trim-and-shine-top-free-online-video-editors-revealed/"><u>Updated 2024 Approved Cut, Trim, and Shine Top Free Online Video Editors Revealed</u></a></li>
<li><a href="https://driver-error.techidaily.com/driver-dilemma-solved-smooth-installation/"><u>Driver Dilemma Solved – Smooth Installation</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-the-radeon-wattman-defaults-crash-recovery-expert-solutions/"><u>Troubleshooting the 'Radeon WattMan Defaults Crash Recovery': Expert Solutions</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-incompatibility-alerts-unsupported-hard-devices-on-idt-software-platforms/"><u>Fix Incompatibility Alerts: Unsupported Hard Devices on IDT Software Platforms</u></a></li>
<li><a href="https://driver-error.techidaily.com/lenovos-blue-tooth-troubles-win11-remedied-strategies/"><u>Lenovo's Blue-Tooth Troubles, Win11 Remedied Strategies</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-in-2024-screen-recording-101-how-to-use-filmora-scrn-for-desktop-capture/"><u>Updated In 2024, Screen Recording 101 How to Use Filmora Scrn for Desktop Capture</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshoot-and-fix-missing-intel-cpu-coprocessor-drivers-on-windows-11-easily/"><u>Troubleshoot and Fix Missing Intel CPU Coprocessor Drivers on Windows 11 Easily</u></a></li>
<li><a href="https://driver-error.techidaily.com/addressing-windows-non-responsive-enter-issue/"><u>Addressing Windows Non-Responsive Enter Issue</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-mastering-media-migration-tiktok-directly-to-fb/"><u>[New] Mastering Media Migration  TikTok Directly to FB</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-vertical-video-victory-tips-for-seamless-social-media-sharing/"><u>2024 Approved Vertical Video Victory Tips for Seamless Social Media Sharing</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-sideways-videos-a-guide-to-adjusting-orientation-on-asus-pcs/"><u>Troubleshooting Sideways Videos: A Guide to Adjusting Orientation on ASUS PCs</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-your-qualcomm-bluetooth-driver-woes-in-windows-11-step-by-step-solutions/"><u>Solving Your Qualcomm Bluetooth Driver Woes in Windows 11 – Step-by-Step Solutions</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-the-seamless-swivel-rotating-your-media-masterpieces-on-social-sites/"><u>2024 Approved  The Seamless Swivel  Rotating Your Media Masterpieces on Social Sites</u></a></li>
<li><a href="https://driver-error.techidaily.com/quick-win-strategies-for-windows-ndis-issues/"><u>Quick-Win Strategies for Windows NDIS Issues</u></a></li>
<li><a href="https://driver-error.techidaily.com/a-excuse-me-if-you-guys-but-i-am-a-human-resources-manager-are-all-of-the-same-time-periods/"><u>A: Excuse Me if You Guys, but I Am a Human Resources Manager) Are All of the Same Time Periods</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-tips-for-recovering-from-default-radeon-wattman-setup-errors/"><u>Troubleshooting Tips for Recovering From Default Radeon Wattman Setup Errors</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-copyright-guide-for-instagram-music/"><u>In 2024, Copyright Guide for Instagram Music</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-mouse-and-window-lag-woes/"><u>Overcoming Mouse & Window Lag Woes</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-errors-in-the-configuration-segment-for-services/"><u>Resolving Errors in the Configuration Segment for Services</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/daily-dose-of-bengali-knowledge/"><u>Daily Dose of Bengali Knowledge</u></a></li>
</ul></div>
