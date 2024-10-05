---
title: "Combining Sections Interface: A Comprehensive Guide on Merge Modules Pages"
date: 2024-10-02T17:23:39.036Z
updated: 2024-10-05T16:14:43.431Z
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

### Adding a merge module

![Add Merge Module](https://cdn.advancedinstaller.com/img/toolbar/merge-module-add.png "Add Merge Module") Use the \[Add Module... \] toolbar button, the “Add Module...” context menu item or press the Insert key. An Open File dialog appears where you can choose the module file to merge into your package. Advanced Installer extracts and displays some general information from the module. 

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137973/21526" target="_top" id="2137973">
  <img src="//a.impactradius-go.com/display-ad/21526-2137973" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137973/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)Advanced Installer shows you the dependencies (if any) of a merge module, none are added automatically to the project, and no type of dependency check is made at build time. However, Advanced Installer checks for module exclusions; if you try to add two merge modules and one of them excludes the other, the former is excluded from the build.

### Adding a Visual Studio merge module

![Add Visual Studio MSM](https://cdn.advancedinstaller.com/img/toolbar/merge-module-vs-add.png "Add Visual Studio MSM") Use the \[Add Visual Studio MSM \] toolbar button or the “Add Visual Studio MSM” context menu item. A special dialog appears where you can select the Visual Studio merge modules to be merged into your package.

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)Most Visual Studio merge modules also require their corresponding**policy** MSM files.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006955/19272" target="_top" id="2006955">
  <img src="//a.impactradius-go.com/display-ad/19272-2006955" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006955/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Adding a merge module from the repository

Use the “Add From Repository” context menu item. You can inspect the merge modules from the repository from the [Repository Manager](https://tools.techidaily.com/advancedinstaller/products/).

<!-- affiliate ads begin -->
<span id="1982461">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982461.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982461">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982461.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982461%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982461/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Exporting a merge module to the repository

Use the “Move To Repository” context menu item. You can inspect the merge modules from the repository from the [Repository Manager](https://tools.techidaily.com/advancedinstaller/products/).

### Adding an Advanced Installer merge module

![Add Advanced Installer MSM](https://cdn.advancedinstaller.com/img/toolbar/merge-module-ai-add.png "Add Advanced Installer MSM") Use the\[Add Advanced Installer MSM \] toolbar button or the “Add Advanced Installer MSM” context menu item. A special dialog appears where you can select the Advanced Installer merge modules to be merged into your package.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123731/7443" target="_top" id="2123731">
  <img src="//a.impactradius-go.com/display-ad/7443-2123731" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123731/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Removing a merge module

![Remove](https://cdn.advancedinstaller.com/img/toolbar/remove.png "Remove") Use the \[Delete \] toolbar button, the “Delete” list context menu item or press the Delete key while a merge module is selected.

### Edit the merge module's properties

Use the “Properties” option from the context menu while a merge module is selected. The [Edit Module Properties](https://tools.techidaily.com/advancedinstaller/products/) dialog appears.

<!-- affiliate ads begin -->
<span id="1484963">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1484963.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1484963">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1484963.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1484963%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1484963/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Configuring the merge process

Use the “Configure” context menu item or press the+ key. The [Configure Merge Module Dialog](https://tools.techidaily.com/advancedinstaller/products/) is displayed and allows you to configure the merge process. 

You can create a merge module using a [merge module](https://tools.techidaily.com/advancedinstaller/products/) project.

### Explore the content of a merge module

Sometimes you want to know for sure what is included in a merge module. If so, the “Explore in Advanced Installer” option from the context menu can help. It imports the merge module in a separated Advanced Installer AIP project where you can examine its content in details. 

### Add dependencies of a merge module to the project

 Some merge modules are dependent on other merge modules. If this is the case, you can observe these dependencies in theDependencies column of the Merge Module view. If you decide to also include these dependencies in your project, Advanced Installer can help. Option “Add dependencies” from context menu tries to add automatically the dependencies of the selected merge module into the project. To achieve this, a search is performed in the directory where the selected merge module is placed. If a dependency cannot be found when you are notified. You can add by yourself these missed dependencies using the method described in Adding a merge module section. 

<!-- affiliate ads begin -->
<span id="1982485">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982485.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982485">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982485.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982485%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982485/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Low MSM Compatibility

![Low MSM Compatibility](https://cdn.advancedinstaller.com/img/toolbar/low_msm_comp.png "Low MSM Compatibility")Enabling this option sets Advanced Installer to not include in the final package empty tables. This could result in breaking some custom actions from the included merge modules, that would try to use other predefined empty tables, which are not included in the output package.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2005183/22899" target="_top" id="2005183">
  <img src="//a.impactradius-go.com/display-ad/22899-2005183" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005183/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-a-comprehensive-guide-to-thumbnail-production/"><u>[New] 2024 Approved A Comprehensive Guide to Thumbnail Production</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-instagram-perfection-sizing-your-video-just-right/"><u>[New] In 2024, Instagram Perfection Sizing Your Video Just Right</u></a></li>
<li><a href="https://youtube-data.techidaily.com/n-2024-unlocking-youtubes-viewer-count-secret-weights/"><u>[New] In 2024, Unlocking YouTube's Viewer Count Secret Weights</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-quick-tips-to-produce-quality-thumbnails-fast/"><u>[Updated] Quick Tips to Produce Quality Thumbnails Fast</u></a></li>
<li><a href="https://fox-tips.techidaily.com/efficient-querying-techniques-with-xml-search-parameters-for-enhanced-information-extraction/"><u>Efficient Querying Techniques with XML Search Parameters for Enhanced Information Extraction</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-erase-an-iphone-15-plus-without-apple-id-password-by-drfone-ios/"><u>How To Erase an iPhone 15 Plus Without Apple ID Password?</u></a></li>
<li><a href="https://fox-tips.techidaily.com/leading-no-cost-screen-capture-software-find-your-perfect-match/"><u>Leading No-Cost Screen Capture Software: Find Your Perfect Match!</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/scriptwriting-simplified-chatgpts-creative-methodologies/"><u>Scriptwriting Simplified: ChatGPT's Creative Methodologies</u></a></li>
<li><a href="https://fox-tips.techidaily.com/simple-methods-to-transform-your-product-images-background-into-perfect-white-no-photoshop-required/"><u>Simple Methods to Transform Your Product Images' Background Into Perfect White - No Photoshop Required!</u></a></li>
<li><a href="https://win-blog.techidaily.com/solving-wwe-2k20s-stability-issues-on-your-computer-effortlessly/"><u>Solving WWE 2K20's Stability Issues on Your Computer Effortlessly</u></a></li>
<li><a href="https://fox-tips.techidaily.com/step-by-step-guide-transforming-your-music-files-from-3ga-to-mp3-format/"><u>Step-by-Step Guide: Transforming Your Music Files From 3GA to MP3 Format</u></a></li>
<li><a href="https://fox-tips.techidaily.com/understanding-and-accessing-ftp-servers-a-comprehensive-guide/"><u>Understanding and Accessing FTP Servers: A Comprehensive Guide</u></a></li>
</ul></div>

