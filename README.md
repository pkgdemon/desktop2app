# desktop2app

Tool to generate App Wrappers from XDG applications created with ChatGPT.


**Usage**

```
sudo ./desktop2app /usr/local/share/applications/firefox.desktop
```

**TODO**

* Integration with GSWrapper_Launcher
* Support for mime types

**Known Issues**

* If file viewer in GWorkspace/Workspace is open it might be required to logout to get icons.
* App Wrappers when clicked from dock may shift to the end of the dock when clicked.  This should be fixed with GSWrapper_Launcher.
