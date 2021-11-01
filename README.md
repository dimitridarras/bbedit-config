# bbedit-config
Consistent settings for BBEdit on various machines.

https://apple.stackexchange.com/questions/227481/how-do-i-export-bbedit-settings-to-another-mac

 look in

~/Library/Containers/BBEdit/Data/Library/

Within that folder, you'll find version of the Preferences, BBEdit, and Application Support/BBEdit folders. So if you're transferring from an older BBEdit setup, copy your source

~/Library/Preferences/com.barebones.bbedit.plist

to

~/Library/Containers/BBEdit/Data/Library/Preferences/com.barebones.bbedit.plist,

on the new machine. Then

~/Library/BBEdit

to

~/Library/Containers/BBEdit/Data/Library/BBEdit,

and last

~/Library/Application Support/BBEdit

to

~/Library/Containers/BBEdit/Data/Library/Application Support/BBEdit

If your source preferences are already in ~/Library/Containers/BBEdit/Data/Library/, then just do a straight copy from old to new for the folders and files listed.
