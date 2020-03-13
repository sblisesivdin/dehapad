[Home](index.md) | [About](about.md) | [Screenshots](screenshots.md) | [Dev](development.md) | [Archive](archive.md) | [Manual](user_manual.md) 

## Development

I know, the code is quite primitive, and mostly I am coding this to myself. So there are some known bugs and lack of features. Please do not expect too many things. It is a hobby. Just control this page at a time. New versions may arrive. At least I will release a major version at every April 21st.

Please report bugs and feature requests to sblisesivdin-AT-gmail.com email address.

### TODO 

I know, the code is quite primitive, and mostly I am coding this to myself. So there are some known bugs and feature missings. Please do not expect too many things. It is a hobby. Just control this page at a time. New versions may arrive. 


* Open in sidebar mode (must be with auto-save).
* Auto highlighting for each file type.
* Installation setup with file associations.
* Setup file with proper file associations is included.
* "Recent files" feature.
* Multi-file editor (Not planning in near future.)
* Rewrite read me.
* BUG: "Save as" is not asking nor controlling if there is existing file in that name. 


### CHANGELOG

#### Development version
* Import image (BMP2ASCII-Art)
* Mainmenu and its properties are closed for sidebar mode. Sidebar mode is more plain now.
* Border behavior changed and border icons are moved in sidebar mode.
* Caption of the window is now showing both filename and DEHApad's name.
* Newly designed about window.
* URL links are corrected.
* BUG SOLVED: When dehapad is closed in sidebar mode, sidebar's place stay intact. Windows can not use that space any more. sidebar usage is totally corrected.
* BUG SOLVED: "New file" behavior was totally erroneous. Now it is fixed for all possible situations with saved or non-saved file with saving, not-saving and cancelling selections.  It is a huge step for the reliability of the code for daily usage.
* BUG SOLVED: When closing a non-saved file, it asks two-times to save the file.
* BUG SOLVED: When open without any old remembered file info, an error occured.
* BUG SOLVED: Drag and Drop is not working properly since it is announced in v.0.26.01. It is working fine now with file remembering feature.

#### Version v.4.00 - April 21st, 2019
* .LOG support: Put .LOG in the first line of your file. It will add recent time information at the end of the file when opened.
* Opening user documentation website from Help menu,
* Go to line feature.

#### Version v.3.00 - April 21st, 2018
* Autosave.
* Web addresses are corrected in the About box.

#### Version v.2.76 - January 22nd, 2018
* Printing margins are corrected.
* Highlighting for 17 different languages.
* Setup file.

#### Version v.2.52 - October 27th, 2017
* Compiled with new FPC (v.3.0.2)
* Creating its own ".ini" file at first start. 
* Sizeable windows are corrected to be non-sizeable. Only main windows is sizeable.
* Use the short name of the program (DP) in sidebar mode. Use DEHApad or filename in normal mode.

#### Version v.2.12 - July 5th, 2017
* Instead of desktop centering for the forms, screen centering or main form centering is used (works better with more-than-one monitor setups,
* Right-click menu (popup menu),
* Wrong behaviors of File/New and File/Open menu items are corrected. Previously, one can open or create the file without saving the opened one.behaviours of File/New and File/Open menu items are corrected. Previously, one can open or create the file without saving the opened one.
* Form closing and exiting behaviours are corrected.
* Auto opens last file. 

#### Version v.2.0 - April 21st, 2017
* Using the latest name (DEHApad) in the code.
* Corrected Save and Save-As behaviour.behaviour.
* Showing the length of the file, the total number of lines and position of the cursor in the status bar.
* Some information is given in status bar like opening file saving file...etc.
* Major Feature: Totally new structure. SynEdit type text field.
* Major Feature: Printing! There are some options added in the options part of the program.
* Major Feature: Different font and coloring scheme for Normal and Sidebar modes.
* Redesigned icon, logo and about windows 
* Redesigned and re-programmed Options windows.
* The gutter is hidden in Sidebar mode.
* Adding some shortcuts (Ctrl-Q for Quit(previously Exit), Ctrl-Alt-O for Options).
* Bugfix: Main windows was activated when the Print dialogue was closed. Now option window is activated.

#### Version v.0.26.01 - Jan 9th, 2017
* Undo,
* Drag and drop.
* Insert date and time.
* Using new name (DApad) in the code.

#### Version v.0.22.72
* Some minor cosmetic changes.
* Adding shortcuts (Ctrl-N for New, Ctrl-O for Open, Ctrl-S for Save, Ctrl-X for Cut, Ctrl-C for Copy, Ctrl-P for Paste, Ctrl-A for Select All, Ctrl-F for Find, Ctrl-H for Replace, Ctrl-M for switching modes between normal and side pad modes, Ctrl-E and Ctrl-D for opening encryption/decryption dialog.
* Changing the case of selected text. Shortcuts are Shift+ Ctrl +U for Uppercase and Ctrl+U Lowercase.
* Select all.

#### Version v.0.16.98 - December 7th, 2016
* Find and Replace.
* Author and home page information with links added.
* Simple encryption-decryption.

#### Version v.0.14.24 - November 27th, 2016
* Edit menu with cut/copy/paste.
* Readme.txt file as a documentation.
* Some visual improvements. Commenting the code.
* Word-wrap and scrollbars.
* Changing Background color. Now, the default colour is a paper like the color (#E8E3BF). 

#### Version v.0.08.49 - November 6th, 2016
* Smaller file size and download size, 
* Sidebar mode changing process is taken from options form to the main form. With selecting the menu option, the mode is changing. 
* The font can be changed and font info can be saved ( the only style cannot be changed due to a compiler problem). 
* Compiled ".exe" has an icon now. 
* Working fine with HiDPi systems. 

#### Version v.0.06.57 - October 30th, 2016
* Everything is new for now :) 
