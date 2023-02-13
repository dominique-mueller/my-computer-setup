<div align="center">

# My Computer Setup

My personal computer setup, for Windows.

</div>

<br><br>

## Windows

Advanced configurations.

<br>

### Disable web search in start menu

1. Open Group Policy Editor (`gpedit`)
2. Navigate to "User Configuration" > "Administrative Templates" > "Windows Components" > "File Explorer"
3. Open "Turn off display of recent search entries in the File Explorer search box" policy (double click)
4. Select "Enabled", hit "Apply" and "OK"

<br><br>

## Apps

The following is a list of software I usually install on my computer.

| Name                            | Source                                                            | Description                                                                       |
| ------------------------------- | ----------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| **Google Chrome**               | [Website](https://www.google.com/intl/de_de/chrome)               | Primary browser                                                                   |
| **Microsoft PowerToys**         | [Store](https://apps.microsoft.com/store/detail/XP89DCGQ3K6VLD)   | Utilities                                                                         |
| **Process Lasso** (paid)        | [Website](https://bitsum.com)                                     | Mainly interesting for pinning CPU priorities / affinities                        |
| **7-Zip**                       | [Website](https://7-zip.org)                                      | File archiver (zip, rar, iso, ...)                                                |
| **Notepad++**                   | [Website](https://notepad-plus-plus.org/downloads)                | Universal file editor                                                             |
| **Media Player Classic**        | [Website](https://github.com/clsid2/mpc-hc)                       | The fastest media player (audio, video)                                           |
| **Google Drive for Desktop**    | [Website](https://www.google.com/intl/de/drive/download)          | Google Drive Sync                                                                 |
| **Microsoft 365 Single** (paid) | [Store](https://www.microsoft.com/store/apps/CFQ7TTC0K5BF)        | Good'old office (e.g. Word, Excel, PowerPoint, Outlook)                           |
| **Adobe Creative Cloud** (paid) | [Store](https://apps.microsoft.com/store/detail/XPDLPKWG9SW2WD)   | Adobe Creative Cloud (e.g. Photoshop, Lightroom, XD, After Effects, Premiere Pro) |
| **Paint.NET**                   | [Website](https://www.getpaint.net/download.html)                 | Simple photo editor, perfect for quickly compressing images                       |
| **Spotify**                     | [Store](https://www.microsoft.com/store/productId/9NCBCSZSJRSB)   | Spotify                                                                           |
| **ExpressVPN** (paid)           | [Website](https://www.expressvpn.com/de/vpn-software/vpn-windows) | VPN connection                                                                    |
| **OBS Studio**                  | [Store](https://apps.microsoft.com/store/detail/XPFFH613W8V6LV)   | Streaming / Recording                                                             |
| **Virtual Clone Drive**         | [Website](https://www.elby.ch/de/products/vcd.html)               | Mount images into the Explorer                                                    |
| **Discord**                     | [Store](https://apps.microsoft.com/store/detail/XPDC2RH70K22MN)   | Game Messaging                                                                    |
| **Whatsapp Desktop**            | [Store](https://www.microsoft.com/store/productId/9NKSQGP7F2NH)   | Private Messaging                                                                 |
| **Telegram Desktop**            | [Store](https://www.microsoft.com/store/productId/9NZTWSQNTD0S)   | Private Messaging                                                                 |
| **Slack**                       | [Store](https://www.microsoft.com/store/productId/9WZDNCRDK3WP)   | Work Messaging                                                                    |
| **Zoom**                        | [Store](https://apps.microsoft.com/store/detail/XP99J3KP4XZ4VV)   | Work Video Conferencing Client                                                    |
| **Microsoft Teams**             | [Store](https://apps.microsoft.com/store/detail/XP8BT8DW290MPQ)   | Work Messaging                                                                    |

<br>

### Paint.NET Plugins:

| Name            | Source                                                                                                                                    | Description                   |
| --------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------- |
| **IcoCur**      | [Website](https://forums.getpaint.net/topic/927-icon-cursor-and-animated-cursor-format-v37-may-2010/page/13/?tab=comments#comment-514467) | Adds support for `.ico` files |
| **SvgFileType** | [Website](https://github.com/otuncelli/Scalable-Vector-Graphics-Plugin-for-Paint.NET)                                                     | Adds support for `.svg` files |

> Plugins (`.dll` files) for file type support are placed into the `C:\Program Files\paint.net\FileTypes` folder

<br>

### Outlook: Disable Microsoft 365 connection when using on-premise Exchange setup

After setting up your Outlook e-mail address as per usual,

1. Open the Registry Editor (`regedit`)
2. Navigate to `HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\AutoDiscover`
3. Create a new "DWORD (32-bit) Value" with the name `ExcludeExplicitO365EndPoint` and the value `1`
4. Restart Outlook, possibly restart Windows

<br><br>

## Gaming Clients

The following is a list of software used for gaming purposes.

| Name                    | Source                                                            | Description             |
| ----------------------- | ----------------------------------------------------------------- | ----------------------- |
| **Battle.net Launcher** | [Website](https://www.blizzard.com/de-de/apps/battle.net/desktop) | Battle.net Client       |
| **Epic Games Launcher** | [Store](https://apps.microsoft.com/store/detail/XP99VR1BPSBQJ2)   | Epic Games Client       |
| **EA App**              | [Website](https://www.ea.com/games/library/pc-download)           | EA Gaming Client        |
| **Steam**               | [Website](https://store.steampowered.com/about)                   | Steam Gaming Client     |
| **Ubisoft Connect**     | [Store](https://apps.microsoft.com/store/detail/XPDP2QW12DFSFK)   | Ubisoft Gaming Client   |
| **GOG Galaxy 2.0**      | [Website](https://www.gog.com/galaxy)                             | GOG Galaxy 2.0 Launcher |

<br><br>

## Development

See **[my development setup](https://github.com/dominique-mueller/my-development-setup)**.
