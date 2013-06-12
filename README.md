Specing's miscellaneous utilities:
==================================

Everything is released under the GNU GPLv3

Im sure you can find a copy of the license floating around the 'net

A '#' on the line following the command indicates the program should be run as root
while '$' marks that it may be useful when used with no privileges.
The same line also lists expected arguments

UTILITIES
------------------------------------------------------------------------------
 - ptree-update 
 	- # ptree-update
 	- Maintain a compressed (SQuashFS) image of the Portage tree using either AUFS or rsync to tmpfs
 - analize-file-sizes 
 	- $ analize-file-sizes directory
	- Print how many files are there in size ranges: [ 2^n, 2^(n+1) ) for every n = 0,..,31
 - merge_log
	- $ merge_log earlier.log latter.log [merged.log]
	- merge two log files together removing the duplicate section (taking the lines from the second log).
	- start of the line (timestamp) is ignored when comparing lines for equality
	- CURRENTLY NOT FLEXIBLE AND PROBABLY BROKEN
