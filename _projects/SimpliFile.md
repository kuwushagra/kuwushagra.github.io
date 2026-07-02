---
layout: project
projectname: SimpliFile
description: A Minimal GUI-Based File Manager Using ImGui and OpenGL
projectimage: https://github.com/kuwushagra/SimpliFile/raw/main/screenshots/screenshot.png?raw=true
projectlink: https://github.com/kuwushagra/SimpliFile
multidownload: true
multidlwindows: https://github.com/kuwushagra/SimpliFile/releases/download/v1.3.5-c41/SimpliFile-windows.zip
multidllinux: https://github.com/kuwushagra/SimpliFile/releases/download/v1.3.5-c41/SimpliFile-linux.zip
multidlmacosx86: https://github.com/kuwushagra/SimpliFile/releases/download/v1.3.5-c41/SimpliFile-macos-x86_64.zip
multidlmacosarm: https://github.com/kuwushagra/SimpliFile/releases/download/v1.3.5-c41/SimpliFile-macos-arm64.zip
---

## About 
This File Manager was made as a college project and can perform very basic operations such as:
- Creation of New Folders
- Deletion of Folders
- Cut/Copy/Paste (on both files and folders)
- Renaming of files and folders
- Navigation of folders
- Launching/opening files of various types by double click (opens in the default app set by your DE)
- Show used space in volume


### Platforms
<img src="https://skillicons.dev/icons?i=windows"/> <img src="https://skillicons.dev/icons?i=linux"/> <img src="https://skillicons.dev/icons?i=apple"/>  

This application is presently usable and buildable on Windows, Linux & macOS.

## Running:

### Windows:
- Download the latest SimpliFile-Windows.zip from the [Releases Section](https://github.com/kuwushagra/SimpliFile/releases)
- Extract both the `.exe` and the `includes` folder
- Get the latest version of `MinGW-w64`
- Double click the executable or execute `SimpliFile.exe` from the commandline
  
### Linux:
1. Download the latest zip and extract the `SimpliFile.AppImage` from the [Releases Section](https://github.com/kuwushagra/SimpliFile/releases)
2. Run `sudo apt install libfuse2t64 libglfw3`
4. Run `chmod +x SimpliFile.AppImage`
5. Either double click on the AppImage or run `./SimpliFile.AppImage`

### macOS:

- Download the latest SimpliFile-macos-<x86_64/arm64>.zip from the [Releases Section](https://github.com/kuwushagra/SimpliFile/releases) depending on your architecture
- Run `brew install glfw`
- Extract the `SimpliFile.app` file (in most cases you will just see the .app file so no need to extract)
- Double click to launch
