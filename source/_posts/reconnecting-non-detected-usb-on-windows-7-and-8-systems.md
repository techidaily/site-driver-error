---
title: Reconnecting Non-Detected USB on Windows 7 & 8 Systems
date: 2024-08-22T14:13:20.546Z
updated: 2024-08-23T14:13:20.546Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Reconnecting Non-Detected USB on Windows 7 & 8 Systems
excerpt: This Article Describes Reconnecting Non-Detected USB on Windows 7 & 8 Systems
thumbnail: https://thmb.techidaily.com/2cd3ca0cbeb8c4e3cd0fc34413344036f23c5912ab89cbe4dfebf3e1ac0d9691.jpg
---

## Reconnecting Non-Detected USB on Windows 7 & 8 Systems

![](https://images.drivereasy.com/wp-content/uploads/2016/08/usb-device-not-recognized.png) When you plug in your USB flash drive, a balloon warning in system tray would pop up to tell you that**USB Device Not Recognized**. Sometimes you don’t even see this notification and your USB flash driver just stops working. No worries, it’s possible and, in some cases, quite easy to fix. Here are 3 solutions for you to try. You may not need to try them all, just work your way down and find the one works for you.   **Method 1:[Reinstall USB Driver](https://versadesk.pxf.io/xyboxx) Method 2:[Update USB Driver Automatically (Recommended)](#update) Method 3: [Remove External Devices](https://laganoo.pxf.io/5g6ygn) Method 4:[Create INF Files](https://ancheer.sjv.io/y96bgp)**

## **Method 1: Reinstall USB Driver**

Faulty or outdated USB driver can render your USB devices not responding. To fix it: 1) On your keyboard, press the**Windows logo key**and**R**at the same time to invoke a Run command. Type**devmgmt.msc**in and press**Enter**.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59a9230c26f39.png)

2) Expand **Universal Serial Bus controllers**. See if you can a yellow exclamation mark in front of your**Host Controller**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/yellow-exclamation-marks-in-device-manager.jpg) If you cannot see such a device under **Universal Serial Bus controllers**, check if you can see it under**Other devices**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/unknown-device.png) 3) Double-click the device with a yellow exclamation mark. Go to**Driver**, click **Uninstall**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b6c64654e98.png) 4) Check the box for **Delete the driver software for this device**and click **OK.** ![](https://images.drivereasy.com/wp-content/uploads/2016/08/confirm-uninstall.png) 5) Reboot your computer with the USB flash drive connected. See if Microsoft helps you detect and install the new USB driver. If you have more than one**Host Controllers** with the yellow exclamation marks in front, repeat these procedures more than once.

## Method 2: Update USB driver automatically

If Microsoft fails to find the latest version of the USB driver for you, you might need to search for it by yourself. If you don’t have the time, patience or computer skills to update your drivers manually, you can do it automatically with [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/). Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version it takes just 2 clicks (and you get full support and a 30-day money back guarantee): 1)[**Download**](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy. 2) Run Driver Easy and click the**Scan Now**button. Driver Easy will then scan your computer and detect any problem drivers. ![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58e60dbd97325.png) 3) Click the**Update**button next to the flagged USB device to automatically download and install the correct version of this driver (you can do this with the FREE version). Or click**Update All**to automatically download and install the correct version of all the drivers that are missing or out of date on your system (this requires the [**Pro version**](https://tools.techidaily.com/drivereasy/download/)– you’ll be prompted to upgrade when you click Update All). ![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58e60dd5d26f7.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## **Method 3: Remove External Devices**

If there are too many USB devices connected to your PC, some of them might not respond or work properly. To fix it, you can try clean restart your PC: Remove or disconnect all unnecessary discs and devices from your computer. Make sure that the computer is off, and then remove any discs and USB devices and the memory cards from the card reader slot. Disconnect non-essential devices such as camera, MP3-playersprinters, scanners, external hard drives etc., and leave mouse, keyboard and monitor connected. If you are a**laptop**user: 1) Turn off the computer and make sure you have disabled or disconnected all unnecessary external devices. Remove the computer from any port replicator or docking station. 2) Unplug the AC adapter from the computer and remove the battery from the battery compartment. 3) Press and hold the**Power**button for about 15 seconds to drain any residual electrical charge from the capacitors that protect the memory. 4) Insert the battery and AC adapter back into the laptop, but make sure you don’t connect any external devices just yet. 5) Press**Power**button to turn on the computer. Then reconnect the USB devices one by one. If you are using**desktop**: 1) Turn off the computer completely and disconnect the power cord from the back of the computer. 2) Press the power button on the computer for 5 seconds. 3) Reconnect the power cord and turn on the power. Then reconnect the USB devices one by one.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **Method 4: Create INF Files**

