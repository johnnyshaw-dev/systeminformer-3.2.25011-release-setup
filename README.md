<div align="center">

<img src="assets/logo.svg" width="128" height="128" alt="System Informer logo">

# System Informer

A free, powerful, multi-purpose tool that helps you monitor system resources, debug software and detect malware.

Brought to you by Winsider Seminars & Solutions, Inc.

[![Build status](https://img.shields.io/github/actions/workflow/status/winsiderss/systeminformer/build.yml?branch=master&label=build)](https://github.com/winsiderss/systeminformer/actions)
[![Contributors](https://img.shields.io/github/contributors/winsiderss/systeminformer)](https://github.com/winsiderss/systeminformer/graphs/contributors)
[![License](https://img.shields.io/github/license/winsiderss/systeminformer)](LICENSE.txt)

[![Downloads](https://img.shields.io/github/downloads/winsiderss/systeminformer/total)](https://systeminformer.com)

[![Discord](https://img.shields.io/discord/789912032042254336?label=discord)](https://discord.gg/systeminformer)
[![Twitter](https://img.shields.io/twitter/follow/systeminformer?style=social)](https://twitter.com/systeminformer)
[![Website](https://img.shields.io/badge/website-systeminformer.com-blue)](https://systeminformer.com)

</div>

---

## System requirements

Windows 10 or higher, 32-bit or 64-bit.

## Features

* A detailed overview of system activity with highlighting.
* Graphs and statistics allow you quickly to track down resource hogs and runaway processes.
* Can't edit or delete a file? Discover which processes are using that file.
* See what programs have active network connections, and close them if necessary.
* Get real-time information on disk access.
* View detailed stack traces with kernel-mode, WOW64 and .NET support.
* Go beyond services.msc: create, edit and control services.
* Small, portable and no installation required.
* 100% Free Software (MIT)

## Building the project

Requires Visual Studio (2022 or later).

After cloning the repo run `build_init.cmd` located in the `build` directory, this doesn't not run again unless there are updates to the tools or third party libraries.

Execute `build_release.cmd` located in the `build` directory to compile the project or load the `SystemInformer.sln` and `Plugins.sln` solutions if you prefer building the project using Visual Studio.

You can download the free Visual Studio Community Edition to build the System Informer source code.

See the build readme for more information or if you're having trouble building.

## Enhancements/Bugs

Please use the [GitHub issue tracker](https://github.com/winsiderss/systeminformer/issues) for reporting problems or suggesting new features.

## Settings

If you are running System Informer from a USB drive, you may want to save System Informer's settings there as well. To do this, create a blank file named `SystemInformer.exe.settings.xml` in the same directory as `SystemInformer.exe`.

You can do this using Windows Explorer:

1. Make sure "Hide extensions for known file types" is unticked in Tools > Folder options > View.
2. Right-click in the folder and choose New > Text Document.
3. Rename the file to `SystemInformer.exe.settings.xml` (delete the `.txt` extension).
