---
title: Reconnecting USB Gadgets in Windows 7/8 After Disconnection
date: 2024-09-04T12:48:42.669Z
updated: 2024-09-05T12:48:42.669Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Reconnecting USB Gadgets in Windows 7/8 After Disconnection
excerpt: This Article Describes Reconnecting USB Gadgets in Windows 7/8 After Disconnection
thumbnail: https://thmb.techidaily.com/acc116e7f31959c80ee46ff620abee605b240216ab77712435cda97b5c53cabd.jpg
---

## Reconnecting USB Gadgets in Windows 7/8 After Disconnection

![](https://images.drivereasy.com/wp-content/uploads/2016/08/usb-device-not-recognized.png) When you plug in your USB flash drive, a balloon warning in system tray would pop up to tell you that**USB Device Not Recognized**. Sometimes you don’t even see this notification and your USB flash driver just stops working. No worries, it’s possible and, in some cases, quite easy to fix. Here are 3 solutions for you to try. You may not need to try them all, just work your way down and find the one works for you.   **Method 1:[Reinstall USB Driver](https://versadesk.pxf.io/xyboxx) Method 2:[Update USB Driver Automatically (Recommended)](#update) Method 3: [Remove External Devices](https://laganoo.pxf.io/5g6ygn) Method 4:[Create INF Files](https://ancheer.sjv.io/y96bgp)**

## **Method 1: Reinstall USB Driver**

Faulty or outdated USB driver can render your USB devices not responding. To fix it: 1) On your keyboard, press the**Windows logo key**and**R**at the same time to invoke a Run command. Type**devmgmt.msc**in and press**Enter**.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59a9230c26f39.png)

2) Expand **Universal Serial Bus controllers**. See if you can a yellow exclamation mark in front of your**Host Controller**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/yellow-exclamation-marks-in-device-manager.jpg) If you cannot see such a device under **Universal Serial Bus controllers**, check if you can see it under**Other devices**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/unknown-device.png) 3) Double-click the device with a yellow exclamation mark. Go to**Driver**, click **Uninstall**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b6c64654e98.png) 4) Check the box for **Delete the driver software for this device**and click **OK.** ![](https://images.drivereasy.com/wp-content/uploads/2016/08/confirm-uninstall.png) 5) Reboot your computer with the USB flash drive connected. See if Microsoft helps you detect and install the new USB driver. If you have more than one**Host Controllers** with the yellow exclamation marks in front, repeat these procedures more than once.

## Method 2: Update USB driver automatically

If Microsoft fails to find the latest version of the USB driver for you, you might need to search for it by yourself. If you don’t have the time, patience or computer skills to update your drivers manually, you can do it automatically with [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/). Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version it takes just 2 clicks (and you get full support and a 30-day money back guarantee): 1)[**Download**](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy. 2) Run Driver Easy and click the**Scan Now**button. Driver Easy will then scan your computer and detect any problem drivers. ![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58e60dbd97325.png) 3) Click the**Update**button next to the flagged USB device to automatically download and install the correct version of this driver (you can do this with the FREE version). Or click**Update All**to automatically download and install the correct version of all the drivers that are missing or out of date on your system (this requires the [**Pro version**](https://tools.techidaily.com/drivereasy/download/)– you’ll be prompted to upgrade when you click Update All). ![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58e60dd5d26f7.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997680/19272" target="_top" id="1997680">
  <img src="//a.impactradius-go.com/display-ad/19272-1997680" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997680/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **Method 3: Remove External Devices**

If there are too many USB devices connected to your PC, some of them might not respond or work properly. To fix it, you can try clean restart your PC: Remove or disconnect all unnecessary discs and devices from your computer. Make sure that the computer is off, and then remove any discs and USB devices and the memory cards from the card reader slot. Disconnect non-essential devices such as camera, MP3-playersprinters, scanners, external hard drives etc., and leave mouse, keyboard and monitor connected. If you are a**laptop**user: 1) Turn off the computer and make sure you have disabled or disconnected all unnecessary external devices. Remove the computer from any port replicator or docking station. 2) Unplug the AC adapter from the computer and remove the battery from the battery compartment. 3) Press and hold the**Power**button for about 15 seconds to drain any residual electrical charge from the capacitors that protect the memory. 4) Insert the battery and AC adapter back into the laptop, but make sure you don’t connect any external devices just yet. 5) Press**Power**button to turn on the computer. Then reconnect the USB devices one by one. If you are using**desktop**: 1) Turn off the computer completely and disconnect the power cord from the back of the computer. 2) Press the power button on the computer for 5 seconds. 3) Reconnect the power cord and turn on the power. Then reconnect the USB devices one by one.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934292/19272" target="_top" id="1934292">
  <img src="//a.impactradius-go.com/display-ad/19272-1934292" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934292/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **Method 4: Create INF Files**

