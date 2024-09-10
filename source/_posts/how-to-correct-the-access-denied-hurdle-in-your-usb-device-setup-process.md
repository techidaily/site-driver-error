---
title: How To Correct the 'Access Denied' Hurdle in Your USB Device Setup Process
date: 2024-09-09T03:08:13.864Z
updated: 2024-09-10T03:08:13.864Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes How To Correct the 'Access Denied' Hurdle in Your USB Device Setup Process
excerpt: This Article Describes How To Correct the 'Access Denied' Hurdle in Your USB Device Setup Process
thumbnail: https://thmb.techidaily.com/fed3ffae9229ff3a7d3580519bb324f0e6bad8a6cd96fa55cbded24321f049a3.jpg
---

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134241/18498" target="_top" id="2134241">
  <img src="//a.impactradius-go.com/display-ad/18498-2134241" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134241/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How To Correct the 'Access Denied' Hurdle in Your USB Device Setup Process

If you can’t install any new USB devices due to error “Access is denied”, it can be frustrating. But don’t worry, here you will find the solution to fix the problem.  
  
![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57c6862c6dbe8.png) .

First, make sure that you login to computer as Administrator. If you are not logged in with Administrator, follow steps below to switch it to Administrator.  
  
1\. Go to**Control Panel**and View by**Category**. Click**User Accounts**.(In your case, this may be “User Accounts and Family Safety”.)  
  
![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57c68c5d7bf6a.jpg)
  
<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2135316/14409" target="_top" id="2135316">
  <img src="//a.impactradius-go.com/display-ad/14409-2135316" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2135316/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2\. Click **Change your account type** and enter your password if necessary.
  
![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_5791ba4e50787.png)
  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132160/7443" target="_top" id="2132160">
  <img src="//a.impactradius-go.com/display-ad/7443-2132160" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132160/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3\. Then click**Start** button and choose to **Log off**  of Windows, and then log back in again.
  
![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_5791bab2104ee.png)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123509/26400" target="_top" id="2123509">
  <img src="//a.impactradius-go.com/display-ad/26400-2123509" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123509/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
After that, reinstall the driver again.  
  
 **Turn off any antivirus or anti-spyware program**
  
If you are using an Administrator account and the problem persists, turn off any antivirus and anti-spyware program temporarily. This will work if the update is blocked by these program.
  
**Give permission to USBSTOR registry key**
  
If the problem could not be resolved, the USBSTOR registry key most probably has denied access to SYSTEM account. Follow these steps and give permission to USBSTOR registry key.
  
1\. Press**Win+R**(Windows key and R key) at the same time. A Run dialog will open.  
2\. Type**regedit**in the run box and click**OK**button.
  
![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57c6905ba04f8.png)
  
 3\. Go to **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Services\\USBSTOR.** Right-click on it and select**Permissions…** from the context menu.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57c692c5d030c.jpg)
  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135409/19272" target="_top" id="2135409">
  <img src="//a.impactradius-go.com/display-ad/19272-2135409" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135409/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 4\. Select**SYSTEM** from the Group or user names. In Permissions for SYSTEM section, make sure the Full Control Allow checkbox is checked and uncheck any Deny checkbox. Click Apply button to apply the changes.  
  
