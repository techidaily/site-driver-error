---
title: Nexus One Non-Detection in Linux Mint Cinnamon, Solution Found!
date: 2024-10-26T22:26:41.604Z
updated: 2024-10-29T17:54:49.634Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Nexus One Non-Detection in Linux Mint Cinnamon, Solution Found!
excerpt: This Article Describes Nexus One Non-Detection in Linux Mint Cinnamon, Solution Found!
thumbnail: https://thmb.techidaily.com/de3aeccba8a1988fe712bc85cebc3af3bc3a21faab0414036ff801745dc15189.png
---

## Nexus One Non-Detection in Linux Mint Cinnamon, Solution Found

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
<li><a href="https://extra-guidance.techidaily.com/2024-approved-step-by-step-guide-to-3d-text-effects-in-psx/"><u>2024 Approved Step-by-Step Guide to 3D Text Effects in PSX</u></a></li>
<li><a href="https://driver-error.techidaily.com/bios-interrupt-resolution-complete/"><u>BIOS Interrupt Resolution Complete</u></a></li>
<li><a href="https://driver-error.techidaily.com/conquering-drive-distress-the-story-of-e52/"><u>Conquering Drive Distress: The Story of E52</u></a></li>
<li><a href="https://driver-error.techidaily.com/easy-steps-to-updatedownload-hp-envy-ebowarders/"><u>Easy Steps to Update/Download HP Envy Ebowarders</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/eight-outstanding-choices-for-private-video-communication-for-2024/"><u>Eight Outstanding Choices for Private Video Communication for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-venintanddev33a0-acpi-errors/"><u>Fixing VEN_INT&DEV_33A0 ACPI Errors</u></a></li>
<li><a href="https://tech-hub.techidaily.com/1722050626295-how-to-find-your-ideal-ai-chatbot-service-check-out-these-critical-7-features-first/"><u>How to Find Your Ideal AI Chatbot Service: Check Out These Critical 7 Features First!</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-restore-bluetooth-functionality-in-windows-10-with-qualcomm-atheros-drivers-step-by-step-fixes/"><u>How to Restore Bluetooth Functionality in Windows 10 with Qualcomm Atheros Drivers - Step by Step Fixes</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-honor-90-pro-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Honor 90 Pro to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-apply-these-techniques-to-improve-how-to-detect-fake-gps-location-on-samsung-galaxy-m54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Apply These Techniques to Improve How to Detect Fake GPS Location On Samsung Galaxy M54 5G | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-sign-out-of-apple-id-on-iphone-14-pro-max-without-password-by-drfone-ios/"><u>In 2024, How to Sign Out of Apple ID On iPhone 14 Pro Max without Password?</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-issue-initialization-failure-of-battleye-driver-fixing-error-code-1450/"><u>Resolved Issue: Initialization Failure of BattlEye Driver - Fixing Error Code 1450</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-the-mystery-of-non-functional-dolby-sound-in-your-pc-heres-how/"><u>Solving the Mystery of Non-Functional Dolby Sound in Your PC – Here’s How! ✅</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-11-free-apps-to-check-imei-on-infinix-smart-7-phones-by-drfone-android/"><u>Top 11 Free Apps to Check IMEI on Infinix Smart 7 Phones</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-guide-resolving-driver-load-error-during-initialization-of-battleye-service/"><u>Troubleshooting Guide: Resolving 'Driver Load Error' During Initialization of BattlEye Service</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/uncovering-budget-friendly-video-conferencing-tools-for-all-systems/"><u>Uncovering Budget-Friendly Video Conferencing Tools for All Systems</u></a></li>
<li><a href="https://sound-issues.techidaily.com/unstuck-with-no-volume-heres-how-to-fix-sound-problems-on-your-laptop/"><u>Unstuck with No Volume? Here's How to Fix Sound Problems on Your Laptop</u></a></li>
<li><a href="https://driver-error.techidaily.com/wacom-unplugged-no-more-devices-dance-together/"><u>Wacom Unplugged No More! Devices Dance Together</u></a></li>
<li><a href="https://some-guidance.techidaily.com/winx-dvd-ripper-pro-descargador-de-dvds-y-blu-ray-4k-ultra-rapido-para-sistemas-windows-11/"><u>WinX DVD Ripper Pro: Descargador De DVDs Y Blu-Ray 4K Ultra Rápido Para Sistemas Windows 11</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://oneplusfr.sjv.io/c/5597632/1622438/14044" target="_top" id="1622438">
  <img src="//a.impactradius-go.com/display-ad/14044-1622438" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://oneplusfr.sjv.io/i/5597632/1622438/14044" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

