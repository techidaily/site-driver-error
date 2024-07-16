---
title: Address Realtek LAN Problem Post-Windows 10 Upgrade
date: 2024-07-15T06:55:43.787Z
updated: 2024-07-16T06:55:43.787Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Address Realtek LAN Problem Post-Windows 10 Upgrade
excerpt: This Article Describes Address Realtek LAN Problem Post-Windows 10 Upgrade
thumbnail: https://thmb.techidaily.com/234a90d5c27844c283f4441b2b9e5e76ee9e8064b4a1ba5d5f5c1598b8d0670d.jpg
---

## Address Realtek LAN Problem Post-Windows 10 Upgrade

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

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deb007e7e1.png)

 6) Now on the left side of the pane, choose**Energy Efficient Ethernet** option, then change the Value to**Disabled** . After the changes, hit**OK** to save.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deab52d9e0.png)

 7) Still, in the**Properties** window, this time, let’s go to**Power Management** tab. Un-tick the box for**Allow the computer to turn off this device to save power** . Then hit**OK** to save and exit.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587decc3276b5.png)

---

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Option Three:** **Reinstall or Rollback Realtek Adapter Driver**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand the category**Network adapters** .

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

 Hit**OK** to continue.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://driver-error.techidaily.com/easy-steps-to-repair-non-functional-laptoppc-keyboards-article-name-358-characters/"><u>Easy Steps to Repair Non-Functional Laptop/PC Keyboards - Article Name — 358 Characters</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/digital-cinematographer-hub/"><u>Digital Cinematographer Hub</u></a></li>
