---
title: Solving Realtek LAN Driver Failure with Windows 11
date: 2024-08-15T06:43:52.895Z
updated: 2024-08-16T06:43:52.895Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Solving Realtek LAN Driver Failure with Windows 11
excerpt: This Article Describes Solving Realtek LAN Driver Failure with Windows 11
thumbnail: https://thmb.techidaily.com/7198dc888f65174fbf2046c2c24c70817b0458c73734644af430af59b81e9b9d.jpg
---

## Solving Realtek LAN Driver Failure with Windows 11

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

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de2ea5a2ef.png)

 This will help you reset your TCP/IP (Transmission Control Protocol/Internet Protocol). To make it easier to understand, TCP/IP is the language that your computer uses to communicate with the outside world. Reseting TCP/IP will help you revert your Internet settings to the stage where it still works.

---

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deb007e7e1.png)

 6) Now on the left side of the pane, choose**Energy Efficient Ethernet** option, then change the Value to**Disabled** . After the changes, hit**OK** to save.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deab52d9e0.png)

 7) Still, in the**Properties** window, this time, let’s go to**Power Management** tab. Un-tick the box for**Allow the computer to turn off this device to save power** . Then hit**OK** to save and exit.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://driver-error.techidaily.com/fixed-keyboard-not-working-on-windows-10/"><u>[Fixed] Keyboard Not Working on Windows 10</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-in-2024-transform-your-photos-mastering-time-lapse-with-samsung-mobile/"><u>[New] In 2024, Transform Your Photos  Mastering Time Lapse with Samsung Mobile</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-pazera-unleashed-a-deep-dive-into-audio-extractor-reviews-of-2024/"><u>[New] Pazera Unleashed  A Deep Dive Into Audio Extractor Reviews of 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-the-elite-selection-of-top-12-tycoons-perfect-for-strategic-souls-for-2024/"><u>[New] The Elite Selection of Top 12 Tycoons - Perfect for Strategic Souls for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-the-essential-checklist-for-syncing-obs-and-zoom/"><u>[New] The Essential Checklist for Syncing OBS & Zoom</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/opmusicreactionvids-yt-celebrity-highlights-2023/"><u>[New] TopMusicReactionVids  YT Celebrity Highlights, 2023</u></a></li>
