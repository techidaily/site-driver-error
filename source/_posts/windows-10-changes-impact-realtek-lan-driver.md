---
title: Windows 10 Changes Impact Realtek LAN Driver
date: 2024-08-15T06:51:40.537Z
updated: 2024-08-16T06:51:40.537Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Windows 10 Changes Impact Realtek LAN Driver
excerpt: This Article Describes Windows 10 Changes Impact Realtek LAN Driver
thumbnail: https://thmb.techidaily.com/908abdf5786977a17c0b2ecf2fc693bdf5a10c0549e2851740329dd839b1ac68.jpg
---

## Windows 10 Changes Impact Realtek LAN Driver

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b91ef1806793.jpg)

 Users have reported that their Realtek PCIe Family Controller (Ethernet) randomly stopped working after they upgraded to Windows 10\. There are still no answers from Microsoft or Realtek as to why would this happen, and this situation happens randomly on different occasions, so there are a lot of solutions that could be of help.

 If this is the problem you are experiencing now, please follow the instructions below to get it fixed by yourself.

[**Option One: Reset TCP/IP**](https://natural-cycles.sjv.io/vmebmr)
[**Option Two: Change Settings in Network Adapter Properties**](https://aofit.pxf.io/mmjyxq)
[**Option Three: Reinstall Realtek Adapter Driver**](https://westkiss.pxf.io/daqnaq)
[**Option Four: Update the Realtek Driver**](https://newchic.sjv.io/jzg4zq)

---

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

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
### **Option Two:** **Change Settings in Network Adapter Properties**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
 2) Locate and click the arrow to expand category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
3) Then right-click Realtek PCIe GBE Family Controller option and choose **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de65b229a9.png)

 4) Go to**Advanced** tab, then choose**Speed & Duplex** option on the left side of the pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de6ed4d026.png)

 5) On the**Value** bar, change the default Auto Negotiation to **100 Mbps Full Duplex**  or some other options accordingly. We chose**100 Mbps Full Duplex** here, but yours could be different.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deb007e7e1.png)
<!-- affiliate ads begin -->
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->

 6) Now on the left side of the pane, choose**Energy Efficient Ethernet** option, then change the Value to**Disabled** . After the changes, hit**OK** to save.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deab52d9e0.png)

 7) Still, in the**Properties** window, this time, let’s go to**Power Management** tab. Un-tick the box for**Allow the computer to turn off this device to save power** . Then hit**OK** to save and exit.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587decc3276b5.png)

---

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
### **Option Three:** **Reinstall or Rollback Realtek Adapter Driver**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
 2) Locate and click the arrow to expand the category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)
<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Hit**OK** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)
<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4) Go to the menu bar on the top and click the button for **Scan for hardware changes** .  
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee9a707c2.png)

 5) Windows will help you automatically install the correct driver that it can find. But there is no guarantee that the new driver is going to work since Windows has provided the not working one originally.

 If you clearly remember that your Ethernet stops working after you update to a certain version of the driver, it is suggested that you roll it back to the stage where it was working well.

---

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
### **Option Four: Update the Realtek Driver**

 The steps above may help you resolve the issue, but if they don’t, you can try to update the Realtek driver. If you don’t have time, patience, or computer skills to update the driver manually,  you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/) .**