<li><a href="https://driver-error.techidaily.com/unresponsive-gaming-due-to-graphics-quick-resolution-guide/"><u>Unresponsive Gaming Due To Graphics – Quick Resolution Guide!</u></a></li>
<li><a href="https://network-issues.techidaily.com/wi-fi-signal-slipping-away/"><u>Wi-Fi Signal Slipping Away</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-free-6-best-youtube-to-mp3-downloader-for-android/"><u>[Updated] In 2024, FREE 6 Best YouTube to MP3 Downloader for Android</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-and-fixing-qualcomm-atheros-bluetooth-drivers-for-optimal-performance-on-windows-n11/"><u>Troubleshooting and Fixing Qualcomm Atheros Bluetooth Drivers for Optimal Performance on Windows N11</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-prevent-nvidia-driver-from-uninstalling-itself/"><u>How to Prevent Nvidia Driver From Uninstalling Itself</u></a></li>
<li><a href="https://games-able.techidaily.com/will-radeon-and-nvidia-costs-escalate-soon/"><u>Will Radeon and Nvidia Costs Escalate Soon?</u></a></li>
<li><a href="https://driver-error.techidaily.com/diagnosing-and-correcting-asus-windows-10-acpi-fails/"><u>Diagnosing & Correcting Asus Windows 10 Acpi Fails</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixed-no-official-support-for-amdintel-drivers-in-premiere-pro-software/"><u>Fixed: No Official Support for AMD/Intel Drivers in Premiere Pro Software</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-propel-your-creativity-mastering-inshot-for-device-edits/"><u>[New] Propel Your Creativity  Mastering Inshot for Device Edits</u></a></li>
<li><a href="https://driver-error.techidaily.com/clarify-device-not-found-on-win98beta/"><u>Clarify 'Device Not Found' On Win98Beta</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-expert-recommended-steadicams-for-drone-videography/"><u>[New] Expert-Recommended Steadicams for Drone Videography</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-absent-cddvd-readers/"><u>Troubleshooting Absent CD/DVD Readers</u></a></li>
<li><a href="https://driver-error.techidaily.com/comprehensive-fixes-for-installation-warnings-validating-drivers-on-your-pc/"><u>Comprehensive Fixes for Installation Warnings: Validating Drivers on Your PC</u></a></li>
<li><a href="https://driver-error.techidaily.com/multi-generation-driver-set-for-pci-cards/"><u>Multi-Generation Driver Set for PCI Cards</u></a></li>
<li><a href="https://driver-error.techidaily.com/graphics-glitch-overcome-seamless-setup/"><u>Graphics Glitch Overcome – Seamless Setup</u></a></li>
<li><a href="https://driver-error.techidaily.com/error-code-45-from-devmgmt-fixed/"><u>Error Code 45 From DevMgmt Fixed</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-ahead-of-the-curve-tiktoks-freshest-acts/"><u>[Updated] In 2024, Ahead of the Curve  TikTok's Freshest Acts</u></a></li>
<li><a href="https://driver-error.techidaily.com/asus-pc-backlight-malfunctioning/"><u>Asus PC Backlight Malfunctioning</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-vivo-y100twithwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Vivo Y100twith/without a PC</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-eye-on-your-instagram-disconnectors/"><u>[Updated] Eye on Your Instagram Disconnectors</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-sizing-up-your-photos-how-to-use-a-ratio-calculator-effectively-for-2024/"><u>New Sizing Up Your Photos How to Use a Ratio Calculator Effectively for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/successfully-pairing-your-iphone-with-pcmac-using-revamped-usb-drivers/"><u>Successfully Pairing Your iPhone with PC/Mac Using Revamped USB Drivers</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-innovative-ways-to-capture-authenticity-in-customer-reviews/"><u>[Updated] Innovative Ways to Capture Authenticity in Customer Reviews</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-overview-fb-video-dimension-categories-for-2024/"><u>[New] Overview  FB Video Dimension Categories for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/bypassing-google-account-with-vnrom-bypass-for-honor-x50i-by-drfone-android/"><u>Bypassing Google Account With vnROM Bypass For Honor X50i</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-pokemon-go-joystick-on-samsung-galaxy-s23-fe-drfone-by-drfone-virtual-android/"><u>How to use Pokemon Go Joystick on Samsung Galaxy S23 FE? | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-reveal-missing-seagate-disk-on-windows/"><u>How to Reveal Missing Seagate Disk on Windows</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-tinyvid-recorder-examination-and-reviews/"><u>In 2024, TinyVid Recorder Examination & Reviews</u></a></li>
<li><a href="https://driver-error.techidaily.com/enhancing-convenience-with-fixed-win11-bluescreen-a-step-by-step-guide-resolved/"><u>Enhancing Convenience with Fixed Win11 Bluescreen - A Step-By-Step Guide [Resolved]</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/in-2024-rotate-your-videos-with-ease-10-free-online-and-offline-solutions/"><u>In 2024, Rotate Your Videos with Ease 10 Free Online and Offline Solutions</u></a></li>
<li><a href="https://driver-error.techidaily.com/device-error-wudfrd-loading-failure-event-id-219/"><u>Device Error: WudfRd Loading Failure (Event ID 219)</u></a></li>
<li><a href="https://driver-error.techidaily.com/the-aa-personalitynationalitycounty-lgbtqv-25-for-yout-database-thatdeeds-30-mildly-happy-to-find-the-gender/"><u>The A/A Personality_nationalityCounty LGBTQv 25%% for Yout Database That'deed''s] ==#30 Mildly Happy-To Find the Gender</u></a></li>
<li><a href="https://driver-error.techidaily.com/missing-driver-detection-issue/"><u>Missing Driver Detection Issue</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/some-facts-about-gif-background-you-didnt-know-for-2024/"><u>Some Facts About GIF Background You Didnt Know for 2024</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-in-2024-registration-and-login/"><u>New In 2024, Registration and Login</u></a></li>
<li><a href="https://driver-error.techidaily.com/wi-fi-6ax201-not-operating-fixed-connectivity-issues/"><u>Wi-Fi 6Ax201 Not Operating - Fixed Connectivity Issues</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721102108469-quick-guide-to-taming-nonstop-buzzing-of-bluetooth-devices-on-latest-os-update-fix-revealed/"><u>Quick Guide to Taming Nonstop Buzzing of Bluetooth Devices on Latest OS Update! [Fix Revealed]</u></a></li>
<li><a href="https://driver-error.techidaily.com/usb-microphonespeaker-troubleshooting-for-win10-users/"><u>USB Microphone/Speaker Troubleshooting for WIN10 Users</u></a></li>
<li><a href="https://driver-error.techidaily.com/guide-to-overcome-blue-screen-of-death-issue-error-code-0x0000007e-on-win7/"><u>Guide to Overcome Blue Screen of Death Issue (Error Code: 0X0000007E) on Win7</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-touchpad-driver-not-working-on-windows-10/"><u>Solved Touchpad Driver Not Working on Windows 10</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-economical-dslrs-for-the-cost-conscious/"><u>2024 Approved  Economical DSLRs for the Cost-Conscious</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-turn-off-find-my-iphone-14-plus-when-phone-is-broken-drfone-by-drfone-ios/"><u>How to Turn Off Find My iPhone 14 Plus when Phone is Broken? | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-ideal-voice-transformation-tools-for-digital-talent/"><u>In 2024, Ideal Voice Transformation Tools for Digital Talent</u></a></li>
<li><a href="https://driver-error.techidaily.com/dell-latitude-e4300-unsupported-in-debian-jessie-solved/"><u>Dell Latitude E4300 Unsupported in Debian Jessie [Solved]</u></a></li>
<li><a href="https://driver-error.techidaily.com/step-by-step-guide-restoring-the-missing-coprocessor-on-windows-nix/"><u>Step-by-Step Guide: Restoring the Missing Coprocessor on Windows Nix</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-best-10-screen-recorders-for-youtube/"><u>[Updated] Best 10 Screen Recorders for YouTube</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-access-denied-during-usb-installation-problems/"><u>Resolving 'Access Denied' During USB Installation Problems</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-amplify-focus-on-the-little-things-with-videoleap-zoom/"><u>In 2024, Amplify Focus on the Little Things with VideoLeap Zoom</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-exclusive-list-of-top-mobile-editing-software-for-iphoneandroid/"><u>2024 Approved  Exclusive List of Top Mobile Editing Software for iPhone/Android</u></a></li>
<li><a href="https://animation-videos.techidaily.com/in-2024-top-15-male-anime-characters-by-voting/"><u>In 2024, Top 15 Male Anime Characters By Voting</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-graphics-driver-deployment-roadblocks/"><u>Overcoming Graphics Driver Deployment Roadblocks</u></a></li>
<li><a href="https://driver-error.techidaily.com/complete-solution-installing-a-missing-coprocessor-driver-for-windows-10/"><u>Complete Solution: Installing a Missing Coprocessor Driver for Windows 10</u></a></li>
<li><a href="https://driver-error.techidaily.com/revealed-ms-bda-through-gfx-lens/"><u>Revealed: MS BDA Through GFX Lens</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-maximizing-your-library-a-detailed-walkthrough-of-downloading-music-from-spotify/"><u>New In 2024, Maximizing Your Library A Detailed Walkthrough of Downloading Music From Spotify</u></a></li>
<li><a href="https://driver-error.techidaily.com/healed-touchpad-drive-6-fixes-for-a-smooth-experience/"><u>Healed Touchpad Drive - 6 Fixes for a Smooth Experience</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-transform-your-memories-into-a-captivating-video-for-2024/"><u>New Transform Your Memories Into a Captivating Video for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/diagnosing-and-repairing-windows-failure-to-recognize-your-most-recent-usb-device/"><u>Diagnosing and Repairing Windows' Failure to Recognize Your Most Recent USB Device</u></a></li>
<li><a href="https://driver-error.techidaily.com/restoring-functional-status-of-realtek-usb-networks/"><u>Restoring Functional Status of Realtek USB Networks</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-leveraging-fb-instream-ad-techniques-to-boost-engagement/"><u>[Updated] Leveraging FB Instream Ad Techniques to Boost Engagement</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/beyond-virtualdub-explore-these-exceptional-video-editing-tools/"><u>Beyond VirtualDub Explore These Exceptional Video Editing Tools</u></a></li>
<li><a href="https://driver-error.techidaily.com/improve-system-with-newly-updated-death-driver-for-win11/"><u>Improve System with Newly Updated DeaTH Driver for WIN11</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-avi-editors-for-windows-11108187-easily-edit-avi-files-on-pc/"><u>Updated AVI Editors for Windows 11/10/8.1/8/7 Easily Edit AVI Files on PC</u></a></li>
<li><a href="https://driver-error.techidaily.com/securing-seamless-connection-lenovo-on-windows-10/"><u>Securing Seamless Connection: Lenovo on Windows 10</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/in-2024-sonic-design-lab-pioneering-audio-manipulation-in-sony-vegas-pro/"><u>In 2024, Sonic Design Lab Pioneering Audio Manipulation in Sony Vegas Pro</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/expert-tips-for-capturing-your-gaming-skills-in-obs-for-2024/"><u>Expert Tips for Capturing Your Gaming Skills in OBS for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-2024-windows-11-the-11-best-tricks-revealed/"><u>[New] In 2024, Windows 11  The 11 Best Tricks Revealed</u></a></li>
</ul></div>
