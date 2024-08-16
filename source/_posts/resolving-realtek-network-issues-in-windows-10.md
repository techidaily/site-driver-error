---
title: Resolving Realtek Network Issues in Windows 10
date: 2024-08-15T06:44:04.032Z
updated: 2024-08-16T06:44:04.032Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Resolving Realtek Network Issues in Windows 10
excerpt: This Article Describes Resolving Realtek Network Issues in Windows 10
thumbnail: https://thmb.techidaily.com/cbf529e05dd3135fe67a52edb00f230c5ea15121620c8f38c53b6edc4bb0734a.jpg
---

## Resolving Realtek Network Issues in Windows 10

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b91ef1806793.jpg)

 Users have reported that their Realtek PCIe Family Controller (Ethernet) randomly stopped working after they upgraded to Windows 10\. There are still no answers from Microsoft or Realtek as to why would this happen, and this situation happens randomly on different occasions, so there are a lot of solutions that could be of help.

 If this is the problem you are experiencing now, please follow the instructions below to get it fixed by yourself.

[**Option One: Reset TCP/IP**](https://natural-cycles.sjv.io/vmebmr)
[**Option Two: Change Settings in Network Adapter Properties**](https://aofit.pxf.io/mmjyxq)
[**Option Three: Reinstall Realtek Adapter Driver**](https://westkiss.pxf.io/daqnaq)
[**Option Four: Update the Realtek Driver**](https://newchic.sjv.io/jzg4zq)

---

### **Option One: Reset TCP/IP**

1) On your keyboard, press the**Windows logo key** , type**cmd** , right-click**Command Prompt** from the results, and select**Run as administrator** .  
  
![how to open Command Prompt as an admin](https://images.drivereasy.com/wp-content/uploads/2023/10/win11-Command-Prompt-Run-as-administrator.jpg)

 When prompted with the following notification, hit**Yes** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de25ac8c94.jpg)

 2) Type in the following command:

netsh int ip reset c:\resetlog.txt

 Make sure that you have made no typo and hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de2ea5a2ef.png)

 This will help you reset your TCP/IP (Transmission Control Protocol/Internet Protocol). To make it easier to understand, TCP/IP is the language that your computer uses to communicate with the outside world. Reseting TCP/IP will help you revert your Internet settings to the stage where it still works.

---

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Option Two:** **Change Settings in Network Adapter Properties**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand category**Network adapters** .

<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
3) Then right-click Realtek PCIe GBE Family Controller option and choose **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de65b229a9.png)

 4) Go to**Advanced** tab, then choose**Speed & Duplex** option on the left side of the pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de6ed4d026.png)

 5) On the**Value** bar, change the default Auto Negotiation to **100 Mbps Full Duplex**  or some other options accordingly. We chose**100 Mbps Full Duplex** here, but yours could be different.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deb007e7e1.png)

 6) Now on the left side of the pane, choose**Energy Efficient Ethernet** option, then change the Value to**Disabled** . After the changes, hit**OK** to save.

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
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

 Hit**OK** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)

 4) Go to the menu bar on the top and click the button for **Scan for hardware changes** .  
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee9a707c2.png)

 5) Windows will help you automatically install the correct driver that it can find. But there is no guarantee that the new driver is going to work since Windows has provided the not working one originally.

 If you clearly remember that your Ethernet stops working after you update to a certain version of the driver, it is suggested that you roll it back to the stage where it was working well.

---

### **Option Four: Update the Realtek Driver**

 The steps above may help you resolve the issue, but if they don’t, you can try to update the Realtek driver. If you don’t have time, patience, or computer skills to update the driver manually,  you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/) .**

