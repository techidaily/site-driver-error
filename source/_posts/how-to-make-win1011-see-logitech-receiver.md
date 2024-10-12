---
title: How to Make Win10/11 See Logitech Receiver
date: 2024-10-10T16:21:23.555Z
updated: 2024-10-12T16:36:45.115Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes How to Make Win10/11 See Logitech Receiver
excerpt: This Article Describes How to Make Win10/11 See Logitech Receiver
thumbnail: https://thmb.techidaily.com/c465b3961d0e8ae791649e84e8128b1614e8e09e935ed979e13eb915c45489fc.jpg
---

## How to Make Win10/11 See Logitech Receiver

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a8eaab2959a4-300x120.png)

 If you have a Logitech wireless mouse, and you get a message saying **Device driver software was not successfully installed** when you plug your unifying receiver into your PC, you’re not alone. Many Windows are reporting this problem as well. But no worries, this is not at all a hard problem to fix.

 If you’re bugged by this problem, no worries. Many Windows users are able to resolve it with one of the following solutions. You may not have to try them all; just work your way down until you find the one that works.

## Try these fixes, one at a time

1. [**Copy the driver file from a well-functioning computer**](https://ursime.pxf.io/r5bm57)
2. [**Remove possible conflict applications**](https://silver-cuisine.pxf.io/nlgolx)
3. [**Update mouse and USB drivers**](https://aofit.pxf.io/mmjyxq)
4. [**Run Logitech Unifying Receiver as administrator**](https://dhgate.sjv.io/5g6yb2)
5. [**Perform a hard reset**](https://martinic.evyy.net/m5azrm)

 You should get a working mouse or touchpad to do the instructions below. The following screenshots are shown on Windows 11, but all the fixes apply to Windows 10, and 8&7 as well.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896541/19272" target="_top" id="1896541">
  <img src="//a.impactradius-go.com/display-ad/19272-1896541" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896541/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## **1: Copy the driver file from a well-functioning computer**

 If your current PC lacks the needed driver file, your mouse receiver won’t work as well as it should. To fix it:

 1) Go to   **C:\\Windows\\inf\\**  to find the**usb.PNF** and**usb.inf** files. If you can see them on your current PC, then move on to the methods below.

![](https://www.drivereasy.com/wp-content/uploads/2016/07/win-11-usb-inf.jpg)

 2) If you can’t see them,**copy** them from another computer whose USB receiver is working properly and **paste** them onto this folder.

 3) If you don’t have another computer, see if you can find them via this path**C:\\Windows\\ System32** .

 4) If you can find the**usb.inf** and**usb.PNF** files, still, copy and paste them to the folder **C:\\Windows\\inf\\** .

## **2: Remove possible conflict applications**

 If you have MotionInJoy installed on your PC, it could be the culprit. It’s reported to conflict with Logitech unifying receiver. You can remove it:

 1) On your keyboard, hold down the Windows logo key and press R to open the Run window. Then type in**control** and hit Enter to open the**Control Panel** .

![](https://www.drivereasy.com/wp-content/uploads/2019/04/win-11-run-control-panel.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012406/19272" target="_top" id="2012406">
  <img src="//a.impactradius-go.com/display-ad/19272-2012406" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012406/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 2) View by**Category** and click **Uninstall a program** .

![](https://www.drivereasy.com/wp-content/uploads/2016/07/win-11-control-category-uninstall.jpg)

 3) Right-lick **MotionInJoy** and click **Uninstall** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_57830b6e39c32.png)

<!-- affiliate ads begin -->
<span id="1304647">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1304647.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1304647">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1304647.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1304647%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1304647/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4) Type in**regedit** in the search bar and then open it.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ae4aa24870a.png)

 5) On your keyboard, press the **Ctrl key** and **F** at the same time to open a search window. Type **DS3** .

![](https://www.drivereasy.com/wp-content/uploads/2016/07/win-11-registry-editor-ds3.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484910/16446" target="_top" id="1484910">
  <img src="//a.impactradius-go.com/display-ad/16446-1484910" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484910/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 6) Delete all the DS3 files that you can see, especially the DS3.exe file.

![](https://www.drivereasy.com/wp-content/uploads/2016/07/registry-delete-ds3.png)

 7) Unplug your**Logitech Unifying Receiver** .

 8) Restart your computer and then plug in your Logitech Unifying Receiver.

 9) Wait for Windows Update to help you find the correct driver.

## **3: Update Mouse and USB Drivers**

 One of the most common causes of an unresponsive keyboard is an outdated mouse or USB driver.

 There are two ways you can get the right drivers for your mouse and USB port: manually or automatically.

**Manual driver update**  – You can update your drivers manually by going to the manufacturer’s website and searching for the most recent correct driver. Note that for your USB driver, you may need to try both the manufacturer of your PC and also the manufacturer of your USB port’s chipset. Be sure to choose only drivers that are compatible with your variant of Windows 10\.