1) Go to**C:\\Windows\\inf**folder. Make sure you can see these files listed: (there could be other files)**usb.inf,** **usb2.inf,** **usbport.inf,** **usbprint.inf,** **usbstor.inf,** **usbvideo.inf** ![](https://images.drivereasy.com/wp-content/uploads/2016/08/usb-inf-file-folder.jpg) 3) If some of the above files are missing, you need to create them. If you have another computer with all the USB ports well functioned, look for the files in that computer, copy and paste them here. 4) If you don’t have another computer, here is the alternative for you. Download the mentioned files from this webpage <http://www.infdump.com/>. You can find the files by searching with the name of the files. Download the files**usb.inf,** **usb2.inf,** **usbport.inf,** **usbprint.inf,** **usbstor.inf,** **usbvideo.inf**, one by one. You can save them directly to the **C:\\Windows\\inf** folder when you are downloading or you can copy them to the**C:\\Windows\\inf** folder all together after you have downloaded all of them. 5) After the files are replaced or created, you need to unplug all of your USB devices and then plug them back in again. If necessary, you can also do a reboot. **Related post:** **[What to do if USB not recognized in Windows 10?](https://tools.techidaily.com/drivereasy/download/)**

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
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
<li><a href="https://facebook-video-content.techidaily.com/new-facebooks-brief-broadcasts-unpacked/"><u>[New] Facebook's Brief Broadcasts Unpacked</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-innovative-virtual-bike-trails-unveiled/"><u>[New] Innovative Virtual Bike Trails Unveiled</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-master-windows-10s-native-features-to-cut-videos-instantly/"><u>[New] Master Windows 10'S Native Features to Cut Videos Instantly</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-easy-customization-free-youtube-visual-templates/"><u>[Updated] 2024 Approved  Easy Customization  Free YouTube Visual Templates</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-expert-tips-capturing-high-quality-whatsapp-voice-transcripts/"><u>[Updated] 2024 Approved  Expert Tips  Capturing High-Quality WhatsApp Voice Transcripts</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-securing-memories-how-to-obtain-facebooks-live-videos/"><u>[Updated] 2024 Approved  Securing Memories  How to Obtain Facebook's Live Videos</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-2024-approved-tonal-trails-the-journey-of-audio-blending/"><u>[Updated] 2024 Approved  Tonal Trails  The Journey of Audio Blending</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-from-raw-to-rad-turning-up-the-heat-with-snapchat-filters/"><u>[Updated] From Raw to Rad  Turning Up the Heat with Snapchat Filters</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-maximize-your-virtual-meetings-with-top-6-webcams-for-zoom/"><u>[Updated] Maximize Your Virtual Meetings with Top 6 Webcams for Zoom</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-avoid-common-errors-while-spinning-videos-in-android-apps/"><u>2024 Approved  Avoid Common Errors While Spinning Videos in Android Apps</u></a></li>
<li><a href="https://common-error.techidaily.com/5-installation-issue-with-error-code-0x800f081f/"><u>5 Installation Issue with Error Code 0X800F081F</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-lava-blaze-pro-5g-drfone-by-drfone-virtual-android/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Lava Blaze Pro 5G | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-m-audio-drivers-compatible-with-windows-10-7-8-and-81/"><u>Download M-Audio Drivers Compatible with Windows 10, 7, 8 & 8.1</u></a></li>
<li><a href="https://driver-error.techidaily.com/easy-fix-for-devices-without-proper-drivers-in-windows-10-8-and-operating-systems/"><u>Easy Fix for Devices Without Proper Drivers in Windows 10, 8 & ^ Operating Systems</u></a></li>
<li><a href="https://hardware-help.techidaily.com/effortless-download-and-update-of-dells-built-in-speakers-drivers/"><u>Effortless Download and Update of Dell's Built-In Speakers Drivers</u></a></li>
<li><a href="https://driver-error.techidaily.com/enabling-recognition-of-usb-gadgets-on-windows-78/"><u>Enabling Recognition of USB Gadgets on Windows 7/8</u></a></li>
<li><a href="https://driver-error.techidaily.com/enhancing-performance-update-win11-deathadder-driver/"><u>Enhancing Performance: Update WIN11 DeathAdder Driver</u></a></li>
<li><a href="https://driver-error.techidaily.com/error-detection-ideport0-device-glitch/"><u>Error Detection: Ideport0 Device Glitch</u></a></li>
<li><a href="https://driver-error.techidaily.com/experience-portable-power-the-new-minisforum-ti-touchscreen-mini-pc-ultra-9-cpu-inside/"><u>Experience Portable Power: The New MinisForum Ti Touchscreen Mini PC - Ultra 9 CPU Inside</u></a></li>
<li><a href="https://driver-error.techidaily.com/expert-advice-how-to-rectify-the-screen-orientation-glitch-in-asus-laptop-video-playbacks/"><u>Expert Advice: How to Rectify the Screen Orientation Glitch in ASUS Laptop Video Playbacks</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-an-airtag-from-your-apple-id-account-from-iphone-11-by-drfone-ios/"><u>How to Remove an AirTag from Your Apple ID Account From iPhone 11?</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-swiftly-fix-the-itbm-driver-access-issue-step-by-step-guide/"><u>How to Swiftly Fix the ITBM Driver Access Issue - Step-by-Step Guide</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/how-to-track-apple-iphone-15-plus-location-by-number-drfone-by-drfone-virtual-ios/"><u>How to Track Apple iPhone 15 Plus Location by Number | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/hp-wireless-keyboard-woes-masterful-fixes-for-a-seamless-typing-experience/"><u>HP Wireless Keyboard Woes? Masterful Fixes for a Seamless Typing Experience</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-itel-p55plus-drfone-by-drfone-virtual-android/"><u>In 2024, 15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Itel P55+ | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-methods-to-mirror-oppo-a78-to-roku-drfone-by-drfone-android/"><u>In 2024, 3 Methods to Mirror Oppo A78 to Roku | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-6-rising-stars-non-periscope-video-sharing-on-mobile-devices/"><u>In 2024, 6 Rising Stars  Non-Periscope Video Sharing on Mobile Devices</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-fake-snapchat-location-without-jailbreak-on-oppo-find-n3-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fake Snapchat Location without Jailbreak On Oppo Find N3 | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-disabled-iphone-13ipad-without-computer-drfone-by-drfone-ios/"><u>In 2024, How to Unlock Disabled iPhone 13/iPad Without Computer | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/logitech-hub-no-show-fix-windows-1011-issue/"><u>Logitech Hub No Show? Fix Windows 10/11 Issue</u></a></li>
<li><a href="https://driver-error.techidaily.com/nvidia-driver-compatibility-fixed/"><u>Nvidia Driver Compatibility Fixed</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-nonfunctional-right-click-windows-11-touchpad-armageddon-reversed/"><u>Overcoming Nonfunctional Right Click - Windows 11 Touchpad Armageddon Reversed</u></a></li>
<li><a href="https://driver-error.techidaily.com/precision-link-between-asus-webcam-and-windows-10-os/"><u>Precision Link Between ASUS Webcam and Windows 10 OS</u></a></li>
<li><a href="https://unlock-android.techidaily.com/remove-the-lock-screen-fingerprint-of-your-vivo-v30-lite-5g-by-drfone-android/"><u>Remove the Lock Screen Fingerprint Of Your Vivo V30 Lite 5G</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-the-issue-invalid-installation-of-device-drivers-on-your-pc/"><u>Resolving the Issue: Invalid Installation of Device Drivers on Your PC</u></a></li>
<li><a href="https://driver-error.techidaily.com/secured-network-interface-continuity-fix/"><u>Secured Network Interface Continuity Fix</u></a></li>
<li><a href="https://driver-error.techidaily.com/smart-1080p-touch-screen-msi-desktop-with-advanced-artificnial-intelligence-features/"><u>Smart 1080P Touch Screen MSI Desktop with Advanced Artificnial Intelligence Features</u></a></li>
<li><a href="https://driver-error.techidaily.com/system-capacity-underutilized-yet-unavailable/"><u>System Capacity Underutilized, Yet Unavailable</u></a></li>
<li><a href="https://driver-error.techidaily.com/the-ultimate-guide-to-addressing-radeon-wattman-system-failures-preventing-unwanted-resets-and-restorations/"><u>The Ultimate Guide to Addressing Radeon WattMan System Failures: Preventing Unwanted Resets & Restorations</u></a></li>
<li><a href="https://driver-error.techidaily.com/top-tips-for-correcting-vertically-rotated-images-and-videos-on-your-asus-device/"><u>Top Tips for Correcting Vertically Rotated Images and Videos on Your ASUS Device</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-non-compatible-hardware-alerts-for-idt-systems/"><u>Troubleshooting Non-Compatible Hardware Alerts for IDT Systems</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-tips-for-killer-wifi-bluetooth-connectivity-problems-with-windows-11/"><u>Troubleshooting Tips for Killer WiFi Bluetooth Connectivity Problems with Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/ultimate-tutorial-on-activating-safe-mode-and-deleting-nvidiaamd-graphics-drivers-from-windows-8/"><u>Ultimate Tutorial on Activating Safe Mode and Deleting Nvidia/AMD Graphics Drivers From Windows 8</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/understanding-streaming-devices-what-are-they-and-how-do-they-work/"><u>Understanding Streaming Devices: What Are They and How Do They Work?</u></a></li>
<li><a href="https://driver-error.techidaily.com/unleash-the-full-potential-of-your-pc-with-updated-deathadder-bios/"><u>Unleash the Full Potential of Your PC with Updated Deathadder BIOS</u></a></li>
<li><a href="https://driver-error.techidaily.com/wdcsam64prewin8sys-core-isolation-not-active/"><u>wdcsam64_prewin8.sys: Core Isolation Not Active</u></a></li>
<li><a href="https://driver-error.techidaily.com/winnt-re-establish-usb-link-after-failure/"><u>WinNT: Re-Establish USB Link After Failure</u></a></li>
</ul></div>
