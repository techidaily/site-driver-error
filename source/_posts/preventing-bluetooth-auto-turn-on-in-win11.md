---
title: Preventing Bluetooth Auto-Turn On in WIN11
date: 2024-07-15T06:55:05.060Z
updated: 2024-07-16T06:55:05.060Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Preventing Bluetooth Auto-Turn On in WIN11
excerpt: This Article Describes Preventing Bluetooth Auto-Turn On in WIN11
thumbnail: https://thmb.techidaily.com/154ba651f58f7b61c6d13ed51a3e08aab825faff32ad0111bfbaa0c8293dac8c.jpg
---

## Preventing Bluetooth Auto-Turn On in WIN11

Windows 10 users have been complaining that they are**unable to turn off**the Bluetooth connection even when they don’t want to use their Bluetooth devices, for instance, when they are in a neighborhood where there are so many Bluetooth devices detected. They cannot see the toggle switch (circled out in the screenshot) in Bluetooth device setting.

![](https://images.drivereasy.com/wp-content/uploads/2016/11/manage-bluetooth-devices.jpg)

The reason why this is happening is that Microsoft seems to have an odd logic. It will recognize laptops with battery on is the mobile devices, thus with the Bluetooth device toggle available and easy to access. But if you are with a desktop, or sometimes, an all-in-one, chances are Windows 10 will not see your computer as a mobile device, thus it will not let you have access to the Bluetooth devices management panel. Luckily, this is not a difficult question to solve, not at all. Follow the options below to fix your problem fast and easily ![**Option 1: Disable Bluetooth device driver**](https://boody-eco-wear.pxf.io/qyo4oo) [**Option 2: Update Bluetooth device driver**](https://propmoneyinc.pxf.io/q4jzdy) [**Option 3: Modify Registry settings**](https://united.elfm.net/zqobdx)   **Option 1: Disable Bluetooth device driver** 1) Open**Device Manager** by pressing**Windows key**and**R**at the same time. Then type in**devmgmt.msc** and hit**Enter**.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/11/devmgmt-msc.png)

 2) In**Device Manager** , expand category Bluetooth, then right click the Bluetooth device that you want to temporarily disconnect and choose**Disable** .

![](https://images.drivereasy.com/wp-content/uploads/2016/11/disable-bluetooth-device-manager.jpg)

 If you cannot see all of your Bluetooth devices, please click the**View** button and then select**Show hidden devices** .

![](https://images.drivereasy.com/wp-content/uploads/2016/11/show-hidden-devices.png)

 Please note that the name of your Bluetooth device could be different from mine, which is very natural and normal. If you have multiple Bluetooth devices, you might see other options here. The procedure is the same, just right click them and**Disable** them.   **Option 2: Update Bluetooth device driver** If the steps above don’t resolve your Bluetooth problem in Windows 10, it may be caused by a device driver.  You can automatically update all your device drivers to the latest correct version with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .  Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version it takes just 2 clicks (and you get full support and a 30-day money back guarantee): 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy. 2) Run Driver Easy and click the **Scan Now**  button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/img_594b60655cf90.png)

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) Click the **Update** button next to the flagged Bluetooth device to automatically download and install the correct version of that driver (you can do this with the FREE version). Or click **Update All** to automatically download and install the correct version of **_all_**  the drivers that are missing or out of date on your system (this requires the [**Pro version**](https://tools.techidaily.com/drivereasy/download/)  – you’ll be prompted to upgrade when you click Update All). ![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58e613efeb2c3.jpg)   **Option 3: Modify Registry settings** **Note**: In this option, we will be making some changes to the Registry. Before doing that, it is very important for you to [**backup**](https://tools.techidaily.com/drivereasy/download/) the registry first, just in case any unwanted error happens. 1) Type**regedit**in the search box and then choose**regedit Run command** from the list of choice.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/11/regedit-run-command.png)

When prompted for administrator permission, just click**Yes**to continue.

<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/11/uac.png)

2) Follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\ActionCenter\\Quick Actions\\All\\SystemSettings\_Device\_BluetoothQuickAction**.

