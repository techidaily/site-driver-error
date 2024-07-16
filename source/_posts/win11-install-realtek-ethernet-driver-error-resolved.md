---
title: "Win11 Install: Realtek Ethernet Driver Error Resolved"
date: 2024-07-15T06:46:36.683Z
updated: 2024-07-16T06:46:36.683Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: "This Article Describes Win11 Install: Realtek Ethernet Driver Error Resolved"
excerpt: "This Article Describes Win11 Install: Realtek Ethernet Driver Error Resolved"
thumbnail: https://thmb.techidaily.com/64b02260fc2e331299df22a1e999eab91ad890c07462ad4672fe1c0550ce5fa1.jpg
---

## Win11 Install: Realtek Ethernet Driver Error Resolved

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b91ef1806793.jpg)

 Users have reported that their Realtek PCIe Family Controller (Ethernet) randomly stopped working after they upgraded to Windows 10\. There are still no answers from Microsoft or Realtek as to why would this happen, and this situation happens randomly on different occasions, so there are a lot of solutions that could be of help.

 If this is the problem you are experiencing now, please follow the instructions below to get it fixed by yourself.

[**Option One: Reset TCP/IP**](https://natural-cycles.sjv.io/vmebmr)
[**Option Two: Change Settings in Network Adapter Properties**](https://aofit.pxf.io/mmjyxq)
[**Option Three: Reinstall Realtek Adapter Driver**](https://westkiss.pxf.io/daqnaq)
[**Option Four: Update the Realtek Driver**](https://newchic.sjv.io/jzg4zq)

---

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
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

### **Option Two:** **Change Settings in Network Adapter Properties**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
3) Then right-click Realtek PCIe GBE Family Controller option and choose **Properties** .

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de65b229a9.png)

 4) Go to**Advanced** tab, then choose**Speed & Duplex** option on the left side of the pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de6ed4d026.png)

 5) On the**Value** bar, change the default Auto Negotiation to **100 Mbps Full Duplex**  or some other options accordingly. We chose**100 Mbps Full Duplex** here, but yours could be different.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deb007e7e1.png)

 6) Now on the left side of the pane, choose**Energy Efficient Ethernet** option, then change the Value to**Disabled** . After the changes, hit**OK** to save.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deab52d9e0.png)

 7) Still, in the**Properties** window, this time, let’s go to**Power Management** tab. Un-tick the box for**Allow the computer to turn off this device to save power** . Then hit**OK** to save and exit.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587decc3276b5.png)

