---
title: Resolving 'Unable to Install Hcmond Device Driver' Issues
date: 2024-08-22T14:10:50.345Z
updated: 2024-08-23T14:10:50.345Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Resolving 'Unable to Install Hcmond Device Driver' Issues
excerpt: This Article Describes Resolving 'Unable to Install Hcmond Device Driver' Issues
thumbnail: https://thmb.techidaily.com/eb0b88fc8ea01a6f57ac593062a230bcd4f411a04c405e68f58f5857acd450ec.jpg
---

## Resolving 'Unable to Install Hcmond Device Driver' Issues

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
 3) Click the **Update** button next to the flagged drivers to automatically download and install the correct version of their driver (you can do this with the FREE version). Or click **Update All**  to automatically download and install the correct version of _all_   the drivers that are missing or out of date on your system (this requires the Pro version – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ca0a7166942.jpg)

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
##

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
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

 2) Go to the location where you saved the setup file. This is to get the msi name.

 3) Type**.\\xxxx.msi** in PowerShell command prompt and press**Enter** on your keyboard. XXXX means the name of msi file. Replace it with your msi file name.

In my case, my file is “VMware-VMRC-10.0.1-5898794”:

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ca1311509ab.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
So I typed “.\\VMware-VMRC-10.0.1-5898794.msi”:

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ca13ea65f0f.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
##

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
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


