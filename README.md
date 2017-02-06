# ****************** Backup your settings ******************

# WebStorm-Syntax-Highlight---PHP-WordPress

Download syntax hightlight for webstorm - by alexander shcherbakov.jar File

To install the file just go to "In your WebStorm IDE" File -> Import Settings
Choose the new file.jar and press ok

It will import all the File Type PHP syntax Highlight for your WebStorm IDE

And Have fun :)


#Problems With importing the .jar file - no settings

Error: Invalid File - file.jar contains no settings to import. Please make sure you have generated the file using 'File|Export Settings feature

If you have this problem please refer to this steps

1. Export your own settings .jar file by going to File -> Export Settings... There is no need exporting all of the setting - Just the File Types - Uncheck all of the other options...
2. Open the .jar file with WINRAR "Or any other compresing software" and go to the "filetypes" folder.
3. Replace the php.xml file with the new provided file from this repo "XML/php.xml" - If there is no "php.xml" file in your just exported settings "settings.jar/filetypes/php.xml" file so just add the new file.... 
4. Import the updated file to your WebStorm - File -> Import Settings and press ok.
5. WebStorm should restart now and load with the new syntax highligh PHP/WordPress

This was Tested by me few times and works fine.... On WebStorm 11
