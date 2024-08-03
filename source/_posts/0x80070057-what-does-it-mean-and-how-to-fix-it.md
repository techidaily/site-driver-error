---
title: "0X80070057: What Does It Mean & How to Fix It?"
date: 2024-07-15T06:51:22.666Z
updated: 2024-07-16T06:51:22.666Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: "This Article Describes 0X80070057: What Does It Mean & How to Fix It?"
excerpt: "This Article Describes 0X80070057: What Does It Mean & How to Fix It?"
thumbnail: https://thmb.techidaily.com/33c48593ec0173b68a8667f248e53142d39bc8c3611fadd3a7f85564f8ade76e.jpg
---

## 0X80070057: What Does It Mean & How to Fix It?

 If you’re on Windows and you see the error code 0x80070057 showing up and you have no idea how to deal with it, you’re not alone. Many Windows users are reporting this problem as well. But don’t worry, it’s possible to fix it.

 The annoying part about this error code is, you can see it in many places. You should use different approaches when you see it in different situations. Here are 3 situations and their fixes accordingly, you should select from them and fix this problem right away.

1. [**Windows Update error 0x80070057**](https://technitya.sjv.io/dkpn02)
2. **[The parameter is incorrect. (0x80070057)](#fix2)**
3. **[Microsoft Office Error Code 0x80070057](https://dhgate.sjv.io/5g6yb2)**
4. **[Good to go?](https://lenovo-in.zlvv.net/kj14kn)**

## 1\. Windows Update error 0x80070057

 If you run into this error in Windows Update, try renaming the**SoftwareDistribution** folder in your computer. This works in most cases.

To do so, follow these steps:

 1) Press**Windows key** and**R** at them same time to open Run box. Type**%systemroot%** in the search box and hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_579077283a94a.png)

 2)Right-click **SoftwareDistribution**  and **Rename** it **SoftwareDistribution.old** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_579077f0654e5.png)

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_5790782d1d925.png)

 3) You might need to provide administrator permission to continue this step. Just click**Continue** to go on.

 4) Type**services** in the search box and click**Services** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_57907ce0b2ec6.png)

 Make sure the status of **Windows Update** here is**Started** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_57907a2431653.png)

5) Restart your computer after the change.

## 2\. The parameter is incorrect. (0x80070057)

### Method 1: Change the Decimal Symbol Setting

 The problem could occur if the decimal symbol is not set to “**.** “(dot). This situation is common in languages other than English(United States).

 1) Follow the path **Control Panel (View by Category)> Clock, Language, and Region** . (For Windows 10:**Clock and Region**)

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_57904f1a2d58b.png)

 2) Click **Region and Language** . (For Windows 10:**Region**)

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_57904f364448e.png)

 3) Click **Formats** , then click**Additional settings** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_57904f65d4cb8.png)

 4) In the**Decimal symbol** field, type**.** (dot) and then click**OK** two times.

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_57904fc16e9e7.png)

5) Restart your computer after the change.

### Method 2: Add a Registry Key Value

**Note** : Faulty changes in registry value could cause some unrecoverable error which will do damage to your computer, so in case of any further error, please [back-up your registry](https://tools.techidaily.com/drivereasy/download/) first and restore it should anything go wrong.

 1) Click the **Start** button and type**regedit** in the search box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_5790736ebb1b3.png)

 2) Follow the path
 **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Policies\\Microsoft\\SystemCertificates.**

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_579073b7d4adf.png)

 3) On the right side of the pane, right-click the blank space and choose**DWORD Value** when the**New** option occurs.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_57907416a5d9b.png)

 4) Change the name to **CopyFileBufferedSynchronousIo** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_5790747482ec5.png)

 5) Double-click to change the**Value data** to**1** and press**OK** to save.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_579074900718f.png)

6) Exit Registry and restart your computer after the change.

## 3\. Microsoft Office Error Code 0x80070057

 This error is also commonly seen when you are tying to install Microsoft Office or in the middle of using it. To solve this problem, you can temporarily disable firewall and disable antivirus software.

To turn off firewall in Windows, you could follow the steps below.

 1) Follow the path **Control Panel > System and Security > Windows Firewall >** **Turn Windows Firewall on or off** .

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_579083bc1a8b6.png)

 2) You could choose the option**Turn off Windows Firewall (not recommended)** temporarily until the error got fixed.

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
![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_579083f1a6a4a.png)

 3) Repair the Office Click-to-run application. Right-click**Start** button and find**Uninstall a program** under**Programs** , and click it.

 Scroll mouse to look for**Microsoft Office 365** and click**Change** . You need to restart computer and try the installation again.

## 4\. Good to go?

**PRO TIP** : If the problem still remains after trying the fixes above, it’s time to update your device drivers.

 You can try the Free version of [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) , and update all of your drivers one by one.

**OR**

 Update all your missing and outdated drivers**automatically** with just one click with [**Driver Easy Pro**](https://tools.techidaily.com/drivereasy/download/) . Just give it a try as it comes with a no-questions-asked**30-day money-back guarantee** and**professional tech support** .

**All the drivers in Driver Easy** **come straight from** **the manufacturer** .

![](https://images.drivereasy.com/wp-content/uploads/2019/12/update-all-your-drivers-2.jpg)

 If you need assistance, please contact **Driver Easy’s support** **team** at [**support@drivereasy.com**](https://vapordna.pxf.io/vnbxna) .

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


