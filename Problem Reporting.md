Problem Reporting - Realtek ALC AppleHDA_v1.0  
![alt text](https://github.com/toleda/audio_ALC_guides/blob/master/xsound.jpeg)  
# Problem Reporting - HDMI Audio AppleHDA
OS X HDMI audio support for Intel Graphis HD, AMD Radeon, Nvidia GeForce, Intel/AMD and Intel/Nvidia graphics configurations.  
Supports OS X: 10.11, 10.10, 10.9 and 10.8  
Native AppleHDA

**Problem Reporting/Support for all HDMI Audio Guides**

Change Log  

1.	**v1.0 - 1/21/15: El Capitan/10.11.x**

**HDMI Audio Guides** 

1. [HDMI Audio AppleHDA [Guides]](https://github.com/toleda/audio_hdmi_guides)

**Tools**

1. [IOReg_v2.1](https://github.com/toleda/audio_ALCInjection/blob/master/IORegistryExplorer_v2.1.zip) (select View Raw)
2. [DPCIManger](http://sourceforge.net/projects/dpcimanager/)  
3. [MaciASL](http://sourceforge.net/projects/maciasl/)
4. [audio_codecdetect.command](https://github.com/toleda/audio_ALCInjection/blob/master/audio_codecdetect.command.zip) (select View Raw)
5. Property List Editors -
	1. [Xcode](https://developer.apple.com/xcode/)  
	2. Property List Editor, PlistEdit Pro, TextEdit, etc.
	3. TextEdit, TextWrangler (last resort)
6. [Clover Configurator](http://www.osx86.net/files/file/49-clover-configurator/)
7. [Clover Wiki](http://clover-wiki.zetam.org/Home)

**Problem Reporting** (no files atached, no reply)

1.	Description of audio problem
2.	OS X version/motherboard model/BIOS version/processor/graphics
3.	Procedure/Guide used
4. Terminal/Shell/File/Export Text As. . . (if run)
	1. audio_codecdetect.command (Tools 4.)
5.	Copy of IOReg - IOReg_v2.1/File/Save a Copy As…, verify file (Tools 1.)
6. Copy Of Console/All Messages (last boot)/File/Save a Copy As..
7.	Installed S/L/E/AppleHDA.kext or AppleHDA8Series AppleHDAxxx kext
8.	Screenshot: 
	1. 	DPCIManager/Status (Tools 2.) 
	2. System Information/Hardware/Audio/Intel High Definition Audio (not Devices)
9. Terminal/Shell/File/Export Text As. . . (if run:)
	1. audio_cloverHDMI-1xx...command
10. Chameleon (if installed)
	1. Extra/org.chameleon.Boot.plist
	2. DPCIManager/Misc/Boot Log (Tools 2.)
	3. Extra/dsdt.aml (if installed)
	4. Extra/ssdt.aml (if installed)
11.	Clover (if installed)
	1.	EFI/CLOVER/config.plist
	2.	DPCIManager/Misc/Boot Log (Tools 2.)
	3.	EFI/CLOVER/ACPI/Patched/dsdt.aml (if installed)
	4.	EFI/CLOVER/ACPI/Patched/ssdt.aml (if installed)

Post to (select one link):

1.	[HDMI Audio AppleHDA - InsanelyMac.com](http://www.insanelymac.com/forum/topic/310530-el-capitan-applehda-hdmi-audio/)  
2. [HDMI Audio AppleHDA - tonymacx86.com](http://www.tonymacx86.com/hdmi-audio/143760-audio-hdmi-audio-applehda-guide.html)
 
toleda
https://github.com/toleda/audio_hdmi_guides
