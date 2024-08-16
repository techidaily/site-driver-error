---
title: Solving Post-Update Issues with Realtek LAN Controls
date: 2024-08-15T06:47:10.316Z
updated: 2024-08-16T06:47:10.316Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Solving Post-Update Issues with Realtek LAN Controls
excerpt: This Article Describes Solving Post-Update Issues with Realtek LAN Controls
thumbnail: https://thmb.techidaily.com/edd57a156bbf7df4d7711f42029b2540d33e03363e3c55cf994eda041a9cd465.jpg
---

## Solving Post-Update Issues with Realtek LAN Controls

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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
3) Then right-click Realtek PCIe GBE Family Controller option and choose **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de65b229a9.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->

 4) Go to**Advanced** tab, then choose**Speed & Duplex** option on the left side of the pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de6ed4d026.png)

 5) On the**Value** bar, change the default Auto Negotiation to **100 Mbps Full Duplex**  or some other options accordingly. We chose**100 Mbps Full Duplex** here, but yours could be different.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deb007e7e1.png)
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 6) Now on the left side of the pane, choose**Energy Efficient Ethernet** option, then change the Value to**Disabled** . After the changes, hit**OK** to save.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deab52d9e0.png)
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 7) Still, in the**Properties** window, this time, let’s go to**Power Management** tab. Un-tick the box for**Allow the computer to turn off this device to save power** . Then hit**OK** to save and exit.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587decc3276b5.png)

---

