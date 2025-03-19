# ACSaveTool Changelog

## v2.6.0
- Added support for the AC:Shadows
- Added support for CLI mode
- GUI: Fixed the dark mode and switched to use the native theme on Windows 11

## v2.5.0
- Added support for AC:Mirage
- Extended the capability for game title auto detection
- Decryption/Encryption ID detection is now supported for AC:Revelations
- GUI: Allow test save file drag & drop to Encryption ID text field
- GUI: Open save button now locates a possible path for the selected game
- GUI: New option on Preferences to switch Account ID for save path detection
- GUI: New option on Preferences to enable verbose log
- Misc. code refactoring and fixup

## v2.4.3
- Added option on Preferences to keep the current save format
- Added support for loading certain non-standard saves
- Applied workaround to prevent crashes on platforms with Hardware-enforced Stack Protection enabled

## v2.4.2
- Fixed issue when processing certain non-standard saves
- GUI: Added dark mode support
- GUI: Added Preferences panel (Ctrl-P, for specific use only)

## v2.4.1
- Added support for Immortals Fenyx Rising
- Improved compatibility for some old saves
- Fixed broken input validation for certain game titles
- Added more tooltips to GUI

## v2.4.0
- Added support for ACValhalla
- Added input validation for Encryption/Decryption ID fields
- Minor GUI tweaks

## v2.3.1
- Added support to convert ACLHD save to ACLRM (choose ACLHD & double click `Encryption ID` label)
- Show output file name if different from the original file
- Adjusted release package structure

## v2.3.0
- Added support for loading certain non-standard saves (*.sav)
- Moved backup save location to separate `acst_backup` folder
- Fixed test save file processing logic
- Performance optimization
- Miscellaneous GUI issue fixup

## v2.2.0
- Disable detection feature if the game title is ACR
- Added support for Steep saves
- Changed default file open path to user profile directory
- Reduced release package size
- Some cleanup and minor GUI issue fixes

## v2.1.1
- Additional checking for the test save path to prevent a folder or file with the same name being used as test save
- Relaxed filtering for decryption/encryption ID input to allow underscores (_) and dots (.)

## v2.1.0
- Added support for detecting decryption key from test save file
- Fixed issue on GUI stopping processing saves when decryption and encryption key are both given
- Added showing execution time on GUI
- Added extra checking for valid save detection

## v2.0.0
- First public release
