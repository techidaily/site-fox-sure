---
title: "Understanding Software Release Criteria: Navigating the Launch Specifications Tab"
date: 2024-10-10T02:54:54.677Z
updated: 2024-10-11T02:33:31.452Z
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
<a href="https://appsumo.8odi.net/c/5597632/2105866/7443" target="_top" id="2105866">
  <img src="//a.impactradius-go.com/display-ad/7443-2105866" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105866/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-missing-fb-watch-icon-get-it-fixed-now/"><u>[New] 2024 Approved Missing FB Watch Icon? Get It Fixed Now</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-optimizing-zoom-conferences-the-power-of-filters/"><u>[New] In 2024, Optimizing Zoom Conferences The Power of Filters</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-nostalgia-reimagined-transforming-your-vintage-photos-into-cutting-edge-videos/"><u>[New] Nostalgia Reimagined Transforming Your Vintage Photos Into Cutting-Edge Videos</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-the-ultimate-guide-to-cam-cover-selection/"><u>[New] The Ultimate Guide to Cam Cover Selection</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-optimal-window-calls-8-top-rated-titles-4-1/"><u>[Updated] In 2024, Optimal Window Calls 8 Top Rated Titles #4-#1</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/comprehensive-guide-to-the-lg-um7300-a-beginners-49-4k-flat-screen-review/"><u>Comprehensive Guide to the LG UM7300 - A Beginner's 49 4K Flat Screen Review</u></a></li>
<li><a href="https://fox-sure.techidaily.com/dynamic-system-initialization-query-interface/"><u>Dynamic System Initialization Query Interface</u></a></li>
<li><a href="https://fox-sure.techidaily.com/effective-approaches-to-iservice-failure-response-and-recovery-tactics/"><u>Effective Approaches to IService Failure Response and Recovery Tactics</u></a></li>
<li><a href="https://tech-haven.techidaily.com/generative-ai-and-employment-can-chatgpt-surpass-human-work/"><u>Generative AI and Employment: Can ChatGPT Surpass Human Work?</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-change-lock-screen-wallpaper-on-nokia-by-drfone-android/"><u>In 2024, How to Change Lock Screen Wallpaper on Nokia</u></a></li>
<li><a href="https://fox-sure.techidaily.com/key-features-of-microsofts-server-roles-and-services/"><u>Key Features of Microsoft's Server Roles and Services</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/navigating-the-world-of-lut-filters-for-obs-mastery-for-2024/"><u>Navigating the World of LUT Filters for OBS Mastery for 2024</u></a></li>
<li><a href="https://fox-sure.techidaily.com/optimizing-java-launchers-a-guide-to-property-files-on-macos-systems/"><u>Optimizing Java Launchers: A Guide to Property Files on macOS Systems</u></a></li>
<li><a href="https://fox-sure.techidaily.com/quick-and-free-transform-your-mov-files-into-wmv-format-with-our-simple-converter/"><u>Quick & Free: Transform Your MOV Files Into WMV Format with Our Simple Converter</u></a></li>
<li><a href="https://fox-sure.techidaily.com/step-by-step-guide-mastering-the-art-of-downloading-captured-videos/"><u>Step-by-Step Guide: Mastering the Art of Downloading Captured Videos</u></a></li>
<li><a href="https://fox-sure.techidaily.com/step-by-step-tutorial-quickly-adorning-pics-with-festive-santa-caps/"><u>Step-by-Step Tutorial: Quickly Adorning Pics with Festive Santa Caps</u></a></li>
<li><a href="https://android-unlock.techidaily.com/still-using-pattern-locks-with-samsung-galaxy-z-fold-5-tips-tricks-and-helpful-advice-by-drfone-android/"><u>Still Using Pattern Locks with Samsung Galaxy Z Fold 5? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://fox-sure.techidaily.com/transferring-phonebook-info-flawlessly-upgrading-contacts-from-an-outdated-iphone-to-a-modern-one/"><u>Transferring Phonebook Info Flawlessly: Upgrading Contacts From an Outdated iPhone to a Modern One</u></a></li>
<li><a href="https://fox-sure.techidaily.com/understanding-collective-structures-an-insight-into-group-theoretical-approaches/"><u>Understanding Collective Structures: An Insight Into Group Theoretical Approaches</u></a></li>
</ul></div>

