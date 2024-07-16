---
title: Stopping Bluetooth From Autostart in Win11 OS
date: 2024-07-15T06:55:40.445Z
updated: 2024-07-16T06:55:40.445Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Stopping Bluetooth From Autostart in Win11 OS
excerpt: This Article Describes Stopping Bluetooth From Autostart in Win11 OS
thumbnail: https://thmb.techidaily.com/5e4f2e08bc06e83ddb45587d928cf61d9245bd50e484b6c6cc6059c7ac856aae.jpg
---

## Stopping Bluetooth From Autostart in Win11 OS

Windows 10 users have been complaining that they are**unable to turn off**the Bluetooth connection even when they don’t want to use their Bluetooth devices, for instance, when they are in a neighborhood where there are so many Bluetooth devices detected. They cannot see the toggle switch (circled out in the screenshot) in Bluetooth device setting.

![](https://images.drivereasy.com/wp-content/uploads/2016/11/manage-bluetooth-devices.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
The reason why this is happening is that Microsoft seems to have an odd logic. It will recognize laptops with battery on is the mobile devices, thus with the Bluetooth device toggle available and easy to access. But if you are with a desktop, or sometimes, an all-in-one, chances are Windows 10 will not see your computer as a mobile device, thus it will not let you have access to the Bluetooth devices management panel. Luckily, this is not a difficult question to solve, not at all. Follow the options below to fix your problem fast and easily ![**Option 1: Disable Bluetooth device driver**](https://boody-eco-wear.pxf.io/qyo4oo) [**Option 2: Update Bluetooth device driver**](https://propmoneyinc.pxf.io/q4jzdy) [**Option 3: Modify Registry settings**](https://united.elfm.net/zqobdx)   **Option 1: Disable Bluetooth device driver** 1) Open**Device Manager** by pressing**Windows key**and**R**at the same time. Then type in**devmgmt.msc** and hit**Enter**.

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/11/devmgmt-msc.png)

 2) In**Device Manager** , expand category Bluetooth, then right click the Bluetooth device that you want to temporarily disconnect and choose**Disable** .

![](https://images.drivereasy.com/wp-content/uploads/2016/11/disable-bluetooth-device-manager.jpg)

 If you cannot see all of your Bluetooth devices, please click the**View** button and then select**Show hidden devices** .

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/11/show-hidden-devices.png)

 Please note that the name of your Bluetooth device could be different from mine, which is very natural and normal. If you have multiple Bluetooth devices, you might see other options here. The procedure is the same, just right click them and**Disable** them.   **Option 2: Update Bluetooth device driver** If the steps above don’t resolve your Bluetooth problem in Windows 10, it may be caused by a device driver.  You can automatically update all your device drivers to the latest correct version with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .  Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version it takes just 2 clicks (and you get full support and a 30-day money back guarantee): 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy. 2) Run Driver Easy and click the **Scan Now**  button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/img_594b60655cf90.png)

3) Click the **Update** button next to the flagged Bluetooth device to automatically download and install the correct version of that driver (you can do this with the FREE version). Or click **Update All** to automatically download and install the correct version of **_all_**  the drivers that are missing or out of date on your system (this requires the [**Pro version**](https://tools.techidaily.com/drivereasy/download/)  – you’ll be prompted to upgrade when you click Update All). ![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58e613efeb2c3.jpg)   **Option 3: Modify Registry settings** **Note**: In this option, we will be making some changes to the Registry. Before doing that, it is very important for you to [**backup**](https://tools.techidaily.com/drivereasy/download/) the registry first, just in case any unwanted error happens. 1) Type**regedit**in the search box and then choose**regedit Run command** from the list of choice.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/11/regedit-run-command.png)

When prompted for administrator permission, just click**Yes**to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/11/uac.png)

2) Follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\ActionCenter\\Quick Actions\\All\\SystemSettings\_Device\_BluetoothQuickAction**.

