---
title: "Guide: Addressing and Repairing the Failed Hcmon Driver Install Problem"
date: 2024-10-26T20:14:02.667Z
updated: 2024-10-30T01:10:52.143Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: "This Article Describes Guide: Addressing and Repairing the Failed Hcmon Driver Install Problem"
excerpt: "This Article Describes Guide: Addressing and Repairing the Failed Hcmon Driver Install Problem"
thumbnail: https://thmb.techidaily.com/5d0cffeef3a457f6d646442a32f08e24ee51602aa778ea2d41cdc52aa7fdbdaa.jpg
---

## Guide: Addressing and Repairing the Failed Hcmon Driver Install Problem

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59c9ee600eb02.jpg)

 If you get error “Failed to install the hcmon driver” during installing the VMware products (vSphere, Remote Console, etc.),  don’t worry. You can fix the problem with one of the solutions in this article.

## What is the HCMON driver?

 HCMON driver is a virtual USB driver. It allows your physical USB ports to connect to the virtual machines.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082530/7443" target="_top" id="2082530">
  <img src="//a.impactradius-go.com/display-ad/7443-2082530" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082530/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to fix this error?

 The error occurs can be due to different issues. We post the top 5 solutions in this article. You can fix this error with one of these solutions. You may not have to try them all. Just work your way down until you find the one that works for you.

 Solution 1:**[Install the product as an administrator](https://pish-posh-baby.sjv.io/g1jg15)**
 Solution 2:**[Update the drivers](https://ship7com.pxf.io/0zwaz3)**
 Solution 3:**[Remove the hcmon.sys driver](https://ancheer.sjv.io/y96bgp)**
 Solution 4:**[Install the product using PowerShell](https://printrendy.pxf.io/xyboy5)**
 Solution 5: **[Install .NET Framework 3.5.1](https://ursime.pxf.io/r5bm57)**

## Solution 1: Install the product as an administrator

 When you install the product, you’re required to install the hcmon driver. Windows may see this as a user adding hardware to the PC. But this user doesn’t have the permission to do that. In this case, this error may occur. Try to install the product as an administrator:

1) Right-click on the downloaded setup file.

2) Click**Run as administrator** . If you don’t see the option “Run as administrator”, this solution doesn’t apply to you. Skip then move on to other solutions.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ca09694f9d6.png)

##

## Solution 2: Update the drivers

 Corrupted drivers especially graphics drivers can cause this error. To fix the problem, try to update the drivers.

 If you don’t have the time, patience or computer skills to update the drivers manually,  you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version it takes just 2 clicks (and you get full support and a 30-day money back guarantee):

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click **Scan Now** . Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ca0a63e05e5.jpg)

 3) Click the **Update** button next to the flagged drivers to automatically download and install the correct version of their driver (you can do this with the FREE version). Or click **Update All**  to automatically download and install the correct version of _all_   the drivers that are missing or out of date on your system (this requires the Pro version – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ca0a7166942.jpg)

##

## Solution 3: Remove the hcmon.sys driver

 The HCMON driver might be installed. One possible solution is to remove the hcmon.sys driver. Follow these steps:

 1) Go to **[Device Manager](https://tools.techidaily.com/drivereasy/download/)**  .

 2) Click**View** \>**Show hidden devices** .

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ca0ccee9685.png)

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398449/3022" target="_top" id="398449">
  <img src="//a.impactradius-go.com/display-ad/3022-398449" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398449/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Double-click**Non-Plug and Play Drivers.**

 4) Right-click**hcmon** and click**Uninstall** .

 6) Delete the**C:\\Windows\\system32\\drivers\\hcmon.sys** file.

 7) Restart the computer.

##

## Solution 4: Install the product using PowerShell

Try to install the product in PowerShell. Follow steps below:

 1) Type “powershell” in the search field. Right-click**Windows PowerShell** (The name may be different depending on the Windows version you’re using.) and click**Run as administrator** .

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ca0f0ca0506.png)

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098701/14409" target="_top" id="2098701">
  <img src="//a.impactradius-go.com/display-ad/14409-2098701" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098701/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 2) Go to the location where you saved the setup file. This is to get the msi name.

 3) Type**.\\xxxx.msi** in PowerShell command prompt and press**Enter** on your keyboard. XXXX means the name of msi file. Replace it with your msi file name.

