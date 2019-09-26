# netbeans-launcher-mac
Much desired NetBeans launcher for Mac

1. Create a folder /Applications/NetBeans
2. Extract the folder "netbeans" you downloaded and place it in the beforementioned folder
3. Place this launcher (.app) into /Applications/NetBeans
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
