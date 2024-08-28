---
title: Stopping Bluetooth From Autostart in Win11 OS
date: 2024-08-27T06:58:57.800Z
updated: 2024-08-28T06:58:57.800Z
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
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-clearing-up-audio-in-skype-conferences/"><u>[New] In 2024, Clearing Up Audio in Skype Conferences</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-instagram-harmony-understanding-rights-for-2024/"><u>[New] Instagram Harmony  Understanding Rights for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-perfect-your-hd-vids-on-android-with-these-10-players-for-2024/"><u>[New] Perfect Your HD Vids on Android With These 10 Players for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-cannot-install-drivers-no-intelr-adapters-are-present-in-this-computer/"><u>[Solved] Cannot Install Drivers. No Intel(R) Adapters Are Present in This Computer</u></a></li>
<li><a href="https://driver-error.techidaily.com/titled-system-recovery-after-software-installation-hurdles/"><u>[TITLED] System Recovery After Software Installation Hurdles</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-affordable-minecraft-video-graphics-for-2024/"><u>[Updated] Affordable Minecraft Video Graphics for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-bridging-gap-integrating-zoom-into-your-gmail-setup/"><u>[Updated] Bridging Gap  Integrating Zoom Into Your Gmail Setup</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-visual-tweets-the-panorama-of-threaded-video/"><u>2024 Approved  Visual Tweets  The Panorama of Threaded Video</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-facts-you-need-to-know-about-screen-mirroring-vivo-g2-drfone-by-drfone-android/"><u>3 Facts You Need to Know about Screen Mirroring Vivo G2 | Dr.fone</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/calmly-quieten-your-computers-audio-output/"><u>Calmly Quieten Your Computer's Audio Output</u></a></li>
<li><a href="https://games-able.techidaily.com/correcting-freezing-graphics-display-error-0x887a0006-fixes/"><u>Correcting Freezing Graphics Display - Error 0X887A0006 Fixes</u></a></li>
<li><a href="https://driver-error.techidaily.com/diagnosing-and-repairing-issues-with-hps-wireless-keyboards-a-comprehensive-guide/"><u>Diagnosing and Repairing Issues with HP's Wireless Keyboards: A Comprehensive Guide</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/direct-conversion-convert-and-upload-mp3-songs-on-youtube/"><u>Direct Conversion  Convert & Upload MP3 Songs on YouTube</u></a></li>
<li><a href="https://driver-error.techidaily.com/disabled-issue-resolved-ready-for-use/"><u>Disabled Issue Resolved: Ready for Use</u></a></li>
<li><a href="https://driver-error.techidaily.com/driver-start-up-problem-event-number-219/"><u>Driver Start-Up Problem - Event Number 219</u></a></li>
<li><a href="https://driver-error.techidaily.com/error-on-wudfrd-driver-initialization-id-219/"><u>Error on WudfRd Driver Initialization, ID 219</u></a></li>
<li><a href="https://win-blog.techidaily.com/expert-guide-why-isnt-my-amazon-prime-video-working-and-what-to-do/"><u>Expert Guide: Why Isn't My Amazon Prime Video Working & What To Do?</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixed-unsupported-intelamd-drivers-premiere-pro/"><u>Fixed: Unsupported Intel/AMD Drivers Premiere Pro</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-get-back-working-dolby-atmos-driver-for-windows-after-a-failed-update-resolved/"><u>How to Get Back Working Dolby Atmos® Driver for Windows After a Failed Update - Resolved!✔️</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-in-ar-games-on-vivo-s17t-drfone-by-drfone-virtual-android/"><u>How to Simulate GPS Movement in AR games On Vivo S17t? | Dr.fone</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-a-closer-look-at-youtubes-payment-system-and-its-potential/"><u>In 2024, A Closer Look at YouTube's Payment System and Its Potential</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-a-network-locked-realme-11-5g-phone-by-drfone-android/"><u>In 2024, How to Unlock a Network Locked Realme 11 5G Phone?</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/leading-cable-modemrouter-duos-of-the-year-a-2024-selection/"><u>Leading Cable Modem/Router Duos of the Year - A 2024 Selection</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-the-missing-coprocessor-driver-error-on-your-windows-10-machine-solutions-inside/"><u>Overcoming the Missing Coprocessor Driver Error on Your Windows 10 Machine - Solutions Inside!</u></a></li>
<li><a href="https://extra-resources.techidaily.com/post-a-highlight-from-the-latest-audio-show/"><u>Post a Highlight From the Latest Audio Show</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/quick-and-easy-guide-to-turn-videos-into-animated-gif-delights-for-2024/"><u>Quick & Easy Guide to Turn Videos Into Animated GIF Delights for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/remedying-inability-to-use-windows-enter-key/"><u>Remedying Inability to Use Windows Enter Key</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-issue-initialization-fails-due-to-battleye-driver-error-code-1450/"><u>Resolved Issue: Initialization Fails Due to BattlEye Driver Error Code 1450</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-non-functioning-qualcomm-atheros-bluetooth-drivers-in-windows-10-step-by-step-guide/"><u>Resolving Non-Functioning Qualcomm Atheros Bluetooth Drivers in Windows 10: Step by Step Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-the-problem-of-a-faulty-usb-device-not-detected-by-windows/"><u>Resolving the Problem of a Faulty USB Device Not Detected by Windows</u></a></li>
<li><a href="https://driver-error.techidaily.com/restoring-your-pcs-audio-system-after-installing-dynaudio-driver-for-dolby-atmos-fixed/"><u>Restoring Your PC’s Audio System After Installing Dynaudio Driver for Dolby Atmos®- Fixed! ✅</u></a></li>
<li><a href="https://driver-error.techidaily.com/revamp-your-hp-envy-20s-performance-with-latest-drivers-downloading-and-update-tutorial/"><u>Revamp Your HP Envy 20'S Performance with Latest Drivers - Downloading and Update Tutorial</u></a></li>
<li><a href="https://driver-error.techidaily.com/solve-your-hp-keyboard-woes-a-comprehensive-fix-for-common-wireless-issues/"><u>Solve Your HP Keyboard Woes - A Comprehensive Fix for Common Wireless Issues</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-touchpad-driver-not-working-on-windows-11/"><u>Solved Touchpad Driver Not Working on Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/tackling-unloading-of-enex-system-drivers-on-windows-11/"><u>Tackling Unloading of eNEX System Drivers on Windows 11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-importance-of-non-primary-footage-in-editing/"><u>The Importance of Non-Primary Footage in Editing</u></a></li>
<li><a href="https://fox-blue.techidaily.com/top-9-drone-video-editing-software-for-different-level-for-2024/"><u>Top 9 Drone Video Editing Software for Different Level for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-and-solving-windows-7-bsod-issue-error-code-0x0000007e/"><u>Troubleshooting and Solving Windows 7 BSOD Issue (Error Code: 0X0000007E)</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-steps-for-driver-load-problem-in-battleye-service-with-error-message-1450/"><u>Troubleshooting Steps for 'Driver Load Problem' In BattlEye Service with Error Message (1450)</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-steps-resolving-issues-when-your-final-usb-device-fails-and-windows-ignores-it/"><u>Troubleshooting Steps: Resolving Issues When Your Final USB Device Fails & Windows Ignores It</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-the-bsod-blue-screen-error-code-0x0000007e-in-windows-easy-fix/"><u>Troubleshooting the BSOD (Blue Screen) Error Code 0X0000007E in Windows Easy Fix</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-entering-safe-mode-and-deleting-problematic-graphics-drivers-on-windows-8/"><u>Troubleshooting: Entering Safe Mode & Deleting Problematic Graphics Drivers on Windows 8</u></a></li>
<li><a href="https://driver-error.techidaily.com/unexplored-reserve-of-system-resources/"><u>Unexplored Reserve of System Resources</u></a></li>
<li><a href="https://driver-error.techidaily.com/unidentified-discdvdcd-in-w10w11/"><u>Unidentified Disc/DVD/CD in W10/W11</u></a></li>
<li><a href="https://driver-error.techidaily.com/unlock-frozen-dell-mouse-on-win7/"><u>Unlock Frozen Dell Mouse on Win7</u></a></li>
<li><a href="https://driver-error.techidaily.com/unlock-the-secrets-of-solving-iphones-usb-connection-woes-using-effective-mtp-driver-techniques/"><u>Unlock the Secrets of Solving iPhone's USB Connection Woes Using Effective MTP Driver Techniques</u></a></li>
</ul></div>
