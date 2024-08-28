---
title: Troubleshooting Unsuccessful USB Setups Caused by Permission Restrictions
date: 2024-08-27T07:00:47.393Z
updated: 2024-08-28T07:00:47.393Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Troubleshooting Unsuccessful USB Setups Caused by Permission Restrictions
excerpt: This Article Describes Troubleshooting Unsuccessful USB Setups Caused by Permission Restrictions
thumbnail: https://thmb.techidaily.com/235c9a836def3af64d14d9406f5da36fac525d1a6b5286ab03fa2d909747fb1b.jpg
---

## Troubleshooting Unsuccessful USB Setups Caused by Permission Restrictions

If you can’t install any new USB devices due to error “Access is denied”, it can be frustrating. But don’t worry, here you will find the solution to fix the problem.  
  
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57c6862c6dbe8.png) .

First, make sure that you login to computer as Administrator. If you are not logged in with Administrator, follow steps below to switch it to Administrator.  
  
1\. Go to**Control Panel**and View by**Category**. Click**User Accounts**.(In your case, this may be “User Accounts and Family Safety”.)  
  
![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57c68c5d7bf6a.jpg)
  
2\. Click **Change your account type** and enter your password if necessary.
  
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_5791ba4e50787.png)
  
 3\. Then click**Start** button and choose to **Log off**  of Windows, and then log back in again.
  
![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_5791bab2104ee.png)

After that, reinstall the driver again.  
  
 **Turn off any antivirus or anti-spyware program**
  
If you are using an Administrator account and the problem persists, turn off any antivirus and anti-spyware program temporarily. This will work if the update is blocked by these program.
  
**Give permission to USBSTOR registry key**
  
If the problem could not be resolved, the USBSTOR registry key most probably has denied access to SYSTEM account. Follow these steps and give permission to USBSTOR registry key.
  
1\. Press**Win+R**(Windows key and R key) at the same time. A Run dialog will open.  
2\. Type**regedit**in the run box and click**OK**button.
  
<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57c6905ba04f8.png)
  
 3\. Go to **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Services\\USBSTOR.** Right-click on it and select**Permissions…** from the context menu.

<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57c692c5d030c.jpg)
  
 4\. Select**SYSTEM** from the Group or user names. In Permissions for SYSTEM section, make sure the Full Control Allow checkbox is checked and uncheck any Deny checkbox. Click Apply button to apply the changes.  
  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://driver-error.techidaily.com/fixed-sm-controller-drives-in-windows-11/"><u>[FIXED] SM Controller Drives in Windows 11</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-favorite-frameworks-top-instagram-filters/"><u>[New] In 2024, Favorite Frameworks  Top Instagram Filters</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-meme-magic-unleashed-top-humorous-creations-for-the-metaverse-world/"><u>[New] Meme Magic Unleashed  Top Humorous Creations for the Metaverse World</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-clockwise-conversions-transform-your-instagram-posts-through-rotation/"><u>[Updated] In 2024, Clockwise Conversions  Transform Your Instagram Posts Through Rotation</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-creating-impactful-youtube-thumbnails-and-ads/"><u>[Updated] In 2024, Creating Impactful YouTube Thumbnails & Ads</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/affordability-meets-performance-discover-why-googles-pixel-4a-5g-is-a-top-contender-in-the-budget-5g-phone-market/"><u>Affordability Meets Performance: Discover Why Google's Pixel 4a 5G Is a Top Contender in the Budget 5G Phone Market</u></a></li>