![](https://images.drivereasy.com/wp-content/uploads/2016/11/hkey_local_machinesoftwaremicrosoftwindowscurrentversionactioncenterquick-actionsallsystemsettings_device_bluetoothquickaction.png)

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
3) On the right pane, locate and right click the file with the name **Type**and choose**Modify**. ![](https://images.drivereasy.com/wp-content/uploads/2016/11/modify-value.png) 4) Then change the**Value data**from 0 to**1**. Then hit**OK**to save and exit.

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
<li><a href="https://extra-support.techidaily.com/new-lg-360-degree-headset-review-next-gen-immersion/"><u>[New] LG 360-Degree Headset Review - Next-Gen Immersion</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-guide-resolving-driver-load-failure-in-battleye-services-error-code-1450/"><u>Troubleshooting Guide: Resolving 'Driver Load Failure' In BattlEye Services (Error Code 1450)</u></a></li>
<li><a href="https://driver-error.techidaily.com/logitech-brio-webcam-not-detected-after-windows-11-creators-update-solved/"><u>Logitech Brio Webcam Not Detected After Windows 11 Creators Update [Solved]</u></a></li>
<li><a href="https://driver-error.techidaily.com/unveiling-the-secret-to-flawless-elan-pad-on-win11/"><u>Unveiling the Secret to Flawless Elan Pad on Win11</u></a></li>
<li><a href="https://driver-error.techidaily.com/initiating-the-operation-of-non-loading-enex-drivers-in-win11/"><u>Initiating the Operation of Non-Loading eNEX Drivers in Win11</u></a></li>
<li><a href="https://driver-error.techidaily.com/a-comprehensive-solution-to-fix-uninstalled-drivers-on-your-windows-11-8-or-7-pc/"><u>A Comprehensive Solution to Fix Uninstalled Drivers on Your Windows 11, 8 or ^7 PC</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-top-vr-game-creators-to-watch-for-2024/"><u>[New] Top VR Game Creators To Watch for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-fixing-missing-driver-installations-on-windows-1087-devices/"><u>Solved: Fixing Missing Driver Installations on Windows 10/8/7 Devices</u></a></li>
<li><a href="https://driver-error.techidaily.com/visualizing-ms-bda-in-graphics-context/"><u>Visualizing MS BDA in Graphics Context</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-inventory-guide-to-photographic-and-videography-units/"><u>[New] Inventory Guide to Photographic and Videography Units</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-repeated-uninstalls-of-nvidia-software/"><u>Solving Repeated Uninstalls of Nvidia Software</u></a></li>
<li><a href="https://driver-error.techidaily.com/graphics-decipherment-microsofts-ms-bda/"><u>Graphics Decipherment: Microsoft's MS BDA</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-chat-enhancement-course-turning-your-graphics-into-social-media-stickers/"><u>[Updated] Chat Enhancement Course  Turning Your Graphics Into Social Media Stickers</u></a></li>
<li><a href="https://driver-error.techidaily.com/unresolved-ax201-intel-wi-fi-not-operating/"><u>Unresolved: Ax201 Intel Wi-Fi Not Operating</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-the-vertical-display-problem-correcting-upward-facing-videos-on-your-asus-notebook/"><u>Resolving the Vertical Display Problem: Correcting Upward-Facing Videos on Your ASUS Notebook</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-in-2024-subtitled-out-of-a-zip-how-to-convert-files/"><u>[New] In 2024, Subtitled Out of a Zip! How To Convert Files</u></a></li>
<li><a href="https://driver-error.techidaily.com/bring-forth-your-absentee-seagate-hard-drive-on-w10/"><u>Bring Forth Your Absentee Seagate Hard Drive on W10</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-the-snapshot-solution-how-to-swiftly-switch-your-gif-for-a-sticker/"><u>[Updated] The Snapshot Solution  How to Swiftly Switch Your GIF for a Sticker</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-graphics-card-hurdles-fixing-code-43-errors-in-nvidia-geforce-gtx-950-under-windows-10/"><u>Overcoming Graphics Card Hurdles: Fixing Code 43 Errors in NVIDIA GeForce GTX 950 Under Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/tweak-dell-touchpad-for-win7-stability/"><u>Tweak Dell TouchPad for Win7 Stability</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-the-innovators-playbook-recording-shows-in-the-cloud/"><u>[New] 2024 Approved  The Innovator’s Playbook  Recording Shows in the Cloud</u></a></li>
<li><a href="https://driver-error.techidaily.com/hd-driver-harmony-unlocked-on-win11/"><u>HD Driver Harmony Unlocked on Win11</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-step-by-step-to-reel-success-on-instagram-for-2024/"><u>[New] Step-by-Step to Reel Success on Instagram for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-10-pro-ways-to-upgrade-your-twitch-broadcast-experience-for-2024/"><u>[Updated] 10 Pro Ways to Upgrade Your Twitch Broadcast Experience for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-overcome-usb-install-failures-due-to-access-denied-errors/"><u>How to Overcome USB Install Failures Due to Access Denied Errors</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/terminology-trek-through-the-virtual-landscape/"><u>Terminology Trek Through the Virtual Landscape</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-compatibility-with-samsungs-mobile-os/"><u>Windows Compatibility with Samsung's Mobile OS</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-looking-for-free-tools-to-create-radial-blur-images-online-read-our-full-guide-to-learn-about-the-6-best-programs-to-add-this-effect-to-your-picture/"><u>In 2024, Looking for Free Tools to Create Radial Blur Images Online? Read Our Full Guide to Learn About the 6 Best Programs to Add This Effect to Your Pictures</u></a></li>
<li><a href="https://driver-error.techidaily.com/bluetooth-troubleshooting-lenovo-plus-windows-11-success/"><u>Bluetooth Troubleshooting: Lenovo + Windows 11 Success</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixed-sm-bus-control-improvements-for-win11/"><u>[FIXED]: SM Bus Control Improvements for Win11</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-troubleshooting-steps-for-windows-10-coprocessor-driver-not-found-errors/"><u>Solved: Troubleshooting Steps for Windows 10 Coprocessor Driver Not Found Errors</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-how-to-improve-resilience-against-photos-app-issues-in-windows-11/"><u>In 2024, How to Improve Resilience Against Photos App Issues in Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/service-installation-correction-on-inf-section/"><u>Service Installation Correction on INF Section</u></a></li>
<li><a href="https://driver-error.techidaily.com/automobile-rejected-by-tech-gear/"><u>Automobile Rejected by Tech Gear</u></a></li>
<li><a href="https://driver-error.techidaily.com/remedy-driver-conflict-on-xps-13-notebook/"><u>Remedy Driver Conflict on XPS 13 Notebook</u></a></li>
<li><a href="https://driver-error.techidaily.com/understanding-the-usb-composite-device-a-guide-to-legacy-usb-systems/"><u>Understanding the USB Composite Device: A Guide to Legacy USB Systems</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-guide-for-fixing-failed-to-initialize-battleye-with-driver-error-145/"><u>Troubleshooting Guide for Fixing 'Failed to Initialize BattlEye' With Driver Error 145^</u></a></li>
<li><a href="https://driver-error.techidaily.com/atariousness-and-listeria-13980-meters-pertains-more-than/"><u>Atariousness and Listeria (13980 Meters Pertains More Than</u></a></li>
<li><a href="https://driver-error.techidaily.com/quick-fix-how-to-solve-your-slow-nvidia-games-expert-tips-inside/"><u>[Quick Fix] How to Solve Your Slow Nvidia Games – Expert Tips Inside</u></a></li>
<li><a href="https://driver-error.techidaily.com/deciphering-signal-flux-error-codes-e-52/"><u>Deciphering Signal Flux: Error Codes E-52</u></a></li>
<li><a href="https://driver-error.techidaily.com/address-udma-driver-failure/"><u>Address UDMA Driver Failure</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721102124391-run-a-system-file-checker-scan-to-verify-and-repair-corrupted-files/"><u>Run a System File Checker Scan to Verify and Repair Corrupted Files</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-steps-to-retrieve-and-install-device-drivers-on-windows-10-8-and-7-systems/"><u>Resolved! Steps to Retrieve and Install Device Drivers on Windows 10, 8 & 7 Systems</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-teach-you-to-transfer-files-from-infinix-smart-8-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways To Teach You To Transfer Files from Infinix Smart 8 to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/improve-mouse-functioning-on-dell-win7-platform/"><u>Improve Mouse Functioning on Dell, Win7 Platform</u></a></li>
<li><a href="https://driver-error.techidaily.com/unraveling-the-mystery-of-vintage-usb-composite-hardware-for-todays-tech-enthusiasts/"><u>Unraveling the Mystery of Vintage USB Composite Hardware for Today's Tech Enthusiasts</u></a></li>
<li><a href="https://driver-error.techidaily.com/rejuvenate-faulty-dell-touch-pad-win7/"><u>Rejuvenate Faulty Dell Touch Pad Win7</u></a></li>
</ul></div>
