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
http://mackyle.github.com/fakeroot site.

In order to build, the Mac OS X 10.4u SDK is required as well as the developer
tools (with gcc version 4.0) and building requires Mac OS X 10.4 or later.
