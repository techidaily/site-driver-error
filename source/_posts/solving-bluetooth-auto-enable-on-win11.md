---
title: Solving Bluetooth Auto-Enable on Win11
date: 2024-10-17T13:32:54.389Z
updated: 2024-10-17T21:59:59.806Z
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
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-zooming-into-clarity-a-blueprint-for-crisp-screenshots/"><u>[New] 2024 Approved Zooming Into Clarity A Blueprint for Crisp Screenshots</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/orldwide-top-earners-in-the-streaming-sphere-for-2024/"><u>[New] Worldwide Top Earners in the Streaming Sphere for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/update-wdcsam64prewin8sys-core-isolation-deactivated/"><u>[Update] wdcsam64_prewin8.sys: Core Isolation Deactivated</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-turning-twitter-videos-into-audible-mp3s/"><u>[Updated] In 2024, Turning Twitter Videos Into Audible MP3s</u></a></li>
<li><a href="https://blog-min.techidaily.com/2-ways-to-transfer-text-messages-from-infinix-hot-30i-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>2 Ways to Transfer Text Messages from Infinix Hot 30i to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/directx-9-hurdles-a-swift-fix-guidebook/"><u>DirectX 9 Hurdles: A Swift Fix Guidebook</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-3-things-you-must-know-about-fake-snapchat-location-on-apple-iphone-6s-drfone-by-drfone-virtual-ios/"><u>In 2024, 3 Things You Must Know about Fake Snapchat Location On Apple iPhone 6s | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-complete-fixes-to-solve-iphone-11-randomly-asking-for-apple-id-password-drfone-by-drfone-ios/"><u>In 2024, Complete Fixes To Solve iPhone 11 Randomly Asking for Apple ID Password | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-crafting-perfect-web-memories-with-our-top-browser-capture-software/"><u>In 2024, Crafting Perfect Web Memories with Our Top Browser Capture Software</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/m3-apple-silicon-revolutionizes-computing-discover-its-far-reaching-effects-beyond-macbooks-and-imacs-zdnet/"><u>M3 Apple Silicon Revolutionizes Computing – Discover Its Far-Reaching Effects Beyond MacBooks & iMacs | ZDNet</u></a></li>
<li><a href="https://driver-error.techidaily.com/razers-latest-gem-a-comprehensive-review-of-the-revolutionary-wi-fi-headset-for-gamers/"><u>Razer's Latest Gem: A Comprehensive Review of the Revolutionary Wi-Fi Headset for Gamers</u></a></li>
<li><a href="https://driver-error.techidaily.com/solve-non-functional-usb-audio-device-issue-in-win10/"><u>Solve Non-Functional USB Audio Device Issue in WIN10</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-elan-tablet-glitches-on-windows-10/"><u>Solving Elan Tablet Glitches on Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/sound-error-eliminated-on-hd-bus/"><u>Sound Error Eliminated on HD Bus</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-and-repairing-itbm-driver-accessibility-problems/"><u>Troubleshooting and Repairing ITBM Driver Accessibility Problems</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948905/19272" target="_top" id="1948905">
  <img src="//a.impactradius-go.com/display-ad/19272-1948905" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948905/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

