# icloud 2 Lightroom photoimport
Moves images from Apple iCloud photo library to a directory from where Lightroom can import them

Description
===
The script should be run from cron every minute.

Directories left empty will be deleted if untouched more than one minute.

It then looks for files in the Fotobibliotek.photoslibrary/Masters library that hasn't been updated for more than 0 seconds. This is to prevent moving files still beind written in the photo library.

Files found will be moved to a local direcroty outside the photo library, from where Lightroom or similar app are able to import it.

History
===
Originally the shell script was made just as a quick rutine to move files from A to B. No configuration, no style, just for the time being.

In the effort to learn GitHub, version controle, Python and Pycharm (in some locations using Mergurial), the script could serve that purpose.