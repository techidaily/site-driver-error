---
title: "Troubleshooting: Permission Problems with USB Installation on Windows"
date: 2024-08-09T08:50:18.387Z
updated: 2024-08-10T08:50:18.387Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: "This Article Describes Troubleshooting: Permission Problems with USB Installation on Windows"
excerpt: "This Article Describes Troubleshooting: Permission Problems with USB Installation on Windows"
thumbnail: https://thmb.techidaily.com/98381f75da9e421b6eb855209185ef7a1fbf0a3e49f7737dbe8956238d8582c9.jpg
---

## Troubleshooting: Permission Problems with USB Installation on Windows

If you can’t install any new USB devices due to error “Access is denied”, it can be frustrating. But don’t worry, here you will find the solution to fix the problem.  
  
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57c6862c6dbe8.png) .

First, make sure that you login to computer as Administrator. If you are not logged in with Administrator, follow steps below to switch it to Administrator.  
  
1\. Go to**Control Panel**and View by**Category**. Click**User Accounts**.(In your case, this may be “User Accounts and Family Safety”.)  
  
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57c68c5d7bf6a.jpg)
  
2\. Click **Change your account type** and enter your password if necessary.
  
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_5791ba4e50787.png)
  
 3\. Then click**Start** button and choose to **Log off**  of Windows, and then log back in again.
  
<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_5791bab2104ee.png)

After that, reinstall the driver again.  
  
 **Turn off any antivirus or anti-spyware program**
  
If you are using an Administrator account and the problem persists, turn off any antivirus and anti-spyware program temporarily. This will work if the update is blocked by these program.
  
**Give permission to USBSTOR registry key**
  
If the problem could not be resolved, the USBSTOR registry key most probably has denied access to SYSTEM account. Follow these steps and give permission to USBSTOR registry key.
  
1\. Press**Win+R**(Windows key and R key) at the same time. A Run dialog will open.  
2\. Type**regedit**in the run box and click**OK**button.
  
