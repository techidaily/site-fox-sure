---
title: "Auto-Start Application Pinning: Quick Guide for Windows Taskbar"
date: 2024-10-09T21:09:17.934Z
updated: 2024-10-11T00:30:09.781Z
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
<a href="https://unicoeye.pxf.io/c/5597632/2134218/18498" target="_top" id="2134218">
  <img src="//a.impactradius-go.com/display-ad/18498-2134218" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134218/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-tips.techidaily.com/new-2024-approved-the-premier-ranking-comprehensive-8k-tv-analysis/"><u>[New] 2024 Approved The Premier Ranking Comprehensive 8K TV Analysis</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-digital-tapestry-crafting-visual-narratives-for-2024/"><u>[New] Digital Tapestry Crafting Visual Narratives for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-shine-up-advanced-setups-to-make-your-clips-pop/"><u>[New] Shine Up Advanced Setups to Make Your Clips Pop</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-streamlining-and-maximizing-your-ad-reach-a-compree-guide-to-fb-instream-ad-setup/"><u>2024 Approved Streamlining & Maximizing Your Ad Reach A Compree Guide to FB Instream Ad Setup</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/advance-repair-for-bad-and-corrupt-video-files-of-honor-90-by-stellar-video-repair-mobile-video-repair/"><u>Advance Repair for Bad and Corrupt Video Files of Honor 90</u></a></li>
<li><a href="https://fox-sure.techidaily.com/diy-guide-creating-personalized-holiday-videos/"><u>DIY Guide: Creating Personalized Holiday Videos</u></a></li>
<li><a href="https://fox-sure.techidaily.com/expert-apowersoft-guidance-and-support-services/"><u>Expert Apowersoft Guidance & Support Services</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-do-you-play-hevc-h-265-files-on-sony-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>How do you play HEVC/H.265 files on Sony ?</u></a></li>
<li><a href="https://fox-sure.techidaily.com/how-to-move-tv-episodes-from-ipad-to-pc-or-mac/"><u>How to Move TV Episodes From iPad to PC or Mac</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-behind-the-magic-cinematic-technique-1-5-insights/"><u>In 2024, Behind the Magic Cinematic Technique #1-5 Insights</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-the-pathway-to-reinvention-step-by-step-guide-on-altering-your-tiktok-handle/"><u>In 2024, The Pathway to Reinvention Step-by-Step Guide on Altering Your TikTok Handle</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/manage-your-default-podcast-adds-on-spotify-playlist-for-2024/"><u>Manage Your Default Podcast Adds on Spotify Playlist for 2024</u></a></li>
<li><a href="https://fox-sure.techidaily.com/step-by-step-guide-capturing-your-facebook-video-chats/"><u>Step-by-Step Guide: Capturing Your Facebook Video Chats</u></a></li>
<li><a href="https://fox-sure.techidaily.com/step-by-step-guide-seamlessly-duplicate-your-windows-pc-display-on-an-ipad/"><u>Step-by-Step Guide: Seamlessly Duplicate Your Windows PC Display on an iPad</u></a></li>
<li><a href="https://fox-sure.techidaily.com/top-3-seamless-methods-for-wireless-pc-to-mi-tv-connection/"><u>Top 3 Seamless Methods for Wireless PC-to-Mi TV Connection</u></a></li>
</ul></div>

