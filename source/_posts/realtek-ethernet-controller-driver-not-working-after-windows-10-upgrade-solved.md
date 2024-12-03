---
title: Realtek Ethernet Controller Driver Not Working After Windows 10 Upgrade [Solved]
date: 2024-11-25T18:52:41.211Z
updated: 2024-12-02T16:53:10.737Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Realtek Ethernet Controller Driver Not Working After Windows 10 Upgrade [Solved]
excerpt: This Article Describes Realtek Ethernet Controller Driver Not Working After Windows 10 Upgrade [Solved]
thumbnail: https://thmb.techidaily.com/f48216f44870658586ad3ccce716597fb01e77f0820fb3295ce715c935d7c91e.jpg
---

## Realtek Ethernet Controller Driver Not Working After Windows 10 Upgrade [Solved]

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b91ef1806793.jpg)

 Users have reported that their Realtek PCIe Family Controller (Ethernet) randomly stopped working after they upgraded to Windows 10\. There are still no answers from Microsoft or Realtek as to why would this happen, and this situation happens randomly on different occasions, so there are a lot of solutions that could be of help.

 If this is the problem you are experiencing now, please follow the instructions below to get it fixed by yourself.

[**Option One: Reset TCP/IP**](https://natural-cycles.sjv.io/vmebmr)
[**Option Two: Change Settings in Network Adapter Properties**](https://aofit.pxf.io/mmjyxq)
[**Option Three: Reinstall Realtek Adapter Driver**](https://westkiss.pxf.io/daqnaq)
[**Option Four: Update the Realtek Driver**](https://newchic.sjv.io/jzg4zq)

---

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLlUft1ZxI0?si=pBd5QdHEE27qsNlN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xa2_mFu-obA?si=_xDGF1pv-dnuaDOr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This will help you reset your TCP/IP (Transmission Control Protocol/Internet Protocol). To make it easier to understand, TCP/IP is the language that your computer uses to communicate with the outside world. Reseting TCP/IP will help you revert your Internet settings to the stage where it still works.

---

### **Option Two:** **Change Settings in Network Adapter Properties**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
3) Then right-click Realtek PCIe GBE Family Controller option and choose **Properties** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/L603QXgjb3I?si=sMYHfMGy2kNPSHPt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

---

### **Option Three:** **Reinstall or Rollback Realtek Adapter Driver**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand the category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hHPljBHrvkA?si=HwdfDM9rlbABSIrx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

 Hit**OK** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)

 4) Go to the menu bar on the top and click the button for **Scan for hardware changes** .  
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee9a707c2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RhLjZsruC9M?si=-861oUSfrUde2Ykt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://visual-screen-recording.techidaily.com/new-elite-arena-top-10-royale-game-spectacles-for-2024/"><u>[New] Elite Arena Top 10 Royale Game Spectacles for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-asmr-unraveled-enhancing-mental-wellness/"><u>[Updated] ASMR Unraveled Enhancing Mental Wellness</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-facebook-evolution-what-you-need-to-know/"><u>[Updated] In 2024, Facebook Evolution What You Need to Know</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-foundational-steps-to-your-distinctive-marketing-voice/"><u>[Updated] The Foundational Steps to Your Distinctive Marketing Voice</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-enabling-virtual-reality-on-your-phone-a-step-by-step-approach/"><u>2024 Approved Enabling Virtual Reality on Your Phone A Step-by-Step Approach</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-top-10-youtube-to-mp3-transformation-tools/"><u>2024 Approved Top 10 YouTube-to-MP3 Transformation Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-immediate-failure-effective-strategies-to-tackle-onedrive-folder-issues-on-pc/"><u>Conquering Immediate Failure: Effective Strategies to Tackle OneDrive Folder Issues on PC</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-fix-and-play-overcoming-launch-difficulties-with-skyrim/"><u>How to Fix and Play: Overcoming Launch Difficulties with Skyrim</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-reactivate-nonworking-right-click-on-windows-11-touchpad/"><u>How To Reactivate Nonworking Right Click on Windows 11 Touchpad</u></a></li>
<li><a href="https://driver-error.techidaily.com/intel-icd-identifying-the-opengl-driver/"><u>Intel ICD: Identifying the OpenGL Driver</u></a></li>
<li><a href="https://driver-error.techidaily.com/no-response-from-apple-tv-remote-on-macos-sierra-fix-ready/"><u>No Response From Apple TV Remote on MacOS Sierra (Fix Ready)</u></a></li>
<li><a href="https://driver-error.techidaily.com/pchelp-i-need-to-turn-off-the-built-in-bluetooth-on-my-windows-10-machine/"><u>PCHelp I Need to Turn Off the Built-In Bluetooth on My Windows 10 Machine</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolve-frequent-amd-driver-crashes-fast/"><u>Resolve Frequent AMD Driver Crashes Fast</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/short-lived-vid-impression/"><u>Short-Lived Vid Impression</u></a></li>
<li><a href="https://driver-error.techidaily.com/solutions-to-intel-wireless-bluetooth-drivers-not-working-on-your-windows-11-device/"><u>Solutions to Intel Wireless Bluetooth Drivers Not Working on Your Windows 11 Device</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-guide-restoring-functionality-of-your-non-responsive-hp-wireless-keyboard/"><u>Troubleshooting Guide: Restoring Functionality of Your Non-Responsive HP Wireless Keyboard</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-missing-touchpad-pointer-on-windows-11-a-step-by-step-guide/"><u>Troubleshooting Missing Touchpad Pointer on Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-correcting-a-missing-coprocessor-driver-on-windows-11-systems/"><u>Troubleshooting: Correcting a Missing Coprocessor Driver on Windows 11 Systems</u></a></li>
<li><a href="https://driver-error.techidaily.com/vehicle-vigilance-overcoming-error-e52/"><u>Vehicle Vigilance: Overcoming Error E52</u></a></li>
</ul></div>

