# QuickLookFixer

## Overview

Force reloading of Generators list, and optionally reset the thumbnail disk cache too.

This repository includes two downloadable files: "**Reset QuickLook**" and "**Reset QuickLook (and Reset Disk Cache)**".

## Instructions

1. Copy & Paste `.workflow` file/s into user Services folder, located in Library.
  (`~/Library/Services/`)

2. Click the App Name in the top menu bar (e.g. "**Safari**", "**iTunes**").

3. Open the **Services** menu.

4. Click on your desired workflow.

5. You may see a spinning gear in your menu bar (*see below*). If you don't, you probably missed it and it's done it's job correct.

![Screenshot](https://user-images.githubusercontent.com/3734562/43505464-5de2cb24-95aa-11e8-9066-af6e14718ea1.png "Screenshot")

## Usage

In almost every case you should use **Reset QuickLook (and Reset Disk Cache)**. If you know what you're doing, and you don't wish to clear the cache, use **Reset QuickLook**.

**Reset QuickLook** performs `qlmanage -r`

**Reset QuickLook (and Reset Disk Cache)** performs `qlmanage -r cache`


| Workflow                               | Command           | Function                        |
| -------------------------------------- | ----------------- | ------------------------------- |
| Reset QuickLook                        | qlmanage -r       | Force reloading Generators list |
| Reset QuickLook (and Reset Disk Cache) | qlmanage -r cache | Reset thumbnail disk cache      |