1) Go to**C:\\Windows\\inf**folder. Make sure you can see these files listed: (there could be other files)**usb.inf,** **usb2.inf,** **usbport.inf,** **usbprint.inf,** **usbstor.inf,** **usbvideo.inf** ![](https://images.drivereasy.com/wp-content/uploads/2016/08/usb-inf-file-folder.jpg) 3) If some of the above files are missing, you need to create them. If you have another computer with all the USB ports well functioned, look for the files in that computer, copy and paste them here. 4) If you don’t have another computer, here is the alternative for you. Download the mentioned files from this webpage <http://www.infdump.com/>. You can find the files by searching with the name of the files. Download the files**usb.inf,** **usb2.inf,** **usbport.inf,** **usbprint.inf,** **usbstor.inf,** **usbvideo.inf**, one by one. You can save them directly to the **C:\\Windows\\inf** folder when you are downloading or you can copy them to the**C:\\Windows\\inf** folder all together after you have downloaded all of them. 5) After the files are replaced or created, you need to unplug all of your USB devices and then plug them back in again. If necessary, you can also do a reboot. **Related post:** **[What to do if USB not recognized in Windows 10?](https://tools.techidaily.com/drivereasy/download/)**

<!-- affiliate ads begin -->
<span id="2135472">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2135472.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2135472">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2135472.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2135472%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2135472/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://instagram-videos.techidaily.com/1716183822170-new-2024-approved-how-to-get-more-instagram-video-views/"><u>[New] 2024 Approved  How to Get More Instagram Video Views?</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-your-picture-at-a-glance-quick-steps-for-saving-social-media-pics-for-2024/"><u>[New] Your Picture at a Glance  Quick Steps for Saving Social Media Pics for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-the-driver-detected-a-controller-error-on-deviceharddisk1dr1-or-dr3/"><u>[Solved] The Driver Detected a Controller Error on DeviceHarddisk1DR1 or DR3</u></a></li>
<li><a href="https://driver-error.techidaily.com/update-hardware-and-dev-driver-operational-on-win/"><u>[Update: Hardware & Dev Driver Operational on Win</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-in-2024-blades-vivid-palette-now-in-stunning-4k-clarity/"><u>[Updated] In 2024, Blade's Vivid Palette, Now in Stunning 4K Clarity</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-top-10-iphone-lens-capabilities-in-ios-11/"><u>[Updated] Top 10 iPhone Lens Capabilities in iOS 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/cant-switch-bluetooth-off-my-laptop-is-frozen/"><u>Can't Switch Bluetooth OFF - My Laptop Is Frozen</u></a></li>
<li><a href="https://driver-error.techidaily.com/clearing-up-the-driver-hurdle-hd/"><u>Clearing Up the Driver Hurdle (HD)</u></a></li>
<li><a href="https://driver-error.techidaily.com/comprehensive-solution-for-the-missing-coprocessor-driver-error-in-windows-10/"><u>Comprehensive Solution for the 'Missing Coprocessor Driver' Error in Windows 10</u></a></li>
<li><a href="https://unlock-android.techidaily.com/delete-gmail-account-withwithout-password-on-xiaomi-13t-pro-by-drfone-android/"><u>Delete Gmail Account With/Without Password On Xiaomi 13T Pro</u></a></li>
<li><a href="https://driver-error.techidaily.com/device-support-added-to-win-8-desktop/"><u>Device Support Added to Win 8 Desktop</u></a></li>
<li><a href="https://driver-error.techidaily.com/effortlessly-fixing-windows-11s-elan-tap-mishaps/"><u>Effortlessly Fixing Windows 11'S Elan Tap Mishaps</u></a></li>
<li><a href="https://driver-error.techidaily.com/error-cleaned-correctly-configuring-your-device-code-1-explanation/"><u>Error Cleaned: Correctly Configuring Your Device (Code 1 Explanation)</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-network-controller-driver-issue-on-dell-laptop/"><u>Fix Network Controller Driver Issue on Dell Laptop</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-wd-ses-usb-device-issue/"><u>Fix WD SES USB Device Issue</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-qualcomm-wireless-network-adapter-issues-on-windows-11-a-comprehensive-guide/"><u>Fixing Qualcomm Wireless Network Adapter Issues on Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-boot-into-safe-mode-and-remove-your-graphics-card-driver-in-windows-8/"><u>How to Boot Into Safe Mode and Remove Your Graphics Card Driver in Windows 8</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-repair-broken-qualcomm-atheros-bluetooth-drivers-in-windows-11-detailed-guide/"><u>How to Repair Broken Qualcomm Atheros Bluetooth Drivers in Windows 11 [Detailed Guide]</u></a></li>
<li><a href="https://driver-error.techidaily.com/immediate-action-plan-for-mtp-connection-errors/"><u>Immediate Action Plan for MTP Connection Errors</u></a></li>
<li><a href="https://driver-error.techidaily.com/immediate-solutions-for-driver-not-available-on-itbm-system-effortless-troubleshooting-guide/"><u>Immediate Solutions for 'Driver Not Available' On ITBM System - Effortless Troubleshooting Guide</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-can-we-unlock-our-nokia-c110-phone-screen-by-drfone-android/"><u>In 2024, How Can We Unlock Our Nokia C110 Phone Screen?</u></a></li>
<li><a href="https://buynow-help.techidaily.com/in-depth-evaluation-of-the-third-gen-apple-tv-4k-streaming-box/"><u>In-Depth Evaluation of the Third Gen Apple TV 4K Streaming Box</u></a></li>
<li><a href="https://driver-error.techidaily.com/mastered-the-challenge-of-error-45/"><u>Mastered the Challenge of Error #45</u></a></li>
<li><a href="https://tech-hub.techidaily.com/maximizing-efficiency-discover-the-leading-8-artificial-intelligence-chrome-extensions/"><u>Maximizing Efficiency: Discover the Leading 8 Artificial Intelligence Chrome Extensions</u></a></li>
<li><a href="https://driver-error.techidaily.com/nvidia-drivers-installed-smoothly/"><u>Nvidia Drivers Installed Smoothly</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcome-asus-camera-errors-in-windows-11-os/"><u>Overcome ASUS Camera Errors in Windows 11 OS</u></a></li>
<li><a href="https://driver-error.techidaily.com/pci-simple-communications-controller-driver-issue-solved/"><u>PCI Simple Communications Controller Driver Issue [Solved]</u></a></li>
<li><a href="https://driver-error.techidaily.com/purging-illegal-configurations-from-inf-service-section/"><u>Purging Illegal Configurations From INF Service Section</u></a></li>
<li><a href="https://driver-error.techidaily.com/released-irql-anomaly-in-win11/"><u>Released: Irql Anomaly in Win11</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-adding-the-required-drivers-to-operate-devices-on-windows-1187-systems/"><u>Resolved: Adding the Required Drivers to Operate Devices on Windows 11/8/7 Systems</u></a></li>
<li><a href="https://driver-error.techidaily.com/restore-your-hp-laptops-keyboard-functionality-quick-fix-for-the-inactive-keys-syndrome-article-name-356-characters/"><u>Restore Your HP Laptop's Keyboard Functionality: Quick Fix For the 'Inactive Keys’ Syndrome - Article Name — 356 Characters</u></a></li>
<li><a href="https://driver-error.techidaily.com/silenced-hard-drive-error-signals/"><u>Silenced Hard Drive Error Signals</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/strategic-approach-to-dealing-with-youtube-copyright-claims-for-2024/"><u>Strategic Approach to Dealing With YouTube Copyright Claims for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/streamlining-hardware-compatibility-in-win11/"><u>Streamlining Hardware Compatibility in WIN11</u></a></li>
<li><a href="https://driver-error.techidaily.com/successful-resolution-of-asus-webcam-on-windows-10/"><u>Successful Resolution of ASUS Webcam on Windows 10</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-20-mobiles-transforming-dji-aerial-video-art-for-2024/"><u>Top 20 Mobiles Transforming DJi Aerial Video Art for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/trim-mkv-files-on-mac-the-top-3-software/"><u>Trim MKV Files on Mac The Top 3 Software</u></a></li>
<li><a href="https://techidaily.com/undeleted-lost-videos-from-smart-8-by-fonelab-android-recover-video/"><u>Undeleted lost videos from Smart 8</u></a></li>
<li><a href="https://driver-error.techidaily.com/upgraded-hat-support-on-the-latest-windows-os/"><u>Upgraded HAT Support on the Latest Windows OS</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/viral-success-the-most-loved-ae-themes-for-social-media/"><u>Viral Success  The Most Loved AE Themes for Social Media</u></a></li>
</ul></div>
