---
title: Cease Recurring Uninstall of Hardware Drivers
date: 2024-07-15T06:57:02.418Z
updated: 2024-07-16T06:57:02.418Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Cease Recurring Uninstall of Hardware Drivers
excerpt: This Article Describes Cease Recurring Uninstall of Hardware Drivers
thumbnail: https://thmb.techidaily.com/ec5c93589cbbf4437a85d01509aad074c0824b7a47a862a6e3798990cfe51fb1.png
---

## Cease Recurring Uninstall of Hardware Drivers

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
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc59ba063ed0.jpg)
4. Click**System** .  
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc5994c83f8c.jpg)
10. Open the downloaded file and follow the on-screen instructions to install the driver.
11. Restart your computer and check if the problem is resolved. If not, try Fix 2, below.

---

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
<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://driver-error.techidaily.com/how-i-overcame-iphones-external-storage-connectivity-issues-with-mtp-drivers/"><u>How I Overcame iPhone's External Storage Connectivity Issues with MTP Drivers</u></a></li>
<li><a href="https://driver-error.techidaily.com/active-alert-code-cleared/"><u>Active Alert: Code Cleared</u></a></li>
<li><a href="https://driver-error.techidaily.com/section-error-inf-service-setup-invalid-resolved/"><u>Section Error: INF Service Setup Invalid - Resolved</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-automate-your-video-editing-top-auto-reframe-tools/"><u>2024 Approved Automate Your Video Editing Top Auto-Reframe Tools</u></a></li>
<li><a href="https://driver-error.techidaily.com/stop-amd-driver-problems-immediately/"><u>Stop AMD Driver Problems Immediately</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/how-to-make-a-bigger-head-look-on-your-tiktok-video-a-comprehensive-guide-3-steps/"><u>How to Make a Bigger Head Look on Your TikTok Video  A Comprehensive Guide (3 Steps)</u></a></li>
<li><a href="https://extra-resources.techidaily.com/boost-your-game-presence-with-free-voice-alteration-tips-for-free-fire/"><u>Boost Your Game Presence with Free Voice Alteration Tips for Free Fire</u></a></li>
<li><a href="https://driver-error.techidaily.com/task-management-overcoming-disk-saturation-on-win11/"><u>Task Management: Overcoming Disk Saturation on Win11</u></a></li>
<li><a href="https://driver-error.techidaily.com/mouse-not-connecting-windows-troubleshoot/"><u>Mouse Not Connecting: Windows Troubleshoot</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-samsung-galaxy-a24-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Samsung Galaxy A24 to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/801gamma-x-aimslearnmore-wes)/"><u>801`(Gamma = {X | AIMS_LearnMore, We's]]></u></a></li>
<li><a href="https://driver-error.techidaily.com/navigating-safe-mode-on-windows-8-and-how-to-uninstall-video-card-software/"><u>Navigating Safe Mode on Windows 8 & How to Uninstall Video Card Software</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-rapid-removal-of-ssgnature-backdrops-explained/"><u>[New] Rapid Removal of Ssgnature Backdrops Explained</u></a></li>
<li><a href="https://driver-error.techidaily.com/unable-to-mute-or-disable-internal-wifibluetooth-on-windows-10-fix/"><u>Unable to Mute or Disable Internal WIFI/Bluetooth on Windows 10 – Fix?</u></a></li>
<li><a href="https://techidaily.com/is-your-xiaomi-redmi-a2-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Xiaomi Redmi A2 working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/key-errors-on-win-10-pc/"><u>Key Errors on Win 10 PC</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-0x0000007e-blue-screen-of-death-error-on-windows-7/"><u>[Solved] 0X0000007E Blue Screen of Death Error on Windows 7</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-the-tap-trouble-on-win11s-elan-pad/"><u>Overcoming the Tap Trouble on Win11's Elan Pad</u></a></li>
<li><a href="https://driver-error.techidaily.com/gtx-950-code-43-troubleshooting-expert-tips-for-windows-11-users/"><u>GTX 950 Code 43 Troubleshooting: Expert Tips for Windows 11 Users</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-popular-aspect-ratio-transformer-tools-for-image-and-video-editing/"><u>New 2024 Approved Popular Aspect Ratio Transformer Tools for Image and Video Editing</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-a-step-by-step-approach-to-infusing-conversations-with-gifs-on-snapchat-for-2024/"><u>[Updated] A Step-by-Step Approach to Infusing Conversations with GIFs on Snapchat for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-instantly-correct-itbm-driver-availability-errors/"><u>How to Instantly Correct ITBm Driver Availability Errors</u></a></li>
<li><a href="https://driver-error.techidaily.com/understanding-and-repairing-the-blue-screen-of-death-error-0x00000/"><u>Understanding and Repairing the Blue Screen of Death: Error 0X00000</u></a></li>
<li><a href="https://driver-error.techidaily.com/comprehensive-fix-addressing-missing-coprocessor-drivers-in-your-windows-10-machine/"><u>Comprehensive Fix: Addressing Missing Coprocessor Drivers in Your Windows 10 Machine</u></a></li>
<li><a href="https://driver-error.techidaily.com/mastering-the-update-process-how-to-get-latest-drivers-for-hp-envy-nv-series-computers/"><u>Mastering the Update Process: How to Get Latest Drivers for HP Envy Nv Series Computers</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-qualcomm-atheros-bluetooth-driver-problems-in-windows-10-solved/"><u>Troubleshooting Qualcomm Atheros Bluetooth Driver Problems in Windows 10 - Solved</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-most-reliable-gopro-cases-1-10-showdown/"><u>The Most Reliable GoPro Cases - #1-10 Showdown</u></a></li>
<li><a href="https://driver-error.techidaily.com/device-compatibility-error-wudfrd-loading-failure/"><u>Device Compatibility Error: WudfRd Loading Failure</u></a></li>
<li><a href="https://some-techniques.techidaily.com/gold-standard-of-livestream-performances-for-2024/"><u>Gold Standard of Livestream Performances for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-graphic-issues-on-windows-8-learn-to-start-in-safe-mode-and-perform-graphics-driver-updates-or-reinstalls/"><u>Resolving Graphic Issues on Windows 8? Learn to Start in Safe Mode & Perform Graphics Driver Updates or Reinstalls</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-activation-lock-on-mac-for-apple-iphone-13-mini-by-drfone-ios/"><u>In 2024, How To Bypass iCloud Activation Lock on Mac For Apple iPhone 13 mini?</u></a></li>
<li><a href="https://driver-error.techidaily.com/fast-remediation-faulty-mtp-usb-cables/"><u>Fast Remediation: Faulty MTP USB Cables</u></a></li>
<li><a href="https://driver-error.techidaily.com/easy-to-fix-amd-drivers-keep-crashing-issue/"><u>Easy To Fix AMD Drivers Keep Crashing Issue</u></a></li>
</ul></div>