<li><a href="https://driver-error.techidaily.com/comprehensive-hardware-reviews-toms-digital-diary/"><u>Comprehensive Hardware Reviews - Tom's Digital Diary</u></a></li>
<li><a href="https://driver-error.techidaily.com/diagnose-and-repair-expert-advice-for-handling-failed-to-install-the-hcmon-driver-error/"><u>Diagnose & Repair: Expert Advice for Handling 'Failed to Install the HCmon Driver' Error</u></a></li>
<li><a href="https://driver-error.techidaily.com/ease-your-way-through-windows-ndis-issues/"><u>Ease Your Way Through Windows NDIS Issues</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixed-issue-intelamd-drivers-not-supported-by-premiere-pro/"><u>Fixed Issue: Intel/AMD Drivers Not Supported by Premiere Pro</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-missing-seagate-hard-drive-on-win11-pc/"><u>Fixing Missing Seagate Hard Drive on Win11 PC</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-non-functional-bluetooth-drivers-a-step-by-step-for-qualcomm-atheros-on-windows-10/"><u>Fixing Non-Functional Bluetooth Drivers: A Step-by-Step for Qualcomm Atheros on Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-qualcomm-atheros-bluetooth-issues-in-windows-11-an-easy-solution/"><u>Fixing Qualcomm Atheros Bluetooth Issues in Windows 11: An Easy Solution</u></a></li>
<li><a href="https://driver-error.techidaily.com/gadget-disallows-auto-charging/"><u>Gadget Disallows Auto Charging</u></a></li>
<li><a href="https://driver-error.techidaily.com/guide-to-restore-functionality-for-failed-usb-devices-unrecognized-by-windows-operating-system/"><u>Guide to Restore Functionality for Failed USB Devices Unrecognized by Windows Operating System</u></a></li>
<li><a href="https://driver-error.techidaily.com/hardware-initialization-success/"><u>Hardware Initialization Success</u></a></li>
<li><a href="https://some-techniques.techidaily.com/how-to-use-luts-in-photoshop-cc-for-2024/"><u>How to Use LUTs in PhotoShop CC for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-5-easy-ways-to-change-location-on-youtube-tv-on-xiaomi-redmi-12-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Easy Ways to Change Location on YouTube TV On Xiaomi Redmi 12 5G | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-change-lock-screen-wallpaper-on-samsung-galaxy-xcover-7-by-drfone-android/"><u>In 2024, How to Change Lock Screen Wallpaper on Samsung Galaxy XCover 7</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-chronicle-of-creation-weaving-time-lapse-animations-via-movie-maker/"><u>In 2024, The Chronicle of Creation  Weaving Time-Lapse Animations via Movie Maker</u></a></li>
<li><a href="https://driver-install.techidaily.com/installing-updated-hp-officejet-8620-drivers-on-windows/"><u>Installing Updated HP OfficeJet 8620 Drivers on Windows</u></a></li>
<li><a href="https://driver-error.techidaily.com/no-force-needed-to-set-up-graphics-correctly/"><u>No Force Needed to Set Up Graphics Correctly</u></a></li>
<li><a href="https://driver-error.techidaily.com/no-issues-newly-installed-nvidia-drivers-running-fine/"><u>No Issues - Newly Installed Nvidia Drivers Running Fine</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-device-manager-software-glitches/"><u>Overcoming Device Manager Software Glitches</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolve-access-denied-error-during-usb-installation/"><u>Resolve 'Access Denied' Error During USB Installation</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-your-graphic-card-issues-fixing-a-code-forty-three-with-windows-eleven-and-gtx-ninety-five/"><u>Resolving Your Graphic Card Issues: Fixing a 'Code Forty-Three' With Windows Eleven and GTX Ninety-Five</u></a></li>
<li><a href="https://driver-error.techidaily.com/secure-installation-new-nvidia-drivers-ready/"><u>Secure Installation: New Nvidia Drivers Ready</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-hp-bluetooth-driver-issue-in-windows-11/"><u>Solved HP Bluetooth Driver Issue in Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-how-to-get-and-set-up-necessary-drivers-on-your-windows-device-windows-1087/"><u>Solved! How to Get and Set Up Necessary Drivers on Your Windows Device (Windows 10/8/7)</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-the-driver-load-failure-how-to-fix-battlenet-service-initialization-issue/"><u>Solving the 'Driver Load Failure' - How to Fix Battlenet Service Initialization Issue</u></a></li>
<li><a href="https://driver-error.techidaily.com/steps-to-solve-me-driver-failures/"><u>Steps to Solve ME Driver Failures</u></a></li>
<li><a href="https://driver-error.techidaily.com/strategic-approaches-for-solving-nvidia-driver-failures/"><u>Strategic Approaches for Solving Nvidia Driver Failures</u></a></li>
<li><a href="https://driver-error.techidaily.com/toms-tech-evaluations-comprehensive-reviews-and-advice-on-electronics/"><u>Tom's Tech Evaluations: Comprehensive Reviews & Advice on Electronics</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-fixing-hardware-device-not-recognized-error-in-idt-packages/"><u>Troubleshooting: Fixing 'Hardware Device Not Recognized' Error in IDT Packages</u></a></li>
</ul></div>
