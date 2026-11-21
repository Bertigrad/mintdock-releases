<p align="center">
  <img src="img/banner.jpg" alt="Mintdock — a light, macOS-style dock for Windows 11" width="100%">
</p>

<p align="center">
  <a href="../../releases/latest"><img src="https://img.shields.io/github/v/release/Bertigrad/mintdock-releases?label=download&style=for-the-badge&color=6d3df5" alt="Download the latest version"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Windows%2011-x64-0078D4?style=flat-square" alt="Windows 11 x64">
  <img src="https://img.shields.io/badge/RAM-~15%20MB-6ee7b7?style=flat-square" alt="About 15 MB of RAM">
  <img src="https://img.shields.io/badge/no%20admin%20rights-needed-6ee7b7?style=flat-square" alt="No administrator rights needed">
  <img src="https://img.shields.io/badge/updates-signed-6ee7b7?style=flat-square" alt="Signed updates">
  <img src="https://img.shields.io/badge/English%20%C2%B7%20T%C3%BCrk%C3%A7e%20%C2%B7%20Deutsch-informational?style=flat-square" alt="English, Türkçe, Deutsch">
</p>

<p align="center">
  <b>English</b> · <a href="#türkçe">Türkçe</a> · <a href="#deutsch">Deutsch</a>
</p>

**Mintdock** replaces the Windows taskbar with a floating, glassy dock: your apps on the left, live tiles for music,
weather, calendar, system and more on the right. It is a native app, so it stays light: about **15 MB of memory** and
almost no CPU while idle — no browser engine, no .NET.

<p align="center"><img src="img/features.jpg" alt="Liquid Glass, Magnify, Quick search, Live tiles, Any screen edge, ~15 MB RAM" width="760"></p>

## A look inside

<table>
  <tr>
    <td width="50%"><img src="img/dock-dark.jpg" alt="The dock in the dark style"><br><sub><b>Liquid Glass</b> — the dock and every panel pick up your wallpaper.</sub></td>
    <td width="50%"><img src="img/dock-light.jpg" alt="The dock in the light style"><br><sub><b>Light, dark, black or midnight</b> — or follow Windows.</sub></td>
  </tr>
  <tr>
    <td><img src="img/settings.jpg" alt="Settings with a category sidebar"><br><sub><b>Make it yours</b> — accents, presets, corners and glass tint.</sub></td>
    <td><img src="img/settings-search.jpg" alt="Searching the settings"><br><sub><b>Find any setting</b> by typing.</sub></td>
  </tr>
  <tr>
    <td><img src="img/quick-search.jpg" alt="Quick search"><br><sub><b>Quick search</b> — apps, windows, files, settings and sums.</sub></td>
    <td><img src="img/clipboard.jpg" alt="Clipboard history"><br><sub><b>Clipboard history</b> — kept in memory only, never on disk.</sub></td>
  </tr>
  <tr>
    <td><img src="img/calendar.jpg" alt="Calendar panel"><br><sub><b>Calendar</b> with your iCal events and usage reset days.</sub></td>
    <td><img src="img/vertical.jpg" alt="The dock on the left edge"><br><sub><b>Any edge, any screen</b> — bottom, top, left, right, or every monitor.</sub></td>
  </tr>
  <tr>
    <td><img src="img/magnify.png" alt="Magnify"><br><sub><b>Magnify</b> — icons grow under the pointer, like on a Mac.</sub></td>
    <td><img src="img/update.jpg" alt="Update ready notice"><br><sub><b>Signed updates</b> — downloaded in the background, installed when you say so.</sub></td>
  </tr>
</table>

## What you get

- **Dock:** pinned and running apps, unread badges (Discord, Outlook…), window previews, a richer right-click menu
  (jump-list tasks, recent files, run as administrator, close all windows), drag & drop, folder stacks.
- **Tiles:** clock & calendar, weather, music, network & sound, CPU & memory, storage, recycle bin, screen time, focus
  timer, notes, world clocks, Bluetooth battery, tray icons, notifications, Task Manager, clipboard.
- **Quick search** (opt-in shortcut), **window overview**, **Win+1…9**, auto-hide, hide from screen recordings.
- **Themes:** accent colours (or your Windows / wallpaper colour), presets, corners, glass tint; export and import
  your settings.
- **Three languages:** English, Türkçe, Deutsch.

## Install

<p align="center"><img src="img/installer.jpg" alt="The installer" width="620"></p>

1. Download `mintdock-<version>.exe` from the [latest release](../../releases/latest).
2. Run it and click **Install**. It installs for your account only — **no administrator rights** — and starts.
3. Windows may say *"Windows protected your PC"* because the app is not code-signed yet: click **More info → Run anyway**.

**Uninstall:** Settings → Apps → Installed apps → Mintdock. Your taskbar comes back right away.

## Privacy & updates

- No account, no telemetry, no ads. Network is used only for features you turn on (weather for a city you pick, your
  calendar links, GitHub / Claude / Codex usage tiles) and the daily update check against this repository.
- Every update is checked before it is installed: the manifest `latest.json` must carry a valid ECDSA P-256 signature
  (`latest.json.sig`) from the release key built into the app, and the download must match its size and SHA-256.
- To check a download by hand: `Get-FileHash .\mintdock-<version>.exe -Algorithm SHA256` and compare with `SHA256SUMS`.

## Requirements

Windows 11, 64-bit. Nothing else to install. A GPU is only used if you turn on the glass effect.

---

## Türkçe

**Mintdock**, Windows görev çubuğunun yerine geçen, havada duran cam görünümlü bir dock: solda uygulamaların, sağda
müzik, hava durumu, takvim, sistem ve daha fazlası için canlı kutucuklar. Yerel bir uygulama olduğu için çok hafif:
boşta yaklaşık **15 MB bellek** ve neredeyse sıfır işlemci.

- **İndir:** [son sürümden](../../releases/latest) `mintdock-<sürüm>.exe` dosyasını indirip çalıştırın ve **Kur**'a basın.
  Yalnızca sizin hesabınıza kurulur, **yönetici izni gerekmez**.
- Windows *"Bilgisayarınız korundu"* derse (uygulama henüz kod imzalı değil): **Ek bilgi → Yine de çalıştır**.
- **Kaldırma:** Ayarlar → Uygulamalar → Mintdock. Görev çubuğunuz hemen geri gelir.
- **Güncellemeler** günde bir kez denetlenir, arka planda indirilir ve yalnızca imzası doğrulanırsa, siz onaylayınca
  kurulur. Hesap, takip veya reklam yoktur.

## Deutsch

**Mintdock** ersetzt die Windows-Taskleiste durch ein schwebendes Dock im Glas-Look: links Ihre Apps, rechts Live-Kacheln
für Musik, Wetter, Kalender, System und mehr. Als native App bleibt es leicht: im Leerlauf etwa **15 MB Speicher** und
kaum CPU.

- **Download:** Laden Sie aus dem [neuesten Release](../../releases/latest) `mintdock-<Version>.exe` herunter, starten Sie
  es und klicken Sie auf **Installieren**. Die Installation erfolgt nur für Ihr Konto, **ohne Administratorrechte**.
- Meldet Windows *„Der Computer wurde durch Windows geschützt“* (noch keine Code-Signatur): **Weitere Informationen →
  Trotzdem ausführen**.
- **Deinstallieren:** Einstellungen → Apps → Mintdock. Die Taskleiste ist sofort wieder da.
- **Updates** werden einmal täglich geprüft, im Hintergrund geladen und nur mit gültiger Signatur nach Ihrer Zustimmung
  installiert. Kein Konto, kein Tracking, keine Werbung.
