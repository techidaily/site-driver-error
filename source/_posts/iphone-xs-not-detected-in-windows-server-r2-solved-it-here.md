---
title: IPhone XS Not Detected in Windows Server R2, Solved It Here
date: 2024-09-04T12:51:29.183Z
updated: 2024-09-05T12:51:29.183Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes IPhone XS Not Detected in Windows Server R2, Solved It Here
excerpt: This Article Describes IPhone XS Not Detected in Windows Server R2, Solved It Here
thumbnail: https://thmb.techidaily.com/637640ea893a93e111b973883d0f05d3166b54a33cafa8864cd2873a58b515ce.png
---

## IPhone XS Not Detected in Windows Server R2, Solved It Here

 **Quick Through: [Method One: If you see a  or  by the Apple Mobile Device USB Driver](https://images.drivereasy.com/wp-content/uploads/2016/09/yellow-exclmation-mark.png) or ![](https://images.drivereasy.com/wp-content/uploads/2016/09/iphone-7-not-recognized-by-windows-7-question-mark.png) by the Apple Mobile Device USB Driver](#1)** **[Method Two: If you don’t see ,  or  by the Apple Mobile Device USB Driver](https://images.drivereasy.com/wp-content/uploads/2016/09/img_57cfc2b7b55a1.png) , ![](https://images.drivereasy.com/wp-content/uploads/2016/09/yellow-exclmation-mark.png) or ![](https://images.drivereasy.com/wp-content/uploads/2016/09/img_57cfc2cc4c57a.png) by the Apple Mobile Device USB Driver](#2)** **[Method Three: If you see  next to the Apple Mobile Device USB Driver](https://images.drivereasy.com/wp-content/uploads/2016/09/img_57cfc3cc786ff.png) next to the Apple Mobile Device USB Driver](#3)** **[Method Four: If your iPhone is listed under Other device and with a  next to it](https://images.drivereasy.com/wp-content/uploads/2016/09/yellow-exclmation-mark.png) next to it](#4)** iPhone users may have encountered this situation before: you connect your iPhone to your computer, you have clicked the**Trust**button on your device, but you cannot see iPhone on**My Computer**. This is what it should look like if iPhone is detected by Windows.

![](https://images.drivereasy.com/wp-content/uploads/2016/09/apple-iphone-in-windows-7.jpg)

In **Devices and Printers(Control Panel > Hardware and Sound > Devices and Printers)**, it appears under the**Unspecified**category as**Apple Mobile Device USB Driver**.

![](https://images.drivereasy.com/wp-content/uploads/2016/09/apple-mobile-device-usb-driver-in-unspecified.jpg)

Luckily, this is not a hard problem to tackle. Before we begin, we need to make sure that you have done the following things properly. 1) Make sure that you have **[the latest version of iTunes](https://support.apple.com/kb/HT201352)** that works on your computer.

![](https://images.drivereasy.com/wp-content/uploads/2016/09/get-the-latest-version-of-itunes.jpg)

2) Check that you have the latest software on your Windows 7\. You can check the if there are available updates on your computer by the path**Control Panel > System and Security > Windows Update**.

![](https://images.drivereasy.com/wp-content/uploads/2016/09/windows-update-in-windows-7.jpg)

3) Press**Trust**on your iPhone.

![](https://images.drivereasy.com/wp-content/uploads/2016/09/trust-this-computer-on-iphone.jpg)

4) Make sure that your device is turned on. 5) Try other USB cables or USB ports to see if iPhone can be detected.   **Method One: Manually Update Apple Mobile Device USB Driver**This method is adopted when you see a ![](https://images.drivereasy.com/wp-content/uploads/2016/09/yellow-exclmation-mark.png) or ![](https://images.drivereasy.com/wp-content/uploads/2016/09/iphone-7-not-recognized-by-windows-7-question-mark.png) by the**Apple Mobile Device USB Driver**.

![](https://images.drivereasy.com/wp-content/uploads/2016/09/img_57cfc1d3812c4.png)

1) Go to **[Device Manager](https://tools.techidaily.com/drivereasy/download/)** . 2) Expand category**Universal Serial Bus controllers**.

![](https://images.drivereasy.com/wp-content/uploads/2016/09/img_57cfc066b0a94.png)

3) Double click**Apple Mobile Device USB Driver**. 4) In**Driver**tab, click**Update Driver…**option. ![](https://images.drivereasy.com/wp-content/uploads/2016/09/update-driver-apple-mobile-device-usb-driver-properties.png) 5) Choose**Browse my computer for driver software**. ![](https://images.drivereasy.com/wp-content/uploads/2016/09/browse-my-computer-for-driver-software-600x439.png) 6) Then choose**Let me pick from a list of device drivers on my computer**.

![](https://images.drivereasy.com/wp-content/uploads/2016/09/let-me-pick-from-a-list-of-device-drivers-on-my-computer-600x439.png)

7) In**Apple Mobile Device USB Driver**category, choose**Have disk…**option. If the**Have Disk…** option is unavailable under**Apple Mobile Device USB Driver** category, choose a device category such as**Mobile Phone**or**Storage Device**, if that’s what you can see.

![](https://images.drivereasy.com/wp-content/uploads/2016/09/apple-mobile-device-usb-driver-category-600x439.png)

8) Click**Browse**. ![](https://images.drivereasy.com/wp-content/uploads/2016/09/browse-for-inf-file.png) 9) Then navigate to   **C:\\Program Files\\Common Files\\Apple\\Mobile Device Support\\Drivers** . Double click the**usbaapl** file. If you are running a 64-bit version of Windows, this file will be called**usbaapl64** . If you don’t see**usbaapl64**here or if there isn’t a**Drivers**folder, look in **C:\\Program Files (x86)\\Common Files\\Apple\\Mobile Device Support\\Drivers**.

![](https://images.drivereasy.com/wp-content/uploads/2016/09/have-disk-usbaapl64.png)

10) In the**Have Disk**window, click**OK**. ![](https://images.drivereasy.com/wp-content/uploads/2016/09/img_57cfba2f3f906.png) 11) Then click**Next**. Windows will help you with the driver update after this.

![](https://images.drivereasy.com/wp-content/uploads/2016/09/next-to-finish-the-install-process-600x439.png)

12) Open iTunes now to see if it recognizes your iPhone.   **Method Two: Restart the Apple Mobile Device Service** This method applies when you see this notification when connecting your device to PC: **This iPhone cannot be used because the Apple Mobile Device Service is not started**.

![](https://images.drivereasy.com/wp-content/uploads/2016/09/this-iphone-cannot-be-used-because-the-apple-mobile-device-service-is-not-started.png) This method also applies when you don’t see ![](https://images.drivereasy.com/wp-content/uploads/2016/09/img_57cfc2b7b55a1.png) , ![](https://images.drivereasy.com/wp-content/uploads/2016/09/yellow-exclmation-mark.png) or ![](https://images.drivereasy.com/wp-content/uploads/2016/09/img_57cfc2cc4c57a.png) by the **Apple Mobile Device USB Driver** .  1) Close iTunes and disconnect your iPhone from your PC.

2) Press**Windows key**and**R**at the same time to invoke a Run command, then type**services.msc**in and hit**Enter**. ![](https://images.drivereasy.com/wp-content/uploads/2016/09/img_57cfbd4cbc7ad.png) 3) Locate and double click**Apple Mobile Device Service**.![](https://images.drivereasy.com/wp-content/uploads/2016/09/apple-mobile-device-service.jpg) 4) Change the**Startup type**to**Automatic**. ![](https://images.drivereasy.com/wp-content/uploads/2016/09/startup-type-to-automatic.jpg) 5) Click**Stop**the service.![](https://images.drivereasy.com/wp-content/uploads/2016/09/stop-the-service.png) 6) After the service stops, click**Start**the service.![](https://images.drivereasy.com/wp-content/uploads/2016/09/start-the-service.png) 7) Click**OK**.![](https://images.drivereasy.com/wp-content/uploads/2016/09/ok-to-save-the-change.png)

8) Restart your computer.

9) Open your iTunes and connect your iPhone to your computer.   **Method Three: Enable Apple Mobile Device USB Driver** If you see ![](https://images.drivereasy.com/wp-content/uploads/2016/09/img_57cfc3cc786ff.png) next to the **Apple Mobile Device USB Driver**, this method applies to your situation. 1) Go to **[Device Manager](https://tools.techidaily.com/drivereasy/download/)** . 2) Expand**Universal Serial Bus controllers**.![](https://images.drivereasy.com/wp-content/uploads/2016/09/expand-universal-serial-bus-controllers.png) 3) Right click **Apple Mobile Device USB Driver** and choose**Enable**. ![](https://images.drivereasy.com/wp-content/uploads/2016/09/apple-mobile-device-usb-driver-enable.png)   **Method Four: Update iPhone Driver**This method applies when you see your iPhone listed under**Portable Device** instead of**Universal Serial Bus controllers**and with a yellow exclamation mark next to it.![](https://images.drivereasy.com/wp-content/uploads/2016/09/portable-device-with-yellow-exclamation-mark.png) It is highly recommended that you use [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) to scan and download drivers that you need for free. If your iPhone is not showing in the correct position and your computer says it is already the latest version of device driver that Windows can find, then you need to give a try of **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)** . Driver Easy is a free software to use. As the name suggests, it is very easy to use. There are only two steps involved. 1) Click**Scan Now**button to scan for the new drivers available. ![](https://images.drivereasy.com/wp-content/uploads/2017/03/img_58da3829b5cbb.png) 2) Click the**Update**button next to**Apple Mobile Device USB Driver** and wait for Driver Easy to help you with the device driver update. ![](https://images.drivereasy.com/wp-content/uploads/2017/03/img_58da383c4afde.jpg)

That’s all you need to do.

In addition, Driver Easy is a totally free software to use. But if you are looking for more features and professional tech support, you can have a try at our **[professional version](https://tools.techidaily.com/drivereasy/download/)** . If you are not satisfied with Driver Easy at the end, you can always ask for a refund within thirty days.

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
<li><a href="https://facebook-video-files.techidaily.com/new-feed-flourish-elevating-engagement-from-ordinary-posts/"><u>[New] Feed Flourish  Elevating Engagement From Ordinary Posts</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-in-2024-unparalleled-quality-discover-the-best-8-streamer-cameras/"><u>[New] In 2024, Unparalleled Quality  Discover the Best 8 Streamer Cameras</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-the-ultimate-framework-for-crafting-compelling-live-video-thumbnails/"><u>[New] The Ultimate Framework for Crafting Compelling Live Video Thumbnails</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-unraveling-monetization-strategies-in-the-realm-of-video-shorts/"><u>[New] Unraveling Monetization Strategies in the Realm of Video Shorts</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-responsive-input-on-fixd-windows-11-pc/"><u>[Resolved]: Responsive Input on Fix'd Windows 11 PC</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-cant-find-the-name-of-intel-icd-opengl-driver/"><u>[SOLVED] Can't Find the Name of Intel ICD OpenGL Driver</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-the-third-party-inf-does-not-contain-digital-signature-information/"><u>[SOLVED] The Third-Party INF Does Not Contain Digital Signature Information</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-achieving-video-greatness-on-tiktok-with-smart-use-of-pre-made-templates/"><u>[Updated] 2024 Approved  Achieving Video Greatness on TikTok with Smart Use of Pre-Made Templates</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-cutting-edge-techniques-for-bypassing-obscuring-elements-in-affinity-photo/"><u>[Updated] 2024 Approved  Cutting-Edge Techniques for Bypassing Obscuring Elements in Affinity Photo</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-evaluating-every-aspect-of-du-recorder-design-and-function/"><u>[Updated] Evaluating Every Aspect of Du Recorder Design & Function</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-expert-advice-for-improved-minecraft-zooms/"><u>[Updated] Expert Advice for Improved Minecraft Zooms</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-a-complete-guide-to-twitter-archive-mastery/"><u>[Updated] In 2024, A Complete Guide to Twitter Archive Mastery</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-dissecting-sharex-opinions-and-picks/"><u>[Updated] In 2024, Dissecting ShareX  Opinions & Picks</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-in-depth-guide-to-frozen-pleasure-viewing-tools/"><u>[Updated] In 2024, In-Depth Guide to Frozen Pleasure Viewing Tools</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-leveraging-lut-technology-in-adobe-premiere/"><u>[Updated] Leveraging LUT Technology in Adobe Premiere</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-basics-of-animated-infographics-and-signage/"><u>2024 Approved  Basics of Animated Infographics and Signage</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-crossplatform-audiomagic-2023/"><u>2024 Approved  CrossPlatform AudioMagic 2023</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/4-easy-ways-for-your-vivo-y78-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>4 Easy Ways for Your Vivo Y78 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/all-must-knows-to-use-fake-gps-go-location-spoofer-on-infinix-smart-8-drfone-by-drfone-virtual-android/"><u>All Must-Knows to Use Fake GPS GO Location Spoofer On Infinix Smart 8 | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/asus-desktop-and-laptops-troubleshooting-fixing-inverted-video-problems/"><u>Asus Desktop and Laptops Troubleshooting: Fixing Inverted Video Problems</u></a></li>
<li><a href="https://driver-error.techidaily.com/bootloader-interrupt-process-improved/"><u>Bootloader Interrupt Process Improved</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/bumble-success-hack-increase-your-chances-of-getting-matched/"><u>Bumble Success Hack: Increase Your Chances of Getting Matched</u></a></li>
<li><a href="https://driver-error.techidaily.com/corrected-invalid-service-inf-issue/"><u>Corrected Invalid Service INF Issue</u></a></li>
<li><a href="https://driver-error.techidaily.com/dealing-with-access-issues-solutions-for-failed-usb-installs/"><u>Dealing With Access Issues: Solutions for Failed USB Installs</u></a></li>
<li><a href="https://driver-error.techidaily.com/dolby-advanced-audio-driver-not-working-in-windows-solved/"><u>Dolby Advanced Audio Driver Not Working in Windows [Solved]</u></a></li>
<li><a href="https://driver-error.techidaily.com/easy-setup-windows-plus-samsung-driver/"><u>Easy Setup: Windows + Samsung Driver</u></a></li>
<li><a href="https://driver-error.techidaily.com/error-code-45-triumphantly-resolved/"><u>Error Code 45: Triumphantly Resolved</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixed-usb-webcam-error-with-asus-model/"><u>Fixed USB Webcam Error with ASUS Model</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-a-top-down-image-displacement-on-an-asus-desktoplaptop/"><u>Fixing a Top-Down Image Displacement on an ASUS Desktop/Laptop</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-wireless-keyboard-issues-on-your-pc-a-step-by-step-guide/"><u>Fixing Wireless Keyboard Issues on Your PC: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/fresh-start-how-to-refresh-device-drivers-on-windows-10-without-hitches/"><u>Fresh Start: How to Refresh Device Drivers on Windows 10 Without Hitches</u></a></li>
<li><a href="https://driver-error.techidaily.com/gtx-950-code-43-malfunction-in-win10-diagnosis-and-repair-solutions/"><u>GTX 950 'Code 43' Malfunction in Win10 - Diagnosis and Repair Solutions</u></a></li>
<li><a href="https://driver-error.techidaily.com/guiding-users-through-driver-troubleshooting-dm/"><u>Guiding Users Through Driver Troubleshooting (DM)</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-overcome-the-unsupported-hardware-detected-error-in-idt-packages/"><u>How to Overcome the ‘Unsupported Hardware Detected’ Error in IDT Packages</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-infinix-smart-8-plus-phone-password-without-factory-reset-by-drfone-android/"><u>How to Unlock Infinix Smart 8 Plus Phone Password Without Factory Reset?</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-amplify-youtube-performance-rapid-video-rendering-guide/"><u>In 2024, Amplify YouTube Performance - Rapid Video Rendering Guide</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-apple-iphone-12-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Apple iPhone 12 Pro Max | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-from-samsung-galaxy-z-flip-5-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock from Samsung Galaxy Z Flip 5 Devices</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-fix-apple-iphone-14-unavailable-issue-with-ease-drfone-by-drfone-ios/"><u>In 2024, How To Fix Apple iPhone 14 Unavailable Issue With Ease | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-simplified-process-for-posting-imovie-videos-on-vimeo/"><u>In 2024, Simplified Process for Posting iMovie Videos on Vimeo</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-11-free-apps-to-check-imei-on-vivo-y36i-phones-by-drfone-android/"><u>In 2024, Top 11 Free Apps to Check IMEI on Vivo Y36i Phones</u></a></li>
<li><a href="https://driver-error.techidaily.com/installation-complete-printer-drivers-installed/"><u>Installation Complete: Printer Drivers Installed</u></a></li>
<li><a href="https://driver-error.techidaily.com/navigate-the-bios-tweaking-maze-razer-deathadder-in-windows-10/"><u>Navigate the BIOS Tweaking Maze: Razer Deathadder in Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/no-more-dead-keys-a-comprehensive-fix-for-broken-wireless-keyboards-on-pcs-with-windows-os/"><u>No More Dead Keys – A Comprehensive Fix for Broken Wireless Keyboards on PCs with Windows OS</u></a></li>
<li><a href="https://driver-error.techidaily.com/optimize-point-touch-response-time-dell-windows-7/"><u>Optimize Point-Touch Response Time (Dell, Windows 7)</u></a></li>
<li><a href="https://driver-error.techidaily.com/re-establish-connection-with-devices-in-winnt-40/"><u>Re-Establish Connection with Devices in WinNT 4.0</u></a></li>
<li><a href="https://driver-error.techidaily.com/reconnecting-devices-after-adb-failure/"><u>Reconnecting Devices After ADB Failure</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-gtx-ninety-five-error-code-forty-three-in-windows-eleven/"><u>Resolving GTX Ninety-Five Error Code Forty-Three in Windows Eleven</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-issues-when-your-final-usb-peripheral-fails-and-windows-ignores/"><u>Resolving Issues When Your Final USB Peripheral Fails & Windows Ignores</u></a></li>
<li><a href="https://driver-error.techidaily.com/simplified-fixes-to-overcome-itbm-driver-unavailable-dilemma/"><u>Simplified Fixes to Overcome 'ITBM Driver Unavailable' Dilemma</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-the-missing-pressed-button-in-windows/"><u>Solving the Missing Pressed Button in Windows</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-guide-finding-the-right-driver-to-connect-your-canon-dr-c22e-printer-with-windows-11108/"><u>Step-by-Step Guide: Finding the Right Driver to Connect Your Canon DR-C22e Printer with Windows 11/10/8</u></a></li>
<li><a href="https://driver-install.techidaily.com/streamlined-system-software-enhancements-for-w7/"><u>Streamlined System Software Enhancements for W7</u></a></li>
<li><a href="https://driver-error.techidaily.com/tackling-intermittent-nvidia-driver-crashes/"><u>Tackling Intermittent Nvidia Driver Crashes</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-guide-fixing-the-driver-not-found-issue-in-itbm-systems/"><u>Troubleshooting Guide: Fixing the 'Driver Not Found' Issue in ITBM Systems</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-geo-blocking-and-how-to-bypass-it-on-realme-12-5g-drfone-by-drfone-virtual-android/"><u>What is Geo-Blocking and How to Bypass it On Realme 12 5G? | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-11-hints-to-reveal-invisible-seagate-hd/"><u>Windows 11 Hints to Reveal Invisible Seagate HD</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-11-missing-coprocessor-drivers-fixes-and-guidance-provided/"><u>Windows 11 Missing Coprocessor Drivers - Fixes and Guidance Provided</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043639/7443" target="_top" id="2043639">
  <img src="//a.impactradius-go.com/display-ad/7443-2043639" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043639/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->