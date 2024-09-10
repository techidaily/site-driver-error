---
title: "Troubleshooting: How to Resolve 'Access Denied' Error During USB Device Installation"
date: 2024-09-09T03:09:58.627Z
updated: 2024-09-10T03:09:58.627Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: "This Article Describes Troubleshooting: How to Resolve 'Access Denied' Error During USB Device Installation"
excerpt: "This Article Describes Troubleshooting: How to Resolve 'Access Denied' Error During USB Device Installation"
thumbnail: https://thmb.techidaily.com/7dd47039b908f15adfac56204ff22ad7becb8a002a35f04201c966ce7066b460.jpg
---

## Troubleshooting: How to Resolve 'Access Denied' Error During USB Device Installation

If you can’t install any new USB devices due to error “Access is denied”, it can be frustrating. But don’t worry, here you will find the solution to fix the problem.  
  
![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57c6862c6dbe8.png) .

<!-- affiliate ads begin -->
<a href="https://bluettiit.sjv.io/c/5597632/2114267/17093" target="_top" id="2114267">
  <img src="//a.impactradius-go.com/display-ad/17093-2114267" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2114267/17093" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
First, make sure that you login to computer as Administrator. If you are not logged in with Administrator, follow steps below to switch it to Administrator.  
  
1\. Go to**Control Panel**and View by**Category**. Click**User Accounts**.(In your case, this may be “User Accounts and Family Safety”.)  
  
![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57c68c5d7bf6a.jpg)
  
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136624/26400" target="_top" id="2136624">
  <img src="//a.impactradius-go.com/display-ad/26400-2136624" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136624/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2\. Click **Change your account type** and enter your password if necessary.
  
![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_5791ba4e50787.png)
  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135419/19272" target="_top" id="2135419">
  <img src="//a.impactradius-go.com/display-ad/19272-2135419" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135419/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3\. Then click**Start** button and choose to **Log off**  of Windows, and then log back in again.
  
![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_5791bab2104ee.png)

After that, reinstall the driver again.  
  
 **Turn off any antivirus or anti-spyware program**
  
If you are using an Administrator account and the problem persists, turn off any antivirus and anti-spyware program temporarily. This will work if the update is blocked by these program.
  
**Give permission to USBSTOR registry key**
  
If the problem could not be resolved, the USBSTOR registry key most probably has denied access to SYSTEM account. Follow these steps and give permission to USBSTOR registry key.
  
1\. Press**Win+R**(Windows key and R key) at the same time. A Run dialog will open.  
2\. Type**regedit**in the run box and click**OK**button.
  
![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57c6905ba04f8.png)
  
<!-- affiliate ads begin -->
<span id="1982456">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982456.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982456">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982456.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982456%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982456/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3\. Go to **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Services\\USBSTOR.** Right-click on it and select**Permissions…** from the context menu.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57c692c5d030c.jpg)
  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135367/19272" target="_top" id="2135367">
  <img src="//a.impactradius-go.com/display-ad/19272-2135367" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135367/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 4\. Select**SYSTEM** from the Group or user names. In Permissions for SYSTEM section, make sure the Full Control Allow checkbox is checked and uncheck any Deny checkbox. Click Apply button to apply the changes.  
  
![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57c6933c3f709.png)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123471/16836" target="_top" id="2123471">
  <img src="//a.impactradius-go.com/display-ad/16836-2123471" border="0" alt="https://techidaily.com" width="234" height="60"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123471/16836" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://driver-error.techidaily.com/fixed-wdcsam64prewin8sys-turned-off-core-isolation/"><u>[Fixed] wdcsam64_prewin8.sys Turned Off Core Isolation</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-how-to-remove-background-noise-from-skype-video-calls/"><u>[New] 2024 Approved  How to Remove Background Noise From Skype Video Calls</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-the-ultimate-list-best-mac-compatible-recorders/"><u>[New] 2024 Approved  The Ultimate List  Best Mac-Compatible Recorders</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-brief-stardom-flash-review/"><u>[New] Brief Stardom Flash Review</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-how-zooming-up-with-fb-live-transforms-broadcasts/"><u>[New] How Zooming Up with FB Live Transforms Broadcasts</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-simplified-guide-to-switching-clownfish-voices-on-win/"><u>[New] Simplified Guide to Switching Clownfish Voices on Win</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-the-insiders-approach-to-maximizing-youtube-video-revenue/"><u>[New] The Insider's Approach to Maximizing YouTube Video Revenue</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-intels-ax201-unable-to-connect-wifi-6/"><u>[RESOLVED] Intel's Ax201 Unable to Connect Wifi 6</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-microsoft-teredo-tunneling-adapter-missing/"><u>[Solved] Microsoft Teredo Tunneling Adapter Missing</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-from-raw-footage-to-final-cut-chroma-mastery-for-2024/"><u>[Updated] From Raw Footage to Final Cut  Chroma Mastery for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-from-srt-to-sub-transforming-playback-sequences/"><u>[Updated] From SRT to SUB  Transforming Playback Sequences</u></a></li>
