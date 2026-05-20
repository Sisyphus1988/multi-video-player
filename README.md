# Multi Video Player

A lightweight local multi-video player built as a single HTML file.

It is designed for quickly opening, previewing, and controlling multiple local videos in one page without any backend service.

## Features

- Open multiple local video files at once
- Import a whole folder with `webkitdirectory`
- Drag and drop files or folders into the page
- Play, pause, mute, unmute, and remove videos independently
- Batch controls for all loaded videos
- Fullscreen and Picture-in-Picture support
- Per-video playback speed control and speed presets
- Search videos by filename
- Progress tooltip, buffered progress, and time display
- Metadata display for resolution and file size
- Keyboard shortcuts for common playback actions
- Responsive grid layout for multi-instance viewing

## Tech Stack

- Plain HTML
- Plain CSS
- Vanilla JavaScript

## Usage

1. Open `multi-video-player.html` in a Chromium-based browser.
2. Click to choose video files, or choose a folder.
3. You can also drag local files or folders into the page.
4. Control each video independently or use the toolbar for batch actions.

## Browser Notes

- Folder import depends on `webkitdirectory`, so Chromium-based browsers work best.
- Folder drag-and-drop recursion also relies on Chromium-specific APIs.
- Picture-in-Picture and some media behaviors may vary by browser.

## Project Structure

```text
multi-video-player.html
README.md
README_CN.md
```

## Status

This project is currently a small personal utility and is being iterated as a lightweight frontend-only tool.

## Chinese Documentation

See [README_CN.md](./README_CN.md).

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Sisyphus1988/multi-video-player&type=Date)](https://star-history.com/#Sisyphus1988/multi-video-player&Date)
