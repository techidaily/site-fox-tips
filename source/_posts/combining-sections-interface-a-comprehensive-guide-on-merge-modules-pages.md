---
title: "Combining Sections Interface: A Comprehensive Guide on Merge Modules Pages"
date: 2024-09-27T05:03:21.151Z
updated: 2024-09-30T08:14:21.048Z
tags:
  - user-guide
categories:
  - advancedinstaller
description: "This Article Describes Combining Sections Interface: A Comprehensive Guide on Merge Modules Pages"
thumbnail: https://thmb.techidaily.com/7b4e6458caaa3e9950165c60cd6d036d2d81733c195f98fbf5326f59e3a1eeef.jpg
---

## Combining Sections Interface: A Comprehensive Guide on Merge Modules Pages

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
                  * [Merge Modules](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Configure Merge Module Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Edit Module Properties Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Select Merge Modules dialog](https://tools.techidaily.com/advancedinstaller/products/)  
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

## Merge Modules Page

Merge modules are simplified MSI packages that contain Windows Installer components, and setup logic to be included in any number of MSI packages. A merge module cannot be installed alone because it lacks some necessary database tables that are present in an installation database. Merge modules also contain additional tables that are unique to themselves. To install the information delivered by a merge module with an application; the module must first be merged into the application's .msi file. You can merge an MSI package with as many modules as you want.

![Merge modules](https://cdn.advancedinstaller.com/img/ui/merge-modules.png "Merge modules")  

![Caution!](https://cdn.advancedinstaller.com/svg/common/IconMessageWarning.svg) The project to which you add a merge module and the module itself is merged at build time. Therefore, after the package is built the merge module is not a separate element anymore.

Advanced Installer is using the Merge Modules support provided by the MergeMod COM server. This functionality comes with the Windows Installer SDK, in the mergemod.dll file.

If this file is not present on your machine, Advanced Installer notifies you with an exception at build time. For installing the MergeMod COM server follow the next steps:

* Download and install latest Windows Installer SDK from Microsoft Platform SDK.
* Open a command prompt in folder "C:\\Program Files (x86)\\Windows Kits\\8.0\\bin\\x86".
* Call from command-line "regsvr32.exe mergemod.dll". The result must be "DllRegisterServer in mergemod.dll succeeded."

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)Make sure you call the "regsvr32.exe mergemod.dll" from an elevated Command Prompt.

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)When you add a Merge Module, it is included in a feature and is displayed on the [Organization page](https://tools.techidaily.com/advancedinstaller/products/).

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105874/7443" target="_top" id="2105874">
  <img src="//a.impactradius-go.com/display-ad/7443-2105874" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105874/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Adding a merge module

![Add Merge Module](https://cdn.advancedinstaller.com/img/toolbar/merge-module-add.png "Add Merge Module") Use the \[Add Module... \] toolbar button, the “Add Module...” context menu item or press the Insert key. An Open File dialog appears where you can choose the module file to merge into your package. Advanced Installer extracts and displays some general information from the module. 

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)Advanced Installer shows you the dependencies (if any) of a merge module, none are added automatically to the project, and no type of dependency check is made at build time. However, Advanced Installer checks for module exclusions; if you try to add two merge modules and one of them excludes the other, the former is excluded from the build.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016148/19272" target="_top" id="2016148">
  <img src="//a.impactradius-go.com/display-ad/19272-2016148" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016148/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134224/18498" target="_top" id="2134224">
  <img src="//a.impactradius-go.com/display-ad/18498-2134224" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134224/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Adding a Visual Studio merge module

![Add Visual Studio MSM](https://cdn.advancedinstaller.com/img/toolbar/merge-module-vs-add.png "Add Visual Studio MSM") Use the \[Add Visual Studio MSM \] toolbar button or the “Add Visual Studio MSM” context menu item. A special dialog appears where you can select the Visual Studio merge modules to be merged into your package.

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)Most Visual Studio merge modules also require their corresponding**policy** MSM files.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014853/22899" target="_top" id="2014853">
  <img src="//a.impactradius-go.com/display-ad/22899-2014853" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014853/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484950/16446" target="_top" id="1484950">
  <img src="//a.impactradius-go.com/display-ad/16446-1484950" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484950/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Adding a merge module from the repository

Use the “Add From Repository” context menu item. You can inspect the merge modules from the repository from the [Repository Manager](https://tools.techidaily.com/advancedinstaller/products/).

### Exporting a merge module to the repository

Use the “Move To Repository” context menu item. You can inspect the merge modules from the repository from the [Repository Manager](https://tools.techidaily.com/advancedinstaller/products/).

### Adding an Advanced Installer merge module

![Add Advanced Installer MSM](https://cdn.advancedinstaller.com/img/toolbar/merge-module-ai-add.png "Add Advanced Installer MSM") Use the\[Add Advanced Installer MSM \] toolbar button or the “Add Advanced Installer MSM” context menu item. A special dialog appears where you can select the Advanced Installer merge modules to be merged into your package.

### Removing a merge module

![Remove](https://cdn.advancedinstaller.com/img/toolbar/remove.png "Remove") Use the \[Delete \] toolbar button, the “Delete” list context menu item or press the Delete key while a merge module is selected.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/857869/11832" target="_top" id="857869">
  <img src="//a.impactradius-go.com/display-ad/11832-857869" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/857869/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Edit the merge module's properties

Use the “Properties” option from the context menu while a merge module is selected. The [Edit Module Properties](https://tools.techidaily.com/advancedinstaller/products/) dialog appears.

### Configuring the merge process

Use the “Configure” context menu item or press the+ key. The [Configure Merge Module Dialog](https://tools.techidaily.com/advancedinstaller/products/) is displayed and allows you to configure the merge process. 

You can create a merge module using a [merge module](https://tools.techidaily.com/advancedinstaller/products/) project.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/977686/11832" target="_top" id="977686">
  <img src="//a.impactradius-go.com/display-ad/11832-977686" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/977686/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Explore the content of a merge module

Sometimes you want to know for sure what is included in a merge module. If so, the “Explore in Advanced Installer” option from the context menu can help. It imports the merge module in a separated Advanced Installer AIP project where you can examine its content in details. 

### Add dependencies of a merge module to the project

 Some merge modules are dependent on other merge modules. If this is the case, you can observe these dependencies in theDependencies column of the Merge Module view. If you decide to also include these dependencies in your project, Advanced Installer can help. Option “Add dependencies” from context menu tries to add automatically the dependencies of the selected merge module into the project. To achieve this, a search is performed in the directory where the selected merge module is placed. If a dependency cannot be found when you are notified. You can add by yourself these missed dependencies using the method described in Adding a merge module section. 

### Low MSM Compatibility

![Low MSM Compatibility](https://cdn.advancedinstaller.com/img/toolbar/low_msm_comp.png "Low MSM Compatibility")Enabling this option sets Advanced Installer to not include in the final package empty tables. This could result in breaking some custom actions from the included merge modules, that would try to use other predefined empty tables, which are not included in the output package.

## Topics

* [Configure Merge Module Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
Configure the merge process
* [Edit Module Properties Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
Merge Module Properties
* [Select Merge Modules dialog](https://tools.techidaily.com/advancedinstaller/products/)  
Select predefined merge modules

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
<li><a href="https://youtube-web.techidaily.com/024-approved-the-best-free-cloud-based-video-editing-tools/"><u>[New] 2024 Approved The Best Free, Cloud-Based Video Editing Tools</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-adventure-at-a-glance-comparing-gopros-hero5-b-and-session/"><u>[New] Adventure at a Glance Comparing GoPro's Hero5 B & Session</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-top-5-ps1-emulation-software-on-modern-computers/"><u>[Updated] In 2024, Top 5 PS1 Emulation Software on Modern Computers</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-ppt-presentations-with-verbal-narration-guide/"><u>2024 Approved PPT Presentations with Verbal Narration Guide</u></a></li>
<li><a href="https://fox-tips.techidaily.com/convert-and-save-your-favorite-vidspot-videos-as-mp4movavi-with-ease-video-converter-app/"><u>Convert and Save Your Favorite Vidspot Videos as MP4/MOV/AVI with Ease - Video Converter App</u></a></li>
<li><a href="https://fox-tips.techidaily.com/convert-your-giantbomb-videos-into-high-quality-mp4-files/"><u>Convert Your GiantBomb Videos Into High-Quality MP4 Files</u></a></li>
<li><a href="https://fox-tips.techidaily.com/download-high-quality-movies-from-pornotube-in-mp4movavi-formats-with-ease/"><u>Download High-Quality Movies From Pornotube in MP4/MOV/AVI Formats with Ease</u></a></li>
<li><a href="https://fox-tips.techidaily.com/download-high-quality-zapiks-sports-footage-in-various-formats-mp4-avi-mov/"><u>Download High-Quality Zapiks Sports Footage in Various Formats - MP4, AVI, MOV</u></a></li>
<li><a href="https://fox-tips.techidaily.com/download-vevo-songs-in-high-quality-formats-mp4-mp3-avi-for-mac-and-pc/"><u>Download Vevo Songs in High-Quality Formats (MP4, MP3, AVI) for Mac & PC</u></a></li>
<li><a href="https://fox-tips.techidaily.com/downloading-your-favorite-bravo-tv-episodes-in-various-formats-on-windows-or-mac-computers/"><u>Downloading Your Favorite Bravo TV Episodes in Various Formats on Windows or Mac Computers</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-bypass-icloud-activation-lock-with-imei-code-on-your-apple-iphone-se-2022-by-drfone-ios/"><u>In 2024, Bypass iCloud Activation Lock with IMEI Code On your Apple iPhone SE (2022)</u></a></li>
<li><a href="https://blog-min.techidaily.com/in-2024-how-to-use-life360-on-windows-pc-for-honor-magic-6-lite-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Life360 on Windows PC For Honor Magic 6 Lite? | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/master-the-shortcut-beginning-command-line-sessions-right-where-you-need-them-on-pc/"><u>Master the Shortcut: Beginning Command Line Sessions Right Where You Need Them on PC</u></a></li>
<li><a href="https://solve-lab.techidaily.com/movavi-aacwma-wav/"><u>Movavi의 고전 AAC/WMA 오피스 데이터를 위해 속도가 빨라진 무료 WAV 대응제: 세부 정보</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-inaccessible-delete-switch-in-windows-11-pins/"><u>Overcoming Inaccessible Delete Switch in Windows 11 PINs</u></a></li>
</ul></div>

