**buildhistory class**. 
This class records information about the contents of all packages built and about the images created by the build system in a Git repository where you can examine them. Build history
is disabled by default. To enable it, you need to add
```
INHERIT += “buildhistory”
BUILDHISTORY_COMMIT = “1”
```
