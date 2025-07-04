# desktop2app

A quick tool to generate GNUstep App Wrappers from XDG applications.


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
