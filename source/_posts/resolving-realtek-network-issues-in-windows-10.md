---
title: Resolving Realtek Network Issues in Windows 10
date: 2024-07-15T06:58:09.720Z
updated: 2024-07-16T06:58:09.720Z
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
<li><a href="https://driver-error.techidaily.com/understanding-the-legacy-of-usb-composite-devices-insights-and-solutions/"><u>Understanding the Legacy of USB Composite Devices: Insights and Solutions</u></a></li>
<li><a href="https://driver-error.techidaily.com/breaking-barrier-error-52-in-car-systems/"><u>Breaking Barrier Error 52 in Car Systems</u></a></li>
<li><a href="https://some-skills.techidaily.com/utilizing-in-presentation-speech-to-text-functionality-in-powerpoint-for-2024/"><u>Utilizing In-Presentation Speech-to-Text Functionality in PowerPoint for 2024</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/in-2024-quicktakes-why-videos-thrive-on-twitter-writes/"><u>In 2024, QuickTakes  Why Videos Thrive on Twitter' Writes</u></a></li>
<li><a href="https://unlock-android.techidaily.com/tips-and-tricks-for-setting-up-your-vivo-v30-phone-pattern-lock-by-drfone-android/"><u>Tips and Tricks for Setting Up your Vivo V30 Phone Pattern Lock</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-how-to-stand-out-yt-thumbnail-size-and-engagement-strategies/"><u>2024 Approved  How to Stand Out  YT Thumbnail Size and Engagement Strategies</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-how-to-transfer-from-apple-iphone-6-plus-to-iphone-8x11-drfone-by-drfone-transfer-from-ios/"><u>In 2024, How to Transfer from Apple iPhone 6 Plus to iPhone 8/X/11 | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-tips-for-uploading-external-urls-to-ig/"><u>[Updated] Tips for Uploading External URLs to IG</u></a></li>
<li><a href="https://driver-error.techidaily.com/usb-speaker-lacks-volume-how-to-fix-it-on-win10/"><u>USB Speaker Lacks Volume - How to Fix It on Win10</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-best-android-sim-unlock-code-generators-unlock-your-motorola-moto-g34-5g-phone-hassle-free-by-drfone-android/"><u>The Best Android SIM Unlock Code Generators Unlock Your Motorola Moto G34 5G Phone Hassle-Free</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-gauging-storage-capacity-for-full-length-films/"><u>[New] Gauging Storage Capacity for Full-Length Films</u></a></li>
<li><a href="https://driver-error.techidaily.com/missing-dvdcd-driver-on-win11-fixed/"><u>Missing DVD/CD Driver on Win11? Fixed!</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-optimal-team-chats-secrets-to-success-4-steps/"><u>[New] In 2024, Optimal Team Chats  Secrets to Success, #4 Steps</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-changefake-your-oppo-reno-11f-5g-location-on-viber-drfone-by-drfone-virtual-android/"><u>How to Change/Fake Your Oppo Reno 11F 5G Location on Viber | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/system-anomaly-ideport0-error-reported/"><u>System Anomaly: Ideport0 Error Reported</u></a></li>
<li><a href="https://driver-error.techidaily.com/asus-key-backlight-not-activating/"><u>Asus Key Backlight Not Activating</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-set-your-preferred-job-location-on-linkedin-app-of-your-lava-blaze-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Set Your Preferred Job Location on LinkedIn App of your Lava Blaze Pro 5G | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-the-crash-and-reboot-default-radeon-wattman-setting-issue/"><u>Resolving the 'Crash & Reboot: Default Radeon Wattman Setting' Issue</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-what-this-post-can-teach-you-about-clay-animation-for-2024/"><u>Updated What This Post Can Teach You About Clay Animation for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/comprehensive-tips-for-repairing-a-malfunctioning-wireless-keyboard-compatible-with-windows-pcs/"><u>Comprehensive Tips for Repairing a Malfunctioning Wireless Keyboard Compatible With Windows PCs</u></a></li>
<li><a href="https://extra-support.techidaily.com/shining-through-hd-is-it-a-wise-pick-for-hdr-in-2024/"><u>Shining Through HD  Is It a Wise Pick for HDR, In 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/make-your-computer-listen-a-quick-guide-to-fix-unresponsive-bluetooth-on-latest-os-update-guide-inside/"><u>Make Your Computer Listen: A Quick Guide To Fix Unresponsive Bluetooth on Latest OS Update [Guide Inside]</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-disappeared-bluetooth-manage-your-devices/"><u>Fixing: Disappeared Bluetooth, Manage Your Devices</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-boxed-bliss-reinventing-the-art-of-first-contacts/"><u>[Updated] Boxed Bliss  Reinventing the Art of First Contacts</u></a></li>
<li><a href="https://driver-error.techidaily.com/resurrecting-disabled-windows-10-usb-earbuds/"><u>Resurrecting Disabled Windows 10 USB Earbuds</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/pokemon-go-no-gps-signal-heres-every-possible-solution-on-poco-f5-pro-5g-drfone-by-drfone-virtual-android/"><u>Pokemon Go No GPS Signal? Heres Every Possible Solution On Poco F5 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/the-companyinfo-given-that-i-want-this-question-forensicinia1098-735-kmkm-so-far-as-to-be-able-to-find-out-which-of-these-numbers-in-i-in-order-for-differen3/"><u>The Company_info = 'Given that I Want This Question. Forensicinia,1098-735 Km/Km, so Far as to Be Able to Find Out Which of These Numbers in (I) In Order for Different Languages</u></a></li>
<li><a href="https://driver-error.techidaily.com/error-48-cleared-from-device-hub/"><u>Error 48 Cleared From Device Hub</u></a></li>
<li><a href="https://driver-error.techidaily.com/smoothing-over-elans-operational-snags-in-win10/"><u>Smoothing Over Elan's Operational Snags in Win10</u></a></li>
<li><a href="https://driver-error.techidaily.com/sound-fix-no-more-driver-trouble-hd/"><u>Sound Fix: No More Driver Trouble (HD)</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-realme-11-5g-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Realme 11 5G to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-windows-keystroke-issues-enter-key/"><u>Resolving Windows Keystroke Issues: Enter Key</u></a></li>
<li><a href="https://driver-error.techidaily.com/error-code-45-hardware-harmony-achieved/"><u>Error Code 45: Hardware Harmony Achieved</u></a></li>
<li><a href="https://driver-error.techidaily.com/hd-drivers-win11-success-story/"><u>HD Drivers: Win11 Success Story</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-can-we-bypass-vivo-t2x-5g-frp-by-drfone-android/"><u>How Can We Bypass Vivo T2x 5G FRP?</u></a></li>
<li><a href="https://facebook.techidaily.com/a-shift-toward-data-privacy-on-iphones/"><u>A Shift Toward Data Privacy on iPhones</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-video-orientation-issues-in-asus-laptops-how-to-get-things-right-side-up-again/"><u>Troubleshooting Video Orientation Issues in ASUS Laptops – How To Get Things Right-Side Up Again</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-easy-path-from-spotify-to-youtube-discover-the-best-playlist-tools/"><u>[New] 2024 Approved  Easy Path From Spotify to YouTube  Discover the Best Playlist Tools</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-issues-with-unrecognized-usb-devices-in-windows-step-by-step-guide/"><u>Resolving Issues with Unrecognized USB Devices in Windows: Step-by-Step Guide</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-in-2024-5-best-realistic-text-to-speech-ai-voice-generators-you-may-like/"><u>New In 2024, 5 Best Realistic Text to Speech AI Voice Generators You May Like</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-7-bsod-troubleshooting-resolve-error-code-0x0000007e-step-by-step-guide/"><u>Windows 7 BSOD Troubleshooting: Resolve Error Code 0X0000007E Step-by-Step Guide</u></a></li>
<li><a href="https://techidaily.com/how-to-get-out-of-recovery-on-apple-iphone-13-pro-max-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Get Out of Recovery on Apple iPhone 13 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-infinix-gt-10-pro-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Infinix GT 10 Pro | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/sonic-boom-new-technology-reviewed-for-2024/"><u>Sonic Boom  New Technology Reviewed for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/breaking-down-directx-9-setup-errors-in-steps/"><u>Breaking Down DirectX 9 Setup Errors in Steps</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-explore-10-prime-video-editing-apps-for-android-and-pc-for-2024/"><u>[Updated] Explore 10 Prime Video Editing Apps for Android and PC for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-straighten-the-orientation-of-video-outputs-on-your-asus-computer-monitor/"><u>How To Straighten The Orientation Of Video Outputs On Your Asus Computer Monitor</u></a></li>
<li><a href="https://driver-error.techidaily.com/win-1011s-missed-connection-with-unify-hub/"><u>Win 10/11'S Missed Connection with Unify Hub</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-solution-fixing-qualcomm-atheros-bluetooth-connectivity-on-windows-11/"><u>Step-by-Step Solution: Fixing Qualcomm Atheros Bluetooth Connectivity on Windows 11</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-2024-approved-mastering-audio-visual-integration-how-to-add-audio-to-video-using-premiere-pro/"><u>Updated 2024 Approved Mastering Audio-Visual Integration How to Add Audio to Video Using Premiere Pro</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-drive-operation-anomaly/"><u>Resolved Drive Operation Anomaly</u></a></li>
<li><a href="https://driver-error.techidaily.com/solve-your-hcmon-driver-problems-effective-fixes-for-installation-errors/"><u>Solve Your HCMon Driver Problems: Effective Fixes for Installation Errors</u></a></li>
<li><a href="https://driver-error.techidaily.com/multi-os-pci-hardware-support-tools/"><u>Multi-OS PCI Hardware Support Tools</u></a></li>
<li><a href="https://driver-error.techidaily.com/enhancing-windows-10-lenovo-bt-driver/"><u>Enhancing Windows 10 Lenovo BT Driver</u></a></li>
<li><a href="https://driver-error.techidaily.com/wi-fi-6ax201-connectivity-anomaly-addressed-now/"><u>Wi-Fi 6Ax201 Connectivity Anomaly - Addressed Now</u></a></li>
</ul></div>
