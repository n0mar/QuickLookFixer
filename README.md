# QuickLookFixer

## Overview

Force reloading of Generators list, and optionally reset the thumbnail disk cache too.

This repository includes two downloadable files: "**Reset QuickLook**" and "**Reset QuickLook (and Reset Disk Cache)**".

## Installation

1. Open `.workflow` file/s. You will be prompted with the dialogue below.

![Installation Dialogue](https://user-images.githubusercontent.com/3734562/43505869-942ba9f2-95ab-11e8-8e91-521bf44bd88f.png "Installation dialogue")

  The `.workflow` will be **moved** (*not copied*) to `~/Library/Services/`

# Usage

1. Click the App Name in the top menu bar (e.g. "**Safari**", "**iTunes**").

2. Open the **Services** menu.

3. Click on your desired workflow.

4. You may see a spinning gear in your menu bar (*see below*). If you don't, you probably missed it and it's done it's job correct.

![Spinning Gear icon](https://user-images.githubusercontent.com/3734562/43505464-5de2cb24-95aa-11e8-9066-af6e14718ea1.png "Spinning Gear icon")

## Additional Information

In almost every case you should use **Reset QuickLook (and Reset Disk Cache)**. If you know what you're doing, and you don't wish to clear the cache, use **Reset QuickLook**.

|: Workflow                              |: Command            |: Function                       |
| -------------------------------------- | ------------------- | ------------------------------- |
| Reset QuickLook                        | `qlmanage -r`       | Force reloading Generators list |
| Reset QuickLook (and Reset Disk Cache) | `qlmanage -r cache` | Reset thumbnail disk cache      |
