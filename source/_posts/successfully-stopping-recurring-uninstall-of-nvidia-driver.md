---
title: Successfully Stopping Recurring Uninstall of Nvidia Driver
date: 2024-08-22T14:13:49.676Z
updated: 2024-08-23T14:13:49.676Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Successfully Stopping Recurring Uninstall of Nvidia Driver
excerpt: This Article Describes Successfully Stopping Recurring Uninstall of Nvidia Driver
thumbnail: https://thmb.techidaily.com/c9e9de36eb357f7db5b739ff1ada424f8276ace6815f6a294b656d072c86df72.jpg
---

## Successfully Stopping Recurring Uninstall of Nvidia Driver

 Whenever you download and install a new**Nvidia driver** on your PC, it**keeps uninstalling itself** a few days later? Don’t worry, it’s fixable! And in most cases, the fix is pretty fast and simple…

## Try these fixes

 Here are 4 fixes that have helped other users get their Nvidia drivers working again. You may not have to try them all; just work your way down the list until you find the one that works for you.

1. [**Check your device installation settings**](https://uperfect.sjv.io/g1jgba)
2. [**Delete the logging file in your Windows Registry**](https://zonlipartnershipprogram.pxf.io/b0rbxy)
3. [**Update your Nvidia driver**](https://turtlebeacheu.sjv.io/1r0r59)
4. [**Reinstall your Nvidia driver**](https://dreoaffiliateprogram.pxf.io/k0ezjl)

### Fix 1: Check your device installation settings

 You can go to**Device Installation Settings** to stop Windows from automatically downloading drivers, then redownload the Nvidia driver you want. Here’s how to check your device installation settings:

1. On your keyboard, press the**Windows logo** ![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4ecde832800.png) key and**R** at the same time to invoke the Run box.
2. Type**control** and press**Enter** to go to Control Panel.  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc59b08cdf4e.png)
3. Click**System and Security** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc59ba063ed0.jpg)
4. Click**System** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc59bd79ae6d.jpg)
5. Click**Advanced system settings** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc59c0e94e5d.jpg)
6. Click the**Hardware** tab, then the**Device Installation Settings** button.  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc59cb552443.jpg)
7. Select**No** , and click**Save changes** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc5a1202b9e9.jpg)
8. Click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc5a2a572543.jpg)
9. Go to the**NVIDIA Driver Downloads** page to download the needed driver for your Nvidia graphics card.  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc5994c83f8c.jpg)
10. Open the downloaded file and follow the on-screen instructions to install the driver.
11. Restart your computer and check if the problem is resolved. If not, try Fix 2, below.

---

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
### Fix 2: Delete the logging file in your Windows Registry

1. You should first make sure all Nvidia services are stopped:  
   1. Press the**Windows log** ![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4ecde832800.png) key and**R** together to open the Run box.  
   2. Type**services.msc**  then click**OK** .  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc5a9433a0fb.png)  
   3. Select and stop**all** Nvidia services.  
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
   ![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc5ae3f67690.jpg)
2. You should also check that all Nvidia programs are ended:  
   1. Press**Ctrl+Shift+Esc** to open Task Manager.  
   2. End**all** of Nvidia apps and processes.  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc5b0564178c.jpg)
3. You can then delete the logging file in your Windows Registry:  
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
   1. Press**Windows+R** to open the Run box.  
   2. Type **regedit** and press**Enter** .  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc5b13e9cf85.png)  
   3. Navigate to the following path, then delete the**Logging** file:  
   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\NVIDIA Corporation\\Logging**  
    **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Wow6432Node\\NVIDIA Corporation\\Logging**
4. Visit the Nvidia website to download and install the needed driver. If you’re not confident playing around with drivers manually, you can, instead, update your Nvidia driver automatically with**Driver Easy** in Fix 3, below.

---

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
### Fix 3: Update your Nvidia driver

 If your Nvidia driver is missing, corrupted, or improperly installed, it can also trigger the**Nvidia driver keeps uninstalling itself** issue.

 If you don’t have the time, patience or computer skills to update your Nvidia driver manually, you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . You don’t need to know exactly what system your computer is running, you don’t need to be troubled by the wrong driver you would be downloading, and you don’t need to worry about making a mistake when installing. Driver Easy handles it all.

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.
2. Run Driver Easy and click**Scan Now** . Driver Easy will then scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc58e5bb6635.jpg)
3. Click**Update** next to any flagged devices to automatically download the correct version of their drivers, then you can install them manually. Or click**Update All** to automatically download and install them all automatically. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  – you’ll be prompted to upgrade when you click Update All. You get full support and a 30-day money back guarantee.)  
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc58e7b30171.jpg)
4. Restart your computer and check if your Nvidia driver now works properly. If it doesn’t, contact Driver Easy’s support team at**<support@drivereasy.com>** for further assistance. They’d be happy to help you. Or you can move on to Fix 4, below.

---

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Fix 4: Reinstall your Nvidia driver

