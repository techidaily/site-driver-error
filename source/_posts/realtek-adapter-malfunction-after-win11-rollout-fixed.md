---
title: Realtek Adapter Malfunction After Win11 Rollout Fixed
date: 2024-08-15T06:54:15.194Z
updated: 2024-08-16T06:54:15.194Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Realtek Adapter Malfunction After Win11 Rollout Fixed
excerpt: This Article Describes Realtek Adapter Malfunction After Win11 Rollout Fixed
thumbnail: https://thmb.techidaily.com/c27c29fba053b8832f23b24095348059aefd5880debbcb1a483191d3fe3d1075.jpg
---

## Realtek Adapter Malfunction After Win11 Rollout Fixed

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
### **Option Two:** **Change Settings in Network Adapter Properties**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
3) Then right-click Realtek PCIe GBE Family Controller option and choose **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de65b229a9.png)
<!-- affiliate ads begin -->

<!-- affiliate ads end -->

 4) Go to**Advanced** tab, then choose**Speed & Duplex** option on the left side of the pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de6ed4d026.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->

 5) On the**Value** bar, change the default Auto Negotiation to **100 Mbps Full Duplex**  or some other options accordingly. We chose**100 Mbps Full Duplex** here, but yours could be different.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deb007e7e1.png)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->

 6) Now on the left side of the pane, choose**Energy Efficient Ethernet** option, then change the Value to**Disabled** . After the changes, hit**OK** to save.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deab52d9e0.png)
<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 7) Still, in the**Properties** window, this time, let’s go to**Power Management** tab. Un-tick the box for**Allow the computer to turn off this device to save power** . Then hit**OK** to save and exit.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587decc3276b5.png)

---

### **Option Three:** **Reinstall or Rollback Realtek Adapter Driver**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 2) Locate and click the arrow to expand the category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

 Hit**OK** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->

 4) Go to the menu bar on the top and click the button for **Scan for hardware changes** .  
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee9a707c2.png)

 5) Windows will help you automatically install the correct driver that it can find. But there is no guarantee that the new driver is going to work since Windows has provided the not working one originally.

 If you clearly remember that your Ethernet stops working after you update to a certain version of the driver, it is suggested that you roll it back to the stage where it was working well.

---