<li><a href="https://article-files.techidaily.com/new-video-speed-mastery-selecting-premium-pc-monitor-controls-for-2024/"><u>[New] Video Speed Mastery  Selecting Premium PC Monitor Controls for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-asus-backlight-issue-identified/"><u>[SOLVED] ASUS Backlight Issue Identified</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-irqlnotlessorequal-bsod-in-windows-10/"><u>[Solved] IRQL_NOT_LESS_OR_EQUAL BSOD in Windows 10</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-2024-approved-cultivating-productive-collaboration-a-pathway-to-effective-collab-videos/"><u>[Updated] 2024 Approved  Cultivating Productive Collaboration  A Pathway to Effective Collab Videos</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-expert-tips-on-creating-striking-ae-titles/"><u>[Updated] Expert Tips on Creating Striking AE Titles</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-expand-your-gameplay-leading-xbox-drives-reviewed/"><u>[Updated] In 2024, Expand Your Gameplay  Leading Xbox Drives Reviewed</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-how-to-master-real-time-video-sharing-on-facebook/"><u>[Updated] In 2024, How to Master Real-Time Video Sharing on Facebook</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/10-free-online-sticker-makers-to-make-your-own-stickers/"><u>10 Free Online Sticker Makers to Make Your Own Stickers</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-crucial-elements-for-online-tale-artistry/"><u>2024 Approved  Crucial Elements for Online Tale Artistry</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-djis-edge-shifted-the-ultimate-mavic-air-vs-spark-showdown/"><u>2024 Approved  DJI's Edge Shifted  The Ultimate Mavic Air Vs. Spark Showdown</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-efficiently-priced-flight-machines-affordable-drones-list/"><u>2024 Approved  Efficiently Priced Flight Machines  Affordable Drones List</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-master-the-dark-and-light-iphone-silhouette-tips/"><u>2024 Approved  Master the Dark & Light  IPhone Silhouette Tips</u></a></li>
<li><a href="https://location-fake.techidaily.com/3utools-virtual-location-not-working-on-honor-v-purse-fix-now-drfone-by-drfone-virtual-android/"><u>3uTools Virtual Location Not Working On Honor V Purse? Fix Now | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/address-realtek-lan-problem-post-windows-10-upgrade/"><u>Address Realtek LAN Problem Post-Windows 10 Upgrade</u></a></li>
<li><a href="https://driver-error.techidaily.com/bridging-the-gap-fixing-hidden-bluetooth-status/"><u>Bridging the Gap: Fixing Hidden Bluetooth Status</u></a></li>
<li><a href="https://driver-error.techidaily.com/corrected-nonfunctional-realtek-interface-after-upgrade/"><u>Corrected Nonfunctional Realtek Interface After Upgrade</u></a></li>
<li><a href="https://driver-error.techidaily.com/correcting-vertical-display-errors-on-your-asus-computer/"><u>Correcting Vertical Display Errors on Your ASUS Computer</u></a></li>
<li><a href="https://driver-error.techidaily.com/driver-error-code-bcm20702a0-unavailable/"><u>Driver Error Code BCM20702A0 Unavailable</u></a></li>
<li><a href="https://driver-error.techidaily.com/ecc-error-correction-for-peripheral-drivers/"><u>ECC Error Correction for Peripheral Drivers</u></a></li>
<li><a href="https://driver-install.techidaily.com/efficient-driver-setup-microsoft-pro-4-on-pcs/"><u>Efficient Driver Setup: Microsoft Pro 4 on PCs</u></a></li>
<li><a href="https://driver-error.techidaily.com/effortless-solutions-overcoming-the-itbm-driver-access-problem/"><u>Effortless Solutions: Overcoming the ITBM Driver Access Problem</u></a></li>
<li><a href="https://driver-error.techidaily.com/enable-functional-right-click-on-windows-11-touchpad-solved/"><u>Enable Functional Right-Click on Windows 11 Touchpad [Solved]</u></a></li>
<li><a href="https://driver-error.techidaily.com/enhance-touchpad-functionality-fixed-right-click-in-windows-11/"><u>Enhance Touchpad Functionality - Fixed Right-Click in Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/expert-advice-resolving-non-responsive-hp-keyboard-problems-with-ease/"><u>Expert Advice: Resolving Non-Responsive HP Keyboard Problems with Ease</u></a></li>
<li><a href="https://driver-error.techidaily.com/expert-tips-restoring-your-qualcomm-atheros-bluetooth-connection-on-windows-vehicles-with-the-following-titles/"><u>Expert Tips: Restoring Your Qualcomm Atheros Bluetooth Connection on Windows Vehicles with the Following Titles</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/facebook-id-video-overview-length-aspect-ratio-frame-rate-for-2024/"><u>Facebook ID Video Overview  Length, Aspect Ratio, Frame Rate for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/failure-to-connect-device-due-to-missing-driver/"><u>Failure to Connect Device Due to Missing Driver</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-the-malfunction-of-your-latest-connected-usb-and-regaining-recognition-in-windows/"><u>Fixing the Malfunction of Your Latest Connected USB and Regaining Recognition in Windows</u></a></li>
<li><a href="https://driver-error.techidaily.com/graphics-installer-maneuver-victory-achieved/"><u>Graphics Installer Maneuver – Victory Achieved</u></a></li>
<li><a href="https://driver-error.techidaily.com/graphics-mastery-achieved-no-installer-woes/"><u>Graphics Mastery Achieved – No Installer Woes</u></a></li>
<li><a href="https://driver-error.techidaily.com/guide-to-kill-bluetooth-on-windows-10/"><u>Guide to Kill Bluetooth on Windows 10</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/how-automatic-high-dynamic-range-enhances-image-quality-for-2024/"><u>How Automatic High Dynamic Range Enhances Image Quality for 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-easily-update-your-amd-ryzen-drivers-step-by-step-instructions/"><u>How to Easily Update Your AMD Ryzen Drivers: Step-by-Step Instructions</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-fix-the-driver-being-installed-is-not-validated-for-this-computer/"><u>How to Fix: The Driver Being Installed Is Not Validated for This Computer</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-reset-your-iphone-13-pro-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Reset Your iPhone 13 Pro Without iTunes? | Dr.fone</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-5-traps-for-newbies-in-online-advertising-how-to-evade-them/"><u>In 2024, 5 Traps for Newbies in Online Advertising – How to Evade Them</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-erase-an-iphone-15-plus-without-apple-id-password-by-drfone-ios/"><u>In 2024, How To Erase an iPhone 15 Plus Without Apple ID Password?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-cards-of-poco-c51-without-puk-codes-by-drfone-android/"><u>In 2024, How To Unlock SIM Cards Of Poco C51 Without PUK Codes</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-quintessential-play-by-radio-stories/"><u>In 2024, Quintessential Play-by-Radio Stories</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-the-video-vault-mastering-the-art-of-live-video-storage/"><u>In 2024, The Video Vault  Mastering the Art of Live Video Storage</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-three-ways-to-sim-unlock-asus-rog-phone-7-ultimate-by-drfone-android/"><u>In 2024, Three Ways to Sim Unlock Asus ROG Phone 7 Ultimate</u></a></li>
<li><a href="https://driver-error.techidaily.com/invalid-inf-alert-installation-fixed/"><u>Invalid INF Alert: Installation Fixed</u></a></li>
<li><a href="https://driver-error.techidaily.com/keyboard-issue-in-windows-11-resolved/"><u>Keyboard Issue in Windows 11 Resolved</u></a></li>
<li><a href="https://tech-hub.techidaily.com/maximizing-your-interaction-with-bert-language-model-by-google-a-comprehensive-how-to/"><u>Maximizing Your Interaction with BERT Language Model by Google - A Comprehensive How-To</u></a></li>
<li><a href="https://driver-error.techidaily.com/navigating-and-fixing-driver-errors-efficiently/"><u>Navigating and Fixing Driver Errors Efficiently</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-non-operational-windows-enter/"><u>Overcoming Non-Operational Windows Enter</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-persistent-nvidia-driver-self-removal/"><u>Overcoming Persistent Nvidia Driver Self-Removal</u></a></li>
<li><a href="https://driver-error.techidaily.com/secrets-to-silence-wired-bluetooth-on-windows/"><u>Secrets to Silence Wired Bluetooth on Windows</u></a></li>
<li><a href="https://driver-error.techidaily.com/solve-disabled-right-click-error-in-windows-11-touchpad/"><u>Solve Disabled Right-Click Error in Windows 11 Touchpad</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-intel-wi-fi-6-ax201-malfunctioning/"><u>Solved: Intel Wi-Fi 6 Ax201 Malfunctioning</u></a></li>
<li><a href="https://win-amazing.techidaily.com/step-by-step-download-of-updated-drivers-for-your-canon-mg3600/"><u>Step-by-Step Download of Updated Drivers for Your Canon MG3600</u></a></li>
<li><a href="https://driver-error.techidaily.com/stopping-bluetooth-from-autostart-in-win11-os/"><u>Stopping Bluetooth From Autostart in Win11 OS</u></a></li>
<li><a href="https://driver-error.techidaily.com/system-complaint-non-responsive-keyboard/"><u>System Complaint: Non-Responsive Keyboard</u></a></li>
<li><a href="https://driver-error.techidaily.com/tackling-problems-with-older-usb-device-types-resolved-insights/"><u>Tackling Problems with Older USB Device Types: Resolved Insights</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-non-functional-qualcomm-atheros-bluetooth-in-windows-11-solved/"><u>Troubleshooting Non-Functional Qualcomm Atheros Bluetooth in Windows 11 [Solved]</u></a></li>
<li><a href="https://driver-error.techidaily.com/unwanted-windows-11-bluetooth-how-to-stop-it/"><u>Unwanted Windows 11 Bluetooth: How to Stop It</u></a></li>
<li><a href="https://driver-error.techidaily.com/usb-device-not-recognized-in-windows-heres-how-to-fix-it/"><u>USB Device Not Recognized in Windows? Here's How to Fix It!</u></a></li>
</ul></div>
