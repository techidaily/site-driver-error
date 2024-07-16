---
title: Troubleshooting USB Installation Failures Caused by Access Denied Messages
date: 2024-07-15T06:58:26.897Z
updated: 2024-07-16T06:58:26.897Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Troubleshooting USB Installation Failures Caused by Access Denied Messages
excerpt: This Article Describes Troubleshooting USB Installation Failures Caused by Access Denied Messages
thumbnail: https://thmb.techidaily.com/db7b5b29f3dd85ab1439e42aeefbd0af6cf9e882cf1c9c7fcb2a6858953bbb8e.jpg
---

## Troubleshooting USB Installation Failures Caused by Access Denied Messages

If you can’t install any new USB devices due to error “Access is denied”, it can be frustrating. But don’t worry, here you will find the solution to fix the problem.  
  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57c6862c6dbe8.png) .

First, make sure that you login to computer as Administrator. If you are not logged in with Administrator, follow steps below to switch it to Administrator.  
  
1\. Go to**Control Panel**and View by**Category**. Click**User Accounts**.(In your case, this may be “User Accounts and Family Safety”.)  
  
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57c68c5d7bf6a.jpg)
  
2\. Click **Change your account type** and enter your password if necessary.
  
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
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57c692c5d030c.jpg)
  
 4\. Select**SYSTEM** from the Group or user names. In Permissions for SYSTEM section, make sure the Full Control Allow checkbox is checked and uncheck any Deny checkbox. Click Apply button to apply the changes.  
  
<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://driver-error.techidaily.com/windows-11-addressing-bus-controllers/"><u>Windows 11: Addressing Bus Controllers</u></a></li>
<li><a href="https://driver-error.techidaily.com/driving-machine-rejected-by-tech-device/"><u>Driving Machine Rejected by Tech Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ultimate-guide-to-modify-mouses-double-click-speed/"><u>Ultimate Guide to Modify Mouse's Double-Click Speed</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-insiders-guide-to-recording-and-livestreaming-sports-events/"><u>2024 Approved  Insider's Guide to Recording and Livestreaming Sports Events</u></a></li>
<li><a href="https://driver-error.techidaily.com/rectifying-issues-with-wm11-sm-bus-drivers/"><u>Rectifying Issues with WM11 SM Bus Drivers</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721105317336-fixing-the-unexpected-reset-of-your-radeon-wattman-stable-performance-now-achievable/"><u>Fixing the Unexpected Reset of Your Radeon Wattman - Stable Performance Now Achievable</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-the-bsod-error-code-0x0000007e-in-windows-7-a-step-by-step-guide/"><u>Fixing the BSOD Error Code 0X0000007E in Windows 7: A Step-by-Step Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/decoding-the-past-a-comprehensive-guide-to-older-usb-composite-devices/"><u>Decoding the Past: A Comprehensive Guide to Older USB Composite Devices</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721102147633-qualcomm-atheros-bluetooth-connectivity-woes-with-windows-11-heres-your-comprehensive-fix/"><u>Qualcomm Atheros Bluetooth Connectivity Woes with Windows 11? Here's Your Comprehensive Fix!</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-post-youtube-video-on-the-best-days-to-get-more-view/"><u>In 2024, Post Youtube Video on the Best Days to Get More View</u></a></li>
<li><a href="https://driver-error.techidaily.com/expert-advice-resolving-unable-to-install-hcmondrv-errors-successfully/"><u>Expert Advice: Resolving 'Unable to Install Hcmondrv' Errors Successfully</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721104681699-blackberry-storm-beta-not-recognized-by-fedora-33-solution-found/"><u>Blackberry Storm Beta Not Recognized by Fedora 33 - Solution Found</u></a></li>
<li><a href="https://driver-error.techidaily.com/technology-blocks-vehicle-charge/"><u>Technology Blocks Vehicle Charge</u></a></li>
<li><a href="https://driver-error.techidaily.com/default-amd-wattman-settings-collapse-and-recovery-complete-solution-guide/"><u>Default AMD Wattman Settings Collapse & Recovery: Complete Solution Guide</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-level-up-your-auditory-game-in-valorant-with-this-must-try-free-tool/"><u>[New] Level Up Your Auditory Game in Valorant with This Must-Try, Free Tool</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-the-complete-handbook-to-extracting-audio-from-youtube-videos-for-2024/"><u>Updated The Complete Handbook to Extracting Audio From YouTube Videos for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/addressing-unresponsive-right-click-issue-for-windows-11-touchpads/"><u>Addressing Unresponsive Right Click Issue for Windows 11 Touchpads</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-the-auto-uninstall-loop-in-nvidia-drivers/"><u>Fixing the Auto-Uninstall Loop in Nvidia Drivers</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-unraveling-the-mysteries-of-instagram-saved-stories-for-2024/"><u>[Updated] Unraveling the Mysteries of Instagram Saved Stories for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-repair-non-functional-qualcomm-atheros-bluetooth-driver-on-windows-11-step-by-step-guide/"><u>How to Repair Non-Functional Qualcomm Atheros Bluetooth Driver on Windows 11 - Step by Step Guide</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-detailed-review-of-doctorsim-unlock-service-for-apple-iphone-12-pro-max-drfone-by-drfone-ios/"><u>In 2024, Detailed Review of doctorSIM Unlock Service For Apple iPhone 12 Pro Max | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/device-manager-error-48-resolved/"><u>Device Manager Error #48 Resolved</u></a></li>
<li><a href="https://driver-error.techidaily.com/unrecognized-cddvd-in-win11-settled/"><u>Unrecognized CD/DVD in Win11 - Settled</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-many-attempts-to-unlock-apple-iphone-13-pro-drfone-by-drfone-ios/"><u>In 2024, How Many Attempts To Unlock Apple iPhone 13 Pro | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshoot-and-solve-not-available-itbm-driver-error-instantly/"><u>Troubleshoot and Solve 'Not Available' ITBM Driver Error Instantly!</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-the-ultimate-selection-of-windows-10-audio-mixing-tools-for-2024/"><u>Updated The Ultimate Selection of Windows 10 Audio Mixing Tools for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-application-has-been-blocked-from-accessing-graphics-hardware-windows-10/"><u>[SOLVED] Application Has Been Blocked From Accessing Graphics Hardware Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/intel-processor-driver-disappeared-on-windows-11-heres-how-you-can-quickly-restore-it/"><u>Intel Processor Driver Disappeared on Windows 11? Here's How You Can Quickly Restore It!</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/best-free-wmv-video-combining-software-for-this-year/"><u>Best Free WMV Video Combining Software for This Year</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-comparative-content-crusade-analyzing-your-videos-against-others/"><u>[Updated] In 2024, Comparative Content Crusade  Analyzing Your Videos Against Others'</u></a></li>
</ul></div>
