# IET Download Manager — notice of modification

IET Download Manager is a modified version of **Mister Download Manager**
(<https://github.com/anefzaoui/misterdownloadmanager>), copyright (C) 2026 Ahmed Nefzaoui and
its contributors, released under the GNU General Public License, version 3 or later
(see [LICENSE](LICENSE)). This modified version is released under the same licence.

Forked from upstream commit `a156528` (version 0.5.2) on 2026-11-13.

## What this fork changed (2026-11-13)

- Renamed the program to "IET Download Manager" (abbreviated "IETDM") in the app, its
  translations, the command-line tools, the browser extension and the installers.
- Gave it its own program names (`ietdownloadmanager.exe`, `-cli`, `-nmhost`, `-mcp`), data
  folder (`%APPDATA%\ietdownloadmanager`), registry key (`HKCU\Software\IETDownloadManager`),
  single-instance lock, browser native-messaging host (`com.ietdownloadmanager.host`) and
  installer AppId, so it can be installed next to Mister Download Manager without touching it.
- Replaced the app icon with an original IET icon.
- Pointed problem reports, crash reports and the update check at this fork's own repository
  (`OWNER/ietdownloadmanager`, a placeholder until it is published) instead of upstream's.
- The About box credits the original project and author.

Links to upstream's website (help pages) and source are kept. Upstream's documentation in
`docs/` and `website/` is unchanged and still describes Mister Download Manager.
