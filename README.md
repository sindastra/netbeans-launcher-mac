[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/W7W215OZB)

# Update 2021: Background Info

Back when NetBeans was taken over by Apache, the Mac version suffered as it was released without App launcher, and instead you'd simply get a Java application with scripts to run. This was not convenient, so I created this launcher, which allows you to conveniently double click (or single click in Dock) like with any other application. Of course, by now, Apache NetBeans for Mac gets packaged into a nice App, making this launcher here obsolete. But I'll keep it up in case you need to run an older version of NetBeans.

# netbeans-launcher-mac
Much desired NetBeans launcher for Mac

# Quick Start Guide

1. Create a folder /Applications/NetBeans
2. Extract the folder "netbeans" you downloaded from Apache and place it in the beforementioned folder
3. Place this launcher (.app) into /Applications/NetBeans (see bottom of this page on how to obtain)
4. Place your JDKHOME into /Applications/NetBeans (or create a symlink called JDKHOME to your actual JDKHOME)
5. Right click on the launcher and choose open, then choose open again when asked.

Normally launch NetBeans using this launcher from now on. Place it into your dock for convenience.

# Folder structure

Just to clarify, this is what the folder structure should look like (case sensitive):
```
/
|- Applications
  |- NetBeans
    |- netbeans
    |- JDKHOME
    |- NetBeans.app
```
Where "netbeans" is the downloaded version of Apache NetBeans (containing the folder "bin") and "JDKHOME" is either a symlink to JDKHOME or the JDKHOME contents itself.

# Obtaining

Get it from the [RELEASES](https://github.com/sindastra/netbeans-launcher-mac/releases)

# Installation

Simply download the "source" ZIP (or tarball) and install the NetBeans.app as described in this README.md (Quick Start Guide)
