# QuickLookFixer

Force reloading of Generators list, and optionally reset the thumbnail disk cache too.

This repository includes two downloadable files: "**Reset QuickLook**" and "**Reset QuickLook (and Reset Disk Cache)**".

## Installation

1. Download latest zip [**here**](https://github.com/n0mar/QuickLookFixer/releases).

2. Uncompress zip file

3. Open `.workflow` file/s. You will be prompted with the dialogue below.

  Selecting **Install** will **move** the workflow (**not copy**) to `~/Library/Services/`; **Open with Automator** will allow you to see the [source code for the workflow](https://github.com/n0mar/QuickLookFixer#additional-information).

![Installation Dialogue](https://user-images.githubusercontent.com/3734562/43505869-942ba9f2-95ab-11e8-8e91-521bf44bd88f.png "Installation dialogue")

# Usage

1. Once installed, click the App Name in the top menu bar (e.g. **Finder**, **Safari**, **iTunes**).

2. Open the **Services** menu.

3. Click on your desired workflow.

4. You may see a spinning gear in your menu bar (*see below*). If you don't, it was probably too quick for you to notice, and it's already completed the task.

![Spinning Gear icon](https://user-images.githubusercontent.com/3734562/43506591-e1756ebc-95ad-11e8-953f-e08c701773a0.png "Spinning Gear icon")

## Additional Information

In almost every case you should use **Reset QuickLook (and Reset Disk Cache)**. If you know what you're doing, and you don't wish to clear the cache, use **Reset QuickLook**.

| Workflow                               | Command             | Function                        |
| -------------------------------------- | ------------------- | ------------------------------- |
| Reset QuickLook                        | `qlmanage -r`       | Force reloading Generators list |
| Reset QuickLook (and Reset Disk Cache) | `qlmanage -r cache` | Reset thumbnail disk cache      |