### **Option Three:** **Reinstall or Rollback Realtek Adapter Driver**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 2) Locate and click the arrow to expand the category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Hit**OK** to continue.
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
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
<li><a href="https://driver-error.techidaily.com/fix-high-res-audio-on-win11-system/"><u>[Fix] High-Res Audio on Win11 System</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixed-initial-boot-failure-from-drivers-not-installed/"><u>[FIXED] Initial Boot Failure From Drivers Not Installed</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixed-responsive-keys-restored-to-windows-11/"><u>[Fixed]: Responsive Keys Restored to Windows 11</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-how-to-find-my-playlist-on-youtube/"><u>[New] 2024 Approved  How to Find My Playlist on YouTube</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-lgs-smart-tv-leap-discovering-the-bp550-update/"><u>[New] LG's Smart TV Leap  Discovering the BP550 Update</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-ranking-the-leading-10-pixels-for-free-access/"><u>[New] Ranking the Leading 10 Pixels for Free Access</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-capturing-moments-dslr-setup-for-online-streaming-pcmac-for-2024/"><u>[Updated] Capturing Moments  DSLR Setup for Online Streaming (PC/Mac) for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-deciphering-the-maximum-duration-for-instagram-videos-for-2024/"><u>[Updated] Deciphering the Maximum Duration for Instagram Videos for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-efficient-content-curation-steps-towards-a-well-organized-watch-later-playlist-for-2024/"><u>[Updated] Efficient Content Curation  Steps Towards a Well-Organized 'Watch Later' Playlist for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-web-integration-adding-youtube-playlists-easily/"><u>[Updated] Web Integration  Adding YouTube Playlists Easily</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-the-art-of-audio-finesse-advanced-editing-strategies-for-podcasters/"><u>2024 Approved  The Art of Audio Finesse  Advanced Editing Strategies for Podcasters</u></a></li>
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-realme-12-5g-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>4 Methods to Turn off Life 360 On Realme 12 5G without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://facebook.techidaily.com/breaking-stereotypes-the-rise-and-role-of-metamates-at-facebook/"><u>Breaking Stereotypes: The Rise and Role of Metamates at Facebook</u></a></li>
<li><a href="https://fox-info.techidaily.com/cinematicwave-win8-software-for-2024/"><u>CinematicWave Win8 Software for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/code-1-troubleshooting-steps-for-configuring-devices-correctly/"><u>Code 1 Troubleshooting: Steps for Configuring Devices Correctly</u></a></li>
<li><a href="https://driver-error.techidaily.com/correct-dell-laptops-ethernet-anomaly/"><u>Correct Dell Laptop's Ethernet Anomaly</u></a></li>
<li><a href="https://driver-error.techidaily.com/direct-correction-methods-for-usb-mtp-errors/"><u>Direct Correction Methods for USB MTP Errors</u></a></li>
<li><a href="https://driver-error.techidaily.com/easy-solutions-when-confronted-with-failed-hcmonservice-installs/"><u>Easy Solutions When Confronted with Failed Hcmonservice Installs</u></a></li>
<li><a href="https://some-techniques.techidaily.com/evasive-techniques-for-anonymous-instagram-broadcasting-for-2024/"><u>Evasive Techniques for Anonymous Instagram Broadcasting for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/expert-advice-diagnosing-and-correcting-error-0x0000007e-bsod-issue-on-windows-7-systems/"><u>Expert Advice: Diagnosing and Correcting Error 0X0000007E BSOD Issue on Windows 7 Systems</u></a></li>
<li><a href="https://driver-error.techidaily.com/firmware-blocks-car-loading/"><u>Firmware Blocks Car Loading</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-the-error-when-windows-fails-to-acknowledge-new-usb-device-connections/"><u>Fixing the Error When Windows Fails to Acknowledge New USB Device Connections</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-the-gtx-ebx-950-code-43-issue-in-windows-11-a-comprehensive-guide/"><u>Fixing the GTX Ebx 950 'Code 43' Issue in Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/gtx-950-malfunctioning-with-code-43-heres-the-complete-solution-for-windows-10-users/"><u>GTX 950 Malfunctioning with Code 43? Here's the Complete Solution for Windows 10 Users</u></a></li>
<li><a href="https://some-techniques.techidaily.com/harmony-in-transition-crafting-crossfade-effects-for-2024/"><u>Harmony in Transition  Crafting Crossfade Effects for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-boot-into-safe-mode-and-efficiently-uninstall-graphics-driver-on-windows-8/"><u>How To Boot Into Safe Mode & Efficiently Uninstall Graphics Driver On Windows 8</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-fix-failed-to-install-the-hcmon-driver-error/"><u>How to Fix Failed to Install the Hcmon Driver Error</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-get-your-qualcomm-atheros-bluetooth-driver-up-and-running-on-windows-10/"><u>How to Get Your Qualcomm Atheros Bluetooth Driver Up and Running on Windows 10</u></a></li>
<li><a href="https://some-techniques.techidaily.com/iconic-14-examples-of-animate-texts-for-2024/"><u>Iconic 14 Examples of Animate Texts for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-8-safe-and-effective-methods-to-unlock-your-iphone-se-2020-without-a-passcode-by-drfone-ios/"><u>In 2024, 8 Safe and Effective Methods to Unlock Your iPhone SE (2020) Without a Passcode</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-mastering-reddit-a-step-by-step-guide-for-effective-posts/"><u>In 2024, Mastering Reddit  A Step-By-Step Guide for Effective Posts</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-why-is-ipogo-not-working-on-samsung-galaxy-a24-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, Why is iPogo not working On Samsung Galaxy A24? Fixed | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-apple-iphone-se-2020-drfone-by-drfone-virtual-ios/"><u>In 2024, Why Your WhatsApp Live Location is Not Updating and How to Fix on your Apple iPhone SE (2020) | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/insufficient-resources-on-system/"><u>Insufficient Resources on System</u></a></li>
<li><a href="https://driver-error.techidaily.com/keyboard-issue-solved-functional-on-windows-11/"><u>Keyboard Issue Solved: Functional on Windows 11</u></a></li>
<li><a href="https://driver-error.techidaily.com/mastering-bluetooth-shutdown-on-windows-10/"><u>Mastering Bluetooth Shutdown on Windows 10</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-behind-the-scenes-sound-management-expert-insights-into-using-ducking-effects/"><u>New 2024 Approved Behind-the-Scenes Sound Management Expert Insights Into Using Ducking Effects</u></a></li>
<li><a href="https://driver-error.techidaily.com/nonresponsive-or-stuck-pclaptop-key-issue-here-is-a-simple-fix-for-your-beloved-machine-article-title-how-to-guide-tech-talker402-chars/"><u>Nonresponsive or Stuck PC/Laptop Key Issue? Here Is a Simple Fix for Your Beloved Machine (Article Title) – How-To Guide | Tech Talker—402 Chars</u></a></li>
<li><a href="https://driver-error.techidaily.com/overcome-hot-plugging-shortfall/"><u>Overcome Hot-Plugging Shortfall</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-iphone-se-2022-data-from-itunes-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover iPhone SE (2022) Data From iTunes | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/reduced-lag-increased-speed-in-win11/"><u>Reduced Lag, Increased Speed in Win11</u></a></li>
<li><a href="https://driver-error.techidaily.com/reinstating-operational-right-click-on-windows-11-touchpad/"><u>Reinstating Operational Right Click on Windows 11 Touchpad</u></a></li>
<li><a href="https://driver-error.techidaily.com/solution-guide-fixing-the-driver-load-error-for-battleye-service-initiation-problem-error-1450/"><u>Solution Guide: Fixing the Driver Load Error for BattlEye Service Initiation Problem (Error 1450)</u></a></li>
<li><a href="https://techidaily.com/solved-mac-doesnt-recognize-my-iphone-14-pro-max-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Solved Mac Doesnt Recognize my iPhone 14 Pro Max | Stellar</u></a></li>
<li><a href="https://driver-error.techidaily.com/swift-strategies-to-overcome-directx-9-fail/"><u>Swift Strategies to Overcome 'DirectX 9 Fail'</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-ultimate-guide-to-understanding-ai-language-decode-29-crucial-terms/"><u>The Ultimate Guide to Understanding AI Language: Decode 29 Crucial Terms</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-valorants-input-delay-for-optimal-pc-gaming-experience-updated-2024/"><u>Troubleshooting Valorant's Input Delay for Optimal PC Gaming Experience (Updated: 2024)</u></a></li>
<li><a href="https://driver-error.techidaily.com/unsupported-device-error-solutions-for-incompatible-hardware-in-your-idt-software/"><u>Unsupported Device Error: Solutions for Incompatible Hardware in Your IDT Software</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-87-fails-to-show-nvidia-gpus/"><u>Windows 8/7 Fails to Show Nvidia GPUs</u></a></li>
<li><a href="https://driver-error.techidaily.com/windows-wireless-keyboard-issues-solve-common-connection-problems-now/"><u>Windows Wireless Keyboard Issues? Solve Common Connection Problems Now!</u></a></li>
</ul></div>
