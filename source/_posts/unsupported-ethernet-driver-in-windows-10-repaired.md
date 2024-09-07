---
title: Unsupported Ethernet Driver in Windows 10 Repaired
date: 2024-09-06T03:33:46.373Z
updated: 2024-09-07T03:33:46.373Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverError
description: This Article Describes Unsupported Ethernet Driver in Windows 10 Repaired
excerpt: This Article Describes Unsupported Ethernet Driver in Windows 10 Repaired
thumbnail: https://thmb.techidaily.com/65300c988d41879c46efcdc0b8a7f4ebdd53e06feae865a9a356c9f8b695aec3.jpg
---

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115918/19272" target="_top" id="2115918">
  <img src="//a.impactradius-go.com/display-ad/19272-2115918" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115918/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Unsupported Ethernet Driver in Windows 10 Repaired

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b91ef1806793.jpg)

<!-- affiliate ads begin -->
<span id="1983553">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983553.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983553">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983553.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983553%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983553/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115947/19272" target="_top" id="2115947">
  <img src="//a.impactradius-go.com/display-ad/19272-2115947" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115947/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135349/19272" target="_top" id="2135349">
  <img src="//a.impactradius-go.com/display-ad/19272-2135349" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135349/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
3) Then right-click Realtek PCIe GBE Family Controller option and choose **Properties** .
<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014857/22899" target="_top" id="2014857">
  <img src="//a.impactradius-go.com/display-ad/22899-2014857" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014857/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de65b229a9.png)

 4) Go to**Advanced** tab, then choose**Speed & Duplex** option on the left side of the pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de6ed4d026.png)

 5) On the**Value** bar, change the default Auto Negotiation to **100 Mbps Full Duplex**  or some other options accordingly. We chose**100 Mbps Full Duplex** here, but yours could be different.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deb007e7e1.png)

<!-- affiliate ads begin -->
<span id="1993654">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993654.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993654">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993654.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993654%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993654/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 6) Now on the left side of the pane, choose**Energy Efficient Ethernet** option, then change the Value to**Disabled** . After the changes, hit**OK** to save.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587deab52d9e0.png)

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2135316/14409" target="_top" id="2135316">
  <img src="//a.impactradius-go.com/display-ad/14409-2135316" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2135316/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 7) Still, in the**Properties** window, this time, let’s go to**Power Management** tab. Un-tick the box for**Allow the computer to turn off this device to save power** . Then hit**OK** to save and exit.

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587decc3276b5.png)

---

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123512/26400" target="_top" id="2123512">
  <img src="//a.impactradius-go.com/display-ad/26400-2123512" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123512/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Option Three:** **Reinstall or Rollback Realtek Adapter Driver**

 1) Press**Windows key** and**X** at the same time, then choose**Device Manager** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de5537df74.png)
 2) Locate and click the arrow to expand the category**Network adapters** .
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135354/19272" target="_top" id="2135354">
  <img src="//a.impactradius-go.com/display-ad/19272-2135354" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135354/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587de66c519eb.png)
 3) Then right-click click**Realtek PCIe GBE Family Controller** option and then choose**Uninstall** .
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee15b99f3.png)

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014849/22899" target="_top" id="2014849">
  <img src="//a.impactradius-go.com/display-ad/22899-2014849" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014849/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Hit**OK** to continue.
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee50286a0.png)

 4) Go to the menu bar on the top and click the button for **Scan for hardware changes** .  