---

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Option Three:** **Reinstall or Rollback Realtek Adapter Driver**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand the category**Network adapters** .

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

 Hit**OK** to continue.
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://driver-error.techidaily.com/no-more-laggy-windows-11/"><u>No More Laggy Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/reactivation-process-complete/"><u>Reactivation Process Complete</u></a></li>
<li><a href="https://some-techniques.techidaily.com/improve-office-productivity-with-speech-to-text-conversion-in-microsoft-word-for-2024/"><u>Improve Office Productivity with Speech to Text Conversion in Microsoft Word for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/mouse-mastery-latency-free-windows-experience/"><u>Mouse Mastery: Latency-Free Windows Experience</u></a></li>
<li><a href="https://driver-error.techidaily.com/diagnosing-and-fixing-win1011-sm-bus-drivers/"><u>Diagnosing and Fixing Win10/11 Sm Bus Drivers</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-nubia-z50-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On Nubia Z50 Ultra? | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/elevating-system-bus-efficiency-on-win11/"><u>Elevating System Bus Efficiency on Win11</u></a></li>
<li><a href="https://driver-error.techidaily.com/detect-unseen-seagate-hdd-win11-tips-and-tricks/"><u>Detect Unseen Seagate HDD: Win11 Tips & Tricks</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-the-definitive-list-of-popular-software-for-auditory-disentanglement-from-video-footage-for-2024/"><u>New The Definitive List of Popular Software for Auditory Disentanglement From Video Footage for 2024</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/in-2024-advanced-audio-editing-in-adobe-premiere-pro-effortless-track-mixing-methods/"><u>In 2024, Advanced Audio Editing in Adobe Premiere Pro Effortless Track Mixing Methods</u></a></li>
<li><a href="https://fake-location.techidaily.com/ispoofer-is-not-working-on-xiaomi-13t-fixed-drfone-by-drfone-virtual-android/"><u>iSpoofer is not working On Xiaomi 13T? Fixed | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/restoring-sound-output-from-non-responsive-usb-device-on-win10/"><u>Restoring Sound Output From Non-Responsive USB Device on WIN10</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-cross-platform-collaboration-for-sharing-facebook-videos/"><u>[New] 2024 Approved  Cross-Platform Collaboration for Sharing Facebook Videos</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-essential-youtube-subscriptions-for-economic-updates/"><u>2024 Approved  Essential YouTube Subscriptions for Economic Updates</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/2024-approved-top-mp4-metadata-editors-for-video-organization/"><u>2024 Approved Top MP4 Metadata Editors for Video Organization</u></a></li>
<li><a href="https://driver-error.techidaily.com/no-more-lags-streamlined-windows-control/"><u>No More Lags: Streamlined Windows Control</u></a></li>
<li><a href="https://driver-error.techidaily.com/win10-addressing-usb-non-responsive/"><u>Win10: Addressing USB Non-Responsive</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-xiaomi-redmi-12-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Xiaomi Redmi 12 Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-enjoy-uninterrupted-viewing-top-20-youtube-download-apps/"><u>[New] In 2024, Enjoy Uninterrupted Viewing  Top 20 YouTube Download Apps</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-realme-gt-3-drfone-by-drfone-virtual-android/"><u>Here are Some Pro Tips for Pokemon Go PvP Battles On Realme GT 3 | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-windows-10-qualcomm-atheros-bluetooth-not-working-solution/"><u>Troubleshooting Windows 10: Qualcomm Atheros Bluetooth Not Working Solution</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-bring-imagination-to-life-self-animated-artistry/"><u>[Updated] Bring Imagination to Life  Self-Animated Artistry</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-the-iphone-external-storage-connectivity-problem-usb-mtp-driver-solutions/"><u>Fixing the iPhone External Storage Connectivity Problem: USB MTP Driver Solutions</u></a></li>
<li><a href="https://driver-error.techidaily.com/conquer-directx-9-startup-issues-in-5-minutes/"><u>Conquer DirectX 9 Startup Issues in 5 Minutes</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-premier-online-videography-tools-to-eye-for-2024/"><u>[New] Premier Online Videography Tools to Eye for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-asus-keyboard-backlight-not-working/"><u>[SOLVED] ASUS Keyboard Backlight Not Working</u></a></li>
<li><a href="https://driver-error.techidaily.com/alert-wireless-mouse-error-no-signal-detected/"><u>[Alert] Wireless Mouse Error - No Signal Detected</u></a></li>
<li><a href="https://driver-error.techidaily.com/titled-successful-installation-of-essential-hardware-drivers/"><u>[TITLED] Successful Installation of Essential Hardware Drivers</u></a></li>
<li><a href="https://driver-error.techidaily.com/the-ultimate-fix-how-to-correctly-install-your-hcmon-driver-and-avoid-failures/"><u>The Ultimate Fix: How to Correctly Install Your HCMon Driver and Avoid Failures</u></a></li>
<li><a href="https://driver-error.techidaily.com/keyboard-and-pc-now-harmonious-post-windows-11-fix/"><u>Keyboard & PC Now Harmonious Post-Windows 11 Fix</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-compatible-samsung-mobile-system/"><u>Windows-Compatible: Samsung Mobile System</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-asus-usb-c-webcam-glitch-on-windows-11/"><u>Resolved ASUS USB-C Webcam Glitch on Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/htc-one-mini-bluetooth-failure-on-elementary-os-4-loki-resolved-37-characters/"><u>HTC One Mini Bluetooth Failure on Elementary OS 4 Loki, Resolved! (37 Characters)</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-1011-recover-absent-data-acquisitor/"><u>Windows 10/11: Recover Absent Data Acquisitor</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-the-speedy-blueprint-collecting-tiktoks-with-ease/"><u>[New] The Speedy Blueprint  Collecting TikToks with Ease</u></a></li>
<li><a href="https://driver-error.techidaily.com/endless-bluetooth-woes-no-more-win10-edition/"><u>Endless Bluetooth Woes, No More! - Win10 Edition</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721104210852-revive-your-wireless-keyboard-on-a-windows-pc-solutions-that-work/"><u>Revive Your Wireless Keyboard on a Windows PC – Solutions That Work</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-top-shots-and-their-tales-the-most-shared-stock-memes/"><u>2024 Approved  Top Shots and Their Tales  The Most Shared Stock Memes</u></a></li>
<li><a href="https://driver-error.techidaily.com/drivers-unsuccessful-lacking-intel-adapter-support/"><u>Drivers Unsuccessful; Lacking Intel Adapter Support</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-fix-enter-key-not-working-on-windows/"><u>How to Fix Enter Key Not Working on Windows</u></a></li>
<li><a href="https://driver-error.techidaily.com/cutting-through-disk-space-errors-on-win1110/"><u>Cutting Through Disk Space Errors on Win11/10</u></a></li>
</ul></div>