**Automatic driver update**  – If you don’t have the time, patience or computer skills to update your drivers manually, you can, instead, do it automatically with [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) .  Driver Easy will automatically recognize your system and find the correct drivers for your exact mouse and USB port, and your variant of Windows 10, and it will download and install them correctly:

 1)[**Download**](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.

 2) Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/img_58db63a8174fd.png)

 3) Click the**Update** button next to the flagged mouse device and/or USB port to automatically download and install the correct version of that driver (you can do this with the FREE version).

 Or click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (this requires the [**Pro version**](https://tools.techidaily.com/drivereasy/download/) – you’ll be prompted to upgrade when you click_**Update All**_ ).

![](https://images.drivereasy.com/wp-content/uploads/2017/03/img_58db63d8ac59f.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123727/7443" target="_top" id="2123727">
  <img src="//a.impactradius-go.com/display-ad/7443-2123727" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123727/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## **4: Run Logitech Unifying Receiver as administrator**

 1) On your keyboard, press the**Windows logo key** and**R** at the same time. Type**devmgmt.msc** and press**Enter** .

![](https://www.drivereasy.com/wp-content/uploads/2015/11/run-devmgmt.msc_.jpg)

 2) Expand **Mice and other pointing devices,** right-click the**HID-compliant mouse** and click **Disable** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_57834599bc659.png)

 3) Download [Logitech Unifying Software](http://support.logitech.com/en%5Fus/software/unifying) . After the download, right-click the icon and click **Run as administrator** .

![](https://www.drivereasy.com/wp-content/uploads/2016/07/win-11-logi-run-as-adm.jpg)

 4) After the installation, right-click**Logitech Unifying Software** in the**Start** panel and click **Run as administrator** .

![](https://www.drivereasy.com/wp-content/uploads/2016/07/win-11-logi-run-as-adm-start.jpg)

5) Your Logitech receiver should be able to work now.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1884021/19272" target="_top" id="1884021">
  <img src="//a.impactradius-go.com/display-ad/19272-1884021" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1884021/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## **5: Perform a hard reset**

**Note:**  When performing a**hard reset** , you must disconnect or remove all peripheral devices. You should start and test the computer by itself, and then reconnect one peripheral device at a time.
 1)**Turn off** your computer.

 2) **Remove** the computer from any port replicator or docking station.

 3) **Disconnect** all external connected peripheral devices such as USB storage devices, external displays, and printers.

 4) **Unplug** the AC adapter from the computer.

 5) **Remove** the battery from the battery compartment(If you are using a laptop).

 6) Press and hold down the**Power** button for about 15 seconds to drain any residual electrical charge from the capacitors that protect the memory.

 7) Insert the battery and plug the AC adapter back into the notebook computer, but do not connect any of the peripheral devices.

 8) Press the**Power** button to turn on the computer.

 9) If a startup menu opens, use the arrow keys to select**Start Windows Normally** , and then press the**Enter** key.

 10) After reconnecting each of the peripheral devices, run**Windows Update** to update all device drivers.

* [Logitech](https://store.drivereasy.com/order/cart.php?PRODS=4731822&QTY=1&AFFILIATE=108875)

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
<li><a href="https://youtube-data.techidaily.com/he-artistic-science-behind-youtube-live-imagery-for-2024/"><u>[New] The Artistic Science Behind YouTube Live Imagery for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-photographys-color-transformation-secrets/"><u>[Updated] Photography's Color Transformation Secrets</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-mastering-the-art-of-continuous-snapstreak-success/"><u>2024 Approved Mastering the Art of Continuous Snapstreak Success</u></a></li>
<li><a href="https://facebook.techidaily.com/digital-billionaires-pledge-5m-to-help-combat-virus/"><u>Digital Billionaire's Pledge: $5M to Help Combat Virus</u></a></li>
<li><a href="https://driver-error.techidaily.com/driver-error-system-search-failed/"><u>Driver Error: System Search Failed</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-pc-recordings-win-5-budget-friendly-filters/"><u>Enhance PC Recordings: Win 5 Budget-Friendly Filters</u></a></li>
<li><a href="https://driver-error.techidaily.com/guide-to-restoring-bluetooth-functionality-with-qualcomm-atheros-drivers-in-windows-10/"><u>Guide to Restoring Bluetooth Functionality with Qualcomm Atheros Drivers in Windows 10</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-why-does-the-pokemon-go-battle-league-not-available-on-oppo-reno-10-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Why does the pokemon go battle league not available On Oppo Reno 10 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/perfect-your-social-media-presence-wirecast-streaming-tips-for-2024/"><u>Perfect Your Social Media Presence Wirecast Streaming Tips for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/restored-functionality-to-windows-for-broadcom-80211n-adapter/"><u>Restored Functionality to Windows for Broadcom 802.11N Adapter</u></a></li>
<li><a href="https://driver-error.techidaily.com/stop-bluetooth-from-turning-on-automatically/"><u>Stop Bluetooth From Turning On Automatically</u></a></li>
<li><a href="https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-apple-iphone-7-drfone-by-drfone-virtual-ios/"><u>Thinking About Changing Your Netflix Region Without a VPN On Apple iPhone 7? | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/tricking-out-the-intellme-glitches/"><u>Tricking Out the IntellME Glitches</u></a></li>
<li><a href="https://driver-error.techidaily.com/win10-how-to-locate-missing-external-storage-devices/"><u>Win10: How to Locate Missing External Storage Devices</u></a></li>
<li><a href="https://driver-error.techidaily.com/win11-bootup-flaw-bsod-irql-disparity/"><u>Win11 Bootup Flaw: [BSOD] Irql Disparity</u></a></li>
</ul></div>