![](https://images.drivereasy.com/wp-content/uploads/2017/01/img_587dee9a707c2.png)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137205/26400" target="_top" id="2137205">
  <img src="//a.impactradius-go.com/display-ad/26400-2137205" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137205/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-tips.techidaily.com/0-most-susbcribed-youtuber-in-the-world/"><u>[New] 10 Most Susbcribed YouTuber in the World</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-best-starting-points-on-youtube-top-16-opener-list-for-growth/"><u>[New] 2024 Approved  Best Starting Points on YouTube  Top 16 Opener List for Growth</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-boost-your-videos-popularity-on-youtube/"><u>[New] 2024 Approved  Boost Your Video's Popularity on YouTube</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-craft-cinematic-magic-learn-green-screen-wonders-with-youtube/"><u>[New] 2024 Approved  Craft Cinematic Magic  Learn Green Screen Wonders with YouTube</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-craft-your-story-aspect-ratios-for-powerful-yt-thumbnails/"><u>[New] 2024 Approved  Craft Your Story  Aspect Ratios for Powerful YT Thumbnails</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-defining-your-visual-and-stylistic-identity-high-relevance/"><u>[New] 2024 Approved  Defining Your Visual and Stylistic Identity [High Relevance]</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-delving-into-the-advantages-and-disadvantages-of-youtube-premium/"><u>[New] 2024 Approved  Delving Into the Advantages and Disadvantages of YouTube Premium</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-does-youtube-offer-frequent-payments-to-you/"><u>[New] 2024 Approved  Does YouTube Offer Frequent Payments to You?</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-elevate-views-the-power-of-synergistic-youtube-content-partnerships/"><u>[New] 2024 Approved  Elevate Views  The Power of Synergistic YouTube Content Partnerships</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-elevate-your-freefire-presence-with-top-tips-and-tricks/"><u>[New] 2024 Approved  Elevate Your FreeFire Presence with Top Tips and Tricks</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-essential-tools-for-youtube-live-broadcasting-reveal-the-7-key-apps/"><u>[New] 2024 Approved  Essential Tools for YouTube LIVE Broadcasting  Reveal the 7 Key Apps</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-essential-youtube-tagging-strategies-for-optimal-visibility/"><u>[New] 2024 Approved  Essential YouTube Tagging Strategies for Optimal Visibility</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-expose-your-guide-to-finding-censored-youtube-clips/"><u>[New] 2024 Approved  Exposé  Your Guide to Finding Censored YouTube Clips</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-guidelines-for-optimal-youtube-video-brightness/"><u>[New] 2024 Approved  Guidelines for Optimal YouTube Video Brightness</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-instant-subscription-monitoring-tools/"><u>[New] 2024 Approved  Instant Subscription Monitoring Tools</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-mind-mavens-top-10-educational-youtube-hubs/"><u>[New] 2024 Approved  Mind Mavens  Top 10 Educational YouTube Hubs</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-professional-video-editing-simplified-with-mac-mp4-cutters/"><u>[New] 2024 Approved  Professional Video Editing Simplified with Mac MP4 Cutters</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-snippet-supremacy-essential-hashes-for-accelerated-viewership-growth/"><u>[New] 2024 Approved  Snippet Supremacy  Essential Hashes for Accelerated Viewership Growth</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-the-art-of-keeping-your-audience-attentive-and-committed-top-6-methods-revealed/"><u>[New] 2024 Approved  The Art of Keeping Your Audience Attentive & Committed  Top 6 Methods Revealed</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-the-role-of-green-infrastructure-in-revitalizing-cities/"><u>[New] 2024 Approved  The Role of Green Infrastructure in Revitalizing Cities</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-mellow-mixdowns-lowlighting-with-ease-in-garageband/"><u>[New] Mellow Mixdowns  Lowlighting with Ease in Garageband</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-slumber-solutions-through-asmr-advisors-choice/"><u>[New] Slumber Solutions Through ASMR  Advisors' Choice</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-top-8-best-screen-capture-tools-for-linux/"><u>[New] Top 8 Best Screen Capture Tools for Linux</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-focused-freedom-advanced-mounting-solutions-for-phonescams-for-2024/"><u>[Updated] Focused Freedom  Advanced Mounting Solutions for Phones/Cams for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-guide-to-picking-best-free-online-srt-translation-providers/"><u>2024 Approved  Guide to Picking Best Free Online SRT Translation Providers</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-mastering-access-to-exclusive-snapshots/"><u>2024 Approved  Mastering Access to Exclusive Snapshots</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/-engagement-crafting-an-animated-subscribe-button-in-filmoras-step-by-step-guide-for-2024/"><u>Drive Engagement  Crafting an Animated Subscribe Button in Filmora's Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-lock-apps-on-vivo-x-fold-2-to-protect-your-individual-information-by-drfone-android/"><u>How to Lock Apps on Vivo X Fold 2 to Protect Your Individual Information</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-remove-remote-management-from-iphone-se-2020-by-drfone-ios-unlock-ios-unlock/"><u>How to Remove remote management from iPhone SE (2020)?</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-apple-iphone-x-passcode-screen-drfone-by-drfone-ios/"><u>How to Unlock Apple iPhone X Passcode Screen? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-vivo-y77t-drfone-by-drfone-virtual-android/"><u>In 2024, Simple and Effective Ways to Change Your Country on YouTube App Of your Vivo Y77t | Dr.fone</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/-the-safest-ways-to-extract-and-convert-youtube-tracks-to-mp3/"><u>Learn the Safest Ways to Extract and Convert YouTube Tracks to MP3</u></a></li>
<li><a href="https://driver-install.techidaily.com/refreshing-printer-drivers-seamlessly-on-modern-oses/"><u>Refreshing Printer Drivers Seamlessly on Modern OSes</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/-vs-youtube-differences-between-vimeo-and-youtube-for-2024/"><u>Vimeo vs YouTube  Differences Between Vimeo and YouTube for 2024</u></a></li>
</ul></div>
