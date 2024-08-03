---
title: Correcting Realtek'enas Unsupported Driver Issue
date: 2024-08-02T07:29:43.433Z
updated: 2024-08-03T07:29:43.433Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Correcting Realtek'enas Unsupported Driver Issue
excerpt: This Article Describes Correcting Realtek'enas Unsupported Driver Issue
thumbnail: https://thmb.techidaily.com/3fc14c15f73df5f4c8b19f8291c51668294576df82a5964da7eda1f1831694f2.jpg
---

## Correcting Realtek'enas Unsupported Driver Issue

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b91ef1806793.jpg)

 Users have reported that their Realtek PCIe Family Controller (Ethernet) randomly stopped working after they upgraded to Windows 10\. There are still no answers from Microsoft or Realtek as to why would this happen, and this situation happens randomly on different occasions, so there are a lot of solutions that could be of help.

 If this is the problem you are experiencing now, please follow the instructions below to get it fixed by yourself.

[**Option One: Reset TCP/IP**](https://natural-cycles.sjv.io/vmebmr)
[**Option Two: Change Settings in Network Adapter Properties**](https://aofit.pxf.io/mmjyxq)
[**Option Three: Reinstall Realtek Adapter Driver**](https://westkiss.pxf.io/daqnaq)
[**Option Four: Update the Realtek Driver**](https://newchic.sjv.io/jzg4zq)

---

<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Option One: Reset TCP/IP**

1) On your keyboard, press the**Windows logo key** , type**cmd** , right-click**Command Prompt** from the results, and select**Run as administrator** .  
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
![how to open Command Prompt as an admin](https://images.drivereasy.com/wp-content/uploads/2023/10/win11-Command-Prompt-Run-as-administrator.jpg)

 When prompted with the following notification, hit**Yes** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de25ac8c94.jpg)

 2) Type in the following command:

netsh int ip reset c:\resetlog.txt

 Make sure that you have made no typo and hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de2ea5a2ef.png)

 This will help you reset your TCP/IP (Transmission Control Protocol/Internet Protocol). To make it easier to understand, TCP/IP is the language that your computer uses to communicate with the outside world. Reseting TCP/IP will help you revert your Internet settings to the stage where it still works.

---

### **Option Two:** **Change Settings in Network Adapter Properties**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand category**Network adapters** .

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
3) Then right-click Realtek PCIe GBE Family Controller option and choose **Properties** .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de65b229a9.png)

 4) Go to**Advanced** tab, then choose**Speed & Duplex** option on the left side of the pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de6ed4d026.png)

 5) On the**Value** bar, change the default Auto Negotiation to **100 Mbps Full Duplex**  or some other options accordingly. We chose**100 Mbps Full Duplex** here, but yours could be different.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deb007e7e1.png)

 6) Now on the left side of the pane, choose**Energy Efficient Ethernet** option, then change the Value to**Disabled** . After the changes, hit**OK** to save.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deab52d9e0.png)

 7) Still, in the**Properties** window, this time, let’s go to**Power Management** tab. Un-tick the box for**Allow the computer to turn off this device to save power** . Then hit**OK** to save and exit.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587decc3276b5.png)

---

### **Option Three:** **Reinstall or Rollback Realtek Adapter Driver**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand the category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .
<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

 Hit**OK** to continue.
<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)

 4) Go to the menu bar on the top and click the button for **Scan for hardware changes** .  
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee9a707c2.png)

 5) Windows will help you automatically install the correct driver that it can find. But there is no guarantee that the new driver is going to work since Windows has provided the not working one originally.

 If you clearly remember that your Ethernet stops working after you update to a certain version of the driver, it is suggested that you roll it back to the stage where it was working well.

---

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
### **Option Four: Update the Realtek Driver**

 The steps above may help you resolve the issue, but if they don’t, you can try to update the Realtek driver. If you don’t have time, patience, or computer skills to update the driver manually,  you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/) .**

