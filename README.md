xpujol's Linux scripts library
==============================

Collection of personal scripts that I use to work on a Linux environment.

Where and how
-------------
- Currently working on CentOS release 6.5
- Library located on `/usr/bin/xpujol-linux-lib`, with all the files having permissions `777` and ownership `root root`
- Symlinks on `/usr/bin`, eg. `ln -s /usr/bin/xpujol-linux-lib/foobar /usr/bin/foobar`
- Since `/usr/bin` is in the `$PATH` variable for all users, the scripts will be available to anyone everywhere

The scripts
-----------
- **datesync**: syncs the date of the machine with an NTP server
- **perm**: sets the widest possible permissions and ownerships for all the files and directories within the present location
- **clearcache**: clears the memory disc caching. Particularly handy for clearing the MySQL query cache
- **cpapi**: very specific to my particular working file structure

