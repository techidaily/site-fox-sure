---
title: "Auto-Start Application Pinning: Quick Guide for Windows Taskbar"
date: 2024-09-27T19:12:59.909Z
updated: 2024-09-30T01:02:34.900Z
tags:
  - user-guide
categories:
  - advancedinstaller
description: "This Article Describes Auto-Start Application Pinning: Quick Guide for Windows Taskbar"
thumbnail: https://thmb.techidaily.com/f3f2548974ead8262f3cbe2023235f7ed337f6212ab7a7e3e523b3fd374baa30.jpg
---

## Auto-Start Application Pinning: Quick Guide for Windows Taskbar

Table of Contents

* [Introduction](https://tools.techidaily.com/advancedinstaller/products/)
* [Registration](https://tools.techidaily.com/advancedinstaller/products/)
* [Using Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)
* [Features and Functionality](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Changing Version](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Upgrades](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Synchronized Folders](https://tools.techidaily.com/advancedinstaller/products/)  
   * [File Hashes](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Patches](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Single Package Authoring](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Single Instance Application](https://tools.techidaily.com/advancedinstaller/products/)  
   * [UAC](https://tools.techidaily.com/advancedinstaller/products/)")  
   * [Merge Modules](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Prerequisite Repository](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Native Java Launcher](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Packaging a Java App for Deployment on a Mac OS X](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Pack200 Compression](https://tools.techidaily.com/advancedinstaller/products/)  
   * [LZMA Compression](https://tools.techidaily.com/advancedinstaller/products/)  
   * [AES Encryption](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Smart Edit Control](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Smart Condition Edit Control](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Package User Interface](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Advanced Installer Updater](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Internet Information Services](https://tools.techidaily.com/advancedinstaller/products/)  
   * [SQL Databases](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Serial Validation](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Best Practice](https://tools.techidaily.com/advancedinstaller/products/)  
   * [ISO 19770-2](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Using the Table Editor](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Pin Program to Start Menu Automatically in Windows (App Packaging)](https://www.advancedinstaller.com/user-guide/tiles-show-start.html "Pin Program to Start Menu Automatically in Windows (App Packaging)")
* [Tutorials](https://tools.techidaily.com/advancedinstaller/products/)
* [Samples](https://tools.techidaily.com/advancedinstaller/products/)
* [How-tos](https://tools.techidaily.com/advancedinstaller/products/)
* [FAQs](https://tools.techidaily.com/advancedinstaller/products/)
* [Windows Installer](https://tools.techidaily.com/advancedinstaller/products/)
* [Deployment Technologies](https://tools.techidaily.com/advancedinstaller/products/)
* [IT Pro](https://tools.techidaily.com/advancedinstaller/products/)
* [MSIX](https://tools.techidaily.com/advancedinstaller/products/)
* [Video Tutorials](https://tools.techidaily.com/advancedinstaller/products/)
* [Advanced Installer Blog](https://tools.techidaily.com/advancedinstaller/products/)
* [Table of Contents](https://tools.techidaily.com/advancedinstaller/products/)

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Pin Program to Windows Start Menu

Microsoft strongly recommends against automatically showing tiles in the Start Menu from Windows as part of the installation. It should always be the user's choice. For this specific reason creating tiles for your application doesn't automatically make them visible in the Start Menu. Advanced Installer enforces asking the installing user for confirmation through the [**PINTOSTART** property](https://tools.techidaily.com/advancedinstaller/products/). 

After enabling [Show on Start](https://tools.techidaily.com/advancedinstaller/products/) option for your application in the [Tiles Page](https://tools.techidaily.com/advancedinstaller/products/), you also need to set the PINTOSTART property to IDYES as follows:

* From the [Dialog Editor page](https://tools.techidaily.com/advancedinstaller/products/) if you have Enterprise or Architect license edition
* By using a [Message Box custom action](https://tools.techidaily.com/advancedinstaller/products/) if you have Professional

The behavior will be:

| **PINTOSTART** not set  | All tiles defined in the Tiles Page will be visible only when users manually pin an application (EXE) or application's shortcut to the Start Menu (context menu -> Pin to Start), after the installation. |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **PINTOSTART** \= IDYES | Same as above + tiles with "Show in Start" option enabled will be immediately visible after installation.                                                                                                 |

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2141680/17091" target="_top" id="2141680">
  <img src="//a.impactradius-go.com/display-ad/17091-2141680" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettieu.pxf.io/i/5597632/2141680/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Video tutorial

#### Did you find this page useful?

Please give it a rating:

 Thanks!

#### Report a problem on this page

Information is incorrect or missing

Information is unclear or confusing

Something else

#### Can you tell us what’s wrong?

Send message

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
<li><a href="https://youtube-zero.techidaily.com/ed-free-music-unlocked-the-ultimate-library-for-videographers/"><u>[Updated] Free Music Unlocked The Ultimate Library for Videographers</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-dominating-the-digital-space-from-5000-to-over-a-million-views/"><u>[Updated] In 2024, Dominating the Digital Space From 5,000 to Over a Million Views</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-uncapped-screenshot-savior-app-for-2024/"><u>[Updated] Uncapped Screenshot Savior App for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/can-i-bypass-a-forgotten-phone-password-of-samsung-galaxy-f14-5g-by-drfone-android/"><u>Can I Bypass a Forgotten Phone Password Of Samsung Galaxy F14 5G?</u></a></li>
<li><a href="https://fox-sure.techidaily.com/does-flipbuilder-support-integration-with-multimedia-content/"><u>Does FlipBuilder Support Integration with Multimedia Content?</u></a></li>
<li><a href="https://fox-sure.techidaily.com/easy-guide-to-enable-pdf-download-on-your-site-with-flipbuilder/"><u>Easy Guide to Enable PDF Download on Your Site with FlipBuilder</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-data-from-moto-g24-by-fonelab-android-recover-data/"><u>Easy steps to recover deleted data from Moto G24</u></a></li>
<li><a href="https://techtrends.techidaily.com/effective-communication-mastering-conversations-with-mozilla-thunderbird/"><u>Effective Communication: Mastering Conversations with Mozilla Thunderbird</u></a></li>
<li><a href="https://fox-sure.techidaily.com/efficient-steps-for-instantly-exporting-live-settings-into-a-theme-in-flipbuilder/"><u>Efficient Steps for Instantly Exporting Live Settings Into a Theme in FlipBuilder</u></a></li>
<li><a href="https://fox-sure.techidaily.com/effortlessly-transform-several-pdf-documents-into-individual-flipbooks-using-custom-naming-schemes-flipbuildercom/"><u>Effortlessly Transform Several PDF Documents Into Individual Flipbooks Using Custom Naming Schemes [FlipBuilder.com]</u></a></li>
<li><a href="https://fox-sure.techidaily.com/enhance-your-ebooks-by-adding-photos-a-guide-on-crafting-pixel-perfect-page-turners-with-flipbuilder-technology/"><u>Enhance Your eBooks by Adding Photos: A Guide on Crafting Pixel-Perfect Page Turners with FlipBuilder Technology</u></a></li>
<li><a href="https://fox-sure.techidaily.com/future-proofing-development-the-art-of-saving-and-recycling-flipprojects-on-flipbuildercom/"><u>Future-Proofing Development: The Art of Saving and Recycling FlipProjects on FlipBuilder.com</u></a></li>
<li><a href="https://fox-sure.techidaily.com/how-does-flipbuilder-facilitate-easy-file-uploads-for-your-web-projects/"><u>How Does FlipBuilder Facilitate Easy File Uploads for Your Web Projects?</u></a></li>
<li><a href="https://fox-sure.techidaily.com/how-to-localize-your-flipbook-content-with-flipbuilder-for-target-audience-engagement/"><u>How to Localize Your FlipBook Content with FlipBuilder for Target Audience Engagement</u></a></li>
<li><a href="https://fox-sure.techidaily.com/how-to-request-a-purchase-invoice-on-flipbuildercom/"><u>How to Request a Purchase Invoice on FlipBuilder.com</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/legal-free-fb-tunes-downloader-for-2024/"><u>Legal, Free FB Tunes Downloader for 2024</u></a></li>
<li><a href="https://win-able.techidaily.com/troubleshooting-guide-solving-the-tribes-of-midgard-game-crash-problems/"><u>Troubleshooting Guide: Solving the 'Tribes of Midgard' Game Crash Problems</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-2024-approved-easy-steps-to-make-a-talking-avatar-with-ai-from-any-photos/"><u>Updated 2024 Approved Easy Steps to Make a Talking Avatar with AI From Any Photos</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/vision-loss-card-detection-failed/"><u>Vision Loss: Card Detection Failed</u></a></li>
</ul></div>

