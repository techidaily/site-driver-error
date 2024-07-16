---
title: How to Prevent Nvidia Driver From Uninstalling Itself
date: 2024-07-15T06:50:38.482Z
updated: 2024-07-16T06:50:38.482Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes How to Prevent Nvidia Driver From Uninstalling Itself
excerpt: This Article Describes How to Prevent Nvidia Driver From Uninstalling Itself
thumbnail: https://thmb.techidaily.com/2944d63225d253c3279f8dae40efe484858639ea552fbe04c95a0ccb48d7f545.jpg
---

## How to Prevent Nvidia Driver From Uninstalling Itself

 Whenever you download and install a new**Nvidia driver** on your PC, it**keeps uninstalling itself** a few days later? Don’t worry, it’s fixable! And in most cases, the fix is pretty fast and simple…

## Try these fixes

 Here are 4 fixes that have helped other users get their Nvidia drivers working again. You may not have to try them all; just work your way down the list until you find the one that works for you.

1. [**Check your device installation settings**](https://uperfect.sjv.io/g1jgba)
2. [**Delete the logging file in your Windows Registry**](https://zonlipartnershipprogram.pxf.io/b0rbxy)
3. [**Update your Nvidia driver**](https://turtlebeacheu.sjv.io/1r0r59)
4. [**Reinstall your Nvidia driver**](https://dreoaffiliateprogram.pxf.io/k0ezjl)

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
### Fix 1: Check your device installation settings

 You can go to**Device Installation Settings** to stop Windows from automatically downloading drivers, then redownload the Nvidia driver you want. Here’s how to check your device installation settings:

1. On your keyboard, press the**Windows logo** ![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4ecde832800.png) key and**R** at the same time to invoke the Run box.
2. Type**control** and press**Enter** to go to Control Panel.  
<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc59b08cdf4e.png)
3. Click**System and Security** .  
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Fix 2: Delete the logging file in your Windows Registry

1. You should first make sure all Nvidia services are stopped:  
   1. Press the**Windows log** ![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4ecde832800.png) key and**R** together to open the Run box.  
   2. Type**services.msc**  then click**OK** .  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc5a9433a0fb.png)  
   3. Select and stop**all** Nvidia services.  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc5ae3f67690.jpg)
2. You should also check that all Nvidia programs are ended:  
   1. Press**Ctrl+Shift+Esc** to open Task Manager.  
   2. End**all** of Nvidia apps and processes.  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc5b0564178c.jpg)
3. You can then delete the logging file in your Windows Registry:  
   1. Press**Windows+R** to open the Run box.  
   2. Type **regedit** and press**Enter** .  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc5b13e9cf85.png)  
   3. Navigate to the following path, then delete the**Logging** file:  
   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\NVIDIA Corporation\\Logging**  
    **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Wow6432Node\\NVIDIA Corporation\\Logging**
4. Visit the Nvidia website to download and install the needed driver. If you’re not confident playing around with drivers manually, you can, instead, update your Nvidia driver automatically with**Driver Easy** in Fix 3, below.

---

### Fix 3: Update your Nvidia driver

 If your Nvidia driver is missing, corrupted, or improperly installed, it can also trigger the**Nvidia driver keeps uninstalling itself** issue.

 If you don’t have the time, patience or computer skills to update your Nvidia driver manually, you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . You don’t need to know exactly what system your computer is running, you don’t need to be troubled by the wrong driver you would be downloading, and you don’t need to worry about making a mistake when installing. Driver Easy handles it all.

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.
2. Run Driver Easy and click**Scan Now** . Driver Easy will then scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc58e5bb6635.jpg)
3. Click**Update** next to any flagged devices to automatically download the correct version of their drivers, then you can install them manually. Or click**Update All** to automatically download and install them all automatically. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  – you’ll be prompted to upgrade when you click Update All. You get full support and a 30-day money back guarantee.)  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc58e7b30171.jpg)
4. Restart your computer and check if your Nvidia driver now works properly. If it doesn’t, contact Driver Easy’s support team at**<support@drivereasy.com>** for further assistance. They’d be happy to help you. Or you can move on to Fix 4, below.

---

### Fix 4: Reinstall your Nvidia driver

