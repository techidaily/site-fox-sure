---
title: "Auto-Start Application Pinning: Quick Guide for Windows Taskbar"
date: 2024-10-03T16:54:34.845Z
updated: 2024-10-05T16:27:26.528Z
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
<a href="https://aligracehair.sjv.io/c/5597632/1959712/19272" target="_top" id="1959712">
  <img src="//a.impactradius-go.com/display-ad/19272-1959712" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959712/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-latest-instagram-photo-and-video-size-checklist/"><u>[New] In 2024, Latest Instagram Photo and Video Size Checklist</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-top-8-gold-text-wonders-in-the-vast-world-of-3d-sites/"><u>2024 Approved Top 8 Gold-Text Wonders in the Vast World of 3D Sites</u></a></li>
<li><a href="https://fox-sure.techidaily.com/easy-step-by-step-guide-how-to-add-voiceovers-in-your-video-projects/"><u>Easy Step-by-Step Guide: How to Add Voiceovers in Your Video Projects</u></a></li>
<li><a href="https://fox-sure.techidaily.com/effortless-integration-how-to-incorporate-pdf-files-into-your-ibook-collection/"><u>Effortless Integration: How to Incorporate PDF Files Into Your iBook Collection</u></a></li>
<li><a href="https://fox-http.techidaily.com/expert-timekeeping-tools-without-a-price/"><u>Expert Timekeeping Tools Without a Price</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-videos-from-xiaomi-redmi-note-13-proplus-5g-to-ipad-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Videos from Xiaomi Redmi Note 13 Pro+ 5G to iPad | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-remove-forgotten-pin-of-your-honor-magic-5-lite-by-drfone-android/"><u>In 2024, How to Remove Forgotten PIN Of Your Honor Magic 5 Lite</u></a></li>
<li><a href="https://fox-sure.techidaily.com/key-features-of-microsofts-server-roles-and-services/"><u>Key Features of Microsoft's Server Roles and Services</u></a></li>
<li><a href="https://fox-sure.techidaily.com/optimizing-java-launchers-a-guide-to-property-files-on-macos-systems/"><u>Optimizing Java Launchers: A Guide to Property Files on macOS Systems</u></a></li>
<li><a href="https://fox-sure.techidaily.com/optimizing-your-web-app-with-advanced-techniques-in-aspnet-settings/"><u>Optimizing Your Web App with Advanced Techniques in ASP.NET Settings</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/tips-and-tricks-for-setting-up-your-realme-c67-4g-phone-pattern-lock-by-drfone-android/"><u>Tips and Tricks for Setting Up your Realme C67 4G Phone Pattern Lock</u></a></li>
<li><a href="https://fox-sure.techidaily.com/top-rated-chromebook-video-editing-software-the-ultimate-guide/"><u>Top-Rated Chromebook Video Editing Software: The Ultimate Guide</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-server-disconnects-for-smoother-gameplay-in-escape-from-tarkov/"><u>Troubleshooting Server Disconnects for Smoother Gameplay in Escape From Tarkov</u></a></li>
<li><a href="https://fox-sure.techidaily.com/ultimate-guide-to-creating-effective-website-binders-and-pages/"><u>Ultimate Guide to Creating Effective Website Binders & Pages</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/wireless-sound-the-ultimate-guide-to-linking-your-bluetooth-speaker-with-your-pc/"><u>Wireless Sound: The Ultimate Guide to Linking Your Bluetooth Speaker with Your PC</u></a></li>
</ul></div>

