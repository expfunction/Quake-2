--   EDIT   --
*Retargeted for Visual Studio 2022
Steps completed:
- VS C++ 6.0 workspace (.dsw) converted to VS 2022 solution (.sln).
- All projects retargeted to Windows 10 SDK (10.0.18362.0).
- In all projects Function-Level linking enabled.
- Software renderer (ref_soft) project has been properly configured for MASM(!)
	~ Incremental linking enabled.
	~ Item types of .asm files selected as MASM
	~ Lp1 and Lp2 symbols edited in r_drawa.asm code (see git changes)!
- All projects except ctf built, tested and cofirmed as working properly :)
							-Burak Yazar
-- END EDIT --

This is the complete source code for Quake 2, version 3.19, buildable with
visual C++ 6.0.  The linux version should be buildable, but we haven't
tested it for the release.

The code is all licensed under the terms of the GPL (gnu public license).  
You should read the entire license, but the gist of it is that you can do 
anything you want with the code, including sell your new version.  The catch 
is that if you distribute new binary versions, you are required to make the 
entire source code available for free to everyone.

The primary intent of this release is for entertainment and educational 
purposes, but the GPL does allow commercial exploitation if you obey the 
full license.  If you want to do something commercial and you just can't bear 
to have your source changes released, we could still negotiate a separate 
license agreement (for $$$), but I would encourage you to just live with the 
GPL.

All of the Q2 data files remain copyrighted and licensed under the 
original terms, so you cannot redistribute data from the original game, but if 
you do a true total conversion, you can create a standalone game based on 
this code.

Thanks to Robert Duffy for doing the grunt work of building this release.

John Carmack
Id Software