<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://driver-error.techidaily.com/fixed-keyboard-not-working-on-windows-10/"><u>[Fixed] Keyboard Not Working on Windows 10</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-loop-like-a-boss-quick-and-easy-techniques-for-youtube-watchers/"><u>[New] 2024 Approved  Loop Like a Boss  Quick and Easy Techniques for YouTube Watchers</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-enhance-video-performance-selecting-top-12-players/"><u>[New] Enhance Video Performance  Selecting Top 12 Players</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-from-monotonous-to-magnificent-font-integration-in-ae/"><u>[New] From Monotonous to Magnificent  Font Integration in AE</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-asus-backlight-issue-identified/"><u>[SOLVED] ASUS Backlight Issue Identified</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-irqlnotlessorequal-bsod-in-windows-10/"><u>[Solved] IRQL_NOT_LESS_OR_EQUAL BSOD in Windows 10</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-how-android-enables-seamless-screen-capturing/"><u>[Updated] In 2024, How Android Enables Seamless Screen Capturing</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-profitable-pursuits-on-youtube-the-non-ad-revenue-roadmap/"><u>[Updated] Profitable Pursuits on YouTube  The Non-Ad Revenue Roadmap</u></a></li>
<li><a href="https://driver-error.techidaily.com/address-realtek-lan-problem-post-windows-10-upgrade/"><u>Address Realtek LAN Problem Post-Windows 10 Upgrade</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-gaps-combining-folders-and-files-win-1011-style/"><u>Bridging Gaps: Combining Folders & Files, Win 10/11 Style</u></a></li>
<li><a href="https://driver-error.techidaily.com/correcting-vertical-display-errors-on-your-asus-computer/"><u>Correcting Vertical Display Errors on Your ASUS Computer</u></a></li>
<li><a href="https://driver-error.techidaily.com/driver-error-code-bcm20702a0-unavailable/"><u>Driver Error Code BCM20702A0 Unavailable</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-pictures-from-infinix-smart-8-by-fonelab-android-recover-pictures/"><u>Easy steps to recover deleted pictures from Infinix Smart 8.</u></a></li>
<li><a href="https://driver-error.techidaily.com/effortless-solutions-overcoming-the-itbm-driver-access-problem/"><u>Effortless Solutions: Overcoming the ITBM Driver Access Problem</u></a></li>
<li><a href="https://driver-error.techidaily.com/enable-functional-right-click-on-windows-11-touchpad-solved/"><u>Enable Functional Right-Click on Windows 11 Touchpad [Solved]</u></a></li>
<li><a href="https://driver-error.techidaily.com/enhance-touchpad-functionality-fixed-right-click-in-windows-11/"><u>Enhance Touchpad Functionality - Fixed Right-Click in Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/expert-advice-resolving-non-responsive-hp-keyboard-problems-with-ease/"><u>Expert Advice: Resolving Non-Responsive HP Keyboard Problems with Ease</u></a></li>
<li><a href="https://driver-error.techidaily.com/expert-tips-restoring-your-qualcomm-atheros-bluetooth-connection-on-windows-vehicles-with-the-following-titles/"><u>Expert Tips: Restoring Your Qualcomm Atheros Bluetooth Connection on Windows Vehicles with the Following Titles</u></a></li>
<li><a href="https://driver-error.techidaily.com/failure-to-connect-device-due-to-missing-driver/"><u>Failure to Connect Device Due to Missing Driver</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-the-malfunction-of-your-latest-connected-usb-and-regaining-recognition-in-windows/"><u>Fixing the Malfunction of Your Latest Connected USB and Regaining Recognition in Windows</u></a></li>
<li><a href="https://driver-error.techidaily.com/graphics-installer-maneuver-victory-achieved/"><u>Graphics Installer Maneuver – Victory Achieved</u></a></li>
<li><a href="https://driver-error.techidaily.com/guide-to-kill-bluetooth-on-windows-10/"><u>Guide to Kill Bluetooth on Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-fix-the-driver-being-installed-is-not-validated-for-this-computer/"><u>How to Fix: The Driver Being Installed Is Not Validated for This Computer</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-vivo-x-fold-2-drfone-by-drfone-virtual-android/"><u>How to Get and Use Pokemon Go Promo Codes On Vivo X Fold 2 | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-send-and-fake-live-location-on-facebook-messenger-of-your-realme-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>How to Send and Fake Live Location on Facebook Messenger Of your Realme 12 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://program-issues.techidaily.com/overcoming-voice-chat-setbacks-in-among-us-on-desktop-pcs/"><u>Overcoming Voice Chat Setbacks in Among Us on Desktop PCs</u></a></li>
<li><a href="https://driver-error.techidaily.com/secrets-to-silence-wired-bluetooth-on-windows/"><u>Secrets to Silence Wired Bluetooth on Windows</u></a></li>
<li><a href="https://driver-error.techidaily.com/solve-disabled-right-click-error-in-windows-11-touchpad/"><u>Solve Disabled Right-Click Error in Windows 11 Touchpad</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-intel-wi-fi-6-ax201-malfunctioning/"><u>Solved: Intel Wi-Fi 6 Ax201 Malfunctioning</u></a></li>
<li><a href="https://driver-error.techidaily.com/system-complaint-non-responsive-keyboard/"><u>System Complaint: Non-Responsive Keyboard</u></a></li>
<li><a href="https://driver-error.techidaily.com/tackling-problems-with-older-usb-device-types-resolved-insights/"><u>Tackling Problems with Older USB Device Types: Resolved Insights</u></a></li>
<li><a href="https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-vivo-v29-pro-drfone-by-drfone-virtual-android/"><u>Thinking About Changing Your Netflix Region Without a VPN On Vivo V29 Pro? | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-non-functional-qualcomm-atheros-bluetooth-in-windows-11-solved/"><u>Troubleshooting Non-Functional Qualcomm Atheros Bluetooth in Windows 11 [Solved]</u></a></li>
<li><a href="https://android-frp.techidaily.com/ultimate-guide-on-motorola-razr-40-frp-bypass-by-drfone-android/"><u>Ultimate Guide on Motorola Razr 40 FRP Bypass</u></a></li>
<li><a href="https://driver-error.techidaily.com/unwanted-windows-11-bluetooth-how-to-stop-it/"><u>Unwanted Windows 11 Bluetooth: How to Stop It</u></a></li>
<li><a href="https://driver-error.techidaily.com/usb-device-not-recognized-in-windows-heres-how-to-fix-it/"><u>USB Device Not Recognized in Windows? Here's How to Fix It!</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-when-vivo-x100-has-black-screen-of-death-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do When Vivo X100 Has Black Screen of Death? | Dr.fone</u></a></li>
</ul></div>
