---
title: Fixing the Auto-Uninstall Loop in Nvidia Drivers
date: 2024-08-15T06:43:30.069Z
updated: 2024-08-16T06:43:30.069Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Fixing the Auto-Uninstall Loop in Nvidia Drivers
excerpt: This Article Describes Fixing the Auto-Uninstall Loop in Nvidia Drivers
thumbnail: https://thmb.techidaily.com/42a3217d9873863c48091846f5f8a9e9b9b6456440b499628df593e7d229a025.jpg
---

## Fixing the Auto-Uninstall Loop in Nvidia Drivers

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
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc59b08cdf4e.png)
3. Click**System and Security** .  
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc59ba063ed0.jpg)
4. Click**System** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc59bd79ae6d.jpg)
5. Click**Advanced system settings** .  
<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc59c0e94e5d.jpg)
6. Click the**Hardware** tab, then the**Device Installation Settings** button.  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc59cb552443.jpg)
7. Select**No** , and click**Save changes** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc5a1202b9e9.jpg)
8. Click**OK** .  
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc5a2a572543.jpg)
9. Go to the**NVIDIA Driver Downloads** page to download the needed driver for your Nvidia graphics card.  
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
   ![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bc5b13e9cf85.png)  
   3. Navigate to the following path, then delete the**Logging** file:  
   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\NVIDIA Corporation\\Logging**  
    **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Wow6432Node\\NVIDIA Corporation\\Logging**
4. Visit the Nvidia website to download and install the needed driver. If you’re not confident playing around with drivers manually, you can, instead, update your Nvidia driver automatically with**Driver Easy** in Fix 3, below.

