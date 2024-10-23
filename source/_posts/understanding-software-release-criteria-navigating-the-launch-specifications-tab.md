---
title: "Understanding Software Release Criteria: Navigating the Launch Specifications Tab"
date: 2024-10-20T05:52:22.591Z
updated: 2024-10-22T22:03:18.830Z
tags:
  - user-guide
categories:
  - advancedinstaller
description: "This Article Describes Understanding Software Release Criteria: Navigating the Launch Specifications Tab"
thumbnail: https://thmb.techidaily.com/fa290563760e589f24a85fc95189dcd8b9293ad6203d8af2e7f7aed06726e6d2.jpg
---

## Understanding Software Release Criteria: Navigating the Launch Specifications Tab

Table of Contents

* [Introduction](https://tools.techidaily.com/advancedinstaller/products/)
* [Registration](https://tools.techidaily.com/advancedinstaller/products/)
* [Using Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [GUI](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Working with Projects](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Installer Project](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Product Information](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Resources](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Package Definition](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Requirements](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Prerequisites](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Launch Conditions](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [System Launch Conditions Tab](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Software Launch Conditions Tab](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Custom Launch Conditions Tab](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Merge Modules](https://tools.techidaily.com/advancedinstaller/products/)  
         * [User Interface](https://tools.techidaily.com/advancedinstaller/products/)  
         * [System Changes](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Server](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Custom Behavior](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Patch Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Merge Module Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Updates Configuration Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Windows Store App Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Modification Package Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Optional Package Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Windows Mobile CAB Projects](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Visual Studio Extension Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Software Installer Wizards - Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Visual Studio integration](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Alternative to AdminStudio/Wise](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Replace Wise](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Migrating from Visual Studio Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Keyboard Shortcuts](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Shell Integration](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Command Line](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Advanced Installer PowerShell Automation Interfaces](https://tools.techidaily.com/advancedinstaller/products/)
* [Features and Functionality](https://tools.techidaily.com/advancedinstaller/products/)
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

## Software Launch Conditions Tab

Predefined conditions that must be fulfilled in order to launch the installation package.

![Software launch conditions](https://cdn.advancedinstaller.com/img/ui/software-launch-conditions.png "Software launch conditions")  

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)These launch conditions are per build, therefore they must be specified for each defined build. By default when a new build is created there are no launch conditions enabled for it. You can select the desired build in the toolbar builds combo. This option is enabled only if several build are defined.

The predefined launch conditions from Advanced Installer work in two ways:

* minimum version check - your package will be installed if the select version or a higher one is found on the machine
* fixed version check - your package will be installed only if that version which you select from the combo is installed on the target machine. No matter if a higher version exists or not.

All launch conditions that start with "Minimum" in the list below have as expected a minimum version check, all other launch conditions perform an exact version check.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151864/7443" target="_top" id="2151864">
  <img src="//a.impactradius-go.com/display-ad/7443-2151864" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151864/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Required Applications

Add software launch conditions to your package. The available options are:

| Launch Condition                                                       | Latest Supported Version                   |
| ---------------------------------------------------------------------- | ------------------------------------------ |
| Minimum IE version                                                     | Internet Explorer 11                       |
| Minimum IIS version                                                    | Internet Information Services 10.0         |
| Minimum .NET Core version                                              | .NET Runtime 8.0                           |
| Minimum .NET Framework version                                         | .NET Framework 4.8                         |
| Minimum Adobe Reader version                                           | Adobe Reader DC 2019                       |
| Minimum JRE version                                                    | Java Runtime Environment 10                |
| Minimum JDK version                                                    | Java Development Kit 22                    |
| Minimum DirectX version                                                | DirectX 12                                 |
| Installed Office Application                                           | Office 2016+                               |
| Minimum XNA Framework version                                          | XNA Framework 4.0                          |
| Minimum SQL Server Express version                                     | SQL Server Express 2019                    |
| Minimum SQL Server Compact version                                     | SQL Server Compact 4.0                     |
| Minimum SQL ODBC Driver version                                        | SQL Driver 17 for SQL Server               |
| Minimum ActiveSync / Windows Mobile Device Center version              | Winodws Mobile Device Center 6.1           |
| Installed VSTO Runtime                                                 | Visual Studio Tools for Office 4.0 Runtime |
| Installed Office 2003 PIA                                              | \-                                         |
| Installed Office 2007 PIA                                              | \-                                         |
| Installed Office 2010 PIA                                              | \-                                         |
| Installed Office Shared Interop Assembly                               | Office 2010 Shared Interop Assembly        |
| SharePoint Foundation                                                  | Microsoft SharePoint Server 2016           |
| Minimum PowerShell version                                             | PowerShell 7.2                             |
| Minimum Windows PowerShell version                                     | Windows PowerShell 5.1                     |
| Run only if user has permissions for deploying SharePoint solutions    | \-                                         |
| Run only if Administration and Timer SharePoint services are started   | \-                                         |
| Run only if the packaged SharePoint solutions are not already deployed | \-                                         |

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
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-singular-snaps-crafting-a-musical-experience-in-snapchat/"><u>[New] In 2024, Singular Snaps Crafting a Musical Experience in Snapchat</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-ranking-premium-free-excellence-the-finest-free-lut-selections/"><u>[New] Ranking Premium-Free Excellence The Finest Free LUT Selections</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-capture-attention-incorporating-borders-to-insta-videos/"><u>2024 Approved Capture Attention Incorporating Borders to Insta-Videos</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/a-comprehensive-guide-to-instagram-edits-for-professionals-for-2024/"><u>A Comprehensive Guide to Instagram Edits for Professionals for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719381834367-cep-library-integration/"><u>CEP Library Integration:</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/comprehensive-app-audit-insightful-through-az-capture-for-2024/"><u>Comprehensive App Audit Insightful Through AZ Capture for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/creative-filmmaking-on-a-budget-using-smartphones-as-webcams-for-2024/"><u>Creative Filmmaking on a Budget Using Smartphones as Webcams for 2024</u></a></li>
<li><a href="https://fox-sure.techidaily.com/die-einfachste-methode-pdf-konvertierung-iphone-zu-ipad-uber-vier-ansatze/"><u>Die Einfachste Methode: PDF-Konvertierung iPhone Zu iPad Über Vier Ansätze</u></a></li>
<li><a href="https://fox-sure.techidaily.com/effortlessly-switching-chats-a-guide-to-relocating-conversations-between-iphone-and-iphone-se/"><u>Effortlessly Switching Chats: A Guide to Relocating Conversations Between iPhone and iPhone SE</u></a></li>
<li><a href="https://fox-sure.techidaily.com/hddesd-usb/"><u>HDDがESD-USBにリプログラムされました！こうすれば通常モードで使えるようになります</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-nocturnal-notions-for-iphone-photographers/"><u>In 2024, Nocturnal Notions for iPhone Photographers</u></a></li>
<li><a href="https://fox-sure.techidaily.com/iphone-songs-auf-cd-brennen-ohne-itunes-und-mit-einfachen-methoden/"><u>IPhone Songs Auf CD Brennen: Ohne ITunes Und Mit Einfachen Methoden</u></a></li>
<li><a href="https://fox-sure.techidaily.com/1728506261130-pc/"><u>PC初期化前のアプリケーション無効化手順</u></a></li>
<li><a href="https://fox-sure.techidaily.com/schnelllosungen-fur-verzogerte-datentransfers-im-windows-server-2019-top-3-methoden/"><u>Schnelllösungen Für Verzögerte Datentransfers Im Windows Server 2019 - Top 3 Methoden</u></a></li>
<li><a href="https://fox-sure.techidaily.com/top-strategies-for-efficiently-backing-up-your-asus-notebook-on-windows-11/"><u>Top Strategies for Efficiently Backing Up Your ASUS Notebook on Windows 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/transferer-un-opus-a-une-version-en-ligne-sans-frais-movavi/"><u>Transférer Un Opus À Une Version En Ligne Sans Frais - Movavi</u></a></li>
<li><a href="https://fox-sure.techidaily.com/ultimate-strategies-for-preserving-past-correspondence-in-microsoft-outlook-the-definitive-walkthrough/"><u>Ultimate Strategies for Preserving Past Correspondence in Microsoft Outlook - The Definitive Walkthrough</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-data-from-zte-axon-40-lite-by-fonelab-android-recover-data/"><u>Undelete lost data from ZTE Axon 40 Lite</u></a></li>
<li><a href="https://fox-sure.techidaily.com/vollstandige-anleitung-zum-installieren-und-wiederaufleben-von-windows-11-auf-einer-frischen-festplatte-dreifache-strategien-fur-erfolg/"><u>Vollständige Anleitung Zum Installieren Und Wiederaufleben Von Windows 11 Auf Einer Frischen Festplatte - Dreifache Strategien Für Erfolg</u></a></li>
</ul></div>

