---
title: Fixing Ethernet Driver Not Working After Upgrade
date: 2024-07-15T06:57:58.224Z
updated: 2024-07-16T06:57:58.224Z
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
<li><a href="https://driver-error.techidaily.com/resolution-unlit-mouse-on-modern-os/"><u>[Resolution] Unlit Mouse on Modern OS</u></a></li>
<li><a href="https://howto.techidaily.com/my-videos-arent-playing-on-samsung-galaxy-f54-5g-what-can-i-do-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>My Videos Arent Playing on Samsung Galaxy F54 5G – What Can I Do? | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/enhancing-system-performance-by-troubleshooting-devices-dm/"><u>Enhancing System Performance by Troubleshooting Devices (DM)</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-kakaotalk-elites-flash-chats-on-snapchat/"><u>[New] In 2024, KakaoTalk Elites' Flash Chats on Snapchat</u></a></li>
<li><a href="https://driver-error.techidaily.com/bridging-gap-uncover-missing-bluetooth-manage-panel/"><u>Bridging Gap: Uncover Missing Bluetooth, Manage Panel</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-and-set-up-necessary-device-drivers-in-windows-11-8-or-7-a-step-by-step-solution/"><u>Fix and Set Up Necessary Device Drivers in Windows 11, 8 or 7 - A Step-by-Step Solution</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-saving-the-essence-a-guide-for-virtual-meeting-records/"><u>[New] Saving the Essence  A Guide for Virtual Meeting Records</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/additional-tips-about-sinnoh-stone-for-motorola-moto-g73-5g-drfone-by-drfone-virtual-android/"><u>Additional Tips About Sinnoh Stone For Motorola Moto G73 5G | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/happy-hours-wacom-all-systems-go/"><u>Happy Hours: Wacom, All Systems Go</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-host-controller-accessibility/"><u>Fix Host Controller Accessibility</u></a></li>
<li><a href="https://driver-error.techidaily.com/blackberry-z10-not-detected-by-debian-wheezy-issue-fixed/"><u>Blackberry Z10 Not Detected by Debian Wheezy - Issue Fixed</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-adb-device-not-found-error-on-windows/"><u>[Solved] ADB Device Not Found Error on Windows</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-your-laptops-nonfunctional-hp-keyboard-in-simply-steps-article-name-358-characters/"><u>Fix Your Laptop's 'Nonfunctional’ HP Keyboard in Simply Steps - Article Name — 358 Characters</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-usb-installation-problems-overcoming-access-denied/"><u>Troubleshooting USB Installation Problems: Overcoming 'Access Denied'</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-mastering-discord-gifs-the-ultimate-communication-tool-for-teams-for-2024/"><u>[New] Mastering Discord GIFs  The Ultimate Communication Tool for Teams for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-easily-obtain-and-update-essential-software-for-your-hp-envy-series-20-device/"><u>How to Easily Obtain & Update Essential Software for Your HP Envy Series 20 Device</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-the-5-best-gaming-keyboards-under-100/"><u>[Updated] The 5 Best Gaming Keyboards Under 100$</u></a></li>
<li><a href="https://driver-error.techidaily.com/unused-capacity-in-system-resources/"><u>Unused Capacity in System Resources</u></a></li>
<li><a href="https://driver-error.techidaily.com/nvidia-unseen-in-multiple-oses/"><u>Nvidia Unseen in Multiple OSes</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/unveiling-horizon-based-approaches-to-post-on-igtv/"><u>Unveiling Horizon-Based Approaches to Post on IGTV</u></a></li>
<li><a href="https://driver-error.techidaily.com/battleye-initialization-failure-resolving-the-driver-loading-error-code-1450/"><u>BattlEye Initialization Failure - Resolving the Driver Loading Error Code 1450</u></a></li>
<li><a href="https://driver-error.techidaily.com/hd-audio-hub-fix-resolved-error-message/"><u>HD Audio Hub Fix - Resolved Error Message</u></a></li>
<li><a href="https://driver-error.techidaily.com/functional-reactivation-achieved/"><u>Functional Reactivation Achieved</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-vertical-playback-problems-correcting-the-orientation-of-videos-on-your-asus-notebook/"><u>Resolving Vertical Playback Problems: Correcting the Orientation of Videos on Your ASUS Notebook</u></a></li>
<li><a href="https://driver-error.techidaily.com/driver-not-found-bcm20702a0/"><u>Driver Not Found: BCM20702A0</u></a></li>
<li><a href="https://vp-tips.techidaily.com/the-art-of-selecting-podcasts-for-iphone-devices/"><u>The Art of Selecting Podcasts for iPhone Devices</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-10-reinstalls-faulty-realtek-drivers-correctly/"><u>Windows 10 Reinstalls Faulty Realtek Drivers Correctly</u></a></li>
<li><a href="https://driver-error.techidaily.com/effortless-solutions-to-the-itbm-driver-missing-problem/"><u>Effortless Solutions to the 'ITBM Driver Missing' Problem</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-interlinked-upload-sharing-content-via-twt-plus-tumble/"><u>In 2024, Interlinked Upload  Sharing Content via Twt + Tumble</u></a></li>
<li><a href="https://driver-error.techidaily.com/easy-steps-on-how-to-fetch-newest-driver-software-for-the-hp-envy-20/"><u>Easy Steps on How to Fetch Newest Driver Software for the HP Envy 20</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-rtx-graphics-issues-in-gaming-heres-how-to-quickly-optimize/"><u>[Solved]: RTX Graphics Issues in Gaming – Here's How to Quickly Optimize</u></a></li>
<li><a href="https://driver-error.techidaily.com/regaining-normal-enter-behavior-on-windows/"><u>Regaining Normal Enter Behavior on Windows</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/still-using-pattern-locks-with-poco-c51-tips-tricks-and-helpful-advice-by-drfone-android/"><u>Still Using Pattern Locks with Poco C51? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-ways-to-make-sure-your-facebook-video-cover-size-is-perfect/"><u>New 2024 Approved Ways To Make Sure Your Facebook Video Cover Size Is Perfect</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-dream-houses-in-minecraft-top-6-ideas-for-2024/"><u>[Updated] Dream Houses in Minecraft  Top 6 Ideas for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/device-restricts-vehicle-loading/"><u>Device Restricts Vehicle Loading</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-6-methods-to-protect-yourself-from-location-tracking-on-apple-iphone-xr-drfone-by-drfone-virtual-ios/"><u>In 2024, 6 Methods to Protect Yourself from Location Tracking on Apple iPhone XR | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/optical-drive-non-appearance-in-win11/"><u>Optical Drive Non-Appearance in Win11</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-pause-life360-location-sharing-for-oneplus-nord-ce-3-lite-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How To Pause Life360 Location Sharing For OnePlus Nord CE 3 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-2024-approved-precision-audio-leveling-in-three-simple-steps/"><u>Updated 2024 Approved Precision Audio Leveling in Three Simple Steps</u></a></li>
<li><a href="https://driver-error.techidaily.com/fast-tracking-your-way-through-windows-drivers/"><u>Fast-Tracking Your Way Through Windows Drivers</u></a></li>
<li><a href="https://driver-error.techidaily.com/persistent-nvidia-driver-auto-uninstall-mystery-solved/"><u>Persistent Nvidia Driver Auto-Uninstall Mystery Solved</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-in-depth-analysis-understanding-google-podcasts-app/"><u>[Updated] 2024 Approved  In-Depth Analysis  Understanding Google Podcasts App</u></a></li>
<li><a href="https://driver-error.techidaily.com/guide-to-fixing-unsupported-hardware-warnings-in-idt-system-compatibility-tips-and-tricks/"><u>Guide to Fixing 'Unsupported Hardware' Warnings in IDT System – Compatibility Tips & Tricks</u></a></li>
<li><a href="https://driver-error.techidaily.com/mastering-the-recovery-of-amds-radeon-wattman-overcoming-crash-and-default-restore-hurdles/"><u>Mastering the Recovery of AMD's Radeon WattMan: Overcoming Crash and Default Restore Hurdles</u></a></li>
<li><a href="https://driver-error.techidaily.com/ultimate-guide-updating-and-downloading-drivers-for-your-hp-envy-20-laptop/"><u>Ultimate Guide: Updating and Downloading Drivers for Your HP Envy 20 Laptop</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-intel-high-definition-audio-driver-issues-on-windows-10/"><u>[Solved] Intel High Definition Audio Driver Issues on Windows 10</u></a></li>
<li><a href="https://techidaily.com/video-fixer-software-for-all-corrupt-videos-of-vivo-y27-4g-by-stellar-video-repair-mobile-video-repair/"><u>Video Fixer Software for all Corrupt Videos of Vivo Y27 4G</u></a></li>
<li><a href="https://driver-error.techidaily.com/dissecting-microsofts-ms-bda-vision/"><u>Dissecting Microsoft's MS BDA Vision</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-restore-functionality-of-your-malfunctioning-hp-bluetooth-keypad/"><u>How To Restore Functionality of Your Malfunctioning HP Bluetooth Keypad?</u></a></li>
<li><a href="https://driver-error.techidaily.com/qualcomm-atheros-bluetooth-driver-fix-for-windows-11-expert-tips-and-tricks/"><u>Qualcomm Atheros Bluetooth Driver Fix for Windows 11: Expert Tips and Tricks!</u></a></li>
<li><a href="https://driver-error.techidaily.com/amd-radeon-r7-250-graphics-driver-problems-on-windows-10-solved/"><u>AMD Radeon R7 250 Graphics Driver Problems on Windows 10 [Solved]</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-how-to-add-audio-effects-to-your-video-with-ease-for-2024/"><u>Updated How to Add Audio Effects to Your Video with Ease for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-click-jams-in-windows-10/"><u>Fixing Click Jams in Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/coprocessor-driver-missing-on-windows-11-solved/"><u>Coprocessor Driver Missing on Windows 11 [Solved]</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-successfully-update-and-install-drivers-for-your-device-on-microsoft-windows-10-8-7-solved/"><u>How to Successfully Update and Install Drivers for Your Device on Microsoft Windows (10, 8, 7) [SOLVED]</u></a></li>
</ul></div>
