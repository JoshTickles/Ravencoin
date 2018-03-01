# RavenBinaries Mac Download Instructions

1) Download Raven-Qt.dmg from this repository.

2) Double click the DMG to mount it. 

3) Drag Raven Core icon to the Applications Folder

4) Open the Applications folder and Launch Raven Core.

Note: You may get the follow error on first launch:
```
Dyld Error Message:
  Library not loaded: @loader_path/libboost_system-mt.dylib
  Referenced from: /Applications/Raven-Qt.app/Contents/Frameworks/libboost_thread-mt.dylib
  Reason: image not found
```
To resolve, you will need to copy libboost_system.dylib to libboost_system-mt.dylib in the /Applications/Raven-Qt.app/Contents/Frameworks folder  
  
