+++
title = ''
date = 2023-12-21T22:53:23+01:00
draft = false
+++

# WiiUDownloader
A free and open source Wii U NUS Downloader.

## Introduction

WiiUDownloader is a free and open-source tool designed to simplify the process of downloading Wii U games, updates, DLC, demos, and more. With a user-friendly interface and powerful features, it's your go-to solution for accessing and enjoying Wii U content effortlessly.

## Screenshots
{{< cards >}}
  {{< card image="images/WiiUDownloaderMainScreenshot.png" >}}
  {{< card image="images/WiiUDownloaderSearchScreenshot.png" >}}
  {{< card image="images/WiiUDownloaderDownloadingScreenshot.png" >}}
{{< /cards >}}

## Features

- Browse and search for Wii U games, updates, DLC, demos, and more.
- Download selected titles or queue multiple titles for batch download.
- Decrypt downloaded contents for use on emulator (optional).
- Delete encrypted contents after decryption (optional).
- Filter titles based on name or title ID.
- Select regions (Japan, USA, and Europe) to filter available titles.

## Downloads

To get started WiiUDownloader, download the appropriate binary for your operating system from the links below:

- [Linux (AppImage)](https://github.com/Xpl0itU/WiiUDownloader/releases/latest/download/WiiUDownloader-Linux-x86_64.AppImage)
- [macOS](https://github.com/Xpl0itU/WiiUDownloader/releases/latest/download/WiiUDownloader-macOS-Universal.dmg)
- [Windows](https://github.com/Xpl0itU/WiiUDownloader/releases/latest/download/WiiUDownloader-Windows.zip)

For Linux, you may need to give execution permission to the downloaded binary:

```bash
chmod +x WiiUDownloader-Linux-x86_64.AppImage   # For Linux
```

## Usage

To use WiiUDownloader, follow these steps:

1. Double-click the downloaded binary to launch WiiUDownloader.
2. The WiiUDownloader window will appear, showing a list of available Wii U titles.
3. Use the search bar to filter titles by name or title ID.
4. Click on the category buttons to filter titles by type (Game, Update, DLC, Demo, All).
5. Click on the checkboxes to select the desired region(s) for filtering (Japan, USA, Europe).
6. Click on the "Add to queue" button to add selected titles to the download queue. The button label will change to "Remove from queue" if titles are already in the queue.
7. Click on the "Download queue" button to choose a location to save the downloaded games. The program will start downloading the queued titles.
8. If you enable "Decrypt contents," the program will decrypt the downloaded files. You can also choose to delete encrypted contents after decryption (optional).
9. If you already have downloaded files that aren't decrypted, you can go to Tools > Decrypt Contents and select the folder to decrypt.

## Discord Server

WiiUDownloader has a Discord server which you can join for help and feedback.
{{< discord id=1040977806496116848 >}}

## Support Me (Donations)

You can support me (the developer) through donations on Ko-Fi, which are really appreciated and help me a lot on developing new cool stuff.
{{< kofi >}}
