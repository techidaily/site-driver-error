---
title: Realtek Ethernet Controller Driver Not Working After Windows 10 Upgrade [Solved]
date: 2024-09-04T12:51:27.777Z
updated: 2024-09-05T12:51:27.777Z
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

---

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886073/19272" target="_top" id="1886073">
  <img src="//a.impactradius-go.com/display-ad/19272-1886073" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886073/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Option Three:** **Reinstall or Rollback Realtek Adapter Driver**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand the category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087390/7443" target="_top" id="2087390">
  <img src="//a.impactradius-go.com/display-ad/7443-2087390" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087390/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Hit**OK** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)

 4) Go to the menu bar on the top and click the button for **Scan for hardware changes** .  
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee9a707c2.png)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1001453/11832" target="_top" id="1001453">
  <img src="//a.impactradius-go.com/display-ad/11832-1001453" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1001453/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 5) Windows will help you automatically install the correct driver that it can find. But there is no guarantee that the new driver is going to work since Windows has provided the not working one originally.

 If you clearly remember that your Ethernet stops working after you update to a certain version of the driver, it is suggested that you roll it back to the stage where it was working well.

---

<!-- affiliate ads begin -->
<span id="1982596">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982596.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982596">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982596.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982596%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982596/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Option Four: Update the Realtek Driver**

 The steps above may help you resolve the issue, but if they don’t, you can try to update the Realtek driver. If you don’t have time, patience, or computer skills to update the driver manually,  you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/) .**

**IMPORTANT:**  If you can’t have access to the internet due to the network driver issues, you can use **[Driver Easy Offline Scan Feature](https://tools.techidaily.com/drivereasy/download/)**  to download and install a new network driver.

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version, it takes just 2 clicks (and you get full support and a 30-day money-back guarantee):

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2023/03/Driver-Easy-download-needed-1200x900.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043618/7443" target="_top" id="2043618">
  <img src="//a.impactradius-go.com/display-ad/7443-2043618" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043618/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) Click the **Update** button next to the Realtek PCIe driver to automatically download the correct version of this driver, then you can manually install it (you can do this with the FREE version).

 Or click **Update All**  to automatically download and install the correct version of _all_   the drivers that are missing or out of date on your system (this requires the Pro version – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2020/11/update-network-adapter-driver.jpg)