![](https://images.drivereasy.com/wp-content/uploads/2016/11/hkey_local_machinesoftwaremicrosoftwindowscurrentversionactioncenterquick-actionsallsystemsettings_device_bluetoothquickaction.png)

3) On the right pane, locate and right click the file with the name **Type**and choose**Modify**. ![](https://images.drivereasy.com/wp-content/uploads/2016/11/modify-value.png) 4) Then change the**Value data**from 0 to**1**. Then hit**OK**to save and exit.

<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://driver-error.techidaily.com/step-by-step-solutions-to-prevent-videos-from-displaying-upside-down-on-an-asus-notebook/"><u>Step-by-Step Solutions to Prevent Videos From Displaying Upside Down on an ASUS Notebook</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-get-your-qualcomm-atheros-devices-bluetooth-working-perfectly-on-windows-jndz-eleven/"><u>How to Get Your Qualcomm Atheros Device's Bluetooth Working Perfectly on Windows ˈ|jɪndz Eleven</u></a></li>
<li><a href="https://some-guidance.techidaily.com/transforming-simple-videos-text-addition-in-windows-10s-photos-software-for-2024/"><u>Transforming Simple Videos  Text Addition in Windows 10'S Photos Software for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-erratic-trackpad-behavior-in-dell-windows-7/"><u>Fix Erratic Trackpad Behavior in Dell-Windows 7</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolve-nonworking-right-click-on-windows-11-touchpad-panel/"><u>Resolve Nonworking Right Click on Windows 11 Touchpad Panel</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-transform-your-social-feed-to-full-screen/"><u>[New] In 2024, Transform Your Social Feed to Full Screen</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-get-your-qualcomm-atheros-bluetooth-working-again-on-a-windows-10-pc/"><u>How to Get Your Qualcomm Atheros Bluetooth Working Again on a Windows 10 PC</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-pro-grade-animation-top-software-picks-for-mac-and-windows-users/"><u>New In 2024, Pro-Grade Animation Top Software Picks for Mac and Windows Users</u></a></li>
<li><a href="https://driver-error.techidaily.com/mastering-directx-9-startup-in-minimal-steps/"><u>Mastering DirectX 9 Startup in Minimal Steps</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-download-andupdate-drivers-for-hp-envy-20-pc-series/"><u>How to Download &Update Drivers for HP ENVY 20 PC Series</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-first-timer-accessories-transform-your-gopro-experience/"><u>2024 Approved  First-Timer Accessories - Transform Your GoPro Experience</u></a></li>
<li><a href="https://driver-error.techidaily.com/discovering-name-for-glplusicd-driver/"><u>Discovering Name for GL+ICD Driver</u></a></li>
<li><a href="https://driver-error.techidaily.com/end-of-window-lags-and-pauses/"><u>End of Window Lags & Pauses</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-the-ultimate-pathway-for-iphone-speech-capture-and-documentation/"><u>New 2024 Approved The Ultimate Pathway for iPhone Speech Capture and Documentation</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-shooting-hdr-on-iphone-a-comprehensive-guide/"><u>[Updated] Shooting HDR on iPhone  A Comprehensive Guide</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-check-if-your-oppo-is-unlocked-by-drfone-android/"><u>How To Check if Your Oppo Is Unlocked</u></a></li>
<li><a href="https://driver-error.techidaily.com/making-logitech-receptor-discoverable-on-pcs/"><u>Making Logitech Receptor Discoverable on PCs</u></a></li>
<li><a href="https://driver-error.techidaily.com/careless-install-of-gpu-driver/"><u>Careless Install of GPU Driver?</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-the-ultimate-guide-to-video-editing-on-your-smartphone/"><u>New The Ultimate Guide to Video Editing on Your Smartphone</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-battleye-service-unable-to-initialize-due-to-error-1450-a-comprehensive-guide/"><u>Fixing 'BattlEye Service Unable To Initialize' Due To Error 1450 - A Comprehensive Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/guide-installing-necessary-drivers-for-your-windows-pc-windows-1187/"><u>Guide: Installing Necessary Drivers for Your Windows PC [WINDOWS 11/8/7]</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-2024-approved-top-video-editing-software-with-ai-reframing/"><u>Updated 2024 Approved Top Video Editing Software with AI Reframing</u></a></li>
<li><a href="https://animation-videos.techidaily.com/animated-business-logos-and-tools-to-create-for-2024/"><u>Animated Business Logos and Tools to Create for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/the-evolution-and-functionality-of-usb-composite-devices-a-comprehensive-guide/"><u>The Evolution and Functionality of USB Composite Devices: A Comprehensive Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-seagate-hdd-visibility-issue-in-win11/"><u>Solving Seagate HDD Visibility Issue in Win11</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721102843679-windows-11-and-qualcomm-atheros-bluetooth-woes-heres-your-ultimate-fix/"><u>Windows 11 and Qualcomm Atheros Bluetooth Woes? Here's Your Ultimate Fix!</u></a></li>
<li><a href="https://driver-error.techidaily.com/system-and-compressed-memory-high-disk-usage-on-windows-10-solved/"><u>System and Compressed Memory High Disk Usage on Windows 10 [Solved]</u></a></li>
<li><a href="https://driver-error.techidaily.com/overhauling-intel-mmc-faults/"><u>Overhauling Intel MMC Faults</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-easy-way-to-modify-iphone-photo-dimensions/"><u>2024 Approved  The Easy Way to Modify iPhone Photo Dimensions</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-restoring-functionality-when-your-pc-lacks-a-coprocessor-driver-in-windows-nt/"><u>Solved! Restoring Functionality When Your PC Lacks a Coprocessor Driver in Windows nT</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-guide-to-installing-missing-device-drivers-in-windows-operating-systems/"><u>Step-by-Step Guide to Installing Missing Device Drivers in Windows Operating Systems</u></a></li>
<li><a href="https://driver-error.techidaily.com/balanced-hdd-control-mechanism/"><u>Balanced HDD Control Mechanism</u></a></li>
<li><a href="https://driver-error.techidaily.com/bluetoothusb-headset-not-recognized-windows-10-guide-to-solutions/"><u>Bluetooth/USB Headset Not Recognized: Windows 10 Guide to Solutions</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-device-hubs-error-48/"><u>[SOLVED] Device Hub's Error 48</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-guide-restoring-bluetooth-functionality-for-qualcomm-atheros-on-windows-10/"><u>Troubleshooting Guide: Restoring Bluetooth Functionality for Qualcomm Atheros on Windows 10</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/quick-fixes-addressing-top-youtube-short-challenges/"><u>Quick Fixes  Addressing Top YouTube Short Challenges</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-optimizing-viewing-distance-youtube-tips/"><u>[Updated] 2024 Approved  Optimizing Viewing Distance  YouTube Tips</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-11-free-apps-to-check-imei-on-nokia-c300-phones-by-drfone-android/"><u>In 2024, Top 11 Free Apps to Check IMEI on Nokia C300 Phones</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-guide-booting-windows-8-into-safe-mode-and-removing-your-graphics-drivers/"><u>Step-by-Step Guide: Booting Windows 8 Into Safe Mode & Removing Your Graphics Drivers</u></a></li>
<li><a href="https://driver-install.techidaily.com/intuitive-driver-upgrades-for-z50-70/"><u>Intuitive Driver Upgrades for Z50-70</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-navigating-auto-captioned-content-in-social-media-visuals/"><u>[Updated] Navigating Auto-Captioned Content in Social Media Visuals</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-mastering-instagram-success-harness-the-power-of-ig-data/"><u>2024 Approved  Mastering Instagram Success  Harness the Power of IG Data</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-unable-to-connect-to-the-synaptics-pointing-device-driver/"><u>[Solved] Unable to Connect to the Synaptics Pointing Device Driver</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-guide-to-saving-games-on-windows-10-pro-for-2024/"><u>[New] Guide to Saving Games on Windows 10 Pro for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-data-acquisition-issue-in-windows-os/"><u>Resolving Data Acquisition Issue in Windows OS</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-invisible-cddvd-on-windows-11/"><u>Resolving Invisible CD/DVD on Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/simple-fixes-for-itbm-driver-not-found-errors-on-your-computer/"><u>Simple Fixes for ITBM Driver Not Found Errors on Your Computer</u></a></li>
</ul></div>