---

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://facebook-video-files.techidaily.com/new-2024-approved-boosting-your-fb-pages-advanced-ranking-strategies/"><u>[New] 2024 Approved  Boosting Your FB Pages  Advanced Ranking Strategies</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-twisting-tales-in-visual-storytelling-mastering-the-art-of-rotating-photos-for-maximum-engagement-on-social-media-platforms/"><u>[New] 2024 Approved  Twisting Tales in Visual Storytelling  Mastering the Art of Rotating Photos for Maximum Engagement on Social Media Platforms</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-vlog-verily-tips-and-taboos-in-the-daily-digital-sphere/"><u>[New] 2024 Approved  Vlog Verily  Tips and Taboos in the Daily Digital Sphere</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-capture-screens-free-cross-platform-for-windowsmac-users/"><u>[New] Capture Screens, Free! - Cross-Platform for Windows/Mac Users</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-how-to-share-twitch-stream-on-facebook-for-2024/"><u>[New] How to Share Twitch Stream on Facebook for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-tweeting-videos-to-tweenish-animations-for-no-fee/"><u>[New] In 2024, Tweeting Videos to Tweenish Animations for No Fee</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-pendulum-assembly-set/"><u>[New] Pendulum Assembly Set</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-adjusting-your-macs-snapshot-formats-with-ease/"><u>[Updated] Adjusting Your Mac's Snapshot Formats with Ease</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-get-facebook-links-fetched-top-8-free-tools-for-23-for-2024/"><u>[Updated] Get Facebook Links Fetched  Top 8 Free Tools for '23 for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-comprehensive-guide-to-showmores-efficient-recording-tools/"><u>[Updated] In 2024, Comprehensive Guide to ShowMore's Efficient Recording Tools</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-sharing-tweets-with-facebook-friends/"><u>[Updated] In 2024, Sharing Tweets with Facebook Friends</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-optimal-solutions-to-clear-logos-on-tiktok-media-for-2024/"><u>[Updated] Optimal Solutions to Clear Logos on TikTok Media for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-behind-the-scenes-choosing-ideal-winter-backdrops/"><u>2024 Approved  Behind the Scenes  Choosing Ideal Winter Backdrops</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-creating-a-domino-effect-with-memes/"><u>2024 Approved  Creating a Domino Effect with Memes</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-saving-your-focus-a-guide-to-quieting-naysayers-on-google-video-calls/"><u>2024 Approved  Saving Your Focus  A Guide to Quieting Naysayers on Google Video Calls</u></a></li>
<li><a href="https://driver-error.techidaily.com/avoiding-frequent-nvidia-driver-malfunctions/"><u>Avoiding Frequent Nvidia Driver Malfunctions</u></a></li>
<li><a href="https://driver-error.techidaily.com/correcting-venintanddev33a0-drive-errors/"><u>Correcting VEN_INT&DEV_33A0 Drive Errors</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721104231373-demystifying-the-legacy-usb-composite-device-problems-now-fixed/"><u>Demystifying the Legacy USB Composite Device Problems - Now Fixed</u></a></li>
<li><a href="https://driver-error.techidaily.com/efficient-deathadder-drivers-on-new-windows-version/"><u>Efficient DeathAdder Drivers on New Windows Version</u></a></li>
<li><a href="https://driver-error.techidaily.com/elan-touchpad-driver-issues-in-windows-11-solved/"><u>Elan Touchpad Driver Issues in Windows 11 [Solved]</u></a></li>
<li><a href="https://driver-error.techidaily.com/enabling-seagate-drives-on-new-windows-11-os/"><u>Enabling Seagate Drives on New Windows 11 OS</u></a></li>
<li><a href="https://driver-error.techidaily.com/enhanced-recording-quality-fixed-windows-10-asus-cam-issue/"><u>Enhanced Recording Quality: Fixed Windows 10 ASUS Cam Issue</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ring-the-world-of-aspect-ratios-in-youtube-content-for-2024/"><u>Exploring the World of ASPECT RATIOS in YOUTUBE Content for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/failed-driver-setup-absence-of-intel-interface/"><u>Failed Driver Setup - Absence of Intel Interface</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-for-missing-win-pci-data-collector/"><u>Fix for Missing Win PCI Data Collector</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-install-realtek-hd-audio-driver-failure-easily/"><u>Fix Install Realtek HD Audio Driver Failure. Easily</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-intel-mcpu-driver-problems/"><u>Fixing Intel MCPU Driver Problems</u></a></li>
<li><a href="https://unlock-android.techidaily.com/full-tutorial-to-bypass-your-honor-play-7t-face-lock-by-drfone-android/"><u>Full Tutorial to Bypass Your Honor Play 7T Face Lock?</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-deactivate-non-stop-bluetooth-on-pcs/"><u>How to Deactivate Non-Stop Bluetooth on PCs</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-fix-failed-to-start-battleye-addressing-the-1450-driver-load-issue/"><u>How to Fix 'Failed to Start BattlEye': Addressing the 1450 Driver Load Issue</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-oppo-k11x-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a Oppo K11x Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-your-xiaomi-14-pro-lock-screen-password-by-drfone-android/"><u>How to Reset your Xiaomi 14 Pro Lock Screen Password</u></a></li>
<li><a href="https://driver-error.techidaily.com/master-the-fix-how-to-properly-configure-devices-and-avoid-error-code-1-issues/"><u>Master the Fix: How to Properly Configure Devices & Avoid Error Code 1 Issues</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-streamline-your-workflow-40-key-final-cut-pro-x-keyboard-shortcuts/"><u>New Streamline Your Workflow 40 Key Final Cut Pro X Keyboard Shortcuts</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-the-device-misconfigured-hurdle-resolving-code-1-issues/"><u>Overcoming the 'Device Misconfigured' Hurdle - Resolving Code 1 Issues</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-the-challenge-of-a-nonfunctional-coprocessor-module-for-windows-10-users-solutions-unveiled/"><u>Overcoming the Challenge of a Nonfunctional Coprocessor Module for Windows 10 Users – Solutions Unveiled</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-venintanddev33a0-acpi-challenges/"><u>Overcoming VEN_INT&DEV_33A0 Acpi Challenges</u></a></li>
<li><a href="https://driver-error.techidaily.com/printer-driver-issue-resolved-quickly/"><u>Printer Driver Issue Resolved Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proactive-approaches-to-linux-in-windows-mastering-wsl-2-techniques/"><u>Proactive Approaches to Linux in Windows: Mastering WSL 2 Techniques</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolution-fixing-invalid-inf-install-section/"><u>Resolution: Fixing Invalid INF Install Section</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-unsupported-hardware-error-messages-with-your-idt-software/"><u>Resolving Unsupported Hardware Error Messages with Your IDT Software</u></a></li>
<li><a href="https://driver-error.techidaily.com/silent-keyboard-lights-asus/"><u>Silent Keyboard Lights ASUS</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-screen-reset-on-windows-with-elan-tablet-driver/"><u>Solving Screen Reset on Windows with Elan Tablet Driver</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-guide-booting-into-safe-mode-and-removing-nvidiaamd-gpu-drivers-on-windows-8/"><u>Step-by-Step Guide: Booting Into Safe Mode & Removing NVIDIA/AMD GPU Drivers on Windows 8</u></a></li>
<li><a href="https://driver-error.techidaily.com/successfully-solving-the-missing-cpu-module-driver-problem-for-windows-11-users/"><u>Successfully Solving the Missing CPU Module Driver Problem for Windows 11 Users</u></a></li>
<li><a href="https://driver-error.techidaily.com/systems-resource-inventory-shortfall/"><u>System's Resource Inventory Shortfall</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/the-best-methods-to-unlock-the-iphone-locked-to-owner-for-iphone-xs-max-drfone-by-drfone-ios/"><u>The Best Methods to Unlock the iPhone Locked to Owner for iPhone XS Max | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/the-complete-tutorial-upgrading-and-downloading-drivers-for-hps-envy-13-15-and-17-series-computers/"><u>The Complete Tutorial: Upgrading and Downloading Drivers for HP's Envy 13, 15, and 17 Series Computers</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/top-youtube-hashtag-strategies-for-boosting-your-contents-visibility-for-2024/"><u>Top Youtube Hashtag Strategies for Boosting Your Content's Visibility for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-adb-error-on-windows-xp/"><u>Troubleshooting ADB Error on Windows XP</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-tips-solve-constant-palworld-game-crashes-on-your-computer/"><u>Troubleshooting Tips: Solve Constant PalWorld Game Crashes on Your Computer</u></a></li>
<li><a href="https://driver-error.techidaily.com/unifying-experience-corrected-asus-webcam-link-to-w10-os/"><u>Unifying Experience: Corrected Asus Webcam Link to W10 OS</u></a></li>
</ul></div>
