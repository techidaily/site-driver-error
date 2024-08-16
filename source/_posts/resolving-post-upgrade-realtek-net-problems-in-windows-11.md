---
title: Resolving Post-Upgrade Realtek Net Problems in Windows 11
date: 2024-08-15T06:46:04.528Z
updated: 2024-08-16T06:46:04.528Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Resolving Post-Upgrade Realtek Net Problems in Windows 11
excerpt: This Article Describes Resolving Post-Upgrade Realtek Net Problems in Windows 11
thumbnail: https://thmb.techidaily.com/89da36f12af5e5ecabd872d074753c94f1e0591c9264a3deac22fa09078e3cf8.jpg
---

## Resolving Post-Upgrade Realtek Net Problems in Windows 11

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
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Option Two:** **Change Settings in Network Adapter Properties**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
3) Then right-click Realtek PCIe GBE Family Controller option and choose **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de65b229a9.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->

 4) Go to**Advanced** tab, then choose**Speed & Duplex** option on the left side of the pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de6ed4d026.png)

 5) On the**Value** bar, change the default Auto Negotiation to **100 Mbps Full Duplex**  or some other options accordingly. We chose**100 Mbps Full Duplex** here, but yours could be different.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deb007e7e1.png)

 6) Now on the left side of the pane, choose**Energy Efficient Ethernet** option, then change the Value to**Disabled** . After the changes, hit**OK** to save.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deab52d9e0.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->

 7) Still, in the**Properties** window, this time, let’s go to**Power Management** tab. Un-tick the box for**Allow the computer to turn off this device to save power** . Then hit**OK** to save and exit.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587decc3276b5.png)

---

