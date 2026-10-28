# D2R Multigate Launcher

By **celloboy126**, with Codex.

Download the **Setup.exe** from [Releases](https://github.com/celloboy126/D2R-Multigate-Launcher/releases/latest)
and install, or extract the portable ZIP and run **D2RMultigateLauncher.exe**.
The Windows x64 package is self-contained and includes its language packs and
lowHD/QoL mod packages; no separate .NET or AutoHotkey installation is needed.
The launcher requests administrator permission for its game-window operations.

The five bundled mod packages match the checksum-verified downloads at
https://github.com/celloboy126/lowHD/releases/tag/v2026.10.27.

Add accounts, configure their region and launch arguments in Details, and launch
them individually or in batches. Configure opens the expandable settings. The
language selector stays at the lower right. Appearance offers Ember, Portal,
Moonlight and Forest palettes. The credits and contact details are under About.

Settings remain in `%APPDATA%\D2RSuite\Preview`. Updates and uninstalling the
launcher preserve them. Credentials use the current Windows user's protection;
copying a profile to another Windows user or computer does not transfer its login
secrets. The installer writes the launcher only; game mods and extracted game
data change only through the corresponding launcher operations.

Both built-in online make/join modes check visible game screens. Learning uses
small-region pixel/pattern checks and occasional local OCR. Custom deterministic
macros are available. No game-process memory is read or written, and no game code
is injected. This does not constitute Blizzard approval or guarantee that any
automated input or broadcasting feature is exempt from enforcement. Read How
scripts operate in Configure and choose which features you use.

Offline make-game is separate: select Offline Hell, Offline Nightmare or Offline
Normal. Normal sends Enter only, for a character without a difficulty selector.
Switch back to Online before using an online character.

Support travel currently depends on tested English game UI at 1920 × 1200 with
the normal centered automap and adequate brightness. Unsupported or uncertain
routes stop rather than continuing blindly. Some routes and unusual layouts are
still being tested. Act I outside-town travel is enabled only for validated
layouts; Act IV outside-town is supported. Other outside-town routes are not
available. These support restrictions do not describe make/join's broader
calibration support. Language packs include translated advanced operating help;
community review is welcome and untranslated messages fall back to English.

The launcher checks for updates on startup and shows brief change notes before
installation. Updates require a manifest signed by the project's embedded public
key and a matching installer SHA-256. This authenticates updates; it is separate
from Windows Authenticode signing. Windows may show **Unknown publisher** because
the installer does not have a commercial Windows signing certificate. No security
settings need to be disabled. Download the initial copy only from this project's
official releases.

Keep the launcher folder separate from the game's folders. Uninstall removes
installed launcher files and shortcuts, not
your saved profiles, game installation, installed mods or extracted game data.

Public project: https://github.com/celloboy126/D2R-Multigate-Launcher

Discord: **celloboy126** · https://discord.com/users/754143383978508379

Optional support: https://venmo.com/celloboy126

Third-party component notices are included in `licenses`.
