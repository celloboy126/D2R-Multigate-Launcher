# D2R Multigate Launcher

Launch and manage your D2R accounts, share configurable macros, and set up
lowHD/QoL mods from one self-contained Windows tool.

By **celloboy126**, with Codex.

**[Download the latest release](https://github.com/celloboy126/D2R-Multigate-Launcher/releases/latest)**
— choose **Setup.exe** to install or **Portable.zip** to extract and run.

**New in 0.17.9: [Secure online Make/Join](#new--secure-online-makejoin) · [한국어 빠른 설정](#한국어-빠른-설정)**

## lowHD / QoL mod downloads

**Last updated: November 11, 2026.** Download the standalone mods from the **[lowHD/QoL release Assets](https://github.com/celloboy126/lowHD/releases/tag/v2026.11.11.2)**: [main](https://github.com/celloboy126/lowHD/releases/download/v2026.11.11.2/lowHDmain.zip), [filler](https://github.com/celloboy126/lowHD/releases/download/v2026.11.11.2/lowHDfiller.zip), [min](https://github.com/celloboy126/lowHD/releases/download/v2026.11.11.2/lowHDmin.zip), [partial](https://github.com/celloboy126/lowHD/releases/download/v2026.11.11.2/lowHDpartial.zip), or [QoL](https://github.com/celloboy126/lowHD/releases/download/v2026.11.11.2/QoL.zip). The launcher bundles all five variants. Its lowHDmin includes the Escape-menu fixes described below.

**November 11 refresh:** Includes the latest lowHDmain and lowHDpartial files. All five variants include the gold screen and panel badges and rectangular player-count markers.

## Interface previews

These previews are rendered from the actual interface with **fictional accounts
and sample TZ/D-Clone values**. Running statuses are simulated for demonstration.
No personal account information, private settings or live game screenshots are shown.

| Ember | Portal |
| --- | --- |
| [![Ember palette: sample account batch and compact TZ/D-Clone panel](screenshot-ember.png)](screenshot-ember.png) | [![Portal palette with pink and violet accents](screenshot-portal.png)](screenshot-portal.png) |
| **Moonlight** | **Forest** |
| [![Moonlight palette with cool blue accents](screenshot-moonlight.png)](screenshot-moonlight.png) | [![Forest palette with brown and green accents](screenshot-forest.png)](screenshot-forest.png) |

Click an image to view it at full size. Accounts can launch individually or in
batches; batch members are highlighted without changing the row layout.

<details>
<summary><strong>See Make/Join and support configuration</strong></summary>

The following panels show generic demo/default settings, not an author's profile.

![Make/Join configuration, online/offline modes and game-number defaults](screenshot-make-join.png)

![BO barbarian and enchantress configuration with fictional accounts](screenshot-support.png)

</details>

## Features

- Individual and batch account launching, region selection and shared macros.
- Configurable hotkeys, broadcasting, held input and live clickable thumbnails.
- Online make/join, follow, benching, exclusions and automatic or dedicated offline entry.
- BO support, positioning-only Enchantress and parking, with guarded visual recognition.
- Compact TZ/D-Clone information from [d2emu.com](https://d2emu.com).
- Bundled lowHDmain, lowHDfiller, lowHDmin, lowHDpartial and QoL mods.
- Four dark palettes, twenty interface languages and project-verified updates.

## New in 0.17.9

### New · Secure online Make/Join

**Enable it in Configure → Make / join → Make-game target → Online · secure panels.** This opt-in mode uses the in-game Party/Create and Help/Join panels supplied by the current bundled lowHD and QoL mods. Panel clients send keyboard shortcuts and paste the fields without OCR, badge checks, or screen captures.

1. Start each participating character in an online game with panels closed. From the title screen, you can use Broadcast to advance the accounts manually together, then turn Broadcast off.
2. In Make / join, match **Party panel hotkey** and **Help panel hotkey** to your in-game bindings. The defaults are **P** and **H**. You can also enable **Use the regular lobby workflow for the active host** for faster hosting.
3. Turn on Follow and press **Ctrl+Space**. Enter the exact destination game name and password the first time. Later presses increment and paste the full name. **Ctrl+J** brings followers into the last requested game. **Ctrl+Shift+Space** clears the session details so the next Ctrl+Space asks again.
4. Check the thumbnails or player count for arrivals. Secure panel clients submit the request without verifying that the server accepted it.

The panel interval is adjustable and defaults to 250 ms. Follower grace, stagger, parallel preparation, exclusions, and benching still apply. Routine Ctrl+Space overlays can be turned off while errors and reset messages remain visible.

### 한국어 빠른 설정

**설정 → 방 만들기 / 참가 → 방 만들기 방식 → 온라인 · 안정 모드 (패널)**을 선택하세요.

- 최신 lowHD 또는 QoL 모드를 사용하고, 참여할 캐릭터를 모두 온라인 방에 입장시킨 뒤 패널을 닫아 주세요. 타이틀 화면에서 시작한다면 브로드캐스트로 함께 입장한 뒤 브로드캐스트를 끄면 됩니다.
- **파티 패널 단축키**와 **도움말 패널 단축키**를 게임 설정과 맞추세요. 기본값은 **P**와 **H**입니다. 방장만 기존 대기실 방식으로 진행하도록 설정할 수도 있습니다.
- 따라가기 기능을 켜고 **Ctrl+Space**를 누르세요. 처음에는 만들거나 참가할 방 이름과 비밀번호를 직접 입력합니다. 이후에는 방 번호가 자동으로 올라갑니다. **Ctrl+Shift+Space**를 누르면 다음 Ctrl+Space에서 방 정보를 다시 입력할 수 있습니다.
- 패널 방식은 화면을 읽거나 입장 성공 여부를 확인하지 않습니다. 썸네일 또는 방 인원수로 입장을 확인해 주세요.

### Other improvements

- First in-game arrival now has up to 15 seconds for confirmation in regular Make/Join. Successful arrivals still advance immediately.
- Make/Join settings place follower grace and stagger side by side. Diagnostics remain available next to the language selector.
- Updated translations for secure Make/Join, related settings, and status messages, with a dedicated Korean wording pass.

## New in 0.17.8

- Fixed the bundled lowHDmin Escape menus so Save and Exit is selected by default and all Garden menu buttons share one keyboard focus group. Also corrected large-font party badge scaling and unavailable waypoint labels in lowHDmin.
- Improved follower exits for Ctrl+Space and Ctrl+J. The launcher checks that the Escape menu is open and Save and Exit is selected before submitting. A follower that cannot exit no longer prevents the others from joining.
- Reduced unnecessary waiting before follower preparation and added optional spacing between follower join submissions. Spacing defaults to off.
- Title-screen followers now use timed background keyboard input. Background Enter temporarily releases held Ctrl, Shift, and Alt. Diagnostics record title input and focus changes.

If you already have lowHDmin installed, apply the refreshed mod from the launcher and restart the affected Diablo II: Resurrected windows to load the updated layouts.

## New in 0.17.7

- Password verification now reads the full lobby field so a small first asterisk near the edge can be counted. With OCR enabled, the count must match the pasted password length.
- Added **Use OCR for game text** under Make/Join, enabled by default. Turning it off skips OCR reads and uses badge, clipboard, and pixel checks where available.
- Diagnostics now test Windows OCR on a generated image and report whether it was read correctly.

## New in 0.17.6

- Lobby joins verify that the password paste registered. D2R validates the actual password.
- Ctrl+J tries the saved password even if the on-screen mask appears to have a different number of characters.
- Parking can recognize the requested game by its name and password presence when the exact mask count is unclear. Repeat joins still reuse previously verified passwords.

## New in 0.17.5

- Follow uses the configured default game password when one is saved, even if the main account's lobby password field looks empty. The main account's Create password is left as entered.
- Ctrl+J's game-name recovery verifies the paste before returning focus to the main account.
- Launcher updates can refresh QoL already applied to extracted Direct-mode data. Enable bundled-mod updates and **Keep bundled QoL applied when updating**, then close all D2R windows.

## New in 0.17.4

- Followers and parked accounts reuse the lobby password after a successful join when the next game uses the same password. This skips focusing, pasting into, and checking the password field on repeat joins.
- First joins and password changes still verify the field. A join error resets reuse so the next attempt can enter the password again.
- Bundled lowHDmain files match the current mod. The [standalone mod downloads](https://github.com/celloboy126/lowHD/releases/tag/v2026.11.11.2) are unchanged.

## New in 0.17.3

- Fixed a clipboard timing issue that could paste a verification marker into the lobby game-name field.
- Verifies password entry before submitting and overlaps password-field checks across followers. A single follower has no extra fixed wait.
- Bundles the latest lowHDmain and lowHDpartial files alongside lowHDfiller, lowHDmin and QoL. All five match the [standalone mod downloads](https://github.com/celloboy126/lowHD/releases/tag/v2026.11.11.2).

## New in 0.17.2

- Updated lowHDmain and lowHDpartial packages.
- More reliable BO waypoint arrival recognition, with A, X and E as the default shout keys for new setups.
- BO casts and waypoint interactions wait for held modifiers. Outside-town waypoint opening tries a background click.

## New in 0.17.0

- Badge-first screen/panel recognition and compact player counters across all bundled mods, with legacy fallbacks.
- Automatic online/offline make-game detection, a separate preferred offline difficulty, and faster confirmed offline entry. Online lobby difficulty stays user-controlled.
- More reliable cold Ctrl+J game-name reading, panel cleanup, background startup and BO waypoint/shout handling.
- Refreshed lowHD/QoL downloads, updated translations, and make/join configuration refinements.

## New in 0.16.5

- More reliable screen recognition with outside thumbnails, short/wide windows and automatic layout recovery.
- Parking fixes for live maker/joiner changes, stale lobby fields, failed joins and support handoffs.
- Solo commands preserve unrelated accounts' idle states.
- Clearer diagnostics privacy wording and small About refinements.

## New in 0.16.4

- Private diagnostics and feedback, optional reviewed attachments, and replies in the launcher.
- Capture/calibration improvements for Windows 10 and different window borders/scaling.
- Faster active make/join startup and shared follower grace timing.
- Reliable reopening from shortcuts, expanded language packs, and clearer hotkey guidance.

## New in 0.16.3

- Per-account low-resource idle with automatic script/observer wake-up.
- More reliable autonomous parking, title-screen startup, and retries while waiting for the host.
- Live parking timing controls and cleaner account selection.
- Faster repeated follower joins and hardened waypoint-panel recovery.

## New in 0.16.2

- Optional clickable, highlighted account rows that replace the Details button; disabled by default.
- Game window titles can use the original title, launch number, or account label.
- Optional lowHDpartial expansion from already extracted game data; only missing files are copied.
- More reliable parking, improved support routes and background waypoint controls.
- All five November 5 mod packages bundled.

## Getting started

Install **Setup.exe**, or extract **Portable.zip** and run
**D2RMultigateLauncher.exe**. No separate .NET or AutoHotkey installation is needed.
The launcher requests administrator permission for its game-window operations.
Add accounts, set their region and arguments in Details, and launch individually
or by batch. Configure opens expandable settings; the language selector stays at
the lower right. Source-code archives generated automatically by GitHub are not
the launcher download. This public repository contains binaries and documentation.

The five bundled mod packages match the checksum-verified
[lowHD/QoL release](https://github.com/celloboy126/lowHD/releases/tag/v2026.11.11.2).

## Compatibility and script behavior

Both built-in online make/join modes check visible game screens. Learning uses
small-region pixel/pattern checks and occasional local OCR. Custom deterministic
macros are also available. No game-process memory is read or written, and no game
code is injected. This is not Blizzard approval or a guarantee against enforcement;
read **Configure → How scripts operate** and choose which features to use.

Support navigation has its strongest test coverage at **1920 × 1200**, with a readable normal centered automap and English game UI. Authored town-to-waypoint routes for Acts I–V and all waypoint destinations are enabled, along with Act I just outside town. Other resolutions and destinations still need wider community testing. Enchantress positioning can also stay in towns; **automatic Enchant casting remains disabled**. Changes wait for the next scripted game entry. Town waypoint opening and panel selection use background clicks; the game's own panel-opening cursor shift is immediately reversed. Older interaction fallbacks may briefly borrow the pointer. Unavailable acts/waypoints show an error and select Act I outside for the next game. Make/join has broader calibration support than support navigation.

Language packs include advanced operating help; community review is welcome and
untranslated messages fall back to English.

For offline play, select Offline Hell, Offline Nightmare or Offline Normal.
Normal sends Enter only for characters without a difficulty selector. Switch
back to Online before using an online character.

## Settings and updates

Settings remain in `%APPDATA%\D2RSuite\Preview`. Updates and uninstall preserve
them. Login secrets use the current Windows user's protection and do not transfer
automatically to another Windows account or computer. Game files change only
through the corresponding mod install or extracted-data operation.

The launcher checks for updates at startup and shows brief change notes. Updates
require a project-signed manifest and matching installer SHA-256. This is separate
from Windows Authenticode signing: Windows may show **Unknown publisher** because
there is no commercial Windows publisher certificate. Download the initial copy
only from this project's official releases; no security settings need disabling.
Uninstall removes launcher files and shortcuts, not profiles, game files or mods.

## Contact and credits

**Discord:** [celloboy126](https://discord.com/users/754143383978508379)
for suggestions, bug reports and language requests. Include version, mod,
resolution, action and error text; never post passwords, login tokens or profiles.

Built by celloboy126 on jsp / Nexus Mods / Traderie, with Codex. Inspired by
shupershuff's D2R launcher, Gimli's Tinymod, mininexus mod, numerous modders on
inven. Third-party notices are included in the package's `licenses`.

Optional support: [Venmo @celloboy126](https://venmo.com/celloboy126).



## Optional lowHDpartial expansion

After installing partial and extracting game data, use **Configure → lowHD / QoL mods → Copy extracted data into lowHDpartial**. The launcher previews missing-file count and disk space. It copies from `Data/global`, `Data/hd` and `Data/local`, preserving every existing partial asset, empty override and mod build marker. No other mod is expanded. Launch with `-mod lowHDpartial`; `-direct` is not needed. This can use tens of GB of additional disk space. A permitted bundled-mod update replaces the mod folder, so update extracted data and repeat the copy afterward. Loading improvements depend on storage and the assets being used.
