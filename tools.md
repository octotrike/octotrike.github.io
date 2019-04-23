---
title: Tools
description: Download, installation, use & versioning information for the Trike tool.
---

There are two implementations of Trike.  One is a spreadsheet, and the other is a standalone desktop tool.  We have big plans for the latter (read more [below](#standalone)), but unless you are a Trike or Smalltalk developer, you want the spreadsheet.

# <a name="spreadsheet">Spreadsheet</a>

Almost everyone who is currently using Trike to create threat models of actual systems is using the spreadsheet.  It is most compatible with Excel 2011 (yes, for Mac), but users have also reported success with other versions of Excel.  Unfortunately, it does not work with OpenOffice.
	
If you are just getting started, you will want to [download the latest publicly released Trike spreadsheet and help file](http://sourceforge.net/projects/trike/files/latest/download?source=files).
	
If you would like to be one of our alpha testers, or are seeing a bug someone has reported, you may want to try:
* [the latest development version of the Trike spreadsheet](https://sourceforge.net/p/trike/code/HEAD/tree/spreadsheet/trunk/src/Trike.xlsx)
* [the latest development version of the Trike help file](https://sourceforge.net/p/trike/code/HEAD/tree/spreadsheet/trunk/docs/help/TrikeHelp.xlsx)
* [the latest work-in-progress spreadsheet help](https://sourceforge.net/apps/trac/trike/wiki/Spreadsheet%20Help) on the wiki, since we are trying to move away from putting help in a spreadsheet

All versions of the spreadsheet are using Trike methodology version 1.5, which is an interim methodology bridging the very large gap between version 1 and version 2.
	
If you are seeing a bug no one has reported in any version of the spreadsheet, please take the time to [let us know]({{ "/contact" | relative_url }}) so we can fix it for you.

# <a name="standalone">Standalone Tool</a>

If you started following Trike back in the dawn of time, you probably saw or played our standalone desktop tool.  This tool was written in Smalltalk, specifically Squeak.  It implements methodology version 1, which is now fairly outdated.  It is mildly buggy and does not implement file import or export.  We are not maintaining it in any way.  We mention it here mostly for historical reasons, but also because some of us got used to reading its style of intended actions grid.  If you want to look at its code or play with it yourself, you will need to [download Trike 1.1.2a for your OS](https://sourceforge.net/projects/trike/files/trike/1.1.2a/).  If your OS is not listed, you will need to download the generic files and supply your own [Squeak](http://www.squeak.org/) VM for your OS. 

The future of Trike is also a standalone desktop tool written in Smalltalk.  It will implement methodology version 2.  It will do file import and export, likely using an XML-based file format, and peer to peer collaboration.  It is in the pre-alpha stage.  We have a design and threat model, and are in the process of moving our code base from SqueakSource and our laptops (bad us), where it has been living, to SourceForge.  If you want to play, you will soon be able to:
* follow these [instructions for setting up a Trike development environment](http://trike.wiki.sourceforge.net/Development+Environment) and likely
* [contact us]({{ "/contact" | relative_url }}) or poke around elsewhere on [the Trike wiki](http://trike.wiki.sourceforge.net/)
