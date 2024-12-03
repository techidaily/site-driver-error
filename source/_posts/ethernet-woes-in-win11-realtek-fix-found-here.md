---
title: Ethernet Woes in Win11 - Realtek Fix Found Here
date: 2024-11-30T18:01:41.650Z
updated: 2024-12-02T18:29:37.002Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Ethernet Woes in Win11 - Realtek Fix Found Here
excerpt: This Article Describes Ethernet Woes in Win11 - Realtek Fix Found Here
thumbnail: https://thmb.techidaily.com/2ade3a49b6280463f663d29a0a9aed4a110f8560d1f316c09a570158c78fc956.jpg
---

## Ethernet Woes in Win11 - Realtek Fix Found Here

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b91ef1806793.jpg)

 Users have reported that their Realtek PCIe Family Controller (Ethernet) randomly stopped working after they upgraded to Windows 10\. There are still no answers from Microsoft or Realtek as to why would this happen, and this situation happens randomly on different occasions, so there are a lot of solutions that could be of help.

 If this is the problem you are experiencing now, please follow the instructions below to get it fixed by yourself.

[**Option One: Reset TCP/IP**](https://natural-cycles.sjv.io/vmebmr)
[**Option Two: Change Settings in Network Adapter Properties**](https://aofit.pxf.io/mmjyxq)
[**Option Three: Reinstall Realtek Adapter Driver**](https://westkiss.pxf.io/daqnaq)
[**Option Four: Update the Realtek Driver**](https://newchic.sjv.io/jzg4zq)

---

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9wiIVztRIqQ?si=GBgdwQ78k5hbeFDv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### **Option One: Reset TCP/IP**

1) On your keyboard, press the**Windows logo key** , type**cmd** , right-click**Command Prompt** from the results, and select**Run as administrator** .  
  
![how to open Command Prompt as an admin](https://images.drivereasy.com/wp-content/uploads/2023/10/win11-Command-Prompt-Run-as-administrator.jpg)

 When prompted with the following notification, hit**Yes** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de25ac8c94.jpg)

 2) Type in the following command:

netsh int ip reset c:\resetlog.txt

 Make sure that you have made no typo and hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de2ea5a2ef.png)

 This will help you reset your TCP/IP (Transmission Control Protocol/Internet Protocol). To make it easier to understand, TCP/IP is the language that your computer uses to communicate with the outside world. Reseting TCP/IP will help you revert your Internet settings to the stage where it still works.

---

### **Option Two:** **Change Settings in Network Adapter Properties**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
3) Then right-click Realtek PCIe GBE Family Controller option and choose **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de65b229a9.png)

 4) Go to**Advanced** tab, then choose**Speed & Duplex** option on the left side of the pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de6ed4d026.png)

 5) On the**Value** bar, change the default Auto Negotiation to **100 Mbps Full Duplex**  or some other options accordingly. We chose**100 Mbps Full Duplex** here, but yours could be different.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deb007e7e1.png)

 6) Now on the left side of the pane, choose**Energy Efficient Ethernet** option, then change the Value to**Disabled** . After the changes, hit**OK** to save.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deab52d9e0.png)

 7) Still, in the**Properties** window, this time, let’s go to**Power Management** tab. Un-tick the box for**Allow the computer to turn off this device to save power** . Then hit**OK** to save and exit.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587decc3276b5.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15Ju8Cb4UZ8?si=5wdiQXdz1BOxIkDH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

---

### **Option Three:** **Reinstall or Rollback Realtek Adapter Driver**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand the category**Network adapters** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RhLjZsruC9M?si=-861oUSfrUde2Ykt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/P6Wfzj6YNDM?si=WRZQD9zCdQ1_tW1b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

 Hit**OK** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LT4sdZgUvRQ?si=SvQD5FouEzu4UHpJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 4) Go to the menu bar on the top and click the button for **Scan for hardware changes** .  
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee9a707c2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xa2_mFu-obA?si=_xDGF1pv-dnuaDOr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 5) Windows will help you automatically install the correct driver that it can find. But there is no guarantee that the new driver is going to work since Windows has provided the not working one originally.

 If you clearly remember that your Ethernet stops working after you update to a certain version of the driver, it is suggested that you roll it back to the stage where it was working well.

---

### **Option Four: Update the Realtek Driver**

 The steps above may help you resolve the issue, but if they don’t, you can try to update the Realtek driver. If you don’t have time, patience, or computer skills to update the driver manually,  you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/) .**