<li><a href="https://driver-error.techidaily.com/diagnosing-the-driver-loading-mishap-in-battleye-services-mastering-error-code-1450/"><u>Diagnosing the Driver Loading Mishap in BattlEye Services - Mastering Error Code 1450</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/cting-your-profit-share-in-youtube-short-creation-for-2024/"><u>Dissecting Your Profit Share in YouTube Short Creation for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/driver-load-not-achieved-for-device-id-219/"><u>Driver Load Not Achieved for Device (ID: 219)</u></a></li>
<li><a href="https://driver-error.techidaily.com/driverless-devices-fix-with-these-steps-for-win10win8win7/"><u>Driverless Devices? Fix with These Steps for Win10/Win8/Win7</u></a></li>
<li><a href="https://driver-error.techidaily.com/error-fixed-gpu-driver-successful-installer/"><u>Error Fixed: GPU Driver Successful Installer</u></a></li>
<li><a href="https://driver-error.techidaily.com/gtx-950-error-code-43-explained-easy-fixes-for-a-smooth-windows-11-experience/"><u>GTX 950 Error Code 43 Explained - Easy Fixes for a Smooth Windows 11 Experience</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-come-up-with-the-best-pokemon-team-on-zte-blade-a73-5g-drfone-by-drfone-virtual-android/"><u>How to Come up With the Best Pokemon Team On ZTE Blade A73 5G? | Dr.fone</u></a></li>
<li><a href="https://ai-topics.techidaily.com/how-to-generate-speech-from-text-the-best-text-to-speech-converters/"><u>How To Generate Speech From Text | The Best Text-to-Speech Converters</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-overcome-access-is-denied-when-setting-up-your-usb-device/"><u>How to Overcome 'Access Is Denied' When Setting Up Your USB Device</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-successfully-overcome-a-failed-hcmond-driver-setup/"><u>How to Successfully Overcome a Failed Hcmond Driver Setup</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-unlock-apple-id-from-your-iphone-8-without-security-questions-by-drfone-ios/"><u>How to Unlock Apple ID From your iPhone 8 without Security Questions?</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-work-with-outdated-usb-composite-devices-a-step-by-step-guide/"><u>How to Work with Outdated USB Composite Devices - A Step-by-Step Guide</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-easy-fixes-how-to-recover-forgotten-icloud-password-from-your-iphone-12-by-drfone-ios/"><u>In 2024, Easy Fixes How To Recover Forgotten iCloud Password From your iPhone 12</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-hide-your-identity-share-your-life-instagram-live-secrets/"><u>In 2024, Hide Your Identity, Share Your Life - Instagram Live Secrets</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-do-you-get-sun-stone-evolutions-in-pokemon-for-apple-iphone-8-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, How Do You Get Sun Stone Evolutions in Pokémon For Apple iPhone 8 Plus? | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/key-steps-for-resolving-device-failures-in-dm/"><u>Key Steps for Resolving Device Failures in DM</u></a></li>
<li><a href="https://win-dash.techidaily.com/latest-update-available-easy-installation-of-brother-hl-l2350d-printer-driver/"><u>Latest Update Available: Easy Installation of Brother HL-L2350D Printer Driver</u></a></li>
<li><a href="https://screen-recording.techidaily.com/mastering-stardew-on-ginger-islet-for-2024/"><u>Mastering Stardew on Ginger Islet for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/network-adapter-driver-missing-in-windows-10-solved/"><u>Network Adapter Driver Missing in Windows 10 [Solved]</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/overview-of-the-best-realme-narzo-60-5g-screen-mirroring-app-drfone-by-drfone-android/"><u>Overview of the Best Realme Narzo 60 5G Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolve-erratic-dell-touch-screen-driver/"><u>Resolve Erratic Dell Touch Screen Driver</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-how-to-fix-the-absence-of-a-coprocessor-driver-in-windows-10/"><u>Resolved: How to Fix the Absence of a Coprocessor Driver in Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-the-default-radeon-wattman-issues-a-comprehensive-fix-guide/"><u>Resolving the Default Radeon Wattman Issues: A Comprehensive Fix Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/seagate-hard-drive-not-detected-w10-troubleshooting/"><u>Seagate Hard Drive Not Detected - W10 Troubleshooting</u></a></li>
<li><a href="https://driver-error.techidaily.com/smooth-touchscreen-experience-in-new-windows-11-with-elan/"><u>Smooth Touchscreen Experience in New Windows 11 with Elan</u></a></li>
<li><a href="https://driver-error.techidaily.com/swift-fix-amd-drivers-keep-hitting-issues/"><u>Swift Fix: AMD Drivers Keep Hitting Issues</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-ultimate-guide-to-computer-hardware-according-to-toms-review/"><u>The Ultimate Guide to Computer Hardware According to Tom's Review</u></a></li>
<li><a href="https://driver-error.techidaily.com/triumph-over-graphics-error-during-install/"><u>Triumph over Graphics Error During Install</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-hp-wireless-keyboard-connectivity-issues-fixes-and-solutions/"><u>Troubleshooting HP Wireless Keyboard Connectivity Issues - Fixes and Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-windows-11-overcoming-user-profile-service-sign-in-errors/"><u>Troubleshooting Windows 11: Overcoming 'User Profile Service' Sign-In Errors</u></a></li>
<li><a href="https://extra-hints.techidaily.com/unlocking-64128gbs-full-potential-for-video-storing/"><u>Unlocking 64/128GB's Full Potential for Video Storing</u></a></li>
<li><a href="https://driver-error.techidaily.com/unplugging-problems-lenovo-bluetooth-in-windows-10/"><u>Unplugging Problems: Lenovo Bluetooth in Windows 10</u></a></li>
</ul></div>
