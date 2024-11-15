---
title: MacBook Pro Air Unsupported in Ubuntu Mate 20.04 [Solved]
date: 2024-11-13T02:06:08.397Z
updated: 2024-11-14T18:02:54.049Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes MacBook Pro Air Unsupported in Ubuntu Mate 20.04 [Solved]
excerpt: This Article Describes MacBook Pro Air Unsupported in Ubuntu Mate 20.04 [Solved]
thumbnail: https://thmb.techidaily.com/daf5ba2a8491ccb029544c33871dfddf8c00a96e763bab0af0faf409f9f29c9c.jpg
---

## MacBook Pro Air Unsupported in Ubuntu Mate 20.04 [Solved]

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
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-innovative-integration-select-the-top-6-editing-apps-post-snow-leopard/"><u>[New] In 2024, Innovative Integration Select the Top 6 Editing Apps Post-Snow Leopard</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-uncomplicated-multisnap-storytelling-on-snapchat-for-2024/"><u>[New] Uncomplicated Multisnap Storytelling on Snapchat for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-a-stepwise-approach-to-twitter-archive-utilization-for-2024/"><u>[Updated] A Stepwise Approach to Twitter Archive Utilization for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-mastering-photo-editing-unveiling-clear-images-with-photopea/"><u>[Updated] In 2024, Mastering Photo Editing Unveiling Clear Images with Photopea</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/best-3-oneplus-nord-ce-3-lite-5g-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>Best 3 OnePlus Nord CE 3 Lite 5G Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/comparatif-des-images-matricielles-vs-vecteur-comprendre-les-distinctions-cles/"><u>Comparatif Des Images Matricielles vs Vecteur: Comprendre Les Distinctions Clés</u></a></li>
<li><a href="https://driver-error.techidaily.com/demystifying-the-legacy-usb-composite-device-problems-now-fixed/"><u>Demystifying the Legacy USB Composite Device Problems - Now Fixed!</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-transform-still-photos-using-illustration-for-dynamic-effects/"><u>In 2024, Transform Still Photos Using Illustration for Dynamic Effects</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-two-ways-to-sync-contacts-from-samsung-galaxy-z-flip-5-to-gmail-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Two Ways to Sync Contacts from Samsung Galaxy Z Flip 5 to Gmail | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/mastering-amd-radeon-wattman-overcoming-configuration-setbacks-and-resets/"><u>Mastering AMD Radeon Wattman: Overcoming Configuration Setbacks & Resets</u></a></li>
<li><a href="https://driver-error.techidaily.com/navigating-and-fixing-ndis-on-pcs-swiftly/"><u>Navigating and Fixing NDIS on PCs Swiftly</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-glitches-lenovo-in-windows-10/"><u>Overcoming Glitches: Lenovo in Windows 10</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/perfect-viewer-experience-watching-lord-of-the-rings-series-correctly/"><u>Perfect Viewer Experience: Watching 'Lord of the Rings' Series Correctly</u></a></li>
<li><a href="https://driver-error.techidaily.com/reclaim-absent-discs-and-drives-from-windows-1110/"><u>Reclaim Absent Discs & Drives From Windows 11/10</u></a></li>
<li><a href="https://driver-error.techidaily.com/run-a-system-file-checker-scan-to-verify-and-repair-corrupted-files/"><u>Run a System File Checker Scan to Verify and Repair Corrupted Files.</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-navigate-and-fix-your-qualcomm-atheros-bluetooth-driver-problems-now/"><u>Windows Navigate and Fix Your Qualcomm Atheros Bluetooth Driver Problems Now</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1815679/21290" target="_top" id="1815679">
  <img src="//a.impactradius-go.com/display-ad/21290-1815679" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://versadesk.pxf.io/i/5597632/1815679/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