**IMPORTANT:**  If you can’t have access to the internet due to the network driver issues, you can use **[Driver Easy Offline Scan Feature](https://tools.techidaily.com/drivereasy/download/)**  to download and install a new network driver.

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version, it takes just 2 clicks (and you get full support and a 30-day money-back guarantee):

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2023/03/Driver-Easy-download-needed-1200x900.jpg)

 3) Click the **Update** button next to the Realtek PCIe driver to automatically download the correct version of this driver, then you can manually install it (you can do this with the FREE version).

 Or click **Update All**  to automatically download and install the correct version of _all_   the drivers that are missing or out of date on your system (this requires the Pro version – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2020/11/update-network-adapter-driver.jpg)

 Hopefully the tips above help you fix the Realtek Ethernet Controller driver not working issue. If you have any questions or ideas, feel free to leave your comments below, please.

* [Realtek](https://store.drivereasy.com/order/cart.php?PRODS=4731822&QTY=1&AFFILIATE=108875)

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
<li><a href="https://facebook-record-videos.techidaily.com/new-mastering-personalized-youtube-channel-urls-simple-steps-guide/"><u>[New] Mastering Personalized YouTube Channel URLs  Simple Steps Guide</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-the-quickest-way-to-entertain-kapwing-memes/"><u>[Updated] In 2024, The Quickest Way to Entertain - Kapwing Memes</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-keeping-your-audience-engaged-in-a-revised-social-lands-ward/"><u>2024 Approved  Keeping Your Audience Engaged in a Revised Social Lands Ward</u></a></li>
<li><a href="https://howto.techidaily.com/8-solutions-to-solve-youtube-app-crashing-on-oppo-find-x7-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Solutions to Solve YouTube App Crashing on Oppo Find X7 | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721098332496-bluetooth-unresponsive-windows-10-a-step-by-step-guide/"><u>Bluetooth Unresponsive – Windows 10: A Step by Step Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/boost-your-pc-with-new-razer-deadriver-on-windows-10/"><u>Boost Your PC with New Razer DeaDriver on Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/device-compatibility-flaws-wudfrd-loading-issue-id-219/"><u>Device Compatibility Flaws, WudfRd Loading Issue ID: 219</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/does-galaxy-s23-support-avchd-video-by-aiseesoft-video-converter-play-mts-on-android/"><u>Does Galaxy S23 support AVCHD video?</u></a></li>
<li><a href="https://driver-error.techidaily.com/easy-instructions-how-to-install-driver-updates-for-the-hp-envy-20-laptop/"><u>Easy Instructions: How to Install Driver Updates for the HP Envy 20 Laptop</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/elevate-your-content-game-with-these-instagram-story-tips-for-2024/"><u>Elevate Your Content Game with These Instagram Story Tips for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/enhance-dell-pointer-efficacy-win7/"><u>Enhance Dell Pointer Efficacy (Win7)</u></a></li>
<li><a href="https://driver-error.techidaily.com/expert-tips-for-diagnosing-and-repairing-the-dll-rpc-server-process-failure-on-windows-vista-and-7/"><u>Expert Tips for Diagnosing and Repairing the 'DLL RPC Server Process' Failure on Windows Vista & 7</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721097052069-fix-your-gpu-problem-for-better-gameplay-solution-inside/"><u>Fix Your GPU Problem for Better Gameplay - Solution Inside!</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-the-windows-7-blue-screen-error-code-0x0000007e/"><u>Fixing the Windows 7 'Blue Screen' Error Code 0X0000007E</u></a></li>
<li><a href="https://driver-error.techidaily.com/guide-to-efficiently-downloading-and-installing-new-drivers-for-your-hp-envy-20-computer/"><u>Guide to Efficiently Downloading and Installing New Drivers for Your HP ENVY 20 Computer</u></a></li>
<li><a href="https://driver-error.techidaily.com/hdr-sound-ready-error-cleared-on-bus/"><u>HDR Sound Ready: Error Cleared on Bus</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-fix-headset-no-sound-on-win10-system/"><u>How To Fix Headset No Sound on WIN10 System</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-fix-iphones-external-storage-connectivity-via-usb-an-ultimate-guide/"><u>How to Fix iPhone's External Storage Connectivity via USB: An Ultimate Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-solve-wireless-keyboard-problems-with-your-windows-computer-easily/"><u>How to Solve Wireless Keyboard Problems with Your Windows Computer Easily</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-update-or-downgrade-iphone-x-without-losing-anything-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade iPhone X Without Losing Anything? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/identify-missing-your-drivers-with-windows-device-manager-on-windows-11107-by-drivereasy-guide/"><u>Identify missing your drivers with Windows Device Manager on Windows 11/10/7</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-2024-discover-cost-free-vfx-wonders-on-the-net/"><u>In 2024, Discover Cost-Free VFX Wonders on the Net</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-how-to-turn-your-smartphone-into-a-virtual-reality-vr-headset/"><u>In 2024, How to Turn Your Smartphone Into a Virtual Reality (VR) Headset</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-ultimate-guide-to-crypto-conversion-best-generator-list/"><u>In 2024, The Ultimate Guide to Crypto Conversion – Best Generator List</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-10-fingerprint-lock-apps-to-lock-your-samsung-galaxy-s23-phone-by-drfone-android/"><u>In 2024, Top 10 Fingerprint Lock Apps to Lock Your Samsung Galaxy S23 Phone</u></a></li>
<li><a href="https://driver-error.techidaily.com/mastering-touchpad-fixes-for-windows-users-with-elan/"><u>Mastering Touchpad Fixes for Windows Users with Elan</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/network-locked-sim-card-inserted-on-your-oneplus-12-phone-unlock-it-now-by-drfone-android/"><u>Network Locked SIM Card Inserted On Your OnePlus 12 Phone? Unlock It Now</u></a></li>
<li><a href="https://driver-error.techidaily.com/newly-installed-compatible-and-reliable-nvidia-drivers/"><u>Newly Installed: Compatible and Reliable Nvidia Drivers</u></a></li>
<li><a href="https://driver-error.techidaily.com/remedied-video-ram-access-interruptions/"><u>Remedied Video RAM Access Interruptions</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-crash-and-restore-the-default-radeon-wattman-configuration-fixed/"><u>Resolving 'Crash & Restore': The Default Radeon Wattman Configuration Fixed</u></a></li>
<li><a href="https://extra-tips.techidaily.com/supreme-seminar-strategist-summit/"><u>Supreme Seminar Strategist Summit</u></a></li>
<li><a href="https://driver-error.techidaily.com/trouble-with-your-logitech-brio-webcam-post-windows-creators-upgrade-heres-what-i-did-to-find-a-solution-solved/"><u>Trouble with Your Logitech Brio Webcam? Post Windows Creators Upgrade – Here's What I Did to Find a Solution (Solved)</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-guide-resolving-issues-with-unrecognized-final-usb-device-on-windows/"><u>Troubleshooting Guide: Resolving Issues with Unrecognized Final USB Device on Windows</u></a></li>
<li><a href="https://driver-error.techidaily.com/unlocking-potential-lenovo-bt-driver-for-win10/"><u>Unlocking Potential: Lenovo BT Driver for Win10</u></a></li>
<li><a href="https://driver-error.techidaily.com/weve-found-a-quick-resolution-for-your-gpu-related-gaming-woes/"><u>We've Found a Quick Resolution for Your GPU-Related Gaming Woes</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-fake-gps-location-pro-and-is-it-good-on-honor-magic-5-lite-drfone-by-drfone-virtual-android/"><u>What is Fake GPS Location Pro and Is It Good On Honor Magic 5 Lite? | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-11-error-code-eliminated-irql/"><u>Windows 11 Error Code Eliminated: IRQL</u></a></li>
</ul></div>