![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57c6905ba04f8.png)
  
 3\. Go to **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Services\\USBSTOR.** Right-click on it and select**Permissions…** from the context menu.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57c692c5d030c.jpg)
  
 4\. Select**SYSTEM** from the Group or user names. In Permissions for SYSTEM section, make sure the Full Control Allow checkbox is checked and uncheck any Deny checkbox. Click Apply button to apply the changes.  
  
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57c6933c3f709.png)

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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-hacks-for-preventing-youtube-short-failures/"><u>[New] 2024 Approved  Hacks for Preventing YouTube Short Failures</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-lilliputscreenmugger-review-analysis/"><u>[New] 2024 Approved  LilliputScreenMugger Review Analysis</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-incorporate-no-cost-tunes-to-boost-your-vlogs/"><u>[Updated] Incorporate No-Cost Tunes to Boost Your Vlogs</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-exploring-9-zero-price-editors-for-youtube-content/"><u>2024 Approved  Exploring 9 Zero Price Editors for YouTube Content</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-flipping-photo-hues-a-step-by-step-guide/"><u>2024 Approved  Flipping Photo Hues  A Step-by-Step Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/apple-arcades-edge-in-portable-entertainment-play/"><u>Apple Arcade's Edge in Portable Entertainment Play</u></a></li>
<li><a href="https://fox-links.techidaily.com/asus-chromebook-flip-c302ca-outstanding-budget-laptop-with-remarkable-versatility-reviewed/"><u>Asus Chromebook Flip C302CA: Outstanding Budget Laptop with Remarkable Versatility Reviewed</u></a></li>
<li><a href="https://program-issues.techidaily.com/battlefield-5-stability-guide-resolving-pc-performance-and-crash-problems/"><u>Battlefield #5 Stability Guide - Resolving PC Performance and Crash Problems</u></a></li>
<li><a href="https://driver-error.techidaily.com/cddvd-non-detect-in-win11-repair-complete/"><u>CD/DVD Non-Detect in Win11 - Repair Complete</u></a></li>
<li><a href="https://driver-error.techidaily.com/complete-guide-updating-and-downloading-drivers-for-your-hp-envy-20/"><u>Complete Guide: Updating and Downloading Drivers for Your HP Envy 20</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-honor-x50iplus-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use GPS Joystick to Fake GPS Location On Honor X50i+ | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/corrected-unsupported-intelamd-drivers-within-adobe-premiere-pro/"><u>Corrected Unsupported Intel/AMD Drivers Within Adobe Premiere Pro</u></a></li>
<li><a href="https://tech-haven.techidaily.com/elevate-your-linkedin-game-with-chatgpt-a-comprehensive-guide-to-landing-jobs-faster/"><u>Elevate Your LinkedIn Game with ChatGPT: A Comprehensive Guide to Landing Jobs Faster</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/enhanced-communication-through-3-neurological-activities/"><u>Enhanced Communication Through 3 Neurological Activities</u></a></li>
<li><a href="https://driver-error.techidaily.com/enhanced-windows-11-sm-bus-drives-no-more-issues/"><u>Enhanced Windows 11 SM Bus Drives, No More Issues</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-speed-negotiation-failure/"><u>Fix Speed Negotiation Failure</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixed-windows-wont-boot-after-updating-drivers/"><u>Fixed: Windows Won’t Boot After Updating Drivers</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-iphone-portable-storage-issues-overcoming-the-mtp-driver-challenge-on-windows-pcs/"><u>Fixing iPhone Portable Storage Issues - Overcoming the MTP Driver Challenge on Windows PCs</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-oneplus-nord-n30-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on OnePlus Nord N30 5G | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/hardware-error-bcm2omedian-device-unsupported/"><u>Hardware Error - BCM2omedian Device Unsupported</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-overcome-access-denied-when-setting-up-a-new-usb-device/"><u>How to Overcome 'Access Denied' When Setting Up a New USB Device</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-gmail-password-on-motorola-moto-g23-devices-by-drfone-android/"><u>How to Reset Gmail Password on Motorola Moto G23 Devices</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-4-most-known-ways-to-find-someone-on-tinder-for-itel-p55-5g-by-name-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Most-Known Ways to Find Someone on Tinder For Itel P55 5G by Name | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-master-iphone-timelapses-efficient-recording-tips/"><u>In 2024, Master iPhone Timelapses  Efficient Recording Tips</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-unlimited-access-to-creative-mcb-resources/"><u>In 2024, Unlimited Access to Creative MCB Resources</u></a></li>
<li><a href="https://driver-error.techidaily.com/meltdown-fixing-intellme-malfunctions/"><u>Meltdown: Fixing IntellME Malfunctions</u></a></li>
<li><a href="https://driver-error.techidaily.com/no-vehicle-load-for-this-equipment/"><u>No Vehicle Load for This Equipment</u></a></li>
<li><a href="https://driver-error.techidaily.com/razer-deadriver-on-windows-10-seamless-installation-guide/"><u>Razer DeaDriver on Windows 10: Seamless Installation Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/rectify-host-controller-defect/"><u>Rectify Host Controller Defect</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/resolve-google-chrome-video-troubles-fb/"><u>Resolve Google Chrome Video Troubles (FB)</u></a></li>
<li><a href="https://driver-error.techidaily.com/revise-and-validate-inf-service-installation/"><u>Revise and Validate INF Service Installation</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-the-top-to-bottom-problem-correcting-your-asus-laptops-inverted-videos/"><u>Solving the Top-to-Bottom Problem: Correcting Your ASUS Laptop's Inverted Videos</u></a></li>
<li><a href="https://driver-error.techidaily.com/to-do-so-by-cn-and-i-need-to-check2-is-not-foundations-of-an-image/"><u>To Do so by C:\n; and I Need to Check_2 Is Not Foundations of an Image</u></a></li>
<li><a href="https://some-skills.techidaily.com/transformative-notetaking-the-mematic-way-for-2024/"><u>Transformative Notetaking  The Mematic Way for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshoot-usb-errors-post-adb-interruption/"><u>Troubleshoot USB Errors Post ADB Interruption</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-tips-accessing-safe-mode-and-cleaning-up-gpu-drivers-on-your-windows-8-device/"><u>Troubleshooting Tips: Accessing Safe Mode & Cleaning Up GPU Drivers on Your Windows 8 Device</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/updated-in-2024-how-to-make-a-funny-meme-on-macbook/"><u>Updated In 2024, How to Make a Funny Meme on MacBook</u></a></li>
<li><a href="https://facebook.techidaily.com/why-leaving-no-footprint-on-facebook-is-smart/"><u>Why Leaving No Footprint on Facebook Is Smart</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721102073099-windows-users-learn-how-to-fix-a-malfunctioning-wireless-keyboard-today/"><u>Windows Users! Learn How to Fix a Malfunctioning Wireless Keyboard Today!</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721100650720-windows-wireless-keyboard-issues-solve-common-connection-problems-now/"><u>Windows Wireless Keyboard Issues? Solve Common Connection Problems Now</u></a></li>
</ul></div>
