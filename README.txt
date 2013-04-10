README FOR BUILD-CGDB
=====================
The build-cgdb project builds a standalone, universal cgdb executable that runs
on Mac OS X 10.4 or later.

In addition, it creates a convenient installer to install the
/usr/local/bin/cgdb executable, the /usr/local/share/man/man1/cgdb.1 man page,
the /usr/local/share/info/cgdb.info info file and the
/usr/local/share/cgdb/cgdb.txt files.

The resulting installer is compatible with Mac OS X 10.4 and later.

--------
Building
--------
Simply run the build script and all necessary files will be downloaded and then
cgdb will be built and a cgdb.dmg disk image created containing the cgdb
installer.

------------
Requirements
------------
In order to build the installer, fakeroot must be installed.  A compatible
version of fakeroot can be installed from the github
http://mackyle.github.io/fakeroot site.

In order to build, the Mac OS X 10.4u SDK is required as well as the developer
tools (with gcc version 4.0) and building requires Mac OS X 10.4 or later.

-------
License
-------
The cgdb sources are licensed with GPLv2 (or later) and require Readline
version 5.1 or later.  Readline 5.2 is the last GPLv2 (or later) licensed
version of Readline (Readline 6 is GPLv3 or later).  The built OS X cgdb
executable included in the installer is linked against a version 5.2 Readline
library so the entire work remains GPLv2 (or later).

-----
Links
-----
cgdb home page:      http://cgdb.github.com/
cgdb GitHub page:    https://github.com/cgdb/cgdb
old cgdb sf page:    http://sourceforge.net/projects/cgdb/
old cgdb support:    http://cgdb.sourceforge.net/support.php
Readline tarball:    http://ftp.gnu.org/gnu/readline/readline-5.2.tar.gz
OS X Installers:     https://github.com/mackyle/build-cgdb/downloads