<!-- affiliate ads begin -->
<span id="1977020">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977020.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977020">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977020.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977020%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977020/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://driver-error.techidaily.com/alert-intermittent-mouse-functionality-in-window-10/"><u>[Alert]: Intermittent Mouse Functionality in Window 10</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-from-recordings-to-live-an-obs-guide-to-youtube-and-twitch-streaming/"><u>[New] 2024 Approved  From Recordings to Live  An OBS Guide to YouTube and Twitch Streaming</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-how-to-record-screen-with-ultra-screen-recorder/"><u>[New] 2024 Approved  How to Record Screen With Ultra Screen Recorder</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-2024-approved-the-sound-solution-for-twitters-video-content/"><u>[New] 2024 Approved  The Sound Solution for Twitter's Video Content</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-a-quick-dive-into-video-ratios-the-aspect-ratio-essentials-for-youtubers/"><u>[New] In 2024, A Quick Dive Into Video Ratios  The Aspect Ratio Essentials for YouTubers</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-instant-live-from-obs-to-instagram-app/"><u>[New] Instant Live  From OBS to Instagram App</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-in-depth-analysis-applying-luts-to-elevate-your-cinematography/"><u>2024 Approved  In-Depth Analysis  Applying LUTs to Elevate Your Cinematography</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/additional-tips-about-sinnoh-stone-for-tecno-spark-go-2023-drfone-by-drfone-virtual-android/"><u>Additional Tips About Sinnoh Stone For Tecno Spark Go (2023) | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/address-erratic-dell-pointing-device-win7/"><u>Address Erratic Dell Pointing Device (Win7)</u></a></li>
<li><a href="https://driver-error.techidaily.com/addressing-and-fixing-windows-11s-critical-missing-cpu-coprocessor-driver-dilemma/"><u>Addressing and Fixing Windows 11'S Critical Missing CPU Coprocessor Driver Dilemma</u></a></li>
<li><a href="https://driver-error.techidaily.com/addressing-faulty-inf-service-setup-section/"><u>Addressing Faulty INF Service Setup Section</u></a></li>
<li><a href="https://driver-error.techidaily.com/addressing-nonoperational-realtek-controllers-post-upgrade/"><u>Addressing Nonoperational Realtek Controllers Post-Upgrade</u></a></li>
<li><a href="https://driver-error.techidaily.com/armored-fixed-asus-usb-webcam-link-with-win11-os/"><u>Armored Fixed ASUS USB-Webcam Link with Win11 OS</u></a></li>
<li><a href="https://extra-hints.techidaily.com/assessing-the-value-of-digital-image-anchor-points-for-2024/"><u>Assessing the Value of Digital Image Anchor Points for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/best-3d-animation-software-free-trials-and-paid-versions/"><u>Best 3D Animation Software Free Trials and Paid Versions</u></a></li>
<li><a href="https://driver-error.techidaily.com/bluetooth-not-working-on-windows-11-solved/"><u>Bluetooth Not Working on Windows 11 [Solved]</u></a></li>
<li><a href="https://driver-error.techidaily.com/bluetooth-simplified-windows-problems-addressed-quickly/"><u>Bluetooth Simplified: Windows Problems Addressed Quickly</u></a></li>
<li><a href="https://driver-error.techidaily.com/bring-back-functionality-fix-a-missing-touchpad-driver/"><u>Bring Back Functionality: Fix a Missing Touchpad Driver</u></a></li>
<li><a href="https://driver-error.techidaily.com/complete-solution-for-driver-issues-on-devices-running-windows-10-8-or-7-install-now/"><u>Complete Solution for Driver Issues on Devices Running Windows 10, 8 or 7 – Install Now!</u></a></li>
<li><a href="https://driver-error.techidaily.com/comprehensive-fix-for-hcmon-driver-error-during-setup-process/"><u>Comprehensive Fix for HCMON Driver Error During Setup Process</u></a></li>
<li><a href="https://driver-error.techidaily.com/comprehensive-guide-to-older-versions-of-usb-composite-devices/"><u>Comprehensive Guide to Older Versions of USB Composite Devices</u></a></li>
<li><a href="https://driver-error.techidaily.com/comprehensive-troubleshooting-tips-getting-your-wireless-keyboard-back-online-in-windows-environment/"><u>Comprehensive Troubleshooting Tips: Getting Your Wireless Keyboard Back Online in Windows Environment</u></a></li>
<li><a href="https://driver-error.techidaily.com/configuring-your-device-right-a-comprehensive-approach-to-solve-the-code-1-error-message/"><u>Configuring Your Device Right: A Comprehensive Approach to Solve the 'Code 1' Error Message</u></a></li>
<li><a href="https://driver-error.techidaily.com/connectivity-problem-missing-drivers-on-pc/"><u>Connectivity Problem: Missing Drivers on PC</u></a></li>
<li><a href="https://driver-error.techidaily.com/correcting-unsupported-usb-errors-in-win-78-environment/"><u>Correcting Unsupported USB Errors in Win 7/8 Environment</u></a></li>
<li><a href="https://driver-error.techidaily.com/cracking-the-code-on-usb-cannot-be-installed-access-is-denied-expert-solutions-for-windows-users/"><u>Cracking the Code on 'USB Cannot Be Installed, Access Is Denied': Expert Solutions for Windows Users</u></a></li>
<li><a href="https://driver-error.techidaily.com/dealing-with-iphones-and-mtp-driver-woes-master-these-troubleshooting-tips/"><u>Dealing With iPhones and MTP Driver Woes? Master These Troubleshooting Tips</u></a></li>
<li><a href="https://driver-error.techidaily.com/decoding-bda-graphics-through-visual-rendering/"><u>Decoding BDA Graphics Through Visual Rendering</u></a></li>
<li><a href="https://driver-error.techidaily.com/device-back-in-service/"><u>Device Back in Service</u></a></li>
<li><a href="https://driver-error.techidaily.com/device-driver-loaded-on-win-os/"><u>Device Driver Loaded on Win OS</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-exit-android-factory-mode-on-honor-x50i-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Exit Android Factory Mode On Honor X50i? | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-fix-pokemon-go-route-not-working-on-realme-note-50-drfone-by-drfone-virtual-android/"><u>How to Fix Pokemon Go Route Not Working On Realme Note 50? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-remove-a-previously-synced-google-account-from-your-realme-11-5g-by-drfone-android/"><u>How to Remove a Previously Synced Google Account from Your Realme 11 5G</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721102202054-htc-desire-z-not-detected-on-fedora-core-linux-problem-solved/"><u>HTC Desire Z Not Detected on Fedora Core Linux, Problem Solved</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-a-deep-dive-into-exceptional-screen-recording-using-adobe-captivity/"><u>In 2024, A Deep Dive Into Exceptional Screen Recording Using Adobe Captivity</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/inside-camstudios-updated-screen-recorder-techniques-for-2024/"><u>Inside CamStudio's Updated Screen Recorder Techniques for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721103877616-iphone-cant-connect-correct-your-phones-mtp-drivers-today/"><u>IPhone Can't Connect? Correct Your Phone's MTP Drivers Today</u></a></li>
<li><a href="https://facebook.techidaily.com/keeping-it-covert-a-step-by-step-guide-to-private-content-retrieval/"><u>Keeping It Covert: A Step-by-Step Guide to Private Content Retrieval</u></a></li>
<li><a href="https://some-approaches.techidaily.com/leading-tech-for-cloud-saving-top-choices-for-android-for-2024/"><u>Leading Tech for Cloud Saving  Top Choices for Android for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-the-ultimate-ranking-8-best-ios-compatible-daws-for-ipad-and-iphone-enthusiasts/"><u>New 2024 Approved The Ultimate Ranking 8 Best iOS-Compatible DAWs for iPad and iPhone Enthusiasts</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721101631137-no-more-loneliness-for-wacom-connected/"><u>No More Loneliness for Wacom, Connected</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/snappy-sharing-uploading-and-publishing-short-videos-online/"><u>Snappy Sharing  Uploading and Publishing Short Videos Online</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721101503379-solved-no-valid-dx11-video-card-found-black-ops-error/"><u>Solved: No Valid DX11 Video Card Found Black Ops Ⅲ Error</u></a></li>
<li><a href="https://android-frp.techidaily.com/the-updated-method-to-bypass-motorola-moto-g-stylus-5g-2023-frp-by-drfone-android/"><u>The Updated Method to Bypass Motorola Moto G Stylus 5G (2023) FRP</u></a></li>
</ul></div>
