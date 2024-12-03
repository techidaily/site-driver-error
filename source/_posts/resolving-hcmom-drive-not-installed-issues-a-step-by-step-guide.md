---
title: "Resolving 'Hcmom Drive Not Installed' Issues: A Step-by-Step Guide"
date: 2024-11-26T21:01:53.816Z
updated: 2024-12-02T20:38:00.524Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: "This Article Describes Resolving 'Hcmom Drive Not Installed' Issues: A Step-by-Step Guide"
excerpt: "This Article Describes Resolving 'Hcmom Drive Not Installed' Issues: A Step-by-Step Guide"
thumbnail: https://thmb.techidaily.com/18d1ae3b93316df7253b6d9ca3430e2e7b9da85a6ae22dbb42da5be064fc57fa.png
---

## Resolving 'Hcmom Drive Not Installed' Issues: A Step-by-Step Guide

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Sj2QNA-JXI?si=V-_h73iE3VlE214k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Solution 1: Install the product as an administrator

 When you install the product, you’re required to install the hcmon driver. Windows may see this as a user adding hardware to the PC. But this user doesn’t have the permission to do that. In this case, this error may occur. Try to install the product as an administrator:

1) Right-click on the downloaded setup file.

2) Click**Run as administrator** . If you don’t see the option “Run as administrator”, this solution doesn’t apply to you. Skip then move on to other solutions.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ca09694f9d6.png)

##

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RBN1gYY5hUs?si=p89CMiMzeJzU0wGu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hXIq2G0nShk?si=5Z4Fwv7ZB6oKWsdd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Solution 4: Install the product using PowerShell

Try to install the product in PowerShell. Follow steps below:

 1) Type “powershell” in the search field. Right-click**Windows PowerShell** (The name may be different depending on the Windows version you’re using.) and click**Run as administrator** .

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ca0f0ca0506.png)

 2) Go to the location where you saved the setup file. This is to get the msi name.

 3) Type**.\\xxxx.msi** in PowerShell command prompt and press**Enter** on your keyboard. XXXX means the name of msi file. Replace it with your msi file name.

In my case, my file is “VMware-VMRC-10.0.1-5898794”:

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ca1311509ab.png)

So I typed “.\\VMware-VMRC-10.0.1-5898794.msi”:

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ca13ea65f0f.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/w7c5EHp-GDw?si=UTw7lZR0wTmRjp8W" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MHafwnWSEQk?si=rejNVNpJZH2SqNLy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://driver-error.techidaily.com/engaged-troubleshooting-for-unrecognized-devices-stopped/"><u>[ENGAGED] Troubleshooting for Unrecognized Devices Stopped</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-inshots-competitors-for-pclaptop-editors/"><u>[New] Inshot's Competitors for PC/Laptop Editors</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-arcade-adventurers-approaches/"><u>[Updated] ARCADE ADVENTURERS' APPROACHES</u></a></li>
<li><a href="https://driver-error.techidaily.com/balance-windows-7-dell-interactive-elements/"><u>Balance Windows 7 Dell Interactive Elements</u></a></li>
<li><a href="https://driver-error.techidaily.com/devhub-error-48-now-fixed/"><u>DevHub Error #48 Now Fixed</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-after-format-on-realme-c53-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos from Android Gallery after format on Realme C53</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-xiaomi-14-ultra-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Xiaomi 14 Ultra to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcoming-the-challenges-of-gtx-950-code-43-on-your-windows-11-machine-expert-advice/"><u>Overcoming the Challenges of GTX 950 Code 43 on Your Windows 11 Machine - Expert Advice</u></a></li>
<li><a href="https://facebook.techidaily.com/rank-your-social-sites-today/"><u>Rank Your Social Sites Today</u></a></li>
<li><a href="https://driver-error.techidaily.com/restoring-normality-of-windows-input-keys/"><u>Restoring Normality of Windows Input Keys</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-perfect-order-for-viewing-the-matrix-franchise-on-your-screen/"><u>The Perfect Order for Viewing The Matrix Franchise on Your Screen</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/weighing-the-financial-outcomes-for-premium-ai-inputs/"><u>Weighing the Financial Outcomes for Premium AI Inputs</u></a></li>
</ul></div>

