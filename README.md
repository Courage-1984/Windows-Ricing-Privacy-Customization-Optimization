![wallpaper_1920x540_1710641511095](https://github.com/Courage-1984/Windows-Ricing-Privacy-Customization-Optimization/assets/18268669/2838ed94-0f6a-41a5-9ad7-c6fb50ee8510)

# Windows: Ricing, Privacy, Customization & Optimization

**Windows Ricing, Privacy, Customization &amp; Optimization. Windows security, performance, productivity and customization.**

> Improve on Windows settings, features and utilities. Install Themes, Icons, Cursors, Wallpapers & more! Block spying, tracking and telemetry on Windows. Remove Bloatware and monitor your Windows. Become a SUPER-USER!
***

# ‼️BEFORE DOING ANYTHING DO THIS FIRST:
Create a Bootable USB Recovery Drive for Windows 10, this is essebtial as you could use it to recover or troubleshoot your system in case something goes wrong. This guide covers Ricing, Debloating, Privacy, Custom & Optimization tweaks which all has the potential to maybe just break something. Though this should not happen so don't worry, these tweaks, scripts, software and etc have been tested and used by a lot!
[Create a Bootable USB Recovery Drive in Windows 10](https://www.tenforums.com/tutorials/4200-create-recovery-drive-windows-10-a.html)

> [!TIP]
> **ALSO: Make a habit of creating System Restore Points often:**
> [How to Create a System Restore Point in Windows 10](https://www.tenforums.com/tutorials/4571-create-system-restore-point-windows-10-a.html)
> 
> **ALSO: Make a habit of creating Backups of you Registry often:**
> [Create a Backup of the Entire Windows Registry](https://techpp.com/2022/03/11/backup-and-restore-windows-registry-guide/#Method_2_Create_a_Backup_of_the_Entire_Windows_Registry)

> [!NOTE]
> My thinking for the general direction of this guide/repo is the following:
> 1. First I'll start with the **debloating** and **privacy** stuff, after all it is ideal to have a nice clean system for the next
> 2. Then I will move on to somewhat a mixture of traditional **ricing** along with **tweaking** and **optimization**
> 3. And lastly I will recomend some general **software** to have

> [!IMPORTANT]
> This will not be a too in depth guide as **a lot** of the resoures I will provide has guides or steps whithin them or is just straight forward and instructions is not needed or is provided on their site.

***
![1201088](https://github.com/Courage-1984/Windows-Ricing-Privacy-Customization-Optimization/assets/18268669/356128a8-2f79-41a5-b6b4-05ac398d0f7c)
# 🪟 Windows
*some important and must have top level stuff for windows*

> [!TIP] Good to Know:
>     [**Use the System File Checker tool to repair missing or corrupted system files:**](https://support.microsoft.com/en-us/topic/use-the-system-file-checker-tool-to-repair-missing-or-corrupted-system-files-79aa86cb-ca52-166a-92a3-966e85d4094e) If some Windows functions aren't working or Windows crashes, use the System File Checker to scan Windows and restore your files.  (**NOTE:** This doesn't replace the fact that you **should** always make a system restore point before changing things)

1. Open an elevated command prompt.
2. Type the following command, and then press Enter.  It may take several minutes for the command operation to be completed.
```cmd
	DISM.exe /Online /Cleanup-image /Restorehealth	
```
3. When it has completed type the following command, and then press Enter.
```cmd
	sfc /scannow
```
4. A system restart might be required.
5. Go read the full article [HERE](https://support.microsoft.com/en-us/topic/use-the-system-file-checker-tool-to-repair-missing-or-corrupted-system-files-79aa86cb-ca52-166a-92a3-966e85d4094e).

[Keycheck](https://keycheck.dev/) - Keycheck - Check Shortcuts of 101 Apps

### 📁 Windows & Windows Files
[MAS](https://massgrave.dev/) - Microsoft Activation Scripts: A Windows and Office activator, also get your Genuine Installation Media for Windows & Office here [Github](https://github.com/massgravel/massgrave.dev).

[Microsoft Activation Scripts (MAS)](https://github.com/massgravel/Microsoft-Activation-Scripts) - A Windows and Office activator using HWID / Ohook / KMS38 / Online KMS activation methods, with a focus on open-source code and fewer antivirus detections.

[Fake Windows Activators](https://pastebin.com/gCmWs2GR) - Fake Windows Activators

[Gravesoft](https://gravesoft.dev/) - People making open-source and free software for Windows.

[Microsoft Software Download Listing](https://msdl.gravesoft.dev/) - Microsoft Software Download Listing lets you browse and download products from Microsoft Software Download pages [Github](https://github.com/gravesoft/msdl).

[TechBench](https://tb.rg-adguard.net/public.php) - Get your windows and office ISOs here. This project will no longer be updated. New project:

[List of files by Microsoft®](https://files.rg-adguard.net/) - List of files by Microsoft®

### 🖥️ command-line shell
[Windows Terminal](https://apps.microsoft.com/detail/9n0dx20hk701?rtc=1&hl=en-fr&gl=FR) - The Windows Terminal is a modern, fast, efficient, powerful, and productive terminal application for users of command-line tools and shells like Command Prompt, PowerShell, and WSL.

[PowerShell 7](https://www.howtogeek.com/663684/how-to-install-powershell-7-on-windows-10/) - PowerShell is a task automation and configuration management program from Microsoft, consisting of a command-line shell and the associated scripting language.

[WSL](https://learn.microsoft.com/en-us/windows/wsl/install#install-wsl-command) - Windows Subsystem for Linux: Windows Subsystem for Linux is a feature of Windows that allows developers to run a Linux environment without the need for a separate virtual machine or dual booting.

[Hyper™](https://hyper.is/) - Terminal

### 📦 Package Manager
[winget](https://apps.microsoft.com/detail/9nblggh4nns1?rtc=1&hl=en-fr&gl=FR#activetab=pivot:overviewtab) - Windows Package Manager

[Chocolatey](https://chocolatey.org/) - The package manager for Windows

[Ninite](https://ninite.com/) - Install and Update All Your Programs at Once

[Python](https://www.python.org/downloads/) - Python is a programming language that lets you work quickly and integrate systems more effectively.

[pip](https://pip.pypa.io/en/stable/installation/) - pip is the package installer for Python. You can use it to install packages from the Python Package Index and other indexes.

***
![wallpaper_3840x886_1710695249428](https://github.com/Courage-1984/Windows-Ricing-Privacy-Customization-Optimization/assets/18268669/bc9aa4d1-bfcf-4f14-9bfe-71c89109cf5a)
# 🏎️ Quickies
*things that you can decide if you want it or not and takes just a moment to implement*

### 🔑 Some Useful Registry Keys:
- [How to Remove the Folders From “This PC” on Windows 10](https://github.com/Courage-1984/Remove-Folders-From-This-PC-Win10)
- [Disable Windows Web Search in Start](https://github.com/Courage-1984/Disable-Windows-Web-Search-in-Start)
- [How to Enable Windows Photo Viewer in Windows 10](https://github.com/Courage-1984/Enable-Windows-Photo-Viewer-Win10)
- [Pin Files to Start on Windows 10](https://github.com/Courage-1984/Pin-Files-to-Start-Windows-10)
- [Show more details in Details pane of File Explorer](https://github.com/Courage-1984/Show-more-details-in-Details-pane-of-File-Explorer)
- [Add Take Ownership to Context Menu in Windows 10](https://github.com/Courage-1984/Add-Take-Ownership-to-Context-Menu)

Lists of Reg Keys: 
- [Registry Tweaks](https://www.ricing.chloechantelle.com/#advanced)
- [Registry Editing](https://namazso.github.io/nanami-tan/#RegEdit)

### 🪛 Tweaks
- [Windows God Mode Control Panel](https://github.com/Courage-1984/Windows-God-Mode-Control-Panel)
- [How to ACTUALLY Change the Windows Default System Font](https://github.com/Courage-1984/Windows-Change-Default-System-Font)
- [Remove the language indicator](https://www.askvg.com/fix-input-indicator-icon-comes-back-in-taskbar-notification-area-after-restarting-windows/) - Permanently remove language indicator from the taskbar
- [Fix search indexing](https://lifehacker.com/set-windows-10-to-search-all-file-contents-with-this-se-1733511735) - Start menu will search through files and file contents
- [WinSetView](https://github.com/LesFerch/WinSetView) - Globally Set Explorer Folder Views
- [How to Prevent Windows 10 or 11 From Automatically Downloading Updates](https://www.howtogeek.com/224471/how-to-prevent-windows-10-from-automatically-downloading-updates/)
- [How to stop Windows 10 from automatically updating device drivers](https://forums.tomshardware.com/faq/how-to-stop-windows-10-from-automatically-updating-device-drivers.2398360/)
- [Prevent Windows 10 from Automatically Restarting Your PC After Updating](https://lifehacker.com/prevent-windows-10-from-automatically-restarting-your-p-1723647582)
- [Fix problems that block programs from being installed or removed](https://support.microsoft.com/en-us/topic/fix-problems-that-block-programs-from-being-installed-or-removed-cca7d1b6-65a9-3d98-426b-e9f927e1eb4d) - The Program Install and Uninstall troubleshooter helps you automatically repair issues when you're blocked from installing or removing programs. It also fixes corrupted registry keys.

### 🦠 Online Url and File Analyses
- [VirusTotal](https://www.virustotal.com/) - Analyse suspicious files, domains, IPs and URLs to detect malware and other breaches
- [Hybrid Analysis](https://www.hybrid-analysis.com/) - Free Automated Malware Analysis Service. This is a free malware analysis service for the community that detects and analyzes unknown threats using a unique Hybrid Analysis technology.
- [Cloudflare Radar URL Scanner](https://radar.cloudflare.com/scan) - Understand the security, performance, technology, and network details of a URL with a publicly shareable report.
- [Jotti's malware scan](https://virusscan.jotti.org/) - Jotti's malware scan is a free service that lets you scan suspicious files with several anti-virus programs.
- [ANY-RUN](https://any.run/) - Interactive Online Malware Sandbox

***
![wallpaper_3840x886_1710695846578](https://github.com/Courage-1984/Windows-Ricing-Privacy-Customization-Optimization/assets/18268669/81381a9d-603c-43aa-9245-819e535ad81a)
# 🧰 Debloating, Optimisation, Customisation & Privacy
*This section will cover Debloating, Optimising & Tweaking your system along with some Privacy stuff.*

> [!IMPORTANT]
> **This section will have somewhat of an order to it. My top recommadations will be listed first and all will follow in and order of what I suggest to use them.**

## 🌟 FIRST:

🔥 [Chris Titus Tech's Windows Utility](https://github.com/ChrisTitusTech/winutil) - Chris Titus Tech's Windows Utility - Install Programs, Tweaks, Fixes, and Updates

You can just run the following in your powershell (admin):
``` powershell
  iwr -useb https://christitus.com/win | iex
```

✨ [SophiApp](https://github.com/Sophia-Community/SophiApp) - ⚡ The most powerful open source tweaker on GitHub for fine-tuning Windows 10 & Windows 11

You can just run the following in your powershell (admin):
``` powershell
  iwr app.sophia.team -useb | iex
```

📌 [Sophia Script for Windows](https://github.com/farag2/Sophia-Script-for-Windows) - ⚡ The most powerful PowerShell module on GitHub for fine-tuning Windows 10 & Windows 11

**This is basically the same thing as the previous but it's the script and not an app. The script is a bit autonomous so I suggest rather using the app SophiApp**

📌 [O&O AppBuster](https://www.oo-software.com/en/ooappbuster) - Bust Apps you do not want!

📌 [Bulk Crap Uninstaller](https://www.bcuninstaller.com/) - Remove large amounts of unwanted applications quickly.

📌 [Revo Uninstaller](https://www.revouninstaller.com/) - Uninstall unwanted programs and their leftovers, quickly and easily!

📌 [Uninstalr](https://uninstalr.com/) - Uninstalr is the best Windows uninstaller - Uninstalr is a fast, lightweight and accurate way to uninstall software in Windows.

> That basically covers it for the first section. With these tools you now should have a nice clean, debloated, optimised and fast system.

## 🌟 SECOND:

🔥 [privacy is sexy](https://privacy.sexy/) - 🔐 Enforce privacy & security best-practices on Windows, macOS and Linux.

✨ [Optimizer](https://github.com/hellzerg/optimizer) - The finest Windows Optimizer

📌 [Privatezilla](https://github.com/builtbybel/privatezilla#download) - 👀👮🐢🔥Performs a privacy & security check of Windows 10

📌 [O&O ShutUp10++](https://www.oo-software.com/en/shutup10) - Free antispy tool for Windows 10 and 11

> and that's the second part. You should now have some robust security, privacy, anti-telementary, anti-data-collection, anti-spying, and so one...

## 🌟 THIRD:

- [WPD](https://wpd.app/) - WPD is the most convenient way to configure various privacy settings in Windows.
- [WindowsSpyBlocker](https://github.com/crazy-max/WindowsSpyBlocker) - Block spying and tracking on Windows
- [MajorPrivacy](https://github.com/xanasoft/MajorPrivacy/) - Advanced Privacy Tool for Windows
- [Awesome Windows privacy](https://github.com/TemporalAgent7/awesome-windows-privacy?tab=readme-ov-file) - A list of awesome tools, documentation and scripts for better privacy on Microsoft Windows
- [Debloat Windows 10](https://github.com/W4RH4WK/Debloat-Windows-10) - A Collection of Scripts Which Disable / Remove Windows 10 Features and Apps
- [DisableWinTracking](https://github.com/bitlog2/DisableWinTracking?tab=readme-ov-file) - Uses some known methods that attempt to minimize tracking in Windows 10
- [Windows10Debloater](https://github.com/Sycnex/Windows10Debloater) - Script to remove Windows 10 bloatware.
- [Win11Debloat](https://github.com/Raphire/Win11Debloat) - A simple, easy to use powershell script to remove bloatware apps from windows, disable telemetry, bing in windows search aswell as perform various other changes to declutter and improve your windows experience. This script works for both windows 10 and windows 11.
- [RyTuneX](https://github.com/rayenghanmi/RyTuneX) - RyTuneX is a cutting-edge optimizer built with the WinUI 3 framework, designed to amplify the performance of Windows devices. Crafted for both Windows 10 and 11.
- [Windows 10 Privacy Guide](https://github.com/adolfintel/Windows10-Privacy) - Windows 10 Privacy Guide
- [Comparison of Windows 10 Privacy tools](https://www.ghacks.net/2015/08/14/comparison-of-windows-10-privacy-tools/) - Comparison of Windows 10 Privacy tools

> This was a short one. Items listed in this section is basically leftovers, ones that did not make it to the first and second section thus they are not neccecary if you used the ones in the first and second section.

## 🥈 Honorable Mentions

- [Eylenburg's Tech Website](https://eylenburg.github.io/) - Detailed Comparisons of OS's, Browsers, Environments and Services
- [System Tools, Hardware Tools, Windows ISOs, Customization](https://fmhy.net/system-tools) - System Tools, Hardware Tools, Windows ISOs, Customization
- [Couleur Tweak Tips](https://ctt.cx/) - Couleur Tweak Tips - a comprehensive aggregation of useful resources for enthusiasts looking to expand their toolchain of programs and adopt good practices to enhance the quality of life in daily computer use and video production.
- [CTT Wiki](https://github.com/couleur-tweak-tips/CTT) - Couleur Tweak Tips documentation hosted on GitHub Pages using Material for MkDocs
- [Couleur Tweak Tips Ongoing Projects](https://github.com/couleur-tweak-tips) - Couleur Tweak Tips Ongoing Projects
- [KMS_VL_ALL_AIO](https://raw.githubusercontent.com/abbodi1406/KMS_VL_ALL_AIO/master/KMS_VL_ALL_AIO.cmd) - Right click this link and save as KMS_VL_ALL_AIO.cmd. The BEST windows and office activator.
- [Open-Shell](https://open-shell.github.io/Open-Shell-Menu/) - A collection of utilities bringing back classic features to Windows.
- [QuickBoost](https://github.com/SanGraphic/QuickBoost) - Automated Windows 10 / 11 Tweaking Utility
- [QuickMon](https://github.com/RudolfHenning/QuickMon) - QuickMon is a simple monitoring and alerting tool. It allows you to monitor and alert on various resources/services locally or remotely.
- [Winaero Tweaker](https://winaerotweaker.com/) - It is an all-in-one application that comes with dozens of options for fine-grained tuning of various Windows settings and features
- [Sysinternals Suite](https://learn.microsoft.com/en-us/sysinternals/downloads/sysinternals-suite) - The Sysinternals Troubleshooting Utilities have been rolled up into a single Suite of tools
- [Process Explorer](https://learn.microsoft.com/en-us/sysinternals/downloads/process-explorer) - Process Explorer shows you information about which handles and DLLs processes have opened or loaded
- [Pegasun System Utilities](https://pegasun.com/system-utilities) - Maximize PC performance and battery life
- [Blackbird](https://www.getblackbird.net/) - Windows privacy, security and performance
- [Start X Back](https://github.com/echnobas/StartXBack) - A universal crack for Start Is/All Back.
- [Modern Flyouts](https://github.com/ModernFlyouts-Community/ModernFlyouts) - A modern Fluent Design replacement for the old Metro themed flyouts present in Windows.

***
![wallpaper_3840x886_1710698131501](https://github.com/Courage-1984/Windows-Ricing-Privacy-Customization-Optimization/assets/18268669/59647495-3441-4328-b2ce-db6ae409a6cf)
# 🍙 Ricing Windows
**ri • cing**

*/ry-sing/*

*making windows yours. tweaking & customising to fit your needs*

> [!CAUTION]
> **Don't forget to do your system restore points and backups often along with the registry, espescially with this section!**

> [!NOTE]
> I will be suggesting the stuff I did and like but at the end of this section I wil be posting resources to the best ricing guides and repos/indexes I found so go through them for a full understanding of what and how you can actully customise your windows. I highly recommend it.

****[READ ME IF YOU HAVE NO IDEA WHAT YOU ARE DOING](https://pastebin.com/raw/mtgSWp42)****

### 💜 My Recommendations

#### First we will start of with the software you should have

[Icaros](https://github.com/Xanashi/Icaros) - Icaros Shell Extensions: Icaros is a collection of lightweight, high quality, Windows Shell Extensions. Provide Windows Explorer thumbnails and properties for almost any file type!

[7+ Taskbar Tweaker](https://tweaker.ramensoftware.com/) - Customize the Windows taskbar with dozens of exclusive options. Adapt the taskbar to your workflow, not the other way around.

[TranslucentTB](https://github.com/TranslucentTB/TranslucentTB?tab=readme-ov-file) - A lightweight utility that makes the Windows taskbar translucent/transparent.

[ExplorerPatcher](https://github.com/valinet/ExplorerPatcher) - This project aims to enhance the working environment on Windows

[QTTabBar](http://qttabbar.wikidot.com/) - Adds a lot more functionality to Explorer, including tabs, hotkeys and alternative navigation panes. THIS ONE IS BETTER THAN THE NEXT

[K-Lite Codec Pack](https://codecguide.com/download_kl.htm) - Download the K-Lite Codec Pack so that QTTabBar can hover preview more file types!

[QtTabBar](https://www.yuque.com/indiff/qttabbar) - QTTabBar is a small tool that allows you to use tab multi label function in Windows Explorer. [Githhub](https://github.com/indiff/qttabbar)

[OldNewExplorer](https://msfn.org/board/topic/170375-oldnewexplorer-119/) - OldNewExplorer is the Windows 10 (and Windows 8.1, and 8) shell extension / tweaker which can undo "improvements" to file browsing made in newer Windows version. Everything is optional for your liking.

[StartIsBack](https://startisback.com/) - Real start menu for Windows 8 and Windows 10. Start menu is back and it's better than ever. Get the most useful shell enhancement for Windows 10 now!

[WinverUWP](https://github.com/dongle-the-gadget/WinverUWP) - A UWP version of winver

[Volume²](https://github.com/irzyxa/Volume2) - advanced Windows volume control

[Mouse Wheel Accelerator](https://sourceforge.net/projects/mwaccelerator/) - Mouse Wheel Accelerator improves the wheel scroll in windows towards dynamic smooth iPhone-like scrolling.

[Microsoft PowerToys](https://github.com/microsoft/PowerToys) - Windows system utilities to maximize productivity

[AutoHotkey](https://www.autohotkey.com/) - The ultimate automation scripting language for Windows.

Some of my AHK: [Custom-AutoHotkeys](https://github.com/Courage-1984/Custom-AutoHotkeys) - Custom AutoHotkeys for efficiency / productivity.

Some more AHK: [Xatmo980 Tools](https://github.com/Xatmo980/Tools) - A Small Collection of my Autohotkey Programs

[ClipClip](https://clipclip.com/) - clipboard management software for Windows

[flux](https://justgetflux.com/) - makes the color of your computer's display adapt to the time of day

[TeraCopy](https://www.codesector.com/teracopy) - Copy your files faster and more securely

[Jocys-com Clock](https://www.jocys.com/Clock/) - Clock for WINDOWS

[Mactype](https://www.dropbox.com/s/nyaxc8h1hb6lcx2/MacType.zip?e=2) - Better font rendering, includes version for W7 and W10 (also works on 8.1).

[7-Zip](https://www.7-zip.org/) - file archiver with a high compression ratio

[JDownloader 2](https://jdownloader.org/jdownloader2) - open-source download management tool

#### Windows Translucency:

#### A few things to make various parts of your Windows OS Translucent

- [TranslucentTB](https://github.com/TranslucentTB/TranslucentTB) - A lightweight utility that makes the Windows **taskbar** translucent/transparent.
- [TranslucentSM](https://github.com/rounk-ctrl/TranslucentSM) - A lightweight utility that makes the Windows **Start Menu** translucent/transparent
- [DWMBlurGlass](https://github.com/Maplespe/DWMBlurGlass) - Add custom effect to global system **title bar**, support win10 and win11.
- [ExplorerBlurMica](https://github.com/Maplespe/ExplorerBlurMica) - Add background Blur effect or Acrylic (Mica for win11) effect to **explorer** for win10 and win11.
- [TranslucentFlyouts](https://github.com/ALTaleX531/TranslucentFlyouts) - Translucent effect for most of the win32 **flyouts**.
- [Translucent Flyouts Config GUI](https://github.com/Satanarious/TranslucentFlyoutsConfig) - A configuration GUI for Translucent Flyouts

#### Cursor:

- [Mac Mouse Pointer Guide](https://www.intowindows.com/download-mac-mouse-cursor-for-windows-10/) - How To Get Mac Mouse Pointer (Cursor)
- [macOS Sierra Retina cursors](https://www.deviantart.com/in-dolly/art/macOS-Sierra-Retina-cursors-650823654) - macOS Sierra Retina cursors
- [ElCapitan cursors](https://www.deviantart.com/in-dolly/art/Updated-ElCapitan-cursors-593804414) - Updated ElCapitan cursors

**ElCapitan cursors is smaller but the macOS Sierra Retina cursors is much cleaner!**
- [Apple Cursor](https://github.com/ful1e5/apple_cursor?tab=readme-ov-file) - Free & Open source macOS Cursors.
- [macOS Cursors Megapack for Windows](https://github.com/antiden/macOS-cursors-for-Windows?tab=readme-ov-file) - Tested in Windows 10 & 11, 4K (125%, 150%, 200%). With 2 versions, 2 types and 3 different sizes!

****check out this repo above for a folder of mac cursors****

- [Posy's improved cursors for Windows 10](http://www.michieldb.nl/other/cursors/) - Posy's improved cursors for Windows 10

- [Modern Inverted Mouse Cursors for Windows](https://github.com/emvaized/modern_inverted_mouse_cursors) - Modern Inverted Mouse Cursors for Windows - This project aims to recreate standard inverted mouse cursors in Windows 10/11 with a more modern design
- [Adwaita cursors for HiDPI displays](https://github.com/manu-mannattil/adwaita-cursors) - Adwaita cursors for HiDPI displays - GNOME's Adwaita cursor theme in sizes 24, 30, ..., 96 and custom colors
  
- [Open Cursor Library](http://www.rw-designer.com/) - This library contains computer mouse cursors for Microsoft Windows systems. - 182220 cursors
- [Open Cursor Library - 182220 cursors](http://www.rw-designer.com/cursor-library) - Open Cursor Library - 182220 cursors
- [Cursor Editor](https://www.cursor.cc/?) - A Cursor Editor for those custom cursors of yours.


#### Font:

- [JetBrains Mono](https://www.jetbrains.com/lp/mono/) - A free and open source typeface for developers
- [Google Fonts](https://fonts.google.com/) - Browse Fonts
- [FontSpace](https://www.fontspace.com/) - Free Fonts | 120,000+ Font Downloads
- [DaFont](https://www.dafont.com/) - Download fonts
- [Dfonts](https://www.dfonts.org/) - Dfonts - Free Fonts Download

### I have not yet gotten into themes and wallpapers but I have some links for y'all and don't forget the ricing guides at the end of this section!

#### Wallpapers:

**Go check out my [Wallpaper Image Collections](https://github.com/Courage-1984/Wallpaper-Image-Collections) Github repo for some nice wallpapers**

- [WallpaperAccess](https://wallpaperaccess.com/) - Access to Thousands of Awesome Free HD Wallpapers
- [Original Windows Wallpapers](https://wallpaperaccess.com/original-windows) - Top Free Original Windows Backgrounds
- [Wallpapersden](https://wallpapersden.com/) - 4K Wallpapers | HD Wallpaper | Ultra HD 4K, 8K Wallpapers for Desktop & Mobiles
- [WallpaperHub](https://www.wallpaperhub.app/) - Free wallpapers for your PC, phone and tablet

### Theming:

#### Suggested Theme Patcher:

 [**SecureUxTheme**](https://github.com/namazso/SecureUxTheme) - A secure boot compatible in-memory UxTheme patcher - SecureUxTheme is a piece of software that removes signature verification of styles in Windows.

 #### **GUIDES:**

 - [Help: Step by step installing SecureUxTheme and a custom theme](https://github.com/namazso/SecureUxTheme/wiki/Help:-Step-by-step-installing-SecureUxTheme-and-a-custom-theme) - Help: Step by step installing SecureUxTheme and a custom theme
- [How to install Windows 10 or 11 Themes](https://www.deviantart.com/niivu/art/Installing-Windows-Themes-UPDATED-708835586) - A small tutorial on how to install and apply Windows 10 and 11 Themes
- [Home: WINDOWS 10 THEMES by niivu](https://github.com/niivu/Windows-10-themes/wiki) - Welcome to the Windows-10-themes wiki! For those interested in installing themes for Windows 10.

#### Other Theme Patchers:

- [UltraUXThemePatcher](https://mhoefs.eu/software_uxtheme.php?lang=en) - UltraUXThemePatcher modifies your system files so that 3. party themes can be used.
- [UXTheme Patcher](https://uxthemepatcher.com/) - UXTheme Patcher is a software that patch Windows 10 or Windows 11 theme signature requirements to enable Windows 10 or Windows 11 theme customization.

#### niivu:

*dabble in graphic design. Mainly GUI for Windows. Themes, skins, wallpapers & icons*

- [WINDOWS 10 THEMES by niivu](https://github.com/niivu/Windows-10-themes) - Windows 10 desktop themes created by niivu designs
- [WINDOWS 11 THEMES by niivu](https://github.com/niivu/Windows-11-themes) - Windows 11 desktop themes created by niivu designs
- [windows-customization-extras](https://github.com/niivu/windows-customization-extras) - Extra skins and Wallpapers for Windows Customization. Including Stardock Curtains, PotPlayer, foobar2000, etc..
- [7tsp-Icon-themes](https://github.com/niivu/7tsp-Icon-themes) - 7tsp icon themes for Windows as well as some extras. Please read the guide prior to installation
- [RoundedTB](https://github.com/RoundedTB/RoundedTB) - Add margins, rounded corners and segments to your taskbars!
- [niivu deviantart Windows Themes](https://www.deviantart.com/niivu/gallery) - niivu deviantart Windows Themes - 347.6K Watchers, 63 Deviations, 2.8M Pageviews
- [Big Sur 2 - Windows 10 Themes](https://www.deviantart.com/niivu/art/Big-Sur-2-Windows-10-Themes-861727886) - Big Sur 2 - Windows 10 Themes
- [Paranoid Android Redux for Windows 10](https://www.deviantart.com/niivu/art/Paranoid-Android-Redux-for-Windows-10-897408948) - Paranoid Android Redux for Windows 10

#### DeviantArt:

- [DeviantArt](https://www.deviantart.com/) - DeviantArt - The Largest Online Art Gallery and Community
- [Windows10themes](https://www.deviantart.com/tag/windows10themes) - Explore the Best Windows10themes Art
- [macOS Sierra for all Windows OS](https://www.deviantart.com/peterrollar/art/macOS-Sierra-for-all-Windows-OS-624954743) - macOS Sierra for all Windows OS
- [macOS theme](https://www.deviantart.com/macos2020/art/macOS-theme-835225319) - macOS theme
- [macOS Dark theme](https://www.deviantart.com/macos2020/art/macOS-Dark-theme-835637852) - macOS Dark theme
- [Windows X Desktop](https://www.deviantart.com/kamranvaliyev/art/Windows-X-Desktop-861559168) - Windows X Desktop
- [Windows X Button](https://www.deviantart.com/kamranvaliyev/art/Windows-X-Button-861556345) - Windows X Button
- [Big Sur for Google Chrome](https://www.deviantart.com/mnmldsgn/art/Big-Sur-for-Google-Chrome-860192433) - Big Sur for Google Chrome

#### Misc:

- [WINDOWSCUSTOMIZATION](https://windowscustomization.com/) - Shape your computer beautifully - Themes, Icons, Cursors, Wallpapers, Rainmeter & Miscellaneous.
- [7themes-su](https://7themes.su/) - OS Windows Themes, Skins, Icons, Wallpaper, Cursors & Miscellaneous.
- [VSTHEMES](https://vsthemes.org/en/) - Windows Design - Customize Desktop - Themes, Wallpapers, Skind, Icons, Cursors, Programs, Articles, etc
- [Discover Customization on DeviantArt](https://www.deviantart.com/topic/customization) - Download custom skins and assets to personalize your day-to-day tools and applications.
- [Explore Windows10](https://www.deviantart.com/tag/windows10) - Explore the Best Windows10 Art & Themes.
- [Dracula](https://draculatheme.com/) - One theme. All platforms.
- [Catppuccin Theme](https://github.com/catppuccin) - Catppuccin is a community-driven pastel theme that aims to be the middle ground between low and high contrast themes.
- [Aura Theme](https://github.com/daltonmenezes/aura-theme) - A beautiful dark theme for your favorite apps.
- [themer](https://themer.dev/) - development environment theme creator
- [Theme Studio](https://themes.vscode.one/) - Create Your Own VS Code Themes
- [terminal-sexy](https://terminal.sexy/) - Terminal Color Scheme Designer
- [Terminals Are Sexy](https://terminalsare.sexy/) - A curated list of Terminal frameworks, plugins & resources for CLI lovers.
- [TerminalSplash](https://terminalsplash.com/) - Windows Terminal Themes
- [Windows Terminal Themes](https://windowsterminalthemes.dev/) - Windows Terminal Themes
- [Stardock WindowBlinds](https://www.stardock.com/products/windowblinds/) - Customize the look and feel of your Windows 10 and Windows 11 Start menu*, taskbar, window frames, and more.
- [Stardock Products Multi Patcher v1.4](https://nsaneforums.com/topic/444155-stardock-products-multi-patcher-v14/?_fromLogin=1) - Stardock Products Multi Patcher v1.4
- [BigSurSounds](https://github.com/ThisIsNoahEvans/BigSurSounds) - Sounds extracted from macOS 11 Big Sur Beta 1
- [BigSurSounds](https://bigsur-sounds.itsnoahevans.co.uk/) - BigSurSounds - Download Entire Library
- [Fluent Search](https://www.fluentsearch.net/) - With Fluent Search, you can search for running apps, browser tabs, in-app content, files and more. Available for Windows 10/11 only.

### 🌐 Ricing Guides & Indexes

[ri • cing](https://www.ricing.chloechantelle.com/) - A nice, short and sweet ricing guide. The one that started this journey of discovering ricing for me!

[nanami-tan](https://namazso.github.io/nanami-tan/) - In-depth Ricing resource and index of helpful links. [Github Repo](https://github.com/namazso/nanami-tan/)

[The Windows Theming Wiki](https://github.com/winthemers/wiki) - Guides you need to start your windows ricing journey.

[Windows Ricing](https://ninjasr.heliohost.org/w/lb/windows) - Ricing (customizing) Windows.

[WINDOWS 10 RICING](https://github.com/DavidRela/riceWindows) - Windows 10 Ricing Guide - Tools, tutorials, and resources to get the best possible experience on an Microsoft Windows based system.

[list o' resources](https://rizonrice.github.io/resources) - Ricing resources for Linux, Mac and Windows.

[FMHY Themes / Ricing](https://fmhy.net/system-tools#themes-ricing) - FMHY Themes / Ricing

[winthemers](https://winthemers.github.io/) - winthemers is a community dedicated to customizing windows. [Github Repo](https://github.com/winthemers)

[r/ricing](https://www.reddit.com/r/ricing/) - This reddit is intended to be a central resource to help users get started with desktop customization

[The Ricing Guide - Linux](https://nam.is-a.dev/blog/ricing/) - The Ricing Guide - Linux

[Windux](https://github.com/OrbEnforcer/Windux) - Just a bunch of random ideas I took from reddit or other OS and tried to get them on windows through rainmeter.

***

# ⚙️ General Software

### Instead of creating another list I just thought I'd give you a link to another list of software I made: [Pixelated Pathways](https://courage-1984.github.io/pixelated-pathways/#software)
***

## 🖥️ I hope you enjoyed this guide/list and found some stuff usefull.

