Alarm Clock PowerPro - Professional Portable Alarm / Timer / Scheduling Software
Version: 2026.07.30

This is a portable application. No installation or administrator privileges are required.

======================================================================
SYSTEM REQUIREMENTS
   Windows 10 19045.x or later (64-bit)
   No installation required - fully portable
   It will run on older Win 10 but no support will be given to versions lower than 19045.x.

======================================================================
QUICK START
   Run "Alarm Clock Launcher.exe" to start.

======================================================================
INSTALLATION, UPDATES & DOWNGRADES 

   TL;DR: EXIT the program, then EXTRACT the ZIP over the existing folder and REPLACE ALL existing files.
      
   Recommended update method
      1) Exit the program.
      2) Extract the official ZIP over the existing folder.
      3) Replace all existing files when prompted.

   This preserves your alarms and configuration because official ZIP releases
   contain only the Default*.xml files. Existing Alarms.xml and Config.xml are
   left untouched.

   IMPORTANT:
      Always exit the program before replacing files.
      Updating while the program is running may leave EXE or DLL files only
      partially replaced, preventing the program from starting.

   Optional backup
      /Data/Alarms/Alarms.xml
      /Data/Config/Config.xml

      If you have added, removed, renamed, or modified files in /Media/, back up that folder before updating.
      A normal unzip and overwrite restores the original Media files, replacing any
			modified files that have the same filename.

======================================================================
CLEAN INSTALL - PRESERVE DATA
   A clean install is normally unnecessary. Updating by extracting over an existing
      installation is the recommended method.
   
   Perform a clean install only if you suspect program files have become damaged or
      modified, or if you want a completely fresh copy of the application.
   
	If you have added, removed, renamed, or modified any files inside /Media/,
   back up that folder before performing a clean install.

   A clean install restores the original program files. Any changes you have made
   inside the program folder (including custom media, renamed media files, or other
   personal files) must be backed up manually if you wish to keep them.

   There are two ways to perform a clean install
		A) use the migration EXE
		B) manual copy all necessary files
   
   Using Alarm Clock Migration.exe
      1) exit the program
      2) rename your OLD install to something like 'Alarm Clock PowerPro.old' (any unique name works)
      3) unzip the new install to the proper final desired location.
      4) Drag the old installation folder onto 'Alarm Clock Migration.exe'.
            The migration executable will copy only the known expected user data files from old to new.
            The migration executable does not copy any additional media, logs, backups, or other user files.
      5) After verifying everything works you can delete the old folder
            
   Manual clean install
      1) Exit the program.
      2) Back up these files from your OLD install:
            /Data/Alarms/Alarms.xml
            /Data/Config/Config.xml
            /Data/State/State.xml + State_old.xml  (optional)
            /Media/                                (if you have added custom media, renamed files, or edited files).
      3) After confirming your backups are complete, archive or rename the existing 'Alarm Clock PowerPro' folder.
      4) Extract a fresh copy of the official full (60MB+) ZIP package (not the small ~20MB patches).
      5) Restore your backed-up files to their original locations:
            /Data/Alarms/Alarms.xml
            /Data/Config/Config.xml
            /Data/State/State.xml + State_old.xml  (optional)
            /Media/                                (only if you have added, renamed, replaced, or edited media files)
      6) After verifying everything works you can delete the old folder

   Your alarms and settings will be restored while all program files are
   replaced with a clean copy. State files are optional. If omitted, they will be regenerated automatically over time.
   If State.xml is not migrated, the 'First Run Introduction' will be shown again.

   Alarm definitions reference media by filename. If a referenced file has been
   removed, renamed, or not restored after a clean install, the affected alarms
   will be flagged "Needs Review" until updated.

======================================================================
LICENSE
   Free for personal / 3-device use.
   Full License                  /LICENSE.txt
   For Third-Party assets see    /NOTICE.txt

======================================================================
PORTABLE
    No installation required.
    No AppData.
    No registry writes unless explicitly enabled.
    No Visual C++ Redistributable required.
    Move or copy the entire folder to relocate the program.

======================================================================
MULTIPLE VERSIONS

   Multiple versions may be stored on the same computer.

   Only one instance of Alarm Clock PowerPro may run at a time. Launching a
   second copy will activate the existing instance instead.

   This behavior may change in a future release.
	
======================================================================
DOCUMENTATION
   Features:               /Docs/Features.txt
   Version Notes:          /Docs/Version.txt
   Developer Notes:        /Docs/Dev notes.txt
   Third-Party Licenses:   /NOTICE.txt
