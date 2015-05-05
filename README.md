gptsync
=======

Here's an OSX port and enhancement i made to help creating hybrid MBR partitions on GPT drive.

Code came from project rEFit: http://refit.sourceforge.net/

MacNB modifications:

- Added -s option to show partition info (instead of a separate utility)
- Added code to check for Clover boot sectors
- Added GUID table entry for Linux File System (to fix "GPT partition of type 'Unknown' found, will not touch this disk”. This is also a bug in the Linux version of gptsync