**IMPORTANT:**  If you can’t have access to the internet due to the network driver issues, you can use **[Driver Easy Offline Scan Feature](https://tools.techidaily.com/drivereasy/download/)**  to download and install a new network driver.

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version, it takes just 2 clicks (and you get full support and a 30-day money-back guarantee):

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2023/03/Driver-Easy-download-needed-1200x900.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oP8grXxuy2o?si=uIRNhTYbecTcaC7J" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Click the **Update** button next to the Realtek PCIe driver to automatically download the correct version of this driver, then you can manually install it (you can do this with the FREE version).

 Or click **Update All**  to automatically download and install the correct version of _all_   the drivers that are missing or out of date on your system (this requires the Pro version – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2020/11/update-network-adapter-driver.jpg)

 Hopefully the tips above help you fix the Realtek Ethernet Controller driver not working issue. If you have any questions or ideas, feel free to leave your comments below, please.

* [Realtek](https://store.drivereasy.com/order/cart.php?PRODS=4731822&QTY=1&AFFILIATE=108875)

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
<li><a href="https://article-helps.techidaily.com/new-ultimate-tips-for-iphones-hdr-images-for-2024/"><u>[New] Ultimate Tips for iPhone's HDR Images for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-deciphering-hidden-content-on-youtube-an-ordered-walkthrough/"><u>[Updated] In 2024, Deciphering Hidden Content on YouTube An Ordered Walkthrough</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-snapshot-superiority-choosing-the-best-10-cameras/"><u>2024 Approved Snapshot Superiority Choosing the Best 10 Cameras</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-correcting-windows-update-error-0x8024401c-on-win1011-platforms/"><u>Effective Solutions for Correcting Windows Update Error 0X802#4401c on Win10/11 Platforms</u></a></li>
<li><a href="https://driver-error.techidaily.com/effective-strategies-to-fetch-latest-drivers-for-your-hp-envy-20-laptop/"><u>Effective Strategies to Fetch Latest Drivers for Your HP Envy 20 Laptop</u></a></li>
<li><a href="https://sound-issues.techidaily.com/fixing-razer-barracuda-x-microphone-issues-on-windows-11-and-10/"><u>Fixing Razer Barracuda X Microphone Issues on Windows 11 & 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-the-frustrating-access-is-denied-during-usb-installation-process/"><u>Fixing the Frustrating 'Access Is Denied' During USB Installation Process</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-navigating-the-best-lipo-cells-for-quality-flight-time/"><u>In 2024, Navigating the Best LiPo Cells for Quality Flight Time</u></a></li>
<li><a href="https://driver-error.techidaily.com/mastering-device-error-repair-in-dm/"><u>Mastering Device Error Repair in DM</u></a></li>
<li><a href="https://driver-error.techidaily.com/mastering-safe-mode-a-users-manual-to-uninstall-graphics-card-drivers-on-windows-ebox/"><u>Mastering Safe Mode: A User's Manual to Uninstall Graphics Card Drivers on Windows Ebox</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/navigating-new-norms-the-reluctance-of-hybrid-workers-to-rejoin-offices-and-impending-changes-zdnet/"><u>Navigating New Norms: The Reluctance of Hybrid Workers to Rejoin Offices and Impending Changes | ZDNet</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-gtx-ninety-five-error-with-codes-a-fix-guide-for-windows-eleven-users/"><u>Resolving GTX Ninety-Five Error with Codes: A Fix Guide for Windows Eleven Users</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-the-absent-coprocessor-driver-on-your-windows-10-system-guide/"><u>Resolving the Absent Coprocessor Driver on Your Windows 10 System [Guide]</u></a></li>
<li><a href="https://tech-haven.techidaily.com/safeguarding-your-secrets-against-unauthorized-access-through-tailored-gpt-systems/"><u>Safeguarding Your Secrets Against Unauthorized Access Through Tailored GPT Systems</u></a></li>
<li><a href="https://driver-error.techidaily.com/the-ultimate-guide-to-address-and-solve-incorrectly-set-up-errors-in-your-device-tackling-code-ebeerf/"><u>The Ultimate Guide to Address and Solve 'Incorrectly Set Up' Errors in Your Device - Tackling Code Ebeerf</u></a></li>
<li><a href="https://driver-error.techidaily.com/unmasking-ms-bda-via-visual-rendering/"><u>Unmasking MS BDA via Visual Rendering</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-skip-the-hunt-exclusive-filmora-coupon-codes-inside/"><u>Updated 2024 Approved Skip the Hunt Exclusive Filmora Coupon Codes Inside</u></a></li>
</ul></div>

