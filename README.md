# movepict_icloud2lr_autoimport
Moves images from Apple iCloud photo library to a directory from where Lightroom can import them

Description
===
The script should be run from cron every minute.

Directories left empty will be deleted if untouched more than one minute.

It then looks for files in the Fotobibliotek.photoslibrary/Masters library that hasn't been updated for more than 0 seconds. This is to prevent moving files still beind written in the photo library.

Files found will be moved to a local direcroty outside the photo library, from where Lightroom or similar app are able to import it.
