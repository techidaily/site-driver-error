---
title: Fixing Ethernet Driver Not Working After Upgrade
date: 2024-08-15T06:44:21.669Z
updated: 2024-08-16T06:44:21.669Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Fixing Ethernet Driver Not Working After Upgrade
excerpt: This Article Describes Fixing Ethernet Driver Not Working After Upgrade
thumbnail: https://thmb.techidaily.com/6304baca930779dbe6ae3412704c6577c66eb8d788b6fe6b67667ffd209c0a5f.jpg
---

## Fixing Ethernet Driver Not Working After Upgrade

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b91ef1806793.jpg)

 Users have reported that their Realtek PCIe Family Controller (Ethernet) randomly stopped working after they upgraded to Windows 10\. There are still no answers from Microsoft or Realtek as to why would this happen, and this situation happens randomly on different occasions, so there are a lot of solutions that could be of help.

 If this is the problem you are experiencing now, please follow the instructions below to get it fixed by yourself.

[**Option One: Reset TCP/IP**](https://natural-cycles.sjv.io/vmebmr)
[**Option Two: Change Settings in Network Adapter Properties**](https://aofit.pxf.io/mmjyxq)
[**Option Three: Reinstall Realtek Adapter Driver**](https://westkiss.pxf.io/daqnaq)
[**Option Four: Update the Realtek Driver**](https://newchic.sjv.io/jzg4zq)

---

<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Option One: Reset TCP/IP**

1) On your keyboard, press the**Windows logo key** , type**cmd** , right-click**Command Prompt** from the results, and select**Run as administrator** .  
  
![how to open Command Prompt as an admin](https://images.drivereasy.com/wp-content/uploads/2023/10/win11-Command-Prompt-Run-as-administrator.jpg)

 When prompted with the following notification, hit**Yes** to continue.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de25ac8c94.jpg)

 2) Type in the following command:

netsh int ip reset c:\resetlog.txt

 Make sure that you have made no typo and hit**Enter** .

<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de2ea5a2ef.png)

 This will help you reset your TCP/IP (Transmission Control Protocol/Internet Protocol). To make it easier to understand, TCP/IP is the language that your computer uses to communicate with the outside world. Reseting TCP/IP will help you revert your Internet settings to the stage where it still works.

---

### **Option Two:** **Change Settings in Network Adapter Properties**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand category**Network adapters** .

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
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand the category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

 Hit**OK** to continue.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-access.techidaily.com/new-2024-approved-essential-convertor-list-8-proven-sub-and-srt-solutions/"><u>[New] 2024 Approved  Essential Convertor List  8 Proven Sub and SRT Solutions</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-enhancing-meeting-productivity-zooms-audio-and-video-recording-tips/"><u>[New] Enhancing Meeting Productivity  Zoom's Audio & Video Recording Tips</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-creating-impact-with-high-converting-youtube-advertising-banners/"><u>[New] In 2024, Creating Impact with High-Converting YouTube Advertising Banners</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-in-2024-sharpening-digital-images-through-strategic-zooming/"><u>[New] In 2024, Sharpening Digital Images Through Strategic Zooming</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-cream-of-the-crop-top-8-sites-for-rich-3d-and-text/"><u>[New] The Cream of the Crop  Top 8 Sites for Rich 3D & Text</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-ultimate-guide-to-reducing-shakiness-on-your-gopro-movie/"><u>[New] The Ultimate Guide to Reducing Shakiness on Your GoPro Movie</u></a></li>
<li><a href="https://driver-error.techidaily.com/repaired-initial-error-of-non-booting-device-addressed/"><u>[REPAIRED] Initial Error of Non-Booting Device Addressed</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-easy-guide-turning-your-favorite-youtube-videos-into-animated-gifs-for-2024/"><u>[Updated] Easy Guide  Turning Your Favorite YouTube Videos Into Animated GIFs for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-augmented-gaming-experience-the-top-8-list/"><u>2024 Approved  Augmented Gaming Experience  The Top 8 List</u></a></li>
<li><a href="https://driver-error.techidaily.com/broadcom-n-adapter-woes-ended-in-windows-os/"><u>Broadcom N Adapter Woes Ended in Windows OS</u></a></li>
<li><a href="https://driver-error.techidaily.com/closed-report-no-available-support-for-intelamd-video-drivers-in-premiere-pro/"><u>Closed Report: No Available Support for Intel/AMD Video Drivers in Premiere Pro</u></a></li>
<li><a href="https://driver-error.techidaily.com/comprehensive-guide-to-repairing-older-usb-composite-device-connections-fixed/"><u>Comprehensive Guide to Repairing Older USB Composite Device Connections [FIXED]</u></a></li>
<li><a href="https://driver-error.techidaily.com/corrected-audio-video-sync-errors-asus-and-windows-11-compatibility/"><u>Corrected Audio-Video Sync Errors: ASUS & Windows 11 Compatibility</u></a></li>
<li><a href="https://driver-error.techidaily.com/dealing-with-improper-driver-installation-errors-on-your-computer-a-comprehensive-guide/"><u>Dealing with Improper Driver Installation Errors on Your Computer: A Comprehensive Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/default-amd-wattman-settings-collapse-and-recovery-complete-solution-guide/"><u>Default AMD Wattman Settings Collapse & Recovery: Complete Solution Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/device-driver-problems-in-windows-7811-follow-these-steps-to-get-it-solved-now/"><u>Device Driver Problems in Windows 7/8/11? Follow These Steps to Get It Solved Now</u></a></li>
<li><a href="https://driver-error.techidaily.com/disconnect-dilemma-bluetooth-mouse-on-win-810/"><u>Disconnect Dilemma: Bluetooth Mouse on Win 8/10</u></a></li>
<li><a href="https://driver-error.techidaily.com/driver-error-no-longer-affecting-system/"><u>Driver Error No Longer Affecting System</u></a></li>
<li><a href="https://driver-error.techidaily.com/error-free-installation-of-nvidia-drivers-2024-version/"><u>Error-Free Installation of Nvidia Drivers - 2024 Version</u></a></li>
<li><a href="https://driver-error.techidaily.com/faulty-driver-bcm20702a0-not-found/"><u>Faulty Driver - BCM20702A0 Not Found</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-your-non-working-hp-keyboard-a-step-by-step-tutorial/"><u>Fix Your Non-Working HP Keyboard: A Step-by-Step Tutorial</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721104314262-fix-cannot-disable-bluetooth-functionality-in-my-laptop-using-cortana/"><u>Fix: Cannot Disable Bluetooth Functionality in My Laptop Using Cortana.</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-can-i-disable-bluetooth-on-windows-10-quick-fix/"><u>How Can I Disable Bluetooth on Windows 10? Quick Fix!</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-make-sense-of-dolby-digital-not-playing-properly-on-laptop-answer-found-and-resolved/"><u>How to Make Sense of 'Dolby Digital' Not Playing Properly on Laptop? – Answer Found & Resolved!✨</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-deleted-realme-11-pro-contacts-an-easy-method-explained-by-fonelab-android-recover-contacts/"><u>How to Restore Deleted Realme 11 Pro Contacts  An Easy Method Explained.</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-tecno-camon-30-pro-5g-to-pc-drfone-by-drfone-android/"><u>How to Screen Mirroring Tecno Camon 30 Pro 5G to PC? | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/ideport0-malfunction-signal-noticed/"><u>Ideport0 Malfunction Signal Noticed</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-the-ultimate-watch-list-top-10-music-clips-on-facebook/"><u>In 2024, The Ultimate Watch List  Top 10 Music Clips on Facebook</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-why-does-itools-virtual-location-not-work-for-apple-iphone-15-pro-maxipad-solved-drfone-by-drfone-virtual-ios/"><u>In 2024, Why Does iTools Virtual Location Not Work For Apple iPhone 15 Pro Max/iPad? Solved | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/intel-me-firmware-troubleshooting/"><u>Intel ME Firmware Troubleshooting</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-apple-iphone-14-pro-max-drfone-by-drfone-virtual-ios/"><u>Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Apple iPhone 14 Pro Max | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/masterclass-in-capturing-high-quality-vimeo-videos-for-2024/"><u>Masterclass in Capturing High-Quality Vimeo Videos for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/mastering-speed-control-on-your-netflix-streams/"><u>Mastering Speed Control on Your Netflix Streams</u></a></li>
<li><a href="https://driver-error.techidaily.com/prevent-regular-amd-driver-failures/"><u>Prevent Regular AMD Driver Failures</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolve-device-improperly-set-up-issue-understanding-and-fixing-error-1/"><u>Resolve 'Device Improperly Set Up' Issue - Understanding and Fixing Error 1</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolve-the-driver-not-found-issue-in-your-itbm-with-simple-steps/"><u>Resolve the 'Driver Not Found' Issue in Your ITBM with Simple Steps</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721102667819-resolving-the-missing-coprocessor-driver-issue-in-windows-11-a-step-by-step-guide/"><u>Resolving the Missing Coprocessor Driver Issue in Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/seagate-drive-mystery-showing-up-on-windows/"><u>Seagate Drive Mystery: Showing Up on Windows?</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-fixes-for-windows-10s-asus-drivers/"><u>Step-By Step Fixes For Windows 10'S Asus Drivers</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-guide-to-upgrading-razer-deathadder-driver-in-win10/"><u>Step-by-Step Guide to Upgrading Razer Deathadder Driver in Win10</u></a></li>
<li><a href="https://driver-error.techidaily.com/the-complete-walkthrough-downloading-and-installing-new-drivers-on-hps-envy-laptops/"><u>The Complete Walkthrough: Downloading and Installing New Drivers on HP'S Envy Laptops</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-hidden-perils-of-ai-penned-literature/"><u>The Hidden Perils of AI-Penned Literature</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-tips-for-device-misconfiguration-warning-code-1-resolved/"><u>Troubleshooting Tips for Device Misconfiguration Warning - Code 1 Resolved</u></a></li>
<li><a href="https://driver-error.techidaily.com/unblocking-stuck-usb-to-serial-connections/"><u>Unblocking Stuck USB to Serial Connections</u></a></li>
<li><a href="https://driver-error.techidaily.com/unraveling-the-mystery-of-driver-52-troubles/"><u>Unraveling the Mystery of Driver #52 Troubles</u></a></li>
<li><a href="https://driver-error.techidaily.com/win11-disables-graphics-card-use/"><u>Win11 Disables Graphics Card Use</u></a></li>
<li><a href="https://driver-error.techidaily.com/win11-prevents-gpu-use-attempt/"><u>Win11 Prevents GPU Use Attempt</u></a></li>
<li><a href="https://driver-error.techidaily.com/wudfrd-not-booting-device-event-id-219/"><u>WudfRd Not Booting, Device Event ID: 219</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/be-editing-essentials-the-ultimate-guide-post-upload-refinements-for-2024/"><u>YouTube Editing Essentials  The Ultimate Guide Post-Upload Refinements for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/zooms-ideal-cam-selections-top-6-picks/"><u>Zoom's Ideal Cam Selections  Top 6 Picks</u></a></li>
</ul></div>
