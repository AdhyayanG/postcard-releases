# POSTCARD

A Windows desktop browser with a personal, local-first internet journal. Browse as usual, press **FILE PAGE** (Ctrl+D) to keep a page with its snapshot and a note in a dated entry, and read your entries back as a scrapbook or a magazine.

This repository holds the installers only.

## Download

Get `POSTCARD-Setup-<version>.exe` from the [latest release](https://github.com/AdhyayanG/postcard-releases/releases/latest) and run it. Windows 10 or 11, 64-bit.

The installer is not code-signed yet, so Windows SmartScreen shows "Windows protected your PC". Choose **More info**, then **Run anyway**.

## Good to know

- **Your journal stays on your PC.** No account, no sync, no analytics. Settings → Back up journal copies everything into a folder you choose.
- **Updates install themselves.** POSTCARD checks this page for a new version, downloads it in the background and installs it the next time you quit.
- **Google sign-in does not work.** Google refuses sign-in from browsers built on Electron. YouTube, Maps and Search work signed out; use Gmail and Drive in another browser or a mail app.
- **Uninstalling** (Settings → Apps → POSTCARD) keeps your journal in `%APPDATA%\POSTCARD`.
