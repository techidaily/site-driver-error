---
title: Corrected Realtek Network Issue in New OS Version
date: 2024-07-15T07:02:30.422Z
updated: 2024-07-16T07:02:30.422Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Corrected Realtek Network Issue in New OS Version
excerpt: This Article Describes Corrected Realtek Network Issue in New OS Version
thumbnail: https://thmb.techidaily.com/fb64d3334f8fecc4f94c1ae3403a6dd894e812df5486b2d51ee08c850ba80fdd.jpg
---

## Corrected Realtek Network Issue in New OS Version

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b91ef1806793.jpg)

 Users have reported that their Realtek PCIe Family Controller (Ethernet) randomly stopped working after they upgraded to Windows 10\. There are still no answers from Microsoft or Realtek as to why would this happen, and this situation happens randomly on different occasions, so there are a lot of solutions that could be of help.

 If this is the problem you are experiencing now, please follow the instructions below to get it fixed by yourself.

[**Option One: Reset TCP/IP**](https://natural-cycles.sjv.io/vmebmr)
[**Option Two: Change Settings in Network Adapter Properties**](https://aofit.pxf.io/mmjyxq)
[**Option Three: Reinstall Realtek Adapter Driver**](https://westkiss.pxf.io/daqnaq)
[**Option Four: Update the Realtek Driver**](https://newchic.sjv.io/jzg4zq)

---

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
3) Then right-click Realtek PCIe GBE Family Controller option and choose **Properties** .

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

### **Option Three:** **Reinstall or Rollback Realtek Adapter Driver**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand the category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

 Hit**OK** to continue.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)

 4) Go to the menu bar on the top and click the button for **Scan for hardware changes** .  
<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://driver-error.techidaily.com/win-printer-drivers-found-and-fixed/"><u>Win Printer Drivers - Found & Fixed</u></a></li>
<li><a href="https://driver-error.techidaily.com/chip-select-failures-resolved-in-io-driver/"><u>Chip Select Failures Resolved in I/O Driver</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-the-ultimate-guide-to-simple-iphone-screencasting/"><u>In 2024, The Ultimate Guide to Simple iPhone Screencasting</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-illustration-elevation-incorporating-text-into-3d-artwork/"><u>2024 Approved  Illustration Elevation  Incorporating Text Into 3D Artwork</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-end-your-active-discord-association-for-2024/"><u>[New] End Your Active Discord Association for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/disc-drives-hidden-windows-11-troubleshooted/"><u>Disc Drives Hidden: Windows 11 Troubleshooted</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-microsoft-excel-2016-has-stopped-working-error-stellar-by-stellar-guide/"><u>How to fix Microsoft Excel 2016 has stopped working error? | Stellar</u></a></li>
<li><a href="https://driver-error.techidaily.com/corrected-unsupported-driver-issue-with-amd-and-intel-graphics-in-premier-pro/"><u>Corrected Unsupported Driver Issue with AMD & Intel Graphics in Premier Pro</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-three-ways-to-sim-unlock-htc-u23-pro-by-drfone-android/"><u>In 2024, Three Ways to Sim Unlock HTC U23 Pro</u></a></li>
<li><a href="https://driver-error.techidaily.com/maximizing-your-pc-gaming-experience-with-razer-driver-update/"><u>Maximizing Your PC Gaming Experience with Razer Driver Update</u></a></li>
<li><a href="https://driver-error.techidaily.com/syncing-sm-bus-controllers-on-windows-1011-platforms/"><u>Syncing SM Bus Controllers on Windows 10/11 Platforms</u></a></li>
<li><a href="https://driver-error.techidaily.com/demystifying-and-fixing-issues-related-to-vintage-usb-combined-devices/"><u>Demystifying and Fixing Issues Related to Vintage USB Combined Devices</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-ideal-3d-software-for-creating-animation/"><u>In 2024, Ideal 3D Software for Creating Animation</u></a></li>
<li><a href="https://driver-error.techidaily.com/unseen-usb-devices-on-win-1011/"><u>Unseen USB Devices on Win 10/11</u></a></li>
<li><a href="https://driver-error.techidaily.com/rectifying-erroneous-inf-section-for-service-installation/"><u>Rectifying Erroneous INF Section for Service Installation</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-solution-for-dealing-with-incorrect-device-settings-error-code-1/"><u>Step-by-Step Solution for Dealing With Incorrect Device Settings (Error Code 1)</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-1011-sm-bus-controller-error-fix/"><u>Windows 10/11: SM Bus Controller Error Fix</u></a></li>
<li><a href="https://driver-error.techidaily.com/guide-to-fix-video-playback-reversed-horizontally-on-asus-laptops/"><u>Guide to Fix Video Playback Reversed Horizontally on ASUS Laptops</u></a></li>
<li><a href="https://driver-error.techidaily.com/guide-installing-essential-drivers-for-proper-device-functionality-on-windows-operating-systems-win1187/"><u>Guide: Installing Essential Drivers for Proper Device Functionality on Windows Operating Systems (Win11/8/7)</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-fix-imaging-devices-missing-in-windows-11/"><u>How To Fix Imaging Devices Missing in Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/meltdown-and-spectre-intel-me-solutions/"><u>Meltdown & Spectre: Intel ME Solutions</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-usb-connectivity-after-adb-error/"><u>Fix USB Connectivity After ADB Error</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-instagram-friendships-unlocked-leading-free-and-safe-follower-finding-tools-iosandroid/"><u>In 2024, Instagram Friendships Unlocked  Leading Free & Safe Follower-Finding Tools (iOS/Android)</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-awe-inspiring-allure-top-youtube-magic-editing-wonders/"><u>In 2024, Awe-Inspiring Allure  Top YouTube Magic Editing Wonders</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-explore-5-superior-ways-to-record-sound-with-windows-11/"><u>In 2024, Explore 5 Superior Ways to Record Sound with Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-the-mystery-resolving-issues-when-your-final-usb-device-fails-and-windows-ignores-its-existence/"><u>Solving the Mystery: Resolving Issues When Your Final USB Device Fails & Windows Ignores Its Existence</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-social-media-savvy-instagrams-best-tips-for-gif-uploads-and-posting/"><u>[New] In 2024, Social Media Savvy  Instagram's Best Tips for GIF Uploads and Posting</u></a></li>
<li><a href="https://driver-error.techidaily.com/guide-to-resolve-device-misconfigured-error-with-code-not-configured-correctly4/"><u>Guide to Resolve 'Device Misconfigured' Error with Code Not-Configured-Correctly(4)</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-based-bluetooth-troubleshooting-tips/"><u>Windows-Based Bluetooth Troubleshooting Tips</u></a></li>
<li><a href="https://driver-error.techidaily.com/error-driver-installation-without-intel-component/"><u>Error: Driver Installation Without Intel Component</u></a></li>
<li><a href="https://driver-error.techidaily.com/restore-visibility-to-hardware-on-win1011/"><u>Restore Visibility to Hardware on Win10/11</u></a></li>
<li><a href="https://driver-error.techidaily.com/broadcom-n-adapter-woes-ended-in-windows-os/"><u>Broadcom N Adapter Woes Ended in Windows OS</u></a></li>
<li><a href="https://driver-error.techidaily.com/remedy-for-ignored-logitech-unifying-hub-in-oses/"><u>Remedy for Ignored Logitech Unifying Hub in OSes</u></a></li>
<li><a href="https://driver-error.techidaily.com/mastering-device-error-repair-in-dm/"><u>Mastering Device Error Repair in DM</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolution-device-driver-error/"><u>[Resolution: Device Driver Error]</u></a></li>
<li><a href="https://driver-error.techidaily.com/expert-advice-on-repairing-iphone-mtp-usb-interface-driver-glitches-for-easy-data-transfer/"><u>Expert Advice on Repairing iPhone MTP USB Interface Driver Glitches for Easy Data Transfer</u></a></li>
<li><a href="https://fox-glue.techidaily.com/top-20-dynamic-anime-openers-songs/"><u>Top 20 Dynamic Anime Openers' Songs</u></a></li>
<li><a href="https://driver-error.techidaily.com/freeze-free-fast-windows-11/"><u>Freeze-Free, Fast Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-qualcomm-atheros-bluetooth-issues-on-windows-10-complete-solution/"><u>Fixing Qualcomm Atheros Bluetooth Issues on Windows 10: Complete Solution</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-audiovisual-voice-transformation-the-latest-devices-feedback-and-options/"><u>Updated 2024 Approved Audiovisual Voice Transformation The Latest Devices, Feedback, & Options</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-the-gtx-hemisphere-950-code-43-issue-in-windows-11-a-comprehensive-guide/"><u>Fixing the GTX Hemisphere 950 'Code 43' Issue in Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-collect-audio-files-from-fb-newsfeeds/"><u>2024 Approved  Collect Audio Files From FB Newsfeeds</u></a></li>
<li><a href="https://driver-error.techidaily.com/win11-advanced-sm-bus-driver-functionality/"><u>Win11: Advanced SM Bus Driver Functionality</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-from-video-lessons-to-vivid-engaging-gifs-no-download-needed-for-2024/"><u>[New] From Video Lessons to Vivid, Engaging GIFs – No Download Needed for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-step-by-step-guide-to-flawless-zoom-screen-sharing/"><u>In 2024, Step-by-Step Guide to Flawless Zoom Screen Sharing</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-decoding-facebook-capturing-and-keeping-status-videos/"><u>[Updated] In 2024, Decoding Facebook  Capturing and Keeping Status Videos</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-tips-and-tricks-to-tell-if-your-iphone-11-pro-is-unlocked-by-drfone-ios/"><u>In 2024, Tips And Tricks To Tell if Your iPhone 11 Pro Is Unlocked</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721097773366-windows-11-and-qualcomm-atheros-restoring-bluetooth-connectivity-with-proven-solutions/"><u>Windows 11 and Qualcomm Atheros: Restoring Bluetooth Connectivity with Proven Solutions.</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-identify-and-fix-missing-seagate-hd-on-pc/"><u>How To Identify & Fix Missing Seagate HD on PC</u></a></li>
</ul></div>
