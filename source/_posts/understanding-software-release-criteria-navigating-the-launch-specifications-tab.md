---
title: "Understanding Software Release Criteria: Navigating the Launch Specifications Tab"
date: 2024-09-30T18:37:02.172Z
updated: 2024-10-05T17:51:16.379Z
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
<a href="https://aligracehair.sjv.io/c/5597632/2087248/19272" target="_top" id="2087248">
  <img src="//a.impactradius-go.com/display-ad/19272-2087248" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087248/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://some-guidance.techidaily.com/new-unveiling-vrs-immersive-visual-experience/"><u>[New] Unveiling VR's Immersive Visual Experience</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-perfect-end-youtube-outro-essentials-and-top-creators/"><u>[Updated] The Perfect End YouTube Outro Essentials & Top Creators</u></a></li>
<li><a href="https://fox-sure.techidaily.com/comprehensive-guide-to-customizing-ixml-file-attributes/"><u>Comprehensive Guide to Customizing iXML File Attributes</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/essential-choices-premier-extended-pads-for-pc-users-rankings-and-insights-2eplus-years/"><u>Essential Choices: Premier Extended Pads for PC Users - Rankings and Insights (2E+ Years)</u></a></li>
<li><a href="https://sound-issues.techidaily.com/fix-silent-system-restore-audio-on-your-windows-10-pc-instantly/"><u>Fix Silent System: Restore Audio on Your Windows 10 PC Instantly</u></a></li>
<li><a href="https://fox-sure.techidaily.com/how-can-i-protect-my-photographs-a-comprehnensive-guide-on-copyrighting-imagery/"><u>How Can I Protect My Photographs? A Comprehnensive Guide on Copyrighting Imagery</u></a></li>
<li><a href="https://fox-sure.techidaily.com/leading-2x2-photo-editor-apps-enhance-images-with-easy-crop-options-and-background-color-adjustments/"><u>Leading 2X2 Photo Editor Apps : Enhance Images with Easy Crop Options and Background Color Adjustments</u></a></li>
<li><a href="https://fox-sure.techidaily.com/module-selection-and-integration-wizard-dialogue-box/"><u>Module Selection & Integration Wizard Dialogue Box</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-the-best-in-show-a-comprehensive-review-of-the-10-most-effective-podcast-to-text-apps/"><u>Updated In 2024, The Best in Show A Comprehensive Review of the 10 Most Effective Podcast to Text Apps</u></a></li>
</ul></div>