In my case, my file is “VMware-VMRC-10.0.1-5898794”:

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ca1311509ab.png)

<!-- affiliate ads begin -->
<span id="1516072">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1516072.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1516072">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1516072.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1516072%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1516072/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

So I typed “.\\VMware-VMRC-10.0.1-5898794.msi”:

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ca13ea65f0f.png)

##

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/798161/11305" target="_top" id="798161">
  <img src="//a.impactradius-go.com/display-ad/11305-798161" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i110150.net/i/5597632/798161/11305" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Solution 5:Install .NET Framework 3.5.1

 To install the product successfully, ensure your computer has installed .NET Framework 3.5.1\. If not, install it.

 Click [here](https://www.microsoft.com/en-us/download/details.aspx?id=22) to go to the download page of Microsoft to download .NET Framework 3.5.1\. Then install it on your computer.

* [Drivers](https://tools.techidaily.com/drivereasy/download/)
* [Windows](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://some-approaches.techidaily.com/new-the-finest-picks-top-8-web-sites-with-rich-3d-and-gold-lined-texts/"><u>[New] The Finest Picks Top 8 Web Sites with Rich 3D & Gold-Lined Texts</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-avoid-monetization-mishaps-essential-youtube-checks/"><u>[Updated] Avoid Monetization Mishaps Essential YouTube Checks</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-unveiling-the-secrets-to-choosing-movie-trailers-music/"><u>2024 Approved Unveiling the Secrets to Choosing Movie Trailers' Music</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/8-best-apps-for-screen-mirroring-realme-v30-pc-drfone-by-drfone-android/"><u>8 Best Apps for Screen Mirroring Realme V30 PC | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/a-perfect-guide-to-remove-or-disable-google-smart-lock-on-oneplus-ace-3-by-drfone-android/"><u>A Perfect Guide To Remove or Disable Google Smart Lock On OnePlus Ace 3</u></a></li>
<li><a href="https://driver-error.techidaily.com/driver-error-reported-bcm20702a0/"><u>Driver Error Reported - BCM20702A0</u></a></li>
<li><a href="https://driver-error.techidaily.com/guide-to-immediate-fix-for-itbm-driver-not-available-error-messages-on-your-device/"><u>Guide to Immediate Fix for 'ITBM Driver Not Available' Error Messages on Your Device</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-do-i-canin-and-more-than/"><u>How Do I Can'in (and More Than</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-fix-base-system-device-driver-issue-in-device-manager/"><u>How to Fix Base System Device Driver Issue in Device Manager</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-fix-nvidia-geforce-gtx-950-code-43-problems-on-your-windows-10-pc/"><u>How to Fix NVIDIA GeForce GTX 950 'Code 43' Problems on Your Windows 10 PC</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-overview-of-the-best-vivo-y36-screen-mirroring-app-drfone-by-drfone-android/"><u>In 2024, Overview of the Best Vivo Y36 Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/revising-illegal-configuration-segment-in-inf/"><u>Revising Illegal Configuration Segment in INF</u></a></li>
<li><a href="https://driver-error.techidaily.com/swift-and-simple-how-to-update-windows-10s-deadriver-seamlessly/"><u>Swift and Simple: How to Update Windows 10'S DeaDriver Seamlessly</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721100561642-tackling-vintage-usb-composite-unit-issues-solutions-for-a-smarter-connection/"><u>Tackling Vintage USB Composite Unit Issues - Solutions for a Smarter Connection!</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-nokia-g22-by-drfone-android/"><u>The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On Nokia G22</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/unleashing-productivity-ai-integration-into-docs-and-spreadsheets/"><u>Unleashing Productivity: AI Integration Into Docs & Spreadsheets</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/update-your-pc-download-amd-rx-6800-drivers-for-windows-7-10-and-11/"><u>Update Your PC: Download AMD RX 6800 Drivers for Windows 7, 10 & 11</u></a></li>
</ul></div>