![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57c6933c3f709.png)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137214/26400" target="_top" id="2137214">
  <img src="//a.impactradius-go.com/display-ad/26400-2137214" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137214/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Also check your user account and see if it has full control of the system and any deny checkbox is unchecked.

 After that, update the USB driver again and it should work this time.

 You can update drivers manually, but it could take forever. You can also update drivers through Windows Update, which may fail to provide new drivers. If you want to update drivers more easily and successfully, you can consider using Driver Easy to update the driver automatically, which can scan your computer and detect all problem drivers in 20 seconds, then give you a list of new drivers. Click [here](https://tools.techidaily.com/drivereasy/download/) to download Driver Easy now.
 Driver Easy has Free version and Professional version. Both versions can be used to download drivers automatically. But with Professional version, you can even update all drivers with 1 click. No time is wasted. More importantly, you will enjoy Free technical support guarantee and money-back guarantee. You can ask for further assistance regarding any driver issue. And you can ask for a full refund for any reason.

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
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-discover-the-ultimate-5-gaming-webcam-winners-for-streaming/"><u>[New] 2024 Approved Discover the Ultimate 5 Gaming Webcam Winners for Streaming</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-shoppers-ultimate-list-of-top-rated-webcams/"><u>[New] 2024 Approved Shopper’s Ultimate List of Top-Rated Webcams</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-the-driver-detected-a-controller-error-on-deviceharddisk1dr1-or-dr3/"><u>[Solved] The Driver Detected a Controller Error on DeviceHarddisk1DR1 or DR3</u></a></li>
<li><a href="https://driver-error.techidaily.com/update-hardware-and-dev-driver-operational-on-win/"><u>[Update: Hardware & Dev Driver Operational on Win</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-battle-for-asgard-the-ragnarok-chronicles-for-2024/"><u>[Updated] Battle for Asgard The Ragnarök Chronicles for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-unlocking-the-potential-of-mobile-video-conferencing/"><u>2024 Approved Unlocking the Potential of Mobile Video Conferencing</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-htc-u23-pro-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your HTC U23 Pro</u></a></li>
<li><a href="https://driver-error.techidaily.com/cant-switch-bluetooth-off-my-laptop-is-frozen/"><u>Can't Switch Bluetooth OFF - My Laptop Is Frozen</u></a></li>
<li><a href="https://driver-error.techidaily.com/clearing-up-the-driver-hurdle-hd/"><u>Clearing Up the Driver Hurdle (HD)</u></a></li>
<li><a href="https://driver-error.techidaily.com/comprehensive-solution-for-the-missing-coprocessor-driver-error-in-windows-10/"><u>Comprehensive Solution for the 'Missing Coprocessor Driver' Error in Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/device-support-added-to-win-8-desktop/"><u>Device Support Added to Win 8 Desktop</u></a></li>
<li><a href="https://android-unlock.techidaily.com/downloading-samfw-frp-tool-30-for-lava-storm-5g-by-drfone-android/"><u>Downloading SamFw FRP Tool 3.0 for Lava Storm 5G</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-network-controller-driver-issue-on-dell-laptop/"><u>Fix Network Controller Driver Issue on Dell Laptop</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-qualcomm-wireless-network-adapter-issues-on-windows-11-a-comprehensive-guide/"><u>Fixing Qualcomm Wireless Network Adapter Issues on Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-boot-into-safe-mode-and-remove-your-graphics-card-driver-in-windows-8/"><u>How to Boot Into Safe Mode and Remove Your Graphics Card Driver in Windows 8</u></a></li>
<li><a href="https://driver-error.techidaily.com/immediate-solutions-for-driver-not-available-on-itbm-system-effortless-troubleshooting-guide/"><u>Immediate Solutions for 'Driver Not Available' On ITBM System - Effortless Troubleshooting Guide</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-stop-my-spouse-from-spying-on-my-sony-xperia-10-v-drfone-by-drfone-virtual-android/"><u>In 2024, How to Stop My Spouse from Spying on My Sony Xperia 10 V | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/iphone-11-pro-data-recovery-software-to-recover-lost-ios-data-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>iPhone 11 Pro® Data Recovery Software to Recover Lost iOS® Data | Stellar</u></a></li>
<li><a href="https://some-approaches.techidaily.com/mac-mastery-enhance-storage-and-quality-with-dvd-shrink-the-ultimate-guide-to-dvd-ripping-and-compression/"><u>Mac Mastery: Enhance Storage and Quality with DVD Shrink - The Ultimate Guide to DVD Ripping & Compression</u></a></li>
<li><a href="https://driver-error.techidaily.com/mastered-the-challenge-of-error-45/"><u>Mastered the Challenge of Error #45</u></a></li>
<li><a href="https://hardware-help.techidaily.com/mastering-the-setup-a-guide-to-downloading-and-installing-arduino-nano-drivers-on-your-windows-computer/"><u>Mastering the Setup: A Guide to Downloading and Installing Arduino Nano Drivers on Your Windows Computer</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigate-the-world-of-computer-components-with-confidence-guidance-from-toms-hardware/"><u>Navigate the World of Computer Components with Confidence - Guidance From Tom's Hardware</u></a></li>
<li><a href="https://driver-error.techidaily.com/nvidia-drivers-installed-smoothly/"><u>Nvidia Drivers Installed Smoothly</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcome-asus-camera-errors-in-windows-11-os/"><u>Overcome ASUS Camera Errors in Windows 11 OS</u></a></li>
<li><a href="https://driver-error.techidaily.com/purging-illegal-configurations-from-inf-service-section/"><u>Purging Illegal Configurations From INF Service Section</u></a></li>
<li><a href="https://driver-error.techidaily.com/released-irql-anomaly-in-win11/"><u>Released: Irql Anomaly in Win11</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-adding-the-required-drivers-to-operate-devices-on-windows-1187-systems/"><u>Resolved: Adding the Required Drivers to Operate Devices on Windows 11/8/7 Systems</u></a></li>
<li><a href="https://driver-error.techidaily.com/restore-your-hp-laptops-keyboard-functionality-quick-fix-for-the-inactive-keys-syndrome-article-name-356-characters/"><u>Restore Your HP Laptop's Keyboard Functionality: Quick Fix For the 'Inactive Keys’ Syndrome - Article Name — 356 Characters</u></a></li>
<li><a href="https://driver-error.techidaily.com/silenced-hard-drive-error-signals/"><u>Silenced Hard Drive Error Signals</u></a></li>
<li><a href="https://driver-error.techidaily.com/successful-resolution-of-asus-webcam-on-windows-10/"><u>Successful Resolution of ASUS Webcam on Windows 10</u></a></li>
<li><a href="https://extra-tips.techidaily.com/unlock-clarity-in-photos-leading-10-online-edits-at-a-glance/"><u>Unlock Clarity in Photos Leading 10 Online Edits at a Glance</u></a></li>
<li><a href="https://facebook.techidaily.com/virtual-reality-on-facebook-3-red-flags-to-note/"><u>Virtual Reality on Facebook – 3 Red Flags to Note</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/your-ultimate-guide-to-downloading-thrones-tunes-online/"><u>Your Ultimate Guide to Downloading Thrones Tunes Online</u></a></li>
</ul></div>