**IMPORTANT:**  If you can’t have access to the internet due to the network driver issues, you can use **[Driver Easy Offline Scan Feature](https://tools.techidaily.com/drivereasy/download/)**  to download and install a new network driver.

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version, it takes just 2 clicks (and you get full support and a 30-day money-back guarantee):

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://driver-error.techidaily.com/fixed-previous-software-conflict-leading-to-boot-failure/"><u>[FIXED] Previous Software Conflict Leading to Boot Failure</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-diaspora-user-visualization-measurements-format-length/"><u>[New] Diaspora User Visualization  Measurements, Format, Length</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-favorite-frameworks-top-instagram-filters/"><u>[New] Favorite Frameworks  Top Instagram Filters</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-the-essential-guide-to-twitters-video-converters/"><u>[New] In 2024, The Essential Guide to Twitters Video Converters</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-the-best-eight-free-translation-tools-unveiled/"><u>[New] The Best Eight Free Translation Tools Unveiled</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-key-to-unlocking-the-best-video-production-talents/"><u>[New] The Key to Unlocking the Best Video Production Talents</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-razer-mouse-freezing-on-windows-10/"><u>[Solved] Razer Mouse Freezing on Windows 10</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-how-to-amplify-facebook-stories-with-music-elements/"><u>[Updated] In 2024, How to Amplify Facebook Stories with Music Elements</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-harmonious-blends-using-fades-in-logic-pro-x/"><u>2024 Approved  Harmonious Blends  Using Fades in Logic Pro X</u></a></li>
<li><a href="https://driver-error.techidaily.com/306-we-see-all-this-year)/"><u>306, We See All This Year}}]></u></a></li>
<li><a href="https://unlock-android.techidaily.com/a-complete-guide-to-oem-unlocking-on-infinix-zero-30-5g-by-drfone-android/"><u>A Complete Guide To OEM Unlocking on Infinix Zero 30 5G</u></a></li>
<li><a href="https://driver-error.techidaily.com/address-bluetooth-driver-malfunction-on-xps-2-in-1/"><u>Address Bluetooth Driver Malfunction on XPS 2-In-1</u></a></li>
<li><a href="https://driver-error.techidaily.com/alleviate-io-scheduling-conflict/"><u>Alleviate I/O Scheduling Conflict</u></a></li>
<li><a href="https://driver-error.techidaily.com/amd-radeon-wattmans-sudden-shutdown-and-comeback-fixing-the-settings-glitch-effortlessly-complete-tutorial/"><u>AMD Radeon Wattman's Sudden Shutdown and Comeback: Fixing the Settings Glitch Effortlessly – Complete Tutorial</u></a></li>
<li><a href="https://driver-error.techidaily.com/asus-laptop-troubleshooting-solving-the-inverted-screen-problem/"><u>ASUS Laptop Troubleshooting: Solving the Inverted Screen Problem</u></a></li>
<li><a href="https://driver-error.techidaily.com/bring-back-surround-sound-experience-on-windows-10-fixed-your-non-functional-dts-truehd-driver-issue-done/"><u>Bring Back Surround Sound Experience on Windows 10 – Fixed Your Non-Functional DTS TrueHD Driver Issue - Done!✅</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/bring-your-vision-to-life-top-free-and-paid-3d-video-creators-for-2024/"><u>Bring Your Vision to Life Top Free and Paid 3D Video Creators for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721104340272-built-in-internal-wi-fi-and-bt-wont-stop-in-win10-need-help/"><u>Built-In Internal Wi-Fi and BT Won't Stop in Win10 – Need Help</u></a></li>
<li><a href="https://driver-error.techidaily.com/cross-platform-device-drivers-for-pci-devices/"><u>Cross-Platform Device Drivers for PCI Devices</u></a></li>
<li><a href="https://driver-error.techidaily.com/dealing-with-disappearing-cpu-co-processor-drivers-in-windows-11-fixes-and-tips/"><u>Dealing with Disappearing CPU Co-Processor Drivers in Windows 11 – Fixes and Tips</u></a></li>
<li><a href="https://driver-error.techidaily.com/device-party-wacom-connectivity-triumphant/"><u>Device Party: Wacom Connectivity Triumphant</u></a></li>
<li><a href="https://driver-error.techidaily.com/easy-steps-to-update-device-drivers-in-various-versions-of-windows/"><u>Easy Steps to Update Device Drivers in Various Versions of Windows</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/elevate-your-marketing-strategy-with-cookiebot-analytics-powerhouse/"><u>Elevate Your Marketing Strategy with Cookiebot Analytics Powerhouse</u></a></li>
<li><a href="https://article-helps.techidaily.com/elevate-your-vision-advanced-techniques-in-hdr-portraits/"><u>Elevate Your Vision  Advanced Techniques in HDR Portraits</u></a></li>
<li><a href="https://driver-error.techidaily.com/enhanced-performance-in-new-win11-os/"><u>Enhanced Performance in New Win11 OS</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/exploring-rumors-on-sonys-latest-virtual-reality-gear-release-info-price-guesses-and-specs-explained/"><u>Exploring Rumors on Sony's Latest Virtual Reality Gear: Release Info, Price Guesses & Specs Explained</u></a></li>
<li><a href="https://driver-error.techidaily.com/find-and-fix-driver-issues-a-step-by-step-guide-for-windows-11-8-and-7-users/"><u>Find and Fix Driver Issues: A Step-by-Step Guide for Windows 11, 8 & 7 Users</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-standard-vga-graphics-adapter-driver-issue-easily/"><u>Fix Standard VGA Graphics Adapter Driver Issue. Easily</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-video-controller-driver-issue-in-windows-11-easily/"><u>Fix Video Controller Driver Issue in Windows 11. Easily</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-ethernet-driver-not-working-after-upgrade/"><u>Fixing Ethernet Driver Not Working After Upgrade</u></a></li>
<li><a href="https://driver-error.techidaily.com/hardware-restriction-graphic-device-block-in-windows/"><u>Hardware Restriction: Graphic Device Block in Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-google-play-location-on-oppo-k11-5g-drfone-by-drfone-virtual-android/"><u>How to Change Google Play Location On Oppo K11 5G | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-fix-the-crash-and-recovery-of-default-amd-radeon-wattman-settings-comprehensive-solutions/"><u>How to Fix the 'Crash & Recovery' Of Default AMD Radeon Wattman Settings: Comprehensive Solutions</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-reset-a-locked-realme-11-proplus-phone-by-drfone-android/"><u>How to Reset a Locked Realme 11 Pro+ Phone</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-resolve-the-graphics-card-issue-code-43-on-your-windows-11-pc/"><u>How to Resolve the Graphics Card Issue (Code 43) on Your Windows 11 PC</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-oppo-reno-10-pro-5g-phone-password-without-factory-reset-by-drfone-android/"><u>How to Unlock Oppo Reno 10 Pro 5G Phone Password Without Factory Reset?</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-enhance-instagram-content-with-background-tracks/"><u>In 2024, Enhance Instagram Content with Background Tracks</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-frp-from-motorola-moto-g73-5g-by-drfone-android/"><u>In 2024, How to Bypass FRP from Motorola Moto G73 5G?</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-motorola-razr-40frp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Motorola Razr 40FRP Lock</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-the-ultimate-guide-to-xiaomi-redmi-note-12t-pro-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Ultimate Guide to Xiaomi Redmi Note 12T Pro Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://driver-error.techidaily.com/iphone-se-not-detected-on-fedora-core-os-solution-found-here/"><u>IPhone SE Not Detected on Fedora Core OS - Solution Found Here</u></a></li>
<li><a href="https://screen-recording.techidaily.com/latest-techniques-for-ios-iphoneipad-screen-capture-2023-update/"><u>Latest Techniques for iOS (iPhone/iPad) Screen Capture - 2023 Update</u></a></li>
<li><a href="https://facebook.techidaily.com/leveraging-multiple-group-platforms-for-increased-impact/"><u>Leveraging Multiple Group Platforms for Increased Impact</u></a></li>
<li><a href="https://driver-error.techidaily.com/limited-available-resources-on-device/"><u>Limited Available Resources on Device</u></a></li>
<li><a href="https://technical-tips.techidaily.com/macbook-air-users-must-know-trick-effortlessly-managing-dual-displays/"><u>Macbook Air Users' Must-Know Trick: Effortlessly Managing Dual Displays</u></a></li>
<li><a href="https://driver-error.techidaily.com/navigating-windows-8-enabling-safe-mode-and-uninstalling-video-card-drivers-easily/"><u>Navigating Windows #8: Enabling Safe Mode and Uninstalling Video Card Drivers Easily</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-mac-video-production-simplified-best-video-makers-for-beginners/"><u>New Mac Video Production Simplified Best Video Makers for Beginners</u></a></li>
<li><a href="https://driver-error.techidaily.com/qualcomm-atheros-bluetooth-drivers-failing-on-windows-10-easy-fixes-that-work/"><u>Qualcomm Atheros Bluetooth Drivers Failing on Windows 10: Easy Fixes That Work</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719357869666-quick-remedies-to-address-compatibility-issues-on-windows-xp/"><u>Quick Remedies to Address Compatibility Issues on Windows XP</u></a></li>
<li><a href="https://driver-error.techidaily.com/rectifying-acpi-driver-fault-venintanddev33a0/"><u>Rectifying ACPI Driver Fault: VEN_INT&DEV_33A0</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-driver-absence-issues-on-your-device-windows-11-8-and-7-solutions/"><u>Resolving Driver Absence Issues on Your Device: Windows 11, 8 & 7 Solutions</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-the-gtx-950s-code-43-issue-in-windows-11-a-comprehensive-guide/"><u>Resolving the GTX 지판 950'S 'Code 43 Issue' In Windows 11 - A Comprehensive Guide</u></a></li>
<li><a href="https://extra-support.techidaily.com/scrutinizing-high-quality-brightness-in-hd-imaging-for-2024/"><u>Scrutinizing High-Quality Brightness in HD Imaging for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-the-problem-unrecognized-usb-devices-on-windows-troubleshooting-steps/"><u>Solving the Problem: Unrecognized USB Devices on Windows - Troubleshooting Steps</u></a></li>
<li><a href="https://driver-error.techidaily.com/system-alert-bcm20702a0-driver-not-available/"><u>System Alert: BCM20702A0 Driver Not Available</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/the-compreeved-list-of-non-bandicamp-capture-software-on-mac/"><u>The Compreeved List of Non-Bandicamp Capture Software on Mac</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-ultimate-list-of-live-streaming-camera-models/"><u>The Ultimate List of Live-Streaming Camera Models</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-non-recognizing-usb-devices-on-w78/"><u>Troubleshooting Non-Recognizing USB Devices on W7/8</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unlocking-the-potential-androids-journey-with-bing-and-ai/"><u>Unlocking the Potential: Android's Journey with Bing and AI</u></a></li>
<li><a href="https://driver-error.techidaily.com/win-usb-serial-reconciliation-guide/"><u>Win-USB Serial Reconciliation Guide</u></a></li>
</ul></div>
