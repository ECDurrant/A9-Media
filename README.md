# A9 Video Taker

A simple Windows app for saving videos your session can access.

**[Download A9 for Windows](https://github.com/ECDurrant/A9-Video-Taker/releases/latest/download/A9-Video-Taker.zip)** · **[Release notes](https://github.com/ECDurrant/A9-Video-Taker/releases/latest)**

## Start

1. Extract the ZIP into a folder. Keep all its files together.
2. Open **A9 Video Taker.exe**.
3. Paste a video link, choose Auto or a quality, and click **Download**.

Paste multiple links to make a queue. **Open video** plays a saved result.
**Stop** pauses work; **Resume / retry** continues unfinished jobs.
If A9 opens a browser, play the video or sign in when needed. That separate
A9 browser profile remembers your sign-ins.

## Keep the downloaded app up to date

Open **Settings > Check A9 updates**. A9 checks this repository's latest release,
downloads a verified update and reopens at the same location. The app checks
for new releases automatically each day and asks before installing.

Updates preserve your preferences, queue, sign-ins and downloaded videos.
**Update video engine** separately refreshes site support.

For an update received as a file, use **Settings > Install update file** and
select the `.a9update` file from a release.

### Upgrading an older copy

Close A9. Download **A9-Updater.exe** and the `.a9update` file from the
[latest release](https://github.com/ECDurrant/A9-Video-Taker/releases/latest).
Open the updater, select your existing A9 folder, and select the update file.
Future updates can be installed inside A9.

## Privacy and compatibility

Preferences, browser sessions, queue and videos stay on your computer. They
are not included in release downloads. No telemetry is included.

Some sites require an ordinary login or CAPTCHA interaction. DRM-protected
streams and content your session cannot access cannot be saved by A9.
The app uses [yt-dlp](https://github.com/yt-dlp/yt-dlp) and
[FFmpeg](https://ffmpeg.org/).

This repository distributes the Windows app and release notes.
