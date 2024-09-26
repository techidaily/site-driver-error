---
title: How to Resolve USB Installer Problems When You Get an 'Access Is Denied'
date: 2024-08-09T08:46:41.841Z
updated: 2024-08-10T08:46:41.841Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes How to Resolve USB Installer Problems When You Get an 'Access Is Denied'
excerpt: This Article Describes How to Resolve USB Installer Problems When You Get an 'Access Is Denied'
thumbnail: https://thmb.techidaily.com/89e14fb11e9e592fbd5c568e89cdfa2567dfefcd7e2cc4ffd1db69453f4dcbe5.jpg
---

## How to Resolve USB Installer Problems When You Get an 'Access Is Denied'

If you can’t install any new USB devices due to error “Access is denied”, it can be frustrating. But don’t worry, here you will find the solution to fix the problem.  
  
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57c6862c6dbe8.png) .

First, make sure that you login to computer as Administrator. If you are not logged in with Administrator, follow steps below to switch it to Administrator.  
  
1\. Go to**Control Panel**and View by**Category**. Click**User Accounts**.(In your case, this may be “User Accounts and Family Safety”.)  
  
![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57c68c5d7bf6a.jpg)
  
2\. Click **Change your account type** and enter your password if necessary.
  
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_5791ba4e50787.png)
  
 3\. Then click**Start** button and choose to **Log off**  of Windows, and then log back in again.
  
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_5791bab2104ee.png)

After that, reinstall the driver again.  
  
 **Turn off any antivirus or anti-spyware program**
  
If you are using an Administrator account and the problem persists, turn off any antivirus and anti-spyware program temporarily. This will work if the update is blocked by these program.
  
**Give permission to USBSTOR registry key**
  
If the problem could not be resolved, the USBSTOR registry key most probably has denied access to SYSTEM account. Follow these steps and give permission to USBSTOR registry key.
  
1\. Press**Win+R**(Windows key and R key) at the same time. A Run dialog will open.  
2\. Type**regedit**in the run box and click**OK**button.
  
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57c6905ba04f8.png)
  
 3\. Go to **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Services\\USBSTOR.** Right-click on it and select**Permissions…** from the context menu.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57c692c5d030c.jpg)
  
 4\. Select**SYSTEM** from the Group or user names. In Permissions for SYSTEM section, make sure the Full Control Allow checkbox is checked and uncheck any Deny checkbox. Click Apply button to apply the changes.  
  
<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57c6933c3f709.png)

 Also check your user account and see if it has full control of the system and any deny checkbox is unchecked.

 After that, update the USB driver again and it should work this time.

 You can update drivers manually, but it could take forever. You can also update drivers through Windows Update, which may fail to provide new drivers. If you want to update drivers more easily and successfully, you can consider using Driver Easy to update the driver automatically, which can scan your computer and detect all problem drivers in 20 seconds, then give you a list of new drivers. Click [here](https://tools.techidaily.com/drivereasy/download/) to download Driver Easy now.
 Driver Easy has Free version and Professional version. Both versions can be used to download drivers automatically. But with Professional version, you can even update all drivers with 1 click. No time is wasted. More importantly, you will enjoy Free technical support guarantee and money-back guarantee. You can ask for further assistance regarding any driver issue. And you can ask for a full refund for any reason.

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