1. Type**control** in the Run box and press**Enter** to open Control Panel.
2. Click**Uninstall a program** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc5b694a6834.jpg)
3. Delete all Nvidia programs.  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc5b6e7f170d.jpg)
4. Restart your computer.
5. When you’re back in Windows, repeat the steps in [**Fix** **2**](https://propmoneyinc.pxf.io/q4jzdy) above.

---

 After trying all of the above fixes, does your Nvidia driver now work properly? If not, don’t give up hope. Our IT specialists will help you fix it for free, if you [buy Driver Easy](https://tools.techidaily.com/drivereasy/download/) . Plus you get a super-easy way to automatically update all your drivers, and keep your computer in tip-top shape!

 Either way, as always, you’re more than welcome to leave a comment below to share your results or any other suggestions.

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
<li><a href="https://driver-error.techidaily.com/fixed-arch-bluetooth-mouse-not-working-after-windows-10-creators-update/"><u>[FIXED] Arch Bluetooth Mouse Not Working After Windows 10 Creators Update</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-ultimate-editing-hacks-for-flawless-image-edits-on-canva-for-2024/"><u>[New] Ultimate Editing Hacks for Flawless Image Edits on Canva for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/quick-fix-unresponsive-rtx-game-heres-how-we-fixed-it/"><u>[Quick Fix] Unresponsive RTX Game? Here’s How We Fixed It</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-asus-keys-no-light/"><u>[RESOLVED] Asus Keys No Light</u></a></li>
<li><a href="https://driver-error.techidaily.com/status-update-device-recognition-success/"><u>[Status Update: Device Recognition Success]</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-free-mcb-theme-images-templates-and-more/"><u>[Updated] 2024 Approved  Free MCB Theme Images, Templates & More</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-map-masterpieces-excellent-quests-for-gold/"><u>[Updated] 2024 Approved  Map Masterpieces  Excellent Quests for Gold</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-how-to-use-snap-camera-on-google-meet-for-2024/"><u>[Updated] How to Use Snap Camera on Google Meet for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-how-to-triple-down-on-instagrams-growth-metrics/"><u>[Updated] In 2024, How to Triple Down on Instagram's Growth Metrics</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-quick-setup-obs-and-zoom-coexistence-made-simple-for-2024/"><u>[Updated] Quick Setup  OBS & Zoom Coexistence Made Simple for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-retro-reality-on-snapchat-effortless-video-reversal-for-2024/"><u>[Updated] Retro Reality on Snapchat  Effortless Video Reversal for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-revealing-hidden-pathways-understanding-facebooks-off-activity-tracking-for-2024/"><u>[Updated] Revealing Hidden Pathways  Understanding Facebook's Off-Activity Tracking for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-ideal-screencasting-software-for-effective-teaching/"><u>2024 Approved  Ideal Screencasting Software for Effective Teaching</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unleash-creativity-fast-windows-10-photo-edits-made-simple/"><u>2024 Approved  Unleash Creativity Fast  Windows 10 Photo Edits Made Simple</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/animation-mastery-the-10-best-2d-software-for-creators-free-and-paid-for-2024/"><u>Animation Mastery The 10 Best 2D Software for Creators Free & Paid for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/device-unity-wacoms-happy-ever-after/"><u>Device Unity: Wacom's Happy Ever After</u></a></li>
<li><a href="https://driver-error.techidaily.com/disabling-permanent-bluetooth-issue-fixed/"><u>Disabling Permanent Bluetooth Issue (Fixed)</u></a></li>
<li><a href="https://driver-error.techidaily.com/dvd-non-discovery-in-windows-11-resolved-quickly/"><u>DVD Non-Discovery in Windows 11 - Resolved Quickly</u></a></li>
<li><a href="https://driver-error.techidaily.com/effective-ways-to-fix-the-qualcomm-atheros-bluetooth-driver-errors-in-windows-10-computers/"><u>Effective Ways to Fix the Qualcomm Atheros Bluetooth Driver Errors in Windows 10 Computers</u></a></li>
<li><a href="https://driver-error.techidaily.com/eradicating-invalid-configuration-segment-in-inf/"><u>Eradicating Invalid Configuration Segment in INF</u></a></li>
<li><a href="https://driver-error.techidaily.com/error-48-resolved-in-device-manager/"><u>Error 48 Resolved in Device Manager</u></a></li>
<li><a href="https://sound-issues.techidaily.com/fast-solutions-repairing-your-oculus-rift-s-headsets-microphone-in-minutes-updated-guide/"><u>Fast Solutions: Repairing Your Oculus Rift S Headset's Microphone in Minutes – Updated Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-blue-yeti-drivers-not-detected-recognized-or-installed/"><u>Fix: Blue Yeti Drivers Not Detected, Recognized or Installed</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-deleted-oneplus-photos-an-easy-method-explained-by-fonelab-android-recover-photos/"><u>How to Restore Deleted OnePlus Photos  An Easy Method Explained.</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-turn-off-find-my-iphone-8-when-phone-is-broken-drfone-by-drfone-ios/"><u>How to Turn Off Find My iPhone 8 when Phone is Broken? | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-a-quick-dive-into-video-ratios-the-aspect-ratio-essentials-for-youtubers/"><u>In 2024, A Quick Dive Into Video Ratios  The Aspect Ratio Essentials for YouTubers</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-htc-u23-pro-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your HTC U23 Pro Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/instagram-and-soundtracks-demystifying-legalities/"><u>Instagram & Soundtracks  Demystifying Legalities</u></a></li>
<li><a href="https://driver-error.techidaily.com/introducing-the-minisforum-s100-a-pocket-computer-with-poe-and-25gbe-connectivity/"><u>Introducing the Minisforum S100: A Pocket Computer with PoE and 2.5GbE Connectivity</u></a></li>
<li><a href="https://driver-error.techidaily.com/keyboard-failure-in-windows-10/"><u>Keyboard Failure in Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/lenovo-bluetooth-streamlined-in-the-era-of-windows-11/"><u>Lenovo Bluetooth Streamlined in the Era of Windows 11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/leveraging-videos-with-text-a-cost-free-approach/"><u>Leveraging Videos with Text  A Cost-Free Approach</u></a></li>
<li><a href="https://driver-error.techidaily.com/mastering-safe-boot-in-windows-8-a-complete-guide-to-disable-and-reinstall-display-adapters/"><u>Mastering Safe Boot in Windows 8 - A Complete Guide to Disable and Reinstall Display Adapters</u></a></li>
<li><a href="https://driver-error.techidaily.com/mend-quickly-persistent-amd-glitches/"><u>Mend Quickly: Persistent AMD Glitches</u></a></li>
<li><a href="https://driver-error.techidaily.com/no-more-errors-hidef-audio-device-fixed/"><u>No More Errors: HiDef Audio Device Fixed</u></a></li>
<li><a href="https://some-guidance.techidaily.com/quintessential-underwater-accessories-for-gopro-for-2024/"><u>Quintessential Underwater Accessories for Gopro for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-usb-network-driver-not-working-after-update/"><u>Resolving USB Network Driver Not Working After Update</u></a></li>
<li><a href="https://driver-error.techidaily.com/restored-functioning-keyboard-on-windows-11-pc/"><u>Restored: Functioning Keyboard on Windows 11 PC</u></a></li>
<li><a href="https://driver-error.techidaily.com/seamless-iphone-data-sharing-made-possible-by-resolving-usb-device-driver-hiccups/"><u>Seamless iPhone Data Sharing Made Possible by Resolving USB Device Driver Hiccups</u></a></li>
<li><a href="https://driver-error.techidaily.com/solution-guide-installing-missing-drivers-on-your-device-compatible-with-older-versions-of-windows/"><u>Solution Guide: Installing Missing Drivers on Your Device Compatible with Older Versions of Windows</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-endless-bluetooth-in-win10/"><u>Solving Endless Bluetooth in Win10</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-the-issue-invalid-driver-installation-on-your-pc/"><u>Solving the Issue: Invalid Driver Installation on Your PC</u></a></li>
<li><a href="https://driver-error.techidaily.com/stabilized-windows-11-display/"><u>Stabilized Windows 11 Display</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-tutorial-to-recover-disappeared-gpu-drivers-on-windows-10-platforms/"><u>Step-by-Step Tutorial to Recover Disappeared GPU Drivers on Windows 10 Platforms</u></a></li>
<li><a href="https://driver-error.techidaily.com/steps-to-solve-windows-78-unsupported-usb-errors/"><u>Steps to Solve Windows 7/8 Unsupported USB Errors</u></a></li>
<li><a href="https://driver-error.techidaily.com/strategies-to-tackle-intel-mmc-errors/"><u>Strategies to Tackle Intel MMC Errors</u></a></li>
<li><a href="https://some-guidance.techidaily.com/streaming-high-quality-vr-videos-made-easy-for-ios-users-for-2024/"><u>Streaming High-Quality VR Videos Made Easy for IOS Users for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/triumph-over-hardware-conflict-45/"><u>Triumph Over Hardware Conflict #45</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-and-fixing-the-absent-coprocessor-in-windows-11-guide/"><u>Troubleshooting and Fixing the Absent Coprocessor in Windows 11 [Guide]</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-base-driver-errors-dm/"><u>Troubleshooting Base Driver Errors (DM)</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/ultimate-movie-watchlists-streamlining-screen-time/"><u>Ultimate Movie Watchlists  Streamlining Screen Time</u></a></li>
<li><a href="https://driver-error.techidaily.com/unearthing-the-opengl-enhanced-intel-chipset/"><u>Unearthing the OpenGL-Enhanced Intel Chipset</u></a></li>
<li><a href="https://driver-error.techidaily.com/vehicle-compatibility-problem-with-gadget/"><u>Vehicle Compatibility Problem with Gadget</u></a></li>
<li><a href="https://driver-error.techidaily.com/win-compatibility-solving-broadcom-wi-fi-n-adapter-problems/"><u>Win Compatibility: Solving Broadcom Wi-Fi N Adapter Problems</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-10-supports-asus-usb-camera-better-now/"><u>Windows 10 Supports ASUS USB Camera Better Now</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-11-irql-glitch-resolved/"><u>Windows 11 IRQL Glitch Resolved</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-users-samsung-driver-installation/"><u>Windows Users: Samsung Driver Installation</u></a></li>
</ul></div>
