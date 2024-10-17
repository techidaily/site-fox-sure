---
title: "Understanding Software Release Criteria: Navigating the Launch Specifications Tab"
date: 2024-10-12T23:01:11.378Z
updated: 2024-10-17T07:29:55.411Z
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
<a href="https://aligracehair.sjv.io/c/5597632/2135369/19272" target="_top" id="2135369">
  <img src="//a.impactradius-go.com/display-ad/19272-2135369" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135369/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://some-techniques.techidaily.com/new-hardware-basics-preparing-for-big-sur-os/"><u>[New] Hardware Basics Preparing for Big Sur OS</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-comprehensive-guide-ps4-recording-via-obs-studio/"><u>[Updated] 2024 Approved Comprehensive Guide PS4 Recording via OBS Studio</u></a></li>
<li><a href="https://fox-sure.techidaily.com/1728505657605-windowsnas/"><u>如何在Windows系统中将数据快速移动到NAS服务器上：基本步骤解读</u></a></li>
<li><a href="https://fox-sure.techidaily.com/anweisungen-fur-die-verwendung-von-win3n-disk-imager-mit-windows-10-x64-schritt-fur-schritt-leitfaden/"><u>Anweisungen Für Die Verwendung Von Win3n Disk Imager Mit Windows 10 (X64) - Schritt-Für-Schritt-Leitfaden</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/mastering-development-skills-the-best-online-programming-tutorials-for-the-year-2024/"><u>Mastering Development Skills: The Best Online Programming Tutorials for the Year 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-overheating-dilemma-of-shell-infrastructure-on-windows-and-linux-systems/"><u>Solving the Overheating Dilemma of Shell Infrastructure on Windows and Linux Systems</u></a></li>
<li><a href="https://fox-sure.techidaily.com/step-by-step-tutorial-uploading-camera-roll-images-from-iphone-to-snapchat/"><u>Step-by-Step Tutorial: Uploading Camera Roll Images From iPhone to Snapchat</u></a></li>
<li><a href="https://fox-sure.techidaily.com/troubleshooting-tips-how-to-successfully-complete-an-iphone-restore-when-itunes-gets-stuck/"><u>Troubleshooting Tips: How to Successfully Complete an iPhone Restore when iTunes Gets Stuck</u></a></li>
<li><a href="https://youtube-web.techidaily.com/k-more-watchers-simple-youtube-growth-hacks/"><u>Unlock More Watchers Simple YouTube Growth Hacks</u></a></li>
<li><a href="https://extra-hints.techidaily.com/virtual-viewpoint-battle-live-tools-vs-equipment/"><u>Virtual Viewpoint Battle Live Tools vs Equipment</u></a></li>
</ul></div>