1. Type**control** in the Run box and press**Enter** to open Control Panel.
2. Click**Uninstall a program** .  
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://instagram-clips.techidaily.com/updated-navigating-url-integration-in-ig-stories-and-posts/"><u>[Updated] Navigating URL Integration in IG Stories and Posts</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-most-useful-tips-for-pokemon-go-ultra-league-on-asus-rog-phone-8-pro-drfone-by-drfone-virtual-android/"><u>The Most Useful Tips for Pokemon Go Ultra League On Asus ROG Phone 8 Pro | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-unboxing-the-typhoon-h-yuneecs-drone-expertise/"><u>[New] 2024 Approved  Unboxing the Typhoon H  Yuneec's Drone Expertise</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-free-video-flipper-tools-rotate-your-videos-online/"><u>Updated In 2024, Free Video Flipper Tools Rotate Your Videos Online</u></a></li>
<li><a href="https://driver-error.techidaily.com/bringing-back-obscured-bluetooth-to-system-hub/"><u>Bringing Back: Obscured Bluetooth to System Hub</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-windows-11-irql-error/"><u>Resolved: Windows 11 Irql Error</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-iphones-mass-storage-problem-update-your-usb-drivers/"><u>Fixing iPhone's Mass Storage Problem: Update Your USB Drivers</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-best-digital-trailer-design-studios/"><u>New In 2024, Best Digital Trailer Design Studios</u></a></li>
<li><a href="https://driver-error.techidaily.com/win11-hd-audio-smooth-operations/"><u>Win11 HD Audio: Smooth Operations</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-qualcomm-atheros-bluetooth-driver-problems-in-windows-10-solved/"><u>Troubleshooting Qualcomm Atheros Bluetooth Driver Problems in Windows 10 - Solved</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-the-tap-trouble-on-win11s-elan-pad/"><u>Overcoming the Tap Trouble on Win11's Elan Pad</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-searches-for-missing-driver/"><u>Windows Searches for Missing Driver</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-realme-gt-3-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use GPS Joystick to Fake GPS Location On Realme GT 3 | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-facetime-simplified-a-compreited-guide-for-android-users/"><u>In 2024, FaceTime Simplified  A Compreited Guide for Android Users</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-warehouse-in-the-sky-top-pricing-on-demand/"><u>[New] Warehouse in the Sky  Top Pricing on Demand</u></a></li>
<li><a href="https://driver-error.techidaily.com/key-errors-on-win-10-pc/"><u>Key Errors on Win 10 PC</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-proven-methods-to-record-flawlessly-using-nvidia/"><u>2024 Approved  Proven Methods to Record Flawlessly Using NVIDIA</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-the-ultimate-guide-to-movie-trailer-software-for-mac-and-windows/"><u>Updated The Ultimate Guide to Movie Trailer Software for Mac and Windows</u></a></li>
<li><a href="https://driver-error.techidaily.com/restoring-windows-enter-button-operations/"><u>Restoring Windows Enter Button Operations</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-5-ways-to-record-streaming-audio-online-for-2024/"><u>[New] 5 Ways to Record Streaming Audio Online for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/stop-amd-driver-problems-immediately/"><u>Stop AMD Driver Problems Immediately</u></a></li>
<li><a href="https://driver-error.techidaily.com/easy-troubleshooting-tips-to-repair-qualcomm-atheros-bluetooth-driver-malfunctions-in-windows-10/"><u>Easy Troubleshooting Tips to Repair Qualcomm Atheros Bluetooth Driver Malfunctions in Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/801gamma-x-aimslearnmore-wes)/"><u>801`(Gamma = {X | AIMS_LearnMore, We's]]></u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-guide-booting-into-windows-8-safe-mode-and-removing-your-graphic-drivers/"><u>Step-by-Step Guide: Booting Into Windows 8 Safe Mode & Removing Your Graphic Drivers</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-quick-start-to-engaging-in-face-to-face-conversations-on-snapchat/"><u>[Updated] Quick Start to Engaging in Face-to-Face Conversations on Snapchat</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-instantly-correct-itbm-driver-availability-errors/"><u>How to Instantly Correct ITBm Driver Availability Errors</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-incompatibility-issues-a-users-guide-to-validating-and-fixing-invalid-driver-installs/"><u>Overcoming Incompatibility Issues: A User's Guide to Validating and Fixing Invalid Driver Installs</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-anymp4-screen-recorder-download-and-review/"><u>[New] 2024 Approved  AnyMP4 Screen Recorder Download and Review</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-i-overcame-iphones-external-storage-connectivity-issues-with-mtp-drivers/"><u>How I Overcame iPhone's External Storage Connectivity Issues with MTP Drivers</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-0x0000007e-blue-screen-of-death-error-on-windows-7/"><u>[Solved] 0X0000007E Blue Screen of Death Error on Windows 7</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-building-a-brand-building-income-youtube-edition/"><u>[New] 2024 Approved  Building a Brand, Building Income  YouTube Edition</u></a></li>
<li><a href="https://driver-error.techidaily.com/repairing-windows-lack-of-enter-button-input/"><u>Repairing Windows: Lack of Enter Button Input</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-scoreboard-the-best-video-to-mp3-convertors/"><u>2024 Approved  Scoreboard  The Best Video to Mp3 Convertors</u></a></li>
<li><a href="https://driver-error.techidaily.com/navigating-ndis-roadblocks-in-windows-easily/"><u>Navigating NDIS Roadblocks in Windows Easily</u></a></li>
<li><a href="https://driver-error.techidaily.com/ethernet-woes-in-win11-realtek-fix-found-here/"><u>Ethernet Woes in Win11 - Realtek Fix Found Here</u></a></li>
<li><a href="https://driver-error.techidaily.com/comprehensive-fix-addressing-missing-coprocessor-drivers-in-your-windows-10-machine/"><u>Comprehensive Fix: Addressing Missing Coprocessor Drivers in Your Windows 10 Machine</u></a></li>
<li><a href="https://driver-error.techidaily.com/unable-to-mute-or-disable-internal-wifibluetooth-on-windows-10-fix/"><u>Unable to Mute or Disable Internal WIFI/Bluetooth on Windows 10 – Fix?</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-samsung-galaxy-xcover-7-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Samsung Galaxy XCover 7 Reset Code | Dr.fone</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/updated-2024-approved-maximize-yandex-translate-in-video-translation-and-beyond/"><u>Updated 2024 Approved Maximize Yandex Translate in Video Translation and Beyond</u></a></li>
<li><a href="https://driver-error.techidaily.com/navigating-safe-mode-on-windows-8-and-how-to-uninstall-video-card-software/"><u>Navigating Safe Mode on Windows 8 & How to Uninstall Video Card Software</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-audible-mac-visual-record-functionality-for-2024/"><u>[Updated] Audible Mac Visual Record Functionality for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/gtx-950-code-43-troubleshooting-expert-tips-for-windows-11-users/"><u>GTX 950 Code 43 Troubleshooting: Expert Tips for Windows 11 Users</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-a-lost-honor-x9b-for-free-drfone-by-drfone-virtual-android/"><u>How to Track a Lost Honor X9b for Free? | Dr.fone</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/optimize-your-mac-a-step-by-step-guide-to-freeing-up-space-for-fcpx-for-2024/"><u>Optimize Your Mac A Step-by-Step Guide to Freeing Up Space for FCPX for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-hd-audio-windows-quest/"><u>[Resolved] HD Audio Windows Quest</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-from-vivo-x90s-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock from Vivo X90S Devices</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-fake-gps-location-apps-on-android-of-your-itel-s23-drfone-by-drfone-virtual/"><u>In 2024, 10 Fake GPS Location Apps on Android Of your Itel S23 | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/fast-remediation-faulty-mtp-usb-cables/"><u>Fast Remediation: Faulty MTP USB Cables</u></a></li>
<li><a href="https://driver-error.techidaily.com/device-detection-issue-absence-of-intel-chipset/"><u>Device Detection Issue: Absence of Intel Chipset</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/ways-to-stop-parent-tracking-your-apple-iphone-se-drfone-by-drfone-virtual-ios/"><u>Ways to stop parent tracking your Apple iPhone SE | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/excellent-free-webcam-video-snapper-app/"><u>Excellent Free Webcam Video Snapper App</u></a></li>
<li><a href="https://driver-error.techidaily.com/device-compatibility-error-wudfrd-loading-failure/"><u>Device Compatibility Error: WudfRd Loading Failure</u></a></li>
<li><a href="https://driver-error.techidaily.com/easy-to-fix-amd-drivers-keep-crashing-issue/"><u>Easy To Fix AMD Drivers Keep Crashing Issue</u></a></li>
<li><a href="https://driver-error.techidaily.com/understanding-and-repairing-the-blue-screen-of-death-error-0x00000/"><u>Understanding and Repairing the Blue Screen of Death: Error 0X00000</u></a></li>
<li><a href="https://driver-error.techidaily.com/mouse-not-connecting-windows-troubleshoot/"><u>Mouse Not Connecting: Windows Troubleshoot</u></a></li>
<li><a href="https://driver-error.techidaily.com/reversing-vertical-screen-orientation-in-asus-devices-for-optimal-viewing/"><u>Reversing Vertical Screen Orientation in ASUS Devices for Optimal Viewing</u></a></li>
<li><a href="https://driver-error.techidaily.com/finalised-device-driver-successfully-installed-and-running/"><u>[FINALISED] Device Driver Successfully Installed and Running</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-choose-your-view-facebook-video-aspect-ratio/"><u>[New] Choose Your View  Facebook Video Aspect Ratio</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/best-youtube-hubs-for-professional-insights/"><u>Best YouTube Hubs for Professional Insights</u></a></li>
<li><a href="https://driver-error.techidaily.com/task-management-overcoming-disk-saturation-on-win11/"><u>Task Management: Overcoming Disk Saturation on Win11</u></a></li>
</ul></div>
