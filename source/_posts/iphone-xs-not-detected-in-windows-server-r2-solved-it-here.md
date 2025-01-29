---
title: IPhone XS Not Detected in Windows Server R2, Solved It Here
date: 2025-01-28T16:14:44.783Z
updated: 2025-01-29T19:55:47.640Z
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
<li><a href="https://driver-error.techidaily.com/fixed-non-shining-asus-keys/"><u>[FIXED] Non-Shining Asus Keys</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-top-10-tips-recording-your-youtube-livestreams/"><u>[New] In 2024, Top 10 Tips Recording Your Youtube Livestreams</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-the-driver-detected-a-controller-error-on-deviceharddisk1dr1-or-dr3/"><u>[Solved] The Driver Detected a Controller Error on DeviceHarddisk1DR1 or DR3</u></a></li>
<li><a href="https://driver-error.techidaily.com/update-hardware-and-dev-driver-operational-on-win/"><u>[Update: Hardware & Dev Driver Operational on Win</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-terminology-trek-through-the-virtual-landscape/"><u>[Updated] Terminology Trek Through the Virtual Landscape</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-zooming-in-with-confidence-a-kinemaster-cinematographers-handbook/"><u>2024 Approved Zooming in with Confidence A Kinemaster Cinematographer's Handbook</u></a></li>
<li><a href="https://win-web3.techidaily.com/1728477102639-aomei/"><u>迷你指南：啟用 AOMEI 逆向重建並確定影片壓縮格式</u></a></li>
<li><a href="https://driver-download.techidaily.com/how-to-update-your-logitech-brio-webcam-driver-for-windows-7-8-or-10-free-download-guide/"><u>How to Update Your Logitech Brio Webcam Driver for Windows 7, 8 or 10 - Free Download Guide</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722974743520-install-the-latest-epson-wf-2630-drivers-on-your-pc-running-windows-7-8-or-10-heres-how/"><u>Install the Latest Epson WF-2630 Drivers on Your PC Running Windows 7, 8, or 10 - Here's How</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/kinemasters-secret-to-meme-making-mastery-for-2024/"><u>KineMaster's Secret to Meme-Making Mastery for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/large-client-withdrawals-cause-asetek-to-stop-providing-earnings-projections/"><u>Large Client Withdrawals Cause Asetek to Stop Providing Earnings Projections</u></a></li>
<li><a href="https://driver-error.techidaily.com/mastered-the-challenge-of-error-45/"><u>Mastered the Challenge of Error #45</u></a></li>
<li><a href="https://fox-within.techidaily.com/navigating-requirements-configuring-your-pre-install-setup-interface/"><u>Navigating Requirements: Configuring Your Pre-Install Setup Interface</u></a></li>
<li><a href="https://driver-error.techidaily.com/nvidia-drivers-installed-smoothly/"><u>Nvidia Drivers Installed Smoothly</u></a></li>
<li><a href="https://driver-error.techidaily.com/purging-illegal-configurations-from-inf-service-section/"><u>Purging Illegal Configurations From INF Service Section</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-adding-the-required-drivers-to-operate-devices-on-windows-1187-systems/"><u>Resolved: Adding the Required Drivers to Operate Devices on Windows 11/8/7 Systems</u></a></li>
<li><a href="https://driver-error.techidaily.com/silenced-hard-drive-error-signals/"><u>Silenced Hard Drive Error Signals</u></a></li>
<li><a href="https://driver-error.techidaily.com/successful-resolution-of-asus-webcam-on-windows-10/"><u>Successful Resolution of ASUS Webcam on Windows 10</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlocking-made-easy-the-best-10-apps-for-unlocking-your-lenovo-thinkphone-device-by-drfone-android/"><u>Unlocking Made Easy The Best 10 Apps for Unlocking Your Lenovo ThinkPhone Device</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

