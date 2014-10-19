Impulse Tracker
===============

Full source code for Impulse Tracker, including sound drivers, network drivers,
and some supporting documentation

 

Pre-Requisite Software
----------------------

To build Impulse Tracker, you will need:

-   Turbo Assembler v4.1

-   Turbo Link v3.01

-   Borland MAKE v4.0

-   A DOS environment

 

Once you have these, building IT.EXE should be just a single call to `MAKE`

 

Quick File Overview
-------------------

-	IT.ASM
	Startup routines
	
-	IT\_DISK.ASM
	Disk IO Routines. Uses IT\_D\_\*.INC files

-	IT\_DISPL.ASM
	Display routines for the Playback Screen (F5)

-	IT\_EMS.ASM
	EMS memory handling routines

-	IT\_F.ASM
	Collection of functions used by the object model

-	IT\_FOUR.ASM
	Fast Fourier routines. Used by the graphic equalizer (Alt-F12).
	Not available on all all sound cards

-	IT\_G.ASM
	Global key handler functions

-	IT\_H.ASM
	Help Module (F1)

-	IT\_I.ASM
	Sample list (F3) and Instrument list (F4) module 

-	IT\_K.ASM
	Keyboard module

-	IT\_L.ASM
	Information line code

-	IT\_M.ASM
	Main message loop/dispatcher

-	IT\_MDATA.ASM
	Global music variable data

-	IT\_MMTSR.ASM
	Sample compression/decompression routines

-	IT\_MOUSE.ASM
	Mouse handling code

-	IT\_MSG.ASM
	Message editor module (Shift-F9)

-	IT\_MUSIC.ASM
	Module playback code. Also uses IT\_M\_EFF.INC

-	IT\_NET.ASM
	Network code

-	IT\_OBJ1.ASM
	UI object definitions

-	IT\_PE.ASM
	Pattern Editor module (F2)

-	IT\_S.ASM
	Screen functions, including character generation

-	IT\_TUTE.ASM
	Interactive Tutorial module

-	IT\_VESA.ASM
	VESA code for graphic equalizer

-	SWITCH.INC
	High level switches for the program

 
