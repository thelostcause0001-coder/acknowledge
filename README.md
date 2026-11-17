# Acknowledge

A free, local-first video editor: multi-track timeline, colour tools, captions, keyframes and on-device MP4 export. No account, subscription or watermark.

## Windows

[Download the latest Windows installer](https://github.com/thelostcause0001-coder/acknowledge/releases/latest/download/Acknowledge_0.1.0_x64-setup.exe) (Windows 10/11, 64-bit, about 10 MB).

The build is not code-signed, so Windows SmartScreen may ask you to confirm before running it.

## Building the installer

Open **Actions → Build Windows release → Run workflow**. The workflow runs on GitHub's Windows runner, fetches the app source bundle from the landing page, installs dependencies, downloads the FFmpeg core, and builds the Tauri installer with NSIS. A successful run publishes a new release.

Built with React, Vite, TypeScript and Tauri 2.
