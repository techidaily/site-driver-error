---
title: Solved Ethernet Control Failure on Windows 10
date: 2024-10-07T16:25:02.642Z
updated: 2024-10-12T16:28:58.803Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Solved Ethernet Control Failure on Windows 10
excerpt: This Article Describes Solved Ethernet Control Failure on Windows 10
thumbnail: https://thmb.techidaily.com/5565177be356d6fd1f6d2b58dc2046c46dae913812fa6d796b06a5e79fd2f303.jpg
---

## Solved Ethernet Control Failure on Windows 10

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

### **Option Two:** **Change Settings in Network Adapter Properties**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
3) Then right-click Realtek PCIe GBE Family Controller option and choose **Properties** .

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098702/14409" target="_top" id="2098702">
  <img src="//a.impactradius-go.com/display-ad/14409-2098702" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098702/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de65b229a9.png)

 4) Go to**Advanced** tab, then choose**Speed & Duplex** option on the left side of the pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de6ed4d026.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094482/7443" target="_top" id="2094482">
  <img src="//a.impactradius-go.com/display-ad/7443-2094482" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 5) On the**Value** bar, change the default Auto Negotiation to **100 Mbps Full Duplex**  or some other options accordingly. We chose**100 Mbps Full Duplex** here, but yours could be different.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deb007e7e1.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037318/7443" target="_top" id="2037318">
  <img src="//a.impactradius-go.com/display-ad/7443-2037318" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037318/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 6) Now on the left side of the pane, choose**Energy Efficient Ethernet** option, then change the Value to**Disabled** . After the changes, hit**OK** to save.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deab52d9e0.png)

<!-- affiliate ads begin -->
<span id="1516072">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1516072.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1516072">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1516072.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1516072%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1516072/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 7) Still, in the**Properties** window, this time, let’s go to**Power Management** tab. Un-tick the box for**Allow the computer to turn off this device to save power** . Then hit**OK** to save and exit.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587decc3276b5.png)

---

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036486/19272" target="_top" id="2036486">
  <img src="//a.impactradius-go.com/display-ad/19272-2036486" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036486/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### **Option Three:** **Reinstall or Rollback Realtek Adapter Driver**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand the category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

 Hit**OK** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)

 4) Go to the menu bar on the top and click the button for **Scan for hardware changes** .  
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee9a707c2.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043639/7443" target="_top" id="2043639">
  <img src="//a.impactradius-go.com/display-ad/7443-2043639" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043639/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-classic-rogelikes-vs-roguelites-dynamics/"><u>[New] In 2024, Classic Rogelikes Vs. Roguelites' Dynamics</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-strategic-lighting-for-best-iphone-photography/"><u>[New] Strategic Lighting for Best iPhone Photography</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-film-for-a-friendly-facebook-feature-for-2024/"><u>[Updated] Film for a Friendly Facebook Feature for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-the-angle-advantage-guide-mastering-the-art-of-spinning-photos-for-social-media-triumphs-for-2024/"><u>[Updated] The Angle Advantage Guide Mastering the Art of Spinning Photos for Social Media Triumphs for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-fix-disruption-chromium-and-tweeted-videos/"><u>2024 Approved Fix Disruption Chromium and Tweeted Videos</u></a></li>
<li><a href="https://tech-revival.techidaily.com/download-the-latest-ai-experience-free-gpt-4-all-version-of-chatbot-on-your-windows-machine/"><u>Download the Latest AI: Experience Free GPT-4 All Version of Chatbot on Your Windows Machine</u></a></li>
<li><a href="https://driver-error.techidaily.com/dvd-reader-disappearance-issue-solved-in-win11/"><u>DVD Reader Disappearance Issue Solved in Win11</u></a></li>
<li><a href="https://driver-error.techidaily.com/end-of-window-lags-and-pauses/"><u>End of Window Lags & Pauses</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/everything-you-need-to-know-about-unlocked-apple-iphone-xs-drfone-by-drfone-ios/"><u>Everything You Need To Know About Unlocked Apple iPhone XS | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-lava-yuva-2-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location without Jailbreak On Lava Yuva 2 | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/idt-software-update-solving-unrecognized-device-issues-effectively/"><u>IDT Software Update: Solving Unrecognized Device Issues Effectively</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-the-art-of-accompaniment-crafting-a-harmonious-blend-between-video-and-music-for-2024/"><u>New The Art of Accompaniment Crafting a Harmonious Blend Between Video and Music for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/overhauling-intel-mmc-faults/"><u>Overhauling Intel MMC Faults</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolved-no-support-for-amdintel-in-premier-pro-videos/"><u>Resolved: No Support for AMD/Intel in Premier Pro Videos</u></a></li>
<li><a href="https://data-wizards.techidaily.com/restoring-ravaged-media-files-the-sample-approach/"><u>Restoring Ravaged Media Files: The Sample Approach</u></a></li>
<li><a href="https://driver-error.techidaily.com/solving-seagate-hdd-visibility-issue-in-win11/"><u>Solving Seagate HDD Visibility Issue in Win11</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-guide-booting-windows-8-into-safe-mode-and-removing-your-graphics-drivers/"><u>Step-by-Step Guide: Booting Windows 8 Into Safe Mode & Removing Your Graphics Drivers</u></a></li>
<li><a href="https://driver-error.techidaily.com/the-evolution-and-functionality-of-usb-composite-devices-a-comprehensive-guide/"><u>The Evolution and Functionality of USB Composite Devices: A Comprehensive Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-hardware-recognition-complete/"><u>Windows Hardware Recognition Complete</u></a></li>
</ul></div>

