---
title: Solving Bluetooth Auto-Enable on Win11
date: 2024-12-30T17:38:00.652Z
updated: 2025-01-02T22:53:14.139Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Solving Bluetooth Auto-Enable on Win11
excerpt: This Article Describes Solving Bluetooth Auto-Enable on Win11
thumbnail: https://thmb.techidaily.com/b7ec02702d51d57959e5bd1248adaf8d9c4e1536be03bd52fccab5d6aa482430.jpg
---

## Solving Bluetooth Auto-Enable on Win11

Windows 10 users have been complaining that they are**unable to turn off**the Bluetooth connection even when they don’t want to use their Bluetooth devices, for instance, when they are in a neighborhood where there are so many Bluetooth devices detected. They cannot see the toggle switch (circled out in the screenshot) in Bluetooth device setting.

![](https://images.drivereasy.com/wp-content/uploads/2016/11/manage-bluetooth-devices.jpg)

The reason why this is happening is that Microsoft seems to have an odd logic. It will recognize laptops with battery on is the mobile devices, thus with the Bluetooth device toggle available and easy to access. But if you are with a desktop, or sometimes, an all-in-one, chances are Windows 10 will not see your computer as a mobile device, thus it will not let you have access to the Bluetooth devices management panel. Luckily, this is not a difficult question to solve, not at all. Follow the options below to fix your problem fast and easily ![**Option 1: Disable Bluetooth device driver**](https://boody-eco-wear.pxf.io/qyo4oo) [**Option 2: Update Bluetooth device driver**](https://propmoneyinc.pxf.io/q4jzdy) [**Option 3: Modify Registry settings**](https://united.elfm.net/zqobdx)   **Option 1: Disable Bluetooth device driver** 1) Open**Device Manager** by pressing**Windows key**and**R**at the same time. Then type in**devmgmt.msc** and hit**Enter**.

![](https://images.drivereasy.com/wp-content/uploads/2016/11/devmgmt-msc.png)

 2) In**Device Manager** , expand category Bluetooth, then right click the Bluetooth device that you want to temporarily disconnect and choose**Disable** .

![](https://images.drivereasy.com/wp-content/uploads/2016/11/disable-bluetooth-device-manager.jpg)

 If you cannot see all of your Bluetooth devices, please click the**View** button and then select**Show hidden devices** .

![](https://images.drivereasy.com/wp-content/uploads/2016/11/show-hidden-devices.png)

 Please note that the name of your Bluetooth device could be different from mine, which is very natural and normal. If you have multiple Bluetooth devices, you might see other options here. The procedure is the same, just right click them and**Disable** them.   **Option 2: Update Bluetooth device driver** If the steps above don’t resolve your Bluetooth problem in Windows 10, it may be caused by a device driver.  You can automatically update all your device drivers to the latest correct version with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .  Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version it takes just 2 clicks (and you get full support and a 30-day money back guarantee): 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy. 2) Run Driver Easy and click the **Scan Now**  button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/img_594b60655cf90.png)

3) Click the **Update** button next to the flagged Bluetooth device to automatically download and install the correct version of that driver (you can do this with the FREE version). Or click **Update All** to automatically download and install the correct version of **_all_**  the drivers that are missing or out of date on your system (this requires the [**Pro version**](https://tools.techidaily.com/drivereasy/download/)  – you’ll be prompted to upgrade when you click Update All). ![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58e613efeb2c3.jpg)   **Option 3: Modify Registry settings** **Note**: In this option, we will be making some changes to the Registry. Before doing that, it is very important for you to [**backup**](https://tools.techidaily.com/drivereasy/download/) the registry first, just in case any unwanted error happens. 1) Type**regedit**in the search box and then choose**regedit Run command** from the list of choice.

![](https://images.drivereasy.com/wp-content/uploads/2016/11/regedit-run-command.png)

When prompted for administrator permission, just click**Yes**to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/11/uac.png)

2) Follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\ActionCenter\\Quick Actions\\All\\SystemSettings\_Device\_BluetoothQuickAction**.

![](https://images.drivereasy.com/wp-content/uploads/2016/11/hkey_local_machinesoftwaremicrosoftwindowscurrentversionactioncenterquick-actionsallsystemsettings_device_bluetoothquickaction.png)

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
<li><a href="https://fox-direct.techidaily.com/new-in-2024-5-prized-mac-compatible-live-streamers/"><u>[New] In 2024, 5 Prized Mac-Compatible Live Streamers</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-the-social-media-revolution-a-side-by-side-look-at-tiktok-and-snapchats-features/"><u>[New] In 2024, The Social Media Revolution A Side-By-Side Look at TikTok and Snapchat's Features</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-the-ultimate-guide-to-ps4-game-broadcasts-with-obs/"><u>2024 Approved The Ultimate Guide to PS4 Game Broadcasts with OBS</u></a></li>
<li><a href="https://some-guidance.techidaily.com/convert-avchd-files-to-mp4-at-no-cost-a-step-by-step-guide-for-windows-10-users/"><u>Convert AVCHD Files to MP4 at No Cost: A Step-by-Step Guide for Windows 10 Users</u></a></li>
<li><a href="https://driver-error.techidaily.com/error-message-decoded-overcoming-battleye-service-start-up-issues-and-driver-problems-code-1450/"><u>Error Message Decoded: Overcoming BattlEye Service Start-Up Issues and Driver Problems (Code 1450)</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-adjust-and-restore-correct-video-playback-direction-on-an-asus-notebook/"><u>How to Adjust and Restore Correct Video Playback Direction on an ASUS Notebook</u></a></li>
<li><a href="https://solve-lab.techidaily.com/metodo-gratuito-para-transformar-archivos-f4v-a-mp4-en-linea-facilmente-usando-el-software-de-movavi/"><u>Método Gratuito Para Transformar Archivos F4V a MP4 en Línea Fácilmente Usando El Software De Movavi</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/oladance-ows-sports-analysis-a-critical-look-at-the-audio-quality-of-open-ear-headphones/"><u>Oladance Ows Sports Analysis: A Critical Look at the Audio Quality of Open-Ear Headphones</u></a></li>
<li><a href="https://driver-error.techidaily.com/recover-lost-lfe-channel-with-your-pcs-audio-system-after-dolby-pro-logic-iix-error-installation-solved/"><u>Recover Lost LFE Channel with Your PC's Audio System After Dolby Pro Logic IIx Error Installation, Solved!✔️</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-fix-for-battleye-services-failed-initialization-and-resolving-error-1450-in-drivers/"><u>Step-by-Step Fix for BattlEye Service's Failed Initialization and Resolving Error 1450 in Drivers</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/step-by-step-tutorial-to-create-engaging-valorant-videos-with-thumbnails-for-2024/"><u>Step-by-Step Tutorial to Create Engaging Valorant Videos with Thumbnails for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/tackling-windows-11s-irql-crash/"><u>Tackling Windows 11'S IRQL Crash</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

