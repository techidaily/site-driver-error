---
title: How to Fix Failed to Install the Hcmon Driver Error
date: 2024-12-14T01:57:05.303Z
updated: 2024-12-16T02:20:49.204Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes How to Fix Failed to Install the Hcmon Driver Error
excerpt: This Article Describes How to Fix Failed to Install the Hcmon Driver Error
thumbnail: https://thmb.techidaily.com/a50a3cec0521fa6fb800284717c9122c07291a0277fd1f77229ad231586b5b14.jpg
---

## How to Fix Failed to Install the Hcmon Driver Error

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59c9ee600eb02.jpg)

 If you get error “Failed to install the hcmon driver” during installing the VMware products (vSphere, Remote Console, etc.),  don’t worry. You can fix the problem with one of the solutions in this article.

## What is the HCMON driver?

 HCMON driver is a virtual USB driver. It allows your physical USB ports to connect to the virtual machines.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Double-click**Non-Plug and Play Drivers.**

 4) Right-click**hcmon** and click**Uninstall** .

 6) Delete the**C:\\Windows\\system32\\drivers\\hcmon.sys** file.

 7) Restart the computer.

##

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XIUatTFH0Zw?si=ZCtoBtIy18y2F5Vc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Solution 4: Install the product using PowerShell

Try to install the product in PowerShell. Follow steps below:

 1) Type “powershell” in the search field. Right-click**Windows PowerShell** (The name may be different depending on the Windows version you’re using.) and click**Run as administrator** .

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ca0f0ca0506.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Jfq2Wx1Bcs?si=YQrYpTy0g4aV5QaO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 2) Go to the location where you saved the setup file. This is to get the msi name.

 3) Type**.\\xxxx.msi** in PowerShell command prompt and press**Enter** on your keyboard. XXXX means the name of msi file. Replace it with your msi file name.

In my case, my file is “VMware-VMRC-10.0.1-5898794”:

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ca1311509ab.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LBCobAYzzcc?si=J3eSTQ3AdyxWAjGo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

So I typed “.\\VMware-VMRC-10.0.1-5898794.msi”:

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ca13ea65f0f.png)

##

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mHFtYJppXFk?si=ylFaAT4nXqCmlV8F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://driver-error.techidaily.com/fixed-wireless-mouse-not-working-on-windows/"><u>[Fixed] Wireless Mouse Not Working on Windows</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/npacking-youtubes-social-media-code-of-conduct-for-2024/"><u>[New] Unpacking YouTube's Social Media Code of Conduct for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-a-step-by-step-approach-for-effective-spotify-marketing/"><u>[Updated] A Step-by-Step Approach for Effective Spotify Marketing</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-laughable-phone-melodies-essential-sites-listed/"><u>[Updated] Laughable Phone Melodies Essential Sites Listed</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-prime-methods-for-turning-youtube-videos-into-mpegs/"><u>[Updated] Prime Methods for Turning YouTube Videos Into MPEGs</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unleash-your-potential-top-6-head-mounted-cameras-by-gopro/"><u>2024 Approved Unleash Your Potential Top 6 Head-Mounted Cameras by GoPro</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-missing-seagate-external-drive-in-new-os/"><u>Fixing Missing Seagate External Drive in New OS</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-qualcomm-atheros-bluetooth-issues-on-windows-10-complete-solution/"><u>Fixing Qualcomm Atheros Bluetooth Issues on Windows 10: Complete Solution</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-erase-your-yahoo-mail-account-forever-a-step-by-step-process/"><u>How to Erase Your Yahoo Mail Account Forever – A Step-by-Step Process</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-pause-life360-location-sharing-for-htc-u23-pro-drfone-by-drfone-virtual-android/"><u>How To Pause Life360 Location Sharing For HTC U23 Pro | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-resolve-windows-n11s-absent-cpu-coprocessor-driver-problem/"><u>How to Resolve Windows N11's Absent CPU Coprocessor Driver Problem</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-the-missing-coprocessor-driver-issue-in-windows-11/"><u>Resolving the 'Missing Coprocessor Driver' Issue in Windows 11</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/the-ultimate-guide-to-gaming-displays-why-asus-vg245h-rules-them-all/"><u>The Ultimate Guide to Gaming Displays: Why Asus VG245H Rules Them All</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-are-location-permissions-life360-on-nokia-c12-drfone-by-drfone-virtual-android/"><u>What are Location Permissions Life360 On Nokia C12? | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-mouse-misfires/"><u>Windows Mouse Misfires</u></a></li>
<li><a href="https://driver-error.techidaily.com/winning-against-the-notorious-code-43-error-on-your-gtx-950-while-using-windows-10-a-step-by-step-fix/"><u>Winning Against the Notorious Code 43 Error on Your GTX 950 While Using Windows 10 – A Step-by-Step Fix</u></a></li>
</ul></div>

