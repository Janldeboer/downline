# Downline

![GitHub All Releases](https://img.shields.io/github/downloads/stefnotch/downline/total.svg)

[Downline](https://stefnotch.github.io/downline/) is a free, cross-platform desktop application for downloading video and audio from YouTube and many other sites. It is a frontend for youtube-dl. Works on Windows, MacOS and Linux.

[Check out the other youtube-dl GUIs here](https://www.reddit.com/r/youtubedl/wiki/info-guis), I personally quite recommend [this one](https://github.com/jely2002/youtube-dl-gui)

**Download the latest version [here](https://github.com/stefnotch/downline/releases/latest)**.

Sweet, [Microsoft is shipping Webview2 with more and more Windows 10 machines](https://blogs.windows.com/msedgedev/2022/06/27/delivering-the-microsoft-edge-webview2-runtime-to-windows-10-consumers/). Downline updates incoming hopefully soon.

## Screenshots

<p align="center">
  <img src="https://user-images.githubusercontent.com/23068820/52162513-f5db9a00-26fa-11e9-8cca-964d921f3bf3.png" alt="screenshots" width="460"/>
</p>

## Features

- Works for links from [several sites](https://ytdl-org.github.io/youtube-dl/supportedsites.html)
- Choose audio and video quality (with support for 4K videos)
- Convert audio to multiple formats `(mp3, aac, m4a and more)`
- Convert video to multiple formats `(mp4, webm, mkv)`
- Pause and resume downloads
- Download entire playlist and channel
- Download and embed subtitles
- Download multiple files simultaneously

### Coming Soon

- More file naming options
- Display errors
- And more

To support this project, you can [donate to the developer](https://www.paypal.com/donate?hosted_button_id=U8D5FNF9JSUFU).

## Developer Instructions

After downloading the source code and having installed all the [prerequesites for your system](https://tauri.studio/en/docs/getting-started/intro)

Install dependencies:

```
npm install
```

Running the app in development mode (so you can edit without having to restart the app everytime):

```
npm run dev
```

Note that it may take over a minute the first time you try this out

### Build Instructions

1. [Install the prerequesites for your system](https://tauri.app/v1/guides/getting-started/prerequisites)
2. `npm install`
3. `npm run build`

When publishing a new release, don't forget to update
- package.json
- tauri.conf.json
- store.ts migration
- https://github.com/stefnotch/downline/tree/gh-pages

## Credits

- [youtube-dl](https://github.com/ytdl-org/youtube-dl/)
- [yt-dlp](https://github.com/yt-dlp/yt-dlp)
- [ffmpeg](https://ffmpeg.org/)
- [tauri](https://tauri.studio/)
- [vuejs](https://vuejs.org/)
- [esbuild](https://github.com/evanw/esbuild)
- [vite tauri template](https://github.com/yooneskh/vite-tauri-template)

## Legal

This software is distributed under the [MIT license](https://github.com/stefnotch/downline/blob/master/LICENSE).
