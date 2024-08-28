---
title: Preventing Bluetooth Auto-Turn On in WIN11
date: 2024-08-27T07:00:27.106Z
updated: 2024-08-28T07:00:27.106Z
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
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-maximize-impact-with-custom-icons-and-graphics-on-your-instagram-posts/"><u>[New] 2024 Approved  Maximize Impact with Custom Icons and Graphics on Your Instagram Posts</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-hardware-drivers-active/"><u>[Resolved] Hardware Drivers Active</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-cannot-install-drivers-no-intelr-adapters-are-present-in-this-computer/"><u>[Solved] Cannot Install Drivers. No Intel(R) Adapters Are Present in This Computer</u></a></li>
<li><a href="https://driver-error.techidaily.com/titled-system-recovery-after-software-installation-hurdles/"><u>[TITLED] System Recovery After Software Installation Hurdles</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-best-practices-for-secondary-footage-selection-and-use-for-2024/"><u>[Updated] Best Practices for Secondary Footage Selection and Use for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-elevate-chat-dynamics-pin-messages-with-confidence-in-discord/"><u>[Updated] Elevate Chat Dynamics  Pin Messages with Confidence in Discord</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-in-2024-cinematic-cadences-finding-film-friendly-sounds/"><u>[Updated] In 2024, Cinematic Cadences  Finding Film-Friendly Sounds</u></a></li>
<li><a href="https://android-location.techidaily.com/10-free-location-spoofers-to-fake-gps-location-on-your-oppo-find-x6-pro-drfone-by-drfone-virtual/"><u>10 Free Location Spoofers to Fake GPS Location on your Oppo Find X6 Pro | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-budget-calculation-for-shooting-a-music-video/"><u>2024 Approved  Budget Calculation for Shooting a Music Video</u></a></li>
<li><a href="https://extra-tips.techidaily.com/boost-your-media-creation-skills-a-detailed-walkthrough-of-movie-maker-on-windows-8/"><u>Boost Your Media Creation Skills  A Detailed Walkthrough of Movie Maker on Windows 8</u></a></li>
<li><a href="https://driver-error.techidaily.com/diagnosing-and-repairing-issues-with-hps-wireless-keyboards-a-comprehensive-guide/"><u>Diagnosing and Repairing Issues with HP's Wireless Keyboards: A Comprehensive Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/dial-back-disappearance-of-your-touchpads-driver/"><u>Dial Back Disappearance of Your Touchpad's Driver</u></a></li>
<li><a href="https://driver-error.techidaily.com/disabled-issue-resolved-ready-for-use/"><u>Disabled Issue Resolved: Ready for Use</u></a></li>
<li><a href="https://driver-error.techidaily.com/driver-start-up-problem-event-number-219/"><u>Driver Start-Up Problem - Event Number 219</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-productivity-top-30-mouse-control-wizards/"><u>Elevate Productivity: Top 30 Mouse Control Wizards</u></a></li>
<li><a href="https://driver-error.techidaily.com/error-on-wudfrd-driver-initialization-id-219/"><u>Error on WudfRd Driver Initialization, ID 219</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixed-unsupported-intelamd-drivers-premiere-pro/"><u>Fixed: Unsupported Intel/AMD Drivers Premiere Pro</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixes-and-solutions-how-to-troubleshoot-an-hp-wireless-keyboard-that-wont-respond/"><u>Fixes & Solutions: How to Troubleshoot an HP Wireless Keyboard That Won't Respond</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-bypass-iphone-13-passcode-easily-video-inside-drfone-by-drfone-ios/"><u>How to Bypass iPhone 13 Passcode Easily Video Inside | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-get-back-working-dolby-atmos-driver-for-windows-after-a-failed-update-resolved/"><u>How to Get Back Working Dolby Atmos® Driver for Windows After a Failed Update - Resolved!✔️</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-earning-big-from-youtube-shorts-key-requirements-and-profit-prospects/"><u>In 2024, Earning Big From YouTube Shorts  Key Requirements and Profit Prospects</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-can-we-bypass-xiaomi-13t-frp-by-drfone-android/"><u>In 2024, How Can We Bypass Xiaomi 13T FRP?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-card-on-apple-iphone-xr-online-without-jailbreak-by-drfone-ios/"><u>In 2024, How to Unlock SIM Card on Apple iPhone XR online without jailbreak</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-path-to-stardom-logo-creation-tips-for-podcasters/"><u>In 2024, The Path to Stardom  Logo Creation Tips for Podcasters</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-the-missing-coprocessor-driver-error-on-your-windows-10-machine-solutions-inside/"><u>Overcoming the Missing Coprocessor Driver Error on Your Windows 10 Machine - Solutions Inside!</u></a></li>
<li><a href="https://driver-error.techidaily.com/pci-controller-woes-solved-in-windows-os/"><u>PCI Controller Woes Solved in Windows OS</u></a></li>
<li><a href="https://driver-error.techidaily.com/remedying-inability-to-use-windows-enter-key/"><u>Remedying Inability to Use Windows Enter Key</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-issue-initialization-fails-due-to-battleye-driver-error-code-1450/"><u>Resolved Issue: Initialization Fails Due to BattlEye Driver Error Code 1450</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-non-functioning-qualcomm-atheros-bluetooth-drivers-in-windows-10-step-by-step-guide/"><u>Resolving Non-Functioning Qualcomm Atheros Bluetooth Drivers in Windows 10: Step by Step Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-the-problem-of-a-faulty-usb-device-not-detected-by-windows/"><u>Resolving the Problem of a Faulty USB Device Not Detected by Windows</u></a></li>
<li><a href="https://driver-error.techidaily.com/restoring-your-pcs-audio-system-after-installing-dynaudio-driver-for-dolby-atmos-fixed/"><u>Restoring Your PC’s Audio System After Installing Dynaudio Driver for Dolby Atmos®- Fixed! ✅</u></a></li>
<li><a href="https://driver-error.techidaily.com/revamp-your-hp-envy-20s-performance-with-latest-drivers-downloading-and-update-tutorial/"><u>Revamp Your HP Envy 20'S Performance with Latest Drivers - Downloading and Update Tutorial</u></a></li>
<li><a href="https://driver-error.techidaily.com/solve-your-hp-keyboard-woes-a-comprehensive-fix-for-common-wireless-issues/"><u>Solve Your HP Keyboard Woes - A Comprehensive Fix for Common Wireless Issues</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-touchpad-driver-not-working-on-windows-11/"><u>Solved Touchpad Driver Not Working on Windows 11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/speedy-file-assessment-on-windows-pcs/"><u>Speedy File Assessment on Windows PCs</u></a></li>
<li><a href="https://tech-revival.techidaily.com/step-by-step-fixes-for-windows-update-error-0x80070422-in-windows-10-operating-system/"><u>Step-by-Step Fixes for Windows Update Error 0X80070422 in Windows 10 Operating System</u></a></li>
<li><a href="https://driver-error.techidaily.com/tackling-unloading-of-enex-system-drivers-on-windows-11/"><u>Tackling Unloading of eNEX System Drivers on Windows 11</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/to-embrace-or-not-the-itop-screen-recorder-dilemran-for-2024/"><u>To Embrace or Not  The ITop Screen Recorder Dilemran for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-and-resolving-windows-11s-missing-coprocessor-drivers-easy-fixes-unveiled/"><u>Troubleshooting and Resolving Windows 11'S Missing Coprocessor Drivers: Easy Fixes Unveiled</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-and-solving-windows-7-bsod-issue-error-code-0x0000007e/"><u>Troubleshooting and Solving Windows 7 BSOD Issue (Error Code: 0X0000007E)</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-steps-for-driver-load-problem-in-battleye-service-with-error-message-1450/"><u>Troubleshooting Steps for 'Driver Load Problem' In BattlEye Service with Error Message (1450)</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-steps-resolving-issues-when-your-final-usb-device-fails-and-windows-ignores-it/"><u>Troubleshooting Steps: Resolving Issues When Your Final USB Device Fails & Windows Ignores It</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-the-bsod-blue-screen-error-code-0x0000007e-in-windows-easy-fix/"><u>Troubleshooting the BSOD (Blue Screen) Error Code 0X0000007E in Windows Easy Fix</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-entering-safe-mode-and-deleting-problematic-graphics-drivers-on-windows-8/"><u>Troubleshooting: Entering Safe Mode & Deleting Problematic Graphics Drivers on Windows 8</u></a></li>
<li><a href="https://driver-error.techidaily.com/unexplored-reserve-of-system-resources/"><u>Unexplored Reserve of System Resources</u></a></li>
<li><a href="https://driver-error.techidaily.com/unidentified-discdvdcd-in-w10w11/"><u>Unidentified Disc/DVD/CD in W10/W11</u></a></li>
<li><a href="https://driver-error.techidaily.com/unlock-frozen-dell-mouse-on-win7/"><u>Unlock Frozen Dell Mouse on Win7</u></a></li>
<li><a href="https://driver-error.techidaily.com/unlock-the-secrets-of-solving-iphones-usb-connection-woes-using-effective-mtp-driver-techniques/"><u>Unlock the Secrets of Solving iPhone's USB Connection Woes Using Effective MTP Driver Techniques</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-legendaries-are-in-pokemon-platinum-on-motorola-g24-power-drfone-by-drfone-virtual-android/"><u>What Legendaries Are In Pokemon Platinum On Motorola G24 Power? | Dr.fone</u></a></li>
</ul></div>
