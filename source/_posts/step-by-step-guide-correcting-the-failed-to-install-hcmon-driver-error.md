---
title: "Step-by-Step Guide: Correcting the 'Failed to Install Hcmon Driver Error'"
date: 2024-12-09T18:19:08.846Z
updated: 2024-12-16T07:56:57.499Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: "This Article Describes Step-by-Step Guide: Correcting the 'Failed to Install Hcmon Driver Error'"
excerpt: "This Article Describes Step-by-Step Guide: Correcting the 'Failed to Install Hcmon Driver Error'"
thumbnail: https://thmb.techidaily.com/4e8500390862c71ba9fd3f45025661c15b6c8c5d9fdf1c818444f469b9c52d07.PNG
---

## Step-by-Step Guide: Correcting the 'Failed to Install Hcmon Driver Error'

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59c9ee600eb02.jpg)

 If you get error “Failed to install the hcmon driver” during installing the VMware products (vSphere, Remote Console, etc.),  don’t worry. You can fix the problem with one of the solutions in this article.

## What is the HCMON driver?

 HCMON driver is a virtual USB driver. It allows your physical USB ports to connect to the virtual machines.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to fix this error?

 The error occurs can be due to different issues. We post the top 5 solutions in this article. You can fix this error with one of these solutions. You may not have to try them all. Just work your way down until you find the one that works for you.

 Solution 1:**[Install the product as an administrator](https://pish-posh-baby.sjv.io/g1jg15)**
 Solution 2:**[Update the drivers](https://ship7com.pxf.io/0zwaz3)**
 Solution 3:**[Remove the hcmon.sys driver](https://ancheer.sjv.io/y96bgp)**
 Solution 4:**[Install the product using PowerShell](https://printrendy.pxf.io/xyboy5)**
 Solution 5: **[Install .NET Framework 3.5.1](https://ursime.pxf.io/r5bm57)**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MmTJlcwgyrQ?si=x3hba82M0tT57fj7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Solution 1: Install the product as an administrator

 When you install the product, you’re required to install the hcmon driver. Windows may see this as a user adding hardware to the PC. But this user doesn’t have the permission to do that. In this case, this error may occur. Try to install the product as an administrator:

1) Right-click on the downloaded setup file.

2) Click**Run as administrator** . If you don’t see the option “Run as administrator”, this solution doesn’t apply to you. Skip then move on to other solutions.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ca09694f9d6.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jnITUsxMz5s?si=ohwRVH6eWhVnC6Xf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/X4q6gyaEojM?si=ImdFm6Zsr0azykqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 2) Go to the location where you saved the setup file. This is to get the msi name.

 3) Type**.\\xxxx.msi** in PowerShell command prompt and press**Enter** on your keyboard. XXXX means the name of msi file. Replace it with your msi file name.

In my case, my file is “VMware-VMRC-10.0.1-5898794”:

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ca1311509ab.png)

So I typed “.\\VMware-VMRC-10.0.1-5898794.msi”:

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ca13ea65f0f.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##

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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-guiding-adding-songs-to-your-yt-channel/"><u>[New] 2024 Approved Guiding Adding Songs to Your YT Channel</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-boosting-remote-meeting-effectiveness-through-optimized-zoom-recordings-for-2024/"><u>[New] Boosting Remote Meeting Effectiveness Through Optimized Zoom Recordings for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/harting-growth-the-best-online-stock-yts-for-2024/"><u>[New] Charting Growth The Best Online Stock YTs for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-navigating-instas-archive-maze-for-optimal-results/"><u>[New] Navigating Insta’s Archive Maze for Optimal Results</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-pros-picks-best-10-terraria-mods/"><u>[Updated] Pro's Picks Best 10 Terraria Mods</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-ultimate-path-to-flawless-video-subtitles-via-internet-services/"><u>2024 Approved The Ultimate Path to Flawless Video Subtitles via Internet Services</u></a></li>
<li><a href="https://driver-error.techidaily.com/bring-back-your-touchpad-driver-missing-heres-what-you-can-do/"><u>Bring Back Your Touchpad: Driver Missing? Here's What You Can Do</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-resolve-your-iphones-media-transport-problem-with-updated-usb-drivers/"><u>How to Resolve Your iPhone's Media Transport Problem with Updated USB Drivers</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-wiped-call-history-on-poco-x5-by-fonelab-android-recover-call-logs/"><u>How to restore wiped call history on Poco X5?</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-pgsharp-legal-when-you-are-playing-pokemon-on-oppo-find-x6-drfone-by-drfone-virtual-android/"><u>In 2024, Is pgsharp legal when you are playing pokemon On Oppo Find X6? | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/iphone-cannot-connect-to-computer-heres-how-you-can-fix-the-mtp-usb-device-driver-malfunction/"><u>IPhone Cannot Connect to Computer? Here's How You Can Fix the MTP USB Device Driver Malfunction</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-windows-11s-elan-pad-hurdles-for-smooth-use/"><u>Overcoming Windows 11'S Elan Pad Hurdles for Smooth Use</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshoot-and-resolve-qualcomm-atheros-bluetooth-driver-problems-in-windows-11/"><u>Troubleshoot and Resolve Qualcomm Atheros Bluetooth Driver Problems in Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/unsupported-device-no-intel-adapters-detected/"><u>Unsupported Device - No Intel Adapters Detected</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-videopad-video-editor-a-thorough-review-and-comparison-with-other-options/"><u>Updated In 2024, Videopad Video Editor A Thorough Review and Comparison with Other Options</u></a></li>
<li><a href="https://driver-error.techidaily.com/win11-system-thwarts-gpu-connection/"><u>Win11 System Thwarts GPU Connection</u></a></li>
</ul></div>

