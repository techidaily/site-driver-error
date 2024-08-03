---
title: "Win11 Install: Realtek Ethernet Driver Error Resolved"
date: 2024-08-02T07:26:26.898Z
updated: 2024-08-03T07:26:26.898Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: "This Article Describes Win11 Install: Realtek Ethernet Driver Error Resolved"
excerpt: "This Article Describes Win11 Install: Realtek Ethernet Driver Error Resolved"
thumbnail: https://thmb.techidaily.com/64b02260fc2e331299df22a1e999eab91ad890c07462ad4672fe1c0550ce5fa1.jpg
---

## Win11 Install: Realtek Ethernet Driver Error Resolved

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b91ef1806793.jpg)

 Users have reported that their Realtek PCIe Family Controller (Ethernet) randomly stopped working after they upgraded to Windows 10\. There are still no answers from Microsoft or Realtek as to why would this happen, and this situation happens randomly on different occasions, so there are a lot of solutions that could be of help.

 If this is the problem you are experiencing now, please follow the instructions below to get it fixed by yourself.

[**Option One: Reset TCP/IP**](https://natural-cycles.sjv.io/vmebmr)
[**Option Two: Change Settings in Network Adapter Properties**](https://aofit.pxf.io/mmjyxq)
[**Option Three: Reinstall Realtek Adapter Driver**](https://westkiss.pxf.io/daqnaq)
[**Option Four: Update the Realtek Driver**](https://newchic.sjv.io/jzg4zq)

---

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
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

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
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

---

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Option Three:** **Reinstall or Rollback Realtek Adapter Driver**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand the category**Network adapters** .

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

 Hit**OK** to continue.
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)

 4) Go to the menu bar on the top and click the button for **Scan for hardware changes** .  
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee9a707c2.png)

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
<li><a href="https://instagram-video-files.techidaily.com/new-building-brands-and-bonds-on-instagram-steps-to-reach-a-thousand-followers/"><u>[New] Building Brands and Bonds on Instagram  Steps to Reach a Thousand Followers</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-how-to-create-facebook-video-ads-with-free-video-creation-kit-in-2024/"><u>[New] How to Create Facebook Video Ads with FREE Video Creation Kit, In 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/outube-for-filmmakers-revolutionizing-visual-storytelling-for-2024/"><u>[New] Youtube for Filmmakers  Revolutionizing Visual Storytelling for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-jest-journal-chronicles-of-timely-laughter/"><u>[Updated] Jest Journal  Chronicles of Timely Laughter</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-onscreen-excellence-flexible-talent-access/"><u>2024 Approved  Onscreen Excellence  Flexible Talent Access</u></a></li>
<li><a href="https://android-unlock.techidaily.com/5-solutions-for-vivo-y100i-unlock-without-password-by-drfone-android/"><u>5 Solutions For Vivo Y100i Unlock Without Password</u></a></li>
<li><a href="https://driver-error.techidaily.com/comprehensive-fixes-for-installation-warnings-validating-drivers-on-your-pc/"><u>Comprehensive Fixes for Installation Warnings: Validating Drivers on Your PC</u></a></li>
<li><a href="https://driver-error.techidaily.com/critical-issue-ideport0-control-glitch/"><u>Critical Issue: Ideport0 Control Glitch</u></a></li>
<li><a href="https://driver-error.techidaily.com/direct-android-bridge-to-your-windows-device-samsung/"><u>Direct Android Bridge to Your Windows Device (Samsung)</u></a></li>
<li><a href="https://driver-error.techidaily.com/easy-steps-to-repair-non-functional-laptoppc-keyboards-article-name-358-characters/"><u>Easy Steps to Repair Non-Functional Laptop/PC Keyboards - Article Name — 358 Characters</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/from-plot-to-post-a-detailed-guide-to-writing-youtube-videos-for-2024/"><u>From Plot to Post  A Detailed Guide to Writing YouTube Videos for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/guide-to-overcome-blue-screen-of-death-issue-error-code-0x0000007e-on-win7/"><u>Guide to Overcome Blue Screen of Death Issue (Error Code: 0X0000007E) on Win7</u></a></li>
<li><a href="https://driver-error.techidaily.com/healed-touchpad-drive-6-fixes-for-a-smooth-experience/"><u>Healed Touchpad Drive - 6 Fixes for a Smooth Experience</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-reveal-missing-seagate-disk-on-windows/"><u>How to Reveal Missing Seagate Disk on Windows</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-honor-100-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Honor 100 phone? | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/improve-system-with-newly-updated-death-driver-for-win11/"><u>Improve System with Newly Updated DeaTH Driver for WIN11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-full-guide-on-mirroring-your-samsung-galaxy-a14-4g-to-your-pcmac-drfone-by-drfone-android/"><u>In 2024, Full Guide on Mirroring Your Samsung Galaxy A14 4G to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-which-pokemon-can-evolve-with-a-moon-stone-for-xiaomi-13-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, Which Pokémon can Evolve with a Moon Stone For Xiaomi 13 Ultra? | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/missing-driver-detection-issue/"><u>Missing Driver Detection Issue</u></a></li>
<li><a href="https://driver-error.techidaily.com/restoring-functional-status-of-realtek-usb-networks/"><u>Restoring Functional Status of Realtek USB Networks</u></a></li>
<li><a href="https://driver-error.techidaily.com/successfully-pairing-your-iphone-with-pcmac-using-revamped-usb-drivers/"><u>Successfully Pairing Your iPhone with PC/Mac Using Revamped USB Drivers</u></a></li>
<li><a href="https://driver-error.techidaily.com/the-aa-personalitynationalitycounty-lgbtqv-25-for-yout-database-thatdeeds-30-mildly-happy-to-find-the-gender/"><u>The A/A Personality_nationalityCounty LGBTQv 25%% for Yout Database That'deed''s] ==#30 Mildly Happy-To Find the Gender</u></a></li>
<li><a href="https://driver-error.techidaily.com/touchpads-silent-struggle-ends-driver-fixed/"><u>Touchpad's Silent Struggle Ends - Driver Fixed!</u></a></li>
<li><a href="https://driver-error.techidaily.com/transform-your-gaming-experience-razer-driver-updates-for-win10-users/"><u>Transform Your Gaming Experience: Razer Driver Updates for Win10 Users</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-absent-cddvd-readers/"><u>Troubleshooting Absent CD/DVD Readers</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-windows-10-elan-pad-malfunctions/"><u>Troubleshooting Windows 10 Elan Pad Malfunctions</u></a></li>
<li><a href="https://driver-error.techidaily.com/unleashing-efficiency-end-stutter-issues/"><u>Unleashing Efficiency: End Stutter Issues</u></a></li>
<li><a href="https://driver-error.techidaily.com/unraveling-the-mystery-behind-nvidia-crashes/"><u>Unraveling the Mystery Behind Nvidia Crashes</u></a></li>
<li><a href="https://driver-error.techidaily.com/usb-microphonespeaker-troubleshooting-for-win10-users/"><u>USB Microphone/Speaker Troubleshooting for WIN10 Users</u></a></li>
</ul></div>