### **Option Three:** **Reinstall or Rollback Realtek Adapter Driver**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
 2) Locate and click the arrow to expand the category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

 Hit**OK** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)

 4) Go to the menu bar on the top and click the button for **Scan for hardware changes** .  
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee9a707c2.png)
<!-- affiliate ads begin -->
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
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
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
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
<li><a href="https://driver-error.techidaily.com/irqlfixed-win11-os-blue-screen-issue/"><u>[IRQL_FIXED]: Win11 OS Blue Screen Issue</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-achieve-peak-performance-zooms-6-webcam-picks/"><u>[New] Achieve Peak Performance  Zoom's #6 Webcam Picks</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-leading-spots-for-digital-3d-glamour-text-artistry/"><u>[New] Leading Spots for Digital 3D Glamour Text Artistry</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-navigating-the-riches-of-stardews-ginger-isle-for-2024/"><u>[New] Navigating the Riches of Stardew’s Ginger Isle for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-prime-artistry-summary-intense-pinnacle-studio-review-2023/"><u>[Updated] Prime Artistry Summary  Intense Pinnacle Studio Review 2023</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-revolutionary-guide-to-iphone-x-animoji-mastery/"><u>[Updated] Revolutionary Guide to iPhone X Animoji Mastery</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-exclusive-review-of-top-mp4-players/"><u>2024 Approved  Exclusive Review of Top MP4 Players</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-guidance-download-tamil-music-as-ringtone-and-how-to-cut-a-song-as-ringtone/"><u>2024 Approved  Guidance  Download Tamil Music As Ringtone And How To Cut A Song As Ringtone</u></a></li>
<li><a href="https://driver-error.techidaily.com/a-excuse-me-if-you-guys-but-i-am-a-human-resources-manager-are-all-of-the-same-time-periods/"><u>A: Excuse Me if You Guys, but I Am a Human Resources Manager) Are All of the Same Time Periods</u></a></li>
<li><a href="https://driver-error.techidaily.com/addressing-windows-non-responsive-enter-issue/"><u>Addressing Windows Non-Responsive Enter Issue</u></a></li>
<li><a href="https://extra-information.techidaily.com/crafting-a-perfect-power-pair-lipo-and-drones/"><u>Crafting a Perfect Power Pair  LiPo and Drones</u></a></li>
<li><a href="https://driver-error.techidaily.com/demystifying-the-functionality-of-outdated-usb-composite-devices-and-how-to-fix-them/"><u>Demystifying the Functionality of Outdated USB Composite Devices and How to Fix Them</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/directly-syncing-your-tiktok-videos-with-facebook-for-2024/"><u>Directly Syncing Your TikTok Videos with Facebook for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/enabling-hardware-detection-for-seagate-external/"><u>Enabling Hardware Detection for Seagate External</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/enlightening-the-future-one-language-at-a-time/"><u>Enlightening the Future, One Language at a Time</u></a></li>
<li><a href="https://driver-error.techidaily.com/error-code-48-issue-now-solved/"><u>Error Code 48 - Issue Now Solved</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-incompatibility-alerts-unsupported-hard-devices-on-idt-software-platforms/"><u>Fix Incompatibility Alerts: Unsupported Hard Devices on IDT Software Platforms</u></a></li>
<li><a href="https://driver-error.techidaily.com/graphics-device-hack-rejected-in-win11-system/"><u>Graphics Device Hack Rejected in Win11 System</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-fix-auto-lock-greyed-out-on-iphone-14-drfone-by-drfone-ios/"><u>How To Fix Auto Lock Greyed Out on iPhone 14 | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-xiaomi-redmi-a2plus-phone-with-broken-screen-by-drfone-android/"><u>How to Unlock Xiaomi Redmi A2+ Phone with Broken Screen</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-7-top-ways-to-resolve-apple-id-not-active-issue-for-iphone-6-drfone-by-drfone-ios/"><u>In 2024, 7 Top Ways To Resolve Apple ID Not Active Issue For iPhone 6 | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-itel-p55-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Itel P55 | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-expert-techniques-to-masterboard-use-during-remote-collaborations-across-various-operating-systems/"><u>In 2024, Expert Techniques to Masterboard Use During Remote Collaborations Across Various Operating Systems</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-change-credit-card-from-your-iphone-11-pro-max-apple-id-and-apple-pay-by-drfone-ios/"><u>In 2024, How to Change Credit Card from Your iPhone 11 Pro Max Apple ID and Apple Pay</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-iphone-8-3-ways-to-unlock-by-drfone-ios/"><u>In 2024, How To Unlock iPhone 8 3 Ways To Unlock</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-light-up-the-screen-tips-and-steps-for-adding-gifs-to-snapchats/"><u>In 2024, Light Up the Screen  Tips and Steps for Adding GIFs to Snapchats</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-the-true-story-of-youtube-earnings-and-viewer-volume-requirements/"><u>In 2024, The True Story of YouTube Earnings and Viewer Volume Requirements</u></a></li>
<li><a href="https://driver-error.techidaily.com/key-backlight-off-on-asus-device/"><u>Key Backlight OFF on ASUS Device</u></a></li>
<li><a href="https://driver-error.techidaily.com/lenovo-t460-drivers-download-and-update-on-windows-10/"><u>Lenovo T460 Drivers Download & Update on Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/lenovos-blue-tooth-troubles-win11-remedied-strategies/"><u>Lenovo's Blue-Tooth Troubles, Win11 Remedied Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-shortcuts-for-microsoft-store-uwp/"><u>Mastering Windows Shortcuts for Microsoft Store UWP</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-giants-of-social-networking-fb-twtr-ig-and-yt/"><u>Navigating the Giants of Social Networking: FB, TWTR, IG, and YT</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-how-to-edit-videos-like-a-pro-an-online-guide-to-downloading-and-post-production/"><u>New How to Edit Videos Like a Pro An Online Guide to Downloading and Post-Production</u></a></li>
<li><a href="https://driver-error.techidaily.com/printer-issue-resolved-with-new-driver-update/"><u>Printer Issue Resolved with New Driver Update</u></a></li>
<li><a href="https://driver-error.techidaily.com/quick-win-strategies-for-windows-ndis-issues/"><u>Quick-Win Strategies for Windows NDIS Issues</u></a></li>
<li><a href="https://driver-error.techidaily.com/reinstating-your-touchpad-driver-recovery-unveiled/"><u>Reinstating Your Touchpad - Driver Recovery Unveiled</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-errors-in-the-configuration-segment-for-services/"><u>Resolving Errors in the Configuration Segment for Services</u></a></li>
<li><a href="https://driver-error.techidaily.com/revitalizing-your-touchpads-performance-no-driver/"><u>Revitalizing Your Touchpad's Performance, No Driver?</u></a></li>
<li><a href="https://extra-support.techidaily.com/smoothly-softening-endings-audio-fades-made-simple-with-adobe-premiere-pro-for-2024/"><u>Smoothly Softening Endings  Audio Fades Made Simple with Adobe Premiere Pro for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/solve-disappearing-optical-drives-on-win11/"><u>Solve Disappearing Optical Drives on Win11</u></a></li>
<li><a href="https://driver-error.techidaily.com/solve-recurring-amd-glitches-rapidly/"><u>Solve Recurring AMD Glitches Rapidly</u></a></li>
<li><a href="https://driver-error.techidaily.com/system-barred-from-using-win10s-graphics-hardware/"><u>System Barred From Using Win10's Graphics Hardware</u></a></li>
<li><a href="https://driver-error.techidaily.com/system-call-issue-with-io-controller-over/"><u>System Call Issue with I/O Controller Over</u></a></li>
<li><a href="https://win-able.techidaily.com/the-ultimate-fix-ensuring-seamless-launches-for-valheim-in-the-latest-update/"><u>The Ultimate Fix: Ensuring Seamless Launches for Valheim in the Latest Update</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshoot-and-fix-missing-intel-cpu-coprocessor-drivers-on-windows-11-easily/"><u>Troubleshoot and Fix Missing Intel CPU Coprocessor Drivers on Windows 11 Easily</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-sideways-videos-a-guide-to-adjusting-orientation-on-asus-pcs/"><u>Troubleshooting Sideways Videos: A Guide to Adjusting Orientation on ASUS PCs</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-the-radeon-wattman-defaults-crash-recovery-expert-solutions/"><u>Troubleshooting the 'Radeon WattMan Defaults Crash Recovery': Expert Solutions</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-tips-for-recovering-from-default-radeon-wattman-setup-errors/"><u>Troubleshooting Tips for Recovering From Default Radeon Wattman Setup Errors</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/understanding-and-adhering-to-twitters-video-standards/"><u>Understanding and Adhering to Twitter's Video Standards</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/unleashing-video-potential-with-effective-tagging-techniques-on-youtube/"><u>Unleashing Video Potential with Effective Tagging Techniques on YouTube</u></a></li>
<li><a href="https://driver-error.techidaily.com/unresponsive-mouse-lurking-in-windows-settings/"><u>Unresponsive Mouse Lurking in Windows Settings</u></a></li>
<li><a href="https://driver-error.techidaily.com/your-pc-graphics-issues-let-us-fix-your-nvidia-rtx-gaming-woes/"><u>Your PC Graphics Issues? Let Us Fix Your Nvidia RTX Gaming Woes!</u></a></li>
</ul></div>