**IMPORTANT:**  If you can’t have access to the internet due to the network driver issues, you can use **[Driver Easy Offline Scan Feature](https://tools.techidaily.com/drivereasy/download/)**  to download and install a new network driver.

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version, it takes just 2 clicks (and you get full support and a 30-day money-back guarantee):

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2023/03/Driver-Easy-download-needed-1200x900.jpg)

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
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-binge-worthy-vids-the-most-shared-content-on-fb-featured-here/"><u>[New] 2024 Approved  Binge-Worthy Vids! The Most Shared Content on FB Featured Here</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-razer-mouse-freezing-on-windows-11/"><u>[Solved] Razer Mouse Freezing on Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-enhance-your-gpu-performance-step-bysis-guide-inside/"><u>[Solved]: Enhance Your GPU Performance – Step-Bysis Guide Inside</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-get-more-from-tiny-screens-top-6-youtube-shorts-downloader-apps/"><u>[Updated] Get More From Tiny Screens  Top 6 YouTube Shorts Downloader Apps</u></a></li>
<li><a href="https://driver-error.techidaily.com/37-resolved-device-driver-init-failed/"><u>37 Resolved: Device Driver Init Failed</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/7-ways-to-unlock-a-locked-realme-gt-5-phone-by-drfone-android/"><u>7 Ways to Unlock a Locked Realme GT 5 Phone</u></a></li>
<li><a href="https://driver-error.techidaily.com/alleviate-cable-transmission-bug/"><u>Alleviate Cable Transmission Bug</u></a></li>
<li><a href="https://win-able.techidaily.com/back-4-blood-on-pc-say-goodbye-to-unexpected-game-crashes/"><u>Back 4 Blood on PC - Say Goodbye to Unexpected Game Crashes</u></a></li>
<li><a href="https://driver-error.techidaily.com/bluetooth-woes-on-windows-11-solve-your-qualcomm-atheros-driver-challenges-here/"><u>Bluetooth Woes on Windows 11? Solve Your Qualcomm Atheros Driver Challenges Here!</u></a></li>
<li><a href="https://technical-tips.techidaily.com/diagnosing-and-repairing-nspr4dll-error-tips-and-techniques/"><u>Diagnosing and Repairing Nspr4.dll Error - Tips & Techniques</u></a></li>
<li><a href="https://driver-error.techidaily.com/driver-disabled-bcm20702a0/"><u>Driver Disabled: BCM20702A0</u></a></li>
<li><a href="https://driver-error.techidaily.com/enhancing-stability-actions-against-nvidia-glitches/"><u>Enhancing Stability: Actions Against Nvidia Glitches</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-hp-photosmart-printer-driver-issues-for-windows-11/"><u>Fix HP Photosmart Printer Driver Issues for Windows 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/free-to-use-travel-wizards-the-compilation-of-top-7-planning-apps/"><u>Free-to-Use Travel Wizards - The Compilation of Top 7 Planning Apps</u></a></li>
<li><a href="https://driver-error.techidaily.com/get-back-to-connecting-effortlessly-resolve-bluetooth-problems-on-latest-os-update-in-no-time-guide-inside/"><u>Get Back to Connecting Effortlessly – Resolve Bluetooth Problems on Latest OS Update in No Time [Guide Inside]</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-fix-asus-acpi-driver-issues-in-windows-11/"><u>How to Fix Asus ACPI Driver Issues in Windows 11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-navigating-filmoras-fcc-initiative-a-guide/"><u>In 2024, Navigating Filmora's FCC Initiative  A Guide</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-srt-conversion-made-simple-xml-ssa-ttml-and-more/"><u>In 2024, SRT Conversion Made Simple  XML, SSA, TTML, and More</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-vivo-y100a-device-by-drfone-android/"><u>In 2024, The Ultimate Guide How to Bypass Swipe Screen to Unlock on Vivo Y100A Device</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-windowsmac-meeting-record-skype-guide/"><u>In 2024, Windows/Mac Meeting Record - Skype Guide</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-similar-software-or-alternatives-to-virtualdub/"><u>New 2024 Approved Similar Software or Alternatives to VirtualDub</u></a></li>
<li><a href="https://driver-error.techidaily.com/pci-device-drivers-download-for-windows-11-10-8-7/"><u>PCI Device Drivers Download for Windows 11, 10, 8, 7</u></a></li>
<li><a href="https://driver-error.techidaily.com/quick-fixes-for-overcoming-the-missing-itbm-driver-error-get-back-online-now/"><u>Quick Fixes for Overcoming the Missing ITBM Driver Error – Get Back Online Now!</u></a></li>
<li><a href="https://driver-error.techidaily.com/radeon-settings-host-application-has-stopped-working-solved/"><u>Radeon Settings: Host Application Has Stopped Working [SOLVED]</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721103422515-resolve-uninstalled-device-drivers-in-windows-1187-with-easy-fixes/"><u>Resolve Uninstalled Device Drivers in Windows 11/8/7 With Easy Fixes!</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721096821860-speedily-correct-the-missing-itbm-driver-issue-with-simple-tips/"><u>Speedily Correct the Missing ITBM Driver Issue with Simple Tips</u></a></li>
<li><a href="https://driver-error.techidaily.com/strategic-approach-to-base-system-driver-troubles/"><u>Strategic Approach to Base System Driver Troubles</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/tp-link-av1300-extender-assessment-evaluating-effectiveness-in-boosting-home-wireless-networks/"><u>TP-Link AV1300 Extender Assessment: Evaluating Effectiveness in Boosting Home Wireless Networks</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshoot-and-fix-unresponsive-gadgets-in-windows-operating-systems-solution-included/"><u>Troubleshoot and Fix Unresponsive Gadgets in Windows Operating Systems (Solution Included)</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-code-1-fixing-incorrect-device-configuration/"><u>Troubleshooting Code 1: Fixing Incorrect Device Configuration</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-correcting-the-failed-to-load-hcmonservice-message/"><u>Troubleshooting: Correcting the 'Failed to Load Hcmonservice' Message</u></a></li>
<li><a href="https://driver-error.techidaily.com/unhindered-interaction-mouse-and-windows-10-fixes/"><u>Unhindered Interaction: Mouse & Windows 10 Fixes</u></a></li>
<li><a href="https://driver-error.techidaily.com/unlocking-enhanced-surround-audio-making-your-dolby-pro-logic-iix-driver-work-again-in-win-10-done/"><u>Unlocking Enhanced Surround Audio: Making Your Dolby Pro Logic IIx Driver Work Again in Win 10 – Done!🎶</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721104319235-win10-and-seagate-connection-woes-fix-now/"><u>Win10 & Seagate Connection Woes - Fix Now!</u></a></li>
<li><a href="https://driver-error.techidaily.com/wudfrd-startup-error-device-event-code-219/"><u>WudfRd Startup Error - Device Event Code 219</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/youtube-journey-enhancers-best-narrative-methods-for-2024/"><u>YouTube Journey Enhancers  Best Narrative Methods for 2024</u></a></li>
</ul></div>
